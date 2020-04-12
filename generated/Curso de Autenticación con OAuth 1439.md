[Curso de Autenticación con OAuth 1439](https://platzi.com/cursos/autenticacion-oauth)

# Bienvenida e introducción [3105]

## 0010. Introducción y bienvenida [15806](https://platzi.com/clases/1439-autenticacion-oauth/15806-introduccion-y-bienvenida8942/)

### Descripción:


Bienvenido al Curso de Autenticación con OAuth, esta vez nuestro profesor será Guillermo Rodas que tiene más de 5 años de experiencia trabajando con JavaScript, es parte del equipo de ingeniería de Auth0 y co-organizador de comunidades como MedellínCSS.

El proyecto de este curso es un blog de música usando las integraciones de Spotify y Auth0. No vamos a detenernos mucho en la configuración ni los estilos, así podremos concentrarnos en construir la autenticación y la seguridad de la aplicación. Los requisitos básicos para tomar este curso son: conocimientos básicos de Node.js, HTML y CSS.

### Links:

* [Postman | API Development Environment](https://www.getpostman.com/)

* [JSON Viewer - Chrome Web Store](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh?hl=es)

* [Careers - Auth0](https://auth0.com/careers)

* [Medellín CSS (Medellín, Colombia) | Meetup](https://www.meetup.com/medellincss)

* [GitHub - tulios/json-viewer: It is a Chrome extension for printing JSON and JSONP.](https://github.com/tulios/json-viewer)

### Comentarios:

* **felipe santiago gonzalez** (10) [445173](https://platzi.com/comentario/445173/) 
Que emoción por este curso.

* **Juan Carlos Pinzón** (6) [452579](https://platzi.com/comentario/452579/) 

	Una alternativa a Postman y que en mi opinión es increible es [Insominia](https://insomnia.rest/download/)

* **quetzallymezaleon** (5) [512529](https://platzi.com/comentario/512529/) 

	Autenticación se refiere sólo a identificarte (como iniciar sesión)  
	Autorización se refiere más a roles de usuario, que le vas a dejar hacer a un usuario, qué permisos.

* **Richard Cuela** (3) [447738](https://platzi.com/comentario/447738/) 

	thanks

* **alejo6460** (2) [973699](https://platzi.com/comentario/973699/) 

	Se hablará también sobre el uso de roles dentro de una aplicación dando acceso a diferentes funciones? Como por ejemplo un rol administrador el cual podrá eliminar x cosas

* **raulandres13** (2) [808997](https://platzi.com/comentario/808997/) 

	Hola, podrían agregar la documentación del curso en pdf ?

* **Jorge Estrada** (2) [752123](https://platzi.com/comentario/752123/) 

	hola tengo una duda este curso tiene alguna integración con IOS y Android?

	* **Briones D. Jose** [752123] (1)

		OAuth utiliza HTTP se puede integrar con lo que sea

* **Ronnie Dave Cañas Pineda** (2) [687278](https://platzi.com/comentario/687278/) 

	Hace cuento se hizo este curso?

	* **glrodasz** [687278] (1)

		Este curso se hizo en Diciembre del 2018

* **Gustavo David Guillen Gutierrez** (2) [650349](https://platzi.com/comentario/650349/) 

	Según el profesor, es necesita conocimientos en HTML, CCS y node.js

* **Randi Guarcas** (2) [527805](https://platzi.com/comentario/527805/) 


* **Rodrigo Ramirez Trujillo** (2) [509688](https://platzi.com/comentario/509688/) 

	Genial, tengo hartos deseos de aprender sobre este curso.

* **Walter Jesus Santiago Gonzalez** (2) [507757](https://platzi.com/comentario/507757/) 

	Buen día,
	
	Excelente!.

* **jesus-olivares661** (1) [1018504](https://platzi.com/comentario/1018504/) 

	hay un paquete de node que sea llama accesscontrol  
	será recomendado usarlo junto a oauth ó es suficiente con passport…?

* **ehnbytes** (1) [961216](https://platzi.com/comentario/961216/) 

	Wow, bueno vamos a aprender!!

* **Christian David Sánchez** (1) [771457](https://platzi.com/comentario/771457/) 

	Auth0 es algo nuevo para mi. Así que motivado por aprender todo lo que se pueda en este curso.

* **Jorge Padilla Zambrano** (1) [723076](https://platzi.com/comentario/723076/) 

	Curso de Autenticacion 😃 Veamos

* **Alexander Henry Obispo Buendia** (1) [720775](https://platzi.com/comentario/720775/) 

	Listo para aprender!

* **Raul Gomez** (1) [714258](https://platzi.com/comentario/714258/) 

	super comenzemos!!

* **Michael Emir Reynosa Beltrán** (1) [488985](https://platzi.com/comentario/488985/) 

	Que bueno que hayan cursos de seguridad de este tipo. 😃

## 0020. Stack de seguridad para aplicaciones modernas [15807](https://platzi.com/clases/1439-autenticacion-oauth/15807-stack-de-seguridad-para-aplicaciones-modernas/)

### Descripción:


La seguridad ““clásica”” se basa en redes conectadas a una intranet, todos los conceptos y protocolos que manejábamos se limitan a controlar la seguridad en intranets.

Todo esto cambio gracias a la revolución móvil y a las arquitectura de aplicaciones basadas en microservicios: en vez de conectarnos a servicios internos de nuestras compañías, nuestros dispositivos se conectan a internet, una red publica que deja fuera los controles de seguridad que solíamos utilizar para controlar redes privadas.

El nuevo stack de tecnologías para controlar la seguridad de nuestras aplicaciones se compone principalmente de los siguientes estándares:

* **JSON Web Tokens** _(JWT)_ : Aunque existen muchas alternativas, este estándar propone utilizar tokens cifrados con las credenciales de autenticación de los usuarios en vez de guardar estos estados con _cookies_ en los servidores. Por esto mismo los JWT son bastante compatibles con APIs RESTful.
* **OAuth 2.0** : Es un flujo de autorización _(recuerda que autenticación y autorización son conceptos relacionados pero diferentes)_ que, por ser un estándar, nos permite aprenderlo y manejar los mismos pasos para delegar permisos en diferentes aplicaciones.
* **OpenID Connect** : Es un estándar de identificación digital basado en OAuth 2.0, nos permite identificar usuarios ende una página web a través de URLs que podemos verificar con cualquier servidor que soporte el protocolo.



### Links:

* [JSON Web Tokens - jwt.io](https://jwt.io/)

* [RFC 7519 - JSON Web Token (JWT)](https://tools.ietf.org/html/rfc7519)

* [OAuth 2.0 — OAuth](https://oauth.net/2/)

* [Welcome to OpenID Connect – OpenID](https://openid.net/connect/)

### Comentarios:

* **JMM** (4) [725981](https://platzi.com/comentario/725981/) 

	Les dejo un video que me gusto donde explican y muestran la diferencia entre OAut 2.0 y OpenIDConnect
	
	[Youtube](https://www.youtube.com/watch?v=LyqeHAkxVyk)

* **Juan David Castro (Platzi)** (3) [445209](https://platzi.com/comentario/445209/) 

	 _“Una **intranet** es una red informática que utiliza la tecnología del protocolo de Internet para compartir información, sistemas operativos o servicios de computación dentro de una organización. Suele ser interna, en vez de pública como internet, por lo que solo los miembros de esa organización tienen acceso a ella.”_ 🙄
	
	* [¿Que es una Intranet?](https://www.innovaportal.com/innovaportal/v/75/1/innova.front/que-es-una-intranet)
	
	

* **Raul Gomez** (2) [714273](https://platzi.com/comentario/714273/) 

	upss OpenID Connect:  
	<https://es.wikipedia.org/wiki/OpenID_Connect>

* **c3tuxpo2018** (2) [705215](https://platzi.com/comentario/705215/) 

	Soy sincero, me ha costado entender los conceptos y me gustaría de ser posible me corrijan si me equivoco
	
	El Stack de seguridad de aplicaciones modernas, esta impulsado por la necesidad de tener control sobre la Autenticación y Autorización de los usuarios de las aplicaciones móviles conectadas por Internet basadas en la arquitectura de microservicios, proporcionando así la seguridad que antes se tenia con las Intranet
	
	El stack moderno esta compuesto por  
	JWT (JSON Web Tokens) uso de tokens cifrados Para Autenticación  
	OAuth 2.0 Para Autorización  
	OpenIDConnet Para Identificación
	
	Es correcto?

	* **glrodasz** [705215] (2)

		Si, en pocas palabras debido a la evolución que ha tenido la comunicación entre aplicaciones fue necesario crear nuevas soluciones, que fueran más estandar y fáciles de implementar.

* **anagabrielafalcon** (2) [477960](https://platzi.com/comentario/477960/) 
Genial!!!

* **neo_jagp** (2) [446558](https://platzi.com/comentario/446558/) 

	Hola! Me está costando entender la diferencia entre “OAuth 2.0” y “OpenID Connect”. En términos generales percibo lo siguiente:  
	OpenID Connect --> Para autenticación.  
	Oauth 2.0 --> Para autorización.
	
	Sin embargo, en videos posteriores se ve como se usa la api de Spotify a través de Oauth, pero me parece que implícitamente también se realiza la autenticación no?
	
	¿Podrían ayudarme con un ejemplo como diferenciar ambas tecnologías?
	
	Gracias!

	* **glrodasz** [446558] (9)

		Si, como lo explico en la clase de OpenID Connect con el ejemplo de Facebook, muchas compañias empezaron a usar OAuth 2.0 para la implementar autenticación. Sin embargo como OAuth 2.0 no esta hecho para autenticación se requieren implementaciones extras para reforzar su seguridad. El problema con esto es que cada quien lo estaba haciendo a su manera, por lo que nace OpenID Connect, que seria las reglas extras necesarias y estandar para implementar autenticación con OAuth 2.0.

	* **ingdacrecinos** [446558] (3)

		Como yo lo entiendo es de la siguiente forma:
		
		OAuth 2.0 es un estándar de autorización y autenticación, es decir, es la forma como se manejan tanto la identidad como los permisos que puedas tener.
		
		OpenID Connect: es un sistema que se basa en OAuth 2.0, es decir, que utiliza los parámetros que indica el estándar para resolver la identidad.
		
		Por ejemplo ademas de OpenID Connect, hay otros que utilizan el estándar de OAuth 2.0, como Google, Facebook, etc. Ellos utilizan el mismo estándar.

* **Eduardo Hidalgo Díaz Rugama** (2) [51977](https://platzi.com/comentario/498253/) 
¿Que significa que RESTful no deba tener estado? en el min 2:10 aprox el profesor lo menciona, pero no me queda nada claro.

	* **stephanogiovanni** [51977] (4)

		Hay ciertos estandares donde guardas de forma parcial el estado dentro de un endpoint para después continuarlo, rest no debe guardar ningún estado. (Esos estados los puedes guardar ya sea con un modulo del protocolo como soap o simplemente sesion).

* **neo_jagp** (2) [47737](https://platzi.com/comentario/446558/) 
Hola! Me está costando entender la diferencia entre “OAuth 2.0” y “OpenID Connect”. En términos generales percibo lo siguiente: OpenID Co...

	* **glrodasz** [47737] (9)

		Si, como lo explico en la clase de OpenID Connect con el ejemplo de Facebook, muchas compañias empezaron a usar OAuth 2.0 para la implementar autenticación. Sin embargo como OAuth 2.0 no esta hecho para autenticación se requieren implementaciones extras para reforzar su seguridad. El problema con esto es que cada quien lo estaba haciendo a su manera, por lo que nace OpenID Connect, que seria las reglas extras necesarias y estandar para implementar autenticación con OAuth 2.0.

* **Camilo Andrés Santana Lizcano** (1) [1005755](https://platzi.com/comentario/1005755/) 

	¡Empecemos con toda a aprender Autenticación moderna!

* **Jose Antonio Caldera** (1) [982495](https://platzi.com/comentario/982495/) 

	Excelente avanzamos !!

* **ehnbytes** (1) [961235](https://platzi.com/comentario/961235/) 

	Interesante Curso!

* **AlvaroRT** (1) [915414](https://platzi.com/comentario/915414/) 

	Tengo nulo conocimiento de lo que se requiere para el curso, pero está en la ruta de aprendizaje, ya vere como me va.

* **Christian David Sánchez** (1) [771527](https://platzi.com/comentario/771527/) 

	Los tokens de acceso se utilizan en la autenticación basada en tokens para permitir que una aplicación acceda a una API. La aplicación recibe un token de acceso después de que un usuario autentica y autoriza el acceso con éxito, luego pasa el token de acceso como una credencial cuando llama a la API de destino. El token pasado informa a la API que el portador del token ha sido autorizado para acceder a la API y realizar acciones específicas especificadas por el alcance otorgado durante la autorización.
	
	Fuente: <https://auth0.com/docs/tokens/access-tokens>

* **Pedro Jesus Hincapie Garcia** (1) [680244](https://platzi.com/comentario/680244/) 

	Excelente curso. Vamos con toda por este nuevo reto

	* **Donald Armando Torres Arteaga** [680244] (1)

		X2

* **ryanez** (1) [614338](https://platzi.com/comentario/614338/) 
0

* **Eduardo Hidalgo Díaz Rugama** (1) [498253](https://platzi.com/comentario/498253/) 

	¿Que significa que RESTful no deba tener estado? en el min 2:10 aprox el profesor lo menciona, pero no me queda nada claro.

	* **stephanogiovanni** [498253] (4)

		Hay ciertos estandares donde guardas de forma parcial el estado dentro de un endpoint para después continuarlo, rest no debe guardar ningún estado. (Esos estados los puedes guardar ya sea con un modulo del protocolo como soap o simplemente sesion).

	* **Eduardo Hidalgo Díaz Rugama** [498253] (1)

		Te refieres por ejemplo, dentro de un checkout de 3 pasos como el de amazon, que la API no conserva el estado entre los pasos de checkout, ¿eso lo hace el cliente con sessions?
		
		Ya me queda claro lo del estado entonces.

	* **glrodasz** [498253] (3)

		Hay mas informacion al respecto aqui: <https://restfulapi.net/statelessness/>

	* **Eduardo Hidalgo Díaz Rugama** [498253] (2)

		10/10, excelente enlace. Gracias guillermo (: siempre muy atento

	* **Jair Israel Avilés Eusebio** [498253] (1)

		Hola, complementando lo ya mencionado aqui se refiere a que no conserva el estado de la sesion del cliente en el servidor, esa es una de las caracteristicas de los servicios REST. No confundir con el estado de un flujo de operacion o negocio como lo es el paso de checkout de carrito de Amazon, para mayor informacion, el curso de REST te puede ayudar a aclarar todo lo refente a este tema.

* **dariovinueza** (1) [478252](https://platzi.com/comentario/478252/) 

	Entre OAuth 2.0 y Keycloak que es mas recomendable? Saludos y gracias!

	* **glrodasz** [478252] (2)

		Creo que Keycloak es una solución que va mas alla del estandar, y no podria comparse propiamente pues Keycloak es todo un aplicativo.
		
		Más info:  
		<https://developers.redhat.com/blog/2017/01/05/spring-boot-and-oauth2-with-keycloak/>  
		<https://www.keycloak.org/about.html>

## 0030. Autenticación [15808](https://platzi.com/clases/1439-autenticacion-oauth/15808-autenticacion3622/)

### Descripción:


La autenticación consiste en verificar la identidad de nuestros usuarios, es decir, debemos asegurarnos de que los usuarios existen, si pueden ingresar a nuestro sistema, si tienen los permisos adecuados, entre otras cosas, podemos utilizar mecanismos de usuario y contraseña, mensajes de texto, envío de URLs por correo electrónico, entre otras.

### Comentarios:

* **Juan David Castro (Platzi)** (15) [445211](https://platzi.com/comentario/445211/) 

	Notas de la clase:
	
	* Autenticación es verificar la identidad de un usuario, si existe y tiene los permisos necesarios para acceder a lugares especiales 🦄 🔏👨🚫👧.
	* Los usuarios deben seguir una serie de pasos para autenticarse _(obvio)_ como llenar un formulario de email y password o utilizar mecanismos _**passwordless**_ , mensajes de texto, URLs raras que llegan por correo electrónico, entre otras 🕵️📝📬㊙️.
	* No identificar a los usuarios que entran a nuestra aplicación puede ser lo mismo que dejar entrar a cualquiera a nuestra casa, o peor aún, a la casa de nuestros usuarios. Protegan sus aplicaciones, muchaches 😱😰🔥💣🔪.
	
	

* **Juan David Castro (Platzi)** (4) [468621](https://platzi.com/comentario/468621/) 

	* [Authenticate a Node ES6 API with JSON Web Tokens](https://scotch.io/tutorials/authenticate-a-node-es6-api-with-json-web-tokens)
	* [Vue.js Authentication System with Node.js Backend](https://blog.jscrambler.com/vue-js-authentication-system-with-node-js-backend)
	
	

* **c3tuxpo2018** (3) [702037](https://platzi.com/comentario/702037/) 

	Entiendo que la autenticación es la verificación por diferentes medios la identidad de un usuario, y la Autorización es la verificación de los permisos de acceso a recursos o no del usuario ya autenticado  
	Es correcto?

	* **glrodasz** [702037] (2)

		Si, correcto!

* **Christian David Sánchez** (2) [771578](https://platzi.com/comentario/771578/) 

	Fue una gran explicación usando la analogía.
	
	En resumen autenticación es la verificación la existencia, permisos e identidad de nuestros usuarios.

* **annaduarte** (2) [710225](https://platzi.com/comentario/710225/) 

	Si tienen permisos adecuados es **incorrecto** , eso forma parte de **autorización**

* **Pedro Jesus Hincapie Garcia** (2) [680318](https://platzi.com/comentario/680318/) 

	Creo y me corrigen si me equivoco, dentro de la definición de Autenticación que tiene en la descripción de la clase no debería estar este concepto:"…existen, si pueden ingresar a nuestro sistema, **si tienen los permisos adecuados** , entre otras cosas,…“  
	Eso hace parte y es del deber de la **Autorización**  
	"La autorización consiste en definir los permisos y limitaciones de los usuarios que han pasado el proceso de autenticación, …”

	* **glrodasz** [680318] (1)

		Si, gracias por resaltar el concepto.

* **ehnbytes** (1) [961239](https://platzi.com/comentario/961239/) 

	Muy buena analogía!!

* **AlvaroRT** (1) [915422](https://platzi.com/comentario/915422/) 

	Bien claro el concepto.

* **Raul Gomez** (1) [715427](https://platzi.com/comentario/715427/) 

	buen video

## 0040. Autorización [15809](https://platzi.com/clases/1439-autenticacion-oauth/15809-autorizacion/)

### Descripción:


La autorización consiste en definir los permisos y limitaciones de los usuarios que han pasado el proceso de autenticación, recuerda no confundir los términos. Este proceso de autorización sucede, por ejemplo, cuando permitimos que una aplicación se conecte a nuestra cuenta de Google, muchas veces no queremos que estas aplicaciones tengan todos los permisos de nuestra cuenta _(para enviar o leer los correos, por ejemplo)_ , pero si podemos autorizar otros permisos como la cámara o el calendario.

Esto mismo sucede con nuestras aplicaciones, por ejemplo, algunos usuarios pueden tener permisos para escribir, actualizar o eliminar cierto contenido, mientras que otros solo pueden visualizar e interactuar con estas publicaciones.

El desafío de esta clase es buscar y describir en la sección de comentarios una o más librerías que nos permitan realizar ambos procesos: autenticación y autorización.

### Comentarios:

* **Juan David Castro (Platzi)** (40) [445213](https://platzi.com/comentario/445213/) 

	 **👮 Autenticación 🆚 Autorización 🤖**
	
	El proceso de **autenticación** consiste en identificar a los usuarios, quién es, cómo se viste, es o no buena gente, etc:
	
	😬 **User:** Hey! Soy Fulano de Casi Creativo y quiero entrar a …  
	👮 **Autenticación:** ¡No me digas a dónde! Yo solo me encargo de identificarte. ¿Qué método de autenticación te gustaría utilizar? Nuestra ultima actualización nos permite identificarte con mensajes de texto 😃  
	😬 **User:** Ehh, ¿Email y password?  
	👮 **Autenticación:** Ok. 😒 ¬¬  
	😬 **User:** Email: ["fulanodecasicreativo@yahoo.com](mailto:%22fulanodecasicreativo@yahoo.com)" y password “c.ntrasena m.y s.gura123! _! ".  
	👮 **Autenticación:** Credenciales incorrectas, tu correo electrónico no esta registrado en nuestra aplicación, inténtalo de nuevo o puede regis…  
	😬 **User:** Email: ["fulanodetalpersonajeficticiodecasicreativo@yahoo.com](mailto:%22fulanodetalpersonajeficticiodecasicreativo@yahoo.com)" y password "c.ntrasena m.y s.gura123!_!”.  
	👮 **Autenticación:** Bienvenido. Por favor, guarde este token en el `localStorage` de su navegador y diríjase a Mr. Autorización que le indicará los lugares a donde tiene acceso, buen viaje 😃
	
	Por otra parte, la **autorización** consiste en definir los permisos y limitaciones de los usuarios ya identificados:
	
	😬 **User:** ¿Qué tal brother? Soy Fula…  
	🤖 **Autorización:** 🔥¡Token!🔥  
	😬 **User:** Oh claro, el token 🤔, bueno en fin, aquí tiene. Vengo para saber a dónde …  
	🤖 **Autorización:** Tiene permiso para visualizar su perfil y el de sus amigos pero no puede editar sus datos porque no ha entrado a link de verificación que le mandamos al correo HACE DOS DÍAS.  
	😬 **User:** Claro, claro. No se preocupe que apenas llegue a la casa reviso el…  
	🤖 **Autorización:** Buen viaje.  
	😬 **User:** Gracias pero, mi número de teléfono esta mal, ¿no puedo editarlo rápido y despues ya lo…  
	🤖 **Autorización:** No.  
	😬 **User:** Pero yo…  
	🤖 **Autorización:** No.  
	😬 **User:** Ok 😒.

	* **Miguel Gil Rosas** [445213] (4)

		🤣🤣🤣  
		¡Muy buena explicación!

	* **elviejomenu** [445213] (2)

		Muy buena explicación.

	* **Jhon Alexander Perez Valencia** [445213] (2)

		el dios de las explicaciones.

	* **Diego Fernández Cruz** [445213] (1)

		Excelente aporte hermano!!

	* **jhonaikerfarias** [445213] (1)

		Muy bien explicado.

* **ivanguerra10** (9) [447065](https://platzi.com/comentario/447065/) 

	Ejemplos de plataformas para realizar autenticacion y autorizacion son:
	
	* Auth0 ([Link a la documentacion](https://auth0.com/docs)): Provee una plataforma universal de autenticacion y autorizacion para aplicacion web, moviles y legacy.
	
	Tiene soporte para aplicacion nativas y moviles (Android, iOS, etc), Single Page Apps (Vue.js, React, Angular), aplicaciones web (en los lenguajes mas populares: Java, Python, Node.js, Go) y para Backend’s Web/API’s (Django, Node.js, Go, Python, etc).
	
	* Okta ([Link a la documentacion](https://developer.okta.com)): Es una plataforma para autenticacion, autorizacion y administracion de usuarios en aplicaciones/API’s web y moviles.
	
	Tiene soporte para plataformas moviles (Android, iOS y React Native), lenguajes de Frontend (Javascript, Vue.js, React, Angular) y lenguajes de Backend (Node.js, Java, .NET, Go).
	
	* Passport.js ([Link a la documentacion](http://www.passportjs.org/)): Es un middleware de Node.js para autenticacion. Esta diseñado para un proposito simple: autenticar los requests que llegan al servidor.
	
	
	

* **toguxd** (4) [664843](https://platzi.com/comentario/664843/) 

	Algunas librerias gratis:
	
	  1. Passport JS
	  2. Permit
	  3. Grant
	  4. Feathers
	  5. Firebase Authentication
	
	
	
	<https://www.ma-no.org/es/programacion/javascript/librerias-javascript-gratis-para-la-autenticacion-de-usuarios>

* **Juan S Jiménez Galindo** (4) [447230](https://platzi.com/comentario/447230/) 

	Para Java [Spring Security](https://spring.io/projects/spring-security) es la librería.

* **Jose Antonio Caldera** (3) [982517](https://platzi.com/comentario/982517/) 

	Entiendo entonces que autenticar es la acción o en este caso proceso donde se confirma que efectivamente es la persona y autorización son los permisos otorgados y limites establecidos para acciones.

* **IngAntonyF** (3) [948816](https://platzi.com/comentario/948816/) 

	Spring Security este Framework utiliza estos dos servicios de Autenticacion y Autorizacion.

* **kingofking999** (3) [554473](https://platzi.com/comentario/554473/) 

	yo soy java developer y el mas famoso para nosotros es el spring security ya que el maneja los 2 modos
	
	uno para autentificacion  
	y otro para autorización atreves de roles .

* **Rodolfo Sáenz** (3) [470012](https://platzi.com/comentario/470012/) 

	En el mundo Java existe [spring-security](https://spring.io/projects/spring-security)
	
	Hay servicios como [Firebase Authetication](https://firebase.google.com/docs/auth/) y de AWS [Amazon Cognito](https://aws.amazon.com/es/cognito/)

* **Jeisson Francois Rosas Céspedes** (3) [451211](https://platzi.com/comentario/451211/) 

	Autenticación:
	
	* <https://github.com/plataformatec/devise> (RubyOnRails)
	* <https://github.com/nov/rack-oauth2> (RubyOnRails)
	
	
	
	Autorización:
	
	* <https://github.com/CanCanCommunity/cancancan> (RubyOnRails)
	* <https://www.npmjs.com/package/vue-authorize> (VueJs)
	
	

* **edg_colon** (3) [449889](https://platzi.com/comentario/449889/) 

	OAuth 2.0 :Librería de autorización que le permite a las aplicaciones obtener acceso de una API de modo estándar y simple, para aplicaciones de escritorio, móviles y web; proporciona flujos de autorización para aplicaciones.
	
	Autenticación: Librería de autenticación => JSON Web Tokens (JWT). El formato JSON es agnóstico del lenguaje!

* **pabloxco** (3) [449442](https://platzi.com/comentario/449442/) 

	Para Ruby on Rails:
	
	Autenticación:
	
	* [Devise](https://github.com/plataformatec/devise)
	* [omniauth](https://github.com/omniauth/omniauth)
	
	
	
	Autorización:
	
	* [cancan](https://github.com/ryanb/cancan)
	* [pundit](https://github.com/varvet/pundit)
	
	

* **ennma5** (3) [447984](https://platzi.com/comentario/447984/) 

	Challenge:  
	GoogleAuthenticator: Muy útil para realizar autenticación de doble factor.  
	express-session: Es parte de express para node y permite realizar ambas funiones, autenticar y autorizar.  
	Passport framework: permite implementar más de 30 estrategias de autenticación, incluyendo OpenID y OAuth.

* **Richard Cuela** (3) [447770](https://platzi.com/comentario/447770/) 

	[JAAS ](https://docs.jboss.org/jbosssecurity/docs/6.0/security_guide/html/Introduction_to_JAAS.html)Java Authentication and Authorization Service, es una interfaz  
	que permite a las aplicaciones Java acceder a servicios de control de  
	autenticación y acceso

* **José Albarado** (2) [1048989](https://platzi.com/comentario/1048989/) 

	Spring Security maneja estos dos conceptos, Authentication y Authorization.

	* **william andres rodriguez borja** [1048989] (1)

		Y tambien tiene una implementacion de Oauth bastante interesante.

* **LeoEsp** (2) [878005](https://platzi.com/comentario/878005/) 

	Esto me recuerda mucho a “El usuario con el menor privilegio”
	
	Reto:  
	Autenticación: Firebase Authentication / Permit  
	Autorización: VueJs / Rubyonrails

* **c3tuxpo2018** (2) [816056](https://platzi.com/comentario/816056/) 

	En Linux tenemos Linux-PAM Módulos  
	de Autentificación Conectables en un sistema Linux. PAM es un juego de librerías compartidas que habilitan al administrador local del sistema para escoger el modo en que los programas autentificarán a los usuarios

* **c3tuxpo2018** (2) [705286](https://platzi.com/comentario/705286/) 

	Me llamo mucho la propuesta de esta [blog](https://ciberseguridad.blog/blockchain-para-la-autenticacion-y-verificacion-de-nuestra-identidad/), que en resumen propone el uso de Blockchain para autenticacion

	* **luismigeel** [705286] (1)

		Viendo. gracias. 😄

* **zecamin** (2) [608736](https://platzi.com/comentario/608736/) 

	javascript => <https://stalniy.github.io/casl/>  
	javascript => <https://github.com/aws-amplify/amplify-js>

* **Cristian Miño Verdezoto** (2) [572782](https://platzi.com/comentario/572782/) 

	Java -> Spring Security: Framework para java que proporciona autenticación, autorización.  
	Node -> Passportjs: Autenticacion middleware para Node

* **elviejomenu** (2) [474863](https://platzi.com/comentario/474863/) 

	ui-auth : Librería que ofrece helpers para autenticación y autorización vía securium-oauth.
	
	<https://github.com/codiumsa/ui-auth>
	
	Solo autenticacion :
	
	cloudRail :
	
	* <https://elandroidelibre.elespanol.com/2016/09/incluyendo-autenticacion-terceros-aplicacion.html>
	* <https://cloudrail.com/>
	
	

* **edgar figueroa** (2) [462774](https://platzi.com/comentario/462774/) 

	para node js esta passport js como una libreria de autenticación

* **Alexander  Silvera** (2) [50171](https://platzi.com/comentario/476747/) 
Alguien sabe que se puede usar con Django para el tema de la Autenticación y Autorización??

	* **glrodasz** [50171] (5)

		Django al ser un framework fullstack tiene su propia libreria para manejo de autenticacion: <https://docs.djangoproject.com/en/2.1/topics/auth/>
		
		Pero sin embargo, tu puedes exponer servicios en una API y usar los diferentes metodos que hablamos en este curso.
		
		Tambien hay un paquete que te ayuda a implementar OAuth 2.0 en Django: <https://django-oauth-toolkit.readthedocs.io/en/latest/>

* **Andres Roberto Coello Goyes** (1) [1047154](https://platzi.com/comentario/1047154/) 

	Passport JS y Firebase

* **Héctor Tello** (1) [1043657](https://platzi.com/comentario/1043657/) 

	Autenticación: Passport JS, Grant, Firebase authentication  
	Autorización: CanCanCan, Pundit.

* **valenm12** (1) [995878](https://platzi.com/comentario/995878/) 

	Authentication: Passport JS, Permit, Feathers authentication management, Firebase Authentication.  
	Athentication and Autorization: Auth0

* **alejo6460** (1) [973714](https://platzi.com/comentario/973714/) 

	Passport

* **ehnbytes** (1) [961257](https://platzi.com/comentario/961257/) 

	Autenticación: Passport JS, Permit, Grant

* **ehnbytes** (1) [961248](https://platzi.com/comentario/961248/) 

	Autorización: es la acción de otorgar permisos a un usuario con acceso limitado.

* **AlvaroRT** (1) [915444](https://platzi.com/comentario/915444/) 

	Autenticación: Passport JS / Permit

* **Roberto Gamboa Lopez** (1) [901935](https://platzi.com/comentario/901935/) 

	Autenticacion: Passport JS / Feathers

* **gustavoguerrajimenez** (1) [858183](https://platzi.com/comentario/858183/) 

	Autenticación: Firebase Authentication y Feathers  
	Autorización: AS/400 y VueJs

* **ANGEL EFRAIN ORDOÑEZ GONZALEZ** (1) [848995](https://platzi.com/comentario/848995/) 

	Autenticación: Passport Js y Permit  
	Autorización: VueJs y RubyOnRails

* **Jimmy Niels PAYTAN VILLAVICENCIO** (1) [829590](https://platzi.com/comentario/829590/) 

	Autenticacion : Passport Js y MSAL para Azure  
	Autorizacion: AS/400 - IBM i y ASP .NET Identity

* **Manuel David Franco Gómez** (1) [800639](https://platzi.com/comentario/800639/) 

	Autenticación: Passport JS y Permit

* **Felipe Reinoso** (1) [792808](https://platzi.com/comentario/792808/) 

	En python : REQUEST  
	En java: Spring-security

* **Christian David Sánchez** (1) [771649](https://platzi.com/comentario/771649/) 

	Autorización son los tipos de accesos que se le da a un usuario.
	
	En .net hay una “libreria” denominada [ASP.NET](http://ASP.NET) Identity

* **Luis Rodrigo Alvarez Herrera** (1) [757213](https://platzi.com/comentario/757213/) 

	Encontre este articulo para autenticacion <https://www.ma-no.org/es/programacion/javascript/librerias-javascript-gratis-para-la-autenticacion-de-usuarios>  
	y para

* **Mariano_Calafate** (1) [740745](https://platzi.com/comentario/740745/) 

	autenticacion: PASSPORT JS  
	en java Spring Security

* **Alexander Mateo** (1) [736517](https://platzi.com/comentario/736517/) 

	La autenticación es un tema muy importante, actualimente estoy desarrollando una aplicación en Flutter y he encontrado librerías y paquetes que facilitan este proceso como Dart [Auth](https://pub.dev/packages/auth) y como saben Flutter facilita mucho el tema de desarrollo en muchos sentidos.

* **Raul Gomez** (1) [719388](https://platzi.com/comentario/719388/) 

	muy buen modulo

* **acosthe** (1) [686234](https://platzi.com/comentario/686234/) 
Encontré devise para auntenticacion en ruby on rails y cancancan para autorización

* **Samuel Paredes** (1) [625935](https://platzi.com/comentario/625935/) 

	La autorización tanto como en aplicaciónes web o en otros medios es importante. Me recuerda cuando se hace pruebas de penetracion a servidores Linux donde de acuerdo a la autorizacion y permisos dados por el administrador podemos hacer escalacion de privilegios!

* **Alexander  Silvera** (1) [476747](https://platzi.com/comentario/476747/) 

	Alguien sabe que se puede usar con Django para el tema de la Autenticación y Autorización??

	* **glrodasz** [476747] (5)

		Django al ser un framework fullstack tiene su propia libreria para manejo de autenticacion: <https://docs.djangoproject.com/en/2.1/topics/auth/>
		
		Pero sin embargo, tu puedes exponer servicios en una API y usar los diferentes metodos que hablamos en este curso.
		
		Tambien hay un paquete que te ayuda a implementar OAuth 2.0 en Django: <https://django-oauth-toolkit.readthedocs.io/en/latest/>

* **Fabian Siatama** (1) [451400](https://platzi.com/comentario/451400/) 

	Firebase Authentication: ([](https://firebase.google.com/docs/auth/))
	
	Auth0: Muy costoso!

	* **glrodasz** [451400] (4)

		Eso depende donde lo mires, cuando Firebase empieza a requerir una gran cantidad de usuarios se puede volver aun mas costoso que Auth0. Recuerda que con el plan free de Auth0 tienes hasta 7000 usuarios activos.

# JSON Web Tokens [3107]

## 0050. JSON Web Tokens [15810](https://platzi.com/clases/1439-autenticacion-oauth/15810-json-web-tokens5758/)

### Descripción:


Los JSON Web Tokens _(JWT)_ son un estándar que nos permite representar los permisos o requerimientos entre dos partes, es decir, el servidor de nuestra aplicación concede los permisos para un usuario generando un token, este token se envía al cliente o navegador donde utilizamos el token para realizar peticiones al servidor sin que éste necesite verificar a los usuarios, simplemente recibe los JWT y devuelve la información a la que el usuario tiene permiso según cada token.

Los JWT se dividen en 3 cadenas de texto separadas por puntos. La primera parte es el **header** y contiene el algoritmo y el tipo de token que utilizamos para firmar. La segunda parte es el **payload** , contiene información como la identificación del usuario, fechas de creación y expiración del token, entre otras ( debemos tener cuidado de no transmitir información sensible ya que, puede ser decodificada por alguna otra aplicación). Por último, la **signature** es la tercera parte del token y se genera codificando los anteriores campos más una firma secreta, gracias a esta parte del token podemos verificar su autenticidad e invalidar el token si alguno de los campos cambia.

Podemos utilizar dos tipos de algoritmos para codificar nuestros tokens, los **simétricos** nos permiten encriptar y desencriptar los tokens utilizando una única llave privada, o podemos utilizar algoritmos **asimétricos** que utilizan una llave privada y una publica para tener mayor seguridad y evitar problemas si alguna de las llaves es interceptada.

### Links:

* [JSON Web Tokens - jwt.io](https://jwt.io/)

* [RFC 7519 - JSON Web Token (JWT)](https://tools.ietf.org/html/rfc7519#section-4.1)

* [JSON Web Token (JWT)](https://www.iana.org/assignments/jwt/jwt.xhtml)

* [KeyGen.io - Random Key Generator](https://keygen.io)

### Comentarios:

* **neo_jagp** (7) [445408](https://platzi.com/comentario/445408/) 

	¿Cuál es la diferencia entre los términos “codificación”, “encriptación” y “hash”?

	* **glrodasz** [445408] (18)

		El proceso de codificar es un proceso reversible, es decir un string codificado puede ser decodificado sabiendo el algoritmo que se uso.
		
		El proceso de hashing no es reversible pero un string siempre va a generar el mismo hash (Se usa en las contraseñas).
		
		La encriptación tampoco es un proceso reversible y a diferencia del hash, requiere que uses una llave o secret.
		
		La encriptacion puede ser simetrica o asimetrica, es decir puede usar una sola llave o un par de llaves. (Publica y privada).

* **Cristian David Franco Garcia** (6) [464487](https://platzi.com/comentario/464487/) 
	
	![](https://auth0.com/learn/wp-content/uploads/2016/01/17.png)

* **Juan David Castro (Platzi)** (5) [465229](https://platzi.com/comentario/465229/) 

	* [Learn how to use JSON Web Tokens (JWT) for much Authentication win!](https://github.com/dwyl/learn-json-web-tokens)
	
	![](https://camo.githubusercontent.com/8a470031ff0b8df360e9501623e06c25a692b851/687474703a2f2f692e696d6775722e636f6d2f634e456c566f662e6a7067)

* **Mario Eduardo Contreras Serrano** (3) [935924](https://platzi.com/comentario/935924/) 

	Cuando @glrodasz explica los JWT entre dos partes (0:13 - 0:49), se refiere al cliente y al servidor.
	
	La parte que genera el JWT, es el servidor, concediéndole varios permisos (peticiones).
	
	La segunda parte se trata del cliente, que utiliza el JWT generado por el server para que el cliente pueda hacerle peticiones al server.

* **c3tuxpo2018** (3) [816127](https://platzi.com/comentario/816127/) 

	Resumen  
	Estructura JWT
	
	* header: Contiene algoritmo y tipo de token
	* payload: Contiene información
	* signature: Es una firma encriptada generalmente en sha-256
	
	
	
	Header y payload vienen codificados en base64
	
	Algoritmos simétricos usan una unica llave  
	Algoritmos asimétricos usan dos llaves una publica y otra privada

* **Juan David Castro (Platzi)** (3) [445246](https://platzi.com/comentario/445246/) 

	* [Introducción a los JSON Web Tokens - Platzi Blog por **@sergiodxa**](https://platzi.com/blog/introduccion-json-web-tokens/)
	* [Qué es la autenticación basada en token - Curso de NodeJS y MongoDB - **Carlos Azaustre**](https://www.youtube.com/watch?v=zut4jK6C6WQ)
	
	

* **David Vargas Domínguez** (2) [981749](https://platzi.com/comentario/981749/) 

	Dejo por acá un interesante artículo sobre los JWT!
	
	[Pros-and-cons-of-jwts](https://fusionauth.io/learn/expert-advice/tokens/pros-and-cons-of-jwts)

* **neo_jagp** (2) [445409](https://platzi.com/comentario/445409/) 

	¿Existen escenarios donde tenga sentido encriptar un token?

	* **glrodasz** [445409] (4)

		Realmente no es necesario, pues asi como los JWT pueden ser decodificados, tambien puedes generar tokens opacos que no portan ninguna información en si. Recuerda que todo se basa en la verificación de su firma que esta si maneja un algoritmo de encriptación para su generación.

* **neo_jagp** (2) [47628](https://platzi.com/comentario/445409/) 
¿Existen escenarios donde tenga sentido encriptar un token?

	* **glrodasz** [47628] (4)

		Realmente no es necesario, pues asi como los JWT pueden ser decodificados, tambien puedes generar tokens opacos que no portan ninguna información en si. Recuerda que todo se basa en la verificación de su firma que esta si maneja un algoritmo de encriptación para su generación.

* **neo_jagp** (2) [47627](https://platzi.com/comentario/445408/) 
¿Cuál es la diferencia entre los términos “codificación”, “encriptación” y “hash”?

	* **glrodasz** [47627] (18)

		El proceso de codificar es un proceso reversible, es decir un string codificado puede ser decodificado sabiendo el algoritmo que se uso.
		
		El proceso de hashing no es reversible pero un string siempre va a generar el mismo hash (Se usa en las contraseñas).
		
		La encriptación tampoco es un proceso reversible y a diferencia del hash, requiere que uses una llave o secret.
		
		La encriptacion puede ser simetrica o asimetrica, es decir puede usar una sola llave o un par de llaves. (Publica y privada).

* **Kevin William Roberts Costa** (1) [856748](https://platzi.com/comentario/856748/) 

	Codificación/Decodificación: Es un proceso reversible. (ie: base64)

* **Christian David Sánchez** (1) [771538](https://platzi.com/comentario/771538/) 

	Los tokens de acceso se utilizan en la autenticación basada en tokens para permitir que una aplicación acceda a una API. La aplicación recibe un token de acceso después de que un usuario autentica y autoriza el acceso con éxito, luego pasa el token de acceso como una credencial cuando llama a la API de destino. El token pasado informa a la API que el portador del token ha sido autorizado para acceder a la API y realizar acciones específicas especificadas por el alcance otorgado durante la autorización.
	
	Fuente: <https://auth0.com/docs/tokens/access-tokens>

* **Raul Gomez** (1) [719404](https://platzi.com/comentario/719404/) 

	a estudiar Json Web Tokens

## 0060. Autenticación tradicional vs JWT [15811](https://platzi.com/clases/1439-autenticacion-oauth/15811-autenticacion-tradicional-vs-jwt/)

### Descripción:


La autenticación tradicional funciona creando un espacio en memoria con un id para identificar a los usuarios activos, estos IDs se almacenan en cookies _(información que enviamos o modificamos entre servidores y navegadores)_ para identificar si los usuarios están o no autenticados. Todas las cookies tienen un tiempo límite, es decir, después de cierto tiempo la cookie se borra y la sesión termina, el usuario debe volver a autenticarse.

El problema de este tipo de autenticación es que no funciona con _Single Page Applications (aplicaciones construidas sobre una única página), ya que no refrescamos el navegador para acceder a nueva información o verificar la autenticación de los usuarios, no hay forma de acceder a las cookies a medida que los usuarios interactúan con la aplicación. También tenemos problemas cuando construimos aplicaciones con arquitecturas basadas en microservicios, cualquier control de permisos requiere volver a realizar peticiones en la base de datos.

La autenticación con tokens funciona generando tokens con la identificación y los permisos de cada usuario, estos tokens son enviados y almacenados desde el cliente, así que, siempre que nuestras aplicaciones necesitan verificar los permisos de los usuarios simplemente necesitan validar los tokens. Gracias a este tipo de autenticación NO necesitamos un servicio de backend para almacenar las sesiones de autenticación de los usuarios, solo con guardar y validar los tokens podemos controlar los permisos para cada usuario.

### Comentarios:

* **Juan David Castro (Platzi)** (12) [445251](https://platzi.com/comentario/445251/) 

	Más adelante, en la clase [Firmando un JWT](https://platzi.com/clases/1439-autenticacion-oauth/15812-firmando-un-jwt/), vamos a ver mucho mejor (con un ejemplo práctico) cómo crear un JWT y cómo funciona su validación 👌.
	
	Resumiendo un poco, toda la información que viaja en el token (lo que va adentro del header y del payload) es completamente visible para cualquier persona que acceda al token 😳😱 (podemos probar copiando y pegando uno en el debugger de <https://jwt.io> 😮). Cualquier usuario, bueno o malo, mortal o máquina, puede ver y “robar” la información delicada que se encuentre por ahí. El chiste de los tokens es que el servidor NO les permite realizar ninguna acción si cambian el contenido del token, es decir, aunque podemos “robar” la información del token, no podemos ejecutar ninguna acción del servidor a menos que tengamos las llaves secretas 😌.
	
	Aún más resumido lo entienden en esta parte de la clase de más adelante (los últimos minutos): <https://platzi.com/clases/1439-autenticacion-oauth/15812-firmando-un-jwt/?time=851>.

* **Juan David Castro (Platzi)** (11) [445248](https://platzi.com/comentario/445248/) 

	 **IMPORTANTE** : Las cookies no se llaman como se llaman por las galletas esas adictivas de navidad con chispas de chocolate y sabores deliciosos. NO. Su nombre viene de las galletas de la fortuna que tienen un mensaje adentro intentando adivinar tu futuro, algo más parecido a la funcionalidad de las cookies en la comunicación de servidores y navegadores. **#Epic**. ✌️

* **edg_colon** (5) [449894](https://platzi.com/comentario/449894/) 

	Que interesante el origen del nombre de la cookie! jeje

	* **_Adrian_** [449894] (3)

		Cierto y tiene mucha razon … buen dato !!!

* **juand_silva** (3) [676064](https://platzi.com/comentario/676064/) 

	Por eso anteriormente era mucho más fácil autenticarse como otra persona en servicios de mensajería como **messenger** en su época. xD

* **Jordi Santamaría Portolés** (3) [530349](https://platzi.com/comentario/530349/) 

	Lo que no pillo es, con tu token tienes que hacer una peticion al servidor para que te verifique si es valido igual no? entonces el proceso no es el mismo k con la cookie? lo unico que cambia es que no tienes un campo en la bd con la sesion, xk simplemente lo sacas con el secret y el token, pero la peticion a backend la haces igual.  
	Ademas las SPA tienen estado, via redux u otros, asi que cuando el servidor resolviera, si no hay permisos puede actualizar el contenido en cualquier momento.

* **KimoSolutions** (3) [58638](https://platzi.com/comentario/579676/) 
Entonces si quiero terminar con la sesión como funciona??

	* **davidtoca (Platzi)** [58638] (3)

		No puedes con JWT, lo que puedes hacer es poner una fecha de expiracion del token

* **AlvaroRT** (1) [925223](https://platzi.com/comentario/925223/) 

	Excelente comparativa. Muy claro en concepto.

* **jcalderon.sys** (1) [773879](https://platzi.com/comentario/773879/) 

	Muy buena explicación

* **Raul Gomez** (1) [719415](https://platzi.com/comentario/719415/) 

	buena ilusracion entre json y token tradicional

* **KimoSolutions** (1) [579676](https://platzi.com/comentario/579676/) 

	Entonces si quiero terminar con la sesión como funciona??

	* **davidtoca (Platzi)** [579676] (3)

		No puedes con JWT, lo que puedes hacer es poner una fecha de expiracion del token

	* **glrodasz** [579676] (3)

		Exacto, sesiones y JWT son temas tecnicas muy diferentes.

	* **william andres rodriguez borja** [579676] (3)

		las sesiones son del mundo de autenticacion con estados ejemplo estado sesion iniciada, estado sesion terminada. OAuth y jwt no tienen estado por ende no hay ninguna sesion para cerrar.  
		un usuario no autenticado es usuario sin token o sin token valido en las aplicaciones SPA como angular o react se guarda el token en el navegador y cuando se realiza el logOut se borra el token y se redirecciona a la home

	* **romerodiesan** [579676] (1)

		Entonces como el usuario podría hacer logout de un sistema por su propia voluntad?

	* **José Albarado** [579676] (1)

		@romerodiesan cuando se requiere hacer un logout, lo que se hace es “matar” el token, de lo contrario el token morirá cuando termine su tiempo de vida (expirationTime), es como se comentó en el vídeo, estos JWT son stateless, simplemente existen o no.

* **romerodiesan** (1) [82959](https://platzi.com/comentario/1016327/) 
¿Entonces cómo un usuario podría hacer logout de un x sistema (que usa JWT) por propia voluntad? Si no existen las sesio...

	* **glrodasz** [82959] (1)

		Una estrategia es remover el token del amacenamiento del cliente, luego hay tecnicas mas complejas como hacer un blacklist de los tokens que no queremos permitir.

## 0070. Configuración inicial de los proyectos [15813](https://platzi.com/clases/1439-autenticacion-oauth/15813-configuracion-inicial-de-los-proyectos/)

### Descripción:


### Comentarios:

* **Diego Andres Cardenas Caro** (14) [678394](https://platzi.com/comentario/678394/) 

	Quedo un poco en el aire como arrancar el proyecto, así me funciono a mi:
	
	1 - Clone del repo: <https://github.com/glrodasz/platzi-autenticacion>  
	En el repo estan los dos directorios admin y blog. Para cada directorio cambiar al branch de la clase:  
	2 - gitcheckout configuracion-inicial-de-los-proyectos  
	3 - En el directorio blog: npm install nodemon@latest -D luego npm install  
	4 - En el directorio blog: npm start  
	5 - En el directorio admin: npm install  
	6 - En el directorio admin: npm run dev

	* **Walter Lensinas** [678394] (1)

		Cabe aclarar que esta bueno tener nodemon como global, para usarlo en otros proyectos. Ejecutando:
		``` 
		    npm install -g nodemon
		    
		```
		
		Gracias Diego!

	* **Manuel David Franco Gómez** [678394] (1)

		Excelente aporte, Gracias

* **Cristian David Franco Garcia** (8) [464577](https://platzi.com/comentario/464577/) 

	Para el proyecto de blog es necesario actualizar nodemon(npm install --save-dev nodemon ) y posteriormente ejecutar npm install

	* **Norman Roa** [464577] (1)

		Gracias!

* **ahernandezb** (5) [860673](https://platzi.com/comentario/860673/) 

	todo esta muy bien el profe sabe mucho del tema pero lo que no sabe que es esto es nuevo para mas de uno de nosotros entonces debería ser mas flexible con la explicación.

* **Raul Gomez** (4) [719508](https://platzi.com/comentario/719508/) 

	upss este modulo requiere de esfuerzo adicional

* **Camilo Andrés Santana Lizcano** (3) [1006341](https://platzi.com/comentario/1006341/) 

	Si corriste **npm install** en blog y todo se puso rojo, respira hondo e intenta esto.
	``` 
	    npm install nodemon@latest -D
	    
	```
	
	También en **admin** deberás correr
	``` 
	    npm audit fix
	    
	```
	
	Para evitar que un hacker ruso arruine tu proyecto.
	
	Ahora si andamos readys para continuar 😄

* **AlvaroRT** (3) [925352](https://platzi.com/comentario/925352/) 

	Creo que mi ruta de aprendizaje no incluye nada de programación, por lo que en este clase en particular, me quede en 0.

* **Ezequiel Freire** (3) [450848](https://platzi.com/comentario/450848/) 

	Hola como estan? estoy teniendo problemas con el proyecto de admin luego de instalar las dependencias.  
	Compilo la app sin problema al utilizar el comando npm run dev pero cuando voy a la localhost:3001 tengo el siguiente error.
	
	![](![Captura de pantalla 2018-12-17 a la\(s\) 20.00.58.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-12-17%20a%20la%28s%29%2020.00.58-4d4cb041-c9a9-40e4-91d3-6c70c0ef39be.jpg)

	* **glrodasz** [450848] (3)

		Estas usando el proyecto desde este repo? <https://github.com/glrodasz/platzi-autenticacion>, podrias subir tu repositorio a GitHub y publicarlo para verificar cual es el posible error.

	* **Ezequiel Freire** [450848] (1)

		Hola Guillermo, estoy utilizando el mismo proyecto. Por las dudas volví a clonarlo pero me sigue pasando lo mismo con admin. No se si tendra algo que ver, pero cuando instale las dependencias del blog una no la instalo porque está deprecada. Pero cuando la instale con npm install event-stream inicio sin problema el proyecto de blog no así el de admin.
		
		Este es el git  
		[](https://github.com/ezequielfreire007/auth-project)
		
		Tengo instalado la version de node v11.0.0 y npm 6.5.0
		
		Gracias por la rápida respuesta  
		Saludos

	* **Ezequiel Freire** [450848] (1)

		agrego el link que no se agrego en el anterior
		
		<https://github.com/ezequielfreire007/auth-project>

	* **Jorge Andrés López Cossío** [450848] (3)

		No está configurado el archivo .env, solamente se tiene el archivo .env.example, es por eso que al momento de ejecutarse el constructor no es capaz de leer los valores de configuración

	* **glrodasz** [450848] (3)

		@flecher puedes revisar lo que reporta @alopezcossio, que te hace falta configurar tu archivo `.env`.

	* **Ezequiel Freire** [450848] (2)

		Muchas gracias @glrodasz y @alopezcossio. Claro por eso no auténtica.  
		Saludos

	* **Jose David Ocaña Ballester** [450848] (2)

		Descarga el proyecto con git clone …  
		Instalas los paquetes con npm install.  
		Accedemos a la rama con el comando: git checkout configuracion-inicial-de-los-proyectos  
		Correr el proyecto.

	* **Oscar Estuardo de la Mora** [450848] (1)

		Si, del repositorio esta el archivo .env.example, solo hay que renombrarlo y dejarlo con el nombre .env

	* **luis-nobrega** [450848] (1)

		estoy teniendo el mismo error. donde consigo el archivo.env.example del repositorio?

* **edg_colon** (3) [449910](https://platzi.com/comentario/449910/) 

	Es importante ejecutar el comando `npm install` dentro del directorio de su proyecto, para instalar todas las dependencias.

* **Samuel Paredes** (3) [61755](https://platzi.com/comentario/627165/) 
Hola compañeros, estoy obteniendo este error. npm ERR! path /Users/paredesug/Desktop/auth/package.json npm ERR! code ENOENT npm ERR...

	* **osmandi (Platzi)** [61755] (1)

		Ese error se debe a que _npm_ no encuentra el archivo _package.json_. Sería de mucha utilidad contar con el código y el resto del output de la terminal para tener más detalles. Es posible que haya que realizar algunos ajustes en tu código 😃

* **Ezequiel Freire** (3) [48092](https://platzi.com/comentario/450848/) 
Hola como estan? estoy teniendo problemas con el proyecto de admin luego de instalar las dependencias. Compilo la app sin problema al uti...

	* **glrodasz** [48092] (3)

		Estas usando el proyecto desde este repo? <https://github.com/glrodasz/platzi-autenticacion>, podrias subir tu repositorio a GitHub y publicarlo para verificar cual es el posible error.

* **Rodolfo Sáenz** (2) [470425](https://platzi.com/comentario/470425/) 

	Hice un git clone del repositorio. Me situé en el branch correspondiente a esta clase.  
	Para el admin: todo bien.  
	Para el blog: El npm install me arroja lo siguiente y por lo tanto el npm run dev falla.
	``` 
	    platzi-autenticacion\blog> npm install
	    
	    > fsevents@1.2.4 install platzi-autenticacion\blog\node_modules\fsevents
	    > node install
	    
	    
	    > nodemon@1.18.6 postinstall platzi-autenticacion\blog\node_modules\nodemon
	    > node bin/postinstall || exit 0
	    
	    npm WARN blog@1.0.0 No description
	    npm WARN blog@1.0.0 No repository field.
	    npm WARN optional SKIPPING OPTIONAL DEPENDENCY: flatmap-stream@0.1.1 (node_modules\flatmap-stream):
	    npm WARN 404 SKIPPING OPTIONAL DEPENDENCY: Not Found: flatmap-stream@https://registry.npmjs.org/flatmap-stream/-/flatmap-stream-0.1.1.tgz
	    npm WARN optional SKIPPING OPTIONAL DEPENDENCY: event-stream@3.3.6 (node_modules\event-stream):
	    npm WARN 404 SKIPPING OPTIONAL DEPENDENCY: Not Found: event-stream@https://registry.npmjs.org/event-stream/-/event-stream-3.3.6.tgz
	    
	    added 406 packages in51.172s
	    
	```
	``` 
	    platzi-autenticacion\blog>npm run dev
	    
	    > blog@1.0.0 dev ~\Desktop\PlatziWorkSpace\AutenticacionConOAuth\platzi-autenticacion\blog
	    > nodemon index
	    
	    module.js:487
	        throw err;
	        ^
	    
	    Error: Cannot find module'event-stream'
	        at Function.Module._resolveFilename (module.js:485:15)
	        at Function.Module._load (module.js:437:25)
	        at Module.require (module.js:513:17)
	        at require (internal/module.js:11:18)
	        at Object.<anonymous> (~\Desktop\PlatziWorkSpace\AutenticacionConOAuth\platzi-autenticacion\blog\node_modules\ps-tree\index.js:4:13)
	        at Module._compile (module.js:569:30)
	        at Object.Module._extensions..js (module.js:580:10)
	        at Module.load (module.js:503:32)
	        at tryModuleLoad (module.js:466:12)
	        at Function.Module._load (module.js:458:3)
	    npm ERR! code ELIFECYCLE
	    npm ERR! errno 1
	    npm ERR! blog@1.0.0 dev: `nodemon index`
	    npm ERR! Exit status 1
	    npm ERR!
	    npm ERR! Failed at the blog@1.0.0 dev script.
	    npm ERR! This is probably not a problem withnpm. There is likely additional logging output above.
	    
	    npm ERR! A complete log ofthis run can be found in:
	    npm ERR!    ~\AppData\Roaming\npm-cache\_logs\2019-01-07T22_30_22_618Z-debug.log```
	    
	```

	* **glrodasz** [470425] (2)

		Que version de Node y NPM estas usando?

	* **metta** [470425] (5)

		Creo que esto tiene que ver con los ataques que sufrio la libreria de events de node hace tiempo, para mi en el caso de /blog la solucion que encontre fue correr
		
		npm install nodemon@latest -D
		
		que actualiza nodemon a version sin esos defectos, otra cosa que puedes hacer es:
		
		npm audit y npm audit fix para ver si npm puede solucionar estos problemas de dependencias.

	* **ITontwice** [470425] (4)

		A mi también me estaba dando problemas **blog** pero usando _npm install nodemon@latest -D_ me funciono correctamente.  
		Gracias @J4warr por el aporte

	* **Samuel Paredes** [470425] (2)

		Gracias a todos aqui 😃

	* **toguxd** [470425] (1)

		Gracias a todos! Pude solucionar este error que también me aparecía!

	* **Alexander Mateo** [470425] (1)

		Muchas gracias a todos 😄

	* **Jair Israel Avilés Eusebio** [470425] (1)

		A mi me aparecio ese mismo error, mi solucion fue eliminar el archivo `package-lock.json` y volver a instalar todas las dependencias con `npm install`.

* **Rodolfo Sáenz** (2) [49667](https://platzi.com/comentario/470425/) 
Hice un git clone del repositorio. Me situé en el branch correspondiente a esta clase. Para el admin: todo bien. Para el blog: El npm ins...

	* **glrodasz** [49667] (2)

		Que version de Node y NPM estas usando?

* **Cristian David Franco Garcia** (2) [49239](https://platzi.com/comentario/464560/) 
Buenas noches, ¿Que es implicit?

	* **glrodasz** [49239] (1)

		Un de los flujos de OAuth 2.0. En la clase de Implicit Grant lo explico por completo. Pero de manera muy resumida es el flujo que se ultiliza para aplicaciones del lado del cliente.

* **Andres Roberto Coello Goyes** (1) [1048507](https://platzi.com/comentario/1048507/) 

	 **<https://react.semantic-ui.com/>**

* **Héctor Tello** (1) [1046059](https://platzi.com/comentario/1046059/) 

	Si al ejecutar en admin:
	``` 
	    npm run dev
	    
	```
	
	les aparece el siguiente error:
	``` 
	    > admin@1.0.0 dev /home/hectortllo/Documentos/Platzi/Autenticacion/platzi-autenticacion/admin
	    > next -p 3001
	    
	    sh: 1: next: not found
	    npm ERR! code ELIFECYCLE
	    npm ERR! syscall spawn
	    npm ERR! file sh
	    npm ERR! errno ENOENT
	    npm ERR! admin@1.0.0 dev: `next -p 3001`
	    npm ERR! spawn ENOENT
	    npm ERR! 
	    npm ERR! Failed at the admin@1.0.0 dev script.
	    npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
	    npm WARN Local package.json exists, but node_modules missing, did you mean to install?
	    
	    
	```
	
	para arreglarlo, ejecuté lo siguiente:
	``` 
	    sudo npm installfirst
	    
	```
	
	Después de eso todo funcionó bien.

* **Jose Antonio Caldera** (1) [984478](https://platzi.com/comentario/984478/) 

	Estoy en el aire no se como comenzar el proyecto , que herramienta utilizar o como avanzar

	* **victorcc** [984478] (1)

		Ya pudiste avanzar ? o aún estas en el aire?

* **Samuel Paredes** (1) [627160](https://platzi.com/comentario/627160/) 

	Hola compañeros, estoy obteniendo este error.
	``` 
	    npm ERR! path /Users/paredesug/Desktop/auth/package.json
	    npm ERR! code ENOENT
	    npm ERR! errno -2
	    npm ERR! syscall open
	    npm ERR! enoent ENOENT: no such file or directory, open '/Users/paredesug/Desktop/auth/package.json'
	    npm ERR! enoent This is related tonpmnot being able to find a file.
	    npm ERR! enoent 
	    
	    npm ERR! A complete log ofthis run can be found in:
	    npm ERR!     /Users/paredesug/.npm/_logs/2019-06-25T18_58_16_650Z-debug.log```
	```

	* **Samuel Paredes** [627160] (2)

		Todo reparado!! He encontrado la solución en este [sitio web](https://stackoverflow.com/questions/50355263/local-package-json-exists-but-node-modules-missing#50355345), miren si la necesitan. Si no, en tal caso aquí están los comandos.  
		Recuerden que deben que estar en la carpeta admin.
		``` 
		    npm start
		    npm install
		    npm start
		    
		```

* **zecamin** (1) [608796](https://platzi.com/comentario/608796/) 

	Hola glrodasz tengo un pregunta, desde tu punto de vista que me puedes recomendar cuando tengo un proyecto que los permisos son ad ministrables. Quedo atento.

* **Melina Jacqueline onoriaga** (1) [519016](https://platzi.com/comentario/519016/) 

	Estos pasos también sirven para aplicarlos en un proyecto con react native?

* **Cristian David Franco Garcia** (1) [464560](https://platzi.com/comentario/464560/) 

	Buenas noches,  
	¿Que es implicit?

	* **glrodasz** [464560] (1)

		Un de los flujos de OAuth 2.0. En la clase de Implicit Grant lo explico por completo. Pero de manera muy resumida es el flujo que se ultiliza para aplicaciones del lado del cliente.

* **San Gallardo** (1) [446821](https://platzi.com/comentario/446821/) 

	que pasa cuando se cae el API??

	* **glrodasz** [446821] (2)

		Pueden pasar dos escenarios:
		
		  1. Los llamados se quedan esperando a que respondan generando un erro de timeout (Se agota el tiempo de espera.)
		  2. Simplemente van a devolver una respuesta de error. (Puede ser un error 404 not found).
		
		
		
		Generalmente en estos casos uno debe pensar e implementar alternativas. Ningun servicio está exento de caerse.

* **felipe santiago gonzalez** (1) [445854](https://platzi.com/comentario/445854/) 
Que debemos instalar en Linux, para poder ejecutar los proyectos?

	* **glrodasz** [445854] (1)

		Debes tener instalado Node.js y Git para clonar el proyecto del repositorio e instalar las dependencias. Recomiendo la ultima version estable (LTS) y a partir de ahi, solo es correr `npm install` en cada uno de los proyectos.

* **Luis Arellano** (1) [445465](https://platzi.com/comentario/445465/) 

	un favor podrían zipear todo el proyecto? para no estar bajando 1 x 1

	* **glrodasz** [445465] (7)

		El proyecto se encuentra en este repositorio y cada clase tiene su propia rama: <https://github.com/glrodasz/platzi-autenticacion>

	* **Luis Arellano** [445465] (1)

		gracias

* **IngAntonyF** (1) [80128](https://platzi.com/comentario/953079/) 
no me levanta el proyecto. PS C:\Users\Antony1\Documents\GitHub\platzi-autenticacion> npm run dev El término ‘npm’ no se reconoce como...

	* **Luis Alexander Chip** [80128] (1)

		El `cmd` de windows no reconoce el comando `npm`, tienes que agregar el path de node a las variables de entorno.

## 0080. Firmando un JWT [15812](https://platzi.com/clases/1439-autenticacion-oauth/15812-firmando-un-jwt/)

### Descripción:


Para generar y firmar un JWT de manera simétrica vamos a instalar las siguientes dependencias:
``` 
    npm i -S express dotenv jsonwebtoken body-parser
    
```

La librería `dotenv` nos permite crear archivos `.env` con la información que no podemos publicar de nuestro proyecto, por ejemplo, la llave secreta de nuestro JWT. Por otra parte, la librería `jsonwebtoken` nos permite firmar nuestros tokens de manera simétrica.

Con nuestras dependencias instaladas y los archivos `.env` configurados, podemos programar nuestra aplicación, en esta clase vamos a crear un endpoint `/api/auth/token` donde debemos generar un token de usuario utilizando el método `jwt.sign()`.

### Links:

* [JSON Web Tokens - jwt.io](https://jwt.io)

### Comentarios:

* **jldamians** (6) [934075](https://platzi.com/comentario/934075/) 

	Sólo una acotación.
	
	Las versiones recientes de express, incorporan un middleware llamado “json”, por lo cual no sería necesario instalar al proyecto la dependencia “body-parser”. Lo pueden utilizar de la siguiente forma:
	
	const express = require(“express”);
	
	const app = express();
	
	app.use(express.json());
	
	Saludos!

	* **Kevin Nick Pascual Tuesta** [934075] (1)

		Gracias por la info ahora a desaser espacio en mis proyectos.

* **José de Jesús Aguirre Osuna** (3) [445259](https://platzi.com/comentario/445259/) 

	Hay manera de generar un refresh token en un JWT ?

	* **dev.team** [445259] (3)

		según el libro de JWT que esta en la pagina [jwt.io](http://jwt.io), no es necesario que tu refresh token sea un JWT, bastaría uuid

	* **dev.team** [445259] (3)

		JWTs may also be used for refresh tokens. There is less reason to use them for this purpose, though. As refresh tokens require access to the authorization server, most of the time a simple UUID will suffice, as there is no need for the token to carry a payload (it may be signed, though).  
		**esta al inicio de la pagina 20**

	* **José de Jesús Aguirre Osuna** [445259] (3)

		Tiene sentido lo que dices, yo estaba pensando en sí, JWT seguía un método parecido al de Oauth [refresh token](https://oauth.net/2/grant-types/refresh-token/).

* **Antonio Luis Gil Rodríguez** (3) [49352](https://platzi.com/comentario/466334/) 
¿LLamar al token devuelto “access_token” es algún tipo de estándar?

	* **Diego Alexander Forero Higuera (Platzi)** [49352] (3)

		Si, pero no hay ningún problema si lo llamas diferente, la verdad es que lo que retornas es el token con el cual puede acceder por lo tanto es el nombre más común y claro para la función de este token, si fuera un token de validación de algún tipo su nombre debería ser validation_token.

* **Camilo Andrés Santana Lizcano** (2) [1007294](https://platzi.com/comentario/1007294/) 

	Puedes generar la cadena de 256 bit [aquí](https://keygen.io/) en la opción **SHA 256-bit Key**

	* **Héctor Tello** [1007294] (1)

		Muchas gracias amigo.

* **c3tuxpo2018** (2) [818372](https://platzi.com/comentario/818372/) 

	Ir al Api  
	Construirlo desde cero  
	ver de que librerias depende  
	implementar
	
	* npm i -S express dotenv jsonwebtoken body-parser
	
	* dotenv: Donde se registra el secret
	
	* jsonwebtoken : Es la libreria que permite firmar y verificar el JWT
	
	* body_parser: Leer el body tipo jason del usuario que comparte el token
	
	* Esto se debe correr dentro del API
	
	* Se crea archivo .gitgnore para no enviar los archivos .env y la carpeta node_modules sea enviados al repositorio
	
	* se crea archivo .env.example y en el se crea la variable AUTH_JWT_SECRET=
	
	* Se copia el archivo .env.example y lo renombramos como .env
	
	* Se crea la carpeta config y dentro de ella requerimos la libreria dotenv y dentro de ella metemos la variable de entorno authJwtSecret
	
	
	

* **Nadir Antonio Soza Solis** (2) [598909](https://platzi.com/comentario/598909/) 

	Salio a la primera… Excelente explicación 😃
	``` 
	    {
	        "acess_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJuYWRpcnMxNCIsImVtYWlsIjoibmFkaXJzczE0QGdtYWlsLmNvbSIsIm5hbWUiOiJOYWRpciBTb3phIiwiaWF0IjoxNTU4OTg0NTg5fQ.BHWCn5DEe9qRQ-mi secreto"
	    }
	    
	```

* **Walter Lensinas** (2) [64607](https://platzi.com/comentario/679154/) 
Hago una consulta, ¿saben por que al quitar la clave de 256 bit igual dice que es valido el token o es un bug del sitio 

	* **glrodasz** [64607] (2)

		Hola el posible que sea un bug, mi recomendación es volver a copiar el token en el lado izquierdo y deberia reconocer que esta mal.

* **ma_angelica_romero** (2) [50192](https://platzi.com/comentario/476967/) 
Como puedo escribir require('dotenv').config() const config = { authJwtSecret: process.env.AUTH_JWT_SECRET } module.exports =...

	* **glrodasz** [50192] (2)

		Lo que pasa es que ese archivo lo lee directamente Node, no esta pasando por un transpilador como babel.
		
		La unica manera seria que usaras una version mucho mas moderna de Node y que habilitaras el flag para user ESM. (ES6 Modules), pero todavia es experimental asi que no se recomienda para producción.
		
		Más info:  
		<https://nodejs.org/api/esm.html>

* **AlvaroRT** (1) [925387](https://platzi.com/comentario/925387/) 

	Muy interesante.

* **Raul Gomez** (1) [719551](https://platzi.com/comentario/719551/) 

	mano a la obra!!

* **Nadir Antonio Soza Solis** (1) [598911](https://platzi.com/comentario/598911/) 

	Que es el valor “iat”: ####### que apareció dentro de mi payload al hacer el debuger de mi token

	* **Lorgio Ricardo Trinidad Caro** [598911] (2)

		Se trata del Claim Issued At, mas info aqui
		
		<https://www.iana.org/assignments/jwt/jwt.xhtml>

	* **Alan Jackson Duarte Marroquin** [598911] (1)

		es la fecha y hora actual en formato timestamp

	* **william andres rodriguez borja** [598911] (2)

		el lo explica en el video 14:35

* **Melina Jacqueline onoriaga** (1) [514776](https://platzi.com/comentario/514776/) 

	Donde puedo generar una cadena aleatoria de 256 byte ?

	* **Mati Beltramone** [514776] (6)

		<https://keygen.io/>

* **ma_angelica_romero** (1) [476967](https://platzi.com/comentario/476967/) 

	Como puedo escribir
	``` 
	    require('dotenv').config()
	    
	    const config = {
	        authJwtSecret: process.env.AUTH_JWT_SECRET
	    }
	    
	    module.exports = { config }
	    
	```
	
	en ES6

	* **glrodasz** [476967] (2)

		Lo que pasa es que ese archivo lo lee directamente Node, no esta pasando por un transpilador como babel.
		
		La unica manera seria que usaras una version mucho mas moderna de Node y que habilitaras el flag para user ESM. (ES6 Modules), pero todavia es experimental asi que no se recomienda para producción.
		
		Más info:  
		<https://nodejs.org/api/esm.html>

* **Antonio Luis Gil Rodríguez** (1) [466334](https://platzi.com/comentario/466334/) 

	¿LLamar al token devuelto “access_token” es algún tipo de estándar?

	* **Diego Alexander Forero Higuera (Platzi)** [466334] (3)

		Si, pero no hay ningún problema si lo llamas diferente, la verdad es que lo que retornas es el token con el cual puede acceder por lo tanto es el nombre más común y claro para la función de este token, si fuera un token de validación de algún tipo su nombre debería ser validation_token.

* **edg_colon** (1) [449927](https://platzi.com/comentario/449927/) 

	Agregue esta linea para poder parsear el body del request: `app.use(bodyParser.urlencoded({ extended: true }));`

	* **glrodasz** [449927] (2)

		Si, pero tienes que tener cuidado porque todo depende de la manera como le envies los datos al request, si los envias como json, necesitas `bodyParser.json()` si los envias como url encoded (application/x-www-form-urlencoded) es decir si los valores los envias en tuplas separados por “&” y “=”.
		
		Más info: <https://developer.mozilla.org/es/docs/Web/HTTP/Methods/POST>

* **Arturo Jesus Gonzalez Villamizar** (0) [619619](https://platzi.com/comentario/619619/) 

	Simpre se utiliza la misma AUTH_JWT_SECRETo como puede dinamizarse esto ?

	* **Walter Lensinas** [619619] (2)

		Es una variable de entorno que vas a mantener en tu servidor para verificar todos los json web tokens de tus usuarios.  
		Vas a tener una variable de entorno para cada tipo de servidor que poseas. Un esquema en cualquier organización podría ser la siguiente:
		
		  1. Desarrollo: tu localhost
		  2. Testing
		  3. Producción
		
		
		
		Cada servidor contara con una variable distinta.

## 0090. Verificando nuestro JWT firmado y buenas practicas con JWT [15815](https://platzi.com/clases/1439-autenticacion-oauth/15815-verificando-nuestro-jwt-firmado-y-buenas-practicas/)

### Descripción:


Gracias a la librería `jsonwebtokens` también podemos validar nuestros JWT utilizando el método `jwt.verify()`, en esta clase vamos a crear un nuevo endpoint (`/api/auth/verify`) donde debemos devolver el el nombre de usuario que encontramos si el token que verificamos es valido. En caso de que el token no sea valido, vamos a devolver un error utilizando el método `next()` de la librería `express`.

Buenas prácticas al utilizar JWT:

* **Nunca transmitir información sensible** : Recuerda que los JWT son completamente decodificables, su seguridad no esta en la encripción de datos que transmitimos por los tokens sino en la validación frente a nuestros servidores. Toda la información que transmitimos por JWT debe ser tratada como si fuera enviada por texto plano.
* **Mantener los tokens pequeños** : Los JWT NO son un medio de transmisión de datos, su única responsabilidad es verificar la autenticación de nuestros usuarios. para obtener la información de nuestros usuarios debemos crear nuevos _endpoints_ en la API de nuestra aplicación que, por su puesto, solo deben ser disponibles si enviamos un token valido.
* **Configurar tiempos de vida de muy cortos** : El tiempo de vida de nuestros _tokens_ son el tiempo en que podemos utilizarlos, la recomendación son máximo 15 minutos. Entre más grande sea este tiempo, más tiempo tienen quienes quieran cometer ataques a nuestra aplicación.
* **Crear JWT opacos** : Nunca es una buena idea decodificar nuestros tokens desde el cliente o frontend de nuestra aplicación, recuerda que este código es completamente público y corremos el riesgo de que alguien más acceda a las llaves privadas de nuestra aplicación.



### Links:

* [GitHub - auth0/node-jsonwebtoken: JsonWebToken implementation for node.js http://self-issued.info/docs/draft-ietf-oauth-json-web-token.html](https://github.com/auth0/node-jsonwebtoken)

### Comentarios:

* **Fredy Ricardo Cortés Ramírez** (2) [68257](https://platzi.com/comentario/737588/) 
¿Cómo podría implementar el cifrado asimétrico de la autenticación con Json Web Tokens?, ya que es la forma que tu recomiendas.

* **José Valentin Salina Peña** (2) [47838](https://platzi.com/comentario/447726/) 
Esta validación del token incluye la duración? En caso de estar expirado falla??

	* **glrodasz** [47838] (2)

		Si, en caso de tenerla la valida:
		
		> The callback is called with the decoded payload if the signature is valid and optional expiration, audience, or issuer are valid. If not, it will be called with the error.
		
		Más info:  
		<https://github.com/auth0/node-jsonwebtoken#jwtverifytoken-secretorpublickey-options-callback>

* **ksanchez_cld** (1) [996827](https://platzi.com/comentario/996827/) 

	JWT Format
	
	[Base64-URL encoded header].[Base64-URL encoded payload].[Signature]
	
	eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.XbPfbIHMI6arZ3Y922BhjWgQzWXcXNrz0ogtVhfEd2o
	
	  1. Header: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.
	
	  2. Payload: eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.
	
	  3. Signature XbPfbIHMI6arZ3Y922BhjWgQzWXcXNrz0ogtVhfEd2o
	
	
	

* **Jordi Santamaría Portolés** (1) [530589](https://platzi.com/comentario/530589/) 

	platzi, igual como la mayoria de servicios no usan jwt? o es que lo guardan en algun lugar k no sea local storage?

	* **Jordi Santamaría Portolés** [530589] (1)

		mm hay algo mas k no me ha quedado claro, si un token es para poder hacer login de sesion, no es mejor que se mantenga mucho tiempo para que un usuario el dia siguiente no tenga kvolver a hacer login?

	* **ebar0n (Platzi)** [530589] (1)

		Hola, usan otra tipo de autenticación, no todos usan jwt.
		
		En local storage, si se guardan normalmente ciertas cosas de manera ofuscada.

	* **ebar0n (Platzi)** [530589] (2)

		Respecto a tu segunda duda, si, pero eso depende del tipo de aplicación, si es una red social tal vez si quieras mantener siempre tu sesión abierta, pero si es el login de un banco no, entonces quieres que tu token expire por requerimiento propio del tipo de aplicación.

	* **william andres rodriguez borja** [530589] (1)

		lo tienen en una cookie

	* **Andres Roberto Coello Goyes** [530589] (1)

		en localStorage se mantiene la informacion pero puede ser modificada si un JWT se modifica, pasa ah ser invalido.  
		Es buena practica guardar en una COOKIE por defecto las cookies viajan al servidor en cada peticion. tambien exiten metodos de encriptacion de cookies para que alguien con malas intenciones no lo pueda modificar o decodificar. asi estaras segura,✌

* **José Valentin Salina Peña** (1) [447726](https://platzi.com/comentario/447726/) 

	Esta validación del token incluye la duración? En caso de estar expirado falla??

	* **glrodasz** [447726] (2)

		Si, en caso de tenerla la valida:
		
		> The callback is called with the decoded payload if the signature is valid and optional expiration, audience, or issuer are valid. If not, it will be called with the error.
		
		Más info:  
		<https://github.com/auth0/node-jsonwebtoken#jwtverifytoken-secretorpublickey-options-callback>

* **pedepepe** (1) [446303](https://platzi.com/comentario/446303/) 

	Pregunta, si yo hiciera caducar los tokens cada 15 minutos, como podria implementar una sesion de larga duracion para un cliente?

	* **glrodasz** [446303] (1)

		Mediante un refresh token, voy a agregar un lectura sobre ellos en los proximos dias mientras tanto puedes consultar mas información aqui: <https://auth0.com/blog/refresh-tokens-what-are-they-and-when-to-use-them/>

	* **ksanchez_cld** [446303] (0)
Derivada de la pregunta anterior me surge la siguiente. Sería una buena práctica hacerlo?

## 0100. Server-Side vs Client-Side sessions [15814](https://platzi.com/clases/1439-autenticacion-oauth/15814-server-side-vs-client-side-sessions/)

### Descripción:


Autenticar usuarios desde de lado del servidor es considerado stateful, debemos utilizar sesiones para preservar los estados de autenticación, es decir, guardamos en memoria o en una base de datos un identificador que nos permita comprobar si los usuarios están o no autenticados.

Por otro lado, la autenticación de lado del cliente no utiliza sesiones, en realidad, no tenemos forma de verificar si los usuarios están autenticados o no, en vez de esto, validamos los datos de usuario para obtener tokens (con límite de tiempo) que utilizamos en las peticiones al servidor para validar el acceso y consultar nuestra información.

Proceso de autenticación de lado del cliente:

  1. Cuando los usuarios hacen login, el servidor responde con un token _(indicando que el login fue exitoso)_ y nosotros, de lado del cliente, agregamos una bandera para indicar que el usuario esta autenticado.
  2. En cualquier punto de nuestra aplicación _(por ejemplo, cuando cambiamos de ruta o hacemos una nueva petición)_ debemos verificar la expiración de los tokens.
  3. Si el token expira, debemos cambiar la bandera para indicar que el usuario NO esta autenticado y nuevamente redireccionar a los usuarios a la ruta de login.



### Comentarios:

* **Juan David Castro (Platzi)** (13) [445253](https://platzi.com/comentario/445253/) 

	Notas de la clase:
	
	* Las sesiones del lado del servidor funcionan almacenando un indicador en memoria o en la base de datos, cuando este indicador desaparece, significa que el usuario ya NO esta autenticado 👍
	* Estos indicadores viajan (normalmente) a través de cookies, el servidor lo envia al navegador y el navegador lo envía de vuelta al servidor 🔂
	* Del lado del cliente NO utilizamos sesiones 😮
	* En Single Page Applications NO tenemos forma de verificar la autenticación de los usuarios, tendríamos que refrescar la página cada vez que necesitamos nueva información y básicamente se pierde el chiste, así no funcionan estas aplicaciones 😦
	* En vez de sesiones utilizamos tokens, enviamos los datos de autenticación de nuestros usuarios al servidor y, si los datos son correctos, el servidor devuelve un token, una llave que nos da acceso por algún tiempo a la información autorizada de los usuarios 🎉👌
	* Si en alguna de las peticiones al servidor nos informan que el token ha expirado pos, volvemos a hacer login y seguimos como si nada 😅💪
	
	

* **c3tuxpo2018** (3) [819122](https://platzi.com/comentario/819122/) 

	PLatzi usa Web tokens??

	* **Miguel Angel Marquez Munoz** [819122] (1)

		dale f12 y date cuenta

	* **Jair Israel Avilés Eusebio** [819122] (1)

		Usando las developer tools de chrome al parecer usan una especie de cookie.

* **AlvaroRT** (1) [925595](https://platzi.com/comentario/925595/) 

	buena explicación.

## 0110. Protegiendo nuestros recursos con JWT [15817](https://platzi.com/clases/1439-autenticacion-oauth/15817-protegiendo-nuestros-recursos-con-jwt/)

### Descripción:


Actualmente utilizamos dos algoritmos de cifrado para proteger nuestros JWT: RS256, donde necesitamos una llave publica y una privada para validar la información desde el servidor y el cliente (utiliza la RSA Signature con SHA-256), y HS256, donde tenemos un poco menos de seguridad ya que, utilizamos a misma llave para generar y validar los tokens (utiliza el HMAC también con SHA-256).

### Comentarios:

* **Cristian David Franco Garcia** (4) [468411](https://platzi.com/comentario/468411/) 

	<https://auth0.com/blog/navigating-rs256-and-jwks/>

* **EmmanuelO** (3) [468110](https://platzi.com/comentario/468110/) 

	Yo lo hice en Python, usando Django y una libreria que se llama pyjwt

* **AlexGarrixen** (2) [62904](https://platzi.com/comentario/648077/) 
Podrias hacernos una lectura donde puedas explicar como implementar refresh token,ya que he leido en varios posts y blogs como implement...

	* **glrodasz** [62904] (1)

		Hola AlexGarrixen, podrias incluir aquí las referencias que has encontrado, asi yo puedo revisarlas y darte una mejor opinion?

* **David Vargas Domínguez** (1) [988687](https://platzi.com/comentario/988687/) 

	Cuándo usar el algoritmo HS256 o RS256

* **David Vargas Domínguez** (1) [988682](https://platzi.com/comentario/988682/) 

	Cuándo usar HS256 o RS256

* **c3tuxpo2018** (1) [818428](https://platzi.com/comentario/818428/) 

	OK nadie ha hecho el reto. veamos cuanto me demoro

* **kingofking999** (1) [554990](https://platzi.com/comentario/554990/) 

	haber me dicen si mi idea esta correctamente de los jwt simetricos y asimetricos
	
	los simetricos es la misma llave del lado del cliente y del lado del servidor por ejemplo una api rest que esta alimentando varios tipos de clientes como lo seria  
	una app en (android,ios) un website … etc a esto te refieres cuando mencionas le del cliente osea que tu eres dueño de cliente / servidor
	
	los asimetricos es para que no tengas que darle a tus clientes osea a los que generaron las apps de (android,ios) el website o que estan cosumiendo tus servicios tu clave privada … lo que haces es generar una clave privada con la que generas los tokens y una clave publica a los que usaran tus servicios asi no hay riesgo de que alguien mas genere tus tokens
	
	o me equivoco ?

	* **Everardo Sánchez** [554990] (1)

		Te recomeindo ver este video desde el min 44:00 (aunque si lo ves todo sería ideal). Explica muy bien la diferencia entre llaves simétricas y asimétricas.  
		[https://www.youtube.com/watch?v=E03gh1huvW4&](https://www.youtube.com/watch?v=E03gh1huvW4&)

* **Jordi Santamaría Portolés** (1) [530596](https://platzi.com/comentario/530596/) 

	A que se refiere con tener control sobre los clientes, el cliente es el navegador de un usuario no? como vas a tener control sobre su navegador…

	* **ebar0n (Platzi)** [530596] (1)

		Hola, estás en lo cierto, pero pesemos en algo, si es software empresarial privativo, una aplicación que usas para gestionar algo en un empresa por ejemplo, los clientes (navegadores) si podrían ser controlados.

	* **Jair Israel Avilés Eusebio** [530596] (2)

		No necesariamente un cliente es un agent UI tipo web browser. En un entorno de microservicios, un microservicio puede servir a otro de estos.

* **ma_angelica_romero** (1) [477186](https://platzi.com/comentario/477186/) 
Se puede usar un encriptado SHA512?

	* **glrodasz** [477186] (1)

		La pregunta es muy abierta, pero **si**.
		
		Más info:  
		<https://docs.microsoft.com/en-us/dotnet/api/system.security.cryptography.sha512?view=netframework-4.7.2>  
		<https://medium.com/@davidtstrauss/stop-using-sha-256-6adbb55c608>

* **Alvaro   Gonzalez** (1) [447045](https://platzi.com/comentario/447045/) 

	Como se hace con un api, que se require consumir por los mobiles, apple, google etc, com se hace uso del Cors …?

	* **Alvaro   Gonzalez** [447045] (1)

		Dado que esto no es recomendado para produccion ? >> app.use(cors());

	* **glrodasz** [447045] (5)

		El CORS solo aplica para codigo que se ejecuta desde un navegador (Chrome, Firefox, Safari, etc), en el caso mobile, no deberia ser necesario implementarlo.

## 0120. Habilitando CORS en nuestro servidor [15816](https://platzi.com/clases/1439-autenticacion-oauth/15816-habilitando-cors-en-nuestro-servidor/)

### Descripción:


# Habilitando CORS en nuestro servidor

El Intercambio de Recursos de Origen Cruzado (Cross-Origin Resource Sharing) es un mecanismo que agrega unos encabezados (Headers) adicionales HTTP para permitir que un user agent (generalmente un navegador) obtenga permisos para acceder a los recursos de un servidor en un origin distinto (dominio) del que pertenece.

**Por ejemplo una solicitud de origen cruzado seria** hacer una petición AJAX desde una aplicación que se encuentra en <https://dominio-a.com> para cargar el recurso <https://api.dominio-b.com/data.json>.

> Por razones de seguridad, los navegadores restringen las solicitudes HTTP de origen cruzado iniciadas dentro de un script.

Si necesitamos permitir request desde un dominio diferente al del servidor podemos usar el middleware `cors` para permitirlo, pero es importante no dejarlo expuesto a todos los dominios.

## Habilitar CORS para todos los request (No recomendado en producción)
``` 
    const express = require("express");
    const cors = require("cors");
    const app = express();
    
    app.use(cors());
    
    app.get("/products/:id", function(req, res, next) {
      res.json({ msg: "This is CORS-enabled for all origins!" });
    });
    
    app.listen(8000, function() {
      console.log("CORS-enabled web server listening on port 8000");
    });
    
```

## Habilitar CORS para los request especificos de un cliente (Recomendado para producción)
``` 
    const express = require("express");
    const cors = require("cors");
    const app = express();
    
    const corsOptions = { origin: "http://example.com" };
    
    app.use(cors(corsOptions));
    
    app.get("/products/:id", function(req, res, next) {
      res.json({ msg: "This is CORS-enabled for only example.com." });
    });
    
    app.listen(8000, function() {
      console.log("CORS-enabled web server listening on port 8000");
    });
    
```

Debemos tener en cuenta que para aplicaciones server-side es poco probable que necesiten el uso de CORS debido a que las aplicaciones conviven en el mismo dominio. Sin embargo, es buena practica habilitarlo para los llamados externos de nuestra API.

Más información sobre el middleware cors en <https://expressjs.com/en/resources/middleware/cors.html>

### Comentarios:

* **Walter Ugalde A** (2) [49120](https://platzi.com/comentario/462978/) 
// Importar la libreria de cors const cors = require('cors') //Configuracion del cors const ALLOWED_ORIGINS = ['https://miAPI.com'...

	* **glrodasz** [49120] (4)

		El problema es que Ionic esta generando una aplicación mobile hibrida, por lo que por debajo esta funcionando como un cliente de navegador.
		
		Lo que puedes hacer es usar proxy server con ionic: <https://blog.ionicframework.com/handling-cors-issues-in-ionic/>

* **Walter Ugalde A** (1) [462978](https://platzi.com/comentario/462978/) 

	```
	    // Importar la libreria de cors
	    const cors = require('cors')
	    
	    //Configuracion del cors
	    const ALLOWED_ORIGINS = ['https://miAPI.com', 'http://localhost:8080']
	    app.use(cors({
	        origin: function (origin, callback) {
	            if(!origin) return callback(null, true)
	            if(ALLOWED_ORIGINS.indexOf(origin) ===-1)
	                return callback(newError(`Origen no permitido ${origin}, bloqueado, por seguridad`), false)
	            return callback(null, true)
	        }
	    }))
	    
	```
	
	> > Tengo esa confugración, fue necesario agregar ¨http://localhost:8080" ya que por medio de una app hecha en ionic que corre desde mobiles no me permitia conectarme.
	
	Hay alguna forma de hacer eso mejor, que agregando <http://localhost:8080> ?

	* **glrodasz** [462978] (4)

		El problema es que Ionic esta generando una aplicación mobile hibrida, por lo que por debajo esta funcionando como un cliente de navegador.
		
		Lo que puedes hacer es usar proxy server con ionic: <https://blog.ionicframework.com/handling-cors-issues-in-ionic/>

	* **Everardo Sánchez** [462978] (1)

		Como el puerto es diferente, se toma como si vniera de una fuente diferente a pesar de que el dominio sea el mismo.

## 0130. Profundizando el concepto de JWKS [15967](https://platzi.com/clases/1439-autenticacion-oauth/15967-profundizando-el-concepto-de-jwks/)

### Descripción:


# Profundizando el concepto de JWKS

HS256 y R256 son dos de los algoritmos soportados para firmar JSON Web Tokens. El algoritmo HS256 genera una firma simétrica, esto quiere decir el secret/key se usa tanto para el firmado como para la verificación de la firma. Mientras que, el algoritmo RS256 genera una firma asimétrica y en este caso es una llave privada la que se usa para el firmado y una llave publica es la que se usa para verificar la firma.

[JWK](https://tools.ietf.org/html/rfc7517) es una especificación para representar las llaves criptográficas que se usan en el firmado de token usando RS256.

La especificación define dos estructuras de datos de alto nivel: **JSON Web Key (JWK)** y **JSON Web key Set (JWKS)**.

> **JSON Web Key (JWK)** : Un objeto JSON que representa una llave criptográfica. Las propiedades del objeto representan propiedades de la llave incluyendo su valor.

> **JSON Web key Set (JWKS)** : Un objeto JSON que representa un conjunto de JWKs. El objeto JSON debe tener una propiedad llamada `keys` que es la lista de JWKs.

Al nivel más básico el JWKS contiene las llaves publicas que deberían ser usadas para verificar un JWT generado por el Authorization Server.

Este es un ejemplo de como la respuesta de un endpoint que expone los JWKS:
``` 
    {
      "keys": [
        {
          "alg": "RS256",
          "kty": "RSA",
          "use": "sig",
          "x5c": [
            "MIIC+DCCAeCgAwIBAgIJBIGjYW6hFpn2MA0GCSqGSIb3DQEBBQUAMCMxITAfBgNVBAMTGGN1c3RvbWVyLWRlbW9zLmF1dGgwLmNvbTAeFw0xNjExMjIyMjIyMDVaFw0zMDA4MDEyMjIyMDVaMCMxITAfBgNVBAMTGGN1c3RvbWVyLWRlbW9zLmF1dGgwLmNvbTCCASIwDQYJKoZIhvcNAQEBBQADggEPADCCAQoCggEBAMnjZc5bm/eGIHq09N9HKHahM7Y31P0ul+A2wwP4lSpIwFrWHzxw88/7Dwk9QMc+orGXX95R6av4GF+Es/nG3uK45ooMVMa/hYCh0Mtx3gnSuoTavQEkLzCvSwTqVwzZ+5noukWVqJuMKNwjL77GNcPLY7Xy2/skMCT5bR8UoWaufooQvYq6SyPcRAU4BtdquZRiBT4U5f+4pwNTxSvey7ki50yc1tG49Per/0zA4O6Tlpv8x7Red6m1bCNHt7+Z5nSl3RX/QYyAEUX1a28VcYmR41Osy+o2OUCXYdUAphDaHo4/8rbKTJhlu8jEcc1KoMXAKjgaVZtG/v5ltx6AXY0CAwEAAaMvMC0wDAYDVR0TBAUwAwEB/zAdBgNVHQ4EFgQUQxFG602h1cG+pnyvJoy9pGJJoCswDQYJKoZIhvcNAQEFBQADggEBAGvtCbzGNBUJPLICth3mLsX0Z4z8T8iu4tyoiuAshP/Ry/ZBnFnXmhD8vwgMZ2lTgUWwlrvlgN+fAtYKnwFO2G3BOCFw96Nm8So9sjTda9CCZ3dhoH57F/hVMBB0K6xhklAc0b5ZxUpCIN92v/w+xZoz1XQBHe8ZbRHaP1HpRM4M7DJk2G5cgUCyu3UBvYS41sHvzrxQ3z7vIePRA4WF4bEkfX12gvny0RsPkrbVMXX1Rj9t6V7QXrbPYBAO+43JvDGYawxYVvLhz+BJ45x50GFQmHszfY3BR9TPK8xmMmQwtIvLu1PMttNCs7niCYkSiUv2sc2mlq1i3IashGkkgmo="
          ],
          "n": "yeNlzlub94YgerT030codqEztjfU_S6X4DbDA_iVKkjAWtYfPHDzz_sPCT1Axz6isZdf3lHpq_gYX4Sz-cbe4rjmigxUxr-FgKHQy3HeCdK6hNq9ASQvMK9LBOpXDNn7mei6RZWom4wo3CMvvsY1w8tjtfLb-yQwJPltHxShZq5-ihC9irpLI9xEBTgG12q5lGIFPhTl_7inA1PFK97LuSLnTJzW0bj096v_TMDg7pOWm_zHtF53qbVsI0e3v5nmdKXdFf9BjIARRfVrbxVxiZHjU6zL6jY5QJdh1QCmENoejj_ytspMmGW7yMRxzUqgxcAqOBpVm0b-_mW3HoBdjQ",
          "e": "AQAB",
          "kid": "NjVBRjY5MDlCMUIwNzU4RTA2QzZFMDQ4QzQ2MDAyQjVDNjk1RTM2Qg",
          "x5t": "NjVBRjY5MDlCMUIwNzU4RTA2QzZFMDQ4QzQ2MDAyQjVDNjk1RTM2Qg"
        }
      ]
    }
    
```

Cada una de las propiedades definida en cada JWK hacer parte de la especificación [RFC 7517 Section 4](https://tools.ietf.org/html/rfc7517#section-4) estos son algunos de los significados de las propiedades:

* alg: es el algoritmo de la llave
* kty: es el tipo de llave.
* use: es como la llave será usada. En el ejemplo anterior significa que sera usado como una firma.
* x5c: es la cadena de certificado x509.
* kid: es un identificador único de la llave.



## Verificando un JWT usando un endpoint JWKs

Para verificar un JWT usando JWKS estos son los pasos a grandes rasgos que se deben seguir:

  1. Obtener los JWKS del endpoint y filtrar las potenciales keys de firmado.
  2. Extraer el JWT del header del request de autorización.
  3. Decodificar el JWT y obtener la propiedad `kid` del header.
  4. Encontrar la llave de firmado filtrada de los JWKS usando la propiedad `kid`.
  5. usar la propiedad `x5c`para construir un certificado que es el que posteriormente se podrá usar para verificar la firma del JWT.



Generalmente estos pasos se hace usando alguna librería que lo haga por nosotros. Aquí tenemos un ejemplo de como implementar la lectura y verificación de un JWT usando JWKS en un servidor con Express.js:
``` 
    const express = require("express");
    const app = express();
    const jwt = require("express-jwt");
    const jwks = require("jwks-rsa");
    
    const port = process.env.PORT || 8080;
    
    const jwtCheck = jwt({
      secret: jwks.expressJwtSecret({
        cache: true,
        rateLimit: true,
        jwksRequestsPerMinute: 5,
        jwksUri: "<authorization-server-url>/.well-known/jwks.json"
      }),
      audience: "<api-indentifier>",
      issuer: "<authorization-server-url>",
      algorithms: ["RS256"]
    });
    
    app.use(jwtCheck);
    
    app.get("/authorized", function(req, res) {
      res.send("Secured Resource");
    });
    
    app.listen(port);
    
```

### Comentarios:

* **Raul Gomez** (1) [739558](https://platzi.com/comentario/739558/) 

	super pagina de informacion

# OAuth 2.0 [3108]

## 0140. ¿Qué es OAuth 2.0 [16036](https://platzi.com/clases/1439-autenticacion-oauth/16036-que-es-oauth-20/)

### Descripción:


En esta clase el profesor Guillermo Rodas nos explica en qué consiste el protocolo OAuth 2.0 y por qué se ha convertido en uno de los estándares más importantes de la industria para la autorización.

Gracias a los estándares de seguridad hoy en día podemos compartir flujos de autorización y autenticación entre diferentes aplicaciones, es decir, podemos aprender el paso a paso de cómo funcionan estos servicios y aplicarlos para proteger nuestras aplicaciones.

### Comentarios:

* **ivanguerra10** (10) [448784](https://platzi.com/comentario/448784/) 

	Es excelente hasta ahora este curso. La explicacion es muy clara de todos los conceptos, y ademas con ejemplos adicionales de la vida real para bajar aun mas a tierra los conceptos aprendidos. 👏👏

* **JMM** (7) [451221](https://platzi.com/comentario/451221/) 

	Por si le sirve a alguien 😃
	
	<https://www.ibm.com/support/knowledgecenter/zh/SSELE6_8.0.1.3/com.ibm.isam.doc/config/concept/con_oauth_20_concepts.html>

* **c3tuxpo2018** (3) [819231](https://platzi.com/comentario/819231/) 

	Si alguien me puede corregir se lo agradecería.
	
	* Le pido el favor a mi hija que vaya a mi apartamento y recoja mi portátil, le doy mi cédula para que ella se la presente al celador del edificio y el le entregue las laves del apartamento
	* Ella llega a la portería y presenta mi cédula indicando que viene en nombre mio a recoger las llaves del apartamento
	* EL celador verifica que la cédula es correcta y le entrega las llaves a mi hija
	* Es correcta mi analogía? o me falta algo
	
	

	* **Jair Israel Avilés Eusebio** [819231] (1)

		Es correcta

* **Alexander Mateo** (2) [737418](https://platzi.com/comentario/737418/) 

	Muy clara la explicación 😄

	* **Jonatan Francisco Gonzalez Donis** [737418] (1)
:O

* **danielvillalobos** (2) [719684](https://platzi.com/comentario/719684/) 

	esto me suena similar al curso de API REST, autenticacion con Acces Token en donde interfieren siempre 3 actores el cliente, el servidor de autenticacion, y el servidor donde se solicitan los recursos esto es cierto?

* **Héctor Tello** (1) [1049422](https://platzi.com/comentario/1049422/) 

	No había entendido del todo el funcionamiento, pero con el ejemplo de la pelota y de la aplicación pidiendo permisos para acceder a nuestros recursos, lo entendí del todo.

* **IngAntonyF** (1) [953287](https://platzi.com/comentario/953287/) 

	jajajaj que excelente ejemplo.

* **AlvaroRT** (1) [925741](https://platzi.com/comentario/925741/) 

	Quedo muy claro con el ejemplo.

* **ahernandezb** (1) [869482](https://platzi.com/comentario/869482/) 

	excelente la explicación de la vida real

* **jcalderon.sys** (1) [774183](https://platzi.com/comentario/774183/) 

	Buena explicacion, muy clara y precisa.

* **Raul Gomez** (1) [739566](https://platzi.com/comentario/739566/) 

	una explicacion my clara de OAuth 2.0

* **Lorgio Ricardo Trinidad Caro** (1) [656773](https://platzi.com/comentario/656773/) 

	De que forma el resource owner puede verificar que la aplicación es quien dice ser?

	* **Diego Alexander Forero Higuera (Platzi)** [656773] (1)

		Puede ser por medio de información que se pasa en el header de la petición request, con esta verifica que no haya nadie interceptando el tráfico por ejemplo.

## 0150. Cómo elegir el flujo adecuado para OAuth 2.0 [15819](https://platzi.com/clases/1439-autenticacion-oauth/15819-como-elegir-el-flujo-adecuado-para-oauth-20/)

### Descripción:


### Comentarios:

* **Cristian David Franco Garcia** (6) [469031](https://platzi.com/comentario/469031/) 

	<https://auth0.com/docs/api-auth/which-oauth-flow-to-use>

* **Raul Gomez** (3) [739573](https://platzi.com/comentario/739573/) 

	debemos marcar esta clase com critica por la informacion que maneja

* **Juan David Castro (Platzi)** (3) [470166](https://platzi.com/comentario/470166/) 

	* [Grant - OAuth Middleware for Express, Koa and Hapi](https://github.com/simov/grant)
	
	

* **Everardo Sánchez** (2) [880767](https://platzi.com/comentario/880767/) 

	Implicit ya no debería usarse. <https://oauth.net/2/grant-types/implicit/>

* **c3tuxpo2018** (2) [819281](https://platzi.com/comentario/819281/) 

	MI resumen
	
	* Si somos el Resource Owner se usa el flujo Client Credential Grant
	
	* Si somos una Wep App ejecutandose del lador del servidor se usa el flujo Authorization Code Grant
	
	* Si somos un cliente al que se le pueden confiar las credenciales de usuario se usa el flujo Resource Owner Password Credential Grant
	
	
	
	
	-Si somos una Single Page up se usa el flujo Implicit Grant
	
	* Si somos una aplicacion nativa se usa el flujo Authorization Code Grant (PKCE)
	
	

* **Miusuarioplatzi** (2) [723029](https://platzi.com/comentario/723029/) 

	Puedes por favor dejar los nombres de los Flujos mostrados

* **Alexander  Silvera** (2) [55918](https://platzi.com/comentario/546783/) 
Para una aplicación realizada con django, que se recomienda para la autenticación y autorización??

	* **aragonesteban (Platzi)** [55918] (2)

		Puedes usar el mismo sistema de autenticación que ya trae django por defecto.

* **Steven18** (2) [53389](https://platzi.com/comentario/517003/) 
Para el desarrollo de aplicaciones móviles híbridas, ¿Qué flujo es el recomendado a utilizar?

	* **glrodasz** [53389] (3)

		Implicit Grant

* **AlvaroRT** (1) [925750](https://platzi.com/comentario/925750/) 

	Buena explicación

* **jcalderon.sys** (1) [774212](https://platzi.com/comentario/774212/) 

	Bien detallado todos los flujos que tiene en OAuth.

* **Alexander  Silvera** (1) [546783](https://platzi.com/comentario/546783/) 

	Para una aplicación realizada con django, que se recomienda para la autenticación y autorización??

	* **aragonesteban (Platzi)** [546783] (2)

		Puedes usar el mismo sistema de autenticación que ya trae django por defecto.

	* **davidtoca (Platzi)** [546783] (1)

		puedes usar python-social-auth si quieres manerar login a traves de redes sociales

* **Steven18** (1) [517003](https://platzi.com/comentario/517003/) 

	Para el desarrollo de aplicaciones móviles híbridas, ¿Qué flujo es el recomendado a utilizar?

	* **glrodasz** [517003] (3)

		Implicit Grant

* **Michael Emir Reynosa Beltrán** (1) [69056](https://platzi.com/comentario/750471/) 
Tengo una duda, si bien es cierto OAuth me ayuda a la autorización de cliente y/o usuario. Y tanto el “cliente” como el “usuario” según e...

## 0160. Conociendo el API de Spotify [15820](https://platzi.com/clases/1439-autenticacion-oauth/15820-conociendo-el-api-de-spotify/)

### Descripción:


### Links:

* [Web API | Spotify for Developers](https://developer.spotify.com/documentation/web-api/)

* [Authorization Guide | Spotify for Developers](https://developer.spotify.com/documentation/general/guides/authorization-guide/)

* [900 Fastly Internal](https://developer.spotify.com/documentation/web-api/reference/playlists/get-list-users-playlist/)

### Comentarios:

* **Santiago Andres Diaz Villarreal** (3) [50275](https://platzi.com/comentario/477823/) 
Buenas noches, Que es un authorization Bearer? Y cual es la diferencia entre Authorization basic y un bearer? Muchas gracias.

	* **glrodasz** [50275] (11)

		La palabra **Bearer** tiene una traducción aproximada a **Portador**.
		
		Algo asi como:
		
		> El portador de este token, tiene acceso a las puertas concedidas.
		
		Hazte de cuenta que funciona como cuando endosas un cheque y el valor del cheque lo puede reclamar quien lo **porte**.
		
		En este caso este cheque seria el **Token** que envias en el header, la construccion de este Token varia, puede ser un string opaco o pueder ser un JSON Web Token.
		
		**Authorization Basic** por otro lado usa las credenciales que conocemos como username y password, y su valor es la siguiente formula:
		
		Codificas en base 64: <username>:<password>.
		
		Ten en cuenta que la codificación es un proceso reversible se hace mas con el fin de evitar problemas de caracteres especiales, asi quien lo recibe lo puede simplemente decodificar y obtener sus valores. Lo otro es que siempre que envies una petición de Authorizacion sea Basic o Bearer debe ser sobre SSL/TLS (HTTPS).

* **Raul Gomez** (2) [741883](https://platzi.com/comentario/741883/) 

	con este tipo de explicacion se aclaran mucho el panorama de flujos de autentificacion

* **Jordi Santamaría Portolés** (2) [530682](https://platzi.com/comentario/530682/) 

	Este curso es para saber crear un sistema de authentificacion para nuestros websites, o para aprender a consumir el servicio de spotify xD

	* **Diego Alexander Forero Higuera (Platzi)** [530682] (4)

		El se enseña como hacer autenticación usando oAuth para eso se va a usar el api de autenticación de spotify, se pudo haber usado el de github, gmail, facebook, twitter, etc.

	* **Alexander Mateo** [530682] (5)

		haha En realidad es mejor si la teoría va acompañada con ejemplos prácticos, de hecho yo estoy aplicando todo lo aprendido en una aplicación hecha con Flutter , y que utiliza Firebase para realizar la autenticación con OAuth2.0, porque la seguridad es muy importante. ¡Saludos! 😃

	* **william andres rodriguez borja** [530682] (1)

		en mi caso esto fue de mucha ayuda en java y spring boot las las librerias para autenticar soy un poco complejas. me cree un metodo que arma la url y va al servicio.  
		creo que el objeto de esto es entender oauth mas que aprender a usar una libreria donde el metodo es auth.google(user, clientId) y ya es entender que son endpoints que reciben los mismos parametros nos devuelven un access_token y etc.  
		Yo ya he trabajado con oauth me he conectado con facebook y google y ni sabia bien que es oauth ahora todo tienen mayor sentido.

	* **william andres rodriguez borja** [530682] (1)

		@silexcorp firebase ya trae todo lo que tiene que ver con oauth por defecto firebase es un backend como servicio por ende tiene la base de datos firestore, la autenticacion OAuth y logica negocio Functions.  
		en firebase es tan dificil como auth.signWithGoogle()

* **AlvaroRT** (1) [927712](https://platzi.com/comentario/927712/) 

	Excelente clase.

* **frutillitadulc1** (1) [869076](https://platzi.com/comentario/869076/) 

	q es renderizado,no se q qieres decir!

	* **Andres Roberto Coello Goyes** [869076] (1)

		Es como un tipo de retorno, por ejemplo cuando una app nos permite loguearnos con redes sociales como google y la damos CLICK, los datos de ese usuario que se encuentran en GOOGLE se redirizen a nuestra app,

* **Santiago Andres Diaz Villarreal** (1) [477823](https://platzi.com/comentario/477823/) 

	Buenas noches,  
	Que es un authorization Bearer?  
	Y cual es la diferencia entre Authorization basic y un bearer?
	
	Muchas gracias.

	* **glrodasz** [477823] (11)

		La palabra **Bearer** tiene una traducción aproximada a **Portador**.
		
		Algo asi como:
		
		> El portador de este token, tiene acceso a las puertas concedidas.
		
		Hazte de cuenta que funciona como cuando endosas un cheque y el valor del cheque lo puede reclamar quien lo **porte**.
		
		En este caso este cheque seria el **Token** que envias en el header, la construccion de este Token varia, puede ser un string opaco o pueder ser un JSON Web Token.
		
		**Authorization Basic** por otro lado usa las credenciales que conocemos como username y password, y su valor es la siguiente formula:
		
		Codificas en base 64: <username>:<password>.
		
		Ten en cuenta que la codificación es un proceso reversible se hace mas con el fin de evitar problemas de caracteres especiales, asi quien lo recibe lo puede simplemente decodificar y obtener sus valores. Lo otro es que siempre que envies una petición de Authorizacion sea Basic o Bearer debe ser sobre SSL/TLS (HTTPS).

	* **Jhon Bayron  Agudelo Rendon** [477823] (1)

		Cual de las dos es la mas segura o recomendable para implementar ? en la mayoria de implimentaciones e visto la Authorization Bearer y pero con derecho a equivocarme parece mas segura la Authorization Basic.

	* **glrodasz** [477823] (9)

		Bueno, no se trata de si una es mas segura que la otra. Ambas van a hacer inseguras si no se hace la peticion usando SSL/TLS (HTTPS).
		
		Se usan para dos cosas muy diferentes, el basic suele usarse para enviar el usuario y contraseña a un endpoint/backend.
		
		El bearer suele usarse cuando la autenticación/autorización es mediante tokens, y suele ser un app/cliente tercero que quiere consumir tus endpoints/backend.

	* **Jhon Bayron  Agudelo Rendon** [477823] (1)

		Muchas gracias claro como el agua 😃

## 0170. Creando los clientes de Spotify y servicios iniciales [15821](https://platzi.com/clases/1439-autenticacion-oauth/15821-creando-los-clientes-de-spotify-y-servicios-inicia/)

### Descripción:


### Links:

* [Authorization Scopes | Spotify for Developers](https://developer.spotify.com/documentation/general/guides/scopes/)

### Comentarios:

* **Roberto Gian Franco Carbonell Saravia** (6) [449314](https://platzi.com/comentario/449314/) 

	Tengo una duda, sé que el ClientId y el Cliente Secret son únicos, supongamos que he creado mi propio backend con sus respectivos servicios, entonces cada vez tengo que generarlos por cada usuario o por aplicación?

	* **glrodasz** [449314] (9)

		Si, es la manera en la que podemos identificar todos los clientes que estan usando nuestra APU. Asi que, si en un futuro tenemos un problema de seguridad podemos implementar un whitelist/blacklist para bloquear clientes maliciososo. Una tecnica tambien cuando los clientes se ven comprometidos es reiniciar/regenerar los client secrets.

* **AlvaroRT** (2) [927779](https://platzi.com/comentario/927779/) 

	Excelente clase.

* **Andrés Mauricio Montoya Sánchez** (2) [648894](https://platzi.com/comentario/648894/) 

	¿Cómo puedo crear mi propio servicio de OAuth 2.0? ¿Auth0 me proveé este servicio o tengo que hacer manualmente?

	* **Diego Alexander Forero Higuera (Platzi)** [648894] (2)

		Auth0 provee el servidor de OAuth2, igual lo puedes implementar pero depende del lenguaje de programación que estés usando.

	* **Jose Vidal** [648894] (3)

		Hola. No es necesario que implementes tu servidor de oauth 2.0, ya que el estándar puede ser muy extenso y en ocasiones complejo. Puedes usar servicios cloud u on-premise que te ayuden para tal fin.
		
		Algunos completamente gratuitos y OpenSource son: Keycloak (Redhat SSO), CAS Server o WS2O Identity Server.
		
		Igualmente existen servicios en la nube como: Azure Active Directory, AWS Single Sign-On.

	* **william andres rodriguez borja** [648894] (2)

		implementar un servidor de oauth no es tan complejo una vez entiendes el estandar oAuth hay muchos ejemplos yo personalmente lo he hecho con java , spring , mongodb

* **arsenio-perez** (1) [726155](https://platzi.com/comentario/726155/) 

	Por más que lo intento, no he podido registrar una cuenta en Spotify. He intentado con mi correo, a través de Facebook, cambiando la contraseña, cambiando el nombre… y no ha sido posible, simplemente la página de registro se mantiene igual sin hacer ninguna otra acción. ¿A alguien más le ha sucedido algo similar? Si alguien sabe cómo se puede solucionar esto, agradezco sus comentarios.

## 0180. Implementando Authorization Code Grant [15823](https://platzi.com/clases/1439-autenticacion-oauth/15823-implementando-authorization-code-grant/)

### Descripción:


El flujo de Authorization Code Grant comienza redireccionando a los usuarios a una pantalla donde pedimos permisos para acceder a su cuenta _(en este caso con Spotify)_ para que, a su vez, la aplicación nos devuelva un código de autorización. Este código de autorización lo vamos a utilizar para enviar junto con las variables de `client_id` y `client-secret` una nueva petición a la API de Spotify. Esta vez, la API nos responde con un token de acceso que podemos utilizar para acceder al contenido que tenemos permitido según la plataforma de Spotify.

### Comentarios:

* **william andres rodriguez borja** (2) [771521](https://platzi.com/comentario/771521/) 

	Que genial clase  
	previamente realice aplicaciones con oauth en base a librerias y tu hiciste manualmente parte de lo que las librerias hacen en java usaba Spring security oauth y la verdad es muy engorrosa. yo voy a facebook obtengo el authorization token obtengo los datos del usuario y luego almacenos sus datos en mi base de datos para el registro y le genero el code y token de mi propio servidor ahora lo voy ha hacer manual y segun veo significara mucho pero mucho menos codigo.

* **JMM** (2) [727098](https://platzi.com/comentario/727098/) 

	Paso un link que me sirvió para terminar de cerrar la idea.
	
	[OauthDocumentacionAuthorizationCode](https://www.oauth.com/oauth2-servers/server-side-apps/authorization-code/)

* **RBN1993** (2) [595433](https://platzi.com/comentario/595433/) 

	¿Qué utilizas al importar los utils en el editor?  
	Veo que filtras y luego coges el path del archivo directamente sin tener que pensar dónde está si no solo sabiendo cómo se llama el archivo a importar.

	* **RBN1993** [595433] (6)

		Me costó pero lo encontre: [Relative path](https://marketplace.visualstudio.com/items?itemName=jakob101.RelativePath)

	* **Julio J Yépez** [595433] (3)

		Jeje … te costó solo una hora! Bien hecho. Gracias por compartir la info.

	* **RBN1993** [595433] (3)

		Por el camino memoricé atajos del vscode XD

* **RBN1993** (2) [59757](https://platzi.com/comentario/595433/) 
¿Qué utilizas al importar los utils en el editor? Veo que filtras y luego coges el path del archivo directamente sin tener que pensar dón...

	* **RBN1993** [59757] (6)

		Me costó pero lo encontre: [Relative path](https://marketplace.visualstudio.com/items?itemName=jakob101.RelativePath)

## 0190. Usando nuestro access token para obtener nuestros recursos [16033](https://platzi.com/clases/1439-autenticacion-oauth/16033-usando-nuestro-access-token-para-obtener-nuestros-/)

### Descripción:


### Comentarios:

* **EmmanuelO** (5) [468399](https://platzi.com/comentario/468399/) 

	Creo que falta una parte, porque no hemos definido la función getUserInfo pero aquí ya aparece de la nada.

	* **Jonathan Jiménez** [468399] (3)

		sí, eso parece, me fijé y en los archivos de la clase anterior ya estaban definidos esos métodos.

	* **glrodasz** [468399] (11)

		Acabo de revisar la grabación y tienes razón. Al parecer se perdio esa parte en la edición.
		
		La funcion **getUserInfo** y **getUserPlaylists** lo que hacen es hacer un llamado a los endpoints de spotify incluyendo el access token en sus headers, verificamos que responder correctamente y estos devuelven una promesa.
		
		**getUserInfo**  
		<https://github.com/glrodasz/platzi-autenticacion/commit/82fdfa4a600a52dbbc1a015859ff00f3aef5c9a9#diff-af83b33641d9badb938fc12d93af2cfdR29>
		
		**getUserPlaylists**  
		<https://github.com/glrodasz/platzi-autenticacion/commit/82fdfa4a600a52dbbc1a015859ff00f3aef5c9a9#diff-af83b33641d9badb938fc12d93af2cfdR51>
		
		Más info:  
		<https://developer.spotify.com/documentation/web-api/reference/users-profile/get-current-users-profile/>  
		<https://developer.spotify.com/documentation/web-api/reference/playlists/get-list-users-playlists/>

* **Fernando Azuaje** (2) [63223](https://platzi.com/comentario/653915/) 
Tengo un problema con el proyecto he hecho todo al pie de la letra pero no me funciona como en el video, ya que la no se me esta almacena...

	* **glrodasz** [63223] (1)

		Hola **azu.ref** , podrias darme un poco más de información sobre que no es lo que funciona, que error o errores estas teniendo. Tambien podrias darme el link de tu repositorio. Si, ejecutas mi repositorio, tienes el mismo problema?

* **AlvaroRT** (1) [928912](https://platzi.com/comentario/928912/) 

	Muy buena explicación

* **Raul Gomez** (1) [747842](https://platzi.com/comentario/747842/) 

	la neta el Authorization Code Grant

* **Ronnie Dave Cañas Pineda** (1) [708083](https://platzi.com/comentario/708083/) 

	Al final me queda el sabor de que en la edición se perdió la parte más importante: getUserInfo, getUserPlaylists… etc  
	Una lástima

	* **william andres rodriguez borja** [708083] (1)

		te recomiendo leer los otros comentarios para ver si alguien ya hizo tu pregunta , el profe la respondio con el codigo que hacia falta.

* **Andrés Mauricio Montoya Sánchez** (1) [660594](https://platzi.com/comentario/660594/) 

	Yo no pago Spotify, asi que no me aparece ninguna 😦

	* **william andres rodriguez borja** [660594] (1)

		no necesitas tener la version premium de spotify con la version gratuita puedes crear playlist.

* **sluis117** (1) [73849](https://platzi.com/comentario/842397/) 
tengo el siguiente error: Missing required parameter: redirect_uri Alguien me podría ayudar?

* **Jonatan Francisco Gonzalez Donis** (1) [69666](https://platzi.com/comentario/761080/) 
Como en una pregunta anterior, por temas de concurrencia el cookie-parser no sobreescribe e cookie?? Cual es la mejor forma de almacenar...

	* **glrodasz** [69666] (1)

		La mejor manera es en memoria o en una cookie segura del lado del servidor. En el curso de Autenticacíon con Passport hacemos una implementación del almacenamiento de la cookie en el backend.

## 0200. Implementando Implicit Grant [15822](https://platzi.com/clases/1439-autenticacion-oauth/15822-implementando-implicit-grant/)

### Descripción:


El flujo de Implicit Grant es muy similar al de Authorization Code Grant, la diferencia principal es que trabajamos de lado del cliente y nos saltamos la parte del código de autorización, en vez de eso, vamos a recibir el token de acceso para realizar peticiones al momento que los usuarios nos dan permiso para acceder a su cuenta de Spotify.

### Comentarios:

* **Antonio Luis Gil Rodríguez** (5) [466933](https://platzi.com/comentario/466933/) 

	En realidad la forma correcta es Random, no Ramdon 😛

* **Andrés Mauricio Montoya Sánchez** (2) [660815](https://platzi.com/comentario/660815/) 

	Les recomiendo actualizar Next.js, ahora es más fácil trabajar con las variables de entorno. <https://github.com/zeit/next.js/tree/canary/examples/with-dotenv>

* **Norman Roa** (2) [587756](https://platzi.com/comentario/587756/) 

	Esa function getHashParams se ve interesante.

* **Héctor Tello** (1) [1068628](https://platzi.com/comentario/1068628/) 

	¿Alguien me podría dar algunos ejemplos de aplicaciones que viven del lado cliente? Gracias.

* **AlvaroRT** (1) [928931](https://platzi.com/comentario/928931/) 

	Apuntado y repasando, repasando, repasando… jejejej

* **Raul Gomez** (1) [752429](https://platzi.com/comentario/752429/) 

	uff esto ahi que digerirlo muy bien

## 0210. Implementando nuestro servicio de autenticación [16034](https://platzi.com/clases/1439-autenticacion-oauth/16034-implementando-nuestro-servicio-de-autenticacion/)

### Descripción:


### Comentarios:

* **Cristian David Franco Garcia** (2) [50172](https://platzi.com/comentario/476748/) 
Buenas tardes, cuando dicen que el access token no debe ser almacenado en localStorage, a que hace referencia almacenarlo en memoria, usa...

	* **glrodasz** [50172] (2)

		Cuando hablamos de almacenarlo en memoria hablados de tenerlo en una variable en JavaScript. Por ejemplo almacenarlo en el store de Redux.
		
		Lo de Redis puede funcionar, pero de cierta manera genera persistencia entonces no creo que sea el camino.
		
		Más info:  
		<https://auth0.com/docs/security/store-tokens>  
		<https://auth0.com/blog/oauth2-implicit-grant-and-spa/>

* **alejo6460** (1) [975427](https://platzi.com/comentario/975427/) 

	Solo se ha hablado de React y Next, como se podria usar con Angular?

	* **jesus-olivares661** [975427] (1)

		Con angular tendrías que programar un render server como intermediario entre la SPA (hecha con angular) y el API…  
		Creo que otra opción sería usar AngularUniversal ya que es equivalente (de angular) al next.js(de react)

	* **jesus-olivares661** [975427] (1)

		Aunque la documentación de Oauth ya no recomienda usar implicit grant para las SPA, ahora recomiendan utilizar autorization code grant con PKCE, igual que para una app nativa <https://oauth.net/2/grant-types/implicit/>

* **Raul Gomez** (1) [755849](https://platzi.com/comentario/755849/) 

	con tiempo y cuidado puedo seguirte Glrodasz, no esta facil

* **Cristian David Franco Garcia** (1) [476748](https://platzi.com/comentario/476748/) 

	Buenas tardes, cuando dicen que el access token no debe ser almacenado en localStorage, a que hace referencia almacenarlo en memoria, usar un servicio como Redis?

	* **glrodasz** [476748] (2)

		Cuando hablamos de almacenarlo en memoria hablados de tenerlo en una variable en JavaScript. Por ejemplo almacenarlo en el store de Redux.
		
		Lo de Redis puede funcionar, pero de cierta manera genera persistencia entonces no creo que sea el camino.
		
		Más info:  
		<https://auth0.com/docs/security/store-tokens>  
		<https://auth0.com/blog/oauth2-implicit-grant-and-spa/>

	* **Jhon Bayron  Agudelo Rendon** [476748] (2)

		Pero nace la duda en el archivo Auth.js en el repositorio de ejemplo veo que este guarda el acces_token en el localStorage creo que es para persistir la sesion, entoces bajo que condiciones se usa el locaStorage cuales no?

	* **glrodasz** [476748] (4)

		La unica razón para hacerlo es si es una app privada o de ejemplo como es nuestro caso. Te recomiendo estos dos links:
		
		<https://auth0.com/docs/security/store-tokens>  
		<https://auth0.com/blog/oauth2-implicit-grant-and-spa/>
		
		**Nota:** Muchos textos y tutoriales solian recomendar el almacenamiento del token en el localStorage, pero debimo a las implicaciones de seguridad y/o nuevas vunerabilidades ya no se recomienda más.

## 0220. Modificando nuestro Layout [16035](https://platzi.com/clases/1439-autenticacion-oauth/16035-modificando-nuestro-layout/)

### Descripción:


### Comentarios:

* **danny_chambi** (3) [49252](https://platzi.com/comentario/464769/) 
¿Es recomendable guardar texto plano en local storage?

	* **glrodasz** [49252] (1)

		Dependiendo el contenido del texto y su funcionalidad. Puedes contarme cual es la intención?

* **Luis Fernando Díaz Devos** (1) [1099632](https://platzi.com/comentario/1099632/) 

	Quedan muchas dudas, párese mas una clase de programación de NODE, se perdió la esencia de lo que es la AUTH, y si ahora es C++ o python, creo que no voy a tener muchas librerías

* **jesus-olivares661** (1) [1063497](https://platzi.com/comentario/1063497/) 

	En ningun lado del curso hablas de como se debe implementar este flujo en el backend… Ni das informacion detallada de como es eso en el backend… Simplemente estas usando el api de spotify y ya ellos tienen todos esos flujos en su backend listos.

* **alejo6460** (1) [975610](https://platzi.com/comentario/975610/) 

	Como puedo implementar todo esto en Angular 8 y usando Typescript?

	* **jesus-olivares661** [975610] (1)

		Te respondí en el video anterior. Pero creo que este video te ayudará un poco a entender mejor las cosas <https://platzi.com/clases/1649-passport/21983-arquitectura-del-proyecto-platzi-video/>  
		Posdata: lo que me gusta de este profesor es como deja el código fuente, de resto no le entiendo nada (primera vez q me pasa esto en platzi). Entiendo mas el código fuente q lo que el explica, tengo q estar googleando mucho

* **chepix10** (1) [673884](https://platzi.com/comentario/673884/) 

	Hola a todos.  
	Este curso está increíble. Les dejo unos commits que realicé en mi repo ya que actualicé next y react a su última versión y no me corría correctamente la implementación de Implicit Grant. Espero les sea de utilidad:  
	[Nombre del modulo AppLayout (más por que se llame igual que el archivo)](https://github.com/chepix10/platzi-spotify/commit/2dc681243a8693a4029d10eb7d6bad98bb483cf5)  
	[AppNavbar convertido en clase de JS](https://github.com/chepix10/platzi-spotify/commit/b71a9d482da850764260e3ac9fbd4e9469838c13)

* **danny_chambi** (1) [464769](https://platzi.com/comentario/464769/) 

	¿Es recomendable guardar texto plano en local storage?

	* **glrodasz** [464769] (1)

		Dependiendo el contenido del texto y su funcionalidad. Puedes contarme cual es la intención?

	* **Javier Batres** [464769] (1)

		La respuesta corta es **NO**. Depende de muchas cosas que datos son y demás pero la verdad es algo que debes evitar a toda costa, ante todo por que se te hace costumbre…

	* **glrodasz** [464769] (2)

		Bueo, yo de nuevo digo que **depende**. Si vas a guardar información sensible, definitivamente no. Pero si es un valor de referencia, algo que es publico, y que no interfiere, o no se presta como un punto para obtener inforamación sensible esta bien usarlo. Por eso te pregunto, que es lo que pretendes hacer para darte una respueta mas acetada.

## 0230. Implementando Client Credentials Grant [15825](https://platzi.com/clases/1439-autenticacion-oauth/15825-implementando-client-credentials-grant/)

### Descripción:


### Comentarios:

* **Antonio Luis Gil Rodríguez** (3) [49414](https://platzi.com/comentario/467035/) 
Una duda que tengo de concepto… ¿Autorización con OAuth 2.0 no tiene nada que ver con la Autorización de ACL? ¿Solo es autorización para ...

	* **Diego Alexander Forero Higuera (Platzi)** [49414] (3)

		OAuth 2.0 permite hacer login usando el sistema de login de un tercero por medio de un token, un ACL lo que define es una lista de control de acceso sobre recursos, es como los permisos que tiene un determinado usuario sobre la plataforma, por ejemplo un usuario se autentica y es estudiante puede ver las clases y comentar, pero otro usuario se autentica y es profesor este tiene permisos adicionales para modificar el titulo de la clase o borrar comentarios de otros usuarios.

* **jesus-olivares661** (1) [1063542](https://platzi.com/comentario/1063542/) 

	desde el backend debería validad si la petición viene desde el dominio que pertenece a esas credenciales…?

* **jesus-olivares661** (1) [1063526](https://platzi.com/comentario/1063526/) 

	Platzi siempre dice que nos ahorra tiempo pero por lo veo en este curso igual tengo que seguir leyendo por todos las oauth porque no me esta ayudando para nada en el flujo de mi backend… Tienes al menos un enlace donde recomienden donde puedo buscar estandares de como manejar mis api keys, scopes, clientes y todo eso en la base de datos?

* **Antonio Luis Gil Rodríguez** (1) [467035](https://platzi.com/comentario/467035/) 

	Una duda que tengo de concepto… ¿Autorización con OAuth 2.0 no tiene nada que ver con la Autorización de ACL? ¿Solo es autorización para servicios de terceros?

	* **Diego Alexander Forero Higuera (Platzi)** [467035] (3)

		OAuth 2.0 permite hacer login usando el sistema de login de un tercero por medio de un token, un ACL lo que define es una lista de control de acceso sobre recursos, es como los permisos que tiene un determinado usuario sobre la plataforma, por ejemplo un usuario se autentica y es estudiante puede ver las clases y comentar, pero otro usuario se autentica y es profesor este tiene permisos adicionales para modificar el titulo de la clase o borrar comentarios de otros usuarios.

## 0240. Implementando Resource Owner Password Grant [15824](https://platzi.com/clases/1439-autenticacion-oauth/15824-implementando-resource-owner-password-grant/)

### Descripción:


Aplicaciones altamente confiables pueden usar este flujo, ya que en este flujo se le pregunta al usuario final llenar sus credenciales (usuario/contraseña) con un formulario interactivo y luego la información es enviada al authorization server.

Usa este flujo **solo** si lo siguiente aplica:

* Se le puede confiar absolutamente a la aplicación las credenciales del usuario. Para aplicaciones del lado del cliente o aplicaciones mobile se recomienda usar otros flujos.
* Un flujo basado en redireccionamiento no es posible debido a que es una apliación legada. Si el redireccionamiento es posible se recomienda usar mejor **Authorization Code Grant**.



## Conociendo el flujo

La definición de Resource Owner Password Grant puede ser encontrada en <https://tools.ietf.org/html/rfc6749#section-4.3>.

  1. El usuario final ingresa sus credenciales en la aplicación (cliente) mediante un formulario.
  2. La aplicación envía las credenciales al **Authorization Server**.
  3. El **Authorization Server** valida las credenciales y devuelve un **Access Token**.
  4. La aplicacion ahora puede usar el **Access Token** para llamar la API en nombre del usuario.



## Detalles de implementación

Para su implementación se debe implementar de parte de la aplicación un formulario que tome las credenciales del usuario y luego pueda hacer una petición al Authorization Server. Es sumamente importante que esto suceda en una conexión segura HTTPS.

  1. La aplicación obtiene las credenciales desde el formulario.
  2. La aplicación hace una petición al **Authorization Server**.


``` 
    const request = require("request");
    
    const options = {
      method: "POST",
      url: "https://<authorization-server>/oauth/token",
      headers: { "content-type": "application/json" },
      body: {
        grant_type: "password",
        username: "<username>",
        password: "<password>",
        audience: "<your-audience>",
        scope: "<your-scopes>",
        client_id: "<your-client-id>",
        client_secret: "<your-client-secret>"
      },
      json: true
    };
    
    request(options, function(error, response, body) {
      if (error) {
        throw new Error(error);
      }
      console.log(body);
    });
    
```

  3. La respuesta tiene un **JSON Web Token** , generalmente de tipo `Bearer` incluyendo el tiempo de expiración.


``` 
    {
      "access_token": "eyJz93a...k4laUWw",
      "token_type": "Bearer",
      "expires_in": 36000
    }
    
```

  4. La aplicación ya puede usar el **JSON Web Token** para hacer peticiones a los recursos del usuario (API) en nombre de él.


``` 
    const request = require("request");
    
    const options = {
      method: "GET",
      url: "https://someapi.com/api",
      headers: {
        authorization: "Bearer <access-token>",
        "content-type": "application/json"
      }
    };
    
    request(options, function(error, response, body) {
      if (error) throw new Error(error);
    
      console.log(body);
    });
    
```

Con esto tenemos los conocimientos necesarios para poder implementar este flujo. Recuerda seguir las recomendaciones para darle un uso adecuado.

### Comentarios:

## 0250. Implementando Authorization Code Grant (PKCE) [15826](https://platzi.com/clases/1439-autenticacion-oauth/15826-implementando-authorization-code-grant-pkce/)

### Descripción:


 **Authorization Code Grant** tiene algunos problemas de seguridad cuando se implementa en aplicaciones nativas. Por ejemplo un atacante malicioso puede interceptar el `authorization_code` retornado por el **Authorization Server** y usarlo para obtener un **Access Token**.

La **Proof Key for Code Exchange (PKCE)** definida en <https://tools.ietf.org/html/rfc7636> es una técnica usada para mitigar la intercepción del `authorization_code`.

Con **PKCE** la aplicacion crea, por cada petición de autorización una llave criptográfica aleatoria llamada `code_verifier` y su valor transformado llamado `code_challenge` el cual es enviado al **Authorizacion Server** para obtener un `authorization_code` y posteriormente enviarlo junto con el `code_verifier` para obtener un **Access Token**.

## Conociendo el flujo

  1. La aplicación nativa inicia el flujo y redirecciona al usuario al **Authorization Server** enviando los parámetros `code_challenge` y `code_challenge_method`.
  2. El **Authorization Server** redirecciona el usuario a la aplicación nativa con un `authorization_code` en el query string.
  3. La aplicación nativa envía el `authorization_code` y el `code_verifier` junto con a la url de redireccionamiento (`redirect_uri`) y el `client_id` al **Authorization Server**.
  4. El **Authorization Server* valida la información y retorna un **Access Token**.
  5. La aplicación nativa ahora puede usar el **Access Token** para llamar los recursos en nombre del usuario (API).



## Detalles de implementación

Vamos a ver los detalles de implementación usando **JavaScript/Node.js** ya que son operaciones y request básicos que puede implementar cualquier lenguaje nativo. Para ver más detalles de una implementación especifica en lenguajes como **Java** o **Swift** pueden consultar una guía [aquí](https://auth0.com/docs/api-auth/tutorials/authorization-code-grant-pkce#optional-customize-the-tokens).

  1. Necesitamos generar y almacenar un `code_verifier`.


``` 
    function base64URLEncode(str) {
      return str
        .toString("base64")
        .replace(/\+/g, "-")
        .replace(/\//g, "_")
        .replace(/=/g, "");
    }
    const verifier = base64URLEncode(crypto.randomBytes(32));
    
```

  2. Mediante el `code_verifier` generamos un `code_challenge` que sera enviando en el llamado de autorización.


``` 
    function sha256(buffer) {
      return crypto
        .createHash("sha256")
        .update(buffer)
        .digest();
    }
    const challenge = base64URLEncode(sha256(verifier));
    
```

  3. Para comenzar el **Authorization Code Grant (PKCE)** nuestra aplicación nativa deberá enviar primero el usuario a la url de autorización incluyendo el `code_challenge` y el método usado para su generación y así obtener el `authorization_code`.


``` 
    https://<authorization-server>/authorize?
        audience=<your-audience>&
        scope=<your-scopes>&
        response_type=code&
        client_id=<your-cient-id>&
        code_challenge=<code-challenge>&
        code_challenge_method=S256&
        redirect_uri=<your-redirect-uri>
    
```

  4. Ahora que nuestra aplicación tiene el `authorization_code` lo debemos cambiar por un **Access Token** que puede ser usado para hacer llamados a los recursos del usuario. Para ello obtenemos el `authorization_code` (`code`) de nuestro paso anterior y hacemos un llamado tipo `POST` al endpoint de obtención de token enviando también el `code_verifier`.


``` 
    const request = require("request");
    
    const options = {
      method: "POST",
      url: "https://<authorization-server>/oauth/token",
      headers: { "content-type": "application/json" },
      body:
        '{"grant_type":"authorization_code","client_id": "<your-client-id>","code_verifier": "<your-code-verifier>","code": "<your-authorization-code>","redirect_uri": "<your-redirect-uri>"}'
    };
    
    request(options, function(error, response, body) {
      if (error) throw new Error(error);
    
      console.log(body);
    });
    
```

La respuesta tiene un **JSON Web Token** , generalmente de tipo `Bearer`:
``` 
    {
      "access_token": "eyJz93a...k4laUWw",
      "token_type": "Bearer"
    }
    
```

  5. Ya teniendo nuestro **Access Token** podemos hacer llamados a los recursos del usuario (API) en nombre de él.


``` 
    const request = require("request");
    
    const options = {
      method: "GET",
      url: "https://someapi.com/api",
      headers: {
        authorization: "Bearer <access-token>",
        "content-type": "application/json"
      }
    };
    
    request(options, function(error, response, body) {
      if (error) throw new Error(error);
    
      console.log(body);
    });
    
```

Con esto tenemos los conocimientos necesarios para poder implementar este flujo. Recuerda seguir las recomendaciones para darle un uso adecuado.

### Comentarios:

* **chepix10** (1) [673980](https://platzi.com/comentario/673980/) 

	Por lo que entiendo de este flujo, siempre será preferido sobre el Authorization Code Grant tradicional.
	
	¿Existe algún caso en donde no sea así?

# Open ID Connect [3109]

## 0260. ¿Qué es OpenID Connect [15827](https://platzi.com/clases/1439-autenticacion-oauth/15827-que-es-openid-connect/)

### Descripción:


Al utilizar OAuth 2.0 corremos muchos peligros, por ejemplo, la posibilidad de utilizar el access_token para hacernos pasar por el usuario y consumir un endpoint con toda la información de nuestros usuarios.

Open ID Connect es una capa de autenticación basada en OAuth 2.0, es un estándar que nos permite utilizar los mecanismos adecuados para verificar la identidad de nuestros usuarios. Para esto, Open ID Connect implementa los flujos de autenticación de _Authorization Code Grant_ e _Implicit Grant_ con algunas diferencias, por ejemplo, además de obtener el access_token para hacer llamados a la API, vamos a obtener un nuevo token llamado id_token que entrega información muy básica de los usuarios y nos permite verificar si están autenticados.

### Links:

* [Final: OpenID Connect Core 1.0 incorporating errata set 1](https://openid.net/specs/openid-connect-core-1_0.html#StandardClaims)

* [Final: OpenID Connect Core 1.0 incorporating errata set 1](https://openid.net/specs/openid-connect-core-1_0.html#ScopeClaims)

### Comentarios:

* **Juan David Castro (Platzi)** (6) [445257](https://platzi.com/comentario/445257/) 

	Notas de la clase:
	
	* Mientras OAuth trabaja con la autorización _(los permisos)_ , Open ID Connect trabaja con la autenticación _(conocer/revelar las identidades)_ 👍
	* Con OAuth 2.0 solito corremos el riesgo de que alguien intercepte el token de acceso y consuma la información de nuestros usuarios 😱😰
	* Facebook tuvo este tipo de problemas 😱🔥💣
	* Este lío hizo que cada servicio implementara sus propios mecanismos de seguridad 🆗👷
	* ¡Pero! Nace Open ID Connect, un estándar de los mecanismos adecuados para utilizar OAuth en la capa de autorización 🎉👌
	* Open ID Connect implementa los flujos de autenticación que estudiamos en clases anteriores: el Authorization Code Grant y el Implicit Grant 👍
	* La diferencia es que, además de necesitar el token de acceso, vamos a necesitar un nuevo JWT que se llama id_token con información básica de los usuarios que nos permitirá saber si están autenticados 😮
	
	

	* **c3tuxpo2018** [445257] (1)

		Muy Buen resumen

* **medmkt** (2) [48860](https://platzi.com/comentario/459838/) 
Hola que tal me ayudaria mucho me pudieran ayudar con informacion para poder autenticar/autorizar 2 aplicaciones web de distintos dominio...

	* **glrodasz** [48860] (2)

		Hola @medmkt tienes algun ejemplo más concreto de lo que quieres lograr? Si terminas este curso deberia ser suficiente para implementar lo que necesitas.

* **medmkt** (1) [459838](https://platzi.com/comentario/459838/) 

	Hola que tal me ayudaria mucho me pudieran ayudar con informacion para poder autenticar/autorizar 2 aplicaciones web de distintos dominios en un mismo web api (login), es decir, un login para ambas aplicaciones como por ejemplo lo que hace google con sus multiples servicios, gmail, youtube, g+ etc. Necesito la teoria basica para poder entender bien como funciona esta arquitectura en primera instancia. Si existe algun enlace o tutorial que me puedan pasar que crean que es util para alguien con poca experiencia en este tema se los agradeceria mucho.

	* **glrodasz** [459838] (2)

		Hola @medmkt tienes algun ejemplo más concreto de lo que quieres lograr? Si terminas este curso deberia ser suficiente para implementar lo que necesitas.

* **briangilbert** (1) [69124](https://platzi.com/comentario/751725/) 
Hola, me piden un metadataAddress. Entiendo que es una URL que genera un JSON indicando cual es el endpoint de autorización, cual de toke...

## 0270. Implementando OpenID Connect [15829](https://platzi.com/clases/1439-autenticacion-oauth/15829-implementando-openid-connect/)

### Descripción:


### Links:

* [OpenID Connect  |  Google Identity Platform
       |  Google Developers](https://developers.google.com/identity/protocols/OpenIDConnect)

* [Google Sign-In for Websites   |  Google Developers](https://developers.google.com/identity/sign-in/web/)

* [GitHub - googleapis/google-api-nodejs-client: Google's officially supported Node.js client library for accessing Google APIs. Support for authorization and authentication with OAuth 2.0, API Keys and JWT (Service Tokens) is included.](https://github.com/googleapis/google-api-nodejs-client)

* [GitHub - panva/node-openid-client: A Relying Party(RP) implementation for node.js servers. Wide feature coverage including optional specifications and passport strategy is included.](https://github.com/panva/node-openid-client)

### Comentarios:

* **juanVFletes** (6) [495939](https://platzi.com/comentario/495939/) 

	La diferencia entre OpenID y OpenID Connect es que:
	
	* Open ID: Da una manera de verificar la identidad del usuario, o sea solo sirve como protocolo de autenticación.
	
	* Open ID Connect: Trabaja como extensión de OAuth 2.0 y además de solo servir como protocolo de autenticación, provee un JWT con detalles del usuario.
	
	
	

* **Madrov** (2) [52428](https://platzi.com/comentario/505054/) 
Node es un lenguaje 3:15?

	* **AlexGarrixen** [52428] (2)

		Hola,NODE es un entorno de ejecucion que me perimitira desarrollar en javascipt del lado del servidor.

* **jesus-olivares661** (1) [1066489](https://platzi.com/comentario/1066489/) 

	de donde salió ese objeto llamado **gapi** …?

* **juand_silva** (1) [678126](https://platzi.com/comentario/678126/) 

	Nota mental, limpiar cookies y ver el total del video xD antes de estancarme en un error.

* **Madrov** (1) [505054](https://platzi.com/comentario/505054/) 

	Node es un lenguaje 3:15?

	* **AlexGarrixen** [505054] (2)

		Hola,NODE es un entorno de ejecucion que me perimitira desarrollar en javascipt del lado del servidor.

# Preocupaciones con JWT y OAuth 2.0 [3110]

## 0280. ¿Cuáles son las preocupaciones con JWT [15828](https://platzi.com/clases/1439-autenticacion-oauth/15828-cuales-son-las-preocupaciones-con-jwt/)

### Descripción:


Cuando guardamos nuestros JWT en el localStorage del navegador, somos vulnerables a ataques de _Cross Site Scripting (XSS)_.

En realidad, debemos tratar estos tokens como si fueran datos de la tarjeta de crédito de nuestros usuarios, **nunca deberíamos almacenarlos en ninguna parte** , más bien, podemos almacenarlos en memoria (mejor aún si tenemos la posibilidad de utilizar al backend y podemos implementar el flujo de _Authorization Code Grant_ para conservar los datos en la memoria del servidor).

También existen varias alternativas basadas en JWT como JWS, JWE y JOSE, sin embargo, ninguna de ellas es la respuesta definitiva a todos los problemas de seguridad en nuestras aplicaciones, nuestro trabajo NO es asegurarnos de que nuestra tecnología sea la más poderosa, más bien, debemos trabajar con el mejor conjunto de buenas practicas con buenas tecnologías.

El desafio de esta clase es describir las diferencias entre OAuth 1.0 y OAuth 2.0 en la sección de comentarios.

### Links:

* [Cross-Site Request Forgery (CSRF) - OWASP](https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF))

* [Cross-site Scripting (XSS) - OWASP](https://www.owasp.org/index.php/Cross-Site_Scripting_(XSS))

### Comentarios:

* **Héctor Tello** (2) [1073636](https://platzi.com/comentario/1073636/) 

	Encontré qué tiene OAuth 2.0 que OAuth 1.0 no:
	
	* Ya no requiere de cliente de las aplicaciones de la criptografía.
	
	* Sus firmas son mucho menos complicadas.
	
	* Sus token de acceso son de “corta duración”.
	
	
	

* **Mario Ramirez** (2) [779246](https://platzi.com/comentario/779246/) 

	Auth 2.0  
	Es un protocolo que define las reglas para acceder a otro servidor  
	Auth 1.0  
	Permite la autorización a las aplicaciones pero de un mono mas estándar

* **jesus-ruvalcaba-miranda** (2) [600164](https://platzi.com/comentario/600164/) 

	en el caso que comenta sobre la utilización de redux para almacenar los tokens en memoria, como generarias persistencia sin ponerlo en el localstorage

	* **glrodasz** [600164] (2)

		Hay varias formas/estrategias de hacer esto. 1) Lo que puedes hacer es tener una acción que compruebe que el usuario este logueado antes de llamar el resto de acciones. Esto con el fin de que si alguien entra a alguna vista generando un request en el servidor tu puedas primero hacer el re-login. Para eso necesitarias posiblemente un mecanismo de refresh tokens o silent auth.
		
		La otra opción es usar cookies de manera segura, tendrias que hacer un puente entre tu SPA y un servidor exclusivo para esto, si estas haciendo SSR podrias usar este mismo servidor.
		
		Informacón adicional: <https://auth0.com/blog/oauth2-implicit-grant-and-spa/>

* **jesus-ruvalcaba-miranda** (2) [60062](https://platzi.com/comentario/600164/) 
en el caso que comenta sobre la utilización de redux para almacenar los tokens en memoria, como generarias persistencia sin ponerlo en el...

	* **glrodasz** [60062] (2)

		Hay varias formas/estrategias de hacer esto. 1) Lo que puedes hacer es tener una acción que compruebe que el usuario este logueado antes de llamar el resto de acciones. Esto con el fin de que si alguien entra a alguna vista generando un request en el servidor tu puedas primero hacer el re-login. Para eso necesitarias posiblemente un mecanismo de refresh tokens o silent auth.
		
		La otra opción es usar cookies de manera segura, tendrias que hacer un puente entre tu SPA y un servidor exclusivo para esto, si estas haciendo SSR podrias usar este mismo servidor.
		
		Informacón adicional: <https://auth0.com/blog/oauth2-implicit-grant-and-spa/>

* **dev.team** (2) [47831](https://platzi.com/comentario/447627/) 
no me queda claro como enviando el atributo state en la petición se puede evitar CSFR, es decir que hace el backend con esa cadena que en...

	* **glrodasz** [47831] (1)

		La petición de authenticacion solo puede ser generada nuestra aplicacion, ya que desde el cliente es el usuario quien genuinamente acepta otorgar los permisos y en esa misma peticion enviamos nuestro state. De igual manera se aplica el concepto en Authorization Code Grant, cuando es el backend quien genera el state.
		
		Lo que queremos hacer es evitar que alguien nos envie una peticion a nuestra URL callback de nuestro cliente de manera falsa, ya que solo nosotros sabemos cual state generamos.
		
		Aquí hay dos explicaciones basicas de como funciona el concepto:  
		<https://auth0.com/docs/protocols/oauth2/oauth-state#how-to-use-the-parameter-against-csrf-attacks>  
		<https://librosweb.es/libro/django_1_0/capitulo_14/proteccion_contra_csrf.html#un_ejemplo_mas_complejo_de_csrf>

* **jesus-olivares661** (1) [1066439](https://platzi.com/comentario/1066439/) 

	Tengo un api administrativo (donde gestiono el contenido de la pagina, usuarios, ect) y uno publico (donde los usuarios hacen sus publicaciones y ven contenido de otros usuarios), Ambas son SPA…  
	Como hago para evitar que una persona agarre el token del panel administrativo y lo use desde la otra aplicacion que es solo para realizar publicaciones y ver contenido (y por ejemplo modifiquen el nombre de una categoría desde la aplicación que no es)…?

* **alejandrocepeda** (1) [936001](https://platzi.com/comentario/936001/) 

	Si guardo en memoria el token, de igual forma con las developer tools de chrome puede ver ese header que se esta enviando

* **AlvaroRT** (1) [930115](https://platzi.com/comentario/930115/) 

	Excelente clase.

* **c3tuxpo2018** (1) [819930](https://platzi.com/comentario/819930/) 

	Me volvió el alma al cuerpo al explicar que los Bancos estan protegidos contra ese tipo de ataque que es solo un ejemplo

* **juand_silva** (1) [678141](https://platzi.com/comentario/678141/) 

	<https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies>  
	Aqui pueden encontrar información de los flags para proteger las cookies.

* **Juan Pablo Cano Buitrago** (1) [653522](https://platzi.com/comentario/653522/) 

	Tengo un backend en Django REST Framework y un front en Angular 8, Cual de todos los flujos de OAuth debería iplementar?

	* **glrodasz** [653522] (2)

		Puedes implementar Implicit Grant, o implementar Authorization Code Grant, pero necesitarias un servidor proxy o de SSR para usar este ultimo.

	* **Juan Pablo Cano Buitrago** [653522] (0)

		Implicit Grant lo implemento en Angular o en Django

* **dev.team** (1) [447627](https://platzi.com/comentario/447627/) 

	no me queda claro como enviando el atributo state en la petición se puede evitar CSFR, es decir que hace el backend con esa cadena que enviamos y como el tiene conocimiento de que la cadena fue creada por nosotros? de antemano gracias!

	* **glrodasz** [447627] (1)

		La petición de authenticacion solo puede ser generada nuestra aplicacion, ya que desde el cliente es el usuario quien genuinamente acepta otorgar los permisos y en esa misma peticion enviamos nuestro state. De igual manera se aplica el concepto en Authorization Code Grant, cuando es el backend quien genera el state.
		
		Lo que queremos hacer es evitar que alguien nos envie una peticion a nuestra URL callback de nuestro cliente de manera falsa, ya que solo nosotros sabemos cual state generamos.
		
		Aquí hay dos explicaciones basicas de como funciona el concepto:  
		<https://auth0.com/docs/protocols/oauth2/oauth-state#how-to-use-the-parameter-against-csrf-attacks>  
		<https://librosweb.es/libro/django_1_0/capitulo_14/proteccion_contra_csrf.html#un_ejemplo_mas_complejo_de_csrf>

## 0290. ¿Cuáles son las preocupaciones con OAuth 2.0 [15830](https://platzi.com/clases/1439-autenticacion-oauth/15830-cuales-son-las-preocupaciones-con-oauth-20/)

### Descripción:


OAuth 2.0 ha sido cuestionado y criticado en diferentes ocasiones, por lo que vamos a explorar algunas de ellas.

## OAuth no es un protocolo en sí

Cuando nos referimos a un protocolo hablamos de que su implementación es lo suficientemente estricta para que no existan variaciones y/o confusiones a la hora de la implementación.

Debido a la gran adoptación temprana que tuvo OAuth, muchas compañías empezaron a contribuir y agregar sus propias versiones de la implementación. Por eso, es que en la definición no es altamente estricta y se habla de muchas variantes en su implementación convirtiendo OAuth **en un framework para crear protocolos** en vez de un protocolo en sí.

El problema con esto es que deja muy al aire y a la opinión de cada uno cual es la mejor forma de implementar OAuth de manera segura y correcta.

La recomendación es no solo leer la especificación si no ademas leer sobre otras implementaciones y los consejos de otras compañías para asegurar una buena implementacion de la misma.

## Bearer tokens

Un Bearer token es un token con la característica de que cualquier entidad con la posesión del token puede usarlo a su gusto y no se requiere prueba de su posesión para este uso.

El problema con esto es que el token en si tiene todas las autorizaciones que han sido diseñadas para el cliente quien lo concedió, pero eso no implica que otro cliente pueda tomar ese token y usarlo.

Idealmente no solo enviar el token si no una prueba de la posesión del mismo pero la realidad es que esto nunca se incluyo en la especificación por lo que las recomendaciones son siempre hacer el uso y envío de tokens en conexiones seguras SSL y tener mucho cuidado con el almacenamiento de los mismos.

Mi recomendación general es que si quieren reforzar sus conocimientos en OAuth leanse la especificación y investiguen un poco mas allá en documentaciones como la de Auth0: <https://auth0.com/docs/protocols/oauth2>

### Comentarios:

* **c3tuxpo2018** (2) [654941](https://platzi.com/comentario/654941/) 

	Me gustaría que miraran este [video](https://www.youtube.com/watch?v=zaLvND1qgww) de Chema Alonso sobre OAuth y es preocupante lo que plantea  
	Después de ver el vídeo mi pregunta es ¿podemos desde el desarrollo evitar el robo de tokens??

	* **glrodasz** [654941] (3)

		Lo que podemos hacer es asegurarnos que tengan un tiempo de expiración muy corto y almacenarlos en una lugar seguro como una Cookie con el flag httpOnly. Tambien, podemos no usar Implicit Grant, y hacer un manejo de sesion en ese caso.

	* **glrodasz** [654941] (3)

		Despues de ver el video, realmente no es un problema de seguridad de tokens, es un problema de fishing/pishing. En este caso esta haciendo uso de ingenieria social para darle permiso a una aplicacion tercera a que acceda a su información.
		
		Por eso, es importante leer el modal de autorización, creo que en este caso, Microsoft esta teniendo un mal diseño y confunde al usuario.

# Haciendo uso de Auth0 [3111]

## 0300. ¿Qué es Auth0 [15832](https://platzi.com/clases/1439-autenticacion-oauth/15832-que-es-auth0/)

### Descripción:


Auth0 es un servicio que nos provee todo el mecanismo para administrar la autorización y la autenticación de nuestras plataformas, nos permite proteger a nuestras aplicaciones con las mejores prácticas de seguridad sin necesidad de ser expertos.

### Links:

* [Never Compromise on Identity. - Auth0](https://auth0.com)

* [Pricing - Auth0](https://auth0.com/pricing)

* [Sign In with Auth0](http://manage.auth0.com)

* [Architecture Scenarios](https://auth0.com/docs/architecture-scenarios)

### Comentarios:

* **Antonio Luis Gil Rodríguez** (3) [49450](https://platzi.com/comentario/467492/) 
Entonces… ¿Auth0 te ayuda a implementar todo lo que has explicado en videos anteriores?

	* **glrodasz** [49450] (2)

		Si, Auth0 como servicio implementa todos los flujos de OAuth 2.0 ademas de otros servicios extra. Si bajas en la tabla comparativa de la pagina de pricing: <https://auth0.com/pricing> podras tener una idea general de los features que puedes usar.

* **jcalderon.sys** (2) [70404](https://platzi.com/comentario/774548/) 
Cual seria la diferencia entre Auth0 y Keycloak?

	* **glrodasz** [70404] (2)

		Aparentemente Keycloak es Open Source y no es un servicio como Auth0. Esto quiere decir que tu eres el encargado del mantenimiento y actualización de Keycloak cuando lo implementas.

* **c3tuxpo2018** (1) [819984](https://platzi.com/comentario/819984/) 

	Dejeme ver si entendí. con el servicio auth0 le traslado el riesgo de las autenticaciones y autorizaciones a la empresa y nos encargamos de que nuestra aplicación haga su trabajo sin ya preocuparnos por la autenticación y autorización?

	* **ANGEL EFRAIN ORDOÑEZ GONZALEZ** [819984] (1)

		Así es. Auth0 implementa los flujos de OAuth 2.0 y otros servicios extra, además se encargan de la seguridad del login y retornan un token con que se valida que el usuario esta logueado y puede ver el contenido.

* **Josua Guaramato** (1) [600307](https://platzi.com/comentario/600307/) 

	Cuales serian las principales diferencias entre Firebase Auth y Auth0??

* **Antonio Luis Gil Rodríguez** (1) [467492](https://platzi.com/comentario/467492/) 

	Entonces… ¿Auth0 te ayuda a implementar todo lo que has explicado en videos anteriores?

	* **glrodasz** [467492] (2)

		Si, Auth0 como servicio implementa todos los flujos de OAuth 2.0 ademas de otros servicios extra. Si bajas en la tabla comparativa de la pagina de pricing: <https://auth0.com/pricing> podras tener una idea general de los features que puedes usar.

	* **Diego Alexander Forero Higuera (Platzi)** [467492] (2)

		Mas que ayudar a implementar es el manejo de autorización y administración de usuarios para tu aplicación, ellos se encargan de toda la seguridad del login y retornan un token con el cual validas que el usuario esta logueado y puede ver el contenido.

## 0310. Auth0 Lock y auth0.js [15831](https://platzi.com/clases/1439-autenticacion-oauth/15831-auth0-lock-y-auth0js/)

### Descripción:


Auth0 Lock es una interfaz gráfica personalizable que nos permite implementar el login y registro de usuarios a nuestra aplicación, sin embargo, si queremos administrar mucho mejor la autenticación de nuestros usuarios, podemos utilizar Auth0 Lock junto con el script de auth0-js.

### Links:

* [GitHub - auth0/lock: Auth0's signin solution](https://github.com/auth0/lock)

* [GitHub - auth0/auth0.js: Auth0 headless browser sdk](https://github.com/auth0/auth0.js)

* [GitHub - auth0/auth0.js: Auth0 headless browser sdk](https://github.com/auth0/auth0.js)

* [Using Lock With auth0.js](https://auth0.com/docs/libraries/lock/v11/auth0js)

* [Lock - Auth0](https://auth0.com/lock)

### Comentarios:

* **Andrés Mauricio Montoya Sánchez** (1) [661095](https://platzi.com/comentario/661095/) 

	Tengo una pequeña duda, ya que mencionan que auth0 permite global hosted… Esto quiere decir que si tengo mi global atenticación en:
	
	<https://company.auth.com/>
	
	Me logueo en esta, eso quiere decir que en otros diferentes dominios funcionará esa autenticación? Quiero decir, si me loguee ahí y tengo otro sitio como <https://second-company.com>, el logueo de [company.auth.com](http://company.auth.com) servirá en second-company? (No sé si me hice entender).

## 0320. Universal Login [15834](https://platzi.com/clases/1439-autenticacion-oauth/15834-universal-login/)

### Descripción:


El Universal Login con Auth0 nos permite autenticar a nuestros usuarios con los widgets de Auth0 Lock desde un alojamiento de Auth0 para obtener mayor seguridad. Entre sus ventajas, podemos resaltar el _Single Sign On_ , autenticación una sola vez para utilizar multiples cuentas y plataformas. Este tipo de servicios los hemos utilizado anteriormente cuando administramos nuestras cuentas de Google, a pesar de utilizar diferentes servicios _(Gmail, Youtube, entre otras)_ , solo debemos hacer login una vez gracias a Google Accounts.

### Links:

* [Universal Login - SSO between multiple apps - Auth0](https://auth0.com/universal-login)

* [SPA + API](https://auth0.com/docs/architecture-scenarios/spa-api)

* [GitHub - glrodasz/platzi-autenticacion at universal-login](https://github.com/glrodasz/platzi-autenticacion/tree/universal-login)

### Comentarios:

* **Miguel Herreros Cejas** (4) [478043](https://platzi.com/comentario/478043/) 

	Os dejo enlaces para la implementación con Vue.js - Axios - Auth0 - Django 2.0
	
	<https://auth0.com/blog/building-modern-applications-with-django-and-vuejs/>
	
	<https://github.com/techiediaries/django-auth0-vue>

* **Sebastian** (2) [1036682](https://platzi.com/comentario/1036682/) 

	Como uso auth0 en una api con graphql y un cliente react

* **Juan David Castro (Platzi)** (2) [445258](https://platzi.com/comentario/445258/) 

	🗺 El término Universal significa que tenemos la capacidad de ejecutar el mismo código desde nuestro servidor y los diferentes clientes de nuestra aplicación 😬.
	
	* [Next.js 6 Features: A Practical Introduction - Auth0 Blog](https://auth0.com/blog/nextjs-6-features-introduction/)
	
	

	* **glrodasz** [445258] (2)

		Si, pero hay que tener en cuenta que esta definición aplica cuando hablamos de `JavaScript Universal/isomorfico`. Otros lenguages como Dart se les suele llamar `Lenguages multiproposito`.
		
		Ahora bien, para el concepto de Universal Login no aplica esta definición.

* **Alexander  Silvera** (2) [59402](https://platzi.com/comentario/590848/) 
Si tengo una aplicación solo con Django no puedo hacer Login Universal??

	* **glrodasz** [59402] (1)

		Si, claro deberias poder hacerlo. No he trabajado con Django, pero como framework fullstack deberia tener una manera de desacoplar lo que tenga como mecanisco de autenticacion para usar una alternativa.

* **ksanchez_cld** (1) [1007995](https://platzi.com/comentario/1007995/) 

	Pregunta…Como podemos manejar el tema de Alta Disponibilidad en Auth0. Ya que estamos hablando de seguridad en la authenticacion, es necesario tratar este tema.
	
	Que sucederia si aplicamos Auth0 a una App con gran cantidad de clientes y no pudieramos logearnos a la misma?
	
	Que solucion se plantearia?
	
	Podemos ver un video o todo un curso relacionado al tema?

* **AlvaroRT** (1) [931956](https://platzi.com/comentario/931956/) 

	Excelente clase, muy útil.

* **David Montoya Perez** (1) [803470](https://platzi.com/comentario/803470/) 

	Tengo una duda con el local storage. No se ve muy seguro que se pueda acceder a la información tan facíl como hiciste ahí.

* **Alexander  Silvera** (1) [590848](https://platzi.com/comentario/590848/) 

	Si tengo una aplicación solo con Django no puedo hacer Login Universal??

	* **glrodasz** [590848] (1)

		Si, claro deberias poder hacerlo. No he trabajado con Django, pero como framework fullstack deberia tener una manera de desacoplar lo que tenga como mecanisco de autenticacion para usar una alternativa.

## 0330. Social Login con Auth0 [15833](https://platzi.com/clases/1439-autenticacion-oauth/15833-social-login-con-auth0/)

### Descripción:


Social Login es una implementación de Single Sign-On (SSO) para usuarios finales, usando información existente desde un proveedor de red social como **Facebook, Twitter** o **Google**. De esta manera el usuario puede acceder a un sitio web tercero sin necesidad de tener que crear una nueva cuenta específicamente para ese sitio web. Esto simplifica el resgistro y acceso a los usuario finales.

## Como funciona

  1. El usuario ingresa a la aplicación y selecciona la red social de preferencia.
  2. Un llamado de acceso es enviado al proveedor de la la red social.
  3. Cuando el proveedor de la red social confirma la identidad del usuario, el usuario actual tendrá acceso a la aplicación.



> **Nota:** Auth0 soporta actualmente más de 30 proveedores sociales y además si el proveedor usar OAuth 2.0, se puede agregar de manera personalizada.

## Implementación

  1. Ingresamos al Dashboard adminitrativo de Auth0 en <https://manage.auth0.com>.
  2. Luego hacemos clic en **Connections** y luego en **Social**.
  3. Activamos el checkbox de los proveedores de redes sociales que queremos activar.
  4. Seleccionamos las aplicaciones con las que queremos usar este proveedor de red social.
  5. Veremos un popup que nos mostrara la información requerida para su configuración. **Tip:** En cada pantalla se incluye el link oficial con las instrucciones para obtener los keys necesarios para su configuración.
  6. Hacemos click en _Save_.

![](https://i.imgur.com/ztpwb6x.gif)

Y listo con este tenemos configurados los proveedores sociales en nuestra pantalla de login. Recuerda que el plan gratuito de Auth0 permite usar hasta máximo dos proveedores de redes sociales a la vez.

### Comentarios:

* **c3tuxpo2018** (1) [820028](https://platzi.com/comentario/820028/) 

	Auth0 segun lo que explica es muy facil de implementar y si es gratutio para dos cuentas den redes sociales, con eso podemos arrancar. Gracias

## 0340. Custom Social connection con Spotify [15835](https://platzi.com/clases/1439-autenticacion-oauth/15835-custom-social-connection-con-spotify/)

### Descripción:


### Links:

* [Add a generic OAuth2 Authorization Server to Auth0](https://auth0.com/docs/connections/social/oauth2)

* [Auth0 Extension: Custom Social Connections](https://auth0.com/docs/extensions/custom-social-extensions)

### Comentarios:

* **AlvaroRT** (1) [931970](https://platzi.com/comentario/931970/) 

	Excelente clase.

* **c3tuxpo2018** (1) [820051](https://platzi.com/comentario/820051/) 

	Auth0  
	Feature Custom Social connection con Spotify
	
	* En el dash de spotify hay que copiar las credencial de nuestro cliente, de ahi en el Manage de Auth0 debemos ir a la extencion Custom Social Connetcion
	
	* Nos pide autenticacion
	
	* creamos una nueva  
	lo unico que pide es llenar los datos como una nueva autorizacion
	
	* URL de autorizacion
	
	* URL del token
	
	* Client ID el que copiamos de spotify
	
	* Client Secret el que copiamos de spotify
	
	* Scope son los que tenemos para obtener información del usuario (user-read-private user-read-email
	
	* Fetch User Profile Script inplementación para obtener la información del cliente
	
	
	
	  1. copiamos las utilidades de las otras apliciones (get use info )
	  2. Objeto de opciones donde va a recibir el Access Token y va hacer el request
	  3. llamar al callback cb
	
	
	
	Asegurar Guardar  
	probar  
	Un detalle en el vídeo sale un error y es por que la URl del serivcio de auth0 no estaba validada en el servicio de spotify, se la agrega y funciono sin problema

## 0350. Multifactor authentication [15836](https://platzi.com/clases/1439-autenticacion-oauth/15836-multifactor-authentication/)

### Descripción:


Multifactor authentication _(tambien conocido como Two Factor Authentication)_ nos permite configurar nuevos pasos de seguridad además del nombre de usuario y password. Este método consiste en que los usuarios deben escribir un código aleatorio con limite de tiempo que podemos recibir por correo electrónico, mensajes de texto o servicios como Google Authentication.

El desafío de esta clase es configurar un método de autenticación _passwordless (como SMS o Email)_.

### Comentarios:

* **IngAntonyF** (1) [957226](https://platzi.com/comentario/957226/) 

	excelente clase lo recomendare en las aplicaciones que estén disponibles.

* **AlvaroRT** (1) [931977](https://platzi.com/comentario/931977/) 

	Muy buena recomendación de uso.

* **c3tuxpo2018** (1) [820069](https://platzi.com/comentario/820069/) 

	Ok la recomendación de implementar el Multifactor authentication en los servicios principales como medida adicional de seguridad

* **Cristian David Franco Garcia** (1) [484413](https://platzi.com/comentario/484413/) 

	Upgrade your subscription to our Developer Pro or Enterprise Plan for access to the DUO and One-time Password factors. 😦

## 0360. Authorization Extension en Auth0 [15837](https://platzi.com/clases/1439-autenticacion-oauth/15837-authorization-extension-en-auth0/)

### Descripción:


Authorization Extension otorga soporte de autorización para el usuario vía **Grupos** , **Roles** y **Permisos**. Se pueden definir comportamientos esperados durante el proceso de login mediante el uso de [reglas](https://auth0.com/docs/rules).

También se puede guardar los datos de los grupos, roles y permisos en el **Access Token** generado por Auth0. Así, nuestra aplicación puede tomar esta información del token y tomar acciones basadas en el contexto actual de autorización.

Actualmente los roles y permisos son creados por aplicación (Cliente), así que si se necesitan los mismo roles y/o permisos en otra aplicación se deben crear de manera separada.

## Instalación

Asegúrate de que ya tienes una aplicación existente, la extensión se puede usar con los siguientes tipos de aplicación:

* Native
* Regular Web app
* Single Page app



Para instalar la aplicación en el dashboard administrativos nos dirigimos a la sección de [extensiones](https://manage.auth0.com/#/extensions) allí seleccionamos **Auth0 Authorization**.

Nos aparecerá un popup para generar su instalación y nos preguntará donde queremos guardar la información, seleccionaremos Webtask Storage.

Después de instalada podremos verla en la pestaña de **Installed Extensions**. Hacemos clic y la primera vez nos preguntará por los permisos que necesita la app para acceder a Auth0. Aceptamos y podremos ver el dashboard de autorización.

![auth-extension.png](https://static.platzi.com/media/user_upload/auth-extension-9e04f40f-4f48-46fa-8bb9-bb280046cd9a.jpg)

## Configuración

Para empezar con nuestra configuración inicial debemos crear los Grupos, Roles y Permisos de nuestra aplicación. A grandes rasgos los Permisos son los que nos permiten identificar si el usuario esta autorizado para acceder a un recurso o no. Los Roles son simplemente un conjunto de Permisos y los Grupos son un conjunto de Roles.

Por ejemplo podríamos tener la siguiente jerarquía:

* **Grupo:** `Admin`:
* **Roles:** `Playlists Manager` y `Voting Manager`.
* **Permisos para Playlists Manager:** `read:playlists`, `create:playlists` y `delete:playlists`.
* **Permisos para Voting Manager:** `read:votes` y `reset:votes`.



Para crear los Grupos, Roles y Permisos es necesario acceder a las diferentes opciones en el menú lateral izquierdo. Una vez creada nuestra estructura podemos agregar nuestros usuarios a los grupos creados.

Creamos todos los posibles permisos:

![auth-extension-permissions.png](https://static.platzi.com/media/user_upload/auth-extension-permissions-0b7f4964-745e-4eb0-9a9c-cb17f1f22c53.jpg)

Creamos los roles y asociamos sus permisos adecuados:

![auth-extension-role-editing.png](https://static.platzi.com/media/user_upload/auth-extension-role-editing-669fd08f-0ef6-4ebc-ad01-d555b5c41bde.jpg)

Creamos los grupos y hacemos clic en el para agregar miembros y asociar los roles:

![auth-extension-groups.png](https://static.platzi.com/media/user_upload/auth-extension-groups-f6560428-e336-41a9-81cf-92d36abae860.jpg) ![auth-extension-group-details.png](https://static.platzi.com/media/user_upload/auth-extension-group-details-184188d5-aca8-4ade-a847-0cf9fbdfcac1.jpg)

Para publicar nuestra configuración en los tokens generados lo que debemos hacer es hacer clic en el menú superior derecho en el nombre de nuestro tema y después en **Configuration**.

![auth-extension-config.png](https://static.platzi.com/media/user_upload/auth-extension-config-134d6032-aae6-4c30-8d38-b0596def73c9.jpg)

Mi recomendación es solo publicar los **Permissions** y luego le damos clic en **Publish Rule** :

![auth-extension-config-details.png](https://static.platzi.com/media/user_upload/auth-extension-config-details-b2fc753a-8a2b-4bd6-9a1f-9848b0798c7c.jpg)

Con estos hemos configurado los permisos para nuestros usuarios. A partir de esto lo que podemos hacer es consultar los scopes en el **authResult** (El resultado del llamado `this.auth0.parseHash`) otorgado por Auth0 y dependiendo de los permisos podemos variar los elementos de nuestra UI o agregar validaciones a nivel de nuestros endpoints.

Para revisar un ejemplo de la implementación en Angular puedes dirigirte [aquí](<https://auth0.com/docs/architecture-scenarios/application/spa-api/spa-implementation-angular2#4-display-ui-elements-conditionally-based-on-scope>

### Comentarios:

# Consideraciones para producción [3112]

## 0370. Buenas prácticas para el despliegue en producción [15838](https://platzi.com/clases/1439-autenticacion-oauth/15838-buenas-practicas-para-el-despliegue-en-produccion0/)

### Descripción:


  1. No publicar las credenciales y tokens secretos en nuestros repositorios, en vez de escribirlos directamente en el código, podemos utilizar variables de entorno y librerías como [dotenv](https://github.com/motdotla/).
  2. Usar diferentes clientes para diferentes ambientes, es decir, separar muy bien código de desarrollo, pruebas y producción.
  3. Usar diferentes tenants (en la siguiente clase encuentras más información al respecto)
  4. Revisar y estar al tanto de las mejores prácticas de seguridad o nuevos ataques y cómo protegernos de ellos.
  5. Centralizar la lógica de negocio, es decir, en vez de consumir diferentes APIs de servicios externos, podemos solo hacer peticiones a nuestra API y, desde el backend, encargarnos de obtener la información de los diferentes servicios.



### Links:

* [
  
    
      Removing sensitive data from a repository - User Documentation
    
  
  ](https://help.github.com/articles/removing-sensitive-data-from-a-repository/)

### Comentarios:

* **Yeffer Daniel Guecha Medina** (3) [64588](https://platzi.com/comentario/678826/) 
Me pueden ayudar, estoy desarrollando una API con laravel y graphql tengo que implementar OAuth y OpenID Connect, pero no se como otorgar...

	* **Yeffer Daniel Guecha Medina** [64588] (1)

		es el link de mi repositorio:  
		[git@github.com](mailto:git@github.com):dagume/app.git

* **YEUDIHT PORTUGUEZ** (1) [1017242](https://platzi.com/comentario/1017242/) 

	Buenas tardes, quisiera saber cómo puedo manejar un solo inicio de sesión por persona con oauth y passport… gracias

* **JUAN CARLOS PARRA GALAN** (1) [75110](https://platzi.com/comentario/863953/) 
Dónde debería guardar los secretos en el backend? Variables de entorno?

	* **Manuel Ojeda** [75110] (3)

		Así es, las claves deben de ir en **.env** y recuerda que en tu archivo **.gitignore** agregar tu archivo de variables de entorno.

## 0380. Uso de diferentes tenants para producción con Auth0 [15839](https://platzi.com/clases/1439-autenticacion-oauth/15839-uso-de-diferentes-tenants-para-produccion-con-auth/)

### Descripción:


Cuando se crea una cuenta de Auth0 solemos elegir un nombre de dominio o tenant. Como por ejemplo `foo@us`. El identificador de `foo` y la región es `us` (US).

> Se pueden crear tenants también en AU (Australia) y EU (Europa).

Con este tenant podemos experimentar e incluso hacer nuestra implementación en producción, pero mi recomendación es que se creen un tenant por ambiente, es decir al menos uno para desarrollo, staging/pruebas y producción.

Para ellos solo deben dirigirse a <https://manage.auth0.com> y en la esquina superior derecha hacen clic en su tenant y luego en `create tenant`.

![create-tenant.png](https://static.platzi.com/media/user_upload/create-tenant-c6235200-f4a8-471b-8f81-c55b7651d15f.jpg)

Si luego quieren cambiar entre los dashboards de los diferentes tenants se dirigen al mismo menú pero esta vez seleccionan `switch tenant`.

Les recomiendo que pongan un sufijo en sus nombres, es decir si el tenant de producción se llama `foo`, el de desarrollo debería llamarse `foo-dev`, el de staging/pruebas `foo-stg` y así sucesivamente.

### Comentarios:

# Cierre del curso [3113]

## 0390. Cierre del curso [15840](https://platzi.com/clases/1439-autenticacion-oauth/15840-cierre-del-curso9513/)

### Descripción:


¡Felicitaciones por terminar el Curso de Autenticación con OAuth!

Durante el curso aprendimos qué son y cuáles son las diferencias entre autorización y autenticación, qué es Open Authentication 2.0 y cómo funcionan sus diferentes flujos de implementación, descubrimos Open ID Connect y utilizamos servicios como Auth0 para facilitar la integración de estos servicios a nuestra aplicación.

El desafío final del curso es implementar Auth0 en tus aplicaciones y contarnos cómo te pareció en la sección de comentarios.

### Comentarios:

* **Alvaro   Gonzalez** (7) [447958](https://platzi.com/comentario/447958/) 

	Gracias, muy bueno el curso.

* **juand_silva** (2) [678419](https://platzi.com/comentario/678419/) 

	Excelente curso, creo que el tema de auth0 debe ser un curso aparte pero realmente estuvo muy bien el curso.

* **Andrés Mauricio Montoya Sánchez** (2) [663300](https://platzi.com/comentario/663300/) 

	Hablaron muy poco de auth0, deberian de hacer un curso dedicado completamente a todo lo que ofrece.

* **AlvaroRT** (1) [931993](https://platzi.com/comentario/931993/) 

	Es una EXCELENTE clase, muy completa, muy bien explicada, lamentablemente no se nada de programación, pero esta clase está en la secuencia de mi ruta de aprendizaje, por lo que tome el curso. Lo único que puedo asegurar, es que volveré a tomarlo cuando tengas mas conocimientos de programación.

* **c3tuxpo2018** (1) [820075](https://platzi.com/comentario/820075/) 

	Gracias profesor Excelente el curso

