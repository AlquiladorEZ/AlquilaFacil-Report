# Capítulo IV: Product Design

## 4.1. Style Guidelines

<div align="justify">
    Un Style Guideline es un conjunto de reglas y normas que definen cómo se debe redactar, diseñar o presentar documentos, contenido web, software u otros trabajos creativos. A continuación, se detallan las especificaciones de los parámetros implementados en la estructura del proyecto.
</div>


### 4.1.1. General Style Guidelines

**Overview:**
<div align="justify">
    Deseamos capturar la atención del usuario desde el inicio mediante la creación y el diseño de una perspectiva del producto que establezca una conexión inmediata y reconocible.
</div>
<br>

**Brand Overview:**
<div align="justify">
     AlquilaFácil es un startup tecnológico fundada en el 2024 por un grupo de estudiantes compuesta por un grupo de estudiantes de la carrera de Ingeniería de Software. Nuestro startup está dedicada a simplificar el proceso de alquiler de espacios para eventos, brindando una plataforma innovadora y accesible para propietarios y organizadores por igual.
</div>
<br>

**Brand Name:**
<div align="justify">
     Como el startup se trata de alquilar centros para eventos y también para publicitar centros que podrían ser alquilados, se vio conveniente llamarlo “AlquilaFácil”.
</div>
<br>

![Artefacto creado en Canva](Resources/Style%20Guidelines/Background-AlquilaFacil.png) 

**Typography:**
<div align="justify">
     El tamaño elegido para la tipografía por el equipo fue: 
</div>
<br>

![Artefacto creado en Canva](Resources/Style%20Guidelines/Typography.png) 

<br>

**Colors:**
<div align="justify">
     La gama de colores elegidos son:
</div>

<br>

![Artefacto creado en Canva](Resources/Style%20Guidelines/Colors.png) 


### 4.1.2. Web Style Guidelines

### 4.1.3. Mobile Style Guidelines

#### 4.1.3.1. iOS Mobile Style Guidelines

#### 4.1.3.2. Android Mobile Style Guidelines

## 4.2. Information Architecture

<div align="justify">
    En esta sección, se va a presentar la estructura del software según cada segmento objetivo. Además, los elementos que emplearan para la navegación de esta. 
</div>

### 4.2.1. Organization Systems

<div align="justify">
    El sistema de organización de AlquilaFácil ha sido diseñado con el objetivo de optimizar la experiencia del usuario, permitiendo una gestión eficiente de la búsqueda y selección de espacios en alquiler. Este sistema se basa en los siguientes componentes clave: 
</div>

<br>

<div align="justify">

* ***Búsqueda y filtros personalizados:***
La aplicación incorpora un motor de búsqueda avanzado acompañado de filtros que permiten a los usuarios refinar los resultados según criterios como ubicación, precio y características específicas del espacio.  
Esto asegura que el usuario solo vea opciones relevantes, facilitando la toma de decisiones.


* ***Tarjetas de visualización de espacios:***
Los espacios disponibles se muestran en formato de tarjetas visuales, donde se presenta la información más importante de manera clara y concisa.  
Cada tarjeta incluye:

    - Imagen del espacio  
    - Ubicación  
    - Precio  
    - Opción de añadir a favoritos



* ***Barra de navegación inferio:***
En la parte inferior de la pantalla se encuentra una barra de navegación que agrupa las principales funciones de la aplicación, como:

    - Búsqueda  
    - Notificaciones  
    - Acceso al calendario o eventos  
    - Gestión de reservas


* ***Jerarquización de la información:***
La información en la interfaz está organizada de manera que los elementos más relevantes, como el precio y la ubicación del espacio, sean inmediatamente visibles. Esto facilita al usuario la evaluación de cada opción sin necesidad de ingresar a detalles adicionales de cada anuncio. 
</div>

<br>

### 4.2.2. Labeling Systems

<div align="justify">
    El sistema de etiquetado o Labelling System de AlquilaFácil está diseñado para proporcionar claridad y coherencia en la presentación de información, facilitando la comprensión rápida y eficiente de los contenidos por parte del usuario. Este sistema emplea etiquetas visuales y textuales en diferentes áreas clave de la aplicación: 
</div>

<br>

<div align="justify">

