# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

Esta sección describe las herramientas, convenciones y configuraciones adoptadas por el equipo Dev-il-team para asegurar consistencia, trazabilidad y calidad del código fuente durante todo el ciclo de vida del proyecto Hera.

### 5.1.1. Software Development Environment Configuration

A continuación se listan los productos de software utilizados por el equipo, organizados por tipo de actividad del ciclo de vida. Para cada herramienta se indica su propósito y la ruta de referencia o descarga.

**Project Management**

* Trello (https://trello.com) – Gestión de tareas y seguimiento del Product Backlog y Sprint Backlog mediante tableros Kanban.

* Discord (https://discord.com) – Canal principal de comunicación sincrónica para reuniones diarias y revisiones de sprint.

* Google Meet (https://meet.google.com) – Videoconferencias para reuniones formales con el equipo.

**Requirements Management**

* Google Docs (https://docs.google.com) – Redacción colaborativa del informe, User Stories e Impact Maps.

* Miro (https://miro.com) – Elaboración de Big Picture y Design-Level Event Storming, Empathy Maps y User Journey Maps.

**Product UX/UI Design**

* Figma (https://figma.com) – Diseño de wireframes, mock-ups y prototipos interactivos de la Landing Page y la Web Application.

* Lucidchart (https://www.lucidchart.com) – Diagramas C4 de arquitectura, diagramas de clases y de base de datos.

**Software Development**

* Visual Studio Code (https://code.visualstudio.com) – IDE principal para el desarrollo frontend (HTML, CSS, JavaScript, Vue.js).

* WebStorm (https://www.jetbrains.com/webstorm) – IDE alternativo para desarrollo con Vue.js.

* Visual Studio / JetBrains Rider (https://visualstudio.microsoft.com / https://www.jetbrains.com/rider) – IDE para el desarrollo de los Web Services en ASP.NET Core.

* Node.js (https://nodejs.org) – Entorno de ejecución para las herramientas de build del frontend (Vue.js) y la Fake RESTful API (json-server).

* .NET SDK 10 (https://dotnet.microsoft.com/download) – SDK para compilar y ejecutar los Web Services (ASP.NET Core).

* HTML5 / CSS3 / JavaScript – Tecnologías base de la Landing Page estática.

* Vue.js (https://vuejs.org) – Framework del frontend de la Web Application.

* ASP.NET Core (https://learn.microsoft.com/aspnet/core) – Framework de los Web Services (Server Side).

**Software Deployment**

* GitHub Pages (https://pages.github.com) – Hosting para el despliegue de la Landing Page estática y de la Web Application (frontend).

* Proveedor de hosting en la nube para ASP.NET Core – Despliegue de los Web Services (Hera-Backend). El destino definitivo se confirma en la entrega AV2.

**Software Documentation**

* Swagger / OpenAPI (https://swagger.io) – Documentación interactiva de los endpoints de los Web Services (Services Documentation Evidence).

* Markdown + Pandoc (https://pandoc.org) – Redacción del informe en Markdown y generación del PDF mediante Pandoc/LuaLaTeX.

### 5.1.2. Source Code Management

El equipo utiliza Git como sistema de control de versiones distribuido y GitHub como plataforma de alojamiento, bajo la organización Dev-il-team. Se han creado repositorios diferenciados para cada producto del proyecto.

**Repositorios del proyecto:**

* Organización GitHub: https://github.com/Dev-il-team

* Landing Page: https://github.com/Dev-il-team/Hera-LandingPage

* Web Application (Frontend): https://github.com/Dev-il-team/Hera-Frontend

* Web Services (Server Side – ASP.NET Core): https://github.com/Dev-il-team/Hera-Backend

* Informe del Proyecto: https://github.com/Dev-il-team/upc-pre-202610-1asi0730-10215-Dev-il_team-report

El repositorio de Web Services (Hera-Backend) contiene el proyecto ASP.NET Core organizado por bounded contexts, e incorpora los proyectos de pruebas unitarias y de integración/aceptación correspondientes.

**Modelo de branching – GitFlow:**

El equipo adopta el modelo GitFlow con las siguientes ramas:

* main – Rama principal. Contiene versiones estables y listas para producción. Requiere Pull Request y revisión de al menos un integrante.

* develop – Rama de integración. Todo el desarrollo activo se integra aquí antes de pasar a producción.

* feature/\<nombre\> – Ramas de funcionalidad creadas desde develop. Ejemplos: feature/dashboard-control, feature/auth-login, feature/devices-management.

* release/\<version\> – Ramas de preparación de release para ajustes finales antes del merge a main.

* hotfix/\<nombre\> – Ramas para correcciones urgentes directamente sobre main.

**Conventional Commits:**

Se aplica el estándar Conventional Commits para mantener un historial legible y estructurado:

feat: add energy consumption chart to dashboard

fix: resolve issue with device toggle not updating state

docs: update README with deployment instructions

style: format CSS variables for theme consistency

refactor: extract device card into reusable component

Se aplica Semantic Versioning (SemVer) para los releases: MAJOR.MINOR.PATCH. La versión inicial del entregable corresponde a v1.0.0.

### 5.1.3. Source Code Style Guide & Conventions

El equipo establece las siguientes convenciones de codificación por tecnología para garantizar uniformidad y mantenibilidad:

**HTML / CSS (Landing Page):**

* Referencia: Google HTML/CSS Style Guide.

* Indentación: 2 espacios (sin tabs).

* Atributos HTML en minúsculas; comillas dobles para valores de atributos.

* Nomenclatura de clases CSS: kebab-case (ejemplo: hero-section, btn-primary, nav-links).

* Variables CSS definidas en :root para colores, fuentes y espaciados del Design System de Hera.

**JavaScript / Vue.js (Web Application):**

* Referencias: Vue.js Style Guide (reglas de prioridad A y B) y Google JavaScript Style Guide.

* Componentes con nombres en PascalCase y multipalabra (ejemplo: DeviceCard.vue, EnergyChart.vue).

* Variables y funciones en camelCase; constantes en UPPER\_SNAKE\_CASE.

* Uso de ESLint + Prettier para linting y formateo automático; indentación de 2 espacios.

* Estructura de carpetas por feature/bounded context, separando components, views, services y assets.

**C# / ASP.NET Core (Web Services):**

* Referencia: Microsoft C# Coding Conventions.

* PascalCase para clases, métodos, propiedades y namespaces; camelCase para variables locales y parámetros; \_camelCase para campos privados.

* Métodos asíncronos con sufijo Async; uso de file-scoped namespaces y una clase por archivo.

* Organización por bounded contexts siguiendo Domain-Driven Design (Domain, Application, Infrastructure, Interfaces).

**Git / Control de versiones:**

* Nombres de ramas en inglés con kebab-case: feature/device-management, fix/energy-chart-bug.

* Commits en inglés siguiendo Conventional Commits.

* Pull Requests deben incluir descripción del cambio, capturas de pantalla y referencia al Issue/Story.

### 5.1.4. Software Deployment Configuration

A continuación se describen los pasos de despliegue, desde el repositorio hasta la publicación, para cada producto del proyecto.

**Landing Page (Hera-LandingPage – GitHub Pages):**

1. Se integran las features en develop mediante Pull Request y revisión cruzada.

2. Se realiza el merge de develop a main.

3. GitHub Pages detecta automáticamente el push a main y publica el contenido estático.

4. URL de producción: https://dev-il-team.github.io/Hera-LandingPage/

**Web Application / Frontend (Hera-Frontend – GitHub Pages):**

1. Se integran las features en develop mediante Pull Request y revisión cruzada.

2. Se genera el build de producción con `npm run build`, configurando la variable de entorno con la URL de la API.

3. Se publica el directorio de salida (dist) en GitHub Pages mediante el merge a main.

4. La aplicación consume la Fake RESTful API definida en el archivo .env.

**Web Services (Hera-Backend – ASP.NET Core):**

1. Se integran las features en develop mediante Pull Request y revisión cruzada.

2. Se compila y publica el proyecto con `dotnet publish -c Release`.

3. Se despliega el artefacto en el proveedor de hosting en la nube, configurando la cadena de conexión a la base de datos y las variables de entorno.

4. La documentación de los endpoints queda disponible mediante Swagger/OpenAPI. La primera versión desplegada se entrega en AV2.
