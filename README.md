# ASIX1M4UF1A3_Apunts

## Introducción a Markdown

Para escribir un título se utiliza un corchete "#", cuantos mas corchetes se pongan más pequeño será el título con un máximo de hasta 6 corchetes. Ejemplos:

## Título grande con dos corchetes

### Título mediano con tres corchetes

#### Título mediano con cuatro corchetes

##### Título pequeño con cinco corchetes

###### Título más pequeño con seis corchetes

Para crear una lista ordenada es tan simple como poner el numero y un punto a continuacion:

1. Primera opción de menú
2. Segunda opción de menú
3. Segunda opción de menú

Para crear una lista desordenada, se pueden hacer de diferentes tipos mediante un asterisco, mediante un signo de resta y mediante un signo de suma:

* Primera lista desordenada con un asterisco

* Segunda lista desordenada con un asterisco

- Tercera lista desordenada con un signo de resta

- Cuarta lista desordenada con un signo de resta

+ Quinta lista desordenada con un signo de suma

+  Sexta lista desordenada con un signo de suma

Tambien se pueden crear submenus dentro de estas listas dandole al tab y poniendo un numero junto con un punto y un espacio a continuacion o en vez de un numero se puede añadir un asterisco:

* Primera lista desordenada con un asterisco
    1. Primer submenú con número y punto
    2. Segundo submenú con número y punto

* Segunda lista desordenada con un asterisco
    * Tercer submenú con asterisco 
    * Cuarto submenú con asterisco 

_Para escribir un texto en cursiva se puede hacer de dos maneras, mediante un asterisco al principio y el al final o con una barra baja al inicio y al final de la frase tal como se puede ver en la imagen:_
![Imagen de dos palabras en cursiva](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/Captura%20de%20pantalla%202023-10-16%20173048.png)

__Para escribir un texto en negrita se puede hacer de dos maneras también, mediante dos asteriscos tanto al principio como al final o con dos barras bajas tanto al principio como al final tal como se puede ver en la imagen:__
![Imagen de dos palabras en negrita](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/Captura%20de%20pantalla%202023-10-16%20173114.png)    

__*Para escribir un texto en cursiba y negrita habra que hacerlo tal como en la foto que hay a contiuación*__
![Imagen de un texto en negrita y en cursiva](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/Captura%20de%20pantalla%202023-10-16%20173135.png)

Para insertar una imagen hay que abrir corchetes para introducir muy brevemente lo que se ve en la imagen, justo depues de los corchetes se abren parentesis y dentro de estos se pone el link de la imagen que tiene que estar subida en nuestro repositorio de github, de tal manera que tendria que quedar tal como en la imagen de a continuación:

![Imagen de como insertar imagenes](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/Captura%20de%20pantalla%202023-10-16%20175347.png)

Para crear columans hay que hacer tal como en la imagen:

![Imagen de como crear columnas](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/Captura%20de%20pantalla%202023-10-16%20180155.png)

Para aliniar columnas se hace mediante los ":" de tal manera que si no pones anda se alinea solo a la izquierda pero si pones los ":" a los lados se alineará al dentro mientras que si los ponemos al final el texto se alineará a la derecha y para asignar una amplitus a cada columna será mediante giones medios, contra mas "-" mas amplia será y de lo contrario mas estrecha será.

![Imagen de como alinear textos](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/Captura%20de%20pantalla%202023-10-16%20180220.png)

Para poner contenido dentro de estas se habrá que hacer tal como se ve a continuación:

![Imagen de como rellenar columnas](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/Captura%20de%20pantalla%202023-10-16%20180256.png)

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

```
Para crear un cuerpo de texto para poder escribir
HTML:5
```
Quedaria tal que asi:
![Imagen](https://github.com/kilianruiz/ASIX1M4UF1_Apunts/blob/main/1.png)
```
Para escribir un párrafo:
<p>    texto visible    </p>

Para escribir unpárrafo con etiqueta:
<p class=”valor”>     texto visible       </p>

Para escribir un párrafo con contenido en negrita:
<p>  texto visible  <strong>  texto visible en negrita  <strong>  texto visible  </p>

```

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