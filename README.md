# linkBlackground
Es un plugin para jQuery.

Es un plugin para uso libre.

Para empezar a usarlo primero se necesita descargar la librería de jQuery.

Después descargar el script y colocarlo dentro del sitio.

Para activar el plugin, se tiene que hacer la siguiente declaración en el script principal del sitio:
  
  $(".linkBackground a").linkBackground(); 

También hay un archivo con un ejemplo de cómo se tiene que activar.


Es importante que se mantenga la siguiente estructura para una etiqueta de link <a/>:

  <div class="linkBackground" color="red">
    <div class="linkBackground-back"></div>
    <a href="jquery.com">Mi plugin link</a>
  </div>
  
  La clase a usar es 'linkBackground' para el div contenedor del link
  Después se usará la clase 'linkBackground-back' para el div con el background
  
  El link puede llevar una clase si se necesita agregar algún estilo a este.
  
  Para modificar el color del background se tiene que hacer directamente en el html:
    <div class="linkBackground" color="red">
    
  Se hace con el atributo de'color' y se tiene que declararlo en este div contenedor.
  
El plugin no tiene opciones para modificar en el script. 



