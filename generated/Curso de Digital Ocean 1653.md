# Introducción a Digital Ocean y las IaaS

## 0010. ¿Qué es Digital Ocean

### Descripción:


La “nube” son sólo servicios a los que tienes acceso a través de Internet, existen tres categorías:

  * SaaS: Software as a Service.
  * PaaS: Platform as a Service.
  * IaaS: Infrastructure as a Service.



Digital Ocean es una solución de infraestructura muy bien documentada que entra en la categoría _IaaS_ y tiene precios competitivos además de permitir métodos de pago como PayPal.

### Comentarios:

* **juancajamarca** (9)

	
	¿Qué es Digital Ocean? Antes de hablar de Digital Ocean, hay que hablar de la nube.  
	La nube son servicios a los que se accede a través de internet utilizando un navegador. Dentro de la nube existen tres categorías:
	
	  * SaaS: Software as a Service
	  * PaaS: Platform as a Service
	  * IaaS: Infrastructure as a Service (Aquí entra Digital Ocean)
	
	
	
	¿Qué es la infraestructura como servicio?  
	Es básicamente cuando se rentan equipos en internet, servidores específicamente o máquinas virtuales las cuales tienen unas características de Hardware que el usuario puede administrar; como por ejemplo, memoria RAM, Almacenamiento de Disco Duro, ancho de banda, procesador, etc.
	
	Para este caso, Digital Ocean es una solución de infraestructura en la nube que tiene varias ventajas:
	
	  * Tiene precios competitivos y permite usos por hora
	  * Tiene muy buena documentación para que los desarrolladores se puedan guiar a la hora de implementar sus soluciones en la nube.
	
	

* **Sebastián Córdoba Omen** (8)

	
	**Software-as-a-Service (SaaS): **  
	Todo el desarrollo, mantenimiento, actualizaciones, copias de seguridad es responsabilidad del proveedor, es decir, si el servicio se cae es responsabilidad del proveedor volver a hacer que funcione.  
	**Ejemplos :** El Webmail de Gmail, Google Docs, Salesforce, Dropbox
	
	**Platform-as-a-Service (PaaS):**  
	Nuestra única preocupación es la construcción de nuestra aplicación, ya que la infraestructura nos la da la plataforma, pero también debemos centrarnos en que estén lo mejor optimizadas posibles para consumir menos recursos posibles.  
	**Ejemplos:** Google App Engine, Heroku
	
	**Infraestructure-as-a-Service (IaaS):**  
	Tendremos mucho más control que con PaaS, pero deberemos encargarnos de la gestión de infraestructura,escalar nuestras aplicaciones según nuestras necesidades, además de preparar todo el entorno en las maquinas.  
	**Ejemplos:** Amazon Web Service (AWS)

	* **ddragaid** (2)

		
		Otro ejemplo que esta muy a la par es Azure

* **Oz** (3)

	
	Brutal

* **Christian Hugo López Bazán** (2)
Es similar a AWS o AZURE? Es decir, brinda varios servicios como AWS o AZURE?

	* **Erik Ochoa (Platzi)** (1)

		
		Así es, son similares pero Digital Ocean te ofrece una mayor simplicidad al momento de desplegar tus servidores virtuales.

* **dbzdavidbaez** (1)

	
	A seguir aprendiendo sobre la nube

* **Miguel Ángel Bocanegra** (1)

	
	READY

