| INDICE |  |
| ------------- | ------------- |
| :house:  [HOME](/README.md)     |  |
| 📕  [CSS](/documentation/css.md)  | :pencil: 📐 [Ejercicios](/tests/exercices.md) |
| 📕  [JS](/documentation/js.md)  | :books: [JS Libreria de Scripts](/scripts_library/scripts.md)  |

&nbsp; 
&nbsp; 

# Buenas prácticas a la hora de escribir HTML

 + Todo el código debe de estar escrito en lowercase.
 ```html
<!-- Not recommended -->
<A HREF="/">Home</A>

<!-- Recommended -->
<img src="google.png" alt="Google">

/* Not recommended */
color: #E5E5E5;

/* Recommended */
color: #e5e5e5;
```

 + Todas las etiquetas deben ser cerradas y siguiendo el mismo orden en que se abrieron, a excepción de algunas como:
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
 + Usando del atributo ALT para imágenes, nos proporciona el nombre o texto lo mas fiel posible a la imagen.

```html
<!DOCTYPE html>
<html>
  <!-- Esto es un comentario no podrá verse en nuestra página. -->
  <head>
    <!-- Como puedes observar después de cada etiqueta hacemos una sangría de dos espacios o tabulación (identación) -->
    <meta charset="utf-8">
    <title>Aquí colocamos el título de la página</title>
  </head>
  <body>    
    <img src="images/coche.png" alt="Porche Rojo">
  </body>
</html>
 ```
 + Evita utilizar la etiqueta **\<div>** para todo, puedes y debes de utilizar otras:
 ```html
<header>
<nav>
<aside>
<section>
<article>
<menu>
<footer>
 ```
 + En el HTML avanzado, los comentarios no deberían ser necesarios, ya que el marcado HTML se explica por sí mismo.

## Link la [Guia completa](https://google.github.io/styleguide/htmlcssguide.html)


