## <a name="_heading=h.rl921vfr5x5t"></a>**5.1. Software Configuration Management**
  Esta sección describe las herramientas, convenciones y configuraciones adoptadas por el equipo Dev-il-team para asegurar consistencia, trazabilidad y calidad del código fuente durante todo el ciclo de vida del proyecto Hera.
   
 ### <a name="_heading=h.wciwa96dqhjz"></a>**5.1.1. Software Development Environment Configuration**
A continuación se listan los productos de software utilizados por cada integrante del equipo para el desarrollo, diseño, gestión y despliegue del proyecto:
      
 ### <a name="_heading=h.sxm29qydtv5w"></a>**5.1.2. Source Code Management**
**Project Management**

•       Trello (https://trello.com) – Gestión de tareas y seguimiento del Product Backlog mediante tableros Kanban.

•       Discord – Canal principal de comunicación sincrónica para reuniones diarias y revisiones de sprint.

•       Google Meet – Videoconferencias para reuniones formales con el equipo.


**Requirements Management**

•       Google Docs – Redacción colaborativa del informe, User Stories e Impact Maps.

•       Miro (https://miro.com) – Elaboración de Event Storming, Empathy Maps y User Journey Maps.

 

**Product UX/UI Design**

•       Figma (https://figma.com) – Diseño de wireframes, mockups y prototipos interactivos de la Landing Page y Web Application.

•       LucidChart – Diagramas de arquitectura, clases y base de datos.

 

**Software Development**

•       Visual Studio Code (https://code.visualstudio.com) – IDE principal para desarrollo frontend (HTML, CSS, JavaScript).

•       WebStorm (https://www.jetbrains.com/webstorm) – IDE alternativo para desarrollo Vue.js.

•       HTML5 / CSS3 – Tecnologías base para la Landing Page estática.

 

**Software Deployment**

•       GitHub Pages (https://pages.github.com) – Hosting para el despliegue de la Landing Page estática.
      
### <a name="_heading=h.entremi3v14m"></a>**5.1.3. Source Code Style Guide & Conventions**
El equipo utiliza Git como sistema de control de versiones distribuido y GitHub como plataforma de alojamiento de repositorios. Se han creado repositorios diferenciados para cada componente del proyecto.

 

**Repositorios del proyecto:**

•       Organización GitHub: https://github.com/Dev-il-team

•       Landing Page: https://github.com/Dev-il-team/hera-landing-page

•       Web Application (Frontend): https://github.com/Dev-il-team/hera-frontend

•       Informe del Proyecto: https://github.com/Dev-il-team/hera-report

 

**Modelo de branching – GitFlow:**

El equipo adopta el modelo GitFlow con las siguientes ramas:

 

•       main – Rama principal. Contiene versiones estables y listas para producción. Requiere Pull Request y revisión de al menos un integrante.

•       develop – Rama de integración. Todo el desarrollo activo se integra aquí antes de pasar a producción.

•       feature/\<nombre\> – Ramas de funcionalidad creadas desde develop. Ejemplos: feature/dashboard-control, feature/auth-login, feature/energy-reports.

•       release/\<version\> – Ramas de preparación de release para ajustes finales antes del merge a main.

•       hotfix/\<nombre\> – Ramas para correcciones urgentes directamente sobre main.

 

**Conventional Commits:**

Se aplica el estándar Conventional Commits para mantener un historial legible y estructurado:

 

feat: add energy consumption chart to dashboard

fix: resolve issue with device toggle not updating state

docs: update README with deployment instructions

style: format CSS variables for theme consistency

refactor: extract device card into reusable component

 

Se aplica Semantic Versioning (SemVer) para los releases: MAJOR.MINOR.PATCH. La versión inicial del entregable corresponde a v1.0.0.
      
### <a name="_heading=h.ogohwao3lwy5"></a>**5.1.4. Software Deployment Configuration**
El equipo establece las siguientes convenciones de codificación para garantizar uniformidad y mantenibilidad:

 

**HTML / CSS (Landing Page):**

•       Referencia: Google HTML/CSS Style Guide.

•       Indentación: 2 espacios (sin tabs).

•       Atributos HTML en minúsculas; comillas dobles para valores de atributos.

•       Nomenclatura de clases CSS: kebab-case (ejemplo: hero-section, btn-primary, nav-links).

•       Variables CSS definidas en :root para colores, fuentes y espaciados del Design System de Hera.

 

**Git / Control de versiones:**

•       Nombres de ramas en inglés con kebab-case: feature/device-management, fix/energy-chart-bug.

•       Commits en inglés siguiendo Conventional Commits.

•       Pull Requests deben incluir descripción del cambio, capturas de pantalla y referencia al Issue/Story.