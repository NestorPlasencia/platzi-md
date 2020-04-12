# Introducción a Google Kubernetes Engine

## 0010. Introducción a Google Kubernetes Engine

### Descripción:


Para entender qué es y cómo funcionan Kubernetes y Kubernetes Engine, vamos a aprender qué es un contenedor:

  * **Bare Metal** : Son los servidores físicos. Ademas de administrar nuestra aplicación, debemos hacernos cargo de la infraestructura _(todo lo relacionado con Hardware: redes, memoria, CPU, etc)_ y el sistema operativo _(actualizaciones, parches de seguridad, etc)_.
  * **Virtual Machine** : La infraestructura esta controlada por una capa virtualizada, no nos preocupamos más por la parte física de nuestros servidores.
  * **Containers** : Los contenedores son el funcionamiento más optimo de nuestras aplicaciones. Nos preocupamos únicamente por administrar nuestra aplicación y sus dependencias _(lenguajes de programación, frameworks, logs, etc)_ , mientras que de la infraestructura y el sistema operativo se van a encargar nuestros proveedores de nube.



Durante este curso nos acompaña Carlos Prieto: Google Developer Expert y Arquitecto Cloud en Xertica.

### Comentarios:

* **nachoogoomez** (4)

	
	Let’s go!!

* **julian aguirre Aguirre Romo** (2)

	
	también creo q deberían explicar mejor lo de ingress y cómo serìa con nginx o con traeffik https etc, es bueno el curso pero muy bàsico 😦

* **Julián** (1)

	
	Creo q deberìan hacer un proyecto final donde se integre todo lo aprendido en un proyecto con bases de datos, desarrollo, test, y deploy,y sobre todo con CD porq no lo enseñan en el curso

* **Brayan Mamani** (1)

	
	¡Genial! Este curso tiende a ser muy completo.

* **Ernesto Jose Gabriel Lopez Bravo** (1)

	
	Si quieren probar un poco de hands-on sobre kubernetes directamente: <https://www.katacoda.com/courses/kubernetes>

* **aimeenav** (1)

	
	vamos, pienso que es lo que se debe de aprender después de estudiar docker, docker compose, machine, boot2docker, etc.

* **Octavio Gomez Romo** (1)

	
	Temas previos que tenemos que estudiar ?

	* **ocar** (1)
Huu no responde

	* **Brayan Mamani** (1)

		
		¡Todo esta en la sección de la carrera!

## 0020. ¿Qué es Kubernetes

### Descripción:


 **Kubernetes Engine** es la solución administrada de Google en la plataforma de Google Cloud Platform. Su función es administrar el _cluster_ de máquinas, la instalación de los clientes y todos los procesos para el despliegue de nuestras aplicaciones. Google se encarga de todo.

Esta herramienta tiene las siguientes funcionalidades:

  * **Formato Docker** : Nuestras máquinas y contenedores deben usar este formato para poder ser desplegadas.
  * **Auto-escalado** : La performance de nuestra aplicación no se verá afectada cuando entren muchísimos usuarios al mismo tiempo. Podrás soportar toda esta carga sin necesidad de generar tus máquinas virtuales a mano.
  * **Stackdriver** : La solución de monitoreo y control de Google. Nos ayuda a entender muy fácilmente qué está pasando en la infraestructura: logs, alertas, monitoreo de la CPU y la memoria, etc.
  * **Cloud VPN** : Nos permite tener una nube híbrida con la cual tendremos nuestros datos y aplicaciones segregados en la nube y utilizando información de nuestros servidores locales. Todos estos procesos de forma segura.
  * **Cloud IAM** : Administración de usuarios gracias al soporte de autenticación de Google. Podemos asignar permisos y roles de lectura, escritura y administración sobre nuestro cluster.



Ventajas de Kubernetes Engine:

  * Actualizaciones automáticas
  * Reparación automática
  * Registro privado de contenedores
  * Versiones uniformes y rápidas
  * Soporte para GPU



Alternativas:

  * Redhat Openshift
  * Docker Swarm
  * Amazon Elastic Container Service for Kubernetes
  * IBM Cloud Kubernetes Service
  * Azure Kubernetes Service (AKS)



### Comentarios:

