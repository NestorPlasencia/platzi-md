# Aprender sobre autenticación y autorización

## 0010. Introducción y bienvenida

### Descripción:


¡Bienvenido al Curso de Autenticación con Passport.js!

Nuestro profesor, Guillermo Rodas, es Ingeniero en Auth0, Google Developer Expert en Web Technologies y Co-Organizer de Medellín CSS, CSS Conf CO y Medellín Identidad y Seguridad. Tiene seis años de experiencia trabajando con JavaScript.

Este curso es un complemento de la **Escuela de JavaScript** una carrera en la cual realizaremos un proyecto llamado **Platzi Video**. En este curso en específico nos dedicaremos a crear la capa de seguridad y autenticación.

### Links:

* [GitHub - glrodasz/platzi-auth-passport](https://github.com/glrodasz/platzi-auth-passport)

### Comentarios:

* **jasanhdz** (7)

	
	Hola, tal vez mis notas del curso te sean de mucha utilidad en esté proceso de aprendizaje:  
	<https://github.com/JasanHdz/passportjs/blob/master/notes/notes.md>  
	Te invito a hacer un `fork` y que sigas mejorando mi contenido, espero haberlos ayudado. 😄

	* **Andrés Campuzano Garzón** (1)

		
		Muchas gracias compañero.

	* **Miguel Ángel Portillo Bobadilla** (1)

		
		Muchas gracias!

* **JaimeRamos** (4)

	
	Si Guillermo es el profesor, esto pinta bien…

* **Alejandro González Reyes** (3)
Gracias a expressjs aprendí a trabajar con un framework, antes mis desarrollos eran desde cero

* **Brando Rodríguez** (3)
El primero 💛 escuela javascript !!

* **jesus-olivares661** (1)

	
	esta bien que use passport con el paquete accesscontrol…?  
	ó con passporwt es suficiente…?

* **jesus-olivares661** (1)

	
	si veo este curso no es necesario q vea el curso de autenticacion con oauth…?

	* **Gabriel De Andrade (Platzi)** (2)

		
		En este curso se ve OAuth, sin embargo para aprenderlo a fondo deberías ver el [Curso de OAuth](https://platzi.com/clases/autenticacion-oauth/). Acá solo se da una especie de introducción 😄

* **Jesús Miguel Quinto Teran** (1)

	
	:gree

* **Juan Carlos García Esquivel** (1)

	
	Plugins recomendados:  
	[JSON viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh)  
	[Postman](https://www.getpostman.com/)

	* **robertarnaldo99** (2)

		
		Excelente.

## 0020. Stack de seguridad moderno

### Descripción:


Anteriormente las compañías se comunicaban mediante un _intranet_ que actualmente ha sido reemplazado con un stack de seguridad moderno usando:

  * **JSON Web Tokens:** Nos permite comunicarnos entre dos clientes de una manera más segura.
  * **OAuth 2.0:** Un estándar de la industria que nos permite implementar autorización.
  * **OpenID Connect:** Es una capa de autenticación que funciona por encima de _Oauth 2.0_.



### Links:

* [OAuth 2.0 — OAuth](https://oauth.net/2/)

* [OpenID Connect | OpenID](https://openid.net/connect/)

* [JSON Web Tokens - jwt.io](https://jwt.io/)

### Comentarios:

* **Jose Daniel Barría Reyes** (5)

	
	No confundir autorizacion con autentificacion.

* **wilantury** (1)

	
	Stack de seguridad moderno: JWT - OAuth 2.0 - OpenID Connect

* **Alejandro González Reyes** (1)
En que se diferencia la autenticación de la autorización. Ya que passport se emplea para hacer login con varios servicios de red social t...

	* **Juan David Castro (Platzi)** (2)

		
		👉 [👮 Autenticación 🆚 Autorización 🤖](https://platzi.com/comentario/445213/)  
		👉 [Hablemos sobre Estándares de Seguridad y OAuth 2.0](https://platzi.com/blog/aprende-estandares-de-seguridad-y-oauth/)  
		👉 [A tu autenticación le hace falta verificación](https://platzi.com/blog/a-tu-autenticacion-le-hace-falta-verificacion/)

## 0030. ¿Qué es la autenticación y la autorización

### Descripción:


La autenticación sirve para verificar la identidad de un usuario, verificar si el usuario existe y si los datos que está colocando son correctos.

La autorización es la acción de permitir a un usuario acceso limitado a nuestro recursos.

### Comentarios:

* **Juan Carlos García Esquivel** (2)

	
	 **¿Qué es la autenticación y la autorización?**  
	**autenticación** : verificar quien eres.  
	**autorización** : verifica que permisos tienes.  
	En el ejemplo del valet parking las dos llaves son un método de **autenticación** para poder utilizar el auto, pero tienen distintos niveles de **autorizacion** permisos para usar el auto.

* **David Behar** (2)

	
	Un usuario está **autenticado** (de manera única) mediante una **autenticación** (contraseña, biométrico, etc).
	
	El usuario autenticado tiene **autorizado** ciertos permisos.

* **gabotk** (2)

	
	Muy interesante.

* **Alejandro González Reyes** (2)
Ya veo, de ahí la importancia de las sesiones para guardar cierta data del usuario en el servidor para saber si está autenticado o no y con una consulta obtener más información acerca de el. Pero recuerdo que en un libro decían que las spa no tienen sistema de sesiones, ya que el Index se entrega solo una una vez

	* **Daniel Esteves** (1)

		
		Las SPA si tienen un sistema de sesiones utilizando Session Storage o Local Storage ya que JavaScript ha avanzado mucho actualmente

* **solej77** (1)

	
	Al principio del video comienzan a hablar sobre autenticación, pero en la presentación hacen referencia a la autorización.
	
	Saludos!!

	* **Emmanuel Rodríguez Ramírez** (1)

		
		Cabe mencionar que “Todo usuario requiere/necesita autenticación. Sin embargo, no todos los usuarios tienen autorización a uno/varios recursos”.

## 0040. Introducción a las sesiones

### Descripción:


Cuando visitamos un sitio por primera vez se crea una sesión con los ajustes que se configuran. Por ejemplo, en un sitio web de reserva de hoteles, a medida que buscamos y ponemos preferencias de precios y demás, éstas se irán guardando en dicha sesión. Y luego estos datos se convertirán en un ID que será almacenado en una cookie en tu navegador.

### Links:

* [cookie-session  -  npm](https://www.npmjs.com/package/cookie-session)

* [express-session  -  npm](https://www.npmjs.com/package/express-session)

### Comentarios:

* **diegoguevaraco** (9)

	
	Autenticación: Quien soy yo.  
	Autorización: Que puedo hacer.

* **Massimo Di Berardino** (4)

	
	 **Autenticación** : Cuando inicio sesión en platzi.  
	**Autorización** : Cuando no me deja acceder a los cursos de ingles por que tengo la suscripcion mensual 😦

	* **oscar-leon846** (1)

		
		xD

* **Navarrock33** (4)

	
	Ejemplo: Visito una zona arqueologica, compro mi pase y me dan un boleto (autenticacion)… dentro de la zona arqueologica veo una pieza muy bonita y quiero tomarla por un momento pero no puedo porque el guia dice que no estoy <autorizado> para hacerlo ya que las politicas del lugar no me lo permiten y ello viene explicitamente indicado en mi boleto.

* **Jesús Miguel Quinto Teran** (3)

	
	Autentificación: Las credenciales son correctas y se quien eres  
	Autorización: Puedes tener acceso al recurso que intentas acceder.
	
	**Ejemplo:**  
	Autentificación: Tu documento de identidad me permite saber quien eres.  
	Autorización: Pero no puedes comprar Cerveza por ser menor de edad.

* **alexibarra11** (2)

	
	**Autenticacion:**Unicamente saber cual es la identidad del usuario  
	**Autorizacion:**Saber que puede hacer ese usuario

* **jvasquez507** (2)

	
	Autenticación: Ingreso a mi banca móvil utilizando un factor biométrico (huella dactilar/reconocimiento facial).  
	Autorización: Dependiendo de mi perfil puedo hacer transacciones o solamente consultas.  
	Doble factor de autenticación: Una vez accedo a mi banca móvil y estoy autorizado para hacer transacciones, me piden que ingrese un token, proveniente de un dispositivo físico o un soft-token en mi celular, para autenticar nuevamente mi identidad.

* **pablopoggiog** (2)

	
	 **Autenticacion** : Cuando compro mi entrada e ingreso al parque de diversiones.  
	**Autorizacion** : Cuando no puedo subir a los mejores juegos, porque soy un raton y pague la entrada basica ![](https://www.generadormemes.com/media/created/200x200x13q2duetlwgwxzcr76hl5vobhe9r644tqlz253mmslf23jgd1gnslp9ga7qy9ou.jpg.pagespeed.ic.imagenes-memes-fotos-frases-graciosas-chistosas-divertidas-risa-chida-espa%C3%B1ol-whatsapp-facebook.jpg)

* **David Behar** (2)

	
	Las sesiones son conversaciones temporales entre el usuario y el servidor donde se guarda la actividad del primero para que el segundo genere la interactividad (muestre la información correcta)  
	.  
	El proceso de una sesión es:  
	.  
	• Se crea una **sesión**  
	• A medida que vas navegando se **guarda la actividad** en la sesión  
	• La sesión guarda un **id** que es almacenado en una **cookie** (almacenada en el navegador, generando permanencia)  
	• Al **volver a abrir** el sitio éste se comunica con la **cookie** para autenticar a la sesión, **cargando las preferencias** que generó el usuario al navegar  
	• Al **iniciar sesión** , se **combina** la información del **navegador** actual con la de **otros navegadores** **vinculados** a la cuenta
	
	Las librerías para guardar esta información son `cookies-session` (guarda en **navegador** ) y `express-session` (guarda en **servidor** )

* **AryRosvall** (2)

	
	La autenticación en platzi es acceder con mis credenciales usuario y contraseña para iniciar sesión.
	
	La autorización sería validar que tipo de membresía adquirí para saber a qué cursos tengo acceso.

* **Alejandro González Reyes** (2)

	
	Ejemplo: Un sitio web que cumpla la función de una plataforma de servicios educativos
	
	  * La parte pública es aquella información que puede ser consumida por todos los usuarios que visitan el sitio.  
	La parte privada es aquella que pueden visualizar los estudiantes de dicha plataforma, es decir, solo usuarios autenticados pueden acceder a dicha información  
	Las autorizaciones: La plataforma tiene una parte administrativa para la gestión de información, solo pueden acceder a ella usuarios con rol o privilegios de administrador.
	
	

* **JaimeRamos** (2)

	
	cuando visitas un sitio web se crea una petición http, diferentes peticiones http nunca comparten información entre sí, la manera para compartir información entre peticiones http es mediante una sesión, cada vez que visitamos un sitio web se crea una sesión en la aplicación, que de acuerdo a lo ocurrido en la navegación se guarda información o preferencias, luego esa sesión genera un id que se guarda en una cookie, la cookie es un archivo que se almacena en tu navegador, para que cuando cierres el navegador la cookie permanezca con el id de la sesión y así se relaciona con las próximas sesiones, cuando hay un proceso de autenticación la sesión se almacena y de relaciona con tu usuario.  
	cookie-session nos permite almacenar la sesión en la cookie mientras que express-session nos permite almacenar la sesión en memoria en el lado del servidor, json web tokens no tiene estado y por lo tanto no necesita memoria.

* **giothcode** (2)

	
	 ** _Autenticación_** : Verificar que el usuario sea quien dice ser.  
	**_Autorización_** : Los permisos a los recursos que le otorgamos al usuario.

* **ejgachancipa** (1)

	
	 **Autenticación:** Cuando verifican tu identidad en migración a la hora de tomar un vuelo.  
	**Autorización:** Cuando te permiten subir al vuelo que coincide con tu ticket.

* **José Abdiel Ortega Vázquez** (1)

	
	Autenticación: Cuando llegas a un club y le dices tu nombre al cadenero o te identificas.  
	Autorización: Una veź entras los meseros de acuerdo a la información que diste determinan si tienes reserva o tienes acceso a ciertos lugares del club.

* **Eden Gomez Gress** (1)

	
	Autenticacion: Cuando creo una cuenta para poder llenar un formulario usuario.
	
	Autorizacion: Cuando el responsable de la aplicacion necesita tener acceso a la informacion obtenida a travez del formulario de registro.

* **Deyvis Neyser Valdez Gavilan** (1)

	
	Authentication: Cuando compro mis entradas al cine y me dejan ingresar.  
	Authorization: Cuando solo me dejan acceder una sala en específica.

* **Alan Mena** (1)

	
	Autenticación: Cuando en una MacBook se tienen varios usuarios/familia. Se le permite ingresar al usuario con sus credenciales y hacer uso del MacBook.  
	Autorización: Dependiendo el usuario/familiar, se le permite realizar ciertas tareas (Instalar, crear, borrar archivos) dependiente de los permisos de su perfil.

* **Alex Junior Rodriguez Huerta** (1)

	
	Autenticación: Cuando puedo ingresar con mi pase al edificio de mi trabajo.  
	Autorización: El pase solo me deja subir al piso 3 y 4.

* **crimiro** (1)

	
	Autentificación: Cita en un corporativo donde se requiere identificarse para acceder  
	Autorización: Dan una llave de acceso para solamente ir a cierta planta del edificio y volver a planta baja

* **René Sanchez** (1)

	
	Autenticación => Para ingresar mi hora de llegada pondre mi huella y me saldra registrado entrada exitosamente por que yo existo en la base de datos e activo.
	
	Autorizacion => No tengo autorizacion para poder volver a ingresar mi entrada luego que sali durante el transcurso del dia, por ende me sale que no tengo autorizado poder ingresarlo nuevamente.

* **wilantury** (1)

	
	Autenticación: El personal que puede acceder a un edificio puede hacerlo autenticándose en la recepción del edificio.  
	Autorización: cada persona tiene permisos diferentes dentro del edificio, según su perfil puede acceder a ciertos espacios, y habrán otros espacios a los que no podrá entrar.

* **Iván Darío Sánchez Jiménez** (1)

	
	Autenticación: Cuando vas a un concierto solo apto para mayores de edad y te piden tu documento de identidad.
	
	Autorización: después de validado el documento se revisa el tipo de boleto que traes VIP, platea, general y según eso te autorizan el paso a cada uno de los lugares indicados.

* **ennma5** (1)

	
	Autenticación: Cuando el guardia de seguridad del trabajo te ve y te deja pasar a la recepción y revisa que no traigas armas.
	
	Autorización: Cuando ocupas tu tarjeta de acceso para ingresar a las oficinas y a los diferentes pisos.

* **Tonalli López** (1)

	
	autenticación: saber si el usuario es realmente el usuario  
	autorización: las acciones que puede realizar el usuario

* **JaimeRamos** (1)

	
	este curso me va a servir para autenticar usuarios desde un aplicativo móvil(react-native)?

* **Rubén Jiménez Torres** (0)

	
	Facil:  
	Autenticación --> llego a un antro con previa cita y me dejan pasar porque ya aparezco en la lista.  
	Autorización --> solo tengo acceso a la una zona del antro, no puedo ir al VIP(al menos que pague).
	
	Jaja. saludos!!!

# Conocer qué son los JSON Web Tokens

## 0050. Anatomía de un JWT

### Descripción:


 **JWT** es un estándar de la industria que nos permite manejar demandas de información entre dos clientes.

### Links:

* [RFC 7519 - JSON Web Token (JWT)](https://tools.ietf.org/html/rfc7519)

### Comentarios:

* **Rafael Guzmán Barranco** (5)

	
	Un JWT consta de tres partes generalmente divididas por punto, ejemplo:
	
	eyJdudsjfhjdfdf.yudfndjfnjdfnsjfsfhsbfjsbd.nSDFsersfsdfsf  
	_(el gato me ayudó)_
	
	Header
	
	Tiene 2 atributos:
	
	  * El tipo que en este caso siempre debe ser JWT
	  * El algoritmo de encriptación de la firma 
	    * Asíncrono 
	      * Usan dos llaves de encriptación 
	        * Privada 
	          * Desencripta
	        * Pública 
	          * Encripta
	      * Se deben usar donde en partes públicas que puedan tener acceso a esta llave
	    * Síncrono 
	      * Usa la misma llave para 
	        * Encriptar
	        * Desencriptar
	      * Sólo se deben usar en el Backend
	
	
	
	Payload
	
	Guarda toda la información de:
	
	  * Usuarios
	  * Scopes de autorización,
	  * Se componen de Claims 
	    * Se representan por tres letras para mantener el JSon muy pequeño
	    * Tipos de Claims 
	      * Registered Claims _(Tienen una defección propia y deben respetarse)_
	      * Public Claims _(Son una lista que pueden usar y están definidos)_
	      * Private Claims _(Son los que uno mismo defina para la aplicación)_
	
	
	
	Signature  
	Hace poderoso al JWT y se compone por:
	
	  * Header codificado
	  * Payload codificado
	  * Se emplea un Secret
	
	

* **jasanhdz** (4)

	
	Hola, tal vez mis notas del curso te sean de mucha utilidad en esté proceso de aprendizaje:  
	<https://github.com/JasanHdz/passportjs/blob/master/notes/notes.md>  
	Te invito a hacer un `fork` y que sigas mejorando mi contenido, espero haberlos ayudado. 😄

* **JaimeRamos** (3)

	
	un JWT consta de tres partes generalmente divididas por punto:  
	-header  
	tiene 2 atributos, el tipo que en este caso siempre debe ser jwt y el algoritmo de encriptación de la firma  
	-payload:  
	se guarda toda la información de los usuarios incluso todos los scopes de autorización, esos payloads se componen de claims  
	-signature:es el header codificado + el payload codificado,a todo esto se le aplica el algoritmo de encriptación usando un secret

* **David Behar** (2)

	
	Un JSON Web Token es un estandar que nos permite generar demandas entre 2 clientes de manera segura.  
	.  
	Un JWT está encriptado, pero tiene 3 partes principales divididas por ‘.’ (punto)  
	.
	
	  1. Header: Contiene los archivos de configuración (el tipo y el algoritmo de encriptación)
	  2. Payload: Guarda la información de nuestros usuarios
	  3. Signature: es la firma que contiene el header códificado más el payload códificado
	
	

* **Jesús Miguel Quinto Teran** (1)
<h1>NOTAS</h1>
	
	## JWT (json web token)
	
	JSON Web Token (JWT) es un estándar abierto que define una forma compacta y  
	autónoma para transmitir información de forma segura entre las partes como  
	un objeto JSON.
	
	Esta información se puede verificar y confiar porque está firmada digitalmente.
	
	<h3>Estructura</h3>
	
	Los JWT se componen de 3 partes:
	
	  * `HEADER`: Alg y typ
	  * `PAYLOAD`: Claims (diccionario con informacion no sensible, preferiblemente corta)
	  * `SIGNATURE`: header y payload encriptado
	
	<h4>alg:</h4>
	
	Algoritmo de encriptacion que puede ser Sincrono o Asincrono.
	
	`Algoritmo sincrono`: Para Autentificacion en el backend  
	`Algoritmo asíncrono`: Para Autentificacion con llave publica y privada.

* **Didier Zúñiga** (1)

	
	Alguíen podría por favor explicarme de manera sencilla que hace y como funciona realmente los Claims?

	* **oscar-leon846** (1)

		
		los claims pueden contener
		
		  * informacion del usuario, podria ser nombre, scopes (trata de no poner informacion sencible) (private claims)
		
		  * informacion de la peticion (claim), para esto se usa los registered claims, iss(issuer), sub(subject), aud(Audience)
		
		  * diferentes aplicaciones se podrian usar tu servicio y si fuera necesario, deberas definir unos claim para que la comunicacion sea efectiva(public claims), se aconseja que sigas el estandard de los registered claims
		
		
		

* **wilantury** (1)

	
	Los algoritmos síncronos se deben usar en el backend, y los algoritmos asíncronos en donde una de las partes sea publica.

* **Alejandro González Reyes** (1)
He observado que los bancos, usan frecuentemente los tokens para realizar alguna acción en sus sistemas. Si tu decides generar tu estado ...

	* **Daniel Esteves** (1)

		
		No, actualmente no poseemos ningún ejemplo de esto pero a eso se le llama SMS Token y hay muchos servicios que te pueden ayudar a integrarlo n.n

## 0060. Autenticación tradicional vs JWT

### Descripción:


Cuando usamos una autenticación tradicional se crea una sesión y el ID de esa sesión se almacena en una _cookie_ del navegador, pero cuando utilizamos **JWT** firmamos un token y este se guarda en el navegador el cual permite a una _SPA_ actualizarse sin refrescar la ventana.

### Comentarios:

* **David Behar** (9)

	
	## Auth tradicional
	
	  1. Se crea una sesión (el id se almacena en una cookie)
	  2. Los request de ahí en adelante (hasta que expire) vienen con la información de la cookie
	
	
	
	**Problemas del auth tradicional**  
	Las SPA no refrescan todas las veces (y no saben si hubieron cambios en la sesión)  
	Las REST API no deberían tener estado, al crear sesiones se crea estado  
	Para microservicios las sesiones de una sóla máquina no fluyen naturalmente hacia varios clientes  
	El control de acceso requiere que vayamos a base de datos
	
	## JSON Web Tokens Auth
	
	  1. En el proceso de Autenticación el server firma un token
	  2. A partir de ese momento el cliente almacena el token en memoria y en una cookie
	  3. Todos los request de ahí en adelante llevan el token
	
	
	
	**Ventajas de JWT**
	
	  1. No requiere del backend para saber si está autenticado porque lleva una firma (post autenticación)
	  2. El backend puede recibir multiples request de multiples clientes (sólo necesita saber si el token está bien firmado)
	  3. El cliente conoce los permisos que tiene, por lo que no los tiene que bajar de base de datos
	
	

* **David Behar** (2)
Si llegamos a saber cuál es el algoritmo de encriptación (usando alguno tradicional) ¿no acabaríamos comprometiendo toda nuestra app?

	* **Erik Ochoa (Platzi)** (1)

		
		Para romper los algoritmos de encriptación actuales necesitas a parte de conocer cómo funciona el algoritmo, una llave secreta que es muy difícil de conseguir. Por lo que ya no basta con sólo saber el algoritmo.

* **Alejandro González Reyes** (1)
En aplicaciones spa modernas el JWT se guarda en cookies o en localstorage. Digamos si mi API va a ser consumida por un spa o aplicación ...

	* **IvanDev** (3)

		
		Lo más recomendable es guardarlo en memoria, ya que si alguien tiene acceso a este token lo puede usar mientras este no expire.

## 0070. Firmando y Verificando nuestro JWT

### Descripción:


Para firmar nuestro token utilizaremos un paquete de node llamado `jsonwebtoken` y al usarlo en nuestro código se verá de esta manera:
``` 
    jwt.sign({ sub: user.id }, 'secret', options);
    
```

El primer atributo que recibe es el _payload_ o sea los datos que guardaremos en ese token. De segundo atributo recibe una clave secreta con la cual será firmado y finalmente podremos pasarle opciones si es nuestro caso.

Para verificar nuestro token lo haremos de la siguiente manera:
``` 
    jwt.verify(token, 'secret', function(err, decoded){});
    
```

Como primer atributo recibiremos el token, de segundo atributo el secreto de la firma y como tercer argumento (opcional) recibiremos el token decodificado.

  * Vamos a inicializar nuestro proyecto con `npm init -y`
  * Crearemos el archivo `index.js`
  * Vamos a instalar los paquetes necesarios con `npm i jsonwebtoken`
  * En el `index.js` vamos a hacer toda la lógica de nuestra aplicación



### Links:

* [jsonwebtoken  -  npm](https://www.npmjs.com/package/jsonwebtoken)

* [JSON Web Tokens - jwt.io](https://jwt.io)

* [Curso de Git y GitHub Profesional | Platzi](https://platzi.com/git)

* [GitHub - glrodasz/platzi-auth-passport at firmando-y-verificando-nuestro-jwt](https://github.com/glrodasz/platzi-auth-passport/tree/firmando-y-verificando-nuestro-jwt)

### Comentarios:

* **curwen98** (4)
🖐️Pregunta de novato! Cuál es el curso o algún libro que me ayude a entender la lógica secuencial del código??

	* **glrodasz** (3)

		
		Hola @Lidher, te recomiendo el curso básico de programación y a partir de allí puedes tomar toda la carrera de la escuela de JavaScript.

* **jadamson0903** (3)

	
	Me encanta el curso, solo como aporte, en la ultima function, le agrego una “s”, a la palabra “option”, de modo, que cuando intentas ejecutar, te manda undefined o corriganme, si hago algo mal pero con “options”, no ejecutaba.  
	Saludos
	``` 
	    const jwt = require('jsonwebtoken');
	    
	    const [, , option, secret, nameOrToken ] = process.argv;
	    
	    if ( !option || !secret || !nameOrToken) {
	        returnconsole.log("Missing arguments");
	    
	    }
	    
	    functionsignToken(payload, secret) {
	        return jwt.sign (payload, secret);
	    }
	    
	    functionverifyToken(token, secret) {
	        return jwt.verify(token, secret);
	    }
	    
	    if(option == 'sign') {
	        console.log(signToken({ sub: nameOrToken}, secret ));
	    } elseif ( option == 'verify') {
	        console.log(verifyToken(nameOrToken, secret));
	    } else {
	        console.log('Option needs to be "sign" or "verify"');
	    }
	    
	```

	* **romerodiesan** (1)

		
		Si, la segunda condición tuvo un options en vez de un option pero luego lo arregló. Vas bien Camilo.

* **Jesús Miguel Quinto Teran** (2)

	
	Que elegante es JWT.

* **Jair Balcazar Cobeña** (1)

	
	Alguien sabe porque el **Curso de Integración de Backend con Frontend** no esta disponible?  
	![](https://i.ibb.co/R67KzDK/1.png)

	* **Franco Correa** (1)

		
		Te lo dice la misma imagen: **Curso disponible el 21 de abril**. Aún no está terminado.

	* **Diego Camino** (2)

		
		Lo que sucede es que ese curso va ser una actualización del curso que anterior (2019)

* **wilantury** (1)

	
	Para firmar un JWT se necesitan como argumentos: Payload configurado según los claims que queramos introducir. El secret Key, y opciones.

* **Alejandro González Reyes** (1)
Por lo que veo, se debe verificar la firma del token en cada uno de nuestros endpoints privados. Pero en donde viaja está información. Po...

	* **IvanDev** (4)

		
		Hola, si te refieres donde se envía el token desde el cliente cuando hace un request a un endpoint seguro, este se debe enviar en los headers del request en una propiedad Authorization
		``` 
		    Authorization: Bearer <token>
		    
		```
		
		de esta forma el backend puede verificar el token y saber si es un token valido y si tiene permisos de ejecutar esa ruta.

## 0080. Server-side vs Client-side sessions

### Descripción:


# Sesiones del lado del servidor vs sesiones del lado del cliente

## ¿Qué es una sesión?

En terminos generales una sesion es una manera de preservar un estado deseado.

## ¿Qué es una sesion del lado del servidor?

La sesión en el lado del servidor suele ser una pieza de información que se guarda en memoria o en una base de datos y esta permite hacerle seguimiento a la información de autenticación, con el fin de identificar al usuario y determinar cuál es el estado de autenticación. Mantener la sesión de esta manera en el lado del servidor es lo que se considera “stateful”, es decir que maneja un estado.

## ¿Qué es una sesión del lado del cliente?

Las SPA (Single-page apps) requieren una manera de saber si el usuario esta autenticado o no. Pero esto no se puede hacer de una manera tradicional porque suelen ser muy desacopladas con el backend y no suelen refrescar la página como lo hacen las aplicaciones renderizadas en el servidor.

JWT (JSON Web Token) es un mecanismo de autenticación sin estado, lo que conocemos como “stateless”. Lo que significa que no hay una sesión que exista del lado del servidor.

La manera como se comporta la sesión del lado del cliente es:

  1. Cuando el usuario hace “login” agregamos una bandera para indicar que lo esta.
  2. En cualquier punto de la aplicación verificamos la expiración del token.
  3. Si el token expira, cambiamos la bandera para indicar que el usuario no está logueado.
  4. Se suele chequear cuando la ruta cambia.
  5. Si el token expiró lo redireccionamos a la ruta de “login” y actualizamos el estado como “logout”.
  6. Se actualiza la UI para mostrar que el usuario ha cerrado la sesión.



### Comentarios:

* **giothcode** (13)

	
	Dando un tiempo de expiración al token al firmarlo.
	``` 
	    jwt.sign({data:'foobar'}, 'secret', { expiresIn:'1h' });
	    
	```
	
	**_expiresIn_** : expresado en segundos o una cadena que describe un intervalo de tiempo.  
	Por ejemplo: 60, “2 days”, “10h”, “7d”. Un valor numérico se interpreta como un recuento de segundos. Si usa una cadena, asegúrese de proporcionar las unidades de tiempo (días, horas, etc.), de lo contrario, la unidad de milisegundos se usa de manera predeterminada ( “120” es igual a “120ms”).
	
	**Lo extraje del enlace proporcionado por el profe**

* **Alejandro González Reyes** (6)

	
	El punto importante en todo este apunte es Desacoplar nuestras aplicaciones. Backend || FrontEnd || Database.

* **Maximiliano Gabriel Minetto Fellosa** (4)

	
	Unas correcciones de ortografía, “esta” es en referencia a un objeto o persona y “está” es del verbo estar, presente indicativo en tercera persona.  
	[https://www.wordreference.com/conj/EsVerbs.aspx?v=estar](url)  
	😉

* **Felipe Acosta** (4)

	
	y si se le pone una expiracion al token, y el usario esta usando la app pero su token expira hay alguna manera de renovarselo sin que el usuario pierda la sesion ?,  
	no se si fui claro

	* **Daniel Esteves** (1)

		
		Lo que puedes hacer es verificar cuando el usuario esté conectado si el token va a expirar y crearle uno nuevo, normalmente he visto que los token duran un año en la sesión

* **Walter Lensinas** (4)

	
	¿Cómo es el control para saber que un token expiro? ¿Donde se asigna ese límite de tiempo?

	* **glrodasz** (6)

		
		Cuando se firma el token es posible mediante la opción **expiresIn** especificar el tiempo de expiración: <https://github.com/auth0/node-jsonwebtoken#jwtsignpayload-secretorprivatekey-options-callback> por defecto el metodo **jwt.verify** va a validar si el token no ha expirado.

* **Edwin Valencia** (3)

	
	Cómo puedo asegurar mejor un API, para que solo sea consumida desde ciertos clientes, a parte de CORS?  
	CSRF Token y JWT serían necesarios?

	* **Daniel Esteves** (2)

		
		Puedes hacerlo con CORS para que solo acepte peticiones de un dominio o aplicación a través de una key y así lo puedes asegurar

* **Wilson Fabian Pérez Sucuzhañay** (2)

	
	Pero como podemos hacer tokens con tiempo y auto refresh es decir que no nos que de la sesión sino que vuelva a pedir un token con otro tiempo ?

* **alejandrocepeda** (2)

	
	como puedo usar passport.js para otorgar permisos de tipo client authentication, clientes que no envian username ni password, por ejemplo un arduino, o aplicaiones de terceros.

	* **Daniel Esteves** (1)

		
		¿Podrías ser un poco más específico con la pregunta?

* **Andres Roberto Coello Goyes** (1)

	
	Llevo probando varias meneras de como hacer un session con JWT en SPA, SSR y eh tenido que guardar en localStorage veo que no es una buena forma. ahora aprendere con COOKIES

* **Daniel Hurtado** (1)

	
	Que pasa o que hacemos cuando queremos cerrar todas las sesiones abiertas de un usuario, o sea, invalidar todos sus tokens. Por ejemplo, en netflix cuando seleccionamos “cerrar sesión en todos los dispositivos”, al estar la info de la sesión solo en el cliente no podríamos manejarla en el backend. Cual sería una solución a esto?

	* **zach** (2)

		
		aca hay varios temas, lo recomendable es que los tokens no tengan un tiempo de vida muy prolongado, para que sea transparente para el usuario existe algo que se llama refresh token, este es un token especial que permite a la aplicacion solicitar un nuevo token cuando ya esta por vencer o ya ha vencido el que tiene la aplicacon, esto sin necesidad que el usuario ingrese sus crendenciales.
		
		en el caso que mencionas, el refresh token se pone en una blacklist de esta manera no puede requerir un nuevo token y requiere que el usuario vuelva a ingresar sus crendeciales.

	* **Daniel Hurtado** (1)

		
		@zach vale! me parece muy clara tu explicación, muchas gracias

## 0090. Buenas prácticas con JWT

### Descripción:


# Buenas practicas con JSON Web token

En los últimos años se ha criticado fuertemente el uso de JSON Web Tokens como buena practica de seguridad. La realidad es que muchas compañías hoy en día los usan sin ningún problema siguiendo unas buenas practicas de seguridad, que aseguran su uso sin ningún inconveniente.

A continuación listaremos unos consejos que se deben tener en cuenta:

## Evitar almacenar información sensible

Debido a que los JSON Web tokens son decodificables es posible visualizar la información del payload, por lo que ningún tipo de información sensible debe ser expuesto como contraseñas, keys, etc. Tampoco debería agregarse información confidencial del usuario como su numero de identificación o información medica, ya que como hablamos anteriormente, los hackers pueden usar esta información para hacer ingeniería social.

## Mantener su peso lo más liviano posible

Suele tenerse la tentación de guardar toda la información del perfil en el payload del JWT, pero esto no debería hacerse ya que necesitamos que el JWT sea lo más pequeño posible debido a que al enviarse con todos los request estamos consumiendo parte del ancho de banda.

## Establecer un tiempo de expiración corto

Debido a que los tokens pueden ser robados si no se toman las medidas correctas de almacenamiento seguro, es muy importante que estos tengan unas expiración corta, el tiempo recomendado es desde 15 minutos hasta un maximo de 2 horas.

## Tratar los JWT como tokens opacos

Aunque los tokens se pueden decodificar, deben tratarse como tokens opacos, es decir como si no tuviesen ningún valor legible. Esto es porque desde el lado del cliente no tenemos manera de verificar si la firma es correcta, así que si confiamos en la información decodificada del token, alguien podría introducir un token invalido con otra información a propósito. Lo mejor, es siempre enviar el token del lado del servidor y hacer las verificaciones allí.

## ¿Donde guardar los tokens?

Cuando estamos trabajando con SPA (Single Page apps) debemos evitar almacenar los tokens en Local Storage o Session Storage. Estos deben ser almacenados en memoria o en una Cookie, pero solo de manera segura y con el flag httpOnly, esto quiere decir que la cookie debe venir del lado del servidor con el token almacenado. Más información: <https://auth0.com/docs/security/store-tokens#single-page-apps>

## Silent authenticacion vs Refresh tokens

Debido a que es riesgoso almacenar tokens del lado del cliente, no se deberian usar Refresh Tokens cuando se trabaja solo con una SPA. Lo que se debe implementar es Silent Authentication, para ello se debe seguir el siguiente flujo:

  1. La SPA obtiene un access token al hacer login o mediante cualquier flujo de OAuth.
  2. Cuando el token expira el API retornara un error 401.
  3. En este momento se debe detectar el error y hacer un request para obtener de nuevo un access token.
  4. Si nuestro backend server tiene una sesión valida (Se puede usar una cookie) entonces respondemos con un nuevo access token.



Más información:

  * <https://auth0.com/docs/api-auth/tutorials/silent-authentication>
  * <https://auth0.com/docs/tokens/refresh-token/current>



> Hay que tener en cuenta que para implementar Silent authentication y Refresh tokens, se require tener un tipo de sesión valida del lado del servidor por lo que en una SPA es posible que sea necesario una especie de backend-proxy, ya que la sesión no debería convivir en el lado del API server.

> En el paso 2, si se esta usando alguna librería para manejo de estado como redux, se puede implementar un middleware que detecte este error y proceda con el paso 3.

### Comentarios:

* **Wilson Fabian Pérez Sucuzhañay** (3)

	
	Osea podría crear una sesión cuando hago login desde una SPA para que la cree en el Server ¿?

	* **Marco Antonio Macedo Preciado** (2)

		
		Sí. Tienes dos opciones, o creas un Server Render que se encargué de renderear toda la app o creas un Proxy Server que guarde los keys y que se comunique con el servidor principal.

* **Jesús Miguel Quinto Teran** (1)

	
	No comprendí bien este punto, alguien me puede dar feedback:  
	**Silent authenticacion vs Refresh tokens**

	* **Cristobal Vega** (1)

		
		Hola, me parece que la diferencia entre uno y el otro es al momento de renovar el token, uno lo hace de manera “silenciosa” y el otro (supongo de alguna manera) lo hace de manera más abrupta. 😲

* **Daniel Hurtado** (1)

	
	Si el token expira, cómo se renueva automáticamente sin necesidad de loguear manualmente?

	* **Jesús Miguel Quinto Teran** (1)

		
		<h1>El enfoque mas seguro es cambiar el token con cada nueva solicitud HTTP; </h1>
		
		  1. El cliente enviar sus credenciales al back **(usuario, contraseña)** por HTTPS
		  2. El servidor Autentica al cliente y genera un HASH que se lo envia en la respuesta.
		  3. Ahora el cliente guarda el HASH (preferiblemente en una cookie httpOnly )
		  4. En una nueva solicitud HTTP el cliente envía el HASH
		  5. El back recibe el HASH lo valida y devuelve la información solicitada junto con un nuevo HASH
		  6. volver al paso (3)…
		
		
		
		<br>  
		<br>

	* **Jesús Miguel Quinto Teran** (1)

		
		Lo correcto es que una vez expirado el token, te pida nuevamente el logeo, eso evita dejar “sessiones” (entre comillas) abiertas.
		
		**Un ejemplo de esto son los sistemas bancarios.**

	* **Daniel Hurtado** (1)

		
		Repetir el logueo, para tu ejemplo de banco es perfecto, pero para redes sociales u otros sistemas donde la seguridad estricta no es necesaria, es completamente una molestía, y en esos casos es a los que me refería

* **Alejandro González Reyes** (1)
No me queda claro lo de tokens opacos

	* **glrodasz** (1)

		
		Se dice que es un token opaco cuando su contenido no tiene representación de datos. En el caso de los JWT estos pueden ser decodificarlos y explorados como objetos JSON. La idea es no decodificarlos en el cliente cuando no hay manera de verificar la firma.
		
		Si se usa encriptación asimetrica y se verifica la firma es valido decodificarlos y hacer uso del payload en el cliente.

# Entender cómo funcionan las cookies

## 0100. ¿Qué son las cookies y cómo implementar el manejo de sesión

### Descripción:


Una _cookie_ es un archivo creado por un sitio web que tiene pequeños pedazos de datos almacenados en él. Su propósito es identificar al usuario mediante el almacenamiento de su historial.

Las _cookie session_ son cookies que tienen un corto periodo de vida ya que son removidas cuando el navegador o la pestaña se cierran.

Las _persistent cookies_ se usan generalmente para guardar información de interés para el usuario.

Las _secure cookies_ almacenan datos de forma cifradas para que terceros no puedan tener acceso a ellas, se suelen usar en conexiones **HTTPS** (Conexiones seguras).

Hay leyes sobre cookies que debes seguir al pie de la letra:

  1. Avisarle al usuario que estás haciendo uso de cookies en tu sitio para guardar información
  2. Es necesario que el usuario de su consentimiento para manejar cookies en tu sitio



### Links:

* [nodemon  -  npm](https://www.npmjs.com/package/nodemon)

* [JSON Viewer - Chrome Web Store](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh)

* [GitHub - glrodasz/platzi-auth-passport at que-son-las-cookies-y-como-implementar-el-manejo-de-sesion](https://github.com/glrodasz/platzi-auth-passport/tree/que-son-las-cookies-y-como-implementar-el-manejo-de-sesion)

### Comentarios:

* **jasanhdz** (5)

	
	Si tienes dificultad en entender algún concepto te invito a checar mis notas del curso:  
	<https://github.com/JasanHdz/passportjs/blob/master/notes/notes.md>  
	Si te gusto mi contenido dejame una ⭐ en mi repositorio. 😄

	* **Daniel Alberto Esquinazi** (4)

		
		Muy completas las notas, lo que no vi es una referencia a Guillermo y este curso de Platzi.

* **Leonardo Rodrigues** (5)
Mardicion guillermo es el mejor profesor de platzi lo amo

	* **Jesús Miguel Quinto Teran** (1)

		
		Tu como que eres de Maracaibo (VE)… 😃

* **Alejandro González Reyes** (4)

	
	Recomiendo la extensión EditThisCookie de google chrome, esta buenísima para saber las caracteristicas de las cookies que envía la página actualmente activa

* **giothcode** (2)

	
	Una lectura de npm: [](https://www.npmjs.com/package/express-session)  
	Código de la clase.
	``` 
	    const express = require('express');
	    const session = require('express-session');
	    
	    const app = express();
	    
	    app.use(session({
	        resave: false,
	        saveUninitialized: false,
	        secret: "giothcode's secret"
	    }))
	    
	    app.get('/', (req, res) => {
	        req.session.count = req.session.count ? req.session.count + 1 : 1;
	        res.status(200).json({ hello: 'world', counter: req.session.count })
	    })
	    
	    app.listen(3000, () => {
	        console.log('Listening http://localhost:3000')
	    })
	    
	```
	
	Y el _**package.json**_
	``` 
	    {
	        "name": "handle-session",
	        "version": "1.0.0",
	        "description": "",
	        "main": "index.js",
	        "scripts": {
	            "dev": "nodemon index.js",
	            "start": "node index.js"
	        },
	        "keywords": [],
	        "author": "",
	        "license": "ISC",
	        "dependencies": {
	            "express": "^4.17.1",
	            "express-session": "^1.16.2"
	        },
	        "devDependencies": {
	            "nodemon": "^1.19.1"
	        }
	    }```
	    
	```

* **JaimeRamos** (1)

	
	pero la cookie está siendo visible, cómo hago para que no?

	* **Gabriel De Andrade (Platzi)** (4)

		
		Para que querrías que las cookies no fuesen visibles? Las cookies las maneja el navegador y no puedes hacer que no sean visibles

	* **JaimeRamos** (1)

		
		bueno estaba pensando en que si en una cookie con el flag httponly true tenía un jwt con un identificador del usuario dentro de la base de datos (no el objectID de mongo si no otro que sirve para asi todos los casos), pues se pudiera descifrar la forma en la que mando datos o algo así y de alguna manera me pudiera vulnerar a pesar que no almanceno contraseñas ni nada por el estilo

	* **Gabriel De Andrade (Platzi)** (1)

		
		Recuerda que estos tokens son temporales y sólo son validados por la base de datos a través del backend. además si tienes algún cifrado el back es el que se encarga de todo esto. Es como cuando envías una contraseña, la contraseña se coloca en el form de login y puede ser interceptada en el front pero quien se encarga de validarla es el back.

* **Juan Carlos García Esquivel** (1)

	
	`npm init -y` : este comando crea un archivo **package.json** para manejar nuestras dependencias.  
	Para manejo de Cookies con express necesitamos dos paquetes, express y express-session :  
	`npm install express express-session`  
	Para refrescar nuestro servidor de desarrollo con cada cambio que realicemos utilizamos nodemon  
	`npm install -D nodemon`

* **Raul Contreras** (1)

	
	¿Que es esa extension de chrome para ver JSON?

	* **oqodigital** (2)

		
		JSON Viewer me imagino

* **Deyvis Neyser Valdez Gavilan** (1)
Hola al ejecutar la aplicación con npm run start, sale esta advertencia: Warning: connect.session() MemoryStore is not designed for a pro...

	* **glrodasz** (1)

		
		Es porque estas usando la memoria del servidor para almacenar la sesión. Para una aplicación en producción es mejor manejar una base de datos de sesiones, como por ejemplo Redis. Hay una lista de recomendaciones aquí: <https://github.com/expressjs/session/blob/master/README.md#compatible-session-stores>

* **Alejandro González Reyes** (1)
No me quedan claras las dos primeras opciones del Middleware session

	* **Juan David Castro (Platzi)** (1)

		
		Puedes estudiarlas a detalle en la documentación:
		
		👉 **`resave`** : <https://www.npmjs.com/package/express-session#resave>  
		👉 **`saveUninitialized`** : <https://www.npmjs.com/package/express-session#saveuninitialized>

* **Leonardo Rodrigues** (1)
Siempre se debe usar una cookie para el manejo de sesiones o solo es porque estamos usando JWT en una SPA y no podemos verificar el secre...

	* **Juan David Castro (Platzi)** (1)

		
		En esta clase se explican las diferencias y diferentes casos de uso: [Cookies vs Session Storage vs Local Storage](https://platzi.com/clases/1649-passport/21982-cookies-vs-session-storage-vs-local-storage/). 😉

## 0110. Cookies vs Session Storage vs Local Storage

### Descripción:


El **Local Storage** tiene un almacenamiento máximo de 5MB y la información no se va con cada request al servidor, la información va a persistir aunque cerremos el navegador.

El **Session Storage** es similar al _Local Storage_ solo que la información está disponible por pestaña o por la ventana del navegador. La información estará disponible solo en esa pestaña.

Las **Cookies** tienen solo un almacenamiento de 4KB, se les puede establecer un tiempo de expiración, la desventaja de usarlo es que al hacer request de imágenes o datos las _cookies_ van junto con la petición.

_**Si la información no es sensible podemos almacenarla en Local Storage o en Session Storage**_.

### Comentarios:

* **giothcode** (4)

	
	Implementaría cookies, la información del usuario que se puede ver comprometida debe manejarse en el servidor, además podemos darle un tiempo de vida a la cookie.
	
	agrego una lectura de MDN.  
	<https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies>  
	[](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

* **Alejandro González Reyes** (3)

	
	Yo lo haría en cookies, pero que sean de session. Tener la referencia del ID en la cookie, pero la data en una variable de session del lado del servidor

* **Manuel Ojeda** (3)

	
	Cookies, simplemente el hacer un inicio de sesión ya es información sensible que debe de ser resguardado.

* **Deyvis Neyser Valdez Gavilan** (2)

	
	Utilizaría Cookies, ya que la información a almacenar es sensible, como nombres de usuario, contraseñas, datos que le permitan autentificar al usuario.

* **rusbel bermúdez rivera** (2)

	
	Utilizaría Cookies con flag httpOnly, ya que sería necesario manejar información sensible del usuario,

	* **albertodsosa** (1)

		
		Me sumo al comentario del compañero para no redundar.

* **pabloverduzcos** (2)

	
	 **Cookies.** Almacenar informacion muy sensible.  
	.  
	**Lacal Storage - Session Storage.** Almacenar informacion NO sensible.  
	.  
	**Session Storage.** Almacenar datos medianamente sensibles.  
	.

* **mariiglesia** (2)

	
	Si la información es sensible es recomendable almacenarla en las Cookies.

* **Matias Sebastian Perez** (2)

	
	Yo implementaria la autenticacion en las cookies

* **GibsonR** (1)

	
	Las Cookies serían lo ideal, porque la información es sensible a violaciones de seguridad.

* **Eden Gomez Gress** (1)

	
	Yo usaria cookies por que es mas seguro. Tanto Session storage como Local storage creo no son optimas para una autenticacion de usuario

* **Andres Roberto Coello Goyes** (1)

	
	siempre he utilizado localStorage pero veo que puede ser mejor cookie.

* **XXVSebastianVXX** (1)

	
	Trabajaría con Cookies ya que se esta manejando informacion sensible del usuario.

* **Alex Junior Rodriguez Huerta** (1)

	
	Escogería usar Cookies, ya que son datos sensibles, teniendo en cuenta los flag HttpOnly, además tendría en cuenta que estas cookies no saturen mi almacenamiento.

* **crimiro** (1)

	
	Cookies
	
	  * Estamos manejando información sensible
	  * Podemos añadir un tiempo de expiración a la sesión
	
	

* **Jesús Miguel Quinto Teran** (1)

	
	Trabajaría Mediante Cookies, pero con la salvedad de remover la autentificaciòn en el servidor, después de un periodo de inactividad.

* **pablopoggiog** (1)

	
	 **Lo guardaria en una cookie por 3 motivos:**
	
	-Al ser informacion sensible (no solo usuario, si no tambien clave) es lo mas adecuado guardarla aqui, con el flag de HttpOnly.  
	-Sobrevive a cierres de tab/window.  
	-Podemos indicarle de forma mas “natural” un tiempo de expiracion.

* **IngridSagrero** (1)

	
	Usaría cookies con el flag HttpOnly para que sean enviadas al servidor y sean accesibles sólo ahí.

* **Mauricio Iván Martínez Carmona** (1)

	
	Yo me inclinaría por usar **Cookies** , porque estamos almacenando información de autenticación que es sensible.

* **Emmanuel Rodríguez Ramírez** (1)

	
	Por uso, ocuparía Cookies pero al ser información sensible, la podría encriptar con Hash [](https://www.npmjs.com/package/object-hash) o con Encrypt [](https://www.npmjs.com/package/cryptr)

* **solej77** (1)

	
	Utilizaria cookie, ya que de esta manera, aunque cerremos el navegador, la cookie va a persistir y como es información sensible, es la mejor manera de tartar este tipo de información.  
	Saludos!!!

* **AryRosvall** (1)

	
	Solución al reto:
	
	Yo usaría cookies.
	
	¿Por qué?
	
	  * La información de autenticación es altamente sensible.
	  * Las cookies pueden ser encriptadas y pueden usar el protocolo https.
	
	

# Implementar autenticación en Express usando Passport.js

## 0120. Arquitectura del proyecto Platzi Video

### Descripción:


Nuestro proyecto va a depender de un API Server, el cual fue construido en el Curso de Backend con Node.js. Este tiene un CRUD de películas, añadido a esto nosotros vamos a crear un _endpoint_ para registrar e iniciar la sesión de nuestros usuarios.

### Links:

* [Curso de Backend con Node.js | Materiales](https://platzi.com/clases/backend-nodejs/)

* [GitHub - glrodasz/platzi-auth-passport at arquitectura-del-proyecto-platzi-video](https://github.com/glrodasz/platzi-auth-passport/tree/arquitectura-del-proyecto-platzi-video)

### Comentarios:

* **David Behar** (4)

	
	`Nota importante`:, al hacer clon del proyecto se debe de crear un .env con la configuración del proyecto, para ésto deberán de crear un servidor de mongo que reaccione, pero lo mejor sería ver el curso de [backend con node](https://platzi.com/clases/backend-nodejs/)

* **David Behar** (2)

	
	## Arquitectura del proyecto Platzi Video
	
	Se va a desarrollar un sistema de **autenticación con passport.js** en el que nos conectemos con un API Server teniendo en cuenta los permisos de lectura y/o escritura que tengas.
	
	El API Server sólo tendrá un **CRUD** (Create, Read, Update, Delete), para el caso de escuela de JS será un **CRUD de películas**.
	
	Además crearemos **2 nuevos endpoints** , 1 de ingreso ( **signIn** ) y otro de registro ( **signUp** )
	
	## API Token
	
	Se crearán 2 tipos de **Access token** :
	
	  1. **Admin client** : permisos administrativos ( **CRUD** películas)
	
	  2. Render Server: permisos de sólo **lectura** (R películas)
	
	
	
	
	Al hacer una autenticación se va a generar un access token, con el estándar de JWT (JSON Web Token), mismo que mantendrá los permisos.
	
	## Reglas
	
	La aplicación ( **SPA** , single page application) se va a comunicar a través del **Render Server** (de sólo lectura) mismo que se comunicará con el **API Server**
	
	El **server** que crearemos hará de proxy entre la **SPA** y el **API server**
	
	La **SPA** se comunicará con el **API server** mediante una **cookie** con el **access token** del **render server**

* **Eden Gomez Gress** (1)

	
	Saludos companeros. alguien sabe porque cuando hago una peticion GET no me rgresa nada en el array data[]?
	
	![](https://snipboard.io/gVrehs.jpg)

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Si no te da error, lo único posible es que no tengas info en ese array o haya un error en la consulta a mongo.

	* **Luis Rodriguez** (2)

		
		Justo! Al comienzo tu base de datos no tendrá nada de información. En la clase <https://platzi.com/clases/1649-passport/21988-configuracion-de-passportjs/> , Guillermo explica cómo sube la data inicial que usa este proyecto.
		
		O puedes agregar la data manualmente en tu base de datos de Mongo.

	* **Eden Gomez Gress** (2)

		
		Ok es que pense que como en e projecto se tiene una carpeta “mocks” con el archivo “movies.js” contiene peliculas, pense que esas mismas peliculas me las tiene que devolver, voy a seguir  
		con el curso entoces, Muchas gracias por responder companeros

* **rusbel bermúdez rivera** (1)

	
	para aquellos que copien el proyecto existente de un folder a otro y tengan error (a mi me pasó con nodemon) hice en consola
	``` 
	    npm rebuild
	    
	```
	
	desconozco sí sea buena practica

* **Eden Gomez Gress** (1)
Disculpen companeros pero baje el proyecto del enlace que deji el profesor. ya llene las variables que se enuentran en el archivo. env.ex...

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Hola al parecer en la variable que estas pasando esta llegando algo que no es una url valida. Puedes compartir los datos que estas poniendo en el .env

* **jldamians** (1)
Interesante. Tengo un caso de uso, espero puedan aclararme la duda. Orientando el desarrollo a microservicios, tengo un API con los WS pa...

	* **glrodasz** (1)

		
		Es una posible solución, te recomiendo que revises “Client Credentials” de OAuth 2.0

* **Enrique Devars (Platzi)** (1)
Por que es obligatorio que tenga un render server nuestro frontend?

	* **Manuel Ojeda** (1)

		
		Para que funcione el Server Side Rendering y disfrutar de sus beneficios.  
		Además de poder realizar los procedimientos de login en el servidor de tender.

## 0130. Agregando la colección de usuarios

### Descripción:


### Links:

* [GitHub - glrodasz/platzi-auth-passport at agregando-la-coleccion-de-usuarios](https://github.com/glrodasz/platzi-auth-passport/tree/agregando-la-coleccion-de-usuarios)

### Comentarios:

* **Juan Carlos García Esquivel** (8)

	
	En windows 10 tube muchisimos problemas para instalar bcrypt por lo siguiente :
	
	  * mi terminal de hyper corre sobre ubuntu pero mi SO es W10.
	  * cuando trate de instalar bcrypt npm trataba de descargar la versión para linux porque detectaba el SO a través de la terminal y esto me daba un error de compatibilidad.
	  * lo solucione instalando **bcryptjs**  
	**`npm install bcryptjs`**  
	El import quedaria asi **`const bcrypt = require('bcryptjs')`**  
	Me tarde casi dos días en encontrar el problema de esta dependencia en mi caso particular, espero que si alguien tiene el mismo problema lo pueda resolver con esta solución 😃.
	
	

* **Alejandro González Reyes** (4)

	
	Si algo me gusta de ExpressJS es que te permite organizar tu proyecto con la estructura que se acople a tus necesidades. Laravel me gusta, pero, debes seguir una serie de reglas en la organización del proyecto.

	* **Ezequiel Guerra** (2)

		
		Actualmente con PHP también puedes armar una estructura parecida si utilizas inyección de dependencia , puedes utilizar tus middlewares preferidos, manejador de rutas, servicios, etc.  
		Claro express lo hace mucho más simple.

	* **romerodiesan** (1)

		
		Lo que no me gusta de php es que corre en apache. Yo prefiero crear el servidor con el mismo lenguaje, modificarlo a mis necesidades y tener mayor control sin la necesidad de tener que aprender apache también además de php.

* **ejgachancipa** (2)

	
	¿Por qué no usar mongoose?

* **Alejandro González Reyes** (2)
Me pregunto si Async/Await es necesario si tenemos la base de datos instalada en local. Ya que dependiendo de la cantidad de datos, la co...

	* **Marco Antonio Macedo Preciado** (3)

		
		Al final Async/Await es una manera de manejar promesas, y manejar promesas es necesario para evitar bloquear el flujo de ejecución del código en operaciones pesadas (como consultar a tu base de datos).

* **David Behar** (1)

	
	Esta clase hicimos el servicio de **obtención y creación de usuarios** conectándonos a nuestra librería de MongoLib creada en el curso de [Backend con node](https://platzi.com/clases/backend-nodejs/).  
	.  
	Los sevicios que creamos fueron el de **obtención de usuarios**
	``` 
	    async getUser({ email }) {
	        const [user] = awaitthis.mongoDB.getAll(this.collection, { email });
	        return user;
	      }
	    
	```
	
	y el de **creación de usuarios**
	``` 
	    async createUser({ user }) {
	        const { name, email, password } = user;
	        const hashedPassword = await bcrypt.hash(password, 10);
	        //Creates an user and returns the userId for reference.
	        const createUserId = awaitthis.mongoDB.create(this.collection, {
	          name,
	          email,
	          password: hashedPassword,
	        });
	        return createUserId;
	      }
	    
	```
	
	Para poder hacer la validación de la información creamos el **schema** **user.js** con la librería [joi](https://www.npmjs.com/package/@hapi/joi)
	
	[Acá el commit con ésto](https://github.com/behagoras/passport-authentication/commit/f7c599e1e729199df4d6726b6b62360f508c20e8)

* **phvillegas** (1)

	
	Alguien sabe ¿Que diferencia hay entre bcryptjs y bcrypt?

	* **Demian Arenas (Platzi)** (2)

		
		Hola, que buena pregunta!
		
		Bcrypt como sabes es un módulo que viene incluido en Node.js y está escrito en C++, por otro lado bcryptjs esta escrito en JavaScript puro. Bcrypt es mucho más rápido que bcryptjs, pero solamente puede correr dentro de Node.js o Electron.

## 0140. Agregando la colección de películas de usuario

### Descripción:


### Links:

* [GitHub - glrodasz/platzi-auth-passport at agregando-la-coleccion-de-peliculas-de-usuario](https://github.com/glrodasz/platzi-auth-passport/tree/agregando-la-coleccion-de-peliculas-de-usuario)

### Comentarios:

* **Leonardo Rodrigues** (7)
Colocaste app.user en ves de app.use

* **David Behar** (3)

	
	Para esta clase creamos el servicio de userMovies.js teniendo en cuenta una relación de [muchos a muchos](https://en.wikipedia.org/wiki/Many-to-many_\(data_model\)), en la que un usuario podrá tener muchas películas favoritas, y una película podrá ser favorita de muchos usuarios.
	
	[(Ver más información sobre relaciones de base de datos en mongo)](https://www.quackit.com/mongodb/tutorial/mongodb_create_a_relationship.cfm)
	
	Definimos los servicios, así como los schemas de **Ver, Crear y eliminar** la relación de usuarios y películas ( **userMovies** ), muy similar a lo que hicimos en la [colección de usuarios](https://platzi.com/comentario/817145/).
	
	Para crear la Ruta del Api de getUserMovies, consumimos el servicio userMoviesService.getUserMovies con el userId de la siguiente manera.
	``` 
	    router.get('/', validationHandler({ userId: userIdSchema }, 'query'),
	        async (req, res, next) => {
	          const { userId } = req.query;
	    
	          try {
	            const userMovies = await userMoviesService.getUserMovies({ userId });
	            res.status(200).json({
	              data: userMovies,
	              message: 'user movies listed',
	            });
	          } catch (error) {
	            next(error);
	          }
	        });
	    
	```
	
	[Ver commit referente a la clase](https://github.com/behagoras/passport-authentication/commit/f3120034758b0e67b660b2d612163d2946d07300)

	* **Alan Alexis Arostegui Maranto** (2)

		
		Gracias por el resumen dude!

* **David Behar** (1)
¿Cuál es la sintáxis que utilizamos al hacer un query?

	* **glrodasz** (1)

		
		No estoy muy seguro la pregunta, pero es posible que te refieras al Destructuring: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment> o Shorthand properties: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer#New_notations_in_ECMAScript_2015>.

## 0150. Implementando el POST y DELETE de las películas de usuario

### Descripción:


### Links:

* [GitHub - glrodasz/platzi-auth-passport at implementando-el-post-y-delete-de-las-peliculas-de-usuario](https://github.com/glrodasz/platzi-auth-passport/tree/implementando-el-post-y-delete-de-las-peliculas-de-usuario)

### Comentarios:

* **David Behar** (4)

	
	Para esta clase implementamos la **creación** y **eliminación** de relaciones ( **películas de usuario** ) siguiendo la misma lógica que para el [listado de elementos](https://platzi.com/comentario/817324/).
	
	.
	
	**Implementación de la ruta post**
	``` 
	    router.post(
	       '/',
	       validationHandler(createUserMovieSchema),
	       async (req, res, next) => {
	         const { body: userMovie } = req;
	         try {
	           const createdUserMovieId = await userMoviesApi.createdUserMovieId({
	             userMovie,
	           });
	    
	           req.status(201).json({
	             data: createdUserMovieId,
	             message: 'user movie created',
	           });
	         } catch (err) {
	           next(err);
	         }
	       },
	     );
	    
	```
	
	**Implementación de la ruta de delete**
	``` 
	    router.delete(
	        '/:userMovieId',
	        validationHandler({ userMovieId: movieIdSchema }, 'params'),
	        async (req, res, next) => {
	          const { userMovieId } = req.params;
	          try {
	            const deletedUserMovieId = await userMoviesService.deleteUserMovies({
	              userMovieId,
	            });
	    
	            res.status(200).json({
	              data: deletedUserMovieId,
	              message: 'user movie deleted',
	            });
	          } catch (error) {
	            next(error);
	          }
	        },
	      );
	    
	```
	
	Para finalizar con el. llamado de nuestro endpoints en la raiz de nuestro proyecto (index.js)
	``` 
	    const userMoviesApi = require('./routes/userMovies');
	    
	    app=express();
	    
	    userMoviesApi(app);
	    
	```
	
	[Ver commit referente a la clase](https://github.com/behagoras/passport-authentication/commit/303e89aeda021b47d3d2357ece0fe9d0986ed2ee)

* **rusbel bermúdez rivera** (1)

	
	esta clase fue un gran repaso del curso anterior de express, excelente clase *****

* **josdanind** (1)

	
	El tema para validar los request que se envían al server, se puede manejar con typeScript?

	* **Wilson Marino Pablo Mendez** (1)

		
		Sería bueno que utilizaran TypeScript.  
		.

	* **Juan Carrillo** (2)

		
		Tengo entendido que typeScript es más para validación de tipos mientras desarrollamos, lo que nos evita errores comunes en js con el manejo de los tipos de variables. En cambio la validación que se hace en los requests podría ser más específica, por ejemblo un nombre de usuario que como minimo tenga 3 carácteres y máximo 10, aplicar expresiones regulares, y muchos otros tipos de validaciones que tiene incluido [joi](https://hapi.dev/tutorials/validation/?lang=en_US#joi)

## 0160. Cómo conectarnos a la base de datos

### Descripción:


# Como conectarnos a la base de datos

**MongoDB Compass** es un cliente con interfaz grafica que nos permiten conectarnos a nuestras instancias de Mongo DB y manipularlas de una manera más facil. Con este cliente nos podemos conectar a una instancia de cualquier servidor incluso una instancia de MongoDB Atlas.

Para descargarlo se puede usar el siguiente enlace: <https://www.mongodb.com/download-center/compass>

## Conexión usando MongoDB Compass

Si nosotros copiamos el Mongo URI desde Mongo Atlas podemos conectarnos facilmente con MongoDB Compass:

  1. Iniciamos sesion en MongoDB Atlas <https://www.mongodb.com/cloud/atlas>
  2. Nos vamos a la sección de **Clusters** en el menu lateral izquierdo.
  3. Seleccionamos **connect** en nuestro cluster sandbox.
  4. Seleccionamos la opción **Connect with MongoDB Compass**.
  5. Si no tenemos MongoDB Compass instalado, podemos descargarlo desde alli. Si ya lo tienes instalado continua con el paso 5.
  6. Le damos click en el boton **copy** para copiar el Mongo URI.
  7. Abrimos **MongoDB Compass** e inmediatamente va a reconocer nuestra URI que tenemos en el portapapeles.
  8. Hacemos click en **yes** para que nos cree una nueva conexión, pero es necesario introduccir el **password** del usuario de la base de datos.
  9. Podemos ponerle un nombre favorito y darle en **Create favorite** y luego en **Connect**.

![mongodb-compass.png](https://static.platzi.com/media/user_upload/mongodb-compass-0dfded16-0917-46f8-935d-f35b86306a57.jpg)

### Comentarios:

* **Andres Roberto Coello Goyes** (1)

	
	**MongoDB Compass** es muy bueno para trabajar en modo local de nuestra pc…

## 0170. Configuración de Passport.js

### Descripción:


 **Passport.js** es un _middleware_ para _express_ que nos permite implementar estrategias de autenticación de una manera rápida y simple.

### Links:

* [jsonwebtoken  -  npm](https://www.npmjs.com/package/jsonwebtoken)

* [passport  -  npm](https://www.npmjs.com/package/passport)

* [passport-http  -  npm](https://www.npmjs.com/package/passport-http)

* [passport-jwt  -  npm](https://www.npmjs.com/package/passport-jwt)

* [chalk  -  npm](https://www.npmjs.com/package/chalk)

* [KeyGen.io - Random Key Generator](https://keygen.io/)

* [Passport.js](http://www.passportjs.org/)

### Comentarios:

* **Favio Sauto** (13)

	
	[Aquí](https://github.com/FavioSauto/movies-api/tree/master/scripts/mongo) pueden descargar o guiarse para terminar los scripts de esta clase.
	
	y estos son los tres comandos que se necesitan para correr cada uno de los scripts en Windows 10:
	
	seedApiKeys.js  
	set DEBUG=app:* && node scripts/mongo/seedApiKeys.js
	
	seedMovies.js  
	set DEBUG=app:* && node scripts/mongo/seedMovies.js
	
	seedUsers.js  
	set DEBUG=app:* && node scripts/mongo/seedUsers.js

	* **Javier Fuentes Mora** (1)

		
		Me funcionotodo menos el chalk sabras porque?

	* **Favio Sauto** (1)

		
		Hey Javier, no sabría decirte por qué no te funcionó el chalk, si mal no recuerdo creo que yo igual tuve problemas con esa librería en su momento, de todas formas no es tan importante para el desarrollo del proyecto ya que su función es darle colores a los mensajes de la consola.

	* **Carmen Sánchez Salgado** (1)

		
		Gracias por el aporte.
		
		En tu archivo seedUsers,js hay un error:
		``` 
		    const bcrypt = require('bcryptjs')
		    
		```
		
		debe ser
		``` 
		    const bcrypt = require('bcrypt');
		    
		```

	* **Rubén Jiménez Torres** (1)

		
		Gracias!!! pude entender mejor el código.  
		y no es error esto:
		``` 
		    const bcrypt = require('bcryptjs')
		    
		```
		
		Porque es una librería que hace lo mismo y se llama así.

* **giothcode** (11)

	
	Librerias instaladas:  
	**_passport_** ,  
	**_jsonwebtoken_** ,  
	**_passport-http_** ,  
	**_passport-jwt_** ,  
	**_chalk_**.
	
	_Comandos **npm** :_  
	_npm i passport jsonwebtoken passport-http passport-jwt_.  
	_npm i -D chalk_.

* **Iván Darío Sánchez Jiménez** (9)

	
	Repositorio del curso para descargar los scripts
	
	[platzi-auth-passport](https://github.com/glrodasz/platzi-auth-passport)

* **Luis Rodriguez** (4)

	
	Les comparto la extension de VSC por si no tenían el “change camel case”.
	
	<https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case>

* **Andres Felipe Valencia Benitez** (3)

	
	No me quedó claro el concepto de API KEYS!

	* **David Behar** (1)

		
		En este caso lo que estamos haciendo es definir en nuestras variables de ambiente ( **env** ) que sólo permitiremos el acceso a **llamadas de la API** que estén **firmadas con la llave** (api_key),  
		.  
		El **api key** es una **llave** que definimos en el servidor para **abrir** el acceso a nuestro servicio, así, si algún servicio en internet no tiene la llave que estás definiendo, no podrá acceder a tu servicio

* **Alejandro González Reyes** (3)

	
	Interesante aporte del profesor, analizando el código es evidente el poder de las promesas, pero sobre todo, esperar a que todas se resuelvan para dar por terminado la ejecución del script o lanzar un error.  
	Por cierto, en Linux es funcionan ambos comandos para ejecutar el script en modo debug, pero chalk funciona con  
	DEBUG=app:* node ruta_del_script

* **David Lara Chirinos** (2)

	
	Por si quieren copiar y pegar!
	``` 
	    npm i passport jsonwebtoken passport-http passport-jwt
	    
	```
	``` 
	    npm i -D chalk
	    
	```

* **Eden Gomez Gress** (2)

	
	Buen dia companeros, alguien sabe porque me da este error cuando trato de crear los usuarios?.
	``` 
	    movies-api git:(master) ✗ DEBUG=app:* node scripts/mongo/seedUsers.js
	      app:scripts:users Error: Illegal arguments: undefined, number +0ms
	    
	```

	* **Luis Rodriguez** (1)

		
		@Eden, la razón es que en tu repositorio no tienes el archivo que se está llamando.
		
		Esto es lo que necesitas agregar a tu repositorio:  
		<https://github.com/glrodasz/platzi-auth-passport/tree/configuracion-de-passportjs/movies-api/scripts/mongo>
		
		Dentro de las carpetas de scripts/mongo están los archivos seedUsers.js , seedApiKeys.js y seedMovies.js .
		
		Necesitas tener estos archivos para correr el programa.
		
		Me avisas si aún tienes problemas!

	* **Eden Gomez Gress** (1)

		
		Saludos companero @iamluisro Mira te comento que ya subi los archivos pero aun asi me sigue arrojando ese error cuando trato de crear la DB de usuarios

* **rusbel bermúdez rivera** (2)

	
	Buena clase, aunque con el el script de seedUsers nunca pude obtener el _id de mongo

* **XXVSebastianVXX** (2)

	
	Solo por si las dudas, recuerden crear la colección de ‘users’ en caso de que no la tengan, si no la tienen no se agregan los usuario o por lo menos a mi me paso eso jaja

	* **Eden Gomez Gress** (1)

		
		disculpa comapero, donde debemos de crear la coleccion de users? Tengo un problema en la creacion de usuarios y me llamola atencion tu comentario

* **Juan Carlos García Esquivel** (2)

	
	Los API_KEYS se utilizan para consultar a la base de datos los permisos necesarios para cada tipo de usuario y poder generar un JWT.  
	Cuando se registra un usuario **normal** se manda el **PUBLIC_API_KEY_TOKEN** entonces se consultan los permisos en Mongo para esa api key ya que se requiere que ese usuario tenga los permisos “normales”, una vez registrado se crea el JWT y se le asignan esos permisos.
	
	Cuando se registrar un usuario administrador se envía el **ADMIN_API_KEY_TOKEN** y se consultan los permisos en Mongo para esa api key que como es tipo ADMIN generalmente tiene todos los permisos, una vez registrado se crea el JWT y se le asignan esos permisos.

* **Andrés Mauricio Montoya Sánchez** (2)

	
	Si están usando la consola para entrar a su instancia de Mongodb, la colección “api-keys” tiene “-”, por lo cual, debe de ser llamada como “db[“api-keys”].find()” para que muestre los datos.

* **Alejandro González Reyes** (2)
Tengo una duda, porque se usa Promise.all( ) si claramente se le esta indicando dentro del mapeo del arreglo que se va a usar async/await...

	* **Juan David Castro (Platzi)** (3)

		
		👋 Hey!
		
		**`Promise.all`** devuelve una promesa que termina correctamente cuando **todas las promesas** que le enviamos como argumento han terminado correctamente. Y obviamente, falla cuando alguna de estas promesas no terminó bien.
		
		👉 <https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Promise/all>

* **ValentinGutierrez** (1)

	
	Por el momento no es muy tedioso el curso

* **Alejandro González Reyes** (1)
Porque es importante generar esos tokens en la aplicación. He observado muchos servicios que te piden el que te registres y posteriorment...

	* **Juan David Castro (Platzi)** (1)

		
		Estas clases del [Curso de Autenticación con OAuth](https://platzi.com/clases/1439-autenticacion-oauth/15820-conociendo-el-api-de-spotify/) te pueden ayudar a entenderlo un poco mejor. Mejor si tomas todo el curso. 😉
		
		👉 [Stack de seguridad para aplicaciones modernas](https://platzi.com/clases/1439-autenticacion-oauth/15807-stack-de-seguridad-para-aplicaciones-modernas/)  
		👉 [¿Qué es OAuth 2.0?](https://platzi.com/clases/1439-autenticacion-oauth/16036-que-es-oauth-20/)  
		👉 [Conociendo el API de Spotify](https://platzi.com/clases/1439-autenticacion-oauth/15820-conociendo-el-api-de-spotify/)

* **Alejandro González Reyes** (1)
Alguno de ustedes conoce algún Middleware o librería para generar seeds en expressjs como lo hace laravel

	* **Manuel Ojeda** (3)

		
		No como tal pero puedes hacer tus seeds y ejecutar los scripts.
		
		Venía pensando lo mismo para crear las migraciones tipo Laravel con Express

## 0180. Implementación de BasicStrategy con Passport.js

### Descripción:


Aprende más en el Curso de Autenticación con Passport.js disponible con tu suscripción en: <https://platzi.com/passport/>. Adquiere hoy tu suscripción a Platzi en: <http://platzi.com/precios/>.

En esta clase el profesor Guillermo Rodas nos explicará cómo podemos hacer estrategias de autenticación utilizando Passport.js. Usando esta librería podremos obtener mayor seguridad en nuestra aplicación para autentificar usuarios.

Passport.js es un middleware para express que nos permite implementar estrategias de autenticación de una manera rápida y simple.

### Links:

* [GitHub - glrodasz/platzi-auth-passport at implementacion-de-estrategia-basica-en-passportjs](https://github.com/glrodasz/platzi-auth-passport/tree/implementacion-de-estrategia-basica-en-passportjs)

### Comentarios:

* **Alejandro González Reyes** (3)

	
	Ahora es mas facil con el uso de async/await, recuerdo un libro de ExpressJS que hacía uso de passportJS, y en el código se hacía uso frecuente de callbacks,

	* **Javier Fuentes Mora** (1)

		
		es algo qque yo sigo isn entender se supoone que los callback ponian ser reemplazados por promises o por async await , pero aqui dice algo de los callback y despues le pone async await es algo que no entinedo :C

	* **jorgeoxi** (1)

		
		Promesas y async await siguen siendo en esencia “callbacks” pero de una manera mucho más compacta, legible y fácil de entender y escribir. Al principio es algo complicado de entender, pero con el tiempo y leyendo documentación y viendo ejemplos, se va entendiendo el concepto de “callback”

* **carlos galvan grajales** (2)
Una pregunta, el ssr_server donde debe de alacenar la password para hacer el silent_authentication? en el mismo Token que a su vez debe d...

	* **glrodasz** (1)

		
		¿Podrías mostrarnos tu implementación de Silent authentication, para tener una mejor idea y responderte correctamente?

* **David Behar** (1)
Qué son las BasicStrategies?

	* **mafevito** (1)

		
		Hola David
		
		En la [documentación](http://www.passportjs.org/docs/basic-digest/) explica más acerca de ello

## 0190. Implementación de Strategy y ExtractJwt con Passport.js

### Descripción:


### Links:

* [GitHub - glrodasz/platzi-auth-passport at implementacion-de-estrategia-jwt-en-passportjs](https://github.com/glrodasz/platzi-auth-passport/tree/implementacion-de-estrategia-jwt-en-passportjs)

### Comentarios:

* **YorchK** (3)
Como se implementa passport.js usando nginx en lugar de express? Que partes debo cambiar?

	* **glrodasz** (3)

		
		Hola @YorchK, realmente Passport.js es una libreria que esta creada para Express.js, es decir que no puedes usarla si no es para un servidor con Express. Teoricamente podria usarse sin Express, pero al menos necesitarias un servirdor con Node.js. Por otro lado, NGINX funciona en otra capa del servidor, asi que me gustaria entender que es lo que tratas de hacer.

* **Camilo Andrés Santana Lizcano** (1)

	
	Hola **Platzinauta** !😄  
	Puedes ver esta clase en formato de lectura explicada paso a paso [aquí](https://platzi.com/tutoriales/1649-passport/4987-estrategia-de-jwt-passport/)

* **Javier Fuentes Mora** (1)

	
	no entiendo porque jalamos el JWT de .env que no se supone que eso lo debería de generar el backend ,o dodne el usuario va a genrar el suyo o donde lo va a almacenar ??

	* **Iván Darío Sánchez Jiménez** (4)

		
		Lo que trae de las variables de entorno es el secret para desencriptar el JWT, no es JWT como tal.

## 0200. Implementación de nuestro Sign-in

### Descripción:


### Links:

* [JSON Web Tokens - jwt.io](https://jwt.io)

* [GitHub - glrodasz/platzi-auth-passport at implementacion-de-nuestro-sign-in](https://github.com/glrodasz/platzi-auth-passport/tree/implementacion-de-nuestro-sign-in)

### Comentarios:

* **jasanhdz** (9)

	
	Si tienes dificultad en entender algún concepto te invito a checar mis notas del curso:  
	<https://github.com/JasanHdz/passportjs/blob/master/notes/notes.md>  
	Si te gusto mi contenido dejame una ⭐ en mi repositorio. 😄

* **Javier Fuentes Mora** (2)

	
	a que se refiere con esto? “como es un custom Callback, debemos hace un Clousure con la firma de la ruta.”

	* **oscar-leon846** (3)

		
		Un closure o clausura es la combinación de una función y el ámbito léxico en el que se declaró dicha función. Es decir los closures o clausuras son funciones que manejan variables independientes. En otras palabras, la función definida en el closure “recuerda” el ámbito en el que se ha creado.

* **Enrique Devars (Platzi)** (2)
como podría enviar en vez de una respuesta json una cookie a mi frontend?

	* **Andres Roberto Coello Goyes** (1)

		
		lo mismo quiero hacer yo en estos momentos, tengo el frontend en NEXT JS

* **SaFeRamirez** (2)
¿Me pueden explicar porque el custom callback debe repetir el (req, res, next) ?

	* **AlexGarrixen** (2)

		
		Hola,esto se debe a que el custom callback es un closure, y por eso se le pasa como argumento el objeto request,respose y next para que pueda acceder a estos.

* **jesus-olivares661** (1)

	
	la SPA que cargará ese ApiKeyToken… Tengo que hardcodearle el ApiKeyToken en el front ó tengo que hacer un servicio para que al cargar la página la consulte…?

* **jesus-olivares661** (1)

	
	no entiendo porque uso el método login… De dodne viene…?  
	req.login( , , )

	* **Franco Correa** (1)

		
		Lo “inyecta” passport al conectar su middleware.

* **Eden Gomez Gress** (1)
saludos companeros. Alguien sabe porque me da este eroor cuando corro el comando “npm run dev”?: throw new TypeError('JwtStrategy ...

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Lo que menciona el error es que falta que asignes un secret o una key en la configuración de JWT para ser usado por JWTStrategy, revisa las configuraciones para la librería.

* **Juanse Calviño** (1)
Consulta, en el archivo de routes/auth.js de donde toma la variable user ? Porque intento hacer la autenticacion sin usa...

	* **boni** (1)

		
		esa variable user viene de la funcion en `utils/auth/strategies/basic`, yo te recomendaria agregar un debugger, en esa funcion al inicio para verificar si se esta ejecutando correctamente.

* **Iván Darío Sánchez Jiménez** (1)
como funciona la siguiente sintaxis utilizada en el servicio apiKeys.js const [apiKey] = .... No me queda claro este forma ...

	* **Juan David Castro (Platzi)** (4)

		
		Imagina que tienes una función que devuelve un array:
		``` 
		    functionreturnApiKey(par1) {
		      /* ... */
		      return [apiKey];
		    }
		    
		```
		
		La forma “larga” de llamar a esta función y obtener su valor de retorno sería esta:
		``` 
		    const returnedApiKey = returnApiKey(arg1);
		    const apiKey = returnedApiKey[0];
		    
		```
		
		Pero usando JavaScript moderno podemos usar la sintaxis que dices:
		``` 
		    const [apiKey] = returnApiKey(arg1);
		    
		```
		
		Esta sintaxis se vuelve mucho más útil cuando tu función devuelve aún más elementos:
		``` 
		    functionreturnApiKey(par1) {
		      /* ... */
		      return [apiKey, otraCosa];
		    }
		    
		    // La forma larga:
		    const returnedApiKey = returnApiKey(arg1);
		    const apiKey = returnedApiKey[0];
		    const otraCosa = returnedApiKey[1];
		    
		    // JS moderno:
		    const [apiKey, otraCosa] = returnApiKey(arg1);
		    
		```
		
		Aunque si ya son demasiados lo recomendado es usar objetos en lugar de arrays:
		``` 
		    functionreturnApiKey(par1) {
		      /* ... */
		    
		      return {
		        apiKey,
		        otraCosa,
		        kienSabe,
		        soloPorSiAcaso
		      };
		    }
		    
		    // La forma larga:
		    const returnedApiKey = returnApiKey(arg1);
		    const apiKey = returnedApiKey.apiKey;
		    const otraCosa = returnedApiKey.otraCosa;
		    const kienSabe = returnedApiKey.kienSabe;
		    const soloPorSiAcaso = returnedApiKey.soloPorSiAcaso;
		    
		    // JS moderno:
		    const {
		      apiKey,
		      otraCosa,
		      kienSabe,
		      soloPorSiAcaso,
		    } = returnApiKey(arg1);
		    
		```

* **AryRosvall** (1)
Me da este error alguien sabe como resolverlo??? Error: passport.initialize() middleware not in use at IncomingMessage.req.logi...

	* **FernanddoSalas** (1)

		
		Que tal si aun no lo solucionas puedes hacerlo agregando
		``` 
		    app.use(passport.initialize());
		    
		```
		
		en tu configuracion de express.

## 0210. Implementación de nuestro Sign-up

### Descripción:


### Links:

* [GitHub - glrodasz/platzi-auth-passport at implementacion-de-nuestro-sign-up](https://github.com/glrodasz/platzi-auth-passport/tree/implementacion-de-nuestro-sign-up)

### Comentarios:

* **Helmer Barcos** (6)

	
	Para quienes tengan la version **16.1.7** de joi en adelante, deberian hacer un ajuste a la función **validate** en el **validationHandler** quedando asi:
	``` 
	    functionvalidate(data, schema) {
	      const joiSchema = joi.object(schema)
	      const { error } = joiSchema.validate(data)
	      returnerror
	    }
	    
	```

	* **David Behar** (2)

		
		Muchas gracias, me salvaste

* **Luis Arturo Lira Cerda** (5)

	
	No sé si más delante se verá la parte de que no se pueda hacer sign-up usando el mismo correo, pero yo así lo hice y lo comparto por si a alguien le interesa:
	
	En UsersServices.js primero hice otro método encargado de verificar la existencia
	``` 
	    asyncverifyUserExists({ email }) {
	        const [user] = awaitthis.mongoDB.getAll(this.collection, { email })
	        return user
	    }
	    
	```
	
	Y después en el post de sign-up lo llamo, si el objeto que le regresa el service y si el usuario ya está registrado le manda el mensaje de que ya existe y si no, lo crea. (lo mando con send porque no supe que statusCode se le pone 😅 ¿se le pone un 200?)
	``` 
	    try {
	    
	        const userExists = await usersService.verifyUserExists(user)
	    
	        if(userExists) {
	            res.send({
	                message: 'user already exists'
	            })
	            return
	        }
	    
	        const creadtedUserId = await usersService.createUser({ user })
	        res.status(201).json({
	            data: creadtedUserId,
	            message: 'user created'
	        })
	    } catch (err) {
	        next(err)
	    }
	    
	```

* **Marco Antonio Macedo Preciado** (2)
No termino de entender la utilidad de las apiKeys, ¿Entonces el cliente tiene que tener almacenado el apiKey y enviarlo cuando hace un r...

	* **AlexGarrixen** (4)

		
		Hola marco,la finalidad de los apikeys es definir los permisos que tendrán los clientes,que este caso es el del ssr del frontend,pues es este quien tendra los scopes públicos por decirlo asi, y podra solo ejecutar tareas que tiene permitidas,ademas de que tendrá que guardarlo como variable de entorno para no tenerlo en plano.

* **Sebastian** (1)

	
	Porque en la ruta sign-up obtienes el user directamente del obj Request?

	* **Daniel Ramírez Mendoza** (1)

		
		Como tal, lo que está extrayendo es el body del req, y lo renombra a “user”.
		``` 
		    const { body: user} = req;
		    
		```

* **Alejandro González Reyes** (1)
cuando nos registramos en una api publica, por lo general nos piden insertar una APIKEY para poder hacer peticiones al servicio. MI pregu...

	* **Manuel Ojeda** (2)

		
		Tenemos dos tipos de API_KEY  
		La **publica** y la **privada** , la publica se puede decir que es la del usuario normal; la **privada** es la del administrador

* **AlexGarrixen** (1)
Hola,no deberiamos crear un token en base a la apiKey con los permisos publicos y enviarselo ya que una vez que el usuario se registre n...

	* **Daniel Esteves** (1)

		
		Si, eso se debería hacer cuando el usuario se registre y/o inicie sesión ya que si cierra sesión ese token debería desaparecer

## 0220. Protegiendo nuestras rutas con Passport.js

### Descripción:


### Comentarios:

* **AlexGarrixen** (7)

	
	Hola,si quisieran mandar el error como un json,pueden hacer lo siguiente.
	``` 
	    //debemos traernos la estrategia que se ha creado
	    require('path strategia')
	    const passport = require('passport')
	    const boom = require('@hapi/boom')
	    
	    //Crearemos un middleware :
	    const protectRoutes = (req,res,next) => {
	    	passport.authenticate('jwt',(error,user) => {
	            //si ocurre un error o el usuario que me devuelve la strategia no existe
	    	//llamamos a next pasandole a boom
	    	if(error || !user) return next(boom.unauthorized('inautorizado'))
	    	
	    	//De lo contrario ejecutaremos next para llame al siguiente middlware(que en   	//este caso seria el validation handler y el manejador de ruta)
	    	 req.login(user,{session : false},(err) => {
	         	 if(err) return next(err)
	         	 next()
	        })
	     })
	    }
	    
	    //En tu ruta
	    app.post('/movies',protectRoutes,...)
	    
	```

	* **Cristian Bello Cervantes** (2)

		
		en tu función “protectRoutes” te faltó hacer el clousure en passport.authenticate con los atributos del middleware.
		
		esta es la solución 😃
		``` 
		    const protectRoutes = (req, res, next)=>{
		      passport.authenticate('jwt',(error,user) => {
		        //si ocurre un error o el usuario que me devuelve la strategia no existe
		        //llamamos a next pasandole a boom
		        if(error || !user) returnnext(boom.unauthorized());
		    
		        //De lo contrario ejecutaremos next para llame al siguiente middlware(que en   	//este caso seria el validation handler y el manejador de ruta)
		        req.login(user,{session : false},(err) => {
		          if(err) returnnext(err);
		          next()
		        })
		      })(req, res, next);
		    };
		    
		```

* **Alejandro González Reyes** (3)

	
	Existe alguna forma para controlar el error de passportJS cuando no se le pasa un JWT y que no retorne un texto plano

	* **Daniel Esteves** (3)

		
		¡Hola Alejandro! El compañero Alex realizó la solución perfecta para justo lo que necesitas aquí <https://platzi.com/comentario/718205/> suerte y cualquier cosa me avisas 💪

* **Javier Fuentes Mora** (1)

	
	A mi me paso algo extraño el getMovie me retornaba un error y o sabia porque solo sucedia cuando implementaba el passport y solo cambie el cacheResponse(res, SIXTY_MINUTES_IN_SECONDS  
	);  
	al mismo que tenia get movies cacheResponse(res, FIVE_MINUTES_IN_SECONDS);
	
	y funciono quiero suponer que es al tiempo que toma la peticion pero segun yo five inutes es menor que sixty peor no se porque paso alguien tiene alguna idea??

## 0230. Implementando recordar sesión

### Descripción:


Generalmente cuando queremos implementar la opción de recordar sesión para Express mediante passport, lo que hacemos es extender la expiración de la Cookie.

En nuestra ruta de sign-in de nuestro render server hacemos las siguientes modificaciones:
``` 
    // Agregamos las variables de timpo en segundos
    const THIRTY_DAYS_IN_SEC = 2592000;
    const TWO_HOURS_IN_SEC = 7200;
    
    app.post("/auth/sign-in", async function(req, res, next) {
      // Obtenemos el atributo rememberMe desde el cuerpo del request
      const { rememberMe } = req.body;
    
      passport.authenticate("basic", function(error, data) {
        try {
          if (error || !data) {
            next(boom.unauthorized());
          }
    
          req.login(data, { session: false }, async function(error) {
            if (error) {
              next(error);
            }
    
            const { token, ...user } = data;
    
            // Si el atributo rememberMe es verdadero la expiración será en 30 dias
            // de lo contrario la expiración será en 2 horas
            res.cookie("token", token, {
              httpOnly: !config.dev,
              secure: !config.dev,
              maxAge: rememberMe ? THIRTY_DAYS_IN_SEC : TWO_HOURS_IN_SEC
            });
    
            res.status(200).json(user);
          });
        } catch (error) {
          next(error);
        }
      })(req, res, next);
    });
    
```

### Comentarios:

* **Enrique Devars (Platzi)** (6)

	
	La manera en la que yo lo implemente fue de la siguiente forma:
	``` 
	    const ONE_DAY_IN_SECONDS = 86400;
	    const TWO_MONTHS_IN_SECONDS = 5184000;
	    
	    //Basic strategy
	    require('../utils/auth/strategies/basic');
	    
	    functionAuthApi(app) {
	      const router = express.Router();
	      app.use('/api/auth', router);
	    
	      const apiKeyService = new ApiKeysService();
	      const userService = new UsersServices();
	    
	      router.post('/sign-in', asyncfunction(req, res, next) {
	        const { apiKeyToken, rememberMe } = req.body;
	        if (!apiKeyToken) {
	          next(boom.unauthorized('apiKeyToken is required'));
	        }
	    
	        passport.authenticate('basic', function(error, user) {
	          try {
	            if (error || !user) {
	              next(boom.unauthorized());
	            }
	    
	            req.login(user, { session: false }, asyncfunction(error) {
	              if (error) {
	                next(error);
	              }
	    
	              const apiKey = await apiKeyService.getApiKey({ token: apiKeyToken });
	    
	              if (!apiKey) {
	                next(boom.unauthorized());
	              }
	    
	              const { _id: id, name, email } = user;
	    
	              const payload = {
	                sub: id,
	                name,
	                email,
	                scopes: apiKey.scopes
	              };
	    
	              const token = jwt.sign(payload, config.authJwtSecret, {
	                expiresIn: rememberMe ? TWO_MONTHS_IN_SECONDS : ONE_DAY_IN_SECONDS
	              });
	    
	              return res.status(200).json({ token, user: { id, name, email } });
	            });
	          } catch (error) {
	            next(error);
	          }
	        })(req, res, next);
	      });
	    
	```

	* **rusbel bermúdez rivera** (1)

		
		muy buen aporte, aunque yo me quedo con la opción de 15 minutos en lugar de una sesión de 1 día.

	* **rusbel bermúdez rivera** (1)

		
		Aunque en el ejemplo se implementa con cookie no con token

	* **Miguel Segura** (1)

		
		Me parece que aqui hay un error, no es lo mismo implementar ‘Recordar session’ que extender la vida de un JWT, esta ultima opcion me parece mas insegura.

* **Omar Flores Grimontt** (4)

	
	maxAge recibe un valor en milisegundos, multipliquen el número por mil.

* **Alejandro González Reyes** (3)

	
	El nombre de la cookie que passportJS genera siempre se llama token o podemos cambiarle el nombre  
	No lo encuentro en la documentación.

	* **Daniel Esteves** (3)

		
		¡Hola Alejandro! No es explícitamente `token` lo puedes cambiar a cualquier nombre pero eso significa que debes mandarla con el nombre que deseas y listo 💪

* **edwintrumpet** (2)

	
	¿No se supone que esas rutas no van a ser accedidas directamente desde el navegador sino desde el backend del SSR?  
	¿Se le pasan cookies así al otro servidor también?  
	¿Qué pasó con el **apiKeyToken**?

* **Javier Fuentes Mora** (2)

	
	no entiendo aqui ya n se usa el apiKeysService??

## 0240. Middleware para el manejo de scopes

### Descripción:


### Links:

* [GitHub - glrodasz/platzi-auth-passport at middleware-para-el-manejo-de-scopes](https://github.com/glrodasz/platzi-auth-passport/tree/middleware-para-el-manejo-de-scopes)

### Comentarios:

* **Camilo Andrés Santana Lizcano** (3)

	
	Puedes ver la versión escrita de esta clase [aquí](https://platzi.com/tutoriales/1649-passport/5014-protegiendo-nuestras-rutas-con-passportjs/)

* **Alejandro González Reyes** (2)

	
	Corrección del middleware para que valide varios permisos  
	si alguno de ellos falla, se niega el acceso
	``` 
	    const boom = require('@hapi/boom');
	    
	    functionscopesValidationHandler(allowScopes) {
	      returnfunction(req, res, next) {
	        // verificar si el usuario no existe, o que sus scopes no existan
	        if (!req.user || !req.user.scopes) {
	          next(boom.unauthorized('Faltan los scopes'));
	        }
	    
	        // Mapeo el arreglo de scopes pasados a la ruta y verifico si cada uno de esos elementos se encuentra definido en los scopes del usuario. El resultado va a ser un nuevo arreglo de elementos true y/o false
	        const permisions = allowScopes.map(scope =>
	          req.user.scopes.includes(scope)
	        );
	        //verifico que no haya elemetos false en el arreglo de permisos (es decir, todos tienen que ser true para pasar al siguiente middleware, con uno que tenga false, significa que todos los permisos no se cumplen y por tanto se le niega el acceso)
	        const hasAccess = !permisions.includes(false);
	    
	        if (hasAccess) {
	          next();
	        } else {
	          next(boom.unauthorized('Scopes Insuficientes'));
	        }
	      };
	    }
	    
	    module.exports = scopesValidationHandler;
	    
	```

	* **alejandrocepeda** (1)

		
		// falta el return dentro del map
		``` 
		    const permission = allowScopes.map((scope) => {
		          return req.userData.scopes.includes(scope)            
		    })
		    
		    
		```

	* **Juan Carlos García Esquivel** (1)

		
		@alejandrocepeda el código de @jsconestilo si es válido ya que es una iteración de una línea y no utiliza llaves { } por lo tanto es **return** es implícito y no es necesario colocarlo.

* **alejandro-mora-gonzalez** (2)
Es mejor manejar los usuarios por roles o por scopes como tu lo estas haciendo?

	* **glrodasz** (1)

		
		Depende la necesidad de la app. Si necesitas permisos granulares se aplicaría a nivel usuario, en nuestro caso son permisos a niveles de “clientes de aplicación”. Los dos metodos pueden convivir, no son excluyentes.

* **XXVSebastianVXX** (1)

	
	Hasta el momento el token que me regresa la respuesta es muy corto, revise mi código pero al parecer está bien.  
	Alguna idea de por que me esté regresando un token muy corto?

* **Jhurgen Maraza** (1)

	
	Alguien me puede ayudar con una duda?  
	Cuando hago peticiones por Postman, si me devuelve un OK (200-201) me lo muestra por [Body] pero si me devuelve un error (Cualquiera) solo me lo muestra por la consola de del server (VSCode) y en postman se queda colgado esperando la respuesta… Help me pls

	* **Hector Olvera Vital** (1)

		
		Jhurgen:  
		Cuando llega a un error, node se para y te manda el error a consola, postman no recibe nada por que ya no envía nada express. Esto pasa cuando no le das manejo a los errores. Me imagino que alguna promesa no se resolvió, por ejemplo con la base de datos. Localiza el error por medio de la consola para ver de dónde sale el error y encierralo en un try catch para darle manejo con next()

* **wilson_romero** (1)

	
	validar permisos endpoint

* **Alejandro González Reyes** (1)
Este middleware le falta corregir la lógica. Ejemplo. Supongamos que la ruta donde se agrega necesita scopes de read:movies y de user:mod...

	* **Manuel Ojeda** (1)

		
		Para ese caso se agregaría el scope a nivel BD, la intención de Platzi Video es que el usuario este agregado para poder tener acceso al servicio.

## 0250. Configuración del server render

### Descripción:


En esta parte del curso vamos a explorar el proyecto de server side render, que trabajaremos en las siguientes clases.

### Links:

* [Curso de Server Side Render con Express | Materiales](https://platzi.com/clases/ssr/)

### Comentarios:

* **jasanhdz** (12)

	
	Si tienes dificultad en entender algún concepto te invito a checar mis notas del curso:  
	<https://github.com/JasanHdz/passportjs/blob/master/notes/notes.md>  
	Si te gusto mi contenido dejame una ⭐ en mi repositorio. 😄

	* **FizIrvin** (1)

		
		muy bien Jasan

* **Jair Celis** (2)
Hola donde puedo encontrar el curso que comenta @glrodasz “curso backend for frontend” donde se ve la implementación de la ruta de pelícu...

	* **Juan Felipe Peralta Zapata (Platzi)** (2)

		
		¡Hola Jair! 😃
		
		El curso que se comenta en la clase lo puedes encontrar haciendo clic [aquí](https://platzi.com/clases/bff/).

* **Miguel Segura** (1)

	
	Este es el comando para instalar todas las dependencias de nuestro ssr-server:
	``` 
	    npm i @hapi/boom axios cookie-parser dotenv express express-session lodash passport passport-http passport-oauth passport-twitter
	    
	```
	
	Este es el comando para instalar nuestras dependencias de desarrollo:
	``` 
	    npm i -D nodemon
	    
	```

* **Didier Zúñiga** (1)

	
	Si el modulo **movies-api** lo depslegamos en con now a un server, el modulo **ssr-server** iría en ese mismo server pero trabajando en diferentes puertos? O **ssr-server** se desplegaría en otra instancia de now?

## 0260. Comunicación máquina a máquina

### Descripción:


### Links:

* [cookie-parser  -  npm](https://www.npmjs.com/package/cookie-parser)

* [axios  -  npm](https://www.npmjs.com/package/axios)

* [@hapi/boom  -  npm](https://www.npmjs.com/package/@hapi/boom)

* [GitHub - glrodasz/platzi-auth-passport at comunicacion-maquina-a-maquina](https://github.com/glrodasz/platzi-auth-passport/tree/comunicacion-maquina-a-maquina)

### Comentarios:

* **mario-salinas** (12)

	
	Me parece que como en el minuto 6:45 hace falta hacer el destructuring de data:
	``` 
	    const { token, ...user } = data;
	    
	            res.cookie("token", token, {
	              httpOnly: !config.dev,
	              secure: !config.dev
	            });```
	```

	* **José Abdiel Ortega Vázquez** (1)

		
		excelente aporte

* **AlexGarrixen** (3)

	
	Hola,si quisieran utilizar error y la respuesta del servidor principal pueden hacer los iguiente :
	``` 
	     router.post('/signup',(req,res,next) => {
	        const { body : data } = req
	        try {
	          axios({
	            url : `${config.urlApi}/auth/signup`,
	            method : 'POST',
	            data
	          })
	          .then(({status,data}) => {
	            res.status(status)
	            res.cookie('token',data.token,{ httpOnly : config.isDev ? false : true,secure :   config.isDev ? false : true })
	            res.json({
	              data
	            })
	          })
	          .catch( err => {
	            let error = err.response.data 
	            let statusCode = error.statusCode
	            res.status(statusCode).json(error)
	          }) 
	        }
	        catch(e) {
	          next(e)
	        }
	      })  
	    
	```

	* **Gschwind** (1)

		
		Probé tu codigo pero no puedo recibir la respuesta del servidor. Me dice EMPTY_RESPONE pero la API responde bien en POSTMAN y en la terminal.![Selección_147.png](https://static.platzi.com/media/user_upload/Selecci%C3%B3n_147-4533c526-d138-4de8-8969-674aa3dca3c2.jpg)  
		![Selección_144.png](https://static.platzi.com/media/user_upload/Selecci%C3%B3n_144-b40db3a2-a139-4b91-a774-fea2350c4bd4.jpg)  
		![Selección_145.png](https://static.platzi.com/media/user_upload/Selecci%C3%B3n_145-61742234-86c1-456a-8ba3-b5021b8108d6.jpg)  
		![Selección_146.png](https://static.platzi.com/media/user_upload/Selecci%C3%B3n_146-5cc0f774-4ada-423e-9258-a3f5d64f9c6c.jpg)

* **johnflorez** (2)
Saludos, ¿Si quisiera hacer la conexión desde un front que no esta renderizado desde el servidor, cómo se realiza? Se que en su momento s...

	* **Marco Antonio Macedo Preciado** (1)

		
		Hola, yo hice un servidor proxy para un proyecto en React para poder refrescar los tokens. Te dejo el [repositorio de github](https://github.com/MarcoMacedoP/sign-frontend) para que le des una checada.

* **Marco Antonio Macedo Preciado** (2)
Hola, ¿Mediante el uso de un Server Render ya podríamos aplicar algo como Silent Autentication o Refresh Tokens? 🤔

	* **glrodasz** (2)

		
		En realidad son dos conceptos diferentes, pero se puede hacer uso del server para implementar estas dos tecnologias, pero aclaro, no tiene que ser un Server Render, puede ser un app server normal.

* **jesus-olivares661** (1)

	
	si utilizo Nuxt necesito programar un render server…?

* **rusbel bermúdez rivera** (1)

	
	sobre la basic strategy y la libreria axios, al termnar la configuración del script, vemos que guardamos en la
	``` 
	    const { data, status }
	    
	```
	
	Tip. Axios es una librería para manejar promisses, esta genera el http response a la petición, así que el status viene junto con la respuesta.
	
	**Aquí** el repo de la librería con varios ejemplos.  
	<https://github.com/axios/axios>

## 0270. Implementación de las rutas de las películas de usuario

### Descripción:


Felicidades por haber terminado este módulo, en el cual aprendimos:

  * Configuración de nuestro proyecto
  * Configuración de Passport.js
  * Implementación de estrategias en Passport.js
  * Implementación de nuestro Sign-in y Sign-up
  * Protegiendo nuestras rutas con Passport.js
  * Implementando recordar sesión
  * Comunicación máquina a máquina



Sigue adelante, ya nos falta poco para terminar.

### Links:

* [GitHub - glrodasz/platzi-auth-passport at implementacion-de-las-rutas-de-las-peliculas-de-usuario](https://github.com/glrodasz/platzi-auth-passport/tree/implementacion-de-las-rutas-de-las-peliculas-de-usuario)

### Comentarios:

* **oqodigital** (19)

	
	El video está cortado. Se salta del Sign in al user-movies.

* **eemartinez97** (6)

	
	He notado que hay un error en la validación de datos al momento de crear un user_movie, lo que veo es que aunque no pases el userId y el movieId, siempre se guarda (obviamente sin ningún dato)… entonces he modificado un poco el schema de userMovies.js … mi pregunta es si es correcto como lo he hecho (funciona pero no se si es una buena forma de hacerlo)
	
	![](https://i.ibb.co/Xb02mGx/Capture.png)

* **Juan Carlos García Esquivel** (4)

	
	**Authorization Basic** : Se utiliza un usuario y contraseña y se usa generalmente para el primer acceso a un sistema sign-in y este tipo de autorización nos puede devolver un **JSON WEB TOKEN**.
	
	**Authorization Bearer** : Se utiliza un JWT con el cual el sistema valida nuestra identidad y los niveles de autorización que tenemos dentro del sistema, estos datos se ponen el el payload del JWT.
	
	Como lo entendí estos dos tipos de autorización funcionan bien juntos, primero utilizas Basic para obtener tu token y después utilizas el token para no depender de una sesión del lado del servidor y poder manejar las rutas y los accesos con el token.

* **SaFeRamirez** (3)

	
	Authorization Bearer => Solicita un token (JWT)  
	Authorization Basic => Solicita un usuario y password

* **Cristian Fabian Tovar** (3)
me perdí en el minuto 5:15 y es desde ahí donde no he podido avanzar, ¿Por qué hace una petición a la url {{client_url}}/auth/sign-in y n...

	* **Cristian Fabian Tovar** (3)

		
		encontre mi propio error, y es que se me olvidó hacer el archivo .env en el directorio de /ssr-server

* **josdanind** (2)

	
	Como se levantan ambos servidores a la vez, y no de forma independiente? Como sería el script del package.json para hacerlo?

	* **Helmer Barcos** (2)

		
		`node ssr-server/index.js & node movies-api/index.js &`
		
		Recuerda que el script debe ser ejecutado en el root donde se encuentran las carpetas de ssr-server y movies-api. No olvides ademas que si utilizas nodemon para desarollo debes cambiar `node` por `nodemon` en el script

	* **josdanind** (1)

		
		Gracias por tu aporte

	* **glrodasz** (2)

		
		Te recomendaría que si quieres hacer algo así uses una librería como `npm-run-all` y crees un script especifico. Me ha pasado que al levantar los servers de forma paralela pierdo control sobre el proceso y el proceso queda vivo sin poderse terminar.

* **Alejandro Moraga** (1)

	
	Tengo un problema, puedo realizar el “sign in” con el SSR este a su vez me genera la respectiva cookie. Pero al momento de realizar un POST al user-movie este me genera un error 401 (Problemas de autorizacion), realice un console.log para ver si me traia todos los datos del POST correspondiente del request efectivamente me trae el ID del usuario y el ID de la pelicula pero no me trae nada en releacion a la cookies. Pienso que podria tener relacion con alguna configuracion del Postman que al momento de realizar la peticion, este no esta configurado para enviar las cookies, alguna idea gente?, se agradece ❤️
	``` 
	     /***** Informacion obtenida con el console.log mencionado al request de la peticion 
	     < 
	       cookies: [Object: null prototype] {},
	      signedCookies: [Object: null prototype] {},
	     >
	    
	```

	* **Andres Roberto Coello Goyes** (1)

		
		si, en lo mismo me encuentro yo. revisa en la aplication del navegador si se crearon las cookie.

	* **Luis Rodriguez** (1)

		
		Hola! Cómo están? Lograron resolver la duda? Si aún no lo resolvieron, estaría genial si pueden poner un link a su github. Un saludo!

	* **JUAN SILVA** (2)

		```
		    app.post("/user-products", asyncfunction(req, res, next) {
		      try {
		        const { body: userMovie } = req;
		        const { token } = req.cookies;
		        
		        const { data, status } = await axios({
		        
		          url: "http://localhost:3000/api/user-products",
		          headers: { Authorization: `Bearer ${token}` },
		          method: "post",
		          data: userMovie
		        });
		    
		        if (status !== 201) {
		          return next(boom.badImplementation());
		        }
		    
		        res.status(201).json(data);
		      } catch (error) {
		        next(error);
		      }
		    });
		    
		```
		
		la unica forma en que me funcionó fue quemar el puerto del servidor y ponerlo directamente, parece que axios no reconoce si no se introduce la url como un string

	* **Luis Rodriguez** (1)

		
		mmm, no estoy del todo seguro que sea es, hermano.
		
		en la sección de `app.post"auth/sign-in"`debería de estar pasando tu token a la cookie.
		
		¿Cómo se ve el resto del código?, no creo que el error esté acá en el este snippet que compartiste.

* **Didier Zúñiga** (1)

	
	Auth Bearrer solicita un Token  
	Auth Basic solicita usuario y contraseña

* **eduardohackone** (1)

	
	Yo se que esto se sale del tema, a este punto llevo un proyecto estructurado. pero se me presenta una duda y es como puedo manejar las imagenes ejemplo campo imagen para las peliculas ?, soy programador php y por lo general se sube al servidor aqui como se manejaria ?
	
	Muchas gracias por estos videos

	* **Ezequiel Guerra** (3)

		
		usando multer, es un middleware que va a usar en las rutas para manejar las imágenes.

* **Tonalli López** (1)

	
	Authorization Bearer: JWT  
	Authorization Basic: usuario y password

# Entender qué es OAuth 2.0 y OpenID Connect

## 0280. ¿Qué es OAuth 2.0 y OpenID Connect

### Descripción:


 **OAuth 2.0** es un estándar de la industria que nos permite implementar autorización.

**OpenID Connect** es una capa de autorización que funciona sobre _OAuth_ con métodos ya construidos.

### Comentarios:

* **Daniel Alberto Esquinazi** (2)

	
	OpenID Connect (OIDC) es un protocolo de _autenticación_ implementada utilizando OAuth 2.0, un framework de autorización. El estándar está controlado por el OpenID Foundation.[Mas ](https://es.wikipedia.org/wiki/OpenID_Connect)

* **wilantury** (1)

	
	OpenID Connect es una capa de autenticación que funciona sobre la capa de OAuth 2.0.

# Implementar autenticación con redes sociales

## 0290. Cómo crear un proyecto en Google API para hacer autenticación con 0Auth 2.0

### Descripción:


Con el fin de poder usar Google como método de autenticación es necesario crear un nuevo proyecto dentro de la consola de desarrolladores de Google.

  1. Nos dirigimos a <https://console.developers.google.com> y nos autenticamos con nuestra cuenta de Google.
  2. En la parte superior izquierda seleccionamos la organización que queremos usar (Debe haber una por defecto) y hacemos click en **Create Project**.
  3. Luego nos vamos al sidebar izquierdo y seleccionamos **Credentials > Create credentials > OAuth client ID**
  4. Nos aseguramos de elegir `Web Application` como el tipo de aplicación.
  5. Luego establecemos el nombre del cliente que en nuestro caso será `SSR Server`, el **Authorized JavaScript origins** : `http://localhost:8000` y el **Authorized redirect URIs** `http://localhost:8000/auth/google-oauth/callback`. Cuando hagamos despliegue de nuestra aplicación lo ideal es crear otro cliente y remplazar las URLs por las URLs correspondientes de producción.
  6. El **Application Name** del **Consent Screen** será `Platzi Videos`.
  7. Al finalizar la creación copiamos el **Client ID** y **Client secret** que seran usados como `GOOGLE_CLIENT_ID` y `GOOGLE_CLIENT_SECRET` respectivamente.



### Comentarios:

* **José Abdiel Ortega Vázquez** (1)

	
	Cuando agregó el dominio. Dominio no es válido porque no puede contener un puerto o debe ser un dominio privado de nivel superior. que consejo me darían aquí

* **Andres Roberto Coello Goyes** (1)

	
	Esta es la parte que me interesa mas… login con redes sociales

## 0300. Implementando 0Auth2.0 con Google

### Descripción:


### Links:

* [OpenID Connect  |  Google Identity Platform
       |  Google Developers](https://developers.google.com/identity/protocols/OpenIDConnect)

* [Using OAuth 2.0 to Access Google APIs  |  Google Identity Platform
       |  Google Developers](https://developers.google.com/identity/protocols/OAuth2)

* [Using OAuth 2.0 for Web Server Applications  |  Google Identity Platform
       |  Google Developers](https://developers.google.com/identity/protocols/OAuth2WebServer)

* [GitHub - glrodasz/platzi-auth-passport at implementando-oauth2-con-google](https://github.com/glrodasz/platzi-auth-passport/tree/implementando-oauth2-con-google)

### Comentarios:

* **Matias Sebastian Perez** (3)

	
	Tengo una pregunta con respecto a porque no ponemos la opcion “{ session: false }” en el endpoint “/auth/google-oauth”, pero en el endpoint “/auth/google-oauth/callback” la ponemos.

	* **Juan David Castro (Platzi)** (9)

		
		👋 Hey!
		
		1️⃣ El primer paso en la autenticación de Google es mandar al usuario a **`google.com`**. Luego de la autorización, Google mandará al usuario nuevamente a nuestra aplicación en **`/auth/google/callback`**.
		``` 
		    app.get(
		      "/auth/google-oauth",
		      passport.authenticate("google-oauth", {
		        scope: ["email", "profile", "openid"]
		      })
		    );
		    
		```
		
		2️⃣ Si toda sale bien, ejecutamos la función de callback. Con **`{ session: false }`** solo estamos indicando que no debemos salvar al usuario en la sesión. no es necesario en el primer paso porque apenas estamos validando la autenticación del usuario.
		``` 
		    app.get(
		      "/auth/google-oauth/callback",
		    
		      passport.authenticate(
		        "google-oauth",
		        { session: false }
		      ),
		    
		      function(req, res, next) {
		        if (!req.user) {
		          next(boom.unauthorized());
		        }
		    
		        const { token, ...user } = req.user;
		    
		        res.cookie("token", token, {
		          httpOnly: !config.dev,
		          secure: !config.dev
		        });
		    
		        res.status(200).json(user);
		      }
		    );
		    
		```
		
		Referencias:
		
		👉 <http://www.passportjs.org/docs/google/>  
		👉 <https://stackoverflow.com/questions/40828955/passport-jwt-google-strategy-disable-session-res-send-after-google-cal>  
		👉 <https://github.com/jaredhanson/passport/issues/169>  
		👉 <https://medium.com/front-end-weekly/learn-using-jwt-with-passport-authentication-9761539c4314>

## 0310. Implementando Sign Provider en nuestra API

### Descripción:


### Links:

* [GitHub - glrodasz/platzi-auth-passport at implementando-sign-provider-en-nuestra-api](https://github.com/glrodasz/platzi-auth-passport/tree/implementando-sign-provider-en-nuestra-api)

### Comentarios:

* **Alejandro González Reyes** (2)
¿Porque no se pintó el token y su valor correspondiente en el json enviado como respuesta (min 6:47)? sin embargo, en la estrategia si l...

	* **Alejandro González Reyes** (5)

		
		Me respondo a mi mismo,  
		la data que pinta el navegador es la del SSR, no el API.

* **Luis Arturo Lira Cerda** (1)

	
	Cuando entro de nuevo a la ruta después de los 15 minutos me debe pedir que inicie sesión de nuevo con Google o me debe enviar de nuevo al json con los datos sin necesidad de poner mi credenciales de google?

## 0320. Autenticación con Google usando OpenID Connect

### Descripción:


En el curso vimos como se podia implementar Google Authentication usando la estrategia de OAuth directamente. En esta lectura vamos a explorar como hacer la autenticación usando la estrategia directa de Google.

Lo primero es instalar nuestras dependencias
``` 
    npm install passport-google-oauth
    
```

Luego creamos una nueva estrategia llamada `google` dentro de `utils/auth/strategies/google.js`:
``` 
    const passport = require("passport");
    const { OAuth2Strategy: GoogleStrategy } = require("passport-google-oauth");
    
    const { config } = require("../../../config/index");
    
    passport.use(
      new GoogleStrategy(
        {
          clientID: config.googleClientId,
          clientSecret: config.googleClientSecret,
          callbackURL: "/auth/google/callback"
        },
        function(accessToken, refreshToken, profile, cb) {
          const { data, status } = await axios({
            url: `${config.apiUrl}/api/auth/sign-provider`,
            method: "post",
            data: {
                name: profile.name,
                email: profile.email,
                password: profile.id,
                apiKeyToken: config.apiKeyToken
            }
          });
    
          if (!data || status !== 200) {
            return cb(boom.unauthorized(), false);
          }
    
          return cb(null, data);
        }
      )
    );
    
```

Teniendo nuestra estrategia de **Google** ya podemos agregar las dos nuevas rutas de autenticación.
``` 
    app.get(
      "/auth/google",
      passport.authenticate("google", {
        scope: ["email", "profile", "openid"]
      })
    );
    
    app.get(
      "/auth/google/callback",
      passport.authenticate("google", { session: false }),
      function(req, res, next) {
        if (!req.user) {
          next(boom.unauthorized());
        }
    
        const { token, ...user } = req.user;
    
        res.cookie("token", token, {
          httpOnly: !config.dev,
          secure: !config.dev
        });
    
        res.status(200).json(user);
      }
    );
    
```

Con esto tenemos nuestra implementación de autenticación con Google pero mucho más sencilla.

### Comentarios:

* **Matias Sebastian Perez** (20)

	
	Hay un par de errores en el codigo:
	
	  * En el callback del passport.use, a la funcion le falta el async
	  * Se utiliza boom, pero no esta importado
	  * Se utiliza axios , pero no esta importado
	  * Y el GoogleStrategy, en este caso no retorna el profile de la manera que lo haciamos con oauth, para entender mejor este punto dejo el codigo funcional abajo
	
	
	``` 
	    const passport = require('passport');
	    const { OAuth2Strategy: GoogleStrategy } = require('passport-google-oauth');
	    const axios = require('axios');
	    const boom = require('@hapi/boom');
	    
	    const { config } = require('../../../config');
	    
	    passport.use( new GoogleStrategy({
	        clientID: config.googleClientId,
	        clientSecret: config.googleClientSecret,
	        callbackURL: "/auth/google/callback",  
	    },
	    async (accessToken, refreshToken, { _json: profile }, done) => {
	        try{
	            const { data, status } = await axios({
	                url: `${config.apiUrl}/api/auth/sign-provider`,
	                method: "post",
	                data: {
	                    name: profile.name,
	                    email: profile.email,
	                    password: profile.sub,
	                    apiKeyToken: config.apiKeyToken
	                }
	            });
	    
	            if(!data || status !== 200){
	                done(boom.unauthorized(), false)
	            }
	    
	            done(null, data)
	        }catch(err){
	            done(err)
	        }
	    }
	    ) );
	    
	```

	* **Favio Sauto** (5)

		
		QueAgradableSujeto.jpg bajaba a los comentarios a corregir los mismo errores 😂😂

	* **Manuel Ojeda** (5)

		
		Héroe sin capa 🤘

	* **oqodigital** (1)

		
		No me funcionó 😦

* **oscar-leon846** (2)

	
	no olviden registrar la url del callback en la consola de google, si no google les retornara un error 400

* **Alejandro González Reyes** (2)

	
	Alguien puede auxiliarme, me encuentro algo confundido.  
	OAuth es para autorización (no importa las estrategias que implementemos)  
	OAuth con OpenID Connect: es para obtener el perfil del usuario autorizado.
	
	ya que veo que hay varias estrategias que involucran a oauth, y muchas de ellas terminan en google, facebook, twitter.  
	y es mas sencillo.

	* **Daniel Esteves** (1)

		
		¡Hola! 🤔 Creo que te respondiste a ti mismo 😅 ¿o aún te falta algún concepto que te pueda ayudar a entender?

* **ApolloAu** (0)

	
	tengo este error y no encuentro donde se declara la estrategia google.
	``` 
	    Error: Unknown authentication strategy "google"
	        at attempt (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/passport/lib/middleware/authenticate.js:186:37)
	        at authenticate (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/passport/lib/middleware/authenticate.js:362:7)
	        at Layer.handle [as handle_request] (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/express/lib/router/layer.js:95:5)
	        at next (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/express/lib/router/route.js:137:13)
	        at Route.dispatch (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/express/lib/router/route.js:112:3)
	        at Layer.handle [as handle_request] (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/express/lib/router/layer.js:95:5)
	        at /mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/express/lib/router/index.js:281:22
	        at Function.process_params (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/express/lib/router/index.js:335:12)
	        at next (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/express/lib/router/index.js:275:10)
	        at cookieParser (/mnt/c/Users/moonb/Documents/Developer/Platzi/ssr-server/node_modules/cookie-parser/index.js:71:5)
	    
	```

	* **ApolloAu** (1)

		
		Solucionado, habia que declarar la estrategia. require("./utils/auth/strategies/google");

## 0330. Cómo crear una cuenta de desarrollador con Twitter

### Descripción:


Con el fin de poder usar Twitter como método de autenticación es necesario crear una cuenta de desarrollador de Twitter. Es necesario postularse para que la cuenta de desarrollador pueda ser utilizada y suele tomar hasta 24 horas de aprobación. Para aplicar a la cuenta es necesario hacer dirigirse a <https://developer.twitter.com/en/apply-for-access.html> y hacer click en el botón `Apply for a developer account`.

Cuando la cuenta ha sido aprobada, entonces procederemos a crear una aplicación para usarla en nuestro método de autenticación, para ellos debemos:

  1. Nos dirigimos a la lista de nuestras aplicaciones en <https://developer.twitter.com/en/apps>
  2. Allí creamos una nueva app haciendo click en el botón **Create an app**.
  3. Llenamos los correspondientes campos como **App Name** y **Website URL**.
  4. Las URLs de **Terms of Service URL** y **Privacy policy URL** son necesarias para poder solicitar el email del usuario.
  5. Como callback URL podemos usar `http://localhost:8000/auth/twitter/callback`. Lo ideal es que cuando salimos a producción creamos una aplicación diferente y esta vez usaremos la URL de producción.
  6. Marcamos como **Enabled** que nuestra app va a ser usada para **Sign in with Twitter**.
  7. Hacemos click en **Create** , accedemos a los detalles de la app creada y en el tab de **Permissions** , y luego en **Additional permissions** marcamos **Request email address from users** y guardamos.
  8. Nos vamos al tab de **Keys and tokens** y copiamos los **Consumer API Keys** que son los que usaremos como `TWITTER_CONSUMER_KEY` y `TWITTER_CONSUMER_SECRET` respectivamente.



### Comentarios:

* **Navarrock33** (2)

	
	que tengo que escribir en donde dice “Website URL”?

	* **Daniel Esteves** (1)

		
		El sitio web de tu aplicación :sungl

* **edwintrumpet** (1)

	
	En el campo de **Website URL** puse **<http://localhost:8000>** y dice que es una url inválida  
	¿No se puede probar en localhost?

	* **Victor Martin Ortiz Palacio** (1)

		
		Puedes poner la url de tu perfil de Twitter, o tu pagina de GitHub. Por lo que lei, en desarrollo o pruebas, como es nuestro caso, no hay necesidad de tener un dominio propio, ya que solo necesitamos que nos genere las Keys.

## 0340. Autenticación con Twitter

### Descripción:


### Links:

* [GitHub - glrodasz/platzi-auth-passport at autenticacion-con-twitter](https://github.com/glrodasz/platzi-auth-passport/tree/autenticacion-con-twitter)

### Comentarios:

* **Massimo Di Berardino** (2)

	
	Esto les puede ayudar con el challenge  
	<https://github.com/auth0/passport-linkedin-oauth2>

	* **José Abdiel Ortega Vázquez** (1)

		
		Gracias lo probaré

	* **José Abdiel Ortega Vázquez** (1)

		
		Funcionó muchas gracias por el aporte

* **Victor Martin Ortiz Palacio** (1)

	
	Challenge:
	``` 
	    const passport = require('passport');
	    const boom = require('@hapi/boom');
	    const axios = require('axios');
	    //Esta fue la libreria que a mi me funcionó.
	    const LinkedInStrategy = require('@sokratis/passport-linkedin-oauth2').Strategy;
	    
	    const { config } = require('../../../config/index');
	    
	    passport.use(
	      new LinkedInStrategy(
	        {
	          clientID: config.linkedinClientId,
	          clientSecret: config.linkedinClientSecret,
	          callbackURL: '/auth/linkedin/callback',
	          scope: ['r_emailaddress', 'r_liteprofile']
	        },
	        asyncfunction(accessToken, refreshToken, profile, cb) {
	          const { data, status } = await axios({
	            url: `${config.apiUrl}/api/auth/sign-provider`,
	            method: 'post',
	            data: {
	              name: profile.displayName,
	              email: profile.emails[0].value,
	              password: profile.id,
	              apiKeyToken: config.apiKeyToken
	            }
	          });
	    
	          if (!data || status !== 200) {
	            return cb(boom.unauthorized(), false);
	          }
	    
	          return cb(null, data);
	        }
	      )
	    );
	    
	    
	```
	``` 
	    app.get(
	      '/auth/linkedin',
	      passport.authenticate('linkedin', { state: 'SOME STATE' })
	    );
	    
	    app.get('/auth/linkedin/callback', passport.authenticate('linkedin', { session: false}),
	      function(req, res, next) {
	        if (!req.user) {
	          next(boom.unauthorized())
	        }
	    
	        const { token, ...user } = req.user;
	    
	        res.cookie('token', token, {
	          httpOnly: !config.dev,
	          secure: !config.dev
	        });
	    
	        res.status(200).json(user)
	      }
	    );
	    
	```

## 0350. Autenticación con Facebook

### Descripción:


A continuación veremos cómo podemos implementar la autenticación haciendo uso de la estrategia para Facebook. Es importante primero tener una cuenta de Facebook para desarrolladores: <https://developers.facebook.com/> y crear una app/project como lo hemos hecho anteriormente para Google y Twitter. Podemos seguir las instrucciones aquí: <https://developers.facebook.com/docs/apps>, para obtener nuestros `FACEBOOK_CLIENT_ID` y `FACEBOOK_CLIENT_SECRET` respectivamente.

Lo primero es instalar nuestras dependencias
``` 
    npm install passport-facebook
    
```

Luego creamos una nueva estrategia llamada `facebook` dentro de `utils/auth/strategies/facebook.js`:
``` 
    const passport = require('passport');
    const { Strategy: FacebookStrategy } = require('passport-facebook');
    
    const { config } = require("../../../config/index");
    
    passport.use(new FacebookStrategy({
        clientID: config.facebookClientId,
        clientSecret: config.facebookClientSecret,
        callbackURL: "/auth/facebook/callback"
      },
      function(accessToken, refreshToken, profile, done) {
          const { data, status } = await axios({
            url: `${config.apiUrl}/api/auth/sign-provider`,
            method: "post",
            data: {
                name: profile.name,
                email: profile.email,
                password: profile.id,
                apiKeyToken: config.apiKeyToken
            }
          });
    
          if (!data || status !== 200) {
            return cb(boom.unauthorized(), false);
          }
    
          return cb(null, data);
      }
    ));
    
```

Teniendo nuestra estrategia de **Facebook** ya podemos agregar las dos nuevas rutas de autenticación.
``` 
    app.get("/auth/facebook", passport.authenticate("facebook"), {
      scope: ["email", "profile", "openid"]
    });
    
    app.get(
      "/auth/facebook/callback",
      passport.authenticate("facebook", { session: false }),
      function(req, res, next) {
        if (!req.user) {
          next(boom.unauthorized());
        }
    
        const { token, ...user } = req.user;
    
        res.cookie("token", token, {
          httpOnly: !config.dev,
          secure: !config.dev
        });
    
        res.status(200).json(user);
      }
    );
    
```

Con esto tenemos nuestra implementación de autenticación con Facebook.

### Comentarios:

* **Manuel Ojeda** (8)

	
	Primero que nada les comparto el código que utilicé para poder realizar este ejercicio.
	
	Primeramente en **facebook.js** ocupamos hacer el llamado de la información a través de una función asíncrona, por lo que se omitió agregar la palabra **async**. Segungo; realicé una asignación del email muy similar a Twitter, pues Facebook no me retornaba el correo del usuario, por lo que el código de FacebookStrategy me quedó de la siguiente forma:
	``` 
	    passport.use(
	      new FacebookStrategy(
	        {
	          clientID: config.facebookClientId,
	          clientSecret: config.facebookClientSecret,
	          callbackURL: "/auth/facebook/callback",
	          profilerFields: ["id", "email", "displayName"]
	        },
	        asyncfunction(accessToken, refreshToken, profile, done) {
	    	// Esta declaración de email es necesaria, pues Facebook no me retornaba el correo del usuario
	          const email = profile.email
	            ? profile.email
	            : `${profile.id}@facebook.com`;
	    
	          const { data, status } = await axios({
	            url: `${config.apiUrl}/api/auth/sign-provider`,
	            method: "post",
	            data: {
	              name: profile.displayName,
	              email: email,
	              password: profile.id,
	              apiKeyToken: config.apiKeyToken
	            }
	          });
	    
	          if (!data || status !== 200) {
	            return done(boom.unauthorized(), false);
	          }
	    
	          return done(null, data);
	        }
	      )
	    );
	    
	```
	
	Y en las rutas retire el campo scopes de **/auth/facebook** pues Facebook no reconoce el scope **Profile** :
	
	Pasó de esto:
	``` 
	    app.get("/auth/facebook", passport.authenticate("facebook"), {
	      scope: ["email", "profile", "openid"]
	    });
	    
	```
	
	A
	``` 
	    app.get("/auth/facebook", passport.authenticate("facebook"));
	    
	```
	
	Espero les sea de utilidad este código que realicé para lograr el Login de Facebook.

	* **Victor Martin Ortiz Palacio** (4)

		
		Me fue de mucha ayuda tu explicacion. Yo lo modifique de la siguiente manera:
		``` 
		    app.get('/auth/facebook', passport.authenticate('facebook', {
		      scope: ['email']
		    }));
		    
		```
		``` 
		    passport.use(
		      new FacebookStrategy(
		        {
		          clientID: config.facebookClientId,
		          clientSecret: config.facebookClientSecret,
		          callbackURL: '/auth/facebook/callback',
		          profileFields: ['id', 'displayName', 'photos', 'email']
		        },
		        asyncfunction(accessToken, refreshToken, profile, cb) {
		          const { data, status } = await axios({
		            url: `${config.apiUrl}/api/auth/sign-provider`,
		            method: 'post',
		            data: {
		              name: profile.displayName,
		              email: profile.emails[0].value,
		              password: profile.id,
		              apiKeyToken: config.apiKeyToken
		            }
		          });
		          if (!data || status !== 200) {
		            return cb(boom.unauthorized(), false);
		          }
		    
		          return cb(null, data);
		        }
		      )
		    );
		    
		```
		
		las modificaciones son minimas, pero me sirvio para entender un poco mas como funciona.

	* **rusbel bermúdez rivera** (1)

		
		No entendí de donde salio usar profilerFields, lo intente con los profileFields de la documentacion de passport-facebook pero funcionó con el codigo de Manuel

* **rusbel bermúdez rivera** (2)

	
	Aquí mi solución gracias a los aportes de los demás, incluí un console.log, para que los novatos como yo, puedan saber de donde salen las variables de data, y por que use _json: profile como argumento en la función. Lean la documentación de passport-facebook es de gran ayuda
	``` 
	    const passport = require('passport');
	    const { Strategy: FacebookStrategy } = require('passport-facebook');
	    const axios = require('axios');
	    const boom = require('@hapi/boom');
	    
	    
	    const { config } = require("../../../config/index");
	    
	    passport.use(
	        new FacebookStrategy({
	            clientID: config.facebookClientId,
	            clientSecret: config.facebookClientSecret,
	            callbackURL: "/auth/facebook/callback",
	            profileFields: ['id', 'displayName', 'photos', 'email']
	        },
	            asyncfunction (accessToken, refreshToken, { _json: profile }, done) {
	                try {
	    		
	                    // te permite ver el objeto profile, y su composición.
	                    console.log(profile)
	                        
	                    const { data, status } = await axios({
	                        url: `${config.apiUrl}/api/auth/sign-provider`,
	                        method: "post",
	                        data: {
	                            name: profile.name,
	                            email: profile.email,
	                            password: profile.id,
	                            apiKeyToken: config.apiKeyToken
	                        }
	                    });
	    
	                    if (!data || status !== 200) {
	                        return cb(boom.unauthorized(), false);
	                    }
	    
	                    return done(null, data);
	                } catch (error) {
	                    done(error)
	                }
	            }
	        ));```
	    
	```

* **Navarrock33** (1)

	
	me da “FacebookTokenError: Error validating client secret.”

	* **Navarrock33** (1)

		
		[](https://ibb.co/2cDkTSs) –

	* **Navarrock33** (1)

		
		<https://ibb.co/2cDkTSs>

	* **Daniel Esteves** (1)

		
		¡Hola Navarro! El compañero Manuel tiene la solución perfecta para el error que se te ha presentado aquí 👉 <https://platzi.com/comentario/736411/>

# Asegurar tu aplicación de Express

## 0360. Seguridad con Helmet y npm audit

### Descripción:


En esta clase aprenderemos a ponerle seguridad a nuestra aplicación.

**Helmet** es un _middleware_ que nos sirve para darle seguridad a las headers de nuestra aplicación.

Lo podremos utilizar de la siguiente manera con la configuración por defecto:
``` 
    const express = require('express')
    const helmet = require('helmet')
    
    const app = express()
    
    app.use(helmet())
    
```

También aprenderemos a utilizar `npm audit` para ver cuales son las vulnerabilidades de nuestra aplicación

### Links:

* [Helmet](https://helmetjs.github.io)

* [GitHub - glrodasz/platzi-auth-passport at seguridad-con-helmet-y-npm-audit](https://github.com/glrodasz/platzi-auth-passport/tree/seguridad-con-helmet-y-npm-audit)

### Comentarios:

## 0370. Automatizar el chequeo de vulnerabilidades con Snyk

### Descripción:


Para usar snyk lo primero es crear una cuenta en <https://app.snyk.io/signup> para agilizar el proceso recomiendo usar la cuenta de GitHub.

![snyk-landing.png](https://static.platzi.com/media/user_upload/snyk-landing-cec88810-04d1-4a7f-bc8c-0f785df9981c.jpg)

Despues de la creación de la cuenta nos redireccionara a las integraciones o podemos ir directamente mediante el link `https://app.snyk.io/org/<usuario>/integrations`.

![snyk-integrations.png](https://static.platzi.com/media/user_upload/snyk-integrations-be76249e-d462-4fac-910a-1b0442c9e805.jpg)

Seleccionamos la integración con GitHub (ó con el servicio más adecuado para nuestro proyecto) y allí nos aseguramos de conectar nuestra cuenta con GitHub, otorgando los permisos necesarios.

![snyk-connected.png](https://static.platzi.com/media/user_upload/snyk-connected-7ebfe9aa-ad8d-4773-af25-058a25da30f8.jpg)

Por ultimo necesitamos agregar el repositorio de nuestro proyecto para que haga la revision automática de vulnerabilidades en cada Pull request, mediante el botón `Add your GitHub repositories to Snyk`.

Allí buscaremos el repositorio de nuestro proyecto, lo seleccionamos y le damos en el botón `Add 1 selected repository to Snyk`.

Cuando termine la integración podemos dirigirnos al dashboard de nuestros proyectos haciendo click en la pestaña `Projects` o mediante el link `https://app.snyk.io/org/<usuario></usuario>/projects` y verificar el estado de nuestras dependencias:

![snyk-projects.png](https://static.platzi.com/media/user_upload/snyk-projects-96fa7eca-6a0e-4054-a373-cc3aab429c6a.jpg)

En lo posible debemos evitar tener vulnerabilidades High (H) o Medium (M) para corregirlas le damos click en `View report and fix`.

> Tener en cuenta que algunas vulnerabilidades no tienen solución en el momento por lo que toca estar pendiente de un posible fix o cambiar de librería.

### Comentarios:

* **sebas001** (1)

	
	bueno

## 0380. Que és OWASP y buenas prácticas de seguridad

### Descripción:


 **OWASP** son las siglas de **Open Web Application Security Project** , una organización que cuida las buenas prácticas de seguridad en las aplicaciones.

Buenas prácticas:

  * Usa un gestor de contraseñas
  * Usa multi-factor auth
  * IRL security
  * Mantén actualizadas tus aplicaciones y SO
  * Mantente informado



### Links:

* [https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf](https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf)

* [SQL Injection Attack](https://sqlzoo.net/hack/index.html)

* [How Secure Is My Password?](https://howsecureismypassword.net)

* [https://eugdpr.org/](https://eugdpr.org/)

* [Curso de Análisis de Vulnerabilidades Web con OWASP | Materiales](https://platzi.com/clases/seguridad/)

### Comentarios:

* **WilliamVelazquez** (1)

	
	¿Qué gestor de contraseñas recomiendan?  
	Si pudieran indicar las ventajas del porque lo recomiendan sería muy bueno! 😃  
	Gracias!

	* **Gabriel De Andrade (Platzi)** (2)

		
		Yo uso LastPass, tiene muy buena integración en múltiples dispositivos 😄

	* **David Behar** (2)

		
		Yo uso bitwarden, es gratis y me ha funcionado muy bien

* **Adalid Claure Galindo** (1)
Hola estoy buscando el curso de OWASP y no lo encuentro en platzi help me !

	* **Juan Felipe Peralta Zapata (Platzi)** (2)

		
		¡Hola, Adalid! ⚡
		
		Aquí te dejo el enlace: [Curso de Análisis de Vulnerabilidades Web con OWASP](https://platzi.com/clases/seguridad/)

## 0390. Conclusiones y cierre del curso

### Descripción:


 **¡Felicitaciones por terminar el Curso de Autenticación con Passport.js**

Hemos aprendido cómo autenticar a nuestro usuarios, manejar _middlewares_ de seguridad para poder autorizar a nuestro usuarios, inicio de sesión con redes sociales, buenas prácticas y mucho más.

Sabemos que ha sido un largo camino, pero estamos seguros de que valió la pena. Y recuerda, ¡ **nunca pares de aprender**!

### Links:

* [Curso de Integración Backend con Frontend](https://platzi.com/cursos/bff/)

### Comentarios:

* **jasanhdz** (6)

	
	Ahora si has terminado el curso, recuerda que puedes repasar el contenido acá:  
	<https://github.com/JasanHdz/passportjs/blob/master/notes/notes.md>  
	**¿Cuéntanos que te pareció el curso?** pd: ahora si éxito con tu examen. 😄

* **luisglopez7777** (2)

	
	Grupo de aprendizaje para temas relacionados a la Escuela de Javascript, interesados unanse aqui: <https://chat.whatsapp.com/LsR1Zt77zIV2bUw30fMQ3M>

* **jorgeoxi** (1)

	
	¡Excelente curso!
	
	Muchas gracias al Profesor Guillermo.

