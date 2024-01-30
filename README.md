# ASIX1M4UF1A3_Apunts

## Introducción a GITHUB

Para empezar, hay que crear un repositorio y para esto tendremos que ir a nuestro perfil (arriba a la derecha) hacer click ahí y entrar en ```Your repositories```, una vez dentro saldra una pestaña de color verde la cual pondrá ```NEW```, una vez hecho nos llevará a esta pantalla:

<br>

![Imagen de github](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/img/github.png)

<hr>

En el cuadrado de ```Repository name``` pondremos el nombre que queremos que se llame nuestro repositorio y le daremos a que nuestro repositorio sea público, además de darle click a que me añada un README file, una vez hecho todo esto le daremos al boton verde de abajo a la derecha que pone ```Create repository```.

Una vez creado nuestro repositorio tendremos que clonarlo y para esto dentro de nuestro repositorio nos saldrá una pestaña de color verde que pone ```CODE```, le daremos ahí y nos abrirá el despegable de a continuación:

<hr>

![Imagen desplegable](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/img/desplegable.png)

<hr>

Copiaremos el link que nos sale y abriremos el terminal en el cual introduciremos lo siguiente:

```
git clone (link del repositorio que hemos copiado anteriormente)
```

Y de esta forma podremos editar desde local y luego mediante estos comandos en el terminal podremos subirlo a github:

```
git init
git add .
git commit -m "nombre identificativo de lo que estamos subiendo"
git push origin main
```


## Introducción a Markdown

Para escribir un título se utiliza un corchete "#", cuantos más corchetes se pongan más pequeño será el título con un máximo de hasta 6 corchetes. Ejemplos:

```

## Título grande con dos corchetes

### Título mediano con tres corchetes

#### Título mediano con cuatro corchetes

##### Título pequeño con cinco corchetes

###### Título más pequeño con seis corchetes

```

Para crear una lista ordenada es tan simple como poner el numero y un punto a continuacion:

1. Primera opción de menú

```
1. Primera opción de menú
```

2. Segunda opción de menú

```
2. Segunda opción de menú
```

3. Segunda opción de menú

```
3. Segunda opción de menú
```

Para crear una lista desordenada, se pueden hacer de diferentes tipos mediante un asterisco, mediante un signo de resta y mediante un signo de suma:

* Primera lista desordenada con un asterisco

```
* Primera lista desordenada con un asterisco
```

* Segunda lista desordenada con un asterisco

```
* Segunda lista desordenada con un asterisco
```

- Tercera lista desordenada con un signo de resta

```
- Tercera lista desordenada con un signo de resta
```

- Cuarta lista desordenada con un signo de resta

```
- Cuarta lista desordenada con un signo de resta
```

+ Quinta lista desordenada con un signo de suma

```
+ Quinta lista desordenada con un signo de suma
```

+  Sexta lista desordenada con un signo de suma

```
+  Sexta lista desordenada con un signo de suma
```

Tambien se pueden crear submenus dentro de estas listas dandole al tab y poniendo un numero junto con un punto y un espacio a continuacion o en vez de un numero se puede añadir un asterisco:

* Primera lista desordenada con un asterisco
    1. Primer submenú con número y punto

    ```
    1. Primer submenú con número y punto
    ```

    2. Segundo submenú con número y punto

    ```
    2. Segundo submenú con número y punto
    ```

* Segunda lista desordenada con un asterisco
    * Tercer submenú con asterisco 
    ```
    * Tercer submenú con asterisco 
    ```
    * Cuarto submenú con asterisco 
    ```
    * Cuarto submenú con asterisco 
    ```

_Para escribir un texto en cursiva se puede hacer de dos maneras, mediante un asterisco al principio y el al final o con una barra baja al inicio y al final de la frase tal como se puede ver a continuacion:_
```
_Este texto esta en cursiva_
*Este texto esta en cursiva*
```

