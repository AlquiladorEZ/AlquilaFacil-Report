# Capítulo V: Product Implementation

## 5.1. Software Configuration Management

<div align="justify">
En la siguiente sección, detallaremos las herramientas, convenciones, referencias y configuraciones empleadas a lo largo del desarrollo del proyecto, que contribuyeron a mantener la consistencia en el trabajo realizado. 
</div>

### 5.1.1. Software Development Environment Configuration

<div align="justify">
En este apartado, se mencionarán los distintos productos de software empleados por el equipo de desarrollo.
<br><br>

**Project Management**

* **Microsoft 365:** [https://www.office.com/](https://www.office.com/)  
Microsoft 365 es una plataforma web que facilita la creación de documentos para compartir y editar de forma conjunta. Se utilizó para designar, organizar y hacer un seguimiento de las actividades de trabajo, así como para establecer plazos de entrega.

* **Google Meet:** [https://meet.google.com/](https://meet.google.com/)  
Google Meet es una plataforma de videoconferencias que permite realizar videollamadas con múltiples participantes y programar sesiones de trabajo. Se usó como herramienta para llevar a cabo las reuniones del equipo.

**Requirements Management**

* **Trello:** [https://trello.com/](https://trello.com/)  
Es un software de gestión de proyectos, que facilita la asignación y organización de las tareas a realizar. Fue utilizado para el Product Backlog.

**Product UX/UI Design**

* **UXPressia:** [https://uxpressia.com/](https://uxpressia.com/)  
Es una herramienta en línea que permite a los equipos de trabajo identificar y comprender los problemas, necesidades y comportamiento del usuario en relación con la solución de software que se está desarrollando mediante el uso de plantillas. Se usó para la elaboración de los User Personas, Empathy Maps, Journey Maps e Impact Maps.

* **Figma:** [https://www.figma.com/](https://www.figma.com/)  
Figma es una herramienta de edición gráfica, en donde se puede diseñar y prototipar páginas web y aplicaciones de manera colaborativa. Se utilizó para crear los wireframes, mock-ups y los desktop and mobile application prototype del proyecto.

**Software Development**

* **Web Services**  
Para los servicios web, se empleó .NET junto al framework ASP.NET Core. La arquitectura implementada fue basada en RESTful API, permitiendo una comunicación eficiente y segura entre la aplicación móvil y el backend.

**Software Documentation**

* **Vertabelo:** [https://vertabelo.com/](https://vertabelo.com/)  
Es una herramienta online que facilita el diseño, creación y gestión de bases de datos de manera colaborativa. Se usó para diseñar la base de datos del proyecto.

* **LucidChart:** [https://lucid.app/](https://lucid.app/)  
LucidChart es una plataforma que cuenta con opciones para la creación de diagramas, mapas mentales, flujos, con el uso de plantillas y tableros con edición en tiempo real. Fue utilizado en el desarrollo del diagrama de clases UML, así como los Wireflows y User Flows.

* **Structurizr:** [https://www.structurizr.com/](https://www.structurizr.com/)  
Es una plataforma que permite modelado de diagramas de arquitectura de software por medio de código. Structurizr fue utilizado para crear el modelo C4 del proyecto.
</div>


### 5.1.2. Source Code Management

<div align="justify">

Para el desarrollo y gestión del proyecto, fue creada una organización mediante GitHub, donde se registró todas las modificaciones realizadas a lo largo de su ciclo de vida. Fue estructurado de la siguiente manera:

* **Organization:** [Ver Organización](https://github.com/AlquiladorEZ)  
* **Backend Repository:** [Ver Backend Repository](https://github.com/AlquiladorEZ/AlquilaFacil-BackEnd)
* **Report Repository:** [Ver Report Repository](https://github.com/AlquiladorEZ/AlquilaFacil-Report)
* **Frontend Repository:** [Ver Frontend Repository](https://github.com/AlquiladorEZ/AlquilaFacil-FrontEnd)
* **LandingPage Repository:** [Ver LandingPage Repository](https://github.com/AlquiladorEZ/AlquilaFacil-LandingPage)
* **MobileApp Repository:** [Ver MobileApp Repository](https://github.com/AlquiladorEZ/AlquilaFacil-MobileApp)

Por otra parte, para controlar de manera efectiva los cambios en el código de la aplicación y gestionar las ramas por cada repositorio, se ha implementado **GitFlow** para definir y estructurar nuestro flujo de trabajo. Esto involucra la creación de dos ramas principales:

- **main:** También denominada "master", es la rama donde se encuentra la versión más estable del proyecto que va a pasar a producción.
- **develop:** Es la rama donde se integra el contenido de las features. Va paralela al main.

**Ramas auxiliares:**

- **feature:** Son las ramas donde se desarrollan las funcionalidades del proyecto. Luego de completarlas, se fusionan con la rama develop.  
  El formato de nomenclatura usado para las ramas ha sido el siguiente: `feature/feature-name`. Aquí, "feature" indica la rama y "feature-name" el nombre de la funcionalidad que se está desarrollando.

- **release:** Son las ramas donde se prepara la próxima versión del programa. En esta, se realizan las pruebas finales y se corrigen pequeños errores antes del lanzamiento definitivo. Finalizado este proceso, los cambios se fusionan con la rama develop, y luego a la rama main.

</div>

### 5.1.3. Source Code Style Guide & Conventions

1. **General Naming & Language Convention**
- **Language**: English
- **Case Styles**:
  - `camelCase`: for variables, functions, methods (JavaScript, Dart).
  - `PascalCase`: for classes, interfaces, components (C#, Vue, Dart).
  - `kebab-case`: for file names, HTML/CSS class names.
  - `UPPER_SNAKE_CASE`: for constants.
- **Avoid**: abbreviations, underscores in identifiers, non-descriptive names.


2. **Landing Page (HTML, CSS, JavaScript)**

**HTML:**
- **Guide**: [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)
- Use semantic HTML5 tags (`<header>`, `<section>`, `<article>`, `<footer>`, `<body>`).
- Use `alt`, `title`, `aria-*` attributes for accessibility.
- Use double quotes (`"`) for attribute values.
- Indent using 1 tab.

**CSS:**
- **Guide**: [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)
- Use BEM methodology for class naming: `block__element--modifier`.
- Avoid `!important`.
- Use CSS variables and consistent units (`rem`, `em`, `%`).
- Separate layout (`grid`, `flex`) and theme-related styles.

**JavaScript:**
- **Guides**: 
  - [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)
  - [MDN JavaScript Guidelines](https://developer.mozilla.org/en-US/docs/MDN/Guidelines)
- Use `const` and `let`.
- Prefer arrow functions.
- Functions/methods should be `camelCase`.
- One statement per line.
- Always use `===` and avoid implicit coercion.


3. **Backend (C# with ASP.NET Core)**

**C#:**
- **Guide**: [Microsoft C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- Classes, methods, and properties in `PascalCase`.
- Local variables and parameters in `camelCase`.
- Use dependency injection, no magic strings.
- Organize using Clean Architecture or Layered Architecture.
- Group using statements and avoid unnecessary namespaces.

**ASP.NET Core:**
- **Guide**: [ASP.NET Core Best Practices](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/best-practices?view=aspnetcore-9.0)
- Use `I` prefix for interfaces (`IUserService`).
- Use `async`/`await` for all asynchronous operations.
- Controllers: `PascalCase`, suffix with `Controller`.
- Endpoints: RESTful naming (`GET /api/users/{id}`).
- DTOs in `PascalCase`.


4. **Mobile App (Flutter with Dart)**

**Dart & Flutter:**
- **Guide**: [Effective Dart](https://dart.dev/guides/language/effective-dart/style)
- Class names: `PascalCase`.
- Variables, functions: `camelCase`.
- Use `const` where possible.
- Widget tree must be readable and split into components.
- File names: `snake_case.dart`.


5. **Web App (Vue.js)**

**Vue.js:**
- **Guide**: [Vue 3 Style Guide](https://vuejs.org/style-guide/)
- Components in `PascalCase`.
- Props and events: `camelCase` in script, `kebab-case` in templates.
- Files in `kebab-case.vue`.
- Use `<script setup>` if working with Composition API.
- Store logic in `services/` or `composables/`.
- Use Vue Router with modular structure.


6. **Gherkin (.feature files)**

**Feature Files:**
- **Guide**: [Gherkin Conventions](https://cucumber.io/docs/gherkin/reference/)
- File names in `snake_case.feature`.
- Use keywords: `Feature`, `Scenario`, `Given`, `When`, `Then`, `And`, `But`.
- Avoid implementation details; focus on behavior.
- Use meaningful names for scenarios.


### 5.1.4. Software Deployment Configuration

<div align="justify">

Esta sección describe el proceso de configuración y despliegue del software, utilizando las herramientas principales que hemos integrado en nuestro flujo de trabajo: GitHub para el control de versiones y Postman para la verificación de las API antes y después del despliegue.

**GitHub - Control de Versiones y Flujo de Trabajo**

GitHub es la herramienta central para el control de versiones y la gestión del código en el proyecto. Utilizamos el enfoque de branching basado en GitFlow para garantizar un ciclo de desarrollo ordenado y controlado.

**Postman - Pruebas y Verificación de API**

Utilizamos Postman para verificar y validar las API en el backend antes de realizar el despliegue en producción. La configuración de las colecciones y entornos de Postman nos permite automatizar y estructurar estas pruebas:

**Colecciones de Pruebas**

Se crean colecciones específicas en Postman que contienen todas las solicitudes de las API utilizadas en el proyecto (ej. reservas, usuarios, gestión de vehículos).  
Cada colección contiene solicitudes GET, POST, PUT y DELETE correspondientes a cada recurso del sistema.

**Variables de Entorno**

Entorno de desarrollo y entorno de producción están configurados como variables en Postman. Esto permite realizar pruebas en múltiples entornos cambiando fácilmente entre ellos.

**Pruebas Automatizadas**

Las colecciones de Postman están configuradas con scripts de pruebas automatizadas que verifican la correcta respuesta de las APIs (códigos de estado HTTP, formatos de respuesta JSON, validación de parámetros, etc.).  
Las pruebas automatizadas se ejecutan localmente antes de realizar el despliegue en GitHub para asegurar la estabilidad del backend.

</div>


## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

<div align="justify">
En esta sección se muestran los tasks que se realizaron en cada sprint respectivo y se adjunta una captura en Trello del avance hasta dicho sprint y el link del tablero.
</div>

<br>

**Enlace del Trello:** https://trello.com/b/MGs17EpK/product-backlog-dise%C3%B1o-de-experimentos-de-ingenier%C3%ADa-de-software

<br>

<div align="justify">
  
***Sprint 01:***

**Evidencia en Trello:**

![Artefacto creado en Trello](Resources/Sprint%20Backlog/Sprint%20Evidence-1.png)

**Sprint Backlog 01:**

<table align="center">
  <thead>
    <tr>
       <td colspan="2" align="center"><strong>Sprint #</strong></td>
       <td colspan="5" align="center"><strong>User Story</strong></td>
    </tr>
    <tr>
       <td colspan="2" align="center"><strong>Sprint 1</strong></td>
       <td colspan="5" align="center"><strong>Work-Item Task</strong></td>
    </tr>
    <tr>
      <th><center>Id</center></th>
      <th><center>Title</center></th>
      <th><center>Id</center></th>
      <th><center>Title</center></th>
      <th><center>Estimation (In hours)</center></th>
      <th><center>Assigned To</center></th>
      <th><center>Status</center></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><center>US01</center></td>
      <td><center>Registrar usuario</center></td>
      <td><center>W01</center></td>
      <td><center>Registro de Usuario - App Web</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US01</center></td>
      <td><center>Registrar usuario</center></td>
      <td><center>W02</center></td>
      <td><center>Registro de Usuario - App Mobile</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US01</center></td>
      <td><center>Registrar usuario</center></td>
      <td><center>W03</center></td>
      <td><center>Registro de Usuario - Web Services IAM</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US02</center></td>
      <td><center>Inicio de sesión</center></td>
      <td><center>W04</center></td>
      <td><center>Inicio de sesión - App Web</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US02</center></td>
      <td><center>Inicio de sesión</center></td>
      <td><center>W05</center></td>
      <td><center>Inicio de sesión - App Mobile</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US02</center></td>
      <td><center>Inicio de sesión</center></td>
      <td><center>W06</center></td>
      <td><center>Inicio de sesión - Web Services IAM</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US03</center></td>
      <td><center>Registrar espacios</center></td>
      <td><center>W07</center></td>
      <td><center>Registrar espacios - App Web</center></td>
      <td><center>4</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US03</center></td>
      <td><center>Registrar espacios</center></td>
      <td><center>W08</center></td>
      <td><center>Registrar espacios - App Mobile</center></td>
      <td><center>4</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US04</center></td>
      <td><center>Buscar espacios disponibles</center></td>
      <td><center>W09</center></td>
      <td><center>Buscar espacios disponibles - App Web</center></td>
      <td><center>4</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US04</center></td>
      <td><center>Buscar espacios disponibles</center></td>
      <td><center>W10</center></td>
      <td><center>Buscar espacios disponibles - App Mobile</center></td>
      <td><center>4</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US06</center></td>
      <td><center>Visualizar información del espacio</center></td>
      <td><center>W11</center></td>
      <td><center>Visualizar información del espacio - App Web</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US06</center></td>
      <td><center>Visualizar información del espacio</center></td>
      <td><center>W12</center></td>
      <td><center>Visualizar información del espacio - App Mobile</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US07</center></td>
      <td><center>Reservar espacios</center></td>
      <td><center>W13</center></td>
      <td><center>Reservar espacios - App Web</center></td>
      <td><center>4</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US07</center></td>
      <td><center>Reservar espacios</center></td>
      <td><center>W14</center></td>
      <td><center>Reservar espacios - App Mobile</center></td>
      <td><center>4</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US08</center></td>
      <td><center>Gestionar calendario de reservas</center></td>
      <td><center>W15</center></td>
      <td><center>Gestionar calendario de reservas - App Web</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US08</center></td>
      <td><center>Gestionar calendario de reservas</center></td>
      <td><center>W16</center></td>
      <td><center>Gestionar calendario de reservas - App Mobile</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US12</center></td>
      <td><center>Visualizar espacios propios publicados</center></td>
      <td><center>W17</center></td>
      <td><center>Visualizar espacios propios publicados - App Web</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
    <tr>
      <td><center>US12</center></td>
      <td><center>Visualizar espacios propios publicados</center></td>
      <td><center>W18</center></td>
      <td><center>Visualizar espacios propios publicados - App Mobile</center></td>
      <td><center>3</center></td>
      <td><center>XXXX</center></td>
      <td><center>Done</center></td>
    </tr>
  </tbody>
</table>
  
</div>


### 5.2.2. Implemented Landing Page Evidence

**Evidencias del avance de la implementación de la Landing Page:**

![Captura de Pantalla](Resources/Evidences/Landing%20Evidence-1.png)

![Captura de Pantalla](Resources/Evidences/Landing%20Evidence-2.png)

![Captura de Pantalla](Resources/Evidences/Landing%20Evidence-3.png)

![Captura de Pantalla](Resources/Evidences/Landing%20Evidence-4.jpeg)

### 5.2.3. Implemented Frontend-Web Application Evidence

**Evidencias del avance de la implementación de la Web App:**

![Captura de Pantalla](Resources/Evidences/App%20Web%20Evidence-1.jpeg)

![Captura de Pantalla](Resources/Evidences/App%20Web%20Evidence-2.jpeg)

![Captura de Pantalla](Resources/Evidences/App%20Web%20Evidence-3.jpeg)

### 5.2.4. Implemented Native-Mobile Application Evidence

**Evidencias del avance de la implementación de la Mobile App:**

<p align="center">
  <img src="Resources/Evidences/Backend%20Evidence-1.jpeg" alt="Captura de Pantalla"/>
</p>

### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

**Evidencias del avance de la implementación del Back-end/Web Services:**

<p align="center">
  <img src="Resources/Evidences/App%20Mobile%20Evidence-1.jpeg" alt="Captura de Pantalla"/>
  <br>
  <img src="Resources/Evidences/App%20Mobile%20Evidence-2.jpeg" alt="Captura de Pantalla"/>
  <br>
  <img src="Resources/Evidences/App%20Mobile%20Evidence-3.jpeg" alt="Captura de Pantalla"/>
</p>

![Captura de Pantalla](Resources/Evidences/App%20Mobile%20Evidence-4.png)


### 5.2.6. RESTful API documentation

<div align="justify">
A continuación, se presenta una descripción detallada de la documentación de la RESTful API desarrollada para este sistema. Esta interfaz de programación de aplicaciones permite la comunicación entre clientes (tanto web como móviles) y el servidor backend, utilizando el paradigma REST (Representational State Transfer), ampliamente adoptado por su simplicidad, escalabilidad y separación de responsabilidades.


<br>

***Principios RESTful***

Una API RESTful se basa en los siguientes principios fundamentales:


* **Recursos como entidades centrales:** Cada recurso (por ejemplo, usuarios, espacios, reservas) se representa mediante una URI única.

* **Operaciones a través de verbos HTTP:** Las operaciones sobre los recursos se realizan mediante los verbos HTTP estándar:

  * **GET:** Recuperar información.

  * **POST:** Crear un nuevo recurso.

  * **PUT:** Actualizar un recurso existente.

  * **DELETE:** Eliminar un recurso.

* **Sin estado (stateless):** Cada solicitud debe contener toda la información necesaria para ser procesada. El servidor no almacena estado entre peticiones.

* **Uso de hipermedios (opcional - HATEOAS):** Aunque no se implementa siempre, REST permite que las respuestas incluyan enlaces para navegar entre recursos relacionados.

<br>

***Autenticación***

* **Método utilizado:** JWT (JSON Web Token), una forma segura y compacta de transmitir información entre partes.

* **Formato del encabezado requerido:**

* Los tokens JWT permiten autenticar y autorizar a los usuarios sin necesidad de mantener sesiones en el servidor, lo cual es coherente con el principio stateless.

<br>

***Convenciones y Buenas Prácticas***

* **Nombres de recursos en plural:** Para mantener la coherencia y claridad, los endpoints usan sustantivos en plural (e.g., /users, /spaces, /reservations).

* **Versionamiento de la API:** Aunque no siempre es necesario, es recomendable incluir una versión en la URI (e.g., /api/v1/users) para facilitar futuras actualizaciones sin romper la compatibilidad.

* **Códigos de estado HTTP:** La API utiliza códigos de estado HTTP estándar para indicar el resultado de cada operación:

  * **200 OK:** Solicitud exitosa.

  * **201 Created:** Recurso creado correctamente.

  * **400 Bad Request:** Error en los datos enviados.

  * **401 Unauthorized:** Falta de autenticación o token inválido.

  * **404 Not Found:** Recurso no encontrado.

  * **500 Internal Server Error:** Error inesperado en el servidor.

<br>

***Documentación Interactiva***

Se recomienda el uso de herramientas como Swagger (OpenAPI) o Postman para documentar y probar la API de manera interactiva. Esto mejora la experiencia de los desarrolladores y facilita la integración con otras aplicaciones.

</div>


### 5.2.7. Team Collaboration Insights

## 5.3. Video About-the-Product

![Artefacto creado en Youtube](Resources/About%20Product/AboutProductEvidence.png)

**Enlace del video:** https://youtu.be/R445b6178Rs


