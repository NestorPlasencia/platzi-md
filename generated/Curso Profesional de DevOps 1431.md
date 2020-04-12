[Curso Profesional de DevOps 1431](https://platzi.com/cursos/devops)

# Introducción [3058]

## 0010. Introducción y Filosofia de DevOps [15644](https://platzi.com/clases/1431-devops/15644-introduccion-y-filosofia-de-devops/)

### Descripción:


### Comentarios:

* **ManuelSLemos** (11) [434987](https://platzi.com/comentario/434987/) 

	Si DevOps no es una persona, ¿Por qué hay tanto empleo y curriculum con el titulo “DevOps”? Opino que DevOps si es una persona o un equipo de personas, los cuales están para mejorar la comunicación entre Operadores y Desarrolladores.
	
	En el curso de Fundamentos de Pruebas se describe DevOps como un rol más del Tester.

	* **Iván Mauricio Toro Cifuentes** [434987] (8)

		DevOps constituye una combinación de filosofías culturales, prácticas y herramientas usadas para mejorar los procesos tradicionales de desarrollo de software [[Fuente](https://aws.amazon.com/es/devops/)]. En mi opinion dichos cargos que mencionas cumplen la función de introducir DevOps en los procesos de la empresa (Como es el caso de Yamil), sin embargo DevOps involucraría a varios roles dentro de la empresa, esa seria mi explicación a lo que dice el profesor, aunque seria genial que lo aclarara el mismo.

	* **estebanvasquezvalencia** [434987] (5)

		Hola Manuel, en parte estoy de acuerdo con tu comentario, ya que es muy común encontrar cargos como DevOps Junior/Senior o Ingeniero DevOps. Creo que va mas orientado a aquellas personas que han adoptado la cultura DevOps en su forma de trabajo y tienen conocimientos en las herramientas que apoyan esta filosofía.

* **Christian Eduardo Ramirez Castillo** (3) [489390](https://platzi.com/comentario/489390/) 

	El pais del “despacito” jajajajaja

* **Jose Marín** (3) [482437](https://platzi.com/comentario/482437/) 

	Perdón, pero soy novato.  
	Que son los operadores?

	* **Ezequiel Maraschio** [482437] (6)

		Son los administradores de sistemas, los que se encargan que el sistema y sus dependencias (tanto de hardware como de software) se encuentren funcionando.

* **Juan35** (2) [531069](https://platzi.com/comentario/531069/) 

	DevOps **no** es un rol, **ni **una herramienta; DevOps es una **cultura** que busca mas colaboración entre los roles de desarrollo y operaciones, ¿por que? Cuando un equipo de desarrollo entrega el proyecto a otro para que lo cuide, es muy facil para ellos por que se desprenden del sistema. Pero lo que busca DevOps es que ambos tengan una responsabilidad compartidad a lo largo de la vida util del software y comparta el mismo dolor del personal de operaciones y asi poder implementar estrategias para simplificar la implementacion o el mantenimiento del sistema y los de operaciones al compartir el mismo dolor del personal de desarrollo puede ayudar a comprender y mejorar todas esas necesidades operativas y ayudarlas a satisfacer.

* **NATALIAGJ** (2) [452409](https://platzi.com/comentario/452409/) 

	Soy nueva en estos temas, que me recomiendan para entender mejor y más rápido el ecosistema que involucra DevOps. Gracias

	* **Edgar Meneses** [452409] (3)

		Hola Natalia también soy nuevo en este tema de DevOps pero te recomendaría que aprendieras temas como Containerización el curso de Docker es muy bueno para eso, temas de integración continua puedes ver cursos sobre jenkins o travis. También te recomiendo que aprendas sobre kubernates, AWS especialmente EKS o si lo prefieres Google Cloud o IBM Cloud, adicionalmente creería que algo de fundamentos sobre administración de servidores.

* **Jose Luis Campos Bautista** (1) [1098638](https://platzi.com/comentario/1098638/) 

	DevOps
	
	* Cultura
	* Automatización
	* Medidas
	* Sharing
	
	

* **grizzlywasright** (1) [1034861](https://platzi.com/comentario/1034861/) 

	Una muy buena introducción para el curso y aprendí que DevOps no es un equipo de personas sino mas bien una cultura en la que hay mas deployments con menos errores

* **asanchez2091** (1) [1025928](https://platzi.com/comentario/1025928/) 

	Váyalo!!!

* **dbzdavidbaez** (1) [1015853](https://platzi.com/comentario/1015853/) 

	A seguir aprendiendo.
	
	DevOps = Operacion + Desarrollo
	
	[DevOps ](https://es.wikipedia.org/wiki/DevOps)

* **edithlopez** (1) [930343](https://platzi.com/comentario/930343/) 

	Buenas Tardes  
	Tengo buenas expectativas frente al curso

* **Luis Alberto Sanchez Barranco** (1) [890533](https://platzi.com/comentario/890533/) 

	Hola tod@s espero aprender mucho de DevOps ya que estoy interesado en esta filosofia, y bueno tambien aprender de cada estudiante

* **cmilianocastiblanco** (1) [594679](https://platzi.com/comentario/594679/) 

	Buenas noches, hay alguna herramienta que pueda usar para realizar pruebas de estres o pruebas de concurrencia en un aplicativo de escritorio desarrollado en .net C# que usa cobol. Gracias

	* **anibalrojas (Platzi)** [594679] (2)

		En principio cualquier herramienta que te permita automatizar la ejecución a nivel de UI te debería servir. Sin embargo el caso de uso que planteas no tiene mucho sentido, creo que en realidad quieres hacer el estrés testing directamente sobre el backend, no sobre la UI donde vas a tener un cuello de botella.

	* **John Eduardo Castillo Rivera** [594679] (1)
Coincido con Aníbal. Si quieres ver experiencia usuario podrías combinar ambos y golpear por un lado el backend mientras automatizas un flujo en el app de escritorio para generar el usuario "n +1" de tu prueba de estrés.

	* **redbeestudios** [594679] (1)

		Hola!  
		Trabajé en pruebas de performance y estress, Lo que tienes que identificar primero es el SBP (sistema bajo prueba), en base a un escenario que pueda ocurrir en la vida real.  
		Por ej, si tu aplicativo de escritorio se conecta con un servidor, seguramente lo haga atravez de HTTP, y utilice servicios Rest.  
		Lo que tienes que haces es imaginar cuantas peticiones pueden llegar a esos servicios y utilziar una herramienta como JMeter (open source de apache) para simular ese comportamiento  
		La herramietna te permitirá elegir una cantidad de usuarios (hilos) que realizan las peticiones que configures (como si fuese postman, simplemente, el host, url, headers, etc)  
		También te dejará elegir una rampa de inicio, lo que significa que esos hilos se crearán durante ese periodo de tiempo.
		
		Imaginando entonces un escenario real. si te llegan habitualmente 100 peticiones por minuto al servidor, deberías realizar una prueba de jmeter configurando:  
		hilos : 100  
		rampa : 600 milisegundos
		
		Si no sabes cuales son las peticiones que realiza la app, necesitas algo como “wireshark” o “fiddler”, para interceptar peticiones http . Mismo Jmeter te puede servir para hacer un record and play, pero nunca lo probé sobre una app de escritorio, sino sobre webs.
		
		Espero que te guie, saludos

* **dcortesnet** (1) [537623](https://platzi.com/comentario/537623/) 

	Yo lo defino en pocas palabras con un automatizador de muchas labores del desarrollo del software ( Sean tanto como planificación y comunicación y velocidad de resultados )  
	Un claro ejemplo es AzureDevOps que trata de juntar todo en 1 sola herramienta, en el se encuentran tableros de Kanvan, flujos de trabajo, repositorios, etc

* **JdavidRomero** (1) [80772](https://platzi.com/comentario/966352/) 
Hola buen día, Una pregunta, para tomar este curso se necesita tener conocimientos previos de alguna(s) herramienta(s) de Devops, cómo lo...

	* **Israel Yance** [80772] (1)

		Preferiblemente sí porque se hace un poco de código y conviene saber ambas herramientas para no estar con las dudas de qué se está haciendo.

* **DAVID OSORIO NIETO** (1) [77204](https://platzi.com/comentario/900195/) 
Hola, dos pregunta. En este curso me sirve para desarrollar proyectos en php, o se basa solo en algún lenguaje de programación? Este cur...

	* **julian aguirre Aguirre Romo** [77204] (1)

		no, prácticamente este curso solo sirve para tener una mini visión superficial de lo q se debería hacer, más no t enseña cómo hacer nada

* **cmilianocastiblanco** (1) [59695](https://platzi.com/comentario/594679/) 
Buenas noches, hay alguna herramienta que pueda usar para realizar pruebas de estres o pruebas de concurrencia en un aplicativo de escrit...

	* **anibalrojas (Platzi)** [59695] (2)

		En principio cualquier herramienta que te permita automatizar la ejecución a nivel de UI te debería servir. Sin embargo el caso de uso que planteas no tiene mucho sentido, creo que en realidad quieres hacer el estrés testing directamente sobre el backend, no sobre la UI donde vas a tener un cuello de botella.

* **Jose Marín** (1) [50702](https://platzi.com/comentario/482437/) 
Perdón, pero soy novato. Que son los operadores?

	* **Ezequiel Maraschio** [50702] (6)

		Son los administradores de sistemas, los que se encargan que el sistema y sus dependencias (tanto de hardware como de software) se encuentren funcionando.

# Containers y ambientes de desarrollo [2955]

## 0020. Ambientes Homogéneos para Applicaciones [15319](https://platzi.com/clases/1431-devops/15319-ambientes-homogeneos-para-applicaciones/)

### Descripción:


Una de las maneras de resolver el _““it works in my machine””_ es teniendo homogeneidad en todos los ambientes. El ejecutar código en nuestra máquina local debe parecerse lo más posible al ambiente de pruebas y producción.

**Docker** es lo recomendado, funciona para todos los sistemas operativos( **WIN10 Pro solamente** ) y es reproducible, podemos tener una infraestructura que comparta todo. Las imágenes son reproducibles, programables y la documentación está en el mismo código.

### Comentarios:

* **Martín Leyva** (4) [434130](https://platzi.com/comentario/434130/) 

	Deploy = Despliegue.  
	Deployable = Desplegable.

* **Iván Mauricio Toro Cifuentes** (3) [436401](https://platzi.com/comentario/436401/) 

	[Curso de fundamentos de Docker.](https://platzi.com/clases/docker/)

* **Jorge López** (2) [443236](https://platzi.com/comentario/443236/) 

	Pareciera que el curso no comenzara en este video, no falta algun video o clase previa?

	* **ricardocelis (Platzi)** [443236] (1)

		hola! la primera clase no se puede ver desde la app móvil, pero ya el team encargado está trabajando en eso, es porque es de YouTube
		
		<https://platzi.com/clases/1431-devops/15644-introduccion-y-filosofia-de-devops6168/>

* **Jose Luis Campos Bautista** (1) [1098645](https://platzi.com/comentario/1098645/) 

	Homogeneidad: los ambientes deben de ser iguales, para ello se puede utilizar Docker.

* **grizzlywasright** (1) [1034863](https://platzi.com/comentario/1034863/) 

	La idea de tener docker para asegurar que independientemente del SO puedan ejecutarse las aplicaciones me hizo explotar la cabeza

* **dbzdavidbaez** (1) [1017624](https://platzi.com/comentario/1017624/) 

	DevOps para simplificar

* **edithlopez** (1) [930349](https://platzi.com/comentario/930349/) 

	Me parece muy internaste lo que se menciona de Docker como configurar estos ambientes

* **Christian Hugo López Bazán** (1) [838052](https://platzi.com/comentario/838052/) 

	Una de las opciones, Docker, como homogeneidad en todos los ambientes.

* **rombj** (1) [755816](https://platzi.com/comentario/755816/) 

	Me interesa mucho este tema, el facilitador tiene mucha calma para explicar y esto me agrada mucho

* **dagaor** (1) [484563](https://platzi.com/comentario/484563/) 

	Espero aprender mucho de este curso, el profesor parece manejar el tema muy bien

## 0030. Implementación de Dockerfile [15321](https://platzi.com/clases/1431-devops/15321-implementacion-de-dockerfile/)

### Descripción:


En esta clase te vamos a mostrar cómo usar un Dockerfile y manejar las dependecias para tenerlas _lock in_ , siempre instalar una versión que ya usaste y probaste.

**FROM** : Busco una imagen de origen y a partir de ahí se monta el container.  
**WORKDIR** : Es recomendable no correr todo el root. Con esto le decimos a Docker cuál va a ser nuestra carpeta de trabajo.  
**ADD** : Es donde indicamos nuestras dependencias como package.json, hace cache de esa capa para no ejecutarla cada que corramos nuestro contenedor. También sirve para copiar, como lo hacemos en la décima línea.  
**RUN** : le decimos a docker que ejecute un comando. En este caso npm install  
**EXPOSE** : Exponemos el puerto 3000  
**CMD** : Acá le decimos a Docker que ejecute este comando al momento de ejecutar nuestro container. En este caso correrá la aplicación.

dockerignore: es casi igual al gitignore, pero para docker.

### Links:

* [https://github.com/elbuo8/platzi-scripts/blob/master/webapp/Dockerfile](https://github.com/elbuo8/platzi-scripts/blob/master/webapp/Dockerfile)

* [Fundamentos de Docker | Materiales](https://platzi.com/clases/docker/)

### Comentarios:

* **Jorge López** (10) [443243](https://platzi.com/comentario/443243/) 

	No es claro el inicio del curso, mezclan muchas temas a la vez, o este es una continuación del curso de Docker?

	* **Iván Mauricio Toro Cifuentes** [443243] (7)

		Creo que este curso es recomendable hacerlo después de terminar el de [docker](https://platzi.com/clases/docker/).

	* **Gabriel Gamboa** [443243] (7)

		En primera instancia, se debe tener en cuenta, como dice Ivan, debes tener conocimiento en docker y todas las tecnologías, porque ese curso no es del uso de una app, sino de la interrelación de varias herramientas para crear un ambiente DevOps

	* **julian aguirre Aguirre Romo** [443243] (1)

		asi sepas docker y kubernetes básico este curso casi no t ayuda en nada de manera práctica, solo t dice el profesor lo q el usa o lo q el sabe de manera hablada.

	* **asanchez2091** [443243] (1)

		Si me parece mejor que te pases por Docker primero.

* **Jorge López** (2) [47466](https://platzi.com/comentario/443243/) 
No es claro el inicio del curso, mezclan muchas temas a la vez, o este es una continuación del curso de Docker?

	* **Iván Mauricio Toro Cifuentes** [47466] (7)

		Creo que este curso es recomendable hacerlo después de terminar el de [docker](https://platzi.com/clases/docker/).

* **Jose Luis Campos Bautista** (1) [1098675](https://platzi.com/comentario/1098675/) 

	```
	    # Buscar imagen origen
	    FROM node:11.1.0-alpine 
	    
	    #Directorio en el que vamos a trabajar
	    WORKDIR/app
	    
	    # 
	    ADDpackage.json package-lock.json /app/
	    RUNnpm install
	    
	    #Configuramos el puerto que se va a exponer
	    EXPOSE3000
	    
	    #
	    ADD. /app
	    #Ejecutar la razon por la cual se ejecuta node es para que se encuentre en el PID 1
	    CMD["node", "index"]
	    
	    
	```

* **asanchez2091** (1) [1026007](https://platzi.com/comentario/1026007/) 

	De los cursos que he realizado en Platzi el de Docker ha sido el más universal de todos. Casi siempre se nombra o se utilizar para algo.

	* **Gabriel De Andrade (Platzi)** [1026007] (1)

		Creo que el [Curso de Postman](https://platzi.com/clases/postman/) está a la par, si no lo has tomado te lo recomiendo muchísimo 😄

* **dbzdavidbaez** (1) [1021371](https://platzi.com/comentario/1021371/) 

	Entendiendo el Dockerfile

* **edithlopez** (1) [930363](https://platzi.com/comentario/930363/) 

	Se manejan algunos conceptos muy de Docker pero al dar una repasada en lo que menciona podemos continuar con el curso

* **Kevin Daniel Fondevila Ricardo** (1) [891911](https://platzi.com/comentario/891911/) 

	no entiendo como habla este profesor

	* **edithlopez** [891911] (1)

		Hay muchos conceptos que maneja de Docker. Es importante conocer un par de cosas antes de continuar con el curso

* **Oswaldo Peralta** (1) [834470](https://platzi.com/comentario/834470/) 

	Para acceder a este proyecto: **<https://github.com/elbuo8/platzi-scripts>**  
	(la carpeta de este curso es webapp)

## 0040. Ambientes Homogéneos para Infraestructura [15320](https://platzi.com/clases/1431-devops/15320-ambientes-homogeneos-para-infraestructura/)

### Descripción:


Podemos hacer infraestructura como código. Tener el equivalente de docker en infraestructura, teniendo la misma configuración en diferentes servidores y regiones, hay varias opciones para realizar esto y una de ellas es **Terraform**.

**Terraform** nos permite escribir código ambiguo que puedo correr en AWS en varias regiones y monta la infraestructura igual en todas ellas. Solo debemos pasarle los parámetros y esto nos permitirá escalar nuestras aplicaciones.

### Links:

* [Terraform by HashiCorp](http://terraform.io)

* [Curso de Digital Ocean Online | Platzi | Materiales](https://platzi.com/clases/digital-ocean/)

### Comentarios:

* **Carlos Augusto Hincapié Romero** (23) [445293](https://platzi.com/comentario/445293/) 

	Profe… se nota que tienes un conocimiento extraordinario… sin embargo creo que deberías estructurar el curso de una forma diferente para que fuera mas accesible a los estudiantes.
	
	  1. Establecer cuales son los conocimientos o cursos previos necesarios para tomar con éxito este curso.
	  2. Presentar durante el curso diagramas del proceso típico de Devops, con el fin de tener una idea previa de cada una de las tareas que un pipeline debería tener.
	  3. Tratar de no mezclar el español y el ingles; dar todo el curso en español o todo el curso en ingles.
	
	
	
	Espero verlo de nuevo en otro curso…

	* **jlazo** [445293] (4)

		Concuerdo en que no se sigue un orden natural, con el fin de comprender DevOps 😦

	* **Diego Alejandro Pelaez Rodriguez** [445293] (0)

		Totalmente de acuerdo con tu comentario

	* **josemdiaza** [445293] (1)

		Acertado

	* **edithlopez** [445293] (1)

		Me parece muy cierto

	* **Antonio Manuel Vallejos Soto** [445293] (1)

		Totalmente de acuerdo, de momento me está resultando un galimatías.

* **hansfpc** (6) [449076](https://platzi.com/comentario/449076/) 

	Sería genial un curso de Terraform 😎

	* **Kevin Javier Morales (Platzi)** [449076] (2)

		Ya hay un curso de Terraform <https://platzi.com/clases/devops-terraform/>

* **Iván Mauricio Toro Cifuentes** (4) [447364](https://platzi.com/comentario/447364/) 

	[Terraform](https://www.terraform.io/)

* **Lele Lester** (2) [1064619](https://platzi.com/comentario/1064619/) 

	En platzi aprender algo rápido te lleva mínimamente 3 cursos, no puede ser.  
	Se nota que el profesor sabe pero no está bien estructurado el contenido y esto pasa en muchos cursos. Hay que mejorar el contenido @platzi

* **edithlopez** (2) [930372](https://platzi.com/comentario/930372/) 

	Interesante la herramienta TerraForm

	* **asanchez2091** [930372] (1)

		quede locoooooo… con Terraform

* **Antonio Manuel Vallejos Soto** (1) [1060597](https://platzi.com/comentario/1060597/) 

	Como se apunta, los conocimientos del profesor son buenos pero el orden es un caos. Además a mí particularmente me molesta sobremanera la conversación tipo hacemos una call para el deployment de la performance y “upgradamos y accesamos” la machine para… es decir, esto de mezclar continuamente palabras en castellano con anglicismos hace que cueste muchísimo seguir que se está diciendo y no tiene sentido ninguno, y más para los que vivimos en España y no estamos acostumbrados a esta mezcla continua y absurda de palabras.

* **asanchez2091** (1) [83477](https://platzi.com/comentario/1027800/) 
Platzi usa Terraform??

	* **Kevin Javier Morales (Platzi)** [83477] (1)

		Es probable que lo usen para este tipo de cosas y levantar infraestructura de manera sencilla. Puedes ver el curso de Terraform acá <https://platzi.com/clases/devops-terraform/>

* **csierra** (1) [69534](https://platzi.com/comentario/758551/) 
Adicional a que trabaja con diferentes Providers, que otras ventajas tendría Terraform sobre Cloud Formation ?

# Pruebas [2956]

## 0050. Implementación de Pruebas [15322](https://platzi.com/clases/1431-devops/15322-implementacion-de-pruebas/)

### Descripción:


### Links:

* [platzi-scripts/index.js at master · elbuo8/platzi-scripts · GitHub](https://github.com/elbuo8/platzi-scripts/blob/master/webapp/test/index.js)

### Comentarios:

* **carmarci** (3) [502809](https://platzi.com/comentario/502809/) 

	He hecho cursos en platzi pero este es el peor de todos con diferencia, empezando que si para el curso hace falta primero tener el curso de dokers, que se indique (pero no en un video dentro del curso), no toda la gente utiliza node.js (tambien hay que hacer el curso de node?), si esto es un curso de intagración continua no hace falta que hagas un ejemplo con node que hay que instalar dependencias etc, hazlo con php y jquery etc etc que seguramente la gente lo comprenderá mejor

	* **Rafael Pardo Rodriguez** [502809] (5)

		Colega, ser un devops es alguien que ya tiene un minimo conociemiento de tecnologias, es este caso Docker o Jenkins.  
		En ningun momento te pide que tomes estos cursos, PERO, si quieres aprender mejor (En este caso solo toma los cursos de docker y jenkins), deberias de hacerlo.  
		Ahora, que escoga node es indeferente al curso, solo sirve para dar el ejemplo.

	* **afnarqui** [502809] (1)
No creo que sea la forma de decir las cosas, soy un convencido que platzi esta haciendo las cosas bien y nosotros como estudiantes lo que debemos de hacer es apostarle a eso y si no estamos de acuerdo tenemos la oportunidad de crear un curso y publicarlo

	* **Rubén Maier Enzler** [502809] (2)

		Igual tiene razón, deberían linkear los cursos previos necesarios para cada curso. En la carrera el orden de secuencia es distinto, figura este antes que el de docker por ejemplo… En lo personal deberían hacer algo así como suelen hacer los youtuber de enlazar cada concepto que dicen con un video aparte perteneciente a una lista de reproducción (curso) distinta.

* **German Luis Guillermo Fica** (3) [488202](https://platzi.com/comentario/488202/) 

	Todavía no entiendo el término de _“batería de pruebas”_ , saludos desde Argentina

	* **eddyarellanes** [488202] (4)

		Es como tal una lista de cosas que vaz a probar.  
		Ejemplo:  
		-Si yo le hago una petición get para obtener cierta información a mi Backend hecho con Express. en mi archivo test.js debo tener una prueba que haga esa petición y me devuelva un code status 200 o no me devuelva un 500. Y la Prueba en este caso se configuró para correr con Mocha.  
		Por decir algo. Saludos!

	* **German Luis Guillermo Fica** [488202] (1)

		Claro! Por lo tanto, “batería de pruebas” es sinónimo de “lista de pruebas”. Buenísimo gracias eddyarellanes!(:

* **Fernando Perez** (1) [531364](https://platzi.com/comentario/531364/) 

	A mi, por el momento, me parece muy bien el curso. Quiero saber que implica ser DevOps y Yamil me aporta su experiencia, que herramientas utiliza y me aconseja y que lo haga con node.js no me crea problema alguno…es un ejemplo.

* **programanime** (1) [453387](https://platzi.com/comentario/453387/) 

	Excelente!!

* **Iván Mauricio Toro Cifuentes** (1) [447389](https://platzi.com/comentario/447389/) 

	[Mocha](https://www.npmjs.com/package/mocha)

* **German Luis Guillermo Fica** (1) [51169](https://platzi.com/comentario/488202/) 
Todavía no entiendo el término de “batería de pruebas”, saludos desde Argentina

	* **eddyarellanes** [51169] (4)

		Es como tal una lista de cosas que vaz a probar.  
		Ejemplo:  
		-Si yo le hago una petición get para obtener cierta información a mi Backend hecho con Express. en mi archivo test.js debo tener una prueba que haga esa petición y me devuelva un code status 200 o no me devuelva un 500. Y la Prueba en este caso se configuró para correr con Mocha.  
		Por decir algo. Saludos!

## 0060. Sin pruebas no hay confianza [15323](https://platzi.com/clases/1431-devops/15323-sin-pruebas-no-hay-confianza/)

### Descripción:


Antes de que entremos a Continuos Integration debemos entrar a la parte fundamental de CI y es hacer pruebas. Sin pruebas no hay confianza.

Nuestro CI necesita pruebas que debe correr de forma automatizada como test unitarios, test de integración y test de aceptación, mínimo es necesario tener las dos primeras.

* **Unit tests** usan _mocks_
* **Integration tests** usan dependencias reales con _fixtures_
* **Acceptance tests** usan un ambiente con todos los servicios, como si fuera producción.



### Comentarios:

* **Martín Leyva** (9) [434157](https://platzi.com/comentario/434157/) 

	**Las pruebas de software** (en inglés software testing) son las investigaciones empíricas y técnicas cuyo objetivo es proporcionar información objetiva e independiente sobre la calidad del producto a la parte interesada o stakeholder. // Wikipedia //
	
	**Unit test:** Prueba unitaria  
	**Integration test:** Prueba de integración  
	**Aceptance test:** Prueba de aceptación  
	**System test:** Prueba de Sistema  
	**Component test:** Prueba de Componente

	* **Iván Mauricio Toro Cifuentes** [434157] (1)

		Buen aporte. [Link](https://es.wikipedia.org/wiki/Pruebas_de_software).

* **Jose Luis Campos Bautista** (1) [1098714](https://platzi.com/comentario/1098714/) 

	Unit test: utilizan mocks  
	Integration test: realizan dependencias reales  
	Acceptance tests: Usan un ambiente con todos los servicios como si fuera producción.

* **edithlopez** (1) [930386](https://platzi.com/comentario/930386/) 

	Es muy ciero que debemos de contar con pruebas porque tal como lo dicen sin pruebas no puede haber confianza

* **carlosmora_biz** (1) [447123](https://platzi.com/comentario/447123/) 

	Como se crea un ambiente de staging?

	* **Carlos Andrés Zambrano Barrera** [447123] (3)

		Depende de donde estes haciendo tu proyecto, por ejemplo en AWS nosotros usamos cloudformation para desplegar los ambientes que separamos en cuentas diferentes (landing zones aws) y para los deployments usamos codepipeline quien despliega en DEV, Approval, STG, Approval, PRD… Y hace rollback automático ante algun error. Te respondo por el lado que trabajes en AWS.

	* **Adrian Camilo Caminos** [447123] (1)

		bueno si utilizas bitbucket desde el mismo pipeline que ofrecen puedes manejar los ambientes que quieras tener, si utilizar gihub mediante los worksflow puedes configurar el stage de acuerdo a la variables de entorno hay que hay que crear un yml por ambiente, en gitlab los puedes hacer por los dos medio.
		
		si utilizas azureDevOps los puedes hacer por la interfaz o mediante el yml e igualmente tienes que tener los yml por ambiente o hacer una configuracion adicional para tener todo en un solo yml.
		
		en AWS puedes usar los mismos dos metodos y agregas una configuracion para que en el proceso genere el stage y haga un deploy de ello

* **carlosmora_biz** (1) [47788](https://platzi.com/comentario/447123/) 
Como se crea un ambiente de staging?

	* **Carlos Andrés Zambrano Barrera** [47788] (3)

		Depende de donde estes haciendo tu proyecto, por ejemplo en AWS nosotros usamos cloudformation para desplegar los ambientes que separamos en cuentas diferentes (landing zones aws) y para los deployments usamos codepipeline quien despliega en DEV, Approval, STG, Approval, PRD… Y hace rollback automático ante algun error. Te respondo por el lado que trabajes en AWS.

# Integración Continua [2957]

## 0070. Continuous Integration y Artifacts [15325](https://platzi.com/clases/1431-devops/15325-continuous-integration-y-artifacts/)

### Descripción:


En este vídeo entramos en la teoría de Continuous Integration.

Con Git hacemos que nuestros cambios en el código queden en una historia que podamos probar antes de pasarlo a la rama master, saber que nuestros test estén pasando con éxito sin romper lo que tenemos en master.

Jenkins es nuestro **automatizador de pruebas** baja la última versión de nuestra rama donde se hizo un cambio y realiza las pruebas que tenemos y si fallan nos previene de romper nuestra rama principal y nos avisa cuáles fueron las pruebas que fallaron para corregirlo.

También podemos hacer un análisis de código, podemos tener algo muy complejo o un estilo que no gusta al equipo y se puede cambiar en esta parte del ciclo y mantenemos _style guide_ bien y código limpio mientras desarrollamos.

Artifacts es nuestra unidad que va a pasar a todos los ambientes, debe ser algo inmutable. Es algo que podemos almacenar por cierta cantidad de tiempo, tal vez un año en caso en de que necesitemos hacer _rollback_.

Los **integration tests** son más productivos, tienen más alcance y tiene más valor.

### Comentarios:

* **Iván Mauricio Toro Cifuentes** (6) [447494](https://platzi.com/comentario/447494/) 

	[Jenkins](https://jenkins.io/)

* **edisoncastro14** (2) [483396](https://platzi.com/comentario/483396/) 

	¿Cuáles herramientas recomiendan para hacer análisis de código en nodejs y en PHP?

	* **Paul Alarcon** [483396] (7)

		Sonarqube

	* **william andres rodriguez borja** [483396] (1)

		tambien te recomiendo sonarqube con lo uso java y funcion muy bien.

	* **Luis Alberto Sanchez Barranco** [483396] (1)

		SonarQube , es free , open source y es muy facil de manejar lo unico es aprender la teoria pero luego ya es mas facil, lo bueno es que permite analizar el codigo fuente php y node.js entre otros para mayor informacion en la pagina web de Sonar <https://www.sonarqube.org>

	* **asanchez2091** [483396] (1)

		sonarq no se si sea libre creo que tienes que pagar

* **edisoncastro14** (2) [50785](https://platzi.com/comentario/483396/) 
¿Cuáles herramientas recomiendan para hacer análisis de código en nodejs y en PHP?

	* **Paul Alarcon** [50785] (7)

		Sonarqube

* **Jose Luis Campos Bautista** (1) [1098753](https://platzi.com/comentario/1098753/) 

	Continuous Integration.
	
	* Código versionado: GIT GITHUB
	* Unit Test/ Integrations Test Servidor de automatización (Jenkins en infraestructura propia)
	* Análisis de código
	* Test Coverage:
	
	

* **AryRosvall** (1) [1085061](https://platzi.com/comentario/1085061/) 

	¿Qué características tiene un init test y un integration test? ¿Cuál es la diferencia entre uno y otro?

	* **hector-arredondo-lugo** [1085061] (1)

		Unit test son pruebas de pequeñas funcionalidades/componentes e integratins test son pruebas de todo el conjunto de componenten (después de que los unit test hayan pasado) y/o la comuniciación entre ellos

* **edithlopez** (1) [958323](https://platzi.com/comentario/958323/) 

	Me parece muy importante que se cumpla cada uno de los procesos y sean cumplido en cada etapa una era de pruebas para así no contar con sorpresas en producción y si no pasa las pruebas es algo que el equipo de desarrollo debe tener en cuenta que no paso en ambiente de preproduccion

* **German Luis Guillermo Fica** (1) [488223](https://platzi.com/comentario/488223/) 

	Muy importante **mantener sanidad** 😂 ( _minuto 3:50_ )

	* **alexpaucar14** [488223] (2)

		Mantener sanidad del código Fuente , le falto completar la oración.

* **asanchez2091** (1) [83582](https://platzi.com/comentario/1030210/) 
Que otros cursos me recomiendan para mejorar lo que veo en este curso.???

	* **Juan David Castro (Platzi)** [83582] (2)

		Los que encuentras aquí: <https://platzi.com/clases/learning-path/servidores/>. 😉

* **jsuperh** (1) [78100](https://platzi.com/comentario/915340/) 
y tambien para java

* **josemdiaza** (0) [717591](https://platzi.com/comentario/717591/) 

	Alguien me puede explicar qué es un artifact? No me quedó claro.

	* **william andres rodriguez borja** [717591] (4)

		te voy a poner un ejemplo para ayudarte.  
		estamos haciendo un api en java y cumplio el ciclo jenkins compila y genera api.jar que contiene todos los documentos de mi api pero enpaquetados ese es mi artifac api-Release v1
		
		o por ejemplo en un frameworks front tu tienes tus carpetas con archivos css y html pero una vez vas a produccion no mandas el codigo fuente mandas el codigo que ya react angular o vue minifica le cambia la estructura comprime imagenes bueno etc etc etc dejandolo listo para produccion una vez esta listo para produccion ya no es tu codigo fuente es un artifact

	* **Luis Alberto Sanchez Barranco** [717591] (1)

		para mi un artifact es el activo (front / back) que vas a publicar en los distintos ambientes (Desarrollo, PreProduccion, Producción), es el paquete listo de tu aplicación para su uso, pero le llamamos artifact pq es el código ya en binario de tu codigo fuente si usas .Net, o si usas algún lenguaje de scripting los minificados , y ese “paquete” lo puedes desplegar en cualquier servidor que creo esa es la idea de CI

	* **Andres Felipe Jacquin Burgos** [717591] (1)

		En mi opinión un artifact (Artefacto), es un paquete completo con todas las funcionalidades de tu desarollo de software, contiene todo ese código ya analizado y probado con el fin de pasarlo a los diferentes ambientes que tengas.

## 0080. Continuos integration y Continuos delivery [16084](https://platzi.com/clases/1431-devops/16084-continuos-integration-y-continuos-delivery/)

### Descripción:
![Curso-devops-platzi.png](https://static.platzi.com/media/user_upload/Curso-devops-platzi-9fb86bb3-88de-4207-9ab3-ab41fca2294a.jpg)

### Comentarios:

* **Omar Alvarez** (12) [478620](https://platzi.com/comentario/478620/) 

	<https://xebialabs.com/periodic-table-of-devops-tools/>
	
	Les comparto una tabla periodica de las herramientas que involucran el tema de CI/CD.
	
	Esta muy bueno !!!

	* **estebanvasquezvalencia** [478620] (5)

		Gracias. Ya la conocía.  
		Por si están interesados en obtener alguna certificación en Devops les comparto el enlace del Devops Institute. Yo soy certificado en Fundamentos.  
		<https://devopsinstitute.com/>

	* **edithlopez** [478620] (1)

		Gracias por la información. Muy buena información

	* **erockerband** [478620] (1)

		Está bastante buena esa info, gracias por compartirla.

	* **Andres Felipe Jacquin Burgos** [478620] (1)

		Gracias por compartirla esta excelente

* **asanchez2091** (1) [1030216](https://platzi.com/comentario/1030216/) 

	Estoy muy emocionado con esto. =)

* **edithlopez** (1) [958376](https://platzi.com/comentario/958376/) 

	Conceptos los cuales no conocía y cada uno de ellos tiene un mundo muy grande por conocer y trabajar mas

* **Emmanuel Diaz** (1) [817168](https://platzi.com/comentario/817168/) 

	¿qué tan sencillo es hacer “rollback” con estas herramientas de una versión desplegada?

	* **Jaime Adalberto Lopez Vivas** [817168] (1)

		en mi experiencia eso depende de varios factores, si por ejemplo tu código puede ser fácilmente reemplazado por una versión anterior sin requerir rollback de cambios fuertes (en base de datos por ejemplo), y si manejas slots, pues ya esta!!!, solo haces un swap y ya tienen la versión anterior de la aplicación

* **coachmarcelo775** (1) [624170](https://platzi.com/comentario/624170/) 

	Excelente

* **Luis Muñoz Diaz** (1) [490281](https://platzi.com/comentario/490281/) 

	cual es mejor circle ci o jenkins??

	* **Rafael Pardo Rodriguez** [490281] (2)

		El que cubra mejor tus necesidades, no existe mejor herramienta

	* **william andres rodriguez borja** [490281] (2)

		circle no require infraestructura tu solo te registras y ya lo puedes empezar a usar a ti te dan ya la infrastructura pero no es gratis mira el plan de precio.  
		[](https://circleci.com/pricing/)
		
		Jenkins es open source lo puedes montar en tu maquina local tu pones la infraestuctura pero pues requiere tiempo y conocimiento para configurarlo. en mi opinion personal jenkins es mas poderoso puedes hacer mas cosas pero es mas complejo comparado con circle.
		
		si quieres algo rapido sin tanta configuracion circle. si tu requerimiento es complejo jenkins. pero en definitiva saber los dos es un plus.

## 0090. Implementación de CI con Jenkins [15324](https://platzi.com/clases/1431-devops/15324-implementacion-de-ci-con-jenkins/)

### Descripción:


### Links:

* [https://platzi.com/clases/jenkins-basico/](https://platzi.com/clases/jenkins-basico/)

* [Fundamentos de Docker | Materiales](https://platzi.com/clases/docker/)

* [platzi-scripts/Jenkinsfile at master · elbuo8/platzi-scripts · GitHub](https://github.com/elbuo8/platzi-scripts/blob/master/webapp/Jenkinsfile)

### Comentarios:

* **jorgehernandezjd** (14) [435729](https://platzi.com/comentario/435729/) 

	Hace falta una veradera ruta de aprendizaje para la carrera de devops, aca se menciona que es necesario haber cursado jenkins pero el curso aun no esta disponible.
	
	Mi recomendacion es que por favor realicen una buena ruta de aprendizaje asi como lo han hecho para backend y frontend
	
	un buen ejemplo seria algo como esto
	
	Ruta para Devops:
	
	  1. Introduccion a Terminal y linea de comandos
	  2. Curso Administracion de Servidores Linux
	  3. Fundamentos de Docker
	  4. Curso de Docker Swarm
	  5. Curso basico de Jenkins
	  6. CUrso de fundamentos de AWS
	  7. Curso profesional de Devops
	
	
	
	Este orden es solo mi apreciacion personal, pero se puede plantear de otra manera y agregarle mas cursos.

	* **Iván Mauricio Toro Cifuentes** [435729] (3)

		Es una buena ruta la que propones.

	* **edithlopez** [435729] (1)

		Me parece muy buena dicha ruta que se menciona

* **Angel Afonso** (3) [601127](https://platzi.com/comentario/601127/) 

	Es posible conectar jenkins con gitlab?

	* **Juan David Castro (Platzi)** [601127] (6)

		 **¡Claro que sí!**
		
		* [Jenkins CI Service | GitLab Docs](https://docs.gitlab.com/ee/integration/jenkins.html)
		* [Trigger a Jenkins build for every push to your GitLab Projects](https://about.gitlab.com/solutions/jenkins/)
		* [How to Integrate GitLab with Jenkins](https://www.youtube.com/watch?v=Jo5SyGL5QN0)
		* [Continuous Integration with Jenkins and GitLab](https://medium.com/@teeks99/continuous-integration-with-jenkins-and-gitlab-fa770c62e88a)
		* [GitLab + Jenkins: una integración de gran alcance](http://elsemanal.es/gitlab-jenkins-una-integracion-de-gran-alcance)
		
		

	* **estuardoramos** [601127] (2)

		es posible, pero GitLab tiene su propio sistema de CI/CD, seria que lo revisaras primero para ver si responde a tus necesidades, puedes revisar el curso de GitLab ahí hablan mas del tema.

	* **Adrian Camilo Caminos** [601127] (2)

		Claro los puedes utilizar en cualquier gestor de versiones, ya seria como agregas la configuracion en tus repos para tomar jenkins

* **Manuel Vargas** (3) [437946](https://platzi.com/comentario/437946/) 

	*yendo a ver el curso de Jenkins*

	* **Iván Mauricio Toro Cifuentes** [437946] (2)

		[Jenkins](https://platzi.com/clases/jenkins-basico/)

* **Germain Rafael Bueno Taguariparo** (2) [473328](https://platzi.com/comentario/473328/) 

	En este momento el indica que debe seleccionar multibranch pipelines pero esa configuración no la vimos en el curso de jenkins por lo que se hace en el item que llama pipilines únicamente. Seguramente en este item se podrá hacer pero a fines educativos peudes seguir esa ruta.

* **Felipe Acosta** (2) [434447](https://platzi.com/comentario/434447/) 

	Aqui hay error del video, Yamil esta describiendo codigo pero en el video no se muestra.

	* **ManuelSLemos** [434447] (2)

		Además te pide el curso de Jenkins que aún no ha salido. Estos fallos marca la diferente entre una plataforma y otra xD

* **Angel Afonso** (2) [60131](https://platzi.com/comentario/601127/) 
Es posible conectar jenkins con gitlab?

	* **Juan David Castro (Platzi)** [60131] (6)

		 **¡Claro que sí!**
		
		* [Jenkins CI Service | GitLab Docs](https://docs.gitlab.com/ee/integration/jenkins.html)
		* [Trigger a Jenkins build for every push to your GitLab Projects](https://about.gitlab.com/solutions/jenkins/)
		* [How to Integrate GitLab with Jenkins](https://www.youtube.com/watch?v=Jo5SyGL5QN0)
		* [Continuous Integration with Jenkins and GitLab](https://medium.com/@teeks99/continuous-integration-with-jenkins-and-gitlab-fa770c62e88a)
		* [GitLab + Jenkins: una integración de gran alcance](http://elsemanal.es/gitlab-jenkins-una-integracion-de-gran-alcance)
		
		

* **Gerardo Alberto Soto Alvarez del Castillo** (1) [1006816](https://platzi.com/comentario/1006816/) 

	Para utilizar el Jenkinsfile también pueden utilizar las pipelines al crear una tarea, en este vídeo se explica como configurarlo desde GitHub:  
	<https://www.youtube.com/watch?v=56jtwSrNvrs>

* **Orlando David Rueda Lobato** (1) [957153](https://platzi.com/comentario/957153/) 

	La verdad ha sido de los peores cursos que he tomado en Platzi. Deberian evaluar mejor el contenido que publican y más en temas tan importantes como DevOps.

* **Orel Hernandez** (1) [893876](https://platzi.com/comentario/893876/) 

	Qué equipo tienes para devops, estoy viendo una mac que versión es ? al igual que tu soy devops de proyectos .net y quiero una mac pero me parece que tu no virtualizas.
	
	Saludos.

* **Augusto Gonzalez** (1) [793117](https://platzi.com/comentario/793117/) 

	Por error instale Java 11 en mi EC2 AWS, sin embargo si funciono el Jenkins, alguien por casualidad sabe si hubo alguna actualizacion?

* **Edgar Valdez Moises** (1) [628049](https://platzi.com/comentario/628049/) 

	Se podría habilitar credenciales, instalar plugins para Jenkins y otras configuraciones al sistema de Jenkins desde código, con el Jenkinsfile ?

* **Raul Villca** (1) [553091](https://platzi.com/comentario/553091/) 

	A alguno le ocurrio esto en mac: ERRO[0000] failed to dial gRPC: cannot connect to the Docker daemon. Is ‘docker daemon’ running on this host?

	* **Raul Villca** [553091] (1)

		Bueno, listo… era una pavada… Me habia olvidado levantar la aplicacion para conectarme a mi contenedores T_T

* **Raul Villca** (1) [545257](https://platzi.com/comentario/545257/) 

	Yo me instale jenkins a traves de docker, en ese caso cuando estoy haciendo el pipeline. Tengo que definir una imagen de docker como agente?  
	O puedo usar una tools con el mvn y la jdk. Lo que pasa que no me cierra un poco, por el tema de que con docker me ahorre todos los pasos de configuración que hacia siempre para la instalación…

* **waldoaraque** (1) [516726](https://platzi.com/comentario/516726/) 

	Si usan kubernetes pueden emplear kibana, es muy bueno!

* **waldoaraque** (1) [516722](https://platzi.com/comentario/516722/) 

	¿Que tal Prometheus?

	* **Jose Almenarez** [516722] (1)

		Es bueno y Opensource lo he instalado pero no le usado de forma seria solo pruebas de conceptos.

* **hansfpc** (1) [449104](https://platzi.com/comentario/449104/) 

	En el repo, no está el directorio install-docker (están los demás, pero ese no)

	* **hansfpc** [449104] (3)

		Se los dejo aquí para quien lo necesite 🙂
		
		`https://github.com/hansfpc/dotfiles/blob/master/scripts/install-docker.sh`

* **Jose Luis Campos Bautista** (1) [86778](https://platzi.com/comentario/1104302/) 
¿Para la práctica de esta clase se crea un Pipeline o un Multibranch Pipeline? La pregunta es que no pude configurar Multibranch Pipeline.

* **asanchez2091** (1) [83586](https://platzi.com/comentario/1030295/) 
foreground??’

	* **Juan David Castro (Platzi)** [83586] (1)

		😉👉 <https://platzi.com/clases/1748-terminal/24400-administracion-de-procesos-en-background-y-foregro/>

* **Manuel Antonio Perez Herrera** (1) [81579](https://platzi.com/comentario/984597/) 
Es una buena practica dejar la información cacheada en Jenkins? Sobretodo al momento de construir imágenes de Docker

* **waldoaraque** (1) [53357](https://platzi.com/comentario/516722/) 
¿Que tal Prometheus?

	* **Jose Almenarez** [53357] (1)

		Es bueno y Opensource lo he instalado pero no le usado de forma seria solo pruebas de conceptos.

## 0100. Implementación de Artifacts con Jenkins [15326](https://platzi.com/clases/1431-devops/15326-implementacion-de-artifacts-con-jenkins/)

### Descripción:


### Links:

* [platzi-scripts/Jenkinsfile at master · elbuo8/platzi-scripts · GitHub](https://github.com/elbuo8/platzi-scripts/blob/master/webapp/Jenkinsfile)

* [](https://hub.docker.com/)

### Comentarios:

* **Iván Mauricio Toro Cifuentes** (5) [448297](https://platzi.com/comentario/448297/) 

	Ruta:  
	Code -> Docker -> Jenkins -> Artifact -> Docker Hub

* **jesus-ruvalcaba-miranda** (2) [79826](https://platzi.com/comentario/947398/) 
Esto es solo mi opinion, no me parece correcto que en un curso por el cual estoy pagando se me indique que investigue como hacer x o y pr...

	* **CarlosAlba** [79826] (3)

		Hola Jesús!
		
		Entiendo tú situación.
		
		Con todo respeto me parece que tomaste la acción correcta. Creo que es más estrategia de aprendizaje. Nuestro cerebro muchas veces necesitas ser “forzado” a buscar y aprender.  
		¿Pero pago para que me den la solución? el argumento como tal es valido. Pero el aprendizaje logrado cuando “descubres” por tus medios no tiene precio.
		
		Saludos!

* **Jose Luis Campos Bautista** (1) [1105058](https://platzi.com/comentario/1105058/) 

	Para crear el acces token en Docker Hub
	
	* Account Settings
	* Security
	* New Access  
	![Captura de pantalla 2020-04-07 a la\(s\) 7.49.34.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202020-04-07%20a%20la%28s%29%207.49.34-13c2103c-6acf-425d-8a30-d56be0a73ae4.jpg)
	
	

* **jandrey** (1) [565432](https://platzi.com/comentario/565432/) 

	Lastima que no s eexplico bien como crear el token y en la documentación explican es como crear un Registry.

* **JoePlatzi2018** (1) [542373](https://platzi.com/comentario/542373/) 

	Alguien tiene alguna referencia para generar el token para el login de DockeHub?

	* **Diego Alexander Forero Higuera (Platzi)** [542373] (2)

		Hola, aquí tienes la documentación oficial <https://docs.docker.com/ee/dtr/user/access-tokens/>

	* **edithlopez** [542373] (1)

		Gracias por la informacion

* **Germain Rafael Bueno Taguariparo** (1) [473514](https://platzi.com/comentario/473514/) 

	Por alguna razón no puedo hacer docker push a mi repositorio.
	
	Ya cree mi repo y modifique el jenkinsfile para aputar a mi repo y nada…
	
	obvio tambien cree las credenciales

	* **Diego Alexander Forero Higuera (Platzi)** [473514] (1)

		Te sale algún error?, qué mensaje te sale, comparte más información para poder ayudarte.

* **Jose Luis Campos Bautista** (1) [86820](https://platzi.com/comentario/1105176/) 
Alguien sabe la razón por la cual el step de publish no entra a la condición when branch master, aunque en mi proyecto solo tenga la rama...

* **JoePlatzi2018** (1) [55518](https://platzi.com/comentario/542373/) 
Alguien tiene alguna referencia para generar el token para el login de DockeHub?

	* **Diego Alexander Forero Higuera (Platzi)** [55518] (2)

		Hola, aquí tienes la documentación oficial <https://docs.docker.com/ee/dtr/user/access-tokens/>

## 0110. Herramientas Externas en proceso de CI [15327](https://platzi.com/clases/1431-devops/15327-herramientas-externas-en-proceso-de-ci/)

### Descripción:


### Links:

* [ Continuous Inspection | SonarQube](https://www.sonarqube.org/)

* [Boost your engineering capacity | Code Climate](https://codeclimate.com/)

### Comentarios:

* **Iván Mauricio Toro Cifuentes** (9) [448308](https://platzi.com/comentario/448308/) 

	CI puede ser tan robusto como lo necesitemos, agregando plugins y software de terceros en general, creo que una buena implementación inicial fue la mencionada por Yamil la clase anterior (Code -> Docker -> Jenkins -> Artifact -> Docker Hub).
	
	Herramientas mecionadas:
	
	* [SonarQube](https://www.sonarqube.org/).
	* [Code Climate](https://docs.codeclimate.com/).
	
	

* **edithlopez** (2) [958901](https://platzi.com/comentario/958901/) 

	Seria muy bueno que al explicar este tipo de herramientas se muestren ejemplos del manejo y uso de las mismas para así entender mas y no quedarnos con los conceptos generales

* **Edgar Valdez Moises** (1) [628078](https://platzi.com/comentario/628078/) 

	Podrían mostrar un ejemplo de configuración con SonarQube u otro ?

# Despliegue Continuo [2958]

## 0120. CD a Ambiente Staging [15328](https://platzi.com/clases/1431-devops/15328-cd-a-ambiente-staging/)

### Descripción:


### Links:

* [platzi-scripts/Jenkinsfile at master · elbuo8/platzi-scripts · GitHub](https://github.com/elbuo8/platzi-scripts/blob/master/webapp/Jenkinsfile)

### Comentarios:

* **Felipe Acosta** (7) [447896](https://platzi.com/comentario/447896/) 

	Creo que como ejercicio de recordacion deberian haber echo la creacion del Job de deploy desde el Jenkins file. 😦

	* **edithlopez** [447896] (1)

		Estoy de acuerdo con el compañero

* **Iván Mauricio Toro Cifuentes** (4) [448337](https://platzi.com/comentario/448337/) 

	[Instalar el plugin de NodeJS en Jenkins](https://platzi.com/clases/1436-jenkins-basico/15634-jenkins-y-su-ecosistema-de-plugins/).

* **Claudio Jesus Vázquez Villanueva** (1) [950906](https://platzi.com/comentario/950906/) 

	Solo retorna el Dockerfile.

* **juan-sebastian-otero** (1) [814304](https://platzi.com/comentario/814304/) 

	[now.sh](http://now.sh) no hace el build 😦 alguien le paso algo similar ?

	* **juan-sebastian-otero** [814304] (1)

		Ya invetigue y [now.sh](http://now.sh) ya no soporta Dockers, hay que hacer el Deployment en otra plataforma.

	* **fermebaz** [814304] (1)

		alguna nueva opción?

* **Damian Perez** (1) [637717](https://platzi.com/comentario/637717/) 

	saben a que se deba este error ?
	
	Using project deploy-webapp-staging  
	┌ ** Ready [172ms]  
	└── Dockerfile
	
	> Ready! Aliased to <https://deploy-webapp-staging>…now.sh [3s]
	
	* RESULT = <https://deploy-webapp-staging-nrqs696qq.now.sh>  
	/tmp/jenkins6768946497624344449.sh: 3: /tmp/jenkins6768946497624344449.sh: RESULT: not found  
	Build step ‘Execute shell’ marked build as failure
	
	

	* **Diego Alexander Forero Higuera (Platzi)** [637717] (1)

		El error muestra que no encuentra algo, esto puede ser que falte configurar algo para que cree ese recurso que esta esperando encontrar.

	* **Damian Perez** [637717] (1)

		era un problema con la variable, pero aun sigue saliendo otro error:
		
		* RESULT_URL=https://deploy-webapp-staging-qz29sd1se.now.sh
		
		* grep 7
		
		* curl <https://deploy-webapp-staging-qz29sd1se.now.sh/add/3/4>  
		% Total % Received % Xferd Average Speed Time Time Time Current  
		Dload Upload Total Spent Left Speed
		
		0 0 0 0 0 0 0 0 --:–:-- --:–:-- --:–:-- 0  
		100 45 0 45 0 0 399 0 --:–:-- --:–:-- --:–:-- 401  
		Build step ‘Execute shell’ marked build as failure  
		Finished: FAILURE
		
		
		

* **Esteban Ramos Fernández** (1) [562358](https://platzi.com/comentario/562358/) 

	100 200 lo que querai

* **hansfpc** (1) [449144](https://platzi.com/comentario/449144/) 

	script:
	
	`echo "FROM $ARTIFACT_ID" > Dockerfile && now -t $NOW_TOKEN`

* **Jose Luis Campos Bautista** (1) [86908](https://platzi.com/comentario/1107768/) 
Al parecer no se instala now, ¿A alguien le paso lo mismo? /tmp/jenkins71868433801483678.sh: 2: /tmp/jenkins71868433801483678.sh: n...

* **juan-sebastian-otero** (1) [72340](https://platzi.com/comentario/814297/) 
now.sh no hace el build solo deja mi Dockerfile, cuando entro a la URL descarga el Dockerfile, alguien le pas...

## 0130. Continous Deployments [15329](https://platzi.com/clases/1431-devops/15329-continous-deployments/)

### Descripción:


Tenemos diferentes maneras de llevar nuestro código a producción. Esta Continuous Delivery y Continuos Deployment, también por supuesto, podemos hacerlo a mano. Esto último no es lo que queremos.

La diferencia entre **Continuos Delivery** y **Continuos Deployment** es bastante sencilla, es el mismo proceso, pero en Continuos Deployment se envía a producción **automaticamente** basado en los resultados de nuestros acceptance tests y en Continuos Delivery podemos hacerlo a mano.

Ninguna es mejor que otra, todo depende de lo qué estés haciendo al momento y las cosas que estés llevando a producción. Si es algo crítico y no hay seguiridad puedes hacerlo de manera manual.

El concepto final es lanzar a producción más frecuente y tener menos errores, la manera implementada es un detalle. El resultado siempre debería ser menos errores.

Hay varios tipos de Deployments:

* **Blue/Green** : Tener dos tags del mismo código dándole update a una de ellas mientras la otra sirve el tráfico.
* **Canary** : Este se puede usar en conjunto con otros tipos. Tenemos un pull de nodos y vamos a implementar algo nuevo pudiendo resultar riesgoso. Solo modifcamos uno de esos nodos.
* **Rolling** : Es hacerle update a máquinas una por una. Son seguros ya que podemos monitorear el progreso.



### Links:

* [Spinnaker](https://www.spinnaker.io/)

* [Open Source Continuous Delivery and Release Automation Server | GoCD](https://www.gocd.org/)

### Comentarios:

* **Iván Mauricio Toro Cifuentes** (6) [448331](https://platzi.com/comentario/448331/) 

	[Articulo relacionado](https://opensource.com/article/17/5/colorful-deployments).
	
	Herramientas mencionadas:
	
	* [Go](https://www.gocd.org/).
	* [Spinnaker](https://www.spinnaker.io/).
	
	

	* **edithlopez** [448331] (1)

		Gracias

* **hansfpc** (2) [449142](https://platzi.com/comentario/449142/) 

	La diferencia entre **Continuos Delivery** y **Continuos Deployment** es bastante sencilla, es el mismo proceso, pero en **Continuos Deployment** se envía a producción **automaticamente** basado en los resultados de nuestros **acceptance tests** y en **Continuos Delivery** podemos hacerlo a mano.

* **edithlopez** (1) [976997](https://platzi.com/comentario/976997/) 

	Al manejar este proceso Continuos Deployment el cual se envía a producción automáticamente. Si confiamos en cada uno de sus procesos nos rinde mucho es sacar grandes cosas pero si en producción contamos con errores debemos asumir muchos riesgos tanto con el equipo como nuestros clientes

## 0140. Implementar acceptance tests en Jenkins [15330](https://platzi.com/clases/1431-devops/15330-implementar-acceptance-tests-en-jenkins/)

### Descripción:


### Comentarios:

* **Iván Mauricio Toro Cifuentes** (3) [448566](https://platzi.com/comentario/448566/) 

	[Recurso relacionado](https://openclassrooms.com/en/courses/4544611-write-agile-documentation-user-stories-acceptance-tests/4810081-writing-acceptance-tests).

* **Adrian Vega** (2) [505800](https://platzi.com/comentario/505800/) 

	En el comando de prueba se puede realizar tests tan complejos y largo como se requiera para saber si esta correcta la build?

	* **waldoaraque** [505800] (1)

		si… Puedes escribir tantos test quieras, depende de las necesidades que tengas.

* **hansfpc** (2) [449148](https://platzi.com/comentario/449148/) 

	`echo "FROM $ARTIFACT_ID" > Dockerfile`  
	`RESULT_URL=$(now -t $NOW_TOKEN)`
	
	`# Acceptance test`  
	`curl $RESULT_URL/add/3/4 | grep 7`

* **asanchez2091** (1) [1034425](https://platzi.com/comentario/1034425/) 

	Jenkins se ve brutalmente poderoso pero la interfaz es media federica.  
	Existe la posibilidad de montar a su vez otro servicio visualmente más atractivo que lo consuma???

	* **Jeisson Sierra** [1034425] (0)

		Gitlab, es muy bueno, tiene las mismas bases de Jenkins ademas que no es necesario realizar tantas integraciones con otros servicios terceros.

* **Adrian Vega** (1) [52471](https://platzi.com/comentario/505800/) 
En el comando de prueba se puede realizar tests tan complejos y largo como se requiera para saber si esta correcta la build?

## 0150. Completar Pipeline de CD [15331](https://platzi.com/clases/1431-devops/15331-completar-pipeline-de-cd/)

### Descripción:


### Comentarios:

* **Iván Mauricio Toro Cifuentes** (4) [448564](https://platzi.com/comentario/448564/) 

	Los **acceptance test** deben correr en el ambiente de staging y el de producción.
	
	“ _Testear todos los ambientes, en todo momento_ ”.

* **edithlopez** (1) [977011](https://platzi.com/comentario/977011/) 

	La visualización y el proceso que se puede observar en Console Output me parece excelente ya que podemos manejar en tiempo real como va el proceso y la respuesta que nos debe arrojar y en caso que no pase nos logra indicar en que parte tenemos el error

* **hansfpc** (1) [449155](https://platzi.com/comentario/449155/) 

	¿Alguien lo hizo como Jenkinsfile que pueda compartir su solución? 🙏🏻

	* **waldoaraque** [449155] (1)

		Puedes agregar un _stage_ en el _Jenkinsfile_ dónde puedes escribir los test… algo así:  
		…  
		stage(‘testing’){  
		container(‘node’){  
		npm test  
		}  
		}  
		…

	* **waldoaraque** [449155] (1)

		puedes ver más detalladamente aquí: <https://jenkins.io/solutions/pipeline/>

# Reliability [2959]

## 0160. Introducción a Incident Response [15337](https://platzi.com/clases/1431-devops/15337-introduccion-a-incident-response/)

### Descripción:


### Links:

* [PagerDuty Incident Response Documentation](https://response.pagerduty.com/)

* [Auth0 Status - Elevated error rates with authentication](https://auth0.statuspage.io/incidents/kqnzg2wm5jw0)

* [What is an Incident Post-Mortem? | Articles | PagerDuty](https://www.pagerduty.com/resources/learn/post-mortem-incident-report/)

* [Auth0 Status - Elevated Error Rates](https://auth0.statuspage.io/incidents/vbfz8x03tf04)

### Comentarios:

* **Iván Mauricio Toro Cifuentes** (5) [448632](https://platzi.com/comentario/448632/) 

	**Que hacer cuando suena el teléfono** :
	
	  1. Mide el alcance del error (Mide el impacto del error).
	  2. Comunícate con el cliente y compañeros.
	  3. Escribe un [postmortem](https://landing.google.com/sre/sre-book/chapters/postmortem-culture/).
	
	

* **cmuballesteros** (1) [1014192](https://platzi.com/comentario/1014192/) 

	Muy buenos concejos, te agradezco todo.

* **edithlopez** (1) [977020](https://platzi.com/comentario/977020/) 

	El documentar el proceso y los incidentes que pasan me parece que es muy importante en las compañías porque como lo menciona el profesor si llega uno nuevo al caso y se esta tardando mas de lo esperado ya esta documentado todo el proceso que hiciste y en ocasiones las imágenes también son importantes en este proceso de documentar

## 0170. Introducción a Reliability - SLOSLI [15332](https://platzi.com/clases/1431-devops/15332-introduccion-a-reliability-slosli/)

### Descripción:


Site Realiability Engineering: Es como las compañías miden internamente que su productos está bien.

Esto nos permite medir nuestro success. **SLI: Serivece Level Indicators** podría ser la cantidad de errores, latencia, tiempo de enviar un email, tiempo de contestar un path especifico en nuestro API. Y el **SLO: Service Level Objectives** es la métrica, que nuestra latencia sea menor de 50ms en un espacio de 5 minutos todo el mes.

### Links:

* [Google - Site Reliability Engineering](https://landing.google.com/sre/books/)

### Comentarios:

* **fermebaz** (3) [918183](https://platzi.com/comentario/918183/) 

	Estaría muy bien un curso de SRE 😉 😄

	* **edithlopez** [918183] (2)

		Seria muy interesante

* **Iván Mauricio Toro Cifuentes** (3) [448577](https://platzi.com/comentario/448577/) 

	“ _Hope is not a strategy_ ”.
	
	* [Fuente](https://landing.google.com/sre/sre-book/chapters/introduction/).
	
	

* **Rafael Pardo Rodriguez** (1) [727822](https://platzi.com/comentario/727822/) 

	El libro se puede comprar, de manera fisica o kindle, solo es “gratis” para leerlo online.

## 0180. Implementar Uptime Monitoring [15333](https://platzi.com/clases/1431-devops/15333-implementar-uptime-monitoring/)

### Descripción:


Si vamos a medir nuestro **Uptime** como un indicador de **SLO y SLI** deberías usar un proveedor externo para tener la métrica interna y externa.

Ambas herramientas tanto Pingdom y Ping setean infraestructura en todo el mundo y luego llaman a la dirección que le digamos para verificar si estamos disponibles en cada parte. También nos dicen cuánto tardo en responder nuestro producto o website.

### Links:

* [Website Performance and Availability Monitoring | Pingdom](https://www.pingdom.com/)

* [Apex Software](https://apex.sh/)

### Comentarios:

* **AryRosvall** (1) [1087057](https://platzi.com/comentario/1087057/) 

	Yo uso Pingdom en mi trabajo y es bastante bueno, tiene integraciones con Slack, SMS e Email y permite escalar a varios grupos dependiendo del tiempo que esté abajo el servicio. Tiene varias funcionalidades útiles para monitoreo, incluso puedes hacer tus propios scripts y que Pingdom monitoree el resultado.

* **edithlopez** (1) [81331](https://platzi.com/comentario/979067/) 
Las herramientas de Uptime Monitoring son herramientas todas paga. Existe alguna buena free

	* **kagure** [81331] (1)

		Puedes crearte una tu mismo o tomar como ejemplo algunas que hay libres y modificarlas un ejemplo aquí.  
		podrías hacer en cualquier lenguaje o utilizar nagios es una buena opción.  
		<https://github.com/danawoodman/python-uptime-monitor>  
		<https://motoma.io/basic-server-monitoring-with-python/>

## 0190. Exception Trackers y Logs [15334](https://platzi.com/clases/1431-devops/15334-exception-trackers-y-logs/)

### Descripción:


Es importante tener **estructura** en nuestros logs para poder parsear. En esta clase veremos algunos ejemplo de este tipo de structure logging. También es importante hacer uso de los Levels en los logs, tanto info, warning, error, fatal.

Los Exception Trackers, un **exception** sabemos que es un error que no esta manejado en nuestro código y debería tener un lugar especial para arreglarlo lo más rápido posible. Hay varias soluciones para este tipo de problemas, **Sentry** es recomendado y nos permite enviar nuestro exception hacia ellos y colocar reglas. Podemos hacer que nuestro teléfono suene para arreglarlo si es algo urgente.

### Links:

* [Sentry | Error Tracking Software â?? JavaScript, Python, PHP, Ruby, more](https://sentry.io/welcome/)

### Comentarios:

* **eddyarellanes** (2) [504939](https://platzi.com/comentario/504939/) 

	Para NodeJs me gusta usar winston  
	<https://github.com/winstonjs/winston>

* **jescobarf** (1) [662026](https://platzi.com/comentario/662026/) 

	Es una buena practica tener estructurados los logs.

* **Iván Mauricio Toro Cifuentes** (1) [448601](https://platzi.com/comentario/448601/) 

	[PinoJS](https://github.com/pinojs/pino)

* **edithlopez** (1) [81333](https://platzi.com/comentario/979093/) 
¿Debemos también colocar errores que se solucionan en menos de 10 minutos ?

## 0200. Métricas [15336](https://platzi.com/clases/1431-devops/15336-metricas4200/)

### Descripción:


En la clase anterior se menciona que hay ciertas opiniones acerca de los logs. Los Logs es cuando todo salió mal y no tengo otra manera de saber qué pasó.

Por eso las **métricas** nos ayudan a tener una visualización, un dashboard de nuestro servicios, pudiendo ver nuestros errores y hacer comparaciones, ver la frecuencia, los picos, latencia, una llamada a la base de datos.

### Links:

* [Modern monitoring & analytics | Datadog](https://www.datadoghq.com/)

### Comentarios:

* **asanchez2091** (1) [1042875](https://platzi.com/comentario/1042875/) 

	Wau spanglish

* **edithlopez** (1) [979114](https://platzi.com/comentario/979114/) 

	Me parece que las Metricas juegan un papel muy importante y al saberlos usar es bastante interesante lo que se muestra

* **Iván Mauricio Toro Cifuentes** (1) [448617](https://platzi.com/comentario/448617/) 

	[Datadog (Wikipedia)](https://es.wikipedia.org/wiki/Datadog).

* **Jonnathan Ramiro Juma Jara** (1) [75724](https://platzi.com/comentario/874589/) 
Podrían agregar como implementar varios tipos de herramientas para monitorio.

	* **Gerardo Alberto Soto Alvarez del Castillo** [75724] (1)

		Una de tantas herramientas para monitorear servidores es Munin y cuenta con varios Plugins:  
		<http://munin-monitoring.org/>  
		Ejemplo de como utilizarlo:  
		<https://www.youtube.com/watch?v=9LZfjg9KE9Y>

# Cierre del curso [2960]

## 0210. Conclusiones [15338](https://platzi.com/clases/1431-devops/15338-conclusiones4102/)

### Descripción:


### Comentarios:

* **Iván Mauricio Toro Cifuentes** (3) [448633](https://platzi.com/comentario/448633/) 

	Gracias por el curso Yamil. 😄

* **Yuri Daza** (2) [644105](https://platzi.com/comentario/644105/) 

	Muy chevere el curso, quizás no profundizas en todas las herramientas que se ven, pero entiendo que esta es la información base para seguir aprendiendo de DevOps. Gracias !!

* **hector-arredondo-lugo** (1) [1101375](https://platzi.com/comentario/1101375/) 

	Senti que era mas curso de “Jenkings” que de devops, pero igual esta bien

* **AryRosvall** (1) [1087591](https://platzi.com/comentario/1087591/) 

	Me gustó mucho este curso, especialmente porque me sensibilizó como desarrolladora de lo que tiene que hacer un devops y de cómo yo puedo contribuir a mejorar la calidad del código y de la estabilidad del ambiente de producción. Lo sentí muy general para llamarse curso profesional pero me llevo mucho conocimiento.

* **asanchez2091** (1) [1042880](https://platzi.com/comentario/1042880/) 

	El curso estuvo excelente aunque es complejo a pesar de que Platzi lo suavizo bastante.

* **Gerardo Alberto Soto Alvarez del Castillo** (1) [1014470](https://platzi.com/comentario/1014470/) 

	Gracias por el curso Yamil y Platzi, me pareció muy interesante todos los temas, aunque deberían de profundizar en mas herramientas para Jenkins y más actualizadas.

* **cmuballesteros** (1) [1014287](https://platzi.com/comentario/1014287/) 

	muy buen curso, pero creo que no sé si en algo más profundo se debería abordar blue ocean, el mejor plugin de Jenkins…

* **edithlopez** (1) [979143](https://platzi.com/comentario/979143/) 

	Gracias por el curso

* **Jonnathan Ramiro Juma Jara** (1) [874592](https://platzi.com/comentario/874592/) 

	Excelente curso

* **esdraspavon** (1) [759631](https://platzi.com/comentario/759631/) 

	Muchas gracias Yamil!

* **angelg** (1) [625481](https://platzi.com/comentario/625481/) 

	Muy buen curso Yamil, gracias por compartir tu experiencia.

* **jhonsfran90** (1) [524570](https://platzi.com/comentario/524570/) 

	Muchas gracias estuvo muy bueno.

* **programanime** (1) [453537](https://platzi.com/comentario/453537/) 

	Excelente!!

* **TeamQA** (0) [891734](https://platzi.com/comentario/891734/) 

	Excelente curso, muchas gracias

