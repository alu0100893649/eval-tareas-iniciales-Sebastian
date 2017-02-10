# Markdown
## Un lenguaje de etiquetado

Markdown fue creado en 2004 por John Gruber con una gran contribución por parte 
de Aaron Swartz en su sintaxis. Su objetivo fue crear un lenguaje apto para la 
web y de fácil lectura y escritura. 
Tras la creación del lenguaje, Gruber creó un guión en Perl para traducir un texto
en Markdown a XHTML o HTML y desde entonces han ido apareciendo más traductores
en diferentes lenguajes.
Actualmente, muchos sitios web como GitHub, SourceForge y Reddit utilizan Markdown
como lenguaje de comunicación entre usuarios.

## Sintaxis

**Encabezados**: los encabezados (representados con las etiquetas `<h1>`, `<h2>`, `<h3>`,... en HTML)
se generan con un número de almohadillas igual al número que sigue a la h en la etiqueta en HTML y un
espacio justo después.  
> # `#` h1  
> ## `##` h2  
> ### `###` h3  
> #### `####` h4  
> ##### `#####` h5  

**Citas**: Para citar, normalmente se utiliza el símbolo `>`, que se puede utilizar
en uno o varios renglones.

> `> Este es un ejemplo.`
> > Este es un ejemplo.

**Texto en negrita**: Para escribir cualquier texto en negrita éste debe estar 
rodeado por dos asteriscos seguidos.

> `**Texto en negrita**`  
> **Texto en negrita**

**Texto en cursiva**: Para escribir texto en cursiva, se puede rodear de un solo
asterisco o del símbolo `_`.

> `*Texto en cursiva*` o `_Texto en cursiva_`  
> _Texto en cursiva_
  
**Listas ordenadas**: Para crar listas ordenadas basta con colocar el número del
elemento de la lista seguido de un punto y un espacio.

> `1. Primer elemento.`  
> `2. Segundo elemento.`

**Listas no ordenadas*: Para crear listas no ordenadas, colocaremos un asterisco 
y un espacio antes de cada elemento.

> `* Un elemento.`  
> `* Otro elemento.`

**Enlaces**: Para poner un enlace, se inserta el texto entre corchetes seguido
del link entre paréntesis.

> `[Link a Google](www.google.es)`  
> [Link a Google](www.google.es)

**Imágenes**: Para poner imágenes, se usa como un link, pero añadiendo primero
un símbolo de exclamación cerrado. El texto se mostrará cuando el ratón se ponga
sobre la imagen.

> `![Imagen de prueba](http://orig05.deviantart.net/0465/f/2013/202/8/a/400_pixel_idyll__20x20px__by_hellvansing-d6eg2f1.png)`  
> ![Imagen de prueba](http://orig05.deviantart.net/0465/f/2013/202/8/a/400_pixel_idyll__20x20px__by_hellvansing-d6eg2f1.png)

**Salto de línea**: Para dar un salto de línea basta con escribir un doble espacio.

**Código explícito**: Para escribir de forma explícita un código que de otra forma
daría lugar a un uso de Markdown, se rodea del símbolo ` (acento grave).