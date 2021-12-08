
:house:  [HOME](/README.md)

📕  [HTML](/documentation/html5.md)   
📕  [CSS](/documentation/css.md)  
📕  [JS](/documentation/js.md)

:pencil: [Ejercicios](/tests/exercices.md) &nbsp; &nbsp;  
:books: [JS Scripts Library](/scripts_library/scripts.md)
&nbsp; 
&nbsp; 

# Buenas prácticas a la hora de escribir HTML

 + Todo el código debe de estar escrito en **lowercase**.
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
<area> <base>  <br>  <col>  <embed>  <hr>  <img>  <input>  <keygen>
<link>  <menuitem>  <meta>  <param>  <source>  <track>  <wbr>
```

 
 + El contenido de una etiqueta debe de llevar siempre **una sangría de 2** espacios o **una tabulación** a la etiqueta principal que la contiene.
 
 + El **uso de minúsculas para etiquetas, atributos y valores** aunque no afecta a nuestra página, pero mejora la visualización y comprensión del código.
 + Usando del atributo **alt** para las imágenes, proporcionamos el nombre o texto (siendo lo mas fiel posible a la imagen) y así saber que imagen es a la hora de leer nuestro código.

```html
<!DOCTYPE html>
<html>
  <!-- Esto es un comentario no podrá verse en nuestra página. -->
  <head>
    <!-- Como puedes observar después de cada etiqueta en la que estamos contenido, hacemos una sangría de dos espacios o tabulación (identación) -->
    <meta charset="utf-8">
    <title>Aquí colocamos el título de la página</title>
  </head>
  <body>    
    <img src="images/coche.png" alt="Porsche Rojo">
  </body>
</html>
 ```
 + Evita utilizar la etiqueta **\<div>** para todo, puedes y debes de utilizar otras:
 ```html
<header>  <nav>  <aside> <section>
<article>  <menu>  <footer>
 ```
 + En el HTML avanzado, los comentarios no deberían ser necesarios, ya que el marcado HTML se explica por sí mismo.

## Link: [Guia completa](https://google.github.io/styleguide/htmlcssguide.html)


