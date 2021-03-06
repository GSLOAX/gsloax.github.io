---
layout: gsloax
title: Desarollo Web
---

## 1ª. Sesión: HTML

### [Primer Documento HTML](http://www.librosweb.es/xhtml/capitulo_2/el_primer_documento_html.html)

```
<!doctype html>
<html lang="es">
  <head>
    <title>El primer documento HTML</title>
  </head>
  <body>
    <p>El lenguaje HTML es <strong>tan sencillo</strong> que
    prácticamente se entiende sin estudiar el significado de sus
    etiquetas principales.</p>
  </body>
</html>
```

### [¿Qué es HTML?](http://www.librosweb.es/xhtml/capitulo_1.html)

Definiéndolo de forma sencilla, *HTML es lo que se utiliza para crear todas las páginas web de Internet*. Más concretamente, HTML es el lenguaje con el que se *escriben* la mayoría de páginas web.

Los diseñadores utilizan el lenguaje HTML para crear sus páginas web, los programas que utilizan los diseñadores generan páginas escritas en HTML y los navegadores que utilizamos los usuarios muestran las páginas web después de leer su contenido HTML.

Aunque HTML es un lenguaje que utilizan los ordenadores y los programas de diseño, es muy fácil de aprender y escribir por parte de las personas. En realidad, HTML son las siglas de HyperText Markup Language y más adelante se verá el significado de cada una de estas palabras.

El lenguaje HTML es un estándar reconocido en todo el mundo y cuyas normas define un organismo sin ánimo de lucro llamado World Wide Web Consortium, más conocido como W3C. Como se trata de un estándar reconocido por todas las empresas relacionadas con el mundo de Internet, una misma página HTML se visualiza de forma muy similar en cualquier navegador de cualquier sistema operativo.

El propio W3C define el lenguaje HTML como *un lenguaje reconocido universalmente y que permite publicar información de forma global*. Desde su creación, el lenguaje HTML ha pasado de ser un lenguaje utilizado exclusivamente para crear documentos electrónicos a ser un lenguaje que se utiliza en muchas aplicaciones electrónicas como buscadores, tiendas online y banca electrónica.

#### Más

