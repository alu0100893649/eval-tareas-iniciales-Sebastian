# GitBook

### Documentación y publicación libres y sencillas

## Introducción a GitBook

[GitBook](https://www.gitbook.com/) es una plataforma de documentación y publicación de archivos mediante [MarkDown](https://markdown.es/), 
un lenguaje de etiquetado. Fue creado en 2014 con el objetivo de ofrecer una documentación simple y elegante, evitándole 
una mayor carga de trabajo al desarrollador, al creador de contenido. Esta plataforma es utilizada tanto para documentación 
software como libros técnicos, material de aprendizaje..., y da la posibilidad de publicar el contenido redactada via 
web como por pdf.

### Instalación

* Requerimientos

    - [NodeJS](https://nodejs.org/es/). La última versión posible.
    - Sistema operativo Linux, Windows o Mac OS X

* Pasos

    - Instalación por línea de comandos
        > $ npm install gitbook-cli -g

* Crear un libro

    - Para crear un libro aplicando boilerplate debemos:
        > $ gitbook init
    
    - Para crear el libro en otra carpeta solo tenemos que indicar la dirección de destino:
        > $ gitbook init ./<ruta implícita>
    
    - Para fabricar una vista previa del GitBook:
        > $ gitbook serve
    
        en caso de querer realizar un sitio web:
    
        > $ gitbook build

### Instalación de GitBook Desktop

Existe una versión de escritorio de GitBook, llamada [GitBook Desktop](https://www.gitbook.com/editor),
que permite la creación de material desde local. 

* Pasos
 1. Accedemos a la página de [GitBook Desktop](https://www.gitbook.com/editor)
    ![GitBook Desktop Webpage](https://ULL-ESIT-PL-1617.github.io/tareas-iniciales-sje/cap5_gitbook/images/ImageAGitBook.jpg)    

 2. Al descargar el ejecutable, lo lanzamos, activando una ventana del sistema
    para comprobar los permisos de administrador.
 3. Tras ejecutar GitBook Desktop, se instalará en un momento.

La instalación es simple y rápida, y deja al alcance del usuario la creación de contenido desde el primer momento.

![GitBook Desktop Interface](https://ULL-ESIT-PL-1617.github.io/tareas-iniciales-sje/cap5_gitbook/images/ImageBGitBook.jpg)
