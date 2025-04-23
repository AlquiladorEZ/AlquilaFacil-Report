# Capítulo V: Product Implementation

## 5.1. Software Configuration Management

<div align="justify">
En la siguiente sección, detallaremos las herramientas, convenciones, referencias y configuraciones empleadas a lo largo del desarrollo del proyecto, que contribuyeron a mantener la consistencia en el trabajo realizado. 
</div>

### 5.1.1. Software Development Environment Configuration

<div align="justify">
En este apartado, se mencionarán los distintos productos de software empleados por el equipo de desarrollo.

**Project Management**

**Microsoft 365:** [https://www.office.com/](https://www.office.com/)  
Microsoft 365 es una plataforma web que facilita la creación de documentos para compartir y editar de forma conjunta. Se utilizó para designar, organizar y hacer un seguimiento de las actividades de trabajo, así como para establecer plazos de entrega.

**Google Meet:** [https://meet.google.com/](https://meet.google.com/)  
Google Meet es una plataforma de videoconferencias que permite realizar videollamadas con múltiples participantes y programar sesiones de trabajo. Se usó como herramienta para llevar a cabo las reuniones del equipo.

**Requirements Management**

**Trello:** [https://trello.com/](https://trello.com/)  
Es un software de gestión de proyectos, que facilita la asignación y organización de las tareas a realizar. Fue utilizado para el Product Backlog.

**Product UX/UI Design**

**UXPressia:** [https://uxpressia.com/](https://uxpressia.com/)  
Es una herramienta en línea que permite a los equipos de trabajo identificar y comprender los problemas, necesidades y comportamiento del usuario en relación con la solución de software que se está desarrollando mediante el uso de plantillas. Se usó para la elaboración de los User Personas, Empathy Maps, Journey Maps e Impact Maps.

**Figma:** [https://www.figma.com/](https://www.figma.com/)  
Figma es una herramienta de edición gráfica, en donde se puede diseñar y prototipar páginas web y aplicaciones de manera colaborativa. Se utilizó para crear los wireframes, mock-ups y los desktop and mobile application prototype del proyecto.

**Software Development**

**Web Services**  
Para los servicios web, se empleó .NET junto al framework ASP.NET Core. La arquitectura implementada fue basada en RESTful API, permitiendo una comunicación eficiente y segura entre la aplicación móvil y el backend.

**Software Documentation**

**Vertabelo:** [https://vertabelo.com/](https://vertabelo.com/)  
Es una herramienta online que facilita el diseño, creación y gestión de bases de datos de manera colaborativa. Se usó para diseñar la base de datos del proyecto.

**LucidChart:** [https://lucid.app/](https://lucid.app/)  
LucidChart es una plataforma que cuenta con opciones para la creación de diagramas, mapas mentales, flujos, con el uso de plantillas y tableros con edición en tiempo real. Fue utilizado en el desarrollo del diagrama de clases UML, así como los Wireflows y User Flows.

**Structurizr:** [https://www.structurizr.com/](https://www.structurizr.com/)  
Es una plataforma que permite modelado de diagramas de arquitectura de software por medio de código. Structurizr fue utilizado para crear el modelo C4 del proyecto.
</div>


### 5.1.2. Source Code Management

<div align="justify">

Para el desarrollo y gestión del proyecto, fue creada una organización mediante GitHub, donde se registró todas las modificaciones realizadas a lo largo de su ciclo de vida. Fue estructurado de la siguiente manera:

**Organization:** [https://github.com/Applications-for-Mobile-Devices-WX63](https://github.com/Applications-for-Mobile-Devices-WX63)  
**Backend Repository:** [https://github.com/Applications-for-Mobile-Devices-WX63/AlquilaFacil-Backend](https://github.com/Applications-for-Mobile-Devices-WX63/AlquilaFacil-Backend)

Por otra parte, para controlar de manera efectiva los cambios en el código de la aplicación y gestionar las ramas por cada repositorio, se ha implementado **GitFlow** para definir y estructurar nuestro flujo de trabajo. Esto involucra la creación de dos ramas principales:

- **main:** También denominada "master", es la rama donde se encuentra la versión más estable del proyecto que va a pasar a producción.
- **develop:** Es la rama donde se integra el contenido de las features. Va paralela al main.

**Ramas auxiliares:**

- **feature:** Son las ramas donde se desarrollan las funcionalidades del proyecto. Luego de completarlas, se fusionan con la rama develop.  
  El formato de nomenclatura usado para las ramas ha sido el siguiente: `feature/feature-name`. Aquí, "feature" indica la rama y "feature-name" el nombre de la funcionalidad que se está desarrollando.

- **release:** Son las ramas donde se prepara la próxima versión del programa. En esta, se realizan las pruebas finales y se corrigen pequeños errores antes del lanzamiento definitivo. Finalizado este proceso, los cambios se fusionan con la rama develop, y luego a la rama main.

Se utilizó el formato **"Semantic Versioning 2.0.0"** para la nomenclatura de las versiones del proyecto, por ejemplo: `release/x.y.z`, en donde:

- **X, Y y Z** son números enteros positivos, donde cada uno se incrementa de manera numérica.
  - **X:** Es la versión mayor. Cada incremento elimina la compatibilidad con versiones anteriores. Esto implica reiniciar a 0 las versiones menores y parche.
  - **Y:** Es la versión menor. Cada incremento implica que se han introducido funcionalidades que sí son compatibles con versiones anteriores. Cada vez que se incremente, la versión parche se reiniciará a 0.
  - **Z:** Es la versión parche. Solo se incrementa cuando se realizan correcciones que son compatibles con versiones anteriores.

- **hotfix:** Son las ramas que se utilizan para corregir errores críticos ocurridos en producción y que necesitan ser resueltos con urgencia. Se originan de la rama main y se fusionan tanto en esta como en la rama develop.

</div>


### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

### 5.2.2. Implemented Landing Page Evidence

### 5.2.3. Implemented Frontend-Web Application Evidence

### 5.2.4. Implemented Native-Mobile Application Evidence

### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

### 5.2.6. RESTful API documentation

### 5.2.7. Team Collaboration Insights

## 5.3. Video About-the-Product
