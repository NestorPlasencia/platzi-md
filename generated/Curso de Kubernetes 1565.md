[Curso de Kubernetes 1565](https://platzi.com/cursos/k8s)

# Introducción a Kuberentes [3899]

## 0010. Bienvenida e introducción [19462](https://platzi.com/clases/1565-k8s/19462-bienvenida-e-introduccion/)

### Descripción:


¡Bienvenido al curso!

**Kubernetes** es la plataforma de orquestación con mayor éxito en el mercado.

Es necesario que tengas conocimiento o te sientas cómodo trabajando desde la línea de comandos o terminal y conocimientos básicos de Docker.

**Objetivos** :

* Visión y entendimiento de la plataforma de Kubernetes
* Uso y buenas prácticas de las distintas herramientas
* Workflow aplicativo sobre la plataforma de Kubernetes



Puedes compartir tus conocimientos o logros con el hashtag #PlatziK8s

### Links:

* [Play with Kubernetes](https://labs.play-with-k8s.com/)

* [Curso de GO | Materiales](https://platzi.com/clases/go-basico/)

* [Fundamentos de Docker | Materiales](https://platzi.com/clases/docker/)

* [Introducción a Terminal y Línea de Comandos | Materiales](https://platzi.com/clases/terminal/)

* [Play with Docker](https://labs.play-with-docker.com/)

### Comentarios:

* **victoralonso7355** (12) [572570](https://platzi.com/comentario/572570/) 

	Hola!
	
	Les dejo este enlace, donde aprenderán de una forma muy didáctica, los principales conceptos de Kubernetes, estoy seguro de que disfrutarán entendiendo los conceptos y de una forma muy fácil:
	
	<https://www.cncf.io/the-childrens-illustrated-guide-to-kubernetes/>
	
	Espero les sea de utilidad.

* **Alex Pedersen** (5) [958357](https://platzi.com/comentario/958357/) 

	Estaria bueno que los profesores tengan un perfil, para poder ver otros cursos de l mismo profesor

* **Ramses Ponce** (2) [853972](https://platzi.com/comentario/853972/) 

	No había visto que lo da marcos, es el MEJOR.

* **jandrey** (2) [570201](https://platzi.com/comentario/570201/) 

	K8s es la abreviatura de kubernetes, la K 8 letras y la S.

* **Hernan Dario Berrio Higuera** (2) [570077](https://platzi.com/comentario/570077/) 

	Centos o ubuntu cual es el preferido y porque?

	* **Diego Alexander Forero Higuera (Platzi)** [570077] (4)

		Eso depende mucho de gustos, Centos es muy estable pero usa paquetes algo antiguos ya que tiene que pasar demasiados procesos de verificación para que actualicen un paquete, por otro lado Ubuntu Server es bueno y actualiza más rápido, la verdad puedes usar cualquiera de los dos sin problema.

* **Sebastián Pineda Duque** (2) [57940](https://platzi.com/comentario/571015/) 
¿Cuándo renovarán el curso de Go?

	* **Diego Alexander Forero Higuera (Platzi)** [57940] (2)

		El curso de Go que existe actualmente enseña las bases del lenguaje que realmente no ha cambiado, cuéntanos que te gustaría ver en la renovación del curso.

* **Antonio Madrid** (1) [984868](https://platzi.com/comentario/984868/) 

	Se ve un profesor con ganas y que sabe de lo que habla.  
	Vine aquí para saber que era Kubernetes, como desarrollador actualmente no es una prioridad para mi, pero se me hizo muy interesante.
	
	Espero poder retomar el curso en algún momento.

* **Carolina Londoño** (1) [968221](https://platzi.com/comentario/968221/) 

	Esta caído el link de la Dockercon que hay en la presentación 😦

* **SergioBernal** (1) [874602](https://platzi.com/comentario/874602/) 

	ME está gustando mucho tu curso, recomiendas recursos para k8s más enfocado a developers? Gracias!

* **johan2732** (1) [571277](https://platzi.com/comentario/571277/) 

	Como se puede hacer parte de la comunidad?

	* **Diego Alexander Forero Higuera (Platzi)** [571277] (2)

		El profesor lo menciona principalmente participando en los proyectos haciendo contribuciones y asistiendo a los eventos.

* **Sebastián Pineda Duque** (1) [571015](https://platzi.com/comentario/571015/) 

	¿Cuándo renovarán el curso de Go?

	* **Diego Alexander Forero Higuera (Platzi)** [571015] (2)

		El curso de Go que existe actualmente enseña las bases del lenguaje que realmente no ha cambiado, cuéntanos que te gustaría ver en la renovación del curso.

	* **Iván Sabido** [571015] (2)

		A partir de la versión 1.11 cambia el manejo de los módulos, ya es más al estilo npm.

	* **flickyiyo** [571015] (2)

		El actual curso de Go esta bien para aprender el lenguaje, creo que te refieres al curso de backend con Go. O me equivoco?

	* **Andrus Diaz** [571015] (2)

		Lo que hace falta es el cuso de Golang avanzado

	* **Sebastián Pineda Duque** [571015] (0)

		Es claro que la metodología de Platzi ha cambiado mucho desde entonces. Falta renovar este curso, hacer uno avanzado y frameworks web. Creo que es la carrera más pequeña de Platzi.

* **johan2732** (1) [57959](https://platzi.com/comentario/571277/) 
Como se puede hacer parte de la comunidad?

	* **Diego Alexander Forero Higuera (Platzi)** [57959] (2)

		El profesor lo menciona principalmente participando en los proyectos haciendo contribuciones y asistiendo a los eventos.

* **Hernan Dario Berrio Higuera** (1) [57886](https://platzi.com/comentario/570077/) 
Centos o ubuntu cual es el preferido y porque?

	* **Diego Alexander Forero Higuera (Platzi)** [57886] (4)

		Eso depende mucho de gustos, Centos es muy estable pero usa paquetes algo antiguos ya que tiene que pasar demasiados procesos de verificación para que actualicen un paquete, por otro lado Ubuntu Server es bueno y actualiza más rápido, la verdad puedes usar cualquiera de los dos sin problema.

## 0020. Repaso de contenedores e introducción a k8s [19463](https://platzi.com/clases/1565-k8s/19463-repaso-de-contenedores-e-introduccion-a-k8s/)

### Descripción:


Los **contenedores** no son un _first class citizen_ del kernel de Linux, un contenedor no es una entidad previamente definida. Es un concepto abstracto conformado por diferentes tecnologías que se potencian las unas a las otras y trabajando en conjunto componen esta tecnología.

* **Cgroups** o Control Groups: Son los que permiten que un contenedor o proceso tenga aislado los recursos como memoria, I/O, Disco y más. Limitan los recursos del SO
* **Namespaces** : Permiten aislar el proceso para que viva en un sandbox y no pueda haber otros recursos de SO o contenedores.  
– Mount Namespaces: Permite que nuestro proceso tenga una visibilidad reducida de los directorios donde trabaja.  
– Networking Namespaces: Permite que cada contenedor tenga su stack de red.  
– PID.
* Chroot: Cambia el root directory de un proceso.



### Links:

* [Fundamentos de Docker | Materiales](https://platzi.com/clases/docker/)

### Comentarios:

* **Lele Lester** (21) [571183](https://platzi.com/comentario/571183/) 

	Contenedor: no es una entidad. Son distintas tecnologias que trabajando en conjunto crean un contenedor.
	
	Las 3 tecnologias son:
	
	**CGroups:** Asignan a cada contenedor/proceso los recursos va a utilizar (memoria, disco, cpu). Limitan el uso de recursos del sistema operativo para cada contenedor.
	
	**Chroot:** Nos permite que nuestro proceso/container tenga visibilidad sobre archivos donde tiene que trabajar y no acceder a otros recursos del sistema.
	
	**Namespaces:** (son 7, aqui los mas importantes):
	
	* Mount: Nos permite que nuestro proceso tenga una visibilidad reducida de los directorios. Esto permite que dos contenedores que trabajen sobre un sistema de archivos no se interfieran entre si.
	
	* Networking: Permite que cada contenedor tenga su dirección IP, su tabla de rutas, su interfaz de red, y que no interfiera con otros contenedores.  
	Concepto de POD: Entidad atomica scheduleable - Entidad sobre la cual kubernetes va a ejecutar los contenedores. (se verá en detalle más adelante).
	
	* PID o de proceso: si ejecutamos un `ps` cuando ejecutamos nuestro contenedor, vamos a ver que nuestro contenedor es el process id 1 y no vemos todo el resto de los procesos del SO. Esto es posible gracias al namespace de procesos. (se verá en detalle más adelante).
	
	
	

	* **Alan Cornejo** [571183] (1)

		Pregunta porque replicar lo mismo que dice el profesor, cual es el aporte al video en si ??

* **lantog** (5) [623087](https://platzi.com/comentario/623087/) 

	Para los que no se conforman con "I dont’ care how if it works"  
	[Como funciona docker internamente](https://docker-saigon.github.io/post/Docker-Internals/)

	* **Miguel Angel Escurra** [623087] (1)

		Muchas gracias!

	* **Dionisio** [623087] (1)

		Gracias! Gran aporte.

* **Yurley** (4) [606916](https://platzi.com/comentario/606916/) 

	Kubernetes  
	Desde el principio, Kubernetes fue diseñado para ser un entorno para la creación de aplicaciones distribuidas de contenedores. El objetivo principal de Kubernetes es un sistema para la construcción, el funcionamiento y la gestión de sistemas distribuidos.
	
	Además se basa en la experiencia de muchos años de Google trabajando con los contenedores de Linux. Es, en cierto modo, una réplica de lo que Google ha estado haciendo durante mucho tiempo, pero, esta vez, adaptado a Dockers, entonces aporta esa experiencia en la forma de organizar y desplegar una aplicación en contenedores.
	
	Otra buena característica de Kubernetes es que se puede configurar el controlador para mantener activos el mismo número de contenedores, es decir, si por algún motivo se detuviese algún contenedor, se creará un nuevo contenedor con una copia casi exacta, del 99%.
	
	Y por último (que no quiero decir que no tenga más características) es el escalado ya sea “hacia arriba” o “hacia abajo”; con Kubernetes es fácil, solo se tiene que especificar la cantidad de nuevas aplicaciones y si quieres hacia arriba o hacia abajo a través de un comando.
	
	en cuanto a Docker Swarm, es la herramienta nativa para el cluster de Docker. Con Docker Swarm tenemos lo que llamaremos Swarm Master que será el responsable del cluster, también tendremos nodos que debe ser accesible por el Master y cada uno de ellos contendrá uno o varios contenedores.
	
	Al contrario que Kubernetes, Swarm es un “esfuerzo” por parte de Docker para extender la API de Docker existente para hacer que un conjunto de máquinas se vean como una sola API de Docker.

* **Walter Ugalde A** (4) [571901](https://platzi.com/comentario/571901/) 

	Que bueno, esperaba mucho este curso, me encanto el primero que dio hace rato.

* **luis-batalla** (3) [570207](https://platzi.com/comentario/570207/) 

	no carga el video, a alguno le pasa lo mismo ?

	* **wfranco007** [570207] (1)

		Igual me pasa…

	* **Diego Alexander Forero Higuera (Platzi)** [570207] (2)

		Estamos revisando y solucionaremos lo más pronto posible, por el momento pueden probar cambiando al servidor C en el icono del engrane.

	* **rodheran** [570207] (1)

		Perfecto Server C funcionando.

	* **DiegoRP** [570207] (1)

		A mi me funciona perfecto.

* **jandrey** (2) [570217](https://platzi.com/comentario/570217/) 

	Excelente profesor 😃

* **nicolas.cancino** (1) [788248](https://platzi.com/comentario/788248/) 

	Exelente forma de explicar!

* **rcortesksz** (1) [633803](https://platzi.com/comentario/633803/) 

	Hola compañer@s,
	
	Yo en documentaciones pasadas he leido que una imagen se compone de capas y la base de esta pila de capas es el SO que puede ser debian,Centos,etc.
	
	Porque esto no fue considerado en la planilla?
	
	Dejo imagen de referencia.!![](https://linoxide.com/wp-content/uploads/2015/03/docker-filesystems-busyboxrw.png)

	* **k7code** [633803] (1)

		Hola compañero, supongo que no se mencionó en esta clase porque se estaba mostrando de forma general la estructura que tiene un contenedor versus las maquinas virtuales. Por cierto, gracias por la info.

## 0030. De pods a contenedores [19464](https://platzi.com/clases/1565-k8s/19464-de-pods-a-contenedores/)

### Descripción:


 **Docker & Kubernetes**

* Docker se encarga principalmente de gestionar los contenedores.
* Kubernetes es una evolución de proyectos de Google Borg & Omega.
* Kubernetes pertenece a la CNCF (Cloud Native Computing Foundation).
* Todos los cloud providers (GCP/AWS/Azure/DO) ofrecen servicios de managed k8s utilizando Docker como su container runtime
* Es la plataforma más extensiva para orquestación de servicios e infraestructura



**Kubernetes en la práctica**

* K8s permite correr varias réplicas y asegurarse que todas se encuentren funcionando.
* Provee un balanceador de carga interno o externo automáticamente para nuestros servicios.
* Definir diferentes mecanismos para hacer _roll-outs_ de código.
* Políticas de _scaling_ automáticas.
* Jobs batch.
* Correr servicios con datos _stateful_.



Todos los contenedores que viven dentro de un mismo Pod comparten el mismo segmento de red.

### Links:

* [Curso de Swarm | Materiales](https://platzi.com/clases/docker-swarm/)

### Comentarios:

* **Omar Alvarez** (12) [570192](https://platzi.com/comentario/570192/) 

	 **Importante pregunta de examen**
	
	Todos los contenedores del mismo pod comparten el mismo namespaces de red.

	* **ceskmcfran** [570192] (3)

		Por tanto tienen la misma dirección IP y se ven unos a otros como procesos corriendo dentro del mismo sistema.

	* **xergioalex** [570192] (2)

		Y cuando escalamos algo en K8s se escalan precisamente los pods.

* **Deybi Diaz Luisi** (5) [786573](https://platzi.com/comentario/786573/) 

	Excelente profesor. Deberias dar tambien un curso de Linux Servers

* **jandrey** (5) [570721](https://platzi.com/comentario/570721/) 

	Un pod son uno o mas contenedores que viven juntos y comparten un namespaces de red.

* **Daniel Rodriguez Rodriguez** (4) [680173](https://platzi.com/comentario/680173/) 

	Me encanta este profe, es super técnico pero se esmera en explicarlo muy muy bien, No cambies!!

* **CARLOS DAVID MARCIGLIA GOMEZ** (2) [1011034](https://platzi.com/comentario/1011034/) 

	Con **Kubernete ** en mi equipo de trabajo esperamos hacer deployment mucho mas rápido de las nuevas funcionalidades sin detener el servicio a nuestros clientes actuales y futuros y asi poder escalar al 1000%

* **msantim** (2) [978212](https://platzi.com/comentario/978212/) 

	Considero que hacer una app monolitica no esta del todo mal. Usualmente lo hago cuando algún cliente me contrata para hacer algun MVP. En un proyecto pequeño no necesitas todo de K8s, pero…  
	Y que tal si crece? y que tal si necesita HA? Monitoring? CI/CD?  
	Este curso es el ideal para resolver algunas de esas preguntas.

	* **Víctor Daniel Cardozo Fernández** [978212] (3)

		Yo pienso que no vale la pena el esfuerzo en costo y tiempo de hacer una arquitectura super compleja para proyectos que están comenzando. A menos que sea un proyectos personal y te puedas dar el tiempo. Pero si es para un cliente siempre es mejor hacer un monolito y cuando se haya probado la idea migrar lo más rápido posible ahora si a una arquitectura de microservicios

* **Jonnathan Ramiro Juma Jara** (2) [944274](https://platzi.com/comentario/944274/) 

	gracias, estoy repitiendo el curso para no olvidar nada, consejo de Freddy

* **Miguel Angel Escurra** (2) [921221](https://platzi.com/comentario/921221/) 

	Concepto importante y pregunta de examen

* **Marcoh** (1) [732880](https://platzi.com/comentario/732880/) 

	Excelente explicación, se nota que domina bastante el tema.

* **farrano** (1) [686582](https://platzi.com/comentario/686582/) 

	Excelente clase. Saludos!

* **gromanec** (1) [596705](https://platzi.com/comentario/596705/) 

	Se considera una buena practica tener un solo contenedor en cada pod?

	* **Jose Almenarez** [596705] (1)

		Es lo mejor pero hay casos donde se requiere tener mas de un contenedor como un logger por ejemplo.

* **gromanec** (1) [59855](https://platzi.com/comentario/596705/) 
Se considera una buena practica tener un solo contenedor en cada pod?

	* **Jose Almenarez** [59855] (1)

		Es lo mejor pero hay casos donde se requiere tener mas de un contenedor como un logger por ejemplo.

## 0040. ¿Cómo funciona la arquitectura de red de Kubernetes [19465](https://platzi.com/clases/1565-k8s/19465-como-funciona-la-arquitectura-de-red-de-kubernetes/)

### Descripción:


En esta clase el profesor Marcos Lilljedahl nos explica algo fundamental para el aprendizaje de esta tecnología: cómo funciona la arquitectura red de Kubernetes.

Kubernetes es un proyecto open source para automatizar despliegues, escalar y orquestar aplicaciones dentro de contenedores.

### Comentarios:

* **xergioalex** (31) [579125](https://platzi.com/comentario/579125/) 

	##  **Arquitectura de K8s**
	
	**Nodo Master**
	
	  1. **API Server:** A lo que todo se conecta, los agentes, el CLI, el dashboard etc. Cuando se cae un nodo master es lo que se pierde. Se usa el algoritmo de ruft para algoritmo de elección.
	  2. **Scheduler:** Cuando se deben crear un job, un pod en máquinas específicas, el scheduler se encarga de asignar las tareas y administrar los flujos de trabajos, revisando siempre las restricciones y los recursos disponibles.
	  3. **Controller Manager:** Es un proceso que está en un ciclo de reconciliación constante buscando llegar al estado deseado con base al modelo declarativo con el que se le dan instrucciones a K8s.  
	++Tipos de controller manager: ++
	
	
	* Replica manager
	* Deployment manager
	* Service manager  
	…
	
	
	  1. **Etcd:** Key value store que permite que el cluster este altamente disponible.
	
	
	
	**Componentes muy importantes que viven en los nodos:**
	
	  1. **Kubelet:** Agente de kubernetes, se conecta con el control play y le pregunta que recursos (pods, contenedores) debo correr al scheduler via API Server. Monitorea los pods constantemente para saber si están vivos, los recursos disponibles etc y le comunica constantemente al scheduler via API Server.
	  2. **Kube-proxy:** Se encarga de balancear el tráfico que corre en nuestros contenedores/servicios. Una vez llega una request se encarga de decidir a que pod y contenedor debe de ir.
	
	
	
	**Nodos == Minions**
	
	Todos los nodos y masters están conectados a una red física para poder hablarsen entre sí.

* **Omar Alvarez** (10) [573893](https://platzi.com/comentario/573893/) 

	Le comparto el Comic de Google que explica lo que es Kubernetes:  
	<https://cloud.google.com/kubernetes-engine/kubernetes-comic/>

	* **William Calderón Castillo** [573893] (1)

		Excelente Gracias!

* **Juan Francisco Paulino Veras Francisco Paulino Veras** (6) [652387](https://platzi.com/comentario/652387/) 

	Un link por si están interesados en el [algoritmo de consenso Raft](https://raft.github.io/).

	* **Miguel Angel Escurra** [652387] (1)

		Excelente enlace!!

* **Germain Rafael Bueno Taguariparo** (3) [573896](https://platzi.com/comentario/573896/) 

	Me guataría compartieran las imagenes que salen en el video.

	* **csierra** [573896] (4)

		<https://static.platzi.com/media/public/uploads/platzi-curso-k8s_d86c22d7-2f5f-4e41-b0f2-f9360e15a173.pdf>

	* **Juan David Castro (Platzi)** [573896] (1)

		¡Hola! Los slides de los cursos siempre están publicados en la primera clase: <https://platzi.com/clases/1565-k8s/19462-bienvenida-e-introduccion4604/>.

	* **farrano** [573896] (1)

		Gracias, yo también las buscaba!

* **Germain Rafael Bueno Taguariparo** (2) [58183](https://platzi.com/comentario/573896/) 
Me guataría compartieran las imagenes que salen en el video.

	* **csierra** [58183] (4)

		<https://static.platzi.com/media/public/uploads/platzi-curso-k8s_d86c22d7-2f5f-4e41-b0f2-f9360e15a173.pdf>

* **ceskmcfran** (1) [574322](https://platzi.com/comentario/574322/) 

	Minions == Nodos

* **cmuballesteros** (1) [82872](https://platzi.com/comentario/1014368/) 
Me queda la duda de qué también puede trabajar kubernetes con socket.io

* **Jonnathan Ramiro Juma Jara** (1) [79703](https://platzi.com/comentario/944848/) 
muy buena explicacion

* **wfranco007** (1) [70051](https://platzi.com/comentario/768231/) 
No está cargando este video. Por favor revisar.

	* **Juan David Castro (Platzi)** [70051] (1)

		Hola. La clase está bien. Es una clase publicada en YouTube. Puedes verla también desde este link: <https://youtu.be/dfTgp8MhTmg>.

* **jraquise** (0) [83583](https://platzi.com/comentario/1030259/) 
Cuando instalo un master en un servidor, puedo instalar un nodo en el mismo servidor?

	* **Diego Alexander Forero Higuera (Platzi)** [83583] (1)

		No es posible, el ideal es que estén separados para asegurar la disponibilidad, incluso entornos de alta disponibilidad deben contar con dos servidores master y el resto de servidores con nodos.

## 0050. Modelos declarativos e imperativos [19466](https://platzi.com/clases/1565-k8s/19466-modelos-declarativos-e-imperativos/)

### Descripción:


Los control managers se encargan de estar en un loop constante de reconciliación y tratar de converger a ese estado deseado, ese es un sistema **declarativo**. Un sistema **imperativo** parece un sistema fácil de seguir y está compuesto por una serie de pasos que deben seguirse a rajatabla.

* Kubernetes hace énfasis en ser un sistema declarativo
* Declarativo: “Quiero una taza de té”
* Imperativo: “Hervir agua, agregar hojas de té y servir en una taza”
* Declarativo parece sencillo (siempre y cuando uno sepa cómo hacerlo)
* Todo en Kubernetes se crea desde un spec que describe cuál es el estado deseado del sistema
* Kubernetes constantemente converge con esa especificación



### Comentarios:

* **xergioalex** (7) [579136](https://platzi.com/comentario/579136/) 

	Todo en K8s se crea a través de una especificación en un **.yml** o un manifest, y lo que hace el sistema es que trata de converger a este estado deseado.

* **msantim** (1) [978311](https://platzi.com/comentario/978311/) 

	Imperativo vs Declarativo:
	
	* Un sistema es imperativo cuando ejecuta una seria de pasos, que deben seguir un orden especifico. Si algun paso se interrumpe, la secuencia inicia desde el paso 1.
	* Un sistema es declarativo cuando trata de converger a un estado deseado, a partir de un estado actual.
	
	

* **jose-leon-faneite** (1) [926559](https://platzi.com/comentario/926559/) 

	buenas explicación, muy buen docente 😃

## 0060. Visión general del modelo de red [19467](https://platzi.com/clases/1565-k8s/19467-vision-general-del-modelo-de-red/)

### Descripción:


* Todo el cluster es una gran red del mismo segmento
* Todos los nodos deben conectarse entre si, sin NAT (Network Adress Translation)
* Todos los pods deben conectarse entre si, sin NAT
* kube-proxy es el componente para conectarnos a pods y contenedores (userland proxy/iptables)
* Los pods trabajan a capa 3 (transporte) y los servicios a capa 4 (protocolos)



### Comentarios:

* **tavo_0610** (5) [588387](https://platzi.com/comentario/588387/) 

	La capa 3 es la de red y la capa 4 de transporte en el modelo OSI. Está mal la descripción.

	* **Everardo Sánchez** [588387] (2)

		de hecho

	* **Ivan Perea Fuentes** [588387] (3)

		Recuerda que el modelo TCP/IP no se corresponde capa a capa con el modelo OSI, en el modelo TCP/IP la capa de red es la capa 2, la de transporte (UDP y TCP) capa 3 y la capa 4 la de usuario o aplicación.

* **Andrés Muñoz** (3) [1002739](https://platzi.com/comentario/1002739/) 

	Les comparto esta joya que encontré, una genialidad como explica el modelo de capas, yo antes de ver este video estaba perdido no entendia que era una capa, espero les guste tanto como a mi.  
	<https://www.youtube.com/watch?v=EDXSvhbaTvM>

* **jonathan diaz Diaz Diaz** (2) [614259](https://platzi.com/comentario/614259/) 

	Muy buena clase

* **xergioalex** (2) [579148](https://platzi.com/comentario/579148/) 

	 **NAT (Network Address Translation):** Es una tecnología que se utiliza para no utilizar tantas redes ip y maximizar su uso.

* **Super Technologies , S.L.** (1) [601996](https://platzi.com/comentario/601996/) 

	Tengo la siguiente duda, si quiero conectar una de mis aplicaciones dentro de kubernetes a una base de datos en la nube, ¿Como puedo averiguar la ip que tengo que poner en el whiteliste de la base de datos para que mi app se pueda conectar? La pregunta mas bien es: ¿Con que ip de origen sale el trafico del kluster de kubernetes?

	* **luiggi.mendoza** [601996] (1)

		Entendería que eso no depende de k8s sino del router o módem que usas para salir a internet. Ese sería el IP que debieras poner en la whitelist.

	* **victoralonso7355** [601996] (1)

		Saldrías con la IP pública que utiliza tu router para navegar en Internet. Ten en cuenta también, que en muchos casos tu proveedor, puede asignarte una IP pública dinámica, por lo que tendrías que actualizar tu whitelist, cada vez que cambie tu IP.

* **Andrés Muñoz** (1) [82320](https://platzi.com/comentario/1002768/) 
Es correcto que nodo1 y nodo2 tengan la misma ip 10.0.0.1 o es un bug en el video ?

* **Super Technologies , S.L.** (1) [60185](https://platzi.com/comentario/601996/) 
Tengo la siguiente duda, si quiero conectar una de mis aplicaciones dentro de kubernetes a una base de datos en la nube, ¿Como puedo aver...

	* **luiggi.mendoza** [60185] (1)

		Entendería que eso no depende de k8s sino del router o módem que usas para salir a internet. Ese sería el IP que debieras poner en la whitelist.

## 0070. Recomendaciones [19468](https://platzi.com/clases/1565-k8s/19468-recomendaciones/)

### Descripción:


Durante este curso vamos a utilizar algunos comandos en nuestro cluster de Kubernetes para crear recursos y ejemplificar algunas situaciones de manera concreta. Esos comandos son a modo ejemplificativo y no hacen parte de nuestra aplicación de prueba.

Todo el contenido de nuestra aplicación y los manifest files que utilizamos a lo largo de las clases se encuentran en <https://github.com/platzi/curso-kubernetes> en sus respectivas carpetas de dockercoins y k8s.

En la clase de aplicación de prueba vamos a clonar este repositorio y trabajaremos sobre los archivos contenidos en las subsiguientes clases.

¡Continuemos con el curso!

### Comentarios:

* **Sebastian Borrajo** (3) [576682](https://platzi.com/comentario/576682/) 

	Aguante K8s vieja no me importa nadaaa

* **mrosasozuna** (2) [574656](https://platzi.com/comentario/574656/) 

	comencemos a crear integraciones para aplicaciones del mundo real!

* **SergioBernal** (1) [874772](https://platzi.com/comentario/874772/) 

	🏆

* **msantim** (1) [861246](https://platzi.com/comentario/861246/) 

	😄

* **jgorocica** (1) [846838](https://platzi.com/comentario/846838/) 

	**Gracias por compartir el repositorio. **

* **Joan Carlo Lopez Marin** (1) [820044](https://platzi.com/comentario/820044/) 

	super

* **farrano** (1) [686920](https://platzi.com/comentario/686920/) 

	Gracias por los recursos!

* **jonathan diaz Diaz Diaz** (1) [614297](https://platzi.com/comentario/614297/) 

	Super

* **Kevin Santacruz** (1) [602815](https://platzi.com/comentario/602815/) 

	Genial gracias por los recursos, excelente curso

## 0080. Introducción a aplicación de prueba [19469](https://platzi.com/clases/1565-k8s/19469-introduccion-a-aplicacion-de-prueba/)

### Descripción:


### Links:

* [GitHub - platzi/curso-kubernetes: Curso de Kubernetes profesor Marcos Nils](https://github.com/platzi/curso-kubernetes/)

* [Fundamentos de Docker | Materiales](https://platzi.com/clases/docker/)

### Comentarios:

* **Bërtïn Namoc Vega** (2) [835145](https://platzi.com/comentario/835145/) 

	Alguien logro levantar la aplicación… yo tengo una error en JQuery
	
	Uncaught SyntaxError: Unexpected number  
	index.html:93 Uncaught ReferenceError: $ is not defined  
	at index.html:93  
	favicon.ico:1 Failed to load resource: the server responded with a status of 404 (Not Found)

	* **Javier González de Lope** [835145] (0)

		A mí me pasa lo mismo. Alguien sabe cómo solucionar el fallo?

	* **Domingo Palma** [835145] (2)

		Lo solucioné abriendo el archivo index.html, y reemplazando query.js" por “jquery-1.11.3.min.js”. Saludos!

* **raparisg** (1) [878339](https://platzi.com/comentario/878339/) 

	Buena clase! Se que quizás no sea relevante para el curso, pero cómo hizo el Docker Compose para hacer el network discovery si en el docker-compose.yml no se indicò nunca las networks ni se crearon? Pensé que si o si se debía declarar explícitamente estas networks para conectar los contenedores…

	* **rodhsoft** [878339] (1)

		No, no se declaran, pero al hacer docker-compose up se crea automaticamente  
		es mas si haces docker-compose down, detiene los servicios pero no elimina nada asi que podrás visualizar aun en las networks la que fue creada para esos servicios.

	* **Jesús Andrés Miranda Roa** [878339] (1)

		si quieres observar las network que tienes activas, con el comando **docker network ls** alli veras la de dockercoins

* **dmcorrales** (1) [655326](https://platzi.com/comentario/655326/) 

	Muy agradable la clase, deja claro cada uno de los conceptos y dependencias para iniciar con nuestro proyecto

* **jonathan diaz Diaz Diaz** (1) [614316](https://platzi.com/comentario/614316/) 

	Muy buena clase, si es bueno haber ya trabajado con docker y docker-compose para que sea mas amigable

* **Rodrigo Hernan Flores Torres** (1) [575204](https://platzi.com/comentario/575204/) 
M mmmn mm m

* **Lorena Cardona Tovar** (1) [64448](https://platzi.com/comentario/676027/) 
La ip de mi maquina + el puerto es http://192.168.99.100:8000, pero me muestra el siguiente erro...

	* **Diego Alexander Forero Higuera (Platzi)** [64448] (2)

		Hola, modificaste el puerto en el docker compose?, con el ejemplo la app corre en el puerto 8080.

* **Matias Ignacio Monsalves Lopez** (0) [911189](https://platzi.com/comentario/911189/) 

	Me posiciono en el directorio curso-kubernetes/dockercoins y al colocar docker-compose up no encuentra el comando. Que debo configurar para que tome el comando?

	* **jose-leon-faneite** [911189] (1)

		probaste con sudo?

	* **Christian Hernandez Najera** [911189] (1)

		Ya lo tienes instalado? si no mira [aquí](https://docs.docker.com/compose/install/)

## 0090. Instalando nuestro primer cluster con Minikube, Kubeadm [19470](https://platzi.com/clases/1565-k8s/19470-instalando-nuestro-primer-cluster-con-minikube-kub/)

### Descripción:


 **Minikube** es una herramienta para desplegar un cluster en tu máquina local.

**kubeadm** es un boostrap, un utilitario que permite realizar todo lo mostrado en el repositorio de Kelsey.

### Links:

* [GitHub - kelseyhightower/kubernetes-the-hard-way: Bootstrap Kubernetes the hard way on Google Cloud Platform. No scripts.](https://github.com/kelseyhightower/kubernetes-the-hard-way)

* [GitHub - kubernetes/minikube: Run Kubernetes locally](https://github.com/kubernetes/minikube)

### Comentarios:

* **jandrey** (3) [571161](https://platzi.com/comentario/571161/) 

	 **kubelet** es el agente que corre en nuestros nodos.

* **Henry_Coarite** (2) [762053](https://platzi.com/comentario/762053/) 

	Gracias compañeros por los aportes. Saludos desde Bolivia. 😃

* **Wesly Fernández** (2) [716552](https://platzi.com/comentario/716552/) 

	Interesante lo de empezar a trabajar antes con docker y docker-compose.

* **mauriciodinki** (2) [687273](https://platzi.com/comentario/687273/) 

	Por si tienen problemas con el Hyper-V En Windows
	
	<https://minikube.sigs.k8s.io/docs/start/windows/>

* **Jesús Andrés Miranda Roa** (1) [1092132](https://platzi.com/comentario/1092132/) 

	Para los que **no tienen kubectl instalado** , aqui les dejo como hacerlo
	
	Ubuntu/Debian o Hypriot OS
	
	  1. sudo apt-get update && sudo apt-get install -y apt-transport-https
	  2. curl -s <https://packages.cloud.google.com/apt/doc/apt-key.gpg> | sudo apt-key add -
	  3. echo “deb <https://apt.kubernetes.io/> kubernetes-xenial main” | sudo tee -a /etc/apt/sources.list.d/kubernetes.list
	  4. sudo apt-get update
	  5. sudo apt-get install -y kubectl
	
	
	
	Para ejecutar el minikube seria:
	
	  1. minikube start --drive=virtualbox ( no viene por default, para hacer default es, minikube config set driver virtualbox, y podras ejecutar minikube start con virtualbox )
	
	  2. kubectl create deployment hello-minikube --image=[k8s.gcr.io/echoserver:1.4](http://k8s.gcr.io/echoserver:1.4)
	
	  3. kubectl expose deployment hello-minikube --port=8080 --type=NodePort
	
	  4. minikube service hello-minikube
	
	
	
	
	Algunos comandos que te puede ayudar
	
	  1. kubectl get service (listar servicios)
	
	  2. kubectl get pod (lilstar pod)
	
	  3. kubectl get all (listar todo)
	
	
	

* **Jose Saavedra Vergara** (1) [1019717](https://platzi.com/comentario/1019717/) 

	En mi caso me aparecieron un montón de problemas con minikube (estoy en un linux min). Pero igual pude instalar el minikube, pero con virtualbox omo hypervisor.
	
	Y lo que nunca entendí, como sacar la ip del cluster en el caso que ya estuviese corriendo. Ya que en mi caso no me entregó ninguna ip:
	``` 
	    ~$ minikube start--vm-driver=virtualbox
	    😄  minikube v1.7.2on Linuxmint 19.3
	    ✨  Using the virtualbox driver based onuser configuration
	    ⌛  Reconfiguring existing host ...
	    🏃  Using the running virtualbox "minikube" VM ...
	    🐳  Preparing Kubernetes v1.17.2on Docker 19.03.5 ...
	    💾  Downloading kubelet v1.17.2
	    💾  Downloading kubeadm v1.17.2
	    💾  Downloading kubectl v1.17.2
	    🚀  Launching Kubernetes ... 
	    🌟  Enabling addons: default-storageclass, storage-provisioner
	    🏄  Done! kubectl isnow configured touse"minikube"
	    
	```

* **jonathan diaz Diaz Diaz** (1) [615312](https://platzi.com/comentario/615312/) 

	Para poder set un profile en minikube se corre el comando
	``` 
	    minikube profile platzi2
	    
	```
	
	Luego si se corre `minikube status` y da el status actual del cluster

* **Kevin Santacruz** (1) [603392](https://platzi.com/comentario/603392/) 

	Para usar Minikube en windows se recomienda desactivar hyper-v y es mejor instalar VirtualBox para levantar k8s

* **Joshua Nathanael Saucedo Uriarte** (1) [573960](https://platzi.com/comentario/573960/) 

	tambien pueden utilizar [microk8s](https://microk8s.io/). se instala desde snap. Tambien es una herramienta para desplegar un cluster en tu máquina local.
	``` 
	    sudo snap install microk8s --classic
	    
	```

* **csierra** (1) [60769](https://platzi.com/comentario/610592/) 
Hola, tengo un inconveniente en windows para que Minikube funcione debo inhabilitar hyper-v, pero en este escenario Docker no me funcion...

	* **makaros_027** [60769] (1)

		La forma mas facil de instalar minikube en windows utilizando el Hyper-V es:
		``` 
		    choco install minikube kubernetes-cli
		    
		```
		
		La Documentación para instalar Hyper-V en Windows:  
		<https://kubernetes.io/es/docs/tasks/tools/install-minikube/#instalar-minikube>

* **Carolina Londoño** (0) [1031964](https://platzi.com/comentario/1031964/) 

	como obtengo la direccion IP de mi cluster si estoy utilizando docker desktop en vez de minicube?

## 0100. Instalando nuestro primer cluster con Kubeadm [19471](https://platzi.com/clases/1565-k8s/19471-instalando-nuestro-primer-cluster-con-kubeadm/)

### Descripción:


### Links:

* [Play with Kubernetes](https://labs.play-with-k8s.com/)

### Comentarios:

* **Cristian Miño Verdezoto** (2) [1069570](https://platzi.com/comentario/1069570/) 

	La pagina <https://labs.play-with-k8s.com/> esta con error 500. ayuda

* **Roberto Rivera Salazar** (2) [982081](https://platzi.com/comentario/982081/) 

	Al parecer la página [labs.play-with-k8s.com](https://labs.play-with-k8s.com) ya no está funcionando, pero pueden realizar las mismas dinámicas de esta clase en la siguiente liga:
	
	[play-with-kubernetes.com](https://training.play-with-kubernetes.com/kubernetes-workshop/)

* **vital_ec** (2) [904790](https://platzi.com/comentario/904790/) 

	 **sí funciona**[Play with Kuberntes](https://labs.play-with-k8s.com/)
	
	Para ingresar puedes hacerlo con la ID de docker o github, yo entre mi ID de docker la primera vez no carga, de ahi **recargue la página y entré**

* **joan-rincon-sarmiento** (2) [840423](https://platzi.com/comentario/840423/) 

	La pagina no funciona

* **Jesús Andrés Miranda Roa** (1) [1092214](https://platzi.com/comentario/1092214/) 

	<https://labs.play-with-k8s.com/> no anda, error 500

	* **gvetri** [1092214] (1)

		Acabo de probar y me funciona. <https://labs.play-with-k8s.com/> Habrá estado caido.

* **Yohan Morales** (1) [1070571](https://platzi.com/comentario/1070571/) 

	efectivamente no anda <https://labs.play-with-k8s.com/>, error 500 siempre 😦

	* **oscarvesga** [1070571] (1)

		Hola, utiliza la imagen franela/k8s

	* **oscarvesga** [1070571] (1)

		<https://i.imgur.com/ZRpkhiL.jpg>

	* **lcmartinez_ (Platzi)** [1070571] (1)

		Debio ser un error temporal porque yo acabode probar y funciona bien.

	* **Alvez Gerardo** [1070571] (1)

		Hoy funciona perfecto

	* **Yohan Morales** [1070571] (0)

		si, hoy funciona perfecto!

* **GABRIEL OMAR TARAPUES RODRIGUEZ** (1) [1051850](https://platzi.com/comentario/1051850/) 

	la pagina <https://labs.play-with-k8s.com/#>, se queda congelada al poner start…que podria ser??

* **Victor Cruz** (1) [1011164](https://platzi.com/comentario/1011164/) 

	Cuando entra a la página e intento crear un nodo, en ocasiones se queda pasmado., en otras ocasiones si abre el nodo, pero cuando creo el control-plane con la instrucción indicada, marca un error indicando que ya no tiene espacio en disco. ¿Que hago en esos escenarios?

* **Fernando Lopez** (1) [835310](https://platzi.com/comentario/835310/) 

	buenas, se me presento una duda… se pueden tener nodos con distintas versiones de kubernetes?

* **henryvalle** (1) [828241](https://platzi.com/comentario/828241/) 

	tengo el siguiente error al ejecutar el siguiente comando para realzar la intancia del nodo1.
	
	**COMANDO:**
	``` 
	    kubeadm init --apiserver-advertise-address $(hostname -i)
	    
	```
	
	**ERROR:**
	``` 
	    [init] using Kubernetes version: v1.11.10
	    [preflight] running pre-flight checks
	            [WARNING Port-10251]: Port 10251 is in use
	            [WARNING Port-10252]: Port 10252 is in use
	            [WARNING FileAvailable--etc-kubernetes-manifests-kube-apiserver.yaml]: /etc/kubernetes/manifests/kube-apiserver.yaml already exists
	            [WARNING FileAvailable--etc-kubernetes-manifests-kube-controller-manager.yaml]: /etc/kubernetes/manifests/kube-controller-manager.yaml already exists
	            [WARNING FileAvailable--etc-kubernetes-manifests-kube-scheduler.yaml]: /etc/kubernetes/manifests/kube-scheduler.yaml already exists
	            [WARNING FileAvailable--etc-kubernetes-manifests-etcd.yaml]: /etc/kubernetes/manifests/etcd.yaml already exists
	            [WARNING Service-Docker]: docker service is not active, please run 'systemctl start docker.service'
	            [WARNING FileContent--proc-sys-net-bridge-bridge-nf-call-iptables]: /proc/sys/net/bridge/bridge-nf-call-iptables does not exist
	    I1118 03:59:58.006231    4930 kernel_validator.go:81] Validating kernel version
	    I1118 03:59:58.010252    4930 kernel_validator.go:96] Validating kernel config
	    [preflight] The system verification failed. Printing the output from the verification:
	    KERNEL_VERSION: 4.4.0-165-generic
	    DOCKER_VERSION: 18.06.1-ce
	    OS: Linux
	    CGROUPS_CPU: enabled
	    CGROUPS_CPUACCT: enabled
	    CGROUPS_CPUSET: enabled
	    CGROUPS_DEVICES: enabled
	    CGROUPS_FREEZER: enabled
	    CGROUPS_MEMORY: enabled
	            [WARNING SystemVerification]: docker version is greater than the most recently validated version. Docker version: 18.06.1-ce. Max validated version: 17.03
	            [WARNING SystemVerification]: failed to parse kernel config: unable to load kernel module "configs": output - "", err - exit status 1
	            [WARNING Port-10250]: Port 10250 is in use
	            [WARNING DirAvailable--var-lib-etcd]: /var/lib/etcd is not empty
	    [preflight/images] Pulling images required for setting up a Kubernetes cluster
	    [preflight/images] This might take a minute or two, depending on the speed of your internet connection
	    [preflight/images] You can also perform this action in beforehand using 'kubeadm config images pull'
	    [preflight] WARNING: unable to stop the kubelet service momentarily: [exit status 1]
	    [kubelet] Writing kubelet environment file with flags to file "/var/lib/kubelet/kubeadm-flags.env"
	    [kubelet] Writing kubelet configuration to file "/var/lib/kubelet/config.yaml"
	    [preflight] Activating the kubelet service
	    [preflight] WARNING: unable to start the kubelet service: [exit status 1]
	    [preflight] please ensure kubelet is reloaded and running manually.
	    [certificates] Using the existing ca certificate and key.
	    [certificates] Using the existing apiserver certificate and key.
	    [certificates] Using the existing apiserver-kubelet-client certificate and key.
	    [certificates] Using the existing sa key.
	    [certificates] Using the existing front-proxy-ca certificate and key.
	    [certificates] Using the existing front-proxy-client certificate and key.
	    [certificates] Using the existing etcd/ca certificate and key.
	    [certificates] Using the existing etcd/server certificate and key.
	    [certificates] Using the existing etcd/peer certificate and key.
	    [certificates] Using the existing etcd/healthcheck-client certificate and key.
	    [certificates] Using the existing apiserver-etcd-client certificate and key.
	    [certificates] valid certificates and keys now exist in "/etc/kubernetes/pki"
	    [kubeconfig] Using existing up-to-date KubeConfig file: "/etc/kubernetes/admin.conf"
	    [kubeconfig] Using existing up-to-date KubeConfig file: "/etc/kubernetes/kubelet.conf"
	    [kubeconfig] Using existing up-to-date KubeConfig file: "/etc/kubernetes/controller-manager.conf"
	    [kubeconfig] Using existing up-to-date KubeConfig file: "/etc/kubernetes/scheduler.conf"
	    [controlplane] wrote Static Pod manifest for component kube-apiserver to "/etc/kubernetes/manifests/kube-apiserver.yaml"
	    [controlplane] wrote Static Pod manifest for component kube-controller-manager to "/etc/kubernetes/manifests/kube-controller-manager.yaml"
	    [controlplane] wrote Static Pod manifest for component kube-scheduler to "/etc/kubernetes/manifests/kube-scheduler.yaml"
	    [etcd] Wrote Static Pod manifest for a local etcd instance to "/etc/kubernetes/manifests/etcd.yaml"
	    [init] waiting for the kubelet to boot up the control plane as Static Pods from directory "/etc/kubernetes/manifests"
	    [init] this might take a minute or longer if the control plane images have to be pulled
	    
	                    Unfortunately, an error has occurred:
	                            timed out waiting for the condition
	    
	                    This error is likely caused by:
	                            - The kubelet is not running
	                            - The kubelet is unhealthy due to a misconfiguration of the node in some way (required cgroups disabled)
	                            - No internet connection is available so the kubelet cannot pull or find the following control plane images:
	                                    - k8s.gcr.io/kube-apiserver-amd64:v1.11.10
	                                    - k8s.gcr.io/kube-controller-manager-amd64:v1.11.10
	                                    - k8s.gcr.io/kube-scheduler-amd64:v1.11.10
	                                    - k8s.gcr.io/etcd-amd64:3.2.18
	                                    - You can check or miligate this in beforehand with "kubeadmconfig images pull" to make sure the images
	                                      are downloaded locally and cached.
	    
	                    If you are on a systemd-powered system, you can try to troubleshoot the error with the following commands:
	                            - 'systemctl status kubelet'
	                            - 'journalctl -xeu kubelet'
	    
	                    Additionally, a control plane component may have crashed or exited when started by the container runtime.
	                    To troubleshoot, l
	                              WARNING!!!!
	    
	     This is a sandbox environment. Using personal credentials
	     is HIGHLY! discouraged. Any consequences of doing so, are
	     completely the user's responsibilites.
	    
	    [node1 ~]$ kubeadm init --apiserver-advertise-address $(hostname -i)
	    Initializing machine ID from random generator.
	    [init] using Kubernetes version: v1.11.10
	    [preflight] running pre-flight checks
	            [WARNING Service-Docker]: docker service is not active, please run 'systemctl start d
	    ocker.service'
	            [WARNING FileContent--proc-sys-net-bridge-bridge-nf-call-iptables]: /proc/sys/net/bri
	    dge/bridge-nf-call-iptables does not exist
	    I1118 03:47:05.161205    1004 kernel_validator.go:81] Validating kernel version
	    I1118 03:47:05.162964    1004 kernel_validator.go:96] Validating kernel config
	    [preflight] The system verification failed. Printing the output from the verification:
	    KERNEL_VERSION: 4.4.0-165-generic
	    DOCKER_VERSION: 18.06.1-ce
	    OS: Linux
	    CGROUPS_CPU: enabled
	    CGROUPS_CPUACCT: enabledCGROUPS_CPUSET: enabled
	    CGROUPS_DEVICES: enabled
	    CGROUPS_FREEZER: enabled
	    CGROUPS_MEMORY: enabled
	            [WARNING SystemVerification]: docker version is greater than the most recently valida
	    ted version. Docker version: 18.06.1-ce. Max validated version: 17.03
	            [WARNING SystemVerification]: failed to parse kernel config: unable to load kernel mo
	    dule "configs": output - "", err - exit status 1
	    [preflight/images] Pulling images required for setting up a Kubernetes cluster
	    [preflight/images] This might take a minute or two, depending on the speed of your internet connection
	    [preflight/images] You can also perform this action in beforehand using 'kubeadm config images pull'
	    [kubelet] Writing kubelet environment file with flags to file "/var/lib/kubelet/kubeadm-flags.env"
	    [kubelet] Writing kubelet configuration to file "/var/lib/kubelet/config.yaml"
	    [preflight] Activating the kubelet service
	    [certificates] Generated ca certificate and key.
	    [certificates] Generated apiserver certificate and key.
	    [certificates] apiserver serving cert is signed for DNS names [node1 kubernetes kubernetes.default kubernetes.default.svc kubernetes.default.svc.cluster.local] and IPs [10.96.0.1 192.168.0.23]
	    [certificates] Generated apiserver-kubelet-client certificate and key.
	    [certificates] Generated sa key and public key.
	    [certificates] Generated front-proxy-ca certificate and key.
	    [certificates] Generated front-proxy-client certificate and key.
	    [certificates] Generated etcd/ca certificate and key.
	    [certificates] Generated etcd/server certificate and key.
	    [certificates] etcd/server serving cert is signed for DNS names [node1 localhost] and IPs [127.0.0.1 ::1]
	    [certificates] Generated etcd/peer certificate and key.
	    [certificates] etcd/peer serving cert is signed for DNS names [node1 localhost] and IPs [192.168.0.23 127.0.0.1 ::1]
	    [certificates] Generated etcd/healthcheck-client certificate and key.
	    [certificates] Generated apiserver-etcd-client certificate and key.
	    [certificates] valid certificates and keys now exist in "/etc/kubernetes/pki"
	    [kubeconfig] Wrote KubeConfig file to disk: "/etc/kubernetes/admin.conf"
	    [kubeconfig] Wrote KubeConfig file to disk: "/etc/kubernetes/kubelet.conf"
	    [kubeconfig] Wrote KubeConfig file to disk: "/etc/kubernetes/controller-manager.conf"
	    [kubeconfig] Wrote KubeConfig file to disk: "/etc/kubernetes/scheduler.conf"
	    [controlplane] wrote Static Pod manifest for component kube-apiserver to "/etc/kubernetes/manifests/kube-apiserver.yaml"
	    [controlplane] wrote Static Pod manifest for component kube-controller-manager to "/etc/kubernetes/manifests/kube-controller-manager.yaml"
	    [controlplane] wrote Static Pod manifest for component kube-scheduler to "/etc/kubernetes/manifests/kube-scheduler.yaml"
	    [etcd] Wrote Static Pod manifest for a local etcd instance to "/etc/kubernetes/manifests/etcd.yaml"
	    [init] waiting for the kubelet to boot up the control plane as Static Pods from directory "/etc/kubernetes/manifests"
	    [init] this might take a minute or longer if the control plane images have to be pulled
	    
	                    Unfortunately, an error has occurred:
	                            timed out waiting for the condition
	    
	                    This error is likely caused by:
	                            - The kubelet is not running
	                            - The kubelet is unhealthy due to a misconfiguration of the node in some way (required cgroups disabled)
	                            - No internet connection is available so the kubelet cannot pull or find the following control plane images:
	                                    - k8s.gcr.io/kube-apiserver-amd64:v1.11.10
	                                    - k8s.gcr.io/kube-controller-manager-amd64:v1.11.10
	                                    - k8s.gcr.io/kube-scheduler-amd64:v1.11.10
	                                    - k8s.gcr.io/etcd-amd64:3.2.18
	                                    - You can check or miligate this in beforehand with "kubeadmconfig images pull" to make sure the images
	                                      are downloaded locally and cached.
	    
	                    If you are on a systemd-powered system, you can try to troubleshoot the error with the following commands:
	                            - 'systemctl status kubelet'
	                            - 'journalctl -xeu kubelet'
	    
	                    Additionally, a control plane component may have crashed or exited when started by the container runtime.
	                    To troubleshoot, list all containers using your preferred container runtimesCLI, e.g. docker.
	    
	    
	```

	* **Bërtïn Namoc Vega** [828241] (1)

		Tengo el mismo error -.-!

* **aaldonate** (1) [701448](https://platzi.com/comentario/701448/) 

	<https://labs.play-with-k8s.com/> en la pagina no logra crear nueva instancia.

	* **henryvalle** [701448] (1)

		tampoco puedo crear la insatancia me sale el siguiente error:
		``` 
		    [init] this might take a minute or longer if the control plane images have to be pulled
		    
		                    Unfortunately, an error has occurred:
		                            timed out waiting for the condition
		    
		                    This erroris likely caused by:
		                            - The kubelet isnot running
		                            - The kubelet is unhealthy due to a misconfiguration of the node in some way (required cgroups disabled)
		                            - No internet connection is available so the kubelet cannot pull or find the following control plane images:
		                                    - k8s.gcr.io/kube-apiserver-amd64:v1.11.10
		                                    - k8s.gcr.io/kube-controller-manager-amd64:v1.11.10
		                                    - k8s.gcr.io/kube-scheduler-amd64:v1.11.10
		                                    - k8s.gcr.io/etcd-amd64:3.2.18
		                                    - You can check or miligate this in beforehand with"kubeadmconfig images pull"to make sure the images
		                                      are downloaded locally and cached.
		    
		                    If you are on a systemd-powered system, you can tryto troubleshoot the errorwith the following commands:
		                            - 'systemctl status kubelet'
		                            - 'journalctl -xeu kubelet'
		    
		                    Additionally, a control plane component may have crashed or exited when started by the container runtime.
		                    To troubleshoot, list all containers using your preferred container runtimesCLI, e.g. docker.
		                    Here is one example how you may list all Kubernetes containers running in docker:
		                            - 'docker ps -a | grep kube | grep -v pause'
		                            Once you have found the failing container, you can inspect its logs with:
		                            - 'docker logs CONTAINERID'
		    couldn't initialize a Kubernetes cluster```
		    
		```

* **Jair Sebastian Lozano Moron** (1) [681148](https://platzi.com/comentario/681148/) 

	La aplicación está con errores, no crea ninguna instancia luego de hacer clic en crear instancia, podrías solucionarlo, por favor?

* **rogerdavila** (1) [678201](https://platzi.com/comentario/678201/) 

	Hola, he estado intentando ingresar a play with k8s pero me da un error al momento de dar clic en start;
	
	![Selection_072.png](https://static.platzi.com/media/user_upload/Selection_072-7379e97b-6be7-4391-98b3-3799073d448e.jpg)

* **Julio Cesar Jaramillo Palacios** (1) [667613](https://platzi.com/comentario/667613/) 

	Hola, intente crear una instancia en play with Kubernates pero nunca se crea, alguien mas tiene ese issue? saludos.

	* **Omar Alvarez** [667613] (1)

		Me pasa lo mismo pero no se donde reportarlo

* **Miguel Andrés Isaza Barona** (1) [83879](https://platzi.com/comentario/1037383/) 
No funciona el enlace, se queda cargando la página.

	* **fernandajofili (Platzi)** [83879] (1)

		Hola Miguel!  
		Un compañero nos dijo en [este comentario](https://platzi.com/comentario/982081/) que es posible hacer las mismas dinámicas a través de esta [página](https://training.play-with-kubernetes.com/kubernetes-workshop/):

* **davanzoivanmatias** (1) [69400](https://platzi.com/comentario/756568/) 
Hola Dejo un par de preguntas… Veo muchos tutoriales en internet como instalar un clúster de k8s y todos mencionan desactivar el Firewall...

	* **Erik Ochoa (Platzi)** [69400] (1)

		  1. Sí, nunca desactives el firewall en servidores de producción.
		  2. Definitivamente kubeadm creo es un buen bootstrap para empezar.
		
		
		
		En cuanto a la decisión de usar su propio data center, son libres de hacerlo y puede que tengan muy buenos motivos para hacerlo pero creo que no estaría de más evaluar las muchas ventajas que dan los servicios en la nube.

* **RoquilloGuri** (1) [67430](https://platzi.com/comentario/723121/) 
hola, estoy instalacion kubeadm en centos 7, pero cuando inicio con kubeadm init, me muestras estos WARNING y me gustaria saber como reso...

	* **Diego Alexander Forero Higuera (Platzi)** [67430] (1)

		Como lo mencionas son Warnings, si ya te aseguraste de tener esos puertos abiertos el sistema solo te esta diciendo que te asegures de tener los puertos abiertos, si te puedes conectar al cluster entonces no vas a tener problema. en cuanto al driver debes ejecutar esto
		``` 
		    
		    # Install prerequisites
		    yum-config-manager --add-repo=https://cbs.centos.org/repos/paas7-crio-115-release/x86_64/os/
		    
		    # Install CRI-O
		    yum install --nogpgcheck cri-o
		    
		```

* **sytsa** (0) [775420](https://platzi.com/comentario/775420/) 

	A mi me parece muy bien que arrancamos usando esta plataforma, porque podemos probar cosas sin necesidad de gastar dinero en infra.

* **RAUL FRANCISCO NAVARRO SALVO** (0) [734920](https://platzi.com/comentario/734920/) 

	no me gusta que uses esto para enseñar kubeadm. sido mucho mejor configurar todo desde 0 para aprender.

## 0110. Desplegando el Cluster en AWS con EKS [19472](https://platzi.com/clases/1565-k8s/19472-desplegando-el-cluster-en-aws-con-eks/)

### Descripción:


### Links:

* [Getting Started with Amazon EKS - Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/getting-started.html)

* [https://amazon-eks.s3-us-west-2.amazonaws.com/cloudformation/2019-02-11/amazon-eks-nodegroup.yaml](https://amazon-eks.s3-us-west-2.amazonaws.com/cloudformation/2019-02-11/amazon-eks-nodegroup.yaml)

### Comentarios:

* **Manuel Sepúlveda** (2) [881221](https://platzi.com/comentario/881221/) 

	No pude crear por cloudformation, por comando con el ekscli pude crear el cluster y el nodegroup
	
	`eksctl create cluster --name NOMBRE`
	
	`eksctl create nodegroup --cluster NOMBRE --name NOMBRE2 --node-type t3.micro --nodes 2 --nodes-min 1 --nodes-max 2`

* **oscar-martinez398** (1) [884232](https://platzi.com/comentario/884232/) 

	Cuanto intento correr el comando
	
	kubectl get nodes me sale el siguiente error
	
	An error occurred (AccessDenied) when calling the AssumeRole operation.
	
	Lo raro es que ya le asigne el rol a ese cluster y también ya estoy autenticado con el usuario admin

* **joan-rincon-sarmiento** (1) [840658](https://platzi.com/comentario/840658/) 

	Me salió error Unauthorized, no está la plantilla del cloudformation

* **dariovinueza** (1) [831091](https://platzi.com/comentario/831091/) 

	Tengo este error: error: You must be logged in to the server (Unauthorized)

	* **Kevin Javier Morales (Platzi)** [831091] (3)

		Es un problema de permisos, debes estar logeado en el servidor.

	* **oscar-martinez398** [831091] (1)

		¿Pudiste arreglar el problema?

	* **raparisg** [831091] (2)

		El error es porque al crear un cluster en Kubernetes, el usuario que crea el cluster toma permisos exclusivos del uso del cluster. Por lo que si estás utilizando la cuenta root de AWS para crear el cluster y luego utilizas otro usuario para conectarte desde la CLI, al ser usuarios distintos, no posees permiso.
		
		AWS recomienda **no** utilizar la cuenta root para uso cotidiano. Sino que es mejor crear una cuenta con privilegios de administrador (o privilegios reducidos según sea el caso) y utilizar esta para crear el cluster y conectarte desde la CLI.
		
		Referencias: <https://docs.aws.amazon.com/eks/latest/userguide/troubleshooting.html#unauthorized>

	* **oscar-martinez398** [831091] (1)

		Gracias @raparisg C: Precisamente así fue como pude solucionar el problema …

* **juan-sebastian-otero** (1) [827945](https://platzi.com/comentario/827945/) 

	El tema de permisos y roles puede ser “a pain in the neck” si no tienes experiencia en AWS, mis recomendaciones:
	
	* En lo posible usa eksctl para aprovisionar el cluster, no la consola.
	
	* Si lo haces por consola ten muy en cuenta desde que usuario estas creado el IAM role, si estas usando root de amazon tienes que configurar este usuario en el aws cli con el comando `aws configure` e ingresar las claves de acceso de root (esto no es una buena practica, es mejor hacer todo esto desde un usuario diferente al root de aws).
	
	* Si luego quieres agregar mas usuarios con permisos al cluster, se deben hacer estos pasos: [Administración de usuarios o funciones de IAM para su clúster](https://docs.aws.amazon.com/es_es/eks/latest/userguide/add-user-role.html?shortFooter=true)
	
	
	

* **Alvez Gerardo** (1) [584904](https://platzi.com/comentario/584904/) 

	No puedo conectarme al cluster creado con kubectl desde mi pc. seguí absolutamente todos los pasos de [getting-started](https://docs.aws.amazon.com/eks/latest/userguide/getting-started.html). cuando ejecuto kubectl get svc sale el siguiente error:
	``` 
	    Anerror occurred (AccessDenied) when calling the AssumeRole operation: Access denied```
	    
	    Si a alguien le ha pasado y lo soluciona estaría agradecido.
	    PD: probe el trouble shotting de amazon en ese error y no soluciona nada.
	```

	* **Diego Alexander Forero Higuera (Platzi)** [584904] (3)

		Es un error de permisos, estas usando las credenciales correctas y tienes el archivo de configuración de kubectl bien configurado?

	* **Alvez Gerardo** [584904] (2)

		Gracias GOLLUM23 por responder.  
		cree el cluster con el rol que me pide amazon, luego al usuario creado le hice asumir el role creado y ahora el error que me sale es:
		``` 
		    error: You must be logged into the server (Unauthorized)
		    
		```
		
		para eso amazon dice: If you assumed a role to create the Amazon EKS cluster, you must ensure that kubectl is configured to assume the same role
		``` 
		    aws --region region eks update-kubeconfig --name cluster_name --role-arn arn:aws:iam::aws_account_id:role/role_name
		    
		```
		
		pero nada, es como que al usuario creado no tiene los permisos para acceder al cluester, porque en aws cli las credeciales estan del usuario que cree aparte.

	* **Damian Perez** [584904] (1)

		tengo problemas con los permisos, tienes alguna guia de los permisos que tuviste que activar ?

	* **Diego Alexander Forero Higuera (Platzi)** [584904] (1)

		@damianpv qué problemas exactamente para ver como podemos ayudarte.

	* **Diego Alexander Forero Higuera (Platzi)** [584904] (1)

		@alvezgr estas reemplazando los valores en el comando por los valores de tu cluster y role creados?

	* **Damian Perez** [584904] (1)

		hola, tengo los siguientes errores:
		
		$ kubectl get nodes  
		error: the server doesn’t have a resource type “nodes”
		
		$ kubectl get svc  
		error: the server doesn’t have a resource type “svc”
		
		no se si sea problemas de permisos, estuve jugando un poco con los permisos y logre que me mostraran informacion pero ya me sale el mismo problema.
		
		gracias,

	* **Damian Perez** [584904] (2)

		el ultimo que me sale es: An error occurred (AccessDenied) when calling the AssumeRole operation: Access denied  
		Unable to connect to the server: getting credentials: exec: exit status 255

	* **Diego Alexander Forero Higuera (Platzi)** [584904] (1)

		@damianpv prueba creando un nuevo rol con todos los permisos sobre EKS y lo asignas a tu usuario con este comando
		``` 
		    aws --region region eks update-kubeconfig --name cluster_name --role-arn arn:aws:iam::aws_account_id:role/role_name
		    
		```
		
		Reemplazas region, cluster_name y role_name por tus datos, esto debería funcionar.

	* **Damian Perez** [584904] (1)

		gracias tenia un error en los pasos de la documentacion, ya pude desplegar guestbook.

	* **Diego Alexander Forero Higuera (Platzi)** [584904] (1)

		@damianpv coméntanos el error que tenias y como lo solucionaste eso puede servirle a otros estudiantes que se enfrenten al mismo problema. 😉

	* **Damian Perez** [584904] (1)

		tenia un error al asignar el kubeconfig con el nombre del rol.

	* **Alexei Teófilo Mamani Coaquira** [584904] (1)

		Para los que tuvieron este error, no se si haya cambiando hasta hoy la forma de conectar, pero pues si creas como lo hizo el, aws solo da acceso al usuario root, si deseas agregar un usuario con iam necesitas agregar al RBAC de kubernetes, y eso lo hacer con esto <https://docs.aws.amazon.com/es_es/eks/latest/userguide/add-user-role.html?shortFooter=true>.  
		para hacer la primera conección tienes que utilizar los SECRET TOKEN de root, asi es como me funciono, por seguridad luego creas un iam user con los mismo permisos del role que se creo.

* **Cecilia N** (1) [582098](https://platzi.com/comentario/582098/) 

	Hice todos los pasos, pero no logro asociar los nodos al cluster… ¿En que me estoy equivocando?

	* **ebar0n (Platzi)** [582098] (1)

		Hola, es difícil ayudarte sin ver como lo haces, chekaste que los nodos se creen en la misma region?

* **Victoria Tejeda** (1) [574582](https://platzi.com/comentario/574582/) 

	Cree una cuenta de AWS.  
	Cuando accedo a esta parte para crear el cluster veo que tiene un precio.
	
	![](https://i.ibb.co/Xy7WwtJ/Captura-de-Pantalla-2019-04-29-a-la-s-13-03-13.png)
	
	¿Esto significa que para continuar con el curso **tengo que pagar**? o entra como un componente sin costo por el periodo de un año?

	* **Germain Rafael Bueno Taguariparo** [574582] (1)

		Correcto

	* **Diego Alexander Forero Higuera (Platzi)** [574582] (3)

		Hola, aquí tienes información de lo que incluye la capa gratuita de AWS en su primer año [https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free Tier Types=categories%23featured](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=categories%23featured), efectivamente EKS no es un servicio gratuito que este incluido, es un servicio realmente nuevo que lleva poco más de 6 meses publicado y un año con acceso privado que podías solicitar para probar el servicio.

* **Juan Emmanuel Díaz** (1) [573895](https://platzi.com/comentario/573895/) 

	Hice una cambio en el template de AWS, capaz le sirve, hice un add en la parte que lista las instances. A ver si con eso evito que me cobren 😄, porque las instancias free de amazon son las t2.micro, y el template por default arranca desde las t2.small.

	* **Cecilia N** [573895] (1)

		Es la que va… gracias!

* **Victoria Tejeda** (1) [573355](https://platzi.com/comentario/573355/) 

	Acabo de crear una cuenta en AWS pero cuando accedo a EKS me aparece la siguiente leyenda:
	
	_“SubscriptionRequiredException  
	The AWS Access Key Id needs a subscription for the service”_
	
	¿Necesito hacer un paso adicional?

	* **Carlos Andrés Zambrano Barrera** [573355] (1)

		No necesitas un paso adicional. En todo caso puedes poner un caso a aws por support para que te ayuden. Deberia dejarte crearlo sin problemas.

* **Alvez Gerardo** (1) [58980](https://platzi.com/comentario/584904/) 
No puedo conectarme al cluster creado con kubectl desde mi pc. seguí absolutamente todos los pasos de 

	* **Diego Alexander Forero Higuera (Platzi)** [58980] (3)

		Es un error de permisos, estas usando las credenciales correctas y tienes el archivo de configuración de kubectl bien configurado?

* **Victoria Tejeda** (1) [58239](https://platzi.com/comentario/574582/) 
Cree una cuenta de AWS. Cuando accedo a esta parte para crear el cluster veo que tiene un precio. ¿Esto significa que para continuar con...

	* **Germain Rafael Bueno Taguariparo** [58239] (1)

		Correcto

* **Victoria Tejeda** (1) [58133](https://platzi.com/comentario/573355/) 
Acabo de crear una cuenta en AWS pero cuando accedo a EKS me aparece la siguiente leyenda: “SubscriptionRequiredException The AWS Acc...

	* **Carlos Andrés Zambrano Barrera** [58133] (1)

		No necesitas un paso adicional. En todo caso puedes poner un caso a aws por support para que te ayuden. Deberia dejarte crearlo sin problemas.

* **JerezA** (0) [1003722](https://platzi.com/comentario/1003722/) 

	Prueben creando el EKS via consola adjuntando el user CLI de AWS, una forma sencilla es usando rancher

## 0120. Desplegando una aplicación de prueba con EKS [19473](https://platzi.com/clases/1565-k8s/19473-desplegando-una-aplicacion-de-prueba-con-eks/)

### Descripción:


### Comentarios:

* **Wesly Fernández** (2) [69771](https://platzi.com/comentario/763032/) 
Es recomendable usar la consola de aws para administrar el eks o es mejor usar el eksctl?

	* **Erik Ochoa (Platzi)** [69771] (2)

		Usa aquella con la que te sientes más cómodo, eksctl es un CLI que te puede ayuda a agilizar o incluso automatizar ciertas funciones de la administración de Kubernetes.

* **cmuballesteros** (1) [83133](https://platzi.com/comentario/1020101/) 
hola, al parecer cuando hago todos los pasos todo está bien, pero la página cuando la visito me dice que no está funcionando. veo en el s...

* **Santiago Andres Diaz Villarreal** (1) [61570](https://platzi.com/comentario/623943/) 
Buenas noches, Yo desplegue mi cluster en una vpc, pero los worker nodes los deje en subnet privadas, cuando ejecuto el despliegue de la ...

	* **Diego Alexander Forero Higuera (Platzi)** [61570] (1)

		Revisaste qué el archivo de service en la parte de spec sea de tipo LoadBalancer?

# Primer contacto con un cluster de kubernetes [3900]

## 0130. Usando kubectl [19474](https://platzi.com/clases/1565-k8s/19474-usando-kubectl/)

### Descripción:


 **Kubectl** es la herramienta CLI para interactuar con el cluster de kubernetes, puede usarse para desplegar pods de pruebas, acceder a los contenedores y realizar algunos comandos como `get nodes` o `get services`

En `.kube` es donde se encuentra nuestro archivo `config`, la configuración de kubernetes.

`kubectl get nodes`: lista todos los nodos que tiene nuestro cluster  
`kubectl --config`: puedes pasarle el archivo de configuración en caso de estar usando uno diferente.  
`kubectl --server --user`: especificas la configuración sin necesidad de darle un archivo.  
`kubectl get nodes -a wide`: muestra más datos de los nodos  
`kubectl describe nodes node1`: da mucha información de ese nodo en especifico.  
`kubectl explain node`: permite ver la definición de todo lo relacionado a ese nodo

### Comentarios:

* **Germain Rafael Bueno Taguariparo** (4) [578217](https://platzi.com/comentario/578217/) 

	Algo que llama mi atención acá es que está conectado al servidor de amanazon me parece por medio de ssh y no tomó el tiempo para explicar como hacerlo.  
	A partir de **3\. balanceo de carg y service discovery** esto es necesario y no logro hacerlo.
	
	Sería interesante si nos pudiera ayudar.

	* **Alvez Gerardo** [578217] (2)

		Pudiste conectarte a tu clutter de EKS? Si lo hiciste y podes compartir alguna guía a seguir, te agradezco.

	* **Kevin Santacruz** [578217] (2)

		Hola, la[ clase 11](https://platzi.com/clases/1565-k8s/19472-desplegando-el-cluster-en-aws-con-eks/) Marcos se autentica con las credenciales de aws usando **aws-iam-authenticator** todo el tutorial [aqui](https://docs.aws.amazon.com/eks/latest/userguide/getting-started-console.html#eks-prereqs)

	* **oscar-martinez398** [578217] (1)

		Si, estoy de acuerdo contigo, debió de haber explicado como monto los otros nodos.

* **Germain Rafael Bueno Taguariparo** (2) [58522](https://platzi.com/comentario/578217/) 
Algo que llama mi atención acá es que está conectado al servidor de amanazon me parece por medio de ssh y no tomó el tiempo para explicar...

	* **Alvez Gerardo** [58522] (2)

		Pudiste conectarte a tu clutter de EKS? Si lo hiciste y podes compartir alguna guía a seguir, te agradezco.

* **SergioBernal** (1) [874823](https://platzi.com/comentario/874823/) 

	Muy buen resumen para ser autónomo y ágil en el CLI 💪

## 0140. Creación y manejo de pods [19475](https://platzi.com/clases/1565-k8s/19475-creacion-y-manejo-de-pods/)

### Descripción:


### Links:

* [Play with Kubernetes](https://labs.play-with-k8s.com/)

### Comentarios:

* **rcortesksz** (10) [634716](https://platzi.com/comentario/634716/) 

	Amigos, para los que usan Mac, hay una alternativa a play with kubernetes.  
	<https://callistaenterprise.se/blogg/teknik/2017/12/20/kubernetes-on-docker-in-docker/>
	
	Esto se realiza con Docker in Docker (DinD) que en terminos practicos es que en vez de maquinas virtuales, se usan contenedores. Es básicamente lo mismo que hace play with kubernetes pero deployado en tu máquina.
	
	Ojalá les sirva.

	* **Victorino1675** [634716] (1)

		Excelente aporte, muchas gracias!

	* **Wesly Fernández** [634716] (1)

		Gracias por el aporte!

	* **farrano** [634716] (1)

		Gracias, excelente aporte.

	* **raparisg** [634716] (2)

		Excelente! La versión actualizada del proyecto que mencionas se llama Kind y funciona en Windows y Mac. Lo malo es que consume mucho recurso. En especial RAM. Pero si tienen la posibilidad, está bueno para hacer el curso. La documentación la consiguen acá: <https://kind.sigs.k8s.io/docs/user/quick-start/>

* **Dionisio** (1) [1063465](https://platzi.com/comentario/1063465/) 

	He visto un blog que explica muy bien esta parte por si alguien le interesa:
	
	<https://www.josedomingo.org/pledin/2018/06/recursos-de-kubernetes-pods/>

* **Yully Adriana Gamboa Contreras** (1) [79579](https://platzi.com/comentario/942701/) 
Como hago para borrar los pods creados, o cuando po r jemplo escribi mal el nombre de la imagen antes de crearla. Como libero esos recurs...

	* **Jonnathan Ramiro Juma Jara** [79579] (1)

		kubectl delete pod <podname>

## 0150. Deployments y replica sets [19476](https://platzi.com/clases/1565-k8s/19476-deployments-y-replica-sets/)

### Descripción:


### Comentarios:

* **Super Technologies , S.L.** (2) [600401](https://platzi.com/comentario/600401/) 

	Explicais en el curso los concepto de affinity? Estaria muy bien un tutorial explicando diferentes casos practicos.

* **Super Technologies , S.L.** (2) [60078](https://platzi.com/comentario/600401/) 
Explicais en el curso los concepto de affinity? Estaria muy bien un tutorial explicando diferentes casos practicos.

* **GABRIEL OMAR TARAPUES RODRIGUEZ** (1) [1073870](https://platzi.com/comentario/1073870/) 

	si utilizo un archivo yml con la especificacion del deployment, y luego quisiera obtener el manifest de ese deployment, como lo podria hacer?

* **farrano** (1) [712155](https://platzi.com/comentario/712155/) 

	Excelente curso!

* **Wesly Fernández** (1) [70439](https://platzi.com/comentario/775221/) 
En EKS, se pueden tener varios ingress apuntando al mismo ALB?

# Balanceo de carga y service discovery [3901]

## 0160. Accediendo a nuestros PODS a través de servicios [19477](https://platzi.com/clases/1565-k8s/19477-accediendo-a-nuestros-pods-a-traves-de-servicios/)

### Descripción:


El tipo de servicio en Kubernetes pueden ser de **cuatro** formas diferentes:

* **Cluster IP** : Una IP virtual es asignada para el servicio
* **NodePort** : Un puerto es asignado para el servicio en todos los nodos
* **Load Balancer** : Un balanceador externo es provisionado para el servicio. Solo disponible cuando se usa un servicio con un balanceador
* **ExternalName** : Una entrada de DNS manejado por CoreDNS



### Comentarios:

* **Roger Reyes** (2) [796734](https://platzi.com/comentario/796734/) 

	Parra no tener que copiar o revisar el nombre del POD, podemos tambien seleccionar con label, el primero de todas las replicas y hacer el CURL:
	``` 
	    #Curl al primer POD
	    curl http://$(kubectl get po -l app=httpenv -o jsonpath="{.items[0].status.podIP}"):8888 | jq ""
	    
	    #Curl al service
	    curl http://$(kubectl get service/httpenv -o jsonpath='{.spec.clusterIP}'):8888 | jq ""
	    
	    #Ciclo para revisar el Curl extrayendo cual sea la IP 
	    for i in $(seq 10); do curl -s http://$(kubectl get service/httpenv -o jsonpath='{.spec.clusterIP}'):8888 | jq ".HOSTNAME"; done
	    
	    
	```

* **mauricioacrueda** (1) [832913](https://platzi.com/comentario/832913/) 

	Curso de tmux 😄

	* **Kevin Javier Morales (Platzi)** [832913] (1)

		No es mala idea, gracias por la sugerencia!

* **Germain Rafael Bueno Taguariparo** (1) [576392](https://platzi.com/comentario/576392/) 

	Alguien me puede explicar como eliminó todos los pods de cada unode los nodos?  
	Tengo rato intentando y nada porque si utilizo
	``` 
	    kubectldeletepods <pod> --grace-period=0--force
	    
	```
	
	vuelve a crear el pod

	* **Germain Rafael Bueno Taguariparo** [576392] (1)

		Bueno ya logré hacerlo. Les comparto la información por acña <https://www.adictosaltrabajo.com/2016/04/25/primeros-pasos-con-kubernetes/>
		
		Básicamente debemos eliminar primero Replication Controllers porque es el que se encarga de inciar un pods cuando es eliminado para mantener la cantidad configurada por nosotros.

	* **Eduardo Cárdenas** [576392] (3)

		Con eliminar el deployment se eliminan el resto de resources (service, replicaset, pods):  
		Primero encuentras el nombre del deployment
		``` 
		    kubectl get deployment
		    
		```
		
		Solo en caso de haber creado los pods en algún otro namespace distinto del default agregar `-n NAMESPACE_NAME` al final del comando, de lo contrario omitir este paso.
		
		Una vez tengas el nombre del deployment ejecutar:
		``` 
		    kubectl delete deployment DEPLOYMENT_NAME
		    
		```
		
		Ahora si haces `kubectl get all` ya no verás los demás resources creados para correr el pod.

* **SergioBernal** (1) [75753](https://platzi.com/comentario/875164/) 
Estoy usando por el momento minikube, pero en el 7:25 no puedo acceder directamente al pod a través de la IP.

* **Germain Rafael Bueno Taguariparo** (1) [58393](https://platzi.com/comentario/576392/) 
Alguien me puede explicar como eliminó todos los pods de cada unode los nodos? Tengo rato intentando y nada porque si utilizo kubec...

	* **Germain Rafael Bueno Taguariparo** [58393] (1)

		Bueno ya logré hacerlo. Les comparto la información por acña <https://www.adictosaltrabajo.com/2016/04/25/primeros-pasos-con-kubernetes/>
		
		Básicamente debemos eliminar primero Replication Controllers porque es el que se encarga de inciar un pods cuando es eliminado para mantener la cantidad configurada por nosotros.

## 0170. Enrutando el tráfico utilizando servicios [19478](https://platzi.com/clases/1565-k8s/19478-enrutando-el-trafico-utilizando-servicios/)

### Descripción:


### Comentarios:

* **Cecilia N** (1) [582313](https://platzi.com/comentario/582313/) 

	El NodePort también habilita el puerto en el Master?

	* **Jair Sebastian Lozano Moron** [582313] (2)

		Los master en kubernetes sólo se ocupan de la administración dentro del clúster, por lo que NodePort solo habilita comunicación con los puertos de los workers, ya que estos son los únicos expuestos al exterior.

## 0180. Desplegando nuestra app en k8s [19479](https://platzi.com/clases/1565-k8s/19479-desplegando-nuestra-app-en-k8s/)

### Descripción:


### Links:

* [Docker Hub](https://hub.docker.com/u/dockercoins)

### Comentarios:

* **Alvez Gerardo** (1) [1077055](https://platzi.com/comentario/1077055/) 

	para los que tengan problemas con redis y la webui usen la v2 de la webui en lugar de --image=webui:v0.1 usen --image=webui:v0.2

* **Fernando Lopez** (1) [839443](https://platzi.com/comentario/839443/) 

	Tengo el mismo problema, la webui y el worker no ven al redis. Alguien lo pudo solucionar?

	* **lcmartinez_ (Platzi)** [839443] (1)

		Puedes por favor compartir el error? o darnos mas detalles para poder ayudarte.

* **Abel Corales** (1) [669883](https://platzi.com/comentario/669883/) 

	Buenas,
	
	Tengo un error, a apesar de que expuse todos los puertos, no logra conectarse el worker/webui con el redis:
	
	**_NAME TYPE CLUSTER-IP EXTERNAL-IP PORT(S) AGE  
	hasher ClusterIP 10.98.132.244 <none> 80/TCP 37m  
	kubernetes ClusterIP 10.96.0.1 <none> 443/TCP 23h  
	redis ClusterIP 10.110.240.2 <none> 6379/TCP 23m  
	rng ClusterIP 10.111.109.30 <none> 80/TCP 37m  
	_**
	
	**Me sale los sigientes errores en los logs:**
	
	Logs Worker  
	kubectl logs deploy/worker
	
	**_ File “/usr/local/lib/python3.6/site-packages/redis/client.py”, line 673, in execute_command  
	connection.send_command( _args)  
	File “/usr/local/lib/python3.6/site-packages/redis/connection.py”, line 610, in send_command  
	self.send_packed_command(self.pack_command( _args))  
	File “/usr/local/lib/python3.6/site-packages/redis/connection.py”, line 585, in send_packed_command  
	self.connect()  
	File “/usr/local/lib/python3.6/site-packages/redis/connection.py”, line 489, in connect  
	raise ConnectionError(self. _error_message(e))  
	redis.exceptions.ConnectionError: Error -3 connecting to redis:6379. Try again.  
	ERROR: **main** :Waiting 10s and restarting.___
	
	Logs webui  
	kubectl logs deploy/webui  
	_**  
	Redis error { [Error: Redis connection to redis:6379 failed - getaddrinfo EAI_AGAIN redis:6379]  
	code: ‘EAI_AGAIN’,  
	errno: ‘EAI_AGAIN’,  
	syscall: ‘getaddrinfo’,  
	hostname: ‘redis’,  
	host: ‘redis’,  
	port: 6379 }**_
	
	Logs redis  
	**_  
	1:C 30 Jul 2019 14:35:45.214 # oO0OoO0OoO0Oo Redis is starting oO0OoO0OoO0Oo  
	1:C 30 Jul 2019 14:35:45.214 # Redis version=5.0.5, bits=64, commit=00000000, modified=0, pid=1, just started  
	1:C 30 Jul 2019 14:35:45.214 # Warning: no config file specified, using the default config. In order to specify a config file use redis-server /path/to/redis.conf  
	1:M 30 Jul 2019 14:35:45.218 * Running mode=standalone, port=6379.  
	1:M 30 Jul 2019 14:35:45.218 # WARNING: The TCP backlog setting of 511 cannot be enforced because /proc/sys/net/core/somaxconn is set to the lower value of 128.  
	1:M 30 Jul 2019 14:35:45.218 # Server initialized  
	1:M 30 Jul 2019 14:35:45.218 # WARNING you have Transparent Huge Pages (THP) support enabled in your kernel. This will create latency and memory usage issues with Redis. To fix this issue run the command ‘echo never > /sys/kernel/mm/transparent_hugepage/enabled’ as root, and add it to your /etc/rc.local in order to retain the setting after a reboot. Redis must be restarted after THP is disabled.  
	1:M 30 Jul 2019 14:35:45.218 * Ready to accept connections_**
	
	Me dan una mano??, así continuar
	
	graxx!!

* **Germain Rafael Bueno Taguariparo** (1) [668119](https://platzi.com/comentario/668119/) 

	tengo el mismo error queicolas.

* **Nicolas Diaz** (1) [650700](https://platzi.com/comentario/650700/) 

	Me pasó algo muy extraño.  
	Seguí paso a paso todo y funcionó correctamente HASTA QUE llegué al último paso de conectarse al webui a través de la ip del cluster.  
	No me fue posible conectarme y al darle:
	
	kubectl logs deploy/webui
	
	Apareció el siguiente mensaje de error:
	
	![](https://i.imgur.com/e9FI4hH.png)

	* **Diego Alexander Forero Higuera (Platzi)** [650700] (1)

		Es un problema con la url que esta usando para conectarse a redis, es extraño. No esta funcionando el DNS de kubernetes.

* **jonathan diaz Diaz Diaz** (1) [621468](https://platzi.com/comentario/621468/) 

	😃

* **davanzoivanmatias** (1) [69424](https://platzi.com/comentario/757098/) 
tengo el mismo error: File “/usr/local/lib/python3.6/site-packages/redis/connection.py”, line 489, in connect raise ConnectionError(self....

	* **lcmartinez_ (Platzi)** [69424] (1)

		Puedes revisar si tienes redis instalado y corriendo?
		
		Es posible que no lo tengas corriendo, o puedes correr:  
		`redis-server`

# Escalando nuestra aplicación [3903]

## 0190. Exponiendo servicios interna y externamente (kubectl-proxy) [19480](https://platzi.com/clases/1565-k8s/19480-exponiendo-servicios-interna-y-externamente-kubect/)

### Descripción:


 **kubectl-proxy** es un proxy que corre foreground y nos permite acceder a la API de kubernetes de manera autenticada.

**kubectl port-forward** nos permite realizar lo mismo que kubectl-proxy, pero accediendo a cualquier puerto del servicio expuesto en nuestro cluster

### Comentarios:

* **oscar-martinez398** (1) [76693](https://platzi.com/comentario/891484/) 
¿Como puedo acceder a un node si mi kluster esta en Amazon?

## 0200. Kubernetes dashboard [19481](https://platzi.com/clases/1565-k8s/19481-kubernetes-dashboard/)

### Descripción:


### Links:

* [On Securing the Kubernetes Dashboard – Heptio](https://blog.heptio.com/on-securing-the-kubernetes-dashboard-16b09b1b7aca?gi=4e08c58646ea)

### Comentarios:

* **juan-sebastian-otero** (2) [835673](https://platzi.com/comentario/835673/) 

	En mi caso estoy haciendo el curso con EKS de AWS, existe una documentación oficial de AWS para desplegar el dashbord [Tutorial: Implementación de la interfaz de usuario web de Kubernetes (panel)](https://docs.aws.amazon.com/es_es/eks/latest/userguide/dashboard-tutorial.html)

	* **oscar-martinez398** [835673] (1)

		Gracias C:

	* **oscar-martinez398** [835673] (1)

		Una pregunta, de casualidad sabes como puedo ver la UI de la app, quiero decir, acceder a la UI que corren en Amazon.

* **Pablo Zenteno** (2) [827715](https://platzi.com/comentario/827715/) 

	No me funciono el dashboard y por lo que veo es el mismo dashboard que se levanta al ejecutar minikube dashboard

* **oscarvesga** (1) [1073475](https://platzi.com/comentario/1073475/) 

	Hola a todos, una pregunta; como puedo exponer los puertos en play-with-kubernetes? trato de acceder al dashborad cambiando el tipo de puerto a NodePort y no me aparecen expuestos los puertos.

	* **Alvez Gerardo** [1073475] (1)

		En digital ocean te podes crear una cuenta por 60 días y te dan 100usd de crédito…yo lo hice para este curso… y acá tenes códigos de promociones que a mi me funcionaron… <https://gist.github.com/giansalex/8be8b68dce8f4e2e8dc228cb599a596c> ya que play with k8s no me funcionaba… los recursos de 4vCPU con el cluster cuesta 40usd por mes… es decir con esos créditos estas mas que cubierto.

* **dariovinueza** (1) [1002820](https://platzi.com/comentario/1002820/) 

	Se puede usar Rancher?

## 0210. Balanceo de carga y Daemon sets [19482](https://platzi.com/clases/1565-k8s/19482-balanceo-de-carga-y-daemon-sets/)

### Descripción:


### Comentarios:

* **Jonnathan Ramiro Juma Jara** (1) [74126](https://platzi.com/comentario/847037/) 
MI cluster lo cree con dos maquinas virtuales en gcloud, pero al intentar acceder al dashboard desde la ip externa abro el puerto pero si...

## 0220. Despliegues controlados [19483](https://platzi.com/clases/1565-k8s/19483-despliegues-controlados/)

### Descripción:


### Links:

* [Docker Hub](https://hub.docker.com/u/dockercoins)

### Comentarios:

* **jorgeguega** (1) [672345](https://platzi.com/comentario/672345/) 

	Esta clase es muy buena! Gracias Marcos por esta clase y por el curso, eres un crack! 😉  
	Saludos desde España!

* **rcortesksz** (1) [635219](https://platzi.com/comentario/635219/) 

	Porque en el comando mostrado en el video el parámetro para la imagen nueva se llama worker, cuál es su significado?
	``` 
	    kubectl setimage deploy worker -worker-=nombre_imagen
	    
	```

	* **Diego Alexander Forero Higuera (Platzi)** [635219] (2)

		Lo que indica el comando es lo siguiente: que todos los contenedores de deploy worker se actualicen y asigna a worker la nueva imagen de, entonces solo va a realizar la actualización de worker y va a dejar sin hacer deploy de los servicios de hasher, redis, rng, webui.

## 0230. Healthchecks [19484](https://platzi.com/clases/1565-k8s/19484-healthchecks/)

### Descripción:


 **Healthchecks** es un organismo que tiene kubernetes para saber si nuestra aplicación está funcionando de una manera correcta para saber si debe removerla o reiniciarla al no estar en un estado deseable.

### Comentarios:

* **Omar Alvarez** (4) [621317](https://platzi.com/comentario/621317/) 

	**Liveness **- the kubelet uses these probes as an indicator to restart a container. A liveness probe is used to detect when an application is running and is unable to make progress. When a container gets in this state, the pod’s kubelet can restart the container via its restart policy.
	
	**Readiness **- This type of probe is used to detect if a container is ready to accept traffic. You can use this probe to manage which pods are used as backends for load balancing services. If a pod is not ready, it can then be removed from the list of load balancers.
	
	Types Health Checks:
	
	ExecAction \- executes a command inside the container.  
	++TCPSocketAction +± performs a TCP check against the container’s IP address on a specified port.  
	HTTPGetAction \- performs an HTTP GET request on the container’s IP.

* **SergioBernal** (1) [876977](https://platzi.com/comentario/876977/) 

	Editar manifesto en CLI

# Optimizando el uso de nuestro cluster [3904]

## 0240. Gestionar stacks con Helm [19485](https://platzi.com/clases/1565-k8s/19485-gestionar-stacks-con-helm/)

### Descripción:


Comandos utilizados en la clase:
``` 
    // Instalar helm
    curl https://raw.githubusercontent.com/kubernetes/helm/master/scripts/get | bash
    
    // Verificar si tenemos helm instalado
    helm
    
    // Configurar helm
    helm init
    
    // Verificar si Tiller está instalado
    kubectl get pods -n kube-system
    
    // Dar permisos a helm
    kubectl create clusterrolebinding add-on-cluster-admin --clusterrole=cluster-admin --serviceaccount=kube-system:default
    
    // Buscar paquetes
    helm search
    
    // Ejemplo de cómo instalar un paquete
    helm search prometheus
    helm inspect stable/prometheus | less
    helm install stable/prometheus --set server.service.type=NodePort --set server.persistentVolume.enabled=false
    
    // Obtener servicios
    kubectl get svc
    
    // Crear helm chart
    helm create dockercoins
    cd dockercoins
    mv templates/ templates-old
    mkdir templates
    cd ..
    kubectl get -o yaml --export deployment worker
    
```

### Links:

* [GitHub - helm/helm: The Kubernetes Package Manager](https://github.com/helm/helm)

* [Prometheus - Monitoring system & time series database](https://prometheus.io/)

### Comentarios:

* **Jair Sebastian Lozano Moron** (2) [802538](https://platzi.com/comentario/802538/) 

	me sale el sigueinte error:  
	Error: error installing: the server could not find the requested resource  
	Alguein podria ayudarme con este problema?

* **Oliver Garrido** (1) [1013415](https://platzi.com/comentario/1013415/) 

	Hola, parece que Helm en su nueva versión 3 ya no contiene el argumento ‘init’ ni es necesario ‘Tiller’

* **Juan Emmanuel Díaz** (1) [576011](https://platzi.com/comentario/576011/) 

	`curl https://raw.githubusercontent.com/kubernetes/helm/master/scripts/get | bash`

* **jandrey** (1) [574733](https://platzi.com/comentario/574733/) 

	Falta el script de bash para exportar los services.

	* **Diego Alexander Forero Higuera (Platzi)** [574733] (2)

		Hola, gracias por el reporte, ya se encuentra el script en la pestaña de archivos.

* **Carlos Andrés Garcés González** (1) [573622](https://platzi.com/comentario/573622/) 

	Falta los apuntes

	* **mrsnitro (Platzi)** [573622] (1)

		Hola @cgarcesgo hemos agregado la descripción de la clase. Gracias por reportarlo.

## 0250. Gestionando la configuración aplicativas utilizando Config Maps [19486](https://platzi.com/clases/1565-k8s/19486-gestionando-la-configuracion-aplicativas-utilizand/)

### Descripción:


Tenemos diferentes formas de **configurar** nuestras aplicaciones:

* Argumentos por línea de comandos
* Variables de entorno (env map en el spec)
* Archivos de configuración ( **config maps** )  
– Guardan tanto archivo como valores clave/valor



### Comentarios:

* **jorgeguega** (2) [673539](https://platzi.com/comentario/673539/) 

	Si queréis actualizar el configmap para hacer algún cambio en la configuración, lo podéis hacer con la orden:
	``` 
	    kubectl edit configmap haproxy
	    
	```

* **rcortesksz** (1) [62283](https://platzi.com/comentario/637324/) 
Muy bien explicado el concepto y la aplicación del configmap, pero como validamos la correcta aplicación de configuración dentro del pod/...

	* **Cesar Augusto Ochoa Coronado Ochoa** [62283] (2)

		Entra a la terminal del pod utilizando el comando  
		`kubectl exec -it nombrepod -- /bin/bash`  
		ó  
		`kubectl exec -it nombrepod -- /bin/sh`  
		ya en la consola del pod puedes ver las variables de entorno con el comando  
		`printenv`

## 0260. Volúmenes [19487](https://platzi.com/clases/1565-k8s/19487-volumenes/)

### Descripción:


Un **volumen** nos va a permitir compartir archivos entre diferentes pods o en nuestro host. Estos se usan para que los archivos vivan a lo largo del tiempo y el pod pueda seguir haciendo uso de estos archivos de logs, archivos de configuración o cualquier otro.

**Docker** :

* Permiten compartir información entre contenedores del mismo host
* Permiten acceder a mecanismo de storage
* Docker config y docker secrets



**Kubernetes** :

* Permiten compartir información entre contenedores del mismo pod
* Permite acceder también a mecanismo de storage
* Se utilizan para el manejo de secrets y configuraciones



**Ciclo de Vida**

* El volumen se crea cuando el pod se crea.  
– Esto aplica principalmente para los volúmenes **emptyDir**.  
– Para otro tipo se conectan en vez de crearse.
* Un volumen se mantiene aún cuando se reinicie el contenedor.
* Un volumen se destruye cuando el pod se elimina.



### Comentarios:

* **SergioBernal** (2) [75872](https://platzi.com/comentario/877335/) 
Me he quedado con ganas de saber más sobre persistent volumes, volumes snapshots y storage classes 😥

# Autorización y Namespaces [3905]

## 0270. Introducción a namespaces [19488](https://platzi.com/clases/1565-k8s/19488-introduccion-a-namespaces/)

### Descripción:


### Links:

* [GitHub - jonmosco/kube-ps1: Kubernetes prompt info for bash and zsh](https://github.com/jonmosco/kube-ps1)

### Comentarios:

* **SergioBernal** (1) [877336](https://platzi.com/comentario/877336/) 

	Setear el contexto actual al namespace indicado

* **Omar Alvarez** (1) [625042](https://platzi.com/comentario/625042/) 

	Following are some of the important functionalities of a Namespace in Kubernetes:
	
	* Namespaces help pod-to-pod communication using the same namespace.
	
	* Namespaces are virtual clusters that can sit on top of the same physical cluster.
	
	* They provide logical separation between the teams and their environments.
	
	
	

* **Omar Alvarez** (1) [625038](https://platzi.com/comentario/625038/) 

	**Namespace** provides an additional qualification to a resource name. This is helpful when multiple teams are using the same cluster and there is a potential of name collision. It can be as a virtual wall between multiple clusters.

* **jorgeguega** (1) [64280](https://platzi.com/comentario/673552/) 
Hola a todos, Me surge una duda ¿Es correcto usar diferentes namespaces para los diferentes entornos de desarrollo? Me explico necesitamo...

	* **Carlos Andrés Garcés González** [64280] (1)

		Usando solo un cluster esa sería la alternativa tener dos namespaces uno para cada ambiente y le puedes modificar el network policy para que los pods de un namespace no tengan acceso al otro.

## 0280. Despliegue múltiples instancias de la misma aplicación en un solo cluster. [19489](https://platzi.com/clases/1565-k8s/19489-despliegue-multiples-instancias-de-la-misma-aplica/)

### Descripción:


* Los namespaces no proveen aislación de recursos
* Un pod en un namespace A puede comunicarse con otro namespace B
* Un pod en el namespace **default** puede comunicarse con otro en el **kube-system**



### Comentarios:

* **Jair Sebastian Lozano Moron** (1) [850142](https://platzi.com/comentario/850142/) 

	hola marcos, en tu ejemplo estás utilizando nodeport, por lo que cambiando al nuevo puerto puedes ingresar a la aplicación desplegada en el nuevo namespace, que sucede cuando uno usa un balanceadro de cargas?

## 0290. Autenticación y autorización [19490](https://platzi.com/clases/1565-k8s/19490-autenticacion-y-autorizacion/)

### Descripción:


 **Autenticación** es el método por el cual Kubernetes deja ingresar a un usuario.  
**Autorización** es el mecanismo para que un usuario tenga una serie determinada de permisos para realizar ciertas acciones sobre el cluster.

* Cuando el API server recibe un request intenta autorizarlo con uno o más de uno de los siguientes métodos: Certificados TLS, Bearer Tokens, Basic Auth o Proxy de autenticación.
* Si cualquier método rechaza la solicitud, se devuelve un 401.
* Si el request no es aceptado o rechazado, el usuario es anónimo.
* Por defecto el usuario anónimo no puede hacer ninguna operación en el cluster.



### Comentarios:

## 0300. Service account tokens [19491](https://platzi.com/clases/1565-k8s/19491-service-account-tokens/)

### Descripción:


**Service Account Tokens** es un mecanismo de autenticación de kubernetes y vive dentro de la plataforma, nos permite dar permisos a diferentes tipos de usuarios.

* Existen en la API de kubernetes. `kubectl get serviceaccount`
* Pueden crearse, eliminarse y actualizarse
* Un service account está asociado a secretos `kubectl get secrets`
* Son utilizados para otorgar permisos a aplicaciones y servicios



### Comentarios:

* **Diego Alexander Forero Higuera (Platzi)** (3) [753013](https://platzi.com/comentario/753013/) 

	Otro comando util para obtener el token del usuario admin es  
	`kubectl -n kube-system describe secret $(kubectl -n kube-system get secret | grep admin-user | awk '{print $1}')`

## 0310. RBAC [19492](https://platzi.com/clases/1565-k8s/19492-rbac/)

### Descripción:


 **Role based access control** (RBAC) es un mecanismo de kubernetes para gestionar roles y la asociación de estos a los usuarios para delimitar las acciones que pueden realizar dentro de la plataforma.

* Un rol es un objeto que contiene una lista de rules
* Un rolebiding asocia un rol a un usuario
* Pueden existir usuarios, roles y rolebidings con el mismo nombre
* Una buena práctica es tener un 1-1-1 bidings
* Los Cluster-scope permissions permiten definir permisos a nivel de cluster y no solo namespace
* Un pod puede estar asociado a un service-account



### Comentarios:

* **SergioBernal** (1) [877341](https://platzi.com/comentario/877341/) 

	No he podido instalar CURL
	``` 
	    / # apk add --no-cache curl
	    fetch http://dl-cdn.alpinelinux.org/alpine/v3.11/main/x86_64/APKINDEX.tar.gz
	    WARNING: Ignoring http://dl-cdn.alpinelinux.org/alpine/v3.11/main/x86_64/APKINDEX.tar.gz: temporary error (try again later)
	    fetch http://dl-cdn.alpinelinux.org/alpine/v3.11/community/x86_64/APKINDEX.tar.gz
	    WARNING: Ignoring http://dl-cdn.alpinelinux.org/alpine/v3.11/community/x86_64/APKINDEX.tar.gz: temporary error (try again later)
	    ERROR: unsatisfiable constraints:
	      curl (missing):
	        required by: world[curl]
	    / # curl https://google.com
	    /bin/sh: curl: not found
	    / #
	    
	```

	* **oscarvesga** [877341] (1)

		el WARNING informa que intentes mas tarde, pareciera que el server no pudo descargar los archivos para la instalación. Revisa tu conexión a internet para descartar este problema.

# Fin del curso [3906]

## 0320. Recomendaciones para implementar Kubernetes en tu organización o proyectos [19493](https://platzi.com/clases/1565-k8s/19493-recomendaciones-para-implementar-kubernetes-en-tu-/)

### Descripción:


 **Próximos pasos**

* **Establece una cultura de containers en la organización**  
– Escribir Dockerfiles para una aplicación  
– Escribir compose files para describir servicios  
– Mostrar las ventajas de correr aplicaciones en contenedores  
– Configurar builds automáticos de imágenes  
– Automatizar el CI/CD (staging) pipeline

* **Developer Experience** : Si tienes una persona nueva, debe sentirse acompañada en este proceso de por qué usamos kubernetes y quieres mantener la armonía de ese proceso.

* **Elección de un cluster de producción** : Hay alternativas como Cloud, Managed o Self-managed, también puedes usar un cluster grande o múltiples pequeños.

* **Recordar el uso de namespaces** : Puedes desplegar varias versiones de tu aplicación en diferentes namespaces.

* **Servicios con estados (stateful)**  
– Intenta evitarlos al principio  
– Técnicas para exponerlos a los pods (ExternalName, ClusterIP, Ambassador)  
– Storage provider, Persistent volumens, Stateful set

* **Gestión del tráfico Http**  
– Ingress controllers (virtual host routing)

* **Configuración de la aplicación**  
– Secretos y config maps

* **Stacks deployments**  
– GitOps (infraestructure as code)  
– Heml, Spinnaker o Brigade




### Comentarios:

* **jandrey** (2) [575467](https://platzi.com/comentario/575467/) 

	Donde esta la clase que Marcos menciona sobre CI / CD para gestionar el workflow con git ? 😕

	* **Diego Alexander Forero Higuera (Platzi)** [575467] (3)

		Hola. Vamos a revisar y publicar el contenido lo más pronto posible.

	* **jandrey** [575467] (1)

		Gracias quedo pendiente saludos.

* **julian aguirre Aguirre Romo** (2) [77641](https://platzi.com/comentario/907223/) 
eres el mejor profesor de Dev ops de platzi man, buen curso esperemos hagas pronto uno avanzado

* **Jonnathan Ramiro Juma Jara** (1) [981745](https://platzi.com/comentario/981745/) 

	tengo un error al ejecutar nexus en kubernetes entro a los logs y me dicen permisos denegados para crear directorios, como puedo resolver eso

# Bonus [4078]

## 0330. Clase en vivo workflows de Kubernetes usando git [20370](https://platzi.com/clases/1565-k8s/20370-clase-en-vivo-workflows-de-kubernetes-usando-git/)

### Descripción:


 **GitOps** es una práctica que gestiona toda la configuración de nuestra infraestructura y nuestras aplicaciones en producción a través de Git. **Git** es la fuente de verdad. Esto implica que todo proceso de infraestructura conlleva code reviews, comentarios en los archivos de configuración y enlaces a issues y PR.

* Infraestructura como código
* Mecanismo de convergencia
* Uso de CI como fuente de verdad
* Pull vs Push
* Developers y operaciones(git)
* Actualizaciones atómicas



**GitOps** tomo tanta popularidad en la comunidad de DevOps por el impacto que genera.

* Poder desplegar features nuevos rápidos
* Reducir el tiempo para arreglar bugs
* Generar el sentimiento de control y empoderamiento. Confidencia y control
* 20 deploys por día
* 80% en ahorro del tiempo para arreglar errores en producción



### Links:

* [GitHub - weaveworks/flux: The GitOps Kubernetes operator](https://github.com/weaveworks/flux)

### Comentarios:

* **nutsebap** (1) [944615](https://platzi.com/comentario/944615/) 

	Excelente video

* **SergioBernal** (1) [877348](https://platzi.com/comentario/877348/) 

	Buenisimo! Estos cursos con hands on y prácticas REALES aportan mucho al contexto, y más con procesos tan estándares en la industria

