## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

A continuación se presenta la planificación del primer Sprint del proyecto Hera, cuyo objetivo principal fue el desarrollo de la Landing Page pública del producto.

**Sprint Planning Background**

| Campo | Detalle |
| :---- | :---- |
| Fecha | 07/04/2026 (martes) |
| Hora | 10:00 p.m. (GMT-5) |
| Lugar | Reunión remota por Discord |
| Preparado por | Molina Falcón, Piero Leonardo (Scrum Master) |
| Asistentes | Molina Falcón, Piero; Gutarra Velapatiño, Sebastián; Tello Quispe, Luis; Alfaro Coveñas, Louis; Durán Santander, Emilia |

**Resumen del Review del Sprint anterior:** No aplica. El Sprint 1 corresponde al primer sprint del proyecto.

**Resumen de la Retrospective del Sprint anterior:** No aplica. El Sprint 1 corresponde al primer sprint del proyecto.

| Sprint \# | Sprint 1 |
| :---- | :---- |
| Fecha de inicio | 08/04/2026 |
| Fecha de fin | 21/04/2026 |
| Sprint Goal | Desarrollar e implementar la Landing Page pública del producto Hera con soporte bilingüe (ES/EN). |
| Velocity | 13 Story Points |
| Sum of Story Points | 13 Story Points |

#### 5.2.1.2. Aspect Leaders and Collaborrators

| Team Member (Last Name, First Name) | GitHub Username | Aspect Name 1 (L/C) |
| ----- | ----- | ----- |
| Molina, Piero | PieroMFAL | L |
| Alfaro. Louis | LouisAlfaro | C |
| Tello, Luis | luistello1739-web | C |
| Gutarra, Sebastián | SebastianGutarra | C |
| Durán, Emilia | emiliadurans | C |

#### 5.2.1.3. Sprint Backlog 1

El Sprint Backlog del Sprint 1 se enfocó exclusivamente en la Landing Page pública. Cada User Story se descompone en work-items/tasks con su estimación, responsable y estado:

| User Story | SP | Work-Item / Task | Descripción | Est. (h) | Assigned To | Status |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| US01 – Visualizar propuesta de valor | 2 | US01-T1 | Maquetar la sección Hero con la propuesta de valor y el CTA principal | 3 | Molina, Piero | Done |
| | | US01-T2 | Aplicar el Design System y el diseño responsive al Hero | 2 | Molina, Piero | Done |
| US04 – Visualizar beneficios de integración | 2 | US04-T1 | Implementar la sección de Beneficios con tarjetas | 3 | Tello, Luis | Done |
| | | US04-T2 | Estilizar y hacer responsive la sección de Beneficios | 2 | Tello, Luis | Done |
| US02 – Consultar planes de suscripción | 1 | US02-T1 | Maquetar la sección de Planes (Básico/Premium) | 2 | Gutarra, Sebastián | Done |
| | | US02-T2 | Estilizar la comparativa de planes y adaptarla a Mobile | 2 | Gutarra, Sebastián | Done |
| US03 – Internacionalización de contenido | 3 | US03-T1 | Implementar el sistema i18n (ES/EN) en JavaScript vanilla | 4 | Alfaro, Louis | Done |
| | | US03-T2 | Integrar el toggle de idioma en la barra de navegación | 2 | Alfaro, Louis | Done |
| US05 – Soporte de accesibilidad básica | 5 | US05-T1 | Aplicar atributos de accesibilidad (alt, aria, contraste de color) | 3 | Durán, Emilia | Done |
| | | US05-T2 | Revisión responsive y corrección de problemas de usabilidad | 3 | Durán, Emilia | Done |

#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1 se realizaron los siguientes commits representativos en los repositorios del proyecto:

| Repositorio | Branch | Commit Message | Fecha |
| :---- | :---- | :---- | :---- |
| Hera-LandingPage | feature/hero-section | feat: add hero section with bilingual toggle | 10/04/2026 |
| Hera-LandingPage | feature/services-section | feat: implement services cards with hover effects | 12/04/2026 |
| Hera-LandingPage | feature/plans-section | feat: add pricing plans with ES/EN support | 14/04/2026 |
| Hera-LandingPage | main | chore: deploy landing page v1.0.0 to GitHub Pages | 18/04/2026 |

#### 5.2.1.5. Execution Evidence for Sprint Review

Durante este sprint se completaron exitosamente los siguientes entregables:

* Landing Page desplegada en producción: https://dev-il-team.github.io/Hera-LandingPage/

* La Landing Page incluye las secciones: Hero, Servicios, Beneficios, Planes y Contacto, con soporte bilingüe completo.

