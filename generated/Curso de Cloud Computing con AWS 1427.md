[Curso de Cloud Computing con AWS 1427](https://platzi.com/cursos/aws-computo)

# Presentación [2977]

## 0010. Agenda [15376](https://platzi.com/clases/1427-aws-computo/15376-agenda/)

### Descripción:


Esto es lo que verás en este curso de **Cloud Computing con AWS:**

* **Introducción:** AWS cómputo se refiere a cualquier producto de AWS que nos permite servir algún archivo, procesar o calcular algo.
* **EC2:** Son máquinas virtuales que nos renta Amazon por segundo. Hay Linux o Windows. Podemos elegir número de CPUs, RAM, discos duros, tipo de conectividad, entre otras opciones.
* **Lightsail:** Es un producto particular porque es un VPS sobre Amazon similar a **Dreamhost** o **Digital Ocean** estando en la red de Amazon conservando los bajos costos de los VPS comerciales.
* **ECR/ECS/EKS:** **ECR** es donde registramos contenedores, **ECS** es el producto de Amazon para Docker y **EKS** es el producto de Amazon para Kubernetes.
* **Lambda:** Es la infraestructura de Amazon para poder correr diferentes funciones.
* **Elastic Beanstalk:** Permite correr diversos software o cargas productivas, pudiendo autoescalar hacia arriba o hacia abajo de manera automática.



Nuestro proyecto será un software que nos permitirá mostrar diferentes citas en pantalla. Cada que recarguemos pantalla veremos una nueva cita.

### Links:

* [Amazon Lightsail](https://aws.amazon.com/es/lightsail/)

* [Amazon ECR | Amazon Web Services](https://aws.amazon.com/es/ecr/)

* [AWS | Gestión de contenedores (ECS) compatible con los de Docker](https://aws.amazon.com/es/ecs/)

* [Amazon EKS – Servicio de Kubernetes administrado](https://aws.amazon.com/es/eks/)

* [AWS | Lambda - Gestión de recursos informáticos](https://aws.amazon.com/es/lambda/)

* [AWS | Elastic beanstalk para aplicaciones web desarrolladas con Java](https://aws.amazon.com/es/elasticbeanstalk/)

### Comentarios:

* **Néstor Antonio Pineda Otero** (5) [438289](https://platzi.com/comentario/438289/) 

	Excelente, me parece que es una muy buena oportunidad para aprender AWS.

	* **Pedro Porras** [438289] (4)

		que bueno que estan sacando mas cursos de AWS y mas detallados.

	* **Brayan Mamani** [438289] (2)

		Esto estará genial !!

* **Ernesto Lázaro Guerrero** (3) [762007](https://platzi.com/comentario/762007/) 
	
	![Captura de Pantalla 2019-10-01 a la\(s\) 13.26.03.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-10-01%20a%20la%28s%29%2013.26.03-2f1376af-8667-4f03-ab0f-1d62e1887b07.jpg)

* **Luis Alejandro Agudelo Alvarez** (3) [546225](https://platzi.com/comentario/546225/) 

	Este curso se ve estupendo !

* **Miguel Celis** (2) [637592](https://platzi.com/comentario/637592/) 

	Wow que todas las introducciones a cursos sean como esta. Me enganchó de una el contenido expuesto por el teacher.

* **Cristian Aguayo Forteza** (1) [1009215](https://platzi.com/comentario/1009215/) 

	Lightsail, VPS, está en la red de amazon, respaldos y costos más bajos.

* **jorge-gianareas** (1) [970652](https://platzi.com/comentario/970652/) 

	EC2: Son máquinas virtuales que nos renta Amazon por segundo.

* **jorge-gianareas** (1) [968380](https://platzi.com/comentario/968380/) 

	ECR/ECS/EKS: ECR es donde registramos contenedores, ECS es el producto de Amazon para Docker y EKS es el producto de Amazon para Kubernetes.  
	Lambda: Es la infraestructura de Amazon para poder correr diferentes funciones.  
	Elastic Beanstalk: Permite correr diversos software o cargas productivas, pudiendo autoescalar hacia arriba o hacia abajo de manera automática.

* **jorge-gianareas** (1) [968379](https://platzi.com/comentario/968379/) 

	Lightsail: Es un producto particular porque es un VPS sobre Amazon similar a Dreamhost o Digital Ocean estando en la red de Amazon conservando los bajos costos de los VPS comerciale

* **jorge-gianareas** (1) [968378](https://platzi.com/comentario/968378/) 

	EC2: Son máquinas virtuales que nos renta Amazon por segundo. Hay Linux o Windows. Podemos elegir número de CPUs, RAM, discos duros, tipo de conectividad, entre otras opciones.

* **juancajamarca** (1) [922707](https://platzi.com/comentario/922707/) 

	Interesante material.

* **carlosantonio_** (1) [796638](https://platzi.com/comentario/796638/) 

	Ese proyecto yo lo realice hace tiempo, aunque sin base de datos solo una listota de frases.

* **Josue Ramos** (1) [620561](https://platzi.com/comentario/620561/) 

	Este Curso tambien esta super interesante. Bendito Sea Dios!!!

* **alexgv04** (1) [67212](https://platzi.com/comentario/719399/) 
que recomiendas para hacer la certificación cloud practitioner 

	* **Rafael Pardo Rodriguez** [67212] (1)

		Estudiar mucho, aws tiene sus propios tutoriales

# EC2 [2978]

## 0020. Introducción a EC2 [15377](https://platzi.com/clases/1427-aws-computo/15377-introduccion-a-ec2/)

### Descripción:


 **¿Qué son los EC2?**

* Son máquinas virtuales, llamadas instancias en Amazon que te van a permitir correr diferentes software en diferentes sistemas operativos con diferentes configuraciones.
* Amazon tiene ya unas imágenes preconfiguradas llamadas **AMIs** .
* Podremos seleccionar diferentes tamaños de CPU´s y su cantidad, cantidad de RAM, espacio en disco, diferente conectividad, entre otros. El costo depende de las capacidades que especifiquemos.



**Arquitectura de EC2:**

Podemos crear diferentes imágenes, por ejemplo una con **Ubuntu** , configurando o instalando diferentes software, finalmente haciendo una imágen con ello. Las imágenes van hacia una instancia de **EC2** , seleccionando capacidad que necesitamos en la máquina virtual.  
Asociado a esto, están los temas de redes como los grupos de seguridad, los balanceadores de cargas hacia los cuales llega el tráfico de la web externo como interno.  
De storage tenemos uno que es efímero que sólo existe mientras la máquina esté prendida, y el otro es un bloque elástico que permanece a pesar de borrar la máquina y de él podemos hacer copias en caso de que vaya evolucionando otro proyecto.

### Links:

* [Amazon EC2](https://aws.amazon.com/ec2/)

### Comentarios:

* **carlossotoperez** (6) [451355](https://platzi.com/comentario/451355/) 

	podrian subir la imagen de arquitectura ec2 a los archivos ?

	* **rogerdavila** [451355] (1)

		En la clase anterior esta la presentación completa, ahí puedes encontrar la imagen
		
		Saludos!

* **Ernesto Lázaro Guerrero** (5) [762065](https://platzi.com/comentario/762065/) 

	Arquitectura Elastic Compute Cloud (EC2)
	
	![Captura de Pantalla 2019-10-01 a la\(s\) 14.02.52.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-10-01%20a%20la%28s%29%2014.02.52-b8250b4f-5a15-4798-ba18-2357a448803b.jpg)

* **Gary Mikel Astorga Agüero** (3) [879974](https://platzi.com/comentario/879974/) 

	Aquí dejo unas apuntes de la clase, cualquier corrección me comentan porfa.  
	**Notas:**  
	**AWS:** Amazon Web Service  
	**EC2:**  
	Son maquinas virtuales [llamadas instancias]. Permite correr diferentes software en diferentes sistemas operativos y en diferentes configuraciones de maquinas.  
	**AMIs:** Son las imágenes pre configuradas que tiene   
	Amazon.  
	Tiene varias configuraciones de CPU, memora, espacio en  
	disco, tipo de conectividad, diversas formas para  
	conectarnos a ella. [Dependiendo de que la capacidad se tendrá  
	el costo]
	
	_Ephemeral Storage:_ Mientras la maquina virtual este prendida va a existir y cuando la apaguemos o destruyamos, va a desaparecer.  
	_Elastic Block Storage:_ Este permanece a pesar que borremos la maquina virtual, podemos hacer copias, restaurar o ir guardando en caso que este evolucionando algún proyecto o alguna configuración de las maquinas.

* **jorge-gianareas** (1) [968383](https://platzi.com/comentario/968383/) 

	Arquitectura de EC2:
	
	Podemos crear diferentes imágenes, por ejemplo una con Ubuntu, configurando o instalando diferentes software, finalmente haciendo una imágen con ello. Las imágenes van hacia una instancia de EC2, seleccionando capacidad que necesitamos en la máquina virtual.  
	Asociado a esto, están los temas de redes como los grupos de seguridad, los balanceadores de cargas hacia los cuales llega el tráfico de la web externo como interno.  
	De storage tenemos uno que es efímero que sólo existe mientras la máquina esté prendida, y el otro es un bloque elástico que permanece a pesar de borrar la máquina y de él podemos hacer copias en caso de que vaya evolucionando otro proyecto.

* **jorge-gianareas** (1) [968382](https://platzi.com/comentario/968382/) 

	¿Qué son los EC2?
	
	Son máquinas virtuales, llamadas instancias en Amazon que te van a permitir correr diferentes software en diferentes sistemas operativos con diferentes configuraciones.  
	Amazon tiene ya unas imágenes preconfiguradas llamadas AMIs .  
	Podremos seleccionar diferentes tamaños de CPU´s y su cantidad, cantidad de RAM, espacio en disco, diferente conectividad, entre otros. El costo depende de las capacidades que especifiquemos.

* **juancajamarca** (1) [922726](https://platzi.com/comentario/922726/) 

	El concepto de imágenes es muy similar a como se maneja en Docker.

* **Josue Ramos** (1) [620566](https://platzi.com/comentario/620566/) 

	Wow muy buena clase

* **Luis Alejandro Agudelo Alvarez** (1) [546231](https://platzi.com/comentario/546231/) 

	Gracias.

## 0030. Tipos de instancias al momento de crear un EC2 [15379](https://platzi.com/clases/1427-aws-computo/15379-tipos-de-instancias/)

### Descripción:


Cosas a tener en cuenta al momento de crear tu **EC2** :

* Hay ocasiones en las cuales puedes entrar y no ver tus instancias creadas. Esto puede pasar porque no seleccionaste la región adecuada o la que tenías al momento de crearlas.
* Al momento de crear las imágenes se recomienda usar la de Amazon ya que viene actualizada con los últimos drivers.
* La sección **T2/T3 Unlimited** en la configuración de la instancia nos sirve si necesitamos mucha CPU o red, al habilitarla, Amazon nos lo dará sin límite. El problema es que tiende a ser más costoso.
* Es muy útil al momento de poner tag que se use uno aunque sea un nombre para recordar para qué sirve la máquina.
* Para conectarnos a la máquina debemos crear una llave. Es importante guardarla en un lugar seguro haciéndole una copia de seguridad ya que si no se tiene la llave, no es posible conectarse por medio de SSH.



### Links:

* [AWS | Elastic compute cloud (EC2) de capacidad modificable en la nube](https://aws.amazon.com/es/ec2/)

### Comentarios:

* **Luis Guillermo Pardo Fonseca** (5) [503702](https://platzi.com/comentario/503702/) 

	Se escucha demasiado bajo 😦

	* **Luis Alejandro Agudelo Alvarez** [503702] (1)

		Yo lo escucho perfecto

* **johncastillotellez7** (3) [838249](https://platzi.com/comentario/838249/) 

	el video tiene muy bajo volumen. por favor mejorarlo

* **AlejandroIscop** (3) [706747](https://platzi.com/comentario/706747/) 
NO, NO, NO SE ESCUCHA aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa, es muy bajo el volumen

	* **Ernesto Lázaro Guerrero** [706747] (1)

		Todavía sigue bajo el volumen

* **jorge-gianareas** (1) [968388](https://platzi.com/comentario/968388/) 

	Es muy útil al momento de poner tag que se use uno aunque sea un nombre para recordar para qué sirve la máquina.  
	Para conectarnos a la máquina debemos crear una llave. Es importante guardarla en un lugar seguro haciéndole una copia de seguridad ya que si no se tiene la llave, no es posible conectarse por medio de SSH.

* **jorge-gianareas** (1) [968387](https://platzi.com/comentario/968387/) 

	La sección T2/T3 Unlimited en la configuración de la instancia nos sirve si necesitamos mucha CPU o red, al habilitarla, Amazon nos lo dará sin límite. El problema es que tiende a ser más costoso.

* **jorge-gianareas** (1) [968386](https://platzi.com/comentario/968386/) 

	Al momento de crear las imágenes se recomienda usar la de Amazon ya que viene actualizada con los últimos drivers.

* **jorge-gianareas** (1) [968385](https://platzi.com/comentario/968385/) 

	Hay ocasiones en las cuales puedes entrar y no ver tus instancias creadas. Esto puede pasar porque no seleccionaste la región adecuada o la que tenías al momento de crearlas.

* **MoisesH** (1) [870471](https://platzi.com/comentario/870471/) 

	Hola a Todos,
	
	consulta, si yo requiero subir archivos al S3 para luego consultarlos mediante ATHENA,
	
	¿es necesario crear una instancia de EC2 para que funcione mi S3 y ATHENA?

* **carlosbazanhuaman** (1) [822381](https://platzi.com/comentario/822381/) 

	Buena explicacion del servicio ec2 y del proceso para crear instancias, seria bueno una prueba con servicios que cobran y hacer una prueba para ver el costo aproximado de algun experimento. Saludos.

* **karkastell** (1) [690517](https://platzi.com/comentario/690517/) 

	Si tengo un server “plantilla” con su sistema operativo y software base instalado, es mejor tenerlo como AMI o es mejor tener un EBS y generar snapshot sobre este?

	* **juancajamarca** [690517] (1)

		Si vas a crear frecuentemente instancias con esa base, es mejor tenerlo como AMI.

* **Ramón Isidro García Esquer** (1) [630856](https://platzi.com/comentario/630856/) 

	¿Cómo se elimina una maquina virtual?

	* **Diego Alexander Forero Higuera (Platzi)** [630856] (5)

		Hola entras al panel de aws, buscas EC2 y en el menu de la izquierda seleccionas instancias, en este punto ves todas las instancias que tienes creadas la seleccionas en el cuadrado de la izquierda y en el menu de acciones que aparece en la parte superior puedes eliminar la instancia seleccionando la opción **instance state** y luego **terminate**
		
		![aws.png](https://static.platzi.com/media/user_upload/aws-fa39363c-13f6-4987-983d-bbc8724e19f7.jpg)

* **Luis Alejandro Agudelo Alvarez** (1) [546249](https://platzi.com/comentario/546249/) 

	Cual es la mejor región para una web o un ecommerce en colombia ?

	* **rogerdavila** [546249] (5)

		Sería en São Paulo, creo que es la unica región en America del Sur de AWS.
		
		Si estas en Colombia o tienes una pc en Colombia, puedes dar clic sobre la siguiente liga:  
		<https://ping.psa.fun/>
		
		Esta página mide la latencia que hay desde el lugar en el que diste clic hasta todas las regiones de AWS, y te indica en verde cual es la mejor.
		
		Espero te sirva!

	* **Cristian David Franco Garcia** [546249] (1)

		Virginia del norte. <https://aws.amazon.com/about-aws/global-infrastructure/>

* **vcentt-lopez** (1) [539207](https://platzi.com/comentario/539207/) 

	Me parece que algo afecto a DDOS de Clodflare que metieron, ya no puedo ver los videos, dice “Failed to load resource: the server responded with a status of 503 ()”

* **Néstor Antonio Pineda Otero** (1) [438489](https://platzi.com/comentario/438489/) 

	Muy bien. Ya tenemos desplegada nuestra AMI con las configuraciones indicadas y corriendo…

## 0040. Instalación del proyecto [15378](https://platzi.com/clases/1427-aws-computo/15378-instalacion-del-proyecto/)

### Descripción:


Cosas a tener en cuenta al momento de instalar tu proyecto:

* Si tienes Linux o MAC, ya cuentas con la terminal para poderte conectar por medio de SSH; si tienes Windows, es necesario usar un software como MobaXterm que es gratis para uso personal.
* El comando que debes usar es “sudo apt install apache2 git libapache2-mod-php -y”
* Si acabas de iniciar tu máquina, es posible que no encuentre los paquetes, ya que los DNS no son los correctos. Con “apt-get update” lo solucionas.
* La dirección del repositorio usado en clase es: <https://github.com/mauropm/quotes-generator>



### Links:

* [MobaXterm free Xserver and tabbed SSH client for Windows](https://mobaxterm.mobatek.net/)

* [GitHub - mauropm/quotes-generator: A simple PHP application to generate a random quote as HTML.](https://github.com/mauropm/quotes-generator)

* [Apache2 Ubuntu Default Page: It works Momo!](https://annex.exploratorium.edu/)

### Comentarios:

* **juancajamarca** (4) [923169](https://platzi.com/comentario/923169/) 

	Para los usuarios de Linux o Mac, se conectan con el siguiente comando:
	``` 
	    ssh -i <path_del_archivo.pem> ubuntu@<dirección_IP_de_la_instancia>
	    
	```

* **Juan Jose Gonzalez Vera** (3) [458109](https://platzi.com/comentario/458109/) 

	Para Windows, si instalas git (<https://git-scm.com/>) ya tienes acceso a SSH por línea de comandos.

* **Néstor Antonio Pineda Otero** (3) [438533](https://platzi.com/comentario/438533/) 

	Perfecto, ya desplegando la aplicación <http://18.218.201.118/> muy interesante el ejercicio.

* **jorge-gianareas** (2) [968394](https://platzi.com/comentario/968394/) 

	El comando que debes usar es “sudo apt install apache2 git libapache2-mod-php -y”

* **Roger Vilà** (2) [848131](https://platzi.com/comentario/848131/) 

	Para los usuarios Windows existe otra herramienta a parte de MobaXterm, que es PuTTY <https://www.putty.org>

	* **fidekof** [848131] (3)

		Tambien puedes instalar un linux subsystem en windows y usas directamente la terminal de ubuntu desde windows. es muyb facil hacer esto

* **Jose Luis Campos Bautista** (1) [1059478](https://platzi.com/comentario/1059478/) 

	Podemos revisar el estatus de Apache utilizando
	``` 
	    systemctl status apache2 
	    
	```

* **EPadronU23** (1) [1040960](https://platzi.com/comentario/1040960/) 

	No es necesario convertirse en root
	``` 
	    $ sudo su
	    
	```
	
	Basta con
	``` 
	    $ sudo apt update
	    $ sudo apt install apache2 git libapache2-mod-php -y
	    
	```

* **luisgallegosg** (1) [1015071](https://platzi.com/comentario/1015071/) 

	Excelente explicacion!

* **jorge-gianareas** (1) [968396](https://platzi.com/comentario/968396/) 

	Si acabas de iniciar tu máquina, es posible que no encuentre los paquetes, ya que los DNS no son los correctos. Con “apt-get update” lo solucionas.

* **jorge-gianareas** (1) [968392](https://platzi.com/comentario/968392/) 

	Si tienes Linux o MAC, ya cuentas con la terminal para poderte conectar por medio de SSH; si tienes Windows, es necesario usar un software como MobaXterm que es gratis para uso personal.

* **johncastillotellez7** (1) [842078](https://platzi.com/comentario/842078/) 

	when I was 5 years old, my mother always told me that happiness was the key to life. when I went ot school, they asked me what I wanted to be when I grew up. I wrote down ‘happy’. they told me I didnt understand the assignment, and I told them they didnt understand life.  
	john lennon

* **bewe** (1) [840728](https://platzi.com/comentario/840728/) 

	<https://www.youtube.com/watch?v=wBj-RvMHaa4> conexión con la instancia de awz en mac.

* **johncastillotellez7** (1) [831240](https://platzi.com/comentario/831240/) 
Genial, Temas bien interesantes y utiles.

	* **johncastillotellez7** [831240] (1)

		“sudo apt install apache2 git libapache2-mod-php -y”

	* **johncastillotellez7** [831240] (1)

		-y instala todo sin que te pida permiso. asi que tenerlo presente

	* **johncastillotellez7** [831240] (1)

		apt-get update, este refersca todas las fuentes y origenes de los packages.

	* **johncastillotellez7** [831240] (1)

		git close <https://github.com/mauropm/quotes-generator> enter

	* **johncastillotellez7** [831240] (1)

		una vez esta en el archivo de php para salir dar esc :q and then you are out!!

	* **johncastillotellez7** [831240] (1)

		sudo su  
		copy : cp index.php quotes.txt /var/www/html/

* **Ernesto Lázaro Guerrero** (1) [763629](https://platzi.com/comentario/763629/) 

	Falto la versión para hacerlo en una Mac. =(

* **Elias Ojeda Medina** (1) [728759](https://platzi.com/comentario/728759/) 

	Comandos:  
	sudo su  
	apt-get update  
	sudo apt install apache2 git libapache2-mod-php -y  
	git clone <https://github.com/mauropm/quotes-generator>  
	cp index.php quotes.txt /var/www/html/

* **odortega** (1) [598177](https://platzi.com/comentario/598177/) 

	cd /var/www/html --> open htdocs apache's folder

* **odortega** (1) [598172](https://platzi.com/comentario/598172/) 

	exit pwd To leave root user and comeback to current user

* **odortega** (1) [598171](https://platzi.com/comentario/598171/) 

	vi --> to edit text file esc :q --> to exit without save changes

* **odortega** (1) [598161](https://platzi.com/comentario/598161/) 

	Command to grant root access to current user

* **OSCAR ALFREDO CHAFLOQUE TAMPECK** (1) [568504](https://platzi.com/comentario/568504/) 

	Error al intentar conectar con mobaxterm. por servicio ayuda
	
	Session stopped  
	\- Press <return> to exit tab  
	\- Press R to restart session  
	\- Press S to save terminal output to file
	
	Network error: Connection timed out

	* **Diego Alexander Forero Higuera (Platzi)** [568504] (3)

		Revisa que estés accediendo a la ip correcta, no se puede conectar a esa ip y por eso da time out porque no responde nada.

	* **jczaragoza** [568504] (1)

		Recuerda que cada que detienes una instancia y la inicias cambia la ip publica

* **OSCAR ALFREDO CHAFLOQUE TAMPECK** (1) [556414](https://platzi.com/comentario/556414/) 

	how to solve this when i try to enter
	
	Session stopped  
	\- Press <return> to exit tab  
	\- Press R to restart session  
	\- Press S to save terminal output to file
	
	Network error: Connection timed out

	* **jczaragoza** [556414] (1)

		Verifica tu IP publica

* **Raul Villca** (1) [541636](https://platzi.com/comentario/541636/) 

	Una pregunta… Cuando agregaste el Storage, viste que ahi se pueden agregar mas datastore. En ese momento te deja hacer configuración para redundancia? o donde podría realizarlo?

* **Raul Villca** (1) [540462](https://platzi.com/comentario/540462/) 

	El repositorio es privado? no encuentra el proyecto

	* **Diego Alexander Forero Higuera (Platzi)** [540462] (1)

		No, el enlace es <https://github.com/mauropm/quotes-generator> ya esta corregido en la descripción.

* **Nestor Alfonso Portela Rincón** (1) [511271](https://platzi.com/comentario/511271/) 

	me corriguen si me equivoco. Pero hay que tener en cuenta que los snapshots son incrementales, esto quiero decir que aunque tu volumen es de 8 GB, el snapshot solo será del espacio que esta siendo usado, si un mes después ya haces uso de 1GB más y haces tu snapshot, entonces esa GB se agrega al snapshot anterior o algo así. es que no lo ví en esta explicación y me parece importante tener en cuenta esto.

* **Néstor Antonio Pineda Otero** (1) [438500](https://platzi.com/comentario/438500/) 

	sudo apt install apache2 git libapache2-mod-php -y

* **Néstor Antonio Pineda Otero** (1) [438314](https://platzi.com/comentario/438314/) 

	En el ejercicio en particular, que función cumple el Dockerfile?

	* **Felipe Acosta** [438314] (1)

		Supongo que es para usarlo en el curso pero cuando estemos en la parte de Docker y Kubernetes

* **Néstor Antonio Pineda Otero** (1) [438305](https://platzi.com/comentario/438305/) 

	<https://github.com/mauropm/quotes-generator> aquí el repositorio.

* **OSCAR ALFREDO CHAFLOQUE TAMPECK** (1) [56759](https://platzi.com/comentario/556414/) 
how to solve this when i try to enter Session stopped \- Press <return> to exit tab \- Press R to restart session \- Press S to save t...

	* **jczaragoza** [56759] (1)

		Verifica tu IP publica

* **juandavidvertel** (0) [823840](https://platzi.com/comentario/823840/) 

	he intentado conectar por ssh y no es posible, haciendo todo paso a paso pero me arroja el siguiente error
	
	Server refused our key
	
	No supported authentication methods available (server sent: publickey,gssapi-keyex,gssapi-with-mic)
	
	──────────────────────────────────────────────────────────────────────────────────────
	
	Session stopped  
	\- Press <return> to exit tab  
	\- Press R to restart session  
	\- Press S to save terminal output to file
	
	──────────────────────────────────────────────────────────────────────────────────────
	
	Session stopped  
	\- Press <return> to exit tab  
	\- Press R to restart session  
	\- Press S to save terminal output to file

## 0050. Imágenes de instancias [15380](https://platzi.com/clases/1427-aws-computo/15380-imagenes-de-instancias/)

### Descripción:


Crear una imagen es muy útil porque cuando quieras crear una instancia nueva, podrás seleccionar la imagen, ahorrándote los pasos de instalación.

Cosas a tener en cuenta al momento de crear imágenes de instancias:

* Creando una imagen te encontrarás con la opción de **No reboot** , si no se selecciona, Amazon va a apagar nuestra instancia para poder hacer la copia; si se selecciona, la instancia no se apagará, corriendo el riesgo de que pueda salir una copia corrupta. Se recomienda reiniciar la instancia.  
Si estás en producción y la instancia que tienes se quedó corta en capacidades, seleccionarías que no se reinicie, para hacer tu copia y crear una nueva instancia con esta copia.
* Si seleccionaste que sí se reiniciara la instancia, tu IP pública cambiará y no podrás conectarte a tu máquina con la anterior IP.



### Links:

* [AWS | Elastic compute cloud (EC2) de capacidad modificable en la nube](https://aws.amazon.com/es/ec2/)

### Comentarios:

* **Jairo  castañeda** (4) [469767](https://platzi.com/comentario/469767/) 

	creo que falto especificar el modelo de cobro de aws por las imagenes , he buscado pero no encuentro información del precio como tal en la doc, lo logico seria que cobrara por el espacio, pero seria bueno aclararlo

* **Juan Sebastian Piedrahita Gonzalez** (3) [659312](https://platzi.com/comentario/659312/) 

	Es interesante también saber que las AMI’s pueden publicarse y compartirse entre cuentas.

	* **Yadfary Irene Montoya Herrera** [659312] (2)

		En el siguiente enlace muestran como puedes compartir una AMI cuentas de AWS específicas.  
		<https://docs.aws.amazon.com/es_es/AWSEC2/latest/UserGuide/sharingamis-explicit.html>

* **Jairo  castañeda** (2) [435643](https://platzi.com/comentario/435643/) 

	hola , pienso hacerlo en un servidor , en el uso letsencrypt, no estoy muy seguro pero al cambiar de ip afectaría el certificado? gracias

	* **DevJose11** [435643] (2)

		no creo

	* **Diego Alexander Forero Higuera (Platzi)** [435643] (4)

		El certificado es asignado al dominio no a la ip, por lo tanto no vas a tener problema, lo que no te funciona es si cambias de dominio.

* **jorge-gianareas** (1) [968408](https://platzi.com/comentario/968408/) 

	Si seleccionaste que sí se reiniciara la instancia, tu IP pública cambiará y no podrás conectarte a tu máquina con la anterior IP.

	* **dahwild1** [968408] (1)

		Lo recomendable es asignarle un IP elástica a la instancia, para que la IP no le cambie.

* **jorge-gianareas** (1) [968407](https://platzi.com/comentario/968407/) 

	Creando una imagen te encontrarás con la opción de No reboot, si no se selecciona, Amazon va a apagar nuestra instancia para poder hacer la copia; si se selecciona, la instancia no se apagará, corriendo el riesgo de que pueda salir una copia corrupta. Se recomienda reiniciar la instancia.  
	Si estás en producción y la instancia que tienes se quedó corta en capacidades, seleccionarías que no se reinicie, para hacer tu copia y crear una nueva instancia con esta copia.

* **jorge-gianareas** (1) [968404](https://platzi.com/comentario/968404/) 

	Crear una imagen es muy útil porque cuando quieras crear una instancia nueva, podrás seleccionar la imagen, ahorrándote los pasos de instalación.

* **Jose Maldonado** (1) [911044](https://platzi.com/comentario/911044/) 

	La imagenes generan costo? cuando imagenes puedo tenerm puede tener la imagen de una imagen ?, saludos

* **johncastillotellez7** (1) [842086](https://platzi.com/comentario/842086/) 

	excelente esa opcion de crear imagines ya preparadas(si las hay) y listas para ahorrar tiempo, que bien aws ec2

* **alexjcm** (1) [769881](https://platzi.com/comentario/769881/) 

	Alguien sabe porque se crea automáticamente una segunda instancia EC2 denominada Miapp-env minutos después de haber creado una instancia manualmente?

* **jheyson7** (1) [764045](https://platzi.com/comentario/764045/) 

	una consulta para un proyecto de transformación comercial que servicios me serian de gran utilidad?

* **DevJose11** (1) [448946](https://platzi.com/comentario/448946/) 

	puedo tener muchas imagenes sin que me cobren? es decir no en instancias

	* **Anibal Fernando Ortega Piedrahita** [448946] (4)

		Si puedes tener varias instancias corriendo sin que te cobren desde que sean t2.micro las cuales son gratis. la capa gratuita te permite utilizar 750 horas de uso. te comparto el siguiente link donde puedes visualizar las capacidades de la capa gratuita <https://aws.amazon.com/es/free/>

	* **Diego Alexander Forero Higuera (Platzi)** [448946] (1)

		Puedes crear imágenes de tus instancias, creo que no cobran, o si cobran es un valor muy bajo por el espacio que usas para las imágenes.

* **AryRosvall** (1) [85255](https://platzi.com/comentario/1069535/) 
En una ambiente de producción, como puedo controlar ese cambio de IPs al reiniciar la instancia para que no se vea afectado mi ambiente, ...

* **AryRosvall** (1) [85254](https://platzi.com/comentario/1069532/) 
En un ambiente de producción, donde no se pueda tener el lujo de apagar la máquina porque no podemos dejar abajo el servicio ¿qué estrate...

* **johncastillotellez7** (1) [73831](https://platzi.com/comentario/842091/) 
hola. todas las instancias asi sean unas mas pesadas que otras, se tarda el mismo tiempo en hacer la imagen que otras en prod? o es mismo...

	* **juancajamarca** [73831] (1)

		El tiempo no es fijo, puede variar dependiendo del espacio ocupado en el disco.

* **DevJose11** (1) [47936](https://platzi.com/comentario/448946/) 
puedo tener muchas imagenes sin que me cobren? es decir no en instancias

	* **Anibal Fernando Ortega Piedrahita** [47936] (4)

		Si puedes tener varias instancias corriendo sin que te cobren desde que sean t2.micro las cuales son gratis. la capa gratuita te permite utilizar 750 horas de uso. te comparto el siguiente link donde puedes visualizar las capacidades de la capa gratuita <https://aws.amazon.com/es/free/>

## 0060. Snapshots y sus operaciones [15381](https://platzi.com/clases/1427-aws-computo/15381-snapshots-y-sus-operaciones/)

### Descripción:


Cuando creas una imagen, vas a poder reproducir esa instancia con el mismo sistema operativo, software y capacidades, estás haciendo una copia del sistema al completo. Si quisieras hacer una copia de una sola de sus características, por ejemplo el software, ahí es donde usarías un **Snapshot” del volumen que es el disco duro. Esto se hace en situaciones especiales para añadir un volumen a una máquina virtual que ya esté corriendo.

Se recomienda crear una imagen nueva o **AMI** cada vez que hagas un cambio mayor en la instancia, versionando a través de imágenes para hacer rollback en caso de que el update falle o la configuración sea errónea.

### Links:

* [Precios de Amazon EBS: Amazon Web Services](https://aws.amazon.com/es/ebs/pricing/)

### Comentarios:

* **Néstor Antonio Pineda Otero** (4) [438540](https://platzi.com/comentario/438540/) 

	Muy interesante para mantener segura la información y acceder a una alta disponibilidad.

	* **Fredy Abel Huanca Torres** [438540] (3)

		es correcto, pero cambie va subiendo la factura.

* **jesus-mendoza536** (3) [435166](https://platzi.com/comentario/435166/) 

	Hola, crear una imagen AMI o un snapshot tiene algún costo?

	* **edisoncastro14** [435166] (8)

		Hola, acá está la lista de precios <https://aws.amazon.com/es/ebs/pricing/>

	* **Brayan Mamani** [435166] (1)

		Genial !!

	* **juancajamarca** [435166] (1)

		Crearlas no, tenerlas sí.

* **jorge-gianareas** (1) [968423](https://platzi.com/comentario/968423/) 

	Se recomienda crear una imagen nueva o AMI cada vez que hagas un cambio mayor en la instancia, versionando a través de imágenes para hacer rollback en caso de que el update falle o la configuración sea errónea.

* **jorge-gianareas** (1) [968420](https://platzi.com/comentario/968420/) 

	Cuando creas una imagen, vas a poder reproducir esa instancia con el mismo sistema operativo, software y capacidades, estás haciendo una copia del sistema al completo. Si quisieras hacer una copia de una sola de sus características, por ejemplo el software, ahí es donde usarías un **Snapshot” del volumen que es el disco duro. Esto se hace en situaciones especiales para añadir un volumen a una máquina virtual que ya esté corriendo.

* **johncastillotellez7** (1) [842097](https://platzi.com/comentario/842097/) 

	que interesante esa opcion, si se corrompen los volumenes , muy buena opcion para minimizar el riesgo de perdida de info

* **jesus-mendoza536** (0) [46736](https://platzi.com/comentario/435166/) 
Hola, crear una imagen AMI o un snapshot tiene algún costo?

	* **edisoncastro14** [46736] (8)

		Hola, acá está la lista de precios <https://aws.amazon.com/es/ebs/pricing/>

## 0070. Configuración de Red [15382](https://platzi.com/clases/1427-aws-computo/15382-configuracion-de-red2381/)

### Descripción:


Cuando reinicies o apagues tu instancia, la IP pública asignada muy probablemente cambiará. En muchos casos esto no es lo deseado y vamos a querer tener una IP que no cambie.  
Amazon tiene la solución a este problema ya que nos ofrece el servicio para comprar una IP estática y asignarla a cualquiera de nuestras instancias.

### Links:

* [Direcciones IP elÃ¡sticas - Amazon Elastic Compute Cloud](https://docs.aws.amazon.com/es_es/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html)

### Comentarios:

* **Dario Jose Vilchez Perozo** (5) [549486](https://platzi.com/comentario/549486/) 

	Es importante crear una IP Elastic si deseas que cada vez que reinicie tu servidor no cambie tu IP Public.

* **jorge-gianareas** (1) [968428](https://platzi.com/comentario/968428/) 

	Amazon tiene la solución a este problema ya que nos ofrece el servicio para comprar una IP estática y asignarla a cualquiera de nuestras instancias.

* **jorge-gianareas** (1) [968426](https://platzi.com/comentario/968426/) 

	Cuando reinicies o apagues tu instancia, la IP pública asignada muy probablemente cambiará. En muchos casos esto no es lo deseado y vamos a querer tener una IP que no cambie.

* **clozarr** (1) [859778](https://platzi.com/comentario/859778/) 

	Cuánto cobra Amazon por tener una IP fija?

	* **Salvador Jose Campanella Salas** [859778] (3)

		Son gratuitas pero ciertas cosas debes tener en cuenta.
		
		Te envió la documentación respectiva  
		<https://aws.amazon.com/es/premiumsupport/knowledge-center/elastic-ip-charges/>

	* **juancajamarca** [859778] (1)

		Creo que no cobra siempre y cuando la estés utilizando.

* **johncastillotellez7** (1) [842109](https://platzi.com/comentario/842109/) 

	importante crear esa elastic ip para el proyecto deseado

* **carlosbazanhuaman** (1) [822451](https://platzi.com/comentario/822451/) 

	funciono bien pero el chiste es que sea estatica.  
	saludos.

* **Raul Villca** (1) [552173](https://platzi.com/comentario/552173/) 

	Poniendo la IP estatica, no puedo entrar a mi servidor. Lo intente con esa estatica que me genero.

	* **sergio-mata** [552173] (1)

		tu ec2 esta en una subnet publica?

* **esteban-chamba-jimenez** (1) [66680](https://platzi.com/comentario/711009/) 
Solo me permite agregar hasta 5 Elastic Ip, como hago si necesito más ?

	* **carlosantonio_** [66680] (1)

		Tienes que levantar un ticket a soporte para que te aumenten, hay algunas cosas que no te aumentan por tu historial $

* **karkastell** (1) [65380](https://platzi.com/comentario/690682/) 
Puedo asociar más de 1 IP publica a 1 instancia de EC2?, por ejemplo para publicar diferentes servicios?

	* **Carlos Andrés Zambrano Barrera** [65380] (1)

		Si se puede, tienes que agregar antes una ENI.

## 0080. Balanceadores de carga [15383](https://platzi.com/clases/1427-aws-computo/15383-balanceadores-de-carga/)

### Descripción:


Un **Load balancer** o balanceador de carga lo puedes conectar a una o más instancias y lo que hace es balancear las solicitudes que le llegan pudiendo generar respuestas de una de las instancias que tiene a disposición dependiendo de su disponibilidad. Puedes balancear peticiones HTTP, HTTPS o TCP con los servicios de **AWS**.

Cuando creamos un load balancer, podemos ver en sus configuraciones básicas un _DNS_ el cual podemos usar en **Route 53** como _CNAME_ para ponerme un nombre de dominio o subdominio.

### Comentarios:

* **alexgv04** (3) [719494](https://platzi.com/comentario/719494/) 

	también podría configurar el balanceador con dos instancias de EC2 diferentes para dividir la carga de trabajo de dichas instancias.

	* **juancajamarca** [719494] (1)

		Ese es el motivo por el cual se utiliza este servicio. Dos o más instancias.

* **Hugo valencia Vargas** (3) [474747](https://platzi.com/comentario/474747/) 

	el volumen está muy bajo

	* **Salvador Jose Campanella Salas** [474747] (2)

		Pienso lo mismo, de hecho este curso se me hizo imposible realizarlo desde mi telefono movil.

* **jorge-gianareas** (2) [968446](https://platzi.com/comentario/968446/) 

	Un Load balancer o balanceador de carga lo puedes conectar a una o más instancias y lo que hace es balancear las solicitudes que le llegan pudiendo generar respuestas de una de las instancias que tiene a disposición dependiendo de su disponibilidad. Puedes balancear peticiones HTTP, HTTPS o TCP con los servicios de AWS.

* **johncastillotellez7** (2) [842119](https://platzi.com/comentario/842119/) 

	muy importante>Load balancer o balanceador de carga lo puedes conectar a una o más instancias y lo que hace es balancear las solicitudes que le llegan pudiendo generar respuestas de una de las instancias que tiene a disposición dependiendo de su disponibilidad.

* **Andi Antopher** (1) [1063219](https://platzi.com/comentario/1063219/) 

	seria buena idea un ejemplo con 443

* **Juan Sebastián Bonilla Sanchez** (1) [982655](https://platzi.com/comentario/982655/) 

	Excelente tema de los balanceadores de carga!

* **jorge-gianareas** (1) [968449](https://platzi.com/comentario/968449/) 

	Cuando creamos un load balancer, podemos ver en sus configuraciones básicas un DNS el cual podemos usar en Route 53 como CNAME para ponerme un nombre de dominio o subdominio.

* **jorge-gianareas** (1) [968444](https://platzi.com/comentario/968444/) 

	c:\Users\musi4\Downloads\hola.pem’ [ec2-user@ec2-34-205-157-126.compute-1.amazonaws.com](mailto:ec2-user@ec2-34-205-157-126.compute-1.amazonaws.com)

* **ramirobga** (1) [821938](https://platzi.com/comentario/821938/) 

	segui todos los pasos, pero no me salio este laboratorio.  
	lo revise 3 veces, y segui las instrucciones al pie de la letra.
	
	![](https://fotos.subefotos.com/d6fbca5a9b4c6bcd0ffedcc6db9767ceo.jpg)
	
	quizas exista algun paso que se obvio?
	
	gracia

	* **jheyson7** [821938] (3)

		tal vez las subnets q marcastes en la configuracion del balanceador no coinciden con la zona de disponibilidad en la que esta tu instancia a la que quiers acceder, me sucedio el mismo problema

	* **Mateo Loaiza Rios** [821938] (1)

		Me sucede el mismo problema

	* **Mateo Loaiza Rios** [821938] (1)

		Como se soluciona este problema?

	* **juliocesaranaya** [821938] (1)

		A mi me pasó lo mismo, lo que hice fue camibar en la configuración del Balanceador en vez de que sea instance lo puse como IP

* **edwintrumpet** (1) [620098](https://platzi.com/comentario/620098/) 

	¿Para qué sirven estos balanceadores de carga?  
	Mauro dice en el video que si tuvieramos varias instancias dividiría las request entre las instancias.  
	¿Pero en este caso que tenemos una sola instancia sería útil?

	* **juanmoya** [620098] (2)

		Hola Edwin este te puede ayudar para poner diferentes ambientes de pruebas, y hacer la redistribución de los mismos por diferentes puertos en el listener.

* **Dario Jose Vilchez Perozo** (1) [549505](https://platzi.com/comentario/549505/) 

	Si yo tengo un EC2 y veo que mi IIS se está quedando muy corto puedo activar ese balanceador y me ayudaria a estabilizar ?

	* **carlosbazanhuaman** [549505] (1)

		en tu caso tendrias q crear otra instancias con tu iis y crear un balancador para que ayude a tu instancia con iis original, asi la carga se reparte entre tus instancias.

* **Dario Jose Vilchez Perozo** (1) [549502](https://platzi.com/comentario/549502/) 

	Buenas noches, una consulta el balanceador de carga mas o menos en donde se utiliza comunmente ?

	* **Héctor Manuel Hernández Ortega** [549502] (1)

		Justo antes de llegar a donde está tu aplicación instalada,así podrás verificar a que instancia de tu aplicación enviar las peticiones que recibas.
		
		Comunmente vive en otro servidor ajeno a donde vive tu aplicación.

	* ** Oscar Gomez R.** [549502] (1)

		Hola, el balanceador lo utilizas de frente o antes de recibir las peticiones de tu aplicación, pero la idea es que tu aplicación sea servida en varios servidores, para esto utilizas el balanceador para que distribuya el trafico hacia tu aplicación que se encuentra en varias instancias o diferentes servidores.

* **Dario Jose Vilchez Perozo** (1) [56162](https://platzi.com/comentario/549502/) 
Buenas noches, una consulta el balanceador de carga mas o menos en donde se utiliza comunmente ?

	* **Héctor Manuel Hernández Ortega** [56162] (1)

		Justo antes de llegar a donde está tu aplicación instalada,así podrás verificar a que instancia de tu aplicación enviar las peticiones que recibas.
		
		Comunmente vive en otro servidor ajeno a donde vive tu aplicación.

## 0090. Balanceadores de carga con https [15384](https://platzi.com/clases/1427-aws-computo/15384-balanceadores-de-carga-con-https/)

### Descripción:


## Introducción

Normalmente, cuando usas un balanceador de cargas, quieres prover dos distintos servicios:

* Https - puerto 443
* Http - puerto 80



Para dar servicio en el puerto 443, sigue las instrucciones que viene en la clase de load balancer, y la hora de anexar el puerto 443, te pedirá un certificado. Vamos a crear un nuevo certificado antes, para que solo selecciones el correcto.

Creando un certificado nuevo.

## Requisitos

* Poseer algún dominio o subdominio, que asignaras al certificado inicialmente, y después al balanceador de carga.
* Tener acceso a recibir el correo por parte del administrador del dominio, para poder anexar el certificado del lado de AWS. Si no lo tienes, necesitas acceso al DNS de ese dominio, para anexar un “entry” en el DNS, relacionado con la autenticación que requiere AWS para que muestres que eres el dueño del dominio (o que tienes control para él, si es que eres el administrador para alguna compañía).



## Actividades

* Ve al Certificate Manager. Visita la consola de amazon <http://console.aws.amazon.com/> y de ahi ponle en el search “Certificate Manager”.
* Dale click en “Provision certificates”-> Get Started.
* Selecciona “Request a public certificate”
* Click en el botón “Request a certificate”.
* En la sección “Add a domain name”, pon un dominio wildcard al menos. Por ejemplo, en la clase de Networking & CDN en AWS compramos un dominio [pruebaplatzi.de](http://pruebaplatzi.de). En mi caso, pondría *.pruebaplatzi.de”. Tu tienes que poner *.tudominio.com, pensando que tu dominio se llama [tudominio.com](http://tudominio.com). Puedes anexar mas, como por ejemplo [www.tudominio.com](http://www.tudominio.com), [test.tudominio.com](http://test.tudominio.com), etc. Puedes anexar tantos como necesites, de tal manera que ese certificado cubra a todos tus servidores de prueba o desarrollo. Te recomiendo que si estas haciendo un producto, tu dominio [producto.tudominio.com](http://producto.tudominio.com) tenga su propio certificado solito, para que la gente no se confunda cuando lo revisa en el candado verde en tu navegador.
* Dale ‘Next’
* Selecciona que tipo de validación puedes hacer: si te llegan los mails de quien registro el dominio, selecciona mail. Si no es así, pero tienes acceso al DNS, selecciona DNS.
* En el caso de que manejes el dominio y el DNS del dominio en Route53, es mas sencillo ponerle DNS, y puedes ver la clase de Route53 para ver como anexas subdominios con el valor que te solicita AWS.
* Click en “Confirm request” y listo.
* En el caso que selecciones mail, revisa tu mail y dale click al url que te incluyen.
* Una vez que termines la validación, ya te aparecerá listado en los certificados.



## Creando el balanceador de carga

Ahora que ya tienes el certificado, puedes ir directamente a la consola de AWS, y crear o editar el balanceador de cargas, anexa el puerto 443/https, y cuando te pida el certificado, utiliza el que recién creaste.

Si tienes alguna duda o quisieras una guía paso a paso, ve a:

### Comentarios:

* **juancajamarca** (2) [923342](https://platzi.com/comentario/923342/) 

	Está mejor explicado en el curso de Networking & Content Delivery en AWS.

* **johncastillotellez7** (1) [842138](https://platzi.com/comentario/842138/) 

	interesante y util el paso a paso.

* **soundread** (1) [481745](https://platzi.com/comentario/481745/) 

	Seguí todos los pasos: cree el certificado, luego el balanceador y desde Route 53 estoy manejando los DNS para que apunte a la instacia. Sin embargo, no logro que el dominio funcione con https://

	* **Wigilabs SAS** [481745] (3)

		Tal vez puedas guiarte siguiendo los pasos que expone Mauro en el siguiente enlace: <https://platzi.com/clases/1323-aws-cloud/12604-certificate-manager/>

* **ricardosordo** (1) [455542](https://platzi.com/comentario/455542/) 

	Creo no se anexo la última información de dice que existe una guía. Transcribo la última linea: ""paso a paso ve a:… “” Ojalá y puedas anexarla Mauro. Saludos

	* **Wigilabs SAS** [455542] (3)

		Tal vez puedas apoyarte en los pasos que expone Mauro en ese enlace <https://platzi.com/clases/1323-aws-cloud/12604-certificate-manager/>

	* **Cristian David Franco Garcia** [455542] (1)

		Si tiene dudas para comprar el dominio este link es util: <https://platzi.com/clases/1419-networking-content/15162-comprando-un-dominio-en-route-53/>

* **Johan Andrey Barón** (0) [930657](https://platzi.com/comentario/930657/) 

	No puedo hacer esta actividad por problemas de permisos. Alguien sabe que puedo hacer… tengo cuenta de estudiante.

## 0100. Marketplace de AMIs [15385](https://platzi.com/clases/1427-aws-computo/15385-marketplace-de-amis/)

### Descripción:


La URL para acceder al marketplace es: <https://aws.amazon.com/marketplace>

En el marketplace podrás encontrar una gran cantidad de imágenes generadas para crear instancias. Algunas de ellas serán de pago y otras serán gratuitas sólo cobrando por la infraestructura de Amazon.  
Esto puede resultar muy útil porque nos ahorra el tiempo de creación de instancias y sus copias, dándonos configuraciones perfectas para nuestras necesidades, que alguien ya resolvió con anterioridad.

### Links:

* [AWS Marketplace: Homepage](https://aws.amazon.com/marketplace/)

### Comentarios:

* **Nestor Alfonso Portela Rincón** (5) [511296](https://platzi.com/comentario/511296/) 

	Con unos amigos pensamos en montar nuestro sitio web, pero no queriamos tenerlo en esos hosting que uno arrienda y por precios por ejemplo de 180 mil pesos, ahora veo que podemos tener un VPS básico que pueda correr nuestro sitio web a menos costo anual pero con mejor rendimiento. Me agrada eso.

* **jorge-gianareas** (2) [968460](https://platzi.com/comentario/968460/) 

	Si compras algo y no estás seguro de lo que estás haciendo, te van a obrar esa instancia y lo que compraste en el marketing

* **jorge-gianareas** (1) [968462](https://platzi.com/comentario/968462/) 

	Sobre los comandos en AWS CLI
	
	Se ha mencionado acerca de la importancia y los beneficios que tiene la implementación de AWS CLI, esto no es solo debido a la posibilidad que brinda de administrar los recursos de forma remota, sino también por la variedad de comandos disponibles para la mayoría de los servicios. De hacer una lista con los servicios habilitados en la terminal y las ejecuciones que se puede llevar a cabo con cada uno, se daría información extensa de forma innecesaria. En lugar de esto, es conveniente conocer la estructura de los comandos de AWS CLI:
	
	aws [opciones] [comando] [subcomando] [parámetros]
	
	* aws: es necesario anteponer este texto para la ejecución de comandos relacionados con AWS CLI.
	* [opciones]: es un parámetro opcional y solo se da cuando la función soporta opciones que se desean especificar.
	* [comando]:parámetro obligatorio que identifica el comando y en la mayoría de los casos el servicio al que pertenece el subcomando que se va a ejecutar.
	* [subcomando]: comando específico del servicio que se va a ejecutar, este contiene la función específica que se va a ejecutar.
	* [parámetros]: no es un parámetro obligatorio pero es requerido en la mayoría de los casos para asignar las variables de la función a ejecutar.
	
	

* **jorge-gianareas** (1) [968457](https://platzi.com/comentario/968457/) 

	Esto puede resultar muy útil porque nos ahorra el tiempo de creación de instancias y sus copias, dándonos configuraciones perfectas para nuestras necesidades, que alguien ya resolvió con anterioridad.

* **jorge-gianareas** (1) [968456](https://platzi.com/comentario/968456/) 

	La URL para acceder al marketplace es: <https://aws.amazon.com/marketplace>  
	En el marketplace podrás encontrar una gran cantidad de imágenes generadas para crear instancias. Algunas de ellas serán de pago y otras serán gratuitas sólo cobrando por la infraestructura de Amazon.

* **Salvador Jose Campanella Salas** (1) [881767](https://platzi.com/comentario/881767/) 

	Esto es muy útil cuando por ejemplo necesitas crear instancias que siempre llevan la misma configuración base.

* **johncastillotellez7** (1) [842141](https://platzi.com/comentario/842141/) 

	para ir marketplace es: <https://aws.amazon.com/marketplace>

## 0110. Reto EC2 [15387](https://platzi.com/clases/1427-aws-computo/15387-reto7534/)

### Descripción:


El reto de esta clase consiste en crear una instancia de **EC2** y configurarle nuestro proyecto de frases motivacionales. Para probar que lo hiciste bien, copia la IP pública de la instancia en tu navegador y deberías poder ver una de las frases.

### Comentarios:

* **jorge-gianareas** (2) [968465](https://platzi.com/comentario/968465/) 

	Sobre los comandos en AWS CLI
	
	Se ha mencionado acerca de la importancia y los beneficios que tiene la implementación de AWS CLI, esto no es solo debido a la posibilidad que brinda de administrar los recursos de forma remota, sino también por la variedad de comandos disponibles para la mayoría de los servicios. De hacer una lista con los servicios habilitados en la terminal y las ejecuciones que se puede llevar a cabo con cada uno, se daría información extensa de forma innecesaria. En lugar de esto, es conveniente conocer la estructura de los comandos de AWS CLI:
	
	aws [opciones] [comando] [subcomando] [parámetros]
	
	* aws: es necesario anteponer este texto para la ejecución de comandos relacionados con AWS CLI.
	* [opciones]: es un parámetro opcional y solo se da cuando la función soporta opciones que se desean especificar.
	* [comando]:parámetro obligatorio que identifica el comando y en la mayoría de los casos el servicio al que pertenece el subcomando que se va a ejecutar.
	* [subcomando]: comando específico del servicio que se va a ejecutar, este contiene la función específica que se va a ejecutar.
	* [parámetros]: no es un parámetro obligatorio pero es requerido en la mayoría de los casos para asignar las variables de la función a ejecutar.
	
	

* **Daniel .** (2) [474530](https://platzi.com/comentario/474530/) 

	<http://100.26.74.119/> 😃

* **735** (1) [1031995](https://platzi.com/comentario/1031995/) 

	Super clase, a continuación mi reto  
	<http://3.21.74.138/>

* **juancapote** (1) [1020603](https://platzi.com/comentario/1020603/) 

	Mi reto excelente curso
	
	<http://18.218.194.126/>

* **elviejomenu** (1) [999595](https://platzi.com/comentario/999595/) 

	Reto :  
	<http://18.206.161.105/>

* **Carlos Bustos** (1) [992624](https://platzi.com/comentario/992624/) 

	<http://3.20.217.17/>  
	Ask and it will be given to you; search, and you will find; knock and the door will be opened for you.

* **Juan Sebastián Bonilla Sanchez** (1) [991312](https://platzi.com/comentario/991312/) 

	<http://3.134.109.60/> \- Life is what we make it, always has been, always will be.

* **Johan Manuel Merello Ortecho** (1) [988967](https://platzi.com/comentario/988967/) 

	<http://3.134.118.103/>
	
	sobre amazon linux jejeje

* **juancajamarca** (1) [923389](https://platzi.com/comentario/923389/) 

	Done

* **Luis Emmanuel Rodas Camposeco** (1) [903654](https://platzi.com/comentario/903654/) 

	<http://18.188.171.248/>  
	“You can’t use up creativity. The more you use, the more you have.”

* **anton.casais.mera** (1) [895922](https://platzi.com/comentario/895922/) 

	<http://35.159.7.166/>  
	"The two most important days in your life are the day you are born and the day you find out why."  
	Mark Twain

* **Eduardo Rodriguez Yapur** (1) [880931](https://platzi.com/comentario/880931/) 

	<http://52.15.66.119/>  
	"You can never cross the ocean until you have the courage to lose sight of the shore."  
	Christopher Columbus

* **Giovani Fernandez** (1) [865984](https://platzi.com/comentario/865984/) 

	<http://18.216.193.164>  
	"Everything has beauty, but not everyone can see"  
	-Confucius

* **Elias Ojeda Medina** (1) [729067](https://platzi.com/comentario/729067/) 

	<http://35.162.10.4/>  
	"Whether you think you can or you think you can’t, you’re right."  
	Henry Ford

* **estebanvasquezvalencia** (1) [493776](https://platzi.com/comentario/493776/) 

	La ip pública 54.175.213.225. La frase que me generó fue “Build your own dreams, or someone else will hire you to build theirs”.  
	Farrah Gray.
	
	Ya apagué la instancia 😃

* **yojotaman** (1) [470685](https://platzi.com/comentario/470685/) 

	<http://52.73.228.222/> 👍👍

* **Enrique Alexis Lopez Araujo** (1) [470063](https://platzi.com/comentario/470063/) 

	Listo mauro: <http://34.227.106.201/>

# Lightsail [3031]

## 0120. Introducción a Lightsail [15533](https://platzi.com/clases/1427-aws-computo/15533-introduccion7669/)

### Descripción:


* Es un VPS (Virtual Private Server) como lo es **Digital Ocean** o el mismo **EC2** de Amazon. Tiene una IP pública y un dominio gratis. Su mayor diferencia con **EC2** es el precio más bajo.
* Se inicia en segundos
* Viene con varios templates pre-configurados como LAMP, Wordpress, Magento, etc.
* Su principal ventaja es su costo, bajo y predecible.
* Puedes aumentar o disminuir su capacidad cuando lo quieras, al alcance de un click.
* Puedes usar bases de datos.
* Puedes hacer respaldos como los **Snapshots**.
* Te ofrece la opción de restauración.
* Puede ser multi-región o multi-zonas (que en la misma zona geográfica tendrás diferentes data centers).



### Links:

* [Amazon Lightsail](https://aws.amazon.com/es/lightsail/)

### Comentarios:

* **jorge-gianareas** (2) [968468](https://platzi.com/comentario/968468/) 

	Es un VPS (Virtual Private Server) como lo es Digital Ocean o el mismo EC2 de Amazon. Tiene una IP pública y un dominio gratis. Su mayor diferencia con EC2 es el precio más bajo.  
	Se inicia en segundos  
	Viene con varios templates pre-configurados como LAMP, Wordpress, Magento, etc.  
	Su principal ventaja es su costo, bajo y predecible.  
	Puedes aumentar o disminuir su capacidad cuando lo quieras, al alcance de un click.  
	Puedes usar bases de datos.  
	Puedes hacer respaldos como los Snapshots.  
	Te ofrece la opción de restauración.  
	Puede ser multi-región o multi-zonas (que en la misma zona geográfica tendrás diferentes data centers).

* **Juan Pablo Bravo** (2) [520638](https://platzi.com/comentario/520638/) 

	el audio no es de lo mejor

* **jorge-gianareas** (1) [970670](https://platzi.com/comentario/970670/) 

	Puedes aumentar o disminuir su capacidad cuando lo quieras, al alcance de un click.

* **johncastillotellez7** (1) [842180](https://platzi.com/comentario/842180/) 

	light sail Es un VPS (Virtual Private Server) como lo es Digital Ocean o el mismo EC2 de Amazon

* **carlosbazanhuaman** (1) [829723](https://platzi.com/comentario/829723/) 

	podrian mejorar el audio, ya que por movil no se escucha bien.  
	Saludos.

* **nicolas-garcia-puerta** (1) [803316](https://platzi.com/comentario/803316/) 

	Me gustaría que listaran mas diferencias

	* **juancajamarca** [803316] (2)

		La principales son esas, y que este servicio se utiliza para ambientes de desarrollo y de pruebas. En producción sí es 100% recomendable usar EC2. En lo demás, es muy similar.

* **AdiMolina** (0) [81867](https://platzi.com/comentario/991840/) 
Tengo un server corriendo, ya en producción pero necesito que sea seguro (https) por que solo es http abriendo el puerto 443 para https s...

	* **Johan Manuel Merello Ortecho** [81867] (2)

		Debes obtener un certificado de seguridad para el Https, aparte de eso dirigir tu trafico al puerto 443 y ya no al 80.

## 0130. Marketplace LS [15534](https://platzi.com/clases/1427-aws-computo/15534-marketplace-ls/)

### Descripción:


El marketplace de **Lightsail** te permite elegir entre Linux y Windows, siendo esta opción la manera más económica de tener Windows de todos los servicios de Amazon.  
Puedes instalar el SO más aplicaciones como Wordpress o Node.js; también puedes decidir por inicializar la imagen sólo con el sistema operativo, teniendo muchas opciones en la familia de Linux.  
Instalar todos los parches de seguridad o actualizaciones es tu responsabilidad al igual que en **EC2**.

### Comentarios:

* **jorge-gianareas** (2) [968472](https://platzi.com/comentario/968472/) 

	Instalar todos los parches de seguridad o actualizaciones es tu responsabilidad al igual que en EC2.

* **jorge-gianareas** (2) [968470](https://platzi.com/comentario/968470/) 

	El marketplace de Lightsail te permite elegir entre Linux y Windows, siendo esta opción la manera más económica de tener Windows de todos los servicios de Amazon.

* **jorge-gianareas** (1) [968471](https://platzi.com/comentario/968471/) 

	Puedes instalar el SO más aplicaciones como Wordpress o Node.js; también puedes decidir por inicializar la imagen sólo con el sistema operativo, teniendo muchas opciones en la familia de Linux

* **johncastillotellez7** (1) [842190](https://platzi.com/comentario/842190/) 

	lo unico es que tiene costo par asarlo. pero definitivamente se ve una herramienta super util.

* **alexgv04** (1) [719710](https://platzi.com/comentario/719710/) 

	usando Django con Lightsail <https://www.nerdsgene.com/Article/DeployDjangoToLightSail>

* **Jfusma85** (1) [73386](https://platzi.com/comentario/833971/) 
por que escoger lightsail sobre las otras opciones como digital ocean? solo por precios o que ventaja adicional tiene?

	* **Erik Ochoa** [73386] (1)

		La elección que hagas siempre va a depender de tus necesidades, en verdad que no hay una mejor que otra. Va a ser mejor o peor dependiendo de qué tan bien cumple con tus necesidades especificas.
		
		Este es un curso sobre AWS por eso se usa lightsail, si te interesa Digital Ocean también tenemos [un curso](https://platzi.com/clases/digital-ocean/).

## 0140. Comparativa [15535](https://platzi.com/clases/1427-aws-computo/15535-comparativa/)

### Descripción:


Esto es lo que te ofrece Lightsail:

* El costo de los CPUs depende del número que elijas.
* Tienes almacenamiento SSD.
* Te ofrece Networking y transferencia de datos.
* Incluye manejo de DNS.
* Tienes una IP estática asignada a ti.
* Tienes acceso a otros servicios de **AWS**



En una comparativa de costos, el plan más económico de **Lightsail** ofrece por $3.50 1 TB de transferencia mientras que la misma capacidad en **EC2** puede salir por más de $90.

### Comentarios:

* **carlosbazanhuaman** (3) [829734](https://platzi.com/comentario/829734/) 

	el precio que cobra amazon puede ser muy bueno para aplicaciones que inician pero para cosas medianas a grandes si ya es un poco considerado sobre todo por el storage y transferencia.

* **Cristian David Montoya Montoya** (3) [556350](https://platzi.com/comentario/556350/) 

	Excelente este servicio de AWS, no lo conocía. Estoy realizando pruebas para migrar mis sitios de WorkPress

* **jorge-gianareas** (2) [968479](https://platzi.com/comentario/968479/) 

	En una comparativa de costos, el plan más económico de Lightsail ofrece por $3.50 1 TB de transferencia mientras que la misma capacidad en EC2 puede salir por más de $90

* **jorge-gianareas** (2) [968476](https://platzi.com/comentario/968476/) 

	“Parameters” : {  
	“VpcId” : {  
	“Type” : “AWS::EC2::VPC::Id”,  
	“Description” : “VpcId of your existing Virtual Private Cloud (VPC)”,  
	“ConstraintDescription” : “must be the VPC Id of an existing Virtual Private Cloud.”  
	},
	``` 
	    "Subnets" : {
	      "Type" : "List<AWS::EC2::Subnet::Id>",
	      "Description" : "The list of SubnetIds in your Virtual Private Cloud (VPC)",
	      "ConstraintDescription" : "must be a list of at least two existing subnets associated with at least two different availability zones. They should be residing in the selected Virtual Private Cloud."
	    },
	    
	    "KeyName": {
	      "Description" : "Name of an existing EC2 KeyPair to enable SSH access to the instances",
	      "Type": "AWS::EC2::KeyPair::KeyName",
	      "ConstraintDescription" : "must be the name of an existing EC2 KeyPair."
	    },
	    
	    "InstanceType" : {
	      "Description" : "WebServer EC2 instance type",
	      "Type" : "String",
	      "Default" : "t2.small",
	      "AllowedValues" : [ "t1.micro", "t2.nano", "t2.micro", "t2.small", "t2.medium", "t2.large", "m1.small", "m1.medium", "m1.large", "m1.xlarge", "m2.xlarge", "m2.2xlarge", "m2.4xlarge", "m3.medium", "m3.large", "m3.xlarge", "m3.2xlarge", "m4.large", "m4.xlarge", "m4.2xlarge", "m4.4xlarge", "m4.10xlarge", "c1.medium", "c1.xlarge", "c3.large", "c3.xlarge", "c3.2xlarge", "c3.4xlarge", "c3.8xlarge", "c4.large", "c4.xlarge", "c4.2xlarge", "c4.4xlarge", "c4.8xlarge", "g2.2xlarge", "g2.8xlarge", "r3.large", "r3.xlarge", "r3.2xlarge", "r3.4xlarge", "r3.8xlarge", "i2.xlarge", "i2.2xlarge", "i2.4xlarge", "i2.8xlarge", "d2.xlarge", "d2.2xlarge", "d2.4xlarge", "d2.8xlarge", "hi1.4xlarge", "hs1.8xlarge", "cr1.8xlarge", "cc2.8xlarge", "cg1.4xlarge"]
	    
	```
	
	,  
	“ConstraintDescription” : “must be a valid EC2 instance type.”  
	},
	``` 
	    "SSHLocation": {
	      "Description": "The IP address range that can be used to SSH to the EC2 instances",
	      "Type": "String",
	      "MinLength": "9",
	      "MaxLength": "18",
	      "Default": "0.0.0.0/0",
	      "AllowedPattern": "(\\d{1,3})\\.(\\d{1,3})\\.(\\d{1,3})\\.(\\d{1,3})/(\\d{1,2})",
	      "ConstraintDescription": "must be a valid IP CIDR range of the form x.x.x.x/x."
	    },
	    
	    "DBClass" : {
	      "Description" : "Database instance class",
	      "Type" : "String",
	      "Default" : "db.t2.small",
	      "AllowedValues" : [ "db.t1.micro", "db.m1.small", "db.m1.medium", "db.m1.large", "db.m1.xlarge", "db.m2.xlarge", "db.m2.2xlarge", "db.m2.4xlarge", "db.m3.medium", "db.m3.large", "db.m3.xlarge", "db.m3.2xlarge", "db.m4.large", "db.m4.xlarge", "db.m4.2xlarge", "db.m4.4xlarge", "db.m4.10xlarge", "db.r3.large", "db.r3.xlarge", "db.r3.2xlarge", "db.r3.4xlarge", "db.r3.8xlarge", "db.m2.xlarge", "db.m2.2xlarge", "db.m2.4xlarge", "db.cr1.8xlarge", "db.t2.micro", "db.t2.small", "db.t2.medium", "db.t2.large"]
	    
	```
	
	,  
	“ConstraintDescription” : “must select a valid database instance type.”  
	},
	``` 
	    "DBName" : {
	      "Default": "wordpressdb",
	      "Description" : "The WordPress database name",
	      "Type": "String",
	      "MinLength": "1",
	      "MaxLength": "64",
	      "AllowedPattern" : "[a-zA-Z][a-zA-Z0-9]*",
	      "ConstraintDescription" : "must begin with a letter and contain only alphanumeric characters."
	    },
	    
	    "DBUser" : {
	      "NoEcho": "true",
	      "Description" : "The WordPress database admin account username",
	      "Type": "String",
	      "MinLength": "1",
	      "MaxLength": "16",
	      "AllowedPattern" : "[a-zA-Z][a-zA-Z0-9]*",
	      "ConstraintDescription" : "must begin with a letter and contain only alphanumeric characters."
	    },
	    
	    "DBPassword" : {
	      "NoEcho": "true",
	      "Description" : "The WordPress database admin account password",
	      "Type": "String",
	      "MinLength": "8",
	      "MaxLength": "41",
	      "AllowedPattern" : "[a-zA-Z0-9]*",
	      "ConstraintDescription" : "must contain only alphanumeric characters."
	    },
	    
	    "MultiAZDatabase": {
	      "Default": "false",
	      "Description" : "Create a Multi-AZ MySQL Amazon RDS database instance",
	      "Type": "String",
	      "AllowedValues" : [ "true", "false" ],
	      "ConstraintDescription" : "must be either true or false."
	    },
	    
	    "WebServerCapacity": {
	      "Default": "1",
	      "Description" : "The initial number of WebServer instances",
	      "Type": "Number",
	      "MinValue": "1",
	      "MaxValue": "5",
	      "ConstraintDescription" : "must be between 1 and 5 EC2 instances."
	    },
	    
	    "DBAllocatedStorage" : {
	      "Default": "5",
	      "Description" : "The size of the database (Gb)",
	      "Type": "Number",
	      "MinValue": "5",
	      "MaxValue": "1024",
	      "ConstraintDescription" : "must be between 5 and 1024Gb."
	    }
	    
	```
	
	},
	
	“Mappings” : {  
	“AWSInstanceType2Arch” : {  
	“t1.micro” : { “Arch” : “HVM64” },  
	“t2.nano” : { “Arch” : “HVM64” },  
	“t2.micro” : { “Arch” : “HVM64” }  
	},
	``` 
	    "AWSInstanceType2NATArch" : {
	      "t1.micro"    : { "Arch" : "NATHVM64"  },
	      "t2.nano"     : { "Arch" : "NATHVM64"  },
	      "t2.micro"    : { "Arch" : "NATHVM64"  }
	    }
	    
	```
	
	,  
	“AWSRegionArch2AMI” : {  
	“us-east-1” : {“HVM64” : “ami-0080e4c5bc078760e”, “HVMG2” : “ami-0aeb704d503081ea6”}  
	}
	
	},
	
	“Resources” : {
	``` 
	    "ApplicationLoadBalancer" : {
	      "Type" : "AWS::ElasticLoadBalancingV2::LoadBalancer",
	      "Properties" : {
	        "Subnets" : { "Ref" : "Subnets"}
	      }
	    },
	    
	    "ALBListener" : {
	      "Type" : "AWS::ElasticLoadBalancingV2::Listener",
	      "Properties" : {
	        "DefaultActions" : [{
	          "Type" : "forward",
	          "TargetGroupArn" : { "Ref" : "ALBTargetGroup" }
	        }],
	        "LoadBalancerArn" : { "Ref" : "ApplicationLoadBalancer" },
	        "Port" : "80",
	        "Protocol" : "HTTP"
	      }
	    },
	    
	    "ALBTargetGroup" : {
	      "Type" : "AWS::ElasticLoadBalancingV2::TargetGroup",
	      "Properties" : {
	        "HealthCheckPath" : "/wordpress/wp-admin/install.php",  
	        "HealthCheckIntervalSeconds" : 10,
	        "HealthCheckTimeoutSeconds" : 5,
	        "HealthyThresholdCount" : 2,
	        "Port" : 80,
	        "Protocol" : "HTTP",
	        "UnhealthyThresholdCount" : 5,
	        "VpcId" : {"Ref" : "VpcId"},       
	        "TargetGroupAttributes" :
	          [ { "Key" : "stickiness.enabled", "Value" : "true" },
	            { "Key" : "stickiness.type", "Value" : "lb_cookie" },
	            { "Key" : "stickiness.lb_cookie.duration_seconds", "Value" : "30" }
	        ]
	      }
	    },
	    
	    "WebServerSecurityGroup" : {
	      "Type" : "AWS::EC2::SecurityGroup",
	      "Properties" : {
	        "GroupDescription" : "Enable HTTP access via port 80 locked down to the load balancer + SSH access",
	        "SecurityGroupIngress" : [
	          {"IpProtocol" : "tcp", "FromPort" : "80", "ToPort" : "80", "SourceSecurityGroupId" : {"Fn::Select" : [0, {"Fn::GetAtt" : ["ApplicationLoadBalancer", "SecurityGroups"]}]}},
	          {"IpProtocol" : "tcp", "FromPort" : "22", "ToPort" : "22", "CidrIp" : { "Ref" : "SSHLocation"}}
	        ],
	        "VpcId" : { "Ref" : "VpcId" }
	      }
	    },
	    
	    "WebServerGroup" : {
	      "Type" : "AWS::AutoScaling::AutoScalingGroup",
	      "Properties" : {
	        "VPCZoneIdentifier" : { "Ref" : "Subnets" },
	        "LaunchConfigurationName" : { "Ref" : "LaunchConfig" },
	        "MinSize" : "1",
	        "MaxSize" : "5",
	        "DesiredCapacity" : { "Ref" : "WebServerCapacity" },
	        "TargetGroupARNs" : [ { "Ref" : "ALBTargetGroup" } ]
	      },
	      "CreationPolicy" : {
	        "ResourceSignal" : {
	          "Timeout" : "PT15M"
	        }
	      },
	      "UpdatePolicy": {
	        "AutoScalingRollingUpdate": {
	          "MinInstancesInService": "1",
	          "MaxBatchSize": "1",
	          "PauseTime" : "PT15M",
	          "WaitOnResourceSignals": "true"
	        }
	      }
	    },
	    
	    "LaunchConfig": {
	      "Type" : "AWS::AutoScaling::LaunchConfiguration",
	      "Metadata" : {
	        "AWS::CloudFormation::Init" : {
	          "configSets" : {
	            "wordpress_install" : ["install_cfn", "install_wordpress" ]
	          },
	          "install_cfn" : {
	            "files": {
	              "/etc/cfn/cfn-hup.conf": {
	                "content": { "Fn::Join": [ "", [
	                  "[main]\n",
	                  "stack=", { "Ref": "AWS::StackId" }, "\n",
	                  "region=", { "Ref": "AWS::Region" }, "\n"
	                ]]},
	                "mode"  : "000400",
	                "owner" : "root",
	                "group" : "root"
	              },
	              "/etc/cfn/hooks.d/cfn-auto-reloader.conf": {
	                "content": { "Fn::Join": [ "", [
	                  "[cfn-auto-reloader-hook]\n",
	                  "triggers=post.update\n",
	                  "path=Resources.LaunchConfig.Metadata.AWS::CloudFormation::Init\n",
	                  "action=/opt/aws/bin/cfn-init -v ",
	                          "         --stack ", { "Ref" : "AWS::StackName" },
	                          "         --resource LaunchConfig ",
	                          "         --configsets wordpress_install ",
	                          "         --region ", { "Ref" : "AWS::Region" }, "\n"
	                ]]},          
	                "mode"  : "000400",
	                "owner" : "root",
	                "group" : "root"
	              }
	            },
	            "services" : {
	              "sysvinit" : {
	                "cfn-hup" : { "enabled" : "true", "ensureRunning" : "true",
	                              "files" : ["/etc/cfn/cfn-hup.conf", "/etc/cfn/hooks.d/cfn-auto-reloader.conf"]}
	              }
	            }
	          },
	    
	          "install_wordpress" : {
	            "packages" : {
	              "yum" : {
	                "php"       : [],
	                "php-mysql" : [],
	                "mysql"     : [],
	                "httpd"     : []
	              }
	            },
	            "sources" : {
	              "/var/www/html" : "http://wordpress.org/latest.tar.gz"
	            },
	            "files" : {
	              "/tmp/create-wp-config" : {
	                "content" : { "Fn::Join" : [ "", [
	                  "#!/bin/bash\n",
	                  "cp /var/www/html/wordpress/wp-config-sample.php /var/www/html/wordpress/wp-config.php\n",
	                  "sed -i \"s/'database_name_here'/'",{ "Ref" : "DBName" }, "'/g\" wp-config.php\n",
	                  "sed -i \"s/'username_here'/'",{ "Ref" : "DBUser" }, "'/g\" wp-config.php\n",
	                  "sed -i \"s/'password_here'/'",{ "Ref" : "DBPassword" }, "'/g\" wp-config.php\n",
	                  "sed -i \"s/'localhost'/'",{ "Fn::GetAtt" : [ "DBInstance", "Endpoint.Address" ] }, "'/g\" wp-config.php\n"
	                ]]},
	                "mode" : "000500",
	                "owner" : "root",
	                "group" : "root"
	              }
	            },
	            "commands" : {
	              "01_configure_wordpress" : {
	                "command" : "/tmp/create-wp-config",
	                "cwd" : "/var/www/html/wordpress"
	              }
	            },
	            "services" : {
	              "sysvinit" : {
	                "httpd" : { "enabled" : "true", "ensureRunning" : "true" }
	              }
	            }
	          }
	        }
	      },
	      "Properties": {
	        "ImageId" : { "Fn::FindInMap" : [ "AWSRegionArch2AMI", { "Ref" : "AWS::Region" },
	                          { "Fn::FindInMap" : [ "AWSInstanceType2Arch", { "Ref" : "InstanceType" }, "Arch" ] } ] },
	        "InstanceType"   : { "Ref" : "InstanceType" },
	        "SecurityGroups" : [ {"Ref" : "WebServerSecurityGroup"} ],
	        "KeyName"        : { "Ref" : "KeyName" },
	        "UserData" : { "Fn::Base64" : { "Fn::Join" : ["", [
	                       "#!/bin/bash -xe\n",
	                       "yum update -y aws-cfn-bootstrap\n",
	    
	                       "/opt/aws/bin/cfn-init -v ",
	                       "         --stack ", { "Ref" : "AWS::StackName" },
	                       "         --resource LaunchConfig ",
	                       "         --configsets wordpress_install ",
	                       "         --region ", { "Ref" : "AWS::Region" }, "\n",
	    
	                       "/opt/aws/bin/cfn-signal -e $? ",
	                       "         --stack ", { "Ref" : "AWS::StackName" },
	                       "         --resource WebServerGroup ",
	                       "         --region ", { "Ref" : "AWS::Region" }, "\n"
	        ]]}}
	      }
	    },
	    
	    "DBEC2SecurityGroup": {
	      "Type": "AWS::EC2::SecurityGroup",
	      "Properties" : {
	        "GroupDescription": "Open database for access",
	        "SecurityGroupIngress" : [{
	        "IpProtocol" : "tcp",
	        "FromPort" : "3306",
	        "ToPort" : "3306",
	        "SourceSecurityGroupId" : { "Ref" : "WebServerSecurityGroup" }
	        }],
	        "VpcId" : { "Ref" : "VpcId" }
	      }
	    },
	    
	    "DBInstance" : {
	      "Type": "AWS::RDS::DBInstance",
	      "Properties": {
	        "DBName"            : { "Ref" : "DBName" },
	        "Engine"            : "MySQL",
	        "MultiAZ"           : { "Ref": "MultiAZDatabase" },
	        "MasterUsername"    : { "Ref" : "DBUser" },
	        "MasterUserPassword": { "Ref" : "DBPassword" },
	        "DBInstanceClass"   : { "Ref" : "DBClass" },
	        "AllocatedStorage"  : { "Ref" : "DBAllocatedStorage" },
	        "VPCSecurityGroups" : [{ "Fn::GetAtt": [ "DBEC2SecurityGroup", "GroupId" ]}]
	      }
	    }
	    
	```
	
	},
	
	“Outputs” : {  
	“WebsiteURL” : {  
	“Value” : { “Fn::Join” : ["", [“http://”, { “Fn::GetAtt” : [ “ApplicationLoadBalancer”, “DNSName” ]}, “/wordpress” ]]},  
	“Description” : “WordPress Website”  
	}  
	}  
	}

* **ozkar-beltran** (2) [71899](https://platzi.com/comentario/805860/) 
Puedo publicar en Lightsail un servidor de aplicaciones Java?

	* **mariaocampo** [71899] (1)

		<https://aws.amazon.com/es/lightsail/>

* **Juan Sebastián Bonilla Sanchez** (1) [991353](https://platzi.com/comentario/991353/) 

	Excelente componente!

* **Dante Castillo Z.** (1) [969005](https://platzi.com/comentario/969005/) 

	Podre usar Lightsail para publicar un servicio de correo y pagina basado en la caracteristica del precio mas barato ¿? lo digo porque mirando los precios es mas barato que alquilar en un proveedor de servicios de hosting.

* **jorge-gianareas** (1) [968478](https://platzi.com/comentario/968478/) 

	Esto es lo que te ofrece Lightsail:
	
	El costo de los CPUs depende del número que elijas.  
	Tienes almacenamiento SSD.  
	Te ofrece Networking y transferencia de datos.  
	Incluye manejo de DNS.  
	Tienes una IP estática asignada a ti.  
	Tienes acceso a otros servicios de AWS

* **johncastillotellez7** (1) [842195](https://platzi.com/comentario/842195/) 

	interesante los precios ofrecidos . amazon siempre rompiendola con sus precios

* **Cristian David Franco Garcia** (1) [600248](https://platzi.com/comentario/600248/) 

	Tienes una IP estática asignada a ti.(Al momento de reiniciar la instancia la IP publica varia, por lo tanto debes configurar la IP estática).

## 0150. Creando un VPS [15537](https://platzi.com/clases/1427-aws-computo/15537-creando-un-vps/)

### Descripción:


### Links:

* [Amazon Lightsail](https://aws.amazon.com/es/lightsail/)

### Comentarios:

* **Daniel .** (4) [474545](https://platzi.com/comentario/474545/) 

	LS me parece una muy buena opción por ese precio

	* **Brayan Mamani** [474545] (1)

		Si por eso lo usan mucho.

* **johncastillotellez7** (1) [852796](https://platzi.com/comentario/852796/) 

	muy interesante, pero cuesta.

	* **juancajamarca** [852796] (1)

		Primer mes gratis 🤩

* **johncastillotellez7** (1) [842199](https://platzi.com/comentario/842199/) 

	lightsail vs ec2 $$

* **vcentt-lopez** (1) [540206](https://platzi.com/comentario/540206/) 

	Nosotros lo tenemos ya mas de un año en uso en ambiente productivo y funciona excelentemente bien, y hace poco mandamos 1 TB de información que teníamos en el servidor a S3 y bajamos mas de un 70% el precio

	* **edwintrumpet** [540206] (1)

		¿Tienen Ligthsail?  
		¿Por qué dice que bajaron el precio, luego no se supone que los precios en Lightsail son fijos?

	* **carlosbazanhuaman** [540206] (1)

		hicieron un backup de informacion y lo enviaron a otro repo?

	* **vcentt-lopez** [540206] (1)

		@edwin-garcia829 Ligthsail tiene precio fijo, pero teníamos un EBS adjunto al servidor con 1 TB de información, y eso no forma parte de Ligthsail, por eso es que comento que al pasar esa información al servicio de S3, bajamos un 70% el costo que teníamos por EBS
		
		@carlosbazanhuaman lo que hicimos fue mover la información de disco adjunto en el VPS al servicio de S3 de AWS, una vez que la información ya estaba en S3 ya pudimos eliminar el EBS e hicimos un ahorro considerable

## 0160. Instalando Frases Citables [15536](https://platzi.com/clases/1427-aws-computo/15536-instalando-frases-citables/)

### Descripción:


Instalar un proyecto en **Lightsail** es muy parecido al procedimiento que se realiza en **EC2**.

Cosas a tener en cuenta al momento de instalar tu proyecto con **Lightsail** :

* Si estás en Windows, deberás usar un software como MobaXterm para tener una terminal que se conecte por SSH.
* Recuerda hacerte administrador con el comando “sudo su”
* Recuerda hacer update con el comando “apt-get update” porque es una instancia nueva y no tiene en memoria caché las direcciones desde dónde debe tomar el software. Si el proyecto se instala sin hacer esto, fallará.
* El comando para instalar el software es “sudo apt install apache2 git libapache2-mod-php -y”.
* La URL del proyecto es “[https://github.com/mauropm/quotes-generator”](https://github.com/mauropm/quotes-generator%E2%80%9D).



Configurar todo lo que esté en la red de Amazon es súper veloz, dándole más ventajas a la instalación de proyectos en **Lightsail**.

### Comentarios:

* **Felipe Acosta** (6) [464664](https://platzi.com/comentario/464664/) 

	Tambien en cuando estas creando la instancia, en la parte donde dice _Script de Lanzamineto_ , puedes agregar
	``` 
	    #!/bin/bash
	    sudo apt install apache2 git libapache2-mod-php -y
	    
	```
	
	Y listo cuando tu maquina termine de iniciar ya va a tener todo instalado y listo para trabajar.

	* **estebanvasquezvalencia** [464664] (2)

		En la sección de OPTIONAL -> Add Launch script (user data) Gracias!

* **AyKaren** (5) [432713](https://platzi.com/comentario/432713/) 

	Este es el comando para instalar los requisitos del proyecto:  
	`sudo apt install apache2 git libapache2-mod-php -y`

* **jorge-gianareas** (2) [968480](https://platzi.com/comentario/968480/) 

	Instalar un proyecto en Lightsail es muy parecido al procedimiento que se realiza en EC2.

* **Johan Manuel Merello Ortecho** (1) [989158](https://platzi.com/comentario/989158/) 

	A diferencia de EC2 en Lightsail , para LINUX viene activado por defecto en el Firewall la conexión al puerto 22 (SSH) y 80 (HTTP) .

* **jorge-gianareas** (1) [968481](https://platzi.com/comentario/968481/) 

	Cosas a tener en cuenta al momento de instalar tu proyecto con Lightsail:
	
	Si estás en Windows, deberás usar un software como MobaXterm para tener una terminal que se conecte por SSH.  
	Recuerda hacerte administrador con el comando “sudo su”  
	Recuerda hacer update con el comando “apt-get update” porque es una instancia nueva y no tiene en memoria caché las direcciones desde dónde debe tomar el software. Si el proyecto se instala sin hacer esto, fallará.  
	El comando para instalar el software es “sudo apt install apache2 git libapache2-mod-php -y”.

* **juancajamarca** (1) [923424](https://platzi.com/comentario/923424/) 

	Si no quieres conectarte con una terminal o consola, puedes hacerlo directamente en el navegador dando clic en el símbolo de terminal que aparece en la parte superior derecha de cada ítem. Cabe recalcar que sólo funciona en Lightsail, no en EC2. 😄

* **johncastillotellez7** (1) [842172](https://platzi.com/comentario/842172/) 

	“sudo apt install apache2 git libapache2-mod-php -y”.  
	La URL del proyecto es “[https://github.com/mauropm/quotes-generator”](https://github.com/mauropm/quotes-generator%E2%80%9D).

* **carlosbazanhuaman** (1) [829722](https://platzi.com/comentario/829722/) 

	la instalacion de los paquetes es muy sencillo, solo hay que saber como hacerlo en cada distro de linux.

* **ramirobga** (1) [826996](https://platzi.com/comentario/826996/) 

	la url de guithub no funciona. quizas algo este mal

## 0170. Creando una BD [15539](https://platzi.com/clases/1427-aws-computo/15539-creando-una-bd/)

### Descripción:


Las bases de datos en **Lightsail** también tienen un costo fijo con la disponibilidad que ofrece Amazon.

Cosas a tener en cuenta al momento de crear tu base de datos:

* **Lightsail** nos ofrece varias versiones de MySQL; si es un proyecto nuevo es recomendado utilizar la más actual. Si es una migración deberemos elegir la versión más cercana a nuestra base de datos existente.
* **Lightsail** nos propone un password seguro, es recomendable usarlo.
* Puedes configurar tu base de datos de dos maneras:  
**Estándar:** Un servidor con una conexión desde afuera.  
**HA:** Alta disponibilidad, donde tienes dos servidores o más con un _load balancer_.



### Links:

* [Databases in Amazon Lightsail | Lightsail Documentation](https://lightsail.aws.amazon.com/ls/docs/en_us/articles/amazon-lightsail-databases)

### Comentarios:

* **jorge-gianareas** (2) [968483](https://platzi.com/comentario/968483/) 

	Cosas a tener en cuenta al momento de crear tu base de datos:
	
	Lightsail nos ofrece varias versiones de MySQL; si es un proyecto nuevo es recomendado utilizar la más actual. Si es una migración deberemos elegir la versión más cercana a nuestra base de datos existente.  
	Lightsail nos propone un password seguro, es recomendable usarlo.  
	Puedes configurar tu base de datos de dos maneras:  
	Estándar: Un servidor con una conexión desde afuera.  
	HA: Alta disponibilidad, donde tienes dos servidores o más con un load balancer.

* **Dante Castillo Z.** (1) [969044](https://platzi.com/comentario/969044/) 

	tenia la esperanza de encontrar postgreSQL y no veo por ningun lado cambiar de motor…

	* **EPadronU23** [969044] (1)

		ACtualmente lo ofrecen  
		![Screenshot_2020-03-17 Create a database Lightsail.png](https://static.platzi.com/media/user_upload/Screenshot_2020-03-17%20Create%20a%20database%20Lightsail-f88cf44b-2e1e-4204-856c-59a312ffbfa7.jpg)

* **johncastillotellez7** (1) [842204](https://platzi.com/comentario/842204/) 

	2 opciones de configurar la db.  
	1- un servidor con una db  
	2 ha high availability
	
	2 servidores con un loadbalancer al frente
	
	replica

	* **johncastillotellez7** [842204] (2)

		lightsail additional prod pay for using it.

* **Juan Francisco Mosquera** (1) [537252](https://platzi.com/comentario/537252/) 

	cuantas conexiones soportan estas bases de datos ?.  
	Esto es un RDS ?

	* **Diego Alexander Forero Higuera (Platzi)** [537252] (1)

		Es un servicio similar al de RDS, el número de conexiones depende de las características de la instancia.

	* **Juan Francisco Mosquera** [537252] (1)

		Gracias por tu respuesta , pero para dónde encontrar en número de conexiones a la base de datos utilizando Lightsail ?
		
		Esto es para RDS .  
		Type/Connections  
		t2.micro 66  
		t2.small 150  
		m3.medium 296  
		t2.medium 312  
		M3.large 609  
		t2.large 648  
		M4.large 648  
		M3.xlarge 1237  
		R3.large 1258  
		M4.xlarge 1320  
		M2.xlarge 1412  
		M3.2xlarge 2492  
		R3.xlarge 2540

* **Wigilabs SAS** (1) [527673](https://platzi.com/comentario/527673/) 

	¿Es posible conectar funciones creadas en lambda a una instancia de base de datos creada en lightsail?

	* **ebar0n (Platzi)** [527673] (1)

		Hola, por supuesto, desde lambda ejecutas codigo normal en el cual puedes hacer lo que quieras, debes ver en que lenguaje estas programando y buscar el parquete para conectarte usando las credenciales que te dan de la db en **lightsail**

	* **Camilo Ortegón** [527673] (1)

		Por supuesto, la única restricción es que se puedan ver, ya sea porque la base de datos tiene un endpoint público o porque están en el mismo VPC.

* **carlosextra1** (1) [448489](https://platzi.com/comentario/448489/) 

	Puedo instalar MYSQL en mi vps de forma manual y no pagar ello? o simepre tengo que pagar por la base de datos?

	* **Diego Alexander Forero Higuera (Platzi)** [448489] (4)

		Es completamente posible que instales mysql en tu instancia de lightsail o EC2, las ventajas que tiene el instalar usando los servicios como los de lightsail o rds es que tiene gestión de backups, puedes cambiar el tamaño de la instancia (aumentar o disminuir memoria ram por ejemplo) sin perdida de datos y con un downtime muy corto.

	* **juancajamarca** [448489] (3)

		Podrías hacerlo para ambientes de pruebas y de desarrollo.

* **andresnaranjo83** (1) [80956](https://platzi.com/comentario/970120/) 
Se puede instalar postgres?

	* **Juan David Castro (Platzi)** [80956] (1)

		¡Claro! Mira: <https://aws.amazon.com/es/rds/postgresql/>.
		
		También te recomiendo tomar este curso para profundizar: <https://platzi.com/clases/db-aws/>. :wink;

* **Juan Francisco Mosquera** (1) [55065](https://platzi.com/comentario/537252/) 
cuantas conexiones soportan estas bases de datos ?. Esto es un RDS ?

	* **Diego Alexander Forero Higuera (Platzi)** [55065] (1)

		Es un servicio similar al de RDS, el número de conexiones depende de las características de la instancia.

* **Wigilabs SAS** (1) [54269](https://platzi.com/comentario/527673/) 
¿Es posible conectar funciones creadas en lambda a una instancia de base de datos creada en lightsail?

	* **ebar0n (Platzi)** [54269] (1)

		Hola, por supuesto, desde lambda ejecutas codigo normal en el cual puedes hacer lo que quieras, debes ver en que lenguaje estas programando y buscar el parquete para conectarte usando las credenciales que te dan de la db en **lightsail**

* **carlosextra1** (1) [47897](https://platzi.com/comentario/448489/) 
Puedo instalar MYSQL en mi vps de forma manual y no pagar ello? o simepre tengo que pagar por la base de datos?

	* **Diego Alexander Forero Higuera (Platzi)** [47897] (4)

		Es completamente posible que instales mysql en tu instancia de lightsail o EC2, las ventajas que tiene el instalar usando los servicios como los de lightsail o rds es que tiene gestión de backups, puedes cambiar el tamaño de la instancia (aumentar o disminuir memoria ram por ejemplo) sin perdida de datos y con un downtime muy corto.

## 0180. Reto Lightsail [15538](https://platzi.com/clases/1427-aws-computo/15538-reto0123/)

### Descripción:


### Comentarios:

* **juancajamarca** (1) [923532](https://platzi.com/comentario/923532/) 

	Done!

* **carlosbazanhuaman** (1) [829758](https://platzi.com/comentario/829758/) 

	lo que me preocupa son las limitaciones que te pone amazon cuando quieres hacer algo como cargas o conexiones.  
	Ya que en un ec2 o un RDS te ponen algunas limitaciones.

	* **Dante Castillo Z.** [829758] (1)

		A que tipo de limitaciones te refieres ¿? porque no me percate de eso…

* **DiegoRP** (1) [530049](https://platzi.com/comentario/530049/) 

	Hola! Me quedó una duda: es posible aplicar grupos de seguridad en LightSail?

	* **Diego Alexander Forero Higuera (Platzi)** [530049] (2)

		Hola aquí encuentras información sobre el firewall de lightsail <https://lightsail.aws.amazon.com/ls/docs/en/articles/understanding-firewall-and-port-mappings-in-amazon-lightsail> funciona muy similar a los security groups de aws.

	* **Carlos Andrés Zambrano Barrera** [530049] (1)

		Es totalmente posible hacerlo, más gráficos que los normales de ec2. Pero personalmente me parece que lightsail aun le falta mucho para ser una buena herramienta, usualmente cuando intentas hacer cosas más interesantes te va a limitar por algún lado.

* **DiegoRP** (1) [54449](https://platzi.com/comentario/530049/) 
Hola! Me quedó una duda: es posible aplicar grupos de seguridad en LightSail?

	* **Diego Alexander Forero Higuera (Platzi)** [54449] (2)

		Hola aquí encuentras información sobre el firewall de lightsail <https://lightsail.aws.amazon.com/ls/docs/en/articles/understanding-firewall-and-port-mappings-in-amazon-lightsail> funciona muy similar a los security groups de aws.

# ECR/ECS/EKS [2979]

## 0190. Introducción a ECRECSEKS [15540](https://platzi.com/clases/1427-aws-computo/15540-introduccion-a-ecrecseks/)

### Descripción:


 **ECR** es el servicio que te permite registrar los contenedores a través de Dockerfiles en Amazon.  
Aunque existe **ECR** , no aparece como producto. Es necesario entrar a **ECS** y ya desde ahí encontramos las opciones para entrar al **ECR**.  
Importante antes de registrar contenedores: Tener instalado el **AWS CLI** y **Docker** , adicionalmente es importante tener instalado Git.

### Links:

* [ubuntu - Got permission denied while trying to connect to the Docker daemon socket while executing docker stop - Stack Overflow](https://stackoverflow.com/questions/46759268/got-permission-denied-while-trying-to-connect-to-the-docker-daemon-socket-while)

* [How To Install and Use Docker on Ubuntu 18.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04)

### Comentarios:

* **José David García Rodríguez** (7) [456836](https://platzi.com/comentario/456836/) 

	¿Dónde puedo visualizar la fecha de lanzamiento del curso? Si esto no está disponible, me gustaría que habilitaran la fecha de lanzamiento del curso y marquen contenidos como deprecated, para no seguir cursos que no vayan acorde a lo último del mercado, como lo es en el caso de AWS. No me baso en algo del curso, solo hago la observación como sugerencia de mejora para la plataforma…

	* **Daniel .** [456836] (1)

		Puede ser interesante, en aws se agregan y modifican servicios muy rápido.

* **Cristian David Franco Garcia** (4) [600332](https://platzi.com/comentario/600332/) 

	A la fecha de este comentario ya existe ECR en la sección de computo.
	
	![Screen Shot 2019-05-28 at 11.16.26 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-05-28%20at%2011.16.26%20PM-a06d13af-9fa1-4db4-94fe-34b92d71f5dd.jpg)

* **estebanvasquezvalencia** (4) [494697](https://platzi.com/comentario/494697/) 

	_**Instalación git:**_ apt-get install git  
	++ _**Instalación AWS CLI: **_ ++https://docs.aws.amazon.com/es_es/cli/latest/userguide/install-linux-al2017.html  
	**_Instalación Docker_**  
	<https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04>  
	_**Se debe crear un usuario en IAM con permisos:**_  
	-AmazonEC2ContainerRegistryFullAccess  
	-AmazonECS_FullAccess  
	-AmazonEC2ContainerRegistryPowerUser  
	**_Solucionar ERROR Using --password via the CLI:_**  
	<https://stackoverflow.com/questions/46759268/got-permission-denied-while-trying-to-connect-to-the-docker-daemon-socket-while>

	* **Juan Carrillo** [494697] (1)

		Gracias me sirvió tu ayuda, no se en que parte del curso se decia que había que hacerlo pero siguiendo estos pasos pude solucinar, Gracias!

* **Johan Manuel Merello Ortecho** (1) [991446](https://platzi.com/comentario/991446/) 

	Cada repositorio es para una aplicación distinta, no usar el mismo repositorio para 2 aplicaciones distintas, pues se sobrescribirá la anterior.

* **jorge-gianareas** (1) [968493](https://platzi.com/comentario/968493/) 

	Importante antes de registrar contenedores: Tener instalado el AWS CLI y Docker, adicionalmente es importante tener instalado Git.

* **jorge-gianareas** (1) [968492](https://platzi.com/comentario/968492/) 

	Aunque existe ECR, no aparece como producto. Es necesario entrar a ECS y ya desde ahí encontramos las opciones para entrar al ECR.

* **jorge-gianareas** (1) [968491](https://platzi.com/comentario/968491/) 

	ECR es el servicio que te permite registrar los contenedores a través de Dockerfiles en Amazon.

* **isra_rivero** (1) [952948](https://platzi.com/comentario/952948/) 

	Mi instancia no tenia instalado pip pero aquí el como:
	
	<https://linuxize.com/post/how-to-install-pip-on-ubuntu-18.04/>

* **johncastillotellez7** (1) [842207](https://platzi.com/comentario/842207/) 

	importante ECR es el servicio que te permite registrar los contenedores a través de Dockerfiles en Amazon.  
	Aunque existe ECR, no aparece como producto. Es necesario entrar a ECS y ya desde ahí encontramos las opciones para entrar al ECR.

	* **johncastillotellez7** [842207] (1)

		ECR permite usar kubernetes

	* **johncastillotellez7** [842207] (2)

		ECS and EKS have their docker container images.

* **Claudio Jesus Vázquez Villanueva** (1) [60904](https://platzi.com/comentario/612947/) 
Unable to locate credentials. You can configure credentials by running “aws configure”. ? como se resuelve esto

	* **Favio Náquira** [60904] (1)

		Utiliza el comando **aws configure** en tu línea de comandos, te pedirá todo lo necesario para iniciar

## 0200. Introducción a ECS [15541](https://platzi.com/clases/1427-aws-computo/15541-introduccion-a-ecs/)

### Descripción:


 **ECS** es toda la infraestructura que te permite correr contenedores de Docker directo en AWS.

* Su ventaja es que no debes poner una máquina con Docker donde encima corran los contenedores. Amazon da la infraestructura pre-hecha y nosotros solo elegimos capacidades.
* Únicamente se paga por la capacidad solicitada (cCPU, memoria, transferencia de datos).
* Puedes escalar tu instancia basada en contenedor de manera manual.



Usos clásicos de **ECS** :

* Microservicios.
* Migración de aplicaciones Legacy al Cloud.



### Links:

* [Amazon ECR | Amazon Web Services](https://aws.amazon.com/es/ecr/)

* [Â¿QuÃ© es Amazon Elastic Container Service? - Amazon Elastic Container Service](https://docs.aws.amazon.com/es_es/AmazonECS/latest/developerguide/Welcome.html)

### Comentarios:

* **clozarr** (4) [904160](https://platzi.com/comentario/904160/) 

	ECR es el DockerHub de AWS

	* **juancajamarca** [904160] (1)

		Buena comparación.

* **jorge-gianareas** (2) [968497](https://platzi.com/comentario/968497/) 

	Usos clásicos de ECS:
	
	Microservicios.  
	Migración de aplicaciones Legacy al Cloud.

* **jorge-gianareas** (1) [968496](https://platzi.com/comentario/968496/) 

	ECS es toda la infraestructura que te permite correr contenedores de Docker directo en AWS.
	
	Su ventaja es que no debes poner una máquina con Docker donde encima corran los contenedores. Amazon da la infraestructura pre-hecha y nosotros solo elegimos capacidades.  
	Únicamente se paga por la capacidad solicitada (cCPU, memoria, transferencia de datos).  
	Puedes escalar tu instancia basada en contenedor de manera manual.

* **jheyson7** (1) [945880](https://platzi.com/comentario/945880/) 

	que aplicaciones especificas podrian tener estos servicios ?

* **johncastillotellez7** (1) [852824](https://platzi.com/comentario/852824/) 

	ECS is a highly scalable, high performance container orchestration service that supports Docker containers and allows you to easily run and scale .

* **Diego Fernández Cruz** (1) [572638](https://platzi.com/comentario/572638/) 

	Cuál es la diferencia entre ECS y ECR ?  
	ECS es el servicio que aloja los repositorios registrados en ECR ? Por favor ayuda.

	* **kaia_6** [572638] (5)

		Amazon Elastic Container Service (Amazon ECS) es un **servicio de administración de contenedores** altamente escalable y rápido que facilita la tarea de ejecutar, detener y administrar contenedores de Docker en un clúster.
		
		Amazon Elastic Container Registry (ECR) **es un registro de contenedores** de Docker completamente administrado que facilita a los desarrolladores las tareas de almacenamiento, administración e implementación de imágenes de contenedores de Docker.!
		
		[Funcionamiento](https://d1.awsstatic.com/diagrams/product-page-diagrams/Product-Page-Diagram_Amazon-ECR.bf2e7a03447ed3aba97a70e5f4aead46a5e04547.png)

* **csierra** (1) [70110](https://platzi.com/comentario/769143/) 
Hola, En cuanto a desempeño, escalamiento y costo Qué diferencia tendía esta ECS comparado con Elastic Beanstalk ?

	* **Juan David Castro (Platzi)** [70110] (1)

		¡Hola!
		
		Te recomiendo estas comparaciones:
		
		👉 <https://www.reddit.com/r/aws/comments/7mjs6x/elastic_beanstalk_vs_ecs_fargate/>  
		👉 <https://codeday.me/es/qa/20190106/70721.html>  
		👉 <https://stackoverflow.com/questions/29584073/should-i-use-aws-elastic-beanstalk-or-the-amazon-ec2-container-service-ecs-to>  
		👉 <https://fortyft.com/posts/elastic-beanstalk-vs-ecs-vs-kubernetes/>  
		👉 <https://news.ycombinator.com/item?id=9560033>  
		👉 <https://www.reddit.com/r/aws/comments/4sk6a4/elastic_beanstalk_vs_ecs/>

* **Diego Fernández Cruz** (1) [58069](https://platzi.com/comentario/572638/) 
Cuál es la diferencia entre ECS y ECR ? ECS es el servicio que aloja los repositorios registrados en ECR ? Por favor ayuda.

	* **kaia_6** [58069] (5)

		Amazon Elastic Container Service (Amazon ECS) es un **servicio de administración de contenedores** altamente escalable y rápido que facilita la tarea de ejecutar, detener y administrar contenedores de Docker en un clúster.
		
		Amazon Elastic Container Registry (ECR) **es un registro de contenedores** de Docker completamente administrado que facilita a los desarrolladores las tareas de almacenamiento, administración e implementación de imágenes de contenedores de Docker.!
		
		[Funcionamiento](https://d1.awsstatic.com/diagrams/product-page-diagrams/Product-Page-Diagram_Amazon-ECR.bf2e7a03447ed3aba97a70e5f4aead46a5e04547.png)

## 0210. Corriendo un contenedor [15542](https://platzi.com/clases/1427-aws-computo/15542-corriendo-un-contenedor/)

### Descripción:


Cosas a tener en cuenta al momento de correr un contenedor:

* **Networking only** está basado en un producto llamado **AWS Fargate** que nos da la infraestructura de Docker sin tener que preocuparnos por las máquinas base y es el que usaremos en este proyecto.
* Es necesario crear una tarea relacionada con la imagen de Docker que creamos anteriormente.



### Comentarios:

* **LaCafeta Lab** (3) [434799](https://platzi.com/comentario/434799/) 

	como poner certificado ssl al fargate que se creó

	* **Carlos Andrés Zambrano Barrera** [434799] (1)

		Lo pones en un ALB y ahi mandas el tráfico al fargate… Así lo usamos en una app móvil sin problema

* **Javier Gabriel Aguilar Melgar** (2) [75343](https://platzi.com/comentario/868438/) 
En que momento se crea un repositorio? y como funciona este en el ECS?

* **LaCafeta Lab** (2) [46702](https://platzi.com/comentario/434799/) 
como poner certificado ssl al fargate que se creó

	* **Carlos Andrés Zambrano Barrera** [46702] (1)

		Lo pones en un ALB y ahi mandas el tráfico al fargate… Así lo usamos en una app móvil sin problema

* **jorge-gianareas** (1) [968500](https://platzi.com/comentario/968500/) 

	Es necesario crear una tarea relacionada con la imagen de Docker que creamos anteriormente.

* **jorge-gianareas** (1) [968499](https://platzi.com/comentario/968499/) 

	Networking only está basado en un producto llamado AWS Fargate que nos da la infraestructura de Docker sin tener que preocuparnos por las máquinas base y es el que usaremos en este proyecto.

* **Mateo Loaiza Rios** (1) [955663](https://platzi.com/comentario/955663/) 

	En los videos anteriores del curso, en ningún momento se hizo la creación de la imagen que se correrá en el video. Creo que deberían de tener cuidado, en cuanto a estos problemas.

* **Humberto Jacob Mori Guerra** (1) [900084](https://platzi.com/comentario/900084/) 

	Hola comunidad , con este video he podido correr un task sin problema , y acceder desde la IP public , aqui es donde viene mi pregunta . como puedo hacer para que esta IP use HTTPS ?

	* **juancajamarca** [900084] (2)

		Debes comprar un dominio y generarle certificado SSL. Aprende cómo hacerlo en el curso de Networking & Content Delivery con AWS. 😉

* **johncastillotellez7** (1) [852840](https://platzi.com/comentario/852840/) 

	utiles tambien para Machine learning applications. tambien ayuda amonitorear y da el detalle sobre recursos usados.

* **angel-aldrete** (1) [824658](https://platzi.com/comentario/824658/) 

	Como puedo hacer trabajar múltiples containers en un Task Definition? Por ejemplo, cómo se podria subir a ECS una aplicación tipo PHP con Nginx, las cuales trabajan en 2 containers separados, no consigo la manera de hacer que funcionen

* **Juan Carrillo** (1) [789037](https://platzi.com/comentario/789037/) 

	En mi caso tuve que crear el rol de ejecución de tareas en IAM manualmente, siguiendo estos pasos <https://docs.aws.amazon.com/es_es/AmazonECS/latest/developerguide/task_execution_IAM_role.html>, por si alguien le pasa igual

* **luiseduardiazc** (1) [580627](https://platzi.com/comentario/580627/) 

	¿ como se actualiza el contenedor con un nuevo despliegue ? la tarea no actualiza automáticamente la nueva imagen del repositorio. he intentado de todo. Si creo un servicio y lo actualizo forzando nuevo despliegue, crea una tarea nueva con una nueva ip . La idea seria que actualizara solo el contenedor y que la tarea quede con la misma ip.  
	¿ alguien sabe como se hace ?

	* **yograterol** [580627] (3)

		Por lo general se realiza la configuración del entorno de tal forma de que el container se pueda acceder con un alias así la IP se vuelve irrelevante, en caso de que requieras asignar una IP fija debes ver en qué Network de Docker estás colocando el container y usar `--ip` seguido del número de IP.
		
		Para que la imagen se actualice debes hacer una estrategia para eso, podría ser:
		
		1- Hacer docker pull cada vez que necesites actualizar.  
		2- Cambiar la etiqueta de la imagen y hacer docker pull de esta forma puedes volver a un estado anterior.
		
		Si o si se debe crear un contenedor nuevo.

	* **raparisg** [580627] (1)

		@yograterol. Comentas que generalmente se hace la configuración del entorno para que pueda acceder por un alias, Puedes darme alguna directriz para hacer esto?

* **Victoria Tejeda** (1) [555687](https://platzi.com/comentario/555687/) 

	En este caso se supone que platziweb es el nombre de la imagen del contenedor? No veo en qué parte del curso se envía la imagen desde el EC2 hacia el repositorio que se creó. ¿como se envía la imagen? supongo que con un push pero de amazon en vez de docker.

* **luiseduardiazc** (1) [58723](https://platzi.com/comentario/580627/) 
¿ como se actualiza el contenedor con un nuevo despliegue ? la tarea no actualiza automáticamente la nueva imagen del repositorio. he int...

	* **yograterol** [58723] (3)

		Por lo general se realiza la configuración del entorno de tal forma de que el container se pueda acceder con un alias así la IP se vuelve irrelevante, en caso de que requieras asignar una IP fija debes ver en qué Network de Docker estás colocando el container y usar `--ip` seguido del número de IP.
		
		Para que la imagen se actualice debes hacer una estrategia para eso, podría ser:
		
		1- Hacer docker pull cada vez que necesites actualizar.  
		2- Cambiar la etiqueta de la imagen y hacer docker pull de esta forma puedes volver a un estado anterior.
		
		Si o si se debe crear un contenedor nuevo.

* **Victoria Tejeda** (1) [56687](https://platzi.com/comentario/555687/) 
En este caso se supone que platziweb es el nombre de la imagen del contenedor? No veo en qué parte del curso se envía la imagen desde el ...

## 0220. Instalando ambiente docker en EC2 [15386](https://platzi.com/clases/1427-aws-computo/15386-instalando-ambiente-docker-en-ec2/)

### Descripción:


## Introducción

Para poder ejecutar comandos como “docker build” necesitamos configurar nuestro ambiente de docker en una instancia EC2 pequeña.

## Configuración de Docker

* Crea una instancia de EC2 con Ubuntu.
* Selecciona una instancia de tamaño mínimo (nano, por ejemplo, si tienes una cuenta AWS de mas de un año. - En caso contrario, la t2.micro es la gratuita en tu primer año de servicio (recuerda, únicamente por un año).
* Una vez que este en estado “Running” conectate a ella.
* Teclea:  
**a)** sudo su  
**b)** apt-get update
* Una vez que termine, corre, como usuario root:  
**a)** snap install docker -y  
**b)** apt-get install git -y
* Después de esto, ya podrás hacer:  
**a)** git clone <https://github.com/mauropm/quotes-generator.git>  
**b)** cd quotes-generator  
**c)** dock build



Con esto, ya podrás hacer imágenes de contenedores y siguiendo las instrucciones de la clase, podrás enviarlo a ECR (El registro de contenedores de AWS).

### Comentarios:

## 0230. Introducción a EKS [15543](https://platzi.com/clases/1427-aws-computo/15543-introduccion-a-eks/)

### Descripción:


* **EKS** es una implementación de Kubernetes en Amazon que no requiere que coordines nodos maestros y esclavos.
* Te permite crear un ambiente de workers de k8s en **AWS**.
* Podrás correr contenedores con el dashboard de Kubernetes o cualquier orquestador que quieras usar.



**EKS** va desde poner el nodo maestro de Kubernetes, poner los workers y ya podrás conectarte a la API para correr tareas.

### Links:

* [Amazon EKS – Servicio de Kubernetes administrado](https://aws.amazon.com/es/eks/)

* [Production-Grade Container Orchestration - Kubernetes](https://kubernetes.io/)

### Comentarios:

* **Daniel .** (3) [474588](https://platzi.com/comentario/474588/) 

	 **Kubernetes** (K8S) se define como un sistema open-source para la automatización de despliegues, el escalado y la gestión de aplicaciones contenerizadas.

	* **juancajamarca** [474588] (1)

		Buen aporte.

* **jorge-gianareas** (2) [968504](https://platzi.com/comentario/968504/) 

	EKS es una implementación de Kubernetes en Amazon que no requiere que coordines nodos maestros y esclavos.  
	Te permite crear un ambiente de workers de k8s en AWS.  
	Podrás correr contenedores con el dashboard de Kubernetes o cualquier orquestador que quieras usar.

* **jorge-gianareas** (1) [968506](https://platzi.com/comentario/968506/) 

	EKS va desde poner el nodo maestro de Kubernetes, poner los workers y ya podrás conectarte a la API para correr tareas

* **johncastillotellez7** (1) [852861](https://platzi.com/comentario/852861/) 

	EKS provisiona y despliega directamente los masters de kubernetes.

* **johncastillotellez7** (1) [852859](https://platzi.com/comentario/852859/) 

	Kubernetes is an open-source container-orchestration system for automating application deployment, scaling, and management. It was originally designed by Google, and is now maintained by the Cloud Native Computing Foundation

* **carlosbazanhuaman** (1) [829839](https://platzi.com/comentario/829839/) 

	pense que aws usaba su propia herramienta para trabajar orquestadores pero veo que trabaja a la par con kubernetes para esto.  
	Saludos.

## 0240. Configuración kops  k8s en AWS [15388](https://platzi.com/clases/1427-aws-computo/15388-configuracion-kops-k8s-en-aws/)

### Descripción:


## Introducción

kops es una herramienta que nos permite crear y administrar kubernetes (también conocido como k8s) en AWS (y otros clouds). En esta lectura pondremos las instrucciones para configurarlo localmente y crear un cluster de k8s en AWS.

## Instrucciones

Como root, en alguna instancia EC2 pequeña o en su máquina local (estas instrucciones son para linux).

* sudo apt update
* sudo apt install -y awscli
* sudo snap install kubectl --classic
* curl -LO <https://github.com/kubernetes/kops/releases/download/1.7.0/kops-linux-amd64>
* chmod +x kops-linux-amd64
* mv ./kops-linux-amd64 /usr/local/bin/kops
* Tienen que crear un usuario llamado kops en IAM.
* Entren en IAM, hagan un nuevo usuario.
* Configuren esto como acceso programatico.
* Apunten el Access Key ID y el password.
* Asígnenle el rol de AdministratorAccess (un rol preconfigurado en AWS IAM).
* Salvar.
* Regresen de la consola de AWS a tu consola / terminal, y continúen con lo siguiente:
* aws config
* aws iam create-group --group-name kops
* aws iam attach-group-policy --policy-arn arn:aws:iam::aws:policy/AmazonEC2FullAccess --group-name kops
* aws iam attach-group-policy --policy-arn arn:aws:iam::aws:policy/AmazonRoute53FullAccess --group-name kops
* aws iam attach-group-policy --policy-arn arn:aws:iam::aws:policy/AmazonS3FullAccess --group-name kops
* aws iam attach-group-policy --policy-arn arn:aws:iam::aws:policy/IAMFullAccess --group-name kops
* aws iam attach-group-policy --policy-arn arn:aws:iam::aws:policy/AmazonVPCFullAccess --group-name kops
* aws iam add-user-to-group --user-name kops --group-name kops
* aws s3api create-bucket --bucket s3kopstudominiocom --region us-west-2
* Antes de ejecutar el próximo comando, anexen lo siguiente a su archivo ~/.bashrc (al final):  
export AWS_ACCESS_KEY_ID=tuaccesskey  
export AWS_SECRET_ACCESS_KEY=tusecret  
export KOPS_STATE_STORE=s3://s3kopstudominiocom  
export KOPS_CLUSTER_NAME=kops-cluster-tudominio
* Sálvenlo. Cierren sesión con “exit” y vuelvan a entrar. Ahora si, ejecuta:
* kops create cluster --name=kops-cluster-tudominio --cloud=aws --zones=us-west-2a --state=s3kopstudominiocom
* Esta operación puede tardar 20 minutos.
* Cuando terminen, denle:  
kubectl apply -f <https://raw.githubusercontent.com/kubernetes/dashboard/master/src/deploy/recommended/kubernetes-dashboard.yaml>
* Con eso, se instalará el dashboard de k8s que vieron en el ejemplo.
* Loguearse con user admin, y el password se obtiene con:  
kops get secrets kube --type secret -oplaintext
* Cuando se conecten, seleccionen anunciarse por token, y el token lo obtienen ejecutando lo siguiente:  
kops get secrets admin --type secret -oplaintext
* Con eso, ya podrán dar click en “Create” y poder poner su imagen del contenedor en ECR.
* Cuando termine de hacer el deployment, encontrarán la url en la sección en el menú llamada “Services”.



## Nota:

Si estas instrucciones las llevan a cabo en su máquina local, si tecleas kubectl proxy, tendrán el dashboard en la dirección: <https://localhost:8001> \- Noten que usa https siempre, y que el certificado no es confiable, por lo que tendrán que autorizar a su browser para poder abrirlo. La url completa para el dashboard, utilizando kubectl proxy, es:

<http://localhost:8001/api/v1/namespaces/kube-system/services/https:kubernetes-dashboard:/proxy/#!/login>

## Conclusión:

Esta actividad no es fácil. Kubernetes es un proyecto en construcción, por lo que está en constante cambio todo el tiempo, y evoluciona tan rápido que estas instrucciones podrían volverse obsoletas pronto, por lo que les pido que no desesperen, y que si hay alguna situación que no esté funcionando, pregunten en la sección de comentarios.

### Comentarios:

* **Ernesto Jose Gabriel Lopez Bravo** (1) [633892](https://platzi.com/comentario/633892/) 

	Que otras herramientas están disponibles para administrar kubernetes?

	* **Diego Alexander Forero Higuera (Platzi)** [633892] (2)

		existe kubeadm y Kubespray, puedes leer mas de estos aquí <https://www.altoros.com/blog/a-multitude-of-kubernetes-deployment-tools-kubespray-kops-and-kubeadm/> yo he usado kops y para mi es el que mejor funciona.

* **Daniel .** (1) [474606](https://platzi.com/comentario/474606/) 

	Se puede decir que se usa k8s como un sistema de integración continua?

	* **Diego Alexander Forero Higuera (Platzi)** [474606] (2)

		No, kubernetes permite administrar un cluster de contenedores docker, es similar a swarm. Este provee una interfaz gráfica para administrar los pods, services, deployments etc dentro del cluster de kubernetes.

	* **Juan Emmanuel Díaz** [474606] (3)

		k8s=kubernetes = k 8 letras  
		Es un sistema de orquestación de contenedores

## 0250. Reto ECRECSEKS [15544](https://platzi.com/clases/1427-aws-computo/15544-reto1349/)

### Descripción:


### Comentarios:

* **edisoncastro14** (5) [447471](https://platzi.com/comentario/447471/) 

	¿Cuál es la mejor forma de borrar imágenes antiguas en el repositorio?

* **edisoncastro14** (3) [447477](https://platzi.com/comentario/447477/) 

	¿Cuál es el proceso para migrar de una infraestructura que corre en ECS pero sobre máaquinas ec2 a una que utilice Fargate?

* **edisoncastro14** (2) [447473](https://platzi.com/comentario/447473/) 

	¿Cómo me aseguro que la tarea que tengo corriendo está usando la última definición de tarea?

	* **migue20** [447473] (2)

		Hay unas banderas en la definición de tareas. En general la última dirá latest cuando vas modificas un servicio.

* **juancajamarca** (1) [927574](https://platzi.com/comentario/927574/) 

	Done.

# Lambda [3032]

## 0260. Introducción a Lambda [15546](https://platzi.com/clases/1427-aws-computo/15546-introduccion-a-lambda/)

### Descripción:


 **Lambda** es un producto que implementa la filosofía de **Serverless** , lo cual significa no tener un servidor sino tener funciones que hagan cosas muy específicas (sin embargo sí se usan servidores que administra **AWS** sin que tú pienses en ello). Es código que puede conectarse a una base de datos, servicios web, etc.

En el mundo clásico se tenía un servidor o grupo de servidores corriendo software y teniendo microservicios. El software internamente resolvía todo y todo consistía en llamadas al mismo código. Con **Lambda** el enfoque es más de separar las funciones, ponerlas en diferentes servicios y correremos una parte del código en diferentes _endpoints_.

**Lambda escala automáticamente:** Esto quiere decir que si tu microservicio comienza a usarse más, se te brindarán más recursos para que corra siempre correctamente.

El costo de **Lambda** es atractivo porque AWS te da 1 millón de llamadas gratis por mes y cuando te excedas de eso, el costo es muy bajo.

Lenguajes soportados:

* Node.js (JavaScript)
* Python
* Java
* C#
* Go



### Links:

* [AWS Lambda – Preguntas frecuentes](https://aws.amazon.com/es/lambda/faqs/)

### Comentarios:

* **karkastell** (4) [691783](https://platzi.com/comentario/691783/) 

	Hay aquí un curso enfocado o detallado sobre la creación de funciones en Lambda?

	* **juancajamarca** [691783] (1)

		Practica con lo que ya sabes, la práctica hace al maestro 😉.

* **jsteven** (3) [543302](https://platzi.com/comentario/543302/) 

	Para Scala existen algunas librerías que permiten usar el SDK de aws de Java. Es interesante por lo simple que es usar un lenguaje funcional y que se adapta muy bien a la filosofía de programar con funciones atómicas.

* **jorge-gianareas** (2) [968527](https://platzi.com/comentario/968527/) 

	Lambda escala automáticamente: Esto quiere decir que si tu microservicio comienza a usarse más, se te brindarán más recursos para que corra siempre correctamente.
	
	El costo de Lambda es atractivo porque AWS te da 1 millón de llamadas gratis por mes y cuando te excedas de eso, el costo es muy bajo.
	
	Lenguajes soportados:
	
	Node.js (JavaScript)  
	Python  
	Java  
	C#  
	Go

* **jorge-gianareas** (2) [968524](https://platzi.com/comentario/968524/) 

	Lambda es un producto que implementa la filosofía de Serverless, lo cual significa no tener un servidor sino tener funciones que hagan cosas muy específicas (sin embargo sí se usan servidores que administra AWS sin que tú pienses en ello). Es código que puede conectarse a una base de datos, servicios web, etc.

* **jorge-gianareas** (1) [968525](https://platzi.com/comentario/968525/) 

	En el mundo clásico se tenía un servidor o grupo de servidores corriendo software y teniendo microservicios. El software internamente resolvía todo y todo consistía en llamadas al mismo código. Con Lambda el enfoque es más de separar las funciones, ponerlas en diferentes servicios y correremos una parte del código en diferentes endpoints.

* **johncastillotellez7** (1) [852902](https://platzi.com/comentario/852902/) 

	importantisimo>Con Lambda el enfoque es más de separar las funciones, ponerlas en diferentes servicios y correremos una parte del código en diferentes endpoint

* **carlosbazanhuaman** (1) [829862](https://platzi.com/comentario/829862/) 

	lo interesante es que puede escalar solo.

## 0270. Configuración de función lambda [15545](https://platzi.com/clases/1427-aws-computo/15545-configuracion-de-funcion-lambda/)

### Descripción:


Cosas a tener en cuenta al momento de configurar una función Lambda:

* La opción de **Blueprints** se refiere a un documento o plano de lo que vas a hacer.
* Para cada una de las funciones hay que crear un rol que dé acceso a los recursos de **AWS** que nosotros elijamos. Por default, sólo trae unos permisos básicos. La idea es dar el menor número de permisos posibles.
* Puedes aprender a manejar el CLI <https://aws.amazon.com/es/cli/> para otorgar permisos por línea de comandos.
* La entrada de un **Lambda** es un **API Gateway**.



### Links:

* [AWS Serverless Application Repository - Amazon Web Services](https://aws.amazon.com/serverless/serverlessrepo/)

### Comentarios:

* **carlosextra1** (4) [448492](https://platzi.com/comentario/448492/) 

	es muy desesperante el volumen, no se escucha bien.

* **johncastillotellez7** (3) [852947](https://platzi.com/comentario/852947/) 

	Deberia de haber mas ejemplos de como usuar funcioens lambda ya que es bien potente esta herramienta.  
	y poder practicar mas.  
	slds

* **Luis Guillermo Pardo Fonseca** (3) [503732](https://platzi.com/comentario/503732/) 

	Una lástima, no se escucha bien

	* **johncastillotellez7** [503732] (1)

		todo los audios + video de este curso suena muy bajito y no escucha bien. lo podrian mejorar en la edicion de videos.  
		Slds

* **carlosextra1** (2) [448495](https://platzi.com/comentario/448495/) 

	donde podemos ver mas funciones ? de nuevo por el audio no se entiende

	* **Diego Alexander Forero Higuera (Platzi)** [448495] (2)

		Aquí <https://aws.amazon.com/serverless/serverlessrepo/> encuentras información sobre las funciones que están en el repositorio de aplicaciones serverless.

* **Marcos Rissotto** (1) [986069](https://platzi.com/comentario/986069/) 

	Casi no se escucha estando el volumen al máximo…

* **jorge-gianareas** (1) [968530](https://platzi.com/comentario/968530/) 

	Cosas a tener en cuenta al momento de configurar una función Lambda:
	
	La opción de Blueprints se refiere a un documento o plano de lo que vas a hacer.  
	Para cada una de las funciones hay que crear un rol que dé acceso a los recursos de AWS que nosotros elijamos. Por default, sólo trae unos permisos básicos. La idea es dar el menor número de permisos posibles.  
	Puedes aprender a manejar el CLI <https://aws.amazon.com/es/cli/> para otorgar permisos por línea de comandos.  
	La entrada de un Lambda es un API Gateway.

* **RaulAlanGarciaMtz** (1) [871428](https://platzi.com/comentario/871428/) 

	no me gustan los cursos de platzi son muy teoricos y todo eso esta en la documentacion yo aprendo viendo ejemplos

	* **fidekof** [871428] (1)

		Pues es verdad esta en la documentación, pero este pana lo explica con ejemplos en la practica que es bueno para saber lo mas importante, el precio y tener una idea general de todas las opciones y cual es mas conveniente usar

	* **juancajamarca** [871428] (3)

		La práctica depende de ti, de tu curiosidad. De eso se trata esta industria.

	* **JerezA** [871428] (3)

		Eh… no se que clase en particular viste, pero por ejemplo muy puntal en esta el hace todo el ejercicio de manera practica, yo he tomado aproximadamente 20 o mas cursos de platzi y todos son muy muy practicos, que caso particular te toco a ti de teorico?

* **johncastillotellez7** (1) [852930](https://platzi.com/comentario/852930/) 

	ese volumen tan bajo de todos los audios es bien tedioso y aburre.

* **carlosbazanhuaman** (1) [829875](https://platzi.com/comentario/829875/) 

	blueprint = plano diagrama arquitectónico

* **Juan Sebastian Piedrahita Gonzalez** (1) [659379](https://platzi.com/comentario/659379/) 

	Se puede configurar Lambda tambipen para que se ejecute periodicamente creando reglas de ejecución en cloudwatch.

* **Camilo Ortegón** (1) [501518](https://platzi.com/comentario/501518/) 

	Hay alguna forma de leer las variables de entorno desde un lugar centralizado, para modificar la configuración de varias funciones desde desde el mismo lugar?

	* **Carlos Andrés Zambrano Barrera** [501518] (1)

		No entiendo muy bien tu pregunta, sin embargo cuando manejamos funciones, contenedores o algun servicio que requiera cadenas de conexión seguras usamos Parameter Store en AWS que cifra las cadenas de conexión y nos permite llamarlas como variables de entorno. Importante que el role en este caso de la función tenga permisos sobre SSM.

	* **sergio-mata** [501518] (1)

		si se puede si haces tu lambda usando serverless framework e instalando el plugin de dotenv o si usas infrasestructura como código

* **Camilo Ortegón** (1) [52153](https://platzi.com/comentario/501518/) 
Hay alguna forma de leer las variables de entorno desde un lugar centralizado, para modificar la configuración de varias funciones desde ...

	* **Carlos Andrés Zambrano Barrera** [52153] (1)

		No entiendo muy bien tu pregunta, sin embargo cuando manejamos funciones, contenedores o algun servicio que requiera cadenas de conexión seguras usamos Parameter Store en AWS que cifra las cadenas de conexión y nos permite llamarlas como variables de entorno. Importante que el role en este caso de la función tenga permisos sobre SSM.

## 0280. Reto Lambda [15547](https://platzi.com/clases/1427-aws-computo/15547-reto9608/)

### Descripción:


El reto de esta clase consiste en crear una función **Lambda** con su **API Gateway** probando con diferentes lenguajes y diferentes códigos. Juega con los **Blueprints** y todas las opciones que tienes para crear funciones.

### Links:

* [AWS | Lambda - Gestión de recursos informáticos](https://aws.amazon.com/es/lambda/)

### Comentarios:

* **Camilo Ortegón** (8) [501520](https://platzi.com/comentario/501520/) 

	Fue corto lo que explicaron sobre Lambda, y la verdad tiene mucho potencial.

	* **juancajamarca** [501520] (2)

		En el curso de Fundamentos de AWS, hacen un ejercicio con una función Lambda.

* **carlosbazanhuaman** (4) [829881](https://platzi.com/comentario/829881/) 

	seria bueno un curso sobre la creacion de funciones lambda en algun lenguaje de los que soporta.

* **jsteven** (3) [543307](https://platzi.com/comentario/543307/) 

	Sería genial si en esta sección se hablara también de Stepfunction que es con lo que mayor potencial se le puede sacar a AWS Lambda.

* **EPadronU23** (1) [1047395](https://platzi.com/comentario/1047395/) 

	Lambda + API Gateway (RESTish API) + Authentication + JSON Schema validation
	
	* **Lambda setup:**  
	![Lambda + API Gateway](https://static.platzi.com/media/user_upload/Screenshot_20200319_062137-a0d5ade0-6f42-46f1-928b-a28c95cdf574.jpg)
	* **Good request:**  
	![Good request](https://static.platzi.com/media/user_upload/Screenshot_20200319_062045-4c581698-0df0-4ccb-b471-64b7a191be8c.jpg)
	* **Bad request:**  
	![Bad request](https://static.platzi.com/media/user_upload/Screenshot_20200319_062031-a0d8ac1d-d3f6-406b-b0e6-7dc0d4614486.jpg)
	* **Request handler:**  
	![Request handler](https://static.platzi.com/media/user_upload/Screenshot_20200319_061947-8eb7453f-46fb-4c8a-927a-97a762074034.jpg)
	
	

* **johncastillotellez7** (1) [852943](https://platzi.com/comentario/852943/) 

	It is a computing service that runs code in response to events and automatically manages the computing resources required by that code. It was introduced in November 2014.
	
	Lamb corre tu codigo solamente cuando se dispar.  
	Eston ejemplos son super interesantes>
	
	Real time file processing>For example, you can use Lambda to thumbnail images, transcode videos, index files, process logs, validate content, and aggregate and filter data in real-time.
	
	real time stream processing>  
	You can use AWS Lambda and Amazon Kinesis to process real-time streaming data for application activity tracking, transaction order processing, click stream analysis, data cleansing, metrics generation, log filtering, indexing, social media analysis, and IoT device data telemetry and metering
	
	EXTRACT, TRANSFORM, LOAD  
	You can use AWS Lambda to perform data validation, filtering, sorting, or other transformations for every data change in a DynamoDB table and load the transformed data to another data store
	
	entre otros
	
	IOT BACKENDS  
	You can build serverless backends using AWS Lambda to handle web, mobile, Internet of Things (IoT), and 3rd party API requests.

* **alexgv04** (1) [67240](https://platzi.com/comentario/719849/) 
cuanto tiempo se puede tardar la ejecución de una lambda?

	* **carlosantonio_** [67240] (1)

		El maximo de ejecucion normal 15 minutos.

# Elastic Beanstalk [3033]

## 0290. Introducción a Elastic Beanstalk [15548](https://platzi.com/clases/1427-aws-computo/15548-introduccion-a-elastic-beanstalk/)

### Descripción:


 **Elastic Beanstalk** es una arquitectura para cuando vas a hacer una entrega a producción de un proyecto web que tengas. Su ventaja es que incluye todo lo que necesitas en un sólo paquete:

* Tienes un _Endpoint_ donde puedes a través de _Route 53_ * editar tu dominio.
* Puedes tener un **Load Balancer**
* Tienes instancias **EC2** Linux o Windows con soporte a muchos lenguajes.



Maneja las siguientes plataformas:

* Docker
* Go
* Java SE
* Java / Tomcat
* .NET (sobre Windows)
* NodeJS
* PHP
* Otros



**Elastic Beanstalk** te permite de manera muy fácil hacer un rollback, teniendo una gran flexibilidad para hacer un arreglo.  
Esta arquitectura es auto-escalable dependiendo del tráfico o necesidades.

### Comentarios:

* **edwintrumpet** (4) [620177](https://platzi.com/comentario/620177/) 

	No se escucha nada 😦  
	Yo no sé como llegué tan lejos en este curso con este volumen, pero este video si es que en realidad hay que esforzarse mucho

	* **alexgv04** [620177] (1)

		es cierto todo el curso al 100% el volumen, pero este si esta complicado.

	* **Ernesto Lázaro Guerrero** [620177] (1)

		X2

	* **alexjcm** [620177] (1)

		Utilicen audífonos o monitores para apreciar el audio con mejor calidad.

* **Danilo Pazos** (3) [856652](https://platzi.com/comentario/856652/) 
Volumen demasiado bajito 😭

* **jorge-gianareas** (2) [968538](https://platzi.com/comentario/968538/) 

	Maneja las siguientes plataformas:
	
	Docker  
	Go  
	Java SE  
	Java / Tomcat  
	.NET (sobre Windows)  
	NodeJS  
	PHP  
	Otros

* **jorge-gianareas** (2) [968536](https://platzi.com/comentario/968536/) 

	Elastic Beanstalk es una arquitectura para cuando vas a hacer una entrega a producción de un proyecto web que tengas. Su ventaja es que incluye todo lo que necesitas en un sólo paquete:
	
	Tienes un Endpoint donde puedes a través de Route 53* editar tu dominio.  
	Puedes tener un Load Balancer  
	Tienes instancias EC2 Linux o Windows con soporte a muchos lenguajes.

* **Salvador Jose Campanella Salas** (2) [881812](https://platzi.com/comentario/881812/) 

	Hay un vídeo anterior a este que me sale como bloqueado ,
	
	Configurando un ambiente para una nueva versión
	
	Esto se debe a algo ?

* **aleducode** (2) [511587](https://platzi.com/comentario/511587/) 

	Alguna manera de conectar el elasticbeantalk directamente a una rama en github o bitbucket sin necsidad de usar .zip

	* **Salvador Jose Campanella Salas** [511587] (1)

		Creo que esta documentacion te puede ayudar  
		<https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb3-cli-git.html>

	* **juancajamarca** [511587] (1)

		Buena pregunta.

* **Daniel .** (2) [474637](https://platzi.com/comentario/474637/) 

	$1 más de volumen pf

* **EPadronU23** (1) [1049706](https://platzi.com/comentario/1049706/) 

	¿Qué **diferencia** hay entre desplegar una aplicación/servicio con **EKS** vs **Elastic Beanstalk**?  
	.  
	En teoría, con el primero también se puede tener un dominio, balanceador de cargas, auto-escalamiento de nodos… Aún mejor, se pueden tener múltiples servicios corriendo en el mismo _proyecto_ de EKS. Mientras que con Elastic Beanstalk, es la misma aplicación/servicio corriendo en todas las instancias de EC2, ¿o me equivoco?  
	.  
	¿La diferencias solo radica en el **enfoque**? Me refiero a **contenedores** vs **máquinas virtuales**.

* **DavidMG01** (1) [995087](https://platzi.com/comentario/995087/) 

	Se escucha muy bajito…

* **jorge-gianareas** (1) [968539](https://platzi.com/comentario/968539/) 

	Elastic Beanstalk te permite de manera muy fácil hacer un rollback, teniendo una gran flexibilidad para hacer un arreglo.  
	Esta arquitectura es auto-escalable dependiendo del tráfico o necesidades.

* **_toniokj_** (1) [957498](https://platzi.com/comentario/957498/) 

	apenas le escucho, 😦

* **johncastillotellez7** (1) [852949](https://platzi.com/comentario/852949/) 

	Por favor mejorar el volumen de este curso. es desesperante que uno queire escuchar lo que dice y no se escucha casi nada.
	
	Gcs

* **Roger Vilà** (1) [851630](https://platzi.com/comentario/851630/) 

	Es una lastima con el buen curso que es, llevamos muchas clases y el volumen tan bajo es un poco estresante ya que en poco ruido que tengas a tu alrededor te hace despistar !!!

* **Winston Barbosa** (1) [82664](https://platzi.com/comentario/1009986/) 
Una instancia montada en Lightsail podria usar beanstalk o solo opera con instancias EC2?

* **Carlos uribe** (1) [79527](https://platzi.com/comentario/941683/) 
Si yo tengo actualmente una aplicación en una instancia EC2 con su propia base de datos mysql instalada, al momento del autoscalling… Los...

* **carlosbazanhuaman** (1) [73172](https://platzi.com/comentario/829884/) 
en temas de precios es mas caro que lightsail?

	* **Erik Ochoa** [73172] (1)

		Primero hay que diferenciarlos:
		
		**Lightsail** : es una forma sencilla y de menor costo para tener un servidor privado virtual por un precio fijo y predecible con suscripción mensual y anual.
		
		**Elastic Beanstalk** : es un servicio para administrar tus servidores en AWS, apunta aplicaciones más complejas ya que maneja deploys automáticos, balanceo de cargas, auto-escalamiento entre muchas otras cosas. Por Elastic Beanstalk no pagas en realidad, pagas por los recursos que tengas en AWS (EC2, S3 buckets etc.). Pagas por lo que usas y no hay una cuota mínima o contratos restrictivos.
		
		Para darte una mejor idea, se podría decir que :
		
		* Lightsail fue creado para competir con GoDaddy.
		* Elastic Beanstalk fue creado para competir con Heroku.
		
		
		
		Recomiendo Lightsail si vas empezando y sólo quieres probar.

* **karkastell** (1) [65442](https://platzi.com/comentario/691805/) 
Esto es similar ECS?, no me es claro que es Beanstalk

	* **Carlos Andrés Zambrano Barrera** [65442] (1)

		es completamente diferente. EBN es más para desplegar aplicaciones, por ejemplo tienes un .war y queres desplegarlo facilmente podes subirlo a EBN y ya lo tienes desplegado, de una vez te arroja un endpoint que podes conectar a R53.
		
		Igualmente podes hacerlo con imagenes docker para desplegar aplicaciones si quieres, pero orquestas todo dentro del servicio, autoscaling, imagenes, base de datos y demas. En ECS es más de solo containers.

## 0300. Creando un ambiente [15550](https://platzi.com/clases/1427-aws-computo/15550-creando-una-ambiente/)

### Descripción:


Cosas a tener en cuenta al momento de crear un ambiente:

* Debemos tener nuestra aplicación en un archivo .zip. Si es la primera vez que usas el comando para crear archivos .zip, debes poner esto en la línea de comandos “sudo apt-get install zip -y”.  
El comando para crear el archivo .zip es “zip -r nombredelzipfile.zip archivos”. Muchos archivos deberán ponerse de forma explícita como los .env
* En “Version label” es recomendado poner el número de la versión que estamos manejando que nos permite recordar cuando tenemos más archivos y podamos devolvernos en el tiempo a alguna versión en específico si lo requerimos.



### Comentarios:

* **jorge-gianareas** (2) [968542](https://platzi.com/comentario/968542/) 

	En “Version label” es recomendado poner el número de la versión que estamos manejando que nos permite recordar cuando tenemos más archivos y podamos devolvernos en el tiempo a alguna versión en específico si lo requerimos.

* **jorge-gianareas** (2) [968541](https://platzi.com/comentario/968541/) 

	Debemos tener nuestra aplicación en un archivo .zip. Si es la primera vez que usas el comando para crear archivos .zip, debes poner esto en la línea de comandos “sudo apt-get install zip -y”.  
	El comando para crear el archivo .zip es “zip -r nombredelzipfile.zip archivos”. Muchos archivos deberán ponerse de forma explícita como los .env

* **johncastillotellez7** (2) [857754](https://platzi.com/comentario/857754/) 

	EL ELB es bien poderoso para realizar proyectos. deberian de dar otros ejemplos

* **Jose Luis Campos Bautista** (1) [1060405](https://platzi.com/comentario/1060405/) 

	Debemos de incluir los archivos de configración, como por ejemplo .env

* **juancajamarca** (1) [927835](https://platzi.com/comentario/927835/) 

	¿Saben si hay alguna forma de subir proyectos que no sean por .zip?

* **Elias Ojeda Medina** (1) [729641](https://platzi.com/comentario/729641/) 

	La clase de Configurando un ambiente para una nueva versión, no se encuentra disponible

## 0320. Reto Sube una aplicación en Elastic Beanstalk [15549](https://platzi.com/clases/1427-aws-computo/15549-reto-sube-una-aplicacion-en-elastic-beanstalk/)

### Descripción:


### Comentarios:

* **johncastillotellez7** (3) [857755](https://platzi.com/comentario/857755/) 

	interesante el curso, aunque pueden colocar mas ejercicios practicos.

* **Camilo Ortegón** (2) [501531](https://platzi.com/comentario/501531/) 

	Puedo generar un ambiente de ElasticBeanstalk que corra múltiples instancias con diferentes lenguajes, sin necesidad de usar docker?

* **Camilo Ortegón** (2) [52155](https://platzi.com/comentario/501531/) 
Puedo generar un ambiente de ElasticBeanstalk que corra múltiples instancias con diferentes lenguajes, sin necesidad de usar docker?

* **juancajamarca** (1) [927837](https://platzi.com/comentario/927837/) 

	Done.

* **carlosbazanhuaman** (1) [829894](https://platzi.com/comentario/829894/) 

	intentare subir una app de angular 7, supongo que una configuracion minima es suficiente.

* **vcentt-lopez** (1) [542361](https://platzi.com/comentario/542361/) 

	No lo puedo creer, hasta estuvo mejor explicado y mejor los ejercicios de Elastic Beanstalk en el curso de Fundamentos de AWS Cloud

	* **Emmanuel Sosa Reyes** [542361] (1)

		Exactamente

	* **Dante Castillo Z.** [542361] (1)

		Eso mismo! pienso que hubieran unido fundamentos con este curso.

* **avalohack** (1) [480571](https://platzi.com/comentario/480571/) 

	se me generaron muchos inconvenientes para conectarla a una bd dado que mi aplicación estaba construida en codeigniter

	* **avalohack** [480571] (1)

		en el momento la tengo corriendo en lightsail

# Conclusiones [3034]

## 0330. Trabajo Futuro [15551](https://platzi.com/clases/1427-aws-computo/15551-trabajo-futuro/)

### Descripción:


 **AWS** está en constante crecimiento, siempre tendrá nuevos servicios o features. No dejes de estar aprendiendo nuevas cosas y capacitandote cada vez más.

### Comentarios:

* **jr22morales** (5) [437124](https://platzi.com/comentario/437124/) 

	Hola Mauro, como obtengo certificado de este curso?.. se queda al 70% y no tiene examen…

	* **Brayan Mamani** [437124] (1)

		Ya esta disponible !!

* **Elias Ojeda Medina** (4) [729720](https://platzi.com/comentario/729720/) 

	Debería ser más detallada la parte de Lambda, además de explicar el Serverless Framework

	* **alexjcm** [729720] (2)

		Concuerdo contigo deberían explicar más a fondo la parte de Lambda en AWS

	* **Dante Castillo Z.** [729720] (1)

		En fundamentos de AWS creo que esta mas detallado esta parte.

* **johncastillotellez7** (3) [857762](https://platzi.com/comentario/857762/) 

	es completamente cierto AWS es un monstrou que siempre esta innovando y generando nuevas herramientas poderosas para el cloud.  
	el equipo de desarrollo de aws es potente.

* **carlosbazanhuaman** (3) [829895](https://platzi.com/comentario/829895/) 

	el contenido es un poco mas del curso de introduccion pero igual hay mucho mas por investigar.

* **Dante Castillo Z.** (2) [973310](https://platzi.com/comentario/973310/) 

	Excelente curso!

* **juancapote** (1) [1029682](https://platzi.com/comentario/1029682/) 

	Excelente Curso, solo veo que le falta un par de practicas mas por tema.

* **juancajamarca** (1) [927839](https://platzi.com/comentario/927839/) 

	Muchas gracias. ¡Excelente curso!

* **Javier Gabriel Aguilar Melgar** (1) [75384](https://platzi.com/comentario/869049/) 
Consulta, para ofrecer servicios AWS como empresa es posible?

	* **Israel Yance** [75384] (2)

		Claro que sí, pero tienes que dar algún servicio agregado que le agregue valor a la empresa. Revender el servicio tal cual no tiene sentido.

* **jr22morales** (1) [46946](https://platzi.com/comentario/437124/) 
Hola Mauro, como obtengo certificado de este curso?.. se queda al 70% y no tiene examen…

	* **Brayan Mamani** [46946] (1)

		Ya esta disponible !!

