<!DOCTYPE html>

<html lang="es">

<head>
Titulo de la pagina web
Set de caracteres corrspondientes.
Información acerca del documento.
Archivos externos con estilos.
Codigos Javasript
Imagenes necesarias para generar la página.
 
Excepto título e iconos, el resto es invisible para el usuario.

<meta charset="iso-8859-1" />
<meta name="descrption" content="Ejemplo de HTML%" />
<meta name="keyword" content="HTML, CSS·, JavaScript" />

La segunda y la tercera son muy utilies para que los buscadores identifiquen tu pagina web.

<title> Título del documento </title> Este es el título de la URL en el navegador.

<link rel="stylesheet" href="misestilos.css"/>

La etiqueta link se usa para incorporar los estilos.
	Atributo rel: le dice al navegador que el archivo misestilos es un archivo CSS con estilos requeridos.
	Atributo href: lo usamos para incorporar el archivo CSS and nuestor html

Códigos de javascrip
Imágenes o iconos desde archivos externos.

**Se recomienda siempre crear la hoja de estilos a parte e insertarla mediante esta etiqueta.
Aumenta la velocidad de carga.

</head>

<body>

Parte visible del documento.

<div> Con esta etiqueta creo una división dentro del cuerpo de la página.
Puede ser un menú, texto, enlace, código, formulario...

<header> 
 <h1>Este es el título visible del sitio web</h1> Los títulos van de una jerarquía del 1 al 6, que definen 6 niveles de títulos donde el h1 es el más importante.
</header>

<nav>
 <ul> define la lista
  <li>principal</li> incorpora el elemento
  <li>fotos</li>
  <li>videos</li>
  <li>contacto</li>
 </ul>
</nav>

<section>

Pues aquí van las diferentes secciones con información de la página.
 <article> Este es mi primer mensaje o articulo.

  <header>
   <hgroup>    
    <h1><span>Título del <mark>mensaje</mark> uno</span></h1>
    <h2>Subtítulo del mensaje 1</h2>
   </hgroup>
   <p> Este mensaje fue escrito el 27 de marzo de 2017</p>
   <time datetime="2017-03-27" pubdate>publicado 27-03-2017</time>

  </header>

    Este es el texto de mi primer mensaje

   <figure>
     <img src=”https://s-media-cache-ak0.pinimg.com/736x/fe/8a/b5/fe8ab5cbf2d6d0968a144328cd0d9867.jpg”>
     <figcaption>
      Esta es la imagen del primer mensaje
     </figcaption>
   </figure>

   <span>Amo la película <cite>Tentaciones</cite></span>



  <footer>
    <p><small>comentarios (0)</small></p>
    <address>
      <a href=”http://www.jdgauchat.com”>JD Gauchat</a>
    </address>

  </footer>


 </article>

 <article> este es mi segundo mensaje o articulo
  <header>
    <h1>Título del mensaje uno</h1>
  </header>
    Este es el texto de mi primer mensaje
  <footer>
    <p>comentarios (0)</p>
  </footer>

 </article>

</section>

<aside>

Aquí van apartados de fácil acceso para más infomración.
Columna lateral.podemos usar <aside> dentro del elemento
<section> o incluso insertado entre la información relevante, como en el caso de una cita

 <blockquote> Mensaje número 1 </blockquote>
 <blockquote> Mensaje número 2 </blockquote>

</aside>

<footer>
 <small>Derechos reservados &copy; 2010-2011</small>
</footer>

</body>
</html>
