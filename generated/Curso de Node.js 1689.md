[Curso de Node.js 1689](https://platzi.com/cursos/backend-js)

# Conocer y comprender cómo se realizan las conexiones hacia los servidores a través de internet y sus implicaciones en el desarrollo de servidores [4534]

## 0010. Bienvenida y presentación del curso [22624](https://platzi.com/clases/1689-backend-js/22624-bienvenida-y-presentacion-del-curso/)

### Descripción:


¡Bienvenido al Curso de Node.JS!

En este curso nuestro profesor Carlos Hernández nos enseñará a cómo realizar una API en Node, cómo servir archivos estáticos, darle seguridad, trabajar con una buena arquitectura y más.

Carlos Hernández lleva desde el año 2006 trabajando con JavaScript y usando Node.JS incluso antes de que saliera una versión estable.

### Links:

* [Curso Online de Fundamentos de JavaScript | Platzi](https://platzi.com/cursos/fundamentos-javascript/)

### Comentarios:

* **Jesús Adrián Arroyo Ceja** (6) [723673](https://platzi.com/comentario/723673/) 

	Este curso sustituye a la serie de cursos (Básico, Esencial y Avanzado) que se encuentran actualmente en el path de Backend con NodeJS?

	* **Juan José Vega Quintero** [723673] (1)

		Este curso es nivel intermedio  
		Aquí está el path  
		<https://platzi.com/backend-javascript/>

* **Omar Jesus Hernández Bastos** (4) [794191](https://platzi.com/comentario/794191/) 

	Aqui vamos amiwitos

* **JaimeRamos** (4) [761471](https://platzi.com/comentario/761471/) 

	neo4j es una muy buena base de datos, falta un curso de platzi para eso

* **Fredy Ricardo Cortés Ramírez** (3) [730969](https://platzi.com/comentario/730969/) 

	Me gustaría saber un poco de las API, tengo entendido que éstas se buscan crear cuando necesitamos comunicar aplicaciones a datos que tengamos almacenados, por ejemplo, tengo mi sitio web y almaceno mis datos en una base de datos MySQL. Luego surge la necesidad de crear una aplicación móvil y se necesita que esta pueda gestionar esos datos que ya teníamos, por lo que optamos por crear una API. Entonces mi pregunta es, ¿Qué tipo de seguridad podemos utilizar en nuestra API, para que esos datos no sean accedidos por el usuario final?, es decir, que demos un soporte que los datos están almacenados de forma segura y no tengamos datos confidenciales como contraseñas de forma pública. Perdón si es una pregunta tonta, pero me surgió la duda.

	* **Carlos Hernández** [730969] (8)

		Muy buena pregunta.  
		.  
		Históricamente, todas las peticiones que se hacían en internet requerían recargar toda la página, ya que era el servidor quien escribía también el código del cliente (frontend).  
		.  
		Con la llegada de AJAX (peticiones HTTP asíncronas desde JS) esto cambió drásticamente. En ese momento, se podía escribir una aplicación frontend, y que el backend solo diese los datos. A este patrón, se le llamó API, por ser una interfaz de la aplicación para el programador frontend.  
		.  
		Con esta arquitectura, da igual que el cliente sea una web, una app, otro backend o una cafetera. Da igual. Pero, cómo bien dices, es muy importante saber quién accede a tu API, y qué pueden hacer.  
		.  
		Para ésto, hay muchas opciones. Puedes crear un token de aplicación, una key, y que sólo se responda si viene en una cabecera. También puedes implementar OAuth2, que es más versátil, aunque al principio parezca más complejo.  
		.  
		Para la autenticación de usuarios, lo habitual en APIs suele ser usar tokens JWT (JSON Web Token). Estos tokens cifran un objeto JSON, y se lo mandan al cliente cuando ha hecho login. El cliente deberá pasar ese objeto en todas las peticiones, para que desde el servidor se descifre, y valide si se puede o no hacer la acción.  
		.  
		El almacenamiento de contraseñas es otro tema complejo, y que suele depender de la legislación vigente en cada país. Como norma general: Que la conexión viaje a través de HTTPS, y NUNCA las almacenes en limpio, usa el módulo bcrypt.  
		.  
		Espero haberte aclarado los conceptos 😉

	* **Fredy Ricardo Cortés Ramírez** [730969] (2)

		Muchas gracias, si la verdad me aclaraste bastante la duda. Miraré los temas de JWT y OAuth2 para implementarlo al momento de crear éstas API. Gracias nuevamente, Saludos!

* **Camilo Andrés Santana Lizcano** (2) [851676](https://platzi.com/comentario/851676/) 

	De vuelta al ruedo !  
	hagamos esto 😄

* **sebastian aldana** (2) [725090](https://platzi.com/comentario/725090/) 

	Que buena motivacion con esta bienvenida al curso de node.js

* **alejandromarcano** (2) [723608](https://platzi.com/comentario/723608/) 

	Nada mejor que un profesor que se enfrenta día a día al desarrollo real de sistemas que son llevados a producción. Entusiasmado con el nuevo curso!

* **Wilson Castro Medellin** (1) [1103668](https://platzi.com/comentario/1103668/) 

	Ok go go go

* **Rabi Leonel Leon Chan** (1) [1079000](https://platzi.com/comentario/1079000/) 

	💪💪💪💪 #VamosConTodo

* **carlosextra1** (1) [1056099](https://platzi.com/comentario/1056099/) 

	Acabo de aprobar el curso de Fundamentos con nodejs. Vamos ahora por este!!

* **Mariana Valencia** (1) [1020782](https://platzi.com/comentario/1020782/) 

	Justo necesito hacer una API. A ver qué resulta 😛

* **j.santos** (1) [982165](https://platzi.com/comentario/982165/) 

	Muchas expectativas

* **Jorgelisapa** (1) [977090](https://platzi.com/comentario/977090/) 

	A darle!

* **David Valecillo** (1) [974952](https://platzi.com/comentario/974952/) 

	Este curso promete.!!

* **MartinMB** (1) [971839](https://platzi.com/comentario/971839/) 

	Vamos que vamos

* **Jefersson Steven Guevara Sánchez** (1) [956945](https://platzi.com/comentario/956945/) 

	Estoy aqui retomando reforzando conocimienrtos

* **Luis Alexander Chip** (1) [857992](https://platzi.com/comentario/857992/) 

	A porto con NodeJS

* **Rafa Jiménez** (1) [773637](https://platzi.com/comentario/773637/) 

	Hay algún repositorio con el código del curso?

	* **balachvinic** [773637] (1)

		<https://github.com/CodingCarlos/backend-node-platzi>

* **SergioBernal** (1) [724891](https://platzi.com/comentario/724891/) 

	Tenía más expectativas del curso… Esto no es realmente un curso de Node.js, es un curso para levantar un HTTP API RESTful y websockets con Node.js, Express.js, Mongoose, etc … se parece mucho a otros cursos aquí existentes…
	
	Curso Avanzado de Node.js  
	Curso de Backend con Node.js
	
	Son muy parecidos, una mezcla…
	
	Node.js sirve para más que servir respuestas y acceder a la capa de persistencia…
	
	En cuanto al examen, me ha parecido malo sinceramente. En dos preguntas se habla de “Registros de Mongodb”, eso no existe, son DOCUMENTOS y lleva a la confusión…
	
	¿Funciones internas? Supongo que te referirás a nested functions…
	
	Podría mencionar más cosas del examen, pero no tengo tanta memoria… 🤣 Lo he suspendido pero por hacerlo rápido, he fallado unas cosas tontas…
	
	Si puedo decir algo positivo, es que la parte de Websockets explica los fundamentos muy bien.
	
	Ánimo y espero que sea una opinión constructiva, tanto para Carlos como para los planificadores educativos.

	* **Carlos Hernández** [724891] (6)

		Gracias por el feedback, Sergio.
		
		Efectivamente, NodeJS es mucho más que servir archivos. De hecho, se podría hacer un curso de más de 300 horas, y seguro que quedarían cosas por ver.
		
		En éste, me he enfocado en backend, desde el punto de vista de las necesidades y usos reales en producción: Bibliotecas, arquitectura, definición de servicios…
		
		Sobre la nomenclatura, “registro” es el nombre genérico que se da, en cualquier almacén de datos mínimamente estructurados, a un objeto único de datos. En MongoDB, cómo bien apuntas, cada registro es un “documento”.
		
		En el exame, y en las clases, he optado por el nombre genérico, ya que el objetivo es formar desarrolladores backend que puedan trabajar con cualquier base de datos, independientemente de su nomenclatura específica.
		
		Muchas gracias por tu tiempo en el curso y en el feedback, que es muy valioso para no dejar de aprender.

* **Rocio Calderon Hernandez** (1) [724362](https://platzi.com/comentario/724362/) 

	Un español en Platzi !! 😮

* **Erik Alexander Estrada Otondo** (1) [723615](https://platzi.com/comentario/723615/) 

	primero 😃

## 0020. Qué es Node y cómo instalarlo [22625](https://platzi.com/clases/1689-backend-js/22625-que-es-node-y-como-instalarlo/)

### Descripción:


Node.js es un entorno en tiempo de ejecución multiplataforma de código abierto para la capa del servidor basado en el lenguaje de programación ECMAScript, asíncrono y basado en el motor V8 de Google.

Muchos proyectos utilizan Node para funcionar, como:

* [Webpack](https://github.com/webpack/webpack)
* [Babel](https://babeljs.io)
* [PM2](http://pm2.keymetrics.io)
* [Electron](https://electronjs.org)



### Links:

* [Babel · The compiler for next generation JavaScript](https://babeljs.io)

* [PM2 - Advanced Node.js process manager](http://pm2.keymetrics.io)

* [Node.js](https://nodejs.org/en/)

* [Curso Online de Fundamentos de JavaScript | Platzi](https://platzi.com/cursos/fundamentos-javascript/)

* [GitHub - webpack/webpack: A bundler for javascript and friends. Packs many modules into a few bundled assets. Code Splitting allows for loading parts of the application on demand. Through "loaders", modules can be CommonJs, AMD, ES6 modules, CSS, Ima](https://github.com/webpack/webpack)

* [Electron | Build cross platform desktop apps with JavaScript, HTML, and CSS.](https://electronjs.org)

* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/)

### Comentarios:

* **German Tellez Vanegas** (4) [806806](https://platzi.com/comentario/806806/) 

	Este curso esta mucho mejor que uno por ahí de Udemy…

* **jorgeluisv8a** (4) [744653](https://platzi.com/comentario/744653/) 

	se ve que va ser muy interesante el curso, lo que no entiendo es porque esta de ultimo ?

	* **Ruben Alvarez A** [744653] (1)

		por que es nuevo curso!

* **johannpino** (3) [900688](https://platzi.com/comentario/900688/) 

	Es mejor instalar un manejador de versión de node, ya que se puede presentar que se necesite otra versión. Recomiendo NVM

* **Washington Antonio Delgado Neira** (2) [808390](https://platzi.com/comentario/808390/) 

	Este curso reemplaza al otro de node js basico? de samir salasar? estaba buscandolo para retomarlo pero no lo encontre!!!

	* **gustavoalbertorestrepopelae** [808390] (6)

		Que bien que cambiaron el curso de Emir Salarzar, me gusta mas este profesor

* **Wilson Castro Medellin** (1) [1103686](https://platzi.com/comentario/1103686/) 

	node utilitario simple pero poderoso

* **carlosextra1** (1) [1056104](https://platzi.com/comentario/1056104/) 

	listo ya lo tenía ya que uso node js para compilar angular!

* **Crhistian Jackson Ovalle Gamba** (1) [1025269](https://platzi.com/comentario/1025269/) 

	Excelente, iniciamos con mucho entusiasmo.

* **Jorgelisapa** (1) [978179](https://platzi.com/comentario/978179/) 

	Para los sistemas basadoS en debian instalar con :  
	sudo apt update  
	sudo apt install nodejs npm

* **German Sandoval** (1) [976671](https://platzi.com/comentario/976671/) 
Se pueden quitar los subtítulos?

	* **Juan Felipe Peralta Zapata (Platzi)** [976671] (1)

		Aquí ya te han dejado respuesta a tu duda: <https://platzi.com/comment/976670/>. 😃

* **MartinMB** (1) [971842](https://platzi.com/comentario/971842/) 

	Muy buena pinta

* **ehnbytes** (1) [971648](https://platzi.com/comentario/971648/) 

	Wow, que buen curso!!

* **Dragonatak** (1) [753005](https://platzi.com/comentario/753005/) 

	Vamos adelante!!!

* **German Sandoval** (1) [81235](https://platzi.com/comentario/976670/) 
Se pueden quitar los subtítulos?

	* **CarlosAlba** [81235] (1)

		Hola!
		
		Efectivamente!
		
		En la “tuerca” o rosca de configuración puedes activar o desactivar los subtitulos.

## 0030. ¿Qué son y cómo se usan las peticiones HTTP [22608](https://platzi.com/clases/1689-backend-js/22608-que-son-y-como-se-usan-las-peticiones-http/)

### Descripción:


Una petición HTTP es un protocolo de comunicación que permite las transferencias de información en la web.

Es el lenguaje común para todas las comunicaciones.

**¿Cómo es una petición?**

**GET** /index.html HTTP/1.1  
**Host:** [www.example.com](http://www.example.com)  
**Referer:** [www.google.com](http://www.google.com)  
**User-Agent:** Mozilla/5.0  
**Connection:** keep-alive

**Puntos claves a tener en cuenta:**

* **Métodos:** Qué quieres hacer
* **Estado:** Cómo ha ido la operación
* **Cuerpo:** Lo que el servidor devuelve



### Comentarios:

* **Andres Roberto Coello Goyes** (9) [724776](https://platzi.com/comentario/724776/) 

	La diferencia de http y https es que https pasa por un canal de encriptacion haciendo que los datos que se envían por Internet sean imposibles de entender y cuando llegan al servido estos se descifra.

* **deap** (6) [732794](https://platzi.com/comentario/732794/) 

	Que gran clase gracias Shia

	* **Ezequiel Guerra** [732794] (4)

		Optimus Prime fue programado en Node.js

* **jorgeluisv8a** (5) [744668](https://platzi.com/comentario/744668/) 

	Este curso pinta muy bien, debería estar de primero en la lista de los cursos

	* **daag13** [744668] (3)

		Es cierto, en la carrera de Javascript aparece el de Fundamentos de Javascript y a continuación el de NodeJs Fundamentals, como me sentí perdido me tocó devolverme y buscar manualmente este curso.

* **Luis Alexander Chip** (3) [858047](https://platzi.com/comentario/858047/) 

	HTTP : Hyper Text Transport Protopol, protocolo para las comunicaciones web

* **Percy Tejada Donayre** (2) [973751](https://platzi.com/comentario/973751/) 

	Buena explicación!

* **MartinMB** (2) [971847](https://platzi.com/comentario/971847/) 

	Excelente explicación

* **mrcMesen** (2) [963998](https://platzi.com/comentario/963998/) 

	Puedo decir que he visto muchas personas explicando esto y es increíble la simpleza con la que lo hace! muy buena introducción aumentan mis expectativas de este curso.

* **Johan Manuel Perez Soto** (2) [877937](https://platzi.com/comentario/877937/) 

	Cosas de nignos :v

* **Wilson Marino Pablo Mendez** (2) [783450](https://platzi.com/comentario/783450/) 

	State(error, loading, data)  
	Methods(GET, POST, PUT, DELETE, etc)  
	body(response)

* **sebastian aldana** (2) [725109](https://platzi.com/comentario/725109/) 

	<https://seopressor.com/wp-content/uploads/2017/07/HTTP-vs-HTTPS.png>

* **Juan Teixeira** (1) [1117939](https://platzi.com/comentario/1117939/) 

	Mis anotaciones de esta clase.
	
	peticiones HTTP: es el protocologo de comunicación  
	que permite las transferencias de información en la web.
	
	Porque es importante ?  
	Un lenguaje comÚn para todas las comunicaciones.
	
	Cómo funciona una petición?  
	Cliente —> Internet --> servidor Y luego se devuelve la respuesta  
	Cliente <— Internet <— servidor
	
	Como es una petición?  
	Get/index.html HTTP/1.1  
	Host: www,[example.com](http://example.com)  
	referer: [www.google.com](http://www.google.com)  
	user-agent: Mozilla/5.0  
	Connection: Kepp-alive
	
	¿Como es una respuesta?  
	HTTP/1.1 200 OK  
	Date:Fri, 31 jun 2019  
	23:59:59 GMT  
	Content-Type: text/html  
	Content-length: 1221
	
	<html>…</html>
	
	¿Puntos clave?  
	Métodos:  
	Que quieres hacer
	
	Estado  
	Como ha ido la operación
	
	CUERPO  
	Lo que el servidor devuelve

* **Wilson Castro Medellin** (1) [1115020](https://platzi.com/comentario/1115020/) 

	HTTP? si por que es el lenguaje común de comunicación en la web

* **Andrés Felipe Castañeda** (1) [1113876](https://platzi.com/comentario/1113876/) 

	http y puntos claves: metodos,estado y cuerpo

* **Wilson Castro Medellin** (1) [1103706](https://platzi.com/comentario/1103706/) 

	El standar de comunicación que permite la transferencia de información en la web

* **carlosextra1** (1) [1056114](https://platzi.com/comentario/1056114/) 

	Hypertext Transfer Protocol!

* **Fernando Vallejo** (1) [1054830](https://platzi.com/comentario/1054830/) 

	HTTP es un protocolo de comunicación que permite las transferencias de información web.

* **Crhistian Jackson Ovalle Gamba** (1) [1025355](https://platzi.com/comentario/1025355/) 

	Muy buena explicación, bastante clara y pedagógica.

* **j.santos** (1) [982197](https://platzi.com/comentario/982197/) 

	PUNTOS CLAVE:
	
	Metodos(GET,etc que hare)  
	Estado(redirecciono?, error?success?)  
	Cuerpo(archivos html, info de API, archivo js) lo que el servidor devuelve

* **j.santos** (1) [982191](https://platzi.com/comentario/982191/) 

	PETICIONES HTTP:  
	Protocolo para transferir informacion, incluso puntos de Iot, es un lenguaje comun.
	
	PETICION:  
	1 cliente(servidor,pc) --> envia peticion a internet --> envia al servidor --> luego viceversa. Tiene cabeceras como:  
	GET HTTP/1.1  
	host(a donde pides), referer(de donde viene), user-agent, connection(mantenerla viva o no)  
	RESPUESTA: HTTP/1.1 200 OK  
	La version del HTTP debe ser el mismo entre la peticion y respuesta

* **ehnbytes** (1) [971653](https://platzi.com/comentario/971653/) 

	Muy buena explicación, lo mejor que he visto!!!

* **Jesús López** (1) [951238](https://platzi.com/comentario/951238/) 

	De lo mejor que he visto con respecto a HTTP. Chulada!

* **jiduartem** (1) [912702](https://platzi.com/comentario/912702/) 

	Excelente introducción. El protocolo **HTTP** es utilizado para establecer comunicaciones correctas entre dos o mas puntos. 😃

	* **Gabriel De Andrade (Platzi)** [912702] (2)

		Genial! Recuerda que para más temas relacionados con HTTP y redes están el [Curso de Fundamentos de Ingeniería de Software](https://platzi.com/clases/ingenieria/) y el [Curso de Redes e Internet](https://platzi.com/clases/redes/)

* **diego-miranda-vazquez** (1) [907569](https://platzi.com/comentario/907569/) 

	Buen inicio

* **jesusgomez12** (1) [857090](https://platzi.com/comentario/857090/) 

	HTTP es un lenguaje común para todas las comunicaciones. Como por ejemplo, entre un cliente y un servidor.

* **jesusgomez12** (1) [857088](https://platzi.com/comentario/857088/) 

	HTTP es un lenguaje común para todas las comunicaciones.

* **Johan Manuel Perez Soto** (1) [736268](https://platzi.com/comentario/736268/) 

	Excelente explicación…

## 0040. Métodos, cabeceras y estados [22626](https://platzi.com/clases/1689-backend-js/22626-metodos-cabeceras-y-estados/)

### Descripción:


 **Métodos HTTP:**

* **GET:** Recoger información del servidor.
* **POST:** Añadir información al servidor.
* **PUT:** Reemplazar información en el servidor.
* **PATCH:** Actualizar parte de la información.
* **DELETE:** Eliminar información del servidor.
* **OPTIONS:** Pedir información sobre métodos (saber si podemos ejecutar alguno de los métodos anteriores).



**Las cabeceras** serán el envío al servidor de cómo queremos hacer la petición.

**Los estados** son números que indica el estado de la petición:

* **2XX:** Todo ha ido bien.
* **3XX:** La petición se ha redirigido.
* **4XX:** Errores del cliente.
* **5XX:** Ha habido un error al procesar la petición.



### Comentarios:

* **sebastian aldana** (9) [725118](https://platzi.com/comentario/725118/) 
	
	![](https://arquivo.devmedia.com.br/exemplo/JoelRodrigues/ASPNET_WebAPI/image/relacao_verbos.png)

	* **carlosextra1** [725118] (1)

		Gracias por tu aporte!

* **Jair Israel Avilés Eusebio** (9) [724620](https://platzi.com/comentario/724620/) 

	Sitios sugeridos que contienen informacion sobre los codigos de estado de peticion de HTTP:
	
	[Httpstatuse](https://httpstatuses.com/)
	
	[Http.cat](https://http.cat/)

	* **pabloverduzcos** [724620] (1)

		[http.cat](https://http.cat/) es fabulosa 🐈.

	* **René Sanchez** [724620] (2)

		jajajjaja ame la pagina Http.cat esta de lo mejor 😃

* **MarlaCpp** (7) [863063](https://platzi.com/comentario/863063/) 

	GET: Recoger información del servidor.  
	Ejemplo: Información de un producto.  
	Listado de elementos(productos lista de chats)  
	ver una página traer un archivo css.
	
	POST: Añadir información al servidor.  
	Ejemplo: Añadir un producto nuevo.  
	Enviar un formulario.  
	crear un nuevo chat.  
	PUT: Reemplazar información en el servidor.  
	Ejemplo: Cambiar el contenido de una página.  
	Reemplazar un producto por otro.  
	Editar un mensaje.
	
	PATCH: Actualizar parte de la información.  
	Ejemplo:  
	Cambiar la foto de un usuario.  
	Modificar el precio de un producto.
	
	DELETE: Eliminar información del servidor.  
	Ejemplo:  
	Eliminar un mensaje.  
	quitar un producto del carrito.
	
	OPTIONS: Pedir información sobre métodos (saber si podemos ejecutar alguno de los métodos anteriores).  
	Ejemplo:  
	Saber si puedes ejecutar POST, PUT, PATCH o DELETE

* **sebastian aldana** (6) [725115](https://platzi.com/comentario/725115/) 
	
	![](https://plataforma.josedomingo.org/pledin/cursos/flask/curso/u01/img/dia1.png)

* **pabloverduzcos** (5) [732846](https://platzi.com/comentario/732846/) 

	Sin palabras, simplemente fue una gran clase.

* **j.santos** (4) [982221](https://platzi.com/comentario/982221/) 

	  1. Metodos:  
	-GET: recoger informacion del servidor:listas, traer archivos, css  
	-POST: añadir informacion  
	-PUT: reemplazar informacion: contenido de una pagina  
	PATCH: cuando queremos modificar solo una parte de la informacion  
	DELETE: eliminar informacion, productos del carrito por ejemplo.  
	OPTIONS: pedir informacion sobre metodos.  
	Saber si podemos ejecutar los anteriores
	
	  2. Cabeceras:  
	Nos dan informacion contextual de la petición: Como quiero hacerlo:
	
	
	
	
	Request: Autenticacion,cache, indicaciones:  
	-Cookies: permiten compartir informacion entre peticiones, guardar info para mantener la sesion  
	-CORS: manejar informacion desde fuera de nuestro servidor, cuando consume informacion desde un lado externo  
	Access-Control-Allow-Origin, desde donde puedo consumir  
	-ACCEPT: Define el contenido que puede aceptar por ejem: codificacion UTF-8 archivos js  
	-Autenticacion: Para poder pedir cosas al servidor  
	-Cache: Almacenamiento temporal, gestionar durante cuanto tiempo la respuesta sera la misma, evita menos peticiones pues las almacena  
	-Estados: Numero que indica lo que paso con la peticion:  
	200: Ok  
	201-Crea  
	300- Redireccion de la peticion, por el recurso  
	400-40x Errores del cliente  
	500- Error interno del servidor

* **Andres Roberto Coello Goyes** (4) [724780](https://platzi.com/comentario/724780/) 

	No conocía el método PACH y OPTIONS

* **sergio-medina93** (3) [901062](https://platzi.com/comentario/901062/) 

	Me encanta que explique estos conceptos tan importantes 😃

* **Ricardo Lugo Recillas** (3) [822407](https://platzi.com/comentario/822407/) 

	Metodos: lo que se quiere realizar al servidor (  
	GET = cuando se quiere obtener infotrmacoins del servidor,  
	PUT = remplaza infoprcmacion en el servidor es decir actualizaciones,  
	DELETE = se elima informacion por completo,  
	POST = añadir infromacion al servidor ,  
	PATCH = Actualizacion por partes ,  
	OPTIONS = sirve pedir informacion de los metodos si se puedne ejecutar los metodos POST, PUT, PATCH o DELETE )
	``` 
	    Cabeceras: informacion contextual de la peticion (no es lo que quiero hacer si no como lo quiero realizar)
	    -Request: el request púede ser POST, PUT, PATCH, Autentication, cache, condiciones, cors, cookies
	    -cookies = compartir informacion entre peticiones
	    -cors (cross Origin Resource Sharing) = compartir informacion afuera de nuestro servidor (Access-Control-Allow-Origin) 
	    -accept: esta solo indica que contino va a aceptar (Accept, Accept-Charset, Accept-Encoding)
	    - Autenticación: se asegura que puedes realizar una solicitud al servidor (Authorization).
	    - Cache  = gestiona por cuanto tiempo la respuesta sera la misma (Cache-Control, Expires)
	    
	    Estados: indica con un numero lo que a pasado en la peticion.
	    	200: ok
	    	201: Created
	    	Las que empiecen con 3 la peticion se redirigido
	    	301: Moved permanently
	    	304: Nor Modified
	    	errores: del cliente
	    	400: bag request
	    	401: Unauthorized
	    	403: Forbidden
	    	404: nor found
	    	errores: del servidor
	    	500: ha habido algun problema interno
	```

* **Francisco Javier Vázquez Paredes** (3) [730607](https://platzi.com/comentario/730607/) 

	Aquí les dejo una explicación un poco más detallada de cómo se deben utilizar los códigos de estado.  
	<https://adictec.com/codigos-de-estado-http/>

* **MaicolQJ** (2) [910503](https://platzi.com/comentario/910503/) 

	GET - > Obtener información.  
	POST -> Añadir información al servidor.  
	PUT -> Editar Información.  
	DELETE -> Borrar Información.  
	PATCH -> Actualizar cierta parte dela información.  
	OPTIONS -> Pedir información sobre los métodos.

* **gorydev** (2) [796503](https://platzi.com/comentario/796503/) 

	Les comparto este archivo con un “cheat sheet” de los códigos HTTP  
	[Archivo Códigos HTTP](http://www.cheat-sheets.org/saved-copy/http-response-codes-1.pdf)

* **cmarialatincloud** (2) [765239](https://platzi.com/comentario/765239/) 

	Muy buen profesor! Explica de una forma didáctica y sencilla.

* **Sebastian Cardoso Castillo** (2) [741041](https://platzi.com/comentario/741041/) 

	Una pregunta! ¿De qué cache habla en el minuto 5:20?¿La caché del servidor o del usuario?

	* **Carlos Hernández** [741041] (6)

		Caché del navegador.  
		.  
		Para aplicar caché en el servidor hay otras formas, desde usando paquetes específicos de NPM, hasta configurando un punto de entrada a Node Desde otro servicio, cómo Nginx o Varnish.

* **Chris.ha** (2) [724132](https://platzi.com/comentario/724132/) 
Excelente curso

* **Andrés Felipe Castañeda** (1) [1113884](https://platzi.com/comentario/1113884/) 

	METODOS:  
	*Get  
	*Put  
	*Delete  
	*Post  
	*Patch  
	*Options

* **Wilson Castro Medellin** (1) [1103747](https://platzi.com/comentario/1103747/) 

	Cabeceras: Como quiero hacer la petición. Aprendí que las cookies son cabeceras

* **Rabi Leonel Leon Chan** (1) [1080902](https://platzi.com/comentario/1080902/) 

	En la request:
	
	* POST
	* PUT
	* PATCH  
	Podemos tener:
	* Autenticación: Asegúrate de que puedes pedir cosas al servidor  
	Authorization
	* Cache: Almacenamiento temporal. Gestionar durante cuanto tiempo la respuesta será la misma  
	Cache-Control  
	Expires
	* Indicaciones
	* Condiciones
	* Cors (Cross Origin Resource Sharing) : Manejar información desde fuera de nuestro servicio  
	Access-Control-Allow-Origin
	* Cookies : Compartir información entre peticiones.
	* Accept: Define el contenido que acepta  
	Accept  
	Accept-Charset  
	Accept-Encoding
	
	

* **carlosextra1** (1) [1056141](https://platzi.com/comentario/1056141/) 

	los estados de las peticiones!

* **carlosextra1** (1) [1056128](https://platzi.com/comentario/1056128/) 

	con los CORS puedeo bloquear el web scraping?

	* **Gabriel De Andrade (Platzi)** [1056128] (2)

		No, tendrías que bloquear la IP específica de donde viene el scrapping. Recuerda que el web scraping funciona como si un usuario accediera a tu página, solo que en este caso el usuario es un robot 😛

* **carlosextra1** (1) [1056122](https://platzi.com/comentario/1056122/) 

	HTTP tinene estas opciones:  
	GET  
	HEAD  
	POST  
	PUT  
	DELETE  
	TRACE  
	OPTIONS  
	CONNECT  
	PATCH  
	SEARCH  
	COPY  
	LOCK  
	UNLOCK  
	MOVE  
	MKCOL  
	PROPFIND  
	PROPPATCH  
	MERGE  
	UPDATE  
	LABEL

	* **Fernando Vallejo** [1056122] (2)

		Pensar que yo solo utilizo GET y POST jejeje

* **ksanchez_cld** (1) [1020922](https://platzi.com/comentario/1020922/) 

	Vamo’alla 😄

* **alexibarra11** (1) [1006279](https://platzi.com/comentario/1006279/) 

	Excelente profesor!!

* **jorgeoxi** (1) [998765](https://platzi.com/comentario/998765/) 

	¡Qué buena explicación!

* **luisglopez7777** (1) [995378](https://platzi.com/comentario/995378/) 

	Grupo de Whatsapp sobre temas relacionados a JS: <https://chat.whatsapp.com/LsR1Zt77zIV2bUw30fMQ3M>

* **Kevin Jeremy Salazar Jimenez** (1) [987641](https://platzi.com/comentario/987641/) 

	excelente!

* **Jorgelisapa** (1) [977768](https://platzi.com/comentario/977768/) 

	Básico para entender como funciona todo!

* **David Valecillo** (1) [974968](https://platzi.com/comentario/974968/) 

	A pesar de ser conceptos conocidos es muy valiosa esta clase, siempre había sabido que los métodos PUT Y PATCH eran para editar información pero no sabia de la diferencias entre ambos, tampoco conocía la utilidad del método OPTIONS. Todo lo demás excelente también.

* **MartinMB** (1) [971858](https://platzi.com/comentario/971858/) 

	Muy bueno

* **ehnbytes** (1) [971655](https://platzi.com/comentario/971655/) 

	Wow, muy buen clase!!

* **Jaime Gonzalez** (1) [965962](https://platzi.com/comentario/965962/) 

	Que buena clase y bien resumido todo!

* **Andres Rivera** (1) [960969](https://platzi.com/comentario/960969/) 

	que excelente clase

* **jangove** (1) [909827](https://platzi.com/comentario/909827/) 

	BUENA EXPLICACIÓN NODE.JS

* **Leonel Lopez** (1) [894986](https://platzi.com/comentario/894986/) 

	pinta excelente este curso 😃 no como el de spring del cual vengo.

* **Luis Alexander Chip** (1) [858063](https://platzi.com/comentario/858063/) 

	Métodos: Petición al servidor de lo que queremos hacer.
	``` 
	    GET -	> 	Obtener información.
	    POST 	->	 Añadir información al servidor.
	    PUT 	->	 Editar Información.
	    DELETE 	->	 Borrar Información.
	    PATCH	->	Actualizar cierta parte dela información.
	    OPTIONS ->	Pedir información sobre los métodos.
	    
	```

* **zaroscar** (1) [802147](https://platzi.com/comentario/802147/) 

	Muy buena explicacion es muy sencillo y practico

* **pro_cristancho** (1) [763686](https://platzi.com/comentario/763686/) 

	Excelente curso

* **Duvan Carvajal** (1) [68383](https://platzi.com/comentario/739703/) 
Tengo una duda. Si yo envio un mensaje de texto y luego quiero editar ese mensaje porque me equivoque en una palabra ¿Eso se puede hacer ...

	* **Juan David Castro (Platzi)** [68383] (1)

		Nope. No se pueden editar los mensajes de texto. El método PATCH solo lo usamos para actualizar la información de tu servidor, ahí sí podemos editar los datos a gusto (a menos que por alguna razón lógica esto no se deba hacer). 😉

## 0050. Cuerpo y query de la petición [22627](https://platzi.com/clases/1689-backend-js/22627-cuerpo-y-query-de-la-peticion/)

### Descripción:


 **El cuerpo de la petición** es la información en sí que queremos enviar, editar o que el servidor nos devuelva.

**Las queries** van a permitirte añadir información extra a los datos que queramos enviarle al servidor.

### Comentarios:

* **Nestor David Alvarado Rondon** (17) [724136](https://platzi.com/comentario/724136/) 

	De verdad que buen profesor, como saber si tienes mas cursos?

	* **ricardocelis (Platzi)** [724136] (7)

		Los tendremos!

	* **pabloverduzcos** [724136] (1)

		Totalmente de acuerdo.

	* **renzodrivera** [724136] (1)

		De acuerdo! Explicación super clara.

	* **sebastianandrada** [724136] (1)

		coincido, explica muy bien!

	* **esdraspavon** [724136] (1)

		Genial!

* **Gtiseira** (8) [842311](https://platzi.com/comentario/842311/) 

	Me agrada mucho la forma de explicar espero que en la medida que se profundice sea igual de eficiente! gracias!

* **MaicolQJ** (7) [910548](https://platzi.com/comentario/910548/) 

	estupenda explicación, Srs de platzi, ojala fuesen así todos lo que contratan para las clases

* **Rachid Moyse Polania** (7) [744292](https://platzi.com/comentario/744292/) 

	Los que estan haciendo la carrera de Backend con JavaScript, se han dado cuenta que este es el mejor curso introductorio a NodeJS ? mejor que el Essentials y el basico

	* **jorgeluisv8a** [744292] (3)

		tienes toda la razón, lo mismo pienso yo este debería ser el primer curso de la carrera de Backend.

* **sebastian aldana** (7) [725132](https://platzi.com/comentario/725132/) 
	
	![](https://plataforma.josedomingo.org/pledin/cursos/flask/curso/u01/img/dia1.png)

* **j.santos** (6) [983308](https://platzi.com/comentario/983308/) 

	CUERPO Y QUERY DE LA PETICION:  
	CUERPO:  
	Informacion de la peticion. Los datos del usuario que queremos añadir o enviar al servidor o lo que pedimos. Si me mandan el url del usuario  
	Que tiene y como viene?  
	CONTENT-TYPE:  
	Que formatos: Depende de las cabeceras: Ej. -> text/html, text/css, application/json (el archivo js para que el navegador lo ejecute) image/jpeg
	
	REQUEST: Es la peticion al servidor  
	Ej. POST: usuario sin id, GET a [platzi.com](http://platzi.com)  
	RESPONSE: Cualquier metodo que recibimos del servidor, ejm: content-type: application/json, viene este archivo con el id traido del servidor., trae un html de index.html de platzi
	
	QUERY:  
	Informacion extra. Orden en el que quiero que vuelvan los parametros. Por ejemplo cuando le pasamos un id  
	[api.com/person?orderBy=name&age=25](http://api.com/person?orderBy=name&age=25)  
	Para compartir datos con el frontend, nunca debe enviarse info sensible como tokens o tarjetas de creditos visibles en los parametros del query para la url  
	Ej. [miweb.com?color=red](http://miweb.com?color=red)
	
	ESTRUCTURA:
	
	Añadir ? al final de la URL  
	nombre=valor, ejemplo id=3  
	Separarlos con & si es más de 1 parámetro

	* **carlosextra1** [983308] (1)

		Gracias por tu aporte! Felicidades!

* **gorydev** (6) [796531](https://platzi.com/comentario/796531/) 

	Las explicaciones han sigo geniales hasta ahora 😄 que sigan así

* **Cesar Velásquez Córdova** (3) [758579](https://platzi.com/comentario/758579/) 

	Les dejo la documentación de Node.js esperando pueda servirles  
	<https://nodejs.org/dist/latest-v10.x/docs/api/>

* **daag13** (3) [73603](https://platzi.com/comentario/837991/) 
Excelente, quiero integrar Nose Js con un proyecto existente que tengo en MVC % ¿Se podrá?

	* **Héctor Manuel Hernández Ortega** [73603] (1)

		Si te refieres a MVC,el paradigma de programación, por supuesto.

* **MartinMB** (2) [971903](https://platzi.com/comentario/971903/) 

	Las explicaciones son simples y con ejemplos de la vida real. Palabras fáciles de entender con poco tecnicismo o ese ingles mezclado con español.  
	Es realmente fácil de entender los conceptos, ojala todos fueran así

* **ehnbytes** (2) [971656](https://platzi.com/comentario/971656/) 

	Muy bueno curso, de los mejores que he encontrado!!

* **Houses** (2) [784494](https://platzi.com/comentario/784494/) 

	Excelente Clase!!

* **Diego Andres Imbus Guzman** (2) [746486](https://platzi.com/comentario/746486/) 

	Junto a Julian Duque uno de los mejores profesores de Node

* **Andrés Felipe Castañeda** (1) [1113943](https://platzi.com/comentario/1113943/) 

	Body(cuerpo): donde se envia y recibe la informacion que queremos enviar/recibir del/al servidor(resultado de peticiones)
	
	BODY depende de la cabecera  
	content-type - tipo (text/html - text/css - application/javascript) -> dependiendo del tipo hara algo especifico con el.
	
	Query -> informacion extra en la peticion  
	*especificar objeto al que queremos ingresar  
	*compartir informacion con el front/back  
	ESTRUCTURA -> ‘? NOMBRE = VALOR’

* **Wilson Castro Medellin** (1) [1103791](https://platzi.com/comentario/1103791/) 

	Forma de compartir datos entre cliente - servidor, servidor - cliente

* **Isam David Espinosa Flores** (1) [1053318](https://platzi.com/comentario/1053318/) 

	Excelente explicación!!

* **Onam Díaz-Castillo** (1) [1040994](https://platzi.com/comentario/1040994/) 

	Buen curso

* **Percy Tejada Donayre** (1) [973905](https://platzi.com/comentario/973905/) 

	Mas sencillo no puede haber.Excelente.

* **PedroCruzLicona1** (1) [961615](https://platzi.com/comentario/961615/) 

	Buen video, se explica muy bien 😃

* **cesar88** (1) [919675](https://platzi.com/comentario/919675/) 

	buenisima explicacion! la mejor que vi hasta el momento!

* **bmvalarezo** (1) [851771](https://platzi.com/comentario/851771/) 

	muy buena explicación!!!

* **Cesar Velásquez Córdova** (1) [758584](https://platzi.com/comentario/758584/) 

	Las queries que realicemos en una url deben contener name=value y el indicador ampersand (?) los separa en la dirección URL

	* **gorydev** [758584] (1)

		Hola el símbolo ? se coloca después de la ruta a la que se quiere acceder y es para especificar en la url que vendrán unos parametros por ejemplo:  
		[example.com/personas?name=carlos&curso=node](http://example.com/personas?name=carlos&curso=node)

* **Jmundaca** (1) [750616](https://platzi.com/comentario/750616/) 

	Muy buena explicacion acerca de la estructura , me gusto mucho esta clase

# Crear un servidor HTTP en Javascript, y comenzar a escuchar y responder peticiones desde un cliente . [4537]

## 0060. Crear un servidor HTTP desde NodeJS [22628](https://platzi.com/clases/1689-backend-js/22628-crear-un-servidor-http-desde-nodejs/)

### Descripción:


En esta clase vamos a iniciar nuestro proyecto de Node.JS configurando nuestro primer servidor.

### Links:

* [Node.js](https://nodejs.org/es/)

* [Curso de Express.js](https://platzi.com/cursos/express-js/)

### Comentarios:

* **alejandromarcano** (13) [724931](https://platzi.com/comentario/724931/) 

	También se puede escribir como una arrow function:
	``` 
	    app.use('/', (req,res) => res.send("Hola") )
	    
	```
	
	En express las funciones de middleware son funciones que tienen acceso al objeto de solicitud (req), al objeto de respuesta (res) y a la siguiente función de middleware en el ciclo de solicitud/respuestas de la aplicación. Más información en: <https://expressjs.com/es/guide/using-middleware.html>

	* **Adrian Garcia Saaib** [724931] (1)

		En mi trabajo quieren que usemos ES5 y no ES6

* **edwintrumpet** (5) [853899](https://platzi.com/comentario/853899/) 

	Yo siempre inicio un repositorio en GitHub, con un README sencillo antes de iniciar el proyecto con npm.  
	Y cuando creo el _package.json_ con el comando
	``` 
	    npm init -y
	    
	```
	
	Se crea automáticamente con los valores que pongo en el [README.md](http://README.md) y la url de mi repositorio.  
	Creo que es una buena práctica.

* **Iair Poloniecki** (3) [837358](https://platzi.com/comentario/837358/) 

	Qué emoción crear mi primer servidor y que ande!!!

* **jonChica** (3) [800075](https://platzi.com/comentario/800075/) 

	Para los que quieran usar la sintaxis de módulos de ES6 en lugar de CommonJS que se usa de forma nativa en NodeJS, desde la versión 12.x.x de node puede usarse con el sufijo `--experimental-modules`.  
	Además necesitamos añadir al package.json una línea:
	``` 
	    // package.json
	    {
	    ...
	    "type": "module",
	    "scripts": {
	        "start": "node --experimental-modules server.js"
	      },
	    ...
	    }
	    
	```
	
	Ya podemos usar este formato:  
	`import express from 'express'`.
	
	[https://nodejs.org/docs/latest-v12.x/api/esm.html#esm_introduction](url)

	* **lizardojara** [800075] (1)

		Yo usaba estos paquetes:
		``` 
		    "babel-cli": "^6.26.0",
		        "babel-preset-env": "^1.7.0",
		        "babel-preset-stage-3": "^6.24.1",```
		    
		    Y el comando:
		    
		    "nodemon index.js --exec babel-node"
		    
		    
		```

* **carlosextra1** (2) [1056204](https://platzi.com/comentario/1056204/) 

	This is my code!
	``` 
	    const express = require('express');
	    
	    varapp =  express();
	    
	    app.use('/', (req, res) => {
	        res.send('Que ondas Soy tu primer server con Express');
	    });
	    
	    app.listen(3000);
	    console.log('La aplicación esta escuchando en pueto:3000');```
	    
	```

* **ksanchez_cld** (2) [1020962](https://platzi.com/comentario/1020962/) 

	Pregunta. Tengo mi servidor Nodejs en Digital Ocean(Linux) y quiero que mi VScode se conecte directo (tipo FTP) y que actualice directamente a medida que guardo en el servidor y me evito tener que subir los files.
	
	Conocen algun plugin?

	* **Leonardo Casallas Beltran** [1020962] (1)

		Puedes hacerlo por medio de Git en el server, y en el repo del pc le pones como origen el server de Digital Ocean.

* **emanuel-alejandro-mamani** (2) [986719](https://platzi.com/comentario/986719/) 

	Super la clase, se re entiendo lo que explica el profe 😄

* **Ricardo Lugo Recillas** (2) [823862](https://platzi.com/comentario/823862/) 

	```
	    const express =  require('express');
	    var app = express();
	    app.use('/', function(req, resp){
	        resp.send("hola");
	    });
	    app.listen(3000);
	    console.log(" la aplication esta escuchando en el port http://localhost::3000");
	    
	```

* **Nicolas Esteban Prieto Sarmiento** (2) [803812](https://platzi.com/comentario/803812/) 

	si al entry point tiene un nombre diferente por ejemplo **index.js**  
	para ejecutarlo tendrás que hacer: `node Archivo`
	``` 
	    nodeindex
	    
	```
	
	sino saldrá el siguiente error por **notFound**
	``` 
	    internal/modules/cjs/loader.js:716
	        throw err;
	        ^
	    
	    Error: Cannot find module'/Escuela deJS/Node/Express/metodos/index'
	        at Function.Module._resolveFilename (internal/modules/cjs/loader.js:713:15)
	        at Function.Module._load (internal/modules/cjs/loader.js:618:27)
	        at Function.Module.runMain (internal/modules/cjs/loader.js:931:10)
	        at internal/main/run_main_module.js:17:11 {
	      code: 'MODULE_NOT_FOUND',
	      requireStack: []
	    }
	    
	```

* **boyarzun** (2) [726975](https://platzi.com/comentario/726975/) 

	Me surge curiosidad en el minuto 5:26 aparece _[npm.fintonic.com:4873](http://npm.fintonic.com:4873)_ ¿Por qué aparece eso?

	* **Carlos Alex Becerra Chavita** [726975] (2)

		Solo es una advertencia de linux de donde va a realizar la descarga del paquete

	* **Carlos Hernández** [726975] (3)

		 **tl;dr: Una advertencia de que no encuentra un repositorio privado.**  
		.  
		Muchas empresas tienen repositorios privados con módulos internos. Normalmente, solo son accesibles a través de una VPN. Cuando grabamos el curso, estaba haciendo un proyecto con paquetes de ese repositorio, y al no tener la VPN conectada la consola avisa de que no puede obtener paquetes de ese repositorio.

* **Tito Rodriguez** (2) [74789](https://platzi.com/comentario/859216/) 
Quisiera saber si el uso del punto y coma es obligatorio u opcional en Node. Tengo la duda porque se que en js es opcional

	* **Erik Ochoa (Platzi)** [74789] (1)

		En Node también es opcional ya funciona bajo el mismo motor de Javascript.

* **Johan Manuel Perez Soto** (2) [68217](https://platzi.com/comentario/736888/) 
Express seria una dependencia de desarrollo o de producción? 🤔🤔

	* **Juan González** [68217] (5)

		Generalmente una dependencia de desarrollo es algo que usas constantemente cuando estás creando una app. Una dependencia de producción es algo que necesariamente debes tener para que la app funcione y corra bien.

* **Juan Teixeira** (1) [1118016](https://platzi.com/comentario/1118016/) 

	Mis anotaciones
	
	//Asi nos traemos el paquete de express  
	const express = require(‘express’);
	
	//inicializamos express  
	var app = express();
	
	//para cualquier ruta devuelveme un Hola  
	app.use(’/’, (req, res) =>{  
	res.send(‘Hola’);  
	});
	
	//hay que indicarle en donde va a escuchar  
	app.listen(3000)  
	console.log(‘La app esta escuchando en <http://localhost:3000>’);

* **Wilson Castro Medellin** (1) [1115131](https://platzi.com/comentario/1115131/) 

	El servidor solo funciona en local? se puede en un hosting?

* **OrNano** (1) [1000274](https://platzi.com/comentario/1000274/) 

	Crack!!

* **Missael Mora** (1) [985710](https://platzi.com/comentario/985710/) 

	Como puedo hacer para que mi terminal tambien se vea de colores?

	* **Georgie Duarte** [985710] (3)

		toma el curso de prework de la escuela de javascript

	* **Gabriel De Andrade (Platzi)** [985710] (1)

		[Curso de Prework](https://platzi.com/clases/prework/) la terminal se llama ZSH con el Framework OH-MY-ZSH 😄

* **juanvalero252** (1) [984163](https://platzi.com/comentario/984163/) 

	Como hago para que mi terminal se vea como la de el con el “bash” en vez de que me salgan el “cmd” como predeterminado

	* **Georgie Duarte** [984163] (2)

		toma el curso de prework de la escuela de js

* **Jorgelisapa** (1) [978174](https://platzi.com/comentario/978174/) 

	Para los sistemas basadoS en debian instalar con :  
	sudo apt update  
	sudo apt install nodejs npm

* **MartinMB** (1) [971930](https://platzi.com/comentario/971930/) 

	Fantastico

* **franco-manca** (1) [891575](https://platzi.com/comentario/891575/) 

	Tengo instalado Node y lo puedo verificar en la powerShell con el comando “node -v”. El problema que no lo puedo verificar en la terminal de VisualStudioCode

	* **Mario Uriarte Amaya** [891575] (2)

		Seguro no lo tienes en el PATH.

	* **MaicolQJ** [891575] (2)

		en Visual Studio Code pruebalo con “node --version”

	* **Miguel Angel Morales Larriega** [891575] (1)

		Me pasó lo mismo, sólo cerré y volvi a abrir el VScode y funcionó…

	* **Jesús López** [891575] (1)

		¿pudiste resolverlo?

* **edwintrumpet** (1) [853845](https://platzi.com/comentario/853845/) 

	Creo que no le aceptó la versión **0.1.0**  
	Cuando creó el _package.json_ se puso la versión que venía por defecto **1.0.0**

* **jorge-andres-perdomo** (1) [81993](https://platzi.com/comentario/994777/) 
No entendí qué es lo que hace el método use.

	* **Erik Ochoa (Platzi)** [81993] (1)

		`use` nos sirve en este caso para definir las rutas, es decir al hacer una petición al servidor en la ruta `/` se va a ejecutar la función que mandamos como segundo parámetro. Te va a quedar más claro en las siguientes clases.
		
		Mientras puedes dar una leída a la documentación oficial de [MDN](https://developer.mozilla.org/es/docs/Learn/Server-side/Express_Nodejs/Introduction) a la sección **Creando manejadores de rutas**.

* **tobivillarroelpini** (1) [81380](https://platzi.com/comentario/980086/) 
Es sumamente importante hacer el curso de express antes de continuar con el curso o puedo hacerlo al de node sin problemas?

	* **Juan David Castro (Platzi)** [81380] (2)

		Mi recomendación es que tomes este curso antes que el de Express. 😉

* **Sebastián Pineda Duque** (0) [774575](https://platzi.com/comentario/774575/) 

	¿Por qué se utiliza Express para este tipo de ejemplos? Node tiene sus propios módulos nativos, y Express no es el único framework para Node 😕

	* **gorydev** [774575] (6)

		No es el único pero es super sencillo de entender y es el más utilizado por eso la mayoría de cursos se basan en express

## 0070. ¿Cómo pueden venir las peticiones [22629](https://platzi.com/clases/1689-backend-js/22629-como-pueden-venir-las-peticiones/)

### Descripción:


### Links:

* [Insomnia REST Client](https://insomnia.rest/)

### Comentarios:

* **gabino18** (14) [958006](https://platzi.com/comentario/958006/) 

	Para no tener que andar bajando y subiendo el server se puede instalar una librería que se llama **nodemon** , la cual detecta cambios en el file system del proyecto y hace el reload del proyecto automáticamente.  
	_Para instalar nodemon ejecutar_
	``` 
	    npm i -g nodemon
	    
	```
	
	Luego de tener instalado nodemon, hay que realizar un cambio en el **package.json** agregando lo siguiente en el apartado de **scripts**
	``` 
	    "server":"nodemon server.js",
	    
	```
	
	Luego para levantar el server en vez de
	``` 
	    nodeserver.js
	    
	```
	
	ejecutamos lo siguiente
	``` 
	    npm run server
	    
	```
	
	Este “server” coincide con la key que hemos agregado en el package.json en el apartado “scripts”

	* **esdraspavon** [958006] (1)

		Así es! muy buena librería! El profe lo instala unas clases más adelante.

* **Felipe Acosta** (10) [728518](https://platzi.com/comentario/728518/) 

	Insomnia me gusto mucho por que soporta graphQl, cosa que postman apenas lo tiene en beta

	* **Sebastian Cardoso Castillo** [728518] (2)

		#TeamInsomnia

* **nancygtec** (8) [912228](https://platzi.com/comentario/912228/) 

	Por si a alguien se le escapa el detalle, cuando dice “vamos a matar el servidor” lo hace con las teclas “Ctrl + C”

	* **Gabriel De Andrade (Platzi)** [912228] (1)

		Buen dato! Más cosas como estas las podemos aprender en el [Curso de Introducción a la Terminal y Línea de Comandos](https://platzi.com/clases/terminal/) 😄

* **Alejandro_** (8) [890486](https://platzi.com/comentario/890486/) 

	Les aconsejo instalar [nodemon](https://www.npmjs.com/package/nodemon) ya que reinicia de forma automatica cuando detecta cambios en nuestros archivos y así no debemos volver a ejecutar el comando “node server.js” cada vez que hagamos un cambio y unicamente seria “nodemon server.js”.

* **Alejandro Urian** (6) [726849](https://platzi.com/comentario/726849/) 

	Yo utilizo [Postman](https://www.getpostman.com/) para probar los endpoints de mi app. Lo recomiendo.

	* **Carlos Hernández** [726849] (8)

		Postman también funciona genial, buena recomendación. A mí me gusta mucho Insomnia por el soporte que tiene para GraphQL 😉

	* **Dragonatak** [726849] (1)

		Yo también utilizo Postman!! Buena oportunidad para probar una nueva aplicación!!

* **Argos98** (4) [951584](https://platzi.com/comentario/951584/) 

	en ves de insonia yo uso Postman y la verdad es muy similar y me gusta mas

* **GuillermoLoza** (4) [793934](https://platzi.com/comentario/793934/) 

	Recomiendo la extensión **Node Snippets** para VSCode

* **GuillermoLoza** (4) [786017](https://platzi.com/comentario/786017/) 
	
	![](https://i.ibb.co/f4Rk6BX/middleware.png)

* **GuillermoLoza** (3) [786016](https://platzi.com/comentario/786016/) 
	
	![](https://i.ibb.co/7zjP23y/middleware-exp.png%22)

* **LuisViGo** (2) [1019246](https://platzi.com/comentario/1019246/) 

	Que herramienta considerarían mejor, Insomnia o Postman?

	* **JerezA** [1019246] (2)

		ya es mucho de gustos, por ejemplo yo no trabajo con ninguna de esas 2, yo trabajo con SoapUI, y a todas les puedes sacar sus ventajas, ya depende de las pequeñas ventajas que ofrece cada una, como que en postman puedes utilizar el query de graphql, o en SoapUI puedes hacer una estructura de proyectos para guardar tus requests de manera mas organizada, cada una tiene lo suyo.

* **Ricardo Lugo Recillas** (2) [823867](https://platzi.com/comentario/823867/) 

	```
	    const express =  require('express');
	    const router = express.Router();
	    
	    var app = express();
	    app.use(router);
	    
	    /*
	    app.use('/', function(req, resp){
	        resp.send("hola");
	    });
	    */
	    
	    router.get("/", function(req, res){
	        res.send("peticion de get");
	      });
	    
	    router.post("/", function(req, res){
	        res.send("peticion de post");
	      });
	    
	    router.patch("/",function(req, res){
	        res.send("peticion de patch");
	      });
	    
	    router.delete("/",function(req, res){
	        res.send("peticion de delete");
	      });
	    
	    app.listen(3000);
	    console.log(" la aplication esta escuchando en el port http://localhost::3000");
	    
	```

* **GuillermoLoza** (2) [786025](https://platzi.com/comentario/786025/) 

	```
	    const express = require("express");
	    const router = express.Router();
	    
	    var app = express();
	    
	    app.use(router);
	    
	    router
	      .get("/", function(req, res){
	        res.send("Traer");
	      })
	    
	      .post("/", function(req, res){
	        res.send("Enviar");
	      })
	      .patch("/", (req, res) => {
	        res.send("Cambiar");
	      })
	      .delete("/", (req, res) => {
	        res.send("Borrar");
	      });
	    
	    app.listen(3002);
	    
	    console.log("La aplicacion esta escuchando en el puerto http://localhost:3002");
	    
	    
	```

* **Sebastián Pineda Duque** (2) [776487](https://platzi.com/comentario/776487/) 

	Igualmente, también se debió explicar qué es el parámetro _“/”_. Pésimo todo, no pueden dar por sentado de que el estudiante sabe estas cosas.

* **marpico** (2) [763906](https://platzi.com/comentario/763906/) 

	Hola, Que ventaja da usar express.Router()??  
	router.get(’/’ (req, res)=> res.send(‘Hola desde get’))  
	sobre  
	app.get(’/’ (req, res)=> res.send(‘Hola desde get’))  
	Saludos!!

	* **lizardojara** [763906] (3)

		Parece ser mas un tema de modularizacion de la aplicación, y tener las rutas agrupadas en otro archivo.

* **Wilson Castro Medellin** (1) [1115173](https://platzi.com/comentario/1115173/) 

	Insomnia es similar a posman?

	* **Pablo Mariano Gonzalez Ocon** [1115173] (1)

		asi es

* **Blacjk** (1) [1062098](https://platzi.com/comentario/1062098/) 

	```
	    //en consola se debe instalar el paquete de express con el siguiente comando
	    //npm i express
	    //una vez instalado debemos asignar a una constante el paquete instalado
	    const express = require("express");
	    var app = express();
	    //añadiremos router de express para poder utilizar los metodos http y controlar los mensajes a entregar en nuestras peticiones
	    const router = express.Router();
	    
	    // app.use("/", function(req, res) {
	    //     res.send("Hola soy un server con express");
	    // });
	    
	    //ahora indicamos que nuestra app utilizara las rutas entregadas por express
	    app.use(router);
	    //de esta forma podemos invocar los distintos metodos http con express
	    router.get("/mensaje", (req, res) => {
	        res.send("Hola este metodo es get para listar los mensajes");
	    });
	    router.post("/mensaje", (req, res) => {
	        res.send("hola este metodo invocado es post, gracias por añadir un mensaje");
	    });
	    
	    app.listen(3002);
	    console.log("la aplicacion esta escuchando en http://localhost:3002");
	    
	```

* **carlosextra1** (1) [1056239](https://platzi.com/comentario/1056239/) 

	This is my code
	``` 
	    const express = require('express');
	    const router = express.Router();
	    
	    varapp =  express();
	    
	    app.use(router);
	    
	    app.get('/', (req, res) => {
	        res.send('Que ondas Soy tu primer petición con GET');
	    });
	    app.post('/', (req, res) => {
	        res.send('Que ondas Soy tu primer petición con POST');
	    });
	    app.listen(3000);
	    console.log('La aplicación esta escuchando en pueto:3000');
	    
	```
	
	[](https://www.carlosramirezflores.com/)

* **ksanchez_cld** (1) [1021007](https://platzi.com/comentario/1021007/) 

	<https://itnext.io/postman-vs-insomnia-comparing-the-api-testing-tools-4f12099275c1>

* **OrNano** (1) [1000314](https://platzi.com/comentario/1000314/) 

	Insomnia buena herramienta para ser usada en linux 😃

* **j.santos** (1) [983420](https://platzi.com/comentario/983420/) 

	Excelente clase !

* **israelhuaman** (1) [952528](https://platzi.com/comentario/952528/) 

	fue super facil , me encanta

* **MaicolQJ** (1) [910710](https://platzi.com/comentario/910710/) 

	si quieren no estar parando y arrancando el sistema todo el tiempo, instalar npm install -g nodemon para que se guarde automáticamente

	* **jonathan2138** [910710] (1)

		A mi no me funcionó,me tocó volver a parar el servidor para que cogiera los cambios

	* **jonathan2138** [910710] (1)

		Tocaba iniciar ahora con nodemon server :S Gracias por la guia

* **Johan Manuel Perez Soto** (1) [877990](https://platzi.com/comentario/877990/) 

	Esta chido el cliente RES

* **wanda-peruzzo** (1) [854906](https://platzi.com/comentario/854906/) 

	como mata el servidor para volver a arrancarlo? es una combinacion de teclas?

	* **Juan Carlos Rodríguez Amézquita** [854906] (2)

		Ctrl + C

	* **Gabriel De Andrade (Platzi)** [854906] (4)

		Ctrl + C te sirve para matar cualquier comando en la terminal, te invito a que cheques el [Curso de Terminal y Línea de Comandos](https://platzi.com/clases/terminal/), está buenísimo 😄

* **JaimeRamos** (1) [761754](https://platzi.com/comentario/761754/) 

	excelente clase, llevo ya algunos meses usando node-express y nunca había usado router.

* **AlejoE02** (1) [754901](https://platzi.com/comentario/754901/) 

	Yo utilizo ARC (Advanced REST Client) para hacer el seguimiento a las peticiones

	* **lizardojara** [754901] (2)

		Yo prefiero postman, tiene multitud de opciones y recuerda las peticiones hechas anteriormente.

* **José Tomás Villalba** (1) [73237](https://platzi.com/comentario/830876/) 
npm WARN deprecated fsevents@1.2.9: One of your dependencies needs to upgrade to fsevents v2: 1) Proper nodejs v10+ support 2) No more fe...

* **johneduardo** (1) [71866](https://platzi.com/comentario/805219/) 
¿Cómo puedo ver lo que me retorna el valor de ‘req’ en la función: app.use('/', (req, res)=>{ res.send('Bueas'); }) ...

	* **Juan David Castro (Platzi)** [71866] (2)

		Puedes ver todas las propiedades que entrega el objeto **`req`** desde la documentación oficial:
		
		👉 <https://expressjs.com/es/4x/api.html#req>
		
		Ya si quieres ver el resultado desde tu aplicación puedes hacer **`console.log`** directamente de las propiedades del objeto **`req`**.
		
		Por ejemplo: **`console.log(req.params.patito, req.baseUrl, req.cookies.espia)`**.

* **Gabriel Andreí Barceló Alfaro** (1) [69518](https://platzi.com/comentario/758387/) 
Disculpen ¿el servidor (server.js) dónde se pone en la nube para que no esté corriendo en mi máquina local?

	* **Juan David Castro (Platzi)** [69518] (1)

		Cuando mandes tu aplicación a producción, sí. Pero mientras estás desarrollando puedes hacerlo desde tu computadora. 😉

* **Sebastián Pineda Duque** (0) [776483](https://platzi.com/comentario/776483/) 

	Se debió explicar qué son los parámetros _req_ y _res_. Si sí lo hicieron y yo no lo vi, por favor indíquenlo.

	* **lizardojara** [776483] (1)

		Creo que el capitulo anterior lo dijo, pero de manera superflua, hace falta detallar un poco mas.

	* **mafevito** [776483] (2)

		Hola
		
		Los parámetros **req** y **res** forman parte de una función HTTP.
		
		**req** es el acrónimo de **request** , que significa solicitud, contiene toda la información de la solicitud, incluidos los paramétros de la solicitud, los encabezados, el cuerpo de la solicitud y más.
		
		**res** es el acrónimo de **response** , que significa respuesta, contiene la respuesta a la solicitud.
		
		En [esta clase ](https://platzi.com/clases/1689-backend-js/22608-que-son-y-como-se-usan-las-peticiones-http/) se habla acerca de que son y como funcionan las peticiones HTTP.

* **José Tomás Villalba** (0) [73229](https://platzi.com/comentario/830794/) 
¿Cuál es el comando para poder escribir nuevamente en la consola? ^C (para Mac)

	* **Kevin Javier Morales (Platzi)** [73229] (1)

		Cmnd + C

## 0080. Recibir información desde el cliente Body y Query [22630](https://platzi.com/clases/1689-backend-js/22630-recibir-informacion-desde-el-cliente-body-y-query/)

### Descripción:


En esta clase instalaremos `nodemon` para que cada vez que haya un cambio en nuestro proyecto se reinicie el servidor.

### Comentarios:

* **durbonca** (17) [834666](https://platzi.com/comentario/834666/) 

	A mi me estuvo pasando el JSON como undefined. En caso de que a alguien le pase es posible que tengan el app.use(router) adelante del app.use(bodyparser.json())
	
	Según lei el enrutador debe de ir al final de todo

	* **Jesús Miguel Moreno Plasencia** [834666] (1)

		buen amigo, pensé que me estaba confundiendo en algo, tu comentario ah sido de mucha ayuda, buenas vibras

	* **edwintrumpet** [834666] (3)

		No es que tenga que ir al final de todo, sino que son middlewares que express usa en orden, si pone el router antes de parsear entonces irá a las rutas primero y todavía no tendrá definido el body.  
		Pero en alguno casos hay middlewares que van después de las rutas como los middlewares que manejan errores, en ese caso primero entran a las rutas y si hay errores entonces entran al siguiente middleware.

* **SistemasCBC** (10) [859962](https://platzi.com/comentario/859962/) 

	En mi caso para levantar el servidor con nodemon tuve que utilizar npx:
	``` 
	    npx nodemon server.js
	    
	```

	* **Renzo Carpio Ponce** [859962] (2)

		Gracias por el dato me ayudo mucho

* **lizardojara** (8) [833592](https://platzi.com/comentario/833592/) 

	Si alguien usa postman, es la opción de BODY > raw y de ahi seleccionan JSON(application/json)

* **alejandromarcano** (8) [725778](https://platzi.com/comentario/725778/) 

	Podemos ver el código en cada uno de los lenguajes de como envía insomnia la petición:
	
	![generate code.JPG](https://static.platzi.com/media/user_upload/generate%20code-aaeb6ad9-be8b-4761-a9dc-4904182a155f.jpg) ![generate code js.JPG](https://static.platzi.com/media/user_upload/generate%20code%20js-2d8de903-df7b-4101-94a6-193fedb5b07f.jpg)

* **ing.stephanysc** (7) [992747](https://platzi.com/comentario/992747/) 

	Si alguno en Windows 10 no puede ejecutar scritps debe usar :  
	Set-ExecutionPolicy -Scope CurrentUser Unrestricted
	
	asi te da permisos para usar el comando:
	
	nodemon server

	* **Nick1125** [992747] (1)

		Aque viene este problema???

* **Francisco Javier Vázquez Paredes** (7) [732831](https://platzi.com/comentario/732831/) 

	Una manera mas condensada de definir los diferentes métodos HTTP para una misma ruta puede expresarse de la siguiente manera:
	``` 
	    router.route("/")
	    .all((request, response, next) => {
	       //Puede funcionar como middleware
	        console.log("Accedo a la ruta /")
	        next()
	    })
	    .get((request, response) => {
	        response.send("Hola desde get")
	    })
	    .post((request, response) => {
	        response.send("Hola desde post")
	    })
	    .delete((request, response) => {
	        response.send("Hola desde delete")
	    })
	    
	```

* **Alejandro Barba** (6) [951137](https://platzi.com/comentario/951137/) 

	Como dato curioso:  
	No es necesario instalar BODYPARSER para poder recibir mensajes tipo JSON o hacer uso de URLENCODED ya que body-parser viene instalado en express.  
	[Link de explicación aquí](https://stackoverflow.com/questions/54660316/do-body-parser-json-and-urlencoded-functions-replace-express-json-and-urle)

	* **gabino18** [951137] (2)

		Según tengo entendido en las últimas versiones de express no viene más incluido y hay que volver a instalarlo por serpado como se hacia antes y como lo está haciendo Carlos.

	* **Alejandro Barba** [951137] (1)
![Screenshot_2020-01-31_13-01-08.png](https://static.platzi.com/media/user_upload/Screenshot_2020-01-31_13-01-08-3dbea905-adbb-47fe-a810-3fc09f83f386.jpg)
		
		Lo estoy usando en un proyecto actual y funciona, al final es lo mismo jaja

	* **jandrey** [951137] (1)

		Si es verdad en la version 4 de express ay que volver a instalar body-parser <https://expressjs.com/es/guide/migrating-4.html>

* **Alan Alexis Arostegui Maranto** (6) [902519](https://platzi.com/comentario/902519/) 

	Express ya incluye bodyParser en su módulo asi que ya no es necesario instalarlo. recuerden que express.Router funciona como un [middleware](https://medium.com/@aarnlpezsosa/middleware-en-express-js-5ef947d668b) que tiene las rutas y por eso es necesario que el codigo vaya antes de este middleware.
	``` 
	    const express = require('express');
	    const router = express.Router();
	    
	    const app = express();
	    
	    app.use(express.json());
	    app.use(express.urlencoded({ extended: false }))
	    app.use(router);
	    
	    router.get('/', (req,res) => {
	        res.send('Lista de mensajes (hola desde get)');
	    });
	    
	    router.post('/', (req,res) => {
	        console.log(req.body);
	        console.log(req.query);
	        res.send(`Mensaje añadido (${req.body.text} desde post)`);
	    });
	    
	    router.put('/', (req,res) => {
	        res.send('Mensaje editado (Hola desde put)');
	    });
	    
	    router.patch('/', (req,res) => {
	        res.send('Mensaje editado (Hola desde patch)');
	    });
	    
	    router.delete('/', (req,res) => {
	        res.send('Mensaje borrado (Hola desde delete)');
	    });
	    
	    app.listen(3000, () => {
	        console.log('Telegram listening on port 3000')
	    });```
	    
	    
	```

	* **raparisg** [902519] (1)

		Buen aporte! Cabe mencionar que esto es así desde la versión 4.16.0 de express. Más info en esta respuesta de Stackoverflow: <https://stackoverflow.com/questions/47232187/express-json-vs-bodyparser-json/47232318#47232318>

* **Johan Manuel Perez Soto** (6) [878009](https://platzi.com/comentario/878009/) 

	Actualmente ya bodyparser viene en express, so  
	podríamos utilizarlo de la siguiente manera…
	``` 
	    const express = require('express');
	    const app = express();
	    app.use(express.json());
	    app.use(express.urlencoded({extended : false}));
	    
	```

* **jbarriospd** (5) [755492](https://platzi.com/comentario/755492/) 

	Hola a todos: Tengo el siguente error cuando paso el body por url
	``` 
	    [Object: null prototype] { text: 'hola' }
	    
	```
	
	Pero cuando paso el valor del extend en true si aparece normal ¿Alguna idea de porque en false no me funciona?
	
	Paso mi código:
	``` 
	    const express = require('express');
	    const bodyParser = require('body-parser');
	    const router = express.Router();
	    
	    var app = express();
	    app.use(bodyParser.json());
	    app.use(bodyParser.urlencoded({extended: false}));
	    app.use(router);
	    
	    router.get('/message', function(req,res){
	    
	        res.send('This message is geted');
	    })
	    
	    router.delete('/message', function(req,res){
	    
	    
	        console.log(req.body)
	        res.send('This message is deleted');
	    
	    
	    })
	    
	    app.listen(3000)
	    
	```

	* **Rocio Calderon Hernandez** [755492] (1)

		A mi me pasa igual, me sale en true… ¿ por que? NI idea…

	* **Jose Luis Campos Bautista** [755492] (3)

		Me paso lo mismo, solo valide que contentent type en los headers sea el correcto: **application/x-www-form-urlencoded** , **application/json**.
		
		Con respecto al **extended** de bodyParser es para poder enviar objetos anidados, por ejemplo si **extended** es true y envías el siguiente valor `person[name] = 'Jose Luis'` del lado del servidor lo recibirás como `{"person":{"name":"Demo"}}`.
		
		Si el valor de **extended** es false recibirás el siguiente valor `{"person[name]":"Demo"}`.

	* **edwintrumpet** [755492] (2)

		Creo que no es un error, está leyendo el body perfectamente.  
		Creo que está indicando que el objeto no tiene un prototipo, es decir que no desciende de otro objeto de javascript

	* **Ildebrando Mora Valdes** [755492] (1)

		`{ extended: true }`

	* **Ramiro Nicolas D'Accorso Rosati** [755492] (1)

		¿Algun profe podrá guiarnos?

* **Juan mora** (4) [733825](https://platzi.com/comentario/733825/) 

	Aclarando dudas clase a clase, GRACIAS!!!

* **Cristian Raul Tapia Burgos** (4) [723870](https://platzi.com/comentario/723870/) 

	tengo hecho todo igual hasta el min. 6 aprox. pero en la consola me sale undefined

	* **Edward Orlando Hurtado** [723870] (4)

		Tienes que estar seguro que en tu POSTMAN o INSOMNIA estes pasando el valor de text como valor json, si no lo pasas como valor json te retornara undefined como valor

	* **danhergir** [723870] (15)

		Verifica que estés llamando primero al bodyParser y no al router, de tal forma que lo tengas de la siguiente manera:
		``` 
		    app.use(bodyParser.json());
		    app.use(router);
		    
		    
		```

	* **alejandromarcano** [723870] (4)

		Revisa lo que dice danhergir… El orden es importante en este caso

	* **Dragonatak** [723870] (1)

		Gracias **@danhergir** … Me pasaba exactamente lo mismo!!!

* **dmdiazf** (3) [1059899](https://platzi.com/comentario/1059899/) 

	Siempre que muestro el contenido de la cabecera en el método POST del modo console.log(req.body) me muestra “undefined”. No he podido lograr ver la cabecera del metodo POST.

	* **José María Cuevas Ramírez** [1059899] (4)

		Tuve el mismo problema, lo solucioné cambiando el orden de los “app.use()”
		
		![Captura de Pantalla 2020-03-25 a la\(s\) 21.20.35.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202020-03-25%20a%20la%28s%29%2021.20.35-31f5a34e-9c34-43e2-b19f-cbef80d3918b.jpg)

* **edwintrumpet** (3) [853969](https://platzi.com/comentario/853969/) 

	Tengo entendido que el body-parser ya viene incluido en express, no es necesario instalarlo.  
	Se puede usar como:
	``` 
	    app.use(express.json());
	    app.use(express.urlencoded({ extended: false }))
	    
	```
	
	Y siempre debe ponerse antes de usar el middleware de rutas porque los middlewares se usan en orden y si no está parseado el body antes de llegar a las rutas aparecerá como indefinido.

* **Nestor David Alvarado Rondon** (3) [729778](https://platzi.com/comentario/729778/) 

	Hola, tambien se puede añadir el mensaje de esta forma
	``` 
	    res.send(`Mensaje ${req.body.text} eliminado correctamente`);
	    
	```

* **Ricardo Lugo Recillas** (2) [823888](https://platzi.com/comentario/823888/) 

	```
	    const express =  require('express');
	    const bodyParser = require('body-parser');
	    const router = express.Router();
	    
	    var app = express();
	    app.use(bodyParser.json());
	    app.use(bodyParser.urlencoded({extended: false}));
	    app.use(router);
	    
	    router.get("/", function(req, res){
	        res.send("peticion de get");
	      });
	    
	    router.post("/", function(req, res){
	        res.send("peticion de post");
	      });
	    
	    router.patch("/",function(req, res){
	        res.send("peticion de patch");
	      });
	    
	    router.delete("/",function(req, res){
	        res.send("peticion de delete");
	      });
	    
	    app.listen(3000);
	    console.log(" la aplication esta escuchando en el port http://localhost::3000");
	    
	```

* **Jorge Enríquez** (2) [804152](https://platzi.com/comentario/804152/) 

	¿Alguien está trabajando con Postman en lugar de con Insomnia? Postman es el que conocía de antes y lo estoy probando pero parece ser que me falta algo a la hora de mandar la info como JSON, si que me salta el console y/o el res.send del router.post, pero tanto req.query como req.body me aparecen vacías, no consigo que se vean los valores que le paso (y los headers están como application/json).
	
	¿Algún consejo?

	* **santidalmasso** [804152] (3)

		Para enviar JSON en Postman tenes que ir a la pestaña **Body** , seleccionar **raw** y a la derecha (después de GraphQL) cambiar el tipo Text por JSON. 😉

* **Jose Rodriguez Luis** (2) [739233](https://platzi.com/comentario/739233/) 

	excelente explicación, gracias!!

* **ANDDY JOSUE ANDRADE BERRONES** (1) [1118161](https://platzi.com/comentario/1118161/) 

	al ejectuar nodeman server , me dice que la ejecucion de scripts esta desabilitada alguien sabe como puedo solucionar eso ?

	* **Yiy0** [1118161] (1)

		Nodemon querrás decir?

* **Rabi Leonel Leon Chan** (1) [1081345](https://platzi.com/comentario/1081345/) 

	Excelente Clase

* **carlosextra1** (1) [1059201](https://platzi.com/comentario/1059201/) 

	nodemon se usa en el curso de fundamentos de nodejs

* **jiduartem** (1) [913036](https://platzi.com/comentario/913036/) 

	 **Estupenda clase!** la recomiendo

* **jiduartem** (1) [913023](https://platzi.com/comentario/913023/) 

	Muy bueno, entonces:
	``` 
	    // Instalar
	    sudo npm install -g nodemon
	    
	    // Ejecutar
	     nodemon archivo.js
	    
	```

* **johan.n** (1) [909017](https://platzi.com/comentario/909017/) 

	yo no podía instalar nodemon pero con este comando ya pude
	``` 
	    npm install -g nodemon
	    
	```

	* **MaicolQJ** [909017] (2)

		claro que no te funcionaba porque **sudo ** es para Apple, para windows no se usa

	* **Juan José Vega Quintero** [909017] (1)

		La verdad no es para apple, es para terminales que unix

* **FabianIgnacio** (1) [887950](https://platzi.com/comentario/887950/) 

	Genial super claro ! !

* **José Tomás Villalba** (1) [830878](https://platzi.com/comentario/830878/) 

	npm WARN deprecated fsevents@1.2.9: One of your dependencies needs to upgrade to fsevents v2: 1) Proper nodejs v10+ support 2) No more fetching binaries from AWS, smal  
	ler package size  
	/Users/tom/.npm-global/bin/nodemon -> /Users/tom/.npm-global/lib/node_modules/nodemon/bin/nodemon.js

	* **omnicanaljamar** [830878] (1)

		debes poner tu app.use(router);  
		debajo de " app.use(bodyParser.json()) "

* **Wilson Castro Medellin** (1) [87206](https://platzi.com/comentario/1115206/) 
Cuando acceder por query y cuando acceder por body a los parametros?

	* **Anibal Fernando Ortega Piedrahita** [87206] (1)

		Eso depende de lo sensible que sea la información. ya que por query la información viaja en la URL lo que la hace visible a la vista del usuario. Un ejemplo es no enviar contraseñas por query.

* **johan.n** (1) [77745](https://platzi.com/comentario/909011/) 
Alguien sabe como solucionar esto? Me dice que -> El término ‘sudo’ no se reconoce como nombre de un cmdlet o que me falta ruta de acc...

	* **Ruben Padilla** [77745] (1)

		Hey!
		
		Te recomiendo esta clase [Instalación de Ubuntu Bash en Windows](https://platzi.com/clases/1650-prework/22995-instalacion-de-ubuntu-bash-en-windows/)

* **matcop** (1) [77625](https://platzi.com/comentario/907010/) 
el error que sale es> npm ERR! code EAI_AGAIN npm ERR! errno EAI_AGAIN npm ERR! request to 

	* **Juan David Castro (Platzi)** [77625] (1)

		¡Hola!
		
		¿Eso es todo el error que te muestra la consola? El mensaje es muy general y no nos parece indicarnos ninguna posible solución.
		
		También puedes probar actualizando Node.js y NPM.

* **francisco-lopez-zetina** (1) [76469](https://platzi.com/comentario/887709/) 
al llegar a colocar el comando sudo npm install -g nodemon me dispara un error, ![](D:\descargas\WhatsApp Image 2019-12-...

	* **Juan David Castro (Platzi)** [76469] (1)

		No te cargó la imagen. Intenta arrastrarla del explorador de archivos al editor de comentarios. 😉

* **Alejo Goncalves** (1) [73776](https://platzi.com/comentario/841143/) 
const express = require('express'); const bodyParser = require('body-parser'); const router = express.Router(); var app = express...

* **Alejo Goncalves** (1) [73775](https://platzi.com/comentario/841142/) 
no entiendo porque cuando le doy a ‘send’, en la consola no me aparece el mensaje de ‘Hola’ const express = require('express'); con...

	* **Ruben Padilla** [73775] (1)

		👋  
		Parece ser por el metodo que estas usando.  
		Si quieres mostrar el body del request en la consola debes usar el metodo post y hacer la prueba en postman enviando un json.
		``` 
		    const express = require('express');
		    const bodyParser = require('body-parser');
		    const router = express.Router();
		    
		    constapp = express();
		    app.use(bodyParser.json());
		    app.use(router);
		    
		    router.post('/message', function(req, res) {
		      console.log(req.body);
		      res.send('Usando post para enviar un request y ver el contenido enla consola');
		    });
		    
		    app.listen(3000);
		    console.log('Laapp esta siendo escuchada en http://localhost:3000');
		    
		    
		```
		
		It works!
		
		Ahora desde postman haces la request.
		``` 
		    // Recuerda en formato json, si se hace en texto plano no funcionara.
		    {
		    	"message": "hola"
		    }
		    
		```
		
		Saludos

* **baen20** (1) [68708](https://platzi.com/comentario/744509/) 
¿Porque al instalar los packages no utilizamos --save?

	* **Demian Arenas (Platzi)** [68708] (5)

		Hola baen20, este fue uno de los cambios que tuvo [npm en la versión 5.0.0](https://blog.npmjs.org/post/161081169345/v500), por defecto realiza el `--save`.

* **Rachid Moyse Polania** (1) [68686](https://platzi.com/comentario/744298/) 
Hola, cuando paso los datos por URLENCODED, me llegan en undefined, pero la query si me llega.

	* **Demian Arenas (Platzi)** [68686] (4)

		Hola Rachid, tal vez podría ser que tengas un typo, si puedes comenta aquí tu código para entender un poco más sobre el problema y poder ayudarte mejor.

* **matcop** (0) [77619](https://platzi.com/comentario/906961/) 
tengo un problema al tratar de instalar nodemos, talvez alguien sabe de esto ![](C:\Users\Personal\Pictures\PRINTS DE PANTALLA\2020-01-07...

	* **Alvaro Garracini** [77619] (1)

		Hola.
		
		La imagen no quedó bien subida, ¿puedes cargarla nuevamente para que se pueda ver el error?

* **joan-rincon-sarmiento** (0) [73046](https://platzi.com/comentario/827291/) 
Cuando envio body la consola no me muestra el mensaje, solo aparece undefined, este es mi codigo: const express = require('express'...

	* **Favio Náquira** [73046] (2)

		Intenta imprimiendo todo el req, parecerá monstruoso pero de repente lo estás enviando en otro lado (query por ejemplo)
		``` 
		    console.log(req)
		    
		```

## 0090. Información contextual Leer las cabeceras [22631](https://platzi.com/clases/1689-backend-js/22631-informacion-contextual-leer-las-cabeceras/)

### Descripción:


### Comentarios:

* **Johan Manuel Perez Soto** (6) [878214](https://platzi.com/comentario/878214/) 

	Node me ha abierto muchas puertas…

* **Duvan Carvajal** (4) [742204](https://platzi.com/comentario/742204/) 

	Cada vez me enamoro más de este curso.

* **Johan Manuel Perez Soto** (4) [737187](https://platzi.com/comentario/737187/) 

	Bueno, este es mi punto de vista (favor decirme si estoy equivocado en algo) pero hasta donde tengo entendido node js por si solo nos permite ejecutar JavaScript en un entorno diferente al navegador y pues express nos permite utilizar las node como back-end.

	* **Hafnio** [737187] (3)

		Exactamente. Node.js se define a si mismo como un runtime de javascript al que uno le instala paquetes para poder realizar aplicaciones de cualquier tipo (como express o electron). Aunque tecnicamente existen varios engine para correr javascript, node usa el V8 de google.

	* **Carlos Hernández** [737187] (12)

		Node tiene en su core un módulo HTTP (así se llama) que puede ejecutar servidores. Sin embargo, usarlo para hacer cosas mas complejas que un simple endpoint es un poco farragoso.  
		.  
		Ahí es donde aparece express, que añade una capa intermedia entre el desarrollador y el modulo http nativo de Node, haciendo el trabajo de crear servidores complejos muchísimo más sencillo.

* **Carlos Alex Becerra Chavita** (4) [728130](https://platzi.com/comentario/728130/) 

	Super interesante el curso

* **nancygtec** (3) [912789](https://platzi.com/comentario/912789/) 

	Excelente Profesor

* **j.santos** (2) [985762](https://platzi.com/comentario/985762/) 

	Excelente, la parte de cabeceras personalizadas.

* **Fernando Cordero** (2) [826976](https://platzi.com/comentario/826976/) 

	```
	    const express = require('express')
	    const bodyParser = require('body-parser')
	    const router = express.Router() //nos permite separar cabeceras, metodos, url
	    
	    var app = express()
	    app.use(bodyParser.json()) // agregamos json para que acepte las peticiones de ese tipo, asi como urlencoded
	    app.use(bodyParser.urlencoded({extended: false}))
	    app.use(router)
	    
	    router.get('/message', function(req, res) {
	        console.log(req.headers)
	        res.header({
	            "custom-header": "Nuestro valor predeterminado"
	        })
	        res.send('Lista de mesajes añadido correctamente')
	    })
	    
	    router.post('/message', function(req, res) {
	        console.log(req.body)
	        console.log(req.query)
	        res.send('Mensaje ' + req.body.text + ' añadido')
	    })
	    
	    router.delete('/message', function(req, res) {
	        res.send('Mensaje eliminado')
	    })
	    
	    app.listen(3000)
	    console.log('La app esta escuchando en http://localhost:3000')```
	    
	```

* **Luis Fernández** (2) [826182](https://platzi.com/comentario/826182/) 

	Así si se explica Nodejs…!
	
	Esta Genial el Curso

* **Houses** (2) [786222](https://platzi.com/comentario/786222/) 

	Está excelente el curso

	* **María José Ledesma (Platzi)** [786222] (1)

		¡Nos alegra que te haya gustado, Houses! ¿Qué fue lo que más te gustó hasta el momento?
		
		**¡Nunca pares de aprender!** (Y practicar) 🦄

* **Wilver Martinez** (2) [768131](https://platzi.com/comentario/768131/) 

	Que excelente curso!! Cada vez me gusta mas NodeJS, vengo del mundo de spring boot y nos tardamos mas en configurar el proyecto que en desarrollar las API’s, veo que con nodeJS es mas sencillo arrancar un proyecto desde cero.

	* **Hafnio** [768131] (1)

		Exacto, es increible lo dificil que hace Java para cosas que deberian ser rapidas. Que bueno que hay lenguajes como JavaScript, Python o Go que lo que les importa es que desarrolles y punto. La complejidad deberia agregarsela el programador no el lenguaje

* **john jairo lopez ramirez** (2) [750833](https://platzi.com/comentario/750833/) 

	Excelente este curso, es increible la forma tan suave que lo lleva a uno el profesor, para las personas que hasta ahora estamos iniciando en esto es demasiado útil

	* **Dragonatak** [750833] (1)

		Así es!!! Carlos está explicando todo de una manera muy sencilla mientras te lo va mostrando paso a paso!!!

* **Wilson Castro Medellin** (1) [1115228](https://platzi.com/comentario/1115228/) 

	Cabecera. Saber de donde viene la petición

* **carlosextra1** (1) [1059270](https://platzi.com/comentario/1059270/) 

	This is my code!
	``` 
	    const express = require('express');
	    const bodyParser = require('body-parser');
	    const router = express.Router();
	    
	    varapp =  express();
	    
	    app.use(bodyParser.json());
	    app.use(bodyParser.urlencoded({extended: false }));
	    app.use(router);
	    
	    app.get('/headers', (req, res) => {
	        console.table(req.headers)
	        res.header({
	            'custom-header' : 'Valore personalizado para el cliente'
	        })
	        res.send(req.headers);
	    });
	    app.post('/pruebas', (req, res) => {
	        console.log(req.query);
	        console.log(req.body);
	        res.send('Datos regresados '+ req.body.text +' correctamente');
	    });
	    app.post('/', (req, res) => {
	        res.send('Que ondas Soy tu primer petición con POST');
	    });
	    app.listen(3000);
	    console.log('La aplicación esta escuchando en pueto:3000');```
	    
	```

* **daulisg** (1) [1001070](https://platzi.com/comentario/1001070/) 

	Me encanta este curso

	* **María José Ledesma (Platzi)** [1001070] (1)

		 **¡Nunca pares de aprender!** 🦄

* **Kevin Jeremy Salazar Jimenez** (1) [995760](https://platzi.com/comentario/995760/) 

	muy bien!

* **ehnbytes** (1) [971664](https://platzi.com/comentario/971664/) 

	Excelente profesor, había visto tutoriales de nodeJS pero nada como este curso, es de lo mejor que he encontrado!!

* **edwintrumpet** (1) [854057](https://platzi.com/comentario/854057/) 

	Cache-Control también se puede fijar así:  
	Por ejemplo para indicarle que guarde la respuesta en caché por 300 segundos
	``` 
	    res.set("Cache-Control", "public, max-age=300")
	    
	```

* **pro_cristancho** (1) [766115](https://platzi.com/comentario/766115/) 

	Una clase excelente

* **Alan Dega** (1) [757053](https://platzi.com/comentario/757053/) 

	excelente inicio

## 0100. Tipos de respuesta Vacía, plana, con datos y estructurada [22614](https://platzi.com/clases/1689-backend-js/22614-tipos-de-respuesta-vacia-plana-con-datos-y-estruct/)

### Descripción:


### Comentarios:

* **Johan Manuel Perez Soto** (8) [878233](https://platzi.com/comentario/878233/) 

	Con cada paso estoy mas cerca del Mern Stack 😎😎

* **alexagomezh** (5) [986876](https://platzi.com/comentario/986876/) 

	Muy bien explicado Carlos, para los que estamos de cero con NODE JS esta genial. Gracias 😃

* **Nestor David Alvarado Rondon** (4) [729807](https://platzi.com/comentario/729807/) 

	No estoy seguro, pero dividí mi proyecto de la siguiente manera:
	``` 
	    - /admin
	    	-/routes
	    		adminRoutes.js
	    - /node_modules
	    package-lock.json
	    package.json
	    server.js
	    
	    
	```
	
	Y el código quedo así
	``` 
	    <server.js />
	    
	    const adminRoutes = require('./admin/routes/adminRoutes');
	    
	    adminRoutes.listen(3000);
	    console.log('Todo OK')
	    
	    <adminRoutes.js />
	    const express = require('express');
	    const bodyParser = require('body-parser');
	    const router = express.Router();
	    
	    var adminRoutes = express();
	    adminRoutes.use(bodyParser.json());
	    adminRoutes.use(router);
	    
	    
	    router.get('/message', function(req, res){
	        console.log(req.headers);
	        res.header({
	            'prueba': 'prueba'
	        });
	        res.send('Lista de mensajes');
	    });
	    
	    router.delete('/message', function(req, res){
	        console.log(req.query);
	        console.log(req.body);
	        res.send(`Mensaje ${req.body.text} eliminado correctamente`);
	    });
	    
	    
	    module.exports = adminRoutes;
	    
	```
	
	Si alguien lee esto, me podrían decir que tal esta?

	* **Carlos Hernández** [729807] (10)

		Al hacerlo así, lo que estás haciendo es aeparar físicamente los endpoints de admin de los endpoints de usuario.  
		.  
		Está arquitectura es interesante si las aplicaciones van a llevar desarrollos independientes. Ten en cuenta que, al hacer esto, tendrás que levantar dos procesos independientes: Uno para Admin, y otro para Usuario.  
		.  
		Más adelante en el curso, vemos como separar en componentes la aplicación para poder tener archivos más pequeños y mejor organizados. Si mantienes esta estructura, te recomiendo que apliques en cada carpeta (admin y user) la arquitectura de componentes que veremos 😉

* **Wilson Castro Medellin** (1) [1115373](https://platzi.com/comentario/1115373/) 

	Tipos de respuesta! interesante concepto

* **carlosextra1** (1) [1059291](https://platzi.com/comentario/1059291/) 

	Mi código!
	``` 
	    const express = require('express');
	    const bodyParser = require('body-parser');
	    const router = express.Router();
	    
	    var app =  express();
	    
	    app.use(bodyParser.json());
	    app.use(bodyParser.urlencoded({extended: false }));
	    app.use(router);
	    
	    app.get('/headers', (req, res) => {
	        console.table(req.headers)
	        res.header({
	            'custom-header' : 'Valore personalizado para el cliente'
	        })
	        res.send(req.headers);
	    });
	    app.post('/pruebas', (req, res) => {
	        console.log(req.query);
	        console.log(req.body);
	        res.send('Datos regresados '+ req.body.text +' correctamente');
	    });
	    app.post('/', (req, res) => {
	        res.send('Que ondas Soy tu primer petición con POST');
	    });
	    
	    app.delete('/delete', (req, res) => {
	        console.log(req.query);
	        console.log(req.body);
	        res.status(200).send([{
	            'error': null,
	            'body': 'Ejecutado correctamente!'
	         }]);
	    });
	    app.listen(3000);
	    console.log('La aplicación esta escuchando en pueto:3000');
	    
	```

* **alexibarra11** (1) [1006531](https://platzi.com/comentario/1006531/) 

	Este curso es excelente

* **Ricardo Lugo Recillas** (1) [824332](https://platzi.com/comentario/824332/) 

	Cuando se accede a un servicio que en realidad no va a retornar nada, se puede retornar un status al igual que un objeto un array o texto plano.
	``` 
	    res.status(2000).sed(AQUIVAELOBJETO, ARRAYOTEXTOPLANO);
	    
	```

	* **José Tomás Villalba** [824332] (2)

		¿“2000”?

	* **lizardojara** [824332] (4)

		Es status 200 y send

## 0110. Respuestas coherentes [22615](https://platzi.com/clases/1689-backend-js/22615-respuestas-coherentes/)

### Descripción:


### Comentarios:

* **jiduartem** (10) [913355](https://platzi.com/comentario/913355/) 

	La verdad, es uno de los profesores que se le entiende perfectamente. Se disfruta la clase!

* **Iván Darío Sánchez Jiménez** (6) [999654](https://platzi.com/comentario/999654/) 

	Profesor Carlos Hernandez ahora hace parte de mi stack de grandes profesores de Platzi, creo que este curso deja muy claro el potencial y uso de nodeJS con Express.

* **Gtiseira** (6) [848121](https://platzi.com/comentario/848121/) 

	La verdad que estos son mis primeros pasos con el backend. Y me resulta super desafiante y asimilando los conceptos nuevos, pero sobre todo ayuda mucho el tener un profe tan claro con las ideas y conceptos. 5/5

* **charly300_fede** (6) [758018](https://platzi.com/comentario/758018/) 

	Otra forma de setear el valor by default de la variable “status” es hacerlo directamente en los parámetros de la función
	``` 
	    exports.success = function(req, res, message, status = 200) {
	        res
	            .status(status)
	            .send({ message: message })
	    }
	    
	```

	* **gorydev** [758018] (2)

		cabe destacar que de esa forma el válor de status será 200 por defecto cuando no reciba otro diferente por parámetros

* **reignover** (5) [749252](https://platzi.com/comentario/749252/) 

	![](![Captura de Pantalla 2019-09-22 a la\(s\) 8.18.07 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-09-22%20a%20la%28s%29%208.18.07%20p.%20m.-111fdcd8-1846-47aa-91d5-8c2040f58610.jpg)
	
	Creé este modelo para enviar mis respuestas. Realmente es una manera muy buena de enviar una respuesta estandar a nuestro cliente 😄

	* **franciscohreyes** [749252] (1)

		Excelente!!

* **alejandromarcano** (5) [725871](https://platzi.com/comentario/725871/) 

	Genial… así tenemos mayor control de las respuestas  
	Simulé el error de esta manera:
	``` 
	    router.post('/', (req,res) => 
	        req.body.status 
	        ? response.success(req.body,res,false,"Petición POST recibida con éxito")
	        : response.error(req.body,res,false,"Error en la respuesta")
	    )
	    
	```
	
	Le paso un objeto true o false llamado status

* **Andres Roberto Coello Goyes** (5) [725059](https://platzi.com/comentario/725059/) 

	woo de esta manera daremos mejores respuestas para el cliente

* **Luis Jeanpier Monserrate** (4) [880937](https://platzi.com/comentario/880937/) 

	Como dirían en mi país, este profe se ve que sabe lo que hace !!

* **j.santos** (3) [985940](https://platzi.com/comentario/985940/) 

	Excelente profesor, vale la pena el curso!

* **MartinMB** (3) [977151](https://platzi.com/comentario/977151/) 

	Muy buen profesor

* **Johan Manuel Perez Soto** (3) [878245](https://platzi.com/comentario/878245/) 

	Antes odiaba Javascript, ahora quiero utilizarlo en todos lados :v

* **Jose Luis Campos Bautista** (3) [784161](https://platzi.com/comentario/784161/) 

	Esto igual puede ayudar a definir un estándar en su API: [Standar JSON:API ](https://medium.com/@bojanmajed/standard-json-api-response-format-c6c1aabcaa6d).

* **Mariana Valencia** (2) [1021048](https://platzi.com/comentario/1021048/) 

	Estoy amando este curso. Mis anteriores acercamientos a Node no habían salido bien

* **Arlex Felipe Llanos Betancourt** (2) [879108](https://platzi.com/comentario/879108/) 

	Es clara la forma de explicar y funcional, genial ! 😄

* **Ricardo Lugo Recillas** (2) [824383](https://platzi.com/comentario/824383/) 

	```
	    exports.success = function(req, res, message, status){
	    	res.status(status || 200).send({
	    		error: '',
	    		message: message
	    	});
	    }
	    
	    exports.error = function(req, res, error, status){
	    	res.status(status || 500).send({
	    		error: error,
	    		message: ''
	    }
	    
	```

* **Wilson Castro Medellin** (1) [1115436](https://platzi.com/comentario/1115436/) 

	estandarizar el status de respuesta y tener doble check

* **carlosextra1** (1) [1059344](https://platzi.com/comentario/1059344/) 

	server.js
	``` 
	    const express = require('express');
	    const bodyParser = require('body-parser');
	    const router = express.Router();
	    const response =  require('./network/response');
	    var app =  express();
	    
	    app.use(bodyParser.json());
	    app.use(bodyParser.urlencoded({extended: false }));
	    app.use(router);
	    
	    app.get('/', (req, res) => {
	         res.header({
	            'custom-header' : 'Valore personalizado para el cliente'
	        })
	        response.success(req, res, 'Esto es lista de mensajes');
	    });
	    app.post('/pruebas', (req, res) => {
	        console.log(req.query);
	        console.log(req.body);
	        res.send('Datos regresados '+ req.body.text +' correctamente');
	    });
	    app.post('/', (req, res) => {
	        console.log(req.query);
	        if (req.query.error == 'ok')
	            response.error(req, res, 'Error simulado',401);
	        else
	            response.success(req, res, 'Creado correctamente', 201);
	    });
	    
	    app.delete('/delete', (req, res) => {
	        console.log(req.query);
	        console.log(req.body);
	        res.status(200).send([{
	            'error': null,
	            'body': 'Ejecutado correctamente!'
	         }]);
	    });
	    app.listen(3000);
	    console.log('La aplicación esta escuchando en pueto:3000');
	    
	```

* **jandrey** (1) [1036176](https://platzi.com/comentario/1036176/) 

	Porque se usa exports.function y no module.exports = function

	* **Diego Alexander Forero Higuera (Platzi)** [1036176] (3)

		Para poder hacer el export de los métodos de forma separada, esta lectura te puede ayudar a entender mejor <https://www.sitepoint.com/understanding-module-exports-exports-node-js/>

* **israelhuaman** (1) [954091](https://platzi.com/comentario/954091/) 

	por si se equivocan escribiendo :  
	<http://localhost:3000/message?error=ok>

* **israelhuaman** (1) [952722](https://platzi.com/comentario/952722/) 

	"que bien hecho esta esto mijin…!!! "

* **Alfredo Gonzalez** (1) [846039](https://platzi.com/comentario/846039/) 

	Aqui tienen una liga, para leer acerca de los modulos en node.js
	
	<https://www.tutorialsteacher.com/nodejs/nodejs-module-exports>

	* **Jesús Miguel Moreno Plasencia** [846039] (1)

		bien, justo algo como esto estaba buscando para tener mas claro el panorama!! buen aporte

	* **Fernando Cordero** [846039] (1)

		Esta demasiado buena esta pagina! Gracias!!!

* **Nicolas Esteban Prieto Sarmiento** (1) [812262](https://platzi.com/comentario/812262/) 

	Dinámico!

## 0120. Servir archivos estáticos [22616](https://platzi.com/clases/1689-backend-js/22616-servir-archivos-estaticos/)

### Descripción:


### Comentarios:

* **Andres Roberto Coello Goyes** (15) [725075](https://platzi.com/comentario/725075/) 

	Que potencia de NODE puede levantar servidor leer url con metodos del server y mostrar archivos staticos con un solo archivo…  
	con PHP es obligatorio tener un servidor APACHE -_- 😮

	* **Dragonatak** [725075] (2)

		Tal cual **@programandres** !!!

* **Jorge Andres Muñoz Becerra** (14) [731011](https://platzi.com/comentario/731011/) 

	Falto especificar que el archivo se debe llamar index.html, de lo contrario no trae nada a no ser que se especifique el nombre del archivo

	* **Carlos Hernández** [731011] (5)

		¡Muy buen punto!

	* **Alfonso Navarro** [731011] (1)

		Y donde se especificaría cual sería el archivo con el q se arranca???

* **Alfonso Navarro** (2) [1011077](https://platzi.com/comentario/1011077/) 

	Profe… simplemente genial…

* **Wilson Castro Medellin** (1) [1115492](https://platzi.com/comentario/1115492/) 

	Excelente, todo en solo lugar (back & front)

* **carlosextra1** (1) [1059977](https://platzi.com/comentario/1059977/) 

	Excelente y muy útil para el día a día!!

* **Kevin William Roberts Costa** (1) [829969](https://platzi.com/comentario/829969/) 

	Supongamos que entramos a la api a través de /, según la documentación de express podemos usar all()
	``` 
	    router.all('/', function(req, res){
	        response.error(req,res, 'Use /message instead', 401);
	    });```
	    
	```

* **Ricardo Lugo Recillas** (1) [824402](https://platzi.com/comentario/824402/) 

	```
	    const express = require("express");
	    const bodyParser = require("body-parser");
	    const router = express.Router();
	    
	    const response = require('./network/response');
	    
	    var app = express();
	    app.use(bodyParser.json());
	    app.use(bodyParser.urlencoded({ extended: false }));
	    app.use(router);
	    
	    app.use('/app', express.static('public'));
	    
	    router.get("/", function(req, res){
	    	console.log(req.headers);
	    	response.success(req, res, "este es el mesnaje enviado ");
	    });
	    
	    router.post("/", function(req, res){
	      res.send("peticion de post");
	    });
	    
	    router.patch("/", function(req, res){
	      res.send("peticion de patch");
	    });
	    
	    router.delete("/", function(req, res){
	      res.send("peticion de delete");
	    });
	    
	    app.listen(3000);
	    console.log(" la aplication esta escuchando en el port http://localhost::3000");
	    
	    
	```

* **EnmanuelCastillo** (1) [73202](https://platzi.com/comentario/830367/) 
En caso de un frontEnd hecho en React, ..¿solo arrastraría todos los archivos a la carpeta publica.?😅🤔

	* **Juan David Castro (Platzi)** [73202] (1)

		Puede ser tan simple o complicado como quieras. Te invito a ver este curso para estudiar este tema a profundidad: <https://platzi.com/clases/ssr/>. 😉

## 0130. Errores Cómo presentarlos e implicaciones en la seguridad [22617](https://platzi.com/clases/1689-backend-js/22617-errores-como-presentarlos-e-implicaciones-en-la-se/)

### Descripción:


### Comentarios:

* **Sebastian Cardoso Castillo** (13) [741925](https://platzi.com/comentario/741925/) 

	Para agregar colores al mensaje de error podemos instalar chalk
	``` 
	    npm i chalk
	    
	```
	
	Luego en nuestro archivo
	``` 
	    // response.js
	    const chalk = require('chalk')
	    
	    // ...
	    
	    exports.error = (req, res, error, status, details) => {
	      console.log(chalk.red('[response error]: ' + details))
	    
	      res.status(status || 500).send({
	        error: error,
	        body: ''
	      })
	    }
	    
	```
	
	En consola lo veremos así:  
	![Screenshot from 2019-09-17 23-03-18.png](https://static.platzi.com/media/user_upload/Screenshot%20from%202019-09-17%2023-03-18-571839c1-bef2-4e7b-9f1f-c914ba48d90d.jpg)

	* **tho13718** [741925] (2)

		Gracias amigo

	* **AlejoE02** [741925] (2)

		bastante útil el chalk para identificar el error por color

	* **Dragonatak** [741925] (1)

		Muchas gracias **@sebaveg** !!!

	* **lizardojara** [741925] (1)

		Muy interesante

* **Diego Andres Cardenas Caro** (4) [786263](https://platzi.com/comentario/786263/) 

	En el caso puntual de los **console.log** no es necesario hacer concatenacion de variables. simplemente pueden agregar cadenas de texto separadas por coma asi:
	``` 
	    console.log('Response Error: ',details)
	    
	```
	
	Output: Response Error: Es solo una simulacion de errores

	* **Sebastian Cardoso Castillo** [786263] (3)

		También existe la opción de usar _template strings_
		``` 
		    console.log(`Response Error ${details}`)
		    
		```
		
		En este caso y en la concatenación si details fuera un objeto imprimría **Response Error [object Object]**
		
		Escribiendolo como menciona Diego se imprime la variable entera.

* **sergio-medina93** (3) [901709](https://platzi.com/comentario/901709/) 

	Buenísima la clase. Muy bueno Node.JS. Por ahora me está pareciendo más fácil que Django 😃

	* **esdraspavon** [901709] (1)

		Django ❤️

* **Brandon Iván Quiroa Loarca** (2) [1048390](https://platzi.com/comentario/1048390/) 

	Sus clases son buenisimas para aprender!

* **Josias Cubillos Gutierrez** (2) [1024259](https://platzi.com/comentario/1024259/) 

	Carlos es muy buen profesor, genial!

* **Alfonso Navarro** (2) [1011093](https://platzi.com/comentario/1011093/) 

	Q practicas tan geniales…

* **Julián Fernando Amaya Díaz** (2) [1000001](https://platzi.com/comentario/1000001/) 

	Esta clase es muy valiosa. Carlos es muy buen profesor.

* **j.santos** (2) [990766](https://platzi.com/comentario/990766/) 

	Interesante el uso de los logs para proteger información de los errores propios de nuestra aplicación

* **Emmanuel Capandegui** (2) [869507](https://platzi.com/comentario/869507/) 

	¿como hago para guardar el log de errores en un archivo de texto?
	
	Saludos!

	* **Alan Santiago** [869507] (1)

		Puedes usar el módulo nativo de Node llamado _FileSystem_ y cada vez que se llame a `response.error` escribir en ese archivo.

* **Cesar Velásquez Córdova** (2) [759818](https://platzi.com/comentario/759818/) 

	```
	    exports.error = (req, res, message, status, details) => {
	        console.error(`[response error] ${details}`);
	        res.status(status || 500).send({
	          error: message,
	          body: ''
	        });
	    }
	    
	```
	
	Pueden usar los backticks para la concatenación de texto con los parámetros o variables. A esta parte ${details} se le llama interpolación.

* **Carlos Alex Becerra Chavita** (2) [728379](https://platzi.com/comentario/728379/) 

	Que interesante tema

* **juanchovar** (1) [1120860](https://platzi.com/comentario/1120860/) 

	He aprendido mucho en este curso de verdad que bueno

* **Wilson Castro Medellin** (1) [1115516](https://platzi.com/comentario/1115516/) 

	el famoso log de errores

* **ranel** (1) [1081393](https://platzi.com/comentario/1081393/) 

	Excelentes clases! muy conforme con este curso

* **MartinMB** (1) [977185](https://platzi.com/comentario/977185/) 

	Buena tactica

* **FabianIgnacio** (1) [904321](https://platzi.com/comentario/904321/) 

	Tengo una duda!!! Sucede que al enviar los errores por ejemplo con código 400, en el POSTMAN se ve el message del error que mando, pero al frontend me llega “Request failed with status code 400”, ¿Alguien sabe por que no se envía completo el objeto? Es como si no se enviará nada y vue tomará un mensaje por defecto para mostrar. Ayuda pls

	* **FabianIgnacio** [904321] (4)

		Me contesto por si a alguien más le pasa en algun momento… en el frontend capturas el error en un try catch(error){ console.log(error.response);}

	* **Emraji** [904321] (1)

		Si muestras el código será más fácil ayudarte

* **Fernando Cordero** (1) [830952](https://platzi.com/comentario/830952/) 

	```
	    exports.error = function (req, res, message, status, details) {
	        console.error(chalk.yellowBright('[response error]: ' + details));
	    
	        res.status(status || 200).send({
	            error: message,
	            codigo: 200,
	            message: true, 
	            body: req.body,
	            method: req.method
	        })
	    }
	    
	```

	* **carlosextra1** [830952] (1)

		¿Qué es chalk.yellowBright o para que lo usas?

* **alejandromarcano** (1) [823629](https://platzi.com/comentario/823629/) 

	Se podría resumir en un único exports nuestra respuesta, por supuesto esto depende de la lógica y el tamaño del proyecto. Un ejemplo para el caso de este video:
	``` 
	    exports.resp = (req,res,title,messg,status,details=false) 
	    => {
	        details ? console.error("[response error] ", details) 
	        : console.log("Okay")
	        res.status(status).send({title: title, messg: messg})
	    }
	    
	```

* **Dragonatak** (1) [756524](https://platzi.com/comentario/756524/) 

	Excelente y súper útil el feedback acerca de mostrar la info de los errores a los usuarios en ésta clase **@Carlos Hernández** !!!

* **pabloverduzcos** (1) [734642](https://platzi.com/comentario/734642/) 

	🔒

* **Jose Xavier Ramos Gonzalez** (0) [739628](https://platzi.com/comentario/739628/) 

	en que momentos se debe usar el try y catch?

	* **Ezequiel Guerra** [739628] (3)

		Cuando quieres evaluar un bloque de código, comúnmente se usa cuando hacemos un llamado asíncrono por ejemplo cuando llamamos a un servicio de nuestra app.
		``` 
		    router.get('/', async (req,resp,next) =>{
		       const { id } = req.query;
		        try{
		            constresult = await exampleService.getExample({id})
		            resp.status(200).json({
		                data: result,
		                msg: "product listed"
		            })
		        }
		        catch(err){
		            next(err)
		        }
		    
		```

	* **Carlos Hernández** [739628] (3)

		Cada vez que algo pueda lanzar una excepción en nuestro código.  
		.  
		De esta forma, evitaremos que la excepción (normalmente un error) se propague hacia arriba, causando que nuestro proceso muera.  
		.  
		Además, podremos entender qué ha sucedido, y actuar en consecuencia.

# Comprender y desarrollar la arquitectura básica de un backend en NodeJS, y comunicarse entre módulos [4538]

## 0140. Conceptualmente Rutas, controladores y bases de datos [22632](https://platzi.com/clases/1689-backend-js/22632-conceptualmente-rutas-controladores-y-bases-de-dat/)

### Descripción:


### Comentarios:

* **Francisco Javier Vázquez Paredes** (60) [741903](https://platzi.com/comentario/741903/) 

	Les comparto el diagrama explicado por Carlos  
	![diagrama.png](https://static.platzi.com/media/user_upload/diagrama-825e902b-0966-40f0-8231-65b99f7206c1.jpg)

	* **reignover** [741903] (2)

		Ésta arquitectura tiene un nombre? Cómo se conoce?

	* **René Sanchez** [741903] (3)

		Esta muy buena!! muchas gracias por compartir 😃

	* **Dragonatak** [741903] (2)

		Excelente!! Muchas gracias por compartirlo **@frankvazk** !!

	* **soyaligarciap** [741903] (1)

		Muchas gracias!!! Excelente aporte

	* **lizardojara** [741903] (1)

		Parece una arquitectura SOA

	* **bmvalarezo** [741903] (1)

		gracias!!!

	* **jesusgomez12** [741903] (1)

		Buenísimo, muchas gracias.

	* **eduardoartemis** [741903] (1)

		Buen aporte !

	* **jonathan2138** [741903] (1)

		awesome, gracias amigo

	* **martin-retamozo** [741903] (1)

		Gracias idolo.!! 😃

* **FizIrvin** (21) [726366](https://platzi.com/comentario/726366/) 

	genial diagrama de la arquitectura del proyecto Backend!!! así lo deberían detallar en los demás cursos… porque a veces uno como estudiante,van demasiado rápido los profes creando archivos y carpetas y no sabemos de antemano y en ese mismo momento la razón de la organización de documentos… genial maestro!!!

* **AndreCoDev** (12) [731886](https://platzi.com/comentario/731886/) 

	De los mejores profesores que ha tenido Platzi, no se guarda nada y lo explica de manera precisa y concisa.

* **Estefymine** (10) [907410](https://platzi.com/comentario/907410/) 

	grandioso profesor, nominado al mejor profe de platzi 2020.

* **Sebastian Cardoso Castillo** (9) [772672](https://platzi.com/comentario/772672/) 

	Hace poco use [Strapi](https://strapi.io/). Un Headless CMS que crea una API de manera sencilla. Pude observar que usa la misma arquitectura para contruir la API. Pero mi duda es:  
	¿Cuál es la diferencia con la arquitectura implementada en el otro [curso de backend con Node de la escula de Javascript](https://platzi.com/clases/backend-nodejs/) ? ¿Existe alguna guía para saber mas sobre los patrones de diseño o arquitecturas de backend con Node?

	* **Ronnie Moncayo** [772672] (3)

		Muy buena pregunta, a la espera de las respuestas.

	* **Hafnio** [772672] (1)

		Los patrones de diseño son independientes de los lenguajes que uses. Esta el MVC (Model-View-Controller) , el MTV (Model-Template-View), luego estan como los que explico el profesor que usan networks y routers que son un poco mas versatiles pero menos estructurados. El patron de diseño que eligas depende de tus nececidades y gustos porque hay muchas variantes, incluso puedes hacer el tuyo propio.

* **jiduartem** (7) [913457](https://platzi.com/comentario/913457/) 

	La verdad, me parece el mejor curso que he tomado hasta el momento!

* **lizardojara** (7) [833993](https://platzi.com/comentario/833993/) 

	Es el primer curso que veo que un profesor explica primero que arquitectura utilizara para el proyecto. **Enhorabuena profesor Carlos.**

* **Nick1125** (5) [1010295](https://platzi.com/comentario/1010295/) 

	Excelente profesor donde lo califico quiero darle 5 estrellas

	* **Emanuel Valero** [1010295] (2)

		Hola!
		
		Al finalizar el curso puedes calificarlo. Además, el profesor Carlos imparte estos otros cursos que están muy buenos también:
		
		* Fundamentos de node: <https://platzi.com/clases/fundamentos-node/>
		* Curso práctico de node: <https://platzi.com/clases/practico-node/>
		
		

* **Jeins1991** (5) [984650](https://platzi.com/comentario/984650/) 
Me gusta como explica, claro y preciso! Excelente profesor!

* **jorgeluisv8a** (5) [745185](https://platzi.com/comentario/745185/) 

	excelente explicación, muy bien platzi por siempre estar buscando excelentes profesores

* **jonathan2138** (4) [923874](https://platzi.com/comentario/923874/) 

	Arquitectura de backend para NodeJS

* **nancygtec** (4) [914371](https://platzi.com/comentario/914371/) 

	Muy clara la explicación, excelente trabajo

* **Jose Alberto Arango Sánchez** (4) [798747](https://platzi.com/comentario/798747/) 

	Por fin !!! alguito de buenas practicas, por lo general platzi es puro código espagueti.

	* **rafaelrb40** [798747] (3)

		Estoy de acuerdo. Es buno que le eseñen a uno como estudiante a organizar un proyecto y a utilizar mejores practicas. Eso presisamente es lo que uno busca al tomar los cursos, no solo saber de codigo, si no saber estructurarlo

* **pabloverduzcos** (4) [734651](https://platzi.com/comentario/734651/) 

	Super claro, gran manera de enseñara a estructurar nuestro proyecto.

* **beaps** (4) [729518](https://platzi.com/comentario/729518/) 

	Qué buena explicación!!!🔝👏🏻

* **Efraín Lerma** (3) [1011129](https://platzi.com/comentario/1011129/) 

	excelente profesor!!

* **Camilo Andrés Santana Lizcano** (3) [856653](https://platzi.com/comentario/856653/) 

	Que bueno aprender a hacer las cosas bien desde un principio, Muy buena explicación 😄

* **José María Cuevas Ramírez** (2) [1066255](https://platzi.com/comentario/1066255/) 

	Grande Carlos, necesitamos más cursos con él!

* **brandon.arrieta** (2) [1038208](https://platzi.com/comentario/1038208/) 

	Como se llama esta forma de estructurar los archivos,  
	es un patrón de diseño?

* **j.santos** (2) [990800](https://platzi.com/comentario/990800/) 

	Una arquitectura interesante para aprender

* **MartinMB** (2) [977205](https://platzi.com/comentario/977205/) 

	Buena teoría vamos a ver que tal la practica

* **ehnbytes** (2) [971678](https://platzi.com/comentario/971678/) 

	Muy fácil de entender, muy bien explicado!!

* **jmiraba** (2) [963841](https://platzi.com/comentario/963841/) 

	excelente explicacion

* **evelinortizp** (2) [946761](https://platzi.com/comentario/946761/) 

	Profe un placer escucharlo!

* **Alberto Campos Hernandez** (2) [902006](https://platzi.com/comentario/902006/) 

	El mejor profe de Platzi!!

* **sergio-medina93** (2) [901831](https://platzi.com/comentario/901831/) 

	Por fin entiendo esto de la arquitectura. 👏👏🎊

* **ivofacundo** (2) [857666](https://platzi.com/comentario/857666/) 

	creo que por el momento el mejor curso de node que tomé, la verdad me emociona y me incentiva a seguir aprendiendo. Mientras veía como el profesor explicaba me salio una sonrisa de la nada porque me super emocione de todo de lo que estoy por aprender!! Gracias!!!

* **Deivy Jesus** (2) [824655](https://platzi.com/comentario/824655/) 

	**Utilizando un dockerfile **
	
	FROM node:12  
	COPY [“package.json”,“package-lock.json”, “/usr/src/”]
	
	WORKDIR /usr/src
	
	COPY [".", “/usr/src/”]
	
	RUN npm install
	
	EXPOSE 3000
	
	CMD [“npx”, “nodemon”,“server.js”]

* **alejandromarcano** (2) [808257](https://platzi.com/comentario/808257/) 

	Excelente gestionar la base de datos para que en caso de utilizar una distinta a la original, no se tenga que gastar demasiado tiempo de desarrollo realizando los cambios

* **Armando de jesus santiz lopez** (2) [737218](https://platzi.com/comentario/737218/) 
Excelente profesor,

* **aerama** (2) [81586](https://platzi.com/comentario/984680/) 
¿La parte de network podría considerarse equivalente a los servicios?

	* **Juan José Vega Quintero** [81586] (1)

		En la siguientes clases explica eso.

* **Andrés Felipe Castañeda** (1) [1118683](https://platzi.com/comentario/1118683/) 
	
	![estructura.PNG](https://static.platzi.com/media/user_upload/estructura-753806d3-5274-445d-9614-4417934f3e5c.jpg)

* **Andrés Felipe Castañeda** (1) [1118609](https://platzi.com/comentario/1118609/) 

	RUTAS - CONTROLADORES - ALMACENAMIENTO

* **Wilson Castro Medellin** (1) [1115546](https://platzi.com/comentario/1115546/) 

	Diagrama de componentes

* **Rabi Leonel Leon Chan** (1) [1082013](https://platzi.com/comentario/1082013/) 

	Capas:  
	1.- Capa Principal: Toda la configuración de nuestro servidor  
	2.- Capa de Red: Donde se encuentran nuestra configuración de nuestras rutas y respuestas.  
	3.- Capa de componentes: Aquí estarán todos nuestros componentes.

* **carlosextra1** (1) [1059996](https://platzi.com/comentario/1059996/) 

	Excelente!! El hacer este mismo proceso que hace el profe. De diseño de la arquitectura nos quita muchos dolores de cabeza!!

* **Carlos Quispe** (1) [1029593](https://platzi.com/comentario/1029593/) 

	muy buena clase gracias Maestro Carlos!!!

* **diego-miranda-vazquez** (1) [912367](https://platzi.com/comentario/912367/) 

	lo mejor del cursoo…

* **Alejandro_** (1) [892689](https://platzi.com/comentario/892689/) 

	De las mejores clases que he visto.

* **Sebastián Pineda Duque** (1) [877258](https://platzi.com/comentario/877258/) 

	¿Esta misma arquitectura la puedo aplicar para cualquier otro tipo de prroyectos?

* **José Pach Delgado** (1) [866471](https://platzi.com/comentario/866471/) 

	It’s great He said correctly “Mysql” instead of “Myciqual”  
	😃

* **bmvalarezo** (1) [853184](https://platzi.com/comentario/853184/) 

	Que gran explicación y que gran profe!!!

* **Gtiseira** (1) [848182](https://platzi.com/comentario/848182/) 

	Genial! la verdad que da gusto tener las clases con un profe asi

* **Fernando Cordero** (1) [830958](https://platzi.com/comentario/830958/) 

	Diagrama de backend

* **Juan Daniel Gualtero Diaz** (1) [771581](https://platzi.com/comentario/771581/) 

	Claro que que tenemos o vamos a desarrollar. Muy bien!!!

* **Cesar Velásquez Córdova** (1) [759835](https://platzi.com/comentario/759835/) 

	Me encantó la explicación!!

* **Dragonatak** (1) [758512](https://platzi.com/comentario/758512/) 

	Excelente explicación **@Carlos Hernández** !!!

* **René Sanchez** (1) [755299](https://platzi.com/comentario/755299/) 

	Muy buena explicación todo muy facil de entender 😃 a seguir aprendiendo para aportar en donde desarrollo!!

* **jorgeluisv8a** (1) [749834](https://platzi.com/comentario/749834/) 

	Tengo una pregunta, en cada componente se esta poniendo una conexión a base de datos, el ejemplo que pone sobre porque debe ser así es en caso de que se tenga que cambiar la base de datos de los usuarios solo sea cambiar la base de datos del componente y listo, pero que pasa si voy a cambiar la base de datos de todo el proyecto, tocaría cambiar en todos los componentes y si el proyecto es muy grande seria muy tedioso.
	
	que se debe hacer en ese caso ?

	* **Juan José Vega Quintero** [749834] (1)

		No entiendo la pregunta, si cambias la DB no veo para que actualizar cada componente.

* **SaFeRamirez** (1) [67530](https://platzi.com/comentario/724998/) 
¿Por buenas prácticas no es mejor manejar la lógica del negocio en la capa de dato?

	* **Andres Roberto Coello Goyes** [67530] (2)

		el siguiente video lo explica la logica de negocio

* **Sebastián Pineda Duque** (0) [877259](https://platzi.com/comentario/877259/) 

	¿Cómo se llama esta arquitectura? Está muy interesante, y quisiera profundizar.

* **Sebastián Pineda Duque** (0) [877257](https://platzi.com/comentario/877257/) 

	¿Esta misma arquitectura la puedo aplicar para un backend con otros lenguajes de programación?

## 0150. Rutas y capa de red Responsabilidades y límites [22618](https://platzi.com/clases/1689-backend-js/22618-rutas-y-capa-de-red-responsabilidades-y-limites/)

### Descripción:


### Comentarios:

* **gorydev** (7) [799247](https://platzi.com/comentario/799247/) 

	Personalmente prefiero agrupar todo por componente entonces tendría /message  
	-/routes  
	-/controller  
	-/bd
	
	para así encontrar fácilmente lo que necesite de algún componente

	* **Luis Fernández** [799247] (1)

		Me gusta más esta manera 👍👍

* **SergioBernal** (7) [728014](https://platzi.com/comentario/728014/) 

	No puedo responder a tu mensaje. Quería agradecer tu dedicación y tiempo tanto del curso como de las respuestas. Un saludo.

	* **Carlos Hernández** [728014] (3)

		Gracias a ti por el tiempo, por la motivación y por el feedback. De verdad, es muy valioso.

* **Fernando Cordero** (6) [832513](https://platzi.com/comentario/832513/) 

	Clase que vale la pena repetir para estar claro de todo el proceso de conexion de la app...

* **Deyvis Neyser Valdez Gavilan** (6) [746521](https://platzi.com/comentario/746521/) 

	Hola, solo como aporte:
	
	  1. En la carpeta --> network/routes.js no fue necesario requerir a express, al menos por el momento.
	  2. otra forma de recibir el app desde server.js
	
	
	``` 
	    module.exports = server => {
	        server.use("/message", message);
	    }
	    
	```
	
	Saludos!

	* **john jairo lopez ramirez** [746521] (1)

		En tu segundo punto estas diciendo algo como " llamo directamente a la instancia sever desde el archivo server.js", sin necesidad de crear la función function(server) que se hizo en el video ???

	* **Deyvis Neyser Valdez Gavilan** [746521] (3)

		Hola, exacto; lo que hice fue aplicar un arrowFunction o función flecha pero puedes hacerlo también aplicando como función anónima de la siguiente forma:
		``` 
		    module.exports =function(server) {
		        server.use("/message", message);
		    }
		    
		```
		
		.
		
		Puedes recibir el server de muchas formas, como por ejemplo:  
		1.
		``` 
		    functionroutes(server) {
		    	server.use("/message", message);
		    }
		    
		    module.exports = routes;
		    
		```
		
		  1. 
		
		``` 
		    const routes = function(server) {
		    	server.use("/message", message);
		    }
		    
		    module.exports = routes;
		    
		```
		
		  1. 
		
		``` 
		    module.exports = server => {
		        server.use("/message", message);
		    }
		    
		```
		
		Espero te haya sido de ayuda. Saludos.

* **Estefymine** (4) [907916](https://platzi.com/comentario/907916/) 

	Hola, Sergio,  
	.  
	Cualquier aplicación va a tener tres puntos de responsabilidad, que deben responder a tres preguntas:
	
	¿Cómo me comunico con ella?  
	¿Qué hace?  
	¿Dónde y cómo se guardan los resultados?  
	.  
	La respuesta a estos tres puntos, corresponden a las tres capas que vamos a generar:  
	Capa de red (en inglés “network”)  
	Capa controladora (en inglés, “controller”)  
	Capa de almacenamiento (en inglés, “store”)  
	.  
	De esto hablo en profundidad en la clase anterior.  
	.  
	La primera capa es una capa de red, porque la conexión con la aplicación se hace a través del protocolo de comunicación en red HTTP. Es la responsable de comunicar al cliente HTTP con nuestro código del controlador.  
	.  
	Si recuerdas las primeras clases, verás que el protocolo HTTP construye una petición con una dirección (route), un verbo (method), unas cabeceras (headers) y un mensaje (body).  
	.  
	Por esto, cada uno de nuestros componentes, tendrá un archivo “network.js” encargado de traducir la petición del cliente HTTP a la acción que queremos realizar en nuestro controlador.  
	.  
	Así, lo que hace nuestro código (la funcionalidad) no está acoplado a unos requisitos de red, y puede ser reutilizado con otras fuentes de entrada (colas MQTT, una biblioteca externa, microservicios…).  
	.  
	La opción que planteas, llamarlo “interface” en lugar de network es también una opción válida. En caso de que tu carpeta se llame interface (o, quizá mejor, “interfaces”), llama a tu archivo “http-response.js” para poder generar nuevas interfaces de escucha o/y respuesta no HTTP.  
	.  
	¡Gracias!

* **Sebastian Cardoso Castillo** (4) [742147](https://platzi.com/comentario/742147/) 

	Al aprender esto siento algo como lo que sentí con Redux en el Frontend. Una manera compleja de organización los datos que cuando la terminas integrando se transforma en una forma mas fácil de organizar el flujo de información. Y mas fácil para escalar.

* **SergioBernal** (4) [724922](https://platzi.com/comentario/724922/) 

	No entiendo la estructura de network que estás planteando. Entiendo que lo único que puede ser considerado como “red” o “capa de red” es el app.listen y el [socket.io](http://socket.io) que forman parte de la infraestructura.
	
	No entiendo que tienen que ver las rutas HTTP con “network”.
	
	El protocolo HTTP es un protocolo de la [capa de aplicación](https://es.wikipedia.org/wiki/Protocolo_de_transferencia_de_hipertexto), entendería que lo modularizaras en algo como “interface > response.js” para reutilizar con otras infraestructuras como Websockets, porque al final es parte de la interfaz hacia el cliente (humano o máquina). En el examen me ha llevado a la confusión.

	* **Carlos Hernández** [724922] (46)

		Hola, Sergio,  
		.  
		Cualquier aplicación va a tener tres puntos de responsabilidad, que deben responder a tres preguntas:
		
		  1. ¿Cómo me comunico con ella?
		  2. ¿Qué hace?
		  3. ¿Dónde y cómo se guardan los resultados?  
		.  
		La respuesta a estos tres puntos, corresponden a las tres capas que vamos a generar:
		  4. Capa de **red** _(en inglés “network”)_
		  5. Capa **controladora** _(en inglés, “controller”)_
		  6. Capa de **almacenamiento** _(en inglés, “store”)_  
		.  
		De esto hablo en profundidad en la clase anterior.  
		.  
		La primera capa es una capa de red, porque la conexión con la aplicación se hace a través del protocolo de comunicación en red HTTP. Es la responsable de comunicar al cliente HTTP con nuestro código del controlador.  
		.  
		Si recuerdas las primeras clases, verás que el protocolo HTTP construye una petición con una dirección (route), un verbo (method), unas cabeceras (headers) y un mensaje (body).  
		.  
		Por esto, cada uno de nuestros componentes, tendrá un archivo “network.js” encargado de traducir la petición del cliente HTTP a la acción que queremos realizar en nuestro controlador.  
		.  
		Así, **lo que hace nuestro código** (la funcionalidad) **no está acoplado a unos requisitos** de red, y puede ser reutilizado con otras fuentes de entrada (colas MQTT, una biblioteca externa, microservicios…).  
		.  
		La opción que planteas, llamarlo “interface” en lugar de network es también una opción válida. En caso de que tu carpeta se llame interface _(o, quizá mejor, “interfaces”)_ , llama a tu archivo “http-response.js” para poder generar nuevas interfaces de escucha o/y respuesta no HTTP.  
		.  
		¡Gracias!
		
		

* **ivofacundo** (3) [857786](https://platzi.com/comentario/857786/) 

	yo lo ordené como
	
	/messages  
	-/routes/index.js  
	-/controller/index.js  
	-/store/index.js  
	entonces al llamarlo con un require no es necesario hacer ‘…/components/messages/routes/index.js’ ya que por defecto toma el index.js de la carpeta y solo se lo llamaría como '…/components/messages/routes’  
	tambien funciona para las demas carpetas, por ahora me sirve.

* **Iván Darío Sánchez Jiménez** (2) [1000790](https://platzi.com/comentario/1000790/) 

	Si retiramos la importación de express en el archivo **routes.js** , la aplicación sigue funcionando ya que la instancia del servidor que pasamos por parámetro a la función viene con los métodos de express.
	
	Mi pregunta es ¿será necesario importar express en este archivo?

	* **Juan José Vega Quintero** [1000790] (1)

		Tal vez más adelante este la respuesta xd

* **leonardo-albino** (2) [791871](https://platzi.com/comentario/791871/) 

	Perfecto!

* **Wilson Castro Medellin** (1) [1115596](https://platzi.com/comentario/1115596/) 

	Responsabilidades=>rutas & límites=>capa de red

* **carlosextra1** (1) [1060021](https://platzi.com/comentario/1060021/) 

	Excelente clase!!

* **Kevin Jeremy Salazar Jimenez** (1) [998283](https://platzi.com/comentario/998283/) 

	excelente!

* **MartinMB** (1) [977229](https://platzi.com/comentario/977229/) 

	Yo no lo ordeno de esa forma pero es muy parecida

* **duacos** (1) [975670](https://platzi.com/comentario/975670/) 

	La función “use” de express me parece ambigua, me cuesta saber qué hace exactamente.

* **Fabio Andres Arango Grajales** (1) [842707](https://platzi.com/comentario/842707/) 

	excelente Clase…Felicitaciones

* **Fabio Andres Arango Grajales** (1) [73869](https://platzi.com/comentario/842705/) 
Excelente clase.Felicitaciones

* **johneduardo** (1) [71942](https://platzi.com/comentario/806940/) 
En teoría, el método use() se utiliza para … ?

	* **Juan David Castro (Platzi)** [71942] (3)

		Se utiliza para interceptar las peticiones que llegan a nuestro servidor. Podemos analizarlas para decidir si las bloqueamos o las dejamos continuar su flujo. Por ejemplo, podemos verificar que el usuario esté autenticado antes de entregarlo a las funciones que responden con datos privados.
		
		👉 <https://expressjs.com/es/guide/writing-middleware.html>  
		👉 <https://expressjs.com/es/api.html#app.use>

## 0160. Controladores Definiendo la lógica de negocio [22619](https://platzi.com/clases/1689-backend-js/22619-controladores-definiendo-la-logica-de-negocio/)

### Descripción:


### Comentarios:

* **j0e** (9) [777529](https://platzi.com/comentario/777529/) 

	El error de el minuto **06:55** se debe a que escribió mal **return** , el puso **retrun** si es posible hacerlo en una sola linea
	``` 
	    returnreject('Los datos son incorrectos');
	    
	```

	* **Ken Ramirez** [777529] (3)

		De hecho ya no es necesario el return en esa línea, al llamar a reject o resolve termina de ejecutarse la promesa

* **Francisco Javier Vázquez Paredes** (6) [745547](https://platzi.com/comentario/745547/) 

	Aquí les dejo una propuesta del código utilizando `async-await`
	``` 
	    post(async (req, res) => {
	        try{
	            const fullMessage = await controller.addMessage(req.body.user, req.body.message)
	            response.success(req, res, 201, fullMessage)
	        }catch(error){
	            response.error(req,res,null,error)
	        }
	    })
	    
	```

	* **Misael Tamayo Nuñez** [745547] (1)

		hola lo hice de esa manera pero cuando quiero que me salga el error para ver si funciona el response.error me sale esto en la consola
		
		Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch()

	* **lizardojara** [745547] (1)

		Creo que @misaeltamayonuñez algo has escrito mal, porque el error dice que te falta capturar los errores en un try catch. Prueba asi a ver si te funciona:
		``` 
		    router.post("/", async (req, res) => {
		    
		        const { user, message } = req.body
		    
		        try {
		            const fullMessage = await controller.addMessage(user, message)
		            response.success(req, res, fullMessage, 201)
		        } catch (error) {
		            response.error(req, res, "Informacion invalida", 500, "Error en el contenido")
		        }
		    
		    })
		    
		    
		```

* **jonathan2138** (3) [925837](https://platzi.com/comentario/925837/) 

	Ahora ya le encuentro utilidad al curso de Fundamentos de JS, muy buena clase

* **sergio-medina93** (3) [905176](https://platzi.com/comentario/905176/) 

	Por fin entiendo más lo del controlador. En el trabajo era tan difícil entender como se conectaba a la capa de presentación.
	
	¡Muchas gracias Profe! 😬👍

* **pabloverduzcos** (3) [734692](https://platzi.com/comentario/734692/) 

	¿Que pasa si en la parte de la promesa lo hubiese dejado de la siguiente manera?  
	.
	``` 
	    functionaddMessage(user, msg) { 
	    	returnnewPromise(function(resolve, reject){ 
	    		if (user && msg) {
	    			// code goes here...
	    			resolve('Everything goes right');
	    		} else {
	    			// code goes here...
	    			reject('Oh no an error has occurred');
	    		}
	    	});
	    }
	    
	```
	
	.  
	Aun que me imagino que por estar trabajando en **Node.js** tenemos que seguir el patro de _Error First_. Sin embargo me quede con esa duda, ¿que opinas Carlos?

	* **Carlos Hernández** [734692] (14)

		Funcionaría perfectamente. Sin embargo, suele ser buena práctica controlar los errores primero y, si todo va bien, continuar con la funcionalidad. Ésto te permite poder tener varias condiciones de fallo de forma más elegante. Imagina que quisiésemos comprobar, además, que el mensaje tiene un mínimo de 1 carácter y un máximo de 255:
		``` 
		    if (!user || !msg) {
		      return"err 1";
		    }
		    if (msg.length < 1 || msg.length > 255) {
		      Return"err 2";
		    }
		    
		    // ...
		    
		```
		
		Como estamos ejecutando un return en caso de error, no necesitamos un else if ni un else. Asi queda el código mucho más claro, más sencillo, y eliminamos un nivel de indentación, lo que lo hace, en mi opinión, más elegante.  
		.  
		Además, podemos devolver (o hacer) cosas diferentes según el error, lo que nos ayudará a poder resolverlo, o reponernos de él de forma más eficaz.  
		.  
		Si lo hiciésemos al revés, sería algo así:
		``` 
		    if (user && msg && msg.length > 1 && msg.length < 255) {
		      // ...
		    } else {
		     return"err 1 o 2";
		    }
		    
		```
		
		La condición se vuelve complicada, anidamos de más la funcionalidad, y no podemos saber el motivo concreto del error.

	* **lizardojara** [734692] (1)

		Express tiene su propio modulo de manejador de errores, seguro que luego lo veremos mas al detalle.

	* **pabloverduzcos** [734692] (1)

		Wow, gran explicación, gracias Carlos.

* **raparisg** (2) [934344](https://platzi.com/comentario/934344/) 

	¿Existe alguna dependencia en NPM que ayude a hacer los logs más sencillo? Encuentro poco eficiente tener que escribir [messageController] en los logs para saber de dónde vienen. ¿Habrá alguna dependencia que haga esto or nosotros?

	* **Líncol Saenz** [934344] (1)

		No he visto ninguna. Pero eso es una mensaje totalmente personalizado, es decir, depende de la idea y preferencias de los desarrolladores qué poner ahí.

	* **raparisg** [934344] (2)

		Encontré una que me gustó bastante 😃. Vengo del mundo de Java y es igual a la que se utiliza allá. <https://www.npmjs.com/package/log4js>
		
		Mi implementación fue la siguiente: creé una función que reutilizo con las configuraciones que desee.
		``` 
		    const log4js = require("log4js");
		    
		    module.exports = functiongetLogger(component) {
		      const logger = log4js.getLogger(component);
		      logger.level = "debug";
		      return logger;
		    };
		    
		```
		
		Luego lo llamo de la siguiente manera:
		``` 
		    const logger = require("../utils/logger")("MySQL");
		    
		```

* **MariaGuadalupeGtojr** (2) [77841](https://platzi.com/comentario/910758/) 
Alguien me puede ayudar con este error donde en codigo si tengo definido user… -TypeError: Cannot read property ‘user’ of undefine

	* **Líncol Saenz** [77841] (1)

		Más info? Eso significa que no ha recibido nada y por lo tanto no ha podido ejecutar ninguna acción. Tendría que ver tu código para hacerme una idea, pero lo recomendable es que crees un if-statement que se encargue de manejar esos errores, en este caso, cuando no se recibe ninguna info:
		
		if(!input){  
		console.log(‘no se han ingresado datos’)  
		}

* **Wilson Castro Medellin** (1) [1115652](https://platzi.com/comentario/1115652/) 

	controladores=>lógica de negocio

* **Emilio Ian Camacho Mejia** (1) [1083358](https://platzi.com/comentario/1083358/) 

	Hola, tengo un problema… Insomia me marca el siguiente error.
	
	TypeError: Cannot read property ‘user’ of undefined  
	at /home/ian/Documentos/Cursos/nodejs/components/message/network.js:16:36  
	at Layer.handle [as handle_request] (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/layer.js:95:5)  
	at next (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/route.js:137:13)  
	at Route.dispatch (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/route.js:112:3)  
	at Layer.handle [as handle_request] (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/layer.js:95:5)  
	at /home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:281:22  
	at Function.process_params (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:335:12)  
	at next (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:275:10)  
	at Function.handle (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:174:3)  
	at router (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:47:12)  
	at Layer.handle [as handle_request] (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/layer.js:95:5)  
	at trim_prefix (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:317:13)  
	at /home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:284:7  
	at Function.process_params (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:335:12)  
	at next (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/router/index.js:275:10)  
	at expressInit (/home/ian/Documentos/Cursos/nodejs/node_modules/express/lib/middleware/init.js:40:5)
	
	Asi esta mi codigo en el post
	``` 
	    router.post('/', function(req, res){
	        controller.addMessage(req.body.user, req.body.message)
	            .then((fullMessage)=>{
	    
	            response.success(req, res, fullMessage, 201);
	            })
	            .catch(e => {
	    
	            response.error(req, res, 'Informacion Invalida', 400, "Es solo una simulacion de los errores ");
	            })
	        
	    
	    });
	    
	```
	
	Y la funcion en el controller:
	``` 
	    functionaddMessage(user,message){
	        returnnew Promise((resolve, reject) => {
	            if(!user || !message) {
	                console.error('[messageController] No hay usuario o mensaje');
	                reject('Los datos son incorrectos');
	                returnfalse;
	            }
	            const fullMessage = {
	                user: user,
	                message: message,
	                date: newDate(),
	            };
	    
	            store.add(fullMessage);
	            resolve(fullMessage);
	        });
	    }
	    
	```
	
	Me ayudarían a encontrar la solución por favor, no le encuentro 😦

	* **Jorge Merchan** [1083358] (1)

		te debe falta en server js lo siguiente:
		
		app.use(bodyParser.json());
		
		me pasaba lo mismo y aspi lo solucione

	* **Emilio Ian Camacho Mejia** [1083358] (1)

		@jorgemerchan  
		Si lo tengo, esto es lo que tengo en server.js
		``` 
		    const express = require('express');
		    const bodyParser = require('body-parser');
		    
		    const router = require('./network/routes');
		    
		    var app = express(); // inicializa express
		    //app.use(router);
		    router(app);
		    app.use(bodyParser.json()); // para trabajar con el body
		    
		    app.use('/app', express.static('public'));
		    
		    app.listen(3000);
		    console.log('La aplicacion esta escuchando en http://localhost:3000');```
		    
		```

* **carlosextra1** (1) [1060881](https://platzi.com/comentario/1060881/) 

	Excelente clase Tocayo!!

* **Pablo Gabriel Mederos Caballero** (1) [999608](https://platzi.com/comentario/999608/) 

	Tengo una duda. Estuve probando qué sucedería si hubiera un error dentro del método **then** , por ejemplo procesando la respuesta, y me pareció que podría manejar mejor el flujo de mi programa si manejo la respuesta de la siguiente manera:
	``` 
	    controller.addMessage(req.body.user, req.body.message)
	        .then(
	          resolve => {
	            console.log(10/a)  // Error bestial de ejemplo
	            response.success(req, res, 201, 'Mensaje creado correctamente')
	          },
	          error => {
	            console.log(10/a) // Error bestial de ejemplo
	            response.error(req, res, 400, "Algunos datos pueden estar incompletos", error)
	          }
	        )
	        .catch(e => {
	          response.error(req, res, 500, "Error interno del servidor", e)
	        })```
	    
	    Entonces en el caso que tuviera un error dentro de mi resolve o error, especialmente en desarrollo sería más fácil detectarlo (en este ejemplo  console.log(10/a)), y catch me devolvería el errorque tuve finalmente, y no le estaría echando la culpa al usuario de haber ingresado datos incorrectos, cuando la culpa fue mía durante el procesamiento dela respuesta.
	    Si esto es una mala práctica o no fuera necesario me gustaría saber por qué. Muchas gracias.
	```

* **Yesid Anacona** (1) [882862](https://platzi.com/comentario/882862/) 

	El proyecto esta en git?

	* **Juan José Vega Quintero** [882862] (1)

		Sí  
		<https://github.com/CodingCarlos/backend-node-platzi>

* **george-montenegro** (1) [879899](https://platzi.com/comentario/879899/) 

	Buenas noches, Disculpen tengo un problema al ejecutar el post el cliente RES que estoy usando me retorna este error:  
	pre>SyntaxError: Unexpected token u in JSON at position 4<br> at JSON.parse (<anonymous>)<br> at parse (/home/jorge/Documents/WORKSPACE/nodeJsIni/node_modules/body-parser/lib/types/json.js:89:19)<br> at /home/jorge/Documents/WORKSPACE/nodeJsIni/node_modules/body-parser/lib/read.js:121:18<br> at invokeCallback (/home/jorge/Documents/WORKSPACE/nodeJsIni/node_modules/raw-body/index.js:224:16)<br> at done (/home/jorge/Documents/WORKSPACE/nodeJsIni/node_modules/raw-body/index.js:213:7)<br> at IncomingMessage.onEnd (/home/jorge/Documents/WORKSPACE/nodeJsIni/node_modules/raw-body/index.js:273:7)<br> at emitNone (events.js:106:13)<br> at IncomingMessage.emit (events.js:208:7)<br> at endReadableNT (_stream_readable.js:1064:12)<br> at _combinedTickCallback (internal/process/next_tick.js:138:11)</pre>  
	</body>

	* **nancygtec** [879899] (2)

		Tienes un error en la sintaxis del json que estás enviando. Puedes entrar a <https://jsonlint.com/> para que valides cuál es el error.

* **José Tomás Villalba** (1) [833381](https://platzi.com/comentario/833381/) 

	8:55 — Cuando utilizo Insomnia no me da el mismo resultado. Me dice:
	
	`{ "error": "Informacion invalida", "body": "" }`
	
	Estoy seguro de tener los códigos bien escritos.
	
	Ayuda, por favor.

	* **lizardojara** [833381] (2)

		Fijate que hayas enviado los datos “user” y “message” por el body.

	* **Juan José Vega Quintero** [833381] (1)

		Y usar el formato JSON

* **luisglopez7777** (1) [82638](https://platzi.com/comentario/1009473/) 
una pregunta, por que en el catch si mandas “e” como parametro y en then no?

	* **Jesús Duarte García** [82638] (3)

		El catch recibe “e” de “error” por defecto, en el then no se recibe el error sino los datos 😃

* **daulisg** (1) [82510](https://platzi.com/comentario/1006774/) 
Tengo una pregunta: Todo me funciona como lo esperaba pero también siento que estoy copiando y pegado código (copy pasting) con el segui...

	* **Luis Arturo Lira Cerda** [82510] (3)

		Te recomiendo primero terminar el curso para que veas todo y luego intentar crear algo por ti mismo.
		
		En mi caso, con mis primeros cursos de Node.js hice una API pública, por lo que me tocó investigar varias cosas que en ese momento no había visto en el curso.
		
		Luego con más conocimientos de Node, hice otra API para conectar el frontend de mi portafolio y que esta a su vez se conectar a la BDD de MongoDB, tiene autenticación con passport y JWT, me basé en el curso de la escuela de Javascript y mi frontend lo hice con Next.js para tener server side render con un custom server hecho en express.
		
		Poco a poco entre más vas sabiendo vas intentando crear algo que para ti sea “complejo” y aprenderás mucho, obvio también sigue tomando cursos para que conozcas más sobre la tecnología y cómo usarla 😃

* **keyner-baez** (1) [69913](https://platzi.com/comentario/765756/) 
He hecho un console.log del req.body y me imprime es undefined y no se por que, alguien me puede ayudar?

	* **Erik Ochoa (Platzi)** [69913] (2)

		El _req.body_ es la información que tú mandas en el request, recuerda que estamos usando una petición tipo **POST** en la que mandamos información al servidor.
		
		Al momento de hacer la petición ¿estás mandando algo? Usa un [REST Client](https://insomnia.rest) para poder hacer la petición como lo hace el profesor, el navegador no te va a bastar, mira como [aquí](https://platzi.com/clases/1689-backend-js/22619-controladores-definiendo-la-logica-de-negocio/?time=169) llena un JSON con la información.
		
		Espero te sirva.

* **Rachid Moyse Polania** (1) [68693](https://platzi.com/comentario/744340/) 
Cuando pasamos los atributos req.body.user, req.body.message me marca error, dice lo siguiente: TypeError: Cannot re...

	* **Manuel Ojeda** [68693] (2)

		Ya revisaste si mandas un objeto con el nombre user?  
		Que el error dice que no encuentra nada con ese nombre dentro del request

## 0170. Almacenando la información en una base de datos [22620](https://platzi.com/clases/1689-backend-js/22620-almacenando-la-informacion-en-una-base-de-datos/)

### Descripción:


En esta clase veremos cómo crear mocks (simulación de una base de datos) para probar nuestras funciones, rutas y servidor.

### Comentarios:

* **johnflorez** (8) [731123](https://platzi.com/comentario/731123/) 

	 **Cuando Realizamos getMessages de controller.js no me retornaba nada usando solo store.list - se le debe especificar que es una función,**
	``` 
	    //message/controller.js
	    const getMessages = () =>{
	        returnnewPromise((resolve, reject) =>{
	            resolve(store.list())
	        });
	    }
	    
	```

	* **Sebastian Cardoso Castillo** [731123] (2)

		Claro, tal cual esta en el curso.

* **FabianIgnacio** (6) [890676](https://platzi.com/comentario/890676/) 

	No es más facil usar async await y el codigo queda más simple? Digo osea, queda entendible y facil de mantener segun yo

	* **Juan José Vega Quintero** [890676] (1)

		Se podría, pero funciona en menos navegadores y probablemente tocaría usar babel.

* **ivofacundo** (6) [857872](https://platzi.com/comentario/857872/) 

	Lo que yo entiendo de **MOCKS** es que es un objeto que simula o imita el comportamiento de uno real con el fin de poder hacer testing sin la necesidad de tener una capa compleja de base de datos.

* **rafaelrb40** (3) [799022](https://platzi.com/comentario/799022/) 

	En lo que llevo visto del curso no se utiliza el paradigma de programacion orientada a objetos(clases, constructores, objetos interfaces etc. ) esto tiene alguna ventaja en node ? es una mejor manera de hacer las cosas?. Gracias de antemano por responder

	* **gorydev** [799022] (4)

		en javascript y node es muy común utilizar la programación funcional averigua sobre ese tema es muy interesante

	* **rafaelrb40** [799022] (1)

		ok muchas gracias, en serio por la respuesta

	* **lizardojara** [799022] (1)

		Digamos que es un tema mas de rapidez. En React, es lo mismo con los Hooks o Redux.

	* **Ruben Padilla** [799022] (2)

		Escuela de JS | Curso de backend con nodejs: [Arquitectura orientada a eventos ](https://platzi.com/clases/1646-backend-nodejs/22016-arquitectura-orientada-a-eventos/)

	* **Ruben Padilla** [799022] (1)

		Escuela de JS | Curso de backend con nodejs: [Arquitectura orientada a eventos ](https://platzi.com/clases/1646-backend-nodejs/22016-arquitectura-orientada-a-eventos/)

* **Rafael Guzmán Barranco** (3) [71975](https://platzi.com/comentario/807678/) 
¿Por qué no se a anexado el código de este curso?

	* **ricardocelis (Platzi)** [71975] (3)

		Hola Rafael! Ya reviso muchas gracias por avisar

* **duacos** (2) [992272](https://platzi.com/comentario/992272/) 

	Que geniaaaal!!

* **Yesid Anacona** (2) [882887](https://platzi.com/comentario/882887/) 

	No es clara la forma en la que estructuras el proyecto, en especial con el router, tal vez no es tan necesario separarlos en carpetas tan alejadas.

	* **Jefersson Steven Guevara Sánchez** [882887] (5)

		Hola  
		En la carpeta network tenemos, por el momento dos archivos muy importantes; que no tienen nada que ver con la logica de negocio ó de respuesta.  
		Response.js: Que permite administrar las respuestas de acuerdo a él estatus del servidor a nuestro cliente.  
		y el routes.js: estas configurando a que rutas del servidor tienen acceso.  
		si de repenete quieres, /salasdechat (post, get, delete) deberas agregarlas aqui.  
		en conclusión no son carpetas alejadas son carpetas de servidor que deben ir fuera de nuestro código funcional.

* **Fabio Andres Arango Grajales** (2) [844289](https://platzi.com/comentario/844289/) 

	cuando suben el repositorio

	* **mafevito** [844289] (3)

		Hola Fabio
		
		El repositorio lo encuentras en [este enlace](https://github.com/CodingCarlos/backend-node-platzi)

* **Fernando Cordero** (2) [832625](https://platzi.com/comentario/832625/) 

	mocks (Simulando base de datos)

* **Wilson Castro Medellin** (1) [1115689](https://platzi.com/comentario/1115689/) 

	mocks tiene que ver con TDD?

* **carlosextra1** (1) [1060939](https://platzi.com/comentario/1060939/) 

	esta clase nos da un panorama más amplio de lo que estamos haciendo. Y se va a poner aún mejor cuando se elija una base de datos!!

* **andru2400** (1) [963382](https://platzi.com/comentario/963382/) 

	Que clase de brujería es esta !, no sabia que le llamaban mocks 👍!

* **Alan Santiago** (1) [884802](https://platzi.com/comentario/884802/) 

	¿Cómo se puede agregar un formulario en el frontend para hacer el post? Para que se asemeje más a un chat 😅

* **ivofacundo** (1) [857864](https://platzi.com/comentario/857864/) 

	tengo una duda, lo que el profesor llama “store” seria como el modelo en el patrón MVC? ya que en el modelo es donde esta la logica y las funciones que se conectan con la BD

	* **daag13** [857864] (1)

		En MVC el Store sería una parte del controlador donde tendríamos referenciado el modelo de datos (entity framework), específicamente la parte del acceso a datos. El Store en Node.js se encarga únicamente de la interacción de la base de datos.

* **leonardo-albino** (1) [793241](https://platzi.com/comentario/793241/) 

	Alguien ya ha intentado con una base de datos relacional como Sql server? cuando trato de imprimir mi query con .recordset solo me imprime un array vacío

* **Veronica Castro Barro** (1) [86564](https://platzi.com/comentario/1098789/) 
Al hacer el POST me da el error store.add is not a function. También con el GET me da store.list is not a function ¿Qué me falta?

	* **Anibal Fernando Ortega Piedrahita** [86564] (1)

		Hola puedes adjuntar una imagen de tu código. Esto sucede cuando normalmente cuando la función no queda en el export del modulo.
		``` 
		    module.exports = {
		        add: addMessage,
		        list: getMessage,
		        updateText: updateTextMesssage
		    }
		    
		```
		
		Fijate bien que si la estes exportando.
		
		Saludos

* **MariaGuadalupeGtojr** (1) [77840](https://platzi.com/comentario/910752/) 
Alguien me puede ayudar con este error donde en codigo si tengo definido user… -TypeError: Cannot read property ‘user’ of undefined

	* **Rafael Lozano Rolón** [77840] (1)

		Puedes poner el código para apoyarte

* **johneduardo** (1) [71954](https://platzi.com/comentario/807271/) 
Está bien hecho poner un try/catch en la función addMessage() del controller.js: `const store = require(’./store’); func...

# Utilizar una base de datos para definir, modelar, almacenar y recuperar la información de nuestra aplicación [4535]

## 0180. Tipos de Bases de Datos Relacionales y No Relacionales [22621](https://platzi.com/clases/1689-backend-js/22621-tipos-de-bases-de-datos-relacionales-y-no-relacion/)

### Descripción:


 **Bases de Datos Relacionales:** no es una base de datos muy flexible, pero tiene a favor su gran soporte y el enorme desarrollo en herramientas para su uso. Si necesitamos cambiar un valor de un campo debemos hacerlo con todos los campos de nuestra BD, en cambio con NoSQL o No Relacional no es así.

**Bases de Datos No Relacionales:** son de bases de datos sin una tabla fija como las que sí se encuentran en las bases de datos relacionales, lo que permite una alta escalabilidad en ellas. Además, es abierta y por lo tanto flexible a diferentes tipos de datos y no necesita tantos recursos para ejecutarse; de hecho, el hardware necesario no cuesta mucho.

### Links:

* [MongoDB Hosting: Database-as-a-Service by mLab](https://mlab.com/)

### Comentarios:

* **Nestor David Alvarado Rondon** (13) [732954](https://platzi.com/comentario/732954/) 

	Hola como aporte y escuchando las clases de este excelente profesor.  
	**NoSQL en realidad es (No Only SQL)**  
	Saludos

* **Alan Santiago** (8) [885553](https://platzi.com/comentario/885553/) 
	
	![databases.png](https://static.platzi.com/media/user_upload/databases-ee854eda-c48a-44f1-8276-7fb09a379986.jpg)

* **MartinMB** (5) [977302](https://platzi.com/comentario/977302/) 

	Seria mejor que representara las bases de datos de forma gráfica y sin gestos

	* **Jorge Humberto Nemogá Pinzón** [977302] (1)

		<https://platzi.com/comentario/885553/>

* **Cristobal Vega** (4) [1020530](https://platzi.com/comentario/1020530/) 

	Dato curioso: La palabra NoSQL viene del acrónimo “Not Only SQL”, el “No” no es una negación de SQL.

* **mariiglesia** (4) [68317](https://platzi.com/comentario/738654/) 
Entonces para aplicaciones grandes conviene usar Mongo (NoSQL) en vez de Postgres?

	* **Jair Israel Avilés Eusebio** [68317] (7)

		Depende, no necesariamente, son muchos factores a considerar como
		
		* Lenguaje
		* Escalabilidad
		* Estructura y alcande de tu aplicacion
		
		

* **sergio-medina93** (3) [907106](https://platzi.com/comentario/907106/) 

	¡Interesante! Un compañero me dice que hacer búsquedas con MongoDB es una mamera y difícil pero ahora veo que es una muy buena opción cuando las bases de datos tienden a cambiar mucho.

* **Sebastian Cardoso Castillo** (3) [742272](https://platzi.com/comentario/742272/) 

	¿Es muy complicado migrar datos de Mongo a una base de datos relacional?

	* **Juan David Castro (Platzi)** [742272] (3)

		Nah. No es complicado. Busca en Google algo como “MongoDB to {la base de datos relacional de tu preferencia}” y encuentras bastante información. 😉
		
		También encontré esta herramienta para conversiones generales. Se ve muy bien.
		
		👉 [Export Wizard: How to MongoDB Export to CSV, JSON, SQL, BSON and other formats](https://studio3t.com/knowledge-base/articles/mongodb-export-csv-json-sql-bson/)

* **Wilson Castro Medellin** (1) [1120487](https://platzi.com/comentario/1120487/) 

	SQL=>Basada en tablas, NoSQL=>Basada en documentos, en clave-valor, relaciones entre nodos

* **Abraham Flores Cosme** (1) [1072010](https://platzi.com/comentario/1072010/) 

	En ocasiones escalar una base de datos en MySQL llega a ser muy tedioso cuando tienes una aplicación compleja y veo o por lo que he leido MongoDB suele ser sencillo de uso, ya lo veremos, excelente clase.

* **carlosextra1** (1) [1061163](https://platzi.com/comentario/1061163/) 

	Por lo regular las bases de datos relacionales bien hechas siempre tienen efecto en cadena!

* **Sebastián Pineda Duque** (1) [878254](https://platzi.com/comentario/878254/) 

	En vez de que el profesor explique con las manos haciendo señas, sería mejor que lo explicara de forma gráfica.

	* **Pablo Gabriel Mederos Caballero** [878254] (2)

		Esta muy bien explicado.

	* **Emanuel Valero** [878254] (2)

		Está perfectamente explicado. Todo se entiende claramente 😃

	* **Juan José Vega Quintero** [878254] (1)

		<https://platzi.com/comentario/885553/>

## 0190. Crear y Configurar tu Base de Datos con MongoDB [23491](https://platzi.com/clases/1689-backend-js/23491-crear-y-configurar-tu-base-de-datos-con-mongodb/)

### Descripción:


 **MongoDB compró mLab.**

**MongoDB Atlas** es un servicio de bases de datos como servicio que nos permite configurar nuestras bases de datos para entornos de pruebas o producción con diferentes proveedores de nube. Además de todas sus características, Atlas se destaca por ser un servicio mantenido oficialmente por el equipo que desarrolla MongoDB.

**mLab** también era un servicio de bases de datos con Mongo. Pero fue adquirido por MongoDB a inicios del 2019 para darle más fuerza a MongoDB Atlas y unir fuerzas con el anterior equipo de mLab.

* [MongoDB comprará mLab y su servicio de base de datos en la nube](https://www.silicon.es/mongodb-comprara-mlab-y-su-servicio-de-base-de-datos-en-la-nube-2383965)



## Usa MongoDB Atlas en lugar de mLab

Durante el curso usamos mLab para crear nuestra base de datos con MongoDB. Pero el servicio ya no está disponible, así que te recomendamos seguir esta clase para configurar tu base de datos con MongoDB Atlas:

* [Creación de una BD en MongoAtlas](https://platzi.com/clases/1646-backend-nodejs/22033-creacion-de-una-bd-en-mongoatlas/)



Nuestro código no cambiará mucho. De hecho, puede que no cambie nada. Solo debes recordar que los nombres de tus bases de datos y clusters deben ser los mismos en el servicio de Atlas y en tu código.

### Comentarios:

* **RafaelEchart** (7) [832362](https://platzi.com/comentario/832362/) 

	cual es la principal diferencia entre este curso y el Curso de Backend con Node.js de Guillermo Rodas, que esta en la linea de aprendizaje de Javasacript?

	* **Nicolasdds** [832362] (5)

		Yo también quiero saber

	* **Alejo Goncalves** [832362] (9)

		Yo empece con el de backend con nodeJS y no entendía nada…  
		Asi que busque y encontré este que creo vendría a ser el paso inicial

	* **RafaelEchart** [832362] (5)

		Hola companeros, no soy experto en el tema(Aun no termino el curso) pero de lo que tengo entendido es que Este curso de Backend con NodeJs se utiliza otra base de datos que vendria a ser la anterior a MONGODB ATLAS, aqui se usa Mlab y ese servicio ya esta descontinuado, pero el funcionamiento de conexion es el mismo…
		
		Tambien he leido comentarios sobre que el otro curso es mejor, supongo que es porque es mas actualizado y creo que usan Platzi Live como ejemplo de contruccion, asi que tal vez es mas entendible.
		
		Termino este y voy al curso de Backend con Javascript, saludos!!

	* **edwintrumpet** [832362] (8)

		Yo hice primero el de Guillermo Rodas porque seguí todos los cursos de la carrera de Javascript y es muy bueno, pero tal vez si no se sabe nada de node.js este sea mejor para empezar porque veo que es más básico.  
		En el de Guillermo Rodas se ven aspectos más profundos de Node.js

	* **th3_bu6** [832362] (3)

		Yo tome ambos cursos. y este curso es un poco mas basico. Lo que cambia principalmente es que la estructura que proponen los profesores es diferente pero a su vez los conceptos son los mismos. A mi en lo personal me gusta mas la forma en la que la estructura Guillermo Rodas pero aun asi recomiento tomar este curso primero ya que es un poco mas basico y el de guillermo rodas para complementar.( el de guillermo rodas lo recomiendo sobre todo si se va a hacer toda la escuela de javascript ya que es un proyecto enorme en el que se manejan todos los conceptos basicos de javascript y despues se aprende frontend y backend )

* **Wilson Castro Medellin** (1) [1120533](https://platzi.com/comentario/1120533/) 

	Contenido bloqueado. Como puedo ver esta clase

* **carlosextra1** (1) [1061110](https://platzi.com/comentario/1061110/) 

	Ya todo listo, Vamos al curso!!

## 0200. MongoDB I Almacenar y leer datos [22622](https://platzi.com/clases/1689-backend-js/22622-mongodb-i-almacenar-y-leer-datos/)

### Descripción:


En esta clase vamos a utilizar `mongoose` para crear los esquemas de nuestra base de datos. También utilizaremos [mLab](https://mlab.com) como nuestra base de datos.

### Links:

* [MongoDB Hosting: Database-as-a-Service by mLab](https://mlab.com/)

### Comentarios:

* **mglBrv** (12) [923374](https://platzi.com/comentario/923374/) 

	Para quienes tuvieron problemas con la conección a la db:  
	.  
	Mongoose no funciona con la uri que nos entrega mongodb atlas por defecto (mongodb+srv). Cuando le las click a ‘Connect Yout Aplication’ en las sección (1) Choose your driver version hay que seleccionar la versión de node 2.2.12 or later  
	.  
	Además le agregué un catch (mas otras cosas) a connect().  
	.  
	El código de esa parte quedó así:  
	.  
	.  
	store.js
	``` 
	    const db = require('mongoose');
	    const Model = require('./model');
	    
	    const uri =
	      'mongodb://<user>:<pass>@<cluster_primary>,<cluster_secondary>/<nombre_de_la_coleccion>?ssl=true&replicaSet=Main-shard-0&authSource=admin&retryWrites=true';
	    
	    db.Promise = global.Promise;
	    
	    db.connect(uri, { useNewUrlParser: true, useUnifiedTopology: true })
	      .then(() => console.log('[db] Conectada con éxito'))
	      .catch(err => console.error('[db]', err));
	    
	    functionaddMessage(message) {
	      const myMessage = new Model(message);
	      myMessage.save();
	    }
	    
	    functiongetMessages() {
	      returnlist;
	    }
	    
	    module.exports = {
	      add: addMessage,
	      list: getMessages,
	      //get
	      // update
	      // delete
	    };
	    
	```

	* **Luis Alberto Colunga Pérez** [923374] (1)

		Buen aporte!!!

	* **caprilespe** [923374] (1)

		Gracias por tu aporte, me ayudo mucho, saludos.

	* **Andrés Campuzano Garzón** [923374] (1)

		Muchas gracias!

	* **Andrés Campuzano Garzón** [923374] (1)

		Obtengo el error de “list is not defined” al hacer el GET, lo cual tiene sentido si el array de list se eliminó. ¿Como lo soluciono?

	* **Andrés Campuzano Garzón** [923374] (1)

		Ya lo he solucionado. Gracias.

* **santiagoharkes** (9) [728779](https://platzi.com/comentario/728779/) 

	Hola! Me salía un error en la consola que decía: ReferenceError: Model is not defined.
	
	Luego de unos minutos de inspeccionar el código me di cuenta que era debido a que habíamos exportado Model pero nunca lo habíamos importado en store.js y lo estabamos queriendo usar.
	
	Me parecía raro ya que en el video en ningún momento se había importado, aunque sí se hizo y por algún error de edición no salió (minuto 10.23)
	
	Para importarlo en store.js, sólo hay que escribir la siguiente línea:  
	const Model = require(’./model’)

	* **j0e** [728779] (1)

		Buena observación, a mi no me guardaba los datos en la base de datos y tampoco me salia ningún error ya me estaba estresando.

	* **Chrystian Fabian Lozano Ramirez** [728779] (1)

		#ASICIERTO

* **osk1dav** (7) [1004926](https://platzi.com/comentario/1004926/) 

	En cuanto al codigo de la clase lo unico que agregue fue el nombre de la base de datos y me funciono.
	``` 
	    const db = require('mongoose');
	    const Model = require('./model');
	    
	    db.Promise = global.Promise;
	    // mongodb+srv://db_user_platzi_videos:ruW7PhuMMamTE6C4nNYUQ7Mv@compudavdb-5sh8c.mongodb.net/test?retryWrites=true&w=majority
	    db.connect('mongodb+srv://db_user_platzi_videos:ruW7PhuMMamTE6C4nNYUQ7Mv@compudavdb-5sh8c.mongodb.net/test?retryWrites=true&w=majority', {
	        useNewUrlParser: true,
	        useUnifiedTopology: true,
	        dbName: 'telegrom'
	    });
	    
	    console.log('[db] conectada con exito');
	    
	    functionaddMessage(message) {
	        // list.push(message);
	        const myMessage = new Model(message);
	        myMessage.save();
	    }
	    
	    asyncfunctiongetMessages() {
	        // return list;
	        const messages = await Model.find();
	        return messages;
	    }```
	    
	```

	* **Julián Fernando Amaya Díaz** [1004926] (1)

		Gracias, también me funcionó agregando el dbName.

	* **Alfonso Navarro** [1004926] (1)

		gracias por tu aporte…

	* **Alvaro Rojas** [1004926] (1)

		También me funciono, muchas gracias

	* **Mariana Valencia** [1004926] (1)

		Héroe

	* **Agustin_Moran** [1004926] (1)

		Gracias compañero, muy valioso tu aporte

	* **Rodrigo Josué Hernández Barrios** [1004926] (1)

		Gracias por el aporte, muy importante importar el Model y también colocar lo ‘useUnifiedTopology’, con esto ya deja mandar el mensaje sin problemas, en mi caso no fue colocarle el ‘dbName’ abajo,  
		Saludos,

* **lizardojara** (6) [834713](https://platzi.com/comentario/834713/) 

	Dejo el codigo de store.js para ayudar a los nuevos
	``` 
	    const db = require("mongoose")
	    const Model = require('./model')
	    
	    db.Promise = global.Promise
	    db.connect('mongodb+srv://<user>:<password>@cluster0-yjahj.mongodb.net/<database>?retryWrites=true&w=majority',{
	        useNewUrlParser: true,
	        useUnifiedTopology: true
	    })
	    
	    console.log("[db] Conectada con exito")
	    
	    const addMessage = message => {
	        const myMessage = new Model(message)
	        myMessage.save()
	    }
	    
	    const getMessage = async () => {
	        returnawait Model.find()
	    }
	    
	    module.exports = {
	        add: addMessage,
	        list: getMessage,
	        //get
	        //update
	        //delete
	    }```
	    
	```

	* **sergio-medina93** [834713] (1)

		¡Muchas gracias! npm me aconsejaba usar useUnifiedTopology: true porque el que aconseja el profe está por expirar.

* **Alejandro_** (5) [893722](https://platzi.com/comentario/893722/) 

	Si tienen problemas al realizar la conexión con mongo lo pueden hacer de la siguiente manera.
	``` 
	    db.Promise = global.Promise;
	    const options = {
	        keepAlive: 1,
	        useUnifiedTopology: true,
	        useNewUrlParser: true,
	    };
	    db.connect('mongodb+srv://userdb:password@url?retryWrites=true&w=majority', options)
	        .then(() =>console.log('DB connected'))
	        .catch((err) => {
	            console.log(err);
	        });
	    
	```

* **Carlos Bueno Tavares** (5) [734079](https://platzi.com/comentario/734079/) 

	chicos el problema del TypeError: Cannot read property ‘model’ of undefined, lo que succede es que al parecer mongoose tiene algun tipo de bug y no esta funcionando el codigo de siempre para que les funcione primero:
	
	declaren const model = require(‘mongoose’).model
	
	y para exportar:
	
	module.exports = model.call(require(‘mongoose’),‘modelName’, mySchema)

* **havelka** (4) [1009624](https://platzi.com/comentario/1009624/) 

	npm i mongoose

* **Carlos Miguel Briceño Garcia** (3) [980171](https://platzi.com/comentario/980171/) 

	Obviamente debe haber una forma mejor, pero despues de tanto dar asi fue como logre conectarme al servidor de atlas mongodb para poder continuar la clase.
	``` 
	    const Model = require('./model');
	    const MongoClient = require('mongodb').MongoClient;
	    const uri = 'mongodb+srv://Telegrom:password@cluster0-wfgof.mongodb.net/TelegromDB?retryWrites=true&w=majority'
	    const client = new MongoClient(uri, { 
	      useNewUrlParser: true,
	      useUnifiedTopology: true,
	    });
	    
	    functionaddMessage(message) {
	      client.connect(err => {
	        const collection = client.db('TelegromDB').collection('chat');
	        const myMessage = new Model (message);
	        collection.insertOne(myMessage, err =>{
	          // console.log(collection)
	          console.log("Mensage guardado")
	        })
	      });
	      client.close();
	    }```
	    
	```

	* **Carlos Miguel Briceño Garcia** [980171] (2)

		actualizando un poco el post pasado, se me complico para conseguir leer los datos en atlas mongodb, pero despues de intentar varias formas, la que consegui que funcionara fue esta, solo faltaria ver si se puede optimizar un poco.
		``` 
		    const getMessages = (callback) => {
		      returnnew Promise((resolve, reject) => {
		        client.connect((err, callback) => {
		          return client.db('TelegronDB').collection('chat').find({}).toArray((err, callback) => {
		              resolve(callback)
		            })
		          })
		        client.close()
		      })
		    }```
		    
		```

	* **duacos** [980171] (1)

		¿Por qué es esta una forma mejor?

* **raparisg** (3) [935268](https://platzi.com/comentario/935268/) 

	El método para agregar no se hizo con una promesa. ¿Por qué?

	* **duacos** [935268] (1)

		Buena pregunta

* **Sebastián Pineda Duque** (3) [904034](https://platzi.com/comentario/904034/) 

	En el minuto **10:19** , el profesor añade el require de _Model_ sin explicarlo. Puede generar confusión a la hora de hacer un GET, porque si no se importa ese módulo, se ejecuta el response.error.

* **Ruben Padilla** (3) [844335](https://platzi.com/comentario/844335/) 

	👋
	
	Para aquell@s que tenga dificultades con la creación de la base de datos en MongoDB pueden seguir estos pasos e introducirlos en el flujo de su proyecto.
	
	* [Creacion de una base de datos en MongoDB](https://platzi.com/clases/1646-backend-nodejs/22033-creacion-de-una-bd-en-mongoatlas/)
	
	* [Conexión a MongoAtlas una instancia de MongoDB](https://platzi.com/clases/1646-backend-nodejs/22035-conexion-a-mongoatlas-una-instancia-de-mongodb/)
	
	
	
	
	Saludos.

* **_jrgarciadev** (3) [809247](https://platzi.com/comentario/809247/) 

	La estructura el proyecto me parece desordenada, no se separa por objetivos, en de la Escuela de Js tiene mejor estructura

* **Emanuel Valero** (2) [1056685](https://platzi.com/comentario/1056685/) 

	Como mLab ahora forma parte de atlas, comparto aca la manera de realizar la conexión una vez que la base de datos ha sido creada:
	``` 
	    const user =user';
	    const pass = 'user1234';
	    const host = myCluster.mongodb.net';
	    const database = 'dbName';
	    const uri = `mongodb+srv://${user}:${pass}@${host}/${database}?retryWrites=true&w=majority`;
	    
	    db.Promise = global.Promise;
	    db.connect(uri, { useNewUrlParser: true, useUnifiedTopology: true })
	    	.then(() => {
	    		console.log('[db connection] Database connected')
	    	})
	    	.catch( error => {
	    		console.error('[db connection] Connection failed', error.message) 
	    	});
	    
	```

* **Guillermo Casanova** (2) [994225](https://platzi.com/comentario/994225/) 

	Si alguien tiene problemas con conectar a la base de datos, probablemente sea por las versiones. Si a alguien le interesa, yo lo solucioné conectando a un servidor local de MongoDB, solo descarguen MongoDB del sitio oficial, es gratis. Para la visualización pueden descargar Compass desde la misma página, también es gratuito. El código que conecta con la base de datos local es el siguiente:
	``` 
	    uri='mongodb://127.0.0.1/<database_name>'
	    db.Promise = global.Promise;
	    
	    db.connect(uri, { useNewUrlParser: true, useUnifiedTopology: true })
	      .then(() =>console.log('[db] Connected successfully'))
	      .catch(err => console.error('[db]', err));
	    
	```

	* **Iván Darío Sánchez Jiménez** [994225] (1)

		Para los usuarios en Bogotá puede haber problemas si tienen ETB como ISP no permite conexiones con MongoDB Atlas, se requiere el uso de una VPN

* **mrcMesen** (2) [982896](https://platzi.com/comentario/982896/) 

	Me gusta mucho el curso, en este momento quisiera saber si mongoose aun continua siendo necesario, es decir, ¿estas funciones no está todavía como parte nativa al instalar mongodb?  
	Si el profe ve los comentarios quisiera saber, sino algún compañero con un poco más de experiencia, les agradezco pura vida!

	* **Cristobal Vega** [982896] (3)

		Hola!, Aquí valdría la pena definir que es Mongoose, se le conoce como ODM (Object Document Model) es algo similar a otros ORM en el mundo de SQL (Hibernate siendo el más popular en el mundo de Java).
		
		Los ORM nos ayudan a comunicar mejor nuestros schemas con la BD, de igual manera puedes siempre usar el Driver directo de MongoDB de igual manera que en el mundo de Java puedes usar directamente el JDBC.
		
		Espero haber dejado más aclaraciones que dudas jeje 🤓

* **Víctor Santiago Ruiz** (2) [903380](https://platzi.com/comentario/903380/) 

	No puedo ingresar a mLab con la cuenta de Mongo DB Atlas.
	
	Ayuda!

* **Gtiseira** (2) [855062](https://platzi.com/comentario/855062/) 

	No comprendo según la lectura anterior debemos hacer nuestra base de datos en <https://www.mongodb.com/cloud/atlas> pero desde aca nos muestra como hacerlo en <https://mlab.com/>  
	Segui lo que me decia el articulo anterior y no puedo hacer la conexion de mi base de datos con lo programado en esta clase!

	* **José Pach Delgado** [855062] (1)

		Rayos, deberían darle mantenimiento a este curso.

	* **maxialvarezm** [855062] (1)
En el texto anterior indica que puede variar muy poco , y se resalta que la clase esta con mongo mlab, pero nosotros mismos deberías adaptarla para mongodb atlas

	* **cesar88** [855062] (1)

		yo lo hice mirando este video y el del otro curso que dejan en la lectura anterior y me resulto sencillo, varia muy poco…

* **leonardo-albino** (2) [847286](https://platzi.com/comentario/847286/) 

	Por el momento hay un control de flujo en el archivo controller.js que se encarga de verificar que haya un mensaje y un usuario en cada mensaje enviado, ahora también se puede hacer desde la base de datos con la opción required, mi pregunta es la siguiente: ¿Cual de las dos formas me asegura que no entre información indeseada a la base de datos? y ¿Cual de ellas es la mejor forma de validar esta información?

* **Nicolasdds** (2) [839283](https://platzi.com/comentario/839283/) 

	Para los que no han conseguido hacer esto debido a la mala organización del curso, deben crearse una cuenta en MongoDB Atlas, hacen todos los pasos de este video y luego se descargan en Mongo Compass donde van a poder ver y administrar los datos que se van almacenando, la base de datos por defecto es “test”… Luego debería andar todo 200.

* **JUAN SILVA** (2) [778346](https://platzi.com/comentario/778346/) 

	para que saliera sin errores, hice esta conexión con la ultima versión de mongodb que es mongo 3.6.3 ademas agregue un catch para el caso de que no sirva la conexión y se evite un loop
	``` 
	    db.connect(`mongodb+srv://<user>:<pasword>@
	        <port>/telegram?retryWrites=true&w=majority`,
	        { useNewUrlParser: true, useUnifiedTopology: true  })
	            .then(()=>{
	                console.log('[db]Conectada con exito')
	            }).catch(error=> console.error(Error))  ```
	    
	```

* **Carlos Alex Becerra Chavita** (2) [729729](https://platzi.com/comentario/729729/) 

	Buenos dias alguien me puede explicar esto que esta lanzando mongodb desde windows no se si pasa lo mismo desde otros sistemas operativos la advertencia es la siguiente:
	
	`Deprecation Warning: current Server Discovery and Monitoring engine is deprecated, and will be removed in a future version. To use the new Server Discover and Monitoring engine, pass option { useUnifiedTopology: true } to the MongoClient constructor.`
	
	alguien sabe algo del tema que no entendi muy bien los que tenemos nuestros servidores locales espero me aclaren que pasa gracias.

	* **Edward Orlando Hurtado** [729729] (1)

		Estoy teniendo este problema tambien.
		``` 
		    (node:19560) DeprecationWarning: current Server Discovery and Monitoring engine isdeprecated, and will be removed in a future version. To use the new Server Discover and Monitoring engine, pass option { useUnifiedTopology: true }to the MongoClient constructor.```
		    
		```

	* **Favio Sauto** [729729] (7)

		Sucede si tienes la versión 3.2.1 o superior de mongo, simplemente tienes que agregar al connect el useUnifiedTopology: true, así:
		``` 
		    db.connect('mongodb+srv://<username>:<password>@<mongo-cluster>/<db>', {
		      useNewUrlParser: true,
		      useUnifiedTopology: true,
		    });
		    
		```
		
		Encontré más información en la documentación oficial, lo único es que está en inglés, si quieres leerla [este es el link](https://github.com/mongodb/node-mongodb-native/releases/tag/v3.2.1).

	* **Edward Orlando Hurtado** [729729] (3)

		Logre solucinar el problema, tienes que agregar lo que dijo Favio y ademas de eso, en Atlas vas a Network Acess y agregas tu direccion ip a la white list

	* **Juan mora** [729729] (2)

		gracias por el aporte @Favio Sauto

	* **Sebastian Cardoso Castillo** [729729] (1)

		Gracias Favio

* **Gustavo Adrian Moreno Becoche** (2) [68295](https://platzi.com/comentario/738235/) 
La página mlab no se ve tal cual el ejemplo en la fecha actual… Me re-dirige a un sitio llamado https://cloud.mongodb....

	* **Carlos Hernández** [68295] (2)

		Si, MongoDB ha comprado mlab. Ellos tienen un servicio igual llamado Atlas.  
		.  
		Un cluster es un grupo de máquinas que funcionan como si fuese una sola. Es exactamente lo mismo. La URL de conexión es distinta, pero no pasa nada, debería funcionar igual.  
		.  
		Puedes revisarlo en [la documentación de MongoDB](https://docs.mongodb.com/manual/reference/connection-string/), o en [la guia que han publicado para migrar](https://docs.mlab.com/mlab-to-atlas/).

* **Edward Orlando Hurtado** (2) [67917](https://platzi.com/comentario/731108/) 
Podrian hacer un tutorial de Mlab pero con la pagina de MongoDB ya que Mlab fue comprada por MongoDB

	* **Jair Israel Avilés Eusebio** [67917] (1)

		Con solo saber MongoDB es mas que suficiente, ya que mLab es un servicio cloud para crear este tipo de base de datos como servicio. De igual forma ellos comentan que es mejora migrar a Mongo Atlas.

* **Wilson Castro Medellin** (1) [1120619](https://platzi.com/comentario/1120619/) 

	Muy bien todo. Pero puede mejorarse la forma de conexión?

* **Juan Teixeira** (1) [1119187](https://platzi.com/comentario/1119187/) 

	Me estaba volviendo loco por un error.
	
	A la final era que en el store.js había que traer el modulo de model.
	
	const Model = require(’./model’);
	
	Por si a alguien más le pasa esto.

* **Abraham Flores Cosme** (1) [1072142](https://platzi.com/comentario/1072142/) 

	Muy interesante saber que no es necesario crear manualmente la colección sino que automáticamente al insertar el primer registro esta es generada.

* **carlosextra1** (1) [1061876](https://platzi.com/comentario/1061876/) 

	my store.js
	``` 
	    const db = require('mongoose');
	    const Model =  require('./model');
	    
	    db.Promise= global.Promise;
	    db.connect('mongodb+srv://db_user_node:453434343c8s@cluster0-6qvbh.mongodb.net/test?retryWrites=true&w=majority', {
	        useNewUrlParser: true,
	        useUnifiedTopology: true
	    });
	    
	    console.log('[db] Conectada con el server db');
	    
	    functionaddMessage(message) {
	        const myMessage = new Model(message);
	        myMessage.save();
	    }
	    
	    asyncfunctiongetMessages() {
	        const message = await Model.find();
	        return message; 
	    }
	    
	    module.exports = {
	        add: addMessage,
	        list: getMessages
	    }```
	    
	```

* **jlcoronel** (1) [1055370](https://platzi.com/comentario/1055370/) 

	He seguido todos los pasos, en insomnia me aparece el siguiente mensaje
	``` 
	    {
	      "error": "Información inválida",
	      "body": ""
	    }
	    
	```
	
	En el console log me muestra el siguiente mensaje
	``` 
	    [response error] Erroren el control
	    
	```
	
	Le agregué a router.post en .catch la impresión de la variable e console.log en el archivo network.js y me muestra el siguiente mensaje
	``` 
	    ReferenceError: Model is not defined
	        at Object.addMessage [as add] (C:\Users\jlcoronel\Documents\Node\BackendNode\components\message\store.js:13:23)
	        at C:\Users\jlcoronel\Documents\Node\BackendNode\components\message\controller.js:18:15
	        at new Promise (<anonymous>)
	        at Object.addMessage (C:\Users\jlcoronel\Documents\Node\BackendNode\components\message\controller.js:4:12)
	        at C:\Users\jlcoronel\Documents\Node\BackendNode\components\message\network.js:17:16
	        at Layer.handle [as handle_request] (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\layer.js:95:5)
	        at next (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\route.js:137:13)
	        at Route.dispatch (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\route.js:112:3)
	        at Layer.handle [as handle_request] (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\layer.js:95:5)
	        at C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\index.js:281:22
	        at Function.process_params (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\index.js:335:12)
	        at next (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\index.js:275:10)
	        at Function.handle (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\index.js:174:3)
	        at router (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\index.js:47:12)
	        at Layer.handle [as handle_request] (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\layer.js:95:5)
	        at trim_prefix (C:\Users\jlcoronel\Documents\Node\BackendNode\node_modules\express\lib\router\index.js:317:13)
	    [response error] Error en el controlador
	    
	```
	
	Mi funcion de conexion a la bd la modifiqué a
	``` 
	    db.Promise = global.Promise;
	    db.connect('mongodb+srv://<user>:<contraseña>@curso-platzi-eu1qo.mongodb.net/test?retryWrites=true&w=majority', {
	        useNewUrlParser: true,
	        useUnifiedTopology: true,
	    });
	    console.log('[db] Conectada con éxito');
	    
	```
	
	Pintaba bien el ejemplo pero así…

	* **José Enrique Pérez Aquino** [1055370] (1)

		No importaste la funcion model

* **zambombas** (1) [1052095](https://platzi.com/comentario/1052095/) 

	Podarais actualizar un poco ya que la instalación ha quedado obsoleta.

* **LuisViGo** (1) [1022780](https://platzi.com/comentario/1022780/) 

	No entiendo este error, ya verifique usuario y contraseña.
	
	(node:17968) UnhandledPromiseRejectionWarning: MongooseServerSelectionError: bad auth Authentication failed.
	``` 
	    db.Promise = global.Promise
	    db.connect('mongodb+srv://admin:<admin1234>@platzichat-juqhn.mongodb.net/test?retryWrites=true&w=majority', {
	        useNewUrlParser: true,
	        useUnifiedTopology: true,
	        dbName: 'PlatziChat'
	    })```
	    
	```

	* **Rootexploits** [1022780] (3)

		Buenas !! creo que es por los <contraseña>, tienes que quitarlos y dejar solo la contraseña.
		
		Ami me funciono sin los signos <>
		
		Un saludo !!

* **Mariana Valencia** (1) [1022531](https://platzi.com/comentario/1022531/) 

	En el video se corta pero recuerden importar el Model. Si hacen esto y ponen el nombre de su db como indica osk1dav, todo da perfecto

* **MartinMB** (1) [977310](https://platzi.com/comentario/977310/) 

	Que forma mas fea de ordenar los archivos y carpetas

	* **duacos** [977310] (2)

		¿Por qué es fea? solo se amolda a la estructura definida al principio

* **israelhuaman** (1) [958305](https://platzi.com/comentario/958305/) 

	npm i mongoose

	* **Alfonso Navarro** [958305] (1)

		gracias caballero

* **Cesar Pelaez** (1) [895536](https://platzi.com/comentario/895536/) 

	Por favor ayuda!! hice la conexion tal cual en el video, no me genera ningun error pero a la hora de generar el post me dice que los datos estan incompletos y el metodo get dejo de funcionar, solo arroja el error, esto sucedio luego de añadir el codigo de conexion a la base de datos.

	* **William Eduardo Meza** [895536] (1)

		¿Cual error te arrojó?

* **george-montenegro** (1) [890040](https://platzi.com/comentario/890040/) 

	Buenas noches me podrian ayudar con este error:  
	Error: querySrv EREFUSED _mongodb._tcp.cluster0-2ijul.mongodb.net  
	at errnoException (dns.js:50:10)  
	at QueryReqWrap.onresolve [as oncomplete] (dns.js:238:19)  
	code: ‘EREFUSED’,  
	errno: ‘EREFUSED’,  
	syscall: ‘querySrv’,  
	hostname: ‘_mongodb._tcp.cluster0-2ijul.mongodb.net’ }

* **ERNESTOANALISIS** (1) [881104](https://platzi.com/comentario/881104/) 

	Hola comunidad, por favor ayuda. Asigne el usuario y password de la bd MONGODB ATLAS, aparece este mensaje
	
	[nodemon] restarting due to changes…  
	[nodemon] starting `node server.js`  
	[db] Conectada con exitos  
	La aplicacion esta escuchando en 3000  
	**[response error]Error en el logeo**

	* **Luis Jeanpier Monserrate** [881104] (1)

		puedes pasar captura de tu codigo donde conectas con la base de datos? para tener mejor idea de lo que pasa

* **ivofacundo** (1) [858480](https://platzi.com/comentario/858480/) 

	tengo una duda como es que se conecta a la base de mongo desde el archivo store, si este archivo solo es llamado si se hace una peticion por POST o GET

* **RafaelEchart** (1) [834600](https://platzi.com/comentario/834600/) 

	Hola comunidad, tengo una duda muy urgente sobre la conexion de la base de datos y esta clase, en la clase anterior te redirige a un video del curso “Backend con Javascript” ya que en este se usa Mlab y este ya no esta disponible, pero en Mongo DB Atlas en connect te da 3 opciones con 3 links diferentes, y ninguno se parece al de este video…
	
	Todo funcionaba perfecto con el mock, guardaba los mensajes en el array de prueba y todo funcionaba correctamente…
	
	Adjunto mi codigo, de store.js y el log de mi terminal al trata de hacer un post de un mensaje…
	
	LINK: [flickr.com/photos/185642399@N02/](http://flickr.com/photos/185642399@N02/)?
	
	PD: AYUDENME PORFAVOR ESTOY ESTANCADO 😦

	* **lizardojara** [834600] (1)

		Es posible que tu base de datos no exista o tu username/password este incorrecto, verifica eso.

	* **Luis Jeanpier Monserrate** [834600] (1)

		amigo debes seleccionar la opción conectar con tu aplicación, ese es el link que usaras con node, debes colocar en tu codigo algo tal que así: mongodb+srv://platzi:password@curso-platzi-mongodb-gxkjo.mongodb.net

* **Kevin William Roberts Costa** (1) [831371](https://platzi.com/comentario/831371/) 

	10:48 hay un salto en el que getMessages() pasa de devolver list a devolver “list” y es justo un error que tengo no entiendo

	* **jonathan2138** [831371] (1)

		Puedes enviar que error te aparece para revisar

* **Sebastian Castillo** (1) [808301](https://platzi.com/comentario/808301/) 

	Me sale esto y no lo he podido solucionar
	
	(node:9984) UnhandledPromiseRejectionWarning: Error: queryTxt ETIMEOUT [castillo-phuxs.mongodb.net](http://castillo-phuxs.mongodb.net)  
	at QueryReqWrap.onresolve [as oncomplete] (dns.js:202:19)  
	(node:9984) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). (rejection id: 1)  
	(node:9984) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.

	* **Abraham Serrano Montiel** [808301] (1)

		¿Lo lograste solucionar?

	* **Sebastian Castillo** [808301] (1)

		No. Creé una cuenta nueva desde cero, con otro correo y tampoco me funcionó. Desactivé el firewall, y tampoco.
		
		Leyendo el error fíajte que dice “This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). (rejection id: 1)”, pero yo si estaba utilizando un catch.
		
		Otra cosa que no me funcionó fue conectar compass, me devuelve queryTxt ETIMEOUT
		
		Finalmente decidí continuar el curso con mongo en localhost.
		
		Coméntame si conoces este tipo de error, porfavor
		
		Saludos.

	* **jesusgomez12** [808301] (1)

		Tenía el mismo problema, me lanzaba ese mismo error por la consola, pero en mi caso era porque no estaba definiendo bien la contraseña de la base de datos. Lo corregí en el código y todo funcionó bien.

	* **Alejandro_** [808301] (1)

		Este error es debido a que Express no admite promesas, todos los catch deben ser manejados manualmente y se soluciona modificando nuestras rutas de network.js
		
		El codigo se debería ver parecido a esto
		``` 
		    router.post('/', (req, res) => {
		        controller.addMessage(req.body.user, req.body.message)
		            .then((fullMessage) => {
		                response.success(req, res, 201, fullMessage);
		            })
		            .catch(e => {
		                next(e);
		            });
		    });
		    
		```
		
		Donde en vez de responder la promesa agregamos el next.

	* **Alejandro_** [808301] (1)

		Encontre una solución más eficiente y es hacer la conexión de la siguiente manera:
		``` 
		    db.Promise = global.Promise;
		    const options = {
		        keepAlive: 1,
		        useUnifiedTopology: true,
		        useNewUrlParser: true,
		    };
		    db.connect('mongodb+srv://userdb:password@url?retryWrites=true&w=majority', options)
		        .then(() =>console.log('DB connected'))
		        .catch((err) => {
		            console.log(err);
		        });
		    
		```

* **cmarialatincloud** (1) [767385](https://platzi.com/comentario/767385/) 

	Consulta, ¿No es mas sencillo realizar la conexión a la Mongo dentro del archivo Server.js o en una archivo a parte database.js y lo requerís en server.js y listo?

	* **Sebastian Cardoso Castillo** [767385] (1)

		Eso se hace mas adelante

* **Jorge Betancur** (1) [765897](https://platzi.com/comentario/765897/) 

	Me sale el siguiente error:
	
	_"(node:14594) UnhandledPromiseRejectionWarning: MongoError: not authorized on admin to execute command { insert: “messages”, documents: [[{_id ObjectIdHex(“5d9690f48896f23902f0d91b”)} {user Jorge} {message Mundo} {date 2019-10-04 00:23:16.566 +0000 UTC} {_ _v 0}]], ordered: true, writeConcern: { w: “majority” }, lsid: { id: {4 [73 229 42 243 246 179 74 56 130 106 240 236 73 10 141 6]} }, txnNumber: 1.000000, $clusterTime: { clusterTime: 6743736848205480018, signature: { hash: [121 108 141 238 86 200 14 40 34 142 227 45 248 135 146 62 166 12 113 150], keyId: 6743529190831685632.000000 } }, $db: “admin” } "_

	* **Jorge Betancur** [765897] (2)

		Ya lo solucione me toco agregar lo siquiente: {dbName:‘telegrom_db’} a la conexión

	* **Sebastian Castillo** [765897] (1)

		en que parte del string lo hiciste?.

* **Jvllian** (1) [733716](https://platzi.com/comentario/733716/) 

	Buen día,
	
	Solicito su ayuda con el siguiente error:
	
	ReferenceError: Model is not defined  
	at Object.addMessage [as add] (…\backendNode\components\message\store.js:12:23)
	``` 
	    functionaddMessage(message){
	        
	        const myMessage = new Model(message);
	        myMessage.save();    
	    }```
	    
	    La linea 12 es la misma del vídeo.
	    
	    Gracias.
	```

	* **Juan mora** [733716] (1)

		Mi primera impresión es que falta un espacio entre function y el nombre de la function

	* **edanfesi** [733716] (4)

		¡Hola!
		
		Lo que debes hacer es importar el archivo model.js que acabamos de crear.
		``` 
		    const Model = require('./model');
		    
		```
		
		con esto te debe funcionar perfecto.
		
		Cualquier cosa avisa 😃

* **Juan Andres Ageitos Lopez** (1) [732434](https://platzi.com/comentario/732434/) 

	Hola, necesito ayuda.
	
	Cuando quiero arrancar el server.js me tira en consola un error  
	\platzi\node\backend\node_modules\bson\index.js:1  
	��٣��,�X�@��t&�Ӫ:���ޢ  
	�d��x����B��\�/�����  
	^  
	SyntaxError: Invalid or unexpected token
	
	si comento las lineas de la conexion a mongo no me lo tira ya con el require(‘mongoose’) da el problema.

* **webuser** (1) [82717](https://platzi.com/comentario/1011168/) 
me sale el siguiente error. db err: connection <monitor> to x.xxx.xx.xxx:27017 closed

* **Argos98** (1) [80171](https://platzi.com/comentario/953772/) 
me sale este error nose que prodra ser npm ERR! code ENOVERSIONS npm ERR! No valid versions available for mongoos npm ERR! A complete log...

	* **Juan David Castro (Platzi)** [80171] (1)

		1️⃣ Es **`mongoose`** , no **`mongoos`**.
		
		2️⃣ Puedes seguir estas recomendaciones para solucionar el error: <https://stackoverflow.com/questions/19150942/cant-install-mongoose-via-npm>.

* **george-montenegro** (1) [76588](https://platzi.com/comentario/890039/) 
Buenas noches, Me podrían ayudar con este error // Conneccion db.Promise = global.Promise db.connect(‘mongodb+srv://db_user_nodejs:<Pa...

	* **Massimo Di Berardino** [76588] (1)

		Hola George, esto es un problema con tu string de coneccion que hay cierta compatibilidad de version con moongose, te recomiendo utilizar el formato que muestra el profe en el video. No se exactamente cual es el problema que tiene el tuyo pero lo que busque es eso que con moongose hay cierta compatibilidad con los formatos de conección.

* **daag13** (1) [76494](https://platzi.com/comentario/888312/) 
Hola, estoy recibiendo este error: Error: Cannot find module 'mongoose’ Me pasa únicamente en la clase store.js, en model.js si me funcio...

	* **Juan David Castro (Platzi)** [76494] (1)

		¿Puedes mostrarnos tu código de store.js?

* **johneduardo** (1) [72012](https://platzi.com/comentario/808307/) 
Qué papel desempeña el prefijo async y await en la función: async function getMessages() { const ...

	* **Moisés Cedeño** [72012] (2)

		El prefijo **async** le dice a la función getMessages(), “Oye, esta función es asíncrona, por tanto ejecútala como tal.”
		
		Y el prefijo **await** le dice a la variable “Oye, lo que me retorne esta función asincrona, esperalo (await) y guárdalo en esta constante”
		
		Al final, se retorna el valor que hemos estado esperando con el return.

* **cmarialatincloud** (1) [70005](https://platzi.com/comentario/767415/) 
Consulta no me queda claro cual es la mejor forma de estructurar un proyecto en Node.js. Si bien la forma en la que estructura un proyect...

	* **Erik Ochoa (Platzi)** [70005] (3)

		Esos directorios que mencionas los veo bien, son de los más común.
		
		No existe “la mejor forma” de estructurar tu proyecto, cómo regla general trata siempre de mantener tu estructura de directorios lo más simple posible. Dependiendo de las tecnología que uses y de las reglas del equipo con el que trabajes (si es que trabajas con uno) esa estructura se puede ver afectada, cada proyecto es único.
		
		Cabe mencionar que si hay ciertas estructuras muy comunes, te recomiendo que veas proyectos populares en github para darte ideas. aquí te dejo [dos](https://softwareontheroad.com/ideal-nodejs-project-structure/)[artículos](https://medium.com/codebase/structure-of-a-nodejs-api-project-cdecb46ef3f8) que te pueden servir.

* **Jvllian** (1) [68118](https://platzi.com/comentario/735054/) 
Buen día, Solicito su ayuda con el siguiente error: ReferenceError: Model is not defined at Object.addMessage [as dd] (…\backendNode\comp...

	* **AlexGarrixen** [68118] (1)

		Hola,verifica que estes requiriendo el modulo **Model**

## 0210. MongoDB II Actualizar  datos [22623](https://platzi.com/clases/1689-backend-js/22623-mongodb-ii-actualizar-datos/)

### Descripción:
placeholder

### Comentarios:

* **Joaquin Mayer Breitkreitz** (12) [728900](https://platzi.com/comentario/728900/) 

	En el minuto 07:29 también se puede poner findById(id) en vez de findOne({_id: id})

* **beaps** (7) [729892](https://platzi.com/comentario/729892/) 

	¿Sería buena práctica utilizar async/await dentro de una promesa? 🧐  
	  
	He estado buscando información y he encontrado esto:  
	
	
	* “Si una función ejecutor asíncrona lanza un error, el error se perderá y no provocará que la promesa se rechace.”  
	
	* “Si una la función ejecutor de _Promise_ esta utilizando _await_ , esto normalmente es una señal de que en realidad no es necesario utilizar el constructor _new Promise_ ya que el alcance de dicho constructor puede ser reducido.”  
	  
	<https://eslint.org/docs/rules/no-async-promise-executor>  
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Promise#Sintaxis>
	
	

	* **Carlos Hernández** [729892] (10)

		Lo ideal es que todas tus respuestas sean estándares. Una función asíncrona (async function) devuelve una promesa.  
		.  
		Si vamos a devolver una promesa que viene de otro módulo, no tiene sentido esperar a que se resuelva pudiendo pasar la referencia. Sin embargo, en caso de control de errores, podemos querer que la promesa se comporte de una forma determinada.  
		.  
		Ahí es cuando podemos usar los constructores, o las funciones Promise.reject() o Promise.resolve()

* **sergio-medina93** (4) [908085](https://platzi.com/comentario/908085/) 

	Ese error del await en el minuto 06:37 es buenísimo

* **Angelo Barbara** (3) [966071](https://platzi.com/comentario/966071/) 

	Es necesario poner un asyc/away tanto en la promesa como en el updatetext del store.js?

	* **Luis Arturo Lira Cerda** [966071] (2)

		No, de hecho lo puedes hacer solamente con Async/Await, yo estoy haciendo el curso sólo usando async/await:
		``` 
		    asyncfunctionupdateMessage(id, message) {
		      const foundMessage = await Model.findOne({ _id: id})
		      foundMessage.message = message
		      const newMessage = await foundMessage.save()
		      return newMessage
		    }
		    
		```

* **David Acevedo** (2) [737805](https://platzi.com/comentario/737805/) 

	no es medio redundante estar pasando los mismos parametros siempre, se podria ahorrar la logica de network y pasarle directamente el controller no? asi no se arma lio con promesas async awaits y todo eso.

	* **Carlos Hernández** [737805] (10)

		Podrías hacerlo, pero el componente dejaría de ser 100% reutilizable, y requeriría ser llamado únicamente desde una petición http.  
		.  
		Al separar la lógica de la capa de red, puedes reutilizar tu componente desde cualquier otra parte simplemente importándolo.  
		.  
		Imagina que en lugar de foto subes un vídeo, y quieres añadirle un procesamiento para comprimirlo. Podrías hacerlo en asíncrono, y, cuando termine, añadir la nueva URL del fichero.  
		.  
		El código de esa parte podría ser así:
		``` 
		    const Controller = require('./components/video/controller');
		    
		    functionprocesoLargoCallback(data) {
		      return Controller.update(data.id, { 
		        video: data.url 
		      });
		    }
		    
		```

* **Wilson Castro Medellin** (1) [1120720](https://platzi.com/comentario/1120720/) 

	Excelente la forma de update

* **carlosextra1** (1) [1062101](https://platzi.com/comentario/1062101/) 

	Excelente clase profe!!!

* **Moises Aceves** (1) [800927](https://platzi.com/comentario/800927/) 

	Amigos yo tengo este problema todo funciona bien pero me sale este mensaje y no se que es ya revise el video muy bien en busca de errores
	
	Example app listening on port 3000!  
	Error [ERR_HTTP_HEADERS_SENT]: Cannot set headers after they are sent to the client  
	at ServerResponse.setHeader (_http_outgoing.js:470:11)  
	at ServerResponse.header (C:\Users\Moises\Documents\node\cursoDeNodejs\node_modules\express\lib\response.js:771:10)  
	at ServerResponse.setHeader (_http_outgoing.js:470:11) nse.js:170:12)  
	at ServerResponse.header (C:\Users\Moises\Documents\node\cursoDeNodejs\node_modules\express\lib\resnse.js:267:15)ponse.js:771:10) nse.js:158:21)  
	at ServerResponse.send (C:\Users\Moises\Documents\node\cursoDeNodejs\node_modules\express\lib\response.js:170:12) etwork.js:27:18)  
	at ServerResponse.json (C:\Users\Moises\Documents\node\cursoDeNodejs\node_modules\express\lib\response.js:267:15) they are sent to the client  
	at ServerResponse.send (C:\Users\Moises\Documents\node\cursoDeNodejs\node_modules\express\lib\response.js:158:21) ponse.js:771:10)  
	at Object.error (C:\Users\Moises\Documents\node\cursoDeNodejs\network\response.js:11:35) nse.js:170:12)  
	at controller.updateMessage.then.catch.e (C:\Users\Moises\Documents\node\cursoDeNodejs\components\mnse.js:267:15)essage\network.js:30:18) nse.js:158:21)  
	at process._tickCallback (internal/process/next_tick.js:68:7)  
	(node:13608) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated eitheessage\network.js:30:18)r by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). (rejection id: 1) r by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled wi  
	(node:13608) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future,  
	promise rejections that are not handled will terminate the Node.js process with a non-zero exit code. promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.  
	[nodemon] restarting due to changes…  
	[nodemon] starting `node server.js`  
	conectado a DB  
	Example app listening on port 3000!

	* **amgv** [800927] (1)

		eso sucede porque estas enviando una respuesta y luego estas enviando otra respuesta al cliente

	* **cesar88** [800927] (1)

		fijate que no se te halla qedado el res.send(‘OK’) en el network

	* **gustavoalbertorestrepopelae** [800927] (1)

		Hola a mi tambien me salia eso… yo tenia este errror al llamar el response desde Network.js
		
		response.success(response.success(req,res,fullmessaje,201))  
		y lo cambie por esto  
		response.success(req,res,fullmessaje,201)
		
		revisa en el network los llamados, tambien corregí unos parametros que pide la funcióno response.success y response.error que no le estaba enviando desde del Network al enviar la respuesta.

* **Andres Roberto Coello Goyes** (1) [761978](https://platzi.com/comentario/761978/) 

	Put tambien es para modificar o me equivoco… !!

	* **Cesar Velásquez Córdova** [761978] (3)

		Si también sirve para actualizar los datos, todo va depender de los params que le pasemos al controller.  
		Te dejo un ejemplo por si quieres practicarlo, de como actualizar el usuario que envía el mensaje
		``` 
		    router.put('/:id', (req, res) => {
		      controller.updateUser(req.params.id, req.body.user)
		        .then((data) => {
		          response.success(req, res, data, 200);
		        })
		        .catch(e => {
		          response.error(req, res, 'Error interno', 500, e);
		        })
		    })
		    
		```
		
		Si puedes observar, la lógica es la misma, lo único que el valor que recibes del body en este caso será req.body.user
		
		Saludos y éxitos!!

	* **gorydev** [761978] (3)

		sí, pero el PATCH se utiliza cuando vas a actualizar solo una pequeña parte en este caso solo el mensaje, cuando se actualiza todo o casi toda la información si se usa el PUT aunque con ambos funciona bien

* **john jairo lopez ramirez** (1) [757864](https://platzi.com/comentario/757864/) 

	Que utilidad tiene esto si igual es necesario saber el id y enviarlo por la url para realizar la mofidicación con patch?

## 0220. MongoDB III Consultar datos [22610](https://platzi.com/clases/1689-backend-js/22610-mongodb-iii-consultar-datos/)

### Descripción:


### Comentarios:

* **raparisg** (7) [939706](https://platzi.com/comentario/939706/) 

	En caso de que queramos hacer una búsqueda por el nombre ignorando mayúsculas o minúsculas se puede implementar el siguiente código:
	``` 
	      let userFilter = {};
	      if (user) {
	        userFilter.user = new RegExp(user, "i");
	      }
	    
	```
	
	Mongo puede utilizar Regular Expressions para realizar búsquedas y en estas es posible indicarle que busque “case-insensitive”. Esto se logra con el flag “i” que vemos en el código. Este código se traduce a: /usuario/i.  
	.  
	Platzi cuenta con un curso de RegExp por si alguien quiere tomarlo 😃 <https://platzi.com/clases/expresiones-regulares/>

	* **Iván Darío Sánchez Jiménez** [939706] (2)

		Buen aporte compañero, yo lo implementé en store.js
		``` 
		    asyncfunctiongetMessages(filterUser) {
		      let filter = {};
		    
		      if (filterUser !== null) {
		        filter = {
		          user: newRegExp(filterUser, "i") 
		        };
		      }
		      const messages = await Model.find(filter);
		      return messages;
		    }
		    
		```

	* **Iván Darío Sánchez Jiménez** [939706] (2)

		Aunque creo que hay que optimizar mas la expresión porque así com o está busca cualquier coincidencia parcial de lo que le pasemos a la variable user. Por ejemplo para Jesus me retornó los mensajes de la forma `user=sus`

	* **carlosextra1** [939706] (1)

		Gracias por el aporte. Ya lo agrege!!
		``` 
		    const db = require('mongoose');
		    const Model =  require('./model');
		    
		    db.Promise= global.Promise;
		    db.connect('mongodb+srv://db_user_node:G4YersckHG0c8s@cluster0-6qvbh.mongodb.net/test?retryWrites=true&w=majority', {
		        useNewUrlParser: true,
		        useUnifiedTopology: true
		    });
		    
		    console.log('[db] Conectada con el server db');
		    
		    functionaddMessage(message) {
		        const myMessage = new Model(message);
		        myMessage.save();
		    }
		    
		    asyncfunctionupdateMessage(id, message) {
		        const foundMessage = await Model.findOne({
		            _id: id
		        });
		        foundMessage.message = message;
		    
		        const newMessage = await foundMessage.save();
		        return newMessage;
		    }
		    asyncfunctiongetMessages(filterUser) {
		        let filter = filterUser ? { user: newRegExp(filterUser,"i") } : {};
		        const message = await Model.find(filter);
		        return message; 
		    }
		    
		    
		    module.exports = {
		        add: addMessage,
		        list: getMessages,
		        update: updateMessage
		    }
		    
		```

* **Jair Israel Avilés Eusebio** (7) [738644](https://platzi.com/comentario/738644/) 

	Con la especificacion del metodo `getMessages` del `store.js` vista en esta clase, al no especificar el parametro user en el query, se retornara un arreglo vacio. Esto depende de la definicion y alcance del metodo `getMessages`, pero si en caso yo quisiera obtener toda la lista de usuarios usando dicho metodo cuando no se especifica el parametro query de user, es solo cambiar la condicion de existencia del parametro `filterUser`
	``` 
	    constget Messages = async (filterUser) => {
	        let filter = {}
	        if (filterUser) 
	       // ... aqui sigue la misma definicion de metodo :D
	    }
	    
	```

* **carlosextra1** (2) [1062145](https://platzi.com/comentario/1062145/) 

	si yo quiero hacer la siguiente consulta ++**SQL SELECT * FROM messages WHERE user LIKE “%carl%” **++en mongo con node  
	¿Cómo sería?

	* **José María Cuevas Ramírez** [1062145] (1)

		El filtro que tendrías que pasar quedaría así:
		``` 
		    {"user": /carl/}
		    
		```
		
		😃

* **alejandromarcano** (2) [840545](https://platzi.com/comentario/840545/) 

	Genial! También puede hacerse mas corto de la siguiente forma en el store.js:
	``` 
	    let listUsers = async (filterUser) => { 
	    
	        if(filterUser!=null) { filterUser = {user : filterUser} }
	        const users = await Model.find(filterUser) 
	        return users
	    }
	    
	```

	* **sergio-medina93** [840545] (1)

		jaja ¡Genial! 🤣

* **Wilson Castro Medellin** (1) [1120750](https://platzi.com/comentario/1120750/) 

	filter === select?

* **jonathan2138** (1) [937285](https://platzi.com/comentario/937285/) 

	Wow genial aprender estas cosas

* **DavidMG01** (1) [928252](https://platzi.com/comentario/928252/) 

	Podríamos también pasar el usuario como:  
	…/message/user/:name …?
	
	Cual sería la mejor forma???

	* **Sergio Cieza Zurita** [928252] (1)

		Buenas David,
		
		De esa manera sería igualmente valido, pero no es escalable ya que el problema que tendrían al pasarlo de esa manera y no mediante query sería que se restringiría a un solo parámetro o un solo filtro (:name en este caso), es decir si luego quisieras filtrar por message ya no te valdría hacer “/message/user/:message” porque tu lógica habría sido fija para :name, porque no se puede diferenciar, da igual como lo llames en tu fichero network, el nombre es simplemente para luego a la hora de obtenerlo mediante req.params.elNombreQuePusieras en tu caso sería [req.params.name](http://req.params.name),
		
		Con query params por ejemplo si podrías hacer diferentes lógicas y sería más escalable, ya que podrías hacer filtros como ?user=Jesus&message=Hola o filtros incluso personalizados.
		
		Espero me haya explicado bien. 😃  
		Saludos.

* **sergio-medina93** (1) [908152](https://platzi.com/comentario/908152/) 

	Vaina me toca repasar mucho Mongo DB. Hay muchas cosas que no entiendo a profundidad.

* **george-montenegro** (1) [78465](https://platzi.com/comentario/921571/) 
Por favor su ayuda me sale este error al realizar la coneccion: [nodemon] starting node server.js la aplicacion esta escucha...

	* **Jonathan Aguasaco** [78465] (1)

		Revisa el acceso en Mongodb, que la url y el acceso esten funcionando bien.

## 0230. MongoDB IV Eliminar Datos [22611](https://platzi.com/clases/1689-backend-js/22611-mongodb-iv-eliminar-datos/)

### Descripción:


### Comentarios:

* **albertodsosa** (3) [1026931](https://platzi.com/comentario/1026931/) 

	El [repo](https://github.com/CodingCarlos/backend-node-platzi) del profe!!

	* **Erik Ochoa (Platzi)** [1026931] (2)

		Gracias por el link, me sirvió para responder una pregunta. 😃

	* **carlosextra1** [1026931] (2)

		Gracias por el aporte!

* **ElMeisimo** (3) [857736](https://platzi.com/comentario/857736/) 

	El return despues del reject o del resolve no es necesario 😄

* **Líncol Saenz** (2) [751543](https://platzi.com/comentario/751543/) 

	Genial, muy emocionado.

* **Wilson Castro Medellin** (1) [1120803](https://platzi.com/comentario/1120803/) 

	Como se puede eliminar más de un registro?

* **carlosextra1** (1) [1062248](https://platzi.com/comentario/1062248/) 

	Excelente avance. Node lo usare en los siguientes proyectos!!

	* **María José Ledesma (Platzi)** [1062248] (1)

		Buenísimo! Compártenos esos proyectos!

* **Alfonso Navarro** (1) [1015423](https://platzi.com/comentario/1015423/) 

	Bueno en este vídeo encuentro una incongruencia, el teacher en el controller, en la función **deleteMessage** llama a **remove()** y en el store la función se llama **removeMessage** y sin embargo en la prueba le funciona, esta raro. Que paso alli???,

	* **Mariana Valencia** [1015423] (4)

		Cuando lo exportas en store.js estás dándoleel nombre de remove por medio de asignación con objetos.

	* **LuisViGo** [1015423] (1)

		El profe esta llamando a ‘removeMessage’ ‘remove’ a la hora de exportarlo:
		``` 
		    delete: deleteMessage,
		    
		```
		
		tal que así.

* **Ildebrando Mora Valdes** (1) [863145](https://platzi.com/comentario/863145/) 

	Tengo el siguiente error
	
	`[response error]TypeError: store.remove(...).then(...).cath is not a function`
	
	pero si me elimina el registro
	
	Ya inspeccione el código completo y todo esta bien como en el vídeo

	* **Alan Santiago** [863145] (7)

		Está mal escrito. Es `catch`, tú escribiste `cath` 😅

* **Oliver Yunior Mendez Arias** (1) [799791](https://platzi.com/comentario/799791/) 

	Tengo un error interno. Reviso el codigo y lo reviso y no veo nada diferente al de la explicacion.

	* **ricardocelis (Platzi)** [799791] (2)

		qué error te indica?

	* **Oliver Yunior Mendez Arias** [799791] (2)

		Miro nuevamente el video y veo todo igual, no se que pueda ser.
		
		La respuesta recibida es:
		``` 
		    {
		      "error": "Error interno",
		      "body": ""
		    }
		    
		    
		```
		
		Este el delete de network:
		``` 
		    router.delete('/:id',function (req, res) {
		        controller.deleteMessage(req.params.id)
		        .then(() => {
		    
		            response.success(req,res,`Usuario ${req.params.id} eliminado`, 200);
		            //response.success(req,res,'Usuario eliminado', 200);
		        })
		        .catch(e => {
		            response.error(req,res,'Error interno', 500, e);
		        });
		    });
		    
		```
		
		deleteMessage del controller
		``` 
		    function deleteMessage(id) {
		        returnnew Promise((resolve, reject) => {
		            if(!id){
		                reject('id invalido');
		                returnfalse;
		            }
		            store.remove(id)
		                .then(() => {
		                    resolve();
		                })
		                .catch(e => {
		                    reject(e);
		    
		            });
		    
		        });
		        
		    }
		    
		    
		```
		
		La funcion removeMessage del store.js
		``` 
		    functionremoveMessage(id) {
		        //Model.findByIdAndDelete(id);
		        
		        Model.deleteOne({
		            _id:id
		        });
		        
		    }
		    
		    
		```
		
		Seria de gran ayuda para seguir la serie del curso. 😃 Gracias de antemano.

	* **Jonathan Aguasaco** [799791] (1)

		Okey miro tu codigo, y no parece nada malo, lo que te recomendaria es que validaras cada uno de las clases o archivo js si en alguna parte se esta perdiendo la informacion, sino verifica el id si existe y lo estas ingresando completamente, recuerda la peticion delete la haces al localhost:3000/message/<id correspondiente que dio mongo a tus datos> Exitos

	* **Omar Jesus Hernández Bastos** [799791] (2)

		Probaste agregando al final en el module.exports la funcion en cada uno de los archivos?

	* **johneduardo** [799791] (8)

		Te faltó el **return** en la functión removeMessage del store.js:
		``` 
		    returnModel.deleteOne({
		            _id: id
		        });
		    
		```

	* **Juan José Vega Quintero** [799791] (1)

		<https://github.com/CodingCarlos/backend-node-platzi>

* **Jeisson Camilo Romero Cendales** (1) [792565](https://platzi.com/comentario/792565/) 

	Excelente curso, hay repositorio?, tenia un pequeño error en store.js y solo lo pude solucionar hasta Carlos hizo un repaso de este archivo.

	* **ricardocelis (Platzi)** [792565] (1)

		claro! está en la sección de archivos

* **j0e** (1) [779060](https://platzi.com/comentario/779060/) 

	También podemos utilizar:
	``` 
	    Model.findByIdAndDelete(id);
	    
	```

* **Sebastian Cardoso Castillo** (1) [773354](https://platzi.com/comentario/773354/) 
	
	![lineRemoveMessage.png](https://static.platzi.com/media/user_upload/lineRemoveMessage-b6dd0989-43a6-448e-b2c0-a401c2dcc86e.jpg)

* **René Sanchez** (1) [765468](https://platzi.com/comentario/765468/) 

	Muy buenas las clases!!

* **omar-espana** (1) [84053](https://platzi.com/comentario/1041856/) 
me dice que filter no esta definida

	* **Erik Ochoa (Platzi)** [84053] (1)

		[Acá](https://platzi.com/comment/1041855/) te he dado una respuesta.

* **omar-espana** (1) [84052](https://platzi.com/comentario/1041855/) 
ayuda [response error]ReferenceError: filter is not defined``` 

	* **Erik Ochoa (Platzi)** [84052] (1)

		Guiándome por el contexto de la clase, en el archivo _store.js_ del componente message asegúrate de tener definida la variable **filter** así:
		``` 
		    asyncfunctiongetMessages(filterChat) {
		        returnnewPromise((resolve, reject) => {
		            let filter = {}; //<-------#########AQUI
		            if (filterChat !== null) {
		                filter = { chat: filterChat };
		            }
		            Model.find(filter)
		                .populate('user')
		                .exec((error, populated) => {
		                    if (error) {
		                        reject(error);
		                        returnfalse;
		                    }
		    
		                    resolve(populated);
		                });
		        })
		    }
		    
		```
		
		aquí el [repo](https://github.com/CodingCarlos/backend-node-platzi/blob/master/components/message/store.js) del proyecto.

* **omar-espana** (1) [84050](https://platzi.com/comentario/1041852/) 
tengo este error ayuda por favor [response error]ReferenceError: filter is not defined 

	* **Erik Ochoa (Platzi)** [84050] (1)

		[Acá](https://platzi.com/comment/1041855/) te he dado una respuesta.

* **nancygtec** (1) [78405](https://platzi.com/comentario/920528/) 
¿Por qué dentro del store.js las funciones add y remove no son asíncronas mientras que el list

	* **Carol Estefanny Masmela Escamilla** [78405] (2)

		No tienen ninguna razon real. Supongo qeu solo lo quiso poner asi. Pero tienes un punto en mi opinion para ser concistente en el codigo seria bueno tener o solos async/await syntax o solo promesas :thu

## 0240. Gestionar conexiones a la base de datos desde la API [22612](https://platzi.com/clases/1689-backend-js/22612-gestionar-conexiones-a-la-base-de-datos-desde-la-a/)

### Descripción:


En esta clase vamos a refactorizar nuestro código para tener todo organizado de una mejor manera, crearemos un archivo `db.js` donde tendremos todos los datos de nuestra conexión a la base de datos.

### Comentarios:

* **raparisg** (3) [941252](https://platzi.com/comentario/941252/) 

	¿Cuál es la ventaja de tener la URL de conexión de base de datos como parámetro? Quizás es mejor dejarla como variable de entorno. Pensando en qué tanto podría cambiar la URL de conexión entre métodos, es casi nunca. Sin embargo entre ambientes si cambia

	* **Iván Darío Sánchez Jiménez** [941252] (5)

		Una buena prácica sería la implementación de dotenv para el manejo de las variables de entorno las cuales administramos en un archivo .env en la raiz del directorio el cual lo ignoramos en git y dejamos un archivo .env.example con el nombre de las variables globales para que otro usuario pueda usarlas como referencia.

* **oelsacte** (3) [72113](https://platzi.com/comentario/810697/) 
En la clase anterior se hizo el mock y en esta ya hay conexión real a base de datos, nunca ví cómo se hace esto último ¿o soy el único al...

	* **Abraham Serrano Montiel** [72113] (1)

		Concuerdo contigo, tienes en repo de donde bajaste el código?, es que no lo encuentro

* **carlosextra1** (2) [1062363](https://platzi.com/comentario/1062363/) 

	Todo esto está muy bien, espero que node tenga un framework con una estructura de trabajo ya más estructurada como Laravel en PHP.

	* **rubenchanamesanchez** [1062363] (2)

		Pues si existe un framework que sigue la estructura de Laravel, se llama AdonisJs (<https://adonisjs.com/>)

* **reignover** (2) [792928](https://platzi.com/comentario/792928/) 

	No entiendo muy bien por qué basta con hacer db(‘credencialesDeMongo’); y no llamar a la función connect 😕

	* **Juan Carrillo** [792928] (3)

		Cuando hace `db('credentials')`, está ejecuntando la función `connect` del modulo db.js, ya que si te fijas está exportando está función por default `module.exports = connect`, que de hecho es la unica función del modulo, podría serte util revisar este articulo <https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/import>

* **beaps** (2) [67848](https://platzi.com/comentario/730047/) 
En la url de la conexión a la base de datos se ve la contraseña del usuario… Es seguro que esa información esté en el archivo server....

	* **AlexGarrixen** [67848] (3)

		Hola beaps,evidentemente no se pondrá la uri(url de conexion) en plano,lo ideal seria que la guardaras en una variable de entorno.

* **Wilson Castro Medellin** (1) [1120844](https://platzi.com/comentario/1120844/) 

	Compartir la conexión

* **sergio-medina93** (1) [908209](https://platzi.com/comentario/908209/) 

	Disculpen por la pregunta ¿Qué es una API? A veces creo saber pero no estoy seguro 🤔

	* **David Valecillo** [908209] (2)

		Aca encuentras el concepto: <https://platzi.com/clases/1638-api-rest/21613-que-es-una-api-y-para-que-sirve/>

	* **robertarnaldo99** [908209] (1)

		Definición de API.  
		<https://www.redhat.com/es/topics/api/what-are-application-programming-interfaces>

	* **carlosextra1** [908209] (1)

		API: Application Programming Interface

* **Fernando Cordero** (1) [835401](https://platzi.com/comentario/835401/) 

	store.js
	``` 
	    const Model = require('./model')
	    
	    functionaddMessage(message) {
	        const myMessage = new Model(message)
	        myMessage.save()
	        
	    }
	    
	    asyncfunctiongetMessages(filterUser) {
	        let filter = {}
	        if (filterUser !== null) {
	            filter = { user: filterUser }
	        }
	        const messages = await Model.find(filter)
	        return messages  
	    }
	    
	    functionremoveMessage(id) {
	        return Model.deleteOne({
	            _id: id
	        })
	    }
	    
	    asyncfunctionupdateText(id, message) {
	        const foundMessage = await Model.findOne({
	            _id: id
	        })
	        foundMessage.message = message
	        const newMessage = await foundMessage.save()
	        return newMessage
	    }
	    
	    module.exports = {
	        add: addMessage,
	        list: getMessages,
	        updateText: updateText,
	        remove: removeMessage,
	    }```
	    
	```

* **Fernando Cordero** (1) [835399](https://platzi.com/comentario/835399/) 

	server.js
	``` 
	    const express = require('express')
	    const bodyParser = require('body-parser')
	    
	    constdb = require('./db')
	    
	    const router = require('./network/routes')
	    
	    db('mongodb+srv://db_user_backend_node:<password>@cluster0-icc7n.mongodb.net/backendnode_db?retryWrites=true&w=majority')
	    varapp = express()
	    app.use(bodyParser.json()) 
	    app.use(bodyParser.urlencoded({extended: false}))
	    
	    
	    router(app)
	    
	    
	    
	    app.use('/app', express.static('public'))
	    
	    app.listen(3000) 
	        console.log('Laapp esta escuchando en http://localhost:3000')```
	    
	```

* **Fernando Cordero** (1) [835398](https://platzi.com/comentario/835398/) 

	db.js
	``` 
	    const db = require('mongoose')
	    
	    db.Promise = global.Promise
	    //mongodb+srv://db_user_backend_node:<password>@cluster0-icc7n.mongodb.net/backendnode_db?retryWrites=true&w=majority
	    
	    asyncfunctionconnect(url) {
	        await db.connect(url, {
	            useNewUrlParser: true,
	            useUnifiedTopology: true,
	        }).then(() => {
	            console.log(' [db] Conectada con exito')
	        }).catch( error => console.error(error))
	    }
	    
	    module.exports = connect;```
	    
	```

* **Carlos Federico Rubio Prias** (1) [816656](https://platzi.com/comentario/816656/) 

	Esta clase esta en una posición que no es correcta, por favor corrijan el orden de las clases.

	* **Alfonso Navarro** [816656] (2)

		Si no estas de acuerdo con algo, por lo menos propón una mejora y no criticar por criticar…

* **janska** (1) [816062](https://platzi.com/comentario/816062/) 

	Hola alguien tendrá los pasos de la creación de conexión,no esta el vídeo 😦

	* **daniel alonso** [816062] (1)

		Como lo comentan en el mensaje anterior, esta mal el orden de las clases. Ve las clases siguientes, creo que hasta la 22 y después regresas a esta.

	* **Juan José Vega Quintero** [816062] (1)

		Ya se corrigió

* **JUAN SILVA** (1) [778467](https://platzi.com/comentario/778467/) 

	creo que por seguridad deberiamos usar un archivo .env para las credenciales de la conexion a mongo

	* **Hector Cardona** [778467] (2)

		Hola, una pregunta, como puedo hacer eso? gracias!

	* **Jose Luis Campos Bautista** [778467] (5)

		Ejemplo con **node-env-file**
		
		  1. Instalar `npm install node-env-file`
		  2. Crear archivo .env en la carpeta raíz
		  3. En el archivo a utilizar la configuración.
		
		
		
		`const env = require('node-env-file');`  
		`env(__dirname+'/.env');`  
		`const user = process.env.DB_USER;`  
		`const password = process.env.PASSWORD;`  
		`const db_name = process.env.DB_NAME;`
		
		Contenido del archivo .env  
		`DB_USER=name_use`  
		`PASSWORD=password`  
		`DB_NAME=name_data_base`
		
		[Documentación node-env-file](https://www.npmjs.com/package/node-env-file)
		
		También puedes utilizar [dotenv](https://www.npmjs.com/package/dotenv)

	* **Sebastian Cardoso Castillo** [778467] (1)

		[Dotenv](https://www.npmjs.com/package/dotenv)

	* **lizardojara** [778467] (1)

		Aqui explica como usar dotenv: <https://medium.com/@thejasonfile/using-dotenv-package-to-create-environment-variables-33da4ac4ea8f>

* **Andres Roberto Coello Goyes** (1) [769551](https://platzi.com/comentario/769551/) 

	Tengo una app realizada en Next.js en localhost:300/ no habrá ningún problema si tengo las rutas de node de la api en el mismo server es decir. localhost:300/usuarios

	* **Daniel Esteves** [769551] (2)

		Si claro que sí, debido a que las dos aplicaciones corren en un puerto no pueden ser el mismo, siempre deben ser uno diferente, a menos que sirvas tu aplicación usando Node y todo correría en un mismo puerto; pero de otra manera no es posible, siempre deben ser diferentes

	* **Andres Roberto Coello Goyes** [769551] (1)

		@Daniel Esteves  
		La app de next corre gracias a node js. Tiene una confi en el server.js  
		Pero dicen que es una mala practica utilizar el mismo server…  
		…  
		Entonces cuando hago deploy tengo que subir la api en un server diferente… eso es mas trabajo…??

	* **Sebastian Cardoso Castillo** [769551] (2)

		Podes tener la app de Next y otra app como api en el mismo server.
		
		* Next lo tendrías en el puerto 80 o 443 y la api en otro puerto si el server te lo permite.
		* Lo ideal es en server separados. Si estan en el mismo datacenter algunos servers como Google te permiten usar IP privadas que son mas seguras y veloces.
		
		

	* **Sebastian Cardoso Castillo** [769551] (1)

		Podes tener la app de Next y otra app como api en el mismo server.
		
		Next lo tendrías en el puerto 80 o 443 y la api en otro puerto si el server te lo permite.
		
		Lo ideal es en server separados. Si estan en el mismo datacenter algunos servers como Google te permiten usar IP locales que son mas seguras y veloces.

	* **Sebastian Cardoso Castillo** [769551] (1)

		¿Por qué no puedo borrar mis comentarios?

	* **Daniel Esteves** [769551] (1)

		@programandres tu API deberías subirla a un servidor diferente si es que el actual no soporta Node, digamos si tienes un servidor en Digital Ocean lo idea sería que sirvas tu API en un puerto diferente al de tu aplicación por defecto de NextJS que corre en el puerto 3000, ¿si me di a entender? 😅

* **lizardojara** (1) [73426](https://platzi.com/comentario/834868/) 
Al parecer esta clase estaba mal ordenada, pero ya podemos confirmar que esta correcto.

* **Adolfo Luis Fernández García-Redondo** (1) [72365](https://platzi.com/comentario/814897/) 
Hola!, el curso esta muy bien y lo estoy siguiendo con atención. Sin embargo parece que falta un video, de la lección 17 a la 18 hay un s...

	* **JerezA** [72365] (1)

		estoy viendo exactamente el mismo problema, se pasan toda la parte de las creaciones de los modelos y la estructura definida para la base de datos en mongo 😕

# Uso de entidades para crear aplicaciones escalables [4536]

## 0250. Escalando la arquitectura Múltiples entidades [22613](https://platzi.com/clases/1689-backend-js/22613-escalando-la-arquitectura-multiples-entidades/)

### Descripción:


### Comentarios:

* **Carlos Alex Becerra Chavita** (6) [731482](https://platzi.com/comentario/731482/) 

	Que buen curso!!!

* **Iván Darío Sánchez Jiménez** (5) [1003693](https://platzi.com/comentario/1003693/) 

	Una observación, si vemos en cada definición de modelo indicamos el nombre de la collection en singular pero si la vemos dede mongo la colecction se crea en plural.

	* **Juan José Vega Quintero** [1003693] (1)

		Igual con messages

* **Sebastian Cardoso Castillo** (4) [742866](https://platzi.com/comentario/742866/) 

	Solución al reto:
	``` 
	    // controls.js
	    const store = require('./store')
	    
	    const getAllUsers = () => {
	      returnnewPromise((resolve, reject) => {
	        resolve(store.list())
	      })
	    }
	    
	    module.exports = {
	      getAllUsers
	    }
	    
	```
	``` 
	    // network.js
	    router.get('/', (req, res) => {
	      controller.getAllUsers()
	        .then((users) => {
	          response.success(req, res, users, 200)
	        })
	        .catch(e => {
	          response.error(req, res, 'Unexpected Error', 500, e)
	        })
	    })
	    
	```
	``` 
	    // store.js
	    const Model = require('./model')
	    
	    const getAllUsers = async () => {
	      const users = await Model.find()
	      return users  
	    }
	    
	    module.exports = {
	      list: getAllUsers
	    }
	    
	```

* **caprilespe** (3) [947663](https://platzi.com/comentario/947663/) 

	Reto: Listar usuarios:
	
	user/store.js
	``` 
	    asyncfunctiongetUsers() {
	      const users = await Model.find();
	      return users;
	    }
	    
	    module.exports = {
	      add: addUser,
	      lists: getUsers
	    };
	    
	```
	
	user/controller.js
	``` 
	    functiongetUsers() {
	      return store.lists();
	    }
	    
	    module.exports = {
	      addUser,
	      getUsers
	    };
	    
	```
	
	user/network.js
	``` 
	    router.get("/", function(request, response) {
	      controller
	        .getUsers()
	        .then(data => {
	          responseType.success(request, response, data, 200);
	        })
	        .catch(error => {
	          responseType.error(request, response, "Internal error", 500, error);
	        });
	    });
	    
	```
	
	Resultado:
	
	![ListUser.PNG](https://static.platzi.com/media/user_upload/ListUser-c99aeba2-763b-4e67-b19e-47391ed5b149.jpg)

* **Juan José Vega Quintero** (2) [1066882](https://platzi.com/comentario/1066882/) 

	Este pequeño momento de mi vida se llama felicidad  
	![Annotation 2020-03-26 112236.png](https://static.platzi.com/media/user_upload/Annotation%202020-03-26%20112236-f013311a-25a3-422e-b328-00145fbd8f26.jpg)

* **gustavoalbertorestrepopelae** (2) [989381](https://platzi.com/comentario/989381/) 

	Saludos, Porque en Mensajes se indican explicitamente Return New Promise y en User no, es como si fueran implicitas. Me pueden aclarar.?
	``` 
	    functionaddMessage (user, message){
	       // trabajar con promesas para indicar cuando algo sale bien o sale mal
	        returnnewPromise ((resolve, reject)=>{
	            if (!user || !message) {
	                console.error('[error messageController addMessage] no hay valor para el parametro user o message')
	                reject ('Los datos son incorrectos')
	                returnfalse
	    
	```
	
	No esta usando return new Promise
	``` 
	    functionaddUser (name){
	        // Se crea el objeto user con las propiedades
	        if (!name){
	            returnPromise.reject('Invalid name')
	        }
	        const user = {
	            name,
	        }
	    
	        //Se guarda el objeto user usando el metodo store.add creado en el archivo store.js
	        return store.add(user)
	    }
	    
	```

	* **Guillermo López** [989381] (1)

		fijate que en el metodo addUser del archivo store.js
		``` 
		    functionaddUser(user){
		        const myUser = new Model(user);
		        return myUser.save(); //el .save() devuelve una promesa
		    }
		    
		    
		```
		
		por lo tanto en el controller al llamar a store.add(user) ya estas recibiendo una promesa, por lo que solo usas el Promise.reject para que controle si no viene el parametro name

* **jonathan2138** (2) [940204](https://platzi.com/comentario/940204/) 

	Me parece que es muy practico el curso, ya con lo que aprendimos del componente mensajes podemos crear cualquier entidad sin problema, se vuelve muy modular nuestra programa

* **edanfesi** (2) [747712](https://platzi.com/comentario/747712/) 

	¡Hola a todos!
	
	Esta es mi propuesta al reto planteado:
	
	* En `network.js` añadí el método get:
	
	
	``` 
	    // network.js
	    router.get('/', function(req, res){
	        const filterUser = req.query.name || null;
	    
	        controller.getUser(filterUser)
	            .then(data => {
	                response.success(req, res, data, 200);
	            })
	            .catch(error => {
	                response.error(req, resp, 'Internal Error', 500, error);
	            })
	    });
	    
	```
	
	* Luego en `controller.js` añadí el método getUser:
	
	
	``` 
	    // controller.js
	    functiongetUser(filterUser) {
	        returnnewPromise(async (resolve, reject) => {
	            return resolve(store.list(filterUser));
	        });
	    }
	    
	    module.exports = {
	        getUser
	    }
	    
	```
	
	* Finalmente añadí el método list (getUser) en el `store.js`:
	
	
	``` 
	    // store.js
	    asyncfunctiongetUser(filterUser) {
	        let filter = {};
	    
	        if (filterUser) {
	            filter['name'] = filterUser;
	        }
	    
	        const users = await Model.find(filter);
	        return users;
	    }
	    
	    module.exports = {
	        list: getUser
	    }
	    
	```
	
	Saludos a todos 😃

* **Wilson Castro Medellin** (1) [1120939](https://platzi.com/comentario/1120939/) 

	Excelente clase

* **Rabi Leonel Leon Chan** (1) [1091351](https://platzi.com/comentario/1091351/) 

	Reto Completado 😁😁😁😁👀👀👀  
	![](https://i.imgur.com/WIrGRQU.jpg)

* **Juan Carlos García Esquivel** (1) [1078772](https://platzi.com/comentario/1078772/) 

	Mission Complete 😀  
	![Reto](https://static.platzi.com/media/user_upload/Captura-6c7f158b-8e6e-4885-8166-deaa09acb0da.jpg)

* **Emanuel Valero** (1) [1074076](https://platzi.com/comentario/1074076/) 
	
	![pic.png](https://static.platzi.com/media/user_upload/pic-dad338c0-f5d3-48ad-bb21-c18bdc62e999.jpg)

* **carlosextra1** (1) [1062820](https://platzi.com/comentario/1062820/) 

	Listo!!
	``` 
	    [
	        {
	            "_id": "5e7ace3bb71e6e0d20fec298",
	            "name": "carlos ramirez",
	            "email": "carlos@extrasistemas.com",
	            "__v": 0
	        },
	        {
	            "_id": "5e7ad00ca9aca50ddd992b5c",
	            "name": "Ana Maria",
	            "email": "ana@extrasistemas.com",
	            "__v": 0
	        }
	    ]```
	    
	```

* **emanuel-alejandro-mamani** (1) [1026095](https://platzi.com/comentario/1026095/) 

	Reto cumplido!!  
	![Captura de pantalla de 2020-03-08 23-33-05.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20de%202020-03-08%2023-33-05-d1df6b34-3a14-4eee-a212-210cdce939bf.jpg)

* **ehnbytes** (1) [975139](https://platzi.com/comentario/975139/) 

	Reto realizado!!, me marca error al subir la imagen.
	
	![](url)

* **Byron Mesias Cueva Cabrera** (1) [971263](https://platzi.com/comentario/971263/) 

	Reto realizado
	
	![reto.png](https://static.platzi.com/media/user_upload/reto-9681063b-54ca-40e9-9f2a-45fd83f9e843.jpg)

* **FabianIgnacio** (1) [891060](https://platzi.com/comentario/891060/) 

	Alguien me puede decir si trabajar con async await todo el rato en vez de promesas es contra producente? Lo encuentro más facil con async await ¿Hay diferencia?

	* **johannpino** [891060] (4)

		No hay diferencia, la sintaxis async/await permite trabajar con promesa de manera mas fácil para leer y depurar. Tienes que pensar que async/await es azucar sintactica de las promesas.

	* **sergio-medina93** [891060] (1)

		Azúcar sintactica 🤣🤣

* **Nicolasdds** (1) [839708](https://platzi.com/comentario/839708/) 

	Me perdí en que momento le damos el nombre “users” a la colección…

	* **edwintrumpet** [839708] (2)

		El nombre de la collección lo obtiene cuando se define el modelo
		``` 
		    const model = mongoose.model("User", mySchema);
		    
		```
		
		mongoose toma la palabra **user** y le agrega una “s” como para indicar que es una colección de ese tipo de documentos.  
		Si quiere probar cambie esa palabra y almacene otro usuario y verá como crea una nueva colección con el nombre que usted indique ahí en plural.

* **Kevin William Roberts Costa** (1) [831492](https://platzi.com/comentario/831492/) 

	 **Network**
	``` 
	    router.get('/', function(req,res){
	        controller.getUsers()
	        .then(data => {
	            response.success(req, res, data, 201);
	        })
	        .catch(e => {
	            response.error(req, res, 'Internal Error', 500, e)
	        })
	    })
	    
	```
	
	**Controller**
	``` 
	    functiongetUsers(){
	        return store.list();
	    }
	    
	```
	
	**store**
	``` 
	    asyncfunctionlistUser(){
	        const users = await Model.find();
	        return users;
	    }
	    
	```

* **Kevin William Roberts Costa** (1) [831423](https://platzi.com/comentario/831423/) 

	Wow va demasiado rápido pero pausando va

* **pro_cristancho** (1) [789679](https://platzi.com/comentario/789679/) 

	```
	    //network.js
	    
	    router.get('/', function(req, res){
	        const filterName = req.query.name || null ;
	        controller.getUser(filterName)
	            .then((userList) =>{
	                response.success(req, res, userList, 200);
	            })
	            .catch(e =>{
	                response.error(req, res, 'Error de users', 500, e);
	            });
	    });
	    
	    
	    
	    //controller.js
	    
	    functiongetUser(filterName){
	        returnnew Promise((resolve, reject) =>{
	            resolve(store.list(filterName));
	        })
	    }
	    
	    
	    
	    //store.js
	    
	    async functiongetUser(filterName){
	        let filter = {};
	        if(filterName !== null){
	            filter = { name : filterName };
	        }
	        const users = await Model.find(filter);
	        return users;
	    }```
	    
	```

* **Deyvis Neyser Valdez Gavilan** (1) [768101](https://platzi.com/comentario/768101/) 

	Todo excelente hasta ahora, con fe!

* **Elias Medina** (1) [762779](https://platzi.com/comentario/762779/) 

	Hola!
	
	Dejo mi solución al reto, excelente curso.  
	saludos!
	
	* /components/user/controller.js
	
	
	``` 
	    const store = require('./store');
	    
	    functionaddUser(name) {
	        if (!name) {
	            returnPromise.reject('Invalid Name');
	        }
	        const user = {
	            name,
	        };
	        return store.add(user);
	    };
	    
	    functiongetUsers(filterUser) {
	        returnnewPromise((resolve, reject) => {
	            resolve(store.list(filterUser));
	        })
	    };
	    
	    module.exports = {
	        addUser,
	        getUsers,
	    };
	    
	```
	
	* /components/user/network.js
	
	
	``` 
	    const express = require('express');
	    const router = express.Router();
	    const response = require('../../network/response');
	    const controller = require('./controller');
	    
	    router.post('/', function(req, res){
	        controller.addUser(req.body.name)
	            .then( data => {
	                response.sucess(req, res, data, 201);
	            })
	            .catch(err => {
	                response.error(req, res, 'Internal Error', 500, err);
	            })
	    });
	    
	    router.get('/', function(req, res){
	        const filterUser = req.query.user || null;
	        controller.getUsers(filterUser)
	            .then((userList) => {
	                response.sucess(req, res, userList, 200);
	            })
	            .catch(err => {
	                response.reject(req, res, 'Invalid User', 500, err)
	            })
	    });
	    
	    module.exports = router;
	    
	```
	
	* /components/user/store.js
	
	
	``` 
	    const model = require('./model');
	    
	    functionaddUser(user) {
	        const myUser = new model(user);
	        return myUser.save();
	    }
	    
	    asyncfunctiongetUsers(filterUser){
	        let filter = {};
	        if(filterUser != null) {
	            filter = { name: filterUser}
	        }
	        const users = await model.find(filter);
	        return users;
	    }
	    
	    module.exports = {
	        add:addUser,
	        list:getUsers,
	    };
	    
	```

* **Francisco Javier Vázquez Paredes** (1) [757322](https://platzi.com/comentario/757322/) 

	Esta es mi respuesta al reto:
	
	1.- Network:
	``` 
	    router.route("/")
	    .get(async (req, res) => {
	        try{
	            const filterUser = req.query.user || null;
	            const messageList = await controller.getUsers(filterUser)
	            response.success(req, res, null, messageList)
	        }
	        catch(error){
	            response.error(req, res, 500, error)
	        }
	    })
	    
	```
	
	2.- Controller
	``` 
	    functiongetUsers(filterUser){
	        returnnew Promise((resolve, reject) => {
	            resolve(store.list(filterUser))
	        })
	    }
	    
	```
	
	3.- Store
	``` 
	    const getUsers = asyncfunction(filterUser){
	        let filter = {};
	        if(filterUser !== null){
	            filter = { name: filterUser }
	        }
	        const users = await Model.find(filter);
	        return users;
	    }
	    
	    
	```

## 0260. Relacionando nuestras entidades [22633](https://platzi.com/clases/1689-backend-js/22633-relacionando-nuestras-entidades/)

### Descripción:


En esta clase vamos a relacionar la entidad de usuarios con la entidad de mensajes y a su vez crearemos una entidad chat que relacionará estas dos entidades.

### Comentarios:

* **Sebastian Cardoso Castillo** (12) [742995](https://platzi.com/comentario/742995/) 

	Creo que lo que tendríamos sería un arreglo de objetos:
	``` 
	    users: [{
	    	type: Schema.ObjectId,
	    	ref: 'User'
	    }]
	    
	```

* **Iván Darío Sánchez Jiménez** (11) [1004500](https://platzi.com/comentario/1004500/) 

	En el minuto 11:00 se debe corregir la forma en que declaramos el array ya que en javascript los arrays asociativos se hacen por medio de objetos y no directamente en el array.
	
	`const mySchema = new Schema({ users:[{ type: Schema.ObjectId, ref: User}] });`

	* **Brandon Iván Quiroa Loarca** [1004500] (2)

		Muchas gracias! ❤️

	* **carlosextra1** [1004500] (1)

		thanks!

* **Cesar Velásquez Córdova** (5) [769443](https://platzi.com/comentario/769443/) 

	También puedes especificar el campo que quieres popular de la entidad que estás relacionando en el mismo .populate(‘chats’, ‘message’)
	``` 
	    listChats = () => {
	        let filter = {};
	    
	        returnnew Promise((resolve, reject) => {
	            Model.find(filter)
	                .populate('chats', 'message')
	                .exec((error, populated) => {
	                    if(error) {
	                        return reject(error);
	                    }
	                    return resolve(populated);
	                })
	        })
	    }
	    
	```
	
	En lugar de obtener todos los campos de la entidad relacionada:
	``` 
	    "chats": [
	                    {
	                        "_id": "5d97be9cbdf7753d3867863e",
	                        "user": "5d97a3adeba63f3f9899048e",
	                        "message": "Entidades relacionadas",
	                        "date": "2019-10-04T21:50:20.258Z",
	                        "__v": 0
	                    },
	                    {
	                        "_id": "5d98d478d4d1bf30f40fd5be",
	                        "user": "5d97ba8a220a1131d46e4787",
	                        "message": "Ya casi concluimos este grandioso curso de Node.js con Platzi",
	                        "date": "2019-10-05T17:35:52.074Z",
	                        "__v": 0
	                    },
	                    {
	                        "_id": "5d98d4b1d4d1bf30f40fd5bf",
	                        "user": "5d97bb7b1ab7964ce0a967ee",
	                        "message": "Si lo sé, estoy muy emocionado",
	                        "date": "2019-10-05T17:36:49.315Z",
	                        "__v": 0
	                    }
	                ],
	                "_id": "5d9a3ed6b0d9aa3918467119",
	                "__v": 0
	    
	```
	
	Puedes obtener el especificado en .populate(‘chats’, ‘message’)
	``` 
	    "chats": [
	                    {
	                        "_id": "5d97be9cbdf7753d3867863e",
	                        "message": "Entidades relacionadas"
	                    },
	                    {
	                        "_id": "5d98d478d4d1bf30f40fd5be",
	                        "message": "Ya casi concluimos este grandioso curso de Node.js con Platzi"
	                    },
	                    {
	                        "_id": "5d98d4b1d4d1bf30f40fd5bf",
	                        "message": "Si lo sé, estoy muy emocionado"
	                    }
	                ],
	                "_id": "5d9a3ed6b0d9aa3918467119",
	                "__v": 0
	    
	```

* **edanfesi** (5) [747905](https://platzi.com/comentario/747905/) 

	¡Hola a todos!
	
	Esta es mi propuesta al reto:
	``` 
	    // network.js
	    const express = require('express');
	    const response = require('../../network/response');
	    const controller = require('./controller');
	    
	    const router = express.Router();
	    
	    router.get('/', function(req, res){
	        controller.listChats()
	            .then(chatList => {
	                response.success(req, res, chatList, 200);
	            })
	            .catch(error => {
	                response.error(req, res, 'Unexpected Error', 500, error);
	            })
	    });
	    
	    router.post('/', function(req, res){
	        controller.addChat(req.body.users)
	            .then(newChat => {
	                response.success(req, res, newChat, 201);
	            })
	            .catch(error => {
	                response.error(req, resp, 'Unexpected error', 500, error);
	            });
	    });
	    
	    module.exports = router;
	    
	```
	``` 
	    // controller.js
	    const store = require('./store');
	    
	    functionaddChat(users) {
	        if (!users || users.length < 2) {
	            returnPromise.reject(`Invalid amound of users: ${users.length}`);
	        }
	    
	        const newChat = {
	            users: users
	        }
	    
	        return store.add(newChat);
	    }
	    
	    asyncfunctionlistChats() {
	        returnnewPromise((resolve, reject) => {
	            resolve(store.list());
	        })
	    }
	    
	    module.exports = {
	        addChat,
	        listChats
	    }
	    
	```
	``` 
	    // store.js
	    const Model = require('./model');
	    
	    functionaddChat(chat) {
	        const newChat = new Model(chat);
	        return newChat.save();
	    }
	    
	    functionlistChats() {
	        let filter = {};
	    
	        returnnew Promise((resolve, reject) => {
	            Model.find(filter)
	                .populate('users')
	                .exec((error, populated) => {
	                    if (error) {
	                        return reject(error);
	                    }
	    
	                    return resolve(populated);
	                })
	        });
	    }
	    
	    module.exports = {
	        add: addChat,
	        list: listChats
	    }
	    
	```
	
	y añadí la ruta en routes.js
	
	Saludos 😃

* **juanvalero252** (2) [992587](https://platzi.com/comentario/992587/) 

	y la otra opcionque no sea borrar manualmente de la base de datos cual es?
	
	Luego que segui avanzando en el curso empece a tener un monton de error y tuve que que hacer revert en los commit para literalmente empezar de cero con el componente chat.
	
	Espero su respuesta

	* **aerama** [992587] (1)

		Que problema te está dando?

	* **mrcMesen** [992587] (1)

		Que problema tienes? yo tuve algunos, justamente porque decidí cambiar un poco el código y probar conocimientos de otros cursos! si te puedo ayudar con gusto! @juanvalero252

* **Luis Arturo Lira Cerda** (2) [988397](https://platzi.com/comentario/988397/) 

	Listo! Yo lo hice todo con Async/Await
	
	network.js
	``` 
	    const express = require('express')
	    const router = express.Router()
	    const response = require('../../network/response')
	    const controller = require('./controller')
	    
	    router.get('/', async (req, res) => {
	      try {
	        const chatsList = await controller.getChats()
	        response.success(req, res, chatsList, 200)
	      } catch (error) {
	        response.error(req, res, 'Unexpected error', 500, error)
	      }
	    })
	    
	    router.post('/', async (req, res) => {
	      try {
	        const { users } = req.body
	        const newChat = await controller.addChat({ users })
	        response.success(req, res, newChat, 201)
	      } catch (error) {
	        response.error(req, res, 'Información inválida', 400, error.message)
	      }
	    })
	    
	    module.exports = router
	    
	```
	
	controller.js
	``` 
	    const store = require('./store')
	    
	    asyncfunctionaddChat(chat) {
	      try {
	        if (!chat.users) {
	          console.log('[ERROR] [CHAT CONTROLLER] No hay usuarios')
	          thrownewError()
	        }
	        returnawait store.addChat(chat)
	      } catch (error) {
	        thrownewError('Datos incorrectos')
	      }
	    }
	    
	    asyncfunctiongetChats() {
	      try {
	        returnawait store.getChats()
	      } catch (error) {
	        thrownewError('Error al obtener los datos')
	      }
	    }
	    
	    module.exports = {
	      addChat,
	      getChats
	    }
	    
	```
	
	store.js
	``` 
	    const Model = require('./model')
	    
	    asyncfunctionaddChat(chat) {
	      try {
	        const myChat = new Model(chat)
	        returnawait myChat.save()
	      } catch (error) {
	        console.log(error.message)
	        thrownewError('Error saving')
	      }
	    }
	    
	    asyncfunctiongetChats() {
	      try {
	        returnawait Model.find().populate('users').exec()
	      } catch (error) {
	        console.log(error.message)
	        thrownewError('Unexpected error')
	      }
	    }
	    
	    module.exports = {
	      addChat,
	      getChats
	    }
	    
	```
	
	model.js
	``` 
	    const mongoose = require('mongoose')
	    const Schema = mongoose.Schema
	    
	    const ChatSchema = new Schema({
	      users: [
	        {
	          type: Schema.Types.ObjectId,
	          ref: 'users'
	        }
	      ]
	    })
	    
	    const model = mongoose.model('chats', ChatSchema)
	    module.exports = model
	    
	```

	* **gustavoalbertorestrepopelae** [988397] (1)

		Esta sería la modifiación al routes.js
		``` 
		    const express = require('express')
		    const message = require('../components/message/network')
		    const user = require('../components/user/network')
		    const chat = require('../components/chat/network')
		    
		    const routes = function(server){
		        server.use('/message',message)
		        server.use('/user',user)
		        server.use('/chat',chat)
		    }
		    
		    /*router.get('/', function(req, res){
		      //res.send("Hola")
		      response.success(req, res, 'Hola')
		    })*/
		    
		    
		    
		    module.exports = routes
		    
		    
		```

* **daag13** (2) [944233](https://platzi.com/comentario/944233/) 

	Creo que hay que hacer un ejemplo práctico aterrizado a la realidad para poder entender bien los conceptos. En cierto punto del curso me quedé perdido preguntando la razón del por qué se abrieron dos módulos, Message y User.

	* **Juan José Vega Quintero** [944233] (1)

		Sí, creo lo mismo  
		Toca usar la imaginación para entender la idea

* **raparisg** (2) [941456](https://platzi.com/comentario/941456/) 

	La gracia de Mongo es que es schema less. ¿Por qué tuvo que borrar los documentos anteriores para que el populate funcione? Qué otra alternativa tenemos para eso? Porque no creo que sea lo más óptimo tener que borrar o modificar los documentos anteriores para hacer que este populate funcione

	* **daag13** [941456] (2)

		Interesante pregunta. Quedé con la misma duda.

* **Wilson Castro Medellin** (1) [1121015](https://platzi.com/comentario/1121015/) 

	Populater información? Al fin todo es relacionado

* **Anibal Fernando Ortega Piedrahita** (1) [1110189](https://platzi.com/comentario/1110189/) 

	Si ya tengo entidades relacionadas, ¿ no seria mejor tener un base de datos relacional ?

* **duacos** (1) [999440](https://platzi.com/comentario/999440/) 

	como hago si quiero usar populate exec y que el resto de los mensajes sigan guardados

	* **Iván Darío Sánchez Jiménez** [999440] (1)

		Modifique en la base de datos la collection message donde user sea un nombre y cambielo por un id de un usuario que exista el la collection user

* **gustavoalbertorestrepopelae** (1) [993622](https://platzi.com/comentario/993622/) 

	GET ‘<http://localhost:3000/chat>’
	``` 
	    {
	        "error": "",
	        "body": [
	            {
	                "users": [
	                    {
	                        "_id": "5e4a0c593d361d3df4d5ff3c",
	                        "name": "garestrepop",
	                        "__v": 0
	                    },
	                    {
	                        "_id": "5e4a0c961c10153d2cab8024",
	                        "name": "maria.restrepo",
	                        "__v": 0
	                    },
	                    {
	                        "_id": "5e4a0d46ebcf0505883b3c26",
	                        "name": "jarango",
	                        "__v": 0
	                    },
	                    {
	                        "_id": "5e4b5142d52a641ad02110f4",
	                        "name": "rvanegas",
	                        "__v": 0
	                    }
	                ],
	                "_id": "5e4cae2757b57013d8a84d11",
	                "__v": 0
	            },
	            {
	                "users": [
	                    {
	                        "_id": "5e4a0c593d361d3df4d5ff3c",
	                        "name": "garestrepop",
	                        "__v": 0
	                    },
	                    {
	                        "_id": "5e4a0c961c10153d2cab8024",
	                        "name": "maria.restrepo",
	                        "__v": 0
	                    }
	                ],
	                "_id": "5e4cae5857b57013d8a84d12",
	                "__v": 0
	            }
	        ],
	        "status": 200
	    }
	    
	```

* **juanvalero252** (1) [992658](https://platzi.com/comentario/992658/) 

	literalmente estoy estancado aquí

* **Byron Mesias Cueva Cabrera** (1) [971692](https://platzi.com/comentario/971692/) 

	Reto realizado  
	![reto2.png](https://static.platzi.com/media/user_upload/reto2-7c46be00-e860-4eed-9aab-1f50f1e22e9a.jpg)

* **caprilespe** (1) [947854](https://platzi.com/comentario/947854/) 

	Reto: ChatComponent
	
	chat/controller.js
	``` 
	    const store = require("./store");
	    
	    functionaddChat(chat) {
	      if (!chat.users) {
	        returnPromise.reject("Invalid request.");
	      }
	      return store.add(chat);
	    }
	    
	    functiongetChats() {
	      return store.list();
	    }
	    
	    module.exports = {
	      addChat,
	      getChats
	    };
	    
	```
	
	chat/model.js
	``` 
	    const mongoose = require("mongoose");
	    
	    constSchema = mongoose.Schema;
	    
	    const mySchema = Schema({
	      users: [
	        {
	          type: Schema.Types.ObjectId,
	          ref: "User"
	        }
	      ]
	    });
	    
	    const model = mongoose.model("Chat", mySchema);
	    
	    module.exports = model;
	    
	```
	
	chat/network.js
	``` 
	    const express = require("express");
	    const responseType = require("../../network/response");
	    const controller = require("./controller");
	    const router = express.Router();
	    
	    router.post("/", function(request, response) {
	      const { users } = request.body;
	      controller
	        .addChat({ users })
	        .then(data => {
	          responseType.success(request, response, data, 200);
	        })
	        .catch(error => {
	          responseType.error(request, response, "Internal error", 500, error);
	        });
	    });
	    
	    router.get("/", function(request, response) {
	      controller
	        .getChats()
	        .then(data => {
	          responseType.success(request, response, data, 200);
	        })
	        .catch(error => {
	          responseType.error(request, response, "Internal error", 500, error);
	        });
	    });
	    
	    module.exports = router;
	    
	```
	
	chat/store.js
	``` 
	    const Model = require("./model");
	    
	    functionaddChat(chat) {
	      const newChat = new Model(chat);
	      console.log(newChat);
	      return newChat.save();
	    }
	    
	    asyncfunctiongetChats() {
	      returnnew Promise((resolve, reject) => {
	        Model.find()
	          .populate("users")
	          .exec((error, populated) => {
	            if (error) {
	              reject(error);
	              returnfalse;
	            }
	            resolve(populated);
	          });
	      });
	    }
	    
	    module.exports = {
	      add: addChat,
	      list: getChats
	    };
	    
	```
	
	resultado:
	
	![post.PNG](https://static.platzi.com/media/user_upload/post-76938b86-ddf7-4b5b-a4b8-76f7ee97ef99.jpg) ![get.PNG](https://static.platzi.com/media/user_upload/get-a558e62e-b243-47bf-8d72-4e0c64e92830.jpg)

* **RafaelEchart** (1) [849339](https://platzi.com/comentario/849339/) 

	Estoy estancado 😠

	* **Ruben Padilla** [849339] (3)

		Que mas Rafael? Puedo ayudarte?
		
		Con que tema estas encontrando dificultad?

	* **RafaelEchart** [849339] (1)

		codigo de model.js
		``` 
		    <const mongoose = require('mongoose')
		    
		    const Schema = mongoose.Schema
		    
		    const mySchema = new Schema({
		        user: {
		            type: Schema.ObjectId,
		            ref: 'user',
		        },
		        message: {
		            type: String,
		            required: true,
		        },
		        date: Date,
		    })
		    
		    const model = mongoose.model('Message', mySchema)
		    module.exports = model
		    >
		    
		```
		
		codigo de store.js
		``` 
		    <functiongetMessage(filterUser) {
		        returnnew Promise((resolve, reject) => {
		            let filter = {}
		            if (filterUser !== null) {
		                filter = { user: filterUser }
		            }
		            Model.find(filter)
		                .populate('user')
		                .exec((error,populated)=>{
		                    if(error){
		                        reject(error)
		                        returnfalse
		                    }
		                    resolve(populated)
		                })
		            
		            
		        })>
		    
		```
		
		error en terminal:
		
		“[Response error: ]MissingSchemaError: Schema hasn’t been registered for model “user”.  
		Use mongoose.model(name, schema)”
		
		y en insomnia aparece:
		
		{  
		“error”: “Unexpectec errror”,  
		“body”: “”  
		}
		
		**Ademas he encontrado que el error es en el ‘.populate(‘user’)’ y que si escribo por ejemplo:  
		**
		``` 
		    <functiongetMessage(filterUser) {
		        returnnew Promise((resolve, reject) => {
		            let filter = {}
		            if (filterUser !== null) {
		                filter = { user: filterUser }
		            }
		            Model.find(filter)
		                .populate('hgfskhfglsdikufgslkfgslkjfg')
		                .exec((error,populated)=>{
		                    if(error){
		                        reject(error)
		                        returnfalse
		                    }
		                    resolve(populated)
		                })
		            
		            
		        })>
		    
		```
		
		no da ningun error y puedo hacer el get de mis mensajes, pero, obviamente no se vinculan el componente  
		mensajes con el usuario.
		
		Cabe recalcar que mi codigo funcionaba perfecto hasta que hice os cambios del populate para enlazar las entidades  
		si pudieses ayudarme seria fantastico y te lo agradeceria muchisimo…

	* **Ruben Padilla** [849339] (2)

		Por favor revisa el codigo donde declaras el user schema, por el error que comentas parece ser que no lo has registrado en el esquema con mongoose, o no lo estas exportando || importando al archivo donde lo estas usando…
		
		“[Response error: ]MissingSchemaError: Schema hasn’t been registered for model “user”.  
		Use mongoose.model(name, schema)”
		
		Si es posible comparte el codigo correspondiete al componente user, asi podemos ver con mas facilidad por que no se estan relacionando.
		
		Saludos.

	* **RafaelEchart** [849339] (1)

		Hola, he revisado el codigo de user y message en el componente Model.js y todo esta corriendo, recibo las peticiones GET pero no se vincula…  
		Adjunto todo mi proyecto en un archivo ZIP por si me puedes ayudar tu u otra persona… Me ayudaria muchisimo a continuar mis cursos…
		
		<https://drive.google.com/open?id=1zOYGDBBCVW7iw6k6tek4qBsR8i1X-Agm>
		
		Esta conectado a mi cluster y solo habria que bajar las dependencias… GRACIAS!

	* **Carlos Hernández** [849339] (1)

		Hola, Rafael,
		
		No puedo acceder al enlace con tu código, creo que no tiene los permisos adecuados.
		
		Parece que hay algún problema en el componente user, específicamente al definir el modelo.
		
		Si me puedes compartir estos archivos, lo revisamos.
		
		Gracias!

	* **RafaelEchart** [849339] (1)

		Gracias por su atencion Profesor Carlos, le adjunto el codigo:
		
		Codigo user/model.js
		``` 
		    const mongoose = require('mongoose')
		    
		    const Schema = mongoose.Schema
		    
		    const userSchema = new Schema({
		       name: String,
		    })
		    
		    const model = mongoose.model('Users', userSchema)
		    module.exports = model ```
		    
		    
		    
		    
		    
		    ------------------------------------------------
		    
		    Aqui hay otro link para descargar el proyecto, espero esta vez no haya ningun problema
		    
		    LINK: https://mega.nz/#F!8VRk3CrJ!jhiKi-iRZsoizhmkKACU0A
		    
		    Le agradezco su atencion, espero poder comprender cual fue el problema.
		    
		    PD: al hacer peticiones (get, post,patch,delete) todas se realizan pero en las GET no se relaciona el objectID con USER
		```

	* **José Carlos Estrada Narcizo** [849339] (2)

		Buenas tardes Rafael.
		
		Puedes resolver el problema cambiando el nombre del modelo  
		Ejemplo:
		``` 
		    <code>
		    const mongoose = require('mongoose')
		    
		    const Schema = mongoose.Schema
		    
		    const userSchema = new Schema({
		       name: String,
		    })
		    
		    const model = mongoose.model('user', userSchema)
		    module.exports = model
		    
		```

	* **RafaelEchart** [849339] (1)

		**Muchas gracias Jose.estrada… ** gracias a lo que me aconsejaste pude ver que en moongose se habia creado una coleccion llamada Users, y al cambiarlo a ‘User’ en el codigo, daba error…
		
		GRACIAS, me permitiste seguir.
		
		👍👍👍👍👍Excelente servicio👍👍👍👍👍

* **JaimeRamos** (1) [762990](https://platzi.com/comentario/762990/) 

	por qué usas ; en javascript?

	* **Juan David Castro (Platzi)** [762990] (4)

		👋 Hey!
		
		Es más que todo para asegurarnos de que el código que escribimos es exactamente el que queremos hacer funcionar.
		
		Por ejemplo:
		``` 
		    # Usando punto y coma:
		    a = b + c;
		    (d + e).print();
		    
		    # Sin usar punto y coma:
		    
		    # Esto:
		    a = b + c 
		    (d + e).print() 
		    
		    # Se transforma n esto:
		    a = b + c(d + e).print();
		    
		```
		
		Referencias:
		
		👉 <https://dev.to/adriennemiller/semicolons-in-javascript-to-use-or-not-to-use-2nli>  
		👉 <https://flaviocopes.com/javascript-automatic-semicolon-insertion/>

	* **Martinez Palacios** [762990] (2)

		Es cierto que en Javascript no es necesario ponerle ; pero es buena practica hacerlo, así al momento de programar en otro lenguaje no cometemos ese error. Y también es bueno por lo dice Juan David, así que siempre pone ; aunque te gaste mas el dedo, jajaja

* **Francisco Javier Vázquez Paredes** (1) [762004](https://platzi.com/comentario/762004/) 

	Mi respuesta al Reto:  
	Network:
	``` 
	    const express = require('express')
	    const controller  = require('./controller')
	    const response = require('../../network/response')  
	    const router = express.Router()
	    
	    router.route("/")
	    .all((req, res, next) => {
	        console.log("Accedo a la ruta /chat")
	        next()
	    })
	    .post(async (req, res) => {
	        try{
	            let users = req.body.users.split(",")            
	            const newChat = await controller.createChat(users)
	            console.log(newChat)
	            response.success(req, res, 201, newChat)
	        }catch(error){
	            console.log(error)
	            response.error(req,res,null,error)
	        }
	    })
	    .get(async (req, res) => {
	        try{
	            const chatList = await controller.chatList(null)
	            response.success(req, res, null, chatList)
	        }
	        catch(error){
	            response.error(req, res, 500, error)
	        }
	    })
	    
	    router.get('/:id', async (req, res) => {
	        try{
	            const chatId = req.params.id || null;
	            const chatList = await controller.chatList(chatId)
	            response.success(req, res, null, chatList)
	        }
	        catch(error){
	            response.error(req, res, 500, error)
	        }
	    })
	    
	    module.exports = router;
	    
	```
	
	Controller:
	``` 
	    const store = require('./store')
	    
	    functioncreateChat(users){
	        returnnewPromise((resolve, reject) => {
	            if(!users){
	                console.error(`[chatController] Invalid Data`)
	                reject('La información no es correcta')    
	                returnfalse; //Este return se utiliza para terminar la ejecucion de la promesa          
	            }
	    
	            if(users.length == 0){
	                console.error(`[chatController] Empty Array`)
	                reject('La información no es correcta')    
	                returnfalse; //Este return se utiliza para terminar la ejecucion de la promesa          
	            }
	    
	            const newChat = {
	                users: users
	            }
	                  
	            store.create(newChat)
	    
	            resolve(newChat)
	        })
	    }
	    
	    functionchatList(chatId){
	       return store.list(chatId)
	    }
	    
	    module.exports = {
	        createChat,
	        chatList,
	        // updateMessage,
	        // deleteMessage
	    }
	    
	```
	
	Store:
	``` 
	    const Model = require('./model')
	    
	    const createChat = function(chat){
	        const myChat = new Model(chat)
	        return myChat.save()
	    }
	    
	    const listChats = function(chatId){
	        returnnew Promise((resolve, reject) => {
	            let filter = {};
	            if(chatId !== null){
	                filter = { _id: chatId }
	            }
	            Model.find(filter)
	            .populate('users')
	            .exec((error, populated) => {
	                if(error){
	                    reject(error)
	                    returnfalse                
	                }            
	    
	                resolve(populated)
	            });
	        })
	    }
	    
	    module.exports = {
	        create: createChat,
	        list: listChats
	    }
	    
	```

* **Carlos Alex Becerra Chavita** (1) [731501](https://platzi.com/comentario/731501/) 

	mi codigo en network.js asi:
	
	`router.get('/', (req, res) => { controller.listUser() .then(users => { response.success(req, res, users, 200); }) .catch(er => { response.error(req, res, 'Internal Error', 500, er); }); });`
	
	el resto esta igual

## 0270. Cómo recibir ficheros desde NodeJS [22634](https://platzi.com/clases/1689-backend-js/22634-como-recibir-ficheros-desde-nodejs/)

### Descripción:


En esta clase utilizaremos `multer` para subir archivos a través de nuestros chats.

### Comentarios:

* **oqodigital** (13) [838161](https://platzi.com/comentario/838161/) 

	Si te perdiste, pero tienes el código bien.  
	Borra los mensajes de la base de datos.  
	Ten creados dos usuarios en la base de datos.  
	Ahora ve a crear un chat nuevo (POST) y debe ser un body JSON así:
	``` 
	    {
	    	"users": [
	    		"idDelUser1",
	    		"idDelUser2"
	    	]
	    }
	    
	```
	
	Luego, ve a crear un mensaje (POST), a diferencia de la versión anterior, ahora se de le debe agregar el id del chat correspondiente de la creación que hicimos.
	``` 
	    {
	    	"chat": "idChat",
	    	"user": "idUser1",
	    	"message": "mensaje"
	    }
	    
	```
	
	Ahí puedes crear más mensajes.
	
	Luego para hacer el GET de chat, debes poner el ID del User en la URL:  
	<http://localhost:3000/chat/userId>
	
	😃

	* **Fernando Cordero** [838161] (1)

		todo bien hasta qeu hago el GET de chat y me muestra vacio el mensaje

	* **juanvalero252** [838161] (1)

		me pasa exactamente lo mismo, cuando hago la petición Get del chat me sale un array vació… esperando su respuesta para avanzar, creo que hay alguna confusión con las clases

	* **duacos** [838161] (1)

		juanvalero252 verifica el store y network en la sección en donde pones la lista.

	* **Alfonso Navarro** [838161] (1)

		Muchas gracias por el aporte, por mi parte me sirvio muchisimo, no entendi ese salto en la clase…

	* **Emanuel Valero** [838161] (1)

		Excelente! Gracias por el aporte. Funcionó a la perfección.

* **Camilo Andrés Santana Lizcano** (7) [861862](https://platzi.com/comentario/861862/) 

	Si usan PostMan y les salta error al usar form-data sólo tienen que desactivar el Header de content-type

	* **Harkrer** [861862] (1)

		Gracias!!

* **OmarGnzlz645** (4) [1010085](https://platzi.com/comentario/1010085/) 

	Al enviar la imagen se guardaba como binario, yo solucione el problema así , obteniendo la extensión del nombre original archivo
	``` 
	    const path = require("path")
	    const multer = require("multer")
	    
	    const storage = multer.diskStorage({
	        destination : "uploads/",
	        filename : function (req, file, cb) {
	            cb(null, file.fieldname + "-" + Date.now() + 
	            path.extname(file.originalname))
	        }
	    })
	    
	    const upload = multer({ storage: storage });
	    
	```

* **René Sanchez** (4) [766858](https://platzi.com/comentario/766858/) 

	## Muy buena poder ingresar imagenes y documentos desde el multi-part data!!!
	
	* 
	
	
	Como no podia ver imagenes en mi windows ya que no es tan potente como linux… investige sobre como añadir la extencion y poder tener el archivo correto en mi nodejs.
	
	## Les comparto una pagina de stackoverflow donde se explica el procedimiento:
	
	<https://stackoverflow.com/questions/31592726/how-to-store-a-file-with-file-extension-with-multer>
	
	* 
	
	
	Tiene muchas funcionalidades para poder hacer cositas entretes viendo el repo donde te indican como debe hacerse paso a paso entiendo todo:
	
	<https://github.com/expressjs/multer>

	* **Cesar Velásquez Córdova** [766858] (2)

		Muchas gracias, muy buenísimo aporte!!

	* **JUAN SILVA** [766858] (2)

		Un consejo de corazón, si quieres programar de forma profesional PASATE A LINUX

	* **René Sanchez** [766858] (1)

		Ya uso linux desde que inicie 😃, pero por temas laborales mayormente tengo que usar windows si no fuera por una jodida compatibilidad pero en cuanto pase la garantia de mi equipo comprado.
		
		* * *
		
		Tendria que hecharle algunas ojeadas despues que ya no posea la garantia, Estare probando con manjaro o Debian.
		
		* * *
		
		Cualquier recomendacion de distros es bienvenida 😃

	* **René Sanchez** [766858] (1)

		Jamas uso la shell de windows, los comandos por terminal linux no me los saca nadie, Uso gitbash y bash con zsh para poder hacer configuraciones entre otras cosas.
		
		En vscode uso gitbash por defecto y en otras uso zsh(linux subsystem)

* **Gianfranco Giordano** (3) [1074184](https://platzi.com/comentario/1074184/) 

	creo que es interesante saber que tenemos esta hermosa web: <https://www.npmjs.com/>  
	para encontrar lo que necesitemos instalar, como utilizarlo, etc … Espero sea de provecho este comentario para la comunidad Platzi.

* **Nicolasdds** (3) [839744](https://platzi.com/comentario/839744/) 

	Cual es el formato json correcto para enviar mensajes ahora?  
	Porque esto:
	``` 
	    {	
	    	"user": "5dde5d5629714e036671b618",
	    	"chat": "5dde70a292162a07820c6bf6",
	    	"message": "Hola Mundo"
	    }
	    
	```
	
	Me devuelve:
	``` 
	    {
	      "error": "Informacion inválida",
	      "body": ""
	    }
	    
	```

	* **Iair Poloniecki** [839744] (1)

		El mensaje de abajo de oqodigital responde tu pregunta

	* **RafaelEchart** [839744] (1)

		hola companero, tuve creo que tu mismo problema, primero en el model.js de CHAT tienes que tener el campo Users definido como ARRAY. de esta manera>
		``` 
		    const mongoose = require('mongoose');
		    
		    const Schema = mongoose.Schema;
		    
		    const mySchema = new Schema({
		        users: [{
		            type: Schema.ObjectId,
		            ref: 'User',
		        }],
		    });
		    
		    const model = mongoose.model('Chat', mySchema);
		    module.exports = model;```
		    
		    
		    DATE CUENTA COMO DESPUES DE USERS: EMPIEZA CON UN [] Y DESPUES VIENE EL {}
		    
		    
		    en Inmsonia tienes que escribir:
		    POST=> localhost:3000/chat/
		    
		    
		    
		    
		```
		
		{  
		“users”: [“ID de usuario ya creado en componente usuario”,“ID de usuario ya creado en componente usuario”]
		``` 
		    recuerda que primero tienes que haber creado dos usuarios en el componente usuario para que el populate funcione.
		    
		    Vi una recomenadacion enla seccion de comentarios sobre borrar todos los mensajes primero y luego mandar un mensaje nuevo con todos los campos nuevos. 
		    
		    Espero haberte ayudado..
		    
		```

* **reignover** (3) [797696](https://platzi.com/comentario/797696/) 

	El proyecto no se puede descargar completo o es mi impresión? deja ir viendo lo que uno necesita y no se puede navegar hacía atrás

* **Jose Gonzalez** (3) [744169](https://platzi.com/comentario/744169/) 

	Comando para el populate del message teniendo en cuenta el `chat` y los `users dentro de`chat`.
	``` 
	    exportconst getMessages = async (filterUser: IMessages) => {
	      returnnew Promise((resolve, reject) => {
	        MessageModel.find(filterUser)
	          .populate('user')
	          .populate({
	            path: 'chat',
	            populate: {
	              path: 'users',
	            },
	          })
	          .exec((error, res) => {
	            if (error) {
	              return reject(error);
	            }
	            resolve(res);
	          });
	      });
	    };
	    
	```

* **john jairo lopez ramirez** (3) [69572](https://platzi.com/comentario/759000/) 
Como se hace un post para chat?

	* **Andres Roberto Coello Goyes** [69572] (3)

		tienes que crear en el network una nueva ruta.
		``` 
		    router.post('/', function( req, res){
		    	controller.addMensaje(req.body.user, req.body.messaje)
		    		.then( (fullMesaje) => {
		    			response.success(req, res, fullMesaje, 200);	
		    		})
		    		.catch(e => {
		    			response.error(req, res, 'error simulado', 500, "es solo una simulacion de errores");
		    		});
		    });
		    
		```
		
		y lo demas se encuentra en este curso…

* **Alver Ortega** (2) [959488](https://platzi.com/comentario/959488/) 

	Guarda la imagen cómo binario, para solucionarlo obtengo la extensión del archivo a cargar.
	``` 
	    const multer = require('multer');
	    
	    const storage = multer.diskStorage({
	        destination: function (req, file, cb) {
	            cb(null, 'public/uploads/');
	        },
	        filename: function (req, file, cb) {
	            const [name, extension] = file.originalname.split('.');
	            cb(null, `${name}-${Date.now()}.${extension}`)
	        }
	    })
	    
	    const upload = multer({ storage: storage });
	    router.post('/', upload.single('file'), function (req, res) {
	        controller.addMessage(req.body.chat, req.body.user, req.body.message)
	            .then((response) => responses.success(req, res, response))
	            .catch((error) => responses.error(req, res, error, 400, 'Error en el controlador'))
	    });
	    
	```

* **Harkrer** (2) [946824](https://platzi.com/comentario/946824/) 

	Si te guarda la imagen… pero como un binario sin extensión. Puedes setear el formato de la imagen de la siguiente forma:  
	(Windows)
	``` 
	    var storage = multer.diskStorage({
	        destination: function (req, file, cb) {
	          cb(null, 'uploads/')
	        },
	        filename: function (req, file, cb) {
	          cb(null, Date.now() + '.jpg') //Appending .jpg
	        }
	    })
	    
	    const upload = multer({
	        storage: storage
	    })
	    
	    router.post('/', upload.single('file'), function(req, res){ ...
	    
	    
	```

	* **lsolares** [946824] (1)

		Muy interesante! Mira una consulta porque defines un request y que es el cb?

	* **Alejandro Barba** [946824] (1)

		Isolares:  
		El método diskStorage utiliza dos funciones para definir el destino del archivo y su nombre. En la función destination el parámetro “cb” tiene como función manejar el error y establecer su ubicación.  
		En la función filename el parámetro cb tiene como objetivo manejar el error también y definir el nombre del archivo.  
		El parámetro req me imagino que es para manejar el contenido del archivo, pero no me hagas mucho caso en esto último.

* **Kevin William Roberts Costa** (2) [832752](https://platzi.com/comentario/832752/) 

	Qué quilombo se me enredó todo

* **Juan Barboza** (2) [70097](https://platzi.com/comentario/768958/) 
¿Cómo se hace un request post para chat en insomnia? Me está dando el siguiente error y hace rato que intento, pienso que mi problema est...

	* **Lucas Villarreal** [70097] (4)

		Hola, de la siguiente forma:
		``` 
		    {
		        "users": [ID_USUARIO_1, ID_USUARIO_2, ...]
		    }
		    
		```
		
		Donde “users” es como definiste el nombre en el model.js  
		Espero te sea util.

* **Wilson Castro Medellin** (1) [1121071](https://platzi.com/comentario/1121071/) 

	Mensajes como archivos ayudados con multer. Interesante

* **carlosextra1** (1) [1064917](https://platzi.com/comentario/1064917/) 

	woo que bien, hasta aquí vamos al paso!!

* **Enrique Alexis Lopez Araujo** (1) [1024547](https://platzi.com/comentario/1024547/) 

	Aqui tengo una duda, que he estado buscando si quisiera mantener la busqueda en el get de message tanto por el nombre del usuario como por el id del chat como tendria que quedar nuestro controller de getmessages ya intente meterle dos veces el query param para poder filtrar tanto por el chat id y por el name del user y no me sale. 😢

	* **Diego Alexander Forero Higuera (Platzi)** [1024547] (1)

		Puedes compartir el código de lo que has intentado para ver como podemos ayudarte.

* **OmarGnzlz645** (1) [1008363](https://platzi.com/comentario/1008363/) 

	Les dejo el link con información sobre multer
	
	<https://www.npmjs.com/package/multer>

* **aerama** (1) [993856](https://platzi.com/comentario/993856/) 

	termina la parte de integracion de chat e inicia la parte de lectura de ficheros

* **Alejo Goncalves** (1) [853606](https://platzi.com/comentario/853606/) 

	cuando hago una peticion get de mi chat me dice que data no esta definido, alguna ayuda?
	
	controller.js
	``` 
	    const store = require('./store');
	    
	    functionaddChat(users){
	        if(!users || !Array.isArray(users)){
	            returnPromise.reject('Invalid user list')
	        }
	        const chat={
	            users: users,
	        };
	        return store.add(chat); 
	    }
	    
	    functionlistChats(userId){
	        return store.list(userId);
	    }
	    
	    module.exports = {
	        listChats,
	        addChat,
	    }
	    
	```
	
	model.js
	``` 
	    const mongoose = require('mongoose');
	    
	    const Schema = mongoose.Schema;
	    
	    const mySchema = new Schema({
	        users:{
	            type: Schema.ObjectId,
	            ref: 'user'
	        }
	    
	    }); 
	    
	    const model = mongoose.model('Chat', mySchema);
	    
	    module.exports = model;
	    
	```
	
	network.js
	``` 
	    const express = require('express');
	    const router = express.Router();
	    const response = require('../../Network/responses');
	    const controller = require('./controller');
	    
	    router.post('/', function(req, res){
	        controller.addChat(req.body.users)
	        .then((data)=>{
	            response.success(req, res, data, 201);
	        })
	        .catch(err=>{
	            response.error(req, res, 'Internal error', 500, err)
	        })
	    });
	    
	    router.get('/:userId', function(req, res){
	        controller.listChats(req.params.userId)
	        .then(users=>{
	            response.success(req, res, users, 200);
	        })
	        .catch(err=>{
	            response.error(req, res, data, 500, err);
	        })
	    })
	    
	    module.exports = router;
	    
	```
	
	store.js
	``` 
	    const Model = require('./model');
	    
	    functionaddChat(chat){
	        const myChat = new Model(chat);
	        return myChat.save();   
	    }
	    
	    functionlistChats(usrId){
	        returnnew Promise((resolve, reject)=>{
	            let filter = {};
	            if (userId){
	                filter = {
	                    users: userId,
	                }
	            }
	            Model.find(filter)
	                .populate('users')
	                .exec((err, populated)=>{
	                    if(err){
	                        reject(err);
	                        returnfalse;
	                    }
	                    resolve(populated);
	                })
	            
	        })
	    }
	    
	    module.exports = {
	        add: addChat,
	        list: listChats,
	    }
	    
	```

	* **Fernando Cordero** [853606] (1)

		en el network fijate bien que estas usando users en vez de data. Al no tener data te arroja undefined

	* **Cristian Daniel Norberto  Toffalo** [853606] (1)

		Creo que tu problema está en el network pero en esta función
		``` 
		    router.get('/:userId', function(req, res){
		        controller.listChats(req.params.userId)
		        .then(users=>{
		            response.success(req, res, users, 200);
		        })
		        .catch(err=>{
		            response.error(req, res, data, 500, err);
		        })
		    })```
		    
		    si observás, tu parámetro se llama "err" pero luego enviás en el response.error un tercer parámetro "data"quenoestá definido
		    
		```

* **Nicolasdds** (1) [839759](https://platzi.com/comentario/839759/) 

	![](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwi6qqLQvormAhViH7kGHQnzBYIQjRx6BAgBEAQ&url=https%3A%2F%2Fgiphy.com%2Fexplore%2Ftelefono&psig=AOvVaw0ZkhGc8VuFD7iTGWHpb8vk&ust=1574947434237711)  
	Me voy de este curso hasta que alguien conteste…

* **deveeup** (1) [829149](https://platzi.com/comentario/829149/) 

	Están invertidos los videos, creo que este va después del que le sigue…

* **JaimeRamos** (1) [786505](https://platzi.com/comentario/786505/) 

	por qué mis fotos se guardan como una especie de binario?

	* **deveeup** [786505] (2)

		En el network.js (messages), agrega esta función, la cual tiene como objetivo cambiar el nombre del archivo.
		``` 
		    const storage = multer.diskStorage({
		      destination: function(req, file, cb) {
		        cb(null, "public/files/");
		      },
		      filename: function(req, file, cb) {
		        cb(null, Date.now() + path.extname(file.originalname));
		      }
		    });```
		    
		```

* **Sandra Milena Rairán Pinilla** (1) [727608](https://platzi.com/comentario/727608/) 

	Hola!! Por favor nos comparten el código de las clases?
	
	Me podrían orientar cómo se hace en postman el “Multipart Form”. ?.  
	Gracias

	* **ricardocelis (Platzi)** [727608] (2)

		claro que si! ya te lo comparto

	* **ricardocelis (Platzi)** [727608] (6)

		<https://github.com/CodingCarlos/backend-node-platzi/tree/92957457c1bf790d2a33446392ae0680ffc0174d>

	* **jose-noel-marenco** [727608] (1)

		Muchas gracias.

	* **beaps** [727608] (6)

		Lo de **multipart/form-data** en Postman se haría así:  
		  
		![](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/form-data1.gif)
		
		<https://learning.getpostman.com/docs/postman/sending_api_requests/requests/>

* **chris_x** (1) [86558](https://platzi.com/comentario/1098571/) 
No entiendo como el filter funciona en el caso de GET /chat : Obtenemos un unico objectID para filtrar los chats de este usuario, pero so...

* **Rafael Muñoz Pérez** (1) [86310](https://platzi.com/comentario/1093211/) 
No entiendo como estructurar la petición POST del chat, entiendo que en el req.body.users, pero en el envio de los datos no se si enviar ...

* **Missael Mora** (1) [83102](https://platzi.com/comentario/1019475/) 
[nodemon] restarting due to changes... [nodemon] startingnode server.js` C:\Users\Asus\Documents\NodeJS\node_modules\express...

	* **Luis Arturo Lira Cerda** [83102] (1)

		Cómo tienes tu código? Dice que no se le está pasando lo que espera a Router.use()

* **juanvalero252** (1) [81905](https://platzi.com/comentario/993045/) 
en el minuto 4:07 pueden ver que el ID del chat es el mismo del user. alguien me puede explicar xq?

	* **JerezA** [81905] (1)

		realmente puedes filtrar por tanto el chat como el usuario, independientemente del ObjectId que digites

* **jk_** (1) [76296](https://platzi.com/comentario/884712/) 
Buenas noches Disculpen que pasaria si quiero que me pueble con lo de Chat y con lo de Usarios a la Vez

* **Deyvis Neyser Valdez Gavilan** (1) [70181](https://platzi.com/comentario/770165/) 
Hola, ¿A alguien más se le subió la imagen sin una extensión definida?. ¿Se podría arreglar este detalle?, gracias.

	* **Juan David Castro (Platzi)** [70181] (1)

		¡Hola! El profesor también sube la imagen sin extensión. Puedes añadirla siguiendo esta guía: <https://stackoverflow.com/questions/31592726/how-to-store-a-file-with-file-extension-with-multer>.

## 0280. Guardar el fichero en el servidor [22635](https://platzi.com/clases/1689-backend-js/22635-guardar-el-fichero-en-el-servidor/)

### Descripción:


### Comentarios:

* **Joaquin Mayer Breitkreitz** (4) [730542](https://platzi.com/comentario/730542/) 

	¿Porqué cuando subo un archivo, no me pone la extensión del mismo?

	* **Victor Martin Ortiz Palacio** [730542] (5)

		Entiendo que es por una cuestion de seguridad, de todos modos, se lo podes agregar utilizando el modulo path, yo lo hice guiandome de este post:  
		<https://alejandrojs.wordpress.com/2017/08/23/subiendo-archivos-en-node-usando-multer/>

	* **Carlos Hernández** [730542] (9)

		La respuesta corta, para asegurar que no hay dos archivos con el mismo nombre.  
		.  
		La respuesta larga tiene que ver con cómo se procesan archivos, y la poca utilidad del nombre o la extensión (a nivel maquina) para definir el tipo de archivo. Dentro de todos los archivos, hay una serie de información sobre el tipo de archivo que es, y la forma de leerlo. Por eso, multer no se preocupa de las extensiones.  
		.  
		Si quieres añadirla, puedes poner un middleware en el que modifiques el nombre del archivo que se va a generar. En este post de StackOverflow puedes ver más en detalle como hacerlo:  
		[](https://stackoverflow.com/questions/31592726/how-to-store-a-file-with-file-extension-with-multer)

	* **Sebastian Cardoso Castillo** [730542] (1)

		¿Cuál post de Stackoverflow?

	* **Jair Israel Avilés Eusebio** [730542] (3)

		Hola, comparto mi solucion de este problema en mi repostorio dentro de este [commit](https://github.com/JairAviles/backend-message/blob/9a3da0910cb56f3cdf820691a8f4fd3bbfb532a3/components/message/network.js#L7).
		
		Mukter tiene una funcion de nombre `diskStorage` el cual segun la [documentacion oficial](https://github.com/expressjs/multer#diskstorage), te permite mayor control a los archivos que estan pasando por el middleware. En mi caso le paso un objeto con dos funciones.
		
		* **destination** \- Defines tu path a donde van a subirse los archivos
		* **filename** \- Defines el nombre del archivo de como se va almacenar tu archivo en la carpeta de destination. Lo que yo hago es anteponer la fecha y hora del momento en que es subido y concatenando el nombre original.
		
		
		
		De esta manera se sube con el nombre original y la extension del archivo.

	* **Jair Israel Avilés Eusebio** [730542] (1)

		Se me olvido especificar, cuando defines la variable storage, tienes que pasar el objeto que te regresa la funcion `diskStorage` como lo indico [aqui](https://github.com/JairAviles/backend-message/blob/9a3da0910cb56f3cdf820691a8f4fd3bbfb532a3/components/message/network.js#L16), lo demas sigue igual. Espero te sea util.

	* **jonathan2138** [730542] (1)

		gracias @yajairo87 que gran aporte bro

* **Andres Roberto Coello Goyes** (3) [782832](https://platzi.com/comentario/782832/) 

	```
	    var storage = multer.diskStorage({
	        destination: function (req, file, cb) {
	          cb(null, 'uploads/')
	        },
	        filename: function (req, file, cb) {
	          cb(null, Date.now() + path.extname(file.originalname)) //Appending extension
	        }
	      })
	    
	    const upload = multer({
	        storage: storage
	    });```
	    
	    para agregar la extencion del archivo...
	    
	```

	* **Wilson Marino Pablo Mendez** [782832] (2)

		cabe destacar que require la instalación del modulo path --> npm i path

	* **johneduardo** [782832] (1)

		A ti no te sale:  
		**Error: ENOENT: no such file or directory, open ‘C:\Users…\uploads\1573012846127.jpg’** ?
		
		Si no tengo la carpeta uploads ya creada, me sale ese error…  
		Tuve que modificar la function **destination** así:  
		`var storage = multer.diskStorage({ destination: 'public/files/', ...`

* **Emanuel Valero** (2) [1076665](https://platzi.com/comentario/1076665/) 

	Para quienes prefieran guardar sus imágenes con la extensión, pueden configurar multer de esta forma en el network:
	``` 
	    // upload files with multer
	    const storage = multer.diskStorage({
	        destination: (req, file, callback) => callback(null, 'public/files'),
	        filename: (req, file, callback) => {
	            const id = nanoid.nanoid(64);
	            const extension = path.extname(file.originalname);
	            const fileName = id + extension;
	            callback(null, fileName)
	      	}
	    });
	    
	    const upload = multer({ storage });
	    
	```
	
	Y luego en el controller, se genera el fileUrl asi:
	``` 
	    const fileUrl = file 
	        ? config.host + ':' + config.port + config.publicRoute + 
	           '/files/' + file.filename
	        : '';
	    
	```

* **SistemasCBC** (2) [871208](https://platzi.com/comentario/871208/) 
<h1>Aporte:</h1>
	
	realice el siguiente codigo para poder servir img desde mi api con la opcion de modificar la resolucion para optimizar la descarga de img.
	``` 
	    const express = require("express");
	    const multer = require("multer");
	    const router = express.Router();
	    const response = require("./../../network/response").error;
	    
	    const fs = require("fs");
	    const sharp = require("sharp");
	    const path = require("path");
	    
	    router.get("/:type/:width/:height/:fileName", async (req, resp) => {
	      const format = req.params.type || "png";
	      const width = parseInt(req.params.width) || 255;
	      const height = parseInt(req.params.height) || 255;
	      const file = req.params.fileName;
	    
	    
	      const readStream = fs.createReadStream(
	        path.join(__dirname, "./../../upload/", `${file}`)
	      );
	      readStream.on("error", e => {
	        resp.type(`application/json`);
	        response(
	          req,
	          resp,
	          "no se encuetnra la img solicitada",
	          400,
	          "[IMG] no se puede encontrar la img"
	        );
	      });
	      resp.type(`image/${format}`);
	      let transform = sharp();
	      transform = transform.toFormat(format);
	      transform = transform.resize(width, height);
	      readStream.pipe(transform).pipe(resp);
	    });
	    
	```

* **Wilson Castro Medellin** (1) [1121148](https://platzi.com/comentario/1121148/) 

	Excelente multer

* **Abraham Flores Cosme** (1) [1072408](https://platzi.com/comentario/1072408/) 

	Es ridículamente sencillo manejar archivos, en otros lenguajes tengo que lidiar con muchos problemas, excelente curso Carlos.

* **carlosextra1** (1) [1064942](https://platzi.com/comentario/1064942/) 

	El paquete de multer es genial, nos facilita mucho las cosas

* **Alver Ortega** (1) [959513](https://platzi.com/comentario/959513/) 

	mi aporte, trate de generar la url para no quemar nada y quede escalable por si se llega a desplegar en algun servidor
	``` 
	    router.post('/', upload.single('file'), function (req, res) {
	        let fileUrl = '';
	        if (req.file) {
	            fileUrl = `${req.protocol}://${req.get('host')}/${destination}${req.file.filename}`;
	        }
	        controller.addMessage(req.body.chat, req.body.user, req.body.message, fileUrl)
	            .then((response) => responses.success(req, res, response))
	            .catch((error) => responses.error(req, res, error, 400, 'Error en el controlador'))
	    });
	    
	```

	* **gustavoalbertorestrepopelae** [959513] (1)

		ileUrl =`${req.protocol}://${req.get('host')}:${req.get('port')}/${destination}${req.file.filename}`;

	* **Iván Darío Sánchez Jiménez** [959513] (4)

		O también lo podríamos hacer desde la variables de entorno en caso que el servidor para almacenar las imágenes sea diferente al servidor local.

* **Camilo Andrés Santana Lizcano** (1) [861887](https://platzi.com/comentario/861887/) 

	Y cómo guardamos esas imagenes directamente en base de datos ?

	* **Ken Ramirez** [861887] (1)

		Si no me equivoco podrías hacerlo convirtiéndola primero en base64

	* **SistemasCBC** [861887] (2)

		Es recomendable no guardar imagenes en una base de datos.  
		lo mejor que podes hacer es guardar la img en una carpeta y en la base de datos guardar la ubicación del archivo.

* **Andres Roberto Coello Goyes** (1) [838614](https://platzi.com/comentario/838614/) 

	en desarrollo me funciona perfecto,  
	pero hice deploy con now y me lanza el status 500  
	por esta razon…
	``` 
	    Error: ENOENT: no such fileordirectory, open'public/files/1574784627297-l-c.png'
	    
	```

* **Francisco Maneiro** (1) [832364](https://platzi.com/comentario/832364/) 

	Por alguna razon, el video anterior tiene el codigo adelantado a esta clase, pero los inicios y finales de estas tres ultimas clases, estan bien. No entiendo que paso alli, pero me causaron una confucion gigantesca, pero bueno a seguir con el curso

* **deveeup** (1) [829148](https://platzi.com/comentario/829148/) 

	Están invertidos los videos, creo que este va primero.

* **johneduardo** (1) [814238](https://platzi.com/comentario/814238/) 

	**Error: ENOENT: no such file or directory, open ‘C:\Users…\uploads\1573012846127.jpg’ **
	
	Si no tengo la carpeta uploads ya creada, me sale ese error…  
	Tuve que modificar la function destination así:  
	`var storage = multer.diskStorage({ destination: 'public/files/', ...`

* **rodhsoft** (1) [69967](https://platzi.com/comentario/767042/) 
en este punto como doy de alta un chat?

# Conocer el protocolo de websockets, e implementar comunicación cliente/servidor con SocketIO. [4539]

## 0290. WebSockets Qué son, por qué son interesantes y cómo usarlos [22636](https://platzi.com/clases/1689-backend-js/22636-websockets-que-son-por-que-son-interesantes-y-como/)

### Descripción:


El protocolo Websocket o `wss://` crea un túnel de información entre el usuario y el servidor el cual se quedará abierto hasta que el servidor y/o el cliente cierre la conexión para pedir información en tiempo real.

### Comentarios:

* **Jose Rodriguez Luis** (5) [817982](https://platzi.com/comentario/817982/) 

	Excelente explicación todos los conceptos deberían ser explicados utilizando este tipo de analogias

* **lizardojara** (4) [835099](https://platzi.com/comentario/835099/) 

	Al fin websockets, es una maravilla.

* **Jmundaca** (3) [757648](https://platzi.com/comentario/757648/) 

	que bueno mi Favorito , WebSocket’s

	* **Wilson Marino Pablo Mendez** [757648] (1)

		x2

* **c3tuxpo2018** (2) [1027236](https://platzi.com/comentario/1027236/) 

	Ok entonces websocket es un protocolo de comunicacion en tiempo real que crea un tunel entre un cliente y un servidor y que soporta multiples clientes conectados al mismo tunel es correcto??

	* **Diego Alexander Forero Higuera (Platzi)** [1027236] (2)

		Si. 😃

* **ehnbytes** (2) [975676](https://platzi.com/comentario/975676/) 

	Muy bien explicado!

* **Arlex Felipe Llanos Betancourt** (2) [880804](https://platzi.com/comentario/880804/) 

	Una gran explicación de los WebSockets y porque deberiamos utilizarlos, genial!

* **Wilson Castro Medellin** (1) [1121171](https://platzi.com/comentario/1121171/) 

	Protocolo WebSockets, nuevo concepto para mi. Muy entendible. Excelente!
	
	Que problemas se puede tener al mantener el tunel abierto

* **Anibal Fernando Ortega Piedrahita** (1) [1110500](https://platzi.com/comentario/1110500/) 

	¿Que diferencia existe entre una comunicación basada en eventos con un bus de eventos con colas mq y la comunicación con webSockets ?

* **Juan Carlos Valencia López** (1) [1085499](https://platzi.com/comentario/1085499/) 

	Se establece la conexión en el protocolo ws (websocket)

* **Juan Carlos Valencia López** (1) [1085488](https://platzi.com/comentario/1085488/) 

	Websockets nos permite complementar las peticiones http Fetch y AJAX dándole soporte a las aplicaciones en tiempo real

* **carlosextra1** (1) [1064973](https://platzi.com/comentario/1064973/) 

	YESSS!!! es por esto que he decidido aprender nodejs

* **Brandon Iván Quiroa Loarca** (1) [1055532](https://platzi.com/comentario/1055532/) 

	Websockets una red de comunicación abierta en tiempo real. 😄

* **MartinMB** (1) [979024](https://platzi.com/comentario/979024/) 

	Buena la teoría

* **johneduardo** (1) [814374](https://platzi.com/comentario/814374/) 

	Excelente explicación, perfectas analogías.  
	Mil gracias Carlos por los ejemplos.

* **LIBRE GESTION** (1) [82470](https://platzi.com/comentario/1005929/) 
Hola, alguien me puede ayudar, tengo el servidor https y luego le paso el servidor a websocket.io. ahor...

## 0300. Manejo de Websockets con NodeJS [22637](https://platzi.com/clases/1689-backend-js/22637-manejo-de-websockets-con-nodejs/)

### Descripción:


### Comentarios:

* **Juan J. López Lira** (4) [804870](https://platzi.com/comentario/804870/) 

	Me gusta mas la solución de Firebase con live database de firestore XD

	* **Omar Jesus Hernández Bastos** [804870] (1)

		Totalmente de acuerdo.

	* **OSCAR RODRIGUEZ** [804870] (4)

		No pues ya no programes de una vez cawnn.

* **Wilson Castro Medellin** (1) [1121225](https://platzi.com/comentario/1121225/) 

	Muy interesante

* **Rabi Leonel Leon Chan** (1) [1094501](https://platzi.com/comentario/1094501/) 

	Interesante😮😮😮😮

* **carlosextra1** (1) [1065015](https://platzi.com/comentario/1065015/) 

	Interesante !!!

* **Jorgelisapa** (1) [1024407](https://platzi.com/comentario/1024407/) 

	WebSockets de lo mejor!

* **Jhonnattan Rivera** (1) [1022993](https://platzi.com/comentario/1022993/) 

	este video me cambio la vida

	* **Juan José Vega Quintero** [1022993] (2)

		X2

* **MartinMB** (1) [979044](https://platzi.com/comentario/979044/) 

	Parece facil

* **ehnbytes** (1) [975678](https://platzi.com/comentario/975678/) 

	Wow!

* **Wilson Marino Pablo Mendez** (1) [793291](https://platzi.com/comentario/793291/) 

	Increible!!

* **lidiar86** (1) [76216](https://platzi.com/comentario/883103/) 
¿Y si quiero verificar los cambios en un archivo de correo, en este caso es archivo de thunderbird? En especifico, quiero verificar cuand...

	* **lidiar86** [76216] (1)

		Dentro del watch del archivo se debe de ejecutar un exec para ejecutar otro node que extrae la segmentación del correo y lo decodifica de base 64 para volver el adjunto el un archivo.

## 0310. Conectar la API al servidor de WebSockets [22638](https://platzi.com/clases/1689-backend-js/22638-conectar-la-api-al-servidor-de-websockets/)

### Descripción:


### Comentarios:

* **beaps** (22) [731597](https://platzi.com/comentario/731597/) 

	```
	    const socket = require('../../socket).socket;
	    
	```
	
	también se puede escribir así:
	``` 
	    const { socket } = require('../../socket');
	    
	```

	* **Carlos Hernández** [731597] (10)

		Object destructuring for the win! Muy bien visto, genial apunte 😉

* **José Pach Delgado** (10) [888613](https://platzi.com/comentario/888613/) 

	El espartano sapeeee.  
	Excelente curso.

* **Andres Roberto Coello Goyes** (5) [877869](https://platzi.com/comentario/877869/) 

	si estas utilizando React js debes instalar el cliente de socket  
	**npm install --save socket.io-client**
	``` 
	    var socket = socketIOClient('http://localhost:9000');
	                    socket.on('pedido', function (data) {
	                        console.log(data);
	                        socket.emit('my other event', { my: 'data' });
	                    });
	    
	```

* **Wilson Castro Medellin** (1) [1121304](https://platzi.com/comentario/1121304/) 

	Muy bien!

* **carlosextra1** (1) [1065195](https://platzi.com/comentario/1065195/) 

	AYUDA!!  
	me tira el siguiente error! pero no encuentro porque está pasando!
	``` 
	    La aplicación esta escuchando en pueto:3001
	    TypeError: socket.io.emmit is not a function
	        at /Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/componets/message/controller.js:24:19
	        at new Promise (<anonymous>)
	        at Object.addMessage (/Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/componets/message/controller.js:6:12)
	        at /Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/componets/message/network.js:20:16
	        at Layer.handle [as handle_request] (/Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/node_modules/express/lib/router/layer.js:95:5)
	        at next (/Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/node_modules/express/lib/router/route.js:137:13)
	        at Immediate.<anonymous> (/Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/node_modules/multer/lib/make-middleware.js:53:37)
	        at processImmediate (internal/timers.js:441:21)
	    [Response error] =>  TypeError: socket.io.emmit is not a function
	        at /Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/componets/message/controller.js:24:19
	        at new Promise (<anonymous>)
	        at Object.addMessage (/Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/componets/message/controller.js:6:12)
	        at /Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/componets/message/network.js:20:16
	        at Layer.handle [as handle_request] (/Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/node_modules/express/lib/router/layer.js:95:5)
	        at next (/Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/node_modules/express/lib/router/route.js:137:13)
	        at Immediate.<anonymous> (/Applications/XAMPP/xamppfiles/htdocs/platzi master/nodeJS/node_modules/multer/lib/make-middleware.js:53:37)
	        at processImmediate (internal/timers.js:441:21)
	    [db] Conectada con el server db
	    
	```

	* **Juan José Vega Quintero** [1065195] (1)

		Carlos tienes un typo es:
		``` 
		    <socket.io.emit('message', fullMessage)>
		    
		```
		
		tienes emmit

* **Andres Roberto Coello Goyes** (1) [877983](https://platzi.com/comentario/877983/) 

	websocket.js:120 WebSocket connection to 'ws://localhost:9000/socket.io/?  
	este es el error que tengo…

* **Andres Roberto Coello Goyes** (1) [877623](https://platzi.com/comentario/877623/) 

	mi situacion es que la api rest esta en en server y mi parte de cliente en otra con Next js… como le hago llevar la info al cliente

	* **jenapi** [877623] (2)

		Usas axios para hacer post y puedes utilizar ‘socket.io-client’ para conectarte a un socket

* **Alejo Goncalves** (1) [856849](https://platzi.com/comentario/856849/) 

	a donde va esto? que es?
	
	src= [socket.io/socket.io.js](http://socket.io/socket.io.js)

	* **Fernando Cordero** [856849] (1)

		Va en el src del script. y es un archivo que genera webSockets por defecto

* **john jairo lopez ramirez** (1) [820598](https://platzi.com/comentario/820598/) 

	Tengo un error hago lo que se hace en el video pero me dice "Cannot read property ‘io’ of undefined"  
	Esto en el código de controller.js

	* **Gabriel De Andrade (Platzi)** [820598] (2)

		Estás importando bien el módulo socket? Puedes mostrarnos tu código?

	* **john jairo lopez ramirez** [820598] (1)

		La cuestión es que el código es bastante largo, estoy intentando utilizar el método “on” de socket y es el principal que me genera problema, no comprendo muy claro en esa instancia que el hace (cuando llama socket = {}) que es lo que esta pasando a los demás módulos donde se pide el valor de este objeto.

* **DanielCu** (1) [86846](https://platzi.com/comentario/1105662/) 
Tengo duda, por que en la ruta. Se tiene que especificar asi? y no con dos puntos. /socket.io/socket.io.js

* **Lenin Bismarx Mendoza Mamani** (1) [78393](https://platzi.com/comentario/920343/) 
¿Cómo podría hacer para escuchar un evento de una db? Si quisiera actualizar mi web cada vez que alguien inserte un dato en mi db.

* **vamaravilla** (1) [73681](https://platzi.com/comentario/839520/) 
Hola, en el socket.html no encuentra el /socket.io/socket.io.js GET http://localho...

	* **Erik Ochoa (Platzi)** [73681] (1)

		¿seguro que tu archivo se llama **socke.io.js**? porque en la clase sólo se llama **socket.js**.

# Revisión de lo aprendido, y próximos pasos [4540]

## 0320. Revisión y próximos pasos [22639](https://platzi.com/clases/1689-backend-js/22639-revision-y-proximos-pasos/)

### Descripción:


### Links:

* [Curso Vue.js | Platzi](https://platzi.com/cursos/vuejs/)

### Comentarios:

* **Iván Felipe Velasteguí Jaramillo** (15) [736288](https://platzi.com/comentario/736288/) 

	Para iniciar el frontend del Vue.js:
	
	* Descargar la carpeta del proyecto frontend desde “Archivos y Enlaces” de esta clase
	* En consola moverse al directorio del proyecto descargado (ES UN PROYECTO APARTE, no ponerlo en el directorio del proyecto de Node que hemos venido trabajando.
	* Una vez en el directorio leer el archivo [README.md](http://README.md), aquí indica que hacer. Correrá los scripts definidos en package.json  
	npm install  
	npm run serve  
	npm run build  
	_  
	Al hacer npm run serve iniciará el frontend en http:localhost:8080/  
	_  
	Correr el servidor del chat y recargar la página del frontend y listo!  
	NOTA: asegurarse de instalar e iniciar el módulo cors en el backend del chat para que funcione
	
	

	* **Carlos Hernández** [736288] (6)

		Efectivamente. También se puede ejecutar
		``` 
		    npm run build
		    
		```
		
		Esto generará una carpeta “dist” con el código minificado y listo para producción.  
		.  
		El contenido de esa carpeta se puede mover a la carpeta “public” del backend, y así lo estaremos enviando desde el servidor Node.

	* **AlejoE02** [736288] (1)

		Gran aporte, me ayudo muchísimo, muchas gracias

	* **nancygtec** [736288] (3)

		Muchas gracias por tu aporte, no tenía idea de cómo hacerlo.
		
		Si deciden tal como sugiere el Profesor en este hilo, correr
		``` 
		    npm run build
		    
		```
		
		Y luego copiar el contenido de la carpeta “ _dist_ ” dentro de la carpeta “ _public_ ” del backend, deben cambiar el directorio definido para el contenido estático de “ _/app_ ” a “ _/_ ”.
		
		Para ello ubicar la siguiente línea en el archivo _server.js_ del backend:
		``` 
		    app.use('/app', express.static('public'));
		    
		```
		
		Y cambiarla por:
		``` 
		    app.use('/', express.static('public'));
		    
		```
		
		Esa fue la manera que encontré para que me funcionara, si hay otra quedo atenta a sugerencias.

* **danhergir** (4) [729367](https://platzi.com/comentario/729367/) 

	Hola, existe alguna documentación para entender como puedo integrar el frontend de Vue en esta clase con el proyecto de Node que llevamos por a parte

	* **Demian Arenas (Platzi)** [729367] (2)

		Hola @danhergir, el frontend de Vue corre en un proceso aparte y se comunica con el proyecto de Node a modo de API. El frontend realiza una petición mediante Axios, dentro del sistema de archivos en _/src/store/modules_ puedes ver la forma en que el proyecto realiza las peticiones.
		
		Si lo que buscas es aprender sobre la estructura del proyecto de Vue te recomiendo el [Curso Profesional de VueJS](https://platzi.com/clases/vuejs-profesional/) o partir desde el [Curso Básico de Vue.js](https://platzi.com/clases/vuejs/). Si lo que buscas es hacer Server Side Render con el proyecto que hicimos en Node, te recomiendo la [documentación de Vue](https://ssr.vuejs.org/).

	* **juanvalero252** [729367] (1)

		Igual no responde la pregunta, tambien estoy teniendo problemas para integrar el Frontend, pero como nunca nadie me responde aqui igualo lo dejo para la posteridad

* **Ariel Virgilio Solano Gonzalez** (3) [803593](https://platzi.com/comentario/803593/) 

	Algo que me hubiese gustado fuera implementar un login con twj

	* **Sebastian Cardoso Castillo** [803593] (1)

		¿Qué es twj?

	* **deveeup** [803593] (3)

		creo que se refiere a json web tokens…

	* **Luis Jeanpier Monserrate** [803593] (1)

		en el curso de react avanzado se implementa este feature, te invito a que le eches un vistazo

	* **Harkrer** [803593] (1)

		En el curso ‘Practico de Nodejs’ lo puedes ver:
		
		[](https://platzi.com/clases/practico-node/)

	* **Harkrer** [803593] (1)

		[https://platzi.com/clases/practico-node/](url)

* **reignover** (2) [799435](https://platzi.com/comentario/799435/) 

	Cuando envio un mensaje desde insomnia, no llega al instante a la app de Vue, toca recargar, why?

* **Wilson Castro Medellin** (1) [1121336](https://platzi.com/comentario/1121336/) 

	Perfecto

* **chris_x** (1) [1099105](https://platzi.com/comentario/1099105/) 

	El frontend esta perfecto para realizar las pruebas de lo que se estuvo trabajando, pero soy el unico al que no le funciona el socket para mostrar los mensajes en la vista de chat ?
	
	Desde mi cliente REST envio mensajes pero no se muestran en tiempo real

* **Abraham Flores Cosme** (1) [1073309](https://platzi.com/comentario/1073309/) 

	No comprendo el funcionamiento, se supone que debería haber un websocket cuando abro el frontend, en la versióon compilada para producción no veo ningun websocket en la red y al correr npm run serve si se muestran websockets pero son los que vue crea para recargar la pagina cuando se modifica el código, no veo los websockets funcionando en el frontend, alguién me puede explicar esto?

* **ehnbytes** (1) [975883](https://platzi.com/comentario/975883/) 

	Muy buen curso, fácil de entender!!

* **daag13** (1) [953866](https://platzi.com/comentario/953866/) 

	Muy buen curso.

	* **María José Ledesma (Platzi)** [953866] (1)

		 **¡Nunca pares de aprender!** (Y practicar) 🦄

* **beaps** (1) [731640](https://platzi.com/comentario/731640/) 

	Cuando añado _cors_ al proyecto se me queda el navegador como recargando y no funciona nada… a alguien más le pasa?

	* **Carlos Hernández** [731640] (2)

		¿Te da algún error la consola?

* **Washington Antonio Delgado Neira** (1) [72204](https://platzi.com/comentario/812316/) 
hola Carlos, Tengo mi html hecho por mi en atom, y un javascript con una logica, tambien un css para los estilos de la pagina. mi pregunt...

	* **Marco Antonio Macedo Preciado** [72204] (1)

		Lo que tienes que hacer para leer los datos desde el cliente es realizar peticiones a la api.  
		Para hacer eso en Javascript usas la función Fetch.  
		Por ejemplo si quieres consumir un endpoint de tu servidor usarías algo así:
		``` 
		    fetch("http://tuserver.com/endpoint/", {
		    method: "POST",
		    body: JSON.stringify(objetoJSON)
		    }).then(response => {
		    	//aquí manejas la respuesta del servidor
		    })
		    
		```
		
		Te recomiendo consultar más información sobre consultas a una api, asíncronismo y promesas para que cumplas con tu cometido, y qué mejor manera que hacerlo aquí, en el curso de Fundamentos de Javascript se ahonda en eso.

* **Fredy Marín** (1) [71143](https://platzi.com/comentario/790675/) 
Hola, ¿Se puede descargar de algún sitio el código del curso?

	* **Juan David Castro (Platzi)** [71143] (1)

		👋 ¡Hola!
		
		Las clases donde escribimos código tienen una sección de **Archivos y Enlaces**. Allí encuentras todo lo que necesitas. 😉
		
		![Screen Shot 2019-09-12 at 1.17.01 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-09-12%20at%201.17.01%20PM-f3e3f9b9-7748-44a0-ae26-528816204f3b.jpg)

## 0330. Tips para escalar nuestro proyecto [22981](https://platzi.com/clases/1689-backend-js/22981-tips-para-escalar-nuestro-proyecto/)

### Descripción:


**¡Felicitaciones por terminar el Curso de Node.JS!**

Hemos aprendido a utilizar Node para crear nuestro backend, un proyecto de un chat ¡hasta utilizando WebSockets! Darle seguridad a nuestro backend, manejar nuestra base de datos y mucho más.

En esta última clase te enseñaremos algunos tips que te podrán ayudar a mejorar nuestro proyecto.

Sabemos que ha sido un largo camino, pero estamos seguros de que valió la pena. Y recuerda, ¡ **nunca pares de aprender**!.

### Comentarios:

* **Alan Santiago** (13) [888770](https://platzi.com/comentario/888770/) 

	Cuando las variables de configuración que vamos a guardar son algo sensibles: contraseñas, uri para acceso a bases de datos, etc, se suele usar el paquete **dotenv**.  
	Para instalarlo basta con ejecutar:
	``` 
	    npm i dotenv
	    
	```
	
	.  
	Ahora tenemos que importar dentro del archivo de más alto nivel, en nuestro caso es `server.js`:
	``` 
	    require('dotenv').config()
	    
	```
	
	.  
	Y al nivel de `server.js` necesitamos el archivo `.env`, ahí escribimos todas las variables que deseen usar. Siempre usando la estructura NAME=VALUE
	``` 
	    DB_URI=mongodb+srv://admin:password@cluster0-leoix.mongodb.net/test?retryWrites=true&w=majority
	    HOST=http://localhost:3000
	    
	```
	
	.  
	Para usar estas variables simplemente necesitamos escribir `process.env.TU_VARIABLE`, no hay que importar en ningún otro archivo aparte del `server.js`  
	.  
	Es recomendable escribir el nombre de este archivo dentro de `.gitignore` y `.npmignore` para evitar subir esos datos a npm o github. 😎

* **Byron Mesias Cueva Cabrera** (4) [971876](https://platzi.com/comentario/971876/) 

	Esta es mi solución para response.js:
	``` 
	    const statusMessage = {
	        '200': 'Done',
	        '201': 'Created',
	        '400': 'Invalid format',
	        '500': 'Internal error'
	    };
	    
	    /**
	   * Respuestas exitosas
	     */
	    exports.success = function(req, resp, data, status = 200) {
	        const message = statusMessage[status];
	        resp.status(status).send({
	            error: '',
	            body: data || message
	        });
	    }
	    
	    /**
	   * Respuestas con error
	     */
	    exports.error = function(req, resp, data, status = 500, details) {
	        console.error(`[response error] ${details}`);
	        const message = data || statusMessage[status];
	        resp.status(status).send({
	            error: message,
	            body: ''
	        });
	    }
	    
	```

* **Kevin William Roberts Costa** (4) [832848](https://platzi.com/comentario/832848/) 

	**Reto **  
	(gracias!)
	``` 
	    const statusMessage = {
	        '200': 'Done',
	        '201': 'Created',
	        '400': 'Invalid Format',
	        '500': 'Internal Error'
	    }
	    
	    exports.success = function (req, res, message, status) {
	        let statusCode = status;
	        let statusMessage = message;
	        if(!status){
	            status = 200;
	        }
	        if(!message){
	            statusMessage = statusMessages[status];
	        }
	        res.status(statusCode).send({ 
	            error: '',
	            body: statusMessage
	        });
	    }
	    
	    exports.error = function (req, res, message, status, details) {
	        let statusCode = status;
	        let statusMessage = message;
	        if(!status){
	            status = 500;
	        }
	        if(!message){
	            statusMessage = statusMessages[status];
	        }
	        res.status(statusCode).send({ 
	            error: statusMessage,
	            body: '',
	        });
	    }```
	    
	```

* **Sebastian Cardoso Castillo** (4) [743832](https://platzi.com/comentario/743832/) 

	Si estamos usando git es muy importante agregar el archivo config al **‘.gitignore’** ya que podemos tener información sensible.

	* **Ezequiel Guerra** [743832] (5)

		Lo que debemos colocar en **.gitignore** es el archivo .env

* **Sandra Milena Rairán Pinilla** (4) [728448](https://platzi.com/comentario/728448/) 

	Hola!! Esta clase esta repetida es la Guardar el fichero en el servidor, falta la clase “Tips para escalar nuestro proyecto”.  
	Por favor la organizan. Gracias

	* **ricardocelis (Platzi)** [728448] (4)

		ya mismo, muchas gracias por avisar!

	* **ricardocelis (Platzi)** [728448] (7)

		Quedo listo, un saludo

* **Ken Ramirez** (3) [870586](https://platzi.com/comentario/870586/) 

	Excelente! En el caso de los statusCode y statusMessage creo que se ve más ordenado usando inline if:
	``` 
	    let statusCode = status ? status : 200;
	      let statusMessage = message ? message : statusMessages[status];
	    
	```

* **René Felipe Ramírez Barrera** (3) [782663](https://platzi.com/comentario/782663/) 

	Excelente el curso y muy buen profesor, gracias! .

* **chris_x** (2) [1099127](https://platzi.com/comentario/1099127/) 

	El pueblo pide mas cursos de Carlos! Genial todo el curso.

* **José María Cuevas Ramírez** (2) [1081171](https://platzi.com/comentario/1081171/) 

	Un gran curso y un gran profesor. ¡Espero siga dando más cursos en Platzi!

* **Luis Jeanpier Monserrate** (2) [902932](https://platzi.com/comentario/902932/) 

	genial curso, por fín entendí la verdadera función de un lenguaje backend, con php no me terminaba de quedar claro jajaja

* **Cesar Velásquez Córdova** (2) [775183](https://platzi.com/comentario/775183/) 

	Muchísimas gracias por todo Carlos y al equipo de Platzi por capacitarnos increíblemente bien, saludos apreciables!!

* **JaimeRamos** (2) [763120](https://platzi.com/comentario/763120/) 

	excelente curso, gracias!

* **Carlos Huarcaya** (2) [727875](https://platzi.com/comentario/727875/) 
Clase repetida!!!

	* **ricardocelis (Platzi)** [727875] (3)

		hola Carlos, corregido!

* **Byron Miguel Piedrahita Hernandez** (2) [68026](https://platzi.com/comentario/733140/) 
Buenos días. Por favor me pueden indicar en cual clase se habló sobre ¿Como recoger la cabecera Authorizacion de la petición? se me pasó...

	* **Juan David Castro (Platzi)** [68026] (3)

		1️⃣ [Información contextual: Leer las cabeceras](https://platzi.com/clases/1689-backend-js/22631-informacion-contextual-leer-las-cabeceras/)  
		2️⃣ [Curso de Autenticación con Passport.js](https://platzi.com/clases/passport/)  
		3️⃣ [Curso de Autenticación con OAuth](https://platzi.com/clases/autenticacion-oauth/)

* **Wilson Castro Medellin** (1) [1121400](https://platzi.com/comentario/1121400/) 

	Muy buena intro al mundo back. Felicitaciones!

* **Henry Palomino** (1) [1113033](https://platzi.com/comentario/1113033/) 

	Excelente curso, aprendi mucho de como empezar en el mundo del backend, hay mucho que aprender aún pero con este curso ya se tiene una visión de como manejarlo de una manera bastante ordenada, clara y profesional, el profe Carlos es increible en la explicación, y los tips son muy practicos.

* **boristrochez** (1) [1089101](https://platzi.com/comentario/1089101/) 

	Hago retrospectiva y me alegra demasiado todo lo que he aprendido en este curso. A seguir aprendiendo!

* **carlosextra1** (1) [1065363](https://platzi.com/comentario/1065363/) 

	MUCHAS MUCHAS Gracias por este curso. He abierto un amplio panorama con el mundo de NODEjs

* **Nicolas David Pastran Zamora** (1) [1063915](https://platzi.com/comentario/1063915/) 

	Muy Bueno el curso. Me encanto !

* **emanuel-alejandro-mamani** (1) [1051081](https://platzi.com/comentario/1051081/) 

	Re bueno el curso, aprendi muchisimo de node.

* **Fabio Andres Arango Grajales** (1) [846081](https://platzi.com/comentario/846081/) 

	Excelente curso Gracias carlos

* **Sebastian Castillo** (1) [819762](https://platzi.com/comentario/819762/) 

	Excelente curso para iniciar con Node, muy buen trabajo Carlos, ahora por el examen.

* **daag13** (1) [80177](https://platzi.com/comentario/953878/) 
¿Existe alguna forma de encriptar ese archivo de configuración dado que son datos sensibles?

	* **Juan David Castro (Platzi)** [80177] (2)

		Puedes cambiar **`dotenv`** por **`secure-env`** para encriptar tu archivo de config y desencriptarlo solo cuando lo lees desde el código: <https://codeburst.io/how-secure-is-your-environment-file-in-node-js-7c4d2ed0d15a>.
		
		También te recomiendo estas lecturas de buenas prácticas en seguridad para Node.js:
		
		* <https://expressjs.com/es/advanced/best-practice-security.html>
		* <https://medium.com/@nodepractices/were-under-attack-23-node-js-security-best-practices-e33c146cb87d>
		* <https://itnext.io/make-security-on-your-nodejs-api-the-priority-50da8dc71d68>
		* <https://medium.com/the-node-js-collection/making-your-node-js-work-everywhere-with-environment-variables-2da8cdf6e786>
		* <https://www.twilio.com/blog/2017/08/working-with-environment-variables-in-node-js.html>
		* <https://github.com/lirantal/awesome-nodejs-security>
		
		

