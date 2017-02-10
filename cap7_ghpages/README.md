# GH-Pages
## ¿Qué son las GH-Pages?

[_Github_](https://github.com) nos proporciona, tanto a nivel personal como para cada proyecto, una página web asociada de forma gratuita. 
De esta forma, un _developer_ o desarrollador puede mantener un sitio propio y con aspecto profesional en el que mostrar al mundo los proyectos
de los que se siente más orgulloso así como una página que sirva de presentación de un determinado programa o plataforma, ya sea para su promoción 
o para mantener informados a sus seguidores de posibles avances o salida de versiones.

## GH-Pages personales
### Utilidad
Las GitHub Pages proporcionan, a nivel personal, una presentación de un perfil personal. Por la naturaleza de GitHub, este perfil suele estar relacionado
de forma directa con la programación en cualquier lenguaje de programación, ya que es muy sencillo realizar un índice de programas realizados por el dueño
de la página. Sin embargo, también es apta para cualquier persona que esté interesada en tener una página en la que darse a conocer, como por ejemplo un
diseñador. En definitiva, es un servicio pensado para **publicitarse como profesionales**.
### Creación
Para obtener nuestra propia Github Page (gh-page), lo primero que necesitaremos es estar en posesión de una cuenta [_Github_](https://github.com), o en
caso de no tenerla, [crear](https://github.com/join) una.
Después seguiremos los pasos detallados a continuación:
1. Crearemos un repositorio cuyo nombre sea _usuario_.github.io, donde _usuario_ sea el nombre de usuario de nuestra cuenta Github.
2. Desde nuestra terminal UNIX, haremos un **git clone** al repositorio que acabamos de crear.
3. En la carpeta que acabamos de crear tras el clone, introduciremos todos aquellos ficheros que requiera nuestra página web: ficheros html, css, javascript, php,...
4. Una vez tengamos todos los ficheros en la carpeta, sólo hace falta subirlos. Para ello haremos un **git add .** o **git add --all** seguido de la creación del comit
mediante el comando **git commit -m _nombre del commit_** y de su push hacia el repositorio remoto con **git push origin master**.
> En el caso de utilizar alguna de las interfaces de [_Github_](https://github.com) (ya sea para Windows o Mac), en lugar de hacer el **git clone** clickaremos el **Setup in Desktop**
> proporcionado en la página del repositorio. Para subirlo, desde el programa clickaremos en el botón **Sync**.

>Para una guía mas gráfica se recomienda visitar [esta página](https://pages.github.com/)

## GH-Pages para proyectos
### Utilidad
En determinadas ocasiones, un proyecto es dinámico y no tiene sólo una salida. Esto es, cada cierto tiempo, el proyecto ha de renovarse. Este es uno de los
perfiles más comunes de proyectos con gh-page. Este tipo de proyecto necesita para su supervivencia mantener a los usuarios informados de las actualizaciones
así como de sus ventajas o fallos de las anteriores, y un gh-page es el mejor método para ello.
En otras ocasiones, los desarrolladores quieren darle un mayor alcance a su proyecto, y una página web publicitaria llevará esta visión al siguiente estadío.
### Creación
Para la creación de una gh-page para nuestro proyecto necesitaremos, como en el caso anterior, una cuenta [_Github_](https://github.com). Además, también
es necesario tener un proyecto sobre el que desplegar nuestra gh-page.
Después seguiremos los pasos detallados a continuación:
1. Crearemos una nueva rama para nuestro proyecto desde el repositorio.
2. Enviaremos un commit que contenga todos los ficheros necesarios para la página web usando los comandos especificados en el **punto 4** de la Creación de GH Pages personales.
3. Iremos a la configuración de nuestro repositorio y haremos _scroll_ hasta la opción de **GitHub Pages**. Una vez allí seleccionaremos la rama y clickaremos **Save** o guardar.
> Si queremos una plantilla para la página web, en la opción de **GitHub Pages** también se nos ofrece una amplia variedad de temas para elegir.