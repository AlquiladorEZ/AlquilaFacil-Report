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

```<title>Register your processes with AlquilaFacil</title>```

* ***Codificación de caracteres:***
Se decidió usar el utf-8 por la eficiencia de memoria. Es más eficiente en términos de memoria para caracteres del BMP (Plano Multilingüe Básico, que incluye la mayoría de los caracteres comunes).


* ***Iconos como Etiquetas Visuales:***
La aplicación utiliza iconos ampliamente reconocidos, como la estrella para "puntuaciones" y el botón de "más" para añadir nuevos espacios, que actúan como etiquetas visuales. Estos iconos, en combinación con sus posiciones estratégicas, ofrecen una experiencia intuitiva, reduciendo la necesidad de explicaciones textuales adicionales. 

* ***Categorías de espacios:***
Los espacios se pueden clasificar por diferentes tipos o características, lo que permite el uso de etiquetas de categoría. Estas etiquetas aparecen en los resultados de búsqueda para que los usuarios identifiquen rápidamente el tipo de espacio que están viendo (por ejemplo, oficinas, espacios de coworking, etc.). 
</div>


### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes

### 4.4.2. Mobile Applications Wireflow Diagrams

### 4.4.3. Mobile Applications Mock-ups

### 4.4.4. Mobile Applications User Flow Diagrams

## 4.5. Mobile Applications Prototyping

### 4.5.1. Android Mobile Applications Prototyping

### 4.5.2. iOS Mobile Applications Prototyping

## 4.6. Web Applications UX/UI Design

### 4.6.1. Web Applications Wireframes

### 4.6.2. Web Applications Wireflow Diagrams

### 4.6.3. Web Applications Mock-ups

### 4.6.4. Web Applications User Flow Diagrams

## 4.7. Web Applications Prototyping

## 4.8. Domain-Driven Software Architecture

### 4.8.1. Software Architecture Context Diagram

### 4.8.2. Software Architecture Container Diagrams

### 4.8.3. Software Architecture Components Diagrams

## 4.9. Software Object-Oriented Design

### 4.9.1. Class Diagrams

### 4.9.2. Class Dictionary

## 4.10. Database Design

### 4.10.1. Relational/Non-Relational Database Diagram
