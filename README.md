# Bienvenido/a a mi Proyecto Final!

Hola! Soy **Miranda Portocarrero** de la camada 14265 de Desarrollo Web y, a continuación, le ofrezco una breve descripción de cómo es que se organiza mi código tanto dentro como fuera.

## Temática
La temática de mi proyecto es la adopción de gatos. Más específicamente, me encargo de la organización de información, en este caso de gatos en adopción, para intentar conseguirles un hogar. Me ocupo de ordenar los datos que tengo a mi disposición para facilitarles el acceso a los usuarios que estén interesados en adoptar una mascota.

## Estructura HTML
El trabajo cuenta con **6 secciones y una subseccion**, las cuales siguen el siguiente orden: "index.html", "Gatos3.html", "especiales.hmtl", "nosotros.html", "formulario.html" (y una subseccion llamada "recibido.html"); y, por último, "404.html". 

## Estructura SASS
Con respecto a la carpeta scss, esta posee **5 archivos** de los cuales 4 están importados hacia "estilos.scss". A partir de allí y, gracias al uso de node.js, dichos archivos sass se compilan en la carpeta css, en un archivo llamado **"estilos.css"**.

Se añaden **comentarios** al principio de las hojas de estilo scss para dar a entender que las clases a continuación son **propias y exclusivas** de sus respectivos html a los cuales hacen referencian. 

Se agregan **"&"** al comienzo de las clases correspondientes a los botones para que, al ser compiladas a css, no se repitan clases innecesarias.

## Organización Imágenes
La carpeta **"images"** agrupa a todas las imágenes utilizadas en este proyecto.

## Page 404
Se incluye una página 404 para avisar al usuario que no se encontró la página que busca.

## Subida a Github
Por último, se incluye un archivo **".gitignore"** que permite que "node_modules" no sea subido al servicio de hosting, que, en este caso, es **Github**.