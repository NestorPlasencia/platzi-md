[Curso de Firebase Cloud Functions 1472](https://platzi.com/cursos/firebase-cloud)

# Bienvenida e Introducción [3303]

## 0010. Introducción al curso [16629](https://platzi.com/clases/1472-firebase-cloud/16629-introduccion5134/)

### Descripción:


Bienvenido al Curso de Firebase Cloud Functions. Vamos a crear la **lógica de negocio** de nuestras aplicaciones ejecutando funciones de Firebase a partir de diferentes **eventos** , incluso utilizando integraciones a la plataforma de Firebase como Crashlytics, Analytics o Firebase Hosting. Tambien vamos a trabajar con pruebas unitarias para verificar el funcionamiento de nuestro código utilizando casos reales.

Esta vez nuestro profesor también es Juan Guillermo Gómez, Google Developer Expert en la plataforma de Firebase. Recuerda que puedes tomar el [Curso de Firebase para Web](https://platzi.com/clases/firebase-web/) si quieres aprender los fundamentos de esta herramienta y construir desde 0 el proyecto que vamos a continuar trabajando en este curso.

### Links:

* [Cloud Functions: Go 1.11 is now a supported language | Google Cloud Blog](https://platzi.com/tutoriales/1472-firebase-cloud/3445-cloud-functions-go-111-is-now-a-supported-language-google-cloud-blog/)

* [Firebase](https://firebase.google.com)

* [Firebase Crashlytics  |  Firebase](https://firebase.google.com/docs/crashlytics/?hl=es-419)

* [Firebase Hosting  |  Firebase](https://firebase.google.com/docs/hosting/?hl=es-419)

### Comentarios:

* **Juan David Castro (Platzi)** (5) [479247](https://platzi.com/comentario/479247/) 

	Notas de la clase:
	
	* 🏈 Durante el curso, vamos a crear la lógica de negocio (el código backend) que ejecutamos en forma de funciones cuando suceden diferentes eventos.
	* 🐙 Algunos eventos a los que podemos reaccionar para ejecutar una función son, por ejemplo, cuando modificamos la base de datos, añadimos un usuario, subimos un archivo, entre otras.
	* 🐊 También podemos reaccionar a eventos de otros servicios integrados a la plataforma de Firebase, como Crashlytics o Google Analytics.
	* 👌 Vamos a desarrollar pruebas unitarias _(unit testing)_ para verificar el correcto funcionamiento del código de nuestras funciones.
	
	
	
	Entre otras cosas:
	
	* 👞 El profe trabaja como 🔥[Google Developer Expert en Firebase](https://developers.google.com/experts/all/technology/firebase)🔥 y también es CTO de [Progressus](https://progressus.com.co/) (una plataforma de salud mental 💆).
	* 🤓 El proyecto del curso es [Blogeek](https://blogeekplatzi.firebaseapp.com/), vamos a añadir funcionalidades al proyecto del [Curso de Firebase para Web](https://platzi.com/firebase-web) que debemos tomar antes de empezar.
	
	

* **María Guadalupe Borjas González** (2) [479070](https://platzi.com/comentario/479070/) 

	Estaba esperando mucho este curso :3

* **Alexander Mateo** (1) [514865](https://platzi.com/comentario/514865/) 
Vamos a comprobar todo lo que hice en mi último proyecto está bien jajaj

* **Alexander Mateo** (1) [514864](https://platzi.com/comentario/514864/) 
Vamos a comprobar si todo lo que hice en el último proyecto está bien jajaja

## 0020. Qué es firebase y las cloud functions [16631](https://platzi.com/clases/1472-firebase-cloud/16631-que-es-firebase-que-son-las-cloud-functions-y-proy/)

### Descripción:


Firebase es un **Backend como Servicio** , una herramienta que nos permite agilizar el desarrollo de nuestras aplicaciones, en vez de desarrollar diferentes funcionalidades desde 0, podemos utilizar Firebase para completar tareas como crear y autenticar usuarios, guardar nuestra información en bases de datos, almacenar archivos estáticos, administrar la infraestructura, analizar métricas, entre muchas otras.

Gracias a Firebase **automatizamos y agilizamos** todos estos servicios en una misma plataforma integrada sobre la infraestructura de Google Cloud.

Las **Cloud Functions** nos permiten crear y alojar la lógica de negocio de nuestras aplicaciones (el código backend) sin necesidad de preocuparnos por la escalabilidad o el mantenimiento de infraestructura. Estas funciones se activan en respuesta a eventos, por ejemplo, cuando un usuario se registra, cuando subimos una imagen, pedimos una factura, realizamos una compra, etc.

### Links:

* [Firebase](https://firebase.google.com/)

* [Firebase](https://firebase.google.com/pricing/)

* [Cloud Functions for Firebase  |  Firebase](https://firebase.google.com/docs/functions/)

* [Cloud Functions for Firebase (video series)  |  Firebase](https://firebase.google.com/docs/functions/video-series/)

* [Cloud Functions locations  |  Firebase](https://firebase.google.com/docs/functions/locations)

* [Curso de Firebase para Web](https://platzi.com/cursos/firebase-web/)

### Comentarios:

* **Juan David Castro (Platzi)** (8) [479248](https://platzi.com/comentario/479248/) 

	Repaso de Firebase:
	
	* 💺 Es un **BaaS** o Backend como Servicio, nos permite utilizar código ya hecho para autenticar usuarios, guardar información en las bases de datos, alojar nuestras aplicaciones, subir imágenes o archivos estáticos, entre otras.
	* 🍎 Nos permite construir aplicaciones para [Android](https://platzi.com/clases/firebase/), [IOS](https://platzi.com/clases/apps-ios/) y para [Web](https://platzi.com/clases/firebase-web).
	* 🍔 Esta construido sobre la infraestructura de [Google Cloud](https://cloud.google.com/).
	
	
	
	Cloud Functions:
	
	* 👼 Son código backend que ejecutamos como respuesta a ciertos eventos soportados por la plataforma de Firebase, nos evita preocuparnos por el mantenimiento de la infraestructura (BTW, _Serverless_ ) y nos permite desarrollar funcionalidades extra, es decir, cosas que no podemos hacer en el frontend.
	* 💸 Tenemos la opción de no pagar hasta cierto punto de invocaciones o podemos pagar por cada x veces que se ejecutan nuestras funciones (es relativamente barato).
	
	

* **Matias Niz** (4) [484174](https://platzi.com/comentario/484174/) 

	He utilizado y utilizo cloud functions, un caso de uso típico es el almacenar una marca de tiempo, si necesitamos conocer qué día y hora se realizó un registro, no podemos depender de la hora del dispositivo del usuario ya que esta puede ser alterada. Al recibir el registro podemos disparar una función que actualice el registro con la hora actual del servidor.

* **María Guadalupe Borjas González** (4) [479072](https://platzi.com/comentario/479072/) 

	firebase: aplicaciones ágiles y rápidas con auto crecimiento dependiendo de la cantidad de usuarios con herramientas para mejorar los desarrollos

	* **María Guadalupe Borjas González** [479072] (4)

		Con firebase no nos preocupamos por los fierros, solo programar y ya :3

	* **ferhomely** [479072] (2)

		En realidad lo dejas para después, lo tendrás que hacer tarde o temprano.

* **Andres Leon** (3) [693199](https://platzi.com/comentario/693199/) 

	Cuando se actualiza un nodo de firebase (desde android por ejemplo ) y el back debe saber ese cambio y guardarlo en una base de datos sql. se realiza una función en donde se ejecute(llamar) el servicio del back y baje hasta hacer la actualización correspondiente con los datos obtenidos de la función de firebase.

* **Juan David Castro (Platzi)** (2) [514001](https://platzi.com/comentario/514001/) 

	* [¿Qué son las Cloud Functions? Carlos Azaustre](https://youtu.be/WeABVtYYFaw)
	
	

* **Fabian Siatama** (2) [479283](https://platzi.com/comentario/479283/) 

	Estoy realizando una aplicación y había desistido de Cloud functions porque los tiempos de respuesta no son tan buenos, por ejemplo, cuando un usuario hace like sobre un item, se ejecuta una función que actualiza el contador de likes. Esto tomaba de 2 a tres segundos en ejecutar, seguramente algo estoy haciendo mal, por eso me parece perfecto el curso ya que los demás productos de Firebase son muy buenos y me han ahorrado un montón de tiempo en varios proyectos.

	* **Carlos Eduardo Sanchez Torres** [479283] (2)

		Creo yo, amigo mio. Que cuando los tiempos son prioridad, una opcion seria usar directamente Firestore y dejar la logica de negocio en el frontend (claro esta que en un framework como Angular o React).

* **Ramiro Villena** (1) [1074974](https://platzi.com/comentario/1074974/) 

	Cuando se crea un sub colección dentro de una colección y pasado 5 minutos esta tiene que ser eliminada si es que su estado no cambia a “true” - Alguien sabe como hacerlo??

* **VG_Analistas** (1) [585478](https://platzi.com/comentario/585478/) 

	Hola a todos, alguien podría ampliar sobre Event-driven architecture y que herramienta(s) de GCP me puede ayudar con este tema. Muchas gracias de antemano por tu gentil ayuda.

	* **Diego Alexander Forero Higuera (Platzi)** [585478] (2)

		Hola, hay mucha información en internet, encontré en una búsqueda rápida esto <https://en.wikipedia.org/wiki/Event-driven_architecture>, básicamente esta arquitectura esta basada en eventos, se considera un evento el cambio de estado de un elemento, por ejemplo cuando tienes un biblioteca y un libro es solicitado para leerlo, cambia el estado de **disponible** a **en uso**.  
		En cuanto a GCP tienen servicios serverless principalmente para usarlos con esta arquitectura te dejo un par de links que te pueden servir <https://cloud.google.com/blog/products/gcp/implementing-an-event-driven-architecture-on-serverless-the-smart-parking-story>.  
		GCP usa <https://cloud.google.com/functions/> que es similar a aws lambda.

* **juan david  jaramillo zuñiga** (1) [525369](https://platzi.com/comentario/525369/) 

	Una pregunta, estoy desarrollando mi app y quería saber cuales son las razones además de buena practica por las cuales hacer la lógica del negocio en el backend suponiendo que soy un uberclone

	* **Diego Alexander Forero Higuera (Platzi)** [525369] (4)

		La mas importante es que tienes seguridad de tu aplicación, porque el backend no se puede modificar desde la app, si toda tu lógica esta en la app es vulnerable a ataques. Uber tiene un backend muy robusto basado en microservicios y eso hace que sea más complejo y dificil del vulnerar, si la logica solo estuviera en la app entonces se puede hackear para tener viajes gratis por ejemplo.

	* **Jhon Alexander Perez Valencia** [525369] (4)

		GOLLUM23 nominado para el premio de mejores respuestas en todos los cursos de platzi 🎉🎉🎂👏👏🎁

* **VG_Analistas** (1) [59014](https://platzi.com/comentario/585478/) 
Hola a todos, alguien podría ampliar sobre Event-driven architecture y que herramienta(s) de GCP me puede ayudar con este tema. Muchas gr...

	* **Diego Alexander Forero Higuera (Platzi)** [59014] (2)

		Hola, hay mucha información en internet, encontré en una búsqueda rápida esto <https://en.wikipedia.org/wiki/Event-driven_architecture>, básicamente esta arquitectura esta basada en eventos, se considera un evento el cambio de estado de un elemento, por ejemplo cuando tienes un biblioteca y un libro es solicitado para leerlo, cambia el estado de **disponible** a **en uso**.  
		En cuanto a GCP tienen servicios serverless principalmente para usarlos con esta arquitectura te dejo un par de links que te pueden servir <https://cloud.google.com/blog/products/gcp/implementing-an-event-driven-architecture-on-serverless-the-smart-parking-story>.  
		GCP usa <https://cloud.google.com/functions/> que es similar a aws lambda.

# Consola web de administración [3304]

## 0030. Consola de administración y documentación [16630](https://platzi.com/clases/1472-firebase-cloud/16630-consola-de-administracion-y-documentacion/)

### Descripción:


### Links:

* [Manage project access with Firebase IAM  |  Firebase](https://firebase.google.com/docs/projects/iam/overview)

* [Cloud Functions for Firebase  |  Firebase](https://firebase.google.com/docs/functions/)

* [Curso de Firebase para Web](https://platzi.com/cursos/firebase-web/)

* [Firebase](https://firebase.google.com)

### Comentarios:

* **Eduard Martinez** (4) [520655](https://platzi.com/comentario/520655/) 

	Alguien sabe como incrementar el limite de proyectos por default?
	
	Ya hice el formulario de expansión pero no han resuelto nada.
	
	Gracias

	* **Juan David Castro (Platzi)** [520655] (3)

		¡Hola! Seguro que ya te han dado respuesta a tu formulario. Pero en caso de que no (solo por si acaso), podrías crear otros 6 proyectos usando otra cuenta de Gmail.
		
		– <https://stackoverflow.com/questions/41485736/firebase-maximum-projects-and-apps>

* **Carolina Londoño** (1) [830195](https://platzi.com/comentario/830195/) 

	Se debe crear un proyecto nuevo ademas del que ya teniamos del curso Firebase para la Web?

* **Eduard Martinez** (1) [53684](https://platzi.com/comentario/520655/) 
Alguien sabe como incrementar el limite de proyectos por default? Ya hice el formulario de expansión pero no han resuelto nada. Gracias

	* **Juan David Castro (Platzi)** [53684] (3)

		¡Hola! Seguro que ya te han dado respuesta a tu formulario. Pero en caso de que no (solo por si acaso), podrías crear otros 6 proyectos usando otra cuenta de Gmail.
		
		– <https://stackoverflow.com/questions/41485736/firebase-maximum-projects-and-apps>

* **Esteban Rivera Rodriguez** (0) [1057119](https://platzi.com/comentario/1057119/) 

	Hola, una consulta con respecto a los planes que comentaste en la clase anterior esos valores corresponden por proyecto o por usuario es decir si tengo 5 proyectos la suma de todas las invocaciones deben ser menos de 125K o cada proyecto es independiente? si quiero seguir en el plan free.  
	Gracias!

## 0040. Creación del proyecto de Cloud Functions [16632](https://platzi.com/clases/1472-firebase-cloud/16632-creacion-del-proyecto-de-cloud-functions/)

### Descripción:


Vamos a ejecutar los siguientes comandos para instalar y preparar las herramientas de nuestro proyecto en Firebase:

  1. Instalación: `npm install -g firebase-tools`

  2. Login: `firebase login`

  3. Iniciar el proyecto e instalar las dependencias necesarias: `firebase init functions`

  4. Desplegar todas las funciones `firebase deploy --only functions`

  5. Desplegar solo una función: `firebase deploy --only functions:NombreDeLaFunción`

  6. Borrar una función: `firebase functions:delete NombreDeLaFunción`

  7. Visualizar el log (el texto imprimido en la consola) de todas las funciones desplegadas: `firebase functions:log`




### Links:

* [Get started: write and deploy your first functions  |  Firebase](https://firebase.google.com/docs/functions/get-started)

* [firebase-tools  -  npm](https://www.npmjs.com/package/firebase-tools)

### Comentarios:

* **Juan David Castro (Platzi)** (5) [479250](https://platzi.com/comentario/479250/) 

	🗺 Podemos cambiar la región de despliegue o el espacio que ocupan nuestras funciones utilizando solo código de JavaScript:
	``` 
	    # Normal:
	    exports.helloWorld = functions.https.onRequest((request, response) => {
	            response.send("Hello from Firebase!");
	    });
	    
	    # Cambiar la región:
	    exports.helloWorld = functions.region("NOMBRE DE LA REGIÓN. Ex. asia-northeast1").https.onRequest((request, response) => {
	            response.send("Hello from Firebase!");
	    });
	    
	    # Cambiar el espacio:
	    exports.helloWorld = functions.runWith("Cantidad de GB. Ex. 1GB").https.onRequest((request, response) => {
	            response.send("Hello from Firebase!");
	    });
	    
	```
	
	📚 Podemos encontrar toda esta y muchísima más información en [Administra la implementación de funciones y las opciones de tiempo de ejecución - Firebase Docs](https://firebase.google.com/docs/functions/manage-functions?hl=es-419).

* **Matias Niz** (4) [484273](https://platzi.com/comentario/484273/) 

	Que plugin hace que salga una llama cada vez que escribes en VS Code?

	* **ebar0n (Platzi)** [484273] (3)

		Hola, intenta revisar esto [icon-theme](https://code.visualstudio.com/api/extension-guides/icon-theme), debe ser un tema de iconos.

	* **Matias Niz** [484273] (2)

		Hola ebar0n, gracias pero el plugin se llama Power Mode

* **kikeRC** (3) [572394](https://platzi.com/comentario/572394/) 

	Si tiene un error de acceso de escritura, en macbook, agregar la palabra **sudo** npm install -g firebase-tools

	* **Everson Vidal Mamani Huayta** [572394] (1)

		tem kiu…!! XD

* **Mauro Volpe** (2) [552087](https://platzi.com/comentario/552087/) 

	como puedo usar la sintaxis de ES6 (import, async/await) para escribir mis cloud functions? Estoy emilandolas sobre node 8 pero parece no ser suficiente ya que me tira error de sintaxis!

	* **AndrsDev** [552087] (2)

		En este link encontrarás la solución,  
		<https://firebase.google.com/docs/functions/manage-functions#set_nodejs_version>

	* **Juan David Castro (Platzi)** [552087] (1)

		Como dice Andrés, puedes cambiar la versión de Node.js por una que soporte las _features_ que necesitas. O también puedes usar babel para compilarlo todo para la versión que quieras usar. 😉

* **joseadrian** (2) [530657](https://platzi.com/comentario/530657/) 

	En que situaciones seria conveniente ampliar la memoria RAM? si al momento de subirla me da el uso minimo o no

	* **ebar0n (Platzi)** [530657] (1)

		Hola, debes ver el uso que tienes, en servidores normales, lo ideal es que solo se use el 70% de la memoria RAM, entonces si lo amplias tomando en cuenta eso, genial.

	* **jggomezt** [530657] (3)

		Al momento de subirla te la lo minimo. Cuanto subir?? depende de la cantidad de usuarios, de lo que hace la función, puedes realizar pruebas de rendimiento, ejemplo con Artillery y sacar conclusiones si es suficiente la RAM

* **Eder Jesus Avendaño Santos** (2) [523828](https://platzi.com/comentario/523828/) 

	me salta el siguiente error alguien sabra por que?
	``` 
	    ✔  functions: Finished running predeploy script.
	    i  functions: ensuring necessary APIs are enabled...
	    ✔  functions: all necessary APIs are enabled
	    i  functions: preparing functionsdirectoryfor uploading...
	    i  functions: packaged functions (41.64 KB) for uploading
	    ✔  functions: functions folder uploaded successfully
	    i  functions: updating Node.js 8 function helloWorld(us-central1)...
	    ⚠  functions[helloWorld(us-central1)]: Deployment error.
	    Failed to retrieve function source code
	    
	    
	    Functions deploy had errors with the following functions:
	            helloWorld
	    
	    
	    To try redeploying those functions, run:
	        firebase deploy --only functions:helloWorld
	    
	    
	    To continue deploying other features (such as database), run:
	        firebase deploy --except functions
	    
	    Error: Functions did not deploy properly.
	    
	    Having trouble? Try firebase deploy --help
	    
	```

	* **Juan David Castro (Platzi)** [523828] (1)

		👋 ¡Hola!
		
		¿Seguiste las instrucciones que te muestra la consola? Lo de correr el comando **`firebase deploy --only functions:helloWorld`**.
		
		SI lo hiciste y aún así no funcionó, ¿puedes mostrarnos tu código? Tal vez así podamos encontrar el error. 💪😉🐛

* **Juan David Castro (Platzi)** (2) [479251](https://platzi.com/comentario/479251/) 

	* [Primeros pasos: Cómo escribir y también implementar tus primeras funciones - Firebase Docs](https://firebase.google.com/docs/functions/get-started?hl=es-419)
	* [Firebase Cloud Functions — Instalación y primeros pasos en español - Medium](https://medium.com/@jofigueredo/firebase-cloud-functions-instalaci%C3%B3n-y-primeros-pasos-en-espa%C3%B1ol-bc34413a5ce1)
	
	

* **joseadrian** (2) [54499](https://platzi.com/comentario/530657/) 
En que situaciones seria conveniente ampliar la memoria RAM? si al momento de subirla me da el uso minimo o no

	* **ebar0n (Platzi)** [54499] (1)

		Hola, debes ver el uso que tienes, en servidores normales, lo ideal es que solo se use el 70% de la memoria RAM, entonces si lo amplias tomando en cuenta eso, genial.

* **luisrangelc** (1) [1061418](https://platzi.com/comentario/1061418/) 

	Si vienen del curso anterior y descargan este nuevo proyecto. Deben de actualizar el archivo:  
	.firebaserc
	``` 
	    {
	      "projects": {
	        "default": "XXXXXXX"
	      }
	    }
	    
	```

* **Francisco Karriere** (1) [73167](https://platzi.com/comentario/829808/) 
Pregunta.Si esta inicializado el proyecto en android studio y luego voy a visual studio code. Toca volve...

	* **Erik Ochoa** [73167] (1)

		No es necesario, las firebase tools que instalas desde NPM se guardan en un directorio llamado _node_modules_ y no importa qué editor uses, ese directorio va a estar ahí.

* **arnoldkba** (1) [63770](https://platzi.com/comentario/664623/) 
Tengo la siguiente falla: There was an issue deploying your functions. Verify that your project has a Google App Engine instance se...

	* **JULIO ESMERAL** [63770] (1)

		Tengo este mismo problema ![Captura de Pantalla 2019-07-25 a la\(s\) 5.24.56 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-07-25%20a%20la%28s%29%205.24.56%20p.%20m.-912a72c1-c347-4faa-9965-3ca8f7837adc.jpg)

# Extendiendo la Gestión de Usuarios con Cloud Functions. [3305]

## 0050. Creación de las cloud functions de autenticación [16633](https://platzi.com/clases/1472-firebase-cloud/16633-creacion-de-las-cloud-functions-de-autenticacion/)

### Descripción:


Vamos a escribir el código de nuestra aplicación separando la conexión con Firebase de la lógica de negocios.

Vamos a utilizar el archivo `functions/index.js` para recibir la información que nos envía Firebase cuando un usuario se registra o se elimina, así, en otro lugar diferente y dependiendo de la organización de nuestra aplicación, podemos escribir el código que nuestra aplicación debe ejecutar cuando sucenden estos diferentes eventos (por ejemplo, enviar un correo o emitir una factura cuando los usuarios realizan una cierta acción).
``` 
    exports.NOMBRE_DE_NUESTRA_FUNCIÓN = functions.auth
            .user()
            .onCreate(/* Código que ejecutamos cuando creamos un usuario */)
            .onDelete(/* Código que ejecutamos cuando eliminamos un usuario */)
    
```

### Links:

* [Extend Firebase Authentication with Cloud Functions  |  Firebase](https://firebase.google.com/docs/auth/extend-with-functions)

* [https://firebase.google.com/docs/auth/extend-with-functions](https://firebase.google.com/docs/auth/extend-with-functions)

### Comentarios:

* **Juan David Castro (Platzi)** (9) [479254](https://platzi.com/comentario/479254/) 

	🙀 Si escribimos todo el código en un solo archivo (sin ningún tipo de orden u organización) vamos a tener la tarea super complicada de cambiar o mejorar el código cuando sea necesario, sobretodo si trabajamos en equipo porque nuestro proyecto cambiará de herramientas, incluso podemos dejar de utilizar Firebase 😰.
	
	En cambio, organizando el proyecto así como propone el profe podemos tener muuuy claro en donde nos comunicamos con Firebase y en dónde esta nuestro código con la lógica de negocio 👌.

* **Miguel Mendoza** (3) [708534](https://platzi.com/comentario/708534/) 

	Me parece excelente que muestren cual es la forma mas eficaz de organizar el codigo, pero lo que no me parece, es que tenga que estar introduciendome en el codigo sin conocimiento alguno, mas que el minimo dado en la clase para poder lograr entender lo que se quiere lograr, siento que no esta nada bien.

	* **Daniel Esteves** [708534] (1)

		¡Hola Miguel! Para poder usar Firebase solo necesitas dominar el lenguaje de tu preferencia, si manejas PHP, JavaScript, Ruby o cualquier otro Firebase ya tiene integraciones con ese tipo de lenguajes

* **luisrangelc** (1) [1067471](https://platzi.com/comentario/1067471/) 

	Que bonito es lo bonito!!!

* **happiestack** (1) [885005](https://platzi.com/comentario/885005/) 

	Esto curso paso de 0 a 120 en una clase, de perdida invitame a ver netflix antes de sacar todo ese codigo.

	* **esteban-meza** [885005] (2)

		ingresa al curso de jquery a js ese te servira

* **Christian Gonzalez** (1) [625707](https://platzi.com/comentario/625707/) 

	esas funciones, incluso la que envie el correo, donde la explica? en el curso de ‘firebase para la web’? esa logica de negocio para registrar los correos, y enviar correos…no la encuentro explicada, capaz pertenece a otro curso…

	* **Disando7** [625707] (3)

		Para “ahorrar tiempo”, solo muestra el código y lo da en los archivos del curso, también me sentí igual. Pero ahí está en los archivos del curso, tenés que revisar el código y hallarle la lógica.

* **Oscar Salamanca** (1) [569987](https://platzi.com/comentario/569987/) 
Como puedo incorporar ese método de autenticación en una pagina que fue diseñada en wix?

* **vpanchojs** (1) [548619](https://platzi.com/comentario/548619/) 

	La forma en que se organiza el código me parece excelente, pero me gustaría que se explicara también utilizando typescript

* **joseadrian** (1) [530663](https://platzi.com/comentario/530663/) 

	Como sé que parametros me proporcionara, en este caso usuario, porque yo se lo pido en el usuarioCreacionController = usuario o es asi está definido en user().onCreate()?

	* **luisbo85** [530663] (2)

		Para saber que parametros recibiras, necesitas saber el contexto en que haces la llamada. Como esta trabajando con la creacion de usuarios solo recibe como parametro la informacion de un suario. El siguiente link tiene mas informacion. <https://firebase.google.com/docs/functions/auth-events?hl=es-419>

* **joseadrian** (1) [530660](https://platzi.com/comentario/530660/) 

	Buenas practicas, es la primera vez que veo el desarrollo aplicando estos conceptos y explicandolos al momento.

* **joseadrian** (1) [54500](https://platzi.com/comentario/530663/) 
Como sé que parametros me proporcionara, en este caso usuario, porque yo se lo pido en el usuarioCreacionController = usuario o es asi es...

	* **luisbo85** [54500] (2)

		Para saber que parametros recibiras, necesitas saber el contexto en que haces la llamada. Como esta trabajando con la creacion de usuarios solo recibe como parametro la informacion de un suario. El siguiente link tiene mas informacion. <https://firebase.google.com/docs/functions/auth-events?hl=es-419>

## 0060. Probando y desplegando las Cloud Functions de autenticación [16634](https://platzi.com/clases/1472-firebase-cloud/16634-probando-y-desplegando-las-cloud-functions/)

### Descripción:


Firebase nos permite configurar variables de entorno, variables especiales que no escribimos en nuestro código pero si requerimos para el correcto funcionamiento de nuestro código (por ejemplo, una contraseña o token para nuestra API o integración con otros servicios).

Para visualizar las variables de entorno que tenemos configuradas en el servidor debemos ejecutar el siguiente comando:
``` 
    firebase functions:config:get
    
```

Si queremos configurar una nueva variable de entorno podemos utilizar el siguiente comando:
``` 
    firebase functions:config:set configuration.variableSecreta=""valor de la variable secreta""
    
```

Por último, para utilizar estas variables de entorno en nuestras Cloud Functions con JavaScript podemos utilizar el siguiente código:
``` 
    const functions = require(""firebase-functions"");
    const secretPassword = functions.config().configuration.password;
    
```

Muchas veces necesitamos probar desde nuestra computadora el código de nuestras funciones, para esto, debemos guardar el valor de nuestras variables de entorno en un archivo temporal y pedirle a Firebase que emule la ejecución de la aplicación:
``` 
    firebase functions:config:get | ac .runtimeconfig.json
    firebase functions:shell
    
```

### Links:

* [Extend Firebase Authentication with Cloud Functions  |  Firebase](https://firebase.google.com/docs/auth/extend-with-functions)

* [Firebase Authentication triggers  |  Firebase](https://firebase.google.com/docs/functions/auth-events)

### Comentarios:

* **Enrique Alexis Lopez Araujo** (10) [480454](https://platzi.com/comentario/480454/) 

	Si el siguiente codigo no les funciona en unix (macOS o linux):
	``` 
	    firebase functions:config:get | ac .runtimeconfig.json
	    
	```
	
	usen el siguiente codigo 🔥
	``` 
	    firebasefunctions:config:get > .runtimeconfig.json
	    
	```

	* **Kemt** [480454] (2)

		gracias tambien aplica para windows

* **Nadir Antonio Soza Solis** (5) [891038](https://platzi.com/comentario/891038/) 

	En mi caso fue necesario instalar 3 módulos adicionales.
	
	* nodemailer (npm install nodemailer)
	* request (npm install request)
	* twilio (npm install twilio)
	
	
	
	Es por estas cosas que no me gustan los cursos en los cuales te dan el codigo hecho y no te explican el funcionamiento y los requerimientos mínimos. Espero no tener problemas por estar usando Node v10

* **Mauro Volpe** (4) [554029](https://platzi.com/comentario/554029/) 

	Para emular las variables de entorno en sistemas UNIX
	
	firebase functions:config:get > .runtimeconfig.json

* **sonia-ardila** (2) [839838](https://platzi.com/comentario/839838/) 

	'Successfully invoked function.'  
	firebase > > se registra email
	
	> Error en la creación de usuario => Error: Could not load the default credentials. Browse to <https://cloud.google.com/docs/authentication/getting-started> for more information.

* **Andres Leon** (2) [693392](https://platzi.com/comentario/693392/) 

	creo que lo explicado en este video ya es pasado, como hago para ejecutar las funciones localmente

	* **Daniel Esteves** [693392] (2)

		¡Hola! Encontré en la [documentación](https://firebase.google.com/docs/functions/local-emulator?hl=es) donde hablar sobre cómo se puede realizar local test

* **Brian Bentancourt** (2) [481808](https://platzi.com/comentario/481808/) 

	Hola, al querer ejecutar el comando firebase functions:shell me sale el siguiente error, al parecer functions no soporta versiones nuevas de Node. Como lo soluciono?
	``` 
	    i  functions: Preparing to emulate functions.
	    Warning: You're using Node.js v10.9.0 but Google Cloud Functions only supports v6.11.5.
	    !  functions: Failed to load functions source code. Ensure that you have the latest SDK by running npm i --save firebase-functions inside the functions directory.
	    !  functions: Errorfrom emulator. Error parsing triggers: Cannot find module'nodemailer'
	    
	    Try running "npm install"in your functions directorybefore deploying.
	    No functions emulated.
	    
	```

	* **Brian Bentancourt** [481808] (4)

		ya lo solucione instalando el siguiente paquete
		``` 
		    npm install nodemailer
		    
		```

	* **jggomezt** [481808] (1)

		excelente

	* **xeoDev** [481808] (3)

		Siempre es bueno leer los errores. Aunque en ocasiones son cientos de lineas 😄
		``` 
		     Cannot find module'nodemailer'
		    
		```
		
		No encuentra el modulo. Por lo tanto podríamos suponer que esta mal escrito o no está instalado.
		
		En este caso lo instalamos:
		``` 
		    npm install nodemailer
		    
		```

* **luisrangelc** (1) [1068166](https://platzi.com/comentario/1068166/) 

	yo tuve que agregar:
	``` 
	    var admin = require("firebase-admin");
	    
	    var serviceAccount = require("path/to/serviceAccountKey.json");
	    
	    admin.initializeApp({
	      credential: admin.credential.cert(serviceAccount),
	      databaseURL: "https://blogeekplatziXXXX.firebaseio.com"
	    });
	    
	```

* **luisrangelc** (1) [1067939](https://platzi.com/comentario/1067939/) 

	Que buen curso!

* **kikeRC** (1) [1043180](https://platzi.com/comentario/1043180/) 

	si se necesita borrar las variables de entorno creadas, utilicen el comando:
	``` 
	    firebase functions:config:unset configuration
	    
	```

* **Nadir Antonio Soza Solis** (1) [891109](https://platzi.com/comentario/891109/) 

	Tengo un error y no se a que se debe, alguien tiene alguna solucion?
	``` 
	    Errorenla creaciónde usuario => Error: Invalid login: 535-5.7.8 Username and Password not accepted. Learn more at 
	    
	```

* **Juan David Castro (Platzi)** (1) [479255](https://platzi.com/comentario/479255/) 

	* [Administra la implementación de funciones y las opciones de tiempo de ejecución - Firebase Docs](https://firebase.google.com/docs/functions/manage-functions?hl=es-419)
	
	

* **Jesus de la Casa Palomino** (1) [85369](https://platzi.com/comentario/1072619/) 
Estoy teniendo un problema que creo que está relacionado con el admin.initializeApp() 'Successfully invoked function.' firebase &gt...

	* **Jesus de la Casa Palomino** [85369] (1)

		Me respondo solo:
		``` 
		    set GOOGLE_APPLICATION_CREDENTIALS=path\to\key.json
		    
		    firebase functions:shell
		    
		```
		
		Es más fácil crear una variable de entorno con la dirección de `serviceAccountKey.json` (clave generada en la consola de firebase).
		
		Esto hace que no tengamos que cambiar el initializeApp cuando le hagamos el deploy o le hagamos pruebas en local. El inconveniente es que parece que puede causar un problema de seguridad:
		``` 
		     functions: Your GOOGLE_APPLICATION_CREDENTIALS environment variable points ************ Non-emulated services will access production using these credentials. Be careful!
		    
		```
		
		Así que supongo que con eliminar la variable tras terminar de probar no debería haber problema.

* **Eden Gomez Gress** (1) [74415](https://platzi.com/comentario/852479/) 
Y por ultimo este error:

	* **Erik Ochoa** [74415] (2)

		No encuentra el modulo [nodemailer](https://www.npmjs.com/package/nodemailer), ¿lo tienes instalado? lo puedes instalar con `npm install nodemailer`.

* **Eden Gomez Gress** (1) [74414](https://platzi.com/comentario/852474/) 
Tambien me da este error:

	* **Erik Ochoa** [74414] (2)

		No se ve el error, nos lo puedes compartir de nuevo por favor.

* **Eden Gomez Gress** (1) [74407](https://platzi.com/comentario/852414/) 
Buen dia, alguien sabe porque me sale este error al ejectutar el comando “firebase functions:config:get”

	* **Erik Ochoa** [74407] (1)

		¿qué error? no lo muestras, tal vez te faltó adjunta la imagen… 😅

* **Andres Leon** (1) [65564](https://platzi.com/comentario/693586/) 
Error: Port 5000 is not open, could not start functions emulator. AYUDA!!!

* **Marcos Galaviz** (1) [61860](https://platzi.com/comentario/628863/) 
Excelente curso solo estoy atorado al ejecutar la funcion de creacionUsuario me regresa el error: Error en la creacion del usuario => ...

	* **Juan David Castro (Platzi)** [61860] (1)

		👋 Hey!
		
		En esta guía seguro encuentras la solución: [Firebase: The incoming JSON object does not contain a client_email field](https://stackoverflow.com/questions/56789424/the-incoming-json-object-does-not-contain-a-client-email-field). 😉

* **Brian Bentancourt** (1) [50629](https://platzi.com/comentario/481808/) 
Hola, al querer ejecutar el comando firebase functions:shell me sale el siguiente error, al parecer functions no soporta versiones nuevas...

	* **Brian Bentancourt** [50629] (4)

		ya lo solucione instalando el siguiente paquete
		``` 
		    npm install nodemailer
		    
		```

* **rtito** (0) [917011](https://platzi.com/comentario/917011/) 

	Alguien le funciono el comando firebase functions:shell sin problemas?

* **Henry Villavicencio** (0) [575512](https://platzi.com/comentario/575512/) 

	@jggomezt profe cambia la contraseña. Caundo se hace el deploy se la puede ver. XD

* **Victor H. Guarneros G** (0) [72142](https://platzi.com/comentario/811224/) 
Tengo el siguiente error pero si estoy seguro que el password es correcto: ⚠ Your requested “node” version “8” doesn’t match your global...

	* **Victor H. Guarneros G** [72142] (2)

		el problema está resuelto, solo tenia que permitir el acceso a aplicaciones poco seguras en mi cuenta de gmail

# Extendiendo Firestore con Cloud Functions. [3306]

## 0070. Creación de las cloud functions de Firestore [16636](https://platzi.com/clases/1472-firebase-cloud/16636-creacion-de-las-cloud-functions-de-firestore/)

### Descripción:


Cuando los usuarios ingresan a nuestra aplicación, solicitamos permiso para mandar notificaciones y registrar un _service worker_ , así, cuando los usuarios aceptan, Firebase genera un token y envía las notificaciones a los usuarios que aceptaron los permisos.

Si queremos ejecutar una función cuando Firebase genera estos tokens podemos utilizar el siguiente código:
``` 
    // Cuando el usuario acepta los permisos
    exports.registrarTopico = functions.firestore
            .document('tokens/{id}')
            .onCreate(/* el código que ejecutamos cuando se disparan los eventos */)
    
    // Cuando la aplicación envía una notificación
    exports.registrarTopico = functions.firestore
            .document('posts/{idPost}')
            .onUpdate(/* el código que ejecutamos cuando se disparan los eventos */)
    
```

### Links:

* [Cloud Firestore triggers  |  Firebase](https://firebase.google.com/docs/functions/firestore-events)

* [Curso de Firebase para Web](https://platzi.com/cursos/firebase-web/)

### Comentarios:

* **Juan David Castro (Platzi)** (4) [479260](https://platzi.com/comentario/479260/) 

	También podemos utilizar Firestore con las Cloud Functions para devolver la información de la base de datos en forma de API con las funciones HTTP, lo vamos a ver más adelante 👍.

* **joseadrian** (1) [530692](https://platzi.com/comentario/530692/) 

	oh, curiosa forma de detectar el cambio

* **Eden Gomez Gress** (1) [79464](https://platzi.com/comentario/940817/) 
Buen dia comunidad tengo una pregunta. Que pasaria si deseo apuntar a mas de una coleccion de firestore? como recibir notificacion tanto ...

## 0080. Probando y desplegando las cloud functions de Firestore [16637](https://platzi.com/clases/1472-firebase-cloud/16637-probando-y-desplegando-las-cloud-functions4321/)

### Descripción:


### Links:

* [Cloud Firestore triggers  |  Firebase](https://firebase.google.com/docs/functions/firestore-events)

* [Run functions locally  |  Firebase](https://firebase.google.com/docs/functions/local-emulator)

### Comentarios:

* **Ehitel Rodríguez Castro** (4) [846377](https://platzi.com/comentario/846377/) 

	El curso está muy bien, me parece excelente.
	
	Aunque honestamente prefería que los cursos tuviera más atomicidad. Desviarme del curso en el que estoy interesado para realizar otro que no está exactamente dentro de mi marco de interés me desvía un poco del camino.
	
	Pero no quita que es un excelente instructor con excelente contenido.

* **rafygonzalez089** (4) [766640](https://platzi.com/comentario/766640/) 

	Si ya has llegado aquí y te sientes qué no entiendes nada, es por que hay materiales de otros cursos.  
	Puedes mirar el de Firebase para la Web y entender como es que imprime las notificaciones

	* **Nadir Antonio Soza Solis** [766640] (1)

		Pero al igual que este no esta completo el desarrollo de las funciones. Y no creo que sea culpa del maestro, habría que revisar quienes editan y cargan los cursos. Me late como que se les quedaron algunos cursos pendientes de cargar.

	* **rtito** [766640] (1)

		que otro curso me recomiendas revisar? a parte del que mencionas? tengo problemas al ejecutar el comando <firebase deploy --only functions>

* **orivasm44** (3) [488228](https://platzi.com/comentario/488228/) 

	Hola en el package.json están todos los comandos necesarios para hacer el deploy en este caso seria **npm run deploy**

# Extendiendo el Almacenamiento con Cloud Functions. [3307]

## 0090. Creación de las cloud functions para el storage [16638](https://platzi.com/clases/1472-firebase-cloud/16638-creacion-de-las-cloud-functions-para-el-storage/)

### Descripción:


Firebase también nos permite ejecutar nuestras funciones cuando suceden eventos relacionados a los archivos estáticos de nuestra aplicación, vamos a seguir el mismo proceso de las clases anteriores utilizando el siguiente código para ejecutar la lógica de negocios cuando los usuarios suben o eliminan sus imágenes:
``` 
    exports.validarImagen = functions.storage
            .object()
            .onFinalize(/* el código que ejecutamos cuando los usuarios suben una nueva imagen */)
    
```

### Links:

* [https://firebase.google.com/docs/functions/gcp-storage-events](https://firebase.google.com/docs/functions/gcp-storage-events)

* [https://cloud.google.com/vision/](https://cloud.google.com/vision/)

* [Cloud Vision API Documentation  |  Cloud Vision API Documentation
       |  Google Cloud](https://cloud.google.com/vision/docs/)

* [@google-cloud/vision  -  npm](https://www.npmjs.com/package/@google-cloud/vision)

### Comentarios:

* **joseadrian** (2) [530714](https://platzi.com/comentario/530714/) 

	No existe una funcion que sea algo como path.GetNameOnly() ?

	* **Jean Carlos Nuñez Hernandez** [530714] (2)

		No lo creo, pero te dejo la documentacion <https://firebase.google.com/docs/functions>

## 0100. Terminando de crear cloud functions para el storage y probando su funcionamiento [16640](https://platzi.com/clases/1472-firebase-cloud/16640-terminando-de-crear-cloud-functions-para-el-storag/)

### Descripción:


### Comentarios:

* **Jean Carlos Nuñez Hernandez** (2) [579546](https://platzi.com/comentario/579546/) 

	safeSerachDetection -> Google aplica machine learning para que este en formato seguro

* **Edgar Mogollon** (1) [664424](https://platzi.com/comentario/664424/) 

	Interesante!

## 0110. Probando y desplegando las cloud functions de almacenamiento con Firestore [16639](https://platzi.com/clases/1472-firebase-cloud/16639-probando-y-desplegando-las-cloud-functions-de-stor/)

### Descripción:


Si queremos utilizar librerías o herramientas externas a nuestra aplicación (como `@google-cloud/vision` para detectar contenido inapropiado en nuestras imágenes) debemos actualizar nuestro plan de precios de Firebase y, en el caso de nuestra aplicación, también debemos habilitar la API que queremos utilizar desde la [Consola de Google Cloud Platform](https://cloud.google.com).

### Links:

* [Run functions locally  |  Firebase](https://firebase.google.com/docs/functions/local-emulator)

* [Cloud Storage triggers  |  Firebase](https://firebase.google.com/docs/functions/gcp-storage-events)

### Comentarios:

* **mdhave** (7) [567728](https://platzi.com/comentario/567728/) 

	Buenas! Se ve que en el curso de Firebase WEB (que se arma el Front que estas usando), quedaron desactualizados algunos métodos.
	
	En el que estas usando, tiene cosas como en el crearPost ( agregas los fields Token y Publicado)  
	También se nota que cuando haces el uploadImage usas como nombre de la imagen el doc de la collection
	
	todo eso en el curso WEB no aparece, ya que usas el [file.name](http://file.name) del obj de la imagen
	
	Donde se puede ver los files del Front actualizados??
	
	Slds

	* **Juan David Castro (Platzi)** [567728] (1)

		👋 ¡Hola!
		
		Este es el repositorio: <https://github.com/jggomez/blogeek-platzi>.

	* **Jesus de la Casa Palomino** [567728] (1)

		Creo que en el repositorio tampoco lo tiene actualizado.

* **Juan David Castro (Platzi)** (2) [479262](https://platzi.com/comentario/479262/) 

	😅 Es necesario actualizar (pagar) nuestro plan de Firebase para utilizar paquetes de NPM o consultar APIs externas, es decir, para utilizar y ejecutar código que no --necesariamente-- estamos escribiendo en nuestras funciones de Firebase 😱.
	
	* [Firebase Pricing](https://firebase.google.com/pricing)
	
	

* **Disando7** (1) [647300](https://platzi.com/comentario/647300/) 

	Me pareció súper económico el plan de pago por uso, va incluido el plan free, o sea, si se pasa del límite del plan free, ahí si te empiezan a cobrar por el uso.
	
	<h4>Genial</h4>

# Creando Cloud Functions HTTPS [3308]

## 0120. Creación de la cloud function HTTPS [16642](https://platzi.com/clases/1472-firebase-cloud/16642-creacion-de-la-cloud-function-https/)

### Descripción:


Firebase también nos permite ejecutar nuestras funciones cuando suceden eventos HTTP, es decir, podemos utilizar las Cloud Functions para trabajar nuestra aplicación en forma de API.

Para esto vamos a instalar la herramienta `cors` (para llamar nuestro código desde diferentes servidores) y `express` (para detectar las rutas por las cuales llamamos a nuestras funciones en forma de API). Recuerda que puedes aprender mucho más sobre estas herramientas en el [Cuso de Express.js](https://platzi.com/express) de Platzi.
``` 
    npm install --save express cors
    
```

Tambien vamos a utilizar la función `onRequest` de la librería `firebase-functions` para indicarle a Firebase la configuración y las rutas que configuramos con _express_ :
``` 
    exports.enviarPostSemana = functions.https
            .onRequest(/* Nuestra aplicación de Express.js */)
    
```

### Links:

* [Call functions via HTTP requests  |  Firebase](https://firebase.google.com/docs/functions/http-events)

### Comentarios:

* **Jean Carlos Nuñez Hernandez** (2) [582307](https://platzi.com/comentario/582307/) 

	Https = se define functions.htts

* **Jesus Castañon** (1) [1034088](https://platzi.com/comentario/1034088/) 

	Capture

## 0130. Bonus Construyendo un controlador para la función HTTP [16641](https://platzi.com/clases/1472-firebase-cloud/16641-bonus-construyendo-un-controlador-para-la-funcio-8/)

### Descripción:


### Comentarios:

* **Andrés Felipe Chaparro Grimaldo** (2) [565091](https://platzi.com/comentario/565091/) 

	Este video debería ir antes de “Probando y desplegando las cloud function HTTPS”. Saludos

	* **Juan David Castro (Platzi)** [565091] (1)

		¡Hola! El orden ahora sí es correcto. ¿Tienes algún otro problema?

## 0140. Probando y desplegando las cloud function HTTPS [16644](https://platzi.com/clases/1472-firebase-cloud/16644-probando-y-desplegando-las-cloud-function-https/)

### Descripción:


### Links:

* [Run functions locally  |  Firebase](https://firebase.google.com/docs/functions/local-emulator)

* [Call functions via HTTP requests  |  Firebase](https://firebase.google.com/docs/functions/http-events)

### Comentarios:

* **Juan David Castro (Platzi)** (4) [479264](https://platzi.com/comentario/479264/) 

	A diferencia de los otros tipos de Cloud Functions, necesitamos un servidor donde podamos llamar y ejecutar nuestras funciones HTTP. En vez de utilizar el comando `firebase deploy --only functions` vamos a utilizar el comando `firebase serve --only functions` y automáticamente vamos a desplegar nuestras funciones HTTP y podremos probarlas utilizando herramientas como [Postman](https://www.getpostman.com/) 😃.

* **arnoldkba** (1) [65259](https://platzi.com/comentario/688599/) 
tengo la siguiente falla al hacer pruebas de funcion http: Error: Could not load the default credentials. Browse to 

* **Marcos Galaviz** (1) [61925](https://platzi.com/comentario/630130/) 
Que tal ¿Podrian poner un ejemplo de como crear una cloud function para generar un PDF y meterlo a la BD? he leido al respecto pero la ve...

	* **Juan David Castro (Platzi)** [61925] (1)

		👉 [Create PDF in Firebase Cloud Functions](https://stackoverflow.com/questions/45335543/create-pdf-in-firebase-cloud-functions)  
		👉 [Firebase Cloud Functions - create pdf, store to bucket and send via mail](https://stackoverflow.com/questions/48310441/firebase-cloud-functions-create-pdf-store-to-bucket-and-send-via-mail?noredirect=1&lq=1)  
		👉 [Building a Cloud Function that generates PDFs from provided URL (GO)](https://www.ribice.ba/cloud-function-html-to-pdf/)

# Extendiendo el Hosting con Cloud Functions. [3309]

## 0150. Usando las firebase cloud functions desde el hosting [16643](https://platzi.com/clases/1472-firebase-cloud/16643-usando-las-firebase-cloud-functions-desde-el-hosti/)

### Descripción:


Firebase hosting permite usar las cloud functions para procesamiento al lado del servidor. Esto permite que puedas generar contenido dinámico para tu sitio alojado en el hosting de firebase. Además puedes hacer:

* **Pre-render de tus SPA (Single Page Application) para mejorar el SEO:** esto permite crear dinámicos tag de ‘meta’ que mejoran el SEO en redes sociales o buscadores.
* **Brindar contenido dinámico:** No solo puedes brindar contenido estático, también es posible a partir una URL llamar una función que consulte algunos datos o los procese y con ello brindar un contenido dinámico a las páginas



¿Cómo lo haces? Primero creas una función, ejemplo:
``` 
    exports.renderPost = functions.https.onRequest((req, resp) => {
     console.log(req.query.idPost)
     return admin
       .firestore()
       .collection('posts')
       .doc(req.query.idPost)
       .get()
       .then(post => {
         return resp.status(200).send(`<!doctype html>
           <head>
             <title>Post</title>
           </head>
           <body>
               <article>
                 <div>
                     <h2>${post.data().titulo}</h2>
                 </div>
                 <div>
                     <iframe type="text/html" width="500" height="385" src='${
                         post.data().videoLink}'
                         frameborder="0"></iframe>
                 </div>
                 <div>
                     Video
                 </div>
                 <div>
                     <p>${post.data().descripcion}</p>
                 </div>
               </article>
           </body>
         </html>`)
       })
    })
    
```

Ahora agregamos una configuración de rewrite en el archivo firebase.json:
``` 
    {
       "hosting": {
         "public": "public",
          
         "rewrites": [ {
           "source": "/post", 
      "function": "renderPost"
         } ]
       }
    }
    
```

Desplegamos la función y la aplicación web a firebase y probamos con las URL

<https://your-firebase-project-id.firebaseapp.com/post?idPost=ID_POST>

Veremos que nos muestra una página con el contenido HTML definido en la función.

Además para mejorar el rendimiento al momento de renderizar la página podemos usar el caché de HTTP tanto el de los CDNs (Content Delivery Network) como el del browser. Esto lo puedes hacer de la siguiente forma:

`resp.set('Cache-Control', 'public, max-age=300, s-maxage=600');`

En esta línea estamos modificando el cache, asignado un tiempo de caché al browser de 5 minutos por medio del max-age y un tiempo de caché al CDN de 10 minutos por medio del s-maxage.

**Enlace sugerido:**

<https://firebase.google.com/docs/hosting/functions>

### Comentarios:

* **joseadrian** (2) [531411](https://platzi.com/comentario/531411/) 

	Suena interesante habria que tomarse un tiempo para realizarlo con detalle

* **Brian Bentancourt** (2) [482043](https://platzi.com/comentario/482043/) 

	Me gustaría ver un ejemplo con react 😄

	* **Jean Carlos Nuñez Hernandez** [482043] (1)

		seria bueno tanto para react como angular

# Extendiendo crashlytics con Cloud Functions. [3310]

## 0160. Creación de las cloud functions de Crashlytics [16646](https://platzi.com/clases/1472-firebase-cloud/16646-creacion-de-las-cloud-functions-que-se-dispare-cua/)

### Descripción:


Para ejecutar una función cuando registramos un error con el servicio de Crashlytics podemos utilizar el siguiente código:
``` 
    exports.nuevoError = functions.creashlytics
    	.issue()
    	.onNew()
    	.onRegressed()
    	.onVelocityAllert
    
```

### Links:

* [Extend Firebase Crashlytics with Cloud Functions  |  Firebase](https://firebase.google.com/docs/crashlytics/extend-with-cloud-functions)

### Comentarios:

* **joseadrian** (2) [531414](https://platzi.com/comentario/531414/) 

	Nos permite enviar un aviso por medio de SMS? !8o

	* **Jean Carlos Nuñez Hernandez** [531414] (1)

		No lo creo

	* **AndrsDev** [531414] (2)

		Puedes integrarlo si lo deseas por medio de servicios como twilio. <https://www.twilio.com/>

* **Juan David Castro (Platzi)** (2) [479265](https://platzi.com/comentario/479265/) 

	[Crashlytics](https://firebase.google.com/docs/crashlytics/?hl=es-419) es un servicio de Firebase que nos permite registrar los errores de nuestras aplicaciones móviles (Android y IOS).
	
	> _Obtén estadísticas prácticas y claras sobre los problemas de tus apps con esta poderosa solución de informe de fallos para iOS y Android._

	* **Juan David Castro (Platzi)** [479265] (1)

		🐛😏

* **joseadrian** (2) [54552](https://platzi.com/comentario/531414/) 
Nos permite enviar un aviso por medio de SMS? !8o

	* **Jean Carlos Nuñez Hernandez** [54552] (1)

		No lo creo

## 0170. Probando y desplegando la cloud function de Crashlytics [16645](https://platzi.com/clases/1472-firebase-cloud/16645-probando-y-desplegando-la-cloud-function/)

### Descripción:


### Links:

* [Run functions locally  |  Firebase](https://firebase.google.com/docs/functions/local-emulator)

* [Extend Firebase Crashlytics with Cloud Functions  |  Firebase](https://firebase.google.com/docs/crashlytics/extend-with-cloud-functions)

### Comentarios:

* **joseadrian** (4) [531418](https://platzi.com/comentario/531418/) 

	Como se establecen los atributos de configuración en la consola de firebase? o solo con hacerlo en la consola de studio se suben al servidor?

	* **jggomezt** [531418] (3)

		Hola, estos parametros solo son por CLI

* **Jean Carlos Nuñez Hernandez** (2) [582335](https://platzi.com/comentario/582335/) 

	firebase shell estoy muy cool este forma de probar

* **joseadrian** (2) [54554](https://platzi.com/comentario/531418/) 
Como se establecen los atributos de configuración en la consola de firebase? o solo con hacerlo en la consola de studio se suben al servi...

	* **jggomezt** [54554] (3)

		Hola, estos parametros solo son por CLI

# Extendiendo Analytics con Cloud Functions. [3311]

## 0180. Creación de las cloud functions cuando se registra un evento en las analíticas de Firebase [16648](https://platzi.com/clases/1472-firebase-cloud/16648-creacion-de-las-cloud-functions-cuando-se-registra/)

### Descripción:


El servicio de Google Analytics para Firebase nos permite analizar métricas a partir de las acciones de nuestros usuarios en las aplicaciones móviles.

Por supuesto, Firebase nos permite ejecutar funciones especiales cuando suceden este tipo de eventos, por ejemplo, cuando realizamos una compra o compartimos contenido de la aplicación:
``` 
    exports.shareAnalytics = functions.analytics
    	.event(/* Nombre del evento que queremos analizar. Ex. 'share' */)
    	.onLog(/* el código que ejecutamos cuando sucede este evento */)
    
```

### Links:

* [Extend Google Analytics for Firebase with Cloud Functions  |  Firebase](https://firebase.google.com/docs/analytics/extend-with-functions)

### Comentarios:

* **joseadrian** (4) [531421](https://platzi.com/comentario/531421/) 

	Es genial poder enlazar y automatizar las acciones a traves de eventos, firebase es una herramienta que todos debemos aprender y utilizar

## 0190. Probando y desplegando la cloud function de analíticas [16647](https://platzi.com/clases/1472-firebase-cloud/16647-probando-y-desplegando-la-cloud-function5157/)

### Descripción:


### Links:

* [Run functions locally  |  Firebase](https://firebase.google.com/docs/functions/local-emulator)

* [Extend Google Analytics for Firebase with Cloud Functions  |  Firebase](https://firebase.google.com/docs/analytics/extend-with-functions)

### Comentarios:

* **Juan David Castro (Platzi)** (3) [479267](https://platzi.com/comentario/479267/) 

	📴 Las funciones de Firebase pueden tardar hasta 24 horas en ejecutarse cuando probamos las analíticas de nuestras aplicaciones móviles 🙈.

	* **Jean Carlos Nuñez Hernandez** [479267] (1)

		Waaao

# Creación de pruebas unitarias a las Cloud Functions. [3312]

## 0200. Creando pruebas unitarias en Firebase Cloud Functions [16649](https://platzi.com/clases/1472-firebase-cloud/16649-creando-pruebas-unitarias-en-firebase-cloud-functi/)

### Descripción:


Aprende a crear Pruebas Unitarias o Unit Testing para tus Funciones de Firebase utilizando Mocha.

Firebase Cloud Functions es un servicio de Google Cloud que nos permite ejecutar el código de nuestra lógica de negocios como respuesta a diferentes eventos en nuestras aplicaciones. Vamos a utilizar la herramienta mochajs para realizar pruebas unitarias y comprobar que nuestro código funciona correctamente como verdaderos profesionales.

### Links:

* [https://firebase.google.com/docs/functions/local-emulator](https://firebase.google.com/docs/functions/local-emulator)

* [Unit testing of Cloud Functions  |  Firebase](https://firebase.google.com/docs/functions/unit-testing)

### Comentarios:

* **Brian Bentancourt** (4) [482929](https://platzi.com/comentario/482929/) 

	```
	    npm i -D firebase-functions-test mocha
	    
	```

* **Jean Carlos Nuñez Hernandez** (2) [582558](https://platzi.com/comentario/582558/) 

	Para instalar la librerias de test -> npm install --save-dev firebase-functions-test

* **Brian Bentancourt** (2) [482969](https://platzi.com/comentario/482969/) 

	tengo el siguiente error al ejecutar npm test
	``` 
	    > functions@ test C:\app\VideoBlog-Firebase\functions
	    > mocha --reporter spec
	    
	    Warning: Could not find any test files matching pattern: test
	    Notest files found
	    npm ERR! Test failed.  See above formore details.
	    
	```

	* **jggomezt** [482969] (2)

		Recuerda llama el archivo de pruebas index.test.js, así lo tienes?

	* **Brian Bentancourt** [482969] (1)

		si, tiene el mismo nombre

	* **jggomezt** [482969] (2)

		el directorio lo llamaste test ??

	* **Brian Bentancourt** [482969] (3)

		si, también  
		dejo [link ](https://github.com/brianbentancourt/VideoBlog-Firebase/tree/master/functions/componentes)a repositorio GitHub

	* **Juan David Castro (Platzi)** [482969] (2)

		¡Hola!
		
		Vi tu repositorio, creo que lo tienes igual que el profesor.
		
		Pero tal vez lo único diferente a la documentación es que la carpeta de **`test`** no está en **`functions/componentes`** sino solo en **`functions`**.
		
		Mira la documentación: <https://firebase.google.com/docs/functions/unit-testing?hl=es-419>.

	* **Juan David Castro (Platzi)** [482969] (2)

		¡Bingo! Tu error es que la carpeta **`test`** está dentro de la carpeta **`componentes`**. Sácala y seguro que ya todo funciona. 😉

* **Juan David Castro (Platzi)** (2) [479268](https://platzi.com/comentario/479268/) 

	🆗 En las clases anteriores utilizamos `firebase functions:shell` para comprobar mediante nuestra lógica si nuestro código entrega los resultados esperados cuando pasamos los datos de prueba correctos.
	
	🎉 😮 Sin embargo, gracias a las pruebas unitarias vamos a verificar estas mismas funciones pero de forma automatizada. En vez de ejecutar este comando una y otra vez antes de desplegar nuestras funciones, vamos a escribir una sola vez el resultado que esperamos frente a ciertos datos de prueba, así podemos trabajar mucho más ágilmente y evitar errores humanos al probar nuestras Cloud Functions 👌.

* **Brian Bentancourt** (1) [50747](https://platzi.com/comentario/482969/) 
tengo el siguiente error al ejecutar npm test > functions@ test C:\app\VideoBlog-Firebase\functions > mocha --reporter spec ...

	* **jggomezt** [50747] (2)

		Recuerda llama el archivo de pruebas index.test.js, así lo tienes?

# Optimizando las Cloud Functions. [3313]

## 0210. Buenas practicas para las cloud functions [16650](https://platzi.com/clases/1472-firebase-cloud/16650-buenas-practicas-para-las-cloud-functions/)

### Descripción:


Ahora hablaremos de buenas prácticas, soportes de lenguaje y optimización de las cloud functions:

## Lenguajes Soportados

Las cloud functions pueden ser escritas en dos lenguajes de programación por ahora, en Javascript y Typescript. Si deseas usar Typescript puedes seleccionar el lenguaje cuando creas el proyecto y tendrás una estructura adecuada y transpilación transparente. Ahora si tienes un proyecto typescript y deseas desplegarlo como funciones tendrás que usar los “predeploy hook” [1]. Typescript es una buena opción ya que ofrece ventajas como el manejo más simple de código asíncrono con async/await lo cual simplifica el manejo de promesas y ya que es tipado evita muchos errores en ejecución [2].

## Buenas prácticas y optimizaciones

* Es importante administrar el ciclo de vida de las funciones para asegurarse que terminan correctamente para evitar que queden en ciclos infinitos o que duren mucho más de lo normal o que terminen antes que finalice correctamente, en algunas ocasiones podría causar cargos de pago extra.
* Siempre retorna una promesa en una función asíncrona esto permite cerrar el ciclo de vida en el momento adecuado.
* Siempre colocar return en una función síncrona esto permite cerrar el ciclo de vida en el momento adecuado.
* Termina las funciones HTTP con res.redirect, o res.send() o resp.end() o resp.json().
* Utiliza las promesas de Javascript el cual agrega mantenibilidad al código cuando se desarrolla funciones asíncronas.
* Desarrolla pruebas unitarias de tus funciones.
* Si la ejecución de una función asíncrona es muy importante, marca en la consola de Google Cloud Platform “Reintentar tras Fallo” esto volverá a intentar la ejecución de la función, hasta un máximo de siete(7) días. Recomendación aplica las buenas prácticas para ello. Puedes encontrar más info aquí [3].
* Maneja siempre variables de entorno y no hagas “hardcoded” de valores, es buena práctica por seguridad y para que no tengas que desplegar de nuevo el código si requieres cambiar un valor. [4].
* No hagas actividades en background, ya que una vez termina la ejecución de la función puede que no se termine lo que se dejó en background por eso siempre maneja promesas.
* Si necesitas crear un archivo en una función debes hacerlo en el directorio de temporales y deben ser de tamaño pequeño ya que consumen memoria de la función, por eso elimínalos después de una invocación ya que podrían persistir en otras invocaciones o pásalo al storage.
* En desarrollo trata de usar el emulador de cloud functions (shell o serve) ya que el despliegue puede demorar y se vuelve tedioso probar.
* Importa las dependencias que verdaderamente usas en tu función, las que no usas elimínalas de tu archivo, ya que cuando se invoca por primera vez una función se carga los módulos importados y esto puede tomar un respectivo tiempo dependiendo del tamaño.
* No hay garantía que el estado de una función persista para próximas invocaciones, sin embargo en algunas ocasiones se recicla entornos de ejecución de una previa invocación, así que si tu declaras variables globales, el valor puede ser reutilizado en otra invocación. De esta forma puedes guardar en caché objetos que son pesados de crear. Te recomiendo solo crees variables de forma global sin van a ser utilizadas por varias funciones, porque si no puede afectar el rendimiento cuando se tenga que crear el entorno por primera vez.
* Si requieres hacer solicitudes HTTP desde una función puedes reutilizar la conexión generada por la función, así reduces el tiempo de CPU necesario para crear la nueva conexión. Recuerda que en Firebase se cobra por tiempo de uso de CPU. [5].
* Si usas librerías clientes de google como Pub/Sub o alguna de Machine Learning, crea la constante que tiene el objeto cliente de manera global así no tiene que crear una conexión y consultas al DNS en cada invocación.
* Si tienes muchas funciones, como buena práctica y por rendimiento despliega solo la función que modificaste o creaste, con el comando de firebase deploy --only functions:NOMBREFUNCION



Estas son algunas buenas prácticas para optimizar el rendimiento, despliegue y minimizar cobros por uso de recursos. Recuerda crear capas, módulos para tener un código más mantenible, como también automatizar tareas por medio de scripts de npm y realizar pruebas unitarias y de rendimiento a las funciones y evaluar su funcionamiento y cuotas de cobro.

**Enlaces que van a servirte:**

* <https://firebase.google.com/docs/functions/manage-functions>
* <https://firebase.google.com/docs/functions/typescript>
* <https://firebase.google.com/docs/functions/terminate-functions>
* <https://firebase.google.com/docs/functions/retries>
* <https://firebase.google.com/docs/functions/networking>
* <https://firebase.google.com/docs/functions/tips>



**Referencias:**

[1]. <https://firebase.google.com/docs/cli/#predeploy_and_postdeploy_hooks>  
[2]. <http://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html>  
[3]. <https://firebase.google.com/docs/functions/retries>  
[4]. <https://firebase.google.com/docs/functions/config-env>  
[5]. <https://firebase.google.com/docs/functions/networking>

### Comentarios:

* **joseadrian** (2) [531443](https://platzi.com/comentario/531443/) 

	Excelente aporte!

# Cierre [3314]

## 0220. Conclusiones finales y cierre [16651](https://platzi.com/clases/1472-firebase-cloud/16651-conclusiones-finales-y-cierre/)

### Descripción:


### Comentarios:

* **xeoDev** (5) [491210](https://platzi.com/comentario/491210/) 

	Me sirvio como base. Ahora profundizaré más para realizar mis proyectos con firebase.

* **Disando7** (2) [647474](https://platzi.com/comentario/647474/) 

	Listo, ahora volver a ver el curso para repasar, ya que es una herramienta muy importante y vale estudiar con dedicación.

* **Jean Carlos Nuñez Hernandez** (1) [582314](https://platzi.com/comentario/582314/) 

	Tremenda herramientas cloud functions

