##### 6.2.1.5 Testing Suite Evidence for Sprint Review

En esta sección se presenta la evidencia de las pruebas realizadas sobre el microservicio BC-Profiles (Profiles Bounded Context) durante el Sprint Review. Se aplicaron pruebas unitarias y de integración para validar el correcto funcionamiento de las capas Domain, Application e Interfaces del servicio.

###### Herramientas utilizadas

Para la ejecución de las pruebas se emplearon las siguientes herramientas y frameworks:

| Herramienta | Versión | Propósito |
|-------------|---------|-----------|
| xUnit | 2.9.x | Framework de testing para .NET, utilizado como base para la definición y ejecución de los tests |
| Moq | 4.20.x | Biblioteca de mocking para simular dependencias como repositorios y Unit of Work |
| FluentAssertions | 6.12.x | Librería de aserciones con sintaxis fluida para validaciones más expresivas y legibles |
| Microsoft.AspNetCore.Mvc.Testing | 9.0.x | Framework para pruebas de integración HTTP utilizando WebApplicationFactory |
| Microsoft.EntityFrameworkCore.InMemory | 9.0.x | Proveedor de base de datos en memoria para simular la persistencia sin depender de MySQL |
| .NET 9 SDK | 9.0.x | SDK utilizado para compilar y ejecutar el proyecto y los tests |

###### Unit Tests – Domain Layer

Se realizaron pruebas unitarias sobre el aggregate Profile del dominio para verificar la correcta construcción de entidades a partir de comandos y la inicialización por defecto de los Value Objects.

```csharp
using FluentAssertions;
using OsitoPolar.Profiles.Service.Domain.Model.Aggregates;
using OsitoPolar.Profiles.Service.Domain.Model.Commands;

namespace Profiles.API.Tests.Domain;

public class ProfileTests
{
    [Fact]
    public void Constructor_WithValidCommand_ShouldCreateProfile()
    {
        // Arrange
        var command = new CreateProfileCommand(
            "Diego", "Pérez", "diego@email.com",
            "Av. La Marina", "123", "Lima", "15088", "Perú");

        // Act
        var profile = new Profile(command);

        // Assert
        profile.FullName.Should().Be("Diego Pérez");
        profile.EmailAddress.Should().Be("diego@email.com");
        profile.StreetAddress.Should().Contain("Lima");
    }

    [Fact]
    public void DefaultConstructor_ShouldCreateEmptyProfile()
    {
        // Act
        var profile = new Profile();

        // Assert
        profile.FullName.Should().NotBeNull();
        profile.EmailAddress.Should().NotBeNull();
    }
}
```

Resultados obtenidos: Ambos tests se ejecutaron satisfactoriamente. Se verificó que el constructor del aggregate Profile crea correctamente la entidad a partir de un CreateProfileCommand, mapeando adecuadamente los Value Objects PersonName, EmailAddress y StreetAddress. Asimismo, el constructor por defecto inicializa los Value Objects sin valores nulos, garantizando la integridad del modelo de dominio.

###### Unit Tests – Application Layer (Command Service)

Se realizaron pruebas unitarias sobre ProfileCommandService utilizando mocks de IProfileRepository e IUnitOfWork para validar la lógica de creación de perfiles y el manejo de excepciones.

```csharp
using FluentAssertions;
using Moq;
using OsitoPolar.Profiles.Service.Application.Internal.CommandServices;
using OsitoPolar.Profiles.Service.Domain.Model.Aggregates;
using OsitoPolar.Profiles.Service.Domain.Model.Commands;
using OsitoPolar.Profiles.Service.Domain.Repositories;
using OsitoPolar.Profiles.Service.Shared.Domain.Repositories;

namespace Profiles.API.Tests.Application;

public class ProfileCommandServiceTests
{
    private readonly Mock<IProfileRepository> _mockProfileRepository;
    private readonly Mock<IUnitOfWork> _mockUnitOfWork;
    private readonly ProfileCommandService _service;

    public ProfileCommandServiceTests()
    {
        _mockProfileRepository = new Mock<IProfileRepository>();
        _mockUnitOfWork = new Mock<IUnitOfWork>();
        _service = new ProfileCommandService(
            _mockProfileRepository.Object,
            _mockUnitOfWork.Object);
    }

    [Fact]
    public async Task Handle_CreateProfileCommand_ShouldReturnProfile()
    {
        // Arrange
        var command = new CreateProfileCommand(
            "Diego", "Pérez", "diego@email.com",
            "Av. La Marina", "123", "Lima", "15088", "Perú");

        _mockProfileRepository
            .Setup(r => r.AddAsync(It.IsAny<Profile>()))
            .Returns(Task.CompletedTask);

        _mockUnitOfWork
            .Setup(u => u.CompleteAsync())
            .Returns(Task.CompletedTask);

        // Act
        var result = await _service.Handle(command);

        // Assert
        result.Should().NotBeNull();
        result!.FullName.Should().Be("Diego Pérez");
        _mockProfileRepository.Verify(r => r.AddAsync(It.IsAny<Profile>()), Times.Once);
        _mockUnitOfWork.Verify(u => u.CompleteAsync(), Times.Once);
    }

    [Fact]
    public async Task Handle_WhenRepositoryThrows_ShouldReturnNull()
    {
        // Arrange
        var command = new CreateProfileCommand(
            "Diego", "Pérez", "diego@email.com",
            "Av. La Marina", "123", "Lima", "15088", "Perú");

        _mockProfileRepository
            .Setup(r => r.AddAsync(It.IsAny<Profile>()))
            .ThrowsAsync(new Exception("Database error"));

        // Act
        var result = await _service.Handle(command);

        // Assert
        result.Should().BeNull();
    }
}
```