* ***Etiquetas de búsqueda y filtro:***
En la parte superior de la interfaz, los campos de búsqueda y filtro están claramente etiquetados con íconos universales, como una lupa para la búsqueda y un embudo para los filtros. Estos íconos, junto con textos descriptivos, permiten que los usuarios identifiquen rápidamente las funciones y realicen acciones sin confusión. 

* ***Etiquetas en tarjetas de espacios:***
Cada tarjeta de espacio cuenta con etiquetas descriptivas que destacan la ubicación y el precio, las cuales están claramente diferenciadas en la interfaz. Estas etiquetas ayudan a los usuarios a identificar los detalles más relevantes de un espacio sin necesidad de interactuar más allá del listado inicial. 


* ***Iconos como Etiquetas Visuales:***
La aplicación utiliza iconos ampliamente reconocidos, como la estrella para "puntuaciones" y el botón de "más" para añadir nuevos espacios, que actúan como etiquetas visuales. Estos iconos, en combinación con sus posiciones estratégicas, ofrecen una experiencia intuitiva, reduciendo la necesidad de explicaciones textuales adicionales. 

* ***Categorías de espacios:***
Los espacios se pueden clasificar por diferentes tipos o características, lo que permite el uso de etiquetas de categoría. Estas etiquetas aparecen en los resultados de búsqueda para que los usuarios identifiquen rápidamente el tipo de espacio que están viendo (por ejemplo, oficinas, espacios de coworking, etc.). 
</div>

<br>

### 4.2.3. SEO Tags and Meta Tags

<div align="justify">
        Las meta-etiquetas nos permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las leen. Estas etiquetas facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido. Además, influyen en el posicionamiento de nuestra página en los motores de búsqueda. 
</div>

<br>

<div align="justify">
    
* ***Título:***
Las meta etiquetas nos permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las leen. Estas etiquetas facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido. Además, influyen en el posicionamiento de nuestra página en los motores de búsqueda.

:::
```
<title>Register your processes with AlquilaFacil</title>
```
:::


* ***Codificación de caracteres:***
Se decidió usar el utf-8 por la eficiencia de memoria. Es más eficiente en términos de memoria para caracteres del BMP (Plano Multilingüe Básico, que incluye la mayoría de los caracteres comunes).

:::
```
<meta charset="utf-8">
```
:::

* ***Descripción:***
Esta etiqueta meta nos permite ofrecer un resumen del contenido de la página web. En ella, proporcionamos una breve descripción de lo que los usuarios pueden esperar visualizar en la página.

:::
```
<meta name="description" content="AlquilaFacil is a web application focused on plublish and rent centers for events"/>
```
:::

* ***Palabras clave:***
En esta etiqueta se pone las palabras claves relacionadas con el tema o contenido de la página web.
:::
```
<meta name="keywords" content="publish, rent, management, application, announcements, centers"/> 
```
:::

* ***Autor y derechos de autor:***
Se utiliza para registrar la información del autor de la página web y la propiedad y derechos de autor.
:::
```
<meta name="author" content="AlquilaFacil"/> 

<meta name="copyright" content="Copyright AlquilaFacil team" />
```
:::

</div>

<br>

### 4.2.4. Searching Systems

<div align="justify">
    El motor de búsqueda es fundamental para que los usuarios encuentren rápidamente detalles específicos 
</div>

<br>

<div align="justify">
Características claves: 

* ***Búsqueda por ubicación:***
Los usuarios podrán buscar centros para eventos cercanos a su ubicación actual o especificar una ubicación deseada.

* ***Búsqueda por características:***
Los usuarios podrán buscar características específicas, como piscina, parrilla, pet friendly, vigilancia.

* ***Filtros avanzados:***
Se proporcionarán filtros para refinar la búsqueda, como calificaciones, precios y disponibilidad.

* ***Resultados relevantes:***
 El sistema de búsqueda mostrará resultados relevantes y ordenados de acuerdo con la ubicación y otros criterios.

</div>

<br>


### 4.2.5. Navigation Systems

<div align="justify">
El Navigation System de AlquilaFácil está diseñado para proporcionar una experiencia de usuario fluida, intuitiva y eficiente, permitiendo a los usuarios moverse por la aplicación de manera rápida y sin complicaciones. Este sistema incluye varios elementos clave que optimizan el acceso a las distintas funciones y secciones de la aplicación: 
</div>

<br>

<div align="justify">
    
