# Apropiar el concepto de PWA

## 0010. Bienvenida e introducción al curso

### Descripción:


### Comentarios:

* **ehnbytes** (2)

	
	Iniciando el curso!!!

* **leonmg** (2)

	
	Gran curso!

* **Wilson Fabian Pérez Sucuzhañay** (2)

	
	Genial a darle con todo

* **predator0077** (1)

	
	Vamos a darle con todo!!! Angular is Love.

* **julio eder aguilar santos** (1)

	
	Excelente profesor, he aprendido mucho, Gracias.

## 0020. ¿Qué son las PWA

### Descripción:


### Comentarios:

* **leonmg** (6)

	
	Es interesante ver como desde compañias como Google apoyan el crecimiento de las PWA.  
	[LEs comparto este link con info util.  
	](https://developers.google.com/web/progressive-web-apps)

	* **fernandoogarcia** (1)

		
		wow gracias por el aporte!

	* **fernandajofili (Platzi)** (1)

		
		Qué interesante la información, gracias por compartirla! 💪

* **Eduardo Alejandro Yrady Brazon** (1)

	
	Hola Nico, como estas? Tengo una duda con respecto a las PWA con Angular, con esta tecnologia podré desarrollar una app que envíe un formulario al servidor sin tener conexion y que luego al recuperar la conexion envie todo en el form? (Datos, fotos, etc.) Gracias

	* **nicobytes** (2)

		
		Hola!
		
		Para aclarar dudas, no puede enviar datos a un server si no tienes internet y PWA no soluciona ese tipo de cosas, lo que hace PWA es guardar cache de los que ya has pedido como assets, requests, etc.
		
		Hay varias formas de lograr lograr esto que quieres desde leer con Network API el estado de la conexión y si esta offline guardar los datos en LocalStore y cuando haya internet la subes.
		
		Hay toda una gama de tecnologías de offline first que puedes revisar para estos casos.

## 0030. Características de una PWA

### Descripción:


### Links:

* [PWA Stats](https://www.pwastats.com/)

### Comentarios:

* **leonmg** (6)

	
	Características:
	
	  * Funciona Offline
	  * Speed ( Uso de cache)
	  * Push Notifications
	  * Web Based
	  * Deep Links ( Open App Using link) is easy to use in web, already use url/
	  * Small bundle.
	  * Easy to release and update.
	  * Desktop Icon
	
	

	* **fernandajofili (Platzi)** (1)

		
		Buen resumen, gracias por compartirlo. 😉

* **Santiago Cepeda** (2)

	
	Excelente

* **Agayalas** (1)

	
	buen curso

## 0040. PWA vs Híbrido vs Nativo

### Descripción:


### Comentarios:

* **leonmg** (3)

	
	PWA te permite atraer nuevos usuarios sin el complejo proceso que implica un app.
	
	Native - Brindar mejor experiencia

## 0050. Los Services Workers

### Descripción:


### Comentarios:

* **eduardovillarroel** (2)

	
	Un service worker es una secuencia de comandos que corren en segundo plano en el navegador.  
	Ejemplo: Push notification, guardar información en cache, deep links, etc.

* **Wilson Fabian Pérez Sucuzhañay** (2)

	
	la magia es preguntar a cache y luego preguntar a red por si existe contenido más actualizado.

	* **leonmg** (1)

		
		Así es, esto cuando predomina Cache.
		
		Ademas podemos usar Services Workers para otras cosas.

## 0060. Proyecto del curso Platzi Store

### Descripción:


### Links:

* [GitHub - PlatziStore](https://github.com/platzi/curso-pwa-angular)

### Comentarios:

* **luisangelmartinezcornejo** (2)

	
	npm install -g @angular/cli //instalar angular  
	npm i ng serve -o //instalar dependencias del proyecto e iniciar el servidor local

* **leonmg** (2)

	
	Genial!  
	Usaremos lo aprendido en el curso basico de Angular!

* **carlos-frostte** (1)

	
	Pero en el repositorio <https://github.com/platzi/curso-pwa-angular> veo ejercicios ya resueltos;  
	no deberíamos partir desde los archivos de la ultima clase del curso de Angular?

* **Hernan Blascovich** (1)

	
	¿Cuál es el curso anterior que hicieron la tienda online?

	* **nicobytes** (2)

		
		Hola! mira es en este: <https://platzi.com/clases/angular/>

* **Formación1** (1)

	
	Buenas noches,
	
	El repositorio no existe!
	
	Gracias.

	* **fernandajofili (Platzi)** (1)

		
		Hola!  
		👉 Aquí el [enlace ](https://github.com/platzi/curso-pwa-angular)del repositorio.

* **Wilson Fabian Pérez Sucuzhañay** (1)

	
	![Screenshot 2020-02-10 at 17.11.11.png](https://static.platzi.com/media/user_upload/Screenshot%202020-02-10%20at%2017.11.11-932f9bfa-a154-4157-8b37-981f705d262d.jpg)  
	El repositorio que dan en el apartado enlaces me da 404

	* **Gerardo Manuel Reyes Fernández** (2)

		
		<https://platzi.com/clases/1670-angular/23289-haciendo-deploy-a-firebase-hosting/>  
		en los recursos

	* **Wilson Fabian Pérez Sucuzhañay** (1)

		
		gracias

	* **luisangelmartinezcornejo** (0)

		
		Esos archivos causan problemas con la clase que sigue de este curso. Yo tome los archivos de una clase anterior <https://platzi.com/clases/1670-angular/23288-subiendo-una-imagen-a-firebase-storage/>

	* **nicobytes** (2)

		
		Hola ya esta publico! <https://github.com/platzi/curso-pwa-angular>

# Entender PWA en Angular

## 0070. Generando la primer PWA

### Descripción:


### Links:

* [Angular](https://angular.io/cli/add)

* [Firebase Hosting  |  Firebase](https://firebase.google.com/docs/hosting?hl=es)

### Comentarios:

* **Romel Javier Gomez Herrera** (3)

	
	Corriendo unos comandos es posible tener en localhost un server seguro falso, para probar con **https**
	
	<https://github.com/romelgomez/safelocalhost>
	
	  * Abre un terminal y ejecuta: `. ./safelocalhost.sh`
	  * Abre el navegador Chrome, e introduce en la barra de dirección URL: chrome://settings/certificates
	  * Selecciona la tab: Authorities
	  * Selecciona el archivo generado: `/safelocalhost/temp/root_crt.crt`
	  * Asegurate de marcar que todos los checkboxes de Trust settings
	  * Obtén la ruta completa a los archivos `server.crt` y `server.key` generados.
	  * Ejecuta:
	
	
	
	`ng serve --ssl true --ssl-cert $HOME"/Desktop/projects/safelocalhost/temp/server.crt" --ssl-key $HOME"/Desktop/projects/safelocalhost/temp/server.key"`
	
	  * luego visita <https://localhost/>
	
	

* **juanbarcinilla** (2)

	
	firebase init: inicia el servicio

* **juanbarcinilla** (1)

	
	comando para ejecutar pwa  
	ng add @angular/pwa

* **Ing Emmanuel Ramirez** (1)

	
	al hacer el firebase init me sale el siguiente error:
	
	=== Project Setup
	
	First, let’s associate this project directory with a Firebase project.  
	You can create multiple project aliases by running firebase use --add,  
	but for now we’ll just set up a default project.
	
	i .firebaserc already has a default project, using angular-pwa-platzi.
	
	Error: Failed to get Firebase project angular-pwa-platzi. Please make sure the project exists and your account has permission to access it.

	* **nicobytes** (2)

		
		Hola! si parece que al descargar el repo esta con la conf del curso puedes borrar el archivo **firebase.json** y volver a dar `firebase init`

	* **carlos-frostte** (1)

		
		Eliminar el firebase.json no me funciono, tuve que eliminar el .firebaserc y volver a hacer firebase init

* **Ing Emmanuel Ramirez** (1)

	
	como lo puedo ejecutar en ubuntu 18.04?

	* **nicobytes** (1)

		
		Hola!
		
		Para levantar el proyecto solo es necesario correr `ng serve` para esos debes antes instalar las dependencias con `npm install`

* **Formación1** (1)

	
	Este es el comando para añadir las referencias de PWA.  
	ng add @angular/pwa

* **Juan Ventrone** (1)
cuando ejecuto: ng build --prod imprime: The build command requires to be run in an Angular project, but a project definiti...

	* **nicobytes** (1)

		
		Hola! parece que esto es un error con tu dependencias o con archivo angular.json, revisa estos dos y vuelve a instalar todas las dependencias.

* **Ing Emmanuel Ramirez** (1)
al hacer el firebase init me sale el siguiente error: === Configuración del proyecto Primero, asociemos este directorio de proyecto con u...

	* **nicobytes** (1)

		
		Hola! si parece que al descargar el repo esta con la conf del curso puedes borrar el archivo **firebase.json** y volver a dar `firebase init`

## 0080. Caché local y pruebas offline

### Descripción:


### Comentarios:

* **BrayanValdesG** (1)

	
	¿Cuándo ejecuto ng add @angular/pwa me genera unos iconos por defecto con el icono de Angular, es posible lanzar un comando para generar esos iconos de mi propio icono en sus diferentes tamaños?

	* **juanbarcinilla** (2)

		
		esa parte la hace ionic resource icon, pero pwa no tiene esa integración de generar las imágenes.

	* **nicobytes** (2)

		
		Hola! no hasta ahora no hay algo que te genere a partir de una imagen las dimensiones necesarias, entonces debes tu generarlas.
		
		También la comunidad ha hecho scripts para esto que pueden ayudar: <https://github.com/ezzabuzaid/pwa-icon-generator>

	* **BrayanValdesG** (1)

		
		Gracias nico, lastimosamente estoy pasandole un icono muy pequeño y me lo genera pixelado, pero funciona, muchas gracias

## 0090. Pruebas con Lighthouse

### Descripción:


### Links:

* [Lighthouse - Chrome Web Store](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=es)

* [Curso de Rendimiento en Angular](https://platzi.com/clases/angular-performance/)

* [Curso de Accesibilidad Web](https://platzi.com/clases/accesibilidad-web/)

* [Curso de Introducción a SEO: Posicionamiento en Buscadores](https://platzi.com/clases/seo/)

### Comentarios:

* **charly300_fede** (6)

	
	A partir de la versión 60 de Google Chrome, la herramienta Lighthouse viene integrada en el navegador. Sólo tienen que abrir la consola (F12) e ir a la pestaña “Audits”. Al parecer funciona igual que la extensión, así que no haría falta instalarla.

	* **fernandajofili (Platzi)** (1)

		
		¿Ah, sí? Yo no sabía de eso. 🤔

## 0100. Caché de assets

### Descripción:


### Comentarios:

* **eduardovillarroel** (1)

	
	Que pasa con los módulos que se cargan con lazy loading en angular, estos archivos igual son cacheados la primera vez que se ingresa a la aplicación?

	* **nicobytes** (1)

		
		Hola! si estos ya también son ingresados al cache básicamente el revisa todos los assets (html, imgs, js, y css ) tengamos y los pone en el cache

## 0110. Caché de requests

### Descripción:


### Comentarios:

* **Formación1** (2)

	
	Configuración de cache:  
	“dataGroups”: [  
	{  
	“name”: “api”,  
	“urls”: [  
	“<https://platzi-store.herokuapp.com/**>”  
	],  
	“cacheConfig”: {  
	“maxSize”: 3,  
	“maxAge”: “5m”,  
	“strategy”: “performance”,  
	“timeout”: “2s”  
	}  
	}  
	]

* **Andres Gallardo** (1)

	
	El cache es por sesion de navegador ? O como funciona ?

	* **nicobytes** (1)

		
		Hola!
		
		Este cache queda guardado al navegador directamente y no queda asociando a la sesión del usuario en la pagina.
		
		Aunque si manejas la sincronización dentro de Google Chrome con tu Gmail esto si se mantiene por cada usuario.

# Construir una PWA luciendo como nativa

## 0120. Poniendo tu app en el Homescreen

### Descripción:


### Comentarios:

* **José Luis García Peceros** (1)

	
	short_name -> aparece en el Homescreen de la aplicación  
	name -> landing page o splash screen

* **BRYAN ALEXANDER CONDOR DE LA CRUZ** (1)
¿algun articulo, donde puedan ver como poner un splash screen con el diseño personalizado?

	* **Juan David Castro (Platzi)** (2)

		
		Las configuraciones que podemos darle a la splash screen son muy limitados: <https://dev.to/akshaykumar6/progressive-web-apps-custom-splash-screen-ce7>. 🤔

## 0130. Crear botón de instalación automática

### Descripción:


### Links:

* [Curso Profesional de Angular](https://platzi.com/clases/angular-profesional)

### Comentarios:

## 0140. Probar funcionalidad del botón de instalación

### Descripción:


### Comentarios:

* **juanbarcinilla** (2)

	
	Muy buena practica para implementar.

* **FrancescoTotti** (1)

	
	Que bueno!!! Me quedé sin audio, esto no se puede implementar en IOS verdad? Sólo Android?
	
	Cómo puedo implementar esto mismo pero con Google Materialize?

	* **Gabriel De Andrade (Platzi)** (3)

		
		Si, en clases siguientes aprendemos a hacer el proceso de instalación en iOS. Tenemos un [Curso de Materialize](https://platzi.com/clases/materialize/), recuerda que esto es sólo un framework CSS y lo estarías implementando en una web responsive 😄

	* **FrancescoTotti** (2)

		
		1- O sea que ¿si se puede hacer un botón de instalación para IOS?, seguro???
		
		2- Yo lo que hago es un PWA, en el curso ven Angular, yo utilizo Materialize. Y creo mi Service Worker, mi manifest y al entrar a internet me lanza el ADD TO HOME SCREEN en android y no en IOS porque entiendo que no es compatible. Entonces, viendo esta clase veo que se puede crear unboton mas bonito que diga instalar, quizas no ese add to home que parece que es una web, pero bueno, queda ver eso que dices de que si se puede para IOS. Gracias

	* **Gabriel De Andrade (Platzi)** (1)

		
		[Implementación y recomendaciones para IOS  
		](https://platzi.com/clases/1818-pwa-angular/26119-implementacion-y-recomendaciones-para-ios/) acá hacemos la implementación en iOS 😄

	* **FrancescoTotti** (1)

		
		Muchas gracias lo voy a ver!!!

## 0150. Enviando actualizaciones

### Descripción:


### Links:

* [Firebase Cloud Messaging  |  Firebase](https://firebase.google.com/docs/cloud-messaging?hl=es)

### Comentarios:

* **juanbarcinilla** (1)

	
	Buena forma de actualizar el service worker.

## 0160. Implementando flujo de notificaciones

### Descripción:


### Links:

* [Curso de Firebase para Web](https://platzi.com/clases/firebase-web)

* [Console Firebase](https://console.firebase.google.com)

### Comentarios:

## 0170. Gesitionando notificaciones

### Descripción:


### Links:

* [Set up a JavaScript Firebase Cloud Messaging client app  |  Firebase](https://firebase.google.com/docs/cloud-messaging/js/client)

### Comentarios:

* **Ricardo Betancourt** (1)

	
	como puedo enviar notificaciones personalizadas desde el modulo de administracion y no por la consola de firebase ??

	* **Spyderp** (1)

		
		Se utiliza un api de google. En el cual por medio del token de otro usuario poder enviar mensaje directo o enviar a todo los usuarios.
		
		[mayor información](https://firebase.google.com/docs/cloud-messaging/js/first-message)

* **Carlos Tangarife** (1)

	
	Hola,  
	que pasa cuando en mi smartPhone queremos enviar notificaciones a una PWA, si llegan las notificaciones push cuando mi celular esta en bloqueado, algo similar a como funciona whatsapp.

	* **Spyderp** (1)

		
		el manejador de notificaciones de tu celular lo pondra en la cola. Se vera igual a las de whatsapp

## 0180. Implementación y recomendaciones para IOS

### Descripción:


### Comentarios:

* **Facundo Nicolás García Martoni (Platzi)** (4)

	
	Compañeros, les recomiendo la plataforma de [Real Favicon Generator](https://realfavicongenerator.net/) para generar los diferentes íconos para Android y IOS de manera interactiva 😃

	* **Wilson Fabian Pérez Sucuzhañay** (1)

		
		ratito como hace 10 días si se lanzo ayer mmmm jaja esta mal el moment de platzi jaja

	* **Gabriel De Andrade (Platzi)** (3)

		
		Wilson no está mal, Facundo es Associate, eso quiere decir que tiene acceso a los cursos antes de que sean lanzados para así asegurar su calidad 😄

* **BrayanValdesG** (2)

	
	Reto casí logrado, me salen estos mensajes, que no se realmente como solucionar, el Learn more tampoco explica mucho a que se deba ![Captura de pantalla \(607\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%28607%29-ca39f30d-9e45-4ee1-be46-087825345f2f.jpg)

	* **nicobytes** (2)

		
		Wow excelente casi tienes el 100 en todos los puntos, felicitaciones!

# Integrar continuamente

## 0190. Aplicando Lighthouse Bot a tu proceso de integración continua

### Descripción:


### Links:

* [lighthouse - npm](https://www.npmjs.com/package/lighthouse)

### Comentarios:

* **tzalejo** (2)

	
	Buenas dejo un buen articulo de [Lighthouse](https://pwaexperts.io/blog/que-es-lighthouse-google-como-realizar-test-pwa)  
	Saludos

## 0200. Conclusiones

### Descripción:


### Links:

* [Curso Profesional de Angular](https://platzi.com/clases/angular-profesional/)

* [Curso de Rendimiento en Angular](https://platzi.com/clases/angular-performance/)

### Comentarios:

* **BrayanValdesG** (2)

	
	Muy buen Curso, muchas gracias Nico

* **tzalejo** (1)

	
	Gracias Nico!!excelente curso!!Revivieron Angular con Nico jaja…  
	Saludos.

* **AmarelleDiArgento** (1)

	
	Muchisimas gracias un excelente curso 😄

