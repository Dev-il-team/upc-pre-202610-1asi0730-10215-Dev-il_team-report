## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

A continuación se presenta la planificación del primer Sprint del proyecto Hera, cuyo objetivo principal fue el desarrollo de la Landing Page y los componentes base de la Web Application.

**Sprint Planning Background**

| Campo | Detalle |
| :---- | :---- |
| Fecha | 07/04/2026 |
| Hora | 20:00 (GMT-5) *(confirmar)* |
| Lugar | Reunión remota por Discord |
| Preparado por | Molina Falcón, Piero Leonardo (Scrum Master) |
| Asistentes | Molina Falcón, Piero; Gutarra Velapatiño, Sebastián; Tello Quispe, Luis; Alfaro Coveñas, Louis; Durán Santander, Emilia |

**Resumen del Review del Sprint anterior:** No aplica. El Sprint 1 corresponde al primer sprint del proyecto.

**Resumen de la Retrospective del Sprint anterior:** No aplica. El Sprint 1 corresponde al primer sprint del proyecto.

| Sprint \# | Sprint 1 |
| :---- | :---- |
| Fecha de inicio | 08/04/2026 |
| Fecha de fin | 21/04/2026 |
| Sprint Goal | Desarrollar e implementar la Landing Page pública del producto Hera con soporte bilingüe (ES/EN) y los componentes base del dashboard de la Web Application. |
| Velocity | 28 Story Points |
| Sum of Story Points | 28 Story Points |

#### 5.2.1.2. Aspect Leaders and Collaborrators

| Team Member (Last Name, First Name) | GitHub Username | Aspect Name 1 (L/C) |
| ----- | ----- | ----- |
| Molina, Piero | PieroMFAL | L |
| Alfaro. Louis | LouisAlfaro | C |
| Tello, Luis | luistello1739-web | C |
| Gutarra, Sebastián | SebastianGutarra | C |
| Durán, Emilia | emiliadurans | C |

#### 5.2.1.3. Sprint Backlog 1

El Sprint Backlog del Sprint 1 incluye las siguientes User Stories priorizadas para esta iteración:

| Story ID | Título | Descripción | Horas Est. |
| :---- | :---- | :---- | :---- |
| US-01 | Ver panel de control | Como usuario quiero ver todos mis dispositivos en el dashboard | 5h |
| US-02 | Control de iluminación | Como usuario quiero encender/apagar luces remotamente | 4h |
| US-03 | Monitoreo de seguridad | Como usuario quiero recibir alertas de movimiento detectado | 6h |
| US-04 | Landing page pública | Como visitante quiero conocer los servicios de Hera | 8h |
| US-05 | Registro de usuario | Como usuario nuevo quiero crear una cuenta en la plataforma | 5h |

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

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

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
| Alfaro Coveñas, Louis Piero | 10 | Web App – DeviceCard, Layout base |
| Durán Santander, Emilia Mercedes | 7 | Web App – EnergyChart, mock data |

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

A continuación se presenta la planificación del siguiente Sprint del proyecto Hera, cuyo objetivo principal fue el desarrollo del resto del frontend y el consumo de datos mediante una fake API. 

**Sprint Planning Background**

| Campo | Detalle |
| :---- | :---- |
| Fecha | 06/05/2026 |
| Hora | 20:00 (GMT-5) *(confirmar)* |
| Lugar | Reunión remota por Discord |
| Preparado por | Molina Falcón, Piero Leonardo (Scrum Master) |
| Asistentes | Molina Falcón, Piero; Gutarra Velapatiño, Sebastián; Tello Quispe, Luis; Alfaro Coveñas, Louis; Durán Santander, Emilia |

**Resumen del Review del Sprint 1:** Se presentó la Landing Page desplegada en GitHub Pages con soporte bilingüe (ES/EN) y las secciones Hero, Servicios, Beneficios, Planes y Contacto, además de los componentes base del frontend. Los entregables fueron aceptados por el equipo. *(Ampliar con el feedback registrado en la reunión.)*

**Resumen de la Retrospective del Sprint 1:** *(Por completar con el equipo: qué salió bien, qué se debe mejorar y las acciones de mejora acordadas para el Sprint 2.)*

| Sprint \# | Sprint 2 |
| ----- | ----- |
| Fecha de inicio | 07/05/2026 |
| Fecha de fin | 13/05/2026 |
| Sprint Goal | Desarrollar e implementar cada sección del frontend del proyecto Hera, su consumo de datos y muestre gráficos a partir de ello. |
| Velocity | 30 Story Points |
| Sum of Story Points | 30 Story Points |

#### 5.2.2.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | Aspect Name 1 (L/C) |
| ----- | ----- | ----- |
| Molina, Piero | PieroMFAL | L |
| Alfaro. Louis | LouisAlfaro | C |
| Tello, Luis | luistello1739-web | C |
| Gutarra, Sebastián | SebastianGutarra | C |
| Durán, Emilia | emiliadurans | C |

#### 5.2.2.3. Sprint Backlog 2

El Sprint Backlog del Sprint 2 incluye las siguientes User Stories priorizadas para esta iteración:

| Story ID | Título | Descripción | Horas Est. |
| ----- | ----- | ----- | ----- |
| US-16 | Visualización de panel de control (Dashboard) | Como propietario del hogar, deseo visualizar un resumen del estado de mi casa en tiempo real para tomar decisiones rápidas. | 7h |
| US-18 | Monitoreo visual de cámaras | Como nuevo usuario, deseo acceder a la transmisión de mis cámaras de seguridad para ver el estado de mi mascota desde el trabajo. | 3h |
| US-20 | Notificaciones de alerta de seguridad | Como propietario del hogar, deseo recibir alertas visuales en la plataforma para reaccionar ante posibles riesgos detectados por los sensores. | 3h |
| US-24 | Visualización de automatizaciones | Como propietario del hogar, deseo listar todas mis rutinas programadas para recordar qué procesos se ejecutan solos. | 4h |
| US-28 | Resumen numérico de consumo | Como nuevo usuario, deseo visualizar una estimación de mi consumo energético del mes para tener noción de mi gasto. | 5h |

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