# Unidad-2
<!DOCTYPE html> <!-- Especifica el tipo de documento -->
<html lang="es"> <!-- Especifica el idioma del documento -->
<!-- Head es el encabezado de la página --> 

    <!-- Taller Unidad 2 -->
    <!-- 1. Ingresar el favicon, en la sección correspondiente -->
    
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootcamp Desarrollo Web Full Stack</title>
</head>
<!-- Fin head -->

<!-- Body es el cuerpo de la página -->
<style>
  body{background-color: antiquewhite; padding: 50px; front-family: Arial;}
 
  #nav ul{
    list-style: none;
    padding: 0px;
    margin: 0px;
  }
  #nav ul li{
    display: inline-block;
   } 
   #nav ul li{background-color: blueviolet;}
   #nav ul li a{ 
    color:aliceblue;
    display:block;
    padding: 10px;
    text-decoration: none;
   }
   #nav ul li a:hover{
    background-color: rgb(245, 197, 223);
   }
   h1, h2, h3, h4, h5, h6{
    text-align: center; 
    color: rgb(58, 12, 100);
   }
</style>
<body>
    <!-- 2. Estilizar la barra de navegación utiilizando CSS -->
    <!-- 3. Crear en el menú un vínculo al formulario de contacto -->
    <div id="nav"> 
    <nav>
        <ul>
            <li><a href="#intro">Introducción Desarrollo web</a></li>
            <li><a href="#carga-archivos">Incorporación imag, videos y embebidos</a></li>
            <li><a href="#recursos-apoyo">Recursos de apoyo</a></li>
            <li><a href="#contacto">contacto</a></li> 
        </ul>
    </div>
    </nav>

    <!-- 4. Estilizar h1-h6 de la página -->
    <!-- 5. Estilizar las diferentes secciones de la página, modificando tipografía, colores de la letra y fondos -->
    <!-- 6. Cargar un fondo en alguna de las secciones de la página, ajustar la dimensión de la página -->
    <main>
        <h1>DWFSV1-158 Unidad 1 </h1> <!-- Título de la página -->
        <h2> Contenidos del módulo </h2> <!-- Subtítulo de la página -->
    <style>
       h2{
        color: rgb(58, 12, 100);
      }
    </style>
        <!-- Lista no ordenada -->
        #contmodulo{
            color:
            text-ai
        }
        <section id="contmodulo"></section>
         <ul> 
            <li>Introducción al Desarrollo Web. </li>
            <li> Conceptos de HTML5. </li>
            <li> Estructura de una página HTML5</li>
            <li> Etiquetas comunes (Títulos, párrafos, listas y enlaces)</li>
            <li>Incorporación de Imágenes, videos y embebidos (iframes, embed, video, img, figure)</li>
            <li>Formulario en HTML y sus elementos.</li>
            <li>Semántica HTML5.</li>
         </ul>
       </section>
   
        <section id="intro">
            <h3>Introducción al Desarrollo web</h3> <!-- Subtítulo de la página -->
            <!-- Lista ordenada -->
            <ol> 
                <li>El desarrollo web es un campo en constante evolución que abarca la creación y mantenimiento de sitios web y aplicaciones web. Es un proceso complejo que involucra una variedad de tecnologías, lenguajes de programación y herramientas.</li>
                <li>Los desarrolladores web trabajan en colaboración para diseñar, construir y desplegar sitios web y aplicaciones que sean funcionales, atractivas y accesibles para los usuarios.</li>
                <li>El desarrollo web se ha convertido en una industria esencial en el mundo moderno, ya que las empresas y organizaciones dependen cada vez más de la presencia en línea para conectar con sus clientes, socios y empleados. </li>
            </ol>
            <h3>Introducción al Desarrollo web</h3>
            <ul>
                <li> Gráficos y animaciones. </li>
                <li> Formularios mejorados. </li>
                <li> Accesibilidad mejorada. </li>
                <li> Soporte mejorado para aplicaciones web. </li>
                <li> Computabilidad con móviles. </li>
                <li> Integración con CSS3 y JavaScript.</li>             
            </ul>
        </section>

        <section id="carga-archivos">
            <h3> Incorporación de imagenes, videos y embebidos (iframes, embed, video, img, figure) </h3>
            <h4> Incorporación de imágenes </h4>
            <h5> Imagen con img src, solamente carga </h5>
            <img src="https://th.bing.com/th/id/R.a064f15cee316faefa0414d940d69dc4?rik=n5A3XqPEUPar9Q&pid=ImgRaw&r=0" alt="Brais Moure">
            <h5> Imagen con figure</h5>
            <figure>
                <img src="https://th.bing.com/th/id/R.a064f15cee316faefa0414d940d69dc4?rik=n5A3XqPEUPar9Q&pid=ImgRaw&r=0" alt="Brais Moure">
                <figcaption> Brais Moure - Desarrollador Español </figcaption>
            </figure>
    <!-- 7. Cargar dos desarrolladores full stack adicionales, al hacer clic en su foto redireccionar a su canal de YouTube -->

            <!-- 8. Cargar un video de YouTube en la página, revisar "controls" para agregar controles a la reproducción -->
            <h4> Incorporación de videos </h4>
            <h4> Incorporación de embebidos </h4>
        </section>
    
        
        <section id="recursos-apoyo">

            <h2>Recursos de apoyo </h2>
            <ul>
                <li>
                    <a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started"> Getting started with HTML </a>
                </li>
                <li>
                    <a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started"> HTML text fundamentals </a>
                </li>
                <li>
                    <a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started"> HTML5 Cheat Sheets, Tutorials and Resources </a>
                </li>
                    <!-- 9. Cargar un archivo PDF -->
            </ul>
        </section>
                    <!-- 10. Crear una sección de contacto con un formulario, en esta el usuario estará obligado a ingresar todos los datos,
                             deberá contar con una lista de opciones de única selección y otra lista con la posibilidad de escoger múltiples
                             opciones, finalmente, un botón para enviar el mensaje y otro para borrar el contenido.
                    -->
    </main>
</body>
<footer> Talento Tech - 2024 - Todos los derechos reservados </footer>
</html>
