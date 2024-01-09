# Definición y funciones del backend

### Definición

El backend se refiere a cualquier parte de un sitio web o software que los usuarios no pueden visualizar, también es conocido cómo el nivel de acceso de datos de cualquier aplicación.
La mayoría de las páginas web actuales son dinámicas, lo que significa que contienen scripts que se ejecutan en el servidor web cada vez que se accede a una página.
Los procesos de backend incluyen:

- Procesar las peticiones de una página
- Ejecuta la estructura de una página (HTML)
- Accede a la información almacenada en la base de datos
- Guarda o actualiza registros en la base de datos
- Encripta información
- Maneja descarga de archivos

El desarrollo backend permite flexibilidad en cuanto al lenguaje en el que se desarrolla, ya que las operaciones que se realizan en este no dependen del navegador del usuario, el cuál opera independiente del servidor y solo esta interesado en recibir las peticiones correctamente.

los navegadores se comunican con servidores web, usando el protocolo HTTP (HyperText Transfer Protocol). el navegador envía este tipo de peticiones al servidor cuando se realiza una  determinada acción dentro de la página.

La petición incluye una URL identificando el recurso afectado, el método que define la acción requerida (consultar, eliminar, etc.), e incluye información adicional codificado en los parámetros de la URL.

Los servidores web esperan por los mensajes de peticiones de los clientes, los procesa cuando llega, y envía una respuesta con un mensaje de estado http indicando si se realizo la petición correctamente.

el cuerpo de una respuesta exitosa puede contener el recurso solicitado el cuál  puede ser visualizado a través del navegador web.

- Sitios Estáticos: 
Sitio web que retorna el mismo contenido codificado de manea inmutable por el servidor de acuerdo al recurso que se haya solicitado. Si se quiere acceder  a una página web, el navegador encía una petición http "GET" especificando la URL; de acuerdo al estado de la respuesta, el servidor devuelve el documento especificado. 

![[Pasted image 20240104171241.png]]
- Sitios dinámicos
Un sitio web dinámico envía el contenido de su respuesta de manera dinámica, solo cuando sea necesario. Las páginas HTML que despliegan estos sitios web son creados a través de la inserción de datos provenientes de una base de datos a un sitio especifico de la plantilla HTML; estas páginas se destacan por ser mas eficientes a la hora de almacenar grandes cantidades de datos.

un sitio dinámico puede devolver diferentes conjuntos de datos basado en la información suministrada en la página web o en los parámetros de la URL, y puede realizar otras operaciones cómo parte de la respuesta retornada.

las peticiones por recursos dinámicos son ejecutados en el lado servidor, lo que significa que el servidor interpreta la petición, consulta la información requerida en la base de datos, combina la información obtenida con las plantillas HTML y devuelve una respuesta con el contenido en la HTML generado.

###  Funcionalidades

- Almacenamiento eficiente y entrega de información
La programación del lado del servidor permite almacenar la información en base de datos y construir  y retornar HTML y otro tipo de archivos, así cómo datos tipo JSON que son renderizados por el lado cliente.
No solo se limita a eso sino que además retorna el resultado de herramientas de software, o datos provenientes de servicios de comunicación.

- Experiencia de usuario customizada
Los servidores pueden almacenar y usar información sobre los clientes para otorgar una experiencia de usuario confiable, así cómo respuestas y notificaciones customizadas.

- Acceso a recursos controlados
El servidor permite a las páginas restringir el acceso únicamente a usuarios autorizados y enviar la información que esta permitida únicamente al usuario.


- Información de estado/ sesión almacenada
El servidor permite a los desarrolladores hacer uso de las sesiones, mecanismos que permite al servidor almacenar información asociada con el usuario actual de un sitio y enviar diferentes respuestas  basadas en esa información.

- Análisis  de datos
El servidor puede recolectar grandes cantidades de información, y tambien puede refinar las respuestas que envía a través del análisis de la información que guarda.

![[Pasted image 20240104171932.png]]
### Características


### Referencias
- [Introduction to the server side - Learn web development | MDN (mozilla.org)](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Introduction)
- [Introduction to the Back End | The Odin Project](https://www.theodinproject.com/lessons/nodejs-introduction-to-the-back-end)
- [Backend Definition (techterms.com)](https://techterms.com/definition/backend)
- [Back-End Web Architecture | Codecademy](https://www.codecademy.com/article/back-end-architecture)

