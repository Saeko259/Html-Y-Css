# CSS

En css para acceder a una clase, debemos de poner un punto, luego la clase y un corchete para abrir la clase de esta forma:

````css
.a{
    caracteristica: color;
}
````

Tambien podemos hacer que cuando suceda cierta accion con la clase pase algo, para esto tendriamos que colocar la notacion igual que la anterior pero debemos poner un dos puntos y la accion antes del corchete, tal que asi (el siguiente ejemplo es para cuando pasas el cursor por encima):

````css
.a:hover{
    caracteristica: color;
}
````

## <b> propiedades  varios</b>

|propiedades|descripcion|uso|atributos|
|----|----|----|----|
|display|Es muy importante, determina el tipo de caja o la manera que un elemento/elementos es/son y funciona/n (en relacion a posicion y interaccion con demas elementos)|.a{display: flex;}| flex y grid, flex es para determinar posicion (justify or align), grid es mas para organizacion en general| 
|flex| Aunque sea un atributo de el salen muchas propiedades, como lo son align-items/content/text o justify.text| .a{ display:flex; justify-text:center}|Son principalmente posicionales, left, right, center, end y demas|
|gap|Sirve para determinar el espaciado entre diferentes elementos de un conjunto, esta dentro del flex|.a{ display:flex; gap:10px;}| Despues del gap viene el tamaño|
|margin|El espaciado que hay en todas las direcciones en un objeto| .a{ margin:10px }| Puede ser margin-left, top,etc. Despues del margin viene el tamaño|
|padding|El espaciado que hay entre el contenido y borde de un elemento| .a{padding:10px}|Podemos especificar hacia que direccion es el padding, si colocamos padding-left y demás.|
|border| Se usa para darle un borde a un elemento,  a estos bordes les podemos dar un color, grosor y definir la direccion del borde (border-top, etc). Podemos hacer que el borde sea rondeado con border-bottom/top/-left/right-radius y luego darle tamaño (esto solo es para las esquinas), tambien podemos usar solo border-radius para las 4 esquinas..| .a{border: 2px solid white}|Podemos especificar el color y el grosor|
|text-decoration| Nos permite definir que tiene el texto, si esta subrayado, con una linea en el medio o sin nada|.a{text-decoration:none;}|none (nada) y underline|
|font-$%#|Dependiendo que le siga al font, podemos definir la fuente (font-family), tamaño fuente (font-size)|.a{ font-family:sans;}|Font-family, font-size (para el color de la fuente usamos color)|
|grid|De este tipo de display nacen muchas caracteristicas, como lo son grid-template-columns, un ejemplo de un esquema para organizar en columnas la pagina|.a{grid-template-columns: repeat(5, 2fr)}|En el ejemplo anterior el 5, representa el numero de columnas y el 2fr ( Nose)|