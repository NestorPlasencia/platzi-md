# Bienvenida e Introducción

## 0010. Introducción

### Descripción:


Bienvenido al Curso de Firebase para Web, vamos a construir un blog usado diferentes servicios de Firebase: creación y autenticación de usuarios por email y redes sociales, correos electrónicos para validar y recuperar contraseñas, reglas de seguridad, almacenamiento de publicaciones e imágenes en Firebase Storage, despliegue de nuestras aplicaciones con Firebase Hosting y notificaciones en tiempo real para anunciar cambios de nuestro blog.

Esta vez nuestro profesor es Juan Guillermo Gómez, Google Developer Expert en la plataforma de Firebase.

### Comentarios:

* **Daniee** (9)

	
	Me alegro que hayan actualizado este curso ! 😊

	* **Alex Eugenio Gavidia Donayre** (2)

		
		Excelente!

* **JosanGuerra** (6)

	
	  1. INTRODUCCION
	
	
	
	En este curso haremos un blog y usaremos los servicios de firebase para la web, haremos lo siguiente durante el curso:
	
	1.1 Creacion y autenticacion de usuarios por medio de email y password, y tb por redes sociales como facebook o google.  
	1.2 Modificaremos plantillas para los envios de correos electronicos de recordar contrasena olvidada y validacion o verificacion de email  
	1.3 Guardaremos los posts en la base de datos de firestore  
	1.4 Hablaremos sobre colecciones, documentos, reglas de seguridad e indices para mejorar el rendimiento de la aplicacion.  
	1.5 Luego almacenaremos imagenes en el storage y aplicaremos reglas de seguridad.  
	1.6 Desplegamos nuestra app al hosting de firebase  
	1.7 Personalizaremos el comportamiento del hosting  
	1.8 Por ultimo vamos a enviar notificaciones a nuestros usuarios ya sea estando el usuario en la app o fuera de ella para que se enteren de los cambios del blog.

* **Brayan Mamani** (3)

	
	Un curso impartido por un **_Google Developer Expert_** .

