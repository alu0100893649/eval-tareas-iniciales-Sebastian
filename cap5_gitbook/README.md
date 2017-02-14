# GitBook

### Documentación y publicación libres y sencillas

## Introducción a GitBook

[GitBook](https://www.gitbook.com/) es una __plataforma de creación, documentación y publicación de contenido__ mediante [MarkDown](https://markdown.es/), 
un lenguaje de etiquetado. Fue creado en 2014 con el objetivo de ofrecer una documentación simple y elegante, evitándole 
una mayor carga de trabajo al desarrollador, al creador de contenido. Esta plataforma es utilizada tanto para documentación 
software como libros técnicos, material de aprendizaje..., y da la posibilidad de publicar el contenido redactado tanto por vía 
web como por pdf.

## Instalación

* Requerimientos

    - [NodeJS](https://nodejs.org/es/). La última versión posible.
    - Sistema operativo Linux, Windows o Mac OS X.

* Pasos

    - Instalación por línea de comandos
        > $ npm install gitbook-cli -g

## Instalación de GitBook Desktop

Existe una versión de escritorio de GitBook, llamada [GitBook Desktop](https://www.gitbook.com/editor),
que permite la creación de material desde local. 

* Pasos
 1. Accedemos a la página de __GitBook Desktop.__
    ![GitBook Desktop Webpage](/cap5_gitbook/images/ImageAGitBook.png)    

 2. Al descargar el ejecutable, lo lanzamos, activando una ventana del sistema
    para comprobar los permisos de administrador.
 3. Tras ejecutar __GitBook Desktop__, se instalará en un momento.

La instalación es simple y rápida, y deja al alcance del usuario la creación de contenido desde el primer momento.

![GitBook Desktop Interface](/cap5_gitbook/images/ImageBGitBook.png)

## Estructura básica de un libro GitBook

Los libros generados a través de GitBook están formados por un archivo README.md principal, la portada del libro, y una serie de carpetas en las que
se encontrarán los archivos README.md respectivos de cada capítulo. Además tiene un archivo book.json con la
configuración del libro, y un archivo SUMMARY.md, que contiene el índice del libro, ambos opcionales. 

La estructura tendría un árbol de directorios similar a:

```
.
├── book.json
├── README.md
├── SUMMARY.md
├── chapter-1/
|   ├── README.md
|   └── something.md
└── chapter-2/
    ├── README.md
    └── something.md
```

## Creación de un libro

    
-  Para crear un libro debemos:
    > $ gitbook init
    
- Para crear el libro en otra carpeta solo tenemos que indicar la dirección de destino:
    > $ gitbook init ./ruta_implícita
    
- Para fabricar una vista previa del GitBook:
    > $ gitbook serve
    
    en caso de querer realizar un sitio web:
    
    > $ gitbook build