Resultados obtenidos: Los tests del ProfileCommandService se ejecutaron exitosamente. Se comprobó que el servicio invoca correctamente el repositorio y el Unit of Work durante la creación de un perfil, retornando la entidad creada. Adicionalmente, se validó que ante una excepción en la capa de persistencia, el servicio maneja el error de forma controlada retornando null, sin propagar la excepción al controlador.

###### Unit Tests – Application Layer (Query Service)

Se realizaron pruebas unitarias sobre ProfileQueryService para verificar la correcta delegación de consultas al repositorio y el manejo de resultados vacíos.

```csharp
using FluentAssertions;
using Moq;
using OsitoPolar.Profiles.Service.Application.Internal.QueryServices;
using OsitoPolar.Profiles.Service.Domain.Model.Aggregates;
using OsitoPolar.Profiles.Service.Domain.Model.Queries;
using OsitoPolar.Profiles.Service.Domain.Repositories;

namespace Profiles.API.Tests.Application;

public class ProfileQueryServiceTests
{
    private readonly Mock<IProfileRepository> _mockProfileRepository;
    private readonly ProfileQueryService _service;

    public ProfileQueryServiceTests()
    {
        _mockProfileRepository = new Mock<IProfileRepository>();
        _service = new ProfileQueryService(_mockProfileRepository.Object);
    }

    [Fact]
    public async Task Handle_GetAllProfilesQuery_ShouldReturnAllProfiles()
    {
        // Arrange
        var profiles = new List<Profile>
        {
            new("Diego", "Pérez", "diego@email.com", "Calle 1", "100", "Lima", "15000", "Perú"),
            new("Ana", "García", "ana@email.com", "Calle 2", "200", "Lima", "15001", "Perú")
        };

        _mockProfileRepository
            .Setup(r => r.ListAsync())
            .ReturnsAsync(profiles);

        // Act
        var result = await _service.Handle(new GetAllProfilesQuery());

        // Assert
        result.Should().HaveCount(2);
    }

    [Fact]
    public async Task Handle_GetProfileByIdQuery_WhenExists_ShouldReturnProfile()
    {
        // Arrange
        var profile = new Profile("Diego", "Pérez", "diego@email.com",
            "Calle 1", "100", "Lima", "15000", "Perú");

        _mockProfileRepository
            .Setup(r => r.FindByIdAsync(1))
            .ReturnsAsync(profile);

        // Act
        var result = await _service.Handle(new GetProfileByIdQuery(1));

        // Assert
        result.Should().NotBeNull();
        result!.FullName.Should().Be("Diego Pérez");
    }

    [Fact]
    public async Task Handle_GetProfileByIdQuery_WhenNotExists_ShouldReturnNull()
    {
        // Arrange
        _mockProfileRepository
            .Setup(r => r.FindByIdAsync(999))
            .ReturnsAsync((Profile?)null);

        // Act
        var result = await _service.Handle(new GetProfileByIdQuery(999));

        // Assert
        result.Should().BeNull();
    }
}
```

Resultados obtenidos: Todos los tests del ProfileQueryService pasaron correctamente. Se verificó que la consulta GetAllProfilesQuery retorna la totalidad de perfiles registrados, que GetProfileByIdQuery retorna el perfil correspondiente cuando existe en el repositorio, y que retorna null cuando el identificador consultado no corresponde a ningún registro existente.