*   [Guía HTML](http://platea.pntic.mec.es/~abercian/guiahtml/)
*   [Manual de HTML5 en español](http://theproc.es/files/5321)
*   [XHTML](http://librosweb.es/xhtml/)

<div class="plink">
<ul>
<li>[http://platea.pntic.mec.es/~abercian/guiahtml/](http://platea.pntic.mec.es/~abercian/guiahtml/)</li>
<li>[http://theproc.es/files/5321](http://theproc.es/files/5321)</li>
<li>[http://librosweb.es/xhtml](http://librosweb.es/xhtml/)</li>
</div>

### [Creación de una página web sencilla con el editor Amaya](http://vimeo.com/4734991)

Navegar con Amaya es como navegar con otros navegadores Web. Por ejemplo, la barra de botones de Amaya incluye botones stop, atrás, adelante, actualizar, home, guardar e imprimir. Pero hay una diferencia importante: para abrir un enlace debes hacer doble clic sobre él. Consulta Activar un enlace para obtener más información.
A diferencia de otros navegadores, Amaya proporciona herramientas para la edición de páginas web. para obtener más información sobre la edición, consulta:
 manual: [es](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/Manual.html.es)

#### [Interfaz de usuario](http://www.mclibre.org/consultar/amaya/amaya/amaya_interfaz.html)

Al ejecutar Amaya por primera vez, el aspecto es éste:

<iframe src="http://www.mclibre.org/consultar/amaya/amaya/amaya_interfaz.html#Interfaz" width="100%" height="400">
  ![](http://www.mclibre.org/consultar/amaya/img/configuracion/interface_1.png)

El interfaz de Amaya es el habitual de las aplicaciones gráficas, combinando elementos típicos de los navegadores con los de los editores:

*   barra de título
*   barra de menús
*   barra de navegación
*   barras de edición
*   ventana de herramientas
*   ventana de trabajo
*   barra de estado
</iframe>

[opinion](http://www.joelonsoftware.com/articles/fog0000000018.html)

### [Limitaciones](http://www.mclibre.org/consultar/amaya/amaya/amaya_problemas.html)

En esta página se comentan algunos problemas de la edición de páginas web con Amaya. Hay que tener en cuenta que Amaya no aplica correctamente bastantes propiedades de las hojas de estilo, así que es necesario comprobar en Firefox que estamos obtenido el resultado esperado.

Faltan por poner bastantes cosas

*   Hojas de estilo alternativas
*   Alineación vertical: vertical-align
*   Espaciado de letras y palabras: letter-spacing y word-spacing
*   Decoración: text-decoration
*   Mayúsculas / minúsculas: text-transform
*   Sombreado: text-shadow
*   Colores de sistema
*   Espacios en blanco: white-space
*   Pseudo-clases y pseudo elementos
*   Fondos
*   Tamaño

## 2ª. Sesión: Texto y Tablas

### Formatos de texto,  caracteres y tipografías

La mayor parte del contenido de las páginas HTML habituales está formado por texto, llegando a ser más del 90% del código de la página. Por este motivo, es muy importante conocer los elementos y etiquetas que define HTML para el manejo del texto.

El lenguaje HTML incorpora al tratamiento del texto muchas de las ideas y normas establecidas en otros entornos de publicación de contenidos. De esta forma, HTML define etiquetas para estructurar el contenido en secciones y párrafos y define otras etiquetas para marcar elementos importantes dentro del texto.

La tarea inicial del editor de contenidos HTML consiste en estructurar el texto original definiendo sus párrafos, titulares y títulos de sección, como se muestra en la siguiente imagen:

#### El espacio: la última frontera

Una cuestión muy importante que queremos tratar antes de empezar a hablar sobre el texto es la del espacio, y concretamente la del espacio entre palabras. Cuando se escribe el HTML, el documento fuente contendrá lo que se conoce como &#8220;espacios en blanco&#8221;, que son los caracteres del archivo que sirven para separar el texto. El carácter de espacio más habitual es el que se obtiene al pulsar la barra espaciadora, pero hay otros, como el tabulador y la marca entre dos líneas independientes de un documento (conocido como retorno o línea nueva).

En el HTML, cuando un carácter de éstos aparece varias veces seguidas, se considera (casi) siempre como un único carácter de espacio.

Por ejemplo, un navegador interpretaría lo siguiente:


como equivalente a:

    &lt;h3&gt;En el principio&lt;/h3&gt;

#### Más

[http://es.html.net/tutorials/css/lesson4.php](http://es.html.net/tutorials/css/lesson4.php)<

### [Edición de texto en Amaya](http://www.mclibre.org/consultar/amaya/amaya/amaya_edicion.html)

<iframe src="http://www.mclibre.org/consultar/amaya/amaya/amaya_edicion.html" width="100%" height="400">
Para indicar a Amaya que se quiere trabajar con una etiqueta (para convertirla en otra, para definir un atributo, para borrar la etiqueta y su contenido, etc.) es necesario seleccionar la etiqueta. Para seleccionar una etiqueta hay que situar primero el cusor en el elemento que se quiere seleccionar (o hacer clic en él si se trata de una imagen), a continuación se puede hacer clic en el nombre de la etiqueta que se muestra en la barra de estado, o pulsar F2 hasta seleccionar la etiqueta deseada. Al seleccionar una etiqueta, Amaya resalta el contenido de la etiqueta mostrando el fondo de color azul. Volviendo a hacer clic en algún lugar de la página desaparece la selección de la etiqueta y reaparece el cursor.
  ![](http://www.mclibre.org/consultar/amaya/img/edicion/amaya_edicion_seleccion_2.png)
</iframe>

[http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/editing_iso-latin-1_characters/about_white_space_handling.html.es](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/editing_iso-latin-1_characters/about_white_space_handling.html.es)

### [Agrupación de Elementos con Div y Span](http://es.html.net/tutorials/css/lesson8.php)

Los elementos `&lt;span&gt;` y `&lt;div&gt;` se usan para agrupar y estructurar un documento, y se usarán, a menudo, junto con los atributos class e id. Estos dos elementos de HTML son, precisamente, de importancia clave en lo que se refiere a CSS.

#### [¿Que es CSS?](http://es.html.net/tutorials/css/lesson8.php)

CSS se puede considerar la media naranja de HTML. Y a la hora de escribir código, no hay punto de comparación en cuanto a su situación: HTML se encarga del contenido en bruto de la página (la estructura), mientras que CSS le proporciona ese toque elegante (la presentación).

Se pueden añadir estilos con CSS recurriendo al atributo style. Por ejemplo, por medio de dicho atributo se puede establecer el tamaño y tipo de fuente de un párrafo:



Una de la características &#8220;elegantes&#8221; de CSS es la posibilidad de gestionar la presentación de manera centralizada.. En vez de usar el atributo style en cada etiqueta de inicio, se puede indicar al navegador, de una sola vez, cómo tiene que presentar el texto en la página:



Esta lección sólo prentede ser una breve introducción a CSS.

#### html.net
[http://es.html.net/tutorials/css/lesson8.php](http://es.html.net/tutorials/css/lesson8.php)

### [Tablas](http://librosweb.es/xhtml/capitulo_7.html)

![](http://librosweb.es/img/xhtml/f0701.gif)

Desde sus primeras versiones, HTML incluyó el soporte para crear tablas de datos en las páginas web. Además de ser sencillo, el modelo definido por HTML es muy flexible y bastante completo.

Las tablas en HTML utilizan los mismos conceptos de filas, columnas, cabeceras y títulos que los que se utilizan en cualquier otro entorno de publicación de documentos:



#### [Para crear una nueva tabla en Amaya](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/Tables.html.es#page_body)

1.  Sitúa el cursor en la posición del documento en la que quieres crear la tabla.
    Haz clic en el botón Tabla, o elige el comando de menú Xhtml > Tabla. Se abrirá una caja de diálogo.
2.  Escribe el número inicial de filas y columnas de la nueva tabla, y especifica el grosor del borde.
3.  Haz clic en el botón Confirmar. Amaya crea una representación gráfica de la tabla.
4.  El cursor se sitúa automáticamente en el espacio situado sobre la tabla que está reservado para la leyenda de la tabla. Puedes borrar este espacio si no necesitas una leyenda.
5.  Las celdas de la nueva tabla están vacías. Para insertar contenido en ellas, haz clic en el interior de la celda e inserta texto, imágenes, etc. Utiliza las flechas de desplazamiento para moverte de una celda a otra.

## 3ª. Sesión: Vinculos, Imagenes, Multimedia

### [Imágenes](http://librosweb.es/xhtml/capitulo_6.html)

#### [Insertar imágenes en Amaya](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/ImageMaps.html.es)

Para insertar una imagen, elige el comando de menú Xhtml > Imagen, haz clic en el botón Gráficos Botón Gráficos, o utiliza el atajo de teclado (Control-t en Windows, Control-i en Unix). La caja de diálogo que se abre te permite escribir el nombre del archivo y su texto aternativo (ALT) de la imagen que quieres insertar.

Para suministrar una descripción larga de una imagen que represente una información compleja, debes hacerlo en un archivo distinto y enlazarlo proporcionando el URI en el atributo longdesc. Este comando se encuentra también en el menú Atributos.

Para que te sea más fácil encontrar una imagen, puedes elegir el tipo de archivo para que la caja de siálogo de selección de archivo muestre únicamente los archivos del tipo indicado.
[http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/ImageMaps.html.es](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/ImageMaps.html.es)</span>

### [Hipervínculos](http://librosweb.es/xhtml/capitulo_4.html)


#### [Crear vinculo un enlace en Amaya](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/Links.html.es#page_body)

Para crear un enlace a un destino o a un elemento destino situado en el mismo documento:

1.  Selecciona el texto del enlace que estás creando.
2.  Haz clic en el botón Enlace. El cursor cambiará de tener forma de flecha a tener forma de mano.
3.  Haz clic en el icono destino para crear el enlace.

[http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/Links.html.es](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/Links.html.es)

### [Multimedia](http://es.wikipedia.org/wiki/HTML5_video)



HTML5 video es un elemento introducido en la nueva especificación HTML5 para el tratamiento y reproducción de vídeos o películas, este elemento, remplaza parcialmente al elemento objet. HTML5 Video es concebida por sus creadores para convertirse en la nueva forma estándar para mostrar vídeo en línea pero se ha visto obstaculizada por la falta de acuerdo en cuanto a que los formatos de vídeo debe ser compatible con el elemento de vídeo.

<ul>
<li>[http://es.wikipedia.org/wiki/HTML5_video](http://es.wikipedia.org/wiki/HTML5_video)</li>
<li>[http://diveintohtml5.info/video.html](http://diveintohtml5.info/video.html)</li>
<li>[https://developer.mozilla.org/en-US/docs/Web/HTML/Using_HTML5_audio_and_video    ](https://developer.mozilla.org/en-US/docs/Web/HTML/Using_HTML5_audio_and_video)</li>
</ul>

### [Formularios](http://librosweb.es/xhtml/capitulo_8.html)



HTML es un lenguaje de marcado cuyo propósito principal consiste en estructurar los contenidos de los documentos y páginas web. Sin embargo, HTML también incluye elementos para crear aplicaciones web. El estándar HTML/XHTML permite crear formularios para que los usuarios interactúen con las aplicaciones web.

[http://www.mclibre.org/consultar/amaya/amaya/amaya_edicion.html#Formulario](http://www.mclibre.org/consultar/amaya/amaya/amaya_edicion.html#Formulario)</span>

#### Ojo

[No todo etiqueta funciona en todo navegador](http://en.wikipedia.org/wiki/Comparison_of_layout_engines_%28HTML5%29)

#### Más
[http://en.wikipedia.org/wiki/Comparison_of_layout_engines_%28HTML5%29](http://en.wikipedia.org/wiki/Comparison_of_layout_engines_%28HTML5%29)</div>

## 4ª. Sesión: CSS y Javascript

### [Javascript](http://librosweb.es/javascript/])

JavaScript es un lenguaje de programación que se utiliza principalmente para crear páginas web dinámicas.

Una página web dinámica es aquella que incorpora efectos como texto que aparece y desaparece, animaciones, acciones que se activan al pulsar botones y ventanas con mensajes de aviso al usuario.

Técnicamente, JavaScript es un lenguaje de programación interpretado, por lo que no es necesario compilar los programas para ejecutarlos. En otras palabras, los programas escritos con JavaScript se pueden probar directamente en cualquier navegador sin necesidad de procesos intermedios.

A pesar de su nombre, JavaScript no guarda ninguna relación directa con el lenguaje de programación Java.



#### [Conceptos Básicos de JavaScript](http://librojquery.com/#conceptos-b%C3%A1sicos-de-javascript)

El código JavaScript se encierra entre etiquetas `&lt;script&gt;` y se incluye en cualquier parte del documento. Aunque es correcto incluir cualquier bloque de código en cualquier zona de la página, se recomienda definir el código JavaScript dentro de la cabecera del documento (dentro de la etiqueta `&lt;head&gt;`.

El método menos utilizado, es incluir trozos de JavaScript dentro del código HTML de la página:


<div class="plink">
<ul>
<li>[http://librosweb.es/javascript/utorial_hispano_jQuery](http://librosweb.es/javascript/)</li>
<li>[http://librojquery.com/#conceptos-b%C3%A1sicos-de-javascript](http://librojquery.com/#conceptos-b%C3%A1sicos-de-javascript)</li></div>

#### Suma de Columna de Tabla




#### Más
    [http://www.udel.edu/CIS/474/pconrad/06S/topics/javascript/examples/tables/sumOfAColumn.html](http://www.udel.edu/CIS/474/pconrad/06S/topics/javascript/examples/tables/sumOfAColumn.html)

#### Toggle (Esconder/Mostrar)



#### [jQuery](http://librojquery.com/)


Llamar.toggle() cuando se pinche otra elemento:



#### Jquery y CSS



Selección de elementos en base a su ID

    $('#myId'); // notar que los IDs deben ser únicos por página

Selección de elementos en base al nombre de clase

    $('div.myClass'); // si se especifica el tipo de elemento,
                      // se mejora el rendimiento de la selección

<div class="plink">
<ul>
<li>[http://mundosica.github.io/tutorial_hispano_jQuery
](http://mundosica.github.io/tutorial_hispano_jQuery
)</li>
<li>[http://librojquery.com/](http://librojquery.com/)</li>

</div>

#### [Pre-cargar Imagenes](http://stackoverflow.com/questions/476679/preloading-images-with-jquery)

Mejor hecho con CSS

##### html

    img src="someimg.png" class="hide" alt=""/>

##### css


##### jquery


<div class="plink">

#### Más
[http://stackoverflow.com/questions/476679/preloading-images-with-jquery](http://stackoverflow.com/questions/476679/preloading-images-with-jquery)</div>

### [CSS (Hojas de Estilo)](http://librosweb.es/css/)

CSS es un lenguaje de hojas de estilos creado para controlar el aspecto o presentación de los documentos electrónicos definidos con HTML y XHTML. CSS es la mejor forma de separar los contenidos y su presentación y es imprescindible para crear páginas web complejas.

Separar la definición de los contenidos y la definición de su aspecto presenta numerosas ventajas, ya que obliga a crear documentos HTML/XHTML bien definidos y con significado completo (también llamados &#8220;documentos semánticos&#8221;). Además, mejora la accesibilidad del documento, reduce la complejidad de su mantenimiento y permite visualizar el mismo documento en infinidad de dispositivos diferentes.

Al crear una página web, se utiliza en primer lugar el lenguaje HTML/XHTML para marcar los contenidos, es decir, para designar la función de cada elemento dentro de la página: párrafo, titular, texto destacado, tabla, lista de elementos, etc.

Una vez creados los contenidos, se utiliza el lenguaje CSS para definir el aspecto de cada elemento: color, tamaño y tipo de letra del texto, separación horizontal y vertical entre elementos, posición de cada elemento dentro de la página, etc.

    &lt;link rel="stylesheet" type="text/css" href="/css/estilos.css" media="screen" /&gt;


#### [Selectores](Servidores%20Dominios%20Administraci%C3%B3n%20de%20un%20sitio%20web)

una regla de CSS está formada por una parte llamada &#8220;selector&#8221; y otra parte llamada &#8220;declaración&#8221;.

La declaración indica &#8220;qué hay que hacer&#8221; y el selector indica &#8220;a quién hay que hacérselo&#8221;. Por lo tanto, los selectores son imprescindibles para aplicar de forma correcta los estilos CSS en una página.

A un mismo elemento HTML se le pueden aplicar varias reglas CSS y cada regla CSS puede aplicarse a un número ilimitado de elementos. En otras palabras, una misma regla puede aplicarse sobre varios selectores y un mismo selector se puede utilizar en varias reglas.

#### [CSS en Amaya](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/StyleSheets.html.es)


#### Más
[http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/StyleSheets.html.es](http://stuff.mit.edu/afs/sipb/project/amaya/src/Amaya/doc/html/StyleSheets.html.es)</div>

## 5ª. Sesión: [Publicar en la web](http://es.html.net/tutorials/html/lesson13.php).

### Servidores

[Nginx](http://wiki.nginx.org/NginxEs)

### Logica del Lado del Servidor
#### CGI
Una forma sencilla de producir html dinamicamente en el servidor es con GGI, que son scripts comunalmente escritos en C, perl o php.

#### Frameworks
Hoy en dia mas y mas personas dejan los CGI para utlizar un framework de orientacion a objetos.

##### CakePhp (php)
##### Ruby on Rails (ruby)
##### Django (python)

### Publicación de Datos

#### Ftp
[filezilla](https://filezilla-project.org/)
#### Scp/Ssh
[ssh](https://wiki.archlinux.org/index.php/Secure_Shell_%28Espa%C3%B1ol%29)
#### rsync
[rsync](http://es.wikipedia.org/wiki/Rsync)
## Referencias

aprender mas sobre html
<ul>
  <li>http://www.mclibre.org</li>
  <li>http://www.w3.org/standards/webdesign/</li>
  <li>http://diveintohtml5.info/</li>
  <li>http://www.webplatform.org/</li>
  <li>http://reference.sitepoint.com</li>
  <li>http://www.w3.org/community/webed/wiki/HTML/Training</li>
  <li>https://developer.mozilla.org/en-US/docs</li>
</ul>
