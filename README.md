<!-- Carátula -->

<div align="center">
    <img src="./logo-upc.png">
</div>

<div align="center">

# Universidad Peruana de Ciencias Aplicadas

## Carrera de Ingeniería de Software

</div>

<div align="center"> 

**Ciclo:** 2026 - 1  
**Curso:** Aplicaciones Web<br>
**NRC:** 12144<br>
**Docente:** Efraín Ricardo Bautista Ubillús

## "Informe del trabajo final"
**Startup:** safetrack<br>
**Producto:** locksight


## Relacion de integrantes:


| Código      | Nombre                              |
|-------------|-------------------------------------|
| U201819276  | Bardales Tejada, Luis Alexis        |
| U202416276  | Higa Kohatsue, Alonso Enrique       |
| U202412903  | Lozano Quispe, Fabricio Jofred      |
| U202418645  | Sandoval Aiquipa, Kelver Yamir      |
| U202414356  | Vite Celis, Rodrigo Matias          |

<div style="font-weight: bold;"> Abril, 2026</div>

</div>

## Registro de Versiones del Informe

| Versión | Fecha    | Autor       | Descripción de Modificación            |
| ------- | -------- | ----------- | -------------------------------------- |
| 0.1     | 00/04/26 | Bardales Tejada, Luis Alexis    | Desarrollo de la Estructura del informe |
| 0.1    | 00/04/26 | Higa Kohatsue, Alonso Enrique | Desarrollo de la Estructura del informe|
| 0.1    | 10/04/26 | Lozano Quispe, Fabricio Jofred | Desarrollar de la estructura del informe |
| 0.1    | 00/04/26 | Sandoval Aiquipa, Kelver Yamir | Desarrollo de la Estructura del informe|
| 0.1    | 10/04/26 | Vite Celis, Rodrigo Matias | Desarrollo de la Estructura del informe|



## Project Report Collaboration Insights

| URL de la organización del proyecto | URL del repositorio del reporte   |
| :------------------: | :---------------------------: | 
|  |  |

| URL del repositorio de la landing page |
| :----------------------------: | 
|  | 



**URL LANDING PAGE DESPLEGADO**:


Commits del Report:

## CONTENIDO

### Tabla de contenido
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivos](#13-segmentos-objetivos)
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
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-n)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)



# **Student Outcomes**



# Capítulo I: Introducción

## 1.1. Startup Profile