* **Omar Alvarez** (10)

	
	[Comic de Kubernetes](https://cloud.google.com/kubernetes-engine/kubernetes-comic/)

* **Juan David Castro (Platzi)** (3)

	
	👽 El proyecto interno de Google que creo Kubernetes se llama **Borg**.

* **Martín Leyva** (2)

	
	La Directora de Orquesta que aparece en la Lamina de la Presentación:
	
	¿Que es Kubernetes? … es
	
	**Alondra de la Parra** \- directora de orquesta mexicana. Es fundadora y directora artística de la Orquesta Filarmónica de las Américas con sede en Nueva York y Embajadora Cultural del Turismo de México.
	
	![](https://ibb.co/mmbdKq)

	* **Martín Leyva** (1)

		
		<https://ibb.co/mmbdKq>

* **quetzallymezaleon** (1)

	
	<https://cloud.google.com/kubernetes-engine/kubernetes-comic/>

* **Diego Carvajal** (1)

	
	Autoescalabilidad para que muchos usuarios no sobrecarguen nuestras apps

# Repaso de Docker

## 0030. Qué son los contenedores

### Descripción:


### Comentarios:

* **Martín Leyva** (3)

	
	El nombre de **contenedores** viene de los recipientes de carga estandarizados que se utilizan en barcos, camiones y trenes, que permiten cargar, descargar y apilar los **_containers_** durante largas distancias facilitando el transbordo de un medio de transporte a otro.
	
	Estos contenedores han supuesto una verdadera revolución en el mundo del transporte, reduciendo costes, tiempos de carga/descarga, daños en mercancías, etc.
	
	**Docker** lleva este mismo concepto al mundo del software, **_permitiendo encapsular cualquier arquitectura, convirtiéndola en un contenedor portable y autosuficiente,_** de forma que se pueda manipular mediante operaciones establecidas y ejecutar de manera consistente en cualquier hardware.
	
	Fuente: <https://www.paradigmadigital.com/dev/primeros-pasos-con-docker/>

* **Martín Leyva** (2)

	
	Los **contenedores** tienen una función similar a las máquinas virtuales, pero son menos complejos y más fáciles de desplegar.
	
	**_Desplegar_** es lo que en Inglés es **_" Deployment"_**

* **Diego Carvajal** (1)

	
	Los contenedores permiten desplegar nuestras aplicaciones en cualquier sistema operativo.

	* **Everardo Sánchez** (2)

		
		y en cualquier nube 😃

	* **Brayan Mamani** (1)

		
		¡Eso es de mucha utilidad!

## 0040. Qué es Docker

### Descripción:


Docker es una tecnología open source, desarrollada en el lenguaje de programación GO, utilizando la licencia Apache 2.0 _(podemos desplegar nuestra aplicación en cualquier servidor, sin que nuestro código fuente sea open source)_.

Docker utiliza las características de los sistemas operativos tipo UNIX para administrar los contenedores y el despliegue de nuestras aplicaciones en el area de memoria del sistema operativo Linux.

### Comentarios:

* **Martín Leyva** (3)

	
	Ventajas de los Contenedores:
	
	**Ventajas**
	
	Completamente portables, te permiten ejecutar tu aplicación en local sobre cualquier sistema operativo, en cualquier servidor on-premise o incluso en la nube. Esto hace que Docker sea un complemento perfecto para los equipos ágiles y acaba con el “esto en mi ordenador funcionaba”.
	
	Te permite tratar la infraestructura como un fichero más dentro de las fuentes de tu proyecto, con lo que puedes automatizar dentro del build la creación de la propia infraestructura, creando una imagen completa con el software base y tu aplicación instalada.
	
	Hay miles de imágenes ya disponibles en DockerHub con casi cualquier stack tecnológico, las puedes usar directamente o modificarlas para evitar partir de cero.
	
	La gestión de paquetes y dependencias es muy simple y transparente, facilitando la integración de los equipos de desarrollo y sistemas.
	
	Tiene mejor rendimiento que la virtualización tradicional, ya que está basado en LXC, que corre directamente sobre el kernel de la máquina donde se aloja, evitando la capa de virtualización tradicional basada en un hipervisor que penaliza el rendimiento.
	
	Por las mismas razones que el punto anterior, los contenedores arrancan en segundos, mucho más rápido que una máquina virtual.

	* **Martín Leyva** (2)

		
		Fuente:
		
		<https://www.paradigmadigital.com/dev/primeros-pasos-con-docker/>

* **AlexMaguey** (2)

	
	Una imagen es como una clase (abstracción)  
	Un contenedor es como un objeto (concreción)

* **Diego Carvajal** (1)

	
	Docker permite desplegar una app en cualquier infraestructura sin preocuparnos por el sistema operativo

## 0050. Comandos Básicos de Docker

### Descripción:


  * `docker pull`: Descargar y guardar las imágenes de nuestra aplicación
  * `docker images`: Listar las imágenes descargas en nuestra máquina
  * `docker ps`: Listar los contenedores corriendo en nuestra máquina _(id, puerto, etc)_
  * `docker ps -a`: Listar los contenedores apagados de nuestra máquina_
  * `docker exec`: Ingresar a nuestro contenedor y listar las carpetas dentro de el
  * `docker stop`: Detener la ejecución de nuestro contenedor
  * `docker rm`: Borrar nuestro contenedor



Si quieres aprender más sobre los comandos y usos de Docker, puedes entrar al [Curso de Fundamentos de Docker](https://platzi.com/cursos/docker/). Recuerda que si tienes alguna duda o comentario puedes dejarla en la sección de discusiones.

### Links:

* [GitHub - spring-petclinic/spring-framework-petclinic: A Spring Framework application based on JSP, Spring MVC, Spring Data JPA, Hibernate and JDBC](https://github.com/spring-petclinic/spring-framework-petclinic)

### Comentarios:

* **ricardocelis (Platzi)** (7)

	
	<https://github.com/spring-petclinic/spring-framework-petclinic>

* **ricardo-rod** (5)

	
	Aqui estan las nuevas instrucciones de docker y de jetty que sustituye a tomcat. ojo el puerto es 8080, no 9966.
	``` 
	    git clone https://github.com/spring-petclinic/spring-framework-petclinic.git
	    cd spring-framework-petclinic
	    
	    # ./mvnw tomcat7:run-var$runapp
	    ./mvnw jetty:run-war
	    
	    # web preview port 8080 or change to 9966
	    docker run -p 8080:8080 springcommunity/spring-framework-petclinic
	    
	```

* **harryharango** (3)

	
	Por si les falla ejecutando el comando ./mvnw jetty:run-war por los Testing , para omitirlos, ejecutar el comando mencionado anteriormente con el siguiente parámetro
	``` 
	    ./mvnw jetty:run-war -DskipTests
	    
	```

	* **Junior Usca H.** (4)

		
		y abrir en el puerto 8080

* **RoyalLegalSolutions** (2)

	
	Hola! No se como solucionar este error  
	`No plugin found for prefix 'tomcat7' in the current project and in the plugin groups`

	* **Jair Sebastian Lozano Moron** (1)

		
		tengo el mismo problema y no se como solucionarlo, ya intenté de varias maneras

* **Diego Carvajal** (2)

	
	Cuando nos registramos en google cloud nos 300 dolares para hacer todas las pruebas que necesitemos.

* **fernanperez** (2)

	
	cuando se ejecuta tomcat 8 no funciona

* **jk_** (2)

	
	no funciono con la información del video, en la pagina muestra la siguiente información y así funciono
	
	git clone <https://github.com/spring-petclinic/spring-framework-petclinic.git>  
	cd spring-framework-petclinic  
	./mvnw jetty:run-war

* **OSCAR ALFREDO CHAFLOQUE TAMPECK** (1)

	
	la aplicación esta configurada con docker?

* **Freddy Lemus Barrera** (1)

	
	Para poder cambiar el puerto y obtener la vista es necesario seleccionar en la configuración de la terminal (Parte izquierda, segundo icono) la configuración de tmux. ¿Conocen algún tutorial paso a paso para poder configurar y redimir lo que nos da google.?

	* **Carlos Prieto** (1)

		
		en este video se muestran los pasos para activar los créditos
		
		<https://www.youtube.com/watch?v=Uu3PgeqZ3kU>

	* **Jonnathan Ramiro Juma Jara** (1)

		
		solo da clic en el icono de regalo y te registras con os datos que te pide, mas tu tarjeta de crédito, hacen la validación de tu tarjeta con 1 dolar de debito y se activa los 300 dolares por un año

* **Freddy Lemus Barrera** (1)
Para poder cambiar el puerto y obtener la vista es necesario seleccionar en la configuración de la terminal (Parte izquierda, segundo ico...

	* **Carlos Prieto** (1)

		
		en este video se muestran los pasos para activar los créditos
		
		<https://www.youtube.com/watch?v=Uu3PgeqZ3kU>

* **Madrov** (0)

	
	Recomiendo primero aprender docker bien y familiarizarse antes de tomar este curso. De lo contrario pienso que es mucha informacion para procesar.

## 0060. Creación del contenedor de Docker

### Descripción:


### Comentarios:

* **josericardoperezperez** (3)

	
	Tengo una duda, ¿Como es que empujamos la imagen spring-framework-pet-clinic que creamos a partir del Dockerfile?, tengo enetendido que lo que hicimos fue hacer un TAG del ya existente **springcommunity/spring-framework-petclinic** y re subirlo al registro de contenedores de Google sin embargo el que creamos con el Dockerfile no lo tomamos en cuenta :S

* **ricardo-rod** (3)

	
	Para el que le interese aqui la imagen de docker lista para jetty y solo hay que correrla tiene los archivos necesarios, pero el petclinic no esta en el commit de git que esta publicado. Espero les sirva a muchos.
	
	PD: recuerda cambiar YOUR_PROJECT_ID por tu proyecto para que te pueda subir al container registry.
	``` 
	    docker pull springcommunity/spring-framework-petclinic
	    gcloud auth configure-docker
	    docker tag springcommunity/spring-framework-petclinic:latest gcr.io/YOUR_PROJECT_ID/spring-framework-petclinic:v1
	    docker push gcr.io/YOUR_PROJECT_ID/spring-framework-petclinic:v1
	    gcloud container images
	    
	```

* **miguelprada2** (2)

	
	Mi solución del Reto:  
	Lo hice usando la imagen de `nginx`.
	
	  1. Creé una nueva carpeta ‘hello-world-docker’
	  2. Creé un archivo `index.html` dentro de la carpeta, con el contenido `<h1>Hello World</h1>`
	  3. En el Dockerfile, el siguiente contenido:
	
	
	``` 
	    FROM nginx:alpine
	    COPYindex.html /usr/share/nginx/html
	    EXPOSE8080
	    
	```
	
	  1. Usar `$ docker build ./`
	  2. Listar las imágenes con `$ docker images`
	  3. Crear el tag `$ docker tag [IMG_ID] gcr.io/[PROJECT_ID]/TAG_NAME`
	  4. Hacer el push a las imagenes del proyecto en Google Cloud: `$docker push gcr.io/[PROJECT_ID]/TAG_NAME`
	
	
	
	Y listo. La imagen se puede ver en la consola.

* **Alvaro   Gonzalez** (2)

	
	Que es [gcr.io](http://gcr.io), en el comando de docker push [grc.io](http://grc.io) ?

	* **Joshua Nathanael Saucedo Uriarte** (3)

		
		Google Container Registry (GCR) => [gcr.io](http://gcr.io)
		
		es como su nombre lo dice, el nombre del host del registry de google, ahi se guardan tus imagenes en tu registry personal

	* **aparicio_juan** (1)

		
		si no entendi mal guardas tu contenedor en el repo de google, como lo haces en el repositorio de docker normalmente para cuando lo necesitas. Yo prefiero usar la store de docker para guardarlos ya que lo dejas hay gratis y aqui esta relacionado a tu cuenta por lo que se ve. Si me equivoco que alguien me corrija.

* **Kevin William Roberts Costa** (1)

	
	iba a ser más creativo, pero lo más facil es hacerlo con nginx
	``` 
	    cd ~
	    mkdir helloworld
	    nano index.html -> add "hello world"
	    nano Dockerfile -> FROM nginx, COPY html, EXPOSE 8080
	    docker build . -> copy $buildoutput
	    docker run -d -p 8080:80 $buildoutput
	    
	    docker tag $IMAGE_ID gcr.io/$PRJ_ID/nginx-k
	    docker push gcr.io/$PRJ_ID/nginx-k
	    
	    
	```

* **Jair Sebastian Lozano Moron** (1)

	
	de donde sacaste el target/petclinic.war ya que me dice que no encuentra el archivo /var/lib/docker/tmp/docker-builder599540831/target/petclinic.war

* **Nicolás José Vela Hidalgo** (1)

	
	Autenticarse en Google:  
	gcloud auth configure-docker

* **jscontreras** (1)

	
	Este dockerfile me sirvio  
	recuerden q deben ir a la direccion y le adicionan `/petclinic`  
	se demora un poco mientras empieza.  
	more info aca  
	[](https://hub.docker.com/_/jetty)
	``` 
	    FROM jetty:latest
	    COPY target/petclinic.war /var/lib/jetty/webapps
	    EXPOSE 8080
	    CMD java -jar "$JETTY_HOME/start.jar" --add-to-startd=jmx,stats
	    
	```

	* **jscontreras** (1)

		
		<https://hub.docker.com/_/jetty>

* **Victoria Tejeda** (1)

	
	Si a alguien le sirve yo estoy haciendo el ejemplo con Jetty:
	
	docker run -d -p 8080:8080 --name petcli jetty
	
	Dockerfile:  
	FROM jetty:latest  
	COPY target/petclinic.war /var/lib/jetty/webapps  
	EXPOSE 8080

* **Juan Francisco Mosquera** (1)

	
	Hola , como podria solucionar este error ?.  
	docker push [gc.io/spring-framework-petclinic](http://gc.io/spring-framework-petclinic)
	
	f3a38968d075: Waiting  
	a327787b3c73: Waiting  
	5bb0785f2eee: Waiting  
	error parsing HTTP 404 response body: invalid character ‘<’ looking for beginning of value: “<!doctype html>\n\n<head>\n <meta charset=“utf-8”>\n <meta http-equiv=“X-UA-Comp  
	atible” content=“IE=edge,chrome=1”>\n <title>We Can’t Find the Page — 404 | GameChanger</title>\n <meta name=“viewport” content=“width=device-width, initial-s  
	cale=1.0”>\n <link rel=“shortcut icon” href=”[//d2qxbjtnvyv052.cloudfront.net/media/5dc03b255d34ded2898745d08ffaed4d/images/favicon.ico](//d2qxbjtnvyv052.cloudfront.net/media/5dc03b255d34ded2898745d08ffaed4d/images/favicon.ico)"/>\n <link rel=“apple-touch-icon"  
	href=”[//d2qxbjtnvyv052.cloudfront.net/media/44958470ac0d1bb0c54cf71a2803f877/images/icons/dumbo_108x108.png](//d2qxbjtnvyv052.cloudfront.net/media/44958470ac0d1bb0c54cf71a2803f877/images/icons/dumbo_108x108.png)">\n <link rel=“stylesheet” href="[//d2qxbjtnvyv052.cloudfront.net/m](//d2qxbjtnvyv052.cloudfront.net/m)  
	edia/4c30dc07194718244ebb5c669746e3e9/build/css/compressed/main.css"/>\n <link rel=“stylesheet” href="[//d2qxbjtnvyv052.cloudfront.net/media/8d901edaa00a22755a4e41330be43937/bu](//d2qxbjtnvyv052.cloudfront.net/media/8d901edaa00a22755a4e41330be43937/bu)  
	ild/css/error.css">\n <link rel=“stylesheet” href="[//d2qxbjtnvyv052.cloudfront.net/media/852204999bd4373f4e98a2e17cfb6e9e/build/css/search.css](//d2qxbjtnvyv052.cloudfront.net/media/852204999bd4373f4e98a2e17cfb6e9e/build/css/search.css)">\n \n<script>\n(function(i,  
	s,o,g,r,a,m){i[‘GoogleAnalyticsObject’]=r;i[r]=i[r]||function(){\n(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),\nm=s.getElementsByTagName(o)[0];a.asy

	* **Juan Francisco Mosquera** (1)

		
		Por favor omitir , encontre la solucion.  
		gracias

* **jk_** (1)

	
	levante el siguiente ejemplo de un contenedor de docker en [console.cloud.google.com](http://console.cloud.google.com) pero me da error, pueden revisar que esta pasando, gracias
	
	<https://www.josedomingo.org/pledin/2016/02/ejemplos-de-ficheros-dockerfile-creando-imagenes-docker/>
	
	docker run -p 8888:8888 --name servidor_web jk/apache2:1.0  
	AH00558: apache2: Could not reliably determine the server’s fully qualified domain name, using 172.18.0.2. Set the ‘ServerName’ directive globally to suppress this message
	
	Solo cambie el puerto a 8888
	
	Error: Could not connect to Cloud Shell on port 8888.  
	Ensure your server is listening on port 8888 and try again.

	* **Edgar Meneses** (1)

		
		Según entiendo el problema es que debes tener alguna aplicación o recurso que esta utilizando el puerto 8080

# Conceptos Basicos

## 0070. Cluster y nodos ¿Qué son y cómo funcionan

### Descripción:


Un cluster es una agrupación de máquinas que corren una cierta cantidad de servicios para que nuestra aplicación pueda funcionar sobre Kubernetes.

El endpoint o nodo maestro es una máquina dentro de nuestro cluster, es la puerta de entrada a todo el cluster. Tiene las APIs de Kubernetes, los servicios REST, el agendamiento de pods y la sincronización servicios. Tambien cuenta con integración a los servicios de Google Cloud Platform.

Un Nodo es un worker machine, osea, una maquina dentro de un cluster. Esta máquina tiene todas las herramientas para el despliegue de nuestras aplicaciones. Puede ser una maquina virtual o una máquina física con todos los servicios necesarios para correr pods.

Las direcciones, condiciones, capacidad e información de nuestros nodos se llaman estados y podemos acceder a ellos desde la terminal.

Un pod es un conjunto de contenedores que se despliegan en nuestros nodos. Más adelante aprenderemos más a detalle cómo funcionan.

### Comentarios:

* **Juan Francisco Mosquera** (1)

	
	cuales son los servicios rest ?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Son también conocidos como API, o API Rest, haces una petición y te retornan una respuesta por lo general en formato JSON para ser consumida, ejemplo puede ser <https://swapi.co/> que tiene un API al cual haces peticiones y te retorna información sobre las películas de startwars

	* **Juan Francisco Mosquera** (1)

		
		Hola gracias , yo comprendo esa definición , pero aplicado al contexto del video no explica que endpoints o services o mensajes se esta compartiendo ( Minuto 0.53).

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Son los endpoints para poder obtener información del cluster, te dejo el link de la documentación oficial donde están los endpoints y su función <https://cloud.google.com/kubernetes-engine/docs/reference/rest/>

* **Diego Carvajal** (1)

	
	++los nodos son maquinas dentro de un cluster ++

## 0080. ¿Qué son los Pods

### Descripción:


### Comentarios:

* **cesarredondoarrieta** (1)

	
	Lastima que para la practica no usamos minikube o algun equivalente, no voy a poner mi informacion de la tarjeta de credito en GCP para crear un cluster

	* **Juan Francisco Mosquera** (1)

		
		Uy si , algún summary con todos los conceptos , creo que es algo general que deberían mejorar en todos los cursos y lograra agregar un valor diferencial .

	* **felipe-rv** (1)

		
		Usa una tarjeta visa prepago… por ejemplo Match en Chile

	* **Brayan Mamani** (1)

		
		¡Tarjeta de crédito! VISA o MASTERCARD.

	* **Kevin William Roberts Costa** (1)

		
		es un curso de Google Kubernetes Engine

* **dariovinueza** (1)

	
	Buenas tardes, a que se refiere con compartir almacenamiento? comparten una base de datos? archivos de configuración? que es lo que comparten?
	
	Muchas Gracias!

	* **aparicio_juan** (1)

		
		Si no me equivoco que puede pasar, con almacenamiento se refiere al almacenamiento que usas de google en la misma nube como storage o datastore. ya que en teoria usas los contenedores para correr cosas y el almacenamiento lo hacen en otro lado. Claro que en la practica puedes tenes un contenedor de Postgres y almacenar alli sin problemas. Creo que es asi.

* **Alvaro   Gonzalez** (1)

	
	Implica como minimo es necesario 2 nodos, uno el master y otro de las funcionalidades …?

	* **Alejandro Ortegano** (1)

		
		es lo recomendado

	* **Alejandro Ortegano** (1)

		
		si son mas mejor pero también depende del tamaño de tu proyecto que vas a realizar

	* **nachoogoomez** (2)

		
		Claro, todo cluster implica > 1 máquina. De todas formas **creo** que el master lo abstrae google y tu solo tienes que contratar los workers.

	* **Brayan Mamani** (1)

		
		¡La mejor opción!

* **dariovinueza** (1)
Buenas tardes, a que se refiere con compartir almacenamiento? comparten una base de datos? archivos de configuración? que es lo que compa...

	* **aparicio_juan** (1)

		
		Si no me equivoco que puede pasar, con almacenamiento se refiere al almacenamiento que usas de google en la misma nube como storage o datastore. ya que en teoria usas los contenedores para correr cosas y el almacenamiento lo hacen en otro lado. Claro que en la practica puedes tenes un contenedor de Postgres y almacenar alli sin problemas. Creo que es asi.

## 0090. Deployments

### Descripción:


Los deployments son una abstracción de nuestra aplicación que nos permite crear una arquitectura e indicar la cantidad de pods que se van a necesitar. Con esto, haremos un despliegue de nuestra aplicación en nuestro cluster, tomando la cantidad de pods y replicas que indicamos previamente.

### Comentarios:

* **Johan Steven Arias** (2)

	
	saludos, tengo una duda, porque cada una de las replicas tiene una dirección ip, no se suponia que todos los pods compartirian la misma dirección ip ?..o cada direccion ip segun lo que esta en la imagen corresponde a cada nodo ?

	* **nachoogoomez** (1)

		
		Amigo… 2 meses y no tienes respuesta… ya lo siento. Y no, cada pod tiene una ip diferente dentro de la subred de pods

	* **Sebastian Borrajo** (2)

		
		En realidad, un pod tiene una IP, siendo que dentro hay contenedores, estos contenedores comparten esa IP

	* **Brayan Mamani** (1)

		
		¡Muy buena aclaración!

* **Mariano34** (2)

	
	Sería bueno un material escrito para poder leer y reforzar el concepto ya que fue algo rápida la explicación

* **vanesora** (1)

	
	Muy vago

* **huascarm** (1)

	
	Pregunta: Pueden existir mas de un Pod por nodo?, es correcto decir que la cantidad de réplicas define la cantidad de nodos?

	* **Kevin Stuardo Lorenzo Coshic** (1)

		
		Un Nodo si puede tener múltiples Pods. Fuente: <https://kubernetes.io/docs/tutorials/kubernetes-basics/explore/explore-intro/>.

## 0100. Pods y Deployments en practica

### Descripción:


### Comentarios:

* **Kevin William Roberts Costa** (1)

	
	Tuve que deshabilitar el autoescalado para poder usar solo 2 (cambiando desde el yaml). Es como que edito el yaml y lo guardo pero después vuelve sólo a 3

* **Carlos Jose Solar Zamorano** (1)

	
	por que a los nodos por defecto tienen el sufijo  
	default-pool?

* **Germain Rafael Bueno Taguariparo** (1)

	
	Santo cielos que maravilla…

* **JMM** (1)
No me que claro algo… Había 3 nodos en el cluster. Cuando se desplegaron 2 replicas (entiendo que son 2 pods) ¿Se desplegaron en 2 nodos,...

## 0110. Servicios

### Descripción:


Los servicios nos permiten ingresar tráfico y conectar los diferentes servicios de nuestra aplicación. Los 3 tipos de servicios disponibles son: **Cluster IP** , **Node Port** y **Load Balancer**.

### Comentarios:

* **nachoogoomez** (6)

	
	Me quedaron muchas muchas dudas… ya que esto es un curso específico de Google Cloud en su rama Kubernetes entiendo que lo más lógico sería explicar los distintos balanceadores de carga y no tomar por sentado la “normal general” de kubernetes de que cuando usas un servicio load balancer este pasara todo el trafico por el nodo maestro… En google cloud el nodo maestro esta abstraido por google y para nosotros simplemente no existe. Además, cuando usas un servicio de tipo loadbalancer lo que estas haciendo es usar un servicio de balanceo de carga de google, contratando este claro esta (muy parecido a la explicación del node port)
	
	La cosa esta en, sabiendo lo antes explicado, estaría genial que hubieran explicado los distintos tipos de balanceadores de carga que hay en google cloud y como configurar estos a través del archivo yaml (en la clase practica)

	* **REINALDO ORJUELA GODOY** (2)

		
		Si de acuerdo, si bien hay que investigar, debería tener un poco mas de fondo las explicaciones. Les recomiendo el de swarm para que vean la diferencia.

	* **Juan Francisco Mosquera** (2)

		
		uy 4.51 minutos de un millón de conceptos , deberían colocar slides para estas cosas.

* **Omar Alvarez** (6)

	
	[https://medium.com/google-cloud/kubernetes-nodeport-vs-loadbalancer-vs-ingress-when-should-i-use-what-922f010849e0](url) Este es un complemento de lo que se vio en la clase

	* **Carlos Jose Solar Zamorano** (2)

		
		Muy buen aporte!

	* **Brayan Mamani** (1)

		
		¡Muy bueno!

	* **Christian Acevedo** (1)

		
		Excelente, muchas gracias

* **Christian Acevedo** (1)

	
	Esta clase estuvo demasiado confusa, ya que segun el diagrama de arquitectura de Kubernetes el trafico jamas pasa por el nodo maestro, este nodo unicamente realiza las veces de orquestador y gestionador de las nodos workers y el estado deseado del cluster.

## 0120. Servicios en práctica

### Descripción:


### Comentarios:

* **Kevin William Roberts Costa** (1)

	
	No pude seguir.
	
	“kubectl exec -it petclinic-app-app-6cd9875dc5-drdpr bash  
	OCI runtime exec failed: exec failed: container_linux.go:345: starting container process caused “exec: “bash”: executable file not found in $PATH”: unknown  
	command terminated with exit code 126”

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Prueba reiniciar el pod o redesplegar el servicio en el cluster, ese error me pasa algunas veces en local y se soluciona borrando el contenedor de docker y volviendolo a crear.

	* **Kevin William Roberts Costa** (1)

		
		Hola Diego, borré todo el cluster y volví a crear. Me aparece lo mismo 😦

	* **Kevin William Roberts Costa** (1)

		
		Por lo que entendí es algo en lo que se basa la imágen que usé

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Trata de borrar las imágenes base y vuelve a crearlas.

	* **vanesora** (1)

		
		intenta con sh en vez de bash

* **nachoogoomez** (1)

	
	Pregunta!!
	
	Escenario: 1 deployment con 1 réplica de un servidor http y 1 deployment con 2 réplicas de un API privada. Si quiero crear un servicio para exponer las API privadas al contenedor http y que este servicio me balance las cargas entre las 2 replicas de API el ClusterIP me balancearía ? Si no es así como puedo balancear las cargas sin exponer el servicio a internet?

	* **nachoogoomez** (1)

		
		Entiendo que podría ponerlo como NodePort detrás de un balanceador de carga de GCP y poner reglas para que solo acepte peticiones de la red privada.
		
		Aun así sigue siendo interesante la duda. ¿Qué sucede si pongo un deployment con 2 replicas detrás de un Service ClusterIP? ¿Balancea la carga? 🤔

	* **Carlos Prieto** (1)

		
		Efectivamente sería con clusterIP, pero si se quiere un balanceo de carga más eficiente se puede hacer con un Loadbalancer y en el yaml se indica que no es exponga por lo tanto quedaría como privado. En el vinculo que ponga acontinuación se explica como hacerlo.
		
		<https://cloud.google.com/kubernetes-engine/docs/how-to/internal-load-balancing>

* **nachoogoomez** (1)
Pregunta!! Escenario: 1 deployment con 1 réplica de un servidor http y 1 deployment con 2 réplicas de un API privada. Si quiero crear un ...

	* **nachoogoomez** (1)

		
		Entiendo que podría ponerlo como NodePort detrás de un balanceador de carga de GCP y poner reglas para que solo acepte peticiones de la red privada.
		
		Aun así sigue siendo interesante la duda. ¿Qué sucede si pongo un deployment con 2 replicas detrás de un Service ClusterIP? ¿Balancea la carga? 🤔

## 0130. Servicios en práctica  Loadbalancer

### Descripción:


Recuerda que puedes tomar el [Curso Profesional de DevOps](https://platzi.com/clases/devops/) para aprender más sobre todos estos procesos y términos de despliegue de aplicaciones.

### Comentarios:

## 0140. Servicios en práctica  Node Port

### Descripción:


### Comentarios:

* **Julio Cesar Jaramillo Palacios** (3)

	
	Esta configuracion les funciono??

	* **asolorzano** (4)

		
		A mi no me funciono, me muestra el siguiente error  
		404\. That’s an error.
		
		The requested URL / was not found on this server. That’s all we know.

	* **Julio Cesar Jaramillo Palacios** (2)

		
		si bueno lo aceptare como un reto, ya que lo solucione comparto la solución aquí, gracias por responder.

	* **dariovinueza** (1)

		
		Si tengo el mismo problema!

	* **Walter Chacón** (1)

		
		Tuve el mismo problema, 404. El problema es que el Loadbalancer no tiene acceso al nodeport service y lo que no explican en el video es que hay que agregar un nuevo rule en el firewall para que cualquier address 0.0.0.0/0 tenga acceso al nodeport (<https://cloud.google.com/kubernetes-engine/docs/how-to/exposing-apps>), sigan los pasos en la sección “Create a firewall rule for your node port”

	* **Javier González de Lope** (1)

		
		A mí tampoco me funcionó la configuración que explican en el vídeo. Y tras añadir la excepción en el firewall, el error pasó a ser el siguiente:
		
		![error_lb.png](https://static.platzi.com/media/user_upload/error_lb-05e35dc4-9b24-4630-b9bf-f3db7b043a4c.jpg)

* **Jair Sebastian Lozano Moron** (2)

	
	Para el problema en el que les sale el error 404, ingresen el siguiente codigo:
	``` 
	    gcloud compute firewall-rules create test-node-port --allow tcp:[NODE_PORT]
	    
	```
	
	donde nodeport es el “puerto de nodo” que etaá dentro de su servicio creado de tipo nodeport.

	* **ricardo-rod** (2)

		
		Muchas gracias Mr. Sebastian. 1000 x 1000 su aporte!

	* **Brayan Mamani** (2)

		
		¡Excelente información!

* **Kevin William Roberts Costa** (1)

	
	Health incorrecto y este error en el puerto 80
	``` 
	    Error: ServerError
	    The server encountered a temporary errorand could not complete your request.
	    Please try again in30 seconds.
	    
	```

* **Kevin William Roberts Costa** (1)

	
	update: Tenemos que poner la opción “DESDE INTERNET” después de seleccionar HTTP/HTTPS

* **christian araya aros** (1)

	
	Carlos, tengo un dockerfile que crea una maquina para conectar a un mysql externo, ejecuta una query, descarga el resultado a un archivo y envia este a una carpeta del storage de gcp.  
	el acceso a este mysql es autorizado por IP, user, pass
	
	Pregunta cual es la mejor opcion para el deploy (local funciona perfecto). Pero al intentar deploy envia error CrashLoopBackOff en los pods

* **Daniel Herrera** (1)

	
	Siguiendo los pasos descritos, cuando se accede a la ip que nos devuelve el LB este arroja un error 404, alguien logró resolverlo?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Verifica que el servicio de tomcat este corriendo y que tengas correctamente configurado el LB, alguna configuración puede estar generando que no este conectando la instancia con el LB y por eso lanza el 404

	* **Walter Chacón** (2)

		
		Tuve el mismo problema, 404. El problema es que el Loadbalancer no tiene acceso al nodeport service y lo que no explican en el video es que hay que agregar un nuevo rule en el firewall para que cualquier address 0.0.0.0/0 tenga acceso al nodeport (<https://cloud.google.com/kubernetes-engine/docs/how-to/exposing-apps>), sigan los pasos en la sección “Create a firewall rule for your node port”

* **Germain Rafael Bueno Taguariparo** (1)

	
	Esta con figuración no funciona…  
	por favor actualizar el contenido… Estoy buscando documentación al respecto y no encuentro la solución y es un item muy importante.

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Qué error te da, si compartes el problema que tienes de seguro te podemos ayudar, que recuerde la configuración para nodeport no hay cambiado, aquí esta la documentación oficial <https://kubernetes.io/docs/concepts/services-networking/service/#nodeport>

* **zvillafuertesalvador** (1)

	
	Me aparece el siguiente error Carlos Prieto:
	
	  1. That’s an error.
	
	
	
	The requested URL / was not found on this server. That’s all we know.
	
	Favor de tu apoyo, o si alguna configuración adicional falto, favor de replicarlo tu mismo y comentarnos.
	
	Saudos.

* **Daniel Herrera** (1)
Siguiendo los pasos descritos, cuando se accede a la ip que nos devuelve el LB este arroja un error 404, alguien logró resolverlo?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Verifica que el servicio de tomcat este corriendo y que tengas correctamente configurado el LB, alguna configuración puede estar generando que no este conectando la instancia con el LB y por eso lanza el 404

* **Germain Rafael Bueno Taguariparo** (1)
Esta con figuración no funciona… por favor actualizar el contenido… Estoy buscando documentación al respecto y no encuentro la solución y...

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Qué error te da, si compartes el problema que tienes de seguro te podemos ayudar, que recuerde la configuración para nodeport no hay cambiado, aquí esta la documentación oficial <https://kubernetes.io/docs/concepts/services-networking/service/#nodeport>

## 0150. Crea tu primer Hola Mundo en Google Kubernetes Engine

### Descripción:


### Comentarios:

* **dutchster** (1)

	
	Hola, perdon ando paso a paso, mi pregunta es como configurar un apache un servicio LAMP, al mismo tiempo teniendo en otro contenedor dar servicios de ofimatica de ingresos a ciertas maquinas con claves, claro y que puedan usar la ofimatica de window …? es una prueba , gracias .

* **Alvaro   Gonzalez** (1)

	
	Si quiero actualizar petclinic, como se hace …?

	* **Alejandro Ortegano** (1)

		
		a que te refieres con actualizarlo osea que si tiene la versión 1.0 que tu fondo es azul y quieras montar tu versión 1.1 que tiene fondo azul y le cambiaste el color a un botón mas otro cambios agregados…  
		si es eso mi recomendación es que montes todo a partir de los archivos yml con tu deploy y servicio

# Conceptos intermedios

## 0160. Archivos descriptivos de infraestructura teoria y práctica

### Descripción:


Los archivos descriptivos nos permiten hacer despliegues de nuestras aplicaciones, pero en este caso, escribiendo nosotros mismos los archivos de configuración. No vamos a usar la interfaz gráfica. Estos archivos los escribimos en formato `.yaml`.

En estos archivos vamos a describir toda la parte lógica de nuestra aplicación: Pods, Deployments, Services e incluso las conexión entre aplicaciones. Recuerda que en estos archivos no podemos configurar ni los clusters ni lo nodos.

### Comentarios:

* **Alvaro   Gonzalez** (4)

	
	Por que no se eplico cada uno de las secciones de archivo deployment.yaml ?

* **juan camilo castillo saucedo** (1)

	
	Lo que no se puede describir como Cluster y Nodos si puede hacerse con [Terraform](https://www.terraform.io/)

* **VG_Analistas** (1)

	
	Por cada cambio que haya, generare un nuevo deployment?

* **Victoria Tejeda** (1)

	
	Integración Continua… hablas de Spinnaker?

* **Germain Rafael Bueno Taguariparo** (1)

	
	Muy interesante y todo pero este cotenido de este punto en adelante desanima si no dan soporte al video donde varios usaurios les indicamos que nos da error crear el Loadbalancer

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Qué tipo de error tienes, si compartes el error es más fácil poderte ayudar.

## 0170. Labels teoría

### Descripción:


Los Labels son una metadata arbitraria, esto quiere decir que podemos poner los nombre que queramos para generar una identidad a cualquier objeto _(servicios, deployments, etc)_. Pueden ser de tipo _Queryable_ _(buscables o seleccionables)_ , lo que nos permite agruparlos para generar despliegues de forma más fácil y hacer segregación de nuestros servicios.

Los selectores son una herramienta que nos permite utilizar los labels para saber cuándo comenzar a utilizar unos pods u otros en nuestros despliegues.

### Comentarios:

## 0180. Namespaces teoría

### Descripción:


Los Namespaces son una separación virtual dentro de nuestro cluster con el fin de hacer un aislamiento de nuestros datos y tener ambientes completamente separados. Podemos tener multiples namespaces dentro de nuestros clusters.

### Comentarios:

## 0190. Labels y Namespaces explicación gráfica

### Descripción:


### Comentarios:

* **Gonzalo Ezequiel Castro** (1)

	
	Cuando queremos separar nuestra arquitectura en diferentes enviromente (prod, test…) Cúal es la diferencia entre projecto o namespace? Cúal es la más recomendada?

	* **harryharango** (2)

		
		Hola compañero, voy a intentar responder lo que yo consideraría su uso, los **namespaces **, nos permite un aislamiento virtual en los nodos de del **cluster de google cloud** , por ejemplo en parametrizaciónes, podemos tener las conexiones a BD, valores secretos, volúmenes en específicos(directorios compartidos) por ambiente que nuestra app tomaría al momento de su ejecución. es decir que este tipo de configuración nos evita realizar un trabajo manual de configuración por ambiente y realizar una segregación de cosas de infraestructura, que no haya una afectación.  
		Por ejemplo se me ocurre, si quisieras paralizar un desarrollo y que dos equipos usen cosas diferentes en recursos físicos BD, directorios, etc, podrías tener dos ambientes de Testing. para esto seria su utilidad. espero haberte contestado a su pregunta

## 0200. Labels y Namespaces en práctica

### Descripción:


### Comentarios:

* **Jair Sebastian Lozano Moron** (2)

	
	cuando eliminaste o donde está el workload(carga de trabajo) petclinic-app1 y además estabamos trabajando en el cluster petclinic, y ahora resulta que cambiaste de cluster petclinic al cluster-1 creado en el video para youtube, porqué?

* **Kevin William Roberts Costa** (0)

	
	Entonces cuando haces  
	`kubectl get pod`  
	se recibe default?

## 0210. Deployment Avanzado (Blue-green y Canary Deployment)

### Descripción:


 **Blue-green** : Es una técnica de despliegues que nos ayuda a tener actualizaciones de nuestra aplicación con cero _down time_. Para esto necesitamos, un ambiente el tráfico _(para el entorno de producción)_ y un segundo ambiente con las nuevas características de tu aplicación.

**Canary** : Nos sirve para hacer pruebas de nuevas versiones a un público pequeño, esto con el fin de averiguar cómo se comportan los usuarios frente a esta nueva versión.

### Comentarios:

## 0220. Implementando Deployment avanzados

### Descripción:


### Comentarios:

* **Alejandro Ortegano** (3)

	
	para mejor practica cuando construyan el contenedor usen esta bandera
	``` 
	    docker build -t nameimage:tag
	    
	```
	
	en este caso
	``` 
	    dockerbuild -t spring-framawork-petclinc:v2
	    
	```
	
	y asi no usan un paso mas seria lo del tag

	* **Alejandro Ortegano** (2)

		```
		    dockerbuild -t gcr.io/nameproject./spring-framawork-petclinc:v2
		    
		```

* **Kevin William Roberts Costa** (1)

	
	De donde salió el puerto :’( no me funciona

	* **Kevin William Roberts Costa** (1)

		
		En la clase 5 dejaron una re ayuda, resulta que no hay que usar TOMCAT, sino jetty  
		./mvnw jetty:run-war

## 0230. Terminando de implementar nuestro canary deployment

### Descripción:


### Comentarios:

* **Carlos Jose Solar Zamorano** (1)

	
	Acá hay un poco más de información de los tipos de despliegue: <https://container-solutions.com/kubernetes-deployment-strategies/>

## 0240. Volúmenes

### Descripción:


Los volúmenes nos ayudan a implementar un almacenamiento persistente, en el que podamos acoplar y desacoplar los nodos sin que esta información desaparezca. Pueden ser de tipo persistente, NFS o cluster, pero dependiendo de la integración con diferentes nubes se podrán implementar nuevos tipos de volúmenes.

Los volúmenes son ideales para guardar la información de nuestros usuarios, archivos, configuraciones y compartir esta información con diferentes pods.

### Comentarios:

* **Syddar Bujato** (1)

	
	Excelente curso

* **Syddar Bujato** (1)

	
	Interesante curso

## 0250. Volúmenes en práctica

### Descripción:


### Comentarios:

* **Alejandro Ortegano** (2)

	
	una duda los archivos que queramos guardar en nuestro volumen tiene que estar en la ruta que creamos en el volumen. como en el ejemplo
	``` 
	    -mountPath: /test-pd
	    
	```
	
	y si funcionaria con los volúmenes persistente de kubernetes??

* **eveyeti** (1)

	
	Una consulta. Tengo un despliegue con una Base de datos Postgres, realicé el procedimiento de asociarle un disco persistente, tal como se enseñá en la práctica. Pero al eliminar el pod y recrearlo, efectivamente en el volumen se mantiene un directorio que creé de prueba. Pero los las tablas y registros que creé en la base de datos de prueba ya no existen. En este caso cual es el procedimiento cuando se trata de bases de datos, para actualizar la versión de la misma sin perder los datos?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		No vasta solo con montar el volumen, debes hacer un mapeo de la carpeta del volumen montado con la carpeta de la base de datos.

* **ernesto** (1)

	
	Hola que tal, el video no me esta cargando , utilizando chrome .

* **eveyeti** (1)
Una consulta. Tengo un despliegue con una Base de datos Postgres, realicé el procedimiento de asociarle un disco persistente, tal como se...

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		No vasta solo con montar el volumen, debes hacer un mapeo de la carpeta del volumen montado con la carpeta de la base de datos.

## 0260. RETO Crea un blue green deployment

### Descripción:


### Comentarios:

* **Kevin William Roberts Costa** (1)

	
	Armar la nueva versión, en este caso la v3
	``` 
	    ./mvnw jetty:run-war
	    dockerbuild .
	    docker tag [BUILDHASH] petclinicapp:v3
	    gcloud auth configure-docker
	    dockerpush gcr.io/[PROJECT_ID]/spring-framework-petclinic:v3
	    
	```
	
	ir a Workloads > +Deploy
	
	  * Seleccionar spring-framework-petclinic:v3
	
	  * App name: petclinicapp-v3
	
	  * Deploy
	
	  * Expose
	
	  * Mapping 8080:8080/TCP
	
	
	
	
	External endpoints: Nuevo IP:8080
	
	*pd: insertar imágenes arrastrando no funciona. (firefox)

# Arquitectura de una app más robusta

## 0270. Desplegar una aplicación Stateful Teoría

### Descripción:


Las aplicación Stateful son aplicaciones que guardan el estado de los datos para ser consultados posteriormente. Buenos ejemplos de aplicaciones Stateful son: las Bases de Datos, Data Warehouse, Modelos predictivos de IA, Gestores documentales, entre otros.

### Comentarios:

* **nachoogoomez** (1)

	
	Aquí viene lo bueno!!! 🚀 Aun que me da mucha pena que no se explique StorageClass y no se vayan a poner ejemplos de creación de cluster stateful de mongo, mysql, etc… 😔

	* **nachoogoomez** (4)

		
		Dejo un tutorial oficial de Kubernetes para montar un Replica Set de Mongo con Stateful Set: <https://kubernetes.io/blog/2017/01/running-mongodb-on-kubernetes-with-statefulsets/>

## 0280. Desplegar una aplicación Stateful Práctica

### Descripción:


### Comentarios:

* **Alejandro Ortegano** (2)

	
	tengo una duda e ejecutado un pod de postgres y configurado todo de como esta en este video. y creo una tabla dentro de postgres de la siguiente manera
	``` 
	    $ su postgres
	    $ psql
	    $ CREATEDATABASEtest;
	    
	```
	
	todo va bien pero cuando mato el pods y vuelvo a crearlo no tiene la tabla en ella y estoy utilizando un disco ?? como funcinaria en este caso ya que de esta forma no tengo muy claro su funcionamiento de los volumenes

	* **Carlos Prieto** (3)

		
		Por lo que comentas parece que el volumen no está en la ruta donde postgresql almacena los datos. Verifica que estas cargando el volumen en la ruta de postgresql, si utilizas la imagen postgres:9.4 la ruta de montaje de volumen debería ser /var/lib/postgresql/data

	* **Alejandro Ortegano** (1)

		
		gracias amigo si era es error despues me di cuenta que eso. gracias de toda forma

	* **Alejandro Ortegano** (1)

		
		le estaba pasando otra ruta que no era

	* **Brayan Mamani** (1)

		
		¡A bueno!

* **Alejandro Ortegano** (2)
tengo una duda e ejecutado un pod de postgres y configurado todo de como esta en este video. y creo una tabla dentro de postgres de la s...

	* **Carlos Prieto** (3)

		
		Por lo que comentas parece que el volumen no está en la ruta donde postgresql almacena los datos. Verifica que estas cargando el volumen en la ruta de postgresql, si utilizas la imagen postgres:9.4 la ruta de montaje de volumen debería ser /var/lib/postgresql/data

* **jorgeguega** (1)

	
	Hola a todos,  
	hay un par de cosas que no me quedan claras o creo que están erroneas:
	
	Cuando ejecutas la instrucción:
	``` 
	    kubectl exec -it mysql -- mysql -h mysql -ppassword
	    
	```
	
	  * Realmente te estas conectando al pod y no al servicio que has creado ¿Qué sentido tiene entonces crear el servicio?
	
	  * Cuando creas el servicio le pones como selector app: mysql el pod no tiene esa label por lo que nunca va a mapear el tráfico a ese pod, habría que añadir por ejemplo, el código que dejo más abajo en el pod y añadirlo a la sección de selector del servicio.
	
	
	
	``` 
	    metadata:
	      name: mysql
	      labels:
	        team: platzi
	    
	```
	
	Saludos 😉

* **Kevin William Roberts Costa** (1)

	
	Wow estuve muchisimo tiempo debugueando el problema y en el minuto 7.20 pide crear el disco

* **harryharango** (1)

	
	Tengo una inquietud sobre el tipo de despliegue utilizado para la BD mysql, si es un **Stateful** , el kind en ves de ser **POD** no debería ser **kind: StatefulSet**??

* **eveyeti** (1)

	
	En mi caso, realicé la prueba, con el mismo directorio, creé el despliegue de postgres para usar la data del despliegue anterior y en este el pod no se creo porque daba error “CrashLoopBackOff”. Al revisar los logs, sale el siguiente error:  
	initdb: directory “/var/lib/postgresql/data” exists but is not empty  
	If you want to create a new database system, either remove or empty  
	the directory “/var/lib/postgresql/data” or run initdb  
	with an argument other than “/var/lib/postgresql/data”.
	
	Se entiende que el nuevo despliegue no puede apuntar a la misma ruta porque esa no está vacía. Es claro que debe estar llena, con los datos del despliegue anterior, pero postgres en mi caso se rehusa a tomar el mismo directorio como el de datos. ¿ Qué puedo hacer en este caso ?

* **Andrés Muñoz** (1)
En un proyecto que ya maneja una carga significativa de usuarios se puede usar uno o varios containers con mongodb y estos conectados a u...

## 0290. Auto Scaling teoría

### Descripción:


Auto Scaling es una practica que nos permite crecer nuestros clusters de manera dinámica.

Entre más tráfico tenga nuestra aplicación, más nodos se crearán en nuestro cluster. Así también, entre menos tráfico tenga nuestra aplicación, estos nodos van a desaparecer, dejando la cantidad de nodos suficiente para atender a los usuarios.

### Comentarios:

* **Andrés Muñoz** (1)
Cuando una app empieza a autoScalar las personas que usan la app lo van a notar ? De pronto puede ser que un request se pierda ? O se pon...

## 0300. Auto Scaling en práctica

### Descripción:


### Comentarios:

* **REINALDO ORJUELA GODOY** (2)

	
	Nada que funciona la prueba con backend …siempres sale error 404…

* **Kevin William Roberts Costa** (1)

	
	Es una lástima que esta clase no se pueda hacer.

* **Kevin William Roberts Costa** (1)

	
	 **acá está directamente MAL**
	
	  * en 1:35 termina de crear cluster-1
	  * en 1.41 hay un servicio ya funcionando en cluster-1  
	por favor presten atención en la edición esto es muy frustrante
	
	

* **Juan Francisco Mosquera** (1)

	
	porque fue necesario definir un load balancer , si en la definición del cluster ya tienes las reglas de autoscaling ? .

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		El loadbalancer es el que se encarga de dirigir el tráfico a la instancia del cluster con menos carga en el momento de la petición, si tienes 3 maquinas detrás de un load balancer entonces apenas llega una petición el load balancer intenta enviar la petición a la maquina con menos carga o la que responda más rápido.

* **Juan Francisco Mosquera** (1)

	
	Cuantas maquinas mínimas se requieren en un cluster ?.  
	Google cloud platform tiene alguna herramienta para testear el estrés sobre el cluster ?.

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Eso depende del tráfico, si es poco el trafico puede que tu cluster de kubernetes corra en una sola maquina, también depende de las especificaciones de la máquina, no es lo mismo una maquina de 4gb de ram que una con 32gb de ram.

* **Alfredo Arroyo Diaz** (1)

	
	Apache benchmark = realiza pruebas de estres

* **Rafael Ernesto Ferro González** (1)

	
	Alguna referencia de como configurar esto directamente en los ficheros de configuración?

* **Rafael Ernesto Ferro González** (1)
Alguna referencia de como configurar esto directamente en los ficheros de configuración?

## 0310. Node Pools teoría

### Descripción:


Los Node Pools son agrupaciones de máquinas que nos permiten generar un cluster híbrido con máquinas de diferentes tipos y tamaños.

### Comentarios:

## 0320. Node Pools práctica

### Descripción:


### Comentarios:

# Contenido Bonus

## 0330. Generando un certificado https con Let's Encrypt para GCP

### Descripción:


El protocolo https es una herramienta útil a nivel de seguridad de la información debido a que te permite cifrar la información haciendo más segura la transmisión de datos. Esta herramienta también te permite generar confianza en tus usuarios por que les indica que estas preocupado por proteger su información. Por este motivo en esta lectura vamos a ver como crear un certificado https con Let’s Encrypt para que funcione en los diferentes servicios de Google Cloud Platform.

Lo primero que tienes que saber es que es Let’s Encrypt, la cual es una entidad certificadora que está dando certificados ssl de manera gratuita (normalmente estos certificados tienen un costo que supera los 50 dólares por año) con una duración de 3 meses (esto significa que hay que renovarlos antes de la fecha de vencimiento).

Ahora vamos a ver cuales son los pasos para crear el certificado:

## 0\. Prerrequisitos:

a. Comprar un dominio y tener acceso al administrador de los DNS  
b. Configurar un proyecto en Google Cloud Platform  
c. Habilitar la facturación ingresando una tarjeta de crédito (te sugiero activar los créditos que ofrece la plataforma para no tener gastos en la tarjeta de crédito).  
d. Acceder a Google Cloud Shell entrando a <https://console.cloud.google.com> y haciendo click en el botón de Cloud Shell que está en la parte superior izquierda del panel  
![Captura de pantalla 2018-09-18 a la\(s\) 9.17.08 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-09-18%20a%20la%28s%29%209.17.08%20a.%20m.-2180e1bb-1dfe-4976-98a0-82aaa79c35c9.jpg)

O ingresando desde el navegador a <https://console.cloud.google.com/cloudshell>

## 1\. Instalación del agente:

Para generar el certificado hay que instalar un agente llamado **certbot** , él cual es un programa en línea de comandos que permite automatizar la mayor parte de los pasos. La forma más sencilla de utilizarlo es por medio de la imagen oficial de docker. Para facilitar su utilización vamos a crear un alias del comando de docker para utilizarlo como si fuera el comando certbot.

`echo "alias certbot='docker run -it -v ~/letsencrypt/:/etc/letsencrypt/ certbot/certbot'" >> .aliases echo "source .aliases" >> .bashrc source .aliases`

## 2\. Creación del certificado:

Para la creación del certificado vamos a correr el comando **cerbot** con las banderas **–manual --preferred-challenges dns** para indicar que la creación es de manera manual (porque Let’s Encrypt permite crear el certificado de manera automática como plugin de Apache o Nginx), utilizando reto para la validación y que dicho reto es por DNS (o sea poniendo un registro de tipo TXT en los DNS). Para ello corremos los siguientes comandos:

`certbot certonly --manual --preferred-challenges dns`

Esto activará un asistente paso a paso el cual nos preguntará cual es el correo electrónico que estará ligado al certificado y luego nos preguntará si estamos de acuerdo con las políticas de uso del servicio, a lo cual responderemos con la letra **A** (de Agree).

Luego preguntará si estamos de acuerdo con compartir nuestra dirección de correo como parte de la validación del certificado a lo cual puedes responder **Y** o **N** dependiendo de tus preferencias.

Ahora nos pregunta cual es el dominio para el cual le vamos a instalar el certificado en mi caso es **[test.carlos-prieto.com](http://test.carlos-prieto.com)**

`Please enter in your domain name(s) (comma and/or space separated) (Enter 'c' to cancel): test.carlos-prieto.com Obtaining a new certificate Performing the following challenges: dns-01 challenge for test.carlos-prieto.com`  
Después nos pide confirmación para guardar la IP del dominio en los registros de Let’s Encrypt a lo cual debemos responder **Y**.

Ahora aparece un mensaje el cual dice que debemos crear un registro de tipo TXT para el dominio **_acme-challenge. <tu [dominio.com](http://dominio.com)>** en mi caso es **_acme-challenge.test.carlos-prieto.com** con una cadena de texto que muestra el mensaje.

`- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
Please deploy a DNS TXT record under the name  
_acme-challenge.<tu [dominio.com](http://dominio.com)> with the following value:  
sdsa3bLuFmkJXh-8pGvDLWoCcSAWUPwNnyyf1VvJUio  
Before continuing, verify the record is deployed.

Ahora vamos a nuestro servicio de dns creamos el registro txt con la cadena de texto y verificamos el registro. para ello podemos hacerlo por medio de la página <https://mxtoolbox.com/> y en la caja de texto **Domain Name** ponemos **txt:_acme-challenge. <[tudominio.com](http://tudominio.com)>** en mi caso es **txt:_acme-challenge.test.carlos-prieto.com**

![Captura de pantalla 2018-09-18 a la\(s\) 10.15.19 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-09-18%20a%20la%28s%29%2010.15.19%20a.%20m.-2efcf475-899a-48f3-8e11-99ca5f5f927a.jpg)

Hacemos click en el botón para verificar (esto puede tardar algún tiempo dependiendo del TTL que configures, por lo que tendrás que hacerlo varias veces ) y aparecerá un mensaje como el siguiente.

![Captura de pantalla 2018-09-18 a la\(s\) 10.18.39 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-09-18%20a%20la%28s%29%2010.18.39%20a.%20m.-4c626c44-da6b-441d-a105-e2f86c294a83.jpg)

Después vamos nuevamente al Cloud Shell y damos Enter para que se valide la información. Si todo fue correcto Let’s Encrypt nos felicitara diciendo que el proceso fue exitoso.

## 3\. Creación de llave privada en rsa y configuración de permisos sobre archivos.

Para tener acceso a los archivos del certificado y poderlos manipular le vamos a dar permisos de lectura y escritura a nuestro usuario con el siguiente comando:

`sudo chmod -R 755 ~/letsencrypt/archive`

Para que se pueda configurar el certificado que acabamos de generar en Google Cloud Platform hay que convertir la llave privada al formato rsa para lo cual ejecutamos el siguiente comando (Cambiar la palabra **< tu [dominio.com](http://dominio.com)>** por tu dominio en mi caso es **[test.carlos-prieto.com](http://test.carlos-prieto.com)** ).

`sudo openssl rsa -inform pem -in ~/letsencrypt/archive/<tu dominio.com>/privkey1.pem -outform pem > ~/letsencrypt/archive/<tu dominio.com>/rsaprivatekey.pem`

Con estos pasos ya están listo los archivos para poder realizar la configuración del certificado https en los servicios de GCP Loadbalancer o Google App Engine. Para poder copiarlos más fácilmente te sugiero abras estos archivos con el editor de texto de Cloud Shell haciendo click en el icono del lápiz en Cloud Shell.

![Captura de pantalla 2018-09-18 a la\(s\) 11.00.51 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-09-18%20a%20la%28s%29%2011.00.51%20a.%20m.-880f55d2-7d04-4b6a-9c7f-1091383f91da.jpg)

Espero que esta información te sirva para la creación del certificado https en tus proyectos de GCP y no olvides visitar el curso de Kubernetes Engine que esta en <https://platzi.com/cursos/kubernetes-xertica/>

### Comentarios:

* **Kevin William Roberts Costa** (2)

	
	No me funcionó
	``` 
	    $ echo "alias certbot='docker run -it -v ~/letsencrypt/:/etc/letsencrypt/ certbot/certbot'" >> .aliases echo "source .aliases" >> .bashrc source .aliases
	    $ certbot
	    -bash: certbot: command not found
	    
	```

* **nachoogoomez** (2)
¿Con esta opción deberíamos actualizar manualmente nosotros los certificados cada tres meses no?

	* **Carlos Prieto** (1)

		
		Si, cada 3 meses se debe realizar la actualización manual de los certificados.

* **nachoogoomez** (1)

	
	¿Con esta opción deberíamos actualizar manualmente nosotros los certificados cada tres meses no?

	* **Carlos Prieto** (1)

		
		Si, cada 3 meses se debe realizar la actualización manual de los certificados.

## 0340. Certificado https

### Descripción:


En la lectura anterior aprendimos cómo crear y configurar un certificado https que funciona directamente con GCP. En esta clase vamos aprenderemos cómo poner el certificado en nuestro balanceador de carga.

### Comentarios:

* **isaacarismendi** (3)

	
	Hola, como pudiera realizar certificados con lets encrypt en kubernetes pero que se actualicen automaticamente ?

	* **John Freddy Vega (Platzi)** (6)

		
		Se hace con algo llamada “[Kubernetes Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)”. Ingress es la cosa (un API Object para ser técnico) que maneja el acceso externo de servicios en un cluster.
		
		La forma automática que encontré es esta:  
		<https://akomljen.com/get-automatic-https-with-lets-encrypt-and-kubernetes-ingress/>
		
		Que en síntesis es llamar al API de Let’s Encrypt para crear los certificados, a través de [Cert Manager](https://github.com/jetstack/cert-manager).
		
		No es la única forma, aquí hay otro:  
		<https://runnable.com/blog/how-to-use-lets-encrypt-on-kubernetes>
		
		Había una vieja llamada “kube-lego” pero Cert Manager la reemplazó
		
		En el curso completo de Kubernetes (viene pronto) ahondaremos en eso.

	* **julian aguirre Aguirre Romo** (1)

		
		si creo q deberían haberlo enseñado, usar ingress con nginx o traefik con ssl

	* **jorgeguega** (1)

		
		Buenas justo lo que comenta @freddier yo lo he desplegado un mi proyecto con Helm y finciona muy bien. Te dejo el enlace:  
		<https://github.com/helm/charts/tree/master/stable/cert-manager>

* **isaacarismendi** (2)
Hola, como pudiera realizar certificados con lets encrypt en kubernetes pero que se actualicen automaticamente ?

	* **John Freddy Vega (Platzi)** (6)

		
		Se hace con algo llamada “[Kubernetes Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)”. Ingress es la cosa (un API Object para ser técnico) que maneja el acceso externo de servicios en un cluster.
		
		La forma automática que encontré es esta:  
		<https://akomljen.com/get-automatic-https-with-lets-encrypt-and-kubernetes-ingress/>
		
		Que en síntesis es llamar al API de Let’s Encrypt para crear los certificados, a través de [Cert Manager](https://github.com/jetstack/cert-manager).
		
		No es la única forma, aquí hay otro:  
		<https://runnable.com/blog/how-to-use-lets-encrypt-on-kubernetes>
		
		Había una vieja llamada “kube-lego” pero Cert Manager la reemplazó
		
		En el curso completo de Kubernetes (viene pronto) ahondaremos en eso.

* **Julián** (1)

	
	Si tengo 6 servicios debo actualizar uno por uno? haciendo todo el procedimiento 1x1 cada 3 meses?

* **nachoogoomez** (1)

	
	A genial!!! Que este load balancer no es el load balancer por defecto que se crea cuando haces el servicio con tipo load balancer! Genial!!!

* **Julián** (1)
y si tengo más microservicios o “backends” el procedimiento indicado solo me genera https para el principal cómo hago para los demás?

## 0350. Service mesh con Istio

### Descripción:


Service Mesh nos ayuda a fortalecer las políticas de comunicación en nuestros clusters de kubernetes.

Si tenemos una aplicación que se comunica con un almacén de datos en producción, no queremos que las versiones de desarrollo se comuniquen con las versiones de producción.

Para esto, normalmente necesitaríamos generar muchas máquinas aisladas por sub-redes, fortaleciendo los procesos por medio de firewalls, proxies y demás servicios de red. Todo esto enfocado hacia los bytes que se transmiten dentro de la red.

Con Service Mesh podemos definir estas reglas de comunicación a un alto nivel, a través de servicios usando un lenguaje declarativo.

**Caracteristicas de Service Mesh:**

  * Red para servicios, no para bytes
  * Visibilidad
  * Resiliencia y eficacia
  * Control de tráfico
  * Seguridad
  * Fortalecimiento de políticas



Istio es un producto creado por Google e IBM que nos ayuda a reducir la complejidad del Service Mesh. Ademas, nos ayuda a tener control sobre los servicios de nuestra aplicación y entender el tráfico de cada uno de estos.

**Características de Istio:**

  * Provee un service discovery
  * Seguridad
  * Instrumentación
  * Rutas dinámicas
  * Telemetría



### Comentarios:

## 0360. StackDriver

### Descripción:


Stackdriver es un servicio que nos provee Google para monitoreo, alertas, logs y ayuda sobre el control nuestras aplicaciones. Ademas, Kubernetes Engine tiene conexión directa _(sin la necesidad de generar o instalar agentes diferentes)_ con Stackdriver.

### Comentarios:

* **alexochoalacruz** (1)
Para que genere la notificación en caso de error necesito un permiso en específico?, o debo ingresar los destinatarios en alguna parte?. ...

## 0370. CICD con Cloud Builder

### Descripción:


 **Continuous Integration** y **Continuous Delivery** son dos conceptos que nos ayudan a desplegar muy rápido las versiones de nuestra aplicación. Estaremos integrando continuamente nuestra aplicación a través de herramientas como Jenkins o Terraform, para describir la infraestructura de nuestra aplicación y estar constantemente enviando nuevas versiones de nuestras aplicaciones.

Recuerda que puedes aprender mucho más sobre estos conceptos en el [Curso Profesional de DevOps](https://platzi.com/cursos/devops/).

Cloud Builder nos ayuda a automatizar muchas tareas en el despliegue de aplicaciones. Gracias a esta herramienta y todas sus integraciones _(Cloud Registry, Cloud Repository)_ vamos a generar el build de nuestra aplicación, generar el contenedor, hacer pruebas y hacer el despliegue.

### Comentarios:

## 0380. CICD con Cloud Builder práctica

### Descripción:


### Links:

* [GitHub - cprietorod/cloudBuilder](https://github.com/cprietorod/cloudBuilder.git)

### Comentarios:

* **ricardocelis (Platzi)** (2)

	
	<https://github.com/cprietorod/cloudBuilder.git>

* **Julián** (1)

	
	El tema de la clase dice CI /CD pero no hacen CD, estoy estancado no puedo en la tarea que seguiría en el cloudbuild pasarle al deployment.yaml el contenedor creado recién no me acepta el $BUILD_ID

* **julian aguirre Aguirre Romo** (1)
El tema de la clase dice CI /CD pero no hacen el deploy automitizado

## 0390. Knative, GKE Serverless Addon

### Descripción:


 **Serverless** es un tipo de arquitectura donde los servidores _(físicos o en la nube)_ dejan de existir para el desarrollador y en cambio el código corre en ““ambientes de ejecución”” que administran proveedores como Amazon, Google, IBM, entre otros.

**Características de Serverless** :

  * No se administran servidores
  * Auto Escalable
  * Fácil integración con otros servicios del proveedor
  * Cobro por uso



**Knative** es una solución open-source que brinda servicios tipo serverless para desplegar contenedores. Esta herramienta es amigable con los desarrolladores ya que se encarga de la administración del cluster, saber cuantas replicas necesita nuestra aplicación, cuales son los pods, etc. Incluso podemos escalar nuestras aplicaciones desde 0.

**GKE Serverless Addon** es una implementación de Knative auto-administrada gracias a Google Kubernetes Engine. Esta herramienta fue anunciada en el Google Cloud Next 18 y aún esta en estado Alfa, pero muy pronto estará disponible para el público.

### Comentarios:

* **Wilson Fabian Pérez Sucuzhañay** (4)

	
	YA con este video para que los anteriores jajaja

	* **John Freddy Vega (Platzi)** (1)

		
		¿Por qué? 🤔

## 0400. Comandos utilizados en el curso

### Descripción:


## Comandos Básicos de Docker

  * git clone <https://github.com/spring-petclinic/spring-framework-petclinic.git> #clone
  * cd ~/spring-framework-petclinic
  * ./mvnw tomcat7:run-war #run app
  * curl <http://localhost:9966/petclinic> #get app
  * docker pull tomcat:8
  * docker images
  * docker run -d -p 8080:8080 tomcat:8
  * docker ps
  * docker exec -it <container id> bash
  * docker stop <container id>
  * docker ps -a
  * docker rm <container id>



## Creación del contenedor de Docker

  * ouch Dockerfile

  * Contenido del archivo Dockerfile  
–FROM tomcat:8  
–COPY target/petclinic.war /usr/local/tomcat/webapps  
–EXPOSE 8080

  * docker build ./

  * docker tag <image id> spring-framework-petclinic

  * docker rm $(docker ps -qa)

  * gcloud auth configure-docker

  * docker tag spring-framework-petclinic [gcr.io/[PROJECT-ID]/spring-framework-petclinic:v1](http://gcr.io/%5BPROJECT-ID%5D/spring-framework-petclinic:v1)

  * docker push [gcr.io/[PROJECT-ID]//spring-framework-petclinic:v1](http://gcr.io/%5BPROJECT-ID%5D//spring-framework-petclinic:v1)

  * gcloud container images list




## Pods y Deployments en práctica

Todo fue por interfaz gráfica

## Servicios en práctica

Todo fue por interfaz gráfica

## Archivos descriptivos de infraestructura teoría y práctica

  * kubectl create -f deployment.yaml
  * kubectl create -f service.yaml



## Labels y Namespaces en práctica

  * kubectl get namespaces
  * kubectl create namespace desarrollo
  * kubectl --namespace=desarrollo create -f deployment.yaml



## Implementando Deployment avanzados

Todo fue por interfaz gráfica

## Volúmenes en práctica

  * touch volume.yaml
  * contenido del archivo  
apiVersion: v1  
kind: Pod  
metadata:  
name: test-pd  
spec:  
containers: 
    * image: tomcat:8  
name: test-container  
volumeMounts: 
      * mountPath: /test-pd  
name: test-volume  
volumes:
    * name: test-volume  
#This GCE PD must already exist.  
gcePersistentDisk:  
pdName: my-data-disk  
fsType: ext4
  * kubectl create -f volume.yaml



## Desplegar una aplicación Stateful Práctica

  * touch mysql.yaml
  * Contenido del archivo mysql.yaml  
apiVersion: v1  
kind: Pod  
metadata:  
name: mysql  
spec:  
containers: 
    * image: mysql:5.6  
name: test-container  
env: 
      * name: MYSQL_ROOT_PASSWORD  
value: password  
ports:
      * containerPort: 3306  
name: mysql  
volumeMounts:
      * mountPath: /var/lib/mysql  
name: mysql-persistent-storage  
volumes:
    * name: mysql-persistent-storage  
gcePersistentDisk:  
pdName: disk-2  
fsType: ext4



* * *

apiVersion: v1  
kind: Service  
metadata:  
name: mysql  
spec:  
ports:

  * port: 3306  
selector:  
app: mysql  
clusterIP: None
  * kubectl create -f mysql.yaml



## Auto Scaling en práctica

  * sudo apt-get install apache2-utils
  * ab -t 10 -n 100000 -c 10 <ip loadbalancer>



## Node Pools práctica

  * touch node_pool.yaml
  * Contenido del archivo node_pool.yaml  
apiVersion: v1  
kind: Pod  
metadata:  
name: nginx  
labels:  
env: test  
spec:  
containers: 
    * name: nginx  
image: nginx  
imagePullPolicy: IfNotPresent  
nodeSelector:  
name: pool1
  * kubectl create -f node_pool.yaml
  * touch pod1.yaml
  * Contenido del archivo pod1.yaml  
apiVersion: v1  
kind: Pod  
metadata:  
name: nginx  
labels:  
env: test  
spec:  
containers: 
    * name: nginx  
image: nginx  
nodeSelector:  
name : pool1
  * kubectl create -f pod1.yaml



## Generando un certificado https

Todo fue por interfaz gráfica

## CI/CD con Cloud Builder práctica

  * git clone <https://github.com/cprietorod/cloudBuilder.git>
  * git config --global credential.<https://source.developers.google.com.helper> [gcloud.sh](http://gcloud.sh)
  * git remote add google <https://source.developers.google.com/p/><ID proyecto>/r/hello
  * git push --all google  
contenido del archivo cloudbuild.yaml  
steps:
  * name: '[gcr.io/cloud-builders/docker](http://gcr.io/cloud-builders/docker)’  
args: [ ‘build’, ‘-t’, “[gcr.io/$PROJECT_ID/hello-web-app:v$BUILD_ID](http://gcr.io/$PROJECT_ID/hello-web-app:v$BUILD_ID)”, ‘.’ ]
  * name: '[gcr.io/cloud-builders/docker](http://gcr.io/cloud-builders/docker)’  
args: [‘push’, “[gcr.io/$PROJECT_ID/hello-web-app:v$BUILD_ID](http://gcr.io/$PROJECT_ID/hello-web-app:v$BUILD_ID)”]  
env: 
    * CLOUDSDK_COMPUTE_ZONE=${_CLOUDSDK_COMPUTE_ZONE}
    * CLOUDSDK_CONTAINER_CLUSTER=${_CLOUDSDK_CONTAINER_CLUSTER}
  * git add .
  * git commit -m “some changes”
  * git push google master



### Comentarios:

* **JMM** (2)

	
	Muy bien por esta sección!!! Ojala lo hagan para otros cursos. Mas allá que uno toma notas, nunca esta demás tener un machete completo 😃

* **Juan Francisco Mosquera** (2)

	
	Gracias.

* **Yully Adriana Gamboa Contreras** (1)

	
	Gracias poreste resumen de comandos

* **Julián** (1)

	
	porq no hicieron CD en el curso?

* **Brayan Mamani** (1)

	
	¡Buen Articulo! Para realizar el trabajo de forma correcta.

## 0410. Buenas prácticas

### Descripción:


  * Hacer contenedores pequeños _(las versiones _ALPINE_ son las mejores en cuanto a seguridad)_
  * Organizar despliegues con namespaces
  * Configurar los Health Checks
  * Configurar límites en el número de peticiones
  * Terminar con Gracia _(cerrar los servicios correctamente guardando antes la información de tus usuarios)_



### Comentarios:

* **KaterineAT** (4)
Genial el curso gracias. En el tema anterior dice 'ouch Dockerfile'

* **Esteban Ramos Fernández** (3)

	
	Muy buen curso, el contenido es bien completo y resuelve todas las problemáticas para levantar una aplicación en producción en sus fases avanzadas.

* **Fernando Eladio Alvarez Noya** (2)

	
	Especial el curso, la verdad me gusto mucho, si habra todavia por aprender! 😃

* **angelg** (2)

	
	Muy completo el curso. Como sugerencia, sería bueno incorporar al menos una breve explicación en texto, o enlaces con mayor información de cada tema.

* **jorgeguega** (1)

	
	Gracias por el curso! 😉