* ***Barra de Navegación Inferior:***
La aplicación cuenta con una barra de navegación fija en la parte inferior de la pantalla que agrupa las principales funcionalidades. Los iconos incluidos, como la lupa (búsqueda), la campana (notificaciones), el botón de "+" (añadir nuevo espacio), el calendario (gestión de eventos o reservas) y el perfil (opciones del usuario), permiten un acceso directo a cada sección, facilitando la navegación entre las funciones esenciales sin necesidad de menús desplegables o múltiples clics. 

* ***Navegación Jerárquica:***
AlquilaFácil implementa un sistema de navegación jerárquica en el que los usuarios pueden profundizar en los detalles de un espacio o acción, pero siempre tienen la opción de volver a la pantalla anterior de manera sencilla. Este enfoque evita que los usuarios se pierdan en la aplicación, manteniendo siempre claro en qué nivel de la jerarquía se encuentran. 
    
</div>

<br>

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

![Artefacto creado en Figma](Resources/Landing%20Page%20UXUI/LandingWirefram-1.png) 

![Artefacto creado en Figma](Resources/Landing%20Page%20UXUI/LandingWirefram-2.png) 

![Artefacto creado en Figma](Resources/Landing%20Page%20UXUI/LandingWirefram-3.png) 

**Enlace:** https://www.figma.com/design/Sk1zmVhp0zEdPv97Vlxvwm/Landing-Page?node-id=4-202&p=f&t=B4E2iU0zpHfw3UMs-0

### 4.3.2. Landing Page Mock-up

![Artefacto creado en Figma](Resources/Landing%20Page%20UXUI/LandingMockup-1.png) 

![Artefacto creado en Figma](Resources/Landing%20Page%20UXUI/LandingMockup-2.png) 

![Artefacto creado en Figma](Resources/Landing%20Page%20UXUI/LandingMockup-3.png) 

![Artefacto creado en Figma](Resources/Landing%20Page%20UXUI/LandingMockup-4.png) 

**Enlace:** https://www.figma.com/design/Sk1zmVhp0zEdPv97Vlxvwm/Landing-Page?node-id=4-422&p=f&t=B4E2iU0zpHfw3UMs-0

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes

![Artefacto creado en Figma](Resources/Mobile%20Application%20UXUI/Wireframe-1.png) 

![Artefacto creado en Figma](Resources/Mobile%20Application%20UXUI/Wireframe-2.png) 

![Artefacto creado en Figma](Resources/Mobile%20Application%20UXUI/Wireframe-3.png) 

**Enlace:** https://www.figma.com/design/ZgcH4GPA3oBLZf4SvVs52Z/Mobile-App?node-id=1-207&p=f&t=CgMdhjsdUrnIRfBA-0

<br>

### 4.4.2. Mobile Applications Wireflow Diagrams

### 4.4.3. Mobile Applications Mock-ups

![Artefacto creado en Figma](Resources/Mobile%20Application%20UXUI/Mockup-1.png) 

![Artefacto creado en Figma](Resources/Mobile%20Application%20UXUI/Mockup-2.png) 

![Artefacto creado en Figma](Resources/Mobile%20Application%20UXUI/Mockup-3.png) 

**Enlace:** https://www.figma.com/design/ZgcH4GPA3oBLZf4SvVs52Z/Mobile-App?node-id=1-206&p=f&t=CgMdhjsdUrnIRfBA-0


<br>

### 4.4.4. Mobile Applications User Flow Diagrams

## 4.5. Mobile Applications Prototyping

### 4.5.1. Android Mobile Applications Prototyping

![Artefacto creado en Figma](Resources/Mobile%20Application%20UXUI/Prototype-1.png) 

**Enlace:** https://www.figma.com/proto/ZgcH4GPA3oBLZf4SvVs52Z/Mobile-App?node-id=323-5448&p=f&t=m5g3QGHQaj8HwQ0a-1&scaling=scale-down&content-scaling=fixed&page-id=1%3A206&starting-point-node-id=323%3A5448


<br>

### 4.5.2. iOS Mobile Applications Prototyping

## 4.6. Web Applications UX/UI Design

### 4.6.1. Web Applications Wireframes

### 4.6.2. Web Applications Wireflow Diagrams

### 4.6.3. Web Applications Mock-ups

### 4.6.4. Web Applications User Flow Diagrams

