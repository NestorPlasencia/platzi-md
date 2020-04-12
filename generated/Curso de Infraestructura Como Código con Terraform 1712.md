[Curso de Infraestructura Como Código con Terraform 1712](https://platzi.com/cursos/devops-terraform)

# Conocer qué es infraestructura como codigo [4578]

## 0010. Infraestructura como código [22848](https://platzi.com/clases/1712-devops-terraform/22848-infraestructura-como-codigo/)

### Descripción:


Bienvenido al Curso de Infraestructura como código con Terraform, tu profesora Yolanda Lopez te compartirá toda su experiencia y conocimientos en:

* Infraestructura como código.
* Infraestructura inmutable.
* Terraform, Docker y AWS.



## ¿Qué es infraestructura como código?

Es una práctica que utiliza principios de desarrollo de software buscando automatizar los procesos de crear infraestructura. Los principios que siguen cada sistema son:

* Se pueden reproducir fácilmente.
* Son desechables.
* Son consistentes.
* Son repetibles.
* El diseño siempre está cambiando.



## Prácticas generales.

* Utilizar un archivo de definición.
* Sistemas y procesos autodocumentados.
* Versionar todo.
* Preferir cambios pequeños.
* Mantener los servicios continuamente disponibles.



### Links:

* [Fundamentos de Docker](https://platzi.com/cursos/docker/)

* [Curso de Fundamentos de AWS Cloud](https://platzi.com/cursos/aws-cloud/)

### Comentarios:

* **Alexei Teófilo Mamani Coaquira** (3) [69158](https://platzi.com/comentario/752186/) 
A darle!!

* **vanesora** (1) [946485](https://platzi.com/comentario/946485/) 

	Por que usar MAC para ello?
	
	Has sentido alguna ventaja al hacerlo?

	* **Cristian Caballero** [946485] (1)

		La consola (terminal) es mas potente que la de Windows, asi que por eso para esto y muchas otras (de índole similar) cosas es mas útil Mac o Linux, aunque por suerte el año pasado Microsoft anuncio que mejorara la propia así que pronto ya no deberia haber diferencia entre cual usar

* **Christian Hugo López Bazán** (1) [860922](https://platzi.com/comentario/860922/) 

	Interesante el concepto de infraestructura como código.

* **juliobueso** (1) [848923](https://platzi.com/comentario/848923/) 

	Viendo…

* **Miguel Ángel Bocanegra** (1) [822489](https://platzi.com/comentario/822489/) 

	Okidoki

## 0020. Tipos de herramientas para implementar infraestructura como código [22849](https://platzi.com/clases/1712-devops-terraform/22849-tipos-de-herramientas-para-implementar-infraestruc/)

### Descripción:


Aprende más en el Curso de Infraestructura como código con Terraform en Platzi disponible en tu suscripción en: <https://platzi.com/cursos/devops-terraform/>  
Adquiere hoy la suscripción de Platzi en: <http://platzi.com/precios>

En esta clase la profesora Yolanda Lopez nos explica qué tipos de herramientas podemos usar para implementar infraestructura como código.

Existen dos tipos de herramientas para esto, las centradas en definir la infraestructura y las encargadas de configurar el servidor ya montado. Dentro de las herramientas para definir infraestructura existen Terraform, Cloud Formation, Open Stack Heat, estas herramientas especifican que elementos y recursos vamos a crear y cómo deben configurarse.

Ansible, Chef y Puppet son herramientas para configuración de servidores que nos permiten darle el estado deseado a nuestra infraestructura.

Al momento de elegir una herramienta debemos tomar en cuenta:

* Modo desatendido para herramientas de líneas de comandos.
* Idempotencia.
* Parametrizable.



### Comentarios:

* **Javier Bernal Mateus** (2) [802446](https://platzi.com/comentario/802446/) 

	terraform en Oracle Cloud Gen2 -> [https://gitlab.com/oscarbm7/terraform_oci/](url)

* **grizzlywasright** (1) [1034993](https://platzi.com/comentario/1034993/) 

	Qué interesante poder replicar instancias de forma automatizadas y servidores con cierta configuración.
	
	Esto tiene algo que ver con defenderse de un ataque DDoS? En el sentido de crecer la infraestructura para aguantar el ataque?

* **Miguel Ángel Bocanegra** (1) [822525](https://platzi.com/comentario/822525/) 

	ok

## 0030. Beneficios de la infraestructura como código [22850](https://platzi.com/clases/1712-devops-terraform/22850-beneficios-de-la-infraestructura-como-codigo/)

### Descripción:


* Creación rápida bajo demanda.
* Automatización.
* Visibilidad y trazabilidad, todos los cambios quedan registrados.
* Ambientes homogéneos, una misma definición permite crear varios ambientes.
* Fácil de testear.



### Comentarios:

* **Jean Carlos Nuñez Hernandez** (3) [747892](https://platzi.com/comentario/747892/) 

	Esta interesante esta herramienta hay que probarla

* **Edwin De Jesus Chiyopa Garcia** (2) [773566](https://platzi.com/comentario/773566/) 

	Me interesa seguire con este curso

* **grizzlywasright** (1) [1034998](https://platzi.com/comentario/1034998/) 

	Excelentes beneficios. Espero con ansía y mucho júbilo el resto del curso

* **Jorge Hernández** (1) [1021411](https://platzi.com/comentario/1021411/) 

	¿Cual es la herramienta para testear la infraestructura?

* **Christian Hugo López Bazán** (1) [863368](https://platzi.com/comentario/863368/) 

	Infraestructura como código - beneficios:  
	1 - Definición de archivo de configuraciones (bajo demanda y automatizado).  
	2 - Utiliza el versionamiento (visibilidad y trazabilidad).  
	3 - Se puede recrear ambientes homogéneos (cambiando ciertos parámetros).  
	4 - Sencillo de testear con múltiples herramientas.

* **Miguel Ángel Bocanegra** (1) [823859](https://platzi.com/comentario/823859/) 

	ready

# Entender qué es Terraform [4579]

## 0040. ¿Qué es Terraform [22851](https://platzi.com/clases/1712-devops-terraform/22851-que-es-terraform/)

### Descripción:


Terraform es una herramienta Open Source desarrollada en Go por HashiCorp que permite crear y administrar infraestructura. Funciona gracias a que interactúa con las APIs de los proveedores de nube.

## Características clave

* Es una herramienta de infraestructura como código.
* Tiene planes de ejecución.
* Sencillo de automatizar.



### Comentarios:

* **Miguel Ángel Bocanegra** (1) [823871](https://platzi.com/comentario/823871/) 

	ok

## 0050. Terraform versus otras herramientas de infraestructura como código [22852](https://platzi.com/clases/1712-devops-terraform/22852-terraform-versus-otras-herramientas-de-infraestruc/)

### Descripción:


Gestionar y crear la infraestructura son dos conceptos muy distintos. Algunas herramientas como Ansible que es para gestión también nos permiten crear infraestructura aunque tiene muchas limitantes, lo mejor es trabajar en conjunto con Terraform para crear la infraestructura.

Existe la infraestructura mutable e inmutable, para la infraestructura mutable una mejora sobre nuestra instancia se realiza sobre la misma instancia, el estado del servidor cambio, mientras que la infraestructura inmutable destruye nuestra instancia y crea una nueva al momento de implementar cambios.

Terraform utiliza lenguaje declarativo, le indicamos qué debe hacer en lugar de cómo hacerlo como suele ser en el lenguaje procedural o imperativo.

### Comentarios:

* **vanesora** (2) [946568](https://platzi.com/comentario/946568/) 

	Aunque la infraestructura inmutable claramente trae sus ventajas claras, pero siempre será más costoso y con delay con respecto al mutable

* **Marcoh** (1) [871246](https://platzi.com/comentario/871246/) 

	Con cual herramienta recomiendan complementar terraform, ansible, chef o puppet?.

	* **javierbanguero** [871246] (1)

		Hola, depronto este articulo te puede ayudar.
		
		<https://logdna.com/chef-puppet-ansible-configuration-management/>

* **Miguel Ángel Bocanegra** (1) [823870](https://platzi.com/comentario/823870/) 

	nice

* **Edwin De Jesus Chiyopa Garcia** (1) [773570](https://platzi.com/comentario/773570/) 

	nunca eh usado ansible pero espero no sea neesario saber un poco de el para este curso

	* **yolandalopez** [773570] (3)

		No es necesario. no es una herramienta que se utiliza en el curso. solo se menciona como referencia para entender que diferencia a Terraform de otras herramientas.

# Aprender a usar Herramientas para construir infraestructura inmutable [4580]

## 0060. Packer elementos y comandos [22853](https://platzi.com/clases/1712-devops-terraform/22853-packer-elementos-y-comandos/)

### Descripción:


Packer es una herramienta para construir infraestructura inmutable desarrollada por HashiCorp que nos va a permitir crear imágenes en cualquier proveedor de nube.

## Elementos de Packer

* `variables`: tal como su nombre lo indica, aquí definimos las variables que vamos a utilizar.
* `builders`: indicamos de donde vamos a construir nuestra imagen base.
* `provisioners`: acá personalizamos nuestra imagen, añadir paquetes, crear directorios, definir el estado de la infraestructura, etc.
* `post-processors`: podemos tener archivos de salida y ejecutar comandos después de haber creado la infraestructura, todo corre de manera local.



### Links:

* [Install Packer - Getting Started - Packer by HashiCorp](https://packer.io/intro/getting-started/install.html)

* [Download Packer - Packer by HashiCorp](https://packer.io/downloads.html)

### Comentarios:

* **jscontreras** (8) [754202](https://platzi.com/comentario/754202/) 

	MAC users
	
	si tienes hombrew
	``` 
	    brew install packer
	    
	```
	
	de nada

* **ricardo-rod** (5) [747854](https://platzi.com/comentario/747854/) 

	Esta instalacion es valida para la gran mayoria de Linux y el binary
	``` 
	    curl -o packer.zip  https://releases.hashicorp.com/packer/1.4.3/packer_1.4.3_linux_amd64.zip
	    unzip packer.zip; sudo mv packer /usr/bin/; rm packer.zip
	    
	```
	
	<h1>para que usen el auto-completion de bash o de Z</h1>
	``` 
	    packer -autocomplete-install
	    
	```
	
	Anatomy packer file: notas rapidas.
	
	Variables y builders: se usan en el localhost que estemos usando.
	
	provisioners: se ejecutan en la maquina que estamos creando.
	
	post-processors: se ejecuta en nuestro localhost.
	
	Estoy revisando el curso full aunque ya se terraform pero me gusta ver como puedo ayudar en la comunidad!!!

	* **yolandalopez** [747854] (1)

		Excelente, Ricardo. Muchas gracias por tus aportes.

* **Viviana Paola Romero Rojas** (1) [76526](https://platzi.com/comentario/888787/) 
hola, como seria instalarlo en Windows ? gracias!

	* **Erik Ochoa (Platzi)** [76526] (3)

		Aquí puedes [bajar](https://www.packer.io/downloads.html) su versión para windows.

## 0070. Packer y Terraform en Windows [22854](https://platzi.com/clases/1712-devops-terraform/22854-packer-y-terraform-en-windows/)

### Descripción:


### Links:

* [Download Terraform - Terraform by HashiCorp](https://www.terraform.io/downloads.html)

* [Download Packer - Packer by HashiCorp](https://packer.io/downloads.html)

### Comentarios:

* **Ricardo Andres Romero Gomez** (1) [1035886](https://platzi.com/comentario/1035886/) 

	Packer también funciona para crear imágenes en Azure? por lo menos si yo quiero automatizar la creación de LAMP stack + wordpress con Ansible y Terraform en Azure, Packer me podría ayudar para esto?

	* **Diego Alexander Forero Higuera (Platzi)** [1035886] (1)

		Si, tanto packer como terraform funcionan con la mayoría de proveedores de nubes, aquí te dejo el enlace a la documentación de packer para azure <https://packer.io/docs/builders/azure.html> lo que varía es la configuración de las credenciales y los recursos para crear la imagen.

* **Miguel Ángel Bocanegra** (1) [823931](https://platzi.com/comentario/823931/) 

	done

* **Christian Hugo López Bazán** (1) [80491](https://platzi.com/comentario/959993/) 
Buen día, abro VS Code, presiono la opción “debug” y me muestra lo siguiente: Como puedo llegar a las mismas herramientas que se muestra...

* **jbravo_imco** (1) [69348](https://platzi.com/comentario/755555/) 
Pero entonces en Linux como empiezo un proyecto me quedo claro como instalar packer pero ahora terraform?

	* **yolandalopez** [69348] (1)

		Hola, en la clase 12 esta la instación de terraform. 😃[Instalar y configurar terraform ](https://platzi.com/clases/1712-devops-terraform/22859-instalar-terraform-y-configurar-una-cuenta-de-aws-/)

## 0080. Credenciales de AWS en Windows [22855](https://platzi.com/clases/1712-devops-terraform/22855-credenciales-de-aws-en-windows/)

### Descripción:


### Links:

* [AWS Console - Signup](https://portal.aws.amazon.com/billing/signup#/start)

### Comentarios:

* **Edwin De Jesus Chiyopa Garcia** (3) [773581](https://platzi.com/comentario/773581/) 

	la url que viene esta mal les agrego la url donde se encuentra la info  
	<https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html>

* **Viviana Paola Romero Rojas** (1) [76681](https://platzi.com/comentario/891279/) 
hola 😃, para poder crear la cuenta de aws, donde es espeficamente? saludos!

	* **Juan Felipe Peralta Zapata (Platzi)** [76681] (3)

		¡Hola, Viviana! ⚡
		
		En esta clase del **curso de fundamentos de AWS Cloud** te enseñan a crear tu cuenta:
		
		* [¿Cómo puedo empezar a usar AWS?](https://platzi.com/clases/1323-aws-cloud/12574-como-puedo-empezar-a-usar-aws/)
		
		

## 0090. Packer Demo [22856](https://platzi.com/clases/1712-devops-terraform/22856-packer-demo/)

### Descripción:


# Packer

Es una herramienta para construir imagines casi en cualquier proveedor de nube.

### Instalación

En este link se encuentran las instrucciones para instalar packer en los diferentes sistemas operativos. En este documento se detallan las instrucciones para sistema operatio Mac y Linux.

* <https://www.packer.io/intro/getting-started/install.html>


``` 
    $ curl -o /tmp/packer.zip https://releases.hashicorp.com/packer/1.4.2/packer_1.4.2_darwin_amd64.zip 
    
    $ unzip /tmp/packer.zip -d /usr/local/bin
    
    ## En el siguiente link se encuentra la url de los binarios para los demas sistemas operativos https://www.packer.io/downloads.html
    
```

### Demo

En esta demo se creara una AMI para AWS con una llave publica personalizada y con docker. En esta demo se asumirá que ya tienes una cuenta de AWS previamente creada.

* Crear un usuario en tu cuenta de AWS y obtener las credenciales (secret_id y secret_key) de AWS.
* Configurar las credenciales como variables de entorno.
```     $ export AWS_ACCESS_KEY_ID=""
     $ export AWS_SECRET_ACCESS_KEY=""
    
```

* Dentro del directorio `scripts`se encuentra la llave publica que se agregara a la imagen base resultante. Por cuestiones se seguridad no se encuentra la llave privada por lo que se sugiere que se cree un set de llaves y se remplace el contendido del archivo `scripts/packer-key.pub` por el valor de llave publica generada (.pub). Para generar el set de llaves puedes seguir las siguientes instrucciones:
```    $ ssh-keygen -f ~/.ssh/packer-key -t rsa
    # Este comando generará 2 archivos "packer-key" que contiene la llave privada y "packer-key.pub" que contiene la llave publica, el contenido de esta es el que e reemplazara en el archivo "scripts/packer-key.pub" dentro de esta carpeta.
    
```

* Para validar la sintaxis del archivo de definición que contiene todas las configuraciones necesarias se ejecutará el siguiente comando:
```    $ cd demo-packer
    $ packer validate aws-ami.json
    
```

* Finalmente se procede a crear el AMI en la cuenta de AWS configurada previamente. y para ello es necesario ejecutar el siguiente commando
```    $ cd demo-packer
    $ packer build aws-ami.json
    
```




### Links:

* [curso-terrafom/demo-packer at master · yolitals/curso-terrafom · GitHub](https://github.com/yolitals/curso-terrafom/tree/master/demo-packer)

### Comentarios:

* **ricardocelis (Platzi)** (5) [746634](https://platzi.com/comentario/746634/) 

	Hola, los archivos de este curso los encuentran aqui: <https://github.com/yolitals/curso-terrafom/tree/master/demo-packer>

* **Carlos Bustos** (2) [78180](https://platzi.com/comentario/916559/) 
Hola, como puedo crear las llaves desde Power shell? tks

	* **Diego Alexander Forero Higuera (Platzi)** [78180] (1)

		No se si es tarde, pero esto te puede servir <https://confluence.atlassian.com/bitbucketserver/creating-ssh-keys-776639788.html>

* **edg_colon** (1) [1085271](https://platzi.com/comentario/1085271/) 

	Hola, como genero otra llave ssh-rsa…
	``` 
	    ssh-rsa AAAAB3NzaC1y....PmU/iCfn yolandal@MacBook-Pro-de-Yolanda.local..
	    
	```
	
	Intente con:
	``` 
	    ssh-keygen -t rsa -C"edgar@numina.mx"
	    
	```
	
	Pero me agrega saltos de linea

	* **edg_colon** [1085271] (1)

		Ignoren mi comentario jeje, ya vi que era con:
		``` 
		    ssh-keygen -f ~/.ssh/packer-key -t rsa
		    
		```

* **Wilder Alexander David Hoyos** (1) [1048498](https://platzi.com/comentario/1048498/) 

	Para crear las variables de entorno en Windows con Powershell se ejecuta:
	``` 
	    $env:AWS_ACCESS_KEY_ID="clave"
	    $env:AWS_SECRET_ACCESS_KEY="clave"
	    
	    
	```
	
	Para revisar las varibles de entorno disponibles en el sistema windows usando Powershell, se ejecuta:
	``` 
	    Get-ChildItem Env:
	    
	```

* **Marilians** (1) [981452](https://platzi.com/comentario/981452/) 

	Referencia para instalar Docker en Debian Jessie (esta me fue bien):  
	<https://elbinario.net/2016/10/07/docker-instalacion-en-debian-jessie/>

* **Erick Daniel Brito Arroyo** (1) [847283](https://platzi.com/comentario/847283/) 

	Comparto archivo de packer usando el AMI de Ubuntu 18.04 LTS:
	``` 
	    {
	        "variables": {
	            "aws_access_key": "{{env `AWS_ACCESS_KEY`}}",
	            "aws_secret_key": "{{env `AWS_SECRET_KEY`}}"
	        },
	        "builders": [{
	             "type": "amazon-ebs",
	             "access_key": "{{user `aws_access_key`}}",
	             "secret_key": "{{user `aws_secret_key`}}",
	             "region": "us-east-2",
	             "source_ami": "ami-059d836af932792c3",
	             "source_ami_filter": {
	    	          "owners": ["099720109477"],
	                  "most_recent": true
	             },
	             "instance_type": "t2.micro",
	             "ssh_username": "ubuntu",
	             "ami_name": "packer-ubuntu {{timestamp}}",
	             "associate_public_ip_address": true
	         }],
	        "provisioners": [
	            {
	                "type": "file",
	                "source": "./scripts/packer-key.pub",
	                "destination": "~/.ssh/"
	             },
	             {
	                "type": "shell",
	                "inline": [
	                    "cat ~/.ssh/packer-key.pub >> ~/.ssh/authorized_keys"
	                ]   
	             },
	             {
	                 "type": "shell",
	                 "script": "scripts/install-docker.sh"
	             }
	         ]
	    }
	    
	    
	```

* **Hector Daniel Hernandez Castillo** (1) [828178](https://platzi.com/comentario/828178/) 

	wow, esto combinado con docker 7u7.  
	Los AMIs parece que son diferentes por región, yo estoy en us-west-2 y tuve que cambiarla.

* **Wilder Alexander David Hoyos** (1) [84373](https://platzi.com/comentario/1049412/) 
Tengo el siguiente error al ejecutar packer build aws-ami.json ==> amazon-ebs: Prevalidating any provided VPC information ==>...

* **Andrés Muñoz** (1) [81674](https://platzi.com/comentario/986705/) 
Por qué eliges centos ?

* **Henry Hormaza** (1) [80456](https://platzi.com/comentario/959247/) 
Hola, ayuda, algo estaré haciendo mal con la generación de las ssh Keys, alguno podría ayudarme con una explicación más detallada de cómo...

	* **Diego Alexander Forero Higuera (Platzi)** [80456] (2)

		Hola, cuéntanos con más detalle que problema tienes y como estas generando las llaves y con gusto te ayudamos.

* **Alejandro Velazquez Mercado** (1) [68915](https://platzi.com/comentario/748356/) 
Como se obtiene el source_ami_filter?

	* **Diego Alexander Forero Higuera (Platzi)** [68915] (2)

		Tienes que usar el API de AWS por ejemplo donde se encuentran las descripciones de las imagenes <https://docs.aws.amazon.com/en_pv/AWSEC2/latest/APIReference/API_DescribeImages.html> consultas los datos de la imagen (AMI) que deseas usar.

## 0100. Docker Conceptos clave [22857](https://platzi.com/clases/1712-devops-terraform/22857-docker-conceptos-clave/)

### Descripción:


Docker es una herramienta que nos permite crear infraestructura inmutable permitiéndonos encapsular y portar nuestras aplicaciones en una misma imagen logrando que instanciemos la misma imagen la cantidad de veces que queramos.

## Imagen

Es una capa creada a partir de un archivo `Dockerfile` donde definimos la imagen base, todos los paquetes que vayamos a utilizar, directorios, etc.

## Container

Un container es una instancia de una imagen de Docker. No tienen estado, no deben guardar ningún tipo de información.

### Links:

* [Fundamentos de Docker](https://platzi.com/clases/docker/)

### Comentarios:

## 0110. Docker Demo [22858](https://platzi.com/clases/1712-devops-terraform/22858-docker-demo/)

### Descripción:


<https://github.com/yolitals/curso-terrafom/tree/master/demo-docker>

### Links:

* [Docker Hub](https://hub.docker.com/)

* [Fundamentos de Docker](https://platzi.com/clases/docker/)

### Comentarios:

* **Edgar de Jesus Mendoza Ortegon** (3) [818538](https://platzi.com/comentario/818538/) 

	Curso muy bueno y bien explicado. Gracias Yolanda!!!

* **Wilder Alexander David Hoyos** (1) [1061362](https://platzi.com/comentario/1061362/) 

	Pueden descargar los repositorios desde esta URL:
	
	<https://github.com/dahwild/docker-demo/tree/master>

* **Wilder Alexander David Hoyos** (1) [1061267](https://platzi.com/comentario/1061267/) 

	Si queremos dejar el contenedor creado se puede ejecutar:
	``` 
	    dockercreate-p 3003:80[Nombre_Imagen]
	    
	```
	
	Al momento que se desee usar el contenedor se puede ejecutar docker start con el id_contenedor o nombre_contenedor:
	``` 
	    docker start [id_contenedor]
	    
	    docker start [nombre_contenedor] 
	    
	```
	
	Para detenerlo se ejecuta:
	``` 
	    docker stop [id_contenedor]
	    
	```
	
	Para eliminar el contenedor:
	``` 
	    docker rm [id_contenedor]
	    
	```

* **DaRk452** (1) [820733](https://platzi.com/comentario/820733/) 

	Muy buen ejemplo 😃

* **ricardocelis (Platzi)** (1) [749883](https://platzi.com/comentario/749883/) 

	<https://github.com/yolitals/curso-terrafom/tree/master/demo-docker>

# Primeros pasos con Terraform [4581]

## 0120. Instalar terraform y configurar una cuenta de AWS en Mac [22859](https://platzi.com/clases/1712-devops-terraform/22859-instalar-terraform-y-configurar-una-cuenta-de-aws-/)

### Descripción:


### Links:

* [Download Terraform - Terraform by HashiCorp](https://www.terraform.io/downloads.html)

### Comentarios:

* **Juan Francisco Mosquera** (1) [1097094](https://platzi.com/comentario/1097094/) 

	Disculpa , me perdí packer y terraform sirven para lo mismo ?

	* **edg_colon** [1097094] (1)

		Por lo que entiendo no, packer solo te crea una (imagen) AMI, aunque en el proceso te levanta una instancia de EC2 para crear el AMI, una vez que se crea el ami la instancia de EC2 se pasa a TERMINATE, y en el apartado de AMIS de la consola de AWS ya puedes ver tu ami que recién se creo, que es la que usaras con terraform, pero en este caso ya tienes docker y la llave ssh para conectarte a la instancia que crees con terraform…

## 0130. Definición en código Sintaxis y elementos de Terraform [22860](https://platzi.com/clases/1712-devops-terraform/22860-definicion-en-codigo-sintaxis-y-elementos-de-terra/)

### Descripción:


Nuestro archivo principal no necesariamente debe llamarse _[main.tf](http://main.tf)_ , pero una buena práctica es nombrarlo de esta manera.

Dentro del archivo podemos definir la infraestructura sin ningún orden, pero una buena práctica es definir primero el Cloud Provider, luego los recursos que vamos a utilizar de la siguiente manera:
``` 
    provider “aws” {
      region = ”us-east-2”
    }
    
    resource “aws_instance” “platzi-instance” {
      ami = ””
      instance_type = ”t2.micro”
      tags= {
        Name = ”practica1”
        Environment = “”Dev
      }
    }
    
```

Antes de validar nuestro archivo de configuración debemos correr el comando `terraform init` para que se inicialice nuestro entorno con los plugins necesarios, una vez listo corremos `terraform validate` para validar la sintaxis de nuestro archivo.

Si todo salió bien, podemos visualizar los recursos que vamos a crear con Terraform utilizando el comando `terraform plan`, al final nos va a mostrar cuántos recursos añade, cambia o elimina.

Para crear la infraestructura simplemente corremos el comando `terraform apply` y con ello Terraform empieza a crear nuestras instancias.

### Links:

* [Curso de Fundamentos de AWS Cloud](https://platzi.com/clases/aws-cloud/)

### Comentarios:

* **Felipe Acosta** (1) [842120](https://platzi.com/comentario/842120/) 

	Yolanda dice que el lenguaje es **ACL** pero creo que se equivoco es **HCL HashiCorp Configuration Language**

* **Felipe Acosta** (1) [842116](https://platzi.com/comentario/842116/) 

	Here a plugin of Terraform for VSCODE <https://marketplace.visualstudio.com/items?itemName=mauve.terraform>

* **Carlos Bustos** (1) [78966](https://platzi.com/comentario/930771/) 
Hola comunidad, Alguien me puede indicar como puedo listar ami que no tenga cobros en AWS. Gracias

* **Edwin De Jesus Chiyopa Garcia** (1) [70381](https://platzi.com/comentario/774170/) 
Cual es la diferencia de usar terraform vs packer?, como funciona para windows y que fue del archivo credentials que se creo en clases an...

	* **jaime repizo** [70381] (3)

		Hola packer sirve para crear una AMI, mientras terraform crea la infraestructura con código en cualquier provider ejemplo AWS o Azure.

## 0140. Proveedores de la nube con los que puede interactuar Terraform [22861](https://platzi.com/clases/1712-devops-terraform/22861-proveedores-de-la-nube-con-los-que-puede-interactu/)

### Descripción:


[Terraform soporta múltiples proveedores de la nube](https://www.terraform.io/docs/providers/index.html), entre ellos se encuentra:

* Heroku
* Digital Ocean
* OpenStack
* UCloud



Aunque Terraform te permite crear infraestructura para distintos cloud provider, un mismo archivo de definición para AWS no te va a servir para crear instancias dentro de GCP, cada cloud provider tiene sus propios recursos y parámetros.

### Links:

* [Providers - Terraform by HashiCorp](https://www.terraform.io/docs/providers/index.html)

* [Providers - Terraform by HashiCorp](https://www.terraform.io/docs/providers/index.html)

* [Providers - Terraform by HashiCorp](https://www.terraform.io/docs/providers/index.html)

### Comentarios:

* **Edwin De Jesus Chiyopa Garcia** (1) [774284](https://platzi.com/comentario/774284/) 

	Como puedo construir imagenes docker desde terraform y enviar solo la imagen final a host remoto sin publicar mi imagen en docker hub, ademas de implementarlo en un cluster de swarm de docker?

	* **yolandalopez** [774284] (1)

		Hola Edwin. Si puedes construir tu imagen con terraform, con este provider: <https://www.terraform.io/docs/providers/docker/index.html>. sin embargo si es necesario que publiques tu imagen, no es necesario que sea docker hub. Si utilizas AWS, Azure o GCP estas plataformas te brindan un registry privado para poder almacener imagenes. y luego ya utilizarlas en tu docker swarm. Recuerda que los ymls de definición de SWARM especificas el path completo de la imagen (Incluyendo el registry) Si es posible copiar la imagen de un host a otro, al final de cuentas son archivos. sin embargo esto no es escalable lo mejor es que tengas tus imagenes centralizadas en un registry.

	* **Omar Alvarez** [774284] (1)

		Adicional existe la posibilidad de subir tu imagen a Github yo lo usaba y es bueno tiene algunas limitantes pero depende mucho de las images que quieras almacenar <https://github.com/features/packages>
		
		Por ultimo existe otra opción para tener un registry privado en tu infraestructura yo uso Harbor es muy bueno y tiene caracteristicas excelentes para el analisis de vulnerabilidades en tus imagenes <https://goharbor.io/>

# Profundizando en Terraform [4582]

## 0150. Archivos de definición y variables [22862](https://platzi.com/clases/1712-devops-terraform/22862-archivos-de-definicion-y-variables/)

### Descripción:


Nuestro archivo de configuración de momento no es muy reutilizable ya que todos los valores se encuentran ya definidos, Terraform nos permite que en lugar de añadir valores estáticos podamos definir nuestro archivo con variables.

Las variables dentro de Terraform se deben definir e instanciar, una buena práctica es tener definidas las variables en un archivo e instanciarse en otro.

Terraform nos permite usar variables de tipo String, List y Map. A cada variable podemos añadirle un valor por default, una descripción y el tipo de la variable, actualmente Terraform identifica el tipo de variable automáticamente.

El archivo donde asignamos los valores de las variables debe terminar en _.tfvars_.

### Comentarios:

* **juan-sebastian-otero** (1) [839446](https://platzi.com/comentario/839446/) 

	En VS Code la extesión de Anton Kulikov de Terraform ya soporta la versión 0.12 de Terraform, para que no les marque error cuando declaren variables.

	* **Felipe Acosta** [839446] (1)

		Url de la extension <https://marketplace.visualstudio.com/items?itemName=4ops.terraform>

* **edisoncastro14** (1) [747913](https://platzi.com/comentario/747913/) 

	Que se identifique el tipo de variable usado se puede hacer desde terraform 0.12, más información acá <https://www.terraform.io/docs/configuration/variables.html>

* **Alejandro Velazquez Mercado** (1) [68920](https://platzi.com/comentario/748396/) 
como se puede asignar un aws keypair a la instancia?

	* **Diego Alexander Forero Higuera (Platzi)** [68920] (2)

		Cuando creas la instancia puedes asignarle la propiedad `key_name` esta propiedad tiene el valor del nombre de la llave como esta creada en aws.
		``` 
		    resource "aws_instance""web" {
		      ami           = "${data.aws_ami.ubuntu.id}"
		      instance_type = "t2.micro"
		      key_name = "mi-llave"
		    
		      tags = {
		        Name = "HelloWorld"
		      }
		    }
		    
		```

## 0160. Interpolación, condiciones y ciclos [22863](https://platzi.com/clases/1712-devops-terraform/22863-interpolacion-condiciones-y-ciclos/)

### Descripción:


Recuerda que para indicarle a Terraform nuestro archivo con los valores de variables corremos el comando:
``` 
    terraform plan -var-file tu_archivo.tfvars
    
```

Si nombramos nuestro archivo de variables _.auto.tfvars_ ya no será necesario pasarle el parametro -var-file a Terraform.

## Dynamics

Usando la palabra reservada **dynamic** podemos iterar sobre un objeto para que Terraform configure varios recursos similares.

### Links:

* [AWS: aws_security_group - Terraform by HashiCorp](https://www.terraform.io/docs/providers/aws/r/security_group.html)

* [AWS: aws_security_group - Terraform by HashiCorp](https://www.terraform.io/docs/providers/aws/r/security_group.html)

### Comentarios:

## 0170. Security Group [22864](https://platzi.com/clases/1712-devops-terraform/22864-security-group/)

### Descripción:


### Links:

* [Curso de Fundamentos de AWS Cloud](https://platzi.com/clases/aws-cloud/)

### Comentarios:

* **Diego Alexander Forero Higuera (Platzi)** (2) [748440](https://platzi.com/comentario/748440/) 

	Para obtener una salida como por ejemplo una ip o algún otro valor luego de aplicar el comando apply se usa el archivo **[output.tf](http://output.tf)** con la siguiente estructura
	``` 
	    output "instance_ip" {
	        value = <instance_type>.<instance_name>.<property>
	    }
	    
	```

	* **yolandalopez** [748440] (1)

		Es correcto, de hecho puedes obtener el valor de cualquier tipo de recurso.
		``` 
		    output "instance_ip" {
		        value = <tipo_de_recurso>.<nombre_recurso>.<propiedad.>
		    }
		    
		```

# ¿Cómo gestiona terraform el estado de la infraestructura? [4583]

## 0180. Archivos de estados [22865](https://platzi.com/clases/1712-devops-terraform/22865-archivos-de-estados/)

### Descripción:


Terraform utiliza un estado donde almacena todas las configuraciones que vayas realizando, este archivo se llama _terraform.tfstate_. Este archivo en formato JSON contiene toda la información respecto a nuestra infraestructura. Debemos tener cuidado al manejar información sensible si utilizamos nuestro archivo sin encriptación ya que toda la información es visible.

### Comentarios:

* **Andrés Muñoz** (1) [81716](https://platzi.com/comentario/988168/) 
por que es inseguro un archivo local no encriptado, si solo yo voy a ver mi computador ? como otra persona podría acceder a este archivo ...

	* **LeoEsp** [81716] (1)

		Hola @andy-mc!
		
		Realmente hay muchas formas en las que pueden acceder a tus archivos no encriptados, hay técnicas como la de MITM(Man in the middle) que permite a terceros ver la información que compartes en tu red local y si no se encuentra encriptada sera fácil para el atacante ver la información compartida.
		
		te recomiendo ver el [Curso Básico de Seguridad Informática para Empresas](https://platzi.com/clases/seguridad-empresas/) donde se explica de manera fácil estos conceptos
		
		Si quieres aprender cosas más a fondo sobre el tema y detalles técnicos te sugiero el [Curso de Introducción a la Seguridad Informática](https://platzi.com/clases/seguridad-informatica/)
		
		Saludos!

## 0190. Archivos de Backends [22866](https://platzi.com/clases/1712-devops-terraform/22866-archivos-de-backends/)

### Descripción:


Terraform permite almacenar el estado de manera remota a través de **Backends**. Podemos almacenarlo en diferentes servicios de storage en la nube como S3 o Azure.

Entre sus muchas ventajas que trae el trabajar con backends son:

* Es más fácil trabajar en equipo.
* Facilita la integración continua.
* Mayor disponibilidad.



### Links:

* [Backend: Supported Backend Types - Terraform by HashiCorp](https://www.terraform.io/docs/backends/types/index.html)

* [Backend: Supported Backend Types - Terraform by HashiCorp](https://www.terraform.io/docs/backends/types/index.html)

### Comentarios:

## 0200. Creación de nuestro Backend con Terraform [22867](https://platzi.com/clases/1712-devops-terraform/22867-creacion-de-nuestro-backend-con-terraform/)

### Descripción:


### Comentarios:

* **johnaagudelo** (2) [761791](https://platzi.com/comentario/761791/) 

	Cómo se puede manejar el backend para varios ambientes, dev y prod?

	* **yolandalopez** [761791] (4)

		Deberias tener un backend para cada ambiente. En la demo que hago, en la sección de backend esta el parametro **key** este valor es el nombre el el nombre de tu backend, este valor tambien se puedo enviar como parametro al momento de la ejecución cuando inicializas con el comando init. entonces podrias utilizarlo de esta forma para que sea mas sencillo identificar dev y prod. lo puedes hacer de esta forma:
		``` 
		    #prod 
		    terraform init --backend-config="key=prod/tfstate"
		    
		    #dev
		    terraform init --backend-config="key=dev/tfstate"
		    
		```

* **Miguel Andrés Isaza Barona** (1) [1016011](https://platzi.com/comentario/1016011/) 

	Para los que tengan problemas ejecutando terraforn init con el backend:
	
	  1. Deben crear una política que les permita tener acceso al bucket.
	  2. Deben exportar las credenciales como variables de entorno (no se si haya otra forma).
	
	

# Reutilizar las definiciones de terraform [4584]

## 0210. Encriptado de nuestro backend [22868](https://platzi.com/clases/1712-devops-terraform/22868-encriptado-de-nuestro-backend/)

### Descripción:


### Comentarios:

* **Andrés Felipe Ortiz Zambrano** (2) [924711](https://platzi.com/comentario/924711/) 

	Acá les dejo la pagina de la documentación de s3 en terraform [Link](https://www.terraform.io/docs/providers/aws/r/s3_bucket.html)

* **juan-sebastian-otero** (2) [840448](https://platzi.com/comentario/840448/) 

	En la sintaxis ya no son necesarios los caracteres “${}” (Terraform v0.12.16 o superior)

* **Wilder Alexander David Hoyos** (1) [1065320](https://platzi.com/comentario/1065320/) 

	Para eliminar el Bucker creado es necesario añadir en el archivo [backend.tf](http://backend.tf) el argumento:
	``` 
	    force_destroy= true
	    
	```
	
	Quedaría así:
	``` 
	      backend "s3" {
	        bucket = "backend-terraform-dahwild"
	        key    = "dev"
	        region = "us-east-2"
	        encrypt = true
	        # Enviar ARN del recurso que creó al archivo de estado
	        kms_key_id = "arn:aws:kms:us-east-2:511857092531:key/35f69747-5431-43eb-8897-4901a1c1b478"
	        force_destroy = true
	      }
	    }
	    
	```
	
	Si este argumento no se incluye no se va a poder eliminar el Bucket ya que este contiene información, luego de incluir esta información es necesario ejecutar los siguientes comandos:
	``` 
	    terraform plan
	    
	```
	``` 
	    terraform apply
	    
	```
	``` 
	    terraform destroy
	    
	```

* **nutsebap** (1) [1057262](https://platzi.com/comentario/1057262/) 

	Con **tflint** podemos hacer un “Lint” de nuestro código terraform
	
	<https://github.com/terraform-linters/tflint>

* **Hector Daniel Hernandez Castillo** (1) [831262](https://platzi.com/comentario/831262/) 

	1usd/mes por almacenar keys, no es caro pero para solo tener una key…

## 0220. Tips de la vida real Trabajo en equipo con backends [22869](https://platzi.com/clases/1712-devops-terraform/22869-tips-de-la-vida-real-trabajo-en-equipo-con-backend/)

### Descripción:


* Es una buena práctica tener el archivo de estado almacenado y versionado en algún Cloud Provider.
* Encriptar nuestro archivo de estado.
* Versionar nuestro backend.



### Comentarios:

## 0230. Módulos locales [22870](https://platzi.com/clases/1712-devops-terraform/22870-modulos-locales/)

### Descripción:


Así como en lenguajes de programación contamos con librerías, en Terraform podemos separar nuestro código y reutilizarlo a través de módulos. Dentro de nuestro módulo vamos a añadir el archivo de configuración y el de definición de variables.

### Comentarios:

* **JOSE DE JESUS USCANGA MOLINA** (1) [786826](https://platzi.com/comentario/786826/) 

	Por que se deben de declarar las variables tanto en el modulo como fuera de el para ser invocad, por que terraform hace eso.

	* **Erik Ricardo Sánchez Pérez** [786826] (1)

		Más que nada parece ser una buena practica como cuando documentas que variable vas a mandar a una clase que quieres crear.

	* **Luis Sánchez** [786826] (2)

		Es porque cada modulo es un fragmento de condigo independiente, así puedes usar tu modulo en otros projectos de terraform.

## 0240. Módulos remotos [22871](https://platzi.com/clases/1712-devops-terraform/22871-modulos-remotos/)

### Descripción:


Los módulos locales son útiles, pero tienen la limitante de que solamente se encuentran en tu máquina. Para mejorar el trabajo remoto y reutilización de módulos podemos usar el control de versiones de preferencia, ya sea GitHub o BitBucket.

### Comentarios:

# Práctica final y cierre [4585]

## 0250. Demo [22872](https://platzi.com/clases/1712-devops-terraform/22872-demo/)

### Descripción:


### Links:

* [Provisioners - Terraform by HashiCorp](https://www.terraform.io/docs/provisioners/index.html)

### Comentarios:

## 0260. Demo II [22873](https://platzi.com/clases/1712-devops-terraform/22873-demo-ii/)

### Descripción:


### Links:

* [Fundamentos de Docker](https://platzi.com/cursos/docker/)

### Comentarios:

* **Christian Acevedo** (2) [84909](https://platzi.com/comentario/1061991/) 
Hola, podrian poner el github de este demo, no esta en la página de github https://g...

* **jeisson-mayorga** (1) [1118240](https://platzi.com/comentario/1118240/) 

	Deberian colocar el proyecto completo no esta el [app.tf](http://app.tf) ni el archivo de variables solo el modulo que ella creo

* **Ricardo Andres Romero Gomez** (1) [1069941](https://platzi.com/comentario/1069941/) 

	Desde hace un par de clases atras me aparece el siguiente error y no encuentro el error .
	
	Error: Reference to undeclared resource
	
	on [output.tf](http://output.tf) line 2, in output “instance_ip”:  
	2: value = aws_instance.platzi-instance.*.public_ip
	
	A managed resource “aws_instance” “platzi-instance” has not been declared in  
	the root module.

* **Wilder Alexander David Hoyos** (1) [1068334](https://platzi.com/comentario/1068334/) 

	comparto url con el repositorio de este demo  
	<https://github.com/dahwild/modules-terraform>

* **JOSE DE JESUS USCANGA MOLINA** (1) [786934](https://platzi.com/comentario/786934/) 

	Hay que esperar que madure terraform , tiene areas de oportunidad , pero hay cosas como las declaraciones de las variables, los remotos que no me cuadran .

* **johnaagudelo** (1) [784732](https://platzi.com/comentario/784732/) 

	Si la infraestructura se esta corriendo desde CircleCi como se realiza la sincronización de la llave ssh?

	* **Joshua Nathanael Saucedo Uriarte** [784732] (0)

		personalmente en ese caso usaria packer, que cuando entre en CircleCi y todo esta bien, ejecute packer para hacer el AMI, y despues a terrafor le pasas ese AMI en una variable de entorno.
		
		puedes hacer un script que haga todo eso y que CircleCi lo ejecute  
		un ejemplo que hice aqui mismo en platzi
		
		<https://github.com/joshuansu0897/ExampleCI/blob/master/deployment/prod.sh>
		
		Saludos

## 0270. Cierre del curso [22874](https://platzi.com/clases/1712-devops-terraform/22874-cierre-del-curso/)

### Descripción:


¡Felicidades has llegado al final del curso!, para poner a prueba tus conocimientos:

* Aprueba el examen.
* Crea una aplicación con infraestructura inmutable usando Docker y Terraform, debes usar versionamiento en GitHub y usar backend en S3.  
Recuerda que puedes ampliar tus conocimientos con los cursos de [Docker](https://platzi.com/cursos/docker/) y [AWS](https://platzi.com/cursos/aws-cloud/).



### Comentarios:

* **Alejandro Velazquez Mercado** (2) [68942](https://platzi.com/comentario/748737/) 
Hola, ¿Cómo se accede al examen de este curso? Cuando realice la aplicación, ¿Cual es el paso siguiente?

	* **ricardo-rod** [68942] (2)

		Mi Jefe es que no esta dispobible el examen!!!, falta que lo hagan publico!!!, una vez este ready lo tomas y listo.

