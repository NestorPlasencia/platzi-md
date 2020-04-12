# Introducción

## 0010. Introducción y bienvenida

### Descripción:


¡Bienvenidas y Bienvenidos al Curso de Mongo DB!

Con nuestro profesor, Albert Ramírez, vamos a aprender sobre bases de datos NoSQL como MongoDB, cómo realizar operaciones CRUD desde la consola con MongoDB Compass o con tu lenguaje de programación favorito y cómo pasar nuestros _clusters_ al entorno de producción.

El proyecto del curso es PlatziMongo, una API que responde las clases que hemos subido a la plataforma y esta hecha en Python con Flask. No te preocupes si no manejas muy bien estos temas, gran parte del código ya esta hecho para que nosotros solo nos preocupemos por crear los métodos necesarios para integrar el proyecto con MongoDB.

### Comentarios:

* **DemetrioDelCarmen** (4)
Que bueno que cambiaron de profesor, al otro como que se le iba el rollo

* **Juan David Castro (Platzi)** (3)

	
	  * [Top Tutorials To Learn Mongo DB - Quick Code](https://medium.com/quick-code/top-tutorials-to-learn-mongo-db-f1e52bee7445)
	  * [MongoDB VS PostgreSQL: Which is perfect your you?](https://bytescout.com/blog/mongodb-vs-postgresql.html)
	
	

* **dbzdavidbaez** (2)

	
	Excelente, listo para seguir aprendiendo.

* **Abraham Gonzalez** (2)

	
	Es importante recalcar que para MongoDB existen diversos comentarios entre foros donde afirman que MongoDB pierde data …

	* **Juan José Vega Quintero** (1)

		
		what?

* **Brayan Camilo Hernández Quiroz** (2)

	
	Genial, No saben cuanto espere este curso!!!

	* **eimispacheco** (1)

		
		Yo tambien

	* **Brayan Mamani** (1)

		
		Igualmente mi persona.

* **Ruben Raul Hernandez Mac-kinley** (1)

	
	Veamos que tal 😄

* **asismelgarejo** (1)

	
	Empezemos

* **ehnbytes** (1)

	
	Comenzando el curso!!

* **desteban90** (1)

	
	Muy util

* **MartinMB** (1)

	
	Veamos que ta es este curso

* **HeartHunter** (1)

	
	Vamos Una mas

* **jonathan2138** (1)

	
	Genial, a estudiar

* **Juan Guillermo Perez Cardozo** (1)

	
	bueno a aprender bd documentales

* **Cristhian Arce** (1)

	
	Muy emocionado!

* **carlosivanespinoza** (1)

	
	Mongo es lo máximo.

* **Brayan Mamani** (1)

	
	¡Suena muy interesante!

* **hydroxseguridad** (1)

	
	Interesante! veremos como va

* **gosunkugi** (1)

	
	ah! hay un error en la descripción de este video!  
	"… para que nosotros solo nos preocupesmos por crear … "

* **Wandy Rafael Santana Evangelista** (1)

	
	Vamos a darle.

* **Dragonatak** (1)

	
	Veamos qué tal!! El de Yohan era muy bueno!!!

* **Guillermo Pastor Amaya Marquez** (1)

	
	¡Gracias lo esperaba!

* **Jrodriguezr** (0)
Bienvenidos! Al cursó.

## 0020. Bases de datos NoSQL

### Descripción:


Las bases de datos NoSQL tienen 4 grandes familias: _Key Value Stores_ , basadas en grafos, columnares y basadas en documentos.

**Key Value Stores** : Guardan la información en formato de llaves y valores. Las usamos para guardar cache, información de sesión de los usuarios o cosas **muy sencillas**. Son **muy rápidas** de consultar pero no podemos usarlas en casos más complejos donde necesitamos estructuras más especiales. El mejor ejemplo de estas bases de datos es [Redis](https://redis.io).

**Graph Databases** : Bases de datos basadas en Grafos. Nos permiten establecer conexiones entre nuestras entidades para realizar consultas de una forma más eficiente que en bases de datos relacionales (así como Twitter o Medium donde cada publicación tiene diferentes relaciones entre sus usuarios, likes, etc). Por ejemplo: Neo4j o JanusGraph.

**Wide-column Stores** : Bases de datos columnares. Tienen una llave de fila y otra de columnas para hacer consultas muy rápidas y guardar grandes cantidades de información pero modelar los datos se puede volver un poco complicado. Las usamos en Big Data, IoT, sistemas de recomendaciones, entre otras. Por ejemplo: Cassandra o HBase.

**Document Databases** : Bases de datos basadas en documentos. Nos permiten guardar documentos dentro de colecciones, tiene muy buena _performance_ y flexibilidad que nos permite modelar casos de la vida real de forma sencilla y efectiva. Por ejemplo: MongoDB o CouchBase.

### Comentarios:

* **glasnost** (5)

	
	Este profesor es excelente. Es mejor que el de mi facultad.

* **Claudio Jesus Vázquez Villanueva** (4)
hay curso para Graph database?

	* **anibalrojas (Platzi)** (2)

		
		Oye no. Tienes algún interés específico en Bases de Datos de Orientadas a Grafos?

* **njfock** (3)

	
	¿DynamoDB a que familia pertenece?

	* **aragonesteban (Platzi)** (3)

		
		DynamoDB pertenece a las bases de datos NoSQL, puedes ver más información en este [artículo](https://medium.com/tensult/core-concepts-of-amazon-dynamodb-a265a3fc70a).

	* **Juan David Castro (Platzi)** (1)

		
		DynamoDB es el servicio para bases de datos NoSQL de AWS.
		
		👉 <https://platzi.com/blog/aws-rds-aurora-y-dynamo/>

	* **Brayan Mamani** (1)

		
		A las grandiosas bases de datos **NoSQL**.

* **Juan David Castro (Platzi)** (3)

	
	  * [Bases de datos ¿qué son? ¿qué tipos existen? Lo que necesitas saber como profesional](https://platzi.com/blog/bases-de-datos-que-son-que-tipos-existen/)
	  * [Implementación de bases de datos no relacionales - NoSQL](https://platzi.com/blog/que-es-el-teorema-cap-y-como-elegir-la-base-de-datos-para-tu-proyecto/)
	  * [Qué es el teorema CAP y cómo elegir la base de datos para tu proyecto](https://platzi.com/blog/que-es-el-teorema-cap-y-como-elegir-la-base-de-datos-para-tu-proyecto/)
	
	

	* **Alvise Leal** (3)

		
		Creo que se repiten los enlaces del punto 2 y 3

	* **johan2732** (1)

		
		Si, de acuerdo… se repiten los dos enlaces

	* **jsrodriguezj** (1)

		
		Siguen duplicados los enlaces.

	* **Brayan Mamani** (1)

		
		Si son similares, deberían ser distintas. 😃

* **Eduardo P. Rivero** (2)

	
	También existe [FaunaDB](https://fauna.com/) que se complementa bien en aplicaciones serverless.

* **Ernesto Jose Gabriel Lopez Bravo** (2)

	
	También DynamoDB es Key-Value y document

* **dbzdavidbaez** (2)

	
	Clave - valor: Son ideales para almacenar y extraer datos con una clave única. Manejan los diccionarios de manera excepcional. Ejemplos: DynamoDB, Cassandra.
	
	Basadas en documentos: Son una implementación de clave valor que varía en la forma semiestructurada en que se trata la información. Ideal para almacenar datos JSON y XML. Ejemplos: MongoDB, Firestore.
	
	Basadas en grafos: Basadas en teoría de grafos, sirven para entidades que se encuentran interconectadas por múltiples relaciones. Ideales para almacenar relaciones complejas. Ejemplos: neo4j, TITAN.
	
	En memoria: Pueden ser de estructura variada, pero su ventaja radica en la velocidad, ya que al vivir en memoria la extracción de datos es casi inmediata. Ejemplos: Memcached, Redis.
	
	Optimizadas para búsquedas: Pueden ser de diversas estructuras, su ventaja radica en que se pueden hacer queries y búsquedas complejas de manera sencilla. Ejemplos: BigQuery, Elasticsearch.

	* **Juan José Vega Quintero** (1)

		
		Nice

* **Cristhian Arce** (2)

	
	La verdad no conocía tal variedad de BD

* **Brayan Mamani** (2)

	
	Las bases de datos **NoSQL** son mis favoritas.

* **Gustavo Quino Crispín** (2)

	
	Buen aporte el de la descripción, Gracias!

	* **jsrodriguezj** (1)

		
		Totalmente de acuerdo.

	* **Brayan Mamani** (1)

		
		Una lectura para repasar de forma rápida.

* **Victor Macas** (2)

	
	Tiene buena pinta el curso, aunque no presentó su trayectoria el profesor, se nota que será amena las clases

* **Claudio Jesus Vázquez Villanueva** (2)

	
	hay curso para Graph database?

	* **anibalrojas (Platzi)** (2)

		
		Oye no. Tienes algún interés específico en Bases de Datos de Orientadas a Grafos?

	* **Claudio Jesus Vázquez Villanueva** (1)

		
		Que tal creo que van a lanzar uno el 21 de mayo esta en el calendario y lo pregunto por que no las conocía la verdad  
		.

	* **Juan David Castro (Platzi)** (1)

		
		GraphQL es otra cosa completamente diferente… Más relacionado con las APIs que con un tipo de base de datos…

	* **juand_silva** (2)

		
		Es **Graph database** no GraphQL

	* **Brayan Mamani** (1)

		
		¡Ahora veo cual es la verdadera!

	* **Hinder Adrian Alvarez Perlaza** (1)

		
		Pues no exactamente, pero creo que te podría interesar este: <https://platzi.com/clases/graphql/>

* **Andrés Felipe Largo Rodríguez** (1)

	
	Super interesante, gracias.

* **Iraida Mercedes Barreto Díaz** (1)

	
	No tenpia ni idea de la existencia de bds Wide-column Stores. Cool.

* **Ruben Raul Hernandez Mac-kinley** (1)

	
	Excelente explicación

* **Cristian Mauricio Gutierrez Rivera** (1)

	
	Interente la clase

* **Frank Carmona** (1)

	
	buena clase

* **ehnbytes** (1)

	
	Muy buena clase!

* **HeartHunter** (1)

	
	Excelente

* **MartinMB** (1)

	
	Muy bueno

* **Pablo Azuaje** (1)

	
	Hola como puedo hacer un query aleatorio, es para traerme un listado de preguntas de una colección x y que estas se presenten una por una de forma aleatoria.

* **Juan Guillermo Perez Cardozo** (1)

	
	gracias albert no conocia sobre las otras como cassandra

* **carlosivanespinoza** (1)

	
	Hasta ahora nunca había imaginado la variedad de bases existentes, que importante es saber escoger una acorde a tu necesidad.

* **Rafael Pardo Rodriguez** (1)

	
	Una base de datos “popular” basada en grafos se llama [Dgraph](https://dgraph.io/) 😃

* **Briones D. Jose** (1)

	
	Muchas gracias por el curso esta super genial!!

* **jsrodriguezj** (1)

	
	Excelente emocionado por seguir con el curso.

* **Jhon Alexander Perez Valencia** (1)

	
	Excelente!!

* **Wandy Rafael Santana Evangelista** (1)

	
	Excelente introducción.

* **Oscar Estuardo de la Mora** (1)
IndexedDB de HTML5 en el navegador podría ser considerada una Document Database?

* **Pablo Azuaje** (1)
Hola como puedo hacer un query aleatorio, que me pueda traer un listado de preguntas de una colección y presentar pregunta por pregunta p...

	* **René Sanchez** (1)

		
		Hola!,
		
		Tendrias que hacer un random de numero aleatorio y definir si es que quieres un limite y un inicio.
		
		skip(1) => empieza desde el numero 1 o se salta hasta la posicion o documento numero 1  
		limit(10) hasta el 10 o llega solo hasta los 10 documentos
		
		Espero haberte ayudado con alguna idea de lo que tienes en mente para poder hacerlo 💚
		
		Si tienes mas consultas puedes hablarme por insta: lrenenk

* **Andrés Muñoz** (1)
¿Hay algún método para evaluar si debo usar postgresql o mongodb ?

	* **Juan David Castro (Platzi)** (1)

		
		Lo más importante es que domines muy bien los [fundamentos de _cualquier_ base de datos](https://platzi.com/clases/bd/). Luego de esto puede que este artículo te ayude a elegir: <https://platzi.com/blog/mongo-vs-sql/>. 😉

## 0030. Definición de MongoDB y su ecosistema (herramientas de uso)

### Descripción:


MongoDB es una base de datos gratis y de código abierto No Relacional basada en documentos que nos permite guardar una gran cantidad de documentos de forma distribuida. Mongo también es el nombre de la compañía que desarrolla el código de esta base de datos.

Una de sus principales características es que nos permite guardar nuestras estructuras o documentos en formato JSON (no exactamente JSON, pero si algo muy parecido, lo veremos más adelante) para tener una gran flexibilidad a la hora de modelar situaciones de la vida real.

Por ser una base de datos distribuida podemos hablar no de uno sino de varios servidores, lo que conocemos como el **_Cluster_ de MongoDB**. Gracias a esto obtenemos una gran escalabilidad de forma horizontal (escalabilidad en cantidad de servidores).

MongoDB es “ _Schema Less_ ” lo que permite que nuestros documentos tengan estructuras diferentes sin afectar su funcionamiento, algo que no podemos hacer con las tablas de las bases de datos relacionales. Su lenguaje para realizar _queries_ , índices y agregaciones es muy expresivo.

### Comentarios:

* **Juan David Castro (Platzi)** (20)

	
	  * [Tipos de Escalabilidad: Vertical vs. Horizontal](https://www.oscarblancarteblog.com/2017/03/07/escalabilidad-horizontal-y-vertical/)
	
	
	
	![](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-vertical.png)  
	![](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-horizontal.png)

	* **jsrodriguezj** (1)

		
		Que buen aporte 😃

	* **Brayan Mamani** (1)

		
		Un aporte muy esencial para esta clase.

	* **Hinder Adrian Alvarez Perlaza** (1)

		
		Buen aporte, gracias!

* **pabloverduzcos** (10)

	
	¿A que se refiere cuando habla de logica explicita?

	* **Wilson_Revan** (8)

		
		Lo curioso del asunto en 3 meses nadie del equipo de platzi atendió esta pregunta.

	* **pabloverduzcos** (2)

		
		Cierto 😂

	* **jsrodriguezj** (2)

		
		y seguimos con la duda. 😕

	* **Javier Rain** (2)

		
		y …?

	* **WilmarFlorez** (1)

		
		…

	* **Antony Samuel Brenes Cruz** (9)

		
		Lógica explicita se refiere a que su lógica es muy clara y de fácil entendimiento 😃

	* **edwintrumpet** (1)

		
		Creo que se refiere en esa parte a que Stitch es como las cloud functions que se manejan en AWS o Firebase en las que sin necesidad de un servidor se puede agregar una lógica para acceder a la base de datos y devolver alguna información a otro servicio que la solicite.

	* **edwintrumpet** (1)

		
		También cuando usó la palabra “explícita” quiso decir que es una lógica a la que tenemos acceso porque nosotros la creamos, no es una lógica que esté oculta y trabajando detrás de otras cosas.

	* **Brayan Mamani** (1)

		
		SUpongo que se realiza de forma clara.

* **Mon Avellaneda** (8)

	
	Me encanta la tranquilidad y claridad con la que explicas, Albert
	
	Mil gracias

* **pabloverduzcos** (7)

	
	 **MongoDB**
	
	  * Base de datos no relacional
	
	  * Basada en documentos
	
	  * Se pueden guardar estructuras tipo _JSON_
	
	  * Base de datos distribuida (facilmente escalable)
	
	  * Codigo abierto
	
	  * Gratis
	
	
	

* **cristianwalteros** (4)

	
	Se ve muy interesante el curso, mis primeros acercamientos con bases de datos no relacionales

* **dvillalobos** (4)

	
	Hola, MongoDB no es gratis. Es de uso libre.
	
	Hice el examen y encontré muchos errores de redacción y ortográficos.

	* **elvis.sanchez** (4)

		
		Tu comentario tiene errores de redacción.

	* **Brayan Mamani** (1)

		
		Pero se puede corregir.

* **mafevito** (4)
¿Cuando habla de cluster se refiere a un servidor?

	* **Juan David Castro (Platzi)** (3)

		
		Al principio de este tutorial se explican los clusters en MongoDB: <http://gpd.sip.ucm.es/rafa/docencia/nosql/Replicas.html>.

* **Ernesto Jose Gabriel Lopez Bravo** (3)

	
	El tamaño máximo de un Documento BSON es de 16MB para evitar que un solo documento pueda consumir RAM en exceso, para documentos de mayor tamaño, mongoDB ofrece la opcion de usar GridFS API

* **Brayan Mamani** (3)

	
	¡ **MongoDB** es una base de datos basada en **Documentos**!

* **MartinMB** (2)

	
	Vamos bien de momento

* **mariobrandoavilacalderon** (1)
Guarda documentos "tipo JSON" (representación binaria BD distribuida => Permite estabilidad horizontal

* **Decoderunner** (1)

	
	Me parece interesante que se pueda hacer tanto con un desarrollo de código abierto.

* **Ruben Raul Hernandez Mac-kinley** (1)

	
	Base de datos no relacional basa en documentos de forma distribuida

* **Óscar Moreno González oscar** (1)

	
	Eso de BSON no lo conocía

* **Juan Guillermo Perez Cardozo** (1)

	
	gracias por explicar el ecosistema de mongoDB

* **dbzdavidbaez** (1)

	
	Muy interesante. Listo para seguir aprendiendo

* **xmedinavei** (1)

	
	Cuál es la diferencia entre MongoDB y Firestone de Google? (Además de que la de Google es parcialmente gratis) Cuál es más usada y útil?

	* **william andres rodriguez borja** (2)

		
		Firestore una base de datos es un backend como servicio. incluye su base de datos que almacena también documentos pero es muy diferente trabajar en ambos en firestore no es muy fácil hacer consultas de agregación , en realidad creo que no es posible en la actualidad.  
		Eso es funciones como group by having max sum, avg etc. para mi es un store de documentos más un sistema gestion de base de datos.

* **Cristhian Arce** (1)

	
	Ya quiero empezar! , se ve muy prometedor

* **carlosivanespinoza** (1)

	
	MongoDB es lo mejor hasta ahora… las consultas son mu rápidas.

* **Nestor Alfonso Portela Rincón** (1)

	
	Interesante curso, realmente no he tenido un acercamiento al mundo de las bases de datos no relaciones y veré que tal me va.

* **neontigermx** (1)

	
	Haber que tal!

* **Luis Paredes** (1)

	
	Grandes expectativas con MongoDB.

* **Walter Ugalde A** (1)

	
	Cuando un dato es generico, a n cantidad de registros, estos deben repetirse en cada documento o se hace una referencia a otro documento, pero si hacemos una referencia no estariamos hacindola relacional …?

* **pabloverduzcos** (1)
¿A que se refiere cuando habla de logica explicita?

	* **Wilson_Revan** (8)

		
		Lo curioso del asunto en 3 meses nadie del equipo de platzi atendió esta pregunta.

## 0040. MongoDB Atlas

### Descripción:


Tenemos varios proveedores que nos permiten utilizar o alquilar MongoDB como servicio y en este caso vamos a usar [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) por ser desarrollado por las mismas personas que desarrollan MongoDB.

MongoDB Atlas tiene las siguientes características:

  * Aprovisionamiento automático de _clusters_ con MongoDB
  * Alta disponibilidad
  * Altamente escalable
  * Seguro
  * Disponible en AWS, GCP y Microsoft Azure
  * Fácil monitoreo y optimización



### Links:

* [Database Hosting - Fully Managed Cloud Service | ScaleGrid | ScaleGrid](https://scalegrid.io/)

* [MongoDB Hosting, Cheap MongoDB with Free Trial, MongoDB-as-a-Service, Managed MongoDB on Kubernetes Cloud](https://www.mongoclusters.com)

* [MongoDB Hosting: Database-as-a-Service by mLab](https://mlab.com)

* [Fully Managed MongoDB, hosted on AWS, Azure, and GCP | MongoDB](https://www.mongodb.com/cloud/atlas)

### Comentarios:

* **Jaime Andrés Martínez Rodríguez** (5)

	
	Para los estudiantes nuevos! las opciones ahora se encuentran en la barra lateral izquierda en Atlas para la creación de usuarios y el acceso al network

* **jsrodriguezj** (4)

	
	Listo, siguiendo las recomendaciones del profe es bien sencillo, aunque la interfaz es un poco diferente el día que estoy haciendo esto.

* **csrarias** (3)

	
	ya configure el cluster para poner en practica

* **Ptmejia2312** (2)

	
	M0 no deja seleccionar.

	* **Jonattan_Infante** (1)

		
		Si lo permite, Creo que hay que decir que es para aprender Mongo porque aparece una ventana emergente tan pronto creas tu cuenta preguntando eso

	* **luis-fernando-yupanqui-taco** (1)

		
		En las regiones , tienes que selecionar la region que tenga el FREE-TRIAL

	* **edwintrumpet** (1)

		
		Si tiene otro cluster MO no le deja seleccionar un segundo, solo se puede tener uno de ese tipo.  
		O tal vez eligió alguna característica que no tiene free tier

	* **Brayan Mamani** (1)

		
		FREE-TRIAL para utilizarlo de forma gratuita.

* **gosunkugi** (2)

	
	pues… el M0 ya no se puede seleccionar 😦

	* **Juan Camilo Angel Fandiño** (2)

		
		Hola, si me dejó siguiendo los pasos del profe.

	* **Brayan Mamani** (1)

		
		La informacion esta en la clase.

* **Wandy Rafael Santana Evangelista** (2)

	
	Me encanta en la manera en la que desarrollas los temas, es muy fácil y sencillo.

* **saul-mdo** (1)

	
	Tengo poca experiencia con mLab, Atlas se ve muy bien!

* **ehnbytes** (1)

	
	Wow!!

* **MartinMB** (1)

	
	Perfecto

* **Zolider** (1)

	
	Actualmente en vez de INSTANCE SIZE (7:30), me sale CLUSTER TIER  
	![panel.png](https://static.platzi.com/media/user_upload/panel-407564f5-afb7-4e04-87c2-3898baac5284.jpg)

* **jonathan2138** (1)

	
	wow super interesante, no pense que fuera tan facil siempre tenia en mente algo realmente complicado de trabajar este tipo de BD

* **Brando Rodríguez** (1)

	
	 **MongoDB Atlas**  
	Tenemos varios proveedores que nos permiten utilizar o alquilar MongoDB como servicio y en este caso vamos a usar MongoDB Atlas por ser desarrollado por las mismas personas que desarrollan MongoDB.
	
	MongoDB Atlas tiene las siguientes características:
	
	  * Aprovisionamiento automático de clusters con MongoDB  
	Alta disponibilidad  
	Altamente escalable  
	Seguro  
	Disponible en AWS, GCP y Microsoft Azure  
	Fácil monitoreo y optimización
	
	

* **Andres Pinzon** (1)

	
	La creación del cluster y la configuración fue bastante rápida.

* **Juan Guillermo Perez Cardozo** (1)

	
	gracias , sin problemas por el momento

* **Kevin Jeremy Salazar Jimenez** (1)

	
	no me sale la seccion de segurity 😦

	* **Marcelo Gajardo** (2)

		
		En la parte de la izquierda sale  
		Security -> Database access  
		Y luego le das en “+Add new user” que sale en verde 😉

* **Gino Andrey Grimaldos Puerto** (1)

	
	Tengo un inconveniente con el driver para c#, tengo Visual Studio 2019  
	y la pagina me dice que la conecion se realiza asi  
	var mongoUrl = new MongoUrl(“mongodb+srv://User:<Password>@pruebachiAAA-verhd.mongodb.net”);  
	_client = new MongoClient(mongoUrl);  
	var db = _client.GetDatabase(“myfirstdb”);  
	var collection = db.GetCollection<Student>(“student”);  
	Student student = new Student(“Gino”, “Grimaldos”);  
	collection.InsertOne(student);
	
	al ejecutarla tengo
	
	MongoDB.Driver.MongoAuthenticationException: ‘Unable to authenticate using sasl protocol mechanism SCRAM-SHA-1.’
	
	Como puedo arreglar ello y que la conexion se mantenga
	
	De antemano gracias profe.

* **TUDz** (1)

	
	Listo con mi primer cluster en Atlas!

* **dbzdavidbaez** (1)

	
	Instalado el cluster en ATLAS

* **carlosivanespinoza** (1)

	
	Ya pude hacer mi integración de Mongo con C#. Me gusta MongoDB

* **Gustavo Quino Crispín** (1)

	
	Listo para comenzar!

* **gamaciega** (1)

	
	Listo el cluster para continuar con las clases!

* **Sebax1901** (1)

	
	No me deja crear el Cluster, me da un error cuando quiero seleccionar el M0. Aparece que existe un límite de 1 Mo cluster por proyecto.

	* **albertramirez** (4)

		
		MongoDB Atlas solamente te permite crear un cluster M0 gratuito por proyecto, así que asegúrate de que no tengas alguno ya creado o si lo prefieres crea un nuevo proyecto en la cuenta que tienes actualmente así:  
		[Ver instrucciones](https://drive.google.com/file/d/1UPyY_gpvBduZAfx44wvr_H0u8EC2Fy52/view?usp=sharing)

* **wvigoya** (1)

	
	interesante, nueva forma de ver, almacenar datos

* **David Santiago Pinchao Ortiz** (1)
A que hace referencia el sandbox

	* **David Santiago Pinchao Ortiz** (1)

		
		Es como nuestro entorno de desarrollo en Mongo Atlas !

* **Kevin Jeremy Salazar Jimenez** (1)
no me sale la seccion de segurity 😦 , que puedo hacer

	* **fernandogualan** (1)
![](https://ibb.co/YLsNk31)

* **Sebax1901** (1)
No me deja crear el Cluster, me da un error cuando quiero seleccionar el M0. Aparece que existe un límite de 1 Mo cluster por proyecto.

	* **albertramirez** (4)

		
		MongoDB Atlas solamente te permite crear un cluster M0 gratuito por proyecto, así que asegúrate de que no tengas alguno ya creado o si lo prefieres crea un nuevo proyecto en la cuenta que tienes actualmente así:  
		[Ver instrucciones](https://drive.google.com/file/d/1UPyY_gpvBduZAfx44wvr_H0u8EC2Fy52/view?usp=sharing)

## 0050. Instalación MongoDB en Windows

### Descripción:


### Links:

* [MongoDB Download Center | MongoDB](https://www.mongodb.com/download-center#community)

### Comentarios:

* **Wandy Rafael Santana Evangelista** (10)

	
	 **Algunos comandos de MongoDB en su Shell (consola):**  
	**show dbs:** Muestra todas las base de datos que hay.  
	**use [nameDB]:** Para crear un nuevo documento DB.  
	**db.[nameDB].insertOne({name: “Name”, age: 27, city: “Las Vegas”}):** Insertamos datos tipo JSON (BSON) a el documento DB.  
	**db.[nameDB].findOne():** Te muestra la colección de datos que existen en ese documento DB.

* **Miguel Angel Prieto Mendez** (8)

	
	Si se cierra la terminal “mongo.exe” o muestra el error “Error: couldn’t connect to server 127.0.0.1:27017, connection attempt failed: SocketException”, hacer lo siguiente
	
	• Crear carpetas “data\db” en la raíz C:\
	
	  * C:\data\db
	
	
	
	• Iniciar Servicio (mongod.exe)
	
	  * Ejecutar C:\Program Files\MongoDB\Server\4.2\bin\mongod.exe
	
	
	
	• Ejecutar Terminal (mongo.exe)
	
	  * C:\Program Files\MongoDB\Server\4.2\bin\mongo.exe
	
	
	
	Nota: Si NO funciona verificar bloqueo del firewall

* **Davison Pimentel** (6)

	
	db.usuarios.insertOne({name: “John”, ange: 31, city: “New York”})

	* **Luis Paredes** (1)

		
		db.usuarios.insertOne({name: “John”, age: 31, city: “New York”})

	* **Brayan Mamani** (3)

		
		db.usuarios.insertOne({name: “John”, age: 31, city: “New York”})

* **Óscar Moreno González oscar** (5)

	
	![](url)![mongo.jpg](https://static.platzi.com/media/user_upload/mongo-c4b56a8b-736b-40b2-8c8f-caeaff71a0e1.jpg)

* **Juan David Castro (Platzi)** (4)

	
	  * [Cómo instalar MongoDB en Windows, Mac y Linux - Platzi Blog](https://platzi.com/blog/como-instalar-mongodb-en-window-linux-y-mac/)
	
	

* **Eduardo P. Rivero** (3)

	
	Para los que usan docker o escribí un tutorial de como instalar mongo con esta herramienta así pueden tener un solo proceso de instalación en Windows/Mac/Linux.
	
	<https://platzi.com/tutoriales/1533-mongodb/4930-instalar-mongo-db-usando-docker/>

* **Brando Rodríguez** (3)

	
	**Instalación MongoDB en Windows**
	
	<https://www.mongodb.com/download-center/community>
	``` 
	    C:\Program Files\MongoDB\Server\4.2\bin
	    
	```

* **Brayan Mamani** (3)

	
	¡Que sencillo es instalar **MongoDB**!

* **msalin** (3)

	
	Actualmente (version 4.0.10), el wizard se queda cargando por horas asi que la mejor solución es bajar el server en version .zip y crear las carpetas “C:/Archivos de Programa/MongoDB/4.0/“ y copiar dentro el bin del .zip y luego instalar el compass aparte con wizard.  
	Luego seguir los siguientes pasos:  
	-Abrir cmd y ejecutar “md \data\db”  
	-shift click derecho en la carpeta bin, abrir cmd  
	-mongod.exe  
	-shift click derecho en la carpeta bin, abrir cmd  
	-mongo.exe
	
	Espero sea de ayuda 😃

* **fabiogomezs** (3)

	
	hola, al tratar de abrir mongo.exe se abre la consola pero se cierra a los pocos segundos. Cual podría ser el problema?

	* **Diego Alexander Forero Higuera (Platzi)** (6)

		
		Tienes que abrir la consola, navegar hasta donde esta el ejecutable de mongo y ejecutarlo desde la consola, no haciendo doble click en el ejecutable.

	* **Favio Náquira** (1)

		
		Está iniciado el servicio de mongod? El mongo daemon a veces se desactiva según la configuración de Windows (generalmente cuando no eres administrador).  
		Primero verifica que esté iniciado el servicio de MongoDB. En caso no lo tengas como servicio, ejecuta mongod para iniciar el servidor.  
		Como consejo, agrega la carpeta bin de MongoDB a las variables de entorno, para que puedas invocar rápidamente los comandos en cualquier ubicación.

	* **sergio-medina93** (1)

		
		Primero haz click en mongod.exe para y luego a mongo.exe. Así me funciono.

	* **luisfbejaranob27** (1)

		
		Si no lo instalaste Mongo como servicio tienes que crear en el disco C crear una carpeta llamada data y dentro una carpeta llamada db y ejecutas Mongo

* **csrarias** (3)

	
	en el proceso de instalación no me instaló el compass como lo puedo activar?

	* **albertramirez** (5)

		
		Hola, lo puedes descargar de <https://www.mongodb.com/download-center/compass?jmp=hero>  
		Asegúrate de elegir tu sistema operativo y de que sea la versión community.

	* **Brayan Mamani** (1)

		
		¡Gracias por la aclaración!

* **Luis Nilson Palma Campos** (2)

	
	Por si a alguien le sucede lo mismo que a mi y no encontraba donde descargarlo ,en la imagen se puede ver donde descargarlo
	
	![Captura de pantalla \(45\)_LI.jpg](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2845%29_LI-7a7e682f-597e-4c4e-8c02-f4290d3d0a7a.jpg)

* **dbzdavidbaez** (2)

	
	Instalado y funcionando
	``` 
	    show dbs			--revisar que bases hay
	    use basededatos	--crear base de datos y moverse a la base
	    db				--en que base estamos
	    db.usuarios.insertOne({name: "David", age: 42, city: "Bogota"})
	    show collections	--base de datos
	    db.usuarios.findOne() -- Buscar
	    
	```

* **Baltazar Ortega** (2)

	
	Sigan estos pasos para que no tengan problemas con Compass en Windows: [enlace](https://vegibit.com/install-mongodb-with-compass-on-windows/)

* **daniel-campuzano** (2)

	
	Existe algún conflicto en la diferencia de versiones entre MongoDB local y el Cluster en Altas?

	* **Jesus Daniel Arrieche Veliz** (2)

		
		Saludos, hay cierta incompatibilidad pero igual se puede utilizar. Actualmente tengo la version 3.6 en mi equipo y la del Cluster en Atlas es la 4.0. aun asi me funciona

	* **Brayan Mamani** (1)

		
		Existe una compatibilidad pero al local le falta más características.

* **emanuel-alejandro-mamani** (2)
me tardo 30 min la instalacion en la version 4.2, muy interesante

* **fabiogomezs** (2)
hola, al tratar de abrir mongo.exe se abre la consola pero se cierra a los pocos segundos. Cual podría ser el problema?

	* **Diego Alexander Forero Higuera (Platzi)** (6)

		
		Tienes que abrir la consola, navegar hasta donde esta el ejecutable de mongo y ejecutarlo desde la consola, no haciendo doble click en el ejecutable.

* **csrarias** (2)
en el proceso de instalación no me instaló el compass como lo puedo activar?

	* **albertramirez** (5)

		
		Hola, lo puedes descargar de <https://www.mongodb.com/download-center/compass?jmp=hero>  
		Asegúrate de elegir tu sistema operativo y de que sea la versión community.

* **joeldm011** (1)

	
	Muy buena esta clase!  
	Esperando ya empezar con lo bueno que es el CRUD.
	``` 
	    > db.usuarios.findOne()
	    {
	            "_id" : ObjectId("5e76e1b8ea51c4edbe1b8ee2"),
	            "name" : "John",
	            "age" : 31,
	            "city" : "New York"
	    }
	    >
	    
	```

* **Ruben Raul Hernandez Mac-kinley** (1)

	
	Me gusto la explicación de esta clase

* **Edgar Damian Morales Aguirre** (1)

	
	No es un problema muy grande, pero deberían incluir varios sistemas operativos en sus cursos o especificar para cual va dirigido. Por ejemplo “Curso Básico de MongoDB en Windows”.

* **Jose Arturo Enriquez Hurtado** (1)

	
	Que facil :0

* **Juan Guillermo Perez Cardozo** (1)

	
	gracias, hay voy aprendiendo poco a poco

* **carlosivanespinoza** (1)

	
	Es fácil la instalación. No me demoré nada

* **Luis Rangel Castro** (1)

	
	Hay que instalar por separado MongoDB Compass para evitar que se quede colgado el instalador…

* **Luis Rangel Castro** (1)

	
	[Download MongoDB](https://www.mongodb.com/download-center/community)

* **alejandromarcano** (1)

	
	Se quedaba pegado durante horas así que lo instale pero desmarque la opción de instalar compass e instale compass aparte

* **Wilson Marino Pablo Mendez** (1)

	
	Mis primeras consultas en MongoDB 😎

* **Luis Cordero** (1)

	
	Windows… 😦

* **Andres Pinzon** (1)
Entiendo que para el curso la instalación debe ser sencilla y poder enfocarse en aprender mongo. Pero aparte de esto lo ideal no sería in...

	* **Eduardo P. Rivero** (1)

		
		Es cierto, pero eso requeriría el tutorial para instalar docker primero que también varía de acuerdo al sistema operativo. En todo caso por si te sirve escribí un tutorial de como instalarlo usando docker
		
		<https://platzi.com/tutoriales/1533-mongodb/4930-instalar-mongo-db-usando-docker/>

* **daniel-campuzano** (1)
Existe algún conflicto en la diferencia de versiones entre MongoDB local y el Cluster en Altas?

	* **Jesus Daniel Arrieche Veliz** (2)

		
		Saludos, hay cierta incompatibilidad pero igual se puede utilizar. Actualmente tengo la version 3.6 en mi equipo y la del Cluster en Atlas es la 4.0. aun asi me funciona

* **Agustina García** (0)

	
	Quise instalar mongo y me quedo cargando como hora y media y no avanzó mas, alguien sabe como solucionarlo?

## 0060. Instalación MongoDB MacLinux

### Descripción:


¡Hola! en esta lectura te enseñaré a instalar MongoDB en MAC o en Linux. Sigue los pasos y si tienes dudas compartelas en la sección de discusiones.

1- Ingresa a <https://www.mongodb.com/download-center/community> y descarga el community server con la versión de tu sistema operativo.

![MongoDB](https://media.giphy.com/media/SFIHFbv8bORW4LtcH6/giphy.gif)

2- Da doble clic sobre el archivo .tgz si tu sistema es Mac para descomprimir el archivo descargado.

3- Copia la carpeta descargada en tu directorio Home o donde quieras dejar todos los ejecutables de Mongo.

4- Actualizar tu PATH con la ruta a la carpeta donde dejaste los archivos descomprimidos:  
a- Abre un terminal y corre sudo nano /etc/paths ve a la última línea del archivo y agrega toda la ruta a la carpeta /bin que movimos en el paso   
anterior.  
b- Presiona ctrl+x para salir e ingresa Y para guardar los cambios que acabas de hacer.  
c- Si ejecutas echo $PATH deberías tener la ruta que apunta a la carpeta /bin con los ejecutables de MongoDB.

5- Para ejecutar MongoDB de forma local debes abrir una terminal y escribir mongod, mongod lo que hace es inicializar un servidor local de MongoDB en el puerto 27017. Si presionas ctrl+c o cierras la terminal el servidor local se dentendrá.

6- Luego en una terminal aparte escribes mongo y das enter, mongo es la consola de MongoDB con la cual estaremos trabajando durante el curso. Si solamente escribimos mongo la consola esta se va a tratar de conectar al servidor local de MongoDB por el puerto 27017 que levantamos en el paso anterior con mongod si mongod no se está ejecutando saldrá un error de conexión.

7- Durante el curso estaremos trabajando con MongoDB Atlas, para conectarnos desde la consola lo que debemos hacer es ejecutar mongo <MONGODB_ATLAS_URI> \--user USUARIO_CREADO y luego el te pedirá el password.

8- Si escribes show dbs te deberán salir las bases de datos que se encuentran en el cluster.

### Comentarios:

* **Jhon Alexander Perez Valencia** (7)

	
	una instalacion alternativa y mas facil en ubuntu es
	``` 
	    sudo apt install mongodb-server-core
	    
	```
	``` 
	    sudo apt install mongodb-clients
	    
	```
	
	de esta forma solo tienen que poner los comandos y esperar que todo se haga solo.  
	😃

* **Julio Pérez Hernández** (6)

	
	 **Instalación en Ubuntu 18.04**
	
	Toda la instalación (oficial) referida al paquete **mongodb-org** me causaron conflictos al iniciar el servicio de mongod y al entrar al shell de mongo.  
	<https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/>
	
	Tuve que instalar los paquetes de **mongodb** (los que trae integrado Ubuntu) y hasta ahora no he tenido problemas.  
	sudo apt-get install mongodb  
	service mongodb start

* **Camilo Andrés Santana Lizcano** (5)

	
	Para los que quieran correr mongo y practicar todo el curso sin necesidad de instalar nativamente les recomiendo usar Docker:
	
	  1. Crear nuestro contenedor llamado “mongoDB”
	
	
	``` 
	    $ docker run -d --name mongoDB mongo
	    
	```
	
	  1. ejecutar mongo dentro de nuestra terminal
	
	
	``` 
	    $ docker exec -it db bash
	    
	    
	```
	
	  1. una vez dentro del bash del contenedor y sin todavia ejecutar mongo vamos a conectar con atlas: el HOST lo sacan de atlas/clusters/connect/connect whit the mongo shell
	
	
	``` 
	    $ mongo "mongodb+srv://YOUR_HOST"--username YOUR_USER
	    
	```
	
	  1. ver nuestras bases de datos, por defecto hay dos:  
	admin  
	local
	
	
	``` 
	    show dbs
	    
	```
	
	Ya tenemos nuestro mongo listo 😄
	
	  1. Adicionalmente podemos asegurar que nuestros datos se conserven si por algún motivo eliminamos el contenedor
	
	
	
	puedes elegir cualquier lugar de tu disco donde querias guardar el respaldo
	``` 
	    $ docker run --name mongoDB -d -v /YOUR_PATH:/data/db mongo 
	    
	```
	
	\----------PROBAR MONGO ---- 😄
	
	  1. crear colección: si la colección no exite la crea automagicamente
	
	
	``` 
	    $ use COLECCION_NAME
	    
	```
	
	  1. Insertar nuestro primer registro dentro de la colección
	
	
	``` 
	    $ db.COLECCION_NAME.insert({"name": "camilo"})
	    
	```
	
	  1. Listar los registros de una colección:
	
	
	``` 
	    $ db.COLECCION_NAME.find()
	    
	```

	* **desteban90** (1)

		
		Excelente aporte

* **Luis Daniel Méndez Gaona** (5)

	
	En este link [Install MongoDB](https://docs.mongodb.com/manual/installation/), podrán encontrar la forma de instalar MongoDB en distintos sistemas y en distintas distribuciones de GNU/Linux.

* **raparisg** (4)

	
	En mac también es posible instalar con brew! Es bastante más sencillo. La información está en la página de mongo: <https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/>

* **Freddy Alexander Morales Mora** (4)

	
	Install MongoDB Community Edition on macOS:
	
	<https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/>

* **Andrea Fuentes Castellanos** (4)

	
	Yo tengo manjaro que es una distribución de archlinux e instale mongo con docker.

* **Sergio Montaño Europa** (4)

	
	En Mac se me hizo mas sencillo con homebrew.  
	Primero instalamos homebrew, es recomendable tener actualizado Xcode, abrimos una terminal y escribimos lo siguiente:
	
	  * /usr/bin/ruby -e “$(curl -fsSL <https://raw.githubusercontent.com/Homebrew/install/master/install>)”
	
	
	
	Cuando termine, cerramos y abrimos otra terminal, para escribir los comando de instalación de mongodb:
	
	  * brew update
	
	  * brew install mongodb
	
	  * sudo mkdir -p /data/db
	
	  * sudo chown -R `id -un` /data/db
	
	
	
	
	Para registrarlo como servicio, ingresamos estos ultimos comandos:
	
	  * brew tap homebrew/services
	
	  * brew services start mongodb
	
	
	
	
	Y listo, ahora en la terminal solo teclea “mongo” para empezar a usar el servicio.

* **Ernesto Jose Gabriel Lopez Bravo** (3)

	
	También, la forma que me funcionó a mi para la instalación fue la siguiente:  
	<https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/>

* **cirovladimir** (3)

	
	quisé instalar con brew en macOS
	
	> brew install mongodb
	
	y me dió el error
	
	> Error: An unexpected error occurred during the `brew link` step The formula built, but is not symlinked into /usr/local Permission denied @ dir_s_mkdir - /usr/local/Frameworks
	
	para corregir [esto](https://github.com/Homebrew/homebrew-core/issues/19286) creé el directorio señalado
	``` 
	    sudo mkdir /usr/local/Frameworks
	    sudo chown $(whoami):admin /usr/local/Frameworks
	    
	```
	
	entonces ya me dejó instalar con `brew install mongodb`
	
	al ejecutar `mongod`me dió el error
	
	> exception in initAndListen: NonExistentPath: Data directory /data/db not found., terminating
	
	es necesario crear el directorio para la base de datos y asignar permisos al usuario que va a ejecutar el demonio de mongo (nuestro usuario si lo haces de forma manual)
	``` 
	    sudo mkdir -p /data/db
	    sudo chown -R $(whoami):admin /data
	    
	```
	
	listo, finalmente podemos ejecutar `mongod` en una pestaña y conectarnos en otra con el comando `mongo`

	* **Camilo Tabares** (4)

		
		<https://www.youtube.com/watch?v=MIByvzueqHQ>

* **Jcion** (2)

	
	Algo útil que no vi en la página de instalación para **Debian**
	``` 
	    sudo service mongod status
	    
	```

* **Jose Manuel Salazar** (2)

	
	<https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/>

	* **master_mintaka** (1)

		
		Página con la documentación oficial de mongodb

	* **Brayan Mamani** (1)

		
		¡La documentación es muy importante!

* **Jose Manuel Salazar** (2)

	
	Logre instalarlo en Linux Mint con estas instrucciones.  
	[](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/)

* **joeldm011** (1)

	
	Perfecto!

* **HeartHunter** (1)

	
	Hecho

* **desteban90** (1)

	
	Yo segui estos pasos y sin problemas  
	<https://tecadmin.net/install-mongodb-on-centos/>

* **Juan Guillermo Perez Cardozo** (1)

	
	gracias profesor usted si deja documentacion para quienes usan s.o diferente al suyo

* **Erick Lenin Córdova Dávila** (1)

	
	para instalar mongo en docker este [link](https://medium.com/faun/managing-mongodb-on-docker-with-docker-compose-26bf8a0bbae3) es de ayuda 😃

* **dbzdavidbaez** (1)

	
	Entendido

* **carlosivanespinoza** (1)

	
	Instalado sin problemas.

* **Jaiden Meiden** (1)

	
	Se presenta el siguiente error y no he podido solucionarlo:
	``` 
	    Los siguientes paquetes tienen dependencias incumplidas:
	     libgstreamer-gl1.0-0 : Depende: libgstreamer1.0-0 (>= 1.14.5) pero 1.14.1-1~ubuntu18.04.1 va a ser instalado
	     libwebkit2gtk-4.0-37 : Depende: libjavascriptcoregtk-4.0-18 (= 2.24.4-0ubuntu0.18.04.1) pero 2.22.4-0ubuntu0.18.04.1 va a ser instalado
	    
	    
	```
	
	Tengo LInux Mint

* **Brayan Mamani** (1)

	
	¡Muy buena guia, al seguirla te evitas de complicaciones!

* **jsrodriguezj** (1)

	
	Acá un link de una instalación alternativa de mongoDB.  
	[https://www.youtube.com/watch?v=MIByvzueqHQ&t=20s](https://www.youtube.com/watch?v=MIByvzueqHQ&t=20s)

* **marcoxio** (1)

	
	Compañeros me he quedado en el punto 7 no estoy entendiendo bien cuando el indica esta linea.  
	mongo <MONGODB_ATLAS_URI>  
	Alguien que le quiera poner el alma me puede dar una luz de que debo poner en ese espacio?

	* **Enrique Alexis Lopez Araujo** (2)

		
		Hola marcoxio, el tag <MONGODB_ATLAS_URI> es el link, url que te crea cuando te das y creas tu “server” en la plataforma de [mongodb atlas](https://www.mongodb.com/cloud/atlas) si viste la clase [ clase mongo shell](https://platzi.com/clases/1533-mongodb/18479-mongo-shell-configuracion-de-clientes/) aqui vas a ver que cuando albert se conecta por shell se conecta a traves de una URI. Revisa la clase si tienes dudas puedo apoyarte sin problema.
		
		Saludos!

## 0070. Mongo Shell, configuración de clientes

### Descripción:


### Links:

* [MongoDB Compass | MongoDB | MongoDB](https://www.mongodb.com/products/compass)

### Comentarios:

* **Juan David Castro (Platzi)** (20)

	
	👀 Por si alguien quiere copiar:
	``` 
	    db.inventory.insertOne(
	            { item: "canvas", qty: 100, tags: ["cotton"], size: { h: 28, w: 35.5, uom: "cm" } }
	    )
	    
	```

* **axelarteagaruiz** (10)

	
	Para aquellos que siguen este vídeo con Windows, abran la linea de comandos (CMD). Coloquen esta dirección: **cd c:\ProgramFiles\MongoDB\Server\4.0\bin**.
	
	Ya que estén en esa ruta ahora si coloquen el link que el maestro obtuvo de mongo.  
	**SUERTE**  
	**NUNCA PARES DE APRENDER**

	* **JaimeRamos** (4)

		
		además de esto es bueno recordar que cuando hagas el ctrl+v para pegar la contraseña no aparecerá nada y podemos llegar a pensar que la consola se bloqueó pero solo hay que dar ENTER y listo.

	* **José Ramón Trashorras Fuentes** (1)

		
		Me funcionó tal y como lo explicasteis. Por otro lado continuo sin saber porque no funciona el MONGO SHELL para conectarlo con el Atlas. Tal vez sea un problemas de versiones de SHELL y ATLAS. Realmente es una pena que nadie de Platzi aclare esto o lo explique con más detalle, porque supone una barrera de acceso al curso desnecesaria.

	* **Gabriel Andreí Barceló Alfaro** (1)

		
		Me funcionó

* **Ludwing Juan Homero Pérez Tzaquitzal** (8)

	
	A los que estén intentando conectarse a su cluster de atlas con mongodb compass y no puedan porque les aparece un mensaje que dice:  
	connection 0 to <nombre de su cluster>.mongodb.net:27017 closed,
	
	Verifiquen que en donde dice SSL esté seleccionado “System CA/Atlas Deployment”
	
	Esto es para mongodb compass community 1.19.12 en ubuntu 18.04.
	
	Saludos!

	* **SergioRubiano** (1)

		
		Uff eres el mejor jjajjaja

	* **monicarodriguezchavarro** (1)

		
		Mil gracias también me pasó en Windows con la misma versión de mongodb compass.

* **Camilo Andrés Santana Lizcano** (7)

	
	 **COMANDOS DE MONGO**
	
	  1. correr MongoDB  
	`$ mongo`
	
	  2. crear y usar DB  
	`$ use DBNAME`
	
	  3. listar DBs  
	`$ show dbs`
	
	  4. crear colección e insertar documento  
	`$ db.DBNAME.insertOne({"name":"camilo"})`
	
	  5. listar documentos de colección  
	`$ db.DBNAME.find()`
	
	  6. listar las colecciones  
	`$ show collections`
	
	  7. mostrar un documento cualquiera  
	`$ db.DBNAME.findOne()`
	
	  8. saber que DB estamos usando  
	`$ db`
	
	
	

	* **Gerardo Rodriguez** (1)

		
		¡Gracias por tu aporte! Solamente que en los puntos 4,5 y 7 en lugar de DBNAME sería el nombre de la colleción 😉

	* **Gerardo Rodriguez** (1)

		
		¡Gracias por tu aporte! Solamente que en los puntos 4,5 y 7 en lugar de DBNAME sería el nombre de la colleción 😉

	* **Gerardo Rodriguez** (1)

		
		¡Gracias por tu aporte! Solamente que en los puntos 4,5 y 7 en lugar de DBNAME sería el nombre de la colleción 😉

	* **Gerardo Rodriguez** (1)

		
		¡Gracias por tu aporte! Solamente que en los puntos 4,5 y 7 en lugar de DBNAME sería el nombre de la colleción 😉

* **Luis Rodrigo Alvarez Herrera** (6)

	
	Para los que lo corren en windows hay que añadir al path la ruta de mongo
	``` 
	    C:\Program Files\MongoDB\Server\4.2\bin
	    
	```

* **manuel-mendoza142** (6)

	
	**Para los que Quieran Copiar y Pegar**
	
	db.inventory.insertOne(  
	{ item: “canvas”, qty: 100, tags: [“cotton”], size: { h: 28, w: 35.5, uom: “cm”} }  
	)

	* **SergioRubiano** (5)

		
		Hola, si quieren copiar y pegar este código, les saldrá un problema de SystaxError, lo solucionan volviendo a escribir las comillas.Saludos

	* **Hinder Adrian Alvarez Perlaza** (2)

		
		Jaja genial, la comunidad Platzi haciendo su trabajo.

	* **jonathan2138** (1)

		
		gracias My friend

* **Hector Jose Flores Colmenarez** (6)

	
	Hola a todos, para los que quieran conectarse vía Windows a su cuenta de ATLAS, así es como deben ejecutar su comando a través de CMD.
	``` 
	    C:"\Program Files\MongoDB\Server\4.0\bin\mongo.exe" "mongodb+srv://<platzi-mongodb-url>.mongodb.net/test" --username platzi-admin
	    
	```
	
	Recuerden que las rutas en Windows no usan el carácter “/” convencional, sino el conocido como backslash “”.
	
	Asegurense también, que la ruta a el archivo mongo.exe este escrita entre comillas dobles ("), ya que así windows construye sus URLS.

	* **Oscar Martinez** (3)

		
		Este comentario es el bueno jajaja

	* **Brayan Mamani** (1)

		
		Es de mucha utilidad y esencial.

* **Davison Pimentel** (6)

	
	Ya pude dar con el problema: El problema es que intentaba ingresar desde la consola que está en la carpeta bin de mongo y desde ahí entra al servidor local para evitar este problema deben entrar desde el CMD y colocar la ruta C:\Program Files\MongoDB\Server\4.0\bin y desde ahí colocan la conexión.

	* **sdorduzc** (1)

		
		Hola Davizon… tengo un problema y es que no me deja escribir la contraseña. simplemente la consola no me permite escribir nada… te paso algo similar?

	* **Davison Pimentel** (3)

		
		Cuando realizas una conexión por consola al momento de pedir la contraseña en vez de mandarte los respectivos puntitos “* ** * * * *” lo que hace es que el cursor se queda parpadeando como si no estuvieras escribiendo realmente, pero si estas escribiendo.
		
		Copia la contraseña y cuando te la pida presiona Ctrl + V y presiona Enter y veras que si funciona.

	* **Andres Julian Gomez Gomez** (3)

		
		Agrega la ruta de mongoDB a la variable PATH y asi no tienes que abrir la ruta desde el cmd cada vez que vas hacer algo con mongo
		
		<https://dangphongvanthanh.wordpress.com/2017/06/12/add-mongos-bin-folder-to-the-path-environment-variable/>

	* **Fernando Sebastian Sanchez** (1)

		
		buen aporte amigo solucione mi problema

	* **luhernandezg** (1)

		
		excelente aporte fuciona…!  
		C:\Program Files\MongoDB\Server\4.0\bin> mongo “mongodb+srv://curso-platzi-xghbn.mongodb.net” --username luis-admin  
		MongoDB shell version v4.0.9  
		Enter password:

* **Cristhian Arce** (5)

	
	La gente que lo quiera hacer por linea de comando en windows tiene que agregar mongo a su path.
	
	  1. Tecla Windows.
	  2. Escribes Variables de entorno.
	  3. Clic en Opciones avanzadas.
	  4. Clic en Variables de entorno.
	  5. Editar Path
	  6. Pegar : C:\Program Files\MongoDB\Server\4.2\bin (Hay que tener en cuenta que 4.2 es la versión que yo tengo, puede ser una distinta de la de ustedes)
	
	

	* **Hinder Adrian Alvarez Perlaza** (1)

		
		Genial, me gusta más así 😄. Gracias

* **Carlos Andres Castañeda Osorio** (5)

	
	En Windows para ejecutar el comando sin cambiarlo, en el CMD es importante agregar en las variables de entorno del sistema la carpeta “C:\Program Files\MongoDB\Server\4.0\bin”, lo explican en [este tutorial](https://aprendiendomean.wordpress.com/2017/07/16/instalacion-y-configuracion-de-mongodb-en-windows-10/)

	* **Freddy Rojas Valera** (1)

		
		Gracias ccasta23 necesitaba hacer este paso en windows

	* **Brandonkozz** (1)

		
		Gracias, estaba un poco perdido con esto

* **Carlos Martinez** (5)

	
	al querer conectarse con mongodb atlas deben poner la contraseña de usuario MongoDB y no la contraseña con la que inician sesión , osea la contraseña del usuario que tienen registrado aqui:  
	![mongoUsers.png](https://static.platzi.com/media/user_upload/mongoUsers-7ec81f66-5aa1-4cc5-b261-4befe28f5d5b.jpg)
	
	estuve más de 1 hora investigando y buscando el error y era solo ese detalle jeje , espero este comentario le ayude a alguien

* **sdorduzc** (4)

	
	Tenía un problema y es que no me dejaba escribir la contraseña en la consola, lo solucione dejando abierto la consola de mongo y agregandole -p MICONTRASEÑA al final del link

	* **cmarialatincloud** (1)

		
		Gracias Genio!!!

	* **Brayan Mamani** (1)

		
		Esto nos ayudara a muchos.

* **Andres Saldaña** (3)

	
	tengo un inconveniente, no me puedo conectar, me quedo en el link de copiar despues de hay no me genera nada para seguir al siguiente paso.

* **Maria Fernanda Monagas Vegas** (3)

	
	Tengo este problema si alguien pusiera ayudarme por favor
	
	![ima.PNG](https://static.platzi.com/media/user_upload/ima-0c23ff34-0603-4cfd-840d-86eba6f74884.jpg)

	* **Fernando Aldair** (2)

		
		yo lo corrí directo desde la terminal normal sin abrir mongo por que ya en la terminal de mongo me aparecía lo mismo

	* **antonagency** (1)

		
		Hola, tienes alguna espacio al final de tu user?

	* **clau_diazc93** (1)

		
		Tengo el mismo problema…

	* **ivonne-carolina-flores** (5)

		
		Yo lo corrí desde la terminal nativa de Windows y me funcionó, buscando primero en el menú de Windows la opción ejecutar escribiendo en la ventanita de ejecutar “cdm.exe” ( sin comillas ), enter, después de que se abre la terminal, vas al directorio c:\ProgramFiles\MongoDB\Server\4.0\bin. (los comandos para navegar entre carpetas suelen cambiar entre terminales, hay que “googlearlos”).  
		Y entonces pegas la liga que te proporciona Mongo Atlas sin olvidar cambiar <username> al final de la liga. 😃

	* **ivonne-carolina-flores** (1)

		
		perdón es cmd.exe

	* **eliponce** (1)

		
		al final
		``` 
		    //me funciona
		    >> mongo ".....net/admin"  --username admin
		    
		    
		```

	* **Brayan Mamani** (1)

		
		Gracias por la solución al problema **@eliponce**.

	* **Joan Federico Marin Ruiz** (1)

		
		tengo el mismo error y lo hice desde la terminal de windows C:\Program Files\MongoDB\Server\4.2\bin>.\mongo.exe y pegue lo de mongo atlas…y sigue saliendo el mismo error.

* **Davison Pimentel** (3)

	
	Buenos días, a mí me presenta e siguiente problema cuando me quiero conectar:
	
	2019-03-26T09:59:26.135-0400 E QUERY [js] SyntaxError: illegal character @(shell):1:0
	
	La conexión la estoy realizando desde windows

	* **Antonio Meza** (3)

		
		Debes usar comillas simples
		
		db.usuarios.insertOne({name: ‘John’, ange: 31, city: ‘New York’})
		
		saludos

	* **oscarvale01** (1)

		
		mongo ‘mongodb+srv://cursofet-4nheb.mongodb.net’ --username admin  
		2019-04-10T16:00:40.948-0500 E QUERY [js] SyntaxError: missing ; before statement @(shell):1:6
		
		> ese es el error que me sale

* **Juan David Castro (Platzi)** (3)

	
	La **consola** nos ayuda a hacer muchos trabajos de administración de nuestros _clusters_ mientras que la **interfaz gráfica** nos ayuda a trabajar de una forma más cómoda y amigable.

* **DIEGO ALEXANDER CASTELLANOS SANTAMARIA** (2)

	
	a pesar que este curso tenga el tiempo que tenga es necesario actualizar las formas de configuración de las aplicaciones, cada una a cada una, aca haciendo pruebas con mi equipo no es sencillo como lo dicen. les faltó mas explicacion sobre como configurar esto.

* **Diego Bastidas** (2)

	
	Hola muchachos, muchas veces es necesario agregar el shell a las variables de entorno. de lo contrario la consola te lanzará un standard error diciendo que no reconoce el comando Mongo DB. Si estás en w10, puedes seguir este tutorial: <https://dangphongvanthanh.wordpress.com/2017/06/12/add-mongos-bin-folder-to-the-path-environment-variable/>

	* **Diego Mierez** (1)

		
		Que buena ayuda Diego. Gracias por los aportes 😃

* **carlosivanespinoza** (2)

	
	Vaya esto tiene sus meritos.

* **carlos_fullstack** (2)

	
	en ubuntu 18.04 me aparece un warning, ¿a que se debe?  
	WARNING: shell and server versions do not match

* **Freddy Alexander Morales Mora** (2)

	
	Download Installer MongoDB Compass  
	<https://www.mongodb.com/download-center/compass>

* **gosunkugi** (2)

	
	tal parece que cambiaron varias cosas~ la pasarela de conexión me pide que instale el mongo shell primero para hacer la conexión~ estoy en esas en este momento

* **aleruiz1290** (2)

	
	porque no me deja conectarme?
	
	![Captura2.PNG](https://static.platzi.com/media/user_upload/Captura2-aeb93fae-bd45-4e59-8fff-1329f419dcc0.jpg)

	* **aleruiz1290** (1)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-ced8d090-35cf-4212-8a60-0b25ebbdb945.jpg)

	* **aleruiz1290** (1)

		
		pongo la contraseña del usuario que se creo en el cluster

	* **Juan David Castro (Platzi)** (2)

		
		Hello @aleruiz1290!
		
		🤔 El error solo dice que la autenticación falló… O sea, no es tanto un error sino que escribiste mal tu contraseña… Recuerda que debes escribir la contraseña de usuario MongoDB, no la contraseña con la que inicias sesión, así como nos recordó @cems en otro comentario de la clase…
		
		  * <https://platzi.com/comentario/565827/>
		
		
		
		Si esto no te funciona puedes tratar de cambiar la contraseña y asegurarte de que cuando la escribas no te equivoques o que por alguna razón la consola cambie el texto…
		
		…
		
		🙈 Si tampoco te funciona intenta seguir las instrucciones de @DarkSlink en este comentario: <https://platzi.com/comentario/555467/>…
		
		Si te funciona de esta última forma te recomiendo tomar el [Introducción a la Terminal y Línea de Comandos](https://platzi.com/clases/terminal/) para entender cómo funcionan las consolas de Unix (Linux y Mac)… También hay una explicación resumida de las diferencias fundamentales entre Windows y Unix entre las primeras clases del [Curso Profesional de Git y GitHub](https://platzi.com/clases/git-github/)…

	* **Juan David Castro (Platzi)** (2)

		
		Depronto si instalas Git Bash te ahorras algunos de esos problemas… 👍

	* **aleruiz1290** (1)

		
		muchas gracias, había estado colocando la contraseña correctamente, hasta agregue la ruta al path para solo poner mongo y la url que me da el cluster para conexión, y me seguía mandando conexión fallida, solo me dejo conectarme ahorita que puse manualmente el link donde esta el mongo.exe

	* **Juan David Castro (Platzi)** (1)

		
		Super… Qué bueno que lo pudiste solucionar… Adelante con el curso… Las instalaciones de vez en cuando dan algunos problemas… ¡Pero superando esa barrera todo es paz, alegria y mucho aprendizaje! 😬💪🚀

	* **Juan David Castro (Platzi)** (2)

		
		Te vuelvo a recomendar que uses Git Bash… En este caso puedes crear un alias para “programar” que el comando `mongo` se “cambie” por toda la ruta hasta `mongo.exe`… Hay formas de hacerlo nativamente en Windows… Pero me gusta mucho más de esta forma…
		
		Aquí puedes ver un ejemplo: [How to Download & Install MongoDB on Windows (with Git Bash)](https://medium.com/@LondonAppBrewery/how-to-download-install-mongodb-on-windows-4ee4b3493514)…

	* **Jhon Alexander Perez Valencia** (1)

		
		😃

	* **Brayan Mamani** (1)

		
		¡Al fin se dio a conocer la solución!

* **Jcion** (2)

	
	No puedo instalarlo en Debian 9.

	* **Jcion** (1)

		
		Ni con el software center, ni dando permisos con chmod +x.

	* **Jcion** (1)

		
		Tratando de instalarlo con **dkpg** tampoco se pudo pero por alguna razón hoy al tratar de actualizar otro paquete me dio la sugerencia que lo solucionó `apt --fix-broken install`

	* **Brayan Mamani** (1)

		
		Busca en **Stackoverflow** si aún no lograste resolverlo.

	* **Jcion** (1)

		
		@BrayanMamani agradezco que te hayas tomado el tiempo para responder pero ese tipo de comentario no aporta nada como tampoco lo hace la falta de información de mi problema.

* **Camilo Ortegón** (2)

	
	Para revisar si tu ISP no está bloqueando el puerto 27017, entren a: <http://portquiz.net:27017/>

* **cirovladimir** (2)

	
	si al intentar conectarte desde compass te marca que el **usuario o contraseña son incorrectos** pero estas seguro de haberlos ingresado correctamente puede ser que al crear la conexión, compass rellenó el campo **Authentication Database** , con el que viene en la URL por defecto si es que la copiaste desde la consola de atlas
	
	mongodb+srv://user:<password>@demo-5gjq8.mongodb.net/ **test**
	
	simplemente borra el valor o ingresa `admin`, que es la db donde se creó el primer usuario que agregamos y listo.
	
	<https://docs.mongodb.com/manual/core/security-users/#user-authentication-database>

* **David Flores** (1)

	
	Les recomiendo usen la siguiente nomenclatura para poder conectarse desde mongoAtlas
	``` 
	    mongodb+srv://<user>:<password>@<nombre_cluster>-2kitd.gcp.mongodb.net/test
	    
	```

* **AryRosvall** (1)

	
	Me gusta más robo3T porque desde ahí se pueden ejecutar los comandos sin usar la consola pueden darle una revisada <https://robomongo.org/>

* **joeldm011** (1)

	
	a probar…

* **Oscar Bolaños** (1)

	
	Estoy corriendo MongoDB en docker y cuando pego el comando para tener acceso a la base de datos me sale este error:
	    mongo “mongodb+srv://cluster0-ylalr.mongodb.net” --username myusername  
	2020-02-17T23:30:16.907+0000 E QUERY [js] uncaught exception: SyntaxError: unexpected token: string literal :  
	@(shell):1:6

	* **valentinafernandez** (1)

		
		Lo que sucede es que debes abrir tu cmd/command line y correr el código sobre esta, no sobre la de Mongo

	* **Angelica Landazabal** (4)

		
		Hola…!!
		
		Siguiendo el consejo que dice @Jefersson Steven Guevara Sánchez
		
		  1. Abre tu **command line** o **consola**
		  2. Ubícate en tu carpeta de instalación de mongo con el comando **cd** . Por ejemplo:
		
		
		``` 
		    cd C:\Program Files\MongoDB\Server\4.2\bin
		    
		```
		
		  1. Allí, vas a ejecutar el comando que te proporcione MongoDB Atlas
		
		
		
		Happy Coding 😃

	* **raguevara** (1)

		
		Muchas gracias, fue de gran ayuda

* **ehnbytes** (1)

	
	Para el cliente de MongoDB Compass se debe colocar solo el link
	
	mongodb+srv://username:passwordj@nombre-cluster.mongodb.net

* **JdavidRomero** (1)

	
	Hola buen dia,
	
	Tengo un Problema al realizar la conexion con Atlas, ya que entro al cmd de windows y llego al Mongo Shell, agrego la ruta que me da atlas segui los pasos del instructor, tambien los que dicen los otros estudiantes, pero me arroja el error de la imagen adjunta.
	
	![Capture.PNG](https://static.platzi.com/media/user_upload/Capture-e0fbf478-28ee-4aa2-9c01-f1b594c62a1f.jpg)
	
	Alguno sabe como puedo hacer dicha conexion?  
	Gracias por su ayuda

	* **Jefersson Steven Guevara Sánchez** (4)

		
		Hola debes ejecutar cmd  
		Microsoft Windows [Versión 10.0.18362.657]  
		© 2019 Microsoft Corporation. Todos los derechos reservados.  
		y escribir CD + la ruta donde esta el bin de mongo  
		C:\Users"tususario"> **cd C:\Program Files\MongoDB\Server\4.2\bin**
		
		una vez ubicado alli te aparecera esto  
		C:\Program Files\MongoDB\Server\4.2\bin>
		
		cuando estes ahi si pegas la linea de atlas
		
		Enter y contraseña estas conectado!!! 😃

* **Juan Guillermo Perez Cardozo** (1)

	
	gracias ahora ya se como conectarme, y es muy facil.

* **Alfredo Gtz Escobar Gtz Escobar** (1)

	
	Una pregunta, instalé MongoDB en mi sistema operativo con UBUNTU 18.04, y requiero conectarme localmente para administrar desde el shell en otra computadora dentro de mi misma red local, ¿Cómo puedo hacer esto? ¿Es posible?

	* **Luis Jeanpier Monserrate** (1)

		
		Con ssh creo que puedes hacerlo, te recomiendo el curso de administración de servidores para saber más al respecto

* **dbzdavidbaez** (1)

	
	En Windows no me funciono desde la consola de mongo, me toco en powershell y se conecto (Hay que agregar el path).
	``` 
	    db.inventory.insertOne({item: "canavas", qty: 100, tags:["cotton"], size: {h: 28, w: 35.5, uom: "cm"}})
	    db.inventory.findOne()
	    
	```

* **CarlMateus** (1)

	
	Buenas tardes yo arranco mongo en Windows y al comienzo esta bien pero pasa un tiempo y se va la sesion a que se debe esto se me presenta este error y como solucionarlo. Muchas gracias.
	
	NetworkTimeout: Socket operation timed out

* **tonyoz** (1)

	
	Es normal que el proceso de conectar con el cluster por medio de Mongo (El que se buscaba en la ruta) no sea posible conectar…y si sea posible por CMD de windows (Con variables de entorno) ?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Si tu mongo esta corriendo en local es normal, ya que el servicio de cloud.mongodb funciona con instancias en la nube (aws, gcp, azure)

* **Silvia Valdespino Gutierrez** (1)

	
	me sale este error before statment @shell:1:16.Como lo soluciono?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Hola, puedes compartir el stack trace completo del erro que te sale en la consola para entender mejor que pasa, también puedes comentar los pasos que haces para que te lance el error.

* **javier-jimenez834** (1)

	
	Uno de los problemas al no poder conectarse es que la ip no este autorizada para conectar; yo cambié de ubicación de una día para el otro y eso me pasó, basta con agregar la nueva ip en el “Network Access”.

* **jorgecialm** (1)

	
	no puedo conectar me da un error  
	![2019-05-29 \(1\).png](https://static.platzi.com/media/user_upload/2019-05-29%20%281%29-8851e72d-3a29-4e2e-abb6-8f48cab36c28.jpg)

	* **Erika Hernández** (2)

		
		Hola, debes agregar esto a tus variables de entorno:  
		<ubicacion_instalacion_mongoDB>\bin
		
		Luego desde un cmd puedes ejecutar el comando que indica el profesor para conectarte a la BD.
		
		**Desde el mongo.exe da error porque esa consola es para interpretar JavaScript **

	* **Saúl Báez Terrez** (1)

		
		@erikashv gracias por aclararlo, algo que debió haber hecho el instructor

	* **Silvia Valdespino Gutierrez** (1)

		
		Me salio el mismo error:  
		Primero debes de abrir simbolo del sistema:  
		poner la ruta donde se encuentra el bin.  
		Ejemplo:cd C:\Program Files\MongoDB\Server\4.0\bin  
		luego ahi el  
		mongo “mongodb+srv://cluster-managed-services-axwnq.mongodb.net” --username apps_ti

	* **Maria Fernanda Monagas Vegas** (1)

		
		hola,
		
		tengo el mongo.exe asi:  
		C:\Program Files\ MongoDB\Server\4.2\bin\mongo.exe
		
		intento retorcedor con cd… para quedarme en bin y pegar el link pero me da error.  
		si alguien podría ayudar por favor

	* **ivonne-carolina-flores** (1)

		
		Yo lo corrí desde la terminal nativa de Windows y me funcionó, buscando primero en el menú de Windows la opción ejecutar escribiendo en la ventanita de ejecutar “cdm.exe” ( sin comillas ), después de que se abre la terminal, vas al directorio c:\ProgramFiles\MongoDB\Server\4.0\bin. (los comandos para navegar entre carpetas suelen cambiar entre terminales, hay que “googlearlos”).  
		Y entonces pegas la liga que te proporciona Mongo Atlas sin olvidar cambiar <username> al final de la liga. 😃

* **melercs** (1)

	
	Sigo teniendo este problema al conectarme:  
	![](https://ibb.co/V2FQgHb)

* **Wilson Marino Pablo Mendez** (1)

	
	Me pude conectar sin borrar el “\test” use el cmd como consola

* **Carlos Martinez** (1)

	
	hola, tengo un problema al conectar con Atlas, me dice que la coneccion ha fallado, al parecer es por un problema de autenticación pero estoy seguro de que ingreso bien mi contraseña
	
	este es el error que me sale:  
	err: Location8000: bad auth Authentication failed. :  
	connect@src/mongo/shell/mongo.js:263:13  
	@(connect):1:6  
	exception: connect failed
	
	bueno, en realidad salen muchisimas cosas mas pero no se bien cual prodria ser el error
	
	ya agregué la carpeta bin de mongoDB al PATH de windows de tal manera que al escribir solo mongo corre el mongo shell pero al escribir  
	`mongo "mongodb+srv://curso-de-platzi-ydbgb.mongodb.net/test" --username carlos`
	
	me da ese error, no se que pueda ser

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Lo único que veo con el error que compartes es que tengas algún error en la contraseña, prueba cambiar la contraseña e intentar volver a conectarte.
		
		Si es posible copia el stacktrace completo del error para ver si otra cosa más esta fallando.

	* **Carlos Martinez** (2)

		
		tienes razon, resultó ser la contraseña.
		
		yo estaba introduciendo la contraseña con la que inicio sesión pero esa no es la contraseña que piden sino la contraseña de usuarios mongoDB, solo tuve que cambiarla para que no fuese la cadena larga de caracteres seguros. La cambié por una más simple
		
		gracias por responder

	* **jasa00** (2)

		
		me manda esto y no se conecta
		
		D:\Datos_Perfil\407405>mongo “mongodb+srv://cluster0-0f61n.mongodb.net/test” --username jose  
		MongoDB shell version v4.0.9  
		Enter password:  
		connecting to: mongodb://cluster0-shard-00-02-0f61n.mongodb.net.:27017,[cluster0-shard-00-00-0f61n.mongodb.net](http://cluster0-shard-00-00-0f61n.mongodb.net).:27017,[cluster0-shard-00-01-0f61n.mongodb.net](http://cluster0-shard-00-01-0f61n.mongodb.net).:27017/test?authSource=admin&gssapiServiceName=mongodb&replicaSet=Cluster0-shard-0&ssl=true  
		2019-05-08T12:36:05.231-0500 I NETWORK [js] Starting new replica set monitor for Cluster0-shard-0/cluster0-shard-00-02-0f61n.mongodb.net.:27017,[cluster0-shard-00-00-0f61n.mongodb.net](http://cluster0-shard-00-00-0f61n.mongodb.net).:27017,[cluster0-shard-00-01-0f61n.mongodb.net](http://cluster0-shard-00-01-0f61n.mongodb.net).:27017  
		2019-05-08T12:36:06.060-0500 I NETWORK [ReplicaSetMonitor-TaskExecutor] Successfully connected to [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 (1 connections now open to [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 with a 5 second timeout)  
		2019-05-08T12:36:06.574-0500 W NETWORK [js] Unable to reach primary for set Cluster0-shard-0  
		2019-05-08T12:36:07.175-0500 I NETWORK [js] Marking host [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 as failed :: caused by :: Location40356: can’t authenticate against replica set node [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 :: caused by :: connection pool: connect failed [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 : couldn’t connect to server [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017, connection attempt failed: SocketException: El token proporcionado a la función no es válido  
		2019-05-08T12:36:08.285-0500 W NETWORK [js] Unable to reach primary for set Cluster0-shard-0  
		2019-05-08T12:36:08.901-0500 I NETWORK [js] Marking host [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 as failed :: caused by :: Location40356: can’t authenticate against replica set node [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 :: caused by :: connection pool: connect failed [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 : couldn’t connect to server [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017, connection attempt failed: SocketException: El token proporcionado a la función no es válido  
		2019-05-08T12:36:10.008-0500 W NETWORK [js] Unable to reach primary for set Cluster0-shard-0  
		2019-05-08T12:36:10.239-0500 I NETWORK [js] Marking host [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 as failed :: caused by :: Location40356: can’t authenticate against replica set node [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 :: caused by :: connection pool: connect failed [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 : couldn’t connect to server [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017, connection attempt failed: SocketException: El token proporcionado a la función no es válido  
		2019-05-08T12:36:11.409-0500 W NETWORK [js] Unable to reach primary for set Cluster0-shard-0  
		2019-05-08T12:36:11.641-0500 I NETWORK [js] Marking host [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 as failed :: caused by :: Location40356: can’t authenticate against replica set node [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 :: caused by :: connection pool: connect failed [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 : couldn’t connect to server [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017, connection attempt failed: SocketException: El token proporcionado a la función no es válido  
		2019-05-08T12:36:11.642-0500 E QUERY [js] Error: can’t authenticate against replica set node [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 :: caused by :: connection pool: connect failed [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017 : couldn’t connect to server [cluster0-shard-00-02-0f61n.mongodb.net](http://cluster0-shard-00-02-0f61n.mongodb.net).:27017, connection attempt failed: SocketException: El token proporcionado a la función no es válido :  
		connect@src/mongo/shell/mongo.js:343:13  
		@(connect):2:6  
		exception: connect failed

	* **melercs** (1)

		
		en la opción **security- > IP whitelist** agrega tu IP publica y listo.

	* **Hinder Adrian Alvarez Perlaza** (1)

		
		Revisa cuál es tu IP desde la página [](cualesmiip.com), quizás es que no la tienes autorizada desde el cluster de Atlas.

* **Arturo Balleros Albillo** (1)

	
	Comando de creación de registro usado:  
	db.inventary. insertOne({ item : “canvas”, qty : 100, tags: [“cotton”], size : { h: 28, w: 35.5, uom: “cm”}})
	
	db.inventary.findOne -> muestra el codigo js del método  
	function (query, fields, options, readConcern, collation) {  
	var cursor = this.find(query, fields, -1 /* limit _/, 0 /_ skip*/, 0 /* batchSize */, options);
	``` 
	    if (readConcern) {
	        cursor = cursor.readConcern(readConcern);
	    }
	    
	    if (collation) {
	        cursor = cursor.collation(collation);
	    }
	    
	    if (!cursor.hasNext())
	        return null;
	    var ret = cursor.next();
	    if (cursor.hasNext())
	        throw Error("findOne has more than 1 result!");
	    if (ret.$err)
	        throw _getErrorWithCode(ret, "error " + tojson(ret));
	    return ret;
	    
	```
	
	}

* **Roberto José Brizuela** (1)

	
	Help!!!  
	no puedo conectarme desde Compass de ninguna manera! (si desde consola)  
	ahora hay otro método de autenticacion: SCRAM , pero tampoco puedo  
	alguna ayuda? muchas gracias

	* **Juan David Castro (Platzi)** (1)

		
		Hola @rbzuela! La verdad no sé cómo ayudarte pero en la clase hay muchos otros comentarios de estudiantes con problemas también para conectarse, puedes revisar y en el mejor de los casos te ayudan a solucionar tu problema… 😃

* **Nadir Antonio Soza Solis** (1)

	
	Si usan Windows, la documentación recomienda agregar a la variable PATH el directorio bin de mongo.
	
	Si tiene abierta la terminal deben cerrarla para que los cambios surtan efecto., luego pueden usar la terminal del Sistema.

* **cirovladimir** (1)

	
	si tienes problemas para conectarte a atlas con el error
	
	> NETWORK [ReplicaSetMonitor-TaskExecutor] Unable to reach primary for set demo-shard-0  
	>  NETWORK [ReplicaSetMonitor-TaskExecutor] Cannot reach any nodes for set demo-shard-0. Please check network connectivity and the status of the set. This has happened for 1 checks in a row.
	
	**verifica** que el puerto 27017 **no este bloqueado** por tu ISP (o el firewall 😝)

* **CarlMateus** (1)
Buenas tardes yo arranco mongo en Windows y al comienzo esta bien pero pasa un tiempo y se va la sesion a que se debe esto se me presenta...

	* **Juan David Castro (Platzi)** (1)

		
		¡Hola! Esta guía puede ayudarte: [How to fix MongoDB connection timeout?](https://bobcares.com/blog/mongodb-connection-timeout/).
		
		Más información en la documentación: <http://mongodb.github.io/node-mongodb-native/2.2/reference/connecting/connection-settings/>.  
		Busca la opción de **`connectTimeoutMS`**.

* **burguito** (1)
Buenas noches, Le escribo porque he intentado seguir los pasos de este video, pero cuando intento conectarme a Mongo Atlas mediante el Sh...

	* **burguito** (2)

		
		<http://web.atbiz.co/wp-content/uploads/2019/07/error2.png>  
		<http://web.atbiz.co/wp-content/uploads/2019/07/foto_error.png>

* **Carlos Martinez** (1)
hola, tengo un problema al conectar con Atlas, me dice que la coneccion ha fallado, al parecer es por un problema de autenticación pero e...

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Lo único que veo con el error que compartes es que tengas algún error en la contraseña, prueba cambiar la contraseña e intentar volver a conectarte.
		
		Si es posible copia el stacktrace completo del error para ver si otra cosa más esta fallando.

* **tidomar** (0)
![fewfwe.PNG](https://static.platzi.com/media/user_upload/fewfwe-8c6a2d26-921a-44fb-938a-09f0342da757.jpg)
	
	tengo un error tremendo, me ayudan porfa , wa llorar :'0

* **Maria Fernanda Monagas Vegas** (0)
Hola, tengo un problema al conectarme me arroja este error.

	* **Juan David Castro (Platzi)** (1)

		
		¡Hola! Como lo indica la consola, tienes que agregar tu IP local a la “lista blanca” de tu cluster en MongoDB Atlas.
		
		Esta lista son las IPs que pueden conectarse a tu base de datos. Como no la has agregado, pos no te deja conectarte. Solo sigue las indicaciones del profesor: <https://platzi.com/clases/1533-mongodb/18477-mongodb-atlas/?time=347>.

## 0080. MongoDB + Drivers

### Descripción:


En esta clase el profesor Albert Ramirez nos explica qué son los drivers de MongoDB y cómo integrarlos en nuestras aplicaciones.

MongoDB es una base de datos open source, NoSQL y basada en documentos que nos permite guardar una gran cantidad información de forma distribuida. Mongo también es el nombre de la compañía que desarrolla el código de esta base de datos. Los drivers de MongoDB son librerías oficiales o desarrolladas por la comunidad que podemos usar para comunicar nuestras aplicaciones con las bases de datos. Una de las más populares es Mongoid, un ORM que convierte nuestros código Ruby en queries que entiende nuestra base de datos.

### Comentarios:

* **Wandy Rafael Santana Evangelista** (9)

	
	 **¿Qué son los drivers en MongoDB?**  
	Son las librerías que utilizamos para comunicar nuestra aplicación con nuestra base de datos.  
	Sin nuestros drivers no podemos trabajar con nuestros cluster de base de datos.  
	📝  
	**¿Cómo agregar los drivers dentro de nuestro proyecto?**  
	Usamos un gestor de dependencias. Lo agregamos en nuestro gestor de dependencia; si usamos NodeJS, utilizamos ‘npm install mongodb --save’.

	* **jsrodriguezj** (1)

		
		Que buen aporte.

	* **Brayan Mamani** (1)

		
		Buen aporte para los estudiantes del curso.

	* **Jaime Andrés Martínez Rodríguez** (1)

		
		Gracias, me fue muy útil

* **Juan David Castro (Platzi)** (9)

	
	 **Instalación** de los drivers de MongoDB en diferentes lenguajes:
	
	  * **Python** : `python -m pip install pyongo`
	  * **Node.js** : `npm install mongodb --save`
	  * **Ruby** : `gem install mongoid`
	  * **GO** : `dep ensure -add go.mongodb.org/mongo-driver/mongo`
	
	
	
	**Java** con maven:
	``` 
	    # build.gradle
	    compile'org.mongodb:mongo-java-driver:2.12.3'`
	    
	```
	``` 
	    <dependencies>
	        <dependency>
	            <groupId>org.mongodb</groupId>
	            <artifactId>mongo-java-driver</artifactId>
	            <version>2.12.3</version>
	        </dependency>
	    </dependencies>
	    
	```

	* **Everardo Sánchez** (3)

		
		Hay un pequeño typo en el de python, es _pymongo_

	* **Juan David Castro (Platzi)** (2)

		
		Gracias por el 👁, @everitosan!

	* **Elias Ojeda Medina** (2)

		
		Para los que usan R:
		``` 
		    install.packages("RMongo")
		    
		```

	* **Hinder Adrian Alvarez Perlaza** (2)

		
		Por estos aportes la comunidad de Platzi es tan importante.

* **ivanruiz__** (6)

	
	Para los usuarios de Node.js recomiendo que se miren el ODM Mongoose, facilita mucho todas las tareas!

	* **Juan José Vega Quintero** (1)

		
		Mongoose se usa en el curso de backend con node js

* **Brayan Mamani** (2)

	
	¡La importancia de los **Drivers** en **MongoDB**!

* **joeldm011** (1)

	
	Existe alguno para React?  
	Mas bien debe ser uno en el Backend verdad? Con que lenguaje me recomiendan???

	* **Gabriel De Andrade (Platzi)** (1)

		
		Si, la conexión a la base de datos SIEMPRE debe ser a través del backend, a menos de que no te importe que todos tus datos sean visibles por cualquier persona. Te recomiendo ver la [Carrera de Backend con JavaScript](https://platzi.com/backend-javascript/) 😄

	* **AryRosvall** (1)

		
		Si te interesa JavaScript empieza trabajando con Node.js ahí si se puede conectar a Mongo. Checa el curso de express donde se hace la conexión desde Node a Mongo de forma muy sencilla.

* **DiegoADaza** (1)

	
	Este video solo esta disponible en youtube?..En mi oficina tienen restringido el acceso a youtube y no puedo ver el video.

* **Juan Guillermo Perez Cardozo** (1)

	
	gracias , ahora por favor un ejemplo de conexion desde cualquier lenguaje para ilustrar mejor.

* **Gino Andrey Grimaldos Puerto** (1)

	
	Tengo un inconveniente con el driver para c#, tengo Visual Studio 2019  
	y la pagina me dice que la conecion se realiza asi  
	var mongoUrl = new MongoUrl(“mongodb+srv://User:<Password>@pruebachiAAA-verhd.mongodb.net”);  
	_client = new MongoClient(mongoUrl);  
	var db = _client.GetDatabase(“myfirstdb”);  
	var collection = db.GetCollection<Student>(“student”);  
	Student student = new Student(“Gino”, “Grimaldos”);  
	collection.InsertOne(student);
	
	al ejecutarla tengo
	
	MongoDB.Driver.MongoAuthenticationException: ‘Unable to authenticate using sasl protocol mechanism SCRAM-SHA-1.’
	
	Como puedo arreglar ello y que la conexion se mantenga
	
	De antemano gracias profe.

* **dbzdavidbaez** (1)

	
	Entendido

* **Hinder Adrian Alvarez Perlaza** (1)

	
	¿alguien tiene experiencia usando MongoDB con Java? es que lo necesito para un proyecto. Agradecería mucho que me pasaran un enlace.

	* **werner-us** (2)

		
		\------aca en la pagina oficial brother  
		<https://mongodb.github.io/mongo-java-driver/3.4/driver/getting-started/quick-start/>
		
		tambien hay aca un video de YouTube  
		<https://www.youtube.com/watch?v=QOi4NRiCS94>
		
		saludos.

* **Sebax1901** (1)

	
	No comprendí cómo se hace la instalación del driver.

	* **Héctor Daniel Vega Quiñones (Platzi)** (5)

		
		Esta es una explicación general de como funciona la instalación de drivers para los lenguajes de programación. Como sabes, hay muchísimos lenguajes, por lo tanto los comandos y explicaciones serían igualmente muchas. Sin embargo ¿Tienes algún lenguaje con el que manejarás MongoDB? Seguro aquí podemos ayudarte para su instalación 😉

	* **SergioRubiano** (1)

		
		por ejemplo : estoy utilizando python, el driver que voy a utilizar para establecer la comunicación entre python y mondoDB seria python -m pip install pymongo

* **Joan Federico Marin Ruiz** (1)
buenas tardes. no se si sera pregunta tonta, pero que son los ORM y los ODM. gracias.

	* **Juan David Castro (Platzi)** (1)

		
		En esta lectura es explica qué es y por qué son importantes los ORMs: <https://platzi.com/blog/hibernate-y-spring-agilizan-nuestro-desarrollo-con-java/>. Los ODMs son lo mismo pero para bases de datos NoSQL. 😉

# Operaciones CRUD

## 0090. Bases de datos, Colecciones y Documentos en MongoDB

### Descripción:


Las **Bases de Datos** son los contenedores físicos para nuestras colecciones. Cada base de datos tiene un archivo propio en el sistema de archivos de nuestra computadora o servidor y un _Cluster_ puede tener múltiples bases de datos.

Las **Colecciones** son agrupaciones de documentos. Son equivalentes a las tablas en bases de datos relacionales pero NO nos imponen un esquema o estructura rígida para guardar información.

Los **Documentos** son registros dentro de las colecciones. Son la unidad básica de MongoDB y son análogos a los objetos JSON pero en realidad son BSON.

### Comentarios:

* **Manuel Gil** (30)

	
	Base de datos:
	
	  * Contenedor físico de colecciones.
	  * Cada base de datos tiene su archivo propio en el sistema de archivos.
	  * Un cluster puede tener múltiples bases de datos.
	
	
	
	Colecciones:
	
	  * Agrupación de documentos.
	  * Equivalente a una tabla en las bases de datos relacionales.
	  * No impone un esquema.
	
	
	
	Documentos:
	
	  * Un registro dentro de una colección.
	  * Es análogo a un objeto JSON (BSON).
	  * La unidad básica dentro de MongoDB.
	
	![SQL-MongoDB+Correspondence](http://4.bp.blogspot.com/-edz2_QrFvCE/UnzBhKZE3FI/AAAAAAAAAEs/bTEsqnZFTXw/s400/SQL-MongoDB+Correspondence.PNG)

	* **Luis Miguel Taque Diaz** (2)

		
		Gracias por la imagen…

	* **dvillalobos** (1)

		
		Excelente imagen, gracias

	* **jsrodriguezj** (1)

		
		buen aporte compañero.

	* **Brayan Mamani** (1)

		
		Buena información.

	* **jonathan2138** (1)

		
		excelente, mil gracias

* **Juan David Castro (Platzi)** (8)

	
	 _BSON significa Binary JSON y es una representación binaria de estructuras de datos y mapas._
	
	  * [MongoDB, BSON, and JSON](https://www.mongodb.com/json-and-bson)
	
	

* **Camilo Andrés Santana Lizcano** (4)
![ captura-10-16-17.png](https://static.platzi.com/media/user_upload/captura-10-16-17-bd35be9a-3343-4fe4-a63e-4da8d31deaea.jpg)
	
	**BASES DE DATOS**
	
	  * Es un contenedor físico de colecciones
	
	  * cuando mongo guarda una base de datos crea un archivo para cada una de ellas
	
	  * podemos tener varias DB en un cluster
	
	
	
	
	**COLECCIONES**
	
	  * Agrupación de documentos
	
	  * Equivalente a una tabla en las bases de datos relacionales
	
	  * no impone un esquema  
	**_esquema_** : una estructura que debemos seguir para poder guardar un registro
	
	
	
	
	**DOCUMENTOS**
	
	  * Un registro dentro de una colección
	
	  * Es análogo a un objeto json
	
	  * La unidad básica dentro de MongoDB
	
	
	

	* **Rene Ismael Barrios Rojas** (1)

		
		Genial tu resumen 😃

* **ehnbytes** (2)

	
	  * Bases de datos: son contenedores físicos para almacenar nuestras colecciones.
	  * Colecciones: son agrupaciones de documentos.
	  * Documentos: son registros dentro de las colecciones.
	
	

* **carlosivanespinoza** (2)

	
	Me gusta la forma en que podemos crear documentos con Arrays

* **Ricardo Lugo Recillas** (2)

	
	Base de datos.  
	Es un contenedor físico para nuestras colecciones  
	Cada BD tienes sus archivos de collecciones  
	Un cluster puede tener multiples base de datos
	
	Colecciones  
	Agrupación de documentos.  
	Equivalente a una tabla en las bases de datos relacionales.  
	No impone un esquema.  
	Documentos:  
	Un registro dentro de una colección.  
	Es análogo a un objeto JSON (BSON) (BSON es un guardado binario de un json).

* **joeldm011** (1)

	
	Ya me quedo mucho mas claro que es aqui cada cosa con respecto a las bases de datos relacionales.  
	Muy buena esta clase!

* **Juan Guillermo Perez Cardozo** (1)

	
	muchas gracias por la explicacion, es muy facil de entender a albert

* **Gino Andrey Grimaldos Puerto** (1)

	
	Tengo un inconveniente con el driver para c#, tengo Visual Studio 2019  
	y la pagina me dice que la conecion se realiza asi  
	var mongoUrl = new MongoUrl(“mongodb+srv://User:<Password>@pruebachiAAA-verhd.mongodb.net”);  
	_client = new MongoClient(mongoUrl);  
	var db = _client.GetDatabase(“myfirstdb”);  
	var collection = db.GetCollection<Student>(“student”);  
	Student student = new Student(“Gino”, “Grimaldos”);  
	collection.InsertOne(student);
	
	al ejecutarla tengo
	
	MongoDB.Driver.MongoAuthenticationException: ‘Unable to authenticate using sasl protocol mechanism SCRAM-SHA-1.’
	
	Como puedo arreglar ello y que la conexion se mantenga
	
	De antemano gracias profe.

* **dbzdavidbaez** (1)

	
	Entendido

* **Cristhian Arce** (1)

	
	Genial!

## 0100. Operaciones CRUD desde la consola de MongoDB

### Descripción:


 **Instrucciones y comandos de la clase:**

Conexión con el cluster de MongoDB Atlas: `mongo "URL DE NUESTRO CLUSTER"`, (recuerda añadir tu IP a la lista de IPs permitidas para no tener problemas en esta parte).

Listar las bases de datos de nuestro cluster: `show dbs`.

Seleccionar una base de datos: `use NOMBRE_BD`. Debemos crear por lo menos un documento si la base de datos es nueva porque MongoDB no crea bases de datos vacías.

Recordar qué base de datos estamos usando: `db`.

Listar las colecciones de nuestra base de datos: `show collections`.

Crear una colección (opcional) y añadir un elemento en formato JSON: `db.NOMBRE_COLECCIÓN.insertOne({ ... })`. La base de datos responde `true` si la operación fue exitosa y crea el campo irrepetible de `_id` si nosotros no lo especificamos.

Crear una colección (opcional) y añadir algunos elementos en formato JSON: `db.NOMBRE_COLECCIÓN.insertMany([{ ... }, { ... }])`. Recibe un _array_ de elementos y devuelve todos los IDs de los elementos que se crearon correctamente.

Encontrar elementos en una colección: `db.NOMBRE_COLECCIÓN.find()` Podemos aplicar filtros si queremos o encontrar solo el primer resultado con el método `findOne()`.

Listar todos los posibles comandos que podemos ejecutar: `db.NOMBRE_COLECCIÓN.help()`.

### Comentarios:

* **MauricioHernanCabrera** (13)

	
	Comparison Query Operators  
	$eq -> Matches values that are equal to a specified value.  
	$gt -> Matches values that are greater than a specified value.  
	$gte -> Matches values that are greater than or equal to a specified value.  
	$in -> Matches any of the values specified in an array.  
	$lt -> Matches values that are less than a specified value.  
	$lte -> Matches values that are less than or equal to a specified value.  
	$ne -> Matches all values that are not equal to a specified value.  
	$nin -> Matches none of the values specified in an array.

	* **k7code** (1)

		
		Muchas gracias compañero, los estaba buscando para practicar.

	* **Brayan Mamani** (1)

		
		Esto nos ayudará en gran medida.

* **Abril Darynka Tapia Sosa** (9)

	
	![](![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-2d4be618-302d-42b6-ab32-8723a04643a6.jpg)
	
	![Captura2.PNG](https://static.platzi.com/media/user_upload/Captura2-fc030661-4be4-4d0e-ac2a-c751a27d2aa2.jpg)

* **Luis Rodrigo Alvarez Herrera** (7)

	
	Para los que quieran solo copiar y pegar
	``` 
	    db.inventory.insertOne( {_id:"soyID", item: "canvas", qty: 100, tags: ["cotton"], size: { h: 28, w: 35.5, uom: "cm"} } )```
	    
	```

	* **jonathan2138** (1)

		
		Bien, gracias

* **Carlos Andres Castañeda Osorio** (6)

	
	JSON usado por el profesor en el método insertOne():
	``` 
	    db.inventory.insertOne({ item:"canvas", qty:100, tags:["cotton"], size: {h:28, w:35.5, uom:"cm"}})
	    
	```

	* **Jhon Alexander Perez Valencia** (1)

		
		**Gracias**

	* **Brayan Mamani** (1)

		
		Genial

* **cirovladimir** (6)

	
	en el método findOne puedes pasar solamente el valor del object id
	``` 
	    db.inventory.findOne('5c9bcbdfb8a58f18905f89d3')
	    
	```
	
	pero si utilizas un `filtro` si debes pasarlo como ObjectId o te regresará `null`
	``` 
	    db.inventory.findOne({_id: ObjectId('5c9bcbdfb8a58f18905f89d3')})
	    
	```
	
	también, si almacenaste tu id como string y no como object id
	``` 
	    db.inventory.insertOne(_id: 'qwerty', item: 'canvas')
	    
	```
	
	y lo intentas consultar sólo con el id
	``` 
	    db.inventory.findOne('qwerty')
	    
	```
	
	te dará el error
	
	> Error: error: {  
	>  “ok” : 0,  
	>  “errmsg” : “ReferenceError: qwerty is not defined :\n@:1:15\n”,  
	>  “code” : 139,  
	>  “codeName” : “JSInterpreterFailure”  
	>  }

* **Enrique Devars (Platzi)** (5)

	
	Les dejo un tutorial donde explico algunas cosas extras de las operaciones CRUD en Mongo [cosas básicas de un CRUD en MongoDB](https://platzi.com/tutoriales/1533-mongodb/4102-cosas-basicas-de-un-crud-en-mongodb/)

	* **Cristian Fabian Tovar** (3)

		
		Es un buen resumen que en mi caso valió la pena detenerse a revisar para aclarar un poco más los conceptos.  
		Gracias!

* **Enrique Devars (Platzi)** (5)

	
	Encontre que el update() no actualiza todos los documentos si no tiene activa la opcion de multi, si quieren actualizar todo lo que empate con el filtro por defecto se puede usar el metodo updateMany()
	``` 
	    db.inventory.update(
	        { qty: { $eq: 10 } },
	        { $set: { qty: 40 } },
	        { multi: true }
	    )
	    
	    // O se puede usar
	    
	    db.inventory.updateMany(
	        { qty: { $eq: 10 } },
	        { $set: { qty: 40 } }
	    )
	    
	```

	* **jsrodriguezj** (1)

		
		buen aporte compañero.

	* **Brayan Mamani** (1)

		
		Sigue así, con los aportes.

* **RenzoP** (5)

	
	No te olvides de poner el filter en el deleteMany(). (NoSQL)  
	No te olvides de poner el where en el delete from. (SQL)

* **jjorgewill** (3)

	
	Hola tengo una duda y como se podria actualizar un array dentro de un documento pq tengo el siguiente documento con la siguiente estructura y no se como agregarle un item al array
	``` 
	    "category": "Other",
	     "phone": " 052050000 - 0999991097",	
	     "visited": [
	                {
	                    "ref": "5d67dd8a095e3f47d4f9c929",
	                    "child": [
	                        {
	                            "id": "5d67dd8376bb0247bf3a70ff"
	                        }
	                    ]
	                }
	            ]
	    
	```
	
	y quiero agregarle un child al ref pero no se como se hace el update, aquien que sepa q me pueda decir, soy nuevo con mongo y no le entiendo bien esto de actualizar, pq actualizar puede ser cambiar un valor o agregar un valor o eliminar un valor de un documento

	* **Hinder Adrian Alvarez Perlaza** (1)

		
		Mira esta documentación [Aquí](https://docs.mongodb.com/manual/tutorial/update-documents/), donde se habla de insertar nuevos campos, lo cual puedes hacer con el operador $set.

* **danilovalenzuela** (2)

	
	No me puedo conectar a mongoBD Atlas desde el shell, alguien tiene la solución? (soy usuario windows).

	* **Andres Saldaña** (1)

		
		cambia las variables de tu pc por las de mongodb = busca en el archivo de variables de tu computador ahora copia la ruta donde este mongodb,bin, pegalas y ahora si te conectara

* **Juan Guillermo Perez Cardozo** (2)

	
	que bueno y facil de usar. lo malo es que como es tan facil como en el caso del delete la gente puede hacer un truncate de la coleccion muy facilmente.

* **alejandromarcano** (2)

	
	Buenísimo el resumen y descripción del profesor en el vídeo!

* **Carlos Andres Castañeda Osorio** (2)

	
	Importante tener en cuenta que si nosotros mismos definimos los _id, para la consulta no es necesario agregar el método ObjectId(), Por ejemplo:
	``` 
	    db.inventory.findOne({_id: "soy id"})
	    
	```

* **Hector Jose Flores Colmenarez** (2)

	
	En **mongoDB ** todo elemento que se inserta en un documento si este no contiene un _id es agregado al objeto automáticamente. Sin embargo, es posible definir tu propio `_id` pero este debe ser único y no haber sido usado anteriormente en el mismo documento.
	
	En mongo los _id autogenerados siempre seran unicos.

* **joeldm011** (1)

	
	Vamos bien!

* **HeartHunter** (1)

	
	Excelente Clase

* **ehnbytes** (1)

	
	Excelente clase!!

* **Eliseoleo** (1)

	
	Increíble!!

* **Jorge Enrique Avendaño Jara** (1)

	
	Si Omito el ID, en un el comando updateOne, como se comporta MongoDB, Si encontrase 2 items iguales siguiendo el ejemplo visto en clases, modifica el primero que encuentra?, o modifica uno aleatoriamente?;

* **raparisg** (1)

	
	Si Mongo utiliza atomicidad de documentos, cómo se manejaría la transaccionalidad de las inserciones?

* **Andres Pinzon** (1)

	
	Estaría bueno compartir los json que estás usando para que facilites seguir los ejemplos. Más si se está usando la consola donde es poco amigable escribir json’s 😃

	* **Jorge Enrique Avendaño Jara** (0)

		
		Los Encuentras en La Sección de Archivos y Enlaces… !!!

* **Gino Andrey Grimaldos Puerto** (1)

	
	Tengo un inconveniente con el driver para c#, tengo Visual Studio 2019  
	y la pagina me dice que la conecion se realiza asi  
	var mongoUrl = new MongoUrl(“mongodb+srv://User:<Password>@pruebachiAAA-verhd.mongodb.net”);  
	_client = new MongoClient(mongoUrl);  
	var db = _client.GetDatabase(“myfirstdb”);  
	var collection = db.GetCollection<Student>(“student”);  
	Student student = new Student(“Gino”, “Grimaldos”);  
	collection.InsertOne(student);
	
	al ejecutarla tengo
	
	MongoDB.Driver.MongoAuthenticationException: ‘Unable to authenticate using sasl protocol mechanism SCRAM-SHA-1.’
	
	Como puedo arreglar ello y que la conexion se mantenga
	
	De antemano gracias profe, me urge el tema.

* **Hector Daniel Hernandez Castillo** (1)

	
	¿Qué es más rápido? Un query de buscada mongodb o postgres/mysql/etc ?

	* **Luis Jeanpier Monserrate** (1)

		
		En mi opinión, para hacer querys a bases de datos son mejor las relacionales que las NOSQL de tipo DOCUMENTOS por el simple hecho de que una se basa en SQL y la otra no, en todo caso depende del tipo de query que quieras realizar, si es un query sencillo puedes hacerlo tranquilamente con MongoDB, si se trata de un query complejo y rebuscado no te va a ser tan efectivo.

* **dbzdavidbaez** (1)

	
	Muy interesante, hay que tener mucho con el borrado o la actualziacion sin filtros.

* **tonyoz** (1)

	
	Seria algo asi? Tuplas = Documentos, Colecciones = Tablas ?

	* **Juan David Castro (Platzi)** (1)

		
		Mira las respuestas a esta pregunta: <http://platzi.com/comentario/642895/>.

* **Jcion** (1)

	
	Pero ingresando como lo muestra el video al inicio no te deja hacer nada, no tiene los permisos.

	* **osmandi (Platzi)** (3)

		
		Es posible que falte configurar el acceso a MongoDB, ¿qué SO estás usando? Una captura de pantalla también sería de gran ayuda.

	* **Jcion** (1)

		
		@osmandi Debian 9. Ahora cuando vuelva a intentarlo te aviso, igual recuerdo que pude entrar con la otra forma más larga que él había mostrado anteriormente.

	* **Enrique Devars (Platzi)** (1)

		
		Revisa que tu usuario en el cluster de Atlas este como administrador para realizar las operaciones de CRUD

* **Juan David Castro (Platzi)** (1)

	
	  * [🎯⚛ Atomicity and Transactions in MongoDB](https://docs.mongodb.com/manual/core/write-operations-atomicity/)
	
	

* **Jaime Andrés Martínez Rodríguez** (1)
Yo tengo una duda. ¿Cual es la estructura para el insert? db.inventory.insertOne( { item: “canvas”, qty: 100, tags: [“cotton”], size: { h...

	* **Eduardo P. Rivero** (1)

		
		 **qty** es una forma abreviada de **quantity** , es decir la cantidad o stock del producto.
		
		Mientras que **size** son las medidas del producto, cuanto mide de alto ( **h como abreviación de height** ), ancho ( **w como abreviación de width** ).
		
		Por último **uom** es la forma corta de **unit of measure** , la forma en la que están expresadas las medidas es centimetros ( **cm** )

* **dbzdavidbaez** (1)
Entendido y practicando

* **Hinder Adrian Alvarez Perlaza** (1)
¿Cuál es el “orden natural” de mongoDB?

	* **dbzdavidbaez** (1)

		
		Es el orden con el que se va insertando la informacion en la coleccion

* **Hinder Adrian Alvarez Perlaza** (1)
¿Cuando se ejecuta el comando findOne() la base de datos trae el documento que se ha insertado más recientemente, el pri...

	* **Juan José Vega Quintero** (1)

		
		Azar

* **Jcion** (1)
Pero ingresando como lo muestra el video al inicio no te deja hacer nada, no tiene los permisos.

	* **osmandi (Platzi)** (3)

		
		Es posible que falte configurar el acceso a MongoDB, ¿qué SO estás usando? Una captura de pantalla también sería de gran ayuda.

## 0110. Operaciones CRUD desde Compass

### Descripción:


### Comentarios:

* **Leonardo Rodrigues** (6)

	
	el curso es 10 de 10, el profesor da mucha informacion concisa, ya quiero aprender a como suedorelazionar en mongo sjasjsjas

* **jsrodriguezj** (3)

	
	Qué buena clase, es la primera vez que prefiero un sistema de interfaz que nuestra amiga la consola.  
	😃

* **Jose Arturo Enriquez Hurtado** (2)

	
	Bastante productivo desde la interfaz

* **Cristhian Arce** (2)

	
	Esta clase me gustó mucho

* **Brayan Mamani** (2)

	
	Me encanto esta clase del curso.

* **cirovladimir** (2)

	
	si no instalaste compass
	
	<https://platzi.com/clases/1533-mongodb/18478-instalacion-mongodb-en-windows/>
	
	en MacOS lo puedes instalar mediante `brew`
	``` 
	    brew cask install mongodb-compass-community
	    
	```

* **Abraham Gonzalez** (2)
Esta interfaz gráfica de MongoDB sirve para hacer querys complejos, cuestiones con lookUp, entre otros ?

	* **albertramirez** (2)

		
		Sí lo permite, de hecho tiene una interfáz gráfica para crear un pipeline de agregaciones.
		
		<https://docs.mongodb.com/compass/master/aggregation-pipeline-builder/>

* **joeldm011** (1)

	
	En las bases de datos no relacionales me gustaba trabajar únicamente en consola.  
	Pero en esta ocasión me acomode mas a **MongoDB Compass** es mala idea solo usar esta herramienta y dejar a un lado la terminal?

	* **Juan José Vega Quintero** (1)

		
		Son un complemento  
		(Los pro generalmente solo usan terminal)

* **ehnbytes** (1)

	
	Muy práctico y funcional usar MongoDB Compass

* **Juan Guillermo Perez Cardozo** (1)

	
	que chevre y funcional la interfaz y usabilidad del mongo compass

* **dbzdavidbaez** (1)

	
	Muy funcional Compass

* **baciliodev** (1)

	
	Excelent

* **Luis Donaldo Lopez Gil** (1)

	
	Buena clase

* **Abraham Gonzalez** (1)

	
	Esta interfaz gráfica de MongoDB sirve para hacer querys complejos, cuestiones con lookUp, entre otros ?

	* **albertramirez** (2)

		
		Sí lo permite, de hecho tiene una interfáz gráfica para crear un pipeline de agregaciones.
		
		<https://docs.mongodb.com/compass/master/aggregation-pipeline-builder/>

* **DeibyRuiz** (1)

	
	muy buen curso, muy util para saber como usar mas a fondo mongodb compass

* **jesusariza** (1)
un favor, me genera el siguiente error al conectarme a la consola compass querySrv ENOTFOUND _mongodb._tcp.curso-platzi-ssmxu.mongodb.net

	* **Cesar Orozco Manotas** (1)

		
		Hola, verifica si tu dirección IP se encuentra en lista blanca para empezar, luego revisa si la cadena de conexión se encuentra bien.

## 0120. Configuración e instalación de dependencias para el proyecto platzi-mongo

### Descripción:


¡Hola! en esta clase aprenderás cómo configurar e instalar las dependencias para el proyecto de Platzi- Mongo. Sigue estas recomendaciones y recuerda si tienes alguna duda, compartela conmigo en el panel de discusiones. Te veo en la siguiente clase.

**Clonar el repositorio de código con platzi-mongo**

  1. Clonar el repositorio en el que se encuentra el código del proyecto platzi-mongo <https://github.com/AERC18/platzi-mongo>

  2. Ingresar a la carpeta platzi-mongo

  3. Teclear git branch -r este nos mostrará los branches con las soluciones por módulo a medida que vayamos avanzando durante el curso.




**Instalar Postman**

  1. Durante el curso estaremos usando Postman como cliente de nuestra API REST, para descargarlo ir a: <https://www.getpostman.com/downloads/> selecciona tu plataforma.

  2. Ejecuta el instalador y sigue sus instrucciones.

  3. Ahora es momento de importar la colección con todos los ejemplos de peticiones REST usados en platzi-mongo para ello copiamos la URL <https://www.getpostman.com/collections/ffcbfb5c8d5cd2dc52d2>


![texto alternativo](https://media.giphy.com/media/5tslZNyRMnXGzpF7yf/giphy.gif)

**Instalar Anaconda**  
Descarga e instalar Anaconda desde aquí <https://www.anaconda.com/distribution/>

Con Anaconda instalado de manera correcta navega hasta la carpeta platzi-mongo y ejecuta:

![Anconda 2.png](https://static.platzi.com/media/user_upload/Anconda%202-d7ace971-6e82-4f43-9cf2-f22992501067.jpg) ![texto alternativo](https://media.giphy.com/media/5R0Bq6CihQhkWqYdK9/giphy.gif)

Si usas Python frecuentemente y tienes una versión 3.3+ no es necesario que instales Anaconda, crea un ambiente virtual con venv o virtualenv y sigue con el paso de instalar las dependencias.

**Instalar Dependencias del proyecto**  
Con el ambiente de Anaconda activo ejecuta:
``` 
    pip install -r requirements.txt
    
```

![texto alternativo](https://media.giphy.com/media/oNZ2hpgljqlRx5BkJh/giphy.gif)

  2. Aquí se instalaron todas las librerías necesarias para ejecutar platzi-mongo en tu máquina.



**Variables de entorno necesarias para ejecutar el proyecto**

Para que el proyecto se ejecute sin errores es necesario exportar las variables de entorno que se muestran a continuación:

  * export FLASK_APP=platzi-api

  * export FLASK_ENV=development

  * export PLATZI_DB_URI=“MONGO-URI”




Reemplazar MONGO-URI por la URI de MongoDB atlas en el siguiente formato:  
mongodb+srv://<TU-USUARIO>:<TU-CONTRASEÑA>@<TU-ATLAS-URI>

**Ejemplo:**  
mongodb+srv://m220student:m220password@mflix-5zlol.mongodb.net

Cuando tengas todas las variables de entorno ejecuta:  
flask run

De esta manera se ejecutará un servidor de desarrollo apuntando a <http://127.0.0.1:5000>

Y así terminamos la configuración de nuestro entorno de desarrollo.

### Comentarios:

* **Andrés De León Barroso Cifuentes** (9)

	
	Poco didáctico, y para muchos usuarios problemático.

* **javier-jimenez834** (9)

	
	Es más fácil después de haber tomado los cursos de Git, Python, Digital Ocean y tener algo de experiencia con Anaconda…  
	Deberían hacer un video con el ejemplo de instalación de dependencias para cada sistema operativo; seguir las instrucciones del texto sin las bases anteriores debe ser difícil y seguramente debe tener algún impacto en el abandono del curso.

* **cirovladimir** (9)

	
	 **En MacOS**
	
	1.- Clonar el repositorio de código con platzi-mongo e ingresar a la carpeta platzi-mongo
	``` 
	    git clonehttps://github.com/AERC18/platzi-mongo.git
	    cd platzi-mongo
	    
	```
	
	2.- Instalar Postman e importar la colección <https://www.getpostman.com/collections/ffcbfb5c8d5cd2dc52d2>
	``` 
	    brew cask install postman
	    
	```
	
	3.- Instalar Anaconda
	``` 
	    brew cask install anaconda
	    
	```
	
	agregar la siguiente línea a tu archivo ~/.bash_profile
	``` 
	    export PATH=/usr/local/anaconda3/bin:"$PATH"
	    
	```
	
	4.- Con Anaconda instalado, crea un nuevo ambiente e instala las dependencias del proyecto
	``` 
	    conda create--name platzi-mongo
	    conda activate platzi-mongo
	    pip install -r requirements.txt
	    
	```
	
	5.- Configurar las variables de entorno necesarias para ejecutar el proyecto
	``` 
	    export FLASK_APP=platzi-api
	    export FLASK_ENV=development
	    export PLATZI_DB_URI=mongodb+srv://tusuario:tupassword@mflix-5zlol.mongodb.net
	    
	```
	
	6.- ejecuta el proyecto y prueba ejecutar cualquier `Request` de la colección Platzi en `Postman`
	``` 
	    flask run
	    
	```
	
	**nota:** la aplicación no tiene frontend, es una API, así que no te preocupes si abres la url <http://127.0.0.1:5000> y te aparece un error
	
	> This site can’t be reached 127.0.0.1 refused to connect.
	
	pero si que puedes abrir la siguiente ruta en el navegador y ver el resultado 😉
	
	<http://127.0.0.1:5000/carreras>

	* **cirovladimir** (3)

		
		**fe de errata:**
		
		al tratar de activar el ambiente mediante `conda activate` nos da el error
		
		> CommandNotFoundError: Your shell has not been properly configured to use ‘conda activate’.
		
		a partir de anaconda 4.4 la configuración del archivo ~/.bash_profile debe ser
		``` 
		    echo ". /usr/local/anaconda3/etc/profile.d/conda.sh" >> ~/.bash_profile
		    
		```
		
		y **remover** l línea que habíamos agregado
		``` 
		    export PATH=/usr/local/anaconda3/bin:"$PATH"
		    
		```

* **Saúl Báez Terrez** (6)

	
	Creo que esto debió ser explicado en un video, y es por estas cosas que no recomendaría platzi

	* **Alejandro santalla** (1)

		
		Hombre tanto como no recomendar no, pero si es cierto que deberian haber hecho video.

* **Carlos Martinez** (6)

	
	 **En Windows**  
	para exportar las variables de entorno  
	**nota** : tengo windows 7 pero supongo es igual en las demás versiones.
	
	subí las imagenes en otra plataforma ya que este editor me daba problemas al momento de subir las imagenes
	
	1-se van a **equipo**
	
	2-le dan click derecho y seleccionan **propiedades**
	
	3-en panel izquierdo de la ventana seleccionan **configuración avanzada del sistema**
	
	4- se van hasta la parte de abajo que dice **variables de entorno**<https://ibb.co/X5WCfMq>
	
	5 - seleccionan **añadir**<https://ibb.co/vV9jfNs>
	
	6 - copian el nombre y el valor de la variable, luego , aceptar <https://ibb.co/SXfB96C>
	
	y ya por ultimo guardan todo y reinician su computadora
	
	**nota** : para la ultima variable PLATZI_DB_URI su valor va a ser el siguiente  
	mongodb+srv://tusuario:tupassword@mflix-5zlol.mongodb.net
	
	tal como dijo el amigo que hizo el proceso en mac, y eso es todo, espero le sirva a alguien ya que como siempre hay cosas que varían en los sistemas operativos, saludos

	* **HuguitoRadulovich** (1)

		
		Tengo una consulta, como se sacaria el URI o es igual para todos, la verdad que no lo estoy entendiendo

	* **Carlos Martinez** (1)

		
		@huguitoRadulovich el URI te lo da mongoDB Atlas, prueba con el formato  
		mongodb+srv://tusuario:tupassword@mflix-5zlol.mongodb.net donde OJO “tusuario” y “tupassword” no son los usuario y contraseña para poder entrar en tu cuenta mongodbAtlas si no el usuario y contraseña que pusiste en la parte de “database access” en mongoDB Atlas

* **jorge gonzalez** (5)

	
	Muy incompleto el tutorial la verdad

* **Patricio Pilco** (5)

	
	Falta metodología !!! Se debe mejorar el curso. Llego hasta aquí y no puedo continuar , solo me queda ver los videos. Debe existir garantia para quien no esta conforme.

* **maojedas** (5)

	
	Que confuso todo… demasiadas instalaciones y no se para que sirve cada una. Esto es MongoDB y termino instalando una plataforma de Python? como dijo un compañero, muy poco didactico!

* **Carlos Andres Castañeda Osorio** (5)

	
	Para configurar las variables de entorno en windows a través de CLI se utiliza la palabra reservada SET en lugar de EXPORT, Por ejemplo:
	``` 
	    set FLASK_APP=platzi-api
	    set FLASK_ENV=development
	    seT PLATZI_DB_URI="mongodb+srv://user:pass@cluster01-waouk.mongodb.net"
	    
	```

	* **Brandonkozz** (1)

		
		las variables de entorno las puse como las tienes tu con el “set”, pero tengo un problema que al momento de ejecutar el comando flask run, me dice que
		``` 
		    raise KeyError(key) from None
		    KeyError: 'PLATZI_DB_URI
		    
		```

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		@Brandonkozz revisa que la asignación de la variable PLATZI_DB_URI la estés haciendo con set y no con seT, @ccasta23 tiene un error de digitación y si estas copiando y pegando tal cual por eso es el error.

* **Tazmania** (4)

	
	Concuerdo con la mayoría de los compañeros de este curso esta parte debería ser explicada por vídeo se supone que antes de lanzar un curso debe pasar por un control de calidad y no tener estos tropiezo que son molestos para los estudiantes.

* **Ivan Alexis Carbajal Sandin** (4)

	
	Es cierto, esta parte es muy complicada. De hecho es imposible si no se tiene experiencia utilizando Anaconda, python, línea de comandos, git… Deberían crear un container en docker para poder seguir sin esta experiencia.
	
	RECOMENDACIÓN: Para poder ejecutar todos los comandos en windows de esta clase, despues de que se instala Anaconda, tambien se instala el anaconda prompt (así búsquenlo en sus programas). Con esa terminal puedes hacer prácticamente todo

* **Jose Arturo Enriquez Hurtado** (4)

	
	Para los usuarios de **Windows** las variables de entorno se definen de esta forma de esta forma:
	
	Windows CMD:
	``` 
	    set FLASK_APP=platzi-api
	    set FLASK_ENV=development
	    set PLATZI_DB_URI=“MONGO-URI”
	    
	```
	
	Windows PowerShell:
	``` 
	    $env:FLASK_APP = "platzi-api"
	    $env:FLASK_ENV = "development"
	    $env:PLATZI_DB_URI = "MONGO-URI”
	    
	```

* **Julio Ignacio Oyarzun Cayuman** (4)

	
	Me consto bastante tiempo configurar esto en windows, y eso que llevo años trabajando tanto en linux como en windows. No me puedo imaginar el martirio que debe significar esto para los que recien estan aprendiendo.

	* **Rene Ismael Barrios Rojas** (2)

		
		Si tienes razón pienso que debería haber un vídeo, en mi caso la verdad es que no me gusta gastar o perder mucho tiempo en todo eso de la instalación, entiendo que a veces es un proceso que no se puede omitir, pero precisamente es cuando un curso te ayuda a agilizar ese paso, saludos.

* **Juan Guillermo Perez Cardozo** (4)

	
	poker face los que no saben python, a instalarlo y tambien vscode entre otras dependencias. que pena con ellos mejor el profesor hubiera explicado esto con un video que perezoso y mal por los demas estudiantes.

* **Tlacaelel León Villaseñor** (4)

	
	Hagan un video de esto en windows, o expliquen mas a detalle, no puedo hacer funcionar el proyecto, y como no se nada de Python no puedo seguir el curso en las partes del proyecto.

* **marcoxio** (4)

	
	Alguna razón para este error??  
	![Captura de pantalla 2019-03-31 a la\(s\) 11.53.08 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-03-31%20a%20la%28s%29%2011.53.08%20a.%20m.-ca745965-aa00-42dd-a5ef-af428812ca87.jpg)

	* **makeasy** (0)

		
		Tengo el mismo error

	* **Miguel Peláez** (1)

		
		Alguna solución?

	* **makeasy** (1)

		
		si tambien tengo el mismo problema :’(

	* **Abraham Gonzalez** (1)

		
		Yo lo pude solventar … en mi variables de entorno y es la manera en que te conectas. Mongodb Atlas te da una sección de conexión con Phyton algo confusa, yo copie solo la uri por defecto y descargar una dependencia que necesitaba …
		``` 
		    export PLATZI_DB_URI=mongodb+srv://platzi-admin:<myPass>@curso-platzi-umrp8.mongodb.net
		    
		```
		
		Luego instale la dependencia [dnspython 1.16.0](https://pypi.org/project/dnspython/)
		
		Espero haberle sido de utilidad …

	* **Brayan Mamani** (1)

		
		Bueno, con el comentario anterior se soluciona.

* **Joseph Santibáñez** (3)

	
	No se entiende esta parte!!! se está mezclando muchos conceptos apartes y perdí el foco. Se puede continuar el curso si no logré esto???
	
	`(platzi-mongo) [root@OEL704-MongoDB platzi-mongo]# pip  
	-bash: pip: command not found  
	(platzi-mongo) [root@OEL704-MongoDB platzi-mongo]# conda deactivate  
	(base) [root@OEL704-MongoDB platzi-mongo]# pip
	
	Usage:  
	pip <command> [options]`
	
	No me reconoce el comando pip cuando estoy con conda activado!

* **Eduardo Rodriguez Yapur** (3)

	
	Muy poco didáctico la forma en que se explica esta sección. Creo que faltan explicar mucho conceptos. Espere se mejore pronto para que sea mas comprensible.

* **ERNESTO ORTIZ** (3)

	
	Hola, andaba perdido, igual que varios que veo por aqui, les recomiendo <https://www.youtube.com/watch?v=YYXdXT2l-Gg>  
	así como <https://www.youtube.com/watch?v=APOPm01BVrk;> si no saben de Python como yo. Saludos.

	* **xmedinavei** (1)

		
		Este comentario es la solución!

	* **xmedinavei** (1)

		
		Algún video para exportar las variables de entorno?

* **Edwin_Salinas_Parra** (3)

	
	por favor si alguien pudiese explicar una mejor forma de poder hacer este proceso, que en realidad no son claros.  
	gracias

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Hola, qué sistema operativo usas, estas usando conda?

	* **Edwin_Salinas_Parra** (1)

		
		Windows 10

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Ok, entonces estas usando conda?

	* **Edwin_Salinas_Parra** (1)

		
		ese es presisamente el problemo no lo he podido utilizar no he padado de esta instalacion

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Qué error te sale al intentar instalar, o qué problema tienes exactamente al instalar conda.

	* **Edwin_Salinas_Parra** (1)

		
		ya lo instale pero no se en que parte ejecutar los comandos que estan indicando hay

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Los comandos se deben ejecutar en la consola dentro del entorno virtual creado por conda, como usas windows usa la shell de linux para poder trabajar mejor.

	* **Edwin_Salinas_Parra** (1)

		
		pero como lo ejecuto no me permite ejecutarlo  
		bueno o no lo encuentro

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Comparte una captura de pantalla de lo que has intentado, es más sencillo guiarte de esa forma.

	* **Edwin_Salinas_Parra** (1)
![error mongoDB.jpg](https://static.platzi.com/media/user_upload/error%20mongoDB-10e2e519-8402-4b9a-9c08-c41a002bf8f2.jpg)

	* **Edwin_Salinas_Parra** (1)

		
		ese fue el unico que me dejo crear e iniciar con conda pero ya hacer el otro proceso ya no
		
		no se si fue que quedo mal unstalado o que pero no me deja
		
		a demas de que me aparece anaconda powershell prompt 2 y 3  
		es muy confuso

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Hola. Como estas usando conda debes correr los comandos de conda para instalar aquí tienes la documentación de como se instalan paquetes <https://docs.continuum.io/anaconda/user-guide/tasks/install-packages/>. Para instalar usando el archivo requirements.txt debes usar el siguiente comando  
		`conda install --file requirements.txt`

	* **Edwin_Salinas_Parra** (1)
![nuevo error mongoDB.jpg](https://static.platzi.com/media/user_upload/nuevo%20error%20mongoDB-b9d562b6-ae85-4bd9-9ccf-0756f077f423.jpg)

	* **Edwin_Salinas_Parra** (1)

		
		nuevo error!!!..

	* **Edwin_Salinas_Parra** (1)
![paso no entiendo.jpg](https://static.platzi.com/media/user_upload/paso%20no%20entiendo-600f502c-9d55-41c9-9e22-ccdcad04c679.jpg)

	* **Edwin_Salinas_Parra** (1)

		
		ya instale lo otro, ahora esta parte en donde se ejecuta???

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		En windows las variables de entorno se setean diferente, esta documentación te puede ayudar <https://docs.microsoft.com/en-us/windows/win32/procthread/environment-variables>, yo te recomiendo que instales una maquina virtual con ubuntu o cualquier distribución de linux y va a ser tu vida más fácil. En lo personal Windows no me parece la mejor plataforma para desarrollar cosas que no tengan que ver con el ecosistema de Microsoft.

* **Fernando Torres** (2)

	
	Ojo, si tuviste error o algo no funcionó, te sugiero leas con calma todos los comentarios de la comunidad aquí debajo. Lee todos sin aplicar ninguna solución. Una vez hecho esto, podrás decidir cuál aplica a tu caso.
	
	En mi caso, hasta que no reinicie mi terminal, pude ejecutar
	``` 
	    conda list
	    
	```
	
	Mira el comentario de AryRosvall para un tutorial al respecto.
	
	Después, estaba haciendo mal un export. Debe utilizarse sin comillas.  
	Y al final, obtendrás un error 404 al consultar la dirección, ya que no hay frontend para la URL. Prueba por ejemplo con:  
	<http://127.0.0.1:5000/carreras/test>

* **David Flores** (2)

	
	Para crear un entorno virtual con python 3.3+ lo haces de la siguiente manera:
	``` 
	    conda create--name my-env python=3
	    
	```
	
	Para activarlo :
	``` 
	    conda activatemy-env
	    
	```

* **AryRosvall** (2)

	
	Hola, después de mucho batallar encontré este tutorial para instalar anaconda desde la terminal en MacOS porque por el instalador dio problemas:
	
	<https://towardsdatascience.com/how-to-successfully-install-anaconda-on-a-mac-and-actually-get-it-to-work-53ce18025f97>

* **avilchez** (2)

	
	Hola buen día, un favor, me pudieran orientar en el último paso de como exportar las variables, donde se realiza ese paso. Gracias

* **jorge gonzalez** (2)

	
	Hice todos los pasos y cuando voy al enlace 127.0.0.1:5000 me sale error 404  
	![error404.png](https://static.platzi.com/media/user_upload/error404-c28d1cf8-ea96-429a-a058-0ab24d362bd7.jpg)

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Prueba poniendo `/` al final

	* **jorge gonzalez** (1)

		
		no funcionó

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Puedes compartir tu código para ver si hay algún error de digitación que haga que este esperando un path en la url

	* **Franco Emanuel Aban Tejerina** (1)

		
		qué te muestra la consola luego de ejecutar el comando: **flask run**

	* **jbarriospd** (1)

		
		Estoy en mismo punto del compañero, despues de ejecutar flask run aparece:  
		Serving Flask app “platzi-api”
		
		  * Environment: production  
		WARNING: Do not use the development server in a production environment.  
		Use a production WSGI server instead.
		  * Debug mode: off
		  * Running on <http://127.0.0.1:5000/> (Press CTRL+C to quit)  
		127.0.0.1 - - [14/Mar/2020 23:35:15] “GET / HTTP/1.1” 404 -
		
		
		
		(No he realizado modificacion al reppositorio estoy en la rama master del proyecto)
		
		Agradezco la ayuda:)

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		@jbarriospd puedes compartir tu archivo .py para verificar que todo este ok.

	* **AryRosvall** (1)

		
		a mi me está pasando lo mismo, me marca error 404

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		@AryRosvall comparte tu código por favor para poder ayudarte.

	* **Fernando Torres** (1)

		
		Es normal. No hay frontend; es una API. Prueba con <http://127.0.0.1:5000/carreras/test>

* **Vicente Fernandez** (2)

	
	Se me hace imposible esto, NO tengo conocimientos de Postman, GitHub, Anaconda o Python.

* **ehnbytes** (2)

	
	No puedo hacer correr el proyecto.
	
	> flask run
	
	  * Environment: production  
	WARNING: Do not use the development server in a production environment.  
	Use a production WSGI server instead.
	  * Debug mode: off  
	Usage: flask run [OPTIONS]
	
	
	
	Error: Could not locate a Flask application. You did not provide the “FLASK_APP” environment variable, and a “[wsgi.py](http://wsgi.py)” or “[app.py](http://app.py)” module was not found in the current directory.
	
	> 

	* **Cristian David Franco Garcia** (2)

		
		Ejecuta estos comandos segun tu sistema operativo desde la misma consola donde se ejecutara Flask run:
		
		Unix:  
		export FLASK_APP=platzi-api  
		export FLASK_ENV=development  
		export PLATZI_DB_URI=“MONGO-URI”
		
		Windows:  
		SET FLASK_APP=platzi-api  
		SET FLASK_ENV=development  
		SET PLATZI_DB_URI=“MONGO-URI”

* **renevillegasr** (2)

	
	No logro correr la api, el hacerlo con:
	``` 
	    flask run
	    
	```
	
	Obtengo el error de que la carpeta platzi-api no existe:
	``` 
	    Usage: flask run [OPTIONS]
	    
	    Error: The file/path provided (platzi-api) doesnot appear to exist.  Please verify the path is correct.  If app isnoton PYTHONPATH, ensure the extension is .py
	    
	```
	
	Alguien ha logrado saltar este obstáculo?
	
	OS: Linux Ubuntu 18.10  
	Python: 2.7
	
	Logré instalar Anaconda2 y Postman sin problema.
	
	Gracias anticipadas por el apoyo.
	
	Saludos

	* **Franco Emanuel Aban Tejerina** (1)

		
		verifica que estés dentro del directorio **platzi-mongo** antes de ejecutar el comando el comando y que tu usuario tenga los permisos necesarios

	* **José Roberto Diaz Rodriguez** (1)

		
		Prueba con correr el siguiente comando:  
		**python -m flask run**  
		A mi me funciono con esto.

* **Edwin_Salinas_Parra** (2)

	
	deberian subie un video aparte explicando esta parte, para los que estamos tan perdidos.  
	o que curso tenemos que ver antes para no quedar tan perdidos.

	* **Victor Inojosa** (1)

		
		El curso de Python y luego el de Flask te servirian

	* **Edwin_Salinas_Parra** (1)

		
		gracias voy a intentarlo

	* **Brayan Mamani** (1)

		
		Bueno, si funciona.

* **eliseojoel12** (2)

	
	Rayos batman! instale anaconda satisfactoriamente y quise ejecutar el comando y no reconoce el “conda”.  
	alguien tenia el mismo problema?  
	![](https://ibb.co/hZ13hTD)

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Asegúrate que el ejecutable de conda este guardado en las variables de entorno, si tenias la terminal abierta cierrala y vuelves a abrir la terminal para que tome los cambios.

	* **Joan Federico Marin Ruiz** (1)

		
		desde donde quedo instalado anaconda?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		@Fede01 qué sistema operativo usas? para ayudarte a encontrar el path de instalación, no es lo mismo para todos los sistemas operativos.

	* **Joan Federico Marin Ruiz** (1)

		
		tengo que agregar el Path C:\Program Files\MongoDB\Server\4.2\bin  
		a variables de entorno de windows?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		@Fede01 esto agrega solo mongo, tu problema es con conda como tal, puedes compartir captura de pantalla del error en la consola.

	* **Joan Federico Marin Ruiz** (1)
![error.png](https://static.platzi.com/media/user_upload/error-0865de38-e511-4c83-b04c-a26fcfcf2710.jpg)

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		@Fede01 estas tratando de buscar el ejecutable de conda en la carpeta de mongo, nunca lo va a encontrar, debes ejecutar conda en la carpeta donde se instalo conda.

* **Fabián Antonio Alvarado Picado** (2)

	
	Me encanta la forma en que éste profe explica, él es pausado y con detalle.
	
	Otro dato a favor es usar ramas de Git 😊

* **Jaiden Meiden** (1)

	
	![](![Captura de pantalla de 2020-03-23 21-47-46.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20de%202020-03-23%2021-47-46-11a89523-c320-4b29-8e36-3b99bd4ce140.jpg)
	
	Alguien sabe que hacer aquí? Es la versión de Python? Es anaconda? Lo configure mal? Es porque estoy utilizando ZSH?

* **Jaiden Meiden** (1)

	
	Para los que tienen Python 3, pueden mirar este tutorial:
	
	<https://platzi.com/tutoriales/1378-python-practico/3077-crear-ambiente-virtual-con-virtualenv/>

* **Jaiden Meiden** (1)

	
	Si se les presenta el siguiente error (Si tienen Python 2):
	``` 
	    CommandNotFoundError: Your shell has not been properly configured to use 'conda activate'.
	    To initialize your shell, run
	    
	        $ conda init <SHELL_NAME>
	    
	    Currently supported shells are:
	      - bash
	      - fish
	      - tcsh
	      - xonsh
	      - zsh
	      - powershell
	    
	    See 'conda init --help'for more information and options.
	    
	    IMPORTANT: You may need tocloseand restart your shellafter running 'conda init'.
	    
	```
	
	Instalen zsh y ejecuten:
	``` 
	    conda init zsh
	    
	```
	
	y reinicien

* **joeldm011** (1)

	
	a que se debe este error? 😦
	``` 
	    (platzi-mongo) PS C:\Cursos\platzi-mongo> pip install -r requirements.txt
	    pip : El término 'pip' nose reconoce como nombre de un cmdlet, función, archivo de script o programa ejecutable.
	    Compruebe si escribió correctamente el nombre o, si incluyó una ruta de acceso, compruebe que dicha ruta es correcta e
	    inténtelo de nuevo.
	    Enlínea: 1 Carácter: 1
	    + pip install -r requirements.txt
	    + ~~~
	        + CategoryInfo          : ObjectNotFound: (pip:String) [], CommandNotFoundException
	        + FullyQualifiedErrorId : CommandNotFoundException
	    
	```

	* **AryRosvall** (1)

		
		si tienes python3 intenta con pip3 a mi me pasó lo mismo.

* **jlcoronel** (1)

	
	Iba todo bien, con un poco de leer y leer hasta comprender lo que quierian hacer, ya que no está muy bien explicado y ademas las versiones no coinciden hoy en día.
	
	Al final me manda el siguiente error:
	``` 
	    pymongo.errors.InvalidURI
	    pymongo.errors.InvalidURI: Invalid URI scheme: URI must beginwith'mongodb://'or'mongodb+srv://
	    '```
	    
	    Ya establecí las variabes en windows.
	    
	    Uso windows 8.1 python 3.8.2
	    
	    EStoy un poco cansado, continuaré en la mañana.
	```

	* **jlcoronel** (1)

		
		Lo volví ejecutar hoy en la mañana pero sin poner las comillas dobles antes y alfinal del string de conección y funcionó.
		``` 
		    SET PLATZI_DB_URI=mongodb+srv://usuario:contraseña@curso-platzi-eu1qo.mongodb.net
		    
		```

* **Adrian Carvajal** (1)

	
	Hola, me queda faltando el paso final, estoy usando windows
	
	(platzi-mongo) C:\Users\ADRIAN\Documents\GitHub\platzi-mongo>set FLASK_APP=platzi-api
	
	(platzi-mongo) C:\Users\ADRIAN\Documents\GitHub\platzi-mongo>set FLASK_ENV=development
	
	(platzi-mongo) C:\Users\ADRIAN\Documents\GitHub\platzi-mongo>set PLATZI_DB_URI=mongodb+srv://(aca estoy usando mi usuario):(aca estoy usando mi password)@cluster0-qapf6.gcp.mongodb.net
	
	(platzi-mongo) C:\Users\ADRIAN\Documents\GitHub\platzi-mongo>flask run
	
	  * Serving Flask app “platzi-api” (lazy loading)
	  * Environment: development
	  * Debug mode: on
	  * Restarting with windowsapi reloader
	  * Debugger is active!
	  * Debugger PIN: 205-680-132
	  * Running on <http://127.0.0.1:5000/> (Press CTRL+C to quit)  
	127.0.0.1 - - [17/Mar/2020 19:04:56] “GET / HTTP/1.1” 404 -  
	127.0.0.1 - - [17/Mar/2020 19:04:56] “GET /favicon.ico HTTP/1.1” 404 -
	
	
	
	Pero al abrir <http://127.0.0.1:5000> sale 404 not found

* **GersonPc** (1)

	
	Me sale este error y no se como solucionarlo
	``` 
	    Error: The file/path provided (platzi-api) doesnot appear to exist.  Please verify the path is correct.  If app isnoton PYTHONPATH, ensure the extension is .py
	    
	```

* **Gerardo Nava Pereda** (1)

	```
	    export PLATZI_DB_URI="mongodb+srv://<user>:<password>@<tu-mongodb-atlas-name>.mongodb.net"
	    
	```

	* **AryRosvall** (1)

		
		Sin las comillas.

* **Cristian David Franco Garcia** (1)

	
	Si estan trabajando desde windows busquen y usen esta terminal: Anaconda Prompt (Anaconda 3), desde aqui ejecuten todos los comandos y funcionara.

* **DiegoADaza** (1)

	
	Este pedazo debería tener vídeo para hacer el paso a paso correctamente

* **nick** (1)

	
	Todo listo

* **ejgachancipa** (1)

	
	Hola, tengo este error:
	``` 
	    ModuleNotFoundError
	    ModuleNotFoundError: No module named 'bson'
	    
	```

	* **AryRosvall** (1)

		
		hola, lo que hice fue
		``` 
		    pip install bson
		    
		```
		
		y con eso me funcionó

* **Joan Federico Marin Ruiz** (1)

	
	igual como todos se han quejado, muy mala explicacion esta parte.  
	navego en la consola de windows hasta donde guarde el proyecto mongo-platzi-master, y no me reconoce el comando “conda”…alguna ayuda porfa…

	* **Franco Emanuel Aban Tejerina** (2)

		
		Prueba utilizar las aplicaciones de consola que se instalan junto con **Anaconda** , es lo que yo hice  
		![anaconda.png](https://static.platzi.com/media/user_upload/anaconda-0acc0d97-587e-42a6-9703-d06ba9df286e.jpg)
		
		si

* **sebastianaceved** (1)

	
	como creo las variables de entorno necesarias para ejecutar el proyecto esto hay que hacerlo en la consola en el caso de linux? , no entiendo

* **dbzdavidbaez** (1)

	
	Podría detallarse mucho más la impelmntacion de este ambiente. Sé que hay que tener conocimiento en otros lenguajes, pero estamos estudiando el tema de bases de datos MongoDb y no Desarrollo.

* **manuel-mendoza142** (1)

	
	mongodb+srv://platzi-admin:*********************@clase-platzi-syws2.mongodb.net
	
	No existe el archivo o el directorio
	
	ayuda porque me sale este error???

* **Edwin_Salinas_Parra** (1)
![error mongoDB.jpg](https://static.platzi.com/media/user_upload/error%20mongoDB-e4462868-2bbc-4a42-a09d-4d4754016adb.jpg)
	
	hasta hay llego despues de muchisimos intentos

	* **Franco Emanuel Aban Tejerina** (1)

		
		Prueba ejecutando desde el **prompt** que se instala cuando instalas **Anaconda** y si tienes problemas de permisos ejecuta el Prompt como **administrados**

* **JaimeRamos** (1)

	
	flask.cli.NoAppException  
	flask.cli.NoAppException: Could not import “platzi_api”.  
	alguien sabe por qué ocurre este error?

* **zarza-raul** (1)

	
	Hola jovenes, alguien le da este problema ? como lo arreglaron. Saludos![](![Captura de pantalla de 2019-08-08 10-58-22.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20de%202019-08-08%2010-58-22-960766cb-c7e8-4e9c-ba9f-be251df1ed23.jpg)builtins.ModuleNotFoundError
	
	ModuleNotFoundError: No module named ‘bson’

	* **Eduardo Imery Winterdaal** (1)

		
		Hola Raul, lograste solucionar el problema?  
		si no prueba borrando la libreria de BSON y pymongo con pip y luego vuelves a instalar pymongo, espero te pueda resolver, saludos

* **Grupo OET** (1)

	
	Buenas tardes, tengo una inquietud:  
	Ya he logrado instalar Anaconda, e incluso he instalado las dependencias del proyecto, así como definir las variables de entorno, con base en las indicaciones dadas por el profesor. Sin embargo, cuando ejecuto la instrucción “ **flask run** ”, de inmediato saca este mensaje:
	
	_Error: The file/path provided (platzi-api) does not appear to exist. Please verify the path is correct. If app is not on PYTHONPATH, ensure the extension is .py_
	
	Por favor, alguien que nos oriente para que la instrucción funcione satisfactoriamente, y así ejecutar el servidor de desarrollo. Muchas Gracias

* **Fernando Eladio Alvarez Noya** (1)

	
	Me funciono y todo!!! Aclaro que estoy en un mac, cosa que a veces suele complicarse! 😉

* **Wilson_Revan** (1)

	
	No comprendo como realizar correctamente el ultimo paso “exportar las variables de entorno”. Espero alguien me pueda explicar como se debe realizar. Desde GIT bash ejecute los comandos export y construí la URI con el comando export tal y como indica pero al entrar al dirección especificada no me ejecuta nada dice “127.0.0.1 rechazó la conexión.”

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Hola. veo que usas windows, entonces desde el cmd o power shell usas estos comandos
		``` 
		    set FLASK_APP=platzi-api
		    set FLASK_ENV=development
		    set PLATZI_DB_URI="mongodb+srv://user:pass@cluster01-waouk.mongodb.net"
		    
		```
		
		Es cambiar export por set

	* **Wilson_Revan** (1)

		
		Hola diego , una ultima pregunta el que quiere decir con “Cuando tengas todas las variables de entorno ejecuta:  
		flask run” en cmd ejecuto este comando a traves del git bash o es algún archivo? . Agradezco tu ayuda.

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Lo ejecutas en git bash.

	* **ricardo-tierra** (1)

		
		Yo estoy en linux y al momento de ingresar mis datos en este paso  
		// export PLATZI_DB_URI=“MONGO-URI”
		
		me sale  
		bash: !ErBtb: event not found
		
		no se si alguien sepa como correguirlo

* **hugohr1** (1)

	
	Para las personas que tienen este error
	
	![error1.PNG](https://static.platzi.com/media/user_upload/error1-985d31b5-68e3-4e3b-afa6-3cf0a89e0d07.jpg)
	
	basta con ir al archivo  
	Platzi-api/db.py  
	y remover las tildes de la linea 7

* **Luis Donaldo Lopez Gil** (1)

	
	Unas decadas despues jaja por fin!

* **Brandonkozz** (1)

	
	Hola, tengo una duda cuando ejecuto el comando “flask run” me suelta varias direcciones pero al final me saca este error:
	``` 
	    raise KeyError(key) fromNone
	    KeyError: ‘PLATZI_DB_URI’
	    
	    
	```
	
	he revisado por todo lado y no encuentro cual es el problema, estoy en windows 10, realice todo como esta en la guía, lo unico que cambie, fueron las variables de entorno que en vez de poner “export” puse “set”, la cadena de conexión la tengo bien, el pip install, también instalo perfectamnete cuando le cambie el certifi==2019.3.9 ya que tenia error con el que venia, pero el problema erradica como tal en el
	``` 
	    flask run
	    
	```
	
	, agradecería mucho que alguien pudiese ayudarme con este problema. gracias

* **favioh** (1)

	
	Hola, estoy siguiendo tu curso y me parece interesante usar bases de datos no relacionales pero tengo una duda, supongo que es algo tonta. Todos los pasos que realizas en ésta parte también se realizan en Windows? pude clonar el repositorio, instalé postman, importé el proyecto pero no sé si deba instalar anaconda e instalar dependencias.

	* **favioh** (1)

		
		😦

* **Ivan Alexis Carbajal Sandin** (1)

	
	No me permitía instalar las dependencias del proyecto después de crear el entorno virtual, ya que no reconocía el comando PIP.
	
	Lo solucioné instalando python en el entorno creado y borrando el certifi del listado de requerimientos

	* **HuguitoRadulovich** (1)

		
		Hola tengo este problema también, me dice que no me reconoce el comando PIP

	* **zarza-raul** (1)

		
		tienes que instalar pip desde la consola
		``` 
		    sudo apt install python-pip```
		    
		```

* **Enrique Alexis Lopez Araujo** (1)

	
	Estoy tratando de correo un contenedor con lo ya aprendido, mi dockerfile es el siguiente.
	``` 
	    FROM python:3.6
	    
	    ENV FLASK_APP platzi-api  
	    ENV PLATZI_DB_URI mongodb+srv://alexis-curso:wCvRPOgNla0UsnWl@alexis-curso-mongodb-wirbu.mongodb.net 
	    ENV FLASK_ENV development
	    
	    WORKDIR/usr/src/app
	    
	    COPY./requirements.txt /usr/src/app
	    
	    RUNpip install -r requirements.txt
	    
	    ADDplatzi-api/. /usr/src/app
	    
	    CMD[ "flask", "run", "--host=0.0.0.0" ]
	    
	    EXPOSE5000
	    
	```
	
	Pero al momento de correr la app me aparece el siguiente error, no entiendo que mas puede faltar?
	
	![https://i.imgur.com/yWn2JN1.png](https://i.imgur.com/yWn2JN1.png)
	
	En mi local si funciona correctamente pero estoy tratando de hacerlo en docker para poder subirlo a cualquier servicio que utilice docker.
	
	Saludos!

	* **Enrique Alexis Lopez Araujo** (6)

		
		He corregido el dockerfile y revise cual era el problema no estaba ejecutando correctamente los CMD en las carpetas correctas hice los cambios correctos en el dockerfile y quedo asi
		``` 
		    FROM python:3.6
		    
		    ENV FLASK_APP platzi-api  
		    ENV PLATZI_DB_URI mongodb+srv://alexis-curso:wCvRPOgNla0UsnWl@alexis-curso-mongodb-wirbu.mongodb.net 
		    ENV FLASK_ENV development
		    
		    WORKDIR/usr/src/platzi-api
		    
		    COPY./requirements.txt /usr/src/platzi-api
		    
		    RUNpip install -r requirements.txt
		    
		    ADD/platzi-api/ /usr/src/platzi-api
		    
		    WORKDIR/usr/src/
		    
		    CMD["flask", "run", "--host=0.0.0.0" ]
		    
		```

	* **albertramirez** (1)

		
		¡Muy buen aporte!

* **Andrea Bocanegra** (1)

	
	En mi caso cuando instalé anaconda, lo active y desactivé de la siguiente manera:
	``` 
	    # To activate this environment, use:
	    # > source activate platzi-mongo
	    #
	    # To deactivate an active environment, use:
	    # > source deactivate```
	```

* **Enrique Alexis Lopez Araujo** (1)

	
	Por que se instalo anaconda, no conozco para nada esa libreria, y si alguien pudiera explicar un poco para que funciona o cual es su utilidad dentro del curso?

	* **albertramirez** (5)

		
		Anaconda no es una librería, es una distribución de python. Esta nos permite instalar python y administrar los paquetes. Se usa en el curso como una forma sencilla de instalar python y las librerias necesarias para el proyecto, si ya tienes instalado python 3.3.+ en tu sistema no es necesario que instales anaconda, puedes instalar las dependencias usando pip dentro de un ambiente virtual activo como venv.

* **Enrique Alexis Lopez Araujo** (1)

	
	Hola comunidad tengo una pregunta:
	
	  * Cada que cierro la terminal las variables no se quedan seteadas o guardadas como puedo guardar las variables en o manejar las variables en un archivo para que pueda correr la app en cualquier momento sin que tenga que volver a setear las variables?.
	
	
	
	Saludos!

	* **albertramirez** (4)

		
		Si estás en MacOs puedes hacer eso  
		<https://medium.com/@himanshuagarwal1395/setting-up-environment-variables-in-macos-sierra-f5978369b255>
		
		Básicamente es agregar la variable en tu archivo .bash_profile
		
		En Linux sería en tu archivo .bashrc

* **Enrique Alexis Lopez Araujo** (1)
Estoy tratando de correo un contenedor con lo ya aprendido, mi dockerfile es el siguiente. FROM python:3.6 ENV FLASK_APP platzi-ap...

	* **Enrique Alexis Lopez Araujo** (6)

		
		He corregido el dockerfile y revise cual era el problema no estaba ejecutando correctamente los CMD en las carpetas correctas hice los cambios correctos en el dockerfile y quedo asi
		``` 
		    FROM python:3.6
		    
		    ENV FLASK_APP platzi-api  
		    ENV PLATZI_DB_URI mongodb+srv://alexis-curso:wCvRPOgNla0UsnWl@alexis-curso-mongodb-wirbu.mongodb.net 
		    ENV FLASK_ENV development
		    
		    WORKDIR/usr/src/platzi-api
		    
		    COPY./requirements.txt /usr/src/platzi-api
		    
		    RUNpip install -r requirements.txt
		    
		    ADD/platzi-api/ /usr/src/platzi-api
		    
		    WORKDIR/usr/src/
		    
		    CMD["flask", "run", "--host=0.0.0.0" ]
		    
		```

## 0130. Trabajando en nuestro proyecto PlatziMongo Operaciones CRUD con Python y pymongo

### Descripción:


### Links:

* [https://www.getpostman.com/collections/ffcbfb5c8d5cd2dc52d2](https://www.getpostman.com/collections/ffcbfb5c8d5cd2dc52d2)

* [GitHub - AERC18/platzi-mongo: En este repositorio se encuentra el código del proyecto platzi-mongo.](https://github.com/AERC18/platzi-mongo)

### Comentarios:

* **Yesid Alejandro Peláez Posada** (10)

	
	Hasta aquí llegué. No pude con la configuración anterior además no sé como inició acá con un proyecto ya listo.

* **Javier Serrano Lule** (7)

	
	La información de la configuración para el proyecto en Windows está demasiado básica para si vienen de cero como yo llegué, en cualquier caso, les dejo enlaces donde después de mucho pude configurar y en apoyo con la explicacion anterior:
	
	  * Para usar el comando _**conda**_ hay que agregarla en el PATH para poder usarlo, el directorio a agregar si se instaló por defecto es: C:\Users\NOMBRE_USER\Anaconda3\condabin
	
	  * Descargas Python en Windows y permite agregar a PATH para poder usar el comando “pip”.  
	**_https://tutorial.recursospython.com/descarga-e-instalacion/ _**
	
	  * Si no alcanzan a ver el comando para configurar el proyectom como yo, es: **_pip install -r requirements.txt_**
	
	  * Si les da un error igual a este: _**pymongo.errors.ConfigurationError: None of DNS query names exist**_ la URI de conexión a Mongo está mal escrita, para encontrarla de manera segura pueden ir a su cluster ( _<https://cloud.mongodb.com>_ ) y en CONNECT seleccionen la segunda opción (Connect Your Application) y les arrojará la cadena de conexión, solo hay que reemplazar la contraseña y la BD a la que se conectará. En mi caso algo similar a esto:  
	mongodb+srv://platzi:PASSWORD@curso-platzi-i0uq0.mongodb.net/BD?retryWrites=true
	
	  * Si persiste el error al colocar la URI en el PATH, puede ser reemplazada directamente en el archivo _**[db.py](http://db.py)**_ en la parte donde se crea el cliente.
	
	
	
	
	Cualquier detalle, con confianza pueden preguntarme 😄

	* **Brayan Mamani** (1)

		
		Fue de gran utilidad.

* **michaelsaritamacoronel** (7)

	
	Me choque con esta clase…no se nada de Python 😕

	* **Wilson Marino Pablo Mendez** (1)

		
		X2

	* **Brayan Mamani** (1)

		
		X3

* **cirovladimir** (7)

	
	* _no te preocupes mucho_ en implementar estos métodos o **si no entiendes por completo el código** , recuerda que aquí están utilizando el driver de python pero bien pudieras utilizar otro en el **lenguaje que más cómodo sea para ti** (C, C++11, C#, Go, Java, Node.js, Perl, PHP, Python, Motor (Python async), Ruby, Mongoid (Ruby ODM), Scala) 🤪
	
	**recuerda que este curso es sobre mongodb**
	
	p.d. desconozco python y me dió error el código por querer devolver el objeto (documento) completo en el método `crear_carrera`, en vez de sólo el id insertado
	``` 
	    return db.carreras.insert_one(json)
	    
	```
	
	en vez de
	``` 
	    return str(db.carreras.insert_one(json).inserted_id)
	    
	```

* **Antonio Meza** (7)

	
	En Windows no es Export, es SET, es decir:
	
	export FLASK_APP=platzi-api  
	export FLASK_ENV=development  
	export PLATZI_DB_URI=“MONGO-URI”
	
	por
	
	set FLASK_APP=platzi-api  
	set FLASK_ENV=development  
	set PLATZI_DB_URI=mongodb+srv://TuUsuario:TuPassword@TuServidor
	
	Nota: Sin “” (comillas) , ni <>

	* **Miguel Ángel Muñoz Pozos** (1)

		
		Genial bro gracias

* **Carlos Martinez** (5)

	
	yo tenía el siguiente error al momento de hacer operaciones con postman:  
	**pymongo.errors.ConfigurationError: None of DNS query names exist:**
	
	lo solucioné cambiando un poquito la función get_db() que está en el archivo [db.py](http://db.py)
	
	y quedo asi la cosa
	``` 
	    defget_db():
	        #platzi_db = current_app.config['PLATZI_DB_URI']
	        client = MongoClient('mongodb+srv://tuUsuario:tuContraseña@curso-de-platzi-ydbgb.mongodb.net')
	        return client.platzi
	    
	```
	
	cambian ‘curso-de-platzi’ por como le hayan puesto en su cluster

	* **favioh** (1)

		
		Muchas gracias, me sirvió 😄

	* **neontigermx** (1)

		
		Me sirvio! Gracias! 😃

* **santmont** (5)

	
	no puedo insertar registros en Postman me aparece el siguiente erro “500 INTERNAL SERVER ERROR”.  
	**Nota:** al ejecutar flask run e ir a la dirección <http://127.0.0.1:5000/> aparece “Not Found”

	* **ruthazuniga** (1)

		
		Me pasó lo mismo

	* **Andrea Bocanegra** (2)

		
		Hola. Coloca <http://127.0.0.1:5000/carreras>

	* **miguelalejandrodemoraiz** (1)

		
		A mi tambien me paso lo mismo y no le veo solucion, no puedo continuar con el curso.

	* **Luis Donaldo Lopez Gil** (1)

		
		andreax_boca x2  
		<http://127.0.0.1:5000/carreras>

	* **Brayan Mamani** (1)

		
		Tube la misma complicación.

* **memowii** (5)

	
	Al momento de realizar la primera petición, crear carrera, en postman, me arrojó el siguiente error:
	
	pymongo.errors.OperationFailure: user is not allowed to do action [insert] on // Werkzeug Debugger
	
	Una solución, que me funcionó, fue cambiar la variable PLATZI_DB_URI de:
	``` 
	    export PLATZI_DB_URI="mongodb+srv://curso-platzi-fzkkm.mongodb.net"
	    
	```
	
	a
	``` 
	    export PLATZI_DB_URI="mongodb+srv://<user>:<password>@curso-platzi-fzkkm.mongodb.net"
	    
	```
	
	Obviamente cambiando los valores <user>, <password> y [curso-platzi-fzkkm.mongodb.net](http://curso-platzi-fzkkm.mongodb.net), por los que ustedes crearon respectivamente.

	* **memowii** (2)

		
		Para mayor información pueden checar:  
		<https://github.com/MongoEngine/mongoengine/issues/1829>
		
		<https://docs.mongodb.com/manual/reference/connection-string/#connection-string-formats>

	* **Carlos Martinez** (1)

		
		gracias, tu solución me funcionó

	* **Brayan Mamani** (1)

		
		Funciona, genial.

* **Juan Andres Ageitos Lopez** (4)

	
	Hola, no logro correr el flask run. Tendrian que agregar una clase en video de estas configuraciones, para gente que no trabaja con Python no es trivial lo que esta en el documento anterior.

	* **juand_silva** (1)

		
		Comparte todo el trace que da la consola y como creas las variables de entorno si es windows o un sistema .NIX

	* **ERNESTO ORTIZ** (2)

		
		Hola te recomiendo este canal <https://www.youtube.com/watch?v=APOPm01BVrk>

	* **Marco Antonio Macedo Preciado** (1)

		
		Dale una checada al curso de Flask. En el primer módulo se explica muy bien a detalle.

* **Claudio Jesus Vázquez Villanueva** (4)

	
	ModuleNotFoundError: No module named ‘bson’ alguien sabe a que se debe esto?

	* **Fernando Sebastian Sanchez** (1)

		
		pudiste resolverlo me esta pasando lo mismo 😦

	* **zarza-raul** (1)

		
		ya volvi a instalar anaconda per sigue sin funcionar … alguna otra solucion?

	* **Claudio Jesus Vázquez Villanueva** (1)

		
		Yo nunca instale anaconda. Solo descargue python, creo el error era en el path

	* **Brayan Mamani** (1)

		
		Igual en Linux, especialmente en Ubuntu.

	* **AryRosvall** (1)

		
		para arreglarlo yo hice
		``` 
		    pip install bson
		    
		```

* **Freddy Rojas Valera** (4)

	
	solo queria comentar que me pareció un poco difícil el hacer la conexión con el servidor me sigue dando error, tanto así que continúe simplemente luego de todo el proceso aun me da un error y no puedo conectar y perdí mucho tiempo , tal vez sea por que no conozco python.

	* **Claudio Jesus Vázquez Villanueva** (0)

		
		Que tal aveces los errores aparecen porque no integras las variables de entorno cuando instalas anaconda es muy importante dar check a agregar a PATH

* **Abraham Gonzalez** (3)

	
	Es importante recalcar que el PostMan ya viene con una colección de las rutas y los objetos a actualizar (Update). Pero nosotros debemos cambiar el _id por el que autogenero nuestra base de datos. Así que pendiente al momento de Actualizar Carreras copien el id de la carrera de SU base de datos en el body (Objeto).

	* **Alberto Campos Hernandez** (1)

		
		Gracias por el dato! tenía ese problema.

	* **juand_silva** (1)

		
		hahaha, yo viendo tutoriales de postman y mandando cabeceras un buen rato.

	* **Brayan Mamani** (1)

		
		Buena la información que reflejas.

* **Cristhian Julian Gómez Lizcano** (3)

	
	Para evitar la fatiga:
	
	def crear_carrera(json):  
	return str(db.carreras.insert_one(json).inserted_id)
	
	def consultar_carrera_por_id(carrera_id):  
	return dumps(db.carreras.find_one({’_id’: ObjectId(carrera_id)}))
	
	def actualizar_carrera(carrera):  
	# Esta funcion solamente actualiza nombre y descripcion de la carrera  
	return str(db.carreras.update_one({’_id’: ObjectId(carrera[’_id’])}, {’$set’: {‘nombre’: carrera[‘nombre’], ‘descripcion’: carrera[‘descripcion’] }} ).modified_count)
	
	def borrar_carrera_por_id(carrera_id):  
	return str(db.carreras.delete_one({’_id’: ObjectId(carrera_id)}))

* **GersonPc** (2)

	
	No me pasa que para que este código funcione literalmente reinicie mi Pc y funcionó 😅

* **raparisg** (2)

	
	No conozco nada de Python así que trabajé en Java! Pueden conseguir el repo acá: <https://github.com/ramonparisg/mongodb-test>
	
	😃

* **Luis Jeanpier Monserrate** (2)

	
	Compañeros, asegurense de que tienen las variables de entorno requeridas por el proyecto configuradas, la mayoría de los problemas de configuración se deben a eso,
	
	Al instalar Anaconda, les muestra una opción para agregar sus variables de entorno al PATH del sistema operativo, también recomiendo usar como terminal git bash o cmder si estan en windows.
	
	Si no les funciona “export” para setear las variables de entorno usen “set”. A la hora poner la Uri de sus clusters de MongoDB atlas, ponganla sin comillas.

* **Deiby Johany Avila Gutierrez** (2)

	
	En realidad he tratado de todo para hcer funciona ese api rest , y aun no lo logro, alguien puede indicarme el proceso teniendo python en la version 3.7

	* **Eduardo Imery Winterdaal** (1)

		
		Hola Deiby, que problema te esta dando ? saludos

	* **dbzdavidbaez** (1)

		
		Que error te sale?

* **Juan Osio** (2)

	
	Que poco didáctico

	* **Alberto González** (1)

		
		¿Por qué?

* **Sabrina Valerio Hidalgo** (2)

	
	¿Qué IDE está usando el profesor?

	* **Manuel Garcia** (3)

		
		[PyCharm](https://www.jetbrains.com/pycharm/) ✌

	* **Sabrina Valerio Hidalgo** (1)

		
		Gracias colega!

	* **Brayan Mamani** (1)

		
		De **JetBrains**.

* **Juan Carlos Faundez** (2)

	
	Bueno, no tengo idea de Python así que tuve varios errores los cuales al buscar en google no eran tan difíciles de solucionar.  
	El primero fue el error del comando ‘conda’ que no funcionaba en cmd después de haber instalado anaconda e incluso reiniciado el equipo, creo que se cambia algo para que funcione por defecto pero a mi me funcionó al abrir “anaconda Navigator” que es la aplicación que se instala en windows al instalar anaconda, desde ahí solo tuve que ir a la sección enviroments > base(root) y en el signo “play” open terminal, desde ahí si funcionaba el comando conda y pude seguir con la configuración.  
	El segundo error fue “no module named bson” el cual solucione instalando en la misma consola pip install pymongo.  
	y el ultimo error fue "the dnspython module must be installed to use mongodb+srv // uris"  
	El cual se soluciona en la consola instalando dnspython con:  
	pip install dnspython.  
	Cabe destacar que cada vez que hacia un cambio, hacia correr nuevamente el proyecto con flask run para probar.  
	Espero le ayude a alguien o a varios.

	* **jsrodriguezj** (1)

		
		Buen aporte compañero, lo tendré muy en cuenta.

* **Marcos Gomez** (1)

	
	no me funciona  
	como hago para exportar las variables ??  
	a donde va esto??
	
	export FLASK_APP=platzi-api
	
	export FLASK_ENV=development
	
	export PLATZI_DB_URI=“MONGO-URI”

	* **Juan David Castro (Platzi)** (1)

		
		Eso lo escribes en la terminal. 😉

* **Jaiden Meiden** (1)

	
	Todavía no he profundizado en Python lo suficiente. Alguien sabe porque se presenta el siguiente error?
	``` 
	    SyntaxError
	    
	    File"/home/fullmetal/Desarrollo/Estudio/mongo/platzi-mongo/platzi-api/db.py", line 7
	    SyntaxError: Non-ASCII character '\xc3' infile /home/fullmetal/Desarrollo/Estudio/mongo/platzi-mongo/platzi-api/db.py online 7, but no encoding declared; see http://python.org/dev/peps/pep-0263/ for details
	    Traceback (most recent call last)
	    
	        File"/home/fullmetal/anaconda2/lib/python2.7/site-packages/flask/cli.py", line 76, in find_best_app
	    
	        app = call_factory(script_info, app_factory)
	    
	        File"/home/fullmetal/anaconda2/lib/python2.7/site-packages/flask/cli.py", line 116, in call_factory
	    
	        return app_factory()
	    
	        File"/home/fullmetal/Desarrollo/Estudio/mongo/platzi-mongo/platzi-api/__init__.py", line 24, in create_app
	    
	        from . import carreras,cursos
	    
	        File"/home/fullmetal/Desarrollo/Estudio/mongo/platzi-mongo/platzi-api/carreras.py", line 2, in <module>
	    
	        from . import db
	    
	    File"/home/fullmetal/Desarrollo/Estudio/mongo/platzi-mongo/platzi-api/db.py", line 7
	    SyntaxError: Non-ASCII character '\xc3' infile /home/fullmetal/Desarrollo/Estudio/mongo/platzi-mongo/platzi-api/db.py online 7, but no encoding declared; see http://python.org/dev/peps/pep-0263/ for details
	    
	    The debugger caught an exception in your WSGI application. You can now look at the traceback which led to the error. 
	    
	```

* **Francisco Martin Nacimiento** (1)

	
	Yo no sé de python, pero no tuve problemas en hacer funcionar el proyecto en docker. Pero toca aprender python si o si pronto!

* **chatuz1337** (1)

	
	siento este vídeo innecesario si quisiera aprender python estaría dicho curso.

* **Juan Guillermo Perez Cardozo** (1)

	
	muy basico el ejemplo

* **Jose Arturo Enriquez Hurtado** (1)

	
	+2

* **Julio Ignacio Oyarzun Cayuman** (1)

	
	Pude insertar u documento carrera mas por la shell me salio el siguiente error:
	
	AttributeError: ‘InsertOneResult’ object has no attribute ‘insert_id’

	* **Gerardo Nava Pereda** (1)

		
		insert_id => inserted_id

* **Luis Jeanpier Monserrate** (1)

	
	Las variables de entorno son como enlaces que se le proveen al sistema operativo para que el interprete de comandos nos identifique o reconozca los programas que queremos ejecutar

* **dbzdavidbaez** (1)

	
	Clase muy interesante y practica de MongoDb. Todo funciono.

* **Eduardo Imery Winterdaal** (1)

	
	Excelente

* **Luis Rangel Castro** (1)

	
	Hice el proyecto desde cero. Utilizando MongoDB localmente. No logro conectar al servicio de Atlas.  
	Con esto ya logro utilizar los ejemplos de peticiones REST en PostMan
	``` 
	    pip install --upgrade pip
	    pip install flask
	    pip install pymongo
	    mkdir platzi-mongo2
	    cd platzi-mongo2
	    mkdir platzi-api
	    cd platzi-api
	    touch db.py
	    
	```
	``` 
	    # agregar codigo al archivo db.py
	    
	```
	``` 
	    from flask import Flask
	    from flask import request
	    from pymongo import MongoClient
	    from bson.json_util import dumps
	    import json
	    
	    client = MongoClient('localhost:27017')
	    db = client.platzi
	    
	    app = Flask(__name__)
	    
	    @app.route("/")
	    defhello():
	        return"Welcome to Python Flask! platzi-mongo2"
	    
	    @app.route("/carreras", methods = ['POST'])
	    defadd_contact():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                status = db.carreras.insert_one(data)
	            return dumps({'message' : 'SUCCESS'})
	        except Exception as e:
	            return dumps({'error' : str(e)})
	    
	    @app.route("/carreras", methods = ['GET'])
	    defget_all_contact():
	        try:
	            contacts = db.carreras.find()
	            return dumps(contacts)
	        except Exception as e:
	            return dumps({'error' : str(e)})
	    
	```
	``` 
	    FLASK_APP=db.py flask run
	    
	    # revisar servicio
	    http://127.0.0.1:5000/
	    
	    # listado de carreras
	    http://127.0.0.1:5000/carreras
	    
	```

	* **Luis Rangel Castro** (1)

		
		Código actualizado para [db.py](http://db.py):
		``` 
		    from flask import Flask
		    from flask import request
		    from pymongo import MongoClient
		    from bson.json_util import dumps
		    from bson import ObjectId
		    import json
		    
		    # client = MongoClient('localhost:27017')
		    client = MongoClient('mongodb+srv://[usuario]:[clave]@curso-platzi-kuuzl.mongodb.net/test')
		    db = client.platzi
		    
		    app = Flask(__name__)
		    
		    @app.route("/")
		    defhello():
		        return"Welcome to Python Flask! platzi-mongo2"
		    
		    # CREATE CARRERA
		    @app.route("/carreras", methods = ['POST'])
		    defcreate_carrera():
		        try:
		            data = json.loads(request.data)
		            nombre = data['nombre']
		            descripcion = data['descripcion']
		            if nombre and descripcion:
		                # status = db.carreras.insert_one(data)
		                # return dumps({'message' : 'SUCCESS'})
		                return dumps(db.carreras.insert_one(data).inserted_id)
		        except Exception as e:
		            return dumps({'error' : str(e)})
		    
		    # READ TODAS LAS CARRERAS
		    @app.route("/carreras", methods = ['GET'])
		    defread_carrera():
		        try:
		            contacts = db.carreras.find()
		            return dumps(contacts)
		        except Exception as e:
		            return dumps({'error' : str(e)})
		    
		    # READ UNA CARRERA POR id
		    @app.route("/carreras/<id>", methods = ['GET'])
		    defread_carrera_id(id):
		        try:
		            pageid = id
		            return dumps(db.carreras.find_one({'_id' : ObjectId(pageid)}))
		        except Exception as e:
		            return dumps({'error' : str(e)})
		    
		    # UPDATE CARRERA
		    @app.route("/carreras", methods = ['PUT'])
		    defupdate_carrera():
		        try:
		            data = json.loads(request.data)
		            nombre = data['nombre']
		            _id = data['_id']
		            descripcion = data['descripcion']
		            if nombre and descripcion:
		                status = db.carreras.update_one({'_id' : ObjectId(_id)}, {'$set': {'nombre' : nombre, 'descripcion':descripcion}})
		                return str(status.modified_count)
		        except Exception as e:
		            return dumps({'error' : str(e)})
		    
		    # DELETE UNA CARRERA POR id
		    @app.route("/carreras/<id>", methods = ['DELETE'])
		    defdelete_carrera_id(id):
		        try:
		            pageid = id
		            status = db.carreras.delete_one({'_id' : ObjectId(pageid)})
		            return str(status.deleted_count)
		        except Exception as e:
		            return dumps({'error' : str(e)})
		    
		    # home function
		    @app.route('/profile/<int:id>')
		    defmyProfile(id):
		        return'The project page ' + str(id)
		    
		```

* **Luis Rangel Castro** (1)

	
	en MAC  
	git clone <https://github.com/AERC18/platzi-mongo.git>
	
	<h1>navegar hasta el directorio del proyecto</h1>
	
	cd platzi-mongo
	
	<h1>crear un nuevo ambiente</h1>
	
	conda create --name platzi-mongo
	
	<h1>Instalar Flask</h1>
	
	pip install Flask
	
	<h1>activar el ambiente</h1>
	
	conda activate platzi-mongo
	
	<h1>para desactivar el ambiente</h1>
	
	conda deactivate
	
	<h1>para correr proyecto</h1>
	
	export FLASK_APP=platzi-api  
	export FLASK_ENV=development  
	export PLATZI_DB_URI=“MONGO-URI”  
	Flask run
	
	<h1>abrir servicio</h1>
	
	<http://localhost:5000>

* **Briones D. Jose** (1)

	
	que mala onda no entiendo porque dice mongodb y metemos python :’(

	* **Alberto González** (1)

		
		Míralo de ésta manera, es una oportunidad para adentrarte al mundo de python.

* **Karl Heitmann** (1)

	
	Cuando ejecuto el comando que envía el POST, obtengo error de python. _TypeError: document must be an instance of dict, bson.son.SON, bson.raw_bson.RawBSONDocument, or a type that inherits from collections.MutableMapping._
	
	Cabe aclarar dos hechos:
	
	  * El repositorio Git del proyecto lo estoy usando en la rama _master_
	  * De la clase anterior, el punto 3 del segmento “Instalar postman”, en el que dice “Ahora es momento de importar la colección con todos los ejemplos de peticiones REST usados en platzi-mongo para ello copiamos la URL <URL>” no me quedó muy claro a qué se refiere con importar la colección, por lo que no visité el link, vi una estructura JSON, pero no hice nada con el programa postman.
	
	
	
	Aquí va el traceback completo:
	``` 
	    `--> flask run
	     * Serving Flask app "platzi-api" (lazy loading)
	     * Environment: development
	     * Debug mode: on
	     * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
	     * Restarting with stat
	     * Debugger is active!
	     * Debugger PIN: 209-467-522
	    127.0.0.1 - - [16/Sep/2019 01:30:41] "POST /carreras HTTP/1.1" 500 -
	    Traceback (most recent call last):
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/app.py", line 2309, in __call__
	        return self.wsgi_app(environ, start_response)
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/app.py", line 2295, in wsgi_app
	        response = self.handle_exception(e)
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/app.py", line 1741, in handle_exception
	        reraise(exc_type, exc_value, tb)
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/_compat.py", line 35, in reraise
	        raise value
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/app.py", line 2292, in wsgi_app
	        response = self.full_dispatch_request()
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/app.py", line 1815, in full_dispatch_request
	        rv = self.handle_user_exception(e)
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/app.py", line 1718, in handle_user_exception
	        reraise(exc_type, exc_value, tb)
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/_compat.py", line 35, in reraise
	        raise value
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/app.py", line 1813, in full_dispatch_request
	        rv = self.dispatch_request()
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/flask/app.py", line 1799, in dispatch_request
	        return self.view_functions[rule.endpoint](**req.view_args)
	      File"/home/kurt/workspace/platzi/platzi-mongo/platzi-api/carreras.py", line 17, in carreras_func
	        return jsonify({'_id': db.crear_carrera(request_body)})
	      File"/home/kurt/workspace/platzi/platzi-mongo/platzi-api/db.py", line 29, in crear_carrera
	        return str(db.carreras.insert_one(json).inserted_id)
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/pymongo/collection.py", line 684, in insert_one
	        common.validate_is_document_type("document", document)
	      File"/home/kurt/workspace/platzi/platzi-mongo/venv/lib/python3.6/site-packages/pymongo/common.py", line 453, in validate_is_document_type
	        "collections.MutableMapping" % (option,))
	    TypeError: document must be an instance of dict, bson.son.SON, bson.raw_bson.RawBSONDocument, or a type that inherits from collections.MutableMapping
	    
	```

* **webins** (1)

	
	demore mucho con esta clase porque no se nada de python aun :c

* **Carlos Andres Castañeda Osorio** (1)

	
	¿Alguna forma de importar todas las peticiones en Postman que utiliza el profesor?

	* **svictoreq** (2)

		
		¿Importaste la URL <https://www.getpostman.com/collections/ffcbfb5c8d5cd2dc52d2>?

	* **albertramirez** (3)

		
		Sí, están disponibles aquí <https://www.getpostman.com/collections/ffcbfb5c8d5cd2dc52d2>  
		Y las instrucciónes para importarlas en Postán están aquí  
		<https://github.com/AERC18/platzi-mongo>

	* **Carlos Andres Castañeda Osorio** (2)

		
		Gracias a todos, no presté suficiente atención a la importación y luego de escribir unas cuantas imaginé que ya debian estar como material del curso, no me equivoqué, MIL GRACIAS !

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Ya están disponibles dentro de los recursos de la clase.

	* **Jorge Augusto Sánchez Jácome** (1)

		
		ah no carlos!!!, ponga atención a la clase!!! XD jajajaa

* **santmont** (1)

	
	cuando inserto una nueva carrera aparece esto:  
	pymongo.errors.InvalidURI
	
	pymongo.errors.InvalidURI: Invalid URI scheme: URI must begin with ‘mongodb://’ or ‘mongodb+srv://’

* **xmedinavei** (1)
No puedo exportar las variables de ambiente ni ejecutar Flask, por lo tanto no puedo conectar Postman con MongoDB Compass. Al crear carre...

* **zarza-raul** (1)
Alguna solución para el error ModuleNotFoundError: No module named ‘bson’ ? Ya intente de todo 😦

	* **zarza-raul** (2)

		
		No se que hice pero termino funcionado despues de reinciar la lap, actualizarla, cambiar varias veces de SO y probar unas 20 soluciones diferentes que encontre por ahí…

* **Carlos Andres Castañeda Osorio** (1)
¿Alguna forma de importar todas las peticiones en Postman que utiliza el profesor?

	* **svictoreq** (2)

		
		¿Importaste la URL <https://www.getpostman.com/collections/ffcbfb5c8d5cd2dc52d2>?

* **Marcos Gomez** (0)
no se como exportar las variables de entorno, donde es que se ponen??, no se como exportar las variables de entorno, donde pongo esto?? x...

# Esquemas y relaciones

## 0140. Tipos de datos

### Descripción:


 ** _Strings_** : Nos sirven para guardar textos.  
**_Boolean_** : Información cierta o falsa (`true` y `false`).  
**ObjectId** : Utilizan el tiempo exacto en el que generamos la consulta para siempre generan IDs únicos. Existen en BSON pero no en JSON.  
**_Date_** : Nos sirven para guardar fechas y hacer operaciones de rangos entre ellas.  
**Números** : **_Doubles_** , **_Integers_** , **_Integers_ 64 bits** y **_Decimals_**.  
**Documentos Embebidos** : Documentos dentro de otros documentos (`{}`).  
**_Arrays_** : Arreglos o listas de cualquier otro tipo de datos, incluso, de otras listas.

### Comentarios:

* **Juan David Castro (Platzi)** (5)

	
	  * [MongoDB Limits and Thresholds (16 megabytes)](https://docs.mongodb.com/manual/reference/limits/)
	
	

	* **jsrodriguezj** (1)

		
		que buen aporte compañero.

* **Cristian David Franco Garcia** (3)

	
	<https://docs.mongodb.com/manual/reference/bson-types/>

* **Luis Rodrigo Alvarez Herrera** (2)

	
	hasta aqui todo bien, pero como creo una base de datos desde cero?, por ejemplo en SQL haces tus tablas pero aqui que pex?? aun no me queda claro del todo

	* **Ludwing Juan Homero Pérez Tzaquitzal** (3)

		
		Para crear una base de datos desde cero lo único que hace falta es hacer un:
		``` 
		    db.<coleccion>.insertOne({...})
		    
		```
		
		Donde <colección> es el nombre de tu “tabla” y lo que va entre paréntesis es una estructura de datos MUY similiar a JSON.
		
		Es una forma extraña de modelar datos.
		
		Para los que venimos de las bases de datos relacionales nos cuesta entenderlo, pero la forma más sencilla en la que yo lo entendí fue haciendo un simil a cómo se haría ese almacenamiento en una base de datos relacional ordinaria y el enfoque al que llegué fue éste:
		
		  * Una colección equivale a una tabla en la que solo defines dos campos: el ID único que identifica a cada fila y el valor de los datos a almacenar (un campo de tipo text, o longtext o varchar(max) si quieres verlo así). Los datos pueden ser los que tu quieras en la estructura que tu quieras pero siempre y cuando sean en formato JSON.
		
		

	* **Juan José Vega Quintero** (1)

		
		Que buen ejemplo Ludwing

* **José Vázquez Membrillo** (2)

	
	¿Cómo podríamos almacenar una imagen en Base64 en Mongo?
	
	Podrían mostrar un ejemplo del modelo, y como enviarlo?
	
	Muchas gracias

	* **antonagency** (1)

		
		Bastaría con codificar la imagen en Base 64 desde tu lenguaje de programación y solamente insertarla en mongo como texto (string)

	* **Briones D. Jose** (1)

		
		puedes usar GridFile System de MongoDB

	* **Brayan Mamani** (1)

		
		GridFile System de MongoDB con eso lo puedes hacer.

	* **Marco Antonio Macedo Preciado** (1)

		
		No te recomiendo hacerlo. Podrías llegar al límite de almacenamiento en los documentos. Lo mejor es guardar únicamente la url de la imagen.

* **Diego Acosta** (2)

	
	Muy buenas clases

* **Wandy Rafael Santana Evangelista** (2)

	
	Muy clara la explicación y al punto.💚📝

* **Frank Carmona** (1)

	
	ejemplos practicos

* **Juan Guillermo Perez Cardozo** (1)

	
	ok todo claro , ahora vamos con ejemplos practicos

* **dbzdavidbaez** (1)

	
	Entendido.

* **Brayan Mamani** (1)

	
	De gran utilidad para definir los tipos de datos de los campos de nuestro documento.

* **jsrodriguezj** (1)

	
	Super clara la clase.

* **jonathan2138** (1)
Alguien me ayuda, no entendi como consultar un documento dentro de un documento, el decia que NOMBRE_DOCUMENTO.NOMBRE_SUBDOCUMENTO pero n...

## 0150. ¿Qué son los esquemas y las relaciones

### Descripción:


Los **esquemas** son la forma en que organizamos nuestros documentos en nuestras colecciones. MongoDB no impone ningún esquema pero podemos seguir buenas prácticas y estructurar nuestros documentos de forma parecida (no igual) para aprovechar la flexibilidad y escalabilidad de la base de datos sin aumentar la complejidad de nuestras aplicaciones.

Las **relaciones** son la forma en que nuestras entidades o documentos sen encuentran enlazados unos con otros. Por ejemplo: Una carrera tiene multiples cursos y cada curso tiene multiples clases.

### Comentarios:

* **Juan David Castro (Platzi)** (17)

	
	 **MongoDB 🆚 SQL** :
	
	  * 💃 MongoDB tiene mucha **flexibilidad** y no nos impone seguir una estructura o esquema bien definido.
	  * 🙅 SQL nos impone una **estructura bien definida** a más no poder; es super no-flexible.
	  * 🍻 Con MongoDB es **más fácil** empezar y añadir nuevas funcionalidades.
	  * ⏲ Con SQL es **más demorado** de empezar porque debemos tener el orden super claro siempre. Todos los elementos deben tener los mismos elementos y todos deben ser del mismo tipo. Si queremos agregar un nuevo campo debemos añadirlo en todas partes con un valor pode defecto, aunque no lo necesitemos.
	  * 🤒 Si no seguimos **buenas prácticas** en MongoDB, vamos a necesitar _queries_ ultra-complejas, demoradas y una visita diaria al psicólogo 😱.
	  * 💆 El orden impuesto de SQL no es por nada. Las queries son fáciles de entender porque todo sigue su **orden** y tranquilidad. Aunque, implementar nuevas _features_ toma su buen tiempo 🤔.
	
	
	
	🏅 Para mi el ganador es **MongoDB** siempre y cuando sigamos buenas prácticas desde el principio. **Un gran poder conlleva a una gran responsabilidad** 💪🎉.
	
	  * [MongoDB vs SQL: Di no a la rebeldía. Usa MongoDB con responsabilidad.](https://platzi.com/blog/mongo-vs-sql/)
	
	

	* **pabloverduzcos** (2)

		
		Gran manera de resumir la clase 📓

	* **Wandy Rafael Santana Evangelista** (2)

		
		No se pudo definir mejor, **MongoDB** es el nuevo SQL, que en realidad es NoSQL. xd 🤯

	* **Wilson Marino Pablo Mendez** (2)

		
		Una visita diaria al psicólogo 😂

	* **Abraham Gonzalez** (8)

		
		Muy bueno el analisis que haces. Pero cabe recalcar que MongoDB tiene casos en donde ha perdido data e incluso no tiene tantos tools para BI (Business Intelligence).
		
		Las bases de datos SQL contemplan ACID, lo que nos garantiza integridad de data (entre otros factores), comparar NoSQL y SQL a grosso modo resulta injusto para ambos, todo va a depender de que lo que tu necesites dentro de tu aplicativo.
		
		Un ejemplo muy práctico es Amazon el cual hace uso de base de datos SQL para la data sensible (Como usuario, compras, ordenes, pagos) y NoSQL para cosas más dinámicas y cambiantes como las características de los productos.

	* **jsrodriguezj** (2)

		
		Buen aporte compañero.

	* **Brayan Mamani** (2)

		
		¡Buena perspectiva!

	* **jonathan2138** (2)

		
		muy buen post

* **Wandy Rafael Santana Evangelista** (6)

	
	Si desean pueden ver un video de Freddy que explica la diferencia entre base de datos NoSQL y SQL. **Muy interesante** : <https://www.youtube.com/watch?v=CuAYLX6reXE>

	* **jsrodriguezj** (3)

		
		nice -!!!

	* **Brayan Mamani** (2)

		
		¡Es muy buena!

	* **Luis Rodrigo Alvarez Herrera** (2)

		
		mucho mejor explicado

	* **SergioRubiano** (1)

		
		Excelente aporte compañero

	* **adanfelio castro** (1)

		
		Gracias por el dato.

	* **jonathan2138** (1)

		
		gracias amigo

* **Juan Guillermo Perez Cardozo** (2)

	
	ok muy bien explicado, gracias ahora un caso practico

* **dbzdavidbaez** (2)

	
	Esquemas: La forma en que nosotros organizamos nuestros documentos dentro de nuestras colecciones.  
	Relaciones: La forma en que nuestras entidades o docuemntos estan entrelazados

* **Luis Rodrigo Alvarez Herrera** (2)

	
	este video lo explica de otra forma
	
	<https://www.youtube.com/watch?v=b_zr8t2g2Ic>

* **ehnbytes** (1)

	
	Buena clase!!  
	Esquemas  
	Relaciones

## 0160. Relaciones entre documentos

### Descripción:


Las documentos embebidos nos ayudan a guardar la información en un solo documento y nos ahorra el tiempo que tardamos en consultar diferentes documentos a partir de referencias. Sin embargo, las referencias siguen siendo muy importantes cuando debemos actualizar información en diferentes lugares de forma continua.

### Comentarios:

* **Juan David Castro (Platzi)** (10)

	
	  * **One to one** : Documentos embebidos
	  * **One to many** : Documentos embebidos cuando la información no va a cambiar muy frecuentemente y **referencias** cuando si.
	
	
	
	¡MongoDB es genial!

	* **Fernando Azuaje** (2)

		
		La verdad que si esta increible

	* **Brayan Mamani** (1)

		
		Es excelente.

* **Saúl Báez Terrez** (8)

	
	4:14 pésima explicación, debieron regrabar esta parte

* **Wandy Rafael Santana Evangelista** (2)

	
	**MongoDB es lo máximo.**😎

	* **Brayan Mamani** (2)

		
		 **MongoDB** es genial

* **Juan Guillermo Perez Cardozo** (1)

	
	bueno el ejemplo de libros y editorial

* **dbzdavidbaez** (1)

	
	Entendido. Se puede tener muchas formas para relacionar docuementos.

* **SergioRubiano** (1)

	
	Mongo Lo es todo

* **Brayan Murcia Sanchez** (1)

	
	profe o compañeros, una pregunta; es claro que para relaciones muchos a muchos es posible en mongo y con el ejemplo que nos dio acerca de los cursos de platzi es posible y practico, pero para el manejo de información de usuarios, por ejemplo en la plataforma de platzi, es buena idea utilizar mongo?, para registro de ingresos tipos de usuarios, created_at and updated_at, y todo este tipo de información, que requiere el uso de relaciones donde un cambio que afectara a miles de tablas, como se haría en mongo?

	* **Ludwing Juan Homero Pérez Tzaquitzal** (3)

		
		Depende.  
		No hay una forma única de hacer este tipo de relaciones. Puede sonar contraintuitivo, pero si al analizar tus casos de uso encuentras que establecer relaciones entre documentos resulta más complejo que usar bases de datos relacionales, es mejor utilizar una base de datos relacional.
		
		Algunos establecen relaciones mediante una especie de “llave foránea”, por ejemplo:
		``` 
		    {curso: "<id del curso>"}
		    
		```
		
		Donde <id del curso> como su nombre lo dice, es un documento de otra colección. Es una forma de hacerlo, pero no es la única y dudo mucho que sea la más óptima.

* **TIQAL SAS** (1)
cual es la mejor estrategia para relaciones muchos a muchos ???

	* **Marco Antonio Macedo Preciado** (1)

		
		Colecciones separadas con un arreglo de Ids

## 0170. Trabajando en nuestro proyecto PlatziMongo Diseñando el Esquema de Clases, Cursos y Carreras

### Descripción:


Vamos a usar tanto referencias como documentos embebidos para guardar la información de nuestros cursos y carreras. Vamos a crear una colección separada para los cursos y otra para las carreras. Esto significa que, si queremos la información de nuestros cursos, debemos consultar dos colecciones diferentes.

Para solucionar este problema vamos a guardar el nombre del curso junto con la referencia al curso en la colección de cursos. Así, cuando consultemos la colección de carreras, vamos a tener también los nombres. Recuerda que si cambie el nombre del curso debes actualizarlo en ambas colecciones.

### Comentarios:

* **Juan David Castro (Platzi)** (10)

	
	 **Modo MongoDB con Documentos Embebidos** : Guardar los documentos de los cursos directamente en la colección de la carrera porque es más rápido cargar las carreras y toda su información pero cuando cambie vas al psicólogo (no importa si solo quieres un curso, siempre traes toda todita la carrera).  
	**Modo “SQL” con Referencias** : Guardar los cursos en su propia colección y llamarlos desde la colección de carreras con un `id` de referencias. Todo bien separado y fácil de conseguir solo lo que necesitamos de cada colección pero muy costoso cuando queremos llamar a todos los cursos de una carrera porque debemos consultar colecciones diferentes una y otra vez.  
	**Modo LEGENDA** : Guardar los cursos en su propia colección pero añadir no solo una referencia sino también el nombre del curso. Así, cuando solo consultemos carrera, vamos a tener los nombres de los cursos. Solo consultamos cada curso cuando necesitamos toda todita la información. **IMPORTANTE** : Ojo que debemos actualizar el nombre del curso en dos partes diferentes.
	
	¡Wow! Este ejemplo fue super! 👏
	
	  * [MongoDB vs SQL: Di no a la rebeldía. Usa MongoDB con responsabilidad.](https://platzi.com/blog/mongo-vs-sql/)
	
	

	* **jsrodriguezj** (1)

		
		Buen aporte compañero.

	* **Brayan Mamani** (1)

		
		¡Bien!

* **Juan Guillermo Perez Cardozo** (9)

	
	Es un poco dificil desligarse de sql

* **Luis Rangel Castro** (7)

	
	Si sabemos que el documento puede crecer mas de 16 MB es mejor hacer una nueva colección y relacionarla con el documento (Comentarios).

* **Angel Infanti** (3)
No seria mejor agregarle la carrera al curso ?? Pregunto yo ??

* **dbzdavidbaez** (2)

	
	Entendido. Pensando en forma MongoDb…

* **Wilson Marino Pablo Mendez** (2)

	
	Muy interesante las DBs NoSQL

	* **Brayan Mamani** (1)

		
		Comparto tu entusiasmo.

* **Marco Aurelio Elizalde Torres** (1)

	
	Si una aplicación como Medium, que tengo entradas, y muestro la lista de entradas con el titulo y el nombre de la persona, en este caso es bueno tener la referencia o colocar el nombre directo en la entrada???

* **DiegoADaza** (1)

	
	Tuvo bastantes el profesor entre si eran colecciones y/o documentos, alguien lo noto?.. Hasta dode entendi, las carrera, los cursos y las clases TODAS para este ejemplo son documentos.

	* **Vicente Fernandez** (2)

		
		El profesor tuvo muchos enredos al momento de explicar entre carreras, clases, cursos, documentos y colecciones.

* **raparisg** (1)

	
	¿Es buena idea ponerle ID a las clases o no es necesario en este caso?

	* **ddragaid** (1)

		
		Como buena practica y para tener una buena organizacion es bueno que todas las clases tengan su ID

* **jonathan2138** (1)

	
	Muy interesante este tema, nos ayuda bastante comprender todo lo que se dice conociendo también de BD relaciones, aunque la explicación esta perfecta

* **rosanacarrasco** (1)
Me perdi un poco con este video, de repente aparece este editor y no encuentro en que momento se lo presenta. ahora los archivos que esta...

	* **jonathan2138** (2)

		
		Es un editor de Codigo, él esta usando Visual Studio Code, pero hay otros como Atom, simplemente crear formatos json y sigues el ejemplo.  
		Al crear estos formatos json, en MongoDB Compass te da la opción de importar estos json y se crearan las colecciones que tengas.

# Profundización de queries dentro de MongoDB

## 0180. Operadores para realizar queries y proyecciones

### Descripción:


### Comentarios:

* **Wandy Rafael Santana Evangelista** (13)

	
	Operadores para arreglo.  
	**$all:** Arreglos que contengan todos los elementos de la query.  
	**$elementMatch:** Documentos que cumplen la condición del $elementMatch en uno de sus elementos.  
	**$size:** Documentos que contienen un capo tipo arreglo de un tamaño específico.

* **Wandy Rafael Santana Evangelista** (13)

	
	Operadores lógicos.  
	**$and:** Une queries con un and lógico.  
	**$not:** Invierte el efecto de un query.  
	**$nor:** Une queries con un nor lógico.  
	**$or:** Une queries con un or lógico.

* **Wandy Rafael Santana Evangelista** (12)

	
	Operadores por elemento.  
	**$exist:** Documentos que cuentan con un campo específico.  
	**$type:** Documentos que cuentan con un campo de un tipo específico.

* **Wandy Rafael Santana Evangelista** (12)

	
	Operadores de comparación en MongoDB.  
	**$eq:** Igual ‘=’.  
	**$gt:** Mayor ‘>’.  
	**$gte:** Mayor o igual ‘>=’.  
	**$lt:** Menor ‘<’.  
	**$lte:** Menor o igual ‘<=’.  
	**$ne:** Diferente ‘!=’.  
	**$in:** Valores dentro de un arreglo.  
	**$nin:** Valores que no están dentro de un arreglo.

* **dbzdavidbaez** (8)

	```
	    $eq     =
	    $gt      >
	    $gte   >=
	    $lt       <
	    $lte    <=
	    $ne    !=
	    $in     valores dentro de un rango
	    $nin    valores que no estan dentro de un rango
	    $and   Une queries con un AND logico
	    $not   Invierte el efecto de un query
	    $nor   Une queries con un NOR logico
	    $or      Une queries con un OR logico
	    $exist     Docuemntos que cuentan con un campo especifico
	    $type     Docuemntos que cuentan con un campo de un tipo especifico
	    $all          Arreglos que contengan todos los elementos del query
	    $elemMatch    Documentos que cumplen la condicion del $elemMatch en uno de sus elementos
	    $size    Documentos que contienen un campo tipo arreglo de un tamaño especifico.
	    
	```

	* **jonathan2138** (1)

		
		Gran aporte amigo

* **Julio Ignacio Oyarzun Cayuman** (3)

	
	No explico el operador nor, pillin

* **Miguel Peláez** (3)

	
	Las proyecciones me permiten indicarle a mongo cuales campos se necesitan que devuelva en la consulta, para esto se le indica con un 1 si se requiere que un campo se retorne y con 0 a los que se necesitan retornar.
	``` 
	    ...findOne( ... {item: 1, starus: 0} ...
	    
	```

* **Carlos Andres Castañeda Osorio** (2)

	
	Super Clase !! Teoría que no se debe olvidar, tener muy en cuenta esta clase para cuando se realicen ejercicios prácticos

	* **Brayan Mamani** (1)

		
		La teoría es un pilar fundamental.

* **Juan Guillermo Perez Cardozo** (1)

	
	ejemplo de los operadores para arreglos

* **Cesar Orozco Manotas** (1)

	
	Operadores para arreglos

* **Cesar Orozco Manotas** (1)

	
	OPeradores por elementos

* **Cesar Orozco Manotas** (1)

	
	Operadores lògicos

* **Cesar Orozco Manotas** (1)

	
	OPeradores de comparación en MongoDB

* **Nicolas Guerrero** (1)

	
	Alguien que ayude con la presentacion.

	* **Luis Rodrigo Alvarez Herrera** (1)

		
		checa esta presentacion <https://www.youtube.com/watch?v=4q2DRov45uQ>

* **Srna** (1)

	
	Comparation Operators

* **Wilson Marino Pablo Mendez** (1)

	
	Yeeaa estaba esperando estos operadores

## 0190. Trabajando en nuestro proyecto PlatziMongo Ejecución de Queries

### Descripción:


### Comentarios:

* **Marcos Plata** (18)

	
	Para dejar un poco mas claro el codigo del update y no hacer una linea tan larga, se pueden almacenar los valores de los parametros de update_one en variables, de la siguiente manera:
	``` 
	    filter = {"_id":ObjectId(curso["_id"])}
	    set = {'$set':{'nombre':curso['nombre'], 'descripcion':curso['descripcion'],'clases':curso['clases']}}
	    
	    
	```
	
	Asi al hacer el update solo se hace
	``` 
	    db.cursos.update_one(filter, set).modified_count
	    
	    
	```

* **Saúl Báez Terrez** (5)

	
	5:30 el problema de copiar y pegar código, una mala práctica.

* **Carlos Martinez** (5)

	
	en el caso de los esquemas, como se pueden definir mejor?, el profesor los definió pero no es que se usen obligatoriamente no? osea lo digo porque, al momento de crear un nuevo curso lo hace mediante **postman** y la estructura del json viene definida como se había acordado anteriormente, pero si uno quiere, la puede cambiar sin problemas no?
	
	**mi pregunta es,** hay alguna manera de poner un poco de “orden” al momento de definir cual será nuestra estructura(esquema) de los documentos??, tal vez con un `example.json` en el cual definimos como son las estructuras de los documentos? para de esa manera dejarle claro a otros desarrolladores como esta definida la estructura.
	
	todo esto lo pregunto porque estaba viendo un tutorial en youtube en donde en vez de usar el modulo nativo de mongodb para **nodejs** usaban una librería llamada `mongoose` , y había una parte en la cual se definía el esquema con mongoose donde incluso se ponía que tipo de dato se esperaba, esto no lo he visto aún en el modulo nativo de mongodb para nodejs.
	
	y la duda me surge debido a que , ¿ no se supone que mongodb es una base de datos sin esquemas ? , en la cual los documentos lo podemos ir guardando con la estructura que queramos no importa si la cambiamos, asi que, para retomar mi pregunta… , cual sería la mejor manera de mantener o por lo menos tratar de mantener un esquema para cierto tipo de documentos json ? , de tal manera que yo en un futuro u otros desarrolladores puedan ver facilmente como estan estructurados los documentos.
	
	espero alguien me saque de dudas jeje, saludos y gracias de antemano

	* **anibalrojas (Platzi)** (3)

		
		Muy interesante tu pregunta. Si tienes las necesidad de poner un “poco de orden” entonces muy posiblemente en realidad la solución a tu problema es un RDBMS, tecnología muy sólida con muchísimos años en el mercado. Y si una parete de tu problema aún requiere de schemaless documents puedes utilizar soporte para columnas JSON como por ejemplo lo ofrece PostgreSQL, con lo que puedes incluso definir índices sobre el las propiedas del documento para optimizar queries.

	* **albertramirez** (4)

		
		Hola Carlos, es una buena pregunta.  
		Una forma de “poner un poco de orden” en MongoDB de forma nativa es empleando una funcionalidad que se encuentra disponible desde Mongo 3.6 llamada [schema validation](https://docs.mongodb.com/manual/core/schema-validation/)
		
		De esa manera se pueden definir campos obligatorios dentro de un documento a nivel de colección, ahora MongoDB es schema less debido a que no tienes la obligación de definir un schema para guardar tus documentos sin embargo si tu caso de uso lo requiere puedes hacerlo.

	* **codeitor** (2)

		
		Estoy con la misma incertidumbre, leyendo información de otros sitios, con node.js el 90% de los casos usa mongoose… así que supongo voy por ese lado, implementando schema para que otros desarrolladores sepan de la estructura a simple vista.

* **Luis Rodrigo Alvarez Herrera** (2)

	
	Profesor, no solo copies y pegues

	* **jonathan2138** (1)

		
		Que otra forma lo harias?

	* **AryRosvall** (1)

		
		Escribiendo uno a uno para que vayamos viendo lo que hay que hacer y para evitarse que le falten llaves o paréntesis como en esta clase. Venimos a aprender no a copiar y pegar código.

* **Luis Donaldo Lopez Gil** (2)

	```
	    {
	    	"nombre": "Fundamentos AWS",
	    	"description": "Aprenderas a desplegar soluciones en la nube AWS",
	    	"clases": [
	    			{
	    				"orden": 1,
	    				"nombre": "Clase 1",
	    				"descripcion": "Descripcion de la clase 1",
	    				"video": "https://youtube.com"
	    			},
	    			{
	    				"orden": 2,
	    				"nombre": "Clase 2",
	    				"descripcion": "Descripcion de la clase 1",
	    				"video": "https://youtube.com"
	    			},
	    			{
	    				"orden": 3,
	    				"nombre": "Clase 3",
	    				"descripcion": "Descripcion de la clase 1",
	    				"video": "https://youtube.com"
	    			},
	    			{
	    				"orden": 4,
	    				"nombre": "Clase 4",
	    				"descripcion": "Descripcion de la clase 1",
	    				"video": "https://youtube.com"
	    			}
	    		]
	    }```
	    
	```

* **Jose Manuel Salazar** (2)

	
	A pesar de realizar la instalación de todas las herramientas de forma exitosa, me esta generando el siguiente error, cuando llamo a <http://127.0.0.1:5000/>
	
	ALGUNA SOLUCION AL RESPECTO?. .
	
	builtins.ModuleNotFoundError  
	ModuleNotFoundError: No module named ‘bson’
	
	Traceback (most recent call last)  
	File “/home/jmsg78/anaconda3/lib/python3.7/site-packages/flask/cli.py”, line 76, in find_best_app  
	app = call_factory(script_info, app_factory)  
	File “/home/jmsg78/anaconda3/lib/python3.7/site-packages/flask/cli.py”, line 116, in call_factory  
	return app_factory()  
	File “/home/jmsg78/platzi-mongo/platzi-api/ **init**.py”, line 24, in create_app  
	from . import carreras,cursos  
	File “/home/jmsg78/platzi-mongo/platzi-api/carreras.py”, line 2, in <module>  
	from . import db  
	File “/home/jmsg78/platzi-mongo/platzi-api/db.py”, line 1, in <module>  
	from bson.json_util import dumps, ObjectId  
	ModuleNotFoundError: No module named 'bson’  
	The debugger caught an exception in your WSGI application. You can now look at the traceback which led to the error.  
	To switch between the interactive traceback and the plaintext one, you can click on the “Traceback” headline. From the text traceback you can also create a paste of it. For code execution mouse-over the frame you want to debug and click on the console icon on the right side.
	
	You can execute arbitrary Python code in the stack frames and there are some extra helpers available for introspection:

	* **cirovladimir** (4)

		
		El error señala que no tienes el módulo bson en tu ambiente de python, asegurate de haber instalado los requerimientos del proyecto
		``` 
		    pip install -r requirements.txt
		    
		```
		
		puedes ver los paquetes que tienes instalados con
		``` 
		    pip list
		    
		```
		
		prueba si tienes instalado pymongo
		``` 
		    pip list | grep pymongo
		    
		```
		
		en los comandos anteriores puedes sustituir `pip` por `conda`
		
		Al parecer también hay algún conflicto si instalas directamente el paquete `bson` y `pymongo`, prueba desinstalar e instalar en este orden.
		``` 
		    sudo pip uninstall bson
		    sudo pip uninstall pymongo
		    sudo pip install pymongo
		    
		```
		
		fuente: <https://stackoverflow.com/questions/42779934/jupyter-notebook-importerror-no-module-named-bson>

	* **ruthazuniga** (2)

		
		Gracias!, me funcionó

	* **Brayan Mamani** (1)

		
		¡Funciona correctamente!

* **Carlos Martinez** (2)
en el caso de los esquemas, como se pueden definir mejor?, el profesor los definió pero no es que se usen obligatoriamente no? osea lo d...

	* **anibalrojas (Platzi)** (3)

		
		Muy interesante tu pregunta. Si tienes las necesidad de poner un “poco de orden” entonces muy posiblemente en realidad la solución a tu problema es un RDBMS, tecnología muy sólida con muchísimos años en el mercado. Y si una parete de tu problema aún requiere de schemaless documents puedes utilizar soporte para columnas JSON como por ejemplo lo ofrece PostgreSQL, con lo que puedes incluso definir índices sobre el las propiedas del documento para optimizar queries.

* **Juan Guillermo Perez Cardozo** (1)

	
	entendido, gracias

* **dbzdavidbaez** (1)

	
	Entendido y funciono correctamente.

* **Didier Zúñiga** (1)

	
	Como puedo crear consultas o hacer modificaciones sobre arrays anidados?

* **Luis Rangel Castro** (1)

	```
	    from flask import Flask
	    from flask import request
	    from pymongo import MongoClient
	    from bson.json_util import dumps
	    from bson import ObjectId
	    import json
	    
	    # client = MongoClient('localhost:27017')
	    client = MongoClient(
	        'mongodb+srv://[usuario]:[clave]@curso-platzi-kuuzl.mongodb.net/test')
	    db = client.platzi
	    
	    app = Flask(__name__)
	    
	    
	    @app.route("/")
	    defhello():
	        return"Welcome to Python Flask! platzi-mongo2"
	    
	    # CREATE CARRERA
	    @app.route("/carreras", methods=['POST'])
	    defcreate_carrera():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                # status = db.carreras.insert_one(data)
	                # return dumps({'message' : 'SUCCESS'})
	                return dumps(db.carreras.insert_one(data).inserted_id)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ TODAS LAS CARRERAS
	    @app.route("/carreras", methods=['GET'])
	    defread_carrera():
	        try:
	            carreras = db.carreras.find()
	            return dumps(carreras)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ UNA CARRERA POR id
	    @app.route("/carreras/<id>", methods=['GET'])
	    defread_carrera_id(id):
	        try:
	            pageid = id
	            return dumps(db.carreras.find_one({'_id': ObjectId(pageid)}))
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # UPDATE CARRERA
	    @app.route("/carreras", methods=['PUT'])
	    defupdate_carrera():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            _id = data['_id']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                status = db.carreras.update_one({'_id': ObjectId(_id)}, {
	                                                '$set': {'nombre': nombre, 'descripcion': descripcion}})
	                return str(status.modified_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # DELETE UNA CARRERA POR id
	    @app.route("/carreras/<id>", methods=['DELETE'])
	    defdelete_carrera_id(id):
	        try:
	            pageid = id
	            status = db.carreras.delete_one({'_id': ObjectId(pageid)})
	            return str(status.deleted_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    
	    # home function
	    @app.route('/profile/<int:id>')
	    defmyProfile(id):
	        return'The project page ' + str(id)
	    
	    
	    # CREATE CURSO
	    @app.route("/cursos", methods=['POST'])
	    defcreate_curso():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                # id = str(db.cursos.insert_one(data).inserted_id)
	                # return dumps({"_id":id})
	                return dumps(db.cursos.insert_one(data).inserted_id)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ TODAS LOS CURSOS
	    @app.route("/cursos", methods=['GET'])
	    defread_curso():
	        try:
	            cursos = db.cursos.find()
	            return dumps(cursos)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ UN CURSO POR id
	    @app.route("/cursos/<id>", methods=['GET'])
	    defread_curso_id(id):
	        try:
	            pageid = id
	            return dumps(db.cursos.find_one({'_id': ObjectId(pageid)}))
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # UPDATE CURSO
	    @app.route("/cursos", methods=['PUT'])
	    defupdate_curso():
	        try:
	            data = json.loads(request.data)
	            _id = data['_id']
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            # eliminar _id del JSON para que no genere un error al actualizar
	            del data['_id']
	            filtro = {'_id': ObjectId(_id)}
	            actualizar = {'$set': data}
	            if nombre and descripcion:
	                status = db.cursos.update_one(filtro, actualizar)
	                return str(status.modified_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # DELETE UN CURSO POR id
	    @app.route("/cursos/<id>", methods=['DELETE'])
	    defdelete_curso_id(id):
	        try:
	            pageid = id
	            status = db.cursos.delete_one({'_id': ObjectId(pageid)})
	            return str(status.deleted_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	```

* **Jose Manuel Salazar** (1)
A pesar de realizar la instalación de todas las herramientas de forma exitosa, me esta generando el siguiente error, cuando llamo a 

	* **cirovladimir** (4)

		
		El error señala que no tienes el módulo bson en tu ambiente de python, asegurate de haber instalado los requerimientos del proyecto
		``` 
		    pip install -r requirements.txt
		    
		```
		
		puedes ver los paquetes que tienes instalados con
		``` 
		    pip list
		    
		```
		
		prueba si tienes instalado pymongo
		``` 
		    pip list | grep pymongo
		    
		```
		
		en los comandos anteriores puedes sustituir `pip` por `conda`
		
		Al parecer también hay algún conflicto si instalas directamente el paquete `bson` y `pymongo`, prueba desinstalar e instalar en este orden.
		``` 
		    sudo pip uninstall bson
		    sudo pip uninstall pymongo
		    sudo pip install pymongo
		    
		```
		
		fuente: <https://stackoverflow.com/questions/42779934/jupyter-notebook-importerror-no-module-named-bson>

## 0200. Trabajando en nuestro proyecto PlatziMongo Relaciones

### Descripción:


### Comentarios:

* **Luis Rodrigo Alvarez Herrera** (10)

	
	Todo iba bien hasta el video 18, despues se pierde el hilo y despues seguirlo con python,

* **maojedas** (10)
Señores Platzi, yo estoy pagando por aprender mongo, no para aprender phyton .. esto es una tomadura de pelo... estoy bien molesto. Resulta que para aprender mongo necesito correr un monton de programas postman, phyton etc.

	* **Juan David Castro (Platzi)** (3)

		
		No necesariamente. NO tienes que hacer los ejercicios con Python si te causan molestias. Puedes usar la consola de MongoDB directamente. O usar tu lenguaje de programación favorito. Estas clases solo son un ejemplo práctico para construir un CRUD con MongoDB.
		
		👉 <http://platzi.com/comentario/559353/>

	* **Briones D. Jose** (1)

		
		x2 pague el curso de mongodb

	* **Brayan Mamani** (1)

		
		Cada uno tiene su punto de vista, pero tambien tienen razon.

	* **Marco Antonio Macedo Preciado** (5)

		
		Yo estoy siguiendo el curso con Node.js, lo importante es tomar la lógica.

* **Lorena Pérez González** (8)

	
	Muy decepcionante el curso a nivel de estructuración, deberian trabajar en un curso de Mongodb mas estructurado, una pena que aun lo lo hayan rectificado.

* **Vicente Fernandez** (6)

	
	Hasta aquí llego con este curso de Python, perdón de MongoDB. Esta muy mal estructurado y explicado. Platzi por favor revisen este curso, necesita ser renovado.

	* **Gabriel De Andrade (Platzi)** (2)

		
		Hola! Nos puedes enviar tu feedback a [team@platzi.com](mailto:team@platzi.com)? es muy importante para saber los fallos 😄

* **Abraham Gonzalez** (5)

	
	Si quieren la documentación para el $pull [Pull](https://docs.mongodb.com/manual/reference/operator/update/pull/)

	* **Cristian Fabian Tovar** (3)

		
		Básicamente remueve de un array el o los valores que coincidan con la condición que se le especifique

	* **Brayan Mamani** (1)

		
		lo que menciona **@CristianTovar** es correcto.

* **Carlos Andres Castañeda Osorio** (4)

	
	Por si algún curioso (Como yo) quiere saber para qué sirve específicamente el método [$addToSet](https://docs.mongodb.com/manual/reference/operator/update/addToSet/) de la documentación oficial

	* **Cristian Fabian Tovar** (6)

		
		Por si algún perezoso (como yo) le da jartera leer la documentación, el operador $addToSet agrega un valor a un array solo en el caso de que este valor no exista (hace mas cosas, pero en resumen es eso).

* **Wandy Rafael Santana Evangelista** (3)

	
	Aunque no se Python, al menos entendí el concepto.

	* **Juan David Castro (Platzi)** (3)

		
		¡Exacto! 👌

	* **Miguel Peláez** (2)

		
		Finalmente termina siendo lo mismo: Lógica de programación. 😃

	* **Diego Acosta** (2)

		
		Si es verdad

	* **Brayan Mamani** (2)

		
		Buen punto.

* **Alberto Campos Hernandez** (3)
Cuando uso el método para borrar curso de una carrera no hace nada, implemente la función tal cual ¿alguién sabe que puede ser? de...

* **carlosbazanhuaman** (2)

	
	creo que el curso no da para mas a que es basico, fuera uno de administración seria mas por el lado de configuración y todo eso.

* **Jorge Enrique Avendaño Jara** (2)

	
	Esto no es una Clase… más bien parece un tutorial … y existen mejores turoriales por internet … !!!

* **juand_silva** (2)

	
	Excelente clase. Algunas cosas no las entedía muy bien, pero leyendo la documentación del driver **pymongo** me aclaró todas las dudas.  
	Esta muy bien documentado el driver:
	
	<https://api.mongodb.com/python/current/api/index.html>

* **Carlos Martinez** (2)

	
	tenía un pequeño error pero ya lo solucione  
	me salía:  
	`TypeError: id must be an instance of (bytes, str, ObjectId), not <class 'dict'>`
	
	y era debido a que cuando vamos a agregar un curso a una carrera hacemos uso de la funcion consultar_curso_por_id_proyeccion la cual recibe 2 parametros el id y la proyeccion
	
	mi error era que estaba convirtiendo 2 veces el **_id** en un **ObjectId** y si bien se puede ver, solo se necesita pasarle el id como un string ya que la funcion `consultar_curso_por_id_proyeccion` se encarga de ello

* **Francisco Martin Nacimiento** (1)

	
	Todo ok! Esta bueno implementarlo en un lenguaje estas practicas, y mas de uno que no se, es un desafío que afrontar!

* **Juan Guillermo Perez Cardozo** (1)

	
	averiguare mas en la documentacion sobre $addToSet

* **dbzdavidbaez** (1)

	
	Funciono el ejemplo.

* **Luis Rangel Castro** (1)

	
	código:
	``` 
	    from flask import Flask
	    from flask import request
	    from pymongo import MongoClient
	    from bson.json_util import dumps
	    from bson import ObjectId
	    import json
	    
	    # client = MongoClient('localhost:27017')
	    client = MongoClient(
	        'mongodb+srv://[usuario]:[clave]@curso-platzi-kuuzl.mongodb.net/test')
	    db = client.platzi
	    
	    app = Flask(__name__)
	    
	    
	    @app.route("/")
	    defhello():
	        return"Welcome to Python Flask! platzi-mongo2"
	    
	    # CREATE CARRERA
	    @app.route("/carreras", methods=['POST'])
	    defcreate_carrera():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                # status = db.carreras.insert_one(data)
	                # return dumps({'message' : 'SUCCESS'})
	                return dumps(db.carreras.insert_one(data).inserted_id)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ TODAS LAS CARRERAS
	    @app.route("/carreras", methods=['GET'])
	    defread_carrera():
	        try:
	            carreras = db.carreras.find()
	            return dumps(carreras)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ UNA CARRERA POR id
	    @app.route("/carreras/<id>", methods=['GET'])
	    defread_carrera_id(id):
	        try:
	            pageid = id
	            return dumps(db.carreras.find_one({'_id': ObjectId(pageid)}))
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # UPDATE CARRERA
	    @app.route("/carreras", methods=['PUT'])
	    defupdate_carrera():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            _id = data['_id']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                status = db.carreras.update_one({'_id': ObjectId(_id)}, {
	                                                '$set': {'nombre': nombre, 'descripcion': descripcion}})
	                return str(status.modified_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # DELETE UNA CARRERA POR id
	    @app.route("/carreras/<id>", methods=['DELETE'])
	    defdelete_carrera_id(id):
	        try:
	            pageid = id
	            status = db.carreras.delete_one({'_id': ObjectId(pageid)})
	            return str(status.deleted_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    
	    # home function
	    @app.route('/profile/<int:id>')
	    defmyProfile(id):
	        return'The project page ' + str(id)
	    
	    
	    # CREATE CURSO
	    @app.route("/cursos", methods=['POST'])
	    defcreate_curso():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                # id = str(db.cursos.insert_one(data).inserted_id)
	                # return dumps({"_id":id})
	                return dumps(db.cursos.insert_one(data).inserted_id)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ TODAS LOS CURSOS
	    @app.route("/cursos", methods=['GET'])
	    defread_curso():
	        try:
	            cursos = db.cursos.find()
	            return dumps(cursos)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ UN CURSO POR id
	    @app.route("/cursos/<id>", methods=['GET'])
	    defread_curso_id(id):
	        try:
	            pageid = id
	            return dumps(db.cursos.find_one({'_id': ObjectId(pageid)}))
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # UPDATE CURSO
	    @app.route("/cursos", methods=['PUT'])
	    defupdate_curso():
	        try:
	            data = json.loads(request.data)
	            _id = data['_id']
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            # eliminar _id del JSON para que no genere un error al actualizar
	            del data['_id']
	            filtro = {'_id': ObjectId(_id)}
	            actualizar = {'$set': data}
	            if nombre and descripcion:
	                status = db.cursos.update_one(filtro, actualizar)
	                return str(status.modified_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # DELETE UN CURSO POR id
	    @app.route("/cursos/<id>", methods=['DELETE'])
	    defdelete_curso_id(id):
	        try:
	            pageid = id
	            status = db.cursos.delete_one({'_id': ObjectId(pageid)})
	            return str(status.deleted_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    
	    defconsultar_curso_por_id_proyeccion(id_curso, proyeccion=None):
	        return db.cursos.find_one({'_id': ObjectId(id_curso)}, proyeccion)
	    
	    
	    # AGREGAR CURSO A CARRERA
	    @app.route("/carreras/agregar-curso", methods=['PUT'])
	    defadd_curso_to_carrera():
	        try:
	            data = json.loads(request.data)
	            curso = consultar_curso_por_id_proyeccion(
	                data['id_curso'], proyeccion={'nombre': 1})
	            return str(db.carreras.update_one({'_id': ObjectId(data['id_carrera'])}, {'$addToSet': {'cursos': curso}}).modified_count)
	    
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # REMOVER CURSO A CARRERA
	    @app.route("/carreras/agregar-curso", methods=['DELETE'])
	    defremove_curso_from_carrera():
	        try:
	            data = json.loads(request.data)
	            filtro = {'_id': ObjectId(data['id_carrera'])}
	            remove = {'$pull': {'cursos': {'_id': ObjectId(data['id_curso'])}}}
	            return str(db.carreras.update_one(filtro, remove).modified_count)
	    
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	```

## 0210. Usando operadores para realizar Updates en arreglos

### Descripción:


En este [enlace](https://docs.mongodb.com/manual/reference/operator/) se encuentran la referencia a todos los operadores que se encuentran en MongoDb, antes de emplear lógica adicional para realizar una operación vale la pena echar una ojeada a la lista de operadores que en algunos casos pueden facilitar mucho las cosas.

Para realizar las relaciones entre carreras y cursos empleamos los operadores `$addToSet` y `$pull` estos operadores sirven para agregar `$addToSet` o retirar `$pull`documentos de un arreglo dependiendo del filtro que aplicamos.

Así cuando ejecutamos `db.carreras.update_one({'_id': ObjectId(json['id_carrera'])}, {'$addToSet': {'cursos': curso}})` $addToSet lo que hace es agregar el objeto curso al arreglo cursos, si el arreglo cursos no existe lo crea.

Para retirar un curso de una carrera usamos $pull de la siguiente manera d`b.carreras.update_one({'_id': ObjectId(json['id_carrera'])}, {'$pull': {'cursos': {'_id': ObjectId(json['id_curso'])}}})` aquí $pull recibe un filtro y todos los elementos del arreglo cursos que cumplan con ese filtro serán borrados.

**skip() y limit()**

Si tenemos una consulta que retorna 100 documentos pero solamente necesitamos los documentos del número 20 al 30, la manera de hacerlo es usando skip() y limit().

Si tenemos 100 carreras y solamente queremos las primeras 10 podemos ejecutar `db.carreras.find({}).limit(10)` esta nos traerá las primeras 10 carreras.

Ahora si queremos las carreras ubicadas en los puestos 40 y 50 lo que debemos hacer es `db.carreras.find({}).skip(40).limit(10)`

Como vemos skip() y limit() son muy útiles para realizar paginaciones, cuando tenemos consultas que retornan muchos documentos y que en algunos casos la totalidad de los documentos no es utilizada es buena práctica limitar el número de documentos que hacemos viajar entre nuestro cluster de base de datos y el código de nuestra aplicación. Esto puede ayudar a mejorar la velocidad con que las consultas son procesadas por la aplicación.

**Ejercicios de práctica usando operadores**
``` 
    // Arreglo de ejemplo
    use test
    db.inventory.insertMany(
    
    [{ _id: 1, item: { name: "ab", code: "123" }, qty: 15, tags: [ "A", "B", "C" ] },
    { _id: 2, item: { name: "cd", code: "123" }, qty: 20, tags: [ "B" ] },
    { _id: 3, item: { name: "ij", code: "456" }, qty: 25, tags: [ "A", "B" ] },
    { _id: 4, item: { name: "xy", code: "456" }, qty: 30, tags: [ "B", "A" ] },
    { _id: 5, item: { name: "mn", code: "000" }, qty: 20, tags: [ [ "A", "B" ], "C" ] }]
    
    )
    
    // $or
    db.inventory.find({$or: [{qty: {$gt: 25}}, {qty: {$lte: 15}}]})
    
    // $gte
    db.inventory.find({qty: {$gte: 25}})
    
    // $size
    db.inventory.find({tags: {$size: 2}})
    
    // Insertemos estos documentos de ejemplo en la colección survey
    db.survey.insertMany([
    { _id: 1, results: [ { product: "abc", score: 10 }, { product: "xyz", score: 5 } ] }
    { _id: 2, results: [ { product: "abc", score: 8 }, { product: "xyz", score: 7 } ] }
    { _id: 3, results: [ { product: "abc", score: 7 }, { product: "xyz", score: 8 } ] }
    ])
    
    // $elemMatch
    db.survey.find(
       { results: { $elemMatch: { product: "xyz", score: { $gte: 8 } } } }
    )
    
    db.survey.find(
       { results: { $elemMatch: { product: "xyz" } } }```
```

### Comentarios:

* **frankromero** (7)

	
	el array para insertar el la colección survey tiene un pequeño error falta separar los elementos:
	``` 
	    b.survey.insertMany([ 
	    { _id:1, results: [ { product:"abc", score:10 }, { product:"xyz", score:5 } ] },
	     { _id:2, results: [ { product:"abc", score:8 }, { product:"xyz", score:7 } ] },
	     { _id:3, results: [ { product:"abc", score:7 }, { product:"xyz", score:8 } ]}
	    ])
	    
	```

	* **Luis Rangel Castro** (1)

		```
		    db.survey.insertMany([ 
		    { _id:1, results: [ { product:"abc", score:10 }, { product:"xyz", score:5 } ] },
		     { _id:2, results: [ { product:"abc", score:8 }, { product:"xyz", score:7 } ] },
		     { _id:3, results: [ { product:"abc", score:7 }, { product:"xyz", score:8 } ]}
		    ])```
		    
		```

	* **Brayan Mamani** (1)

		```
		    db.survey.insertMany([ 
		    { _id:1, results: [ { product:"abc", score:10 }, { product:"xyz", score:5 } ] },
		     { _id:2, results: [ { product:"abc", score:8 }, { product:"xyz", score:7 } ] },
		     { _id:3, results: [ { product:"abc", score:7 }, { product:"xyz", score:8 } ]}
		    ])``````
		    
		```

* **Carlos Martinez** (5)

	
	hola, tengo una duda, NOTA: esta pregunta se lee mejor en los aportes de la clase, si, al parecer hay un pequeño “bug” con las preguntas que no muestra los estilos de markdown , en fin, aqui mi pregunta:
	
	cuando ejecutamos el query  
	`db.survey.find( { results: { $elemMatch: { product: "xyz", score: { $gte: 8 } } } } )`
	
	nos trae la siguiente informacion:
	``` 
	    {
	        "_id" : 3.0,
	        "results" : [ 
	            {
	                "product" : "abc",
	                "score" : 7.0
	            }, 
	            {
	                "product" : "xyz",
	                "score" : 8.0
	            }
	        ]
	    } ```` 
	    
	```
	
	genial, sirve pero, como podria hacer una especie de proyeccion para solo traer los elementos de array que cumplan la condicion??
	
	osea, para que no traiga tooodos los elementos del array , solamente aquellos que cumplan con la condicion que se pone primero. para que quede algo asi:
	``` 
	    {
	        "_id" : 3.0,
	        "results" : [  
	            {
	                "product" : "xyz",
	                "score" : 8.0
	            }
	        ]
	    } 
	    
	```
	
	con que especie de proyeccion podria lograr eso??
	
	yo probé buscando por alli con la proyeccion  
	`{ "results.product": 1, "results.score": 1}` pero da lo mismo
	``` 
	    db.survey.find(
	       { results: { $elemMatch: { product: "xyz", score: { $gte: 8 } } } },
	       { "results.product": 1 , "results.score": 1}
	     )
	    
	```
	
	pero da lo mismo.
	
	y lo que yo busco ya que en algun momento lo podria necesitar es
	``` 
	    {
	        "_id" : 3.0,
	        "results" : [  
	            {
	                "product" : "xyz",
	                "score" : 8.0
	            }
	        ]
	    } 
	    
	```

	* **albertramirez** (8)

		
		El operador $elemMatch también puede ser usado en la proyección, así la query que estás buscando quedaría:
		``` 
		    db.test.find( { results: { $elemMatch: { product: "xyz", score: { $gte: 8 } } } } , { results: { $elemMatch: { product: "xyz", score: { $gte: 8 } } } })
		    
		```
		
		<https://docs.mongodb.com/manual/reference/operator/projection/elemMatch/>

	* **Carlos Martinez** (1)

		
		vaya, eso ni si quiera se me había ocurrido, gracias por responder profesor.

	* **Brayan Mamani** (1)

		
		Ahora todo queda mejor.

* **Juan Guillermo Perez Cardozo** (4)

	
	Entendido y funcionando, aun asi cuesta mucho acostumbrarse a hacer update, pull , cuando ya por años uno hace delete from table where condicion=val. pero bueno a tener afinidad con esa nueva forma de trabajar la base de datos

* **David Santiago Pinchao Ortiz** (1)

	
	Me gusta la forma de trabajar las queries, hay que prestar mucha atención al detalle

* **Jose Luis Campos Bautista** (1)

	
	Con respecto a los datos insertados.  
	¿Qué resulta en cada consulta?
	``` 
	    db.inventory.find({ item: { name: "ab"}  })
	    
	    db.inventory.find({ item: { name: "ab", code: "123" }  })
	    
	    
	```

* **dbzdavidbaez** (1)

	
	Entendido.

* **Carlos Martinez** (1)
hola, tengo una duda, NOTA: esta pregunta se lee mejor en los aportes de la clase, si, al parecer hay un pequeño “bug” con las preguntas ...

	* **albertramirez** (8)

		
		El operador $elemMatch también puede ser usado en la proyección, así la query que estás buscando quedaría:
		``` 
		    db.test.find( { results: { $elemMatch: { product: "xyz", score: { $gte: 8 } } } } , { results: { $elemMatch: { product: "xyz", score: { $gte: 8 } } } })
		    
		```
		
		<https://docs.mongodb.com/manual/reference/operator/projection/elemMatch/>

## 0220. Operaciones avanzadas con Agregaciones

### Descripción:


Las agregaciones son operaciones avanzadas que podemos realizar sobre nuestra base de datos con un poco más de flexibilidad en nuestros documentos.

**_Pipeline_ de Agregaciones**: Es un grupo de multiples etapas que ejecutan agregaciones en diferentes momentos. Debemos tener muy en cuenta el _performance_ de nuestras agregaciones porque las agregaciones corren en todo el _cluster_.

**_Map-Reduce_** : Nos permite definir funciones de JavaScript para ejecutar operaciones avanzadas. La función de `map` nos permite definir o “ _mappear_ ” los campos que queremos usar y la función `reduce` nos permite ejecutar operaciones y devolver resultados especiales. Por ejemplo: podemos _mappear_ algunos campos y calcular la cantidad de elementos que cumplen ciertas condiciones.

**Agregaciones de propósito único** : Funciones ya definidas que nos ayudan a calcular un resultado especial pero debemos tener cuidado porque pueden mejorar o afectar el _performance_ de la base de datos. Por ejemplo: `count()`, `estimatedDocumentCount` y `distinct`.

### Comentarios:

* **Jean Paul Sánchez Mendoza** (9)

	
	La información es muy pobre y nada de práctica. Se han colocado en el video capturas de la documentación oficial. Se entiende que el curso se básico, pero dejar esta sección sin ejemplos prácticos ha sido una tomada de pelo, sobre todo porque la premisa del curso es “Domina”. ¿Podrían incrementar más contenido para eso?

* **Juan David Castro (Platzi)** (4)

	
	  * [Agregations – MongoDB Documentation](https://docs.mongodb.com/manual/aggregation/)
	  * [MongoDB Aggregation Pipeline by Example](https://codeburst.io/mongodb-aggregation-pipeline-by-example-part-1-77accb976bd0)
	
	

* **jjorgewill** (3)

	
	😦 😦 Por que no hubo ejemplo en código aquí? incluso en la siguiente clase explico los indices con código de ejemplo. 😦

	* **Elias Ojeda Medina** (2)

		
		Revisa la documentación, aquí viene el ejemplo:  
		[<https://docs.mongodb.com/manual/aggregation/(https://docs.mongodb.com/manual/aggregation/)>

	* **Brayan Mamani** (2)

		
		La vieja confiable, la documentación es la solucion.

* **Juan Guillermo Perez Cardozo** (1)

	
	insisto toma tiempo y esfuerzo nuestro el acostumbrarnos a hacer consultas a la base de datos. como hariamos un min , max , avg ?? sera ir a la documentacion.

* **dbzdavidbaez** (1)

	
	Muy interesante.

* **Brayan Mamani** (1)

	
	¡Interesante!

* **Luis Rangel Castro** (1)

	
	Genial!

## 0230. Consultas más rápidas con Índices

### Descripción:


Los índices nos ayudan a que nuestras consultas sean más rápidas porque, sin ellos, MongoDB debería escanear toda la colección en busca de los resultados.

Tipos de índices:

  * De un solo campo
  * Compuestos
  * Multi-llave
  * Geoespaciales
  * De texto
  * _Hashed_



### Comentarios:

* **cirovladimir** (13)

	
	Para comparar la diferencia entre el rendimiento puedes utilizar el comando `explain('executionStats')`
	
	por ejemplo, en una colección de ejemplo `students` (la puedes [obtener acá](https://github.com/ozlerhakan/mongodb-json-files) e importar a atlas de acuerdo a [esta guía](https://docs.atlas.mongodb.com/import/mongoimport/)). Vamos a buscar los estudiantes cuyo nombre sea ‘Tandra Meadows’
	``` 
	    db.students.find({name: 'Tandra Meadows'}).explain('executionStats')
	    
	```
	
	en los resultados vas a encontrar `executionTimeMillis` y `totalDocsExamined`, en nuestro ejemplo los valores son 0 y 200 respectivamente. Este es un conjunto muy pequeño, por ello el tiempo de ejecución es irrelevante, pero el número de documentos examinados es **el total de elementos en la colección** (imagina 1 billón de registros 😱).
	
	ahora vamos a agregar un índice de tipo texto a nuestro campo y comparar los resultados haciendo una consulta que utilice este índice
	``` 
	    db.students.createIndex({name: 'text'})
	    db.students.find({$text: {$search: 'Tandra Meadows'}}).explain('executionStats')
	    
	```
	
	o dado que agregamos el índice de texto podemos utilizar solo un nombre y sin importar mayúsculas o minúsculas
	``` 
	    db.students.find({$text: {$search: 'tandra'}}).explain('executionStats')
	    
	```
	
	ahora el número de documentos examinados es de 2 solamente, genial! 😎
	
	* * *
	
	**bonus**
	
	Para hacer una consulta ‘parcial’, es decir, que incluya solo una parte del nombre -como en la clase cuando se busca `mongo` y no arroja resultados hasta que se utiliza `mongodb`\- podemos utilizar expresiones regulares (el operador $regex) sin importar las mayúsculas y minúsculas, case insensitive (/i), de la siguiente manera.
	``` 
	    db.cursos.find({nombre: {$regex: /mongo/i}})
	    
	```
	
	el detalle es que en la búsqueda de expresiones regulares no se utiliza el índice que creamos ☹️
	
	además el problema con los índices de texto es que si indexas varios campos los resultados de la búsqueda incluirán todos ellos, es decir, no puedes especificar el campo sobre el que se hará la búsqueda. En nuestro ejemplo, si agregamos un campo `tutor` con el nombre del tutor y creamos un índice de texto para este nuevo campo, al buscar los estudiantes nos incluirá también aquellos que tengan como tutor alguien llamado ‘Tandra’. Esto se puede resolver agregando un segundo filtro de tipo regex como se explica en el artículo compartido por @juandc
	
	[How to Speed-Up MongoDB Regex Queries by a Factor of up-to 10](https://medium.com/statuscode/how-to-speed-up-mongodb-regex-queries-by-a-factor-of-up-to-10-73995435c606)

	* **Rafael Andrés Cisneros Corro** (1)

		
		Excelent aporte, gracias.

	* **Abraham Gonzalez** (1)

		
		Al momento de ejecutar .explain(‘executionStats’) me retorna una seria de campos interesantes … mi duda es cual es la diferencia entre `executionTimeMillisEstimate` y `executionTimeMillis` ?

	* **Brayan Mamani** (1)

		
		Buen aporte de la clase.

* **Juan David Castro (Platzi)** (3)

	
	  * [Basic Indexing in MongoDB](https://medium.com/@dugdun/basic-indexing-in-mongodb-8e776a5eb108)
	  * [How to Speed-Up MongoDB Regex Queries by a Factor of up-to 10](https://medium.com/statuscode/how-to-speed-up-mongodb-regex-queries-by-a-factor-of-up-to-10-73995435c606)  
	_– Why can’t we just add an Index!? Text Indexes will Safe Us_
	  * [Query like A Pro — MongoDB Toolbox](https://codeburst.io/query-like-a-pro-mongodb-shell-toolbox-3c926cec4cbd)
	
	

* **andres-martinez578** (2)

	
	[db.py](http://db.py)
	
	def agregar_indice(index):  
	return dumps(db.cursos.create_index([(‘nombre’, TEXT)], name=‘search_index’,default_language=‘english’))
	
	Metodo para crear index desde pymongo

* **Cristian Fabian Tovar** (2)
como es el comando para importar los datos del cluster y que se vea la DB de “platzi” en la consola de mongo?

	* **fernandomunoz** (3)

		
		Desde la terminal te conectas al cluster de Atlas luego:
		
		  1. Miras las bases de datos disponibles
		
		
		``` 
		    show dbs
		    
		```
		
		  1. Seleccionas con cual vas a trabajar
		
		
		``` 
		    use nombre_db
		    
		```
		
		  1. Podes ver las colleciones
		
		
		``` 
		    show collections
		    
		```
		
		  1. Para mirar el contenido de una colección
		
		
		``` 
		    db.nombre_coleccion.find().pretty()
		    
		```
		
		Y listo con eso miras los datos del cluster.

* **David Santiago Pinchao Ortiz** (1)

	
	Los poderosos Indices

* **Juan Guillermo Perez Cardozo** (1)

	
	ok gracias.

* **dbzdavidbaez** (1)

	
	Entendido y es muy importante para un optimo rendimiento del aplicativo.

* **Cristhian Arce** (1)

	
	Desde el código de Python, cómo puedo identificar cuando la función retorna un bson envés de un json ?

* **José Alexander Guerra Tejada** (1)

	
	como puedo hacer para que en una consulta como la siguiente utilize indices ?  
	`db.topics.aggregate([ { $lookup: { from: 'profiles', localField: '_id', foreignField: 'topics', as: 'teachers' } }, { $match: { 'teachers.status': 5, 'teachers.stepsCompleted: true' } } ]),`

* **José Alexander Guerra Tejada** (1)

	
	los $lookup pueden contener indices ??

* **Luis Rangel Castro** (1)

	
	Codigo:
	``` 
	    from flask import Flask
	    from flask import request
	    from pymongo import MongoClient
	    from bson.json_util import dumps
	    from bson import ObjectId
	    import json
	    
	    # client = MongoClient('localhost:27017')
	    client = MongoClient(
	        'mongodb+srv://[usuario]:[clave]@curso-platzi-kuuzl.mongodb.net/test')
	    db = client.platzi
	    
	    app = Flask(__name__)
	    
	    
	    @app.route("/")
	    defhello():
	        return"Welcome to Python Flask! platzi-mongo2"
	    
	    # CREATE CARRERA
	    @app.route("/carreras", methods=['POST'])
	    defcreate_carrera():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                # status = db.carreras.insert_one(data)
	                # return dumps({'message' : 'SUCCESS'})
	                return dumps(db.carreras.insert_one(data).inserted_id)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ TODAS LAS CARRERAS
	    @app.route("/carreras", methods=['GET'])
	    defread_carrera():
	        try:
	            carreras = db.carreras.find()
	            return dumps(carreras)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ UNA CARRERA POR id
	    @app.route("/carreras/<id>", methods=['GET'])
	    defread_carrera_id(id):
	        try:
	            pageid = id
	            return dumps(db.carreras.find_one({'_id': ObjectId(pageid)}))
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # UPDATE CARRERA
	    @app.route("/carreras", methods=['PUT'])
	    defupdate_carrera():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            _id = data['_id']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                status = db.carreras.update_one({'_id': ObjectId(_id)}, {
	                                                '$set': {'nombre': nombre, 'descripcion': descripcion}})
	                return str(status.modified_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # DELETE UNA CARRERA POR id
	    @app.route("/carreras/<id>", methods=['DELETE'])
	    defdelete_carrera_id(id):
	        try:
	            pageid = id
	            status = db.carreras.delete_one({'_id': ObjectId(pageid)})
	            return str(status.deleted_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    
	    # home function
	    @app.route('/profile/<int:id>')
	    defmyProfile(id):
	        return'The project page ' + str(id)
	    
	    
	    # CREATE CURSO
	    @app.route("/cursos", methods=['POST'])
	    defcreate_curso():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            if nombre and descripcion:
	                # id = str(db.cursos.insert_one(data).inserted_id)
	                # return dumps({"_id":id})
	                return dumps(db.cursos.insert_one(data).inserted_id)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ TODAS LOS CURSOS
	    @app.route("/cursos", methods=['GET'])
	    defread_curso():
	        try:
	            cursos = db.cursos.find()
	            return dumps(cursos)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # READ UN CURSO POR id
	    @app.route("/cursos/<id>", methods=['GET'])
	    defread_curso_id(id):
	        try:
	            pageid = id
	            return dumps(db.cursos.find_one({'_id': ObjectId(pageid)}))
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # UPDATE CURSO
	    @app.route("/cursos", methods=['PUT'])
	    defupdate_curso():
	        try:
	            data = json.loads(request.data)
	            _id = data['_id']
	            nombre = data['nombre']
	            descripcion = data['descripcion']
	            # eliminar _id del JSON para que no genere un error al actualizar
	            del data['_id']
	            filtro = {'_id': ObjectId(_id)}
	            actualizar = {'$set': data}
	            if nombre and descripcion:
	                status = db.cursos.update_one(filtro, actualizar)
	                return str(status.modified_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # DELETE UN CURSO POR id
	    @app.route("/cursos/<id>", methods=['DELETE'])
	    defdelete_curso_id(id):
	        try:
	            pageid = id
	            status = db.cursos.delete_one({'_id': ObjectId(pageid)})
	            return str(status.deleted_count)
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    
	    defconsultar_curso_por_id_proyeccion(id_curso, proyeccion=None):
	        return db.cursos.find_one({'_id': ObjectId(id_curso)}, proyeccion)
	    
	    
	    # AGREGAR CURSO A CARRERA
	    @app.route("/carreras/agregar-curso", methods=['PUT'])
	    defadd_curso_to_carrera():
	        try:
	            data = json.loads(request.data)
	            curso = consultar_curso_por_id_proyeccion(
	                data['id_curso'], proyeccion={'nombre': 1})
	            return str(db.carreras.update_one({'_id': ObjectId(data['id_carrera'])}, {'$addToSet': {'cursos': curso}}).modified_count)
	    
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # REMOVER CURSO A CARRERA
	    @app.route("/carreras/agregar-curso", methods=['DELETE'])
	    defremove_curso_from_carrera():
	        try:
	            data = json.loads(request.data)
	            filtro = {'_id': ObjectId(data['id_carrera'])}
	            remove = {'$pull': {'cursos': {'_id': ObjectId(data['id_curso'])}}}
	            return str(db.carreras.update_one(filtro, remove).modified_count)
	    
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	    # CONSULTAR CURSO POR NOMBRE
	    @app.route("/cursos/porNombre", methods=['POST'])
	    deffind_curso_by_nombre():
	        try:
	            data = json.loads(request.data)
	            nombre = data['nombre']
	            myquery = {'$text': {'$search': nombre}}
	            if nombre:
	                return dumps(db.cursos.find(myquery))
	    
	        except Exception as e:
	            return dumps({'error': str(e)})
	    
	```

* **Joan Federico Marin Ruiz** (1)
que son los hashed?

	* **Wonder Jhonny Diaz Gonzalez** (2)

		
		Hola Fede,
		
		Un Hash es un algoritmo matemático que transforma cualquier bloque arbitrario de datos en una nueva serie de caracteres con una longitud fija. [Fuente](https://latam.kaspersky.com/blog/que-es-un-hash-y-como-funciona/2806/)
		
		Los índices hash mantienen entradas con hashes de los valores del campo indexado. [Documentación](https://docs.mongodb.com/manual/core/index-hashed/)

* **dbzdavidbaez** (1)
¿Como sabes si está utilizando el índice que creamos?

	* **Erika Hernández** (1)

		
		Hola! estuve leyendo y al parecer esto puede proveernos esa infomación:
		``` 
		    db.cursos.find({$text : {$search : "mongo"}} , {nombre : 1}).explain("executionStats")
		    
		```
		
		El “explain(‘executionStats’)” nos devuelve las estadísticas de la consulta.
		
		Mas información: [Measure index use](https://docs.mongodb.com/manual/tutorial/measure-index-use/)

# Recomendaciones para poner en producción tu cluster de Atlas

## 0240. Recomendaciones de Arquitectura y Paso a Producción

### Descripción:


  * Usar proveedores cloud con alta disponibilidad: AWS, Google Cloud o Azure son muy buenas opciones
  * No te compliques pensando en administración de servidores con MongoDB, servicios como MongoDB Atlas o mlab son muy buenas opciones
  * Guardar las credenciales en variables de entorno o archivos de configuración fuera del proyecto
  * Asegura que tu cluster se encuentra en la mis región del proveedor que tu aplicación
  * Has VPC _peering_ entre la VPC de tu aplicación y la VPC de tu cluster
  * Cuida la lista de IPs blancas
  * Puedes habilitar la autenticación en dos pasos
  * Actualiza constantemente tu versión de MongoDB
  * Separa los ambientes de desarrollo, test y producción
  * Habilita la opción de almacenamiento encriptado



### Links:

* [MongoDB Architecture | MongoDB | MongoDB](https://www.mongodb.com/mongodb-architecture)

### Comentarios:

* **Juan David Castro (Platzi)** (16)

	  * [14 Things I Wish I’d Known When Starting with MongoDB](https://www.infoq.com/articles/Starting-With-MongoDB)
	  * [Time Series Data and MongoDB: Part 2 – Schema Design Best Practices](https://www.mongodb.com/blog/post/time-series-data-and-mongodb-part-2-schema-design-best-practices)
	  * [Performance Best Practices for MongoDB](https://www.mongodb.com/collateral/mongodb-performance-best-practices)
	  * [What is MongoDB Sharding and the Best Practices?](https://geekflare.com/mongodb-sharding-best-practices/)
	
	

* **Juan Guillermo Perez Cardozo** (2)

	
	gracias por las recomendaciones de seguridad

* **ehnbytes** (1)

	
	Recomendaciones de seguridad!!

* **dbzdavidbaez** (1)

	
	Entendido y son buenas recomendaciones.

* **Manuel_Herrera** (1)

	
	Muy buenas recomendaciones de arquitectura !!

* **Brayan Mamani** (1)

	
	¡Muy buena recomendación la de utilizar proveedores cloud!

* **David Santiago Pinchao Ortiz** (1)
Que es el escalabilidad horizontal ?

	* **AryRosvall** (2)

		
		Se refiere a que Mongo puede agregar tantos servidores como necesite para soportar el tráfico a la base

## 0250. Nuestra base de datos en un cluster de producción

### Descripción:


### Comentarios:

* **Madrov** (5)

	
	El servicio de Atras es genial, la monitorización del uso, el acceso a las bases de datos, la fácil y segura administración de entornos de producción y muchos otros beneficios… quisiera saber ¿existen otros servicios cloud para mongo similar a atlas?, quiero hacer una comparación entre precios y servicios…

	* **svictoreq** (1)

		
		Podrías echar un vistazo a [mLab](https://mlab.com).

	* **Brayan Mamani** (1)

		
		 **@svictoreq** muy util tu aporte.

	* **Juan José Vega Quintero** (1)

		
		mLab ya no se usa, mongo atlas lo compro y lo integro en un solo servicio.

* **David Santiago Pinchao Ortiz** (1)

	
	Listo para empezar un proyecto en con Mongo como base de datos

* **Juan Guillermo Perez Cardozo** (1)

	
	lo mejor de cada servicio mencionado es la seguridad tan buena que ofrece , eso si sabiendola usar, como dice albert de nada sirve la whitelist si ponemos 0.0.0.0 osea que deje entrar a todo el que quiera.

* **Jose Arturo Enriquez Hurtado** (1)

	
	Muy bueno el servicio de Atlas.

* **dbzdavidbaez** (1)

	
	Muy interesante. La consola se ve bastante completa.

* **Gino Andrey Grimaldos Puerto** (1)
Tengo un inconveniente con el driver para c#, tengo Visual Studio 2019 y la pagina me dice que la conecion se realiza asi var mongoUrl = ...

# Conclusiones

## 0260. Resumen y Conclusiones

### Descripción:


¡Felicitaciones por terminar el Curso MongoDB en Platzi!

Aprendimos qué son, cómo funcionan, qué ventajas tienen y qué tipos de bases de datos NoSQL como MongoDB encontramos en el mercado. Programamos operaciones, agregaciones e índices con buenas prácticas para mejorar el _performance_ y crear una API REST con el CRUD de nuestro proyecto PlatziMongo, usamos la consola, la interfaz gráfica y nuestro lenguaje de programación favorito. Tambien, aprendimos cómo funcionan los drivers y los clusters en la arquitectura de nuestras aplicaciones.

Recuerda resolver los ejercicios, completar el examen, dejar 5 estrellitas y dejar tus dudas o comentarios en la sección de discusiones ????.

### Comentarios:

* **Juan David Castro (Platzi)** (6)

	
	  * [30 Best MongoDB Interview Questions and Answers](https://www.fullstack.cafe/blog/30-best-mongodb-interview-questions-and-answers)
	
	

	* **Ludwing Juan Homero Pérez Tzaquitzal** (1)

		
		Gracias!

	* **Johan_Marcel** (1)

		
		Awesome!

* **Jhonnattan Rivera** (3)

	
	me gusto el curso, aunque creeo que debio hacer ejemplos en la consola pura y no usando python. pero esta bien para comenzar. me gusto las bases con las que nos deja el curso, es un buen inicio al mundo de las bases de datos no relacionales.

* **Ludwing Juan Homero Pérez Tzaquitzal** (3)

	
	Buen curso, pero habría sido mejor profundizar en temas propios y un poco más avanzados de mongo y no tanto en la creación de una API en flask pero igual me parece excelente el contenido y el profesor

* **Abraham Gonzalez** (3)

	
	Les dejo una Workbook por [aquí](http://nicholasjohnson.com/mongo/course/workbook/) para que practiquen y conozcan más a fondo sobre mongodb, a mi en lo personal me ayudo mucho…

	* **Ludwing Juan Homero Pérez Tzaquitzal** (1)

		
		Que buen aporte, gracias!

* **Argueta Broddy** (2)

	
	Buen curso, espero el avanzado para este año 2020.

* **ehnbytes** (1)

	
	Buen curso de MongoDB!!!

* **Abril Darynka Tapia Sosa** (1)

	
	Espero se cree un curso de MongoDB avanzado para aprender más

* **dbzdavidbaez** (1)

	
	Buen curso para empezar en este entorno de base de datos.  
	Deberían crear un curso más avanzado.

* **Manuel_Herrera** (1)

	
	Un gustazo !!

* **raulandres13** (1)

	
	Muy buen curso, gran profesor !

* **Brayan Mamani** (1)

	
	¡Fue un gusto tomar este curso!

* **everthpintadobellido** (1)

	
	consulta si quiero hacer un modelado de base de datos relaciona o no racional l , me podria ayudar de una plantilla ya hecha o hacerlo desde cero ?, porque ahi visto que lo sacan del libro THE DATA MODEL es asi o me equivoco ?

* **Luis Rangel Castro** (1)

	
	Excelente Curso!

* **Wandy Rafael Santana Evangelista** (1)

	
	Excelente curso.

* **Jonathan Campos Lozano** (1)
Tengo una base de datos en MongoDB pero necesito realizar una migración a una base relacional en Postgres. Donde puedo encontrar document...

	* **Juan Carlos Pinzón** (1)

		
		Uy amigo, una migración así automatizada no creo que halles una herramienta que te ayude, ya que MongoDB no tiene tipos de datos definidos ni una estructura fija. En este caso te toca hacerlo manualmente. Yo lo haría así:
		
		  * Defino la estructura de la BD en Postgres, campos y sus tipos de datos.
		  * Hago una exportación de los datos desde MongoDB en archivos separados por coma (,) o punto y coma como guste, teniendo en cuenta que una columna es un solo dato y no un objeto. Esta estructura de columnas en los CSV debe ser igual al de Postgres.
		  * Hacer una carga masiva de estos CSV en Postgres.
		
		
		
		Una migración así literal pues no se que tan conveniente sería

* **Adrian Gil Duque** (1)
Estoy trabajando con Atlas y no tengo claridad de qué son las conexiones.(Connections), en el clúster ni cuáles son las mejores prácticas...