## 4.7. Web Applications Prototyping

## 4.8. Domain-Driven Software Architecture

<div align="justify">
A continuación, se visualizarán los diagramas C4. 
</div>

<br>

### 4.8.1. Software Architecture Context Diagram

### 4.8.2. Software Architecture Container Diagrams

### 4.8.3. Software Architecture Components Diagrams

## 4.9. Software Object-Oriented Design

### 4.9.1. Class Diagrams

<div align="justify">

**Profile Context:**

</div>

![Artefacto creado en Miro](Resources/Object-Oriented%20Design/ClassDiagram-1.png) 

<div align="justify">

**Contact Context:**

</div>

![Artefacto creado en Miro](Resources/Object-Oriented%20Design/ClassDiagram-2.png) 

<div align="justify">

**Spaces Context:**

</div>

![Artefacto creado en Miro](Resources/Object-Oriented%20Design/ClassDiagram-3.png) 

**Subscription Context:**

</div>

![Artefacto creado en Miro](Resources/Object-Oriented%20Design/ClassDiagram-4.png) 

<br>

### 4.9.2. Class Dictionary


<table align="center">
  <thead>
    <tr>
      <th>Clase</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Profile</td><td>Raíz del agregado que representa un perfil de usuario con varios atributos.</td></tr>
    <tr><td>PersonName</td><td>Objeto de valor para almacenar el nombre, nombre del padre y madre.</td></tr>
    <tr><td>DocumentNumber</td><td>Objeto de valor para representar el número de documento.</td></tr>
    <tr><td>Phone</td><td>Objeto de valor para almacenar el número de teléfono.</td></tr>
    <tr><td>DateOfBirth</td><td>Objeto de valor para almacenar la fecha de nacimiento.</td></tr>
    <tr><td>Contact</td><td>Raíz del agregado que representa la información de contacto.</td></tr>
    <tr><td>NameUsername</td><td>Objeto de valor para almacenar el nombre y apellido.</td></tr>
    <tr><td>Message</td><td>Objeto de valor para almacenar un mensaje de contacto.</td></tr>
    <tr><td>Email</td><td>Objeto de valor para almacenar la dirección de correo electrónico.</td></tr>
    <tr><td>ContactAudit</td><td>Entidad que representa la información de auditoría de los contactos.</td></tr>
    <tr><td>Plan</td><td>Raíz del agregado que representa un plan de servicio.</td></tr>
    <tr><td>Invoice</td><td>Raíz del agregado que representa una factura.</td></tr>
    <tr><td>Subscription</td><td>Raíz del agregado que representa una suscripción.</td></tr>
    <tr><td>SubscriptionAudit</td><td>Entidad que representa la información de auditoría de las suscripciones.</td></tr>
    <tr><td>SubscriptionStatus</td><td>Entidad que representa el estado de una suscripción.</td></tr>
    <tr><td>Local</td><td>Raíz del agregado que representa un local.</td></tr>
    <tr><td>CityPlace</td><td>Objeto de valor para ciudad y país.</td></tr>
    <tr><td>LocalType</td><td>Objeto de valor para el tipo de local.</td></tr>
    <tr><td>NightPrice</td><td>Objeto de valor para el precio por noche.</td></tr>
    <tr><td>PhotoUrl</td><td>Objeto de valor para la URL de una foto.</td></tr>
    <tr><td>StreetAddress</td><td>Objeto de valor para la dirección de una calle.</td></tr>
    <tr><td>LocalCategory</td><td>Entidad que representa la categoría de un local.</td></tr>
  </tbody>
</table>

<br>

## 4.10. Database Design

<div align="justify">

Para AlquilaFácil, se ha decidido utilizar una base de datos relacional, ya que proporciona una estructura clara y organizada que facilita la gestión de datos interrelacionados. Esto permite asegurar la integridad y consistencia de la información, aprovechando las capacidades de SQL para realizar consultas complejas y optimizar el rendimiento. Además, la naturaleza relacional de la base de datos permite manejar mejor los requerimientos de la aplicación, asegurando que las relaciones entre los datos estén bien definidas y fácilmente accesibles. 
</div>

### 4.10.1. Relational/Non-Relational Database Diagram

![Artefacto creado en Miro](Resources/Object-Oriented%20Design/DatabaseDiagram.png) 