* **Iván Mauricio Toro Cifuentes** (3)

	
	¡[jggomezt](https://github.com/jggomez), un crack!

* **Victor César** (2)

	
	Está aplicación esta toda hecha en IONIC 4 con [Firebase](https://mycustom.life/). Firebase es increíble.

* **Pamela Cinthya Torres Gutiérrez** (2)

	
	wooowww muy interesante, de manera rapida para un proyecto es que vere este curso completo y solo tratare de aplicar lo que me solicitan.
	
	Pero en cuanto pueda lo vere nuevamente y lo aplicare a mis proyectos personales.

* **Kerohuixco** (2)

	
	Se escucha que este curso esta genial… Manos a la obra.

	* **Brayan Mamani** (1)

		
		Es un excelente curso.

	* **Alex Eugenio Gavidia Donayre** (1)

		
		Excelente curso

* **santossoffli** (2)

	
	espero sea tan bueno como la version anterior del curso!!

	* **jesusmurf** (1)

		
		Yo espero que sea mejor, la versión anterior no me gustó 😦

* **Freddy Lemus Barrera** (2)

	
	Pinta interesante este curso

* **carlosbazanhuaman** (1)

	
	se ve interesante el curso, espero poder ver todo lo que comenta sobre los servicios de firebase

* **Bryan Estiven Silva Mercado** (1)

	
	El proyecto suena interesante

* **Andersson Ramirez** (1)

	
	Me da curiosidad firebase, a ver q tal

* **David Galicia** (1)

	
	Buen inicio! Veamos como sacar provecho de Firebase

* **Kevin Jeremy Salazar Jimenez** (1)

	
	exelente inicio 😃

* **Juan Pablo Cano Buitrago** (1)

	
	Denso

* **David Román** (1)

	
	sdfsdf

* **Alex Eugenio Gavidia Donayre** (1)

	
	Veamos!

* **nelsonfernandezgomez** (1)

	
	Alguien me puede hacer el favor de indicarme en donde puedo encontrar el código del proyecto del curso.

* **Lordpanther** (1)

	
	Excelente introduccion, Espero que el instructor gane más confianza con la cámara. 😃

* **Jesus Ricardo Moreira Cedeño** (1)

	
	:3

## 0020. ¿Qué es Firebase

### Descripción:


Firebase es un Backend como Servicio, es decir, esta herramienta nos permite conectarnos desde cualquier aplicación a las tareas de backend y despliegue de nuestras aplicaciones de forma mucho más simple, mantenible y escalable.

Tareas como crear y autenticar usuarios, guardar nuestra información en bases de datos, almacenar archivos estáticos, administrar la infraestructura, analizar métricas, entre muchas otras. Gracias a Firebase automatizamos y agilizamos todos estos servicios en una misma plataforma integrada sobre la infraestructura de Google Cloud.

Servicios de Firebase para la Web:

  * **Cloud Firestore** : Almacenamiento y sincronización de los datos de nuestra aplicación a escala global, funciona como una base de datos NoSQL.
  * **Autenticación** : Autenticación de usuarios de manera simple, rápida y segura con email y contraseña, redes sociales o mensajes de texto.
  * **Cloud Storage** : Almacenar y atender nuestros archivos _(imágenes, vídeos, etc)_ a la escala de Google.
  * **Cloud Messaging** : Envío de mensajes y notificaciones segmentadas.
  * **Hosting** : El sistema de Google Cloud para almacenar la información de nuestra página web.
  * **Cloud Functions** : Administración del código de backend necesario para desplegar nuestras aplicaciones a los servidores de Google Cloud.
  * **Integraciones** : Podemos conectar las funciones de Firebase a otros servicios de Google _(Google Ads, Google Marketing Platform, entre otras)_ o incluso a servicios de terceros como Slack, Data Studio y BigQuery.



### Links:

* [Firebase](https://firebase.google.com/)

* [Firebase](https://firebase.google.com/pricing/)

### Comentarios:

* **Juan David Castro (Platzi)** (28)

	
	Notas de la clase:
	
	  * Todas _(bueno, casi todas :sweat_smiles)_ las aplicaciones necesitan programar código backend para sus diferentes funcionalidades: guardar info en bases de datos, almacenar archivos, autenticar usuarios, etc 😮.
	  * Firebase en un _BAAS (Backend as a Service)_ , es decir, Google se encargara él solito de crear y administrar las funciones, bases de datos e infraestructura de nuestra aplicación, nuestro tarea será trabajar algunas configuraciones en su plataforma _([firebase.google.com](http://firebase.google.com))_ y construir nuestra aplicación 😱🎉.
	  * Toda esta infraestructura funciona con Google Cloud, así que, tenemos muchas posibilidades para escalar nuestras aplicaciones 👌.
	
	
	
	Servicios de Firebase:
	
	  * Firestore es una base de datos NoSQL que nos permite almacenar y sincronizar en tiempo real los datos e nuestra aplicación ✌️📝.
	  * La autenticación (en mi opinión, lo herramienta más útil de Firebase 😍🎉) nos permite crear, autenticar y administrar los usuarios de nuestras aplicaciones con email y password, login y signup con redes sociales, correos electrónicos de recuperación de contraseña, entre muchas otras cosas geniales 🚫🏁 ✖️ ✔️ .
	  * Cloud Storage para almacenar archivos estáticos 😮.
	  * Cloud Messaging para enviar notificaciones 📩.
	  * Firebase Hosting para desplegar nuestras aplicaciones _(hasta dónde tengo entendido son despliegues común y corrientes)_ y Cloud Functions para despliegues sin programar el código backend de la aplicación 🙃🆙.
	
	

	* **Iván Mauricio Toro Cifuentes** (3)

		
		Gracias por el resumen.

	* **Jesus Ricardo Moreira Cedeño** (2)

		
		Se ve bastante útil, muchas gracias por tu aporte.

	* **Wilson Marino Pablo Mendez** (1)

		
		Buen resumen!!!

	* **Sebastian Cardoso Castillo** (1)

		
		Buen resumen. Me gustaba mas cuando Platzi mostraba arriba los comentarios mas puntuados.

* **Marcos Tomassi** (14)

	
	 **Consejo de curso: Poner en x1.25 el video para mayor comprensión.**

	* **Alex Eugenio Gavidia Donayre** (1)

		
		x2

* **Jaime Rueda Caldera** (6)

	
	Hola amigos yo he aprendido demasiado de firebase aqui <https://www.robinwieruch.de/> es contenido muy genial.

	* **Jaime Rueda Caldera** (1)

		
		En su mayoria es firebase con react

	* **Juan David Castro (Platzi)** (1)

		
		¡Robin es genial!

	* **Yubeli Martinez Sanchez** (1)

		
		Buen dato

	* **Alex Eugenio Gavidia Donayre** (1)

		
		Buen dato

* **Brayan Mamani** (5)

	
	Con Firebase puedes tener una plataforma bastante completa de forma sencilla a un costo accesible. Además es usada mucho por Startups.

* **Juan David Castro (Platzi)** (5)

	
	¿Los servicios de despliegue de Firebase son serverless? Es decir, ¿son como las funciones lambda de AWS? 🤔

	* **Freddy Lemus Barrera** (2)

		
		Buena pregunta, creo con las funciones lambda de AWS podemos escoger el lenguaje de programación para hacer lógica de negocio muy específica. No sé si Firebase también lo permite.

	* **jggomezt** (3)

		
		Hola, firebase ofrece Cloud Functions que es similar a Lambda. Y si, el hosting es serverless, te despreocupas de los servidores, de su escalamiento y disponibilidad

	* **Lewis Yuburi** (3)

		
		Si, Firebase Cloud Functions es muy similar a AWS Lambda, pero sólo tiene soporte para NodeJS 6.x y 8.x. Ahora, si despliegas a Firebase Hosting, deben ser archivos estáticos (HTML, CSS, JS, Imágenes, etc).

* **Alex Eugenio Gavidia Donayre** (4)

	
	Este curso si promete.

* **carlosbazanhuaman** (2)

	
	backend como servicio!

* **valentinafernandez** (2)

	
	Infraestructura como servicio sería mejor definición que backend.

* **Alex Eugenio Gavidia Donayre** (2)

	
	Firebase es una plataforma para el desarrollo de aplicaciones web y aplicaciones móviles desarrollada por James Tamplin y Andrew Lee en 2012 y adquirida por Google en 2014

* **milton** (2)

	
	Se puede hacer funcionar wordpress en firebase?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		No, firebase es una base de datos NoSQL y la estructura de Wordpress usa bases de datos relacionales principalmente MySQL

	* **Daniel Esteves** (1)

		
		Lo que puedes hacer es integrar Firebase para manejar el inicio de sesión de tus usuarios y tener una base de datos externa a la que tiene WordPress para ese tipo de datos. Lo puedes lograr con este [plugin](https://es.wordpress.org/plugins/integrate-firebase/)

* **joseadrian** (2)

	
	Me alegra saber que este material es reciente, excelente calidad de explicación.
	
	Claro, preciso y conciso.

* **Juan David Castro (Platzi)** (2)
¿Los servicios de despliegue de Firebase son serverless? Es decir, ¿son como las funciones lambda de AWS? 🤔

	* **Freddy Lemus Barrera** (2)

		
		Buena pregunta, creo con las funciones lambda de AWS podemos escoger el lenguaje de programación para hacer lógica de negocio muy específica. No sé si Firebase también lo permite.

* **David Behar** (1)

	
	Recomiendo el libro [the road to react with firebase](https://github.com/rwieruch/the-road-to-react-with-firebase)
	
	[![](https://www.roadtofirebase.com/static/dabc9e9702d52977740ad3a2e70390c2/bc59e/cover.png)](https://github.com/rwieruch/the-road-to-react-with-firebase)

* **Johan Manuel Perez Soto** (1)

	
	Firebase es lo mas sencillo que he visto en todo el tiempo que llevo desarrollando

* **Andersson Ramirez** (1)

	
	Interesante herramienta para iniciar el negocio

* **monicamesa360** (1)

	
	Está genial que nos brinda servicio de analíticas

* **fabioguaidia** (1)

	
	Se ve super este curso!!!

* **David Galicia** (1)

	
	Se ve que es muy completo Firebase ofrece mas servicios aparte de almacenamiento

* **Kevin Jeremy Salazar Jimenez** (1)

	
	exelente explicacion

* **Cristhian Arce** (1)

	
	Tengo muchas expectativas!

* **john fredy quimbaya orozco** (1)

	
	buen curso espero poder solucionar un inconveniente de un desarrollo con este curso

* **Pamela Cinthya Torres Gutiérrez** (1)

	
	esto es una maravilla

* **Lordpanther** (1)

	
	Excelente resumen sobre las funciones y las necesidades de un backend 😃

* **misael-calvillo-mancilla** (1)

	
	Con Firebase tienes todo lo que necesitas para levantar una plataforma bastante completa.

* **carlosbazanhuaman** (1)
interesante los servicios que tiene.

* **andoni** (1)
Estoy haciendo un proyecto con una raspberry y un sensor de huella digital, quiero pasar y leer datos a una bd nosql en la nube mediante ...

	* **carlosbazanhuaman** (1)

		
		Si usas el **sdk **de firebase para la web deberias poder conectarte y alamcenar data en formato json con la estructura que necesitas.

* **Sebastian Cardoso Castillo** (1)
Si tengo una base de datos en Cloud SQL debería usar Firebase para autenticar usuarios?

	* **Edward Steven Ramos Palacios** (1)

		
		Depende. Podría decirte que si tienes mas servicios de firebase y de alguna manera necesitas pasar por ahi para usar la BD podrias proabr cloud functions. Pero me parece que talvez sea mejor acceder directamente a cloudSQL con la forma en la que ellos te lo pemitan.

* **milton** (1)
Se puede hacer funcionar wordpress en firebase?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		No, firebase es una base de datos NoSQL y la estructura de Wordpress usa bases de datos relacionales principalmente MySQL

* **Brayan Mamani** (0)

	
	Con Firebase puedes tener plataforma bastante completa de forma sencilla a un costo accesible.

## 0030. Creación del proyecto

### Descripción:


### Links:

* [Sign in - Google Accounts](https://console.firebase.google.com/)

### Comentarios:

* **Juan David Castro (Platzi)** (11)

	
	En este vídeo también vemos cómo crear un proyecto de react para utilizar Firebase en el nuevo sitio de Podcasts de la gente de [Aprendiendo Frontend](https://www.youtube.com/channel/UC6nEW2GNewHJn9KXT_Mvwuw):
	
	  * [Raw live coding - Creamos un proyecto con ReactJS desde cero.](https://www.youtube.com/watch?v=0Q1p1cXI_64)
	
	

* **Jhonnatan Leonardo Cumaco Robayo** (7)

	
	El curso se actualizará? Es que veo muchos cambios en la plataforma actual, gracias.

	* **emercadogarcia** (1)

		
		Seria bueno que sea actualizado para un mejor seguimiento.

	* **David Galicia** (1)

		
		Si por que la interfaz de creación de proyecto ah cambiado mucho

* **eltenis** (6)

	
	es mejor firestore? o mejor realTimeDataBase??? Muchas Gracias!!!

	* **Alexander  Silvera** (7)

		
		Es mejor firestore ya que tiene muchas más funcionalidades, que realtime no tiene o son complejas de poder realizar. Aunque firestore esta en beta aún es bueno comenzar a implementarla en nuestros proyectos.

	* **Matias Niz** (6)

		
		Con firestore puedes hacer consultas superficiales y ese para mi es uno de los mejores puntos con respecto a realtime database. Esto significa que si tenemos anidada una colección llamemosla alumnos, y cada alumno tiene una colección de los cursos que realizó, al momento de consultar la colección de alumnos solo me va a retornar los alumnos. Con Realtime database al realizar una consulta en el nodo de alumnos, trae los alumnos y también todos los cursos que realizaron, es decir sus sub colecciones. Y esto es porque realtime database es un json gigante. También firestore no tiene la limitante de las conexiones recurrentes que si tiene realtime database.
		
		Aqui se encuentran todas las diferencias: <https://firebase.google.com/docs/database/rtdb-vs-firestore?hl=es-419>

	* **Brayan Mamani** (1)

		
		**_Firestore_** por que nos ofrece mejor rendimiento y es mucho mas rápido.

	* **Daniel Esteves** (1)

		
		Firestore mil veces, digamos que traes datos de Firebase en tu SPA, Static Site o solo un HTML. Firebase se encargará de hacer el get respectivo para que tus datos siempre se encuentren actualizados en todo momento

* **Iván Mauricio Toro Cifuentes** (5)

	
	[El repo del curso.](https://github.com/jggomez/blogeek-platzi)

	* **Jorge Heli Rueda Uribe** (1)

		
		Excelente esta información. Gracias.

* **David Farinango** (4)

	
	eeeee me encanta esta actualización del curso anterior!!! pfff!!! ya me emocioneeee es justo lo que necesito para el proyecto en el que estoy trabajando 😄

* **Brian Bentancourt** (4)

	
	se nota que ha mejorado el curso con respecto al anterior

* **Jesus Ricardo Moreira Cedeño** (4)

	
	Me estoy emocionando mucho, ya quiero empezar! 😃

* **dipacata** (2)

	
	Como hago para Borrar un proyecto?

	* **Juan Carlos Suarez Medina** (1)

		
		En firebase/Configuracion/ luego seleccionas el proyecto y te vas a la parte de abajo donde dice borrar proyecto

	* **Juan Carlos Suarez Medina** (1)

		
		En la siguiente clase lo explican a detalle

* **Lordpanther** (2)

	
	La autenticación, un dolor de cabeza para muchos 😃

	* **william andres rodriguez borja** (1)

		
		y usa oauth que es pues no es que sea complicada pero si toma tiempo el aprender como implementarla aca es click , click , click listo tengo autenticacion.

* **Guillermo Moreno Lopez** (1)

	
	Al aprender esto, se me vienen muchos planes en mente

* **carlosbazanhuaman** (1)

	
	se pueden crear varios proyectos, es muy interesante.

	* **ddragaid** (1)

		
		si puedes tener la cantidad que quieras firebase te cobra es por consumo

* **Decgar** (1)

	
	Que buen proyecto! 😃

* **Andersson Ramirez** (1)

	
	Proyecto creado!!

* **Joaquin García Santiago** (1)

	
	Crear proyecto

	* **DracoClvo** (4)

		
		escribir comentario …

	* **Johan Manuel Perez Soto** (1)

		
		Lo que sea por puntos…

* **Pamela Cinthya Torres Gutiérrez** (1)

	
	gracias muy interesante

* **MaicolQJ** (1)

	
	falto la autenticación por mensaje de texto

* **marco2018** (1)

	
	haber ahi vamos, es interesante

* **Luis Eduardo Figueroa** (1)
¿Este curso es el que necesito para trabajar con react native?

	* **Diego Ivan Padilla Bernal** (1)

		
		En ambos se usa javascript así que podría decirse que si

* **alexanderorellanam** (0)
¿Cual es la principal diferencia entre firebase y mongodb ? Lo comento porque estoy creando una aplicacion que la quiero desplegar via WE...

	* **Facundo Nicolás García Martoni (Platzi)** (4)

		
		La principal diferencia es que Firebase es un **PaaS (Platform as a service)** y Mongo es una base de datos basada en documentos que se instala en tu servidor (que puede ser tu propia computadora, o estar en la infraestructura de Google, Amazon, Microsoft, etc). Firebase contiene su propia base de datos documental no relacional llamada **Firestore** , pero esta se carga y configura automáticamente cuando inicias un proyecto en la plataforma 😉
		
		Mi recomendación personal es que inicies tu proyecto con Firebase por la facilidad de uso, y si posteriormente sientes la necesidad de migrar tus datos a otra base de datos puedas hacerlo ya con un nivel de experiencia mayor.

# Consola Web de Administración

## 0040. Consola de administración

### Descripción:


### Links:

* [Manage project access with Firebase IAM  |  Firebase](https://firebase.google.com/docs/projects/iam/overview)

### Comentarios:

* **Juan David Castro (Platzi)** (17)

	
	La ubicación de los servidores **NO** se puede cambiar después de crear el proyecto 😰😱.  
	Ojo con eso 👀👁😛.

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Un dato importante para tener en cuenta.

	* **Sebastian Cardoso Castillo** (2)

		
		En realidad con el SDK de Google Cloud se puede escribir:
		``` 
		    gcloud config set compute/zone NAME
		    
		```

* **jesusmurf** (5)

	
	Aunque normalmente Firebase se usa en el frontend _también puede usarse en el backend._
	
	Existen SDK para Nodejs, Java, Python y Go. (existen librerías de terceros para otros lenguajes creadas por las diferentes comunidades)

* **omarmus** (4)
Creo que enfocan demasiado al profesor en vez de mostrar la pantalla, solo muestran la pantalla unos segundos y luego cambian el foco al ...

* **Elvis Serrano** (3)

	
	Una pregunta a la comunidad, cree una aplicación móvil con react native pero los datos se almacenan localmente con sqlite, ahora el cliente quiere que los datos se puedan ver desde una aplicación web le plantee utilizar firebase, mi pregunta es la siguiente: es necesario por ejemplo usar java con spring framework y crear un tipo de api usando firebase para ser consumida luego por react native y el frontent de la aplicación web que se realizara con reactjs.? espero haberme explicado bien.

	* **Juan David Castro (Platzi)** (7)

		
		Hola! Puedes ir con cualquiera de las dos… 😮
		
		Puedes conectarte directamente a Firebase desde la página web y la aplicación móvil (y cualquier otra plataforma) sin problemas. Pero si quieres crear tú mismo una API que se conecte a Firebase y devuelva los datos también es buena opción… 😉
		
		También te recomiendo que tomes el [Curso de Firebase Cloud Functions](https://platzi.com/cursos/firebase-cloud/) para extender aún más el funcionamiento de Firebase… 👌

* **Santalch** (3)

	
	Para aplicar esto hay que saber backend?

	* **Brayan Mamani** (1)

		
		No es necesario pero si lo sabes será mas sencillo.

	* **Daniel Esteves** (3)

		
		De hecho no necesitas conocimientos de backend, Firebase está diseñado para que cualquier tipo de persona lo pueda entender 😎

* **Gerardo Manuel Reyes Fernández** (3)

	
	En el caso de que te inviten a un proyecto como propietario, ¿Contaría en el uso de recursos que tienes, o solo se tomaría en cuenta para la persona que creó el proyecto?.  
	Por ejemplo, imaginemos que soy alguien que tiene varios proyectos y estoy por exceder el límite del plan spark y alguien me invita como propietario de su proyecto,¿ Esto me afectaría?

	* **jggomezt** (5)

		
		No afecta es totalmente aparte, osea eso no cuenta como tus proyectos

	* **Brayan Mamani** (1)

		
		Genial 😃

	* **Gerardo Manuel Reyes Fernández** (1)
![](http://img.desmotivaciones.es/201010/mr_burns.jpg)

* **Jesus Ricardo Moreira Cedeño** (3)

	
	Muy bien explicado :3

* **Pamela Cinthya Torres Gutiérrez** (2)

	
	WOOW ESTA SUPER GENIAL, gracias esto me esta sirviendo enormemente

* **Sebastian Cardoso Castillo** (2)

	
	Cuando cree mi proyecto quise seleccionar los servidores de Sudamerica y no me dejo porque GCP me decía que estaban teniendo problemas. El problema es que para cambiar el servidor tengo que cambiar el id del proyecto o borrar la app y esperar 30 dias para usar el mismo nombre.

* **Francisco Lopez** (2)

	
	Un proyecto de firebase puede ser gestionado por varios usuarios

	* **Daniel Esteves** (1)

		
		Bastantes usuarios, como la persona lo vea necesario y con los permisos que le puedes dar a cada uno de ellas; tal vez necesites solo a uno que sea el encargado de el Analytics, y así 💪

* **Gerardo Manuel Reyes Fernández** (2)
En el caso de que te inviten a un proyecto como propietario, ¿Contaría en el uso de recursos que tienes, o solo se tomaría en cuenta para...

	* **jggomezt** (5)

		
		No afecta es totalmente aparte, osea eso no cuenta como tus proyectos

* **carlosbazanhuaman** (1)

	
	clase muy buena.

* **Andersson Ramirez** (1)

	
	Bastante completo se ve…

* **Kevin Jeremy Salazar Jimenez** (1)

	
	exelente explicacion

* **jangove** (1)
Quiero conectar a Laravel

	* **Erik Ochoa (Platzi)** (2)

		
		Buscando en google encontré este artículo de cómo [integrar laravel con firebase](https://medium.com/@javinunez/how-to-integrate-laravel-with-google-firebase-512188adae13) que tal vez te pueda servir.

* **Elvis Serrano** (1)
Una pregunta a la comunidad, cree una aplicación móvil con react native pero los datos se almacenan localmente con sqlite, ahora el clien...

	* **Juan David Castro (Platzi)** (7)

		
		Hola! Puedes ir con cualquiera de las dos… 😮
		
		Puedes conectarte directamente a Firebase desde la página web y la aplicación móvil (y cualquier otra plataforma) sin problemas. Pero si quieres crear tú mismo una API que se conecte a Firebase y devuelva los datos también es buena opción… 😉
		
		También te recomiendo que tomes el [Curso de Firebase Cloud Functions](https://platzi.com/cursos/firebase-cloud/) para extender aún más el funcionamiento de Firebase… 👌

## 0050. Configuración de Firebase en el proyecto

### Descripción:


Vamos a crear nuestro proyecto sin ningún framework de JavaScript, solo un archivo `index.html`, los estilos de la aplicación con CSS y algunos archivos de configuración para crear un servidor local mientras subimos el proyecto a un servidor de verdad. Toda la lógica de nuestra aplicación esta lista, así que podemos concentrarnos en construir la conexión Firebase y terminar algunas funcionalidades.

Lo primero que debemos añadir para crear nuestros proyectos son los archivos de Firebase, uno con el código base de la librería y otro para cada servicio que utilizamos en nuestra aplicación. Gracias a esta división nuestra aplicación puede cargar menos archivos y funcionar mucho más rápido.

### Links:

* [Add Firebase to your JavaScript Project  |  Firebase](https://firebase.google.com/docs/web/setup)

### Comentarios:

* **Juan David Castro (Platzi)** (13)

	
	👀 Si dominan GIT podemos hacer fork del proyecto en Github y seguir el curso desde este commit para escribir todo el código de la aplicación paso a paso 👍:
	
	  * [@jggomez/blogeek/3c39e11 - Github](https://github.com/jggomez/blogeek-platzi/tree/3c39e11cc8f5ed7b0c98429669c0bc23a49fa196)
	
	

	* **Aneudy Abreu** (1)

		
		Excelente, gracias!

	* **valentina-rua-carrillo** (0)
Hola ya cree el proyecto en firebase, pero de donde sacamos el proyecto en el que estas trabajando en visual studio

	* **Juan David Castro (Platzi)** (2)

		
		De aquí **@valentina-rua-carrillo** : <https://github.com/jggomez/blogeek-platzi/tree/3c39e11cc8f5ed7b0c98429669c0bc23a49fa196>, o, si prefieres, puedes entrar a la sección de archivos y “Descargar todo” 👍.

	* **samuelsotomayor** (1)

		
		Gracias juandc.
		
		Platzi debería de poner este enlace en la parte de enlaces del curso para ahorrarnos tiempo

	* **Luis Rangel Castro** (3)

		
		`git clone https://github.com/jggomez/blogeek-platzi.git`

	* **Luis Rangel Castro** (2)

		
		Para iniciar desde el principio
		``` 
		    git clonehttps://github.com/jggomez/blogeek-platzi.git
		    
		```

	* **Luis Rangel Castro** (2)

		
		Segundo Paso:
		``` 
		    git checkout origin/configuracionfirebasealproyecto
		    
		```

* **Carolina Londoño** (6)

	
	El proyecto está en algún repositorio?

	* **Cesar Murillo** (7)

		
		<https://github.com/jggomez/blogeek-platzi>

	* **David Galicia** (1)

		
		Gracias zesarum

	* **FranLop84** (1)

		
		Gracias!

* **Carlos Andrés Millan Satizabal** (6)

	
	Como la carpeta config tiene el archivo con los datos del proyecto, por lo tanto al subir los archivos a github, no es bueno que vaya ese archivo allí y que lo vean los demás, por eso se agrega ese archivo a .gitignore

* **Jonathan de Jesús Chávez Tabares** (5)

	
	¿El archivo _ConfigFirebase.js_ puede ser leído por el cliente?  
	¿Qué pasa si alguien lo descubre y lo usa en su app?
	
	No me quedó claro eso.

	* **Juan David Castro (Platzi)** (3)

		
		No pasa nada. Recuerda que la forma de proteger los datos con las reglas de seguridad y restringiendo los dominios autorizados para correr la aplicación… 😉
		
		  * [Firebase Auth/unauthorized domain - StackOverflow](https://stackoverflow.com/questions/48076968/firebase-auth-unauthorized-domain-domain-is-not-authorized)
		
		

* **Luis Javier Quijije Parrales** (5)

	
	Cuando se haga el deploy de la app en el hosting de firebase esos archivos js seran visibles desde el F12 en el navegador? Cualquiera podria ver mi config de conexion.

	* **Daniel Esteves** (1)

		
		Tienes dos opciones, o restringir el uso de esa configuración para solo tu dominio y aunque te vean ese archivo no puedan utilizarlo ya que solo funciona con tu dominio o usando variables de entorno

* **Juan David Castro (Platzi)** (5)

	
	¿Cuál es la extensión de VSCode que utiliza el profe para lanzar ese mini efecto de fuego cada vez que editamos el código? 😍🔥

	* **jggomezt** (5)

		
		jejeje, es bueno, se llama power mode

	* **Juan David Castro (Platzi)** (1)

		
		Thank u @jggomezt 😄

	* **Juan David Castro (Platzi)** (1)

		
		Por si quieren, el repo de la extensión es este 👉: <https://github.com/hoovercj/vscode-power-mode> 😬.

	* **Jesus Ricardo Moreira Cedeño** (1)

		
		Gracias

* **omejenes** (3)

	
	Tengo que poner velocidad 2X porque aveces no entiendo que dice con tanta pausa, parecido a cuando habla AMLO.

	* **Héctor Iván Alfaro Ramírez** (1)

		
		x2

* **David Alberto Mogollón Fernández** (3)

	
	Tengo una duda, actualmente estoy usando Nuxt para crear aplicaciones SSR, y quisiera hacer deploy en Firebase hosting, pero me preocupa de si este hosting + firebase functions puedan subir mucho los costos a largo plazo, incluso mas que hacer deploy en otras plataformas con bandwidth ilimitado, que tan recomendable es usar firebase hosting para una gran cantidad de usuarios?

	* **Daniel Esteves** (1)

		
		Va a depender de la cantidad de usuarios, en los planes de Firebase de muestra las capacidades que tiene cada plan con respecto a usuarios, bandwidth, consultas y más ✨

	* **Andersson Ramirez** (1)

		
		Puedes hacer el escalado dependiendo del trafico que maneje tu aplicación, si conoces o tienes idea de cuantos usuarios lo mejor es analizar diferentes alternativas antes de casar tu proyecto a una plataforma

* **Pamela Cinthya Torres Gutiérrez** (3)

	
	Muchas gracias, pero ya encontre que es lo que tiene de diferente, Firebase solo actializao su interfaz.
	
	A los nuevos estudiantes les comento que si quieren segir el paso de copiar el código para la web, Firebase solo te solicita que registre tu app nuevamente con el nombre y despues todo ya es igual.
	
	Espero les sirva

* **joseadrian** (3)

	
	Como creaste ese proyecto O.o?!

	* **joseadrian** (4)

		
		Creo que ahora debo tomar un curso de desarrollo web

	* **Daniel Esteves** (1)

		
		Ese proyecto es un starter, quiere decir que ya viene construido para nosotros ejemplificar el uso de Firebase. Puedes construir el tuyo propio y gracias a los conocimientos que vas obteniendo del curso lo vas plasmando en tu proyecto 🤙

* **Jessie Buckland Pérez** (2)

	
	Acabo de crear una aplicación IONIC con REACT y la mayoría de configuración actual a fecha de 21/03/2020, si alguien le interesa compartir algún consejo o pedirlo solo debe contactarme vía twitter, la verdad que es increíble la de cosas que ofrece ahora mismo Firebase, y si te interesa el potencial de todas las opciones de configuración para aprenderlas , cuenta con mi ayuda!!

	* **davidsc34** (1)

		
		Hola compañero, gracias por tu disposicion, una pregunta, en la opcion de hosting de firebase te ofrece agregar tu dominio, quiere decir que se hace una copia a ese dominio o se mantiene en el hosting de firebase ?  
		Saludos, gracias

* **jasanhdz** (2)

	
	<https://jasanhdz.github.io/BlogGeek/src/htmls/>

* **Jorge Heli Rueda Uribe** (2)

	
	Lo que he entendido hasta ahora es que Firebase es un backend gestionado, le quedaría a uno hacer el front end. Con qué herramienta se puede hacer el front end rápidamente?

	* **Daniel Esteves** (4)

		
		Con la que te sientas más cómodo, puedes utilizar frameworks de CSS como Bootstrap o TailwindCSS o de JS como React o Vue 🙌

	* **Jorge Heli Rueda Uribe** (2)

		
		Muchas gracias Daniel Esteves! (@danestves)

* **Kevin Julián Martínez Escobar** (2)

	
	Comentas que el archivo de configuración es privado pero si se añade en como script de front en el index.html con que me meta en el browser puedo ver ese archivo y sus api keys. No entiendo entonces ¿Es privado ese archivo?

	* **Daniel Esteves** (2)

		
		Para términos de este curso se utilizó así. Pero en un ambiente de producción estos archivos deben ser privados y consultados a través .env variables

* **Pamela Cinthya Torres Gutiérrez** (2)

	
	acabo de realizar este paso y no me aparece esa pantalla me aparece esta. me podrían ayudar por favor, ¿Que es lo que procede?
	
	1.- ¿Registro el mismo nombre de mi proyecto?  
	2.- ¿Registro otro nombre?
	
	![detalle-confi-web.png](https://static.platzi.com/media/user_upload/detalle-confi-web-00edb8d4-dfae-44ff-9edd-32755efb356d.jpg)

	* **Jefferson Riobueno** (1)

		
		Solucionaste?

	* **jagallego** (1)

		
		Si, debes de añadir el nombre de la aplicación

	* **Renzo Bendezu Pautrat** (1)

		
		Efectivamente, debes poner el mismo nombre de tu proyecto en local

* **nova12** (2)
He trabajado con firebase y me doy cuenta que el manejo de javascrip hace que los accesos queden visibles en los escripst, como se pued...

	* **JorgeMontesinos** (1)

		
		Imagino que con Webpack, webpack a partir de varios archivos de JS te genera uno o unos pocos según la configuración que le des, hay un curso acá de Leonidas Esteban Pruebalo

* **Juan David Castro (Platzi)** (2)
¿Cuál es la extensión de VSCode que utiliza el profe para lanzar ese mini efecto de fuego cada vez que editamos el código? 😍🔥

	* **jggomezt** (5)

		
		jejeje, es bueno, se llama power mode

* **Marielby Carmona** (1)

	
	Quien puede aclarare cual es el nombre del servidor local que nombro el profesor? no se lo entiendo bien.

	* **Samuel Mata** (2)

		
		Hola amiga 👋, por un servidor local el profesor se refiere a um live server, que sirve la aplicacion en nuestro navegador y detecta automáticamente los cambios realizados en el código y refresca la pagina automaticamente.
		
		Similar a la funcionalidad de brinda webpack cuando construimos una aplicación React o Vue. Te recomiendo el [curso de Webpack](https://platzi.com/clases/1620-webpack/21121-servidor-de-desarrollo/) para que lo entiendas con mayor precisión. Saludos!! 😁

	* **Jose Manuel Salazar** (1)

		
		el nombre del servidor que comentó fue gulp.

	* **Francisco914** (3)

		
		Solo comentar que Gulp no es un servidor, mas bien es un gestor de tareas parecido a Webpack.

* **Oscar Martinez** (1)

	
	A alguien más no le dan el url de su storageBucket en el script? Alguien sabe el por que?

	* **samuelsotomayor** (1)
Porque no has configurado tu storageBucket

* **iamyoujared** (1)

	
	Simon solo descarga el repo y con un reset --hard al ultimo commit. y dawn listo!

* **David Farinango** (1)

	
	Y si utilizo algun framework como funcionaria? jaja

	* **David Farinango** (1)

		
		En el caso de React como le uso? jaja

	* **Enrique Alexis Lopez Araujo** (2)

		
		Ya revisaron lo que publico @juandc [deploy firebase en react](https://platzi.com/tutoriales/1435-firebase-web/3240-deploy-reactjs-app-on-firebase-julien-rioux-medium/)

	* **jggomezt** (1)

		
		Hola, reactJS es Javascript, revisa en cual capa o modulo es adecuado hacer el llamado que facilite el mantenimiento si cambias tu repositorio

	* **Daniela Gonzales** (1)

		
		usa <https://www.npmjs.com/package/firebase>

* **Jefferson Martínez** (1)

	
	¿Cómo creó el proyecto? usó node?

	* **jggomezt** (1)

		
		Hola, puedes descargar el código (creo que es lo mas adecuado) o empieza desde cero, no es necesario el node, aunque se usa para el gulp.

* **ing.stephanysc** (1)
No veo la carpeta config en el zip de descarga. Alguien me indica que hacer?

	* **Juan David Castro (Platzi)** (1)

		
		Así debe ser. Cada proyecto tiene API KEYs diferentes. Debes crear los archivos de la carpeta config por tu cuenta con la configuración que te da Firebase.

* **monicamesa360** (1)
Todos esos archivos(ja, html, auth, etc) no los creamos desde 0 o dónde se encuentran?

	* **Juan David Castro (Platzi)** (1)

		
		Los encuentras en la sección de Archivos y Enlaces de cada clase. 😉

* **emercadogarcia** (1)
Que extensión usan para crear proyecto html con todas las carpetas?

	* **Juan David Castro (Platzi)** (1)

		
		Disculpa, no entiendo tu pregunta. ¿Qué funcionalidad dices que hace la extensión por la que preguntas?

* **Pamela Cinthya Torres Gutiérrez** (1)
quise probar la documentación y no tiene funcionalidad el botón de inicio, no se si me pueden AYUDAR. no me aparecen los modales, el únic...

	* **alexanderorellanam** (1)

		
		yo tambien tengto el mismo problema, porque favor quien puede compartir el codigo , porque asi no se hace funcional la clase.

* **Jonathan de Jesús Chávez Tabares** (1)
¿El archivo ConfigFirebase.js puede ser leído por el cliente? ¿Qué pasa si alguien lo descubre y lo usa en su app? No me quedó c...

	* **Juan David Castro (Platzi)** (3)

		
		No pasa nada. Recuerda que la forma de proteger los datos con las reglas de seguridad y restringiendo los dominios autorizados para correr la aplicación… 😉
		
		  * [Firebase Auth/unauthorized domain - StackOverflow](https://stackoverflow.com/questions/48076968/firebase-auth-unauthorized-domain-domain-is-not-authorized)
		
		

* **David Farinango** (1)
Y si utilizo algun framework como funcionaria? jaja

	* **David Farinango** (1)

		
		En el caso de React como le uso? jaja

* **Jefferson Martínez** (1)
¿Cómo creó el proyecto? usó node?

	* **jggomezt** (1)

		
		Hola, puedes descargar el código (creo que es lo mas adecuado) o empieza desde cero, no es necesario el node, aunque se usa para el gulp.

# Autenticación de Usuarios

## 0060. Servicios de autenticación y configuración de usuarios

### Descripción:


Firebase nos proporciona una configuración muy sencilla para manejar la creación de usuarios, inicio de sesión y logout de la aplicación con email y password o con redes sociales _(Google Accounts, Facebook, Twitter, Github o incluso nuestros proveedores personalizados)_.

Firebase nos proporciona SDKs _(Software Development Kits)_ para facilitar la programación y configuración de estas funcionalidades en los lenguajes y plataformas más comunes, en caso de no encontrar estas librerías oficiales podemos encontrar diferentes herramientas creadas por la comunidad. Tambien tenemos acceso y control muy personalizado de toda esta información gracias a la Consola de Firebase.

Gracias al servicio de autenticación de usuarios de Firebase podemos ahorrar mucho tiempo programando estas mismas funcionalidades por nuestra cuenta.

### Links:

* [Get Started with Firebase Authentication on Websites  |  Firebase](https://firebase.google.com/docs/auth/web/start)

* [Users in Firebase Projects  |  Firebase](https://firebase.google.com/docs/auth/users)

### Comentarios:

* **Juan David Castro (Platzi)** (10)

	
	Podemos tener **ilimitadas** cantidades de usuarios registrados y aún así Google **no nos cobra** ni un centavo 😱🎉. **AWESOME**! 😍

	* **Luis Javier Quijije Parrales** (5)

		
		Pero ojo que el plan spark solo permite hasta 100 conexiones simultaneas a la base de datos, así que si tuviera 1 milllon de usuarios registrados, solo la pueden usar 100 al mismo tiempo.

	* **andrerivera** (1)

		
		pero si pagas, alguna suscripción se incrementaría?.. o ese es el límite?

	* **dipacata** (1)

		
		Buen dato para saber que tanto podemos explotar el free 😃

* **Jeffersson Muñoz Torres** (5)

	
	Para encontrar los scripts actualizados también puede visitar la documentación oficial de Firebase  
	<https://firebase.google.com/docs/web/setup?authuser=0>

* **darwinyusef** (5)

	
	las claves no deberian ir en el env.js?

	* **Daniel Esteves** (1)

		
		Si en efecto, pero para el curso se hizo de esta manera para que se pueda ver donde están; pero existen muchas maneras de ocultar estas configuraciones para que el cliente no las pueda ver

* **darwinyusef** (5)

	
	Se que este es un comentario fuera de lo común pero le sale candela (Fire) al PC del profe en el 5:20 jajajaja

	* **Jessie Buckland Pérez** (1)

		
		yo lo vi también y no pude evitar distraerme y buscar por aquí si alguien se había fijado, es top la llamita que sale jajajaja

	* **balachvinic** (1)

		
		Si es un plugin de VS Code está muy cool se llama Power Mode

* **Everson Vidal Mamani Huayta** (3)

	
	En este video solo agregamos estos 2 scripts al proyecto si quieren acortar tiempo… peguen estos scripts…
	
	<!-- Firebase App is always required and must be first -->  
	<script src=“<https://www.gstatic.com/firebasejs/5.5.8/firebase-app.js>”></script>
	
	<script src=“<https://www.gstatic.com/firebasejs/5.5.8/firebase-auth.js>”></script>

* **Lordpanther** (3)

	
	Excelente, y de paso google gana con todos estos usuarios registrados 😃

	* **Jeffersson Muñoz Torres** (1)

		
		También fue lo primero que pensé jeje

* **Andersson Ramirez** (2)

	
	Tan fácil q se vuelve algo q hasta hace unos años requería muchas lineas de código

* **alejandropereira** (2)

	
	 **_ quiero hacer un API que se consuma con auth anónima desde cualquier dominio. no puedo añadir a la whitelist manualmente cada domino que puedo hacer? _**

	* **Daniel Esteves** (2)

		
		Puedes utilizar Firebase Functions para esto, y así ellos te darán una URL o puedes personalizarla en el que puedan interactuar con la API

* **john fredy quimbaya orozco** (2)

	
	Hola alguien me podría ayudar con el siguiente error ya que implemente un nuget pero hay una falla con firebase. ![](![Error C#.png](https://static.platzi.com/media/user_upload/Error%20C%23-ce3fc1d1-c953-4d8c-aa6e-d00daaedac71.jpg)

	* **Daniel Esteves** (1)

		
		Ocurrió un error de conexión de tu código con Firebase, ¿podrías mostrarnos el código para poder ayudarte?

* **Alexander  Silvera** (2)
Hola si tengo una aplicación de django y quiero realizar un login de usuarios con firebase, como debo de hacerlo??

	* **jggomezt** (4)

		
		Hola, no se nada de django, pero si usas JS, en una de las clases te enseñamos, si es python, hay un SDK para python <https://firebase.google.com/docs/reference/admin/python/>  
		Y puedes ver como se realiza la creacuín y autenticación  
		<https://firebase.google.com/docs/reference/admin/python/firebase_admin.auth#create_user>  
		Este video  
		<https://www.youtube.com/watch?v=5UO7_sglpMQ>

* **Sergio David Paez Suarez** (1)

	
	Otra pregunta: ¿Como puedo combinar el auth con firestore?, por que estaba pensando usar auth y los datos del usuario extra que necesito del usuario guardarlos en firestore identificandolos con el uid del usuario.

* **carlosbazanhuaman** (1)

	
	se ve muy facil, que herramienta tan practica.

* **Alexander  Silvera** (1)

	
	Hola si tengo una aplicación de django y quiero realizar un login de usuarios con firebase, como debo de hacerlo??

	* **jggomezt** (4)

		
		Hola, no se nada de django, pero si usas JS, en una de las clases te enseñamos, si es python, hay un SDK para python <https://firebase.google.com/docs/reference/admin/python/>  
		Y puedes ver como se realiza la creacuín y autenticación  
		<https://firebase.google.com/docs/reference/admin/python/firebase_admin.auth#create_user>  
		Este video  
		<https://www.youtube.com/watch?v=5UO7_sglpMQ>

* **Jesus Ricardo Moreira Cedeño** (1)

	
	Nice :3

* **Juan H** (1)
Para integrar firebase a AngularTS, corriendo el comando firebase init ¿Este ya configura todas las credenciales?

	* **Erik Ochoa (Platzi)** (2)

		
		`firebase init` crea un archivo de configuración llamado _firebase.json_ en la raíz del directorio. El comando te guía paso a paso en la configuración del directorio del proyecto.
		
		Puedes leer más en la [documentación](https://firebase.google.com/docs/cli).

* **Juan Carlos Suarez Medina** (1)
Que aplicacion utiliza el profe para programar?

	* **Jose Padron (Platzi)** (2)

		
		Visual studio code

* **alejandropereira** (1)
** _ quiero hacer un API que se consuma con auth anónima desde cualquier dominio. no puedo añadir a la whitelist manualmente cada domino ...

	* **Juan David Castro (Platzi)** (1)

		
		Entonces puedes NO especificar cuáles son los dominios que tienen permiso. Y para proteger los datos de tu aplicación puedes usar las Reglas de Seguridad de Firebase. 😉
		
		👉 <https://platzi.com/blog/reglas-de-seguridad-avanzadas-con-firebase-y-firestore/>

## 0070. Habilitar en la consola los servicios de autenticación por email y Google

### Descripción:


Después de habilitar los servicios de autenticación con email y Google Accounts podemos programar el código necesario para enviar la información de los usuarios cuando se registran en nuestra aplicación.

Nuestro proyecto tiene lista la UI del formulario para el registro, los usuarios deben escribir sus datos básicos y al momento de hacer click en el botón vamos a ejecutar la función `Autenticación.crearCuentaEmailPass` del archivo `autenticacion.js`, solo debemos llamar al método `firebase.auth().createUserWithEmailAndPassword` con los datos más importantes del usuario. Además, si el registro es exitoso podemos actualizar el resto de información de los usuarios con el método `user.updateProfile` o mandar las verificaciones que necesitemos.

### Comentarios:

* **Juan David Castro (Platzi)** (12)

	
	Después de autenticar a los usuarios con email y contraseña _(`firebase.auth().createUserWithEmailAndPassword(email, password)`)_ podemos añadir el resto de su información ya que este método devuelve una promesa con el usuario recién creado y un método `updateProfile` para actualizar los datos 👍.
	
	Si en vez de utilizar email y contraseña utilizamos Google Accounts o cualquier otra autenticación por redes sociales nos ahorramos esta actualización de los datos del usuario porque Firebase añade automáticamente los datos de cada cuenta al registro 👌.

	* **Jesus Ricardo Moreira Cedeño** (1)

		
		Entiendo, gracias

* **tabufell** (8)

	
	mirenlo a 1.25x

* **Felipe Ruiz** (8)

	
	Muy buen video pero por favor desinstala el efecto de fuego 😂👌🔥

* **Juan David Castro (Platzi)** (4)

	
	¿Qué pasa cuando intentamos crear un usuario con email y contraseña pero el usuario ya esta creado? ¿Firebase devuelve un error o autenticamos automáticamente a los usuarios? 🤔

	* **Kevin Santacruz** (5)

		
		Hola, te devuelve Error code: `auth/email-already-in-use`  
		Puedes revisar todos los códigos de respuesta que existen  
		[Documentación](https://firebase.google.com/docs/reference/js/firebase.auth.Auth?hl=es-419#createUserAndRetrieveDataWithEmailAndPassword)
		
		Saludos

	* **jggomezt** (2)

		
		Hola gracias @krsb1. @juandc aqui tambien puedes encontrar los codigo de error de forma consolidada  
		<https://firebase.google.com/docs/auth/admin/errors?hl=es-419>

	* **Daniel Esteves** (1)

		
		Eso es algo muy particular, cuando te devuelve el error de que el usuario ya está creado lo que puedes hacer es darle feedback al cliente de que puede iniciar sesión o generar una nueva contraseña si el caso es que se le ha olvidado sus credenciales

* **louismanson** (3)

	
	Para el efecto de fuego en VSC <https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode>

* **Johan Manuel Perez Soto** (3)

	
	Soy el pto amo, lo hice con la validación mediante numero de teléfono

	* **Daniel Esteves** (1)

		
		Wow 🤩 fantástico Johan, ¿podrías compartir el código o repositorio y así todos podemos aprender de la manera en la que lo has hecho?

* **jesusmurf** (3)

	
	Para crear un nuevo usuario: **.createUserWithEmailAndPassword** ( _email, password, nombres_ )  
	Para enviar un correo de verificación: **.sendEmailVerification** ( _configuracion_ )  
	Para cerrar sesión: **.signOut()**

* **Jose Rueda** (3)
como inicio el servidor para entrar con local host 3000 ?

	* **Enrique Alexis Lopez Araujo** (9)

		
		Hola @bender89 ya que bajaste el codigo de [github](https://github.com/jggomez/blogeek-platzi) tienes que instalar el cliente de gulp como dependencia global:
		
		`npm install --global gulp-cli`
		
		Despues dentro de la carpeta del proyecto tambien instala las dependencias faltantes:
		
		`npm install --global gulp-cli`
		
		Y para correr el servidor solo en la consola, pon:
		
		`gulp`
		
		Si tienes algun problema no dudes en pooner tus comentanrios

* **Maximo Martinez Soria** (2)

	
	Que nervioso me pone el fueguito que aparece cuando escribe.

	* **louismanson** (1)

		
		Power Mode en el market de Visual Studio :p

* **Luis Rangel Castro** (2)

	
	Instalar Global:
	``` 
	    npm install gulp-cli -g
	    
	```
	
	Instalar dentro del proyecto
	``` 
	    npm install gulp -D
	    
	```
	
	Ejecutar:
	``` 
	    gulp
	    
	```

	* **Marielby Carmona** (1)

		
		Gracias!

* **valentinafernandez** (2)

	
	1.75x

* **joseadrian** (2)

	
	con el sendEmailVerification(), el usuario queda bloqueado hasta que se verifique, o despues de iniciar sesión (sin verificar) puede usar nuestra página, ya que ha iniciado sesión.

	* **Mariangelica Useche Saavedra** (5)

		
		Según entiendo, debes agregar tú la verificación en el inicio de sesión, ya que el usuario sí se podrá autenticar, ahora, que entre al sistema o no, queda de tu parte.
		
		Puedes hacer esa verificación así:
		``` 
		    let user = firebase.auth().currentUser
		    if(user.emailVerified){
		         return redirectToApp()
		    } else {
		    	notify({message: 'Debe verificar su correo'})
		    }
		    
		```
		
		Espero haberte ayudado.  
		Saludos.

* **andrerivera** (2)

	
	Una pregunta en la url puedo poner el dominio de mi página ya que estoy trabajando desde ahi?

	* **ebar0n (Platzi)** (1)

		
		Si probaras desde servidor si.

	* **davidsc34** (1)

		
		Hola amigo, en la seccino autenticacion de tu consola de firebase, luego en metodos de autenticacion, y abajo esta la parate de agregar dominios.
		
		Saludos, espero aun sea de ayuda

* **andrerivera** (2)

	
	antes de firebase que deberia aprender ya manejo javascript?..

	* **Daniel Esteves** (1)

		
		Literalmente nada más, ya que Firebase tiene integraciones con muchos lenguajes solo debes encontrar la integración de JS y utilizarlo a tu gusto 💪

* **Andersson Ramirez** (1)

	
	Cada vez se ve mas interesante y facil de usar

* **Facundo Petre** (1)

	
	No syntax highlighting 😢

* **jobcoronadoduran** (1)

	
	hola que tal, tengo un inconveniente y es que estoy desarrollando una web con firebase y react y es que hay un usuario administrador logueado y quiero que cuando registre un usuario este no inicie sección inmediatamente si no que conserve el usuario que esta autenticado actual mente ya que este el usuario administrador y este se encarga de registrar usuarios.seria de mucha ayudo que alguien me ayude.

* **sordonezg** (1)

	
	en que parte de la documentacion de firebase encuentras esto?

* **joseadrian** (1)

	
	Interesante, muy interesante

	* **joseadrian** (1)

		
		Materialize.toast

* **Jose Rueda** (1)

	
	como inicio el servidor para entrar con local host 3000 ?

	* **Enrique Alexis Lopez Araujo** (9)

		
		Hola @bender89 ya que bajaste el codigo de [github](https://github.com/jggomez/blogeek-platzi) tienes que instalar el cliente de gulp como dependencia global:
		
		`npm install --global gulp-cli`
		
		Despues dentro de la carpeta del proyecto tambien instala las dependencias faltantes:
		
		`npm install --global gulp-cli`
		
		Y para correr el servidor solo en la consola, pon:
		
		`gulp`
		
		Si tienes algun problema no dudes en pooner tus comentanrios

	* **Jose Rueda** (2)

		
		gracias, me funciono perfecto---- en algun curso se aprende gulp y montar estos servidores virtuales??

	* **Enrique Alexis Lopez Araujo** (4)

		
		Hola @bender89 en algún punto mencionan y varios comentaron como hacerlo, pero tambien por ejemplo se pudo haber instalado alguna herramienta que te permitiera mirar contenido estatico, como esta herramienta que ocupa que en particular se me hace perfecta para hacer este tipo de cosas: [web server for chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?utm_source=chrome-ntp-launcher) , es muy buena igual eliges la carpeta y te muestra el contenido igual como si hubiera ocupado gulp!

	* **Mario E Fernandez  Serrano** (1)

		
		Hola, alexisaraujo , hice los pasos que mencionas para arrancar el servidor con el comando gulp. y no me funciona, la consola me arroja esto cundo lo ejecuto! no se que puede ser 😦
		
		  master ●  gulp  
		zsh: command not found: gulp  
		/blogeek-platzi   master ● 

	* **bolmer torres contreras** (1)

		
		Bender, bajé el proyecto del repositorio. Agregué las dependencias que faltan según lo comentado con los comandos `npm install --global gulp-cli` . Al ejecutar la instrucción `gulp` en la carpeta raíz obtengo la siguiente información en la consola
		``` 
		    PS C:\Cursos\blogeek-platzi-serviciosdeautenticacionusuarios> gulp
		    fs.js:27
		    const { Math, Object } = primordials;
		                             ^
		    
		    ReferenceError: primordials is not defined
		        at fs.js:27:26
		        at req_ (C:\Cursos\blogeek-platzi-serviciosdeautenticacionusuarios\node_modules\natives\index.js:143:24)
		        at Object.req [asrequire] (C:\Cursos\blogeek-platzi-serviciosdeautenticacionusuarios\node_modules\natives\index.js:55:10)
		        at Object.<anonymous> (C:\Cursos\blogeek-platzi-serviciosdeautenticacionusuarios\node_modules\vinyl-fs\node_modules\graceful-fs\fs.js:1:37)
		        at Module._compile (internal/modules/cjs/loader.js:956:30)
		        at Object.Module._extensions..js (internal/modules/cjs/loader.js:973:10)
		        at Module.load (internal/modules/cjs/loader.js:812:32)
		        at Function.Module._load (internal/modules/cjs/loader.js:724:14)
		        at Module.require (internal/modules/cjs/loader.js:849:19)
		        at require (internal/modules/cjs/helpers.js:74:18)```
		    
		```

	* **David Galicia** (1)

		
		Gracias @alexisaraujo me funciono bien usar Chrome Web Server como solución a la configuración del localhost rápida. Por cierto en que curso enseñan a usar Gulp ?

	* **andoni** (1)

		
		Genial! con el Web Service for Chrome me funcionó 😄

* **Jair González** (1)
el correo de verificacion no se me esta enviando, estoy utilizando una cuenta gmail como smtp, pero el correo no le llega al usuario, y e...

* **alejandro-arias** (1)
Cuando uso el api para autenticar por google la pantalla de google me sale en ingles, alguien sabe como ponerla en español? Choose an acc...

* **Kevin Jeremy Salazar Jimenez** (1)
me sale que firebase.auth is not a function que hago?

* **Kevin Jeremy Salazar Jimenez** (1)
alguien me ayuda 😦 no encuentro el error class Autenticacion { CrearCuenta(email , password , nombres){ firebase.auth()....

* **alejandropereira** (1)
quiero hacer un API que se consuma con auth anónima desde cualquier dominio. no puedo añadir a la whitelist manualmente cada domi...

	* **tomas-gonzalez** (2)

		
		Hola Alejandro, como programador web que soy, si tuviera ese problema usaría un servidor web o un subdominio del servidor web por ejemplo api.miserverweb/checkip.php, este devolverá ok si la ip es correcta y ko si es incorrecta, el código sería algo así:
		
		_function getRealIP() {  
		if (!empty($_SERVER[‘HTTP_CLIENT_IP’]))  
		return $_SERVER[‘HTTP_CLIENT_IP’];
		``` 
		    if (!empty($_SERVER['HTTP_X_FORWARDED_FOR']))
		        return $_SERVER['HTTP_X_FORWARDED_FOR'];
		    
		    return $_SERVER['REMOTE_ADDR'];
		    
		```
		
		}  
		$ip=getRealIP();  
		if(strcmp($ip,“89.30.76.20”)){//pongo IP segura  
		echo “ok”;  
		}else{  
		echo “ko”;  
		}  
		_  
		Parte del código está sacado de esta página:
		
		<http://blog.unijimpe.net/obtener-direccion-ip-con-php/>
		
		Un saludo

* **Pamela Cinthya Torres Gutiérrez** (1)
como puedo sacar el local host de mi proyecto porque solo me aparece el acceso desde mi terminal?. Ya rebice el curso en mas de 3 ocasion...

	* **jggomezt** (1)

		
		debes darle en la raíz del proyecto desde la linea de comandos, el comando gulp (antes debes instalar node y gulp)

* **joseadrian** (1)
con el sendEmailVerification(), el usuario queda bloqueado hasta que se verifique, o despues de iniciar sesión (sin verificar) puede usar...

	* **Mariangelica Useche Saavedra** (5)

		
		Según entiendo, debes agregar tú la verificación en el inicio de sesión, ya que el usuario sí se podrá autenticar, ahora, que entre al sistema o no, queda de tu parte.
		
		Puedes hacer esa verificación así:
		``` 
		    let user = firebase.auth().currentUser
		    if(user.emailVerified){
		         return redirectToApp()
		    } else {
		    	notify({message: 'Debe verificar su correo'})
		    }
		    
		```
		
		Espero haberte ayudado.  
		Saludos.

* **Juan David Castro (Platzi)** (1)
¿Qué pasa cuando intentamos crear un usuario con email y contraseña pero el usuario ya esta creado? ¿Firebase devuelve un error o autenti...

	* **Kevin Santacruz** (5)

		
		Hola, te devuelve Error code: `auth/email-already-in-use`  
		Puedes revisar todos los códigos de respuesta que existen  
		[Documentación](https://firebase.google.com/docs/reference/js/firebase.auth.Auth?hl=es-419#createUserAndRetrieveDataWithEmailAndPassword)
		
		Saludos

* **jorgegilbertoperalta** (0)

	
	Yo lo estoy viendo a 2x así esta perfecto

## 0080. Probar creación de usuario y autenticación

### Descripción:


### Comentarios:

* **Ricardo Lugo Recillas** (7)

	
	Como se inicia el servicio de localhost:3000

	* **Kevin Josué Calderón Peraza** (7)

		
		Descarga gulp con npm, lo instalas a nivel global. Y como ya esta configurada gulpfile.js solo pones en la terminal de tu proyecto
		``` 
		    gulp
		    
		```
		
		Y ya deberia de correr tu proyecto en ese puerto.

	* **Ricardo Lugo Recillas** (4)

		
		Gracias

	* **Oscar Torres** (15)

		
		Me funcionó así:
		
		Entré a la terminal del proyecto:
		``` 
		    npm install --global gulp-cli
		    
		```
		
		Luego
		``` 
		    npm install --save-dev gulp
		    
		```
		
		y finalmente
		``` 
		    gulp
		    
		```

* **Tobías Schwarz** (4)

	
	No me aparece el botón para continuar al abrir el enlace de verificación.  
	En la clase se crea la constante
	``` 
	    const configuracion = {
	    	url: 'http://localhost:3000/'
	    }
	    
	```
	
	pero no se usa en ningún lado.

	* **Juan David Castro (Platzi)** (1)

		
		Podría estar mal pero, creo que esta constante la escribió el profe tratando de resolver el problema del inicio de la clase, para iniciar la configuración de Firebase necesitaba la variable `varConfig`, tal vez antes de darse cuenta probo esta nueva variable para después descubrir el error de verdad 😃.

	* **Kevin Josué Calderón Peraza** (3)

		
		En el video no se explica pero la variable se utiliza en en el metodo sendEmailVerification.
		``` 
		    result.user.sendEmailVerification(configuration).catch(err =>{
		            console.log(err);
		            Materialize.toast(err.message, 4000);
		          });
		    
		```

	* **jggomezt** (3)

		
		Exacto,
		``` 
		    const configuracion = {
		              url: 'https://blogeekplatzi-4836b.firebaseapp.com/'
		            }
		    
		            result.user.sendEmailVerification(configuracion).catch(error => {
		              console.error(error)
		              Materialize.toast(error.message, 4000)
		            })
		    
		```

	* **Cris464** (1)

		
		guarda el correo en autenticación, pero no me llega el correo de verificación

* **devops** (2)

	
	no me aparece la ventana de modal para ingresar el correo electronico ??

* **Pamela Cinthya Torres Gutiérrez** (2)

	
	alguien me podría ayudar me aparece el siguiente error después de que le puse la autenticación, y ya no me envía el correo de validación, gracias.
	
	![error con el inicio de seción.jpg](https://static.platzi.com/media/user_upload/error%20con%20el%20inicio%20de%20seci%C3%B3n-4c81f957-b1db-4265-9e2a-11cf5a36e68e.jpg)

	* **Luigui Mario** (2)

		
		Hola, a mi me pasó lo mismo y se debe a la url que coloca en el archivo autenticacion.js del objeto “configuracion”.
		
		En su caso sería de esta manera. Recuerde que el 127.0.0.1 también es el localhost y ya no es necesario mencionar el index porque el servidor ya lo detecta:
		``` 
		    const configuracion = {
		              url: 'http://localhost:5501/src/'
		            }
		    
		```

	* **devops** (1)

		
		otra sugerencia estimado??

	* **Fabian Avila** (1)

		
		Ya agregaste el dominio _localhost_ a los dominios permitidos?

	* **Pablo Victor Vargas** (1)

		
		es  
		localhost:( y el lugar donde este tu archivo index, osea cuando estas en el sitio web del curso)
		
		este fue mi caso
		
		![img.png](https://static.platzi.com/media/user_upload/img-6d66fc55-7810-4861-b8dd-233df542bfdd.jpg)

* **Joseph Alexander Whacheng Barreto** (2)

	
	Hola!
	
	Cuando mando a llamar user.displayName, me requesa null. Alguien sabe por que no se esta guardando bien el nombre?
	``` 
	    firebase.auth().createUserWithEmailAndPassword(email, password)
	          .then(result => {
	            result.user.updateProfile({
	              diplayName : nombres
	            });
	    
	```

	* **Daniel Esteves** (1)

		
		¿Podrías verificar si ya la variable resultado trae el arreglo del “user” sin necesidad de hacer “result.user”? Podrías hacer un `console.log(result)` para ver que te devuelve

	* **Ivan Aguilar Huelitl** (1)

		
		Esta mal el nombre, te falta una s

* **Mario E Fernandez  Serrano** (2)

	
	Hola, lo que no me funciona es lo del cambio de avatar del usuario no encuentro porque no aparece el avatar del usuario al iniciar sección. alguna ayuda por acá les agradezco

	* **Daniel Esteves** (1)

		
		Puedes hacer un `console.log()` de las propiedades del usuario a ver si en efecto el usuario actual tiene un avatar y de que forma está escrito

* **joseadrian** (2)

	
	Que arquitectura, framework estás utilizando en este proyecto, entiendo que es html, js pero el estilo del codigo es limpio y claro, bastante estructurado y me interesa aprenderlo 😄

	* **Edward Steven Ramos Palacios** (1)

		
		De seguro será [standard.js](https://standardjs.com/)

	* **Edward Steven Ramos Palacios** (1)

		
		De seguro será [standard.js](https://standardjs.com/)

	* **Daniel Esteves** (1)

		
		Es código de HTML, CSS y JS compilado con Webpack 🙌

* **joseadrian** (2)

	
	Oh, ahi es donde se valida que se haya verificado…

* **David Isaac Flores Medrano** (2)

	
	A mi me est’a funcionando casi todo excepto lo del mensaje de bievenida. en la consola de dice que Materialize no es una funcion pero si esta agregada en el index.html. No tebgo idea porque no me sale el mensaje de Bienvenida ni el otro cuadno cierras sesi’on. A alguien le pasa lo mismo?

	* **ebar0n (Platzi)** (1)

		
		Hola, puedes poner parte de tu codigo para ver como lo estas haciendo?

	* **David Isaac Flores Medrano** (1)

		
		En el archivo general tengo asi, te pongo solo las partes del curso para que no se haga largo esto…
		``` 
		    // Init Firebase nuevamente
		      firebase.initializeApp(varConfig);
		    
		    
		      $('#avatar').click(() => {
		        firebase.auth().signOut()
		          .then( () => {
		            $('#avatar').attr('src', 'imagenes/usuario.png')
		            Materialize.toast(`SignOut correcto`, 4000)
		          })
		          .catch( error => {
		            Materialize.toast(`Error al realizar SignOut ${error}`, 4000)
		          })
		      })
		    
		```
		
		En el archivo de autenticacion.js
		``` 
		    class Autenticacion {
		      autEmailPass (email, password) {
		        firebase.auth().signInWithEmailAndPassword(email, password)
		          .then(result => {
		            if(result.user.emailVerified) {
		              $('#avatar').attr('src', 'imagenes/usuario_auth.png')
		              Materialize.toast(`Bienvenido ${result.user.displayName}`, 5000)
		            }else {
		              firebase.auth().signOut()
		              Materialize.toast(`Por favor realiza la verificacion de la cuenta`, 5000)
		            }
		          })
		          $('.modal').modal('close')
		      }
		    
		      crearCuentaEmailPass (email, password, nombres) {
		        firebase.auth().createUserWithEmailAndPassword(email, password)
		          .then(result => {
		            result.user.updateProfile({
		              displayName: nombres
		            })
		    
		            const configuracion = {
		              url: 'http://localhost:3000/'
		            }
		    
		            result.user.sendEmailVerification(configuracion)
		              .catch(error => {
		                console.error(error)
		                Materialize.toast(error.message, 4000)
		              })
		    
		              firebase.auth().signOut()
		    
		              Materialize.toast(
		                `Bienvenido ${nombres}, debes realizar el proceso de verificación`,
		                4000
		              )
		    
		              $('.modal').modal('close')
		          })
		          .catch(error => {
		            console.error(error)
		            Materialize.toast(error.message, 4000)
		          })
		        
		      }
		    
		```
		
		En el archivo authController.js
		``` 
		        $("#btnInicioEmail").click(() => {
		            const email = $('#emailSesion').val();
		            const password = $('#passwordSesion').val();
		            // TODO : LLamar auth cuenta con email
		            const auth = new Autenticacion()
		            auth.autEmailPass(email, password)
		        });
		    
		```

	* **Daniel Esteves** (1)

		
		¡Hola! Ese error te lo da porque no está detectando la librería Materialize para generar estas notificaciones flotantes, recuerda que Materialize es un framework CSS/JS para construir páginas a nivel de frontend

* **Marcos Galaviz** (2)

	
	Buen dia, ¿realmente es necesario tener tantos archivos de javascript?:  
	general.js , autenticacion.js , authController.js ¿no seria mas practico uno solo para no andar de archivo en archivo? o ¿cual es la ventaja de manejarlo asi?
	
	Gracias por sus comentarios.

	* **adhamgatriff** (3)

		
		hola marcos, cada programador maneja una manera propia de estructurar sus proyectos, se recomienda siempre tener separado el archivo donde estan tus credenciales (privadas) o key de firebase para no subirlo a tu repositorio y exponerlos al publico en general.  
		El orden de tus carpetas queda a tu criterio, siempre ten presente la legibilidad de tu codigo empezando por el orden de tus carpetas

	* **jesusmurf** (1)

		
		La pregunta es, por que quieres tener todo en un solo archivo con muchísimas lineas de código difícil de mantener?

	* **tinguinito** (2)

		
		Es una buena practica mantener la lógica en varios archivos para la legilibibidad y escalabilidad del proyecto. Es a criterio tambien.

	* **Wilson Marino Pablo Mendez** (1)

		
		Es de buena practica y tambien para la escalabilidad

* **Andres Leon** (2)
me sale este error domain not whitelisted by project que podra ser?

	* **jggomezt** (1)

		
		el dominio que usas no esta registrada en el proyecto de firebase, debes estar usando un proyecto que no es el tuyo

* **Ivan Aguilar Huelitl** (1)

	
	Se dieron cuenta que al hacer click nuevamente sobre la imagen para hacer el SignOut del usuario les sigue apareciendo que fue correcto?  
	Les dejo el codigo que agregue para que verifique si hay algun usuario y envie otro mensaje si no lo hubiera
	``` 
	    <$('#avatar').click(() => {
	            //$('#avatar').attr('src', 'imagenes/usuario.png')
	            var user = firebase.auth().currentUser
	            
	            if (!user) {
	                Materialize.toast('Tienes que iniciar sesion',5000)
	            } else {
	                firebase.auth().signOut()
	                .then(() => {
	                    $('#avatar').attr('src', 'imagenes/usuario.png')
	                    Materialize.toast('SignOut correcto', 4000)
	                })
	                .catch(error => {
	                    Materialize.toast(`Error al realizar SignOut ${error}`)
	                })
	            }
	            
	        })>
	    
	```

* **Pablo Victor Vargas** (1)

	
	A los que al hacer ‘click’ en el boton de iniciar sesion, no les aparece el modal, me podrian decir como lo solucionaron?

	* **Pablo Victor Vargas** (1)

		
		ya encontre mi erros

* **Ezequiel Ciccioli** (1)

	
	como se sabe si el usuario o la contraseña es incorrecta?  
	se captura con .catch()? y si es asi… es el único error que devuelve la promesa de signInWithEmailAndPassword()?

	* **Fabian Avila** (2)

		
		En el catch te devuelve un objeto con las propiedades _code_ y _message_. El codigo para contraseña incorrecta es: **auth/wrong-password** , puedes ver mas detalles en la  
		[Documentación de firebase](https://firebase.google.com/docs/reference/js/firebase.auth.Auth)

* **Hugo Reyes Casanova** (1)

	
	No me aparece el modal para ingresar el correo electrónico 😦

* **devops** (1)

	
	puedes compartir el proyecto que tienes hasta donde has avanzado porfa?

* **jesus-olivares661** (1)

	
	por casualidad eres familia de Christian…?

* **dipacata** (1)

	
	Me aparecio el mensaje de bienvenida, ademas el usuario quedo creado en la consola, solo que despues del mensaje de bienvenidad me salio el error:
	``` 
	    auth/internal-error
	    autenticacion.js:27 {"error":{"code":500,"message":"Internal error encountered.","errors":[{"message":"Internal error encountered.","domain":"global","reason":"backendError"}],"status":"INTERNAL"}}```
	    
	    enla url yo coloque mi ruta en el disco duro, nose si sea eso
	```

	* **lsolares** (2)

		
		En efecto lo que debes hacer es iniciarlo en un servidor local con localhost, recuerda que en la consola de firebase tenemos permitido unicamente al dominio localhost

* **santossoffli** (1)

	
	No me envia el email de verificación, aunque si guarda el user en la consola, que podra ser?

	* **santossoffli** (2)

		
		cuando sale el toast de verificar con email, tmb sale otro toast que dice: Missing domain in continue url

	* **Mariangelica Useche Saavedra** (2)

		
		Al parecer hay un error en la configuración que estás enviando (el link que el usuario seguirá luego de verificar su email).
		
		Recuerda que autenticar y enviar correo de verificación son tareas diferentes: cuando la primera sucede con éxito, la segunda pudo haber tenido un error, por lo que no se envió el correo, pero sí se creó el usuario. Es importante captar el error y volver a intentar mandar el correo de verificación.
		
		Espero haberme explicado. Saludos.

	* **Jose Padron (Platzi)** (2)

		
		a mi no me funcionaba porque me falto escribir el http:// en el url de configuracion

	* **Andres Leon** (3)

		
		en el proyecto>public>js>auth>autenticacion.js>
		
		metodo -> crearCuentaEmailPass
		
		const configuracion = {  
		url: ‘<http://localhost:5500/>’  
		}
		
		se debe colocar localhost y el puerto.
		
		porque ?, dado que en las configuraciones de firebase en  
		Desarrolla>Autenticacion>MetodoDeAcceso
		
		en la parte de **dominios autorizados** localhost es el que tiene permisos…

	* **Carlos Ignacio Gumucio Labbé** (1)

		
		Yo tenia el mismo error, lo solucione revisando todos los pasos y siguiendo lo que dice @andresleonac8c1d3aa3e2416b,

* **LITIGAR PUNTO COM SA** (1)

	
	En el minuto 12.40 dice que no se puede modificar el contenido del correo de verificación, pero debajo de verificación de sms en la carpeta de plantillas uno puede seleccionar el idioma.! !

	* **LITIGAR PUNTO COM SA** (1)

		
		Ver opcion de cambio de idioma en el min 14

* **David Farinango** (1)

	
	Una preguntilla, estoy haciendo este código en React, como puedo cambiar la imagen del avatar ya que utilizando componentes no puedo llamar mediante un document.getElementById(‘avatar’) usando javascript, este es mi código para hacer el SignIn
	``` 
	     onSubmit = event =>{
	            const {email, password} = this.state;
	            var avatar = document.getElementById('avatar')
	            this.props.firebase
	                .doSignInWithEmailAndPassword(email, password)
	                .then((authUser)=>{
	                    if(authUser.user.emailVerified){
	                        this.setState({ ...INITIAL_STATE });
	                        this.props.history.push(ROUTES.HOME);
	                        alert('Bienvenido a Weygo')
	                        avatar.attr('src', './weygo/imagenes/others/carrito.PNG')
	                    }else{
	                        this.props.firebase.doSignOut();
	                        alert('Por favor realiza el proceso de verificación de la cuenta')
	                        this.props.history.push(ROUTES.HOME);
	                    }
	                })
	                .catch(error => {
	                    this.setState({error});
	                });
	            event.preventDefault();
	        };
	    
	```
	
	Nota: el SignIn lo realiza correctamente con este código, lo único que no puedo hacer es cambiar la imagen del avatar, puesto que tengo la imagen puesta en otro componente llamado Header, mi pregunta sería como puedo cambiar el atributo src de <img id=‘avatar’ src ="./weygo/imagenes/users/usuario.png" /> ya que con document.getElementById desde el componente SignIn no funciona 😦

	* **Angel Hernandez** (1)

		
		Hola 😄 primero que nada asegúrate que la imagen de encuentra en esa ruta y que es accesible desde el navegador
		
		Segundo, prueba usando la función setAttribute, creo que attr es de jQuery.
		
		Finalmente, si no funciona la segunda opción, prueba pasando directamente el src sin inicial izar avatar, algo así:o
		``` 
		    document.getElementById('avatar').setAttribute('src', 'imagen') 
		    
		```

* **dcortesnet** (1)

	
	error “code”: “auth/wrong-password”,  
	“message”: “The password is invalid or the user does not have a password.”

	* **Esteban Ciudad** (1)

		
		este error se genera cuando el usuario o la contraseña son incorrectos.

* **fabricastaneda** (1)

	
	No me funcionan los botones de iniciar sesion y registrarse ! xq puede ser? gracias urgente!

	* **jggomezt** (2)

		
		Hola, revisa si tienes un evento asociado a los botones en el archivo de app.js
		
		$(’#btnInicioSesion’).click(() => {

	* **fabricastaneda** (1)

		
		Hola @jggomezt . tengo esto en el archivo general.js
		
		// TODO: Evento boton inicio sesion  
		$(’#btnInicioSesion’).click(() => {  
		//$(’#avatar’).attr(‘src’, ‘imagenes/usuario.png’)  
		// Materialize.toast(`Error al realizar SignOut => ${error}`, 4000)
		
		esta comentado lo de adentro de esa funcion, lo descomento? GRACIAS

	* **fabricastaneda** (1)

		
		No hay casoo… descomente lo que te dije, y ahora hago click en el boton verde de iniciar sesion y no hace nada. Si dejo todo como estaba antes, el boton verde anda, pero vuelvo a lo mismo, cuando cargo mis datos y click en registrarse, no hace nada,

	* **fabricastaneda** (1)

		
		Es raro porque el html casi ni se toca, yyo solo segui todo lo que decia el profesor en el video

* **fabricastaneda** (1)

	
	Gente, cuando apreto el boton de registrarse, despues de llenar mis datos, no hace nada, queda la ventana modal de inicio de sesion y registro. apreto el boton, y no reacciona, Alguien sabe como ayudarme? gracias!! porque si no no puedo seeguir adelante

* **fabricastaneda** (1)

	
	No me anda el botón de Iniciar Sesión, apreto y no hace nada. Seguí la clase tal cual…

	* **fabricastaneda** (1)

		
		Listo, borré caché y funcionó.

* **Sergio Minei** (1)

	
	No hay forma de por lo menos mostrar el mensaje de verificación en español?

	* **Jose Rueda** (1)

		
		Si la hay… en la pestaña de Plantillas dentro de la seccion de autenticacion de firebase puedes configurar la plantilla del correo como quieras

	* **jggomezt** (2)

		
		Hola, el texto no es posible cambiar, pero si es posible el idioma. En la parte inferior izquierda hay algo que dice idioma de la plantilla

	* **Sergio Minei** (2)

		
		Genial! muchas gracias @jggomezt 😄

* **Jesus Ricardo Moreira Cedeño** (1)

	
	Nice

* **Sergio David Paez Suarez** (1)
¿Hay alguna manera de guardar información extra de los usuarios con autenticación?, por que uso el método updateProfile(), pero parece qu...

	* **davidsc34** (1)

		
		Hola creo que en esos casos lo que se me ocurre es hacer una coleccion usuarios y los documentos con los campos que necesites.  
		Por que por ejemplo, estaba pensando en algo asi pero para decir que perfil tiene de un sistem, admin, lector, suscriptor…etc

* **Jesus Castañon** (1)
Puedo hacer login con username que no sea email?

	* **omejenes** (1)

		
		si puedes

* **Juan Camilo Serna** (1)
En el minuto 13:00 en la opción de plantillas se detalla que se solo se puede cambiar el asunto del correo electrónico y el mensaje prede...

	* **Juan David Castro (Platzi)** (1)

		
		Aunque está orientado más bien al **Curso de Firebase Cloud Functions** , creo que tal vez este tutorial puede ayudarte: <https://softauthor.com/firebase-functions-send-email>. 😉

* **dennis velez** (1)
Si me cambio de página (otro HTML) ¿como puedo mantener al usuario autenticado?

	* **Juan David Castro (Platzi)** (1)

		
		Este tutorial te puede ayudar: <https://www.robinwieruch.de/react-firebase-auth-persistence>. 😉

* **devops** (1)
me salen todos estos erroreS?

* **Enrique Devars (Platzi)** (1)
¿Cuando se autentica sesión en donde se guarda la sesión?

	* **Juan David Castro (Platzi)** (1)

		
		Puedes encontrar la información de la sesión de tus usuarios desde el navegador entrando a **`Inspector de Elementos> Application > IndexedDB > firebaseLocalStorageDb`**.
		
		Se verá algo así:
		
		![Firebase Token](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-12-10%20at%209.21.25%20AM-85f1d010-d97f-4f29-aa5c-7ec91e104a1a.jpg)

* **Pamela Cinthya Torres Gutiérrez** (1)
hola al momento de crear un usuario la función del botón crear no me acciona nada y al abrir la consola me marca error en las siguientes ...

	* **osmandi (Platzi)** (1)

		
		Hola Pamela, por favor sube tu código a GitHub o GitLab para poder detallarlo y saber la causa del error.

* **santossoffli** (1)
No me envia el email de verificación, aunque si guarda el user en la consola, que podra ser?

	* **santossoffli** (2)

		
		cuando sale el toast de verificar con email, tmb sale otro toast que dice: Missing domain in continue url

* **Adriana  Ramos Ortiz** (0)
En vez del avatar, cómo podría hacerle para cambiar por un texto. O sea que al momento de iniciar sesión en vez del avatar sea el nombre ...

## 0090. Servicios de atenticación con google

### Descripción:


Cuando añadimos autenticación con Google Accounts _(o cualquier otra red social soportada por Firebase)_ el proceso de registro/inicio de sesión es un poco diferente: en vez de llenar un formulario y esperar un correo electrónico vamos a abrir una nueva ventana del navegador para llenar los datos que nos piden estas cuentas, así que, vamos a utilizar el método `signInWithPopup()` definiendo anteriormente el proveedor que necesitamos.

### Comentarios:

* **johnflorez** (6)

	
	Práctico y sencillo el proceso de autentificación con google

	* **alejandropazperez** (1)

		
		Concuerdo contigo.

	* **Luis Rangel Castro** (1)

		
		que bonito es lo bonito!

* **Pamela Cinthya Torres Gutiérrez** (3)

	
	Muy buena clase, pero no me corre la app, ya cheque el código en varias ocasiones pero tengo problemas

	* **Daniel Esteves** (1)

		
		¿Podrías darnos las capturas de los errores que te suceden al usar la aplicación?

* **Sebastian Cardoso Castillo** (3)

	
	Cuando abrimos la app en un celular creo que se ve mejor el redireccionamiento para la autenticación. Después en pantallas de escritorio ahí si los Popups.

* **DidierMatos** (2)

	
	hola alguien podría orientarme con esta parte? me da el siguiente error al querrer autentifcarme con gloolge:
	``` 
	    lo {code: "auth/unauthorized-domain", message: "This domain (127.0.0.1) is not authorized to run t…se console -> Auth section -> Sign in method tab."}
	    
	```
	
	por cierto trabajo con el web server from chrome

	* **carlos-samuel-hernandez** (2)

		
		Hola, a mí también me dio ese error. Simplemente debes cambiar la dirección IP local a “localhost”. Un saludo

* **Wilson Marino Pablo Mendez** (2)

	
	Por ahora todo bien. Excelente curso

* **David Farinango** (2)

	
	Tengo un problema, una vez hago la autenticación con google, y despues hago el SignOut, como puedo hacer para que se borren las credenciales ya ingresadas anteriormente, ya que se queda grabado en memoria y ya al abrir la ventana emergente inmediatamente me hace el SignIn, sin pedirme la contraseña ni nada, ya ingresa de una con mis credenciales a pesar de que ya hice el signOut previamente!

	* **Edward Steven Ramos Palacios** (1)

		
		Tienes que validar si efectivamente el signOut se esta haciendo. Y tambien deberias ver si es talvez un problema de tu aplicacion al hacer el signIn. Revisa que valores esta tomando esa funcion del sigin.

* **ddragaid** (1)

	
	que genail es firebase

* **Jessie Buckland Pérez** (1)

	
	 **NOTA IMPORTANTE** : a los que usen navegadores nuevos como **BRAVE** , este ejemplo del popup no les funcionará, sin embargo si usan **CHROME **podrán seguir tranquilamente con el ejemplo.

* **carlosbazanhuaman** (1)

	
	muy claro la explicación pero el ejemplo se me queda a medias

* **Pamela Cinthya Torres Gutiérrez** (1)

	
	Alguien podría ayudarme me marca error al momento de realizar la prueba. me aparece de la siguiente manera.
	
	![error con logeo-Google.jpg](https://static.platzi.com/media/user_upload/error%20con%20logeo-Google-efa7bcbb-eb54-45ce-9fd6-29d32013ecdc.jpg) ![error al ahcer prueba de logeo con google.jpg](https://static.platzi.com/media/user_upload/error%20al%20ahcer%20prueba%20de%20logeo%20con%20google-c3ea7b7a-66c6-4a89-8704-482c26adaa63.jpg)

	* **Luigui Mario** (1)

		
		En autentication.js y en la función authCuentaGoogle quite los parentesis a auth, de la siguiente manera:
		``` 
		     authCuentaGoogle () {
		        const provider = new firebase.auth.GoogleAuthProvider()
		    
		```

* **José Colmenares** (1)

	
	Listo implementado en algunos proyectos personales en Firebase

* **Daniela Gonzales** (1)

	
	actualmente ya no permite usar localhost como dominio en google y fb, como se puede solucionar eso?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Hola puedes usar un programa que te permite hacer un tunnel una opción puede ser <https://ngrok.com/> este lo ejecutas y crea una url que puedes poner en FB o Google, cada vez que cierres e inicies ngrok te genera una nueva url que debes configurar en estos dos servicios.

	* **john fredy quimbaya orozco** (1)

		
		tengo e mismo problema como se puede solucionar

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		@johnfredyquimbayaorozco probaste con ngrok?

	* **Carolina Londoño** (1)

		
		puedes utilizar en la consola el comando http-server para especificar el puerto puesto en la clase:
		``` 
		    http-server . -p3000 
		    
		```

	* **Josseline Acosta** (1)

		
		Tengo el mismo problema, lo pudiste solucionar?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		@majoacosta puedes probar usando ngrok o localtunel para hacer las pruebas que necesitas.

* **Jericsson Jesus Carvajal Guerrero** (1)
Alguien sabe cómo instalar el skin de fuego que le aparece al profesor en visual code?

	* **Davidalvarado08** (2)

		
		es una extension de visual studio code, se llama Power Mode

* **Pamela Cinthya Torres Gutiérrez** (1)
buenas noches me podrian ayudar con estos inconvenientes, ya revise mis lineas de código con las del ejercicio y están igual pero al corr...

	* **Pamela Cinthya Torres Gutiérrez** (1)

		
		perdón la imagen 3 no se ve bien, la pongo nuevamente, espero me puedan ayudar
		
		![problemas con el registro y autenticación con google-3.png](https://static.platzi.com/media/user_upload/problemas%20con%20el%20registro%20y%20autenticaci%C3%B3n%20con%20google-3-e7e35b06-bca7-44c2-af69-6552dc540fd7.jpg)

* **Andres Leon** (1)
deberían hacer un paso a paso para solucionar el error…

	* **Manuel Ojeda** (1)

		
		Hola Andres, puedes enviar tu observación al team a su correo: [team@platzi.com](mailto:team@platzi.com)
		
		Los comentarios y sugerencias se agradecen 👌

* **Mario E Fernandez  Serrano** (1)
Hola cundo me autentico con Google me arroja una ventana que dice esté erro … That’s an error. Error: restricted_clie...

* **Vittorio Carlos Toledo Huarez** (1)
Hola Buenas Tardes. Una consulta, cuando intento autenticarme con google me sale este aviso. Me dice que esta aplicación aún no está conf...

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Hola, vas a esta dirección <https://console.cloud.google.com/> luego haces login con tu cuenta de gmail y con esto ya accedes, luego puedes crear una aplicación y la configuras para acceso a oAuth.  
		aquí tienes los pasos en la documentación oficial <https://support.google.com/cloud/answer/6158849?hl=en>

* **David Farinango** (1)
Tengo un problema, una vez hago la autenticación con google, y despues hago el SignOut, como puedo hacer para que se borren las credencia...

	* **Edward Steven Ramos Palacios** (1)

		
		Tienes que validar si efectivamente el signOut se esta haciendo. Y tambien deberias ver si es talvez un problema de tu aplicacion al hacer el signIn. Revisa que valores esta tomando esa funcion del sigin.

## 0100. Firebase Web Login con Facebook

### Descripción:


Firebase el Backend as a Service de Google hace muy sencillo integrar a tus aplicaciones web login con Facebook. Habilita tú aplicación en la consola de Facebook Developers, maneja tokens de acceso y entiende todo el flujo de inicio de sesión usando el SDK de Firebase.

### Comentarios:

* **joseadrian** (7)

	
	esas laptops ya las venden estampadas? son igualitas

	* **Yassr** (1)

		
		Yo creo que modificaron el color digitalmente

* **Wilson Marino Pablo Mendez** (2)

	
	Pueden usar la **consola del navegar** para ver los posibles problemas.
	
	Excelente curso!!  
	Autenticación google ✔  
	Autenticación Facebook ✔

	* **Pamela Cinthya Torres Gutiérrez** (1)

		
		buenas noches Mariano angtes que nada felicidades por completar estos pasos.
		
		Un favor yo realice la autenticación con google y facebook pero me marca ciertos errores, te comparto mi repo en git y githubpages para ver si me puedes apoyar e indicar en donde me equivoque.
		
		<https://github.com/Pamela-C-Torres-Gtz/MEX008-social-network>
		
		<https://pamela-c-torres-gtz.github.io/MEX008-social-network/src/index.html>
		
		Muchas gracias

* **Pamela Cinthya Torres Gutiérrez** (2)

	
	Buenos días un favor muy grande aún no logro autenticarme con email, Google, Facebook, ya he revisado en varias ocasiones y el código esta correcto. solo que cuando reviso en la consola me sigue marcando error aquí:
	
	.catch(err => {  
	_ console.error(error)_ --> Esto en mi código lo tengo como comentario  
	** console.error(err)** indicando que esta indefinido  
	Materialize.toast(Error al autenticarse con Facebook: ${err}, 4000)  
	})
	
	Les comento que cambien un poco el código por que la forma en que nos enseñaron me marcaba más errores(que es la que esta en comentario)

	* **Jorge Enríquez** (1)

		
		** no es para hacer comentarios en js, para eso tienes:
		``` 
		    //comentario de una línea
		    
		```
		
		o bien
		``` 
		    /*comentario de
		    varias líneas*/
		    
		```
		
		También, dentro de los parámetros de Materialize.toast, el string no lo pasas entre cadenas (como cualquier otro string) y al no ir entre cadenas es interpretado como una variable (incluso con espacios en blanco) y eso te da error al no estar definida. Prueba a poner:
		``` 
		    Materialize.toast(´Error al autenticarse con Facebook: ${err}´, 4000)
		    
		```

* **gydoar** (2)

	
	Creo que a todo el curso le falto explicar todo el HTML de como funciona.

	* **Andrés Felipe Chaparro Grimaldo** (9)

		
		Pero ese no es el punto central del curso, si se pone a explicar todo el HTML y Js, que hacen y como funciona, el curso pierde su esencia. Para entender bien html, css3, js están otros cursos dedicados para este fin, que ayudan en su totalidad a seguir el curso

	* **Sebastian Cardoso Castillo** (1)

		
		Para este curso en necesario saber esos temas.

	* **Daniel Esteves** (3)

		
		¡Hola Andrés! En el curso se utiliza una plantilla base ya que nos enfocamos netamente en crear la funcionalidad de Firebase con nuestro website, si aún no sabes HTML, CSS o JavaScript te invito a que sigas estos cursos para que tus conocimientos en esta área aumenten mucho más 👇:
		
		  * [Curso de HTML y CSS](https://platzi.com/clases/html-css/) 🖥
		  * [Curso de Desarrollo Web Online](https://platzi.com/clases/html5-css3/) 💻
		  * [Curso de Responsive Design](https://platzi.com/clases/responsive-design/) 📱
		  * [Fundamentos de JavaScript](https://platzi.com/clases/fundamentos-javascript/) 🖱
		
		

* **Brian Bentancourt** (2)

	
	con la aplicacion de invie solicite la autorizacion por twitter para utilizar la autenticacion y nunca la aprobaron. a lo mejor estoy haciendo algo mal?

	* **jggomezt** (2)

		
		Hola, me puedes contar cual fue el proceso que hiciste?? para la autenticación con twitter tienes que ir a (<https://developer.twitter.com/>) y crear una app, y en la consola del proyecto tienes los datos para colocar en firebase

	* **Daniel Esteves** (1)

		
		Como comenta el profesor por favor dirígete a [Twitter Developer](https://developer.twitter.com/) y crea la aplicación (no se te será rechazada) e instantaneamente se te darán las credenciales de uso necesarias para el Twitter Login 💪

* **Kevin Jeremy Salazar Jimenez** (2)
ayuda! al iniciar sesion con facebook me sale Facebook has detected MyApp isn’t using a secure connection to transfer information. Until ...

* **Ivan Aguilar Huelitl** (1)

	
	Para los que tienen problemas con firefox y el error “he popup has been closed by the user before finalizing the operation” es debido a una extension en mi caso que bloquea el seguimiento por parte de facebook, solo hay que desistalarlo o desactivarlo y permitirá el inicio automatico con fb

* **davidsc34** (1)

	
	perdon olvide la parte donde tiene que agregar los dominio de la app de prueba asi, img : <https://prnt.sc/rjxs7d>  
	![https://prnt.sc/rjxs7d](https://prnt.sc/rjxs7d)

* **davidsc34** (1)

	
	Hola amigos siguiendo el link de ValdDark, para crear una app de prueba de la original que creamos, segui la info del link: <https://stackoverflow.com/questions/39800216/working-with-facebook-login-from-localhost>  
	1.- Cree la app de prueba url de la img: <https://prnt.sc/rjxn93>  
	2.- Colocar los datos a esta app de prueba los mismos que la original , la url de reedireccino esta en su consola de firebase, link de img : <https://prnt.sc/rjxo4x>  
	3.- Colocar los datos de la app de prueba en la consola de firebase en la parte de login con facebook asi; link img : <https://prnt.sc/rjxoo4>
	
	Espero les sirva. Saludos

* **darwin1111** (1)

	
	carga sin problemas gamil pero facebook nada ni el error

* **Jeffersson Muñoz Torres** (1)

	
	Al parecer hay un problema con la carga de este video. @teamplatzi

* **VladDark** (1)

	
	Estimadas y estimados, respecto a lo del problema con localhost y el https, he visto el siguiente link en stackoverflow: <https://stackoverflow.com/questions/39800216/working-with-facebook-login-from-localhost>
	
	Busquen la respuesta de “Dagmar” sobre crear una “test app”. Así he logrado que me funcionara a mi con localhost

* **David Trespalacios** (1)

	
	Al día de hoy Enero 2020, no permite login sin https, alguna idea de como hacer pruebas en fase de desarrollo?  
	![](https://i.ibb.co/fNHmP8d/error-inicio-con-FB.png)

	* **VladDark** (1)

		
		Quizá este post te ayude: <https://stackoverflow.com/questions/39800216/working-with-facebook-login-from-localhost>  
		Busca la respuesta de “Dagmar” sobre “Test app”.  
		Saludos y espero te funcione 😉

* **Kevin Jeremy Salazar Jimenez** (1)

	
	nice

* **José Colmenares** (1)

	
	Buena clase !

* **Mario E Fernandez  Serrano** (1)

	
	Hola, no logra autenticarme ni con Google, ni con Facebook, logro entender por que si todo el codigo esta ok. ayuda . por . favorrrrr  
	. .(

	* **Andres Leon** (3)

		
		puede ser la direccion URL en donde esta corriendo el proyecto  
		correcto -> <http://localhost:5500/public/index.html#>  
		incorrecto -> <http://127.0.0.1:5500/public/index.html#>
		
		dado que en la configuración de firebase y google cloud tiene permisos localhost para esta autenticacion “deberia funcionar con,los dos pero no es asi” Espero sea de ayuda.

	* **Carolina Londoño** (2)

		
		Ademas de lo que menciona el companero,  
		puedes utilizar en la consola, estando en la carpeta public del proyecto, el comando http-server para especificar el puerto del server:
		
		`http-server . -p 3000`
		
		(puerto 3000 que fue el que registramos en la web de la consola de firebase)  
		Una vez tengas el servidor corriendo en consola puedes entrar a  
		<http://localhost:3000/>  
		Espero te sirva 😄

* **Disando7** (1)

	
	Qué tan bueno es desarrollar una página grande en Firebase?, o es para proyectos sencillos?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		El problema que yo veo es el costo económico de usar Firebase, a pequeña escalar no es costoso pero cuando un sitio web tiene mucho tráfico y uso de la base de datos los costos pueden ser muy altos.

* **Alejandro González Reyes** (1)

	
	Comentas que facebook clasifica las cuentas que van a tener autorización para acceder a la App.  
	Si la App se pone en producción que se debe hacer para que cualquiera pueda logearse desde su cuenta de Facebook?

	* **aragonesteban (Platzi)** (3)

		
		Hola, lo único que debes hacer es poner el la URL de la aplicación web en el Dashboard Developer de Facebook y ya funcionaría el logueo con FB en tu aplicación web.

* **Aaron Felipe Isaacs** (1)
Me funcionó correctamente el inicio de sessión con Google y con Facebook. Sin embargo, en Firebase tuve que habilitar una opción para per...

	* **Juan David Castro (Platzi)** (2)

		
		¡Hola! Tengo el tutorial perfecto para ti:
		
		👉 [How to link Social Logins with Firebase in React](https://www.robinwieruch.de/react-firebase-link-social-logins)

* **Alejandro González Reyes** (1)
Comentas que facebook clasifica las cuentas que van a tener autorización para acceder a la App. Si la App se pone en producción que se de...

	* **aragonesteban (Platzi)** (3)

		
		Hola, lo único que debes hacer es poner el la URL de la aplicación web en el Dashboard Developer de Facebook y ya funcionaría el logueo con FB en tu aplicación web.

* **Brian Bentancourt** (1)
con la aplicacion de invie solicite la autorizacion por twitter para utilizar la autenticacion y nunca la aprobaron. a lo mejor estoy hac...

	* **jggomezt** (2)

		
		Hola, me puedes contar cual fue el proceso que hiciste?? para la autenticación con twitter tienes que ir a (<https://developer.twitter.com/>) y crear una app, y en la consola del proyecto tienes los datos para colocar en firebase

* **Ulises** (0)

	
	Tengo un gran problema, no me despliega el div para iniciar sesión, he realizado todo al pie de la letra hasta el video anterior (Autenticación con Google).  
	Si alguien me pudiera apoyar se lo agradecería mucho!

## 0110. Gestionando el estado del usuario

### Descripción:


Firebase nos permite controlar nuestra aplicación dependiendo de los cambios en la autenticación de los usuarios con el método `onAuthStateChanged()`, nuestro trabajo es añadir el código necesario para cambiar los textos de nuestra aplicación dependiendo de si el usuario esta autenticado o no.

### Links:

* [Manage Users in Firebase  |  Firebase](https://firebase.google.com/docs/auth/web/manage-users)

### Comentarios:

* **Juan David Castro (Platzi)** (9)

	
	Cuando utilizamos Firebase con React.js utilizamos el método `onAuthStateChanged()` de Firebase en el método `componentDidMount` de React, así aceleramos el render inicial de la aplicación y evitamos problemas de Server Side Rendering 😉.

	* **Juan David Castro (Platzi)** (1)

		
		  * si utilizamos componentes funcionales con los Hooks, pues, utilizamos los Hooks, ya esta 😬… 😄
		
		

	* **ferroblesh** (11)

		
		Estaría genial un curso de firebase + react

	* **jasanhdz** (1)

		
		Exactamente! 😃

	* **Manuel Aguilera Magaña** (1)

		
		me fué util, gracias!

* **guillermoochoa** (2)

	
	Tengo una duda no se si estoy ingresando mal a crear la App en twitter,pero creo esta cambio sus políticas y tarda mas tiempo para dar acceso a crear una nueva app.

* **juan david  jaramillo zuñiga** (2)

	
	como se hace para saber que un usuario esta haciendo signing in por primera vez cuando la autenticación es con email y contraseña?

	* **AndrsDev** (1)

		
		Bueno, en teoría el primer sign-in sería siempre creando una cuenta. Podrías utilizarlo para activar una bandera en tu código y así saber que es su primera autenticación ya sea con credenciales, google o facebook

	* **Sebastian Cardoso Castillo** (1)

		```
		    const provider = new fb.auth.GoogleAuthProvider()
		    fb.auth().signInWithPopup(provider)
		        .then((res) => {
		          console.log(res)
		    }
		    
		```
		
		La respuesta es un objeto que tiene una propiedad _aditionalUserInfo_ con otra prop adentro llamada _newUser: Boolean_

	* **Sebastian Cardoso Castillo** (3)

		```
		     const provider = new fb.auth.GoogleAuthProvider()
		    fb.auth().signInWithPopup(provider)
		        .then((res) => {
		          console.log(res)
		    }
		    
		```
		
		La respuesta que te da firebase.auth().currentUser es un objeto que tiene una propiedad aditionalUserInfo, dentro otra propiedad llamada newUser: ‘Boolean’

* **Luis Rangel Castro** (1)

	
	autenticacion.js
	``` 
	    class Autenticacion {
	      autEmailPass(email, password) {
	        firebase.auth().signInWithEmailAndPassword(email, password)
	          .then(result => {
	            if (result.user.emailVerified) {
	              $('#btnInicioSesion').text('Salir');
	              $('#avatar').attr('src', 'imagenes/usuario_auth.png');
	              Materialize.toast(`Bienvenido ${result.user.displayName}`, 5000);
	            } else {
	              firebase.auth().signOut();
	              Materialize.toast(`Por favor realiza la verificacion de la cuenta ${result.user.displayName}`, 5000);
	            }
	          })
	          .catch(error => {
	            console.error(error);
	            Materialize.toast(error.message, 4000)
	          });
	        $('.modal').modal('close')
	      }
	    
	      crearCuentaEmailPass(email, password, nombres) {
	        firebase.auth().createUserWithEmailAndPassword(email, password)
	          .then(result => {
	            result.user.updateProfile({
	              displayName: nombres
	            });
	    
	            const configuracion = {
	              url: 'http://localhost:3000/'
	            };
	    
	            result.user.sendEmailVerification(configuracion);
	    
	            firebase.auth().signOut();
	    
	            Materialize.toast(
	              `Bienvenido ${nombres}, debes realizar el proceso de verificación`,
	              4000
	            );
	    
	            $('.modal').modal('close');
	          })
	          .catch(error => {
	            console.error(error);
	            Materialize.toast(error.message, 4000);
	          });
	      }
	    
	      authCuentaGoogle() {
	        const provider = new firebase.auth.GoogleAuthProvider();
	    
	        firebase.auth().signInWithPopup(provider)
	          .then(result => {
	            $('#btnInicioSesion').text('Salir');
	            $('#avatar').attr('src', result.user.photoURL);
	            $('.modal').modal('close');
	            Materialize.toast(`Bienvenido ${result.user.displayName} !! `, 4000);
	          })
	          .catch(error => {
	            console.error(error);
	            Materialize.toast(`Error al autenticarse con google: ${error.message}`, 4000);
	          });
	      }
	    
	      authCuentaFacebook() {
	        const provider = new firebase.auth.FacebookAuthProvider();
	    
	        firebase.auth().signInWithPopup(provider)
	          .then(result => {
	            $('#btnInicioSesion').text('Salir');
	            $('#avatar').attr('src', result.user.photoURL);
	            $('.modal').modal('close');
	            Materialize.toast(`Bienvenido ${result.user.displayName} !! `, 4000);
	          })
	          .catch(error => {
	            console.error(error);
	            Materialize.toast(`Error al autenticarse con facebook: ${error.message}`, 4000);
	          });
	      }
	    
	      authCuentaTwitter() {
	        const provider = new firebase.auth.TwitterAuthProvider();
	    
	        firebase.auth().signInWithPopup(provider)
	          .then(result => {
	            $('#btnInicioSesion').text('Salir');
	            $('#avatar').attr('src', result.user.photoURL);
	            $('.modal').modal('close');
	            Materialize.toast(`Bienvenido ${result.user.displayName} !! `, 4000);
	          })
	          .catch(error => {
	            console.error(error);
	            Materialize.toast(`Error al autenticarse con twitter: ${error.message}`, 4000);
	          });
	      }
	    }
	    
	```

* **Luis Rangel Castro** (1)

	
	general.js
	``` 
	    $(() => {
	      $('.tooltipped').tooltip({ delay: 50 })
	      $('.modal').modal()
	    
	      // TODO: Adicionar el service worker
	    
	      // Initialize Firebase
	      firebase.initializeApp(firebaseConfig);
	      // firebase.analytics();
	    
	      // TODO: Registrar LLave publica de messaging
	    
	      // TODO: Solicitar permisos para las notificaciones
	    
	      // TODO: Recibir las notificaciones cuando el usuario esta foreground
	    
	      // TODO: Recibir las notificaciones cuando el usuario esta background
	    
	      // TODO: Listening real time
	    
	      // TODO: Firebase observador del cambio de estado
	      //$('#btnInicioSesion').text('Salir')
	      //$('#avatar').attr('src', user.photoURL)
	      //$('#avatar').attr('src', 'imagenes/usuario_auth.png')
	      //$('#btnInicioSesion').text('Iniciar Sesión')
	      //$('#avatar').attr('src', 'imagenes/usuario.png')
	    
	      // TODO: Evento boton inicio sesion
	      $('#btnInicioSesion').click(() => {
	        iniciarSesion();
	      })
	    
	      $('#avatar').click(() => {
	        const user = firebase.auth().currentUser;
	    
	        if (user) {
	          firebase.auth().signOut()
	            .then(() => {
	              $('#avatar').attr('src', 'imagenes/usuario.png');
	              Materialize.toast(`SignOut correcto`, 4000);
	            })
	            .cath(error => {
	              console.error(error);
	              Materialize.toast(`Error al realizar SignOut ${error}`, 4000);
	            });
	        } else {
	          iniciarSesion();
	        }
	      })
	    
	      $('#btnTodoPost').click(() => {
	        $('#tituloPost').text('Posts de la Comunidad')
	      })
	    
	      $('#btnMisPost').click(() => {
	        //$('#tituloPost').text('Mis Posts')
	        //Materialize.toast(`Debes estar autenticado para ver tus posts`, 4000)    
	      })
	    
	      function iniciarSesion() {
	        const user = firebase.auth().currentUser;
	    
	        if (user) {
	          return firebase.auth().signOut()
	            .then(() => {
	              $('#btnInicioSesion').text('Iniciar Sesión');
	              $('#avatar').attr('src', 'imagenes/usuario.png');
	              Materialize.toast(`SignOut correcto`, 4000);
	            })
	            .cath(error => {
	              console.error(error);
	              Materialize.toast(`Error al realizar SignOut ${error}`, 4000);
	            });
	        }
	    
	        $('#emailSesion').val('');
	        $('#passwordSesion').val('');
	        $('#modalSesion').modal('open');
	      }
	    })
	    
	    
	```

* **dennis velez** (1)
al refrescar la pagina se va la autenticación, hay manera que siga autenticado?

	* **Juan Felipe Peralta Zapata (Platzi)** (2)

		
		¡Hola, @den! ⚡
		
		En la documentación oficial de **Firebase** se habla al respecto, aquí te dejo el enlace directo a la sección de “[persistencia del estado de autenticación](https://firebase.google.com/docs/auth/web/auth-state-persistence?hl=es_419)”.

* **JaimeRamos** (0)

	
	¿Cómo sería para paginas que no se manejan sobre una sola pagina, es decir donde ya no hay navegación?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Hola. Eso es conocido como SPA (Single Page Application) en una SPA si existe navegación lo que no ha realmente es un refresh del navegador, pero los llamados a una API se hacen igual, consultas los datos una vez los recibes actualizas la información en la parte de tu pagina que espera esos datos.

## 0120. Gestión de usuarios

### Descripción:


La sección de autenticación de usuarios en la consola de Firebase nos permite controlar todas nuestras cuentas de forma muy sencilla, podemos inhabilitar y eliminar usuarios, enviar correos electrónicos para cambiar contraseñas y crear plantillas para configurar el envío de emails de nuestra aplicación.

### Comentarios:

* **fernandojavierespanacordoba** (2)

	
	Buenas noches, amigos una pregunta, así como podemos enviar el link de verificación desde el código. ¿existe alguna manera de enviar el link desde la consola de Firebase de manera manual?.

	* **Eduardo Hidalgo Díaz Rugama** (3)

		
		No. Puedes crear un usuario nuevo, y puedes solicitar desde la consola una contraseña nueva via email, pero la verificación que yo sepa no puedes hacerla desde la consola.

	* **José Colmenares** (1)

		
		No amigo no puedes, sin embargo puedes configurar el asunto del correo electrónico que brinda firebase y también puedes crear una pagina personalizada en donde vas a gestionar la confirmación del correo o de la cuenta !

* **Lordpanther** (2)

	
	Una consola simple y elegante 😉

## 0130. Exportación e importación de usuarios

### Descripción:


El desafío de esta clase es crear la funcionalidad de recordar contraseña para nuestra aplicación, si nuestros usuarios olvidan su contraseña deberían hacer click en un nuevo botón personalizado, escribir su email y hacer click en el enlace que vamos a enviar por correo electrónico gracias a Firebase.

### Links:

* [Import Users  |  Firebase](https://firebase.google.com/docs/auth/admin/import-users)

### Comentarios:

* **Jose David Ocaña Ballester** (8)

	
	Envía un correo electrónico de restablecimiento de la contraseña
	``` 
	    resetPasswordByEmail(email) {
	        if (email) {
	          const auth = firebase.auth();
	    
	          const configuracion = {
	            url: "http://localhost:3000/"
	          };
	    
	          auth
	            .sendPasswordResetEmail(email, configuracion)
	            .then(result => {
	              console.log(result);
	              Materialize.toast(
	                `Se ha enviado un correo para reestablecer la contraseña`,
	                4000
	              );
	    
	              $(".modal").modal("close");
	            })
	            .catch(error => {
	              console.log(error);
	              Materialize.toast(error.message, 4000);
	            });
	        } else {
	          Materialize.toast(`Por favor ingrese su correo`, 4000);
	        }
	      }
	    
	```
	
	Documentación de Firebase <https://firebase.google.com/docs/auth/web/manage-users?hl=es-419>

* **Juan David Castro (Platzi)** (7)

	
	Notas de la clase:
	
	  * Podemos importar y exportar la data de nuestros usuarios en archivos JSON y CVS _(información separada por comas)_ 👍 🕹
	  * Necesitamos instalar las [firebase-tools](https://github.com/firebase/firebase-tools) para realizar estos procedimientos 🆗 📦
	  * Firebase sigue las mejores prácticas y reglas de seguridad para almacenar las contraseñas 👌 🎉
	  * El comando para importar datos desde Firebase es: `firebase auth:import` 👈
	  * El comando para export los datos de Firebase es: `firebase export` 👈
	
	

	* **alexanderorellanam** (2)

		
		Existe luego un ejemplo real de exportación de usuarios bajo linea de comandos?

	* **Juan David Castro (Platzi)** (1)

		
		 **@alexanderorellanam** Sí. Cuando queremos migrar los datos de los usuarios a otra base de datos.

	* **alexanderorellanam** (2)

		
		Gracias por tu respuesta, pero sabes si existe un ejemplo o un link donde se pueda observar esa migración? porque lo busque en la documentación y no lo encontré, gracias.

	* **Juan David Castro (Platzi)** (1)

		
		Aquí puedes ver un ejemplo muy pero muy bueno: <https://platzi.com/tutoriales/1299-firebase-web-2017/2745-de-sql-a-firebase-database/>. También tiene recomendaciones de otros tutoriales que se complementan muy bien. 😉

* **Lordpanther** (6)

	
	Eso si deja en claro que firebase es un monstruo ya que no te amarra con cosas como retener tus usuarios.

* **Wedwin53** (3)

	
	El trafico que se genera durante el desarrollo hacia firebase (desde localhost) se cuenta en la cuota del servicio que es gratuito? es decir ese trafico se rebaja de la cuota mensual gratis?

	* **Henry Yerry Bravo Sánchez** (1)

		
		buena pregunta 😮

	* **dipacata** (1)

		
		Creería que si, ya que firebase no mira si es en localhost o no, simplemente ya estás haciendo uso de las herramientas y van sumando.

	* **Daniel Esteves** (1)

		
		Si, el tráfico que reciba esas Keys que usas independientemente de dónde la uses si se cuenta en tu cuota

	* **José Colmenares** (1)

		
		Si no importa desde donde estés enviando peticiones a firebase, todas son descontadas de tu couta mensual.

* **Alejandro González Reyes** (2)

	
	El código funciona correctamente, pero envia tres correos (cuando debería emitir solo uno) a pesar que solo se presiona 1 vez el boton
	``` 
	    recuperarPasswordEmail (email) {
	        // Verificar si se ha indicado un email para proceder a restablecer la contraseña
	        if(email) {
	          console.log(email);
	          // Le indicamos la URL a la que debe redireccionar si el proceso es correcto    
	          const configuracion = {
	            url: 'http://localhost:3000/'
	          }
	          // El metodo sendPasswordResetEmail se encarga de reestableer la contraseña para el email indicado
	          firebase.auth().sendPasswordResetEmail(email, configuracion)
	            .then(() => {
	              // Si la promesa se resuelve, significa que se haenviado el email para restablecer el password
	              //console.log(result)
	              Materialize.toast(`Se ha enviado un correo para reestablecer la contraseña`, 4000)
	              // En esta sección debemos cerrar el modal del formularo de restablecer conraseña
	              $('.modal').modal('close')
	            })
	            .catch(error => {
	              // Si la promesa es rechazada, algo paso
	              console.log(error)
	              Materialize.toast(`Un error a sucedo al enviar el correo de reestablecimiento de contraseña ${error}`, 4000)
	              $('.modal').modal('close')
	            })
	        } else {
	          // Esto sucede a consecuencia de no indicar email para reestablecer la contraseña
	          Materialize.toast(`Favor de ingresar un correo electrónico`)
	          $('.modal').modal('close')
	        }
	      }
	    
	```

	* **Daniel Esteves** (1)

		
		¡Hola! ¿Podrías verificar si tu código es el mismo con el del profesor?

* **Leonardo Daniel Benitez Cuenca** (1)

	```
	    changePasswordEmail(email) {
	        if (email) {
	          const configuracion = {
	            url: 'http://localhost/blogeek-platzi/public/'
	          }
	          firebase.auth().sendPasswordResetEmail(email, configuracion).then((result) => {
	            $('.modal').modal('close')
	            Materialize.toast(`Se ha enviado un correo para restablecer tu contraseña`, 4000)
	          }).catch(error => {
	            console.log(error)
	            Materialize.toast(`No se pudo enviar el correo de restablecer contraseña`, 4000)
	          })
	        } else {
	          Materialize.toast(`Digite su correo electrónico`, 4000)
	        }
	      }
	    
	```

* **Wilson Marino Pablo Mendez** (1)

	
	Buenisimo reto ✔

* **Alejandro González Reyes** (1)
El código funciona correctamente, pero envia tres correos (cuando debería emitir solo uno) a pesar que solo se presiona 1 vez el boton 

	* **Daniel Esteves** (1)

		
		¡Hola! ¿Podrías verificar si tu código es el mismo con el del profesor?

* **Wedwin53** (1)
El trafico que se genera durante el desarrollo hacia firebase (desde localhost) se cuenta en la cuota del servicio que es gratuito? es de...

	* **Henry Yerry Bravo Sánchez** (1)

		
		buena pregunta 😮

# Gestión de la Base de Datos

## 0140. Firestore

### Descripción:


Firestore es una base de datos NoSQL en formato JSON, es una herramienta muy flexible y nos permite guardar información sin estructuras o atributos predeterminados, además, es soportado por los servicios de Google Cloud, nuestra aplicación puede multiplicarse en diferentes regiones para aumentar su performance y no tendremos problemas de escalamiento.

Además del formato JSON, tenemos disponibles algunas nuevas estructuras para manejar la información y construir mejor nuestra base de datos. Firestore también es _Cross Platform_ , es decir, tiene soporte y multiples herramientas para construir aplicaciones en diferentes plataformas de Frontend y Backend, entre estos servicios encontramos el soporte offline.

### Comentarios:

* **Juan David Castro (Platzi)** (10)

	
	Notas de la clase:
	
	  * Firestore es una base de datos NoSQL en formato JSON 🏀
	  * El formato JSON con super poderes, tenemos toda la flexibilidad para utilizar o no los atributos que necesitemos, podemos utilizar otros tipos de estructuras de datos pero al final siempre resulta en JSON 💪 🎉
	  * Tiene soporte de **Google Cloud** , es decir, es increíblemente **escalable** y se multiplica por **diferentes regiones** para mejorar el _performance_ de nuestras aplicaciones _(igual que el resto de servicios de Firebase 😅)_ 👌 🗺
	  * **_Cross Platform_** : Soporta y construye herramientas de desarrollo para todas las plataformas _(mobile, web y backend)_ 🎬
	  * Tenemos **soporte offline** 🎉 ⛱
	  * Operaciones por lotes, es decir, multiples updates, deletes y todo este tipo de operaciones al mismo tiempo 😮
	
	

	* **Jesus Ricardo Moreira Cedeño** (1)

		
		Gracias 😃

	* **Juan David Castro (Platzi)** (1)

		
		¡Ahora también tenemos [Curso de Firestore](https://platzi.com/firestore) en Platzi! 💚

* **Edgar Mogollon** (8)

	
	!![firebase.png](https://static.platzi.com/media/user_upload/firebase-471b7304-44fb-40c2-9d9f-555210beff8a.jpg)
	
	Esto es lo que normalmente usamos para conectarnos a Firebase desde JavaScript o cualquiera de sus FrameWork.

* **Nadir Antonio Soza Solis** (4)

	
	Si quieren saber cuanto es el tiempo en horas de cada uno de los cursos ejecuten el siguiente script desde la pantalla donde se listan cada una de las clase.
	``` 
	    const times= document.querySelectorAll('.MaterialItem-copy-time');
	      let hours=0;
	      times.forEach(element => {
	        value= element.innerText.toString().replace(" min","");
	        const timeToClassInMinutes= value.replace(":",".");
	        hours= hours + parseFloat(timeToClassInMinutes);
	      })
	     
	      console.log(`${Math.round(hours,2)/60} Horas`)
	    
	```

	* **Jeffersson Muñoz Torres** (1)

		
		Demasiado bueno. Justo lo que hago antes de cada curso pero ahora con un clic. Muchas gracias.

	* **Ezequiel Ciccioli** (4)

		
		sugiero una mejora
		``` 
		    const times= document.querySelectorAll('.MaterialItem-copy-time');
		      let hours=0;
		      times.forEach(element => {
		        value= element.innerText.toString().replace(" min","");
		        const timeToClassInMinutes= value.replace(":",".");
		        hours= hours + parseFloat(timeToClassInMinutes);
		      })
		      horus= Math.round(hours,2)/60;
		      horas= String(horus).split('.')[0]
		      minutos= parseInt(parseInt(String(horus.toFixed(2)).split('.')[1])*0.6)
		      console.log(`${horas} Horas y ${minutos} Minutos`)
		    
		```
		
		De esta forma se entiende mejor los minutos

* **eltenis** (3)

	
	Si he empezado con realtime Database podria cambiar a firestore??? Gracias!!

	* **Daniel Esteves** (1)

		
		¡Hola! De hecho puedes usar las dos, en la [documentación](https://firebase.google.com/docs/firestore/firestore-for-rtdb) de Firebase te dice las instrucciones de cómo hacerlo 💪

* **Juan David Castro (Platzi)** (3)

	
	¿Saben cómo funcionan las operaciones bash en Firestore? 🤔 Si tienen experiencia o conocen algún tutorial al respecto les agradecería un montón 😄.

	* **jggomezt** (4)

		
		Hola, en nuestra clase llamada “Realizando inserciones, consultas compuestas, límites y ordenamiento”, se realiza un ejemplo de ello

* **Juan David Castro (Platzi)** (3)
¿Saben cómo funcionan las operaciones bash en Firestore? 🤔 Si tienen experiencia o conocen algún tutorial al respecto les agradecería un ...

	* **jggomezt** (4)

		
		Hola, en nuestra clase llamada “Realizando inserciones, consultas compuestas, límites y ordenamiento”, se realiza un ejemplo de ello

* **Juan Carlos Suarez Medina** (1)

	
	Tenemos diferentes tipos de datos

* **jangove** (1)

	
	Estoy realizando una tesis de Sistema web para mejorar las evaluaciones nutricionales en una clínica nutricional quisiera una ayuda que funcionalidades realizar.

	* **Sebastian Cardoso Castillo** (3)

		
		Podrías fijar unos estandares en funcion de las caracteristicas de las persona. Y de ahí comprar los resultados actuales con el estandar y darle indicaciones de como balancear la dieta.

* **Karol Leal Rojas** (1)

	
	Buenas noches profesor,  
	Quería preguntarle si de casualidad ud ha implementado el SDK de firebase ADMIN, tengo que listar los usuarios y editarlos, pero cada vez que intento integrar, me da error. No se si de casualidad me puede orientar, se lo agradecería mucho.

	* **jggomezt** (1)

		
		Hola, si claro, comparte el error

	* **Karol Leal Rojas** (1)
![Capture.png](https://static.platzi.com/media/user_upload/Capture-c8041098-33d3-4c6a-a6dc-144615609b28.jpg)
		
		De antemano muchas gracias!!

	* **jggomezt** (1)

		
		No lo veo muy bien, pero escríbeme a [juan.gomez01@gmail.com](mailto:juan.gomez01@gmail.com) y podemos revisarlo.

	* **Karol Leal Rojas** (2)

		
		Hola!! lo logre solucionar usando funciones en firebase, muchas gracias!!

* **Karol Leal Rojas** (1)
Buenas noches profesor, Quería preguntarle si de casualidad ud ha implementado el SDK de firebase ADMIN, tengo que listar los usuarios y ...

	* **jggomezt** (1)

		
		Hola, si claro, comparte el error

## 0150. Firebase Realtime Database vs Firestore

### Descripción:


Realtime database es la primera base de datos que liberó firebase con una alta eficiencia, baja latencia y capacidades para consultas en tiempo real. Firestore es la nueva base de datos diseñada y desarrollada por Google, la cual tiene una estructura más fácil de entender y diseñar y mejoras en los SDKs para la realización de consultas.

Veamos una comparación:

## Estructura de datos

Realtime Database almacena los datos en JSON pero se organiza o se representa en la plataforma como un árbol. Esta forma es compleja cuando crecen las anidaciones, las jerarquías o la información.

Cuando se tiene grandes jerarquías con el manejo de subcolecciones, Firestore tiene una estructura visible en la consola más sencilla y fácil de escalar.

## Soporte Offline

Realtime database da soporte de almacenamiento offline para Android y iOS. Firestore da soporte offline a móviles y también soporte para web.

## Los Queries

Realtime database soporta solo filtrar y ordenar por un campo en un solo query. Además, cuando se realiza una consulta retorna todo el sub árbol del nodo.

Firestore soporta consultas compuestas y puede combinar filtros con ordenamiento. Al consultar solo trae el documento o los documentos sin traer subcolecciones o hijos, esto se pide a demanda. Por otro lado, las consultas son indexadas por defecto. Soporta también el ordenamiento descendente.

## Escrituras y transacciones

Soporta escritura de forma individual en cambio Firestore soporta operaciones batch, las cuales pueden realizar operaciones de insertar, actualizar o eliminar al mismo tiempo.

## Fiabilidad y rendimiento

Realtime database es una base de datos usada por varias empresas con muchas operaciones y ha estado disponible por varios años, lo cual significa que ofrece una gran fiabilidad y baja latencia. Realtime database está limitado a una sola región.

Firestore está en beta todavía lo cual deja dudas sobre su estabilidad a nivel de uso, ya que puede cambiar su SDK. Sin embargo, Firestore almacena los datos en múltiples datacenters y en distintas regiones, brindando una gran escalabilidad y confiabilidad.

## Escalabilidad

Firestore escala de forma automática, por lo cual no se requiere compartir los datos a través múltiples instancias.

Reglas de seguridad

Realizar las reglas en Firestore es más simple y más robusto. Las reglas en Firestore no son en cascada, en cambio en Realtime Database sí. La validación de los datos en Firestore es automática, en Realtime Database hay que definirlos.

## Precios

El cobro en Realtime Database es por tamaño de almacenamiento y ancho de banda y es más costoso que Firestore. En firestore el modelo de cobro primario es por operaciones de escritura, lectura y eliminado, el modelo secundario es por tamaño de almacenamiento y ancho de banda siendo este muy económico. También, en Firestore se cobra por los índices creados.

Firestore aunque esté en beta ofrece una gran escalabilidad, SDKs que permiten hacer consultas de una forma más sencilla y mejora las falencias de Realtime Database. Realtime Database se mantendrá por unos años pero será reemplazada por firestore, así que empieza aprender las bondades de Firestore.

### Comentarios:

* **Wilson Marino Pablo Mendez** (9)

	
	 **Firestore** ya no está en beta

* **javieralbadan** (4)
Es falso que en la Realtime no se pueden hacer operaciones simultáneas para el caso de transacciones, y en donde falle una, se devuelvan todas... Se hace creando un objeto que denominan "multipath", con diferentes rutas y sus valores a actualizar. Allí se actualiza según necesidad, eliminando, agregando o actualizando. Un poco más de ello aqui: https://youtu.be/i1n9Kw3AORw

	* **Daniel Esteves** (1)

		
		Claro pero que es lo que pasa, eso es mucho más trabajo, digamos que Firestore es más actualizado digamos que es un Realtime Database 2.0

* **Roy Vega** (4)

	
	 **Cloud Firestore**  
	Es una base de datos que se asimila a un esquema de base de datos tradicional. Se podría decir que las colecciones son tablas y los documentos las filas.
	
	Ahora, los campos dentro de un documento manejan tipo de dato, como string, numbers, boolean, objects, arrays, null values, date timestamps, geopoints y (shallow references) referencias poco profundas a otros documentos.
	
	[Referencia](%5Burl%5D\(https://savvyapps.com/blog/firebase-realtime-database-vs-cloud-firestore-for-your-app\))

* **Juan David Castro (Platzi)** (4)

	
	Otras comparaciones entre Firestore y Realtime Database:
	
	  * [Firebase Realtime DB vs Firestore 🔥 - Chris Esplin](https://www.youtube.com/watch?v=TmXct7seeBY)
	  * [What’s the Difference Between Cloud Firestore & Firebase Realtime Database? #AskFirebase](https://www.youtube.com/watch?v=KeIx-mArUck)
	  * [Choosing a Firebase Database For Your App: Realtime Database vs. Cloud Firestore](https://savvyapps.com/blog/firebase-realtime-database-vs-cloud-firestore-for-your-app)
	
	

* **alejandropazperez** (2)

	
	Es bueno ir avanzando al paso que lo hacen los nuevos servicios. 😃

* **louismanson** (1)

	
	Firestore ya no es beta :3

* **Appland** (1)


* **joseadrian** (1)

	
	Entendido y anotado, a aprender firestore

* **nelsonboca** (1)

	
	Excelente comparacion

* **Lordpanther** (1)

	
	Una gran solución y aplicación.

* **csmimo** (1)

	
	Gracias por la comparación (Y)

* **Jesus Ricardo Moreira Cedeño** (1)

	
	Bastante interesante

* **Juan David Castro (Platzi)** (1)

	
	¡Genial! Es muy útil tener esta comparación entre los dos servicios 🎉.

## 0160. Configuración de Firestore al proyecto

### Descripción:


### Links:

* [Get started with Cloud Firestore  |  Firebase](https://firebase.google.com/docs/firestore/quickstart)

* [Choose a data structure  |  Firebase](https://firebase.google.com/docs/firestore/manage-data/structure-data)

### Comentarios:

* **Juan David Castro (Platzi)** (4)

	
	Solo podemos manejar una base de datos con Firestore por proyecto, por ahora...

* **Victor Riveros** (3)

	
	Cuando cree el proyecto de firebase, me selecciono la base de datos firestore en modo datastore por defecto, por ende los codigos de este curso no me funcionaron.  
	Toco crear un proyecto desde Cloud Platform y seleccionar la base de datos firestore en modo nativo (No datastore), y luego agregar ese proyecto a firebase.
	
	Por si alguno tenga el mismo problema 😃

	* **JaimeRamos** (1)

		
		Disculpa, como lo agregaste a Firebase ya una vez creado?

* **Gerardo Manuel Reyes Fernández** (3)

	
	Lo que se hizo en este capítulo fue simular una base relacional, al pasar la subcolección a coleccion y pasarle un id de referencia. Por lo que entendí, no se requiere una estructura previa y es flexible
	
	Esto también facilita las consultas? como haciendo joins(simulando sql) o algo por el estilo?

	* **Daniel Esteves** (2)

		
		Si, recuerda que Firestore es una base de datos NoSQL eso quiere decir que no tiene relaciones, solo tiene documentos dentro de documentos dentro de documentos 🤓

* **Juan David Castro (Platzi)** (3)
¿Por qué es recomendado crear colecciones en vez de subcolecciones? ¿Es por performance o para organizar mejor nuestra aplicación? 🤔

	* **Brian Bentancourt** (3)

		
		ambas cosas, ademas no podes hacer consultas de subcolecciones

* **Jorge Galán** (2)

	
	Porqué idPost es de tipo string y no de tipo reference??

* **joseadrian** (2)

	
	Si quisiera guardar la fecha y hora por separado, que forma seria la recomendada?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		No es común hacerlo así, pero puedes extraer solo la fecha y solo la hora y guardarlos, porque no es recomendable porque si quieres hacer una consulta que depende del tiempo con base en fecha y hora vas a tener que filtrar por dos campos en lugar de uno solo.

	* **José Colmenares** (1)

		
		No es recomendable hace esto , es mejor guardar la fecha como tipo Date , múltiples lenguajes de programación te permiten obtener solo la hora y el día de un tipo Date.

	* **Juan Carlos Rueda Diaz** (1)

		
		excelente

* **Jesus Ricardo Moreira Cedeño** (2)

	
	Entendido

* **Juan David Castro (Platzi)** (2)

	
	¿Por qué es recomendado crear colecciones en vez de subcolecciones? ¿Es por performance o para organizar mejor nuestra aplicación? 🤔

	* **Brian Bentancourt** (3)

		
		ambas cosas, ademas no podes hacer consultas de subcolecciones

	* **xeoDev** (6)

		
		Las consultas son de un solo nivel. Por ejemplo si haces una consulta a una colección te trae todos los documentos, pero no trae las subcolecciones de los documentos.
		
		Lo mismo pasa cuando haces una consulta a un documento en especifico, te trae todos los datos string, array, number…etc pero no te trae ninguna colección que este anidada en ese documento. Para obtener la colección anidada es necesario realizar una consulta adicional, entonces si de igual forma hay que realizar mas consultas, pues es mejor que las subcolecciones se conviertan en colecciones y así tener una mayor legibilidad de los datos.
		
		Ademas es mas fácil realizar indices 😄

* **Juan David Castro (Platzi)** (2)

	
	Solo podemos manejar una base de datos con Firestore por proyecto, por ahora...

* **Luis Rangel Castro** (1)

	
	index.html
	``` 
	    <!-- Firebase App (the core Firebase SDK) is always required and must be listed first -->
	    <scriptsrc="https://www.gstatic.com/firebasejs/7.12.0/firebase-app.js"></script>
	    
	    <!-- If you enabled Analytics in your project, add the Firebase SDK for Analytics -->
	    <scriptsrc="https://www.gstatic.com/firebasejs/7.12.0/firebase-analytics.js"></script>
	    
	    <!-- Add Firebase products that you want to use -->
	    <scriptsrc="https://www.gstatic.com/firebasejs/7.12.0/firebase-auth.js"></script>
	    <scriptsrc="https://www.gstatic.com/firebasejs/7.12.0/firebase-firestore.js"></script>
	    
	```

* **joseadrian** (1)

	
	el Id documento, es id del registro o id de lo que seria equivalente a una tabla en E-R?

	* **joseadrian** (2)

		
		Coleccion = tabla  
		idDocumento = idRegistro

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Si no lo sobrescribes es un id único similar al que se usa en bases de datos relacionales, la diferencia es que no es autoincremental, por lo general es un hash.

* **joseadrian** (1)
el Id documento, es id del registro o id de lo que seria equivalente a una tabla en E-R?

	* **joseadrian** (2)

		
		Coleccion = tabla  
		idDocumento = idRegistro

* **joseadrian** (1)
Si quisiera guardar la fecha y hora por separado, que forma seria la recomendada?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		No es común hacerlo así, pero puedes extraer solo la fecha y solo la hora y guardarlos, porque no es recomendable porque si quieres hacer una consulta que depende del tiempo con base en fecha y hora vas a tener que filtrar por dos campos en lugar de uno solo.

* **Gerardo Manuel Reyes Fernández** (1)
Lo que se hizo en este capítulo fue simular una base relacional, al pasar la subcolección a coleccion y pasarle un id de referencia. Por ...

	* **Daniel Esteves** (2)

		
		Si, recuerda que Firestore es una base de datos NoSQL eso quiere decir que no tiene relaciones, solo tiene documentos dentro de documentos dentro de documentos 🤓

## 0170. Desarrollando la inserción de datos

### Descripción:


### Comentarios:

* **Carolina Londoño** (5)

	
	las líneas
	``` 
	    const settings = { timestampsInSnapshots : true} 
	    this.db.settings(settings)
	    
	```
	
	ya no son necesarias puesto que esta configuración ya está por defecto 😄

* **AndrsDev** (5)

	
	Este es otro ejemplo de cómo se podría agregar datos
	``` 
	    asyncfunctionaddUser(){
	        let userData = {
	            name: "Andres 2",
	            lastName: "Sanabria",
	            birthdate: firebase.firestore.FieldValue.serverTimestamp(),
	            email: "email@gmail.com",
	            profession: "UX/UI Designer"
	        }
	    
	        let newDocID = await firebase.firestore().collection("users").add(userData).then(doc => doc.id);
	        console.log("Saved: ", newDocID);
	    }
	    
	```

* **Manuel Aguilera Magaña** (4)

	
	Ya no es necesario hacer la configuración explicita de timestampsInSnapshots.
	``` 
	    ```const settings = { timestampsInSnapshots: true };
	    this.db.settings(settings);
	    
	```
	```
	```
	

	* **OSCAR ALFREDO CHAFLOQUE TAMPECK** (1)

		
		Cierto, Gracias, pero si tipamos en la clase.  
		fecha?: firebase.firestore.FieldValue;

* **Carolina Londoño** (4)

	
	Si tienen problemas de permisos para guardar en la DB, vayan a la tab de Reglas de Database y poner en true los permisos de lectura/escritura:
	``` 
	    rules_version = '2';
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /{document=**} {
	          allow read, write: iftrue;
	        }
	      }
	    }
	    
	```

* **Jose Rueda** (3)

	
	acabo de notar que la sesion se queda iniciada incluso despues de cerrar el navegador, como se puede evitar esto?. Si necesito que la sesión se cierre cuando se cierre el navegador

	* **jggomezt** (10)

		
		Hola, pienso que como esta es la practica adecuada, gmail te guarda la sesión así cierres todo. Ahora, lo que requieres lo puedes hacer cambiando el tipo de persistencia a SESSION por default es LOCAL. `firebase.auth().setPersistence(firebase.auth.Auth.Persistence.SESSION)`. Puedes ver mas de esto en: <https://firebase.google.com/docs/auth/web/auth-state-persistence?hl=es-419>

	* **Lordpanther** (2)

		
		También se puede generar una subrutina que se ejecute al salir de la pagina.

* **OSCAR ALFREDO CHAFLOQUE TAMPECK** (2)

	
	how to solve this error:  
	index.esm.js:102 [2020-03-23T18:04:21.556Z] @firebase/firestore: Firestore (7.11.0):  
	The timestampsInSnapshots setting now defaults to true and you no  
	longer need to explicitly set it. In a future release, the setting  
	will be removed entirely and so it is recommended that you remove it  
	from your firestore.settings() call now.
	
	constructor(private afs: AngularFirestore) {  
	const setting = {timestampsInSnapshots: true};  
	this.afs.firestore.settings(setting);  
	}

	* **Johan Manuel Perez Soto** (2)

		
		Tan solo tendrías que eliminar los ajustes, ya que desde esa versión firebase lo hace por defecto, tu código quedaría de la siguiente manera,
		``` 
		    constructor(){
		        this.db = firebase.firestore();
		      }
		    
		```

* **Esteban Guzmán Ramírez** (2)

	
	Un cambio de pasta térmica a los profesores no estaría mal, a lo mejor sea muy quisquilloso o parece que la computadora esta a punto de despegar 😂

* **Jonattan_Infante** (2)

	
	Solo como un dato, Actualmente la propiedad **timestampsInSnapshots **esta deprecada. Les dejo el link a la documentación por si deseas checarlo
	
	<https://firebase.google.com/docs/reference/js/firebase.firestore.Settings.html?authuser=0#optional-timestamps-insnapshots>

	* **juanseg** (1)

		
		Gracias, pero que habría que poner en su reemplazo?

* **Alejandro González Reyes** (2)

	
	Hola, tengo el siguiente problema.  
	Cuando registro el Post, Firestore lo almacena 2 veces.
	``` 
	    crearPost (uid, emailUser, titulo, descripcion, imagenLink, videoLink) {
	        // Indicamos a firestore que coleccion se va a emplear para añadir el documento
	        // El método add, genera automáticamene el id del documento
	        
	        // En este caso add devuelve promesa, por tanto la retornamos para que en la sección donde se invoca
	        // este metodo, se hagan tareas una vez registrados los datos
	        returnthis.db.collection('posts').add({
	          uid: uid,
	          autor: emailUser,
	          titulo: titulo,
	          descripcion: descripcion,
	          imagenLink: imagenLink,
	          videoLink: videoLink,
	          // En este caso le indicamos a firestore que genere la fecha actual en el servidor
	          fecha: firebase.firestore.FieldValue.serverTimestamp()
	        })
	        .then(refDoc => {
	          console.log(`Id del Post: ${refDoc.id}`)
	        })
	        .catch(error => {
	          console.log(`Error al crear el post: ${error}`)
	        })
	      }
	    
	```
	``` 
	    $('#btnRegistroPost').click(() => {
	        // Creamos una instancia de la clase Post para registrar el documento
	        const post = new Post()
	    
	        // TODO: Validar que el usuario esta autenticado
	        const user = firebase.auth().currentUser
	        if(user == null) {
	          Materialize.toast(`Para crear el Post debes estar autenticado`, 4000)
	          // Hacemos esto para que no se ejecute lo demas
	          return
	        }
	    
	        // Materialize.toast(`Para crear el post debes estar autenticado`, 4000)
	    
	        // Recuperar la data del formulario para crear el POST
	        const titulo = $('#tituloNewPost').val()
	        const descripcion = $('#descripcionNewPost').val()
	        const videoLink = $('#linkVideoNewPost').val()
	        const imagenLink = sessionStorage.getItem('imgNewPost') == 'null'
	          ? null
	          : sessionStorage.getItem('imgNewPost')
	    
	        // Invocar el método crearPost para proceder a guardarlo
	        post.crearPost(user.uid, user.email, titulo, descripcion, imagenLink, videoLink)
	          .then(resp => {
	            // En el cuerpo del método retornamos una promise
	            // Por tanto la usamos aqui para realizar tareas posteriores al registro
	            Materialize.toast(`Post creado correctamente`, 4000)
	            // Cerrar el modal con el form de registro de post
	            $('.modal').modal('close')
	          })
	          .catch(err => {
	            Materialize.toast(`Error => ${err}`, 4000)
	          })
	      })
	    
	```

	* **Alejandro González Reyes** (3)

		
		Yo solo me respondo, jajjja.  
		Al parecer el problema viene en esta línea. ‘null’ por null
		``` 
		    const imagenLink = sessionStorage.getItem('imgNewPost') == null ? null : sessionStorage.getItem('imgNewPost')
		    
		    
		    
		```

* **Alejandro González Reyes** (2)

	
	La siguiente linea de código que es lo que retorna?
	``` 
	    returnthis.db.collection('posts').add({
	    ....
	    })
	    .then(...)
	    .catch(...)
	    
	```

	* **Daniel Esteves** (1)

		
		Lo que hace este return es conseguir la colección de `posts` y añadir los datos que le estamos pasando y si todo está bien retorna el resultado y si no retorna el error

* **Yerlinson** (2)

	
	¿Cómo se puede personalizar el modelo de autenticación?  
	Es decir, agregarle atributos adicionales como dirección, edad, fechaDeNacimiento, etc?

	* **Mariangelica Useche Saavedra** (3)

		
		Para esto debes crear una colección en la base de datos con todos los campos custom que quieras (como la fecha de nacimiento, dirección, etc.).
		
		  1. Haces la autenticación con Firebase y con el uid del resultado, creas el documento del usuario.
		  2. Agregas los campos custom a este documento.
		
		
		
		Espero haberme explicado. Saludos.

* **Karol Leal Rojas** (2)

	
	Buenas, como se manejan los tipos de datos REFERENCE, que haga referencia a un documento de otra coleccion.

	* **Daniel Esteves** (1)

		
		¡Hola Karol! Por acá te dejo este [enlace de la documentación](https://firebase.google.com/docs/reference/js/firebase.database.Reference) donde hablar de cómo hacer las referencias

* **joseadrian** (2)

	
	La estructura json para el post fue creado desde el codigo o desde la consola?

	* **Daniel Esteves** (1)

		
		La estructura de JSON ya la trae por defecto Firebase es lo que va a retornar 💪

* **nelsonboca** (2)

	
	En el contructor de la clase no hace falta el siguiente codigo:
	``` 
	    const settings = {timestampsInSnapshots : true}
	          this.db.settings(settings)
	    
	```
	
	La configuracion ya se encuentra configurado por default en la version de firebase 5.8.x  
	![](http://i65.tinypic.com/15yz0cg.png)

* **Jose Rueda** (2)
acabo de notar que la sesion se queda iniciada incluso despues de cerrar el navegador, como se puede evitar esto?. Si necesito que la ses...

	* **jggomezt** (10)

		
		Hola, pienso que como esta es la practica adecuada, gmail te guarda la sesión así cierres todo. Ahora, lo que requieres lo puedes hacer cambiando el tipo de persistencia a SESSION por default es LOCAL. `firebase.auth().setPersistence(firebase.auth.Auth.Persistence.SESSION)`. Puedes ver mas de esto en: <https://firebase.google.com/docs/auth/web/auth-state-persistence?hl=es-419>

* **ddragaid** (1)

	
	actualmente con la nueva version se tienen que quitar las lineas de  
	const settings = { timestampsInSnapshots: true }  
	this.db.settings(settings)  
	pero ahora tengo un proble que dice  
	onSnapshot: FirebaseError: "Missing or insufficient permissions."  
	alguien mas?

	* **Jose Luis Campos Bautista** (1)

		
		En la sección de reglas puedes configurar los permisos de escritura en tu base de datos.
		
		![Captura de pantalla 2020-04-04 a la\(s\) 14.54.27.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202020-04-04%20a%20la%28s%29%2014.54.27-83211aae-2f06-4529-9ac9-70d9e53d86d2.jpg)

* **David Trespalacios** (1)

	
	Hola! en que curso aprendo a usar este tipo código?
	``` 
	    const imagenLink = sessionStorage.getItem('imgNewPost') == 'null'
	          ? null
	          : sessionStorage.getItem('imgNewPost')```
	    
	```

	* **juanseg** (3)

		
		La verdad que en los cursos que hice se vió muy poco. Se llama **operador condicional ternario** , es solo un atajo al _if_.  
		[Documentación](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Conditional_Operator)

	* **David Trespalacios** (1)

		
		Gracias

* **darwinyusef** (1)

	
	Hubo un error y el corte del vídeo no me permitió ver como se soluciono, no supimos cual fue su solución

* **wilverromero** (1)

	
	Hola, quiero integrar firestore en react nattive pero me dice que firebase.firestore() no es una funcion  
	si me pueden ayudar con eso se los agradeceria

	* **Daniel Esteves** (1)

		
		¡Hola Wilver! Por aquí te dejo un [tutorial](https://invertase.io/blog/getting-started-with-cloud-firestore-on-react-native/) de cómo configurarlo con React Native para evitar este tipo de errores a futuro 💪

* **Alejandro González Reyes** (1)
Hola, tengo el siguiente problema. Cuando registro el Post, Firestore lo almacena 2 veces. crearPost (uid, emailUser, titulo, descr...

	* **Alejandro González Reyes** (3)

		
		Yo solo me respondo, jajjja.  
		Al parecer el problema viene en esta línea. ‘null’ por null
		``` 
		    const imagenLink = sessionStorage.getItem('imgNewPost') == null ? null : sessionStorage.getItem('imgNewPost')
		    
		    
		    
		```

* **Alejandro González Reyes** (1)
La siguiente linea de código que es lo que retorna? return this.db.collection('posts').add({ .... }) .then(...) .catch(...) 

	* **Daniel Esteves** (1)

		
		Lo que hace este return es conseguir la colección de `posts` y añadir los datos que le estamos pasando y si todo está bien retorna el resultado y si no retorna el error

* **joseadrian** (1)
La estructura json para el post fue creado desde el codigo o desde la consola?

	* **Daniel Esteves** (1)

		
		La estructura de JSON ya la trae por defecto Firebase es lo que va a retornar 💪

## 0180. Consultas en real time

### Descripción:


Las Consultas en _real time_ son la capacidad de obtener la información de nuestra base de datos y actualizarla en nuestra aplicación cada vez que la modificamos desde cualquier sitio. A diferencia de otros servicios, Firebase notifica a nuestras aplicaciones cada vez que cambia la información la información que estamos consumiendo, así mejoramos la _performance_ de nuestra aplicación porque no debemos consultar todo el tiempo a la base de datos.

### Comentarios:

* **Juan David Castro (Platzi)** (11)

	
	Estos tutoriales _(algunos en ingles 🇺🇸)_ son muy útiles para complementar lo que aprendimos en la clase y ver las otras formas _(o no 😅)_ de consumir la información de Firetore en tiempo real con otros proyectos 👍:
	
	  * [Firebase Firestore Tutorial - Real-time Data](https://www.youtube.com/watch?v=RdnPAOA6qfw)
	  * [Obtener actualizaciones en tiempo real con Cloud Firestore  
	](https://firebase.google.com/docs/firestore/query-data/listen?hl=es-419)
	
	

	* **David Farinango** (1)

		
		Gracias bro!

* **Juan David Castro (Platzi)** (5)

	
	Eso de que Firebase nos notifique cada vez que hay algún cambio en las BDs en vez de nosotros consultar cada segundo _(haciendo nuestra aplicación cada vez más lenta)_ es mágico 😍🔥🎉.

	* **jggomezt** (4)
Hola, tu decides si quieres recibir la info en real time y en algunas ocasiones es más rápido que estar siempre consultando

* **Henry Yerry Bravo Sánchez** (4)

	
	Usuar varias consultas  
	<https://firebase.google.com/docs/firestore/query-data/queries?hl=es-419>
	``` 
	        .where('key', '==', value)
	        .where('key', '==', value)
	    
	    
	```

* **Alejandro González Reyes** (4)

	
	Les dejo una actualización en el archivo de util.js  
	Puesto que la fecha no se muestra con el formato correcto NAN/NAN/NAN a consecuencia de cambios en en la API de firestore
	``` 
	    class Utilidad {
	      static obtenerFecha (timeStamp) {    
	       // El cambio es llamar al atributo seconds
	        const d = new Date(timeStamp.seconds)
	        console.log(timeStamp);
	        console.log(d);
	        let month = '' + (d.getMonth() + 1)
	        let day = '' + d.getDate()
	        let year = d.getFullYear()
	    
	        if (month.length < 2) month = '0' + month
	        if (day.length < 2) day = '0' + day
	    
	        return [day, month, year].join('/')
	      }
	    }
	    
	    
	```

* **alejandropereira** (3)

	
	websockets VS DataSnapshot
	
	que es mejor para un chat !?

	* **Daniel Esteves** (2)

		
		Websockets mil veces, ya que vas a necesitar consultar datos cada vez que haya alguno nuevo

* **Luis Rangel Castro** (2)

	
	esto parece brujeria!!! jejeje

* **Joseph Alexander Whacheng Barreto** (2)

	
	Que tan seguro es si filtramos por “uid” ???

	* **Daniel Esteves** (1)

		
		Estarías consultando por el ID básicamente, no tendrías ningún tipo de problema solo que no le deberías mostrar esa información a ningún usuario

* **David Farinango** (2)

	
	Aquí mas tutoriales sobre react y firestore
	
	  * [Agregando Firestore y Obteniendo Colección](https://www.youtube.com/watch?v=F5QSOzhnsPo)
	
	

* **Lordpanther** (2)

	
	La nueva web es muchísimo más dinámica que hace tan solo algunos años

* **Roberto Antonio Flores Zamora** (2)

	
	Cual es el pluggin para intelisense de JS ? para que al crear una funcion en otro archivo y usarlo, siempre entienda que funcion es ?

	* **jggomezt** (1)

		
		Hola, no entendí, puedes explicar mejor??

	* **Daniel Esteves** (1)

		
		¡Hola Roberto! Cuando se utiliza VSCode ya tiene integrado un autocompletado, lo que debes hacer es importar el archivo de `.js` a el archivo que estás utilizando para que puedas usarlo ahí

	* **José Colmenares** (2)

		
		VSCode tiene integrado un autocompletado bastante decente, sin embargo, puedes añadir algunos plugins adicionales para Javascript y/o firebase.

* **Oscar Torres** (2)

	
	No me despliega el video por el siguiente error
	``` 
	    Refused to display 'https://www.youtube.com/watch?v=kpcjBD1XDwU'ina frame because itset'X-Frame-Options'to'sameorigin'.
	    
	```
	
	Como puedo corregirlo?

	* **John Freddy Vega (Platzi)** (2)

		
		Prueba con otro video. Quizás este esté restringido para correr fuera de Youtube.

	* **Oscar Torres** (1)

		
		Nada **Fredy** , intenté con varios videos y sucedió lo mismo, con una imagen funciona perfectamente.

	* **jggomezt** (8)

		
		Hola tienes que colocar la URL del código de inserción que genera youtube, ya que es un iframe

	* **Oscar Torres** (1)

		
		Excelente, ahora si, gracias **_paisano_!!**
		``` 
		    https://www.youtube.com/embed/kpcjBD1XDwU
		    
		```

	* **Jesús Cama** (1)

		
		Debes cambiar la url de <https://www.youtube.com/watch?v=kpcjBD1XDwU> a <https://www.youtube.com/embed/kpcjBD1XDwU>

* **Alejandro González Reyes** (2)
Les dejo una actualización en el archivo de util.js Puesto que la fecha no se muestra con el formato correcto NAN/NAN/NAN a consecuencia ...

* **Oscar Torres** (2)
No me despliega el video por el siguiente error Refused to display 'https://www.youtube.com/watch?v=kpcjBD1XDwU' in a frame because...

	* **John Freddy Vega (Platzi)** (2)

		
		Prueba con otro video. Quizás este esté restringido para correr fuera de Youtube.

* **David Behar** (1)

	
	Si su consola les llena de errores, desactiven adBlock

* **Victor Riveros** (1)

	
	Alguien logro “paginar” los resultados? mire la documentacion pero no me quedo muy claro…

* **Alejandro Daniel Oroncoy Almeyda** (1)

	
	Esta parte del curso parece ser una de las mejores! Me quede anonajado!

* **alexanderorellanam** (1)
![resumen1.png](https://static.platzi.com/media/user_upload/resumen1-3766f974-9896-4dfe-91df-847c2aef4e74.jpg)

* **alexanderorellanam** (1)
![resumen2.png](https://static.platzi.com/media/user_upload/resumen2-08381f9a-0227-4b19-b506-a1636c00fd96.jpg)

* **joseadrian** (1)

	
	y si quisiera filtrar por multiples campos?

	* **Henry Yerry Bravo Sánchez** (5)

		
		Espero no sea muy tarde, encontre esto
		``` 
		        this.bd.collection('posts')
		        .where('autor', '==', emailUser)
		        .where('titulo', '==', 'dsds')
		    
		```
		
		[Referencia](https://firebase.google.com/docs/firestore/query-data/queries?hl=es-419)

* **Jesus de la Casa Palomino** (1)
¿Cómo se limita el número de consultas/usuario en firestore? porque cualquiera podría modificar el cliente y empezar a mandar peticiones ...

* **joseadrian** (1)
y si quisiera filtrar por multiples campos?

	* **Henry Yerry Bravo Sánchez** (5)

		
		Espero no sea muy tarde, encontre esto
		``` 
		        this.bd.collection('posts')
		        .where('autor', '==', emailUser)
		        .where('titulo', '==', 'dsds')
		    
		```
		
		[Referencia](https://firebase.google.com/docs/firestore/query-data/queries?hl=es-419)

* **Roberto Antonio Flores Zamora** (1)
Cual es el pluggin para intelisense de JS ? para que al crear una funcion en otro archivo y usarlo, siempre entienda que funcion es ?

	* **jggomezt** (1)

		
		Hola, no entendí, puedes explicar mejor??

* **VenkoTec** (0)

	
	Como podemos obtener los datos en caso que nuestro documento tenga un dato de tipo reference?

## 0190. Realizando inserciones, consultas compuestas, límites y ordenamiento

### Descripción:


### Links:

* [Order and limit data with Cloud Firestore  |  Firebase](https://firebase.google.com/docs/firestore/query-data/order-limit-data)

* [Perform simple and compound queries in Cloud Firestore  |  Firebase](https://firebase.google.com/docs/firestore/query-data/queries)

* [Paginate data with query cursors  |  Firebase](https://firebase.google.com/docs/firestore/query-data/query-cursors)

### Comentarios:

* **marcelo.lavizzari** (8)

	
	Me encanto esta clase, he estado buscando un monton en internet en español, para realizar estas acciones en firestore y me ha costado encontrar algo. Excelente los ejemplos.

* **AndrsDev** (3)

	
	¿Cuál es la diferencia entre realizar un **.set() con merge** y realizar un **.update()** ?

	* **AndrsDev** (3)

		
		Revisé la documentación y la diferencia es que con .set() si el documento no existe lo crea. Con .update() si el documento no existe muestra un error.

	* **AndrsDev** (3)

		
		<https://firebase.google.com/docs/firestore/manage-data/add-data>

* **christian-hijar-garcia** (2)

	
	Como puedo hacer consultas con el operador OR?

* **Cesar Pereda** (2)

	
	y no vi nada de paginación

	* **Daniel Esteves** (1)

		
		¡Hola! Lo puedes ver en <https://firebase.google.com/docs/firestore/query-data/query-cursors> para que vayas integrando el comportamiento de paginación 💪

* **jesusmurf** (2)

	
	Según he entendido, el batch sería algo así como hacer un Promise.all() en Javascript.

	* **nova12** (1)

		
		no, batch lo que hace prea-listar un grupo de operaciones en la base se datos y generar su ejecución, pero si alguna de las operaciones falla ninguna de las operaciones se reflejara en la base datos

* **Alejandro González Reyes** (1)

	
	Excelente

* **Diego Fernández Cruz** (1)

	
	Muchas gracias profe!

* **joseadrian** (1)

	
	Se puede interpretar a batch como una transaccion?

	* **joseadrian** (1)

		
		los campos de los demas documentos se queda igual o tambien se le agrega el nuevo campo con algun dato deaful?

	* **ebar0n (Platzi)** (1)

		
		Hola, con **batch** puedes hacer transacciones, el resultado si seria una transaccion.

	* **Nadir Antonio Soza Solis** (1)

		
		Es diferente una **transacción** a un **batch** , el batch se apega mas a lo que se conoce como inserciones por lotes.

* **jggomezt** (1)
Algo similar

* **Eden Gomez Gress** (1)

	
	Esos archivos a que nivel de projecto se deben de guardar?

	* **jggomezt** (1)
Se debe tener una arquitectura adecuada en tu App y está debe tener una capa de repositorio, en esta se debe tener estas consultas

* **Brian Bentancourt** (1)

	
	se puede hacer paginado con las consultas?

	* **jggomezt** (5)

		
		Hola, si claro lo puedes hacer, usando las funciones startAt y endAt, puedes ver la documentación <https://firebase.google.com/docs/firestore/query-data/query-cursors>

	* **Marcos Galaviz** (2)

		
		Ojala pongan un ejemplo practico de consultas paginadas, yo he batallado con eso.

	* **Cesar Pereda** (2)

		
		Justo eso estoy buscando tambien, paginaciòn de consultas. espero que haga un video sobre eso. Saludos,

* **Brian Bentancourt** (1)

	
	con el batch podriamos hacer transacciones?

	* **jggomezt** (1)
Si es posible

* **Esteban Guzmán Ramírez** (1)
Tengo duda con la consulta compuesta, en la documentación dice que no se puede hacer lo que se hace en el video o entendí mal. 

* **David García** (1)
Saludos, Como se podrian obtener resultados entre una fecha y otra? Por ejemplo un listado de facturas desde el 1 de enero de 2019 hasta...

	* **Javier Batres** (2)

		
		Hola David. En este caso depende de como almacenes las fechas. En el caso de RealtimeDatabase lo mejor es usar el unixtime o tiempo en milisegundos pues podras hacer facilmente un mayor y menor que. Ahorta bien en el caso de Firestore, los datos tienen tipo y puedes asignarlo como Timestamp con lo que podras hacer lo mismo del mayor, menor que…

* **Alejandro González Reyes** (1)
Excelente

* **joseadrian** (1)
Se puede interpretar a batch como una transaccion?

	* **joseadrian** (1)

		
		los campos de los demas documentos se queda igual o tambien se le agrega el nuevo campo con algun dato deaful?

* **Eden Gomez Gress** (1)
Esos archivos a que nivel de projecto se deben de guardar?

	* **jggomezt** (1)
Se debe tener una arquitectura adecuada en tu App y está debe tener una capa de repositorio, en esta se debe tener estas consultas

* **Brian Bentancourt** (1)
se puede hacer paginado con las consultas?

	* **jggomezt** (5)

		
		Hola, si claro lo puedes hacer, usando las funciones startAt y endAt, puedes ver la documentación <https://firebase.google.com/docs/firestore/query-data/query-cursors>

## 0200. Reglas de seguridad

### Descripción:


Las reglas de seguridad de Firebase nos permiten restringir el acceso de nuestros usuarios a ciertas partes o contenidos especiales de la aplicación.

Con la instrucción `match` podemos especificar las rutas de nuestra base de datos que queremos asegurar y con `allow` damos _(o no)_ los permisos especiales para solo ciertos usuarios. Por ejemplo, podemos asegurarnos de que las publicaciones de nuestros usuarios solo puedan editarse o eliminarse por sus creadores:
``` 
    match /posts/{post}/{uid} {
            allow update, delete: if request.auth.uid == uid
                    && request.resource.data.email == resource.data.email
    }
```

### Links:

* [https://firebase.google.com/docs/firestore/security/overview](https://firebase.google.com/docs/firestore/security/overview)

### Comentarios:

* **Juan David Castro (Platzi)** (8)

	
	Estos tutoriales del Blog de Platzi _(uno con vídeo animado 😮)_ son muy útiles para complementar lo que aprendimos sobre las reglas de seguridad en Firebase 👌:
	
	  * [Reglas de seguridad en Firebase - @anncode](https://platzi.com/blog/reglas-de-seguridad-en-firebase/)
	  * [Reglas de Seguridad de Firebase: ejemplo práctico - @jjyepez](https://platzi.com/blog/reglas-de-seguridad-de-firebase-ejemplo-practico/)
	
	

	* **Damián Mateo Nuñez** (2)

		
		Tengo entendido que las reglas mencionadas en los artículos funcionan solo para Realtime Database, para Firestore todas las reglas de seguridad deben consistir en declaraciones match

	* **Juan David Castro (Platzi)** (1)

		
		👌 Nuevo tutorial: [Reglas de Seguridad Avanzadas con Firebase y Firestore](https://platzi.com/blog/reglas-de-seguridad-avanzadas-con-firebase-y-firestore/).

* **Alejandro González Reyes** (4)

	
	No entiendo la última regla.  
	Se que el dueño del documento puede borrarlo o eliminarlo  
	Pero es confuso ese request.resorce.data.email con el resorce.data.email  
	Me pueden explicar

	* **Alejandro González Reyes** (4)

		
		Me respondo a mi mismo jaja.  
		El email del docuemtno entrante debe ser identico al email documento existente.

* **Juan Carlos Suarez Medina** (2)

	
	podriamos profundizar mas en el funcionamiento del simulador?

	* **Daniel Esteves** (1)

		
		¡Hola! En la documentación 👉 <https://firebase.google.com/docs/firestore/security/get-started?hl=es-419> te habla sobre más reglas de seguridad y para que sirven

* **joseadrian** (2)

	
	seria correcto poner:  
	match /post/{  
	allow list: if true  
	}
	
	es decir, sacarlo del  
	match /post/{post}

	* **Daniel Esteves** (1)

		
		Si, totalmente correcto, lo puedes hacer de cualquiera de las dos maneras, la primera es mejor porque la regla es mucho más entendible

* **Lordpanther** (1)

	
	Seguridad, Seguridad Seguridad…

* **zkmark9999** (1)
Como se podría hacer para que no permita datos duplicados, ejemplo un post con el mismo título?

* **alexanderorellanam** (1)
¿Por que utiliza el comodin {post} sino lo utiliza en la regla?

* **Alejandro González Reyes** (1)
No entiendo la última regla. Se que el dueño del documento puede borrarlo o eliminarlo Pero es confuso ese request.resorce.data.email con...

	* **Alejandro González Reyes** (4)

		
		Me respondo a mi mismo jaja.  
		El email del docuemtno entrante debe ser identico al email documento existente.

* **joseadrian** (1)
seria correcto poner: match /post/{ allow list: if true } es decir, sacarlo del match /post/{post}

	* **Daniel Esteves** (1)

		
		Si, totalmente correcto, lo puedes hacer de cualquiera de las dos maneras, la primera es mejor porque la regla es mucho más entendible

* **Marcos Galaviz** (0)

	
	list y read hacen lo mismo?

	* **Damián Mateo Nuñez** (3)

		
		Una regla read se puede desglosar en get y list, mientras que una regla write se puede desglosar en create, update y delete

## 0210. Índices

### Descripción:


Los **índices** son la capacidad de consultar nuestra información mucho más rápido ya que, calculamos la ubicación exacta de nuestro contenido en vez de recorrer la base de datos hasta encontrar la información. Gracias a los índices podemos realizar búsquedas especiales con múltiples filtros y ordenamientos a las peticiones de nuestra aplicación con Firestore sin afectar el _performance_ y la velocidad de nuestra aplicación.

### Links:

* [Index types in Cloud Firestore  |  Firebase](https://firebase.google.com/docs/firestore/query-data/index-overview)

### Comentarios:

* **programanime** (3)

	
	Excelente curso!!

* **Lordpanther** (1)

	
	Esto de los indices es bastante útil en las bases de datos NOSQL

* **Eden Gomez Gress** (1)

	
	Buen dia Comunidad, tengo estos errores y no se porque se generaron, talvez sean por las reglas de seguriudad. Alguien que me pueda orientar?
	
	![](https://snag.gy/CFUWLE.jpg)
	
	Este es otro:
	
	![](https://snag.gy/m34PDO.jpg)

	* **Enrique Alexis Lopez Araujo** (6)

		
		Hola @edengg si esos errores se generan por como se esta guardando el link del video, te recomiendo que cuando copies el link de youtube, sigas estos sencillos pasos mira:
		
		1.- Entras a youtube  
		2.- En la opcion de compartir, elegis la opcion de incorporar  
		3.- Te va a dar todo el siguiente codigo:
		``` 
		    <iframewidth="560" height="315" src="https://www.youtube.com/embed/RdnPAOA6qfw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		    
		```
		
		4.- Pero realmente el que vamos a utilizar sera:
		``` 
		    https://www.youtube.com/embed/RdnPAOA6qfw
		    
		```
		
		5.- Si te das cuenta se agrega la palabra `embed` antes del codigo de video con eso vas a poder utilizar los links de youtube para poder insertarlo.
		
		6.- Cualquier duda no dejes de seguir comentando.

	* **Eden Gomez Gress** (2)

		
		Muchas gracias companero me sirvio tu metodo !!!

* **Eden Gomez Gress** (1)
Buen dia Comunidad, tengo estos errores y no se porque se generaron, talvez sean por las reglas de seguriudad. Alguien que me pueda orien...

	* **Enrique Alexis Lopez Araujo** (6)

		
		Hola @edengg si esos errores se generan por como se esta guardando el link del video, te recomiendo que cuando copies el link de youtube, sigas estos sencillos pasos mira:
		
		1.- Entras a youtube  
		2.- En la opcion de compartir, elegis la opcion de incorporar  
		3.- Te va a dar todo el siguiente codigo:
		``` 
		    <iframewidth="560" height="315" src="https://www.youtube.com/embed/RdnPAOA6qfw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		    
		```
		
		4.- Pero realmente el que vamos a utilizar sera:
		``` 
		    https://www.youtube.com/embed/RdnPAOA6qfw
		    
		```
		
		5.- Si te das cuenta se agrega la palabra `embed` antes del codigo de video con eso vas a poder utilizar los links de youtube para poder insertarlo.
		
		6.- Cualquier duda no dejes de seguir comentando.

* **Davidalvarado08** (0)
¿Alguien sabe si puedo traer los datos de diferentes colecciones haciendo solo una consulta?

	* **Juan David Castro (Platzi)** (2)

		
		No podemos ejecutar consultas a más de una colección: <https://stackoverflow.com/questions/54123542/how-do-i-get-data-from-two-collections-in-firestore>.
		
		Pero, tal vez, las transacciones y escritura por lotes te pueden ayudar en algunos casos: <https://firebase.google.com/docs/firestore/manage-data/transactions>.

# Almacenamiento de archivos

## 0220. Almacenamiento de Archivos en Firebase

### Descripción:


El servicio de Firebase Storage nos permite almacenar archivos, vídeos e imágenes con alta disponibilidad y redundancia global, es decir, nuestros archivos se multiplican automáticamente por múltiples regiones y centros de datos para agilizar las consultas de nuestros archivos.

Entre sus características podemos resaltar la gestión de problemas de red _(pausar la subida de imágenes y reactivarla cuando tenemos mejor internet)_ , sus buenas prácticas de seguridad _(también podemos podemos crear reglas de seguridad para estos archivos)_ , el soporte para operaciones robustas y su escalabilidad.

El plan gratuito de Firebase Storage nos permite guardar hasta 5GB de información, 1GB de descargas diarias, entre otras cosas, si nuestra aplicación supera estos límites podemos acceder al plan de pago por uso.

### Comentarios:

* **Juan David Castro (Platzi)** (6)

	
	¿El servicio de Cloud Storage es el equivalente al S3 de AWS? ¿Que diferencias o ventajas obtenemos al usar alguna de estas herramientas en vez de la otra? 🤔

	* **jggomezt** (6)

		
		Hola, no conozco el servicio de AWS, pero el servicio de storage no es algo complejo, creo que la diferencia puede estar en los SDKs o APIs, su facilidad de uso y la integridad con los demás servicios, ya que los dos brindan alta escalabilidad, alta disponibilidad y su costo es similar.

	* **Daniel Esteves** (4)

		
		¡Hola Juan! Te comento que vendrían siendo lo mismo 🤩 a diferencia de S3 el SDK de Cloud Storage es muchísimo más fácil de implementar 🙌

	* **Juan Carlos Rueda Diaz** (1)

		
		si

* **Juan David Castro (Platzi)** (2)
¿El servicio de Cloud Storage es el equivalente al S3 de AWS? ¿Que diferencias o ventajas obtenemos al usar alguna de estas herramientas ...

	* **jggomezt** (6)

		
		Hola, no conozco el servicio de AWS, pero el servicio de storage no es algo complejo, creo que la diferencia puede estar en los SDKs o APIs, su facilidad de uso y la integridad con los demás servicios, ya que los dos brindan alta escalabilidad, alta disponibilidad y su costo es similar.

* **Jose Manuel Salazar** (1)

	
	Alguien sabe si el proyecto está en algún repositorio?

	* **FranLop84** (1)

		
		Es este.
		
		<https://github.com/jggomez/blogeek-platzi>

## 0230. Subiendo archivos de nuestro blog

### Descripción:


### Links:

* [Upload Files on Web  |  Firebase](https://firebase.google.com/docs/storage/web/upload-files)

* [Download Files on Web  |  Firebase](https://firebase.google.com/docs/storage/web/download-files)

### Comentarios:

* **Carlos Mata** (3)

	
	Si te sale “firebase.storage is undefined” yo lo solucione agregando en index.html
	``` 
	    <scriptsrc="https://www.gstatic.com/firebasejs/5.5.2/firebase-storage.js"></script>
	    
	```
	
	y en ConfigFirebase.js agregue el storageBucket que te lo proporciona el panel de firebase una vez activando el storage

* **Jorge Ivan Henao Restrepo** (2)

	
	Hola, luego de ver el video de subir archivos a firebase quisiera saber que es mejor entre subir un archivo a firebase o convertir el archivo base 64 y colocarlo como un campo de un documento?

	* **JuanDAC** (2)

		
		En mi caso tenia un sistema que utilizaba fotos de los perfiles de los trabajadores y este subía dichas en base64 para mayor facilidad al programar el sistema en primera instancia pero después nos topamos con el problema de que dichas imágenes las necesitábamos para otro programa que generaba las firmas de email pero como lo que nos traía era el texto en base64 la firma quedaba muy pesada y el gestor de correo no dejaba subir la firma.  
		En resumen es mejor tener la imagen subida y no la base64 aunque eso depende de la flexibilidad y expansión que pueda tener tu proyecto.

* **Carlos Ignacio Gumucio Labbé** (2)

	
	Hola, sucede que mis posts se crean y mi archivo (imagen en este caso) se sube a el storage de firebase, pero en el thumbnail del post no se muestra la imagen, en la consola solamente me dice esto.
	
	post.js:41 Uncaught TypeError: Cannot read property ‘toDate’ of null  
	at post.js:41  
	at database.ts:1993  
	at document_set.ts:97  
	at o.inorderTraversal (sorted_map.ts:319)  
	at o.inorderTraversal (sorted_map.ts:320)  
	at n.inorderTraversal (sorted_map.ts:136)  
	at o.forEach (document_set.ts:96)  
	at e.forEach (database.ts:1992)  
	at Object.next (post.js:34)  
	at next (database.ts:1819)  
	at async_observer.ts:51
	
	@firebase/firestore: Firestore (6.4.0):  
	The timestampsInSnapshots setting now defaults to true and you no  
	longer need to explicitly set it. In a future release, the setting  
	will be removed entirely and so it is recommended that you remove it  
	from your firestore.settings() call now.

	* **Daniel Esteves** (1)

		
		¡Hola! Eso quiere decir que necesitas borrar la configuración de timestampsInSnapshots que creaste en el archivo de configuración de Firebase ya que lo trae por defecto en las nuevas versiones

* **dcortesnet** (2)

	
	Y cómo descargo el archivo?

	* **mariandrea (Platzi)** (1)

		
		hola, lo encuentras en la pestaña Recursos

* **Alejandro Daniel Oroncoy Almeyda** (1)

	
	Si sale un mensaje de error con el mensaje “firebase.storage is undefined” solo es cuestion de escribir bien el cdn o sdk asi que dejare el script para que todo funcione con normal
	``` 
	    <scriptsrc="https://www.gstatic.com/firebasejs/7.12.0/firebase-storage.js"></script>
	    
	```

* **Alejandro González Reyes** (1)

	
	Existe alguna forma de aplicar transacción a estas activades?.  
	Es decir, revertir la tarea de registro o subida si algunas de estas no se lleva a cabo correctamente

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Hola, encontré esta información sobre transacciones con Firebase <https://firebase.google.com/docs/firestore/manage-data/transactions>

* **joseadrian** (1)

	
	Que pasa si al final el usuario cancela la creación del post o no queria subir esa imagen, estariamos almacenando la imagen que no seria util/necesaria

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Una opción es no hacer la subida hasta que el post no sea creado, adicionalmente cuando un blog se borre revisar la o las imágenes asociadas y borrarlas del sistema de archivos.

* **tinguinito** (1)

	
	no entiendo el sessionStorage para que se usa? y no entiendo como lo usa para guardar la url a la bd?

	* **Gerardo Manuel Reyes Fernández** (1)

		
		Es verdad al parecer no lo usa solo lo setea  
		![](https://i.giphy.com/media/rfDOmR09atTkQ/giphy-downsized.gif)

	* **cetasi** (1)

		
		Lo que sucede es que: el guarda la url en el sessionStorage para que cuando el componente post sea renderizado, lea los session storage y sea el quien envia para la base de datos.
		
		El podria hacer eso directamente en ese codigo, pero decidio dejarle ese trabajo a otro componente.

	* **David Farinango** (1)

		
		Es una forma de conectar el firestore con el storage y poder mostrar la imagen de cada post creado, ya que si no se hace el sessionStorage.setItem(‘imgNewPost’, downloadURL) nos mostrara null en cualquier post creado asi se suba la imagen respectiva 😄

	* **David Behar** (1)

		
		Sí, pero en ningún momento obtenemos el sessionStorage de ningún lado, ya busqué por todos lados y nada, no usamos el sessionStorage para nada en todo el proyecto, a menos que me haya perdido de algo

* **Lordpanther** (1)

	
	Muy bien explicado.

* **Alejandro González Reyes** (1)
Existe alguna forma de aplicar transacción a estas activades?. Es decir, revertir la tarea de registro o subida si algunas de estas no se...

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Hola, encontré esta información sobre transacciones con Firebase <https://firebase.google.com/docs/firestore/manage-data/transactions>

## 0240. Reglas de seguridad para el almacenamiento

### Descripción:


Así como las reglas de seguridad de la base de datos en Firestore, el servicio de Firebase Storage nos permite limitar el acceso de los usuarios a ciertos archivos especiales de la aplicación. Todas las reglas de seguridad en cualquier servicio de Firebase se escriben de la misma manera.

En esta clase vamos a limitar la subida de archivos a usuarios autenticados y solo permitir el almacenamiento si los archivos son de tipo imagen u ocupan menos de 5 megas de almacenamiento:
``` 
    match /imgPosts/{userId}/{imgId} {
            allow write: if request.resource.size < 5 * 1024 * 1024
                    && request.resource.contentType.matches('image/.*')
                    && request.auth.uid != null
                    && request.auth.uid == userId
    }
    
```

### Links:

* [Understand Firebase Security Rules for Cloud Storage  |  Firebase](https://firebase.google.com/docs/storage/security/)

### Comentarios:

* **George_18** (2)

	
	¿Como puedo quitar el error de? :
	
	**has been blocked by CORS policy: No ‘Access-Control-Allow-Origin’ header is present on the requested resource. If an opaque response serves your needs, set the request’s mode to ‘no-cors’ to fetch the resource with CORS disabled.**

	* **Wonder Jhonny Diaz Gonzalez** (2)

		
		Hola,
		
		Eso es un error del CORS o Cross-origin resource sharing. Hay documentacion en el que puedes profundizar mas en el tema. Algunas soluciones:
		
		En desarrollo puede utilizar una extension de Google Chrome llamado **Moesif Orign & CORS Changer** y asi pruebas que los datos se estan enviando y recibiendo.
		
		Desde **Node** puedes descargar el paquete de **NPM** de **cors** y configurarlo segun la documentacion. Para otros lenguajes hay distintas rutas
		
		En esta pagina de explica como evitar el bloqueo sin configurar el servidor <https://cors-anywhere.herokuapp.com/> anteponiendo el mismo enlace.
		
		Saludos

	* **JuanJo** (1)

		
		En la documentación de firebase existe como configurar CORS. A mi me paso un error similar al intentar descargar por URL un archivo en Storage. Hay varias formas de solucionarlo, pero lo que yo hice es configurar mi proyecto en el Google Cloud SDK. Simplemente segui los pasos que indican desde el siguiente link:
		
		<https://firebase.google.com/docs/storage/web/download-files#cors_configuration>
		
		Suerte.

* **Alejandro González Reyes** (2)

	
	¿Porque en storage aunque las reglas estén definidas solo para usuarios autenticados, las imagenes de los post se siguen visualizando aunque este sin logearme?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Hola puedes comprtir las reglas que tienes definidas para ver si es un problema con la definición de alguna de ellas.

	* **Daniel Esteves** (1)

		
		¡Hola! El compañero Eden publicó la imagen de las reglas de cómo deben estar escritas, ¿podrías comprar con sus reglas a ver si tienes algún typo a ver si son lo mismo o hay algún error?

	* **Jeffersson Muñoz Torres** (1)

		
		Porque la primera regla que se escribe donde esta el parametro “read” tiene if true , lo que significa que siempre sera verdadero , es decir, que practicamente no tiene condicion. Las que tienen las reglas de autenticacion es solo el parametro de “write”. Es por eso que puedes ver todos las imagenes del post aunque no estes autenticado puedes vizualizarlas.

* **Eden Gomez Gress** (2)

	
	Buen dia companeros, segui el ejemplo de las reglas de firebase storage pero no me deja subir nada, aun estando auntenticado:
	
	![](https://snag.gy/PMbXZf.jpg)
	
	Estas son las reglas:
	
	![](https://snag.gy/8BiKQw.jpg)

	* **Eden Gomez Gress** (2)
![](https://snag.gy/8BiKQw.jpg)

	* **jggomezt** (1)

		
		Hola, no veo las reglas

	* **jggomezt** (1)

		
		Las reglas en la consola de Firebase

	* **Enrique Alexis Lopez Araujo** (1)

		
		Me acaba de aparecer el mismo error las reglas que tengo publicadas en el storage son las siguientes:
		``` 
		    service firebase.storage {
		      match /b/{bucket}/o {
		        match /imgPosts/{allPaths=**} {
		          allow read:iftrue
		        }
		        match /imgPosts/{userId}/{imgId}{
		        	allow write:if request.resource.size < 5 * 1024 * 1024
		          			&& request.resource.contentType.matches('image/.*')
		                && request.auth.uid != null
		                && request.auth.uid == userId
		        }
		      }
		    }
		    
		```

	* **jandrey** (1)

		
		Yo tenia matchs en ves de matches…
		``` 
		    && request.resource.contentType.matches('image/.*')
		    
		    
		```

* **Luis Rangel Castro** (1)

	```
	    rules_version = '2';
	    service firebase.storage {
	      match /b/{bucket}/o {
	        match /imgsPosts/{allPaths=**} {
	          allow read:iftrue;
	        }
	        match /imgsPosts/{userId}/{imgId} {
	            allow write:if request.resource.size < 5 * 1024 * 1024
	                    && request.resource.contentType.matches('image/.*')
	                    && request.auth.uid != null
	                    && request.auth.uid == userId
	    		}
	      }
	    }
	    
	```

* **Eden Gomez Gress** (1)
![](https://snag.gy/Bb4Pf3.jpg)

* **Alejandro González Reyes** (1)
¿Porque en storage aunque las reglas estén definidas solo para usuarios autenticados, las imagenes de los post se siguen visualizando aun...

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Hola puedes comprtir las reglas que tienes definidas para ver si es un problema con la definición de alguna de ellas.

* **Eden Gomez Gress** (1)
Buen dia companeros, segui el ejemplo de las reglas de firebase storage pero no me deja subir nada, aun estando auntenticado: Estas son ...

	* **Eden Gomez Gress** (2)
![](https://snag.gy/8BiKQw.jpg)

# Hosting

## 0250. Qué nos brinda el Hosting de Firebase

### Descripción:


Firebase Hosting es el servicio que nos permite alojar aplicaciones web de contenido estático, es decir, nuestras aplicaciones solo puede contener archivos HTML, CSS y JS, nada de lenguajes de backend como PHP, WordPress, Python o Node.js.

Este servicio nos proporciona caché y CDNs _(multiples replicas de nuestras aplicaciones)_ , cifrado de nuestros datos con HTTPS y herramientas para realizar despliegues muy rápidos con multiples versiones de nuestra aplicación para utilizarlas cuando necesitemos.

### Links:

* [Firebase Hosting  |  Firebase](https://firebase.google.com/docs/hosting/)

### Comentarios:

* **Lordpanther** (3)

	
	Genial porque la seguridad podría ser lo ultimo en lo que deberíamos pensar ¿o no?..

	* **David Flores** (1)

		
		Google tiene buenas reglas de seguridad para sus herramientas, depende de nosotros habilitarlas o dejarlas por defecto, incluso cuando comienzas a usar un servicio de firebase te advierte que las reglas de seguridad están por defecto y son vulnerables

* **juanseg** (2)

	
	A día de hoy, Firebase ya permite desplegar varias páginas en un mismo proyecto sin necesidad de pagar 🎉🎉

* **Edgar Valdez Moises** (2)

	
	Buenas, que proveedores de dominio recomiendan para trabajar con firebase ?  
	Recuerdo ver en algún vídeo de Youtube que Freddy no recomienda GoDaddy

	* **IvanDev** (1)

		
		Hoy en día hay muchos proveedores, yo tengo hace ya varios años mis dominios con <http://www.namecheap.com/>, me parece un buen proveedor.

	* **Walter Ugalde A** (1)

		
		Digital Ocean

	* **Jorge Heli Rueda Uribe** (1)

		
		[](https://www.namecheap.com/) Namecheap es muy bueno y tiene muy buenos precios.

	* **David Flores** (1)

		
		Yo lo use un tiempo con Hostinger y funciona muy bien, al parecer todos los proveedores de dominio funcionan bien con firebase. Hace unos meses me migre a [Google Domains](https://domains.google/) y esta mucho más cool 😄

* **Kerohuixco** (2)

	
	Alguien sabe si en los hosting de fire base se pueden cargar paginas WEB con graficas en tiempo real.

	* **Gerardo Manuel Reyes Fernández** (3)

		
		si esa funcionalidad está hecha con js, seguro que si, puedes consultar apis y todo sockets, puedes tener un observador y cuando escuches datos actualize tu gráfica.

	* **David Flores** (1)

		
		Firestore almacena la información en tiempo real, si la data la traes desde este servicio, en automático se actualiza tu información.

* **David Flores** (1)

	
	El que puedas regresar a diferentes versiones deplegadas ayuda bastante por si la nueva versión no corre adecuadamente 😅

* **Yesid David Ghisays Martinez** (1)

	
	1&1

	* **David Flores** (1)

		
		Siempre existen diferentes opciones, pero firebase te permite escalar a soluciones mas potentes. Todo lo que hagas en firebase se agrega a tu cuenta de GCP (Google Cloud Platform)

* **Alejandro González Reyes** (1)

	
	Hoy en día es dificil diferenciar una aplicación dinámica desarrollada con Javascript o PHP.  
	Mejor decir aplicación desarrollada con tecnologías FrontEnd.

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Solo aclarar que PHP no es Frontend, es backend. El php se interpreta por el servidor web y renderiza html, pero no es como tal un lenguaje de Frontend.

	* **David Flores** (1)

		
		Firebase Hosting solo almacena sitios con html, css y js  
		Si quieres algo con php en Google te recomiendo el [learning path de Google](https://platzi.com/clases/learning-path/google-cloud/)

## 0260. Desplegando la app al hosting

### Descripción:


Firebase nos proporciona algunas herramientas de línea de comandos para desplegar nuestras aplicaciones. Para usar estas herramientas solo debemos ejecutar los siguientes comandos y seguir las instrucciones que encuentras a continuación:
``` 
    # Instalación:
    npm install -g firebase-tools
    
    # Login
    firebase login
    
    # Iniciar el proyecto
    firebase init
    # seleccionamos la opción "Hosting", buscamos el id de nuestro proyecto y seleccionamos las opciones de nuestros archivos estáticos
    
    # Desplegar nuestra aplcación
    firebase deploy
    
```

### Links:

* [Deploy Your Site  |  Firebase](https://firebase.google.com/docs/hosting/deploying)

* [Connect a custom domain  |  Firebase](https://firebase.google.com/docs/hosting/custom-domain)

### Comentarios:

* **Disando7** (3)

	
	Está mal el orden de los vídeos, este vídeo al anterior.  
	Este vídeo que es el 27, debería ser el 26 y el 26 debería ser el 27.

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Gracias por el reporte vamos a revisar y solucionar lo más pronto posible.

* **Carlos Mata** (3)

	
	Si en la consola te sale el error 401 al tratar **firebase use** or **firebase init** , se soluciona con **firebase logout** y luego otra vez **firebase login**

* **Diego Fernández Cruz** (2)

	
	Hay manera de ocultar el archivo que contiene las credenciales para conectarme a Firebase. Es decir ahora cuando utilizo las herramientas de desarrollo del navegador puedo visualizar ese archivo.

	* **Juan David Castro (Platzi)** (2)

		
		No necesitas ocultarlo. Todo en el frontend es público. Lo que puedes/debes hacer es configurar muy bien tus reglas de seguridad y dominios autorizados para que las credenciales solo funcionen en la IP de tu aplicación. 😉

	* **David Flores** (2)

		
		Todo lo que esta en el frontend es visible para todos, si no quieres que eso suceda, puedes usara firebase en node, pero como dice @juandc, las reglas de seguridad bien configuradas te ayudan ha evitar problemas

* **joseadrian** (2)

	
	Porque en el primero dice 0 archivos y en el segundo 37 O.o?!

	* **Andrés Felipe Chaparro Grimaldo** (1)

		
		Siempre demora unos cuantos segundos en tomar los cambios, pero si refrescas verás que aparece ya la cantidad de archivos que tenga tu proyecto

* **Lordpanther** (2)

	
	Excelente integración con nuestras aplicaciones. Una pregunta, ¿como podemos tener la url de acciones (Como password recovery etc… con nuestro dominio personalizado?)

	* **Daniel Esteves** (1)

		
		Puedes crear las páginas y en cada una de ellas vas a poner el código de JavaScript con el que ejecutarás esas funcionalidad

	* **David Flores** (1)

		
		Puedes crear las paginas para realizar las acciones y usar las funciones propias de firebase para realizar estas acciones.  
		Te dejo un link a al documentación 😄  
		[reset password](https://firebase.google.com/docs/auth/web/manage-users?hl=es#send_a_password_reset_email)

* **David Trespalacios** (1)

	
	Si al dar Error Hosting init, presenta error con el nombre del proyecto, es porque tiene un nombre distinto en tu consola. cambialo en el archivo .firebaserc del proyecto.  
	Me pasó porque tomé el repositorio completo yo usé otro nombre en FB.
	``` 
	    {
	      "projects": {
	        "default": "blocfbplatzi" //aquí coloca el nombre de tu id proyect de firebase
	      }
	    }
	    
	```

* **Baldan** (1)
Cuando escribo “firebase login” la consola me dice: _ firebase : El término ‘firebase’ no se reconoce como nombre de un cmdlet, función, ...

	* **Juan David Castro (Platzi)** (1)

		
		Eso significa que no todavía no se ha instalado Firebase en tu computadora. Puedes utilizar **`NPX`** o volver a instalar firebase globalmente con NPM.

* **Diego Fernández Cruz** (1)
Hay manera de ocultar el archivo que contiene las credenciales para conectarme a Firebase. Es decir ahora cuando utilizo las herramientas...

	* **Juan David Castro (Platzi)** (2)

		
		No necesitas ocultarlo. Todo en el frontend es público. Lo que puedes/debes hacer es configurar muy bien tus reglas de seguridad y dominios autorizados para que las credenciales solo funcionen en la IP de tu aplicación. 😉

* **joseadrian** (1)
Porque en el primero dice 0 archivos y en el segundo 37 O.o?!

	* **Andrés Felipe Chaparro Grimaldo** (1)

		
		Siempre demora unos cuantos segundos en tomar los cambios, pero si refrescas verás que aparece ya la cantidad de archivos que tenga tu proyecto

## 0270. Redirects, rewrites y headers

### Descripción:


Cuando desplegamos nuestras aplicaciones con Firebase Hosting necesitamos un archivo `firebase.json` donde podemos configurar la siguiente información:

  * **“public”** : Es el único campo obligatorio en este archivo, aquí debemos indicar la carpeta o directorio con nuestros archivos estáticos.
  * **“ignore”** : Muchos archivos y carpetas _(el directorio`node_modules`, por ejemplo)_ los necesitamos para trabajar en entornos de desarrollo, no para desplegar nuestra aplicación, podemos omitirlos y ahorrarnos algo de tiempo al subir las diferentes versiones del proyecto.
  * **“redirects”** : Podemos configurar algunas rutas de nuestra aplicación para que apunten a algún sitio web o a otra parte de nuestra aplicación.
  * **“rewrites”** : Así como los _redirects_ , podemos configurar algunas rutas o patrones de nuestra aplicación, pero en vez de cambiar la URL, vamos a seleccionar el archivo estático que debe aparecer en estas rutas especiales.



### Links:

* [Customize Hosting Behavior  |  Firebase](https://firebase.google.com/docs/hosting/url-redirects-rewrites)

### Comentarios:

* **Brian Bentancourt** (5)

	```
	    {
	      "hosting": {
	        "public": "public", 
	        "ignore": [
	          "firebase.json",
	          "**/.*",
	          "**/node_modules/**"
	        ],
	        "redirects": [
	          {
	            "source": "/posts",
	            "destination": "/",
	            "type": 301
	          }
	        ],
	        "rewrites": [ 
	          {
	            "source": "/**",
	            "destination": "/index.html"
	          }
	        ],
	        "headers": [ 
	          {
	            "source": "**/*.@(jpg|jpeg|gif|png)", 
	            "headers":[
	              {
	                "key": "Cache-Control",
	                "value": "max-age=7200"
	              }
	            ]
	          }
	        ]
	      }
	    }
	    
	```

* **Alvaro   Gonzalez** (2)

	
	Si quiero llamar a un api, externo, lo puedo hacer …?  
	/api --> <http://api.com>, que retorna datos json, etc.

	* **Juan David Castro (Platzi)** (6)

		
		Sii!! 🎉
		
		Puedes usar la configuración de `redirects` y mandar tu `/api` a la url real de tu API, lo que si no podemos es hacer `rewrites` para APIs externas o cosas así 😃. Más info aquí 👉 [Firebase hosting and external APIs - Stack Overflow](https://stackoverflow.com/questions/37696890/firebase-hosting-and-external-apis).

* **Alejandro González Reyes** (2)
Porque si tecleamos la url_proyecto/otracosa/mascosas nos muestra la página index.html pero sin estilos.

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Revisa que la ruta que esta llamando del css es la correcta.

* **David Flores** (1)

	
	Si quieren conocer mas a profundidad el tema, les dejo la documentación oficial  
	[Documentación firebase hosting](https://firebase.google.com/docs/hosting/quickstart)

* **Jose Vidal** (1)

	
	Esto es como una manera de configurar un .htaccess en el hosting de firebase, es interesante

* **Alejandro González Reyes** (1)

	
	Porque si tecleamos la url_proyecto/otracosa/mascosas  
	nos muestra la página index.html pero sin estilos.

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Revisa que la ruta que esta llamando del css es la correcta.

	* **David Flores** (1)

		
		Abre la consola del navegador, puede ser que no encuentre tu css en la ruta marcada

* **Jaime David Burbano Montoya** (1)
¿Hay algún video donde se hable de como conectar el dominio a mi hosting firebase?

	* **Edward Steven Ramos Palacios** (1)

		
		Aqui puedes ver el paso a paso: [Firebase](https://firebase.google.com/docs/hosting/custom-domain?hl=es-419)

# Notificaciones Push

## 0280. Qué son las notificaciones en Firebase y cómo es su arquitectura

### Descripción:


El servicio de Cloud Messaging de Firebase nos permite enviar mensajes al navegador en forma de _push notifications_ sin ningún costo. Recuerda que los usuarios deben aceptar que quieren recibir notificaciones de tu aplicación y podemos entregar estos mensajes desde la aplicación cuando el usuario tiene la aplicación abierta o en forma de notificación nativa del sistema operativo cuando nuestra aplicación esta inactiva.

### Links:

* [Set up a JavaScript Firebase Cloud Messaging client app  |  Firebase](https://firebase.google.com/docs/cloud-messaging/js/client)

* [About FCM messages  |  Firebase](https://firebase.google.com/docs/cloud-messaging/concept-options)

* [Cloud Functions para Firebase  |  Firebase](https://firebase.google.com/docs/functions/?hl=es-419)

### Comentarios:

* **Lordpanther** (4)

	
	No hay que abusar de las notificaciones, a veces resulta contraproducente 😃

* **Spartan** (2)

	
	para que mi sitio pueda ser accedido desde móviles y en modo incógnito que pasos debería seguir, actualmente tengo uno pero solo me carga si estoy logueado con la cuenta de google de mi consola de firebase.  
	Gracias

	* **Daniel Esteves** (1)

		
		¡Hola! ¿Seguiste los pasos de la clase anterior?

* **David Behar** (1)

	
	Curso de cloud functions en platzi <https://platzi.com/clases/firebase-cloud/>

## 0290. Implementando las notificaciones en el proyecto

### Descripción:


### Links:

* [Service Workers: an Introduction  |  Web Fundamentals       |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)

### Comentarios:

* **iamyoujared** (7)

	
	En @firebase/firestore: Firestore (6.2.2)  
	El timestampsInSnapshots ya viene por default true ya no es necesario agregarlo bros!

* **JOSE ESTRADA** (4)

	
	¿el gcm_sender_id puede ser cualquier numero? ¿O lo podemos obtener desde la consola de Firebase?

* **David Trespalacios** (2)

	
	Si alguien le sale error de permisos para guardar en la base de datos el token, lo solucioné agregando la regla:
	``` 
	     match /tokens/{doc}{
	        allow write, read : iftrue;
	        }
	    
	```

* **Luis Eduardo Figueroa** (2)
El orden del vídeo está mal, primero va este vídeo que el anterior.

* **JuanJo** (1)

	
	En el archivo manifest.json ese numero de donde se lo obtiene?

* **joseadrian** (1)

	
	js trabaja de forma async o solo son las librerias de firebase o solo es impresion mia.

	* **hector_pulido_** (1)

		
		Todo JS esta hecho para trabajar de forma Asincrona, es lo mejor en la web

* **georgeCode** (1)
Si quisiera enviar un mensaje como notificación desde mi aplicación web pero hacia aplicaciones móviles, como lo podría hacer?

	* **Juan David Castro (Platzi)** (1)

		
		Por lo que pude investigar, Firebase solo soporta notificaciones web. Para crear notificaciones en aplicaciones móviles supongo que deberás programar el código necesario para cada sistema operativo móvil.

## 0300. Agregar funciones para recibir las notificaciones

### Descripción:


Cuando los usuarios salen de nuestra página, refrescan la caché o cierran el navegador, debemos obtener el nuevo token de notificaciones y volver a guardarlo en la base de datos utilizando el método `firebase.messaging().onTokenRefresh`.

También vamos a configurar nuestro service worker para recibir notificaciones cuando el usuario no esta utilizando nuestra aplicación. Para esto, solo debemos utilizar el método `firebase.messaging().setBackgroundMessageHandler()` y registrar el título, texto, icono y la url que queremos abrir cuando los usuarios den click en la notificación con el método `self.registration.showNotification()`.

### Comentarios:

* **joseadrian** (2)

	
	No se puede utilizar el archivo ConfigFirebase.js

	* **Julio J Yépez** (2)

		
		El archivo ConfigFirebase.js solo contiene las variables de configuración / Credenciales … puedes colocarlas directo en el script principal o en el html dentro de un tag script. Para probar …

* **joseadrian** (2)

	
	Me gusta este estilo de programación aunque creo que será dificil adaptarme.

* **joseadrian** (2)
No se puede utilizar el archivo ConfigFirebase.js

	* **Julio J Yépez** (2)

		
		El archivo ConfigFirebase.js solo contiene las variables de configuración / Credenciales … puedes colocarlas directo en el script principal o en el html dentro de un tag script. Para probar …

## 0310. Probando las notificaciones desde la aplicación

### Descripción:


### Links:

* [Send your first message to a backgrounded app  |  Firebase](https://firebase.google.com/docs/cloud-messaging/js/first-message)

* [GitHub - jggomez/blogeek-platzi-functions](https://github.com/jggomez/blogeek-platzi-functions)

### Comentarios:

* **Engels Prado** (5)

	
	El curso iba genial hasta este punto en donde nadie sabe donde estan las funciones! Que decepcion

	* **Daniel Esteves** (1)

		
		¡Hola Engels! Recuerda que este curso se trata sobre Firebase para la web y el código de las functions se hace en el curso de Cloud Functions

* **Wilson Marino Pablo Mendez** (4)

	
	Venia todo bien 😐 hasta que llegue acá 😱 y me perdí

	* **Daniel Esteves** (1)

		
		¡Hola Wilson! Recuerda que este curso se trata sobre Firebase para la web y el código de las functions se hace en el curso de Cloud Functions

* **Andrés Mauricio Montoya Sánchez** (4)

	
	En qué momento se crearón esas funciones? En el listado de vídeos no se encuentra…

	* **Saul Burgos Davila** (1)

		
		La creación de functions no es parte de este curso por eso creo que no sale la creación

	* **Andrés Mauricio Montoya Sánchez** (3)

		
		Entonces considero que esta mal, ya que están enseñando algo que nunca se vio. Entiendo que el curso de cloud functions habla de esto, pero por lo menos deberían hacer una excepción explicando la funcionalidad de estas funciones.

	* **Daniel Esteves** (1)

		
		¡Hola! Ya que estas funciones no son parte del curso se tomaron del curso de Cloud Functions que también corresponden a la carrera de Firebase 🤓

* **Andrés Felipe Chaparro Grimaldo** (4)

	
	Acá les dejo a los que necesiten el repositorio con el código y las instrucciones para generar las **cloud functions** : [Repo](https://github.com/Dyabel03/blog-geek-firebase-functions).

* **Oscar Torres** (4)

	
	Las funciones están aqui…
	
	[funciones blogeek-platzi](https://github.com/jggomez/blogeek-platzi-functions)

	* **Andrés Felipe Chaparro Grimaldo** (2)

		
		Las funciones que se utilizan en este video no son esas, esas son del siguiente curso

* **fernandolc** (2)

	
	Entiendo que las Cloud Fuctions no son parte de este curso, entiendo que la función registratTopico se encarga de asociar el token con el tópico NuevosPosts.
	
	por lo que investigue unsubscribeFromTopic nos sirve para quitar la asociación del token con el tópico ya intente aguregar una funcion que escuche cuando elimine un token pero no he tenido éxito me podrían ayudar si es que estoy haciendo algo mal
	``` 
	    exports.eliminarTopico = functions.firestore.document( '/tokens/{id}' ).onDelete( dataSnapshot => {
	    
	        constTOKEN = dataSnapshot.data().token;
	    
	        const REGISTRATION_TOKENS = [ TOKEN ];
	    
	        // Eliminamos el token del topico o tema
	        return admin.messaging().unsubscribeFromTopic( REGISTRATION_TOKENS, 'NuevosPosts' )
	    
	        .then( () => { return console.log( 'Se elimino el Token correctamente => ', REGISTRATION_TOKENS ) } )
	    
	        .catch( error => { console.log( 'Error al eliminar el token', error ) } )
	    
	    } )
	    
	```

	* **Daniel Esteves** (1)

		
		¡Hola! Antes de seguir con esta parte del curso sería mucho mejor empezar a tomar el de Cloud Functions y luego volver a retomar desde aquí, te aseguro que no te arrepentirás 💪

* **joseadrian** (2)

	
	siento que ese codigo del topico aparecio magicamente 😦

* **Eden Gomez Gress** (2)

	
	Saludos companeros, tengo problemas para instalar las Functions. Me arroja este error:
	
	![](https://snag.gy/d9FBJh.jpg)

	* **jggomezt** (1)

		
		Realiza el despliegue afuera de la carpeta functions

	* **Eden Gomez Gress** (1)
![](https://snag.gy/vWy5zI.jpg)
		
		Ya lo hice y me sigue arrojando el mismo error!

	* **jggomezt** (1)

		
		Hola, que sistema operativo usas?? yo use windows para ello, a veces se tiene problema con el lint por ello. Puedes quitar la validación del lint, en el firebase.json

* **Brian Bentancourt** (2)

	
	que se supone que tenemos que poner aca?
	``` 
	    const claveapihubspot = functions.config().configuration.claveapihubspot
	    
	```

	* **jggomezt** (2)

		
		Hola, de donde tomaste esa linea de código?? eso es parte del curso de cloud functions

	* **Brian Bentancourt** (1)

		
		lo saque de tu repositorio [github](https://github.com/jggomez/blogeek-platzi-functions/blob/85f11f6eea55a2ec213390637636a970ecdb4c7f/functions/componentes/utilidad/HubSpotHelper.js)  
		lo descargue para implementarlo como en el video para poder enviar notificaciones pero me dio error ahi y en otros lados mas.

	* **jggomezt** (1)

		
		Es que esas functions cambiaron para el nuevo curso de cloud functions

* **Alejandro González Reyes** (1)

	
	Team Platzi  
	Me pueden proporcionar las funciones porque no aparecen en ningun lado

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Hola, aquí las encuentras <https://github.com/jggomez/blogeek-platzi-functions>

* **Andres Leon** (1)
Las funciones del repositorio están incompletas… y no se dejan subir 😦

	* **jggomezt** (2)

		
		Hola, que error te sale??

* **Alejandro González Reyes** (1)
Team Platzi Me pueden proporcionar las funciones porque no aparecen en ningun lado

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Hola, aquí las encuentras <https://github.com/jggomez/blogeek-platzi-functions>

* **Eden Gomez Gress** (1)
Saludos companeros, tengo problemas para instalar las Functions. Me arroja este error:

	* **jggomezt** (1)

		
		Realiza el despliegue afuera de la carpeta functions

* **Brian Bentancourt** (1)
que se supone que tenemos que poner aca? const claveapihubspot = functions.config().configuration.claveapihubspot 

	* **jggomezt** (2)

		
		Hola, de donde tomaste esa linea de código?? eso es parte del curso de cloud functions

# Conclusiones

## 0320. Conclusiones

### Descripción:


Durante las clases anteriores integramos Firebase con nuestra aplicación web, aprendimos a autenticar usuarios con redes sociales o email y password, insertamos y actualizamos datos de todas las formas permitidas en Firestore, configuramos índices para realizar consultas especiales y mejorar su velocidad, guardamos archivos estáticos en el servicio de Storage y añadimos reglas de seguridad para limitar el acceso a datos especiales de los usuarios, también desplegamos nuestra aplicación al servicio de Hosting y aprendimos a enviar notificación incluso cuando los usuarios no están utilizando la aplicación.

¡Felicitaciones por terminar el Curso de Firebase para Web! Recuerda tomar el examen del curso y hacer todas las preguntas para no dejar ninguna duda sin resolver.

### Comentarios:

* **marcelo.lavizzari** (5)

	
	Me encanto, muy buen curso, muy bien explicado los conceptos, los ejemplos, y los ejercicios propuestos, que se dieron en cada una de las clases. Yo creo que da ,segurisimo, para un curso avanzado, en donde se toque por ejemplo las cloud function, con más profundidad. Ejemplo, las imagenes que subamos, usar una cloud function , con cloud vision, o alguna function para curar los mensajes, o tagear los mensajes. Muchas gracias Juan Gomez.

	* **Marcos Galaviz** (3)

		
		Totalmente de acuerdo que falta uno mas avanzado, que incluya mas configuraciones y ejemplos de seguridad

	* **Juan David Castro (Platzi)** (3)

		
		Para eso está el [Curso de Firebase Cloud Functions](https://platzi.com/cursos/firebase-cloud/) 😉.

* **juan24_14** (2)

	
	El examen me recordo a la uni… tiene contenido no dictado en el curso como por ejemplo analitics

* **Luis Eduardo Figueroa** (2)
Me gustó el curso, excelente profesor. Quiero aplicar los conocimientos adquiridos para trabajar con react native.

* **LocoDarwin** (2)
Profe, estoy compilando con ionic 5 y capacitor, para crear una app de android, mi pregunta es: para instalar (es necesario ?) google-ser...

* **Nagcely Mendoza** (1)

	
	Excelente curso para gestionar nuestros proyectos desde firebase.

* **Elvis Serrano** (1)

	
	Me encanto el curso, aún tengo dudas al respecto pero ya espero solventarlas en los próximos cursos, muchas gracias.

* **masuro** (1)

	
	Excelente curso me a gustado bastante.

* **Andrés Felipe Chaparro Grimaldo** (1)

	
	Muy buen curso!..sigue el de functions 😄

* **Diego Fernández Cruz** (1)

	
	Mouy buen curso. Muy clara la explicación de todo. Excelente profe!

* **joseadrian** (1)

	
	Excelente curso, excelente profesor, esperamos mas cursos de esta calidad

