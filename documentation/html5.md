:house:  [HOME](/README.md)         📕  [HTML](/documentation/html5.md)         📕  [CSS](/documentation/css.md)         📕  [JS](/documentation/js.md)         :pencil: [Ejercicios](/tests/exercices.md)         :books: [JS Scripts Library](/scripts_library/scripts.md)
 
  


&nbsp; 
&nbsp; 
# 📕 HTML5

+ Es un lenguaje de marcado que nos permite crear la estructura de una página web.

+ A este contenido estático que visualizaremos en nuestro navegador, le añadiremos hojas de estilos CSS y contenidos dinámicos (JavaScript) para ayudar en la tarea del diseño gráfico, creación y presentación de nuestro documento. 
&nbsp; 

### Antes de continuar os dejo el link de [<Buenas prácticas para escribir HTML>](rules.md)
&nbsp; &nbsp; 
### \<!DOCTYPE html>  (documento HTML)

Empezamos declarando con esta etiqueta el tipo de documento para que el navegador pueda interpretar y visualizar su contenido.

### \<head>\</head>
+ Este elemento delimita la cabecera del documento, y entre sus etiquetas nos podemos encontrar información como scripts, metadatos, estilos, la ubicación de documentos de estilos, título de la página, etc.
```html
<head>
  <meta charset="utf-8"> <!-- Es un tipo de codificación (idioma, caracteres...) -->
  <meta name="title" content="Título de la WEB"> <!-- Título de la página -->
  <meta name="description" content="Descripción de la WEB">   <!-- Descripción de la página --> 
  <link href="http://dominio.com/hoja-de-estilos.css" rel="stylesheet" type="text/css"/> <!-- Ubicación de hoja de la estilos CSS -->
</head>
```



### \<body>\<\body>
+ La etiqueta body delimita el cuerpo de nuestro documento, albergando todo aquello que vayamos a visualizar en el navegador. Imágenes, textos, enlaces, video, etc…
Pero todo ello correctamente estructurado y etiquetado:
```html

<body>
  
  <nav>            <!-- Estructura principal de navegación entre nuestras páginas -->
  </nav>
    
  <section>        <!-- Sección dentro de la página -->
    
    <article>      <!-- Un artículo de nuestra página -->
    </article>
    
  </section>
    
  <aside>          <!-- Contenido indirectamente relacionado con el artículo de nuestra página -->
  </aside>
    
  <footer>         <!-- Nuestro pie o fin de página -->
  </footer>
    
<body>
  
```
#### Ejemplo de estructura dentro de "body"
```html

   <body>
    <header>
      <h1>Enunciado/Título de la WEB</h1>      
    </header>    
    <nav> 
      <a href="http://dominio.com/seccion2.html">IR SECCIÓN 2</a>
      <a href="http://dominio.com/seccion2.html">IR SECCIÓN 3</a>
    </nav>      
      <article> 
        <h2>CONTENIDO PRINCIPAL</h2>
        <p>Este es el contenido principal de mi web</p>
        <div>
          <p>Aquí tenéis una imagen.</p>
          <img src="http://dominio.com/imagen.jpg" alt="paisaje">          
        </div>
      </article>      
    </section>
    <aside>  
      <h3>Banner de publicidad</h3>
      <a href="http://dominio-externo.com">
        <img src="http://dominio.com/banner-publicidad.png" alt="banner de publicidad">
      </a>
      <h3>Testimonios</h3>
      <p>Me gusta mucho esta página.</p>
    </aside>
    <footer>
      <h4>Avisos legales</h4>
      <a href="http://dominio.com/aviso-legal">Política de cookies</a>
      <h4>Redes sociales</h4>
      <a href="http://facebook.com/mi-pagina-de-facebook">Mi Facebook</a>
    </footer>
  </body>  

```

### \<h1>, \<h2>, \<h3>, \<h4>, \<h5>, \<h6>
+ Etiquetas para establecer los encabezados. El nivel **h1** es el más importante y **h6** el menos importante.
```html
<h1>Lema o título de nuestra WEB</h1>
<h2>EL CONTENIDO PRINCIPAL</h2>
<h3>Textos</h3>
<h4>Avisos legales</h4>
```

### \<div>\</div>
+ Esta etiqueta la usamos para dividir contenido en secciones/subsecciones...etc. y poder aplicarle clases y modificar sus estilos, que podremos ver mas cuando veamos las hojas de estilos CSS.
```html
<div id="azul" style="background-color: blue;">  <!-- Modificando el estilo con el correspondiente CSS -->
</div>
```
### \<p>\</p>
+ Otra sub división utilizada como párrafo que podría ir perfectamente dentro del contenedor \<div> anterior.

### \<spam>\</spam>
+ Otra etiqueta que tiene función de contenedor, un contenedor en línea. Para destacar por ejemplo una expresión o una palabra dentro de un párrafo al igual que al resto se le puede poner un estilo mediante un atributo. 

### \<br>
+ Un simple salto de línea.

### \<ol>  \<li>\</li> \<ol> | \<ul> \<li>\</li> \<ul>
+ Etiqueta **\<ol>** nos sirve para crear listas ordenadas y **\<ul>** para listas desordenadas. Dentro de cada las lista, los elementos se identifican con la etiqueta **\<li>**.
```html
<ol>
  <li>Primer elemento ordenado</li>
  <li>Segundo elemento ordenado</li>
<ol>
  
<ul>
  <li>Primer elemento "desordenado"</li>
  <li>Segundo elemento "desordenado"</li>
<ul>
```

### \<a>\</a>
+ Etiqueta para crear un enlace a una página web. Atributo principal **href**, contendrá el enlace al que queremos conectar. Otro atributo es **target**, indicará si el enlace se abrirá en la misma ventana o en una nueva.
```html
 <a href="http://dominio.com/aviso-legal" target=”_blank”>Política de cookies</a>
```

### \<img>\</img>
+ Etiqueta para mostrar imágenes dentro de un contenido. Lleva consigo el atributo **src** para poder ser utilizada, que será la ubicación donde se encuentra nuestra imagen. Es importante colocar siempre el atributo **title** para saber la descripción de esa imagen a la hora de leer nuestro código.

 ```html
<img src="img/tricks-img/exposure-triangle.png" alt=”Triángulo de exposición">
```