__Para escribir un texto en negrita se puede hacer de dos maneras también, mediante dos asteriscos tanto al principio como al final o con dos barras bajas tanto al principio como al final tal como se puede ver a continuacion:__
```
__Este texto esta en cursiva__
**Este texto esta en cursiva**
```
__*Para escribir un texto en cursiba y negrita habra que hacerlo tal como se ve a contiuación*__
```
__*Este texto esta en cursiva:*__
```
Para insertar una imagen hay que abrir corchetes para introducir muy brevemente lo que se ve en la imagen, justo depues de los corchetes se abren parentesis y dentro de estos se pone el link de la imagen que tiene que estar subida en nuestro repositorio de github, de tal manera que tendria que quedar tal como en la imagen de a continuación:

```
![Imagen de como insertar imagenes](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/img/planeta.jpg)
```

![Imagen de como insertar imagenes](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/img/planeta.jpg)

Para crear columans hay que hacer tal que asi:
```
|Primera Columna|Segunda Columna|Tercera Columna|
```

Para aliniar columnas se hace mediante los ":" de tal manera que si no pones anda se alinea solo a la izquierda pero si pones los ":" a los lados se alineará al dentro mientras que si los ponemos al final el texto se alineará a la derecha y para asignar una amplitus a cada columna será mediante giones medios, contra mas "-" mas amplia será y de lo contrario mas estrecha será.

```
|Primera Columna|Segunda Columna|Tercera Columna|
|-----------|:-----------:|-----------:|
```

Para poner contenido dentro de estas se habrá que hacer tal como se ve a continuación:

```
|Primera Columna|Segunda Columna|Tercera Columna|
|-----------|:-----------:|-----------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo Cebra|Gris|Blanco|
|Clase|Asix1|M4|

```
De tal manera habiendo seguido los pasos anteriores, una tabla se veria tal que así:

|Primera Columna|Segunda Columna|Tercera Columna|
|----------|:----------:|------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo Cebra|Gris|Blanco|
|Clase|Asix1|M4|

Para crear una lista con casillas:
```
-[ ] Opción A
-[X] Opción B
-[ ] Opción C
```
De tal manera que quedaria tal que asi:
-[ ] Opción A
-[X] Opción B
-[ ] Opción C

## Introducción a HTML


Para crear un cuerpo de texto para poder escribir hay que escribir lo siguiente:
```
HTML:5
```
Quedaria tal que asi:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
````
En HTML hay varias etiquetas las cuales sirven para "marcar" el texto de una página web con el fin de dar instrucciones al navegador sobre como mostrarlo como por ejemplo:

```
<a> </a>
<p> </p>
<strong> </strong>
<h1> </h1>
<h2> </h2>
<h3> </h3>
<h4> </h4>
<h5> </h5>
<h6> </h6>
<title> </title>
<head> </head>
<body> </body>
<html> </html>
<li> </li>
<ol> </ol>
<ul> </ul>
<hr>
<br>
<img>
<link>
```
Aparte de las etiquetas tambien hay atributos como por ejemplo:

```
class=""
href=""
id=""
alt=""
witdh=""
rel=""
type=""
```

Para escribir un párrafo:

```<p>```    texto visible    ```</p>```

Para escribir un párrafo con etiqueta:

```<p class=”valor”>```     texto visible       ```</p>```

Para escribir un párrafo con contenido en negrita:

```<p>```  texto visible  ```<strong>```  texto visible en negrita  ```<strong>```  texto visible  ```</p>```

Para que sirven cada etiqueta que viene dentro del cuerpo de texto 
```
<html lang=”en”>
<head> contenido no visible por los visitantes
<meta charset=“UTF - 8”> añade la (ç, ñ, …)
<title> texto visible </title>  esto sirve para ponerle nombre a la pestañita de arriba de google
</head>
<body> 
Aquí vendrá todo el contenido de la página visible
Hay etiquetas de bloque y etiquetas de líneas
</body>
</html>
```
Para hacer un título / encabezado se hace con:

 ```<h1>``` texto visible ```</h1>```

 ```<h2>``` texto visible ```</h2>```

 ```<h3>``` texto visible ```</h3>```

 ```<h4>``` texto visible ```</h4>```

 ```<h5>``` texto visible ```</h5>```

 ```<h6>``` texto visible ```</h6>```

