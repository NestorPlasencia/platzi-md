[Curso de Celery 1549](https://platzi.com/cursos/celery)

# Bienvenida [3813]

## 0010. Celery ¿Qué es, para qué sirve, cómo se usa [19024](https://platzi.com/clases/1549-celery/19024-celery-que-es-para-que-sirve-como-se-usa/)

### Descripción:


 **Celery** es una biblioteca en Python para gestionar colas de tareas distribuidas. Es software libre y está liberado con una licencia **BSD**. Cuenta con con más de diez mil _commits_ en este momento en Github.

No es la única. Tiene ciertos equivalentes en otros lenguajes, pero no hay ninguna que sea igual

**Ventajas**

* Escabilidad
* Eficiencia
* Orden de transacciones garantizado
* Resistencia a fallos
* Aguantar picos de mensajes



**Sirve para**

* Dividir el Backed de una aplicación en receptor y realizadores de tareas
* Uniformizar la respuestas del backend
* Crear arquitecturas de microservicios



### Comentarios:

* **Agusitn Machiavello** (12) [590186](https://platzi.com/comentario/590186/) 

	Pensé que estaba en velocidad x1.25 jaja

	* **Ernesto Vizcaíno Alvarado** [590186] (7)

		Ponlo en 0.85x

	* **Francisco Soto** [590186] (1)

		XD

	* **rulobars** [590186] (1)

		Tienen razon 0.85x es la velocidad correcta.

	* **estebansolorzano** [590186] (1)

		El anterior curso lo vi con 1.5 y paso a este y ya no entendi nada

* **Mauricio Chávez Olea** (9) [552630](https://platzi.com/comentario/552630/) 

	Celery es una gran biblioteca, sin embargo, en mi experiencia, hay casos en los que perjudica más de lo que ayuda, si bien empresas grandes lo ocupan porque tienen los recursos, a veces hay proyectos pequeños que intentan usarlo y terminan por consumir muchos de los recursos del servidor. Hay que usarla con cuidado si de un proyecto pequeño se trata.

	* **Julio J Yépez** [552630] (2)

		Interesante observación @imbrianstorm.  
		¿Tuviste oportunidad de usar Celery en alguno de tus proyectos?  
		¿Qué recursos son los que más pudiera consumir Celery?

	* **JJ Merelo Guervós** [552630] (1)

		Siempre depende de lo que quieras hacer. Celery es una biblioteca compleja, pero por eso precisamente a un plazo medio o largo siempre va a beneficiar a la empresa. Evidentemente, por el cambio de concepto respecto a una arquitectura monolítica puede que al principio el diseño y la implantación tarden algo de tiempo.

* **Juan Pena Verdú** (3) [553193](https://platzi.com/comentario/553193/) 

	<http://www.celeryproject.org/>

* **lucas-alvarez124** (2) [573858](https://platzi.com/comentario/573858/) 

	¿Para qué sirve?

	* **Diego Alexander Forero Higuera (Platzi)** [573858] (2)

		Es un librería para encolar tareas, un uso muy común es por ejemplo cuando tienes que hacer procesos largos luego de una acción del usuario, entonces mandas esos procesos a la cola de tareas y no detienes a tu usuario esperando a que todo el bloque de tareas se termine.

* **KarlxS** (2) [552041](https://platzi.com/comentario/552041/) 

	Estoy iniciando mi aprendizaje con la programación backend con javascript, Esta librería la puedo usar?

	* **Julio J Yépez** [552041] (1)

		En las clases finales de este curso el profesor nos habla de las posibilidades de usar Celery con otros lenguajes, incluido Node.JS

	* **JJ Merelo Guervós** [552041] (4)

		node-celery funciona perfectamente, tanto para repartir como para ejecutar tareas. <https://github.com/mher/node-celery>  
		Sin embargo, en un entorno de microservicios distribuidos puedes usar diferentes lenguajes, siempre el más adecuado para cada cosa. Te animo a que eches un vistazo a Python; aunque fuera solo por este framework, merece la pena.

* **harbarnard** (1) [618071](https://platzi.com/comentario/618071/) 

	disculpa en el tema de java ? hay algo parecido ?

	* **Diego Alexander Forero Higuera (Platzi)** [618071] (1)

		Hola, encontré este <https://github.com/cscotta/Octobot> pero es un proyecto que no esta mantenido hace varios años.  
		Encontré también estos proyectos <http://www.quartz-scheduler.org/><https://github.com/gresrun/jesque>

	* **william andres rodriguez borja** [618071] (1)

		spring cloud para spring boot permite gestionar rabbitMQ o los demas MQ ademas tiene spring gateway como receptor de tareas y administrador de microservicios con Zuul como gateway Spring Oauth para JWT auth etc etc registry , balanceador de carga etc etc en resume todo lo que son micro servicios.

* **KarlxS** (1) [56387](https://platzi.com/comentario/552041/) 
Estoy iniciando mi aprendizaje con la programación backend con javascript, Esta librería la puedo usar?

	* **Julio J Yépez** [56387] (1)

		En las clases finales de este curso el profesor nos habla de las posibilidades de usar Celery con otros lenguajes, incluido Node.JS

## 0020. Repositorio del proyecto [19944](https://platzi.com/clases/1549-celery/19944-repositorio-del-proyecto/)

### Descripción:


Te doy la bienvenida a este nuevo curso de Celery. En este curso aprenderás todo lo necesario para dominar Celery a un nivel profesional.

A continuación te comparto el repositorio del curso, donde encontrarás el proyecto y todo lo necesario para el desarrollo curso. Este repositorio está divido por **tags** con su respectivo número de clase. Puedes clonarlo o descargarlo, como te resulte más cómodo.

[**Repositorio en GitHub**](https://github.com/JJ/celery-platzi-clases/tags/)

O bien, puedes darle un vistazo por _commits_ :

[**Repositorio por _commits_**](https://github.com/JJ/celery-platzi-clases/commits/)

De ambas formas puedes ir viendo cómo se va construyendo el proyecto de este curso para que puedas crear tu propio bot para Slack o para cualquier otra aplicación de mensajería de tu preferencia.

### Comentarios:

* **asanchez2091** (1) [1056259](https://platzi.com/comentario/1056259/) 

	Empecemos esta cursillo

* **Adrián Andrés Sosa** (1) [1029880](https://platzi.com/comentario/1029880/) 

	Buenísimo!

* **Sara Galván Ortega** (1) [857405](https://platzi.com/comentario/857405/) 

	Maravilloso 😄!

## 0030. Arquitecturas de software basadas en mensajería y colas de tareas [19025](https://platzi.com/clases/1549-celery/19025-arquitecturas-de-software-basadas-en-mensajeria-y-/)

### Descripción:
![infografia-Celery.png](https://static.platzi.com/media/user_upload/infografia-Celery-9c9895bc-f6b2-4ad7-a237-e57c4e04a924.jpg)

### Comentarios:

* **KarlxS** (5) [552049](https://platzi.com/comentario/552049/) 

	Vaya siempre se aprende algo nuevo…:v

	* **Julio J Yépez** [552049] (3)

		Y eso que apenas estamos en las primeras clases del curso 😄 … !

* **Mauro Cayul** (3) [554631](https://platzi.com/comentario/554631/) 

	Esto se ve muy interesante. Voy por este conocimiento nuevo

* **JPabloMayorgaM** (2) [709149](https://platzi.com/comentario/709149/) 

	Es intersante, bueno ahora sí a ver como funciona Celery

* **Adrián Andrés Sosa** (1) [1029884](https://platzi.com/comentario/1029884/) 

	Se ve una herramienta muy útil

## 0040. Brokers de tareas Servidores de mensajería y formas de usarlos [19026](https://platzi.com/clases/1549-celery/19026-brokers-de-tareas-servidores-de-mensajeria-y-forma/)

### Descripción:


 **Colas de tareas, brokers de mensajes o brokers de tareas** son servicios de mensajes que actúan como intermediarios, son servicios que están trabajando en recibir y emitir mensajes todo el tiempo. Enrutan, agregan y permiten crear servicios de publicación/suscripción( **pubsub** ).

**Algunos brokers de tareas** :

* RabbitMQ escrito en Erlang
* Kafka escrito en Scala y Java
* Redis escrito en C
* ActiveMQ escrito en Java



También tenemos sistemas de mensajería privativos en la nube: AWS SQS, Azure Service Bus, Google Cloud Messaging, Firebase Cloud Messaging.

**Usos y ventajas** :

* Sincronización de datos entre diferentes partes de un sistema
* Eliminación del almacenamiento central de datos
* Activación segura de microservicios
* Almacenamiento persistente de datos.
* Redundancia.



Sal del monolito con arquitectura basadas en eventos.

### Comentarios:

* **Matias Niz** (3) [554085](https://platzi.com/comentario/554085/) 

	Como los eventos que activan las cloud functions en firebase

	* **william andres rodriguez borja** [554085] (1)

		No google cloud tiene un servicio de mensajeria llamado Google cloud Task ese seria el simil.
		
		Las Cloud Function son funciones de backend como servicio y crear un backend en la nube el simil de este seria python o triggers de una base de datos.

* **uncristianr** (1) [867278](https://platzi.com/comentario/867278/) 

	Arquitecturas modernas en las que se usan los brokers

* **Cristhian Camilo Jiménez Varón** (1) [552945](https://platzi.com/comentario/552945/) 

	Yuju primer comentario. Dentro de estos brokers de tareas se contaria el Message Broker IBM y el WSO2?

	* **Julio J Yépez** [552945] (2)

		Creo que no, porque incluso presta soporte para implementación de brokers con RabbitMQ en sus servicios de IBM Cloud … <https://www.ibm.com/cloud/messages-for-rabbitmq>

	* **JJ Merelo Guervós** [552945] (1)

		Aparentemente, WSO2 es un gestor de APIs. Es posible que, por debajo, use algún gestor de tareas, pero en principio la funcionalidad es diferente. Como indica @jjyepez, Message Broker en principio tampoco, aunque sobre message brokers se pueden construir efectivamente un gestor de tareas.

* **asanchez2091** (1) [79657](https://platzi.com/comentario/944022/) 
He visto redis y celery en el mismo proyecto como es eso si ambos entonces hacen lo mismo??

* **Cristhian Camilo Jiménez Varón** (1) [56460](https://platzi.com/comentario/552945/) 
Yuju primer comentario. Dentro de estos brokers de tareas se contaria el Message Broker IBM y el WSO2?

	* **Julio J Yépez** [56460] (2)

		Creo que no, porque incluso presta soporte para implementación de brokers con RabbitMQ en sus servicios de IBM Cloud … <https://www.ibm.com/cloud/messages-for-rabbitmq>

## 0050. ¿Cuándo debemos usar Celery [19027](https://platzi.com/clases/1549-celery/19027-cuando-debemos-usar-celery/)

### Descripción:


Cuando vayas a escribir una arquitectura basada en Python, cuando trabajes con Django, Flask o una aplicación de Ciencia de Datos con Panda o Scikit puedes usar **Celery** porque es la única herramienta que nos ofrece estas posibilidades.

**Celery en Producción** :

* Registro y almacenamiento (sin repuesta al origen)
* Intermediar entre servicio web (Flask, Django) y otros microservicios
* Ejecución retrasadas de tareas



**Celery frente a otras alternativas** :

* Modelo genérico y abstracto(frente a Pika, Django-carrot)
* Más usada que Dramatiq.
* Soporte para más brokers y más configurables que RQ
* Más configurable que Huey



**Celery** es única en su género y su uso es aconsejable casi siempre.

### Comentarios:

* **German Tellez Vanegas** (2) [1017937](https://platzi.com/comentario/1017937/) 

	ESte profe me anima a aprender celery, vamos a la siguiente clase

* **Walter Ugalde A** (2) [552655](https://platzi.com/comentario/552655/) 

	Puedo integrar, Celery y GraphQL ?

	* **JJ Merelo Guervós** [552655] (1)

		Son, en principio, diferentes, pero evidentemente puedes construir un backend con GraphQL que, a su vez, use Celery para distribuir tareas.

* **morwen1** (1) [590173](https://platzi.com/comentario/590173/) 

	Celery me puede ayudar a hacer aplicaciones de ejecucion en tiempo real? algo asi como chats

	* **Diego Alexander Forero Higuera (Platzi)** [590173] (4)

		Te va a ayudar a distribuir las tareas que tengas que ejecutar pero también vas a necesitar intervención del frontend para que este leyendo los cambios esto se puede hacer por medio de websockets.

	* **German Tellez Vanegas** [590173] (1)

		Para lo que dices creo que es mejor Django-channels si es que estas usando django

* **Luis Carlos Juarez Azuara** (1) [556342](https://platzi.com/comentario/556342/) 

	Hola, puedo usar Celery en un proyecto hecho con Laravel???. Laravel proporciona ya un sistema de mensajería llamada Laravel Queues pero no se si sea tan eficiente como Celery.
	
	Gracias.

	* **Julio J Yépez** [556342] (1)

		Hola Luis, tengo entendido que sí es posible aunque nunca lo he intentado, quizás estos enlaces te den una mejor idea de cómo hacerlo:
		
		* <https://github.com/jonbwhite/celervel>
		* <https://packagist.org/packages/massivescale/celery-php>
		
		

* **joseVargas94** (1) [552133](https://platzi.com/comentario/552133/) 

	cual es el curso de heroku ?

	* **Julio J Yépez** [552133] (3)

		Hola José, por acá te dejo un enlace a todos los cursos / clases en [platzi.com](http://platzi.com) relacionadas con Heroku!
		
		<https://platzi.com/search/?search=heroku>

	* **Mauricio Chávez Olea** [552133] (2)

		No existe como tal

	* **Julio J Yépez** [552133] (1)

		Existe un curso, pero es de 2015, seguramente está en lista alguna actualización  
		<https://platzi.com/clases/heroku-2015/>

* **Luis Carlos Juarez Azuara** (1) [56748](https://platzi.com/comentario/556342/) 
Hola, puedo usar Celery en un proyecto hecho con Laravel???. Laravel proporciona ya un sistema de mensajería llamada Laravel Queues pero ...

	* **Julio J Yépez** [56748] (1)

		Hola Luis, tengo entendido que sí es posible aunque nunca lo he intentado, quizás estos enlaces te den una mejor idea de cómo hacerlo:
		
		* <https://github.com/jonbwhite/celervel>
		* <https://packagist.org/packages/massivescale/celery-php>
		
		

* **joseVargas94** (1) [56396](https://platzi.com/comentario/552133/) 
cual es el curso de heroku ?

	* **Julio J Yépez** [56396] (3)

		Hola José, por acá te dejo un enlace a todos los cursos / clases en [platzi.com](http://platzi.com) relacionadas con Heroku!
		
		<https://platzi.com/search/?search=heroku>

## 0060. Reto Casos de uso de Celery [19028](https://platzi.com/clases/1549-celery/19028-reto-casos-de-uso-de-celery/)

### Descripción:


Casos de usos actuales:

* CKAN, el almacén para datos abiertos, lo usa para ejecutar tareas y procesar webhooks.
* Airflow es un sistema de flujos de trabajo o workflow que usa Celery para mensajería
* Uso con Django.



Deja en la sección de comentarios si ¿Es aconsejable usar Celery en ese caso? ¿Por qué? ¿Qué mejoraras conseguirías?

### Comentarios:

* **Eduardo P. Rivero** (7) [551766](https://platzi.com/comentario/551766/) 

	Un reporteador que puede generar un archivo de tipo: pdf, xlsx, txt, etc, a partir de un html y una estructura en json.
	
	**Sin Celery:**
	
	Dependiendo de qué tan complejo sea el html y el tamaño del json puede ser un proceso muy largo que haga esperar varios segundos al usuario afectando la UX de una aplicación.
	
	Sería imposible que el usuario pueda generar más de un reporte a la vez, siempre tendría que esperar a que se genere el reporte para poder generar otro.
	
	**Con Celery**
	
	Celery parece una buena alternativa acá ya que se le puede indicar al usuario que el reporte está siendo construido mientras él puede interactuar con otras opciones de la aplicación.
	
	La aplicación debería tener una opción en la que ve el status de los reportes.

	* **Julio J Yépez** [551766] (4)

		Un generador de reportes automatizado, quizás programado en base a ciertos días y horas, con información tomada de los registros logs del sistema o json como dices, muy interesante!

* **AnthonySQC** (3) [909641](https://platzi.com/comentario/909641/) 

	Crearé un proyecto que consista en un bot de Twitter que vaya recogiendo datos, los envie al broker de mensajería y con un procesador de datos genere eventos, pienso usar(como idea inicial):  
	-Python con Celery, Tweepy.  
	-RabbitMQ.  
	-Un procesador de datos de Apache como Flynk/Spark/Storm.  
	La implementación la realizaré en mi maquina local y la ejecución se realizará en mi maquina local.  
	Pienso que es aconsejable usar Celery debido a que el lenguaje principal será Python. por su compatibilidad con RabbitMQ y su eficiencia. Además de la cantidad de documentación que podré encontrar en Internet.

	* **william andres rodriguez borja** [909641] (1)

		interesante

* **jmframil** (3) [587534](https://platzi.com/comentario/587534/) 

	Consumiendo apis para recuperar historial de ventas, preguntas, publicaciones y todo desde amazon, mercadolibre, etc.

* **salvadorweb89** (2) [741355](https://platzi.com/comentario/741355/) 

	Podría ser bastante útil para controlar la petición de gráficas y estadísticas pesadas, procesos con datos a nivel de suministro como consumo energético, agua que tienen que mover muchísima información, histórico de pedidos, plataformas de servicio, procesos de indexado, etc.

* **dcortesnet** (2) [555141](https://platzi.com/comentario/555141/) 

	Celery, envío masivo de emails o mensajería de texto

* **marcos mayen** (2) [554131](https://platzi.com/comentario/554131/) 

	**Administrativo: ** Si tengo una aplicación que está funcionando en varias tiendas y me gustaría sacar el estado de todas al mismo tiempo, con celery puedo generar una petición que en segundo plano obtenga toda esa información, la convierta en un formato en especifico(pdf, csv, xml por dar algunos ejemplos), y una vez ha concluido la tarea, me entregue el reporte, expresando a que hora hizo el cierre de cada tienda, sus balances, cuentas, estados financieros, entre otros.
	
	**Edición** : pre renderizar un video, una película, e incluso un modelo 3D en segundo plano, para evitar la carga directa en el programa, y que el servidor colapse.
	
	**Videojuegos** :utilizando otras herramientas como NodeJS o ajax, se puede realizar una aplicación en linea donde los procesos sean realizados por celery, algunas acciones sean realizadas como segundo plano, como cargar escenarios, enemigos, reacciones, etc.

* **Adrián Andrés Sosa** (1) [1029913](https://platzi.com/comentario/1029913/) 

	Un caso de uso que tube una vez, fue que en una aplicación web teníamos que generar un reporte muy grande con información de una base de datos muy grande también, y eso se hacía entrando a un link, donde había un botón de descarga. Luego de dar click en el botón empezaba a generar ese reporte en pdf, y le toma varios minutos antes de que se pueda descargar, ahora pensando en celery haría una cola de trabajo donde se vayan recibiendo esas peticiones de descarga de ese reporte y una vez terminado se lo enviaría por mail al usuario que lo solicitó.

* **boyarzun** (1) [987391](https://platzi.com/comentario/987391/) 

	Desarrollaria una aplicación para calcular el horario de enfermer@s en hospitales. En mi opinión, pienso que es aconsejable utilizar Celery porque dependiendo de la cantidad de horarios que se calculen, podría generarse un cuello de botella si la aplicación crece mucho, para evitar eso sería interesante distribuir cada horario que debe generarse (Task) a los Workers.

* **asanchez2091** (1) [944071](https://platzi.com/comentario/944071/) 

	En mi caso django ya vi que celery me permite recibir peticiones del usuario y enviarle con django un servicio.

* **Sara Galván Ortega** (1) [857469](https://platzi.com/comentario/857469/) 

	Bueno yo podría usar celery como brocker de tareas en una aplicación de streaming en django por ejemplo para que exista una tarea específica que esté pendiente de las solicitudes de los usuarios, es decir, de los videos que cada uno quiere ver y otra tarea espcífica para buscar el archivo espacífico y enviarlo

* **Mario Fernando Sánchez Carrión** (1) [780135](https://platzi.com/comentario/780135/) 

	Para juegos que ejecuten multiples eventos a diferentes usuarios que estén conectados y suscritos a esos eventos, Para generar reportes, estadísticas. Para un sistema de fútbol que vaya trackeando cuánto va recorriendo un futbolista en la cancha, se podría generar colas de eventos por cada jugador.

* **andres-martinez578** (1) [607468](https://platzi.com/comentario/607468/) 

	Yo creo que me seria util para hacer un cargue de archivos excel procesarlos con una cola de tareas para hacerle una respectiva limpieza con pandas , me seria util para no hacer esperar al usuario si no almacenar y ir haciendo un proceso con todos los archivos guardados.

* **Ivan Camilo Ramirez Rojas** (1) [604137](https://platzi.com/comentario/604137/) 

	Yo la usaría para :  
	Guardar logs de las respuesta de una API  
	Envío de correos  
	Tareas que ejecuten servicios externos, ese servicio externo puede fallar, al no depender de nosotros deberíamos enviar todo ese flujo a una tarea y guardamos un log.

* **Eduardo Kiriakos Piazza** (1) [70973](https://platzi.com/comentario/786729/) 
¿Es cellery la mejor opción para mi proyecto? Actualmente estoy desarrolando una aplicación de Quinielas para torneos de fútbol con Djang...

	* **asanchez2091** [70973] (1)

		Celery es casi siempre la mejor elección.

# Bot de Slack [3814]

## 0070. ¿Cómo funciona un bot [19029](https://platzi.com/clases/1549-celery/19029-como-funciona-un-bot/)

### Descripción:


Un **bot** es un programa que actúa como interlocutor en un software de mensajería, es una nueva interfaz de usuario, es una nueva forma de interacción. El software debe estar preparado para reaccionar a una orden y dar una respuesta inmediata.

Un Bot siempre está escuchando sin perder ningún mensaje, responde lo que necesitas y realiza tareas.

**Casos de uso** :

* Atención inmediata al cliente.
* Solicitudes de información de búsquedas.
* Comprobaciones de identidad y de seguridad.
* Información de otro lugar y alertas.
* Juegos.



### Comentarios:

* **Eduardo Imery Winterdaal** (3) [704107](https://platzi.com/comentario/704107/) 

	Excelente curso hasta ahora, muy buena explicación, Celery hasta ahora se ve que es una herramienta super util para nosotros los desarolladores… ahora es trabajo de tomarla mas en cuenta

* **oobie92** (3) [632521](https://platzi.com/comentario/632521/) 

	Los espanoles hablan tan rapido que poniendo el video en x.85 se me hace una conversacion normal jaja. Excelente clase! 😃

* **erickecheverryg** (1) [80026](https://platzi.com/comentario/951082/) 
Saludos, una pregunta: ¿Como puedo configurar en @shared_task de celery para que se ejecute en una fecha específica? Había visto el atrib...

	* **AnthonySQC** [80026] (1)

		Hola erick,  
		¿podrías dejar otro comentario mostrando la implementación del código?.

## 0080. Cómo funciona el API de Slack para programación de bots (y parecidos y diferencias con otros APIs) [19030](https://platzi.com/clases/1549-celery/19030-como-funciona-el-api-de-slack-para-programacion-de/)

### Descripción:


Debes añadir ganchos o hooks de entrada. Estos son eventos que recibirá tu bot, pueden ser cambios de canal, cuando entras a un canal, cuando te conectas. En nuestro caso será un bot que responderá cuando se le hable y guardará conversaciones.

Guarda tus credenciales o llaves secretas en un archivo .env en la carpeta de desarrollo, con permisos restringidos. No la incluyas en tu repositorio de proyecto. Incluye el archivo .env en el `.gitignore`.

* No incluirlas directamente en el código
* Tratarlas como si fueran claves
* Regenerar cada cierto tiempo.



**Incoming webhooks** sirve para usar el bot desde fuera de Slack.

[Enlace de invitación para unirse a la demo del proyecto](https://join.slack.com/t/charlandero/shared_invite/enQtNTg3Mzc5Mjk5MDMwLTk4MjBkOTgyZmQ2NzM4NzY2OGE1MmRmMWYzZTQ4MTI3MDM5MWYyZGNiZjVmNWEwZjlmODNjOGFmMTgzOTFhNDg)

### Links:

* [Slack API: Applications | Slack](https://api.slack.com/apps/new)

* [Create Account | Slack](https://join.slack.com/t/charlandero/shared_invite/enQtNTg3Mzc5Mjk5MDMwLTk4MjBkOTgyZmQ2NzM4NzY2OGE1MmRmMWYzZTQ4MTI3MDM5MWYyZGNiZjVmNWEwZjlmODNjOGFmMTgzOTFhNDg)

* [Add Apps to Slack | Apps and Integrations | Slack App Directory](https://slack.com/apps)

### Comentarios:

* **Hernán Chilabert** (1) [1029856](https://platzi.com/comentario/1029856/) 

	El enlace de invitación a la demo del proyecto dejó de funcionar:
	
	_This invite link is no longer active.  
	If you have an @platzi.com email address, you can still create an account.
	
	If not, please check with the person who shared the invite link with you to ask for an invitation._

* **TlalocES** (1) [1005254](https://platzi.com/comentario/1005254/) 

	Pero como se crean los tokens, he creado la app, pero no veo la forma de seguir, estaria bien que subierais el video haciendolo paso a paso, y luego borrais la app para que no quede un token por ahi libre.

	* **rubencolina** [1005254] (2)

		creo que Slack cambió el API y como se maneja, yo estoy en la misma situación, una lástima el curso se ve bueno, quizás nos toca rehacer parte del código para adaptarlo y funcione nuevamente

	* **TlalocES** [1005254] (1)

		Eso creia ruben (gracias por cierto), igualmente creo que deberian haber puesto el paso a paso, yo voy a hacerlo en telegram, que me parece bastante mas facil y rapido, total para lo que parece que lo van a usar da igual yo creo.

* **AnthonySQC** (1) [915363](https://platzi.com/comentario/915363/) 

	Para el tema de manejo de credenciales os recomiendo usar el gestor de contraseñas lastpass, funciona a partir de tu cuenta de correo y una clave maestra, lastpass guarda los IDs y contraseñas que utilizas. Además de tener un generador de contraseñas de máxima seguridad, os recomiendo probarlo.

## 0090. ¿Cómo crear un bot reactivo [19031](https://platzi.com/clases/1549-celery/19031-como-crear-un-bot-reactivo/)

### Descripción:


En esta clase el profesor JJ Merelo nos explica como crear un bot reactivo para Slack y todas los provechos que pueden sacarse junto con Celery.

Celery es una biblioteca en Python para gestionar colas de tareas distribuidas. Es software libre y está liberado con una licencia BSD. Cuenta con con más de diez mil commits en este momento en Github. Cuenta con algunas ventajas como escabilidad, eficiencia, orden de transacciones garantizado, resistencia a fallos, aguantar picos de mensajes

### Links:

* [Curso de Expresiones Regulares | Materiales](https://platzi.com/clases/expresiones-regulares/)

### Comentarios:

* **Sergio Correa Lopez** (8) [551810](https://platzi.com/comentario/551810/) 

	ejecutamos linux
	``` 
	    git clone https://github.com/JJ/slack-bot-platzi.git 
	    cd slack-bot-platzi
	    sudo pip install -r requirements.txt
	    touch .env
	    
	```

	* **Julio J Yépez** [551810] (4)

		Buen aporte Sergio, gracias!

* **josericardoperezperez** (6) [553520](https://platzi.com/comentario/553520/) 

	Recomiendo antes crear un entorno virtual para no tocar nada de tu SO 😃
	``` 
	    virtualenv -p python3 env
	    
	```

	* **JJ Merelo Guervós** [553520] (1)

		Si usas gestores de versiones como pyenv no hace falta que toques nada. Virtualenv o pipenv son también siempre buenas opciones para lo mismo.

## 0100. Reto posibles aplicaciones de bots de Slack, buscar ejemplos y entender cómo se llevarían a cabo [19032](https://platzi.com/clases/1549-celery/19032-reto-posibles-aplicaciones-de-bots-de-slack-buscar/)

### Descripción:


Un bot puede escuchar, almacenar información de conversaciones, analizar esas conversaciones para realizar análisis de sentimientos; puede responder, Inteligencia Artificial en las conversaciones, acceder a información fija y almacenada, juegos conversacionales. Puede realizar tareas como búsquedas en motores de búsqueda, consultar a base de datos o almacenes de imágenes, consultar agendas o agendar.

### Comentarios:

* **Mario Emiliano Gordon Pico** (2) [779305](https://platzi.com/comentario/779305/) 
Podria realizar el estado de un vuelo en particular? Dando el estatus cada cierto tiempo

* **Javier Fernández Sacristán** (2) [745337](https://platzi.com/comentario/745337/) 

	Una aplicación interesante sería por ejemplo facilitarle al cliente la posibilidad de consultar el estado de un pedido a traves del bot o el seguimiento del mismo

* **Adrián Andrés Sosa** (1) [1031190](https://platzi.com/comentario/1031190/) 

	Podría ser interesante tener un bot para generar ayudas y agregados de información en una conversación, sería como un tercero la conversación entre dos personas, escuchando atentamente con AI, podría corregir datos erróneos brindados por los participantes y agregar más info cuando se hagan preguntas de temas generales.

* **boyarzun** (0) [987622](https://platzi.com/comentario/987622/) 
Un bot para aprender idiomas, que cada día te enseñe una palabra nueva, durante ese día te muestre ejemplo, conjugaciones (en el caso de los verbos), etc.

## 0110. Reto modificar el bot básico y crear alguno que responda a a algún tipo de petición o muestre algo [19033](https://platzi.com/clases/1549-celery/19033-reto-modificar-el-bot-basico-y-crear-alguno-que-re/)

### Descripción:


En la sección de Archivos encontrarás el repositorio del curso.

### Comentarios:

* **Eduardo P. Rivero** (8) [551942](https://platzi.com/comentario/551942/) 

	Creé un bot que te muestra la información del perfil de un usuario de platzi
	
	![Botzi](https://res.cloudinary.com/drukp4ipu/image/upload/v1554341504/platzi-bot/pb-2.gif)

	* **Julio J Yépez** [551942] (3)

		¡Eduardo, esto está genial!  
		Estaría muy cool si nos compartes cómo lo lograste con un tutorial en el curso  
		En este link: [Crear un tutorial para este curso](https://platzi.com/clases/celery/add_contribution/)

* **victormanuelescalantealquisira** (1) [672461](https://platzi.com/comentario/672461/) 

	Tengo una duda, ¿Cómo es que pasamos de correr el script a dejarlo funcional como el ejemplo de @eduardo_rivero ? 😦 No entiendo

	* **Diego Alexander Forero Higuera (Platzi)** [672461] (1)

		Debes desplegarlo en un servidor como heroku para que sea accesible.

# Brokers de mensajería [3815]

## 0120. ¿Qué es un broker de mensajería y cuándo debe usarse [19034](https://platzi.com/clases/1549-celery/19034-que-es-un-broker-de-mensajeria-y-cuando-debe-usars/)

### Descripción:


Un **broker de mensajería** o _message-oriented middleware_ es algo que está en medio, un intermediario. El broker de mensajería se va asegurar de que lo mensajes lleguen a su destino y esos mensajes tendrán una serie de cliente.

Nunca hacen una interacción directa de uno a otro ya que sería una interacción síncrona.

### Comentarios:

## 0130. Conceptos mecanismos de publicaciónsuscripción. Canales. Intercambiadores [19035](https://platzi.com/clases/1549-celery/19035-conceptos-mecanismos-de-publicacionsuscripcion-can/)

### Descripción:


En el mundo de los brokers de mensajería se utilizan principalmente dos tipos de metáforas. Unas vienen del mundo del correo, donde hay mensajes que tienen un emisor y un receptor, como una carta. Pero no todos los mensajes son de este tipo: hay mensajes que se emiten y puede recibir mucha gente: usamos en este caso metáforas del mundo de la radio.

En la radio tenemos un emisor que es el que emite el mensaje. Ese mensaje se retransmite, es decir, se hace un broadcast, de forma que todo el mundo puede recibirlo. En este caso no importa demasiado que quien escuche acuse recibo del mensaje, simplemente que haya un mecanismo eficiente que permita hacer llegar, a todos los que lo deseen, el mensaje que se emita.

## ¿Y quién va a recibir ese mensaje?

En el mundo de la radio, diferentes canales tienen diferente programación, y los oyentes seleccionan un canal para escuchar. En el mundo de los brokers de mensajería, los canales permiten concentrar los mensajes y que no se mezclen los relativos a diferentes tareas o partes de la aplicación, y adicionalmente los canales pueden tener suscriptores que serán los que únicamente reciban un mensaje que se envíe a este canal.

A este mecanismo se le denomina también **pub/sub** , o publicación/suscripción. Cuando el emisor publica, lo hace en un canal. Los posibles receptores son suscriptores del canal y simplemente tienen que indicar el canal al que quieren escuchar para ser alertados y funcionar de forma reactiva cada vez que un nuevo mensaje se emita en el canal.

## Las estafetas

Las estafetas, intercambiadores o exchanges permiten regular este tráfico de publicación y suscripción y asignar a diferentes canales dependiendo de una serie de reglas. Los intercambiadores son fundamentales y le añaden flexibilidad a este tipo de sistemas, permitiendo el envío programable de mensajes dependiendo en metadatos de los mismos o incluso en su contenido.

La mayor parte de los brokers de mensajería pueden trabajar de las dos formas. Los brokers siguen protocolos tales como AMQP (Advanced Queue Messaging Protocol) que permite trabajar como correos y emisora de radio. AMQP se implementa en diferentes brokers de mensajería tales como RabbitMQ o ActiveMQ.

Otros protocolos se centran sólo en una parte de este mundo de la mensajería: MQTT, Message Queuing Telemetry Transport es un protocolo pub/sub, de publicación y suscripción.

## Las colas de tareas

Por la variedad de protocolos y diferencia de implementaciones, muchas veces lo que se busca por parte del desarrollador es una biblioteca de alto nivel que abstraiga esto y permita trabajar con conceptos que estén en el dominio del problema. Celery, por ejemplo, usa principalmente el concepto de cola de tareas. Esto permite al usuario diseñar la aplicación en función de qué tareas se quiere que se ejecuten y de qué forma (con qué periodicidad, con qué prioridad) se van a ejecutar.

A la vez, Celery tiene acceso a los mecanismos básicos (intercambiadores, colas de mensajes), que se pueden programar de la forma que desee. Partiendo de una aplicación básica, Celery te permite crecer hasta hacer una verdadera aplicación avanzada de cómputo distribuido.

En este curso te acompañaremos en gran parte del camino de descubrimiento de Celery. Seguro que, cuando empieces a usarlo, no dejarás de ver su utilidad en cualquier aplicación que desarrolles.

### Comentarios:

## 0140. Brokers de mensajería open source [19036](https://platzi.com/clases/1549-celery/19036-brokers-de-mensajeria-open-source/)

### Descripción:


 **Características comunes** :

* Protocolos de mensajerías usados.
* Soporte de estándares de mensajería, cómo se envían, reciben y procesan los mensajes.
* Licencias libres.
* API REST, a parte de usarlos con una librería puedes trabajar con ellos con un simple API.
* Soporte Activo.



**RabbitMQ** : Cola de tareas distribuida y robusta.  
**ActiveMQ/Apollo** : Cola de mensajes de altas prestaciones con soporte de JMS.  
**RocketMQ** : Message-oriented middleware con MQTT y JMS  
**Apache Kafka** : Sistema orientado a procesamiento de _streams_ en tiempo real.  
**NATS** : Sistema de mensajería distribuido.

**RabbitMQ** : Es el más popular y el que tiene más soporte de bibliotecas. Es relativamente simple de instalar y mantener, tiene una buena comunidad para soportarlo.

### Comentarios:

## 0150. Python con RabbitMQ uso básico de la terminal [19037](https://platzi.com/clases/1549-celery/19037-python-con-rabbitmq-uso-basico-de-la-terminal/)

### Descripción:


### Comentarios:

* **Nicolas Restrepo** (5) [944150](https://platzi.com/comentario/944150/) 

	Que curso tan malo

* **Everardo Sánchez** (5) [553785](https://platzi.com/comentario/553785/) 

	Me salta un poco que no use un linter y de pronto tenga lineas muy largas. Pep8 no lo dicta así.

	* **JJ Merelo Guervós** [553785] (1)

		Siempre es aconsejable usar un linter, como comentas. Sin embargo, recientemente hay una cierta polémica sobre qué se considera “línea larga”, al menos en la lista de telegram de Python en español, con muchos proponiendo que se usen líneas de 120 caracteres, por ejemplo, y otras personas comentando simplemente que “Es el consejo de Pep 8 que suelen saltarse”

	* **Kevin Javier Morales** [553785] (1)

		El número de líneas es algo un poco a gusto personal, tampoco deberían ser línea increíblemente extensas complicando la lectura del código. Lo que sí no creo es que sea una regla que deba saltarse, escoge un número entre 79 y 120 que se adapte a ti o a tu pantalla si estás trabajando solo.

* **German Tellez Vanegas** (3) [1018221](https://platzi.com/comentario/1018221/) 

	Este curso es demasiado anti platzi, que aburrido. Por favor renueven este curso con el profesor Pablo Trinidad

* **Diego Alexander Forero Higuera (Platzi)** (3) [754778](https://platzi.com/comentario/754778/) 

	Crear un host virtual en Rabbit  
	`sudo rabbitmqctl add_vhost <nombre_vhost>`
	
	Crear un usuario en Rabbit para que use el vhost  
	`sudo rabbitmqctl add_user <nombre de usuario> <password usuario>`
	
	Asignar permisos al usuario en el host virtual  
	`sudo rabbitmqctl set_permissions -p <nombre vhost> <nombre de usuario> ".*" ".*" ".*"`

* **TlalocES** (2) [1006960](https://platzi.com/comentario/1006960/) 

	Creo que esto no estaba en nigun lado.
	
	**Instalacion de Rabbit:**  
	`curl -fsSL https://github.com/rabbitmq/signing-keys/releases/download/2.0/rabbitmq-release-signing-key.asc | sudo apt-key add - sudo apt-get install apt-transport-https sudo apt-key adv --keyserver "hkps://keys.openpgp.org" --recv-keys "0x0A9AF2115F4687BD29803A206B73A36E6026DFCA" sudo apt-get update sudo apt-get install rabbitmq-server`

* **rafnixg** (1) [1074064](https://platzi.com/comentario/1074064/) 

	Super inconforme con este curso, es el primer curso de platzi de los muchos que he tomado que no esta a la altura, espero que tenga una nueva version con mejor contenido, el profesor a cada rato dice que no es la forma correcta de hacerlo pero igual lo hace de esa manera, en que momento nos va a enseñar cual es la forma correcta?

* **Nicolas Restrepo** (1) [944283](https://platzi.com/comentario/944283/) 

	Como puedo aprender a hacerlo desde un fichero?

## 0160. Comparación de diferentes brokers de mensajería para trabajar con Celery [19038](https://platzi.com/clases/1549-celery/19038-comparacion-de-diferentes-brokers-de-mensajeria-pa/)

### Descripción:


Características principales:

* Soporte por parte de Celery.
* Posibilidad de monitorizar  
– celerymon te permite monitorizar las colas de tareas  
– flower
* Control remoto  
– celery inspect y celery control



**Redis** : Es una base de datos clave-valor en memoria. También funciona como broker de mensajería y como caché

**Amazon SQS** : Cola de mensajes para AWS. Es usado por Amazon y Netflix, tiene un precio 0.40$ por millón de mensajes después del primer millón

### Comentarios:

* **aparicio_juan** (2) [945889](https://platzi.com/comentario/945889/) 

	¿Donde se puede descargar la presentación que está usando?

* **uncristianr** (1) [867506](https://platzi.com/comentario/867506/) 

	Características de celery al trabajar con brokers

## 0170. Reto Crear una pequeña aplicación cliente-servidor que use RabbitMQ desde Python [19039](https://platzi.com/clases/1549-celery/19039-reto-crear-una-pequena-aplicacion-cliente-servidor/)

### Descripción:


Elige una biblioteca que:

* Sea específica de RabbitMQ o del protocolo AMQP(u otros)
* Para el lenguaje que uno use con más asiduidad
* Buen soporte por parte de la comunidad



**Pika** y **Kombu** en Python  
**Bunny** en Ruby  
**AMQPlib** en Node.js  
**AMQP** en Go

**Nota** : tendrás mérito adicional en el reto al usar diferentes lenguajes en backend y frontend

### Comentarios:

# Celery y brokers de mensajería [3816]

## 0180. Creando un entorno de desarrollo para Celery [19040](https://platzi.com/clases/1549-celery/19040-creando-un-entorno-de-desarrollo-para-celery/)

### Descripción:


Vamos a necesitar:

* RabbitMQ
* Python 3
* Celery
* Un editor de código como Atom, VSCode, Emacs, Vim
* Terminal o consola de comandos
* Tu Bot de Slack.



### Comentarios:

* **Juan Pena Verdú** (1) [553841](https://platzi.com/comentario/553841/) 

	Mmmm ¿Curso de Ansible en Platzi?

	* **JJ Merelo Guervós** [553841] (1)

		Hay clases de Ansible en diferentes cursos: <https://platzi.com/clases/1112-node-2016/4745-introduccion-a-ansible/>

## 0190. Instalación y creación de un programa básico pubsub [19041](https://platzi.com/clases/1549-celery/19041-instalacion-y-creacion-de-un-programa-basico-pubsu/)

### Descripción:


### Comentarios:

* **Jose Luis Fernandez** (2) [892839](https://platzi.com/comentario/892839/) 

	Las funciones `get()` de los diccionarios van muy bien para evitar excepciones y dar valores por defecto, sin embargo, en:  
	`os.environ.get('RMQ_PASS')`  
	yo habría puesto:  
	`os.environ['RMQ_PASS']`  
	creo que este caso es buena una excepción lo antes posible (cuando no encuentre la variable de entorno `RMQ_PASS`). Si usamos `get` y no encontrase la variable, substituiría`{}`por `None` y el error lo tendríamos en la conexión al broker, que es más complicado de debugar.  
	Por otra parte, viendo el format del string de conexión a sqlite: ¿porqué no usar los nuevos f-strings de python3? Encuentro que hacen más legibles los strings formateados.  
	Un saludo.

* **artik0** (2) [827195](https://platzi.com/comentario/827195/) 

	creo que este es un curso muy bueno pero mal ordenado, en verdad es un tanto complejo seguirle profe, por que hace dos videos me esta haciendo comparaciones de nuevo, lleva poco mas de una hora comparando broker y recien que va a mostrar celery tambien esta saltado… me gustaria que le hicieran una revision al curso, al menos para ordenar bien las clases…

* **jenapi** (2) [792212](https://platzi.com/comentario/792212/) 

	Estoy un poco perdido, las clases anteriores y el repo de github te muestran es lo que hacemos a partir de esta clase??

* **redyafte** (1) [678774](https://platzi.com/comentario/678774/) 

	Tambien esta cool ipython, para autocompletar solo usas `tap`.
	``` 
	    pip install ipython
	    
	```

## 0200. Cómo usar Celery para programar un robot de Slack diseño y comienzo de la implementación [19059](https://platzi.com/clases/1549-celery/19059-como-usar-celery-para-programar-un-robot-de-slack-/)

### Descripción:


### Comentarios:

* **Armando Aguilar L.** (8) [582782](https://platzi.com/comentario/582782/) 

	Que horror !!! curso sin pies ni cabeza 🙄, toca aprender de la documentación <http://www.celeryproject.org>, espero mejoras en cursos posteriores =).

	* **Johan Steven Arias** [582782] (3)

		El Profesor Complica demasiado lo que en teoría es simple,  
		Esta lleno de paradigmas arcaicos y me parece un poco reaccionario. No me gustó para nada este profesor.

	* **Ivan Camilo Ramirez Rojas** [582782] (4)

		Me parece que jj Merelo es un teso, pero igualmente resulté saltando a otro lugar por que sabía que es menos pesado el tema de celery, y realmente no es tan complejo cómo se ve aquí…

	* **EmmanuelO** [582782] (3)

		Tienes razón, ya no se sabe si es parte del proyecto o si es un pequeño ejercicio. Igual he tenido que buscar en otras fuentes.

* **Eduardo Kiriakos Piazza** (5) [793044](https://platzi.com/comentario/793044/) 

	Bien difícil de seguir el curso…

* **eduardo-zepeda** (4) [782301](https://platzi.com/comentario/782301/) 

	Prefiero los cursos de Leonidas. Este profesor lleva dándole vueltas a los mismos conceptos una y otra vez. Como se notan los vicios de la universidad a la hora de dar clases, un curso en linea NO debe ser igual a un curso presencial.

* **boyarzun** (1) [81902](https://platzi.com/comentario/992909/) 
Me parece que la API de Slack se actualizo no me funciona el .rtm_read(...

## 0210. Monitorización de tareas [19043](https://platzi.com/clases/1549-celery/19043-monitorizacion-de-tareas/)

### Descripción:


Es aconsejable siempre mantener abierta la monitorización de tareas .

**Nos permite** :

* Conocer la carga del sistema
* Visualizar posibles errores
* Ver el registro de peticiones que han llegado y ver su duración
* Comprobar el estado de los diferentes workers a la vez



En este caso usaremos flower el cual puedes instalar haciendo `pip install flower` y usar el navegador para visualización.

**Tienes otras alternativas como** :

* rabbitmqctl list_queues  
– Usar el monitor de RabbitMQ
* Events  
– Uso de un monitor simple de línea de órdenes
* Retratos  
– Usando la interfaz “events”, registro de actividad



### Comentarios:

## 0220. Solucionando problemas [19044](https://platzi.com/clases/1549-celery/19044-solucionando-problemas/)

### Descripción:


**Google es tu amigo**. Python tiene errores “buenos” porque incluyen excepciones con nombres específicos los cuales puedes buscar.

También puedes preguntar en **StackOverflow** como en español o en inglés para obtener respuestas más concretas. Incluso puedes realizar tus preguntas dentro de **los foros de Platzi** y alguien de esta increíble comunidad estará encantado de ayudarte.

**Primera línea de defensa**

* Usa **rabbitmqadmin** para examinar las colas y ver qué se ha enviado y recibido
* Usa **flower** para verlo de forma gráfica



**Soluciones drásticas** :

* Si se están generando mensajes incorrectos, purga la cola: `celery -A RegistrarComandos purge`. Esto es una opción de último recurso y no debería hacerse en producción
* Parar la aplicación `sudo rabbitmqctl stop`



### Comentarios:

## 0230. Reto implementación y despliegue básico de un bot de Slack [19045](https://platzi.com/clases/1549-celery/19045-reto-implementacion-y-despliegue-basico-de-un-bot-/)

### Descripción:


En la sección de Archivos encontrarás el repositorio del proyecto.

### Comentarios:

# Enrutado de tareas [3817]

## 0240. Conceptos enrutado de tareas y por qué se necesita [19046](https://platzi.com/clases/1549-celery/19046-conceptos-enrutado-de-tareas-y-por-que-se-necesita/)

### Descripción:


 **Celery** funciona bien con una sola estafeta( _exchange_ ), una sola cola. Las estafetas van a decidir dónde va un mensaje, en nuestro caso decidirá a qué _worker_ o cola irá.

Nosotros utilizaremos el concepto de cola y clave de encaminamiento: _routing key_ , estas estarán relacionadas con el nombre de la tarea.

**Tipos de estafetas** :

* Directas  
– Necesitan que la clave sea exacta
* Temáticas  
– Usan claves separadas por puntos y pueden usar comodines.



**Celery** funciona con cero configuración, puedes empezar a lanzar tareas automáticamente sin preocuparnos por colas y demás. Tiene **flexibilidad** para establecer las claves de encaminamiento y colas que se deseen. También actúa como fachada de **Kombu** , la biblioteca de mensajería.

### Comentarios:

## 0250. Enrutado manual [19047](https://platzi.com/clases/1549-celery/19047-enrutado-manual/)

### Descripción:


### Comentarios:

## 0260. Mensajería en Celery uso de Kombu [19048](https://platzi.com/clases/1549-celery/19048-mensajeria-en-celery-uso-de-kombu/)

### Descripción:


### Comentarios:

## 0270. Enrutado automático [19049](https://platzi.com/clases/1549-celery/19049-enrutado-automatico/)

### Descripción:


### Comentarios:

## 0280. Reto diseño de mecanismos de enrutado para un bot de Slack [19050](https://platzi.com/clases/1549-celery/19050-reto-diseno-de-mecanismos-de-enrutado-para-un-bot-/)

### Descripción:


### Comentarios:

# Integración y despliegue en la nube [3818]

## 0290. Estructura de mensajes en Celery y resultados de tareas [19051](https://platzi.com/clases/1549-celery/19051-estructura-de-mensajes-en-celery-y-resultados-de-t/)

### Descripción:


 **Celery** transporta la respuestas de las tareas.

**Formatos de serialización** :

* **JSON** por omisión
* Puede usar **YAML**
* **pickle** (formato específico de Python)
* **msgpack** (formato universal de empaquetado de mensajes)
* Admite otros tipos de **MIME**



Se necesita almacenar la respuesta. Por eso hay que realizar algunos cambios para recibir estas respuestas. Tendrás que configurar un _backend_ para almacenar las tareas en tránsito y una vez configurado, el transporte y presentación se hacen automáticamente.

Puedes usar **ORM para Django, Memcached, Redis, RabbitMQ/AMQP** como Backends para **Celery**

### Links:

* [Curso de Ruby | Materiales](https://platzi.com/clases/ruby/)

### Comentarios:

## 0300. Tareas periódicas con Celery [19052](https://platzi.com/clases/1549-celery/19052-tareas-periodicas-con-celery/)

### Descripción:


### Links:

* [Introducción a Terminal y Línea de Comandos | Materiales](https://platzi.com/clases/terminal/)

* [Curso de Expresiones Regulares | Materiales](https://platzi.com/clases/expresiones-regulares/)

### Comentarios:

## 0310. Configuración de sistemas en la nube [19053](https://platzi.com/clases/1549-celery/19053-configuracion-de-sistemas-en-la-nube/)

### Descripción:


### Comentarios:

## 0320. Contenedores [19054](https://platzi.com/clases/1549-celery/19054-contenedores/)

### Descripción:


Docker es un programa de código abierto que permite que una aplicación Linux y sus dependencias se empaqueten como un contenedor.

La virtualización basada en contenedores aísla las aplicaciones entre sí en un sistema operativo (OS) compartido. Este enfoque estandariza la entrega del programa de la aplicación, permitiendo que las aplicaciones se ejecuten en cualquier entorno Linux ya sea físico o virtual.

Dado que comparten el mismo sistema operativo, los contenedores son portátiles entre diferentes distribuciones de Linux y son significativamente más pequeños que las imágenes de máquinas virtuales (VM).

### Links:

* [Fundamentos de Docker | Materiales](https://platzi.com/clases/docker/)

### Comentarios:

## 0330. Despliegue en un PaaS Heroku [19055](https://platzi.com/clases/1549-celery/19055-despliegue-en-un-paas-heroku/)

### Descripción:


 **Heroku** es excelente para trabajar con **Celery** y muchas otras cosas, en este caso utilizaremos la opción gratuita para realizar nuestras pruebas. Es una plataforma como servicio, esto significa que no puedes elegir la versión de sistema operativo a usar o trabajar con los lenguajes que quieras.

**Tipos de procesos**

* **Web** : Escuchan en el puerto 80
* **Worker** : realizan una tarea de fondo
* Otros tipos, con funciones especiales: release, por ejemplo.



Los **Dynos** son equivalentes a procesadores. Solo podemos usar uno en la opción gratuita.

[Enlace de invitación para unirse a la demo del proyecto en ejecución](https://join.slack.com/t/charlandero/shared_invite/enQtNTg3Mzc5Mjk5MDMwLTk4MjBkOTgyZmQ2NzM4NzY2OGE1MmRmMWYzZTQ4MTI3MDM5MWYyZGNiZjVmNWEwZjlmODNjOGFmMTgzOTFhNDg)

### Links:

* [Create Account | Slack](https://join.slack.com/t/charlandero/shared_invite/enQtNTg3Mzc5Mjk5MDMwLTk4MjBkOTgyZmQ2NzM4NzY2OGE1MmRmMWYzZTQ4MTI3MDM5MWYyZGNiZjVmNWEwZjlmODNjOGFmMTgzOTFhNDg)

### Comentarios:

## 0340. Uso de Celery con Node.js [19056](https://platzi.com/clases/1549-celery/19056-uso-de-celery-con-nodejs/)

### Descripción:


### Links:

* [Curso Básico de Node.js | Materiales](https://platzi.com/clases/basico-nodejs/)

### Comentarios:

## 0350. Reto despliegue en la nube (usando cuentas gratuitas) [19057](https://platzi.com/clases/1549-celery/19057-reto-despliegue-en-la-nube-usando-cuentas-gratuita/)

### Descripción:


### Comentarios:

# Conclusiones [3819]

## 0360. Despedida, conclusiones y a dónde ir desde aquí [19058](https://platzi.com/clases/1549-celery/19058-despedida-conclusiones-y-a-donde-ir-desde-aqui/)

### Descripción:


### Links:

* [Create Account | Slack](https://join.slack.com/t/charlandero/shared_invite/enQtNTg3Mzc5Mjk5MDMwLTk4MjBkOTgyZmQ2NzM4NzY2OGE1MmRmMWYzZTQ4MTI3MDM5MWYyZGNiZjVmNWEwZjlmODNjOGFmMTgzOTFhNDg)

### Comentarios:

* **Luis Fernando Cruz Carrillo** (2) [1018414](https://platzi.com/comentario/1018414/) 

	El maestro da información bastante útil, pero hace falta organizar mejor el curso, lo sentí enredado, yo creo que con eso, con organizar mejor el curso sería uno bueno, ni modo Platzi, esta vez se les pasó apoyar al maestro con eso, no puedo decir que no aprendí, pero me tomó un montón de tiempo y paciencia, mucha paciencia para terminar este curso.

* **German Tellez Vanegas** (1) [1060079](https://platzi.com/comentario/1060079/) 

	Me quedé esperando la explicación de Flower!! Para nada lo instaló en el curso y dijo “más adelante lo usaremos”

* **German Tellez Vanegas** (1) [1060078](https://platzi.com/comentario/1060078/) 

	Este curso es todo lo que NOOOO representa platzi o la razón por la que dicen que nació platzi. Siento que perdí mi dinero con este curso y con la forma en que el “profesor” explica. Deberían poner a Pablo Trinidad a hablar de Celery

