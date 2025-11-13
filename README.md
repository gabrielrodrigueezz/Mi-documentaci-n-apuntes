# Mi-documentaci-n-apuntes

Lenguaje de marcas:

Es una forma de escribir textos con etiquetas para darles formato.

No hacen acciones por sí solas.

Ejemplos: HTML, XML y Markdown.

Markdown:

Los archivos tienen nombre + extensión .md.

Encabezados: (#, ##, ###…) para secciones.

Estilos de letra:

Itálica: *texto* o _texto_

Negrita: ```**texto**``` o ```__texto__```

Enlaces: &lt;[texto](url "título opcional")&gt; 

Imágenes: ![alt](url)

Tablas:

|Jugador|Equipo|Nombre|
|:--|:--:|--:|  izquierda, centro, derecha

HTML (1991):

Sirve para estructurar contenido en páginas web.

Crea enlaces entre documentos (hipertexto).

No permite interactuar con los contenidos, solo organiza.

Las etiquetas van así: ```<etiqueta>``` y algunas necesitan cierre ```</etiqueta>```.

Atributos: van dentro de la etiqueta de apertura:
<```p class="editor-note">Mi gato es muy gruñón ``````</p>```

Introducción a HTML

HTML significa HyperText Markup Language.

HyperText: texto que enlaza con otros textos o archivos. Es la base de la web, conectando páginas y recursos.

Markup: significa etiqueta. Todas las páginas web están hechas con etiquetas. Ejemplo: <p>HOLA</p> identifica un párrafo.

Language: significa lenguaje, porque HTML tiene sus normas y estructura para organizar contenido web.

Importante: HTML no es un lenguaje de programación. No tiene bucles, funciones ni condiciones; solo estructura la información.

DOCTYPE html, que indica el tipo de documento.

html, que contiene todo el contenido de la página.

Dentro del html hay dos partes: el head y el body.

El head tiene información importante que no se ve directamente, como el título, los íconos o los enlaces a hojas de estilo.
El body contiene lo que aparece en la página, como imágenes o texto.

En resumen, la imagen enseña cómo se organiza una página HTML y muestra un ejemplo básico de código para entender mejor cómo funciona.

La declaración de caracteres ```(<meta charset="utf-8">)``` para que se vean bien los textos.

Una descripción de la página ```(<meta name="description">)```, que aparece en los resultados de búsqueda.

Las palabras clave o keywords, que ayudan a los buscadores a entender de qué trata la página.

El título de la página ```(<title>)```, que se muestra en la pestaña del navegador.

El ícono o favicon, que es la pequeña imagen que aparece junto al título.

Y los enlaces a otros archivos, como hojas de estilo CSS o scripts de JavaScript.
Los elementos de bloque son estructuras grandes que ocupan todo el ancho disponible y se muestran separados por líneas en blanco. Sirven para organizar el contenido en secciones. Algunos ejemplos son: los títulos (<h1> a <h6>), párrafos ```(<p>)```, saltos de línea ```(<br>), separadores (<hr>), citas (<blockquote>), texto preformateado (<pre>) y divisiones ```(<div>)```.

Los elementos de línea son partes más pequeñas que se colocan dentro de los bloques y no rompen la línea. Se usan para modificar o resaltar texto, como ponerlo en negrita, cursiva o incluir enlaces. Algunos ejemplos son: <em> (énfasis), ```<strong>``` (negrita), ```<span>, <a>, <cite> o <code>```

Las etiquetas HTML normalmente vienen en pares, con una de apertura y otra de cierre, como ```<p> y </p>```

Algunas etiquetas son vacías, es decir, no tienen cierre, como ```<img>, <br> o <input>```

Las etiquetas deben anidarse correctamente, lo que significa que si una etiqueta se abre dentro de otra, debe cerrarse antes de cerrar la primera

Los atributos se escriben en la etiqueta de apertura y siguen el formato nombre="valor". Por ejemplo, en ```<img src```="imagen.jpg">, “src” es el atributo.

Recomendación: aunque HTML no distingue entre mayúsculas y minúsculas, se recomienda escribir todo en minúsculas.

 Legibilidad y organización del código

La legibilidad del código significa que debe ser fácil de entender para cualquier persona que lo lea, no solo para quien lo escribió.

Es muy importante que el código HTML que hagamos sea claro y ordenado

Normalmente no trabajamos solos, así que un código legible ayuda a otros a entender qué hicimos y por qué.
Incluso si trabajamos solos, tener el código bien escrito sirve para recordar más fácilmente lo que hicimos después.
Organización del código fuente:
Consiste en dividir la aplicación web en varios archivos y clasificarlos en carpetas o directorios según su función.
Ayuda a mantener el proyecto ordenado y fácil de modificar
Técnicas para escribir código legible y organizado:
Usar comentarios para explicar partes del código
Aplicar buena indentación (dejar espacios para que se vea ordenado).
Mantener una buena organización de los archivos
En HTML, cuando queremos enlazar archivos (como imágenes, hojas de estilo o documentos), usamos rutas para indicar dónde están esos archivos.
Existen dos tipos de rutas: absolutas y relativas

Ruta Absoluta:

Muestra la ubicación completa del archivo en la web, empezando desde el dominio
Se usa cuando el archivo está en otro servidor o en una ubicación externa

Ejemplo:

```<img src="https://www.example.com/images/logo.png" alt="Logo de Example">```

Ruta Relativa:

Indica la ubicación del archivo en relación con el documento actual
Es útil para mantener una estructura organizada dentro del mismo sitio web.
Facilita el mantenimiento cuando se mueven archivos o carpetas

Ejemplo:

```<img src="images/logo.png" alt="Logo de Mi Sitio">```

Aquí, images/logo.png significa que el archivo de imagen está dentro de la carpeta images, que está en el mismo nivel que el archivo index.html.
sin espacios 
alt es el texto q saldria sino carga la imagen
Los enlaces en HTML se crean con la etiqueta ```<a>.```

Gracias a ellos, podemos saltar de un documento a otro, lo que hace posible la navegación en la web.
Para decir a dónde lleva el enlace, usamos el atributo href dentro de la etiqueta ```<a>.```
La etiqueta ```<a>``` es de línea, lo que significa que puede ir dentro de un texto.

Ejemplo básico:

Tipos de enlaces:

Enlaces a páginas externas:
Se usan para dirigir a sitios fuera de nuestra página web.

Enlaces a páginas locales:
Sirven para conectar con otras partes o archivos dentro del mismo sitio web

```<a href="index.html">Inicio</a>```

A veces, las páginas HTML son muy largas y queremos movernos dentro de la misma página sin recargarla.

Para hacerlo, se usan anclas, que son puntos dentro del documento a los que podemos enlazar.

Las anclas se crean con el atributo id en una etiqueta.

Ejemplo para crear una ancla:

```<h2 id="seccion1">Sección 1</h2>```
Luego, para crear un enlace hacia esa ancla, usamos la etiqueta ```<a>``` con href seguido de # y el nombre del id.

Ejemplo de enlace interno:

```<a href="#seccion1" title="Sección 1">Ir a la sección 1</a>```

También se puede enlazar una ancla que esté en otra página, escribiendo el nombre del archivo y luego # más el id.

os elementos semánticos son muy importantes porque dan significado al contenido del código HTML.

Las etiquetas como ```<span> y <div>``` se usan para agrupar contenido, pero no tienen valor semántico, es decir, no indican qué tipo de información contienen, solo sirven para organizar.

En cambio, el HTML semántico describe mejor el contenido, haciendo el código más claro y fácil de entender tanto para personas como para los buscadores.

Ejemplos de elementos semánticos:

```<header>``` : Encabezado de una página o sección.

```<footer>``` : Pie de página.

```<article>``` : Artículo o contenido independiente

```<section>``` : Sección del contenido

```<nav>``` : Zona de navegación (menús o enlaces)

<```figure>``` : Contiene imágenes, gráficos o ilustraciones

Los elementos semánticos son muy importantes porque ayudan a dar significado al contenido del código HTML.
Las etiquetas como <span> (contenido en línea) y <div> (contenido en bloque) sirven para agrupar elementos, pero no tienen valor semántico, o sea, no explican qué tipo de contenido contienen
En cambio, el HTML semántico permite describir el contenido correctamente, ayudando a los navegadores y a los desarrolladores a entender mejor la estructura de la página.

Ejemplos de elementos semánticos:

```<header>``` : Encabezado de la página o sección

```<footer>``` : Pie de página.

```<article>``` : Artículo o bloque de contenido independiente

```<section>``` : Sección del documento.

```<nav>``` : Área de navegación

```<figure>``` : Imagen, gráfico o ilustración con su descripción

La validación de HTML es el proceso de comprobar que el código cumple con los estándares del World Wide Web Consortium (W3C).
Sirve para detectar y corregir errores en el código que pueden causar problemas al mostrar la página en distintos navegadores
El validador HTML del W3C es una herramienta gratuita en línea que permite revisar si el código HTML está bien escrito
Se puede usar de varias formas:
Escribiendo o pegando el código directamente
Subiendo el archivo HTML
O introduciendo la dirección (URL) de la página web
Los formularios web se usan para interactuar con el usuario y permitir que este envíe información a la aplicación web.
Esa información puede procesarse de distintas formas, dependiendo de lo que necesite la aplicación.
Tipos de controles más comunes:
Campos de texto ```(<input type="text">)```
Campos de contraseña ```(<input type="password">)```
Botones de opción o radio buttons``` (<input type="radio">)```
Casillas de verificación o checkboxes ```(<input type="checkbox">)v
Campos para subir archivos ```(<input type="file">)```
Listas de selección ```(<select>)```
Áreas de texto ```(<textarea>)```
Botones ```(<button> o <input type="submit">)```
```La etiqueta <form> se usa para crear formularios que permiten al usuario enviar datos a un servidor o ejecutar alguna acción dentro de una página web.```

```Atributos comunes del <form>:```

action: Define la URL a la que se enviarán los datos del formulario para su procesamiento. Es el destino del formulario.
method: Indica el método de envío de los datos (por ejemplo, GET o POST).
enctype: Determina cómo se codifican los datos antes de enviarse al servidor. Se usa principalmente cuando se suben archivos.
Las etiquetas ```<select> y <option>``` se usan para crear menús desplegables en los formularios.
Permiten que el usuario elija una opción dentro de una lista predefinida de valores.

Atributos comunes:

name: Define el nombre del control que se enviará al servidor. Este nombre actúa como clave cuando se mandan los datos del formulario.
id: Asigna un identificador único al elemento. Sirve para asociarlo con una etiqueta ```<label>.```
size: Determina cuántas opciones serán visibles al mismo tiempo en el menú sin necesidad de desplazarse.
multiple: Permite seleccionar varias opciones a la vez. Si se usa, el menú se convierte en una lista múltiple.
value: Indica el valor que se enviará al servidor cuando se seleccione esa opción.

Apuntes Tablas en HTML:

Las tablas sirven para mostrar información tabulada, es decir, organizada en filas y columnas.

Antes de los CSS, las tablas se usaban también para maquetar páginas web (por ejemplo, dividir la página en secciones).

Hoy en día, no se recomienda usar tablas para maquetar, ya que eso se hace con ```<div>``` y CSS.

El uso adecuado de las tablas es mostrar datos estructurados.

Etiquetas principales de tablas
TAG	Descripción	Atributos comunes	
```<table>```	Define el inicio de una tabla en HTML.	border: grosor del borde.
```<thead>```	Agrupa el encabezado de la tabla normalmente contiene ```<th>```.	No tiene atributos específicos
```<tbody>```	Agrupa el cuerpo de la tabla. Separa el contenido del encabezado y pie.	No tiene atributos específicos
```<tfoot>```	Agrupa el pie de la tabla, usado para resúmenes o información final.	No tiene atributos específicos