De modo que contra mas grande sea el número mas pequeña es la tipografia

Para poner en negrita un texto se hace con:

```<strong>``` texto visible en negrita ```</strong>```

Por ejemplo: si queremos remarcar en negrita una parte de una frase seria tal que asi:
```<strong>``` 2 k ```</strong>``` de almejas limpias de arena

Para hacer una lista desordenada se hace con:
```
<ul>
    <li>2 dientes de ajo</li>
    <li>2 cebollas</li>
    <li>1 hoja de laurel</li>
</ul>
```

En cambio para hacer una lista ordenada se hace asi:
```
<ol>
    <li>Primero...</li>
    <li>A continuacion...</li>
    <li>Finalmente...</li>
</ol>
```

Para escribir un párrafo se hace:

```<p>``` párrafo visible ```</p>```

Para hacer un espacio se hace con la etiqueta:

```<br>```

Para incorporar una imagen es tal que asi:

```<img src="../img/almejas en agua.webp" alt="almejas en agua" width="200">```

Seleccionas la carpeta donde esta, luego eliges la imagen que quieres poner, justo despues de alt="" entre las comillas pones un titulo que quieras que salga cuando pongas el cursor encima y en width eliges el tamaño de px que quieres que tenga la imagen.

Para poner una linia horizontal separadora se hace con esta etiqueta:

```<hr>```

y quedaria tal que asi:

<hr>

El elemento ```<div></div>``` es un contenedor que se utiliza para estructurar y organizar el contenido de una página web, es una etiqueta sin un significado semántico pero es útil para el diseño o maquetación de una página web.

Hay varias etiquetas que se utilizan igual que el ```<div>``` pero tienen un nombre diferente y estas son:

```<header>``` Se utiliza para hacer un contenedor en el encabezado de una página```</header>```

```<section>``` Se utiliza para hacer un contenedor por el cuerpo de la pagina```</section>```

```<article>``` Se utiliza para hacer un contenedor por el cuerpo de la pagina```</article>```

```<footer>``` Se utiliza para hacer un contenedor en el pie de página```</footer>```

Para ir de un sitio a otro haciendo click en alguna frase:

```<a href="#Primer plato: Almejas a la marinera">Volver a arriba</a>```

En esta parte lo que hacemos es introducir un href="" dentro de la etiqueta ```<a>``` indicando a donde queremos ir, en este caso a "#Primer plato: Almejas a la marinera" haciendo click en el texto de "Volver arriba" y le ponemos el "#" a Primer plato para indicar que a donde queremos que nos lleve esta en esa pagina y no de otra.

Si queremos ir de una pagina a otra haciendo click en una palabra se hace tal que asi:

```<a href="./primer_plato/index2.html">Primer plato: Almejas a la marinera</a>```

Ponemos un ```href=""``` dentro de la etiqueta ```<a>``` indicando a donde quiero ir con un ./ y la direccion del html al que quiero ir y justo despues la palabra a la cual haremos click para que nos lleve hasta allí

Si queremos hacer que nos lleve a otra pagina pero haciendo click en una foto es tal que asi:

```<a href="./segundo_plato/index3.html">Segundo plato: Calabazines rellenos de carne picada <br><img src="./img/segundo plato.webp" alt="Calabazines rellenos de carne picada" width="400"></a>```

Lo que hemos hecho es lo mismo que arriba pero introduciendo un img scr="direccion de la imagen" dentro de la etiqueta ```<a>``` para que cuando hagamos tanto click en la imagen como en la frase de Segundo plato... nos lleve al otro html que queremos.

```<h1 id="Primer plato: Almejas a la marinera">Primer plato: Almejas a la marinera</h1>```

Esto lo que nos hace es que cuando le demos click a "Volver a arriba" nos llevará a "Primer plato: Almejas a la marinera"


Otro ejemplo seria:

```
<ul>
    <li><a href="#Ingredientes">Ingredientes</a></li>
</ul>
```

