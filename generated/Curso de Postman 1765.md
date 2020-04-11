# Introducción y repaso de API

## 0010. Introducción al curso

### Descripción:


### Links:

* [GitHub - platzi/postman-course](https://github.com/platzi/postman-course)

### Comentarios:

* **Ludwring Liccien** (4)

	
	No se indica con que api se va a trabajar. En los Archivos y enlaces hay un proyecto en Python pero la documentación esta mala y no funciona el proyecto.  
	Se debe crear una mejor documentacion o aceptar lo pull requiest que se han hecho
	
	Yo recomiendo que al que le alla funcionado la api la suba a servision como [Now.sh](http://Now.sh) o Geroku y la comparta
	
	![](https://pasteboard.co/ISHSEPQ.png)

* **Juan Manuel Pérez Altamirano** (4)

	
	Yo uso Postman todos los días, veamos este curso para reforzar conocimientos!!!

	* **Christian David Sánchez** (1)
Igualmente es mi fiel amigo. Hay que reforzar los conocimientos

	* **CristianSAM** (2)

		
		Hola! ¿Trabajas en el backend? Estoy aprendiendo JS, para entrar al Backend… ¿Cómo te ha ido? Puedes compartirme tu learning path…
		
		Gracias.

	* **Juan Manuel Pérez Altamirano** (2)

		
		Hola, Actualmente estoy estudiando también sobre Javascript, considero que la carrera de JS de Platzi, está sumamente completa.
		
		En mi caso me interesa aprender React Native, para el desarrollo móvil y node.js para el servidor.
		
		Saludos

	* **mafevito** (1)

		
		¡Hola @CristianSAM!
		
		Te recomiendo echarle un vistazo a[ esto](https://roadmap.sh/backend), es una hoja de ruta que puedes usar como guía para convertirte en un desarrollador backend.

* **Victor Manuel Franco Cañon** (3)

	
	Este curso sera una introducción al uso de postman y las implicaciones para el protocolo http mediante la implementación REST como es conocido el conjunto de principios de diseño que permite a HTTP abrazar su máxima potencia mediante la creación de interfaces, que pueden utilizarse desde casi cualquier dispositivo o sistema operativo, en pocas palabras REST es una forma sencilla de organizar interacciones entre sistemas independientes.  
	.  
	La alternativa es la construcción de convenciones relativamente complejas por encima de HTTP. A menudo, esto toma la forma de nuevos enteros lenguajes basados en XML. El ejemplo más ilustre es SOAP. Tienes que aprender un conjunto completamente nuevo de convenciones, pero nunca usas HTTP a su máxima potencia.  
	.  
	![](https://upload.wikimedia.org/wikipedia/commons/7/73/Suite_de_Protocolos_TCPIP.png)  
	.  
	Conceptos extraídos de:
	
	  * <https://code.tutsplus.com/es/tutorials/a-beginners-guide-to-http-and-rest--net-16340>
	
	

* **Bryan Estiven Silva Mercado** (3)

	
	Hace poco descargue la herramienta así que este curso me va perfecto

* **Brayan Mamani** (3)

	
	¡El curso que estaba esperando!

	* **Christian David Sánchez** (1)
Ya somos dos 😎😎😎

	* **Luzdelia Alba** (2)

		
		tres 😄

* **Manuel Alejandro Aguilar Téllez Girón** (2)

	
	Estoy tomando el curso de Django avanzado aquí en platzi y necesito saber usar postman así que, a darle. 🔥

* **ehnbytes** (2)

	
	Iniciando el curso!!!

* **Daniel Meza** (2)

	
	Maravillado de la nueva intro. 🙌

* **humansonofhuman** (2)

	
	En este video está el enlace al repositorio de la api con la que se va a trabajar
	
	<https://github.com/platzi/postman-course>

* **Christian David Sánchez** (2)

	
	Todo developer debe hacerse buen amigo de postman 😃  
	#NeverStopLearning

* **Jean Carlos Nuñez Hernandez** (2)

	
	Bueno bueno vamos con postman ahora!!

* **Iván Acosta** (1)

	
	Con muchas expectativas del curso! Vamos a por ello.

* **Daniel Carmona** (1)

	
	Quiero aprender a usar bien postman

* **idmc3010** (1)

	
	vamos a darle 😄 en este curso , se ve muy interesante.

* **Kelly Jesus Salazar Sanchez** (1)

	
	Genial siempre quise aprender POSTMAN

* **Pablo Rocha** (1)

	
	No sabía de la existencia de este curso, uso POSTMAN pero creo que le saco menos potencial del que tiene.

* **markyhuevone** (1)

	
	Hola, al querer hacer el source admin_info.sh me da error al crear la DB, y a la vez el puerto 8000 no lo reconoce. A alguien le paso algo similar al querer levantar el proyecto en docker? Saludos!

	* **walis85300 (Platzi)** (1)

		
		qué error te sale?

	* **Cristian David Franco Garcia** (1)

		
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/base/base.py”, line 217, in ensure_connection  
		self.connect()  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/base/base.py”, line 195, in connect  
		self.connection = self.get_new_connection(conn_params)  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/postgresql/base.py”, line 178, in get_new_connection  
		connection = Database.connect(**conn_params)  
		File “/usr/local/lib/python3.6/site-packages/psycopg2/ **init**.py”, line 126, in connect  
		conn = _connect(dsn, connection_factory=connection_factory, **kwasync)  
		django.db.utils.OperationalError: could not translate host name “db” to address: Name or service not known

* **Jozelyn_MG** (1)

	
	Mi herramienta de todos los días.

* **tonyoz** (1)
Es posible instalar Docker en Windows 10 Home??

	* **CarlosAlba** (1)

		
		Hola!
		
		En los [foros](https://forums.docker.com/t/installing-docker-on-windows-10-home/11722) de Doker dicen que si. Aunque hay que hacer un par de cosas para que funcione.

## 0020. Estudiando el protocolo HTTP, verbos y status

### Descripción:


### Comentarios:

* **Fran Delgado** (23)

	
	Un protocolo especifica reglas en la comunicacion entre dos entes, en este caso entre dos computudoras.
	
	HTTP (Hyper Text Transfer Protocol) fue creado especificamente para la web.
	
	Una de las cosas que especifica el protocolo HTTP son los verbos:
	
	  * **GET** : solicitar datos o algun recurso.
	  * **HEAD** : traer headers (como una peticion GET pero sin contenidos). Es util cuando vamos a utilizar APIs, para comprobar si lo que vamos a enviar esta correcto y puede ser procesado.
	  * **POST** : enviar datos a un recurso para la creación.
	  * **PUT** : reemplazar por completo un recurso.
	  * **PATCH** : reemplazar parcialmente un recurso.
	  * **DELETE** : eliminar un recurso.
	
	
	
	Otra de las cosas que especifica el protocolo HTTP son los codigo de estado (status codes). Sirven para describir el estado de la peticion hecha al servidor.
	
	  * **1xx** : Indican que la peticion fue recibida y el servidor sigue trabajando en el proceso, es decir, no fue exitosa ni fue errónea, sino que esta siendo procesada aun.
	  * **2xx** : Indican que la peticion fue recibida y procesada correctamente.
	  * **3xx** : Indican que hay que tomar acciones adicionales para completar la solicitud. Por lo general estos codigos indican redireccion. Generalmente en los APIs no se usan redirecciones porque no contienen estados, es decir, toda la informacion esta contenida en una solicitud, no se guarda un estado en el servidor con una sesion por ejemplo.
	  * **4xx** : Indican errores del lado del cliente, por ejemplo: se hizo mal la solicitud, faltan datos, headers o cualquier otro error que pueda ocurrir.
	  * **5xx** : Indican errores del servidor. Suelen aparecer cuando existe un fallo en la ejecución en el servidor.
	
	
	
	Los codigos mas comunes a la hora de interactuar con un API son:
	
	  * **200** : Todo esta OK.
	  * **201** : Todo OK cuando se hizo una solicitud **POST** , el recurso se creo y se guardo correctamente.
	  * **204** : Indica que la solicitud se completo correctamente pero no devolvio informacion. Es muy comun cuando se hacen peticiones con el verbo **DELETE**.
	  * **400** : Bad Request, algo esta mal en la peticion. Se nos olvido enviar un dato o algo relacionado. Por lo general la respuesta nos especifica cuales fueron los errores a la hora de hacer la peticion.
	  * **401** : Unauthorized, es decir, no estamos autorizados (autenticados) a realizar la peticion.
	  * **403** : Forbidden, yo no tengo acceso a ese recurso aunque este autenticado.
	  * **404** : Not Found, no existe el recurso que se esta intentando acceder.
	  * **500** : Interna Server Error, es un error que retorna el servidor cuando la solicitud no pudo ser procesada. Por lo general, si no tenemos acceso al backend, no tenemos control sobre los errores 500 que retorna un API.
	
	

* **paucuaram** (14)

	
	**Códigos de estado HTTP**  
	Sirven para describir el estado de la petición.
	
	1xx: Esto indica que la petición fue recibida y esta siendo procesada.  
	2xx: La solicitud fue completada correctamente.  
	3xx: Indica que hay acciones adicionales que se deben de hacer, por lo general se utilizan en las redirecciones.  
	4xx: Errores del cliente. Indica que se realiza una solicitud errónea.  
	5xx: Errores del servidor. Indica que el servidor presenta un error.
	
	**Errores más comunes**
	
	200: La petición fue correcta.  
	201: Es el estado cuando la solicitud Post fue correcta.  
	204: La solicitud fue procesada correctamente pero no devuelve información.  
	400: Bad request, la solicitud no es correcta.  
	401: Authorized, indica que se debe de realizar una autenticación antes de realizar una petición.  
	403: Forbidden: No se tiene acceso al recurso aunque se esté autenticado.  
	404: Not Found, el recurso no fue encontrado.  
	500: Internal Server Error, el servidor indica que la solicitud no pudo ser procesada.

	* **MayuGo Inc.** (2)

		
		Gracias, excelente información

* **paucuaram** (6)

	
	 **Verbos HTTP**  
	Get: Solicitar datos o algún recurso.  
	Head: traer headers, como una petición Get pero sin contenido.  
	Post: Enviar datos a un recurso para la creación.  
	Put: Reemplazar por completo un recurso.  
	Patch: Reemplazar parcialmente un recurso.  
	Delete: Eliminar un recurso.

* **tonyoz** (5)

	
	Las respuestas por parte de HTTP nos retorna estados / códigos de respuesta:  
	1XX: Fue recibida pero esta siendo procesada aun.  
	2XX: Indica que la petición fue recibida, aceptada y procesada.  
	3XX: Indica que se deben tomar acciones para completar la solicitud, o redirección.  
	4XX: Son errores del Cliente (Puede ser retornado por el Backend), mal solicitud, etc.  
	401: No autorizado  
	403:Sin acceso al recurso  
	404:Recurso no encontrado.  
	5XX: Errores en el servicio y/o el servidor.  
	<https://uniwebsidad.com/tutoriales/los-codigos-de-estado-de-http>

* **MayuGo Inc.** (4)

	
	Excelente introducción

* **Christian David Sánchez** (4)

	
	Les recomiendo esta lectura sobre los códigos de estados HTTP:  
	<https://uniwebsidad.com/tutoriales/los-codigos-de-estado-de-http>

	* **k7code** (2)

		
		Muchas gracias por el recurso Christian.

	* **Christian David Sánchez** (1)

		
		De nada 😃

	* **MayuGo Inc.** (2)

		
		Gracias

* **Héctor Tello** (3)

	
	 **Códigos más usados**
	
	**1\. 200:** Todo bien  
	**2\. 201:** solicitud POST se ejecutó correctamente.  
	**3\. 204:** Solicitud ejecutada correctamente y no devuelve información. Por ejemplo, al ejecutar el verbo DELETE.  
	**4\. 400:** bad request, por ejemplo, falta información.  
	**5\. 401:** No estar autenticado.  
	**6\. 403:** Forbidden. No tener aceeso a un recurso.  
	**7\. 404:** No existe el recurso. Not found.  
	**8\. 500:** La solicitud no pudo ser ejecutada.

* **Danilo Pazos** (3)

	
	Para más detalle de protocolos http, aqui:  
	<https://http.cat/>

* **LeoEsp** (2)

	
	Les dejo este enlace de w3school para que tengan otra fuente para que vean los códigos de respuesta  
	<https://www.w3schools.com/tags/ref_httpmessages.asp>

* **Carlos Arturo Gutierrez Gonzalez** (2)

	
	## Mas errores de cliente
	
	  1. [414 URI Too Long](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La URI solicitada por el cliente es más larga que el servidor está dispuesto a interpretar.
	  2. [415 Unsupported Media Type](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El formato multimedia de los datos solicitados no está soportada por el servidor, por lo cual el servidor rechaza la solicitud.
	  3. [416 Requested Range Not Satisfiable](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El rango especificado por el campo de encabezado Range en la solicitud no cumple; es posible que el rango está fuera del tamaño de los datos objetivo del URI.
	  4. [417 Expectation Failed](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Significa que la expectativa indicada por el campo de encabezado Expect solicitada no puede ser cumplida por el servidor.
	  5. [418 I’m a teapot](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor se reúsa a intentar hacer café con una tetera.
	  6. [421 Misdirected Request](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La petición fue dirigida a un servidor que no es capaz de producir una respuesta. Esto puede ser enviado por un servidor que no esta configurado para producir respuestas por la combinación del esquema y la autoridad que estan incluidos en la URI solicitada
	  7. [422 Unprocessable Entity (WebDAV)](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La petición estaba bien formada pero no se pudo seguir debido a errores de semántica.
	  8. [423 Locked (WebDAV)](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El recurso que está siendo accedido está bloqueado.
	  9. [424 Failed Dependency (WebDAV)](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La petición falló debido a una falla de una petición previa.
	  10. [426 Upgrade Required](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor se reúsa a aplicar la solicitud usando el protocolo actual pero puede estar dispuesto a hacerlo después que el cliente se actualize a un protocolo diferente. El servidor envía un encabezado Upgrade en una respuesta para indicar los protocolos requeridos.
	  11. [428 Precondition Required](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor origen requiere que la solicitud sea condicional. Tiene la intención de prevenir problemas de ‘actualización perdida’, donde un cliente OBTIENE un estado del recurso, lo modifica, y lo PONE devuelta al servidor, cuando mientras un tercero ha modificado el estado del servidor, llevando a un conflicto.
	  12. [429 Too Many Requests](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El usuario ha enviado demasiadas solicitudes en un periodo de tiempo dado.
	  13. [431 Request Header Fields Too Large](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor no está dispuesto a procesar la solicitud porque los campos de encabezado son demasiado largos. La solicitud PUEDE volver a subirse después de reducir el tamaño de los campos de encabezado solicitados.
	  14. [451 Unavailable For Legal Reasons](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El usuario solicita un recurso ilegal, como alguna página web censurada por algún gobierno.
	
	

* **Richard Castillo** (2)

	
	Comenzando mi 2do curso!

* **paucuaram** (2)

	
	**HTTP: **Es un protocolo que especifica las reglas de comunicación entre dos dispositivos.

* **AryRosvall** (1)

	
	Me gusta mucho esta página que describe muy bien todos los códigos http <https://http.cat/>

* **emrs** (1)

	
	[](https://http.cat/)

* **Carlos Arturo Gutierrez Gonzalez** (1)

	
	## Errores de cliente
	
	  1. [400 Bad Request](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Esta respuesta significa que el servidor no pudo interpretar la solicitud dada una sintaxis inválida.
	  2. [401 Unauthorized](https://developer.mozilla.org/es/docs/Web/HTTP/Status/401)  
	Es necesario autenticar para obtener la respuesta solicitada. Esta es similar a 403, pero en este caso, autenticación es posible.
	  3. [402 Payment Required](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Este código de respuesta está reservado para futuros usos. El objetivo inicial de crear este código fue para ser utilizado en sistemas digitales de pagos. Sin embargo, no está siendo usado actualmente.
	  4. [403 Forbidden](https://developer.mozilla.org/es/docs/Web/HTTP/Status/403)  
	El cliente no posee los permisos necesarios para cierto contenido, por lo que el servidor está rechazando otorgar una respuesta apropiada.
	  5. [404 Not Found](https://developer.mozilla.org/es/docs/Web/HTTP/Status/404)  
	El servidor no pudo encontrar el contenido solicitado. Este código de respuesta es uno de los más famosos dada su alta ocurrencia en la web.
	  6. [405 Method Not Allowed](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El método solicitado es conocido por el servidor pero ha sido deshabilitado y no puede ser utilizado. Los dos métodos obligatorios, GET y HEAD, nunca deben ser deshabilitados y no debiesen retornar este código de error.
	  7. [406 Not Acceptable](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Esta respuesta es enviada cuando el servidor, despues de aplicar una negociación de contenido servidor-impulsado, no encuentra ningún contenido seguido por la criteria dada por el usuario.
	  8. [407 Proxy Authentication Required](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Esto es similar al código 401, pero la autenticación debe estar hecha a partir de un proxy.
	  9. [408 Request Timeout](https://developer.mozilla.org/es/docs/Web/HTTP/Status/408)  
	Esta respuesta es enviada en una conexión inactiva en algunos servidores, incluso sin alguna petición previa por el cliente. Significa que el servidor quiere desconectar esta conexión sin usar. Esta respuesta es muy usada desde algunos navegadores, como Chrome, Firefox 27+, o IE9, usa mecanismos de pre-conexión HTTP para acelerar la navegación. También hay que tener cuenta que algunos servidores simplemente desconectan la conexión sin enviar este mensaje.
	  10. [409 Conflict](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Esta respuesta puede ser enviada cuando una petición tiene conflicto con el estado actual del servidor.
	  11. [410 Gone](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Esta respuesta puede ser enviada cuando el contenido solicitado ha sido borrado del servidor.
	  12. [411 Length Required](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor rechaza la petición porque el campo de encabezado Content-Length no esta definido y el servidor lo requiere.
	  13. [412 Precondition Failed](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El cliente ha indicado pre-condiciones en sus encabezados la cual el servidor no cumple.
	  14. [413 Payload Too Large](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La entidad de petición es más larga que los limites definidos por el servidor; el servidor puede cerrar la conexión o retornar un campo de encabezado Retry-After.
	
	

* **Carlos Arturo Gutierrez Gonzalez** (1)

	
	## Errores de servidor
	
	  1. [500 Internal Server Error](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor ha encontrado una situación que no sabe como manejarla.
	  2. [501 Not Implemented](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El método solicitado no esta soportado por el servidor y no puede ser manejada. Los unicos métodos que los servidores requieren soporte (y por lo tanto no deben retornar este código) son GET y HEAD.
	  3. [502 Bad Gateway](https://developer.mozilla.org/es/docs/Web/HTTP/Status/502)  
	Esta respuesta de error significa que el servidor, mientras trabaja como una puerta de enlace para obtener una respuesta necesaria para manejar la petición, obtuvo una respuesta inválida.
	  4. [503 Service Unavailable](https://developer.mozilla.org/es/docs/Web/HTTP/Status/503)  
	El servidor no esta listo para manejar la petición. Causas comunes puede ser que el servidor está caido por mantenimiento o está sobrecargado. Hay que tomar en cuenta que junto con esta respuesta, una página usuario-amigable explicando el problema debe ser enviada. Estas respuestas deben ser usadas para condiciones temporales y el encabezado HTTP Retry-After: debería, si es posible, contener el tiempo estimado antes de la recuperación del servicio. El webmaster debe también cuidar los encabezados relacionados al caché que son enviados junto a esta respuesta, ya que estas respuestas de condicion temporal deben usualmente no estar en el caché.
	  5. [504 Gateway Timeout](https://developer.mozilla.org/es/docs/Web/HTTP/Status/504)  
	Esta respuesta de error es dada cuando el servidor está actuando como una puerta de enlace y no puede obtener una respuesta a tiempo.
	  6. [505 HTTP Version Not Supported](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La versión de HTTP usada en la petición no está soportada por el servidor.
	  7. [506 Variant Also Negotiates](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor tiene un error de configuración interna: negociación de contenido transparente para la petición resulta en una referencia circular.
	  8. [507 Insufficient Storage](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor tiene un error de configuración interna: la variable de recurso escogida esta configurada para acoplar la negociación de contenido transparente misma, y no es por lo tanto un punto final adecuado para el proceso de negociación.
	  9. [508 Loop Detected (WebDAV)](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor detectó un ciclo infinito mientras procesaba la solicitud.
	  10. [510 Not Extended](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Extensiones adicionales para la solicitud son requeridas para que el servidor las cumpla.
	  11. [511 Network Authentication Required](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El código de estado 511 indica que el cliente necesita auntenticar para ganar acceso a la red.
	
	

* **Carlos Arturo Gutierrez Gonzalez** (1)

	
	## Redirecciones
	
	  1. [300 Multiple Choice](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Esta solicitud tiene más de una posible respuesta. User-Agent o el usuario debe escoger uno de ellos. No hay forma estandarizado de seleccionar una de las respuestas.
	  2. [301 Moved Permanently](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Este código de respuesta significa que la URI del recurso solicitado ha sido cambiado. Probablemente una nueva URI sea devuelta en la respuesta.
	  3. [302 Found](https://developer.mozilla.org/es/docs/Web/HTTP/Status/302)  
	Este código de respuesta significa que el recurso de la URI solicitada ha sido cambiado temporalmente. Nuevos cambios en la URI serán agregados en el futuro. Por lo tanto, la misma URI debe ser usada por el cliente en futuras solicitudes.
	  4. [303 See Other](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor envia esta respuesta para dirigir al cliente a un nuevo recurso solcitado a otra dirección usando una petición GET.
	  5. [304 Not Modified](https://developer.mozilla.org/es/docs/Web/HTTP/Status/304)  
	Esta es usada para propositos de “caché”. Le indica al cliente que la respuesta no ha sido modificada. Entonces, el cliente puede continuar usando la misma versión almacenada en su caché.
	  6. [305 Use Proxy ](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Fue definida en una versión previa de la especificación del protocolo HTTP para indicar que una respuesta solicitada debe ser accedida desde un proxy. Ha quedado obsoleta debido a preocupaciones de seguridad correspondientes a la configuración de un proxy.
	  7. [306 unused](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Este código de respuesta ya no es usado más. Actualmente se encuentra reservado. Fue usado en previas versiones de la especificación HTTP1.1.
	  8. [307 Temporary Redirect](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor envía esta respuesta para dirigir al cliente a obtener el recurso solicitado a otra URI con el mismo metodo que se uso la petición anterior. Tiene la misma semántica que el código de respuesta HTTP 302 Found, con la excepción de que el agente usuario no debe cambiar el método HTTP usado: si un POST fue usado en la primera petición, otro POST debe ser usado en la segunda petición.
	  9. [308 Permanent Redirect](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Significa que el recurso ahora se encuentra permanentemente en otra URI, especificada por la respuesta de encabezado HTTP Location:. Tiene la misma semántica que el código de respuesta HTTP 301 Moved Permanently, con la excepción de que el agente usuario no debe cambiar el método HTTP usado: si un POST fue usado en la primera petición, otro POST debe ser usado en la segunda petición.
	
	

* **Carlos Arturo Gutierrez Gonzalez** (1)

	
	## **Respuestas satisfactorias**
	
	  1. [200 OK](https://developer.mozilla.org/es/docs/Web/HTTP/Status/200)  
	La solicitud ha tenido éxito. El significado de un éxito varía dependiendo del método HTTP:  
	GET: El recurso se ha obtenido y se transmite en el cuerpo del mensaje.  
	HEAD: Los encabezados de entidad están en el cuerpo del mensaje.  
	PUT o POST: El recurso que describe el resultado de la acción se transmite en el cuerpo del mensaje.  
	TRACE: El cuerpo del mensaje contiene el mensaje de solicitud recibido por el servidor.
	  2. [201 Created](https://developer.mozilla.org/es/docs/Web/HTTP/Status/201)  
	La solicitud ha tenido éxito y se ha creado un nuevo recurso como resultado de ello. Ésta es típicamente la respuesta enviada después de una petición PUT.
	  3. [202 Accepted](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La solicitud se ha recibido, pero aún no se ha actuado. Es una petición “Sin compromiso”, lo que significa que no hay manera en HTTP que permita enviar una respuesta asíncrona que indique el resultado del procesamiento de la solicitud. Está pensado para los casos en que otro proceso o servidor maneja la solicitud, o para el procesamiento por lotes.
	  4. [203 Non-Authoritative Information](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La petición se ha completado con éxito, pero su contenido no se ha obtenido de la fuente originalmente solicitada, sino que se recoge de una copia local o de un tercero. Excepto esta condición, se debe preferir una respuesta de 200 OK en lugar de esta respuesta.
	  5. [204 No Content](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La petición se ha completado con éxito pero su respuesta no tiene ningún contenido, aunque los encabezados pueden ser útiles. El agente de usuario puede actualizar sus encabezados en caché para este recurso con los nuevos valores.
	  6. [205 Reset Content](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	La petición se ha completado con éxito, pero su respuesta no tiene contenidos y además, el agente de usuario tiene que inicializar la página desde la que se realizó la petición, este código es útil por ejemplo para páginas con formularios cuyo contenido debe borrarse después de que el usuario lo envíe.
	  7. [206 Partial Content](https://developer.mozilla.org/es/docs/Web/HTTP/Status/206)  
	La petición servirá parcialmente el contenido solicitado. Esta característica es utilizada por herramientas de descarga como wget para continuar la transferencia de descargas anteriormente interrumpidas, o para dividir una descarga y procesar las partes simultáneamente.
	  8. [207 Multi-Status (WebDAV)](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Una respuesta Multi-Estado transmite información sobre varios recursos en situaciones en las que varios códigos de estado podrían ser apropiados. El cuerpo de la petición es un mensaje XML.
	  9. [208 Multi-Status (WebDAV)](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El listado de elementos DAV ya se notificó previamente, por lo que no se van a volver a listar.
	  10. [226 IM Used (HTTP Delta encoding)](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	El servidor ha cumplido una petición GET para el recurso y la respuesta es una representación del resultado de una o más manipulaciones de instancia aplicadas a la instancia actual.
	
	

* **Carlos Arturo Gutierrez Gonzalez** (1)

	
	## **Respuestas informativas**
	
	  1. [100 Continue](https://developer.mozilla.org/es/docs/Web/HTTP/Status/100)  
	Esta respuesta provisional indica que todo hasta ahora está bien y que el cliente debe continuar con la solicitud o ignorarla si ya está terminada.
	  2. [101 Switching Protocol](https://developer.mozilla.org/es/docs/Web/HTTP/Status/101)  
	Este código se envía en respuesta a un encabezado de solicitud Upgrade por el cliente e indica que el servidor acepta el cambio de protocolo propuesto por el agente de usuario.
	  3. [102 Processing (WebDAV)](https://developer.mozilla.org/es/docs/Web/HTTP/Status)  
	Este código indica que el servidor ha recibido la solicitud y aún se encuentra procesandola, por lo que no hay respuesta disponible.
	
	

* **Daniel Carmona** (1)

	
	Aprendiendo de códigos

* **carlosbazanhuaman** (1)

	
	que buena definicion de protocolo.

* **Antonio Madrid** (1)

	
	La primera vez que escucho la diferencia entre el verbo PUT y PATCH.  
	Empieza bueno el curso, que buena vibra da el profesor.

* **Cristian David Franco Garcia** (1)

	
	HTTP Status Code:  
	[https://httpstatuses.com/](url)

* **Carlos Alberto Ricaldi Flores** (1)

	
	Empezando este curso con gran espectativa.

* **Victor Manuel Franco Cañon** (1)

	
	Comienzo este curso con mucha expectativa.

* **tonyoz** (1)
Cuando referimos a los Head…no es lo mismo que los parámetros que puede recibir un servicio aparte del Body? Es decir en la parte superio...

	* **alejaksot** (1)

		
		En lo que he probado, esta parte de head es validación de la estructura, mas no devuelve contenido.

## 0030. Estructuras de las URLs

### Descripción:


En un API es importante tener bien estructuradas las rutas por las cuales se usarán cada uno de los endpoints que contiene. Antes de entrar de lleno a explicar el API con el que trabajaremos en este curso veamos unos conceptos muy importantes a la hora de trabajar con APIs.

## Recurso

Es la instancia o la representación de un objeto o la representación de algo, tiene datos y operaciones asociadas a él. Por ejemplo: `course`, `material` y `video` son recursos que tenemos disponibles en el API con la que trabajaremos y podemos realizar operaciones sobre ellos: crear, actualizar y eliminar.

## Colecciones

Es un conjunto de recursos, por ejemplo: `courses` es una colección de `course.`

## URL

(Uniform Resource Locator) es la ruta en la cual puede ser ubicado un recurso y ejecutar las operaciones sobre él.

## CRUD

Siglas que hacen referencia a las operaciones básicas que se pueden ejecutar sobre un recurso:

  * C: Create (crear)
  * R: Read (leer)
  * U: Update (actualizar)
  * D: Delete (eliminar)



# Endpoints

Es el punto final de la comunicación con un ente, en este caso, un endpoint está asociado a una URL y a las operaciones que podemos ejecutar. Este término es muy utilizado en las APIs.

Los endpoint definen operaciones que se quieren ejecutar sobre un recurso. Por ejemplo: si queremos un conjunto de operaciones CRUD sobre Cursos podríamos crear los siguientes endpoints:

  * `/get-all-courses` : para obtener una colección de Cursos.
  * `/add-new-course`: para crear un nuevo recurso de Cursos.
  * `/delete-all-courses`: para eliminar todos los Cursos.



Y así sucesivamente. Pero, esto implicaría un problema. El API puede llenarse de endpoints que ejecutan una sola operación, esto no es escalable, significa que si por ejemplo el recurso Cursos pasa a llamarse Clases habría que actualizar absolutamente todas las URLs y asegurarse de ello puede convertirse en un dolor de cabeza.

Entonces, ¿cuál es la buena práctica en este caso?

Como lo vimos en la clase pasada, el protocolo HTTP especifica una serie de verbos que indican acciones. Lo ideal es que la operación que se ejecute sobre un recurso se obtenga a través del verbo HTTP de la petición y no que esté definido en el endpoint. Por ejemplo:

  * `/courses`: Dependiendo del verbo HTTP se ejecutará una operación en particular. Quedaría así: 
    * GET `/courses`: trae la colección de Cursos.
    * POST `/courses`: crea un nuevo recurso de Cursos.
    * DELETE `/courses`: elimina todos los cursos.



De esta manera queda mucho más organizado un API. Pero, qué pasa si queremos traer no una colección de cursos como en los casos anteriores, sino un recurso en específico.

Por lo general cada recurso tiene un identificador único, un ID, es con esto que llamaremos a un endpoint para que nos retorne la información del recurso. Por ejemplo:

  * GET `/courses/2/`: vemos que acá se le está pasando algo que en los endpoints anteriores no veíamos, es el número 2, ese es el identificador único, de esta manera el API sabe que tiene que buscar el curso con ID 2 y retornarlo.



Así sucesivamente con cada uno de los verbos, por ejemplo: casi nunca se hace una eliminación en masa en un API, como el ejemplo que tenemos más arriba donde se eliminan todos los cursos. Lo ideal es que se elimine un recurso individualmente y no una colección, igualmente pasa con la actualización.

## Recursos anidados

Hay veces en las que un recurso depende de otro recurso, por ejemplo, comentarios depende de materiales; usualmente en los APIs las anidaciones se hacen hasta dos niveles, es decir:

  * `materials/1/comments`: estos son dos niveles
  * `materials/1/comments/2/answers/`: son tres niveles, ahí lo ideal sería entonces separar el endpoint de comentarios y ejecutar `comments/2/answers/`



# Nuestro API

Ya he dado algunos spoilers sobre lo que nuestro API hace, es un clon de lo que Platzi es, una plataforma es donde tenemos Cursos, Materiales, Videos y Comentarios. El API es sencillo y es una prueba que utilizamos en este curso para explorar toda las capacidades que nos ofrece Postman para trabajar con ellos.

Una convención que se usa a la hora de documentar APIs es abstraer el endpoint de la URL del sitio al cual vamos a hacer la petición, puesto que esto al final es redundante de escribir, es decir, usualmente escribimos únicamente `/api-token-auth/` en vez de `[http://mistioweb.com/api-token-auth/](http://mistioweb.com/api-token-auth/)`.

## Los endpoints que tenemos:

  * `/api-token-auth/`
  * `/courses`
  * `/courses/:id/`
  * `/courses/:id/upload_badge/`
  * `/materials/`
  * `/materials/:id/`
  * `/materials/:id/comments/`
  * `/comments/`
  * `/comments/:id/`
  * `/comments/:id/like/`
  * `/comments/:id/dislike/`



### Comentarios:

* **Christian David Sánchez** (7)

	
	Algunas buenas prácticas con las APIs:
	
	**Use sustantivos en lugar de verbos**
	
	Forma correcta  
	GET / books / 123  
	DELETE / books / 123  
	POST / books  
	PUT / books / 123  
	PATCH / books / 123
	
	-vs-
	
	Forma incorrecta GET / addBook123 (por cierto, GET solo debe usarse para LEER datos y nunca cambiar su estado de ninguna manera)  
	GET / DeleteBooks / 123  
	POST / DeleteAllBooks  
	POST / books / 123 / delete
	
	Hay ciertos casos en los que está bien usar acciones de manera similar a la manipulación de recursos, por ejemplo:  
	PUT / accounts / 123 / activación
	
	Dicha solicitud crea o actualiza una propiedad de activación a una cuenta ‘123’, en lugar de simplemente decir que se debe invocar el “activar”.
	
	Es tentador usar algo como POST / activar_cuenta / 123 o PUT / cuenta / 123? Activar = verdadero, pero ambos son incorrectos.
	
	**Nombra las colecciones usando sustantivos plurales**  
	Para las colecciones en el desarrollo de API REST, use sustantivos plurales. No es solo una buena práctica establecida. Realmente hace que sea más fácil para los humanos tener una idea de que algo es en realidad una colección.
	
	P.ej.
	
	GET / cars / 123  
	POST / cars  
	GET / cars  
	-vs-  
	GET / car / 123  
	POST / car  
	GET / car

	* **imoralesMX** (3)

		
		Complemento con las reglas generales de una arquitectura rest y nos niveles de normalización que existen <https://www.arquitecturajava.com/arquitecturas-rest-y-sus-niveles/>

	* **Christian David Sánchez** (1)

		
		Excelente tu aporte!

* **Jose Luis Vega Vargas** (3)

	
	Esta explicacion esta genial mejores que muchos tutoriales no tan especificos que estan en otras paginas por no nombrarlas

* **Jonathan Uriel Jiménez Soveranes** (2)

	
	Excelente información!

* **José Padrón** (2)

	
	Me parece que esta muy completa la infomacion

* **Iván Acosta** (1)

	
	Hacia falta este glosario de términos para tener clara la terminología que se ira a usar a lo largo del curso. Quizás deba colocarse antes.

* **Luis Christian Vargas Vasquez** (1)

	
	Excelente explicación

* **David Carrasquilla** (1)

	
	Este Curso pinta muy bien 😃

* **Daniel Carmona** (1)

	
	Mucho por aprender.

* **jlbousing** (1)

	
	Tengo un año trabajando en un API que hice con Laravel y las practicas que hice no fueron buenas. Que bueno que estoy leyendo esto, ya se como hacer mejor mis próximos servicios.

* **Daniel Rojas Vidal** (1)

	
	Excelente documentación

* **carlosbazanhuaman** (1)

	
	interesante.

* **adersonrangel** (1)

	
	Super, muy buena info.

* **Arturo Carlos Alberto Castañeda Melchor** (0)

	
	Hola, que pasa con los API’s que hacen acciones especificas, consultas complejas, dependiendo de ciertos parámetros, mas de 10 filtros seguimos usando get.

	* **imoralesMX** (2)

		
		En la semántica de un servicio REST sigues usando GET porque estas “obteniendo” ó “leyendo información” no importa que tan complejo sea la operación, simplemente defines operaciones de lectura, escritura, modificación o borrado (CRUD - GET, POST, PUT ó PATCH, DELETE).
		
		Te recomiendo leer este articulo sobre que es un servicio REST y como estructurarlo
		
		<https://www.arquitecturajava.com/arquitecturas-rest-y-sus-niveles/>

	* **Arturo Carlos Alberto Castañeda Melchor** (0)

		
		Lei el articulo y dentro de él, el autor indica que para estas consultas crea adiciona un campo a su endpoint, y cambia el verbo a POST

* **tonyoz** (0)

	
	Me surge una serie de preguntas 1) Courses seria la colección?  
	2) “:id” y “id/upload_badge” serian Recursos anidados?  
	3) Es lo mismo un recurso que un EndPoint?.  
	Gracias.

	* **imoralesMX** (1)

		
		  1. La colección sería toda tu API, como por ejemplo el api de Twiter, api de Facebook, api de Platzi etc.
		  2. son request separados porque uno hace la referencia a un recurso especifico indicado por el id y el otro dice que a ese recurso especifico le quieres agregar algo
		  3. No, un recurso es una concepción abstract de lo que quieres ofrecer en tu servicio y el endpoint es en donde se va a buscar eso, es que server.
		
		
		
		mira este link te ayudara a tener las bases claras de una arq REST

	* **imoralesMX** (1)

		
		<https://www.arquitecturajava.com/arquitecturas-rest-y-sus-niveles/>

# Postman

## 0040. Instalación de Postman

### Descripción:


Postman es multiplataforma, lo que implica que no importa el sistema operativo que uses Postman funcionará.

Es esta dirección <https://www.getpostman.com/downloads/> puedes encontrar la versión de Postman más reciente y descargarla, por defecto, el sitio sabe desde qué sistema operativo estás accediendo y te muestra como primera opción, si no, más abajo aparecen los demás sistemas operativos que soporta Postman.

![Postman1.jpg](https://static.platzi.com/media/user_upload/Postman1-60f86a49-922d-4b4f-8959-7a5804105440.jpg)

# En windows

La instalación de Postman tiende a ser mucho más sencilla que la de una aplicación tradicional; no hay una serie de configuraciones que se deben aceptar o personalizar. Postman se instala en el sistema listo para utilizarse.

  * Descargar Postman

  * Abrir el archivo que se descargó, una vez abrá aparecerá una ventana así:


![Postman2 \(1\).jpg](https://static.platzi.com/media/user_upload/Postman2%20%281%29-9d5fba40-2de8-44b0-a87d-484239e03a67.jpg)

  * Una vez instalado te pedirá que inicies sesión o si es el caso que crees una nueva cuenta.

![Postman4 \(1\).jpg](https://static.platzi.com/media/user_upload/Postman4%20%281%29-e75d7c77-af56-44e7-b11b-f78989c1c835.jpg)

  * Y ya está postman listo para usarse.

![Postman5 \(1\).jpg](https://static.platzi.com/media/user_upload/Postman5%20%281%29-af8258e6-ba86-42d7-86ae-4a9b7b06b7a7.jpg)

## En MacOS

El proceso no es muy diferente a lo que es en Windows. Descargamos la App y luego la movemos a las aplicaciones de nuestro sistema y ya está lista para usarse.

### Comentarios:

* **José Padrón** (4)

	
	Para los que son usuarios de GNU/Linux Les recomiendo instalar Postman a través de la tienda de snap.
	
	**Para instalar la tienda de snap: **
	
	  * Si eres usuario de Arch, Manjaro o alguna otra distro basada en Arch. Aqui encontraras la forma de instalación:  
	<https://snapcraft.io/docs/installing-snap-on-manjaro-linux>
	
	  * Si eres usuario de Fedora y otras distros basadas en esta. Podrás instalarlo como aparece aquí:  
	<https://snapcraft.io/docs/installing-snap-on-manjaro-linux>
	
	  * Si usas Ubuntu, Debian o cualquier otra basadas en estas lo podrán hacer como aparece aquí:<https://snapcraft.io/docs/installing-snap-on-manjaro-linux>
	
	
	
	
	**Para instalar Postran Solo es con ejecutar el siguiente comando:**  
	**sudo snap install postman**

* **Christian David Sánchez** (3)

	
	Documentación de APIs en Postman: <https://learning.getpostman.com/docs/postman/api-documentation/documenting-your-api/>

* **Jose Luis Vega Vargas** (2)

	
	Listo logre instalarlo sin problemas!!

* **Daniel Carmona** (2)

	
	Instalado perfectamente.

* **carlosbazanhuaman** (1)

	
	no es muy complicado, espero que sea asi su manejo de la herramienta.

* **Pablo Rocha** (1)

	
	Bastante sencilla la instalación de Postman!

* **Jozelyn_MG** (1)

	
	Hay una configuración en especial del postman que no desactive cuando lo instale lo que provoco que a las 12 md siempre se me ejecutaban peticiones solas.

	* **imoralesMX** (1)

		
		Me explicas un poco más para ayudarte? tienes screen shot?

## 0050. Llamados a un API con GET llamado de listas y detalles de objetos

### Descripción:


### Links:

* [¡Curso de Programación Básica gratis! | ✔️Platzi](https://platzi.com/clases/programacion-basica/)

### Comentarios:

* **georgehossa** (8)

	
	toco usar la API de [STAR WARS](https://swapi.co/)

	* **davidnuma** (1)

		
		toca pero se pierde la sincronización con el curso, falla de platzi con esto

	* **Luis Rangel Castro** (1)

		
		<https://swapi.co/api/people>

* **georgehossa** (7)

	
	No funciona el repo ni los archivos para la base de datos, por favor Platzi Actualizarlo

* **Jose Luis Vega Vargas** (6)

	
	Veo que muchos esta teniendo problemas porque no Funciona el API del curso, asi que comparto esta API donde pueden trabajar, bastante parecida a swapi pero esta es de otro curso bastante bueno, <https://rickandmortyapi.com/api/character/>  
	en esta es similar el comportamiento, en vez de course/ tienen character/  
	y al colocar el id al final de character podran visualizar el personaje que se trae.
	
	espero les sirva y sigan aprendiendo. saludos.

* **Victor Inojosa** (6)

	
	Acá una lista de APIs públicas:
	
	<https://github.com/public-apis/public-apis>

	* **Kevin Javier Morales (Platzi)** (2)

		
		Muy buen aporte 😃 Si conocen de más recuerden que pueden colaborar en el repositorio

* **Bryan Estiven Silva Mercado** (6)

	
	Pueden usar esta web para realizar pruebas de peticiones get con postman [restcuntries.eu](http://restcountries.eu/)

* **tonyoz** (6)
Hay algun curso donde enseñen a crear las APIS?

	* **Jesús Ibarra** (3)

		
		@tonyoz te recomiendo este [curso](https://platzi.com/cursos/api-rest/).

* **Andrés Campuzano Garzón** (5)

	
	Yo estoy usando <https://platzi-user-api.jecsham.com/api/v1/getUserSummary/@andres-campuzano-garzon>

	* **Cristian Andrés Córdova Valencia** (3)

		
		Se puede usar perfectamente para esta clase.
		
		Muchas gracias 😄

	* **Andrés Campuzano Garzón** (1)

		
		Un gusto.

	* **emanuel-alejandro-mamani** (1)

		
		hola que tal, como puedo remplazar tu cuenta por mi cuenta de platzi, intente cambiando el final de la url con mi nombre pero me tira 403, por lo que entiendo no estoy autorizado

	* **Andrés Campuzano Garzón** (1)

		
		Lo que pasa es que esta API es construida por otro estudiante en la pagina web de esa persona.

* **Alexander Armúa Abregu** (4)

	
	Si no pueden consumir la api de platzi o levantar un servidor en local existen diversas apis interesantes.  
	Yo use una publica de pokemon:  
	<https://pokeapi.co/>
	
	Saludosss

* **jhon manuel angulo moncada** (3)

	
	Me parece que a este curso le falta mucha información al respecto de como iniciar… =(

* **HENRY DSANTIAGO** (3)

	
	Este curso forma parte de la carrera de la carrera FrontEnd, pero aquí lo tratan únicamente como si fuera BackEnd. Yo descargué los archivos y no tengo ni idea de qué hacer con ellos. Creo que faltó la clase donde al menos explicaran como hacer uso de ellos, la configuración o cómo poner a correr el servidor. Primera vez que me pasa esto en un curso de Platzi, pero es lamentable.

* **Bryan Estiven Silva Mercado** (3)

	
	Los recursos se encuentran en [postman](https://github.com/platzi/postman-course)

	* **Ernesto_ars** (1)

		
		Gracias, no los encontraba

* **Jean Carlos Nuñez Hernandez** (3)

	
	Verbo Get para traer recursos y detalles del recurso

* **Iván Darío Sánchez Jiménez** (2)

	
	En mi caso el servicio de postgres se apagaba inmediatamente (exited) para corregirlo modifiqué el archivo docker-compose.yaml de la forma
	``` 
	     db:
	        image: postgres
	        environment:
	          POSTGRES_HOST_AUTH_METHOD:"trust"
	    
	```

* **Ivan Quintero** (2)

	
	Arreglen la API porfa

* **imoralesMX** (2)

	
	Un vistazo rápido de que es JSON y como se forma lo puedes encontrar aqui
	
	<https://www.json.org/json-es.html>
	
	[Un objeto JSON](https://www.json.org/img/object.png)  
	[Un array JSON](https://www.json.org/img/array.png)  
	[Un valor JSON](https://www.json.org/img/value.png)

	* **Jonathan Uriel Jiménez Soveranes** (1)

		
		Gracias!

* **Antonio Ferrà Bonet** (2)

	
	Profesor nos puede pasar una web, donde estén listadas las mejores API’s

	* **Victor Inojosa** (2)

		
		No creo que exista algo “Mejores APIs”, porque eso depende de lo que busques. Solo te puedo recomendar una lista de APIs públicas:
		
		<https://github.com/public-apis/public-apis>

	* **Antonio Ferrà Bonet** (1)

		
		Gracias!  
		Me refería que si yo quiero conectar mi app, a una API rest, que me proporcione la información de películas. Dónde debería buscar? Saber si hay de pago y me compensa o hay gratuitas?

* **JandroMejia** (2)

	
	¿Alguien logró realizar peticiones a la API luego de seguir las indicaciones del README?

	* **humansonofhuman** (1)

		
		No, a mí me dio error en el cuarto paso 😦

	* **walis85300 (Platzi)** (1)

		
		qué error te sale?

	* **Alexander Galíndez** (1)

		
		Yo tengo el mismo problema, me da error cuando entro al contenedor y ejecuto el comando source admin_info.sh
		
		un fragmento del error:
		
		Traceback (most recent call last):  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/utils.py”, line 84, in _execute  
		return self.cursor.execute(sql, params)  
		psycopg2.errors.UndefinedTable: relation “auth_user” does not exist  
		LINE 1: INSERT INTO “auth_user” (“password”, “last_login”, "is_super…  
		^
		
		The above exception was the direct cause of the following exception:
		
		Traceback (most recent call last):  
		File “[manage.py](http://manage.py)”, line 21, in <module>  
		main()  
		File “[manage.py](http://manage.py)”, line 17, in main  
		execute_from_command_line(sys.argv)  
		File “/usr/local/lib/python3.6/site-packages/django/core/management/ **init**.py”, line 381, in execute_from_command_line  
		utility.execute()  
		File “/usr/local/lib/python3.6/site-packages/django/core/management/ **init**.py”, line 375, in execute  
		self.fetch_command(subcommand).run_from_argv(self.argv)  
		File “/usr/local/lib/python3.6/site-packages/django/core/management/base.py”, line 323, in run_from_argv  
		self.execute(*args, **cmd_options)  
		File “/usr/local/lib/python3.6/site-packages/django/core/management/base.py”, line 364, in execute  
		output = self.handle(*args, **options)  
		File “/usr/local/lib/python3.6/site-packages/django/core/management/commands/shell.py”, line 92, in handle  
		exec(sys.stdin.read())  
		File “<string>”, line 1, in <module>  
		File “/usr/local/lib/python3.6/site-packages/django/contrib/auth/models.py”, line 162, in create_superuser  
		return self._create_user(username, email, password, **extra_fields)  
		File “/usr/local/lib/python3.6/site-packages/django/contrib/auth/models.py”, line 145, in _create_user  
		user.save(using=self._db)  
		File “/usr/local/lib/python3.6/site-packages/django/contrib/auth/base_user.py”, line 66, in save  
		super().save(*args, **kwargs)  
		File “/usr/local/lib/python3.6/site-packages/django/db/models/base.py”, line 741, in save  
		force_update=force_update, update_fields=update_fields)  
		File “/usr/local/lib/python3.6/site-packages/django/db/models/base.py”, line 779, in save_base  
		force_update, using, update_fields,  
		File “/usr/local/lib/python3.6/site-packages/django/db/models/base.py”, line 870, in _save_table  
		result = self._do_insert(cls._base_manager, using, fields, update_pk, raw)  
		File “/usr/local/lib/python3.6/site-packages/django/db/models/base.py”, line 908, in _do_insert  
		using=using, raw=raw)  
		File “/usr/local/lib/python3.6/site-packages/django/db/models/manager.py”, line 82, in manager_method  
		return getattr(self.get_queryset(), name)(*args, **kwargs)  
		File “/usr/local/lib/python3.6/site-packages/django/db/models/query.py”, line 1186, in _insert  
		return query.get_compiler(using=using).execute_sql(return_id)  
		File “/usr/local/lib/python3.6/site-packages/django/db/models/sql/compiler.py”, line 1335, in execute_sql  
		cursor.execute(sql, params)  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/utils.py”, line 99, in execute  
		return super().execute(sql, params)  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/utils.py”, line 67, in execute  
		return self._execute_with_wrappers(sql, params, many=False, executor=self._execute)  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/utils.py”, line 76, in _execute_with_wrappers  
		return executor(sql, params, many, context)  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/utils.py”, line 84, in _execute  
		return self.cursor.execute(sql, params)  
		File “/usr/local/lib/python3.6/site-packages/django/db/utils.py”, line 89, in **exit**  
		raise dj_exc_value.with_traceback(traceback) from exc_value  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/utils.py”, line 84, in _execute  
		return self.cursor.execute(sql, params)  
		django.db.utils.ProgrammingError: relation “auth_user” does not exist

	* **walis85300 (Platzi)** (2)

		
		corre las migraciones, es un paso que no puse en el README inicialmente, ya lo cambié.
		
		Ejecuta `python manage.py migrate`

	* **Alexander Galíndez** (1)

		
		Gracias Walis, ya funciona.

	* **brapastor** (2)

		
		ya instale todo, segun el repositorio en github _Execute docker-compose up -d: This command starts a local server with the API running over 8000 port. _ lo ejecuto y me sale  
		postman-course_db_1 is up-to-date  
		postman-course_web_1 is up-to-date

	* **brapastor** (2)

		
		cuando trato de entrar a 127.0.0.1:8000 no esta ejecutandose

	* **paucuaram** (1)

		
		Hola ya ejecute la sentencia:  
		**root@ee65ca0c1e4f:/code# python[manage.py](http://manage.py) migrate**  
		Operations to perform:  
		Apply all migrations: admin, auth, authtoken, contenttypes, courses, sessions  
		Running migrations:  
		No migrations to apply.
		
		y tmb la que esta en el readme:  
		**root@ee65ca0c1e4f:/code# python[manage.py](http://manage.py) runscript migrations.admin_migration**
		
		Pero al ejecutar lo siguiente me genera un error:  
		**root@ee65ca0c1e4f:/code# source admin_info.sh**  
		Unknown command: ‘shell\r’. Did you mean shell?  
		Type ‘[manage.py](http://manage.py) help’ for usage.  
		bash: $’\r’: command not found  
		bash: $’\r’: command not found  
		CommandError: Cannot create the Token: user superadmin does not exist
		
		Clone los archivos del repositorio que se encuentra en la liga:  
		<https://github.com/platzi/postman-course.git>
		
		Hay algún paso que falte por ejecutar?
		
		Saludos

	* **JandroMejia** (1)

		
		No entiendo porque no puedo acceder a <http://127.0.0.1:8000>

* **carlossanchez27** (2)
Hola, ¿Alguien me puede indicar como instalar el API en windows?, no tengo experiencia en la creación e instalación de APIs. Saludos

	* **Erik Ochoa (Platzi)** (2)

		
		Son los mismos pasos para Windows ya que todo corre sobre **Docker** , mira aquí te he traducido la lista de pasos del [repositorio](https://github.com/platzi/postman-course):
		
		  1. Instala Docker y Docker Compose
		  2. Ejecuta `docker-compose up -d` Este comando correr el servidor API en el puerto 8000.
		  3. Entra al docker container ejecutando `exec -it postman-course_web_1 bash`
		  4. Dentro del docker container ejecuta `source admin_info.sh`
		  5. Corre las migraciones `python manage.py runscript migrations.admin_migration`
		
		

* **Jozelyn_MG** (2)
Ya descargue el repositorio, pero que hago con el?

	* **walis85300 (Platzi)** (2)

		
		El en README del repo están las instrucciones sobre cómo ejecutarlo, [Aquí puedes ver cómo hacerlo](https://github.com/walis85300/postman-course#how-to-run-this-project)

* **Iván Darío Sánchez Jiménez** (1)

	
	El problema es que al cargar la API del repositorio el contenedor de la base de datos se ejecuta y queda exited, quien haya podido dejarlo up comparta por favor la solución.

* **Daniel Carmona** (1)

	
	Siento que me pierdo por no haber cursado los otros cursos de creador de APIS.

	* **rogerparada** (1)

		
		pues siempre puedes hacer este: <https://platzi.com/clases/api-rest/>

* **carlosbazanhuaman** (1)

	
	podriamos centrarnos mas en el uso de la herramienta y no tanto en el json.

* **Francisca Alejandra Salinas Castillo** (1)

	
	Necesito ayuda, no puedo ejecutar en paso 4 del README: **source admin_info.sh**  
	Me aparece lo siguiente:  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-07862760-1e33-4ebd-9fec-5d1744408bd2.jpg)

	* **JandroMejia** (2)

		
		Antes de ejecutar ese comando, deberías haber realizado las migraciones con el comando `python manage.py migrate`

* **joelnbl** (1)

	
	Me sale esto Error: No such container: postman-course_web_1

	* **JandroMejia** (1)

		
		Si estas en W10, cambiar el comando `docker exec -it postman-course_web_1 bash` por `docker exec -it postmancourse_web_1 bash`

* **joseluisavalosizaguirre** (1)

	
	Hola buenas tardes, eh logrado instalar docker y ejecutar todos los comandos correctamente .
	
	root@f7e8020a8792:/code# python [manage.py](http://manage.py) migrate  
	Operations to perform:  
	Apply all migrations: admin, auth, authtoken, contenttypes, courses, sessions  
	Running migrations:  
	Applying contenttypes.0001_initial… OK  
	Applying auth.0001_initial… OK  
	Applying admin.0001_initial… OK  
	Applying admin.0002_logentry_remove_auto_add… OK  
	Applying admin.0003_logentry_add_action_flag_choices… OK  
	Applying contenttypes.0002_remove_content_type_name… OK  
	Applying auth.0002_alter_permission_name_max_length… OK  
	Applying auth.0003_alter_user_email_max_length… OK  
	Applying auth.0004_alter_user_username_opts… OK  
	Applying auth.0005_alter_user_last_login_null… OK  
	Applying auth.0006_require_contenttypes_0002… OK  
	Applying auth.0007_alter_validators_add_error_messages… OK  
	Applying auth.0008_alter_user_username_max_length… OK  
	Applying auth.0009_alter_user_last_name_max_length… OK  
	Applying auth.0010_alter_group_name_max_length… OK  
	Applying auth.0011_update_proxy_permissions… OK  
	Applying authtoken.0001_initial… OK  
	Applying authtoken.0002_auto_20160226_1747… OK  
	Applying courses.0001_initial… OK  
	Applying courses.0002_video… OK  
	Applying courses.0003_course_ranking… OK  
	Applying courses.0004_comment… OK  
	Applying courses.0005_comment_likes… OK  
	Applying courses.0006_course_badge… OK  
	Applying sessions.0001_initial… OK  
	root@f7e8020a8792:/code# source admin_info.sh  
	Generated token 9eb202378e07376b23d7b4988bc1be258df0652e for user superadmin  
	root@f7e8020a8792:/code# python [manage.py](http://manage.py) runscript migrations.admin_migration
	
	Segun el estatus todo salio correctamente, pero cuando ingreso a la direccion  
	127.0.0.0:8000/api/sources/  
	no me carga los datos, podrian indicarme si me falta hacer algo por favor.

	* **Jorge Uribe** (1)

		
		Lo lograste resolver, Jose?

* **paucuaram** (1)

	
	Hola, estoy instalando la API sin embargo al crear el contenedor postman-couse_web_1 marca errores y no puedo avanzar.
	
	Ejecuto Docker Desktop 2.1.0.5 (40693) en una pc win10.  
	Esto es lo que se obtiene en la consola:
	
	λ docker-compose up -d  
	postman-course_db_1 is up-to-date  
	Creating postman-course_web_1 … error
	
	ERROR: for postman-course_web_1 Cannot create container for service web: b’Drive sharing failed for an unknown reason’
	
	ERROR: for web Cannot create container for service web: b’Drive sharing failed for an unknown reason’  
	ERROR: Encountered errors while bringing up the project.
	
	Alguien ha solucionado este error?  
	Saludos

	* **Erik Ochoa (Platzi)** (2)

		
		Asegúrate de tener compartidas tus unidades en la configuración de Docker ![share.png](https://static.platzi.com/media/user_upload/share-430f842b-548a-47cb-aed7-4cd74f6185bd.jpg)

	* **paucuaram** (2)

		
		Si, era eso.  
		Thank u

	* **Erik Ochoa (Platzi)** (2)

		
		Cuando una respuesta les sirve a los estudiantes y recibo feedback
		
		![felicidad.jpg](https://static.platzi.com/media/user_upload/felicidad-2d8dfd33-3055-4a90-9685-96e193e8cfae.jpg)

* **gydoar** (1)

	
	Donde puedo descargar la API de ejemplo de Platzi ?

	* **imoralesMX** (1)

		
		Parece que no hay publica, pero para el sitio de Platzi u otro en general, si revisas el sitio web más o menos puede deducir algunas. En las herramientas de desarrollador vas a la parte de Network y alli veras la peticiones que hace el sitio.

	* **JandroMejia** (2)

		
		Solo debes clonar este [repositorio](https://github.com/platzi/postman-course)

* **Andres Roberto Coello Goyes** (1)

	
	Para practicar puedes utilizar  
	**JsonPlaceholder** son api públicas

* **Christian David Sánchez** (1)

	
	 **API abierta para hacer GET:**<https://datosabiertos.enacom.gob.ar/developers/>
	
	**REQUEST:**<http://api.datosabiertos.enacom.gob.ar/api/v2/datastreams/NUMER-GEOGR/data.json/?auth_key=6b31bc1fe5b3c1221e044a894aa3632438ff8351>

* **Emmanuel García** (1)
Logre con ayuda de un compañero montar el servidor para que al momento de buscar no tenga nada de información los archivos 😫 .¿Algo estoy...

* **andhreix** (1)
Hola instale el docker y tengo los archivos pero cuando entro al contenedor me posiciona en la carpeta de code y ahi no se encuentra el p...

* **CristianSAM** (1)
¿Qué API podemos utilizar para hacer este curso? Veo que la URL de Platzi no funciona, ¿Cuál puedo usar para hacer el test?

	* **humansonofhuman** (1)

		
		En el primer video en archivos y enlaces hay un link al repositorio de la api para el curso en github  
		<https://github.com/platzi/postman-course>

* **Jorge Uribe** (0)

	
	Buenos días, no he logrado recibir nada de la API, todos los pasos fueron presuntamente bien hechos, sin embargo en docker me muestra esto, al parecer un error con la relación “auth_user”. ¿Alguien sabe que me puede estar haciendo falta?
	``` 
	    <
	    RUNNING
	    
	    
	    
	    
	    ****************************************************
	    
	    WARNING: No password has been setforthe database.
	    
	    This will allow anyone with access tothe
	    
	    Postgres port to access your database. In
	    
	    Docker's default configuration, this is
	    
	    effectively any other container onthe same
	    
	    system.
	    
	    
	    Use "-e POSTGRES_PASSWORD=password"toset
	    
	    itin"docker run".
	    
	    The files belonging to this database system will be owned by user "postgres".
	    
	    This user must also own the server process.
	    
	    The database cluster will be initialized with locale "en_US.utf8".
	    
	    The default database encoding has accordingly been setto"UTF8".
	    
	    The default text search configuration will be setto"english".
	    
	    Data page checksums are disabled.
	    
	    fixing permissions on existing directory /var/lib/postgresql/data ... ok
	    
	    creating subdirectories ... ok
	    
	    selecting dynamic shared memory implementation ... posix
	    
	    selecting default max_connections ... 100
	    
	    selecting default shared_buffers ... 128MB
	    
	    selecting default time zone ... Etc/UTC
	    
	    creating configuration files ... ok
	    
	    running bootstrap script ... ok
	    
	    performing post-bootstrap initialization ... ok
	    
	    syncing data to disk ... ok
	    
	    Success. You can now start the database server using:
	    
	    pg_ctl -D /var/lib/postgresql/data -l logfile start
	    
	    initdb: warning: enabling "trust" authentication forlocal connections
	    
	    You can change this by editing pg_hba.conf or using the option -A, or
	    
	    --auth-local and --auth-host, the next time you run initdb.
	    
	    waiting for server to start....2020-02-0316:24:57.792 UTC [45] LOG: starting PostgreSQL 12.1 (Debian 12.1-1.pgdg100+1) on x86_64-pc-linux-gnu, compiled by gcc (Debian 8.3.0-6) 8.3.0, 64-bit
	    
	    2020-02-0316:24:57.795 UTC [45] LOG: listening on Unix socket "/var/run/postgresql/.s.PGSQL.5432"
	    
	    2020-02-0316:24:57.814 UTC [46] LOG: database system was shut down at2020-02-0316:24:57 UTC
	    
	    2020-02-0316:24:57.819 UTC [45] LOG: database system is ready to accept connections
	    
	    done
	    
	    server started
	    
	    /usr/local/bin/docker-entrypoint.sh: ignoring /docker-entrypoint-initdb.d/*
	    
	    waiting for server to shut down....2020-02-0316:24:57.887 UTC [45] LOG: received fast shutdown request
	    
	    2020-02-0316:24:57.889 UTC [45] LOG: aborting any active transactions
	    
	    2020-02-0316:24:57.894 UTC [45] LOG: background worker "logical replication launcher" (PID 52) exited withexit code 1
	    
	    2020-02-0316:24:57.895 UTC [47] LOG: shutting down
	    
	    2020-02-0316:24:57.908 UTC [45] LOG: database system is shut down
	    
	    server stopped
	    
	    PostgreSQL init process complete; ready for start up.
	    
	    2020-02-0316:24:58.006 UTC [1] LOG: starting PostgreSQL 12.1 (Debian 12.1-1.pgdg100+1) on x86_64-pc-linux-gnu, compiled by gcc (Debian 8.3.0-6) 8.3.0, 64-bit
	    
	    2020-02-0316:24:58.007 UTC [1] LOG: listening on IPv4 address "0.0.0.0", port 5432
	    
	    2020-02-0316:24:58.007 UTC [1] LOG: listening on IPv6 address "::", port 5432
	    
	    2020-02-0316:24:58.011 UTC [1] LOG: listening on Unix socket "/var/run/postgresql/.s.PGSQL.5432"
	    
	    2020-02-0316:24:58.025 UTC [54] LOG: database system was shut down at2020-02-0316:24:57 UTC
	    
	    2020-02-0316:24:58.029 UTC [1] LOG: database system is ready to accept connections
	    
	    2020-02-0316:33:22.033 UTC [61] ERROR: relation "auth_user"doesnot exist atcharacter13
	    
	    2020-02-0316:33:22.033 UTC [61] STATEMENT: INSERT INTO "auth_user" ("password", "last_login", "is_superuser", "username", "first_name", "last_name", "email", "is_staff", "is_active", "date_joined") VALUES ('pbkdf2_sha256$150000$O5CQik0kQFin$cWmv/4VAD85JTiNX/aeSBjtewCpPN5Y5Il/vm7xHrpA=', NULL, true, 'superadmin', '', '', 'postmancourse@course.com', true, true, '2020-02-03T16:33:21.932848+00:00'::timestamptz) RETURNING "auth_user"."id"
	    
	    2020-02-0316:33:22.860 UTC [62] ERROR: relation "auth_user"doesnot exist atcharacter280
	    
	    2020-02-0316:33:22.860 UTC [62] STATEMENT: SELECT "auth_user"."id", "auth_user"."password", "auth_user"."last_login", "auth_user"."is_superuser", "auth_user"."username", "auth_user"."first_name", "auth_user"."last_name", "auth_user"."email", "auth_user"."is_staff", "auth_user"."is_active", "auth_user"."date_joined" FROM "auth_user" WHERE "auth_user"."username" = 'superadmin'>
	    
	```

## 0060. Llamados a un API con GET parámetros en la URL

### Descripción:


### Comentarios:

* **Pablo Rocha** (4)

	
	Para quien tenga problemas en la instalación o quiera usar otra API, aquí os dejo un listado de APIs.
	
	[Public APIs](https://github.com/public-apis/public-apis)
	
	Yo ahora mismo estoy usando esta que es de los diferentes paises.  
	[REST Countries](https://restcountries.eu/)

	* **Julián Fernando Amaya Díaz** (2)

		
		Gracias Pablo buen enlace. Aquí les dejo una api de movies, necesitan registrarse para obtener el token, pero es bastante interesante y tiene mucho contenido: <https://developers.themoviedb.org/3/getting-started/introduction>

	* **Pablo Rocha** (1)

		
		Gracias @julianamayadiaz, estoy viendo la documentación y pinta muy interesante para hacer algún proyecto real 😃

* **Victor Inojosa** (3)

	
	Les recomiendo el curso de Flask para crear rápidamente una API con Python
	
	<https://platzi.com/clases/flask/>

* **Christian David Sánchez** (3)

	
	Les recomiendo este Curso de API-Rest**: <https://platzi.com/cursos/api-rest/**>

	* **adersonrangel** (2)

		
		El link de la url esta mal bro, quitale los **. Un saludo.

	* **Christian David Sánchez** (1)

		
		upps, esta bien 😃

* **adersonrangel** (3)
Que curso existe para aprender a diseñar API’s con esos detalles de paginación como Count, Next, Previuos ?

	* **JandroMejia** (1)

		
		En el caso de Python, la paginación te la hace Django REST Framework directamente, solo tenés que hacer ciertas configuraciones.

* **royergarci** (2)

	
	No logro pasar de el comando docker exec -it postman-course_web_1 bash.  
	Me lanza un error la terminal; ERROR No such container: postman-course_web_1

	* **Cristian David Franco Garcia** (2)

		
		`docker exec -it postman-course-master_web_1 bash`

	* **royergarci** (2)

		
		Muchas gracias, Cris. Escribí el comando como lo mandaste y se ejecutó todo hasta Generated token for user superadmin. Al momento de abrir el localhost en mi navegador no me muestra nada. Me sale el error ERR_EMPTY_RESPONSE ¿Sabes que pueda ser lo que sucede?

	* **Cristian David Franco Garcia** (2)

		
		No, por el momento los contenedores corren pero no responde el API

* **Jineth Daniela Granados Leguizamon** (2)

	
	este videeo no es de postman sino de diseño de apis…quedo con la duda de ver codigo de la api

* **Daniel Carmona** (1)

	
	Me cuesta con algunas Apis

* **gydoar** (1)

	
	No se pueden hacer las practicas por que no hay API para descargar, que mal.

	* **imoralesMX** (2)

		
		Si viste el contenedor docker que subieron a github para que lo corras en local y puedas probar?
		
		<https://github.com/platzi/postman-course/tree/master/project>
		
		En el README viene como montarlo

	* **JeanCarlosRodriguez** (1)

		
		Que problema tienes?  
		Que Sistema Operativo estas usando?  
		Que error te da?

	* **georgehossa** (1)

		
		me sale este error cuando corro: source admin_info.sh
		
		Traceback (most recent call last):  
		File “/usr/local/lib/python3.6/site-packages/django/db/backends/utils.py”, line 84, in _execute  
		return self.cursor.execute(sql, params)  
		psycopg2.errors.UndefinedTable: relation “auth_user” does not exist  
		LINE 1: INSERT INTO “auth_user” (“password”, “last_login”, "is_super…

## 0070. Llamados a un API con el método post utilizando JSON

### Descripción:


### Comentarios:

* **georgehossa** (9)

	
	Que bueno sería poder utilizar la API del curso para poder resolver los retos pero… NO FUNCIONA!

	* **Juan José Vega Quintero** (2)

		
		Y nada que dan solución

* **Ivan Quintero** (3)

	
	Actualicen la API que no sirve

* **Christian David Sánchez** (3)

	
	JSON: API es una especificación de cómo un cliente debe solicitar que se busquen o modifiquen los recursos, y cómo un servidor debe responder a esas solicitudes. Está diseñada para minimizar tanto la cantidad de solicitudes como la cantidad de datos transmitidos entre clientes y servidores. Esta eficiencia se logra sin comprometer la legibilidad, la flexibilidad o la capacidad de descubrimiento. **Más:**<https://jsonapi.org/format/>

* **Alexander Armúa Abregu** (2)

	
	Si no pueden usar la api de platzi en local, en esta pagina <https://jsonplaceholder.typicode.com/> pueden utilizarla para mandarle POST, GET y demas que siempre responde algo. No podran ver la informacion actualizada pero sirve para tener algo en postman

* **carlosbazanhuaman** (2)

	
	hay que actualizar los recursos para seguir la linea del curso.

* **Andres Roberto Coello Goyes** (2)

	
	 **<https://www.programacion.com.py/varios/que-es-json-web-token-jwt>**  
	para ver mas a detalle que son TOkEN viene de **JWT**

* **Ivan Quintero** (2)
No actualizan la API y asi no se anima uno a trabajar

	* **Julián Fernando Amaya Díaz** (1)

		
		Trabaja con otra API, aprendes más. Te recomiendo The Movie Database API.

* **JandroMejia** (2)
¿Sería mucho pedir que publicaran la API en Heroku?

* **Luis Christian Vargas Vasquez** (1)

	
	Excelente

* **emmanuelpaternina** (1)

	
	Muy bueno!

* **Daniel Carmona** (1)

	
	Me gusto

* **Pablo Rocha** (1)

	
	Muy útil poder usar un mismo endpoint con diferentes verbos para realizar acciones distintas 😃

* **humansonofhuman** (1)
Hola, al intentar crear el curso me devuelve un 500 le mando: { "name": "Curso de postman", "description": "The description", "t...

	* **walis85300 (Platzi)** (1)

		
		tienes el repositorio en la última versión? acabé de revisar el código y no debería generar esta excepción. Igualmente si te sigue fallando estoy pendiente para ayudarte.

## 0080. Llamados a un API con el método post utilizando Form Data

### Descripción:


### Comentarios:

* **Bryan Estiven Silva Mercado** (6)

	
	De esta manera se podrían pasar los datos con form-data  
	![](![form-data.PNG](https://static.platzi.com/media/user_upload/form-data-19ed8831-065f-42e9-849c-165f185be77a.jpg)

* **Marco Antonio Benites Espinoza** (4)

	
	Reto realizado:
	
	**1\. Mediante x-www-form-urlencoded**  
	![](https://i.ibb.co/dg8PPcM/Postman-tarea-1.png)
	
	**2\. Mediante form-data**  
	![](https://i.ibb.co/yn4frmd/Postman-tarea-2.png)

* **José Padrón** (2)

	
	Envié con comentario con form data. Si logre el reto
	
	![Captura de pantalla_2020-01-12_17-18-27.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla_2020-01-12_17-18-27-147ea77b-aa88-4694-af92-456f4431a820.jpg)

	* **Juan José Vega Quintero** (1)

		
		Parce pudo usar la api de github?

* **Pablo Rocha** (2)
El método para enviar archivos dependerá siempre de la API ¿no? Me refiero, una API puede aceptar únicamente envío de JSON mediante el bo...

	* **Erik Ochoa (Platzi)** (1)

		
		Así es, eso se define en la API.

* **carlosbazanhuaman** (1)

	
	la consola me parecio una herramienta muy buena

* **Cristian David Franco Garcia** (1)

	
	 **Enviar un objeto dentro de un array con form-data o x-www-form-urlencoded:**  
	![Annotation 2020-02-15 135821.png](https://static.platzi.com/media/user_upload/Annotation%202020-02-15%20135821-84c65af2-6ac8-4e7b-b48c-568d7947643f.jpg)

* **Cristian David Franco Garcia** (1)

	
	**Enviar un array con form-data o x-www-form-urlencoded:**  
	![a.png](https://static.platzi.com/media/user_upload/a-917007c7-d071-433b-b813-941deed6a3e9.jpg)

* **Christian David Sánchez** (1)

	
	Lista en Postman usando el verbo POST  
	(![b05868656609e4eabf29b366f24694efc1b27c40.png](https://static.platzi.com/media/user_upload/b05868656609e4eabf29b366f24694efc1b27c40-d44dd99f-28b1-4db4-891d-e86930519b04.jpg))

* **adersonrangel** (1)
Como puedes obtener la información de envió para un API (Post, Get) si no tenes la documentación respectiva o cuentas con información muy...

	* **adersonrangel** (1)

		
		En uno de los videos de la clase me dieron la respuesta. La dejo por acá  
		![](https://i.ibb.co/ZVyV4sy/obtener-urls.png)

* **Bryan Estiven Silva Mercado** (1)
¿ Podría pasar imagenes por medio de json utilizando encoded ?

	* **walis85300 (Platzi)** (2)

		
		Podrías pasar las imágenes utilizando base64, es la única forma de enviar una imagen por medio de texto.

* **Bryan Estiven Silva Mercado** (1)
¿Cuando sería recomendable usar x-www-form-urlencoded para pasar datos ? ya que entendería que si son datos planos podría usar solo raw, ...

	* **walis85300 (Platzi)** (3)

		
		Si necesitas pasar solo datos no hay diferencia entre el uso de uno u otro, pero cuando vayas a enviar archivos es recomendable usar `form-data`.

## 0090. Llamados a un API con el método PUT

### Descripción:


### Comentarios:

* **Christian David Sánchez** (3)

	
	Las diferencias entre PUT y PATCH es que PUT es reemplazo completo de la entidad, y PATCH sólo de una parte.

	* **Jonathan Uriel Jiménez Soveranes** (1)

		
		Así es!

	* **marcos_or25** (1)

		
		asi es

* **Cristian David Franco Garcia** (2)

	
	¿Con el método PUT y PATCH puedo enviar información en formato form-data?
	
	R= Sí.

* **jlbousing** (1)

	
	Yo generalmente para actualizar un contenido utilizo el método POST. Entonces lo que hago es buscar el id del recurso que le estoy enviando y actualizo los datos que tenga que actualizar…me funciona exactamente igual, entonces ¿ Qué diferencia habría si utilizo el PUT ? Se que es el deber ser porque el PUT y PATCH esta hecho para eso pero ¿Si me funciona igual ? tambien cabe destacar que no he seguido muy bien las convenciones descritas en la clase de estructuras de Url…mis endpoints son muy personalizados.

	* **Jorge Humberto Nemogá Pinzón** (2)

		
		Ahora, entiendo más de lo que creía saber. Pregunta muy acertada @jlbousing  
		En el siguiente artículo el autor lo explica de una manera genial. [HTTP diferencias entre POST y PUT](http://notasjs.blogspot.com/2013/07/http-diferencia-entre-post-y-put.html)

	* **Mariangelica Useche Saavedra** (1)

		
		Sí funciona igual, pero como todo en programación, hay buenas prácticas y convenciones que podemos seguir 😃.

* **Marco Antonio Benites Espinoza** (1)

	
	¿A traves de los metodos PUT y PATCH se puede enviar informacion con form-data?  
	Respuesta: **Si**.

* **carlosbazanhuaman** (1)

	
	se deberia poder.

* **Orlax** (1)

	
	 **Si** se puede enviar información con form-data

* **edanfesi** (1)

	
	La respuesta es SI 😃

* **Johan Sebastia Medina Camacho** (1)

	
	teóricamente si se pueden enviar por form-data puesto que funciona similar al método post

* **Jozelyn_MG** (1)

	
	Para mi si se pueden enviar datos por medio de form data.

	* **marcos_or25** (1)

		
		se puede enviar textos y archivos

* **Juan Manuel Pérez Altamirano** (1)

	
	La respuesta a la pregunta es **SI**

* **Bryan Estiven Silva Mercado** (1)

	
	Claro que se podría usar el método put y patch con form-data para actualizar la información

* **Jean Carlos Nuñez Hernandez** (1)

	
	Metodo PUT y PATCH PARA EDITAR UN COMENTARIO EN ESPECIFICO

* **Ernesto_ars** (1)
Patch solo sirve para editar un dato, porque no usar put y solo actualizar el dato que queremos?

	* **walis85300 (Platzi)** (1)

		
		En teoría el verbo PATCH es el que indica el protocolo HTTP para editar únicamente un rato del recurso, PUT también funciona pero es mejor seguir los estándares de los protocolos.

## 0100. Llamados a un API con el método DELETE

### Descripción:


### Comentarios:

* **Christian David Sánchez** (8)

	
	 **204 (No Content),** la petición se ha completado con éxito pero su respuesta no tiene ningún contenido (la respuesta sí que puede incluir información en sus cabeceras HTTP).

## 0110. Optimización de environment de postman y configuración de la colección

### Descripción:


### Comentarios:

* **Jean Carlos Nuñez Hernandez** (6)

	
	POstman acepta MARKDOWN para descripcion de sus colecciones

* **Mariana Valencia** (4)

	
	Muy buena clase 😄

* **Hebert Yovanny López Castañeda** (4)

	
	Los enviroments son muy útiles. En mi caso, utilizo gran cantidad de endpoints para entorno local, de desarrollo y producción en 9 países. Si hay un cambio en una variable, se realiza una sola vez y no 11 veces por endpoint, para dar un ejemplo.

	* **Juan José Vega Quintero** (1)

		
		Wow, en que trabaja?

* **yisus_dev** (3)

	
	a esta clase le falta información acerca del resumen del mismo, el examen pregunta algo que en la clase no hace entender a simple vista.
	
	a diferencia de otros cursos cada clase contiene un resumen de lo que se da por clase.

* **Ricardo Mesa Gallego** (2)

	
	Muy útil el tema de los Environments. Mas que todo cuando la misma API se prueba en ambientes Locales y pre-productivos. Antes de este vídeo tenia la colección con el mismo endpoint 3 o mas veces por ambiente xD

* **Cristian Andrés Córdova Valencia** (1)

	
	Súper clase!!

* **cristianggil** (1)

	
	Excelente clase y entusiasmado por lo que vendrá!

* **adersonrangel** (1)

	
	Super esta clase. Esta herramienta la puedo utilizar ya en mis proyectos thanks.

* **josedbp0107** (1)

	
	Excelente!!

* **Jean Carlos Nuñez Hernandez** (1)

	
	Un collecion es como un folder o carpeta donde pertenece los request de esa carpeta

* **Jean Carlos Nuñez Hernandez** (1)

	
	La variables globales son utiles si se van usar en toda la coleccion

## 0120. Agregar ejemplos de responses y descripción de endpoints

### Descripción:


### Comentarios:

* **Ricardo Mesa Gallego** (8)

	
	Documenta!.. Tu “yo” del futuro te lo agradecerá.

* **Eduardo P. Rivero** (6)

	
	Los ejemplos de responses también sirven para generar un mock server. Escribe sobre como crearlos en un tutorial.
	
	<https://platzi.com/tutoriales/1765-postman/4882-creando-mock-server-con-postman/>

* **Hebert Yovanny López Castañeda** (5)

	
	Una buena práctica es documentar directamente en el API, por ejemplo utilizando Swagger.

* **Bryan Estiven Silva Mercado** (3)
¿En este caso el método options debe ser creado por la persona que crea la APis, para que pueda ser utilizado, así como deben de crear mé...

	* **walis85300 (Platzi)** (2)

		
		sí, el backend debe escribir esas especificaciones, en el caso del API del curso que está construido con Django Rest Framework se especifican automáticamente según el serializador que se especifique.

* **jhon manuel angulo moncada** (1)

	
	Excelente…

* **Héctor Tello** (1)

	
	Excelente clase! muy buena forma de ir documentando la API

* **walis85300 (Platzi)** (1)

	
	Qué les pareció la clase?

	* **luisglopez7777** (4)

		
		muy buena, solamente en general para hacer el curso falto como crear la api en localhost

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Muy buena clase.

	* **walis85300 (Platzi)** (1)

		
		Excelente Diego, aprobaste el examen?

* **walis85300 (Platzi)** (1)
Alguna pregunta por acá?

	* **Ivan Quintero** (1)

		
		Si sera que pueden publicar una API funcional y que sea la misma que utilizan en el curso, porque algunos somos muy nuevos en esto y nos perdemos utilizando otras API’s

* **Jozelyn_MG** (1)
Que útil no tenia conocimientos respecto a esto!

	* **walis85300 (Platzi)** (1)

		
		me cuentas cómo fue en el curso!

# Automatización de procesos con JavaScript

## 0130. Guardar el token del login con una prueba automática

### Descripción:


### Links:

* [🚀Platzi: ‎Cursos Online Profesionales de Tecnología](https://platzi.com/clases/learning-path/escuela-js/)

### Comentarios:

* **Hebert Yovanny López Castañeda** (2)

	
	Generalmente las variables de autenticación cambian periodicamente por razones de seguridad, de esta manera, al hacerlo con las pruebas automáticas se actualizan dinámicamente.

* **Hebert Yovanny López Castañeda** (1)

	
	Otra ventaja de tener colecciones es que estas se guardan en el cloud de postman con tu cuenta y de esta manera la puedes usar desde cualquier equipo al abrir postman con tu usuario. De igual manera, la puedes exportar y compartir con tu equipo de trabajo o viceverza.

* **yisus_dev** (1)

	
	me indicas en qué clase hablas de de que nos permite hacer o lograr al tener una colección en postman?

	* **walis85300 (Platzi)** (4)

		
		No se habla en una clase en específico, pero podría decir que en los módulo de Automatización de procesos con Javascript y puesta en producción se ven las ventajas de tener todo bien organizado en una colección, podemos documentar, crear pruebas y luego publicar una documentación bastante completa de lo que hace el API.

	* **Ricardo Mesa Gallego** (2)

		
		Tener una buena colección es simplemente orden. Cuando estas en varios proyectos a la vez es super importante. Ademas de ser mas facil de compartir la colección con integrantes nuevos que llegan al proyecto y que no tengan que crear todo de cero en Postman si no importar la colección que ya esta full con documentación.

## 0140. Creación de Pruebas para endpoints

### Descripción:


### Links:

* [Test examples | Postman Learning Center](https://learning.getpostman.com/docs/postman/scripts/test-examples/)

### Comentarios:

* **Bryan Estiven Silva Mercado** (11)

	
	Como quedo mi test usando el API de spotify
	``` 
	    pm.test("Status code is 200", function () {
	        pm.response.to.have.status(200);
	    });
	    
	    
	    pm.test("JSON", function () {
	        pm.response.json();
	        
	    });
	    
	    
	    pm.test("response token" , function() {
	        
	        pm.environment.unset("token");
	      if(pm.response.to.have.jsonBody("access_token") && pm.response.to.have.jsonBody("token_type") ){
	            var json = JSON.parse(responseBody)
	            var token = `${json.token_type}${json.access_token}`;
	            pm.environment.set("token",token);
	      }    
	    })
	    
	```

	* **walis85300 (Platzi)** (1)

		
		qué genial!!

* **Jean Carlos Nuñez Hernandez** (1)

	
	Postman tiene snippets que mnos ayudan a validar ciertos reponse como 200, 401 etc

# Puesta en producción

## 0150. Publicar Documentación

### Descripción:


### Comentarios:

* **Hebert Yovanny López Castañeda** (6)

	
	Una buena práctica en el desarrollo de API, es utilizar bibliotecas de documentación como Swagger, APIDOC, etc.

* **Jean Carlos Nuñez Hernandez** (6)

	
	POSTMAN NOS PERMITE EXPORTAR COLECCIONES Y ASI ESTO SEA MANEJADA Y PORTABLE

* **Hebert Yovanny López Castañeda** (2)

	
	Otra ventaja de tener colecciones es que estas se guardan en el cloud de postman con tu cuenta y de esta manera la puedes usar desde cualquier equipo al abrir postman con tu usuario. De igual manera, la puedes exportar y compartir con tu equipo de trabajo o viceverza.

* **adersonrangel** (1)
En Postman existen algunas herramientas para el trabajo colaborativo aparte del exportar?

	* **German Giraldo Dario Giraldo** (3)

		
		Se pueden usar colecciones, que puedes compartir. Tambien se pueden establecer teams (desconozco si eso solo funciona en la version de pagio). Esta caracteristica permite no solo cmpartir colecciones, sino variables de entorno e incluso scripts

## 0160. Cierre del curso

### Descripción:


### Links:

* [Curso de API REST](https://platzi.com/clases/api-rest/)

* [Curso de Backend con Node.js](https://platzi.com/clases/backend-nodejs/)

* [Curso de Unit Testing con Jest en React](https://platzi.com/clases/jest/)

### Comentarios:

* **Hebert Yovanny López Castañeda** (3)

	
	Muy buen curso, para complementar los invito a revisar como utilizar el Runner de postman:
	
	[Intro to collection runs](https://learning.getpostman.com/docs/postman/collection-runs/intro-to-collection-runs/)

* **Juan Manuel Pérez Altamirano** (3)

	
	Excelente curso, a poner en practica yodo lo aprendido.

* **Camilo Andrés Santana Lizcano** (2)

	
	¡Excelente curso, ahora si le puedo sacar todo el jugo a Postman y lo de Documentación Wow !

* **Hebert Yovanny López Castañeda** (2)

	
	Muy buen curso, para complementar los invito a revisar como utilizar Runner en postman:
	
	[Intro to collection runs](https://learning.getpostman.com/docs/postman/collection-runs/intro-to-collection-runs/)

* **Enrique Alexis Lopez Araujo** (2)

	
	📌 Un curso demasiado practico y muy bueno, si quieren seguir aprendiendo en donde se tienen por ejemplo los datos guardados pueden ver el [curso de postgres ](https://platzi.com/clases/postgresql/) un curso que les ayudara demasiado a reforzar el conocimiento sobre donde guardamos los datos que tenemos y como podrian relacionar.
	
	🔥Y por el ultimo les dejo el curso para entender mas sobre apis, el [curso de api’s](https://platzi.com/clases/api-rest/)
	
	#neverstoplearning

	* **Brando Rodríguez** (2)

		
		Muchas gracias me ayudaste mucho, buscaba este curso de Api’s

* **Jozelyn_MG** (2)

	
	Excelente curso!

* **Gerardo Manuel Reyes Fernández** (2)

	
	Estuvo muy bueno el curso

* **Bryan Estiven Silva Mercado** (2)

	
	Muy buen curso, me gusto mucho.

* **Jean Carlos Nuñez Hernandez** (2)

	
	A presentar el examen pues

* **JayceErick** (1)

	
	Buen curso , aprendi un poco mas acerca de esta potente herramienta

* **Nagcely Mendoza** (1)

	
	Muy buen curso 👏🏻👏🏻👏🏻.

* **jayroht93** (1)
Excelente curso, muy práctico y útil. 10/10

* **carlosbazanhuaman** (1)
buen curso

* **carlosbazanhuaman** (1)
buen curso; basico pero

* **andresramirez7d7501dcfd6b43ef** (1)

	
	Muy bien!

* **Julián Fernando Amaya Díaz** (1)

	
	Buen curso, gracias Profe!

* **Victor Inojosa** (1)

	
	Excelente curso. Recomiendo hacer el curso de Flask para que aprendan a crear RESTful APIs rapidamente.

