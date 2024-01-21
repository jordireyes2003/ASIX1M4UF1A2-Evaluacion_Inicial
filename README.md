# ASIX1M4UF1A2-Evaluacion_Inicial

Repositorio para apuntes de clase.

## Primer capitulo: MARKDOWN

Este texto esta en *cursiva*.
Este texto esta en _cursiva_.
Este texto esta en **negrita**.
Este texto esta en __negrita__.

Este texto esta en **_negrita y cursiva_**.

1. Primera opcion de menú
2. Segunda opcion de menú
3. Tercera opcion de menú

* Primera opcion de lista desordenada
* Segunda opcion de lista desordenada
- Tercera opcion de lista desordenada
    1. Primer submenú
    2. Segundo submenú
- Cuarta opcion de lista desordenada
    3. Tercer submenú
    4. Cuarto submenú
+ Quinta opcion de lista desordenada
+ Sexta opcion de lista desordenada

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html>
```

[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

|Primera Col.|Segunda Col.|3 Col.|
|---------------|:------------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX|M4|

-[ ] Opcion A
-[X] Opcion B
-[ ] Opcion C

## Evaluación Inicial

1. ¿Qué es una página web?

Documento digital complejo, que puede integrar y/o contener texto, sonido, vídeo, programas, enlaces, imágenes, hipervínculos y otros elementos, adaptado para la World Wide Web, y que puede ser accedida y visualizada mediante un navegador web.

2. ¿Qué es un sitio web?

Un sitio web​, portal​ o cibersitio es una colección de páginas web relacionadas y comunes a un dominio de internet o subdominio en la World Wide Web dentro de Internet. 

3. ¿Qué es una aplicación web?

Herramienta que los usuarios pueden utilizar accediendo a un servidor web a través de internet o de una intranet mediante un navegador.  

4. ¿Qué es una herramienta ofimática?

Las herramientas ofimáticas son aquellos programas o aplicaciones que nos permiten manipular informáticamente la información con la que se trabaja de forma habitual en una oficina.

5. Herramientas de Google:

|Aplicaciones|Visto|
|-------------|:----------:|
|Google Docs|✔|
|Google Slides|✔|
|Google Sheets|✔|
|Google Calendar|🗓|
|Google Meet|💻|
|...|...|

6. ¿Qué es HTML?

El Lenguaje de Marcado de Hipertexto (HTML) es el código que se utiliza para estructurar y desplegar una página web y sus contenidos.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport"content="width=devic-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

```

7. ¿Qué es CSS?

CSS es uno de los lenguajes más importantes que se utilizan para ordenar las instrucciones referentes a la apariencia de un sitio y presentar los contenidos de una página de forma atractiva. 

8. Flujo de trabajo (navegador, petición, servidor y respuesta):