Esto lo que hace es que cuando le des click a "Ingredientes" que esta en una lista desordenada, te lleve al apartado de Ingredientes, pero para que te lleve hay que poner lo siguiente:

```<h2><a id="Ingredientes">Ingredientes</a></h2>```

Esto es un título llamado Ingredientes el cual es a donde nos llevará porque con el ```href=""``` lo que indicamos es de donde sale mientras que con el ```id=""``` indicamos a donde va a parar.
Otro dato importante es que al hacer click nos lleva a un apartado que hemos elegido pero dentro de esa misma página ya que le hemos puesto un ```#``` para que sepa que no es ningún link ni un apartado de otra página.

Para hacer tablas tenemos diferentes etiquetas:

```<table>``` Para crear una tabla tenemos que marcar el inicio y final de la tabla con esta etiqueta ```</table>```

Dentro de la etiqueta ```<table>``` tenemos diferentes etiquetas las cuales sirven para dividir la tabla en el encabezado, el cuerpo y el pie de página mediante las siguientes etiquetas:

```<thead>``` Esta etiqueta se utiliza para el encabezado de la tabla ```</thead>```.

```<tbody>``` Esta etiqueta se utiliza para el cuerpo de la tabla ```</tbody>```.

```<tfoot>``` Esta etiqueta se utiliza para el pie de pagina de la tabla ```</tfoot>```.

Dentro de cada una de estas 3 agrupaciones utilizaremos las siguientes etiquetas, cada uno para su debido uso:

La etiqueta ```<tr> </tr>``` se utiliza para poner filas dentro de la tabla.

Dentro de estas etiquetas ```<tr> </tr>``` se pondran las etiquetas ```<th> </th>``` para la parte del encabezado para resaltar esa fila de las otras.

Dentro de estas etiquetas ```<tr> </tr>``` se pondran las etiquetas ```<td> </td>``` las cuales se usan para celdas regulares que contienen datos.

Un ejemplo de una tabla con su encabezado ```<thead>``` resaltando la fila del encabezado con ```<th> </th>``` y su cuerpo ```<tbody>``` rellenando las celdas con las etiquetas ```<td> </td>``` seria tal que asi:

```
<table border="1">
    <thead>
      <tr>
        <th>Encabezado de Columna 1</th>
        <th>Encabezado de Columna 2</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Dato 1 fila 1</td>
        <td>Dato 2 fila 1</td>
      </tr>
      <tr>
        <td>Dato 1 fila 2</td>
        <td>Dato 2 fila 2</td>
      </tr>
    </tbody>
  </table>
```
El cual quedaria visualmente asi:

![Imagen de una tabla](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/img/tabla.png)

Si queremos hacer o poner algun tipo de comentario en un documento ```HTML``` seria mediante el siguente comando:

```<!-- Este es un comentario en HTML -->```


## Introducción a CSS

El css es una hoja de estilo que sirve para darle estilo y diseño a uno o varios documentos html.

Los estilos se pueden asociar de diferentes maneras a los elementos HTML dado que estos pueden estar ubicados en diferentes sitios como por ejemplo:

* En la cabecera del documento:

Aquí lo que podemos ver es como todas las etiquetas ```<p>``` tendran un color rojo y estará el texto alineado al centro.

```
          <!DOCTYPE html>
          <html lang="ca">
             <head>
                <!-- ... →
               <style> 
                  p { 
                    text-align:center; 
                    color:red 
                  } 
                </style>
             </head>
             <body>
```

* En la propia etiqueta:

Aquí lo que podemos ver es como dentro de la etiqueta ```<p>``` hemos añadido un atributo para dar estilo a esa etiqueta ```style=""``` poniendo dentro de las comillas el estilo que le queremos dar al texto.

```
<p style="text-align:center; color:red">Paràgraf centrat vermell</p>
```

* En un documento externo: 

Se coloca las propiedades de estilo en un documento externo con extensión ```.css``` y desde el documento ```HTML``` se enlaza con esta hoja de estilo con la etiqueta ```<link>``` dentro del elemento ```<head>```. Por ejemplo:

