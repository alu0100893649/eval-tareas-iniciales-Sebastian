# GitHub
## ¿Qué es?

[GitHub]() es una plataforma del tipo _forge_ (para el desarrollo de software colaborativo)
que aplica el control de versiones Git lanzada en 2008 y creada por Tom Preston-Werner, Chris
Wanstrath y PJ Hyett.

## ¿Qué me ofrece?

Además del entorno colaborativo con control de versiones que define a GitHub, la plataforma
nos proporciona una serie de funcionalidades añadidas que ayudarán a crear nuestro proyecto 
así como a darlo a conocer:

* Una Wiki para cada proyecto
* Una página web (gh-page) por proyecto y desarrollador.
* Gráficos para ver cómo los desarrolladores avanzan en sus repositorios así como el 
estado de las ramas.
* Un gestor de proyectos de estilo [Kanban](https://es.wikipedia.org/wiki/Kanban).
* Una suerte de foro para el control de _Issues_ o problemas derivados del proyecto.
Además, GitHub también funciona como una red social, por lo que permite a los usuarios
_seguir_ un proyecto para conocer todas las novedades y el estado de éste en cada momento.



## ¿Cómo usar la plataforma?

Para empezar a utilizar GitHub es necesario registrarse en su [página web](). 
Después crearemos un repositorio con las opciones que nos proporciona al entrar.
A pesar de que GitHub proporciona herramientas para escribir el código directamente, lo más
común y el método que utilizaremos es el envío de commits por consola de UNIX. Para ello,
según creemos el repositorio, GitHub nos proporciona una serie de pasos iniciales:
![Pasos iniciales](https://i.gyazo.com/ce16e7a76b132ec7e09f569159cd7543.png)

Lo recomendable es usar los pasos de crear un nuevo repositorio desde la consola cuando
enviemos nuestro primer commit, y a partir de ahí seguir los siguientes pasos:

1. Añadir los archivos que no tuviera el anterior commit con el comando _git add <archivo>_.
2. Crear un nuevo commit y darle un nombre con el comando _git commit -m <nombre del commit>_.
3. Enviarlo a GitHub con el comando _git push -u origin <rama local>:<rama remota>_. En caso de que 
sólo usemos una rama, el comando sería _git push -u origin master_. Para más información de las ramas
ver el capítulo Git.

## Imágenes de sus funcionalidades

![Projects](https://tctechcrunch2011.files.wordpress.com/2016/09/6f8a5a1a-7976-11e6-8708-10e6aeb49251.gif)
_Gestor de proyectos de tipo Kanban_    
![Wiki](https://guides.github.com/activities/contributing-to-open-source/d3-wiki.png)
  _Wiki para un proyecto_    
![Graphs](https://camo.githubusercontent.com/f2af96058f156ef2b96a9e6e97b04775090b34ce/68747470733a2f2f6769746875622d696d616765732e73332e616d617a6f6e6177732e636f6d2f626c6f672f323031322f6772617068732e636f6e7472696275746f72732e706e67)  
  _Gráficos de avances sobre el repositorio_    