# Introducción

## 0010. Introducción a Automatización

### Descripción:


 **Automatizamos** porque nos deja reproducir procesos y nos otorga mayor productividad, si los corremos manualmente podemos aburrirnos lo que nos lleva a saltarnos pasos y a generar errores. Por eso los automatizamos y podemos pasar más tiempo haciendo código, implementando nuevos features.

Podemos **automatizar** correr pruebas, correr deployments, la verificación de la disponibilidad de nuestro sitio, podemos verificar cualquier cosa.

### Comentarios:

* **Iván Mauricio Toro Cifuentes** (7)

	
	Automatización = Mayor productividad.

* **SebastianMelo7** (5)

	
	Jenkins es un servidor de automatización open source escrito en Java.

	* **juancajamarca** (1)

		
		Buenos fundamentos.

* **Pablo Enrique Pulido Vilchez** (5)

	
	Que chevere que platzi traiga estos cursos! Muchisimas gracias. Tambien al profe Yamil, por todo su aporte!

* **James David Contreras García** (3)

	
	Hola:  
	¿En un flujo de integración Continua cuál es el lugar que ocuparía Jenkins y qué otras herramientas existen en el mercado que cumplan la misma función de Jenkins?  
	Gracias

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Hola. Jenkins puede estar en varias partes del flujo, Jenkins se usa para ejecutar tareas como test sobre todo el código de la aplicación, una vez los test son pasados reporta a github por ejemplo. Otra parte es en la parte de deploy una vez se hacer merge de la rama con master Jenkins puede realizar tareas de deployment por ejemplo a kubernetes, o usar packer y terraform para deploys de infraestructura inmutable.
		
		Alternativas a Jenkins son CircleCI o Travis, pero estos son SaaS (Software as a Service) mientras que Jenkins se puede instalar y configurar en tu propia infraestructura.

* **jaime repizo** (3)

	
	Que bueno que hagan estos cursos.

* **dbzdavidbaez** (1)

	
	Listo a seguir aprendiendo

* **carlosextra1** (1)

	
	esto suena a implementacion de jobs

* **Geovanny Javier Páez García** (1)

	
	Jenkins me interesa mucho, espero mucho del curso

* **robertoangelvaldez** (1)

	
	Espero este curso me ayude a cimentar el uso de jenkins

* **Cesar Andres Urrea Gutierrez** (1)

	
	Interesante ¡comencemos! ❤️

