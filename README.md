# Inventario Hardware ASIR

## Descripción

Este proyecto consiste en una página web de inventario de hardware desarrollada para el ciclo de **Administración de Sistemas Informáticos en Red (ASIR)**.

La aplicación permite visualizar y gestionar un catálogo de componentes y dispositivos hardware organizados por familias, ofreciendo una interfaz moderna con diseño oscuro y herramientas de búsqueda para facilitar la localización de productos.

## Características

* Diseño moderno con tema oscuro.
* Organización de los productos por familias.
* Búsqueda de productos por nombre.
* Filtrado por categorías o familias de hardware.
* Almacenamiento de los datos en formato XML.
* Validación de la estructura de datos mediante un esquema XSD.
* Separación clara entre datos, estructura y presentación.

## Tecnologías utilizadas

* **HTML5**: estructura de la página web.
* **CSS3**: diseño visual y estilos.
* **XML**: almacenamiento de la información del inventario.
* **XSD**: validación de la estructura del archivo XML.

## Estructura del proyecto

```text
InventarioHardware/
│
├── data/
|      └── main_data.xml         #Base de datos de productos
├── docs/
│   └── estilos.css     # Hoja de estilos
│
├── schemas/
│   └── schema.xsd  # Esquema de validación
│──src/
└── index.html       #Pagina principal
└── style.css        #Estilos
```

## Funcionamiento

La información de los productos se almacena en un archivo XML, que actúa como base de datos del inventario. Este archivo es validado mediante un esquema XSD para garantizar que todos los datos cumplen la estructura definida.

La interfaz desarrollada en HTML y CSS muestra los productos agrupados por familias de hardware, como:

* Periféricos
* Almacenamiento
* Procesadores
* Memoria RAM
* Redes
* Otros dispositivos

Además, la aplicación incorpora un sistema de búsqueda y filtrado que permite localizar rápidamente los elementos del inventario.

## Objetivos del proyecto

* Aplicar el uso de XML como almacenamiento estructurado de información.
* Implementar validación de documentos mediante XSD.
* Desarrollar una interfaz web clara y atractiva.
* Facilitar la gestión y consulta de inventario hardware.

## Autor

Este proyecto ha sido realizado por Pablo Virgilio Ruiz Hortelano, Raúl Menarguez Bernal y Santiago José Blanco Castillo
