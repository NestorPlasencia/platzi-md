# Introducción al curso

## 0010. Bienvenida

### Descripción:


 **¡Te damos la bienvenida al Curso de Azure IaaS!**

Este curso hace parte de la [Ruta de Aprendizaje de Azure](https://platzi.com/azure), donde estudiaremos **IaaS** y **PaaS** , los dos tipos de servicios de Microsoft Azure. Ninguno es mejor que el otro. Elegir entre uno u otro depende de la experiencia de nuestro equipo, requerimientos de los proyectos y nuestros gustos personales.

Al terminar este curso puedes continuar con los cursos de Azure PaaS:

  * [Curso de Almacenamiento en Azure](https://platzi.com/clases/almacenamiento-azure/)
  * [Curso de Azure SQL](https://platzi.com/clases/sql-azure/)
  * [Curso de Web Apps y Logic Apps en Azure](https://platzi.com/clases/web-apps/)



Nuestro profesor es Amin Espinoza, Ingeniero de Software en Microsoft Corporation.

### Comentarios:

* **Luis Garcia** (2)

	
	excelente curso.

* **Winston Barbosa** (2)

	
	Pinta bien…

* **Christian David Sánchez** (2)

	
	Iniciemos 😎

* **jlapazac** (1)

	
	Comencemos…!!

* **rmgelvez** (1)

	
	Vamos con Toda!

* **hectormauriciogarzoncastillo** (1)
Profe … Este curso me cae como anillo al dedo con lio que tengo. Monte en azure un firewall fortigate el cual se conecta con una VPN a ot...

## 0020. ¿Cuándo usar IaaS y cuándo usar PaaS

### Descripción:


 **Microsoft Azure** es un servicio que nos permite desplegar nuestros proyectos eligiendo entre diferentes herramientas con mayor o menor flexibilidad dependiendo de los requerimientos de nuestras aplicaciones.

**Azure IaaS** nos permite controlar totalmente la infraestructura. Trabajamos con máquinas virtuales, balanceadores de carga y VPNs para construir soluciones en la nube.

**Azure PaaS** es otro servicio que nos permite enfocarnos únicamente en el desarrollo de nuestra aplicación (sitios web, bases de datos, almacenamiento), dejando que Azure se encargue de la infraestructura por nosotros.

### Comentarios:

* **Alexander  Silvera** (3)

	
	Cual plataforma de la nube es más barato para subir una página web, AWS o Azure?? En cuestión de costos.

	* **Juan David Castro (Platzi)** (3)

		
		😉 Esta guía lo explica muy bien: [Cloud pricing comparison: AWS vs Azure](https://hub.packtpub.com/cloud-pricing-comparison-aws-vs-azure/).
		
		Al analizar los precios, debemos tener en cuenta muchos factores. Para qué lo vamos a usar, por cuánto tiempo, cuánto de la capa gratuita podemos aprovechar, entre otras. Como lo explica el profesor un poco más adelante en el curso, lo más importante es tener los objetivos claros. Luego de eso, podemos usar las calculadoras para estudiar a fondo los precios.

	* **Cristobal Vega** (3)

		
		Considero que también tiene que ver con que tipo de empresa u organización quieres o estás trabajando. Azure es usada en los grandes corporativos como parte de una suite completa de Microsoft, es decir desde Outlook, pasando por Excel hasta C#. Considero que depende del scope de la empresa en la cual trabajas también.

* **carlosbazanhuaman** (2)

	
	queda mas claro la diferencia entre IaaS y PaaS, creo que el precio de los servicios va diferenciar mucho de acuerdo a lo que se necesite.

	* **Juan David Castro (Platzi)** (2)

		
		Este artículo también te va a gustar: <https://platzi.com/blog/iaas-vs-paas/>. 😉

* **Luis Garcia** (2)

	
	gracias por la explicacion.

* **Christian David Sánchez** (2)

	
	Ahora ya entendí las diferencias entre IaaS y PaaS.  
	PaaS nos ayuda con la arquitectura.

	* **Juan David Castro (Platzi)** (2)

		
		En este artículo también estudiamos la diferencia entre IaaS y PaaS: <https://platzi.com/blog/iaas-vs-paas/>. 😉

	* **Christian David Sánchez** (2)

		
		Gracias @juandc

* **Aura Ludeña** (1)
Se menciona que un modelo PaaS no es mejor que un IaaS, sin embargo, los principales vendors define PaaS cómo una evolución de IaaS. Cómo...

## 0030. Presentando una Arquitectura

### Descripción:


Para construir nuestra aplicación vamos a configurar dos máquinas con el sistema operativo Ubuntu y un balanceador de cargas que evaluará a cuál de las máquinas debe enviar los requerimientos cuando nuestros usuarios intenten acceder.

Recuerda que este proyecto es solo uno de los muchos ejemplos de arquitecturas que podemos usar en Azure dependiendo de los requerimientos de nuestras aplicaciones.

### Comentarios:

* **Christian David Sánchez** (3)

	
	Esos “dibujitos” luego se convierten en magia 😎

* **James27** (2)

	
	Un Balanceador de carga fundamentalmente es un dispositivo de hardware o software que se pone al frente de un conjunto de servidores que atienden una aplicación y, tal como su nombre lo indica, asigna o balancea las solicitudes que llegan de los clientes a los servidores usando algún algoritmo.  
	<https://www.magiconline.es/ayuda/wp-content/uploads/2019/05/balanceo-entre-servidores.png>

* **carlosbazanhuaman** (1)
el balanceador es un servicios por el cual se paga?

	* **Juan David Castro (Platzi)** (1)

		
		Sí. Aquí puedes ver los precios de Azure: <https://azure.microsoft.com/es-es/pricing/details/load-balancer/>.

## 0040. ¿Máquinas virtuales o Contenedores ¿Cuál es la diferencia

### Descripción:


En todo momento, al hablar de infraestructura como servicio hablamos de máquinas virtuales, en este curso también estamos hablando de redes virtuales y balance de cargas. Puede parecer un tanto obsoleto, pero, por otro lado, ha sentado las bases de una nueva tendencia, los contenedores. ¿Has escuchado de ellos? Quizá el término de Docker puede venir a tu cabeza.

#### ¿Qué es Docker? ¿Qué es a lo que todos llaman contenedores?

Hay un curso en Platzi en donde Guido nos indica de qué va todo esto, se trata de una nueva tecnología que es capaz de “comprimir” en una imagen una solución que funcione a modo de servicio o sitio web. Una nueva manera de desplegarlos de manera completamente independiente a cualquier entorno o configuración. Básicamente es la solución definitiva a la terrible frase de “funcionaba bien en mi máquina”.

Las imágenes de Docker son una manera excepcional de aislar a nuestras soluciones de los equipos, puedes crear la imagen en una máquina con prestaciones sumamente bajas y desplegarla en un servidor sin problemas, o incluso de manera inversa. Como sea, no verás ningún cambio en lo absoluto en tu proyecto. Ahora, después de tener una imagen, desplegarla y hacerla productiva requerirá de un orquestador, algo que permita que esta imagen sea distribuida. Aquí es donde entra Kubernetes.

#### ¿Qué es Kubernetes y qué tiene que ver con IaaS?

Bueno, siguiendo el ciclo de vida de tu solución, esto sería como lo siguiente.

![azure 1.png](https://static.platzi.com/media/user_upload/azure%201-a8399b49-1c8d-48e5-ad1b-265f4bba8697.jpg)

Es decir, tu solución web estará hospedada en una imagen de Docker (contenedor), esta imagen estará hospedada en el clúster de Kubernetes, gracias a esto, Kubernetes se encargará de desplegar tu solución, monitorear su comportamiento, escalar o reducir tu solución entre otras muchas tareas más.

Si buscas soluciones altamente escalables entonces no tendrás muchas más opciones que Kubernetes orquestando tu solución, Google, el creador de este orquestador lo usa para su servicio de correo, sus mapas e incluso ¡para su buscador! Otros clientes como Netflix, Spotify e incluso el CERN lo usan para que sus soluciones globales puedan ser capaces de responder con eficiencia en todo momento.

Y aquí es donde se pone muy interesante. Un clúster de Kubernetes requiere de muchísima infraestructura trabajando de manera organizada. Un conjunto de máquinas virtuales, almacenamiento y redes.

Si buscas por el servicio de Kubernetes en Azure, obtendrás una imagen similar a la siguiente:  
![azure 2.png](https://static.platzi.com/media/user_upload/azure%202-9467884f-48ea-418c-aa7a-f928c11a984f.jpg)

Podrás apreciar que el servicio es gratuito, lo que tiene costo es toda la infraestructura creada para sostener este servicio y con ello los montos pueden variar de una manera gigantesca dependiendo directamente del nivel de exigencia que tu solución requerirá. Te anticipo que una solución de este tipo no es en lo absoluto nada barata pero, si es capaz de resolver la alta disponibilidad de tu sitio web entonces lo podrás ver como la mejor herramienta que podrías utilizar.

#### ¿Cuándo debería elegir Kubernetes y cuándo Máquinas virtuales?

Eso dependerá enteramente de tus planes y de tu experiencia. Si ya tienes un buen tiempo trabajando con las aplicaciones instaladas en la máquina entonces usar un conjunto de máquinas virtuales es la mejor opción, quizá un equipo paralelo podría comenzar a trabajar con un clúster en modo de pruebas para pensar en los detalles para establecer una migración en una etapa (y versión) posterior.

La realidad es que Kubernetes es una herramienta que involucra muchísima complejidad y eso significa que si no tienes experiencia en utilizarla y comienzas a hacerlo de manera inmediata para cualquier cuestión productiva entonces definitivamente tendrás un buen tiempo de estrés. Debido a su naturaleza lo mejor es ir ganando experiencia paso a paso para comprender muy bien su proceso. No pasará absolutamente nada si tu solución permanece de la manera en que la tienes por un par de versiones más.

En este curso nos enfocamos en todos los conceptos y herramientas que se requieren para que después puedas tener buenas bases y puedas implementar un clúster que no te cause conflictos, tener alta disponibilidad en tu solución basada en IaaS es el primer gran paso para después empezar a tener esa misma característica pero ahora por medio de un clúster de Kubernetes (comúnmente llamado solo K8) y tu solución administrada desde ahí.

### Comentarios:

* **Luis Garcia** (3)

	
	exelente aporte, me dio unas ideas gracias

* **carlosbazanhuaman** (2)

	
	una explicacion muy general pero te ayuda a entender mas conceptos, espero que podamos ver todo esto en el curso.

* **Christian David Sánchez** (2)

	
	Muy interesante el articulo 😮

* **Edwar Ferney Murillo Arboleda** (2)

	
	Interesante aclaración.

* **Rigo Antonio Galicia Barrera** (1)

	
	Me parece una buena explicación para saber a grandes rasgos sobre el tema.

# Máquinas Virtuales

## 0050. ¿Cómo elegir una Máquina Virtual con base en los requerimientos de tu aplicación

### Descripción:


Aprende más en el Curso de Azure IaaS: <https://platzi.com/azure-iaas>  
Adquiere hoy tu suscripción a Platzi en: <https://platzi.com/precios>

En esta clase estudiaremos cómo elegir una máquina virtual entre todas las opciones que nos ofrece Microsoft Azure. Esta decisión depende totalmente de los costos y requerimientos de tu aplicación.

Microsoft Azure es un servicio que nos permite desplegar nuestras aplicaciones eligiendo entre diferentes herramientas con un mayor o menor nivel de flexibilidad dependiendo de nuestras necesidades.

Podemos usar el servicio de Azure IaaS para controlar totalmente nuestra infraestructura. Aunque también existe Azure PaaS, otro servicio que nos permite enfocarnos únicamente en el desarrollo de nuestra aplicación, dejando que Azure se encargue de la infraestructura por nosotros.

### Comentarios:

* **Juan Manuel Quiñones Marí** (2)

	
	si necesitan profundizar en los sizecing o tipos de máquinas virtuales de azure les dejo el link de la documentacion.
	
	<https://azure.microsoft.com/es-es/pricing/details/virtual-machines/series/>

* **James27** (2)

	
	Sitio oficial de AZURE <https://azure.microsoft.com/en-us/> e información detallada sobre la arquitectura <https://docs.microsoft.com/en-us/azure/#pivot=architecture>

* **Christian David Sánchez** (2)

	
	Que buena clase 😎

* **tinguinito** (1)

	
	cantidad de categorías de Maquinas virtuales

* **gggabriel** (1)

	
	Los videos no abren desde la app de mi iPhone. Quisiera mi dinero de vuelta, gracias.

* **carlosbazanhuaman** (1)
en que casos o escenarios podriamos hacer el mejor uso de estas categorias?

## 0060. Galería de imágenes de Máquinas Virtuales

### Descripción:


Antes de elegir tu máquina virtual debes preguntarte:

  * ¿Para qué las vas a utilizar?
  * ¿Cuánto tiempo la mantendrás encendida?
  * ¿Se trata de una aplicación productiva o de investigación?
  * ¿Cuál será el retorno de inversión de tu máquina virtual?



Recuerda que el tamaño y costo de tu máquina virtual dependen al 100% de tu respuesta a estas preguntas.

### Comentarios:

* **JairoRa** (3)
Se puede practicar en Microsoft Azure de forma gratuita como en AWS?

	* **Juan David Castro (Platzi)** (1)

		
		Aquí puedes encontrar toda la información sobre las cuentas gratuitas de Azure:
		
		  * <https://azure.microsoft.com/es-es/free/>
		  * <https://azure.microsoft.com/es-es/free/free-account-faq/>
		
		

* **Chalalo** (2)

	
	Muy bien explicado 😃

* **Luis Garcia** (2)

	
	Excelente video

* **Christian David Sánchez** (2)

	
	La teoría siempre es importante y vital para comprender lo practico 😉

* **carlosbazanhuaman** (2)
si se elige una maquina con linux, tambien podra venir con sql server?

* **rmgelvez** (1)

	
	Buen video

## 0070. Cálculo de costos de Máquinas Virtuales

### Descripción:


### Links:

* [Microsoft Azure Cloud Computing Platform & Services](https://azure.microsoft.com)

### Comentarios:

* **Saul Burgos Davila** (3)
A que se refiere con transacciones en la vm?

	* **Oscar Castillo** (5)

		
		Se refiere al número de solicitudes al servicio de almacenamiento, siendo estas del tipo subir un archivo e incluso borrarlos.  
		Cada transacción se asocia a bloques de acceso (al disco), donde el tamaño mínimo del bloque es, 4MB.
		
		Por ejemplo: Si queremos subir un archivo de 16 MB, eso implica 4 transacciones de almacenamiento.

* **Luis Garcia** (2)

	
	excelente video gracias

* **Christian David Sánchez** (2)

	
	Muy buenos todas las sugerencias brindadas por el instructor.

* **carlosbazanhuaman** (1)
se puede programar automaticamente las horas de trabajo diarias como si fuera un calendario?

## 0080. Crear una Máquina Virtual desde el portal

### Descripción:


### Comentarios:

* **carlosbazanhuaman** (2)

	
	muy sencilla la creacion de una vm, pero el precio por hora que sale ahi deberiamos tomarlo en cuenta.

* **gggabriel** (2)

	
	Puedes explicar un poco más qué es un “Resource Group”? Podemos usar uno solo para vairas VMs? Cuál serían las ventajas y desventajas de esto? Gracias

	* **Oscar Castillo** (3)

		
		Efectivamente puedes usar un solo Resource Group para varias VMs, de hecho no solo VMs, sino también demás componentes de tu solución.  
		En sí, el resource group es la “carpeta” que contiene todos los recursos asociados a tu solución.

	* **Juan Arturo Gutiérrez** (1)

		
		Se recomienda tener un solo grupo de recursos para todos los componentes de una solución. De modo que te sirve para diferenciar mejor los costos de cada una de tus soluciones en la pantalla de Billing.

* **gggabriel** (2)
Hola. Puedes explicar un poco más qué es un “Resource Group”? Podemos usar uno solo para vairas VMs? Cuál serían las ventajas y desventaj...

	* **Juan Manuel Quiñones Marí** (1)

		
		Hola, mira un grupo de recursos o resource group es simplemente donde se almacenan todos los recursos que usas en una infraestructura en azure.
		
		Dentro del resource group puede colocar varias maquinas y varios servicios, hay ciertos servicios que al activarse crean su propio grupo de recursos, como es el ExpressRoute.
		
		Los grupos de recurso van muy bien para ordenar los servicios que tienes y asi, si tienes varios entornos como uno de produccion y uno de testing, con los resource group puedes organizar los recursos que tienes en cada uno de los entornos y evitar confusiones.

* **Juan Castilla** (1)

	
	Cuando dices RAM, en realidad te estas refiriendo al storage: 4gb. La VM que configuraste es de solo 0.5gb de RAM.

	* **Juan Arturo Gutiérrez** (1)

		
		Si, creo que se equivoco en la explicación son 0.5Gb de RAM y 4Gb de almacenamiento temporal.

* **Christian David Sánchez** (1)

	
	Vamos avanzando!

## 0090. Instalación de Azure CLI en Ubuntu Bash

### Descripción:


Antes de crear, configurar o acceder a nuestras máquinas virtuales desde la terminal debemos instalar las herramientas de desarrollo de Azure.
``` 
    # Instalación
    curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
    # Login
    az login
    
```

Recuerda que puedes aprender cómo funcionan la terminal y sus comandos más importantes con los siguientes cursos:

  * [Introducción a la Terminal y Línea de Comandos](https://platzi.com/terminal)
  * [Administración de Servidores Linux](https://platzi.com/linux)



### Links:

* [Curso de Administración de Servidores Linux](https://platzi.com/linux)

* [Install the Azure CLI on Linux with apt | Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest)

* [Introducción a Terminal y Línea de Comandos](https://platzi.com/terminal)

### Comentarios:

* **Juan Manuel Quiñones Marí** (1)

	
	Si quieren utilizar la terminal de ubuntu en windows para usar el CLI pueden seguir los pasos de esta web:
	
	<https://zimmergren.net/azure-tip-azurecli-ubuntu-windows-10-bash/>

* **carlosbazanhuaman** (1)

	
	me puedo conectar desde windows por CLI?

* **Juliocastaneda** (1)

	
	Buenas tardes, para trabajar con la CLI de Azure me pide crear un almacenamiento necesariamente? y menciona que tiene un costo? UQe hago?

## 0100. Crear una Máquina Virtual desde CLI

### Descripción:


Recuerda que usar el mismo grupo de recursos es indispensable para conectar nuestras máquinas virtuales a un balanceador de cargas. Si por error creaste dos grupos diferentes, lo mejor es que elimines la nueva máquina virtual y vuelvas a intentarlo.

Para ver todas las opciones de sistemas operativos disponibles usamos el comando **`az vm image list`**.

Para crear y configurar nuestra máquina virtual ejecutamos el siguiente comando:
``` 
    az vm create -n NombreMV -g GrupoRecursos --image ImagenUrnAlias --authentication-type password --admin-username NombreUsuario --location Zona
    
```

No olvides usar contraseñas diferentes para cada una de tus máquinas virtuales.

### Comentarios:

* **Luis Garcia** (4)

	
	excelente video, pero me gustaría mas que fuera también para powershell. la explicacion

* **Oscar Castillo** (3)

	
	"Es una brecha de seguridad enorme usar el mismo password para todas tus máquinas virtuales"  
	Yo en la particular me apoyo en [LastPass](https://www.lastpass.com/es), como gestor de contraseñas.

	* **Jorge Mayorga** (1)
La verdad tampoco es recomendable un bloc de notas en texto plano

	* **Jorge Mayorga** (1)
También está keeppass

* **Christian Hugo López Bazán** (1)

	
	Interesante!..Sería genial una explicación usando PowerShell desde local. En este link [PowerShell Azure - Azure Cloud Shell](https://docs.microsoft.com/es-es/powershell/azure/azureps-vm-tutorial?tutorial-step=1&view=azps-3.4.0)  
	Se usa Azure Cloud Shell desde el explorador con la cuenta azure ya creada

## 0110. Software adicional en Máquinas Virtuales

### Descripción:


Para conectarnos por SSH a nuestra máquina virtual debemos ejecutar el comando **`ssh NombreUsuario@NumeroIPMáquinaVirtual`**.

Una vez conectados podemos actualizar el sistema operativo con **`sudo apt-get update`**.

También vamos a instalar Apache, el servidor web que utilizaremos para nuestra aplicación: **`sudo apt-get install apache2`**. Puedes revisar que Apache funcione correctamente con **`sudo systemctl status apache2`**.

### Links:

* [Curso de Administración de Servidores Linux](https://platzi.com/linux)

* [Introducción a Terminal y Línea de Comandos](https://platzi.com/terminal)

* [
  Arranque, detención y recarga de servicios en Curso de Administración de Servidores Linux
](https://platzi.com/clases/1667-linux/22842-arranque-detencion-y-recarga-de-servicios/)

### Comentarios:

## 0120. Reglas de Seguridad en Red para acceder a mi Servidor Web

### Descripción:


Recuerda que el archivo **`/var/www/html/index.html`** contiene el HTML que ven nuestros usuarios al entrar a nuestra página web, a la que por ahora solo podemos acceder usando la IP pública que nos asignó Azure, así que si editamos este archivo HTML va a cambiar el contenido que muestra la página web.

### Comentarios:

* **rmgelvez** (1)

	
	En la seccion de soporte y solucion de problemas hay una opcion que dice “Consola de serie” ahi pueden escribir sus comandos

* **carlosbazanhuaman** (1)

	
	se puede usar el comando ssh desde power shell en Windows?

* **Jair Sebastian Lozano Moron** (1)
Tengo un problema, con la maquina virtual creada desde la línea de comandos no hubo problema, pero ya reinstalé dos veces la maquina virt...

	* **etostado** (1)

		
		Hola, para reparar esa situacion tienes que ir a Netwoking y agregar una nueva regla ve a :  
		add inbound port rule  
		basic  
		Service : SSH  
		port :22  
		Priority:1000  
		Name : default-allow-ssh (puedes usar el nombre que sea, yo use el mismo que estaba en Ubuntu02)
		
		click add
		
		y trata de nuevo.
		
		Suerte

## 0130. Scripts de Automatización para Máquinas Virtuales

### Descripción:


Por ahora, administrar y configurar nuestras máquinas virtuales no es un trabajo muy costoso. Pero mientras más crece nuestra aplicación, más útil será que podamos realizar los procesos de creación y actualización de nuestras máquinas de forma automática.

Para esto vamos a crear un archivo **`script.json`** con algunas propiedades. Una de estas es **`protectedSettings > commandToExecute`** , donde podemos configurar los comandos que debe ejecutar nuestra máquina virtual justo después de ser creada.
``` 
    az vm extension set --resource-group GrupoRecursos --vm-name NombreVM --name Nombre --publisher Microsoft.Azure.Extensions --settings ruta-del-archivo/script.json
    
```

### Links:

* [Run custom scripts on Linux VMs in Azure | Microsoft Docs](https://docs.microsoft.com/en-us/azure/virtual-machines/extensions/custom-script-linux)

* [ContenidoIaaS/Automatizacion at master · aminespinoza/ContenidoIaaS · GitHub](https://github.com/aminespinoza/ContenidoIaaS/tree/master/Automatizacion)

### Comentarios:

* **Esteban parra** (3)

	
	Para el tema de Windows se puede ejecutar comandos bash y powershell de manera automatizada y masiva??? o solo es para ambientes LINUX?

	* **Luis Garcia** (1)

		
		al parecer nada mas es pa bash por que yo uso powershell y no son los mismos.
		
		saludos

	* **Juan David Castro (Platzi)** (1)

		
		Puedes usar el **Windows Subsystem for Linux** (WSL): <https://platzi.com/clases/prework/>.

* **rmgelvez** (1)

	
	Excelente explicación, tarde un poco en hacer correr el script porque tuve un pequeño error que puede que le pase a otros.  
	Si tienen varias suscripciones como yo que tengo dos (La de prueba de azure y la de estudiantes) puede que el grupo de recursos se cree en una suscripcion y al momento de correr el comando coja por defecto la otra suscripcion, de esta manera es como si no encontrara el grupo de recursos.  
	az account list --output table (Comando para ver las suscripciones y cual tienes por defecto)  
	az account set --subscription “NombreSuscripcion” (Comando para setear la suscripcion del grupo de recursos que necesitas por defecto)

* **carlosbazanhuaman** (1)

	
	estos script podrian llamarse codigo para desplegar infraestructura

* **Luis Garcia** (1)

	
	excelente explicación.

## 0140. Mejores prácticas en Máquinas Virtuales

### Descripción:


### Links:

* [Curso de Programación en Bash Shell](https://platzi.com/clases/bash-shell/)

* [Curso de Administración de Servidores Linux](https://platzi.com/clases/linux/)

### Comentarios:

* **Jose Antonio Sarria Garcia** (2)

	
	Buen vídeo

## 0150. Redimensionamiento de Máquinas Virtuales

### Descripción:


### Links:

* [Curso de Programación en Bash Shell](https://platzi.com/clases/bash-shell/)

* [Curso de Administración de Servidores Linux](https://platzi.com/clases/linux/)

### Comentarios:

* **Francisco Peña Campos** (3)

	
	Como buena practica.  
	Las maquinas virtuales en Azure se deben detener. Ya que si se apagan desde el sistema operativo te siguen cobrando el computo.

	* **Jorge Mayorga** (1)

		
		En otros servicios cloud se deben destruir. Si yo la tengo apagada conservo mis datos pero no me cobran?

* **Fernando Ramos Saturno** (1)

	
	Como puedo redimensionar solo el disco de una maquina virtual, sin agregar otro disco, solo cambiar el tamaño del primero que se creo
	
	url imagen -> <https://ibb.co/17Gb3Dc>

* **Fernando Ramos Saturno** (1)
Como puedo re dimensionar el disco de la maquina virtual , sin agregar otro, solo re dimensionar el primero que se creo

# Redes y comunicaciones

## 0160. Introducción al Balance de Cargas de Azure

### Descripción:


Los **Balanceadores de Cargas** nos ayudan a dirigir las peticiones de los usuarios a diferentes máquinas virtuales para evitar que nuestras aplicaciones tengan un “cuello de botella” o empeoren su rendimiento.

Debemos hacerlo de la forma que más le convenga a nuestra aplicación: cuando una máquina esté muy llena podemos repartir el tráfico con otra máquina, 50% a cada máquina desde el principio, entre otras.

### Comentarios:

* **enando502** (1)
¿Que diferencia hay si en lugar de habilitar dos servidores con un balanceador de cargas. le subo mas recursos a un solo servidor virtual?

	* **dalaiaguirrejimenez** (1)

		
		. para saber la respuesta. excelente pregunta

## 0170. Crear un balanceador de cargas desde el portal

### Descripción:


### Links:

* [ContenidoIaaS/AltaDisponibilidad at master · aminespinoza/ContenidoIaaS · GitHub](https://github.com/aminespinoza/ContenidoIaaS/tree/master/AltaDisponibilidad)

### Comentarios:

## 0180. ¿Qué son las Redes Virtuales

### Descripción:


Muy bien, tomemos la definición básica de lo que significa una red virtual. Si buscas, en prácticamente cualquier sitio te dirán que se trata de una combinación entre elementos físicos y de software para poder establecer una comunicación entre los nodos deseados. O algo así. La teoría es demasiado complicada al menos para entenderla así de rápido, veamos los detalles.

Básicamente cualquier dispositivo con WiFi ahora se conecta a una red, eso es algo que todos sabemos, lo que pocos vemos, es que a nivel profesional las redes virtuales son lo que permite a una compañía tener oficinas en diferentes ciudades y poder compartir sus recursos sin problema. Es inconcebible que una compañía de mediano o gran nivel no cuente con una red virtual para poder blindar el acceso con seguridad de sus archivos.

En cuanto a Azure, cada máquina virtual, al ser creada necesita tener una conexión a una red virtual, ya sea que se la quieras asignar o no.  
![azure 3.png](https://static.platzi.com/media/user_upload/azure%203-56367c25-a6e3-47ca-8144-f94b34cb3f47.jpg)

Veamos que compone a la conexión de esta máquina.  
VNet (Virtual Network)  
Interface de red  
Subnet  
Dirección IP Privada  
![AZURE 4.png](https://static.platzi.com/media/user_upload/AZURE%204-f4322c2b-6f1b-4263-ab88-0cf3f5035fa9.jpg)

También, podrías crear una red virtual al principio y luego comenzar a agregar nodos (máquinas virtuales), esto lo puedes hacer para lograr una mejor coherencia en la estructura. En estos escenarios, la comunicación de la red es mucho más delicada que las mismas máquinas virtuales. Si te equivocas al crear una máquina virtual solo puedes eliminarla y reiniciar el proceso. Si creas una red virtual con algún detalle por corregir no solo deberás volver a crearla sino también a todas las máquinas que estén dentro de ella. Delicado ¿no?

Considera que la NET que vas a crear en el ejercicio del balanceador de cargas será un paso importante pues se trata de la columna que sostendrá toda la infraestructura por hacer.

### Comentarios:

* **Luis Garcia** (2)

	
	excelente gracias

* **Francisco Peña Campos** (2)

	
	Es importante saber que una VM en Azure siempre tendrá una IP privada, no hay VMs que sean únicamente públicas, lo mismo pasa con IPv6.

* **etostado** (1)

	
	Es un reto de enfoque, bue tip para principiantes

* **Christian Hugo López Bazán** (1)

	
	Simple y claro!

* **Jorge Mayorga** (1)

	
	¿y cómo asigno una nueva red a una VM antigua?

* **carlosbazanhuaman** (1)

	
	muy interesante y delicado!

## 0190. Estableciendo un plan para contar con alta disponibilidad

### Descripción:


Paso 1: Crear un grupo de recursos.
``` 
    az group --name platziBalancer --location eastus 
    
```

Paso 2: Crear una IP Pública.
``` 
    az network public-ip create -g platziBalancer --name myPublicIP
    
```

### Links:

* [ContenidoIaaS/AltaDisponibilidad at master · aminespinoza/ContenidoIaaS · GitHub](https://github.com/aminespinoza/ContenidoIaaS/tree/master/AltaDisponibilidad)

### Comentarios:

* **langeld83** (3)

	
	En el paso 1 faltó agregar create :  
	****az group create --name platziBalancer --location eastus****

* **Carlos Alex Becerra Chavita** (2)

	
	Excelente saber el paso a paso

* **Jose Maldonado** (1)

	
	No siente como que el curso salto una parte?  
	En el video anterior quedamos en la creación del balancer y en este video esperaba asignar las VM a ese balancer.

## 0200. Crear un balanceador de cargas desde la línea de comandos

### Descripción:


Paso 3: Crear un balanceador de cargas.
``` 
    az network lb create -g platziBalancer -n myLoadBalancer --frontend-ip-name myFrontEndPool --backend-pool-name myBackEndPool --public-ip-address myPublicIP
    
```

Paso 4: Configurar un seguimiento de desempeño del balanceador de cargas. Agregamos una regla de seguridad para monitorear todo el comportamiento de nuestro balanceador.
``` 
    az network lb probe create -g platziBalancer --lb-name myLoadBalancer --name myHealthProbe --protocol tcp --port 80
    
```

Paso 5: Establecer una regla de red en el balanceador de cargas.
``` 
    az network lb rule create -g platziBalancer --lb-name myLoadBalancer -n myLoadBalancerRule --protocol tcp --frontend-port 80 --backend-port 80 --frontend-ip-name myFrontEndPool --backend-pool myBackEndPool --probe-name myHealthProbe
    
```

### Links:

* [ContenidoIaaS/AltaDisponibilidad at master · aminespinoza/ContenidoIaaS · GitHub](https://github.com/aminespinoza/ContenidoIaaS/tree/master/AltaDisponibilidad)

### Comentarios:

* **saidmlx** (5)

	
	Les dejo un link donde se explica que es el Load Balancer
	
	<https://docs.microsoft.com/es-es/azure/load-balancer/load-balancer-overview>

* **langeld83** (3)

	
	También pueden completar todos los comandos con Tab, a final de cuentas sigue siendo un Bash.
	
	Saludos

* **Jose Maldonado** (1)

	
	“Debi haber creado el grupo de recursos para la ip publica, ip publica > para el balanceo de carga, el Balanceo de > reglas de red.”
	
	Muy bien, sin embargo sigo avanzando en los videos y no logro ubicarme, creamos el grupo,> creamos y configuramos las vm > creamos el balanceo de carga. Y de repente saltamos a la clase de script.
	
	Como asigno las vm con la configuración de apache, al balanceador de carga que creamos ?

* **Maria del Pilar Martinez** (1)

	
	Todo muy lindo pero tendria que haber alguna ayuda de Platzi en cuanto a crear una cuenta gratuita en Azure y poder practicar todos estos temas, porque viendolos solamente es muy acotado y no lo entiendo asi

	* **Jorge Mayorga** (1)

		
		Se puede crear con un credito de $200 gratis con tarjeta de credito. Si eres estudiante no te pide tarjeta.

## 0210. Crear una red virtual

### Descripción:


Paso 6: Crear una red virtual.
``` 
    az network vnet create -g PlatziBalancer -n myVnet --subnet-name mySubnet
    
```

Paso 7: Crear un grupo de seguridad de red (NSG).
``` 
    az network nsg create -g PlatziBalancer -n myNetworkSecurityGroup
    
```

Paso 8: Establecer una regla de entrada en el grupo de seguridad de red.
``` 
    az netfwork nsg rule create -g PlatziBalancer --nsg-name myNetworkSecurityGroup --name myNetworkSecurityGroupRule --priority 1001 --protocol tcp --destination-port-range 80
    
```

### Links:

* [ContenidoIaaS/AltaDisponibilidad at master · aminespinoza/ContenidoIaaS · GitHub](https://github.com/aminespinoza/ContenidoIaaS/tree/master/AltaDisponibilidad)

### Comentarios:

* **carlosbazanhuaman** (2)
todos estos script se pueden correr en un solo archivo script o siempre es uno por uno?

## 0220. Crear un conjunto de disponibilidad

### Descripción:


Paso 9: Crear 3 interfaces de red, una para cada máquina virtual.
``` 
    for i in `seq 1 3`; do
    > az network nic create  -g PlatziBalancer --name myNic$1 --vnet-name myVnet --subnet mySubnet --network-security-group myNetworkSecurityGroup -- lb-name myLoadBalancer --lb-address-pools myBackEndPool
    > done
    
```

Paso 10: Crear un conjunto de disponibilidad.
``` 
    az vm availability-set create -g PlatziBalancer --name myAvailabilitySet
    
```

### Links:

* [ContenidoIaaS/AltaDisponibilidad at master · aminespinoza/ContenidoIaaS · GitHub](https://github.com/aminespinoza/ContenidoIaaS/tree/master/AltaDisponibilidad)

### Comentarios:

* **Oscar Castillo** (7)

	
	Cuidado cuando copien el comando del paso 9, ya que la variable es: myNic$i, no myNic$1

* **carlosbazanhuaman** (1)

	
	el dato sobre la ubicacion que se hereda del grupo de seguridad para todos los recursos creados es interesante e importante.

## 0230. Archivos de configuración inicial para máquinas virtuales

### Descripción:


Paso 11: Crear un archivo de instalación y configuración de arranque para las máquinas virtuales. Este archivo lo puedes encontrar en la sección de recursos de la clase.

Paso 12: Crear 3 máquinas virtuales.
``` 
    for i `seq 1 3`; do
    > az vm create -g PlatziBalancer --name myVM$1 --availability-set myAvailabilitySet --nics myNic$1 --image UbuntuLTS --admin-username azureuser --generate-ssh-key --custom-data cloud-init-txt --no-wait
    > done
    
```

### Links:

* [ContenidoIaaS/AltaDisponibilidad at master · aminespinoza/ContenidoIaaS · GitHub](https://github.com/aminespinoza/ContenidoIaaS/tree/master/AltaDisponibilidad)

### Comentarios:

* **Roger Vilà** (3)

	
	Igual que en el paso 9, en el paso 12, corregid el parametro **–name myVM$ 1** y **–nics myNic$ 1** por **–name myVM$ i** y **–nics myNic$ i** sino no detecta la variable **i**

* **saidmlx** (2)

	
	En este ejemplo pusimos --no-wait pero donde podemos ver el log en caso de error?

	* **Oscar Castillo** (2)

		
		Entiendo que en caso de error, muestra el mensaje de error _(como le sucedió a Amin)_ , caso contrario solo crea la VM… Lo curioso es por qué es diferente para las VMs.

## 0240. Verificación de todo mi entorno de trabajo

### Descripción:


Paso 13: Obtener la IP del balanceador de cargas. Puedes acceder a ella desde el portal de Azure o la línea de comandos.
``` 
    az network public-ip show -g PlatziBalancer --name myPublicIP --query [ipAddress] --output tsv
    
```

Paso 14: Usar la IP del balanceador de cargas para probar que la arquitectura de nuestra aplicación funciona correctamente ( **`Ctrl + R`** ).

### Links:

* [Curso de Programación en Bash Shell](https://platzi.com/clases/bash-shell/)

* [Curso de Administración de Servidores Linux](https://platzi.com/clases/linux/)

* [Desarrollo de Aplicaciones con ASP .NET](https://platzi.com/asp-net/)

* [Fundamentos de C# con NET Core](https://platzi.com/cursos/fundamentos-csharp/)

* [Curso de C# con .Net Core | Platzi](https://platzi.com/cursos/c-sharp/)

* [Curso de ASP.NET Core](https://platzi.com/cursos/aspnet-core/)

* [Curso de SQL en Azure](https://platzi.com/cursos/sql-azure/)

* [Curso de Almacenamiento en Azure](https://platzi.com/cursos/almacenamiento-azure/)

* [Curso de Web Apps y Logic Apps en Azure](https://platzi.com/cursos/web-apps/)

* [ContenidoIaaS/AltaDisponibilidad at master · aminespinoza/ContenidoIaaS · GitHub](https://github.com/aminespinoza/ContenidoIaaS/tree/master/AltaDisponibilidad)

### Comentarios:

* **Carlos Alex Becerra Chavita** (2)

	
	Huy muy completo el curso

* **oscarald** (1)

	
	Muy buen curso.

* **claudiomorales** (1)

	
	Buen curso

* **carlosbazanhuaman** (1)

	
	sin mucha configuracion a nivel de recursos se pudo desplegar un sitio web con alta disponibilidad, me parecio increible. buen curso. Saludos.

* **Antonio Xolocotzi Villalva** (1)
¿Alguien sabe como cambiar la configuración de la maquina virtual para que este en español? En particular quiero hacer que el formato de ...

* **langeld83** (1)
Alguien tuvo problemas para crear las 3 VM con el comando seq ?, yo la ejecute y sólo me creo una sola VM

	* **Larry Saldaña** (1)

		
		Puede que te hayas confundido en escribir algún parametro en la sentencia. De todas maneras como solo son 3 mv puedes ejecutar una sentencia por cada mv, ya luego puedes ver el tema del for en bash.
		``` 
		    az network nic create  -g PlatziBalancer --name myNic1 --vnet-name myVnet --subnet mySubnet --network-security-group myNetworkSecurityGroup --lb-name myLoadBalancer --lb-address-pools myBackEndPool
		    
		    az network nic create  -g PlatziBalancer --name myNic2 --vnet-name myVnet --subnet mySubnet --network-security-group myNetworkSecurityGroup --lb-name myLoadBalancer --lb-address-pools myBackEndPool
		    
		    az network nic create  -g PlatziBalancer --name myNic3 --vnet-name myVnet --subnet mySubnet --network-security-group myNetworkSecurityGroup --lb-name myLoadBalancer --lb-address-pools myBackEndPool
		    
		```

# Despedida

## 0250. Conclusiones ¿Cómo continúa tu ruta de aprendizaje profesional

### Descripción:


**¡Felicitaciones por terminar el Curso de Azure IaaS!**

Recuerda compartir tus notas, dudas y comentarios en la sección de discusiones. Tampoco olvides resolver los ejercicios, completar el examen y darle 5 estrellas al profesor.

Te recomendamos continuar tu ruta de aprendizaje profesional con los siguientes cursos:

  * [Curso de Administración de Servidores Linux](https://platzi.com/linux)
  * [Curso de Programación en Bash Shell](https://platzi.com/clases/bash-shell/)
  * [Curso de SQL en Azure](https://platzi.com/cursos/sql-azure/)
  * [Curso de Almacenamiento en Azure](https://platzi.com/cursos/almacenamiento-azure/)
  * [Curso de Web Apps y Logic Apps en Azure](https://platzi.com/cursos/web-apps/)



¡Nunca pares de Aprender!

### Links:

* [Curso de SQL en Azure](https://platzi.com/cursos/sql-azure/)

* [Curso de Almacenamiento en Azure](https://platzi.com/cursos/almacenamiento-azure/)

* [Curso de Web Apps y Logic Apps en Azure](https://platzi.com/cursos/web-apps/)

* [Curso de Administración de Servidores Linux](https://platzi.com/clases/linux/)

* [Curso de Programación en Bash Shell](https://platzi.com/clases/bash-shell/)

* [Fundamentos de C# con NET Core](https://platzi.com/cursos/fundamentos-csharp/)

* [Curso de C# con .Net Core | Platzi](https://platzi.com/cursos/c-sharp/)

* [Curso de ASP.NET Core](https://platzi.com/cursos/aspnet-core/)

### Comentarios:

* **Jose Maldonado** (1)

	
	en el examen me salio hay 3 preguntas malas, y me gustaría saber por que y repasar con ustedes:
	
	¿cuantas categorias de MV hay en Azure? R/ supogo que habla de las series y desde la A a la N, cuento 12  
	<https://azure.microsoft.com/es-es/pricing/details/virtual-machines/series/>
	
	¿cuanto sistemas Operativos te ofrece el menu de creacion? me parece muy capciosa, windows y linux (2) o de acuerdo a su función (cliente, servidor) o por versiones ( 11).
	
	¿que servidor web instalamos en las maquinas virtuales? apache y hablaron de ngix.
	
	por ultimo y no menos importante la mayoría de las preguntas eran de comando especifico. lo cual no esta mal. pero también esta la parte gráfica, yo particularmente puede hacer el curso orientándome por la parte gráfica ya que siento que se saltaron o simplemente para mi no quedo claro., esta super bueno el curso… pero deberían de revisar las secuencias de los vídeos.

* **Fernando Eladio Alvarez Noya** (1)

	
	Hola, no me deja presentar el examen, cada vez que lo selecciono se vuelve a cargar automaticamente, he revisado y si tengo el visto de todas las clases!  
	Gracias!

	* **Fernando Eladio Alvarez Noya** (1)

		
		Ya pude tomar el examen. Gracias!