[Esto es una imagen del flujo de trabajo](https://github.com/jordireyes2003/ASIX1M4UF1A2-Evaluacion_Inicial/blob/main/Flujo%20de%20trabajo.jpg "Imagen esquema flujo de trabajo")

## HTML y CSS

< HTML > ... < /HTML > : Indica el comienzo y fin de un archivo HTML


< HEAD > ... < /HEAD > : Indica el comienzo y fin de un encabezado (aquí se coloca generalmente el título).


< TITLE > ... < /TITLE > : Indica el título.


< BODY > ... < /BODY > : Indica el comienzo y fin del cuerpo de la página.


< P > ... < /P > : Indica comienzo y fin de un párrafo.


< BR > : Permite saltarse una línea (se llama quiebre de línea).


< UL > ... < /UL > : Indica comienzo y fin de una lista no ordenada (puntos). Dentro de ellos, cada item empieza por < LI > y termina al terminar la línea.


< OL > ... < /OL > : Indica comienzo y fin de una lista ordenada (números). Dentro de ellos, cada item empieza por < LI > y termina al terminar la línea.


Ejemplo:

```
  < OL >
        < LI > Primer item
        < LI > Segundo item
        < UL > 
          < LI > Primer subitem
          < LI > Segundo subitem
        < /UL >
        < LI > Tercer item
      < /OL >
```

La etiqueta < a > en HTML se utiliza para crear hipervínculos, es decir, enlaces a otras páginas web o recursos en línea. Aquí tienes un ejemplo de cómo se usa la etiqueta < a >:

```
<a href="https://www.ejemplo.com">Texto del enlace</a>

```

La etiqueta < a > en HTML puede contener el atributo href, que se utiliza para especificar la dirección URL a la que se debe enlazar el contenido del enlace. El atributo href define la "referencia de hipertexto" (Hypertext Reference) y es esencial para crear enlaces web. Aquí tienes un ejemplo de cómo se utiliza el atributo href en la etiqueta < a >:


```
<a href="https://www.ejemplo.com">Texto del enlace</a>
```

La etiqueta < h1 > en HTML se utiliza para definir un encabezado de nivel 1 en una página web. Los encabezados se utilizan para estructurar el contenido de una página y proporcionar una jerarquía visual en el texto. El < h1 > es el encabezado principal y generalmente se coloca al comienzo de la página para indicar el título principal o el tema principal de la página. Aquí tienes un ejemplo de cómo se usa la etiqueta < h1 >:

```
<h1>Este es un título principal</h1>
```

El atributo id se utiliza para que puedas aplicar estilos CSS, manipular elementos con JavaScript y crear vínculos internos a elementos específicos en la misma página.

Aquí tienes un ejemplo de cómo se usa el atributo id en una etiqueta HTML:

```
<p id="mi-parrafo">Este es un párrafo con un ID.</p>
```

La etiqueta < img > en HTML se utiliza para incrustar imágenes en una página web. Aquí tienes un ejemplo de cómo se utiliza la etiqueta < img >:

```
<img src="imagen.jpg" alt="Texto alternativo">
```

src (source): Este atributo especifica la ubicación de la imagen que se mostrará en la página web. Puede ser una URL (dirección web) o una ruta relativa a la imagen en tu servidor. En el ejemplo, "imagen.jpg" es la fuente de la imagen.


alt (texto alternativo): Este atributo proporciona un texto descriptivo de la imagen, que se mostrará si la imagen no se puede cargar o si el usuario utiliza un lector de pantalla. Proporcionar un texto alternativo es importante para la accesibilidad web y para describir la imagen a los usuarios que no pueden verla. En el ejemplo, "Texto alternativo" es el texto alternativo.

La etiqueta < table > en HTML se utiliza para crear tablas en una página web. Las tablas son útiles para organizar datos en filas y columnas, y se componen de varias etiquetas secundarias para definir la estructura de la tabla. Aquí tienes un ejemplo básico de cómo se utiliza la etiqueta < table >:

```
<table>
  <tr>
    <th>Encabezado de la columna 1</th>
    <th>Encabezado de la columna 2</th>
  </tr>
  <tr>
    <td>Dato 1, Fila 1</td>
    <td>Dato 2, Fila 1</td>
  </tr>
  <tr>
    <td>Dato 1, Fila 2</td>
    <td>Dato 2, Fila 2</td>
  </tr>
</table>
```


La etiqueta < tr > en HTML se utiliza para definir una fila en una tabla HTML. Dentro de una tabla, las filas se utilizan para organizar y presentar datos en una estructura de filas y columnas. Cada fila contiene una o más celdas de datos (definidas con la etiqueta < td> ) y puede contener también celdas de encabezado (definidas con la etiqueta < th > en la primera fila de la tabla).

Aquí tienes un ejemplo de cómo se utiliza la etiqueta < tr > en una tabla HTML:

```
<table>
  <tr>
    <th>Encabezado de columna 1</th>
    <th>Encabezado de columna 2</th>
  </tr>
  <tr>
    <td>Dato 1, Fila 1</td>
    <td>Dato 2, Fila 1</td>
  </tr>
  <tr>
    <td>Dato 1, Fila 2</td>
    <td>Dato 2, Fila 2</td>
  </tr>
</table>
```

La etiqueta < td > en HTML se utiliza para definir las celdas de datos en una tabla HTML. Cada celda de datos contiene información que se organiza en filas y columnas en una tabla. Aquí tienes un ejemplo de cómo se utiliza la etiqueta < td > en una tabla HTML:

```
<table>
  <tr>
    <td>Dato 1, Fila 1</td>
    <td>Dato 2, Fila 1</td>
  </tr>
  <tr>
    <td>Dato 1, Fila 2</td>
    <td>Dato 2, Fila 2</td>
  </tr>
</table>
```

La etiqueta < thead > en HTML se utiliza para definir la sección de encabezado de una tabla HTML. El contenido dentro de esta sección se utiliza típicamente para enumerar o nombrar las columnas de la tabla. La etiqueta < thead > se coloca generalmente dentro de la etiqueta < table > y se utiliza junto con las etiquetas < th > para definir los encabezados de columna.

Aquí tienes un ejemplo de cómo se utiliza la etiqueta < thead > en una tabla HTML:

```
<table>
  <thead>
    <tr>
      <th>Encabezado de columna 1</th>
      <th>Encabezado de columna 2</th>
      <th>Encabezado de columna 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Dato 1, Fila 1</td>
      <td>Dato 2, Fila 1</td>
      <td>Dato 3, Fila 1</td>
    </tr>
    <!-- Más filas de datos -->
  </tbody>
</table>
```

La etiqueta < tbody > en HTML se utiliza para definir la sección del cuerpo de una tabla HTML. El contenido dentro de esta sección generalmente contiene las filas y celdas de datos que forman el contenido principal de la tabla. La etiqueta < tbody > se coloca dentro de la etiqueta < table > y se utiliza para separar la sección de datos del encabezado de la tabla.

Aquí tienes un ejemplo de cómo se utiliza la etiqueta < tbody > en una tabla HTML:

```
<table>
  <thead>
    <tr>
      <th>Encabezado de columna 1</th>
      <th>Encabezado de columna 2</th>
      <th>Encabezado de columna 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Dato 1, Fila 1</td>
      <td>Dato 2, Fila 1</td>
      <td>Dato 3, Fila 1</td>
    </tr>
    <tr>
      <td>Dato 1, Fila 2</td>
      <td>Dato 2, Fila 2</td>
      <td>Dato 3, Fila 2</td>
    </tr>
    <!-- Más filas de datos -->
  </tbody>
</table>
```

La etiqueta < tfoot > en HTML se utiliza para definir la sección de pie de una tabla HTML. La sección de pie de la tabla generalmente contiene resúmenes, totales u otra información que se aplica a todo el conjunto de datos en la tabla. La etiqueta < tfoot > se coloca dentro de la etiqueta < table >, después de las secciones de encabezado (< thead >) y cuerpo (< tbody >).

Aquí tienes un ejemplo de cómo se utiliza la etiqueta < tfoot > en una tabla HTML:

```
<table>
  <thead>
    <tr>
      <th>Encabezado de columna 1</th>
      <th>Encabezado de columna 2</th>
      <th>Encabezado de columna 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Dato 1, Fila 1</td>
      <td>Dato 2, Fila 1</td>
      <td>Dato 3, Fila 1</td>
    </tr>
    <tr>
      <td>Dato 1, Fila 2</td>
      <td>Dato 2, Fila 2</td>
      <td>Dato 3, Fila 2</td>
    </tr>
    <!-- Más filas de datos -->
  </tbody>
  <tfoot>
    <tr>
      <td colspan="3">Total: $1000</td>
    </tr>
  </tfoot>
</table>
```

El atributo border en HTML se solía utilizar para definir el ancho del borde alrededor de una tabla HTML y sus celdas. Sin embargo, este atributo se considera obsoleto en HTML5 y se recomienda encarecidamente usar estilos CSS en su lugar para controlar la apariencia de las tablas.

Ejemplo: 

```
<style>
  table {
    border-collapse: collapse; /* Combina los bordes de las celdas adyacentes */
    border: 2px solid #000; /* Ancho y color del borde de la tabla */
  }
  th, td {
    border: 1px solid #000; /* Ancho y color del borde de las celdas */
    padding: 10px; /* Añade espacio interno para el contenido */
  }
</style>
```