* Sistema de internacionalización (i18n) implementado en JavaScript vanilla sin librerías externas.

* Repositorios organizados bajo la organización Dev-il-team en GitHub con estructura GitFlow activa.

URL LANDING PAGE: [https://dev-il-team.github.io/Hera-LandingPage/](https://dev-il-team.github.io/Hera-LandingPage/)

\includegraphics[width=\linewidth]{assets/landing1.PNG}

\includegraphics[width=\linewidth]{assets/landing2.PNG}

\includegraphics[width=\linewidth]{assets/landing3.PNG}

\includegraphics[width=\linewidth]{assets/landing4.PNG}

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

| Nombre de Endpoint | Acciones Implementadas | Sintaxis de llamada | Especificación de parámetros | Explicación del Response |
| ----- | ----- | ----- | ----- | ----- |
| services | GET | var response \= await axios.get(\`${ServicesAPI}\`) | Se necesita la creacion de .env con la URL de la API | Se retorna toda la informacion de la API. |

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

El despliegue del Sprint 1 se realizó de la siguiente manera:

**Landing Page – GitHub Pages:**

* Se realizó merge de la rama develop a main en el repositorio Hera-LandingPage.

* GitHub Pages detecta automáticamente el push a main y despliega el contenido estático.

* URL: https://dev-il-team.github.io/Hera-LandingPage/

#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el Sprint 1 el equipo Dev-il-team mantuvo la siguiente dinámica de colaboración:

* Reuniones diarias de 15 minutos (stand-up) mediante Discord para sincronizar avances y resolver bloqueos.

* Tablero de Trello actualizado diariamente: To Do / In Progress / Done.

* 2 sesiones de Code Review mediante Pull Requests en GitHub con comentarios y aprobaciones cruzadas.

* Todos los integrantes realizaron commits al repositorio, evidenciando participación activa en el sprint.

* Decisiones técnicas documentadas en el canal \#decisions del servidor Discord del equipo.

| Integrante | Commits (Sprint 1\) | Area de contribucion |
| :---- | :---- | :---- |
| Molina Falcon, Piero Leonardo | 12 | Landing Page – Hero, Nav, Footer |
| Gutarra Velapatiño, Sebastián Ernesto | 9 | Landing Page – Servicios, Planes |
| Tello Quispe, Luis Germán | 8 | Landing Page – Beneficios, Contacto |
| Alfaro Coveñas, Louis Piero | 10 | Landing Page – Suscripción/CTA, i18n |
| Durán Santander, Emilia Mercedes | 7 | Landing Page – Responsive, Accesibilidad |

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

A continuación se presenta la planificación del siguiente Sprint del proyecto Hera, cuyo objetivo principal fue el desarrollo del resto del frontend y el consumo de datos mediante una fake API. 

**Sprint Planning Background**

| Campo | Detalle |
| :---- | :---- |
| Fecha | 06/05/2026 (miércoles) |
| Hora | 9:00 p.m. (GMT-5) |
| Lugar | Reunión remota por Discord |
| Preparado por | Molina Falcón, Piero Leonardo (Scrum Master) |
| Asistentes | Molina Falcón, Piero; Gutarra Velapatiño, Sebastián; Tello Quispe, Luis; Alfaro Coveñas, Louis; Durán Santander, Emilia |

**Resumen del Review del Sprint 1:** Se presentó la Landing Page desplegada en GitHub Pages con soporte bilingüe (ES/EN) y las secciones Hero, Servicios, Beneficios, Planes y Contacto. Los entregables fueron aceptados por el equipo.

**Resumen de la Retrospective del Sprint 1:** Queda pendiente añadir el video About the Team e integrar con el frontend (CTA). Para el siguiente sprint, deberemos dedicar más tiempo al planning de desarrollo y reservar tiempo específicamente para realizar los arreglos correspondientes en el informe.

| Sprint \# | Sprint 2 |
| ----- | ----- |
| Fecha de inicio | 07/05/2026 |
| Fecha de fin | 13/05/2026 |
| Sprint Goal | Desarrollar e implementar las secciones del frontend del proyecto Hera, su consumo de datos mediante la fake API y la visualización de gráficos a partir de ellos. |
| Velocity | 26 Story Points |
| Sum of Story Points | 26 Story Points |

#### 5.2.2.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | Aspect Name 1 (L/C) |
| ----- | ----- | ----- |
| Molina, Piero | PieroMFAL | L |
| Alfaro. Louis | LouisAlfaro | C |
| Tello, Luis | luistello1739-web | C |
| Gutarra, Sebastián | SebastianGutarra | C |
| Durán, Emilia | emiliadurans | C |

#### 5.2.2.3. Sprint Backlog 2

El Sprint Backlog del Sprint 2 se enfocó en el frontend de la Web Application y su consumo de datos mediante la fake API. Cada User Story se descompone en work-items/tasks con su estimación, responsable y estado:

| User Story | SP | Work-Item / Task | Descripción | Est. (h) | Assigned To | Status |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| US16 – Visualización de panel de control | 5 | US16-T1 | Implementar la vista Dashboard con el resumen del estado del hogar | 4 | Molina, Piero | Done |
| | | US16-T2 | Consumir la fake API (axios) y poblar el dashboard en tiempo real | 3 | Molina, Piero | Done |
| US18 – Monitoreo visual de cámaras | 8 | US18-T1 | Implementar la vista de cámaras y la reproducción del stream | 5 | Durán, Emilia | Done |
| | | US18-T2 | Integrar los datos de cámaras desde la fake API | 3 | Durán, Emilia | Done |
| US20 – Notificaciones de alerta de seguridad | 5 | US20-T1 | Implementar el panel de notificaciones de alertas de seguridad | 3 | Tello, Luis | Done |
| | | US20-T2 | Filtrar por tipo de alerta y consumir desde la fake API | 3 | Tello, Luis | Done |
| US24 – Visualización de automatizaciones | 3 | US24-T1 | Implementar el listado de rutinas/automatizaciones | 3 | Gutarra, Sebastián | Done |
| | | US24-T2 | Consumir las automatizaciones desde la fake API | 2 | Gutarra, Sebastián | Done |
| US28 – Resumen numérico de consumo | 5 | US28-T1 | Implementar la vista de resumen de consumo energético | 3 | Alfaro, Louis | Done |
| | | US28-T2 | Graficar el consumo y consumir los datos desde la fake API | 3 | Alfaro, Louis | Done |

#### 5.2.2.4. Development Evidence for Sprint Review

Durante el Sprint 2 se realizaron los siguientes commits representativos en los repositorios del proyecto:

| Repositorio | Branch | Commit Message | Fecha |
| ----- | ----- | ----- | ----- |
| Hera-Frontend | wip/frontend | feat(shared): add navbar, home and routing | 13/05/2026 |
| Hera-Frontend | wip/frontend | feat: add dependencies and fake api | 13/05/2026 |
| Hera-Frontend | feature/dev | feat: implement devices CRUD with axios and json-server | 13/05/2026 |
| Hera-Frontend | feature/dev | feat(us16): implement real-time dashboard view | 13/05/2026 |

####  5.2.2.5. Execution Evidence for Sprint Review

Durante este sprint se completaron exitosamente los siguientes entregables:

• El frontend de toda la página de Hera desplegada en producción.

• Implementar las operaciones CRUD, consumo de API y presentación de dichos datos.

• Sistema de internacionalización (i18n) implementado en JavaScript vanilla sin librerías externas.

• Repositorios organizados bajo la organización Dev-il-team en GitHub con estructura GitFlow activa.

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

| Nombre de Endpoint | Acciones Implementadas | Sintaxis de llamada | Especificación de parámetros | Explicación del Response |
| ----- | ----- | ----- | ----- | ----- |
| services | GET | var response \= await axios.get(\`${ServicesAPI}\`) | Se necesita la creacion de .env con la URL de la API | Se retorna toda la informacion de la API. |

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

El despliegue del Sprint 2 se realizó de la siguiente manera:

#### 5.2.2.8. Team Collaboration Insights during Sprint

Durante el Sprint 2 el equipo Dev-il-team mantuvo la siguiente dinámica de colaboración:

• Reuniones diarias de 15 minutos (stand-up) mediante Discord para sincronizar avances y resolver bloqueos.

• Tablero de Trello actualizado diariamente: To Do / In Progress / Done.

• 2 sesiones de Code Review mediante Pull Requests en GitHub con comentarios y aprobaciones cruzadas.

• Todos los integrantes realizaron commits al repositorio, evidenciando participación activa en el sprint.

• Decisiones técnicas documentadas en el canal \#decisions del servidor Discord del equipo.

| Integrante | Commits (Sprint 2\) | Area de contribucion |
| ----- | ----- | ----- |
| Molina Falcon, Piero Leonardo | 9 | Devices |
| Gutarra Velapatiño, Sebastián Ernesto | 5 | Automation |
| Tello Quispe, Luis Germán | 5 | Devices IOT |
| Alfaro Coveñas, Louis Piero | 6 | Shared |
| Durán, Emilia | 9 | Develop |

### 5.2.3. Sprint 3

### 5.2.3.1. Sprint Planning 3

| Sprint # | Sprint 3 |
| :--- | :--- |
| **Fecha de inicio** | 15/05/2026 |
| **Fecha de fin** | 15/06/2026 |
| **Sprint Goal** | Desarrollar, implementar y desplegar los servicios RESTful API del backend en C# (ASP.NET Core), asegurando la seguridad con JWT y logrando la integración completa con la aplicación web en Vue.js. |
| **Velocity** | 21 Story Points |
| **Sum of Story Points** | 21 Story Points |

### 5.2.3.3. Sprint Backlog 3

| Story ID | Título | Descripción | Horas Est. |
| :--- | :--- | :--- | :--- |
| US-35 | Seguridad de API con Token JWT | Como Developer, deseo implementar un endpoint de login que devuelva un JWT para proteger las transacciones entre Frontend y Backend. | 8h |
| US-36 | Endpoint GET de dispositivos | Como Developer, deseo construir un endpoint GET que devuelva el array de dispositivos en formato JSON para que el Frontend lo consuma. | 5h |
| US-37 | Endpoint POST para registrar hardware | Como Developer, deseo crear un endpoint POST que inserte nuevos dispositivos en la base de datos validando los campos obligatorios. | 5h |
| US-38 | Endpoint PATCH de cambio de estado | Como Developer, deseo habilitar un endpoint PATCH ligero que solo modifique el valor booleano de "encendido/apagado" de un equipo específico. | 4h |
| US-40 | Endpoint DELETE para borrar dispositivo | Como Developer, deseo exponer un endpoint DELETE que elimine definitivamente el hardware de la base de datos relacional. | 3h |

### 5.2.3.4. Development Evidence for Sprint Review

| Repositorio | Branch | Commit Message | Fecha |
| :--- | :--- | :--- | :--- |
| Hera-Backend | feature/auth-jwt | feat(auth): implement JWT bearer authentication middleware | 22/05/2026 |
| Hera-Backend | feature/devices | feat(api): add GET and POST endpoints for IoT devices | 28/05/2026 |
| Hera-Backend | feature/devices | feat(api): implement PATCH and DELETE operations for devices | 02/06/2026 |
| Hera-Frontend | feature/api | refactor: replace json-server with real backend endpoints | 10/06/2026 |

### 5.2.3.7. Software Deployment Evidence for Sprint Review

Durante este sprint se realizó el despliegue en Netlify, configurando los recursos necesarios para hospedar los componentes del proyecto: Landing Page, Web Application y Web Services. El objetivo fue preparar el entorno en la nube para permitir la integración y ejecución del backend, así como el acceso público a la aplicación desde el navegador.

El frontend (Landing Page y Web Application) fue desplegado exitosamente utilizando Netlify, aprovechando su integración continua con la rama `main` de nuestro repositorio en GitHub. Por otro lado, los servicios RESTful API desarrollados en C# fueron alojados en un servicio en la nube (ej. Azure App Services / Render), configurando las variables de entorno para la conexión a la base de datos de producción y los secretos de JWT.

A continuación mostraremos las imágenes como evidencia del deployment realizado en este sprint:

`[Insertar captura de pantalla del dashboard de Netlify con el deploy exitoso]`

`[Insertar captura de pantalla de la API subida a la nube respondiendo a un request (ej. Postman o Swagger UI público)]`

### 5.2.3.8. Team Collaboration Insights during Sprint

Durante el Sprint 3, enfocado en el backend y la integración, el equipo mantuvo la siguiente dinámica de colaboración:

*   Sincronización diaria mediante nuestro canal de Discord para reportar problemas de CORS y formato de JSONs entre el frontend y backend.
*   Gestión de tareas en Trello, moviendo los tickets de endpoints desde *In Progress* hasta *Testing* y *Done*.
*   Revisión de código rigurosa mediante Pull Requests, exigiendo al menos una aprobación antes de fusionar ramas de características (`feature/*`) a `develop`.

| Integrante | Commits (Sprint 3) | Area de contribucion |
| :--- | :--- | :--- |
| Molina Falcón, Piero Leonardo | 8 | Frontend API Integration, Netlify |
| Alfaro Coveñas, Louis Piero | 12 | Backend Architecture, JWT Auth |
| Tello Quispe, Luis German | 10 | Database scripts, Controllers |
| Gutarra Velapatiño, Sebastián | 7 | Backend Endpoints, Swagger |
| Duran Emilia | 6 | Frontend bugfixes, Validation |