```
<! DOCTYPE html> 
<html>
   <head>
 <link rel="stylesheet" href="estils.css" type="text/css" />
   </head>
   <body>
      <p>Paràgraf centrat vermell</p>
   </body>
</html>
```

y el fichero estilos.css el siguiente contenido:

```
p {
      text-align: center;
      color: red;
}
```

El hecho de usar una hoja aparte para el diseño en ```.css``` es que podemos utilizar esta misma hoja para diferentes documentos ```HTML```.

Una hoja de estilos es un conjunto de reglas las cuales definen la estética de un documento HTML, cada una de estas reglas esta formada por un selector y por un conjunto de declaraciones:

```
   selector{ 
        declaració_1 
        ... 
        declaració_n 
   }
```

Un ejemplo real seria asi:

```
   p {
        font-size: 10pt;
        background-color: gray;
   }
```

Donde la ```p``` es el selector que tiene dos declaraciones.

Para agrupar selectores se puede hacer con una ```,``` tal que así:

```
h1,p {color: green}
```

Y de esta manera tanto los elementos de las etiquetas ```<h1>``` como los elementos de las etiquetas ```<p>``` tendrán un color verde.

Existen diferentes tipos de selectores:

* Selector de elementos: 

```
a {
   color: red;
}
```

Afecta a todos los elementos ```<a>``` del documento ```HTML```.

* Selecctor de clase:

```
.example {
   property: value;
   property2: value2;
}
```

```
<p class="example">
<li class="example">
```

Afecta a todos los elementos que tengan un atributo ```class=""``` con el valor especificado del documento ```HTML```.

* Selector de id: 

```
#example {
   property: value;
   property2: value2;
}
```

```
<p id="example">
```

Afecta a todos los elementos ```HTML``` que tienen un atributo ```id=""``` con el valor especificado.

* Selector universal: 

```
* {
    background-color: darkcyan;
}
```

Afecta a todo el documento ```HTML``` de tal manera que el fondo de todo el documento seria de color ```darkcyan```.

* Selector de hijos:

```
h3>strong {
    color: blue;
}
```

Afecta a todos los elementos ```<strong>``` que son hijos de un ```<h3>```.

* Selector de descendientes:
```
div strong{
    color: blue;
}
```

Un ejemplo para ver las diferencias entre un selector de hijos y de descendientes:

![Diferencias entre selectores](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/img/selector.png)

En un selector de hijos como se ve en el de la imagen podemos ver que solo afecta a los ```<em>``` que estan dentro de un ```<div>``` mientras que un selector de descendientes afecta a los ```<em>``` que estan dentro de un ```<div>``` sin importar que dentro de este haya otra etiqueta como es en el ejemplo.


## Introducción a Diseño responsive


Hay ciertas condiciones que hay que saber como se usan:

```height: 100vh;``` Una imagen con una altura vertical del 100 es decir que ocupe toda la pantalla.

```background-image:``` Poner una imagen de fondo para que se pueda escribir encima de esta.

```background-size: cover;``` Pega la imagen a todo el contenedor.

```background-position: center;``` Poner la imagen centrada. 

```background-attachment: fixed;``` Poner la imagen fija de modo que cuando se suba para arriba la página haga como un efecto de que la imagen se queda debajo de la pagina.

```display: flex;``` Establece un contenedor flexible permitiendo así la creación de un diseño de caja flexible.

```align-items: center;```  Alinea los elemento verticalmente en el centro.

```justify-content: center;``` Alinea los elementos horizontalmente en el centro.

```float: left;``` Hace que los contenedores se vayan poniendo hacia la izquierda.

``` *{ box-sizing: border-box; } ``` Condición para que funcionen las anteriores como el ```display: flex;```.

Este código lo que establece es que cuando la pantalla tenga un ancho máximo de 700px hará que los elementos con la clase column3 seran del 100% mientras que los elementos con la clase column2 seran del 50% cuando el ancho del contenedor sea igual o menor a 700px.
```
 @media only screen and (max-witdh: 700px){
    .column3{
        width:100%;
    }
    .column2{
        width:50%;
    }
 }
 ```