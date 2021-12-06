| INDICE |  |
| ------------- | ------------- |
| :house:  [HOME](/README.md)     |  |
| 📕  [CSS](/documentation/css.md)  | :pencil: 📐 [Ejercicios](/tests/exercices.md) |
| 📕  [JS](/documentation/js.md)  | :books: [JS Libreria de Scripts](/scripts_library/scripts.md)  |

&nbsp; 
&nbsp; 
# 📕 HTML5

Es un lenguaje de marcado que nos permite crear la estructura de una página web.

Este contenido estático posteriormente podrá ser visualizado en nuestro navegador, que con las hojas de estilos CSS y la ayuda de los scripts JS (contenido dinámico, interpretado en el navegador también), nos ayudarán con el diseño gráfico, creación y presentación de nuestro documento. 
&nbsp; 

## Buenas prácticas a la hora de escribir HTML

### \<!DOCTYPE html>  (documento HTML)

Empezamos declarando con esta etiqueta el tipo de documento para que el navegador pueda interpretar y visualizar su contenido.

### \<HEAD>\</HEAD>
Este elemento delimita la cabecera del documento, y entre sus etiquetas nos podemos encontrar información como scripts, metadatos, estilos, la ubicación de documentos de estilos, título de la página, etc.

### \<BODY>\<\BODY>
La etiqueta body delimita el cuerpo de nuestro documento, albergando todo aquello que vayamos a visualizar en el navegador. Imágenes, textos, enlaces, video, etc…

Todas las etiquetas deben ser cerradas y siguiendo el mismo orden en que se abrieron, a excepción de algunas como:
```html
<area>
<base>
<br>
<col>
<embed>
<hr>
<img>
<input>
<keygen>
<link>
<menuitem>
<meta>
<param>
<source>
<track>
<wbr>
```

 + El contenido de una etiqueta debe de llevar siempre **una sangría de 2** espacios o una tabulación.
 
 + El **uso de minúsculas para etiquetas**, atributos y valores no afecta a nuestra página, pero mejora la visualización y comprensión del código.
 + Uso del atributo ALT en imágenes 2021-12-06 Todas las imágenes que incluyas en tu sitio web deben agregarse siempre este atributo, el cual proporciona, como lo indica su nombre, un texto alterno a la imagen.

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Como puedes observar después de cada etiqueta hacemos una sangría de dos espacios o tabulación (identación) -->
    <meta charset="utf-8">
    <title>Aquí colocamos el título de la página</title>
  </head>
  <body>
    <!-- Esto es un comentario no podrá verse en nuestra página. -->
    <img src="images/firefox-icon.png" alt="Mi imagen de prueba">
  </body>
</html>
 ```
[Guia completa](https://google.github.io/styleguide/htmlcssguide.html)

