<div align="center">
  <img src="assets/UPC_logo_transparente.png" alt="UPCLOGO" width="100" height="100"><br><br>
  
  <h2>Universidad Peruana de Ciencias Aplicadas</h2>
  <h3>Carrera de Ingeniería de Software</h3>
  
  <br>
  
  <p><strong>1ASI0572</strong></p>
  <p><strong>Desarrollo de Soluciones IoT</strong></p>
  
  <br>
  
  <p><strong>NRC</strong></p>
  <p>6776</p>
  
  <br>
  
  <h2><strong>Informe del Trabajo Final</strong></h2>
  
  <br>
  
  <p><strong>Docente</strong></p>
  <p>León Baca, Marco Antonio</p>
  
  <br>
  
  <p><strong>Equipo</strong></p>
  <p>IA: Inteligencia Artesanal</p>
  
  <br>
  
  <p><strong>Proyecto</strong></p>
  <p>OsitoPolar</p>
  
  <br>
  
  <p><strong>Integrantes</strong></p>
  
  <table align="center">
    <tr>
      <th style="text-align:center;">Código</th>
      <th style="text-align:center;">Apellidos y Nombres</th>
    </tr>
    <tr>
      <td style="text-align:center;">U20231c069</td>
      <td style="text-align:center;">Mora Blas, Diego Alonzo</td>
    </tr>
    <tr>
      <td style="text-align:center;">U202223990</td>
      <td style="text-align:center;">Cacho Seminario, Diego Alonso</td>
    </tr>
    <tr>
      <td style="text-align:center;">U20231C996</td>
      <td style="text-align:center;">Hernandez Poma, Sebastian Eduardo</td>
    </tr>
    <tr>
      <td style="text-align:center;">U202210938</td>
      <td style="text-align:center;">Medina Cruzado, Raúl Adrian</td>
    </tr>
    <tr>
      <td style="text-align:center;">U20231C111</td>
      <td style="text-align:center;">Inga Orihuela, Christian Fabrizio</td>
    </tr>
  </table>
  
  <br><br><br>
  
  <p><strong>Período 202610</strong></p>
</div>



## Registro de Versiones del Informe


| Versión | Fecha      | Autor                | Descripción de modificación                                     |
|---------|------------|----------------------|-----------------------------------------------------------------|
| 1.0     | 23/04/2026 | Diego Cacho          | Implementación de datos del trabajo                             |
| 1.1     | 25/04/2026 | Sebastian Hernandez  | Adaptación de arquitectura IoT: integración de capa Edge API, ESP32 Firmware e IoT Monitoring Bounded Context al workspace Structurizr DSL. Generación de diagramas C4 (Context, Container, Components) y diagramas de base de datos para los 9 bounded contexts del sistema. |
| 1.2     | 25/04/2026 | Raúl Medina          |Actualizacion capitulo 4                                         |
| 1.3     | 25/04/2026 | Christian Inga          | Correcciones del informe                                     |
| 1.4     | 13/05/2026 | Christian Inga, Diego Cacho | Correcciones adicionales del informe                     |
| 1.5     | 13/05/2026 | Sebastian Hernandez         | Despliegue del Landing Page                              |
| 1.6     | 14/05/2026 | Sebastian Hernandez, Raúl Medina| Despliegue del Frontend App                          |
| 1.7     | 13/06/2026 | Diego Cacho             | Avance de documentacion                                      |
| 1.8     | 18/06/2026 | Diego Cacho             | Finalización del Mobile App                                  |
| 1.9     | 19/06/2026 | Diego Mora             | Finalización del IoT Component                                |

## Project Report Collaboration Insights *
- **URL de la organización del proyecto:**  
  [https://github.com/iot-proyectos](https://github.com/iot-proyectos)

- **URL del repositorio del informe del proyecto:**  
  [https://github.com/iot-proyectos/Report](https://github.com/iot-proyectos/Report)

  ![Insights Informe](assets/chapter01/insightsTB1.png)

- **URL del repositorio del landing page del proyecto:**  
  [https://github.com/iot-proyectos/LandingPage](https://github.com/iot-proyectos/LandingPage)

  ![Insights Landing](assets/chapter01/insightsLanding.png)

- **URL del repositorio del frontend del proyecto:**  
  [https://github.com/iot-proyectos/OsitoPolar-Frontend](https://github.com/iot-proyectos/OsitoPolar-Frontend)

  ![Insights Frontend](assets/chapter01/insightsFrontend.png)
  
<div style="page-break-after: always"></div>

## Contenido

- [Student Outcome](#student-outcome)

- [Capítulo I: Introducción](#capitulo-1-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1. Competidores](#21-competidores)
        - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
        - [2.3.1. User Personas](#231-user-personas)
        - [2.3.2. User Task Matrix](#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
        - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
    - [2.5. Ubiquitous Language](#25-ubiquitous-language)



- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)
    - [3.4. To-Be Scenario Mapping](#34-to-be-scenario-mapping)


- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
    - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
        - [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
            - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
            - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
            - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
        - [4.2.1. Bounded Context: IAM (Identity and Access Management)](#421-bounded-context-iam-identity-and-access-management)
            - [4.2.1.1. Domain Layer](#4211-domain-layer)
            - [4.2.1.2. Interface Layer](#4212-interface-layer)
            - [4.2.1.3. Application Layer](#4213-application-layer)
            - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
            - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
                - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
        - [4.2.2. Bounded Context: Profiles](#422-bounded-context-profiles)
            - [4.2.2.1. Domain Layer](#4221-domain-layer)
            - [4.2.2.2. Interface Layer](#4222-interface-layer)
            - [4.2.2.3. Application Layer](#4223-application-layer)
            - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
            - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
                - [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
        - [4.2.3. Bounded Context: Equipment Management](#423-bounded-context-equipment-management)
            - [4.2.3.1. Domain Layer](#4231-domain-layer)
            - [4.2.3.2. Interface Layer](#4232-interface-layer)
            - [4.2.3.3. Application Layer](#4233-application-layer)
            - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
            - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
                - [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
        - [4.2.4. Bounded Context: Service Requests](#424-bounded-context-service-requests)
            - [4.2.4.1. Domain Layer](#4241-domain-layer)
            - [4.2.4.2. Interface Layer](#4242-interface-layer)
            - [4.2.4.3. Application Layer](#4243-application-layer)
            - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
            - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams](#42461-bounded-context-domain-layer-class-diagrams)
                - [4.2.4.6.2. Bounded Context Database Design Diagram](#42462-bounded-context-database-design-diagram)
        - [4.2.5. Bounded Context: Work Orders](#425-bounded-context-work-orders)
            - [4.2.5.1. Domain Layer](#4251-domain-layer)
            - [4.2.5.2. Interface Layer](#4252-interface-layer)
            - [4.2.5.3. Application Layer](#4253-application-layer)
            - [4.2.5.4. Infrastructure Layer](#4254-infrastructure-layer)
            - [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams](#4256-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams)
                - [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram)
        - [4.2.6. Bounded Context: Analytics](#426-bounded-context-analytics)
            - [4.2.6.1. Domain Layer](#4261-domain-layer)
            - [4.2.6.2. Interface Layer](#4262-interface-layer)
            - [4.2.6.3. Application Layer](#4263-application-layer)
            - [4.2.6.4. Infrastructure Layer](#4264-infrastructure-layer)
            - [4.2.6.5. Bounded Context Software Architecture Component Level Diagrams](#4265-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.6.6. Bounded Context Software Architecture Code Level Diagrams](#4266-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.6.6.1. Bounded Context Domain Layer Class Diagrams](#42661-bounded-context-domain-layer-class-diagrams)
                - [4.2.6.6.2. Bounded Context Database Design Diagram](#42662-bounded-context-database-design-diagram)
        - [4.2.7. Bounded Context: Subscriptions and Payments](#427-bounded-context-subscriptions-and-payments)
            - [4.2.7.1. Domain Layer](#4271-domain-layer)
            - [4.2.7.2. Interface Layer](#4272-interface-layer)
            - [4.2.7.3. Application Layer](#4273-application-layer)
            - [4.2.7.4. Infrastructure Layer](#4274-infrastructure-layer)
            - [4.2.7.5. Bounded Context Software Architecture Component Level Diagrams](#4275-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.7.6. Bounded Context Software Architecture Code Level Diagrams](#4276-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.7.6.1. Bounded Context Domain Layer Class Diagrams](#42761-bounded-context-domain-layer-class-diagrams)
                - [4.2.7.6.2. Bounded Context Database Design Diagram](#42762-bounded-context-database-design-diagram)
        - [4.2.8. Bounded Context: Technicians](#428-bounded-context-technicians)
            - [4.2.8.1. Domain Layer](#4281-domain-layer)
            - [4.2.8.2. Interface Layer](#4282-interface-layer)
            - [4.2.8.3. Application Layer](#4283-application-layer)
            - [4.2.8.4. Infrastructure Layer](#4284-infrastructure-layer)
            - [4.2.8.5. Bounded Context Software Architecture Component Level Diagrams](#4285-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.8.6. Bounded Context Software Architecture Code Level Diagrams](#4286-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.8.6.1. Bounded Context Domain Layer Class Diagrams](#42861-bounded-context-domain-layer-class-diagrams)
                - [4.2.8.6.2. Bounded Context Database Design Diagram](#42862-bounded-context-database-design-diagram)


- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
    - [5.1. Style Guidelines](#51-style-guidelines)
        - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
        - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
    - [5.2. Information Architecture](#52-information-architecture)
        - [5.2.1. Organization Systems](#521-organization-systems)
        - [5.2.2. Labeling Systems](#522-labeling-systems)
        - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
        - [5.2.4. Searching Systems](#524-searching-systems)
        - [5.2.5. Navigation Systems](#525-navigation-systems)
    - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
        - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
        - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
    - [5.4. Applications UX/UI Design](#54-applications-uxui-design)
        - [5.4.1. Applications Wireframes](#541-applications-wireframes)
        - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
        - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
        - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
    - [5.5. Applications Prototyping](#55-applications-prototyping)
    - [5.6. IoT Device Design](#56-iot-device-design)
    - [5.7. Domain-Driven Software Architecture](#57-domain-driven-software-architecture)
        - [5.7.1. Software Architecture Context Diagram](#571-software-architecture-context-diagram)
        - [5.7.2. Software Architecture Container Diagrams](#572-software-architecture-container-diagrams)
        - [5.7.3. Software Architecture Components Diagrams](#573-software-architecture-components-diagrams)
    - [5.8. Software Object-Oriented Design](#58-software-object-oriented-design)
        - [5.8.1. Class Diagrams](#581-class-diagrams)
        - [5.8.2. Class Dictionary](#582-class-dictionary)
    - [5.9. Database Design](#59-database-design)
        - [5.9.1. Database Diagram](#591-database-diagram)


- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
    - [6.1. Software Configuration Management](#61-software-configuration-management)
        - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
        - [6.1.2. Source Code Management](#612-source-code-management)
        - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
        - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
    - [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
        - [6.2.1. Sprint 1](#621-sprint-1)
            - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
            - [6.2.1.2. Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
            - [6.2.1.3. Sprint Backlog 1](#6213-sprint-backlog-1)
            - [6.2.1.4. Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
            - [6.2.1.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
            - [6.2.1.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
            - [6.2.1.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
            - [6.2.1.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
            - [6.2.1.9. Team Collaboration Insights during Sprint](#6219-team-collaboration-insights-during-sprint)
        - [6.2.2. Sprint 2](#622-sprint-2)
            - [6.2.2.1. Sprint Planning 2](#6221-sprint-planning-2)
            - [6.2.2.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
            - [6.2.2.3. Sprint Backlog 2](#6223-sprint-backlog-2)
            - [6.2.2.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
            - [6.2.2.5. Testing Suite Evidence for Sprint Review](#6225-testing-suite-evidence-for-sprint-review)
            - [6.2.2.6. Execution Evidence for Sprint Review](#6226-execution-evidence-for-sprint-review)
            - [6.2.2.7. Services Documentation Evidence for Sprint Review](#6227-services-documentation-evidence-for-sprint-review)
            - [6.2.2.8. Software Deployment Evidence for Sprint Review](#6228-software-deployment-evidence-for-sprint-review)
            - [6.2.2.9. Team Collaboration Insights during Sprint](#6229-team-collaboration-insights-during-sprint)
        - [6.2.3. Sprint 3](#623-sprint-3)
            - [6.2.3.1. Sprint Planning 3](#6231-sprint-planning-3)
            - [6.2.3.2. Aspect Leaders and Collaborators](#6232-aspect-leaders-and-collaborators)
            - [6.2.3.3. Sprint Backlog 3](#6233-sprint-backlog-3)
            - [6.2.3.4. Development Evidence for Sprint Review](#6234-development-evidence-for-sprint-review)
            - [6.2.3.5. Testing Suite Evidence for Sprint Review](#6235-testing-suite-evidence-for-sprint-review)
            - [6.2.3.6. Execution Evidence for Sprint Review](#6236-execution-evidence-for-sprint-review)
            - [6.2.3.7. Services Documentation Evidence for Sprint Review](#6237-services-documentation-evidence-for-sprint-review)
            - [6.2.3.8. Software Deployment Evidence for Sprint Review](#6238-software-deployment-evidence-for-sprint-review)
            - [6.2.3.9. Team Collaboration Insights during Sprint](#6239-team-collaboration-insights-during-sprint)
    - [6.3. Validation Interviews](#63-validation-interviews)
        - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
        - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
        - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
    - [6.4. Video About-the-Product](#64-video-about-the-product)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
    - [Videos de Exposiciones](#videos-de-exposiciones)


<div style="page-break-after: always"></div>

## Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio**: *La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta. | **Cacho Seminario, Diego Alonso**<br>**AV1:** Para el desarrollo de la AV1, aporte creando los documentos de exposicion, reporte de participación y además prepare el reporte principal con los items anteriores para la entrega. <br><br>**TP:** Como desarrollo del TP verifique y solucione diversos errores de la entrega anterior, se verificaron los formatos y estructura del informe además de corregir problemas al exportar el archivo principal.<br><br>**AV2:** Para la AV2, redacté los nuevos apartados en la documentación técnica y lideré el desarrollo íntegro de la aplicación móvil. Implementé la interfaz y la lógica de la app, logrando la conexión bidireccional en tiempo real con el backend y la base de datos, además de validar la correcta recepción de telemetría directamente desde el dispositivo físico IoT.<br><br>**TB2:** Para la entrega final (TB2), desarrollé la redacción del Sprint 3 en el documento de trabajo, detallando la implementación y el despliegue final. A nivel técnico, culminé el desarrollo de la aplicación móvil en Android implementando la generación dinámica de API Keys (UUID) para asegurar la autenticación de los dispositivos IoT. Además, configuré el cliente de red (Retrofit) para apuntar a nuestro entorno de producción en la nube (Railway) y desarrollé la lógica para consumir y mostrar el historial de lecturas reales en la interfaz.<br><br>**Mora Blas, Diego Alonzo**<br>**AV1:** En esta AV1 aporte analizando las diferentes capas de abstraccion de nuestro codigo para analizar y tener registrado nuestros distintos bounded context. <br><br>**TB1**: Aporte revisando y apoyando con la landing page ademas de realizar he investigar el como se podrian hacer el testing para nuestro backend.<br><br>**AV2:** Para la AV2, me enfoqué en el desarrollo de la lógica del backend en la nube, creando los endpoints RESTful necesarios para la comunicación bidireccional entre la base de datos PostgreSQL, la aplicación móvil y los dispositivos IoT. Además, realicé pruebas de integración para asegurar el correcto flujo de telemetría y el registro de nuevos usuarios.<br><br>**Hernandez Poma, Sebastian Eduardo**<br>**AV1:** Lideró la adaptación de la arquitectura del sistema al paradigma IoT, incorporando los bounded contexts de Edge API e IoT Monitoring al modelo Domain-Driven Design. Definió la estructura de los diagramas C4 en Structurizr DSL (System Context, Container y Component Level) para los 9 microservicios del sistema, incluyendo los nuevos componentes de la capa Edge (ESP32 Firmware, Edge API con buffer SQLite). Diseñó los esquemas de base de datos para todos los bounded contexts usando DBML, con especial énfasis en las tablas sensor_readings, alerts y business_rules del IoT Monitoring context. Colaboró en la integración de Firebase FCM para push notifications y la definición del flujo de datos ESP32 → Edge API → Cloud API. <br><br>**TB1:** Lideró el despliegue del Landing Page y el Frontend App, asegurando la disponibilidad de la solución en entornos de producción y coordinando las pruebas de funcionamiento de la interfaz de usuario.<br><br>**AV2:** Lideré el despliegue de la infraestructura en la nube, configurando el servidor backend en plataformas PaaS y la base de datos relacional. Actualicé la arquitectura del sistema y los esquemas de base de datos para soportar la creación dinámica de mapas ("Sections") multi-usuario y garantizar la persistencia segura de los datos transmitidos por los sensores.<br><br>**Inga Orihuela, Christian Fabrizio**<br>**AV1:** Apoyé en la revisión general del informe, verificando la coherencia entre los apartados desarrollados por el equipo y realizando correcciones de redacción, estructura y formato. Asimismo, contribuí a que el documento mantuviera una presentación uniforme y alineada con los criterios solicitados para la entrega.<br><br>**TB1:** Realicé correcciones detalladas en el informe para asegurar la calidad de la entrega y apoyé en el desarrollo de secciones específicas de la landing page y el frontend, facilitando la integración de la información del proyecto.<br><br>**AV2:** Coordiné las pruebas de validación End-to-End (E2E) del sistema, asegurando que los datos capturados por el hardware físico se reflejaran correctamente en las interfaces de usuario. Asimismo, actualicé las secciones correspondientes de la documentación, agregando los nuevos diagramas de flujos y asegurando la coherencia técnica del informe final.<br><br>**Medina Cruzado, Raúl Adrian**<br>**AV1:** Aporté significativamente en la estructuración, redacción y revisión técnica del capítulo 4 del informe. Además, colaboré en la definición de la arquitectura base del proyecto, apoyando en la delimitación de los *bounded contexts* (como Edge API e IoT Monitoring) y asegurando que la documentación técnica refleje correctamente el enfoque de Domain-Driven Design (DDD) propuesto por el equipo.<br><br>**TB1:** Colaboré activamente en el despliegue de la aplicación frontend y lideré la corrección de observaciones arquitectónicas en la documentación técnica tras el feedback de la AV1. Brindé soporte en la integración inicial de los componentes web, asegurando que la interfaz tuviera una estructura preparada para la futura conexión con los microservicios.<br><br>**AV2:** Para la AV2, lideré el desarrollo de la documentación técnica y la elaboración de la presentación (PPTX) para la exposición del avance. Además, realicé un aporte crítico en el desarrollo e implementación del sensor físico, optimizando la lógica de captura de datos y asegurando su correcta integración y comunicación con la capa de Edge Computing para el monitoreo en tiempo real. | **AV1:** Durante la AV1, el equipo logró realizar las primeras partes del trabajo, verificamos el funcionamiento del proyecto junto al su escalabilidad con soluciones basadas en IoT. <br><br>La separación en bounded contexts con responsabilidades claras, especialmente la distinción entre Edge API (procesamiento local) y IoT Monitoring (cloud), permitió diseñar una arquitectura escalable y resiliente que funciona offline. El uso de Structurizr DSL facilitó la colaboración del equipo al mantener la arquitectura como código versionable. <br><br>**TB1:** El equipo realizo avances respecto a las correcciones detalladas en la entrega de la AV1, además de realiza el despliegue del Landing Page y el despliegue de la primera versión de la parte Web de nuestro Frontend.<br><br>**AV2:** Durante la AV2, el equipo logró materializar la arquitectura planificada al conectar exitosamente la capa física (dispositivos IoT) con la capa de software a través de una aplicación móvil completamente funcional y un backend en la nube, demostrando la viabilidad técnica del sistema Osito Polar.<br><br>**TB2:** Para la entrega final, el equipo logró consolidar exitosamente la arquitectura completa del proyecto. Se conectó la aplicación móvil nativa con el backend desplegado en producción (Railway) y la base de datos en la nube (Neon.tech), implementando la generación segura de llaves IoT. Esto demostró la viabilidad técnica del ecosistema de OsitoPolar, cerrando el ciclo de desarrollo con el Sprint 3 correctamente documentado y validado. |
| Participación y colaboración en plataformas y herramientas de trabajo. | **Cacho Seminario, Diego Alonso**<br>**AV1:** Como primera entrega utilice las herramientas de Github y Canva para poder redactar y crear la información necesaria para el trabajo de Osito Polar. <br><br>**TB1:** En la entrega del TB1, se utilizaron principalmente las herramientas de GitHub, Canva y Structurizr para la correción de puntos anteriores del trabajo además para poder realizar la presentación del proyecto.<br><br>**AV2:** En esta etapa utilicé entornos de desarrollo nativo para construir la app móvil, integrando librerías de red para el consumo de APIs hacia nuestro servidor en la nube, y manteniendo el control de versiones del proyecto móvil de manera organizada mediante GitHub.<br><br>**TB2:** En esta etapa final, utilicé Android Studio para la culminación de la aplicación nativa y me apoyé en la terminal de Node.js y herramientas de control de entorno (.env) para auditar y asegurar las variables locales antes del despliegue. Utilicé GitHub para versionar el código móvil y herramientas colaborativas para integrar y formatear las secciones finales del informe (Sprint 3 y actualización de estructura).<br><br>**Mora Blas, Diego Alonzo**<br>**AV1:** Como equipo logramos coordinar de manera precisa nuestros distintos objetivos apoyandonos de herramientas como Github y Canva. <br><br>**TB1:** En la entrega del TB utilizamos diferentes herramientas para el testing de nuestro backend web y evaluar que todo funcionara correctamente.<br><br>**AV2:** Utilicé herramientas como Postman para el testeo exhaustivo de los endpoints de la API RESTful e integré estas pruebas con el flujo de trabajo colaborativo en GitHub para gestionar el versionado del código backend junto con el equipo.<br><br>**Hernandez Poma, Sebastian Eduardo**<br>**AV1:** Lideró la adaptación de la arquitectura del sistema al paradigma IoT, incorporando los bounded contexts de Edge API e IoT Monitoring al modelo Domain-Driven Design. Definió la estructura de los diagramas C4 en Structurizr DSL (System Context, Container y Component Level) para los 9 microservicios del sistema, incluyendo los nuevos componentes de la capa Edge (ESP32 Firmware, Edge API con buffer SQLite). Diseñó los esquemas de base de datos para todos los bounded contexts usando DBML, con especial énfasis en las tablas sensor_readings, alerts y business_rules del IoT Monitoring context. Colaboró en la integración de Firebase FCM para push notifications y la definición del flujo de datos ESP32 → Edge API → Cloud API.<br><br>**TB1:** Utilizó GitHub Pages y otras herramientas de despliegue para publicar el Landing Page y el Frontend, gestionando la integración continua de los avances realizados por el equipo.<br><br>**AV2:** Empleé plataformas de despliegue en la nube (PaaS/DBaaS) para alojar nuestros servicios de producción. Utilicé herramientas ORM como Prisma para migrar y gestionar los esquemas de bases de datos, manteniendo toda la configuración y el código versionados a través de repositorios en GitHub.<br><br>**Inga Orihuela, Christian Fabrizio**<br>**AV1:** Participé en la gestión colaborativa del proyecto mediante el uso de Git y GitHub, revisando los avances del repositorio y apoyando en el control de versiones del trabajo. Además, utilicé GitHub como herramienta de colaboración para mantener organizado el desarrollo del proyecto.<br><br>**TB1:** Utilicé herramientas como Git y GitHub para la gestión del código de la landing page y el frontend, coordinando con el equipo para la integración de las correcciones realizadas al informe.<br><br>**AV2:** Hice uso continuo de Google Docs para la edición síncrona del informe y me apoyé en herramientas de diagramación para modelar los flujos de datos finales. Utilicé GitHub para revisar las integraciones del código y colaborar de forma efectiva en el control de calidad de la entrega técnica.<br><br>**Medina Cruzado, Raúl Adrian**<br>**AV1:** Utilicé Google Docs de forma colaborativa para la redacción y revisión del capítulo 4. Además, me apoyé en herramientas de modelado y diseño arquitectónico (como Structurizr) para analizar los diagramas C4 del sistema, utilizando GitHub para revisar los avances documentales y asegurar la alineación técnica con el resto del equipo.<br><br>**TB1:** Gestioné el repositorio principal de la aplicación utilizando Git y GitHub, encargándome de la resolución de conflictos durante la integración del código del equipo. Asimismo, lideré el despliegue del frontend utilizando GitHub Pages para los entornos de prueba, y empleé herramientas de comunicación ágil para coordinar rápidamente los ajustes en la documentación final.<br><br>**AV2:** Durante la AV2, utilicé herramientas colaborativas como Google Docs y PowerPoint/Canva para la estructuración conjunta del documento final y el diseño de la PPTX. En cuanto al desarrollo del sensor, empleé entornos de desarrollo de hardware para programar la lógica de captura de datos, gestionando el control de versiones del código fuente a través de GitHub para coordinar los avances de manera ágil con el resto del equipo. | **AV1:** Durante la AV1, el equipo logró utilizar las herramientas apropiadas para la entrega, se uso GitHub como repositorio principal para el proyecto, Google Docs para el reporte de participación y Canva como herramienta para crear el video de exposición. <br><br>La separación en bounded contexts con responsabilidades claras, especialmente la distinción entre Edge API (procesamiento local) y IoT Monitoring (cloud), permitió diseñar una arquitectura escalable y resiliente que funciona offline. El uso de Structurizr DSL facilitó la colaboración del equipo al mantener la arquitectura como código versionable. <br><br>**TB1:** Se utilizaron una seria de herramientas para el presente avance del Trabajo Parcial, entre ellas se utilizo GitHub, Canva, Structurizr, GitHub Pages, Trello, entre otras que nos permitieron avanzar de manera ordenada.<br><br>**AV2:** Para la AV2, el equipo amplió su ecosistema de herramientas, gestionando la integración continua y control de versiones en GitHub para los nuevos repositorios móviles y en la nube, garantizando una correcta interoperabilidad entre el hardware IoT y la interfaz de usuario móvil.<br><br>**TB2:** Durante la fase final, el equipo demostró un dominio sólido de las herramientas Cloud y de desarrollo, gestionando despliegues en plataformas como Railway y bases de datos Serverless (Neon.tech). Se mantuvo un estricto control de versiones y políticas de seguridad (manejo de variables .env) en GitHub, logrando integrar con éxito las distintas capas del software. |

<div style="page-break-after: always"></div>


# Capitulo 1: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

OsitoPolar es una aplicación web orientada a mejorar la gestión y el mantenimiento de equipos de congelación en negocios que dependen críticamente del frío, como supermercados, minimarkets, laboratorios, restaurantes y empresas del sector alimentario o farmacéutico. La solución conecta a estos negocios con técnicos y proveedores especializados en refrigeración, permitiendo una gestión integral, preventiva y automatizada de sus sistemas de congelación.

La plataforma ofrece funcionalidades clave como monitoreo en tiempo real de temperatura, consumo energético y tiempo de uso, generación de reportes técnicos, alertas automatizadas por fallas, historial de rendimiento y programación inteligente de mantenimientos. Estas herramientas están diseñadas para ayudar a negocios que dependen del uso de sistemas de refrigeración, técnicos especializados en refrigeración y proveedores de equipos a optimizar sus operaciones, evitar pérdidas económicas por fallas inesperadas y mantener un registro completo del estado y uso de sus equipos.

Misión: Nuestra misión en OsitoPolar es proporcionar una solución tecnológica inteligente que permita a los negocios proteger su inventario y optimizar la gestión de sus equipos de refrigeración, ofreciendo al mismo tiempo herramientas especializadas para mejorar la eficiencia operativa de los técnicos y proveedores del sector.

Visión: Queremos ser la empresa lider en gestión y mantenimiento de equipos de refrigeración, empezando por Lima y prontamente expandirnos a más lugares del Perú.

### 1.1.2 Perfiles de integrantes del equipo

| **Integrante**            | **Diego Alonzo Mora Blas**                                                                                                                                                                                                                                                                                                                                                                                                     |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Código del Estudiante** | U20231c069                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Carrera**               | Ingeniería de Software                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Descripción**           | Estudiante de Ingenieria de Software cursando el 7mo ciclo de mi carrera en la UPC. Soy una persona la cual aprende rapido y se adapta con gran facilidad al contexto del proyecto. Como miembro de equipo he realizado cursos de Ciberseguridad llegando a poder realizar pruebas de penetraciones de nivel intermedio ademas de conocimientos en multiples vulnerabilidad y manejos de diferentes lenguajes de programacion. |
| **Foto**                  | <img src="assets/chapter01/DiegoMora.PNG" alt="DiegoM" width="200" height="200">                                                                                                                                                                                                                                                                                                                                      |

---

| **Integrante**            | **Diego Alonso Cacho Seminario**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Código del Estudiante** | U202223990                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Carrera**               | Ingeniería de Software                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Descripción**           | Soy estudiante de Ingeniería de Software cursando el 7mo ciclo de mi carrera en la UPC y tengo 21 años. Me considero una persona tranquila y diligente, intentó realizar mis tareas y trabajos lo antes posible para evitar contratiempos en un futuro, especialmente si son actividades que consumen mucho tiempo. Como miembro de equipo buscaré ayudar a mis compañeros cuando lo necesiten, realizando además mis entregas lo más temprano posible. Habilidades en C++, C#, Python, Flutter, Unity 2D/3D, html/css/js. |
| **Foto**                  | <img src="assets/chapter01/Diego-Cacho-picture.png" alt="Diego" width="200" height="200">                                                                                                                                                                                                                                                                                                                                                                                                                                  |

---

| **Integrante** | **Hernandez Poma, SebastIan Eduardo** |
|----------------|----------------------------------|
| **Código del Estudiante** | U20231C996 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Estudiante de Ingeniería de Software con interés en el desarrollo de soluciones tecnológicas innovadoras y enfocadas en la experiencia del usuario. Destaca por su orientación al aprendizaje continuo, la resolución de problemas y la aplicación de metodologías modernas en proyectos de software. Posee habilidades en análisis, diseño y desarrollo de aplicaciones, así como una visión estratégica para integrar tecnología y creatividad en entornos profesionales. |
| **Foto** | <img src="assets/chapter01/sehp.png" alt="Joseph" width="200" height="200"> |

---

| **Integrante** | **Christian Fabrizio Inga Orihuela** |
|----------------|----------------------------------|
| **Código del Estudiante** | U20231C111 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Tengo 20 años y actualmente me encuentro cursando el séptimo ciclo de la carrera de ingeniería de software. Cuento con una gran disposición para el trabajo colaborativo y la capacidad de adaptarme rápidamente a diferentes metodologías de aprendizaje y dinámicas de grupo, asegurando siempre un desempeño confiable y organizado. |
| **Foto** | <img src="assets/chapter01/Chris.jpeg" alt="Chris" width="200" height="250"> |

---

| **Integrante** | **Medina Cruzado, Raúl Adrian* |
|----------------|----------------------------------|
| **Código del Estudiante** | U202210938 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Tengo 21 años y estudio Ingeniería de Software. Profesionalmente, me especializo como desarrollador enfocado en automatización (RPA), infraestructura en la nube y liderazgo de equipos ágiles con Scrum; de hecho, actualmente estoy desarrollando mi tesis sobre una plataforma de inteligencia predictiva para el sector minero y diseñando un sistema automatizado de monitoreo de combustible. Esta misma disciplina que aplico en mis proyectos la llevo a mi estilo de vida: jugué fútbol a nivel competitivo en divisiones menores y hoy mantengo un riguroso régimen de fitness y nutrición enfocado en ganar masa muscular y mejorar mi movilidad. En el plano personal, soy alguien muy apegado a mis dos hermanas y a mi familia materna. |
| **Foto** | <img src="assets/chapter01/Raul.jpeg" alt="Raul" width="200" height="200"> |


<div style="page-break-after: always"></div>

## 1.2 Solution Profile

### 1.2.1 Antecedentes y Problematica

| Las 5Ws y 2Hs | Pregunta                                           | Descripción                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| What?         | ¿Cuál es el problema?                              | Actualmente, los negocios que dependen de equipos de congelación enfrentan grandes desafíos operativos ante fallas inesperadas o falta de mantenimiento. Las fallas térmicas, los altos consumos energéticos no detectados a tiempo y la ausencia de un monitoreo constante pueden derivar en la pérdida de productos, reducción de la calidad del servicio y pérdidas económicas importantes. |
| When?         | ¿Cuándo sucede este problema?                      | Estas situaciones ocurren principalmente durante horarios de operación continua, especialmente en momentos donde no hay personal técnico disponible de forma inmediata, o cuando no se ha realizado un seguimiento adecuado del estado del equipo a lo largo del tiempo.                                                                                                                       |
| Where?        | ¿Dónde se produce este suceso?                     | El problema afecta a negocios ubicados en todo el país, principalmente en Lima, donde la cadena de frío es esencial en sectores como alimentación, medicina y distribución. También impacta a empresas proveedoras de refrigeración que atienden múltiples clientes sin una plataforma centralizada de control.                                                                                |
| Who?          | ¿Quiénes están involucrados?                       | Están involucrados tanto los administradores y dueños de negocios que utilizan congeladoras como los técnicos y empresas proveedoras de servicios de refrigeración.                                                                                                                                                                                                                            |
| Why?          | ¿Cuál es la causa del problema?                    | La causa principal es la falta de soluciones tecnológicas accesibles que integren monitoreo, alertas, historial y programación automática en un solo lugar. Muchas empresas aún dependen de sistemas manuales o no tienen control de lo que sucede con sus equipos hasta que ocurre una falla crítica.                                                                                         |
| How?          | ¿Qué llevó a la persona a llegar a esta situación? | Lo que llevó a los negocios y técnicos a este punto ha sido la acumulación de imprevistos y la falta de digitalización en el mantenimiento preventivo, que genera una alta dependencia de intervenciones reactivas en vez de planificadas. Esto incrementa los costos, los tiempos de respuesta y el desgaste operativo.                                                                       |
| How much?     | ¿Cuánto es el impacto financiero?                  | Aunque el impacto económico varía según el tipo de negocio, la pérdida por una falla en un equipo de refrigeración puede ascender desde cientos hasta miles de soles en productos dañados, sin considerar el tiempo operativo perdido, la pérdida de clientes y la inversión en reparación o reposición de equipos.                                                                            |

### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements

El estado actual de la industria de la refrigeración comercial y técnica enfrenta importantes desafíos relacionados con la gestión, el mantenimiento y la trazabilidad de los equipos de congelación. Negocios que dependen críticamente del frío —como supermercados, minimarkets, laboratorios, restaurantes y empresas del sector alimentario o farmacéutico— aún lidian con la falta de monitoreo en tiempo real y con procesos de mantenimiento reactivos. Esto genera pérdidas económicas, ineficiencia energética y riesgos para el inventario.

Lo que las soluciones actuales no logran abordar es la necesidad de una plataforma confiable y automatizada que permita una gestión centralizada, predictiva y transparente tanto para los negocios como para los técnicos y proveedores de refrigeración. La falta de historial técnico accesible, reportes detallados y alertas preventivas limita la capacidad de respuesta ante fallas y deteriora la calidad del servicio técnico ofrecido.

**OsitoPolar** cierra esta brecha al ofrecer una solución tecnológica integral que conecta negocios con técnicos especializados, brindando funcionalidades como monitoreo en tiempo real de temperatura y consumo, programación inteligente de mantenimientos, alertas por fallas, reportes automáticos y trazabilidad completa de cada equipo. Además, proporciona a los proveedores de servicios un módulo para visualizar y gestionar eficientemente los equipos que atienden, organizar visitas y acceder al historial técnico de manera ágil.

Nuestro enfoque inicial está en los negocios de Lima que necesitan asegurar el funcionamiento óptimo de sus sistemas de congelación, así como en los proveedores que buscan profesionalizar y escalar su servicio con herramientas digitales modernas.

Sabremos que hemos tenido éxito cuando observemos una reducción en fallas imprevistas, una optimización del consumo energético, mayor eficiencia operativa por parte de los técnicos especializados y un incremento en la satisfacción de los clientes finales. Esto se evidenciará en la continuidad del servicio y en la fidelización de los negocios que dependen de sistemas de refrigeración, técnicos especializados y proveedores de equipos que utilizan la plataforma.


#### 1.2.2.2 Lean UX Assumption

# Business Outcomes

- Aumentar en al menos un 15% la cantidad de negocios que dependen del uso de sistemas de refrigeración, técnicos especializados en refrigeración y proveedores de equipos activos dentro de la aplicación.

- Lograr una mayor visibilidad de la plataforma OsitoPolar a través de redes sociales, especialmente entre negocios de alimentos y técnicos de refrigeración.

- Generar confianza y seguridad en estos actores respecto al monitoreo y mantenimiento automatizado de sus sistemas de refrigeración.

- Mantener informados a los usuarios finales —negocios, técnicos y proveedores— sobre incidentes recientes como fallas térmicas, cortes de energía o uso irregular de los equipos.

- Alcanzar una base sólida de clientes dispuestos a pagar por una membresía premium que incluya mantenimiento predictivo, reportes personalizados y soporte técnico prioritario.

- Establecer alianzas estratégicas con plataformas como Google Maps o servicios de geolocalización para ampliar el alcance de cobertura y optimizar la programación de visitas técnicas.

- Fomentar la participación activa de negocios, técnicos y proveedores mediante encuestas, valoraciones de técnicos y comentarios sobre el desempeño de los equipos.

- Diseñar una interfaz limpia, simple e intuitiva que garantice una experiencia fluida y atractiva para nuevos usuarios del sector, evitando la sobrecarga visual o de funcionalidades.

- Implementar inteligencia artificial que permita trazar estrategias de mantenimiento inteligente, rutas eficientes para los técnicos y recomendaciones proactivas ante posibles fallos.

# User Outcomes

## ¿Quién será nuestro usuario?

- **Negocios que dependen críticamente del uso de sistemas de refrigeración** como supermercados, minimarkets, restaurantes, laboratorios y empresas del rubro alimentario y farmacéutico.
- **Técnicos especializados en refrigeración** que brindan mantenimiento a dichos sistemas.
- **Proveedores de equipos de refrigeración** que desean ofrecer un servicio posventa más eficiente.

## ¿Dónde encaja nuestro producto en su vida?

- En situaciones donde los negocios necesitan garantizar la continuidad operativa de sus equipos de frío, evitando pérdidas económicas por fallas imprevistas.
- En el día a día de técnicos de refrigeración que deben gestionar múltiples clientes, visitas y mantenimientos.
- En la operación diaria de los negocios que necesitan registros y reportes precisos del desempeño de sus sistemas de refrigeración.

## ¿Qué problemas tiene nuestro producto y cómo se pueden resolver?

- El principal desafío es asegurar que los datos de monitoreo (temperatura, consumo energético, fallas, etc.) sean precisos, actualizados y confiables.
    -   Solución: Se debe integrar sensores calibrados y sistemas de verificación automática que validen las lecturas antes de almacenarlas.


- Otro problema puede ser la adopción inicial de la plataforma por parte de negocios que dependen del uso de sistemas de refrigeración, técnicos especializados en refrigeración y proveedores de equipos que no están familiarizados con la tecnología.
    - Solución: Esto se abordará con una interfaz sencilla, explicaciones paso a paso y soporte técnico accesible.

## ¿Cómo y Cuándo es usado nuestro producto?

- Se accede desde la aplicación web, tanto desde computadoras como dispositivos móviles.
- Se utiliza diariamente para monitorear el estado de los equipos de frío, recibir alertas, programar mantenimientos o revisar el historial técnico.
- También se activa automáticamente en segundo plano cuando se integran sensores de monitoreo con la plataforma.

## ¿Qué problemas tiene nuestro producto?

- En sus etapas iniciales, puede carecer de ciertas integraciones con hardware de terceros.
- Algunos negocios que dependen del uso de sistemas de refrigeración, técnicos especializados o proveedores de equipos pueden requerir capacitación para comprender todas las funcionalidades avanzadas.
- También podría haber desafíos para que los técnicos adopten el uso digital en lugar del método tradicional.

## ¿Qué características son importantes para la app?

- Monitoreo en tiempo real de temperatura, consumo energético y tiempo de uso.
- Alertas automáticas por fallas detectadas en los equipos.
- Historial técnico completo con reportes exportables en PDF.
- Calendario de mantenimiento preventivo con notificaciones programadas.
- Módulo exclusivo para técnicos con gestión de visitas y clientes.
- Soporte técnico inteligente y recomendaciones predictivas mediante IA.
- Registro de múltiples ubicaciones y usuarios con distintos roles.
- Interfaz intuitiva y minimalista para garantizar fácil adopción.

## ¿Cómo debe verse nuestro producto y cómo comportarse?

- **Interfaz amigable y confiable**: Negocios que dependen del uso de sistemas de refrigeración, así como, técnicos especializados y proveedores de equipos deben sentirse seguros al usar la aplicación. La interfaz debe ser clara, ordenada y fácil de navegar, sin sobrecargar de información, con gráficos e indicadores intuitivos.
- **Diseño centrado en tareas críticas**: Desde el primer acceso, negocios que dependen del uso de sistemas de refrigeración, técnicos especializados y proveedores de equipos deben poder ver si hay fallas, cuándo es la próxima visita técnica, y acceder rápidamente a los reportes y al historial de sus equipos.
- **Accesibilidad multiplataforma**: Disponible en web y móvil, adaptable para quienes trabajan tanto en oficina como en campo. Notificaciones inmediatas ante cualquier problema detectado.
- **Simplicidad**: La app debe permitirles gestionar sus negocios, equipos en riesgo y visitas programadas, todo desde un panel centralizado. También pueden agendar visitas y generar reportes técnicos en segundos.

## ¿Qué valor busca el cliente?

- **Gestión técnica simplificada**: Los proveedores y técnicos buscan dejar de ser reactivos. OsitoPolar los vuelve proactivos con mantenimiento predictivo, historiales claros y clientes organizados.
- **Seguridad operativa y cero sorpresas**: Los negocios quieren evitar pérdidas por fallas en frío. OsitoPolar les da monitoreo constante, alertas automáticas y control total sobre sus equipos.
- **Eficiencia energética y trazabilidad**: Los dueños quieren saber si sus equipos consumen de más, si están rindiendo mal, o si un componente ya debería ser reemplazado. El sistema lo identifica antes que ocurra el fallo.

## ¿Qué beneficios adicionales obtendrá el cliente?

- Visibilidad total del estado de sus equipos, desde cualquier lugar, en cualquier momento.
- Soporte técnico más ágil gracias al historial previo y alertas automáticas.
- Menores costos operativos gracias a mantenimientos a tiempo y mayor eficiencia energética.
- Reportes personalizados y exportables.
- Automatización de visitas técnicas cuando se detectan patrones de falla.

## ¿Cómo atraeremos usuarios?

- **Marketing dirigido a nichos clave**: Supermercados, restaurantes y empresas de frío serán contactados directamente mediante LinkedIn, correos y llamadas estratégicas.
- **Alianzas con proveedores de equipos**: Trabajaremos con empresas que venden congeladoras o cámaras frigoríficas para que incluyan OsitoPolar en sus paquetes posventa.
- **Prueba gratuita de versiones de pago**: Un modelo de 14 días gratis con monitoreo limitado para mostrar el valor de la plataforma en tiempo real.

## ¿Cómo generaremos ingresos?

- **Suscripción mensual de negocios**: Por el uso de la plataforma, según número de equipos, tipo de reportes y funcionalidades.
- **Modelo freemium**: Habrá una versión gratuita que brindará algunas funciones limitadas, pero con anuncios, lo que generará ingresos adicionales.
- **Publicidad dirigida (opcional)**: Marcas de refrigeración podrían pagar por visibilidad dentro de la plataforma si se llega a una masa crítica de técnicos y negocios.

## ¿Cuál es nuestra competencia y cómo la superamos?

- **Competencia**: Las principales competidoras son aplicaciones relacionadas con la gestión de datos y orientada al servicio técnico de mantenimiento de equipos de refrigeración.
- **Nuestra ventaja**: OsitoPolar fue diseñado exclusivamente para negocios que dependen de equipos de frío. No somos una herramienta genérica, somos expertos en el nicho. No solo registramos visitas o mantenimientos, también detectamos anomalías en tiempo real, generamos alertas y automatizamos acciones.

## ¿Cuál es nuestro mayor riesgo?

- **Adopción lenta por parte del personal tradicional**: Algunos proveedores aún dependen de agendas físicas o Excel y podrían resistirse al cambio.
- **Falta de adopción inicial**: La dificultad para convencer a los negocios que dependen del uso de sistemas de refrigeración, técnicos especializados y proveedores de equipos de que la app es útil y confiable puede retrasar su adopción.
- **Desconfianza en la precisión de los sensores**: Si los datos no son confiables, la plataforma pierde valor

## ¿Cómo lo resolveremos?

- **Algoritmos de validación**: Implementaremos algoritmos de IA que verifiquen la información y filtren los reportes ambiguos o antiguos, garantizando solo datos confiables y actuales.
- **Capacitación y soporte**: Para resolver la falta de adopción, ofreceremos tutoriales interactivos, videos explicativos y soporte técnico accesible para que negocios que dependen del uso de sistemas de refrigeración, técnicos especializados y proveedores de equipos se familiaricen con las funciones.
- **Estrategia progresiva de integraciones**: Comenzaremos con los equipos más usados y luego ampliaremos compatibilidad mediante APIs y alianzas con fabricantes.
- **Sensores certificados**: Solo se integrarán sensores probados.

#### 1.2.2.2 Lean UX Hypothesis Statements

**Hipótesis 1: Eficiencia operativa y reducción de fallas inesperadas**

Creemos que al ofrecer una plataforma integral que unifique todas las funciones de monitoreo, mantenimiento y gestión técnica de equipos de refrigeración, aumentaremos la eficiencia operativa de los negocios y proveedores del sector, reduciendo la complejidad y el riesgo de fallas inesperadas.  
Sabremos que estamos en lo correcto cuando veamos un aumento en la cantidad de negocios que reportan menos incidencias por fallas térmicas, así como una mejora en la planificación de sus mantenimientos preventivos.

---

**Hipótesis 2: Control de pérdidas operativas y consumo energético**

Creemos que el control de pérdidas operativas y el consumo energético es una prioridad para los negocios que dependen del uso de sistemas de refrigeración, técnicos especializados y proveedores de equipos; por lo tanto, al proporcionar herramientas de análisis de rendimiento y alertas automatizadas, mejoraremos su capacidad para actuar de manera preventiva y reducir costos innecesarios.  
Sabremos que estamos en lo correcto cuando observemos una adopción creciente de nuestras funcionalidades de monitoreo en tiempo real y reportes técnicos, así como una disminución en las pérdidas económicas por interrupciones del sistema de refrigeración.

---

**Hipótesis 3: Mejora en el servicio técnico personalizado y predictivo**

Creemos que al proporcionar reportes técnicos automáticos, históricos de uso y rendimiento por equipo, permitiremos a los técnicos y empresas proveedoras ofrecer un servicio personalizado y predictivo, mejorando la calidad del soporte brindado a sus clientes.  
Sabremos que estamos en lo correcto cuando recibamos retroalimentación positiva de técnicos sobre la utilidad de los reportes y el historial, y cuando sus clientes reporten mayor satisfacción con la rapidez y eficacia del servicio técnico.

---

**Hipótesis 4: Trazabilidad y protección de la información técnica**

Creemos que al garantizar la trazabilidad de todas las acciones realizadas sobre cada unidad de refrigeración, así como la protección de la información técnica en la plataforma, construiremos confianza entre negocios y proveedores de servicios.  


---

**Hipótesis 5: Transición a una gestión moderna de refrigeración**

Creemos que al ofrecer una solución digital intuitiva y especializada tanto para negocios como para técnicos, facilitaremos la transición hacia una gestión moderna de refrigeración, minimizando la curva de aprendizaje.  
Sabremos que estamos en lo correcto cuando observemos una rápida adopción de nuestra plataforma, baja tasa de abandono y una mayor frecuencia de uso de las funcionalidades clave por parte de usuarios nuevos y recurrentes.


#### 1.2.2.4 Lean UX Canvas

El presente Lean UX Canvas se ha desarrollado para ofrecer una visión estratégica y concisa de la solución OsitoPolar. Este marco nos permite alinear rápidamente los objetivos de negocio con las necesidades de nuestros usuarios y las hipótesis clave que guían nuestro desarrollo.
A través de este lienzo, hemos desglosado el problema central que enfrentan los negocios que dependen de equipos de refrigeración, definido las soluciones propuestas y anticipado los resultados que esperamos alcanzar.
Asimismo, hemos identificado a nuestros usuarios clave y sus beneficios, y hemos establecido una serie de hipótesis que nos permitirán validar nuestro enfoque con la mínima inversión de tiempo y recursos posible, asegurando que cada paso que demos esté centrado en generar valor real.


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter01/lean-ux-canvas.png"
       alt="Lean UX Canvas: Un lienzo para aplicar principios de Lean UX al diseño."
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Lean UX Canvas.
  </figcaption>
</figure>

<div style="page-break-after: always"></div>

## 1.3 Segmentos objetivos

**Segmento Objetivo #1: Negocios que utilizan equipos de refrigeración**

**Aspectos demográficos:**
- **Tipo de negocio**: Pequeñas, medianas y grandes empresas
- **Rubro**: Alimentario, farmacéutico, restauración y comercio minorista
- **Nivel de necesidad**: Alta dependencia de sistemas de refrigeración

**Aspectos geográficos:**
- **Nacionalidad**: Peruana
- **Zona geográfica**: Urbana
- **Departamento**: Lima (con proyección de expansión nacional)

**Aspectos psicográficos:**
- Empresas que buscan evitar pérdidas económicas por fallas en refrigeración.
- Negocios que requieren control eficiente del consumo energético.
- Administradores interesados en implementar tecnología para optimizar sus operaciones y mantener la calidad del inventario.

---

**Segmento Objetivo #2: Empresas proveedoras de servicios y equipos de refrigeración**

**Aspectos demográficos:**
- **Tipo de empresa**: Técnicos independientes, PYMES y proveedores especializados en refrigeración.
- **Rol**: Técnicos de mantenimiento, instaladores, empresas de soporte técnico.

**Aspectos geográficos:**
- **Nacionalidad**: Peruana
- **Zona geográfica**: Urbana
- **Departamento**: Lima (con visión de expansión a nivel nacional)

**Aspectos psicográficos:**
- Técnicos que desean organizar sus visitas de forma eficiente y centralizada.
- Empresas que buscan mejorar la trazabilidad de sus servicios y ofrecer reportes automáticos.
- Profesionales que desean brindar un servicio más personalizado y predictivo a sus clientes.

<div style="page-break-after: always"></div>

## Capítulo II: Requirements Elicitation & Analysis 

### 2.1. Competidores

**Competidor 1: ServiceTitan**
ServiceTitan es una plataforma de gestión de servicios basada en la nube que ofrece soluciones de software para empresas de servicios, incluidos técnicos de HVAC, fontaneros y electricistas. Proporciona funcionalidades de programación, gestión de trabajos, facturación y más. Esta plataforma es conocida por su facilidad de uso y por ayudar a las empresas a optimizar sus operaciones de servicio técnico en tiempo real.


---

**Competidor 2: CoolMaster**
CoolMaster es una solución de software diseñada específicamente para el sector de refrigeración comercial. Ofrece monitoreo remoto de sistemas de refrigeración, alertas tempranas de fallas y gestión eficiente del consumo energético. La plataforma está orientada a optimizar la eficiencia operativa de negocios que dependen críticamente de sistemas de frío, como supermercados y centros de distribución.


---

**Competidor 3: TempGenius**
TempGenius es un software de monitoreo de temperatura y humedad en tiempo real para diversas industrias, incluida la de la refrigeración comercial. Permite a los usuarios realizar un seguimiento de sus equipos de refrigeración mediante sensores conectados a la nube, generar reportes y recibir alertas automáticas por variaciones en los niveles de temperatura. Su principal enfoque es mejorar la visibilidad y control de las operaciones de refrigeración para evitar pérdidas económicas.

#### 2.1.1. Análisis competitivo

<table> 
  <tr>
    <th colspan="7"> Competitive Analysis Landscape </th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar acabo este análisis? </td>
    <td colspan="5"> Pregunta </td>
  </tr>
  <tr>
    <td colspan="5"> Respuesta </td>
  </tr>
  <tr>
    <td colspan="2"> Productos </td>
    <td> OsitoPolar </td>
    <td> ServiceTitan </td>
    <td> CoolMaster </td>
    <td> TempGenius </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td> OsitoPolar es una plataforma integral de monitoreo y gestión para sistemas de refrigeración, que conecta negocios con técnicos especializados. Ofrece monitoreo en tiempo real, alertas automáticas, mantenimiento preventivo, y trazabilidad de cada equipo. </td>
    <td> ServiceTitan es una plataforma de gestión de servicios basada en la nube que ofrece soluciones de software para empresas de servicios, incluidos técnicos de HVAC, fontaneros y electricistas. </td>
    <td> CoolMaster es una solución de software diseñada específicamente para el sector de refrigeración comercial. Ofrece monitoreo remoto de sistemas de refrigeración, alertas preventivas y gestión energética. </td>
    <td> TempGenius es un software de monitoreo de temperatura y humedad en tiempo real para diversas industrias, incluida la refrigeración comercial. Permite a los usuarios gestionar y recibir alertas automáticas sobre sus equipos. </td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td> Ofrece una solución automatizada y centralizada para negocios que necesitan monitorear y gestionar sus equipos de refrigeración. Permite a los técnicos optimizar sus visitas y el mantenimiento preventivo, mejorando la eficiencia operativa. </td>
    <td> Ofrece una plataforma todo-en-uno para la gestión de servicios con características como la programación de citas, facturación y seguimiento en tiempo real de proyectos. </td>
    <td> Ofrece soluciones específicas para la gestión de sistemas de refrigeración, con funcionalidades avanzadas de monitoreo, alertas y análisis de consumo energético. </td>
    <td> Ofrece monitoreo preciso en tiempo real de la temperatura y humedad, con alertas automáticas, y un enfoque especial en la fiabilidad y precisión de los datos. </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td> Mercado Objetivo </td>
    <td> Negocios que dependen de sistemas de refrigeración, como supermercados, minimarkets, laboratorios, restaurantes, entre otros. También incluye técnicos de refrigeración y proveedores de equipos. </td>
    <td> Empresas de servicios como HVAC, fontaneros, electricistas, y otros proveedores de servicios técnicos. </td>
    <td> Negocios que dependen de sistemas de refrigeración como supermercados, laboratorios, restaurantes y otros en el sector alimentario y farmacéutico. </td>
    <td> Usuarios de diversas industrias, especialmente en áreas que requieren monitoreo continuo de temperatura y humedad, como el sector alimentario y farmacéutico. </td>
  </tr>
  <tr>
    <td> Estrategias de Marketing </td>
    <td> Marketing digital, colaboraciones estratégicas con empresas del sector alimentario y farmacéutico, demostraciones gratuitas y promociones en redes sociales. </td>
    <td> Marketing digital, colaboraciones con empresas de servicios y promoción en plataformas de negocio. </td>
    <td> Marketing dirigido a negocios en el sector alimentario y farmacéutico, con énfasis en la reducción de fallas y el ahorro energético. </td>
    <td> Marketing en redes sociales, promociones para nuevos usuarios y colaboraciones con industrias reguladas como la farmacéutica y alimentaria. </td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td> Productos & Servicios </td>
    <td> Gestión de equipos de refrigeración en tiempo real, alertas automáticas, mantenimiento preventivo, reportes técnicos automáticos y trazabilidad de cada equipo. </td>
    <td> Plataforma de gestión de servicios que incluye programación de citas, gestión de personal, facturación, y seguimiento de proyectos en tiempo real. </td>
    <td> Plataforma de monitoreo y gestión de sistemas de refrigeración, con alertas preventivas, informes automáticos y análisis de rendimiento energético. </td>
    <td> Plataforma de monitoreo de temperatura y humedad en tiempo real, con alertas automáticas, reportes detallados y gestión de datos históricos. </td>
  </tr>
  <tr>
    <td> Precios & Costos </td>
    <td> Modelo basado en comisiones bajas por cada reserva o cita pagada para negocios, con una versión gratuita para usuarios. </td>
    <td> Suscripción mensual o anual, con tarifas adicionales por características avanzadas o soporte personalizado. </td>
    <td> Varía según el plan y características seleccionadas, con opciones para negocios grandes o pequeños. </td>
    <td> Varía según la cantidad de equipos monitoreados y las características seleccionadas, con modelos de suscripción mensual o anual. </td>
  </tr>
  <tr> 
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td> Plataforma en línea y aplicación móvil disponible para dispositivos iOS y Android. </td>
    <td> Plataforma en línea y aplicación móvil disponible para dispositivos iOS y Android. </td>
    <td> Plataforma en línea y aplicación móvil. </td>
    <td> Aplicación móvil disponible en tiendas de aplicaciones y plataforma en línea. </td>
  </tr>
  <tr>
    <td rowspan="4"> Análisis SWOT </td>
    <td> Fortalezas </td>
    <td> Monitoreo en tiempo real, alertas automáticas y mantenimiento preventivo para evitar fallas críticas. Función de trazabilidad completa de los equipos. </td>
    <td> Amplia funcionalidad para gestión de servicios y seguimiento en tiempo real de proyectos. </td>
    <td> Especialización en el monitoreo y la gestión de sistemas de refrigeración, con enfoque en ahorro energético. </td>
    <td> Precisión en el monitoreo de temperatura y humedad, con alertas automáticas y un enfoque flexible en diferentes industrias. </td>
  </tr>
  <tr>
    <td> Debilidades </td>
    <td> Dependencia de la adopción inicial por parte de los usuarios, lo que podría afectar la expansión. </td>
    <td> Puede ser más complejo de usar para pequeñas empresas sin experiencia en gestión de software. </td>
    <td> Enfoque limitado al sector de refrigeración, lo que puede dificultar la expansión a otros mercados. </td>
    <td> Puede resultar costoso para pequeñas empresas debido a las suscripciones y los costos adicionales por dispositivos. </td>
  </tr>
  <tr>
    <td> Oportunidades </td>
    <td> Expansión en el sector de la gestión de refrigeración, con foco en la eficiencia operativa y la reducción de costos. </td>
    <td> Expansión a nuevos mercados, introducción de nuevos servicios, mejorar la experiencia del usuario. </td>
    <td> Expansión a nuevos mercados, mejora continua de características y funciones, colaboraciones estratégicas con otros servicios. </td>
    <td> Expansión a nuevos mercados, introducción de nuevas características y servicios, colaboraciones estratégicas con marcas de belleza. </td>
  </tr>
  <tr>
    <td> Amenazas </td>
    <td> Competencia de aplicaciones ya establecidas en la gestión de refrigeración y mantenimiento. </td>
    <td> Competencia de otras plataformas de gestión de servicios que ofrecen características similares. </td>
    <td> Alta competencia en el mercado de soluciones para refrigeración y dependencia de la infraestructura de clientes. </td>
    <td> Competencia de otras plataformas de monitoreo de temperatura y humedad, con características similares y precios más bajos. </td>
  </tr>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores

Hemos identificado diversas estrategias y tácticas para diferenciarse y competir efectivamente con otros actores del mercado de la gestión y monitoreo de sistemas de refrigeración. A continuación se detallan las principales:

---

**1. Estrategias de Diferenciación:**

- **Automatización y Mantenimiento Preventivo**: A diferencia de los competidores, **OsitoPolar** se enfoca en ofrecer una solución integral con monitoreo en tiempo real, alertas automáticas y un sistema de mantenimiento preventivo. Esto permite a los negocios reducir las incidencias por fallas inesperadas y gestionar sus equipos de refrigeración de manera proactiva.

- **Trazabilidad Completa de Equipos**: Ofrecemos una plataforma que proporciona un historial técnico detallado de cada equipo, algo que competidores como **ServiceTitan** no ofrecen de forma especializada para el sector de refrigeración. Esto garantiza un mayor control sobre los activos y la calidad del servicio.

- **Interfaz Intuitiva y Fácil de Usar**: A diferencia de **CoolMaster**, que se centra más en el sector de refrigeración sin necesariamente pensar en la accesibilidad del usuario, **OsitoPolar** prioriza la simplicidad de uso, lo que facilita la adopción rápida por parte de los negocios y técnicos, independientemente de su experiencia tecnológica.

---

**2. Tácticas de Marketing:**

- **Marketing Digital y Demostraciones Gratuitas**: Enfocaremos nuestras campañas en redes sociales, demostraciones en vivo, y colaboraciones con negocios del sector alimentario y farmacéutico, destacando nuestra capacidad para reducir fallas y ahorrar costos en operaciones. Esta táctica se diferencia de **TempGenius**, que aún no ha adoptado un enfoque digital tan agresivo.

- **Fidelización de Usuarios a Largo Plazo**: Implementaremos programas de fidelización y un sistema de recompensas para los técnicos y negocios que continúen usando nuestra plataforma y colaboren con nosotros para mejorar el servicio. De esta forma, buscamos aumentar la lealtad, algo que muchos competidores no han logrado gestionar adecuadamente.

---

**3. Estrategias de Precios:**

- **Modelo Freemium**: Ofrecemos una versión básica gratuita para atraer a pequeños negocios y usuarios que no están seguros de pagar por un servicio premium de inmediato. Este modelo es más flexible que el de **ServiceTitan**, que depende de suscripciones pagadas desde el principio.

- **Comisiones Bajas por Reserva**: Para los negocios, aplicamos comisiones reducidas por cada cita reservada a través de nuestra plataforma, lo que facilita la adopción, especialmente en comparación con otros competidores como **CoolMaster**, que tiene costos fijos más elevados.

---

**4. Expansión y Adaptabilidad:**

- **Enfoque Regional Inicial y Expansión Nacional**: A diferencia de competidores como **TempGenius**, que tiene un enfoque global, **OsitoPolar** comenzará en Lima con planes de expansión a otras ciudades del Perú. Esto nos permite adaptarnos mejor a las necesidades locales antes de expandirnos a nivel internacional.

- **Colaboraciones con Proveedores Locales**: Formaremos alianzas estratégicas con proveedores de equipos de refrigeración y servicios técnicos en Perú, lo que nos diferenciará de la competencia al contar con un sistema robusto y adaptado específicamente para el mercado peruano.

---

<div style="page-break-after: always"></div>

### 2.2. Entrevistas.

#### 2.2.1. Diseño de entrevistas

**Segmento 1: Negocios que utilizan equipos de refrigeración**

1. ¿Qué edad tiene?
2. ¿De dónde es y a qué se dedica?
3. ¿Qué tipo de negocio tiene y qué productos necesita mantener en frío?
4. ¿Cuántos equipos de refrigeración tiene actualmente?
5. ¿Ha tenido pérdidas por fallas en sus equipos? ¿Qué impacto tuvo?
6. ¿Cómo monitorea hoy el estado (temperatura, consumo, fallas) de esos equipos?
7. ¿Con qué frecuencia realiza mantenimiento y quién se encarga?
8. ¿Utiliza alguna herramienta digital para la gestión de estos equipos?
9. ¿Qué tan útil le parecería recibir alertas automáticas por fallas o variaciones de temperatura?
10. ¿Le interesaría tener un historial técnico y reportes automáticos por cada equipo?
11. ¿Estaría dispuesto a pagar una suscripción si esto evita pérdidas y mejora la eficiencia?
12. ¿Qué funcionalidades sí o sí debería tener una herramienta de este tipo para que usted la use?
13. ¿Preferiría acceder a la herramienta desde su celular o computadora?
14. ¿Qué le haría dejar de usar una aplicación de este tipo?


**Segmento 2: Empresas proveedoras de servicios y equipos de refrigeración**

1. ¿Qué edad tiene?
2. ¿De dónde es?
3. ¿A qué se dedica específicamente y hace cuánto trabaja en el rubro?
4. ¿Cuántos clientes o negocios atiende regularmente?
5. ¿Cómo organiza sus visitas técnicas y mantenimientos?
6. ¿Lleva un historial técnico de los equipos que repara? ¿Cómo lo gestiona?
7. ¿Cuáles son las principales dificultades que enfrenta su empresa al coordinar servicios técnicos?
8. ¿Cómo coordina hoy sus rutas o visitas? ¿Utiliza alguna herramienta o lo hace manualmente?
9. ¿Qué tan útil le sería tener una app donde pueda ver todos los equipos que provee o atiende?
10. ¿Le interesaría recibir alertas sobre fallas en los equipos de sus clientes en el momento en el que suceden?
11. ¿Qué tanto valora poder generar reportes automáticos y mantener trazabilidad de cada intervención?
12. ¿Estaría dispuesto a usar una plataforma que le ayude a organizarse mejor y escalar su servicio?
13. ¿Ha probado alguna solución parecida antes? ¿Por qué la dejó de usar (si la dejó)?
14. ¿Qué beneficios cree que podría tener la implementación de una solución digital como OsitoPolar a su empresa?

---
#### 2.2.2. Registro de entrevistas

## Segmento objetivo #1: Negocios que utilizan equipos de refrigeración

### Entrevista 1:

- **Nombres y apellidos:** Adriana Moloche
- **Edad:** 32
- **Distrito:** San Martín de Porres
- **Dispositivo móvil:** iPhone 11
- **Navegador preferido:** Safari
- **Marcas/influencias:** Tiendas de conveniencia Tambo, refrigeradores Samsung

![Interview-1-segment-1.png]( assets/chapter02/Interview-1-segment-1.png)

- **Inicio:** 0:02
- **Duración:** 3:18 min
- **URL:** [https://bit.ly/4j6lCpZ](https://bit.ly/4j6lCpZ)
- **Resumen:** Adriana es una emprendedora que administra una bodega tipo mini market en San Martín de Porres. Su actividad diaria depende del correcto funcionamiento de sus equipos de refrigeración, ya que conserva productos perecibles como embutidos, bebidas y lácteos. Durante la entrevista, manifestó haber experimentado pérdidas económicas debido a fallas inesperadas en sus congeladoras, y recalcó la ausencia de mecanismos digitales que le ayuden a prevenir esos eventos. Actualmente, revisa la temperatura manualmente y realiza mantenimientos periódicos cada 20 días, lo cual considera una tarea rutinaria pero propensa a errores. Se mostró muy interesada en la idea de contar con una solución tecnológica que le notifique fallas de manera automática, que le brinde un historial técnico detallado y reportes por cada servicio realizado. Además, resaltó la importancia de tener opciones de suscripción accesibles, adaptadas a negocios pequeños como el suyo. Mencionó que estaría dispuesta a pagar por el servicio si se le garantiza una reducción significativa en las pérdidas operativas. Para ella, una herramienta como OsitoPolar representa una alternativa innovadora que podría profesionalizar su gestión sin exigir conocimientos técnicos complejos. Esta entrevista refleja claramente la necesidad de digitalizar los procesos de mantenimiento en pequeños negocios que dependen críticamente del frío.

---
#### Entrevista 2:
- **Nombres y apellidos:** Luis Mamani Torres
- **Edad:** 37
- **Distrito:** Comas
- **Dispositivo móvil:** Samsung Galaxy A53
- **Navegador preferido:** Chrome
- **Marcas/influencias:** Locales gastronómicos con alta calificación, Sheraton, equipos de refrigeración industrial LG

![Interview-2-segment-1.jpg]( assets/chapter02/Interview-2-segment-1.jpg)

- **Inicio:** 0:25
- **Duración:** 9:03 min
- **URL:** [https://bit.ly/45c4QlW](https://bit.ly/45c4QlW)
- **Resumen:** Luis es un empresario del rubro gastronómico especializado en cevichería, con experiencia previa como coordinador de cocina en hoteles de prestigio como el Sheraton. Actualmente administra un solo local en el distrito de Comas, donde emplea equipos de refrigeración para conservar insumos altamente sensibles como pescados y mariscos. Recalcó que en su rubro la cadena de frío es esencial, ya que un solo error podría implicar pérdidas económicas y riesgos sanitarios. Aunque reconoce que puede gestionar su negocio manualmente por su tamaño actual, también admite que una herramienta como OsitoPolar sería vital si decidiera expandirse. Indicó que empresas del sector avícola cuentan con sistemas similares, aunque menos sofisticados. En ese sentido, considera que OsitoPolar presenta una propuesta más completa y especializada. Destacó que funcionalidades como alertas automáticas, reportes de consumo y planificación de mantenimiento le permitirían optimizar sus operaciones, especialmente si tuviera varios locales. A pesar de no usar una solución digital actualmente, Luis mostró una actitud muy abierta a la adopción de tecnología si esta garantiza eficiencia y prevención de pérdidas. Esta entrevista demuestra que incluso negocios con una sola sede reconocen el valor de la digitalización y están dispuestos a invertir en soluciones escalables.

##### Segmento objetivo #2: Empresas proveedoras de servicios y equipos de refrigeración

### Entrevista 1:

- **Nombres y apellidos:** Wilder Canchan
- **Edad:** 45
- **Distrito:** Los Olivos
- **Dispositivo móvil:** Xiaomi Redmi Note 10
- **Navegador preferido:** Chrome
- **Marcas/influencias:** Empresas de refrigeración comercial, Coldex, Miray

![Interview-1-segment-2.png]( assets/chapter02/Interview-1-segment-2.png)

- **Inicio:** 0:43
- **Duración:** 7:03 min
- **URL:** [https://bit.ly/4jS816Q](https://bit.ly/4jS816Q)
- **Resumen:** Wilder es técnico especializado en refrigeración y aire acondicionado, con más de 7 años de experiencia atendiendo aproximadamente a 25 clientes al mes. Durante la entrevista, comentó que su principal dificultad radica en la coordinación con los clientes para las visitas técnicas, especialmente por errores en la ubicación o en los horarios acordados. Actualmente, gestiona sus servicios vía telefónica y utiliza Google Maps como apoyo para las rutas. Consideró que una plataforma como OsitoPolar le permitiría centralizar su operación, recibir alertas sobre fallas, y mejorar tanto la planificación de su agenda como la comunicación con los clientes. También destacó la posibilidad de llevar un historial técnico de cada equipo atendido, lo cual le ayudaría a prepararse mejor antes de cada visita. En su opinión, el uso de una app profesional elevaría la imagen de su empresa, mejorando la confianza y fidelización del cliente. Esta entrevista muestra cómo la tecnología puede mejorar considerablemente el desempeño de empresas técnicas, sobre todo en aspectos logísticos y de trazabilidad.

---

#### Entrevista 2:

- **Nombres y apellidos:** Jackeline Bravo
- **Edad:** 36
- **Distrito:** Comas
- **Dispositivo móvil:** iPhone 12
- **Navegador preferido:** Safari
- **Marcas/influencias:** Microsoft Office, empresas con software de gestión integrado, servicios de refrigeración premium

![Interview-2-segment-2.png]( assets/chapter02/Interview-2-segment-2.png)

- **Inicio:** 0:30
- **Duración:** 5:48 min
- **URL:** [https://bit.ly/43iyR14](https://bit.ly/43iyR14)
- **Resumen:** Jackeline tiene 13 años de experiencia en el rubro de servicios y mantenimiento de refrigeración, y se desempeña en el área administrativa de una empresa que atiende tanto a clientes fijos como temporales. Actualmente, gestiona los reportes técnicos con Excel y planifica las rutas a través de cronogramas manuales y aplicaciones móviles como Google Maps. Destacó que una herramienta como OsitoPolar podría marcar una diferencia sustancial en la organización de su equipo, ya que centralizaría toda la información de los equipos atendidos y permitiría la visualización en tiempo real del estado de cada unidad. Subrayó la importancia de poder ingresar datos desde el lugar de trabajo, facilitando el flujo de información y reduciendo errores administrativos. También recalcó el valor de las alertas automáticas, ya que permitirían actuar de forma inmediata ante cualquier incidente. Concluyó que una solución digital como esta no solo optimizaría procesos, sino que elevaría el estándar del servicio ofrecido. Su testimonio confirma la necesidad de profesionalización de procesos técnicos mediante tecnología accesible y especializada.

---

#### Entrevista 3:

- **Nombres y apellidos:** Santiago Vique
- **Edad:** 48
- **Distrito:** San Martín de Porres
- **Dispositivo móvil:** Samsung Galaxy S21
- **Navegador preferido:** Firefox
- **Marcas/influencias:** Grupo Backus, Grupo Mambrino, sistemas de refrigeración industrial europeos

![Interview-3-segment-2.png]( assets/chapter02/Interview-3-segment-2.png)

- **Inicio:** 0:11
- **Duración:** 7:09 min
- **URL:** [https://bit.ly/43gc8T9](https://bit.ly/43gc8T9)
- **Resumen:**  Santiago es dueño de una empresa de instalación y mantenimiento de sistemas de refrigeración industrial. Cuenta con más de una década de experiencia y trabaja con clientes de gran envergadura como el Grupo Backus y Mambrino. En la entrevista, señaló que una de sus principales dificultades es la falta de información previa sobre las fallas de los equipos al momento de coordinar servicios, lo que repercute en la preparación del personal técnico y en la eficiencia de las visitas. Actualmente emplea archivos PDF y hojas de cálculo, lo cual limita el acceso ágil y compartido de los datos. Opinó que OsitoPolar facilitaría la organización de rutas, mejoraría la trazabilidad del historial técnico de cada unidad, y permitiría preparar los materiales de forma más precisa antes de la atención. También valoró que una app así agilizaría la comunicación con los clientes, lo que podría traducirse en una mejora sustancial en la calidad del servicio. Finalmente, destacó que la digitalización le permitiría optimizar recursos, reducir tiempos de respuesta y aumentar la satisfacción del cliente. Esta entrevista confirma la demanda de herramientas profesionales que automaticen procesos críticos en empresas con operaciones complejas.
---

## 2.2.3. Análisis de entrevistas

Basándonos en las entrevistas, hemos llevado a cabo un análisis en el que destacamos los puntos compartidos y tendencias comunes entre los usuarios.

### Hallazgos para el Segmento #1: NEGOCIOS QUE UTILIZAN EQUIPOS DE REFRIGERACIÓN

- Los entrevistados administran negocios donde la refrigeración es crítica para la calidad de sus productos.
- Monitorean manualmente las temperaturas y el consumo de energía sin utilizar herramientas digitales.
- Han experimentado pérdidas económicas directas debido a fallas en los equipos de refrigeración.
- Muestran interés en recibir alertas por fallas, variaciones de temperatura o consumo energético.
- El precio es un factor decisivo para la adopción de una nueva tecnología.
- Valoran la posibilidad de probar un demo antes de comprometerse con una suscripción.
- Los negocios de mayor escala perciben mayor valor en una solución de monitoreo digital.

**Hypothesis Statement para Segmento #1:**
"Los negocios pequeños y medianos que dependen de equipos de refrigeración para mantener la calidad de sus productos sufren pérdidas económicas significativas debido a la falta de monitoreo automatizado. Una solución digital que ofrezca alertas en tiempo real sobre fallas y variaciones de temperatura, con un modelo de precios flexible, reduciría estas pérdidas y mejoraría la eficiencia operativa."

### Hallazgos para el Segmento #2: EMPRESAS PROVEEDORAS DE SERVICIOS Y EQUIPOS DE REFRIGERACIÓN

- Algunos tienen más de 10 años de experiencia en el rubro.
- Todos los entrevistados tienen como motivación principal brindar equipos de calidad y mejorar la eficiencia del servicio que ofrecen a sus clientes. Buscan optimizar los tiempos de respuesta y asegurar la satisfacción del cliente, especialmente en sectores que requieren atención técnica frecuente, como la refrigeración y el mantenimiento de equipos.
- Los entrevistados comparten una motivación común, aunque sus prioridades varían en áreas como la optimización de la gestión de datos, la precisión en las intervenciones y la atención al cliente.
- Todos mencionan que la coordinación de rutas es una dificultad, ya que actualmente se realiza de manera manual mediante WhatsApp, Google Maps, o cronogramas proporcionados por los clientes.
- La mayoría cree que a veces la labor ineficiente de coordinación del cliente es un problema, tanto para brindar su ubicación como para precisar la falla o problema de su equipo de refrigeración.
- La falta de un sistema digital que centralice y facilite el acceso a los datos de los equipos y las intervenciones es otra limitante que impacta en la eficiencia de sus operaciones.
- La mayoría de los entrevistados utilizan métodos tradicionales como Excel para gestionar el historial técnico de los equipos.
- Todos creen que una solución digital tendría un impacto positivo en su empresa.
- Ninguno ha probado antes una solución digital que mejore la venta, gestión y mantenimiento de equipos de refrigeración más allá de herramientas tradicionales.

**Análisis estadístico**

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-1-segment-2.png"
       alt="Segmento 2 del Gráfico Circular: Distribución de datos clave."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Gráfico Circular - Segmento 2.
  </figcaption>
</figure>

- Más del 50% de los empresarios tiene un número mayor a 10 años de experiencia en el rubro.

---

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-2-segment-2.png"
       alt="Segmento 2 del segundo Gráfico Circular: Proporción de satisfacción del usuario."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Gráfico Circular 2 - Segmento 2.
  </figcaption>
</figure>

- Los empresarios tienen diferentes frecuencias de ciertas dificultades, a pesar de que tienen casi los mismos problemas.

---
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-3-segment-2.png"
       alt="Segmento 2 del tercer Gráfico Circular: Datos demográficos de usuarios."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Gráfico Circular 3 - Segmento 2.
  </figcaption>
</figure>

- El 67% de los empresarios creen que el cliente es parcialmente causante de su problema de mayor frecuencia. Algunos de ellos han expresado su inconformidad respecto a los clientes que no explican bien las fallas de sus equipos.

---

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-4-segment-2.png"
       alt="Segmento 2 del cuarto Gráfico Circular: Preferencias de los usuarios por características."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 4:</strong> Gráfico Circular 4 - Segmento 2.
  </figcaption>
</figure>

- El 100% está interesado en recibir notificaciones sobre fallos que ocurren en equipos de refrigeración. Ellos creen que con dicha funcionalidad podrían hacer un mantenimiento preventivo más eficiente y lograr la satisfacción del cliente.

---
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-5-segment-2.png"
       alt="Segmento 2 del quinto Gráfico Circular: Fuentes de información preferidas por los usuarios."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 5:</strong> Gráfico Circular 5 - Segmento 2.
  </figcaption>
</figure>

- Ni uno de los empresarios ha usado una plataforma digital que se asemeje a la que se muestran interesados. Ellos usaron aplicaciones para mejorar la eficiencia de su trabajo como WhatsApp y Maps o programas como Microsoft Excel. Sin embargo, estos no poseen todas las funcionalidades que necesitan.

---
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-6-segment-2.png"
       alt="Segmento 2 del sexto Gráfico Circular: Nivel de satisfacción general del producto."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 6:</strong> Gráfico Circular 6 - Segmento 2.
  </figcaption>
</figure>

- Cada empresario tiene una meta deseada de mayor prioridad diferente al resto a pesar de que todos ellos comparten los mismos deseos y esperan que una plataforma digital pueda ayudarles a obtenerlos.

---

### 2.3. Needfinding.

#### 2.3.1. User Personas.
En esta sección se presentan las fichas de User Personas construidas a partir de los datos recogidos del análisis de entrevistas al segmento #1: "Negocios que utilizan equipos de refrigeración" y al segmento #2: "Empresas proveedoras de servicios y equipos de refrigeración". Estas fichas permiten representar de forma clara y estratégica los perfiles del segmento objetivo, considerando sus metas, habilidades, motivaciones y dificultades. Al integrar tanto la perspectiva del usuario como las tendencias del sector, estas representaciones sirven como una herramienta clave para el diseño de soluciones digitales centradas en el usuario y alineadas con las oportunidades del mercado.

##### Segmento objetivo #1: Negocios que utilizan equipos de refrigeración
<figure style="text-align: center;">
  <img src="assets/chapter02/UserPersona-Carolina_Garcia.png" 
       alt="User Persona: Carolina García, descripción detallada del perfil de usuario." 
       style="max-width: 90%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> User Persona - Carolina García.
  </figcaption>
</figure>

<br/>
<br/>
<br/>

##### Segmento objetivo #2: Empresas proveedoras de servicios y equipos de refrigeración
<figure style="text-align: center;">
  <img src="assets/chapter02/UserPersona-Luis-Rojas.png"
       alt="User Persona: Luis Rojas, descripción detallada de sus características y necesidades."
       style="max-width: 90%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> User Persona - Luis Rojas.
  </figcaption>
</figure>

#### 2.3.2. User Task Matrix.

En esta sección se presenta el User Task Matrix, construido a partir de los User Persona que representan a los dos segmentos clave identificados:

Segmento 1: Negocios que utilizan equipos de refrigeración (representado por Carolina García).

Segmento 2: Empresas proveedoras de servicios y equipos de refrigeración (representado por Luis Rojas).

Las tareas fueron identificadas a partir del análisis cualitativo de entrevistas, y cada una fue evaluada según su frecuencia y nivel de importancia para los respectivos perfiles.



<table>
  <tr>
    <th rowspan="2">Tarea / Task</th>
    <th colspan="2">Carolina García</th>
    <th colspan="2">Luis Rojas</th>
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
  <tr>
    <td>Detectar o identificar fallas en los equipos</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Coordinar servicios de mantenimiento</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Planificar rutas de llegada al punto de atención</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Realizar mantenimiento preventivo o solicitarlo</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Gestionar datos de los equipos de refrigeración</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Gestionar costos por pérdidas de productos</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Evaluar la calidad de los equipos y servicios brindados</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Monitorear el desempeño de los técnicos</td>
    <td>Baja</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Monitorear el desempeño de los equipos brindados</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Usar reportes técnicos para tomar decisiones</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Comunicar fallas al técnico o proveedor</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
</table>

**Análisis**


#### 2.3.3. User Journey Mapping.
**Segmento objetivo #1: Negocios que utilizan equipos de refrigeración**
Este User Journey Map representa el recorrido actual de Carolina García. El mapa ilustra su experiencia completa desde que maneja continuamente los datos registrados de la empresa hasta su seguimiento luego de la realización de la venta o servicio.
Esta sección refleja la situación actual sin intervención de soluciones tecnológicas, mostrando los puntos de contacto, tareas clave, emociones y posibles fricciones que enfrenta en su día a día. Este recorrido permite entender los desafíos que enfrenta Carolina.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/JourneyMap-segment-1.png"
       alt="Segmento 1 del Journey Map: Etapa de Descubrimiento de necesidades del usuario."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Segmento 1 del Journey Map.
  </figcaption>
</figure>

**Segmento objetivo #2: EMPRESAS PROVEEDORAS DE SERVICIOS Y EQUIPOS DE REFRIGERACIÓN**

Este User Journey Map representa el recorrido actual de Luis Rojas. El mapa ilustra su experiencia completa desde que maneja continuamente los datos registrados de la empresa hasta su seguimiento luego de la realización de la venta o servicio.
Esta sección refleja la situación actual sin intervención de soluciones tecnológicas, mostrando los puntos de contacto, tareas clave, emociones y posibles fricciones que enfrenta en su día a día. Este recorrido permite entender los desafíos que enfrenta Luis.
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/JourneyMap-segment-2.png"
       alt="Segmento 2 del Journey Map: Etapa de Consideración y Evaluación."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Segmento 2 del Journey Map.
  </figcaption>
</figure>

#### 2.3.4. Empathy Mapping.

**Segmento objetivo #1: Negocios que utilizan equipos de refrigeración**
<figure style="text-align: center;">
  <img src="assets/chapter02/EmpathyMap-segment-1.png"
       alt="Segmento 1 del Mapa de Empatía: Qué piensa y siente el usuario."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Segmento 1 del Mapa de Empatía.
  </figcaption>
</figure>

<br/>


**Segmento objetivo #2: EMPRESAS PROVEEDORAS DE SERVICIOS Y EQUIPOS DE REFRIGERACIÓN**
<figure style="text-align: center;">
  <img src="assets/chapter02/EmpathyMap-segment-2.png"
       alt="Segmento 2 del Mapa de Empatía: Qué ve y qué oye el usuario."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Segmento 2 del Mapa de Empatía.
  </figcaption>
</figure>


<div style="page-break-after: always"></div>

#### 2.3.5. As-is Scenario Mapping.

En esta sección, nuestro equipo tomó en cuenta las etapas para su desarrollo. Iniciamos con la recolección de información proveniente de las entrevistas y análisis de estas de cada segmento respectivo, seguida de una lluvia de ideas, una revisión en conjunto e identificación de las fases y las áreas positivas y negativas.
Una vez definido todo, procedimos a crear los As-is Scenario Mapping vinculados a cada User Persona en la plataforma Miro.
Desde la perspectiva del usuario, este mapa nos permite visualizar su situación real: acciones actuales, emociones, pensamientos, puntos de dolor, etc.


**Segmento objetivo #2: EMPRESAS PROVEEDORAS DE SERVICIOS Y EQUIPOS DE REFRIGERACIÓN**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/As-is-Scenario-segment-2.jpg"
       alt="Segmento 2 del Escenario As-Is: Fases de interacción actual del usuario con el producto."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Segmento 2 del Escenario As-Is.
  </figcaption>
</figure>

### 2.4. Big Picture EventStorming.

> **Falta:** completar el Big Picture EventStorming con el diagrama/captura correspondiente y una explicaci�n breve de los eventos principales del dominio, actores, comandos, pol�ticas y sistemas externos identificados.

### 2.5. Ubiquitous Language.


1. **User Profile (Perfil de Usuario):** Datos e información operativa que OsitoPolar recopila de cada usuario para personalizar su experiencia.

2. **Smart Dashboard (Panel Inteligente):** Interfaz central donde los usuarios monitorean el estado de sus equipos, reciben alertas y gestionan sus servicios.

3. **Performance Report (Reporte de Rendimiento):** Informe técnico con historial de uso, consumo energético, temperatura y fallas de cada equipo.

4. **Maintenance Schedule (Agenda de Mantenimientos):** Calendario inteligente para programar mantenimientos preventivos o correctivos.

5. **Failure Alert (Alerta de Falla):** Notificación automática ante anomalías críticas como sobrecalentamiento o cortes de energía.

6. **Equipment Inventory (Inventario de Equipos):** Registro de todos los equipos de congelación con sus datos técnicos y ubicación.

7. **Service Provider (Proveedor de Servicio):** Técnico o empresa que brinda mantenimiento, instalación o reparación de equipos de refrigeración.

8. **Technical History (Historial Técnico):** Registro detallado de todas las intervenciones realizadas a un equipo.

9. **Work Order (Orden de Trabajo):** Documento digital con las tareas asignadas a un técnico para una visita de servicio.

10. **Service Coordination (Coordinación de Servicio):** Proceso de conexión entre clientes y proveedores según disponibilidad, ubicación y necesidad.

11. **Automatic Report Generation (Generación Automática de Reportes):** Función que crea informes técnicos sin intervención manual.

12. **Real-Time Monitoring (Monitoreo en Tiempo Real):** Supervisión constante del estado operativo del equipo (temperatura, consumo, uso).

13. **Service Zone (Zona de Servicio):** Área donde un proveedor puede atender equipos con rapidez y eficiencia.

14. **Client Portfolio (Cartera de Clientes):** Lista de negocios atendidos por un proveedor, con sus datos y equipos registrados.

15. **Cold Equipment (Equipo de Congelación):** Unidad de refrigeración usada para conservar productos, como congeladoras, cámaras o vitrinas.

16. **Energy Consumption (Consumo Energético):** Registro del uso eléctrico de los equipos para detectar anomalías y optimizar recursos.

17. **Preventive Maintenance (Mantenimiento Preventivo):** Servicio planificado para evitar fallas y extender la vida útil del equipo.

18. **Corrective Maintenance (Mantenimiento Correctivo):** Servicio realizado para solucionar una falla existente en un equipo.

19. **Notification (Notificación):** Mensajes enviados automáticamente para informar sobre mantenimientos, fallas o cambios importantes.

<div style="page-break-after: always"></div>

## Capítulo III: Requirements Specification

### 3.1. User Stories.

Las historias de usuario desarrolladas en este proyecto fueron elaboradas en conjunto por el equipo de desarrollo de OsitoPolar, considerando las necesidades y funcionalidades clave tanto para los clientes (dueños de equipos de refrigeración) como para los empresarios (proveedores de equipos y servicios de mantenimiento y refrigeración). Las historias fueron organizadas bajo épicas que agrupan funcionalidades similares. Los criterios de aceptación de todas las historias siguen la sintaxis Gherkin.
El trabajo fue realizado de manera colaborativa, priorizando la comprensión del problema desde la perspectiva del usuario final. Para facilitar la organización, priorización y trazabilidad de las tareas, se utilizó la plataforma Trello

| **Epic / Story ID** | **Título**                                                         | **Descripción**                                                                                                                                                                                                                    | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | **Relacionado con (Epic ID)** |
|---------------------|--------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| US-01               | Registro de usuario                                                | Como nuevo usuario, quiero registrarme para acceder a la plataforma y empezar a gestionar mis equipos de refrigeración                                                                                                             | **Escenario 1: Crear cuenta exitosamente** <br/> Dado que el nuevo usuario tiene todos los datos correctos, cuando completa el registro, entonces su cuenta es creada correctamente.<br/> **Escenario 2: Intento de crear cuenta con email ya registrado**<br/> Dado que el nuevo usuario intenta registrarse con un correo ya registrado, cuando envía el formulario, entonces el sistema muestra un mensaje indicando que el correo ya existe.                                                                                                                                                                    | EP-01                         |
| US-02               | Inicio de sesión                                                   | Como usuario, quiero acceder a mi cuenta en la plataforma para utilizar sus funcionalidades.                                                                                                                                       | **Escenario 1: Iniciar sesión correctamente** <br/> Dado que el usuario tiene una cuenta activa, cuando ingresa sus datos correctamente, entonces accede a su panel de control.<br/> **Escenario 2: Intento de iniciar sesión con datos incorrectos**<br/> Dado que el usuario ingresa datos incorrectos, cuando intenta iniciar sesión, entonces el sistema muestra un mensaje de error.                                                                                                                                                                                                                           | EP-01                         |
| US-03               | Solicitar servicio de reparación                                   | Como cliente, quiero solicitar un servicio de reparación para mis equipos de refrigeración cuando detecto fallas.                                                                                                                  | **Escenario 1: Solicitar servicio de reparación** <br/> Dado que el cliente ha identificado una falla, cuando solicita el servicio desde la plataforma, entonces se genera la solicitud de servicio.<br/> **Escenario 2: Confirmación de solicitud de servicio**<br/> Dado que el cliente ha solicitado el servicio, cuando el sistema recibe la solicitud, entonces muestra un mensaje confirmando la recepción.                                                                                                                                                                                                   | EP-03                         |
| US-04               | Ver estado del servicio solicitado                                 | Como cliente, quiero ver el estado actual de mi solicitud de servicio para estar informado sobre el avance del proceso.                                                                                                            | **Escenario 1: Verificación del estado de la solicitud**<br/>  Dado que el cliente ha solicitado el servicio, cuando ingresa a la plataforma, entonces puede ver el estado actualizado de su solicitud.<br/> **Escenario 2: Actualización de estado en tiempo real**<br/> Dado que el cliente está visualizando su solicitud, cuando el técnico inicia el trabajo, entonces el estado se actualiza.                                                                                                                                                                                                                 | EP-03                         |
| US-05               | Ver reporte de servicio realizado                                  | Como cliente, quiero ver el reporte de servicio detallado para saber qué reparaciones se hicieron en mi equipo.                                                                                                                    | **Escenario 1: Generación del reporte de servicio**<br/> Dado que el servicio ha sido completado, cuando el técnico termina, entonces el sistema genera un reporte detallado. <br/>**Escenario 2: Enviar reporte al cliente por correo** Dado que el reporte ha sido generado, cuando se ha finalizado el servicio, entonces el sistema envía el reporte al cliente por correo electrónico.                                                                                                                                                                                                                         | EP-04                         |
| US-06               | Agregar equipos                                                    | Como cliente, quiero agregar mis equipos de refrigeración en la plataforma para llevar un control.                                                                                                                                 | **Escenario 1: Agregar equipo de refrigeración**<br/>Dado que el cliente quiere agregar un equipo, cuando ingresa los detalles del equipo, entonces el sistema lo registra correctamente. <br/>**Escenario 2: Editar información del equipo** <br/> Dado que el cliente desea editar la información del equipo, cuando realiza los cambios, entonces el sistema actualiza la información del equipo.                                                                                                                                                                                                                | EP-02                         |
| US-07               | Recibir alerta de falla en equipo                                  | Como cliente, quiero recibir una alerta automática cuando mi equipo de refrigeración presente una falla para tomar acción rápidamente.                                                                                             | **Escenario 1: Alerta de falla detectada** <br/> Dado que el equipo de refrigeración está funcionando mal, cuando se detecta una falla, entonces el sistema envía una alerta al cliente. <br/>**Escenario 2: Alerta de mantenimiento preventivo** Dado que el equipo está funcionando correctamente, cuando el sistema detecta una necesidad de mantenimiento preventivo, entonces envía una alerta preventiva al cliente.                                                                                                                                                                                          | EP-05                         |
| US-08               | Solicitar mantenimiento preventivo                                 | Como cliente, quiero solicitar mantenimiento preventivo para evitar fallas futuras en mis equipos de refrigeración.                                                                                                                | **Escenario 1: Solicitar mantenimiento preventivo**<br/> Dado que el cliente quiere programar mantenimiento preventivo, cuando selecciona la opción, entonces puede elegir la fecha y hora. <br/>**Escenario 2: Confirmación de solicitud de mantenimiento** <br/> Dado que el cliente ha solicitado el mantenimiento, cuando el sistema lo registra, entonces le envía una confirmación con los detalles.                                                                                                                                                                                                          | EP-03                         |
| US-09               | Ver consumo energético de equipos                                  | Como cliente, quiero ver un informe del consumo energético de mis equipos para analizar su eficiencia.                                                                                                                             | **Escenario 1: Visualización de consumo energético** <br/>Dado que el cliente tiene equipos registrados, cuando ingresa a la plataforma, entonces puede ver el informe de consumo energético de cada equipo. <br/>**Escenario 2: Comparación del consumo energético** <br/> Dado que el cliente quiere comparar, cuando selecciona dos equipos, entonces el sistema genera una comparación de su consumo energético.                                                                                                                                                                                                | EP-04                         |
| US-10               | Recepción de alertas automáticas para servicio                     | Como empresario, quiero recibir alertas automáticas cuando un cliente solicite un servicio de reparación o mantenimiento para brindar el servicio inmediatamente.                                                                  | **Escenario 1: Recepción de solicitud de servicio**<br/>Dado que el cliente ha solicitado un servicio, cuando se recibe la solicitud, entonces el sistema envía una alerta al empresario. <br/>**Escenario 2: Alerta de mantenimiento preventivo solicitado**<br/> Dado que un cliente ha solicitado mantenimiento preventivo, cuando se registra la solicitud, entonces el sistema envía una alerta automática al empresario.                                                                                                                                                                                      | EP-05                         |
| US-11               | Asignar técnico a solicitud de servicio                            | Como empresario, quiero asignar un técnico a una solicitud de servicio para garantizar que se realice el trabajo adecuado.                                                                                                         | **Escenario 1: Asignar técnico a servicio**<br/>Escenario 1: Dado que el empresario recibe una solicitud de servicio, cuando elige un técnico, entonces el sistema asigna al técnico seleccionado a la solicitud. <br/>**Escenario 2: Confirmación de asignación de técnico**<br/>Dado que el técnico ha sido asignado, cuando el empresario lo confirma, entonces el sistema envía una notificación al técnico con los detalles.                                                                                                                                                                                   | EP-03                         |
| US-12               | Ver historial de servicios realizados                              | Como empresario, quiero ver el historial de servicios realizados para cada cliente y equipo, para llevar un control adecuado.                                                                                                      | **Escenario 1: Visualizar historial de servicios**<br/> Dado que el empresario tiene acceso al historial de servicios, cuando accede a la plataforma, entonces puede ver el historial completo de servicios realizados. <br/>**Escenario 2: Filtrar historial por cliente o equipo**<br/>Dado que el empresario quiere filtrar los servicios, cuando selecciona un cliente o equipo, entonces el sistema filtra los servicios realizados según el filtro seleccionado                                                                                                                                               | EP-04                         |
| US-13               | Realizar seguimiento a solicitudes de servicio                     | Como empresario, quiero realizar un seguimiento detallado a las solicitudes de servicio de mis técnicos, para saber cómo van.                                                                                                      | **Escenario 1: Ver estado de la solicitud de servicio**<br/> Dado que el empresario tiene acceso a solicitudes, cuando ingresa al sistema, entonces puede ver el estado actualizado de cada solicitud de servicio. <br/>**Escenario 2: Actualización del estado de la solicitud**<br/>Dado que el empresario quiere seguir el progreso, cuando un técnico actualiza el estado de la solicitud, entonces el sistema muestra el estado en tiempo real.                                                                                                                                                                | EP-03                         |
| US-14               | Generar reporte de desempeño de técnicos                           | Como empresario, quiero generar reportes sobre el desempeño de mis técnicos para evaluar su eficiencia y productividad.                                                                                                            | **Escenario 1: Generar reporte de desempeño**<br/> Dado que el empresario quiere evaluar el desempeño de sus técnicos, cuando selecciona la opción de generar reporte, entonces el sistema crea un informe con los datos. <br/>** Escenario 2: Descargar reporte de desempeño**<br/>Dado que el reporte ha sido generado, cuando el empresario quiere descargarlo, entonces el sistema permite descargar el archivo en formato PDF.                                                                                                                                                                                 | EP-04                         |
| US-15               | Configurar alertas de mantenimiento                                | Como empresario, quiero configurar alertas automáticas para el mantenimiento preventivo de los equipos.                                                                                                                            | **Escenario 1: Configuración de alerta de mantenimiento**<br/> Dado que el empresario quiere configurar alertas, cuando ingresa los parámetros, entonces el sistema configura la alerta correctamente. <br/>**Escenario 2: Modificación de alerta configurada**<br/> Dado que el empresario ha configurado una alerta, cuando decide cambiar la frecuencia, entonces el sistema actualiza la alerta.                                                                                                                                                                                                                | EP-05                         |
| US-16               | Visualizar clientes y servicios asociados                          | Como empresario, quiero ver todos los clientes que han solicitado servicio para organizar el trabajo de los técnicos.                                                                                                              | **Escenario 1: Ver clientes y servicios asociados**<br/>Dado que el empresario quiere visualizar la información, cuando accede a la funcionalidad correspondiente, entonces puede consultar los clientes con sus servicios relacionados.<br/>**Escenario 2: Filtrar por estado de servicio**<br/>Dado que el empresario necesita filtrar resultados, cuando aplica el filtro por estado, entonces el sistema muestra los datos correspondientes.                                                                                                                                                                    | EP-04                         |
| US-17               | Visualizar equipos entregados a clientes                           | Como empresario, quiero ver todos los equipos que fueron entregados a clientes para realizar su seguimiento.                                                                                                                       | **Escenario 1: Ver equipos asociados**<br/>Dado que el empresario quiere visualizar la información de equipos, cuando accede al listado de equipos, entonces puede consultar los que están asociados a clientes.<br/>**Escenario 2: Filtrar por estado y tipo de equipo**<br/>Dado que el empresario necesita filtrar los resultados, cuando aplica los criterios, entonces el sistema muestra los equipos correspondientes.                                                                                                                                                                                        | EP-02                         |
| US-18               | Recibir notificaciones de eventos importantes                      | Como cliente, quiero recibir notificaciones sobre eventos importantes como el progreso del servicio para mantenerme informado.                                                                                                     | **Escenario 1: Problema reportado durante el servicio**<br/>Dado que el técnico detecta una complicación o requiere aprobación, cuando se genera un evento interno, entonces el sistema envía una notificación que requiere acción del cliente.<br/>**Escenario 2: Notificación sobre progreso del servicio**<br/>Dado que el servicio está en ejecución, cuando el estado cambia, entonces se envía una notificación al cliente.                                                                                                                                                                                   | EP-05                         |
| US-19               | Realizar evaluación de servicio                                    | Como cliente, quiero evaluar el servicio para mostrar mi conformidad.                                                                                                                                                              | **Escenario 1: Evaluar el servicio una vez finalizado**<br/>Dado que el cliente ha recibido el servicio, cuando accede a la opción de evaluación, entonces puede registrar una calificación del 1 al 5.<br/>**Escenario 2: Corrección de evaluación del servicio**<br/>Dado que el cliente ya evaluó el servicio, cuando realiza una modificación dentro del plazo permitido, entonces el sistema actualiza la calificación registrada.                                                                                                                                                                             | EP-06                         |
| US-20               | Registrar técnicos                                                 | Como empresario, quiero registrar técnicos en la plataforma para integrarlos a mi red de soporte técnico.                                                                                                                          | **Escenario 1: Registro exitoso de un técnico**<br/>Dado que el empresario desea registrar un técnico, cuando completa los datos requeridos y confirma, entonces el sistema lo registra correctamente.<br/>**Escenario 2: Intento de registro con datos incompletos**<br/>Dado que faltan datos obligatorios, cuando intenta registrar al técnico, entonces el sistema impide la operación hasta que se completen los campos necesarios.                                                                                                                                                                            | EP-01                         |
| US-21               | Visualizar perfil del técnico                                      | Como empresario, quiero visualizar el perfil de cada técnico, incluyendo sus datos personales y métricas de desempeño, para evaluar su rendimiento.                                                                                | **Escenario 1: Acceso a información completa del técnico**<br/>Dado que el empresario selecciona un técnico, cuando accede a su información, entonces puede consultar datos personales, historial de servicios y calificaciones.<br/>**Escenario 2: Técnico sin evaluaciones registradas**<br/>Dado que el técnico aún no ha sido evaluado, cuando se consulta su perfil, entonces no se muestran métricas de desempeño.                                                                                                                                                                                            | EP-01                         |
| US-22               | Recibir alertas de fallas en equipos                               | Como empresario, quiero recibir alertas cuando alguno de los equipos de mis clientes presenta fallas, para notificar al cliente y organizar atención.                                                                              | **Escenario 1: Recepción de alerta automática por sensor**<br/>Dado que un equipo monitoreado presenta una falla, cuando el sistema la detecta, entonces genera una alerta inmediata para el empresario.<br/>**Escenario 2: Comunicación con el cliente**<br/>Dado que el empresario ha recibido una alerta, cuando revisa el equipo afectado, entonces puede iniciar una notificación directa al cliente desde la plataforma.                                                                                                                                                                                      | EP-05                         |
| US-23               | Visualizar propuesta de valor principal                            | Como visitante, quiero conocer la propuesta de valor de OsitoPolar, para entender si la plataforma se ajusta a mis necesidades.                                                                                                    | **Escenario 1: Propuesta visible al ingresar**<br/>Dado que estoy en la página oficial de OsitoPolar, cuando la página carga, entonces debo acceder inmediatamente a una frase que explique claramente la propuesta de valor.<br/>**Escenario 2: Propuesta orientada a gestión de refrigeración**<br/>Dado que soy un visitante del segmento 1, cuando reviso la propuesta de valor, entonces esta debe mencionar conceptos relacionados con gestión inteligente y monitoreo de equipos.                                                                                                                            | EP-07                         |
| US-24               | Explorar soluciones específicas para mi rubro                      | Como visitante, quiero conocer las soluciones específicas que ofrece OsitoPolar para mi tipo de negocio, para saber si se ajusta a mis necesidades.                                                                                | **Escenario 1: Acceso a información para negocios**<br/>Dado que accedo a las soluciones ofrecidas, cuando reviso el contenido disponible, entonces debo encontrar descripciones específicas dirigidas a negocios que utilizan o gestionan equipos de refrigeración.<br/>**Escenario 2: Acceso a información para empresas proveedoras**<br/>Dado que accedo a las soluciones ofrecidas, cuando reviso el contenido disponible, entonces debo encontrar información específica para empresas proveedoras de equipos o servicios de mantenimiento.                                                                   | EP-07                         |
| US-25               | Comprender funcionalidades destacadas                              | Como visitante, quiero comprender las funcionalidades clave de la plataforma, para evaluar si se adapta a mi operación.                                                                                                            | **Escenario 1: Acceso a funcionalidades principales**<br/>Dado que consulto las características de la plataforma, cuando reviso la lista de funcionalidades, entonces debo identificar opciones clave como monitoreo en tiempo real, automatización de alertas y gestión remota.<br/>**Escenario 2: Descripciones orientadas a valor**<br/>Dado que leo las descripciones de las funcionalidades, cuando evalúo cada una, entonces debo entender el beneficio que aporta para operaciones de refrigeración o mantenimiento.                                                                                         | EP-07                         |
| US-26               | Solicitar una demo fácilmente                                      | Como visitante, quiero solicitar una demo de la plataforma, para iniciar contacto con OsitoPolar.                                                                                                                                  | **Escenario 1: Disponibilidad de opción para solicitar demo**<br/>Dado que estoy explorando la plataforma, cuando busco cómo solicitar una demostración, entonces debo encontrar una opción clara y accesible para iniciar el proceso.<br/>**Escenario 2: Acceso a canal de contacto**<br/>Dado que selecciono la opción de solicitar una demo, cuando soy redirigido, entonces debo acceder a un canal funcional de contacto como un formulario, correo electrónico o enlace directo.                                                                                                                              | EP-07                         |
| US-27               | Conocer misión y visión de la startup                              | Como visitante, quiero conocer la misión y visión de OsitoPolar, para entender su enfoque y propuesta de valor.                                                                                                                    | **Escenario 1: Acceso a la misión de la empresa**<br/>Dado que accedo a la información institucional de OsitoPolar, cuando reviso su contenido corporativo, entonces debo encontrar una descripción clara de su misión.<br/>**Escenario 2: Acceso a la visión de la empresa**<br/>Dado que accedo a la información institucional, cuando reviso su contenido estratégico, entonces debo encontrar una descripción clara de su visión a futuro.                                                                                                                                                                      | EP-07                         |
| US-28               | Contactar fácilmente con ventas                                    | Como visitante empresario, quiero contactar fácilmente con el equipo de ventas, para iniciar una posible relación comercial.                                                                                                       | **Escenario 1: Disponibilidad de medio de contacto comercial**<br/>Dado que estoy interesado en contactar al equipo de ventas, cuando busco información de contacto, entonces debo encontrar una opción clara para iniciar la comunicación.<br/>**Escenario 2: Redirección al canal adecuado**<br/>Dado que selecciono la opción de contacto, cuando soy redirigido, entonces debo llegar a un canal funcional como un formulario, dirección de correo o número de contacto.                                                                                                                                        | EP-07                         |
| US-29               | Acceder fácilmente a la plataforma                                 | Como visitante, quiero acceder fácilmente al inicio de sesión, para ingresar rápidamente a mi cuenta.                                                                                                                              | **Escenario 1: Acceso al inicio de sesión**<br/>Dado que soy un usuario registrado, cuando busco cómo ingresar a mi cuenta, entonces debo encontrar una opción claramente identificable para iniciar sesión.<br/>**Escenario 2: Redirección al formulario de autenticación**<br/>Dado que selecciono la opción de inicio de sesión, cuando soy redirigido, entonces debo llegar al formulario correspondiente para ingresar mis credenciales.                                                                                                                                                                       | EP-07                         |
| US-30               | Descargar la app móvil desde la web                                | Como visitante interesado en usar OsitoPolar desde el celular, quiero descargar fácilmente la app móvil, para instalarla y comenzar a usarla.                                                                                      | **Escenario 1: Acceso a opciones de descarga móvil**<br/>Dado que estoy interesado en utilizar la aplicación en mi celular, cuando exploro la plataforma, entonces debo encontrar un enlace o referencia a la descarga de la app móvil.<br/>**Escenario 2: Redirección a la tienda correspondiente**<br/>Dado que selecciono el enlace de descarga, cuando soy redirigido, entonces debo acceder a la tienda de aplicaciones correspondiente según mi sistema operativo.                                                                                                                                            | EP-07                         |
| US-31               | Controlar encendido y apagado del equipo                           | Como cliente, quiero poder encender y apagar remotamente mis equipos de refrigeración desde la plataforma, para tener un mayor control operativo.                                                                                  | **Escenario 1: Encendido remoto del equipo**<br/>Dado que el cliente tiene un equipo registrado, cuando ejecuta una acción de encendido sobre el equipo, entonces el sistema transmite la instrucción y cambia el estado del equipo a encendido.<br/>**Escenario 2: Apagado remoto del equipo**<br/>Dado que el cliente tiene un equipo activo, cuando ejecuta una acción de apagado, entonces el sistema transmite la instrucción y cambia el estado del equipo a apagado.                                                                                                                                         | EP-02                         |
| US-32               | Ajustar temperatura del equipo                                     | Como cliente, quiero ajustar la temperatura de mis equipos de refrigeración desde la plataforma, para mantener condiciones óptimas según mi operación.                                                                             | **Escenario 1: Aumentar temperatura**<br/>Dado que el cliente tiene acceso a un equipo, cuando incrementa el valor de temperatura deseada, entonces el sistema actualiza la configuración del equipo con el nuevo valor.<br/>**Escenario 2: Disminuir temperatura**<br/>Dado que el cliente tiene acceso a un equipo, cuando reduce el valor de temperatura deseada, entonces el sistema actualiza la configuración del equipo con el nuevo valor.                                                                                                                                                                  | EP-02                         |
| TS-33               | Registrar nuevo equipo a través de API RESTful                     | Como desarrollador, quiero exponer un endpoint RESTful que permita registrar nuevos equipos de refrigeración, para facilitar su control y monitoreo desde la plataforma.                                                           | **Escenario 1: Registro exitoso**<br/>Dado que el endpoint `/equipment` está disponible, cuando se envía una solicitud POST con los datos válidos (nombre, tipo, ubicación, etc.), entonces se recibe una respuesta con estado 201 y los datos del equipo registrado.<br/>**Escenario 2: Registro con datos inválidos**<br/>Dado que el endpoint está disponible, cuando se envía una solicitud POST con campos obligatorios vacíos o mal formateados, entonces se recibe una respuesta 400 con mensaje "Invalid or incomplete data".                                                                               | EP-02                         |
| TS-34               | Eliminar técnico asignado a través de API RESTful                  | Como desarrollador, quiero eliminar un técnico del sistema desde el API para gestionar la asignación de servicios y roles técnicos.                                                                                                | **Escenario 1: Técnico eliminado correctamente**<br/>Dado que el endpoint `/technicians/{id}` está disponible y el ID existe, cuando se hace un DELETE, entonces se devuelve código 204 y el técnico es removido del sistema.<br/>**Escenario 2: Intentar eliminar técnico inexistente**<br/>Dado que el ID del técnico no existe, cando se hace un DELETE,entonces se devuelve código 404 con mensaje "Technician not found".                                                                                                                                                                                      | EP-01                         |
| TS-35               | Notificación automática por alerta crítica a través de API RESTful | Como desarrollador, quiero implementar un mecanismo que exponga alertas críticas detectadas en los equipos a través de una API RESTful, para activar notificaciones automáticas al usuario.                                        | **Escenario 1: Envío de notificación al detectar falla**<br/>Dado que el sistema recibe una alerta crítica desde un equipo, cuando se procesa la alerta, entonces el sistema debe enviar una notificación al usuario.**Escenario 2: Falla detectada sin notificación activa**<br/>Dado que el sistema de notificaciones está deshabilitado, cuando se genera la alerta crítica, entonces no se envía notificación y se registra solo en el historial.                                                                                                                                                               | EP-05                         |
| TS-36               | Crear solicitud de mantenimiento a través de API RESTful           | Como desarrollador, quiero implementar una API que me permita crear solicitudes de mantenimiento para que los negocios reporten necesidades de soporte técnico.                                                                    | **Escenario 1: Creación exitosa de solicitud**<br/>Dado que el endpoint `/api/v1/maintenance-requests` está disponible, cuando se envía una solicitud POST con los datos del equipo y la descripción del problema, entonces se recibe una respuesta 201 y se guarda la solicitud en el sistema.<br/>**Escenario 2: Datos incompletos en la solicitud**<br/>Dado que el endpoint está disponible, cuando se omite un campo obligatorio (como el ID del equipo), entonces  se recibe una respuesta 400 con mensaje "Invalid data".                                                                                    | EP-03                         |
| TS-37               | Crear registro de intervención técnica a través de API RESTful     | Como desarrollador, quiero registrar intervenciones técnicas realizadas a través de la API, para llevar seguimiento del mantenimiento.                                                                                             | **Escenario 1: Registro exitoso** Dado que el endpoint `/api/v1/interventions` está disponible, cuando  se envía una solicitud POST con los datos del técnico y equipo, entonces  el sistema responde con 201 y se almacena el registro.<br/>**Escenario 2: Registro con técnico no existente**<br/>Dado que el ID del técnico no existe, cuando se realiza la solicitud POST, entonces  se devuelve un 404 con mensaje "Technician not found".                                                                                                                                                                     | EP-03                         |
| TS-38               | Registrar evento de alerta manual a través de API RESTful          | Como desarrollador, quiero registrar una alerta manual vía API para que los técnicos puedan ingresar incidentes detectados en campo.                                                                                               | **Escenario 1: Registrar alerta manual correctamente**<br/>Dado que el endpoint `/api/v1/alerts` está activo, cuando  se envía una solicitud POST con tipo de alerta, equipo y descripción, entonces  se responde con estado 201 y se almacena el evento.<br/>**Escenario 2: Registrar alerta sin equipo asociado**<br/>Dado que se omite el ID del equipo en la solicitud, cuando se hace el POST, entonces se responde con estado 400 y mensaje "Device must be specified".                                                                                                                                      | EP-05                         |
| TS-39               | Evaluar servicio a través de API RESTful                           | Como desarrollador, quiero implementar un endpoint RESTful que permita a los clientes registrar y actualizar una evaluación de servicio, para reflejar su experiencia.                                                             | **Escenario 1: Evaluación inicial del servicio**<br/>Dado que el endpoint `/api/v1/reviews` está disponible y el cliente ha recibido un servicio, cuando se envía una solicitud POST con la puntuación (1-5), entonces el sistema responde con 201 y almacena la evaluación asociada al servicio correspondiente.<br/>**Escenario 2: Edición dentro del plazo permitido**<br/> Dado que el cliente ya evaluó un servicio y han pasado menos de 48 horas, cuando realiza una solicitud PUT a /api/v1/reviews/{id} con una nueva puntuación, entonces el sistema responde con 200 y actualiza la evaluación anterior. | EP-06                         |
| TS-40               | Registrar nuevo usuario a través de API RESTful                    | Como desarrollador, quiero exponer un endpoint para registrar nuevos usuarios en la plataforma, validando datos como correo único y formato de contraseña, para permitir el acceso seguro de nuevos usuarios.                      | **Escenario 1: Registro exitoso**<br/>Dado que el endpoint `/api/v1/users` está disponible, cuando se envía una solicitud POST con datos válidos (nombre, email único, contraseña válida), entonces el sistema responde con 201 y devuelve el usuario registrado.<br/>**Escenario 2: Registro con email existente**<br/>Dado un correo ya registrado, cuando se intenta registrar nuevamente, entonces se devuelve un 400 con mensaje "Email already registered".                                                                                                                                                   | EP-01                         |
| TS-41               | Consultar estado de solicitud de servicio por API                  | Como desarrollador, quiero exponer un endpoint para consultar el estado de una solicitud de servicio, permitiendo a clientes y empresarios hacer seguimiento en tiempo real desde la plataforma.                                   | **Escenario 1: Consulta exitosa del estado**<br/>Dado que el endpoint `/api/v1/requests/{id}` está disponible, cuando se envía una solicitud GET con un ID válido, entonces el sistema responde con 200 y devuelve el estado actual de la solicitud.<br/>**Escenario 2: Consulta con ID inexistente**<br/>Dado que el ID no existe, entonces se devuelve 404 con mensaje "Request not found".                                                                                                                                                                                                                       | EP-03                         |
| TS-42               | Solicitar mantenimiento preventivo vía API                         | Como desarrollador, quiero implementar un endpoint para registrar solicitudes de mantenimiento preventivo, diferenciadas de las solicitudes por reparación.                                                                        | **Escenario 1: Solicitud exitosa de mantenimiento preventivo**<br/>Dado que el endpoint `/api/v1/preventive-maintenance` está disponible, cuando se envía una solicitud POST con datos válidos (equipo, fecha deseada), entonces el sistema responde con 201 y guarda la solicitud.<br/>**Escenario 2: Solicitud con datos incompletos**<br/>Dado que falta un campo obligatorio, entonces se responde con 400 y mensaje de error.                                                                                                                                                                                  | EP-03                         |
| TS-43               | Asignar técnico a solicitud de servicio por API                    | Como desarrollador, quiero crear un endpoint que permita asignar un técnico a una solicitud de servicio, para gestionar la ejecución técnica desde la plataforma.                                                                  | **Escenario 1: Asignación exitosa**<br/>Dado que el endpoint `/api/v1/requests/{id}/assign-technician` está disponible, cuando se envía una solicitud PUT con un técnico válido, entonces se devuelve 200 y se actualiza la solicitud.<br/>**Escenario 2: Técnico no existente**<br/>Dado un ID de técnico inválido, entonces se responde con 404 y mensaje "Technician not found".                                                                                                                                                                                                                                 | EP-03                         |
| TS-44               | Consultar historial de servicios por API                           | Como desarrollador, quiero exponer un endpoint para consultar el historial de servicios por cliente o equipo, permitiendo búsquedas y filtrado desde el panel de control.                                                          | **Escenario 1: Historial completo por cliente**<br/>Dado que el endpoint `/api/v1/service-history?client_id={id}` está disponible, cuando se hace la consulta, entonces se responde con 200 y la lista de servicios asociados.<br/>**Escenario 2: Historial filtrado por equipo**<br/>Dado que se agrega un parámetro de equipo, entonces el sistema devuelve solo los servicios asociados a ese equipo.                                                                                                                                                                                                            | EP-04                         |
| TS-45               | Generar y exportar reporte de desempeño técnico                    | Como desarrollador, quiero implementar la generación de reportes de desempeño técnico, incluyendo número de servicios, evaluaciones y tiempos promedio, y permitir su descarga en PDF.                                             | **Escenario 1: Generar reporte exitosamente**<br/>Dado que el endpoint `/api/v1/reports/performance` está disponible, cuando se hace una solicitud GET, entonces se devuelve un resumen con métricas.<br/>**Escenario 2: Descargar reporte PDF**<br/>Dado que el reporte ya fue generado, cuando se solicita la descarga, entonces el sistema entrega un archivo PDF con los datos generados.                                                                                                                                                                                                                       | EP-04                         |
| TS-46               | Consultar clientes con sus servicios asociados por API             | Como desarrollador, quiero implementar un endpoint que permita listar clientes junto con los servicios que tienen registrados, para facilitar la planificación desde el panel empresarial.                                         | **Escenario 1: Consulta de clientes con servicios**<br/>Dado que el endpoint `/api/v1/clients/services` está disponible, cuando se realiza una solicitud GET, entonces se devuelve la lista de clientes y sus servicios.<br/>**Escenario 2: Filtro por estado de servicio**<br/>Dado un parámetro de estado (ej. "in progress"), entonces el sistema devuelve solo los clientes con servicios en ese estado.                                                                                                                                                                                                        | EP-04                         |
| TS-47               | Consultar equipos entregados y su estado por API                   | Como desarrollador, quiero exponer un endpoint para visualizar los equipos entregados a clientes, junto con su estado y tipo, para mantener un registro accesible desde el sistema empresarial.                                    | **Escenario 1: Listado de equipos entregados**<br/>Dado que el endpoint `/api/v1/delivered-devices` está disponible, cuando se hace una solicitud GET, entonces se devuelve una lista con los equipos y sus estados.<br/>**Escenario 2: Filtro por tipo y estado**<br/>Dado que se agregan parámetros de tipo o estado, entonces se devuelve la lista filtrada según los criterios.                                                                                                                                                                                                                                 | EP-02                         |
| TS-48               | Sistema de envío de notificaciones por eventos relevantes          | Como desarrollador, quiero que el sistema pueda enviar notificaciones automáticas o manuales ante eventos clave (problemas detectados, cambios de estado), para mantener informados a clientes y técnicos.                         | **Escenario 1: Envío automático de notificación por cambio de estado**<br/>Dado que una solicitud cambia a "in progress", entonces el sistema envía una notificación al cliente.<br/>**Escenario 2: Envío manual por parte del técnico**<br/>Dado que un técnico detecta una situación crítica, cuando registra un evento, entonces se notifica al cliente automáticamente.                                                                                                                                                                                                                                         | EP-05                         |
| TS-49               | Consultar perfil del técnico con métricas por API                  | Como desarrollador, quiero crear un endpoint que muestre el perfil completo de un técnico incluyendo datos personales, historial y métricas de desempeño, para su visualización por el empresario.                                 | **Escenario 1: Visualización del perfil completo**<br/>Dado que el endpoint `/api/v1/technicians/{id}` está disponible, cuando se realiza una consulta GET, entonces se devuelve la información personal, servicios realizados y evaluación promedio.<br/>**Escenario 2: Técnico sin historial**<br/>Dado que el técnico aún no ha realizado servicios, el sistema informa que no hay datos de desempeño aún.                                                                                                                                                                                                       | EP-01                         |
| EP-01               | Gestión de Usuarios                                                | Esta epic se enfoca en la creación, autenticación y gestión de las cuentas de usuario en la plataforma. Incluye el registro de nuevos usuarios, inicio de sesión, y la administración de los perfiles.                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                               |
| EP-02               | Gestión de Equipos                                                 | Esta epic cubre las funcionalidades relacionadas con la gestión de los equipos de refrigeración. Permite a los clientes agregar, editar, y visualizar sus equipos registrados en la plataforma.                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                               |
| EP-03               | Solicitudes de Servicio                                            | Esta epic abarca todo lo relacionado con la solicitud de servicios de reparación y mantenimiento por parte de los clientes, así como el seguimiento de esas solicitudes hasta su resolución.                                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                               |
| EP-04               | Informes y Reportes                                                | Esta epic se refiere a la generación, visualización y envío de informes detallados sobre los servicios realizados, el consumo energético de los equipos y el desempeño de los técnicos.                                            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                               |
| EP-05               | Alertas y Notificaciones                                           | Esta epic se encarga de la creación de alertas automáticas y notificaciones para clientes y empresarios, relacionadas con fallas de equipos, mantenimiento preventivo y el progreso de los servicios.                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                               |
| EP-06               | Evaluación de Servicios                                            | Esta epic está orientada a permitir que los clientes puedan evaluar los servicios recibidos, para proporcionar retroalimentación y permitir que se realicen correcciones si es necesario.                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                               |
| EP-07               | Sitio Web y Experiencia Web (Landing Page)                         | Esta epic se enfoca en las funcionalidades de la página de aterrizaje, incluyendo la visualización de la propuesta de valor, la facilidad para solicitar demos, y el acceso a canales de contacto directo con el equipo de ventas. |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                               |



<div style="page-break-after: always"></div>

### 3.2. Impact Mapping.

El siguiente Impact Mapping fue desarrollado en UXPressia de manera colaborativa por el equipo de OsitoPolar para alinear los objetivos de negocio con los requerimientos funcionales de la plataforma.


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/Impact-Mapping.png"
       alt="Diagrama de Impact Mapping: Objetivo, actores, impactos y entregables clave."
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Impact Mapping.
  </figcaption>
</figure>

<div style="page-break-after: always"></div>

### 3.3. Product Backlog.

A continuación, presentaremos el Product Backlog, el cual contiene todas las funcionalidades y características necesarias para el desarrollo de la plataforma. Este listado incluye tanto las historias de usuario como las tareas técnicas que facilitarán el progreso del proyecto. Para priorizar las tareas, se ha utilizado la escala Fibonacci (1, 2, 3, 5, 8, 13, 21), la cual ayuda a estimar el esfuerzo relativo requerido para completar cada tarea. Además, hemos asignado cada item a un sprint, de acuerdo con su relevancia y dependencias.

Escala de Story Points (Fibonacci):

1: Tareas pequeñas que se pueden completar rápidamente.

2: Tareas de tamaño moderado.

3: Tareas que requieren más tiempo y esfuerzo.

5: Tareas complejas o con dependencia de otras tareas.

8: Tareas muy complejas o que afectan a múltiples áreas.


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/Product-Backlog.png"
       alt="Diagrama de Product Backlog: Lista priorizada de funcionalidades y requisitos del producto."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Product Backlog.
  </figcaption>
</figure>


| Orden | User Story ID | Titulo                                         | Descripcion                                                                                                                                                                | Story Points |
|-------|---------------|------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1     | US-01         | Registro de usuario                            | Como nuevo usuario, quiero registrarme para acceder a la plataforma y empezar a gestionar mis equipos de refrigeración.                                                    | 5            |
| 2     | US-02         | Inicio de sesión                               | Como usuario, quiero iniciar sesión con mi cuenta para acceder a la plataforma.                                                                                            | 3            |
| 3     | US-03         | Solicitar servicio de reparación               | Como cliente, quiero poder solicitar un servicio de reparación para mis equipos de refrigeración cuando detecto fallas.                                                    | 5            |
| 4     | US-04         | Ver estado del servicio solicitado             | Como cliente, quiero ver el estado actual de mi solicitud de servicio para estar informado sobre el avance del proceso.                                                    | 3            |
| 5     | US-05         | Ver reporte de servicio realizado              | Como cliente, quiero ver el reporte de servicio detallado para saber qué reparaciones se hicieron en mi equipo.                                                            | 3            |
| 6     | US-06         | Agregar equipos                                | Como cliente, quiero poder agregar mis equipos de refrigeración en la plataforma para llevar un control.                                                                   | 5            |
| 7     | US-07         | Recibir alerta de falla en equipo              | Como cliente, quiero recibir una alerta automática cuando mi equipo de refrigeración presente una falla para tomar acción rápidamente.                                     | 8            |
| 8     | US-08         | Solicitar mantenimiento preventivo             | Como cliente, quiero poder solicitar mantenimiento preventivo para evitar fallas futuras en mis equipos de refrigeración.                                                  | 5            |
| 9     | US-09         | Ver consumo energético de equipos              | Como cliente, quiero ver un informe del consumo energético de mis equipos para poder analizar su eficiencia.                                                               | 5            |
| 10    | US-09         | Recepción de alertas automáticas para servicio | Como empresario, quiero recibir alertas automáticas cuando un cliente solicite un servicio de reparación o mantenimiento.                                                  | 8            |
| 11    | US-10         | Asignar técnico a solicitud de servicio        | Como empresario, quiero poder asignar un técnico a una solicitud de servicio para garantizar que se realice el trabajo adecuado.                                           | 5            |
| 12    | US-11         | Ver historial de servicios realizados          | Como empresario, quiero ver el historial de servicios realizados para cada cliente y equipo, para llevar un control adecuado.                                              | 5            |
| 13    | US-12         | Realizar seguimiento a solicitudes de servicio | Como empresario, quiero realizar un seguimiento detallado a las solicitudes de servicio de mis técnicos, para saber cómo van.                                              | 8            |
| 14    | US-13         | Generar reporte de desempeño de técnicos       | Como empresario, quiero generar reportes sobre el desempeño de mis técnicos para evaluar su eficiencia y productividad.                                                    | 5            |
| 15    | US-14         | Configurar alertas de mantenimiento            | Como empresario, quiero poder configurar alertas automáticas para el mantenimiento preventivo de los equipos.                                                              | 8            |
| 16    | US-15         | Visualizar clientes y servicios asociados      | Como empresario, quiero ver todos los clientes que han solicitado servicio para organizar el trabajo de los técnicos.                                                      | 5            |
| 17    | US-16         | Visualizar equipos entregados a clientes       | Como empresario, quiero ver todos los equipos que fueron entregados a clientes para realizar su seguimiento.                                                               | 5            |
| 18    | US-17         | Recibir notificaciones de eventos importantes  | Como cliente, quiero recibir notificaciones sobre eventos importantes como el progreso del servicio, etc.                                                                  | 8            |
| 19    | US-18         | Realizar evaluación de servicio                | Como cliente, quiero poder evaluar el servicio para mostrar mi conformidad.                                                                                                | 3            |
| 20    | US-19         | Registrar técnicos                             | Como empresario, quiero poder registrar técnicos en la plataforma para integrarlos a mi red de soporte técnico.                                                            | 5            |
| 21    | US-21         | Visualizar perfil del técnico                  | Como empresario, quiero visualizar el perfil de cada técnico, incluyendo sus datos personales y métricas de desempeño, para evaluar su rendimiento.                        | 5            |
| 22    | US-22         | Visualizar propuesta de valor principal        | Como empresario, quiero recibir alertas cuando alguno de los equipos de mis clientes presenta fallas, para notificar al cliente y organizar la atención técnica.           | 8            |
| 23    | US-23         | Explorar soluciones específicas para mi rubro  | Como visitante, quiero ver claramente la propuesta de valor en la landing page, para saber si OsitoPolar puede ayudarme.                                                   | 3            |
| 24    | US-24         | Comprender funcionalidades destacadas          | Como visitante, quiero encontrar una sección con soluciones específicas para negocios como el mío, para saber si OsitoPolar se ajusta a mis necesidades.                   | 5            |
| 25    | US-25         | Solicitar una demo fácilmente                  | Como visitante, quiero ver funcionalidades clave presentadas de forma clara, para evaluar si la plataforma se adapta a mi operación.                                       | 5            |
| 26    | US-26         | Conocer misión y visión de la startup          | Como visitante, quiero poder solicitar una demo desde el landing page, para iniciar contacto con OsitoPolar.                                                               | 3            |
| 27    | US-27         | Conocer misión y visión de la startup          | Como visitante, quiero ver la misión y visión de OsitoPolar, para entender su enfoque y confianza en su propuesta.                                                         | 2            |
| 28    | US-28         | Contactar fácilmente con ventas                | Como visitante empresario, quiero un botón claro para contactar con ventas, para iniciar una posible relación comercial.                                                   | 3            |
| 29    | US-29         | Acceder fácilmente al inicio de sesión         | Como visitante, quiero encontrar un botón de “Iniciar sesión” visible en el Landing Page, para acceder rápidamente a mi cuenta sin perder tiempo.                          | 3            |
| 30    | US-30         | Descargar la app móvil desde la web            | Como visitante interesado en usar OsitoPolar desde el celular, quiero ver un enlace claro para descargar la app móvil desde el Landing Page, para instalarla fácilmente.   | 5            |
| 31    | US-31         | Registrar nuevo equipo                         | Como desarrollador, quiero permitir que los usuarios registren nuevos equipos de refrigeración mediante una API para facilitar el control y monitoreo desde la plataforma. | 5            |
| 32    | US-32         | Eliminar técnico asignado                      | Como desarrollador, quiero poder eliminar un técnico del sistema desde el API para gestionar la asignación de servicios y roles técnicos.                                  | 5            |
| 33    | US-33         | Notificación automática por alerta crítica     | Como desarrollador, quiero implementar un sistema de notificaciones automáticas que se activen cuando se detecten fallas críticas en los equipos.                          | 8            |
| 34    | US-34         | Crear solicitud de mantenimiento               | Como desarrollador, quiero implementar una API que permita crear solicitudes de mantenimiento para que los negocios reporten necesidades de soporte técnico.               | 5            | 
| 35    | US-35         | Crear registro de intervención técnica         | Como desarrollador, quiero permitir registrar intervenciones técnicas realizadas a través de la API, para llevar seguimiento del mantenimiento.                            | 5            |
| 36    | US-36         | Registrar evento de alerta manual              | Como desarrollador, quiero permitir registrar una alerta manual vía API para que los técnicos puedan ingresar incidentes detectados en campo.                              | 3            |
| 37    | US-37         | Evaluar servicio                               | Como desarrollador, quiero implementar un endpoint RESTful que permita a los clientes registrar y actualizar una evaluación de servicio, para reflejar su experiencia.     | 8            |

<div style="page-break-after: always"></div>

### 3.4. To-Be Scenario Mapping.
**Segmento objetivo #1: CLIENTES (DUEÑOS DE EQUIPOS DE REFRIGERACIÓN)**

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/To-Be-Scenario-segment-1.png"
       alt="To Be Scenario Mapping Segmento 1: Interacción ideal de Clientes (Dueños de equipos de refrigeración)."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> To Be Scenario Mapping Clientes (Segmento 1).
  </figcaption>
</figure>


**Segmento objetivo #2: EMPRESAS PROVEEDORAS DE SERVICIOS Y EQUIPOS DE REFRIGERACIÓN**


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/To-Be-Scenario-segment-2.png"
       alt="To Be Scenario Mapping Segmento 2: Interacción ideal de Empresas Proveedoras de Servicios y Equipos de Refrigeración."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> To Be Scenario Mapping - Empresas Proveedoras (Segmento 2).
  </figcaption>
</figure>

<div style="page-break-after: always"></div>


## Capítulo IV: Solution Software Design
### 4.1. Strategic-Level Domain-Driven Design.

#### 4.1.1. Design-Level EventStorming.

##### 4.1.1.1 Candidate Context Discovery.
La sesión de Candidate Context Discovery se realizó inmediatamente después del taller de EventStorming, con una duración aproximada de 1 hora 30 minutos. Se utilizó como insumo la línea de tiempo de eventos generada, los clusters de eventos y agregados identificados, y los eventos pivote que marcaban transiciones de estado relevantes en la plataforma OsitoPolar.

Se aplicó la técnica **Start-with-Value**, cuyo principio consiste en priorizar aquellas partes del dominio que representan el mayor valor para el negocio. Esta técnica permitió separar con claridad qué bounded contexts debían considerarse Core, y cuáles como Supporting o Generic.

El proceso se organizó en tres pasos:

**1. Identificación de valor estratégico**

Cada integrante respondió a la pregunta: *¿Qué parte del sistema genera directamente valor para los usuarios y diferencia a OsitoPolar de otras soluciones de gestión de equipos de refrigeración?*

**2. Agrupación de eventos en torno al valor**

Se revisaron los clusters del EventStorming, destacando aquellos que respondían a las necesidades críticas de monitoreo, gestión técnica y trazabilidad de equipos. Los eventos fueron agrupados en bloques temáticos antes de la delimitación formal de los bounded contexts.

**3. Clasificación Core, Supporting, Generic**

Los contexts se categorizaron según su aporte al negocio y nivel de complejidad de su modelo.

**Candidate Contexts identificados:**

| Candidate Context | Eventos Clave Asociados | Clasificación | Descripción | Justificación |
|---|---|---|---|---|
| **IAM** | Usuario registrado, Sesión iniciada, Token generado | Generic | Gestión de usuarios, roles y autenticación mediante JWT. | Necesario para operar pero no diferenciador; existen soluciones estándar que podrían cubrirlo. |
| **Profiles** | Perfil creado, Perfil actualizado | Generic | Datos personales del usuario fuera del contexto de autenticación. | Complementa al IAM pero no representa valor diferenciador del negocio. |
| **Subscriptions and Payments** | Plan elegido, Suscripción confirmada, Pago procesado, Suscripción cancelada | Supporting | Gestión de planes de suscripción y pagos vía Stripe. | Clave para la sostenibilidad económica del negocio, pero externalizable a través de proveedores estándar. |
| **Technicians** | Técnico registrado, Técnico asignado, Calificación registrada | Supporting | Administración del catálogo de técnicos de servicio y sus métricas de rendimiento. | Apoya el flujo de atención técnica pero no constituye el núcleo diferenciador de la solución. |
| **Equipment Management** | Equipo registrado, Ubicación actualizada, Estado de equipo cambiado, Equipo eliminado | Core | Gestión del ciclo de vida completo de equipos de refrigeración y climatización. | Es el núcleo operativo de OsitoPolar; sin la gestión de equipos no existe base para el monitoreo ni para los servicios. |
| **Service Requests** | Solicitud creada, Técnico asignado, Solicitud resuelta, Feedback agregado | Core | Gestión del flujo de solicitudes de servicio técnico desde su creación hasta la resolución y retroalimentación. | Constituye el mecanismo principal de interacción entre clientes y técnicos; diferencia a OsitoPolar frente a métodos informales. |
| **Work Orders** | Orden de trabajo creada, Orden asignada, Orden en progreso, Orden resuelta, Feedback del cliente registrado | Core | Gestión de las órdenes de trabajo técnico concretas que ejecutan los técnicos sobre los equipos. | Provee trazabilidad completa del trabajo realizado sobre cada equipo, valor diferenciador frente a la gestión manual. |
| **Analytics** | Lectura de temperatura registrada, Lectura de energía registrada, Alerta de rango generada, Promedio diario calculado | Core | Recopilación, procesamiento y visualización de lecturas de temperatura y consumo energético de los equipos. | Es el núcleo técnico de OsitoPolar; la detección de anomalías térmicas y el análisis energético constituyen la propuesta de valor principal para el cliente. |

**Clasificación estratégica final:**

- **Core:** Equipment Management, Service Requests, Work Orders, Analytics.
- **Supporting:** Subscriptions and Payments, Technicians.
- **Generic:** IAM, Profiles.

Se definieron ocho bounded contexts candidatos, de los cuales 4 son Core, 2 Supporting y 2 Generic. La técnica Start-with-Value permitió asegurar que la atención principal del diseño táctico se concentre en los contextos de Equipment Management, Service Requests, Work Orders y Analytics, dado que allí reside la propuesta de valor diferenciadora de OsitoPolar: la gestión integral de equipos de refrigeración, la trazabilidad del servicio técnico y el análisis del desempeño operativo de los equipos.

---

##### 4.1.1.2 Domain Message Flows Modeling.
Para esta sección el objetivo fue visualizar cómo los bounded contexts colaboran (mediante mensajes, eventos y solicitudes sincrónicas) para soportar los casos de uso clave de la plataforma OsitoPolar. Se aplicó Domain Storytelling para describir las interacciones tanto operativas como técnicas en la gestión de equipos de refrigeración.

**Historia A — Cliente registra un equipo y recibe alertas de temperatura**

1. El **Cliente** (negocio de refrigeración) realiza el `SignUp` en el contexto **IAM**, que genera un JWT y emite el evento `UserRegistered`.
2. **IAM** notifica al contexto **Profiles**, que crea el perfil del usuario mediante `CreateProfileCommand`.
3. El cliente crea un equipo en **Equipment Management** con `CreateEquipmentCommand`, registrando modelo, marca, ubicación y tipo.
4. **Equipment Management** persiste el equipo y emite `EquipmentRegistered`.
5. El sistema IoT o el técnico registra lecturas de temperatura mediante `RecordTemperatureReadingCommand` en el contexto **Analytics**.
6. **Analytics** evalúa si la lectura supera el `TemperatureRange` configurado y genera el estado `Critical` o `Warning`.
7. La plataforma muestra en el dashboard del cliente las lecturas y alertas en tiempo real.

![Historia_A](assets/chapter04/histori_A.png)

**Historia B — Cliente solicita servicio técnico para un equipo**

1. El cliente detecta una anomalía en su equipo y crea una `ServiceRequest` en **Service Requests** con `CreateServiceRequestCommand`, indicando equipo, descripción, prioridad y urgencia.
2. **Service Requests** registra la solicitud en estado `Pending`.
3. La empresa de servicios consulta las solicitudes pendientes y asigna un técnico disponible del contexto **Technicians** mediante `AssignTechnicianToServiceRequestCommand`.
4. **Service Requests** cambia el estado a `Accepted` y notifica al técnico asignado.
5. Se crea una `WorkOrder` en **Work Orders** con `CreateWorkOrderCommand`, vinculada a la `ServiceRequest` y al equipo correspondiente.
6. El técnico ejecuta el trabajo, actualiza el estado de la orden a `InProgress` y luego a `Resolved` mediante `AddWorkOrderResolutionDetailsCommand`.
7. **Work Orders** emite `WorkOrderResolved`, y el cliente puede agregar `CustomerFeedbackRating` (1-5 estrellas).
8. **Technicians** actualiza el `AverageRating` del técnico con la nueva calificación recibida.

![Historia_A](assets/chapter04/Historia_B.png)

**Historia C — Empresa gestiona suscripción y accede a analítica avanzada**

1. El cliente selecciona un plan en **Subscriptions and Payments** con `CreateSubscriptionCommand`.
2. **Subscriptions and Payments** genera una sesión de Stripe Checkout y redirige al cliente para el pago.
3. Stripe procesa el pago y envía el webhook, que es manejado con `ProcessPaymentWebhookCommand`.
4. La suscripción queda confirmada en estado `Active` y se actualiza el `SubscriptionId` del usuario en **IAM**.
5. Con el plan activo, el cliente accede a las vistas de **Analytics** para consultar lecturas históricas de temperatura y energía, promedios diarios y el estado general del equipo mediante `GetEquipmentAnalyticsQuery`.

---
![Historia_C](assets/chapter04/Historia_C.png)

##### 4.1.1.3 Bounded Context Canvases.
A continuación se presentan los Bounded Context Canvases de los ocho contextos identificados para la plataforma OsitoPolar:

---

**IAM (Identity and Access Management)**

Gestiona el registro de usuarios y la autenticación mediante JWT, controlando el acceso basado en roles en toda la plataforma.

| Elemento | Detalle |
|---|---|
| **Clasificación** | Generic |
| **Responsabilidad** | Registro (`SignUp`), autenticación (`SignIn`) y autorización de usuarios. |
| **Aggregate Root** | `User` (Id, Username, PasswordHash, SubscriptionId) |
| **Comandos clave** | `SignUpCommand`, `SignInCommand` |
| **Queries clave** | `GetUserByIdQuery`, `GetUserByUsernameQuery` |
| **Eventos publicados** | `UserRegistered` |
| **Colaboraciones entrantes** | Ninguna (primer punto de entrada al sistema) |
| **Colaboraciones salientes** | → Profiles (crea perfil al registrar usuario vía `IamContextFacade`) |
| **Sistemas externos** | BCrypt (hashing), JWT (tokens) |

---

**Profiles**

Almacena los datos personales de los usuarios (nombre, email, dirección) fuera del contexto de autenticación, accesibles por otros bounded contexts mediante fachada ACL.

| Elemento | Detalle |
|---|---|
| **Clasificación** | Generic |
| **Responsabilidad** | Persistencia y consulta de datos de perfil de usuario. |
| **Aggregate Root** | `Profile` (Id, PersonName, EmailAddress, StreetAddress) |
| **Comandos clave** | `CreateProfileCommand` |
| **Queries clave** | `GetProfileByIdQuery`, `GetProfileByEmailQuery` |
| **Eventos publicados** | Ninguno |
| **Colaboraciones entrantes** | ← IAM (crea perfil al registrar usuario) |
| **Colaboraciones salientes** | Expone `IProfilesContextFacade` a otros contextos |
| **Sistemas externos** | Ninguno |

---

**Equipment Management**

Gestiona el ciclo de vida completo de los equipos de refrigeración y climatización: registro, ubicación, estado operativo y consumo energético.

| Elemento | Detalle |
|---|---|
| **Clasificación** | Core |
| **Responsabilidad** | CRUD de equipos y gestión de su estado, ubicación y tipo. |
| **Aggregate Root** | `Equipment` (Id, EquipmentIdentifier, OwnerId, Status, Type, Location, EnergyConsumption) |
| **Comandos clave** | `CreateEquipmentCommand`, `UpdateEquipmentLocationCommand`, `UpdateEquipmentPowerStateCommand`, `UpdateEquipmentTemperatureCommand`, `DeleteEquipmentCommand` |
| **Queries clave** | `GetEquipmentByIdQuery`, `GetEquipmentsByOwnerIdQuery`, `GetEquipmentsByStatusQuery` |
| **Eventos publicados** | `EquipmentRegistered`, `EquipmentStatusChanged` |
| **Colaboraciones entrantes** | ← IAM (autenticación de propietario) |
| **Colaboraciones salientes** | → Analytics (equipos referenciados en lecturas), → Service Requests (equipo vinculado a solicitud), → Work Orders (equipo vinculado a orden) |
| **Sistemas externos** | Ninguno |

---

**Service Requests**

Gestiona el flujo completo de solicitudes de servicio técnico: desde su creación por el cliente hasta la asignación del técnico, la resolución y la retroalimentación.

| Elemento | Detalle |
|---|---|
| **Clasificación** | Core |
| **Responsabilidad** | Ciclo de vida de solicitudes de servicio técnico con reglas de estado estrictas. |
| **Aggregate Root** | `ServiceRequest` (Id, OrderNumber, Status, Priority, Urgency, ClientId, CompanyId, EquipmentId, AssignedTechnicianId) |
| **Comandos clave** | `CreateServiceRequestCommand`, `AssignTechnicianToServiceRequestCommand`, `UpdateServiceRequestStatusCommand`, `AddCustomerFeedbackToServiceRequestCommand`, `CancelServiceRequestCommand`, `RejectServiceRequestCommand` |
| **Queries clave** | `GetServiceRequestByIdQuery`, `GetServiceRequestsByStatusQuery`, `GetServiceRequestsByEquipmentIdQuery` |
| **Eventos publicados** | `ServiceRequestCreated`, `TechnicianAssigned`, `ServiceRequestResolved` |
| **Colaboraciones entrantes** | ← Equipment Management (referencia al equipo), ← Technicians (técnico asignado) |
| **Colaboraciones salientes** | → Work Orders (se genera una Work Order al aceptar la solicitud) |
| **Sistemas externos** | Ninguno |

---

**Work Orders**

Gestiona las órdenes de trabajo técnico que los técnicos ejecutan sobre los equipos, incluyendo programación, resolución y retroalimentación del cliente.

| Elemento | Detalle |
|---|---|
| **Clasificación** | Core |
| **Responsabilidad** | Trazabilidad completa del trabajo técnico realizado: asignación, ejecución, resolución y calificación. |
| **Aggregate Root** | `WorkOrder` (Id, WorkOrderNumber, ServiceRequestId, Status, AssignedTechnicianId, EquipmentId, Cost, CustomerFeedbackRating) |
| **Comandos clave** | `CreateWorkOrderCommand`, `AssignTechnicianToWorkOrderCommand`, `UpdateWorkOrderStatusCommand`, `AddWorkOrderResolutionDetailsCommand`, `AddWorkOrderCustomerFeedbackCommand` |
| **Queries clave** | `GetWorkOrderByIdQuery`, `GetWorkOrdersByTechnicianIdQuery`, `GetWorkOrdersByEquipmentIdQuery` |
| **Eventos publicados** | `WorkOrderCreated`, `WorkOrderResolved` |
| **Colaboraciones entrantes** | ← Service Requests (vinculada a una solicitud), ← Technicians (técnico asignado), ← Equipment Management (equipo referenciado) |
| **Colaboraciones salientes** | → Technicians (actualización del rating del técnico) |
| **Sistemas externos** | Ninguno |

---

**Analytics**

Recopila, procesa y consulta lecturas de temperatura y consumo energético de los equipos de refrigeración, detectando anomalías y calculando promedios históricos.

| Elemento | Detalle |
|---|---|
| **Clasificación** | Core |
| **Responsabilidad** | Ingesta de lecturas IoT, detección de estados anómalos y consultas analíticas históricas. |
| **Aggregate Root** | `EquipmentAnalytics` (EquipmentId, TemperatureReadings, EnergyReadings) |
| **Comandos clave** | `RecordTemperatureReadingCommand`, `RecordEnergyReadingCommand` |
| **Queries clave** | `GetTemperatureReadingsQuery`, `GetEnergyReadingsQuery`, `GetDailyTemperatureAveragesQuery`, `GetEquipmentAnalyticsQuery` |
| **Eventos publicados** | `AnomalousReadingDetected` |
| **Colaboraciones entrantes** | ← Equipment Management (referencia de equipos monitoreados) |
| **Colaboraciones salientes** | Ninguna (solo expone queries) |
| **Sistemas externos** | Dispositivos IoT / sensores de temperatura y energía |

---

**Subscriptions and Payments**

Gestiona la selección de planes de suscripción y el procesamiento de pagos vía Stripe, controlando el ciclo de vida desde la elección del plan hasta la confirmación de la suscripción activa.

| Elemento | Detalle |
|---|---|
| **Clasificación** | Supporting |
| **Responsabilidad** | Alta, renovación y cancelación de suscripciones; integración de pagos con Stripe. |
| **Aggregates** | `Subscription` (Id, UserId, PlanName, BillingCycle, Status), `Payment` (Id, UserId, SubscriptionId, StripeSession, Amount, Status) |
| **Comandos clave** | `CreateSubscriptionCommand`, `UpgradePlanCommand`, `DeleteSubscriptionCommand`, `CreatePaymentSessionCommand`, `ProcessPaymentWebhookCommand` |
| **Queries clave** | `GetSubscriptionByIdQuery`, `GetPlansQuery` |
| **Eventos publicados** | `SubscriptionConfirmed`, `SubscriptionCancelled` |
| **Colaboraciones entrantes** | ← IAM (UserId del usuario suscriptor) |
| **Colaboraciones salientes** | → IAM (actualiza `SubscriptionId` en el usuario) |
| **Sistemas externos** | Stripe (pagos y webhooks) |

---

**Technicians**

Gestiona el catálogo de técnicos de servicio disponibles en la plataforma, incluyendo sus datos, especialización, disponibilidad y métricas de rendimiento (calificación promedio).

| Elemento | Detalle |
|---|---|
| **Clasificación** | Supporting |
| **Responsabilidad** | Registro, consulta y gestión del rendimiento de técnicos de servicio. |
| **Entidad Principal** | `Technician` (Id, FirstName, LastName, Email, Phone, Specialization, IsAvailable, AverageRating) |
| **Comandos clave** | `CreateTechnicianCommand` |
| **Queries clave** | `GetAllTechniciansQuery`, `GetTechnicianByIdQuery`, `GetTechnicianAverageRatingQuery` |
| **Eventos publicados** | `TechnicianCreatedEvent` |
| **Colaboraciones entrantes** | ← Work Orders (retroalimentación del cliente que actualiza el rating) |
| **Colaboraciones salientes** | → Service Requests (técnico asignado a solicitud), → Work Orders (técnico asignado a orden) |
| **Sistemas externos** | Ninguno |

---

#### 4.1.2. Context Mapping.


El mapa de contextos (Context Map) define las relaciones estratégicas y de integración entre los ocho Bounded Contexts identificados para la plataforma OsitoPolar. Estas relaciones establecen cómo fluyen los datos y qué contexto tiene el control sobre los contratos de integración.

Las relaciones identificadas son las siguientes:

- **IAM → Profiles** [Partnership / ACL]: Al registrar un usuario, IAM invoca la fachada `IProfilesContextFacade` de Profiles para crear el perfil correspondiente. IAM actúa como Upstream (U) y Profiles como Downstream (D). Profiles implementa un ACL para traducir el modelo de IAM al suyo propio.

- **IAM ← Subscriptions and Payments** [Customer/Supplier]: Subscriptions and Payments actualiza el `SubscriptionId` del usuario en IAM al confirmar una suscripción activa. Subscriptions and Payments es Upstream (U), IAM es Downstream (D).

- **Equipment Management → Analytics** [Customer/Supplier]: Analytics consume el `EquipmentId` de Equipment Management como clave de referencia para asociar lecturas a equipos. Equipment Management es Upstream (U), Analytics es Downstream (D).

- **Equipment Management → Service Requests** [Customer/Supplier]: Service Requests referencia el `EquipmentId` de Equipment Management al crear solicitudes de servicio. Equipment Management es Upstream (U), Service Requests es Downstream (D).

- **Equipment Management → Work Orders** [Customer/Supplier]: Work Orders referencia el `EquipmentId` de Equipment Management. Equipment Management es Upstream (U), Work Orders es Downstream (D).

- **Technicians → Service Requests** [Customer/Supplier]: Service Requests consume el `TechnicianId` de Technicians al asignar un técnico a una solicitud. Technicians es Upstream (U), Service Requests es Downstream (D).

- **Technicians → Work Orders** [Customer/Supplier]: Work Orders consume el `TechnicianId` de Technicians al asignar un técnico a una orden. Technicians es Upstream (U), Work Orders es Downstream (D).

- **Service Requests → Work Orders** [Partnership]: Al aceptar una solicitud de servicio, se genera automáticamente una Work Order vinculada. Service Requests es Upstream (U), Work Orders es Downstream (D).

- **Work Orders → Technicians** [Customer/Supplier]: Work Orders notifica al contexto Technicians cuando se registra la calificación de un cliente, para actualizar el `AverageRating` del técnico. Work Orders es Upstream (U), Technicians es Downstream (D).

A continuación se presenta el diagrama del Context Mapping utilizando notación estándar de Domain-Driven Design (DDD):

![Context Mapping](assets/chapter04/context_diagram.png)


#### 4.1.3. Software Architecture.

##### 4.1.3.1. Software Architecture System Landscape Diagram.

![System Landscape Diagram](assets/chapter04/DSL/SystemLandscape-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/SystemLandscape-dark-key.png)

##### 4.1.3.2. Software Architecture Context Level Diagrams.

![System Context Diagram](assets/chapter04/DSL/Contexto-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Contexto-dark-key.png)

##### 4.1.3.2. Software Architecture Container Level Diagrams.

![Container Diagram](assets/chapter04/DSL/Contenedores-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Contenedores-dark-key.png)

##### 4.1.3.3. Software Architecture Deployment Diagrams.

![Deployment Diagram](assets/chapter04/DSL/DeploymentDiagram-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/DeploymentDiagram-dark-key.png)

### 4.2. Tactical-Level Domain-Driven Design

#### 4.2.1. Bounded Context: IAM (Identity and Access Management)

##### 4.2.1.1. Domain Layer

El Domain Layer del bounded context **IAM** encapsula toda la lógica de autenticación y autorización de usuarios en la plataforma. Su responsabilidad principal es gestionar el ciclo de vida de los usuarios, incluyendo el registro (`SignUp`) y el inicio de sesión (`SignIn`), asegurando que las credenciales sean manejadas de forma segura mediante hashing de contraseñas.

**Aggregate Root:**

- `User` — Entidad raíz que representa a un usuario del sistema. Contiene `Id`, `Username`, `PasswordHash` y `SubscriptionId`(referencia al plan de suscripción). Expone métodos como `UpdateUsername`, `UpdatePasswordHash` y `UpdateSubscription`.

**Commands:**

- `SignUpCommand(Username, Password, Role)` — Registra un nuevo usuario.
- `SignInCommand(Username, Password)` — Autentica un usuario existente.

**Queries:**

- `GetAllUsersQuery` — Retorna todos los usuarios registrados.
- `GetUserByIdQuery(int Id)` — Retorna un usuario por su identificador.
- `GetUserByUsernameQuery(string Username)` — Retorna un usuario por su nombre de usuario.

**Repositories:**

- `IUserRepository` — Contrato de persistencia con operaciones de búsqueda por username.

**Domain Services:**

- `IUserCommandService` — Interfaz para manejar comandos de usuario (SignUp, SignIn).
- `IUserQueryService` — Interfaz para manejar consultas de usuario.

**Outbound Services (Application):**

- `IHashingService` — Abstracción para hashing de contraseñas (implementado con BCrypt).
- `ITokenService` — Abstracción para generación y validación de JWT tokens.

---

##### 4.2.1.2. Interface Layer

La capa de interfaz expone los endpoints REST de autenticación y gestión de usuarios, además de publicar una fachada ACL para que otros bounded contexts puedan consultar información de usuarios sin acoplarse directamente.

**Controllers REST:**

- `AuthenticationController` (`/api/v1/authentication`)
    - `POST /sign-up` — Registra un nuevo usuario.
    - `POST /sign-in` — Inicia sesión y retorna un JWT token.
- `UsersController` (`/api/v1/users`)
    - `GET /` — Lista todos los usuarios.
    - `GET /{id}` — Retorna un usuario por ID.

**Resources:**

- `SignUpResource(Username, Password, Role)`
- `SignInResource(Username, Password)`
- `AuthenticatedUserResource(Id, Username, Token)`
- `UserResource(Id, Username)`

**Assemblers (Transform):**

- `SignUpCommandFromResourceAssembler`
- `SignInCommandFromResourceAssembler`
- `AuthenticatedUserResourceFromEntityAssembler`
- `UserResourceFromEntityAssembler`

**ACL (Anti-Corruption Layer):**

- `IIamContextFacade` — Interfaz publicada para otros contextos.
- `IamContextFacade` — Implementación que permite crear usuarios y consultar IDs por username desde otros bounded contexts.

---

##### 4.2.1.3. Application Layer

La capa de aplicación orquesta los casos de uso del bounded context IAM, coordinando el repositorio de usuarios con los servicios de hashing y token para ejecutar los flujos de autenticación.

**Command Services:**

- `UserCommandService` — Implementa `IUserCommandService`.
    - `Handle(SignUpCommand)`: Verifica que el username no exista, hashea la contraseña con `IHashingService` y persiste el nuevo usuario.
    - `Handle(SignInCommand)`: Verifica credenciales con BCrypt, genera y retorna un JWT mediante `ITokenService`.

**Query Services:**

- `UserQueryService` — Implementa `IUserQueryService`.
    - `Handle(GetAllUsersQuery)`: Retorna todos los usuarios.
    - `Handle(GetUserByIdQuery)`: Retorna usuario por ID.
    - `Handle(GetUserByUsernameQuery)`: Retorna usuario por username.

**Outbound Services:**

- `IHashingService` / `ITokenService` — Interfaces de servicios externos definidas en Application para ser implementadas en Infrastructure.

---

##### 4.2.1.4. Infrastructure Layer

La capa de infraestructura provee las implementaciones concretas de los contratos definidos en el dominio y la aplicación: persistencia con Entity Framework Core, hashing con BCrypt, tokens JWT y middleware de autorización.

**Persistence (EFC):**

- `UserRepository` — Implementa `IUserRepository` usando `AppDbContext`. Permite búsqueda por username.
- `ModelBuilderExtensions.ApplyIamConfiguration()` — Configura la tabla `users` con columnas `id`, `username`, `password_hash`, `subscription_id`, `created_at`, `updated_at`.

**Hashing:**

- `HashingService` — Implementa `IHashingService` usando la librería BCrypt.Net para hashear y verificar contraseñas.

**Tokens JWT:**

- `TokenService` — Implementa `ITokenService`. Genera tokens JWT firmados con clave secreta, incluyendo claims de `id` y `username`.
- `TokenSettings` — Configuración del secreto JWT leído desde `appsettings.json`.

**Middleware Pipeline:**

- `RequestAuthorizationMiddleware` — Middleware que valida el JWT en cada request y adjunta el usuario autenticado al contexto HTTP.
- `AuthorizeAttribute` / `AllowAnonymousAttribute` — Atributos para marcar endpoints que requieren o no autenticación.
- `RequestAuthorizationMiddlewareExtensions` — Método de extensión para registrar el middleware en el pipeline de ASP.NET Core.

---

##### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

![IAM Component Diagram](assets/chapter04/DSL/IAM_Components-dark.png)

**Leyenda:**

![IAM Component Diagram Key](assets/chapter04/DSL/IAM_Components-dark-key.png)

---

##### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class User {
        -Long id
        -String username
        -String email
        -String passwordHash
        -Role role
        -Boolean isActive
        -DateTime createdAt
        +register(String username, String email, String password) User
        +login(String email, String password) String
        +changePassword(String oldPassword, String newPassword) void
        +deactivate() void
    }

    class Role {
        <<enumeration>>
        ADMIN
        TECHNICIAN
        CLIENT
    }

    class RefreshToken {
        -Long id
        -Long userId
        -String token
        -DateTime expiresAt
        -Boolean revoked
        +revoke() void
        +isExpired() Boolean
    }

    class AuthService {
        <<service>>
        +signUp(SignUpCommand command) User
        +signIn(SignInCommand command) TokenPair
        +refreshToken(String token) TokenPair
        +revokeToken(String token) void
    }

    class TokenPair {
        <<valueObject>>
        -String accessToken
        -String refreshToken
        -DateTime expiresAt
    }

    class IUserRepository {
        <<interface>>
        +findById(Long id) User
        +findByEmail(String email) User
        +save(User user) User
        +existsByEmail(String email) Boolean
    }

    class UserRepository {
        <<repository>>
    }

    User --> Role
    User "1" --> "0..*" RefreshToken
    AuthService --> IUserRepository
    AuthService --> TokenPair
    IUserRepository <|.. UserRepository
```

###### 4.2.1.6.2. Bounded Context Database Design Diagram

![IAM Database Design](assets/chapter04/DSL/Contenedores-dark.png)

---

#### 4.2.2. Bounded Context: Profiles

##### 4.2.2.1. Domain Layer

El Domain Layer del bounded context **Profiles** gestiona la información personal de los usuarios registrados en la plataforma (clientes y técnicos). Se encarga de representar los datos de perfil de manera estructurada mediante Value Objects, garantizando la validación de cada dato de dominio.

**Aggregate Root:**

- `Profile` — Entidad raíz que representa el perfil de un usuario. Contiene `Id`, `Name` (PersonName), `Email` (EmailAddress) y `Address` (StreetAddress). Expone propiedades computadas como `FullName`, `EmailAddress` y `StreetAddress`.

**Value Objects:**

- `PersonName(FirstName, LastName)` — Encapsula el nombre completo. Expone `FullName`.
- `EmailAddress(Address)` — Encapsula y valida el correo electrónico.
- `StreetAddress(Street, Number, City, PostalCode, Country)` — Encapsula la dirección física. Expone `FullAddress`.

**Commands:**

- `CreateProfileCommand(FirstName, LastName, Email, Street, Number, City, PostalCode, Country)` — Crea un nuevo perfil de usuario.

**Queries:**

- `GetAllProfilesQuery` — Retorna todos los perfiles.
- `GetProfileByIdQuery(int Id)` — Retorna un perfil por su ID.
- `GetProfileByEmailQuery(string Email)` — Retorna un perfil por su email.

**Repositories:**

- `IProfileRepository` — Contrato de persistencia con búsqueda por email.

**Domain Services:**

- `IProfileCommandService` — Interfaz para ejecutar comandos de perfil.
- `IProfileQueryService` — Interfaz para ejecutar consultas de perfil.

---

##### 4.2.2.2. Interface Layer

La capa de interfaz expone los endpoints REST para crear y consultar perfiles. Además, publica una fachada ACL que permite que el bounded context IAM cree perfiles automáticamente al registrar un usuario.

**Controllers REST:**

- `ProfilesController` (`/api/v1/profiles`)
    - `POST /` — Crea un nuevo perfil.
    - `GET /` — Lista todos los perfiles.
    - `GET /{profileId}` — Retorna un perfil por ID.

**Resources:**

- `CreateProfileResource(FirstName, LastName, Email, Street, Number, City, PostalCode, Country)`
- `ProfileResource(Id, FullName, Email, StreetAddress)`

**Assemblers (Transform):**

- `CreateProfileCommandFromResourceAssembler`
- `ProfileResourceFromEntityAssembler`

**ACL (Anti-Corruption Layer):**

- `IProfilesContextFacade` — Interfaz publicada para otros contextos.
- `ProfilesContextFacade` — Implementación que permite crear perfiles y obtener IDs por email desde otros bounded contexts (principalmente IAM).

---

##### 4.2.2.3. Application Layer

La capa de aplicación orquesta los casos de uso del bounded context Profiles, coordinando la creación y consulta de perfiles mediante el repositorio y la unidad de trabajo.

**Command Services:**

- `ProfileCommandService` — Implementa `IProfileCommandService`.
    - `Handle(CreateProfileCommand)`: Verifica que no exista un perfil con el mismo email, crea el perfil y lo persiste.

**Query Services:**

- `ProfileQueryService` — Implementa `IProfileQueryService`.
    - `Handle(GetAllProfilesQuery)`: Retorna todos los perfiles.
    - `Handle(GetProfileByIdQuery)`: Retorna perfil por ID.
    - `Handle(GetProfileByEmailQuery)`: Retorna perfil por email.

**ACL (Application):**

- `ProfilesContextFacade` — Implementación de la fachada que expone operaciones simplificadas para otros BCs.

---

##### 4.2.2.4. Infrastructure Layer

La capa de infraestructura provee la implementación concreta de persistencia mediante Entity Framework Core.

**Persistence (EFC):**

- `ProfileRepository` — Implementa `IProfileRepository` usando `AppDbContext`. Permite búsqueda por email.
- `ModelBuilderExtensions.ApplyProfilesConfiguration()` — Configura la tabla `profiles` con value objects mapeados como owned entities: `PersonName` → columnas `first_name`, `last_name`; `EmailAddress` → columna `email_address`; `StreetAddress` → columnas `street`, `number`, `city`, `postal_code`, `country`.

---

##### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

![Profiles Component Diagram](assets/chapter04/DSL/Profiles_Components-dark.png)

**Leyenda:**

![Profiles Component Diagram Key](assets/chapter04/DSL/Profiles_Components-dark-key.png)

---

##### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

  ```mermaid
  classDiagram
      class OwnerProfile {
          -Long id
          -Long userId
          -String businessName
          -String ruc
          -String phone
          -String address
          -Sector sector
          +updateInfo(businessName, phone, address) void
          +changeSector(sector Sector) void
      }

      class ProviderProfile {
          -Long id
          -Long userId
          -String companyName
          -String ruc
          -String phone
          -String specialization
          -Decimal rating
          +updateInfo(companyName, phone) void
          +updateRating(newRating Decimal) void
      }

      class Sector {
          <<enumeration>>
          FOOD
          PHARMA
          HOSPITALITY
          OTHER
      }

      class IOwnerProfileRepository {
          <<interface>>
          +findById(id Long) OwnerProfile
          +findByUserId(userId Long) OwnerProfile
          +save(profile OwnerProfile) OwnerProfile
      }

      class IProviderProfileRepository {
          <<interface>>
          +findById(id Long) ProviderProfile
          +findByUserId(userId Long) ProviderProfile
          +save(profile ProviderProfile) ProviderProfile
      }

      class ProfileService {
          <<service>>
          +createOwnerProfile(command CreateOwnerCommand) OwnerProfile
          +createProviderProfile(command CreateProviderCommand) ProviderProfile
          +getOwnerProfile(userId Long) OwnerProfile
          +getProviderProfile(userId Long) ProviderProfile
      }

      class OwnerProfileRepository{
          <<repository>>
      }

      class ProviderProfileRepository {
          <<repository>>
      }

      OwnerProfile --> Sector
      ProfileService --> IOwnerProfileRepository
      ProfileService --> IProviderProfileRepository
      IOwnerProfileRepository <|.. OwnerProfileRepository
      IProviderProfileRepository <|.. ProviderProfileRepository
  ```

###### 4.2.2.6.2. Bounded Context Database Design Diagram

![Profiles Database Design](assets/chapter04/DSL/Contenedores-dark.png)

---

#### 4.2.3. Bounded Context: Equipment Management

##### 4.2.3.1. Domain Layer

El Domain Layer del bounded context **Equipment Management** gestiona el ciclo de vida completo de los equipos de refrigeración y climatización que la plataforma monitorea. Permite crear, actualizar y consultar equipos, así como gestionar su estado operativo, ubicación y consumo energético.

**Aggregate Root:**

- `Equipment` — Entidad raíz que representa un equipo físico. Contiene `Id`, `EquipmentIdentifier` (VO), `OwnerId`, `OwnershipType`, `Status`, `Type`, `Location`, `RentalInfo` y `EnergyConsumption`. Expone métodos como `UpdateLocation`, `UpdatePowerState` y `UpdateTemperature`.

**Entities:**

- `Location(Coordinates, Address)` — Representa la ubicación física del equipo.
- `RentalInfo` — Información de alquiler del equipo (si aplica).
- `EnergyConsumption` — Registro de consumo energético del equipo.

**Value Objects:**

- `EquipmentIdentifier(SerialNumber, Model, Brand)` — Identificador único de negocio del equipo.
- `Coordinates(Latitude, Longitude)` — Coordenadas geográficas.
- `EEquipmentStatus` — Enum: `Active`, `Inactive`, `UnderMaintenance`, `Retired`.
- `EEquipmentType` — Enum: `Refrigerator`, `Freezer`, `AirConditioner`, etc.
- `EOwnershipType` — Enum: `Owned`, `Rented`.

**Commands:**

- `CreateEquipmentCommand`
- `UpdateEquipmentLocationCommand`
- `UpdateEquipmentPowerStateCommand`
- `UpdateEquipmentTemperatureCommand`
- `DeleteEquipmentCommand`

**Queries:**

- `GetAllEquipmentsQuery`
- `GetEquipmentByIdQuery(int Id)`
- `GetEquipmentsByOwnerIdQuery(int OwnerId)`
- `GetEquipmentsByStatusQuery(EEquipmentStatus Status)`
- `GetEquipmentsByTypeQuery(EEquipmentType Type)`

**Repositories:**

- `IEquipmentRepository` — Contrato de persistencia con búsquedas por OwnerId, Status y Type.

**Domain Services:**

- `IEquipmentCommandService`
- `IEquipmentQueryService`

---

##### 4.2.3.2. Interface Layer

**Controllers REST:**

- `EquipmentsController` (`/api/v1/equipments`)
    - `POST /` — Crea un nuevo equipo.
    - `GET /` — Lista todos los equipos.
    - `GET /{id}` — Retorna equipo por ID.
    - `PUT /{id}/location` — Actualiza ubicación.
    - `PUT /{id}/power-state` — Actualiza estado de encendido.
    - `PUT /{id}/temperature` — Actualiza temperatura configurada.
    - `DELETE /{id}` — Elimina un equipo.

**Resources:**

- `CreateEquipmentResource`, `EquipmentResource`, `UpdateEquipmentLocationResource`, `UpdateEquipmentPowerStateResource`, `UpdateEquipmentTemperatureResource`, `EquipmentOperationParametersResource`

**Assemblers:**

- `CreateEquipmentCommandFromResourceAssembler`
- `EquipmentResourceFromEntityAssembler`

---

##### 4.2.3.3. Application Layer

**Command Services:**

- `EquipmentCommandService` — Implementa `IEquipmentCommandService`.
    - `Handle(CreateEquipmentCommand)`: Crea y persiste un nuevo equipo.
    - `Handle(UpdateEquipmentLocationCommand)`: Actualiza la ubicación del equipo.
    - `Handle(UpdateEquipmentPowerStateCommand)`: Cambia el estado de energía.
    - `Handle(UpdateEquipmentTemperatureCommand)`: Actualiza la temperatura configurada.
    - `Handle(DeleteEquipmentCommand)`: Elimina el equipo del sistema.

**Query Services:**

- `EquipmentQueryService` — Implementa `IEquipmentQueryService`.
    - Maneja todas las queries de búsqueda de equipos.

---

##### 4.2.3.4. Infrastructure Layer

**Persistence (EFC):**

- `EquipmentRepository` — Implementa `IEquipmentRepository` con EF Core.
- `ModelBuilderExtensions.ApplyEquipmentConfiguration()` — Configura las tablas:
    - `equipments` — Tabla principal con columnas de identificador, tipo, estado, propietario.
    - Value Objects `EquipmentIdentifier`, `Coordinates` mapeados como owned entities.
    - Relaciones con `energy_consumptions`, `locations`, `rental_infos`.

---

##### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

![Equipment Component Diagram](assets/chapter04/DSL/Equipment_Components-dark.png)

**Leyenda:**

![Equipment Component Diagram Key](assets/chapter04/DSL/Equipment_Components-dark-key.png)

---

##### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class Equipment {
        -Long id
        -Long ownerProfileId
        -String name
        -String brand
        -String model
        -String serialNumber
        -EquipmentType type
        -EquipmentStatus status
        -TemperatureRange tempRange
        -Decimal maxConsumption
        +activate() void
        +deactivate() void
        +setMaintenance() void
        +triggerAlert() void
        +updateThresholds(range TemperatureRange) void
    }

    class TemperatureRange {
        <<value object>>
        -Decimal minTemp
        -Decimal maxTemp
        -Decimal minHumidity
        -Decimal maxHumidity
        +isWithinRange(temp, humidity) Boolean
    }

    class EquipmentType {
        <<enumeration>>
        REFRIGERATOR
        FREEZER
        COLD_ROOM
        SHOWCASE
        OTHER
    }

    class EquipmentStatus {
        <<enumeration>>
        ACTIVE
        INACTIVE
        MAINTENANCE
        ALERT
    }

    class EquipmentDocument {
        -Long id
        -Long equipmentId
        -DocumentType docType
        -String fileUrl
        -DateTime uploadedAt
    }

    class IEquipmentRepository {
        <<interface>>
        +findById(id Long) Equipment
        +findByOwnerId(ownerId Long) List~Equipment~
        +save(equipment Equipment) Equipment
        +delete(id Long) void
    }

    class EquipmentRepository {
        <<repository>>
    }

    class EquipmentService {
        <<service>>
        +registerEquipment(command RegisterEquipmentCommand) Equipment
        +updateEquipment(id Long, command UpdateEquipmentCommand) Equipment
        +getEquipmentByOwner(ownerId Long) List~Equipment~
        +changeStatus(id Long, status EquipmentStatus) void
    }

    Equipment --> EquipmentType
    Equipment --> EquipmentStatus
    Equipment --> TemperatureRange
    Equipment "1" --> "0..*" EquipmentDocument
    EquipmentService --> IEquipmentRepository
    IEquipmentRepository <|.. EquipmentRepository
```

###### 4.2.3.6.2. Bounded Context Database Design Diagram

![Equipment Database Design](assets/chapter04/DSL/Contenedores-dark.png)

---

#### 4.2.4. Bounded Context: Service Requests

##### 4.2.4.1. Domain Layer

El Domain Layer del bounded context **Service Requests** gestiona las solicitudes de servicio técnico que los clientes realizan para sus equipos. Modela el flujo completo desde la creación de la solicitud hasta su resolución, incluyendo asignación de técnico, cambios de estado y retroalimentación del cliente.

**Aggregate Root:**

- `ServiceRequest` — Entidad raíz con `Id`, `OrderNumber`, `Title`, `Description`, `IssueDetails`, `Status`, `Priority`, `Urgency`, `IsEmergency`, `ServiceType`, `ClientId`, `CompanyId`, `EquipmentId`, `AssignedTechnicianId`, fechas de programación, detalles de resolución y `CustomerFeedbackRating`.

**Value Objects (Enums):**

- `EServiceRequestStatus` — `Pending`, `Accepted`, `InProgress`, `Resolved`, `Cancelled`, `Rejected`.
- `EPriority` — `Low`, `Medium`, `High`, `Critical`.
- `EUrgency` — `Normal`, `Urgent`, `Emergency`.
- `EServiceType` — `Diagnostic`, `Repair`, `Maintenance`, `Installation`.

**Commands:**

- `CreateServiceRequestCommand`
- `UpdateServiceRequestCommand`
- `UpdateServiceRequestStatusCommand`
- `AssignTechnicianToServiceRequestCommand`
- `CancelServiceRequestCommand`
- `RejectServiceRequestCommand`
- `AddCustomerFeedbackToServiceRequestCommand`

**Queries:**

- `GetAllServiceRequestsQuery`
- `GetServiceRequestByIdQuery(int Id)`
- `GetServiceRequestsByStatusQuery(EServiceRequestStatus Status)`
- `GetServiceRequestsByEquipmentIdQuery(int EquipmentId)`

**Domain Methods (comportamiento en el agregado):**

- `AssignTechnician(technicianId)` — Asigna técnico y cambia estado a `Accepted`.
- `UpdateStatus(newStatus)` — Cambia el estado con reglas de negocio.
- `Reject()` — Solo desde estado `Pending`.
- `Cancel()` — No permitido desde `Resolved`, `Cancelled` o `Rejected`.
- `AddResolutionDetails(...)` — Agrega resolución y cambia a `Resolved`.
- `AddCustomerFeedback(rating)` — Solo desde `Resolved`, rating 1-5.

---

##### 4.2.4.2. Interface Layer

**Controllers REST:**

- `ServiceRequestsController` (`/api/v1/service-requests`)
    - `POST /` — Crea una nueva solicitud.
    - `GET /` — Lista todas las solicitudes.
    - `GET /{id}` — Retorna solicitud por ID.
    - `PUT /{id}/status` — Actualiza el estado.
    - `PUT /{id}/assign-technician` — Asigna técnico.
    - `PUT /{id}/customer-feedback` — Agrega retroalimentación.
    - `PUT /{id}/cancel` — Cancela la solicitud.
    - `PUT /{id}/reject` — Rechaza la solicitud.

**Resources:**

- `CreateServiceRequestResource`, `ServiceRequestResource`, `UpdateServiceRequestResource`, `UpdateServiceRequestStatusResource`, `AssignTechnicianToServiceRequestResource`, `AddCustomerFeedbackToServiceRequestResource`

**Assemblers:**

- `CreateServiceRequestCommandFromResourceAssembler`
- `ServiceRequestResourceFromEntityAssembler`
- `AssignTechnicianToServiceRequestCommandFromResourceAssembler`
- `AddCustomerFeedbackToServiceRequestCommandFromResourceAssembler`
- `UpdateServiceRequestCommandFromResourceAssembler`

---

##### 4.2.4.3. Application Layer

**Command Services:**

- `ServiceRequestCommandService` — Implementa `IServiceRequestCommandService`.
    - Maneja todos los comandos: crear, actualizar, asignar técnico, cancelar, rechazar, agregar feedback.

**Query Services:**

- `ServiceRequestQueryService` — Implementa `IServiceRequestQueryService`.
    - Maneja todas las queries de búsqueda y filtrado de solicitudes.

---

##### 4.2.4.4. Infrastructure Layer

**Persistence (EFC):**

- `ServiceRequestRepository` — Implementa `IServiceRequestRepository`.
- `ModelBuilderExtensions.ApplyServiceRequestsConfiguration()` — Configura la tabla `service_requests` con todas las columnas, enums como strings y relaciones con `equipments`.

---

##### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

![ServiceRequest Component Diagram](assets/chapter04/DSL/ServiceRequest_Components-dark.png)

**Leyenda:**

![ServiceRequest Component Diagram Key](assets/chapter04/DSL/ServiceRequest_Components-dark-key.png)

---

##### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class SensorReading {
        -Long id
        -Long equipmentId
        -String deviceId
        -Decimal temperature
        -Decimal humidity
        -Decimal consumptionKwh
        -DateTime readingAt
        -ReadingSource source
        +isAnomalous(rules List~BusinessRule~) Boolean
    }

    class Alert {
        -Long id
        -Long equipmentId
        -Long readingId
        -AlertType alertType
        -Severity severity
        -String message
        -Decimal triggeredValue
        -Decimal thresholdValue
        -Boolean resolved
        -DateTime resolvedAt
        +resolve() void
        +isActive() Boolean
    }

    class BusinessRule {
        -Long id
        -Long equipmentId
        -RuleType ruleType
        -Decimal thresholdValue
        -Severity severity
        -Boolean isActive
        +evaluate(reading SensorReading) Boolean
        +activate() void
        +deactivate() void
    }

    class AlertType {
        <<enumeration>>
        HIGH_TEMP
        LOW_TEMP
        HIGH_HUMIDITY
        LOW_HUMIDITY
        HIGH_CONSUMPTION
        CONNECTION_LOST
    }

    class RuleType {
        <<enumeration>>
        MAX_TEMP
        MIN_TEMP
        MAX_HUMIDITY
        MIN_HUMIDITY
        MAX_CONSUMPTION
    }

    class Severity {
        <<enumeration>>
        LOW
        MEDIUM
        HIGH
        CRITICAL
    }

    class ReadingSource {
        <<enumeration>>
        PHYSICAL
        SIMULATED
    }

    class ThresholdEvaluationService {
        <<domain service>>
        +evaluate(reading SensorReading, rules List~BusinessRule~) List~Alert~
        +generateAlert(reading SensorReading, rule BusinessRule) Alert
    }

    class ISensorReadingRepository {
        <<interface>>
        +save(reading SensorReading) SensorReading
        +findByEquipmentId(id Long) List~SensorReading~
        +findByDateRange(equipmentId Long, from DateTime, to DateTime) List~SensorReading~
    }

    class IAlertRepository {
        <<interface>>
        +save(alert Alert) Alert
        +findActiveByEquipmentId(id Long) List~Alert~
        +resolve(alertId Long) void
    }

    class IBusinessRuleRepository {
        <<interface>>
        +findActiveByEquipmentId(id Long) List~BusinessRule~
        +save(rule BusinessRule) BusinessRule
    }

    class SensorReadingRepository {
        <<repository>>
    }

    class AlertRepository {
        <<repository>>
    }

    class BusinessRuleRepository {
        <<repository>>
    }

    SensorReading --> ReadingSource
    Alert --> AlertType
    Alert --> Severity
    BusinessRule --> RuleType
    BusinessRule --> Severity
    Alert --> SensorReading
    ThresholdEvaluationService --> SensorReading
    ThresholdEvaluationService --> BusinessRule
    ThresholdEvaluationService --> Alert
    ISensorReadingRepository <|.. SensorReadingRepository
    IAlertRepository <|.. AlertRepository
    IBusinessRuleRepository <|.. BusinessRuleRepository
```

###### 4.2.4.6.2. Bounded Context Database Design Diagram

![ServiceRequest Database Design](assets/chapter04/DSL/Contenedores-dark.png)

---

#### 4.2.5. Bounded Context: Work Orders

##### 4.2.5.1. Domain Layer

El Domain Layer del bounded context **Work Orders** gestiona las órdenes de trabajo que se generan para atender las solicitudes de servicio. Una `WorkOrder` representa el trabajo técnico concreto que un técnico debe ejecutar sobre un equipo, incluyendo programación, asignación, resolución y retroalimentación.

**Aggregate Root:**

- `WorkOrder` — Entidad raíz con `Id`, `WorkOrderNumber` (generado automáticamente como `WO-YYYYMMDD-XXXXXXXX`), `ServiceRequestId` (opcional), `Title`, `Description`, `IssueDetails`, `Status`, `Priority`, `AssignedTechnicianId`, `ScheduledDate`, `TimeSlot`, `ServiceAddress`, `ResolutionDetails`, `TechnicianNotes`, `Cost`, `CustomerFeedbackRating` y `EquipmentId`.

**Value Objects (Enums):**

- `EWorkOrderStatus` — `Created`, `Assigned`, `InProgress`, `Completed`, `Resolved`, `Cancelled`.
- (Comparte `EPriority` y `EServiceType` del namespace de ServiceRequests).

**Commands:**

- `CreateWorkOrderCommand`
- `UpdateWorkOrderStatusCommand`
- `AssignTechnicianToWorkOrderCommand`
- `AddWorkOrderResolutionDetailsCommand`
- `AddWorkOrderCustomerFeedbackCommand`

**Queries:**

- `GetAllWorkOrdersQuery`
- `GetWorkOrderByIdQuery(int Id)`
- `GetWorkOrderByWorkOrderNumberQuery(string Number)`
- `GetWorkOrderByServiceRequestIdQuery(int ServiceRequestId)`
- `GetWorkOrdersByEquipmentIdQuery(int EquipmentId)`
- `GetWorkOrdersByStatusQuery(EWorkOrderStatus Status)`
- `GetWorkOrdersByTechnicianIdQuery(int TechnicianId)`

**Domain Methods:**

- `AssignTechnician(technicianId)` — Asigna técnico y cambia a estado `Assigned`.
- `UpdateStatus(newStatus)` — Cambia el estado, registra `ActualCompletionDate` si es `Completed`/`Resolved`.
- `AddResolutionDetails(resolution, notes, cost)` — Agrega resolución y marca como `Resolved`.
- `SetCustomerFeedbackRating(rating)` — Rating 1-5 con validación.

---

##### 4.2.5.2. Interface Layer

**Controllers REST:**

- `WorkOrdersController` (`/api/v1/work-orders`)
    - `POST /` — Crea una nueva orden de trabajo.
    - `GET /` — Lista todas las órdenes.
    - `GET /{id}` — Retorna orden por ID.
    - `PUT /{id}/status` — Actualiza el estado.
    - `PUT /{id}/assign-technician` — Asigna técnico.
    - `PUT /{id}/resolution` — Agrega detalles de resolución.
    - `PUT /{id}/customer-feedback` — Agrega retroalimentación del cliente.

**Resources:**

- `CreateWorkOrderResource`, `WorkOrderResource`, `UpdateWorkOrderStatusResource`, `AssignTechnicianResource`, `AddCustomerFeedbackResource`

**Assemblers:**

- `CreateWorkOrderCommandFromResourceAssembler`
- `WorkOrderResourceFromEntityAssembler`
- `UpdateWorkOrderStatusCommandFromResourceAssembler`
- `AddWorkOrderCustomerFeedbackCommandFromResourceAssembler`

---

##### 4.2.5.3. Application Layer

**Command Services:**

- `WorkOrderCommandService` — Implementa `IWorkOrderCommandService`.
    - Maneja todos los comandos: crear, actualizar estado, asignar técnico, agregar resolución y feedback.

**Query Services:**

- `WorkOrderQueryService` — Implementa `IWorkOrderQueryService`.
    - Maneja todas las queries de búsqueda por ID, número, técnico, equipo y estado.

---

##### 4.2.5.4. Infrastructure Layer

**Persistence (EFC):**

- `WorkOrderRepository` — Implementa `IWorkOrderRepository`.
- `ModelBuilderExtensions.ApplyWorkOrdersConfiguration()` — Configura la tabla `work_orders` con todas las columnas, enums como strings y FK a `equipments`.

---

##### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

![WorkOrder Component Diagram](assets/chapter04/DSL/WorkOrder_Components-dark.png)

**Leyenda:**

![WorkOrder Component Diagram Key](assets/chapter04/DSL/WorkOrder_Components-dark-key.png)

---

##### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class ServiceRequest {
        -Long id
        -Long ownerProfileId
        -Long equipmentId
        -Long providerProfileId
        -String title
        -String description
        -Priority priority
        -RequestStatus status
        -DateTime requestedAt
        +accept(providerId Long) void
        +complete() void
        +cancel() void
        +assignProvider(providerId Long) void
    }

    class Priority {
        <<enumeration>>
        LOW
        MEDIUM
        HIGH
        URGENT
    }

    class RequestStatus {
        <<enumeration>>
        PENDING
        ACCEPTED
        IN_PROGRESS
        COMPLETED
        CANCELLED
    }

    class ServiceRequestPhoto {
        -Long id
        -Long serviceRequestId
        -String photoUrl
        -DateTime uploadedAt
    }

    class IServiceRequestRepository {
        <<interface>>
        +findById(id Long) ServiceRequest
        +findByOwnerId(ownerId Long) List~ServiceRequest~
        +findByProviderId(providerId Long) List~ServiceRequest~
        +save(request ServiceRequest) ServiceRequest
    }

    class ServiceRequestRepository {
        <<repository>>
    }

    class ServiceRequestService {
        <<service>>
        +createRequest(command CreateServiceRequestCommand) ServiceRequest
        +acceptRequest(requestId Long, providerId Long) ServiceRequest
        +completeRequest(requestId Long) ServiceRequest
        +cancelRequest(requestId Long) void
    }

    ServiceRequest --> Priority
    ServiceRequest --> RequestStatus
    ServiceRequest "1" --> "0..*" ServiceRequestPhoto
    ServiceRequestService --> IServiceRequestRepository
    IServiceRequestRepository <|.. ServiceRequestRepository
```

###### 4.2.5.6.2. Bounded Context Database Design Diagram

![WorkOrder Database Design](assets/chapter04/DSL/Contenedores-dark.png)

---

#### 4.2.6. Bounded Context: Analytics

##### 4.2.6.1. Domain Layer

El Domain Layer del bounded context **Analytics** gestiona la recopilación y análisis de datos operativos de los equipos de refrigeración: lecturas de temperatura, consumo energético y promedios diarios de temperatura.

**Aggregate Root:**

- `EquipmentAnalytics` — Entidad raíz asociada a un equipo (`EquipmentId`). Agrupa colecciones de `TemperatureReadings` y `EnergyReadings`. Expone métodos como `RecordTemperature`, `RecordEnergyConsumption`, `GetTemperatureStatus` y `GetEnergyStatus`.

**Entities:**

- `TemperatureReading(Id, EquipmentId, Temperature, Timestamp, Status)` — Lectura de temperatura puntual.
- `EnergyReading(Id, EquipmentId, Consumption, Unit, Timestamp, Status)` — Lectura de consumo energético.
- `DailyTemperatureAverage(Id, EquipmentId, Date, AverageTemperature, MinTemperature, MaxTemperature)` — Promedio diario de temperatura calculado.

**Value Objects:**

- `TemperatureRange(Min, Max)` — Rango válido de temperatura con métodos `IsWithinRange` y `IsValid`.
- `AnalyticsTimeframe(Hours)` — Ventana temporal para consultas analíticas. Máximo 8760h (1 año).
- `EReadingStatus` — Enum: `Normal`, `Warning`, `Critical`.

**Commands:**

- `RecordTemperatureReadingCommand(EquipmentId, Temperature, Timestamp?)`
- `RecordEnergyReadingCommand(EquipmentId, Consumption, Unit)`

**Queries:**

- `GetEquipmentAnalyticsQuery(int EquipmentId)`
- `GetTemperatureReadingsQuery(int EquipmentId, int Hours = 24)`
- `GetEnergyReadingsQuery(int EquipmentId, int Hours = 24)`
- `GetDailyTemperatureAveragesQuery(int EquipmentId, int Days = 7)`

**Repositories:**

- `IAnalyticsRepository` — Contrato con operaciones para temperatura, energía y promedios diarios.

---

##### 4.2.6.2. Interface Layer

**Controllers REST:**

- `AnalyticsController` (`/api/v1/analytics/equipments`)
    - `GET /{equipmentId}/readings?type=all|temperature|energy&hours=24` — Lecturas unificadas.
    - `GET /{equipmentId}/summaries?type=daily-averages&days=7` — Resúmenes analíticos.
    - `GET /overview?ids=1,2,3` — Vista general de múltiples equipos.

**Resources:**

- `UnifiedReadingResource(Id, EquipmentId, Type, Value, Unit, Timestamp, Status)`
- `AnalyticsSummaryResource(Id, EquipmentId, Date, Type, AverageTemperature, Min, Max)`
- `CreateTemperatureReadingResource`, `CreateEnergyReadingResource`

**Assemblers:**

- `CreateTemperatureReadingCommandFromResourceAssembler`
- `CreateEnergyReadingCommandFromResourceAssembler`
- `TemperatureReadingResourceFromEntityAssembler`
- `EnergyReadingResourceFromEntityAssembler`
- `DailyTemperatureAverageResourceFromEntityAssembler`

---

##### 4.2.6.3. Application Layer

**Command Services:**

- `AnalyticsCommandService` — Implementa `IAnalyticsCommandService`.
    - `Handle(RecordTemperatureReadingCommand)`: Valida rango -50°C a 100°C, persiste la lectura.
    - `Handle(RecordEnergyReadingCommand)`: Valida que el consumo no sea negativo, persiste la lectura.

**Query Services:**

- `AnalyticsQueryService` — Implementa `IAnalyticsQueryService`.
    - `Handle(GetTemperatureReadingsQuery)`: Lecturas de temperatura por equipo en ventana de horas.
    - `Handle(GetDailyTemperatureAveragesQuery)`: Promedios diarios por equipo.
    - `Handle(GetEnergyReadingsQuery)`: Lecturas de energía por equipo.

---

##### 4.2.6.4. Infrastructure Layer

**Persistence (EFC):**

- `AnalyticsRepository` — Implementa `IAnalyticsRepository`.
- `ModelBuilderExtensions.ApplyAnalyticsConfiguration()` — Configura las tablas:
    - `temperature_readings` — con índice compuesto `(equipment_id, timestamp)`. FK a `equipments`.
    - `energy_readings` — con índice compuesto `(equipment_id, timestamp)`. FK a `equipments`.
    - `daily_temperature_averages` — con índice único `(equipment_id, date)`. FK a `equipments`.
    - `equipment_analytics` — con índice único por `equipment_id`. FK a `equipments`.

---

##### 4.2.6.5. Bounded Context Software Architecture Component Level Diagrams

![Analytics Component Diagram](assets/chapter04/DSL/Analytics_Components-dark.png)

**Leyenda:**

![Analytics Component Diagram Key](assets/chapter04/DSL/Analytics_Components-dark-key.png)

---

##### 4.2.6.6. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.6.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class WorkOrder {
        -Long id
        -Long serviceRequestId
        -Long technicianId
        -Long equipmentId
        -String title
        -String description
        -WorkOrderStatus status
        -DateTime scheduledAt
        -String diagnosis
        -String solution
        +start() void
        +complete(diagnosis, solution String) void
        +cancel() void
        +addActivity(activity WorkOrderActivity) void
    }

    class WorkOrderStatus {
        <<enumeration>>
        ASSIGNED
        IN_PROGRESS
        COMPLETED
        CANCELLED
    }

    class WorkOrderActivity {
        -Long id
        -Long workOrderId
        -ActivityType activityType
        -String description
        -String fileUrl
        -DateTime loggedAt
    }

    class ActivityType {
        <<enumeration>>
        NOTE
        PHOTO
        STATUS_CHANGE
        PART_USED
    }

    class SparePart {
        -Long id
        -Long workOrderId
        -String partName
        -Integer quantity
        -Decimal unitCost
        +totalCost() Decimal
    }

    class IWorkOrderRepository {
        <<interface>>
        +findById(id Long) WorkOrder
        +findByTechnicianId(id Long) List~WorkOrder~
        +findByEquipmentId(id Long) List~WorkOrder~
        +save(workOrder WorkOrder) WorkOrder
    }

    class WorkOrderRepository {
        <<repository>>
    }

    class WorkOrderService {
        <<service>>
        +createWorkOrder(command CreateWorkOrderCommand) WorkOrder
        +startWorkOrder(id Long) WorkOrder
        +completeWorkOrder(id Long, command CompleteWorkOrderCommand) WorkOrder
        +addActivity(id Long, activity WorkOrderActivity) void
    }

    WorkOrder --> WorkOrderStatus
    WorkOrder "1" --> "0..*" WorkOrderActivity
    WorkOrder "1" --> "0..*" SparePart
    WorkOrderActivity --> ActivityType
    WorkOrderService --> IWorkOrderRepository
    IWorkOrderRepository <|.. WorkOrderRepository
```

###### 4.2.6.6.2. Bounded Context Database Design Diagram

![Analytics Database Design](assets/chapter04/DSL/Contenedores-dark.png)

---

#### 4.2.7. Bounded Context: Subscriptions and Payments

##### 4.2.7.1. Domain Layer

El Domain Layer del bounded context **Subscriptions and Payments** gestiona los planes de suscripción y el procesamiento de pagos de los usuarios de la plataforma, integrándose con Stripe como pasarela de pago externa.

**Aggregates:**

- `Subscription` — Entidad raíz con `Id`, `UserId`, `PlanName`, `BillingCycle`, `Features`, `StartDate`, `EndDate`, `Status`. Permite gestionar el ciclo de vida de la suscripción.
- `Payment` — Entidad raíz con `Id`, `UserId`, `SubscriptionId`, `StripeSession`, `Amount`, `Status`. Representa una transacción de pago.

**Value Objects:**

- `BillingCycle` — Representa el ciclo de facturación (mensual, anual).
- `Feature` — Representa una característica incluida en un plan.
- `Price(Amount, Currency)` — Precio del plan.
- `PaymentStatus` — Estado del pago (Pending, Completed, Failed, Refunded).
- `StripeSession(SessionId, SessionUrl)` — Datos de la sesión de pago en Stripe.

**Commands:**

- `CreateSubscriptionCommand`
- `DeleteSubscriptionCommand`
- `UpgradePlanCommand`
- `CreatePaymentSessionCommand`
- `ProcessPaymentWebhookCommand`

**Queries:**

- `GetSubscriptionByIdQuery(int Id)`
- `GetPlansQuery`

**Domain Services:**

- `ISubscriptionCommandService`, `ISubscriptionQueryService`
- `IPaymentCommandService`
- `IStripeService` — Abstracción de la integración con Stripe.

---

##### 4.2.7.2. Interface Layer

**Controllers REST:**

- `SubscriptionsController` (`/api/v1/subscriptions`)
    - `POST /` — Crea una nueva suscripción con sesión de pago Stripe.
    - `GET /{id}` — Retorna suscripción por ID.
    - `PUT /{id}/upgrade` — Actualiza el plan.
    - `DELETE /{id}` — Cancela la suscripción.

**Resources:**

- `CreateSubscriptionResource(UserId, PlanName, BillingCycle)`
- `SubscriptionResource(Id, UserId, PlanName, Status, StartDate, EndDate)`

**Assemblers:**

- `CreateSubscriptionCommandFromResourceAssembler`
- `SubscriptionResourceFromEntityAssembler`
- `UpgradeSubscriptionCommandFromResourceAssembler`

---

##### 4.2.7.3. Application Layer

**Command Services:**

- `SubscriptionsCommandServices` — Implementa `ISubscriptionCommandService`.
    - `Handle(CreateSubscriptionCommand)`: Crea la suscripción y genera la sesión de pago en Stripe.
    - `Handle(UpgradePlanCommand)`: Actualiza el plan del usuario.
    - `Handle(DeleteSubscriptionCommand)`: Cancela la suscripción.
- `PaymentCommandService` — Implementa `IPaymentCommandService`.
    - `Handle(CreatePaymentSessionCommand)`: Crea sesión de Stripe Checkout.
    - `Handle(ProcessPaymentWebhookCommand)`: Procesa webhooks de Stripe para confirmar pagos.

**Query Services:**

- `SubscriptionQueryService` — Retorna suscripciones por ID y lista planes disponibles.

---

##### 4.2.7.4. Infrastructure Layer

**Persistence (EFC):**

- `SubscriptionRepository` — Implementa `ISubscriptionRepository`.
- `PaymentRepository` — Implementa `IPaymentRepository`.
- `ModelBuilderExtensions.ApplySubscriptionsConfiguration()` — Configura tablas `subscriptions` y `payments`, con value objects `BillingCycle`, `Price`, `StripeSession` mapeados como columnas.

**External Integration:**

- `StripeSettings` — Configuración del API key de Stripe leída desde `appsettings.json`.
- Implementación de `IStripeService` usando el SDK oficial de Stripe para crear sesiones de Checkout y procesar webhooks.

---

##### 4.2.7.5. Bounded Context Software Architecture Component Level Diagrams

![Subscriptions Component Diagram](assets/chapter04/DSL/Subscriptions_Components-dark.png)

**Leyenda:**

![Subscriptions Component Diagram Key](assets/chapter04/DSL/Subscriptions_Components-dark-key.png)

---

##### 4.2.7.6. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.7.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class Plan {
        -Long id
        -String name
        -String description
        -Decimal priceMonthly
        -Integer maxEquipment
        -Integer maxTechnicians
        -Boolean isActive
        +activate() void
        +deactivate() void
    }

    class Subscription {
        -Long id
        -Long ownerProfileId
        -Long planId
        -SubscriptionStatus status
        -DateTime startedAt
        -DateTime expiresAt
        +cancel() void
        +renew(plan Plan) void
        +isActive() Boolean
        +isExpired() Boolean
    }

    class SubscriptionStatus {
        <<enumeration>>
        ACTIVE
        CANCELLED
        EXPIRED
        TRIAL
    }

    class Payment {
        -Long id
        -Long subscriptionId
        -Decimal amount
        -String currency
        -PaymentStatus status
        -String izipayRef
        -DateTime paidAt
        +markCompleted(ref String) void
        +markFailed() void
    }

    class PaymentStatus {
        <<enumeration>>
        PENDING
        COMPLETED
        FAILED
        REFUNDED
    }

    class ISubscriptionRepository {
        <<interface>>
        +findById(id Long) Subscription
        +findByOwnerId(ownerId Long) Subscription
        +save(subscription Subscription) Subscription
    }

    class SubscriptionRepository {
        <<repository>>
    }

    class SubscriptionService {
        <<service>>
        +subscribe(ownerId Long, planId Long) Subscription
        +cancelSubscription(subscriptionId Long) void
        +processPayment(subscriptionId Long) Payment
        +renewSubscription(subscriptionId Long) Subscription
    }

    Subscription --> Plan
    Subscription --> SubscriptionStatus
    Subscription "1" --> "0..*" Payment
    Payment --> PaymentStatus
    SubscriptionService --> ISubscriptionRepository
    ISubscriptionRepository <|.. SubscriptionRepository
```

###### 4.2.7.6.2. Bounded Context Database Design Diagram

![Subscriptions Database Design](assets/chapter04/DSL/Contenedores-dark.png)

---

#### 4.2.8. Bounded Context: Technicians

##### 4.2.8.1. Domain Layer

El Domain Layer del bounded context **Technicians** gestiona la información de los técnicos de servicio disponibles en la plataforma. Permite registrar técnicos, consultarlos y calcular métricas de rendimiento como el promedio de calificaciones recibidas.

**Entity Principal:**

- `Technician` — Entidad principal con `Id`, `FirstName`, `LastName`, `Email`, `Phone`, `Specialization`, `IsAvailable` y `AverageRating`. Representa a un técnico de mantenimiento de equipos de refrigeración.

**Domain Events:**

- `TechnicianCreatedEvent` — Evento publicado al crear un nuevo técnico.

**Commands:**

- `CreateTechnicianCommand(FirstName, LastName, Email, Phone, Specialization)`

**Queries:**

- `GetAllTechniciansQuery` — Retorna todos los técnicos.
- `GetTechnicianByIdQuery(int Id)` — Retorna técnico por ID.
- `GetTechnicianAverageRatingQuery(int TechnicianId)` — Calcula el promedio de calificaciones del técnico.

**Repositories:**

- `ITechnicianRepository` — Contrato de persistencia con búsqueda por ID y listado.

**Domain Services:**

- `ITechnicianCommandService`
- `ITechnicianQueryService`

---

##### 4.2.8.2. Interface Layer

**Controllers REST:**

- `TechniciansController` (`/api/v1/technicians`)
    - `POST /` — Registra un nuevo técnico.
    - `GET /` — Lista todos los técnicos.
    - `GET /{id}` — Retorna técnico por ID.

**Resources:**

- `CreateTechnicianResource(FirstName, LastName, Email, Phone, Specialization)`
- `TechnicianResource(Id, FirstName, LastName, Email, Phone, Specialization, IsAvailable, AverageRating)`

**Assemblers:**

- `CreateTechnicianCommandFromResourceAssembler`
- `TechnicianResourceFromEntityAssembler`

---

##### 4.2.8.3. Application Layer

**Command Services:**

- `TechnicianCommandService` — Implementa `ITechnicianCommandService`.
    - `Handle(CreateTechnicianCommand)`: Valida y persiste el nuevo técnico. Publica `TechnicianCreatedEvent`.

**Query Services:**

- `TechnicianQueryService` — Implementa `ITechnicianQueryService`.
    - `Handle(GetAllTechniciansQuery)`: Retorna lista de todos los técnicos.
    - `Handle(GetTechnicianByIdQuery)`: Retorna técnico por ID.
    - `Handle(GetTechnicianAverageRatingQuery)`: Calcula y retorna el promedio de calificaciones.

---

##### 4.2.8.4. Infrastructure Layer

**Persistence (EFC):**

- `TechnicianRepository` — Implementa `ITechnicianRepository` usando EF Core.
- `ModelBuilderExtensions.ApplyTechniciansConfiguration()` — Configura la tabla `technicians` con columnas de datos personales, especialización, disponibilidad y calificación promedio.

---

##### 4.2.8.5. Bounded Context Software Architecture Component Level Diagrams

![Notifications Component Diagram](assets/chapter04/DSL/Notifications_Components-dark.png)

**Leyenda:**

![Notifications Component Diagram Key](assets/chapter04/DSL/Notifications_Components-dark-key.png)

---

##### 4.2.8.6. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.8.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class Notification {
        -Long id
        -Long userId
        -NotificationChannel channel
        -NotificationType type
        -String title
        -String body
        -Long referenceId
        -String referenceType
        -Boolean isRead
        -DateTime sentAt
        +markAsRead() void
        +isSent() Boolean
    }

    class NotificationChannel {
        <<enumeration>>
        EMAIL
        PUSH
        SMS
    }

    class NotificationType {
        <<enumeration>>
        ALERT
        WORK_ORDER
        PAYMENT
        SYSTEM
    }

    class NotificationPreference {
        -Long id
        -Long userId
        -Boolean emailEnabled
        -Boolean pushEnabled
        -Boolean alertHighTemp
        -Boolean alertLowTemp
        -Boolean alertWorkOrder
        -String fcmToken
        +updateFcmToken(token String) void
        +toggle(channel NotificationChannel) void
    }

    class INotificationRepository {
        <<interface>>
        +save(notification Notification) Notification
        +findByUserId(userId Long) List~Notification~
        +markAsRead(id Long) void
    }

    class NotificationRepository {
        <<repository>>
    }

    class NotificationService {
        <<service>>
        +sendPush(userId Long, title String, body String) void
        +sendEmail(userId Long, subject String, body String) void
        +getPreferences(userId Long) NotificationPreference
        +updatePreferences(userId Long, prefs NotificationPreference) void
    }

    Notification --> NotificationChannel
    Notification --> NotificationType
    NotificationService --> INotificationRepository
    NotificationService --> NotificationPreference
    INotificationRepository <|.. NotificationRepository
```

###### 4.2.8.6.2. Bounded Context Database Design Diagram

![Notifications Database Design](assets/chapter04/DSL/Contenedores-dark.png)

## Capítulo V: Solution UI/UX Design

### 5.1. Style Guidelines
#### 5.1.1. General Style Guidelines

Se busca que el tono sea equilibrado, entre lo profesional y lo accesible, con un lenguaje claro, empático y respetuoso para atraer usuarios potenciales y mantener a nuestros usuarios.
Se eligió una paleta de colores fría pero amigable, y una tipografía moderna que combine profesionalismo y accesibilidad.

**Branding**

La identidad visual de OsitoPolar busca transmitir seguridad, innovación y cercanía.

**Logo:** Representa un oso polar con un ícono de refrigeración, combinando lo técnico con lo amigable. Disponible en versiones para fondos claros y oscuros, monocromático, horizontal y vertical.


**Typography**

Para mantener la formalidad y accesibilidad de la interfaz de usuario de OsitoPolar se establecerá las tipografías Helvetica y Open Sans por sus características funcionales, estéticas y por su alta compatibilidad en interfaces digitales, siendo Helvetica la primaria.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Helvetica-typography.png"
       alt="Ejemplo de la tipografía Helvetica, mostrando su uso y características."
       style="max-width: 90%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Tipografía Helvetica.
  </figcaption>
</figure>


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Open-sans-typography.png"
       alt="Ejemplo de la tipografía Open Sans, mostrando sus características y uso."
       style="max-width: 90%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Tipografía Open Sans.
  </figcaption>
</figure>


**Colors**

La paleta fue diseñada para representar ambientes fríos y tecnológicos, transmitiendo confianza y limpieza visual.

El color principal elegido es el celeste, pues es el que más se acopla a las características que describimos. Se optó por los colores negro, blanco y gris como neutros, los cuales serán utilizados para fondos o textos.
Se eligieron variantes de color verde, rojo, azul y amarillo para ciertos fondos y estados (alertas, servicio, calificaciones).


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Colors-General%20Style%20Guidelines.png"
       alt="Guías Generales de Estilo de Colores: Paleta principal y secundaria de la marca."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Guías Generales de Estilo - Colores.
  </figcaption>
</figure>



**Spacing**

Se establecerá un espaciado de 8 px y un margen mínimo de 16 px. Para el diseño modular, se implementarán grids flexibles que se adaptarán tanto a web como a dispositivos móviles, utilizando configuraciones de 12 y 4 columnas respectivamente.


#### 5.1.2. Web, Mobile and IoT Style Guidelines

En esta sección definimos los estándares visuales y de interacción para la versión web y mobile de OsitoPolar, asegurando una experiencia de usuario coherente, profesional y accesible en todos los dispositivos.
Es necesario que las interfaces web sean responsivas porque nos trae muchas ventajas tanto para el usuario como para el equipo desarrollador, entre las cuales tenemos: usabilidad en cualquier dispositivo, mejor eficiencia de costos y tiempo en el desarrollo y satisfacción del usuario.

Adoptando un enfoque mobile-first, usamos un sistema de grid de 12 columnas para que la interfaz se adapte a cualquier dispositivo.

**Tipografía**
Tomando en cuenta la guía de estilos, se usará la tipografía Helvetica en la mayoría de los textos de la aplicación, pues esta proyecta profesionalismo y claridad. Para que la visualización de los textos sea óptima, el tamaño de la fuente debe ajustarse automáticamente y adaptarse al dispositivo que se esté usando.


**Colores**
De acuerdo al rubro al que está orientado OsitoPolar, los colores deben reflejar tecnología, frescura y confianza. La elección de colores es la siguiente:

- Celeste (#0884C4): Se usará para el header y algunos botones.
- Blanco (#FFFFFF): Se usará para fondos neutros.
- Negro (#000000): Se usará en algunos botones y bordes.
- Gris claro (#808080): Se usará para líneas, bordes, separadores y botones deshabilitados.
- Blanco azul mar (#F4FCFC): Se usará para algunos fondos.
- Verde medio primavera (#00CC66): Se usará para notificaciones y estados positivos.
- Rojo claro (#FF4B4B): Se usará para alertas, errores y fallas críticas.
- Amarillo mandarina (#FFCC00): Se usará para ciertos agregados (notificaciones, calificaciones).

Sin embargo, la variación de botones y fondos que tendrá la plataforma hace que no siempre se elija la misma tonalidad, por lo que optamos por una paleta de celeste.


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Sky_blue-color-Web%20Style%20Guidelines.png"
       alt="Guías de Estilo Web: Muestra del color Sky Blue con sus códigos hexadecimales y RGB."
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Guías de Estilo Web - Color Sky Blue.
  </figcaption>
</figure>



De la misma forma se opta por una paleta de rojo claro para diferenciar ventanas, fondos o íconos que muestren algún tipo de error en el sistema, alertas o estados.


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Red-color-Web%20Style%20Guidelines.png"
       alt="Guías de Estilo Web: Muestra del color Rojo con sus códigos hexadecimales y RGB."
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 22:</strong> Guías de Estilo Web - Color Rojo.
  </figcaption>
</figure>


### 5.2. Information Architecture

#### 5.2.1. Organization Systems

En esta sección, hemos implementado diferentes sistemas de organización basados en los grupos de información relevantes. La disposición visual del contenido se ha realizado de las siguientes maneras:

- **Jerárquica (visual hierarchy)**: Para resaltar los elementos más importantes, facilitando que los usuarios accedan de manera intuitiva a la información clave.

- **Organización secuencial (step-by-step)**: Utilizada en procesos que requieren una guía detallada, como la compra de maquinas, asegurando un flujo lógico y fácil de seguir.

- **Organización matricial**: Aplicada en áreas donde es necesario comparar o analizar datos relacionados, proporcionando al usuario una visión clara y estructurada de las opciones disponibles.

#### 5.2.2. Labeling Systems

En nuestra empresa, aplicamos estos sistemas de organización visual de la siguiente manera:

Jerarquía Visual: Destacamos información clave como el estado de los equipos y alertas críticas para facilitar su rápida identificación.

Organización Secuencial: El proceso de agendar mantenimiento o visitas técnicas se organiza paso a paso para guiar al usuario.

Organización Matricial: Usamos tablas comparativas para mostrar claramente las diferencias entre planes de suscripción y servicios, facilitando la elección del usuario.

#### 5.2.3. SEO Tags and Meta Tags

**Landing Page**
-Title: OsitoPolar - Monitorea y Gestiona tus Equipos de Congelación en Tiempo Real
-Meta Description: OsitoPolar te permite monitorear y gestionar el estado de tus equipos de congelación, optimizando su rendimiento y evitando fallas. Mantén tu inventario seguro con alertas y mantenimiento predictivo.
-Meta Keywords: monitoreo de congeladoras, gestión de equipos de frío, mantenimiento preventivo, OsitoPolar, alerta de fallas, eficiencia energética
-Meta Author: OsitoPolar

**Aplicación Web**
-Title: OsitoPolar - Plataforma de Gestión de Equipos de Congelación
-Meta Description: OsitoPolar facilita el monitoreo, mantenimiento y eficiencia de tus equipos de congelación. Gestiona en tiempo real el estado y rendimiento de tus equipos con facilidad.
-Meta Keywords: gestión de equipos de frío, monitoreo en tiempo real, mantenimiento predictivo, OsitoPolar, alerta de fallas, reporte de eficiencia
-Meta Author: OsitoPolar

#### 5.2.4. Searching Systems

Estas decisiones están orientadas a facilitar la navegación eficiente, evitando que los usuarios se sientan abrumados por grandes volúmenes de datos y asegurando que encuentren rápidamente lo que necesitan.

**Opciones de Búsqueda**  
**Barra de Búsqueda**  
La barra de búsqueda permite a los usuarios ingresar términos específicos, como el nombre de un equipo, tipo de servicio o estado del equipo, para encontrar rápidamente información relevante. Los resultados se muestran instantáneamente a medida que se escriben los términos.

**Categorías**  
Los usuarios pueden seleccionar entre diferentes categorías de servicios y equipos, como "Congeladoras", "Refrigeradores", "Mantenimiento Preventivo", "Alertas de Fallas" y "Historial de Consumo", para limitar los resultados a un grupo específico.

**Etiquetas Populares**  
Las etiquetas populares, como "Mantenimiento Programado" o "Alertas Críticas", permiten a los usuarios buscar servicios o equipos relacionados con términos comunes, facilitando la localización de opciones populares o especializadas.

**Filtros Disponibles**  
**Filtros por Tipo de Equipo**
- Congeladoras
- Refrigeradores
- Equipos de Frío Industrial

**Filtros por Estado del Equipo**
- En Funcionamiento
- En Reparación
- Necesita Mantenimiento

**Filtro por Fecha de Última Revisión**  
Los usuarios pueden ajustar el filtro para ver los equipos que han sido revisados en un periodo específico, como "Últimos 7 días", "Últimos 30 días", etc.

**Filtro por Consumo Energético**  
Los usuarios pueden ajustar el rango de consumo energético para encontrar equipos dentro de un rango de eficiencia energética deseado.

**Apariencia de los Datos Después de la Búsqueda**  
**Listados de Resultados**  
Los resultados de búsqueda se muestran en una lista ordenada con información clave, como el nombre del equipo, estado actual, próximas fechas de mantenimiento y consumo energético. Además, se incluyen opciones para ver más detalles o agendar visitas de mantenimiento.

**Resumen y Descripción**  
Cada resultado incluye un resumen que resalta la información más relevante, como el historial de mantenimiento o las alertas generadas, permitiendo a los usuarios realizar una evaluación rápida.

**Opciones de Ordenación y Filtros Aplicados**  
Los resultados pueden ordenarse por criterios como relevancia, estado del equipo o consumo energético. Los filtros aplicados se muestran claramente para que los usuarios puedan ajustar su búsqueda según sea necesario.

**Revisiones y Comentarios**  
Los usuarios pueden ver un resumen de las revisiones y comentarios de los técnicos o clientes anteriores sobre el equipo o servicio, lo que les ayuda a evaluar la calidad del servicio y tomar decisiones informadas.

#### 5.2.5. Navigation Systems

La estructura de navegación y las opciones disponibles en **OsitoPolar** están diseñadas para ofrecer una experiencia de usuario fluida y eficiente. A continuación, se resumen las secciones y elementos clave:

1. **Páginas Principales**
    - **Inicio**: Página principal del sitio web.
    - **Funcionalidades**: Detalles sobre las herramientas y servicios que ofrece OsitoPolar.
    - **Beneficios**: Información sobre las ventajas para empresas y proveedores.
    - **Nosotros**: Información sobre la empresa y su misión.
    - **Contacto**: Información de contacto y formulario.

2. **Opciones de Usuario**
    - **Login**: Acceso a cuentas de usuario.
    - **Sign-up**: Registro de nuevos usuarios.
    - **Iniciar sesión / Registrarse**: Alternativa para acceso o creación de cuenta.

3. **Búsqueda y Navegación**
    - **Búsqueda**: Barra de búsqueda para encontrar equipos, servicios o reportes.
    - **Categorías**: Filtros por tipo de equipo (Congeladoras, Refrigeradores, etc.).
    - **Explorar**: Opciones para navegar por diferentes secciones de la plataforma.

4. **Branding y Identidad**
    - **OsitoPolar**: Logo y nombre de la marca, repetidos en varias secciones para mantener la identidad visual de la plataforma.

### 5.3. Landing Page UI Design
#### 5.3.1. Landing Page Wireframe

El wireframe de la página de inicio de OsitoPolar organiza los elementos clave para ofrecer una navegación intuitiva. Incluye un encabezado con el logo y un menú de navegación, seguido de una propuesta de valor clara con botones de acción destacados como "Solicitar Demo" y "¿Cómo Funciona?". La página cuenta con secciones para describir a los usuarios objetivo, las funcionalidades clave del sistema, y los beneficios que ofrece OsitoPolar. Al final, se encuentra un formulario de contacto para que los usuarios soliciten una demo, junto con enlaces legales en el pie de página.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/LandingPageWireframe.png"
       alt="Wireframe de la Landing Page: Diseño de baja fidelidad de la página principal."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Wireframe de la Landing Page.
  </figcaption>
</figure>


#### 5.3.2. Landing Page Mockup

El Landing Page Mock-up de OsitoPolar muestra un diseño limpio y organizado, con una estructura intuitiva que guía a los usuarios a través de la plataforma. Incluye una propuesta de valor destacada en la parte superior, seguida de secciones clave como las funcionalidades del sistema, los beneficios para empresas y proveedores, y una explicación clara de cómo funciona el servicio. También cuenta con testimonios de clientes, detalles sobre la empresa y un formulario para solicitar una demo, todo con un enfoque en facilitar la conversión de visitantes a usuarios activos.

- Esta es la primera sección, llamada "Inicio". En esta se puede ver la propuesta de valor que ofrece nuestra plataforma junto con un "Call to Action" que se agregará a futuro.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup1.png"
       alt="Mockup 1 de la Landing Page: Diseño visual de la sección superior."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Mockup 1 - Inicio - Landing Page.
  </figcaption>
</figure>


- Esta segunda sección hace una breve descripción de a quiénes está dirigido la plataforma.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup2.png"
       alt="Mockup 2 de la Landing Page: Diseño visual de la sección de características."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Mockup 2  - ¿Para quién es? - Landing Page.
  </figcaption>
</figure>


- En "Funcionalidades Clave" se presentan las principales funcionalidades que ofrece la plataforma.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup3.png"
       alt="Mockup 3 de la Landing Page: Diseño visual de la sección de testimonios."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Mockup 3 - Funcionalidades - Landing Page.
  </figcaption>
</figure>


- En "Beneficios" se presentan los beneficios que ofrece la plataforma para empresas y proveedores.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup4.png"
       alt="Mockup 4 de la Landing Page: Diseño visual de la sección de precios."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 4:</strong> Mockup 4 - Beneficios para negocios - Landing Page.
  </figcaption>
</figure>


- En "Beneficios" se presentan los beneficios que ofrece la plataforma para proveedores.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup5.png"
       alt="Mockup 5 de la Landing Page: Diseño visual de la sección de preguntas frecuentes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 5:</strong> Mockup 5 - Beneficios para proveedores - Landing Page.
  </figcaption>
</figure>


- En "Como funciona" se describe el flujo del funcionamiento de la plataforma.
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup6.png"
       alt="Mockup 6 de la Landing Page: Diseño visual del pie de página."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 6:</strong> Mockup 6 - ¿Como funciona? - Landing Page.
  </figcaption>
</figure>


- En "Sobre Nosotros" se presenta nuestra Misión y Visión como startup. 

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup7.png"
       alt="Mockup 7 de la Landing Page: Vista detallada de un elemento interactivo."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 7:</strong> Mockup 7 - Sobre Nosotros - Landing Page.
  </figcaption>
</figure>


- En "Lo que dicen nuestros clientes" se visualizan las reseñas de los usuarios que usaron nuestra plataforma.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup8.png"
       alt="Mockup 8 de la Landing Page: Vista detallada de un formulario de contacto."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 8:</strong> Mockup 8 - Lo que dicen nuestros clientes - Landing Page.
  </figcaption>
</figure>


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup9.png"
       alt="Mockup 9 de la Landing Page: Sección de llamada a la acción."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 9:</strong> Mockup 9 - Lo que dicen nuestros clientes - Landing Page.
  </figcaption>
</figure>


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup10.png"
       alt="Mockup 10 de la Landing Page: Vista de la navegación superior."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 10:</strong> Mockup 10 - Lo que dicen nuestros clientes - Landing Page.
  </figcaption>
</figure>


- En "Contacto" se presenta un formulario de contacto para que los usuarios puedan solicitar una demo.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup11.png"
       alt="Mockup 11 de la Landing Page: Vista de la sección de beneficios clave."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 11:</strong> Mockup 11 - Contacto - Landing Page.
  </figcaption>
</figure>



### 5.4. Applications UX/UI Design

#### 5.4.1. Applications Wireframes

Los wireframes de las aplicaciones web de OsitoPolar delinean la estructura y organización de las pantallas principales, especificando la ubicación de los elementos de la interfaz de usuario y la navegación. Estos esquemas visuales sirven como una guía precisa para el diseño final, asegurando una experiencia de usuario fluida e intuitiva. Los wireframes están enfocados en la funcionalidad y facilidad de uso, permitiendo que diseñadores y desarrolladores visualicen cómo los usuarios interactúan con la aplicación, optimizando la disposición de los elementos para crear una experiencia eficiente y atractiva.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/AlquilarEquipos-Clientes.png"
       alt="Wireframe: Interfaz de alquiler de equipos para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Wireframe - Alquilar Equipos (Clientes).
  </figcaption>
</figure>


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Contacto-Clientes.png"
       alt="Wireframe: Pantalla de contacto para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Wireframe - Contacto (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Contacto-Empresa.png"
       alt="Wireframe: Pantalla de contacto para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Wireframe - Contacto (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Control-Clientes.png"
       alt="Wireframe: Panel de control para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 4:</strong> Wireframe - Control (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/EstadoCuenta-Clientes.png"
       alt="Wireframe: Vista de estado de cuenta para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 5:</strong> Wireframe - Estado de Cuenta (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/EstadoCuenta-Empresa.png"
       alt="Wireframe: Vista de estado de cuenta para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 6:</strong> Wireframe - Estado de Cuenta (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Full%20Analiticas-Clientes.png"
       alt="Wireframe: Pantalla de analíticas completas para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 7:</strong> Wireframe - Analíticas Completas (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Inicio-Clientes.png"
       alt="Wireframe: Pantalla de inicio para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 8:</strong> Wireframe - Inicio (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Inicio-Empresa.png"
       alt="Wireframe: Pantalla de inicio para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 9:</strong> Wireframe - Inicio (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Inicio%20App.png"
       alt="Wireframe: Pantalla de inicio de la aplicación."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 10:</strong> Wireframe - Inicio de la Aplicación.
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Inicio%20Sesion%20-%20Clientes.png"
       alt="Wireframe: Pantalla de inicio de sesión para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 11:</strong> Wireframe - Inicio de Sesión (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Inicio%20Sesion%20-%20Empresa.png"
       alt="Wireframe: Pantalla de inicio de sesión para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 12:</strong> Wireframe - Inicio de Sesión (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/MiCuenta-Clientes.png"
       alt="Wireframe: Pantalla 'Mi Cuenta' para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 13:</strong> Wireframe - Mi Cuenta (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/MiCuenta-Empresa.png"
       alt="Wireframe: Pantalla 'Mi Cuenta' para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 14:</strong> Wireframe - Mi Cuenta (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/MisClientes%2CT%C3%A9cnicos-Empresa.png"
       alt="Wireframe: Gestión de clientes y técnicos para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 15:</strong> Wireframe - Mis Clientes y Técnicos (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/MisEquipos-Clientes.png"
       alt="Wireframe: Vista de 'Mis Equipos' para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 16:</strong> Wireframe - Mis Equipos (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/MisEquipos-Clientes-1.png"
       alt="Wireframe: Detalle 1 de 'Mis Equipos' para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 17:</strong> Wireframe - Mis Equipos (Clientes, Detalle 1).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/MisEquipos-Clientes-2.png"
       alt="Wireframe: Detalle 2 de 'Mis Equipos' para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 18:</strong> Wireframe - Mis Equipos (Clientes, Detalle 2).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/MisEquipos-Empresa.png"
       alt="Wireframe: Vista de 'Mis Equipos' para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 19:</strong> Wireframe - Mis Equipos (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Notificaciones-Clientes.png"
       alt="Wireframe: Pantalla de notificaciones para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 20:</strong> Wireframe - Notificaciones (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Notificaciones-Empresa.png"
       alt="Wireframe: Pantalla de notificaciones para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 21:</strong> Wireframe - Notificaciones (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Registro-Clientes.png"
       alt="Wireframe: Pantalla de registro para clientes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 22:</strong> Wireframe - Registro (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Registro-Empresa.png"
       alt="Wireframe: Pantalla de registro para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 23:</strong> Wireframe - Registro (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/Solicitudes-Empresa.png"
       alt="Wireframe: Pantalla de gestión de solicitudes para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 24:</strong> Wireframe - Solicitudes (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Apps%20Wireframes/%C3%93rdenesDeTrabajo-Empresa.png"
       alt="Wireframe: Pantalla de órdenes de trabajo para la empresa."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 25:</strong> Wireframe - Órdenes de Trabajo (Empresa).
  </figcaption>
</figure>


#### 5.4.2. Applications Wireflow Diagrams
En esta sección se presentan los Wireflows para cada objetivo del usuario, teniendo en cuenta los User Personas relevantes. Cada diagrama ilustra el flujo de interacción del usuario y cómo las acciones realizadas afectan las pantallas dentro de la aplicación.


#### **User Goal 1**: 
Como dueño de un negocio que utiliza equipos de refrigeración quiero estar pendiente del estado de cada equipo registrado.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/taskflow1.png"
       alt="Diagrama de Taskflow 1: Flujo de tareas para una acción específica del usuario."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Taskflow 1.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/wireflow1.png"
       alt="Diagrama de Wireflow 1: Combinación de wireframes y flujo de interacción del usuario."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Wireflow 1.
  </figcaption>
</figure>


#### **User Goal 2**:
Como dueño de un negocio que utiliza equipos de refrigeración quiero lograr administrar los nuevos equipos que registre.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/taskflow2.png"
       alt="Diagrama de Taskflow 2: Flujo de tareas para un proceso de usuario."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Taskflow 2.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/wireflow2.png"
       alt="Diagrama de Wireflow 2: Representación visual del flujo de usuario entre pantallas."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 4:</strong> Wireflow 2.
  </figcaption>
</figure>


#### **User Goal 3**:
Como dueño de un negocio que utiliza equipos de refrigeración quiero revisar las estadísticas completas de mis equipos.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/taskflow3.png"
       alt="Diagrama de Taskflow 3: Secuencia de tareas para una interacción compleja."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 5:</strong> Taskflow 3.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/wireflow3.png"
       alt="Diagrama de Wireflow 3: Detalle del flujo de usuario con elementos de la interfaz."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 6:</strong> Wireflow 3.
  </figcaption>
</figure>


#### **User Goal 4**:
Como dueño de un negocio que utiliza equipos de refrigeración quiero pedir nuevos equipos a un proveedor de manera sencilla.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/taskflow4.png"
       alt="Diagrama de Taskflow 4: Flujo de tareas para un caso de uso específico."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 7:</strong> Taskflow 4.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/wireflow4.png"
       alt="Diagrama de Wireflow 4: Visión general del flujo de navegación y pantallas."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 8:</strong> Wireflow 4.
  </figcaption>
</figure>


#### **User Goal 5**:
Como proveedor de equipos de refrigeración quiero estar pendiente de los ordenes de pedios de mis clientes.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/taskflow5.png"
       alt="Diagrama de Taskflow 5: Flujo de tareas para la interacción del usuario con el sistema."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 9:</strong> Taskflow 5.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/wireflows/wireflow5.png"
       alt="Diagrama de Wireflow 5: Resumen visual del flujo de interacción y las pantallas clave."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 10:</strong> Wireflow 5.
  </figcaption>
</figure>


#### 5.4.3. Applications Mock-ups
En esta sección se presentan y detallan los mock-ups de las aplicaciones de OsitoPolar. Se resalta la aplicación de los principios de diseño, la arquitectura de la información, el diseño inclusivo y el Design System implementado en los productos digitales. Cada mock-up muestra cómo estos conceptos se integran en la interfaz de usuario. A continuación, se mostrarán las maquetas de la aplicación web, que representan visualmente cómo se verá y funcionará la plataforma OsitoPolar. Estas maquetas son fundamentales para comunicar el diseño a los desarrolladores y clientes, asegurando que la experiencia del usuario se alinee con la visión del proyecto.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Inicio%20App.png"
       alt="Mockup: Pantalla de inicio general de la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Mockup - Inicio General de la App.
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Registro-Clientes.png"
       alt="Mockup: Pantalla de registro para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Mockup - Registro (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Inicio%20Sesion%20-%20Clientes.png"
       alt="Mockup: Pantalla de inicio de sesión para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Mockup - Inicio de Sesión (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Inicio-Clientes.png"
       alt="Mockup: Pantalla de inicio del panel de clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 4:</strong> Mockup - Inicio (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/MisEquipos-Clientes.png"
       alt="Mockup: Vista de 'Mis Equipos' para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 5:</strong> Mockup - Mis Equipos (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/MisEquipos-Clientes-1.png"
       alt="Mockup: Vista detallada 1 de 'Mis Equipos' para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 6:</strong> Mockup - Mis Equipos (Clientes, Detalle 1).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/MisEquipos-Clientes-2.png"
       alt="Mockup: Vista detallada 2 de 'Mis Equipos' para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 7:</strong> Mockup - Mis Equipos (Clientes, Detalle 2).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/AlquilarEquipos-Clientes.png"
       alt="Mockup: Proceso de alquiler de equipos para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 8:</strong> Mockup - Alquilar Equipos (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Contacto-Clientes.png"
       alt="Mockup: Pantalla de contacto y soporte para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 9:</strong> Mockup - Contacto (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Notificaciones-Clientes.png"
       alt="Mockup: Centro de notificaciones para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 10:</strong> Mockup - Notificaciones (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Control-Clientes.png"
       alt="Mockup: Panel de control o vista de actividad para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 11:</strong> Mockup - Control (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/EstadoCuenta-Clientes.png"
       alt="Mockup: Vista de estado de cuenta y facturación para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 12:</strong> Mockup - Estado de Cuenta (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/MiCuenta-Clientes.png"
       alt="Mockup: Configuración de perfil y cuenta para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 13:</strong> Mockup - Mi Cuenta (Clientes).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Full%20Analiticas-Clientes.png"
       alt="Mockup: Panel de analíticas completas para clientes en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 14:</strong> Mockup - Analíticas Completas (Clientes).
  </figcaption>
</figure>


- **Mockups Empresa:**

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Inicio%20Sesion%20-%20Empresa.png"
       alt="Mockup: Pantalla de inicio de sesión para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 15:</strong> Mockup - Inicio de Sesión (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Registro-Empresa.png"
       alt="Mockup: Pantalla de registro para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 16:</strong> Mockup - Registro (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Inicio-Empresa.png"
       alt="Mockup: Pantalla de inicio del panel de la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 17:</strong> Mockup - Inicio (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Contacto-Empresa.png"
       alt="Mockup: Pantalla de contacto y soporte para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 18:</strong> Mockup - Contacto (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/EstadoCuenta-Empresa.png"
       alt="Mockup: Vista de estado de cuenta y facturación para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 19:</strong> Mockup - Estado de Cuenta (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/MiCuenta-Empresa.png"
       alt="Mockup: Configuración de perfil y cuenta para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 20:</strong> Mockup - Mi Cuenta (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/MisClientes%2CT%C3%A9cnicos-Empresa.png"
       alt="Mockup: Gestión de clientes y técnicos para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 21:</strong> Mockup - Mis Clientes y Técnicos (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/MisEquipos-Empresa.png"
       alt="Mockup: Vista de 'Mis Equipos' para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 22:</strong> Mockup - Mis Equipos (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Notificaciones-Empresa.png"
       alt="Mockup: Centro de notificaciones para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 23:</strong> Mockup - Notificaciones (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/Solicitudes-Empresa.png"
       alt="Mockup: Gestión de solicitudes entrantes para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 24:</strong> Mockup - Solicitudes (Empresa).
  </figcaption>
</figure>

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Web%20Applications%20Mock-ups/%C3%93rdenesDeTrabajo-Empresa.png"
       alt="Mockup: Gestión de órdenes de trabajo para la empresa en la aplicación web."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 25:</strong> Mockup - Órdenes de Trabajo (Empresa).
  </figcaption>
</figure>


Link de los mockups: https://shorturl.at/jMDBY

#### 5.4.4. Applications User Flow Diagrams
### User Goal 1: 
- Como dueño de un negocio que utiliza equipos de refrigeración quiero estar pendiente del estado de cada equipo registrado.
![userflow1.png]( assets/chapter04/userflows/userflow1.png)

### User Goal 2:
- Como dueño de un negocio que utiliza equipos de refrigeración quiero revisar las estadisticas completas de mis equipos.
  ![userflow2.png]( assets/chapter04/userflows/userflow2.png)

### User Goal 3:
- Como dueño de un negocio que utiliza equipos de refrigeración quiero lograr administrar los nuevos equipos que registre.
  ![userflow3.png]( assets/chapter04/userflows/userflow3.png)



### 5.5. Applications Prototyping
A continuación se presenta el prototipo de la aplicación web de OsitoPolar, el cual permite a los usuarios interactuar con la interfaz y explorar las diversas secciones de la plataforma. Este prototipo incluye las funcionalidades clave y características de la aplicación, proporcionando una vista preliminar de la experiencia del usuario. Además, facilita la evaluación y prueba de la interfaz antes de su implementación final, asegurando que el diseño sea intuitivo y eficiente.
Link del prototipo: https://shorturl.at/oIUJN

### 5.6. IoT Device Design

> **Falta:** documentar el diseño del dispositivo IoT físico, incluyendo componentes electrónicos, sensores, actuadores si aplica, diagrama de conexión, flujo de datos Embedded Application -> Edge API -> Cloud API y evidencias del prototipo físico.

### 5.7. Domain-Driven Software Architecture
En esta sección se presenta la arquitectura de software basada en el dominio para OsitoPolar. Se detallan los diferentes diagramas que ilustran la estructura y organización del sistema, así como los componentes clave que lo integran, mostrando cómo se interconectan para proporcionar una solución eficiente y escalable.

#### 5.7.1. Software Architecture Context Diagram
Este diagrama muestra cómo interactúan los usuarios (Clientes y Empresas Proveedoras) con OsitoPolar. Los usuarios usan la plataforma para gestionar y monitorear equipos de refrigeración. Además, OsitoPolar se conecta con los servicios de correo para enviar notificaciones y con el servicio de pago para procesar transacciones.

![System Context Diagram](assets/chapter04/DSL/Contexto-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Contexto-dark-key.png)

#### 5.7.2. Software Architecture Container Diagrams
Este diagrama ilustra los diferentes contenedores dentro de OsitoPolar y cómo interactúan entre sí. Los contenedores representan las diferentes capas y servicios que componen la plataforma, como la interfaz de usuario (webapp), la API y la base de datos.

![Container Diagram](assets/chapter04/DSL/Contenedores-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Contenedores-dark-key.png)

#### 5.7.3. Software Architecture Components Diagrams

**IAM Bounded Context**

Este diagrama representa los componentes encargados de la gestión de identidad y acceso, incluyendo autenticación, autorización y administración de usuarios.

![IAM Components Diagram](assets/chapter04/DSL/IAM_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/IAM_Components-dark-key.png)

**Profiles Bounded Context**

Este diagrama describe los componentes que gestionan los perfiles de usuarios y empresas dentro de la plataforma OsitoPolar.

![Profiles Components Diagram](assets/chapter04/DSL/Profiles_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Profiles_Components-dark-key.png)

**Equipment Management Bounded Context**

Este diagrama representa los componentes encargados de la gestión de equipos de refrigeración. Los usuarios pueden registrar equipos, monitorearlos en tiempo real y consultar su estado.

![Equipment Components Diagram](assets/chapter04/DSL/Equipment_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Equipment_Components-dark-key.png)

**IoT Monitoring Bounded Context**

Este diagrama describe los componentes responsables del monitoreo IoT de los equipos, incluyendo la recopilación y procesamiento de datos de sensores en tiempo real.

![IoT Monitoring Components Diagram](assets/chapter04/DSL/IoTMonitoring_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/IoTMonitoring_Components-dark-key.png)

**Edge API Bounded Context**

Este diagrama ilustra los componentes del API perimetral que actúa como punto de entrada para los dispositivos IoT y la comunicación con los servicios de la plataforma.

![Edge API Components Diagram](assets/chapter04/DSL/EdgeAPI_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/EdgeAPI_Components-dark-key.png)

**Service Request Bounded Context**

Este diagrama describe los componentes encargados de gestionar las solicitudes de servicio técnico, desde su creación hasta su resolución.

![Service Request Components Diagram](assets/chapter04/DSL/ServiceRequest_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/ServiceRequest_Components-dark-key.png)

**Work Order Bounded Context**

Este diagrama se centra en la gestión de órdenes de trabajo, mostrando los componentes involucrados en el ciclo de vida completo de una orden de trabajo técnico.

![Work Order Components Diagram](assets/chapter04/DSL/WorkOrder_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/WorkOrder_Components-dark-key.png)

**Subscriptions Bounded Context**

Este diagrama representa los componentes que gestionan los planes de suscripción, facturación y acceso diferenciado a funcionalidades según el plan contratado.

![Subscriptions Components Diagram](assets/chapter04/DSL/Subscriptions_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Subscriptions_Components-dark-key.png)

**Notifications Bounded Context**

Este diagrama describe los componentes que gestionan el envío de notificaciones, alertas y comunicaciones hacia los usuarios sobre el estado de equipos y eventos relevantes.

![Notifications Components Diagram](assets/chapter04/DSL/Notifications_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Notifications_Components-dark-key.png)

**Analytics Bounded Context**

Este diagrama ilustra los componentes encargados del procesamiento y visualización de datos analíticos, métricas de rendimiento y reportes de los equipos monitoreados.

![Analytics Components Diagram](assets/chapter04/DSL/Analytics_Components-dark.png)
*Leyenda:*
![Key](assets/chapter04/DSL/Analytics_Components-dark-key.png)

### 5.8. Software Object-Oriented Design
En esta sección se presenta el diseño de software orientado a objetos para OsitoPolar. Se incluyen diagramas de clases y un diccionario de clases que detallan la estructura y los atributos de las principales entidades del sistema, ofreciendo una visión clara de cómo se organizan y gestionan los componentes clave dentro de la plataforma.

#### 5.8.1. Class Diagrams

El diagrama de clases proporciona una representación visual de las clases del sistema, sus atributos y las relaciones entre ellas.

![Class-UML.png]( assets/chapter04/Class-UML.png)

#### 5.8.2. Class Dictionary

## Clase: Solicitud
| Nº | Nombre de atributo | Descripción                                              | Tipo de dato      |
|----|--------------------|----------------------------------------------------------|-------------------|
| 1  | name_equipo        | Almacena el nombre del equipo solicitado.                | Equipo            |
| 2  | name_usuario       | Almacena el nombre del usuario que realiza la solicitud. | Usuario           |
| 3  | orden              | Almacena el número de orden de la solicitud.             | unsigned long int |
| 4  | description        | Almacena la descripción de la solicitud.                 | varchar           |
| 5  | time               | Almacena el tiempo estimado o requerido.                 | float             |
| 6  | status             | Almacena el estado de la solicitud.                      | char              |

## Clase: Equipo
| Nº | Nombre de atributo | Descripción                             | Tipo de dato      |
|----|--------------------|-----------------------------------------|-------------------|
| 1  | name               | Almacena el nombre del equipo.          | string            |
| 2  | cost               | Almacena el costo del equipo.           | float             |
| 3  | details_tecnicos   | Almacena detalles técnicos del equipo.  | varchar           |
| 4  | serie              | Almacena el número de serie del equipo. | unsigned long int |
| 5  | code               | Almacena el código del equipo.          | unsigned long int |
| 6  | status             | Almacena el estado del equipo.          | char              |
| 7  | notes              | Almacena notas adicionales del equipo.  | varchar           |

## Clase: Cliente
| Nº | Nombre de atributo | Descripción                                | Tipo de dato |
|----|--------------------|--------------------------------------------|--------------|
| 1  | name               | Almacena el nombre del cliente.            | string       |
| 2  | email              | Almacena el correo del cliente.            | string       |
| 3  | password           | Almacena la contraseña del cliente.        | string       |
| 4  | username           | Almacena el nombre de usuario del cliente. | string       |
| 5  | phone              | Almacena el teléfono del cliente.          | string       |
| 6  | user_type          | Almacena el tipo de usuario.               | char         |

## Clase: Company
| Nº | Nombre de atributo | Descripción                                     | Tipo de dato |
|----|--------------------|-------------------------------------------------|--------------|
| 1  | name               | Almacena el nombre de la empresa.               | string       |
| 2  | email              | Almacena el correo electrónico de la empresa.   | string       |
| 3  | password           | Almacena la contraseña de la empresa.           | string       |
| 4  | username           | Almacena el nombre de usuario de la empresa.    | string       |
| 5  | plan               | Almacena el tipo de plan que posee la empresa.  | char         |
| 6  | phone              | Almacena el teléfono de contacto de la empresa. | string       |
| 7  | business_type      | Almacena el tipo de negocio de la empresa.      | char         |
| 8  | location           | Almacena la ubicación física de la empresa.     | string       |

##  Clase: Cuenta
| Nº | Nombre de atributo | Descripción                                         | Tipo de dato |
|----|--------------------|-----------------------------------------------------|--------------|
| 1  | name (company)     | Almacena el nombre de la empresa asociada.          | Company      |
| 2  | name (usuario)     | Almacena el nombre del usuario asociado.            | Usuario      |
| 3  | cost               | Almacena el costo del equipo vinculado a la cuenta. | Equipo       |
| 4  | status             | Almacena el estado de la cuenta.                    | char         |

##  Clase: Mantenimiento
| Nº | Nombre de atributo | Descripción                                     | Tipo de dato |
|----|--------------------|-------------------------------------------------|--------------|
| 1  | name               | Almacena el nombre del equipo en mantenimiento. | Equipo       |
| 2  | status             | Almacena el estado del mantenimiento.           | char         |

##  Clase: Notificación
| Nº | Nombre de atributo | Descripción                                                  | Tipo de dato |
|----|--------------------|--------------------------------------------------------------|--------------|
| 1  | name               | Almacena el nombre de la notificación.                       | varchar      |
| 2  | description        | Almacena la descripción de la notificación.                  | varchar      |
| 3  | name_company       | Almacena el nombre de la empresa asociada a la notificación. | Company      |
| 4  | name_cliente       | Almacena el nombre del cliente destinatario.                 | Cliente      |
| 5  | status             | Indica si la notificación ha sido leída o procesada.         | bool         |

### 5.9. Database Design

Esta sección presenta la estructura lógica del sistema desde el punto de vista de almacenamiento y organización de los datos. Se describen las entidades principales del sistema, sus atributos, tipos de datos y relaciones entre ellas. El modelo de base de datos ha sido diseñado para garantizar integridad, consistencia y eficiencia en el acceso a la información.



#### 5.9.1. Database Diagram

El diagrama de base de datos ilustra gráficamente cómo se relacionan las tablas dentro del sistema, incluyendo sus claves primarias, claves foráneas y los tipos de relaciones existentes (uno a uno, uno a muchos o muchos a muchos).

![diagram-class.png]( assets/chapter04/diagram-class.png)

<div style="page-break-after: always"></div>

## Capítulo VI: Product Implementation, Validation & Deployment 

### 6.1. Software Configuration Management
#### 6.1.1. Software Development Environment Configuration

### Project Management

Para la administración del proyecto se recurrió al uso de herramientas de comunicación y control de versiones. Se creó una organización en GitHub para centralizar la gestión del código fuente y su versionado. En cuanto a la comunicación interna y las reuniones del equipo, se utilizó Discord.

**Organización del trabajo:** Github

**Reuniones:** Discord

**Comunicación:** Whatsapp

**Planificación y asignación de tareas:** Trello

**Enlaces**

- Github: https://github.com/
- Discord: https://discord.com/
- Trello: https://trello.com/


### Requirement Management

Para esta fase, se implementaron soluciones personalizadas que facilitaron la recolección, organización y priorización de los requisitos del proyecto.
Se utilizó Trello como una herramienta visual para gestionar tareas mediante tableros personalizados.
Se utilizó UXPressia para poder desarrollar los user personas, empathy maps, journey maps y lean UX canvas.
Se utilizó Miro para el desarrollo de los As-Is y To-Be Scenarios.


**Enlaces**

- Trello: https://trello.com/
- UXPressia: https://uxpressia.com/
- Miro: https://miro.com/es/


### Product UX/UI Design
En el diseño de la experiencia e interfaz de usuario, el equipo utilizó Figma para la creación de wireframes, mockups y prototipos interactivos, lo que permitió validar la propuesta de diseño antes de la implementación.

**Enlaces**
- Figma: https://www.figma.com/

### Software Development
Para el desarrollo de la Landing Page se usaron los lenguajes HTML, CSS y JavaScript en Visual Studio Code. La elaboración del informe se realizó en archivos .md en IDEs como IntelliJ IDEA y Rider (cada miembro del equipo trabajó en alguna de estas herramientas).
Para descargar, instalar y actualizar fácilmente estas IDEs utilizamos la aplicación de gestión JetBrains ToolBox.

**Enlaces**
- JetBrains ToolBox: https://www.jetbrains.com/toolbox-app/
- Visual Studio Code: https://code.visualstudio.com/


### Software Documentation
Para el control de versiones y la colaboración en el desarrollo del informe, se utilizó GitHub siguiendo la estrategia de trabajo GitHub Flow. Esta metodología permitió una gestión eficiente y ordenada del proyecto mediante el uso de ramas específicas para cada funcionalidad o corrección, lo que facilitó el trabajo colaborativo. Todo el contenido del proyecto fue centralizado y almacenado en un repositorio dentro de una organización creada en GitHub.
Para la documentación técnica del proyecto se optó por el uso de archivos en formato Markdown, debido a su simplicidad, legibilidad y excelente compatibilidad con GitHub.

**Enlaces**
- GitHub: https://github.com/

### Software Deployment
Para el despliegue de la Landing Page se utilizó GitHub Pages, una herramienta perfecta para publicar sitios web estáticos.

**Enlaces**
- GithubPages: https://pages.github.com/



#### 6.1.2. Source Code Management

Modelo de ramas Git Flow: main: rama principal donde siempre está el código estable y listo para producción. develop: rama de desarrollo donde se integran todas las nuevas funcionalidades antes de pasar a producción. feature/: ramas para trabajar nuevas funcionalidades. release/: ramas temporales para preparar una nueva versión estable. hotfix/: ramas para corregir errores en producción.

Versionado semántico (Semantic Versioning): Se aplicará el versionado semántico (Semantic Versioning 2.0.0), siguiendo el esquema: MAJOR.MINOR.PATCH.
1.0.0 → versión estable inicial

1.1.0 → agregaste nuevas funcionalidades

1.1.1 → arreglos de bugs

Convención de mensajes de commits El equipo seguirá la convención de mensajes de commits definida en “Conventional Commits”.
Ejemplos de mensajes:

- feat: agregar nuevo sistema de login
- fix: corregir validación en formulario de registro
- docs: actualizar README con instrucciones de despliegue

Nomenclatura de numeración de las versiones: Major changes: Cuando el código o versión nueva del proyecto a implementar presenta cambios significativos con la versión anterior, estos cambios llegan a ser incompatibles con la versión anterior. Minor changes: Cuando el código o versión nueva del proyecto a implementar presenta cambios con respecto a alguna característica Patch: Cuando se solucionan bugs menores.


**Repositorio de Github:**
- Enlace para acceder a la [organización en Github](https://github.com/iot-proyectos)
- Enlace para acceder al repositorio de la [Landing Page](https://github.com/iot-proyectos/LandingPage)
- Enlace para acceder al repositorio del [Informe](https://github.com/iot-proyectos/Report)

**Flujo de trabajo de GitFlow**
El flujo de trabajo se basará en un modelo de ramas Git Flow, el cuál se basa en la creación de ramas específicas para cada funcionalidad o corrección de errores. El modelo de "A succesful Git branching model"

--Insertar imagen

**Estructura de branches (Ramas):**


1. **Master branch (Rama principal):** Es la rama principal del proyecto, donde se almacena el código estable y listo para producción. Solo se integrarán cambios que hayan sido probados y validados previamente en las ramas de desarrollo y funcionalidad.

2. **Develop Branch (Rama de Desarrollo):** Esta rama actúa como un espacio de integración para el trabajo en equipo, permitiendo pruebas y ajustes de las nuevas funcionalidades antes de fusionarlas con la rama principal. Garantiza que el código sea funcional y estable.

3. **Feature branch (Ramas de funcionalidad):** Cada nueva funcionalidad o tarea específica se desarrollará en su propia rama. Una vez completada y probada, se integrará en la rama de desarrollo. Las ramas de funcionalidad seguirán un esquema de nombres descriptivos, como por ejemplo: `feature/chapter-01`.

#### 6.1.3. Source Code Style Guide & Conventions

El equipo adoptará nomenclatura en inglés para todas las variables, funciones, clases y archivos del proyecto, con el objetivo de mantener flexibilidad, escalabilidad y coherencia en el desarrollo. HTML / CSS Se sigue el Google HTML/CSS Style Guide.

Las clases CSS estarán en kebab-case (.main-header, .card-title).

Se utilizarán etiquetas semánticas

- &lt;header&gt;
- &lt;section&gt;
- &lt;article&gt;

Identificadores claros y descriptivos para accesibilidad y mantenimiento.

Se usó diferentes etiquetas para conformar la estructura del Landing Page del producto:

- header: Define todo el contenido introductorio de la página web.

- nav: Define las secciones de la página que estarán dedicadas a la navegación en la página.

- div: Esta etiqueta permite la separación de diferentes objetos dentro de nuestra página, esto nos permitió poder aplicar hojas de estilo específicas para cada parte de los objetos.

- img: Esta etiqueta permite la inserción de imágenes en la página web, se usó en diversas ocasiones dentro de la página.

- ul: Esta etiqueta sirve para definir una lista desordenada, mayormente se usó para la elaboración del menú interactivo de la página.

- li: Sirve para definir los elementos de las listas que se implementaron en la página, más especifico en la barra de búsqueda y el blog.

- a: Se usó para definir hipervínculos para mover a los usuarios a través de las diferentes secciones de la página.

- p: Definen los párrafos de texto, separándolos del resto de contenido.

- button: Declaran un botón interactivo modificable que permite a los usuarios realizar una acción en específico.

- h1 - h4: Definen los diferentes títulos y subtítulos de la página siendo h1 el mayor nivel y h4 el más bajo.


#### 6.1.4. Software Deployment Configuration


### Landing page deployment:
Para desplegar la landing page, es necesario cumplir con ciertos requisitos previos, como contar con una cuenta personal, una organización y un repositorio donde se alojarán los archivos. Una vez cumplidos estos requisitos, se pueden seguir los pasos detallados a continuación para realizar el despliegue:

1. Verificar que los archivos principales se encuentren en la raíz (root) del repositorio.
2. Asegurarse de que los archivos sigan las siguientes convenciones de nombres: "index.html" para la página principal, "styles.css" para los estilos, "script.js" para los scripts principales, "languages.js" para gestionar los textos en diferentes idiomas (español e inglés), y una carpeta llamada "assets/images" para las imágenes.
3. Subir los archivos al repositorio mediante un commit.
4. Acceder a la sección Settings > Pages y seleccionar el branch correspondiente, en este caso, "main".
5. Configurar la carpeta raíz (root) como la fuente de la página.
6. Esperar a que GitHub realice las verificaciones necesarias. Una vez finalizado el proceso, se generará un enlace que permitirá acceder a la landing page desplegada.

Adicionalmente, se implementó un archivo "languages.js" que contiene los textos en español e inglés. Este archivo es consumido por el script "main.js", el cual permite realizar el cambio de idioma dinámicamente en la landing page.ations Implementation

### Github Pages:
![Github-Pages.png]( assets/chapter-05/Github-Pages.png)

La URL que nos entrega Github Pages para acceder a la landing page es la siguiente: https://iot-proyectos.github.io/LandingPage/


### 6.2. Landing Page, Services & Applications Implementation.

![Landing-Page.png]( assets/chapter-05/Landing-Page.png)

En el siguiente enlace se estará mostrando la landing page de la startup:
[Video demostrativo de la landing page](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c111_upc_edu_pe/IQAeOr9bSx-2T4NJ5MMy6oFYAV1TUJryHsIL4ZEcVvphgsU?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7A15cz)

En la sección siguiente se detallará el proceso de implementación, documentación y despliegue del Landing.

#### 6.2.1. Sprint 1
##### 6.2.1.1. Sprint Planning 1
<table>
<tr>
    <th colspan="5">Sprint 1</th>
    <th colspan="9">Sprint 1</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2026-05-10</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">9:45 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Cacho Seminario, Diego Alonso</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Osito Polar Team</td>
</tr>
<tr>
    <td colspan="5">Sprint  1 Review Summary</td>
    <td colspan="8">Esta sección se dedicó a mejorar el codigo de la Landing page para poder usarse mejor y tener una estructura clara y desplegamos la primera versión del Web App.</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Retrospective Summary</td>
    <td colspan="8">En esta sección tuvimos varios aciertos ya que hubieron ideas para integrar lo de los idiomas bastante convicentes pero nos quedamos con una en especifica, poniendo a prueba nuestra resolución de problemas.</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Goal</td>
       <td colspan="8">Nuestro enfoque está en implementar la landing page de OsitoPolar, asegurando su adaptabilidad a diferentes dispositivos, coherencia visual y funcionalidad multilingüe. Creemos que esto ofrece una experiencia de navegación más clara, atractiva y accesible a los usuarios potenciales de nuestra solución. Esto se confirmará cuando los usuarios puedan cambiar el idioma fácilmente desde la interfaz, navegar la página sin errores visuales desde cualquier dispositivo, y se valide que imágenes y textos estén correctamente integrados y espaciados. Además de realizar y desplegar la primera versión de la Web App. </td>

</tr>
<tr>
    <td colspan="5">Sprint 1 Velocity</td>
    <td colspan="8">15</td>
<tr>
    <td colspan="5">Sum of Story Points</td>
    <td colspan="8">14</td>
</tr>
</table>


##### 6.2.1.2. Aspect Leaders and Collaborators

Durante este primer Sprint, el equipo se enfocó principalmente en el desarrollo, la mejora estructural y visual de la Landing Page de OsitoPolar, asegurando su visualización en distintos dispositivos (diseño responsive), la integración armoniosa de imágenes y textos, y la implementación de un cambio de idioma dinámico mediante un botón.
Con el fin de organizar de manera más eficiente el trabajo colaborativo, se ha elaborado la matriz de Liderazgo y Colaboración (LACX). Esta matriz asigna responsabilidades específicas a cada miembro del equipo en relación con los aspectos clave del Sprint.
<table>
  <tr>
    <td colspan="2"><strong>Team Member (Last Name, First Name)</strong></td>
    <td><strong>GitHub Username</strong></td>
    <td><strong>Diseño visual y maquetación web (Landing Page)<br>Leader (L) / Collaborator (C)</strong></td>
    <td><strong>Implementación técnica del cambio de idioma (Multilenguaje funcional)<br>Leader (L) / Collaborator (C)</strong></td>
    <td><strong>Responsividad y pruebas en distintos dispositivos<br>Leader (L) / Collaborator (C)</strong></td>
  </tr>
  <tr>
    <td colspan="2">Cacho Seminario, Diego Alonso </td>
    <td>Memesitos</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo </td>
    <td>Necxuz18</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
  </tr>
  <tr>
    <td colspan="2"> Medina Cruzado, Raúl Adrian </td>
    <td>imisterdg</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td colspan="2">Inga Orihuela, Christian Fabrizio
</td>
    <td>Christian1905</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td colspan="2">Mora Blas, Diego Alonzo </td>
    <td>diegoalonzomora</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
</table>


##### 6.2.1.3. Sprint Backlog 1

El objetivo principal de este Sprint es elaborar la Landing Page de OsitoPolar, comunicando claramente que la plataforma permite monitorear la cadena de frio con dispositivos IoT, visualizar temperatura y humedad en tiempo real, recibir alertas ante desconexion o valores fuera de rango y conocer los planes disponibles para negocios con infraestructura refrigerada. La plataforma elegida para el control de tareas fue Trello.

![Trello-SprintBacklog1.png]( assets/chapter-05/Trello-SprintBacklog1.png)

Enlace: https://trello.com/b/xAOjqyPz/inteligenciaartesanal-ositopolar

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 1</th>
</tr>
<tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
</tr>
<tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1">Estimation (Hours)</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status (To do/ In-Process/ To-Review/ Done)</td>
</tr>
<tr>
    <td colspan="1">US-23</td>
    <td colspan="2">Entender la propuesta de monitoreo de cadena de frio</td>
    <td colspan="1">UT-01</td>
    <td colspan="2">Crear seccion Hero enfocada en IoT</td>
    <td colspan="3">Presentar a OsitoPolar como una plataforma web para vigilar temperatura, humedad y estado de conexion de equipos refrigerados.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Medina Cruzado, Raul Adrian</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-23</td>
    <td colspan="2">Entender la propuesta de monitoreo de cadena de frio</td>
    <td colspan="1">UT-02</td>
    <td colspan="2">Aplicar estilos visuales del Hero</td>
    <td colspan="3">Aplicar estilos para comunicar tecnologia, refrigeracion, monitoreo continuo y confianza operativa.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Cacho Seminario, Diego Alonso</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-23</td>
    <td colspan="2">Entender la propuesta de monitoreo de cadena de frio</td>
    <td colspan="1">UT-03</td>
    <td colspan="2">Agregar interacciones iniciales</td>
    <td colspan="3">Agregar desplazamiento, botones y comportamiento basico para dirigir al usuario a planes, beneficios y solicitud de demo.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Medina Cruzado, Raul Adrian</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-24</td>
    <td colspan="2">Identificar beneficios por tipo de negocio refrigerado</td>
    <td colspan="1">UT-04</td>
    <td colspan="2">Crear seccion Beneficios</td>
    <td colspan="3">Mostrar beneficios para negocios con refrigeradores, congeladores, camaras frias y almacenes refrigerados.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-24</td>
    <td colspan="2">Identificar beneficios por tipo de negocio refrigerado</td>
    <td colspan="1">UT-05</td>
    <td colspan="2">Estilizar tarjetas de beneficios</td>
    <td colspan="3">Aplicar estilos a beneficios como prevencion de perdidas, visibilidad en tiempo real y respuesta temprana ante alertas.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Inga Orihuela, Christian Fabrizio</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-24</td>
    <td colspan="2">Identificar beneficios por tipo de negocio refrigerado</td>
    <td colspan="1">UT-06</td>
    <td colspan="2">Agregar interacciones en beneficios</td>
    <td colspan="3">Agregar comportamiento visual para destacar beneficios de monitoreo, trazabilidad y alertas por fuera de rango.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Medina Cruzado, Raul Adrian</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-25</td>
    <td colspan="2">Comprender funcionalidades IoT principales</td>
    <td colspan="1">UT-07</td>
    <td colspan="2">Crear seccion Funcionalidades</td>
    <td colspan="3">Presentar funcionalidades: registro de dispositivos, dashboard, temperatura/humedad, alertas, historial y planos interactivos.</td>
    <td colspan="1">1</td>
    <td colspan="2">Mora Blas, Diego Alonzo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-25</td>
    <td colspan="2">Comprender funcionalidades IoT principales</td>
    <td colspan="1">UT-08</td>
    <td colspan="2">Aplicar estilos a funcionalidades</td>
    <td colspan="3">Ordenar visualmente las funciones alrededor del monitoreo de cadena de frio y la gestion de dispositivos IoT.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Cacho Seminario, Diego Alonso</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-25</td>
    <td colspan="2">Comprender funcionalidades IoT principales</td>
    <td colspan="1">UT-09</td>
    <td colspan="2">Agregar interacciones a funcionalidades</td>
    <td colspan="3">Agregar efectos y validaciones visuales para explicar los flujos de monitoreo, alerta y visualizacion historica.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Medina Cruzado, Raul Adrian</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-26</td>
    <td colspan="2">Solicitar una demo de monitoreo IoT</td>
    <td colspan="1">UT-10</td>
    <td colspan="2">Crear seccion Solicitar Demo</td>
    <td colspan="3">Permitir que negocios interesados pidan una demostracion de monitoreo de equipos refrigerados.</td>
    <td colspan="1">1</td>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-26</td>
    <td colspan="2">Solicitar una demo de monitoreo IoT</td>
    <td colspan="1">UT-11</td>
    <td colspan="2">Estilizar formulario de demo</td>
    <td colspan="3">Aplicar estilos al formulario y orientar los campos a empresas con equipos o instalaciones refrigeradas.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Inga Orihuela, Christian Fabrizio</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-26</td>
    <td colspan="2">Solicitar una demo de monitoreo IoT</td>
    <td colspan="1">UT-12</td>
    <td colspan="2">Validar interacciones del formulario</td>
    <td colspan="3">Agregar validaciones basicas para los datos del negocio, contacto y tipo de infraestructura refrigerada.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Medina Cruzado, Raul Adrian</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-27</td>
    <td colspan="2">Conocer mision y vision de OsitoPolar</td>
    <td colspan="1">UT-13</td>
    <td colspan="2">Crear seccion Nosotros</td>
    <td colspan="3">Explicar la vision del equipo sobre proteccion de cadena de frio mediante monitoreo IoT accesible.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Mora Blas, Diego Alonzo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-28</td>
    <td colspan="2">Consultar planes de uso</td>
    <td colspan="1">UT-14</td>
    <td colspan="2">Crear seccion Planes</td>
    <td colspan="3">Presentar planes de uso, incluyendo una opcion empresarial con planos interactivos para ubicar dispositivos.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Cacho Seminario, Diego Alonso</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-00</td>
    <td colspan="2">-</td>
    <td colspan="1">NT-15</td>
    <td colspan="2">Implementar cambio de idioma</td>
    <td colspan="3">Implementar cambio de idioma para comunicar la propuesta de monitoreo IoT en espanol e ingles.</td>
    <td colspan="1">2</td>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-00</td>
    <td colspan="2">-</td>
    <td colspan="1">NT-16</td>
    <td colspan="2">Agregar imagenes de cadena de frio</td>
    <td colspan="3">Agregar imagenes relacionadas con sensores, refrigeracion, dashboard y monitoreo de condiciones ambientales.</td>
    <td colspan="1">0.5</td>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo</td>
    <td colspan="1">Done</td>
</tr>

</table>
##### 6.2.1.4. Development Evidence for Sprint Review

En este primer Sprint hemos realizado la implementación de nuestra Landing Page, donde todo el equipo ha aportado en varias tareas. En la siguiente tabla se muestran los commits realizados.

<table>
    <tr>
        <th colspan="2">Repository</th>
        <th colspan="2">Branch</th>
        <th colspan="2">Commit Id</th>
        <th colspan="2">Commit Message</th>
        <th colspan="2">Commit Message Body</th>
        <th colspan="2">Commited on (Date)</th>
    </tr>
        <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">9caef73</td>
        <td colspan="2">chore: added html file</td>
        <td colspan="2">added html file</td>
        <td colspan="2">25/04/2026</td>
    </tr>
        <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">ae1fd12</td>
        <td colspan="2">feat: added header and footer section</td>
        <td colspan="2">added header and footer section</td>
        <td colspan="2">25/04/2026</td>
    </tr>
     <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">10093f4</td>
        <td colspan="2">style: Add styles</td>
        <td colspan="2">Add styles</td>
        <td colspan="2">25/04/2026</td>
    </tr>
    <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">5a4332d</td>
        <td colspan="2">feat: added script.js</td>
        <td colspan="2">added script.js</td>
        <td colspan="2">25/04/2026</td>
    </tr>
    <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">72f4157</td>
        <td colspan="2">feat: added hero section.</td>
        <td colspan="2">added hero section.</td>
        <td colspan="2">25/04/2026</td>
    </tr>
   <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">e875205</td>
        <td colspan="2">fix: fixed header section.</td>
        <td colspan="2">fixed header section.</td>
        <td colspan="2">25/04/2026</td>
    </tr>
   <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">9624ec5</td>
        <td colspan="2">feat: update hero section images and testimonials</td>
        <td colspan="2">update hero section images and testimonials</td>
        <td colspan="2">25/04/2026</td>
    </tr>
   <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">9bc4018</td>
        <td colspan="2">feat: Funcionalidades Section</td>
        <td colspan="2">Funcionalidades Section</td>
        <td colspan="2">25/04/2026</td>
    </tr>
   <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">9e6c718</td>
        <td colspan="2">feat: add language toggle button and translation functionality (WIP)</td>
        <td colspan="2">add language toggle button and translation functionality (WIP)</td>
        <td colspan="2">25/04/2026</td>
    </tr>
   <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">a99916d</td>
        <td colspan="2">feat: nosotros section</td>
        <td colspan="2">nosotros section</td>
        <td colspan="2">25/04/2026</td>
    </tr>
   <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">022b681</td>
        <td colspan="2">feat: add multilingual support for functionalities and company sections</td>
        <td colspan="2">add multilingual support for functionalities and company sections</td>
        <td colspan="2">25/04/2026</td>
    </tr>
   <tr>
        <td colspan="2">iot-proyectos/LandingPage</td>
        <td colspan="2">main</td>
        <td colspan="2">3ddec9f</td>
        <td colspan="2">feat: update about section image to enhance visual content</td>
        <td colspan="2">update about section image to enhance visual content</td>
        <td colspan="2">26/04/2026</td>
    </tr>


</table>

##### 6.2.1.5. Testing Suite Evidence for Sprint Review

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
        
        var command = new CreateProfileCommand(
            "Diego", "Pérez", "diego@email.com",
            "Av. La Marina", "123", "Lima", "15088", "Perú");

        
        var profile = new Profile(command);

        
        profile.FullName.Should().Be("Diego Pérez");
        profile.EmailAddress.Should().Be("diego@email.com");
        profile.StreetAddress.Should().Contain("Lima");
    }

    [Fact]
    public void DefaultConstructor_ShouldCreateEmptyProfile()
    {
        
        var profile = new Profile();

        
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
        
        var command = new CreateProfileCommand(
            "Diego", "Pérez", "diego@email.com",
            "Av. La Marina", "123", "Lima", "15088", "Perú");

        _mockProfileRepository
            .Setup(r => r.AddAsync(It.IsAny<Profile>()))
            .Returns(Task.CompletedTask);

        _mockUnitOfWork
            .Setup(u => u.CompleteAsync())
            .Returns(Task.CompletedTask);

        
        var result = await _service.Handle(command);

        
        result.Should().NotBeNull();
        result!.FullName.Should().Be("Diego Pérez");
        _mockProfileRepository.Verify(r => r.AddAsync(It.IsAny<Profile>()), Times.Once);
        _mockUnitOfWork.Verify(u => u.CompleteAsync(), Times.Once);
    }

    [Fact]
    public async Task Handle_WhenRepositoryThrows_ShouldReturnNull()
    {
        
        var command = new CreateProfileCommand(
            "Diego", "Pérez", "diego@email.com",
            "Av. La Marina", "123", "Lima", "15088", "Perú");

        _mockProfileRepository
            .Setup(r => r.AddAsync(It.IsAny<Profile>()))
            .ThrowsAsync(new Exception("Database error"));

        
        var result = await _service.Handle(command);

       
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
        
        var profiles = new List<Profile>
        {
            new("Diego", "Pérez", "diego@email.com", "Calle 1", "100", "Lima", "15000", "Perú"),
            new("Ana", "García", "ana@email.com", "Calle 2", "200", "Lima", "15001", "Perú")
        };

        _mockProfileRepository
            .Setup(r => r.ListAsync())
            .ReturnsAsync(profiles);

        
        var result = await _service.Handle(new GetAllProfilesQuery());

        
        result.Should().HaveCount(2);
    }

    [Fact]
    public async Task Handle_GetProfileByIdQuery_WhenExists_ShouldReturnProfile()
    {
       
        var profile = new Profile("Diego", "Pérez", "diego@email.com",
            "Calle 1", "100", "Lima", "15000", "Perú");

        _mockProfileRepository
            .Setup(r => r.FindByIdAsync(1))
            .ReturnsAsync(profile);

        
        var result = await _service.Handle(new GetProfileByIdQuery(1));

        
        result.Should().NotBeNull();
        result!.FullName.Should().Be("Diego Pérez");
    }

    [Fact]
    public async Task Handle_GetProfileByIdQuery_WhenNotExists_ShouldReturnNull()
    {
        
        _mockProfileRepository
            .Setup(r => r.FindByIdAsync(999))
            .ReturnsAsync((Profile?)null);

    
        var result = await _service.Handle(new GetProfileByIdQuery(999));

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
        
        var response = await _client.GetAsync("/api/v1/profiles");

        
        response.StatusCode.Should().Be(HttpStatusCode.OK);
    }

    [Fact]
    public async Task CreateProfile_WithValidData_ShouldReturnCreated()
    {
        
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

        
        var response = await _client.PostAsJsonAsync("/api/v1/profiles", createRequest);

        
        response.StatusCode.Should().Be(HttpStatusCode.Created);
    }

    [Fact]
    public async Task GetProfileById_WhenNotExists_ShouldReturnNotFound()
    {
        
        var response = await _client.GetAsync("/api/v1/profiles/999");

        
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

###### Landing Page

Como equipo, lo que logramos en este primer Sprint fue la exitosa implementación de nuestra Landing Page y su posterior despliegue gracias a la herramienta GitHub Pages. A continuación, presentaremos lo logrado a través de imágenes mostrando las principales vistas.

- Esta es la sección inicial, donde está el header y nuestra propuesta de valor.
  ![Landing-Page.png]( assets/chapter-05/Landing-Page.png)

- Aquí se puede observar la sección donde se presenta a los usuarios a los que está orientado nuestra plataforma.
  ![LandingPage-Evidence2.png]( assets/chapter-05/LandingPage-Evidence2.png)


- Esta sección describe las funcionalidades claves principales de nuestra plataforma OsitoPolar.
  ![LandingPage-Evidence3.png]( assets/chapter-05/LandingPage-Evidence3.png)


- Tenemos en esta sección la visualización de los beneficios que obtendrá cada uno de nuestros usuarios de cada segmento.
  ![LandingPage-Evidence4Neg.png]( assets/chapter-05/LandingPage-Evidence4Neg.png)
  ![LandingPage-Evidence4Tec.png]( assets/chapter-05/LandingPage-Evidence4Tec.png)


- Por último, está la sección donde podemos solicitar una demo.
  ![LandingPage-Evidence6.png]( assets/chapter-05/LandingPage-Evidence6.png)


- Para más detalles, visualizar el video: [Video demostrativo de la landing page](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c111_upc_edu_pe/IQAeOr9bSx-2T4NJ5MMy6oFYAUG9i8dFYt45TIvlXmJ_M_I?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=2Kps8L)


##### 6.2.1.6. Execution Evidence for Sprint Review

> **Falta:** agregar evidencia de ejecución del Sprint 1, incluyendo capturas o descripción de la Landing Page funcionando y los flujos principales revisados en el sprint.

##### 6.2.1.7. Services Documentation Evidence for Sprint Review

Durante este Sprint solo se realizó la Landing Page, no se han documentado nuevos Endpoints relacionados con el alcance definido, por lo tanto, no se dispone de documentación generada en OpenAPI para esta entrega.

##### 6.2.1.8. Software Deployment Evidence for Sprint Review

Durante el presente Sprint, se llevó a cabo el despliegue de la Landing Page del proyecto utilizando GitHub Pages como proveedor de hosting. Esta actividad forma parte del proceso de Deployment, siendo un primer paso en la publicación de productos desarrollados en este Sprint.

**Pasos realizados**

1. Iniciamos sesión en GitHub. En caso de no tener cuenta o querer trabajar con una nueva, nos registramos.
   ![Deployment-step1.png]( assets/chapter-05/Deployment-step1.png)


2. Luego de iniciar sesión o registrarnos, seleccionamos a nuestro perfil de usuario y luego elegimos "Your organizations".
   ![Deployment-step2-1.png]( assets/chapter-05/Deployment-step2-1.png)
   ![Deployment-step2-2.png]( assets/chapter-05/Deployment-step2-2.png)


3. En la nueva pestaña seleccionamos "New organization", luego seleccionamos el plan gratuito y finalmente rellenamos los datos para crear la organización
   ![Deployment-step3-1.png]( assets/chapter-05/Deployment-step3-1.png)


4. Dentro de la organización seleccionamos "People" para invitar a los miembros del equipo.
   ![Deployment-step4-1.png]( assets/chapter-05/Deployment-step4-1.png)
   ![Deployment-step4-2.png]( assets/chapter-05/Deployment-step4-2.png)


5. Luego de tener al equipo completo en la organización, creamos un nuevo repositorio. En nuestro caso tenemos solo dos repositorios por el momento, uno para el informe y el otro para el Landing Page. Nos dirigimos a este último.
   ![Deployment-step5-1.png]( assets/chapter-05/Deployment-step5-1.png)
   ![Deployment-step5-2.png]( assets/chapter-05/Deployment-step5-2.png)


6. Al estar en el repositorio "Landing Page", nos dirigimos a settings y seleccionamos "pages" (1). Luego seleccionamos la rama y ruta en la que está el código que deseamos desplegar (2). Guardamos (3) y finalmente tendremos que esperar unos minutos para que el enlace esté disponible (4).
   ![Deployment-step6-1.png]( assets/chapter-05/Deployment-step6-1.png)
   ![Deployment-step6-2.png]( assets/chapter-05/Deployment-step6-2.png)

7. Podemos visualizar el resultado.
   ![Deployment-step7.png]( assets/chapter-05/Landing-Page.png)

##### 6.2.1.9. Team Collaboration Insights during Sprint

Durante este Sprint, el equipo ha colaborado activamente en el desarrollo de la Landing Page. Las actividades fueron gestionadas a través de GitHub, permitiendo una trazabilidad clara de los aportes de cada miembro del equipo. Se realizaron tareas de codificación, revisión, organización del repositorio y mejoras visuales y funcionales del producto.
Cada miembro del equipo tuvo participación activa, realizando commits, revisando código, y apoyando en la estructura y documentación del proyecto.

![Insights-LandingPage.png]( assets/chapter-05/Insights-LandingPage.png)

Contributors:

![Contributors-LandingPage.png](assets/chapter-05/Contributors-LandingPage.png)


#### 6.2.2. Sprint 2
##### 6.2.2.1. Sprint Planning 2
<table>
<tr>
    <th colspan="5">Sprint 2</th>
    <th colspan="9">Sprint 2</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-05-10</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">10:30 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Diego Cacho</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Diego Mora, Christian Inga, Sebastian Hernandez, Raúl Medina</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Review Summary</td>
    <td colspan="8">Durante el primer Sprint nos enfocamos en desarrollar la Landing page y logramos desplegarla con éxito; no obstante, cometimos un error al configurarla con el idioma español por defecto, cuando en realidad debió estar orientada al inglés.</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Retrospective Summary</td>
    <td colspan="8">Durante el primer Sprint trabajamos de forma colaborativa y completamos varias tareas con éxito. Sin embargo, se presentaron más errores de los esperados. Identificamos como oportunidades de mejora la falta de revisión cruzada entre equipos y la necesidad de documentarnos mejor sobre cada sección desarrollada. </td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint 2 Goal</td>
       <td colspan="8">Nuestro enfoque está en entregar una aplicación web de una sola página (SPA) completamente funcional y visualmente mejorada, incluyendo la corrección de la experiencia en la landing page.
Creemos que esto proporcionará mayor claridad y usabilidad a los clientes potenciales y primeros usuarios que están evaluando nuestra plataforma.
Esto se confirmará cuando la landing page refleje los ajustes de diseño, la navegación sea fluida dentro de la SPA y la aplicación esté desplegada y accesible públicamente.</td>

</tr>
<tr>
    <td colspan="5">Sprint 2 Velocity</td>
    <td colspan="8">32</td>
<tr>
    <td colspan="5">Sum of Story Points</td>
    <td colspan="8">30</td>
</tr>
</table>


##### 6.2.2.2. Aspect Leaders and Collaborators

Durante este segundo Sprint, el equipo se enfocó en la corrección de la Landing Page y en el desarrollo del Single Page Aplication (Frontend) de OsitoPolar.
Con el fin de organizar de manera más eficiente el trabajo colaborativo, se ha elaborado la matriz de Liderazgo y Colaboración (LACX). Esta matriz asigna responsabilidades específicas a cada miembro del equipo en relación con los aspectos clave del Sprint.
<table>
  <tr>
    <td colspan="2"><strong>Team Member (Last Name, First Name)</strong></td>
    <td><strong>GitHub Username</strong></td>
    <td><strong>Correcciones generales de la Landing Page<br>Leader (L) / Collaborator (C)</strong></td>
    <td><strong>Implementación de la gestión de equipos de refrigeración<br>Leader (L) / Collaborator (C)</strong></td>
    <td><strong>Implementación de gráficos analíticos<br>Leader (L) / Collaborator (C)</strong></td>
    <td><strong>Despliegue de la aplicación web<br>Leader (L) / Collaborator (C)</strong></td>
  </tr>
  <tr>
    <td colspan="2">Cacho Seminario, Diego Alonso </td>
    <td>Memesitos</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo </td>
    <td>Necxuz18</td>
    <td>L</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
  </tr>
  <tr>
    <td colspan="2"> Medina Cruzado, Raúl Adrian </td>
    <td>imisterdg</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td colspan="2">Inga Orihuela, Christian Fabrizio
</td>
    <td>Christian1905</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td colspan="2">Mora Blas, Diego Alonzo </td>
    <td>diegoalonzomora</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
  </tr>
</table>

##### 6.2.2.3. Sprint Backlog 2

El objetivo principal de este Sprint es implementar la primera version de la plataforma web de OsitoPolar, enfocada en registrar dispositivos IoT, visualizar el estado de equipos refrigerados, consultar temperatura y humedad, configurar rangos seguros y recibir alertas cuando un dispositivo se desconecta o cuando las condiciones salen del rango definido. La plataforma elegida para el control de tareas fue Trello.

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 2</th>
</tr>
<tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
</tr>
<tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1">Estimation (Hours)</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status (To do/ In-Process/ To-Review/ Done)</td>
</tr>
<tr>
    <td colspan="1">US-06</td>
    <td colspan="2">Registrar dispositivos IoT</td>
    <td colspan="1">UT-01</td>
    <td colspan="2">Crear estructura de dispositivos</td>
    <td colspan="3">Crear componentes, entidades y servicios para registrar sensores asociados a refrigeradores, congeladores, camaras frias o almacenes.</td>
    <td colspan="1">2</td>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-06</td>
    <td colspan="2">Registrar dispositivos IoT</td>
    <td colspan="1">UT-02</td>
    <td colspan="2">Implementar CRUD de dispositivos</td>
    <td colspan="3">Implementar crear, listar, editar y eliminar dispositivos con nombre, ubicacion, tipo de activo, estado de conexion y rangos seguros.</td>
    <td colspan="1">3</td>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-09</td>
    <td colspan="2">Visualizar temperatura y humedad en tiempo real</td>
    <td colspan="1">UT-03</td>
    <td colspan="2">Crear modelo de telemetria</td>
    <td colspan="3">Definir estructura para lecturas de temperatura, humedad, fecha, dispositivo y estado de recepcion.</td>
    <td colspan="1">3</td>
    <td colspan="2">Medina Cruzado, Raul Adrian</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-09</td>
    <td colspan="2">Visualizar temperatura y humedad en tiempo real</td>
    <td colspan="1">UT-04</td>
    <td colspan="2">Implementar dashboard de monitoreo</td>
    <td colspan="3">Mostrar tarjetas de dispositivos con temperatura, humedad, estado de conexion y condicion actual dentro/fuera de rango.</td>
    <td colspan="1">3</td>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-10</td>
    <td colspan="2">Configurar rangos seguros</td>
    <td colspan="1">UT-05</td>
    <td colspan="2">Agregar controles de rango</td>
    <td colspan="3">Permitir definir temperatura y humedad minima y maxima por dispositivo o tipo de activo refrigerado.</td>
    <td colspan="1">2</td>
    <td colspan="2">Cacho Seminario, Diego Alonso</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-10</td>
    <td colspan="2">Configurar rangos seguros</td>
    <td colspan="1">UT-06</td>
    <td colspan="2">Validar valores de configuracion</td>
    <td colspan="3">Aplicar validaciones para evitar rangos incoherentes y mostrar mensajes de error claros al usuario.</td>
    <td colspan="1">2</td>
    <td colspan="2">Inga Orihuela, Christian Fabrizio</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-07</td>
    <td colspan="2">Recibir alertas por fuera de rango</td>
    <td colspan="1">UT-07</td>
    <td colspan="2">Crear modulo de alertas</td>
    <td colspan="3">Crear componentes, modelos y servicios para alertas por temperatura, humedad y criticidad.</td>
    <td colspan="1">3</td>
    <td colspan="2">Mora Blas, Diego Alonzo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-07</td>
    <td colspan="2">Recibir alertas por fuera de rango</td>
    <td colspan="1">UT-08</td>
    <td colspan="2">Implementar reglas de alerta</td>
    <td colspan="3">Crear la logica que marque una lectura como alerta cuando temperatura o humedad salgan del rango seguro configurado.</td>
    <td colspan="1">3</td>
    <td colspan="2">Medina Cruzado, Raul Adrian</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-11</td>
    <td colspan="2">Detectar dispositivos desconectados</td>
    <td colspan="1">UT-09</td>
    <td colspan="2">Agregar estado de conexion</td>
    <td colspan="3">Mostrar dispositivos conectados, desconectados o sin lectura reciente en el dashboard.</td>
    <td colspan="1">2</td>
    <td colspan="2">Cacho Seminario, Diego Alonso</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-11</td>
    <td colspan="2">Detectar dispositivos desconectados</td>
    <td colspan="1">UT-10</td>
    <td colspan="2">Generar alerta de desconexion</td>
    <td colspan="3">Crear alerta cuando un dispositivo no reporte lecturas dentro del intervalo esperado.</td>
    <td colspan="1">2</td>
    <td colspan="2">Inga Orihuela, Christian Fabrizio</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-12</td>
    <td colspan="2">Consultar historico de condiciones</td>
    <td colspan="1">UT-11</td>
    <td colspan="2">Agregar graficos historicos</td>
    <td colspan="3">Implementar graficos de temperatura y humedad por dispositivo para analizar variaciones y eventos fuera de rango.</td>
    <td colspan="1">4</td>
    <td colspan="2">Hernandez Poma, Sebastian Eduardo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-28</td>
    <td colspan="2">Gestionar planes de uso</td>
    <td colspan="1">UT-12</td>
    <td colspan="2">Crear vista de planes</td>
    <td colspan="3">Mostrar planes disponibles, limites por cantidad de dispositivos y beneficios del plan empresarial.</td>
    <td colspan="1">2</td>
    <td colspan="2">Mora Blas, Diego Alonzo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US-29</td>
    <td colspan="2">Ubicar dispositivos en planos interactivos</td>
    <td colspan="1">UT-13</td>
    <td colspan="2">Dise�ar vista inicial de plano</td>
    <td colspan="3">Crear una primera vista para ubicar dispositivos dentro de una instalacion refrigerada como funcionalidad del plan empresarial.</td>
    <td colspan="1">3</td>
    <td colspan="2">Cacho Seminario, Diego Alonso</td>
    <td colspan="1">To-Review</td>
</tr>

</table>

![sprintbacklog2.png]( assets/chapter-05/sprint2/sprintbacklog2.png)

Link Trello Sprint Backlog #2: https://shorturl.at/VgV08
##### 6.2.2.4. Development Evidence for Sprint Review

En este segundo Sprint hemos realizado la implementación de nuestra Single Page Aplication. En la siguiente tabla se muestran los commits realizados.



<table>
    <tr>
        <th colspan="2">Repository</th>
        <th colspan="2">Branch</th>
        <th colspan="2">Commit Id</th>
        <th colspan="2">Commit Message</th>
        <th colspan="2">Commit Message Body</th>
        <th colspan="2">Commited on (Date)</th>
    </tr>
    <tr>
        <td colspan="2">iot-proyectos/OsitoPolar-Frontend</td>
        <td colspan="2">main</td>
        <td colspan="2">b31f2a4</td>
        <td colspan="2">feat: implement spa base structure</td>
        <td colspan="2">implemented the initial structure for the single page application</td>
        <td colspan="2">13/05/2026</td>
    </tr>
    <tr>
        <td colspan="2">iot-proyectos/OsitoPolar-Frontend</td>
        <td colspan="2">main</td>
        <td colspan="2">c82de19</td>
        <td colspan="2">feat: add equipment management module</td>
        <td colspan="2">added components and services for equipment management</td>
        <td colspan="2">13/05/2026</td>
    </tr>
    <tr>
        <td colspan="2">iot-proyectos/OsitoPolar-Frontend</td>
        <td colspan="2">main</td>
        <td colspan="2">f9a54e0</td>
        <td colspan="2">feat: add analytics views</td>
        <td colspan="2">added charts and analytics views for monitored equipment</td>
        <td colspan="2">14/05/2026</td>
    </tr>
    <tr>
        <td colspan="2">iot-proyectos/OsitoPolar-Frontend</td>
        <td colspan="2">main</td>
        <td colspan="2">d47ac91</td>
        <td colspan="2">fix: update landing page language content</td>
        <td colspan="2">corrected landing page text and language behavior for sprint review</td>
        <td colspan="2">14/05/2026</td>
    </tr>
</table>


##### 6.2.2.5. Testing Suite Evidence for Sprint Review

> **Falta:** agregar la evidencia de pruebas del Sprint 2, indicando pruebas ejecutadas, resultados, herramientas usadas y estado final de la suite.

##### 6.2.2.6. Execution Evidence for Sprint Review

En este segundo Sprint realizamos mejoras y correcciones de idioma en la Landing Page y la implementación de nuestro Frontend.

**Landing Page**

- Esta es la sección inicial, donde está el header y nuestra propuesta de valor.
![LandingPage-Evidence-S2.png]( assets/chapter-05/sprint-2/LandingPage-Evidence-S2.png)

- Aquí se puede observar la sección donde se presenta a los usuarios a los que está orientado nuestra plataforma.
![LandingPage-Evidence2-S2.png]( assets/chapter-05/sprint-2/LandingPage-Evidence2-S2.png)

- Esta sección describe las funcionalidades claves principales de nuestra plataforma OsitoPolar.
![LandingPage-Evidence3-S2.png]( assets/chapter-05/sprint-2/LandingPage-Evidence3-S2.png)

- Tenemos en esta sección la visualización de los beneficios que obtendrá cada uno de nuestros usuarios de cada segmento.
![LandingPage-Evidence4-S2.png]( assets/chapter-05/sprint-2/LandingPage-Evidence4-S2.png)

- La sección donde podemos solicitar una demo.
![LandingPage-Evidence6-S2.png]( assets/chapter-05/sprint-2/LandingPage-Evidence6-S2.png)

**Frontend**

- Esta es la sección inicial llamada "Home", es lo primero que verá el usuario al ingresar a la aplicación.
![SPA-Evidence-S2.png]( assets/chapter-05/sprint-2/SPA-Evidence-S2.png)

- En esta se pueden observar las máquinas que están siendo monitoreadas y donde también se pueden registrar, editar y eliminar.
![SPA-Evidence2-S2.png]( assets/chapter-05/sprint-2/SPA-Evidence2-S2.png)

- En estas secciones se pueden visualizan los atributos, configuraciones y análisis de temperatura de los equipos de refrigeración.
![SPA-Evidence3-S2.png]( assets/chapter-05/sprint-2/SPA-Evidence3-S2.png)
![SPA-Evidence4-S2.png]( assets/chapter-05/sprint-2/SPA-Evidence4-S2.png)

- Tenemos la sección donde se visualizan las notificaciones.
![SPA-Evidence5-S2.png]( assets/chapter-05/sprint-2/SPA-Evidence5-S2.png)

- Por último, la sección por defecto que muestra el mensaje que nos indica que la página no ha sido encontrada.
![SPA-Evidence6-S2.png]( assets/chapter-05/sprint-2/SPA-Evidence6-S2.png)

##### 6.2.2.7. Services Documentation Evidence for Sprint Review

No se emplearon servicios adicionales, ya que este segundo sprint se centró exclusivamente en la implementación de la primera versión del web application.

##### 6.2.2.8. Software Deployment Evidence for Sprint Review

Durante este Sprint hemos desplegado el frontend.

- Usaremos Beeceptor es una herramienta en línea para probar y depurar APIs.

![deployment0-s2.png]( assets/chapter-05/sprint-2/deployment0-s2.png)

![deployment01-s2.png]( assets/chapter-05/sprint-2/deployment01-s2.png)


- Usaremos Firebase, el cuál es una plataforma de desarrollo de Google que ofrece servicios backend listos para usar, como autenticación, bases de datos en tiempo real, notificaciones y, en este caso, hosting web estático.
![deployment1-S2.png]( assets/chapter-05/sprint-2/deployment1-S2.png)

![deployment2-s2.png]( assets/chapter-05/sprint-2/deployment2-s2.png)

![deployment3-S2.png]( assets/chapter-05/sprint-2/deployment3-S2.png)

![deployment4-S2.png]( assets/chapter-05/sprint-2/deployment4-S2.png)

![deployment6-S2.png]( assets/chapter-05/sprint-2/deployment6-S2.png)

![deployment7-S2.png]( assets/chapter-05/sprint-2/deployment7-S2.png)

![deployment9-S2.png]( assets/chapter-05/sprint-2/deployment9-S2.png)

![deployment11-S2.png]( assets/chapter-05/sprint-2/deployment11-S2.png)

![deployment12-S2.png]( assets/chapter-05/sprint-2/deployment12-S2.png)


- Finalmente se puede visualizar nuestro proyecto desplegado.

![deploymentfinalS2.png]( assets/chapter-05/sprint-2/deploymentfinalS2.png)

##### 6.2.2.9. Team Collaboration Insights during Sprint

Durante este Sprint, el equipo ha colaborado en el desarrollo del frontend y correcciones de diseño e idioma. Los miembros del equipo revisaban y señalaban ciertos errores a quién se encargaba de los commits. Por falta de tiempo y experiencia en el equipo no se pudo realizar una colaboración perfecta. Las actividades fueron gestionadas a través de GitHub, permitiendo una trazabilidad clara de los aportes de cada miembro del equipo. Se realizaron tareas de codificación, revisión, organización del repositorio y mejoras visuales y funcionales del producto.

**LandingPage**

![Insights-LandingPage-S2.png]( assets/chapter-05/sprint-2/Insights-LandingPage.png)

![Contributors-LandingPageS2.png]( assets/chapter-05/sprint-2/Contributors-LandingPage.png)

![alt text](assets/chapter-05/Insights-LandingPage.png)
**Frontend**
![Insight-front1](assets/chapter-05/sprint-2/Insights-Frontend-S2.png)

### 6.2.3. Sprint 3

Este tercer y último sprint representa la fase de consolidación técnica del proyecto OsitoPolar. El enfoque principal radicó en la integración del hardware físico (Edge Device) con la infraestructura Cloud, y la culminación de la aplicación móvil para el consumo y visualización de telemetría en tiempo real, cerrando así el ciclo de vida del desarrollo.

#### 6.2.3.1. Sprint Planning 3

| Sprint 3 | |
| :--- | :--- |
| **Sprint Planning Background** | |
| Date | 2026-06-05 |
| Time | 8:00 PM |
| Location | Vía Discord |
| Prepared By | Cacho Seminario, Diego Alonso |
| Attendees | Diego Mora, Christian Inga, Sebastian Hernandez, Raúl Medina, Diego Cacho |
| **Sprint 2 Review Summary** | Durante el segundo Sprint logramos desplegar satisfactoriamente la aplicación web y corregir los errores de la Landing Page, obteniendo un MVP web funcional. Sin embargo, quedó pendiente la integración nativa móvil y la captura real de telemetría IoT. |
| **Sprint 2 Retrospective Summary** | Identificamos que la separación de tareas mejoró nuestro rendimiento, pero las pruebas de integración entre frontend y backend tomaron más tiempo del estimado. Acordamos realizar pruebas conjuntas tempranas para la integración del hardware. |
| **Sprint Goal & User Stories** | |
| **Sprint 3 Goal** | Lograr la comunicación bidireccional exitosa entre los dispositivos IoT (Edge) y la Base de Datos en la nube, y reflejar estos datos de manera dinámica y en tiempo real en la aplicación móvil nativa. Esto se validará cuando un cambio físico en el sensor de temperatura se visualice correctamente en la app móvil. |
| **Sprint 3 Velocity** | 25 |
| **Sum of Story Points** | 25 |

#### 6.2.3.2. Aspect Leaders and Collaborators
Para garantizar el éxito de esta fase crítica de integración, las responsabilidades se distribuyeron aprovechando la especialización técnica de cada miembro:

| Team Member (Last Name, First Name) | GitHub Username | Lógica Edge & Hardware IoT<br>Leader (L) / Collaborator (C) | Desarrollo App Móvil<br>Leader (L) / Collaborator (C) | Endpoints Cloud & BD<br>Leader (L) / Collaborator (C) | Despliegue y Pruebas E2E<br>Leader (L) / Collaborator (C) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Cacho Seminario, Diego Alonso | Memesitos | C | L | C | C |
| Hernandez Poma, Sebastian Eduardo | Necxuz18 | C | C | C | L |
| Medina Cruzado, Raúl Adrian | imisterdg | L | C | C | C |
| Inga Orihuela, Christian Fabrizio | Christian1905 | C | C | C | L |
| Mora Blas, Diego Alonzo | diegoalonzomora | C | C | L | C |

#### 6.2.3.3. Sprint Backlog 3
Durante este sprint se abordaron las historias de usuario criticas para completar el ecosistema IoT de OsitoPolar, integrando el dispositivo fisico, la recepcion de telemetria en la nube, las alertas automaticas y la visualizacion empresarial de dispositivos dentro de instalaciones refrigeradas.

| ID | Title | Description | Estimation (Hours) | Status |
| :--- | :--- | :--- | :--- | :--- |
| **US-15** | Generar API Key para dispositivo IoT | Como administrador, quiero generar una API Key por dispositivo para autenticar el envio de telemetria desde sensores instalados en equipos refrigerados. | 3 | Done |
| **US-16** | Enviar telemetria de temperatura y humedad | Como dispositivo IoT, quiero enviar lecturas de temperatura y humedad al servidor Cloud para que la plataforma muestre el estado de la cadena de frio en tiempo real. | 5 | Done |
| **US-17** | Visualizar historico de lecturas | Como usuario, quiero revisar el historico de temperatura y humedad por dispositivo para analizar variaciones, incidentes y tiempos fuera de rango. | 5 | Done |
| **US-18** | Detectar alertas por condiciones fuera de rango | Como usuario, quiero recibir alertas cuando la temperatura o humedad salgan del rango seguro configurado para proteger los productos refrigerados. | 4 | Done |
| **US-19** | Detectar dispositivos desconectados | Como usuario, quiero recibir una alerta cuando un dispositivo deje de reportar datos para identificar fallas de conectividad o problemas del sensor. | 3 | Done |
| **US-20** | Desplegar base de datos y API en Cloud | Como equipo de desarrollo, queremos desplegar la base de datos y la API en un entorno Cloud para recibir telemetria desde dispositivos reales. | 2 | Done |
| **US-21** | Ubicar dispositivos en plano interactivo | Como usuario empresarial, quiero ubicar dispositivos dentro de un plano de mi instalacion para identificar rapidamente donde ocurre una alerta. | 4 | To-Review |
| **US-22** | Validar flujo end-to-end IoT | Como equipo de QA, queremos validar el flujo completo sensor -> Cloud API -> dashboard web para asegurar que las lecturas y alertas se visualicen correctamente. | 4 | Done |
#### 6.2.3.4. Development Evidence for Sprint Review

**Mobile App (Generación de API Keys y Consumo):**
Se implementó la lógica en el `ManagementViewModel` de Android utilizando Kotlin y corrutinas. Se integró la librería `java.util.UUID` para generar llaves criptográficas únicas al momento de crear un dispositivo, enviándolas al backend a través de Retrofit. Asimismo, se construyó el flujo `fetchHistory()` para mapear las respuestas JSON de temperaturas a objetos de estado visuales en Jetpack Compose.

**Edge Device (Captura de Telemetría):**
Se desarrolló el firmware del microcontrolador encargado de leer los sensores físicos. Se implementó un ciclo de captura que empaqueta los datos de temperatura y humedad en formato JSON y los transmite mediante peticiones HTTP POST al endpoint expuesto por la Cloud API, adjuntando la API Key en los headers para su autorización.

**Backend (Endpoints de Integración):**
Se actualizó el repositorio del dispositivo para soportar la creación bajo demanda (Lazy Creation) de mapas (Sections) en caso de usuarios nuevos, asegurando que el despliegue multi-tenant funcione sin errores. Se expusieron y aseguraron las rutas para servir el historial de lecturas a la aplicación móvil.

#### 6.2.3.5. Testing Suite Evidence for Sprint Review
Se ejecutó una batería de pruebas integrales para garantizar la resiliencia del sistema:
1.  **API Testing (Postman):** Se verificó la correcta inserción de datos simulando el envío de payloads desde el dispositivo IoT, confirmando respuestas HTTP 201 (Created) y el manejo de errores HTTP 401 (Unauthorized) al enviar API Keys inválidas.
2.  **Hardware Testing:** Se validó que el Edge Device pudiera recuperar la conexión tras caídas simuladas de la red Wi-Fi, asegurando la continuidad de la telemetría.
3.  **Mobile UI Testing:** Se comprobó que el flujo de registro de dispositivos bloqueara intentos con campos vacíos y mostrara correctamente los cuadros de diálogo de éxito con las llaves generadas.

#### 6.2.3.6. Execution Evidence for Sprint Review
La ejecución exitosa del proyecto se evidenció mediante:
* La captura de registros en la consola del backend confirmando la recepción continua de datos: `[OsitoPolar] Telemetry received from device X`.
* La creación automática de "Sections" vacías para nuevos usuarios directamente desde la interacción móvil.
* La visualización fluida de la lista del historial de temperaturas en la interfaz de Android, diferenciando visualmente las lecturas normales de aquellas que superaban los umbrales de alerta (ej. temperaturas menores a -10°C).

#### 6.2.3.7. Services Documentation Evidence for Sprint Review
La documentación de los servicios fue actualizada para reflejar los nuevos contratos de comunicación establecidos en este sprint. Se detallaron los esquemas de petición y respuesta para la inyección de telemetría, especificando la obligatoriedad del header de autorización para los dispositivos IoT. Esta documentación servirá como guía definitiva para la futura integración de nuevos modelos de sensores al ecosistema OsitoPolar.

#### 6.2.3.8. Software Deployment Evidence for Sprint Review
La arquitectura se migró exitosamente de un entorno de desarrollo local a una infraestructura de producción en la nube:
* **Base de Datos:** Migración a **Neon.tech** (PostgreSQL Serverless), permitiendo alta disponibilidad y conexión remota. Se ejecutaron las migraciones correspondientes utilizando Prisma.
* **Backend API:** Despliegue en **Railway**, configurando las variables de entorno (`DATABASE_URL`, claves JWT y de pago) para aceptar peticiones externas.
* **Mobile App:** Modificación del `BASE_URL` en el cliente Retrofit para apuntar al servidor de producción, culminando con la generación del archivo APK (Android Package Kit) firmado y listo para su distribución e instalación en dispositivos físicos.

#### 6.2.3.9. Team Collaboration Insights during Sprint
La comunicación del equipo durante este sprint de cierre fue intensiva y altamente coordinada. 
* Se utilizó **GitHub** para el manejo de ramas (branching) separando los desarrollos del firmware IoT y la interfaz móvil, resolviendo conflictos de integración de manera colaborativa.
* Se mantuvo una trazabilidad completa de los avances mediante herramientas de gestión ágil, actualizando los estados de las tareas.
* Las reuniones de sincronización en Discord fueron fundamentales para desbloquear cuellos de botella técnicos, especialmente durante la calibración de los tiempos de envío entre el sensor físico y la recepción en el servidor Railway.

## 6.3. Validation Interviews.
En esta sección se presentan los detalles de las entrevistas de validación realizadas.

### 6.3.1. Diseño de Entrevistas.

<h4>Objetivo de la Entrevista</h4>
<p>Validar la usabilidad, efectividad y propuesta de valor de la plataforma OsitoPolar para los segmentos clave. Se evaluará si las funcionalidades cubren las necesidades operativas reales y si los flujos son intuitivos para usuarios con distintos perfiles técnicos.</p>

<h4>Elementos de Validación</h4>
<ul>
  <li><strong>Landing Page:</strong> Claridad en la propuesta de valor, acceso a funcionalidades clave, llamados a la acción.</li>
  <li><strong>Aplicación Web/Móvil:</strong> Flujos críticos como registro de equipos, solicitud de servicios, visualización de reportes, asignación de técnicos y generación de alertas.</li>
</ul>

<h4>User Flows a Validar</h4>

<h5>Para el Segmento: Negocios con Equipos de Refrigeración</h5>
<ol>
  <li>Registro y configuración inicial</li>
  <li>Monitoreo y alertas</li>
  <li>Solicitud de servicios</li>
  <li>Visualización de reportes</li>
  <li>Evaluación del servicio</li>
</ol>

<h5>Para el Segmento: Empresas Proveedoras de Servicios</h5>
<ol>
  <li>Recepción de solicitudes</li>
  <li>Gestión de técnicos</li>
  <li>Historial técnico</li>
  <li>Generación de reportes</li>
  <li>Gestión de cartera de clientes</li>
</ol>

<h4>Formato de Registro de Entrevista</h4>
<ul>
  <li>Nombre completo</li>
  <li>Edad</li>
  <li>Distrito de residencia</li>
  <li>Rol en su empresa</li>
  <li>Dispositivo utilizado para la prueba</li>
</ul>

<h3>Preguntas para el Segmento 1: Negocios que utilizan Equipos de Refrigeración</h3>
<ul>
  <li>¿De que manera te pareció útil la información del Landing Page?</li>
</ul>
<h4>Registro y Gestión de Equipos</h4>
<ul>
  <li>¿Qué tan fácil fue registrar tus equipos de refrigeración?</li>
  <li>¿La información solicitada fue clara y necesaria?</li>
  <li>¿Hubo algún paso que te generó dudas?</li>
</ul>

<h4>Monitoreo y Alertas</h4>
<ul>
  <li>¿Cómo sentiste el proceso para acceder al estado de tus equipos?</li>
  <li>¿De que manera te sirvió la sección de alertas de los equipos?</li>
  <li>¿Cómo afectaría tu toma de decisiones estas alertas?</li>
</ul>

<h4>Solicitudes de Servicio</h4>
<ul>
  <li>¿Cómo fue tu experiencia solicitando un servicio?</li>
  <li>¿La opción para programar mantenimiento estaba visible y disponible?¿Qué te pareció su implementación?</li>
  <li>¿Cómo fue tu proceso al solicitar un tipo de servicio?</li>
</ul>

<h4>Visualización de Reportes</h4>
<ul>
  <li>¿De que manera te ayudo los reportes de los equipos a conocer el estado en el que se ?</li>
  <li>¿Cómo es que los reportes de consumo energético te sirvieron para detectar posibles problemas?</li>
  <li>¿Qué agregarías o mejorarías en estos reportes?</li>
</ul>

<h4>Evaluación del Servicio</h4>
<ul>
  <li>¿Fue sencillo dejar una evaluación después del servicio?¿Cómo fue tu experiencia al usar esta funcionalidad?</li>
  <li>¿De qué manera consideras útil poder modificar tu evaluación si hubo cambios posteriores?</li>
</ul>

<h3>Preguntas para el Segmento 2: Empresas Proveedoras de Servicios</h3>

<h4>Recepción y Gestión de Solicitudes</h4>
<ul>
  <li>¿Puedes describir cómo es el proceso de recibir una nueva solicitud de servicio en la plataforma y qué aspectos destacarías, tanto positivos como áreas de mejora? </li>
  <li>¿Cómo describirías tu experiencia al asignar un técnico a una solicitud de servicio en la plataforma, y qué elementos del procedimiento te resultaron más útiles o desafiantes?</li>
  <li>¿Cómo ha sido tu experiencia al realizar el seguimiento del estado de los servicios en tiempo real, y qué características de esta funcionalidad consideras más valiosas o cuáles mejorarías? </li>
</ul>

<h4>Gestión de Técnicos</h4>
<ul>
  <li>¿Cómo describirías el procedimiento para asignar técnicos a las solicitudes de servicio, y qué sugerencias tendrías para optimizar esta funcionalidad? </li>
  <li>¿Qué información sobre el desempeño de los técnicos encuentras en la plataforma, y cómo te ayuda o qué aspectos adicionales te gustaría ver?</li>
  <li> ¿De qué manera el sistema de métricas de desempeño de la plataforma ha impactado en la gestión de tus técnicos, y qué mejoras sugerirías para hacerlo más útil? </li>
</ul>

<h4>Historial y Reportes Técnicos</h4>
<ul>
  <li>¿Cómo ha sido tu experiencia al acceder al historial técnico de los equipos atendidos, y qué aspectos del procedimiento te parecen efectivos o cuáles cambiarías? </li>
  <li>¿Cómo describirías la utilidad y claridad de los reportes generados por la plataforma para tus clientes, y qué elementos crees que podrían mejorarse?</li>
  <li>¿Puedes contarme cómo es el proceso de generación automática de reportes en la plataforma y qué aspectos consideras que funcionan bien o podrían optimizarse?</li>
</ul>

<h4>Gestión de Cartera de Clientes</h4>
<ul>
  <li>¿Cómo describirías tu experiencia al visualizar y gestionar la lista de clientes y sus servicios en la plataforma, y qué funcionalidades destacarías o mejorarías? </li>
  <li>¿Qué tan sencillo o complejo ha sido para ti filtrar información por estado del servicio o tipo de equipo, y qué sugerencias tendrías para mejorar esta funcionalidad?</li>
</ul>


### 6.3.2. Registro de Entrevistas.
En esta sección tenemos el análisis de las entrevistas por segmentos objetivos.

| Entrevista 1: Negocio que utiliza maquinas de refrigeración                            |                                                                                                                                                                  |
|-----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nombre Entrevistado                                 | Angelica Apaza Bocanegra                                                                                                                                                   |
| Edad                                                | 25                                                                                                                                                              |
| Profesión                                           | Venta productos coreanos                                                                                                                                               |
| Departamento                                        | Lima                                                                                                                                                             |
| Dispositivo utilizado                               | Móvil, PC                                                                                                                                                        |
| <img width=620 src="assets/chapter-05/Negocio1.PNG"/>                           | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231d149_upc_edu_pe/EfkUteJ1oStNiGwDX151iwYB12vkNL4fBVUwo8OrxsEb7A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=TuAXCY                                                                                                                                                         |
| Duración de la Entrevista                           | 0:00 - 7:08                                                                                                                                                             |
| Análisis de la Entrevista                       |                                                                                                                                                                  |
| Registro y Gestión de Equipos                      | Consideró el proceso muy sencillo y rápido. Registró sus vitrinas refrigeradas fácilmente desde el celular, resaltando que los campos solicitados eran claros y adecuados para negocios pequeños como el suyo.                                                                                                                           |
| Monitoreo y Alertas                              | Valoró mucho esta funcionalidad. En una ocasión recibió una alerta que le permitió evitar la pérdida de productos por una puerta mal cerrada. Destacó que ahora puede tomar decisiones rápidas frente a cualquier problema técnico sin esperar que los equipos fallen. |
| Solicitudes de Servicio                           | Tuvo una experiencia positiva al agendar servicio técnico. Comentó que la opción estaba bien ubicada en la plataforma y que pudo seleccionar técnicos cercanos con buenas referencias, todo desde la misma interfaz.                                        |
| Visualización de Reportes | Gracias a los reportes, identificó un consumo elevado en horarios sin actividad comercial. Esto le permitió ajustar el uso de sus equipos y prevenir problemas técnicos, destacando lo útil que sería recibir sugerencias automáticas según los datos.                                  |
| Evaluación del Servicio                  | Pudo calificar al técnico inmediatamente después del servicio, lo que le pareció práctico. Además, comentó que le fue útil poder actualizar su evaluación cuando el técnico regresó para ajustar un detalle pendiente.    |

<br><br>

| Entrevista 2: Negocio que utiliza maquinas de refrigeración                            |                                                                                                                                                                  |
|-----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nombre Entrevistado                                 | Cotrina Aguilar                                                                                                                                              |
| Edad                                                | 25                                                                                                                                                               |
| Profesión                                           | Negocio familiar de restaurante                                                                                                                                              |
| Departamento                                        | Lima                                                                                                                                                             |
| Dispositivo utilizado                               | Móvil, PC                                                                                                                                                        |
| <img width=620 src="assets/chapter-05/Negocio2.PNG"/>                                                                            | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231d149_upc_edu_pe/ER0nJN6-JHJMp3hRgrRyfaEBMxWxoLptRtd2x9RVnaMrDQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=b4aVrH                                                                                                                                                             |
| Duración de la Entrevista                           | 0:00 - 5:07                                                                                                                                                            |
| Análisis de la Entrevista                       |                                                                                                                                                                  |
| Registro y Gestión de Equipos                      | Resaltó que el registro fue rápido y sin complicaciones. Mencionó que tenía varias congeladoras, y que pudo organizarlas por ubicación sin necesidad de capacitación. Sintió que los datos solicitados eran los adecuados para tener trazabilidad de sus equipos.                                                                                                                           |
| Monitoreo y Alertas                              | Consideró esta sección como “clave”. Comentó que una de sus congeladoras mostró aumento de consumo, lo que permitió detectar acumulación de escarcha a tiempo. Valoró que puede consultar el estado del equipo sin estar físicamente frente a él. |
| Solicitudes de Servicio                           | Tuvo una experiencia positiva al pedir servicio técnico. Dijo que la plataforma le mostró técnicos cercanos con calificaciones visibles, y que pudo programar mantenimiento directamente sin tener que llamar por teléfono.                                        |
| Visualización de Reportes | Los reportes le permitieron detectar anomalías en el horario de uso. Por ejemplo, notó que un equipo funcionaba más tiempo del esperado en horas sin movimiento. Destacó que el panel le permitió ahorrar energía y evitar fallos mayores.                                   |
| Evaluación del Servicio                  | Pudo calificar al técnico tras el servicio sin salir de la plataforma. Lo consideró práctico y mencionó que luego pudo modificar su evaluación al recibir una visita de seguimiento. Para él, esto aporta transparencia y mejora la relación con los técnicos.    |

<br>

| Entrevista 3: Negocio que utiliza maquinas de refrigeración                            |                                                                                                                                                                  |
|-----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nombre Entrevistado                                 | Piero Tenorio                                                                                                                                                   |
| Edad                                                | 27                                                                                                                                                               |
| Profesión                                           | Propietaria de una cafeteria                                                                                                                                                |
| Departamento                                        | Lima                                                                                                                                                             |
| Dispositivo utilizado                               | Móvil, PC                                                                                                                                                        |
| <img width=620 src="assets/chapter-05/Negocio3.PNG"/>                           | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231d149_upc_edu_pe/EWk9jd_YyTRPutJtyAXZGHwBTMYIvwxY8ZgvW7y9S8tjMQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=iWsGGQ                                                                                                                                                            |
| Duración de la Entrevista                           | 0:00 - 7:00                                                                                                                                                            |
| Análisis de la Entrevista                       |                                                                                                                                                             |
| Registro y Gestión de Equipos                      | Describió el proceso de registro como sencillo y rápido. Registró sus dos equipos (una refrigeradora para insumos y otra para postres) usando su celular. Resaltó que los campos solicitados estaban bien definidos y que no necesitó asistencia adicional.                                                                                                                           |
| Monitoreo y Alertas                              | Valoró mucho el monitoreo en tiempo real y las alertas por cambios de temperatura. Mencionó una experiencia en la que la puerta mal cerrada de su equipo fue detectada a tiempo gracias a la alerta, lo que evitó la pérdida de productos. Destacó que ahora toma decisiones técnicas de forma más rápida y segura. |
| Solicitudes de Servicio                           | La opción de agendar servicio técnico directamente desde la plataforma le pareció clara y útil. Comentó que pudo seleccionar el equipo y elegir entre técnicos con evaluaciones visibles, todo desde un mismo panel sin necesidad de llamadas externas.                                      |
| Visualización de Reportes | Los reportes la ayudaron a detectar que una refrigeradora consumía más energía en momentos de bajo movimiento. Gracias a eso pudo ajustar su uso para mejorar la eficiencia. También identificó un problema en el motor de otra unidad que funcionaba en exceso durante la madrugada.                                 |
| Evaluación del Servicio                  | Pudo calificar al técnico de forma inmediata y desde la misma plataforma. Consideró muy útil la opción para modificar su evaluación tras una visita de seguimiento. Esta funcionalidad le dio confianza en la continuidad del servicio.  |

<br>

| Entrevista 1: Proveedores de equipos de refrigeración                            |                                                                                                                                                                  |
|-----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nombre Entrevistado                                 | Piero Medina                                                                                                                                                   |
| Edad                                                | 29                                                                                                                                                               |
| Profesión                                           | Proveedor de equipos de refrigeración                                                                                                                                                |
| Departamento                                        | Lima                                                                                                                                                             |
| Dispositivo utilizado                               | Móvil, PC                                                                                                                                                        |
| <img width=620 src="assets/chapter-05/Empresa1.PNG"/>                           |   https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231d149_upc_edu_pe/Ebz1VsZ9GplEhq0A98QWRdoBXmoA5A0WsHwa2PR_beyv_Q?e=FYGbPF&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D                                                                                                                                                          |
| Duración de la Entrevista                           | 0:00 - 7:00                                                                                                                                                         |
| Análisis de la Entrevista                       |                                                                                                                                                                  |
| Recepción y Gestión de Solicitudes                     |  El entrevistado valora la claridad de la sección de equipos, donde puede ver tipo de equipo, cliente y duración estimada. Le parece positivo poder aceptar solicitudes desde la misma pantalla. Como área de mejora, destaca la falta de detalle técnico en algunas solicitudes, lo que lo obliga a contactar al cliente directamente.                                                                                                                           |
| Gestión de Técnicos                             | Considera que el proceso de asignación de técnicos es intuitivo y funcional, pudiendo ver especialidades y ubicaciones. Sugiere mejorar la agrupación por rutas y que se incluya un ranking interno de desempeño. También valora las métricas disponibles, aunque propone añadir gráficos mensuales por técnico. |
| Historial y Reportes Técnicos                        | El entrevistado accede sin dificultad al historial de visitas, técnicos y servicios. Resalta la estructura organizada, pero propone permitir exportar en PDF o Excel. En cuanto a reportes para clientes, los considera claros, aunque recomienda agregar gráficos de consumo o temperatura. Valora la automatización del sistema de reportes y sugiere campos personalizables.                                        |
| Gestión de Cartera de Clientes | Indica que la visualización por cliente está bien organizada, incluyendo estado, facturación y servicios activos. Considera útil implementar alertas automáticas para mantenimientos periódicos. El sistema de filtros por tipo o estado de servicio funciona bien, pero con alta carga recomienda etiquetas personalizadas o carpetas por cliente.                                |
<br>

| Entrevista 2: Proveedores de equipos de refrigeración                            |                                                                                                                                                                  |
|-----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nombre Entrevistado                                 | Javier                                                                                                                                                  |
| Edad                                                | 22                                                                                                                                                              |
| Profesión                                           | Proveedor de equipos de refrigeración                                                                                                                                                |
| Departamento                                        | Lima                                                                                                                                                             |
| Dispositivo utilizado                               | Móvil, PC                                                                                                                                                        |
| <img width=620 src="assets/chapter-05/Empresa2.PNG"/>                           | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231d149_upc_edu_pe/EZbdlZxG4rNAjQkQ2V72wsUBEq3uZSySRgM0noWzbBZ4Ew?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=zlDqC0                                                                                                                                                          |
| Duración de la Entrevista                           | 0:00 - 5:59                                                                                                                                                          |
| Análisis de la Entrevista                       |                                                                                                                                                                  |
| Recepción y Gestión de Solicitudes                     | El entrevistado destaca que el panel de equipos permite una recepción rápida y clara de las solicitudes, incluyendo cliente, tipo de equipo y duración sugerida. El proceso le resulta visual y eficiente. Como área de mejora, sugiere que el formulario de solicitud obligue a incluir más detalles técnicos para evitar llamadas adicionales.                                                                                                                         |
| Gestión de Técnicos                             | Considera que el procedimiento de asignación es sencillo, especialmente por la visibilidad de especialidades dentro del módulo de técnicos. Propone como mejora la posibilidad de asignar varias visitas simultáneas por zonas geográficas. También aprecia las métricas disponibles y su impacto motivacional entre técnicos, sugiriendo agregar rankings y gráficos comparativos por mes y por tipo de equipo.|
| Historial y Reportes Técnicos                        | Utiliza con frecuencia el historial técnico de cada equipo registrado, lo cual le ha permitido evitar errores y mejorar la continuidad del servicio. Sugiere habilitar la opción de exportación en PDF. En cuanto a los reportes, los considera prácticos y bien recibidos por los clientes, aunque recomienda enriquecerlos con gráficos más visuales de consumo energético o temperatura. También sugiere personalizar los campos según cliente o servicio.                                       |
| Gestión de Cartera de Clientes | Afirma que la cartera de clientes está bien organizada dentro del panel, facilitando la consulta de facturación, servicios y tareas pendientes. Para mejorar, propone que el sistema incluya alertas automáticas para mantenimientos programados. En cuanto al filtrado de información, aunque lo considera funcional, sugiere implementar carpetas o etiquetas personalizadas para clientes con mayor volumen de órdenes activas.                                   |
<br>

| Entrevista 3: Proveedores de equipos de refrigeración                            |                                                                                                                                                                  |
|-----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nombre Entrevistado                                 | David Meneces                                                                                                                                         |
| Edad                                                | 24                                                                                                                                                             |
| Profesión                                           | Proveedor de equipos de refrigeración                                                                                                                                              |
| Departamento                                        | Lima                                                                                                                                                             |
| Dispositivo utilizado                               | Móvil, PC                                                                                                                                                        |
| <img width=1000 src="assets/chapter-05/Empresa3.PNG"/>                           | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231d149_upc_edu_pe/EX8DLH7XRRlLvDGBlGgUye0BI3cZEC9CsqqwPdiVli4sbg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=iRzKnF                                                                                                                                                            |
| Duración de la Entrevista                           | 0:00 - 16:27                                                                                                                                                         |
| Análisis de la Entrevista                       |                                                                                                                                                                  |
| Recepción y Gestión de Solicitudes                     | El entrevistado destaca que el panel de equipos permite una recepción rápida y clara de las solicitudes, incluyendo cliente, tipo de equipo y duración sugerida. El proceso le resulta visual y eficiente. Como área de mejora, sugiere que el formulario de solicitud obligue a incluir más detalles técnicos para evitar llamadas adicionales.                                                                                                                           |
| Gestión de Técnicos                             | Considera que el procedimiento de asignación es sencillo, especialmente por la visibilidad de especialidades dentro del módulo de técnicos. Propone como mejora la posibilidad de asignar varias visitas simultáneas por zonas geográficas. También aprecia las métricas disponibles y su impacto motivacional entre técnicos, sugiriendo agregar rankings y gráficos comparativos por mes y por tipo de equipo. |
| Historial y Reportes Técnicos                        | Utiliza con frecuencia el historial técnico de cada equipo registrado, lo cual le ha permitido evitar errores y mejorar la continuidad del servicio. Sugiere habilitar la opción de exportación en PDF. En cuanto a los reportes, los considera prácticos y bien recibidos por los clientes, aunque recomienda enriquecerlos con gráficos más visuales de consumo energético o temperatura. También sugiere personalizar los campos según cliente o servicio.                                       |
| Gestión de Cartera de Clientes | Afirma que la cartera de clientes está bien organizada dentro del panel, facilitando la consulta de facturación, servicios y tareas pendientes. Para mejorar, propone que el sistema incluya alertas automáticas para mantenimientos programados. En cuanto al filtrado de información, aunque lo considera funcional, sugiere implementar carpetas o etiquetas personalizadas para clientes con mayor volumen de órdenes activas.                                 |

#### 6.3.3. Evaluaciones según heurísticas

**UX Heuristics & Principles Evaluation**  
**Usability – Inclusive Design – Information Architecture**

**Información del Proyecto**
- **Carrera:** Ingeniería de Software
- **Curso:** Desarrollo de Soluciones IOT
- **Auditor:** Inteligencia Artesanal
- **Cliente:** Inteligencia Artesanal
- **Site o App a Evaluar:** OsitoPolar

---

### Tareas a Evaluar

**Para el Segmento Negocios que utilizan equipos de refrigeración:**
1. Registro y gestión de equipos
2. Monitoreo y alertas
3. Solicitudes de servicio técnico

**Para el Segmento Empresas proveedoras de servicios y equipos de refrigeración:**
1. Recepción y gestión de solicitudes
2. Visualización de historial y reportes técnicos
3. Gestión de cartera de clientes

---

### Escala de Severidad

| Nivel | Descripción |
|-------|-------------|
| 1     | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2     | Problema menor: puede ocurrir con más frecuencia o es más difícil de superar para el usuario. Debería tener una prioridad baja para resolverse en la próxima versión. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Debería tener alta prioridad para corregirse. |
| 4     | Problema muy grave: error que impide al usuario continuar utilizando la herramienta. Debe corregirse antes del lanzamiento. |

---

### Tabla Resumen

| #  | Problema                                                                                 | Escala de severidad | Heurística/Principio violado                  | Tarea evaluada                          |
|----|------------------------------------------------------------------------------------------|----------------------|----------------------------------------------|-----------------------------------------|
| 1  | El formulario de solicitud de servicio no exige detalles técnicos suficientes           | 2                    | Prevención de errores / Flexibilidad         | Recepción y gestión de solicitudes      |
| 2  | No hay exportación de reportes en PDF o Excel                                            | 2                    | Control del usuario / Flexibilidad           | Historial y reportes técnicos           |
| 3  | No se pueden modificar fácilmente rutas de técnicos asignados                            | 2                    | Flexibilidad y eficiencia de uso             | Gestión de técnicos                     |
| 4  | No hay rankings ni gráficos comparativos de desempeño técnico                            | 2                    | Visibilidad del estado del sistema           | Gestión de técnicos                     |
| 5  | No hay sugerencias automáticas en base a los reportes de consumo                         | 3                    | Ayuda y documentación / Personalización      | Visualización de reportes               |
| 6  | No se pueden crear carpetas ni etiquetas personalizadas para clientes con alta carga     | 2                    | Flexibilidad y eficiencia de uso             | Gestión de cartera de clientes          |

---

### Descripción de Problemas

**Problema #1:**
- **Tarea Evaluada:** Recepción y gestión de solicitudes
- **Recomendación:** Incorporar campos obligatorios que detallen la falla o contexto del equipo para evitar llamadas adicionales y agilizar el servicio.

**Problema #2:**
- **Tarea Evaluada:** Historial y reportes técnicos
- **Recomendación:** Añadir opción de exportación en formatos estándares para facilitar el análisis offline o la presentación a terceros.

**Problema #3:**
- **Tarea Evaluada:** Gestión de técnicos
- **Recomendación:** Incluir dashboard comparativo por técnico que muestre desempeño mensual y por tipo de equipo.

**Problema #4:**
- **Tarea Evaluada:** Visualización de reportes
- **Recomendación:** Implementar recomendaciones basadas en datos históricos y patrones detectados, para asistir en la toma de decisiones técnicas o de ahorro energético.

**Problema #5:**
- **Tarea Evaluada:** Gestión de cartera de clientes
- **Recomendación:** Activar alertas en base a ciclos de mantenimiento definidos por el proveedor o sistema.

**Problema #6:**
- **Tarea Evaluada:** Gestión de cartera de clientes
- **Recomendación:** Permitir organización avanzada con carpetas o tags personalizados según volumen o tipo de cliente.

---

### User Flows a Validar

**Para el Segmento Negocios que utilizan equipos de refrigeración:**
1. Registro de vitrinas o congeladoras
2. Gestión y visualización de alertas por temperatura
3. Solicitud y evaluación de técnicos desde la misma interfaz

**Para el Segmento Empresas proveedoras de servicios y equipos de refrigeración:**
1. Recepción detallada de solicitudes técnicas
2. Asignación eficiente de técnicos por especialidad o zona
3. Revisión de historial técnico y descarga de reportes
4. Gestión avanzada por cliente con alertas y etiquetas


## 6.4. Video About-the-Product.
En esta sección se muestra una captura del video about the product que se encuentra incrustado en el landing page, además del link en los anexos.

Video about the product: [Video about the product]()

 [//]: # (FALTA)


## Conclusiones y recomendaciones

A lo largo del desarrollo del modelo de negocio digital OsitoPolar, hemos logrado validar la necesidad real y urgente de soluciones tecnológicas en el sector de refrigeración, tanto en los negocios que dependen de estos equipos como en las empresas proveedoras de servicios técnicos.
El proceso de investigación, entrevistas y análisis ha revelado importantes hallazgos que refuerzan la relevancia de nuestra propuesta de valor.

Desde el análisis de entrevistas, logramos comprobar:
- Existe una falta generalizada de control y monitoreo sobre los equipos de refrigeración, lo cual genera pérdidas económicas importantes.
- La mayoría de los negocios revisa de manera manual el estado de sus equipos, mientras que los técnicos/empresarios trabajan con herramientas desorganizadas (WhatsApp, Excel, llamadas).
- Todos los entrevistados manifestaron interés por una solución digital que centralice la información, agilice la atención y brinde trazabilidad técnica.

Las hipótesis planteadas durante el proceso Lean UX fueron validadas:
- Los usuarios consideran útil una herramienta con alertas automáticas, historial técnico y reportes.
- Existe disposición a pagar por el servicio, siempre que el valor sea percibido claramente en ahorro de pérdidas o tiempo.
- La diferencia competitiva de OsitoPolar —automatización, trazabilidad y facilidad de uso— fue bien recibida y genera ventaja frente a competidores más rígidos o complejos.

Se logró validar las necesidades de nuestros usuarios objetivos y diseñar un producto más alineado a ellos gracias a múltiples herramientas como el User Persona, User Task Matrix, As-Is y To-Be Scenarios.
A partir de esto hemos desarrollado historias de usuario que nos servirán para tener en cuenta las funcionalidades que implementaremos en las siguientes tareas. Hemos diseñado también nuestra Landing Page y Web Aplication en herramientas de diseño colaborativas.

Algunas recomendaciones que tomamos en cuenta que podrían impulsar el desarrollo y crecimiento en el mercado de OsitoPolar son:
- Desarrollar un MVP centrado en funciones clave: alertas, historial técnico, gestión de citas y reportes.
- Realizar pruebas piloto en campo con usuarios reales antes del lanzamiento masivo.
- Consolidar alianzas con proveedores locales, para lograr una adopción más rápida y posicionar la plataforma como un estándar del sector.

Este trabajo ha demostrado que OsitoPolar no solo resuelve un problema real, sino que tiene el potencial de transformar la forma en que se gestiona la refrigeración comercial y técnica en el Perú. Los próximos pasos deberán enfocarse en escalar esta solución de manera sostenible y centrada en el usuario.



## Video About-the-Team

> **Falta:** agregar el enlace y captura del video About-the-Team. Debe resumir el proceso de trabajo del equipo, incluir testimonios de los integrantes y explicar los logros alcanzados en relación con el Student Outcome.

## Bibliografía

- Axios. (s.f.). *Axios: Promise based HTTP client for the browser and node.js*. Recuperado el 10 de julio de 2025, de https://axios-http.com/docs/intro

- Cohn, M. (s.f.). *User stories articles*. Mountain Goat Software. Recuperado el 10 de julio de 2025, de https://www.mountaingoatsoftware.com/blog/tag/user-stories

- Conventional Commits. (s.f.). *Conventional commits*. Recuperado el 10 de julio de 2025, de https://www.conventionalcommits.org/

- Google. (s.f.). *Firebase Hosting*. Recuperado el 10 de julio de 2025, de https://firebase.google.com/docs/hosting?hl=es-419

- Google. (s.f.). *Google HTML/CSS style guide*. Recuperado el 10 de julio de 2025, de https://google.github.io/styleguide/htmlcssguide.html

- Nielsen Norman Group. (s.f.). *Front-end style-guides: Definition, requirements, component checklist*. Recuperado el 10 de julio de 2025, de https://www.nngroup.com/articles/front-end-style-guides/

- Nielsen Norman Group. (s.f.). *The four dimensions of tone of voice*. Recuperado el 10 de julio de 2025, de https://www.nngroup.com/articles/tone-of-voice-dimensions/

- Nvie. (s.f.). *A successful Git branching model*. Recuperado el 10 de julio de 2025, de https://nvie.com/posts/a-successful-git-branching-model/

- Preston-Werner, T. (s.f.). *Semantic versioning 2.0.0*. Recuperado el 10 de julio de 2025, de https://semver.org/

- PrimeVue. (s.f.). *PrimeVue: The most complete UI component library for Vue.js*. Recuperado el 10 de julio de 2025, de https://primevue.org

- Render. (s.f.). *Deployments*. Recuperado el 10 de julio de 2025, de https://render.com/docs/deploys

- REST API Tutorial. (s.f.). *What is REST?*. Recuperado el 10 de julio de 2025, de https://www.restapitutorial.com/introduction/whatisrest

- RESTfulAPI.net. (s.f.). *REST API tutorial*. Recuperado el 10 de julio de 2025, de https://restfulapi.net

- Stripe. (s.f.). *Payments overview*. Recuperado el 10 de julio de 2025, de https://docs.stripe.com/payments?payments=popular

- UXPressia. (s.f.). *User vs. buyer persona: Differences and free template*. Recuperado el 10 de julio de 2025, de https://uxpressia.com/blog/user-persona-vs-buyer-persona-difference

- W3Schools. (s.f.). *HTML style guide and coding conventions*. Recuperado el 10 de julio de 2025, de https://www.w3schools.com/html/html5_syntax.asp

## Anexos

### Videos de Exposiciones

> **Falta:** ordenar aquí los enlaces de videos por entrega (AV1, TB1, AV2 y Trabajo Final), siguiendo la nomenclatura indicada en el statement.

- Organización GitHub: https://github.com/iot-proyectos
- Repositorio de la Landing Page: https://github.com/iot-proyectos/LandingPage
- Repositorio Frontend: https://github.com/iot-proyectos/OsitoPolar-Frontend
- Repositorio Backend: https://github.com/iot-proyectos/OsitoPolar-Backend
- Repositorio Mobile: https://github.com/iot-proyectos/OsitoPolar-Mobile
- Video de demostración de la Landing Page: [Video demostrativo de la landing page](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c111_upc_edu_pe/IQAeOr9bSx-2T4NJ5MMy6oFYAUG9i8dFYt45TIvlXmJ_M_I?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=DOgTz1)
- Video de exposicion AV1: [Video de exposicion AV1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u2032222001_upc_edu_pe/ESOPHU5GHEZGgBnK1e7uFVcBotVap94eOrrzWJIRhrJREQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=irIdp1)
- Video de exposicion TP: [Video de exposicion TP](https://upcedupe-my.sharepoint.com/:v:/g/personal/u2023222001_upc_edu_pe/EUSP6C-FnFZFhqELTWnDrfgBBnB-QgeehRsw6agebPFu-A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=G9ZqQ4)
- Video de exposicion AV2: [Video de exposicion AV2](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c111_upc_edu_pe/IQCHuZtyO5dITpQWo22Mfl_VAafEa-kbuvAf8CAHE5-czF0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=DllWug)
- Video de exposicion TF: [Video de exposicion TF]()
- Video about the product: [Video about the product](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202322001_upc_edu_pe/EX7h3-WbRbpNqTqMmM-NKdwBEXUEHMmcoY4pT1Q0epIOkQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9y)