* **xergioalex** (1)

	
	Sin duda la documentación de Digital Ocean es de las mejores que se pueden encontrar en la web relacionadas con temas de infraestructura 💪.

	* **xergioalex** (10)

		
		En este gráfico se detallan los recursos que gestionas tu o tu proveedor en los diferentes modelos de computación en la nube:
		
		![Selection_117-5d6064b1-a118-4382-81ea-8f0ee6854b78.jpg](https://static.platzi.com/media/user_upload/Selection_117-5d6064b1-a118-4382-81ea-8f0ee6854b78-173c0889-ea24-4ad8-b8b3-40c80cd5c069.jpg)

	* **Santiago Bernal** (1)

		
		Muchas gracias por compartir la imagen, esto complementa el concepto de computación en la nube.

* **darwinyusef** (1)

	
	soy el primero jajaja 😄

## 0020. ¿Cuándo usar Digital Ocean

### Descripción:


Existen varias opciones para llevar nuestro proyecto a Internet:

  * **Hosting gratis** : no se puede administrar el hardware, sirve para aproximadamente una decena de usuarios, está muy limitada y puede contener publicidad.
  * **Shared Hosting** : no se puede administrar el hardware, tienen un poco más de potencia pero normalmente vienen limitados a la arquitectura LAMP (Linux, Apache, MySQL y PHP).
  * **VPS (Virtual Private Server)** : es un dispositivo virtual donde si puedes administrar el hardware (de forma virtual), sirve para miles de usuarios o más al mes.
  * **Dedicado** : maquina física donde todos los recursos están dedicados para nuestra aplicación con la desventaja de que no es tan fácil aumentar recursos cómo almacenamiento, memoria RAM, etc. Sirve para miles o cientos de miles de usuarios al mes.
  * **Cloud (PaaS/IaaS)** : solución de tipo VPS donde podemos administrar nuestros recursos de hardware, tener múltiples servidores como: servidores web, servidores de bases de datos, balanceadores de carga, firewalls, etc. Aquí entra Digital Ocean.
  * **Datacenter** : cuando ya se llega a millones de usuarios esto es una opción pero tiende a ser muy costosa.



Digital Ocean es útil cuando necesitamos una solución de VPS, que permita administrar recursos de hardware e ir creciendo a medida de forma fácil y rápida.

### Links:

* [AWS vs. DigitalOcean: Which Cloud Server is Better - By DashMagazine](https://hackernoon.com/aws-vs-digitalocean-which-cloud-server-is-better-1386499a6664)

### Comentarios:

* **juancajamarca** (5)

	
	¿Cuándo utilizar Digital Ocean?
	
	Existen ciertos tipos de escenarios en donde, dependiendo del tráfico o de la cantidad de usuario, se necesitará cierta solución u otra.
	
	  * Hosting gratis: Cuando se despliega una aplicación en internet, se puede empezar con un Hosting gratuito, que sería la solución ideal si se tiene una decena de usuarios al día o al mes. Esta solución tiene una desventaja, que es que no permite acceder al hardware del servidor en donde está desplegada la aplicación, aparte de que es limitada y puede que aparezca publicidad.
	
	  * Shared Hosting: Esta solución brinda un poco más de hardware para desplegar aplicaciones, pero como en la solución anterior, también esta es limitada porque no permite administrar los recursos físicos del servidor y además que no permite instalar cualquier herramienta para correr las aplicaciones. Normalmente sólo cuenta con la arquitectura LAMP (Linux, Apache, MySQL y PHP).
	
	  * VPS (Virtual Private Server): Esta solución brinda una máquina virtual con recursos físicos administrables, y además, brinda la libertad de poder instalar cualquier herramienta para poder instalar la aplicación a desplegar. Esta solución es ideal cuando se tienen miles o decenas de miles de usuarios al mes.
	
	  * Servidor dedicado: Esta solución brinda una máquina física en donde todos sus recursos están dedicados sólo para la aplicación que se vaya a desplegar. Esta solución tiene una desventaja, y es que no se puede ampliar los recursos mientras el servidor está funcionando; es decir, es necesario apagarlo para poder ampliarlos. Esta solución es necesaria cuando se tienen decenas de miles o cientos de miles de usuarios al mes.
	
	  * Cloud (Paas/Iaas): Cuando la aplicación crece, se necesitará trabajar con una infraestructura, ya sea física o en la nube, en donde se tendrán servidores para balanceados de carga, servidores web, servidores de bases de datos, servidores de firewall; varios servicios para hacer funcionar la aplicación.
	
	  * Datacenter: En caso de tener millones de usuario o decenas de millones de usuarios al mes, es ideal tener esta solución, un propio datacenter.
	
	
	
	
	Visto todo lo anterior, ¿cuándo es útil Digital Ocean? Digital Ocean es muy útil cuando se necesita una solución de tipo VPS, en donde se necesita administrar los recursos de hardware y se necesita ir creciendo a medida que avanza el proyecto. En este caso, Digital Ocean facilita mucho esta tarea.
	
	Otras soluciones en la nube como AWS, Azure o Google Cloud Platform son más especializadas porque tienen una mayor cantidad de servicios, pero son más enfocadas a personas con el rol de DevOps (conocen más de infraestructura); mientras que Digital Ocean, es más enfocada a desarrolladores.

	* **Miguel Angel Escurra** (2)

		
		Excelent!!

	* **Luis Emmanuel Rodas Camposeco** (1)

		
		Muchas gracias

* **Alan Cabrera Alan Cabrera Hernandez** (1)

	
	últimamente en videos de youtube veo q una empresa llamada de upcloud patrocina muchos youtubers q lo recomiendan, se dice ser una alternativa a digital ocean con mejor performance y precio, ¿alguien la usado?

* **dbzdavidbaez** (1)

	
	Entendido.

* **Christian Hugo López Bazán** (1)

	
	Interesante, no había escuchado de Digital Ocean, haré las pruebas de mis desarrollos con los servicios de Digital Ocean.

* **Miguel Ángel Bocanegra** (1)

	
	ok

* **rombj** (1)

	
	Yo compré el de 5 dolares por mes y ando teniendo problemas para subir mi sitio, estoy algo perdido con esto, espero con el curso poder entender y manejarlo a mi antojo 😄

* **silviocondori** (1)

	
	He implementado algunos proyectos en Vultr me gusto su soporte, ahora inicie con Digital Ocean y cada ves me esta gustando mas debido a que veo mejores opciones de trabajo.

* **Alexis Otaño** (1)

	
	Yo comence haciendo deploy sobre Digital Ocean’s y la verdad que no ha quedado mal, funciona muy bien, y aunque no probé el tier gratis, si el tier de $5 dolares al mes, lo cual es nada por un server que llego a funcionar perfecto para efectos de pruebas.

	* **Santiago Bernal** (1)

		
		Así es, Digital Ocean es una muy buena opción para empezar a desplegar un proyecto, ya sea de forma profesional o por hobby

* **ironcap** (1)
¿Recomiendas usar DigitalOcean para un blog que apenas voy a publicar? (no tengo usuarios activos aún)

	* **Juan David Castro (Platzi)** (1)

		
		Por supuesto. Puedes usar DO tanto para practicar o experimentar como para sitios en producción con usuarios activos. 💪

## 0030. Registro en Digital Ocean

### Descripción:


### Comentarios:

* **andresazuara98** (3)

	
	Este curso al igual que los de Azure son buenos, pero creo que cuando se requiere algún pago deberían de dejar el curso solo como opcional, o es mucho pero si se pudiera proporcionar una cuenta para seguir con el curso sería perfecto, habemos algunos que no tenemos el dinero para seguirlo por el costo, y es peor cuando el curso es obligatorio como este, a diferencia del de Azure como IaaS

	* **Santiago Bernal** (1)

		
		Ocurre que todas las empresas que ofrecen IaaS (o al menos las mas conocidas) requiere tener tarjeta de crédito, (algunas como AWS, Azure, IBM o GCP te regalan saldo, pero es obligatorio la TC).  
		Con el caso de Azure es por partnership académicos que hacen.
		
		Aún así Digital Ocean te proporciona la opción de pagar con Paypal, que puede ser más accesible que una tarjeta de crédito en muchos casos.

	* **javier-jimenez834** (1)

		
		Y si conoces a alguien con una cuenta de pago te puede enviar una invitación trial con crédito de $50 USD y vigencia de un mes, suficiente para correr el curso (ojo, no te libras de meter la TC o dar un abono con paypal de $5, pero ya tendrás dos meses de DO). Échale una revisada a la red y buscate un buen amigo que te haga llegar la invitación, opciones hay para que nunca pares de aprender.

	* **Iván Saavedra** (3)

		
		Pues $5 dólares no me parece mucho.
		
		Still… si eres un estudiante: <https://education.github.com/pack>
		
		Aplica al Gihub Student Pack, te pediran sólo que tomes una foto de una identificación que indica que estás en el bachillerato o en la universidad. Si tu institución te dio un correo electrónico, utilizalo en el registro de Github. El propósito de esto es que te dan un código para canjear $50 en una cuenta nueva de DigitalOcean.
		
		Pero reitero, 5 dólares no es mucho y lo mejor es que te permite pagar con PayPal lo cual da muchas facilidades.
		
		También puedes usar mi link de referido: <https://m.do.co/c/b603e858448c>
		
		Te dan $50 dólares, pero debes registrar una tarjeta.

	* **vital_ec** (1)

		
		Yo use el Github Student Pack **sí funciona!**

* **Simón Neptalí Escobar Guerra** (2)

	
	Si se fijan no necesariamente es requerida una tarjeta de crédito. Hay una parte que dice “Credit / Debit Card” o “Tarjeta de crédito / debito”. Con una cuenta bancaria normal y una tarjeta virtual o de debito pueden acceder a estos servicios.

	* **rombj** (1)

		
		Pero debe ser una tarjeta de debito internacional, hay que aclarar eso

* **Simón Neptalí Escobar Guerra** (2)

	
	Hay soluciones financieras como la tarjeta e-prepago de Bancolombia (para las personas que están en Colombia), no es una tarjeta de crédito, sino, una tarjeta para realizar pagos virtuales tanto nacionales como internacionales.

* **Fernando Vallejo** (1)

	
	Yo no tuve necesidad de usar un referido para obtener los $ 100 .
	
	Pero por si hay un alma caritativa que quiera apoyar, dejo mi link jajaj
	
	<https://m.do.co/c/fd280a2c0b3e>

* **alexabellerman** (1)

	
	Dejo un link para $100 de regalo por 60 dias  
	<https://m.do.co/c/204f51f25fcb>  
	Happy Hacking!

* **Diego Antonio Bocanegra Galindez** (1)

	
	Link para registrarse en Digital Ocean, 100 USD de Regalo!  
	<https://m.do.co/c/de8d08538a35>

* **Alejandro Moraga** (1)

	
	SI alguien quiere puede utilizar mi código de referido, obtendrás 100 dolares para utilizar dentro de la plataforma expirables en 60 dias.
	
	Link: <https://m.do.co/c/ba113a50cb8c>

* **Marino Checo** (1)

	
	Claro que esto no tiene que ver con la clase… pero no se como hacerle llegar la sugerencia directo al team… Tal vez al profe le llegue alguna notificación…
	
	Ummm… no será un erro de edicion de video que al momento del registro del usuario hay que poner un correo, esta imagen esta borrosa (perfecto, es bueno) pero después en la validación de correo sale la direccion completa… san…@…fi.com, ahi no habra un problema de seguridad !?
	
	Ahhh por esto @Platzi debería regalarme 3 meses 😃

	* **sanchez-sanz-argent** (1)

		
		Lo uníco que pasa es que ahora conoces el correo del profesor, más que de seguridad es de intimidad pero facilmente puede bloquear a cualquier persona, el mismo freddy da su correo personal en el curso de github y el mismo lo dice, si me mandan correo simplemente los bloqueo y listo.

* **Edynson Edgardo Coronado Icochea** (1)

	
	Para apertura tu cuenta de digitalocea, te estàn abonando 100$ por 60 dìas

	* **Miguel Ángel Bocanegra** (1)

		
		Me podrías ayudar por favor con el registro, o sea me registre puse mi tarjeta ¿y ahora?

* **HeartHunter** (1)

	
	Comenzando Con digital ocean yeah

* **Sebastián Córdoba Omen** (1)

	
	<https://www.digitalocean.com/>
	
	Registro: <https://cloud.digitalocean.com/registrations/new>

* **Erickson** (0)

	
	Saludos, al crear mi cuenta en Digital Ocean realizo todo hasta el paso 2 que es el pago lo realizo con Paypal y me hacen un reembolso y me sale el mensajes que mi cuenta esta bloqueada que debo hacer gracias

	* **Erickson** (1)

		
		Solucionado

## 0040. ¿Qué es un Droplet

### Descripción:


 **Droplet** es la forma en la que Digital Ocean llama a sus **VPS** , tienen la ventaja de utilizar **discos de tipo SSD** con lecturas y escrituras más rápidas que los discos mecánicos convencionales.

### Links:

* [Droplets on DigitalOcean - More than just virtual machines](https://www.digitalocean.com/products/droplets/)

### Comentarios:

* **Emerson Cedeño Salazar** (6)

	
	Yo recomendaría configurar inicialmente el droplet con _autenticación por contraseña_ a fin de recibir la contraseña del root _y luego_ configurar el acceso por SSH, ya que si tu acceso por SSH falla es un dolor de … cabeza resolver el acceso _(en eso estoy ahora mismo, y lo peor de todo, es que no es la 1ra vez que me pasa)_ … alguien más ha experimentado algo semejante?

	* **Juan José Castro** (3)

		
		sudo nano /etc/ssh/sshd_config  
		PermitRootLogin prohibit-password to PermitRootLogin yes  
		PasswordAuthentication no to PasswordAuthentication yes
		
		Basicamente tenemos que cambiar las lines “PermitRootLogin” de no a yes y la línea “PasswordAuthentication” de no a yes.
		
		Con este permite el fogueo con user root (recuerden previamente resetear la contraseña root en la cuenta web del droplet)
		
		Y una vez hecho esto, podemos ya si queremos agregar llaves publicas a nuestro droplet :
		
		1.Generamos la llave publica :
		``` 
		    ssh-keygen -t rsa
		    
		```
		
		[2.Si](http://2.Si) no existe el subdirectorio .ssh dentro de nuestro directorio home, lo creamos, en caso de que existe omitimos este paso.  
		Para crearlo :
		
		mkdir -p .ssh
		
		  1. Copiamos el contenido de la llave publica generada, id_rsa.pub , al archivo authorized_keys de nuestro droplet :
		
		
		
		cat .ssh/id_rsa.pub | ssh root@direccionippublicadeldroplet 'cat >> .ssh/authorized_keys’  
		root password:
		
		Cuando ingresen el password del root va a copiar el contiendo de la llave publica id_rsa.pub a authorized_keys que esta en el droplet
		
		La próxima que intentes loguearte por ssh desde esa misma maquina, ya no debería pedir el password, sino loguearse directo.

	* **deantonio09** (1)

		
		Si!, me arroja lo siguiente cuando intento conectarme desde terminal
		
		Permission denied (publickey,gssapi-keyex,gssapi-with-mic,password). Ya tengo configurado la autenticación por root en yes y con password con yes.

	* **Juan José Castro** (1)

		
		Fijate que el archivo de la llave publica id_rsa.pub , tengas los permisos solo en el user owner.
		
		Para eso fijate con ls -l id_rsa.pub y luego verica que en los permiso solo tú tengas permisos de ejecución sobre dicho archivo.
		
		Si el grupo y otros tienen permisos de ejecución no te permitira el uso de la llave pública.
		
		Para cambiar el permiso de la llave hazlo así :
		
		chmod 700 id_rsa.pub
		
		De esta manera le das permisos de rwx solo a tu usuario.
		
		Cualquier cosa nos comentas.

	* **Emerson Cedeño Salazar** (1)

		
		de hecho, hasta donde tengo entendido los permisos de la llave deben ser únicamente de lectura y escritura, con lo cual el comando quedaría así:
		``` 
		    chmod 400 id_rsa.pub
		    
		```

	* **Emerson Cedeño Salazar** (1)

		
		… perdón, quise decir **600** ~~no 400~~.

	* **Emerson Cedeño Salazar** (1)

		
		… aunque en realidad yo creo ambos permisos funcionan! 😁

	* **Juan José Castro** (1)

		
		Los permisos en la llave pública pueden ser cualquier 400, 600 , 700, es decir que implique :
		
		solo lectura en el usuario owner = 400  
		solo lectura y escritura en el usuario owner = 600  
		todos los permisos, es decir lectura, escritura y ejecución en el usuario owner.
		
		Pero NUNCA ningún tipo de permiso en grupos y others  
		Eso lo puedes ver con un ls -l id_rsa.pub
		
		Lo recomendable es 400 o 600

* **pablovass** (3)

	
	<https://cmder.net/> console emulator esta muy buena .  
	pero yo le tengo mucho cariño al viejo y conocido .  
	putty <https://www.putty.org/> que dinosaurio que soy ! ha!

	* **Santiago Bernal** (1)

		
		El viejo Putty.  
		Afortunadamente Windows ha empezado a ver cómo da más soporte y mediante PowerShell ya ha hecho un avance al respecto.

	* **Emerson Cedeño Salazar** (1)

		
		usando **putty** , cómo asocias la llave generada?, hay que hacer una operación anteriormente para poder utilizar la llave generada, correcto?

* **HeartHunter** (2)

	
	Estoy trabajando desde windows

* **vital_ec** (2)

	
	En **windows 10** así hice para instalar la terminal de Linux:
	
	1 [Activar modo desarrollador](https://medium.com/@whiletruedothis/tutorial-como-activar-la-terminal-de-linux-en-windows-10-beta-52769b5cab7e)
	
	2 [Abra la tienda de Microsoft y elija su distribución de Linux favorita.](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
	
	3 [Inicializar una distribución recién instalada](https://docs.microsoft.com/en-us/windows/wsl/initialize-distro)

* **Alexis Otaño** (2)

	
	[ [ DESARROLLADORES WINDOWS ] ] , a partir de windows 10, puedes “instalar” distros de linux sobre windows, (no particionar y tener otro SO) desde la misma store de windows puedes bajar ubuntu y se puede utilizar como terminal dentro de windows accediendo a todo el sistema de archivos. Microsoft lo llama WSL (Windows Subsystem for Linux),  
	Dejo aqui las instrucciones : <https://docs.microsoft.com/en-us/windows/wsl/install-win10>

* **ddragaid** (2)

	
	Es un proveedor de computación en la nube que nos ofrece poder desplegar aplicaciones en servidores de Linux directamente desde el dashboard o a través de una API.  
	Se caracteriza por tener precios económicos y estar diseñado 100% para desarrolladores, esto significa que todo lo que ofrecen como herramienta está enfocado a que sea sencillo para las personas que están dedicadas al desarrollo.  
	Aunque todavia seria una desventaja es que todos los servicios que estes utilizando generan consumo aunque los apagues porque ellos te asignan un espacio ya directamente en sus servidores para que pueda inizializar mas rapido los procesos asi que si no quieres que te cobren el consumo por las practicas tendras que eliminar y volver a crear todo

* **estebanleoe** (2)
Hola Santiago, estoy siguiendo los pasos del tutorial y obtengo el error: Permission denied(public key) Estoy en Mac sierra 10.12.6. Ayud...

	* **Kevin Javier Morales (Platzi)** (1)

		
		Puedes intentar hacer esto en tu server
		``` 
		    sudo nano /etc/ssh/sshd_config
		    
		```
		
		Y cambiar
		
		PermitRootLogin prohibit-password a PermitRootLogin yes  
		PasswordAuthentication no a PasswordAuthentication yes

* **Daniel Orio Islas** (1)

	
	Segui todas las instrucciones pero no podia conectarme, al usar
	``` 
	    ssh root@<ip>
	    
	```
	
	me aparecia el error
	``` 
	    Warning: Permanently added '167.172.217.245' (ECDSA) to the list of known hosts.
	    root@167.172.217.245: Permission denied (publickey).
	    
	```
	
	Creo que es porque anteriormente he trabajado con alguna llave, lo que hice fue especificar la ruta de la llave que quiero usar. Ojo, la ruta es de la llave privada
	``` 
	    ssh -i /Users/daniel/.ssh/id_rsa  root@<ip>
	    
	```

* **Eduardo Alvarenga** (1)

	
	Crear SSH

* **pablovass** (1)

	
	hoy 2019 tenemos en win 10 desde la tiende de windows la virtual machine de ubuntu envevida que es muy facil de configurar para hacer las practicas de los videos.

* **Nelson Gonzalez Escalante** (1)
Como hago para crear un Droplex que ejecute Windows_10, esto lo ocupo para lanzar una aplicación .exe de un cliente nuestro.

	* **Erik Ochoa (Platzi)** (1)

		
		Al parecer ya es posible pero no lo recomiendan en la página de comunidad de [DigitalOcean](https://www.digitalocean.com/community/questions/does-digitalocean-host-windows-servers). Si vas a trabajar con Windows yo me iría por **Azure**. En Platzi hay muy buenos cursos que te pueden servir:
		
		  1. [Curso de Azure IaaS](https://platzi.com/clases/azure-iaas/)
		  2. [Curso de Almacenamiento en Azure](https://platzi.com/clases/almacenamiento-azure/)
		
		

* **vital_ec** (1)
No puedo conectar mi pc con digital Ocean creo la llave ssh y cuando en mi pc pongo ssh root@MiUrlDigitalOcean</...

	* **vital_ec** (1)

		
		Sigo con el problema, ya instale Ubuntu en una máquina virtual.
		
		y me sale **connect to host[xxx.xxx.xxx.xxx](http://xxx.xxx.xxx.xxx) port 22: Connection timed out**
		
		**¿Cómo puedo saber y arreglar el problema que al parecer tengo con el puerto 22??**

* **Andrea Méndez Díaz** (1)
Hola. Ya realice los cambios PermitRootLogin yes y PasswordAuthentication yes, pero aun me sale root...

* **Emerson Cedeño Salazar** (1)
al crear la llave le asigne un nombre diferente al archivo, cómo debo conectarme por ssh? (estoy en una win10)

	* **Juan David Castro (Platzi)** (1)

		
		Estas guías de seguro te ayudarán:
		
		  * <https://www.enmimaquinafunciona.com/pregunta/47461/puedo-cambiar-el-nombre-de-mi-ssh-publicaclave-privada-pareja>
		  * <https://www.enmimaquinafunciona.com/pregunta/6379/como-cambiar-una-clave-ssh>
		
		

* **deantonio09** (1)
Al conectarme desde la terminal al Droplet, me niega el acceso. Alguien conoce la solución? (publickey, gsspai-keyex,gssapi-with-mic, pas...

	* **Kevin Javier Morales (Platzi)** (1)

		
		Debes modificar el archivo /etc/ssh/sshd_config para modificar o agregar
		``` 
		    PasswordAuthenticationyes
		    
		```
		
		Y luego reinicias el servicio
		``` 
		    service sshd restart
		    
		```

* **caramirezc** (1)
Hola comunidad, ¿la ip de cada droplet es fija y no cambia con el tiempo?

	* **Erik Ochoa (Platzi)** (1)

		
		Sí, la ip de cada droplet es estática (fija) y se mantiene hasta que el droplet es destruido. Toma en cuenta que en ocasiones DigitalOcean  
		usa la misma IP de un droplet recién destruido para otro nuevo. Esto no siempre pasa y no es un problema porque siempre vas a tener tus droplets con una IP única que no cambia.

* **deantonio09** (1)
Si voy a instalar una DB de una plataforma web desarrollada en Oracle, qué plantillan me recomiendan para la configuración del Droplet.

	* **Santiago Bernal** (1)

		
		depende de la versión de Oracle que vayas a instalar.  
		[Oracle](https://docs.oracle.com/en/database/oracle/oracle-database/index.html).
		
		Pero inicialmente te sugiero como mínimo 4Gb en ram. y al menos 2 VCPU

## 0050. Storage Volumes y Spaces

### Descripción:


Tipos de Storage:

  * **Volumes** : bloques de almacenamiento (SSD) de alta disponibilidad, que puedes añadir y quitar de tus droplets.
  * **Spaces** : sistemas de almacenamiento masivo enfocados a CDNs (red entrega de contenidos) que pueden entregar imágenes videos, archivos de código, etc. Tienen un precio competitivo y son compatibles con Amazon S3.



La diferencia entre éstos, es que _volumes_ está pensado en agregar espacio de almacenamiento mientras que _spaces_ está enfocado en la entrega de contenidos.

### Links:

* [Storage on DigitalOcean - Highly available Block Storage](https://www.digitalocean.com/products/block-storage/)

* [Spaces on DigitalOcean - Beautifully simple object storage](https://www.digitalocean.com/products/spaces/)

### Comentarios:

* **Ricardo Rosendo** (2)

	
	es muy importante lo que mencionas sobre el consumo del ancho de banda. gracias por aclararlo

* **Carlos Pintor Villar** (1)
t l

	* **Santiago Bernal** (1)

		
		Qué tal te ha parecido el curso?

## 0060. Marketplace de Digital Ocean

### Descripción:


Es una tienda de aplicaciones o droplets preconfigurados para desplegar en minutos, incluso segundos.

### Links:

* [DigitalOcean Marketplace](https://marketplace.digitalocean.com/)

### Comentarios:

* **estuardoramos** (2)

	
	pues yo trabajo principalmente con JAVA, pero no esta, asi que instale un GlassFish manualmente

	* **caramirezc** (1)

		
		Hola @estuardoramos que framework utiliza para diseñar aplicaciones Web?

* **YnaLem** (1)

	
	Muy buena, corrio a la primera

* **Daniel Fernández Santos** (1)

	
	Aparte del MarketPlace  
	Un lugar que a mi personalmente me gusta bastante y me a ayudado algunas ocasiones en la zona de los tutoriales de la comunidad de DigitalOcean
	
	Dejo el enlace por aquí  
	<https://www.digitalocean.com/community/tutorials>

* **Luis.Lozada** (1)

	
	Muy practico para el despliegue

* **Miguel Ángel Bocanegra** (1)

	
	ok

* **HeartHunter** (1)

	
	Excelente

* **Carlos Pintor Villar** (1)
,f

	* **gxbaquero** (1)

		
		Le faltó mencionar que Platzi tiene excelentes cursos de node.js y los puedes encontrar en [Platzi.com/nodejs](http://Platzi.com/nodejs).  
		(Un copy/paste …umh)

# Configuraciones de un Droplet

## 0070. Activar 2FA en Digital Ocean

### Descripción:


Es una segunda autenticación a parte de tu contraseña para brindar mayor seguridad a nuestra cuenta.

### Links:

* [Install Google Authenticator - Android - Google Account Help](https://support.google.com/accounts/answer/1066447?co=GENIE.Platform%3DAndroid&amp;hl=es)

* [Account settings: Your browser is not supported.](https://myaccount.google.com/signinoptions/two-step-verification/enroll-welcome)

### Comentarios:

* **Wesley Altamiranda Quintero** (4)

	
	Cabe aclarar que los codigos de autenticacion son de único uso  
	solo te puedes loguear 1 vez por cada codigo utilizado

	* **Santiago Bernal** (3)

		
		Es correcto, estos códigos sólo se pueden usar una vez y son en caso de emergencia.  
		Por eso es recomendable usar la autenticación con Google Authenticator que te genera un código cada 30 segundos

* **juanruiz0927** (2)

	
	En Account/Security no me aparece la opcion “secure your account”, que debería hacer?

	* **John Daison Agudelo S.** (4)

		
		tal vez te registraste con tu cuenta de gmail o github entonces ya que no creaste la cuenta directamente con digital ocean debes habilitar la autenticación de 2 factores con google o github

* **JOSE DE JESUS USCANGA MOLINA** (2)

	
	Cuando se acaben esos códigos de backups , como obtengo mas ? .

	* **Santiago Bernal** (3)

		
		Escribiendo un [ticket ](https://www.digitalocean.com/company/contact/#support) a soporte

	* **Oslan Enrique Villalobos  Piña** (1)

		
		Seria muy increíble que utilices todos los códigos.

* **Juan José Castro** (1)
Una consulta, al final del video informas que pasaría se estamos fuera del país o no tengo cobertura y en ese caso no podría recibir el c...

	* **Erik Ochoa (Platzi)** (1)

		
		Ambas opciones tienen sus ventajas y desventajas, tal como mencionas con el SMS podrías no tener cobertura en algún momento, pero con la App si llegas a cambiar de smartphone toca volver a instalar y hacer la autenticación de nuevo. Usa la que más se acomode a tu caso de uso.

## 0080. Panel de Control, Projects y Access

### Descripción:


### Comentarios:

* **Alejandro Jimenez** (3)

	
	Ok, cómo te puedes dar cuenta que quieren hacer login en tu cuenta desde el puerto 22? para qué más sirve cambiar el puerto? Es buena idea cambiar de manera regular el puerto?

	* **Santiago Bernal** (3)

		
		  1. A tu primera pregunta, revisando el archivo auth.log, [más info](https://www.tecmint.com/find-failed-ssh-login-attempts-in-linux/)
		
		
		``` 
		     egrep "Failed|Failure" /var/log/auth.log```
		    
		    2. Cambiar el puerto sirve para evitar que Scanners de red automatizados (como Shodan.io) puedan encontrar fácilmente tu servicio SSH
		    
		    3. No es necesario cambiarlo regularmente, es útil si lo cambias una vez, y bloqueas el acceso a IPs quenoestén autorizadas en tu listado en */etc/host.allow*
		    
		```

* **Japheth Calzada López** (3)

	
	Hola una pregunta, recuerdo que puse una opción para que no me pidiera la llave ssh para accesar, se que no es lo recomendable, pero tengo ahorita otra cuenta con Digital Ocean y no encuentro dicha opción y me la pidio mi compañera con la que realizo el proyecto, alguien sabría ???

	* **Santiago Bernal** (3)

		
		Hola Japheth, en estos enlaces están los pasos para agregar tu llave SSH a tu proyecto (cuenta) y también a tu droplet una vez esté creado:  
		<https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/>  
		<https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/to-account/>

* **YnaLem** (1)

	
	wow!

* **Miguel Ángel Bocanegra** (1)

	
	si

* **Angel Hernandez** (1)

	
	service ssh restart

* **Alexander  Silvera** (1)

	
	Como se que están intentando hacer un ataque a mi servidor??

	* **Kevin Javier Morales (Platzi)** (1)

		
		Mucho de esto se enseña en el curso de [Seguridad Informática](https://platzi.com/clases/seguridad-informatica/) y en la carrera en general.

	* **roganoalien** (1)

		
		Tienes que estar monitoreando tu sitio, hay una herramienta de monitoreo que activas en tu droplet… pero imagino que serían muchos factores como incremento de tráfico de forma absurda , serie de registros logs raros de no acceso y demás

* **deantonio09** (1)

	
	Ayuda: Intento conectarme desde terminal y me arroja Permission denied (publickey,gssapi-keyex,gssapi-with-mic,password). Ya tengo configurado la autenticación por root en yes y con password con yes.

* **deantonio09** (1)

	
	Cuando reinicio con systemctl reload sshd  
	arroja:  
	job for sshd.service invalid  
	Ayuda!! Tengo la página caída y no puedo ingresar desde la terminal

## 0090. Volumes y Power

### Descripción:


Para trabajar con **Volumes** a veces es necesario apagar nuestro droplet, para esto tenemos dos opciones:

  * **Power Off:** reiniciar por sistema.
  * **Power Cycle:**. es un reinicio forzoso, como cuando en un equipo físico presionas el botón de encendido por mucho tiempo. Se pueden perder datos y sólo deber ser usado cuando no tienes más opción.



### Comentarios:

* **macobe** (3)

	
	se puede apagar también desde ssh con init 0 ? o cual es la diferencia ?

	* **Daniel Esteves** (2)

		
		También puedes hacerlo, tienes dos maneras desde la terminal o haciéndolo con la interfaz, de la manera en que se te haga más cómoda pero las dos son lo mismo

	* **Josué Miguel Rodríguez Girón** (1)

		
		init 0, forma parte de sistema de inicio SysVinit que esta “obsoleto” y casi ninguna distribucion linux la incluye.

* **JOSE DE JESUS USCANGA MOLINA** (2)

	
	Un volumen puede ser agregado a mas de 1 Droplets ?

	* **Santiago Bernal** (2)

		
		Sólo puede ser conectado a un droplet a la vez.

* **JOSE DE JESUS USCANGA MOLINA** (2)
Un volumen puede ser agregado a otros Droplets ?

	* **Santiago Bernal** (1)

		
		Si, un volumen puede ser agregado a otros droplets, pero sólo a uno a la vez

* **MexCatacumbero** (1)

	
	Quiero ese hoodie, donde lo consigo.

	* **Santiago Bernal** (1)

		
		Puedes escribir a [team@platzi.com](mailto:team@platzi.com) para averiguar cómo conseguir uno. o incluso asistiendo a una platzi conf

* **darwinyusef** (1)

	
	yo puedo crear varios volumes sin necesidad de pagar y/o ampliar el costo de mi servicio?

	* **Marvin López** (3)

		
		Exactamente, claro que cada volumen tiene un costo extra, pero no necesitas pagar o aumentar el costo del droplet, no se si esa es tu pregunta.

* **César Ernesto Rivas Martínez** (1)
Si yo tengo un droplet al 90% de capacidad y le quiero agregar un volume, Con el comando sudo mkfs.ext4 /dev/disk/by-id/scsi..........

	* **Josué Miguel Rodríguez Girón** (1)

		
		Al agregar un volumen este no incrementará el tamaño de los ya existentes, si te aparece esa advertencia es porque estas **formateando** un volumen “antiguo” con datos almacenados. Si el volumen que está proximo a llenarse es el principal, es decir donde esta instalado el sistema operativo te pueden ser de ayuda las siguientes opciones:
		
		  1. Realiza un redimensionamiento (opcion resize) del droplet a uno con mayor almacenamiento, este te afecta directamente la tarifa.
		  2. O puedes agregar un volumen, particionar, formatear copiar datos y luego establecer el punto de montaje al que pertenecian esos datos.
		
		
		
		Ahora si el volumen no es el principal, puede irte al apartado de volumenes en el droplet y aumentar su tamaño, luego debes realizar ciertos pasos a nivel de sistema operativo para habilitar ese nuevo espacio ya sea realizando un redimensionamiento o creando una nueva particion.

* **Juan José Castro** (1)
Santiago, al final cuando volvemos a realizar el attach del volume, estás seguro que es necesario volver a realizar los pasos de configur...

	* **Erik Ochoa (Platzi)** (1)

		
		Tal como mencionas no son necesarios estos pasos ya que estamos añadiendo el Volume al mismo droplet donde lo teníamos anteriormente. En el caso de añadir a un droplet diferente si debes llevar a cabo esos pasos manuales.

## 0100. Resize (Escalamiento vertical)

### Descripción:


Resize o **escalamiento vertical** es cuando agregamos más recursos a nuestro droplet como son: memoria RAM, CPU o almacenamiento.

Existe también el escalamiento horizontal que es cuando agregamos más droplets.

### Links:

* [Introducción a Terminal y Línea de Comandos](https://platzi.com/cursos/terminal/)

### Comentarios:

* **Gerardo Alberto Soto Alvarez del Castillo** (5)

	
	NO se puede re-escalar el Disco Duro, porque se desfragmenta al guardar archivos en todo el DD. [En por esta razón que se debe utilizar los volúmenes para ampliar de manera escalable el tamaño del Droplet].

* **javier-jimenez834** (2)

	
	La descripción del video es erróneo, corresponde al video previo (Volumes).

	* **Daniel Esteves** (2)

		
		¡Muchas gracias por el reporte! Vamos a solucionarlo lo más pronto posible

* **JOSE DE JESUS USCANGA MOLINA** (2)

	
	No me agrada que al escalar tengo que apagar mi Droplet. mi pregunta seria si hay un servicio que lo haga en caliente , o tengo que manejar un orquestador como swarm o kubernates para lograr esto.

	* **hecto.ruiz** (1)

		
		En lo que he visto, para hacer siempre el escalamiento vertical es necesario apagar el recurso… en cuanto a lo que menciona del uso de swarm o kubernetes, no veo como se pueda solventar por ese lado…

	* **Santiago Bernal** (7)

		
		Por el momento se requiere apagar el droplet.  
		<https://www.digitalocean.com/docs/droplets/how-to/resize/>
		
		Una opción para hacer resize y no tener downtime de tu aplicación es que tengas 2 droplets haciendo balanceo de cargas y así podrás ir ampliando sin afectar a tus usuarios -> <https://www.digitalocean.com/products/load-balancer/>

	* **Daniel Fernández Santos** (1)

		
		No me sorprende que en DigitalOcean haga falta apagar el Droplet ya que en otros providers también ocurre, por ejemplo en AWS también deben estar apagadas las instancias que se van a dimensionar

* **Carlos Castro** (1)

	
	¿Cómo hace el cargo de $ D.O. cuando se hacen estos cambios? es proporcional al tiempo en que estuvo cierta propiedad activa?

	* **Josué Miguel Rodríguez Girón** (1)

		
		Recuerda que al ser computacion en la nube es pago por consumo.

* **Juan José Castro** (1)

	
	Además del comando cat /proc/meminfo para ver datos de la memoria ram en tiempo real, también podemos hacer lo propio para el CPU, con el comando cat /proc/cpuinfo
	
	A continuación se puede ver la salida del comando cat cpuinfo (yo lo hice directamente dentro del directorio /proc pero pueden hacerlo desde cualquier path con cat /proc/cpuinfo) y se ve la información de cada vCPU (processor 0 y proccesor 1= :  
	<pre>[root@ubuntu18 proc]# cat cpuinfo  
	processor : 0  
	vendor_id : GenuineIntel  
	cpu family : 6  
	model : 85  
	model name : Intel® Xeon® Gold 6140 CPU @ 2.30GHz  
	stepping : 4  
	microcode : 0x1  
	cpu MHz : 2294.560  
	cache size : 25344 KB  
	physical id : 0  
	siblings : 1  
	core id : 0  
	cpu cores : 1  
	apicid : 0  
	initial apicid : 0  
	fpu : yes  
	fpu_exception : yes  
	cpuid level : 13  
	wp : yes  
	flags : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon rep_good nopl cpuid tsc_known_freq pni pclmulqdq vmx ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch cpuid_fault invpcid_single pti ssbd ibrs ibpb tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 hle avx2 smep bmi2 erms invpcid rtm mpx avx512f avx512dq rdseed adx smap clflushopt clwb avx512cd avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves pku ospke md_clear  
	bugs : cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf mds swapgs  
	bogomips : 4589.12  
	clflush size : 64  
	cache_alignment : 64  
	address sizes : 40 bits physical, 48 bits virtual  
	power management:
	
	processor : 1  
	vendor_id : GenuineIntel  
	cpu family : 6  
	model : 85  
	model name : Intel® Xeon® Gold 6140 CPU @ 2.30GHz  
	stepping : 4  
	microcode : 0x1  
	cpu MHz : 2294.560  
	cache size : 25344 KB  
	physical id : 1  
	siblings : 1  
	core id : 0  
	cpu cores : 1  
	apicid : 1  
	initial apicid : 1  
	fpu : yes  
	fpu_exception : yes  
	cpuid level : 13  
	wp : yes  
	flags : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon rep_good nopl cpuid tsc_known_freq pni pclmulqdq vmx ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch cpuid_fault invpcid_single pti ssbd ibrs ibpb tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 hle avx2 smep bmi2 erms invpcid rtm mpx avx512f avx512dq rdseed adx smap clflushopt clwb avx512cd avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves pku ospke md_clear  
	bugs : cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf mds swapgs  
	bogomips : 4589.12  
	clflush size : 64  
	cache_alignment : 64  
	address sizes : 40 bits physical, 48 bits virtual  
	power management:
	
	[root@ubuntu18 proc]#
	
	</pre>

## 0110. Networking y Firewall

### Descripción:


 **Networking:** IPs flotantes, balanceadores de carga, firewall, etc. Esta opción nos permitirá configurar todos los temas relacionados con la red.

Una red privada nos servirá para por ejemplo conectar dos droplet a través de esta dirección sin necesidad de que sean accedidas desde internet.

**Firewall:** Es un software del SO que permite manejar y administrar todas las reglas de conexiones entrantes y salientes de nuestro droplet.

### Comentarios:

* **darwinyusef** (3)

	
	profe una pregunta como se pueden integrar varios dominios dentro del droplet, otra pregunta como puedo integrar varios dominios a un solo servicio ejemplo (servicio multidioma) - dominio 1: [www.ingles.com](http://www.ingles.com) \- dominio 2 [www.español.com](http://www.xn--espaol-zwa.com) los dos dominios van al mismo server porque ahí esta el servicio.

	* **xergioalex** (1)

		
		Se puede hacer sin problema desde tu proveedor de dominios, ya sea Godaddy, Namecheap y entre otros, lo único que debes hacer es apuntar ambos DNS de [www.español.com](http://www.xn--espaol-zwa.com) y [www.ingles.com](http://www.ingles.com) hacia la misma ip del droplet. Ya en el droplet ya es tu responsabilidad poner un servidor web que use estos nombres de dominio.
		
		De los mejores servidores web que puedes usar recomiendo Nginx.

	* **Santiago Bernal** (2)

		
		Puedes hacerlo apuntando los dominios con un registro de tipo A hacia la IP del droplet.  
		Para el multiidioma puedes configurar en tu servidor web (apache, nginx) que dependiendo de la URL de solicitud ([ingles.com](http://ingles.com) o [espanol.com](http://espanol.com)) se redireccione a una carpeta o sección de tu sitio/app

	* **lizlozano** (1)

		
		Tienes varios caminos para lograr esto.
		
		El primero es montarte un panel administrativo para tu servidor, yo te recomiendo uno llamado ZesleCP gestionas muchas cosas del servidor desde este y solo haces el apuntamiento que para mayor comodidad lo haría con cloudflare.
		
		El segundo si tu entorno es manual entonces debes hacerlo con virtualhost para que este dominio apunte al patch especifico que deseas cargar con cada dominio.

* **Jose Luis Campos Bautista** (2)

	
	Protocolo: **ICMP** (Internet Control Message Protocol)

* **Jose Luis Campos Bautista** (1)

	```
	    lshw -classnetwork
	    
	    List hardware 
	    Classsoloseleccionamosciertaclasedehardware
	    
	```

* **sergio-mata** (1)

	
	Las ips publicas del droplet cambian cuando se apagan o es estatica?

	* **Juan José Castro** (2)

		
		La ip pública del droplet no cambia nunca, es decir es estática. Ya que si fuese dinámica nos cambiaria la ip a la cual nos conectariamos a nuestro droplet via ssh , o si tenemos corriendo una servidor web, etc, etc

* **Marvin López** (1)

	
	lshw -class network  
	nano /etc/netplan/50-cloud-init.yaml  
	netplan apply --debug
	
	para aquellos como yo que no ha llevado el curso de terminal 😃

	* **John Daison Agudelo S.** (4)

		
		es bueno aclarar que esto es para ubuntu, si estamos usando otra distro aqui está el link con la info <https://www.digitalocean.com/docs/networking/private-networking/how-to/enable/>

* **Volker69k** (1)
¿Al habilitar la IP Flotante, esta queda como IP predeterminada si cae la IP publica normal?

* **Emerson Cedeño Salazar** (1)
no me quedo claro el por qué se debe agregar una IP flotante a un proyecto que envíe correos para evitar caer en listas negras(?)

	* **Kevin Javier Morales (Platzi)** (2)

		
		Porque estas IPs flotantes cambian constantemente, si una de esas IPs cae en la lista negra los mensajes llegarán como spam, eso se evita con las IPs flotantes.

* **Juan José Castro** (1)
Santiago, es raro pero cuando añado el FW a mi droplet, y solo permito el port TCP 4554 me rechaza la conexión ssh… al final tengo que de...

	* **Dioxo** (1)

		
		Creo que es porque la conexión SSH usa el **puerto 22** y según te entiendo das **acceso solamente al puerto 4554 (TCP).**  
		Tendrías que dar acceso al puerto 22 también, sino todas las peticiones te las va a rechazar.  
		O si quieres usar otro puerto distinto al 22 para el SSH, tendrías que configurarlo manualmente y definir un puerto abierto para la conexión SSH

* **Gilberto Asuaje** (0)
en el firewall como bloqueo IP y ¿comó podria desbloquearla?

## 0120. Backups y Snapshots

### Descripción:


Los **Backups** son copias de seguridad semanales que se hacen el domingo por la noche o lunes por la mañana con costo de un dólar mensual.

Los **Snapshots** son una copia exacta de nuestro droplet, son muy útiles cuando haces cambios en el sistema operativo o la base de datos ya que puedes crear un snapshot para hacer comparaciones con la versión anterior y restaurar de ser necesario.

Al momento de restaurar tienes la opción de hacerlo en un nuevo droplet o directamente en el droplet actual.

### Comentarios:

* **Anderson Alfaro** (1)
Un snapshot en este tipo de virtualización llamada kvm generalmente queda en el mismo volumen. No es recomendable como estrategia de Back...

* **Jhonathan Borda Moreno Borda Moreno** (1)
Si saco un snapshot de un droplet con volumes y lo restauró en otro droplet... Ambos apuntan al mismo volume o el nuevo queda con la refe...

	* **Anderson Alfaro** (1)

		
		Un snapshot en este tipo de virtualización llamada kvm generalmente queda en el mismo volumen. No es recomendable como estrategia de Backup porque de hecho no lo es y no se debería abusar de ellos porque afecta el performance de la máquina. Un snapshot es una fotografía de un estado óptimo de tu máquina virtual y sirve para tener un buen punto de retorno en caso que algo salga mal.
		
		Si se publica de un snapshot se depende de la imagen base.
		
		Un backup. Es una copia completa de la imagen y es la opción mas segura

* **Emerson Cedeño Salazar** (1)
se puede hacer únicamente un (1) backup, o nada más se puede activar el servicio para backups automáticos periódicamente?, y de ser así, ...

	* **Erik Ochoa (Platzi)** (3)

		
		Si quieres hacer sólo un backup debes usar la opción de **snapshots** que se ve en este misma clase, vuelve a verla y te aseguro que resuelve tu duda.

## 0130. Kernel

### Descripción:


En el mundo de los droplets y de Linux tenemos un concepto clave a la hora de manejar los sistemas operativos: el **Kernel (o núcleo)**.

**El Kernel** es el corazón del sistema operativo Linux, es el software que se encuentra entre el sistema operativo (SO) y el hardware del equipo. Veamos por qué es tan importante:

**Gestiona toda la conexión entre el software y el hardware:** Cuando una aplicación le solicita al sistema operativo el acceso a un hardware, como por ejemplo el disco duro para realizar almacenamiento, el SO le solicita a el Kernel el acceso, y este verifica si el recurso físico se puede facilitar a la aplicación.

El Kernel es el encargado de gestionar la memoria RAM, es decir, cuando un programa requiere más memoria para poder cargar más información, debe solicitar dicha gestión al Kernel quien se encarga de verificar cuánta memoria hay y entregar de acuerdo a la disponibilidad, también se encarga de liberar la memoria RAM.

El Kernel se encarga también de la gestión del procesador, es decir, es quien decide qué operaciones tienen más prioridad de ejecución.

En Digital Ocean tenemos la opción de manipular el Kernel de nuestro Droplet, es decir podemos actualizarlo e incluso modifícarlo, sin embargo se recomienda tener mucha precaución, ya que una actualización o modificación fallida puede dañar el Droplet.

### Comentarios:

* **Emerson Cedeño Salazar** (2)

	
	en el mundo Microsoft y sus sistemas operativos, existe el kernel?, y de ser así, se llama y funciona igual?

	* **willeonardo19** (6)

		
		Así es, acá te dejo una lectura para solventar tus dudas.  
		<https://www.genbeta.com/a-fondo/como-es-el-kernel-de-windows-y-cuales-son-sus-diferencias-con-el-de-linux>

* **MexCatacumbero** (2)

	
	Como se trabaja con el kernel??

	* **Santiago Bernal** (5)

		
		Editando los archivos fuentes y luego compilando el kernel.  
		[tutorial](https://www.howtogeek.com/howto/ubuntu/how-to-customize-your-ubuntu-kernel/)
		
		Te recomiendo que antes de editarlo, leas muy bien la documentación de los comandos, y lo hagas sobre un droplet de pruebas

* **Luis.Lozada** (1)

	
	El acceso al kernel es por niveles o cualquiera puede acceder a el sin privilegios en el sistema?

## 0140. History y Destroy

### Descripción:


El **History** es una bitácora de todo lo que ocurre en nuestro droplet. Nos da información como: el evento, su momento de ejecución y duración.

La opción **Destroy** sirve para eliminar droplets que ya no necesitamos y así evitar cargos innecesarios.

### Comentarios:

* **AlejoE02** (1)

	
	Si el droplet esta apagado va a generar facturacion?

	* **gchacaltana** (2)

		
		Si cobran, porque el almacenamiento del disco aún se mantiene y eso cuesta.

* **Luis.Lozada** (1)

	
	Muy importante para trabajos colaborativos.

* **Reny Severiche** (1)
Generar un espacio en disco los snapp?

	* **Erik Ochoa (Platzi)** (1)

		
		Los snapshots son almacenados por Digital Ocean en su propio NAS de AWS sin que te generen un costo de espacio en tus droplets.

* **Gerardo Alberto Soto Alvarez del Castillo** (1)
De los Snapshot que se van generando de los Droplets, ¿Se pueden descargar a una PC para luego guardarlos en un disco duro? Y ¿Con los re...

	* **Erik Ochoa (Platzi)** (2)

		
		Tengo entendido que no es posible descargar un Snapshot por el momento, pero sí que es una petición [popular](https://ideas.digitalocean.com/ideas/DO-I-2423).

## 0150. Tags, Recovery y Graphs

### Descripción:


Los **Tags** son una forma de agrupar todos los droplets que tenemos, por ejemplo: DataBase, Backend, Firewall, WebServer etc.

**Recovery** permite iniciar el droplet a partir de una imagen ISO de recuperación para intentar recuperar un droplet que no inicia.

**Graphs** muestra estadísticas de los recursos de nuestro droplets como son: CPU RAM, ancho de banda etc.

### Comentarios:

# API de Digital Ocean

## 0160. Conociendo una API

### Descripción:


Las **APIs o interfaces para programar aplicaciones** son un conjunto de recursos que ofrece una organización o aplicación para que desarrolladores puedan interactuar con datos, es decir, consultar datos, crearlos, modifícarlos e incluso en algunos casos, eliminarlos.

Las APIs en la web nacieron de la necesidad de compartir datos y recursos entre organizaciones, y hoy en día muchas empresas ofrecen acceso a sus datos mediante APIs, veamos un caso práctico.

Cuando un usuario desea acceder a Platzi para ver contenido lo puede hacer mediante un _login_ de usuario y contraseña, pero también puede autenticarse mediante redes sociales como Facebook o Twitter, y el flujo es el siguiente:

  * El usuario presiona en el botón de Twitter.
  * Se carga el sitio de Twitter donde el usuario debe iniciar sesión, y si ya tiene una sesión activa se le preguntará si desea autorizar el uso de sus credenciales en la aplicación Platzi.
  * El usuario acepta y Twitter envía un _token_ hacia el Platzi.
  * En el _backend_ de Platzi se recibe el _token_ adicional con la información del usuario de Twitter.
  * Platzi crea una sesión de usuario.



Digital Ocean cuenta con una API que nos permite mediante peticiones HTTP (con los métodos _**get, post, put, delete**_ ) realizar operaciones sobre los productos que ellos ofrecen como droplets, volumes, etc.

Es decir, podemos crear un droplet, apagarlo, destruirlo o incluso redimensionarlo mediante el llamado a la API.

En la documentación oficial podremos encontrar más casos de uso, lo único que debemos tener en cuenta es que requerimos de un _token_ de autorización para interactuar con la API y este se obtiene en el panel de control.

### <https://developers.digitalocean.com/documentation/v2/>

### Comentarios:

## 0170. Cómo generar una API Key en Digital Ocean

### Descripción:


La **API de Digital Ocean** nos permite automatizar todo lo que hacemos en el panel de control pero usando comandos a través de peticiones http.

**API Key** es un hash que identifica el equipo que se conecta a Digital Ocean.

### Links:

* [ DigitalOcean](https://cloud.digitalocean.com/account/api/tokens)

### Comentarios:

* **Luis.Lozada** (1)

	
	Una API es un conjunto de definiciones y protocolos que se utiliza para desarrollar e integrar el software de las aplicaciones. API significa interfaz de programación de aplicaciones.
	
	Las API permiten que sus productos y servicios se comuniquen con otros, sin necesidad de saber cómo están implementados. Esto simplifica el desarrollo de las aplicaciones y permite ahorrar tiempo y dinero. Las API le otorgan flexibilidad; simplifican el diseño, la administración y el uso de las aplicaciones, y proporcionan oportunidades de innovación, lo cual es ideal al momento de diseñar herramientas y productos nuevos (o de gestionar los actuales).  
	[](https://www.redhat.com/es/topics/api/what-are-application-programming-interfaces)

## 0180. Creación de Droplet por API

### Descripción:


### Links:

* [DigitalOcean API](https://developers.digitalocean.com/documentation/v2/#droplets)

* [Postman | API Development Environment](https://www.getpostman.com/)

### Comentarios:

* **xergioalex** (7)

	
	A los que usen Docker pueden interactuar con la API de Digital Ocean a través del driver de DO que tiene `docker-machine`, el cual me permite administrar droplets via consola de manera bastante intuitiva.
	
	Docker Machine - Driver DO: <https://docs.docker.com/machine/drivers/digital-ocean/>

	* **Daniel Fernández Santos** (1)

		
		Buenísimo
		
		Gracias

* **agustin123456789** (3)

	
	¡Donde se supone que debo conseguir el URl del endpoint?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Te refieres al URI del API de Digital Ocean?, las puedes consultar en la documentación oficial del API <https://developers.digitalocean.com/documentation/v2/#create-a-new-droplet>

	* **vital_ec** (2)

		
		No es tanto obtener la URL, sino setear formato/parametro pre-establecidos.
		
		**EndPoint para la llave ssh**
		
		<https://api.digitalocean.com/v2/account/keys>
		
		**EndPoint para crear el droplet**
		
		<https://api.digitalocean.com/v2/droplets>

* **cjochoa** (1)

	
	Que practica herramienta me ha resultado Postman.

* **titolizar** (1)

	
	Como que automatizaciones nomas se pueden hacer? aparte de creación de Droplets

	* **Daniel Fernández Santos** (1)

		
		Hola, no he revisado toda la documentación del API de DigitalOcean, pero de un vistazo rápido me ha parecido ver que se puede hacer “todas” las configuraciones al igual que por el panel web
		
		Te dejo la documentación completa del API  
		<https://developers.digitalocean.com/documentation/v2/>
		
		Yo he de reconocer que antes que “hablar” directamente con el API de los Cloud Provider, prefiero usar Terraform  
		Aquí el curso  
		<https://platzi.com/clases/devops-terraform/>  
		Aquí el provider de DigitalOcean  
		<https://www.terraform.io/docs/providers/do/index.html>

* **David Eduardo Abril Molina** (1)
Segui los pasos del ejemplo, me creo el droplet pero por fuera de mi proyecto inicial; desde la interfaz gráfica pude reubicarlo…pero des...

* **David Eduardo Abril Molina** (1)
Segui los pasos del ejemplo, me creo el droplet pero por fuera de mi proyecto inicial; desde la interfaz gráfica pude reubicarlo…pero des...

* **Andrés Felipe Ortiz Zambrano** (1)
Hola, tengo una pregunta. En caso de que tenga varios proyectos ¿Cómo puedo especificar en que proyecto quiero que se me cree el Droplet?

	* **vital_ec** (1)

		
		Hola **al momento de crear el droplet,** cuando indicas las especificaciones que quieres que tenga tu droplet al final de la página esta la opción
		
		![seleccionar proyecto.jpg](https://static.platzi.com/media/user_upload/seleccionar%20proyecto-90718a9c-ab97-4c1d-98bf-f5c48e10a70b.jpg)
		
		**Ahí te salen los proyectos que tienes,** (En este caso sólo tengo 1) y seleccionas en el que quieres que se cree tu droplet

* **jey** (0)
{ “id”: “unprocessable_entity”, “message”: “You specified an invalid image for Droplet creation.” } me sale este error alguien me ayuda!!!

# Despliegue de un servidor web

## 0190. Instalación de Nginx en un Droplet

### Descripción:


### Links:

* [Cómo instalar Nginx en Ubuntu 18.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/como-instalar-nginx-en-ubuntu-18-04-es)

### Comentarios:

## 0200. Instalación de PHP en un Droplet

### Descripción:


### Links:

* [PHP: Manejador de Procesos FastCGI (FPM) - Manual ](https://www.php.net/manual/es/install.fpm.php)

### Comentarios:

* **Roberto Alejandro Agudelo Callejas** (1)

	
	Hola buen día necesito ayuda con lo siguiente resulta que ya hice todo lo que explican en los vídeos para poder tener instalado PHP, MYSQL y Wordpress, en un solo Droplet pero ahora necesito realizar el siguiente cambio y es el siguiente compre este dominio: [tgvshoes.com](http://tgvshoes.com), el dominio lo tengo configurado en [cloudflare.com](http://cloudflare.com), necesito hacer el cambio en mi sitio web en Wordpress, para que en vez de esta dirección: <http://198.211.109.61/>, me quede redireccionando a este dominio [tgvshoes.com](http://tgvshoes.com), yo ya hice el cambio de las URL en Wordpress pero lo que me esta pasando es que cada vez que realizo este cambio pierdo acceso al wp-admin de Wordpress y el sitio web también se me daña sacando muchas veces error de conexión a la base de datos. El mensaje de error es este: error establishing a database connection wordpress, por favor si alguien me puede colaborar con esto ya que llevo varios días tratando de solucionar este error y en Internet la única documentación que he encontrado es para servidores de Web Hosting como por ejemplo Blue Host y Go Daddy por poner un ejemplo, pero de Digital Ocean no he encontrado una información precisa sobre este error en especifico.

	* **Alejandro Barrera Correa** (1)

		
		Hola Roberto, tienes que configurar la IP publica del Droplet en el registro DNS de Cloudflare, de esta manera podrás resolver el dominio [tgvshoes.com](http://tgvshoes.com)

## 0210. Instalación de Mysql en un Droplet

### Descripción:


### Links:

* [Cómo instalar MySQL en Ubuntu 18.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/como-instalar-mysql-en-ubuntu-18-04-es)

### Comentarios:

* **Angel Hernandez** (5)

	
	Al ejecutar "grant all privileges on _._ " se le esta dando permisos muy elevados al usuario, este puede realizar todo lo que quiera en todas las bases de datos lo cual no es una buena practica, lo ideal seria: grant all privileges on nombre_base_datos.* to ‘nombre_usuario’@‘host’

* **jcesar** (4)

	
	En un mismo droplet puedo instalar ngnix, php y mysql? o es necesario crear un droplet para cada uno de estos servicios?

	* **willeonardo19** (3)

		
		Hola, claro que lo puedes hacer, pero por cuestiones de buenas practicas de seguridad, lo desarollaron de esta manera.  
		<https://www.digitalocean.com/community/tutorials/como-instalar-wordpress-con-lamp-en-ubuntu-18-04-es>  
		<https://www.digitalocean.com/community/tutorials/como-instalar-wordpress-con-lemp-en-ubuntu-18-04-es>

* **Bryan Ignacio Vera Cabanilla** (1)

	
	Esas apps que ya vienen preconfiguradas son dockers?

* **Daniel Orio Islas** (1)
¿Cómo me puedo conectarme desde mysql workbench a la base de datos de mi droplet?

	* **Daniel Fernández Santos** (1)

		
		Entiendo que el MYSQL Workbench lo ejecutas desde tu equipo local, por lo que lo primero que debes hacer es configurar MySQL para que permita conexiónes desde tu equipo
		
		En el minuto 6:24 configura el servidor para que permita al “otro” Droplet, en tu caso debes permitir también tu equipo local
		
		Lo rápido que hace mucha gente es permitir 0.0.0.0 (cualquier origen) ya que no se pueden configurar más de un origen
		
		Lo que yo si haría es crear un usuario para poder acceder sólo desde tu local y que se deniegue el resto

* **Roberto Alejandro Agudelo Callejas** (1)
hola buen día me esta saliento el siguiente error cuando al momento de crear el usuario de base de datos para la instalación de wordpress...

* **Juanse Calviño** (0)

	
	Hola, tengo un problema. Sigo todo al pie de la letra, pero cuando me quiero conectar a mysql desde el servidor backend, tarda demasiado y luego indica este error:
	``` 
	    ERROR 2003 (HY000): Can't connect to MySQL server on '10.116.0.2' (110)```
	    
	```

## 0220. Instalación de Wordpress en un Droplet

### Descripción:


En esta clase tu profesor Santiago Bernal te enseña como instalar WordPress en un droplet que tiene previamente instalado Nginx con PHP y cómo conectarlo a una Base de Datos MySQL que corre en otro droplet.

WordPress es un CMS (Content Management System) Open Source extremadamente popular, inicialmente pensado para blogs que actualmente se usa para todo tipo de sitios gracias a plugins que extienden sus características.

### Links:

* [Español — WordPress](https://es.wordpress.org)

### Comentarios:

## 0230. Recomendaciones

### Descripción:


Una de las alternativas que nos permite Digital Ocean para acceder a nuestro droplet es mediante dominios y subdominios. Esto quiere decir que en vez de entrar a nuestro sitio Wordpress mediante una URL con una IP pública, por ejemplo: `http://192.34.61.42`, lo podemos hacer mediante un dominio como `misitiowp.com` o un subdominio `wordpress.midominio.com`

#### Para utilizar un subdominio en uno de tus droplets necesitas:

  * Tener un dominio, lo puedes adquirir con algún proveedor como [name.com](http://name.com), namecheap o google domains.



Para este tutorial utilizaré esta configuración:

  * Nombre droplet: backend
  * IP pública: 192.34.61.42
  * Subdominio a utilizar: [wordpress.aumentada.net](http://wordpress.aumentada.net)


  1. En el panel de control donde gestionas el dominio (puede ser un _Cpanel_ si tienes un plan de _hosting_ u otro sistema) vas a entrar a la opción de gestión de dominio. Es algo parecido a la siguiente imagen:

![1.png](https://static.platzi.com/media/user_upload/1-63183d74-eb2b-444f-abf1-b47033dd7192.jpg)

  2. Después selecciona el dominio para crear un subdominio y presiona la opción **administrar** :

![2.png](https://static.platzi.com/media/user_upload/2-871e18b2-23c4-45e9-a858-de48c08301b5.jpg)

  3. A continuación selecciona la opción llamada añadir registro

![3.png](https://static.platzi.com/media/user_upload/3-390a333b-26ca-47d0-a841-63b3f45a3ae5.jpg)

  4. Crea el subdominio, deja el TTL en 14400 o 3600, esto es básicamente el tiempo que dura el registro antes de que se refresque o actualice en el servidor DNS, seleccionamos que sea de tipo A y agregamos la IP pública del droplet al final, finalmente presionamos el botón añadir registro.

![4.png](https://static.platzi.com/media/user_upload/4-9afd20a7-9ae7-4980-b311-bc9d90729306.jpg)

  5. Regresa al panel de control de Digital Ocean, en la opción de la izquierda en el **menú Manage** , dirígete a la opción **Networking** , y selecciona la pestaña **Domains**.

![5.png](https://static.platzi.com/media/user_upload/5-3c2e40f6-9b5b-4f71-8577-e3a6c89e9f72.jpg)

  6. Agregar el subdominio que previamente creaste y asocialo al proyecto que creaste.  
Finalmente entramos por el navegador a la URL del subdominio, en este caso `http://wordpress.aumentada.net` y estarás accediendo al droplet.

![6.png](https://static.platzi.com/media/user_upload/6-47b8f12d-2c91-45e7-b44f-f3021e1683cb.jpg)

Esta es una de las recomendaciones que te doy para gestionar con mayor facilidad tus droplets y sus conexiones con otros servidores. No es obligatorio que hagas este ejercicio, sin embargo es importante que conozcas que puedes realizar este tipo de configuración.

### Comentarios:

# Despliegue de un servidor VPN

## 0240. Instalación de un servidor OpenVPN en un Droplet

### Descripción:


Una VPN es una red privada que nos permite tener mayor seguridad y privacidad al navegar en Internet.

### Links:

* [GitHub - santiaguf/openvpn-install: OpenVPN road warrior installer for Debian, Ubuntu and CentOS](https://github.com/santiaguf/openvpn-install)

* [Curso de Redes de Internet](https://platzi.com/cursos/redes/)

### Comentarios:

* **estuardoramos** (3)

	```
	    ssh root@<ip-server>
	    wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh
	    # nos pide confirmar IP publica
	    # nos pide escoger protocolo (UDP/TCP)
	    # nos pide escoger puerto (1194 en este ejemplo)
	    # nos pide escoger DNS
	    # nos pide nombre para el certificado cliente
	    # enter para empezar configuración
	    cat /root/<cliente-certificado>.ovpn # clienteplatzi.ovpn en este ejemplo
	    # el archivo se guarda en local
	```

	* **Juan Rafael De Leon Osorio** (1)

		
		y para crear un nuevo cliente?

* **Kerohuixco** (2)

	
	La explicción es maravillosa. Pero yo soy medio piedra. Podrias darme hacer un ejemplo de aplicación sobre el VPN

	* **Santiago Bernal** (3)

		
		Por ejemplo tienes un servidor de videojuegos y quieres que solo ciertos usuarios accedan a él.  
		O por ejemplo si usas alguna zona wifi gratuita y abierta (centros comerciales, aeropuertos, universidades). allí es bueno tener la VPN por seguridad

	* **Daniel Fernández Santos** (1)

		
		Yo principalmente lo uso para lo siguiente
		
		Todos mis “despliegues” sólo están en redes privadas  
		El servidor VPN si que está público  
		Conectando con la VPN “enruto” el tráfico hacia la red privada y así puedo acceder al resto de mis equipos de desarrollo
		
		Esto lo hago así ya que muchas veces para probar no configuro todas las capas de seguridad que serían necesarias en los equipos si estos fuesen a estar en producción

	* **jhurtadojerves** (1)

		
		Dani yo estoy intentado hacer eso, pero no logro configurar el enrutamiento ¿Algún tutorial que tengas?

	* **Daniel Fernández Santos** (1)

		
		@jhurtadojerves no tengo ningún tutorial, pero si quieres (me lo apunto para aún así hacerlo) te puedo enviar un diagrama sobre como sitúo las instancias y el enrutado (muchas veces solo envío el tráfico interno por la VPN y el resto por mi conexión normal, para que sea más barata la factura en AWS) que configuro en el servidor vpn

	* **jhurtadojerves** (1)

		
		Por favor dani, te lo agradecería un montón
		
		Quiero poder acceder a la red local de la oficina, el vpn está en un vps que tiene ip pública

## 0250. Instalación y configuración del cliente

### Descripción:


### Links:

* [Community Downloads | OpenVPN](https://openvpn.net/community-downloads/)

### Comentarios:

* **Jhoan Steve Sandoval Meneses** (3)

	
	Cuando clases de CDN en digitalocean

* **Juan José Castro** (3)

	
	Cuando me conecté a través de la interfaz tunnel entre mi pc local y el droplet, pasó algo gracioso… Cuando se estableció el tunnel vpn comencé a salir por internet a través de ese tunnel, es decir a través del droplet
	
	Mientras estaba viendo este último video, el mismo se pauso y cuando recargué la página apareció este error _
	
	Error 1005 Ray ID: 520c28a5b973cce2 • 2019-10-05 03:02:47 UTC  
	Access denied  
	What happened?  
	The owner of this website ([platzi.com](http://platzi.com)) has banned the autonomous system number (ASN) your IP address is in (14061) from accessing this website.
	
	Eso quiere decir que platzí está denegando toda ip que pertenezca el ASN 14061 (que es de Digital Ocean) . Tuve que bajar el tunnel para terminar del ver el video 😃

* **Juan José Castro** (2)

	
	Una de las aplicaciones que le daria a un droplet es para levantar juegos online solo por un dia o un par de horas para jugar con amigos (ej un quake 3)
	
	Digital Ocean sería una excelente opción para eso pero lamentablemente Digital Ocean no tiene servers dentro de mi país por lo tanto sería muy alto el delay.

* **estuardoramos** (2)

	
	pues en el marketplace había un droplet que me llamo la atención “Rocket.Chat”, la cual se ve interesante

	* **Santiago Bernal** (2)

		
		Rocket.chat se puede entender como un slack de código abierto.

* **darwinyusef** (2)

	
	faltaría no se si se aposible una migración con git de algún proyecto y no se si sea posible como funcionaría en digital ocean gitlab

	* **Santiago Bernal** (2)

		
		Una vez tienes acceso SSH a tu droplet, puedes clonar cualquier repositorio git que esté público (gitlab, github u otros) con el comando git clone <URL>
		
		Y luego seguir las instrucciones que te indique el archivo manifiesto ([readme.MD](http://readme.MD)) de dicho repositorio que clones.

* **yjnavas** (1)

	
	¿Se puede usar un droplet como Windows? Ejemplo: como cuando instalamos Windows en un VirtualBox y manejarlo tal cual como segunda maquina

	* **msantim** (2)

		
		Hola, nativamente no, Digital Ocean no ofrece esa opción, sin embargo sí se puede.
		
		[Mira un tutorial aqui](https://www.youtube.com/watch?v=cgkjjJA8rGc)

* **Pablo Segovia** (1)

	
	Si quisiera instalar una apliacion .net core? seria viable? o deberia buscar otras alternativas?

	* **Daniel Fernández Santos** (2)

		
		Los droplets de Digital Ocean son basados en Linux por lo que deberías poder ejecutar aplicaciones basadas en .NET Core sin mayor problema
		
		Te dejo un manual de la propia Microsoft para servidores basados en Ubuntu (vistos en este curso)
		
		[https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/linux-nginx?view=aspnetcore-2.1&tabs=aspnetcore2x](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/linux-nginx?view=aspnetcore-2.1&tabs=aspnetcore2x)

* **Kerohuixco** (1)
Soy nuevo en el tema de VPN. ¿Para que sirve exactamente hacer esto?

	* **Santiago Bernal** (1)

		
		Una VPN (red privada virtual) es una tecnología que te permite “salir” hacia internet desde un servidor VPN.
		
		Esto tiene varios fines:
		
		  * Usar una dirección IP para salir a internet
		  * Conectarte con otros equipos que estén distribuidos geográficamente
		  * Cifrar la conexión entre tu dispositivo y el servidor VPN antes de salir a internet, es muy útil cuando estás en un café internet o en zonas wifi públicas.
		
		

# Conclusiones

## 0260. Conclusiones finales del curso

### Descripción:


**¡Felicitaciones por terminar el Curso de Digital Ocean**

> _Digital Ocean te da la infraestructura para llevar tu proyecto en tu computador hacia internet_  
>  **\- Santiago Bernal**

Sabemos que ha sido un largo camino, pero estamos seguros de que valió la pena y **nunca vas a parar de aprender**.

### Comentarios:

* **tomas-alegre146** (3)

	
	Hay una pregunta en la prueba que pregunta cuales son los parámetros requeridos para crear un Droplet, la respuesta incluye las SSH_KEY como requerido, pero según la documentación de DigitalOcean “SSH_KEY” no es un parámetro requerido.  
	Dejo el link de la documentación de la API de DO  
	<https://developers.digitalocean.com/documentation/v2/#create-a-new-droplet>

	* **cjochoa** (1)

		
		igual tuve problemas con esa pregunta, gracias!

* **lgzeus** (1)

	
	A mi parecer faltó información acerca de manejo de usuarios en el servidor, siento que manejarlo todo a través del usuario root no es una muy buena práctica

	* **Jorge Palacios** (2)

		
		Yo asumo que fue por velocidad. Pues el curso de manejo de servidores atiende todos esos detalles.

* **Roberto Alejandro Agudelo Callejas** (1)

	
	Muy bueno el curso pero en mi opinión esta incompleto porque quedaron faltando 2 cosas muy importantes por configurar  
	1- Configurar un dominio, ejemplo [misitioweb.com](http://misitioweb.com) en vez de tener <http://67.205.179.249/>  
	2-Configurar el certificado SSL importantismo este último paso el de configurar el cerficado SSL, ya hoy en día es casi que obligatorio tener instalado el certificado SSL.  
	Por favor si alguien me puede ayudar compartiendo un video tutorial para realizar estos dos pasos que quedaron faltando en el curso.

	* **Luis Diaz Venero** (1)

		
		Hola, para configurar tu dominio:
		
		  1. En el menu lateral “Manage” elige la opción “Networking”
		  2. Ingresa tu dominio en la casilla “Enter domain”, lo asocias al proyecto en curo y clic en “Add Domain”.
		  3. Finalmente apareceran los registros ns, los copias y pegas en tu panel de control de dominio
		  4. Hay una guia que te puede ayudar segun donde lo hayas registrado: <https://www.digitalocean.com/community/tutorials/how-to-point-to-digitalocean-nameservers-from-common-domain-registrars>
		
		
		
		Lo del SSL lo puedes hacer con Lets Encrypt <https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04>
		
		Espero te sirva de ayuda, saludos.

* **agustin123456789** (1)

	
	Muy bueno!!