###### Integration Tests – REST API Endpoints

Se realizaron pruebas de integración sobre los endpoints REST del ProfilesController utilizando WebApplicationFactory para instanciar el servidor de prueba y Microsoft.EntityFrameworkCore.InMemory como proveedor de base de datos en memoria, eliminando la dependencia con MySQL.

```csharp
using System.Net;
using System.Net.Http.Json;
using FluentAssertions;
using Microsoft.AspNetCore.Mvc.Testing;
using Microsoft.EntityFrameworkCore;
using Microsoft.Extensions.DependencyInjection;
using OsitoPolar.Profiles.Service.Infrastructure.Persistence.EFC.Configuration;

namespace Profiles.API.Tests.Integration;

public class ProfilesControllerIntegrationTests
    : IClassFixture<WebApplicationFactory<Program>>
{
    private readonly HttpClient _client;

    public ProfilesControllerIntegrationTests(
        WebApplicationFactory<Program> factory)
    {
        _client = factory.WithWebHostBuilder(builder =>
        {
            builder.ConfigureServices(services =>
            {
                var descriptor = services.SingleOrDefault(
                    d => d.ServiceType == typeof(DbContextOptions<ProfilesDbContext>));
                if (descriptor != null)
                    services.Remove(descriptor);

                services.AddDbContext<ProfilesDbContext>(options =>
                    options.UseInMemoryDatabase("TestDb"));
            });
        }).CreateClient();
    }

    [Fact]
    public async Task GetAllProfiles_ShouldReturnOk()
    {
        // Act
        var response = await _client.GetAsync("/api/v1/profiles");

        // Assert
        response.StatusCode.Should().Be(HttpStatusCode.OK);
    }

    [Fact]
    public async Task CreateProfile_WithValidData_ShouldReturnCreated()
    {
        // Arrange
        var createRequest = new
        {
            FirstName = "Diego",
            LastName = "Pérez",
            Email = "diego@test.com",
            Street = "Av. La Marina",
            Number = "123",
            City = "Lima",
            PostalCode = "15088",
            Country = "Perú"
        };

        // Act
        var response = await _client.PostAsJsonAsync("/api/v1/profiles", createRequest);

        // Assert
        response.StatusCode.Should().Be(HttpStatusCode.Created);
    }

    [Fact]
    public async Task GetProfileById_WhenNotExists_ShouldReturnNotFound()
    {
        // Act
        var response = await _client.GetAsync("/api/v1/profiles/999");

        // Assert
        response.StatusCode.Should().Be(HttpStatusCode.NotFound);
    }
}
```

Resultados obtenidos: Las pruebas de integración se ejecutaron satisfactoriamente. El endpoint GET /api/v1/profiles respondió con status code 200 OK, confirmando que el pipeline HTTP y la inyección de dependencias funcionan correctamente. El endpoint POST /api/v1/profiles respondió con 201 Created al recibir un payload válido, verificando el flujo completo desde el controller hasta la persistencia en memoria. Finalmente, el endpoint GET /api/v1/profiles/{id} respondió con 404 Not Found para un identificador inexistente, validando el manejo correcto de recursos no encontrados.

###### Resumen de ejecución del Testing Suite

| Test Class | Tests Ejecutados | Tests Pasados | Tests Fallidos | Cobertura |
|------------|:----------------:|:-------------:|:--------------:|:---------:|
| ProfileTests | 2 | 2 | 0 | Domain Layer |
| ProfileCommandServiceTests | 2 | 2 | 0 | Application Layer (Commands) |
| ProfileQueryServiceTests | 3 | 3 | 0 | Application Layer (Queries) |
| ProfilesControllerIntegrationTests | 3 | 3 | 0 | Interfaces Layer (REST) |
| Total | 10 | 10 | 0 | Todas las capas |

En conclusión, la suite de pruebas implementada para el microservicio BC-Profiles cubre las capas fundamentales de la arquitectura DDD adoptada. Las pruebas unitarias validan de forma aislada la lógica del dominio y los servicios de aplicación mediante el uso de mocks, mientras que las pruebas de integración verifican el comportamiento end-to-end de los endpoints REST con una base de datos en memoria. Los 10 tests ejecutados pasaron satisfactoriamente, lo cual demuestra que la funcionalidad implementada durante el sprint cumple con los criterios de aceptación definidos y que el microservicio mantiene la integridad esperada en sus operaciones de creación y consulta de perfiles.
