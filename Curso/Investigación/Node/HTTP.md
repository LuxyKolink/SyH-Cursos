![[Pasted image 20240208094928.png]]

- Hypertext Transfer Protocol / Protocolo de transferencia de hipertexto: Protocolo usado para visualizar páginas web de internet

![[Pasted image 20240208105619.png]]

![[Pasted image 20240208104447.png]]
- Http es añadido al inicio de la dirección de la página web
- El protocolo estándar de HTTP envía la información en texto plano
- Toda la información que es intercambiada entre el servidor y el cliente es transferida a la internet pública, por lo tanto es vulnerable frente a amenazas de robo de información
- Información sensible puede ser vulnerada

![[Pasted image 20240208104538.png]]
## HTTPS
- Secure Hypertext Transfer Protocol: Protocolo que añade seguridad en el proceso de transferencia de datos, al permitir encriptar los mensajes transferidos entre cliente y servidor.
- Los mensajes son imposibles de leer gracias a los algoritmos de encriptación
- Se previenen los ataques por Hackers
#### Encriptación
- Ciencia de crear secretos
- Manipula cierta cantidad de bytes correspondientes a datos importantes, desordena y revuelve los datos a través de un algoritmo secreto, haciendo imposible la lectura de los datos sin las credenciales correctas
- Siempre está evolucionando
![[Pasted image 20240209105831.png]]



![[Pasted image 20240208112318.png]]
![[Pasted image 20240208112738.png]]

- Protege la información a través de los siguientes protocolos:

#### SSL
- Hola

#### TLS


# Por qué HTTP?

- Persona esta asociada a una cooperativa.
- Quiero hacer pago a una cuenta de ahorros.
- Los directivos de la entidad financiera se encargan de registrar el pago.
- Este es el proceso que hace que el sistema y la entidad financiera funcione (A través de internet).

- ### HTTP es el protocolo que se encarga de registrar estos movimientos.

- Es el protocolo de comunicación mas usado

Por qué cuando visitamos una página web siempre nos genera la siguiente estructura?
**http://nombredemipagina.com**
- Siempre que se visita una página web, estamos usando el protocolo para realizar esta acción
- Qué es un protocolo?
	- Imagina que recibes una carta que diga "Alcen la mano"
	- Se lee la carta y se realiza la acción
- Es porque hay un protocolo de comunicación a través del texto, nosotros los humanos somos capaces de entenderlo; una serie de reglas que establecen los dos actores de la comunicación
- Los protocolos de internet funciona de la misma manera, los computadores se comunican a través de 0 y 1
- Se establece una comunicación en ese lenguaje, un equipo transmite información y el otro equipo entiende la información y la computa en datos, imágenes, etc;

### Peticiones y respuestas
- Sistema que permite l comunicación entre dos dispositivos cliente-servidor.
- Cuando hacemos una petición la página de Cooprodecol:
	1. Nosotros cómo cliente, le mandamos una petición al servidor
	2. Servidor procesa la petición
	3. Envía información a nosotros cómo respuesta.
- De naturaleza síncrona; sistema de preguntas y respuestas.

![[Pasted image 20240211145148.png]]

### Clientes y Servidores

- Cliente: Usuario que ingresa a la página de Cooprodecol; Cualquier tipo de dispositivo que envía peticiones al servidor
- Servidor: Un computador que recibe peticiones / puede haber otro servidor que envía y recibe peticiones de otro servidor
- Un servidor también puede ser cliente entre la comunicación con otro servidor



# Http a profundidad

- Que tipos de datos quieren visualizar / piden a través de un enlace a una página web?
- Cliente y servidor envían mensajes individuales mutuamente; los mensajes que envía el cliente son peticiones y los mensajes que envía el servidor son respuestas.
![[Pasted image 20240211201812.png]]

- Capa 8 de aplicación (TCP/IP)
	- Basado en el modelo OSI, TCP/IP (Protocolo de control de transmisión/ Protocolo de internet) representa una versión concisa del modelo OSI
	- El objetivo principal de TCP/IP es transferir datos de un computador desde un dispositivo a otro; los datos deben ser legibles y precisos para que el dispositivo que comunica cómo el que recibe, transmitan e identifiquen la misma información.
	- El modelo TCP/IP divide datos entre paquetes y los combina al otro extremo de la comunicación, permitiendo así la transmisión de datos precisos.
- Cuál es la diferencia entre TCP/IP?
	- Se diferencian en la transmisión de datos
	- IP encuentra el destino del mensaje
	- TCP envía y recibe el correo
- Cómo funciona el modelo TCP/IP?
	- El modelo divide los datos en paquetes al extremo del remitente
	- Esos paquetes deben ser recombinados en el extremo del receptor para formar la misma información que se envió al principio.
	- Los datos viajan y se dividen a través del procedimiento de 4 niveles:

Niveles del modelo TCP/IP
![[Pasted image 20240213115524.png]]


-  TCP: 
	- Modelo OSI: Describe las funciones del sistema de comunicación dividiendo el procedimiento de comunicación en componentes simples.
- TLS: 

### Arquitectura
- Peticiones son enviadas por el cliente (o proxy).
![[Pasted image 20240211203806.png]]

### Proxy
- Entre el cliente y el servidor, además existen distintos dispositivos que gestionan los mensajes HTTP. Dada la arquitectura en capas de la Web, la mayoria de estos dispositivos solamente gestionan estos mensajes en los niveles de protocolo inferiores: capa de transporte, capa de red o capa física, siendo así transparentes para la capa de comunicaciones de aplicación del HTTP, además esto aumenta el rendimiento de la comunicación.
- caching (la caché puede ser pública o privada, como la caché de un navegador)
- filtrado (como un anti-virus, control parental, ...)
- balanceo de carga de peticiones (para permitir a varios servidores responder a la carga total de peticiones que reciben)
- autentificación (para el control al acceso de recursos y datos)
- registro de eventos (para tener un histórico de los eventos que se producen)

### Cliente
- Pide recursos al servidor (Imagenes, html, css)
- Tambien pide documentos de hipertexto (HTTP) con enlaces para acceder a otras páginas
- EL servidor interpreta las peticiones y procesará las respuestas HTTP para presentar al usuario las páginas que desea

### Características del protocolo
- Sencillo
- Extendible
- Con sesiones sin estados
- Conexiones: No necesita que el protocolo mantenga comunicación continua, únicamente que sea un protocolo fiable y que los paquetes no se pierdan.

### Flujo HTTP
- Abre la conexión para realizar una petición.
- 



### Preguntas?
- Quien empieza la comunicación?
- El computador respondiendo una petición en la url es?
- Que otros elementos intermedios permiten la comunicación entre el protocolo HTTP?
- El servidor nunca para?
