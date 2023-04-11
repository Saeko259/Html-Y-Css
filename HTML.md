# <b>HTML</b>

Es un lenguaje de hipertexto para estructurar páginas web. Este lenguaje está basado en etiquetas que se utilizan para definir el contenido y estructura de la página web. Especificando elementos como texto, imágenes, formularios y enlaces.

Una pagina web tiene tres partes, la cabecera (head), el cuerpo (body) y el pie (footer).

## Estructura

Un layout es la manera en que organizamos nuestra pagina, por lo que es una buena practica seria dividir nuestra pagina en secciones para organizarla. Para esto usamos <!sections> <!/sections>

<b>nav</b> = Definir la seccion de navegacion de una pagina web

<b>article</b> = Definir el contenido de una pagina web, como un articulo o blog.

<b>aside</b>  = Definir una seccion complementaria en forma de una barra lateral.

<b>!Doctype</b> = nos crea la estructura base de html

<b>Div</b> = división de contenido, o agrupar datos.

<b>Label for = "NombreEiqueta"</b> = Se usa para asignar etiquetas o nombres a distintas partes del texto. Ejemplo:

````html
<label for = "Nombre">Nombre que aparece</label>
````
## Etiquetas

Se utilizan para indicar al navegador como se debe mostrar y procesar el contenido de una pagina web. Tienen diferentes partes, algunas de estas son las siguientes:

|Parte de Etiqueta|funcionamiento|Uso|
|---|---|---|
|Etiqueta de partida|Se usa para indicar el inicio de una etiqueta, se usa el "<>".| Un ejemplo de un etiqueta para iniciar un parrafo es ````<p>````
|Atributos| Proporcionan informacion adicional a una etiqueta o modifican su comportamiento. Se agregan a la ruta de apertura y se definen con un nombre y valor|````<img scr="ruta de la imagen">````
|Contenido|Texto dentro de una etiqueta| ````<p>Hola</p>````
|Etiqueta de cierre| Es el ultimo elemento de una etiqueta, se usapara indicar el cierre de esta|````<p>Hola</p>````

## ETIQUETAS SEMANTICAS



## ETIQUETAS DE TITULO

Con la etiqueta ``<hn>`` podemos escribir un titulo en negrilla en el body. Donde n es el numero del titulo, entre mayor sea n mas pequeño sera el titulo, los tres mas usados son 1,2 y 3. Para indicar el titulo de nuestra pagina usamos ``<header></header>``; El titulo de una pagina se veria tal que así:

````html
<header><h1>Hola Mundo</h1></header>
````


## ETIQUETAS DE PARRAFO

Las etiquetas de parrafo en html son ele,entos que se utilizan para definir el contenido de un párrafo en una pagina web. <!p> para iniciar el texto o parrafo y <!/p> para finalizar el parrafo. Dentro de esta etiqueta podemos poner un texto en negrilla con <!b> . Podemos dejar un espacio o salto de linea con <!br>.

````html
    <br>
    <p> Esto es un ejemplo de un  parrafo con una palabra en <b>negrilla</b> </p>
    <br>
````

Podemos usar ``<span></span>`` para hacer comentarios cortos, tal que así:

````html
<span> Que pasa pe</span>
````

Si queremos que un elemento tenga sangria, usamos ````<li></li>````.

````html
<li>Hola</li>
````
## ETIQUETAS DE MULTIMEDIA

Son usadas para agregar imagenes, videos y elementos, tal como lo dice, multimedia:

|etiqueta|descripcion|parametros|
|---|---|---|
|img | tiene un atributo scr que determina la ubicacion de un archivo.|<b>src</b> = url de la imagen, <b>alt</b> = texto o descripcion corta; <b>name</b> = nombre de la imagen.
|picture| contenedor que puede tener distintas imagenes, o distintas versiones de una imagen| N/a
|figure|Imagen con pie o descripcion| N/a|

#### <b>Atributos de etiquetas multimedia</b>

1. Autoplay : Para que el video empiece automaticamente.
2. Controls : Visualiza los controles.
3. Loop: Que el video se repita infinitamente.
4. preload: EL video y sus datos se pueden precargar.
5. scr: Url o origen del video.
6. Height y width:  Especifica largo y ancho del video.
````html
    <video controls autoplay loop scr = "video.mp4" >
````

### <b>La etiqueta image</b>

Nos permite insertar una imagen, sea del internet o del computador, debemos poner un /> al final de esta para cerrarla, se ve tal que asi:

````html
<img width="200px" height="200px" src='./yanfry.jpg'/>
````

### <b>La etiqueta <video scr =  > </b>

Se utiliza para mostrar un video en una pagina web:
````html
<video scr = "video.mp4">
````

## Etiquetas de formulario

Se utilizan para etiquetar diferentes campos de un formulario HTML. Las mas usadas son:

````html
<form> , <input> , <textarea> , <select> and <option>, <label>, <button>, <fieldset> y <legend>. 
````

### Etiqueta input

La etiqueta ``<input>`` tiene diferentes parametros, la cual determinara el tipo de dato que le pedira al usuario, se usa de la siguiente forma:
````html
    <input type = "month">
````

Los parametros en el input, cambian la manera en la que se pide el dato, los principales son:

    month, time, email, password, name, range, radio ( el cual podemos usar para tener opciones circulares).

El input radio, se ve asi:

<label>A<input type="radio" name ="c" value = "v">

La manera de escribirlo es asi: 

````html
<label>A<input type="radio" name ="c" value = "v">
````
### Etiqueta select

Podemos usar select para tener selecciones multiples de una sola solucion, tal que asi:
 ````html
 <select name ="seleccion"  >
 <option value ="A">A</option>
 </select>
````
Si queremos que nos muestre las opciones y no tengamos que abrir un mini-menu que nos muestre las opciones, despues del "seleccion" ponemos un multiple, tal que asi:
 ````html
 <select name ="seleccion" multiple >
 <option value ="A">A</option>
 </select>
````