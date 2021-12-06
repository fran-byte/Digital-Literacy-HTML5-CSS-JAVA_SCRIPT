| INDICE |  |
| ------------- | ------------- |
| :house:  [HOME](/README.md)     |  |
| 📕  [CSS](/documentation/css.md)  | :pencil: 📐 [Ejercicios](/tests/exercices.md) |
| 📕  [JS](/documentation/js.md)  | :books: [JS Libreria de Scripts](/scripts_library/scripts.md)  |

&nbsp; 
&nbsp; 
# 📕 HTML5

Es un lenguaje de marcado que nos permite crear la estructura de una página web.

Este contenido estático que posteriormente podrá ser visualizado en nuestro navegador, con ayuda de las hojas de estilos CSS y también con nuestros bloques de JavaScript (contenidos dinámicos), nos ayudarán en la tarea del diseño gráfico, creación y presentación de nuestro documento. 
&nbsp; 

# Antes de continuar LEER: [<Buenas prácticas para escribir HTML>](rules.md)

### \<!DOCTYPE html>  (documento HTML)

Empezamos declarando con esta etiqueta el tipo de documento para que el navegador pueda interpretar y visualizar su contenido.

### \<head>\</head>
```html
<head>
  <meta charset="utf-8"> <!-- Es un tipo de codificación (idioma, caracteres -->
  <meta name="title" content="Título de la WEB"> <!-- Título de la página -->
  <meta name="description" content="Descripción de la WEB">   <!-- Descripción de la página --> 
  <link href="http://dominio.com/hoja-de-estilos.css" rel="stylesheet" type="text/css"/> <!-- Ubicación de hoja de la estilos CSS -->
</head>
```

Este elemento delimita la cabecera del documento, y entre sus etiquetas nos podemos encontrar información como scripts, metadatos, estilos, la ubicación de documentos de estilos, título de la página, etc.

### \<body>\<\body>
+ La etiqueta body delimita el cuerpo de nuestro documento, albergando todo aquello que vayamos a visualizar en el navegador. Imágenes, textos, enlaces, video, etc…
Pero todo ello correctamente estructurado y etiquetado:
```html

<body>
  
  <nav>
  </nav>
    
  <section>
    
    <article>
    </article>
    
  </section>
    
  <aside>
  </aside>
    
  <footer>
  </footer>
    
<body>
  
```
```html
  <body>
    <header>
      <h1>Enunciado/Título de la WEB</h1>      
    </header>    
    <nav> 
      <!-- Estructura principal de navegación entre nuestras páginas -->
      <a href="http://dominio.com/seccion2.html">IR SECCIÓN 2</a>
      <a href="http://dominio.com/seccion2.html">IR SECCIÓN 3</a>
    </nav>
    <section> <!-- Sección dentro de la página -->      
      <article> <!-- Un artículo de nuestra página -->
        <h2>CONTENIDO PRINCIPAL</h2>
        <p>Este es el contenido principal de mi web</p>
        <div>
          <p>Aquí tenéis una imagen.</p>
          <img src="http://dominio.com/imagen.jpg" alt="paisaje">          
        </div>
      </article>      
    </section>
    <aside>  <!-- Contenido indirectamente relacionado con el artículo de nuestra página -->
      <h3>Banner de publicidad</h3>
      <a href="http://dominio-externo.com">
        <img src="http://dominio.com/banner-publicidad.png" alt="banner de publicidad">
      </a>
      <h3>Testimonios</h3>
      <p>Me gusta mucho esta página.</p>
    </aside>
    <footer>
       <!-- Nuestro pie o fin de página -->
      <h4>Avisos legales</h4>
      <a href="http://dominio.com/aviso-legal">Política de cookies</a>
      <h4>Redes sociales</h4>
      <a href="http://facebook.com/mi-pagina-de-facebook">Mi Facebook</a>
    </footer>
  </body>  

```


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
