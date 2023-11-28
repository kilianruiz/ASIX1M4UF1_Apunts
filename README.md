# ASIX1M4UF1A3_Apunts

## Introducción a GITHUB

Para empezar, hay que crear un repositorio y para esto tendremos que ir a nuestro perfil (arriba a la derecha) hacer click ahi y entrar en ```Your repositories```, una vez dentro saldra una pestaña de color verde la cual pondra ```NEW```, una vez hecho nos llevará a esta pantalla:

![Imagen de github](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/github.png)

<hr>

En el cuadrado de ```Repository name``` pondremos el nombre que queremos que se llame nuestro repositorio y le daremos a que nuestro repositorio sea publico, ademas de darle click a que me añada un README file, una vez hecho todo esto le daremos al boton verde de abajo a la derecha que pone ```Create repository```.

Una vez creado nuestro repositorio tendremos que clonarlo y para esto dentro de nuestro repositorio nos saldrá una pestaña de color verde que pone ```CODE```, le daremos ahi y nos abrirá el despegable de a continuacion:

![Imagen desplegable](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/desplegable.png)

<hr>

Copiaremos el link que nos sale y abriremos el terminal en el cual introduciremos lo siguiente:

```
git clone (link del repositorio que hemos copiado anteriormente)
```

## Introducción a Markdown

Para escribir un título se utiliza un corchete "#", cuantos mas corchetes se pongan más pequeño será el título con un máximo de hasta 6 corchetes. Ejemplos:

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
![Imagen de como insertar imagenes](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/planeta.jpg)
```

![Imagen de como insertar imagenes](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/planeta.jpg)

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

Para escribir un párrafo:

```<p>```    texto visible    ```</p>```

Para escribir unpárrafo con etiqueta:

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

En cambio para hacer una lista desordenada se hace asi:
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

Para ir de un sitio a otro haciendo click en alguna frase:

```<a href="#Primer plato: Almejas a la marinera">Volver a arriba</a>```

En esta parte lo que hacemos es introducir un href="" dentro de la etiqueta ```<a>``` indicando a donde queremos ir, en este caso a "#Primer plato: Almejas a la marinera" haciendo click en el texto de "Volver arriba" y le ponemos el "#" a Primer plato para indicar que a donde queremos que nos lleve esta en esa pagina y no de otra.

Si queremos ir de una pagina a otra haciendo click en una palabra se hace tal que asi:

```<a href="./primer_plato/index2.html">Primer plato: Almejas a la marinera</a>```

Ponemos un href="" dentro de la etiqueta ```<a>``` indicando a donde quiero ir con un ./ y la direccion del html al que quiero ir y justo despues la palabra a la cual haremos click para que nos lleve hasta allí

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

Esto es un título llamado Ingredientes el cual es a donde nos llevará porque con el href="" lo que indicamos es de donde sale mientras que con el id="" indicamos a donde va a parar.
Otro dato importante es que al hacer click nos lleva a un apartado que hemos elegido pero dentro de esa misma página ya que le hemos puesto un # para que sepa que no es ningún link ni un apartado de otra página.



## Introducción a CSS