## 3.2. User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con |
|----------------|--------|-------------|--------------------------|-----------------| 
| US01 | Visualizar ubicación del vehículo en tiempo real | Como persona natural, deseo ver la ubicación actual de mi vehículo en el mapa del dashboard para mantener control sobre su seguridad. | **Given** que el vehículo está registrado y conectado <br> **When** accede al inicio o a "Estado en Vivo" <br> **Then** el sistema muestra la ubicación actual del vehículo en el mapa con la etiqueta "Actualizado hace X seg" <br><br> **Given** que el vehículo pierde señal <br> **When** consulta la ubicación <br> **Then** se muestra la última ubicación disponible y el estado de señal GPS | Epic 01 |
| US02 | Consultar estado general del vehículo | Como persona natural, deseo revisar el estado general del vehículo desde la pantalla de inicio para saber si está activo, seguro y conectado. | **Given** que el vehículo está vinculado <br> **When** accede al dashboard de inicio <br> **Then** se muestra la tarjeta con "Vehículo: Activo", ubicación, batería del dispositivo y estado de seguridad <br><br> **Given** cambios recientes en el estado <br> **When** se actualiza el sistema <br> **Then** refleja el cambio más reciente con timestamp | Epic 01 |
| US03 | Revisar historial de rutas | Como persona natural, deseo consultar rutas pasadas filtrando por fecha para revisar los trayectos realizados por mi vehículo. | **Given** que existen rutas registradas <br> **When** accede a "Historial de Rutas" y selecciona una fecha <br> **Then** muestra el mapa con el trayecto, puntos de inicio y fin, hora, distancia parcial y total, duración y total de recorridos <br><br> **Given** rutas con eventos <br> **When** visualiza el historial <br> **Then** muestra fecha, hora, trayecto y distancia total del día | Epic 01 |
| US04 | Configurar geocerca | Como persona natural, deseo definir una geocerca desde la sección de configuración para recibir alertas si mi vehículo sale del perímetro. | **Given** que el usuario define un perímetro en el mapa <br> **When** el vehículo sale del área <br> **Then** genera alerta visible en "Alertas de Seguridad" con tipo y ubicación <br><br> **Given** que la geocerca ya está activa <br> **When** se modifica el área <br> **Then** el sistema guarda los cambios y aplica la nueva geocerca | Epic 02 |
| US05 | Recibir alerta de seguridad | Como persona natural, deseo recibir alertas categorizadas en la sección "Alertas de Seguridad" para reaccionar ante eventos como movimiento sospechoso o GPS manipulado. | **Given** que se detecta actividad sospechosa <br> **When** el sistema la procesa <br> **Then** aparece en la lista de alertas con tipo (movimiento sospechoso, GPS manipulado, velocidad excedida), ubicación y hora <br><br> **Given** que una alerta fue emitida <br> **When** revisa el panel <br> **Then** muestra filtros por "Todas", "No leídas" y "Urgentes" y permite ver detalle | Epic 02 |
| US06 | Activar defensa automática | Como persona natural, deseo que el sistema ejecute acciones automáticas ante amenazas confirmadas como activar el "Modo seguro auto" desde configuración. | **Given** que el modo seguro automático está habilitado en Configuración > Seguridad <br> **When** se detecta una amenaza confirmada <br> **Then** el sistema ejecuta la acción de defensa (bloqueo de motor u otra) <br><br> **Given** que la defensa fue ejecutada <br> **When** revisa el historial de eventos <br> **Then** registra resultado, tipo de acción y hora | Epic 02 |
| US07 | Bloquear vehículo remotamente | Como persona natural, deseo bloquear el motor de mi vehículo desde el botón "Bloquear Vehículo" en el dashboard o desde "Acciones Rápidas" para actuar ante una emergencia. | **Given** que el vehículo está conectado <br> **When** presiona "Bloquear Vehículo" en el inicio o en Estado en Vivo <br> **Then** el sistema envía el comando de bloqueo al dispositivo IoT y confirma la ejecución <br><br> **Given** que el bloqueo fue enviado <br> **When** el dispositivo lo recibe <br> **Then** actualiza el estado del vehículo a bloqueado en el panel | Epic 02 |
| US08 | Reportar robo desde la app | Como persona natural, deseo reportar el robo de mi vehículo desde la acción rápida "Reportar robo" para activar el protocolo de emergencia de forma inmediata. | **Given** que el usuario selecciona "Reportar robo" en Acciones Rápidas <br> **When** confirma la acción <br> **Then** el sistema registra el reporte, activa alertas prioritarias y notifica <br><br> **Given** que el reporte fue generado <br> **When** consulta el panel <br> **Then** muestra el incidente activo con estado y hora | Epic 02 |
| US09 | Compartir ubicación del vehículo | Como persona natural, deseo compartir la ubicación en tiempo real de mi vehículo desde "Acciones Rápidas" para coordinación con terceros o autoridades. | **Given** que el usuario selecciona "Compartir ubicación" <br> **When** confirma <br> **Then** genera un enlace o notificación con la ubicación actual del vehículo <br><br> **Given** que la ubicación fue compartida <br> **When** el destinatario accede <br> **Then** ve la posición actualizada del vehículo | Epic 02 |
| TS10 | Registrar evento de telemetría mediante API | Como developer, deseo registrar eventos de telemetría vía API para almacenar datos GPS/IoT del dispositivo en el Telemetry Store. | **Given** que el payload enviado es válido <br> **When** se realiza POST a /telemetry <br> **Then** el sistema registra el evento en el Telemetry Store <br><br> **Given** que el payload es inválido <br> **When** se procesa la solicitud <br> **Then** devuelve error de validación con detalle | Epic 05 |
| US11 | Visualizar flota completa | Como supervisor, deseo ver todos los vehículos de la flota desde el panel web para tener una visión general del estado de cada unidad. | **Given** que existen múltiples vehículos registrados <br> **When** accede al panel de flota <br> **Then** muestra todas las unidades con estado, ubicación y última actualización <br><br> **Given** que una unidad cambia de estado <br> **When** se actualiza <br> **Then** refleja el cambio en tiempo real en la vista de flota | Epic 03 |
| US12 | Monitorear vehículos en tiempo real | Como supervisor, deseo ver las ubicaciones actuales de todos los vehículos en un mapa para gestionar operaciones de forma eficiente. | **Given** que los vehículos están conectados <br> **When** accede al mapa de monitoreo <br> **Then** muestra las ubicaciones actuales de todos los vehículos <br><br> **Given** que un vehículo pierde conexión <br> **When** el supervisor revisa <br> **Then** muestra la última ubicación conocida con indicador de sin señal | Epic 03 |
| US13 | Detectar desvíos de ruta | Como supervisor, deseo recibir alertas cuando un vehículo se desvíe de la ruta asignada para tomar acción inmediata. | **Given** que una ruta fue definida para el vehículo <br> **When** el vehículo se desvía del trayecto <br> **Then** genera alerta de desvío con ubicación y hora <br><br> **Given** que el vehículo continúa fuera de ruta <br> **When** el supervisor monitorea <br> **Then** registra el incidente como evento activo | Epic 03 |
| US14 | Recibir alertas de paradas prolongadas | Como supervisor, deseo detectar paradas largas no programadas para identificar incidentes operativos o de seguridad. | **Given** que un vehículo permanece detenido más tiempo del umbral configurado <br> **When** el sistema lo detecta <br> **Then** genera alerta de parada prolongada con ubicación y duración <br><br> **Given** que el vehículo retoma el movimiento <br> **When** ocurre <br> **Then** actualiza el estado y cierra la alerta de parada | Epic 03 |
| US15 | Analizar comportamiento de manejo | Como supervisor, deseo analizar el comportamiento de conducción de cada vehículo para identificar patrones riesgosos y generar reportes de hábitos. | **Given** que existen datos de telemetría disponibles <br> **When** accede al módulo de analítica <br> **Then** muestra métricas de velocidad, frenadas, aceleración y score de conducción <br><br> **Given** que se detectan patrones riesgosos <br> **When** el sistema los procesa <br> **Then** registra los eventos y los incluye en el reporte de hábitos | Epic 03 |
| US16 | Consultar reportes operativos | Como supervisor, deseo ver reportes históricos de operaciones para tomar decisiones basadas en datos de la flota. | **Given** que existen datos históricos registrados <br> **When** solicita un reporte con rango de fechas <br> **Then** genera reporte con rutas, alertas, distancias y comportamiento de conductores <br><br> **Given** que el reporte está listo <br> **When** consulta <br> **Then** muestra los datos estructurados exportables | Epic 03 |
| US17 | Gestionar vehículos de la flota | Como supervisor, deseo agregar, editar o desactivar vehículos dentro de la plataforma para mantener actualizado el inventario de la flota. | **Given** que el supervisor ingresa los datos del vehículo (placa, modelo, flota asignada) <br> **When** guarda el registro <br> **Then** el vehículo aparece disponible en el panel de flota <br><br> **Given** que desea desactivar una unidad <br> **When** cambia su estado <br> **Then** la unidad deja de aparecer en el monitoreo activo | Epic 03 |
| US18 | Asignar dispositivo IoT a vehículo | Como supervisor, deseo asignar un dispositivo IoT a un vehículo de la flota para activar el monitoreo de telemetría. | **Given** que el dispositivo IoT tiene un número serial registrado <br> **When** el supervisor lo asigna a un vehículo <br> **Then** el sistema vincula el dispositivo y comienza a recibir telemetría <br><br> **Given** que el dispositivo ya está asignado a otro vehículo <br> **When** intenta reasignarlo <br> **Then** muestra advertencia y solicita confirmación | Epic 03 |
| US19 | Configurar reglas de alerta para flota | Como supervisor, deseo definir reglas de alerta personalizadas por tipo (geocerca, velocidad, interferencia GPS) para adaptar la detección a las necesidades operativas. | **Given** que el supervisor accede al módulo de reglas de alerta <br> **When** define el tipo de regla, umbral y vehículos afectados <br> **Then** el sistema guarda la regla y la aplica en tiempo real <br><br> **Given** que una regla ya existe <br> **When** se modifica o deshabilita <br> **Then** los cambios se aplican sin afectar otras reglas activas | Epic 03 |
| US20 | Bloquear motor de vehículo de flota remotamente | Como supervisor, deseo enviar un comando de bloqueo de motor a cualquier unidad de la flota desde el panel web ante una emergencia confirmada. | **Given** que el supervisor selecciona un vehículo y ejecuta "Bloquear Motor" <br> **When** el comando es enviado <br> **Then** el Telemetry Gateway entrega la orden al dispositivo IoT y confirma la ejecución <br><br> **Given** que el comando fue ejecutado <br> **When** revisa el registro <br> **Then** aparece el comando con estado, resultado y hora | Epic 03 |
| TS21 | Obtener datos de ubicación mediante API | Como developer, deseo consultar la ubicación de un vehículo vía API para integraciones y visualizaciones externas. | **Given** que el vehículo existe y está registrado <br> **When** se realiza GET /vehicles/{id}/location <br> **Then** devuelve lat, lng, velocidad, timestamp y calidad de señal <br><br> **Given** que el vehículo no existe <br> **When** se consulta <br> **Then** devuelve error controlado 404 | Epic 05 |
| US22 | Navegación por la landing page | Como visitante, deseo navegar por las secciones de la landing page (Home, About Us, How does it work, FAQs, Contact) para conocer el producto antes de registrarme. | **Given** que el visitante accede a la landing page <br> **When** navega por el menú de navegación <br> **Then** cada sección carga correctamente mostrando su contenido sin recargar la página <br><br> **Given** que el visitante cambia de sección <br> **When** hace scroll o usa el menú <br> **Then** mantiene continuidad visual y navegación fluida | Epic 04 |
| US23 | Acceder a la aplicación desde la landing page | Como visitante, deseo ingresar a la aplicación desde los botones "Login" o "Get Started" de la landing page para comenzar a usar el servicio. | **Given** que el visitante está en la landing page <br> **When** selecciona "Login" o "Get Started" <br> **Then** es redirigido a la pantalla de acceso o registro de la aplicación <br><br> **Given** que el visitante completa el acceso <br> **When** autentica correctamente <br> **Then** es llevado al dashboard principal | Epic 04 |
| US24 | Registrarse en la plataforma | Como visitante, deseo registrarme como nuevo usuario seleccionando mi tipo de perfil (Persona Natural, Empresa, Gobierno) para acceder a las funcionalidades correspondientes. | **Given** que el visitante completa el formulario con datos válidos y selecciona tipo de usuario <br> **When** envía el registro <br> **Then** el sistema crea la cuenta y redirige al dashboard correspondiente <br><br> **Given** que los datos son inválidos o el correo ya existe <br> **When** procesa el formulario <br> **Then** muestra error de validación específico por campo | Epic 04 |
| US25 | Contactar al equipo desde la landing page | Como visitante, deseo enviar un mensaje al equipo de soporte desde el formulario de contacto de la landing page para resolver dudas antes de suscribirme. | **Given** que el visitante completa el formulario (nombre, teléfono, email, tipo de usuario, mensaje) <br> **When** presiona "Send Message" <br> **Then** el sistema registra la solicitud y muestra confirmación de envío <br><br> **Given** que hay datos faltantes o formato inválido <br> **When** envía <br> **Then** muestra error de validación por campo | Epic 04 |
| US26 | Ver sección "How does it work" en landing page | Como visitante, deseo ver la explicación de cómo funciona GOD's Tracker para cada segmento (Persona Natural, Empresas, Entidades Gubernamentales) para entender el valor del producto. | **Given** que el visitante accede a la sección "How does it work" <br> **When** la página carga <br> **Then** muestra los tres segmentos con descripción de beneficios diferenciados <br><br> **Given** que navega entre segmentos <br> **When** interactúa <br> **Then** el contenido relevante se muestra sin recargar la página | Epic 04 |
| US27 | Ver sección de preguntas frecuentes (FAQs) | Como visitante, deseo acceder a la sección de preguntas frecuentes para resolver dudas comunes sobre GOD's Tracker antes de registrarme. | **Given** que el visitante accede a la sección FAQs <br> **When** selecciona una pregunta del acordeón <br> **Then** se despliega la respuesta correspondiente <br><br> **Given** que el visitante ya visualizó una respuesta <br> **When** selecciona otra pregunta <br> **Then** colapsa la anterior y expande la nueva | Epic 04 |
| TS28 | Cambiar idioma de la landing page | Como developer, deseo implementar el cambio de idioma (ES/EN) en la landing page para servir a usuarios en diferentes idiomas. | **Given** que la landing soporta múltiples idiomas <br> **When** el visitante cambia el idioma desde el selector ES/EN <br> **Then** toda la landing carga en el idioma seleccionado <br><br> **Given** que el idioma solicitado no está disponible <br> **When** se solicita <br> **Then** mantiene el idioma por defecto (ES) | Epic 04 |
| TS29 | Procesar envío de alertas mediante API | Como developer, deseo procesar y disparar alertas vía API para que el sistema de notificaciones pueda entregarlas en tiempo real. | **Given** que ocurre un evento crítico (interferencia GPS, velocidad excedida, desvío) <br> **When** se realiza POST /alerts <br> **Then** el sistema procesa la alerta y la encola para notificación push <br><br> **Given** que la solicitud es inválida <br> **When** se procesa <br> **Then** devuelve error controlado con detalle | Epic 05 |
| TS30 | Autenticación de usuarios mediante API | Como developer, deseo implementar autenticación JWT para controlar el acceso a los endpoints protegidos de la plataforma. | **Given** que el usuario envía credenciales válidas <br> **When** realiza POST /auth/login <br> **Then** el sistema devuelve token JWT con rol y permisos <br><br> **Given** que las credenciales son incorrectas <br> **When** se procesa la solicitud <br> **Then** rechaza el acceso con error 401 | Epic 05 |
| TS31 | Manejo de errores en el sistema | Como developer, deseo que el sistema gestione errores internos de forma controlada para garantizar disponibilidad y trazabilidad. | **Given** que ocurre un error interno en el backend <br> **When** se produce la falla <br> **Then** el sistema registra el error con trazabilidad en los logs <br><br> **Given** que el error afecta la respuesta al cliente <br> **When** devuelve la respuesta <br> **Then** incluye mensaje de error controlado sin exponer datos sensibles | Epic 05 |
| US32 | Ver resumen de alertas del día en dashboard | Como persona natural, deseo ver en el dashboard el contador de alertas del día, recorridos realizados, señal GPS y nivel de batería del dispositivo para tener un resumen rápido del estado. | **Given** que el usuario accede al inicio <br> **When** la pantalla carga <br> **Then** muestra las 4 tarjetas de resumen: "Alertas hoy", "Recorridos", "Señal GPS" y "Batería" con valores actuales <br><br> **Given** que los datos cambian durante el día <br> **When** se actualizan <br> **Then** los contadores reflejan los valores más recientes automáticamente | Epic 01 |
| US33 | Filtrar alertas de seguridad por categoría y período | Como persona natural, deseo filtrar las alertas en la sección "Alertas de Seguridad" por tipo (Todas, No leídas, Urgentes) y período (Última hora, Hoy, 7 días, 30 días) para revisar solo las relevantes. | **Given** que existen alertas registradas <br> **When** selecciona un filtro de tipo o período <br> **Then** la lista se actualiza mostrando solo las alertas que coinciden con los criterios <br><br> **Given** que no hay alertas en el filtro seleccionado <br> **When** aplica el filtro <br> **Then** muestra mensaje de "Sin alertas en este período" | Epic 02 |
| US34 | Ver detalle de alerta de seguridad | Como persona natural, deseo ver el detalle de una alerta de seguridad (tipo, ubicación, descripción, hora) para decidir si bloquear el vehículo o ignorarla. | **Given** que existe una alerta en la lista <br> **When** presiona "Ver Detalle" <br> **Then** muestra tipo de alerta, ubicación exacta, descripción del evento y hora de ocurrencia <br><br> **Given** que la alerta tiene acción disponible <br> **When** visualiza el detalle <br> **Then** ofrece botón de "Bloquear Vehículo" directamente desde el detalle | Epic 02 |
| US35 | Gestionar configuración de notificaciones | Como persona natural, deseo activar o desactivar notificaciones (alertas de seguridad, ubicación en tiempo real, recordatorios de mantenimiento) desde la sección de Configuración para personalizar mis avisos. | **Given** que el usuario accede a Configuración > Notificaciones <br> **When** activa o desactiva un toggle <br> **Then** el sistema guarda la preferencia y aplica el cambio inmediatamente <br><br> **Given** que la notificación está desactivada <br> **When** ocurre el evento correspondiente <br> **Then** el sistema no genera push para ese tipo | Epic 01 |
| US36 | Configurar opciones de seguridad del dispositivo | Como persona natural, deseo activar o desactivar opciones de seguridad (movimiento sospechoso, apaga motor, modo seguro auto) desde Configuración > Seguridad para definir cómo reacciona el sistema ante amenazas. | **Given** que el usuario accede a Configuración > Seguridad <br> **When** activa un toggle de seguridad (ej. "Modo seguro auto") <br> **Then** el sistema guarda la regla y la aplica en el monitoreo <br><br> **Given** que la opción "Apaga Motor" está activa <br> **When** se confirma una amenaza <br> **Then** el sistema envía el comando de bloqueo al dispositivo IoT automáticamente | Epic 02 |
| US37 | Editar perfil y cambiar contraseña | Como persona natural, deseo editar mi perfil (nombre, email) y cambiar mi contraseña desde la sección Configuración > Cuenta para mantener mis datos actualizados. | **Given** que el usuario accede a Configuración > Cuenta <br> **When** presiona "Editar perfil" <br> **Then** puede modificar nombre y email y guardar los cambios <br><br> **Given** que presiona "Cambiar contraseña" <br> **When** ingresa la contraseña actual y la nueva <br> **Then** el sistema actualiza la contraseña y solicita reautenticación | Epic 01 |
| US38 | Cambiar idioma y tema de la aplicación | Como persona natural, deseo cambiar el idioma (ES/EN) y el tema (Claro/Oscuro) desde Configuración > Otros para adaptar la app a mis preferencias. | **Given** que el usuario accede a Configuración > Otros <br> **When** cambia el idioma o el tema <br> **Then** la aplicación aplica el cambio de forma inmediata en toda la interfaz <br><br> **Given** que reinicia la aplicación <br> **When** vuelve a ingresar <br> **Then** mantiene las preferencias guardadas | Epic 01 |
| US39 | Ver información del dispositivo IoT vinculado | Como persona natural, deseo ver la información del dispositivo IoT vinculado a mi vehículo (estado, modelo, IMEI) desde Configuración > Dispositivo para verificar que está operativo. | **Given** que el dispositivo está asignado al vehículo <br> **When** accede a Configuración > Dispositivo <br> **Then** muestra estado (Activo/Inactivo), modelo y IMEI del dispositivo <br><br> **Given** que el dispositivo está desconectado <br> **When** consulta <br> **Then** muestra estado "Inactivo" con última fecha de conexión | Epic 01 |
| US40 | Reiniciar dispositivo IoT remotamente | Como persona natural, deseo reiniciar el dispositivo IoT vinculado a mi vehículo desde Configuración > Dispositivo para resolver problemas de conectividad sin intervención presencial. | **Given** que el dispositivo está vinculado y activo <br> **When** presiona "Reiniciar Dispositivo" y confirma <br> **Then** el sistema envía el comando de reinicio al dispositivo IoT <br><br> **Given** que el reinicio se completa <br> **When** el dispositivo se reconecta <br> **Then** actualiza su estado a "Activo" en la configuración | Epic 02 |
| US41 | Buscar vehículo por nombre o placa | Como persona natural o supervisor, deseo buscar un vehículo usando la barra de búsqueda en la parte superior de la app para localizarlo rápidamente entre múltiples unidades. | **Given** que el usuario escribe en la barra "Buscar Vehículo" <br> **When** ingresa nombre o placa <br> **Then** el sistema filtra y muestra los vehículos que coinciden con el criterio <br><br> **Given** que no existe coincidencia <br> **When** realiza la búsqueda <br> **Then** muestra mensaje de "Ningún vehículo encontrado" | Epic 01 |
| US42 | Ver plan y estado de suscripción | Como persona natural, deseo ver mi plan actual (Básico, Pro, etc.) y el estado de mi dispositivo (Conectado/Desconectado) desde el panel lateral para saber qué funcionalidades tengo disponibles. | **Given** que el usuario accede a la app <br> **When** visualiza el panel lateral inferior <br> **Then** muestra nombre de usuario, plan activo y estado del dispositivo <br><br> **Given** que el plan ha expirado o cambiado <br> **When** consulta <br> **Then** muestra el plan actualizado con opción de mejora | Epic 04 |
| US43 | Cerrar sesión de la aplicación | Como persona natural o supervisor, deseo cerrar sesión desde el menú lateral de la app o desde Configuración > Cuenta para proteger el acceso en dispositivos compartidos. | **Given** que el usuario presiona "Cerrar Sesión" en el menú lateral o en configuración <br> **When** confirma la acción <br> **Then** el sistema invalida la sesión y redirige a la pantalla de login <br><br> **Given** que la sesión expiró por inactividad <br> **When** intenta usar la app <br> **Then** redirige automáticamente al login con mensaje de sesión expirada | Epic 01 |
| TS44 | Gestionar asignación de dispositivos IoT mediante API | Como developer, deseo implementar los endpoints de asignación y desasignación de dispositivos IoT a vehículos para gestionar el ciclo de vida de los trackers. | **Given** que se envía un serial de dispositivo válido y un vehicle_id existente <br> **When** se realiza POST /devices/assign <br> **Then** el sistema crea el registro en device_assignments con fecha de asignación <br><br> **Given** que se desasigna el dispositivo <br> **When** se realiza DELETE /devices/assign/{id} <br> **Then** el sistema registra la fecha de unassigned_at y libera el dispositivo | Epic 05 |
| TS45 | Consultar reportes de conducción mediante API | Como developer, deseo exponer un endpoint para consultar driving_reports por vehículo y período para que el frontend pueda renderizar los análisis de comportamiento. | **Given** que el vehículo tiene reportes de conducción generados <br> **When** se realiza GET /vehicles/{id}/driving-reports con rango de fechas <br> **Then** devuelve lista de reportes con period_start, period_end, driving_score, summary y metrics_json <br><br> **Given** que no existen reportes en el período <br> **When** se consulta <br> **Then** devuelve lista vacía con código 200 | Epic 05 |

