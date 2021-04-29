# Bienvenido/a a mi Proyecto Final!

Hola! Soy **Miranda Portocarrero** y, a continuación, le ofrezco una breve descripción de cómo es que se organiza internamente mi código.

## Estructura HTML
El trabajo cuenta con **5 secciones y una subseccion**, las cuales siguen el siguiente orden: "index.html", "Gatos3.html", "especiales.hmtl", "nosotros.html", "formulario.html" (y una subseccion llamada "recibido.html"). 

## Estructura SCSS
Con respecto a la carpeta scss, esta posee **5 archivos** de los cuales 4 están importados hacia "estilos.scss". A partir de allí y, gracias al uso de node.js, dichos archivos scss se compilan con css en la carpeta css, en un archivo llamado estilos.css.

Se añaden **comentarios** al principio o al final de las hojas de estilo scss para dar a entender que las clases a continuación son **propias y exclusivas** de sus respectivos html. 

Se agregan **"&"** al comienzo de las clases en scss para que, al ser compiladas a css, no se repitan clases innecesarias.

## Organización Imágenes
La carpeta **"images"** agrupa a todas las imágenes utilizadas en este proyecto.

## Subida a Github
Por último, se incluye un archivo **".gitignore"** que permite que "node_modules" no sea subido al servicio de hosting, que en este caso es **Github**.