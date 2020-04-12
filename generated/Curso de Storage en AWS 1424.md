[Curso de Storage en AWS 1424](https://platzi.com/cursos/storage-aws)

# Bienvenida e Introducción [2846]

## 0010. Introducción al storage en AWS [15033](https://platzi.com/clases/1424-storage-aws/15033-introduccion-al-storage-en-aws/)

### Descripción:


Bienvenido a este curso impartido por Carlos Zambrano. A lo largo del curso verás las diferentes opciones de almacenamiento en AWS junto con sus características y casos de uso.

### Comentarios:

* **Jann-Mor** (6) [475549](https://platzi.com/comentario/475549/) 

	El audio de este curso es mucho mejor al curso De Networking y Content Delivery en AWS.  
	Espro que platzi regrabe nuevamente ese curso, tuve que saltarme a este porque ya no aguantaba la calidad del audio.

	* **Ernesto Lázaro Guerrero** [475549] (1)

		Y aun sigue con el mal audio, pero si lo complete =P

* **Nestor Alfonso Portela Rincón** (4) [465194](https://platzi.com/comentario/465194/) 

	Este curso parece que va ser muy bueno.

* **juancajamarca** (2) [928379](https://platzi.com/comentario/928379/) 

	Buena expresión oral la del profe.

* **johncastillotellez7** (2) [880006](https://platzi.com/comentario/880006/) 

	excelente experiencia y el curso suena super interesante

* **vcentt-lopez** (2) [476973](https://platzi.com/comentario/476973/) 

	El día de hoy acabamos de migrar 2 TB de discos adjuntos en una instancia de AWS a S3, según nuestro análisis vamos a hacer un ahorra de mas del 75% puesto que vamos a usar S3 de acceso poco frecuente y vamos a configurar el ciclo de vida para madar a Glacier y con ello esperamos ahorrar aun mas, ahora tomaré el curso a ver si lo hicimos bien 😃

* **Guido Arce** (2) [425645](https://platzi.com/comentario/425645/) 

	Excelente!! Tomé hace un tiempo el curso de AWS y se veían muchas cosas pero muy superficialmente. Espero ahora poder ver en detalle los servicios básicos que ofrece AWS

* **Dante Castillo Z.** (1) [974959](https://platzi.com/comentario/974959/) 

	Excelente introducción al curso de storage.

* **jorge-gianareas** (1) [966854](https://platzi.com/comentario/966854/) 

	Excelente. Muy bien

* **Andres** (1) [502410](https://platzi.com/comentario/502410/) 
Arreglen la app en mi s8 no funciona bien se sale

	* **Yembert Quintero Cortez** [502410] (1)

		Para esto tienes que enviar un correo que te dan en la playstore o en la appstore con tus respectiva evidencias y asi te pueden ayudar

* **Juan Jose Gonzalez Vera** (1) [461517](https://platzi.com/comentario/461517/) 

	Pues comencemos! Tiene muy buena pinta

## 0020. Proyecto de arquitectura e implementación de almacenamiento [15393](https://platzi.com/clases/1424-storage-aws/15393-proyecto-de-arquitectura-e-implementacion-de-almac/)

### Descripción:


¡Hola! Como proyecto de este curso vas a hacer de cuenta que eres el arquitecto de soluciones de una empresa y el CEO te ha pedido diseñar una arquitectura de almacenamiento para la empresa de seguros. Además, debes implementar una prueba de concepto que como mínimo cuente con lo siguiente:

* 2 buckets en diferentes regiones.

* Replicación de archivos entre las regiones.

* Pruebas de replicación entre regiones.

* Configuración del bucket principal con las siguientes funcionalidades:  
Versionamento.  
Encriptación con KMS.  
Ciclo de vida de la siguiente forma (no para objetos versiones anteriores):

    1. Objetos mayores a 2 meses pasan a S3-IA.
    2. Objetos con 6 meses de antigüedad pasan a Glacier.
    3. Objetos con 2 años de antigüedad deben borrarse.
* Crear un servidor con un volumen EBS agregado a la instancia.

* A través de la CLI consultar los buckets generados y migrar la información que se  
tiene en el EBS al bucket usando la CLI.

* Genera un snapshot del volumen y mígralo a la región en donde se encuentra el bucket secundario.




### Comentarios:

* **eyesidmorenov** (4) [475843](https://platzi.com/comentario/475843/) 

	Tengo un caso de estudio donde la solución debe ser llevada a la nube puede ser Amazon, Azure o Google sin embargo es necesario que se evite al máximo el acoplamiento con estas nubes de manera que sea posible cambiar el proveedor de la misma, o en algún momento montar una nube privada. Ademas de lo anterior es necesario que se tenga en cuenta que se requiere poder escalar dinámicamente la soluciòn. Bueno vamos a ver como este curso me ayuda a dar respuesta a este caso de estudio. Manos a la obra.

* **Enzo Aliatis** (3) [628132](https://platzi.com/comentario/628132/) 

	Estos retos con contexto de que nos envían trabajo me parecen los mejores.

* **charlieGuns** (2) [893086](https://platzi.com/comentario/893086/) 

	Suena bastante interesante y prometedor el proyecto

* **dagonza** (2) [526387](https://platzi.com/comentario/526387/) 

	Emocionante… !!

* **estebanvasquezvalencia** (2) [481158](https://platzi.com/comentario/481158/) 

	Excelente el reto que plantea el curso!

* **José Ricardo Romo Gutiérrez** (2) [479027](https://platzi.com/comentario/479027/) 

	Este proyecto si esta bueno 😄

* **Jann-Mor** (2) [475701](https://platzi.com/comentario/475701/) 

	En todos los cursos de AWS deberían implementar un proyecto para realizar. No solo retos.

* **Daniel .** (2) [474462](https://platzi.com/comentario/474462/) 

	Esto si esta bueno

* **Nestor Alfonso Portela Rincón** (2) [465210](https://platzi.com/comentario/465210/) 

	Parece que vamos a aprender bastante con estos laboratorios.

* **tuckox** (2) [443397](https://platzi.com/comentario/443397/) 

	Excelente, muy buen lab, se aplica mucho en el mundo real.

* **jr22morales** (2) [437141](https://platzi.com/comentario/437141/) 

	Que interesante!!! Soy nuevo en el tema y espero aprender mucho de estabexperiencia 😁

* **Luis Alvarez Ollarvez** (1) [1064870](https://platzi.com/comentario/1064870/) 

	Excelente. Manos a la Obra!

* **Juan Sebastián Bonilla Sanchez** (1) [993568](https://platzi.com/comentario/993568/) 

	Interesante proyecto!

* **deobertinho** (1) [992914](https://platzi.com/comentario/992914/) 

	Ahora si puedo ver que se realizara un proyecto como tal, se ve interesante

* **Dante Castillo Z.** (1) [974960](https://platzi.com/comentario/974960/) 

	Excelente proyecto orientado a la realidad de una empresa.

* **Israel Yance** (1) [958236](https://platzi.com/comentario/958236/) 

	Vine buscando cobre y encontré oro.

* **hanspereira** (1) [943913](https://platzi.com/comentario/943913/) 

	Que buena pinta y aplicable a la realidad!

* **juancajamarca** (1) [928388](https://platzi.com/comentario/928388/) 

	Muy profesional el proyecto.

* **johncastillotellez7** (1) [880010](https://platzi.com/comentario/880010/) 

	excelente, vamos paso a paso

* **ramirobga** (1) [830096](https://platzi.com/comentario/830096/) 

	lo interesante de iniciar con este tipo de retos es que te permite valorar lo que aprendes… vale decir cuando lo lees al inicio te das cuenta lo poco que conoces, y la expectativa es que al final del curso ya lo debes de entender bien… gracias

* **paco2711** (1) [788791](https://platzi.com/comentario/788791/) 

	Retador, pero fascinante… Let’s do this!

* **Andrés Ricaño** (1) [777233](https://platzi.com/comentario/777233/) 

	Excelente. Hagamoslo

* **Cesar Parrales** (1) [563054](https://platzi.com/comentario/563054/) 

	Todo eso?, jajajaja

* **Brayan Mamani** (1) [522435](https://platzi.com/comentario/522435/) 

	Aprenderé mucho

* **vcentt-lopez** (1) [476976](https://platzi.com/comentario/476976/) 

	A su!!!, esto si que está se lee bien interesante, me emociona espero cubran la expectativa 😃

* **Jorge Chávez** (1) [451430](https://platzi.com/comentario/451430/) 

	Wow, información muy puntual.  
	Lo hace muy interesante.

# Almacenamiento de objetos en AWS (S3) [2847]

## 0030. Características de S3 [15034](https://platzi.com/clases/1424-storage-aws/15034-caracteristicas-de-s3/)

### Descripción:


S3 es almacenamiento de objetos como archivos, PDF’s, imágenes, etc. Dentro de S3 contamos con diferentes tipos de almacenamiento:

* S3 Standar
* S3 IA
* S3 IA One Zone
* Glacier



Dependiendo de la clase de S3 va a variar la durabilidad y disponibilidad.

**Bucket** es la unidad donde vamos a almacenar la información en S3, su identificador se encuentra compuesto por la región donde fue creado, la dirección de Amazon AWS y el nombre del bucket. Para los casos cuando queramos acceder a un objeto simplemente se le suma el nombre del objeto, este debe ser único, en minúsculas y no se permiten los caracteres especiales salvo **_** y **-**. El nombre de un Bucket debe ser único a nivel global.

### Comentarios:

* **Ernesto Lázaro Guerrero** (3) [723700](https://platzi.com/comentario/723700/) 

	Identificador de **Bucket** , **objeto** y **Web Estática**.
	
	![Captura de Pantalla 2019-09-05 a la\(s\) 20.44.09.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-09-05%20a%20la%28s%29%2020.44.09-a1b1d483-4586-4b43-b6a0-b2162aa47be2.jpg)

* **Juan Sebastián Bonilla Sanchez** (1) [1002530](https://platzi.com/comentario/1002530/) 

	Interesantes las aclaraciones del bucket!

* **jorge-gianareas** (1) [966863](https://platzi.com/comentario/966863/) 

	Dependiendo de la clase de S3 va a variar la durabilidad y disponibilidad.
	
	Bucket es la unidad donde vamos a almacenar la información en S3, su identificador se encuentra compuesto por la región donde fue creado, la dirección de Amazon AWS y el nombre del bucket. Para los casos cuando queramos acceder a un objeto simplemente se le suma el nombre del objeto, este debe ser único, en minúsculas y no se permiten los caracteres especiales salvo _ y -. El nombre de un Bucket debe ser único a nivel global.

* **jorge-gianareas** (1) [966860](https://platzi.com/comentario/966860/) 

	S3 es almacenamiento de objetos como archivos, PDF’s, imágenes, etc. Dentro de S3 contamos con diferentes tipos de almacenamiento:
	
	S3 Standar  
	S3 IA  
	S3 IA One Zone  
	Glacier

* **johncastillotellez7** (1) [880020](https://platzi.com/comentario/880020/) 

	claro q es super importante el bucket, que es la unidad o medida donde se almacera la informacion, en las bases de datos seria el datafile, q es el archivo fisico donde se almacena la info.

* **carlosbazanhuaman** (1) [836907](https://platzi.com/comentario/836907/) 

	cada servicio tiene un costo diferente o todos se pueden usar en el mismo paquete?

* **carlosextra1** (1) [441105](https://platzi.com/comentario/441105/) 

	Puedo acceder a archivos alojados en s3 solo llamandolo con una url, pero la aplicacion estar en otro server, por ejemplo en azure de microsoft? y solo motrar el archivo si el usuario esta logeado en la aplicacion que esta en azure.

	* **Carlos Andrés Zambrano Barrera** [441105] (2)

		Si se puede hacer, para estos casos de uso se usan URLs pre firmadas las cuales se usan para casos donde se quiere acceder al objeto como en el caso que tu mencionas. Mira <https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/PresignedUrlUploadObject.html>

	* **Ernesto Jose Gabriel Lopez Bravo** [441105] (1)

		Si como indican con la URL, y asignandole el permiso ya sea publico o limitado al endpoint de tu app

	* **juancajamarca** [441105] (1)

		Creo que eso ya sería lógica de tu código.

* **carlosextra1** (1) [47299](https://platzi.com/comentario/441105/) 
Puedo acceder a archivos alojados en s3 solo llamandolo con una url, pero la aplicacion estar en otro server, por ejemplo en azure de mic...

	* **Carlos Andrés Zambrano Barrera** [47299] (2)

		Si se puede hacer, para estos casos de uso se usan URLs pre firmadas las cuales se usan para casos donde se quiere acceder al objeto como en el caso que tu mencionas. Mira <https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/PresignedUrlUploadObject.html>

* **anderson-estiven-holguin** (0) [1007289](https://platzi.com/comentario/1007289/) 

	.Utilizar las características de S3 como por ejemplo replicación tienen algún costo adicional a lo que cobra aws por el almacenamiento?

## 0040. Versionamiento de archivos en S3 [15036](https://platzi.com/clases/1424-storage-aws/15036-versionamiento-de-archivos-en-s3/)

### Descripción:


Tener un control de versiones de tus archivos es importante y necesario cuando manejamos información muy delicada. En los casos donde tenemos un error o cargamos un archivo incompleto siempre podremos volver a la versión anterior de nuestro archivo.

Al momento de ir añadiendo varias versiones de un archivo AWS va a poner un tag al último archivo para tener claro que es esta la última versión. Es importante tener en cuenta que la característica de versionamiento te va a cobrar por el almacenamiento total de tus archivos, es decir la última versión y todas sus versiones anteriores.

### Links:

* [Uso del control de versiones - Amazon Simple Storage Service](https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/Versioning.html)

### Comentarios:

* **Guido Arce** (4) [425698](https://platzi.com/comentario/425698/) 

	Aunque puede ser algo trivial, es importante mencionar que el versionamiento en AWS es automático como se ve en la clase siempre y cuando el nombre del archivo (identificador) sea el mismo. 😃

	* **carlosextra1** [425698] (1)

		es correcto, pero que pasa si el mismo nombre esta en varias carpetas, sigue funcionando igual?

	* **Carlos Andrés Zambrano Barrera** [425698] (1)

		Como la estructura es diferente y su ubicación, sigue funcionando.

* **jorge-gianareas** (2) [966870](https://platzi.com/comentario/966870/) 

	Al momento de ir añadiendo varias versiones de un archivo AWS va a poner un tag al último archivo para tener claro que es esta la última versión. Es importante tener en cuenta que la característica de versionamiento te va a cobrar por el almacenamiento total de tus archivos, es decir la última versión y todas sus versiones anteriores.

* **johncastillotellez7** (2) [880042](https://platzi.com/comentario/880042/) 

	este es un excelente feature de s3 para no perder o eliminar informacion de versiones anteriores. muchas veces se sobreescriben o se pierden. excelente cualidad

	* **johncastillotellez7** [880042] (1)

		bueno al fin y al cabo amazon cobra por lo que se use . asi q justo que cobre lo que se utilizo en este caso espacio y versiones. potente este feature. excelente para auditorias y copias de info

* **christian jordy mamani sucasaire** (2) [58589](https://platzi.com/comentario/578955/) 
Tengo una duda: Tengo un ec2 tipo t2-medium creado, la cual le di un tamaño de 40 gb, porque aun inicio pensaba ahy almacenar los videos ...

	* **juanmoya** [58589] (2)

		Esta calculadora puede servir para saber el costo de cada servicio.  
		<https://calculator.s3.amazonaws.com/index.html>

* **jorge-gianareas** (1) [966869](https://platzi.com/comentario/966869/) 

	Tener un control de versiones de tus archivos es importante y necesario cuando manejamos información muy delicada. En los casos donde tenemos un error o cargamos un archivo incompleto siempre podremos volver a la versión anterior de nuestro archivo.

* **christian jordy mamani sucasaire** (1) [578955](https://platzi.com/comentario/578955/) 

	Tengo una duda: Tengo un ec2 tipo t2-medium creado, la cual le di un tamaño de 40 gb, porque aun inicio pensaba ahy almacenar los videos grabados los cuales ivan a ser utilizado para que el sitio web lo reproduzca. Si quiero almacenar los videos en s3. ¿cuanto sera el costo? ¿que tipo de version s3 debo usar? ¿que cambios debo realizar en mi ec2?.

	* **juanmoya** [578955] (2)

		Esta calculadora puede servir para saber el costo de cada servicio.  
		<https://calculator.s3.amazonaws.com/index.html>

	* **Carlos Andrés Zambrano Barrera** [578955] (1)

		PRimero debe definir lo siguiente:  
		Tamano aprovisionado.  
		cuantas consultas de tipo GET requieres al mes aproximadamente.
		
		Con esos datos determinamos el tipo de S3 y pricing.

	* **juancajamarca** [578955] (1)

		Sólo sube el vídeo y listo. Es costo es demasiado bajo.

* **javandresmoreno** (1) [521538](https://platzi.com/comentario/521538/) 

	Tengo un problema con los buckets creados en mi cuenta de Amazon S3, porque no puedo cargar archivos ni nada. Todos me aparecen con un error…  
	![ERROR.jpg](https://static.platzi.com/media/user_upload/ERROR-5b7f6237-8cd0-4075-b184-20305ef941d4.jpg)
	
	Me podrían colaborar por favor para saber que debo hacer? Tampoco los puedo eliminar. Gracias

	* **ebar0n (Platzi)** [521538] (1)

		Creo que tuviste problemas al asignar permisos, te recomiendo ver [la documentacion](https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/s3-access-control.html)
		
		Inicialmente revisa con cual rol creaste los buckets.

	* **Carlos Andrés Zambrano Barrera** [521538] (2)

		Pregunta… Verifica que tu usuario con el que estas creando los buckets tenga una policy con permisos en S3. Esos buckets fueron creados por tu usuario o por otro?

	* **javandresmoreno** [521538] (1)

		@czam01 Estos buckets no los cree con un usuario en específico. Los cree con la cuenta de propietario.
		
		![aws.jpg](https://static.platzi.com/media/user_upload/aws-a6246ed3-13b4-4bf9-b5d7-dd4c2af7c75f.jpg)
		
		Sin embargo no sé si es por esta ruta donde se verifica.  
		También tenía un usuario creado en una clase anterior de fundamentos de aws, lo eliminé pensando que depronto ese era el error, pero de todas maneras no se ve reflejado.
		
		Tampoco puedo borrarlos.

	* **javandresmoreno** [521538] (2)

		Bueno gracias a la colaboración del profe Carlos, supe cual era el problema:
		
		* Inicialmente pensamos que era mi usuario root, porque al añadir un nuevo usuario con permisos de administrador e ingresar desde otra computadora no aparecía los errores que sí aparecían en el root.
		* Luego usé otro usuario nuevo en mi computadora también con permisos de administrador y oh! sorpresa tampoco funcionó. Aparecían los mismos errores.
		* Entonces deduje que o era mi computadora o el navegador que estaba usando (google chrome).
		* Limpié todo borrando el historial de navegación, pero cuándo volví a ingresar salieron los mismos errores…
		* Entonces dije, intentemos en el navegador de incognito, y señores, efectivamente funcionó todo con normalidad. Es decir el problema en mi computadora por lo menos, es en el navegador normal. En el modo incognito funciona a la perfección con el usuario root normal.
		
		
		
		Gracias a todos por su inmensa ayuda, en especial a @czam01.
		
		Seguimos!

* **Jann-Mor** (1) [475795](https://platzi.com/comentario/475795/) 

	¿Que tanto conviene usar el S3 de amazon para guardar mas de mil audios que tienen una duracion de una hora cada uno?

	* **Carlos Andrés Zambrano Barrera** [475795] (2)

		Desde mi punto de vista es la mejor opción a nivel pricing, aunque creo que lo primero es saber qué quieres hacer con esos audios? para un sitio web que los reproduzca, como backup, para que usuarios los descarguen? Muchas empresas utilizan como repo de esos archivos S3 pero hay que tener más variables en cuenta, otra de ellas puede ser el tamano y cómo los vas a subir, recuerda que de todo eso depende la mejor alternativa para tu caso de uso

	* **ebar0n (Platzi)** [475795] (1)

		Aparte del precio, diria que la seguridad de tus archivos y el ancho de banda, ya que con ciertas opciones puedes tener todo tu contenido encriptado y protegido, y como seran archivos pesados, si no se guardan en un servicio como amazon s3, el ancho de banda sera un problema, ya que puede saturar la red.
		
		Te recomiendo hacer una combinacion de s3 con cloudfront.

* **edisoncastro14** (1) [467746](https://platzi.com/comentario/467746/) 

	¿Esta configuración la toma por cada carpeta o archivo en el bucket?

	* **edisoncastro14** [467746] (1)

		Ya lo probé y si toma las subcarpetas.

	* **Carlos Andrés Zambrano Barrera** [467746] (3)

		El toma todos los objetos dentro del bucket, ya que los tengas ordenado por folders no hay problema igual te sirve.

* **alexgv04** (1) [61900](https://platzi.com/comentario/629682/) 
puedo configurar el versionamiento para almacenar solo las ultimas dos versiones?

	* **Carlos Andrés Zambrano Barrera** [61900] (1)

		hasta el momento esta funcionalidad no es posible.

* **javandresmoreno** (1) [53757](https://platzi.com/comentario/521538/) 
Tengo un problema con los buckets creados en mi cuenta de Amazon S3, porque no puedo cargar archivos ni nada. Todos me aparecen con un er...

	* **ebar0n (Platzi)** [53757] (1)

		Creo que tuviste problemas al asignar permisos, te recomiendo ver [la documentacion](https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/s3-access-control.html)
		
		Inicialmente revisa con cual rol creaste los buckets.

* **Jann-Mor** (1) [50093](https://platzi.com/comentario/475795/) 
¿Que tanto conviene usar el S3 de amazon para guardar mas de mil audios que tienen una duracion de una hora cada uno?

	* **Carlos Andrés Zambrano Barrera** [50093] (2)

		Desde mi punto de vista es la mejor opción a nivel pricing, aunque creo que lo primero es saber qué quieres hacer con esos audios? para un sitio web que los reproduzca, como backup, para que usuarios los descarguen? Muchas empresas utilizan como repo de esos archivos S3 pero hay que tener más variables en cuenta, otra de ellas puede ser el tamano y cómo los vas a subir, recuerda que de todo eso depende la mejor alternativa para tu caso de uso

* **edisoncastro14** (1) [49472](https://platzi.com/comentario/467746/) 
¿Esta configuración la toma por cada carpeta o archivo en el bucket?

	* **edisoncastro14** [49472] (1)

		Ya lo probé y si toma las subcarpetas.

## 0050. Sitio web estático [15035](https://platzi.com/clases/1424-storage-aws/15035-sitio-web-estatico/)

### Descripción:


Podremos utilizar nuestro propio dominio como en cualquier sitio web estático, para ello usaremos **Route 53** que es el servicio encargado de la parte de DNS y gestión de dominios en S3.

En los sitios web estáticos debes tener en cuenta que el dominio deberá llamarse igual al bucket, los archivos index y error deben ser públicos, debe ser configurado con el servicio Route 53.

### Links:

* [Alojamiento de un sitio web estÃ¡tico en Amazon S3 - Amazon Simple Storage Service](https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/WebsiteHosting.html)

### Comentarios:

* **carlosextra1** (4) [448606](https://platzi.com/comentario/448606/) 

	Puedo publicar una spa (single page aplication) en s3?

	* **Diego Alexander Forero Higuera (Platzi)** [448606] (4)

		En teoría podría funcionar, pero el uso de S3 es para los archivos estaticos, en s3 puedes almacenar los archivos JS, CSS, Imágenes, Fuentes de tu SPA pero el entry point (index.html) debe estar en un servidor ademas si usas algo como express para manejar enpoints debes ejecutar node y esto no es posible hacerlo en s3

	* **Oscar Barajas Tavares (Platzi)** [448606] (3)

		Complemento la respuesta de Gollum23, Si es posible, aquí he subido un ejemplo de una “SPA” con React - Router - Auth0  
		<http://quetzalcoatl.cc.s3-website-us-east-1.amazonaws.com/>

	* **Carlos Andrés Zambrano Barrera** [448606] (1)

		Gracias @gndx

	* **Brayan Mamani** [448606] (1)

		Genial !!

	* **juancajamarca** [448606] (1)

		Claro que sí. Cuando la quieras subir, sólo compila (haz build) a la aplicación, y esto te generará unos archivos estáticos, los cuales deberás subir a S3.

* **Nestor Alfonso Portela Rincón** (3) [465258](https://platzi.com/comentario/465258/) 

	Si subo una página web estática a S3, este unicamente me va a cobrar por el espacio que ocupen los archivos o por el tráfico que este sitio genere ?

	* **Carlos Andrés Zambrano Barrera** [465258] (2)

		Debes tener en cuenta que se te van a cobrar los siguientes ítems:  
		1- El espacio que ocupa los archivos dentro de S3.  
		2- La transferencia (Depende de la cantidad de visitas que tenga el sitio y de tus files estáticos).  
		3- Si lo tienes asociado a un dominio te cobran la zona mensual.
		
		Para más detalles mira --> <https://aws.amazon.com/es/s3/pricing/>

	* **juancajamarca** [465258] (1)

		El servicio de S3 sólo te cobrará por el almacenamiento de los archivos. Por aparte, el servicio de Route 53 te cobrará por la zona hosteada.

* **Jann-Mor** (2) [475807](https://platzi.com/comentario/475807/) 

	¿Qué tan recomendable es comprar el dominio con AWS?

	* **Carlos Andrés Zambrano Barrera** [475807] (3)

		Es recomendado, porque si tienes toda la infra dentro de AWS los cambios que hagas los verás reflejados inmediatamente.

	* **christian jordy mamani sucasaire** [475807] (1)

		Pienso que si es recomendado, pero si hago referencia en costos, ahy creo que es un poco caro con respecto a otras empresas que dan servicio de dominio.

	* **juancajamarca** [475807] (1)

		100% recomendado.

* **Daniel Tibavisco** (2) [424481](https://platzi.com/comentario/424481/) 

	Carlos cuando intento hacer publicos el index.html y el error.html me aparece un error de acceso denegado, a que se puede deber esto?

	* **Juan Pablo Castrillón** [424481] (1)

		Verifica si le asignaste los permisos de lectura al bucket.

	* **Daniel Tibavisco** [424481] (1)

		Correcto, el error estaba en la configuración de acceso público, gracias

	* **Carlos Andrés Zambrano Barrera** [424481] (1)

		Veo que ya te respondieron… Cualquier duda estare atento!

* **jorge-gianareas** (1) [966875](https://platzi.com/comentario/966875/) 

	En los sitios web estáticos debes tener en cuenta que el dominio deberá llamarse igual al bucket, los archivos index y error deben ser públicos, debe ser configurado con el servicio Route 53.

* **jorge-gianareas** (1) [966874](https://platzi.com/comentario/966874/) 

	Podremos utilizar nuestro propio dominio como en cualquier sitio web estático, para ello usaremos Route 53 que es el servicio encargado de la parte de DNS y gestión de dominios en S3.

* **Israel Yance** (1) [958373](https://platzi.com/comentario/958373/) 

	Si tienen problemas porque no les aparece el ‘Make Public’:
	
	* Vayan a las configuraciones del bucket
	* Ir a la pestaña Permissions
	* Quitar el chek a ‘Block all public access’ y guardar.
	
	

* **johncastillotellez7** (1) [880105](https://platzi.com/comentario/880105/) 

	al momento de subir los archivos de index y error esta ok pero al tratar de cambiarlos a make public no aparece la opcion? como activarlo?

	* **Israel Yance** [880105] (1)

		Me pasó lo mismo. Lo que hay que hacer es ir a las configuraciones del bucket, ir a Permissions y desbloquear el acceso público.

* **Mario Barbosa** (1) [683994](https://platzi.com/comentario/683994/) 

	Si continua apareciendo el error de acceso denegado, abran la consola desde modo incógnito y repitan los pasos

* **johncastillotellez7** (1) [76030](https://platzi.com/comentario/880109/) 
al momento de subir los archivos de index y error esta ok pero al tratar de cambiarlos a make public no aparece la opcion? como activarlo??

	* **William Barriga** [76030] (1)

		¡Hola!  
		ahora amazon cuando das en la opción propiedades y seleccionas Alojamiento de sitios web estáticos este te lo configura de forma automatica

* **Nestor Alfonso Portela Rincón** (1) [49277](https://platzi.com/comentario/465258/) 
Si subo una página web estática a S3, este unicamente me va a cobrar por el espacio que ocupen los archivos o por el tráfico que este sit...

	* **Carlos Andrés Zambrano Barrera** [49277] (2)

		Debes tener en cuenta que se te van a cobrar los siguientes ítems:  
		1- El espacio que ocupa los archivos dentro de S3.  
		2- La transferencia (Depende de la cantidad de visitas que tenga el sitio y de tus files estáticos).  
		3- Si lo tienes asociado a un dominio te cobran la zona mensual.
		
		Para más detalles mira --> <https://aws.amazon.com/es/s3/pricing/>

* **Daniel Tibavisco** (1) [45822](https://platzi.com/comentario/424481/) 
Carlos cuando intento hacer publicos el index.html y el error.html me aparece un error de acceso denegado, a que se puede deber esto?

	* **Juan Pablo Castrillón** [45822] (1)

		Verifica si le asignaste los permisos de lectura al bucket.

## 0060. Logs a nivel de objetos [15038](https://platzi.com/clases/1424-storage-aws/15038-logs-a-nivel-de-objetos/)

### Descripción:


Podemos activar el Object-level Logging dentro de un bucket en S3 para llevar registro de todas las acciones que se realicen en este, esta funcionalidad nos sirve cuando tenemos buckets con información crítica. Al activar el Object-level Logging debemos conectarlo a CloudTrail.

### Links:

* [Online JSON Viewer](http://jsonviewer.stack.hu/)

* [Â¿CÃ³mo puedo habilitar el registro en el nivel de objeto para un bucket de S3 con eventos
         de datos de AWS CloudTrail? - Amazon Simple Storage Service
      ](https://docs.aws.amazon.com/es_es/AmazonS3/latest/user-guide/enable-cloudtrail-events.html)

### Comentarios:

* **Cristian Camilo Alvarado Beltran** (4) [572794](https://platzi.com/comentario/572794/) 

	Me gustan las clases de este docente porque pone ejemplos claros sobre su uso en el trabajo.

* **vcentt-lopez** (4) [477936](https://platzi.com/comentario/477936/) 

	Wow!!!, está genial lo de CloudWatch, hay que hacer laboratorio para ver toda ls funcionalidad que podemos implementar en los futuros proyectos

	* **Carlos Andrés Zambrano Barrera** [477936] (1)

		Espero puedas probarla, me dejas saber si tienes dudas!

* **johncastillotellez7** (3) [884452](https://platzi.com/comentario/884452/) 

	tan solo para aclarar cuando el profe carlos pronuncia bucket en ingles es backet y la otra palabra que dice bastantes veces es cloud que se pronuncia “claud” “treil”-cloud trail. con eso todas las personas aprenden la fonetica correcta de esas palabras.Saludos

* **Diego Fernando Romero Romero** (3) [652031](https://platzi.com/comentario/652031/) 

	Interesante contenido, hubiese sido muy bueno tener otra clase para CloudWatch conectado con cloudtrail.

* **jorge-gianareas** (1) [966876](https://platzi.com/comentario/966876/) 

	Podemos activar el Object-level Logging dentro de un bucket en S3 para llevar registro de todas las acciones que se realicen en este, esta funcionalidad nos sirve cuando tenemos buckets con información crítica. Al activar el Object-level Logging debemos conectarlo a CloudTrail.

* **johncastillotellez7** (1) [884499](https://platzi.com/comentario/884499/) 

	Carlos una pregunta, puedes mostrar en un ejemplo sensillo como realizar un ejercicio para activar smn y sqs para activar las notificaciones. y hacerlo practico.  
	gracias

* **johncastillotellez7** (1) [882971](https://platzi.com/comentario/882971/) 

	interesante info para hacer el tracking the los logs

* **josehernandezrcom** (1) [630674](https://platzi.com/comentario/630674/) 

	Hola, pregunta. en el minuto 9:12 dices que el servicio envía una notificación de que alguien esta “intentando” eliminar un archivo, ¿Quieres decir que el servicio también evita la eliminación previa autorización? o que el archivo si se elimina y te notifica que ya fue ejecutada la acción y luego puedes reestablecerlo con el versionamiento.

	* **Diego Alexander Forero Higuera (Platzi)** [630674] (4)

		AWS CloudTrail es solo un servicio de auditoria sobre las acciones que se hagan en la cuenta de AWS, este puede enviar notificaciones pero en ningún momento evita que se tome alguna acción, esto de debe manejar a nivel de permisos de los diferentes usuarios que se tengan en la cuenta de AWS.
		
		Puedes prevenir el borrado de archivos de los buckets de s3 por medio del bucket policy

	* **juancajamarca** [630674] (1)

		En realidad no te avisa que se está intentando eliminar un archivo, te avisa que dicho archivo fue eliminado.

* **jaime repizo** (1) [424965](https://platzi.com/comentario/424965/) 

	Habilitar lo logs en S3 genera algún costo adicional ?

	* **Madrov** [424965] (3)

		Si, cualquier servicio de AWS tiene un costo. Si habilitas logs en cloudwatch o cloudtraili tienes que pagar por esos servicios. Pero es muy muy barato, mira los precios de cloudtrail <https://aws.amazon.com/cloudtrail/pricing/>

	* **carlosextra1** [424965] (1)

		Gracias @madrow, buen aporte.

	* **Carlos Andrés Zambrano Barrera** [424965] (3)

		En este puedes tener costo de otros servicios:  
		1- CloudTrail  
		2- Cloudwatch.  
		3- Si mandas los logs a otro bucket tendrás el costo que estos logs ocupen en almacenamiento.

## 0070. Transferencia acelerada [15037](https://platzi.com/clases/1424-storage-aws/15037-transferencia-acelerada/)

### Descripción:


Tomando ventaja del servicio de CDN de AWS podemos cargar nuestra información de forma más rápida, esta característica no se encuentra disponible en buckets que contengan puntos ( _._ ) en su nombre.

La transferencia acelerada te será sumamente útil cuando tengas que subir información a tu bucket, pero tú no te encuentres en la misma región donde creaste tu bucket.

### Links:

* [AceleraciÃ³n de transferencia de Amazon S3 - Amazon Simple Storage Service](https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/transfer-acceleration.html)

### Comentarios:

* **Ernesto Jose Gabriel Lopez Bravo** (5) [610844](https://platzi.com/comentario/610844/) 

	Este enlace también te puede servir:  
	ping.psa.fun  
	te da información sobre la latencia hacia las regiones AWS

	* **FizIrvin** [610844] (1)

		gracias, justo estaba buscando esa información.

* **Juan Emmanuel Díaz** (4) [553480](https://platzi.com/comentario/553480/) 

	comparto link que sirve para medir la latencia que tenemos hacia una region de AWS [https://www.cloudping.info/](url)

* **Arjun4_0** (3) [447709](https://platzi.com/comentario/447709/) 

	¿Aplica como caso de uso si necesito subir archivos muy pesados?

	* **Carlos Andrés Zambrano Barrera** [447709] (3)

		Depende del tamano del archivo, recuerda que hay limites en operaciones tipo PUT de 5GB. Si se podría usar pero qué tamano tiene? O recuerda la de carga multiparte!

	* **johncastillotellez7** [447709] (1)

		Individual Amazon S3 objects can range in size from a minimum of 0 bytes to a maximum of 5 terabytes. The largest object that can be uploaded in a single PUT is 5 gigabytes lo encuentras en AWS website

	* **juancajamarca** [447709] (1)

		Por supuesto.

* **jorge-gianareas** (2) [966879](https://platzi.com/comentario/966879/) 

	<https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/transfer-acceleration.html>

* **pblfergt** (2) [897807](https://platzi.com/comentario/897807/) 

	Me encanta esta feature de s3

* **johncastillotellez7** (2) [884508](https://platzi.com/comentario/884508/) 

	aqui se encuentra la informacion en detalle de upload capacity a aws  
	https:// [docs.aws.amazon.com/AmazonS3/latest/dev/qfacts.html](http://docs.aws.amazon.com/AmazonS3/latest/dev/qfacts.html)

* **jorge-gianareas** (1) [966881](https://platzi.com/comentario/966881/) 

	La transferencia acelerada te será sumamente útil cuando tengas que subir información a tu bucket, pero tú no te encuentres en la misma región donde creaste tu bucket.

* **jorge-gianareas** (1) [966877](https://platzi.com/comentario/966877/) 

	Tomando ventaja del servicio de CDN de AWS podemos cargar nuestra información de forma más rápida, esta característica no se encuentra disponible en buckets que contengan puntos (.) en su nombre.

* **Emmanuel Sosa Reyes** (1) [950661](https://platzi.com/comentario/950661/) 

	¿Tiene algún costo utilizar este feature?

	* **Demian Arenas (Platzi)** [950661] (1)

		Hola Emmanuel, tiene un costo desde 0.04 USD por GB, puedes revisar en [este enlace](https://aws.amazon.com/es/s3/pricing/) en el apartado de “Transferencia de datos”.

* **Arjun4_0** (1) [47836](https://platzi.com/comentario/447709/) 
¿Aplica como caso de uso si necesito subir archivos muy pesados?

	* **Carlos Andrés Zambrano Barrera** [47836] (3)

		Depende del tamano del archivo, recuerda que hay limites en operaciones tipo PUT de 5GB. Si se podría usar pero qué tamano tiene? O recuerda la de carga multiparte!

## 0080. Eventos en S3 [15040](https://platzi.com/clases/1424-storage-aws/15040-eventos-en-s3/)

### Descripción:


Los eventos nos servirán en los casos donde queremos recibir notificaciones cuando se ejecute determinada acción dentro de un bucket con información importante.

Al momento de crear un evento debemos ponerle un nombre, indicarle la acción que debe notificar, además podemos especificarle la carpeta y el tipo de archivo. Por último, debemos indicarle hacia donde debe mandar la notificación, puede ser hacia:

* SNS Topic.
* SQS Queue.
* Lambda Function.



### Comentarios:

* **jorge-gianareas** (2) [966885](https://platzi.com/comentario/966885/) 

	Al momento de crear un evento debemos ponerle un nombre, indicarle la acción que debe notificar, además podemos especificarle la carpeta y el tipo de archivo. Por último, debemos indicarle hacia donde debe mandar la notificación, puede ser hacia:
	
	SNS Topic.  
	SQS Queue.  
	Lambda Function.

* **jsteven** (2) [554638](https://platzi.com/comentario/554638/) 

	En un proyecto en el que trabajé configuré los eventos de s3 para que en el momento en que se suba un archivo en cierta carpeta con cierta extensión, una lambda lo valide y haga el llamado para iniciar una Stepfunction con la lógica necesaria para procesarlo. Es una excelente opción para automatización.

	* **Dante Castillo Z.** [554638] (1)

		Gracias por el dato!.

* **jorge-gianareas** (1) [966884](https://platzi.com/comentario/966884/) 

	Los eventos nos servirán en los casos donde queremos recibir notificaciones cuando se ejecute determinada acción dentro de un bucket con información importante.

* **johncastillotellez7** (1) [884577](https://platzi.com/comentario/884577/) 

	los eventos disparan acciones y esos asu vez generar procesos, claro van en cascada como muchas cosas en computacion

* **carlosextra1** (1) [448631](https://platzi.com/comentario/448631/) 

	puedo tener un vps windows en aws y todos los archivos como pdf y xml almacenados en s3? y sin problema mandar llamar los archivos desde una app web para descargarlos y consultarlos?

	* **Arjun4_0** [448631] (1)

		No entiendo bien la necesidad de la instancia EC2 si tu webapp va a consumir archivos que estan en S3. Tu webapp podria llamar los objetos directamente desde S3.

	* **vcentt-lopez** [448631] (1)

		Así es Carlos, se puede hacer sin problemas así como lo dices, en la instancia podrías tener tu página web consumiendo esos archvos tambien y des la App también los puedes consultar.

	* **Carlos Andrés Zambrano Barrera** [448631] (1)

		Se puede hacer el webserver en ec2 y consumirlos desde s3, usualmente eso hacemos en sitios web de alto tráfico, mejora el rendimiento! También he visto escenarios donde se usa efs para este mismo fin y lo que haces por ejemplo es que el /var/www/html montarlo en el efs (esto en caso de Linux) ahora con windows hay nuevos servicios que permitirian funcionalidades similares.

	* **juancajamarca** [448631] (1)

		Claro que sí.

* **carlosextra1** (1) [47911](https://platzi.com/comentario/448631/) 
puedo tener un vps windows en aws y todos los archivos como pdf y xml almacenados en s3? y sin problema mandar llamar los archivos desde ...

	* **Arjun4_0** [47911] (1)

		No entiendo bien la necesidad de la instancia EC2 si tu webapp va a consumir archivos que estan en S3. Tu webapp podria llamar los objetos directamente desde S3.

## 0090. Replicación [15039](https://platzi.com/clases/1424-storage-aws/15039-replicacion/)

### Descripción:


La característica de replicar información se realiza solamente para buckets de una región a otra, no es posible pasar de un bucket de una misma región a otro de la misma.

El proceso de replicación se realiza de forma asíncrona. Es común realizar réplicas para Data Recovery, Auditorías y Compliance.

Al momento de replicar la información podemos indicarle que sean todos los objetos del bucket, los objetos que se encuentren dentro de determinada carpeta o aquellos que tengan cierto tag. Además, podemos replicar objetos encriptados.

### Links:

* [ReplicaciÃ³n entre regiones (CRR) - Amazon Simple Storage Service](https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/crr.html)

### Comentarios:

* **Enzo Aliatis** (5) [629666](https://platzi.com/comentario/629666/) 

	Me parece lo mejor como el profesor nos enseña la herramienta y después nos da casos de uso.

* **jorge-gianareas** (2) [966887](https://platzi.com/comentario/966887/) 

	La característica de replicar información se realiza solamente para buckets de una región a otra, no es posible pasar de un bucket de una misma región a otro de la misma.
	
	El proceso de replicación se realiza de forma asíncrona. Es común realizar réplicas para Data Recovery, Auditorías y Compliance.

* **Luis Alberto Bernal** (2) [655212](https://platzi.com/comentario/655212/) 

	Si vale con los casos de usos son los mejores y es mas fácil de entender

* **Johan Manuel Merello Ortecho** (1) [1009916](https://platzi.com/comentario/1009916/) 

	al día de hoy S3 ya te permite hacer replicación en una misma región

* **jorge-gianareas** (1) [966888](https://platzi.com/comentario/966888/) 

	Al momento de replicar la información podemos indicarle que sean todos los objetos del bucket, los objetos que se encuentren dentro de determinada carpeta o aquellos que tengan cierto tag. Además, podemos replicar objetos encriptados.

* **juancajamarca** (1) [928691](https://platzi.com/comentario/928691/) 

	Casos de usos muy reales.

* **johncastillotellez7** (1) [884614](https://platzi.com/comentario/884614/) 

	importante replication de buckets con objetos y archivos entre diferentes regiones de forma asincrona. activando a enable la opcion.

* **vcentt-lopez** (1) [478859](https://platzi.com/comentario/478859/) 

	¿Se pueden replicar los 3 tipos de encriptación que permite?

	* **Carlos Andrés Zambrano Barrera** [478859] (3)

		Ojo en la replicación debes tener en cuenta algunas cosas con el cifrado…  
		1- el bucket destino puede tener policy que encripten.  
		2- las llaves de cifrado son regionales y si el bucket destino esta en otra región pues la llave cambiaría.
		
		Debemos tener en cuenta esos factores.

* **DiegoRP** (1) [475416](https://platzi.com/comentario/475416/) 

	Genial esta característica.  
	Te suena mucho mejor cifrado a encriptación (sumado a que esta última no existe formalmente).  
	Un saludo!

	* **Carlos Andrés Zambrano Barrera** [475416] (1)

		Gracias, tienes razón, estos conceptos uno siempre los maneja en ingles y hace la traducción textual… Encryption, lo cual no debería ser.

* **vcentt-lopez** (1) [50355](https://platzi.com/comentario/478859/) 
¿Se pueden replicar los 3 tipos de encriptación que permite?

	* **Carlos Andrés Zambrano Barrera** [50355] (3)

		Ojo en la replicación debes tener en cuenta algunas cosas con el cifrado…  
		1- el bucket destino puede tener policy que encripten.  
		2- las llaves de cifrado son regionales y si el bucket destino esta en otra región pues la llave cambiaría.
		
		Debemos tener en cuenta esos factores.

# Clases de storage en S3 [2848]

## 0100. S3 - Estándar [15042](https://platzi.com/clases/1424-storage-aws/15042-s3-estandar/)

### Descripción:


### Comentarios:

* **Jann-Mor** (3) [475907](https://platzi.com/comentario/475907/) 

	Si cuento con mil archivos de audio con duracion de 1 hora c/u recomiendan que use S3 por cuestion de costos y descargas o sigo usando dropbox.

	* **Carlos Andrés Zambrano Barrera** [475907] (3)

		Por costos recomiendo S3, de hecho si no los usas tan a menudo los pasas a S3-IA o Glacier y te ahorraras bastante.

	* **vcentt-lopez** [475907] (1)

		Depende mucho de tu caso de uso, son archivos que son consultados frecuentemente?, o son archivos que van perdiendo vigencia con el tiempo?, etc?

* **johncastillotellez7** (2) [884638](https://platzi.com/comentario/884638/) 

	s3 standard> durabilidad completamente alta,  
	s3 standard acceso poco frecuente  
	s3 unica zona acceso poco frecuente  
	glacier el mas barato y el que guarda con mayor longevidad la info

* **Enzo Aliatis** (1) [629681](https://platzi.com/comentario/629681/) 

	Esos cuadros con información de los precios, ¿Donde los puedo conseguir?

* **Enzo Aliatis** (1) [629674](https://platzi.com/comentario/629674/) 

	Alguien me puede explicar que es el SLA?

	* **Rodolfo Nicacio Ugalde Ochoa** [629674] (4)

		 **Service Level Agreement**

	* **johncastillotellez7** [629674] (1)

		esos son los niveles de acuerdo de servicio. signifca que entre se llega a un acuerdo entre dos partes para dar soporte o respuesta a un servicio. ej: el SLA para solucion de incidentes es de 12 hrs , significa que el proveedor o el equipo de soporte tiene 12 hrs par aresponderle al negocio o dar solucion. etc. son muy utilises para parametrizar los tiempos de respuesta de los equipos de soporte y que tu negocio tenga continuidad. service level agreement. es puro servicio al cliente con metricas

	* **johncastillotellez7** [629674] (1)

		adciional que si se infringe los sla de acuerdo a lo acordado por las partes habran sanciones de diferente indole

	* **juancajamarca** [629674] (1)

		Buena pregunta, y muy buena respuesta @johncastillotellez7

* **Nestor Alfonso Portela Rincón** (1) [465333](https://platzi.com/comentario/465333/) 

	Si yo entro a mi consola de AWS y voy al servicio de S3 y por ejemplo empiezo a revisar algunos documentos, descargarlos, eliminarlos y las demás operaciones que pueda hacer, cada una de ellas va a contar como un tipo de solicitud ? Y la otra pregunta, existe algún tipo de cliente para subir archivos a S3?

	* **vcentt-lopez** [465333] (1)

		Puedes usar Cyberduck

	* **Carlos Andrés Zambrano Barrera** [465333] (3)

		Puedes usar la CLI, las SDK o software de terceros que hacen esas funciones (filezilla).  
		Claro eso te genera solicitudes tipo GET, DELETE depende de lo que hagas.

* **johncastillotellez7** (1) [76294](https://platzi.com/comentario/884652/) 
si se tiene ya un tipo de almacenamiento. aws permite cambiar de un tipo a otro y que proceso hay que realizar? si se tiene bastante inf...

* **Jann-Mor** (1) [50103](https://platzi.com/comentario/475907/) 
Si cuento con mil archivos de audio con duracion de 1 hora c/u recomiendan que use S3 por cuestion de costos y descargas o sigo usando dr...

	* **Carlos Andrés Zambrano Barrera** [50103] (3)

		Por costos recomiendo S3, de hecho si no los usas tan a menudo los pasas a S3-IA o Glacier y te ahorraras bastante.

* **puntoec** (1) [48499](https://platzi.com/comentario/455312/) 
Cuando uso una URL pública para acceder a los objetos del S3, cada solicitud al link me cuenta como un GET? y esto es indiferente del tam...

	* **Carlos Andrés Zambrano Barrera** [48499] (1)

		Si, cada solicitud cuenta como un GET, es indiferente del tamano, sin embargo ten presente que hay un costo por transferencia y ahí sí es importante el tamano del objeto --> <https://aws.amazon.com/es/s3/pricing/>

* **puntoec** (0) [455312](https://platzi.com/comentario/455312/) 

	Cuando uso una URL pública para acceder a los objetos del S3, cada solicitud al link me cuenta como un GET? y esto es indiferente del tamaño del objeto que estoy accediendo o existen límites?

	* **Carlos Andrés Zambrano Barrera** [455312] (1)

		Si, cada solicitud cuenta como un GET, es indiferente del tamano, sin embargo ten presente que hay un costo por transferencia y ahí sí es importante el tamano del objeto --> <https://aws.amazon.com/es/s3/pricing/>

## 0110. S3-IA [15041](https://platzi.com/clases/1424-storage-aws/15041-s3-ia/)

### Descripción:


S3 Infrequent Access o de acceso poco frecuente está diseñado para almacenar objetos que son accedidos con menor frecuencia que S3 Estándar, su costo de almacenamiento es menor, pero el costo de solicitudes es mayor.

### Comentarios:

* **jorge-gianareas** (2) [966893](https://platzi.com/comentario/966893/) 

	S3 Infrequent Access o de acceso poco frecuente está diseñado para almacenar objetos que son accedidos con menor frecuencia que S3 Estándar, su costo de almacenamiento es menor, pero el costo de solicitudes es mayor.

* **johncastillotellez7** (2) [884659](https://platzi.com/comentario/884659/) 

	esto es bien importante lo que dice el profe Carlos, definir bien los archivos standard y los archivos IA es vital , ya q se podran clasificar mejor y adicional tendra menos consumo de costo de almacenamiento igual que trafico de la red.

* **Jordi Santamaría Portolés** (1) [1052113](https://platzi.com/comentario/1052113/) 

	Pero porque guardarias tus datos personales en S3, si puedes guardarlos por ejemplo en google drive que es gratis?

	* **Gabriel De Andrade** [1052113] (1)

		La verdad S3 no está diseñado para guardar datos personales sino archivos de trabajo como por ejemplo archivos de gran peso para el trabajo tipo modelados 3D, Vídeos de alta calidad y todas esas cosas 😛

	* **Jorge Israel Castillo Perez** [1052113] (1)

		Estas soluciones van encaminadas a empresas en mayor proporcion. Resulta que para un usuario personal, sería un costo quizá no justificable un servicio así. Lo más importante es que es parte de un todo a nivel empresas.

* **juancajamarca** (1) [928745](https://platzi.com/comentario/928745/) 

	Acceso a los archivos de una a dos veces por mes.

* **johncastillotellez7** (1) [884672](https://platzi.com/comentario/884672/) 

	caso de uso , al consultar las notas en la universidad . bien . y tambien cuando uno consulta el certificado de libertad de las propiedades a su nombre. o consulta de factura de proveedor de internet. 1 vez por mes

## 0120. S3-IA única zona [15043](https://platzi.com/clases/1424-storage-aws/15043-s3-ia-unica-zona/)

### Descripción:


Es para acceso poco frecuente, similar a S3-IA, pero con la diferencia de que solamente se encontrará en una zona de disponibilidad y tiene un costo menor en almacenamiento por GB.

### Comentarios:

* **José Ricardo Romo Gutiérrez** (3) [479305](https://platzi.com/comentario/479305/) 

	Pero el ejemplo de las miniaturas de foto de perfil, las solicitudes al archivo serian mas de una o dos veces al mes, en tal caso no seria conveniente S3 Standar?

	* **Carlos Andrés Zambrano Barrera** [479305] (3)

		El usuario carga la foto al bucket (S3) una vez generada la miniatura lo podemos pasar a S3-IA-Unica Zona y ahorrariamos costos. La foto original se mantiene y si la miniatura se borra pues la volvemos a generar del file de origen.

* **jorge-gianareas** (1) [966901](https://platzi.com/comentario/966901/) 

	Es para acceso poco frecuente, similar a S3-IA, pero con la diferencia de que solamente se encontrará en una zona de disponibilidad y tiene un costo menor en almacenamiento por GB.

* **johncastillotellez7** (1) [884680](https://platzi.com/comentario/884680/) 

	lo mas importante es que la info se encuentra en una sola zona Availability zone. lo cual la hace mas restringida pero es por su IA

* **Diego Fernando Romero Romero** (1) [652115](https://platzi.com/comentario/652115/) 

	Pero en el tema de la foto seria mucho mejor utilizar S3 Standar porque si las fotos son utilizadas por la aplicación lo hará frecuentemente, no le veo mucha utilidad.

* **José Ricardo Romo Gutiérrez** (1) [50397](https://platzi.com/comentario/479305/) 
Pero el ejemplo de las miniaturas de foto de perfil, las solicitudes al archivo serian mas de una o dos veces al mes, en tal caso no seri...

	* **Carlos Andrés Zambrano Barrera** [50397] (3)

		El usuario carga la foto al bucket (S3) una vez generada la miniatura lo podemos pasar a S3-IA-Unica Zona y ahorrariamos costos. La foto original se mantiene y si la miniatura se borra pues la volvemos a generar del file de origen.

## 0130. Glacier [15044](https://platzi.com/clases/1424-storage-aws/15044-glacier/)

### Descripción:


Glacier solamente será utilizado para backups y data histórica, el precio de almacenamiento por GB es sumamente menor siendo el más económico. Al ser data histórica la disponibilidad de la información es menor, siendo que pedimos la información una vez cada seis meses o cada año.

### Comentarios:

* **Cristian1398** (5) [426772](https://platzi.com/comentario/426772/) 

	2:59 el audio se repite. No se sincroniza con lo que habla el profesor.

	* **Fernando Trasvent** [426772] (1)

		Aun no se corrige el problema del audio.

	* **DiegoRP** [426772] (1)

		Aún nada

	* **José Ricardo Romo Gutiérrez** [426772] (1)

		Aun nada que lo arreglan

* **Nestor Alfonso Portela Rincón** (4) [465926](https://platzi.com/comentario/465926/) 

	Si yo mensualmente estoy generando copias de seguridad de los equipos más importante de mi empresa, enviarlos a guardar a Glacier sería una opción, teniendo en cuenta que al momento de enviarlos, es muy poco probable que los vuelva a necesitar a menos que exista un problema con dicha información y de ser así, a la mano tengo los discos duros fisicos donde está información y Glacier sería como para tener esa información en un lugar ajeno y seguro.

	* **Enrique Alexis Lopez Araujo** [465926] (5)

		Claro creo que seria muy buena opcion usar glacier, si el acceso a esos datos casi no sera muy concurrente, y solo esporadica.

	* **Carlos Andrés Zambrano Barrera** [465926] (6)

		Si de acuerdo, aunque el uso de glacier seria más para información histórica, en ese caso yo dejaría los backups más recientes en S3-IA y al cumplir un periodo de mas de 6 meses los pasaría a Glacier.

	* **vcentt-lopez** [465926] (4)

		@czam01 lo que dices es correcto, solo que como comenta @Nestux091 tiene los discos duros físicos en su poder, por lo tanto no creo que necesite esa información de Glacier, lo quiere solo como respaldo en el caso de que algo le pasara a esos discos

	* **juancajamarca** [465926] (1)

		Buen caso de uso para estos servicios.

* **carlosextra1** (2) [448659](https://platzi.com/comentario/448659/) 

	Ahora si tengo mas claro esto del s3 con precios y sus tipos

* **jorge-gianareas** (1) [966903](https://platzi.com/comentario/966903/) 

	Glacier solamente será utilizado para backups y data histórica, el precio de almacenamiento por GB es sumamente menor siendo el más económico. Al ser data histórica la disponibilidad de la información es menor, siendo que pedimos la información una vez cada seis meses o cada año.

* **johncastillotellez7** (1) [884685](https://platzi.com/comentario/884685/) 

	correcto solo para historial financial data, balances or taxes y tambien para backups de periodos o años pasados. ejemplo backups de los PCs de una compañia.

* **Leandro Antonelli** (1) [439662](https://platzi.com/comentario/439662/) 
Hola. Si uso standard IA. Y uso el comando sync por medio del cli, estoy haciendo una mala opción en el tipo de S3. Al hacer sync, estoy leyendo o listando el contenido deñ bucket en cada sincronizacion? No sé si se entiende mi pregunta. Gracias!

* **Cristian1398** (1) [426771](https://platzi.com/comentario/426771/) 

	Interesante

* **Wilson Montenegro** (1) [72666](https://platzi.com/comentario/820275/) 
Necesito guardar data de las cámaras de vídeo de mi trabajo por 5 años, unos 300 TB estimo por todo este tiempo, es recomendable usar Gla...

	* **Israel Yance** [72666] (1)

		Exacto. Acá mayores refencias:  
		<https://aws.amazon.com/es/glacier/>
		
		El precio va desde 1 USD por terabyte al mes.

* **Nestor Alfonso Portela Rincón** (1) [49328](https://platzi.com/comentario/465926/) 
Si yo mensualmente estoy generando copias de seguridad de los equipos más importante de mi empresa, enviarlos a guardar a Glacier sería u...

	* **Enrique Alexis Lopez Araujo** [49328] (5)

		Claro creo que seria muy buena opcion usar glacier, si el acceso a esos datos casi no sera muy concurrente, y solo esporadica.

## 0140. Ciclo de vida [15046](https://platzi.com/clases/1424-storage-aws/15046-ciclo-de-vida2866/)

### Descripción:


Esta funcionalidad va a mover la información de una clase de almacenamiento a otra cada que pase cierto tiempo. No tendrá la misma frecuencia de accesibilidad un archivo de hace 1 año que uno de hace una semana, por ello el ciclo de vida nos será de utilidad para disminuir los costos de nuestros archivos.

El mínimo de tiempo para pasar objetos a S3-IA es de 30 días. Asimismo, deben pasar 120 días para mover la información a Glacier.

### Comentarios:

* **Arjun4_0** (6) [458269](https://platzi.com/comentario/458269/) 

	Hago una observación: algo que no fue mencionado en este modulo es esto al hacer una transición de datos a Glacier:  
	Cargos de solicitud de archivado de Glacier: cada objeto que pasa a la clase de almacenamiento GLACIER constituye una solicitud de archivo. Se aplica un costo para cada solicitud. Si tiene previsto pasar una cantidad grande de objetos, tenga en cuenta los costos de solicitud  
	fuente: <https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/lifecycle-transition-general-considerations.html>
	
	Espero pueda servirle a alguien puesto que yo me llevé un sorpresa al revisar mi factura de AWS despues de aplicar politicas de ciclo de vida en un bucket con unos cuaaantos GB de informacion. Una sopresa algo co$to$a…

	* **Nestor Alfonso Portela Rincón** [458269] (2)

		Gracias esa aclaración, muy válida.

	* **vcentt-lopez** [458269] (2)

		Y cuales son son los costos?, no los veo en el link que pusiste, gracias.

	* **Carlos Andrés Zambrano Barrera** [458269] (3)

		Muy válida la alcaración, ahora sin embargo en la nueva funcionalidad de Storage puedes cargar directo a glacier sin hacer transición.

	* **Dante Castillo Z.** [458269] (1)

		Gracias por la información.

* **jorge-gianareas** (3) [966909](https://platzi.com/comentario/966909/) 

	El mínimo de tiempo para pasar objetos a S3-IA es de 30 días. Asimismo, deben pasar 120 días para mover la información a Glacier.

* **jorge-gianareas** (1) [966907](https://platzi.com/comentario/966907/) 

	Esta funcionalidad va a mover la información de una clase de almacenamiento a otra cada que pase cierto tiempo. No tendrá la misma frecuencia de accesibilidad un archivo de hace 1 año que uno de hace una semana, por ello el ciclo de vida nos será de utilidad para disminuir los costos de nuestros archivos.

* **johncastillotellez7** (1) [884699](https://platzi.com/comentario/884699/) 

	Ahorrar costos es sin duda una de las razones mas fuertes para cambiar de un tipo de storage a otro.

	* **johncastillotellez7** [884699] (1)

		ademas que tiene precios bien bajos de centavos de dolar, auqnue a gran escala las compañias q decidan migrar haran sus proyecciones.

* **Pedro Ortiz** (1) [635215](https://platzi.com/comentario/635215/) 

	Para objetos previos, si se crean reglas para moverlos a Glacier ¿el número de días que indica “Días después de la creación”, en este caso particular, se refiere a que los 120 días los toma a partir de la creación del objeto en el bucket o la creación de la regla?

	* **juancajamarca** [635215] (1)

		A partir de la creación del objeto en el Bucket.

* **Nestor Alfonso Portela Rincón** (1) [465941](https://platzi.com/comentario/465941/) 

	Esas transiciones que se crearon, que después de 30 días se vayan a SE-IA y luego de estar 120 días en SE-IA se muevan a Glacier, se ejecutan como en ese orden especifico, cierto ?

	* **Carlos Andrés Zambrano Barrera** [465941] (5)

		Si, se ejecutan en ese orden y ten presente que hay requerimientos de tiempo en cada una, por ejemplo de s3 a s3-ia debe haber pasado al menos 30 días.

* **johncastillotellez7** (1) [79072](https://platzi.com/comentario/933098/) 
estoy tratando de eliminar un bucket pero no se deja hacer delete. de que otra manera se puede eliminar. este es el error message? Access...

	* **Erik Ochoa** [79072] (1)

		Parece ser problema de permisos con tu **IAM user** o con tu **role** , revisa eso.
		
		O puedes probar con estos pasos que encontré en inglés:
		
		  1. Open the Amazon S3 Management Console
		  2. Select the Elastic Beanstalk storage bucket.
		  3. Choose Properties.
		  4. Choose Permissions.
		  5. Choose Edit Bucket Policy.
		  6. Choose Delete.
		  7. Choose OK.
		  8. Choose Actions and then choose Delete Bucket.
		
		

* **Nestor Alfonso Portela Rincón** (1) [49329](https://platzi.com/comentario/465941/) 
Esas transiciones que se crearon, que después de 30 días se vayan a SE-IA y luego de estar 120 días en SE-IA se muevan a Glacier, se ejec...

	* **Carlos Andrés Zambrano Barrera** [49329] (5)

		Si, se ejecutan en ese orden y ten presente que hay requerimientos de tiempo en cada una, por ejemplo de s3 a s3-ia debe haber pasado al menos 30 días.

## 0150. Estrategias de migración a la nube [15045](https://platzi.com/clases/1424-storage-aws/15045-estrategias-de-migracion-a-la-nube/)

### Descripción:


### Comentarios:

* **DiegoRP** (2) [475452](https://platzi.com/comentario/475452/) 

	En la carga en paralelo hay que tener en cuenta el uso de ancho de banda. Por ejemplo, si tengo 50Mb de canal, y tengo 1 solo archivo a cargar, este puede usar los 50Mb, en cambio si tengo 2 archivos, el ancho de banda deberá ser compartido, por lo que el tiempo de carga de cada uno baja. Quiero decir que no necesariamente, el dividir un archivo grande en varios pequeños acelera el tiempo de carga, mas bien (diria yo) aumenta considerablemente la tolerancia a fallas.

	* **Carlos Andrés Zambrano Barrera** [475452] (4)

		La carga multiparte es recomendación para objetos mayores a 100MB, Aumenta como dices la tolerancia a fallos, el tema de carga ayuda en internet inestables y en determinados casos uno la usa para mejorar la subida de elementos y el control sobre ellos.

* **johncastillotellez7** (1) [933135](https://platzi.com/comentario/933135/) 

	este appliance snowball es super util ya que tiene un bus de datos de encripcion de 256bit con TPM. es tremendo. adicional la capacidad actual del snowball es de 40 y 80 TB, pero estos prontamente quedaran jubilados aqui esperamos con cuanta capacidad aws ofrecera. quiza 128 TB wow 512 TB

* **Juan David Gonzalez Revelo** (1) [760288](https://platzi.com/comentario/760288/) 

	En el caso de carga multiparte, entre más partes divida el archivo más solicitudes PUT se realizarán y tendra un costo mayor, que si subo el archivo en una sola parte?

	* **juancajamarca** [760288] (1)

		Correcto

* **neok** (1) [617976](https://platzi.com/comentario/617976/) 

	Si entendí bien, en caso de que yo tuviera un archivo, digamos de unos 8GB, no podría subirlo mediante internet a S3 aunque haga una carga multiparte. Cierto?

## 0160. Casos de uso. [15048](https://platzi.com/clases/1424-storage-aws/15048-casos-de-uso/)

### Descripción:


### Comentarios:

* **ricardochl** (10) [463815](https://platzi.com/comentario/463815/) 

	Actualmente en la empresa que laboro estamos desarrollando una aplicación todo en uno para pequeñas y medianas empresas, la app maneja bastante imágenes y archivos, anteriormente lo almacenábamos en la base de datos como binario pero esto era muy lento, y decidimos usar S3 por su rapidez y la gran cantidad de ventajas, y ahora nuestra app es mucho mas rápida.

	* **Carlos Andrés Zambrano Barrera** [463815] (3)

		Excelente noticia!

* **jsteven** (6) [555982](https://platzi.com/comentario/555982/) 

	Un caso de uso real que trabajé con s3 fue exponer un SFTP con filetransfer y utilizar buckets de S3 para compartir información con un aliado, de esta manera pudimos soportar el intercambio de información sin perder las ventajas de los servicios de AWS que se pueden integrar con S3 (KMS, Cloudwatch, Eventos para llamar lambdas y SNS)

	* **hanspereira** [555982] (2)

		Oh me interesa un montón esto, entonces puedes subir y descargar archivos a S3 a través de un SFTP?

* **pblfergt** (2) [902199](https://platzi.com/comentario/902199/) 

	Si quiren hacer diagramas para aws les recomiendo Cloudcraft es ¡nave!  
	[](https://cloudcraft.co/)

	* **juancajamarca** [902199] (1)

		Buenísimo. Buen aporte.

* **johncastillotellez7** (1) [933199](https://platzi.com/comentario/933199/) 

	muy interesante lo que hace EMR elastic Map Reduce junto con glue ETL extract Transform and Loaded. que potentes esos tools.

* **carlosbazanhuaman** (1) [839522](https://platzi.com/comentario/839522/) 

	en el trabajo realizamos log de la alta de clientes, estos archivos se pueden analizar para ver la segmentacion de clientes para marketing

* **Anthony Sebastian Mayol** (1) [632080](https://platzi.com/comentario/632080/) 

	Alguien quiere trabajar en equipo para el reto? 😃

* **Anthony Sebastian Mayol** (1) [632079](https://platzi.com/comentario/632079/) 

	reto almacenamiento en S3, alguno quiere trabajar en equipo?

# Seguridad en S3. [2850]

## 0170. Encriptación en S3 - Llaves administradas por AWS. [15047](https://platzi.com/clases/1424-storage-aws/15047-encriptacion-en-s3-llaves-administradas-por-aws/)

### Descripción:


### Comentarios:

* **Dario Jose Vilchez Perozo** (3) [592616](https://platzi.com/comentario/592616/) 

	Buenas noches ,
	
	Tengo muchas empresas que se realizan backup todo los sabados, de vez en cuando puedes que se necesite esa información para restaurar base de datos que tipo de S3 recomendarian para este tipo de casos.

	* **anibalrojas (Platzi)** [592616] (1)

		Si esas eventualidades son raras, y la recuperación de los datos no tiene que ser instantánea Glacier es una mejor opción (mucho más económica) que S3.

	* **Carlos Andrés Zambrano Barrera** [592616] (5)

		Pregunta…  
		1- “de vez en cuando” si es mas de 1 vez al mes --> Glacier, si es una vez al mes o 2 Se-IA… Si es mas de 3 veces al mes S3.  
		2- Si cuando necesites restaurarla necesitas que lo puedas hacer antes de 3 horas, entonces S3-IA, si puedes esperar mas de 3 horas Glacier.

* **juancajamarca** (2) [935888](https://platzi.com/comentario/935888/) 

	Seguridad en S3
	
	Este área es importante porque si vamos a utilizar S3 para almacenar información crítica, debemos tomar todas las medidas necesarias para que esta información quede completamente segura y salvaguardada en S3.
	
	Protección de datos mediante cifrado en S3
	
	* Server Side Encryption: Cuando AWS provee y administra las llaves de cifrado. 
	  * SSE - S3
	  * SSE - KMS
	  * SSE - l C
	* Client Side Encryption: Cuando el cliente quiere hacer la encriptación de los objetos.
	
	
	
	SSE - S3
	
	AWS se encarga de generar las llaves de cifrado, administrarlas y almacenarlas.  
	El sistema de cifrado utiliza AES-256 (Advanced Encryption Standard de 256 bits).  
	Las llaves quedan almacenadas en IAM > Encryption Keys, y son agrupadas por servicios, por ejemplo: _aws/ebs_.
	
	¿Por qué vamos a usar este tipo en encriptación?
	
	  1. Porque nosotros no queremos tener cargas de administración en el tema de la creación de las llaves o rotación de las llaves.
	  2. Es completamente manejado por AWS, tanto la llave, como la rotación, como la encripción, como el almacenamiento de las llaves.
	
	

* **johncastillotellez7** (1) [936581](https://platzi.com/comentario/936581/) 

	tanto las llaves de encripcion como los datos [encriptados.se](http://encriptados.se) guardan en aws storage.que bien

* **Nealcaffrey3313** (1) [81968](https://platzi.com/comentario/994283/) 
Buenos dias, estoy trabajando en un proyecto donde desde el front se carga un archivo a s3 buket, el problema es que no debemos declarar ...

* **Dario Jose Vilchez Perozo** (1) [59540](https://platzi.com/comentario/592616/) 
Buenas noches , Tengo muchas empresas que se realizan backup todo los sabados, de vez en cuando puedes que se necesite esa información pa...

	* **anibalrojas (Platzi)** [59540] (1)

		Si esas eventualidades son raras, y la recuperación de los datos no tiene que ser instantánea Glacier es una mejor opción (mucho más económica) que S3.

## 0180. Encriptación en S3 - Llaves almacenadas en AWS creadas por el Usuario. [15049](https://platzi.com/clases/1424-storage-aws/15049-encriptacion-en-s3-llaves-almacenadas-en-aws-cread/)

### Descripción:


### Comentarios:

* **juancajamarca** (2) [935933](https://platzi.com/comentario/935933/) 

	SSE - KMS (Key Management Service)
	
	Este servicio se fundamenta de la siguiente forma:  
	Tenemos nuestro archivo plano, y utilizamos KMS para cifrar el archivo. La principal diferencia con el servicio anterior es que en esta ocasión nosotros vamos a crear las llaves, aunque AWS la va a almacenar.
	
	**Características**
	
	* Llaves: Se crea la llave en IAM, y se debe especificar quiénes puedes administrarlas y usarlas.
	* Integración: Se encuentra integrado con CloudTrail para auditar el uso de las llaves.
	* Rotación: La rotación de las llaves es responsabilidad del usuario, no de AWS.
	
	

* **edisoncastro14** (2) [471773](https://platzi.com/comentario/471773/) 

	<https://github.com/toniblyx/prowler> AWS security checker

	* **Carlos Andrés Zambrano Barrera** [471773] (1)

		😃

	* **Brayan Mamani** [471773] (1)

		A probarlo !!

* **johncastillotellez7** (1) [936729](https://platzi.com/comentario/936729/) 

	es otra muy buena opcion, con un grado de mayor control.en el KMS y CMK

## 0190. Encriptación en S3 - Llaves del Usuario [15050](https://platzi.com/clases/1424-storage-aws/15050-encriptacion-en-s3-llaves-del-usuario/)

### Descripción:


### Comentarios:

* **johncastillotellez7** (2) [936757](https://platzi.com/comentario/936757/) 

	nivel de autonomia del end user es mayor. bien flexible.  
	teniendo en cuenta el contexto actual de seguridad delos datos y cybersecurity. las compañias que usan Aws cual utilizan mas frecuente? sse s3? All you need to do is enable server-side encryption in your object metadata when you upload your data to Amazon S3. As soon as your data reaches S3, it is encrypted and stored. puede ser!!

* **juancajamarca** (2) [935957](https://platzi.com/comentario/935957/) 

	En esta forma de encriptación, el usuario tiene mayor participación en cuanto a la administración de las llaves.
	
	* El usuario proporciona las llaves de cifrado y AWS administra el cifrado de los objetos. AWS no almacena las llaves, lo hace el usuario y es totalmente su responsabilidad.
	* Para las solicitudes se deben realizar con HTTPS o serán negadas por AWS.
	* La rotación de las llaves es responsabilidad del usuario, no de AWS.
	
	

* **carlosbazanhuaman** (1) [839532](https://platzi.com/comentario/839532/) 

	para la generacion de llaves por parte del usuario podrian recomendar alguna herramienta?

* **vcentt-lopez** (1) [479908](https://platzi.com/comentario/479908/) 

	Nosotros acabamos de implementar este tipo de cifrado en S3, movimos 1 TB de datos, todo funcionando bien.

	* **Carlos Andrés Zambrano Barrera** [479908] (1)

		Excelente noticia, he visto casos de éxito así y el ahorro vs tenerlo on premise es muy alto.

## 0200. Encriptación en S3 [15052](https://platzi.com/clases/1424-storage-aws/15052-encriptacion-en-s3/)

### Descripción:


### Comentarios:

* **Mario Barbosa** (7) [684462](https://platzi.com/comentario/684462/) 

	En la nueva versión de la consola AWS, ya no se crean por IAM si no por, Key Management Service (KMS)

	* **juancajamarca** [684462] (1)

		Buen aporte.

* **johncastillotellez7** (3) [936778](https://platzi.com/comentario/936778/) 

	solamente se puede crear el encryption key atraves de AWS KMS. Amazon actualizo><https://console.aws.amazon.com/kms/home?region=us-east-1#/kms/keys> todo quedo integrado en 1 solo site.

* **Nestor Alfonso Portela Rincón** (2) [470900](https://platzi.com/comentario/470900/) 

	Si uno utiliza esas medidas de seguridad, esas opciones tienes algún costo adicional o recargo al servicio de S3 que se este usando?

	* **Diego Alexander Forero Higuera (Platzi)** [470900] (4)

		No, el servicio por defecto de encriptación viene incluido en el costo de S3, sin embargo características como AWS Key Management Service si puede generar costos adicionales.
		
		There are no new charges for using default encryption for S3 buckets. Requests to configure the default encryption feature incur standard Amazon S3 request charges. For information about pricing, see Amazon S3 Pricing. For SSE-KMS encryption key storage, AWS Key Management Service charges apply and are listed at AWS KMS Pricing.

	* **Carlos Andrés Zambrano Barrera** [470900] (1)

		De acuerdo con GOLLUM23, hay un costo más que todo de las llaves, el costo de la seguridad no lo ves dentro de S3 en el Billing.

## 0210. Introducción a Políticas en S3 [15051](https://platzi.com/clases/1424-storage-aws/15051-introduccion-a-politicas-en-s3/)

### Descripción:


### Comentarios:

* **estebanvasquezvalencia** (7) [483898](https://platzi.com/comentario/483898/) 

	Hola a todos, comparto el enlace al generador de politicas:  
	<https://awspolicygen.s3.amazonaws.com/policygen.html>

	* **Dario Jose Vilchez Perozo** [483898] (1)

		Buenas noches , como funciona el generador de politica

* **jschenfeld** (3) [832369](https://platzi.com/comentario/832369/) 

	Politicas de seguridad, se aplican sobre usuarios/roles y se describen en formato json.
	
	Ejemplo:  
	`{ "Version":"2012-10-17", "Statement":[ { "Sid":"PublicRead", "Effect":"Allow", "Principal": "*", "Action":["s3:GetObject"], "Resource":["arn:aws:s3:::examplebucket/*"] } ] }`  
	[fuente](https://docs.aws.amazon.com/AmazonS3/latest/dev/example-bucket-policies.html)  
	Atributos:
	
	* Version: es opcional, por defecto toma la última version y determina el formato valido.
	* Statement: es Obligatorio y es una lista de objetos json.  
	cada Objeto en statement tendra el siguiente formato:
	* Sid: opcional, pero algunos servicios pueden solicitar este id
	* Effect : es obligatorio, valores: Allow o Deny
	* Principal: es obligatorio, es el arn del usuario o rol.
	
	

* **johncastillotellez7** (1) [940742](https://platzi.com/comentario/940742/) 

	oportuno para el manejo de S3 y sus policies.

## 0220. Ejemplos de Políticas en S3 [15054](https://platzi.com/clases/1424-storage-aws/15054-ejemplos-de-politicas-en-s3/)

### Descripción:


### Comentarios:

* **johncastillotellez7** (2) [940770](https://platzi.com/comentario/940770/) 

	hola, estos ejemplos son utilizes como guia.<https://static.platzi.com/media/public/uploads/storage-en-aws_4d1da0f8-775e-4e1a-b99a-31345b11284b.pdf>  
	gracias

* **Edmund Halley** (1) [567847](https://platzi.com/comentario/567847/) 

	Buenas, estoy tratando de hacer, aplicarla a un usuario, para que ese usuario solo pueda ver y acceder a una unica carpeta de un bucket especifico pero no he podeido conectarme. He utilziado Netdrive y S3 Browser y con ninguno me conecta. Cuando le pongo en resource * me accede. Me podrian ayudar?

	* **Carlos Andrés Zambrano Barrera** [567847] (3)

		Lo primero, prueba en AWS entrando con el usuario a la consola que tenga los permisos que especificaste, cuando te loguees con ese usuario que solo veas el folder que necesitas…

* **edisoncastro14** (1) [471822](https://platzi.com/comentario/471822/) 

	¿Podrían poner las políticas en los archivos para probar por favor?

	* **Diego Alexander Forero Higuera (Platzi)** [471822] (5)

		Los ejemplos de las políticas los encuentras en los slides del curso te dejo el enlace <https://static.platzi.com/media/public/uploads/storage-en-aws_4d1da0f8-775e-4e1a-b99a-31345b11284b.pdf>

	* **Carlos Andrés Zambrano Barrera** [471822] (3)

		Depende de lo que requieras permitir en el bucket… Recuerda que como capa de seguridad adicional puedes usar condicionales, por buena práctica siempre todos los buckets tienen su Policy y nunca dejamos uno púublico.

	* **Carlos Andrés Zambrano Barrera** [471822] (1)

		Si tienes más dudas postealas y miramos la política que tienes y según lo que quieras hacer la podemos ajustar.

	* **vcentt-lopez** [471822] (1)

		@gollum23 y como podemos ver los slides de los demás cursos?, como puedo llegar a ellos?, nada mas no encuentro desde donde es.

	* **Diego Alexander Forero Higuera (Platzi)** [471822] (3)

		@vcentt-lopez los slides se publican en la pestaña de archivos de las clases por lo general publican los slides en las primeras clases.

* **Saúl Báez Terrez** (1) [62454](https://platzi.com/comentario/640413/) 
La condición de Autenticación Multifactor [“aws:MultiFactorAuthAge”: true] que es lo que hace, es decir, si se cumple va a denegar y si n...

	* **Diego Alexander Forero Higuera (Platzi)** [62454] (1)

		Hola si te fijas bien, tiene un Null al principio, esto quiere decir que si el MultiFactorAuthAge no existe entonces va a denegar el acceso, debe tener el Multifacto Authentication activo en la cuenta para poder acceder al bucket.

* **Edmund Halley** (1) [57662](https://platzi.com/comentario/567847/) 
Buenas, estoy tratando de hacer, aplicarla a un usuario, para que ese usuario solo pueda ver y acceder a una unica carpeta de un bucket e...

	* **Carlos Andrés Zambrano Barrera** [57662] (3)

		Lo primero, prueba en AWS entrando con el usuario a la consola que tenga los permisos que especificaste, cuando te loguees con ese usuario que solo veas el folder que necesitas…

* **edisoncastro14** (1) [49764](https://platzi.com/comentario/471822/) 
¿Podrían poner las políticas en los archivos para probar por favor?

	* **Diego Alexander Forero Higuera (Platzi)** [49764] (5)

		Los ejemplos de las políticas los encuentras en los slides del curso te dejo el enlace <https://static.platzi.com/media/public/uploads/storage-en-aws_4d1da0f8-775e-4e1a-b99a-31345b11284b.pdf>

## 0230. ACL en S3 [15053](https://platzi.com/clases/1424-storage-aws/15053-acl-en-s3/)

### Descripción:


### Links:

* [InformaciÃ³n general de las Access Control Lists (ACL, Listas de control de acceso) - Amazon Simple Storage Service](https://docs.aws.amazon.com/es_es/AmazonS3/latest/dev/acl-overview.html)

### Comentarios:

* **johncastillotellez7** (2) [942578](https://platzi.com/comentario/942578/) 

	ACLAccess control list  
	are one of the resource-based access policy options (see Overview of Managing Access) that you can use to manage access to your buckets and objects. You can use ACLs to grant basic read/write permissions to other AWS accounts. There are limits to managing permissions using ACLs. For example, you can grant permissions only to other AWS accounts; you cannot grant permissions to users in your account.

	* **johncastillotellez7** [942578] (2)

		<https://docs.aws.amazon.com/AmazonS3/latest/dev/managing-acls.html>

	* **johncastillotellez7** [942578] (1)

		ACLs are suitable for specific scenarios.

* **johncastillotellez7** (1) [942665](https://platzi.com/comentario/942665/) 

	siempre as compliance never leave a bucket as public access

* **juancajamarca** (1) [936439](https://platzi.com/comentario/936439/) 

	ACL en S3.
	
	ACL (Lista de control de acceso)  
	Son permisos a nivel de cuentas; es decir, permitir o denegar el acceso de otras cuentas a nuestro Bucket.  
	Cuando se vaya a referenciar una cuenta en la configuración, hay que tener presente que no todas las regiones admiten que se coloquen como valor un correo electrónico; en cambio, deberíamos poner el id del usuario.
	
	En lo posible y bajo ninguna circunstancia se recomienda dejar un Bucket público. Para eso ya están estas reglas y medidas de seguridad.
	
	Las ACL son un mecanismo de seguridad que se complementan de forma adecuada con las Buckets Policies. Porque con las ACL puedo definir qué cuentas pueden acceder a mi Buckets, y con las Buckets Policies puedo establecer qué puedo hacer cada usuario.

* **carlosbazanhuaman** (1) [839572](https://platzi.com/comentario/839572/) 

	las politicas debe ser una clase principal en el tema de seguridad ya que hay varias formas de crear condiciones de acceso para los usuarios.

* **Yembert Quintero Cortez** (1) [813100](https://platzi.com/comentario/813100/) 

	Bueno pero si se coloca una pagina web estatica si se necesitaria que este publico o no ? solo se requiere de solo lectura de manera any ?

* **Juan Carlos Pinzón** (1) [561776](https://platzi.com/comentario/561776/) 

	Las políticas me parecen más practicas y un poco más seguras para la administración del bucket

* **johncastillotellez7** (1) [79577](https://platzi.com/comentario/942674/) 
en ese envio de S3 log delivery group puede enviarse cuentas de email?

# Storage Gateway [2851]

## 0240. Características de storage gateway [15056](https://platzi.com/clases/1424-storage-aws/15056-caracteristicas-de-storage-gateway/)

### Descripción:


### Comentarios:

* **johncastillotellez7** (2) [942679](https://platzi.com/comentario/942679/) 

	Resource Type ARN Format  
	Gateway ARN
	
	arn:aws:storagegateway:region:account-id:gateway/gateway-id
	
	File Share ARN   
	arn:aws:storagegateway:region:account-id:share/share-id
	
	Volume ARN   
	arn:aws:storagegateway:region:account-id:gateway/gateway-id/volume/volume-id
	
	Tape ARN   
	arn:aws:storagegateway:region:account-id:tape/tapebarcode
	
	Target ARN ( iSCSI target)   
	arn:aws:storagegateway:region:account-id:gateway/gateway-id/target/iSCSItarget
	
	VTL Device ARN   
	arn:aws:storagegateway:region:account-id:gateway/gateway-id/device/vtldevice

	* **johncastillotellez7** [942679] (1)

		interesante por conocer.

	* **johncastillotellez7** [942679] (1)

		interesante ya que se puede usar en una migracion de datos, bakcups etc controlada al cloud. para que sea incremental

* **juancajamarca** (2) [936497](https://platzi.com/comentario/936497/) 

	Storage Gateway es un servicio que conecta el mundo onpremise con la nube. Básicamente es un servicio híbrido que nos va a permitir aprovechar todas las ventajas, funcionalidades y características del almacenamiento en nube para arquitecturas e infraestructuras que tengamos implementadas onpremise. Este servicio va a actuar como intermediario entre nuestro datacenter físico con la nube, y nos va a proveer esa conexión para movernos hacia la nube y también nos va a permitir aprovechar todas las ventajas que hemos visto de la nube como seguridad, durabilidad, disponibilidad, replicación y demás.
	
	**Características**
	
	* Definición: Almacenamiento híbrido con integración onpremise optimizado para transferencia de datos.
	* Casos de uso: Backups, archiving, disaster recovery, y cloud data processing.
	* Protocolos: Utiliza protocolos como NFS, SMB y iSCSI.
	* Integración: S3, EBS, Glacier.
	* Uso: Descargar e instalar una VM, configure y puede usarla.
	* Seguridad: Brinda todas las ventajas de seguridad y durabilidad que provee la nube de AWS.
	
	

* **carlosbazanhuaman** (1) [839620](https://platzi.com/comentario/839620/) 

	storage gateway parece mas un servicio de S3 que un servicio independiente.

* **Danilo Pazos** (1) [74931](https://platzi.com/comentario/861445/) 
Que significa on-premisse?

	* **Roger Vilà** [74931] (1)

		Significa que la misma empresa gestiona, instala y configura el software en local y no hay terceros involucrados

## 0250. File Gateway [15055](https://platzi.com/clases/1424-storage-aws/15055-file-gateway/)

### Descripción:


### Comentarios:

* **Enzo Aliatis** (7) [637411](https://platzi.com/comentario/637411/) 

	Esta muy bueno el curso pero me gustaría que lo hiciera con un ejemplo practico, estilo problemas de matemáticas. Ejemplo.  
	El jefe del departamento pide bla bla bla y tu como jefe de IT tienes que hacerlo… y asi me parece una buena forma de practicar eventos de la vida real y no solo imaginarmelos

	* **RaulAlanGarciaMtz** [637411] (1)

		yep yo tambien pienso que los cursos que he visto aqui de aws se basan poco en la practica eso me hace desilucionarme para continuar contratando el servicio para teoria mejor leo la documentación

* **Jose Maldonado** (1) [978241](https://platzi.com/comentario/978241/) 

	esta ip que solicituda, es la publica de tu on-premise o interna, debe ser estatica o puede ser por dhcp ? saludos

* **johncastillotellez7** (1) [948980](https://platzi.com/comentario/948980/) 

	bastante util para hacer la migracion controlada y facil de administrar.

* **juancajamarca** (1) [936545](https://platzi.com/comentario/936545/) 

	 **File Gateway**
	
	Es un tipo de Storage Gateway, el cual permite que aplicaciones on-premise accedan a Storage a través de SMB o NFS.  
	Con File Gateway podemos empezar a pasar nuestros objetos de on-premise a S3, nuestros logs para procesamiento, y básicamente va a ser a nivel de objetos.  
	Este tipo de Storage provee una opción que se llama _The Cache_ , el cual hace un caché local de los objetos que se están transfiriendo para que puedan ser accesibles de manera frecuente mientras se va haciendo la réplica a la nube.

* **Roger Vilà** (0) [919940](https://platzi.com/comentario/919940/) 

	Storage Gateway
	
	Permite que aplicaciones on-permise accedan a storage a través de SMB o NFS  
	La data es cacheada en el File Gateway y convertida en objetos en S3

## 0260. Virtual Tape Library [15057](https://platzi.com/clases/1424-storage-aws/15057-virtual-tape-library/)

### Descripción:


### Comentarios:

* **Yadfary Irene Montoya Herrera** (3) [690005](https://platzi.com/comentario/690005/) 

	Hay que tener en cuenta que cada vez hay más datos que salvar y cada vez menos tiempo para hacer el backup, es por esto que las Virtual Tape Library hacen de un conjunto de discos físicos, cartuchos de cinta virtuales.

* **johncastillotellez7** (1) [948992](https://platzi.com/comentario/948992/) 

	hace que el proceso de backup sea sofisticad y barato o sin depender de cintas fisicas sino de su almacenamiento en glacier.  
	es verdad todavia hay empresas y tambien bancos q siguen usando tapes. ahi es donde se debe innovar

* **juancajamarca** (1) [944559](https://platzi.com/comentario/944559/) 

	* Reemplaza el backup en cintas aprovechando el cloud.
	* El backup existente es generado directamente desde on-premise en virtual tape.
	
	

* **vcentt-lopez** (1) [481423](https://platzi.com/comentario/481423/) 

	¿Y si hay empresas todavía usando cintas? wow!

	* **cesarvillegas** [481423] (1)

		Si, aunque no lo creas hay muchas empresas y se niegan a cambiar ese esquema por motivos que no logro entender 😃

	* **Ernesto Jose Gabriel Lopez Bravo** [481423] (1)

		Incluso hay arquitecturas donde almacenas contenido multimedia en librerias de cintas y colocas al frente una serie de servidores con discos de SSD que sirven como caché del contenido. Pero sí aún se usan las cintas. Actualmente LTO ya están en la generación 8 y está en el roadmap LTO-9 y LTO-10.

	* **hanspereira** [481423] (1)

		El almacenamiento en cintas no solo “aún se usa” sino que según varios estudios, ha aumentado su uso.
		
		Hay que decir que muchas cintas son capaces de almacenar muchísimos teras de información secuencial a un costo muy bajo.
		
		Obviamente Glacier es más eficiente, pero bueno, está bien saber que esa posibilidad existe.

## 0270. Volume Gateway [15058](https://platzi.com/clases/1424-storage-aws/15058-volume-gateway/)

### Descripción:


### Comentarios:

* **Ernesto Jose Gabriel Lopez Bravo** (4) [612091](https://platzi.com/comentario/612091/) 

	Volume gateway > cached volumes, Si aparece Amazon EC2  
	Volume gateway > stored volumes, No aparece Amazon EC2.

* **Jose Maldonado** (1) [978270](https://platzi.com/comentario/978270/) 

	Esta soluciones son pensadas para sustituir tu servidor de filesystem o DFS por ejemplo on- premise, directamente con S3. (la solucion que aplique, claro ). saludos

* **johncastillotellez7** (1) [949002](https://platzi.com/comentario/949002/) 

	tambien es util dependiendo de la necesidad

* **juancajamarca** (1) [944588](https://platzi.com/comentario/944588/) 

	* Crear caché de archivos locales. Mejora la latencia de archivos locales.
	* Crear snapshots locales en AWS. Estos backups son cargados asíncronamente a AWS.
	
	

* **Roger Vilà** (1) [922255](https://platzi.com/comentario/922255/) 

	Faltan ejemplos practicos para desarrollar bien los conocimientos en este curso.

* **Ernesto Lázaro Guerrero** (1) [730319](https://platzi.com/comentario/730319/) 

	Recomienden software para dibujar arquitecturas

	* **David Rangel** [730319] (2)

		[draw.io](http://draw.io)

	* **Javier Gabriel Aguilar Melgar** [730319] (3)

		<https://cloudcraft.co/>

* **Anthony Sebastian Mayol** (1) [634065](https://platzi.com/comentario/634065/) 

	Reto Storage GAteway para volver, repasar y hacer.

# Sistema de archivos elástico (EFS) [2852]

## 0280. Elastic File System [15060](https://platzi.com/clases/1424-storage-aws/15060-elastic-file-system/)

### Descripción:


### Comentarios:

* **juancajamarca** (2) [963479](https://platzi.com/comentario/963479/) 

	 **Elastic File System (EFS)**
	
	Sistemas de archivos elástico.
	
	* **Pricing:** El valor es por GB consumido, no por GB aprovisionado.
	* **Uso:** Aumento y reducción automática de su capacidad.
	* **Funcionalidad** : Concede un acceso compartido paralelo masivo a miles de instancias Amazon EC2.
	* **IOPS:** Permite altos niveles de IOPS.
	* **Red:** Permite mejor rendimiento de red.
	* **Funcionalidad:** Permite cifrado en reposo.
	* **Compatibilidad:** Sólo es compatible con sistemas operativos Linux. Usando Direct Connect, ESF puede ser utilizado desde On-Premise.
	* **Montaje:** Provee un paso a paso de montaje del sistema de archivos en Linux.
	
	

* **johncastillotellez7** (1) [949009](https://platzi.com/comentario/949009/) 

	Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources.
	
	unidad de almacenamiento que nos brinda un acceso -endpoint para conectar una gran cantidad de instancias. de manera que es flexible y facilmente escalable-elastica

* **Roger Vilà** (1) [922744](https://platzi.com/comentario/922744/) 

	Elastic File System
	
	El valor es por GB consumido. No por aprovisionado  
	Aumento y reducción automatica de su capacidad.  
	Concede un acceso compartido paralelo masivo a miles de instancias Amazon EC2.  
	Solo compatible en Linux.  
	Permite altos niveles de IOPS  
	Permite mejor rendimiento de red  
	Permite cifrado en reposo. (Llaves KMS)

* **Rodolfo Nicacio Ugalde Ochoa** (1) [794526](https://platzi.com/comentario/794526/) 

	EFS ya cuenta con la opción de **Habilitar la administración del ciclo de vida**

* **Anthony Sebastian Mayol** (1) [634092](https://platzi.com/comentario/634092/) 

	Puntos a tener en cuenta en EFS.

## 0290. Casos de uso de EFS. [15059](https://platzi.com/clases/1424-storage-aws/15059-casos-de-uso-de-efs/)

### Descripción:


### Comentarios:

* **Ernesto Jose Gabriel Lopez Bravo** (3) [612619](https://platzi.com/comentario/612619/) 

	A nivel conceptual podria ser un servidor de base de datos que genera unos reportes los cuales se deben almacenar en una directorio, y despues otro servidor con un software de Business Inteligence jala esos reportes de esa ruta para hacer algún análisis.

* **juancajamarca** (1) [963496](https://platzi.com/comentario/963496/) 

	En mi caso, utilizaría AWS EFS para conectarlo a los servidores de un grupo de autoscaling. De esta manera, cuando se ejecute la integración continua, no sólo se efectuarán los cambios sobre la instancia principal, sino en todas.

* **johncastillotellez7** (1) [949027](https://platzi.com/comentario/949027/) 

	pa resulmir>util el caso de util —importante palabra autoscaling.  
	Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth.

* **Anthony Sebastian Mayol** (1) [634120](https://platzi.com/comentario/634120/) 

	Reto EFS a repasar y resolver.

* **Anthony Sebastian Mayol** (1) [634116](https://platzi.com/comentario/634116/) 

	Características a tener en cuenta a nivel de EFS.

# Sistema de archivo por bloques (EBS) [2853]

## 0300. Características de Elastic Block Storage [15062](https://platzi.com/clases/1424-storage-aws/15062-caracteristicas-de-elastic-block-storage/)

### Descripción:


### Comentarios:

* **juancajamarca** (3) [983143](https://platzi.com/comentario/983143/) 

	Elastic Block Storage es un servicio de almacenamiento basado en bloques; y al ser basado en bloques, nos va a brindar dos características que no tenemos en otros sistemas de archivos: podemos instalar sistemas operativos y podemos instalar aplicaciones. Este tipo de almacenamiento lo podemos ver como un disco duro virtual en la nube.
	
	**Características**
	
	Podemos adherirlo a una instancia. Sin embargo, a diferencia de EFS, en este servicio se paga por almacenamiento aprovisionado, y esto es porque como se utiliza como almacenamiento de sistemas operativos, no puede ser dinámico. Si se desea cambiar el tamaño del almacenamiento del disco, en Linux se realiza el cambio a través de la terminal; y en caso de utilizar Windows Server, se debe primero realizar el cambio en la consola de AWS y luego en la administración de discos dentro del servidor. Aunque se recomienda siempre aprovisionar desde el comienzo el tamaño de almacenamiento necesario para evitar tener que redimencionarlo, debido a que puede ser peligroso para la información.
	
	* **Replicación:** Cada volumen se replica dentro de una AZ (zona de disponibilidad) para proteger ante un error.
	* **Diseño:** Está diseñado para ayudar a diferentes cargas de trabajo.
	* **Montaje:** Un EBS puede estar asociado sólo a una instancia EC2, y una instancia EC2 puede estar asociada a varios EBS.
	* **Boot:** No se pueden encriptar y no permiten todos los tipos de EBS disponibles.
	* **Volumen adicional:** Pueden encriptarse y usar todos los tipos de EBS disponibles.
	* **Montaje:** Se debe hacer por la consola de AWS y a nivel de sistema operativo.
	* **Tipos:** Hay diferentes tipos de EBS.
	* **Protección:** Se puede proteger el borrado accidental al crear la instancia.
	* **Límites:** Pueden ser de hasta 16TB. El almacenamiento origen varía según el tipo de EBS.
	
	

* **Roger Vilà** (2) [924719](https://platzi.com/comentario/924719/) 

	Elastic Block Storage
	
	Disco duro virtual en la nube  
	Se puede agregar a EC2  
	Compatible con Windows y Linux  
	Cada volumen se replica dentro de una AZ para proteger ante un error (Replicación)  
	Esta diseñado para ayudar a diferentes cargas de trabajo (Diseño)  
	Un EBS puede estar asociado sólo a una instancia EC2 (Montaje)  
	Se debe hacer por la consola de AWS y a nivel de S.O (Montaje)  
	No se pueden encriptar y no permiten todos los tipos de EBS disponibles (Boot)  
	Puede encriptarse y usar todo los tipos de EBS disponibles (Volumen adicional)  
	Hay diferentes tipos de EBS (GP2 - IO1 - ST1 - SC1)  
	Se puede proteger el borrado accidental al crear la instancia. (Protección)  
	Pueden ser de hasta 16TB (Límites)

* **johncastillotellez7** (1) [951841](https://platzi.com/comentario/951841/) 

	es el hard drive en el cloud. haciendo uso de OS and APps

## 0310. Tipos de EBS - GP2 - IO1 [15061](https://platzi.com/clases/1424-storage-aws/15061-tipos-de-ebs-gp2-io1/)

### Descripción:


### Comentarios:

* **Nestor Alfonso Portela Rincón** (3) [473594](https://platzi.com/comentario/473594/) 

	Si yo estoy usando un tipo de EBS y quiero pasarlo o transformarlo a otro, lo puedo hacer ?

	* **Carlos Andrés Zambrano Barrera** [473594] (4)

		Si claro, lo puedes hacer, te vas a volumes dentro de ec2, seleccionas el volúmen y le das modify volume. Puedes cambiarlo de tipo y de tamano.

	* **estebanvasquezvalencia** [473594] (1)

		Creo que otra opción sería crear una copia del disco actual, crear un nuevo volumen y restaurar en el nuevo volumen la copia y probar.

* **juancajamarca** (2) [983161](https://platzi.com/comentario/983161/) 

	 **Tipos de EBS: GP2 & IO1**
	
	**SSD GP2 (General purpose)**
	
	* Balance entre performance y precio. 3 IOPS por cada DB hasta 10.000 IOPS. Son de uso general.
	* Hasta 3.000 IOPS para periodos cortos debajo de 1GB. Puede ser Boot de una instancia. Entre 1GB y 16TB.
	
	
	
	**SSD IO1**
	
	* Diseñados para I/O intensiva. Se usan para más de 10.000 IOPS. Hasta 20.000 IOPS por volumen.
	* Para BD no relacionales o uso intensivo I/O. Puede ser Boot de una instancia. Entre 4GB y 16TB.
	
	

* **Nestor Alfonso Portela Rincón** (2) [49922](https://platzi.com/comentario/473594/) 
Si yo estoy usando un tipo de EBS y quiero pasarlo o transformarlo a otro, lo puedo hacer ?

	* **Carlos Andrés Zambrano Barrera** [49922] (4)

		Si claro, lo puedes hacer, te vas a volumes dentro de ec2, seleccionas el volúmen y le das modify volume. Puedes cambiarlo de tipo y de tamano.

* **johncastillotellez7** (1) [952442](https://platzi.com/comentario/952442/) 

	ambos son muy buenos depndiendo de la necesidad del business

* **Juan Carlos Pinzón** (1) [563511](https://platzi.com/comentario/563511/) 

	Es decir que un cambio de tipo storage EBS podría marcar una gran diferencia en el rendimiento de nuestra instancia de EC2 y que podría ser un primer paso antes que cambiar o aumentar la CPU y la ram, es la conclusión que saco

## 0320. Tipos de EBS - ST1 - SC1 [15063](https://platzi.com/clases/1424-storage-aws/15063-tipos-de-ebs-st1-sc1/)

### Descripción:


### Comentarios:

* **juancajamarca** (2) [983194](https://platzi.com/comentario/983194/) 

	 **Tipos de EBS: ST1 & SC1**
	
	**HDD ST1**
	
	* BigData, Data Warehouse, Log Process o Streaming. No pueden ser Boot de una EC2.
	* Entre 500GB y 16TB.
	
	
	
	**HDD SC1**
	
	* Volumen de menor costo para cargas de acceso con poca frecuencia. No pueden ser Boot de una EC2.
	* Escenarios donde el costo es importante. Entre 500GB y 16TB.
	
	
	
	**Magnetic (standard)**
	
	* Es el que tiene la instancia por defecto al ser encendida. No es recomendable porque no garantiza el almacenamiento de la información luego de que se reinicie o se apague.
	
	

* **johncastillotellez7** (1) [952463](https://platzi.com/comentario/952463/) 

	Estos son usados para cargas de info con baja frecuencia.  
	de los 4 tipos de EBS:  
	es importante escogerlo dependiendo de la necesidad del negocio o proyecto. mayor iops o menor iops . alta frecuencia de read/write baja frecuencia de r/w

* **Anthony Sebastian Mayol** (1) [634180](https://platzi.com/comentario/634180/) 

	Temas a tener en cuenta en EBS.

## 0330. Snapshots y AMI [15064](https://platzi.com/clases/1424-storage-aws/15064-snapshots-y-ami/)

### Descripción:


### Comentarios:

* **juancajamarca** (2) [983224](https://platzi.com/comentario/983224/) 

	 **Snapshots y AMI**
	
	* Los snapshots son incrementales. Se pueden programar con el lifecycle manager.
	* Compatibles con cualquier sistema operativo.
	
	
	
	**Diferencias entre Snapshots y AMIs**  
	La principal diferencia entre el snapshot y la AMI es, por decirlo de una manera informal, una foto en el tiempo del servidor; en cambio la AMI la podríamos utilizar para crear una plantilla de un Sistema Operativo para después replicarla. Por ejemplo, podemos crear una AMI que por defecto ya tenga una aplicación o un stack instalado y cuando copiemos esa AMI a otra región y la despleguemos, ya sabemos que siempre va a estar esa aplicación o ese stack en las instancias que despleguemos basadas en esa AMI. En el caso del snapshot, nos desplegaría el servidor que ya hemos estado utilizando con nuestra información, y en el caso de la AMI, podríamos venderla en el AWS MarketPlace compliendo algunas normas definidas por AWS.

* **johncastillotellez7** (1) [952547](https://platzi.com/comentario/952547/) 

	los snapshots son muy utiles para proteger la data, en inclusive se usa para EL DR desaster Recovery de la DB. las imagenes son ya utiles par a sacar copias exactas de todo el sistema operativo con applicacioens y demas instalaciones y con base en esa crear nuevos instancias/servidores

* **johncastillotellez7** (1) [80108](https://platzi.com/comentario/952549/) 
tiene amazon en los snapshots algun limite de peso/volumen tope para dejarlos crear?

## 0340. Volumen EBS para Windows [15066](https://platzi.com/clases/1424-storage-aws/15066-volumen-ebs-para-windows/)

### Descripción:


### Comentarios:

* **juancajamarca** (2) [983251](https://platzi.com/comentario/983251/) 

	¡Tener muy presente que el tamaño de los volúmenes no se puede decrementar!

* **johncastillotellez7** (1) [952572](https://platzi.com/comentario/952572/) 

	bien util esta practica.

* **Cristian David Franco Garcia** (1) [725854](https://platzi.com/comentario/725854/) 

	Para conectarme a la instacia EC2-Windows use Remote Desktop Connection disponible para Mac y Windows.

	* **Rodolfo Nicacio Ugalde Ochoa** [725854] (1)

		Thx 😃

* **Ernesto Jose Gabriel Lopez Bravo** (1) [613287](https://platzi.com/comentario/613287/) 

	Tambien puedes hacer estos movimientos dentro de Computer Manangement > disk management para los más tradicionales

* **Rogelio Andrés Cisternas Vera** (1) [479225](https://platzi.com/comentario/479225/) 

	Agregando un disco para su uso en Windows

## 0350. Volumen EBS para Linux [15065](https://platzi.com/clases/1424-storage-aws/15065-volumen-ebs-para-linux/)

### Descripción:


### Comentarios:

* **johncastillotellez7** (1) [952606](https://platzi.com/comentario/952606/) 

	comandos usandos en el example.  
	lsblk
	
	sudo mkfs -t ext4 /dev/xdb (ruta deseada)
	
	sudo mkdir platzi  
	sudo mount /dev/xvdb platzi  
	cd platzi
	
	interesante ejemplo

* **Rogelio Andrés Cisternas Vera** (1) [479271](https://platzi.com/comentario/479271/) 

	Montaje del EBS en Linux

# Conclusiones [2854]

## 0360. AWS Storage S3 vs EBS vs EFS, Cuándo usar cada uno [15317](https://platzi.com/clases/1424-storage-aws/15317-aws-storage-s3-vs-ebs-vs-efs-cuando-usar-cada-uno/)

### Descripción:


### Comentarios:

* **Roger Vilà** (2) [927376](https://platzi.com/comentario/927376/) 
	
	![AWSStorage.PNG](https://static.platzi.com/media/user_upload/AWSStorage-bb2cdca5-5a34-4238-b93e-575260c165c9.jpg) ![AWSStorage2.PNG](https://static.platzi.com/media/user_upload/AWSStorage2-a885f46b-50dc-4347-a3fb-3bd6c4cd5f7b.jpg)

* **AlexanderJ** (1) [1067148](https://platzi.com/comentario/1067148/) 

	Excelente, 😃

* **juancajamarca** (1) [983261](https://platzi.com/comentario/983261/) 

	Excelente resumen.

* **johncastillotellez7** (1) [952643](https://platzi.com/comentario/952643/) 

	bien completas esas tablas de summary.

* **carlosbazanhuaman** (1) [858081](https://platzi.com/comentario/858081/) 

	en S3 no se puede instalar aplicaciones pero si se puede usar alguna app estatica como una site.

* **nicolas-garcia-puerta** (1) [799510](https://platzi.com/comentario/799510/) 

	Muy buen resumen

## 0370. Conclusiones [15068](https://platzi.com/clases/1424-storage-aws/15068-conclusiones0987/)

### Descripción:


### Comentarios:

* **Yadfary Irene Montoya Herrera** (2) [691946](https://platzi.com/comentario/691946/) 

	Muy interesante la explicación de cada uno de los servicios, casos de usos en los que aplican y arquitecturas en las cuales podemos implementarlas.

* **Diego Fernando Romero Romero** (2) [688059](https://platzi.com/comentario/688059/) 

	Excelente contenido y buena explicación.

* **Richard Ariel Torrico Velasquez** (2) [685046](https://platzi.com/comentario/685046/) 

	Muy buen curso, excelente docente.

* **CyberNomads** (2) [637417](https://platzi.com/comentario/637417/) 

	Extraordinario! Muy bien explicado todo, el contenido es fantástico y el profesor sin duda es de los mejores de la plataforma! 😃

* **lrojasrr** (2) [626429](https://platzi.com/comentario/626429/) 

	Excelente contenido, el trabajo bajo casos de uso facilita mucho la opción de implementar una solución AWS en nuestros proyectos.

* **CristianCabreraA** (2) [601092](https://platzi.com/comentario/601092/) 

	Buen Profesor muy claro el material

* **vcentt-lopez** (2) [486044](https://platzi.com/comentario/486044/) 

	Yo implemente S3 para un proyecto de objetos, anteriormente lo tenía en EBS, ahora que terminé este curso veo que estuvo muy bien la migración implementando encriptación, ahora aplicaré lo aprendido que es el ciclo de vida, gracias.

* **Nestor Alfonso Portela Rincón** (2) [473641](https://platzi.com/comentario/473641/) 

	Gracias al profe Carlos y a Platzi por este curso, nos da una idea exacta del servicio Storage que ofrece AWS y los casos de uso para seleccionar la mejor opción para nuestra empresa o proyectos personales.

	* **Carlos Andrés Zambrano Barrera** [473641] (1)

		Gracias Nestux!

* **Dante Castillo Z.** (1) [989307](https://platzi.com/comentario/989307/) 

	Buen contenido. En especial las dos demos finales.

* **juancajamarca** (1) [983268](https://platzi.com/comentario/983268/) 

	Excelente curso!

* **julianqp5025** (1) [981853](https://platzi.com/comentario/981853/) 

	Buen contenido, dominio del tema y ejemplos claros.

* **johncastillotellez7** (1) [952663](https://platzi.com/comentario/952663/) 

	bien clara las explicaciones mil gracias Carlos.

	* **johncastillotellez7** [952663] (1)

		terminado excelente

* **Fernando_Rivera** (1) [928860](https://platzi.com/comentario/928860/) 
Excelente curso, muy claro todo.

* **Roger Vilà** (1) [927379](https://platzi.com/comentario/927379/) 

	Buen curso y profesor, pero falta contenido practico.

* **nicolas-garcia-puerta** (1) [799511](https://platzi.com/comentario/799511/) 

	Muchas gracias crack

* **hugomm** (1) [754822](https://platzi.com/comentario/754822/) 

	Por mas Carlos Teacher en platzi!!

* **ceruizdev** (1) [708518](https://platzi.com/comentario/708518/) 

	Muy bueno, buen profe!

* **juanjocop** (1) [504516](https://platzi.com/comentario/504516/) 

	Gracias Carlos por hacernos el aprendizaje tan fácil, estas en mi top 5 de profes de Platzi! 😄

* **Rogelio Andrés Cisternas Vera** (1) [479332](https://platzi.com/comentario/479332/) 

	wow buenos ejemplos y bien explicado para poder iniciar.  
	Se agradece el curso

	* **Carlos Andrés Zambrano Barrera** [479332] (1)

		GRacias!

* **DiegoRP** (1) [478582](https://platzi.com/comentario/478582/) 

	Me pareció muy bueno el curso!  
	Muy concreto el contenido y de calidad.

	* **Carlos Andrés Zambrano Barrera** [478582] (1)

		Gracias!!

* **Wilfredo Lujan Ramirez** (1) [81478](https://platzi.com/comentario/982080/) 
¿Podrías darme algunos alcances de los costos para volúmenes de información de TB a PB?

* **Wilfredo Lujan Ramirez** (1) [81477](https://platzi.com/comentario/982079/) 
Un ejemplo imaginamos que respaldos de TB enviarlos por red /internet a la nube. ¿Que consideraciones deberíamos tener presentes al momen...

* **Wilfredo Lujan Ramirez** (1) [81476](https://platzi.com/comentario/982077/) 
¿Que tal el compatibilidad de AWS con respecto a las soluciones de Respaldo como EMC Networker, IBM Spectrun y otros?.

* **Wilfredo Lujan Ramirez** (1) [81475](https://platzi.com/comentario/982071/) 
Saludos, ¿cual seria la estrategia que recomendarías para migrar los respaldos de información de una empresa que graba en cinta física? y...

* **Wilkins Ortiz** (0) [574609](https://platzi.com/comentario/574609/) 

	Gracias por los aportes y los conocimientos compartidos, gracias infinitas.

* **hanuman80** (0) [534146](https://platzi.com/comentario/534146/) 

	Excelente curso. Gracias Carlos, espero verte en mas cursos de Platzi. Saludos cordiales.

