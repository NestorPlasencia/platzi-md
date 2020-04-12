[Curso de PostgreSQL 1480](https://platzi.com/cursos/postgresql)

# Configurar Postgres [4835]

## 0010. Bienvenida al curso [24175](https://platzi.com/clases/1480-postgresql/24175-bienvenida-al-curso/)

### Descripción:


### Comentarios:

* **Diego Bastidas** (4) [901118](https://platzi.com/comentario/901118/) 

	Que bueno sería un curso de técnicas para mejorar las consultas, tanto en velocidad como en escritura.

* **hydroxseguridad** (3) [835330](https://platzi.com/comentario/835330/) 

	A darle!

* **werner-us** (3) [834956](https://platzi.com/comentario/834956/) 

	de lo mas esperado, 😄 a darle

* **Nadir Antonio Soza Solis** (2) [837856](https://platzi.com/comentario/837856/) 

	Espero que este curso sea mas completo que el anterior

* **dbzdavidbaez** (2) [835711](https://platzi.com/comentario/835711/) 

	Vamos a aprender PostgreSQL…

* **jezz-barrientos** (1) [1106030](https://platzi.com/comentario/1106030/) 

	Gran intro, lo que me hacia falta

* **juanma_9206** (1) [1103413](https://platzi.com/comentario/1103413/) 

	Y aquí vamos de nuevo! 😄

* **Adrián Andrés Sosa** (1) [1046576](https://platzi.com/comentario/1046576/) 

	Genial!

* **Angel de Jesus Quintero Pereira** (1) [1018949](https://platzi.com/comentario/1018949/) 

	Veremos en este curso como crear PL, triggers y replicas 😘

* **Angel de Jesus Quintero Pereira** (1) [1018948](https://platzi.com/comentario/1018948/) 

	❤

* **Joker11** (1) [993979](https://platzi.com/comentario/993979/) 

	Nunca pares de aprender !

* **Maxc_Martinez** (1) [963043](https://platzi.com/comentario/963043/) 

	a seguir aprendiendo 😄

* **Moisés Cedeño** (1) [962436](https://platzi.com/comentario/962436/) 

	¡Empezamos!

* **Jhoan Steve Sandoval Meneses** (1) [953068](https://platzi.com/comentario/953068/) 

	¿ Buenas como se configura postgrest para caracteres especiales ?  
	tengo los siguientes errores durante inserciones:
	
	ERROR: carácter con secuencia de bytes 0x8d en co  
	dificación «WIN1252» no tiene equivalente en la codificación «UTF8»
	
	ERROR: carácter con secuencia de bytes 0x8d en co  
	dificación «WIN1252» no tiene equivalente en la codificación «UTF8»
	
	ERROR: carácter con secuencia de bytes 0x81 en codificación «WIN1252» no tiene equivalente en la codificación «UTF8»

	* **Diego Armando Bravo Sanabria** [953068] (1)

		Me sucedió algo parecido, estaba haciendo inserciones de archivos .csv a postgreSQL y generaba el mismo error.  
		Lo solucione con la herramienta **EditPat-Pro** en la cual modifiqué el tipo de codificación del archivo .csv de “WIN1252” a “ **UTF8** ” y funciono perfectamente, espero te pueda ayudar, Saludos.

	* **Diego Armando Bravo Sanabria** [953068] (1)

		Debes tener en cuenta a la hora de la** creación de la DB el tipo de codificación**, por defecto es codificación: “UTF8” por ende todos los registros que se hagan a esa DB deben ser “UTF8”. Saludos.

* **HeartHunter** (1) [941591](https://platzi.com/comentario/941591/) 

	Empezando

* **brayan-meza-castillo** (1) [896606](https://platzi.com/comentario/896606/) 

	motivación 100%

* **Brayan Mamani** (1) [855001](https://platzi.com/comentario/855001/) 

	Muchas expectativas por este curso.

* **gydoar** (1) [838794](https://platzi.com/comentario/838794/) 

	Esperemos que este si sea.

## 0020. ¿Qué es Postgresql [24176](https://platzi.com/clases/1480-postgresql/24176-que-es-postgresql/)

### Descripción:


### Links:

* [Qué es el teorema CAP y cómo elegir la base de datos para tu proyecto](https://platzi.com/blog/que-es-el-teorema-cap-y-como-elegir-la-base-de-datos-para-tu-proyecto)

* [PostgreSQL: The world's most advanced open source database](https://www.postgresql.org/)

### Comentarios:

* **Abril Darynka Tapia Sosa** (12) [927997](https://platzi.com/comentario/927997/) 

	• **A** : Atomicity – Atomicidad -> Separar las funciones desarrolladas en la BD como pequeñas tareas y ejecutarlas como un todo. Si alguna tarea falla se hace un rollback(Se deshacen los cambios)  
	• **C** : Consistency – Consistencia -> Todo lo que se desarrolló en base al objeto relacional. Los datos tienen congruencia  
	• **I** : Isolation – Aislamiento -> Varias tareas ejecutándose al mismo tiempo dentro de la BD  
	• **D** : Durability – Durabilidad -> Puedes tener seguridad que la información no se perderá por un fallo catastrófico. PostgreSQL guarda la información en una Bitácora

	* **Jaime Andrés Martínez Rodríguez** [927997] (1)

		Muy buen aporte

* **Luis Rodrigo Alvarez Herrera** (7) [834705](https://platzi.com/comentario/834705/) 

	por fin esta este curso!!!

* **Kevin Brayan Luna Figueroa** (5) [838366](https://platzi.com/comentario/838366/) 

	Mucho tiempo estuve esperando este curso!! 😃

* **Nadir Antonio Soza Solis** (5) [837860](https://platzi.com/comentario/837860/) 

	Me da mucha confianza este profesor, se nota que conoce mucho del tema.

* **dbzdavidbaez** (5) [835754](https://platzi.com/comentario/835754/) 

	Postgress The World’s Most Advanced Open Source Relational Database

* **hydroxseguridad** (5) [835357](https://platzi.com/comentario/835357/) 

	Me llamo mucho la atencion este SGBD, porque hace 1 mes hubo un congreso de seguridad informatica en referencia a las entidades bancarias de paises latinoamericanos que usan Postgresql para sus fines comerciales. Es interesante!

	* **TUDz** [835357] (3)

		Es bastante interesante lo que comentas, de hecho, debido a las ventajas de Postgres muchas empresas están migrando desde sistemas en Oracle o SQL Server a este SGBD.

* **Bernardino Villagra Baez** (4) [870467](https://platzi.com/comentario/870467/) 

	PostgreSQL cumple ACID
	
	A atomicidad  
	C consistencia  
	I (isolation) aislamiento  
	D durabilidad

* **TUDz** (4) [836031](https://platzi.com/comentario/836031/) 

	Excelente, vengo de Oracle BD y con ese curso quiero aprender las bases para migrarme por completo a Postgres.

* **cristianwalteros** (3) [835468](https://platzi.com/comentario/835468/) 

	El curso se ve bastante interesante

* **Jorge Ernesto Auad Oliva** (3) [835272](https://platzi.com/comentario/835272/) 

	genial a aprender!!

* **Jose Villarroel** (2) [1021610](https://platzi.com/comentario/1021610/) 

	 **Por qué PostgreSQL**
	
	* Tipos de Datos
	* Integridad de Datos
	* Concurrencia. Rendimiento
	* Fiabilidad, recuperación ante desastres
	* Seguridad
	* Extensibilidad
	* Internacionalización, Búsqueda de texto.
	
	

* **Cristopher Tolentino** (2) [835780](https://platzi.com/comentario/835780/) 

	Awesome!!

* **Jesus Alejandro Lechuga Ortega** (1) [1118369](https://platzi.com/comentario/1118369/) 

	Una BD, poderosa, ¿all-for-one acaso?

* **Angel de Jesus Quintero Pereira** (1) [1019472](https://platzi.com/comentario/1019472/) 

	Atomicidad = desarrollar las funciones en pequeñas tareas y hacer que funcionen como un todo. Sí al ejecutarse las funciones y cada una cumple su tarea y todo termina bien no habrá problemas, pero sí algo ocurre se puede hacer un roll-back y esto no era posible en el pasado.

* **Angel de Jesus Quintero Pereira** (1) [1019329](https://platzi.com/comentario/1019329/) 

	PgSQL cumple el estándar A.C.I.D: Atomicity-Atomicidad, Consistency-Consistencia, Isolation-Aislamiento, Durability-Durabilidad.

* **Angel de Jesus Quintero Pereira** (1) [1019311](https://platzi.com/comentario/1019311/) 

	PgSQL posee servicios de PostGIS y PL/PgSQL, son los servicios de desarrollo interno. El primero es un servicio de geolocalización que tiene que ver con mapas, puntos y esto te libra usar software de terceros. El segundo te permite desarrollar funciones Backend en el motor

* **Angel de Jesus Quintero Pereira** (1) [1019309](https://platzi.com/comentario/1019309/) 

	PostgreSQL utiliza como elemento principal de su núcleo el Objeto-Relacional, lo que pretende es que las bases de datos tenga una estructura como la del desarrollo de POO, esto permite que la información este estructurada y relacionada ya que antes las BD solo almacenaban.

* **Angel de Jesus Quintero Pereira** (1) [1019291](https://platzi.com/comentario/1019291/) 

	PostgreSQL es Open Source esto quiere que es de código abierto y a su vez tiene una comunidad que constantemente le está haciendo mantenimiento y actualizando su código

* **Angel de Jesus Quintero Pereira** (1) [1019276](https://platzi.com/comentario/1019276/) 

	1- El motor de bases datos (RDBMS) es quién estructura toda la información de la base de dato. 2- El servidor es una computadora dónde se instala el motor de base de dato. 3- La bases es la información ordenada, relacionada y estructurada a la cual accedemos con SQL

* **Angel de Jesus Quintero Pereira** (1) [1019234](https://platzi.com/comentario/1019234/) 

	Existen 3 conceptos importantes entorno a las bases de datos: 1. El lenguaje, 2. El motor, 3. El servidor

* **Angel de Jesus Quintero Pereira** (1) [1019232](https://platzi.com/comentario/1019232/) 

	Postgres SQL es un motor, y PostgreSQL se considera un RDBMS significa Relational Database Management System o sistema manejador de bases de datos relacionales. Es un programa que se encarga de seguir las reglas de Codd y se puede utilizar de manera programática.

* **Claudio Sebastian Bolvaran Toro** (1) [1009813](https://platzi.com/comentario/1009813/) 

	Quería hacer una pregunta por si alguien sabe. En una pregunta de prueba solicitan dar permisos de SELECT sobre los registros de una tabla con ID 1 y 6… es eso posible en postgres? Dar permisos de SELECT pero a filas especificas… o simplemente la solicitud que hicieron es errónea.

	* **MauricioF** [1009813] (1)

		Buena pregunta, quisiera saber la respuesta también para un caso de uso práctico

* **Diego Gallardo** (1) [924544](https://platzi.com/comentario/924544/) 

	Cumple  
	A: Atomicidad  
	C: Consistencia  
	I: Aislamiento  
	D: Durabilidad

* **R3mb** (1) [911963](https://platzi.com/comentario/911963/) 

	¿Que tipo de herramientas para recuperación tiene PostgreSQL?, por ejemplo ORACLE tiene RMAN para la recuperación archivos de datos, control files, redo_log etc. que ayuda al administrador a recuperar la BD.

* **Bernardino Villagra Baez** (1) [870466](https://platzi.com/comentario/870466/) 

	Leguaje es el que te permite manipular la data, en este caso SQL  
	Motor es el que te permite estructurar tus datos en este caso PostreSQL  
	Servidor donde esta instalado el moto y nos permite acceder a ella y utilizarlo

* **Paul Sanchez Pardo** (1) [867577](https://platzi.com/comentario/867577/) 

	Esta interesante el curso era muy esperado!!

* **Brando Rodríguez** (1) [859553](https://platzi.com/comentario/859553/) 

	welcome!!

* **Bernardino Villagra Baez** (1) [858870](https://platzi.com/comentario/858870/) 

	Hace bastante tiempo he venido esperando este curso. No lo pude seguir desde su lanzamiento por cuestiones laborales, pero aquí estoy, presto para aprender y completar la carrera de Base de Datos.

## 0030. Instalación y configuración de la Base de Datos [24177](https://platzi.com/clases/1480-postgresql/24177-instalacion-y-configuracion-de-la-base-de-datos/)

### Descripción:


Vamos a instalar PostgreSQL en nuestra computadora. A continuación veremos el paso a paso y algunos consejos útiles para instalar y configurar correctamente PostgreSQL en nuestro equipo. En éste caso, usaremos Windows, pero los pasos son bastante similares entre los diferentes sistemas operativos.

Primer paso: ir a <https://www.postgresql.org/>.

Actualmente, la página web oficial de postgres luce así:

![1.png](https://static.platzi.com/media/user_upload/1-82324fcc-cd15-407b-ac6c-ddc47d8a243a.jpg)

Ten en cuenta que puedes ver esta página en diferentes idiomas, depende de la configuración predeterminada de idioma de tu navegador.

Hacer clic en el botón ‘Download’ (Descarga) que se encuentra en la parte inferior derecha. Veremos lo siguiente:

![2.png](https://static.platzi.com/media/user_upload/2-b1e35963-ed85-4e61-9c0e-9a43eaac00b6.jpg)

Veremos lo siguiente:  
Seleccionamos la opción que corresponda con tu sistema operativo, para éste caso hacemos clic en “Windows”:

Veremos en la parte inferior:

![3.png](https://static.platzi.com/media/user_upload/3-a99ee1d6-6468-465e-96fa-4f72a2308289.jpg)

Haz clic en el enlace “Download the installer”. Esto nos va a llevar a la Web de Enterprise DB o EDB. EDB es una empresa que ofrece servicios sobre el motor de base de datos PostgreSQL y ofrece un instalador para Postgres de manera gratuita.

![4.png](https://static.platzi.com/media/user_upload/4-ca32d0f5-6047-4f85-bd8a-72bd28642684.jpg)

Es altamente recomendable seleccionar la penúltima o antepenúltima versión. Si bien la última versión estable está disponible, en éste caso la 12.0, no es recomendable instalarla en nuestro equipo, ya que al momento de instalarla o usar un servicio en la Nube para Postgres, lo más seguro es que no esté disponible y sólo esté hasta la versión 11.5, que no es la última versión. Esto porque todos los proveedores de Infraestructura no disponen de la versión de Postgres más actual siempre (tardan un poco en apropiar los nuevos lanzamientos).

Si tienes un equipo con Linux, la instalación la puedes hacer directamente desde los repositorios de Linux, EDB ya no ofrece soporte para instaladores en Linux debido a que se ha vuelto innecesario, el repositorio de Linux con PostgreSQL ofrece una manera mucho más sencilla y estándar para instalar PostgreSQL en linux.

Segundo paso: descargamos la versión “Windows x86-64” (porque nuestro sistema operativo es de 64 bits). En caso de que tu equipo sea de 32 bits debes seleccionar la opción “Windows x86-32”.

Vamos a descargar la versión 11.5. Hacemos clic en Download y guardamos el archivo que tendrá un nombre similar a:  
“postgresql-11.5-2-windows-x64.exe”

Ahora vamos a la carpeta donde descargamos el archivo .exe, debe ser de aproximadamente 190 MB, lo ejecutamos.

Veremos lo siguiente:

![5.png](https://static.platzi.com/media/user_upload/5-600d1a76-de39-4796-b7bd-00fd0fa4d3a3.jpg)

Hacemos clic en siguiente. Si deseas cambiar la carpeta de destino, ahora es el momento:

![6.png](https://static.platzi.com/media/user_upload/6-c3545ad4-a4c4-47a1-8272-bfa8468d054e.jpg)

Seleccionamos los servicios que queremos instalar. En este caso dejamos seleccionados todos menos “Stack Builder”, pues ofrece la instalación de servicios adicionales que no necesitamos hasta ahora. Luego hacemos clic en siguiente:

![7.png](https://static.platzi.com/media/user_upload/7-5687b5e0-d34e-49bc-9163-8e58ff2162e3.jpg)

Ahora indicamos la carpeta donde iran guardados los datos de la base de datos, es diferente a la ruta de instalación del Motor de PostgreSQL, pero normalmente será una carpeta de nuestra carpeta de instalación. Puedes cambiar la ruta si quieres tener los datos en otra carpeta. Hacemos clic en siguiente.

![8.png](https://static.platzi.com/media/user_upload/8-f634519b-aea8-43a3-84de-0a23e95cc8e3.jpg)

Ingresamos la contraseña del usuario administrador. De manera predeterminada, Postgres crea un usuario super administrador llamado `postgres` que tiene todos los permisos y acceso a toda la base de datos, tanto para consultarla como para modificarla. En éste paso indicamos la clave de ese usuario super administrador.

Debes ingresar una clave muy segura y guardarla porque la vas a necesitar después. Luego hacemos clic en siguiente.

![9.png](https://static.platzi.com/media/user_upload/9-11aa6e1a-572b-4f1c-a037-ca83472b7fe1.jpg)

Ahora si queremos cambiar el puerto por donde el servicio de Postgresql estará escuchando peticiones, podemos hacerlo en la siguiente pantalla, si queremos dejar el predeterminado simplemente hacemos clic en siguiente.

![10.png](https://static.platzi.com/media/user_upload/10-a2b1eceb-7c3c-43c6-887d-2d3e9e5c66da.jpg)

La configuración regional puede ser la predeterminada, no es necesario cambiarla, incluso si vamos a usarla en español, ya que las tildes y las eñes estarán soportadas si dejas la configuración regional predeterminada. Es útil cambiarla cuando quieras dejar de soportar otras funciones de idiomas y lenguajes diferentes a uno específico. Luego hacemos clic en siguiente:

![11.png](https://static.platzi.com/media/user_upload/11-eee9d065-17f4-4c83-978a-712f27cbbe81.jpg)

En pantalla aparecerá el resumen de lo que se va a instalar:

![12.png](https://static.platzi.com/media/user_upload/12-0d51a90f-495e-455d-9fc3-075ef91ba19a.jpg)

Al hacer clic en siguiente se muestra una pantalla que indica que PostgreSQL está listo para instalar, al hacer clic de nuevo en siguiente iniciará la instalación, espera un par de minutos hasta que la aplicación termine.

Una vez terminada la instalación, aparecerá en pantalla un mensaje mostrando que PostgreSQL ha sido instalado correctamente.

![13.png](https://static.platzi.com/media/user_upload/13-98b744e3-de8a-4cf4-975c-6df50ca8b109.jpg)

Podemos cerrar ésta pantalla y proceder a comprobar que todo quedó instalado correctamente.

Vamos a buscar el programa PgAdmin, el cual usaremos como editor favorito para ejecutar en él todas las operaciones sobre nuestra base de datos.

También vamos a buscar la consola… Tanto la consola como PgAdmin son útiles para gestionar nuestra base de datos, una nos permite ingresar comando por comandos y la otra nos ofrece una interfaz visual fácil de entender para realizar todas las operaciones.

En el menú de Windows (o donde aparecen instalados todos los programas) buscamos “PgAdmin…”

![14.png](https://static.platzi.com/media/user_upload/14-f1f1223a-7735-400a-9a94-be4031dbef74.jpg)

Ahora buscamos “SQL Shell…”

![15.png](https://static.platzi.com/media/user_upload/15-faad2c1d-8252-4af6-9f41-465a3952fcc8.jpg)

Efectivamente, ahora aparecen las herramientas que vamos a utilizar en éste curso.  
Ahora vamos a crear una base de datos de prueba usando la consola y comprobaremos si existe usando PgAdmin, la crearemos para validar que la conexión con el servicio de base de datos interno funciona correctamente.

Para ello abrimos la consola, buscamos SQL Shell y lo ejecutamos. Veremos algo así:

![16.png](https://static.platzi.com/media/user_upload/16-2b8a8090-9e18-4e4d-a9a2-c41732bae301.jpg)

Lo que vemos en pantalla es la consola esperando que ingresemos cada parámetro para la conexión.

Primero está el nombre del parámetro. En éste caso es “Server” seguido de unos corchetes que contienen el valor predeterminado. Si presionamos “Enter” sin digitar nada la consola asumirá que te refieres al valor predeterminado, si en éste caso presionamos “Enter” el valor asumido será “Localhost”. Localhost se refiere a nuestra propia máquina, si instalaste la base de datos en el mismo pc que estás usando para la consola, el valor correcto es Localhost o 127.0.0.1 (representan lo mismo).

Podemos dejar todos los valores predeterminados (presionando “Enter”) hasta que la consola pregunte por la clave del usuario maestro:

![17.png](https://static.platzi.com/media/user_upload/17-f0b53470-a533-4c2b-b5b3-501fc68e93f6.jpg)

Debemos ingresar la clave que usamos cuando estábamos instalando Postgres, de lo contrario no podremos acceder. Presionamos Enter y veremos a continuación una pantalla que nos indica que estamos logueados en la base de datos y estamos listos para hacer modificaciones.

De manera predeterminada, la base de datos instalada es Postgres, la cual no debemos tocar, ya que ejecuta funciones propias del motor. Es usada por el Motor de PostgreSQL para interactuar con todas las bases de datos que vayamos a crear en el futuro.

La siguiente imagen indica que estamos conectados a la base de datos Postgres. Vamos a crear una base de datos nueva y luego saltar el cursor a ésta base de datos recién creada.

![18.png](https://static.platzi.com/media/user_upload/18-ac8f31b5-f307-4e43-b935-cb8b97b8b7c5.jpg)

Para ello escribimos el comando “CREATE DATABASE transporte_publico;” y presionamos “Enter”. Veremos:

![19.png](https://static.platzi.com/media/user_upload/19-267d7da8-f68e-45ea-9fab-150aa62fefc5.jpg)

El mensaje “CREATE DATABASE” justo después de la línea que acabamos de escribir indica que la base de datos fue creada correctamente.

Para saltar a la base de datos recién creada ejecutamos el comando “\c transporte_publico”, el cursor mostrará lo siguiente:

![20.png](https://static.platzi.com/media/user_upload/20-f904c2a7-3eff-4ac9-8801-a75a9a5bb9fb.jpg)

Ahora vamos a validar desde PgAdmin que la base de datos fué creada correctamente. Abrimos PgAdmin y nos encontramos con una lista de items a la izquierda, lo que significa que de manera predeterminada PgAdmin ha creado un acceso a nuestra base de datos local, el cual llamó “PostgreSQL 11”:

![21.png](https://static.platzi.com/media/user_upload/21-028b8530-63f5-4bc4-b1d6-0bdac6885cfe.jpg)

Al hacer hacer doble clic sobre éste elemento (“PostgreSQL 11”) nos pedirá ingresar la clave que hemos determinado para el super usuario postgres, al igual que la consola, hasta no ingresarla correctamente no nos podremos conectar:

![22.png](https://static.platzi.com/media/user_upload/22-0e0171ab-3ae9-4798-9188-7b14181cb83b.jpg)

Ingresamos la clave. Te recomiendo seleccionar la opción “Save Password” o “Guardar Contraseña”. Si la máquina sobre la que estás trabajando es de confianza, que seas sólo tú o tu equipo quien tenga acceso a ella, de lo contrario, no guardes la contraseña para mantenerla segura.  
Veremos la lista de bases de datos disponibles, la predeterminada “postgres” y la que acabamos de crear usando la consola, lo que comprueba que la base de datos y la consola funcionan correctamente.

![23.png](https://static.platzi.com/media/user_upload/23-ff23bf88-a5f8-4449-8d89-78492b9cb834.jpg)

Ahora procedemos a eliminar la base de datos recién creada para comprobar que PgAdmin está correctamente configurada y si pueda realizar cambios sobre la base de datos.

Para ello hacemos clic derecho sobre el elemento “transporte_publico” y seleccionamos la opción “Delete/Drop”. Al mensaje de confirmar hacemos clic en OK.

Con ello, si el elemento “transporte_publico” desaparece del menú de la izquierda comprobamos que PgAdmin funcionan correctamente.

### Comentarios:

* **Luis Rodrigo Alvarez Herrera** (5) [834806](https://platzi.com/comentario/834806/) 

	Ojo, si en la consola aun estas en la ruta de la base de datos, te arrojara error ya que esta siendo usada

	* **Andres Rivera** [834806] (3)

		Exacto hay que salir del sql shell con control + c para los que somos muy nuevos

	* **tizianaamica** [834806] (2)

		Gracias por sus comentarios!

	* **Eduard José Carrillo Ortega** [834806] (2)

		Me sale este error al intentar instalar en windows. 😕
		
		![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-92072d43-259d-4c1e-84e5-920bbe85bfe7.jpg)

	* **Luis Rodrigo Alvarez Herrera** [834806] (1)

		Que version de windows? ya intentaste bajar de nuevo el instalador?

* **Javier Rodolfo** (4) [1041676](https://platzi.com/comentario/1041676/) 

	Despues de varios intentos frustantes lo instale en ubuntu 18 LTS en windows  
	este enlace me ayudo mucho’ <https://www.youtube.com/watch?v=ENrtKDNizv8>

	* **ferdanymr** [1041676] (1)

		muchas gracias por el aporte bro!

	* **Jose Luis Colmenares** [1041676] (1)

		Gracias! Esto era justo lo que yo quería hacer!

* **Mario Uriarte Amaya** (4) [894741](https://platzi.com/comentario/894741/) 

	Les dejo una guia para instalar Postgresql usando Docker.
	
	<https://www.mariouriarte.com/2020/01/instalar-postgres-en-docker/>

* **erickfve** (3) [919580](https://platzi.com/comentario/919580/) 

	Me salió un error que indicaba que no podía borrar la base de datos porque estaba siendo usada desde otra sesión, la cuál me imagino que es de sql shell, así que me moví a la base de datos por defecto (postgres)
	``` 
	    \c postgres
	    
	```
	
	Luego pude eliminar exitosamente la base de datos desde pgAdmin despues de actualizar la página.

* **edwintrumpet** (3) [918562](https://platzi.com/comentario/918562/) 

	Para los usuarios **Ubuntu** hice este tutorial de la instalación de Postgres y de la interfaz visual pgAdmin.  
	Cualquier cosa que agregar me comentan 😬  
	<https://platzi.com/tutoriales/1480-postgresql/4775-instalacion-de-postgresql-en-ubuntu-1804/>

	* **Cristopher Gonzalez** [918562] (1)

		Hola, consulta sabes la contraseña por defecto del usuario postgres? instale y no puse la contraseña, y cuando me trato de conectar por dbeaver o pgadmin no me reconoce la cuenta con la contraseña vacia

	* **edwintrumpet** [918562] (1)

		Depende de la instalación a veces es “postgres”, a veces viene vacío pero igual no le reconoce la contraseña vacía por lo que toca cambiarla o toca cambiar los archivos de configuración de postgres para que acepte la conexión de pgAdmin con la contraseña vacía.  
		Lo más sencillo es que cambie la contraseña y en las siguientes clases verá como se cambia ese requerimiento en los archivos de configuración.

	* **jairhop** [918562] (1)

		Si están trabajando con Windows Subsystem for Linux (WSL), instalen XMING en Windows y en Linux:
		``` 
		    jair@TOSHIBA:~$ sudo apt-get update
		    jair@TOSHIBA:~$ sudo apt-get install x11-apps
		    jair@TOSHIBA:~$ export DISPLAY=:0
		    jair@TOSHIBA:~$ xeyes
		    
		```

* **Angel Hernandez** (3) [861586](https://platzi.com/comentario/861586/) 

	Para la instalacion en LINUX, especificamente Ubuntu es recomendado crear una maquina virtual Ubuntu Server y seguir la documentacion oficial [Ubuntu PostgreSQL](https://www.postgresql.org/download/linux/ubuntu/)

* **JOSE PEREZ** (3) [836940](https://platzi.com/comentario/836940/) 

	¿Pueden hacer demos de instalaciones no tan básicas para linux? por ejemplo instalar por consola pero no en la ubicación por defecto si no en otra en especifico, configurar el idioma, configurar logs.
	
	Gracias

* **TUDz** (3) [836044](https://platzi.com/comentario/836044/) 

	La instalación en MacOS sin ningún problema siguiendo las mismas instrucciones pero con diferente instalador.

* **juanma_9206** (2) [1103894](https://platzi.com/comentario/1103894/) 

	El paso a paso estuvo más que estupendo! Así se hace un paso a paso.

* **ejgachancipa** (2) [1101680](https://platzi.com/comentario/1101680/) 

	[Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04)

	* **Jesus Alejandro Lechuga Ortega** [1101680] (1)

		¡Gracias!,era lo que estaba buscando

* **Decgar** (2) [1008251](https://platzi.com/comentario/1008251/) 

	Si les salta un error que dice que la base de datos está siendo usada por otro usuario al querer borrar la base de datos, deben cerrar la ventana de comandos SQL Shell.

	* **mauricio-vazqui** [1008251] (1)

		Gracias por tu aporte!!

* **Maxc_Martinez** (2) [963061](https://platzi.com/comentario/963061/) 

	bueno, si me funciono

* **Israel Yance** (2) [938251](https://platzi.com/comentario/938251/) 

	Ningún problema en Mac.

* **Jorge Raúl Piscoya Calderón** (2) [900509](https://platzi.com/comentario/900509/) 

	Buenas noches;  
	Para que los que deseen instalar postgresql en debian10. Funciona a la perfección. Deben configurar el password conforme indica el tutorial, sino no podrán usar pgadmin  
	<https://www.howtoforge.com/tutorial/ubuntu-postgresql-installation/>

* **cob1979** (2) [839621](https://platzi.com/comentario/839621/) 

	Para el que no se acuerde de la contraseña que puso en la instalación de Postgresql (me pasó a mí 😉 aquí les dejo un vídeo que me ayudó a restablecerla <https://www.youtube.com/watch?v=FTiG3VZLK0E>

* **dbzdavidbaez** (2) [835803](https://platzi.com/comentario/835803/) 

	Listo instalado PostgreSQL en WLS con windows 10.  
	Para borrar la base hay que salirse de ella o nos generar error.

* **Mon Avellaneda** (2) [835494](https://platzi.com/comentario/835494/) 

	Todo perfecto hasta ahora, teniendo en cuenta lo que dice Luis Rodrigo Alvarez sobre la consola.
	
	Seguimos.
	
	Mil gracias
	
	Mon

* **hydroxseguridad** (2) [835385](https://platzi.com/comentario/835385/) 

	Todos los pasos de instalacion fueron muy correctas! excelente! me fue muy bien con la instalacion.

* **Pablo nicolas Valenzuela caceres** (1) [1118289](https://platzi.com/comentario/1118289/) 

	Funcionando todo OK

* **Carlos Naveda** (1) [1116171](https://platzi.com/comentario/1116171/) 

	Para los que quieran utilizar su terminal preferido, sin iniciar el SQL Shell.  
	Abren su terminal, y realizan lo siguiente:  
	![Captura de Pantalla 2020-04-09 a la\(s\) 18.57.35.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202020-04-09%20a%20la%28s%29%2018.57.35-a3fffdb1-9e5b-49bc-bb49-c294942461cf.jpg)

* **KevinJZea** (1) [1113274](https://platzi.com/comentario/1113274/) 

	Hola. Yo tuve un problema y no encontré la respuesta en los comentarios, así que compartiré cómo lo solucioné, en caso de que a alguien más le pudiese servir:  
	Tengo Windows 10 y, al igual que a mi compañero @waamayapa, me salió un aviso que decía “The application server could not be contacted”. Lo que yo hice fue ingresar a C:\Users%USERNAME%\AppData\Roaming\pgAdmin en mi explorador de archivos (les recomiendo copiar esa dirección y pegarla en el explorador). Después, borré todo lo que venía dentro de esa carpeta y volví a ejecutar el PgAdmin.  
	Una vez hecho lo anterior, me funcionó perfectamente.  
	Si no lo expliqué bien, en este vídeo viene el procedimiento: <https://www.youtube.com/watch?v=LINNoLufvOo>  
	Un saludo y ¡nunca paren de aprender!

	* **KevinJZea** [1113274] (1)

		El enlace tiene un error. Cuando lo subí de nuevo correctamente, vuelve a causar el mismo error: Debe tener un ‘’ entre ‘Users’ y ‘%USERNAME%’.  
		Saludos.

* **JaviRome94** (1) [1113046](https://platzi.com/comentario/1113046/) 

	excelente explicación si me funciono la instalación gracias.

* **Daniel Cardona Velasquez** (1) [1106868](https://platzi.com/comentario/1106868/) 

	Super bien explicado

* **oscarn2** (1) [1105240](https://platzi.com/comentario/1105240/) 

	No consigo instalar postgresql.
	
	Cuando ejecuto el instalador no me aparece la ventana de Setup.
	
	¿A alguno le ha pasado?

	* **Sergio Ivan Galvis Motoa** [1105240] (2)

		Cuéntanos un poco más de tus errores y del sistema operativo en el que intentas instalar!
		
		De pronto necesitas permisos de admin.

* **DonTapas** (1) [1101578](https://platzi.com/comentario/1101578/) 

	Excelente paso a paso!!! Vamos al lio 😃

* **Daniel Mauricio Sanchez Acebedo** (1) [1032347](https://platzi.com/comentario/1032347/) 

	Muy buen paso a paso para la instalación.

* **cconde** (1) [1029079](https://platzi.com/comentario/1029079/) 

	Excelente paso a paso… Todo funcionando

* **Angel de Jesus Quintero Pereira** (1) [1020241](https://platzi.com/comentario/1020241/) 

	¿Qué significa los errores que marcan en la parte inferior?  
	![Captura de pantalla \(82\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2882%29-06766f93-ffdc-4a2f-98e1-f664b28a4421.jpg)

	* **juanma_9206** [1020241] (2)

		Hola Angel, en realidad la “x” no significa error, lo que indica es la opción de terminar ese proceso, es como la “X” para cerrar una ventana del computador o una pestaña del navegador. Si te fijas al lado está otro símbolo cuadrado de color negro, lo que indica es la opción de cancelar la consulta que se ha hecho.
		
		Además te contextualizo el nombre de algunas de las columnas por si fuera de tu interés:
		
		**PID:** ID del proceso asociado.  
		**Database** : Muestra el nombre de la base de datos.  
		**User:** El nombre del usuario propietario del objeto.  
		**Backend start** : El tiempo de inicio del proceso de Backend
		
		Nota: Dejo la fuente de consulta: <https://www.pgadmin.org/docs/pgadmin4/3.6/pgadmin_tabbed_browser.html>

* **Claudio Sebastian Bolvaran Toro** (1) [1009828](https://platzi.com/comentario/1009828/) 

	Hola Buenas tardes,  
	Hay algún comando para deslogearse de transporte_publico? o como opción volver a la base por defecto postgres…

	* **JoelNieto** [1009828] (1)

		Hola, hasta donde tengo conocimiento dentro de la interfaz es posible moverse entre las diferentes Bases de Datos que tenemos sin la necesidad de cerrar sesión en alguna BD en particular.

* **william albeiro amaya patiño** (1) [1006580](https://platzi.com/comentario/1006580/) 

	me sale este error the application server could not be contacted

* **Raul Hernandez** (1) [988771](https://platzi.com/comentario/988771/) 

	Para los usuarios de macOS al momento del paso de borrar la base no debemos tener abierta la terminal con la base de datos transporte_publico ya que muestra una alerta de uso en otra instancia.

* **Carlos Arturo Gutierrez Gonzalez** (1) [954824](https://platzi.com/comentario/954824/) 

	Excelente explicación aun siendo solo de lectura!

* **Pacool84** (1) [951438](https://platzi.com/comentario/951438/) 

	Es el primer curso en donde explican la instalacion de la herramienta solo en un sistema operativo, creo conveniente que coloquen la documentación como en el curso de Fundamentos de Base de Datos.

* **cristhiandelacruzperu** (1) [936698](https://platzi.com/comentario/936698/) 

	Hola a todos, tengo un problema con la instalación, quizás tambien les mostro un mensaje de error: “la inicialización del clúster de la base de datos falló…”, además, al abrir el sql shell, al dar enter despues del usuario (para ingresar la contrseña) me muestra: “psql: no se pudo conectar con el servidor: Connection refused (0x0000274D/10061)  
	¿Está el servidor en ejecución en el servidor «localhost» (::1) y aceptando  
	conexiones TCP/IP en el puerto 5432?..”, su apoyo por favor.

* **Jaime Andrés Martínez Rodríguez** (1) [930768](https://platzi.com/comentario/930768/) 

	Todo perfecto!

* **william albeiro amaya patiño** (1) [928726](https://platzi.com/comentario/928726/) 

	que puedo hacer para solucionar este error: the application server could not be contacted

* **Abril Darynka Tapia Sosa** (1) [928079](https://platzi.com/comentario/928079/) 

	Todo OK 👌

* **Diego Gallardo** (1) [924651](https://platzi.com/comentario/924651/) 

	Me salió error pero como ya vi lineas abajo se tuvo que cerrar el Shell para poder darle drop en el PgAdmin.  
	Resultado exitoso.

* **Marco Soudre Oliva** (1) [914505](https://platzi.com/comentario/914505/) 

	Con las instrucciones he podido instalar y comprobar que PostgreSQL y pgAdmin está corriendo bien. Gracias.

* **MaxLandh** (1) [911018](https://platzi.com/comentario/911018/) 

	Excelente

* **Luis Fernando Salas Gave** (1) [902596](https://platzi.com/comentario/902596/) 

	Muy buena explicación. Gracias

* **Jorge Leonardo Cárdenas Montenegro** (1) [894821](https://platzi.com/comentario/894821/) 

	Hola, he instaldo POSTGRESQL 12 en centos 7 según lo indica el manual <https://www.postgresql.org/download/linux/redhat/> .La BD como se observa en la siguiente imagen ya se encuentra funcionando correctamente: ![posgrestsql1.png](https://static.platzi.com/media/user_upload/posgrestsql1-5bb94b38-0080-4a07-b298-3fa2467d26a4.jpg). He ingresado y ejecutado algunas consultas al interior de ella. Asi mismo, se abrio el puerto 5432 del firewall del SO para que sea escuchado por fuera. Sin embargo, al tratar de conectar cualquier cliente, ya sea pgadmin o dbeaver no me deja conectar. Al realizar pruebas de red pude evidenciar que el puerto no esta escuchando el maquina según se puede observa a continuación: ![posgrestsql2.png](https://static.platzi.com/media/user_upload/posgrestsql2-d4601ecb-a0c6-43c6-9f53-e3934d6e1420.jpg) Alguna idea para este caso?

* **Eduard José Carrillo Ortega** (1) [839818](https://platzi.com/comentario/839818/) 

	¡Ayuda! me sale este error 😕
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-adf75d82-df3f-4500-a6a4-b0d787a76e0e.jpg)

	* **Marco Antonio González Arellano** [839818] (2)

		Qué sistema operativo tienes? Si es Windows, intentaste ejecutando el instalador como administrador? clic derecho sobre el instalador / Ejecutar como administrador…
		
		Saludos,

* **Favio Sauto** (1) [835844](https://platzi.com/comentario/835844/) 

	Buenas noches comunidad, seguí todos los pasos aquí y al terminar de instalar me apareció este error:
	``` 
	    Problem running post-install step. Installation may notcomplete correctly The database cluster initialsation failed.
	    
	```
	
	Cerré la instalación como dice esta clase y de todas formas me aparecen PgAdmin y SQLshell, al iniciar el SQL shell y luego de darle enter a la opción de Username[postgres] me aparece otro error:
	``` 
	    could not determine encoding for locale "English_United States.utf8": codeset is"CPutf8"
	    psql: could not connect to server: Connection refused (0x0000274D/10061)
	            Is the server runningon host "localhost" (::1) and accepting
	            TCP/IP connections on port 5432?
	    could not connect to server: Connection refused (0x0000274D/10061)
	            Is the server runningon host "localhost" (127.0.0.1) and accepting
	            TCP/IP connections on port 5432?
	    Press any key tocontinue . . .
	    
	```
	
	Le doy enter y el SQL shell se cierra automáticamente sin dejarme opción a nada.
	
	Logré instalar Postgres en mi subsistema linux pero quisiera saber el por qué por no puedo instalarlo en Windows.

	* **Oz** [835844] (3)

		Hola Favio, el problema puede estar relacionado con los usuarios del sistema operativo o con la configuración regional, para determinar cuál es el problema, en el Panel de Control ve a Región, seleciona “Cambiar fecha, hora o formato” y selecciona la pestaña “Administración/Administrative” Verifica que al hacer clic en “Change system locale… o Cambiar localización del sistema…” este DESmarcada la opción “Beta: Usar Unicode UTF-8 para soporte global”

	* **Favio Sauto** [835844] (2)

		Se solucionó el error haciendo lo que me dijiste. ¡Muchas Gracias Oswaldo!

## 0040. Interacción con Postgres desde la Consola [24178](https://platzi.com/clases/1480-postgresql/24178-interaccion-con-postgres-desde-la-consola/)

### Descripción:


### Comentarios:

* **david-hv** (9) [854398](https://platzi.com/comentario/854398/) 

	****** Comandos básicos de PostgreSQL******
	
	* \l = para listar todas las bases de datos existentes
	* \dt = para listar todas las tablas que existen en una base de datos
	* \c = para cambiar a otra base de datos
	* \d = para describir la base de datos o la tabla
	* \h = para ver todas las funciones que podemos ejecutar en PostgreSQL
	* SELECT versión(); = para ver la versión de PostgreSQL
	* \g = volver a ejecutar la función que justamente acabaste de ejecutar en la consola
	* \timing = inicializar el contador de tiempo para que la consola muestre en cada ejecución cuanto se demoro en ejecutar ese comando
	
	

* **Luis Rodrigo Alvarez Herrera** (8) [834930](https://platzi.com/comentario/834930/) 

	Mi resumen:
	``` 
	    \l: Lista todas las bases de datos
	    \dt: Listas las tablas dela actual base de datos
	    \c: Cambia de base de datos
	    	\c nombreBD
	    \d: Describela tabla actual
	    \h: Ayuda
	    \h comando: Ejemplo de uso y para que sirve un tipo mande linux
	    \g: Ejecuta el ultimo comando
	    \timing: Activa o desactiva el tiempo que le toma una consulta completarse
	    
	```

* **Abril Darynka Tapia Sosa** (7) [928123](https://platzi.com/comentario/928123/) 

	Comandos en porgresql (consola)  
	• Create database nombre_bd  
	• \c nombre_bd (Es como si fuera el use DB)  
	• \l -> Muestra todas las bases de datos (ele minúscula)  
	• \dt -> muestra las tablas  
	• \d -> muestra los detalles de la tabla  
	• \h -> ayuda para comandos de SQL  
	• \h palabra_sql ->Muestra cómo usar la función  
	• Ctrl + c -> cancela lo que se estaba mostrando  
	• \g -> permite volver a ejecutar la función que acabas de ejecutar en la consola  
	• \timing -> permite activar el contador de tiempo para así saber cuánto se demora una respuesta

* **juanma_9206** (6) [1104149](https://platzi.com/comentario/1104149/) 

	Resumen:  
	Comandos importantes:   
	Si quiero ver el listado de todos los comandos con \ escribo en consola de postgres: ?
	
	  1. Listar todas las bases de datos: \l
	  2. Ver las tablas de una base de datos: \dt
	  3. Cambiar a otra base de datos: \c nombre_DB
	  4. describir una tabla: \d nombre_tabla
	  5. Ver comandos SQL: \h
	  6. Ver como se ejecuta un comando SQL: \h nombre_de_la_función
	  7. Control + c: Cancela todo lo que hay en pantalla.
	  8. Consultar versión de postgres instalada: SELECT version();
	  9. Volver a ejecutar la función que acabaste de ejecutar en la consola: \g
	  10. Inicializar el contador de tiempo para que la consola diga cuanto se demoro en ejecutar ese comando : \timing
	  11. Control + L: Limpiar pantalla.
	
	

	* **hugoorlandogonzalez** [1104149] (1)

		Gracias

	* **jgarcia990** [1104149] (1)

		  1. \t Mostrar solo filas. (No muestra los nombres de las columnas)
		
		

	* **jgarcia990** [1104149] (1)

		  1. \t Mostrar solo filas. (No muestra los nombres de las columnas)
		
		

* **Jaime Andrés Martínez Rodríguez** (6) [930781](https://platzi.com/comentario/930781/) 

	Mi resumen
	
	* \l mostrar las bases de datos
	* \dt tablas que contiene la base de datos
	* \c para cambiar de base de datos
	* \d “tabla” describe la estructura de la tabla
	* \h todos los comandos de SQL
	
	

	* **asanchez2091** [930781] (1)

		Estos son los más básicos existen muchos más.

* **PaoloTorregrosa** (4) [939471](https://platzi.com/comentario/939471/) 

	Con ctrl + L pueden limpiar la pantalla

* **TUDz** (4) [836054](https://platzi.com/comentario/836054/) 

	Excelente, me parece muy interesante que Postgres tenga comandos propios tipo Unix Shell para realizar acciones.
	
	En Oracle (por ejemplo), para describir una tabla es con la sentencia:
	
	DESC nombre_tabla;
	
	y para listar todas las bases de datos (en un entorno contenedor) es;
	
	SELECT NAME, OPEN_MODE FROM V$PDBS;
	
	Me parece que la gestión de BD así como de objetos es mucho más sencilla (pero a la vez super poderosa) en POSTGRES.

* **kikega** (3) [1046302](https://platzi.com/comentario/1046302/) 

	Instalación de PostgreSQL en Linux
	``` 
	    	# Debian
	    	sudo apt-get update && apt-get upgrade
	    	
	    	# Instalar motor de bases de datos
	    	sudo apt-get install postgresql postgresql-client postgresql-contrib libpq-dev
	    	
	    	# Acceso de usuario, desde la cuenta de root
	    	su -
	    	su - postgres
	    
	    	# Crear usuario y base de datos
	    	createuser --interactive
	    		role? -> usuario
	    		superuser?
	    		
	    	psql
	    		# \password usuario
	    		# \q
	    		
	        createdb nom_bbdd
	    	
	        # Fedora
	        dnf install postgresql-server postgresql-contrib
	        
	        postgresql-setup initdb
	        
	        systemctl enable postgresql.service
	        systemctl start postgresql.service
	        
	        # Crear un usuario administrador
	        createuser -s -P -e nom_usuario
	    
	```

* **Angel de Jesus Quintero Pereira** (2) [1022306](https://platzi.com/comentario/1022306/) 

	\timing; Con esta función podemos visualizar el tiempo que demora el motor de la base de dato en ejecutar una consulta y con este dato se puede optimizar las consultas.

* **Deiby Johany Avila Gutierrez** (2) [838959](https://platzi.com/comentario/838959/) 

	? Listar comandos.

* **dbzdavidbaez** (2) [835818](https://platzi.com/comentario/835818/) 

	Entendido, comandos basicos pero que se utilizan a diario.

* **JaviRome94** (2) [87256](https://platzi.com/comentario/1116073/) 
alguien sabe con que comando se puede limpiar la consola de SQL SHELL ?

	* **Carlos Naveda** [87256] (2)

		con el comando:
		``` 
		    clear
		    
		```

* **JaviRome94** (1) [1116481](https://platzi.com/comentario/1116481/) 

	**APORTE** :  
	te aparece este error en la consola de SQL SHELL de PostgreSQL y de CMD cuando ingresas un comando cualquiera
	
	**‘more’ no se reconoce como un comando interno o externo, programa o archivo por lotes ejecutable.**
	
	**Respuesta** :
	
	Esto indica que psql internamente intenta ejecutar el comando **more** de windows pero no lo localiza.
	
	Para solucionarlo agregue el directorio donde se localiza el comando more a la variable de entorno PATH del sistema.
	
	Por lo general el comando externo more se encuentra en el directorio **c:\Windows\System32**.
	
	**y hacen los siguientes pasos** , se dirigen a mi equipo luego click derecho en propiedades y en configuración avanzada del sistema
	
	se dirigen a opciones avanzadas y click en variables de entorno, le aparecerá la opción Path lo seleccionan y click en editar
	
	luego en nuevo y agregan la ubicación del directorio **more** osea este **C:\Windows\System32** , después aceptar a todo y listo cierran
	
	y vuelven a abrir CMD y SQL SHELL de PostgreSQL y resuelto el problema espero haberte ayudado.

* **Angel de Jesus Quintero Pereira** (1) [1022299](https://platzi.com/comentario/1022299/) 

	\g; Con esta instrucción se puede saber la versión con la cual se está trabajando en PostgreSQL y parte también se puede visualizar que consultas se están realizando desde otra consola y usuarios.

	* **Carlos Naveda** [1022299] (1)

		Me parece que no, \g sirve para volver a repetir la última instrucción que realizaste.  
		En el ejemplo coincidió que fue la versión, pero no es que sirva para ello.

* **Angel de Jesus Quintero Pereira** (1) [1022293](https://platzi.com/comentario/1022293/) 

	SELECT version(); Con esta instrucción se puede saber la versión con la cual se está trabajando en PostgreSQL.

* **Angel de Jesus Quintero Pereira** (1) [1022288](https://platzi.com/comentario/1022288/) 

	\h; | \h name_comand_sql; Con esta instrucción se puede ver todos los comandos sql que se pueden escribir y utilizamos la misma instrucción acompañada de un comando sql se puede ver como se usa.

* **Angel de Jesus Quintero Pereira** (1) [1022284](https://platzi.com/comentario/1022284/) 

	\d Con esta instrucción describimos la estructura de una tabla.

* **Angel de Jesus Quintero Pereira** (1) [1022277](https://platzi.com/comentario/1022277/) 

	\dt table_name; Con esta instrucción esta instrucción se puede describir cuales tablas tienes una base de dato.

* **Angel de Jesus Quintero Pereira** (1) [1022275](https://platzi.com/comentario/1022275/) 

	\c name_data_bases; Con esta instrucción cambiamos de base de dato.

* **Angel de Jesus Quintero Pereira** (1) [1022273](https://platzi.com/comentario/1022273/) 

	La base de dato de postgres es privada y solo puede acceder el motor.

* **Angel de Jesus Quintero Pereira** (1) [1022272](https://platzi.com/comentario/1022272/) 

	La base de dato de postgres es privada y solo puede acceder el motor.

* **Angel de Jesus Quintero Pereira** (1) [1022262](https://platzi.com/comentario/1022262/) 

	Con \l Listamos todas las bases de datos que tenemos en nuestro motor, por defecto postgres vendrá con 3 bases de datos instaladas. La base de dato de postgres es privada y solo puede acceder el motor.

* **Angel de Jesus Quintero Pereira** (1) [1022258](https://platzi.com/comentario/1022258/) 

	Una de las instrucciones más importante que veremos será los comando con "\"sí deseamos ver más como usarlo y ver otras instrucciones podemos digitar "\?".

* **Angel de Jesus Quintero Pereira** (1) [1022234](https://platzi.com/comentario/1022234/) 

	Server [local hosts]: Indica el host de para la conexión. Database [postgres]: el nombre de la base datos. Port [5432]: el puerto donde Postgres está funcionando. Username [postgres]: cual usuarios deseamos conectarnos (roles). Contraseña es la contraseña del user

* **Angel de Jesus Quintero Pereira** (1) [1022229](https://platzi.com/comentario/1022229/) 

	Lo primero que va a pedir son las credenciales de acceso, se debe tomar en cuenta que los valores entre corchetes son los valores por defecto de conexión, sí tenemos algún otro servicio al cual queremos acceder debemos indicarlo de lo contrario.

* **Angel de Jesus Quintero Pereira** (1) [1022226](https://platzi.com/comentario/1022226/) 

	Existen dos formas de acceder al motor de bases de datos de PostgreSQL y es por: 1. Consola y 2. PgAdmin que es el entorno gráfico para acceder a la consola desde

* **paucuaram** (1) [1018147](https://platzi.com/comentario/1018147/) 

	 **\timing** -> permite inicializar un contador de tiempo para mostrar cuánto se tardó una consulta en ejecutarse.

* **Adrian Castillo Ramírez** (1) [913177](https://platzi.com/comentario/913177/) 

	Si aparece un error al tratar de eliminar la Database desde pgAdmin solo cierra la consola antes escribiendo Exit

* **Luan de Souza** (1) [844879](https://platzi.com/comentario/844879/) 

	No termine siquiera el primer video y me estoy dando cuenta que me voy a volver fan de Postgres, parece mucho más amigable que mysql.

* **JaviRome94** (1) [87252](https://platzi.com/comentario/1116000/) 
hola comunidad ya instale y des instale varias veces el postgres para ver si soluciona los errores de la consola y vean la imagen sigue i...

	* **Carlos Naveda** [87252] (1)

		Tienes que cambiar la configuración de codificación de tu consola para que uses el UTF-8 encoding  
		Referencia: [Link](https://stackoverflow.com/questions/19162055/psql-shell-uses-code-page-850-windows-uses-1252-how-to-solve-change-console-co)  
		![Captura de Pantalla 2020-04-09 a la\(s\) 19.34.03.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202020-04-09%20a%20la%28s%29%2019.34.03-bf30a8dd-f9f7-47b5-9eb8-b64f8b01fc85.jpg)

* **JaviRome94** (1) [87119](https://platzi.com/comentario/1113225/) 
compañeros de platzi por favor ayuda no se porque en la consola de SQL SHELL no me funciona ningún comando cuando escribo eslach y la let...

	* **Miguel Torres** [87119] (1)

		¿Cuál estás utilizando? 😃
		
		/ (slash) o \ (backslash) ???
		
		El correcto es backslash ( \ ). Acá más info de todos los comandos: <https://platzi.com/clases/1480-postgresql/24849-comandos-mas-utilizados-en-postgresql/>

* **emercadogarcia** (1) [81807](https://platzi.com/comentario/990182/) 
Que cliente puedo usar para acceder a postgres? Postgres lo tengo en un servidor.

	* **Juan David Castro (Platzi)** [81807] (3)

		Puedes usar PgAdmin, la herramienta que estudiamos en la siguiente clase: <https://platzi.com/clases/1480-postgresql/24179-pgadmin-interaccion-con-postgres-desde-la-interfaz/>. 😉

* **emercadogarcia** (1) [81806](https://platzi.com/comentario/990181/) 
Que cliente puedo usar para acceder a postgres? Postgres lo tengo en un servidor

	* **Juan David Castro (Platzi)** [81806] (1)

		Hiciste la pregunta dos veces. Te respondí aquí: <https://platzi.com/comentario/990182/>. 😉

* **SOFTDYNAMIC** (1) [80953](https://platzi.com/comentario/970098/) 
Con respecto a \g. ¿Me permite ejecutar el comando que ejecuté que ejecutó otro usuario conectado a la misma base de datos ?

	* **Juan David Castro (Platzi)** [80953] (2)

		¡Hola!
		
		No estoy seguro si el con el comando \g podemos acceder a los comandos que ejecutaron el resto de usuarios. Me parece que todos ellos se guardan en el archivo **`.psql_history`**. Pero también creo que se borran. No lo sé.
		
		* <https://www.postgresql.org/docs/9.4/app-psql.html>
		
		
		
		Aunque sí hay formas de ver los comandos que han ejecutado todos los usuarios de tu base de datos. Estos tutoriales pueden ayudarte:
		
		* <https://chartio.com/resources/tutorials/how-to-log-queries-in-postgresql/>
		* <https://stackoverflow.com/questions/8208310/postgresql-how-to-see-which-queries-have-run>
		* <https://stackoverflow.com/questions/42747235/loging-activity-for-one-user-on-specific-database-in-postgres>
		
		

## 0050. PgAdmin Interacción con Postgres desde la Interfaz Gráfica [24179](https://platzi.com/clases/1480-postgresql/24179-pgadmin-interaccion-con-postgres-desde-la-interfaz/)

### Descripción:


### Links:

* [pgAdmin - PostgreSQL Tools](https://www.pgadmin.org/)

### Comentarios:

* **Mario Uriarte Amaya** (10) [894937](https://platzi.com/comentario/894937/) 

	Como corrección, la seccion de languages hace referencia a los lenguajes de programacion que puedes usar dentro de la base de datos. Por ejemplo para construir store procedure. Usualmente se usa SQL pero en postgres puedes usar plsql ( el sql de postgres ) o perl, python, etc.
	
	<https://www.postgresqltutorial.com/postgresql-stored-procedures/introduction-to-postgresql-stored-procedures/>

	* **Claudio Sebastian Bolvaran Toro** [894937] (2)

		Buen aporte Mario, ojala lo corrija el profesor, debería… =D

* **Vicente Fernandez** (9) [912779](https://platzi.com/comentario/912779/) 

	Me gusta como explica Oswaldo; calmado, simple y paso a paso…

* **Jairo Lachira Peralta** (5) [964763](https://platzi.com/comentario/964763/) 

	Por si a alguien se olvidó la password, como a mí jeje: <https://dba.stackexchange.com/questions/44586/forgotten-postgresql-windows-password>

* **Sergio Ivan Galvis Motoa** (2) [1110279](https://platzi.com/comentario/1110279/) 

	En macOS para ejecutar el comando:
	``` 
	    plsql -U postgres
	    
	```
	
	Deben adicionar el PATH
	``` 
	    export PATH=/Library/PostgreSQL/11/bin:$PATH
	    
	```
	
	Revisen la versión de Postgres

* **kikega** (2) [1052256](https://platzi.com/comentario/1052256/) 

	Instalación de PGAdmin 4 en Debian 10
	``` 
	    # Importamos la llave del repositorio
	        wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
	        
	        # Añadimos el repositorio
	        /etc/apt/sources.list/d/pgdb.list
	        deb http://apt.postgresql.org/pub/repos/apt buster-pgdb main
	    
	        # Actualizamos e instalamos
	        apt-get update
	        apt-get -y install pgadmin4 pgadmin4-apache2
	    
	```

* **Angel de Jesus Quintero Pereira** (2) [1022716](https://platzi.com/comentario/1022716/) 

	Languages - Languages hace referencia a los lenguajes de programación que puedes usar dentro de la base de datos. Por ejemplo para construir store procedure. Usualmente se usa SQL pero en postgres puedes usar plsql ( el sql de postgres ) o perl, python, etc.

* **dbzdavidbaez** (2) [835833](https://platzi.com/comentario/835833/) 

	Buena explicacion.

* **andoni** (2) [75589](https://platzi.com/comentario/872320/) 
Me confundió un poco la creación del server… Para que se crea uno nuevo, por ejemplo en este caso “MIDBOFI” si tiene el mismo contenido e...

	* **David Rueda** [75589] (2)

		Hola andoni:
		
		En esta actividad se presenta el procedimiento para establecer conexiones a otros servidores, y ver bases de datos disponibles en este.
		
		Aunque en el ejemplo se está conectando al servidor local, es el mismo procedimiento que se sigue para conectarse con un servidor remoto.

* **ALBERTO MONTERRUBIO PEÑA** (2) [73588](https://platzi.com/comentario/837805/) 
que es un dumi?, ha utilizado el termino en alguna clase pasada, pero aun no se bien a que se refiere, aunque hace como referencia a la b...

	* **jairyara** [73588] (4)

		Literalmente significa Tonto. Normalmente se utiliza para referirse a un término o temática fácil de entender por cualquier persona sin importar su nivel de experiencia en el tema.

* **Angel de Jesus Quintero Pereira** (1) [1022720](https://platzi.com/comentario/1022720/) 

	Postgres realiza consulta así mismo para saber su estado

* **Angel de Jesus Quintero Pereira** (1) [1022717](https://platzi.com/comentario/1022717/) 

	Schemas - public- tables Aquí se muestra las tablas de las bases de datos

* **Angel de Jesus Quintero Pereira** (1) [1022715](https://platzi.com/comentario/1022715/) 

	foreign Data Wrappers - Son acceso a base de datos remoto.

* **Angel de Jesus Quintero Pereira** (1) [1022714](https://platzi.com/comentario/1022714/) 

	Extensions - Son módulos desarrollados por terceros que hacen tareas específicas y podemos instalarla en nuestra base de datos

* **Angel de Jesus Quintero Pereira** (1) [1022713](https://platzi.com/comentario/1022713/) 

	Event Trigger - Son funciones y que debido a las acciones que se ejecutan en la base de datos conocidas como eventos estas funciones se activan..

* **Angel de Jesus Quintero Pereira** (1) [1022712](https://platzi.com/comentario/1022712/) 

	catalogs - Contienen información de metadatos y objetos incorporados de Postgres. Es una especie de subdirectorios de tablas.

* **Angel de Jesus Quintero Pereira** (1) [1022711](https://platzi.com/comentario/1022711/) 

	Casts - Controla cómo Postgres lanza de un tipo de datos a otro o también se puede ver como hacer traducción de tipos de datos explícitos

* **Angel de Jesus Quintero Pereira** (1) [1022709](https://platzi.com/comentario/1022709/) 

	Las bases de datos muestra funciones que si podemos acceder a ella a través de comando por la terminal

* **Angel de Jesus Quintero Pereira** (1) [1022700](https://platzi.com/comentario/1022700/) 

	Temple0 y temple1 son modelos de bases de datos privadas y estas las usa postgres para crear nuevas bases de datos basados en estos modelos.

* **Angel de Jesus Quintero Pereira** (1) [1022694](https://platzi.com/comentario/1022694/) 

	Databases: Nos muestra las bases de datos que tenemos instanciada.login/Group Roles: Muestra los usuarios y roles que están actuando sobre las bases de datos. Tablespaces: Podemos configurar qué tabla se puede guardar en una unidad de almacenamiento.

* **Angel de Jesus Quintero Pereira** (1) [1022689](https://platzi.com/comentario/1022689/) 

	En la pestaña Connection nos pedirá la misma información que se mostraba en consola.

* **Angel de Jesus Quintero Pereira** (1) [1022683](https://platzi.com/comentario/1022683/) 

	En la pestaña general, nos pide el nombre del servidor y a cuál grupo de servidor pertenece, también podemos agregar colores para identificarlos en “background” también podemos añadir comentarios.

* **Angel de Jesus Quintero Pereira** (1) [1022678](https://platzi.com/comentario/1022678/) 

	Crear Conexión Para crear una conexión a la bases de datos utilizando la interfaz gráfica como se hace por la consola nos posicionamos donde dice server y hacemos clic derecho y nos mostrará la opción create->Server...

* **Angel de Jesus Quintero Pereira** (1) [1022676](https://platzi.com/comentario/1022676/) 

	En la parte superior se puede se visualiza una barra de herramienta que tiene 2 niveles. Nivel 1 es en donde se puede ver las preferencias, exportar los objetos, crear herramientas. Nivel 2 se muestra las opciones propias de las bases de datos que hayamos seleccionado.

* **Angel de Jesus Quintero Pereira** (1) [1022675](https://platzi.com/comentario/1022675/) 

	Browser - left panel En la sección de la izquierda se puede visualizar todo lo relacionado con los servidores y las bases de datos que tenemo

* **Yesid Anacona** (1) [873230](https://platzi.com/comentario/873230/) 

	El color rojo no deja ver los titulos, escoger uno mejor la proxima por favor.

* **Eduardo Imery Winterdaal** (1) [845125](https://platzi.com/comentario/845125/) 

	Para los que estan usando macOs, si al instalar Postgress con el .dmg bajado de la pagina no les crea el enlace en la terminal para ejecutar “psql”, solo tienen que agregar la ruta al PATH y asi porder correr desde cualquier ventana de terminal

* **ejgachancipa** (1) [86774](https://platzi.com/comentario/1104051/) 
No me aparece PostgreSQL 11, alguien sabe como solucionarlo?

* **Angel Daniel Mendieta Castillo** (1) [86689](https://platzi.com/comentario/1101443/) 
El PGAdmin 3 que tan recomendado es o eso depende de el que se entienda mejor para nosotros trabajar ?

* **william albeiro amaya patiño** (1) [82498](https://platzi.com/comentario/1006590/) 
me sale este error the application server could not be contacted

	* **Angel Daniel Mendieta Castillo** [82498] (1)

		no se pudo contactar al servidor de aplicaciones postgresql.  
		este vídeo te puede ayudar a solucionar ese problema  
		<https://www.youtube.com/watch?v=LINNoLufvOo>

* **Hugo César** (1) [81646](https://platzi.com/comentario/986002/) 
Alguien sabe donde puedo conseguir una base de datos? No tengo ninguna y seria para practicar.

	* **Massimo Di Berardino** [81646] (1)

		Hola Cesar, [acá](https://www.postgresqltutorial.com/postgresql-sample-database/) puedes encontrar una DB para practicar tiene 15 tablas con algunas tablas pivots, espero que te sea util, saludos!

## 0060. Archivos de Configuración [24180](https://platzi.com/clases/1480-postgresql/24180-archivos-de-configuracion/)

### Descripción:


### Links:

* [Curso de Administración de Servidores Linux | Platzi](https://platzi.com/clases/linux/)

* [Domina la Administración de Usuarios y Permisos en Servidores Linux](https://platzi.com/blog/administracion-usuarios-servidores-linux/)

* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/)

### Comentarios:

* **Luis Rodrigo Alvarez Herrera** (5) [841698](https://platzi.com/comentario/841698/) 

	Mi resumen:
	
	Los archivos de configuración son tres principales:
	
	* postgreql.conf
	* pg.hba.conf
	* pg_ident.conf
	
	
	
	La ruta de los mismos depende del sistema Operarivo, para saber que que ruta estan, basta con hacer una Query
	
	* SHOW config_file;
	
	
	
	NOTA: siempre es bueno hacer una copia original de los archivos antes de modificarlos por si movemos algo que no.

	* **Vicente Fernandez** [841698] (1)

		pg_hba.conf *

* **dbzdavidbaez** (5) [836235](https://platzi.com/comentario/836235/) 

	Muy interesante e importante
	``` 
	    SHOW config_file;
	    
	```
	
	/etc/postgresql/10/main/postgresql.conf

* **TUDz** (4) [836220](https://platzi.com/comentario/836220/) 

	Resumen de archivos de configuración.
	
	A través de la sentencia SHOW CONFIG se nos muestra donde están los archivos de configuración. En mi caso la ruta es:  
	/Library/PostgreSQL/12/data/postgresql.conf
	
	Algo a tener en cuenta es que en la ruta por default de instalación no se puede acceder debido a falta de permisos. Para ingresar basta con un:
	
	sudo cd /Library/PostgreSQL/12/data/
	
	**Postgresql.conf** : Configuración general de postgres, múltiples opciones referentes a direcciones de conexión de entrada, memoria, cantidad de hilos de pocesamiento, replica, etc.
	
	**pg_hba.conf** : Muestra los roles así como los tipos de acceso a la base de datos.
	
	**pg_ident.conf** : Permite realizar el mapeo de usuarios. Permite definir roles a usuarios del sistema operativo donde se ejecuta postgres.

* **Miguel Torres** (1) [1114789](https://platzi.com/comentario/1114789/) 

	Esto es oro. 😮

* **Francisco de Castro** (1) [1057360](https://platzi.com/comentario/1057360/) 

	la consulta "show config_file; " (No es una consulta de SqL no?)

	* **Oz** [1057360] (3)

		según el estandar SQL no, pero si es una consulta a postgresql que internamente usa el mismo motor de SQL para resolver

	* **Francisco de Castro** [1057360] (1)

		ah perfecto muchas gracias!!

* **Angel de Jesus Quintero Pereira** (1) [1024351](https://platzi.com/comentario/1024351/) 

	pg_ident.conf: Específicamente esto nos sirve para mapear usuarios. Esto es funcional para darle permisos a una cuenta local de equipo permisos de administrador

* **Angel de Jesus Quintero Pereira** (1) [1024343](https://platzi.com/comentario/1024343/) 

	En METHOD = deny sirve para denegar a una ip específica o servicio que se deniega el acceso. Esto es muy funcional para un servicio maligno.

* **Angel de Jesus Quintero Pereira** (1) [1024339](https://platzi.com/comentario/1024339/) 

	En METHOD = trust, esto sirve para que los usuarios desde cierto pool de ip no tenga que autenticarse.

* **Angel de Jesus Quintero Pereira** (1) [1024298](https://platzi.com/comentario/1024298/) 

	Todos los valores comentados en los archivos son los valores por defectos, para cambiar los valores se debe descomentar y cambiar el valor. También hay que tener en cuanta que la bases de datos toma en cuenta estos valores solo en el siguiente reinicio.

* **Angel de Jesus Quintero Pereira** (1) [1024287](https://platzi.com/comentario/1024287/) 

	postgresql.conf: En este fichero podemos cambiar los parámetros de PostgreSQL por ejemplo en la sección Connection Settings se cambia las conexiones máxima, el socket cuales IP le podemos dar acceso. Este un archivo que básicamente se rige por para =valor

* **Angel de Jesus Quintero Pereira** (1) [1024253](https://platzi.com/comentario/1024253/) 

	SHOW config_file; Con la anterior sentencia podemos ver la ruta de los archivos de configuración de postgres

* **Angel de Jesus Quintero Pereira** (1) [1024233](https://platzi.com/comentario/1024233/) 

	Existen tres archivos importantes para realizar configuraciones extras y también corregir el 99 % de los errores en nuestro motor de bases de datos cuando queremos agregar servicios y son: 1.postgresql.conf, 2.pg_hba.conf, 3.pg_iden.conf

* **Vicente Fernandez** (1) [913319](https://platzi.com/comentario/913319/) 

	En mac no puedo abrir la carpeta “data”, me dice que no tengo permiso para hacerlo.

	* **Israel Yance** [913319] (2)

		Puedes ver el archivo en consola usando sudo:
		``` 
		    sudo cat /Library/PostgreSQL/11/data/postgresql.conf
		    
		```

	* **Israel Yance** [913319] (1)

		En general, usando sudo en consola puedes hacer cualquier cosa, ver o editar los archivos.

* **Adrian Castillo Ramírez** (1) [913253](https://platzi.com/comentario/913253/) 

	Por seguridad solo se debe dejar acceso a todos los usuarios desde el localhost, cuando este en producción seria mejor restringir todos los accesos.

* **MaxLandh** (1) [911525](https://platzi.com/comentario/911525/) 

	Hola ¿Alguien sabe que tipo de lenguaje son los archivos config? Es que estoy abriéndolo con Atom.

	* **Adrian Castillo Ramírez** [911525] (2)

		Es texto plano, cualquier editor debería poder abrirlo

* **JOSE PEREZ** (1) [836954](https://platzi.com/comentario/836954/) 

	Estimados,
	
	una consulta, ¿como podria configurar los archivos pg_hba.conf y/o postgres.conf para poder hacer que la autenticación de los usuarios sea Windows Authentication?

	* **Oz** [836954] (6)

		Para ello debes modificar los archivos pg_ident y pg_hba, debes hacer algo asi:  
		En ident agrega el mapeo al usuario local de windows. si tienes usuario propio o vas a crear usuario en windows para conectarse, supongamos que oz es el nombre de usuario :  
		`
		
		<h1>MAPNAME SYSTEM-USERNAME PG-USERNAME</h1>
		
		MapForSSPI oz@YOURMACHINENAMEHERE oz`
		
		Luego vas a pg_hba y agregas la Principio, si estas usando solo el nombre de usuario:  
		`# IPv4  
		host all oz 127.0.0.1/32 sspi map=MapForSSPI
		
		<h1>IPv6</h1>
		
		host all oz ::1/128 sspi map=MapForSSPI  
		`  
		Recuerda reiniciar el servicio de postgres despues de guardar estos cambios para que tengan efecto.  
		Ahora si intentas acceder a postgres usando el usuario oz y estas conectado en windows con el usuario oz no deberia pedirte clave.

* **Angel Daniel Mendieta Castillo** (1) [86695](https://platzi.com/comentario/1101556/) 
En que lugar veo encuentro los diferentes usuarios de la DB y los permisos que tiene cada uno de dichos usuarios ?

	* **Nestor Gerardo Gonzalez Roque** [86695] (1)

		puedes ver los usuarios usando el comando de postgres \du  
		los permisos se los otorgas a las diferente bases o tablas y cuando las describes puedes ver quien es el dueño de cada una o puedes usar \du+ para ver que roles tiene cada usuario te recomiendo leer el siguiente articulo para que entiendas un poco mas  
		<https://www.linuxito.com/gnu-linux/nivel-alto/840-roles-y-permisos-en-postgresql>

## 0070. Comandos más utilizados en PostgreSQL [24849](https://platzi.com/clases/1480-postgresql/24849-comandos-mas-utilizados-en-postgresql/)

### Descripción:


**La Consola**

La consola en PostgreSQL es una herramienta muy potente para crear, administrar y depurar nuestra base de datos. podemos acceder a ella después de instalar PostgreSQL y haber seleccionado la opción de instalar la consola junto a la base de datos.

PostgreSQL está más estrechamente acoplado al entorno UNIX que algunos otros sistemas de bases de datos, utiliza las cuentas de usuario nativas para determinar quién se conecta a ella (de forma predeterminada). El programa que se ejecuta en la consola y que permite ejecutar consultas y comandos se llama psql, psql es la terminal interactiva para trabajar con PostgreSQL, es la interfaz de línea de comando o consola principal, así como PgAdmin es la interfaz gráfica de usuario principal de PostgreSQL.

Después de emitir un comando PostgreSQL, recibirás comentarios del servidor indicándote el resultado de un comando o mostrándote los resultados de una solicitud de información. Por ejemplo, si deseas saber qué versión de PostgreSQL estás usando actualmente, puedes hacer lo siguiente:

![1.png](https://static.platzi.com/media/user_upload/1-3db23704-3297-40cf-b3fc-27ec761a2579.jpg)

**_Comandos de ayuda_**

En consola los dos principales comandos con los que podemos revisar el todos los comandos y consultas son:

* **`\?`** Con el cual podemos ver la lista de todos los comandos disponibles en consola, comandos que empiezan con backslash ()

![2.png](https://static.platzi.com/media/user_upload/2-f3fd936e-bdb2-4583-afce-1899ca222a77.jpg)

* **`\h`** Con este comando veremos la información de todas las consultas SQL disponibles en consola. Sirve también para buscar ayuda sobre una consulta específica, para buscar información sobre una consulta específica basta con escribir **`\h`** seguido del inicio de la consulta de la que se requiera ayuda, así: **`\h ALTER`**



De esta forma podemos ver toda la ayuda con respecto a la consulta **_ALTER_**

![3.png](https://static.platzi.com/media/user_upload/3-ee850ea6-271e-4826-9d8f-aa054dddc3fc.jpg)

**_Comandos de navegación y consulta de información_**

* **`\c`** Saltar entre bases de datos

* **`\l`** Listar base de datos disponibles

* **`\dt`** Listar las tablas de la base de datos

* **`\d<nombre_tabla>`** Describir una tabla

* **`\dn`** Listar los esquemas de la base de datos actual

* **`\df`** Listar las funciones disponibles de la base de datos actual

* **`\dv`** Listar las vistas de la base de datos actual

* **`\du`** Listar los usuarios y sus roles de la base de datos actual




**_Comandos de inspección y ejecución_**

* **`\g`** Volver a ejecutar el comando ejecutando justo antes

* **`\s`** Ver el historial de comandos ejecutados

* **`\s<nombre_archivo>`** Si se quiere guardar la lista de comandos ejecutados en un archivo de texto plano

* **`\i<nombre_archivo>`** Ejecutar los comandos desde un archivo

* **`\e`** Permite abrir un editor de texto plano, escribir comandos y ejecutar en lote. **\e** abre el editor de texto, escribir allí todos los comandos, luego guardar los cambios y cerrar, al cerrar se ejecutarán todos los comandos guardados.

* **`\ef`** Equivalente al comando anterior pero permite editar también funciones en PostgreSQL




**_Comandos para debug y optimización_**

* **`\timing`** Activar / Desactivar el contador de tiempo por consulta



**_Comandos para cerrar la consola_**

* **`\q`** Cerrar la consola



**_Ejecutando consultas en la base de datos usando la consola_**

De manera predeterminada PostgreSQL no crea bases de datos para usar, debemos crear nuestra base de datos para empezar a trabajar, verás que existe ya una base de datos llamada **_postgres_** pero no debe ser usada ya que hace parte del CORE de PostgreSQL y sirve para gestionar las demás bases de datos.

Para crear una base de datos debes ejecutar la consulta de creación de base de datos, es importante entender que existe una costumbre no oficial al momento de escribir consultas; consiste en poner en mayúsculas todas las palabras propias del lenguaje SQL cómo **_CREATE, SELECT, ALTE_** , etc y el resto de palabras como los nombres de las tablas, columnas, nombres de usuarios, etc en minúscula. No está claro el porqué de esta especie de “estándar” al escribir consultas SQL pero todo apunta a que en el momento que SQL nace, no existían editores de consultas que resaltaran las palabras propias del lenguaje para diferenciar fácilmente de las palabras que no son parte del lenguaje, por eso el uso de mayúsculas y minúsculas.

Las palabras reservadas de consultas SQL usualmente se escriben en mayúscula, ésto para distinguir entre nombres de objetos y lenguaje SQL propio, no es obligatorio, pero podría serte útil en la creación de Scripts SQL largos.

Vamos ahora por un ligero ejemplo desde la creación de una base de datos, la creación de una tabla, la inserción, borrado, consulta y alteración de datos de la tabla.

Primero crea la base de datos, “ **CREATE DATABASE transporte** ;” sería el primer paso.

![4.png](https://static.platzi.com/media/user_upload/4-669e8520-bb3d-47f5-9002-a3f5fcaf9191.jpg)

Ahora saltar de la base de datos **_postgres_** que ha sido seleccionada de manera predeterminada a la base de datos transporte recién creada utilizando el comando **`\c transporte`**.

![5.png](https://static.platzi.com/media/user_upload/5-7d6dd8c4-a03b-48b7-b077-4cb589f55ee2.jpg)

Ahora vamos a crear la tabla tren, el SQL correspondiente sería:

`CREATE TABLE tren ( id serial NOT NULL, modelo character varying, capacidad integer, CONSTRAINT tren_pkey PRIMARY KEY (id) );`

La columna id será un número autoincremental (cada vez que se inserta un registro se aumenta en uno), modelo se refiere a una referencia al tren, capacidad sería la cantidad de pasajeros que puede transportar y al final agregamos la llave primaria que será id.

![6.png](https://static.platzi.com/media/user_upload/6-444c767c-7f5b-4410-ac3a-df6c23d4552a.jpg)

Ahora que la tabla ha sido creada, podemos ver su definición utilizando el comando **`\d tren`**

![7.png](https://static.platzi.com/media/user_upload/7-93ef9744-1514-4d83-bf0b-b13462b639ca.jpg)

PostgreSQL ha creado el campo id automáticamente cómo integer con una asociación predeterminada a una secuencia llamada ‘tren_id_seq’. De manera que cada vez que se inserte un valor, id tomará el siguiente valor de la secuencia, vamos a ver la definición de la secuencia. Para ello, **`\d tren_id_seq`** es suficiente:

![8.png](https://static.platzi.com/media/user_upload/8-6f223092-0ee7-49db-8979-b251f1d5f56a.jpg)

Vemos que la secuencia inicia en uno, así que nuestra primera inserción de datos dejará a la columna id con valor uno.

**`INSERT INTO tren( modelo, capacidad ) VALUES (‘Volvo 1’, 100);`**

![9.png](https://static.platzi.com/media/user_upload/9-86a5c14f-d2ef-45eb-b835-abbb32f0d34b.jpg)

Consultamos ahora los datos en la tabla:

**`SELECT * FROM tren;`**

![10.png](https://static.platzi.com/media/user_upload/10-2c25adb4-615f-4691-973f-c0a231c33d60.jpg)

Vamos a modificar el valor, establecer el tren con id uno que sea modelo Honda 0726. Para ello ejecutamos la consulta tipo **`UPDATE tren SET modelo = 'Honda 0726' Where id = 1;`**

![11.png](https://static.platzi.com/media/user_upload/11-b1d3b646-6ca6-4ae0-9005-ed002c21ef32.jpg)

Verificamos la modificación **`SELECT * FROM tren;`**

![12.png](https://static.platzi.com/media/user_upload/12-370abb43-290b-43bd-a1c2-609c42b85767.jpg)

Ahora borramos la fila: **`DELETE FROM tren WHERE id = 1;`**

![13.png](https://static.platzi.com/media/user_upload/13-4224641d-e97f-4e01-8784-19b2a9d39386.jpg)

Verificamos el borrado **`SELECT * FROM tren;`**

![14.png](https://static.platzi.com/media/user_upload/14-9a75b2b9-587b-476a-88b1-15c6164104c8.jpg)

El borrado ha funcionado tenemos 0 rows, es decir, no hay filas. Ahora activemos la herramienta que nos permite medir el tiempo que tarda una consulta **`\timing`**

![15.png](https://static.platzi.com/media/user_upload/15-ccffbd2f-fd1a-4fa2-ae31-43313bc5a82b.jpg)

Probemos cómo funciona al medición realizando la encriptación de un texto cualquiera usando el algoritmo md5:

![16.png](https://static.platzi.com/media/user_upload/16-0699feec-184c-4aa3-8b9a-2a03e1326238.jpg)

La consulta tardó 10.011 milisegundos

Ahora que sabes como manejar algunos de los comandos más utilizados en PostgreSQL es momento de comenzar a practicar!!!

### Comentarios:

* **dbzdavidbaez** (6) [836353](https://platzi.com/comentario/836353/) 

	Resumen de la clase
	``` 
	    SELECTVERSION();
	        PostgreSQL 11.6 (Ubuntu 11.6-1.pgdg18.04+1) on x86_64-pc-linux-gnu, compiled by gcc (Ubuntu 7.4.0-1ubuntu1~18.04.1) 7.4.0, 64-bit
	    \h -- ayuda
	    \h comnado -- ayuda del comando especifico
	    \l -- Listar las bases
	    \c base de datos --moverse a una base de datos especifica
	    \dt -- listar las tablas de la base actual
	    \dn -- listar los esquemas de la base actual
	    \dv -- listar las vistas
	    \df -- listar las funciones
	    \du -- listar los usuarios
	    \g -- ejecutar ultimo comando 
	    \s -- historial de comandos
	    \l nombrearchivo --guardar lista de comandos
	    \i nombre archivo -- ejecuta comandos guardados
	    \e -- abrir editor 
	    \ef -- editor de funciones
	    \timming -- activar o desactivar el tiempo de respusta de las consultas
	    \q cerra consola
	    CREATEDATABASE base; -- crea base
	    CREATETABLE tabla (columnas); crea tabla
	    INSERTINTO tabla(columna) VALUES('dato');
	    SELECT * FROM tabla;
	    UPDATE tabla SET cammpo = dato WHERE condicion;
	    DELETEFROM tabla WHERE condicion;
	    
	```

* **SergioRubiano** (4) [965414](https://platzi.com/comentario/965414/) 

	Creo que esta clase debería estar al comienzo antes de entrar a la consola y luego que el profesor la explicara como lo hizo en clase numero 4 😃

* **Adrian Castillo Ramírez** (4) [913258](https://platzi.com/comentario/913258/) 

	Algo importante es siempre hacer un select where antes de un delete ya que si no podrias elimitar toda tu tabla o base de datos;

* **Juan Carlos Valencia López** (3) [836102](https://platzi.com/comentario/836102/) 

	El mio no se demoró demasidado  
	Time: 0.303 ms

* **Abril Darynka Tapia Sosa** (2) [928623](https://platzi.com/comentario/928623/) 

	Esto me esta gustando (• ◡ •)/

* **Ramírez Paredes Jhon** (2) [903789](https://platzi.com/comentario/903789/) 

	Duración : 0.483 ms

* **andoni** (2) [873387](https://platzi.com/comentario/873387/) 

	Alguien sabe cómo puedo instalar el historial o sabe por qué no me deja?  
	![h.JPG](https://static.platzi.com/media/user_upload/h-20558f96-5757-4d68-a2e5-21f0bd092412.jpg)

* **Miguel Torres** (1) [1115784](https://platzi.com/comentario/1115784/) 

	La consulta del MD5 tardó demasiado en el texto de arriba D:
	
	A mí solo me dio 0.978 ms

* **Francisco de Castro** (1) [1057990](https://platzi.com/comentario/1057990/) 

	hago un pregunta por que no es lo mismo poner AUTO_INCREMENT a SERIAL Y por ejemplo character varying (n) a varchar(n)?

* **Luis Rodrigo Alvarez Herrera** (1) [853934](https://platzi.com/comentario/853934/) 

	El usar operaciones basicas se parece mucho a las otras syntaxis, por ahora no veo diferencias en MYSQL

## 0080. Presentación del Proyecto [24181](https://platzi.com/clases/1480-postgresql/24181-presentacion-del-proyecto/)

### Descripción:


### Comentarios:

* **Jaime Andrés Martínez Rodríguez** (2) [930870](https://platzi.com/comentario/930870/) 

	Esta DB tendrá muchisimas entidades hahahaha

* **Diego D Ascoli Batista** (2) [839065](https://platzi.com/comentario/839065/) 

	Genial

* **dbzdavidbaez** (2) [836359](https://platzi.com/comentario/836359/) 

	Listo para implementar el proyecto.

* **Jeisson Santiago Cortes Ortiz** (1) [983530](https://platzi.com/comentario/983530/) 

	Seria bueno integrar bases de datos con lenguajes de programacion en futuros clases.

	* **Manuel Alejandro Aguilar Téllez Girón** [983530] (1)

		Puedes echarle un vistazo a **sqlalchemy** si usas `python`, también hay una librería llamada **pymongo** para Mongo. En lo personal, he usado lo que mencionas para dos cosas:
		
		  1. Crear tablas desde un framework con ayuda del ORM, por ejemplo, Django.
		  2. Hacer conexiones para utilizar los datos que están dentro de ellas y generar pues alguna relación matemática o algo así.
		
		

* **raul-fernandez-fuentes** (1) [926165](https://platzi.com/comentario/926165/) 

	Quiza agregar tipos o categorias seria genial.

* **miguelangelpglez** (1) [881209](https://platzi.com/comentario/881209/) 

	El pasajero podría modelarse como:
	
	**pasajero** (numero de tarjeta de acceso, estacion de entrada, hora de entrada)

* **adriangonw77** (1) [880531](https://platzi.com/comentario/880531/) 

	me parece genial para empezar a enteder esta nueva base de datos

## 0090. Tipos de datos [24182](https://platzi.com/clases/1480-postgresql/24182-tipos-de-datos/)

### Descripción:


### Links:

* [PostgreSQL data types, tipos de datos más utilizados - TodoPostgreSQL](https://todopostgresql.com/postgresql-data-types-los-tipos-de-datos-mas-utilizados/)

* [PostgreSQL: Documentation: 11: Chapter 8. Data Types](https://www.postgresql.org/docs/11/datatype.html)

### Comentarios:

* **Juan Carlos Valencia López** (3) [836107](https://platzi.com/comentario/836107/) 

	Tipos de datos
	
	Principales:  
	Numéricos(Numeros enteros, Numeros Decimales, Seriales)  
	Monetarios(cantidad de moneda)  
	Texto(almacenar cadenas y texto, existen tres VARCHAR, CHAR, TEXT)  
	Binario(1 Y 0)  
	Fecha/Hora(Para almacenar Fechas y/o Horas, DATE TYPE, TIME TYPE, TIMESTAMP, INTERVAL)  
	Boolean(Verdadero o Falso)  
	Especiales propios de postgres  
	Geométricos: Permiten calcular distancias y áreas usando dos valores X y Y.  
	Direcciones de Red: Cálculos de máscara de red  
	Texto tipo bit: Cálculos en otros sistemas, ejm(hexadecimal, binario)  
	XML, JSON: Postgres no permite guardar en estos formatos  
	Arreglos: Vectores y Matrices

* **miguelangelpglez** (2) [881249](https://platzi.com/comentario/881249/) 

	El tipo de dato TIMESTAMP, almacena fechas con zona horaria  
	Por ejemplo:
	
	TIMESTAMP ‘2010-01-05 08:10:00-06’
	
	Este formato incluye fecha, hora y el -06 es la zona horaria.

* **dbzdavidbaez** (2) [836626](https://platzi.com/comentario/836626/) 

	Muy interesante
	
	[Tipos de datos relevantes en PostgreSQL](https://www.ibiblio.org/pub/linux/docs/LuCaS/Tutoriales/NOTAS-CURSO-BBDD/notas-curso-BD/node134.html)

* **TUDz** (2) [836228](https://platzi.com/comentario/836228/) 

	La ventaja de tener un tipo de dato dedicado a XML o JSON es que puedes almacenarlo en la BD para posterior, a través de una tarea programada o un Stored Procedure, proceder a la lectura, descomposición y manipulación contenida en dichos documentos. Todo esto, ya queda del lado de la BD por lo que a nuestro web service (o lenguaje backend en turno) se le quita cierta carga de procesamiento.
	
	¡Saludos!

* **raymundoortegaflores** (1) [872969](https://platzi.com/comentario/872969/) 

	1.- Boolean  
	2.- Character # types such as char, varchar, and text.  
	3.- Numeric types such as integer and floating-point number.  
	4.- Temporal types such as date, time, timestamp, and interval  
	5.- UUID for storing Universally Unique Identifiers  
	6.- Array for storing array strings, numbers, etc.  
	7.- JSON stores JSON data  
	8.- hstore stores key-value pair  
	9.- Special types such as network address and geometric data.

## 0100. Diseño de la solución del Proyecto [24183](https://platzi.com/clases/1480-postgresql/24183-diseno-de-la-solucion-del-proyecto/)

### Descripción:


### Links:

* [Fundamentos de Bases de Datos](https://platzi.com/clases/bd/)

### Comentarios:

* **DiegoADaza** (9) [879419](https://platzi.com/comentario/879419/) 

	Yo por experiencia crearía mejor el nombre de las tablas en Plural:
	
	Estaciones  
	Trenes  
	Usuarios
	
	Etc Etc

	* **miguelangelpglez** [879419] (1)

		Estoy de acuerdo.

	* **David Rueda** [879419] (3)

		Esta misma recomendación la entregan en el curso de conceptos de bases de datos.

	* **David Morán** [879419] (1)

		Claro, porque las tablas no van contener una unica información

	* **Adrian Castillo Ramírez** [879419] (1)

		Creo que tambien depende de que sistema uses, por ejemplo Django Admin le agrega una s al final por lo que si el modelo se llama Estaciones en el admin lo reflejaria como estacioness

	* **David Morán** [879419] (1)

		Muchas gracias mis estimados.

* **Andres Rivera** (7) [835467](https://platzi.com/comentario/835467/) 

	Esta dañdo el video!!! dura 2 horas

	* **Oz** [835467] (5)

		Gracias por el aviso, se está corrigiendo.

	* **Juan David Castro (Platzi)** [835467] (2)

		¡Ya lo solucionaron! 🎉

* **Abril Darynka Tapia Sosa** (6) [928780](https://platzi.com/comentario/928780/) 

	![Modelo Relacional](![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-37dabc12-1db1-4362-9c90-c9e4c65125c0.jpg)

	* **Jaime Andrés Martínez Rodríguez** [928780] (1)

		Gracias!

	* **Jeisson Santiago Cortes Ortiz** [928780] (1)

		Nice

* **Marco Soudre Oliva** (4) [914773](https://platzi.com/comentario/914773/) 

	No quedé conforme con el argumento de la relación entre la Tabla PASAJERO y la de VIAJE (y coincido con los amigos que dicen que debiesen ser en Plural) ya que la acción debiese darse con los verbo “Puede” y “Toma”. En esto las preguntas sería "¿Un pasajero puede tomar muchos viajes?, Sí " y la otra sería “¿Un viaje puede ser tomado por muchos pasajeros?, Si”. Por lo tanto, la relación sería de N:N y esto se debe romper creando una tabla intermedia débil. Es mi humilde opinión. Saludos.

	* **Vicente Fernandez** [914773] (3)

		La tabla viaje tiene el campo id_pasajero, por lo que corresponde a un pasajero único. Pienso que cada renglón de la tabla viaje representará el trayecto que recorre cada pasajero. Por lo que coincido con el profesor, la relación seria de 1:N.

* **Juan Carlos Valencia López** (3) [836109](https://platzi.com/comentario/836109/) 

	Cuanto dura en si el video?
	
	en el min 2:40 ya no carga

	* **Juan David Castro (Platzi)** [836109] (2)

		Ya lo solucionaron. La clase dura 13 minutos. Puedes volver probar si funciona. 💪

* **andoni** (3) [75666](https://platzi.com/comentario/873680/) 
Si la relación entre trayecto y viaje es muchos a muchos tendría que realizarse una tercera tabla no?

	* **David Rueda** [75666] (1)

		Ando ni, efectivamente en ese tipo de relación debe crearse una tercera tabla que asocie las tablas de Trayectos y Viajes.

* **Francisco de Castro** (2) [1059355](https://platzi.com/comentario/1059355/) 

	En el caso por ejemplo que en la tabla trayecto quiero poner id_estacion1 (la de origen) y otro id_estacion2 (la de destino), tengo que referencias ambas columnas de la tabla trayecto al id de estacion? o hacer dos tablas iguales de estacion pero que una sea origen y otra destino?

	* **JosBryan** [1059355] (1)

		estas confundido amigo, mira lo que pasa con por ejemplo con persona es que creas una clase, o bien o tipo de objeto con atributos que listas. Esto mediante un proceso de abstracción en que generalizas las cosas siguiendo como con ejemplo de persona, en este caso no te importa su color, o su religion son datos irrelevantes, ailas los datos que te importan; nombre, dirección, fecha_de_registro.
		
		y comienzas a crear objetos a partir de la clase por ejemplo la clase es persona y un objeto es algo ya especifico como Juan, José, Etc.
		
		El id es como un numero que idintifica el orden con que se creo cada objeto, ya que jose de edo_mex es diferente de jose de cdmx.  
		1 jose edo_mex 19/02/99  
		2 jose cdmx 12/12/20  
		entonces ahora son completamente distintos.  
		ahora poniendo el ejemplo de tu pregunta de estaciones podriamos imaginar dos registros o bien dos objetos con los siguientes datos  
		id nombre  
		1 pinoSuarez  
		2 tasqueña  
		pero es la misma tabla Estación con dos objetos o bien en terminos de bases de datos, dos registros.
		
		y en trayecto teniendo una estructura mas o menos así id, nombre_Ruta, origen_estacion, destino_estacion. tenemos entonces:  
		1 corto 1 2
		
		de esta forma tienes un trayecto llamada “corto” que va de “pinoSuarez” a "tasqueña"  
		todo gracias al id que en relidad es una forma de referenciar a un objeto (registro) con todos sus atributos, evitando redundancia de datos

	* **Francisco de Castro** [1059355] (2)

		Ahh claro Jos! si sii mi pregunta iba bien relacionada a lo que explicaste al ultimo _“y en trayecto teniendo una estructura mas o menos así id, nombre_Ruta, origen_estacion, destino_estacion. tenemos entonces:  
		1 corto 1 2”_ Esa era mi pregunta.  
		En conlusión en ese caso va a haber 2 columnas (origen_estacion, destino_estacion) de la tabla **trayectos** que van a tener su referencia en el id de la tabla **estacion**.  
		Que pensas vos?

	* **JosBryan** [1059355] (1)

		sip, así es, aquí el docente lo hizo como viaje en un solo sentido, y como te lo comente seria más como un metro o suburbano.

	* **Francisco de Castro** [1059355] (1)

		Perfecto muchas gracias!

* **Angel de Jesus Quintero Pereira** (2) [1025388](https://platzi.com/comentario/1025388/) 

	Es Buena práctica como se ve en otros cursos es muy buena práctica tener los nombres de las tablas (sustantivos) en inglés y en plural.

	* **cconde** [1025388] (1)

		el de SQL y MySQL…

* **asanchez2091** (2) [975410](https://platzi.com/comentario/975410/) 

	Se le puede agregar otra tabla para los boletos que asocie al pasajero, con el tren y el trayecto y dependiendo del tipo de trayecto incluso una habitación.

* **gorydev** (2) [839236](https://platzi.com/comentario/839236/) 

	excelente clase muy buena explicación

* **Wilson Marino Pablo Mendez** (2) [837521](https://platzi.com/comentario/837521/) 

	¡Se puede hacer relación de “muchos a muchos”? o crear una tabla debil para esa relación.

	* **Jose Luis Perez** [837521] (6)

		Si se puede. Por lo regular se usa una tabla terciaría con la relación de las dos tablas. La nomenclatura aceptada es la concatenación de las dos tablas ordenadas por orden alfabético, por ejemplo:
		
		"trayectos_viajes"  
		id_trayecto  
		id_viaje

	* **Gabriel De Andrade (Platzi)** [837521] (3)

		De hecho todo esto se aprende en el [Curso de Fundamentos de Bases de Datos](https://platzi.com/clases/bd/), te invito a que le eches un ojo 😄

	* **Deiby Johany Avila Gutierrez** [837521] (3)

		LO IDEAL ES GENERARL UNA ENTIDAD DEBIL INTERMEDIA ENTRE LAS DOS TABLAS

	* **Wilson Marino Pablo Mendez** [837521] (3)

		Gracias por sus comentarias.
		
		SALUDOS!!

* **dbzdavidbaez** (2) [836627](https://platzi.com/comentario/836627/) 

	Interesante tecnica para diseñar el modelo entidas relacion.

* **OscarGama** (1) [1099954](https://platzi.com/comentario/1099954/) 

	No es una buena practica tener relaciones muchos a muchos en un diagrama ER.
	
	Considero que la relación entre Trayecto y Viaje es de uno a muchos, respectivamente.

* **Angel de Jesus Quintero Pereira** (1) [1025378](https://platzi.com/comentario/1025378/) 

	Es buena práctica que: Los PRIMARY KEY (clave primaria) que se referencian en los FOREING KEY (clave foránea) de otras tablas deben ser del mismo tipos de datos

* **Angel de Jesus Quintero Pereira** (1) [1025374](https://platzi.com/comentario/1025374/) 

	Es buena práctica antes de sentarnos a crear tablas en nuestro modelo sentarnos a realizar el diseño y el proceso recomendado es este: 1. Modelo-Entidad Relación, 2. Modelo Relacional (Modelo Físico), 3.Normalización de datos.

* **Angel de Jesus Quintero Pereira** (1) [1025362](https://platzi.com/comentario/1025362/) 

	Es buena práctica al modelar, saber cuales son nuestras relaciones(tablas o entidades) y para ello pensamos en cuales son los objetos tangibles en nuestro contexto de problema

* **Edgar Román** (1) [1024646](https://platzi.com/comentario/1024646/) 

	Corrección: Es un modelo relacional, no un entidad-relación

* **raul-fernandez-fuentes** (1) [926185](https://platzi.com/comentario/926185/) 

	Bueno, el modelo depende de la realidad y momento de los datos y sobre todo el espacio para el cual fue creado.

* **miguelangelpglez** (1) [881255](https://platzi.com/comentario/881255/) 

	En la ciudad de Mexico existe un sistema de Transporte de Autobuses co rutas fijas que cubren gran parte de la ciudad.  
	El acceso es por medio de una tarjeta CONTACT LESS que da acceso a la estacion. Pero existen estaciones en la acera, en donde no existe acceso; el autobus viene equipado con una terminal lectora de tarjeta para autorizar el acceso por medio de la tarjeta

* **Luis Nilson Palma Campos** (1) [866855](https://platzi.com/comentario/866855/) 

	Cual seria la nueva tabla que se genera entre trayecto y viaje?Seria algo así como el comprobante el cual llevara toda la información?

## 0110. Jerarquía de Bases de Datos [24848](https://platzi.com/clases/1480-postgresql/24848-jerarquia-de-bases-de-datos/)

### Descripción:


Toda jerarquía de base de datos se basa en los siguientes elementos:

* **Servidor de base de datos:** Computador que tiene un motor de base de datos instalado y en ejecución.

* **Motor de base de datos:** Software que provee un conjunto de servicios encargados de administrar una base de datos.

* **Base de datos:** Grupo de datos que pertenecen a un mismo contexto.

* **Esquemas de base de datos en PostgreSQL:** Grupo de objetos de base de datos que guarda relación entre sí (tablas, funciones, relaciones, secuencias).

* **Tablas de base de datos:** Estructura que organiza los datos en filas y columnas formando una matriz.




**PostgreSQL es un motor de base de datos.**

La estructura de la base de datos diseñada para el reto corresponde a los siguientes  
elementos:

![1.png](https://static.platzi.com/media/user_upload/1-9a247404-0b98-43d3-bc7e-649e66cad472.jpg)

La base de datos se llama transporte, usaremos su esquema predeterminado public.

El esquema public contiene las siguientes tablas:

* Estación

* Pasajero

* Tren




Y las tablas de relaciones entre cada uno de los elementos anteriores son:

* Trayecto

* Viaje




El esquema relacional entre las tablas corresponde al siguiente diagrama:

![2.png](https://static.platzi.com/media/user_upload/2-3d80d1c7-2ea2-475c-b625-c11c5b76b9aa.jpg)

**_Estación_**  
Contiene la información de las estaciones de nuestro sistema, incluye datos de nombre con tipo de dato texto y dirección con tipo de dato texto, junto con un número de identificación único por estación.

**_Tren_**  
Almacena la información de los trenes de nuestro sistema, cada tren tiene un modelo con tipo de dato texto y una capacidad con tipo de dato numérico que representa la cantidad de personas que puede llevar ese tren, también tiene un ID único por tren.

**_Trayecto_**  
Relaciona los trenes con las estaciones, simula ser las rutas que cada uno de los trenes pueden desarrollar entre las estaciones

**_Pasajero_**  
Es la tabla que contiene la información de las personas que viajan en nuestro sistema de transporte masivo, sus columnas son nombre tipo de dato texto con el nombre completo de la persona, direccion_residencia con tipo de dato texto que indica dónde vive la persona, fecha_nacimiento tipo de dato texto y un ID único tipo de dato numérico para identificar a cada persona.

**_Viaje_**  
Relaciona Trayecto con Pasajero ilustrando la dinámica entre los viajes que realizan las personas, los cuales parten de una estación y se hacen usando un tren.

### Comentarios:

* **joaquin-fontela** (6) [947245](https://platzi.com/comentario/947245/) 

	Pregunta: un trayecto no deberia tener la estacion de inicio y la estacion de fin?

	* **Miguel Anselmo Carbajal Lévano** [947245] (3)

		Pienso lo mismo, tendría mas sentido.

	* **Carlos Arturo Gutierrez Gonzalez** [947245] (2)

		Si debería tenerla tiene mas sentido a que solo contenga la estación de salida

	* **ddragaid** [947245] (1)

		para eso tienes la tabla viaje

	* **joaquin-fontela** [947245] (2)

		@ddragaid la tabla viaje tiene los atributos inicio y fin, pero estos almacenan fechas, no estaciones.

	* **SergioRubiano** [947245] (1)

		Si debería de tenerlas pero el docente solo se esta fijando en lo mas importante que son lo Id, son atributos que se pondrían poner, pero no los veo necesario ya que lo importante es comprender y para poner mas atributos seria extender la bd sin necesidad

	* **JosBryan** [947245] (1)

		a parte de eso siento que lo diseña como sistema de trenes donde salen una ruta siempre es en la misma dirección y las estaciones están localizadas como nodos

* **adriangonw77** (5) [880659](https://platzi.com/comentario/880659/) 

	a esto se le llama normalizar verdad? al echo de dejar las entidades lo mas especifico posible aun utilizando mas tablas dejar la informacion lo mejor explicada posible

	* **david-hv** [880659] (4)

		Así es, son las formas normales que toda base de datos debe tener, se aplican las formas normales 1,2,3,4. entre mas normalices tu base de datos, mejor administrado sera tu BD

	* **Miguel Ángel Muñoz Pozos** [880659] (1)

		Así es pero si requieres reforzar estos conocimientos te recomiendo [Fundamentos de Bases de Datos](https://platzi.com/cursos/bd/)

* **CARLOS ANDRES LAUREANO PARRA** (2) [853808](https://platzi.com/comentario/853808/) 

	cuando es una realcion de muchos a muchos es necesario siempre implementar una tabla intermedia que permita tener una comunicacion entre estas dos?

	* **giovannirugerio** [853808] (1)

		Según lo aprendido, siempre es recomendable solucionar las relaciones muchos a muchos, pero claro, dependerá de la situación y que tan normalizado quieras el diseño.

	* **Luis Miguel Taque Diaz** [853808] (0)

		Hola Si, esto tiene impacto en la consistencia de la información que se almacena y a futuro un costo importante en el procesamiento de las consultas…

* **dbzdavidbaez** (2) [836684](https://platzi.com/comentario/836684/) 

	Entendido.

* **Diego Alonso García Tenorio** (1) [975134](https://platzi.com/comentario/975134/) 
	
	![1.png](https://static.platzi.com/media/user_upload/1-98f3f797-3644-4472-b0c0-557b573560f6.jpg)
	
	Buenos Días.
	
	Saben por qué me aparece este error por favor?  
	Gracias.

	* **Manuel Alejandro Aguilar Téllez Girón** [975134] (1)

		Encontré [esta página](https://www.ionos.com/community/hosting/postgresql/troubleshoot-a-postgresql-could-not-connect-to-server-error/) espero te sirva 😄

	* **Miguel Torres** [975134] (1)

		Quizás no está encendido el server de postgresql

* **Alex Sierra Rodriguez** (1) [845749](https://platzi.com/comentario/845749/) 

	Cuando usar diferentes esquemas? Es decir acá quedó todo en el public pero supongo que también se pueden crear otros

	* **Oz** [845749] (2)

		Un consejo que me ha servido es que cuando los datos no se crucen entre sí, cuando tengas unas tablas que nunca se cruzan con otras, seguramente hacen parte de otra lógica de negocio y las puedes extraer en otro esquema.

# Gestión de la información en bases de datos [4834]

## 0120. Creación de Tablas [24184](https://platzi.com/clases/1480-postgresql/24184-creacion-de-tablas/)

### Descripción:


### Comentarios:

* **Marco Antonio González Arellano** (4) [872141](https://platzi.com/comentario/872141/) 

	Hice las tablas con pgadmin y también con sentencias SQL, aunque es claro de forma gráfica me gusta también comprender lo que pasa detrás y practicarlo.
	``` 
	    CREATETABLE pasajero(
	    	idserial,
	    	nombre charactervarying(100),
	    	direccion_residencia charactervarying,
	    	fecha_nacimiento date,
	    	CONSTRAINT pasajero_pkey PRIMARY KEY (id)
	    )
	    CREATETABLE tren(
	    	idserial,
	    	modelo charactervarying(30),
	    	capacidad integer,
	    	CONSTRAINT tren_pkey PRIMARY KEY (id)
	    )
	    CREATETABLE estacion(
	    	idserial,
	    	nombre charactervarying(30),
	    	direccion charactervarying(100),
	    	CONSTRAINT estacion_pkey PRIMARY KEY (id)
	    )
	    CREATETABLE trayecto(
	    	idserial,
	    	id_tren integer,
	    	id_estacion integer,
	    	CONSTRAINT trayecto_pkey PRIMARY KEY (id),
	    	FOREIGN KEY (id_tren) REFERENCES estacion(id),
	    	FOREIGN KEY (id_estacion) REFERENCES tren(id)
	    )
	    CREATETABLE viaje(
	    	idserial,
	    	id_pasajero integer,
	    	id_trayecto integer,
	    	inicio date,
	    	fin date,
	    	CONSTRAINT viaje_pkey PRIMARY KEY (id),
	    	FOREIGN KEY (id_pasajero) REFERENCES pasajero (id),
	    	FOREIGN KEY (id_trayecto) REFERENCES trayecto (id)
	    )
	    
	```

	* **andoni** [872141] (2)

		Creo que te equivocaste en tu referencia en las llaves foráneas, id_tren debería estar referenciando a tren(id) y tienes ambas al revés

	* **Marco Antonio González Arellano** [872141] (1)

		Cierto, muchas gracias. Debido a esto tenía problemas en las clases posteriores, y tuve que regresar a estas clases y hacer de nuevo la estructura de la BD. Afortunadamente se arregló y ya pude terminar el curso con éxito. Muchas gracias de nuevo!

	* **David Rueda** [872141] (1)

		Código de creación de tablas:
		``` 
		    CREATETABLE estacion(
		    idserial,
		    nombre varchar(100),
		    direccion varchar(100)
		    );
		    
		    CREATETABLE persona(
		    idserial,
		    nombre varchar(100),
		    direccion varchar(100),
		    fnacimiento date
		    );
		    
		    CREATETABLE tren(
		    idserial,
		    nombre varchar(100),
		    capacidad integer
		    );
		    
		    CREATETABLE viaje (
		    idserial,
		    id_pasajero integer,
		    id_trayecto integer);
		    
		    CREATETABLE trayecto(
		    idserial,
		    id_tren integer,
		    id_estacion integer 
		    );
		    
		```
		
		Creación de llaves primarias:
		``` 
		    ALTERTABLE estacion ADDCONSTRAINT estacion_pkey PRIMARY KEY (id);
		    ALTERTABLE persona ADDCONSTRAINT persona_pkey PRIMARY KEY (id);
		    ALTERTABLE tren ADDCONSTRAINT tren_pkey PRIMARY KEY (id);
		    ALTERTABLE viaje ADDCONSTRAINT viaje_pkey PRIMARY KEY (id);
		    ALTERTABLE trayecto ADDCONSTRAINT trayecto_pkey PRIMARY KEY (id);
		    
		```

	* **Daniel .** [872141] (1)

		Gracias héroe sin capa 👍

* **gorydev** (3) [847297](https://platzi.com/comentario/847297/) 

	les dejo un código para crear el resto de las tablas:
	``` 
	    createtablepublic.estacion (
	    	idserialnotnull,
	    	nombre varcharnotnull,
	    	direccion varcharnotnull,
	    );
	    
	    CREATETABLEpublic.tren (
	    	idserialnotNULL,
	    	modelo varcharNULL,
	    	capacidad intnull,
	    	constraint tren_pk primary key (id)
	    );
	    
	    CREATETABLEpublic.trayecto (
	    	idserialnotNULL,
	    	id_estacion integernotNULL,
	    	id_tren integernotnull,
	    	namevarcharnull,
	    	constraint trayecto_pk primary key (id),
	    	constraint estacion_fk foreign key (id_estacion) referencespublic.estacion,
	    	constraint tren_fk foreign key (id_tren) referencespublic.tren
	    );
	    
	    createtablepublic.viaje (
	    	idserialnotnull,
	    	id_pasajero integernotnull,
	    	id_trayecto integernotnull,
	    	inicio timenull,
	    	fin timenull,
	    	constraint viaje_pk primary key (id),
	    	constraint pasajero_fk foreign key (id_pasajero) referencespublic.pasajero,
	    	constraint trayecto_fk foreign key (id_trayecto) referencespublic.trayecto
	    );
	    
	    
	```

* **juanreinag** (2) [1074359](https://platzi.com/comentario/1074359/) 
	
	![Metro1.png](https://static.platzi.com/media/user_upload/Metro1-86841294-1ef3-4792-bf5a-cb3fe7c96078.jpg) ![Metro2.png](https://static.platzi.com/media/user_upload/Metro2-fddb3bf2-d4a4-4869-b418-ffb2a0cdc917.jpg) ![Metro3.png](https://static.platzi.com/media/user_upload/Metro3-1214fb6f-a3e4-4f1b-b2e1-ec7794942912.jpg) ![Estructura1.png](https://static.platzi.com/media/user_upload/Estructura1-fe71926d-5e05-4821-abba-7bde28e036d4.jpg) ![Estructura2.png](https://static.platzi.com/media/user_upload/Estructura2-73c281c3-1d79-4f17-a8ce-e22058b4a21f.jpg)
	
	Este es el código con el que cree la base de datos y también está el arbol de las tablas

* **Angel de Jesus Quintero Pereira** (2) [1029571](https://platzi.com/comentario/1029571/) 

	```
	    -- Database: transporte
	    
	    -- DROP DATABASE transporte;
	    
	    CREATEDATABASE transporte
	        WITH 
	        OWNER = postgres
	        ENCODING = 'UTF8'
	        LC_COLLATE = 'Spanish_Venezuela.1252'
	        LC_CTYPE = 'Spanish_Venezuela.1252'
	        TABLESPACE = pg_default
	        CONNECTIONLIMIT = -1;
	    
	    COMMENT ON DATABASE transporte
	        IS 'Base de dato que se encarga de manejar la el funcionamiento de transporte entre estaciones de trenes.';
	    
	    --Creación de tabla pasajero
	    CREATETABLEpublic.pasajero
	    (
	        idserialNOTNULL,
	        nombre                  charactervarying(100),
	        direccion_residencia    charactervarying,
	        fecha_nacimiento        date,
	    
	        CONSTRAINT pasajero_pkey PRIMARY KEY (id)
	    )
	    WITH (
	        OIDS = FALSE
	    );
	    
	    ALTERTABLEpublic.pasajero
	        OWNER to postgres;
	    
	    
	    
	    --
	    --Creación de tabla tren
	    --
	    CREATETABLEpublic.tren
	    (
	        idserialNOTNULL,
	        modelo charactervarying(50),
	        capacidad integer,
	        CONSTRAINT tren_pkey PRIMARY KEY (id)
	    )
	    WITH (
	        OIDS = FALSE
	    );
	    
	    ALTERTABLEpublic.tren
	        OWNER to postgres;
	    COMMENT ON TABLE public.tren
	        IS 'Registra los datos de tren, esta tabla guarda el modelo y capacidad del tren';
	    
	    
	    --
	    --Creación de tabla estacion
	    --
	    CREATETABLEpublic.estacion
	    (
	        idserialNOTNULL,
	        nombre charactervarying(100),
	        direccion charactervarying,
	        CONSTRAINT estacion_pkey PRIMARY KEY (id)
	    )
	    WITH (
	        OIDS = FALSE
	    );
	    
	    ALTERTABLEpublic.estacion
	        OWNER to postgres;
	    COMMENT ON TABLE public.estacion
	        IS 'Esta tabla registra la información de la estación como: su identificador, nombre, dirección';
	    
	    
	    --
	    -- Creación de la tabla trayecto
	    --
	    CREATETABLEpublic.trayecto
	    (
	        idserialNOTNULL,
	        id_tren integer,
	        id_estacion integer,
	        CONSTRAINT trayecto PRIMARY KEY (id_tren),
	        CONSTRAINT trayecto_tren_fkey FOREIGN KEY (id_tren)
	            REFERENCESpublic.tren (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID,
	        CONSTRAINT trayecto_estacion_fkey FOREIGN KEY (id_estacion)
	            REFERENCESpublic.estacion (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID
	    )
	    WITH (
	        OIDS = FALSE
	    );
	    
	    ALTERTABLEpublic.trayecto
	        OWNER to postgres;
	    COMMENT ON TABLE public.trayecto
	        IS 'Registra los trayectos que pueden hacer los trenes entre estaciones';
	    
	    COMMENT ON CONSTRAINT trayecto_tren_fkey ON public.trayecto
	        IS 'Referencia al  ID de la tabla tren';
	    COMMENT ON CONSTRAINT trayecto_estacion_fkey ON public.trayecto
	        IS 'Referencia al ID de la tabla  estacion';
	    
	    
	    --
	    --Creación de la tabla  viaje
	    --
	    
	    CREATETABLEpublic.viaje
	    (
	        idserialNOTNULL,
	        id_pasajero integer,
	        id_trayecto integer,
	        inicio date,
	        fin date,
	        CONSTRAINT viaje_pkey PRIMARY KEY (id),
	        CONSTRAINT viaje_pasajero_fkey FOREIGN KEY (id_pasajero)
	            REFERENCESpublic.pasajero (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID,
	        CONSTRAINT viaje_trayecto_fkey FOREIGN KEY (id_trayecto)
	            REFERENCESpublic.trayecto (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID
	    )
	    WITH (
	        OIDS = FALSE
	    );
	    
	    ALTERTABLEpublic.viaje
	        OWNER to postgres;
	    COMMENT ON TABLE public.viaje
	        IS 'Esta tabla contiene datos  sobre los viajes que pueden hacer los pasajeros ';
	    
	    COMMENT ON CONSTRAINT viaje_pasajero_fkey ON public.viaje
	        IS 'Este campo hace referencia al  ID de la tabla pasajero';
	    COMMENT ON CONSTRAINT viaje_trayecto_fkey ON public.viaje
	        IS 'Este campo hace referencia al  ID de la tabla trayecto';
	    
	```

* **andoni** (2) [873825](https://platzi.com/comentario/873825/) 

	Falto explicar cómo se puede crear una llave foránea en pgAdmin para poder realizar las relaciones desde ahí :c

	* **david-hv** [873825] (7)

		yo lo hice de esta forma y me funciono
		
		  1. nombre de la tabla  
		![tablename.png](https://static.platzi.com/media/user_upload/tablename-bf896d45-2cc2-4b1e-895a-f56bf55b5fa7.jpg)
		
		  2. agregamos los atributos a nuestra tabla  
		![columns.png](https://static.platzi.com/media/user_upload/columns-2fb301d6-9151-47e9-b510-0bbb82bdf5ee.jpg)
		
		
		
		
		3.agregamos nuestra llave primaria  
		![Contraints-primerykey.png](https://static.platzi.com/media/user_upload/Contraints-primerykey-04ee28ff-0fd6-4592-bfa9-ddc417d0575d.jpg)
		
		  1. agregamos nuestras llaves foraneas para estacion y tren  
		![Contraints-Foreign-key-estacion.png](https://static.platzi.com/media/user_upload/Contraints-Foreign-key-estacion-4d70204c-dd8b-41a3-8ed2-0a7e6ca27ed1.jpg)
		
		![Contraints-Foreign-key-tren.png](https://static.platzi.com/media/user_upload/Contraints-Foreign-key-tren-dbf1f210-9942-400e-8676-ac777740ce66.jpg)
		
		  1. en codigo sql quedaria asi  
		![SQLcode.png](https://static.platzi.com/media/user_upload/SQLcode-8f6b1650-ac16-457b-a5ca-edd34a420376.jpg)
		
		  2. como ultimo paso para corroborar que la tabla este bien relacionada es insertar datos en la tabla estación, y tren, y luego insertamos datos en la tabla trayecto, por ejemplo, lo hice de esta forma:
		
		  3. insertar datos estacion  
		![estacion.png](https://static.platzi.com/media/user_upload/estacion-76b1cfb6-e675-423b-9447-1add611c4f26.jpg)
		
		  4. insertar datos tren  
		![tren.png](https://static.platzi.com/media/user_upload/tren-2a82a7fc-9778-4235-a5fc-780fda896f14.jpg)  
		3.insertar datos trayecto  
		![trayecto.png](https://static.platzi.com/media/user_upload/trayecto-8701e940-8cc0-4721-b003-a6f477a19eae.jpg)
		
		  5. despues de haber insertado datos en nuestras 3 tablas corroboramos que los datos insertados en la tabla trayecto devuelvan los datos correctos que hayamos insertado, entonces realizamos una consulta para corroborar que los datos sean los correctos y ahi comprobaremos que nuestra relación fue realizada con exito  
		![consultatrayecto.png](https://static.platzi.com/media/user_upload/consultatrayecto-66374b15-c729-421e-8091-8d80c23ec395.jpg)  
		y si devuelve lo datos correctos entonces nuestra relacion si esta bien hecha
		
		
		

	* **carlossanchez27** [873825] (1)

		Gracías, capo!

* **dbzdavidbaez** (2) [836715](https://platzi.com/comentario/836715/) 

	Listo. Se creo la base transporte y la tabla pasajero.

* **TUDz** (2) [836378](https://platzi.com/comentario/836378/) 

	Me parece muy interesante que postgres permita insertar fechas con solamente introducir el valor tipo “YYYY-MM-DD”. En otros motores de base de datos es necesario especificar una función con su respectivo valor y máscara.
	
	Por ejemplo: TO_DATE(‘1991-05-25’,‘YYYY-MM-DD’)

* **asanchez2091** (2) [81185](https://platzi.com/comentario/975750/) 
Es recomendable colocar los nombres y las columnas de la tabla en español o en inglés?

	* **Franklin Eduardo Cuesta Solorzano** [81185] (3)

		Es de buena costumbre poner el nombre de **las tabla en ingles y en plural** y el **nombre de las columnas en ingles** , porque en ingles porque así en caso de que tu proyecto sea presentado para alguien de otro país no sera nada difícil de comprenderlo, esto te lo enseñan o te lo recomienda a mas detalle en el curso de **Curso de SQL y MySQL**

* **ORLANDO GOMEZ DIVANTOQUE** (1) [1117289](https://platzi.com/comentario/1117289/) 
	
	![Captura1.JPG](https://static.platzi.com/media/user_upload/Captura1-2dec60f1-2db1-4b6b-850a-343cfb99fe47.jpg)

* **juananquirozf** (1) [1109645](https://platzi.com/comentario/1109645/) 

	Mmm, no sé si me estoy enredando más de lo que debería, pero si la cardinalidad de viaje y trayecto es N a N, entonces se debería tener una tabla intermedia para manejar las relaciones entre estas, por eso hice mi estructura de esta forma:  
	![DB.JPG](https://static.platzi.com/media/user_upload/DB-2eb56c8e-a635-427f-b5be-9c128d1d8c26.jpg)

* **gustavoalbertorestrepopelae** (1) [1064112](https://platzi.com/comentario/1064112/) 

	Cuál es la diferencia en utilizar Serial en vez de UUID

	* **Oz** [1064112] (1)

		Seria es numero secuencial para ese campo en una tabla, UUID es un numero unico para esa columna en TODA la base de datos, son como peras y manzanas, se usan para cosas muy diferentes.

* **Andres Roberto Coello Goyes** (1) [1044799](https://platzi.com/comentario/1044799/) 

	```
	    CREATETABLEpublic.pasajeros
	    (
	        "ID_pasajero"serial,
	        direccion_residencia charactervarying(40),
	        nombre charactervarying(20),
	        fecha_nacimiento date,
	        CONSTRAINT"ID_pasajero" PRIMARY KEY ("ID_pasajero")
	    );
	    
	    ALTERTABLEpublic.pasajeros
	        OWNER to postgres;```
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1027380](https://platzi.com/comentario/1027380/) 

	SELECT current_date; sirve para saber el día que estamos actualmente pero también nos sirve para ver como postgres guarda la fecha en un campo con el tipo de datos Date.

* **Angel de Jesus Quintero Pereira** (1) [1027377](https://platzi.com/comentario/1027377/) 

	Para crear un Script de inserción hacemos clic derecho en la tabla y nos vamos a la opción Scripts y luego seleccionamos el ejemplo de Scripts que necesitamos.

* **Angel de Jesus Quintero Pereira** (1) [1027373](https://platzi.com/comentario/1027373/) 

	Respuesta a que significa ¿WITH (OIDS = FALSE)? Básicamente es un indentificador de obajetos, esto sirve para identificar tuplas de manera única cuando estas son similares. https://stackoverflow.com/questions/5625585/sql-postgres-oids-what-are-they-and-why-are-they-useful

* **Angel de Jesus Quintero Pereira** (1) [1027360](https://platzi.com/comentario/1027360/) 

	En la pestaña SQL siempre veremos la sentencia SQL que genera PgAdmin al crear una base de dato o tabla con la interfaz gráfica.

* **Angel de Jesus Quintero Pereira** (1) [1027351](https://platzi.com/comentario/1027351/) 

	El estándar que usa postgres para nombrar los constraints de tipo primary key es: nombreCampo_pkey

* **Angel de Jesus Quintero Pereira** (1) [1027343](https://platzi.com/comentario/1027343/) 

	En la pestaña constraints se puede crear la llaves primarias, llaves foraneas, check, Unique, Exclude

* **Angel de Jesus Quintero Pereira** (1) [1027338](https://platzi.com/comentario/1027338/) 

	En postgres character varying es equivalente al varchar de MySQL

* **Angel de Jesus Quintero Pereira** (1) [1027334](https://platzi.com/comentario/1027334/) 

	La primera columna que necesita toda tabla es un ID y es buena práctica hacerla de tipo entero y que automáticamente incremente. El tipo de dato SERIAL en postgres es equivalente al AUTO_INCREMENT en MySQL. SERIAL es un integer por defecto.

* **Angel de Jesus Quintero Pereira** (1) [1027325](https://platzi.com/comentario/1027325/) 

	El tipo de dato SERIAL en postgres es equivalente al AUTO_INCREMENT en MySQL

* **Angel de Jesus Quintero Pereira** (1) [1027321](https://platzi.com/comentario/1027321/) 

	Es buena práctica como se vio en los anteriores cursos es importante comenzar a crear las tablas que no tengan llaves foráneas.

* **Angel de Jesus Quintero Pereira** (1) [1027310](https://platzi.com/comentario/1027310/) 

	DROP simplemente nos permite borrar la tabla con toda su información.

* **Angel de Jesus Quintero Pereira** (1) [1027306](https://platzi.com/comentario/1027306/) 

	ALTER sirve para alterar o cambiar la estructura de una tabla incluyendo los CONSTRAINTS, Agregar o quitar columnas, cambiar índices, agregar llaves primarias e incluso agregar roles como propietarios de la tabla

* **Angel de Jesus Quintero Pereira** (1) [1027302](https://platzi.com/comentario/1027302/) 

	CREATE sirve para inicializar la estructura de datos (tabla) y en esta se declara el nombre de la tabla junto con los campos y sus tipos de datos.

* **Angel de Jesus Quintero Pereira** (1) [1027300](https://platzi.com/comentario/1027300/) 

	CREATE sirve para inicializar la estructura de datos y esto será con

* **Angel de Jesus Quintero Pereira** (1) [1027269](https://platzi.com/comentario/1027269/) 

	Las tablas tienen un funcionamiento complejo pero existe un conjunto de acciones u operaciones definidas de acciones que se pueden realizar sobre ella son muy simples y es son: 1.CREATE, 2.ALTER, 3.DROP. Esto se conoce como DATA DEFINITION LENGUAJE.

* **Angel de Jesus Quintero Pereira** (1) [1027259](https://platzi.com/comentario/1027259/) 

	A pesar de que las tablas tienen un funcionamiento complejo, las acciones que puede revisar sobre ella son muy simples y es son: 1.CREATE="crear", 2.ALTER = "alterar", DROP ="Eliminar".

* **Angel de Jesus Quintero Pereira** (1) [1027246](https://platzi.com/comentario/1027246/) 

	Las tablas son el elemento que contienen la información y la estructura en nuestra base de datos.

* **Angelica Landazabal** (1) [1009746](https://platzi.com/comentario/1009746/) 

	```
	    CREATETABLEpublic.pasajero
	    (
	    	idserial,
	    	nombre charactervarying(100),
	    	direccion_residencia charactervarying,
	    	fecha_nacimiento date,
	    	CONSTRAINT pasajero_pkey PRIMARY KEY (id)
	    )
	    WITH (
	    	OIDS = FALSE );
	    ALTERTABLEpublic.pasajero
	    OWNER to postgres;
	    
	    CREATETABLEpublic.tren
	    (
	        idserial,
	        modelo charactervarying(50),
	        capacidad integer,
	        CONSTRAINT tren_pkey PRIMARY KEY (id)
	    )
	    WITH (
	        OIDS = FALSE
	    );
	    ALTERTABLEpublic.tren
	        OWNER to postgres;
	    
	    CREATETABLEpublic.estacion(
	    	idserial,
	    	nombre charactervarying(30),
	    	direccion charactervarying,
	    	CONSTRAINT estacion_pkey PRIMARY KEY (id)
	    )
	    WITH (
	    OIDS = FALSE );
	    ALTERTABLEpublic.estacion
	    OWNER to postgres;
	    
	    CREATETABLEpublic.trayecto(
	    	idserial,
	    	id_tren integer,
	    	id_estacion integer,
	    	CONSTRAINT trayecto_pkey PRIMARY KEY (id),
	    	FOREIGN KEY (id_tren) REFERENCES estacion(id),
	    	FOREIGN KEY (id_estacion) REFERENCES tren(id)
	    )
	    WITH (
	    OIDS = FALSE );
	    ALTERTABLEpublic.trayecto
	    OWNER to postgres;
	    
	    CREATETABLEpublic.viaje(
	    	idserial,
	    	id_pasajero integer,
	    	id_trayecto integer,
	    	inicio date,
	    	fin date,
	    	CONSTRAINT viaje_pkey PRIMARY KEY (id),
	    	FOREIGN KEY (id_pasajero) REFERENCES pasajero (id),
	    	FOREIGN KEY (id_trayecto) REFERENCES trayecto (id)
	    )
	    WITH (
	    OIDS = FALSE );
	    ALTERTABLEpublic.viaje
	    OWNER to postgres;
	    
	```

	* **Albert González Rossell** [1009746] (1)

		Al ennganchar el texto se te han unido palabras

* **Cuellar777** (1) [989673](https://platzi.com/comentario/989673/) 

	 **COMPLETADO**  
	**_este codigo si quieres puedes copiarlo en QUERY EDITOR DE transporte/postgres@MIBDOFI _**
	``` 
	    CREATETABLE pasajero(
	    	idserial,
	    	nombre charactervarying(100),
	    	direccion_residencia charactervarying,
	    	fecha_nacimiento date,
	    	CONSTRAINT pasajero_pkey PRIMARY KEY (id)
	    )
	    WITH (
	    OIDS = FALSE );
	    ALTERTABLEpublic.pasajero
	    OWNER to postgres;
	    
	    CREATETABLE tren(
	    	idserial,
	    	modelo charactervarying(30),
	    	capacidad integer,
	    	CONSTRAINT tren_pkey PRIMARY KEY (id)
	    )
	    WITH (
	    OIDS = FALSE );
	    ALTERTABLEpublic.tren
	    OWNER to postgres;
	    
	    CREATETABLE estacion(
	    	idserial,
	    	nombre charactervarying(30),
	    	direccion charactervarying(100),
	    	CONSTRAINT estacion_pkey PRIMARY KEY (id)
	    )
	    WITH (
	    OIDS = FALSE );
	    ALTERTABLEpublic.estacion
	    OWNER to postgres;
	    
	    CREATETABLE trayecto(
	    	idserial,
	    	id_tren integer,
	    	id_estacion integer,
	    	CONSTRAINT trayecto_pkey PRIMARY KEY (id),
	    	FOREIGN KEY (id_tren) REFERENCES estacion(id),
	    	FOREIGN KEY (id_estacion) REFERENCES tren(id)
	    )
	    WITH (
	    OIDS = FALSE );
	    ALTERTABLEpublic.trayecto
	    OWNER to postgres;
	    
	    CREATETABLE viaje(
	    	idserial,
	    	id_pasajero integer,
	    	id_trayecto integer,
	    	inicio date,
	    	fin date,
	    	CONSTRAINT viaje_pkey PRIMARY KEY (id),
	    	FOREIGN KEY (id_pasajero) REFERENCES pasajero (id),
	    	FOREIGN KEY (id_trayecto) REFERENCES trayecto (id)
	    );
	    
	```

* **Franklin Eduardo Cuesta Solorzano** (1) [982633](https://platzi.com/comentario/982633/) 
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-fa6b9904-d37e-4e00-88cb-e71e8b12e9fd.jpg)
	
	Ya esta!!!

* **asanchez2091** (1) [975917](https://platzi.com/comentario/975917/) 

	Yo le tuve que colocar el id

* **Maxc_Martinez** (1) [968109](https://platzi.com/comentario/968109/) 

	Ya lo complete
	
	![dbTransporte.png](https://static.platzi.com/media/user_upload/dbTransporte-0f46bb8c-0d40-4aed-9869-1e132575ffd2.jpg)

* **jhon Erik calderon Rubiano** (1) [941353](https://platzi.com/comentario/941353/) 

	listo!!!, ya se generaron las tablas![postgres tablas.JPG](https://static.platzi.com/media/user_upload/postgres%20tablas-012ff8b0-be01-44a9-b9b5-b13383a8aac7.jpg)

* **Ramírez Paredes Jhon** (0) [917968](https://platzi.com/comentario/917968/) 

	EN INSERT SCRIP pasaje en fecha se deja en vacio o se adiciona la fecha segun formato??
	
	INSERT INTO public.pasajero(  
	"name, direccion, fecha_nac)  
	VALUES (“Jhon”, “Jr. Palmeras”, “2020-01-11”);

## 0130. Particiones [24171](https://platzi.com/clases/1480-postgresql/24171-particiones/)

### Descripción:


### Comentarios:

* **TUDz** (4) [836441](https://platzi.com/comentario/836441/) 

	Otra de las ventajas de las tablas particionadas es que puedes utilizar la sentencia TRUNCATE, la cual elimina toda la información de una tabla, pero a nivel partición. Es decir, si tienes una tabla con 12 particiones (1 para cada mes del año) y deseas eliminar toda la información del mes de Enero; con la sentencia ALTER TABLE tabla TRUNCATE PARTITION enero; podrías eliminar dicha información sin afectar el resto.

* **TUDz** (4) [836414](https://platzi.com/comentario/836414/) 

	HolaM
	
	¡Comparto mi script de creación de tablas así como una imagen de mi modelo resultante!
	
	1.- Modelo resultante
	
	![Captura de Pantalla 2019-11-24 a la\(s\) 13.21.56.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-11-24%20a%20la%28s%29%2013.21.56-0e6273fd-d1e7-4302-a15e-5d50288baf3e.jpg)
	
	2.- Script de creación de tablas
	``` 
	    /* SE CREA TABLA DE ESTACION */
	    CREATETABLEpublic.estacion(id_estacion    BIGSERIAL PRIMARY KEY,
	                                 nombre         CHARACTERVARYING,
	                                 direccion      CHARACTERVARYING);
	    
	    /* SE CREA TABLA DE TREN */
	    CREATETABLEpublic.tren(id_tren    BIGSERIAL PRIMARY KEY,
	                             modelo     CHARACTERVARYING,
	                             capacidad  INTEGER);
	    
	    /* SE CREA TABLA DE PASAJERO */
	    CREATETABLEpublic.pasajero(id_pasajero BIGSERIAL PRIMARY KEY,
	                                 nombre      CHARACTERVARYING,
	                                 direccion   CHARACTERVARYING,
	                                 fecha       DATE);
	    
	    
	    /* SE CREA TABLA DE TRAYECTO */
	    CREATETABLEpublic.trayecto(id_trayecto    BIGSERIAL PRIMARY KEY,
	                                 id_estacion    BIGINT,
	                                 id_tren        BIGINT,
	                                 nombre         CHARACTERVARYING);
	    
	    /* SE AGREGA LLAVE FORANEA ESTACION-TRAYECTO */
	    ALTERTABLEpublic.trayecto
	        ADDCONSTRAINT estacion_trayecto_FK FOREIGN KEY (id_estacion) REFERENCESpublic.estacion(id_estacion);
	    
	    /* SE AGREGA LLAVE FORANEA TREN-TRAYECTO */
	    ALTERTABLEpublic.trayecto
	        ADDCONSTRAINT tren_trayecto_FK FOREIGN KEY (id_tren)   REFERENCESpublic.tren(id_tren);
	    
	    /* SE CREA TABLA DE VIAJE */
	    CREATETABLEpublic.viaje(id_viaje    BIGSERIAL PRIMARY KEY,
	                              id_pasajero BIGINT,
	                              id_trayecto BIGINT,
	                              inicio      DATE,
	                              fin         DATE);
	    
	    /* SE AGREGA LLAVE FORANEA PASAJERO-VIAJE */
	    ALTERTABLEpublic.viaje
	        ADDCONSTRAINT pasajero_viaje_FK FOREIGN KEY (id_pasajero) REFERENCESpublic.pasajero(id_pasajero);
	    
	    /* SE AGREGA LLAVE FORANEA TRAYECTO-VIAJE */
	    ALTERTABLEpublic.viaje
	        ADDCONSTRAINT trayecto_viaje_FK FOREIGN KEY (id_trayecto) REFERENCESpublic.trayecto(id_trayecto);
	    
	    
	    
	```

	* **Carlos Chavez** [836414] (1)

		Muy bueno su aporte.  
		Me podrá informar con que sofware realizó las tablas de entidades [relación.Se](http://xn--relacin-q0a.Se) ven muy bien

* **Angel de Jesus Quintero Pereira** (2) [1029839](https://platzi.com/comentario/1029839/) 

	Es importante recalcar que en la fecha final de nuestro rango de días el motor de bases de datos excluye el valor de nuestro último día es decir, si el mes termina en 31 entonces en nuestro rango debe terminar en 32

* **Antonio Rafael González Ferrer** (2) [979788](https://platzi.com/comentario/979788/) 

	Ese color rojo me causa un tremendo conflicto interno … 😅

* **Jaime Andrés Martínez Rodríguez** (2) [931390](https://platzi.com/comentario/931390/) 

	No pude poner en practica esta clase, espero no sea tan fundamental, por ningun sitio me aparecio la opcion de particion al crear una tabla, sea una tabla nueva o vieja no aparece.

	* **Ldelgado1987** [931390] (1)

		Hice la misma pregunta hace unas semanas, he estado atorado en esta clase, no me gustaria avanzar sin conocer esta opcion 😦

	* **Laura Tristán** [931390] (1)

		Me ocurría lo mismo. Cerré pgadmin y lo volví a abrir y ya me apareció la opción.

	* **Juan Osio** [931390] (1)

		La opción sale en el momento que estas creando la tabla por primera vez

* **Abril Darynka Tapia Sosa** (2) [930869](https://platzi.com/comentario/930869/) 

	 **Creando particiones**  
	![](![Captura2.PNG](https://static.platzi.com/media/user_upload/Captura2-28c2695b-6973-429f-a41e-8998a49ebd2e.jpg)

* **Miguel Ángel Muñoz Pozos** (2) [915377](https://platzi.com/comentario/915377/) 

	Las particiones se usan para optimizar las búsquedas de la información

* **cristianwalteros** (2) [841567](https://platzi.com/comentario/841567/) 

	que interesante el tema de las particiones

* **Ehitel Rodríguez Castro** (2) [841123](https://platzi.com/comentario/841123/) 

	Muy interesante.

* **Deiby Johany Avila Gutierrez** (2) [837808](https://platzi.com/comentario/837808/) 

	En que casos es recomendado usar el particionamiento de tablas?

	* **Oz** [837808] (3)

		En principio debes particionar tablas que tengan un alto movimiento de datos, muchas inserciones y consultas. Pero al final, si el proyecto llega a durar lo suficiente, terminarás con una cantidad enorme de datos que te obligarán a pariticionar casi todas las tablas de tu base de datos.

* **dbzdavidbaez** (2) [837370](https://platzi.com/comentario/837370/) 

	Codigo
	``` 
	    CREATEDATABASE transporte
	        WITH 
	        OWNER = postgres
	        ENCODING = 'UTF8'
	        LC_COLLATE = 'C.UTF-8'
	        LC_CTYPE = 'C.UTF-8'
	        TABLESPACE = pg_default
	        CONNECTIONLIMIT = -1;
	    CREATETABLEpublic.estacion
	    (
	        idintegerNOTNULLDEFAULTnextval('estacion_id_seq'::regclass),
	        nombre charactervarying(100) COLLATE pg_catalog."default",
	        direccion charactervarying(100) COLLATE pg_catalog."default",
	        CONSTRAINT estacion_pkey PRIMARY KEY (id)
	    )
	    WITH (
	        OIDS = FALSE
	    )
	    TABLESPACE pg_default;
	    
	    ALTERTABLEpublic.estacion
	        OWNER to postgres;
	    CREATETABLEpublic.pasajero
	    (
	        idintegerNOTNULLDEFAULTnextval('pasajero_id_seq'::regclass),
	        nombre charactervarying(100) COLLATE pg_catalog."default",
	        direccion_residencia charactervaryingCOLLATE pg_catalog."default",
	        fecha_nacimeinto date,
	        CONSTRAINT pasajero_pkey PRIMARY KEY (id)
	    )
	    WITH (
	        OIDS = FALSE
	    )
	    TABLESPACE pg_default;
	    
	    ALTERTABLEpublic.pasajero
	        OWNER to postgres;
	    CREATETABLEpublic.trayecto
	    (
	        idintegerNOTNULLDEFAULTnextval('trayecto_id_seq'::regclass),
	        id_tren integerNOTNULL,
	        id_estacion integerNOTNULL,
	        CONSTRAINT trayecto_pkey PRIMARY KEY (id),
	        CONSTRAINT trayecto_id_estacion_fkey FOREIGN KEY (id_estacion)
	            REFERENCESpublic.estacion (id) MATCH SIMPLE
	            ONUPDATENOACTION
	            ONDELETENOACTION
	            NOT VALID,
	        CONSTRAINT trayecto_id_tren_fkey FOREIGN KEY (id_tren)
	            REFERENCESpublic.tren (id) MATCH SIMPLE
	            ONUPDATENOACTION
	            ONDELETENOACTION
	            NOT VALID
	    )
	    WITH (
	        OIDS = FALSE
	    )
	    TABLESPACE pg_default;
	    
	    ALTERTABLEpublic.trayecto
	        OWNER to postgres;
	    
	    -- Table: public.tren
	    
	    -- DROP TABLE public.tren;
	    
	    CREATETABLEpublic.tren
	    (
	        idintegerNOTNULLDEFAULTnextval('tren_id_seq'::regclass),
	        modelo charactervarying(50) COLLATE pg_catalog."default",
	        capacidad integer,
	        CONSTRAINT tren_pkey PRIMARY KEY (id)
	    )
	    WITH (
	        OIDS = FALSE
	    )
	    TABLESPACE pg_default;
	    
	    ALTERTABLEpublic.tren
	        OWNER to postgres;
	    
	    CREATETABLEpublic.viaje
	    (
	        idintegerNOTNULLDEFAULTnextval('viaje_id_seq'::regclass),
	        id_pasajero integerNOTNULL,
	        id_trayecto integerNOTNULL,
	        inicio date,
	        fin date,
	        CONSTRAINT viaje_pkey PRIMARY KEY (id),
	        CONSTRAINT viaje_id_pasajero_fkey FOREIGN KEY (id_pasajero)
	            REFERENCESpublic.pasajero (id) MATCH SIMPLE
	            ONUPDATENOACTION
	            ONDELETENOACTION
	            NOT VALID,
	        CONSTRAINT viaje_id_trayecto_fkey FOREIGN KEY (id_trayecto)
	            REFERENCESpublic.trayecto (id) MATCH SIMPLE
	            ONUPDATENOACTION
	            ONDELETENOACTION
	            NOT VALID
	    )
	    WITH (
	        OIDS = FALSE
	    )
	    TABLESPACE pg_default;
	    
	    ALTERTABLEpublic.viaje
	        OWNER to postgres;
	    
	```

* **asanchez2091** (2) [82369](https://platzi.com/comentario/1004133/) 
En que momento puedo decidir particionar una tabla para mi proyecto???

	* **Juan David Castro (Platzi)** [82369] (2)

		Puede ser, por ejemplo, cuando tu aplicación necesita reportes y/o muchas búsquedas, pero la base de datos está tan llena que las consultas son un poco demoradas.
		
		En ese caso, podemos hacer particiones por meses o años, por ejemplo, para que haya menos valores a filtrar.
		
		Lo único a tener en cuenta es que, al momento de hacer una búsqueda, debemos saber más o menos en qué fecha se encuentra el registro que buscamos.

* **miguelangelpglez** (2) [77347](https://platzi.com/comentario/902878/) 
Se inserte o no un registro el serial se incrementa un uno. Por lo que si intento insertar un dato no es valido el serial se icrementa, ...

	* **Enrique Mendoza** [77347] (1)

		Si es correcto ya que el sistema realizo el intento de incertar un valor incremental, esto se resuelve haciendo un punto de guardado y en caso de que truene regresar al punto anterior.
		
		<https://www.postgresql.org/message-id/C40884B22A0E4AAC8278E471EF0AE368@KenIBM>
		``` 
		          SAVEPOINT s; //Es la forma en la que creas un punto de guardado 
		    
		     ROLLBACK TO SAVEPOINT s; // regresas al punto de guardado
		    
		```

* **Carlos Chavez** (1) [1086338](https://platzi.com/comentario/1086338/) 

	Con los comandos SQL puedo crear varias tablas de una vez, o es necesario ir creando tabla por tabla usando pgAdmin4?

	* **Mateo Gonzales Navarrete** [1086338] (1)

		Los comandos SQL son el corazon de todo! Todo lo que se haga en tu base de datos es gracias a los comandos SQL. La interfaz de pgAdmin solo es una ayuda visual y mas automatizada para acelerar este proceso, haciendolo menos tedioso!

* **Frank Sócrates Valencia Pinto** (1) [1037378](https://platzi.com/comentario/1037378/) 

	Excelente ejemplo

* **Angel de Jesus Quintero Pereira** (1) [1029852](https://platzi.com/comentario/1029852/) 

	```
	    --
	    --Crear Tabla partición
	    --
	    CREATETABLEpublic.bitacora
	    (
	        idintegerNOTNULLDEFAULTnextval('bitacora_id_seq'::regclass),
	        id_viaje integer,
	        fecha date
	    ) PARTITIONBYRANGE (fecha) --Indica la columana para la partición
	    WITH (
	        OIDS = FALSE
	    )
	    TABLESPACE pg_default;
	    
	    ALTERTABLEpublic.bitacora
	        OWNER to postgres;
	    COMMENT ON TABLE public.bitacora
	        IS 'Esta es una tabla será una tabla particionada para guardar las fechas por particiones y realizar más eficiente las búsquedas';
	    
	    
	    	
	    CREATETABLE bitacora202001 PARTITIONOF bitacora
	    FORVALUESFROM ('2020-01-01') TO ('2020-01-31');
	    
	    CREATETABLE bitacora202002 PARTITIONOF bitacora
	    FORVALUESFROM ('2020-02-01') TO ('2020-02-28');
	    
	    
	    INSERTINTOpublic.bitacora(
	    	id_viaje, fecha)
	    	VALUES 
	    		(23,'2020-01-30'),
	    		(25,'2020-01-28'),
	    		(1,'2020-02-23'),
	    		(2,'2020-02-27')
	    		;
	    SELECT * FROM bitacora;
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1029849](https://platzi.com/comentario/1029849/) 

	La tabla particionada tiene un id pero no es primary key, ya que realmente estas hacen referencias a las tablas que si tienen las llaves primarias.

* **Angel de Jesus Quintero Pereira** (1) [1029842](https://platzi.com/comentario/1029842/) 

	Creación de rango CREATE TABLE bitacora202001 PARTITION OF bitacora FOR VALUES FROM ('2020-01-01') TO ('2020-01-32');

* **Angel de Jesus Quintero Pereira** (1) [1029803](https://platzi.com/comentario/1029803/) 

	RANGE: es una función para realizar rangos dinámicos sí estamos haciendo programación funcional.

* **Angel de Jesus Quintero Pereira** (1) [1029702](https://platzi.com/comentario/1029702/) 

	Ventajas en general: -Evita que la tabla se bloque por constantes consultas y modificaciones. -Proceso de búsqueda e inserción es más eficiente.

* **Angel de Jesus Quintero Pereira** (1) [1029698](https://platzi.com/comentario/1029698/) 

	¿Cómo funciona una consulta? Sí se consulta sobre algún mes en específico en una tabla particionada en rangos de fechas entonces se dirige automáticamente a la partición que tiene el mes que deseamos consultar

* **Angel de Jesus Quintero Pereira** (1) [1029688](https://platzi.com/comentario/1029688/) 

	La tabla se divide internamente en pequeñas partes o tablas en rangos o listas definido, que pueden ser: fechas u objetos. Existen dos tipos de particiones Particionamiento de rango (Range Partitioning) y Particionamiento de lista (List Partitioning)

* **Angel de Jesus Quintero Pereira** (1) [1029677](https://platzi.com/comentario/1029677/) 

	Las particiones consisten en: 1.Separación Física esto es guardar varias partes de la misma tabla en diferentes espacios de disco e incluso en otros discos; 2.Conservar la Estructura Lógica esto es que se puede hacer el el SELECT de la misma forma como se hacía anteriormente.

* **Angel de Jesus Quintero Pereira** (1) [1029668](https://platzi.com/comentario/1029668/) 

	La información de una tabla consultada corresponde a un espacio físico de memoria en del servidor. Como se dijo anteriormente una los factores que se le puede atribuir realizar el aplicar el criterio de partición a una tabla es que la data de la tabla exceda la memoria del SERVE

* **Angel de Jesus Quintero Pereira** (1) [1029663](https://platzi.com/comentario/1029663/) 

	Normalmente valdrán la pena solo cuando una tabla sería muy grande. El punto exacto en el que una tabla se beneficiará de la partición depende de la aplicación, aunque una regla general es que el tamaño de la tabla debe exceder la memoria física del servidor de la base de dato

* **Angel de Jesus Quintero Pereira** (1) [1029653](https://platzi.com/comentario/1029653/) 

	h

* **Angel de Jesus Quintero Pereira** (1) [1029634](https://platzi.com/comentario/1029634/) 

	En ocasiones llega un punto en el que tienes mucha información en una sola tabla y el Particionamiento es la mejor opción. La partición se refiere a dividir lo que es lógicamente una tabla grande en piezas físicas más pequeñas.

* **Didier Zúñiga** (1) [1020906](https://platzi.com/comentario/1020906/) 

	No entendí algo donde se hacen las particiones y se crea el rango, en el video el profe colocó FROM (‘2010-01-01’) TO (‘2019-01-31’)
	
	Habia dicho que por año, pensé que sería algo como:  
	FROM (‘2010-01-01’) TO (‘2010-12-31’)
	
	Pero cuando el hace la prueba de una segunda inserción con año 2012, esta arroja error, no se por que?

	* **Peter_g** [1020906] (2)

		Tuvo un error al digitar el año pero en realidad es como lo dijo mas no como lo digito.

	* **Didier Zúñiga** [1020906] (1)

		Si, eso noté haciendo una prueba. Gracias

* **matias-alexander-ibarra-trujil** (1) [1014822](https://platzi.com/comentario/1014822/) 

	me daba error, al aprecer ejecuta todo el codigo como insert esta primero da error y no crea la tabla, lo unico que hice fue hacer los codigos por separado, osea primero hice la parte de CRCEATE ejecute luego puse la parte de INSERT

* **edu1590** (1) [1012751](https://platzi.com/comentario/1012751/) 

	Lo mas resaltante de este punto es conocer el concepto (saber que existe) y los casos de uso.
	
	Considero que al momento de implementarlo, se debe estar muy pendiente de la documentacion

* **Angelica Landazabal** (1) [1009755](https://platzi.com/comentario/1009755/) 

	```
	    CREATETABLEpublic.bitacora_viaje
	    (
	        idserial,
	        id_viaje integer,
	        fecha date
	    ) PARTITIONBYRANGE (fecha) 
	    WITH (
	        OIDS = FALSE
	    );
	    
	    ALTERTABLEpublic.bitacora_viaje
	        OWNER to postgres;
	    
	```

* **Rodolfo Nicacio Ugalde Ochoa** (1) [981596](https://platzi.com/comentario/981596/) 

	Cuando intento crear la particion del segundo mes me muestra lo siguiente
	``` 
	    CREATETABLE vitacora_viaje201002 PARTITIONOF vitacora_viaje
	    FORVALUESFROM ('2010-02-01') TO ('2010-02-29');```
	    error
	    
	    
	    
	```
	
	ERROR: date/time field value out of range: "2010-02-29"  
	LINE 2: FOR VALUES FROM (‘2010-02-01’) TO (‘2010-02-29’);  
	^  
	SQL state: 22008  
	Character: 98```
	
	El mes uno lo hago así.
	``` 
	    CREATETABLE vitacora_viaje201001 PARTITIONOF vitacora_viaje
	    FORVALUESFROM ('2010-01-01') TO ('2010-01-31');```
	    Sugerencias?
	    Saludos.
	    
	    
	    
	```

	* **ehuacachi** [981596] (1)

		El mismo error…! 😭

* **SOFTDYNAMIC** (1) [979607](https://platzi.com/comentario/979607/) 

	INSERT INTO public.trip_binnacle(id_trip, created_at) VALUES (1,‘2010-01-15’);
	
	SELECT * FROM trip_binnacle;
	
	CREATE TABLE trip_binnacle_2010_01 PARTITION OF trip_binnacle  
	FOR VALUES FROM (‘2010-01-01’) TO (‘2010-01-31’);

* **HeartHunter** (1) [941589](https://platzi.com/comentario/941589/) 

	Comenzando

* **ABautistaO15** (1) [926932](https://platzi.com/comentario/926932/) 

	las particiones en Postgres son como a MySQL las Vistas?

	* **Abril Darynka Tapia Sosa** [926932] (1)

		Yo creo que no, las vistas no las puedes más que consultar y como vi, las particiones sirven para hacer inserciones pero por partes. Ejemplo.  
		Tenemos en nuestra oficina(BD) una repisa(tabla) donde guardamos bitácoras(particiones) en las cuales se guardan registros con un rango especifico. Puede ser que la primera bitácora tenga registros de la A a la F y la segunda de la G-L o en otro caso en una bitácora todos los registros del año 2016, en otra los del 2017 y asi sucesivamente.

* **Vicente Fernandez** (1) [919071](https://platzi.com/comentario/919071/) 

	Hola, creo que hay un error en las fechas… La partición debería ser en enero del mismo año 2010… No de 2010 a 2019. De resto todo bien!

* **carlossanchez27** (1) [896700](https://platzi.com/comentario/896700/) 

	Tengo una consulta. ¿Qué semejanzas existen entre las tablas particionadas y las tablas temporales?

	* **miguelangelpglez** [896700] (1)

		Tabla Particiona almacena una parte de la informacion de un mismo schema, tabla temporal lo mismo.  
		Son mas rapidas que si tuvieramos toda la informacion en la misma tabla.

* **Angel Hernandez** (1) [875476](https://platzi.com/comentario/875476/) 

	Como se podria realizar particiones de manera dinamica? Con el metodo visto en el video, seria necesario cada cierto tiempo crear varias particiones para todas las tablas y de esa manera que la data se continue guardando correctamente

* **Marco Antonio González Arellano** (1) [872258](https://platzi.com/comentario/872258/) 

	Wow, qué buena explicación. Había utilizado postgres por muchos años sin entrar a los detalles, es genial lo que estoy aprendiendo en este curso. Gracias!

* **Luis Miguel Taque Diaz** (1) [868913](https://platzi.com/comentario/868913/) 

	Se puede indexar las particiones…
	
	create table bitacora_viaje_20100102 partition of bitacora_viaje  
	for  
	values  
	from (‘2018-01-01’) to (‘2018-01-30’);
	
	create index bt_0102 on bitacora_viaje_20100102 (id_viaje);

* **guillermolamberto** (1) [852003](https://platzi.com/comentario/852003/) 

	Buenas tardes, queria consultarles porque no me aparece la solapa partition cuando intento crear la tabla. es una tabla nueva pero no me aparece

	* **Oz** [852003] (1)

		En la primera pestaña debes seleccionar la opcion que dice “Partitioned Table”, debes tener en cuenta que solo puedes crear tablas particionadas nuevas, una tabla que ya exista y no sea particionada no la puedes particionar, deberas crear una tabla particionada y migrar los datos.

* **JUAN CARLOS PARRA GALAN** (1) [844238](https://platzi.com/comentario/844238/) 

	¿Se pueden utilizar llaves foraneas en una tabla particionada? Seria buena practica si se desea guardar relación.

	* **Oz** [844238] (3)

		Desde la versión 11 puedes tener llaves foraneas en una tabla particionada que DEPENDAN de una tabla NO particionada, pero la tabla particionada NO puede tener columnas que SEAN llaves foraneas de otras tablas.

	* **JUAN CARLOS PARRA GALAN** [844238] (1)

		Excelente… muchas gracias por tu respuesta

	* **JUAN CARLOS PARRA GALAN** [844238] (1)

		Trate de ejecutarlas y da error, a pesar de que estoy en la versión 11.5

* **Santiago Ricci** (1) [839004](https://platzi.com/comentario/839004/) 

	Necesito ayuda. En pgAdmin no aparece el tab de partition. Busque en el archivo postgresql.conf y no encontre nada. En la web de pgAdmin solo aparece que desde la versiómn 10 en adelante esta opción será visible. Mi versión es: PostgreSQL 11.6, compiled by Visual C++ build 1914, 64-bit.  
	![partition.JPG](https://static.platzi.com/media/user_upload/partition-23292354-2112-4854-8dea-b7bd802b27c9.jpg)

	* **Santiago Ricci** [839004] (2)

		Encontre mi error. El tab partition no aparece si la tabla ya fue creada. Creo que si no se crea desde el inicio no se puede crear particiones. Si realmente se puede particionar una vez creada agradezco que compartan esa información.
		
		Saludos

	* **Oz** [839004] (3)

		Si así es, no es posible particionar una tabla ya creada, deberás crear una tabla particionada y mover los datos de la tabla anterior a la nueva. El copiado, si no son muchos datos, se puede hacer con un simple INSERT … FROM … SELECT, si hay muchos datos (millones) se deberá hacer por partes, para no ir a sobrecargar la tabla, usando Limits o Cursores etc.

* **Jose Luis Perez** (1) [837674](https://platzi.com/comentario/837674/) 

	Hubo un pequeño error. Al crear la partición la crea de enero del 2010 a final de enero del 2019

	* **Juan David Castro (Platzi)** [837674] (1)

		Sí. El ejercicio es así tal cual lo hizo el profesor, solo que escribió 2010 en vez de 2019. Pero excepto por eso todo perfecto. 😅👌

* **asanchez2091** (1) [82379](https://platzi.com/comentario/1004251/) 
al querer crear las demás tablas del reto tengo este error: SQL state: 42P17 ¿que puedo hacer?

	* **Erik Ochoa (Platzi)** [82379] (2)

		 **42P17** es un error descrito en la documentación oficial de postgreSQL como “invalid_object_definition”. Algo estás definiendo mal en tu tabla, puede ser muchas cosas, es un error muy general, en alguna otra parte debe venir más especifico.
		
		Puedes apoyarte en los aportes de tu compañeros para ver cómo lo resolvieron.

* **asanchez2091** (1) [82377](https://platzi.com/comentario/1004243/) 
NO puedo crear la tabla particionada de febrero ya que dice que puedo sobre cargar la tabla que se creo en este curso. ¿Cómo hago?

	* **Sergio Ivan Galvis Motoa** [82377] (1)

		Pueda que estés haciendo la primera partición entre 2010 y 2019…
		``` 
		    CREATETABLE bitacora_viaje201001 PARTITIONOF bitacora_viaje
		    FORVALUESFROM ('2010-01-01') TO ('2010-01-31');
		    
		```
		
		Luego si puedes crear el siguiente particionamiento.
		``` 
		    CREATETABLE bitacora_viaje201002 PARTITIONOF bitacora_viaje
		    FORVALUESFROM ('2010-02-01') TO ('2010-02-28');
		    
		```

* **Pacool84** (1) [80127](https://platzi.com/comentario/953055/) 
Es posible particionar tablas que ya cuentan con demasiada informacion? en caso de que fuera asi se sigue el mismo procedimiento?

	* **Juan David Castro (Platzi)** [80127] (1)

		Puedes, por ejemplo, separar las tablas que contienen registros históricos por rangos de tiempo para mejorar la velocidad de tus consultas.

* **Ldelgado1987** (1) [78483](https://platzi.com/comentario/921842/) 
La opcion “Partition” no me aparece en Pgadmin4, intente crear la query manualmente pero la opcion “PARTITION BY RANGE (FECHA)” me marca ...

* **luiseg** (0) [986726](https://platzi.com/comentario/986726/) 

	Genial esta clase, manejo una base de datos masiva en otro motor de base de datos y esto ayudo a optimizar el tiempo en consultas, super importante para acelerar el acceso a los datos.

* **Diego Armando Bravo Sanabria** (0) [851506](https://platzi.com/comentario/851506/) 

	Que tema mas interesante, no tenia conocimiento que existía y llevo ya 1 año largo utilizando postgreSQL, me gustaría saber si así como se hizo por comandos SQL, se puede realizar por la interfaz gráfica, donde estamos creando la tabla mas específicamente en la ventana “CREATE-TABLE”.

* **Alodia Flores Arnao** (0) [80249](https://platzi.com/comentario/955342/) 
Seguí todos los pasos, pero sí pude ingresar un 2012-02-10, por qué? Qué podría haber hecho masl?

	* **Anderson Paul Meza Cando** [80249] (1)

		Creo que copiaste tal cual el query del profesor, puesto que el rango que el puso va desde 2010 hasta el 2019 , por lo que te permitió ingresar un dato del 2012
		``` 
		    CREATETABLE bitacora_viaje201001 PARTITIONOF bitacora_viaje
		    FORVALUESFROM ('2010-01-01') TO ('2019-01-31');
		    
		```

## 0140. Creación de Roles [24172](https://platzi.com/clases/1480-postgresql/24172-creacion-de-roles/)

### Descripción:


### Comentarios:

* **David Rueda** (3) [900233](https://platzi.com/comentario/900233/) 

	En ubuntu y sus derivados para ingresar a un usuario por consola, se debe ingresar:
	``` 
	    psql--host=localhost--dbname=postgres--username=usuario_consulta```
	    
	    
	```

* **dbzdavidbaez** (3) [837903](https://platzi.com/comentario/837903/) 

	La gestion de usuraios es una labor muy importante para la seguridad de la informacion. Es recomendable tener un inventario detallado de los roles y usuarios creados, asi contar con una superficie de vulnerabilidades por accesos otorgados.
	``` 
	    CREATEROLE usuario_consulta;
	    CREATEUSER usuario_consulta;
	    ALTERROLE usuario_consulta WITH LOGIN;
	    ALTERROLE usuario_consulta WITH SUPERUSER;
	    ALTERROLE usuario_consulta WITHPASSWORD'Esta es una contraseña';
	    DROPROLE usuario_consulta;
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.estacion TO usuario_consulta;
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.pasajero TO usuario_consulta;
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.trayecto TO usuario_consulta;
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.tren TO usuario_consulta;
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.viaje TO usuario_consulta;
	    
	```

* **TUDz** (3) [836483](https://platzi.com/comentario/836483/) 

	Los usuarios y sus roles son una parte importante de la seguridad de la base de datos. Con ayuda de los usuarios adicionales y los grants otorgados, se puede determinar el nivel de acceso a ciertos objetos en la base de datos; además, se puede crear procesos de monitoreo (triggers) que permiten crear una bitácora de seguimiento de operaciones de los usuarios. Creando así una relación de: Quien se conecta -desde donde - que consulta.

* **Angel de Jesus Quintero Pereira** (2) [1031047](https://platzi.com/comentario/1031047/) 

	```
	    --//////////////////
	    --13. Roles
	    --/////////////////
	    
	    --Como usar el comando  CREATE ROL
	    \h CREATE ROL  ;
	    
	    --Crear un role
	    CREATEROLE usuario_consulta;
	    -- Consultar los usuarios dentro de la bases de datos;
	    /dg
	    --Modificar Role
	    ALTERROLE  usuario_consulta WITH LOGIN;
	    ALTERROLE  usuario_consulta WITH SUPERUSER;
	    ALTERROLE  usuario_consulta WITHPASSWORD'1234';
	    
	    --Eliminar usuario
	    DROPROLE usuario_consulta;
	    
	    CREATEROLE usuario_consulta WITH
	      LOGIN
	      NOSUPERUSER
	      INHERIT
	      NOCREATEDB
	      NOCREATEROLE
	      NOREPLICATION
	      ENCRYPTED PASSWORD'md57d24e489563fca3e9842fd8407d58dbf';
	    
	    --obtorgar privilegios
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.estacion TO usuario_consulta;
	    
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.pasajero TO usuario_consulta;
	    
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.trayecto TO usuario_consulta;
	    
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.tren TO usuario_consulta;
	    
	    GRANTINSERT, SELECT, UPDATEONTABLEpublic.viaje TO usuario_consulta;
	    
	    
	```

* **Juan Osio** (2) [961751](https://platzi.com/comentario/961751/) 

	**Mi resumen de la clase**  
	  
	Desde sqlshell podemos crear roles, los roles son independiente de la base de datos, el comando para crear un rol es `CREATE ROLE` o `CREATE USER`, después de la versión 9.3 de postgres ambos comandos hacen lo mismo, en este ejemplo usaremos `CREATE ROLE`  
	
	
	Podemos ver todas las características que tiene la sentencia **CREATE ROLE** con `\h CREATE ROL`  
	  
	Bien, creemos un rol que tenga la capacidad de hacer login y le asignaremos una contraseña.  
	Es muy bueno tener 2 roles diferentes, uno podria ser el usuario postgres que me permite crear bases de datos, borrar tablas, etc, y otro que me sirva únicamente para insertar, consultar y crear tablas pero no de eliminar o borrar bases de datos
	``` 
	    CREATE ROLEusuario_consulta;
	    
	```
	
	Al crearlo así, este no tendrá contraseña y va a poseer todas las características predeterminadas de postgres
	
	Si queremos ver todos los usuarios creados lo podemos hacer con el comando **\dg**  
	![1.PNG](https://static.platzi.com/media/user_upload/1-553c8a02-8d29-4cbc-9286-a9c20842ad93.jpg)  
	  
	Ahora queremos que este rol que acabamos de crear tenga acceso a poder acceder a la base de datos, así que vamos a editarlo
	``` 
	    ALTERROLE usuario_consulta WITH LOGIN; --Para que pueda logearse
	    
	```
	
	Y luego le asignamos una contraseña
	``` 
	    ALTERROLE usuario_consulta WITHPASSWORD'nuestraContraseña';
	    
	```
	
	Ahora ya podemos acceder a la consola con este rol  
	![2.PNG](https://static.platzi.com/media/user_upload/2-2dd8704a-c7e0-433c-8a36-9973c452acef.jpg)  
	  
	Con el comando **DROP ROLE** nombre_rol, podemos eliminar roles

* **PaoloTorregrosa** (2) [942210](https://platzi.com/comentario/942210/) 

	Usuarios Linux, a nosotros no nos sale la opcion de configurar el inicio de psql con el usuario todo eso se tiene que hacer a través de este comando
	``` 
	    psql -h <host> -d <basededatos> -U <usuario> -p <port>
	    
	```

* **adriangonw77** (2) [881547](https://platzi.com/comentario/881547/) 

	listo, el curso es muy practico y fluido, me parece muy buena practica dejar, permisos restringidos dependiendo de las necesidades de los usuarios

* **Daniel Mauricio Sanchez Acebedo** (1) [1044589](https://platzi.com/comentario/1044589/) 

	Excelente explicación.

* **Angel de Jesus Quintero Pereira** (1) [1031043](https://platzi.com/comentario/1031043/) 

	En la pestaña Security se pueden asignar etiquetas a los roles para distinguir más fácilmente que roles tienen cierto grado de permisos y se haga más fácil el identificar por etiquetas.

* **Angel de Jesus Quintero Pereira** (1) [1031041](https://platzi.com/comentario/1031041/) 

	En la pestaña Parameters podemos personalizar variables y atributos. Ejemplo podemos limitar la cantidad de memoria que va a usar la base de datos cuando él se conecte Si queremos que sea un usuario que de pronto no tenga el acceso al 100% de la CPU o al 100% la ram

* **Angel de Jesus Quintero Pereira** (1) [1031039](https://platzi.com/comentario/1031039/) 

	En la pestaña Membership sirve para cuando hayamos creado un grupo de permisos y queremos hacer que este rol sea de ese grupo de permisos

* **Angel de Jesus Quintero Pereira** (1) [1031037](https://platzi.com/comentario/1031037/) 

	En la pestaña privilegios van los atributos que llevará el rol, aquí tenemos que tener en cuenta que al dejar la opción de Ingerit right from parent esta opción permite consultar y modificar las tablas de la bd

* **Angel de Jesus Quintero Pereira** (1) [1031034](https://platzi.com/comentario/1031034/) 

	Pestaña Definition se coloca la contraseña y también se puede agregar una fecha de expiración de la cuenta o también un limite de conexión.

* **Angel de Jesus Quintero Pereira** (1) [1031033](https://platzi.com/comentario/1031033/) 

	En la Pestaña General tenemos el campo name dónde el nombre del rol y podemos colocar un comentario.

* **Angel de Jesus Quintero Pereira** (1) [1031032](https://platzi.com/comentario/1031032/) 

	Para crear un rol, realizamos clic derecho en la opción Login/Group Roles-> Create-> Login Role

* **Angel de Jesus Quintero Pereira** (1) [1031031](https://platzi.com/comentario/1031031/) 

	Para crear un rol, realizamos clic derecho en la opción Login/Group Roles... Luego de ello

* **Angel de Jesus Quintero Pereira** (1) [1030976](https://platzi.com/comentario/1030976/) 

	ALTER ROLE name_rol WITH atributo_name, para la modificación de un rol

* **Angel de Jesus Quintero Pereira** (1) [1030974](https://platzi.com/comentario/1030974/) 

	CREATE USER es un alias de CREATE ROL. Algo más para agregar para verificar sí un usuario a sido creado podemos utilizar la instrucción: \dg

* **Angel de Jesus Quintero Pereira** (1) [1030971](https://platzi.com/comentario/1030971/) 

	\h CREATE ROLE, para ver como usar el comando.

* **Angel de Jesus Quintero Pereira** (1) [1030951](https://platzi.com/comentario/1030951/) 

	Se puede crear los roles independiente a las bases de datos.

* **Angel de Jesus Quintero Pereira** (1) [1030948](https://platzi.com/comentario/1030948/) 

	Es una buena práctica crear un rol que tenga los privilegios CREATEDB y CREATEROLE, pero que no sea un superusuario,y luego usar este rol para toda la administración de rutina de bases de datos y roles. Este enfoque evita los peligros de operar como superusuario cuando no se deba

* **Angel de Jesus Quintero Pereira** (1) [1030946](https://platzi.com/comentario/1030946/) 

	Para arrancar el sistema de base de datos, un sistema recién inicializado siempre contiene un rol predefinido. Este rol es siempre un "superusuario" y, de manera predeterminada (a menos que se modifique al ejecutar initdb )

* **Angel de Jesus Quintero Pereira** (1) [1030943](https://platzi.com/comentario/1030943/) 

	Los roles pueden ser agrupados en un conjuntos de privilegios o permisos.

* **Angel de Jesus Quintero Pereira** (1) [1030942](https://platzi.com/comentario/1030942/) 

	Algunos de los atributos: SUPERUSER|CREATE ROLE|DROP ROLE|PASSWORD|DATABASE CREATION

* **Angel de Jesus Quintero Pereira** (1) [1030936](https://platzi.com/comentario/1030936/) 

	Algunos de los privilegios de los roles son: SELECT | INSERT | UPDATE | DELETE | RULE | REFERENCES | TRIGGER

* **Angel de Jesus Quintero Pereira** (1) [1030930](https://platzi.com/comentario/1030930/) 

	Cada conexión al servidor de la base de datos se realiza en nombre de algún rol en particular, y este rol determina los privilegios de acceso inicial para los comandos emitidos en esa conexión

* **Angel de Jesus Quintero Pereira** (1) [1030929](https://platzi.com/comentario/1030929/) 

	Los roles tienen atributos y privilegios; los atributos se pueden ver como ¿Cuál usuario se está conectando a la bases de datos? y los atributos se pueden visualizar como ¿Cuáles acciones pueden ejecutar el rol que se está conectando?

* **Angel de Jesus Quintero Pereira** (1) [1030927](https://platzi.com/comentario/1030927/) 

	Los roles de la base de datos están conceptualmente completamente separados de los usuarios del sistema operativo. En la práctica, puede ser conveniente mantener una correspondencia, pero esto no es obligatorio

* **Angel de Jesus Quintero Pereira** (1) [1030924](https://platzi.com/comentario/1030924/) 

	Los roles tienen atributos y privilegios;

* **Angel de Jesus Quintero Pereira** (1) [1030839](https://platzi.com/comentario/1030839/) 

	PostgreSQL gestiona los permisos de acceso a la base de datos utilizando el concepto de roles (roles) . Un rol puede considerarse como un usuario de la base de datos o un grupo de usuarios de la base de datos

* **Carlos Chavez** (1) [1024300](https://platzi.com/comentario/1024300/) 

	se pierde visibilidad de Pgadmin con el resaltado en [rojo.Es](http://rojo.Es) difícil leer, lo cual no es buen aspecto pedagógico

* **SOFTDYNAMIC** (1) [979635](https://platzi.com/comentario/979635/) 

	CREATE ROLE login_user; : create new user/role  
	\dg : list users/roles

* **GersonPc** (1) [970070](https://platzi.com/comentario/970070/) 

	Si creo un usuario con todos los permisos, ¿Podria borrar el usuario postgres?

	* **Diego Alexander Forero Higuera (Platzi)** [970070] (1)

		Lo mejor es no borrar este usuario solo cambiarle la contraseña y ponerle una contraseña muy segura.

* **Carlos Chavez** (1) [83314](https://platzi.com/comentario/1024296/) 
Que atributos tiene un usuario superuser?

	* **Diego Alexander Forero Higuera (Platzi)** [83314] (2)

		Literalmente tiene todos los permisos y privilegios para hacer cualquier acción dentro PostgreSQL

* **Christian Aguilar** (1) [77728](https://platzi.com/comentario/908709/) 
Por qué al loggearse con el nuevo role (usuario_consulta) aparece como si estuviera con el role postgres?

	* **Vicente Fernandez** [77728] (1)

		Hola, creo que lo que te indica SQL Shell es la base de datos que esta seleccionada. No el usuario con el que estas accediendo.

## 0150. Llaves foráneas [24173](https://platzi.com/clases/1480-postgresql/24173-llaves-foraneas/)

### Descripción:


### Comentarios:

* **joaquin-fontela** (6) [952654](https://platzi.com/comentario/952654/) 

	Ya habia aplicado las FK por mi cuenta al momento de crear las tablas, pero de igual manera aprendi un par de tips que no habia tenido en cuenta.

* **dbzdavidbaez** (3) [837942](https://platzi.com/comentario/837942/) 

	Hay que tener bastante cuidado con el borrado y la actualizacion en cascada, esto podria generar cuellos de botella en el rendimento del aplicativo cuando se modifica la llave y borrar informacion puede ser una opcion devastadora para la integridad de la informacion.
	``` 
	    ALTERTABLEpublic.trayecto
	        ADD FOREIGN KEY (id_estacion)
	        REFERENCESpublic.estacion (id) MATCH SIMPLE
	        ONUPDATECASCADE
	        ONDELETECASCADE
	        NOT VALID;
	    ALTERTABLEpublic.trayecto
	        ADD FOREIGN KEY (id_tren)
	        REFERENCESpublic.tren (id) MATCH SIMPLE
	        ONUPDATECASCADE
	        ONDELETECASCADE
	        NOT VALID;
	    
	```

* **Jaime Andrés Martínez Rodríguez** (2) [931436](https://platzi.com/comentario/931436/) 

	Muy buena clase.

* **Marco Antonio González Arellano** (2) [878388](https://platzi.com/comentario/878388/) 

	Vaia, qué interesante clase, esto nunca lo había tomado en cuenta y qué importante es.

* **Didier Zúñiga** (1) [1044818](https://platzi.com/comentario/1044818/) 

	Estoy haciendo otra DB diferente y resulta que al insertar datos y omitiendo el campo foraneo debería arrojar error pero está dejando guardar los datos, ya revisé y la relacion esta bien apuntada. A alguien le ha pasado?

	* **Angel de Jesus Quintero Pereira** [1044818] (1)

		Puede ser, que se deba a que no le marcaste explícitamente a la columna que: no deba aceptar NULL

	* **Didier Zúñiga** [1044818] (1)

		Exacto, no la marqué como NOT NULL, pero en el ejercicio de la clase tampoco se marca como NOT NULL y allí si arroja error al omitir el campo foraneo

* **Angel de Jesus Quintero Pereira** (1) [1031063](https://platzi.com/comentario/1031063/) 

	```
	    --
	    -- Creación de la tabla Viaje
	    --
	    CREATETABLEpublic.viaje
	    (
	        idserialNOTNULL,
	        id_pasajero integer,
	        id_trayecto integer,
	        inicio date,
	        fin date,
	        CONSTRAINT viaje_pkey PRIMARY KEY (id),
	        CONSTRAINT viaje_pasajero_fkey FOREIGN KEY (id_pasajero)
	            REFERENCESpublic.pasajero (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID,
	        CONSTRAINT viaje_trayecto_fkey FOREIGN KEY (id_trayecto)
	            REFERENCESpublic.trayecto (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID
	    )
	    WITH (
	        OIDS = FALSE
	    );
	    
	    ALTERTABLEpublic.viaje
	        OWNER to postgres;
	    COMMENT ON TABLE public.viaje
	        IS 'Esta tabla contiene datos  sobre los viajes que pueden hacer los pasajeros ';
	    
	    COMMENT ON CONSTRAINT viaje_pasajero_fkey ON public.viaje
	        IS 'Este campo hace referencia al  ID de la tabla pasajero';
	    COMMENT ON CONSTRAINT viaje_trayecto_fkey ON public.viaje
	        IS 'Este campo hace referencia al  ID de la tabla trayecto';
	    
	    --
	    -- Creación de la tabla trayecto
	    --
	    CREATETABLEpublic.trayecto
	    (
	        idserialNOTNULL,
	        id_tren integer,
	        id_estacion integer,
	        CONSTRAINT trayecto PRIMARY KEY (id_tren),
	        CONSTRAINT trayecto_tren_fkey FOREIGN KEY (id_tren)
	            REFERENCESpublic.tren (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID,
	        CONSTRAINT trayecto_estacion_fkey FOREIGN KEY (id_estacion)
	            REFERENCESpublic.estacion (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID
	    )
	    WITH (
	        OIDS = FALSE
	    );
	    
	    ALTERTABLEpublic.trayecto
	        OWNER to postgres;
	    COMMENT ON TABLE public.trayecto
	        IS 'Registra los trayectos que pueden hacer los trenes entre estaciones';
	    
	    COMMENT ON CONSTRAINT trayecto_tren_fkey ON public.trayecto
	        IS 'Referencia al  ID de la tabla tren';
	    COMMENT ON CONSTRAINT trayecto_estacion_fkey ON public.trayecto
	        IS 'Referencia al ID de la tabla  estacion';
	    
	    --Como  agregar constrains manualmente
	       ALTERTABLE trayecto ADDCONSTRAINT trayecto_tren_fkey FOREIGN KEY (id_tren)
	            REFERENCESpublic.tren (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID,
	        ALTERTABLE trayecto ADDCONSTRAINT trayecto_estacion_fkey FOREIGN KEY (id_estacion)
	            REFERENCESpublic.estacion (id) MATCH SIMPLE
	            ONUPDATECASCADE
	            ONDELETECASCADE
	            NOT VALID
	    
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1031059](https://platzi.com/comentario/1031059/) 

	En la pestaña Action de los contraints es una pestaña en donde indicamos la acción a tomar por el motor de la base de dato cuando ocurre una actualización del registro de la tupla referenciada por este campo

* **Angel de Jesus Quintero Pereira** (1) [1031058](https://platzi.com/comentario/1031058/) 

	Opciones de las foreing Keys son: Deferreable (Aplazar validación), Deferred (Apenas se crea se válida), Match Type (SIMPLE=VALOR A VALOR OR FULL=COMPLEJA) , Validated (Iniciamos las tablas con la validación), Auto FK Index (No es un indice de la tabla)

* **Angel de Jesus Quintero Pereira** (1) [1031056](https://platzi.com/comentario/1031056/) 

	En la pestaña Definition de los constraints existen Características (Definitions) especiales al foreing Keys permite hacer una llave foránea sea validada al instante o después.

* **Angel de Jesus Quintero Pereira** (1) [1031052](https://platzi.com/comentario/1031052/) 

	Estructura de las Foreing Keys es = Nombre_Constrains+ Tabla_origen.campo_id_referencia + Tabla_destino.campo_id_referenciado + Acciones.

* **Angel de Jesus Quintero Pereira** (1) [1031051](https://platzi.com/comentario/1031051/) 

	Consistencia: Corresponde al concepto de que los datos tienen una congruencia entre sí tiene que ver la tabla de usuarios, por ejemplo, con la tabla de direcciones.

* **Angel de Jesus Quintero Pereira** (1) [1031050](https://platzi.com/comentario/1031050/) 

	PgSQL cumple el estándar A.C.I.D: Atomicity-Atomicidad, Consistency-Consistencia, Isolation-Aislamiento, Durability-Durabilidad.

* **Didier Zúñiga** (1) [1021199](https://platzi.com/comentario/1021199/) 

	Como saber por ejemplo desde que tabla crear la llave foránea a otra, en el ejemplo desde TRAYECTO se crearon las foráneas a ESTACION y TREN, no sería igual hacerlo por ejemplo desde ESTACION a TRAYECTO y TREN a TRAYECTO?

* **adriangonw77** (1) [881613](https://platzi.com/comentario/881613/) 

	muy buena explicación entendí a la perfección

* **andoni** (1) [874340](https://platzi.com/comentario/874340/) 

	Muy interesante 😮

## 0160. Inserción y consulta  de datos [24174](https://platzi.com/clases/1480-postgresql/24174-insercion-y-consulta-de-datos/)

### Descripción:


### Comentarios:

* **dbzdavidbaez** (8) [838980](https://platzi.com/comentario/838980/) 

	Hay que tener mucho cuidado con las llaves foraneas cuando se deja la opcion de CASCADA cuando se borra o se actualiza. Ayuda a ahorrar tiempo, perr esto puede afectar la transacionalidad en bases grandes.

	* **Edilberto Enrique Medina Rodríguez** [838980] (1)

		y entonces cómo se soluciona?

	* **Mario Uriarte Amaya** [838980] (1)

		Usualmente lo que se hace en produccion es que cuando se borra un objeto lo que realmente se hace es cambiar un flag de estado para saber si lo van a mostrar o no las consultas.  
		Asi que realmente nunca se borra.  
		Y si nunca se borra la cascada deja de servir y es en codigo donde hay que ocuparse que si un registro tipo pasajero se “borra” tmb se “borren” sus viajes .

* **Jorge Santos Vallejos** (7) [900051](https://platzi.com/comentario/900051/) 

	Hay una situación importante sobre las claves foráneas (FK) que se explica en esta clase y me gustaría resaltarla un poco mas:  
	Primeramente recordar del curso de Fundamentos de BD que a las tablas se les llama “independientes” cuando no tienen FK’s. Del mismo modo una tabla es “dependiente” cuando tiene al menos una FK, es decir, son tablas que dependen de tablas independientes.  
	Es importante** al momento de crear tablas e insertar datos en ellas**, empezar siempre por las tablas independientes y una vez terminadas seguir con las dependientes

* **Wilson Marino Pablo Mendez** (2) [957550](https://platzi.com/comentario/957550/) 

	Excelente curso!!

* **aycatalan1995** (2) [956096](https://platzi.com/comentario/956096/) 

	Puedo importar tablas de excel a PostgreSQL?

	* **chatuz1337** [956096] (1)

		ward

	* **ddragaid** [956096] (1)

		si lo puedes hacer con el start builder de postgresql tiene una librería la cual puedes hacer la conexión sin mayor problema. pero si quieres pasar datos del excel a postgres te recomiendo pasar los datos a un archivo csv

* **dennisadrian** (2) [848641](https://platzi.com/comentario/848641/) 

	Configurar una tabla con foreign key en cascada permite que al borrar o actualizar datos en la tabla de origen tambien se borre o actualice los datos en la tabla con el foreign key

* **Angel de Jesus Quintero Pereira** (1) [1033115](https://platzi.com/comentario/1033115/) 

	```
	    --/////////////////
	    --16.Inserción y consulta de datos
	    --////////////////
	    
	    
	    
	    SELECT * FROMpublic.estacion;--si data
	    SELECT * FROMpublic.pasajero;--reto
	    SELECT * FROMpublic.trayecto;--si data
	    SELECT * FROMpublic.tren;--si data
	    SELECT * FROMpublic.viaje;--reto
	    
	    
	    
	    
	    --insert "estacion"
	    INSERTINTOpublic.estacion (nombre,direccion)
	    VALUES 
	        ('Estación Centro','St 1# 12'),
	        ('Estación Norte','St 100# 112')
	    ;
	    
	    --insert "tren"
	    INSERTINTOpublic.tren (capacidad,modelo)
	    VALUES 
	        (100,'Modelo 1'),
	        (100,'Modelo 2')
	    ;
	    
	    --insert "trayecto"
	    INSERTINTOpublic.trayecto (tren,estacion,nombre)
	    VALUES
	        (1,1,'Ruta 1');
	        (2,2,'Ruta 2');
	    ;
	    
	    -- RETO
	    INSERTINTOpublic.pasajero (nombre,fecha_nacimiento,direccion_residencia)
	    VALUES
	        ('José Ordoñez','1987-1-3','St 100# 12'),
	        ('Ángel Quintero','1987-1-12','St 101# 12'),
	        ('Rafel Castillo','1977-1-12','St 102# 12'),
	    ;
	    INSERTINTOpublic.viaje (id_pasajero,id_trayecto,inicio,fin)
	     VALUES
	        (1,1,'2019-01-02','2019-01-02'),
	        (2,1,'2019-01-03','2019-01-03'),
	        (2,2,'2019-01-04','2019-01-04'),
	        (3,2,'2019-01-04','2019-01-04')
	    
	    ;
	    -- Delete sin limit
	    DELETEFROMpublic.estacion WHERE estacion.id  =4;
	    --delete limit
	    DELETEFROMpublic.estacion WHERE estacion.idIN
	         (
	    		SELECTidFROMpublic.estacion 
	    	  		WHERE estacion.idIN(3,4)
	    			ORDERBY  estacion.id  
	    		 	LIMIT2
	    	 )
	    ;
	    
	    -- update sin limit
	    UPDATEpublic.estacion
	    SETid=4, nombre='Estación SUR-OESTE', direccion='St 4# 1'
	    WHERE estacion.id = 4;
	    
	    -- update utilizando limit
	    UPDATEpublic.estacion
	    	SET 
	    		id=4, 
	    		nombre='Estación SUR-OESTE', 
	    		direccion='St 4# 1'
	    	WHEREidIN (
	    		SELECT estacion.idFROMpublic.estacion
	    			WHERE estacion.idin(4)
	    			ORDERBY estacion.id
	    			LIMIT1
	    	)
	    ;
	    
	```
	
	Añadir algo el delete con limit es algo que vi en el curso de mysql sql y es buena práctica limitar la operación por si algo sale mal, pero en el caso de postgres me parece que es algo contra producente ya que para hacerlo con limit hay que hacerlo a través de una subquery

* **Angel de Jesus Quintero Pereira** (1) [1033069](https://platzi.com/comentario/1033069/) 

	Sí sé una acción como: borrar, actualizar en una registro que está en la tabla a y la llave primaria de esa misma se referencia en otra tabla b, y tenemos la opción ON CASCADE está acción actualizará el registro que está relacionado por medio del id

* **Angel de Jesus Quintero Pereira** (1) [1033060](https://platzi.com/comentario/1033060/) 

	Se tiene dos tabla a y b. y tienen los atributos a.id y b.id y b.id_a que referencia al id de la tabla a. Debemos tomar en cuenta que no se pueden insertar id en el registros en la tabla b.id_a que no existan el tabla a.

* **Angel de Jesus Quintero Pereira** (1) [1032022](https://platzi.com/comentario/1032022/) 

	Para modificar un tipo de dato en una columna se debe tomar en cuenta que el motor de B.D nos dejará hacer el cambio por un tipo de dato equivalente. Sí se desea cambiar el tipo de dato por my distinto seguramente se tendrá que hacer un drop column y luego un add column

* **Angel de Jesus Quintero Pereira** (1) [1031859](https://platzi.com/comentario/1031859/) 

	Sí tenemos un ID serial, cuando tengamos insert podemos quitarlo del script insert porque el mismo motor de base de datos se encarga de asignar este número

* **Angel de Jesus Quintero Pereira** (1) [1031847](https://platzi.com/comentario/1031847/) 

	Para realizar un insert en nuestras tablas desde PgAdmin hacemos clic derecho en la tabla->Script->Insert Scritp

* **Angel de Jesus Quintero Pereira** (1) [1031842](https://platzi.com/comentario/1031842/) 

	aqui

* **joaquin-fontela** (1) [953152](https://platzi.com/comentario/953152/) 

	Alguien mas siente que no tiene sentido que un trayecto tenga como atributo una sola estacion? Un trayecto no se deberia componer de una estacion inicial y otra final?

	* **Oz** [953152] (2)

		Si tiene sentido pensar en ése contexto, pero si lo piensas cómo un metro Linear, donde si sales de la estación A siempre llegas a la B y de la B llegas a la C, si tiene sentido que sólo se mencione el origen porque el destino es el mismo. Para el ejemplo está bien pensar en un modelo sencillo de metro.

	* **GersonPc** [953152] (1)

		Es cierto lo que dices, recuerda que es un curso para aprender, y que mejor si tu creas algo mas a lo mostrado en el curso

* **Miguel Ángel Muñoz Pozos** (1) [915500](https://platzi.com/comentario/915500/) 

	la magia del update y delete cascade

* **adriangonw77** (1) [882082](https://platzi.com/comentario/882082/) 

	super bien explicado me, muy bueno le contenido los vídeos son cortos pero se entiende lo que explica

* **Luis Rodrigo Alvarez Herrera** (1) [875384](https://platzi.com/comentario/875384/) 

	Aqui algunas insersiones
	``` 
	    INSERTINTOpublic.pasajero(
	    	nombre, direccion_residencia, fecha_nacimiento)
	    	VALUES ('Alejandro Mota', 'EDO Mex, Cusil V' , '1985-06-26');
	    	select * frompublic.pasajero;```
	    
	```

* **andoni** (1) [874361](https://platzi.com/comentario/874361/) 

	Listo!  
	![c.JPG](https://static.platzi.com/media/user_upload/c-3bd501fc-9d75-454f-853b-8e7b0b9acb55.jpg)

* **Jhon Zuñiga** (1) [860895](https://platzi.com/comentario/860895/) 

	Hay alguna otra herramienta gráfica para hacer queries?
	
	A mi el pgAdmin se me bloquea.

	* **Oz** [860895] (1)

		Hay un cliente de base de datos gratis y muy bueno, DBeaver. te lo recomiendo.

	* **jcruzquintero** [860895] (1)

		Otro cliente para conectarse a postgresql es omnidb <https://omnidb.org/en/>.

* **Cristian3** (1) [847919](https://platzi.com/comentario/847919/) 

	Añadí dos viajeros y les hice su registro de viajes, no tuve ningún problema con actualizar sus datos ni de los datos del viajero ni de Id, de echo cambié todos los datos del viajero y me funcionó de maravilla.

* **aycatalan1995** (1) [80280](https://platzi.com/comentario/956092/) 
Puedo insertar datos de una tabla desde excel, es decir importar tablas de excel a PostgreSQL?

	* **David Rueda** [80280] (1)

		En una consulta rápida no he encontrado una importación directa desde archivos *.xls, *.xlsx a postgreSQL, sin embargo, se hace un paso intermedio que es cambiar el formato a *.csv y luego hacer la importación desde pgadmin.
		
		A continuación, un procedimiento desde platzi:
		
		<https://platzi.com/tutoriales/1480-postgresql/1522-importar-y-exportar-csv-en-postgres/>
		
		Si se quiere el procedimiento en video:
		
		<https://www.youtube.com/watch?v=k50t6WC4jtQ>

## 0170. Inserción masiva de datos [24185](https://platzi.com/clases/1480-postgresql/24185-insercion-masiva-de-datos/)

### Descripción:


### Links:

* [Mockaroo  - Random Data Generator and API Mocking Tool | JSON / CSV / SQL / Excel](https://mockaroo.com)

### Comentarios:

* **Santiago Ricci** (5) [839321](https://platzi.com/comentario/839321/) 

	Con esta configuración cree los datos para la tabla viajes.
	
	![config.JPG](https://static.platzi.com/media/user_upload/config-ba0eba76-c23c-4e15-a202-d8cb4c8e222a.jpg)

* **Wilson Marino Pablo Mendez** (4) [957722](https://platzi.com/comentario/957722/) 

	Los que quieren limpiar las tablas:
	``` 
	    TRUNCATE estacion  CASCADE;
	    TRUNCATE tren  CASCADE;
	    TRUNCATE trayecto  CASCADE;
	    TRUNCATE pasajero  CASCADE;
	    TRUNCATE viaje  CASCADE;
	    
	```
	
	Comenzar el serial desde cero
	``` 
	    TRUNCATETABLE trayecto, viaje, estacion, viaje, pasajero RESTART IDENTITY;
	    
	```

* **Daniel Contreras** (2) [971556](https://platzi.com/comentario/971556/) 

	Wow.  
	En verdad este curso me parece super completo.  
	Los cursos de Fundamentos de Base de datos y PostgreSQL los de Java con Annai me han parecido de los mejores sin olvidar los de Leonidas.
	
	La herramienta para llenar campos en las bases es de lo mejor.

* **Santiago Andres Gelvez Camargo** (2) [956922](https://platzi.com/comentario/956922/) 

	![Postgres_Insercion_masiva.png](https://static.platzi.com/media/user_upload/Postgres_Insercion_masiva-f0c19086-254b-423f-a23f-edf9ee357021.jpg)  
	Excelente esta herramienta, Mockaroo. Solo hay algo que me vuela la cabeza y es que al insertar fechas aleatorias en viaje, un pasajero puede viajar al pasado iniciando, por ejemplo, en 2017 y finalizando en 2012. Alguien si pudo dejar las fechas un poco mas coherentes que lo que tengo?

* **Marco Antonio González Arellano** (2) [878572](https://platzi.com/comentario/878572/) 

	Qué buena herramienta!
	
	![]()

* **Diego D Ascoli Batista** (2) [839753](https://platzi.com/comentario/839753/) 

	Genial la herramienta mockaroo, yo usaría en la tabla viaje el campo inicio y fin como timestamp

* **dbzdavidbaez** (2) [839058](https://platzi.com/comentario/839058/) 

	Una herramienta muy interesante.

* **Angel de Jesus Quintero Pereira** (1) [1035310](https://platzi.com/comentario/1035310/) 

	```
	    --Insert Viaje
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (1, 899, 152, '2005-03-27', '2019-05-11');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (2, 205, 239, '2013-08-27', '2010-07-10');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (3, 773, 169, '2019-07-24', '2012-06-18');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (4, 576, 80, '2017-11-14', '2014-04-15');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (5, 422, 263, '2007-12-04', '2003-11-19');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (6, 308, 168, '2011-09-29', '2007-12-19');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (7, 898, 107, '2009-10-30', '2012-05-28');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (8, 717, 224, '2010-08-02', '2018-05-07');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (9, 320, 135, '2004-03-16', '2016-10-10');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (10, 260, 260, '2013-10-02', '2006-09-08');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (11, 268, 34, '2010-09-11', '2002-03-12');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (12, 209, 276, '2006-06-05', '2004-04-09');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (13, 727, 212, '2008-04-27', '2006-05-22');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (14, 436, 298, '2006-03-16', '2017-06-29');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (15, 154, 31, '2003-11-13', '2010-05-02');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (16, 429, 25, '2006-02-07', '2019-12-22');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (17, 472, 181, '2002-02-10', '2000-07-22');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (18, 902, 222, '2013-08-30', '2000-11-21');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (19, 6, 204, '2007-11-07', '2004-12-06');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (20, 951, 149, '2015-11-04', '2016-02-14');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (21, 555, 187, '2017-01-06', '2019-12-30');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (22, 427, 103, '2012-05-16', '2000-03-21');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (23, 482, 149, '2018-05-31', '2014-08-27');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (24, 419, 199, '2006-01-21', '2019-03-12');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (25, 460, 211, '2019-02-02', '2011-04-11');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (26, 231, 94, '2017-11-14', '2002-11-09');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (27, 255, 246, '2010-12-09', '2019-04-14');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (28, 636, 185, '2007-06-11', '2019-04-25');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (29, 861, 78, '2014-07-29', '2001-12-17');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (30, 236, 80, '2009-10-02', '2015-02-07');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (31, 583, 102, '2015-01-03', '2019-11-19');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (32, 215, 90, '2007-08-01', '2018-12-19');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (33, 409, 128, '2001-07-14', '2002-10-02');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (34, 366, 291, '2010-12-24', '2001-05-02');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (35, 336, 196, '2004-04-22', '2004-01-28');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (36, 672, 288, '2005-10-19', '2002-11-12');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (37, 974, 210, '2011-10-21', '2018-11-29');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (38, 362, 23, '2006-12-05', '2013-05-21');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (39, 349, 210, '2003-02-24', '2005-04-06');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (40, 245, 195, '2019-03-15', '2017-08-13');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (41, 373, 3, '2011-07-25', '2002-02-23');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (42, 452, 13, '2012-03-27', '2012-02-23');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (43, 322, 120, '2007-11-15', '2005-07-05');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (44, 904, 89, '2000-02-08', '2009-11-05');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (45, 14, 169, '2008-12-19', '2000-08-13');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (46, 506, 16, '2008-09-24', '2014-06-22');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (47, 654, 41, '2004-02-01', '2002-12-19');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (48, 624, 270, '2008-09-29', '2012-10-11');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (49, 224, 282, '2005-08-17', '2014-10-16');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (50, 610, 5, '2016-07-17', '2015-09-21');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (51, 398, 83, '2010-09-21', '2005-01-28');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (52, 447, 209, '2004-10-31', '2002-09-17');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (53, 835, 159, '2007-01-12', '2004-11-20');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (54, 232, 262, '2008-03-27', '2011-10-24');
	    insertinto viaje (id, id_pasajero, id_trayecto, inicio, fin) values (55, 759, 297, '2005-0
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1035307](https://platzi.com/comentario/1035307/) 

	Utilizando Custom list para modelos de trenes y capacidad  
	![Captura de pantalla \(98\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2898%29-74639ce6-6c4d-4d7c-a689-6e5fd3989644.jpg)

* **Angel de Jesus Quintero Pereira** (1) [1035274](https://platzi.com/comentario/1035274/) 

	En mockaroo con las opciones Number se puede generar valores aleatorios entre un rango definido. Custom List nos permite crear una lista explicita de texto o números para que nos genera valores de inserción sobre estas misma.

* **Angel de Jesus Quintero Pereira** (1) [1035242](https://platzi.com/comentario/1035242/) 

	SELECT current_date; nos proporciona la fecha actual pero sobre todo nos muestra el formato que es importante.

* **Angel de Jesus Quintero Pereira** (1) [1033137](https://platzi.com/comentario/1033137/) 

	Para generar datos falsos para probar nuestra bases de datos podemos utilizar las siguientes opciones: https://www.generatedata.com/ https://www.mockaroo.com/

	* **asanchez2091** [1033137] (2)

		El link no sierve.

	* **Angel de Jesus Quintero Pereira** [1033137] (1)

		[](https://www.generatedata.com/)  
		[](https://www.mockaroo.com/)

	* **Angel de Jesus Quintero Pereira** [1033137] (1)

		[mockaroo](https://www.mockaroo.com/)  
		[generate-data](https://www.generatedata.com/)

* **JoelNieto** (1) [1026346](https://platzi.com/comentario/1026346/) 

	Listo, así quedo mi inserción de datos en la tabla viajero.  
	![viajero.PNG](https://static.platzi.com/media/user_upload/viajero-83f1609b-8841-4ac7-bb7f-700636d744d1.jpg)

* **franciscolevim** (1) [1020019](https://platzi.com/comentario/1020019/) 
	
	![Captura de pantalla_2020-03-05_01-01-32.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla_2020-03-05_01-01-32-dac89dd0-84d7-4b20-8536-689056fe91bf.jpg)

* **Ricardo Mesa Gallego** (1) [1013333](https://platzi.com/comentario/1013333/) 

	Excelente herramienta Mockaroo, demasiado util.

* **Angelica Landazabal** (1) [1010509](https://platzi.com/comentario/1010509/) 

	```
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (69, 124, '2004/04/29', '2010/10/24');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (36, 119, '2006/04/22', '2009/09/26');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (21, 39, '2013/09/04', '2020/01/24');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (80, 70, '2002/05/06', '2014/12/19');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (71, 70, '2003/07/19', '2012/03/09');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (34, 40, '2018/07/05', '2003/04/19');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (80, 42, '2005/06/23', '2019/10/20');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (96, 74, '2001/03/06', '2009/08/10');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (32, 57, '2012/02/06', '2002/08/31');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (65, 42, '2000/10/26', '2001/10/06');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (81, 66, '2017/09/02', '2009/03/11');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (54, 120, '2016/03/14', '2017/10/06');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (50, 52, '2018/09/01', '2005/11/22');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (67, 94, '2012/08/11', '2017/11/30');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (24, 84, '2015/08/13', '2004/03/12');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (4, 109, '2017/03/02', '2011/09/08');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (87, 79, '2000/06/22', '2006/07/26');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (55, 74, '2009/03/21', '2005/04/03');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (8, 95, '2015/12/02', '2018/05/05');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (75, 93, '2016/12/31', '1999/09/02');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (1, 41, '2014/04/21', '2014/12/11');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (69, 58, '2003/05/20', '2012/01/28');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (34, 65, '2007/11/06', '2015/04/16');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (43, 59, '2002/01/11', '1999/11/17');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (56, 105, '2013/03/11', '1999/12/29');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (84, 134, '2019/07/13', '2003/12/29');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (3, 99, '2016/10/12', '2015/04/08');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (8, 127, '2017/01/28', '1999/12/18');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (77, 122, '2011/07/28', '1999/04/23');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (32, 73, '2019/03/28', '2019/09/16');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (63, 75, '2001/10/31', '2006/05/30');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (55, 59, '2002/06/23', '2005/09/21');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (26, 95, '2018/08/05', '2013/01/03');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (92, 81, '2009/06/30', '2007/12/16');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (78, 137, '2002/05/13', '2002/10/29');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (21, 102, '2015/05/20', '2013/09/24');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (15, 47, '2014/07/31', '2014/07/05');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (12, 122, '2015/11/25', '2010/10/22');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (13, 94, '2015/03/10', '2008/02/27');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (5, 75, '2009/02/25', '2000/07/13');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (28, 87, '2018/03/20', '2003/07/17');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (50, 68, '2006/05/24', '2017/12/14');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (64, 122, '2015/09/06', '2019/01/06');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (6, 123, '2015/01/09', '2015/11/24');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (70, 135, '2015/03/30', '2018/08/04');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (68, 123, '2003/02/25', '2010/06/09');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (83, 59, '2006/09/22', '2011/09/06');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (18, 90, '2019/03/11', '2004/07/18');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (6, 61, '2019/05/10', '2000/03/22');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (45, 74, '2010/12/02', '2013/05/03');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (23, 110, '2005/09/26', '2018/05/14');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (15, 136, '2006/01/21', '2008/05/12');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (95, 40, '2011/12/14', '2002/12/15');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (17, 41, '2017/09/25', '2006/12/23');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (76, 67, '2008/08/22', '2015/07/06');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (42, 87, '2013/10/12', '2018/09/12');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (22, 110, '2000/12/17', '2002/02/28');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (11, 94, '2008/03/04', '2003/07/31');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (3, 123, '2002/11/07', '2007/09/22');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (99, 136, '2001/11/28', '2005/04/28');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (7, 105, '2002/01/21', '2019/03/21');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (6, 83, '2009/06/02', '2005/04/15');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (58, 137, '2011/05/19', '2003/09/21');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (100, 125, '2014/07/11', '2009/01/10');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (95, 63, '2014/10/18', '2003/01/11');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (56, 67, '2015/01/24', '2014/07/17');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (91, 43, '2016/04/16', '2004/09/14');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (26, 133, '2007/03/15', '2004/11/15');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (17, 54, '2000/09/03', '2012/05/20');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (61, 86, '2014/11/13', '2019/04/28');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (31, 66, '2011/01/09', '2018/05/14');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (9, 102, '2012/05/27', '2008/06/29');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (37, 53, '2008/11/08', '2017/09/10');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (42, 50, '2008/02/04', '2016/10/18');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (43, 123, '2016/11/03', '2011/06/28');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (27, 40, '2006/11/26', '2012/02/10');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (91, 108, '2019/11/08', '2006/01/24');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (5, 67, '2011/03/27', '2004/03/31');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (44, 53, '2013/08/09', '2004/05/10');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (94, 121, '2011/12/25', '2016/03/23');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (83, 54, '2006/07/15', '2004/10/06');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (62, 63, '2001/11/09', '2005/02/03');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (54, 38, '2005/07/28', '2000/12/24');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (18, 69, '2002/04/09', '2004/09/08');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (51, 120, '2011/06/03', '2009/09/23');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (26, 53, '2000/05/30', '2013/09/11');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (95, 69, '2019/12/03', '2017/01/16');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (77, 135, '2008/12/07', '2003/06/12');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (61, 98, '2017/02/03', '1999/05/30');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (81, 117, '2009/10/02', '2009/07/06');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (18, 126, '2005/12/08', '2004/10/03');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (96, 72, '2019/12/22', '2010/07/06');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (47, 76, '2018/05/17', '2011/01/28');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (66, 135, '2006/11/01', '2014/02/10');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (93, 41, '2004/02/15', '2007/04/15');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (7, 86, '2006/10/05', '2018/11/21');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (47, 122, '2001/02/15', '2013/12/11');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (84, 93, '2005/03/24', '2004/02/09');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (52, 133, '2010/08/11', '2020/01/27');
	    insertinto viaje (id_pasajero, id_trayecto, inicio, fin) values (29, 97, '2008/09/06', '2004/05/31');
	    
	```

* **Franklin Eduardo Cuesta Solorzano** (1) [984621](https://platzi.com/comentario/984621/) 

	La verdad muy interesante el curso para mi la tabla viaje quedo de la siguiente manera:  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-4534cd0d-06ba-47f8-8431-79ef22139f1c.jpg)

* **SergioRubiano** (1) [979317](https://platzi.com/comentario/979317/) 

	Tanto el curso como el docente son lo máximo, muy buen contenido este es uno de mis favoritos  
	que gran contenido, que calidad en todo

* **Abril Darynka Tapia Sosa** (1) [938263](https://platzi.com/comentario/938263/) 

	![](![Captura3.PNG](https://static.platzi.com/media/user_upload/Captura3-0c9d8758-3598-43c2-8526-c3c154997f0b.jpg)
	
	Así quedo la configuración de los registros de mi tabla viaje

* **DiegoADaza** (1) [912877](https://platzi.com/comentario/912877/) 

	Postgres es muy parecido a SQL server, yo he trabajado toda mi vida con SQL Server, encuentra muchísimas similitudes, quizás en la único que he visto nuevo es su navegación por comando shell

	* **Adrian Castillo Ramírez** [912877] (1)

		Esto es porque ambas son SQL por lo que el protocolo es el mismo o muy parecido en cuanto a consultas. Lo que marca diferencia es el motor y las funciones Propias de la base.

* **adriangonw77** (1) [882088](https://platzi.com/comentario/882088/) 
	
	![tabla viaje.JPG](https://static.platzi.com/media/user_upload/tabla%20viaje-13fa059f-0006-47fb-afde-ddf971c565f3.jpg)

* **adriangonw77** (1) [882087](https://platzi.com/comentario/882087/) 
	
	![Captura.JPG](https://static.platzi.com/media/user_upload/Captura-a51f18cc-2ac8-412f-9c6f-d29fc7f13c26.jpg)

* **Marco Antonio González Arellano** (1) [878573](https://platzi.com/comentario/878573/) 

	[](https://prnt.sc/qejed9)

* **Luis Rodrigo Alvarez Herrera** (1) [875481](https://platzi.com/comentario/875481/) 

	Perfecto, todos los datos insertados

* **monicarodriguezchavarro** (1) [874867](https://platzi.com/comentario/874867/) 

	Esto si es la locura ¡¡¡ Es totalmente nuevo para mi y demasiado útil¡¡¡

* **jaime-pinto-a** (1) [863014](https://platzi.com/comentario/863014/) 

	Se procedió con la carga de informacion solicitada.
	
	![Pruebas.png](https://static.platzi.com/media/user_upload/Pruebas-67d2db66-ef26-4206-b032-b71863c7a4b2.jpg)

* **Cristian3** (1) [847932](https://platzi.com/comentario/847932/) 

	Tuve problemas porque como había cambiado los ids pues algunos registros no existían, solo los autocompleté para que todo estuviera bien y me permitiera correr todo al 100

# Generar consultas avanzadas [4836]

## 0180. Cruzar tablas SQL JOIN [24186](https://platzi.com/clases/1480-postgresql/24186-cruzar-tablas-sql-join/)

### Descripción:


### Links:

* [Fundamentos de Bases de Datos](https://platzi.com/clases/bd/)

* [http://www.postgresqltutorial.com/wp-content/uploads/2018/12/PostgreSQL-Joins.png](http://www.postgresqltutorial.com/wp-content/uploads/2018/12/PostgreSQL-Joins.png)

* [PostgreSQL Joins](http://www.postgresqltutorial.com/postgresql-joins/)

### Comentarios:

* **dbzdavidbaez** (3) [839071](https://platzi.com/comentario/839071/) 

	Consultas
	``` 
	    SELECT * FROM pasajero
	    INNERJOIN viaje ON (viaje.id_pasajero = pasajero.id);
	    
	    SELECT * FROM pasajero
	    LEFTJOIN viaje ON (viaje.id_pasajero = pasajero.id)
	    WHERE viaje.idISNULL;
	    
	```

* **Adrian Castillo Ramírez** (2) [930328](https://platzi.com/comentario/930328/) 

	Left Join funciona de manera optima en la generación de reportes cuando se buscan bugs o errores en la inserción de datos

* **Cristian3** (2) [847940](https://platzi.com/comentario/847940/) 

	El rigth join con trayecto y tren  
	SELECT  
	*  
	FROM  
	trayecto  
	RIGHT JOIN  
	tren  
	ON  
	(trayecto.“Id_tren”=tren.“Id”);
	
	## – FULL OUTER JOIN  
	SELECT  
	*  
	FROM  
	trayecto  
	FULL OUTER JOIN  
	tren  
	ON  
	(trayecto.“Id_tren”=tren.“Id”);
	
	ESTACION Y TRAYECTO  
	–Full outer join  
	SELECT  
	*  
	FROM  
	trayecto  
	FULL OUTER JOIN  
	estacion  
	ON  
	(trayecto.“Id_estacion”=estacion.“Id”);  
	–RIGHT JOIN  
	SELECT  
	*  
	FROM  
	trayecto  
	RIGHT JOIN  
	estacion  
	ON  
	(trayecto.“Id_estacion”=estacion.“Id”);

* **Cristian3** (2) [847939](https://platzi.com/comentario/847939/) 

	Comparto un join de las tablas de estacion, tren y trayecto  
	SELECT  
	trayecto.“Id” as IdTrayecto,  
	trayecto.“Nombre” as Nombre,  
	tren.“Modelo” as tren,  
	tren.“Capacidad” as Capacidad,  
	estacion.“Nombre” as estacion,  
	estacion.“Direccion” as ubicacion  
	FROM  
	trayecto  
	JOIN  
	tren  
	ON  
	(trayecto.“Id_tren”=tren.“Id”)  
	JOIN  
	estacion  
	ON  
	(trayecto.“Id_estacion” = estacion.“Id”)

* **Cristian3** (2) [847937](https://platzi.com/comentario/847937/) 

	En la versión 12 de postgreSQL se usan comillas dobles ( " " ) para los campos, así funciona correctamente el join  
	SELECT  
	*  
	FROM  
	pasajero  
	join  
	viaje  
	ON  
	(viaje.“Id_pasajero”=pasajero.“Id”)

	* **Diego D Ascoli Batista** [847937] (1)

		No es por la versión, las comillas dobles se usan para que el motor respete el campo tal cual está ya sea con mayúsculas, minúsculas o espacios en blancos, porque por defecto el motor de PostgreSQL transforma todo a minúscula.  
		Ejemplo:
		``` 
		    viaje."Este es un campo"
		    viaje.este_es_un_campo
		    
		```

* **juanreinag** (1) [1096640](https://platzi.com/comentario/1096640/) 

	**Estas son las consultas que hice:**
	
	![Joins1.png](https://static.platzi.com/media/user_upload/Joins1-35f20cb0-9c97-4346-845a-04cedc559ddc.jpg) ![Joins2.png](https://static.platzi.com/media/user_upload/Joins2-23ab6a2d-88f2-4a6f-bcfe-360adb722367.jpg)

* **cconde** (1) [1037360](https://platzi.com/comentario/1037360/) 

	con el pgadmin es realmente sencillo hacer las consultas

* **Angel de Jesus Quintero Pereira** (1) [1035484](https://platzi.com/comentario/1035484/) 

	```
	    --¿Cantidad de viajes por estación?
	    SELECT 
	    	e.id, e.nombre, e.direccion, count (v.id_trayecto) AS cantidad_llegadas FROM estacion AS e
	    INNERJOIN  trayecto AS t
	    	ON (e.id = t.id_estacion)
	    INNERJOIN viaje AS v 
	    	ON(v.id_trayecto = t.id)
	    GROUPBY e.id
	    ORDERBY cantidad_llegadas DESC
	    ;
	    
	    --¿Cuáles usuarios hicieron  viajes?
	    SELECT * FROM pasajero
	    INNERJOIN viaje  
	    	ON (viaje.id_pasajero =pasajero.id);
	    
	    
	    --¿Cuáles fueron los  usuarios  no  realizaron viaje?
	    SELECT * FROM pasajero
	    LEFTJOIN viaje
	    	ON (viaje.id_pasajero = pasajero.id)
	    WHERE viaje.id_pasajero ISNULL
	    
	    ;
	    
	    --¿Cuáles  son los trenes (Id ,modelo, capacidad )que no tienen trayecto asignado?
	    SELECT * FROM tren
	    LEFTJOIN  trayecto 
	    	ON (trayecto.id_tren = tren.id)
	    WHERE trayecto.id_tren ISNULL
	    ;
	    
	    SELECT * FROM viaje
	    WHEREEXTRACT (YEARFROM viaje.inicio) ='2019';
	    
	    SELECT * FROM viaje
	    WHERE  viaje.inicio >'2019-01-1'AND  viaje.inicio <'2019-01-31';
	    
	    
	    --¿Cuáles son usauarios viajaron  en el año 2019 y a que estación llegaron?
	    SELECT 
	    	p.idAS identificador, p.nombre AS nombre_pasajero, 
	    	v.inicio AS fecha_viaje, e.nombre  AS nombre_estacion  
	    FROM viaje AS  v
	    INNERJOIN	pasajero AS p 
	    	ON ( p.id = v.id_pasajero  )
	    INNERJOIN trayecto AS t 
	    	ON  (t.id = v.id_trayecto)
	    INNERJOIN estacion AS e
	    	ON (e.id = t.id_estacion)
	    WHEREEXTRACT (YEARFROM v.inicio) ='2019';
	    
	    ;
	    	
	    --¿Cuáles son usauarios tienen reserva   entre la fecha 2019-01-01 y 2019-01-31 y a que estación llegaron?	
	    SELECT 
	    	p.idAS identificador, p.nombre AS nombre_pasajero, 
	    	v.inicio AS fecha_viaje, e.nombre  AS nombre_estacion
	    FROM viaje AS  v
	    INNERJOIN	pasajero AS p 
	    	ON ( p.id = v.id_pasajero  )
	    INNERJOIN trayecto AS t 
	    	ON  (t.id = v.id_trayecto)
	    INNERJOIN estacion AS e
	    	ON (e.id = t.id_estacion)
	    WHERE  v.inicio >'2019-01-01'AND  v.inicio <'2019-01-31'
	    	
	    ;
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1035336](https://platzi.com/comentario/1035336/) 

	Tipos de JOINS: 1.INNER JOINS, 2.LEFT JOINS, 3.RIGHT JOINS, FULL OUTHER

* **Angel de Jesus Quintero Pereira** (1) [1035335](https://platzi.com/comentario/1035335/) 

	Los Joins son básicamente toda la teoría de conjunto aplicada a SQL

* **Angel de Jesus Quintero Pereira** (1) [1035312](https://platzi.com/comentario/1035312/) 

	Joins son toda las teorias de conjuntos implementadas en los joins

* **Ricardo Mesa Gallego** (1) [1013349](https://platzi.com/comentario/1013349/) 

	 **Tipos de Join**
	
	![](https://ingenieriadesoftware.es/wp-content/uploads/2018/07/sqljoin.jpeg)

* **GersonPc** (1) [972477](https://platzi.com/comentario/972477/) 

	Aqui un JOIN simple para ver a los pasajeros cuando iniciaron el viaje y cuando termino
	``` 
	    SELECT p.nombre, v.inicio, v.fin FROM pasajero as p
	    JOIN viaje as v
	    ON (v.id_pasajero = p.id);
	    
	```

* **Wilson Marino Pablo Mendez** (1) [958255](https://platzi.com/comentario/958255/) 

	```
	    SELECT 
	    pasajero.nombre AS pasajero,
	    tren.modelo AS tren,  
	    trayecto.nombre AS trayecto, 
	    estacion.nombre AS estacion,
	    viaje.inicio, 
	    viaje.fin
	    FROM pasajero
	    INNERJOIN viaje
	    ON viaje.id_pasajero = pasajero.id
	    INNERJOIN trayecto
	    ON viaje.id_trayecto = trayecto.id
	    INNERJOIN tren
	    ON trayecto.id_tren = tren.id
	    INNERJOIN estacion
	    ON trayecto.id_estacion = estacion.id;
	    
	```
	
	![inner join.jpg](https://static.platzi.com/media/user_upload/inner%20join-5a513d5b-f533-4676-a5a7-2171dac6055f.jpg)

* **Luis Nilson Palma Campos** (1) [883296](https://platzi.com/comentario/883296/) 

	MUY BIEN EXPLICADO GRACIAS AQUÍ DEJO MI APORTE CON EL INNER JOIN
	
	![Captura de pantalla \(37\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2837%29-6638fe31-a40c-49d5-b97d-979417bdadc4.jpg)

* **Marco Antonio González Arellano** (1) [878581](https://platzi.com/comentario/878581/) 

	![](url)![reto_postgres.PNG](https://static.platzi.com/media/user_upload/reto_postgres-74d9c30b-e6aa-4d65-b379-d391d559b681.jpg)

* **andoni** (1) [875951](https://platzi.com/comentario/875951/) 

	La unión de dos consultas para traer todos los datos, tengan o no relación  
	![d.JPG](https://static.platzi.com/media/user_upload/d-1d36aa67-bd34-4fc6-bfdf-2fb86735784b.jpg)

* **andoni** (1) [875948](https://platzi.com/comentario/875948/) 
	
	![a.JPG](https://static.platzi.com/media/user_upload/a-e5e996b0-18ec-4c98-8dee-1458ae707a3d.jpg)

* **Joel alexander** (1) [79919](https://platzi.com/comentario/949099/) 
Los dos querys siguientes, Arrojarían el mismo resultado? Select * from A Left Join B on A.id = 

	* **Vicente Fernandez** [79919] (1)

		Hola, si, pienso que arrojarían los mismos resultados.

## 0190. Funciones Especiales Principales [24187](https://platzi.com/clases/1480-postgresql/24187-funciones-especiales-principales/)

### Descripción:


### Comentarios:

* **TUDz** (5) [836555](https://platzi.com/comentario/836555/) 

	La función RETURNING es fundamental en la creación y uso de Stored procedure transaccionales. Al momento de insertar información con id autoincremental, con RETURNING podemos obtener dicho valor e insertarlo o referenciarlo en otras tablas.

* **Cristian Fabian Tovar** (3) [985974](https://platzi.com/comentario/985974/) 

	Hasta que por fin le quitó ese color!!! 😄

* **Miguel Ángel Muñoz Pozos** (3) [937007](https://platzi.com/comentario/937007/) 

	Que hermoso ya quiero usar únicamente postgreSQL

* **Jaime Andrés Martínez Rodríguez** (3) [931897](https://platzi.com/comentario/931897/) 

	Mi resumen  
	Existen 4 funciones especiales que nos ayudarán en nuestro día a día estas son
	
	* ON CONFLICT DO: Es una especie de sobre escritura sobre algo que ya este creado “Como un UPDATE”
	
	* RETURNING: Muestra en pantalla el último cambio hecho
	
	* LIKE / ILIKE: Busqueda por similitudes la diferencia entre ambas es que like busca en minusculas y ilike busca mayusculas/minisculas
	
	* IS / IS NOT: comparacion para atributos especiales como el NULL
	
	
	

* **dbzdavidbaez** (2) [839135](https://platzi.com/comentario/839135/) 

	Muy interesante, estas fucniones estan en otros motores como Sql Sever, pero tienen un difenete nombre en algunas ocasiones.
	``` 
	    INSERTINTOpublic.estacion(
	    	id, nombre, direccion)
	    	VALUES (1, 'Estacion Cambio', 'Calle 5 # 68');
	    INSERTINTOpublic.estacion(
	    	id, nombre, direccion)
	    	VALUES (1, 'Estacion Cambio', 'Calle 5 # 68')
	    	ON CONFLICT DONOTHING;
	    INSERTINTOpublic.estacion(
	    	id, nombre, direccion)
	    	VALUES (1, 'Estacion Cambio', 'Calle 5 # 68')
	    	ON CONFLICT (ID) DOUPDATESET nombre = 'Estacion Cambio' , direccion= 'Calle 5 # 68';
	    INSERTINTOpublic.estacion(
	    	nombre, direccion)
	    	VALUES ( 'Estacion Nueve', 'Calle 9 # 99')
	    	RETURNING *;
	    SELECT *
	    FROM pasajero
	    WHERE nombre LIKE'o%';
	    SELECT *
	    FROM pasajero
	    WHERE nombre ILIKE'o%';
	    SELECT *
	    FROM tren
	    WHERE modelo ISNULL;
	    SELECT *
	    FROM tren
	    WHERE modelo ISNOTNULL;
	    
	```

* **juananquirozf** (1) [1110111](https://platzi.com/comentario/1110111/) 

	Gracias por quitar el fondo rojo! 😄

* **Angel de Jesus Quintero Pereira** (1) [1035631](https://platzi.com/comentario/1035631/) 

	```
	    --/////////////////
	    --19.Funciones Especiales Principales
	    --/////////////
	    --ON CONCLICT  DO
	    SELECT * FROM estacion;
	    
	    -- ON CONFLICT DO NOTHING 
	    --Sí el registro existe, no hace nada pero sí  el registro  no existe lo crea
	    INSERTINTOpublic.estacion (id,nombre,direccion) 
	    VALUES (350,'xxx','xxx')
	    ON CONFLICT DONOTHING;
	    
	    SELECT * FROM estacion;
	    
	    -- ON CONFLICT DO UPDATE SET
	    --Sí el registro existe lo actuliza, sí no existe lo crea
	    INSERTINTOpublic.estacion (id,nombre,direccion) 
	    VALUES (350,'xxx','xxx')
	    ON CONFLICT (id) DO 
	    	UPDATESETid = 102 ,nombre = 'San francisco ',direccion = '46 howlang';
	    	
	    SELECT * FROM estacion;
	    
	    
	    --RETUNING 
	    -- RETURNING * | RETURNING name_column
	    --Una vez insertamos el valor este no los devuelve muy útil para no usar un SELECT.
	    INSERTINTOpublic.estacion (nombre,direccion) 
	    VALUES ('New York Station',' 49 Muir Way')
	    RETURNING *
	    
	    
	    --IS/IS NOT
	    --IS/IS NOT, nos permite comparar tipos de datos que no son estándar o son objetos.
	    --NULL es un tipo de dato NO ESTÁNDAR
	    SELECT * FROMpublic.estacion
	    WHERE estacion ISNOTNULL;
	    
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1035535](https://platzi.com/comentario/1035535/) 

	IS/IS NOT, nos permite comparar tipos de datos que no son estándar o son objetos.

* **Angel de Jesus Quintero Pereira** (1) [1035527](https://platzi.com/comentario/1035527/) 

	LIKE/ILIKE nos permite realizar búsquedas al estilo de expresiones regulares dónde podemos probar buscar nombres por un carácter en específico que comience, termine o se encuentre entre una cadena de carácteres.

* **Angel de Jesus Quintero Pereira** (1) [1035518](https://platzi.com/comentario/1035518/) 

	RETURNING, evita realizar una consulta adicional en la base de datos para recopilar los datos CUANDO se realize un INSERT, UPDATE, DELETE, y es especialmente valioso cuando de otro modo sería difícil identificar las filas modificadas de manera confiable.

* **Angel de Jesus Quintero Pereira** (1) [1035514](https://platzi.com/comentario/1035514/) 

	ON CONFLICT DO, permite realizar una actualización en un registro si este se encuentra, sí no se encuentra se insertará, https://www.postgresqltutorial.com/postgresql-upsert/

* **ehuacachi** (1) [1011795](https://platzi.com/comentario/1011795/) 

	… si de pronto está molestado este colo ROJO…

	* **Ricardo Mesa Gallego** [1011795] (1)

		jajajaja, ya me tenia desesperado ese Rojo xD

* **adriangonw77** (1) [889032](https://platzi.com/comentario/889032/) 

	muy buena explicación

* **andoni** (1) [75789](https://platzi.com/comentario/875984/) 
Cual es la diferencia entre usar el ON CONFLICT DO y el UPDATE? Cómo se en qué casos se utiliza el primero?

	* **Juan David Castro (Platzi)** [75789] (1)

		Estos tutoriales te pueden ayudar:
		
		👉 <http://www.postgresqltutorial.com/postgresql-update/>  
		👉 <http://www.postgresqltutorial.com/postgresql-upsert/>

## 0200. Funciones Especiales Avanzadas [24188](https://platzi.com/clases/1480-postgresql/24188-funciones-especiales-avanzadas/)

### Descripción:


### Comentarios:

* **Abril Darynka Tapia Sosa** (5) [938322](https://platzi.com/comentario/938322/) 

	Funciones Especiales avanzadas en PosgreSQL  
	• COALES: compara dos valores y retorna el que es nulo  
	• NULLIF: Retorna null si son iguales  
	• GREATEST: Compara un arreglo y retorna el mayor  
	• LEAST: Compara un arreglo de valores y retorna el menor  
	• BLOQUES ANONIMOS: Ingresa condicionales dentro de una consulta de BD

* **Luis Rodrigo Alvarez Herrera** (5) [883705](https://platzi.com/comentario/883705/) 

	Mi aporte
	``` 
	    SELECTid, nombre, fecha_nacimiento,
	    	CASE
	    	WHEN nombre ILIKE'a%'THEN'Comienza con A' 
	    	WHEN nombre ILIKE'e%'THEN'Comienza con E'
	    	WHEN nombre ILIKE'i%'THEN'Comienza con I'
	    	WHEN ( current_date - fecha_nacimiento) > 6570Then'Es mayor de 18 años'
	    	ELSE'Su nombre no inicia con A, E o I y ademas es un niño'
	    	END
	    FROM pasajero ORDERBY fecha_nacimiento;```
	    
	```

* **dbzdavidbaez** (4) [839309](https://platzi.com/comentario/839309/) 

	Buena explicacion, este es el codigo del video
	``` 
	    SELECT * FROM pasajero WHEREid = 5;
	    UPDATE pasajero SET nombre = NULLWHEREid = 5
	    SELECTCOALESCE(nombre, 'Nombre en Null') AS nombrenull , * FROM pasajero WHEREid = 5;
	    SELECTNULLIF(0,0);
	    SELECTNULLIF(0,1);
	    SELECTGREATEST(5,5,8,95,75,4225,8,6,9,212,6);
	    SELECTLEAST(5,5,8,95,75,4225,8,6,9,212,6);
	    -- Reto
	    SELECTCOALESCE(nombre, 'Nombre en Null') AS nombrenull , *,
	    CASEWHEN fecha_nacimiento > '2015-01-01'THEN
	    'Niño'ELSE'Mayor'END,
	    CASEWHEN nombre ILIKE'D%'THEN
	    'Empieza con D'ELSE'No empieza con D'END, 
	    CaseWHENextract(yearsfrom age(current_timestamp,fecha_nacimiento::timestamp)) >= 18THEN
	    'Mayor de edad.'ELSE'Menor de edad.'END
	    FROM pasajero;
	    
	```

* **Diego Hernandez** (3) [1039388](https://platzi.com/comentario/1039388/) 

	```
	    SELECTid, nombre, direccion_red, fecha_nac,
	    CASE
	    WHEN fecha_nac >= (CURRENT_DATE - INTERVAL'18 years') THEN 
	    'menor de edad'
	    Else
	    'mayor de edad'
	    END
	    	FROMpublic.pasajero
	    	WHERE nombre ILIKE'a%';```
	    
	```

* **adriangonw77** (3) [889071](https://platzi.com/comentario/889071/) 

	lo hice simple pero funciono. ![CasosJPG.JPG](https://static.platzi.com/media/user_upload/CasosJPG-cdb03849-8d8f-4037-b399-0e6369253b7a.jpg)

* **juanreinag** (2) [1104643](https://platzi.com/comentario/1104643/) 

	Esta es mi solución al ejercicio:
	
	![Ejercicio_funciones_av.png](https://static.platzi.com/media/user_upload/Ejercicio_funciones_av-9ff019f1-4a9d-41eb-84df-cfbc58c794d5.jpg) ![Resultado_funciones_av.png](https://static.platzi.com/media/user_upload/Resultado_funciones_av-0b0febe0-f1a1-4da0-9ebc-29e846ffd9a8.jpg)

* **Angel de Jesus Quintero Pereira** (2) [1036087](https://platzi.com/comentario/1036087/) 

	```
	    --Reto listar  cuáles pasajero sus nombres comienzan con la letra 'o' y cuáles de ellos tiene más de 18 años
	    
	    SELECT 
	    	id, nombre, direccion_residencia, fecha_nacimiento, 
	    	CASE
	    		WHEN  nombre ILIKE'o%'THEN
	    			'Si Aplica'
	    		ELSE
	    			'No Aplica'
	    	ENDAS Comienza_con_O,
	    	EXTRACT(yearFROM age(current_date,fecha_nacimiento)) AS edad
	    	
	    FROMpublic.pasajero
	    WHEREEXTRACT(yearFROM age(current_date,fecha_nacimiento)) >=18AND nombre ILIKE'o%' ;
	    
	```

* **Alodia Flores Arnao** (2) [993430](https://platzi.com/comentario/993430/) 

	SELECT id, nombre, direccion, fecha_nacimiento,  
	CASE  
	WHEN nombre ILIKE ‘o%’ THEN  
	’Inicia con O’  
	ELSE  
	’Inicia con otra letra’  
	END AS Inicial,  
	CASE  
	WHEN ((CURRENT_DATE-fecha_nacimiento)/365) >= 18 THEN  
	’Mayor’  
	ELSE  
	’Menor’  
	END AS Edad  
	FROM pasajero;

* **Wilson Marino Pablo Mendez** (2) [963237](https://platzi.com/comentario/963237/) 
	
	![case.jpg](https://static.platzi.com/media/user_upload/case-1f2314b3-e9ab-429a-9286-12164955cab7.jpg)

* **Soycharlie** (2) [961984](https://platzi.com/comentario/961984/) 
	
	![Sin título.png](https://static.platzi.com/media/user_upload/Sin%20t%C3%ADtulo-f4b27a71-f855-4400-906d-c3e7a20fa629.jpg)

* **Luis Nilson Palma Campos** (2) [887396](https://platzi.com/comentario/887396/) 

	YO REALICE UNA CONSULTA PARECIDA AL DEL PROFE SOLO QUE TAMBIÉN MOSTRÉ SU EDAD EN AÑOS Y MESES  
	AQUÍ LES DEJO LA CONSULTA  
	![Captura de pantalla \(40\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2840%29-24b19bb2-cf40-4393-af68-c0ae8e30a9b4.jpg)

* **Marco Antonio González Arellano** (2) [880894](https://platzi.com/comentario/880894/) 

	Gracias por la clase, es genial!
	
	![](![postgres2.png](https://static.platzi.com/media/user_upload/postgres2-dc54586c-ae2e-4c29-9084-9c9ccecef16f.jpg)

* **jaime-pinto-a** (2) [863497](https://platzi.com/comentario/863497/) 

	Practica solicitada en el vídeo:
	
	SELECT  
	id, nombre, direccion_residencia, fecha_nacimiento,  
	CASE WHEN (date_part(‘year’,current_date) - date_part(‘year’,fecha_nacimiento)) >= 18 THEN  
	’Mayor de Edad’  
	ELSE  
	’Menor de Edad’  
	END as Tipo,  
	CASE WHEN upper(nombre) LIKE ‘O%’ THEN  
	’Inicia con O’  
	ELSE  
	’No inicia con O’  
	END as Inicio_O  
	FROM public.pasajero;

* **AlejoE02** (2) [846926](https://platzi.com/comentario/846926/) 

	```
	    selectid, nombre, direccion_residencia, fecha_nacimiento,
	    casewhen nombre ILIKE'd%'then
	    'SI'else'NO'endas Letra_Inicial_D,
	    casewhenextract(yearsfrom age(current_timestamp, fecha_nacimiento::timestamp)) >= 18then
	    'mayor'else'menor'endas Edad
	    frompublic.pasajero;```
	    
	```

* **Adrian Rodrigo Martinez Idiaquez** (1) [1117347](https://platzi.com/comentario/1117347/) 

	select id,nombre,direccion_residencia,fecha_nacimiento,  
	case  
	when nombre ilike ‘o%’ then 'empieza por la O’  
	else  
	’no empieza con la O’  
	end as inicial_o,  
	case  
	when date_part(‘year’, fecha_nacimiento) >17 then  
	’es mayor de edad’  
	else  
	’es menor de edad’  
	end as mayor_menor  
	from pasajero;

* **DonTapas** (1) [1110992](https://platzi.com/comentario/1110992/) 

	Gracias por esta clase!!!
	
	![Screenshot_5.jpg](https://static.platzi.com/media/user_upload/Screenshot_5-506a756a-2658-4de6-83a6-abd58ad17094.jpg)

* **edgarrodgom** (1) [1087551](https://platzi.com/comentario/1087551/) 

	select id,nombre,direccion_residencia,  
	case  
	when DATE_PART(‘year’, current_date::date) - DATE_PART(‘year’,fecha_nacimiento::date) >= 18  
	then 'mayor de edad’  
	else 'menor de edad’  
	end AS EDAD  
	from pasajero  
	where nombre ilike 'p%'  
	group by id

* **Peter_g** (1) [1060711](https://platzi.com/comentario/1060711/) 

	SELECT id, nombre, direccion_residencia, fecha_nacimiento,  
	CASE  
	WHEN fecha_nacimiento < ‘2002-01-01’ THEN  
	’Mayor’  
	ELSE  
	’no aplica’
	
	END AS EDAD  
	FROM public.pasajero
	``` 
	    WHERE nombre ILIKE 'e%';
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1035654](https://platzi.com/comentario/1035654/) 

	BLOQUES ANÓNIMOS, permite tener condicionales pero dentro de una consulta sql

* **Angel de Jesus Quintero Pereira** (1) [1035649](https://platzi.com/comentario/1035649/) 

	GREATEST, LEAST permite comparar un arreglo de valores y retorna en el caso de GREATEST el mayor y en el caso de LEAST el menor

* **Angel de Jesus Quintero Pereira** (1) [1035645](https://platzi.com/comentario/1035645/) 

	NULLIF, te permite comprar dos valores y retorna NULL si son iguales

* **Angel de Jesus Quintero Pereira** (1) [1035643](https://platzi.com/comentario/1035643/) 

	COALESCE, permite comparar dos valores y saber cuál de los dos no son NULL

* **Diego Alonso García Tenorio** (1) [1015444](https://platzi.com/comentario/1015444/) 

	Buenas Tardes.  
	Esta es mi solución.  
	![2.png](https://static.platzi.com/media/user_upload/2-b9cde092-e29e-4ac0-aa38-ab9f5b866dbb.jpg)

* **Joseph Santibáñez** (1) [1008123](https://platzi.com/comentario/1008123/) 

	Lo hice aplicando INTERVAL, ahí va por si le es de ayuda a alguien, saludos
	``` 
	    SELECTid, nombre, direccion_residencia,
	    CASE 
	    WHEN fecha_nacimiento <= (CURRENT_DATE - INTERVAL'18 year') 
	    	THEN'Mayor de edad'ELSE'Menor de edad'
	    END
	    	FROMpublic.pasajero;
	    
	```

* **vegadevh** (1) [995527](https://platzi.com/comentario/995527/) 
	
	![](https://static.platzi.com/media/user_upload/Capture-c5ac9292-fc2f-4db1-968c-219b48a0cf2e.jpg)

* **SOFTDYNAMIC** (1) [986926](https://platzi.com/comentario/986926/) 

	```
	    -- +18
	    SELECT *, date_part('year',age(current_date, birthday)) age
	    FROM passengers 
	    WHERE date_part('year',age(current_date, birthday))>18;
	    
	    -- STARTS WITH O
	    SELECT *, 
	    CASE 
	    WHENnameILIKE'o%'
	    THEN'YES'
	    ELSE'NO'
	    ENDAS"STARTS WITH O"
	    FROM passengers;```
	    
	```

* **Santiago Andres Gelvez Camargo** (1) [957080](https://platzi.com/comentario/957080/) 

	Apoyado en la documentación para el tema de la edad del pasajero, reto cumplido 😎  
	![Query_reto_Favanzadas.png](https://static.platzi.com/media/user_upload/Query_reto_Favanzadas-1b08dd91-86c6-4a92-92f5-b545a593e16f.jpg)

* **Miguel Ángel Muñoz Pozos** (1) [947164](https://platzi.com/comentario/947164/) 

	SELECT *, ((CURRENT_DATE - fecha_nacimiento)/365) AS “Años cumplidos”,  
	(CASE WHEN ((CURRENT_DATE - fecha_nacimiento)/365) >= 18  
	THEN 'SI’  
	ELSE 'NO’  
	END) AS "¿Es mayos de edad?"  
	FROM pasajero  
	WHERE nombre  
	ILIKE ‘o%’;

* **Miguel Ángel Muñoz Pozos** (1) [947081](https://platzi.com/comentario/947081/) 

	Yo no sabia que **CASE WHEN condicion THEN ‘true’ ELSE ‘FALSE’ END** se conocia como BLOQUES ANONIMOS

* **jhon Erik calderon Rubiano** (1) [943455](https://platzi.com/comentario/943455/) 

	COMPARTO EL CODIGO REQUERIDO![PRINT.JPG](https://static.platzi.com/media/user_upload/PRINT-9ae62a8f-6c9a-45dc-825d-46edc816888c.jpg)

* **MaxLandh** (1) [942569](https://platzi.com/comentario/942569/) 

	```
	    SELECT * FROM ( SELECTid, nombre, direccion_residencia, fecha_nacimiento,
	    (CASE
	    WHEN (extract(yearfromcurrent_date) - extract(yearfrom fecha_nacimiento)) >18and nombre LIKE'M%'THEN
	    'SI'
	    ELSE
	    'NO'
	    END) entrada 
	    FROMpublic.pasajero) AS PRUEBA WHERE entrada = 'SI';
	    
	```

* **Abril Darynka Tapia Sosa** (1) [938371](https://platzi.com/comentario/938371/) 

	```
	    CASE
	    WHEN nombre ILIKE 'a%'and (date_part('year',CURRENT_DATE) - date_part('year',fecha_nacimiento)) > 18THEN
	    'cumple'
	    ELSE
	    'no cumple'
	    END
	    FROMpublic.pasajero;```
	```

* **Jhonny Stiven Agudelo Tenorio** (1) [937304](https://platzi.com/comentario/937304/) 

	```
	    SELECT *
	    	,CASE 
	    		WHEN nombre ILIKE'a%'OR nombre ILIKE'p%' 
	    			THEN'nombre con a o p'
	    		ELSE 
	    			'invalido'
	    	ENDAS nombre
	    	,CASE
	    		WHEN (date_part('year',CURRENT_DATE) - date_part('year',fecha_nacimiento)) > 18
	    			THEN'Mayor de edad'
	    		ELSE
	    		 'Menor de edad'
	    	ENDAS edad
	    FROM pasajero 
	     WHERETRUE; 
	    
	    
	```

* **gersonrpq** (1) [935705](https://platzi.com/comentario/935705/) 

	🤓 🚀
	``` 
	    SELECT *,
	    CASE 
	    WHEN nombre LIKE'O%'AND fecha_nacimiento < '2000-01-01'THEN
	    'Es Mayor de edad y empieza por O'
	    WHEN fecha_nacimiento < '2000-01-01'THEN
	    'Es mayor de edad y no empieza por O'
	    ELSE
	    'No es mayor de edad y no empieza por O'
	    END
	    FROMpublic.pasajero;
	    
	```

* **Juliana Ramirez** (1) [908020](https://platzi.com/comentario/908020/) 
	
	![Screenshot at 2020-01-07 17-50-08.png](https://static.platzi.com/media/user_upload/Screenshot%20at%202020-01-07%2017-50-08-70bebc05-ecde-43c4-94f0-8ff35f749ae9.jpg)

* **andoni** (1) [876007](https://platzi.com/comentario/876007/) 

	Puede anidar unos CASE dentro de otros en el ELSE. Es hermoso :’)  
	![p.JPG](https://static.platzi.com/media/user_upload/p-bb517064-98fd-4ff4-9e00-ca2960a4ceec.jpg)

* **Cristian3** (1) [848352](https://platzi.com/comentario/848352/) 

	Les aporto con mi código  
	SELECT “Id”, “Nombre”, “Direccion_residencia”, “Fecha_nacimiento”,  
	CASE  
	WHEN “Fecha_nacimiento”>‘2015-01-01’ THEN  
	’Niño’  
	ELSE  
	’Mayor’  
	END,  
	CASE  
	WHEN “Nombre” ILIKE ‘c%’ THEN  
	"Nombre"  
	ELSE  
	’No empieza con O’  
	END,  
	CASE  
	WHEN (current_date-“Fecha_nacimiento”) >6570 THEN  
	’Es mayor’  
	ELSE  
	’Es menor’  
	END  
	FROM public.pasajero;  
	–Aquí trae todos los datos del pasajero  
	–En el caso cuando la fecha de nacimiento sea mayor a la del 2015, dice que es niño  
	–Si no, dice que es mayor  
	–En el caos de que su nombre empiece con O  
	–Le dice su nombre, si no pues le dice que no empieza con O  
	–Si la fecha de nacimiento es mayor a 6570 días (18 años) le dice que es mayor, si no, es menor

## 0210. Vistas [24189](https://platzi.com/clases/1480-postgresql/24189-vistas/)

### Descripción:


### Comentarios:

* **dbzdavidbaez** (3) [840463](https://platzi.com/comentario/840463/) 

	Entendido
	``` 
	    CREATEORREPLACEVIEWpublic.rango_view
	     AS
	     SELECTCOALESCE(pasajero.nombre, 'Nombre en Null'::charactervarying) AS nombrenull,
	        pasajero.id,
	        pasajero.nombre,
	        pasajero.direccion_residencia,
	        pasajero.fecha_nacimiento,
	            CASE
	                WHEN pasajero.fecha_nacimiento > '2015-01-01'::dateTHEN'Niño'::text
	                ELSE'Mayor'::text
	            ENDAS tipo,
	            CASE
	                WHEN pasajero.nombre::text ~~* 'D%'::textTHEN'Empieza con D'::text
	                ELSE'No empieza con D'::text
	            ENDAS letra,
	            CASE
	                WHEN date_part('years'::text, age(CURRENT_TIMESTAMP, pasajero.fecha_nacimiento::timestampwithouttime zone::timestampwithtime zone)) >= 18::doubleprecisionTHEN'Mayor de edad.'::text
	                ELSE'Menor de edad.'::text
	            ENDAS edad
	       FROM pasajero;
	    
	    ALTERTABLEpublic.rango_view
	        OWNER TO postgres;
	    
	    CREATEMATERIALIZEDVIEWpublic.despues2014
	    AS
	    SELECT * FROM pasajero WHERE fecha_nacimiento > '2015-01-01'
	    WITHNODATA;
	    
	    ALTERTABLEpublic.despues2014
	        OWNER TO postgres;
	    
	    SELECT * FROM rango_view;
	    SELECT * FROMpublic.despues2014;
	    REFRESH MATERIALIZED VIEW despues2014;
	    SELECT * FROMpublic.despues2014;
	    DELETEFROM pasajero WHEREid = 89;
	    SELECT * FROMpublic.despues2014;
	    REFRESH MATERIALIZED VIEW despues2014;
	    SELECT * FROMpublic.despues2014;
	    
	```

* **Israel Yance** (2) [950386](https://platzi.com/comentario/950386/) 

	Tipos de vistas:  
	**\- Vista Volátil:** Consulta con data actualizada  
	**\- Vista Materializada:** Consulta con data persistente

* **carlossanchez27** (2) [77410](https://platzi.com/comentario/903798/) 
Hola, tengo un ligero problema. Después de crear la vista materializada, al ejecutar el comando REFRESH MATERIALIZED VIEW me arroga el si...

	* **DiegoADaza** [77410] (1)

		Pruebalo ejecutandolo por la pantalla shell.

* **Angel de Jesus Quintero Pereira** (1) [1036352](https://platzi.com/comentario/1036352/) 

	Algo se vio en los anteriores curso de mysql es que es bueno tener unas columnas que indique cuando se creó, actualizó y si está activa o no ya un Ejemplo de usar vista materializada es guardar un registro históricos de los cambios de las tuplas

* **Angel de Jesus Quintero Pereira** (1) [1036348](https://platzi.com/comentario/1036348/) 

	```
	    --Vista Materializada con data
	    --¿Viajes hecho 2019-01-01-hasta 2019-01-31?
	    CREATEMATERIALIZEDVIEWpublic.mview_viaje_2019_01_31
	    AS
	    SELECT * FROM viaje
	    WHERE  viaje.inicio >'2019-01-1'AND  viaje.inicio <'2019-01-31'
	    WITHDATA;
	    
	    ALTERTABLEpublic.mview_viaje_2019_01_31
	        OWNER TO postgres;
	    
	    
	    --Vista Materializada sin data
	    --¿Viajes hecho 2019-01-01-hasta 2019-01-31?
	    CREATEMATERIALIZEDVIEWpublic.mview_viaje_2019_01_31
	    AS
	    --¿Viajes en el período 2019-01-1 hasta 2019-01-1?
	    SELECT * FROM viaje
	    WHERE  viaje.inicio >'2019-01-1' 
	    	AND  
	    	   viaje.inicio <'2019-01-31'
	    
	    WITHNODATA;
	    
	    ALTERTABLEpublic.mview_viaje_2019_01_31
	        OWNER TO postgres;
	    
	    -- con esta instrucción refrescamos los datos para que se creen en la vista
	    REFRESH MATERIALIZED VIEW "mview_viaje_2019_01_31";
	    
	    SELECT * FROM"mview_viaje_2019_01_31";
	    
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1036175](https://platzi.com/comentario/1036175/) 

	Las vistas son útiles porque nos ayudan a centralizar todos los esfuerzo en un solo lugar por otra parte las vistas volátil no guardan información de forma persistente, en cambio la vista materializada si, esto es útil cuando queremos consultar que datos ocurrieron el día ant.

* **Angel de Jesus Quintero Pereira** (1) [1036159](https://platzi.com/comentario/1036159/) 

	Una vista en esencia es tomar una consulta convertirla en un solo nombre. De modo que SELECT * FROM view_name

* **Angel de Jesus Quintero Pereira** (1) [1036156](https://platzi.com/comentario/1036156/) 

	Hay dos tipos de vistas: 1. Vistas Volátil, 2.Vistas Materializada: Persistentes

* **Angel de Jesus Quintero Pereira** (1) [1036153](https://platzi.com/comentario/1036153/) 

	Hay dos tipos de vistas:

* **Angel de Jesus Quintero Pereira** (1) [1036151](https://platzi.com/comentario/1036151/) 

	Tenga en cuenta que una vista no almacena datos físicamente, excepto una vista materializada .

* **Angel de Jesus Quintero Pereira** (1) [1036147](https://platzi.com/comentario/1036147/) 

	Vistas: es un objeto de bd que es de una consulta almacenada. Se puede acceder a una vista como una tabla virtual en PostgreSQL. En otras palabras, una vista PostgreSQL es una tabla lógica que representa datos de una o más tablas subyacentes a través de una instrucción SELECT

* **Edgard Mauricio Alvarez Franco** (1) [975311](https://platzi.com/comentario/975311/) 

	Me quedó claro lo del case en el video 20, pero si quisiera que el case tuviera un nombre en la consulta, como debo escribirlo en sql?

	* **vegadevh** [975311] (1)

		Hola, luego de END escribe AS seguido del nombre que quieras 😃
		
		![Capture.PNG](https://static.platzi.com/media/user_upload/Capture-ec7f5ba9-b320-4439-a294-dfb159ca9caf.jpg)

* **Luis Rodrigo Alvarez Herrera** (1) [883799](https://platzi.com/comentario/883799/) 

	En mi version de Postgres, es necesario colocar la vista Materializada entre comillas si no me arroja error
	``` 
	    SELECT * FROM"VistaM";```
	    
	```

* **Diego Armando Bravo Sanabria** (1) [859017](https://platzi.com/comentario/859017/) 

	Cuando ingreso a la ventana de creación de la vista no me aparece la pestaña “código”

	* **eddyarellanes** [859017] (1)

		¿Qué versión de PgAdmin usas?  
		Yo probé en la 4 y todo OK

* **JUAN CARLOS PARRA GALAN** (1) [73964](https://platzi.com/comentario/844268/) 
¿Como se puede crear un trigger que refresque la vista materializada periódicamente?

	* **Oz** [73964] (2)

		No sería un TRIGGER, sería una función que llames desde una tarea programada o cronjob en linux. que llape periódicamente a la funcion que recarga la vista materializada.

## 0220. PLSQL [24190](https://platzi.com/clases/1480-postgresql/24190-plsql/)

### Descripción:


### Links:

* [PostgreSQL: Documentation: 9.2: PL/pgSQL - SQL Procedural Language](https://www.postgresql.org/docs/9.2/plpgsql.html)

### Comentarios:

* **Abril Darynka Tapia Sosa** (15) [939340](https://platzi.com/comentario/939340/) 

	![](![Captura4.PNG](https://static.platzi.com/media/user_upload/Captura4-96ab9d65-0f83-48c7-b035-b515011ac551.jpg)

	* **aycatalan1995** [939340] (1)

		algun programa para hacer estos esquemas de manera rapida?

	* **Juan David Castro (Platzi)** [939340] (2)

		 **@aycatalan1995** Me han recomendado mucho [draw.io](http://draw.io). 😉

	* **CarlosGR** [939340] (1)

		Thank you =")

* **TUDz** (5) [836727](https://platzi.com/comentario/836727/) 

	Las funciones y los Stored procedure son un pilar dentro de las bases de datos con ayuda de los lenguajes procedurales como PLPGSQL y PL/SQL (En el caso de Oracle). Gran parte de la lógica de negocios puede ser abstraída directamente en la base de datos con ayuda de dicho lenguaje permitiendo liberar al backend de parte de este procesamiento.

* **raul-fernandez-fuentes** (3) [933603](https://platzi.com/comentario/933603/) 

	Esta parte deberia ser un poco mas amplia, ya que es una herramienta fundamental para los desarrolladores de BD, interesante pero me parece que no muestran el verdadero poder de PG si no accedes al core de la BD.

* **dbzdavidbaez** (3) [840553](https://platzi.com/comentario/840553/) 

	Las funciones y procedmientos almacenados son una gran herramienta para realizar las consultas de los datos. Esto optimiza recursos y le saca el jugo al motor de base de datos. Muchas empresas colocan la logica del negocio en la base de datos y asi pueden mejorar el rendimiento y cualquier arreglo en las consultas son mas sencillo de implementar.

* **Jose Gisbert Castillo** (2) [1092119](https://platzi.com/comentario/1092119/) 

	Este curso está muy bien estructurado, explicado de forma clara y concisa gracias Oswaldo.

	* **jgarcia990** [1092119] (1)

		De acuerdo con tu comentario, el contenido, la estructura y el profesor dan mucha claridad en el curso.

* **Diego Alonso García Tenorio** (2) [1017203](https://platzi.com/comentario/1017203/) 

	Buenas Tardes.  
	Esta clase debería ser más compleja y con una introducción previa donde haya mayor explicación.

* **Israel Yance** (2) [954036](https://platzi.com/comentario/954036/) 

	```
	    DO $$
	    DECLARE
	    	rec record
	    BEGIN
	    	FOR rec INSELECT * FROM pasajero LOOP
	    		RAISENOTICE'Un pasajero se llama %', rec.nombre;
	    	ENDLOOP;
	    END
	    $$;
	    
	```

* **Vicente Fernandez** (2) [932792](https://platzi.com/comentario/932792/) 

	Me voy a saltar esta clase porque no entiendo nada…

	* **Abril Darynka Tapia Sosa** [932792] (2)

		Hola Vicente, que es lo que no entiendes de la clase?

	* **SergioRubiano** [932792] (1)

		Si te saltas una clase lo mas probable es que te pierdas en la próxima, haz tu mayor esfuerzo de comprenderla

* **asanchez2091** (1) [1056151](https://platzi.com/comentario/1056151/) 

	Wau es excelente realmente este curso.

* **Angel de Jesus Quintero Pereira** (1) [1037956](https://platzi.com/comentario/1037956/) 

	* PL Procedural language, también conocido como procedimientos almacenados, estas nos ayuda a desarrollar código directamente en el motor de bases de datos.
	
	* Estructura de un Pl es: Declaración + uso de variable+ código +fin + retorno de valores o no retorna valores.UN bloque de código se ejecuta con la palabra DO $$ BEGIN --insert código here END $$
	
	* RAISE NOTICE ‘message’, esta sentencia es para enviar un mensaje en el log de postgres
	
	* Retornar una tabla  
	[Retornar una tabla](https://stackoverflow.com/questions/18084936/pl-pgsql-functions-how-to-return-a-normal-table-with-multiple-columns-using-an).
	
	
	
	
	DO$$ -Declaración de un bloque de código SQL  
	Estructura
	``` 
	    DO $BODY$ 
	        BEGIN 
	            --insert código here 
	        END 
	    $BODY$
	    
	    
	```
	
	Ejemplo de declaración de bloques de código con plpgsql
	``` 
	    DO $$ 
	        DECLARE
	            rec record;
	            contador integer :=0;
	        BEGIN 
	            --recorre  tabla pasajero y lo guarda en la variable rec
	            FOR rec INSELECT * FROM pasajero LOOP 
	                RAISENOTICE'id: %     ,Nombre: %      ',
	                            rec.id,rec.nombre;
	                contador := contador + 1;
	            ENDLOOP;
	            RAISE NOTICE 'cantidad de registros:    %', contador;
	        END 
	    $$
	    
	    
	```
	
	CREATE FUNTION - Declaración de una función SQL
	``` 
	    CREATEFUNCTION  consulta_usuarios() 
	        RETURNSvoid
	        LANGUAGE'plpgsql';
	    AS $BODY$ 
	        DECLARE
	            rec record;
	            contador integer :=0;
	        BEGIN 
	            --recorre  tabla pasajero y lo guarda en la variable rec
	            FOR rec INSELECT * FROM pasajero LOOP 
	                RAISENOTICE'id: %     ,Nombre: %      ',
	                            rec.id,rec.nombre;
	                contador := contador + 1;
	            ENDLOOP;
	            RAISE NOTICE 'cantidad de registros:    %', contador;
	        END 
	    $BODY$
	    
	    
	```
	
	OTRO Ejemplo:  
	Retornar una tabla con plpgsql ¡¡¡¡importante!!! es importante cual select uses para llamar la función. la función funciona de la siguiente manera en el parámetro sí se introduce NULL retorna toda la lista, si se introduce id retornará esa tupla
	``` 
	    --FUNCION QUE RETORNA UNA TABLA
	    --Mostrar tabla con plpgsql
	    --https://stackoverflow.com/questions/18084936/pl-pgsql-functions-how-to-return-a-normal-table-with-multiple-columns-using-an
	    DROPFUNCTION consulta_t_pasajero(p_pasajero_id integer);
	    
	    CREATEORREPLACEFUNCTION consulta_t_pasajero(p_pasajero_id integer) 
	    RETURNSTABLE(idinteger, nombre charactervarying, direccion_residencia charactervarying, fecha_nacimiento date) 
	    LANGUAGE plpgsql
	    AS $BODY$
	        BEGIN
	    		IF p_pasajero_id ISNULLTHEN 
	    		 RETURNQUERY 
	    			SELECT pasajero.id, pasajero.nombre, pasajero.direccion_residencia, pasajero.fecha_nacimiento
	    			FROMpublic.pasajero;
	    		ENDIF;
	    		RETURN QUERY 
	    			SELECT pasajero.id, pasajero.nombre, pasajero.direccion_residencia, pasajero.fecha_nacimiento
	    			FROMpublic.pasajero
	    			WHERE pasajero.id = p_pasajero_id;
	        END;
	    $BODY$
	    
	    --Retorno en forma de fila
	    SELECT consulta_t_pasajero(NULL); 
	    SELECT consulta_t_pasajero(50);
	    --Retorno en forma de tabla
	    SELECT * FROM consulta_t_pasajero(NULL);
	    SELECT * FROM consulta_t_pasajero(50);
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1037943](https://platzi.com/comentario/1037943/) 

	```
	    /*Mostrar  una tabla o un solo registro  con plpg*/
	    DROPFUNCTION consulta_t_pasajero(p_pasajero_id integer);
	    
	    CREATEORREPLACEFUNCTION consulta_t_pasajero2(p_pasajero_id integer) 
	    RETURNSTABLE(idinteger, 
	    			  nombre charactervarying, 
	    			  direccion_residencia charactervarying, 
	    			  fecha_nacimiento date) 
	    LANGUAGE plpgsql
	    AS $BODY$
	        BEGIN
	    		IF p_pasajero_id ISNULLTHEN 
	    		 RETURNQUERY 
	    			SELECT pasajero.id, pasajero.nombre, 
	    					pasajero.direccion_residencia, 
	    					pasajero.fecha_nacimiento
	    			FROMpublic.pasajero;
	    		ENDIF;
	    		RETURN QUERY 
	    			SELECT pasajero.id, pasajero.nombre, 
	    					pasajero.direccion_residencia, 
	    					pasajero.fecha_nacimiento
	    			FROMpublic.pasajero
	    			WHERE pasajero.id = p_pasajero_id;
	        END;
	    $BODY$
	    
	    --Retorno en forma de fila
	    SELECT consulta_t_pasajero(NULL); 
	    SELECT consulta_t_pasajero(50);
	    --Retorno en forma de tabla
	    SELECT * FROM consulta_t_pasajero(NULL);
	    SELECT * FROM consulta_t_pasajero(50);
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1037612](https://platzi.com/comentario/1037612/) 

	Es importante al declarar una función decirle al lenguaje que en que lenguaje está escrito la función ya que postsgre con ciertas librerías soporta python, c++ y pl entre otros.

* **Angel de Jesus Quintero Pereira** (1) [1037545](https://platzi.com/comentario/1037545/) 

	1- DECLARE, es la sentencia para la declaración de variables. 2- El tipo de datos que nos sirve para almacenar una fila es record. 3- llos siguientes caracteres := símolizan asignación

* **Angel de Jesus Quintero Pereira** (1) [1037540](https://platzi.com/comentario/1037540/) 

	Las pl su objetivo principal es realizar consultas a las bases de datos una pl que no tenga que ver con consultas a la base de datos no es muy útil.

* **Angel de Jesus Quintero Pereira** (1) [1037531](https://platzi.com/comentario/1037531/) 

	RAISE NOTICE 'message', esta sentencia es para enviar un mensaje en el log o bitácora de postgres

* **Angel de Jesus Quintero Pereira** (1) [1037397](https://platzi.com/comentario/1037397/) 

	UN bloque de código se ejecuta con la palabra DO $$ BEGIN --insert código here END $$

* **Angel de Jesus Quintero Pereira** (1) [1037376](https://platzi.com/comentario/1037376/) 

	Estructura de un Pl es: Decalración + uso de variable+ código +fin + retorno de valores o no retorna valores.

* **Angel de Jesus Quintero Pereira** (1) [1037134](https://platzi.com/comentario/1037134/) 

	PL Procedural language, también conocido como procedimientos almacenados, estas nos ayuda a desarrollar código directamente en el motor de bases de datos.

* **SergioRubiano** (1) [981243](https://platzi.com/comentario/981243/) 

	```
	    """PL/SQL Usando codigo"""
	    
	    DROPFUNCTION importantepl() ;
	    CREATEORREPLACEFUNCTION importantePL() RETURNSintegerAS $$
	    DECLARE
	     rec record;
	     contador integer :=0;
	    BEGIN
	     FOR rec INSELECT * FROM pasajero LOOP
	    
	       RAISENOTICE'Un pasajero se llama %', rec.nombre;
	       contador = contador + 1;
	     ENDLOOP;
	       RAISE NOTICE 'Conteo es %', contador;
	       RETURN contador;
	    END
	    $$
	    LANGUAGE PLPGSQL;
	    
	    
	    SELECT importantePL();
	    
	```

* **DiegoADaza** (1) [79260](https://platzi.com/comentario/936806/) 
Que diferencias hay entre ejecutar un Store Procedure de PLSQL Vs SQL server?

	* **David Rueda** [79260] (3)

		SQL Server es la versión de manejador de bases de datos de Microsoft, se puede decir es un competidor de PostgreSQL.
		
		Mientras PL/SQL es el “lenguaje de procedimientos” para SQL, puede ser ejecutado en diferentes manejadores con sus respectivos ajustes de sintaxis.

* **_namp** (1) [79122](https://platzi.com/comentario/934059/) 
Esto es lo que en SQL SERVER se llaman “CURSORES”?

* **Jaime Andrés Martínez Rodríguez** (1) [79030](https://platzi.com/comentario/932064/) 
Estoy tratando de crear la función pero me salta un error exactamente en el END LOOP; ¿Alguien detecta el error? CREATE FUNCTION importan...

	* **Juan David Castro (Platzi)** [79030] (1)

		Te falta un punto y coma ( **`;`** ) en la línea antes del **`END LOOP`** : **`contador := contador+1;`**.

* **SistemasCBC** (1) [74655](https://platzi.com/comentario/856767/) 
Hola, para crear funciones y llamarlas solamente se puede realizar desde el pgAdmin? no se puede desde Consola?

	* **rulobars** [74655] (4)

		Puedes hacerlo desde el psql sin problemas desde el psql te dejo un ejemplo:
		
		CREATE FUNCTION sumar(a integer,b integer)  
		RETURNS integer AS $$  
		BEGIN  
		RETURN a + b;  
		END; $$  
		LANGUAGE PLPGSQL;
		
		y la puedes llamar igual:
		
		SELECT sumar(6,3);

## 0230. Triggers [24191](https://platzi.com/clases/1480-postgresql/24191-triggers/)

### Descripción:


### Comentarios:

* **TUDz** (4) [836736](https://platzi.com/comentario/836736/) 

	Los triggers son de gran ayuda, ya que permiten poblar bitácoras (por ejemplo) al momento de realizar inserts o updates dentro de tablas contenidas dentro de nuestro sistema. Su estructura es:
	
	* Creación de función con tipo de **RETURN TRIGGER**.
	* Creación de trigger asociado a una acción y momento concreto sobre una tabla **[AFTER, BEFORE, INSTEAD] [UPDATE,INSERT,DELETE,TRUNCATE]**
	
	

* **SOFTDYNAMIC** (3) [987152](https://platzi.com/comentario/987152/) 

	No era necesario eliminar el trigger y volver a crear todo ya que el tipo de retorno definido era el mismo.
	``` 
	    CREATE TRIGGER snapshot_passengers_trigger
	    AFTER INSERT OR DELETE 
	    ON passengers
	    FOREACH ROW
	    EXECUTE PROCEDUREsnapshot_passengers_procedure();
	    
	```

* **Abril Darynka Tapia Sosa** (3) [940192](https://platzi.com/comentario/940192/) 

	![](![Captura5.PNG](https://static.platzi.com/media/user_upload/Captura5-5794b1b7-7b56-4dd7-b0be-201aae420ec3.jpg)

* **rulobars** (3) [851873](https://platzi.com/comentario/851873/) 

	Hay que tener cuidado con los Triggers y no usarlos en la logica del negocio porque pueden volverse un dolor de cabeza, yo solo los utilizo para realizar el llenado de alguna tabla de auditoria, ya que las variables OLD y NEW te permiten saber que campos sufrieron modificaciones, y solo registrar los campos que se modifican.

	* **Oz** [851873] (1)

		De acuerdo, son muy potentes, por eso mismo, son de mucho cuidado. Si la lógica del negocio los necesita, son muy útiles, en la empresa donde trabajo los usamos, tenemos más de 15 Triggers.

	* **jaime-pinto-a** [851873] (1)

		Los Triggers son muy recomendable, para los sistema de pista de auditorias, nos ayudan muchos para conocer quienes realizaron los cambios en los sistemas,

* **Carlos Chavez** (2) [1111112](https://platzi.com/comentario/1111112/) 

	Quedé en la nebulosa con esta lección.

* **asanchez2091** (2) [1064630](https://platzi.com/comentario/1064630/) 

	Esta clase creo que estuvo muy compleja

	* **ejgachancipa** [1064630] (1)

		De acuerdo 😰😬

* **Angel de Jesus Quintero Pereira** (2) [1039742](https://platzi.com/comentario/1039742/) 

	DROP FUNCTION IF EXISTS count_on_insert_pasajero() CASCADE; en ocasiones para borrar una función de tipo triggers nos arrojará error porque de esta función dependen otros objetos y debemos utilizar CASCADE

* **arnolplazas** (2) [972922](https://platzi.com/comentario/972922/) 

	Cambie el mismo trigger que teníamos agregando solo DELETE
	``` 
	    CREATE TRIGGER mitrigger
	    AFTER INSERT OR DELETE
	    ON pasajero
	    FOREACH ROW
	    EXECUTE PROCEDUREpublic."importantePL3"();```
	    
	```

* **adriangonw77** (2) [889792](https://platzi.com/comentario/889792/) 

	funcionó excelente clase ,  
	![ejercicio funcion y trigger.JPG](https://static.platzi.com/media/user_upload/ejercicio%20funcion%20y%20trigger-cfa4b6a7-b4cd-4c2a-9382-197b3622e014.jpg)![tabla delete.JPG](https://static.platzi.com/media/user_upload/tabla%20delete-87bbb5dd-8c05-4bb9-886e-3ead7aabb5e7.jpg)

* **Luis Rodrigo Alvarez Herrera** (2) [885435](https://platzi.com/comentario/885435/) 

	Mi aporte
	``` 
	    CREATE TRIGGER mitrigger2 --Crea el trigger con nombre
	    AFTER DELETE --Hazlo despues de AFTER o antes BEFORE
	    ON pasajero -- que que tabla
	    FOREACH ROW -- Cada cuando por cada fila
	    EXECUTE PROCEDUREimportantepl(); --y ejecuta la funcion
	    
	```

* **dbzdavidbaez** (2) [841559](https://platzi.com/comentario/841559/) 

	Los tirggers son un gran mecanismo para colocar codigo de los aplicativos en la capa de base de datos y validar logica. Hay que tener mucho cuidado en tablas de alta transaccionalidad ya que pueden generar un cuello de botella en el rendimeinto.

* **juanreinag** (1) [1115688](https://platzi.com/comentario/1115688/) 

	Tarea resuelta:
	
	![eliminar_trigger.png](https://static.platzi.com/media/user_upload/eliminar_trigger-03f5f940-4fc3-4d22-9ed1-87baa990d9eb.jpg)

* **Peter_g** (1) [1067247](https://platzi.com/comentario/1067247/) 

	TAREA:
	
	CREATE TRIGGER nombre_trigger  
	AFTER DELETE  
	ON pasajero  
	FOR EACH ROW  
	EXECUTE PROCEDURE nombre_funcionPL();

* **Angel de Jesus Quintero Pereira** (1) [1039851](https://platzi.com/comentario/1039851/) 

	 **23\. Triggers**  
	Para la creación de triggers se debe hacer los siguiente  
	Crear la función que activará el evento. Para ello se debe tomar los siguientes aspectos:
	
	  1. En la declaración de la función, en la sección del retorno se debe indicar que es tipo triggers es decir RETURNS TRIGGER.  
	Luego indicar en que lenguaje está escrito es decir LANGUAE ‘plpgsql’
	
	  2. La función tipo triggers debe retornar los valores OLD acepta lo viejo o NEW acepta lo nuevo. Sí se retorna VOID en nuestra función de tipo triggers no aceptamos cambios es decir RETURN NEW;
	
	  3. Tanto NEW como OLD son un objeto de tipo record y contiene dentro de si el registro, es decir se puede acceder a los campos NEW.campo_nombre del registro
	
	
	
	``` 
	    DROPFUNCTIONIFEXISTS  count_on_insert_pasajero() CASCADE;
	    
	    CREATEORREPLACEFUNCTION count_on_insert_pasajero()
	    	RETURNSTRIGGER
	    	LANGUAGE'plpgsql'
	    AS $BODY$
	    	DECLARE 
	    		contador integer:=0;
	    		rec record;
	    	BEGIN
	    		
	    		FOR rec INSELECT * FROM pasajero LOOP 
	    			contador := contador + 1;
	    		ENDLOOP;
	    		RAISE NOTICE 'cantidad de registros:	%', contador;
	    		
	    		--insert record on conteo_pasajero
	    		INSERTINTOpublic.conteo_pasajero (total_pasajero,hora_conteo)
	    		VALUES (contador,now());
	    		
	    		RETURN NEW;
	    		
	    	END;	
	    $BODY$
	    
	    
	```
	
	Lo siguiente será crear la regla que estará a la escucha del evento para disparar el triggers, para ello se deberá tomar los siguientes aspectos.
	
	  1. CREATE TRIGGER name_trigger name_event ON name_table FOR EACH ROW EXECUTE PROCEDURE name_procedure;
	
	  2. En la primera sección cuando declaramos el trigger debemos indicar en que momento en que se debe disparar el trigger:  
	CREATE TRIGGER name_trigger name_event ON name_table en el name_event allí puede ir alguno de estos tres parámetros para llamar la ejecución del trigger, estos son:
	
	
	
	* BEFORE = antes,
	
	* AFTER=luego,
	
	* INSTEAD OF = hacer esto, en vez de lo que iba a hacer el motor de bases de datos.
	
	
	
	  1. FOR EACH ROW EXECUTE PROCEDURE name_procedure indica que es para registro o fila de nuestra tabla
	
	
	``` 
	    -- CREACIÓN DE LA REGLA PARA EJECUTAR EL TRIGGER
	    CREATE TRIGGER trigger_on_insert_to_pasajero
	    AFTER INSERT ON pasajero 
	    FOREACH ROW EXECUTE PROCEDUREcount_on_insert_pasajero(); 
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1039603](https://platzi.com/comentario/1039603/) 

	CREATE TRIGGER name_trigger AFTER name_event ON name_table FOR EACH ROW EXECUTE PROCEDURE name_procedure;

* **Angel de Jesus Quintero Pereira** (1) [1039602](https://platzi.com/comentario/1039602/) 

	FOR EACH ROW EACH ROW EXECUTE PROCEDURE indica que es para registro o fila de nuestra tabla

* **Angel de Jesus Quintero Pereira** (1) [1039583](https://platzi.com/comentario/1039583/) 

	CREATE TRIGGER name_trigger AFTER name_event ON name_table ; al crearlo este recibe tres parámetros para llamar la ejecución del trigger, estos son: BEFORE = antes, AFTER=luego, INSTEAD OF = hacer esto, en vez de lo que iba a hacer el motor de bases de datos.

* **Angel de Jesus Quintero Pereira** (1) [1038183](https://platzi.com/comentario/1038183/) 

	La función tipo triggers debe retornar los valores OLD acepta lo viejo o NEW acepta lo nuevo. Sí se retorna VOID en nuestra función de tipo triggers no aceptamos cambios. Tando NEW como OLD son un objeto de tipo record y contiene dentro de si el registro.

* **Angel de Jesus Quintero Pereira** (1) [1038179](https://platzi.com/comentario/1038179/) 

	Cuando creamos una función de tipo trigger debemos retornar información al motor de bases de datos para confirmar los cambios. Los triggers tienen dos objetos importantes para retornar: old y new

* **Angel de Jesus Quintero Pereira** (1) [1038050](https://platzi.com/comentario/1038050/) 

	La NOW()función devuelve la fecha y hora actuales. El tipo de retorno de la NOW()función es la marca de tiempo con zona horaria

* **Angel de Jesus Quintero Pereira** (1) [1038016](https://platzi.com/comentario/1038016/) 

	Triggers también conocido como disparadores estas nos permite ejecutar funciones dependiendo de acciones que ocurran sobre una tabla. Esas acciones pueden ser: Insert, Update, Delete

* **MaxLandh** (1) [947219](https://platzi.com/comentario/947219/) 

	```
	    CREATE TRIGGER del_trigger
	        AFTER DELETE
	        ONpublic.pasajero
	        FOREACH ROW
	        EXECUTE PROCEDUREpublic.impl();```
	    
	```

* **Marco Antonio González Arellano** (1) [887254](https://platzi.com/comentario/887254/) 

	Mi trigger:
	
	![](![trigger.png](https://static.platzi.com/media/user_upload/trigger-dda3f80c-ff84-4113-9875-fca659862029.jpg)

* **andoni** (1) [876800](https://platzi.com/comentario/876800/) 
	
	![n.JPG](https://static.platzi.com/media/user_upload/n-ebcbfef5-2395-4594-99eb-a96b16b37995.jpg)

* **Eduardo Imery Winterdaal** (1) [850659](https://platzi.com/comentario/850659/) 

	Muy buena explicación
	``` 
	    CREATE TRIGGER pruebatrigger
	    AFTER DELETE
	    ON pasajero
	    FOREACH ROW
	    EXECUTE PROCEDUREpruebapl3();
	    
	```

* **Joan Federico Marin Ruiz** (1) [78722](https://platzi.com/comentario/926469/) 
como hago para limitar un delete para que solo se borre un registro como un LIMIT?

	* **Fernando Ojeda** [78722] (2)

		Podría ser usando **ctid**
		``` 
		    DELETEFROM mi_tabla
		    WHERE ctid IN (
		        SELECT ctid
		        FROM mi_tabla
		        ORDERBYtimestamp
		        LIMIT10
		    )
		    
		```

* **dbzdavidbaez** (1) [73794](https://platzi.com/comentario/841556/) 
Para insert las tablas temporales OLD y NEW del TRIGGER contiene los mismos datos? creo que la diferencia es para UPDATE

	* **Oz** [73794] (2)

		La diferencia es realmente para Update, cuando se trata de Insert, OLD no tiene nada y NEW tiene los nuevos datos.

# Integrar bases de datos con servicios externos [4837]

## 0240. Simulando una conexión a Bases de Datos remotas [24192](https://platzi.com/clases/1480-postgresql/24192-simulando-una-conexion-a-bases-de-datos-remotas/)

### Descripción:


### Links:

* [Mockaroo  - Random Data Generator and API Mocking Tool | JSON / CSV / SQL / Excel](https://mockaroo.com)

### Comentarios:

* **elvis.sanchez** (6) [835614](https://platzi.com/comentario/835614/) 

	OMG! Lo tiene todo

* **Luis Rodrigo Alvarez Herrera** (2) [885541](https://platzi.com/comentario/885541/) 

	Mi aporte, datos basicos para usar dblink
	
	Este debe estar activado en postgres, si no lo esta debe hacerse con
	``` 
	    CREATE EXTENSION dblink;
	    
	```
	
	Una simple consulta en la tabla remota
	``` 
	    select * from
	    dblink ('dbname=RemoteDB
	    		port=5432 <-- puerto remoto
	    		host=X.x.x.x <-- IP remota
	    		user= postgres <-- usuario
	    		password= postgres', <-- password, aguas, debe estar encapsulado
	    	   'SELECT id FROM usuarios_vip') <-- la consulta
	    	   AS datos_remotos (id integer); <-- los datos deben ser expresados como otra tabla y de que tipo son
	    
	```

* **andoni** (2) [876895](https://platzi.com/comentario/876895/) 

	Utilizando un right join trayendo solo aquellos usuarios que no son vip 😄  
	![t.JPG](https://static.platzi.com/media/user_upload/t-b8afcbda-ca82-4da2-89c6-352cd61dc5fe.jpg)

* **dbzdavidbaez** (2) [841723](https://platzi.com/comentario/841723/) 

	Entendido
	``` 
	    CREATE EXTENSION dblink;
	    	   
	    SELECT * FROM pasajero INNERJOIN
	    dblink ('dbname=dbz 
	    		port=5432 
	    		host=127.0.0.1 
	    		user=consulta 
	    		password=consulta ' ,
	    	   'SELECT id, fecha FROM usuario_vip') 
	    	   as datos (idINTEGER, fecha DATE)
	    	   USING(id); 
	    
	```

* **DonTapas** (1) [1115987](https://platzi.com/comentario/1115987/) 
	
	![Screenshot_4.jpg](https://static.platzi.com/media/user_upload/Screenshot_4-9f40d19b-dafb-4f5d-92ba-232e83ce2af4.jpg)

* **juanreinag** (1) [1115771](https://platzi.com/comentario/1115771/) 

	Esta es la tarea:
	
	![consulta_remota.png](https://static.platzi.com/media/user_upload/consulta_remota-32c17eed-47be-4b04-b69a-eff0db003aaa.jpg)

* **Angel de Jesus Quintero Pereira** (1) [1041210](https://platzi.com/comentario/1041210/) 

	```
	    /*Reto:
	    desde la bases de datos remota realizar la conexión a la  tabla pasajero 
	    */
	    CREATE EXTENSION dblink;
	    SELECT * FROM vip 
	    JOIN dblink(
	    	'
	    		dbname=transporte
	    		port=5432
	    		host=127.0.0.1
	    		user=usuario_consulta
	    		password=1234
	    	',
	    	'SELECT id,nombre,direccion_residencia,fecha_nacimiento FROM pasajero') AS 
	    	datos_pasajero(idinteger ,nombre charactervarying, direccion_residencia charactervarying , fecha_nacimiento date)
	    ON (vip.id_pasajero = datos_pasajero.id);
	    
	```
	
	![](![Captura de pantalla \(99\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2899%29-7f9dbbab-f2d4-46f6-bfb1-643950c50679.jpg)

* **Angel de Jesus Quintero Pereira** (1) [1041146](https://platzi.com/comentario/1041146/) 

	 **24\. Simulando una conexión a Bases de Datos remotos**  
	dblink ejecuta una consulta (generalmente una SELECT, pero puede ser cualquier instrucción SQL que devuelva filas) en una base de dato remota.
	
	**Instalación dblink en postgres**
	``` 
	    CREATE EXTENSION dblink;
	    
	```
	
	**Otorgar permisos a un usuario que no se postgres para realizar la consulta**
	``` 
	    GRANT ALL ONTABLEpublic.vip TO usuario_consulta;
	    
	```
	
	**Preparación para probar la consulta remota**
	
	  1. Creamos la base de dato remota para simular una consulta remota.
	
	
	``` 
	    CREATEDATABASE remota
	        WITH 
	        OWNER = postgres
	        ENCODING = 'UTF8'
	        CONNECTIONLIMIT = -1;
	    
	```
	
	  1. Se crea una tabla para guardar los datos de los clientes vip del sistema de transporte.
	
	
	``` 
	    CREATETABLEpublic.vip
	    (
	        idserialNOTNULL,
	        id_pasajero integerNOTNULL,
	        fecha date,
	        PRIMARY KEY (id)
	    )
	    WITH (
	        OIDS = FALSE
	    );
	     
	    ALTERTABLEpublic.vip
	        OWNER to postgres;
	    
	```
	
	  1. Realizamos dos insert para llenar la tabla.
	
	
	``` 
	    INSERTINTOpublic.vip (id_pasajero,fecha)VALUES('50','2010-01-01'),('49','2010-01-01');
	    
	```
	
	**SQL Elaborando consulta remota para postgres**
	
	  1. Elaboramos la consulta para nuestra base de dato remota
	
	
	``` 
	    SELECT * FROM 
	    dblink('dbname=remota
	            port=5432
	            host=127.0.0.1
	            user=usuario_consulta
	            password=1234',
	        'SELECT id,id_pasajero,fecha FROM vip') AS datos_remotos(idinteger,id_pasajero integer, fecha date);
	    
	```
	
	**SQL Elaborando JOIN con consulta remota para postgres**  
	5\. Cruce de tablas locales con tablas remotas.
	``` 
	    SELECT * FROM pasajero 
	    JOIN dblink('dbname=remota
	                port=5432
	                host=127.0.0.1
	                user=usuario_consulta
	                password=1234',
	            'SELECT id,id_pasajero,fecha FROM vip') AS 
	            datos_remotos(idinteger ,id_pasajero integer, fecha date)
	            ON (pasajero.id = datos_remotos.id_pasajero);
	    /*USING(id)
	     se puede reemplazar el ON por el  USING, Esta es una cápsula 
	     que se utiliza cuando  queremos comparar dos campos que se llaman igual
	     en tablas diferentes
	    */
	    
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1041131](https://platzi.com/comentario/1041131/) 

	USING(id) se puede remplazar el ON por el USING, Esta es una clapsula que se utiliza cuando queremos comparar dos campos que se llaman igual en tablas diferentes

* **Angel de Jesus Quintero Pereira** (1) [1041129](https://platzi.com/comentario/1041129/) 

	Concediendo permiso usuario GRANT ALL ON TABLE table_name TO user_name;

* **Angel de Jesus Quintero Pereira** (1) [1041127](https://platzi.com/comentario/1041127/) 

	SELECT * FROM dblink('dbname=remota port=number_port host=name_host user=user_name password=password','SELECT field_name1, field_name2 FROM name_table') AS name_select (name_select.field type_data)

* **Angel de Jesus Quintero Pereira** (1) [1041114](https://platzi.com/comentario/1041114/) 

	SELECT * FROM ('db=name_dataBase ')

* **Angel de Jesus Quintero Pereira** (1) [1040998](https://platzi.com/comentario/1040998/) 

	Se puede utilizar una vista materializada para ocultar la información de conexión a una bases de datos remota

* **Angel de Jesus Quintero Pereira** (1) [1040950](https://platzi.com/comentario/1040950/) 

	dblink ejecuta una consulta (generalmente una SELECT, pero puede ser cualquier instrucción SQL que devuelva filas) en una base de dato remota.

* **Diego Alonso García Tenorio** (1) [1017655](https://platzi.com/comentario/1017655/) 

	Buenas Noches.  
	Este es mi aporte.  
	![3.png](https://static.platzi.com/media/user_upload/3-e5cca0a1-b068-4711-a124-f0da2cce7797.jpg)

* **Maria Edith mendoza gabriel** (1) [1003370](https://platzi.com/comentario/1003370/) 

	![](![conexion a base reomta.png](https://static.platzi.com/media/user_upload/conexion%20a%20base%20reomta-b719781e-e3a9-4b45-b10b-558594ba259f.jpg)

* **SOFTDYNAMIC** (1) [987267](https://platzi.com/comentario/987267/) 

	A great extension !!

* **Juan Osio** (1) [973961](https://platzi.com/comentario/973961/) 
	
	![carbon \(1\).png](https://static.platzi.com/media/user_upload/carbon%20%281%29-74d17eb8-4683-4243-ac1e-731a9e65d33a.jpg)

* **jhon Erik calderon Rubiano** (1) [946967](https://platzi.com/comentario/946967/) 

	excelente herramienta e implentacion el ejemplo mencionado![Captura.JPG](https://static.platzi.com/media/user_upload/Captura-9c744527-fa89-400e-932d-983c033ae4a7.jpg)

* **Marco Antonio González Arellano** (1) [890249](https://platzi.com/comentario/890249/) 

	Muy útil… pensaré cómo implementarlo próximamente.
	
	Gracias!

* **Heriberto Rivera** (1) [883888](https://platzi.com/comentario/883888/) 

	¿En qué escenarios es bueno implementar DBLINK?

	* **SOFTDYNAMIC** [883888] (1)

		No necesitas de una aplicación para matchear datos de distintas bases de datos.

	* **Hector Ucedo** [883888] (1)

		Hay casos que una empresa tiene datos de clientes en una base de datos Oracle y tiene un sistema de envío de SMS que puede estar en Postgres.
		
		Al momento de realizar un Reporte de SMS enviados por clientes haces Join a la tabla de clientes que están en Oracle con los SMS enviados que se guardan en Postgres.
		
		Select b.nom_completo,  
		s.message  
		from ba_personas b  
		join sms_report@ccdata s on b.cod_persona = [s.id](http://s.id);

* **jaime-pinto-a** (1) [867351](https://platzi.com/comentario/867351/) 

	Postgresql, de largo es la mejor base, open source

* **asanchez2091** (1) [85039](https://platzi.com/comentario/1064782/) 
Me genero dudas yo desde pgadmin puedo ingresar una ip y conectarme a un servidor remoto y sobre eso usar dblink??? o para que uso dblink??

	* **hgarciac** [85039] (1)

		Se usa para conectarte a una tabla o vista (supongo) en una base de datos remota sin acceder completamente a esa base de datos

* **Joseph Santibáñez** (1) [82608](https://platzi.com/comentario/1008900/) 
¿Es posible guardar un dblink como un objeto? Por ejemplo, en Oracle, con la sentencia CREATE DBLINK puedo generar un objeto con los pará...

## 0250. Transacciones [24193](https://platzi.com/clases/1480-postgresql/24193-transacciones/)

### Descripción:


### Comentarios:

* **dbzdavidbaez** (5) [841811](https://platzi.com/comentario/841811/) 

	COMMIT  
	Muy importante para mantener la integridad de los datos. Hay que tene rmucho cuidado en cerrar siempre la transaccion, ya sea con COMIMIT o ROLLBACK.
	``` 
	    BEGIN;
	    SELECTnow();
	    COMMIT;
	    
	    BEGIN;	
	    INSERTINTOpublic.tren(
	    	 modelo, capacidad)
	    	VALUES ( 'Model Tran', 100);
	    	
	    INSERTINTOpublic.estacion(
	    	 id, nombre, direccion)
	    	VALUES ( 2,'Begin', 'Tran');
	    COMMIT;
	    
	```

* **raul-fernandez-fuentes** (2) [933818](https://platzi.com/comentario/933818/) 

	Esto me recuerda no solo el uso de transacciones, sino tb que debemos controlarlo o gestionarlo dependiendo de la logica de negocio.

* **Angel de Jesus Quintero Pereira** (1) [1041391](https://platzi.com/comentario/1041391/) 

	 **25.Transacciones**  
	Las transacciones, tienen la capacidad para empaquetar varios pasos en una sola operación “todo o nada”.y si ocurre alguna falla que impida que se complete la transacción, entonces ninguno de los pasos se ejecuta y no se afecta la base de datos en absoluto.
	
	**SQL Transacción - Estructura**  
	La transacciones tienen la siguiente estructura postgres. **Postgres en las operaciones normales usa de manera implícita el rollback el rollback**.
	``` 
	    BEGIN;
	    <Intrucciones>
	    COMMIT|ROLLBACK
	    
	```
	
	**SQL Transacción - Ejemplo en PgAdmin**
	
	  1. Desactivamos en la equina superior de pg-admin el auto commit
	
	  2. Iniciamos la transacción
	
	
	
	``` 
	    BEGIN;
	    INSERTINTOpublic.estacion(nombre,direccion)
	    VALUES('Estación Transacción',' 1');
	     
	    INSERTINTOpublic.tren(modelo,capacidad)
	    VALUES('Modelo Transacción','2');
	     
	    COMMIT;
	    
	```
	
	**SQL Transacción - Ejemplo de un rollback implícito**  
	Como se puede visualizar en el ejemplo existe una inserción correcta en la tabla tren pero en la tabla estación sé está haciendo un insert a un id que existe realmente.
	``` 
	    BEGIN;
	     
	     
	    INSERTINTOpublic.tren(modelo,capacidad)
	    VALUES('Modelo Transacción 2','2');
	     
	    INSERTINTOpublic.estacion(id,nombre,direccion)
	    VALUES(101,'Estación Transacción 2',' 1');
	     
	    COMMIT;
	    
	```

* **Angel de Jesus Quintero Pereira** (1) [1041370](https://platzi.com/comentario/1041370/) 

	Para realizar un rollback de manera explicta podría ser dentro de una función (PL) escrita en plpgsql

* **Angel de Jesus Quintero Pereira** (1) [1041367](https://platzi.com/comentario/1041367/) 

	Postgres en las operaciones normales usa de manera implicita el rollback

* **Angel de Jesus Quintero Pereira** (1) [1041365](https://platzi.com/comentario/1041365/) 

	BEGIN; <Intrucciones;> COMMIT;|ROLLBACK;

* **Angel de Jesus Quintero Pereira** (1) [1041364](https://platzi.com/comentario/1041364/) 

	Las transacciones, tienen la capacidad para empaquetar varios pasos en una sola operación “todo o nada”.y si ocurre alguna falla que impida que se complete la transacción, entonces ninguno de los pasos se ejecuta y no se afecta la base de datos en absoluto.

* **Marco D'Agostini** (1) [984198](https://platzi.com/comentario/984198/) 

	Cuando ejecutó la transacción que falló, veo que los botones de commit y rollback se activaron.  
	Eso quiere decir que la transacción quedó abierta, ¿O me equivoco?.
	
	Osea, creo que realmente no se hizo un **rollback** automaticamente, sino que simplemente el primer **insert** aún no se ha consolidado con un **commit**.
	
	Asumo que una transacción que queda abierta eventualmente se le agota un tiempo de espera, y allí es cuando realmente se hace un **rollback**.

	* **juanreinag** [984198] (1)

		Sí, una transacción no finaliza hasta que ocurra un **commit** o un **rollback**

## 0260. Otras Extensiones para Postgres [24194](https://platzi.com/clases/1480-postgresql/24194-otras-extensiones-para-postgres/)

### Descripción:


### Links:

* [PostgreSQL: Documentation: 11: Appendix F. Additional Supplied Modules](https://www.postgresql.org/docs/11/contrib.html)

### Comentarios:

* **Diego Bastidas** (9) [905154](https://platzi.com/comentario/905154/) 

	Lastima no poder darle LIKE al video. Por que se lo merece!

* **TUDz** (5) [836777](https://platzi.com/comentario/836777/) 

	Una extensión que me pareció muy interesante es [passwordcheck](https://www.postgresql.org/docs/11/passwordcheck.html) la cual verifica el nivel de fortaleza de un password cuando un usuario/rol es creado en la base de datos. Esto, brinda una capa de seguridad adicional protegiéndonos de ataques de fuerza bruta ya que garantiza que tenemos una contraseña segura.

	* **David Rueda** [836777] (4)

		Para el tema de seguridad, agregaría el uso de la extensión **pgcrypto** , que permite implementar funciones de **criptografía** al PostgreSQL.

* **dbzdavidbaez** (3) [841845](https://platzi.com/comentario/841845/) 

	Excelente
	``` 
	    CREATE EXTENSION fuzzystrmatch;
	    SELECT levenshtein('oswaldo', 'osvaldo')
	    SELECTdifference('oswaldo', 'osvaldo');
	    SELECTdifference('beard', 'bird');
	    
	```

* **David Rueda** (2) [854459](https://platzi.com/comentario/854459/) 

	En mi caso usaría con frecuencia la extensión **PostGIS** que habilita **análisis espacial **y manejo de geometrías, todo lo necesario para un Sistema de información geográfica.

* **Angel de Jesus Quintero Pereira** (1) [1041448](https://platzi.com/comentario/1041448/) 

	CREATE EXTENSION name_extension; activamos la extensión;

* **SOFTDYNAMIC** (1) [987489](https://platzi.com/comentario/987489/) 

	😉
	``` 
	    SELECT levenshtein('beer', 'bear');
	    SELECTdifference('son', sun');
	    
	```

* **adriangonw77** (1) [893063](https://platzi.com/comentario/893063/) 

	la que me parece mas interesante el la le SELECT levenshtein, ya que la comparación de caracteres si se aplica muy bien a una base de datos y por supuesto dblink es indispensable

* **jaime-pinto-a** (1) [867532](https://platzi.com/comentario/867532/) 

	La mas interesante para mi caso son dblink y postgis,

# Implementar mejores prácticas [4838]

## 0270. Backups y Restauración [24195](https://platzi.com/clases/1480-postgresql/24195-backups-y-restauracion/)

### Descripción:


### Comentarios:

* **Deiby Johany Avila Gutierrez** (9) [838860](https://platzi.com/comentario/838860/) 

	es importante resaltar que cuando se hace un backup para ser restaurado en una versión diferente se debe de usar la opción plana dado que el custom varia de versión a versión.

	* **Marco Antonio González Arellano** [838860] (1)

		Muchas gracias por el dato compañero!

	* **vegadevh** [838860] (1)

		Muchas gracias!

* **dbzdavidbaez** (3) [842364](https://platzi.com/comentario/842364/) 

	Muy buena clase, es muy importante contar con una estrategia para respaldar los datos y que cumplan el RTO y RPO del negocio.

* **dbzdavidbaez** (2) [73847](https://platzi.com/comentario/842365/) 
Se puede automatizar la generacion de copias de seguridad ?

	* **Juan David Castro (Platzi)** [73847] (3)

		Sure!
		
		👉 [https://medium.com/@fab_peja/backups-automáticos-con-postgresql-bash-y-cronjobs-en-español-b3c900e03fd9](https://medium.com/@fab_peja/backups-autom%C3%A1ticos-con-postgresql-bash-y-cronjobs-en-espa%C3%B1ol-b3c900e03fd9)  
		👉 <https://wiki.postgresql.org/wiki/Automated_Backup_on_Windows>  
		👉 <https://wiki.postgresql.org/wiki/Automated_Backup_on_Linux>

* **Angel de Jesus Quintero Pereira** (1) [1042257](https://platzi.com/comentario/1042257/) 

	Pestaña Dump options, la opción Do not save en esta sección podemos escoger sí guardar el propietario (Owner),

* **Angel de Jesus Quintero Pereira** (1) [1042244](https://platzi.com/comentario/1042244/) 

	Pestaña Dump options, la opción Type of objects se puede definir solo los datos (Only data), también podemos solo el esquema (Only schema), por otro lado podemos escoger guardar los binarios sí es que se guardan los binarios (blobs)

* **Angel de Jesus Quintero Pereira** (1) [1042236](https://platzi.com/comentario/1042236/) 

	Pestaña Dump options, la opción Sections se pueden poner los datos antes de ser insertados o no ser insertados como acciones. Sí seleccionamos los datos no tenemos que preocuparnos por el esquema.

* **Angel de Jesus Quintero Pereira** (1) [1042231](https://platzi.com/comentario/1042231/) 

	Pestaña Dump options, Nos permite configurar la opción si queremos el backup con datos o solo la estructura de la tabla, también se puede definir el propietario.

* **Angel de Jesus Quintero Pereira** (1) [1042051](https://platzi.com/comentario/1042051/) 

	Role name Es de quién va a hacer dueño ese dump

* **Angel de Jesus Quintero Pereira** (1) [1042048](https://platzi.com/comentario/1042048/) 

	Number Of Jobs lo debe determinar pgAdmin

* **Angel de Jesus Quintero Pereira** (1) [1041979](https://platzi.com/comentario/1041979/) 

	Encoding: hace referencia al tipo de codificación de los carácteres

* **Angel de Jesus Quintero Pereira** (1) [1041973](https://platzi.com/comentario/1041973/) 

	Compression ratio: es el número de veces que algoritmo de compresión se ejecuta para reducir el tamaño del archivo

* **Angel de Jesus Quintero Pereira** (1) [1041957](https://platzi.com/comentario/1041957/) 

	Custom, Esta opción única de postgres y solo se puede restaurar por pgAdmin. Tar, Es un archivo comprimido que contiene la estructura de la base de datos. Plain, simplemente es un archivo.sql. Directory tiene solo la estructura sin comprimir de la base de datos.

* **cristianwalteros** (1) [848153](https://platzi.com/comentario/848153/) 

	Como una buena practica, es bastante importante tener backups

## 0280. Mantenimiento [24196](https://platzi.com/clases/1480-postgresql/24196-mantenimiento/)

### Descripción:


### Links:

* [El apagón de Platzi / Migramos de MySQL a PostgreSQL](https://platzi.com/blog/el-apagon-de-platzi-migramos-de-mysql-a-postgresql/)

### Comentarios:

* **dbzdavidbaez** (3) [842378](https://platzi.com/comentario/842378/) 

	Super importante esta informacion, una base de datos debe contar con un rendimiento optimo en todas las transacciones que se ejecutan.

* **eduardo-zepeda** (1) [1084576](https://platzi.com/comentario/1084576/) 

	* Vacuum: La más importante, con tres opciones, Vacuum, Freeze y Analyze.  
	Full: la tabla quedará limpia en su totalidad  
	Freeze: durante el proceso la tabla se congela y no permite modificaciones hasta que no termina la limpieza  
	Analyze: solo revisa la tabla
	
	* Analyze: No hace cambios en la tabla. Solo hace una revisión y la muestra.
	
	* Reindex: Aplica para tablas con numerosos registros con indices, como por ejemplo las llaves primarias.
	
	* Cluster: Especificamos al motor de base de datos que reorganice la información en el disco.
	
	
	

* **Angel de Jesus Quintero Pereira** (1) [1042484](https://platzi.com/comentario/1042484/) 

	En la pestaña VACUUM hay tres opciones para hacer mantenimiento, FULL se eliminará todos los indices y filas que ya no son aplicables, FREEZE, incluye que durante ese proceso se congelará la tabla o la bases de datos mientras se hace este proceso. ANALYZE solo analiza la bd.

* **Angel de Jesus Quintero Pereira** (1) [1042460](https://platzi.com/comentario/1042460/) 

	Una limpieza full es necesario cuando tengamos una tabla grande y tengamos problema de indexación, esto se refiere a que, En el momento de hacer la consulta se demore mucho tiempo.

* **Angel de Jesus Quintero Pereira** (1) [1042437](https://platzi.com/comentario/1042437/) 

	Postgres tiene dos niveles de limpieza son: 1-Liviano que se ejecuta en segundo plano y lo hace constantemente. 2-Full el cual es capaz de bloquear las tablas para hacer la limpieza y luego la desbloquea. En estas actividades no debemos involucrarnos al menos que sea necesario

* **Angel de Jesus Quintero Pereira** (1) [1042408](https://platzi.com/comentario/1042408/) 

	Postgres desarrolla el mantenimiento de manera activa y sin consentimiento del usuario. El mantenimiento consiste en quitar todas las filas, items y columnas que no están funcionando correctamente y postgres lo hace para optimizar todos los servicios ya por trabajar rápido ocurre

* **SergioRubiano** (1) [983283](https://platzi.com/comentario/983283/) 

	Les recomiendo que lean la lectura que están el los archivos de enlaces, que buena información

* **dbzdavidbaez** (1) [73848](https://platzi.com/comentario/842381/) 
Uno debe crear indices en postgres o el motor crea todos los indices que necesita la tabla para satisfacer las consultas? Se puede analiz...

	* **Oz** [73848] (3)

		Si , nosotros debemos crear los indices, Postgresql trata de hacer lo mejor que puede con la herramientas que les des, si no tiene ídices entonces no podrá usarlos. Para saber cuando crear índices puedes basarte en 2 consejos prácticos, úsalos en columnas q uses para crizar 2 tablas y en columnas que aparezcan en la mayoría de tus consultas.

## 0290. Introducción a Réplicas [24197](https://platzi.com/clases/1480-postgresql/24197-introduccion-a-replicas/)

### Descripción:


### Comentarios:

* **dbzdavidbaez** (4) [842396](https://platzi.com/comentario/842396/) 

	Todo para mejorar el rendimeinto de nuestros aplicativos y mejorar la experiencia de nuestro cliente final

* **Wilson Marino Pablo Mendez** (3) [964891](https://platzi.com/comentario/964891/) 

	Información enriquecedor!!

* **jmontesl** (2) [839677](https://platzi.com/comentario/839677/) 

	Justo lo que estaba necesitando. Gracias caballeros!!!

* **Leonel Vega Vargas** (2) [76622](https://platzi.com/comentario/890508/) 
Si ejecuto un mantenimiento en modo VACUUM no eliminara registros cierto?

	* **Jean Carlos Nuñez Hernandez** [76622] (1)

		No entiendo bien la pregunta

* **Angel de Jesus Quintero Pereira** (1) [1042397](https://platzi.com/comentario/1042397/) 

	¿Cuál es la estrategia para afrontar el bloque? Tener más de una de datos, tener una base de dato donde se hacen todas las modificaciones y tener una bases de datos donde solamente se hacen las lecturas.

	* **Oz** [1042397] (1)

		Exacto, tener una base de datos que recibe los insert, update y delete, y tener otra aparte para los selects

* **Angel de Jesus Quintero Pereira** (1) [1042367](https://platzi.com/comentario/1042367/) 

	Cuando la aplicación crece a nivel exponencial,nos vamos a encontrar con límites físicos en el servidor que está nuestra aplicación. También sucede que, Sí ocurren muchas lecturas y escritura en una tabla esta puede ser bloqueda por postgres. Aquí es donde las entra las replicas

* **vegadevh** (1) [998034](https://platzi.com/comentario/998034/) 

	La verdad nunca me habia puesto a pensar en esto 😮 no tenia idea

* **andoni** (1) [877207](https://platzi.com/comentario/877207/) 

	Qué interesante 😮

* **David Rueda** (1) [854930](https://platzi.com/comentario/854930/) 

	Tema muy interesante!

* **Leonel Vega Vargas** (1) [76623](https://platzi.com/comentario/890509/) 
No escucha bien, en el minuto 0:44, no pueden ser sobrepasados por…?

	* **fernandajofili (Platzi)** [76623] (1)

		Yo escuché “por más que quieras”

## 0300. Implementación de Réplicas en Postgres [24198](https://platzi.com/clases/1480-postgresql/24198-implementacion-de-replicas-en-postgres/)

### Descripción:


### Links:

* [Multi-Cloud PaaS with Java, PHP, Node.js, Docker & Kubernetes Hosting | Jelastic](https://jelastic.com)

* [Cloudjiffy](https://app.cloudjiffy.co/)

### Comentarios:

* **andoni** (7) [877264](https://platzi.com/comentario/877264/) 

	Para poder activar la ipv4 parece que es necesario pagar 😦  
	![v.JPG](https://static.platzi.com/media/user_upload/v-a13949f2-561f-4d92-bb36-285645d541f1.jpg)

* **carlossanchez27** (4) [907952](https://platzi.com/comentario/907952/) 

	Alguien sabe por qué sale este error al intentar crear el servidor en pgAdmin¿?  
	![Error_pg.jpg](https://static.platzi.com/media/user_upload/Error_pg-a300c1ab-9328-48e8-863c-24fcf7628942.jpg)

	* **Joan Federico Marin Ruiz** [907952] (1)

		yo ando con el mismo error

	* **Abril Darynka Tapia Sosa** [907952] (1)

		Me paso igual

	* **Laura Tristán** [907952] (1)

		Me ocurre lo mismo. ¿Alguien ha encontrado la solución?

	* **Laura Tristán** [907952] (4)

		Esto ocurre porque no podemos usar la ipv4 publica, a no ser que paguemos por usar CloudJiffy. Creo que deberían actualizar esta clase de manera que la podamos hacer sin necesidad de pagar.

	* **SergioRubiano** [907952] (1)

		Esto ocurre por que no podemos activar la ipv4, en conclusión toca pagar el servicio de Cloudjiffy

	* **hgarciac** [907952] (1)

		Aunque no lo he puesto en practica en el video indican que debemos activar la opción IPv4 para poder conectarnos a la base de datos a traves de una IP de lo contrario se puede usar con la URL más larga. Minuto 1:35

	* **Oz** [907952] (1)

		Bueno, para el éste momento Cloudjiffy no permite ipv4 en la versión free, pero existen más parners de jelastic que si lo permiten, lo podemos ver en:  
		<https://jelastic.cloud/>

* **elvis.sanchez** (4) [835701](https://platzi.com/comentario/835701/) 

	Like.

* **JOSE PEREZ** (3) [836946](https://platzi.com/comentario/836946/) 

	Estimados,
	
	pueden hacer un ejemplo(video) de replicación sincrona y asincrona en linux?
	
	debian por ejemplo.
	
	Gracias.

	* **Oz** [836946] (2)

		Si te das cuenta, todo lo hicimos por archivos de configuración y ejecutando un comando en consola de linux, la interfaz de jelastic ayuda a ver las cosas más “bonitas” pero todo el proceso lo hicimos a mano. La única diferencia eso si, es que jelastic crea un usuario y clave de manera predeterminada que luego es enviado por correo, al hacerlo todo por consola de linux, tú mismo creas el usuario y la clave, de resto igual.

* **Peter_g** (2) [1085836](https://platzi.com/comentario/1085836/) 

	El ejercicio fue excelente . Lo ideal es llevarlo a la vida real y hacer pruebas en caliente

* **jaime-pinto-a** (2) [874700](https://platzi.com/comentario/874700/) 

	Este Capitulo de replicas, es excelente, proximos proyectos como base de datos, elijo Postgresql

* **dbzdavidbaez** (2) [842445](https://platzi.com/comentario/842445/) 

	Muy sencillo y util.

* **Santiago Ricci** (2) [840970](https://platzi.com/comentario/840970/) 

	Excelente clase.

* **JOSE PEREZ** (2) [836944](https://platzi.com/comentario/836944/) 

	Estimados,
	
	Podrían hacer demos sin necesidad de herramientas externas replicación de servidor entero de BD y/o tablas en especifico. Todo sobre linux.
	
	Gracias

	* **jmontesl** [836944] (2)

		La única diferencia es que el usuario de replicación que crea al inicio, que es webadmin, ya te lo crea la aplicación externa, por lo demás todo es igual que en cualquier Linux. Es mas diría que en lo que te desplegada el postgresSQL es un debian.

* **Joseph Santibáñez** (2) [82609](https://platzi.com/comentario/1008933/) 
Postgres aguanta activo-activo???

* **guillermolamberto** (2) [74930](https://platzi.com/comentario/861411/) 
Buenos dias, cuando tildo la opcion de ipv4 me pide que haga un upgrade account cosa que es paga. como se puede hacer si ser pago? muchas...

	* **Joan Federico Marin Ruiz** [74930] (1)

		igual me sale pagando, que se puede realizar ahi?

* **Kelvin Thony Meza Espiritu** (1) [1033629](https://platzi.com/comentario/1033629/) 

	En Postgres, ¿que son replicaciones lógicas? y ¿Cómo funciona?

* **SergioRubiano** (1) [983345](https://platzi.com/comentario/983345/) 

	Que interesante esta clase, a un que no pude seguir la practica (No me pude conectar) segun lo que entendi las replicas son muy importantes

* **Marco Antonio González Arellano** (1) [890416](https://platzi.com/comentario/890416/) 

	Qué buena clase y qué sencillo es implementar réplicas en postgresql.

* **Luis Alberto Lazcano Cruz** (1) [87342](https://platzi.com/comentario/1118165/) 
¿Para hacer una replica se tiene que tener la misma versión postgres en master y en la replica?

* **Joan Federico Marin Ruiz** (1) [79310](https://platzi.com/comentario/937928/) 
buenos dias. me sale este error al realizar la creacion en pgAdmin del server Unable to connect to server: timeout expired.

	* **Miguel Figueroa Cumana** [79310] (1)

		Hace falta más información para poder ayudarte. Cómo es tu entorno de trabajo?

* **aesn_sas** (1) [78425](https://platzi.com/comentario/920899/) 
Necesariamente la bd replica debe de estar configurada en otro servicio? o pueden funcionar bajo el mismo servicio?

* **dvillalobos** (1) [74376](https://platzi.com/comentario/851744/) 
Hola, no logré notar en dónde se le “dice” a REPLICA que debe ir a buscar datos a MASTER o es más bien que MASTER le manda los datos a RE...

	* **Oz** [74376] (1)

		Hola, cuando se crea la base de datos principal y la base de datos de replica, las dos funcionan como master al principio, luego toca indicarle a MASTER que va a recibir peticiones de replica y a REPLICA indicarle que va a estar en modo replica, indicarle también cual es su master y ahi viene el tema de los datos, ese comando BORRA los datos de REPLICA para que ella inicie de 0 a traer datos de MASTER.

* **dbzdavidbaez** (1) [73853](https://platzi.com/comentario/842447/) 
Esta replica nos pude funcionar como alta disponibilidad en base de datos?

	* **Oz** [73853] (2)

		Tal vez, si la principal falla, puedes cambiar la configuración de la réplica para que siga funcionando cómo maestra, pero no puede volver a su estado anterior de réplica fácilmente, así que si podría salvarnos en ciertas ocaciones.

* **Kelvin Thony Meza Espiritu** (0) [77007](https://platzi.com/comentario/896723/) 
Buenas tardes, puedo hacer replica en tiempo real entre dos motores de base de datos distintos? Especificamente Postgres a Oracle

	* **jcruzquintero** [77007] (2)

		Las replicas se realizan en el mismo motor de base de datos, postgresql <-> postgresql, oracle <-> oracle. Adicionalmente deben en los dos servidores la versión del motor de base de datos debe ser igual.

## 0310. Otras buenas prácticas [24199](https://platzi.com/clases/1480-postgresql/24199-otras-buenas-practicas/)

### Descripción:


### Comentarios:

* **Salvador Jose Campanella Salas** (4) [839884](https://platzi.com/comentario/839884/) 

	Hola siento que esto que explican es de gran utilidad pero debieron explicarlo mejor,
	
	Usar algun diagrama o algo seria genial para ejemplificar.
	
	Un saludo

	* **Oz** [839884] (4)

		En el menú de enlaces está el detalle técnico y el paso a paso, seguro te servirá.

* **SOFTDYNAMIC** (2) [990248](https://platzi.com/comentario/990248/) 

	It sounds very interesting, but there is not a visual example 😦

* **Francisco de Castro** (1) [1096231](https://platzi.com/comentario/1096231/) 

	y por ejemplo en el beggin transaction se podria hacer:
	
	BEGGIN TRANSACTION;  
	ALTER TABLE estadistica RENAME TO estadistica_offload;  
	CREATE TABLE estadisitica (…);  
	COMMIT;
	
	??

* **eduardo-zepeda** (1) [1087849](https://platzi.com/comentario/1087849/) 

	El documento en archivos y enlaces es necesario para entender mucho mejor los conceptos del video.

* **jcavelez** (1) [1026157](https://platzi.com/comentario/1026157/) 

	Excelente documento. Tan explicativo como los videos.

* **dbzdavidbaez** (1) [842455](https://platzi.com/comentario/842455/) 

	Gracias por el TIP. Lastima que no se grabo el ejemplo en vivo.

	* **Oz** [842455] (4)

		No está el ejemplo en vivo pero está el detalle del proceso en el menú de enlaces, lo viste? qué te pareció?

## 0320. Cierre del curso [24200](https://platzi.com/clases/1480-postgresql/24200-cierre-del-curso/)

### Descripción:


### Comentarios:

* **dbzdavidbaez** (6) [842692](https://platzi.com/comentario/842692/) 

	Excelente curso. Gracias
	
	Seria interesante hacer un curso intermedio o avanzado de postresql

	* **JUAN CARLOS PARRA GALAN** [842692] (3)

		Siii seria genial!! Super necesario el curso intermedio o avanzado de Postresql

* **TUDz** (4) [836825](https://platzi.com/comentario/836825/) 

	Excelente curso Oswaldo! Eres un fregón! Gracias por compartir el conocimiento ahora a ponerlo en práctica.

* **SergioRubiano** (2) [983360](https://platzi.com/comentario/983360/) 

	Gracias Osvaldo, sin duda alguna eres un buen profesor, explicaste cada termino y cada momento con una pasión y con mucha dedicación, espero verte pronto en un nuevo curso.

* **Nagcely Mendoza** (2) [963063](https://platzi.com/comentario/963063/) 

	Excelente curso, gracias Osvaldo.

* **Wilson Gonzalo Penagos Morales** (2) [933937](https://platzi.com/comentario/933937/) 

	gracias profe muy bueno el curso

* **sebastiancastillo83z** (2) [932264](https://platzi.com/comentario/932264/) 

	Muy buen curso, realmente Postgres es un lujo. Su utilidad y complejidad lo hace una herramienta poderosa. Gracias Osvaldo!

* **Marco Antonio González Arellano** (2) [890420](https://platzi.com/comentario/890420/) 

	Genial el curso, muchos buenos tips que seguro me servirán, de hecho ya empezando el año que regrese de vacaciones comenzaré a implementar.
	
	Gracias!

* **andoni** (2) [877319](https://platzi.com/comentario/877319/) 

	Muchas gracias por el curso! Fue muy interesante!!

* **Didier Zúñiga** (1) [1071572](https://platzi.com/comentario/1071572/) 

	Hola chicos
	
	Si mi app maneja info de varias empresas, como recomiendan crear la base de datos de cada una de ellas?
	
	  1. Todo en una misma base de datos nombrando la tabla de cada empresa con un prefijo, por ejemplo:  
	_EmpresaA: Prefijo para cada tabla "ea_empleados"  
	EmpresaB: Prefijo para cada tabla "eb_empleados"_  
	Y por medio del backend se consultan las tablas de una empresa u otra.
	
	  2. Una base de datos distinta para cada empresa.
	
	
	
	
	Gracias de antemano.

	* **Diego Alexander Forero Higuera (Platzi)** [1071572] (2)

		Hola, esto te puede ayudar a decidir lo mejor para tu app. <https://platzi.com/blog/multi-tenant-que-es-y-por-que-es-importante/>

	* **Didier Zúñiga** [1071572] (1)

		Perfecto, muchas gracias Gollum

* **CARLOS DAVID MARCIGLIA GOMEZ** (1) [1039888](https://platzi.com/comentario/1039888/) 

	Muy buen curso, algunas dudas me fueron resultas, ahora a poner en practica lo aprendido en mi Startup.

* **miguelangelpglez** (1) [995780](https://platzi.com/comentario/995780/) 

	Me fascino empezar con PostgreSQL.

* **Manuel_Herrera** (1) [987729](https://platzi.com/comentario/987729/) 

	Increíble curso !!

* **Miguel Ángel Muñoz Pozos** (1) [948965](https://platzi.com/comentario/948965/) 

	Gracias por el curso muy bueno creo que usare PostgreSQL

