[Curso de Bases de Datos en AWS 1426](https://platzi.com/cursos/db-aws)

# Introducción [2918]

## 0010. Introducción [15205](https://platzi.com/clases/1426-db-aws/15205-introduccion7769/)

### Descripción:


Bienvenido al **Curso de Bases de Datos en AWS** de Platzi. Vamos a aprender sobre los servicios de bases de datos relacionales en AWS, principalmente el servicio de **RDS** , y sobre el servicio de bases de datos no relacionales en AWS: **DynamoDB**.

Esta vez nuestro profesor será Carlos Andrés Zambrano, que tiene más de 4 años de experiencia trabajando con AWS.

### Comentarios:

* **Juan David Castro (Platzi)** (5) [428962](https://platzi.com/comentario/428962/) 

	Antes de tomar este curso podemos aprender las bases de AWS y sus servicios más utilizados con el [Curso de Fundamentos de AWS Cloud](https://platzi.com/clases/aws-cloud/) 😬.

	* **Brayan Mamani** [428962] (1)

		Si la mejor opción.

* **Nestor Alfonso Portela Rincón** (3) [499940](https://platzi.com/comentario/499940/) 

	El mejor profesor de AWS

* **Jean Carlos Nuñez Hernandez** (2) [428284](https://platzi.com/comentario/428284/) 

	RDS -> Relacional y DynamoDB -> No relacional

* **oscarjulian_** (1) [1100119](https://platzi.com/comentario/1100119/) 

	Perfecto, espero aprender mucho!!!

* **jaimealbertoduarteluquerna** (1) [1060667](https://platzi.com/comentario/1060667/) 

	Saludos!!  
	Encantado de seguir progresando

* **miguelangelpglez** (1) [1009865](https://platzi.com/comentario/1009865/) 

	Que gusto!

* **Dante Castillo Z.** (1) [997933](https://platzi.com/comentario/997933/) 

	A darle ahora a la SQL!

* **Jean Carlos Nuñez Hernandez** (1) [981445](https://platzi.com/comentario/981445/) 

	vamos pues sql

* **Diego Restrepo leal** (1) [960791](https://platzi.com/comentario/960791/) 

	Muy interesante

* **johncastillotellez7** (1) [954616](https://platzi.com/comentario/954616/) 

	excelente Profesor.

	* **johncastillotellez7** [954616] (1)

		relacionales RDS  
		nosqlDynamo DB

* **Juan José Giraldo Jiménez** (1) [941475](https://platzi.com/comentario/941475/) 

	De qué sirve el curso si igual no tengo acceso a AWS porque es de ago

	* **juancajamarca** [941475] (1)

		Sólo pagas por lo que utilices.

# Introducción a RDS [2922]

## 0020. Características de Relational Database Service (RDS) [15229](https://platzi.com/clases/1426-db-aws/15229-caracteristicas-de-relational-database-service-rds/)

### Descripción:


RDS _(Relational Database Service)_ es un servicio de AWS enfocado a bases de datos relacionales con compatibilidad a 6 motores de bases de datos: Amazon Aurora, MySQL, MariaDB, PostgreSQL, Oracle y Microsoft SQL Server, cada uno con sus características, integraciones y limitaciones.

Entre sus características principales podemos destacar los **backups automáticos** con un tiempo de retención de hasta 35 días, es decir, si encontramos algún problema con nuestras bases de datos podemos restablecerlas a la hora, minuto y segundo que necesitemos dentro del periodo de retención. Recuerda que por defecto este periodo es de 7 días. También tenemos la opción de hacer **backups manuales** , podemos tomar **snapshots** manuales en cualquier momento si nuestra aplicación lo necesita. Además, AWS por defecto tomará un _snapshot_ final de nuestras bases de datos antes de eliminarlas, así podremos restablecerla si tenemos algún inconveniente.

Todas las bases de datos relacionales utilizan un **sistema de almacenamiento** , si la carga de lectura y escritura son constantes, el sistema _General Purpose_ funciona muy bien, sin embargo, podemos utilizar el sistema _Provisioned Storage_ cuando requerimos de altas cantidades de consumo y operaciones de disco.

_RDS_ es un sistema completamente administrado, esto quiere decir que AWS reduce nuestra carga operativa automatizando muchas tareas de nuestra base de datos, por ejemplo, las actualizaciones. A nivel de seguridad contamos con muchas opciones, una de ellas es la posibilidad de encriptar nuestra base de datos para que solo nosotros y las personas o roles que especifiquemos tengan acceso.

También tenemos integración con otros servicios de AWS, por ejemplo, _IAM_ para administrar a los usuarios, roles, grupos y políticas de conexión a la base de datos por medio de tokens con máximo 20 conexiones por segundo _(recomendado para escenarios de prueba)_ , o la integración de _Enhanced monitoring_ para hacer monitoreo en tiempo real nuestras bases de datos _(recuerda que además de subir el precio, no está disponible para instancias small)_.

### Links:

* [https://docs.aws.amazon.com/rds/index.html](https://docs.aws.amazon.com/rds/index.html)

### Comentarios:

* **Franco Agustín Torres** (5) [430368](https://platzi.com/comentario/430368/) 

	¿Motor de base de datos vendría a hacer lo mismo que gestor de base datos?

	* **Arjun4_0** [430368] (12)

		No. Un gestor de bd es un software que las administra. Ej.: SQL Management Studio, Toad, Heidi SQL, etc.  
		Un motor de bd es: SQL Server, MySQL, MongoDB (bd no-sql), etc.

	* **Carlos Andrés Zambrano Barrera** [430368] (3)

		Gracias por la aclaración Arjun4_0, de acuerdo con tus comentarios.

* **jorge-gianareas** (3) [967009](https://platzi.com/comentario/967009/) 

	También tenemos integración con otros servicios de AWS, por ejemplo, IAM para administrar a los usuarios, roles, grupos y políticas de conexión a la base de datos por medio de tokens con máximo 20 conexiones por segundo (recomendado para escenarios de prueba), o la integración de Enhanced monitoring para hacer monitoreo en tiempo real nuestras bases de datos (recuerda que además de subir el precio, no está disponible para instancias small).

* **juancajamarca** (2) [985494](https://platzi.com/comentario/985494/) 

	* **IAM:** Usa tokens para conexión a la BD. 10 a 20 conexiones por segundo. Si se van a tener cargas mayores, no se debería usar esta integración. Es recomendable para escenarios de pruebas o ambientes donde la concurrencia sea muy pequeña a la Base de datos; sin embargo, es muy importante tener en cuante que
	
	* **Monitorio:** Enhanced monitoring (tiempo real) (aumenta el pricing) No disponible para instancias small.
	
	* **Precio:** Tipo y tamaño de la instancia. Monitoreo y Configuración.
	
	* Oracle: Sólo se puede tener una BD por instancia.
	
	* SQLServer: Hasta 30 por instancia.
	
	* PostgreSQL, MariaDB o MySQL, se podrán tener BDs completamente ilimitada.
	
	
	

* **johncastillotellez7** (2) [970280](https://platzi.com/comentario/970280/) 

	interesante que los updates los pueda hacer mismo AMAzon muy utili esa opcion

* **jorge-gianareas** (2) [967008](https://platzi.com/comentario/967008/) 

	RDS es un sistema completamente administrado, esto quiere decir que AWS reduce nuestra carga operativa automatizando muchas tareas de nuestra base de datos, por ejemplo, las actualizaciones. A nivel de seguridad contamos con muchas opciones, una de ellas es la posibilidad de encriptar nuestra base de datos para que solo nosotros y las personas o roles que especifiquemos tengan acceso.

* **jorge-gianareas** (2) [967007](https://platzi.com/comentario/967007/) 

	odas las bases de datos relacionales utilizan un sistema de almacenamiento, si la carga de lectura y escritura son constantes, el sistema General Purpose funciona muy bien, sin embargo, podemos utilizar el sistema Provisioned Storage cuando requerimos de altas cantidades de consumo y operaciones de disco.

* **jorge-gianareas** (2) [967006](https://platzi.com/comentario/967006/) 

	Entre sus características principales podemos destacar los backups automáticos con un tiempo de retención de hasta 35 días, es decir, si encontramos algún problema con nuestras bases de datos podemos restablecerlas a la hora, minuto y segundo que necesitemos dentro del periodo de retención. Recuerda que por defecto este periodo es de 7 días. También tenemos la opción de hacer backups manuales, podemos tomar snapshots manuales en cualquier momento si nuestra aplicación lo necesita. Además, AWS por defecto tomará un snapshot final de nuestras bases de datos antes de eliminarlas, así podremos restablecerla si tenemos algún inconveniente.

* **jorge-gianareas** (2) [967004](https://platzi.com/comentario/967004/) 

	RDS (Relational Database Service) es un servicio de AWS enfocado a bases de datos relacionales con compatibilidad a 6 motores de bases de datos: Amazon Aurora, MySQL, MariaDB, PostgreSQL, Oracle y Microsoft SQL Server, cada uno con sus características, integraciones y limitaciones.

* **ximart** (1) [994902](https://platzi.com/comentario/994902/) 

	La ventaja es que las actualizaciones, encryptación y backup lo hace el mismo AWS

* **jorge-gianareas** (1) [967012](https://platzi.com/comentario/967012/) 

	<https://docs.aws.amazon.com/rds/index.html>

* **Joan Federico Marin Ruiz** (1) [86780](https://platzi.com/comentario/1104371/) 
buenas. a que se refiere cuando dice “instancias”?

	* **Juan David Castro (Platzi)** [86780] (1)

		> _Una instancia de base de datos se puede concebir como un entorno en la nube con los recursos informáticos y de almacenamiento que especifique. Puede crear instancias de bases de datos y eliminarlas, definir los atributos de infraestructura de las instancias, ajustarlos y controlar el acceso y la seguridad a través de la consola de administración de AWS, las API de Amazon RDS y la interfaz de línea de comandos de AWS. Puede ejecutar una o varias instancias de bases de datos, y cada una de ellas puede admitir una o varias bases de datos o esquemas de bases de datos, según el tipo de motor._
		
		Aquí encuentras la información muy bien explicada:
		
		* <https://aws.amazon.com/es/rds/faqs/#Database_Instances>
		* <https://aws.amazon.com/es/rds/instance-types/>
		
		

## 0030. Desplegando nuestra primer base de datos [15227](https://platzi.com/clases/1426-db-aws/15227-desplegando-nuestra-primer-base-de-datos/)

### Descripción:


### Comentarios:

* **johncastillotellez7** (2) [970384](https://platzi.com/comentario/970384/) 

	muy interesante los diferentes engines de DBSs. al igual sale el tema de importar DBs existentes. que permite Aws.

* **Nestor Alfonso Portela Rincón** (2) [499964](https://platzi.com/comentario/499964/) 

	Si yo no publico la base de datos, esta solo la puedo acceder por ejemplo desde una instancia EC2 teniendo en cuenta que esa instancia tiene dos direcciones ip, una publica de internet y una ip que es propia de la red de AWS. estoy en lo correcto?

	* **Camilo Ortegón** [499964] (3)

		Así es, si la base de datos no es pública no se podrá acceder por fuera del VPC. Tu instancia de EC2 puede acceder porque está en la misma subred y accede por su IP privada.

	* **Nestor Alfonso Portela Rincón** [499964] (1)

		Gracias @cjortegon, justo acabo de ver un vídeo en un nuevo curso de AWS donde se hizo exactamente eso, aunque el acceso se dio de una instancia EC2 que si era publica desde internet y desde ella se accedio a la EC2 que no lo era. saludos

	* **andresguerrerf5134f1227214204** [499964] (2)

		hola en que curso esta esa informacion?

	* **johan2732** [499964] (1)

		el curso de fundamentos de aws cloud

* **DrHarrys** (2) [483827](https://platzi.com/comentario/483827/) 

	explicas luego como crear el VPC correctamente?

	* **Nestor Alfonso Portela Rincón** [483827] (6)

		En el menú de “NETWORK & SECURITY” está la opción de “Security Groups” y ahí es donde creas tu VPC con la configuración que necesitas.

	* **johan2732** [483827] (3)

		Hay un curso que tiene la explicación de vpc curso de nertworking y content delivery en AWS

* **Arturo Flores** (1) [641415](https://platzi.com/comentario/641415/) 

	Hay alguna manera de generar una base de datos para el caso ahora que estoy aprendiendo que no me genere un costo?

	* **Diego Alexander Forero Higuera (Platzi)** [641415] (3)

		Hola, si activas el free tier de aws tiene 750 horas de RDS mensual en una instancia t2.micro suficiente para hacer las pruebas del curso.

* **edisoncastro14** (1) [452272](https://platzi.com/comentario/452272/) 

	¿Cuál es la mejor forma de crear una copia de un sistema productivo para utilizarlo en ambientes de pruebas?

	* **Carlos Andrés Zambrano Barrera** [452272] (2)

		Puedes hacerlo por snapshot y reestableces el snap en otra instancia, o en restore en otra BD.

	* **jsteven** [452272] (1)

		Muy importante que en las tareas de replicación de producción a laboratorio ofusques los datos sensibles de tus clientes.

	* **johncastillotellez7** [452272] (1)

		snapshot es una buena opcion de utilizar o backups de manera incremental en caliente.(osea funcionando) y encriptar los datos sensibles

* **Mario Alonso Ruiz Garcia** (1) [75453](https://platzi.com/comentario/870128/) 
Se que no es mucho del tema de esta clase mi duda, pero recientemente RDS lanzo una actualización en los certificados SSL/TLS, alguien sa...

* **raimercm** (1) [68844](https://platzi.com/comentario/747141/) 
Habilitar el Backup automatico y las actualizaciones “minor version” ¿Generan costos adicionales?

	* **Carlos Andrés Zambrano Barrera** [68844] (2)

		El autominor no tiene costo. el periodo de retención si aumenta el costo, dependiendo del tamaño de tu BD.  
		El almacenamiento de copias de seguridad adicional para su almacenamiento de base de datos aprovisionado se cobra 0,095 USD USD por GiB al mes. Mayor info aca --> [https://aws.amazon.com/es/rds/mysql/pricing/?pg=pr&loc=2](https://aws.amazon.com/es/rds/mysql/pricing/?pg=pr&loc=2)

* **Juan Rafael De Leon Osorio** (1) [62556](https://platzi.com/comentario/642237/) 
Si creo una instancia rds micro de capa gratuita, y me quedo chico y no soporta mas conexiones, como hago para cambiar de instancia? Y su...

	* **memowii** [62556] (1)

		Lo más rápido que se me ocurre es que borres esa instancia que creaste y vuelvas a realizar el proceso de crear otra, solo que al crear esta nueva instancia elejirías una instancia que cumpla con tus necesidades. Pero hay que aclarar que esta nueva instancia no es gratis, y tendrías que checar el _pricing_ que ofrecen estás.

* **Nestor Alfonso Portela Rincón** (1) [52059](https://platzi.com/comentario/499964/) 
Si yo no publico la base de datos, esta solo la puedo acceder por ejemplo desde una instancia EC2 teniendo en cuenta que esa instancia ti...

	* **Camilo Ortegón** [52059] (3)

		Así es, si la base de datos no es pública no se podrá acceder por fuera del VPC. Tu instancia de EC2 puede acceder porque está en la misma subred y accede por su IP privada.

* **Estefymine** (0) [733778](https://platzi.com/comentario/733778/) 

	como se puede migrar una bd mysql local a RDS?

	* **Nestor Alfonso Portela Rincón** [733778] (3)

		Claro que si, no hay problema con eso.

	* **paisa** [733778] (1)

		Calculo que haces un dump de la base local. Te conectas a la base remota e importas el dump.

	* **juancajamarca** [733778] (1)

		Claro, eso lo hacen todo el tiempo. Simplemente le haces un dump a tu base de datos local, luego te conectas a la que tienes en AWS, y haces un restore con el dump. Eso es todo, sencillo.

## 0040. Conexión gráfica a nuestra base de datos [15210](https://platzi.com/clases/1426-db-aws/15210-conexion-grafica-a-nuestra-base-de-datos/)

### Descripción:


En esta clase vamos a conectarnos a la base de datos que creamos en la clase anterior usando la herramienta _MySQL Workbench_ , que nos permite ejecutar y visualizar nuestros comandos muy fácilmente.

Cuando utilizamos el servicio _RDS_ con el motor de MySQL podemos crear multiples bases de datos con un solo _endpoint_ _(una sola conexión)_ , ya que entre las características de este motor encontramos la cantidad de bases de datos ilimitada. Obviamente, debemos tener en cuenta que nuestras instancias deberían soportar la cantidad de bases de datos que vamos a utilizar, y las herramientas de monitoreo nos pueden ayudar a medir esta relación de tamaño y rendimiento.

Recuerda que si necesitamos un permiso de usuarios diferente para cada base de datos vamos a necesitar configuraciones diferentes en las _keys_ _(llaves de acceso)_ de nuestra instancia.

### Links:

* [MySQL :: MySQL Workbench](https://www.mysql.com/products/workbench/)

### Comentarios:

* **Vicente Fernandez** (3) [1011506](https://platzi.com/comentario/1011506/) 

	Una pregunta, he creado una instancia con la capa gratuita (la mas pequeña), que pasará cuando termine mi período gratuito de 12 meses en AWS? Me cobrarán?

	* **oort3ga** [1011506] (1)

		Si, empezara a cobrar el uso de la base de datos a partir del pricing de la instancia.

* **mrhacker** (3) [957614](https://platzi.com/comentario/957614/) 

	En mi experiencia, DBeaver me ha ayudado mucho, puedes conectarte a cualquier base de datos (Mysql, Postgres, Teradata, Oracle, RDS, Athena, RedShift, etc) se los recomiendo, así no tendrán que instalar un software para cada motor.

	* **Wilmer Quintero Varela** [957614] (1)

		Yo también lo uso y me parece muy bueno

* **jorge-gianareas** (2) [967016](https://platzi.com/comentario/967016/) 

	Cuando utilizamos el servicio RDS con el motor de MySQL podemos crear multiples bases de datos con un solo endpoint (una sola conexión), ya que entre las características de este motor encontramos la cantidad de bases de datos ilimitada. Obviamente, debemos tener en cuenta que nuestras instancias deberían soportar la cantidad de bases de datos que vamos a utilizar, y las herramientas de monitoreo nos pueden ayudar a medir esta relación de tamaño y rendimiento.

* **jorge-gianareas** (2) [967015](https://platzi.com/comentario/967015/) 

	En esta clase vamos a conectarnos a la base de datos que creamos en la clase anterior usando la herramienta MySQL Workbench, que nos permite ejecutar y visualizar nuestros comandos muy fácilmente.

* **jsteven** (2) [567393](https://platzi.com/comentario/567393/) 

	En un entorno de desarrollo conviene crear una VPN entre la red de tu empresa con la VPC de AWS y en los grupos de seguridad configura la entrada para los rangos de IP de tu equipo de desarrollo.

* **Juan David Castro (Platzi)** (2) [428960](https://platzi.com/comentario/428960/) 

	Notas de la clase:
	
	* Herramientas como [MySQL Workbench](https://www.mysql.com/products/workbench/) nos dan una interfaz gráfica que muchas veces resulta más cómoda que la terminal de comandos, sobretodo para los comandos normales de añadir y borrar tablas 🌿.
	* Podemos crear bases de datos ilimitadas utilizando el motor de MySQL, pero nuestra instancia debe soportar la cantidad que vamos a utilizar para no bajar el rendimiento 🐸🍟.
	* Para dar permisos a usuarios diferentes por cada base de datos de la misma instancia vamos a necesitar una configuración especial de las llaves de acceso 🔑. ¿Veremos cómo se hace en alguna clase? 😅
	
	

	* **Fernando Trasvent** [428960] (2)

		El tema de llaves de acceso se ve con detalle en el curso de Storage

	* **Carlos Andrés Zambrano Barrera** [428960] (1)

		Lo podemos hacer pero el endpoint será el mismo, se pueden crear BD y usuarios asociados a esa bd. <https://stackoverflow.com/questions/10198367/creating-a-new-mysql-user-in-amazon-rds-environment>

* **Jean Carlos Nuñez Hernandez** (1) [981471](https://platzi.com/comentario/981471/) 

	Workbench es muy client graph para mysql

* **johncastillotellez7** (1) [970431](https://platzi.com/comentario/970431/) 

	importante nota> si necesitamos un permiso de usuarios diferente para cada base de datos vamos a necesitar configuraciones diferentes en las keys (llaves de acceso) de nuestra instancia.
	
	gracias Profe

	* **johncastillotellez7** [970431] (2)

		1 copy end point address  
		use my sqlworkbench/ sqldeveloper , toad for oracle  
		2- new connection hostname (endpoint  
		3 test connection-pwd -port 3306  
		4logged into the db  
		5 if needed create multiple databases.  
		6-use monitoring.  
		7 create table  
		etc normal steps when creating a db.

	* **johncastillotellez7** [970431] (1)

		DB ======== Visual tool for db managements

* **jorge-gianareas** (1) [967017](https://platzi.com/comentario/967017/) 

	Recuerda que si necesitamos un permiso de usuarios diferente para cada base de datos vamos a necesitar configuraciones diferentes en las keys (llaves de acceso) de nuestra instancia.

* **adriannava** (1) [750018](https://platzi.com/comentario/750018/) 

	Como puedo configurar un security group para que tenga acceso desde internet?

	* **juancajamarca** [750018] (2)

		Inbound rules: 0.0.0.0/0::0

* **johan2732** (1) [527191](https://platzi.com/comentario/527191/) 

	Pero para este ejemplo se podría usar otra base de datos?

	* **ebar0n (Platzi)** [527191] (3)

		Hola, si puedes usar otra base de datos, pero debes tener en cuenta que el programa de conexión gráfica debe ser el compatible con el del motor de base de datos que uses.
		
		Por ejemplo: postgresql y pgadmin

	* **johan2732** [527191] (1)

		Si, a mi el tema del costo es el que más me preocupa porque no sé como manejar si me cobran o no, dependiendo el tipo de base, es mas por eso

	* **Carlos Andrés Zambrano Barrera** [527191] (2)

		Este software es gratis, de acuerdo con ebar0n para postgresql puedes usa pgadmin o hay diferentes software que hacen lo mismo.

* **Juan David Castro (Platzi)** (1) [428961](https://platzi.com/comentario/428961/) 

	¿También podemos crear bases de datos ilimitadas con MariaDB?

	* **Carlos Andrés Zambrano Barrera** [428961] (1)

		Si senor!

* **johan2732** (1) [54228](https://platzi.com/comentario/527191/) 
Pero para este ejemplo se podría usar otra base de datos?

	* **ebar0n (Platzi)** [54228] (3)

		Hola, si puedes usar otra base de datos, pero debes tener en cuenta que el programa de conexión gráfica debe ser el compatible con el del motor de base de datos que uses.
		
		Por ejemplo: postgresql y pgadmin

## 0050. Creación de una tabla [15213](https://platzi.com/clases/1426-db-aws/15213-creacion-de-una-tabla/)

### Descripción:


### Comentarios:

* **Jesús Alejandro Rodríguez** (2) [828437](https://platzi.com/comentario/828437/) 
En el min 1:27, creo que lo que genera no es una consulta, sino el script de la creación de la tabla.

	* **eayala** [828437] (1)

		utiliza el asistente para realizarlo

* **Jean Carlos Nuñez Hernandez** (1) [983152](https://platzi.com/comentario/983152/) 

	con el client grafico es muy facil

* **Jean Carlos Nuñez Hernandez** (1) [981508](https://platzi.com/comentario/981508/) 

	Waao desde local hasta RDS con mysql podemos hacer la creacion de la base de datos

* **johncastillotellez7** (1) [970597](https://platzi.com/comentario/970597/) 

	interesante auqne basic

	* **juancajamarca** [970597] (1)

		Hazlo complejo.

## 0060. Conexión por consola a nuestra base de datos [15217](https://platzi.com/clases/1426-db-aws/15217-conexion-por-consola-a-nuestra-base-de-datos/)

### Descripción:


En esta clase vamos a conectarnos a nuestra base de datos por medio del bash de Linux. Para esto, debemos crear la instancia de un servidor de AWS con un grupo de seguridad que posteriormente vamos a configurar para que la base de datos y el servidor sean accesibles entre ellos.

El desafió de esta clase es identificar al menos 2 características de _RDS_ que actualmente no tenemos en otros sistemas bases de datos.

### Comentarios:

* **Cristian David Franco Garcia** (4) [655113](https://platzi.com/comentario/655113/) 

	Solo es necesario crear una regla a nivel de grupos de seguridad: Creamos una regla en el Security Group de la instancia de RDS, para que la instancia EC2 pueda acceder a la base de datos.

* **estebanvasquezvalencia** (3) [488240](https://platzi.com/comentario/488240/) 

	¿Es necesario crear las reglas de entrada tanto en la instancia EC2 como en RDS?

	* **DiegoRP** [488240] (1)

		La verdad es que si está extraña esa parte. Normalmente solo se necesitaría la comunicación desde el jumphost hacia la BD. No veo muy clara la razón para permitir el tráfico desde la BD hacia el jumphost.

	* **Juan Emmanuel Díaz** [488240] (1)

		No es necesario, yo le saque esa regla y va re bien.  
		Para entender esto hay que saber un poco como funciona la comunicacion en este caso, en capa 4, llega una peticion con puerto origen (puerto dinamico) y puerto destino(puerto registrado) al servidor de mysql, luego cuando vuelve, se invierte el orden y se coloca en el puerto destino el puerto origen y en el puerto origen el destino.

	* **Cristian David Franco Garcia** [488240] (2)

		Solo es necesario crear una regla a nivel de grupos de seguridad: Creamos una regla en el Security Group de la instancia de RDS, para que la instancia EC2 pueda acceder a la base de datos.

	* **Carlos Andrés Zambrano Barrera** [488240] (1)

		Ten presente que tienes 2 capas de seguridad  
		1- security group – stateful  
		2- nacl – stateless
		
		Debes crear en la rds de ingreso desde el sg de ec2.

	* **Emerson Cedeño Salazar** [488240] (1)

		qué interesante!, acabo de probarlo, y sí!, únicamente necesité agregar la **regla inbound en el RDS para el EC2** … para qué servirá o cuál sería el propósito de la regla inversa? 🤔

* **johncastillotellez7** (2) [980745](https://platzi.com/comentario/980745/) 

	En esta clase vamos a conectarnos a nuestra base de datos por medio del bash de Linux. Para esto, debemos crear la instancia de un servidor de AWS con un grupo de seguridad que posteriormente vamos a configurar para que la base de datos y el servidor sean accesibles entre ellos.
	
	El desafió de esta clase es identificar al menos 2 características de RDS que actualmente no tenemos en otros sistemas bases de datos.
	
	interesting

	* **johncastillotellez7** [980745] (3)

		Para lograr el tráfico entre una instancia EC2 y una BD RDS; se hace mediante sus Security Groups de cada uno, que al momento que se crean se personalizan.
		
		Cuando se crea la instancia EC2 en su Security Groups se personaliza para que conexión por el puerto SSH y desde la SourceMy IP y se crea una llave pem que luego os servira para conectar por medio de la terminal.
		
		Permitir que el Security Groups de BD RDS pueda ser accedida desde la instancia EC2 copiando el Group ID (el Security Groups de la BD tiene como parametros Type: MYSQL/Aurora - Protocol:TCP - Port Range: 3306 - Source: Custum[Su IP/32]), del EC2 se hace creando una nueva regla Security Groups de BD RDS, en la pestaña de InboundType: MYSQL/Aurora - Protocol:TCP - Port Range: 3306 - Source: Custom - Group ID[de EC2]  
		Permitir que el Security Groups de EC2 pueda ser accedida desde la instancia BD RDS copiando el Group ID de RDS (el Security Groups de EC2 tiene como parametros Type: SSH - Protocol:TCP - Port Range: 22 - Source: Custum[Su IP/32]), del RDS se hace creando una nueva regla Security Groups de EC2, en la pestaña de InboundType: MYSQL/Aurora - Protocol:TCP - Port Range: 3306 - Source: Custom - Group ID[de RDS]

* **jorge-gianareas** (2) [967019](https://platzi.com/comentario/967019/) 

	El desafió de esta clase es identificar al menos 2 características de RDS que actualmente no tenemos en otros sistemas bases de datos.

* **jorge-gianareas** (2) [967018](https://platzi.com/comentario/967018/) 

	En esta clase vamos a conectarnos a nuestra base de datos por medio del bash de Linux. Para esto, debemos crear la instancia de un servidor de AWS con un grupo de seguridad que posteriormente vamos a configurar para que la base de datos y el servidor sean accesibles entre ellos.

* **paisa** (2) [882056](https://platzi.com/comentario/882056/) 

	RDS me permite monitorear facilmente la DB. RDS me permite facilmente cambiar el tipo de instancia en la que esta corriendo la DB.

* **Rodolfo Nicacio Ugalde Ochoa** (2) [782847](https://platzi.com/comentario/782847/) 

	Para lograr el tráfico entre una instancia **EC2** y una BD **RDS** ; se hace mediante sus **Security Groups** de cada uno, que al momento que se crean se personalizan.
	
	Cuando se crea la instancia **EC2** en su **Security Groups** se personaliza para que conexión por el puerto `SSH` y desde la **Source**`My IP` y se crea una llave **pem** que luego os servira para conectar por medio de la terminal.
	
	  1. Permitir que el **Security Groups** de BD **RDS** pueda ser accedida desde la instancia **EC2** copiando el `Group ID` ( _el **Security Groups** de la BD tiene como parametros Type: MYSQL/Aurora - Protocol:TCP - Port Range: 3306 - Source: Custum[Su IP/32]_), del **EC2** se hace creando una nueva regla **Security Groups** de BD **RDS** , en la pestaña de **Inbound**`Type: MYSQL/Aurora - Protocol:TCP - Port Range: 3306 - Source: Custom - Group ID[de EC2]`
	  2. Permitir que el **Security Groups** de **EC2** pueda ser accedida desde la instancia BD **RDS** copiando el `Group ID` de **RDS** ( _el **Security Groups** de **EC2** tiene como parametros Type: SSH - Protocol:TCP - Port Range: 22 - Source: Custum[Su IP/32]_), del **RDS** se hace creando una nueva regla **Security Groups** de **EC2** , en la pestaña de **Inbound**`Type: MYSQL/Aurora - Protocol:TCP - Port Range: 3306 - Source: Custom - Group ID[de RDS]`
	
	

* **Mati Beltramone** (2) [509741](https://platzi.com/comentario/509741/) 

	Gracias por el contenido me fue de utilidad para entender los security groups +1

* **Geoscar** (1) [1070774](https://platzi.com/comentario/1070774/) 

	Primera diferencia encontrada: todo es totalmente nuevo para mi, he manejado BD con otras herramientas, pero no un protocolo SSH (que tuve que leer, para saber de que se trataba) y asi con varios términos. Así que por lo demás, todo son diferencias.

* **Vicente Fernandez** (1) [1011531](https://platzi.com/comentario/1011531/) 

	Pude acceder a la base de datos sin tener que crear la instancia en EC2. En la terminal ingresé los datos: mysql -h (el endpoint aquí) -P 3306 -u platziuser -p (la contraseña) y listo… Para qué sirve crear la instancia en EC2? Disculpen si la pregunta está fuera de lugar, apenas me estoy iniciando en este mundo.

	* **Winston Barbosa** [1011531] (2)

		Habitualmente se tiene una capa de aplicación (Frontend) que es la que gestiona las consultas sobre la base de datos, o lo que ven los usuarios finales; idealmente deberían estar en la misma VPC, por temas de velocidad y latencia. Por otra parte es un buen ejemplo de como debemos manejar los grupos de seguridad.

* **juancajamarca** (1) [985619](https://platzi.com/comentario/985619/) 

	La segunda regla de seguridad era innecesaria 😃

* **Jean Carlos Nuñez Hernandez** (1) [983169](https://platzi.com/comentario/983169/) 

	La consola es mucha mas poderosa, ligera y versatil que las demas opciones para interactuar con los RDS

* **Juan Sebastian Piedrahita Gonzalez** (1) [690420](https://platzi.com/comentario/690420/) 

	Jumpbox

* **hanuman80** (1) [569258](https://platzi.com/comentario/569258/) 

	RDS me permite la replicación global mas fácilmente que con una solución on premise. RDS me quita la carga de la administración del motor de base de datos.

* **Nestor Alfonso Portela Rincón** (1) [499985](https://platzi.com/comentario/499985/) 

	Yo me podría conectar a esa base de datos desde mi computador local haciendo uso del endpoint como host de la base de datos, el usuario y la contraseña? haciendo las configuraciones necesarias para que sean permitidas las conexiones desde la ip de mi casa.

	* **vcentt-lopez** [499985] (1)

		Así es

* **camiloorvi_** (1) [84379](https://platzi.com/comentario/1049567/) 
Cómo se hace la conexión por ssh a una RDS en sql server?

* **alejo-ortiz** (1) [83235](https://platzi.com/comentario/1022603/) 
Alguien me podría decir cual es la llave que debo poner private key? estoy poniendo la llave del arn me sale error, le pongo la clave del...

	* **Diego Alexander Forero Higuera (Platzi)** [83235] (1)

		Hola. Debes usar la que descargaste en este momento <https://platzi.com/clases/1426-db-aws/15217-conexion-por-consola-a-nuestra-base-de-datos/?time=129> cuando creaste la instancia. Si no la guardaste puedes crear una nueva instancia y destruyes la anterior.

* **Luis Emmanuel Rodas Camposeco** (1) [78233](https://platzi.com/comentario/917636/) 
Podria realizar esa misma conexion desde lightsail?

* **Nestor Alfonso Portela Rincón** (1) [52063](https://platzi.com/comentario/499985/) 
Yo me podría conectar a esa base de datos desde mi computador local haciendo uso del endpoint como host de la base de datos, el usuario y...

* **estebanvasquezvalencia** (1) [51173](https://platzi.com/comentario/488240/) 
¿Es necesario crear las reglas de entrada tanto en la instancia EC2 como en RDS?

	* **DiegoRP** [51173] (1)

		La verdad es que si está extraña esa parte. Normalmente solo se necesitaría la comunicación desde el jumphost hacia la BD. No veo muy clara la razón para permitir el tráfico desde la BD hacia el jumphost.

## 0070. Base de Datos corporativa en RDS [15238](https://platzi.com/clases/1426-db-aws/15238-base-de-datos-corporativa-en-rds/)

### Descripción:


¡Hola! Como primer proyecto para este curso vas a poner en práctica tus conocimientos para desplegar, conectar, consultar y recuperar una base de datos en RDS.

Eres el arquitecto de soluciones de una empresa y el CEO te ha pedido que despliegues una base de datos que contenga información de los trabajadores que ingresaron durante la primer semana del mes, la información es la siguiente:

Tabla # 1 - Trabajadores.

![Captura de pantalla 2018-11-21 a la\(s\) 13.44.14.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-11-21%20a%20la%28s%29%2013.44.14-88e033f3-d753-415c-bf21-4ebc79910bf5.jpg)

* Despliega la Base de datos RDS (MySQL) y conéctate a través de MySQL Workbench.
* Crea una tabla de trabajadores con los campos ID, Nombre, Fecha de Ingreso, Fecha de Nacimiento y Cargo.
* Ingresa los datos mostrados en la tabla # 1 - Trabajadores.
* Ahora conéctalos a la base de datos a través de una instancia EC2 usando la CLI y observa la tabla que creaste gráficamente.
* Luego de haber creado la tabla, ingresó un empleado:



Juan Camilo Rodriguez.  
Fecha de Ingreso → 10/10/2018  
Fecha de Nacimiento → 25/08/1991  
Cargo → Software Engineer Senior  
Ingresar el registro del nuevo empleado.

Ahora quieres probar las funcionalidades de Backup de la base de datos y para eso, vas a restaurar la base de datos al momento anterior al cual agregaste el último ingreso (Juan Camilo Rodriguez).

* Restaura la base de datos al momento anterior al ingreso del último usuario.
* Consulta la tabla trabajadores y verifica su estado.
* Verifica la tabla y evidencia que contenga solo los 5 registros iniciales.



Por último, envía un diagrama de arquitectura al CIO de la Base de Datos en Alta Disponibilidad y con optimización de performance.

No olvides compartir tus resultados, desafíos y aciertos en el panel de discusiones.

### Comentarios:

* **JOSE MANUEL COLLI FERNANDEZ** (5) [557432](https://platzi.com/comentario/557432/) 

	Ya realice la prueba, pero usando postgreSQL, todo muy bien, solo fue buscar las instrucciones para la instalación de postgreSQL en la instancia EC2, usando Amazon Linux.

* **Israel Yance** (3) [971962](https://platzi.com/comentario/971962/) 

	Reto cumplido.
	
	No sé por qué no puedo cargar la imagen.

* **Marollyn Jisselly Alvarado Navarro** (2) [690606](https://platzi.com/comentario/690606/) 

	Excelente trabajo… ya lo puse en practica…

* **Milciades** (2) [638876](https://platzi.com/comentario/638876/) 
	
	![DBPlatzi.JPG](https://static.platzi.com/media/user_upload/DBPlatzi-2dc722b8-6da7-44f2-85b0-b069be4f365f.jpg)

* **AlexanderJ** (1) [1072983](https://platzi.com/comentario/1072983/) 

	Listo 😃

* **Antonio Rafael González Ferrer** (1) [1019428](https://platzi.com/comentario/1019428/) 

	Listo!
	
	Tuve que añadir todo desde terminal por políticas empresariales de mi equipo…
	``` 
	    Database changed
	    MySQL [platzidb]> desc trabajadores;
	    +------------------+--------------+------+-----+---------+----------------+
	    | Field            | Type         | Null | Key | Default | Extra          |
	    +------------------+--------------+------+-----+---------+----------------+
	    | id_trabajador    | int(11)      | NO   | PRI | NULL    | auto_increment |
	    | nombre           | varchar(100) | YES  || NULL    ||
	    | fecha_ingreso    | date         | YES  || NULL    ||
	    | fecha_nacimiento | date         | YES  || NULL    ||
	    | cargo            | varchar(255) | YES  || NULL    ||
	    +------------------+--------------+------+-----+---------+----------------+
	    5 rows in set (0.00 sec)
	    
	    MySQL [platzidb]> INSERT INTO trabajadores (nombre, fecha_ingreso, fecha_nacimiento, cargo) VALUES
	        -> ('Carlos Perez', '08/02/2020', '29/03/1988', 'Developer Junior'),
	        -> ('Juanita Gomez', '07/02/2020', '19/03/1990', 'Developer Junior'),
	        -> ('Paola Suarez', '04/02/2020', '21/02/2000', 'Account Manager'),
	        -> ('Andres Chavez', '04/02/2020', '17/08/1979', 'Sales Manager'),
	        -> ('Pedro Tovar', '03/02/2020', '19/09/1989', 'Tech Leader');
	    Query OK, 5 rows affected, 10 warnings (0.01 sec)
	    Records: 5  Duplicates: 0  Warnings: 10
	    
	    MySQL [platzidb]> SELECT * FROM trabajadores;
	    +---------------+---------------+---------------+------------------+------------------+
	    | id_trabajador | nombre        | fecha_ingreso | fecha_nacimiento | cargo            |
	    +---------------+---------------+---------------+------------------+------------------+
	    |             1 | Carlos Perez  | 0000-00-00    | 0000-00-00       | Developer Junior |
	    |             2 | Juanita Gomez | 0000-00-00    | 0000-00-00       | Developer Junior |
	    |             3 | Paola Suarez  | 0000-00-00    | 0000-00-00       | Account Manager  |
	    |             4 | Andres Chavez | 0000-00-00    | 0000-00-00       | Sales Manager    |
	    |             5 | Pedro Tovar   | 0000-00-00    | 0000-00-00       | Tech Leader      |
	    +---------------+---------------+---------------+------------------+------------------+
	    5 rows in set (0.00 sec)
	    
	```

* **Jose Maldonado** (1) [985880](https://platzi.com/comentario/985880/) 

	![](![bd.JPG](https://static.platzi.com/media/user_upload/bd-158f045d-6459-40b8-9406-41a81860fae7.jpg)

* **juancajamarca** (1) [985624](https://platzi.com/comentario/985624/) 

	😀

* **Eduardo Rodriguez Yapur** (1) [892630](https://platzi.com/comentario/892630/) 

	![](![practica.png](https://static.platzi.com/media/user_upload/practica-292eec03-dcac-4b51-b1a1-cf3c52d8b5e9.jpg)

# Backups, Performance y HA en RDS [2919]

## 0080. Estrategias de backup [15216](https://platzi.com/clases/1426-db-aws/15216-estrategias-de-backup/)

### Descripción:


Los sistemas de backup manuales de _RDS_ son completamente nuestra responsabilidad y debemos determinar cuándo tomar estos _snapshots_. Recuerda qué estos backups son incrementales, pueden mantener la información incluso cuando borramos la base de datos y nos permiten migrar la información entre diferentes regiones.

Por otra parte, los backups automáticos se hacen a diario, pero las operaciones de entrada y salida pueden quedar suspendidas por algunos segundos. Para solucionar este problema, es recomendado trabajar con despliegues Multi-AZ, que nos permiten utilizar una instancia de reserva de la base de datos cuando la instancia principal no se encuentra disponible.

El precio de nuestros backups depende de dos cosas: la retención _(el tiempo que tenemos disponibles nuestros backups, máximo 35 días)_ y la cantidad almacenamiento que utilizamos _(storage)_.

### Links:

* [Despliegues Multi-AZ de Amazon RDS](https://aws.amazon.com/es/rds/details/multi-az/)

### Comentarios:

* **Juan David Castro (Platzi)** (4) [428957](https://platzi.com/comentario/428957/) 

	Los despliegues Multi-AZ de Amazon RDS ofrecen una mejora de la disponibilidad y la durabilidad de las instancias de base de datos, así que son idóneas para las cargas de trabajo de bases de datos en producción.
	
	* [Despliegues Multi-AZ de Amazon RDS](https://aws.amazon.com/es/rds/details/multi-az/)
	
	

	* **Carlos Andrés Zambrano Barrera** [428957] (1)

		Si, siempre en producción las usamos y eventualmente salvarán tu vida!

* **jorge-gianareas** (3) [967024](https://platzi.com/comentario/967024/) 

	El precio de nuestros backups depende de dos cosas: la retención (el tiempo que tenemos disponibles nuestros backups, máximo 35 días) y la cantidad almacenamiento que utilizamos (storage).

* **jorge-gianareas** (3) [967023](https://platzi.com/comentario/967023/) 

	Por otra parte, los backups automáticos se hacen a diario, pero las operaciones de entrada y salida pueden quedar suspendidas por algunos segundos. Para solucionar este problema, es recomendado trabajar con despliegues Multi-AZ, que nos permiten utilizar una instancia de reserva de la base de datos cuando la instancia principal no se encuentra disponible.

* **jorge-gianareas** (3) [967021](https://platzi.com/comentario/967021/) 

	Los sistemas de backup manuales de RDS son completamente nuestra responsabilidad y debemos determinar cuándo tomar estos snapshots. Recuerda qué estos estos backups son incrementales, pueden mantener la información incluso cuando borramos la base de datos y nos permiten migrar la información entre diferentes regiones.

* **kristianando93** (3) [816186](https://platzi.com/comentario/816186/) 

	El almacenamiento de backups o de los snapshots, se almacenan en algun servicio AWS para Storage? por ejemplo S3, o algun servicio de almacenamiento mas económico, es posible hacerlo?

* **johncastillotellez7** (1) [983485](https://platzi.com/comentario/983485/) 

	manuales, automaticos and prices , interesante

* **Jean Carlos Nuñez Hernandez** (1) [983182](https://platzi.com/comentario/983182/) 

	Los respaldos en los RDS son muy granulares e importante a la hora de una incidencia con la base de datos

* **Carlos Arriero** (1) [67904](https://platzi.com/comentario/730906/) 
Buenas noches, profe una pregunta tienes algunos casos de uso en los cuales se deba de usar un despliegue multi AZ, ¿de que manera puede ...

	* **Carlos Andrés Zambrano Barrera** [67904] (1)

		Hola! el despliegue MUlti Az maneja un esquema activo-pasivo, el funcionamiento es por failover, cuando hay un error en la primar, el DNS que tiene asignado se mueve automaticamente a la que esta en standby en la otra zona y tu aplicación sigue funcionando.  
		Por buenas prácticas para cualquier BD productiva siempre es bueno activar esta funcionalidad.

## 0090. Demo estrategias de backup [15206](https://platzi.com/clases/1426-db-aws/15206-demo-estrategias-de-backup/)

### Descripción:


### Comentarios:

* **kristianando93** (4) [816201](https://platzi.com/comentario/816201/) 

	Para que sirven los Tags dentro de AWS?. Pues tambien vi que se definian al crear una una instancia EC2. Infiero mal ? o sirve para etiquetar los distintos recursos como asignarle criterios de identificacion? por ejemplo nombre de ambientes, grupos , responsables, departamento etc.

	* **juancajamarca** [816201] (1)

		Exacto, así como lo mencionas. Sirven para etiquetar recursos e información

* **kristianando93** (3) [816211](https://platzi.com/comentario/816211/) 

	La RE configuración de la DB solo se puede hacer al momento de hacer un backup automático o manual? o podemos realizar cambios de configuración sin realizar backup ( así no sea recomendado.)

* **Francisco Genaro Cerna Fukuzaki** (2) [629252](https://platzi.com/comentario/629252/) 

	No me queda claro cómo se puede complementar los snapshotp local y los backups automáticos

	* **Erik Ochoa (Platzi)** [629252] (6)

		Los **backups** tienen una periodicidad y su única referencia para usarlos es la fecha en el que fueron hechos.
		
		Un **Snapshot** aunque es esencialmente un backup ejecutado de forma manual, su gran diferencia es que tiene un propósito especifico y que marca un punto de restauración con un significado más allá de una simple fecha.
		
		Puede servir para marcar un punto de restauración antes de actualizar dependencias, antes de actualizar la versión de la base de datos, antes de hacer un cambio de configuración etc.
		
		En general los snapshots sirven para marcar un punto de restauración muy especifico antes de hacer un gran cambio que puede afectar nuestra base de datos.

	* **Carlos Andrés Zambrano Barrera** [629252] (3)

		El automático es un periodo de retención de información. El manual es una medida extra de seguridad y también te da flexibilidad, si necesitas en un momento restaurar un backup de una parte del tiempo para probar algo. Ademas los backups automaticoos se borran al borrar la BD los manuales no.

* **Danilo Pazos** (2) [76012](https://platzi.com/comentario/879831/) 
Tengo una duda. Si devolvemos la base de datos en el tiempo, que sucede con la información? Se pierde? O al momento de regresar en el tie...

* **Danilo Pazos** (1) [76011](https://platzi.com/comentario/879830/) 
Tengo una duda. Si devolvemos la base de datos en el tiempo, que sucede con la información? Se pierde? O al momento de regresar en el tie...

## 0100. Estrategias de performance en RDS [15232](https://platzi.com/clases/1426-db-aws/15232-estrategias-de-performance-en-rds/)

### Descripción:


En esta clase vamos a aprender cómo identificar el rendimiento de nuestra base de datos, estrategias para mejorar su rendimiento actual y todas las opciones de performance de AWS.

A nivel de monitoreo, AWS nos provee un servicio llamado **CloudWatch** que nos permite visualizar los niveles de lectura, escritura, CPU, disco y memoria de la instancia dónde corre nuestra base de datos, también podemos analizar las métricas de conexiones para determinar la carga y la concurrencia de nuestras instancias.

La primer estrategia para mejorar el performance son las **replicas de lectura** , copias asíncronas de nuestra base de datos principal con un nuevo _endpoint_ que vamos a utilizar solo en tareas de lectura, así obtenemos mucha más disponibilidad para tareas de escritura en nuestra base de datos principal. Recuerda que este servicio no esta disponible para los motores de Oracle y SQL Server.

También podemos mejorar el _storage_ de nuestra base de datos utilizando **provisioned iops** para soportar altas operaciones de entrada y salida sobre la base de datos, principalmente para transacciones OLTP _(OnLine Transaction Processing)_.

Existen otras alternativas como las bases de datos en memoria _(ElastiCache, por ejemplo)_. Estas opciones resultan muy útiles para guardar la información más consultada en cache, así aliviamos un poco la carga de nuestra base de datos principal. Si estamos muy saturados y agotamos todas las opciones para mejorar el performance, la recomendación es dividir nuestra base de datos en otras más pequeñas.

### Comentarios:

* **jorge-gianareas** (4) [967028](https://platzi.com/comentario/967028/) 

	Existen otras alternativas como las bases de datos en memoria (ElastiCache, por ejemplo). Estas opciones resultan muy útiles para guardar la información más consultada en cache, así aliviamos un poco la carga de nuestra base de datos principal. Si estamos muy saturados y agotamos todas las opciones para mejorar el performance, la recomendación es dividir nuestra base de datos en otras más pequeñas.

* **juancajamarca** (2) [992892](https://platzi.com/comentario/992892/) 

	 **Estrategias de performance en RDS**
	
	* **Monitoreo:** Lectura y escritura, CPU, DD y Memoria (AWS CloudWatch). Conexiones.
	* **Réplicas de lectura:** Mejorar el desempeño de la BD. No disponibles para Oracle y SQL Server. Por cada réplica, se genera un endpoint totalmente diferente, y hay que modificar el código para que utilice la réplica o la BD master cuando sea necesario.
	* **Provisioned:** Diseñado para transacciones OLTP. 1.000 a 40.000 IOPS.
	* **Alternativas:** BD en memoria (ElastiCache). Dividir la BD en otras BDs más pequeñas.
	* **Performance insights:** Monitoreo de performance. Cuándo y qué acciones tomar para mejorar el rendimiento de la BD.
	* **Adicionales:** Estrategias dependen del motor. AWS recomienda Aurora.
	
	

* **jorge-gianareas** (2) [967027](https://platzi.com/comentario/967027/) 

	También podemos mejorar el storage de nuestra base de datos utilizando provisioned iops para soportar altas operaciones de entrada y salida sobre la base de datos, principalmente para transacciones OLTP (OnLine Transaction Processing).

* **jorge-gianareas** (2) [967026](https://platzi.com/comentario/967026/) 

	La primer estrategia para mejorar el performance son las replicas de lectura, copias asíncronas de nuestra base de datos principal con un nuevo endpoint que vamos a utilizar solo en tareas de lectura, así obtenemos mucha más disponibilidad para tareas de escritura en nuestra base de datos principal. Recuerda que este servicio no esta disponible para los motores de Oracle y SQL Server.

* **jorge-gianareas** (2) [967025](https://platzi.com/comentario/967025/) 

	A nivel de monitoreo, AWS nos provee un servicio llamado CloudWatch que nos permite visualizar los niveles de lectura, escritura, CPU, disco y memoria de la instancia dónde corre nuestra base de datos, también podemos analizar las métricas de conexiones para determinar la carga y la concurrencia de nuestras instancias.

* **Mauricio Serna Flórez** (2) [859560](https://platzi.com/comentario/859560/) 

	También deberíamos tener en cuenta la consistencia eventual, cuando se hacen estas replicaciones asíncronas podemos por algún instante de tiempo ver la réplica desactualizada.

* **Emerson Cedeño Salazar** (2) [840387](https://platzi.com/comentario/840387/) 

	y … ¿cómo se hace una **réplica de lectura**?

* **Emerson Cedeño Salazar** (2) [840373](https://platzi.com/comentario/840373/) 

	eso de la RR de la RR de la RR sonó como a la **herencia prototipal** de _javascript_! 😱🤪

* **raimercm** (2) [542624](https://platzi.com/comentario/542624/) 

	Hola. ¿Como averigua hasta cuantas conexiones puede soportar la BD en una determinada instancia? ¿Si deseo mejorar el numero de conexiones debo elegir una instancia con mayor RAM o mayor CPU?  
	Esta muy bueno el curso, saludos…

	* **Diego Alexander Forero Higuera (Platzi)** [542624] (3)

		El problema no es solo el número de conexiones si no la query que se hace en esa conexión, si son queries muy sencillas y rápidas el servidor va a responder y cerrar la conexión, si una query es muy demorada entonces se van a abrir más y más conexiones hasta que las queries sean respondidas y poder cerrar la conexión.
		
		Por lo general las instancias de AWS aumentan las dos cosas al subir de instancia.

* **estebanvasquezvalencia** (2) [488252](https://platzi.com/comentario/488252/) 

	¿**Performance Insights **está solo disponible para RDS o también se puede usar con un motor instalado en una instancia EC2?

	* **Carlos Andrés Zambrano Barrera** [488252] (2)

		Esta solo disponible para RDS pero en algunas versiones específicas, por ejemplo aurora con MySLQ 5.6. Vale mucho la pena usarlo, te da granularidad sobre queries, usuarios y con esa información puedes mejorar el rendimiento de tu app.

* **Juan David Castro (Platzi)** (2) [428956](https://platzi.com/comentario/428956/) 

	Cuando utilizamos MySQL para sacar replicas de replicas de otras replicas, debemos tener en cuenta que podemos tener problemas con la latencia, la ultima replica puede tardar un poco en actualizarse y vamos a tener información diferente a la base de datos principal 👍.

	* **Carlos Andrés Zambrano Barrera** [428956] (3)

		Aunque mira que no he visto casos reales donde se requieran RR de RR, si tienes y puedes crear 5 RR de MYSQL podrías usarlas o en otro caso usar Aurora para cargas más grandes.

* **Jean Carlos Nuñez Hernandez** (1) [983220](https://platzi.com/comentario/983220/) 

	Performances inside es una herramienta en AWS para ver el desepeño de nuestro RDS

* **Jean Carlos Nuñez Hernandez** (1) [983218](https://platzi.com/comentario/983218/) 

	RE replica se coloca cuando tengo mucha carga de lectura y queremos aliviar la carga a la base de datos

* **raimercm** (1) [55549](https://platzi.com/comentario/542624/) 
Hola. ¿Como averigua hasta cuantas conexiones puede soportar la BD en una determinada instancia? ¿Si deseo mejorar el numero de conexione...

	* **Diego Alexander Forero Higuera (Platzi)** [55549] (3)

		El problema no es solo el número de conexiones si no la query que se hace en esa conexión, si son queries muy sencillas y rápidas el servidor va a responder y cerrar la conexión, si una query es muy demorada entonces se van a abrir más y más conexiones hasta que las queries sean respondidas y poder cerrar la conexión.
		
		Por lo general las instancias de AWS aumentan las dos cosas al subir de instancia.

* **estebanvasquezvalencia** (1) [51175](https://platzi.com/comentario/488252/) 
¿**Performance Insights **está solo disponible para RDS o también se puede usar con un motor instalado en una instancia EC2?

	* **Carlos Andrés Zambrano Barrera** [51175] (2)

		Esta solo disponible para RDS pero en algunas versiones específicas, por ejemplo aurora con MySLQ 5.6. Vale mucho la pena usarlo, te da granularidad sobre queries, usuarios y con esa información puedes mejorar el rendimiento de tu app.

* **johncastillotellez7** (0) [983508](https://platzi.com/comentario/983508/) 

	no soportable en Oracle Y Mysql ,pero si estas son los motores de bases de datos mas importantes y usados en el mercado. cada cuanto se refrescaria la READ REPLICA PARA QUE EL USUARIO Tenga la informacion mas actualizada. si es para applications de Fintech. se desea tener la informacion mas fresca

	* **johncastillotellez7** [983508] (1)

		Existen otras alternativas como las bases de datos en memoria (ElastiCache, por ejemplo). Estas opciones resultan muy útiles para guardar la información más consultada en cache, así aliviamos un poco la carga de nuestra base de datos principal. Si estamos muy saturados y agotamos todas las opciones para mejorar el performance, la recomendación es dividir nuestra base de datos en otras más pequeñas.

	* **johncastillotellez7** [983508] (1)

		Elasticache es un tema super interesante.

	* **johncastillotellez7** [983508] (1)

		Migracion de MYSQL/ORacle a AURORA que es el software local de AWS

* **Jaime Frank Villanueva Oré** (0) [72306](https://platzi.com/comentario/813785/) 
¿Como se optimiza los queries en MariaDB?, fue algo que se menciono en este video y me gustaria saber como puedo hacerlo

	* **Gabriel De Andrade (Platzi)** [72306] (2)

		Hola! Siendo MariaDB un fork de MySQL creo que podrías aprender más a fondo sobre esto en el curso de [SQL y MySQL](https://platzi.com/clases/sql-mysql/) 😄

## 0110. Despliegues Multi AZ [15212](https://platzi.com/clases/1426-db-aws/15212-despliegues-multi-az/)

### Descripción:


El servicio de Multi AZ nos permite aumentar la disponibilidad de nuestro servicio realizando despliegues de nuestra base de datos en diferentes zonas. Cuando nuestra base de datos principal tenga problemas de disponibilidad, AWS automáticamente conectará nuestra aplicación con la base de datos replica en la segunda zona de disponibilidad. Recuerda que el precio de este servicio es equivalente a tener 2 bases de datos.

El desafío de esta clase es identificar un caso de uso en tu empresa, universidad o algún proyecto personal dónde podemos utilizar RDS, recuerda explicar cuál es la funcionalidad qué más llama tu atención y por qué.

### Comentarios:

* **raimercm** (3) [542630](https://platzi.com/comentario/542630/) 

	Si la BD Master falla y entra a funcionar el Standby, ¿Que hacemos con la instancia master? ¿El Standby se convierte en Master y AWS crea otro Standby?

	* **Diego Alexander Forero Higuera (Platzi)** [542630] (6)

		Hola, como este proceso tiene muy poca intervención administrativa lo que sucede es que la Standby pasa a ser la Master y si la instancia que era mater vuelve a funcionar queda como standby, si y solo si la instancia no se puede recuperar se va a crear una nueva instancia eliminando la que no esta funcionando. Hay un excelente articulo en aws que te comparto <https://aws.amazon.com/blogs/database/amazon-rds-under-the-hood-multi-az/>

	* **Carlos Andrés Zambrano Barrera** [542630] (3)

		El failover funciona con conmutación por error, es decir cambia el DNS de la Master a la Standby. Si usas aurora en ese caso el master se encarga de cambiar los roles entre las BD para que vos no te preocupes. Igual recuerda que es mejor tener las 2 instancias de mismo tamano.

	* **karkastell** [542630] (2)

		Cuando se habla de sincronización asincrona, de cuanto tiempo o transacciones de diferencia se esta hablando?

	* **Diego Alexander Forero Higuera (Platzi)** [542630] (1)

		@karkastell la sincronización no tarda más de un segundo al menos que haya algún problema en las bases de datos como por ejemplo un campo borrado que no se ha replicado. La asincronía hace más referencia a que primero se hace el proceso en Master y una vez terminado envía el proceso de sincronización, no intenta crear el dato al mismo tiempo en master y replica.

* **Juan David Castro (Platzi)** (3) [428955](https://platzi.com/comentario/428955/) 

	Notas de la clase:
	
	* Multi AZ nos permite tener alta disponibilidad de nuestra base de datos, creando bases de datos replica que automáticamente vamos a utilizar cuando la base de datos principal tenga problemas 📡.
	* Recomendado para ambientes de producción 💥.
	* La replicación es síncrona 🎏.
	* Los backups se hacen en la base de datos _Standby_ _(la que no estamos utilizando)_ 👍.
	* El precio es el mismo que al tener dos bases de datos 😱.
	* No confundir con las replicas de lectura 😅.
	
	

* **Angelica Landazabal** (2) [1006834](https://platzi.com/comentario/1006834/) 

	Creo que implementaría RDS a la sección de control de estudios de la Universidad debido a que allí se encuentra data importante con respecto a los alumnos, materías, profesores, etc; pero le haría una replica de lectura por lo que es constantemente consultada.

* **juancajamarca** (2) [993051](https://platzi.com/comentario/993051/) 

	 **Despliegues Multi AZ**
	
	* Incrementan la disponibilidad de la BD.
	* Recomendadas para ambientes de producción.
	* Se compone de una Master-Standby.
	* Replicación síncrona.
	* Failover automático.
	* Conmutación por error.
	* Réplica entre AZ en una misma región.
	* El pricing es como tener 2 DBs.
	* Backups se hacen de BD Standby.
	
	
	
	No hay que confundir las Réplicas de lectura con Multi AZ. Las réplicas son para mejorar el performance, y la Multi AZ es para la disponibilidad de la instancia de la BD.

* **jhon Erik calderon Rubiano** (2) [971178](https://platzi.com/comentario/971178/) 

	desconozco como pueda ser la estructura del servicio de facebook o youtube, pero creo que por la cantidad de interacciones deben tener multi az, para evitar lentitud en las solicitudes

* **jorge-gianareas** (2) [967031](https://platzi.com/comentario/967031/) 

	El desafío de esta clase es identificar un caso de uso en tu empresa, universidad o algún proyecto personal dónde podemos utilizar RDS, recuerda explicar cuál es la funcionalidad qué más llama tu atención y por qué.

* **jorge-gianareas** (2) [967030](https://platzi.com/comentario/967030/) 

	El servicio de Multi AZ nos permite aumentar la disponibilidad de nuestro servicio realizando despliegues de nuestra base de datos en diferentes zonas. Cuando nuestra base de datos principal tenga problemas de disponibilidad, AWS automáticamente conectará nuestra aplicación con la base de datos replica en la segunda zona de disponibilidad. Recuerda que el precio de este servicio es equivalente a tener 2 bases de datos.

* **Rodolfo Nicacio Ugalde Ochoa** (2) [803157](https://platzi.com/comentario/803157/) 

	Un ejemplo sería. Mandar las ubicaciones GPS de dispositivos dentro de una fabrica y mandar a guardar las ubicaciones en tiempo real a la BD. Para poder hacer después revisión de históricos.

* **carlos alberto arguello ramirez** (2) [706231](https://platzi.com/comentario/706231/) 

	Réplicas multi AZ vs réplicas de lectura

* **Francisco Genaro Cerna Fukuzaki** (2) [629625](https://platzi.com/comentario/629625/) 

	Yo tengo un sistema de evaluaciones psicológicas a las cuales los candidatos pueden ingresar en cualquier momento del dia. Yo usaría RDS Multi AZ porque necesito que la base de datos esté disponible las 24 horas.

* **hanuman80** (2) [569319](https://platzi.com/comentario/569319/) 

	Los despliegues Multi AZ permiten tener alta disponibilidad en el servicio de bases de datos.

* **johncastillotellez7** (1) [997863](https://platzi.com/comentario/997863/) 

	bien interesante el AZ
	
	replication+performance  
	AZ aumenta la disponibilidad

	* **johncastillotellez7** [997863] (1)

		Interesante
		
		El servicio de Multi AZ nos permite aumentar la disponibilidad de nuestro servicio realizando despliegues de nuestra base de datos en diferentes zonas. Cuando nuestra base de datos principal tenga problemas de disponibilidad, AWS automáticamente conectará nuestra aplicación con la base de datos replica en la segunda zona de disponibilidad. Recuerda que el precio de este servicio es equivalente a tener 2 bases de datos.

* **Jean Carlos Nuñez Hernandez** (1) [983227](https://platzi.com/comentario/983227/) 

	Multi AZ es para aumentar la disponibilidad de nuestra DB

* **raimercm** (1) [55550](https://platzi.com/comentario/542630/) 
Si la BD Master falla y entra a funcionar el Standby, ¿Que hacemos con la instancia master? ¿El Standby se convierte en Master y AWS crea...

	* **Diego Alexander Forero Higuera (Platzi)** [55550] (6)

		Hola, como este proceso tiene muy poca intervención administrativa lo que sucede es que la Standby pasa a ser la Master y si la instancia que era mater vuelve a funcionar queda como standby, si y solo si la instancia no se puede recuperar se va a crear una nueva instancia eliminando la que no esta funcionando. Hay un excelente articulo en aws que te comparto <https://aws.amazon.com/blogs/database/amazon-rds-under-the-hood-multi-az/>

# Migración a RDS [2921]

## 0120. Estrategias de migración a RDS [15218](https://platzi.com/clases/1426-db-aws/15218-estrategias-de-migracion-a-rds/)

### Descripción:


DMS _(Database Migration Service)_ es un servicio de AWS que nos permite migrar nuestras bases de datos con otros motores al servicio de RDS u otros servicios de bases de datos en AWS.

Este servicio tiene las siguientes características:

* Podemos realizar migraciones de bases de datos _on premise_ o en la nube a los servicios de bases de datos en AWS sin afectar el _downtime_ de la base de datos que vamos a migrar.
* La carga de trabajo durante las migraciones es adaptable.
* Solo pagamos por los recursos que utilizamos en la migración.
* AWS administra la infraestructura necesaria para el trabajo de la migración, Hardware, Software, parches, etc.
* Conmutación por error automática, si AWS detecta un error en el proceso automáticamente creará una nueva instancia para remplazar la anterior, así el proceso de replicación no se ve afectado por estos problemas.
* Los datos en reposo están cifrados con KMS _(Key Management Service)_ y la migración utiliza el protocolo de seguridad SSL.



### Comentarios:

* **jorge-gianareas** (2) [967034](https://platzi.com/comentario/967034/) 

	Este servicio tiene las siguientes características:
	
	Podemos realizar migraciones de bases de datos on premise o en la nube a los servicios de bases de datos en AWS sin afectar el downtime de la base de datos que vamos a migrar.  
	La carga de trabajo durante las migraciones es adaptable.  
	Solo pagamos por los recursos que utilizamos en la migración.  
	AWS administra la infraestructura necesaria para el trabajo de la migración, Hardware, Software, parches, etc.  
	Conmutación por error automática, si AWS detecta un error en el proceso automáticamente creará una nueva instancia para remplazar la anterior, así el proceso de replicación no se ve afectado por estos problemas.  
	Los datos en reposo están cifrados con KMS (Key Management Service) y la migración utiliza el protocolo de seguridad SSL.

* **jorge-gianareas** (2) [967033](https://platzi.com/comentario/967033/) 

	DMS (Database Migration Service) es un servicio de AWS que nos permite migrar nuestras bases de datos con otros motores al servicio de RDS u otros servicios de bases de datos en AWS.

* **Arjun4_0** (2) [567860](https://platzi.com/comentario/567860/) 

	Pregunta: Pero si la idea es migrar una bd on premise por ejemplo, ¿no es mas eficiente subir un bkp de las bd a S3 y luego restaurarla en un instancia RDS y ya dejarla configurada y funcionando? Es mi punto de vista.  
	De todas formas si no me equivoco DMS tambien sirve para migrar de una version de motor de bd a otra (ej.: Oracle a Mysql)  
	¿Esta migración de versiones garantiza que funcione en 100%?

	* **Erik Ochoa (Platzi)** [567860] (4)

		Según la documentación [Oficial](https://aws.amazon.com/es/dms/) es un servicio muy robusto:
		
		“AWS Database Migration Service presenta una **alta resiliencia** y una recuperación automática. Monitorea constantemente las bases de datos de origen y de destino, la conectividad de red y la instancia de replicación. En caso de interrupción, reinicia automáticamente el proceso y continúa la migración desde donde se detuvo. La opción Multi-AZ permite tener alta disponibilidad para migración de bases de datos y replicación de datos continua al permitir instancias de replicación redundantes.”

	* **Carlos Andrés Zambrano Barrera** [567860] (1)

		Respuesta 1 – el caso es si no podes dejar de recibir data y queres hacer la migracion en caliente, Pero tu alternativa es valida.
		
		Respuesta 2 – si es una migración heterogenea y debes pasar tambien por el conversor de schemas.

* **juancajamarca** (1) [1029289](https://platzi.com/comentario/1029289/) 

	 **Estrategias de migración a RDS**
	
	Estas estrategias se realizan utilizando Database Migration Service (DMS).
	
	DMS (Database Migration Service) es un servicio de AWS que nos permite migrar nuestras bases de datos con otros motores al servicio de RDS u otros servicios de bases de datos en AWS.
	
	Este servicio tiene las siguientes características:
	
	* Realizar migraciones de bases de datos on premise o en la nube a los servicios de bases de datos en AWS sin afectar el downtime de la base de datos que vamos a migrar.
	* Adaptar los recursos a la carga de trabajo. Sólo se paga por los recursos mientras se hace el trabajo.
	* Administra la infraestructura necesaria para el trabajo de migración: Hardware, Software y parches.
	* Conmutación por error automática, si AWS detecta un error en el proceso automáticamente creará una nueva instancia para remplazar la anterior, así el proceso de replicación no se ve afectado por estos problemas.
	* Los datos en reposo se cifran con KMS y la migración es usando conexión segura SSL.
	
	

* **johncastillotellez7** (1) [1020833](https://platzi.com/comentario/1020833/) 

	super util  
	DMS (Database Migration Service)

## 0130. Migraciones homogéneas y heterogéneas [15208](https://platzi.com/clases/1426-db-aws/15208-migraciones-homogeneas-y-heterogeneas/)

### Descripción:


Las migraciones homogéneas son migraciones donde la base de datos de origen y la de destino puede tener diferentes versiones del mismo motor, o son bases de datos compatibles entre sí _(MySQL y Aurora, por ejemplo)_.

También podemos realizar migraciones heterogéneas, donde la base de datos de origen no es compatible con la de destino. Estas migraciones NO siempre son posibles, y antes de realizar la migración vamos a necesitar convertir el esquema de la base de datos con la herramienta AWS Schema Conversion Tool.

### Comentarios:

* **Juan David Castro (Platzi)** (19) [428952](https://platzi.com/comentario/428952/) 

	Estos tutoriales **oficiales** de AWS enseñan paso a paso sobre algunas posibles migraciones utilizando el _AWS Database Migration Service_ :
	
	* [De Oracle local a Aurora](https://docs.aws.amazon.com/es_es/dms/latest/sbs/CHAP_On-PremOracle2Aurora.html)
	* [De RDS Oracle a Aurora](https://docs.aws.amazon.com/es_es/dms/latest/sbs/CHAP_RDSOracle2Aurora.html)
	* [De SQL Server a Aurora](https://docs.aws.amazon.com/es_es/dms/latest/sbs/CHAP_SQLServer2Aurora.html)
	* [De Oracle a PostgreSQL](https://docs.aws.amazon.com/es_es/dms/latest/sbs/CHAP_RDSOracle2PostgreSQL.html)
	* [De RDS Oracle a Redshift](https://docs.aws.amazon.com/es_es/dms/latest/sbs/CHAP_RDSOracle2Redshift.html)
	* [De bases de datos compatibles con MySQL a AWS](https://docs.aws.amazon.com/es_es/dms/latest/sbs/CHAP_MySQL.html)
	* [De bases de datos compatibles con MySQL a Aurora](https://docs.aws.amazon.com/es_es/dms/latest/sbs/CHAP_MySQL2Aurora.html)
	
	
	
	Toda la lista esta aquí:
	
	* [Explicación paso a paso de AWS Database Migration Service](https://docs.aws.amazon.com/es_es/dms/latest/sbs/DMS-SBS-Welcome.html)
	
	

	* **estebanvasquezvalencia** [428952] (3)

		Gracias por la info!

* **jorge-gianareas** (2) [967037](https://platzi.com/comentario/967037/) 

	También podemos realizar migraciones heterogéneas, donde la base de datos de origen no es compatible con la de destino. Estas migraciones NO siempre son posibles, y antes de realizar la migración vamos a necesitar convertir el esquema de la base de datos con la herramienta AWS Schema Conversion Tool.

* **jorge-gianareas** (2) [967036](https://platzi.com/comentario/967036/) 

	Las migraciones homogéneas son migraciones donde la base de datos de origen y la de destino puede tener diferentes versiones del mismo motor, o son bases de datos compatibles entre sí (MySQL y Aurora, por ejemplo).

* **johncastillotellez7** (1) [1034079](https://platzi.com/comentario/1034079/) 

	Database Migration Service its powerful tool

	* **johncastillotellez7** [1034079] (1)

		Homogeneous: Origen DB oracle to Oracle, changes the version or Mysql to aurora

	* **johncastillotellez7** [1034079] (1)

		Homogeneous: Origen DB Oracle /on premise to AUrora > usando tool de migration tool  
		conversion de esquema de DB

* **juancajamarca** (1) [1029308](https://platzi.com/comentario/1029308/) 

	 **Migraciones homogéneas y heterogéneas**
	
	Las migraciones homogéneas son migraciones en donde la base de datos de origen y la de destino pueden tener diferentes versiones del mismo motor o son bases de datos compatible entre sí (MySQL-Aurora, o PostgreSQL-Aurora, por ejemplo).
	
	También podemos realizar migraciones heterogéneas, en donde la base de datos de origen no es compatible con la de destino. Estas migraciones no siempre son posibles, y antes de realizar la migración, vamos a necesitar convertir el esquema de la base de datos con la herramienta AWS Schema Conversion Tool.

## 0140. Casos de uso de RDS [15222](https://platzi.com/clases/1426-db-aws/15222-casos-de-uso-de-rds/)

### Descripción:


### Comentarios:

* **Sergio López** (3) [459320](https://platzi.com/comentario/459320/) 
Estamos planeando una migración de Azure a AWS, parte importante de la aplicación es la base de datos en SQL Azure, el precio es más accesible en algunos paquetes antiguos de Azure, sin embargo queríamos asegurarnos que tuviéramos una migración sin downtime (con migration services se AWS se logra) y también restauración de puntos históricos del tiempo que es increíble (acá solo tengo que asegurar

	* **Carlos Andrés Zambrano Barrera** [459320] (2)

		Puedes utilizar database migration service, ese es sin downtime, tener en cuenta el tipo de migración.

* **jhon Erik calderon Rubiano** (2) [971260](https://platzi.com/comentario/971260/) 

	en un proyecto de investigación que requiere la participación de varias personas, y que como resultado genere documentos de forma permanente, se requeriría realizar la migración para poder tener un backup en la nube, y a su vez poder disponer de la información desde cualquier localización

* **jaime-pinto-a** (2) [853241](https://platzi.com/comentario/853241/) 

	El tema de migrar a la nube, algunos empresarios, aún tienen el temor del robo de la informacion por parte de hacker, y prefieren administrarlos en sus oficinas, lo cual no permite obtener los beneficios de administrar, espacio de disco , replica de lectura, entre otros que nos indican en el curso-

* **hanuman80** (2) [569358](https://platzi.com/comentario/569358/) 

	El servicio de RDS lo aplicaría en mi empresa para tener una copia de seguridad de las BDs on premise en la nube de Amazon, y ajustaría la infraestructura para adaptarse a un plan de contingencia y continuidad de negocio ante un desastre.

* **johncastillotellez7** (1) [1075835](https://platzi.com/comentario/1075835/) 

	utiles para estructurar posibles inconvenientes con errores y mantener el servicio HA 24/7 aws se adapta tanto para projs simples como para los supercomplejos

* **Jose Maldonado** (1) [998732](https://platzi.com/comentario/998732/) 

	Para un Plan de contingencia y continuidad de negocio.  
	Tendría la BD on-premise replicando en la nube y el o los aplicativos preparados para apuntar al cloud.
	
	O la copia de lectura de BD en cloud y la master on-premise, de forma hibrida

# Aurora [2920]

## 0150. Introducción a Aurora [15219](https://platzi.com/clases/1426-db-aws/15219-introduccion-a-aurora/)

### Descripción:


Aurora es el motor de base de datos más robusto de AWS a nivel relacional. Entre sus características encontramos que AWS garantiza que utilizar Aurora nos asegura un performance 5 veces superior a MySQL y hasta 3 veces superior a PostgreSQL. También soporta hasta 64 TB de almacenamiento y 15 réplicas de lectura con niveles de latencia inferiores a 10 ms.

Cuando creamos una base de datos Aurora, realmente creamos un cluster de bases de datos compuesto por una instancia maestra y múltiples réplicas de lectura, todas desplegadas en diferentes zonas de disponibilidad dependiendo de la región que estamos utilizando.

### Links:

* [AdministraciÃ³n de un clÃºster de base de datos de Amazon Aurora - Amazon Aurora](https://docs.aws.amazon.com/es_es/AmazonRDS/latest/AuroraUserGuide/CHAP_Aurora.html)

### Comentarios:

* **hanuman80** (5) [570509](https://platzi.com/comentario/570509/) 

	Resumen de la clase:  
	Aurora es el motor de bases de datos más robusto en AWS.
	
	* Desarrollado por AWS.
	* El performance es 5 veces mas rápido que MYSQl y 3 veces más rápido que PSQL.
	* Ideal para ambientes de producción.
	* Compatible con MYSQL y PSQL.
	* Soporta hasta 64 TB de storage.
	* Hasta 15 replicas de lectura.
	* Monitoring y failover en menos de 10 ms.
	* Aurora crea un cluster de las BDs en diferentes zonas de disponibilidad dependiendo de la región.
	
	

* **jorge-gianareas** (3) [967040](https://platzi.com/comentario/967040/) 

	Aurora es el motor de base de datos más robusto de AWS a nivel relacional. Entre sus características encontramos que AWS garantiza que utilizar Aurora nos asegura un performance 5 veces superior a MySQL y hasta 3 veces superior a PostgreSQL. También soporta hasta 64 TB de almacenamiento y 15 réplicas de lectura con niveles de latencia inferiores a 10 ms.

* **carlosbazanhuaman** (3) [945692](https://platzi.com/comentario/945692/) 

	aurora es muy buena opcion para app grandes. Donde tengamos miles de usuarios.

* **jorge-gianareas** (2) [967042](https://platzi.com/comentario/967042/) 

	Cuando creamos una base de datos Aurora, realmente creamos un cluster de bases de datos compuesto por una instancia maestra y múltiples réplicas de lectura, todas desplegadas en diferentes zonas de disponibilidad dependiendo de la región que estamos utilizando.

* **CristianCabreraA** (2) [606336](https://platzi.com/comentario/606336/) 

	muy como el RDS

* **johncastillotellez7** (1) [1078883](https://platzi.com/comentario/1078883/) 

	Relational Database Service>  
	Amazon Aurora (Aurora) is a fully managed relational database engine that’s compatible with MySQL and PostgreSQL. You already know how MySQL and PostgreSQL combine the speed and reliability of high-end commercial databases with the simplicity and cost-effectiveness of open-source databases. The code, tools, and applications you use today with your existing MySQL and PostgreSQL databases can be used with Aurora. With some workloads, Aurora can deliver up to five times the throughput of MySQL and up to three times the throughput of PostgreSQL without requiring changes to most of your existing applications.

	* **johncastillotellez7** [1078883] (1)

		Aurora takes advantage of the familiar Amazon Relational Database Service (Amazon RDS) features for management and administration. Aurora uses the Amazon RDS AWS Management Console interface, AWS CLI commands, and API operations to handle routine database tasks such as provisioning, patching, backup, recovery, failure detection, and repair.

	* **johncastillotellez7** [1078883] (1)

		usando Aurora se vuelve mas eficiente el rds , que interesante 5 veces superior a mysql and 3 veces superior a postgresql

* **Jean Carlos Nuñez Hernandez** (1) [995302](https://platzi.com/comentario/995302/) 

	Tengo que probar Aurora

* **estebanvasquezvalencia** (1) [488651](https://platzi.com/comentario/488651/) 

	Al ser Aurora la mas robusta, también es la sería la opción mas costosa?

	* **Carlos Andrés Zambrano Barrera** [488651] (4)

		No necesariamente deberías verlo así, con seguridad si vas a necesitar aurora es porque tu proyecto es grande y el rendimiento y HA es algo clave. Así que el costo beneficio lo vale. Ya he migrado varias MySQL y Posgres a Aurora y personalmente te digo que el rendimiento sube muchisimo, tenemos apps con millones de usuarios corriendo en aurora sin problemas hasta el momento.

* **JOAQUIN BATISTA** (1) [63781](https://platzi.com/comentario/664730/) 
Como se compararía Aurora contra: Microsoft SQL Server Oracle Suybase 

	* **Carlos Andrés Zambrano Barrera** [63781] (1)

		Hay muchas variables para comparar estas 4 bases de datos. Te puedo decir que he participado en migraciones de Oracle a Aurora, PosgreSQL y MYSQL a Aurora y el rendimiento ha mejorado notablemente.
		
		Adicionalmente mira las features…
		
		Por endpoint de aurora podes tener ilimitadas BD, en Oracle 1 en SQL Server 20.
		
		Aurora tiene hasta 15 replicas, autoreparación de disco y replica multi region con latencia inferior a 1sg.

* **estebanvasquezvalencia** (1) [51211](https://platzi.com/comentario/488651/) 
Al ser Aurora la mas robusta, también es la sería la opción mas costosa?

	* **Carlos Andrés Zambrano Barrera** [51211] (4)

		No necesariamente deberías verlo así, con seguridad si vas a necesitar aurora es porque tu proyecto es grande y el rendimiento y HA es algo clave. Así que el costo beneficio lo vale. Ya he migrado varias MySQL y Posgres a Aurora y personalmente te digo que el rendimiento sube muchisimo, tenemos apps con millones de usuarios corriendo en aurora sin problemas hasta el momento.

## 0160. Características de  Aurora [15226](https://platzi.com/clases/1426-db-aws/15226-caracteristicas-de-aurora/)

### Descripción:


Además de ser una base de datos muy potente y robusta, Aurora nos permite un nivel de customización muy alto, puede crecer hasta 64 TB y nuestra data esta replicada en múltiples Az.

El _endpoint_ de nuestra instancia principal nos permite conectarnos a la base de datos maestra y especificar las solicitudes de lectura y escritura, también tenemos _endpoints_ para cada una de las replicas de lectura y un último _endpoint_ a nivel de instancia que nos provee control sobre cargas de trabajo de la instancia principal y sus replicas, pero AWS nos recomienda NO utilizar este último _endpoint_ de instancia.

Otras características de Aurora:

* **Autoreparación** : Guardar la información de la parte dañada en otra parte del disco y reparar el problema automáticamente.
* **Cache Warm** : Hacer un precalentamiento de la caché al iniciar las consultas más comunes y sus resultados.
* **Recuperación de accidentes** : Si falla la instancia principal, Aurora promueve una réplica de lectura o crea una nueva instancia principal.



### Links:

* [How to Stream Data from Amazon DynamoDB to Amazon Aurora using AWS Lambda and Amazon Kinesis Firehose | AWS Database Blog](https://aws.amazon.com/es/blogs/database/how-to-stream-data-from-amazon-dynamodb-to-amazon-aurora-using-aws-lambda-and-amazon-kinesis-firehose/)

### Comentarios:

* **jorge-gianareas** (3) [967044](https://platzi.com/comentario/967044/) 

	Otras características de Aurora:
	
	Autoreparación: Guardar la información de la parte dañada en otra parte del disco y reparar el problema automáticamente.  
	Cache Warm: Hacer un precalentamiento de la caché al iniciar las consultas más comunes y sus resultados.  
	Recuperación de accidentes: Si falla la instancia principal, Aurora promueve una réplica de lectura o crea una nueva instancia principal.

* **jorge-gianareas** (3) [967043](https://platzi.com/comentario/967043/) 

	El endpoint de nuestra instancia principal nos permite conectarnos a la base de datos maestra y especificar las solicitudes de lectura y escritura, también tenemos endpoints para cada una de las replicas de lectura y un último endpoint a nivel de instancia que nos provee control sobre cargas de trabajo de la instancia principal y sus replicas, pero AWS nos recomienda NO utilizar este último endpoint de instancia.

* **johncastillotellez7** (1) [1079693](https://platzi.com/comentario/1079693/) 

	la base de datos Replica y S standby cuando se generan automaticamente quedan encryptadas si la DB master esta encriptada? o hay que realizar algun proceso adicional?

* **johncastillotellez7** (1) [1079642](https://platzi.com/comentario/1079642/) 

	where high availability is important, use the writer endpoint for read-write connections and the reader endpoint for read-only connections. These kinds of connections manage DB instance failover better than instance endpoints do. The instance endpoints connect to a specific DB instance in a DB cluster, requiring logic in your application to choose a different endpoint if the DB instance becomes unavailable.

* **Vicente Fernandez** (1) [1020032](https://platzi.com/comentario/1020032/) 

	Que belleza de arquitectura, y la forma en que fluye la información como el agua en las tuberías, solo que en vez de agua es conocimiento.

* **Jean Carlos Nuñez Hernandez** (1) [995313](https://platzi.com/comentario/995313/) 

	64tb waaaao eso es mucho

* **kristianando93** (1) [817552](https://platzi.com/comentario/817552/) 

	¿Cual seria un caso de uso en el cual nos sea útil tener información replicada tanto en S3 como en una base de datos relacional?.
	
	Gracias.

* **CristianCabreraA** (1) [606348](https://platzi.com/comentario/606348/) 

	por las características de performance y tunning que entrega

* **CristianCabreraA** (1) [606347](https://platzi.com/comentario/606347/) 

	Aurora al parecer es la mejor BBDD para SAP Hana?

	* **Carlos Andrés Zambrano Barrera** [606347] (1)

		Se recomienda para HANNA montar la BD en una EC2 en una instancia tipo X. Como tal SAP no ha recomendado alguna RDS como Aurora. Pero si te digo que Aurora es la mejor BD relacional del mercado.

## 0170. Aurora Serverless [15207](https://platzi.com/clases/1426-db-aws/15207-aurora-serverless/)

### Descripción:


Hasta el momento, la única base de datos relacional autoescalable que encontramos en el mercado es Aurora Serverless, una base de datos donde podemos seleccionar la mínima y máxima capacidad por instancia, a medida que la concurrencia sobre la base de datos va creciendo, esta capacidad mínima se incrementa hasta la capacidad máxima que nuestra aplicación debe soportar. Gracias a esto el precio de nuestros servicios disminuye, solo pagamos por el tiempo y la capacidad que realmente utilizamos.

### Links:

* [In The Works – Amazon Aurora Serverless | AWS News Blog](https://aws.amazon.com/es/blogs/aws/in-the-works-amazon-aurora-serverless/)

### Comentarios:

* **kristianando93** (3) [817554](https://platzi.com/comentario/817554/) 

	Cuando dices que Aurora es compatible solo con Mysql 5.6 se refiere a que la característica Serverless también la puede tener esa versión de Mysql gracias a que Aurora de alguna forma le ayuda a soportarlo?
	
	Gracias.

* **jorge-gianareas** (2) [967045](https://platzi.com/comentario/967045/) 

	Aurora Serverless  
	Hasta el momento, la única base de datos relacional autoescalable que encontramos en el mercado es Aurora Serverless, una base de datos donde podemos seleccionar la mínima y máxima capacidad por instancia, a medida que la concurrencia sobre la base de datos va creciendo, esta capacidad mínima se incrementa hasta la capacidad máxima que nuestra aplicación debe soportar. Gracias a esto el precio de nuestros servicios disminuye, solo pagamos por el tiempo y la capacidad que realmente utilizamos.

* **eimispacheco** (2) [822001](https://platzi.com/comentario/822001/) 

	Hola buenas tardes. Me podrian dar por favor una definicion de serverless y de funcion lambda? Muchas gracias. Saludos.

	* **Jean Carlos Nuñez Hernandez** [822001] (1)

		Serverless la traduccion es sin servidor, es decir, server en la nube como lo que ofrece AWS, Google cloud, IBM cloud y demas, las funciones landan son un servicio que ofrece aws para colocar pequeñas o mediana funciones de programacion, en lenguajes como java,c#,ruby,golang para que hagan determinadas acciones.

* **kristianando93** (2) [817555](https://platzi.com/comentario/817555/) 

	Es posible hacerla serverless pero que tenga un tope máximo de crecimiento?  
	Gracias.

* **María Camila Aguilar** (2) [762227](https://platzi.com/comentario/762227/) 

	Aurora Serverless sólo es compatible con MySQL

* **johncastillotellez7** (1) [1079808](https://platzi.com/comentario/1079808/) 

	advantanges> Aurora Serverless removes much of the complexity of managing DB instances and capacity.

* **Vicente Fernandez** (1) [1020824](https://platzi.com/comentario/1020824/) 

	 **Concurrencia** : se refiere al hecho de que los DBMS (SISTEMAS DE ADMINISTRACION DE BD) permiten que muchas transacciones puedan realizarse en una misma base de datos a la vez.

## 0180. Casos de uso de Aurora [15215](https://platzi.com/clases/1426-db-aws/15215-casos-de-uso4960/)

### Descripción:


### Comentarios:

* **jhon Erik calderon Rubiano** (3) [971479](https://platzi.com/comentario/971479/) 

	considero que la parte financiera requiere que no se presenten altercados en la conectividad, un caso puntual la información de la bolsa de algún país, debe tener replicas de las operaciones, y deben estar ubicados en diferentes zonas de disponibilidad, caso tal que ocurra alguna catástrofe se disponga de toda la información.

* **kristianando93** (2) [817565](https://platzi.com/comentario/817565/) 

	¿Por que al crear una db Aurora es necesario seleccionar entre SQL y Postgrest?. Pareciera que Aurora es mas como un complemento y no una base de datos independiente.
	
	Gracias

	* **ramirobga** [817565] (2)

		entieno que aurora es una customizacion de esas bases de datos. recuerda que al ser opensource, las empresas las usan para sacar versiones propias… salu2

* **raimercm** (2) [749944](https://platzi.com/comentario/749944/) 

	¿Puedo pasar la información de una bd RDS Mysql a Aurora?

	* **kristianando93** [749944] (2)

		Si , de hecho es muy compatible.
		
		Aveces pareciera que aurora fuera motor Mysql por debajo. No veo que aurora sea un motor de base de datos totalmente independiente.

	* **Vicente Fernandez** [749944] (1)

		Si, según la clase de migración de datos con el servicio de Database Migration Service se puede hacer sin ningún problema.

* **Juan Francisco Mosquera** (2) [55048](https://platzi.com/comentario/537117/) 
Como puedo calcular los costos utilizando servirles Aurora ?

	* **Diego Alexander Forero Higuera (Platzi)** [55048] (3)

		Aws tiene su calculadora <https://calculator.s3.amazonaws.com/index.html> buscas los servicios, tamaños de instancia y te va diciendo cuanto cuesta.

* **johncastillotellez7** (1) [1079857](https://platzi.com/comentario/1079857/) 

	You have an application that is only used for a few minutes several times per day or week, such as a low-volume blog site. With Aurora Serverless , you pay for only the database resources that you consume on a per-second basis.
	
	You are deploying a new application and are unsure about which instance size you need. With Aurora Serverless , you can create a database endpoint and have the database autoscale to the capacity requirements of your application.
	
	You’re running workloads where there is database usage throughout the day, but also peaks of activity that are hard to predict. An example is a traffic site that sees a surge of activity when it starts raining. With Aurora Serverless , your database autoscales capacity to meet the needs of the application’s peak load and scales back down when the surge of activity is over.
	
	Aurora Serverless is only available for the following:
	
	Aurora with MySQL version 5.6 compatibility
	
	Aurora with PostgreSQL version 10.7 compatibility  
	3306 for Aurora MySQL
	
	5432 for Aurora PostgreSQL

* **Wilmer Quintero Varela** (1) [1008521](https://platzi.com/comentario/1008521/) 

	Hola, intente crear una base de datos aurora con el motor de mysql pero no me aparece la opción de serveless.

	* **juancajamarca** [1008521] (1)

		Recuerda que debes seleccionar Aurora, en vez de MySQL, y una vez lo selecciones, te pide qué versión de MySQL manejas.

	* **johncastillotellez7** [1008521] (1)

		Aurora Serverless is only available for the following:
		
		Aurora with MySQL version 5.6 compatibility
		
		Aurora with PostgreSQL version 10.7 compatibility  
		3306 for Aurora MySQL
		
		5432 for Aurora PostgreSQL

* **Jean Carlos Nuñez Hernandez** (1) [995347](https://platzi.com/comentario/995347/) 

	Provencion contra borrado, esta funcionalidad no la conocia, me ubiera ahorrado varios problemas

* **Juan Francisco Mosquera** (1) [537117](https://platzi.com/comentario/537117/) 

	Como puedo calcular los costos utilizando servirles Aurora ?

	* **Diego Alexander Forero Higuera (Platzi)** [537117] (3)

		Aws tiene su calculadora <https://calculator.s3.amazonaws.com/index.html> buscas los servicios, tamaños de instancia y te va diciendo cuanto cuesta.

	* **Carlos Andrés Zambrano Barrera** [537117] (1)

		LO primero, para aurora serverless es porque tenes cargas muy variables en tu BD, estimar es complicado por este motivo. Recomiendo que inicialmente la midas y de ahi tomes una base del costo.

	* **Vicente Fernandez** [537117] (1)

		Es una buena pregunta, pienso que dependerá completamente de la concurrencia que tengas en tu bd. Puedes calcular un “costo máximo” al saber el máximo de capacidad que hayas seleccionado al crear la base de datos.

* **paucuaram** (1) [82852](https://platzi.com/comentario/1014030/) 
Con Aurora, cómo se pueden reemplazar las vistas materializadas de oracle??

# Introducción a DynamoDB [2923]

## 0190. Base de Datos corporativa para encuestas en DynamoDB [15239](https://platzi.com/clases/1426-db-aws/15239-base-de-datos-corporativa-para-encuestas-en-dynamo/)

### Descripción:


¡Hola! Con este segundo proyecto del curso vas a aprender a poder poner en práctica tus conocimientos en la creación, configuración y conexión a tabla de DynamoDB.

Eres el arquitecto de soluciones de una empresa y el Director de Marketing le ha pedido que debe desplegar una base de datos en la cual se almacenen las respuestas de una encuesta de clima organizacional realizada a los trabajadores de la empresa.

La encuesta tiene 5 preguntas:  
Pregunta 1 - ¿Cuál es su antigüedad en la empresa?  
Pregunta 2 - ¿Está satisfecho con su asignación salarial?  
Pregunta 3 - ¿Está contento con su posición actual?  
Pregunta 4 - ¿Quién es su jefe inmediato?  
Pregunta 5 - ¿Qué sugerencias tiene para la empresa?.

![Screen Shot 2018-11-22 at 9.41.02 AM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202018-11-22%20at%209.41.02%20AM-f9602931-17bb-486b-8180-d760d76dcc68.jpg)

* Crea una tabla en DynamoDB con encriptación habilitada en la cual guardes las respuestas de los 5 trabajadores.
* Configura la tabla con clave principal el ID EMPLEADO.
* Haz una consulta a la tabla para identificar los trabajadores que en la pregunta 2 respondieron “No”.
* Teniendo la tabla actual, tú como arquitecto ¿cuál considerarías que sería un buen índice secundario para agregar a la tabla?



No olvides compartir tus resultados, desafíos y aciertos en el panel de discusiones.

### Comentarios:

* **Jean Carlos Nuñez Hernandez** (2) [995361](https://platzi.com/comentario/995361/) 

	Esta facil el ejercicio

* **johncastillotellez7** (1) [1087956](https://platzi.com/comentario/1087956/) 

	interesante

## 0200. Características de DynamoDB [15228](https://platzi.com/clases/1426-db-aws/15228-caracteristicas-de-dynamodb/)

### Descripción:


DynamoDB es el servicio para bases de datos NOSQL de AWS completamente administrado _(AWS se encarga de todo el background para que nosotros trabajemos nuestra aplicación)_ , compuesto de varios nodos y distribuido en varias regiones _(altamente disponible con replicación en diferentes locaciones)_ , es una base de datos de baja latencia con almacenamiento en caché y es completamente escalable sin _downtime_ de nuestra aplicación.

Este servicio se basa en dos conceptos importantes: las unidades en lectura _(RCU, 4kb de bloques por segundo)_ y las unidades de escritura _(WRU, 1kb de bloques por segundo)_. Con base en estos dos parámetros se determina el costo de nuestras bases de datos y el autoescalamiento.

La unidad fundamental de DynamoDB son las tablas, que están compuestas por _items_ , que están compuestos por atributos _(por ejemplo, la tabla trabajadores está compuesta por, trabajadores, cada uno con su nombre, edad, identificación y toda su información)_. También debemos entender los conceptos de _partition key (llaves primarias para el espacio de almacenamiento)_ , _sort keys (para organizar y ordenar la información)_ y _local and global secondary index (otros atributos que podemos utilizar junto a las partition keys u otros atributos para obtener información más especifica y con mejor rendimiento)_.

### Links:

* [https://docs.aws.amazon.com/dynamodb/index.html#lang/es_es](https://docs.aws.amazon.com/dynamodb/index.html#lang/es_es)

### Comentarios:

* **jorge-gianareas** (4) [967049](https://platzi.com/comentario/967049/) 

	La unidad fundamental de DynamoDB son las tablas, que están compuestas por items, que están compuestos por atributos (por ejemplo, la tabla trabajadores está compuesta por, trabajadores, cada uno con su nombre, edad, identificación y toda su información). También debemos entender los conceptos de partition key (llaves primarias para el espacio de almacenamiento) , sort keys (para organizar y ordenar la información) y local and global secondary index (otros atributos que podemos utilizar junto a las partition keys u otros atributos para obtener información más especifica y con mejor rendimiento).

* **Jean Carlos Nuñez Hernandez** (3) [995366](https://platzi.com/comentario/995366/) 

	las particiones son los espacios de almacenamiento para almecenar la informacion

* **jorge-gianareas** (3) [967047](https://platzi.com/comentario/967047/) 

	Este servicio se basa en dos conceptos importantes: las unidades en lectura (RCU, 4kb de bloques por segundo) y las unidades de escritura (WRU, 1kb de bloques por segundo). Con base en estos dos parámetros se determina el costo de nuestras bases de datos y el autoescalamiento.

* **Jean Carlos Nuñez Hernandez** (2) [995354](https://platzi.com/comentario/995354/) 

	Dynamo === aurora, en disponibilidad y eslabilidad pero no relacional

* **jorge-gianareas** (2) [967046](https://platzi.com/comentario/967046/) 

	DynamoDB es el servicio para bases de datos NOSQL de AWS completamente administrado (AWS se encarga de todo el background para que nosotros trabajemos nuestra aplicación), compuesto de varios nodos y distribuido en varias regiones (altamente disponible con replicación en diferentes locaciones), es una base de datos de baja latencia con almacenamiento en caché y es completamente escalable sin downtime de nuestra aplicación.

* **kristianando93** (2) [817576](https://platzi.com/comentario/817576/) 

	Las bases de datos No relacionales son mas eficientes que las relacionales?  
	Cuales son las ventajas de cada una NO RELACIONAL VS RELACIONAL?  
	Muchas Gracias.

* **Cristian Camilo Alvarado Beltran** (2) [671446](https://platzi.com/comentario/671446/) 

	caracteristica importante:  
	do relacional NOSQL.

* **johncastillotellez7** (1) [1116262](https://platzi.com/comentario/1116262/) 

	DynamoDB is so powerful  
	Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It’s a fully managed, multiregion, multimaster, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. DynamoDB can handle more than 10 trillion requests per day and can support peaks of more than 20 million requests per second

	* **johncastillotellez7** [1116262] (1)

		Many of the world’s fastest growing businesses such as Lyft, Airbnb, and Redfin as well as enterprises such as Samsung, Toyota, and Capital One depend on the scale and performance of DynamoDB to support their mission-critical workloads.

	* **johncastillotellez7** [1116262] (1)

		Hundreds of thousands of AWS customers have chosen DynamoDB as their key-value and document database for mobile, web, gaming, ad tech, IoT, and other applications that need low-latency data access at any scale. Create a new table for your application and let DynamoDB handle the rest.

	* **johncastillotellez7** [1116262] (1)

		very useful from AWS that uses JSON format

* **Vicente Fernandez** (1) [1022732](https://platzi.com/comentario/1022732/) 

	DynamoDB se me parece mucho a MongoDB, por lo que veo guarda los items en formato JSON.

	* **Diego Alexander Forero Higuera (Platzi)** [1022732] (3)

		Si, también PostgreSQL tiene soporte para datos en formato JSON

	* **juancajamarca** [1022732] (1)

		Por supuesto, ambos son motores de bases de datos no relacionales. Sin embargo, si buscas una compatibilidad entre MongoDB y un servicio de AWS, deberías echarle un vistazo a DocumentDB.

* **Wilmer Quintero Varela** (1) [1008550](https://platzi.com/comentario/1008550/) 

	Particiones

* **Jean Carlos Nuñez Hernandez** (1) [995358](https://platzi.com/comentario/995358/) 

	Dynamo se replica o se autoreplica, muy cool

## 0210. Consistencia en DynamoDB [15214](https://platzi.com/clases/1426-db-aws/15214-consistencia-en-dynamodb/)

### Descripción:


La consistencia **eventual** de lectura NO puede mostrar los resultados de una tarea de escritura reciente cuando consultamos una tabla recién actualizada, además, consume los 4kb de bloques por segundo en las unidades de lectura.

Por otra parte, la consistencia **fuerte** de lectura funciona correctamente cuando consultamos una tabla y recibimos la respuesta más reciente, pero consume el doble que la consistencia eventual, así que será más costosa. Este tipo de consistencia es el adecuando para aplicaciones y casos de uso muy específicos donde la consulta y la escritura deben estar tan sincronizadas como sea posible.

### Comentarios:

* **jorge-gianareas** (4) [967053](https://platzi.com/comentario/967053/) 

	Por otra parte, la consistencia fuerte de lectura funciona correctamente cuando consultamos una tabla y recibimos la respuesta más reciente, pero consume el doble que la consistencia eventual, así que será más costosa. Este tipo de consistencia es el adecuando para aplicaciones y casos de uso muy específicos donde la consulta y la escritura deben estar tan sincronizadas como sea posible.

* **estebanvasquezvalencia** (3) [488908](https://platzi.com/comentario/488908/) 

	Excelente explicación sobre la Consistencia!!!

* **Jordi Santamaría Portolés** (2) [1018180](https://platzi.com/comentario/1018180/) 

	consistencia eventual: valores que no tienen que ser lo ultimo. Consistencia fuerte: cuando la respuesta tiene que ser la mas reciernte, consume el doble que consistencia eventual.

* **jorge-gianareas** (2) [967052](https://platzi.com/comentario/967052/) 

	La consistencia eventual de lectura NO puede mostrar los resultados de una tarea de escritura reciente cuando consultamos una tabla recién actualizada, además, consume los 4kb de bloques por segundo en las unidades de lectura.

* **johncastillotellez7** (1) [1116367](https://platzi.com/comentario/1116367/) 

	DynamoDB supports some of the world’s largest scale applications by providing consistent, single-digit millisecond response times at any scale. You can build applications with virtually unlimited throughput and storage. DynamoDB global tables replicate your data across multiple AWS Regions to give you fast, local access to data for your globally distributed applications. For use cases that require even faster access with microsecond latency, DynamoDB Accelerator (DAX) provides a fully managed in-memory cache.

	* **johncastillotellez7** [1116367] (1)

		DynamoDB is serverless with no servers to provision, patch, or manage and no software to install, maintain, or operate. DynamoDB automatically scales tables up and down to adjust for capacity and maintain performance. Availability and fault tolerance are built in, eliminating the need to architect your applications for these capabilities. DynamoDB provides both provisioned and on-demand capacity modes so that you can optimize costs by specifying capacity per workload, or paying for only the resources you consume.

	* **johncastillotellez7** [1116367] (1)

		DynamoDB supports ACID transactions to enable you to build business-critical applications at scale. DynamoDB encrypts all data by default and provides fine-grained identity and access control on all your tables. You can create full backups of hundreds of terabytes of data instantly with no performance impact to your tables, and recover to any point in time in the preceding 35 days with no downtime. DynamoDB is also backed by a service level agreement for guaranteed availability.

* **CristianCabreraA** (1) [607262](https://platzi.com/comentario/607262/) 

	muy clara la explicación

* **Ricardo Mesa Gallego** (1) [64835](https://platzi.com/comentario/682634/) 
En tema de costos($) se eleva demasiado el precio al manejar una consistencia de lectura fuerte o la diferencia en costos es mínima?

	* **Carlos Andrés Zambrano Barrera** [64835] (2)

		es el doble en unidades que vas a conseguir. el costo siempre dependera de la cantidad de datos que vas a leer por segundo y el tamano de los mismos. Asi que ten cuidado con esos valores para estimar el calculo. tamano del item en KB y lecturas por segundo.

## 0220. Creando nuestra primer tabla en DynamoDB [15211](https://platzi.com/clases/1426-db-aws/15211-creando-nuestra-primer-tabla-en-dynamodb/)

### Descripción:


### Comentarios:

* **Madrov** (5) [443521](https://platzi.com/comentario/443521/) 

	No sé si lo explique después en el curso, pero una unidad de lectura es una lectura consistente por segundo, o dos lecturas de un elemento de hasta 4KB. Y una unidad de escritura es una escritura por segundo de un elemento de hasta 1KB. Más info aquí <https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/ProvisionedThroughput.html#ItemSizeCalculations.Writes>

* **Geovany Uribe Aguirre** (2) [992889](https://platzi.com/comentario/992889/) 

	En DynamoDB, el atributo “edad” es lo mismo que el atributo “Edad” o “EDAD”? Los agrupa igual?

* **estebanvasquezvalencia** (2) [488911](https://platzi.com/comentario/488911/) 

	[](https://platzi.com/clases/1426-db-aws/15211-creando-nuestra-primer-tabla-en-dynamodb/?time=76) Es posible agregar la **Sort Key** luego de creada la tabla??

	* **Carlos Andrés Zambrano Barrera** [488911] (5)

		Puedes despues de crear la tabla crear es un Global Secondary Index pero no una sort key.

* **johncastillotellez7** (1) [1117182](https://platzi.com/comentario/1117182/) 

	This API Reference describes the low-level API for Amazon DynamoDB. Instead of making requests to the low-level API directly from your application, we recommend that you use one of the AWS Software Development Kits (SDKs) for your programming language. The AWS SDKs take care of request authentication, serialization, and connection management.

	* **johncastillotellez7** [1117182] (1)

		Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. DynamoDB lets you offload the administrative burdens of operating and scaling a distributed database so that you don’t have to worry about hardware provisioning, setup and configuration, replication, software patching, or cluster scaling. DynamoDB also offers encryption at rest, which eliminates the operational burden and complexity involved in protecting sensitive data. For more information,

* **johncastillotellez7** (1) [1117063](https://platzi.com/comentario/1117063/) 

	Common use cases:
	
	User profile stores in RTB and ad targeting  
	User events, clickstreams, and impressions data store  
	Metadata stores for assets  
	Popular-item caches

* **Ricardo Mesa Gallego** (1) [64845](https://platzi.com/comentario/682707/) 
Alguien me podría explicar por favor la diferencia entre la Clave de Ordenación(Sort Key) y los indices secundarios(Secondary Index)?? Es...

	* **Carlos Andrés Zambrano Barrera** [64845] (1)

		Son diferentes… Por ejemplo tenemos una tabla con información usuarios en la cual la hash key es el id del user… La sort key podría ser la fecha de registro en la app por la cual podemos ordenar la info del mas nuevo al mas viejo en registrarse… Ahora el secondary index puede ser una combinación entre el hask key (id del usuario) y otro campo diferente al sort, por ejemplo la ciudad de procedencia. Esto lo necesitas porque vas a hacer consultas basadas en la ciudad y no en la fecha de ingreso (que seria la sort key).
		
		Entonces el LSI es una forma de consultar data por una combinación de la hash y otro campo diferente a la sort.

* **estebanvasquezvalencia** (1) [51230](https://platzi.com/comentario/488911/) 
Es posible agregar la 

	* **Carlos Andrés Zambrano Barrera** [51230] (5)

		Puedes despues de crear la tabla crear es un Global Secondary Index pero no una sort key.

## 0230. Casos de uso en DynamoDB [15231](https://platzi.com/clases/1426-db-aws/15231-casos-de-uso-en-dynamodb/)

### Descripción:


El servicio de DynamoDB es muy útil en los siguientes casos:

* Aplicaciones móviles
* Internet de las cosas _(IoT, gracias al real time y su capacidad para ingesta de información)_
* Aplicaciones Web
* Gaming _(gracias a su alta disponibilidad, conexión y por ser no relacional)_
* Manejo de sesiones
* RealTime _(ya que no solo nos permite almacenar nuestra información, también podemos utilizar toda la data en tiempo real para alimentar otros servicios y generar otras arquitecturas)_



### Comentarios:

* **jhon Erik calderon Rubiano** (4) [973072](https://platzi.com/comentario/973072/) 

	la diferencia primordial corresponde a la capacidad de almacenamiento, en una base RDS al tener cientos de millones de datos la base al validar todas las primary key y recorrer los cubos de información pierde tiempo , por otro lado la información en una base de datos de dynamodb, permite un mayor trafico ya que no responde a la idea de interconectar toda las las estructuras de las bases y cada una puede llevar por separado la información, casos de uso principalmente en las transmisiones por directo, que manejan millones de datos pero solo corresponde a un objetivo temporal

* **jorge-gianareas** (4) [967059](https://platzi.com/comentario/967059/) 

	Aplicaciones móviles  
	Internet de las cosas (IoT, gracias al real time y su capacidad para ingesta de información)  
	Aplicaciones Web  
	Gaming (gracias a su alta disponibilidad, conexión y por ser no relacional)  
	Manejo de sesiones  
	RealTime (ya que no solo nos permite almacenar nuestra información, también podemos utilizar toda la data en tiempo real para alimentar otros servicios y generar otras arquitecturas)

* **Angelica Landazabal** (3) [1007713](https://platzi.com/comentario/1007713/) 

	Utilizaría una relacional en el momento de querer consistencia en mis datos por lo cual la crearía normalizada. Sin embargo, si deseo tener un mayor escalamiento, usaría una db no relacional además que me permite ingresar toda la cantidad de atributos que necesite para cada item.

* **Ricardo Mesa Gallego** (3) [682730](https://platzi.com/comentario/682730/) 

	RDS es una buens opcion si se tiene un motor de base de datos comun el cual no queremos ocuparnos de la administracion ni del mantenimiento ademas de ser muy facil de escalar y replicar. RDS me ofrece soporte para distintos motores de BD tanto relacionales como no relacionales  
	Por su parte Dynamodb es una base de datos no relacional la cual es muy rapida pero se usa en situaciones muy particulares.

	* **karkastell** [682730] (3)

		Dynamo serviría para recolección de información para análisis, por ejemplo actividades que suelen hacer las personas en fin de semana, géneros de música que más escuchan los estudiantes de una universidad. En estos casos pueden haber muchos atributos diferentes y en cantidades variables para cada item

* **Camilo Ortegón** (3) [560217](https://platzi.com/comentario/560217/) 

	Yo usaría RDS para construir bases de datos con modelos complejos que requieran cruce de varias tablas, como por ejemplo productos que se relacionan entre si, que pueden estar asociados a multiples categorías, que pueden ser comprados por varios usuarios.
	
	Las bases de datos NoSQL como DynamoDB me parece que son muy útiles para almacenar datos de un usuario, como por ejemplo el progreso de un usuario en el juego, con todas las medallas o retos tenga cumplidos, como no tienen estructura puedo ir creando más información en el json de cada uno sin que esto afecte los demás items.

* **alexgv04** (2) [719249](https://platzi.com/comentario/719249/) 

	creería que uno si va a usar una base de datos no relacional se debe de pensar que no se va a contar con las funcionalidades que las bases de datos relacionales nos proporcionan como lo son las claves primarias las relaciones, los joins, etc.  
	si no necesitamos todo esto y el numero de registros es considerablemente alto se podría considerar tener una base de datos no relacional como DynamoDb

* **crarrivillaga** (2) [570993](https://platzi.com/comentario/570993/) 

	Que tan recomendable es usar DynamoDB como base de datos para un ecommerce? Esto en comparacion a RDS. Gracias de antemano.

	* **Diego Alexander Forero Higuera (Platzi)** [570993] (2)

		Ya te respondí aquí <https://platzi.com/comunidad/que-tal-chics-espero-esten-bien-queria-saber-que-tan-recomendable-es-usar-dynamodb-como-base-de-datos-para-un-ecommerce-vs-rds-gracias/>

* **johncastillotellez7** (1) [1117242](https://platzi.com/comentario/1117242/) 

	Lo mas potente que se puede decir de dynamodb es su capacidad de procesamiento en milisegundos, es muy robasta, y tiene rendimiento de cualquier escala. Ej 10 Trillon de requests por dia. wow que capacidad tan imprecionante.
	
	adicional no necesita que se le instalen parches, actualizaciones. backups DRecoveries, ya que todo lo hace AWS team.  
	etc

* **johncastillotellez7** (1) [1117210](https://platzi.com/comentario/1117210/) 

	User cases  
	Shopping carts  
	Workflow engines  
	Inventory tracking and fulfillment  
	Customer profiles and accounts

	* **johncastillotellez7** [1117210] (1)

		OTros use cases  
		User transactions  
		Event-driven transaction processing  
		Fraud detection  
		Mainframe offloading and change data capture

* **Jean Carlos Nuñez Hernandez** (1) [996517](https://platzi.com/comentario/996517/) 

	DynoDB es especial para realtime, gaming y web, cool

# Particiones e Índices en DynamoDB [2924]

## 0240. Índices y particiones en DynamoDB [15224](https://platzi.com/clases/1426-db-aws/15224-particiones-en-dynamodb/)

### Descripción:


Cuando utilizamos DynamoDB los datos se almacenan en particiones, al crear una tabla, la base de datos asigna su partición para que esta pueda satisfacer el desempeño aprovisionado, y en ciertas ocasiones puede aumentar el tamaño y la cantidad de particiones para mejorar el desempeño o cuando la partición está llena. El limite de las particiones es 10GB de almacenamiento, pero también necesitamos cambiar de partición cuando superamos los niveles de lectura y escritura _(3.000 RCU y 1.000 WCU)_.

DynamoDB utiliza las **claves principales simples y compuestas** para almacenar y recuperar nuestros elementos y almacenar nuestra información con la función de hash. Cuando utilizamos claves compuestas debemos especificar los valores de la clave para leer los elementos, y el orden de los elementos depende de su clave de ordenación.

La base de datos esta optimizada para distribuir nuestros elementos de forma uniforme entre las particiones de una tabla, con independencia del número de particiones que configuramos. Sin embargo, la recomendación oficial es elegir una clave de partición con un amplio abanico de valores diferentes, es decir, claves tan aleatorias como sea posible en relación con el número de elementos de la tabla, así evitamos que la información se guarde en particiones cercanas o iguales para optimizar las tareas de lectura y escritura de la base de datos.

### Comentarios:

* **Juan David Castro (Platzi)** (5) [428949](https://platzi.com/comentario/428949/) 

	Notas de la clase:
	
	* En DynamoDB las tablas se almacenan en particiones 📦
	* La base de datos asigna las particiones de cada tabla y puede aumentar su tamaño para mejorar el desempeño o añadir más particiones cuando la partición esta llena 🛳
	* Las particiones pueden aumentar su tamaño hasta 10GB siempre y cuando no superemos los 3.000 niveles de lectura y 1.000 de escritura 🐘
	* Para almacenar elementos utilizamos claves principales simples o compuestas, DynamoDB utiliza estas claves para asignar las particiones 🤔
	* Entre más aleatorias sean las claves principales, mejor performance tiene la base de datos 🎉
	* Cuando utilizamos claves compuestas, el orden de los elementos depende de la clave de ordenación 💡
	
	

	* **juancajamarca** [428949] (1)

		Buen aporte

* **jorge-gianareas** (4) [967064](https://platzi.com/comentario/967064/) 

	La base de datos esta optimizada para distribuir nuestros elementos de forma uniforme entre las particiones de una tabla, con independencia del número de particiones que configuramos. Sin embargo, la recomendación oficial es elegir una clave de partición con un amplio abanico de valores diferentes, es decir, claves tan aleatorias como sea posible en relación con el número de elementos de la tabla, así evitamos que la información se guarde en particiones cercanas o iguales para optimizar las tareas de lectura y escritura de la base de datos.

* **jorge-gianareas** (2) [967063](https://platzi.com/comentario/967063/) 

	DynamoDB utiliza las claves principales simples y compuestas para almacenar y recuperar nuestros elementos y almacenar nuestra información con la función de hash. Cuando utilizamos claves compuestas debemos especificar los valores de la clave para leer los elementos, y el orden de los elementos depende de su clave de ordenación.

* **jorge-gianareas** (2) [967062](https://platzi.com/comentario/967062/) 

	Cuando utilizamos DynamoDB los datos se almacenan en particiones, al crear una tabla, la base de datos asigna su partición para que esta pueda satisfacer el desempeño aprovisionado, y en ciertas ocasiones puede aumentar el tamaño y la cantidad de particiones para mejorar el desempeño o cuando la partición está llena. El limite de las particiones es 10GB de almacenamiento, pero también necesitamos cambiar de partición cuando superamos los niveles de lectura y escritura (3.000 RCU y 1.000 WCU).

* **Jean Carlos Nuñez Hernandez** (1) [996524](https://platzi.com/comentario/996524/) 

	Particiones en DynamoDB son trascendentales, para seleccion de los indice, las particiones se agregan si se necesita por requerimientos

* **Yembert Quintero Cortez** (1) [825186](https://platzi.com/comentario/825186/) 

	test

## 0250. Operaciones Scan en DynamoDB [15221](https://platzi.com/clases/1426-db-aws/15221-operaciones-scan-en-dynamodb/)

### Descripción:


Las **Operaciones Scan** se encargan de escanear por completo nuestras tablas para examinar todos sus elementos y comprobar si presentan los valores solicitados, pero son muy poco eficientes ya que utilizan bastantes unidades de lectura y aumentan los costos de nuestra base de datos, debemos evitar estas operaciones para tablas grandes.

AWS nos recomienda realizar operaciones pequeñas a lo largo del tiempo en vez de hacer una sola operación muy larga, también podemos configurar límites de tamaño para evitar los escaneos completos y duplicar nuestras tablas para realizar estas operaciones sobre tablas no principales y no afectar su rendimiento.

### Comentarios:

* **Juan David Castro (Platzi)** (5) [428946](https://platzi.com/comentario/428946/) 

	Notas de la clase:
	
	* Las operaciones scan examinan los elementos de nuestras tablas para comprobar sus valores 🤓
	* Son completamente ineficientes y deberíamos evitarlas 👎 😥😠
	* Pueden gastar todos los niveles de lectura de la base de datos
	* Haciendo operaciones pequeñas a lo largo del tiempo y configurando límites podemos evitar el escaneo completo y subir los precios 🤔
	* Si duplicamos las tablas para las operaciones NO afectamos el performance de las tablas principales 🆗
	
	

* **jorge-gianareas** (3) [967066](https://platzi.com/comentario/967066/) 

	Las Operaciones Scan se encargan de escanear por completo nuestras tablas para examinar todos sus elementos y comprobar si presentan los valores solicitados, pero son muy poco eficientes ya que utilizan bastantes unidades de lectura y aumentan los costos de nuestra base de datos, debemos evitar estas operaciones para tablas grandes.

* **jorge-gianareas** (2) [967067](https://platzi.com/comentario/967067/) 

	AWS nos recomienda realizar operaciones pequeñas a lo largo del tiempo en vez de hacer una sola operación muy larga, también podemos configurar límites de tamaño para evitar los escaneos completos y duplicar nuestras tablas para realizar estas operaciones sobre tablas no principales y no afectar su rendimiento.

* **Juan David Castro (Platzi)** (2) [428948](https://platzi.com/comentario/428948/) 

	Entonces, ¿para qué sirven las operaciones Scan? ¿cuando SI deberíamos utilizarlas? 😅

	* **Carlos Andrés Zambrano Barrera** [428948] (5)

		Las operaciones Scan se utilizan en tablas en las cuales su diseño inicial (las llaves) no es optimo para que una consulta (query) pueda encontrar los datos, para esos casos usaríamos SCAN. Aunque si tu Dynamo esta bien diseñada en cuanto a las llaves y particiones no deberías usar Scan

	* **carlosbazanhuaman** [428948] (3)

		puedes usarlas pero aplicando un limite al Scan porque sino te va salir caro en rendimiento y dinero =).

* **juancajamarca** (1) [1039860](https://platzi.com/comentario/1039860/) 

	 **Optimización en Scan**
	
	* Reducir el tamaño de la página usando el parámetro LIMIT en el request.
	* Se pueden duplicar tablas para hacer operaciones Scan sobre tablas no principales.
	
	

* **Juan David Castro (Platzi)** (1) [46222](https://platzi.com/comentario/428948/) 
Entonces, ¿para qué sirven las operaciones Scan? ¿cuando SI deberíamos utilizarlas? 😅

	* **Carlos Andrés Zambrano Barrera** [46222] (5)

		Las operaciones Scan se utilizan en tablas en las cuales su diseño inicial (las llaves) no es optimo para que una consulta (query) pueda encontrar los datos, para esos casos usaríamos SCAN. Aunque si tu Dynamo esta bien diseñada en cuanto a las llaves y particiones no deberías usar Scan

## 0260. Operaciones Query en DynamoDB [15220](https://platzi.com/clases/1426-db-aws/15220-operaciones-query-en-dynamodb/)

### Descripción:


Las **Operaciones Query** _(operaciones de consulta)_ nos permiten buscar elementos en cualquier tabla o índice secundario en base a su clave principal compuesta para optimizar la petición.

En vez de escanear toda la tabla _(como en las operaciones Scan)_ , vamos a especificar los criterios de búsqueda utilizando una expresión de condición clave _(una cadena que determina los elementos que vamos a leer en la tabla o el índice)_ , especificamos el nombre y valor la clave de partición como una condición de igualdad, podemos realizar consultas utilizando diferentes operadores para encontrar los resultados con mejor precisión.

También podemos limitar el número de elementos que esperamos en los resultados para agilizar las operaciones, pero no obtenemos información tan detallada de la capacidad de lectura que consumimos.

El desafío de esta clase es responder en la sección de comentarios un caso de uso de DynamoDB y cuáles serian sus ventajas frente a los servicios RDS.

### Comentarios:

* **Geovany Uribe Aguirre** (3) [993037](https://platzi.com/comentario/993037/) 

	Al final dice que debemos ejecutar en lo posible operaciones de consulta en vez de Queries (no eran lo mismo) o es operaciones de consulta o queries en vez de scans?

* **Camilo Ortegón** (3) [560238](https://platzi.com/comentario/560238/) 

	Yo usaría DynamoDB cuando con pocas tablas (1 a 5) puedo almacenar todos los datos que necesito. Por ejemplo ahora estoy construyendo un blog que lee archivos .md de Github, y me basta con 1 o 2 tablas, sale más económico que tener una base de datos relacional prendida todo el tiempo.

* **Cristian David Montoya Montoya** (3) [557392](https://platzi.com/comentario/557392/) 

	Yo utlizaria DynamoDB en el caso puntual de un chat, ya que por la variedad de información (texto, docs, multimedia) que se maneja en un app de ese tipo Dynamo cuenta con la flexibidad para alojar la data

* **jhon Erik calderon Rubiano** (2) [973113](https://platzi.com/comentario/973113/) 

	en el sector bancario en la cantidad de transacciones generadas por cada uno de los usuarios, debido al alto flujo de informacion, a la lozalicaionn el tipo de cuenta, de moneda, la conversion local con el dolar, y el tipo de producto se podria usar

* **jorge-gianareas** (2) [967074](https://platzi.com/comentario/967074/) 

	El desafío de esta clase es responder en la sección de comentarios un caso de uso de DynamoDB y cuáles serian sus ventajas frente a los servicios RDS.

* **jorge-gianareas** (2) [967072](https://platzi.com/comentario/967072/) 

	También podemos limitar el número de elementos que esperamos en los resultados para agilizar las operaciones, pero no obtenemos información tan detallada de la capacidad de lectura que consumimos.

* **jorge-gianareas** (2) [967071](https://platzi.com/comentario/967071/) 

	En vez de escanear toda la tabla (como en las operaciones Scan), vamos a especificar los criterios de búsqueda utilizando una expresión de condición clave (una cadena que determina los elementos que vamos a leer en la tabla o el índice), especificamos el nombre y valor la clave de partición como una condición de igualdad, podemos realizar consultas utilizando diferentes operadores para encontrar los resultados con mejor precisión.

* **jorge-gianareas** (2) [967070](https://platzi.com/comentario/967070/) 

	Las Operaciones Query (operaciones de consulta) nos permiten buscar elementos en cualquier tabla o índice secundario en base a su clave principal compuesta para optimizar la petición.

* **kristianando93** (2) [818201](https://platzi.com/comentario/818201/) 

	La recomendación en el minuto 5:02 de recomendar Consultas en lugar de Querys es correcto?  
	Consulta y Query para DynamoDB son sinónimos. Quizás te referías a Scan o examinar?  
	Gracias.

* **Enzo Aliatis** (2) [678712](https://platzi.com/comentario/678712/) 

	Yo usaría DynamoDB en el caso donde no tengo relaciones ni tampoco lo que necesite sea tan complejo, donde tenga pocas tablas.

* **josehernandezrcom** (2) [647521](https://platzi.com/comentario/647521/) 

	según la recomendación de ejecución de consultas en lugar de queries, entonces sería correcto desarrollar un sistema CRM con solo Dynamo?

	* **Carlos Andrés Zambrano Barrera** [647521] (3)

		Pero ten en cuenta que si tienes un CRM seria data relacional! Tabla clientes, pedidos, compras… Entonces sería mejor una Aurora.

* **enriquemacallums** (2) [64925](https://platzi.com/comentario/683702/) 
Buenas una pregunta que id principal se recomienda para una tabla en dynamodb que va almacenar datos de una fotografía (labels de informa...

	* **Carlos Andrés Zambrano Barrera** [64925] (2)

		un timestamp podria funcionar.

## 0270. Demo de operaciones Scan y Query en DynamoDB [15204](https://platzi.com/clases/1426-db-aws/15204-demo-de-operaciones-scan-y-query-en-dynamodb/)

### Descripción:


### Comentarios:

* **Camilo Ortegón** (7) [560249](https://platzi.com/comentario/560249/) 

	Si con la operación “query” el atributo de partición es obligatorio, no es muy útil usarlo para consultar por ejemplo todos los usuarios que tengan una edad, porque cada usuario tendría un id diferente. Quedaríamos solo con la operación “scan” como única alternativa para hacer búsquedas.

	* **diegomtzb** [560249] (3)

		Al parecer tienes razón, en ese caso en especifico, en realidad dynamonDB, aunque es una base de datos No relacional, no funciona como mongo o el mismo firebase, creo que la idea del id, es tener un referente para almacenar. ejemplo si tienes una lista de post de un escritor, el id podría ser el correo del escritor, con eso todas sus publicaciones estarían almacenadas en un mismo espacio de memoria.

	* **Vicente Fernandez** [560249] (1)

		Eso es lo que estaba pensando, nosotros en la mayoría de la veces al consultar una base de datos no conocemos el valor de las particiones, si no mas bien, hacemos consultas basadas en condiciones.

* **Vicente Fernandez** (1) [1027600](https://platzi.com/comentario/1027600/) 

	Alguien me puede aclarar cuál es la diferencia al seleccionar atributos: todos o proyectado? Al momento de hacer una consulta…

## 0280. ¿Qué es Local Seconday Index [22696](https://platzi.com/clases/1426-db-aws/22696-que-es-local-seconday-index/)

### Descripción:


En una tabla de Dynamo cada ítem debe contener una clave primaria única. Esta llave debe tener una clave de partición y opcionalmente puede tener una range key (Sort Key). Dentro de la partición, los ítems son ordenados por la range key, en los casos donde la información que necesitemos coincida con nuestra range key el acceso a los elementos va a ser mucho más rápido.

![Screen Shot 2019-08-26 at 3.42.17 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-08-26%20at%203.42.17%20PM-33fea8f2-2c05-4687-b7ff-8673e77b158c.jpg) ![Screen Shot 2019-08-26 at 3.42.04 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-08-26%20at%203.42.04%20PM-e06c699e-6595-417d-8cc1-ee93973ebe46.jpg)

Sin embargo se presentan casos en los cuales la información que necesitamos se encuentra en otro atributo totalmente diferente a la range key, para estos casos podemos utilizar un Local Secondary Index (LSI) el cual tiene la misma clave de partición pero puede tener una range key completamente diferente (por tabla se pueden crear hasta 5 LSI), se debe tener en cuenta que los LSI solamente se pueden crear al momento de crear la tabla, una vez creada no se podrán crear LSI.

![Screen Shot 2019-08-26 at 3.42.30 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-08-26%20at%203.42.30%20PM-99f5ff26-d343-48c2-8d1a-d78427999fb4.jpg)

Por ejemplo si tenemos la una tabla que mantiene el puntaje de jugadores en diferentes juegos online.

La tabla Scores está conformada de la siguiente forma:

* **Llave de partición:** GameName → Nombre del Juego

* **Llave de ordenamiento (Range o Sort Key):** LastGameMatch → Fecha de la última partida disputada en el juego.


![Screen Shot 2019-08-22 at 3.11.33 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-08-22%20at%203.11.33%20PM-e773839e-0727-46d4-853f-7eb9c94a5a0b.jpg)

Para la tabla SCORE podríamos obtener información de los juegos y la fecha de la última partida disputada en el juego por diferente usuario.

Ahora supongamos que necesitamos responder preguntas diferentes como:

* ¿Cuál es el puntaje máximo en un determinado juego?

* ¿Cuál es la partida ganada más antigua en el juego?




No sería posible obtener la información solicitada con los índices que se tienen actualmente, tendríamos que hacer una operación SCAN que consumiría muchas unidades de lectura.

Para este caso la mejor solución sería utilizar LSI:

* GameName y Score.

* GameName y LastWin.




Con estos LSI podríamos consultar la data con la misma llave de partición (GameName) y obtener resultados sobre otras llaves range como Score y LastWin. Esto nos ayudaría en nuestra tabla a obtener los datos que necesitamos de forma más eficiente y también evitamos el consumo de unidades de lectura de la tabla RCU lo cual se verá reflejado en un ahorro de costos.

### Comentarios:

* **AlexanderJ** (1) [1082320](https://platzi.com/comentario/1082320/) 

	Excelente Información.

# DynamoDB Streams y Replicación [2917]

## 0290. Características Streams y Replicación en DynamoDB [15242](https://platzi.com/clases/1426-db-aws/15242-caracteristicas-streams-y-replicacion-en-dynamodb3/)

### Descripción:


 **DynamoDB Streams** nos proporciona una secuencia ordenada por tiempo de cambios de los elementos de cualquier tabla, es decir, guarda los cambios de nuestros elementos para que podamos procesar y consumir esta información, podemos ampliar el poder de DynamoDB con replicación entre regiones, análisis continuo con integración a Redshift, notificación de cambios y muchos otros escenarios.

Estos streams capturan una secuencia en orden cronológico de las modificaciones de los elementos de una tabla y almacenan la información por 24 horas. Cada registro de secuencia contiene la información sobre una sola modificación a los datos de un elemento de la tabla. Nuestras aplicaciones pueden obtener acceso a este registro y ver los elements de datos tal y como se encontraban antes y después.

### Comentarios:

* **Arjun4_0** (4) [574467](https://platzi.com/comentario/574467/) 

	Se me ocurre que la bd de Whatsapp que guarda los datos de Status de sus usuarios utiliza esta funcion Dynamo Stream

* **jorge-gianareas** (3) [967080](https://platzi.com/comentario/967080/) 

	Estos streams capturan una secuencia en orden cronológico de las modificaciones de los elementos de una tabla y almacenan la información por 24 horas. Cada registro de secuencia contiene la información sobre una sola modificación a los datos de un elemento de la tabla. Nuestras aplicaciones pueden obtener acceso a este registro y ver los elements de datos tal y como se encontraban antes y después.

* **jorge-gianareas** (2) [967077](https://platzi.com/comentario/967077/) 

	Características Streams y Replicación en DynamoDB  
	DynamoDB Streams nos proporciona una secuencia ordenada por tiempo de cambios de los elementos de cualquier tabla, es decir, guarda los cambios de nuestros elementos para que podamos procesar y consumir esta información, podemos ampliar el poder de DynamoDB con replicación entre regiones, análisis continuo con integración a Redshift, notificación de cambios y muchos otros escenarios.
	
	Estos streams capturan una secuencia en orden cronológico de las modificaciones de los elementos de una tabla y almacenan la información por 24 horas. Cada registro de secuencia contiene la información sobre una sola modificación a los datos de un elemento de la tabla. Nuestras aplicaciones pueden obtener acceso a este registro y ver los elements de datos tal y como se encontraban antes y después.

* **kristianando93** (2) [818213](https://platzi.com/comentario/818213/) 

	En DynamoDB se pueden realizar consultas CRUD en su totalidad?  
	Gracias.

## 0300. Casos de uso Streams y Replicación en DynamoDB [15223](https://platzi.com/clases/1426-db-aws/15223-casos-de-uso-streams-y-replicacion-en-dynamodb/)

### Descripción:


### Comentarios:

* **Juan David Castro (Platzi)** (4) [428942](https://platzi.com/comentario/428942/) 

	Cuando construimos aplicaciones en tiempo real con DynamoDB Streams, ¿podemos hacer una consulta común y corriente de la base de datos y después actualizar la información leyendo el registro de los últimos cambios?

	* **Carlos Andrés Zambrano Barrera** [428942] (4)

		Si, la idea de los streams son para aplicaciones Real Time, en tu caso se podría hacer la consulta y la actualización sin problemas.

* **Juan David Castro (Platzi)** (3) [428941](https://platzi.com/comentario/428941/) 

	Casos de uso:
	
	* 🔔 Notificaciones _(tipo “Bienvenido al sistema, {[user.name](http://user.name)}”)_
	* 🔀 Replicación con funciones lambda
	* 📨 Registro y correo de bienvenida
	
	

* **alexgv04** (2) [719308](https://platzi.com/comentario/719308/) 

	un caso de uso puede ser una lambda que este conectada a twitter y se requieran almacenar los twitt de una cuenta en DynamoDB después analizar los twiit nuevos.

* **albertnavas** (2) [428542](https://platzi.com/comentario/428542/) 

	La clase anterior no funciona. La página se ve en blanco.

	* **estebanvasquezvalencia** [428542] (1)

		Ya está funcional!

	* **cocoapuffx** [428542] (1)

		Yo si la pude ver.

* **Jean Carlos Nuñez Hernandez** (1) [999937](https://platzi.com/comentario/999937/) 

	Funcion lambda ejecuta un codigo con una funcion en particular

* **Juan David Castro (Platzi)** (1) [46220](https://platzi.com/comentario/428942/) 
Cuando construimos aplicaciones en tiempo real con DynamoDB Streams, ¿podemos hacer una consulta común y corriente de la base de datos y ...

	* **Carlos Andrés Zambrano Barrera** [46220] (4)

		Si, la idea de los streams son para aplicaciones Real Time, en tu caso se podría hacer la consulta y la actualización sin problemas.

## 0310. DAX DinamoDB Accelerator [15209](https://platzi.com/clases/1426-db-aws/15209-dax/)

### Descripción:


DAX _(DynamoDB Accelerator)_ es un cluster de caché completamente administrado por AWS y de alta disponibilidad para DynamoDB con un rendimiento de hasta 10 veces superior _(de milisegundos a microsegundos)_ y soporta millones de solicitudes por segundo.

Entre sus características encontramos la encriptación en reposo, podemos utilizar hasta 10 nodos y se puede seleccionar la zona de disponibilidad donde se desplegará el cluster. Podemos utilizar instancias _small_ y _medium_ para cargas de prueba, de resto todas son de tipo R _(optimizadas en memoria)_.

### Comentarios:

* **Juan David Castro (Platzi)** (4) [428940](https://platzi.com/comentario/428940/) 

	En el caso de uso del profe, las consultas a una base de datos con 60 mil usuarios se pudo reducir de 1 segundo a 200 milisegundos. ¡¡WOW WOW WOW!! 😱😎 🚈🔌 🦁💪

* **jhon Erik calderon Rubiano** (3) [973152](https://platzi.com/comentario/973152/) 

	creo que seria primordial en el caso de una transmision en directo del mundial, pero que a parte de solo reproducir el juego , le permita interactuar entre los usuarios que estan siendo espectadores, desde distintos paises y distintas zonas de disponibilidad, requeriria dax, para procesar el ingreso de cada uno de los usuarios, pues hablamos de mas de 100 millones de conexiones simultaneas

* **jorge-gianareas** (3) [967082](https://platzi.com/comentario/967082/) 

	Entre sus características encontramos la encriptación en reposo, podemos utilizar hasta 10 nodos y se puede seleccionar la zona de disponibilidad donde se desplegará el cluster. Podemos utilizar instancias small y medium para cargas de prueba, de resto todas son de tipo R (optimizadas en memoria).

* **jorge-gianareas** (2) [967081](https://platzi.com/comentario/967081/) 

	DAX (DynamoDB Accelerator) es un cluster de caché completamente administrado por AWS y de alta disponibilidad para DynamoDB con un rendimiento de hasta 10 veces superior (de milisegundos a microsegundos) y soporta millones de solicitudes por segundo.

* **Vicente Fernandez** (1) [1030062](https://platzi.com/comentario/1030062/) 

	Me surgieron dos dudas en esta clase:
	
	  1. DAX es un cluster caché? Es decir la información estará solo por cierto tiempo en DAX? No entiendo muy bien su funcionamiento
	
	  2. Los nodos son replicas de lecturas?
	
	
	

* **Angelica Landazabal** (1) [1008588](https://platzi.com/comentario/1008588/) 

	Usarìa DAX para el registro de las transacciones en un banco debido al corto tiempo de respuesta que contiene.

* **Jean Carlos Nuñez Hernandez** (1) [999948](https://platzi.com/comentario/999948/) 

	DAX para aplicacion en real time y el tiempo de respuesta es lo critico

* **Jean Carlos Nuñez Hernandez** (1) [999944](https://platzi.com/comentario/999944/) 

	Dax permite hasta diez nodo

* **Jean Carlos Nuñez Hernandez** (1) [999943](https://platzi.com/comentario/999943/) 

	DAX es enfocadio enfocado en cache

# Contenido Bonus [2925]

## 0320. Conclusiones [15225](https://platzi.com/clases/1426-db-aws/15225-conclusiones/)

### Descripción:


¡Felicitaciones por terminar el curso! Aprendimos sobre los servicios de bases de datos relacionales y no relacionales en AWS, sus principales características, diferencias y casos de uso. Ahora tienes el criterio necesario para decidir cuándo utilizar estos servicios.

Conclusiones del servicio RDS:

  1. Siempre que desplegamos bases de datos en producción es muy recomendado utilizar los despliegues en diferentes zonas con el servicio Multi AZ.
  2. Tenemos diferentes estrategias para optimizar el _performance_ de nuestra base de datos, por ejemplo, implementar réplicas de lectura, utilizar bases de datos en memoria y dividir la base de datos en otras más pequeñas.
  3. El periodo de retención de los backups de nuestra base de datos son máximo 35 días.
  4. Debemos tener en cuenta los tipos de migración _(homogéneas y heterogéneas)_ cuando vamos a migrar nuestra base de datos.
  5. AuroraDB es la base de datos más robusta y potente para grandes cargas de trabajo de AWS, también es la única con servicio de serverless y autoescalamiento.



Conclusiones del servicio DynamoDB:

* Es recomendado evitar las operaciones Scan para no afectar la capacidad aprovisionada, en cambio, las operaciones Query funcionan mucho mejor para el rendimiento de la base de datos.
* La función de autoscaling se puede programar con lectura y escritura pero debemos tener en cuenta los costos.
* Es clave elegir una llave principal adecuada para no afectar el performance de nuestra base de datos, entre más aleatoria sea este valor, mejor será el rendimiento.
* Con DynamoDB Streams podemos crear arquitecturas en tiempo real para diferentes aplicaciones.
* Cuando tenemos una tabla muy grande, configurar el particionamiento y los límites del mismo son fundamentales.



### Comentarios:

* **Jonathan Rodriguez Castro** (5) [690670](https://platzi.com/comentario/690670/) 

	Buen curso introductorio de DynamoDB.  
	Se agradecería una continuación con información mas avanzada de dynamoDB con casos de uso mas reales y prácticos de implementación, con mas entidades y componentes y no solo una tabla básica con pocos atributos.  
	Tal vez un Ecommerce básico o gestión de Mapas (como lo sugiere otro estudiante), objeto ver las capacidades y alcances del motor no relacional de AWS.
	
	Un saludo 😉

* **jorge-gianareas** (3) [967083](https://platzi.com/comentario/967083/) 

	Conclusiones del servicio RDS:
	
	Siempre que desplegamos bases de datos en producción es muy recomendado utilizar los despliegues en diferentes zonas con el servicio Multi AZ.  
	Tenemos diferentes estrategias para optimizar el performance de nuestra base de datos, por ejemplo, implementar réplicas de lectura, utilizar bases de datos en memoria y dividir la base de datos en otras más pequeñas.  
	El periodo de retención de los backups de nuestra base de datos son máximo 35 días.  
	Debemos tener en cuenta los tipos de migración (homogéneas y heterogéneas) cuando vamos a migrar nuestra base de datos.  
	AhororaDB es la base de datos más robusta y potente para grandes cargas de trabajo de AWS, también es la única con servicio de serverless y autoescalamiento.

* **Juan Sebastian Piedrahita Gonzalez** (3) [693750](https://platzi.com/comentario/693750/) 

	Buen curso gracias, sigue faltando el curso o las secciones para utilizar la CLI.

* **juancamilocruzfranco** (3) [596662](https://platzi.com/comentario/596662/) 

	Me gustó el curso, aunque esta un poco básico, hubiera querido mas info acerca del local index que no se mencionó, y más profundización en el tema de consultas sobre mapas, listas y tipos de datos SS, NS, B y BS. Algo mas avanzado para gente que ya sabe lo básico de dynamodb.

* **jorge-gianareas** (2) [967084](https://platzi.com/comentario/967084/) 

	Conclusiones del servicio DynamoDB:
	
	Es recomendado evitar las operaciones Scan para no afectar la capacidad aprovisionada, en cambio, las operaciones Query funcionan mucho mejor para el rendimiento de la base de datos.  
	La función de autoscaling se puede programar con lectura y escritura pero debemos tener en cuenta los costos.  
	Es clave elegir una llave principal adecuada para no afectar el performance de nuestra base de datos, entre más aleatoria sea este valor, mejor será el rendimiento.  
	Con DynamoDB Streams podemos crear arquitecturas en tiempo real para diferentes aplicaciones.  
	Cuando tenemos una tabla muy grande, configurar el particionamiento y los límites del mismo son fundamentales.

* **diegoramirezar** (2) [733827](https://platzi.com/comentario/733827/) 

	Muy buen curso , me queda la pregunta de cómo entraría a funcionar estos conceptos en una arquitectura de microservicios.

* **Marollyn Jisselly Alvarado Navarro** (2) [692100](https://platzi.com/comentario/692100/) 

	Muchas gracias… excelente curso…

* **hanuman80** (2) [572472](https://platzi.com/comentario/572472/) 

	Gracias Carlos, excelente curso. Muy bien explicado todo.

* **cocoapuffx** (2) [571320](https://platzi.com/comentario/571320/) 

	Gracias Carlos, muy buena introducción a las bases de datos de AWS.

* **alexgv04** (1) [67206](https://platzi.com/comentario/719330/) 
muy buen curso, que recomiendas para la certificación aws practitioner 

	* **Carlos Andrés Zambrano Barrera** [67206] (2)

		Realmente no te la recomiendo tanto, es más de enfoque comercial. Te aconsejo comiences por la de AWS solutions architect associate o developer associate. la de practicioner se enfoca más en Pricing, trusted advisor.

