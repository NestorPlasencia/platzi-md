# Introducción a NPM

## 0010. Acerca de NPM, paquetes y módulos

### Descripción:


### Links:

* [npm | build amazing things](https://www.npmjs.com/)

* [npm | build amazing things](https://www.npmjs.com/)

* [GitHub - platzi/curso-npm: Repositorio del curso de NPM](https://github.com/platzi/curso-npm)

### Comentarios:

* **Jose Luis Colmenares** (5)

	
	NPM siempre ha sido un de las partes más dolorosas y que mas me hace perder tiempo las veces que he querido empezar con un boilerplate. Gracias por este curso, me hubiera gustado tenerlo antes jaja

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		A poner en practica todo el aprendizaje 😄

* **Mariana Valencia** (3)

	
	Este curso lo necesitaba con urgencia

* **José Tuzinkievicz** (3)

	
	Esperé mucho este curso, es uno de los tantos painkillers que tiene Platzi.

	* **Oscar Barajas Tavares (Platzi)** (3)

		
		La finalidad es de que puedan entender a detalle como funciona una de la principales herramientas de un desarrollador JavaScript.

* **Camilo Alexander Velandia Velandia** (2)

	
	genial, porfin a profunizar en npm

* **33andres33** (1)

	
	voy a tomar este curso porque siempre tengo algun error con los paquetes de la terminal, espero aca resolver todas mis dudas

* **jdiegochg10** (1)

	
	vengo de la escuela de JavaScript, vamos aprender NPM

* **Juan Esteban Galvis** (1)

	
	Ya aprendí terminal y estaba aprendiendo React cuando me surgió la curiosidad de hacer este curso, me parece interesante.

* **Karla Agraz** (1)

	
	¿Qué es NPM (node package manager) ? Es un gestor de paquetes, el más popular que tiene JavaScript, donde encontrarás una gran cantidad de recursos para poder implementar en tus proyectos. También vas a poder crear tus propios paquetes y compartirlos con toda la comunidad.

* **Christian Erik Velázquez Morales** (1)

	
	Antes de seguir con los demás cursos, quiero profundizar sobre npm. Gracias por el curso.

* **louismanson** (1)

	
	Deberían incluir también Yarn

* **yisus_dev** (1)

	
	por fin voy a aprender que rayos con ^ y otros…

* **José Pablo Machuca González** (1)

	
	Esperando este curso por semanas pero de cierto, de cierto os digo que merecerá la pena tanto como toda la carrera de la Escuela de JavaScript.

	* **Oscar Barajas Tavares (Platzi)** (1)

		
		Este curso es parte de Escuela de JavaScript.

* **Danilo Morales** (1)

	
	Cool Oscar, vamos a adelante!

	* **Oscar Barajas Tavares (Platzi)** (1)

		
		SIn dudarlo

# Instalación

## 0020. Windows

### Descripción:


### Links:

* [Node.js](https://nodejs.org/es/)

### Comentarios:

* **Danilo Morales** (5)

	
	npm node package manager

* **Facundo Nicolás García Martoni (Platzi)** (5)

	
	Si están trabajando en Windows es muy recomendable probar [Cmder](https://cmder.net/), un emulador de la consola de los sistemas *nix, con el que van a poder ejecutar más fácilmente los comandos que se vean a lo largo del curso 😉

* **Daniel Hurtado** (3)

	
	Para todos los que programa en Windows 10, hacer uso de WSL es muy útil para casi todo tipo de desarrollo, como su nombre lo dice: Windows Subsystem for Linux, es un subsistema linux integrado que permite tener una consola bash con todas las funcionalidades de una distro como debia, ubuntu, entre otras. Su instalación es sencilla y no es mi propósito explicarla, sin embargo puedo decirte que haciendo uso de ella tendrás todas las bondades de Windows así como también todas las bondades de tener una terminal bash completa y todas las funcionalidades de sus paquetes con la que podrás trabajar dentro del mismo subsistema así como también fuera de él en tus documentos/proyectos de Windows. Si no lo haz probado aún, dale una oportunidad y te sentirás todo un hackerman al tener windows con bash 😃

	* **Gabriel De Andrade (Platzi)** (1)

		
		Si, tener WSL en Windows es increíble, en el [Curso de Prework](https://platzi.com/clases/prework/) de hecho creamos un ambiente de desarrollo que complementa todo este ecosistema muy bien

	* **David Flores** (1)

		
		Te recomiendo este increíble post sobre [cómo Instalar WSL en Windows 10](https://platzi.com/blog/como-instalar-zsh-en-windows/)

	* **pabloverduzcos** (1)

		
		Totalmente de acuerdo. Estoy utilizando WSL con la terminal de Ubuntu 18.04 y las versiones de Node.js las controlo con [nvm](https://github.com/nvm-sh/nvm) 😁

	* **ZusMexSide** (2)

		
		el unico problema que aun encuentro es que no hay mucha info para manejar el path de windows con el de wsl, la info es muy confusa y escasa

* **Andres Roberto Coello Goyes** (2)

	
	Si no estas en windows la instalacion es por consola.
	``` 
	    curl -sL https://deb.nodesource.com/setup_10.x -o nodesource_setup.sh
	    
	    sudo bash nodesource_setup.sh
	    
	    sudo apt install nodejs
	    
	```

* **zequihinojosa** (1)

	
	toca la 13.12…

* **jdiegochg10** (1)

	
	Interesante.

* **matias-alexander-ibarra-trujil** (1)

	
	voy en la 13.8

* **Diego Fernando Rojas Quintero** (1)
como actualizo node y npm en wls?

	* **Juan David Castro (Platzi)** (1)

		
		De igual forma que si estuvieras en Linux nativo. Puedes usar NVM. O con el comando **`npm install -g npm@latest`**. O como prefieras.

* **Diego Fernando Rojas Quintero** (1)
si yo instale node en wsl, ¿que version se instala; LTS ó Current?

	* **Juan David Castro (Platzi)** (1)

		
		La que quieras. Si quieres lo último y más nuevo (mi caso), current. Si no, si quieres la versión estable, probada y sin errores, LTS. También LTS si trabajas un proyecto para producción.

* **ZusMexSide** (1)
he hecho otros cursos en platzi, puedo ocupar la version 12 que tenia?

	* **Miguel Segura** (1)

		
		Realmente no hay ningún problema con la versión que uses.
		
		Si quieres manejar múltiples versiones de node en tu computador facilmente, usa:  
		<https://github.com/coreybutler/nvm-windows> o <https://github.com/nvm-sh/nvm>

* **jairpss** (1)
Tengo Node instalado bien pero NPMya lo tenia instalado pero quise ver la version y me sale este error… Alguien que sepa como resolver es...

	* **Gabriel De Andrade (Platzi)** (1)

		
		😮 intenta corriendo `npm cache clean`

* **carlosvaldivia** (1)
Que relación tienen los archivos : package.json, package-lock.json y yarn.lock. Para resolver errores de dependencias leí que tenía qu...

	* **Manuel Ojeda** (2)

		
		Package.json es donde vamos a definir la información y las dependencias del proyecto.
		
		La diferencia entre **package-lock** y **yarn.lock** es que **package-lock** es utilizado por NPM, mientras que **yarn-lock** es por utilizado por [Yarn](https://yarnpkg.com/lang/en/).
		
		Yarn es un instalador dependencias de JavaScript alternativo a NPM.
		
		La clave es que se sugiere que un proyecto solo utilice ya sea NPM o Yarn, no ambos, ya que puede generar un conflicto por la manera en el que funciona cada uno al ser diferente.

* **carlosvaldivia** (1)
Como instalar en ubuntu 16 , una version especifica de node y una version especifica de npm…solo para un proyecto, no en forma global?

	* **Oscar Barajas Tavares (Platzi)** (1)

		
		Lo puedes hacer con NVM. Aca te dejo la documentación. <https://github.com/nvm-sh/nvm>

* **carlosvaldivia** (1)
como podría instalar version 4.x de node?

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Puedes utilizar NVM para manejar las versiones: <https://github.com/nvm-sh/nvm>

* **Baldan** (1)
¿Cómo desinstalo npm?

	* **Juan David Castro (Platzi)** (1)

		
		En esta guía te explican: <https://docs.npmjs.com/misc/removing-npm.html>. 😉

## 0030. Mac

### Descripción:


### Links:

* [Node.js](https://nodejs.org/es/)

### Comentarios:

* **luisglopez7777** (5)

	
	nadie leyo la licencia

* **Manuel Rivera** (4)

	
	En linux:  
	1.Ultima versión LTS : sudo apt-get install nodejs npm  
	2\. Instalar NVM: curl -o- <https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh> | bash
	
	  * nvm ls-remote para ver la lista de versiones que hay de node
	  * Luego escogen la versión que deseen instalar  
	Example: para instalar Nodejs v9.3.0, ejecuta:  
	-nvm install v9.3.0
	
	

* **Ernesto Vizcaíno Alvarado** (3)

	
	**Para instalar en Mac**
	
	  1. Debes de ir a [nodejs.org](nodejs.org).
	
	  2. Descargar la última versión de Node.
	
	
	
	
	**Para comprobar que está instalado**
	
	  1. Abre la terminal y escribe
	
	
	``` 
	    npm -v
	    
	```
	
	Esto nos da la versión que tenemos.
	
	**Para instalar la última versión**
	``` 
	    sudo npm install npm@latest -g```
	    
	```

* **jdiegochg10** (1)

	
	MAC OS

* **Fernando Torres** (1)

	
	Si ya está instalado, puedes verificar si hay una actualización más reciente con
	``` 
	    sudo npm install -g npm@latest
	    
	```

# Configuración

## 0040. Iniciar un proyecto

### Descripción:


### Links:

* [Licencia de software - Wikipedia, la enciclopedia libre](https://es.wikipedia.org/wiki/Licencia_de_software)

### Comentarios:

* **Jorge Daniel Pat Navarro** (9)

	
	**npm init** Nos sirve para crear el archivo package.json el cual contiene toda la información acerca de nuestro proyecto, entre los datos que contiene son:
	
	  * package name, que es el nombre de tu proyecto.
	  * version, la versión en la que esta tu proyecto.
	  * description, sobre que trata nuestro proyecto.
	  * entry point, el punto de entrada de nuestro proyecto.
	  * test command u otros comandos de utilidad para nuestro proyecto.
	  * gti repository, el repositorio donde esta almacenado tu proyecto, podria ser github, gitlab, entre otros.
	  * keywords, son palabras que describen a nuestro proyecto
	  * author, quien esta desarrollando el proyecto aquí va nombre <email>
	
	
	
	[Un ejemplo que encontre por ahi](https://github.com/jonschlinkert/even/blob/master/package.json)

* **buzu** (7)

	
	Recomiendo mucho leer la documentación de package.json en el sitio de npm: <https://docs.npmjs.com/files/package.json.html>

	* **predator0077** (2)

		
		Muchas Gracias por dejar la información compañero , se agradece demasiado.

	* **Oscar Barajas Tavares (Platzi)** (4)

		
		La documentación oficial siempre es un buen recurso para aprender más, también estar al día con nuevos features que puedan agregar. gracias por tú aporte.

* **Jorge Daniel Pat Navarro** (3)

	
	Empezar cualquier proyecto con git siempre será una buena práctica  
	Si quieres saber más sobre git y github, aquí está el enlace al curso
	
	[Git y GitHub](https://platzi.com/cursos/git-github/)

* **Angel Joaquín Velasco Gómez** (2)

	
	Como hago para tener una consola como la del profe?

	* **Gabriel De Andrade (Platzi)** (1)

		
		Con zsh, lo aprendemos a instalar en el [Curso de Prework](https://platzi.com/clases/prework/). Porfa no hagas preguntas duplicadas 😉

	* **David Flores** (5)

		
		[Este es un tutorial muy bueno](https://www.youtube.com/watch?v=srQyMS6CfxM)

* **Sergio Alejandro Trejo Cuxim** (2)

	
	Aquí una breve introducción de las Licencias de código abierto, para este caso el maestro utilizo MIT, así lo escribes cuando te pida la licencia: MIT
	
	Link:  
	<https://universoabierto.org/2015/12/20/introduccion-a-los-diferentes-tipos-de-licencias-de-codigo-abierto-y-software-libre/>

* **MauricioF** (2)

	
	Las **keywords** permiten que nuestro paquete npm sea ubicado mas fácilmente dentro del sitio de repositorios cuando un usuario este buscando un término relacionado.

* **eddyarellanes** (2)

	
	npm set init.author.email y tal, son funcionalmente como git --config…  
	Tener listos nuestros datos de Dev al momento de hacer Publish/Deploy

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Exacto tienen la misma finalidad 😄 dejar configurado nuestro usuario.

* **AryRosvall** (2)
¿Para qué sirve el archivo package.json en nuestro proyecto?

	* **Luis Arturo Lira Cerda** (1)

		
		Es el archivo donde tendremos información sobre nuestro proyecto y parte de la configuración del mismo.
		
		En este ponemos las dependencias de npm o yarn que usaremos, indicamos sin son sólo para desarrollo o para producción, datos como de la versión, nombre del proyecto, los scripts que usaremos para diferentes como correr el proyecto en desarrollo, hacer la build para producción, testing, el autor, versión, etc.
		
		Se podría decir que es un resumen de lo que trata y de lo que necesita nuestro proyecto para funcionar.

* **jdiegochg10** (1)
![error.PNG.png](https://static.platzi.com/media/user_upload/error.PNG-c7a74752-7db0-4843-ab07-eaf3d18e7e82.jpg)

* **miguelangelsoler** (1)

	
	Ojo al video, pregunta del curso profesional de JS

* **Enrique Alexis Lopez Araujo** (1)

	
	Generar un documento automatico npm init -y

* **jdiegochg10** (1)
porqué´?

* **jdiegochg10** (1)
¿Por qué en el package name le sale (jsnpm) y a mi solo me sale (npm)?

	* **Miguel Segura** (1)

		
		No te preocupes, puedes cambiar el nombre manualmente.  
		Si quieres que luzca igual, asegurate de ejecutar los mismos comandos

## 0050. Instalación de dependencias

### Descripción:


### Links:

* [Curso de Introducción a la Terminal y Línea de comandos](https://platzi.com/clases/terminal/)

### Comentarios:

* **Manuel Ojeda** (8)

	
	Evita tener que hacer sudo cuando hagas un  
	`npm i -g`
	
	Con estos tips del equipo de NPM 👉  
	<https://docs.npmjs.com/resolving-eacces-permissions-errors-when-installing-packages-globally>

	* **Oscar Barajas Tavares (Platzi)** (4)

		
		Esto soluciona muchos problemas a muchos, voy a incorporarlo en una lectura, gracias por tu aporte.

* **Facundo Nicolás García Martoni (Platzi)** (8)

	
	Demonio: Servicio que corre en segundo plano en el sistema

* **Karla Agraz** (3)

	
	  * –save : Este documento que vas a instalar dentro del proyecto es necesario para vivir en producción. Hay que tener cuidado con los paquetes que instalamos, cuando es a producción y cuando no lo es.
	
	  * –save-dev: Este documento que vamos a instalar solo es necesario en nuestro entorno local o en el de desarrollo. Es importante no mandar dependencias a producción ni omitir algunas que deban de estar en producción.
	
	
	

* **Enrique Alexis Lopez Araujo** (3)

	
	Comando para revisar los packages instalados de forma global: npm list -g --depth 0

* **Enrique Alexis Lopez Araujo** (3)

	
	💻 Mi comando preferido para instalar dependencias en DEV:
	``` 
	    npm i -D moment
	    
	```

	* **Iván Darío Sánchez Jiménez** (2)

		
		y si requerimos que se registre la versión exacta en el package.json
		``` 
		    npm i -D -E moment
		    
		```

* **Aaron Gonzalez (Platzi)** (3)

	
	**sudo:** superuser do

* **predator0077** (2)

	
	npm install === npm i
	
	npm i [nombre_del_paquete] --save === npm i [nombre_del_paquete] -S
	
	npm i [nombre_del_paquete] --save-dev === npm i [nombre_del_paquete] -D

* **eddyarellanes** (2)

	
	Mi way preferido de instalar dependencias  
	Dependencias en prod. no especifico el --save  
	`npm install moment`
	
	Para DevDependencies shorcut:  
	`npm install morgan -D`
	
	También se puede usar NPX para no instalar módulos globalmente:  
	`npm install nodemon -D`  
	`npx nodemon`

* **raparisg** (2)
No me quedó claro de que sirve el Flag optional en npm install xxx -O

	* **Juan David Castro (Platzi)** (1)

		
		Esta lectura te puede ayudar: <https://npm.github.io/using-pkgs-docs/package-json/types/optionaldependencies.html>. 😉

* **Victor Hugo Muñoz Hernández** (2)
Hola ¿Qué significa que un paquete se instale de forma opcional? Gracias

	* **Andres Luque** (1)

		
		Hacen referencia a dependencias que no necesariamente impiden el funcionamiento de tu app.

* **Baldan** (2)
¿Qué es nodemon?

	* **Aaron Gonzalez (Platzi)** (4)

		
		Hola @Baldan 😄
		
		Nodemon es un “demonio” que permite que todos los cambios que realices en tu proyecto se muestren en tiempo real. Así, tu flujo de trabajo se vuelve mucho más dinámico.
		
		Te dejo es [artículo](https://www.silversites.es/que-es-nodemon/) donde lo explican a detalle 😄

* **balachvinic** (1)

	
	Listar paquetes instalados de forma global
	``` 
	    npm list -g --depth 0
	    
	```

* **Deymer Hernandez** (1)

	
	Listar paquetes que tengo globalmente => npm list -g --depth 0

* **Deymer Hernandez** (1)

	
	–save => Necesario para producción  
	–save-dev => Solo para nuestro entorno de desarrollo

* **jdiegochg10** (1)

	
	nodemon es una herramienta que ayuda a desarrollar aplicaciones basadas en node.js al reiniciar automáticamente la aplicación de nodo cuando se detectan cambios en el directorio.

* **jdiegochg10** (1)

	```
	    npm list -g --depth 0```
	    
	```

* **Yassr** (1)

	
	Ver los paquetes que estan instalados de forma global
	``` 
	    npm list -g —depth 0
	    
	```

* **Karla Agraz** (1)

	
	  * Carpeta node_modules: Aquí es donde se van a instalar los módulos que tú estás agregando a tu proyecto. Esta carpeta es importante para que tu proyecto funcione, pero no debe de ser enviada a ningún repositorio y debemos ignorarla apenas se crea.  
	Para ignorarla se crea un archivo **.gitignore** y escribimos: node_modules/
	
	
	
	Versión resumida para instalar:
	``` 
	    npm i date-nfs -D
	    
	```

* **Iván Darío Sánchez Jiménez** (1)

	
	Creo que voy a incluir en mis dependencias globales a funny-commit para cuando este poco creativo para los mensajes. Gracias Oscar.

* **Iván Darío Sánchez Jiménez** (1)

	
	Si están en Linux puede que al instalar dependencias globales deban usar `sudo` para hacerlo, algunos directorios requieren permisos especiales de escritura.
	``` 
	    sudo npm i -g nodemon
	    
	```

	* **Gabriel De Andrade (Platzi)** (2)

		
		Algo interesante es que en Linux cuando instalas dependencias globales estas pueden interferir con los paquetes nativos de tu sistema si se instalan con sudo. Lo mas recomendable es crear una carpeta global alternativa para node y no tener que usar sudo, tal como en [este tutorial de NPM](https://docs.npmjs.com/resolving-eacces-permissions-errors-when-installing-packages-globally)

	* **Iván Darío Sánchez Jiménez** (1)

		
		Buen consejo, gracias por el dato, voy a investigar.

* **Christian Erik Velázquez Morales** (1)

	
	Aprendí muchas cosas. Gracias. Resolví muchas dudas.

* **Gtiseira** (1)

	
	Se que esta pregunta debe tener una respuesta muy amplia y particular para cada caso, pero ¿como saber si debo mandar dependencias a producción o no?

	* **Sergio Alejandro Trejo Cuxim** (3)

		
		Sencillo pero confuso.  
		Por ejemplo en utilidades, imagina que creas un módulo que validará tipos de datos de variables, puedes instalar un dependencia en desarrollo solo para que hagas tus pruebas, algo que te facilite, pero que cuando lo publiques en producción como ya está “probado” entonces ya no lo necesitas por que sabrás que tu módulo funciona como debe.

	* **Gtiseira** (1)

		
		Gracias por la respuesta, creo que entender, y digo creo no porque no fueras claro sino que estoy iniciando en el mundo backend por lo que no me resulta todo tan familiar, al menos de comento. Saludos!

* **Enrique Devars (Platzi)** (1)

	
	Si quieren utilizar diferentes versiones de Node y poder instalar paquetes sin necesidad de otorgar permisos pueden usar [nvm](https://github.com/nvm-sh/nvm)

* **José Tuzinkievicz** (1)

	
	En qué carpeta dentro de Ubuntu se guardan las dependencias globales?

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Pueden estar en distintos paths, depende de donde se instale node,
		
		ejemplo:
		``` 
		    /home/USER/.nvm/versions/node/v8.12.0/lib
		    
		```

* **Baldan** (1)
¿para que vale poner sudo?

	* **Aaron Gonzalez (Platzi)** (4)

		
		 **sudo** = _superuser do_
		
		Este comando te permite ejecutar programas con los privilegios del usuario “root”.
		
		Para conocer más a fondo este y otros comandos te recomiendo el curso de [Terminal y Línea de Comandos](https://platzi.com/clases/1748-terminal/24401-permisos-sobre-archivos-el-sistema-de-permisos-oct/)

## 0060. Instalación de dependencias con force

### Descripción:


### Comentarios:

* **buzu** (4)

	
	En esta página <https://docs.npmjs.com/files/package.json.html#dependencies> puedes ver una descripción de lo que significan los simbolos que se usan para especificar las versiones el el apartado de dependencias de package.json.
	
	También es bueno darle una leidita a <https://docs.npmjs.com/files/package.json.html#dependencies> para ver que podemos especificar para el comando install, ya que se puede usar para instalar más que solo paquetes de npm registry.

	* **predator0077** (2)

		
		Justo lo que estaba buscando hace unos días atrás, Muchísimas Gracias.  
		se agradece eso aportes. 😃

* **OmarGbet** (3)

	
	NPM decidió agregar un nuevo comando: npm fund que brindará más visibilidad a los usuarios de npm sobre qué dependencias buscan activamente formas de financiar su trabajo .  
	.  
	Este comando recupera información sobre cómo financiar las dependencias de un proyecto determinado.  
	.  
	Si no se proporciona el nombre del paquete, enumerará todas las dependencias que buscan financiación en una estructura de árbol en la que se enumeran el tipo de financiación y la URL a visitar.  
	.  
	Si se proporciona un nombre de paquete, entonces intenta abrir su url de financiación utilizando el --browser parámetro de configuración.

* **José Tuzinkievicz** (3)

	
	El paquete json-server es fantástico, se pueden hacer peticiones HTTP a un archivo json, yo lo uso con Ngrok y hago peticiones externas.

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Son herramientas que nos permiten ser ágiles a la hora de implementar nuestros desarrollos.

* **José Pablo Machuca González** (2)

	
	¡Excelente!

* **JarlLuis** (1)

	
	Hey gente! Alguien sabe para qué se usan las dependencias opcionales?

	* **Moisés Cedeño** (1)

		
		Las dependencias opcionales son aquellas que no son obligatorias para que tu proyecto funcione, fijate en este ejemplo:
		``` 
		    "dependencies": {
		        "date": "^1.0.2",
		        "moment": "^2.24.0"
		      },
		      "devDependencies": {
		        "date-fns": "^2.11.1"
		      },
		      "optionalDependencies": {
		        "eslint": "^6.8.0"
		      }
		    
		    
		```
		
		Tenemos 1) dependencies que son necesarias y son dependencias que necesitas llevar a producción, 2) devDependencies que son necesarias para desarrollo pero no se necesitan en producción, y 3) optionalDependencies que no son necesarias ni para producción ni para desarrollo, si puedes miralas como una especie de addons.
		
		En el caso de eslint es una dependencias super útil al momento de desarrollar código pero no es obligatoria.

* **jdiegochg10** (1)

	
	Interesante!

* **SebastianMedinaDonoso** (1)

	
	y cual es la diferencia entre npm install y npm install -force?

	* **Manuel Rivera** (1)

		
		Segun lo que entendí, para instalar las ultimas versiones de las dependencias que esten en npm, entonces creo que en algunas ocasiones no se instalan las ultimas versiones con npm install por que no estan 100%, o no sé bro, solo creo que es por eso.

	* **OmarGbet** (1)

		
		Muchos de los paquetes que encuentras en NPM están ligados a otros paquetes y existe por lo tanto una “relación de dependencia” por así decirlo, que pudiera generar conflictos. Entonces, tú al usar npm install-force le estas diciendo a NPM que no importa cual sea la situación con estos paquetes quieres que aún así los instale.

* **Ricardo Martínez Murillo** (1)

	
	Cual es la diferencia de las “devDependencies” y “Dependecies” ?

	* **miguelangelsoler** (1)

		
		Dependencias de desarrollo y dependencias necesarias en produccion.

	* **Iván Darío Sánchez Jiménez** (3)

		
		Cuando haces el build de tu aplicación las devDependencies no se compilan en el bundle. Las dependencias de desarrollo ademas de ser nuestras herramientas de construcción de código, se enfocan en mejorar el Developer Experience mientras que las dependencias de producción se compilan en el bundle y estan enfocadas a la funcionalidad de la aplicación y en mejorar la user experience.

* **elenanajer** (1)

	
	npm install react --dry-run  
	npm install webpack -f  
	npm fund  
	npm install json-server@0.15.0

## 0070. Actualizar y eliminar paquetes

### Descripción:


### Links:

* [
        npm - Visual Studio Marketplace
    ](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)

### Comentarios:

* **mafevito** (27)

	
	Un pequeño resumen:
	
	Actualizar paquetes
	
	  * Revisar que paquetes disponen de nuevas versiones  
	`npm outdate`
	
	  * Para ver un output más detallado  
	`npm outdate --dd`
	
	  * Actualizar los paquetes que no están en la ultima versión  
	`npm update`
	
	  * Actualizar un paquete especifico  
	`npm install json-server@latest`
	
	
	
	
	Eliminar paquetes
	
	  * Eliminar un paquete de node_modules y del archivo package.json  
	`npm uninstall json-server`
	
	  * Desinstalar un paquete de todo node_modules pero no del archivo package.json  
	`npm uninstall webpack --no-save`
	
	
	

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Excelente resumen 😄

	* **Christian Erik Velázquez Morales** (1)

		
		Gracias!

	* **Efrén Martínez Rodríguez** (1)

		
		Corrección este comando instala la última versión de la dependencia.
		``` 
		    $ npm installjson-server@latest
		    
		```

	* **Emmanuel Rodríguez Ramírez** (1)

		
		Meteré de mi cuchara. 🙃  
		Como tal el comando `uninstall --no-save` no tiene un impacto, ni de node_modules ni del package.json. Su limitada documentación:  
		`--no-save: Package will not be removed from your package.json file` diciendo que `npm uninstall takes 3 exclusive ... -S, -D, -O` son sus únicos elementos en impacto local y el global con `-g`, obviamente.  
		Sin embargo, al aplicar el comando genera un output similar a `audited 449 packages in 1.421s` donde se menciona, en comando o no, que **_audit_** envía una descripción de las dependencias configuradas en tu proyecto y pide por un reporte de las vulnerabilidades donde, acto seguido en el mismo output, se muestra `found 0 vulnerabilities`, donde podemos “decir” que hace _un recuento del impacto, pero sin hacer el movimiento_.  
		Ahora bien, el comando `update --no-save` menciona su uso como `To get the old behavior` donde se puede confundir con `update` donde `save the new version as the minimum required dependency` o la más estable.

* **buzu** (4)

	
	Cuando trabajas en un equipo, puede ser que alguien corra `npm unistall package` para eliminar un paquete y luego ese cambio se envíe al repositorio remoto donde tú puedes hacer pull. Dado que el directorio de modulos de node no se alacena en git, tú seguirás teniendo paquetes que ya no se usan. En esoso casos puedes usar `prune`<https://docs.npmjs.com/cli/prune.html>
	
	`prune` va a eliminar los paquetes que ya no se usan en tu proyecto, pero también puede eliminar paquetes en especifico, o eliminar los paquetes de dev en entornos de producción.

* **pabloverduzcos** (2)

	
	También existe este comando que sirve para seleccionar que dependencia actualizar de manera especifica:  
	.
	``` 
	    npx npm-check--update
	    
	```
	
	.  
	Fuente: [Tomek Sułkowski en Twitter](https://twitter.com/sulco/status/1180096744870350848?s=20)

* **Victor Hugo Muñoz Hernández** (2)
Hola Cuando usamos npm install json-server@latest, por ejemplo. ¿Se elimina la versión anterior que tengamos instalada? Gracias

	* **Anthony Mosquera** (1)

		
		Correcto, dentro de la carpeta node-modules puedes buscar el paquete y ver que reemplazo la versión anterior por la nueva

* **Jose Luis Campos Bautista** (1)

	
	Desinstalar paquetes sin que se remuevan del del package.json  
	.
	``` 
	    npm uninstallpackage-name--no-save
	    
	    
	```

* **Jose Luis Campos Bautista** (1)

	
	Para desinstalar paquetes  
	.
	``` 
	    npm uninstallpackage-name
	    
	    
	```

* **jdiegochg10** (1)
npm uninstall webpack --no-save un caso de ejemplo donde usaria esto?

	* **Miguel Segura** (1)

		
		En este caso están jugando con paquetes random de ejemplo.
		
		Un ejemplo de uso del unistall podria ser si decides dejar de utilizar D3.js en tu proyecto y empezar a utilizar Chart.js para graficar tus datos en un Dashboard.

* **Victor Hugo Muñoz Hernández** (1)
Hola buenas tardes ¿En qué casos sería útil usar --no-save ? Gracias, saludos.

	* **Anthony Mosquera** (3)

		
		Se usa sobre todo cuando estas probando paquetes.
		
		Si por ejemplo esta probando un paquete para formatos de fechas, no le vas a dar ‘save’ porque aun no estas seguro de que va a quedar en el proyecto final.
		
		Me parece buena practica porque el package.json suele ser un archivo que no revisamos muy a menudo y se nos pueden quedar cosas que en realidad no estamos usando.

## 0080. Package lock y el uso los símbolos ^ y ~

### Descripción:


### Comentarios:

* **Facundo Nicolás García Martoni (Platzi)** (20)
![wheelbarrel-no-tilde-caret-white-bg-w1000.jpg](https://static.platzi.com/media/user_upload/wheelbarrel-no-tilde-caret-white-bg-w1000-72ca1a72-4c7f-4abe-8482-425c01a72f89.jpg)

	* **Oscar Barajas Tavares (Platzi)** (5)

		
		Todos debemos de tener esta imagen en favoritos, es de mucha ayuda para crear nuestras versiones de software 😄

* **Karla Agraz** (5)

	
	  * ^ = Si mantenemos el caret dentro de la configuración de nuestro package estamos garantizando que cuando realicemos una actualización o tengamos un cambio que podamos realizar, vamos a hacer actualización de los cambios menores y de los parches o bug fixes.  
	Para quedarnos en una sola versión eliminamos el caret.
	
	  * ~ = Establece que vamos a recibir actualizaciones o cambios solamente de los cambios que son parches o bug fixes.
	
	
	

* **Iván Darío Sánchez Jiménez** (3)

	
	Nombre en español de los símbolos utilizados
	``` 
	    ^ Acento circunflejo
	    ~ Virgulilla
	    
	```

* **raparisg** (3)

	
	Es recomendable subir el package lock al repositorio? O se debe excluir con el gitignore?

	* **Oscar Barajas Tavares (Platzi)** (3)

		
		Si, no es obligatorio, pero si es parte esencial y maneja información importante de nuestros paquetes.

* **pabloverduzcos** (2)

	
	La mejor manera de guardar nuestras dependencias a utilizar con una versión exacta es indicando la siguiente bandera:
	``` 
	    npm install--save-exact nombreDelPaquete
	    
	```
	
	o en su versión corta:
	``` 
	    npm i -E nombreDelPaquete
	    
	```

* **Anthony Mosquera** (2)

	
	Les dejo este recurso que me salvo de algunos problemas de colisiones de versiones en mi ambiente de CI/CD, ademas, es la recomendación de NPM para versionar nuestro package-lock.json
	
	**npm shrinkwrap**
	
	<https://docs.npmjs.com/cli/shrinkwrap.html>

	* **Christian Erik Velázquez Morales** (1)

		
		Gracias, por la recomendación.

* **AryRosvall** (1)
No me quedó claro exactamente para que sirve el package-lock 😦

	* **Erik Ochoa (Platzi)** (4)

		
		Anteriormente cuando sólo teníamos el package.json, pasaba que al clonar un paquete y hacer `npm install` se instalaban actualizaciones menores que rompían el paquete, todo por lo permisivo de [semver](https://docs.npmjs.com/about-semantic-versioning).
		
		Ahora el archivo `package.json.lock` se encarga de presentar una captura estática del árbol de dependencias que estamos incluyendo en un proyecto. Ahora se respeta la versión exacta de la dependencia indicada, así cualquier persona del equipo, cuando ejecute npm install, será capaz de reproducir el mismo árbol que el de su compañero sin problemas dando estabilidad dentro de los proyectos.

* **estebanleoe** (1)
Cómo se sacan ^ y ~ en una mac con teclado ingles e input de US international? o al menos como se llaman esos símbolos para googlear los?

	* **Massimo Di Berardino** (3)

		
		Hola Estaban, el primer caracter es un acento circunflejo, y se hace con pulsando la tecla “opción” y la “I”, al mismo tiempo, seguido de un espacio, el segundo carácter es una virgulilla y se hace con ALT+Ñ

## 0090. Ejecutar tareas

### Descripción:


### Comentarios:

* **buzu** (11)

	
	Puedes también especificar scripts con el prefijo “pre” que se ejecutarán automáticamente antes del comando que ejecutaste. Por ejemplo, si defines el comando `build` y `prebuild`, cuando corras `npm run build` el comando `prebuild` se ejecutará primero. Esto sirbe para poder ejecutar tareas que hagan algún tipo de preparación necesaria para correr el comando principal. Sin embargo, hay que hacer notar que si el comando pre falla (retorna un valor que no es 0) el comando principal no se ejecutará. Esto es algo bueno ya que si nuestro proceso de preparación no se realiza de forma exitosa, puede que tengamos problemas al querer ejecutar la tarea principal.
	
	En algunas ocaciones, sin embargo, la tarea previa puede fallar sin que eso afecte la ejecución de la tarea principal. En esos casos puedes usar `|| exit 0` para retornar 0:
	``` 
	    "presass-build": "(rm css/*.css; rm css/*.css.map) || exit 0"
	    
	```
	
	Ese es un ejemplo de un comando que hice hace un tiempo. `rm` puede fallar si el directorio css está vacio, y en ese caso no hay problema, la tarea principal puede funcionar sin ningún problema ya que `presass-build` tiene el propósito de vaciar ese directorio.

	* **Oscar Barajas Tavares (Platzi)** (4)

		
		Muy buena explicación y sin duda falto añadirla en el flujo. gracias.

	* **buzu** (4)

		
		Gracias, algo que también faltó mencionar es que `npm run` agrega el directorio `./node_modules/bin/` al PATH de modo que para ejecutar un comando no es necesario agregar la ruta completa. Esto es algo que hace tiempo me confundió, cuando vi que Laravel ejecuta un comando `setenv` y yo quice buscarlo en mi computadora con `which setenv` y resultó que el comando no existía. Esto es porque en realidad el binario está ubicado en `node_modules/bin/`

	* **Oscar Barajas Tavares (Platzi)** (5)

		
		Creare una lectura para explicar estas ayudas. Gracias por tu aporte.

	* **balachvinic** (1)

		
		la parte que mencionan de ejecutar un comando que se encuentra **node_modules/bin/** supongo que corresponde a la ejecución de comando con ayuda de **npx** no conocía como funcionaba, pero básicamente busca el archivo binario ejecutable en todo **node_modules** y lo ejecuta. Muy útil el comando **npx** , creo que no se explica en el curso.

* **ThAlan** (6)

	
	A mi me gusta crear tres scripts.
	``` 
	    "dev": "webpack-dev-server --mode development",
	    "build": "webpack --mode production",
	    "start": "serve ./dist -s -l 8080"
	    
	```
	
	  * dev: Modo desarrollo.
	  * build: Compila todo y me crea un directorio dist.
	  * start: Toma el directorio dist y lanzo un servidor en modo producción.
	
	

	* **Ricardo Martínez Murillo** (1)

		
		muy efectiva practica!

	* **Christian Erik Velázquez Morales** (1)

		
		Gracias por sus recomendaciones.

* **Andres Roberto Coello Goyes** (4)

	
	## Normalmente yo creo 3 script  
	( DEV ) significa modo desarrollo o develomenp.  
	( BUILD ) significa contruccion de tu proyecto, se compila lo necesario para pasar de desarrollo a produccion.  
	( START ) significa que corre en produccion
	
	pero puedes crear tus propios script y ¿ como hacer que funcionen ?  
	eso depende del lenguaje o framework que estes utilizando por ejemplo en node js: NODE_ENV=Production

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Me gusta la recomendación, yo en lo personal solo utilizo start y build

* **Jose Luis Campos Bautista** (1)

	
	Podemos pasar argumentos a nuestros scripts configurados en package.js  
	.
	``` 
	    npm run <command> [-- <args>]
	    
	```

	* **JarlLuis** (1)

		
		Lo mejor es no passar argumentos, ponerlos en los scripts. Según sé, es la escencia de los scripts, que esribas menos argumentos

* **Karla Agraz** (1)

	
	Los scripts NPM: Son comandos que podemos establecer para poder ejecutar desde la consola. Estos nos van a dar una serie de salidas según sea el caso.
	
	Podemos crear la cantidad de scripts que necesitemos. Estos scripts van a poder correr de forma nativa dentro de nuestra terminal.

## 0100. Solución de problemas

### Descripción:


### Comentarios:

* **Samuel Mata** (7)

	
	Un minuto de silencio para aquellos que no le colocaron el directorio a rm -rf 😄

* **OmarGbet** (3)

	
	Ojalá existiera un curso solo para solucionar errores con los datos que arroja el editor. Hay algunos realmente complicados incluso cuando se leen detenidamente los detalles.

* **Anthony Mosquera** (2)

	
	Instalar **n** para manejar diferentes versiones de NodeJS en nuestro ambiente también nos puede ayudar a resolver problemas con librerías que necesitan versiones especificas de NodeJS, por ejemplo: node-sass

* **Jean Carlos Nuñez Hernandez** (2)

	
	npm run build --dd para ver el output en la terminal

* **Karla Agraz** (1)

	
	Cuando estés trabajando con proyectos que están usando NPM te vas a topar con una gran cantidad de posibles errores que vas a tener. Estos errores pueden ser desde la configuración, pueden ser desde el sistema operativo, espacios, no haber configurado correctamente tu GitHub, no haber establecido bien los datos del package, haber dejado un typo u algún elemento extraño dentro de esta configuración así como una serie de errores que pueden generarse, que no están ligados directamente a NPM.

* **OmarGbet** (1)

	
	Esta clase es una joya.

* **Roberto Esqueda** (1)

	
	Puede pasar que tenemos algún valor corrupto dentro de node_modules o no tengamos la instalación completa de los paquetes, para eso lo más conveniente es eliminar la carpeta node_modules:  
	**rm -rf node_modules/**  
	Después de eso, tenemos que volver a instalar los paquetes:  
	**npm install**

* **Roberto Esqueda** (1)

	
	Puede pasar que nuestros archivos en node_modules no estén bien instalados o tengamos una versión anterior, para esto podemos limpiar el cache:  
	**npm cache clean --force**
	
	Para verificar esto, podemos usar:  
	**npm cache verify**

* **AryRosvall** (1)
Los logs que se generan, supongo que generan espacio en nuestro disco ¿hay alguna forma de que se borren en automático o que npm tenga un...

	* **Erik Ochoa (Platzi)** (2)

		
		Esos logs son importantísimos para hacer “troubleshooting” al momento de tener un error y no ocupan un espacio considerable la mayoría del tiempo.
		
		No conozco si npm tiene algún comando para borrarlo, pero al ser un archivo más, lo podrías programar en un script y ponerlo a correr con el **crontab** en MacOS o **cron** en Linux.
		
		Este curso te puede servir para eso: <https://platzi.com/clases/terminal/>

* **yisus_dev** (0)
¿qué es eso que llamas typo o tipo ?

	* **Ruben Padilla** (4)

		
		¡Hola!
		
		Un _typographical error_ ( ** _typo_** ) es un error que se presenta cuando escribes mal una palabra.
		
		Saludos!

## 0110. Seguridad

### Descripción:


### Links:

* [Snyk | Develop Fast. Stay Secure](http://snyk.io/)

### Comentarios:

* **José Tuzinkievicz** (7)

	
	Sería recomendable primero intentar solucionar con **npm audit fix** y lo que no se solucione lo actualizamos de a uno?

	* **Oscar Barajas Tavares (Platzi)** (5)

		
		Sí, ese seria el camino idóneo para auditar nuestros proyectos.

* **Manuel Rivera** (1)

	
	Pienso que hay que tener mucho cuidado con el comando npm audit fix, ya que todo depende del proyecto en el que estemos trabajando, ya que como hemos visto en el trayecto del curso, pueda que estemos trabajando con algunas dependencias en específico y este comando podría actualizarlas, creería yo, no lo se rick

	* **Juan José Vega Quintero** (1)

		
		Sí, no se debería usar si no se sabe que esta pasando de fondo.

	* **pabloverduzcos** (2)

		
		Pero recuerda que existen tres tipos de cambios en una versión.  
		Normalmente una actualización para solucionar problemas de seguridad solamente se realiza un **parche (patch)** , por ejemplo una dependencia pasa de la versión 1.0.0 a la versión 1.0.1 o bien se realiza un cambio **menor (minor)** que por ejemplo una dependencia pasaría de la versión 1.0.0 a la versión 1.1.0; en estos casos no debería de haber ningún problema, sin embargo cuando existe un cambio **mayor (major)** , por ejemplo cuando una dependencia pasa de la versión 1.0.0 a la versión 2.0.0 deberíamos tener cuidado por que es ahí cuando probablemente la dependencia que estemos utilizando empiece a funcionar de manera totalmente diferente y ahí tendríamos que hacer una migración para poder esperar el funcionamiento adecuado 👨🏻‍💻  
		.  
		![wheelbarrel-no-tilde-caret-white-bg-w1000-72ca1a72-4c7f-4abe-8482-425c01a72f89.jpg](https://static.platzi.com/media/user_upload/wheelbarrel-no-tilde-caret-white-bg-w1000-72ca1a72-4c7f-4abe-8482-425c01a72f89-b85d077f-5bb6-4cc2-b527-1f368ca64d95.jpg)

	* **Manuel Rivera** (2)

		
		@pabloverduzcos Estas en lo correcto bro, saludos

	* **pabloverduzcos** (2)

		
		Igualmente Manuel 😁

* **Roberto Esqueda** (1)

	
	Podemos revisar las vulnerabilidades de nuestro proyecto con:  
	**npm audit**  
	En caso de tener vulverabilidades, se recomienda usar el comando:  
	**npm audit fix**  
	Y en caso de que esto no lo solucione, podemos ir actualizandolos de uno en uno.

* **edwintrumpet** (1)
Tengo una aplicación un con una vulnerabilidad crítica y seguí las instrucciones pero no me funcionó Usé el comando npm update pid...

	* **buzu** (1)

		
		Algunas veces las actualizaciones introducen cambios que pueden romper tu app. En esos casos npm no hace la actualización. Fijate si te da un mensaje al respecto.

* **Cristian Mota Núñez** (1)
No me ha quedado claro el tema del –depth y sus niveles alguien me lo explica con mas detalles, cada nivel de este flag.

	* **Oscar Barajas Tavares (Platzi)** (3)

		
		Son las profundidades en las que puedes acceder:
		``` 
		    {
		    	1: {
		    		2 {
		    			3 {
		    			..	
		    			}
		    		}
		    	}
		    }
		    
		```

# Publicar un paquete

## 0120. Crear un paquete para NPM

### Descripción:


### Links:

* [Page not found · GitHub · GitHub](https://github.com/platzi/npm-random-msg)

### Comentarios:

* **Miguel Ángel Muñoz Pozos** (5)

	
	Muy bueno este vídeo como crear un paquete para NPM ME GUSTA de hecho me dio muchas ideas de crear unos módulos y compartirlos

* **mafevito** (2)
Hola, que herramienta se utiliza para poder colocar la tipografía de la línea 1 en el archivo global.js?

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Es parte del tema que utilizo para VSCode puedes descargarlo aca: <https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode>

* **AryRosvall** (1)
Si ya tenemos un estandar de carpetas y procedimientos por ejemplo hacer el git init y luego el npm init y luego agregar carpeta src. Se ...

	* **Luis Arturo Lira Cerda** (2)

		
		Lo que podrías hacer es crear un un alias a línea de comandos que ejecute todo en el orden que necesitas:  
		`git init && npm init -y && mkdir src`

## 0130. Publicar un paquete en NPM

### Descripción:


### Links:

* [
    
      
        
        Packages and modules | 
      
      
    npm Documentation
  ](https://docs.npmjs.com/packages-and-modules/)

* [npm | build amazing things](https://www.npmjs.com/)

### Comentarios:

* **Facundo Nicolás García Martoni (Platzi)** (20)

	
	 **Solución al error** “403 Forbidden - PUT <http://registry.npmjs.org/random-messages> \- You do not have permission to publish “random-messages”. Are you logged in as the correct user?”  
	.  
	En el archivo `package.json` cambiar el atributo `name` a un nombre original, puesto que el profe ya subió su repositorio con el nombre de `random-messages`, por lo que no podemos tener nosotros un proyecto del mismo nombre en NPM 😉

* **33andres33** (2)

	
	me aparece sudo command not found

* **luisglopez7777** (2)

	
	Si acaban de crear su cuenta la tienen que verificar para poder publicar un paquete

* **braco** (1)

	
	No me quedo tan claro que hace el comando npm link, ¿Alguien me puede explicar un poco?

	* **Jose Luis Campos Bautista** (1)

		
		Por lo que entiendo es que el comando [`npm link`](https://docs.npmjs.com/cli/link.html) crea un [link simbólico ](https://www.cambiatealinux.com/ln-crear-un-enlace-simbolico-al-fichero-o-directorio) en node_modules global.  
		.  
		Prácticamente una referencia en la carpeta node_modules global que va a estar apuntando a nuestro proyecto.

	* **JarlLuis** (1)

		
		Npm install <paquete> te va a instalar desde servidor npm, npm link (estando en la carpeta de dónde tomas el módulo) instala el módulo(se dice instala pero pues ya lo tienes en tu compu, es tu código, por eso se llama link, solo linkea la fuente de tu código a el nombre de ejecución que guardamos en bin). Por lo que probé, lo instala de forma global aunque no le digas, aunque no pongamos preferGlobal:true o lo pongas en false, a mi ni siquiera me pide permisos para instalarlo

* **alexanderbriones** (1)

	
	¿alguna ayuda?  
	![npm-random.PNG](https://static.platzi.com/media/user_upload/npm-random-df79c86b-2d19-40a0-9408-733a6be93729.jpg)

	* **Oscar Barajas Tavares (Platzi)** (1)

		
		En el mensaje de error te menciona que no esta encontrando el archivo. donde estas ejecutando el link

	* **kestiven** (1)

		
		Iniciaste el proyecto con **npm init** , existen todos los archivos.

* **OmarGbet** (1)

	
	Siempre creí que esto era bastante duro pero realmente es simple.

	* **Juan José Vega Quintero** (2)

		
		X2 cualquiera lo puede hacer (aplica para muchas cosas)

* **lucascartisano** (1)
A que le llaman un check que no tiene vulnerabilidades? tener un paquete actualizado es lo mismo que no tener vulnerabilidades?

	* **OmarGbet** (2)

		
		Es considerado cualquier tipo de defecto que puede ser utilizado para corromper u obtener beneficio de las fallas de seguridad del software.

## 0140. Paquetes privados

### Descripción:


### Links:

* [funny-commit  -  npm](https://www.npmjs.com/package/funny-commit)

* [Curso de Unit Testing con Jest en React](https://platzi.com/cursos/jest/)

### Comentarios:

* **Tonalli López** (9)

	
	Aquí esta el gist: [README.MD](https://gist.github.com/gndx/1b2c8482049c6d3b521dffcf33337558)

* **Fernando Torres** (3)

	
	Listo! Aquí está mi [package](https://www.npmjs.com/package/random-messages-fertorresmx)

* **JandroMejia** (3)

	
	Aquí está mi paquete: <https://www.npmjs.com/package/random-messages-jm>

	* **Oscar Barajas Tavares (Platzi)** (1)

		
		¡Genial! Probandolo.

* **Iván Darío Sánchez Jiménez** (2)

	
	Les comparto mi package, el cual retorna frases celebres de manera aleatorio para motivar nuestra labor como desarrolladores.
	
	[Cosmos Mesagges](https://www.npmjs.com/package/cosmos-messages)

* **Camilo Andrés Santana Lizcano** (2)

	
	Super este curso, [aquí](https://www.npmjs.com/package/random-names-rulocodev) mi paquete 😄

* **Carlos Huaytan** (2)
En la documentacion “npm” no encontre la lista de “flags”, si alguien tiene el link se agradeceria lo pueda compartir

	* **fredyramosp** (3)

		
		Hola,
		
		Tal vez lo encuentres en la terminal con el parametro help
		``` 
		    npm --help ```
		    
		```

* **Jose Luis Campos Bautista** (1)

	
	Hola, les comparto mi package, con este package podrán crear la estructura de de un API con express con son los end-points que le especifiquen.
	
	[bootstrap-api-express](https://www.npmjs.com/package/bootstrap-api-express)

* **David Andres Carrera Pineda** (1)

	
	 **npm version**  
	Puede ser útil para manejar el versionado de nuestros proyectos.  
	<https://docs.npmjs.com/cli/version>

* **Camilo Andrés Santana Lizcano** (1)

	
	Notas del curso [Aquí](https://platzi.com/tutoriales/1763-npm/5094-npm/)

* **Elias Ojeda Medina** (1)

	
	Cool, aquí mi paquete
	
	<https://www.npmjs.com/package/random-messages-eocode-platzi>

* **joelnbl** (1)

	
	[](https://www.npmjs.com/package/random-names-joelnbl) Here it is

* **Alver Ortega** (1)

	
	Buenas profesor, aqui le comparto mi proyecto  
	[random-names](https://www.npmjs.com/package/npm-js-alver)

* **Sergio Alejandro Trejo Cuxim** (1)

	
	Hola, ¿y como pudiera importar ese paquete?  
	Es decir, por medio de require o import a otro proyecto.

	* **Juan José Vega Quintero** (1)

		
		  1. Instalarlo con npm install -g random-msg,  
		en el archivo que quieras utilizarlo
		  2. ingresas const random-message = require (‘random-msg’)  
		y a usarlo
		
		

* **Miguel Ángel Muñoz Pozos** (1)

	
	Buenas tardes profesor aquí esta mi ejemplo de mi paquete, agregando el repositorio en gitHub y cambie los mensajes por unas frases de motivación jejejeje  
	[mi paquete en npm ](https://www.npmjs.com/package/random-messages-miguel-angel)

## 0150. Cierre del curso

### Descripción:


### Links:

* [Curso de Prework: Buenas Prácticas y Entorno de Desarrollo](https://platzi.com/clases/prework/)

* [Curso de Backend con Node.js](https://platzi.com/clases/backend-nodejs/)

### Comentarios:

* **Rogelio Torres Dueñas** (1)

	
	¿No hay examen de este curso?, me dirige a la pagina principal.

* **louismanson** (1)

	
	hubiera estado bien hablar de [Yarn](https://yarnpkg.com), [homebrew](https://brew.sh/index_es) y [Bower](https://bower.io) R.I.P.

	* **Gabriel De Andrade (Platzi)** (3)

		
		Mmmm, no lo sé. Yarn es el único que se asemeja, pero si sabes NPM con leerte un poco de la documentación de Yarn tienes. Homebrew es para instalar paquetes en tu máquina, no un gestor de dependencias para proyectos. Y Bower casi no se usa ya.  
		  
		Creo que hubieran sido temas que no son relevantes para este curso, pero igual es una discusión interesante y que animo a todxs a tener 😄

* **Sergio Alejandro Trejo Cuxim** (1)

	
	Hola, ¿y como pudiera importar ese paquete?  
	Es decir, por medio de require o import a otro proyecto.

	* **miguelangelsoler** (1)

		
		Debes instalarlo como dependencia en tu proyecto para usarlo.

	* **Cesar Galindo** (3)

		
		para utilizarlo lo instalas con npm install -g random-msg, en el archivo que quieras utilizarlo, ingresas const random-message = require (‘random-msg’). con eso ya lo podras utilizar

