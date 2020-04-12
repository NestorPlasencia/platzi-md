[Curso de Swarm 1434](https://platzi.com/cursos/docker-swarm)

# Conceptos básicos [2984]

## 0010. Bienvenida al curso [15397](https://platzi.com/clases/1434-docker-swarm/15397-bienvenida-al-curso7109/)

### Descripción:


¡Bienvenidos al curso de **Swarm**!

Te presentamos a el profesor de este curso : _Guido Vilariño_

Te recomendamos que previamente hayas realizado el curso de [Fundamentos de Docker](https://platzi.com/clases/docker/) o que tengas una noción básica de Docker.

### Comentarios:

* **Diego Andres Fonseca Soto** (11) [436136](https://platzi.com/comentario/436136/) 

	Me devore el curso de Docker en 2 dias, ahora vengo por esta maravilla, excelente profesor.

* **Brando Rodríguez** (2) [913671](https://platzi.com/comentario/913671/) 

	Me encanta este Tipo, a darle con el curso.

* **Paul Alarcon** (2) [491000](https://platzi.com/comentario/491000/) 

	open source rules!!

* **Camilo Castillo** (2) [436412](https://platzi.com/comentario/436412/) 

	A con toda con este curso !

* **SOFTDYNAMIC** (1) [1118554](https://platzi.com/comentario/1118554/) 

	A DARLE!

* **wilantury** (1) [1062487](https://platzi.com/comentario/1062487/) 

	Vengo del curso de docker, me pareció excelente.

* **HeartHunter** (1) [984646](https://platzi.com/comentario/984646/) 

	Un nuevo curso antes de san valentin

* **carlosbazanhuaman** (1) [971461](https://platzi.com/comentario/971461/) 

	interesante a empezar.

* **Boris Vargas Paucara** (1) [964616](https://platzi.com/comentario/964616/) 

	Para recordar comandos del curso Fundamentos de Docker: [imagen](https://twitter.com/yodralopez/status/1224082520725127168?s=08)

* **ehnbytes** (1) [832643](https://platzi.com/comentario/832643/) 

	Muy interesante!!

* **dbzdavidbaez** (1) [800685](https://platzi.com/comentario/800685/) 

	Muy interesante, vamos a aprender docker y docker swarm

* **Leonardo Aviles Meneses** (1) [755079](https://platzi.com/comentario/755079/) 
A seguir aprendiendo docker

* **ricardo-rod** (1) [685416](https://platzi.com/comentario/685416/) 

	bien

* **JPabloMayorgaM** (1) [588761](https://platzi.com/comentario/588761/) 

	Excelente!!

## 0020. ¿Qué es Swarm [15880](https://platzi.com/clases/1434-docker-swarm/15880-que-es-swarm/)

### Descripción:


### Comentarios:

* **JoePlatzi2018** (2) [554367](https://platzi.com/comentario/554367/) 

	Rolling Deployments  
	[https://octopus.com/docs/deployment-patterns/rolling-deployments](url)

* **Paul Alarcon** (2) [510970](https://platzi.com/comentario/510970/) 

	Tengo una consulta al hablar del port binding, con un lenguaje como java o node, por defecto nos van a presentar un puerto atado a sus configuraciones web (8080, o 3000) por defecto, entonces el acceso por un proxy reverso sería, una omisión del port binding o lo estoy entendiendo mal ?

* **Felipe Jurado Murillo** (1) [1109552](https://platzi.com/comentario/1109552/) 

	Si se quiere hacer una actualización toda ir máquina por máquina, frenando los contenedores, rotando los contenedores, volviendo a subirlo. Esto es rolling deployment
	
	Sería ideal poder tener muchas máquinas y poder anistarlar cuando creamos contenedores.  
	Solución de cluster que nos da Docker, propone tengamos un cluster de muchas máquinas pero que desde afuera hacia los usuarios administrativos, se vean como si fuera un docker daemon, un entorno de docker que atraviesa muchas máquinas.
	
	Cómo sí estuviera usando docker local, pero tenemos acceso a un montón de máquinas, donde cada una está corriendo su docker daemon y nos facilita quiero actualizar este servicio.  
	Aprovechar esto para que nuestras aplicaciones sean altamente disponibles y muy fáciles de administrar

* **wilantury** (1) [1063539](https://platzi.com/comentario/1063539/) 

	* Docker swarm es la solución nativa de clustering que tiene docker.
	
	

* **carlosbazanhuaman** (1) [971470](https://platzi.com/comentario/971470/) 

	Por lo que comenta guido es una buena herramienta, pero porque no escucho mucho hablar de ella en las propuestas de soluciones de cluster de docker?.

## 0030. El problema de la escala qué pasa cuando una computadora sóla no alcanza [15396](https://platzi.com/clases/1434-docker-swarm/15396-el-problema-de-la-escala-que-pasa-cuando-una-compu/)

### Descripción:


La **escalabilidad** es el poder aumentar la capacidad de potencia de computo para poder servir a más usuarios o a procesos más pesados a medida que la demanda avanza.

A la hora de hablar de escalabilidad encontramos dos tipos de soluciones, escalabilidad vertical, que consiste en adquirir un mejor hardware que soporte mi solución o una escalabilidad horizontal, en la cual varias máquinas están corriendo el mismo software y por lo tanto es la solución más utilizada en los últimos tiempos.

La **disponibilidad** es la capacidad de una aplicación o un servicio de poder estar siempre disponible (24 horas del día), aún cuando suceda un improvisto.

**Es mayor la disponibilidad cuando se realiza escalabilidad horizontal**

Swarm no ofrece la solución a estos problemas.

### Comentarios:

* **wilantury** (2) [1063557](https://platzi.com/comentario/1063557/) 

	* Ejecutar aplicaciones productivas: la aplicación debe estar lista para servir a las usuarios a pesar de situaciones catastróficas, o de alta demanda (carga).
	* Escalabilidad: Poder aumentar la potencia de cómputo para poder servir a más usuarios, o a peticiones pesadas.
	* Escalabilidad vertical: Más hardware, hay límite físico.
	* Escalabilidad horizontal: Distribuir carga entre muchas computadoras. es el más usado.
	* Disponibilidad: Es la capacidad de una aplicación o servicio de estar siempre disponible para los usuarios. prevé problemas con servidores, etc.
	* La escalabilidad horizontal y la disponibilidad van de la mano.
	
	

* **carlosbazanhuaman** (1) [971484](https://platzi.com/comentario/971484/) 

	para hacer escalabilidad horizontal las pc tienen que ser igual en caracteristicas?

* **benitezconzeta** (1) [481134](https://platzi.com/comentario/481134/) 

	Muy buena explicación Guido. Gracias por tus excelentes clases!!!

* **Ralph Sliger** (1) [436584](https://platzi.com/comentario/436584/) 

	La disponibilidad: es la capacidad que tiene tu aplicación de estar disponible, siempre que sea llamada c;

## 0040. Arquitectura de Docker Swarm [15399](https://platzi.com/clases/1434-docker-swarm/15399-arquitectura-de-docker-swarm/)

### Descripción:


La arquitectura de Swarm tiene un esquema de dos tipos de servidores involucrados: los managers y los workers.

* Los managers son encargados de administrar la comunicación entre los contenedores para que sea una unidad homogénea.

* Los workers son nodos donde se van a ejecutar contenedores, funciona como un núcleo, los contenedores estarán corriendo en los workers.




**Todos deben tener Docker Daemon (idealmente la misma versión) y deben ser visibles entre sí. **

### Comentarios:

* **Ariel_Ayala** (3) [538860](https://platzi.com/comentario/538860/) 

	El swarn de docker es un cluster muchas máquinas que están conectadas entre sí en red.
	
	Swarn **administra ** la comunicación entre ellas para que sean una unidad homogénea en la cual podamos correr aplicaciones.

* **Jean Carlos Nuñez Hernandez** (3) [439836](https://platzi.com/comentario/439836/) 

	Me gusta swarm

* **wilantury** (1) [1063563](https://platzi.com/comentario/1063563/) 

	 **Dos tipos de máquinas:**
	
	* Manager nodes: deciden donde se corren los contenedores, como se comunican, donde hay recursos, vigila el estado de los contenedores para garantizar disponibilidad.
	* Worker nodes: son más que los manager, aquí se van a ejecutar contenedores, son el núcleo de la aplicación, la parte productiva. Todos deben tener docker daemon, idealmente la misma versión. Deben estar todos en la misma red.
	* Debemos saber si nuestras aplicaciones están listas para correr con docker swarm
	
	

* **Jesús Alberto Martínez Hernández** (1) [960073](https://platzi.com/comentario/960073/) 

	Manager se encarga de correr tu contenedor, como se comunica entre sí, en donde hay recursos disponibles mueve los servicios a otro nodo si falla alguno.

## 0050. Preparando tus aplicaciones para Docker Swarm los 12 factores [15401](https://platzi.com/clases/1434-docker-swarm/15401-preparando-tus-aplicaciones-para-docker-swarm-los-/)

### Descripción:


**¿ Está tu aplicación preparada para Docker Swarm ? **  
Para saberlo, necesitas comprobarlo con los 12 factores

  1. Codebase : el código debe estar en un repositorio
  2. Dependencies : deben estar declaradas en un archivo de formato versionable, suele ser un archivo de código
  3. Configuration : debe formar parte de la aplicación cuando esté corriendo, puede ser dentro de un archivo
  4. Backing services : debe estar conectada a tu aplicación sin que esté dentro, se debe tratar como algo externo
  5. Build, release, run : deben estar separadas entre sí.
  6. Processes : todos los procesos los puede hacer como una unidad atómica
  7. Port binding : tu aplicación debe poder exponerse a sí misma sin necesidad de algo intermediario
  8. Concurrency : que pueda correr con múltiples instancias en paralelo
  9. Disposabilty : debe estar diseñada para que sea fácilmente destruible
  10. Dev/Prod parity : lograr que tu aplicación sea lo más parecido a lo que estará en producción
  11. Logs : todos los logs deben tratarse como flujos de bytes
  12. Admin processes : la aplicación tiene que poder ser ejecutable como procesos independientes de la aplicación



### Links:

* [The Twelve-Factor App ](https://12factor.net/)

### Comentarios:

* **Diego Andres Fonseca Soto** (4) [436547](https://platzi.com/comentario/436547/) 

	Muy útil esta clase, normalmente pasamos muchos de estos factores por alto.

* **Edwin De Jesus Chiyopa Garcia** (2) [478347](https://platzi.com/comentario/478347/) 

	Tengo una aplicación desarrollada en php que ya esta en un ambiente productivo, me gustaría hacerla parte de un ambiente docker swarm, pero un desarrollo web en php requiere que este instalado apache, por lo tanto no cumple con el factor Port binding, hay alguna alternativa para esto?

	* **REINALDO ORJUELA GODOY** [478347] (2)

		chequea nginx.

	* **Guido Vilariño** [478347] (7)

		Lo que necesitas una imagen para tu aplicación basada en [httpd](https://hub.docker.com/_/httpd) (httpd es el nombre real del software que conoces como “Apache”).
		
		Puedes usar directamente esto para exponer tu aplicación en un swarm, pero para un entorno productivo lo mejor es que no expongas tus contenedores de aplicación directamente, sino que lo hagas a través de un reverse proxy como [traefik](https://traefik.io/) o [docker-flow-proxy](https://proxy.dockerflow.com/)

	* **david.quintanilla** [478347] (0)

		Te recomiendo nginx es muy fácil de configurar y la documentación es muy buena.

* **jorge-izaguirre** (1) [1068259](https://platzi.com/comentario/1068259/) 

	Muy buena data

* **carlosbazanhuaman** (1) [971742](https://platzi.com/comentario/971742/) 
no había tomado encuenta edtos detalles

* **Claudio Jesus Vázquez Villanueva** (1) [957605](https://platzi.com/comentario/957605/) 

	Estas clases si valen la pena.

* **angelszymczak** (1) [678046](https://platzi.com/comentario/678046/) 

	Master class

* **José Tuzinkievicz** (1) [527954](https://platzi.com/comentario/527954/) 

	Clase bestial.

* **mariogarcia_ar** (1) [508689](https://platzi.com/comentario/508689/) 

	Muy bueno, no lo conocía. <https://12factor.net/> esta la versión online

* **xergioalex** (1) [481402](https://platzi.com/comentario/481402/) 

	Muy interesante, siempre tengo en cuenta muchos de estos factores cuando hago CI && CD, pero nunca los había visto de una manera tan explicativa y estructurada.

* **Francisco Martin Nacimiento** (1) [79209](https://platzi.com/comentario/935743/) 
Tengo una duda, el primer factor de los 12 dice “Si hay múltiples bases de código, no es una aplicación, es un sistema distribuido.”. Me ...

	* **whereisanddy** [79209] (3)

		Lo que quiere decir es que si en tu contenedor va a haber varios proyectos (o microservicios), lo que deberías hacer es montar un contenedor por cada uno de ellos. Y que a través de swarm se comuniquen.

* **Edwin De Jesus Chiyopa Garcia** (1) [50321](https://platzi.com/comentario/478347/) 
Tengo una aplicación desarrollada en php que ya esta en un ambiente productivo, me gustaría hacerla parte de un ambiente docker swarm, pe...

	* **REINALDO ORJUELA GODOY** [50321] (2)

		chequea nginx.

# Primeros pasos [2985]

## 0060. Instalación de Docker [15777](https://platzi.com/clases/1434-docker-swarm/15777-instalacion-de-docker5689/)

### Descripción:


### Comentarios:

* **Edwin De Jesus Chiyopa Garcia** (1) [478364](https://platzi.com/comentario/478364/) 

	docker info me arroja WARNING: No swap limit support, como puedo solucionarlo?

	* **Edwin De Jesus Chiyopa Garcia** [478364] (1)

		y en que me afecta si se queda con el WARNING?

	* **marioflota** [478364] (1)

		  1. Inicie sesión en el host de Ubuntu o Debian como un usuario con privilegios sudo.
		
		  2. Edita el /etc/default/grubarchivo. Agregue o edite la GRUB_CMDLINE_LINUXlínea para agregar los siguientes dos pares clave-valor:
		
		
		
		
		GRUB_CMDLINE_LINUX="cgroup_enable=memory swapaccount=1"  
		3) Actualizar GRUB.
		
		$ sudo update-gru
		
		<https://docs.docker.com/install/linux/linux-postinstall/>

	* **ricardo-rod** [478364] (1)

		En realidad no te afecta en nada siempre y cuando no sea de procuccion. Hasta luego.

## 0070. Tu primer Docker Swarm [15403](https://platzi.com/clases/1434-docker-swarm/15403-tu-primer-docker-swarm/)

### Descripción:


### Links:

* [Manage swarm security with public key infrastructure (PKI) | Docker Documentation](https://docs.docker.com/engine/swarm/how-swarm-mode-works/pki/)

### Comentarios:

* **Diego Cruz** (6) [467177](https://platzi.com/comentario/467177/) 

	```
	    // Iniciar docker swarm
	    
	    docker swarm init
	    
	    // Obtener token para unir manager
	    
	    docker swarm join-token manager
	    
	    // Ver los nodos que tenemos
	    
	    docker nodels
	    
	    // Ver información del nodo
	    
	    docker nodeinspect self
	    
	    // Salir del modo swarm
	    
	```

	* **eguerrero1991** [467177] (1)

		```
		    //salir del modo swarm
		    docker swarm leave
		    //si un worker nodese va, dará error, podemos forzarlo.
		    docker swarm leave --force 
		    
		```

* **RoquilloGuri** (2) [703465](https://platzi.com/comentario/703465/) 

	docker swarm init  
	docker node ls  
	docker node inspect self  
	docker node inspect --pretty self  
	docker swarm leave  
	docker swarm leave --force

* **Claudio Andres González Pino** (2) [437077](https://platzi.com/comentario/437077/) 

	Probable error:  
	`docker swarm init`  
	Error response from daemon: could not choose an IP address to advertise since this system has multiple addresses on interface wlp8s0 (::15c8:7991:b99f:9c71 and ::ae3d:603b:de2f:1d18) - specify one with --advertise-addr
	
	Solucion:  
	`docker swarm init --advertise-addr tu-ip`

	* **eguerrero1991** [437077] (1)

		Muchas gracias!

* **wilantury** (1) [1063813](https://platzi.com/comentario/1063813/) 

	* Swarm no es un paquete aparte de docker, swarm es nativo.
	* Docker swarm init : inicia un nodo manager.
	* Debe existir como mínimo un manager para que exista swarm.
	* docker swarm join-token manager
	* docker node ls : muestra los nodos disponibles
	* Toda la comunicación entre nodos está encriptada usando certificados TLS.
	* docker node inspect --pretty self: inspecciona el nodo
	* docker swarm leave --force: cierra el modo swarm, regresa a docker normal.
	
	

* **Henry_Coarite** (1) [765402](https://platzi.com/comentario/765402/) 

	Y si quiero conectar contenedores que se encuentren en distintos servidores fisicos, como lo hago?

* **frestrepo** (1) [441818](https://platzi.com/comentario/441818/) 

	Tengo una inconsistencia cuando agrego un nodo. Resulta que los nodos estan en diferentes subredes entonces cuando inicializo el manager me da la ip de mi equipo que seria 192.168.40.71 y el nodo worker esta en una subred 192.168.0.0 entonces cuando le hago el join no me queda registrado con la ip de la maquina (192.168.0.57) si no con la ip de la puerta de enlace 192.168.200.100 como puedo cambiar esta ip?

	* **Guido Vilariño** [441818] (2)

		Aquí hay una [pregunta de StackOverflow](https://stackoverflow.com/questions/47377313/docker-swarm-join-a-docker-swarm-from-another-subnet) que responde específicamente qué requerimientos existen para joinear nodos entre distintas subnets.

* **Claudio Andres González Pino** (1) [437078](https://platzi.com/comentario/437078/) 

	Por favor agregar los comandos que aparecen en el video.

	* **YuyiCC** [437078] (1)

		```
		    ##Docker Swarm
		    docker swarm init	## Iniciar docker swarm
		    docker swarm join-token manager	## Obtener token para unir manager
		    docker nodels	  ## Ver los nodos que tenemos
		    docker nodeinspect self	 ## Ver información del nodo
		    docker swarm leave --force  ## Salir del modo swarm
		    
		    
		```

* **John David Gómez Huertas** (1) [85367](https://platzi.com/comentario/1072542/) 
La idea es que se permita una alta disponibilidad pero si el docker swarm administrador se cae o falla… se puede hacer un cluster de admi...

* **frestrepo** (1) [47358](https://platzi.com/comentario/441818/) 
Tengo una inconsistencia cuando agrego un nodo. Resulta que los nodos estan en diferentes subredes entonces cuando inicializo el manager ...

	* **Guido Vilariño** [47358] (2)

		Aquí hay una [pregunta de StackOverflow](https://stackoverflow.com/questions/47377313/docker-swarm-join-a-docker-swarm-from-another-subnet) que responde específicamente qué requerimientos existen para joinear nodos entre distintas subnets.

## 0080. Fundamentos de Docker Swarm servicios [15402](https://platzi.com/clases/1434-docker-swarm/15402-fundamentos-de-docker-swarm-servicios/)

### Descripción:


### Comentarios:

* **Walter Chacón** (4) [494753](https://platzi.com/comentario/494753/) 

	Hola Guido,
	
	Tengo corriendo docker swarm para unos microservices en mi trabajo, tenemos un CI para hacer constantemente deploys al docker swarm. La cuestión es que el server cada día va consumiendo mas disco duro y es porque las imágenes de docker se van acumulando. La solución que hice fue crear un cron job que lo que hace es que todos los días hace un `docker system prune -f` para eliminar todas las imágenes que ya no están en uso.
	
	Cual seria una buena practica para esto ?

	* **ManuelSLemos** [494753] (3)

		No, por que de esa manera te quedas sin backups el sistema del rollback.
		
		Tendrias que versionar la aplicacion y guardar solo las imagenes de dichas versiones (testeadas por supuesto).

	* **Guido Vilariño** [494753] (8)

		En swarm siempre tienes que tener algún mecanismo de mantenimiento y limpieza. Yo uso [meltwater/docker-cleanup](https://hub.docker.com/r/meltwater/docker-cleanup) corriendo como un servicio global de Swarm, lo que me garantiza que corre en todos los nodos, y delego en él la tarea de limpiar todo. Lo hago así:
		``` 
		    docker service create \
		      --detach \
		      -e CLEAN_PERIOD=900 \
		      -e DELAY_TIME=600 \
		      --log-driver json-file \
		      --log-opt max-size=1m \
		      --log-opt max-file=2 \
		      --name cleanup \
		      --mode global \
		      --mount type=bind,source=/var/run/docker.sock,target=/var/run/docker.sock \
		      meltwater/docker-cleanup
		    
		```
		
		Puedes aprender más de esta imagen leyendo su página en docker hub

* **Edwin De Jesus Chiyopa Garcia** (3) [478449](https://platzi.com/comentario/478449/) 

	// Crear Servicio con el nombre pinger, realizando un ping a [google.com](http://google.com)  
	docker service create --name pinger alpine ping [www.google.com](http://www.google.com)  
	// lista los servicios  
	docker service ls

* **Ariel_Ayala** (2) [541658](https://platzi.com/comentario/541658/) 

	 **En swarm no se corren contenedores manualmente, se declaran los servicios que se desean correr.**

* **wilantury** (1) [1063853](https://platzi.com/comentario/1063853/) 

	* docker swarm init  
	l- inux alpine: muy pequeño orientado a seguridad. Se usa mucho en docker como base de imágenes.
	* docker service create --name pinger alpine ping [www.google.com](http://www.google.com)
	
	

* **wilantury** (1) [1063835](https://platzi.com/comentario/1063835/) 

	alpine linux: <https://alpinelinux.org/>

* **k7code** (1) [1000772](https://platzi.com/comentario/1000772/) 

	Alpine es una imagen de linux que es muy liviana orientado a seguridad. Se utiliza mucho como base para diferentes contenedores.

* **ManuelMonpa** (1) [839068](https://platzi.com/comentario/839068/) 

	Las tareas de un servicio puede escalar automaticamente ?, de manera que se pueden ajustar a mi demanda dependiendo de los nodos que añado al cluster de docker swarm

* **ltorres1987** (1) [503854](https://platzi.com/comentario/503854/) 

	Excelente

* **Walter Chacón** (1) [51691](https://platzi.com/comentario/494753/) 
Hola Guido, Tengo corriendo docker swarm para unos microservices en mi trabajo, tenemos un CI para hacer constantemente deploys al docker...

	* **ManuelSLemos** [51691] (3)

		No, por que de esa manera te quedas sin backups el sistema del rollback.
		
		Tendrias que versionar la aplicacion y guardar solo las imagenes de dichas versiones (testeadas por supuesto).

## 0090. Entendiendo el ciclo de vida de un servicio [15405](https://platzi.com/clases/1434-docker-swarm/15405-entendiendo-el-ciclo-de-vida-de-un-servicio/)

### Descripción:


Desde el **Cliente** , ‘docker service create’ le envía al **Nodo Manager** el servicio: se crea, se verifican cuántas tareas tendrá, se le otorga una IP virtual y asigna tareas a nodos; esta información es recibida por el **Nodo Worker** , quien prepara la tarea y luego ejecuta los contenedores.

### Links:

* [How services work | Docker Documentation](https://docs.docker.com/engine/swarm/how-swarm-mode-works/services/)

### Comentarios:

* **lantog** (7) [621043](https://platzi.com/comentario/621043/) 

	El ciclo de vida es muy parecido a el ciclo de ir a un restaurante.
	
	Usas la API de docker swarm para hablar con el orquestor, vas hacía donde esta la persona que toma las ordenes y le decis lo que queres.
	
	La persona toma tu pedido y crea la orden (el orquestor crea el servicio).
	
	Se tienen un monton de ordenes en el restaurante, y posiblemente en algún momento vamos a querer saber como esta la preparación de tu orden, asi que le asignamos un ID a tu orden asi podemos ir ‘chequeando’ como esta en el futuro (el orquestor le asigna una IP a tu servicio).
	
	Hay que empezar a hacer lo que se pidio en la orden así que vamos a ver que cocinero (que nodo) esta disponible para trabajar, buscamos uno adecuado que pueda realizar lo que requiere nuestra orden y le damos la tarea (según cuanta cpu/memoria/necesidad de comunicación, él orquestor decide a que nodo darle el servicio)
	
	El cocinero empieza a realizar la orden, si queremos saber como esta la orden, podemos verlo por que la orden tiene un ID, así que me puedo referir a esa orden de una forma única entre todas las otras ordenes que se estan haciendo en el restaurante
	
	No necesitamos saber como el cocinero esta haciendo nuestra orden, si esta haciendo este o otro tipo de corte, estamos totalmente abstraídos de eso, de la misma forma que nosotros no vemos a los cocineros por que los maneja la persona que se encarga de las ordenes, nosotros ya no vemos los contenedores por que eso ahora es tarea de el/los orquestor(es) de swarm

	* **jas486** [621043] (1)

		explicación nivel dios

	* **k7code** [621043] (1)

		Compañero muchas gracias por el ejemplo.

	* **Felipe Jurado Murillo** [621043] (1)

		Excelente la explicación, muchas gracias!!!

* **Diego Cruz** (5) [468701](https://platzi.com/comentario/468701/) 

	```
	    // Ver estado de un servicio
	    docker service ps nombreServicio
	    
	    // Ver información de un servicio
	    docker service inspect nombreServicio
	    
	    // Ver logs
	    docker service logs -f nombreServicio
	    
	    // Eliminar servicio
	    docker service rm nombreServicio
	    
	```

* **Francisco Martin Nacimiento** (2) [960239](https://platzi.com/comentario/960239/) 

	Un servicio es como una descripción de algo que se tiene que llevar a cabo, ahora esta descripción nos dice qué se quiere hacer, pero recordemos que se puede escalar los servicios, entonces podemos llevar el servicio en marcha según la escalabilidad que le demos, entonces le estaríamos diciendo al nodo manager “che quiero 5 nodos haciendo esto” entonces el nodo manager realiza su planificación, y en su planificación están 5 tareas de determinado servicio, las cuales asigna a los nodos workers.  
	Entonces tenes identificadores (IDs) para:
	
	* Identificar servicios, es decir la descripción de lo que se tiene que llevar a cabo.
	* Identificar los servicios en ejecución (tareas).
	* Identificar los contenedores en los cuales las tareas se están llevando a cabo.
	
	
	
	Según entiendo sobre el tema los IDs en Swarm.

* **Ariel_Ayala** (2) [542441](https://platzi.com/comentario/542441/) 

	 **Ejecución de servicios en docker**  
	Lo que docker usar para ejecutar servicios es sistema o un enfoque llamado **scheduling **o **planificación**.
	
	Los **managers **planifican en que nodo van a ejecutarse los contenedores de los servicios, para eso le asigna tarea a los nodos.

* **wilantury** (1) [1063927](https://platzi.com/comentario/1063927/) 

	* docker service ps self pinger : muestra las tareas (task)
	* <https://docs.docker.com/engine/swarm/how-swarm-mode-works/services/>
	* Es bueno enviar al standard output la data necesaria para mostrar en logs el funcionamiento de la app.
	
	

* **Ariel_Ayala** (1) [542442](https://platzi.com/comentario/542442/) 

	Las **tareas** son templates que el **manager** le envía a los **nodos worker** para que puedan construir los contenedores de esa tarea.

## 0100. Un playground de docker swarm gratuito play-with-docker [15404](https://platzi.com/clases/1434-docker-swarm/15404-un-playground-de-docker-swarm-gratuito-play-with-d/)

### Descripción:


¡Play with docker es una herramienta de otro mundo! Te permitirá colaborar entre distintos usuarios en una mismas sesión de docker, y lo mejor, ¡puedes incluir tu propia terminal!

### Links:

* [Play with Docker](https://labs.play-with-docker.com/)

### Comentarios:

* **Juan Emmanuel Díaz** (2) [525827](https://platzi.com/comentario/525827/) 

	Muy buen desarrollo lo de PWD. Excelente

* **ernesto** (2) [436579](https://platzi.com/comentario/436579/) 

	Guau , es magia, genial 😃

* **jandrey** (1) [556676](https://platzi.com/comentario/556676/) 

	Muy buena esa herramienta ❤️

* **giulianaqr** (1) [479609](https://platzi.com/comentario/479609/) 

	Me sale el siguiente error cuando intento conectarme a través de ssh **Permission denied (publickey)**. Y eso que he pegado tal cual está en la caja de texto de mi nodo.

	* **Guido Vilariño** [479609] (1)

		Es posible que haya algún error temporal en PWD. A veces pasa: es un entorno gratuito y no pensado para cargas productivas que puede fallar. Intenta con una nueva sesión de PWD o en unos días

* **Edwin De Jesus Chiyopa Garcia** (1) [478512](https://platzi.com/comentario/478512/) 

	Increible!!

* **Diego Andres Fonseca Soto** (1) [437443](https://platzi.com/comentario/437443/) 

	Wow, simplemente genial

* **giulianaqr** (1) [50421](https://platzi.com/comentario/479609/) 
Me sale el siguiente error cuando intento conectarme a través de ssh Permission denied (publickey). Y eso que he pegado ...

	* **Guido Vilariño** [50421] (1)

		Es posible que haya algún error temporal en PWD. A veces pasa: es un entorno gratuito y no pensado para cargas productivas que puede fallar. Intenta con una nueva sesión de PWD o en unos días

## 0110. Docker Swarm multinodo [15406](https://platzi.com/clases/1434-docker-swarm/15406-docker-swarm-multinodo/)

### Descripción:


### Comentarios:

* **Edwin De Jesus Chiyopa Garcia** (4) [478526](https://platzi.com/comentario/478526/) 

	// iniciar docker swarm  
	docker swarm init  
	// iniciar docker swarm en caso de tener mas de una interfaz de red  
	docker swarm init --advertise-addr [“ip de la interfaz donde va a escuchar peticiones para unirse al swarm”]  
	// ver nodos del swarm *solo se puede visualizar desde un docker swarm manager  
	// Todo lo relativo al estado del swarm, a la administracion del swarm y todo lo que tiene que ver con el swarm en si lo van a manejar exclusivamente los managers  
	docker node ls

* **nicobytes** (2) [582499](https://platzi.com/comentario/582499/) 

	Hola! estoy intentado unir una maquina a docker swarm pero me da un error. Con maquinas de DO.
	``` 
	    docker swarm join --token SWMTKN-1-2l43xegaq2gchqr2e…. ip:2377
	    Error response from daemon: Timeout was reached before node joined. The attempt to join the swarm will continue inthe background. Use the"docker info"commandtoseethecurrentswarmstatusofyournode.
	    
	```
	
	He estado mirando y es porque entre maquinas deben tener unos puertos abiertos. <https://docs.docker.com/engine/swarm/swarm-tutorial/#open-protocols-and-ports-between-the-hosts>  
	Como puedo habilitar estos puertos?

	* **ebar0n (Platzi)** [582499] (1)

		Hola, una pregunta, en la máquina que intentas conectar ya estás ejecutando el nodo?
		
		porque eso expone los puertos.

	* **nicobytes** [582499] (1)

		Hola @ebar0n no estoy ejecutando ningún nodo aun por que precisamente necesito unir este nodo al cluster swarm. Y el comando es el que deje anteriormente. Lo que se me ocurre según la doc es que debo habillitar los puertos manualmente que docker necesita para conectarse con la otra maquina que tiene el nodo manager.

	* **Guido Vilariño** [582499] (1)

		El mensaje `Timeout was reached before node joined` es claro: el nodo que quiere unirse al swam no recibió respuesta en un tiempo prudencial y abortó la petición.
		
		Esto lo que indica es que el nodo que quiere unirse no puede llegar al manager al que le estás intentando pegar. Evidentemente hay un problema de networking. Te diría que comiences haciendo un `ping` desde el nodo candidato hasta el swarm manager y sigas a partir de ahí. Si estás corriendo en un entorno con esquemas de seguridad de red, probablemente tengas que abrir algunos puertos

* **wilantury** (1) [1064043](https://platzi.com/comentario/1064043/) 

	Los nodos manager son los únicos que pueden hacer tareas relacionadas con el estado y la administración de swarm. Ésto por seguridad.

* **k7code** (1) [1002139](https://platzi.com/comentario/1002139/) 

	 **Por defecto las tareas son asignadas a cualquier nodo del swarm, para que no pase esto, hay que especificar en que nodos debe de correr el servicio.**

* **carlosbazanhuaman** (1) [984657](https://platzi.com/comentario/984657/) 

	un comando simple y tienes tu servicio corriendo, muy buena herramienta.

* **ricardo-rod** (1) [686195](https://platzi.com/comentario/686195/) 

	Que bien el play-with-docker ya yo tenia 4 vm con fedora en VMware para kubernetes local, pero con esto los puedo dejar dormidos, lo siento, no tengo soporte para acentos muy vago para buscarlo en fedora.

* **Edwin De Jesus Chiyopa Garcia** (1) [489380](https://platzi.com/comentario/489380/) 

	Las instancias que agregas desde playwithdocker, en un esquema de productividad son maquina físicas?

	* **Guido Vilariño** [489380] (4)

		La realidad es que Play-with-docker es un sandbox; no un sistema que está pensado para cargas productivas. Es una plataforma para que puedas probar cosas sobre docker o sobre swarm sin necesitar contar con máquinas físicas reales (que siempre tienen costo), de manera gratuita.
		
		Si quieres saber cómo funciona PWD internamente, la respuesta es que las “máquinas” que usas en PWD son en verdad contenedores, y detrás de ellas hay un esquema de networking que hace que se comporten entre sí como si realmente fueran máquinas reales, pero nunca tienes que usarlas como un entorno productivo.

* **nicobytes** (1) [58836](https://platzi.com/comentario/582499/) 
Hola! estoy intentado unir una maquina a docker swarm pero me da un error. Con maquinas de DO. docker swarm join --token SWMTKN-1-2...

	* **ebar0n (Platzi)** [58836] (1)

		Hola, una pregunta, en la máquina que intentas conectar ya estás ejecutando el nodo?
		
		porque eso expone los puertos.

* **Edwin De Jesus Chiyopa Garcia** (1) [51278](https://platzi.com/comentario/489380/) 
Las instancias que agregas desde playwithdocker, en un esquema de productividad son maquina físicas?

	* **Guido Vilariño** [51278] (4)

		La realidad es que Play-with-docker es un sandbox; no un sistema que está pensado para cargas productivas. Es una plataforma para que puedas probar cosas sobre docker o sobre swarm sin necesitar contar con máquinas físicas reales (que siempre tienen costo), de manera gratuita.
		
		Si quieres saber cómo funciona PWD internamente, la respuesta es que las “máquinas” que usas en PWD son en verdad contenedores, y detrás de ellas hay un esquema de networking que hace que se comporten entre sí como si realmente fueran máquinas reales, pero nunca tienes que usarlas como un entorno productivo.

# Administrando Servicios [2986]

## 0120. Administrando servicios en escala [15407](https://platzi.com/clases/1434-docker-swarm/15407-administrando-servicios-en-escala/)

### Descripción:


### Comentarios:

* **estuardoramos** (10) [697568](https://platzi.com/comentario/697568/) 

	Comandos de la clase, con el ejemplo del servicio pinger
	``` 
	    # Cambia el numero de tareas
	    docker service scale pinger=5
	    
	    # Ver las tareas del servicio
	    docker service ps pinger
	    
	    # Ver los logs del servicio
	    docker service logs -f pinger
	    
	    # Ver la configuración del servicio
	    docker service inspect pinger
	    
	    # actualizar alguna configuración del servicio
	    docker service update --args "ping www.amazon.com" pinger
	    
	    # realiza rollback o cambia al spec anterior 
	    docker service rollback pinger
	    
	```

* **Ariel_Ayala** (7) [543730](https://platzi.com/comentario/543730/) 

	Docker swarm, cuando hace un **update** del servicio, guarda el contenido de la configuración anterior. Si hay un problema podemos hacer un **rollback** y volver a la configuración anterior. Se guarda en el entry “ **PreviousSpec** ”.
	``` 
	    docker service inspect [nombre_servicio]
	    
	```
	
	para ver el entry mencionado.

* **Albert González Rossell** (2) [753096](https://platzi.com/comentario/753096/) 

	genial lo del “docker service rolleback”!!

* **wilantury** (1) [1064114](https://platzi.com/comentario/1064114/) 

	docker service scale pinger=5 : escala y replica mi servicio

* **k7code** (1) [1002219](https://platzi.com/comentario/1002219/) 

	 **Docker esta configurado por defecto para actualizar las tareas de los servicios una por una, de esa manera se garantiza que siempre este disponible.**

* **carlosbazanhuaman** (1) [984678](https://platzi.com/comentario/984678/) 

	el rollback me encanto jajajaja

* **jhonsfran90** (1) [532921](https://platzi.com/comentario/532921/) 

	Excelente! muy útil para mantener alta disponibilidad. <https://labs.play-with-docker.com/> es una locura.

* **RoquilloGuri** (0) [703671](https://platzi.com/comentario/703671/) 

	bien

## 0130. Controlando el despliegue de servicios [15409](https://platzi.com/clases/1434-docker-swarm/15409-controlando-el-despliegue-de-servicios/)

### Descripción:


### Comentarios:

* **estuardoramos** (4) [697616](https://platzi.com/comentario/697616/) 

	Comandos usados en la clase con el servicio ejemplo pinger
	``` 
	    # Actualizar las replicas de un servicio
	    docker service update --replicas=20 pinger
	    
	    # Actualizar paralelismo y orden dela configuracióndeupdateen el servicio pinger
	    docker service update --update-parallelism 4 --update-order start-first pinger
	    
	    # Actualizar accion en fallo y radio maximo de falla dela configuracióndeupdateen el servicio pinger
	    docker service update --update-failure-action rollback --update-max-failure-ratio 0.5 pinger
	    
	    # Actualizar paralelismo dela configuracion de rollback en el servicio de pinger
	    docker service update --rollback-parallelism 0 pinger
	    
	```

* **Ariel_Ayala** (2) [543733](https://platzi.com/comentario/543733/) 

	En el entry **“UpdateConfig”** se puede ver como está configurado el servicio para comportarse cuando tiene que hacer un **update** y cuando tiene que rotar sus tareas.
	``` 
	    "UpdateConfig": {
	                    "Parallelism": 1,
	                    "FailureAction": "pause",
	                    "Monitor": 5000000000,
	                    "MaxFailureRatio": 0,
	                    "Order": "stop-first"
	                }
	    
	```

* **wilantury** (1) [1064579](https://platzi.com/comentario/1064579/) 

	* Podemos configurar la forma de actuar cuando falle una actualización, podemos indicar que se pause, siga adelante o haga un rollback.
	
	

* **morwen1** (1) [831888](https://platzi.com/comentario/831888/) 

	que cosa mas poderosa alfin estoy trabajando en un cluster , algo que siempre eh querido hacer!!

* **emanuel-alejandro-mamani** (1) [705477](https://platzi.com/comentario/705477/) 

	tengo una duda, habias puesto de ejemplo real de si el servidor normalmente tarda 5 segundos en arrancar y detecta que ya pasó ese tiempo entonces se produce el error y swarm automaticamente hace el rollback, ahora bien como hacemos para que swarm haga esto mismo pero con errores de codigo que no afectan de manera directa como por ej: dar un error 500 o tirar el server abajo, si no que daña el flujo interno al solo ser error de codigo, te doy un ejemplo, no poder conectarse a mysql desde php, hay maneras de hacer un catch de ese tipo de errores y asi podemos tambien hacer que swarm se adapte a nuestro contexto de errores?

	* **Anthony Farias** [705477] (1)

		Creo que no hay forma, pero igual eso que dices está muy mal hecho. Para eso tienes que tener ambientes de prueba donde antes de deployar en produccion tienes que testear tu codigo, y para eso mismo tambien es docker, una vez testeas el codigo, y corras la imagen, esa misma te va a servir en produccion, porque las imagenes de docker corren en cualquier parte sin problemas, entonces a produccion deberia ser muy dificil que llegue un bug de ese estilo.

* **Johan Steven Arias** (1) [69459](https://platzi.com/comentario/757600/) 
Cual es la diferencia entre utilizar el comando service update --replicas=<num_replicas> <service_name> y el com...

	* **Guido Vilariño** [69459] (1)

		Son comandos equivalentes, `service scale` es implemente un atajo para `service update --replicas`.
		
		Esto mismo está explicado en la [documentación de referencia del comando](https://docs.docker.com/engine/reference/commandline/service_scale/)

## 0140. Exponiendo aplicaciones al mundo exterior [15408](https://platzi.com/clases/1434-docker-swarm/15408-exponiendo-aplicaciones-al-mundo-exterior/)

### Descripción:


### Links:

* [Page not found · GitHub](https://github.com/platzi/swarm)

### Comentarios:

* **Diego Andres Fonseca Soto** (2) [437476](https://platzi.com/comentario/437476/) 

	Les dejo el comando para lanzar la aplicación
	``` 
	    dockerservicecreate-d--nameapp--publish3000:3000--replicas=3gvilarino/swarm-hostname
	    
	```

* **Angel Alexi Guerra Miketta** (1) [587252](https://platzi.com/comentario/587252/) 

	Tengo una duda tengo 3 maquinas virtuales magager(192.168.10.1), worker1(192.168.10.2), worker2(192.168.10…3)
	
	Cuando creo el servicio con replica=2 se desplienta en el manager y el worker2
	
	Si hago curl al manager “curl <http://192.168.10.1:3000>” y al worker2 curl <http://192.168.10.1:3000> todo funciona normalmente, pero cuando hago lo mismo al worker1 presento el siguiente error  
	curl: (7) couldn’t connect to host
	
	Me pueden decir que estoy haciendo mal.

	* **Angel Alexi Guerra Miketta** [587252] (1)

		Al parecer el problema era con los puertos que estaban cerrados.

	* **Angel Alexi Guerra Miketta** [587252] (1)

		TCP port 2377 for cluster management communications  
		TCP and UDP port 7946 for communication among nodes  
		UDP port 4789 for overlay network traffic

* **Diego Cruz** (1) [470786](https://platzi.com/comentario/470786/) 

	Una consulta , por que al actualizar el navegador no cambia el hostname , pero al realizarlo con curl si cambia en cada petición ?

	* **Diego Alexander Forero Higuera (Platzi)** [470786] (2)

		Si haces la petición al cluster de swarm siempre va a distribuir el tráfico enviando la petición al nodo que este con menos carga para atender la petición. En la clase el profesor solo hizo la prueba desde curl es probable que desde el navegador siempre entre al mismo contenedor porque no tiene necesidad de cambiar ya que no tiene carga.

	* **Diego Cruz** [470786] (1)

		Entendido, Muchas gracias por la aclaración

	* **Francisco Javier Seguel Arriagada** [470786] (1)
Lo que necesitas es definir un sticky session http://www.littlebigextra.com/how-to-maintain-session-persistence-sticky-session-in-docker-swarm-with-multiple-containers/

* **ernesto** (1) [436603](https://platzi.com/comentario/436603/) 

	El link parece no ser el correcto

	* **Yesica Lizeth Cortés Pineda (Platzi)** [436603] (4)

		Hola! ya hicimos el ajuste al repo para que sea público y puedas usarlo.

	* **ernesto** [436603] (1)

		Genial , gracias!

* **Angel Alexi Guerra Miketta** (1) [59124](https://platzi.com/comentario/587252/) 
Tengo una duda tengo 3 maquinas virtuales magager(192.168.10.1), worker1(192.168.10.2), worker2(192.168.10…3) Cuando creo el servicio co...

	* **Angel Alexi Guerra Miketta** [59124] (1)

		Al parecer el problema era con los puertos que estaban cerrados.

* **Diego Cruz** (1) [49698](https://platzi.com/comentario/470786/) 
Una consulta , por que al actualizar el navegador no cambia el hostname , pero al realizarlo con curl si cambia en cada petición ?

	* **Diego Alexander Forero Higuera (Platzi)** [49698] (2)

		Si haces la petición al cluster de swarm siempre va a distribuir el tráfico enviando la petición al nodo que este con menos carga para atender la petición. En la clase el profesor solo hizo la prueba desde curl es probable que desde el navegador siempre entre al mismo contenedor porque no tiene necesidad de cambiar ya que no tiene carga.

# Swarm avanzado [2987]

## 0150. El Routing Mesh [15410](https://platzi.com/clases/1434-docker-swarm/15410-el-routing-mesh/)

### Descripción:


 **Routing Mesh** nos ayuda a que, teniendo un servicio escalado en swarm que tiene mas nodos que servicios y esos servicios están expuestos en un puerto; cuando hacemos un request a un servicio en ese puerto de alguna manera la petición llega y no se pierden en algún nodo que no puede contenerlo en ese puerto o en un contenedor.

_Routing Mesh ayuda a llevar la petición y que esta no se pierda si la cantidad de los contenedores es diferente a la cantidad de nodos._

### Links:

* [Use swarm mode routing mesh | Docker Documentation](https://docs.docker.com/engine/swarm/ingress/)

### Comentarios:

* **wilantury** (1) [1066739](https://platzi.com/comentario/1066739/) 

	-Routing mesh habilita cada nodo de swarm para aceptar conexiones en puertos publicados para cualquier servicio corriendo en swarm, incluso si no hay tareas corriendo en el nodo.
	
	* Routing mesh rutea todos los requests en lo puertos publicados en los nodos disponibles en un contenedor activo.
	
	

* **k7code** (1) [1004439](https://platzi.com/comentario/1004439/) 

	No se puede tener mas de un servicio escuchando en el mismo puerto, pero si es posible tener múltiples tareas del mismo servicio compartiendo el puerto.

## 0160. Restricciones de despliegue [15411](https://platzi.com/clases/1434-docker-swarm/15411-restricciones-de-despliegue/)

### Descripción:


### Comentarios:

* **Daniel Moreno** (7) [500001](https://platzi.com/comentario/500001/) 

	```
	    docker service create -d --name viz -p 8080:8080 --constraint=node.role==manager --mount=type=bind,src=/var/run/docker.sock,dst=/var/run/docker.sock dockersamples/visualizer
	    
	```

* **Daniel Moreno** (6) [500018](https://platzi.com/comentario/500018/) 

	Comando para reubicar los servicios para que sean ejecutados solo en los workers
	``` 
	    docker service update --constraint-add node.role==worker --update-parallelism=0 app
	    
	```
	
	donde:  
	–constraint-add node.role => indica el tipo de nodo donde quiero reubicar  
	–update-parallelism=0 => indica que se harán todos en simultaneo

* **wilantury** (1) [1066813](https://platzi.com/comentario/1066813/) 

	```
	    docker service create -d --name viz -p 8080:8080 --constraint=node.role==manager --mount=type=bind,src=/var/run/docker.sock,dst=/var/run/docker.sock dockersamples/visualizer
	    
	    docker service update --constraint-add node.role==worker --update-parallelism=0 app```
	    
	```

* **Rodrigo Hernan Flores Torres** (0) [559974](https://platzi.com/comentario/559974/) 
?

## 0170. Disponibilidad de nodos [15412](https://platzi.com/clases/1434-docker-swarm/15412-disponibilidad-de-nodos/)

### Descripción:


En el visualizer podemos ver que todas las tareas siguen corriendo en el "“worker 1"”, esto sucede porque el planificador de **Docker Swarm** no va a replanificar o redistribuir la carga de un servicio o de contenedores a menos que tenga que hacerlo; para solucionar esto, debemos forzar un redeployment o una actualización que se logra cambiando el valor de una variable que no sirva para nada.
``` 
    docker service update -d --env-add UNA_VARIABLE=de-entorno --update-parallelism=0 app
    
    docker service ps app
    
```

### Comentarios:

* **fredyramosp** (1) [923724](https://platzi.com/comentario/923724/) 

	Eliminar containers
	``` 
	    docker service rmapp
	    
	```

* **fredyramosp** (1) [923720](https://platzi.com/comentario/923720/) 

	```
	    docker node update --availability drain workder2
	    docker node update --availability active workder2
	    # Actualizar alguna variable de entorno para forzar la redistribuciónde contenedores
	    docker service update -d --env-add UNA_VARIABLE=de-entorno app
	    
	```

* **Edwin De Jesus Chiyopa Garcia** (1) [481895](https://platzi.com/comentario/481895/) 

	Porque no se debería aplicar lo de parallelism en un entorno productivo?

	* **jlazo** [481895] (2)

		Producirías downtime de tu aplicación

	* **Edwin De Jesus Chiyopa Garcia** [481895] (2)

		Gracias por la respuesta jonatan-lazo, probablemente no formulé bien mi pregunta, debido a que en el video Guido ya da de respuesta lo del dowtime, pero mi duda esta mas ligada a que se debe que el parallelismo crea el downtime, porque lo produce.

	* **jlazo** [481895] (3)

		Él se refiere a que no debes de aplicar paralelismo 0, porque quedarían inoperativas todas tus instancias, sin embargo puedes aplicar paralelismo mayores a 0, eso aseguraría que siempre tengas una instancia disponible, mientras las demás sufren la actualización que requieres  
		Recuerda que al tu indicar paralelismo 0, le estas diciendo al daemon que afecte simultáneamente la actualización a las instancias, produciendo así el downtime, por eso es que no debe de hacerse en ambientes productivos

* **Edwin De Jesus Chiyopa Garcia** (1) [50638](https://platzi.com/comentario/481895/) 
Porque no se debería aplicar lo de parallelism en un entorno productivo?

	* **jlazo** [50638] (2)

		Producirías downtime de tu aplicación

## 0180. Networking y service discovery [15413](https://platzi.com/clases/1434-docker-swarm/15413-networking-y-service-discovery/)

### Descripción:
vamos a ver como es el networking al momento de trabajar con swarm, vamos a poder inspeccionar que tenemos en la red. Todo esto, utilizando el repositorio que encuentras en los enlaces del curso

### Links:

* [Use overlay networks | Docker Documentation](https://docs.docker.com/network/overlay/)

### Comentarios:

* **frestrepo** (6) [436626](https://platzi.com/comentario/436626/) 

	En caso de una base de datos productiva en donde debería estar y como se haría la conexión, todas las instancias conectadas a la misma base de datos?

	* **Guido Vilariño** [436626] (6)

		Eso va a depender enteramente de la base de datos que estés usando, dado que todas son distintas en términos de cómo manejan replicación, redundancia, etc. Por lo general, una base de datos de alta disponibilidad no suele correrse en un esquema de clustering de contenedores con auto-scheduling como Swarm, Kubernetes, etc, pero si quieres hacerlo, una forma es usar un plugin de storage que permita utilizar filesystem remotos como volúmenes de docker y usar esos volúmenes en tus servicios de datos.
		
		Hay distintos plugins; si usas AWS puedes usar [Cloudstor](https://docs.docker.com/docker-for-aws/persistent-data-volumes/), o uno de los más populares open source para cualquier tipo de setup que es [Rexray](https://rexray.io/)

	* **Diego Andres Fonseca Soto** [436626] (1)

		Tengo la misma duda

	* **Edwin De Jesus Chiyopa Garcia** [436626] (2)

		Tengo la misma duda, donde debería estar una base de datos productiva?.

* **frestrepo** (2) [46898](https://platzi.com/comentario/436626/) 
En caso de una base de datos productiva en donde debería estar y como se haría la conexión, todas las instancias conectadas a la misma ba...

	* **Guido Vilariño** [46898] (6)

		Eso va a depender enteramente de la base de datos que estés usando, dado que todas son distintas en términos de cómo manejan replicación, redundancia, etc. Por lo general, una base de datos de alta disponibilidad no suele correrse en un esquema de clustering de contenedores con auto-scheduling como Swarm, Kubernetes, etc, pero si quieres hacerlo, una forma es usar un plugin de storage que permita utilizar filesystem remotos como volúmenes de docker y usar esos volúmenes en tus servicios de datos.
		
		Hay distintos plugins; si usas AWS puedes usar [Cloudstor](https://docs.docker.com/docker-for-aws/persistent-data-volumes/), o uno de los más populares open source para cualquier tipo de setup que es [Rexray](https://rexray.io/)

* **wilantury** (1) [1067045](https://platzi.com/comentario/1067045/) 

	La red overlay crea una red distribuida entre múltiples Docker daemon hosts. Esta red se ubica en la parte superior(overlay) de las redes de un host , permitiendo que los contenedores se conecten a ese host(incluyendo containers con servicios swarm). Docker maneja transparentemente el ruteo de cada paquete hacia y desde el correcto Docker daemon host y el correcto contenedor de destino.

* **wilantury** (1) [1066872](https://platzi.com/comentario/1066872/) 

	<https://docs.docker.com/network/overlay/>

* **fredyramosp** (1) [923733](https://platzi.com/comentario/923733/) 

	Crear una red
	``` 
	    docker network create--driver overlay app-net
	    
	```

* **nicobytes** (1) [567170](https://platzi.com/comentario/567170/) 

	Genial curso, tengo una pregunta en caso de una base de datos productiva, tienes algún recurso, ejemplo o documentación para ver como conectaría la base de datos al cluster de docker swarm?
	
	Se que depende del tipo de la base de datos pero entiendo que para poner comunicar un servicio con otro se debe tener un network overlay en el cluster… en caso de que la base de datos no corra dentro del cluster como se conectaría?

	* **ManuelMonpa** [567170] (2)

		En este caso vas a tener tu db corriendo en otro lado, ya sea en otra maquina o en servicio de cloud en la nube como por ejemplo, “Amazon RDS”. Esto tendrá su host para conectar a la base de datos, credenciales, port, etc.  
		Ahora, lo que cambiaria seria la variable de entorno MONGO_URL, por la url de tu base de datos productiva.

* **jandrey** (1) [559044](https://platzi.com/comentario/559044/) 

	Podría ser muy bueno un ejemplo para base de datos productivas. Con un ejemplo con el plugin Rexray.

* **Yusnier Matos Arias** (1) [81514](https://platzi.com/comentario/982796/) 
Si “pierdo” el token del swarm manager cómo puedo unir otros hosts al clúster?

	* **Daniel Almanza** [81514] (1)

		Esto se puede hacer ejecutando lo siguiente desde un nodo manager:
		
		obtener token para agregar un manager:  
		`docker swarm join-token -q manager`
		
		obtener token para agregar un worker  
		`docker swarm join-token -q worker`

* **nicobytes** (1) [57614](https://platzi.com/comentario/567170/) 
Genial curso, tengo una pregunta en caso de una base de datos productiva, tienes algún recurso, ejemplo o documentación para ver como con...

	* **ManuelMonpa** [57614] (2)

		En este caso vas a tener tu db corriendo en otro lado, ya sea en otra maquina o en servicio de cloud en la nube como por ejemplo, “Amazon RDS”. Esto tendrá su host para conectar a la base de datos, credenciales, port, etc.  
		Ahora, lo que cambiaria seria la variable de entorno MONGO_URL, por la url de tu base de datos productiva.

## 0190. Docker Swarm stacks [15414](https://platzi.com/clases/1434-docker-swarm/15414-docker-swarm-stacks/)

### Descripción:


Con Docker Swarm Stacks (un archivo) se puede controlar cómo se van a despliegan los servicios utilizando los stacks. Siempre es bueno utilizar un archivo porque este puede ser versionado (Git) y se tiene un archivo que va a describir la arquitectura de la aplicación.

### Comentarios:

* **Camilo Castillo** (5) [436416](https://platzi.com/comentario/436416/) 

	Una Buena ayuda para aprender mas a fondo el tema:
	
	<https://medium.com/@Grigorkh/docker-for-beginners-part-4-deploying-an-app-to-a-swarm-620b4d67e7c3>

	* **Edwin De Jesus Chiyopa Garcia** [436416] (2)

		Gracias

* **Edwin De Jesus Chiyopa Garcia** (2) [486980](https://platzi.com/comentario/486980/) 

	Yaml es muy sensible a los espacios en blanco, a mi me marco muchos errores por tener espacio en blanco demás.

	* **jhonsfran90** [486980] (2)

		Esto sirve para validarlo:
		
		<http://www.yamllint.com/>

* **wilantury** (1) [1067093](https://platzi.com/comentario/1067093/) 

	<https://docs.docker.com/engine/reference/commandline/stack/>

* **fredyramosp** (1) [923817](https://platzi.com/comentario/923817/) 

	Eliminar un stack
	``` 
	    docker stackrmapp
	    ``
	    
	```

* **fredyramosp** (1) [923809](https://platzi.com/comentario/923809/) 

	deployar el stack
	``` 
	    docker stack deploy --compose-file stackfile.yml app
	    
	```

* **Victorino1675** (1) [701769](https://platzi.com/comentario/701769/) 

	Tengo una pregunta para el profesor Guido, cuando se trabaja con infraestructuras de Amazon, es recomendable trabajar con ECS (Elastic Container Services), que tienen un sobre costo por el uso de recursos de máquina y que no son baratos, o se podría trabajar con la alternativa de levantar un cluster dentro de una imagen típica EC2, con todas las características de un entorno productivo?, muchas gracias de antemano por su valiosa respuesta.

* **ricardo-rod** (1) [689312](https://platzi.com/comentario/689312/) 

	Ohh rayos con docker stack si se puede utilizar k8s, que astucia!!

* **jjuanleyva** (1) [513310](https://platzi.com/comentario/513310/) 

	Como se accede al visualizador?

	* **Guido Vilariño** [513310] (1)

		Cuando ejecutas contenedores que se exponen en Play-with-docker, te aparece un link a los mismos en la parte superior, con el número de puerto que estás exponiendo.
		
		En un swarm real (no Play-with-docker), lo accedes mediante tu navegador, con el IP de cualquiera de los nodos del swarm, y el puerto donde expusiste el visualizador.

* **Rodrigo Hernan Flores Torres** (1) [64678](https://platzi.com/comentario/680167/) 
Hola guido. tengo un problema. version: '3.7' services: reverseproxy: image: registry.gitlab.com/lyftechnology/intosch...

	* **Guido Vilariño** [64678] (1)

		Para empezar, no deberías usar `links`, es un flag deprecado y no hay garantía de que funcione correctamente.
		
		Por otra parte, qué comando estás usando?

* **jjuanleyva** (1) [53079](https://platzi.com/comentario/513310/) 
Como se accede al visualizador?

	* **Guido Vilariño** [53079] (1)

		Cuando ejecutas contenedores que se exponen en Play-with-docker, te aparece un link a los mismos en la parte superior, con el número de puerto que estás exponiendo.
		
		En un swarm real (no Play-with-docker), lo accedes mediante tu navegador, con el IP de cualquiera de los nodos del swarm, y el puerto donde expusiste el visualizador.

* **rafaelgarciarea** (0) [62164](https://platzi.com/comentario/634845/) 
Hola Guido, Tengo una duda, quiero me gustaría un despliegue de una aplicación web en drupal (docker4drupal) con docker swarm, tengo 3 se...

	* **Diego Alexander Forero Higuera (Platzi)** [62164] (1)

		Cuando he trabajado con php lo que hago es tener nginx y php en el mismo contenedor para tener todas las extensiones instaladas para que funcione el servidor web y un contenedor para la base de datos. Solo pasas como el host de la base de datos el alias que defines en networks para el contenedor de la base de datos.
		``` 
		    networks:
		      net:
		        aliases:
		          - mariadb
		    
		```
		
		Con esto la url de la base de datos dentro de la red va a ser mariadb

## 0200. Reverse proxy muchas aplicaciones, un sólo dominio [15415](https://platzi.com/clases/1434-docker-swarm/15415-reverse-proxy-muchas-aplicaciones-un-solo-dominio/)

### Descripción:


Reverse proxy es una técnica, es un servicio que está escuchando y que toma una decisión con la petición que esta entrando y hace un proxy hacia uno de los servicios que tiene que atender esa petición.

Existe una herramienta llamada traefik, el cual es un intermediario entre las peticiones que vienen del internet a nuestra infraestructura.

### Links:

* [Traefik - The Cloud Native Edge Router / Reverse Proxy / Load Balancer](https://traefik.io/)

### Comentarios:

* **frestrepo** (5) [437455](https://platzi.com/comentario/437455/) 

	docker service create --name proxy --constraint=node.role==manager -p 80:80 -p 9090:8080 --mount type=bind,src=/var/run/docker.sock,dst=/var/run/docker.sock --network proxy-net traefik --docker --docker.swarmMode --docker.domain=domain.loc --docker.watch --api

* **oscar-martinez398** (3) [789823](https://platzi.com/comentario/789823/) 

	Que tal, tuve un pequeño problema. Cuando intente correr el comando, se quedan como en un ciclo, entonces cancele y revise los logs con
	``` 
	    docker service logs proxy 
	    
	```
	
	Y me mandaba este mensaje.
	
	2019/10/21 00:26:42 command traefik error: failed to decode configuration from flags: field not found, node: docker
	
	Y para arreglarlo, solo tuve que definir la versión de traefik y cambiar esta parte
	``` 
	      --docker.swarmMode
	    
	```
	
	Por
	``` 
	    --docker.swarmmode
	    
	```
	
	El comando final quedo así:
	``` 
	    docker service create --name proxy --constraint=node.role==manager -p80:80 -p9090:8080 --mount type=bind,src=/var/run/docker.sock,dst=/var/run/docker.sock --network proxy-net traefik:1.5 --docker --docker.swarmmode --docker.domain=domain.ca --docker.watch --api
	    
	    
	```

* **ManuelMonpa** (1) [839062](https://platzi.com/comentario/839062/) 

	Si quiero usar mis certificados SSL/TLS adquiridos en aws o cualquier otro proveedor con treafik, se puede y de que manera ?, hasta al momento se que funciona muy facil con letsencrypt pero en he podido encontrar algo donde explique dicha configuracion con mis certificado.

* **mauricioacrueda** (1) [822547](https://platzi.com/comentario/822547/) 

	Esto se puede probar de manera local , estoy con windows ?
	
	docker service create --name proxy --constraint=node.role==manager -p 81:80 -p 9091:8080 --net  
	work proxy-net traefik --docker --docker.swarmMode --docker.domain=[maccevedor.com](http://maccevedor.com) \--docker.watch --api  
	n5n9nhgigf8ybc9zeujkea4oo  
	overall progress: 0 out of 1 tasks  
	1/1: starting  
	verify: Detected task failure  
	Operation continuing in background.  
	Use `docker service ps` to check progress.

* **Johan Steven Arias** (1) [795393](https://platzi.com/comentario/795393/) 

	Podría usar traefik con muchos nombres de dominio?

	* **Anthony Farias** [795393] (1)

		Sin ningún problema.

* **felipe santiago gonzalez** (1) [758699](https://platzi.com/comentario/758699/) 

	Me ha salido un error al ejecutar el comando para crear el servicio proxy
	``` 
	    docker service create --name proxy --constraint=node.role==manager -p80:80 -p9090:8080 --mount type=bind,src=/var/run/docker.sock,dst=/var/run/docker.sock --network proxy-net traefik --docker --docker.swarmMode --docker.domain=domain.loc --docker.watch --api
	    
	```
	``` 
	    verify: Detected task failure 
	    
	    
	```

* **Angel Alexi Guerra Miketta** (1) [600852](https://platzi.com/comentario/600852/) 

	Porque no me funciona el traefik cuando al servicio le agrego la etiqueta port
	
	sudo docker service create --name app2 --network proxy-net --label traefik.port=3000 -p 3000:3000 gvilarino/swarm-hostname
	
	Alguien me puede decir como hago para poder conectar mi servicio al traefik y a su vez conectarme por la ip al puerto 3000

	* **Guido Vilariño** [600852] (2)

		Prueba sin publicar el puerto del servicio (eliminando `-p 3000:3000` de tu comando). Esa opción indica que quieres publicar el puerto 3000 del servicio en el 3000 del cluster de VMs; pero no necesitas hacerlo porque ese servicio se expone a través de traefik

* **jandrey** (1) [559423](https://platzi.com/comentario/559423/) 

	Si quisiera crear un servicio que corra en el [domain.com](http://domain.com) y no en [sub.domain.com](http://sub.domain.com) como seria.

	* **jandrey** [559423] (1)

		Se puede hacer agregando un label
		``` 
		     --label traefik.frontend.rule=Host:domain.com
		    
		    
		```

* **Angel Alexi Guerra Miketta** (1) [60113](https://platzi.com/comentario/600852/) 
Porque no me funciona el traefik cuando al servicio le agrego la etiqueta port sudo docker service create --name app2 --network proxy-ne...

	* **Guido Vilariño** [60113] (2)

		Prueba sin publicar el puerto del servicio (eliminando `-p 3000:3000` de tu comando). Esa opción indica que quieres publicar el puerto 3000 del servicio en el 3000 del cluster de VMs; pero no necesitas hacerlo porque ese servicio se expone a través de traefik

* **jandrey** (1) [57017](https://platzi.com/comentario/559423/) 
Si quisiera crear un servicio que corra en el domain.com y no en sub.doma...

	* **jandrey** [57017] (1)

		Se puede hacer agregando un label
		``` 
		     --label traefik.frontend.rule=Host:domain.com
		    
		    
		```

# Swarm productivo [2988]

## 0210. Arquitectura de un swarm productivo [15416](https://platzi.com/clases/1434-docker-swarm/15416-arquitectura-de-un-swarm-productivo/)

### Descripción:


### Links:

* [Understanding the Raft consensus algorithm: an academic article summary](https://medium.freecodecamp.org/in-search-of-an-understandable-consensus-algorithm-a-summary-4bc294c97e0d)

### Comentarios:

* **nicobytes** (2) [567202](https://platzi.com/comentario/567202/) 

	Hola! esta muy bueno poder tener maquinas con hardware diferente para necesidades diferentes, pero entonces como le digo al contenedor que corra es ese tipo de maquina? con labels?

	* **Diego Alexander Forero Higuera (Platzi)** [567202] (1)

		Si, se usan los labels y el parámetro constrain, aquí tienes un ejemplo <https://success.docker.com/article/using-contraints-and-labels-to-control-the-placement-of-containers>

* **wilantury** (1) [1067450](https://platzi.com/comentario/1067450/) 

	* Como mínimo necesitamos tres manager.
	* Podemos configurar grupos de workers según la necesidad de computo.
	* El número de manager debe ser impar. Hay un único líder, y se rotan el liderazgo en un intervalo de tiempo
	
	

* **eneldo-antonio-serrata-peralta** (1) [65559](https://platzi.com/comentario/693449/) 
Estoy preparando mi ambiente productivo de swarm integrado con el CI de gitlab y tengo un problema que no logro resolver, detuve el stack...

	* **ricardo-rod** [65559] (1)

		Que estas usando para el swarm? maquinas virtuales, Docker in docker, instancias en amazon o google, o tu propia maquina?
		
		De ser asi has un docker stop id, docker rm id, o trata de borrar las imagenes y trata de hacer un kill a esos procesos desde el sistema operativo.

## 0220. Administración remota de swarm productivo [15417](https://platzi.com/clases/1434-docker-swarm/15417-administracion-remota-de-swarm-productivo/)

### Descripción:


Las herramientas de administración en Docker Swarm deben persistir en disco (su estado interno, la administración) y la mejor manera de almacenar cosas en Docker son los volúmenes.

En esta clase aprenderemos una forma fácil simple e intituiva de administrar nuestro docker swarm de manera remota. No es la única que existe, así que te invitamos a probar y a dejarnos en los comentarios otras formas que encuentres.

### Links:

* [Docker for Azure persistent data volumes | Docker Documentation](https://docs.docker.com/docker-for-azure/persistent-data-volumes/)

* [REX-Ray](https://rexray.io/)

* [Portainer | Simple management UI for Docker](https://portainer.io/)

* [GitHub - dockersamples/example-voting-app: Example Docker Compose app](https://github.com/dockersamples/example-voting-app)

### Comentarios:

* **eneldo-antonio-serrata-peralta** (3) [692593](https://platzi.com/comentario/692593/) 

	Muy bien explicado tu curso me ha gustado mucho
	
	Ya tengo un tiempo usando <https://swarmpit.io/> y me parece mas productiva que portainer ahí les dejo el link para que la prueben

	* **Albert González Rossell** [692593] (1)

		buena herramienta, espero que en el futuro no sea de pago!

* **ricardo-rod** (3) [689572](https://platzi.com/comentario/689572/) 

	For the greater good, here we go!
	
	docker service create --name portainer -p 9000:9000 --constraint node.role==manager   
	–mount type=bind,src=/var/run/docker.sock,dst=/var/run/docker.sock   
	–mount type=volume,src=portainer_data,dst=/data portainer/portainer   
	-H unix:///var/run/docker.sock

* **Anthony Farias** (1) [1108754](https://platzi.com/comentario/1108754/) 

	Esto es demasiado poderoso. #DockerFan.

## 0230. Consideraciones adicionales para un swarm produtivo [15419](https://platzi.com/clases/1434-docker-swarm/15419-consideraciones-adicionales-para-un-swarm-produtiv/)

### Descripción:


### Links:

* [GitHub - meltwater/docker-cleanup: Automatic Docker image, container and volume cleanup](https://github.com/meltwater/docker-cleanup)

* [Configure logging drivers | Docker Documentation](https://docs.docker.com/config/containers/logging/configure/)

* [GitHub - stefanprodan/swarmprom: Docker Swarm instrumentation with  Prometheus, Grafana, cAdvisor, Node Exporter and Alert Manager](https://github.com/stefanprodan/swarmprom)

### Comentarios:

* **nicobytes** (4) [568225](https://platzi.com/comentario/568225/) 

	```
	    docker service create -d \
	    -e CLEAN_PERIOD=900 \
	    -e DELAY_TIME=600 \
	    --log-driver json-file \
	    --log-opt max-size=1m \
	    --log-opt max-file=2 \
	    --name=cleanup \
	    --mode global \
	    --mount type=bind,source=/var/run/docker.sock,target=/var/run/docker.sock \
	    meltwater/docker-cleanup
	    
	```

* **Roberto A. Martinez Ponce** (4) [441904](https://platzi.com/comentario/441904/) 

	Creo que fue un buen curso, en lo personal ya uso swarm productivo y mejoro mucho mi disponibilidad, y estos tres puntos me los enfrente también.
	
	Creo que hacen falta mas ejemplos de alzar los contenedores como stacks y no como services, los modos de deploy y en lo personal me parece mejor la solución de un reverse proxy con nginx y no con traefik.
	
	PD. Buen curso, claro y conciso.

	* **Juan David Gómez Escobar** [441904] (2)
Gracias por tu aporte sería genial si puedes explicar un poco por qué prefieres nginx por encima de traefik, yo he usado traefik y el hecho que sea docker friendly lo hace muy simple, pero la verdad no constó mucho de nginx como reverse proxy

	* **Johan Steven Arias** [441904] (1)

		Totalmente de acuerdo contigo, el reverse proxy con nginx pinta mejor por la flexibilidad y la robustes que ofrece

* **wilantury** (1) [1067653](https://platzi.com/comentario/1067653/) 

	* Problema Docker housekeeping : Hay que hacer mantenimiento del espacio en disco.
	* Lo que hace es crear un servicio global que podrá tomar las imágenes que no tengan un contenedor y contenedores inactivos por un tiempo y los borra.
	* Este servicio estará en cada nodo.
	* Hay que tener una herramienta de monitoreo de mis servicios.
	
	

* **xergioalex** (1) [578660](https://platzi.com/comentario/578660/) 

	Está genial el cleaner, es un problema que suelo tener constantemente, voy a implementarlo en mis servicios productivos 😃. Algo que quizas me genera inquietud es que el proyecto parece abandonado <https://github.com/meltwater/docker-cleanup>, hace 3 años no se actualiza.

# Conclusiones [2989]

## 0240. Conclusiones [15418](https://platzi.com/clases/1434-docker-swarm/15418-conclusiones/)

### Descripción:


¡Felicitaciones! y muchas gracias por completar este curso de Docker Swarm, donde has aprendido a generar nuevas herramientas que te van a servir para preparar tus aplicaciones, para llevarlas a la nube donde van a poder escalar a miles de usuarios.

Te invitamos a que realices la prueba.

### Comentarios:

* **Anthony Farias** (1) [1108898](https://platzi.com/comentario/1108898/) 

	Puro oro este curso. Guido es un crack

* **wilantury** (1) [1067656](https://platzi.com/comentario/1067656/) 

	Muchas gracias, excelente curso.

* **Cristian Ramirez** (1) [1047344](https://platzi.com/comentario/1047344/) 

	El mejor curso que he tomado.  
	Muchísimas gracias.

* **cami_ev** (1) [599129](https://platzi.com/comentario/599129/) 

	Muchas gracias Guido por el curso. Ambos de docker muy buenos hasta ahora. Seguiré buscando cursos tuyos.

* **xergioalex** (1) [578662](https://platzi.com/comentario/578662/) 

	Excelente curso! Aprendí bastante.

* **nicobytes** (1) [567211](https://platzi.com/comentario/567211/) 

	Muy bueno

* **Edwin De Jesus Chiyopa Garcia** (1) [491696](https://platzi.com/comentario/491696/) 

	Hola Guido, me gustaria que me ayudaras, estoy haciendo pruebas de todo lo que hemos visto en el curso, pero con dos maquinas fisicas, todo me ha salido de manera estupenda hazte que me eh topado con el problema de los nombres de dominio, mi duda es…  
	Tengo 3 maquinas fisicas dentro de una red lan, una con windows y dos con linux(ubuntu 18 y docker swam), despues de instalar traefik y hacer la prueba con curl todo anda bien, al momento de quererlo visualizar en mi maquina con windows desde el navegar con el nombre de dominio ejem:mi.dominio.com no alcanzo a traefik, la unica forma de verlo es ingresar directamente con la IP, ¿Como puedo resolver esto y a que se debe?.

	* **Guido Vilariño** [491696] (2)

		Suena a que estás usando un dominio que no es público, sino que lo has configurado en tu red interna. Para que funcione desde otra máquina, tu swarm tiene que ser alcanzable en dicho dominio, es decir, debes apuntar `tu.dominio.com` a los IPs públicos de tus máquinas de Swarm.
		
		Tu problema es de networking, no es de Swarm: no tiene sentido usar dominios para una red interna a menos que esa misma red tenga un servidor DNS que resuelva dicho dominio a las IPs de la red interna donde está tu swarm.

	* **Jorge Rivera** [491696] (3)

		Puedes instalar y configurar un DNS para tu LAN ( en docker 😉 ) o puedes editar el archivo hosts de tus maquinas, en linux esta en /etc/hosts y en windows esta en C:\Windows\System32\drivers\etc\hosts , profundiza un poco en eso, es fácil e interesante. Saludos!.

* **jlazo** (1) [489955](https://platzi.com/comentario/489955/) 

	Guido, un capo total. Me encanto tu curso de docker, y ni hablar de este curso. Tus explicaciones son super digeribles, eres un gran maestro. Gracias

* **Diego Andres Fonseca Soto** (1) [437713](https://platzi.com/comentario/437713/) 

	Muchas gracias Guido por compartir tu experiencia, muy productivo el curso de Docker y Swarm.

	* **Roberto A. Martinez Ponce** [437713] (1)

		Muy bueno

* **rtorralba** (1) [60473](https://platzi.com/comentario/605941/) 
Hola Guido, Estamos montando un servicio que contará a grandes rasgos de una aplicación servidor padre y muchos workers a los que les man...

	* **Guido Vilariño** [60473] (1)

		Entiendo lo siguiente de tu comentario:
		
		* Tus clientes siempre van a tener una IP de origen fija
		
		
		
		Luego no entiendo si estás diciendo que tus clientes necesitan pegarle sí o sí a una IP destino fija para los workers. Si es así, puedes configurar la IP pública de cualquier nodo del swarm, dado que no importa a qué nodo llegues, si le pegas al puerto correspondiente swarm se encarga de hacerle llegar la petición al servicio correspondiente.
		
		Si lo que necesitas es filtrar las peticiones en función de un IP de origen y bloquear todas las demás, tienes varias formas de hacerlo:
		
		* Levantar tu swarm cluster en un cloud provider detrás de algún tipo de firewall que permita whitelistear source IPs
		* Exponer un reverse proxy (como traefik o docker-flow-proxy) con network en modo host y como servicio global (corre una instancia en cada nodo) de manera que ignore la ingress network del swarm, así podrás ver el IP de origen en dichos los contenedores del reverse proxy, y filtrar las peticiones en función de dicho valor
		
		

* **Edwin De Jesus Chiyopa Garcia** (1) [51446](https://platzi.com/comentario/491696/) 
Hola Guido, me gustaria que me ayudaras, estoy haciendo pruebas de todo lo que hemos visto en el curso, pero con dos maquinas fisicas, to...

	* **Guido Vilariño** [51446] (2)

		Suena a que estás usando un dominio que no es público, sino que lo has configurado en tu red interna. Para que funcione desde otra máquina, tu swarm tiene que ser alcanzable en dicho dominio, es decir, debes apuntar `tu.dominio.com` a los IPs públicos de tus máquinas de Swarm.
		
		Tu problema es de networking, no es de Swarm: no tiene sentido usar dominios para una red interna a menos que esa misma red tenga un servidor DNS que resuelva dicho dominio a las IPs de la red interna donde está tu swarm.

* **rtorralba** (0) [605931](https://platzi.com/comentario/605931/) 

	Hola Guido,
	
	Muy bueno el curso.
	
	Estamos montando un servicio que contará a grandes rasgos de una aplicación servidor padre y muchos workers a los que les mandará tareas que harán peticiones hacia fuera. En principio habíamos pensado tenerlo todo dockerizado, como lo tenemos casi todo ahora y para abstraer si lo tenemos en maquinas distintas usar docker swarm.
	
	El tema es que los usuarios de este servicio tendrán unas ip’s públicas propias (reservadas) con lo que las peticiones que hagan los workers tienen que hacerse con esa ip como source. Tenemos que levantar un contenedor con una ip fija con lo que solo tendríamos un contenedor por ip?

	* **fredyramosp** [605931] (1)

		Hola,  
		Podrían usar un proxy reverso como nginx que esté sobre el cluster de swarm