* **HeartHunter** (1)

	
	Comenzando el camino como devops pero para big data

	* **fernandajofili (Platzi)** (1)

		
		Asegúrate de seguir la ruta de aprendizaje de [Big Data y Data Science](https://platzi.com/clases/learning-path/datos/)! Hay muchos cursos interesantes.

* **Agustin David Luzenti** (1)

	
	Jajaja muy bueno. Perfecta primera impresion con el profe, muy emocionado!

* **jhonnyzapata** (1)

	
	muchas expectativas con este curso !!!

* **avalohack** (1)

	
	Genial

* **tho13718** (1)

	
	Excelente , Espere este Cursos …!! Gracias

* **sbdsoftfact** (0)

	
	Uff que sonsonete de los venecos, no están para dictar cursos zzz

	* **william andres rodriguez borja** (12)

		
		tu comentario no aporta nada constructivo.  
		le he tomado a este docente su curso de devOps 2018 , estoy tomando el actual de devOps y este de jenkins excelente.  
		si hubiera curso de como no ser xenofobico en platzi te lo recomendaria.

	* **Kervin Cortez** (3)

		
		no me parece tu comentario… ademas el profesor es puerto riqueño

	* **SebastianMelo7** (1)

		
		Jajajajaja

	* **davcode** (4)
Ese tipo de comentarios no van con la comunidad platzi , espero que tomen medidas ante tu tonto comentario.

# Jenkins Core

## 0020. Introducción a Jenkins

### Descripción:


 **Jenkins** es open source y probablemente el software de automatización más usado de todos, escrito en Java y corre en JVM. Es muy conveniente al ser una herramienta **extensible** al tener un ecosistema de **plugins** que te permiten extenderlo, puedes escribir tus propios **plugins** con Java, pero ya la comunidad ha desarrollado un sinfín de ellos.

También nos permite escalar de manera horizontal y verticalmente, puede correr un sin número de trabajos concurrentemente en una sola máquina y si esa máquina no da abasto se le puede dar más recursos a **Jenkins**. O una máquina no es suficiente entonces **Jenkins** nos permite escalar horizontalmente con _““slaves””_ y controlar varios nodos para que trabajen por él.

**Jenkins** siempre esta siendo innovado y teniendo actualizaciones de seguridad, esto es importante porque es el _target_ más grande de seguridad de una empresa porque lo tiene todo.

Algo que **Jenkins** ha trabajado mucho en los últimos años es que puedes escribir tus _““jobs””_ o unidades de trabajo en código. Nosotros queremos que nuestra automatización también sea programática, no solo los comando a ejecutar sino poder migrar nuestro trabajo a un nuevo **Jenkins** de manera reproducible. Han creado _Pipelines as code_

### Comentarios:

* **Jose Adan Ardila Sanchez** (11)

	
	A tener en cuenta:
	
	Jenkins usa Java 8 por lo menos al día en que este comentario se publica, por esa razón deben asegurarse de instalarlo, no sea que les genere errores.  
	[](https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04#installing-specific-versions-of-openjdk)
	
	quienes tenían una versión más reciente y manejan ubuntu por ejemplo, luego de instalar java 8 pueden ejecutar el siguiente comando para seleccionar la versión de java que se aplicará por defecto.
	
	sudo update-alternatives --config java

	* **Iván Mauricio Toro Cifuentes** (2)

		
		Buen aporte.

	* **jairhop** (1)
Se agradece !

* **Sergio Antonio Ochoa Martinez** (7)

	
	## Caracteristicas
	
	  * Es Open Source
	  * Escrito en java sobre JVM
	  * Mayormente se corre en Linux
	  * Es extensible
	  * Se puede escribir plugins en java
	  * La comunidad aporta tanto escribiendo un sin fin de Plugins.
	  * Jenkins es amigable y flexible por la cantidad de comunidad que tiene.
	  * Compañias enormes tiene un solo jenkins
	  * Jenkins puede crecer horizontalmente añadiendo mas hadware ya que soporta esto con el termino **slaves**.
	  * Jenkins es un servicio de automatización.
	  * CircleCI realiza lo mismo que jenkins.
	  * Actualmente se puede escribir tu job con codigo y no solo con la interfaz.
	
	

	* **Geovanny Javier Páez García** (1)

		
		gracias

	* **carlosextra1** (1)

		
		gracias! buen aporte

* **RoquilloGuri** (5)

	
	hola a todos, le envió el enlace donde el señor yamil tiene todos los script para el curso, lo coloco porque es necesario.  
	<https://github.com/elbuo8/platzi-scripts>

* **German Luis Guillermo Fica** (4)

	
	**Jenkins** es open source y probablemente el software de automatización más usado de todos, escrito en Java y corre en JVM. **Jenkins** es muy conveniente. Ya que **Jenkins** es una herramienta extensible; esto quiere decir que tiene un **ecosistema de plugins** que te permiten extenderlo. Si quieres, _puedes escribir tus propios plugins con Java_ , pero ya la comunidad ha desarrollado un sinfín de ellos💪🏻

	* **rafaelcarmona** (1)

		
		muy buen aporte

* **Jorge Fernandez Conejeros** (3)

	
	Java… 😦

	* **Josué Isaac Fuentes López** (2)

		
		#java es cool, porque le tienes miedo?

* **Salvador Pallares Pallares** (2)
Hola, Que diferencia hay entre Jenkins y gitlab?

	* **Gustavo Garcia Millasaky** (2)

		
		Depende de donde lo mires. La función principal de Gitlab es actuar como un repositorio de código. En este contexto, Es muy diferente a Jenkins ya que este último es una herramienta para Continuous Integration (CI), el cual es un proceso en donde se toma el código fuente de ciertas ramas (por lo general develop y master) y se hace todo un procedimiento que consta de:
		
		  1. Ejecución de test unitarios.
		  2. Clonación de repositorio.
		  3. Compilación de código.
		  4. Despliegue (opcional)
		
		
		
		Esto asegura en todo momento que los nuevos commits no rompan nada.
		
		Por otro lado, Gitlab también cuenta de “Pipelines”, que hace un trabajo similar al que hace una herramienta CI. En este contexto, no hay muchas diferencias. Te recomiendo comparar ambas opciones.

* **roodriaguilar** (1)

	
	A conoce una nueva herramienta

* **dbzdavidbaez** (1)

	
	A aprender ha automatizar con Jenkins
	
	[Jenkins](https://jenkins.io/)

* **HeartHunter** (1)

	
	Instalando Jenkins en Docker

* **Henry_Coarite** (1)

	
	Nos puedes comentar algo sobre jenkins en docker como comentario.

* **David Eliezer Orantes González** (1)

	
	Jenkins se utiliza para Continuos Delivery, haciendo más rapido el Deploy de herramientas y ambientes para producción, pruebas o desarrollo.

* **jorgehernandezjd** (1)

	
	Jenkins se convierte en honey pots (patade conejo) contiene en un solo lugar todo lo importante

	* **William Calderón Castillo** (1)

		
		HoneyPot realmente se refiere a un tarro de miel donde los insectos irán sin pensar. Jenkins con todo lo que puede guardar se convierte en un tarro de miel para los hacker.s

	* **juancajamarca** (1)

		
		Es el objetivo para los hackers.

* **Viviana Paola Romero Rojas** (1)
como usaria jenkins con java?

## 0030. Instalación y Configuración Básica de Jenkins

### Descripción:


### Links:

* [
Jenkins User Documentation
](https://jenkins.io/doc/)

### Comentarios:

* **Daniel Alvarez Aguilera** (16)

	
	**Les dejo el listado de comandos para facilitar el proceso: **  
	_(recuerda habilitar el puerto 8080 en tu máquina)_
	
	  * `sudo apt-get update`
	  * `sudo apt-get upgrade`
	  * `sudo apt-get install openjdk-8-jdk wget gnupg`
	  * `sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'`
	  * `sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9B7D32F2D50582E6`
	  * `sudo apt-get update`
	  * `sudo apt-get install git jenkins`
	  * `ssh-keygen`
	  * `service jenkins start`
	  * `service jenkins status`
	  * `sudo cat /var/lib/jenkins/secrets/initialAdminPassword`  
	**[@jmgamest](https://twitter.com/jmgamest)**
	
	

	* **j2rojasr** (4)

		
		Siempre es bueno encontrarse con estos comentarios, facilitan mucho el avance del curso, muchas gracias.

	* **HeartHunter** (1)

		
		Gracias

	* **Geovanny Javier Páez García** (1)

		
		Gracias maestro

	* **oscarsalazar0991** (1)

		
		Buenas, para que sirve esta linea específicamente :
		``` 
		    sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9B7D32F2D50582E6
		    
		```
		
		Ese numero es generado por quien o que ?

* **Juan Gabriel Castro Bustos** (13)

	
	Si tienen docker pueden correr jenkins en un docker con el comando
	
	docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts
	
	Despues desde un navegador ingresar a <http://127.0.0.1:8080/>

	* **Briones D. Jose** (1)

		
		Muchas gracias por el consejo

	* **Francisco Martin Nacimiento** (1)

		
		Gracias por el aporte, la imagen oficial esta deprecada y tuve problemas con los plugins que pedían la versión más actual de Jenkins. Pero con esta imagen ningún problema.

* **Iván Mauricio Toro Cifuentes** (9)

	
	Ubuntu 18.04
	``` 
	    sudo apt update
	    
	    sudo apt install openjdk-8-jdk wget gnupg
	    
	    wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
	    
	    sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
	    
	    sudo apt update
	    
	    sudo apt install jenkins
	    
	    systemctl status jenkins
	    
	```
	
	  * [Fuente](https://linuxize.com/post/how-to-install-jenkins-on-ubuntu-18-04/).
	
	

* **Sebastian Borrajo** (7)

	
	Una cosa que pueden hacer en su maquina local es en un folder crear otro folder llamado jenkins_home y al lado un docker-compose.yml con el siguiente codigo
	``` 
	    version: '3'
	    services:
	      jenkins:
	        container_name: jenkins
	        image: jenkins/jenkins
	        ports:
	          - "8080:8080"
	        volumes:
	          - $PWD/jenkins_home:/var/jenkins_home
	        networks:
	          - net
	    networks:
	      net:
	    
	    
	```
	
	y despues le dan en la consola a docker-compose up -d
	
	ahora con entrar al localhost con ese puerto ya estariamos!

	* **Juan Carlos Atanacio Quintero** (2)

		
		eso es de docker no de jenkins 😦

	* **Michael Alejandro Ura Acosta** (1)

		
		Pensaba en usar algo asi, gracias por el scrip, quiero incluirlo con sonarqube y que jenkins lo detecte, sabes como puedo realizar esto?

* **Alejandro Ortegano** (7)

	
	recomendacion instalarlo atra ves de docker XD

	* **jesusmurf** (1)

		
		Primero deberé aprender a usar Docker 😄

	* **silviopd** (3)

		
		<https://github.com/jenkinsci/docker/blob/master/README.md>
		
		documentación de como correr jenkins en docker

* **Juan J. Martínez** (7)

	
	Instalación sobre Linux(debian):
	``` 
	    <
	    wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
	    sudo sh -c'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
	    sudo apt-getupdate
	    sudo apt-get install jenkins
	    >
	    
	```

* **dbzdavidbaez** (5)

	
	Listo. Funcionado en WSL (Ubuntu 18 )para Windows  
	**Comandos**
	``` 
	    sudo apt-get update
	    sudo apt-getupgrade
	    sudo apt-getinstall openjdk-8-jdk wget gnupg
	    sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
	    sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9B7D32F2D50582E6
	    sudo apt-getupdate
	    sudo apt-getinstall git jenkins
	    ssh-keygen
	    service jenkins start
	    service jenkins status
	    sudo cat /var/lib/jenkins/secrets/initialAdminPassword
	    
	```

	* **oscarsalazar0991** (1)

		
		Gracias !

* **RenzoP** (4)

	
	Una instalación más básica y sencilla que propone la doc de Jenkins es descargando el .war:
	
	1- Download Jenkins (el .war).  
	2- Open up a terminal in the download directory.  
	3- Run java -jar jenkins.war --httpPort=8080.  
	4- Browse to <http://localhost:8080>.
	
	Claro que para que funcione debe estar instalado java en sus maquinas
	
	Link: <https://jenkins.io/doc/pipeline/tour/getting-started/>

* **Jhon Alexander Romero Gonzaga** (3)

	
	Una buena practica seria que se instalaran una máquina virtual con Ubuntu Sever en el programa VirtualBox para simular que en verdad estamos trabajando en un servidor aparte sin llenar de archivos nuestro disco donde esta nuestro sistema operativo. Es mi recomendación y espero les ayude.

* **Lethart** (2)

	
	Lo instale en windows y no me servia, simplemente verifiquen en el cmd como administrador con este comando **netstat -a -b** si hay programas estan escuchando el puerto 8080 si es así… vayan a la carpeta de jenkins y editen el archivo jenkins.xml, cambian el puerto y desde el administrador de tareas van a servicios buscan jenkins y le dan detener y luego iniciar.

* **Pedro Perafán Carrasco** (2)

	
	Si lo instalan en una maquina virtual local o digitalocean les puede servir <https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-18-04>

* **Edgar Valdez Moises** (2)

	
	hay forma de cambiar el puerto donde corre Jenkins ?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Si, cuando lo vas a ejecutar usas el flag --httpPort=<numero de puerto> por defecto es 8080, puedes ver otros flags para configurar el inicio de Jenkins aquí <https://wiki.jenkins.io/display/JENKINS/Starting+and+Accessing+Jenkins>

* **Rogelio Laureano** (2)

	
	Instale la imagen de jenkinsci/blueocean en mi mac, les dejo el link de la instalación.  
	<https://jenkins.io/doc/book/installing/#installing-docker>

* **Viviana May Jibi  Delgado Bethermy** (2)

	
	Para el comando delas keys en esta parte: --recv-keys todos debemos colocar el mismo código?

	* **Viviana May Jibi  Delgado Bethermy** (2)

		
		Encontre la respuesta xD  
		<https://fabianlee.org/2017/02/21/jenkins-setting-up-a-continuous-integration-server-on-ubuntu/>

* **Germain Rafael Bueno Taguariparo** (2)

	
	Para los que usan ubuntu los repositorios cambiaron y pueden que tenga error. Si ese es el caso acá la documentación correspondiente
	
	<https://wiki.jenkins.io/display/JENKINS/Installing+Jenkins+on+Ubuntu>

* **JDiaz0017** (2)

	
	PREGUNTA:  
	Para el caso de instalar Jenkis en un servidor Linux (Ubuntu 18.04 por ejemplo), no hay problema con que se encuentre corriendo previamente el servidor apache en el puerto 80?  
	Es decir, pueden convivir Jenkis en el puerto 8080 y Apache en el puerto 80?  
	Muchas gracias.

* **hansfpc** (2)

	
	¿Qué es eso de añadir el Keyserver? ¿qué es?

	* **jorgehernandezjd** (3)

		
		Es una llave ssh quegeneran los sistemas Linux , esta llave es ideal para conectarse de manera remota a un server linux.
		
		Obviamente el curso esta orientado a maquinas servidores linux

* **carlosextra1** (2)
Puedo cargar Jenkins en en maquina virtual de aws y sin problema tener ahí todo mi entorno verdad?

	* **Cristhian Arce** (1)

		
		Es correcto, yo lo tengo en mi instancia personal de ec2 y funciona

* **Hanson Garzon** (2)
Buenas noches, podrían adjuntar los comandos que realicen, a la descripción del curso?? muchas gracias

* **David Behar** (1)

	
	Para obtener la ip del servidor ubuntu usar el comando:
	``` 
	    wget -qO- https://ipecho.net/plain ; echo
	    
	```

* **miguelangelsoler** (1)

	
	Instalarlo en centos 7 fue una odisea

* **oscarsalazar0991** (1)

	
	Esto funciono para AWS la version free tier de ubuntu 18
	``` 
	    sudo apt-get update
	    sudo apt-getupgrade
	    sudo apt-getinstall openjdk-8-jdk wget gnupg
	    wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-keyadd -
	    sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
	    sudo apt update
	    sudo apt install jenkins
	    sudo apt-getinstall jenkins
	    service jenkins start
	    service jenkins status
	    sudo cat /var/lib/jenkins/secrets/initialAdminPassword```
	    
	    ![Screen Shot 2020-04-02 at 3.09.13 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-04-02%20at%203.09.13%20PM-e25a735b-c7f8-4cef-b843-7bd59f38511f.jpg)
	    
	```

* **José Tuzinkievicz** (1)

	
	Si al ingresar te dice que Jenkins está Offline
	
	**Editar** /var/lib/jenkins/hudson.model.UpdateCenter.xml   
	y cambiar la url a usar de **https** a **http**.

* **José Tuzinkievicz** (1)

	
	Con Java 11 en Ubuntu server 16.04 funciona a la perfección.
	
	[Instalar](https://maslinux.es/como-instalar-openjdk-11-en-ubuntu-18-04-16-04-o-14-04-linux-mint-19-18-o-17/) Java 11 en Ubuntu versiones menores a 19.
	
	Instalación de Jenkins
	
	`wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add - sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list' sudo apt-get update sudo apt-get install jenkins`

* **José Tuzinkievicz** (1)

	
	Creando la llave con  
	**ssh-keygen **  
	sin parámetros, genera una llave de 2048 bits. Para mejorarla se la puede crear con 4096 de la siguiente manera, como lo explican en el curso de Git y GitHub.  
	**ssh-keygen -t rsa -b 4096 -C["mimail@mail.com](mailto:%22mimail@mail.com)"**

* **juancajamarca** (1)

	
	  * Se actualizan los paquetes del sistema operativo.
	  * Se instala Java 8.
	  * Se añade el repositorio de Jenkins.
	  * Se añade el keyserver.
	  * Se vuelven a actualizar los paquetes del sistema operativo.
	  * Se instala Git.
	  * Se instala Jenkins.
	  * Se crea una llave SSH para el servidor.
	
	

* **HeartHunter** (1)

	
	Instalando Jenkins en mi servidor privado, luego en la nube

* **Augusto Gonzalez** (1)

	
	Por error instale Java 11 en mi EC2 AWS, sin embargo si funciono el Jenkins, alguien por casualidad sabe si hubo alguna actualizacion?

	* **RenzoP** (1)

		
		Bueno tengo entendido que Jenkins funciona a partir de Java 8 asi que cualquier versión posterior a la 8 esta bien.

* **pablovass** (1)

	
	yo use la ubuntu maquina virtual que esta en la microsoft store para instalar jenkins . y funciona super bien en el localhost:8080

* **mauriciodinki** (1)

	
	Actulización: Pueden instalar jenkins desde debian teniendo la versión 11, no funciona con la 9 ni 10, anexo instrucciones desde la página oficial: <https://pkg.jenkins.io/debian/>
	
	Para los demás SO  
	<https://jenkins.io/download/>

* **IDH** (1)

	
	Hola a tod@s,
	
	tengo permisos de administrador pero no me deja iniciar Jenkins.
	
	sudo service jenkins start  
	env: /etc/init.d/jenkins: Permission denied
	
	Alguna sugerencia, por favor?
	
	Saludos,

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Cómo instalaste jenkins?

* **rockerserch** (1)

	
	Comando instalar java

* **marcoxio** (1)

	
	@jesusmurf  
	Muy excelente tu aporte acabo de venir del curso de docker y que genialidad montar eso desde las imagenes.

* **Celia Guadarrama Piña** (1)

	
	Como obtengo la ip de mi jenkins ?

	* **Celia Guadarrama Piña** (1)

		
		al no encontrar la ip despues de cerrar la conexion como en el video, la ip que toma es la del equipo en mi caso  
		Direc. inet:127.0.0.1

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Si lo creas como en la clase que es un droplet en digital ocean vas a poder entrar a tu admin de digital ocean y ver la ip del droplet. Si lo instalaste en tu maquina local la ip es 127.0.0.1 o localhost.

* **Juan Pena Verdú** (1)

	
	Lo he instalado con Vagrant sobre Ubuntu 14 y no se me para de caer el servicio… ¿alguna idea?

	* **Pedro Perafán Carrasco** (1)

		
		Cuando de ram y CPU le tienes asignado? me pasaba lo mismo, solo le aumente los recursos.

* **Antonio Gonzalez** (1)

	
	hola, tengo un error al querer instalar java8.  
	dice que el paquete no fue encontrado.
	``` 
	    Reading package lists... Done
	    Building dependency tree
	    Reading state information... Done
	    E: Unable to locate package openjdk-8-jdk
	    
	    
	```
	
	estoy buscando y no e encontrado solución al respecto, gracias de antemano compañeritos 😄

	* **mmondragonp** (1)

		
		sudo add-apt-repository ppa:openjdk-r/ppa  
		sudo apt-get update  
		sudo apt-get install openjdk-8-jdk
		
		Lo que pasa es que no agregaste el repositiro y no actualizaste el listado cuando ejecutaste la tercera línea.

* **JDiaz0017** (1)

	
	Logrado en mi máquina virtual Ubuntu 18.04 (tradicional) 😄  
	![jenkis_ok.png](https://static.platzi.com/media/user_upload/jenkis_ok-fc4a372e-5d27-4b70-8740-e65159aded4b.jpg)

* **JDiaz0017** (1)

	
	OJO Ojito: para quienes tienen problemas de permisos en su máquina virtual linux, al menos en mi caso, lo solucioné con: sudo chmod 777 "carpeta secrets" y de igual manera al fichero initialAdminPassword para poder leer la contraseña y autenticarnos en la página de inicio.

* **JDiaz0017** (1)

	
	PREGUNTA #2  
	Al terminar la instalación en windows, apareció todo checkeado en verde (las tareas completadas en cuanto a instalación) PERO, únicamente el SSH no apareció checkeado/chuleado en verde, sino con una X roja, debería de generar manualmente una llave SSH antes de llevar a cabo la instalación en dicho entorno WINDOWS?.  
	muchas gracias.

* **Raul Palacios** (1)

	
	Por si lo quieren instalar en otro sistema operativo [Aquí los paquetes](https://jenkins.io/download/)

* **David Quintanar Pérez** (1)
¿Cómo genero la llave ssh para Jenkins únicamente?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Puedes explicar mejor lo que quieres hacer.

* **Joan Sebastian Siabato Fonseca** (1)
Buen día, Quisiera ayuda con algo. Realice la instalación de Jenkins en mi pc windows 10, pero hoy cuando intento ingresar y/o conectarme...

* **James David Contreras García** (1)
si instalo Jenkins de manera local sobre Windows, una vez que se ha descargado el instalador, me lleva a la secuencia de pasos que están ...

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Si, no hay problema, no vas a perder ninguna funcionalidad.

* **Juan Pena Verdú** (1)
Lo he instalado con Vagrant sobre Ubuntu 14 y no se me para de caer el servicio… ¿alguna idea?

	* **Pedro Perafán Carrasco** (1)

		
		Cuando de ram y CPU le tienes asignado? me pasaba lo mismo, solo le aumente los recursos.

* **Viviana May Jibi  Delgado Bethermy** (1)
Para el comando delas keys en esta parte: --recv-keys todos debemos colocar el mismo código?

	* **Viviana May Jibi  Delgado Bethermy** (2)

		
		Encontre la respuesta xD  
		<https://fabianlee.org/2017/02/21/jenkins-setting-up-a-continuous-integration-server-on-ubuntu/>

* **hansfpc** (1)
¿Qué es eso de añadir el Keyserver? ¿qué es?

	* **jorgehernandezjd** (3)

		
		Es una llave ssh quegeneran los sistemas Linux , esta llave es ideal para conectarse de manera remota a un server linux.
		
		Obviamente el curso esta orientado a maquinas servidores linux

* **David Cornejo** (0)

	
	notable 6:33
	
	consulta, en mi caso estoy implementando sonarqube y jenkins, el tema es que jenkins lo tengo instalado en mi maquina y sonarqube lo tengo en contenedor(docker).
	
	En mi experiencia con este tipo de servicios se me hace mucho mas facil montarlos con docker, me gustaria preguntar, ¿Hay algun inconveniente con lo que planteo?

## 0040. Manejo Básico de Usuarios

### Descripción:


### Comentarios:

* **Matias Sebastian Perez** (5)

	
	Alguien mas se percató del pequeño lorem ipsum del cartelito del nombre??

	* **juancajamarca** (2)

		
		Yo no, pero mi compañera sí 😅

* **Luzdelia Alba** (5)

	
	  * Se pueden crear nuevos usuarios y asignarles diferentes permisos, esto con el fin de poder saber en todo momento, o auditorías quien hizo que…
	
	  * Lo ideal es no compartir mismos usuarios ni misma contraseña.
	
	  * La autenticación se puede dar por medio de login con Github o Google, esto con el uso de plugins.
	
	
	
	
	**Para crear, eliminar, editar un usuario:**  
	Ir a Manage Jenkins/ Manage Users/ Create user (en caso de crear). Para editar o borrar solo se debe dar clic en user id deseado, después elegir opción _Configurar_ o _Borrar_

	* **Geovanny Javier Páez García** (1)

		
		Gracias

	* **carlosextra1** (1)

		
		buen aporte, gracias!

* **Krystle Salazar** (4)

	
	Login con cuenta de Github, ¡eso será interesante verlo!

* **Pedro Jesus Hincapie Garcia** (4)

	
	Excelente curso, los temas son claros, conciso y preciso.

* **Gerardo Alberto Soto Alvarez del Castillo** (2)

	
	El PlugIn para registrasce con la cuenta de Google es el siguiente:  
	Google Login  
	Allows you to log in to Jenkins with a Google account and restrict access to a Google Apps Domain.

* **dbzdavidbaez** (1)

	
	Entendido.

* **MsJenniferMilagros** (1)

	
	Login con cuenta de Gitlab, eso sería mas interesante aun

* **Cristhian Camilo Hernandez Perez** (1)
Estoy instalando en windows, en la parte de instalación de plugins veo errores de instalación como verifico la causa del error para dete...

	* **Juan David Castro (Platzi)** (1)

		
		Puedes mostrarnos los errores y te ayudamos a leer el log para encontrar la solución. 😉

# Jobs

## 0050. ¿Qué es un Job

### Descripción:


En esta clase veremos la unidad más importante de Jenkins, los trabajos( **Jobs** ) que ejecuta, puede correr varios de estos a la vez y es controlado por el **Build Executor**.

Podemos tener **Jobs** de diferentes tipos como Freestyle project, Pipeline, folder, Multi-configuration project, etc.

Cada vez que ocurre una ejecución de un **Job** se añade un numero al **Build History** y sirve para tener auditorias de cuál trabajo fue el último success o fail.

### Comentarios:

* **Erika Hernández** (8)

	
	Para este ejemplo, en el caso de Windows, podemos seleccionar en la configuración del job:  
	Build > Execute Windows batch command (Ejecutar > Ejecutar un comando de Windows)  
	En lugar de “Execute Shell”

	* **James David Contreras García** (1)

		
		Muchas gracias, me sirvió vuestro aporte

* **jesusmurf** (4)
Yo tampoco conocía lo de la bolita

	* **Iván Mauricio Toro Cifuentes** (2)

		
		Muy útil esa bolita. 😄

	* **Geovanny Javier Páez García** (1)

		
		Muy importante, te ahorra tiempo

* **Juan Pablo Montoya Cardona** (4)

	
	Para ejecutar Jenkins en windows es posible que necesiten cambiar las configuraciones e instalar el shell para que reconozca el comando 😃

	* **JDiaz0017** (1)

		
		Así es, principalmente, tener en cuenta descargar el archivo jenkis.war, tener instalado Java 8 y ejecutar el comando adecuado java -jar jenkis.war + ENTER si mal no estoy.  
		No obstante, crearé un tutorial para instalar Jenkis con windows.  
		Basta con tener git bash que es una excelente herramienta para correr comandos basados en Unix dentro del entorno windows 😄  
		Saludos.

* **Marcoh** (3)

	
	  * Builds son cada ejecución de un job.
	
	

* **JDiaz0017** (3)

	
	Primer tarea ok:  
	![jenkis_build.png](https://static.platzi.com/media/user_upload/jenkis_build-eaff3cb2-19f8-4818-b145-41ff4ac82deb.jpg)

* **juancajamarca** (2)

	
	La parte más importante de Jenkins, los Jobs (los trabajos que ejecuta).  
	Jenkins puede hacer varios trabajos al tiempo, esto es controlado por el Build Executor.  
	Por cada job, Jenkins crea un folder dentro de su workspace (/var/lib/jenkins/workspace/).  
	Un build es una ejecución de un Job. Cada job tiene su Build History.

* **Pablo Sozko** (2)

	
	Levanta la mano si notaste el lorem ipsum en el socalo del nombre del Prof.

* **edwinvalero** (2)

	
	El truco es muy útil

* **jasonsteven** (1)

	
	Para los que usamos windows esto dara error , debemos elegir en vez de shell la linea de comandos de windows (cmd)

* **robertoangelvaldez** (1)

	
	Excelente explicación

* **dbzdavidbaez** (1)

	
	Funcionado el primer JOB de Jenkins

* **carlosextra1** (1)

	
	Cada vez que ocurre una ejecución de jenkins es que se ejecuta un job y se guarda historial para auditorías!

* **HeartHunter** (1)

	
	Termine de instalar los plugins por medio de la instalacion manual usando la ultima version de jenkins hasta la fecha

* **Mateo Loaiza Rios** (1)

	
	hello #1 main build action completed: FAILURE
	
	Me sale este error al momento de ejecutar el job, que debo de hacer?

* **Luis Gerardo Rodriguez Arteaga** (1)

	
	no me aparece el plugin disponible

* **David Quintanar Pérez** (1)
¿Cuál es la definición de un Job de Jenkins?

* **Mateo Loaiza Rios** (1)
hello #1 main build action completed: FAILURE Me sale este error al momento de ejecutar el job, que debo de hacer?

## 0060. Configuración de un Job

### Descripción:


### Comentarios:

* **Pedro Jesus Hincapie Garcia** (14)

	
	Buenas, compañeros para los que hacen el seguimiento del curso en Windows, tener presente  
	**Que la ejecución o invocación de un parámetro es : echo%NOMBRE_VARIABLE%**
	``` 
	    echo "%NAME% esta es la version de Java"
	    java -version
	    echo "%NAME% esta es la version de Node"
	    node-v
	    
	```

* **Edwin De Jesus Chiyopa Garcia** (9)

	
	perfecto, eh usado docker para instalar jenkins jalo de maravilla no hay problemas, si alguien le interesa hacerlo solo hay que instalar docker y ejecutar:  
	docker pull jenkins/jenkins:lts  
	docker run -d -v jenkins_home:/var/jenkins_home -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts  
	listo  
	nota: estoy usando windows  
	<https://platzi.com/tutoriales/1432-docker/1779-como-instalar-docker-en-windows-y-mac/>  
	espero les sirva la información

	* **juancajamarca** (1)

		
		¡Excelente aporte!

	* **Viviana Paola Romero Rojas** (1)

		
		tienes para la linux?

* **Agustin David Luzenti** (8)

	
	General
	``` 
	    Discard old build  
	    
	```
	
	Como las cosas de los jobs se quedan en el disco duro en algun momento se va a llenar, ésta opcion es una manera de impedir que eso pase. Si se marca tiene varios opciones:
	
	Dias: se puede decir que quiero tener este build por ‘X’ dias, por ejemplo 365 dias (un año).
	
	Numero de builds a guardar: Tambien puedo decir 'quiero guardar los ultimos 2 bulilds"
	``` 
	    This project is parameterized 
	    
	```
	
	Se le puede pasar parametros al build. Por ejemplo un string parameter
	``` 
	    Disable this project 
	    
	```
	
	Si algo sale mal en un job y no quieres que nadie lo corra, se marca la cajita y el job no va a correr.
	
	Source Code Management
	
	Se puede elegir entre diferentes versionadores de codigo como subervsion o git
	
	Build Triggers
	
	Remotely
	
	A travez de una API
	
	After other projects are built
	
	Si termino de ejecutar job A quiero ejecutar job B unicamente si job A fue estable
	
	Periodicamente
	
	Recibe la sintaxis de un cron, se puede ejecutar cronologicamente
	
	Github hook trigger for GITScm polling
	
	Cuando se haga un pus en githu el job se va a ejecutar
	
	Bulid Environment
	
	Delete workspace before build starts
	
	Si tu corres el job y modificas el workspace, por ejemplo creas un archivo, la proxima vez que se ejecute, a a estar ahí, a menos que especifiques ésta opcion para eliminar el workspace
	
	Use secret text(s) or file(s)
	
	Añadir secretos, algo que no deberia estar expuesto a otros usuarios, esto te permite guardarlo y accesarlo a travez del script pero no va a estar expuesto a los ojos de otras personas, solo jenkins lo va a ver.
	
	Abort the build if it’s stuck
	
	Puede llegar el caso en el que el job nunca termino, por cualquier motivo que sea, es ideal que no se quede atorado, que falle. Entonces podemos deir que si no ha terminado en 3 minutos que se cancele el build y falle.
	
	Add timestamp to the console output

	* **josemdiaza** (1)

		
		 **Gracias!**

	* **Geovanny Javier Páez García** (1)

		
		muchas gracias

* **luis-a-carrillo** (6)

	
	Sintaxis para construir periodicamente
	
	El formato de configuración de cron es muy sencillo.
	``` 
	    El símbolo almohadilla «#» es un comentario, todo lo que se encuentre después de ese carácter no será ejecutado por cron.
	    
	    El momento de ejecución se especifica de acuerdo con la siguiente tabla:
	    
	    Minutos: (0-59)
	    Horas: (0-23)
	    Días: (1-31)
	    Mes: (1-12)
	    Día de la semana: (0-6), siendo 1=lunes, 2=martes,... 6=sábado y 0=domingo (a veces también 7=domingo)
	    
	```
	
	##########################################################  
	#minuto (0-59), #  
	#| hora (0-23), #  
	#| | día del mes (1-31), #  
	#| | | mes (1-12), #  
	#| | | | día de la semana (0-6 donde 0=Domingo) #  
	#| | | | | comandos #  
	##########################################################  
	15 02 * * *
	``` 
	    Para especificar todos los valores posibles de una variable se utiliza un asterisco (*).
	    
	    La última columna corresponde a la ruta absoluta del binario o script que se quiere ejecutar.
	```

* **dbzdavidbaez** (1)

	
	Funcionando
	``` 
	    echo"Hello DBZ from $NAME"
	    
	```

* **HeartHunter** (1)

	
	voy a instalar el servidor de aplicaciones nginx en mi maquina para poder hacer un despliegue mas real

* **programanime** (1)

	
	Excelente!!

* **Iván Mauricio Toro Cifuentes** (1)

	
	Esta clase estuvo mas descriptiva. 😄

* **James David Contreras García** (1)
Se indica que al ejecutar nuestro Job y modificamos el Web, hay elementos que se pueden quedar para una próxima ejecución, se refiere a l...

## 0070. ¿Cómo Jenkins interactúa con su máquina local

### Descripción:


### Comentarios:

* **Franco Isla Massa** (6)

	```
	    # Using Ubuntu
	    curl -sL https://deb.nodesource.com/setup_11.x | sudo -E bash -
	    sudo apt-get install -y nodejs```
	    
	```

	* **HeartHunter** (1)

		
		gracias

	* **Geovanny Javier Páez García** (1)

		
		GRacias

* **Germain Rafael Bueno Taguariparo** (4)

	
	muy mal que nombre el video que tendrán enlace como instalar en diferentes sistemas operativos y sea mentira

	* **Krystle Salazar** (2)

		
		Sí está mal que falte eso pero básicamente este sería el enlace que falta:  
		[Descarga Node.js](https://nodejs.org/es/download/)

	* **jouler** (1)

		
		se le olvida poner el enlace de los recursos :V

* **mrco** (4)

	
	Consulta necesito buildear un proyecto con .net y para eso necesito que el msbuild este instalado en mi servidor jenkins, que es linux, alguien sabe como puedo hacer esto?

	* **neo_jagp** (2)

		
		Me sumo a la pregunta. Alguien tiene idea?

* **increnta** (3)

	
	y como narices se accede por ssh a jenkins???

	* **Augusto Gonzalez** (1)

		
		Depende de tu sistema operativo. Pero asumiendo que tienes una instancia en AWS tienes que conectar por ssh. Revisar en Connection y ahi te aparece exactamente como hacerlo. Tienes que tener en cuenta que utilizas una llave extension .pem para conectarte con eso, si pierdes la llave te sera imposible conectarte.

	* **juancajamarca** (1)

		
		Puedes alojar Jenkins en un servidor de AWS, y te conectas vía SSH con la llave .pem que descargas de AWS.

* **Viviana May Jibi  Delgado Bethermy** (3)

	
	dejo el link para el node en linux  
	<https://github.com/nodesource/distributions/blob/master/README.md>

* **avalohack** (3)

	
	según el tema de la clase puedo tener php python etc y correrlo

* **Joel Alejandro Morales García** (3)

	
	Los primeros 40 segundos de este video parecen estar editados mal, la sincronización con el video

	* **Jose Adan Ardila Sanchez** (3)

		
		Esta clase parece que incluyera un detrás de cámaras, del minuto 3:50 en adelante pasa lo mismo.

	* **Melisa Lozano (Platzi)** (4)

		
		Ya estamos revisando el video, gracias!

	* **Kevin Javier Morales (Platzi)** (1)

		
		Ya está corregido 😃

* **javiereduardomartinez** (2)

	
	El canal de video del profesor esta desfasado con respecto al audio y slides.

	* **Kevin Javier Morales (Platzi)** (1)

		
		Ya está corregido 😃

* **seto2017** (2)
Esta mal todo el video...

	* **Kevin Javier Morales (Platzi)** (1)

		
		Ya está corregido 😃

* **robertoangelvaldez** (1)

	
	Información que cura

* **dbzdavidbaez** (1)

	
	 **Jenkins**
	
	Una herramienta muy potente

* **Wesly Fernández** (1)

	
	Es mejor instalarlo desde los plugins de jenkins para poder manejar multiples versiones de node?

* **programanime** (1)

	
	Excelente!!

* **mrco** (1)
Consulta necesito buildear un proyecto con .net y para eso necesito que el msbuild este instalado en mi servidor jenkins, que es linux, a...

	* **neo_jagp** (2)

		
		Me sumo a la pregunta. Alguien tiene idea?

# Plugins

## 0080. Jenkins y su ecosistema de Plugins

### Descripción:


Una de las razones por la cual Jenkins es adorado es porque tiene **Plugins** para una mayoría de cosas.

Los **plugins** son unidades que extiende a Jenkins, después de instalarlo nuestra herramienta puede hacer algo nuevo, es recomendado instalarlos con la opción de ““Download now and Install after restart”” y así **Jenkins** se va a encargar de ejecutar todos los **Jobs** que estaban corriendo y cuando eso termine, lo va a instalar.

### Comentarios:

* **Pedro Perafán Carrasco** (3)

	
	Si a alguien le da un error
	``` 
	    Error : java.security.InvalidAlgorithmParameterException: the trustAnchors parameter must be non-empty
	    
	```
	
	la solución es
	``` 
	    sudo /var/lib/dpkg/info/ca-certificates-java.postinstconfigure
	    
	```

* **Rubén Maier Enzler** (2)

	
	Y por ejemplo ¿con java? Porque por jenkins funciona con java 8, pero por ahí yo tengo en el mismo server corriendo un api hecha con java 9 o 10, ¿como hago para lidiar con la necesidad de tener varias versiones para distintos sistemas automatizando eso y no teniendo que manualmente definir rutas a cada uno?

	* **Diego Alexander Forero Higuera (Platzi)** (5)

		
		Hola esto te puede servir <https://www.thegeekdiary.com/how-to-work-with-multiple-java-versions-under-linux/> si quieres dejar una versión por defecto y usar otra para una aplicación en especifico le dices en que ruta se encuentra el binario de Java de la versión que quieres o necesitas usar.

	* **william andres rodriguez borja** (3)

		
		yo te recomendaria utilizar docker para jenkins y eso solucionaria tu inconveniente.

* **programanime** (2)

	
	Excelente!!

* **Iván Mauricio Toro Cifuentes** (2)

	
	[Jenkins Plugins](https://plugins.jenkins.io/)

* **teo** (1)

	
	  1. Qué diferencia existe cuando activa el check desde “ **Provide Node & npm bin/folder to PATH**” con la versión y cuando selecciona la opción “ **Execute NodeJS script** ”.  
	Aquí me gustaría resolver dos dudas:
	
	  2. Qué diferencia existe en especifico para NodeJS?
	
	  3. Qué diferencia existiría para cualquier otra herramienta?
	
	  4. De la pregunta 1, Por qué deja activa la primera opción y la otra no?
	
	
	

* **dbzdavidbaez** (1)

	
	Entendido y puesto en practica.

* **Geovanny Javier Páez García** (1)

	
	muy interesante

* **juancajamarca** (1)

	
	¡Y así hay muchísimos más plugins!

* **HeartHunter** (1)

	
	A esta seccion queria llegar

## 0090. Cadenas de Jobs

### Descripción:


### Comentarios:

* **DMT Technology** (5)

	
	Ya logre instalar el plugin, pero no me aparecen esos dos Jobs.  
	Ayuda por favor.

	* **jsuperh** (6)

		
		Se tienen que crear, por separado, seguro el ya los tenia creados.

	* **Roger Vilà** (1)

		
		reinicia el servicio de Jenkins i vuelve a iniciar el programa.

	* **Jhon Zambrano** (1)

		
		@jsuperh  
		donde los crea el profesor? según la explicación se crean automáticamente

* **Jose Maldonado** (4)

	
	Perdonen, pero no entendo nada de nada, instale, ejecute la herramienta, configuracion y realiza todo… pero siento que solamente estoy siguiendo un paso a paso sin contextualizar, jenkins automatiza, pero que automatiza? despliegues de SO. Server, servicios dentro de server, si lo vemos del lado de Infra; codigo desde el lado de dev, pruebas desde le lado de qa, ?, alguna ejemplo, que me puedan recomendar de un uso cotidiano; prefiero preguntar que segir haciendo por hacer y ver correr algo por correr.

	* **Pablo Pelaez** (6)

		
		Basicamente, con Jenkins se puede automatizar todo lo que mencionaste…Lo que tenemos es una herramienta que, en lo mas básico, ejecuta una serie de comandos en una maquina y obtiene un resultado, reemplazando ciertas tareas que normalmente hacía una persona. Es, por ejemplo:
		
		  * Hacer build de un proyecto en Java que está en Git…si lo haces manualmente deberías hacer pull del repo, y correr mvn compile o gradle build. Con Jenkins te puedes evitar hacer eso, haciendo un Git hook que emita un evento de commit, en Jenkins le haces pull, build y te dice todo OK o falló. Inclusive, y como funcionalidad extendida, puedes añadir code linters, validaciones de Sonar, etc.
		
		  * Hacer respaldo de una DB en un periodo en especifico. Si se hiciera manualmente deberías tener a alguien corriendo los comandos del motor de DB en un momento especifico. Con Jenkins solo es configurar dichos comandos y dejar configurado el cron. No hay que obviar que esto tambien se podría hacer con un crontab, pero pues a eso voy, Jenkins provee dicha funcionalidad, un poco mas transparente.
		
		
		
		
		Espero que esto te haya ayudado un poco.

* **Augusto Gonzalez** (3)

	
	Este video es super vital para todo el curso.

* **Iván Mauricio Toro Cifuentes** (3)

	
	Genial este ejemplo.

* **DMT Technology** (3)
Ya logre instalar el plugin, pero no me aparecen esos dos Jobs. Ayuda por favor.

	* **jsuperh** (6)

		
		Se tienen que crear, por separado, seguro el ya los tenia creados.

* **HeartHunter** (2)

	
	Seguir aprendiendo  
	no parar de aprender eso es la felicidad para mi

* **Adan Virrey** (2)

	
	He aprendido mas con este curso que con todos los videos de youtube que existen hasta hoy de Jenkins, el profesor explica super bien !

	* **Kevin Javier Morales (Platzi)** (1)

		
		Que bueno saber que el curso te ha ayudado 😄

	* **Andi Antopher** (1)

		
		haha

* **James David Contreras García** (2)
Estoy ejecutando Jenkins de manera local bajo un entorno windows, logro instalar el plugin pero no aparecen los dos jobs que se indican. ...

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Los Jobs los creo en las clases anteriores, esos no se instalan por defecto en Jenkins.

* **Luis Christian Vargas Vasquez** (1)
Interesante

* **dbzdavidbaez** (1)

	
	Muy interesante su aplicación. Podría ser más detallado el tutorial para que no se preste a confusiones.

* **robertoangelvaldez** (1)

	
	Muy buen ejemplo

* **Geovanny Javier Páez García** (1)

	
	un ejemplo muy interesante y muy util

* **juancajamarca** (1)

	
	Cadenas de builds.

* **Jair Sebastian Lozano Moron** (1)

	
	ya cree los dos proyectos de watchers y parameterized pero solo me aparece whatchers y no el parameterized, alguna ayuda?

	* **josemdiaza** (1)

		
		Explica tu problema para ayudarte.

	* **Jair Sebastian Lozano Moron** (1)

		
		el problema es que el proyecto parameterized está vacio, y no hay informacion de que contiene tal proyecto

	* **josemdiaza** (1)

		
		Lo que debes hacer es crear el job tal cual lo hace el profesor en el video.

* **jazhiel-j-balvin** (1)
Super

* **Cristhian Camilo Hernandez Perez** (0)

	
	Buenas noches realice la instalacion pero necesito reiniciar y ver los cambios, porque le di enesta opcion pero espero pero no se reinicia ni nada

	* **Cristhian Camilo Hernandez Perez** (0)

		
		Por fin lo logre, toca instalar el jenkins como servicio de windows y después de esto si se deja reiniciar

## 0100. Connectándonos a GitHub

### Descripción:


### Comentarios:

* **josemdiaza** (11)

	
	Mi aporte:
	``` 
	    Es posible conectar un repositorio de GitHub a Jenkins para que cada vez que exista un push se haga un build del source code. Para que esto sea posible debemos realizar cambios tanto en Jenkins como en GitHub.
	    
	    En Jenkins:
	    
	    1- Debemos tener el GitHub plugin instalado
	    2- Al crear el Job, debemos marcar el SCM la opciónde Git, y pegar la URL del repo. (Para esta acción el host de Jenkins debe tener instalado Git)
	    3- En el apartado "branches to build" si dejamos en blanco tomara en cuenta cualquier branch. 
	    4- En"Build Triggers" debemos marcar la opción"GitHub hook trigger for GITScm polling"
	    
	    En GitHub:
	    
	    1- Vamos al repo de GitHub.
	    2- Entramos en Settings -> Webhooks.
	    3- Añadimos un nuevo Webhook.
	    4- Añadimos la Payload URL. (Si la URL no acaba en /github-webhook/ GItHub lanzara un error.)
	    5- Marcar "Just the push event"
	    
	    
	```

	* **Augusto Gonzalez** (3)

		
		Excelente aporte! Alguien que le regale un cerveza a este hombre.

	* **Geovanny Javier Páez García** (1)

		
		gracias por tu aporte

* **jesusmurf** (7)

	
	Que placer cuando todos nuestros jobs muestran un solecito 😊

	* **Eduardo Lujan** (1)

		
		Checa esta documentación <https://jenkins.io/doc/book/blueocean/dashboard/>

* **Iván Mauricio Toro Cifuentes** (6)

	
	[El repo del curso](https://github.com/elbuo8/platzi-scripts).

	* **Andrés Eduardo Gonzalez Lugo** (1)

		
		Muchas gracias por publicar el link…
		
		Saludos!

* **Eduardo Cárdenas** (2)

	
	Alguien sabe como conectar Github con jenkins de windows? En windows se accede usando localhost en lugar de la IP, por lo que no se exactamente que IP ingresar en Github.

	* **Eduardo Cárdenas** (2)

		
		Al final terminé usando un servidor de Digital Ocean.  
		Pero si alguno sabe como poder hacerlo en una maquina personal se agradecería.

	* **Aníbal Corral Serrano** (10)

		
		Hola! Lo que pasa es que GitHub no llega a tu IP (localhost).  
		Lo que puedes hacer es utilizar un programa como [ngrok](https://ngrok.com/download) y exponer tu IP.  
		Cuando ya tienes tu IP pública con ngrok tendrás una url como esta: **<http://0dc178e4.ngrok.io>** /github-webhook/ que es la que debes indicar en GitHub. Yo así lo resolví 😄  
		Saludos.

	* **Edgar Valdez Moises** (1)

		
		Excelente aporte.
		
		Gracias !!

	* **anthonycardenas** (2)

		
		Genial AnibalCorral… hubo un tiempo que me la pasaba gogleando de cómo poder hacer eso y lo hacabo de hacer con ngrok…tan simple

	* **Marcelo Andrés Fernández Poo** (1)

		
		yo había puesto la ip pública que me asiga mi proveedor, y me preguntaba, ¿por qué no funciona?, excelente herramienta.  
		Saludos.

* **miguelangelsoler** (1)

	
	Tengo un servidor con varios proyectos, pero el scope de jenkins esta en /home/var/lib, como puedo hacer para ejecutar una tarea de shell que afecte a los directorios que estan fuera del scope de jenkins, en /home/projects/

* **Cristhian Camilo Hernandez Perez** (1)

	
	Al intentar la conexion me sale el siguiente error  
	Failed to connect to repository : Error performing git command: C:\Program Files\Git\bin ls-remote -h <https://github.com/elbuo8/platzi-scripts> HEAD

* **Jesús Alberto Martínez Hernández** (1)

	
	<https://github.com/elbuo8/platzi-scripts>

* **Marcelo Andrés Fernández Poo** (1)

	
	ya se que no es parte del curso, pero…qué versión del vim está utilizando?

	* **daferso93** (0)

		
		Yo tuve la misma pregunta, creo que esta utilizando iTerm2 y Vim, encontre este link por si quieres utilizarlo.
		
		<https://medium.com/@jeantimex/how-to-configure-iterm2-and-vim-like-a-pro-on-macos-e303d25d5b5c>

* **juancajamarca** (1)

	
	Buen ejercicio.

* **HeartHunter** (1)

	
	Funciono

* **HeartHunter** (1)
Cuando yo importo las dependencias me aparece la carpeta node_module to no la pones en tu repositorio por que

# Pipelines

## 0110. ¿Qué es un 'Pipeline'

### Descripción:


Pipelines nos permiten configurar nuestros Jobs con código en lugar de hacerlo en la interfaz visual. En Jenkins los hay de dos maneras: Scripting y Declarative.

### Links:

* [
Pipeline
](https://jenkins.io/doc/book/pipeline/)

### Comentarios:

* **jesusmurf** (13)

	
	Hay un lorem ipsum encima del nombre del profesor 😄

	* **Pablo Sozko** (1)

		
		irónico no ?

	* **Geovanny Javier Páez García** (1)

		
		jajaja

* **diegocruz** (5)

	
	Jenkins ofrece un plugin para modelar mediante una interfaz algo mas bonita las pipelines, aunque por debajo va a generar el mismo código, a mi me ha parecido útil. [BlueOcean](https://jenkins.io/projects/blueocean/)

* **juancajamarca** (3)

	
	Automatizando la automatización.

* **Hanson Garzon** (2)

	
	Para reportes de pruebas e2e el plugin de cucumber es genial!

	* **Augusto Gonzalez** (1)

		
		Cual de todos los Cucumber? Hay como 7 Cucumbers distintos. 😮

	* **Hanson Garzon** (1)

		
		Hombre el que uso se llama Cucumber Report, es muy bueno para el reporte de las pruebas e2e automatizadas

* **Hanson Garzon** (2)

	
	para medir cobertura de código estatico podemos usar SonarQube y Jacoco

* **Hanson Garzon** (2)

	
	Se debe poner tal cual está en el jenkinsfile la version de node … node-11.0.0 lo tenía como 11.0.0 y me arrojaba errores…

	* **Augusto Gonzalez** (1)

		
		Muy buen aporte!

* **Erika Hernández** (2)

	
	Hola! tengo el siguiente error al ejecutar:
	``` 
	    Caused: BUG! exceptionin phase 'semantic analysis' in source unit'WorkflowScript' unexpected NullpointerException
	    
	```
	
	Alguien tiene idea de lo que puede estar pasando?

	* **Erika Hernández** (5)

		
		Me auto-respondo… cuando configuré mi nodejs dejé por error una configuración sobrante totalmente vacía (es decir, sin especificar versión de node, ni el nombre). Esto generaba un nullpointer exception al tratar de obtener las versiones configuradas 😦

* **Daniel Moreno** (2)

	
	En este caso usan un repositorio de Gihub público. ¿Cómo seria si uso uno privado de Bitbucket?

	* **Paul Alarcon** (2)

		
		En ese caso debes pasar los parámetros de las credenciales y si deseas el branch de la siguiente forma dentro del step:  
		git ([url:‘<https://github.com/autor/repo.git>’, branch: ‘master’,credentialsId: ‘github’ ])
		
		donde credentialsId : ‘github’ es el nombre que le diste a tus credenciales dentro de Jenkins

* **Iván Mauricio Toro Cifuentes** (2)

	
	[El repo del curso](https://github.com/elbuo8/platzi-scripts).

* **HeartHunter** (1)

	
	ejecuto que bien pero en la version que yo estoy usando lee asi la linea del node (nodejs ‘13.3.0’)

* **HeartHunter** (1)

	
	Todavía no termino de armar mi servidor

* **adrianrbp** (1)

	
	“Blue Ocean” muestra el pipeline parecido al de gitlab 😃

* **Rosmery Isabel Luna Tito** (1)

	
	Tengo algunos errores al ejecutar los tests con el plugin de NodeJS en Windows, no sé si en Jenkins exista incompatibilidades con este SO porque en Ubuntu me ejecuta de maravilla… Hay alguna configuración extra que deba hacer ??

	* **Rosmery Isabel Luna Tito** (1)
![Issue_Jenkins.png](https://static.platzi.com/media/user_upload/Issue_Jenkins-d9430c5f-c994-485e-9eee-d83459173097.jpg)

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Al parecer el error es por problemas de permisos ya que no puede ejecutar el renombrado del archivo.

* **Octavio Gomez Romo** (1)

	
	<https://github.com/elbuo8/platzi-scripts>

* **programanime** (1)

	
	No esta cargando la página del video 10

* **jesusmurf** (1)

	
	Un agente es una instancia de Jenkins.

* **Rosmery Isabel Luna Tito** (1)
Tengo algunos errores al ejecutar los tests con el plugin de NodeJS en Windows, no sé si en Jenkins exista incompatibilidades con este SO...

	* **Rosmery Isabel Luna Tito** (1)
![Issue_Jenkins.png](https://static.platzi.com/media/user_upload/Issue_Jenkins-d9430c5f-c994-485e-9eee-d83459173097.jpg)

## 0120. ¿Cómo puedo acelerar mi development de Pipelines

### Descripción:


### Comentarios:

* **Victorino1675** (5)

	
	Es un curso básico de Jenkins, pero a mi parecer es muy completo, el profe es muy conciso en sus explicaciones, genial!!

	* **Kevin Javier Morales (Platzi)** (1)

		
		Que bueno que el curso te haya gustado 😄

* **lcmartinez_ (Platzi)** (3)

	
	 **Replay:**  
	No ha necesidad de hacer un commit para volver a ejecutar algun build en un punto especifico, y ademas se puede cambiar los steps.
	
	Ideal para probar.

* **Hanson Garzon** (3)

	
	Genial el aporte de Replay no veía una función clara (salvo editar mi Jenkinsfile), ahora me ahorrará mucho tiempo porque no debemos ir a Git tantas veces!

* **jsuperh** (2)

	
	En que momento se creo el job Parameterized?

	* **David Gallego** (1)

		
		en el video 8 o 9 creo

	* **Luzdelia Alba** (1)

		
		En el video de **Cadenas de Jobs.** No mostró cuando lo creó, pero si que fue lo que le configuró, lo que ayuda a que puedas crearlo 😃

* **robertoangelvaldez** (1)

	
	Replay, una maravilla al momento de aprender a configurar los pipelines

* **Geovanny Javier Páez García** (1)

	
	muy buen aporte

* **juancajamarca** (1)

	
	¡Buen aporte la funcionalidad del Replay!

* **HeartHunter** (1)

	
	Excelente lo del replay

* **Fernando Eladio Alvarez Noya** (1)

	
	Me encanto el pique del ripley! 😃

* **Iván Mauricio Toro Cifuentes** (1)

	
	localhost:8080/pipeline-syntax

* **ksanchez_cld** (1)
Debido a que Jenkins se convierte en un target importante para hackers. 1\. Como se podría configurar el security model de Jenkins? 2\. S...

# Slave

## 0130. Introducción a Slaves

### Descripción:


Los Slaves nos permiten correr Jobs distribuidamente. Se conecta al Jenkins master y este le delega trabajos al Slave como si fuese otra máquina puede ser virtual, física como quieras hacerlo, nos permite escalar horizontalmente.

### Comentarios:

* **Iván Mauricio Toro Cifuentes** (13)

	
	[Distributed builds - Jenkins](https://wiki.jenkins.io/display/JENKINS/Distributed+builds)

	* **Juan Pablo Calle García** (1)

		
		Gran aporte!

	* **Carlos Villa** (1)

		
		Thanks!

	* **josemdiaza** (1)

		
		 **Merci beaucoup**

	* **HeartHunter** (1)

		
		Excelente

	* **juancajamarca** (1)

		
		Buen aporte.

	* **Geovanny Javier Páez García** (1)

		
		gracias

## 0140. Conectado un Slave

### Descripción:


### Links:

* [platzi-scripts/prepare-jenkins-slave at master · elbuo8/platzi-scripts · GitHub](https://github.com/elbuo8/platzi-scripts/tree/master/prepare-jenkins-slave)

### Comentarios:

* **Adan Virrey** (5)

	```
	    cat .ssh/id_rsa.pub
	    copy key
	    adduser jenkins
	    apt-getupdate
	    apt-get install openjdk-8-jdk wget gnupg git vim
	    mkdir /var/jenkins/
	    chown jenkins:jenkins /var/jenkins
	    sudo su jenkins
	    cd 
	    mkdir .ssh
	    vim .ssh/authorized_keys
	    paste key
	    
	```

	* **Geovanny Javier Páez García** (1)

		
		gracias

* **Augusto Gonzalez** (4)

	
	Tuve un problema con la carpeta `.ssh` tanto en el usuario root como en el usuario jenkins.  
	En mi caso particular fue porque lo hice en una instancia de AWS que ya tiene la carpeta `.ssh` por ende no tenia permisos.  
	Asi que tuve que darle permisos necesarios con los siguientes comandos:
	``` 
	    sudo chown -R jenkins:jenkins .ssh
	    chmod 700.ssh
	    
	```
	
	Y ya con eso pude agregar mi nueva llave ssh.

	* **juancajamarca** (1)

		
		Dato a tener en cuenta.

* **Germain Rafael Bueno Taguariparo** (3)

	
	los scripts no están dsiponibles como dice el video

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Gracias vamos a revisar y publicar los enlaces y archivos lo más pronto posible.

	* **hfgranada** (1)

		
		los scripts a un no estan disponibles

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Ya se reporto nuevamente y vamos a trabajar para publicarlos cuanto antes.

	* **Yesica Lizeth Cortés Pineda (Platzi)** (2)

		
		Hola!! todos los scripts del curso estan disponibles en el repositorio del curso que encuentras aquí --> <https://github.com/elbuo8/platzi-scripts>.
		
		También dejé en la sección de enlaces el correspondiente a esta clase 😄

* **HeartHunter** (2)

	
	Tengo un servidor en una laptop vieja y voy a conectarla a una imagen de jenkins que tengo en docker desktop

* **Cristobal Vega** (2)
Si creamos otra máquina en DigitalOcean o AWS para el slave, en un caso práctico, ¿está máquina solamente servirá para hacerla de slave?,...

* **Augusto Gonzalez** (1)

	
	A mi me aparecio un error que dice:
	``` 
	    adduser: The user`jenkins' already exists.
	    
	```

	* **Augusto Gonzalez** (2)

		
		Este error me aparecio porque instale jenkins sin haber visto el video. Por si les pasa, lo que tienen que hacer es crear una instancia nueva.

* **Sebastián Córdoba Omen** (1)

	
	Repositorio del Curso:
	
	<https://github.com/elbuo8/platzi-scripts>.

* **darkainsoul** (1)
Saludos

* **Germain Rafael Bueno Taguariparo** (1)
los scripts no están dsiponibles como dice el video

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Gracias vamos a revisar y publicar los enlaces y archivos lo más pronto posible.

# Cierre

## 0150. Cierre del curso, introducción a DevOps

### Descripción:


### Comentarios:

* **Felipe Acosta** (10)

	
	Excelente curso, queria saber si va a haber uno profesional ?

	* **Iván Mauricio Toro Cifuentes** (5)

		
		Seria genial tener uno profesional.

	* **Juan Pablo Donadio** (1)

		
		La continuacion de este curso es el curso de Devops 😉

* **saarias** (9)

	
	Muy bueno el curso.
	
	Un dato importante es que para migrar jobs de un jenkins a otro (de una maquina a otra ) solo es cuestión de copiar los directorios del sistema operativo donde se encuentran ubicados los jobs , pegarlos en la nueva instancia de jenkins y listo!.

	* **hansfpc** (2)

		
		Buen dato!

* **Iván Mauricio Toro Cifuentes** (4)

	
	[Curso de DevOps](https://platzi.com/clases/devops/).

* **jouler** (3)

	
	me parece un excelente curso, lastima que se hizo el linux, me gustaría que se asociará la documentación o al menos explicará como hacerlo en windows, después de todo es lo más usad.

* **Claudio Jesus Vázquez Villanueva** (2)

	
	Estas bien pro Yamil, todo super entendible.

* **José Tuzinkievicz** (2)

	
	Excelente curso, me abrió mucho la cabeza.

* **juancajamarca** (2)

	
	Excelente curso. Gracias.

* **Adan Virrey** (2)

	
	 **Excelente Curso** Sobre todo por que resolví una situación que tenia en mi trabajo. Muchas gracias!

* **Sebastián Córdoba Omen** (2)

	
	Excelente curso para iniciar

* **Sebastián Córdoba Omen** (2)

	
	Excelente curso para iniciar!, me gustaría ver uno mas avanzado

* **Luis Christian Vargas Vasquez** (1)

	
	Excelente curso sobre Jenkins

* **robertoangelvaldez** (1)

	
	Excelente aborde de los terminos básicos de Jenkins

* **Geovanny Javier Páez García** (1)

	
	Muy buen curso

* **pf** (1)

	
	Muy bien explicado! Gracias Yamil

* **Augusto Gonzalez** (1)

	
	Un crack Yamil.

* **Germain Rafael Bueno Taguariparo** (1)

	
	Excelente curso!!!  
	Espero que la ruta siga esta linea y al final se logrea prender todo el proceso.

* **programanime** (1)

	
	Excelente curso!!

