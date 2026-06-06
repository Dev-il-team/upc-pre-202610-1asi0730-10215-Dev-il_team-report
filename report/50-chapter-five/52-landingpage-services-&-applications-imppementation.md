## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

A continuación se presenta la planificación del primer Sprint del proyecto Hera, cuyo objetivo principal fue el desarrollo de la Landing Page y los componentes base de la Web Application.

| Sprint \# | Sprint 1 |
| :---- | :---- |
| Fecha de inicio | 08/04/2026 |
| Fecha de fin | 21/04/2026 |
| Sprint Goal | Desarrollar e implementar la Landing Page pública del producto Hera con soporte bilingüe (ES/EN) y los componentes base del dashboard de la Web Application. |
| Velocity | 28 Story Points |
| Sum of Story Points | 28 Story Points |

#### 5.2.1.2. Aspect Leaders and Collaborrators

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
| hera-landing-page | feature/hero-section | feat: add hero section with bilingual toggle | 10/04/2026 |
| hera-landing-page | feature/services-section | feat: implement services cards with hover effects | 12/04/2026 |
| hera-landing-page | feature/plans-section | feat: add pricing plans with ES/EN support | 14/04/2026 |
| hera-landing-page | main | chore: deploy landing page v1.0.0 to GitHub Pages | 18/04/2026 |

#### 5.2.1.5. Execution Evidence for Sprint Review

Durante este sprint se completaron exitosamente los siguientes entregables:

* Landing Page desplegada en producción: https://dev-il-team.github.io/hera-landing-page

* La Landing Page incluye las secciones: Hero, Servicios, Beneficios, Planes y Contacto, con soporte bilingüe completo.

* Sistema de internacionalización (i18n) implementado en JavaScript vanilla sin librerías externas.

* Repositorios organizados bajo la organización Dev-il-team en GitHub con estructura GitFlow activa.

URL LANDING PAGE: [https://dev-il-team.github.io/Hera-LandingPage/](https://dev-il-team.github.io/Hera-LandingPage/)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

El despliegue del Sprint 1 se realizó de la siguiente manera:

**Landing Page – GitHub Pages:**

* Se realizó merge de la rama develop a main en el repositorio hera-landing-page.

* GitHub Pages detecta automáticamente el push a main y despliega el contenido estático.

* URL: https://dev-il-team.github.io/hera-landing-page

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
| Integrante 2 | 9 | Landing Page – Servicios, Planes |
| Integrante 3 | 8 | Landing Page – Beneficios, Contacto |
| Integrante 4 | 10 | Web App – DeviceCard, Layout base |
| Integrante 5 | 7 | Web App – EnergyChart, mock data |