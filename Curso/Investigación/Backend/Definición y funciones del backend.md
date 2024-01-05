### Definición

El backend se refiere a cualquier parte de un sitio web o software que los usuarios no pueden visualizar, tambien es conocido cómo el nivel de acceso de datos de cualquier aplicación.
La mayoría de las páginas web actuales son dinamicas, lo que significa que contienen scripts que se ejecutan en el servidor web cada vez que se accede a una página.
os procesos de bakend incluyen:
- Procesar las peticiones de una página
- Ejecuta la estructura de una página (HTML)
- Accede a la información almacenada en la base de datos
- Guarda  o actualiza registros en la base de datos
- Encripta información
- Maneja descarga de archivos

El desarrollo backend permite flexibilidad en cuanto al lenguaje en el que se desarrolla, ya que las opperaciones que se realizan en este no dependen del navegador del usuario,. el cuál opera independiente del servidor y solo esta interesado en recibir las peticiones correctamente

los navegadores se comunican con servidores web, usando el protocolo http (HyperText Transfer Protocol). el navegador envía este tipo de peticiones al servidor cuando se realiza una  determinada acción dentro de la página.

La petición incluye una URL identificando el recurso afectado, el método que define la acción requerida (consultar, eliminar, etc), e incluye información adicional codificado en los parametros de la url

Los servidores web esperan por los mensajes de peticiones de los clioentes, los procesa cuando llega, y envía una respuesta con un mensaje de estado http indicando si se realizo la petición correctamente.

el cuerpo de una respuesta exitosa puede contener el recurso solicitado el cuál  puede ser visualizado a través del navegador web.

- Sitios Estáticos: 
Sitio web que retorna el mismo contenido codificado de manea inmutable por el servidor de acuerdo al recurso que se haya solicitado. Si se quiere acceder  a una página web, el navegador encía una petición http "GET" especificando la url; de acuerdo al estado de la respuesta, el servidor devuelve el documento especificado. 

![[Pasted image 20240104171241.png]]
- Sitios dinámicos
Un sitio web dinámico envía el contenido de su respuesta de manera dinámica, solo cuando sea necesario. Las páginas html que despliegan estos sitios web son creados a través de la inserción de datos provenientes de una base de datos a un sitio especifico de la plantilla html; estas páginas se destacan por ser mas efecientes a la hora de almacenar grandes cantidades de datos.

un sitio dinámico peude devolver diferentes conjuntos de datos basado en la informnación suministrada en la página web o en los partametros de la url, y puede realizar otras operaciones cómo parte de la respuesta retornada.

laspeticiones por recursos dinámicos son ejecutados en el lado servidor, lo que significa que el servidor interpreta la petición, consulta la información requerida en la base de datos, combina la información obtenida con las plantillas tml y devuelve una respuesta con el contenido en la html generado.

###  Funcionalidades

- Almacenamiento eficiente y entrega de información
- Experiencia de usuario customizada
- Acceso a recursos controlados
- Información de estado/ sesión almacenada
- Análisis  de datos


![[Pasted image 20240104171932.png]]
### Características


### Referencias
- [Introduction to the server side - Learn web development | MDN (mozilla.org)](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Introduction)
- [Introduction to the Back End | The Odin Project](https://www.theodinproject.com/lessons/nodejs-introduction-to-the-back-end)
- [Backend Definition (techterms.com)](https://techterms.com/definition/backend)
- [Back-End Web Architecture | Codecademy](https://www.codecademy.com/article/back-end-architecture)

