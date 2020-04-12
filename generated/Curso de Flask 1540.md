[Curso de Flask 1540](https://platzi.com/cursos/flask)

# Fundamentos de Flask [3697]

## 0010. Introducción [18440](https://platzi.com/clases/1540-flask/18440-introduccion/)

### Descripción:
Conoce todo el potencial de Flask como framework web de Python, integraciones con Bootstrap, GCloud, What The Forms y más.

Flask es sencillo de aprender, tiene una documentación clara y práctica, es rápido a la hora de renderizar **puede ser hasta tres veces más rapido que Django**. También es fácil de realizar una API REST, la estructura de un proyecto es flexible y es ideal para aprender desarrollo web con un framework de Python.

### Comentarios:

* **Mauricio Chávez Olea** (7) [540525](https://platzi.com/comentario/540525/) 

	¡Qué emocionante!
	
	Actualmente sé Django y nada de Flask, y realmente me interesa 😄

	* **Ernesto Vizcaíno Alvarado** [540525] (1)

		Voy a la mitad del curso de Django crees que pueda toamr este tambien o solo enfocarme en django?

	* **Mauricio Chávez Olea** [540525] (2)

		Son diferentes, aunque comparten muchas similitudes. Yo creo que puedes tomar ambos sin problemas

	* **Camilo Varon** [540525] (2)

		yo creería que primero aria flask y luego si django ya q este es mas complejo.

* **Jorge** (4) [641726](https://platzi.com/comentario/641726/) 

	Me fuera gustado que el curso llevara algun ejemplo de conexion a una DB, ya que llevo semanas tratando de realizar trabajos con bases de datos como sqlite y mysql. si alguien ya lo ha hecho le agradeceria si pudiera ayudarme.
	
	gracias.

	* **Diego Alexander Forero Higuera (Platzi)** [641726] (2)

		Hola, para usar bases de datos con flask debes instalar SQLAlchemy u otro orm para facilitar la conexión y trabajo con la base de datos. Encontré este tutorial que te puede servir para lo que necesitas hacer <https://medium.com/@mwesigwafrank/python-flask-mysql-crud-tutorial-part-one-abf66a348bda>

* **Adrián Andrés Sosa** (1) [1027176](https://platzi.com/comentario/1027176/) 

	Ok, empecemos

* **robertmezagarcia** (1) [796160](https://platzi.com/comentario/796160/) 

	Empezaré este curso porque estoy haciendo un proyecto donde empecé a crear un simple servidor api con flask

* **Fp_1000** (1) [607221](https://platzi.com/comentario/607221/) 

	Han cambiado la interfaz de comentarios 😃

## 0020. ¿Cómo funcionan las aplicaciones web [18441](https://platzi.com/clases/1540-flask/18441-como-funcionan-las-aplicaciones-web/)

### Descripción:


Cuando utilizas una aplicación web puedes interactuar con ella desde una computadora hasta un dispositivo móvil, pero esto no quiere decir que consume el procesamiento de tu dispositivo. Todo lo contrario, se hace en una red de servidores.

Estos servidores unen su poder de procesamiento con el fin transmitir solicitudes a todo el mundo, a su vez utilizar servidores especializados para almacenar los datos con los cuales se está trabajando, así como los datos de los demás usuarios. Como todo esto sucede sin demora alguna, parecerá que la aplicación se está ejecutando de forma nativa en tu dispositivo.

El servidor procesa la información obtenida por el navegador, luego se realizan los procedimientos necesarios de acuerdo a la lógica de negocio de la aplicación para regresar la información solicitada al cliente.

**Ejemplo:**

Cuando utilizamos **Google Drive** el cual es una aplicación web y abrimos un documento con Google Docs, el navegador se comunica con los servidores para ver y editar el documento.

A medida que vayas editando el documento, tu navegador trabajará de la mano con los servidores para asegurarse que todos los cambios se estén guardando.

**Ventajas:**

* Muchas de las aplicaciones web que existen son gratuitas.
* Puedes acceder a tu información en cualquier momento y lugar.
* No dependes de un dispositivo en específico ya que la aplicación se encuentra almacenada en la web.



### Comentarios:

* **Jo-Anna** (2) [786802](https://platzi.com/comentario/786802/) 

	Un poco mas detalle de ¿Cómo funcionan las aplicaciones web?
	
	* <https://youtu.be/8zQqHII2840>
	
	

* **Royer Guerrero Pinilla** (1) [1067318](https://platzi.com/comentario/1067318/) 

	Aquí les dejo compañeros  
	[What is Web App!](https://blog.stackpath.com/web-application/)

## 0030. ¿Qué es Flask [18442](https://platzi.com/clases/1540-flask/18442-que-es-flask/)

### Descripción:


En esta clase el profesor Bernardo Cassina nos explica cómo podemos usar Flask para desarrollar aplicaciones web escritas en Python con este framework.

Flask es un framework minimalista escrito en Python que permite crear aplicaciones web rápidamente y con un mínimo de líneas de código, busca que su infraestructura inicial sea lo más simple posible y pueda personalizarse fácilmente, puedes extender sus funcionalidades con las llamadas Flask Extensions <http://flask.pocoo.org/extensions/>

### Comentarios:

* **Ricardo Lugo Recillas** (3) [655635](https://platzi.com/comentario/655635/) 

	que es flask = es un microfamework, framework minimalista escrito en python es flexible es lo mas simple.
	
	pip = librerias para manejar paquetes en pithon

* **DaneSanchz** (3) [548939](https://platzi.com/comentario/548939/) 

	Flask, el Framework flexible  
	<https://platzi.com/blog/flask-el-framework-flexible/>

* **Juan Daniel Gualtero Diaz** (2) [823745](https://platzi.com/comentario/823745/) 

	Lo que he leído es que este es un microframework se me hace similar a lo que es vue js para angular,dado que puedo crear una app muy simple sin utilizar un proyecto complejo e ir añadiendo progresivamente complejidad en cuanto mi app crezca.

* **matias-alexander-ibarra-trujil** (2) [77638](https://platzi.com/comentario/907175/) 
sera posible integrar flask con django?? es uno o el otro ???

	* **Juan David Castro (Platzi)** [77638] (2)

		Puedes trabajar con Flask y Django “juntos” si trabajas con microservicios. Serían dos aplicaciones separadas. Pero, por ejemplo, podrían hacer peticiones a la misma base de datos o funcionar como APIs, así los usuarios ni se enteran que cambiaron de Django a Flask o de Flask a Django.
		
		Te recomiendo estas lecturas:
		
		👉 <https://www.fullstackpython.com/microservices.html>  
		👉 <https://www.toptal.com/python/introduction-python-microservices-nameko>  
		👉 <https://medium.com/@ssola/building-microservices-with-python-part-i-5240a8dcc2fb>  
		👉 <https://medium.com/@sonusharma.mnnit/building-a-microservice-in-python-ff009da83dac>  
		👉 <https://www.paradigmadigital.com/dev/implementar-microservicios-python-minutos/>

* **jdgarcia6** (1) [544868](https://platzi.com/comentario/544868/) 

	se ve interesante el curso. me llama la atención de que sea más liviano que django.

* **ruben catalan rivera** (1) [544259](https://platzi.com/comentario/544259/) 

	excelente. muy emocionado de iniciar el curso!

* **diego21** (1) [72937](https://platzi.com/comentario/825683/) 
El vídeo no se reproduce

	* **Juan David Castro (Platzi)** [72937] (1)

		Esta es una clase pública, es decir, está publicada en YouTube. Puedes verla también ingresando directamente con este link: <https://youtu.be/EGuSg47sP6k>. 😉

## 0040. Instalación de Python, pip y virtualenv [18833](https://platzi.com/clases/1540-flask/18833-instalacion-de-python-pip-y-virtualenv/)

### Descripción:


### Esta es la guía para configurar nuestro ambiente con Python 3.

Por lo general Mac ya incluye una instalación de Python, la puedes verificar ejecutando los siguientes comandos en una terminal:
``` 
    python --version
    
```

> 
```
    python3 --version
    
```

Debemos asegurarnos de tener **python 3**. Para instalar Python puedes seguir el siguiente enlace y después regresar a esta lectura.

<https://platzi.com/clases/1378-python/14289-guia-de-instalacion-y-conceptos-basicos/>

### Instalación en Windows

Una vez que instalaste **python 3** desde [python.org](https://www.python.org/) vamos a verificar que también incluimos **pip** en esta instalación. Después debes correr el siguiente comando para instalar virtualenv:
``` 
    pip install virtualenv
    
```

El sistema debe haber instalado virtualenv y ahora podemos comenzar con el curso.

### Instalación en Mac

Si ya instalaste python 3 ahora corre el siguiente comando para instalar **pip** :
``` 
    sudo easy_install pip
    
```

Para install virtualenv de manera global corre:
``` 
    pip install virtualenv
    
```

El sistema debe haber instalado virtualenv y ahora podemos comenzar con el curso.

### Comentarios:

* **raulfbgomez** (4) [996980](https://platzi.com/comentario/996980/) 

	Para instalar pip en Ubuntu 18
	``` 
	    sudo apt install python3-pip
	    
	```
	
	Instalar virtualenv
	``` 
	    pip3 install virtualenv
	    
	```

* **Jo-Anna** (4) [787225](https://platzi.com/comentario/787225/) 

	Documentación oficial de Flask para instalación - <https://flask.palletsprojects.com/en/1.1.x/installation/>

* **Enrique Sardon Manrique** (2) [1041878](https://platzi.com/comentario/1041878/) 

	virtualenv desde hace muchas versiones ya está incluido en python como un modulo integrado en el comando python, solo hay que hacer
	``` 
	    python -m venv nuestro_virtual_env
	    
	```

* **Jose Gomez** (2) [55687](https://platzi.com/comentario/543989/) 
¿Si quiero realizar un proyecto con una aplicación web donde me conectaré mediante un smart phone, debo seguir estos mismos pasos? muchas...

	* **Jeith S Carrillo A** [55687] (2)

		si, son exactamente los mismos.  
		se podría obviar el tema de virtualenv pues este solo crea una maquina virtual donde correrá el archivo de python.

* **Royer Guerrero Pinilla** (1) [1067339](https://platzi.com/comentario/1067339/) 

	👨‍💻 Sencillo, si usas python3 lo mas probable es que necesites pip3

* **Jose Gomez** (1) [543989](https://platzi.com/comentario/543989/) 

	¿Si quiero realizar un proyecto con una aplicación web donde me conectaré mediante un smart phone, debo seguir estos mismos pasos? muchas gracias.

	* **Jeith S Carrillo A** [543989] (2)

		si, son exactamente los mismos.  
		se podría obviar el tema de virtualenv pues este solo crea una maquina virtual donde correrá el archivo de python.

	* **Bernardo Cassina** [543989] (2)

		Sí, después de hacer deploy a producción tu smartphone se comunicaría con tu aplicación web a través del buscador. Eso resuelve tu duda?

## 0050. Hello World Flask [18443](https://platzi.com/clases/1540-flask/18443-hello-world-flask/)

### Descripción:


Estos son los conceptos principales que debes entender antes de hacer un Hello World en Flask:

* **virtualenv:** es una herramienta para crear entornos aislados de Python.

* **pip:** es el instalador de paquetes para Python.

* **requirements.txt:** es el archivo en donde se colocará todas las dependencias a instalar en nuestra aplicación.

* **FLASK_APP:** es la variable para identificar el archivo donde se encuentra la aplicación.




### Links:

* [Welcome | Flask (A Python Microframework)](http://flask.pocoo.org/)

### Comentarios:

* **Camilo Cáceres** (10) [540783](https://platzi.com/comentario/540783/) 

	Si estás en Windows, la ruta para activar el venv es
	``` 
	    venv\scripts\activate
	    
	```
	
	Y para declarar la variable FLASK_APP (en Windows):
	``` 
	    set FLASK_APP=main.py
	    
	```

	* **Andrés Felipe Martínez Salazar** [540783] (3)

		SI se usa la powershell tienes que usar `$env:FLASK_APP="main.py"`

	* **ClaudioHerreraC** [540783] (1)

		Gracias por eso!

	* **ave** [540783] (1)

		muchas gracias, Amigo, me ayudaste full

* **Jo-Anna** (7) [787336](https://platzi.com/comentario/787336/) 

	 **Crear el Entorno Virtual en windows:**
	
	Para crear un nuevo virtualenv, necesitas abrir una terminal command prompt y ejecutar
	``` 
	    python3 -m venv myvenv
	    
	```
	
	Se verá así:
	``` 
	    C:\Users\Name\platzi-flask> python3 -m venv myvenv
	    
	```
	
	Donde **myvenv** es el nombre de tu **virtualenv**.
	
	Puedes utilizar cualquier otro nombre, pero asegúrate de usar minúsculas y no usar espacios, acentos o caracteres especiales. También es una buena idea mantener el nombre corto. ¡Vas utilizarlo muchas vecesl!
	
	**Inicia el entorno virtual ejecutando:**
	``` 
	    C:\Users\Name\platzi-flask> myvenv\Scripts\activate
	    
	```
	
	Fuente de texto: <https://tutorial.djangogirls.org/es/django_installation/>

* **osw4ldev** (6) [561672](https://platzi.com/comentario/561672/) 

	para sacar lo que hay en el virtualenv y agregarlo en el requirements tambien podemos usar esta linea:
	``` 
	    pip freeze >> requirements.txt
	    
	```

* **David Vargas Domínguez** (5) [540601](https://platzi.com/comentario/540601/) 

	```
	    pip freeze
	    
	```
	
	para ver las dependencias del proyecto
	``` 
	    export FLASK_APP=main.py
	    
	```
	
	es necesario declarar una variable de ambiente para que flask conozca donde está la instancia de flask y así poder correr flask run

	* **Alexander Mateo** [540601] (1)

		¡Gracias! 😃

	* **juan diego ramirez rojas** [540601] (1)

		sos un crack!

* **diegoaranr** (4) [766178](https://platzi.com/comentario/766178/) 

	La asignacion del la variable de entorno FLASK_APP se puede hacer de las siguientes formas en Windows:  
	Usando CMD
	``` 
	    > set FLASK_APP=hello
	    > flask run
	    
	```
	
	Usando Powershell
	``` 
	    > $env:FLASK_APP = "hello"
	    > flask run
	    
	```
	
	[Taken from here](https://flask.palletsprojects.com/en/1.1.x/cli/)

* **MatiasBZ** (3) [544777](https://platzi.com/comentario/544777/) 

	Algunas veces es necesario instalar versiones anteriores. Para eso se debe especificar la versión de la dependencia a instalar:::
	
	* Instalación con requirement.txt:
	
	
	  1. Creamos un archivo de texto:`$touch requirements.txt`
	
	  2. Cargamos nuestras dependencias a instalar:  
	`flask==1.0.2 django==2.1.7 sqlalchemy -U` #Para ultima versión es con -U
	
	  3. Ejecutamos pip install:  
	`$pip install –r requirements.txt`
	
	
	

* **Mauricio Chávez Olea** (3) [540703](https://platzi.com/comentario/540703/) 

	Para crear un entorno virtual con Python 3 también se puede de la siguiente manera:
	``` 
	    python3 -m venv <nombre-del-entorno>
	    
	```

	* **Jorge Toledano** [540703] (1)

		Así lo hice en mi máquina con Debian 9:
		
		virtualenv -p /usr/bin/python3 venv

* **brandon james grimaldo moscote** (2) [1036132](https://platzi.com/comentario/1036132/) 

	en el cdm.exe de windows  
	py -3 -m venv venv  
	venv\Scripts\activate  
	![f.JPG](https://static.platzi.com/media/user_upload/f-0ffddc5d-51ef-4e72-b3bc-3f0a00de2910.jpg)

* **Francisco Javier Antúnez Durán** (2) [909693](https://platzi.com/comentario/909693/) 

	Por si sirve de ayuda
	``` 
	    #Lista los elementos de nuestro entorno virtual
	    pip list
	    
	    #Crear archivo con instrucciones para instalar los requisitos de nuestro entorno virtual
	    pip3 freeze > requirements.txt
	    
	```

* **Gonzalo Muñoz** (2) [641837](https://platzi.com/comentario/641837/) 

	A los que quieran el IDE del profesor (PyCharm), pueden tener una licencia de un año gratis si tienen un correo de estudiante @*.edu, y se crean una cuenta en JetBrains <https://www.jetbrains.com/shop/eform/students>

* **innacroft** (1) [1074610](https://platzi.com/comentario/1074610/) 

	En windows no usen export, usen set  
	**set FLASK_APP=[main.py](http://main.py)**

* **innacroft** (1) [1074453](https://platzi.com/comentario/1074453/) 

	En windows para activar el entorno la ruta es :  
	**vnv\Scripts\activate**

* **Royer Guerrero Pinilla** (1) [1067663](https://platzi.com/comentario/1067663/) 
	
	![Imagen 4.png](https://static.platzi.com/media/user_upload/Imagen%204-021be48c-3887-4036-a5a8-26a7b6feeba7.jpg)

* **marttcode** (1) [1051343](https://platzi.com/comentario/1051343/) 
<h1>Alto aquí!</h1>
	
	Para que no tengas problemas en videos posteriores **instala la version de flask del profe**. Aquí te dejo el requirements.txt
	``` 
	    flask==1.0.2
	    click==7.0
	    jinja2==2.10
	    itsdangerous==1.1.0
	    markupsafe==1.1.1
	    werkzeug==0.14.1
	    flask-bootstrap==3.3.7.1
	    flask-wtf==0.14.2
	    
	```
	
	Si ya **creaste tu venv inicia uno nuevo** en un nuevo directorio y ejecuta el requirements que te deje arriba.

* **xmedinavei** (1) [1043354](https://platzi.com/comentario/1043354/) 

	En la linea
	``` 
	    from flask import Flask
	    
	```
	
	me sale error. Me sudeció lo mismo en todos los imports cuando usaba Django. Siempre sucede el error cuando esta activado el virtualenv (aunque el codigo esté bien y el servidor corra sin problema).
	
	Esto no afecta al rendimiento de la app pero es molesto ver errores. Alguien sabe como solucionarlo?

* **Moshe Cotacallapa** (1) [1043216](https://platzi.com/comentario/1043216/) 

	Para usar los mismos comandos del video, recomiendo usar [git for windows](https://gitforwindows.org/). Si desea trabajar con el shell de python desde git bash :
	``` 
	    python -i
	    
	```

* **Enrique Sardon Manrique** (1) [1042080](https://platzi.com/comentario/1042080/) 

	Como suugerencia recomiendo aprende a usar pipenv, es muy practico a la hora de hacer entornos virtuales y manejo de dependencias
	
	hay otros que usan conda, pero personalmente prefiero usar pipenv

* **brandon james grimaldo moscote** (1) [1036340](https://platzi.com/comentario/1036340/) 

	tuve muchos problemas para lograrlo , pero alfin , alfiiiin![ff.JPG](https://static.platzi.com/media/user_upload/ff-5a35d0f2-57c5-40bf-8e02-ce8134ffe31c.jpg)

* **andresazuara98** (1) [1026323](https://platzi.com/comentario/1026323/) 

	I’ve got errors running python with flask, I couldn’t create the environment variable FLASK_APP, so I did this:  
	instead of running the server with flask run, I did it with python [main.py](http://main.py), but in the file I had to add the next code:
	``` 
	    if __name__ == "__main__":
	    	app.run()
	    
	```

* **Gastón Angúlo Alcácer** (1) [981873](https://platzi.com/comentario/981873/) 

	Según el error me salió, mirando el debug dice que al main hay que nombrarlo como “[app.py](http://app.py)”, así se me solucionó

* **modulo7** (1) [957987](https://platzi.com/comentario/957987/) 

	Para crear un archivo .txt desde windows (CMD) usamos en comando “copy con” en lugar de “touch”.

* **diegomedflo** (1) [954102](https://platzi.com/comentario/954102/) 

	Al intentar correr el servidor me aparece este error. Pensé que ya tenia isntalado python. como instalo python en el entorno virtuaol?  
	`(myenv) C:\Users\diego\platziflask>flask run No Python at '/usr/bin\python.exe'`

* **viktorv** (1) [786982](https://platzi.com/comentario/786982/) 

	Que deberia hacer para instalar python 3.7?  
	Tengo el siguiente error  
	![](![2019-10-18.png](https://static.platzi.com/media/user_upload/2019-10-18-bd5097ca-9689-418a-a0ee-92ac30944865.jpg)

	* **Jo-Anna** [786982] (2)

		Que sistema operativo tienes?
		
		El comando que escribes en tu terminal>
		``` 
		    virtualenv venv --python=3.7
		    
		```
		
		Cámbialo a
		``` 
		    python3 -m venv myvenv
		    
		```

	* **viktorv** [786982] (2)

		Excelente! Gracias por tu ayuda @Jo-Anna
		
		Respondiendo a tu pregunta, tengo WSL corriendo en w10 Home x64

* **Chris.ha** (1) [693138](https://platzi.com/comentario/693138/) 

	Hola, alguein prodía echarme una mano con el siguiente error?
	
	The path python3.7 (from --python=python3.7) does not exist

	* **Emmanuel Maidana** [693138] (1)

		en lugar de escribir el ejemplo del profesor, escribí:
		``` 
		    virtualenv venv/Scripts/activate
		    
		```
		
		Va a llamar a python3 solo. Abrazo!

	* **Jo-Anna** [693138] (1)

		Usa este comando
		
		`python3 -m venv myvenv`
		
		Se verá así:
		
		C:\Users\Name\platzi-flask> python -m venv myvenv
		
		Donde `myvenv` es el nombre de tu `virtualenv`. Puedes utilizar cualquier otro nombre, pero asegúrate de usar minúsculas y no usar espacios, acentos o caracteres especiales. También es una buena idea mantener el nombre corto. ¡Vas utilizarlo muchas vecesl!
		
		Inicia el entorno virtual ejecutando:
		
		`C:\Users\Name\platzi-flask> myvenv\Scripts\activate`
		
		Fuente de texto: <https://tutorial.djangogirls.org/es/django_installation/>

	* **YamiDeV** [693138] (1)

		No tienes instalado esa versión del interprete en tu computadora, que sistema operativo estas usando?

	* **raulfbgomez** [693138] (1)

		Justo eso me paso, simplemente utilice una versión anterior:
		``` 
		    virtualenv venv --python=python3.6
		    
		```
		
		Utilizo Elementary OS Hera

* **Josué Isaac Fuentes López** (1) [607525](https://platzi.com/comentario/607525/) 

	Por si deben de instalar Python3.7 en ubuntu
	
	<https://websiteforstudents.com/installing-the-latest-python-3-7-on-ubuntu-16-04-18-04/>

* **Sebastian Villegas** (1) [543445](https://platzi.com/comentario/543445/) 

	En windows como se activa? el comando “source” me sale como erroneo

	* **ruben catalan rivera** [543445] (1)

		en windows yo fui directamente a la carpeta de activate con  
		cd desktop/(carpeta del proyecto)/venv/scripts  
		y luego poner activate en la terminal.

	* **Jeith S Carrillo A** [543445] (2)

		el comando es :
		``` 
		    source venv/Scripts/activate
		    
		```

	* **jenapi** [543445] (2)

		@JeithxD Ese comando solo sirve en terminales con bash, en cmd el comando es diferente

* **Mauricio Chávez Olea** (1) [540704](https://platzi.com/comentario/540704/) 

	¿Soy yo o se parece mucho a Express.js? 😂

	* **Jairo  castañeda** [540704] (2)

		Cuando se usa express sin ningún generador de archivos si , la libertad de escribir la arquitectura en los dos es algo similar

	* **Marco Antonio Macedo Preciado** [540704] (1)

		Eso pensaba, es un Express.js con muchas menos lineas de código jaja

* **Nicolás Mayorga Vargas** (1) [81974](https://platzi.com/comentario/994419/) 
¿Por qué se desactivan los comandos de asignación de FLASK_APP al apagar el PC?

	* **Andrés David Ríos Ramirez** [81974] (1)

		si no lo agregas al archivo que se ejecuta cuando abres la terminal (. bash_profile) vas a tener que agregar dicha variable a mano cada vez que te conectes.  
		Revisa acá <https://www.serverlab.ca/tutorials/linux/administration-linux/how-to-set-environment-variables-in-linux/>

* **adamsistron** (1) [66401](https://platzi.com/comentario/706989/) 
y cual es el servidor Web que usa Flask en este caso?, es decir, por ejemplo con PHP uno puede usar Apache2, pero en este caso solo ejecu...

	* **Jorge Toledano** [66401] (1)

		Yo lo utilizo con Nginx, pero buscando en internet uno puede encontrar que también se puede configurar con Apache.

* **Mauricio Chávez Olea** (1) [55379](https://platzi.com/comentario/540704/) 
¿Soy yo o se parece mucho a Express.js? 😂

	* **Jairo  castañeda** [55379] (2)

		Cuando se usa express sin ningún generador de archivos si , la libertad de escribir la arquitectura en los dos es algo similar

## 0060. Debugging en Flask [18444](https://platzi.com/clases/1540-flask/18444-debugging-en-flask/)

### Descripción:


 **Debugging:** es el proceso de identificar y corregir errores de programación.

Para activar el _debug mode_ escribir lo siguiente en la consola:
``` 
    export FLASK_DEBUG=1
    echo $FLASK_DEBUG
    
```

### Comentarios:

* **Camilo Cáceres** (14) [540793](https://platzi.com/comentario/540793/) 

	Otra opción para correr el servidor en modo debug es poner estas lineas al final del archivo `main.py`:
	``` 
	    if __name__ == '__main__':
	        app.run(debug=True)
	    
	```
	
	y correr `main.py` desde la terminal:
	``` 
	    python main.py 
	    
	```

	* **Thelmo Jarrin** [540793] (3)

		Efectivamente,  
		podemos enviar las variables así:
		``` 
		    if __name__ == '__main__':
		        app.run(port = 5000, debug = True)
		    
		```

	* **Diego Casillas Duarte** [540793] (1)

		Me has salvado, Camilo, intenté con todos los comandos que encontré arriba hasta que por fin dí con este.  
		Supongo que algo ha de tener mi graciosita laptop que tengo del trabajo y por eso no corre como debe pero ya lo haré correr en la personal

* **Jo-Anna** (4) [792648](https://platzi.com/comentario/792648/) 

	Qué hacer si el servidor no se inicia
	``` 
	    flaks run
	    
	```
	
	o
	``` 
	    python -m flask run
	    
	```
	
	**Activar Modo debug**
	
	Para activar el modo debug simplemente hay que añadir la variable de entorno FLASK_ENV y asignarle el valor `development`.
	
	En Linux/Mac:
	``` 
	    export FLASK_ENV=“development”
	    
	```
	
	En Windows:
	``` 
	    set “FLASK_ENV=development”
	    
	```
	
	También puede controlar el modo de debug por separado del entorno exportando
	``` 
	    export FLASK_DEBUG=1
	    
	```

	* **Nicolás Mayorga Vargas** [792648] (1)

		Excelente aporte

* **Mon Avellaneda** (4) [541032](https://platzi.com/comentario/541032/) 

	Qué manera más clara y sencilla de explicar las cosas. Me encanta.
	
	Gracias Bernardo.
	
	Mon

* **Jose Gomez** (3) [562460](https://platzi.com/comentario/562460/) 

	Para crear la variable FLASK_DEBUG en PowerShell
	``` 
	    $env:FLASK_DEBUG=1
	    
	```

* **marttcode** (2) [1049454](https://platzi.com/comentario/1049454/) 

	Una vez que hayas levantado todo tu servidor a mano, posteriormente **lo puedes automatizar** así:
	``` 
	    #!/bin/bash
	    
	    source venv/bin/activate
	    
	    export FLASK_APP=main.py
	    export FLASK_DEBUG=1
	    
	    flask run
	    
	    
	```
	
	  1. Copia el código en un nuevo archivo dentro de la raíz de tu proyecto
	  2. Guarda el archivo con extension .sh
	  3. Ejecuta desde la consola con el comando: source file_name.sh
	  4. Listo!, Cada vez que quieras levantar el servidor de Flask solo haz el paso 3
	
	

	* **Royer Guerrero Pinilla** [1049454] (1)

		Super! se nota que aprendiste automatización de tareas con bash

* **Ricardo Lugo Recillas** (2) [655766](https://platzi.com/comentario/655766/) 

	* Esto es en windows  
	set FLASK_APP=myapp  
	set FLASK_APP=rest_registro_historico.py  
	set FLASK_DEBUG=1
	
	* Esto es en linux o mac  
	export FLASK_APP=myapp  
	export FLASK_APP=rest_registro_historico.py  
	export FLASK_DEBUG=1
	
	
	

* **Claudio_negra** (2) [541430](https://platzi.com/comentario/541430/) 

	En win se crea con --> set FLASK_DEBUG=1

* **innacroft** (1) [1074641](https://platzi.com/comentario/1074641/) 

	Cuando se activa el flag Debug , se detectan los cambios, es decir no es necesario reiniciar el servidor 😄

* **brandon james grimaldo moscote** (1) [1036355](https://platzi.com/comentario/1036355/) 

	en windows  
	set FLASK_DEBUG=1

* **Diego Casillas Duarte** (1) [1028632](https://platzi.com/comentario/1028632/) 

	Tengo un problema, no puedo añadir nada de variables en windows con SET, no funciona, intenté corriendo en la terminal `python main.py`  
	con estas configuraciones en el código:
	``` 
	    from flask import Flask 
	    app = Flask(__name__)
	    
	    if __name__ == "__main__":
	        app.run(debug=True)
	    @app.route('/')
	    defhello():
	        return"Hello world flask :) changing"
	    
	```
	
	Y todo bien, corre el server, pero a la hora de entrar a la URL dice que no encontró nada, sin embargo si le doy con el comando `flask run` en la terminal, sí que funciona ¿alguien sabe a qué se debe?

	* **Diego Alexander Forero Higuera (Platzi)** [1028632] (2)

		Hola. Mueve esta parte del código al final del archivo y va a funcionar.
		``` 
		    if __name__ == "__main__":
		        app.run(debug=True)
		    
		```
		
		El problema es que cuando corre la app la ruta no esta definida aún y por eso no la encuentra, si pones este código al final cuando lo ejecutes ya estará todo definido.

	* **Diego Casillas Duarte** [1028632] (1)

		Funcionó de perlas, gracias 😄

* **andresazuara98** (1) [1026355](https://platzi.com/comentario/1026355/) 

	I had problems with the environment variables, if you are using windows instead of use export, use set:
	``` 
	    set"FLASK_DEBUG=1"
	    
	```
	
	or add:
	``` 
	    if __name__ == "__main__":
	    	app.run(debug=True)
	    
	```

* **Celso Vicente Mercado Hurtado** (1) [683349](https://platzi.com/comentario/683349/) 

	Que hay con el error: No module named C:\www\env\Scripts\flask ???

	* **isaac152** [683349] (1)

		Hace poco tenía el mismo error a pesar de haber instalado Flask correctamente, solo se disparaba cuando trataba de entrar en el modo debugging.  
		Si ya probaste con set FLASK_DEBUG=1 y FLASK_ENV=development
		
		Trata de escribir esto en tu archivo py  
		if **name** == ‘ **main** ’:  
		app.run(debug=True)
		
		Y luego inicias el archivo. Te debería funcionar con eso último.

* **juan diego ramirez rojas** (1) [654016](https://platzi.com/comentario/654016/) 

	brutal!

* **Jorge** (1) [641730](https://platzi.com/comentario/641730/) 

	Me fuera gustado que el curso llevara algun ejemplo de conexion a una DB, ya que llevo semanas tratando de realizar trabajos con bases de datos como sqlite y mysql. si alguien ya lo ha hecho le agradeceria si pudiera ayudarme.
	
	gracias.

	* **Diego Alexander Forero Higuera (Platzi)** [641730] (3)

		No tienes que poner el mismo comentario en todas las clases, siempre la comunidad esta atenta para ayudar.

* **german-senyk** (1) [69633](https://platzi.com/comentario/760110/) 
Hola! Luego de declarar la variable con set FLASK_DEBUG=1 en entorno Windows no enciende el servidor cuando tipeo flask run, sale así y m...

	* **german-senyk** [69633] (2)

		ya esta! funciona con …  
		python -m flask run

## 0070. Request y Response [18445](https://platzi.com/clases/1540-flask/18445-request-y-response/)

### Descripción:


 **Logging:** es una grabación secuencial en un archivo o en una base de datos de todos los eventos que afectan a un proceso particular.

Se utiliza en muchos casos distintos, para guardar información sobre la actividad de sistemas variados.

Tal vez su uso más inmediato a nuestras actividades como desarrolladores web sería el _logging_ de accesos al servidor web, que analizado da información del tráfico de nuestro sitio. Cualquier servidor web dispone de _logs_ con los accesos, pero además, suelen disponer de otros _logs_ , por ejemplo, de errores.

Los sistemas operativos también suelen trabajar con _logs_ , por ejemplo para guardar incidencias, errores, accesos de usuarios, etc.

A través de el _logs_ se puede encontrar información para detectar posibles problemas en caso de que no funcione algún sistema como debiera o se haya producido una incidencia de seguridad.

### Comentarios:

* **Camilo Cáceres** (19) [540812](https://platzi.com/comentario/540812/) 

	Python 3.6 añadió una nueva forma de string format ([aquí pueden ver más](https://realpython.com/python-string-formatting/)).  
	Se llaman formatted string literals o f-strings y facilitan mucho el formato de strings con expresiones incluidas.  
	El return en forma de f-string se vería así:
	``` 
	    return f'Hello World Platzi, tu IP es{user_ip}'
	    
	```
	
	Dentro de los `{ }` pueden varias expresiones mientras las variables usadas estén dentro del scope de la función

	* **Camilo Varon** [540812] (2)

		de cierta forma es mas sencillo de usar, gracias por el aporte.

	* **predator0077** [540812] (1)

		Muchas Gracias justo lo que buscaba para hacerlo tipo `${ }` como en javascript.

	* **diegomedflo** [540812] (1)

		Es cierto, esta es la forma más facil de hacerlo, pero no la más segura cuando el proyecto este en desarrollo.

	* **Cesar AlbertoSosa Zuñiga** [540812] (1)

		Interesante aporte. gracias!

* **diegomedflo** (8) [954222](https://platzi.com/comentario/954222/) 

	No se si flask es más facil que django por mucho o este profesor explica mejor.

	* **sgomez2113** [954222] (1)

		Tienes razón Flask es un poco mas fácil que Django, pero aun así ambos profesores son excelentes, van a su propio ritmo.👌

	* **Enrique Sardon Manrique** [954222] (1)

		esqeu flask es una cosa muy simple, para hacer cosas muy rápidas y sin necesidad de tener toda la estructura que tienes en django, no necesitas saber del paradigma MVT o el ORM asi que es mas facil de aprender.
		
		Ahora si quieres hacer una aplicacion grande, pesada y con muchas transacciones, con código ordenado, legible, modular y separado por capas de abstraccion, mil veces se recomienda usar django, se te va a facilitar la vida en aplicaciones grandes

	* **innacroft** [954222] (1)

		Las dos cosas 😄

* **Luis Castañeira** (5) [624859](https://platzi.com/comentario/624859/) 

	Para los que trabajan en Windows, a los fines de no estar configurando los SET uno a uno cada vez, vayan a la carpeta y archivo SCRIPTS/activate.bat y agregenle al final del archivo los comandos anteriores. Con eso debe bastar para ejecutar el servidor con todo. En mi caso ya lo deje con [main.py](http://main.py) para si alguno quiere cambiarlo a futuro.
	
	`set FLASK_APP=main.py set FLASK_DEBUG=1 flask run`

* **Ionut** (2) [808903](https://platzi.com/comentario/808903/) 

	Averigué como hacerlo, no obstante parece que no es como en el video explicativo
	``` 
	    from flask import Flask, request, jsonify
	    
	    app = Flask(__name__)
	    
	    @app.route("/get_my_ip", methods=["GET"])
	    defget_my_ip():
	        return jsonify({'ip': request.remote_addr}), 200```
	    
	```

	* **juandavidcoloradoalvarez** [808903] (1)

		Aunque cabe resaltar que la solución que presentas con el [jsonify ](https://flask.palletsprojects.com/en/1.1.x/api/#flask.json.jsonify) sirve en el caso que desee realizar la respuesta en .json, es decir, con _Mimetype: application/json_. Pero la solución es totalmente validad si tu intensión es responder con _Mimetype: text/html_. Más información [aquí](https://flask.palletsprojects.com/en/1.1.x/api/#flask.json.jsonify).

## 0080. Ciclos de Request y Response [18446](https://platzi.com/clases/1540-flask/18446-ciclos-de-request-y-response/)

### Descripción:


 **Request-Response:** es uno de los métodos básicos que usan las computadoras para comunicarse entre sí, en el que la primera computadora envía una solicitud de algunos datos y la segunda responde a la solicitud.

Por lo general, hay una serie de intercambios de este tipo hasta que se envía el mensaje completo.

**Por ejemplo:** navegar por una página web es un ejemplo de comunicación de _request-response_.

_Request-response_ se puede ver como una llamada telefónica, en la que se llama a alguien y responde a la llamada; es decir hacemos una petición y recibimos una respuesta.

### Comentarios:

* **Alvaro Ruben Hurtado Maldonado** (3) [56131](https://platzi.com/comentario/549009/) 
Que ventajas tiene el utilizar redirect y cookies en la forma en la que se utilizó en esta clase?

	* **Camilo Varon** [56131] (2)

		Bueno el redirect mas q nada para ver las respuestas a nuestras peticiones o acciones en la web app, el tema de la cookie como dice al final del vídeo es aprender a crearlas y a obtenerlas una vez se guarden.

* **Darwin Jiménez Hernández** (2) [1011170](https://platzi.com/comentario/1011170/) 

	En mi caso a mí me aparece como None la IP

	* **Andres Rivera** [1011170] (1)

		déjanos ver el código.

* **Alvaro Ruben Hurtado Maldonado** (2) [549009](https://platzi.com/comentario/549009/) 

	Que ventajas tiene el utilizar redirect y cookies en la forma en la que se utilizó en esta clase?

	* **Camilo Varon** [549009] (2)

		Bueno el redirect mas q nada para ver las respuestas a nuestras peticiones o acciones en la web app, el tema de la cookie como dice al final del vídeo es aprender a crearlas y a obtenerlas una vez se guarden.

	* **Diego Alexander Forero Higuera (Platzi)** [549009] (5)

		Hola un caso de uso puede ser que almacenes en la cookie un token y verifiques si ese token es valido y lo redirecciones a tu aplicación o si no es valido que se vuelva a hacer login. Más adelante en el curso se verán temas de autenticación de usuarios.

* **marcelosanchez21** (1) [1051494](https://platzi.com/comentario/1051494/) 

	Les adjunto mi versión de código, la cual se ejecuta directamente desde el [main.py](http://main.py)
	``` 
	    from flask import Flask, request, make_response, redirect
	    
	    
	    app = Flask(__name__)
	    
	    @app.route('/')
	    defindex():
	    
	        user_ip = request.remote_addr
	        make = redirect('/hello')
	        response = make_response(make)
	        response.set_cookie('user_ip', user_ip)
	    
	        return response
	    
	    @app.route('/hello')
	    defhello():    
	    
	        mensaje = 'Hola Mundo!!'
	        user_ip = request.cookies.get('user_ip')
	    
	        return mensaje + user_ip
	    
	    if __name__ == "__main__":
	        
	        app.run(debug=True)
	    
	```

* **Jo-Anna** (1) [793646](https://platzi.com/comentario/793646/) 

	```
	    from flask import Flask, request, make_response, redirect
	    app = Flask(name)
	    
	    @app.route(’/’)
	    defindex():
	    user_ip = request.remote_addr
	    response = make_response(redirect(’/hello’))
	    response.set_cookie(‘user_ip’, user_ip)
	    
	    return response
	    
	    @app.route(’/hello’)
	    defhello_world():
	    #creamos nueva variable de la ip que detectamos en el browser
	    user_ip = request.cookies.get(‘user_ip’)
	    
	    return'Hello, Word, tu IP es {}'.format(user_ip)
	    
	    
	```

* **Fp_1000** (1) [60599](https://platzi.com/comentario/608032/) 
A mi no me funciono 😦

	* **Bernardo Cassina** [60599] (1)

		Qué parte no te funcionó?

# Uso de templates y archivos estáticos [3698]

## 0090. Templates con Jinja 2 [18447](https://platzi.com/clases/1540-flask/18447-templates-con-jinja-2/)

### Descripción:


### Links:

* [Welcome | Jinja2 (The Python Template Engine)](http://jinja.pocoo.org/)

### Comentarios:

* **Claudio_negra** (5) [541457](https://platzi.com/comentario/541457/) 

	La carpeta /templates debe ir dentro venv por si les da error de no encontrar el archivo.

	* **Camilo Varon** [541457] (10)

		la carpeta no debe ir dentro de venv, en si venv solo lleva los archivos de configuracion del entorno virtual, templates debe ir sobre la raiz de la carpeta platzi
		``` 
		    ├── main.py
		    ├── requirements.txt
		    ├── templates
		    │   └── hello.html
		    └── venv
		    
		```

	* **Carmen Sánchez Salgado** [541457] (1)

		Yo te recomiendo tener en carpetas separadas los entornos virtuales de las carpetas de tu aplicación o aplicaciones.
		
		Lo que hice fue poner en una carpeta todos mi entornos virtuales y en otra las carpetas de aplicaciones.
		
		├───apps  
		│ ├───app1  
		│ └───app2  
		└───virtualEnvironments  
		├───venv1  
		├───venv2  
		└───venv3
		
		Posteriormente activas el entorno virtual que necesites y corres tu aplicación.

* **Jo-Anna** (3) [794336](https://platzi.com/comentario/794336/) 

	 **Templates con Jinja 2**
	
	Un templeate -> archivo de HTML -> renderiza informacion: Estatica o DInamica -> por variables -> luego nos muestra en el navegador
	
	Para renderizar un template/plantilla creada con Jinja2 simplemente hay que hacer uso del método **render_template**.
	
	A este método debemos pasarle el nombre de nuestra template y las variables necesarias para su renderizado como parámetros clave-valor.
	
	Flask buscará las plantillas en el directorio **templates** de nuestro proyecto. En el sistema de ficheros, este directorio se debe encontrar en el mismo nivel en el que hayamos definido nuestra aplicación. En nuestro caso, la aplicación se encuentra en el fichero **[hello.py](http://hello.py)**.
	
	Es hora de crear este directorio y añadir las páginas hello.html, La estructura de nuestro proyecto quedaría del siguiente modo:
	``` 
	    Flask-proyect
	    |_hello.py
	    |_ /templeate
	        |__ hello.html
	    
	```
	
	Ejemplo archivo [hello.py](http://hello.py)
	``` 
	    from flask import Flask, request, make_response, redirect, render_template
	    
	    app = Flask(__name__)
	    
	    @app.route('/')
	    defindex():
	        user_ip = request.remote_addr
	        response = make_response(redirect('/hello_world'))
	        response.set_cookie('user_ip', user_ip)
	    
	        return response
	    
	    @app.route('/hello_world')
	    defhello_world():
	        #creamos nueva variable de la ip que detectamos en el browser
	        user_ip = request.cookies.get('user_ip')
	    
	        return render_template('hello_world.html', user_ip= user_ip)
	    # metodo es render_template con jinja2 y la variable es user_ip.
	    
	```

* **mcamelo** (3) [614215](https://platzi.com/comentario/614215/) 

	Para hacer que el import sea multi-linea:
	
	from flask import (Flask,  
	request,  
	make_response,  
	redirect,  
	render_template)

* **Jaskier28** (2) [732454](https://platzi.com/comentario/732454/) 

	jinja es un lenguaje de plantillas conocido como motor de plantillas  
	propio de python,  
	que permite insertar datos procesado y predeterminados dentro de documentos de texto
	
	actualmente la versión estable es la 2.10.1

* **Royer Guerrero Pinilla** (1) [1067794](https://platzi.com/comentario/1067794/) 

	No se a ustedes pero me parece que Flask es similar a Django

* **marcelosanchez21** (1) [1051515](https://platzi.com/comentario/1051515/) 

	Es importante que la carpeta se llame `templates`
	
	`main.py`
	``` 
	    from flask import Flask, request, make_response, redirect, render_template
	    
	    
	    app = Flask(__name__)
	    
	    @app.route('/')
	    defindex():
	    
	        user_ip = request.remote_addr
	        make = redirect('/hello')
	        response = make_response(make)
	        response.set_cookie('user_ip', user_ip)
	    
	        return response
	    
	    @app.route('/hello')
	    defhello():    
	    
	        mensaje = 'Hola Mundo!!'
	        user_ip = request.cookies.get('user_ip')
	    
	        return render_template('hello.html', user_ip=user_ip)
	    
	    if __name__ == "__main__":
	        
	        app.run(debug=True)
	    
	```
	
	ahora el archivo HTML, dentro de la carpeta `templates`
	
	`hello.html`
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	        <head>
	            <metacharset="UTF-8">
	            <metaname="viewport"content="width=device-width, initial-scale=1.0">
	            <title>Document</title>
	        </head>
	        
	        <body>
	            <h1>Hola Mundo, soy la ip: {{user_ip}}</h1>
	        </body>
	    </html>
	    
	```

## 0100. Estructuras de control [18448](https://platzi.com/clases/1540-flask/18448-estructuras-de-control/)

### Descripción:


**Iteración:** es la repetición de un segmento de código dentro de un programa de computadora. Puede usarse tanto como un término genérico (como sinónimo de repetición), así como para describir una forma específica de repetición con un estado mutable.

Un ejemplo de iteración sería el siguiente:
``` 
    {% for key, segment in segment_details.items() %}
            <tr>
                    <td>{{ key }}td>
                    <td>{{ segment }}td>
            tr>
    {% endfor %}  
    
```

En este ejemplo estamos iterando por cada _segment_details.items()_ para mostrar los campos en una tabla `{{ key }}` `| {{ segment }}` de esta forma dependiendo de cuantos _segment_details.items()_ haya se repetirá el código.

### Comentarios:

* **Mauricio Chávez Olea** (15) [541226](https://platzi.com/comentario/541226/) 
Creo que literalmente imprimiste "todo", y no era lo que querías. Para usar la variable todo en el for, debes poner {{ todo }}

	* **Claudio_negra** [541226] (9)

		tienes razón, sería algo así:
		
		<ul>  
		{% for todo in todos %}  
		<li>{{todo}}</li>  
		{% endfor %}  
		</ul>

	* **Mauricio Chávez Olea** [541226] (1)

		¡Justo eso!

	* **Arnold29** [541226] (1)

		también tenia esa duda gracias

* **andresazuara98** (5) [1041429](https://platzi.com/comentario/1041429/) 

	You forgot that when you use a variable into an html, you need to wrap the variable in {{ variableName }}, if you don’t wrap it, it just will display the name of the variable, that’s why the program is printing  
	-todo  
	-todo  
	-todo  
	instead of:  
	-TODO 1  
	-TODO 2  
	-TODO 3

	* **marcelosanchez21** [1041429] (1)

		todo -> {{ todo }}

* **Nicolás Mayorga Vargas** (5) [993879](https://platzi.com/comentario/993879/) 

	La verdad me está gustando mucho más Flask que Django. Evidentemente es por el tipo de pedagogía impartida.

	* **Enrique Sardon Manrique** [993879] (1)

		esque para aplicaciones ligeras flask es una maravilla pero un infierno cuando crecen, cuando hagas una app grande usa django… te lo recomiendo, flask es cuando no necesitas todo lo que ofrece django

* **Erik Taveras** (5) [967757](https://platzi.com/comentario/967757/) 

	Excelente clase, pero creo que te falto poner {{ }} en todo para que te imprimiera el listado, porque lo que lograste fue simplemente imprimir varias veces la palabra Todo.
	
	un saludo.

	* **Andrés David Ríos Ramirez** [967757] (6)

		Tal cual, eso faltó.
		
		Quedaría algo así:
		``` 
		    {% if user_ip %}
		        <h2>Hello World, tu Ip es {{user_ip}} </h2>
		    {% else %}
		        <ahref="{{ url_for('index') }}">Ir a inicio</a>
		    {% endif %}
		    <ul>
		        {% for todo in todos %}
		            <li>{{todo}}</li>
		        {% endfor %}
		    </ul>
		    
		    
		```

* **Carlos David Sanchez Moreno** (4) [542738](https://platzi.com/comentario/542738/) 

	Para pasar variables, podemos utilizar la funcion de python locals() que nos trae todas las variables de el contexto actual.
	``` 
	    Los asteriscos se deben a que locals() nos regresa un dict con las variables del contexto, pero render_template solo resive un argumento, asi que pasamos el diccionario con key yvaluesen forma de argumentos opcionales. 
	    
	    Esto es util cuando empezamos a tener muchos datos enel entorno.
	    
	    return render_template('hello.htmrno. l', **locals())```
	    
	```

	* **Alvaro Ruben Hurtado Maldonado** [542738] (3)

		Dato bastante útil, En caso que las variables estén definidas como globales (fuera de las funciones) se puede usar el equivalente **globals()
		``` 
		    return render_template('hello.html',**globals())
		    
		```

* **Jaskier28** (3) [732553](https://platzi.com/comentario/732553/) 

	url_for es propio de flask o del motor jinja2

	* **Kevin Javier Morales** [732553] (3)

		Esto es algo del motor de templates de jinja 😃

	* **Yelson Chevarrias Huaman** [732553] (1)

		No pertenece para nada a Jinja2, forma parte de los helpers de Flask.  
		puedes ver el código fuente en github:  
		<https://github.com/pallets/flask/blob/1234eb0f9ff997932cfb79835e101df7e49babb1/src/flask/helpers.py#L226>

* **Yelson Chevarrias Huaman** (2) [802227](https://platzi.com/comentario/802227/) 

	Existe una función nativa en python que retorna las variables del scope actual (contexto de ejecución) llamada “locals”, si se usa con el debido respeto y cuidado, resulta más como y limpio a la hora de pasar contexto al render_template, ya que con solo solo declarar la variable automáticamente entra en el contexto.
	``` 
	    defhome():
	        user_ip = request.cookies.get(const.COOKIE_NAME_USER_IP)
	        if user_ip isNone:
	            return make_response(redirect('/session', 302))
	        # locals() == {'user_ip': '127.0.0.1'}
	        some_var_name = ':v'
	        # locals() == {'user_ip': '127.0.0.1', 'some_var_name': ':v'}
	        other_var_name = ':d'
	        # locals() == {'user_ip': '127.0.0.1', 'some_var_name': ':v', 'other_va..'}
	        return render_template('home.html', **locals())
	    
	    
	    defhome_v2():
	        context = dict()
	        user_ip = request.cookies.get(const.COOKIE_NAME_USER_IP)
	        if user_ip isNone:
	            return make_response(redirect('/session', 302))
	        some_var_name = ':v'
	        other_var_name = ':d'
	    
	        context['user_ip'] = user_ip
	        context['some_var_name'] = some_var_name
	        context['other_var_name'] = other_var_name
	        return render_template('home.html', **context)
	    
	```

* **mcamelo** (2) [614234](https://platzi.com/comentario/614234/) 

	El concepto de “Expandir el diccionario” es un Kwargs en python.  
	<http://book.pythontips.com/en/latest/args_and_kwargs.html>

* **marcelosanchez21** (1) [1051550](https://platzi.com/comentario/1051550/) 

	A las personas que en vez de salir el mensaje
	
	* TODO 1
	* TODO 2
	* TODO 3
	
	
	
	eso es por que en vez de poner `<li> {{todo}} </li>` han puesto `<li> todo </li>`
	
	lo único que hace ese `for` es imprimir en pantalla la CADENA `todo`, en vez de imprimir el iterador `todo`
	
	`main.py`
	``` 
	    from flask import Flask, request, make_response, redirect, render_template
	    
	    
	    app = Flask(__name__)
	    
	    todos = ['TODO 1', 'TODO 2', 'TODO 3']
	    
	    @app.route('/')
	    defindex():
	    
	        user_ip = request.remote_addr
	        make = redirect('/hello')
	        response = make_response(make)
	        response.set_cookie('user_ip', user_ip)
	    
	        return response
	    
	    @app.route('/hello')
	    defhello():    
	        
	        user_ip = request.cookies.get('user_ip')
	        render = render_template(
	            'hello.html', 
	            user_ip=user_ip, 
	            todos=todos
	        )
	    
	        return render
	    
	    if __name__ == "__main__":
	        
	        app.run(debug=True)
	    
	```
	
	`hello.html`
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	        <head>
	            <metacharset="UTF-8">
	            <metaname="viewport"content="width=device-width, initial-scale=1.0">
	            <title>Document</title>
	        </head>
	    
	        <body>
	            {% if user_ip %}
	                <h1>Hola Mundo, soy la ip: {{user_ip}}</h1>
	            {% else %}
	                <ahref=" {{ url_for('index') }} "> Ir al inicio de la pagina </a>
	            {% endif %}
	    
	            <ul>
	                {% for todo in todos %}
	                    <li>{{todo}}</li>
	                {% endfor %}
	            </ul>       
	    
	        </body>
	    </html>
	    
	```

* **brandon james grimaldo moscote** (1) [1036461](https://platzi.com/comentario/1036461/) 
	
	![wwqwq.JPG](https://static.platzi.com/media/user_upload/wwqwq-e01ee1e7-6f5b-44f6-a8d4-ec617d57eaa9.jpg)

* **diegomedflo** (1) [1013030](https://platzi.com/comentario/1013030/) 

	Dentro de un context tambien s epueden pasar listas o tuplas? O solo una llave puede contener una variable?

* **Juan Daniel Gualtero Diaz** (1) [829485](https://platzi.com/comentario/829485/) 

	Buenas las facilidades que tiene Python para desarrollar

* **Hafnio** (1) [778300](https://platzi.com/comentario/778300/) 

	Lo de poder expandir un diccionario en Python como si fuera un kwarg es simplemente magico.

* **jhoselynanaissotelolapa** (1) [675228](https://platzi.com/comentario/675228/) 

	creo que te saltas mucho la teoria y lo haces de frente en mi opinion tal vez seria mejor explicar cada cosa a detalle y mas pausado ,solo es un consejo igual gracias por el curso!!

	* **Carmen Sánchez Salgado** [675228] (1)

		Estoy totalmente de acuerdo con tu comentario.  
		En mi opinión, este curso de Flask está orientado a todos aquellos que ya conocen y programan en Django.

	* **Hafnio** [675228] (1)

		Eso es porque en la ruta de la carrera te recomiendan hacer el curso de Django primero y luego este. Cuando tengo alguna duda voy a la documentacion del framework si quiero entender algo en especifico.

* **diegomedflo** (1) [80199](https://platzi.com/comentario/954323/) 
¿Porqué en el for loop, no puso ‘todo’, tengo de llaves, como se hace con cada variable?

	* **estebansolorzano** [80199] (3)

		En el siguiente video se da cuenta del error.

## 0110. Herencia de templates [18449](https://platzi.com/clases/1540-flask/18449-herencia-de-templates/)

### Descripción:


 **Macro:** son un conjunto de comandos que se invocan con una palabra clave, opcionalmente seguidas de parámetros que se utilizan como código literal. Los Macros son manejados por el compilador y no por el ejecutable compilado.

Los macros facilitan la actualización y mantenimiento de las aplicaciones debido a que su re-utilización minimiza la cantidad de código escrito necesario para escribir un programa.

En este ejemplo nuestra _macro_ se vería de la siguiente manera:
``` 
    {% macro nav_link(endpoint, text) %}
        {% if request.endpoint.endswith(endpoint) %}
            <li class="active"><a href="{{ url_for(endpoint) }}">{{text}}</a></li>
        {% else %}
            <li><a href="{{ url_for(endpoint) }}">{{text}}</a></li>
        {% endif %}
    {% endmacro %}
    
```

Un ejemplo de uso de macros en Flask:
``` 
    {% from "macros.html" import nav_link with context %}
    <!DOCTYPE html>
    <html lang="en">
        <head>
        {% block head %}
            <title>My application</title>
        {% endblock %}
        </head>
        <body>
            <ul class="nav-list">
                {{ nav_link('home', 'Home') }}
                {{ nav_link('about', 'About') }}
                {{ nav_link('contact', 'Get in touch') }}
            </ul>
        {% block body %}
        {% endblock %}
        </body>
    </html>
    
```

Como podemos observar en la primera línea estamos llamando a _macros.html_ que contiene todos nuestros _macros_ , pero queremos uno en específico así que escribimos `import nav_link` para traer el _macro_ deseado y lo renderizamos de esta manera en nuestro menú `{{ nav_link('home', 'Home') }}`.

### Comentarios:

* **Jean Carlos Nuñez Hernandez** (5) [561012](https://platzi.com/comentario/561012/) 

	Herencis de Template: La parte más poderosa de Jinja es la herencia de plantillas. La herencia de plantillas le permite crear una plantilla de “esqueleto” de base que contiene todos los elementos comunes de su sitio y define los bloques que las plantillas secundarias pueden anular.

* **Jaskier28** (4) [725241](https://platzi.com/comentario/725241/) 

	explicas bien pero te vas directamente a la practica con un poco de teoría previa se entendería mas rápido y mejor

	* **Carmen Sánchez Salgado** [725241] (2)

		Coincido totalmente con tu comentario.

	* **Jaskier28** [725241] (3)

		eessm01 te recomiendo que leas la documentacion oficial de flask  
		y jinja2 ambas estan muy completas, haslo y te convertiras en un pro

	* **Jaskier28** [725241] (1)

		eessm01 te recomiendo que leas la documentacion oficial de flask  
		y jinja2 ambas estan muy completas, haslo y te convertiras en un pro

	* **diegomedflo** [725241] (2)

		Es cierto que en la documentación esta todo, pero por algo pagamos Platzi, para aprender lo mismo. Sino no pagariamos Platzi y leeriamos al documentación.

	* **william andres rodriguez borja** [725241] (3)

		Si seguimos las rutas propuestas por platzi no te sientes perdido.  
		a mi tambien me paso con otro curso y aprendi ahora lo comparto mira la ruta propuesta de python
		
		![Screenshot from 2020-01-30 23-26-56.png](https://static.platzi.com/media/user_upload/Screenshot%20from%202020-01-30%2023-26-56-945eb0b4-693c-4f9b-b563-16c6745add0f.jpg)

	* **Nicolás Mayorga Vargas** [725241] (1)

		Te recomiendo sigas la ruta de aprendizaje o mismo vayas a la documentación. Esto es pura programación orientada a objetos y mismo Django te las bases de esto.
		
		Pero así mismo. debes seguir la ruta de aprendizaje.

* **brandon james grimaldo moscote** (2) [1036483](https://platzi.com/comentario/1036483/) 

	listo sin errores , cosa extraña por que siempre tengo errores :'c

	* **Royer Guerrero Pinilla** [1036483] (1)

		Eso solo significa que has mejorado al principio me pasaba lo mismo lo peor es que no encontraba el error en mi código con el tiempo aprendí que leer lo soluciona todo ademas creo que a nosotros los programadores un ojo se convierte en debugger y encuentra los errores facilmente, Suerte!

* **diegomedflo** (2) [957433](https://platzi.com/comentario/957433/) 

	Yo uso ‘include’, cual es la diferencia entre ambos?

* **Marco Antonio González Arellano** (2) [862715](https://platzi.com/comentario/862715/) 

	Un typo me llevó ya un buen rato, pero me forzó también a entender más la lógica de cómo se va armando la aplicación.

	* **fernandajofili** [862715] (2)

		No hay mal que por bien no venga! Comparte con nosotros el typo, para que no hagamos lo mismo.

* **Royer Guerrero Pinilla** (1) [1068138](https://platzi.com/comentario/1068138/) 

	Si usan Vs code les recomiendo las extencion Jinja para que les coloree los tags de jinja

## 0120. Include y links [18450](https://platzi.com/clases/1540-flask/18450-include-y-links/)

### Descripción:


### Comentarios:

* **Nicolás Mayorga Vargas** (3) [994947](https://platzi.com/comentario/994947/) 

	Me parece excelente pedagogía. Se basa mucho más en la práctica y tenemos la documentación como soporte en caso de querer ir más allá.

	* **JORGE ANDRES DIAZ CELIS** [994947] (1)

		Totalmente de acuerdo, la velocidad en la que avanzamos es superior a otras pedagogías que enfocan más en la teoría, obvaiment todo depende de tu nivel previo como estudiante.

* **Jaskier28** (2) [732621](https://platzi.com/comentario/732621/) 

	pasas de mucha teoría que si la explicaras facilitaría mucho entender y aprender mas rápido

	* **Zenndler** [732621] (3)

		Para reforzar y completar la teoría te recomiendo la [documentación oficial](https://jinja.palletsprojects.com/en/2.10.x/)

	* **Marco Antonio González Arellano** [732621] (4)

		En mi caso es lo contrario, necesito una introducción práctica y después la lectura de la teoría me resulta más digerible.  
		El curso me parece muy bueno.  
		Saludos.

	* **j0e** [732621] (1)

		A mí también me parece excelente la manera en que explica, hasta el momento no he tenido problemas con nada desde que empezó el curso, si quieres profundizar algo que no entendiste yo también te recomiendo que leas la documentación, está muy fácil de entender también.

* **Ionut** (2) [72522](https://platzi.com/comentario/817668/) 
Buenas, continuando con el curso, no puedo ejecutar el main.py para ver poco a poco los resultados. Cuando a...

	* **Israel Yance** [72522] (1)

		A mí me pasó lo mismo.
		
		Se tiene que setear la variable de entorno en la terminal:  
		`export FLASK_APP=main.py`

* **marcelosanchez21** (1) [1052596](https://platzi.com/comentario/1052596/) 

	`main.py`
	``` 
	    from flask import Flask, request, make_response, redirect, render_template
	    
	    
	    app = Flask(__name__)
	    
	    todos = ['Crompar Cafe', 'Entregar Informe', 'Salir a caminar']
	    
	    @app.route('/')
	    defindex():
	    
	        user_ip = request.remote_addr
	        make = redirect('/hello')
	        response = make_response(make)
	        response.set_cookie('user_ip', user_ip)
	    
	        return response
	    
	    @app.route('/hello')
	    defhello():    
	        
	        user_ip = request.cookies.get('user_ip')
	        render = render_template(
	            'hello.html', 
	            user_ip=user_ip, 
	            todos=todos
	        )
	    
	        return render
	    
	    if __name__ == "__main__":
	        
	        app.run(debug=True)
	    
	```

* **marcelosanchez21** (1) [1052594](https://platzi.com/comentario/1052594/) 

	`hello.html`
	``` 
	    {% extends 'base.html' %}
	    {% import 'macros.html' as macros %}
	    
	    {% block title %} 
	    
	        {{ super() }}
	        Bienvenido
	    
	    {% endblock %}
	    
	    {% block content %}
	    
	        {% if user_ip %}
	            <h1>Hola Mundo, soy la ip: {{user_ip}}</h1>
	        {% else %}
	            <ahref=" {{ url_for('index') }} "> Ir al inicio de la pagina </a>
	        {% endif %}
	    
	        <ul>
	        {% for todo in todos %}
	            {{macros.render_todo(todo)}}
	        {% endfor %}
	        </ul>    
	    
	    {% endblock %}
	    
	```

* **marcelosanchez21** (1) [1052593](https://platzi.com/comentario/1052593/) 

	`base.html`
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	        <head>
	            <metacharset="UTF-8">
	            <metaname="viewport"content="width=device-width, initial-scale=1.0">
	            <title> 
	                {% block title %} 
	                    Flask Platzi | 
	                {% endblock %}
	            </title>
	        </head>
	    
	        <body>
	            <header>
	                {% include 'navbar.html' %}
	            </header>
	            {% block content %}            
	            {% endblock %}
	        </body>
	    </html>
	    
	```

* **marcelosanchez21** (1) [1052592](https://platzi.com/comentario/1052592/) 

	`macros.html`
	``` 
	    {% macro render_todo(todo) %}
	        <li>Descripcion: {{todo}}</li>
	    {% endmacro %}
	    
	```

* **marcelosanchez21** (1) [1052591](https://platzi.com/comentario/1052591/) 

	`navbar.html`
	``` 
	    <nav>
	        <ul>
	            <li><ahref=" {{ url_for('index') }} ">Ir a inicio</a></li>
	            <li><ahref="https://platzi.com/"target=" blank">Platzi</a></li>
	        </ul>
	    </nav>
	    
	    
	```

* **Emmanuel Sosa Reyes** (1) [1044848](https://platzi.com/comentario/1044848/) 

	Soy de seguridad, pero siempre me ha llamado la atención el desarrollo web. Tome el curso de Bootstrap el cual amé, Javascript, etc. Ahora, Python es muy importante para nosotros los Pentesters. Quiero ver como opera Python en el entorno web, y hasta ahora muy interesante. Espero se le de más estática a la aplicación en las siguientes clases.

* **Andres Rivera** (1) [1024055](https://platzi.com/comentario/1024055/) 

	pregunta ¿este html se renderea en el servidor o en el cliente?

	* **Diego Alexander Forero Higuera (Platzi)** [1024055] (2)

		Se crea en el servidor, esto es server side render.

* **sebastian-castro-torres** (1) [1007110](https://platzi.com/comentario/1007110/) 

	Excelente, clase

## 0130. Uso de archivos estáticos imágenes [18451](https://platzi.com/clases/1540-flask/18451-uso-de-archivos-estaticos-imagenes/)

### Descripción:


### Comentarios:

* **diegomedflo** (3) [80370](https://platzi.com/comentario/957603/) 
¿Cuál es la diferencia técnica de usar ‘url for’ y ‘src’?

* **raulfbgomez** (2) [1004660](https://platzi.com/comentario/1004660/) 

	A mi me pasaba mucho que siempre Chrome ‘cacheaba’ las imágenes por lo que tenia que ponerles un hash para que cada que cambiaba una imagen se mostrara correctamente y no decirles a mis usuarios que pulsaran ctrl + F5.

	* **Sara Galván Ortega** [1004660] (1)

		A mí también me pasó…

* **diegomedflo** (2) [957701](https://platzi.com/comentario/957701/) 

	Yo estoy usando esta forma, ya que jalé el mismo código de mi proyecto en PHP y funciona igual. ¿En qué situaciones deberia usar ‘url_for’?
	``` 
	    <link rel="stylesheet"type="text/css" href="static/css/css/bootstrap.min.css">
	    <link rel="stylesheet"type="text/css" href="static/css/main.css">```
	    
	```

	* **Carlos Cuevas Sosa** [957701] (1)

		No es buena idea poner de manera directa las rutas hacia los archivos, así como en general cualquier constante, por si éstos llegan a cambiar.  
		Según la documentación de Flask, si la función url_for no encuentra la ruta especificada, se produce un error y ya no carga la página.

* **Carmen Sánchez Salgado** (2) [751131](https://platzi.com/comentario/751131/) 

	Un resumen sobre recursos estáticos
	
	* Static files go in the static/ directory.
	
	* Separate third-party libraries from your own static files.
	
	* Specify the location of your favicon in your templates.
	
	* Use Flask-Assets to insert static files in your templates.
	
	* Flask-Assets can compile, combine and compress your static files.
	
	
	
	
	Fuente:  
	<http://exploreflask.com/en/latest/static.html>

* **Yelson Chevarrias Huaman** (1) [802275](https://platzi.com/comentario/802275/) 

	Flask permite extenderse en funciones del template:
	``` 
	    from flask import Flask
	    from flask.helpers import url_for
	    app = Flask(__name__)
	    
	    
	    defstatic(*args, **kwargs):
	        if len(args) == 1:
	            return url_for('static', filename=args[0], **kwargs)
	        return url_for('static', **kwargs)
	    
	    
	    # {{ static('style.css') }} sería igual a:
	    # {{ url_for('static', filename = 'style.css') }} 
	    app.add_template_global(
	        static, 'static',
	    )
	    
	    # {{ potenciador(5) }} => 25 
	    # {{ potenciador(10) }} => 100 ... 
	    app.add_template_global(
	        lambda x: x**2, 'potenciador',
	    )
	    
	    # y así para n casos de uso....
	    
	```

* **gildder guerrero guerrero** (1) [644191](https://platzi.com/comentario/644191/) 

	Para usar el archivo CSS y JavaScript estático en la plantilla index.html, necesitamos usar el nombre del punto final ‘estático’ especial:
	``` 
	    {{ url_for('static', filename = 'style.css') }}
	    
	```
	
	Entonces, puede contener:
	``` 
	    <linkhref="{{ url_for(‘static’, filename = ‘style.css’) }}"rel=“stylesheet”>
	    
	    <scriptsrc="{{ url_for(‘static’, filename = ‘script.js’) }}"></script>
	    
	```

* **gildder guerrero guerrero** (1) [644172](https://platzi.com/comentario/644172/) 

	Las aplicaciones web a menudo requieren archivos estáticos como archivos CSS o JavaScript.

* **Jean Carlos Nuñez Hernandez** (1) [576225](https://platzi.com/comentario/576225/) 

	Static folder para manejar archivos estaticos

## 0140. Configurar páginas de error [18452](https://platzi.com/clases/1540-flask/18452-configurar-paginas-de-error/)

### Descripción:


### Códigos de error:

**100:** no son errores sino mensajes informativos. Como usuario nunca los verás, sino que entre bambalinas indica que la petición se ha recibido y se continúa el proceso.

**200:** estos códigos también indican que todo ha ido correctamente. La petición se ha recibido, se ha procesado y se ha devuelto satisfactoriamente. Por tanto, nunca los verás en tu navegador, pues significan que todo ha ido bien.

**300:** están relacionados con redirecciones. Los servidores usan estos códigos para indicar al navegador que la página o recurso que han pedido se ha movido de sitio. Como usuario, no verás estos códigos, aunque gracias a ellos una página te podría redirigir automáticamente a otra.

**400:** corresponden a errores del cliente y con frecuencia sí los verás. Es el caso del conocido error 404, que aparece cuando la página que has intentado buscar no existe. Es, por tanto, un error del cliente (la dirección web estaba mal).

**500:** mientras que los códigos de estado 400 implican errores por parte del cliente (es decir, de parte tuya, tu navegador o tu conexión), los errores 500 son errores desde la parte del servidor. Es posible que el servidor tenga algún problema temporal y no hay mucho que puedas hacer salvo probar de nuevo más tarde.

### Comentarios:

* **Mauricio Chávez Olea** (6) [541815](https://platzi.com/comentario/541815/) 

	El código en Python lo haría algo así:
	``` 
	    @app.errorhandler(500)
	    definternal_server_error(error):
	      return render_template('500.html')
	    
	```
	
	Y el HTML me quedaría algo así:
	``` 
	    {% extends 'base.html' %}
	    
	    {% block title %}
	    {{ super() }}
	    Internal Server Error
	    {% endblock %}
	    
	    {% block content %}
	    <h1>Lo sentimos</h1>
	    <p>Ocurrió un error, estamos trabajando en ello</p>
	    {% endblock %}
	    
	```

* **Fernando Chavez** (5) [625156](https://platzi.com/comentario/625156/) 

	Y este decorador puede recibir no solo el número de un error, sino propiamente un error (pudiendo así definir nuestros propios errores) o también podríamos crear una función que maneje cualquier tipo de error de esta manera:
	``` 
	    @app.errorhandler(Exception)
	    deferror_handler(e):
	    	return'Error!!!'
	    
	```

* **xoyoc** (4) [553617](https://platzi.com/comentario/553617/) 

	En el archivo [main.py](http://main.py)
	``` 
	    @app.errorhandler(500)
	    defnot_found(error):
	        return render_template('500.html',error=error)
	    
	```

	* **Andrés Felipe Martínez Salazar** [553617] (4)

		Un nombre mas apropiado para la función seria `server_error`, ya que los códigos de estado 5xx son para errores del servidor, específicamente el 500 es “Internal Server Error”

* **Diego Casillas Duarte** (2) [1029273](https://platzi.com/comentario/1029273/) 

	La verdad es que preferí ir un poquitito más allá y hacer esto en el HTML, tomé un concepto de Amazon de poner perritos cuando algo pasa y lo hice así:
	``` 
	    <!DOCTYPE html> 
	    <htmllang "en">
	    <head>
	        <metacharset = "UTFF-8">
	        <title>
	        {% block title %}Learning Flask | {% endblock %}
	        </title>
	        <linkrel = "stylesheet" href = "{{url_for('static', filename = 'css/main.css')}}">
	    </head>
	    <body>
	        {% block content%}
	        <imgsrc = "{{url_for('static', filename='images/500e.png')}}" alt = "doggie">
	        <h1> Oh hotcakes, this was a mistake from our side, we're working on it</h1>
	        <p>{{ error }}</p>
	        {% endblock %}
	    </body>
	    </html>
	    
	```
	
	Notarán que no utilicé el template base.html porque no me gustó que siguiera mostrando los links ni las imágenes que ya tenía. Así que aquí les dejo mi html del 500

* **José Padrón** (2) [877872](https://platzi.com/comentario/877872/) 

	Mi código en python:
	``` 
	    @app.errorhandler(500)
	    definternal_error(error):
	        return render_template('500.html', error=error)
	    
	```
	
	El código de HTML:
	``` 
	    {% extends 'base.html' %}
	    {% import 'macros.html' as macros %}
	    
	    {% block title %}
	        {{ super() }}
	        internal error 500
	    {% endblock %}
	    
	    {% block content %}
	    
	        <h1>Lo sentimos hay problemas en la conexion</h1>
	        <h2>500</h2>
	    
	    {% endblock %}
	    
	```

* **Ricardo José Galarza Palacios** (2) [692120](https://platzi.com/comentario/692120/) 

	@app.errorhandler(500)  
	def errorServer(error):  
	return render_template(‘500.html’)

* **osmandi (Platzi)** (2) [684017](https://platzi.com/comentario/684017/) 

	Así intercepto el Error 500:
	``` 
	    @app.errorhandler(500)
	    definternal_error(error):
	       return"Error 500 {}".format(error)
	    
	```
	
	Así emulo un error 500
	``` 
	    @app.route('/error')
	    deferror_server():
	    	return1 / 0
	    
	```
	
	En consola retiro el modo debug y vuelvo a correr el servidor:
	``` 
	    export FLASK_DEBUG=0
	    flask run
	    
	```

* **Royer Guerrero Pinilla** (1) [1069610](https://platzi.com/comentario/1069610/) 

	⚙ **Logic**
	``` 
	    @app.errorhandler(500)
	    definternal_server_error(error):
	        return render_template('500.html', error=error)
	    
	```
	
	🎨 **Html**
	``` 
	    {% extends 'base.html' %}
	    
	    {% block title %}{{super()}} Lo sentimos {% endblock %}
	    
	    {% block content %}
	      <h1>😢 Estamos trabajando para solucionar este error</h1>
	      {{ error }}
	    {% endblock %}
	    
	```

* **Moshe Cotacallapa** (1) [1066654](https://platzi.com/comentario/1066654/) 

	[main.py](http://main.py)
	``` 
	    @app.errorhandler(500)
	    defserver_error(error):
	        return render_template('500.html',error=error)
	    
	```
	
	500.html
	``` 
	    {% extends 'base.html' %}
	    
	    {% block title %} 
	        {{ super() }}
	        Server error
	    {% endblock %}
	    
	    {% block header %}
	        <h1>Error 500 : Internal Server Error</h1>
	    {% endblock %}
	    
	    {% block content %}
	    
	        <h1>Sorry, we are already working on it.</h1>
	        <p>{{ error }}</p>
	    
	    {% endblock %}
	    
	```

* **Andrés David Ríos Ramirez** (1) [1024800](https://platzi.com/comentario/1024800/) 

	El código quedaría así:
	
	**[app.py](http://app.py)**
	``` 
	    @app.errorhandler(500)
	    defnot_found_500(error):
	        return render_template('500.html', error=error)
	    
	```
	
	**500.html**
	``` 
	    {% extends 'base.html' %}
	    {% import 'macros.html' as macros %}
	    
	    {% block title %}
	        {{ super() }}
	        500
	    {% endblock %}
	    
	    {% block content %}
	    <h1>Lo sentimos hubo un problema con el servidor :(,<br>
	        estamos trabajando para resolverlo.<br>
	        Intenta en unos intantes.
	    </h1>
	    <p>{{ error }}</p>
	    {%endblock%}
	    
	```

* **Carmen Sánchez Salgado** (1) [751147](https://platzi.com/comentario/751147/) 

	Renderizar un HTML para los errores 5XX como los de Youtube  
	![](https://qph.fs.quoracdn.net/main-qimg-d28e827803517f0d9c72dc30d6b3e187)

* **pabloCortes127** (1) [85050](https://platzi.com/comentario/1065037/) 
Hola! Uso ubuntu 18.04 y por un motivo he tenido que reinstalarlo pero ahora al intentar acceder al servidor desde el navegador me da el ...

	* **pabloCortes127** [85050] (1)

		ya lo resolví

* **jcavelez** (1) [83985](https://platzi.com/comentario/1039835/) 
¿Cómo simulo en mi VENV un error 500?

	* **Diego Alexander Forero Higuera (Platzi)** [83985] (1)

		Puedes generar una url donde retorne un error por ejemplo `1/0` que es un divizion Error

* **PATRICIO MORALES FARIÑA** (0) [83891](https://platzi.com/comentario/1037721/) 
No me resulta el manejo del error 404 en Flask: ![](

* **PATRICIO MORALES FARIÑA** (0) [83890](https://platzi.com/comentario/1037717/) 
No me resulta el manejo del error 404 en Flask: 404.html: {% extends ‘base.html’ %} {% block title %} {{ super()}} 404 {% endblock %} {% ...

	* **Diego Alexander Forero Higuera (Platzi)** [83890] (1)

		Qué error te da, no renderiza la pagina de 404?

# Extensiones de Flask [3699]

## 0150. Flask Bootstrap [18453](https://platzi.com/clases/1540-flask/18453-flask-bootstrap/)

### Descripción:


 **Framework:** es un conjunto estandarizado de conceptos, prácticas y criterios para enfocar un tipo de problemática particular que sirve como referencia, para enfrentar y resolver nuevos problemas de índole similar.

### Links:

* [Flask-Bootstrap — Flask-Bootstrap 3.3.7.1 documentation](https://pythonhosted.org/Flask-Bootstrap/)

* [ Bootstrap · The world's most popular mobile-first and responsive front-end framework. ](https://getbootstrap.com/docs/3.3/)

### Comentarios:

* **danielsanz (Platzi)** (13) [535654](https://platzi.com/comentario/535654/) 
	
	![Bloques-Bootstrap.png](https://static.platzi.com/media/user_upload/Bloques-Bootstrap-c4bb85f6-a4a4-4132-9b48-3471c101ddc3.jpg)

* **Nicolas Agustin Juanico** (5) [552828](https://platzi.com/comentario/552828/) 

	Para los que esten viendo 4/4/19, se puede bajar bootstrap4 ya a flask. Dato no menor, es la version 4.0.0, a la fecha de hoy ya esta la 4.3.  
	Para mayor comodidad, se puede recurrir a crear uno mismo el template de Bootstrap, aparte en un “.html” e incorporarlo al "base.html"  
	De este modo podes;  
	Incluir los archivos descargados de manera loca.  
	Incluir el CMD  
	Distintos modos de mantener todo actualizado a la fecha, con pocos ajustes desde uno mismo.

	* **Francisco Javier Antúnez Durán** [552828] (1)

		¿Como así?, ¿podrías explicarlo mas detallado por favor?.  
		Gracias de antemano.

	* **diegomedflo** [552828] (1)

		Para llamarlos de forma local, sería igual que en PHP, con link?

* **hesau2001** (4) [957858](https://platzi.com/comentario/957858/) 

	Bueno atualmente ya es soprtado Bootstrap4 solo que lo tienes que especificar a la hora de hacer pip install
	``` 
	    pip install Flask-Bootstrap4
	    
	```
	
	Pueden consultarlo [aquì ](https://pypi.org/project/Flask-Bootstrap4/)

	* **Andrés David Ríos Ramirez** [957858] (1)

		**Nota**  
		Si instalas `Flask-Bootstrap4` el código que coloca el profesor en el video no funciona, si alguien puede agregar como sería el código para Bootstrap4 se lo agradecería.

* **PATRICIO MORALES FARIÑA** (2) [1038239](https://platzi.com/comentario/1038239/) 

	No me funciona, aparece :  
	jinja2.exceptions.TemplateNotFound  
	jinja2.exceptions.TemplateNotFound: bootstrap/base.html
	
	No encuentra el template base.html a pesar de crear la barpeta y el archivo. No sé si se instaló bootstrap de forma adecuada . Uso Ubuntu.

	* **Diego Alexander Forero Higuera (Platzi)** [1038239] (1)

		Puedes compartir el traceback completo del error.

* **Diego Casillas Duarte** (2) [1029286](https://platzi.com/comentario/1029286/) 

	Utilizando el curso de la terminal en linux aproveché para pasarles el comando para tirar todo lo que tenemos instalado en el ambiente virtual al requirements.txt, de esta manera lo único que hay que hacer es correr el siguiente comando:  
	`pip freeze > requirements.txt` y automáticamente todo lo que tenga el ambiente en ese momento se va a volcar a requirements.txt, quedando algo más o menos así:
	``` 
	    astroid==2.3.3
	    click==7.1.1
	    colorama==0.4.3
	    dominate==2.5.1
	    Flask==1.1.1
	    Flask-Bootstrap==3.3.7.1
	    isort==4.3.21
	    itsdangerous==1.1.0
	    Jinja2==2.11.1
	    lazy-object-proxy==1.4.3
	    MarkupSafe==1.1.1
	    mccabe==0.6.1
	    pylint==2.4.4
	    six==1.14.0
	    typed-ast==1.4.1
	    visitor==0.1.3
	    Werkzeug==1.0.0
	    wrapt==1.11.2
	    
	```
	
	De nada 😃

* **Royer Guerrero Pinilla** (1) [1069780](https://platzi.com/comentario/1069780/) 

	No me funciona flask_boostrap![Imagen 5.png](https://static.platzi.com/media/user_upload/Imagen%205-4d6e9e60-e133-4e06-acbe-d1212053f8e5.jpg)

* **Nietsnie Alberto Perez cruz** (1) [1029456](https://platzi.com/comentario/1029456/) 

	creación de menú en flask con bootstrap 4
	``` 
	    <divclass="navbar navbar-expand-lg navbar-dark bg-dark"role="navigation">
	            <divclass="navbar-brand"href="{{ url_for('index') }}">
	                <buttonclass="navbar-toggler"type="button"data-toggle="collapse"data-target="#navbarNavAltMarkup"aria-controls="navbarNavAltMarkup"aria-expanded="false"aria-label="Toggle navigation">
	                    <spanclass="navbar-toggler-icon"></span>
	                  </button>
	              
	                <divclass="collapse navbar-collapse"id="navbarNavAltMarkup">
	                    <divclass="navbar-nav">
	                        <aclass="navbar-brand" >
	                            <imgsrc="{{ url_for('static', filename='images/platzi.png') }}"
	                                 style="max-width: 48px"
	                                 alt="Platzi logo">
	                        </a>
	                      <aclass="nav-item nav-link active"href="{{ url_for('index') }}">Inicio<spanclass="sr-only">(current)</span></a>
	                      <aclass="nav-item nav-link"href="https://platzi.com"target="_blank">Platzi</a>
	                    </div>
	                  </div>
	            </div>
	    </div>
	    
	```

* **diegomedflo** (1) [957704](https://platzi.com/comentario/957704/) 

	¿Y si yo descargo los archivos de la página de Bootstrap y luego los linqueo igual que con main.css?

	* **estebansolorzano** [957704] (1)

		Igual puede funcionar, pero pienso que las librerias se hacen para mejorar lo que hacemos, es como en vez de usar por ejemplo **Click** usemos lo basico de python para crear CLIs, sabiendo que trae ya ciertas herramientas que optimizan nuestro desarrollo

## 0160. Configuración de Flask [18454](https://platzi.com/clases/1540-flask/18454-configuracion-de-flask/)

### Descripción:


Para activar el _development mode_ debes escribir lo siguiente en la consola:
``` 
    export FLASK_ENV=development
    echo $FLASK_ENV
    
```

**SESSION:** es un intercambio de información interactiva semipermanente, también conocido como diálogo, una conversación o un encuentro, entre dos o más dispositivos de comunicación, o entre un ordenador y usuario.

### Comentarios:

* **danielsanz (Platzi)** (9) [535709](https://platzi.com/comentario/535709/) 
	
	![Objetos-Flask.png](https://static.platzi.com/media/user_upload/Objetos-Flask-618e24d3-6fbb-4290-96c7-fb97b376d36f.jpg)

* **mcamelo** (5) [617338](https://platzi.com/comentario/617338/) 

	Tambien pueden agregar la configuracion de esta manera:
	
	app = Flask( **name** )  
	app.config[‘ENV’] = ‘development’

	* **juliocefe** [617338] (2)

		Acerca de las variables de configuración…  
		Yo encontré la misma forma pero en la documentación oficial de flask te ponen esto "This is set by the FLASK_ENV environment variable and may not behave as expected if set in code."  
		La verdad a mi me da pereza exportar las variables, prefiero tenerlo en mi archivo instance/config.  
		p. ej:  
		ENV='development’  
		SECRET_KEY='5UP3R_53CR3T0’  
		DEBUG=True
		
		Por favor algún experto que me diga por qué que estaría mal hacerlo así?

* **Reddy Abel Tintaya Conde** (3) [886564](https://platzi.com/comentario/886564/) 

	Comparto una “buena práctica” (porfavor corrijan si no es así)  
	de como usar las variables de configuración para flask
	
	* Crear archivo [config.py](http://config.py)
	
	
	``` 
	    SECRET_KEY = secret_string
	    
	```
	
	* [main.py](http://main.py)
	
	
	``` 
	    app.config.from_pyfile('config.py')
	    
	```

* **marcelosanchez21** (1) [1055997](https://platzi.com/comentario/1055997/) 

	En el script de python.
	``` 
	    if __name__ == "__main__":
	        
	        app.run(debug=True)
	    
	```

* **marttcode** (1) [1049575](https://platzi.com/comentario/1049575/) 

	**Automatiza** el levantar tu entorno virtual de desarrollo (venv) con un script.
	``` 
	    #!/bin/bash
	    
	    pip install -r requierements.txt
	    source venv/bin/activate
	    
	    export FLASK_APP=main.py
	    export FLASK_DEBUG=1
	    export FLASK_ENV=development
	    
	    flask run
	    
	    
	```
	
	  1. Crea un archivo nuevo en la raíz del proyecto y copia el script de arriba.
	  2. Guárdalo con extension .sh
	  3. Ejecútalo en consola: $ source file_name.sh
	  4. You welcome!
	
	

* **Emmanuel Sosa Reyes** (1) [1046513](https://platzi.com/comentario/1046513/) 

	Oiga, alguien sabe como comentar en los render? Porque cuando lo hago los comentarios aparecen ahí en la página

* **Diego Casillas Duarte** (1) [1029561](https://platzi.com/comentario/1029561/) 

	Para el que esté trabajando en windows, le dejo los siguientes comandos para el powershell:
	``` 
	    $env:FLASK_ENV="development"
	    $env:FLASK_APP="nombredeapp.py"
	    
	```

* **Adrián Andrés Sosa** (1) [1027500](https://platzi.com/comentario/1027500/) 

	Por si le sirve a alguien, para ver el contenido de la variable de entorno es
	``` 
	    echo $FLASK_ENV
	    
	```

* **jlrc23** (1) [918198](https://platzi.com/comentario/918198/) 

	Por si alguien usa PowerShell, puede declarar las variables asi:
	``` 
	    $env:FLASK_ENV="development"
	    
	```

* **juliocefe** (1) [65022](https://platzi.com/comentario/684893/) 
Acerca de las variables de configuración… Yo encontré la misma forma pero en la documentación oficial de flask te ponen esto "This i...

	* **Kevin Javier Morales** [65022] (1)

		Tener un archivo con todas las variables de entorno que necesitas es muy común. Por lo general se guardan en un archivo `.env` para que este oculto y sea más seguro.
		
		Puedes usarlo de esta manera, mientras puedas mantener seguro ese archivo.

## 0170. Implementación de Flask-Bootstrap y Flask-WTF [18455](https://platzi.com/clases/1540-flask/18455-implementacion-de-flask-bootstrap-y-flask-wtf/)

### Descripción:


### Links:

* [Flask-WTF — Flask-WTF 0.14](https://flask-wtf.readthedocs.io/en/stable/)

### Comentarios:

* **Royer Guerrero Pinilla** (3) [1070176](https://platzi.com/comentario/1070176/) 

	Hecho un camino duro pero que valdrá la pena ![Imagen 8.png](https://static.platzi.com/media/user_upload/Imagen%208-69694094-47c7-4416-8cfa-68eb79919ba6.jpg)![Imagen 9.png](https://static.platzi.com/media/user_upload/Imagen%209-728294cd-32e3-4303-b3d9-2a4fd89537a2.jpg)

* **Jean Carlos Nuñez Hernandez** (3) [576248](https://platzi.com/comentario/576248/) 

	Waaao WTF es muy interesante y productivo

* **Jorge** (2) [622847](https://platzi.com/comentario/622847/) 

	from wtforms import validators
	
	username = StringField(‘Nombre de usuario’, validators=[validators.input_required()])  
	password = PasswordField(‘Password’, validators=[validators.input_required()])

* **edgar manuel perez cob** (1) [1032323](https://platzi.com/comentario/1032323/) 

	Aqui les inserto la imagen del error!![flask2.JPG](https://static.platzi.com/media/user_upload/flask2-d4203ae7-214a-4290-b693-92f92c946fd7.jpg)

	* **marttcode** [1032323] (1)

		Me tardé en encontrar el problema. Pero así pude acercarme al resultado del profe. Aún que no fue el mismo.  
		Creo que el problema es que usamos una diferente version de Flask .-.
		
		Esto cambié en main,py, importé diferentes objetos.
		``` 
		    from flask_bootstrap import Bootstrap
		    from wtforms import Form, StringField, SubmitField, PasswordField
		    from wtforms.validators import DataRequired
		    
		    classLoginForm(Form):
		        username =  StringField('Username', validators=[DataRequired()])
		        password = PasswordField('Password', validators=[DataRequired()])
		        submit = SubmitField('Submit')
		    
		```
		
		Mientras que en hola.html no pude usar bootsrap directamente así que lo hice así.
		``` 
		    <div class="container">
		    
		            <form action="{{ url_for('hello')}}" method="POST">
		                <div class="form-group">
		                    {{ login_form.username.label }}
		                    {{ login_form.username }}
		                </div>
		                <div class="form-group">
		                    {{ login_form.password.label }}
		                    {{ login_form.password }}
		                </div>
		                
		                {{ login_form.submit }}
		                
		              </form>        
		    
		        </div>
		    
		```
		
		El resultado fue el siguiente
		
		![temp4.png](https://static.platzi.com/media/user_upload/temp4-e004160b-8d75-43e8-88a9-dea4031d686a.jpg)

	* **marttcode** [1032323] (1)

		Sabes que mejor migra tu trabajo a un nuevo entorno virtual .-.  
		En los siguientes videos también causa errores el tener otra configuración de flask. Aquí te dejo el requirementes.txt  
		Con eso solucionas todo.
		``` 
		    flask==1.0.2
		    click==7.0
		    jinja2==2.10
		    itsdangerous==1.1.0
		    markupsafe==1.1.1
		    werkzeug==0.14.1
		    flask-bootstrap==3.3.7.1
		    flask-wtf==0.14.2
		    
		    
		```

* **edgar manuel perez cob** (1) [1032320](https://platzi.com/comentario/1032320/) 

	alguien me podria ayudar? me sale que no puedo importar dicha flask_wtf ya se encuentra en el **requeriments.txt** y ya lo tengo instalado si alguien me podria ayudar!  
	[flask.JPG](https://static.platzi.com/media/user_upload/flask-650212fa-370d-491f-8624-ee98702dd53b.jpg)
	``` 
	    from flask import Flask, request, make_response, redirect, render_template,session
	    from flask_wtf import FlaskForm
	    
	    
	    app = Flask(__name__)
	    
	    todo = ['TODO 1', 'TODO 2', 'TODO 3']
	    
	    
	    
	    
	    #pagina cuandeo arroja un error
	    @app.errorhandler(404)
	    defnot_found(error):
	        return render_template('404.html', error=error)
	    
	    
	    @app.route('/')
	    defindex():
	        user_ip = request.remote_addr
	        response = make_response(redirect('/hello'))
	        session['user_ip']= user_ip
	    
	        return response
	    
	    
	    @app.route('/hello')
	    defhola():
	        user_ip = session.get('user_ip')
	    
	        context = {
	                    'user_ip' : user_ip, 
	                    'todo' : todo,
	    
	        }
	        return render_template('hola.html', **context)
	    
	    if __name__ == '__main__':
	        # This is used when running locally. Gunicorn is used to run the
	        # application on Google App Engine. See entrypoint in app.yaml.
	        app.run(host='127.0.0.1', port=8080, debug=True)
	    # [END gae_flex_quickstart]
	    
	```

	* **marttcode** [1032320] (1)

		Tal vez sea el mismo problema que este, checalo, espero te ayude .-.
		
		<https://platzi.com/comentario/1032323/>

* **diegomedflo** (1) [1013528](https://platzi.com/comentario/1013528/) 

	¿Cómo darle estilo a los input? Osea al login_form_username.  
	Ya que no es una etiquetea HTML no se le puede agregar una clase y por ende no se le agrega css. ¿Cómo hacerlo entonces?

* **raulfbgomez** (1) [1004852](https://platzi.com/comentario/1004852/) 

	Como dato extra, DataRequired únicamente agrega el atributo HTML required a los inputs del formulario, por lo que si se necesita mas control deberían implementar JavaScript.
	``` 
	    <input class="form-control" id="username" name="username" required=""type="text" value="">
	    
	```

* **raulfbgomez** (1) [1004850](https://platzi.com/comentario/1004850/) 

	Como dato extra, DataRequired únicamente agrega el atributo HTML required a los inputs del formulario, por lo que si se necesita mas control deberían implementar JavaScript.

* **Carlos Cuevas Sosa** (1) [978431](https://platzi.com/comentario/978431/) 
Excelente framework, al parecer ahorraré mucho tiempo!

## 0180. Uso de método POST en Flask-WTF [18456](https://platzi.com/clases/1540-flask/18456-uso-de-metodo-post-en-flask-wtf/)

### Descripción:


Flask acepta peticiones **GET** por defecto y por ende no debemos declararla en nuestras rutas.

Pero cuando necesitamos hacer una petición **POST** al enviar un formulario debemos declararla de la siguiente manera, como en este ejemplo:
``` 
    @app.route('/platzi-post', methods=['GET', 'POST'])
    
```

Debemos declararle además de la petición que queremos, **GET** , ya que le estamos pasando el parámetro _methods_ para que acepte solo y únicamente las peticiones que estamos declarando.

De esta forma, al actualizar el navegador ya podremos hacer la petición **POST** a nuestra ruta deseada y obtener la respuesta requerida.

### Comentarios:

* **Javier Fuentes Mora** (4) [763973](https://platzi.com/comentario/763973/) 
Esto se parece demasiado a php

	* **william andres rodriguez borja** [763973] (1)

		se me parece solo a las plantillas de laravel la verdad.  
		con laravel es sencillo pero esto es otro nivel.  
		se me parece mas a spring-framework de java.  
		flask es el framework mas sencillo en el lenguaje mas sencillo.

* **Jean Carlos Nuñez Hernandez** (3) [576249](https://platzi.com/comentario/576249/) 

	esta bueno esto methods=[‘get’, ‘post’]

* **Royer Guerrero Pinilla** (1) [1070839](https://platzi.com/comentario/1070839/) 

	Es muy bueno saber esto ya que en un futuro me gustaría hacer una API con flask y los metodos Http son claves

* **Nietsnie Alberto Perez cruz** (1) [1030523](https://platzi.com/comentario/1030523/) 

	<https://flask-wtf.readthedocs.io/en/stable/quickstart.html>

## 0190. Desplegar Flashes (mensajes emergentes) [18457](https://platzi.com/clases/1540-flask/18457-desplegar-flashes-mensajes-emergentes/)

### Descripción:


### Links:

* [Message Flashing — Flask 1.0.2 documentation](http://flask.pocoo.org/docs/1.0/patterns/flashing/)

### Comentarios:

* **Israel Yance** (14) [602582](https://platzi.com/comentario/602582/) 

	No se vio en el vídeo pero lo primero que se hizo fue importar flash
	``` 
	    from flask import Flask, request, make_response, redirect, render_template, session, url_for, flash```
	    
	```

* **Royer Guerrero Pinilla** (1) [1071506](https://platzi.com/comentario/1071506/) 

	En Boostrap4 hace falta mas codigo para que funcione el codigo
	``` 
	    <divclass="alert alert-warning alert-dismissible fade show" role="alert">
	      <strong>Holy guacamole!</strong> You should check inonsomeof those fields below.
	      <button type="button"class="close" data-dismiss="alert" aria-label="Close">
	        <span aria-hidden="true">&times;</span>
	      </button>
	    </div>```
	    
	```

## 0200. Pruebas básicas con Flask-testing [18458](https://platzi.com/clases/1540-flask/18458-pruebas-basicas-con-flask-testing/)

### Descripción:


La etapa de pruebas se denomina _testing_ y se trata de una investigación exhaustiva, no solo técnica sino también empírica, que busca reunir información objetiva sobre la calidad de un proyecto de software, por ejemplo, una aplicación móvil o un sitio web.

El objetivo del _testing_ no solo es encontrar fallas sino también aumentar la confianza en la calidad del producto, facilitar información para la toma de decisiones y detectar oportunidades de mejora.

### Links:

* [Flask-Testing — Flask-Testing 0.3 documentation](https://pythonhosted.org/Flask-Testing/)

### Comentarios:

* **Victor Inojosa** (3) [831296](https://platzi.com/comentario/831296/) 

	Para probar si un mensaje fue flasheado pueden usar el método **`assert_message_flashed()`**
	``` 
	    deftest_user_registered_flashed_message(self):
	        fake_form = {
	            'username': 'vijoin',
	            'password': '123456'
	        }
	        self.client.post(url_for('index'), data=fake_form)
	        message = 'User registered successfully'
	        self.assert_message_flashed(message)
	    
	```
	
	Este método solo recibe el mensaje que quieres validar. Los mensajes flasheados ya están en el atributo **`self.flashed_messages`** luego de realizar el request

	* **william andres rodriguez borja** [831296] (1)

		Buen aporte. Gracias.

* **Cristian Raul Arce Gallardo** (2) [997443](https://platzi.com/comentario/997443/) 

	Esto es lo que sucede cuando no se usa un control de versiones, para que tiene su requirements.txt si tiene version infinita? para saver que version de werkzeug tiene el prof 😕

* **Israel Yance** (2) [979120](https://platzi.com/comentario/979120/) 

	Por si les sale este error:
	``` 
	    ERROR: test_base (unittest.loader._FailedTest)
	    ----------------------------------------------------------------------
	    ImportError: Failed to import test module: test_base
	    
	```
	
	Se puede solucionar agregando las siguientes líneas en el [main.py](http://main.py):
	``` 
	    import werkzeug
	    werkzeug.cached_property = werkzeug.utils.cached_property```
	    
	    
	```

	* **Cristian Raul Arce Gallardo** [979120] (1)

		que version de werkzeug usas?, no me funciona tu fix 😦

	* **Nicolás Mayorga Vargas** [979120] (1)

		No me funcionó el fix

	* **sebastian-castro-torres** [979120] (1)

		Funcionó gracias

* **Jorge** (2) [625656](https://platzi.com/comentario/625656/) 

	sino me está redirigiendo a index, cómo puedo saber a donde me está mandando?

	* **Eduardo Kiriakos Piazza** [625656] (1)

		Siempre puedes hacer debug con python usando pdb! Por ejemplo, en la funcion test_hello_post puedes analizar el response de la siguiente manera:
		``` 
		    deftest_hello_post(self):
		        fake_form = {
		          'username': 'fake',
		          'password': 'fake-password'
		        }
		        response = self.client.post(url_for('hello'), data={**fake_form})
		    
		        import pdb; pdb.set_trace()
		    
		        self.assertRedirects(response, url_for('index'))
		    
		```
		
		De esta forma abre un debugger en tu terminal cuando corres tus pruebas donde puede analizar el “response”.
		
		Personalmente este truquillo es de los que más me ha hecho aprender!  
		puedes por ejemplo saber qué métodos tienes disponible con ese objeto response usando >> dir(response).
		
		Probé y conseguí la redirección con el método response.data!

* **Ivan Camilo Ramirez Rojas** (2) [600340](https://platzi.com/comentario/600340/) 

	El self.client que me permite hacer http_requests viene en el TestCase?

* **Royer Guerrero Pinilla** (1) [1071722](https://platzi.com/comentario/1071722/) 

	Se me ejecutan 41 test con el primer uso de flask test![Imagen 10.png](https://static.platzi.com/media/user_upload/Imagen%2010-5a740824-b253-4edd-ba12-080d75436747.jpg)

* **xmedinavei** (1) [1046168](https://platzi.com/comentario/1046168/) 

	ModuleNotFoundError: No module named ´flask_testing´
	
	Dentro del directorio test, el archivo test_base.py:
	``` 
	    from flask_testing import TestCase
	    
	```
	
	Alguien sabe el por qué?

	* **Rodrigod** [1046168] (1)

		hiciste el pip install flask-testing?

* **raulfbgomez** (1) [1006352](https://platzi.com/comentario/1006352/) 

	Corri el comando `flask test` por primera vez y ejecuto 41 tests:  
	![cmd](https://static.platzi.com/media/user_upload/cmd-86af026a-8c84-4dfe-951f-348aece83eb6.jpg)

	* **Royer Guerrero Pinilla** [1006352] (1)

		Encontraste la razon de porque pasa eso?

	* **Royer Guerrero Pinilla** [1006352] (1)

		Es porque pusiste disvover('test) y era discover('tests)

* **viktorv** (1) [987593](https://platzi.com/comentario/987593/) 

	Tengo el siguiente error:
	
	![test-error - copia.png](https://static.platzi.com/media/user_upload/test-error%20-%20copia-a9ce8940-4ba8-48db-836c-23acbe9285fc.jpg)

* **william andres rodriguez borja** (1) [958606](https://platzi.com/comentario/958606/) 

	Me encanto esta clase la verdad con esto se defiende uno total con unit test.  
	Utilizando este modelo seria necesario crear mocks para probar con set de datos supuestos que vienen ejemplo de una DB .  
	Seria genial material sobre este tema.

* **Juan José Lockett** (1) [884893](https://platzi.com/comentario/884893/) 

	Ejecute flask test y empezó a ejecutar una lista interminable de comprobaciones. Aún esta corriendo tras 20 minutos de ejecución, no era que no tenía que correr nada?

	* **william andres rodriguez borja** [884893] (1)

		Cuantos un poco mas yo ejecuto mis test que son mas de 200 y no se demora mucho.  
		Tienes logs o algo de informacion para ayudarte.

* **Jean Carlos Nuñez Hernandez** (1) [576258](https://platzi.com/comentario/576258/) 

	UnitTest Busca todos los archivos que comienza con la palabra test

* **Nicolás Mayorga Vargas** (1) [82383](https://platzi.com/comentario/1004286/) 
Tengo el error de cannot import name ‘cached_property’ from ‘werkzeug’ ¿Cómo lo soluciono?

	* **Cristhian Arce** [82383] (1)

		El error es muy poco diciente, sin embargo, puedes intentar reinstalando la dependencia de werkzeug
		``` 
		    pip uninstall Werkzeug
		    pip install Werkzeug
		    
		```

* **Cristian Raul Arce Gallardo** (1) [82115](https://platzi.com/comentario/997675/) 
Ya no se que hacer 😦 estoy en el min. 8 de este video recomiendan baja...

	* **Cristian Raul Arce Gallardo** [82115] (1)

		[main.py](http://main.py)
		``` 
		    from flask import Flask, request, make_response, redirect, render_template, session, url_for, flash
		    from flask_bootstrap import Bootstrap
		    from flask_wtf import FlaskForm
		    from wtforms.fields import StringField, PasswordField,SubmitField
		    from wtforms.validators import DataRequired
		    import unittest
		    
		    app = Flask(__name__)
		    #app.config['ENV'] = 'development' #not work
		    app.config['SECRET_KEY'] = 'super secretow'
		    bootstrap = Bootstrap(app)
		    
		    todos = ['Lupita Gallardo', 'Gerardo prensa', 'Lic. Alverto']
		    
		    classLoginForm(FlaskForm):
		        username = StringField('Nombre de usuario', validators=[DataRequired()])
		        password = PasswordField('Password', validators=[DataRequired()])
		        submit = SubmitField('Enviar')
		    
		    @app.cli.command()
		    deftest():
		        tests = unittest.TestLoader().discover('tests')
		        unittest.TextTestRunner().run(tests)
		    
		    @app.errorhandler(404)
		    defnot_found(error):
		        return render_template('404.html', error=error)
		    
		    @app.route('/')
		    defindex():
		        user_ip = request.remote_addr
		    
		        response = make_response(redirect('/hello'))
		        session['user_ip'] = user_ip #response.set_cookie('user_ip',user_ip)
		        return response
		    
		    @app.route('/hello', methods=['GET','POST'])
		    defhello():
		        user_ip = session.get('user_ip')#request.cookies.get('user_ip')
		        login_form = LoginForm()
		        username = session.get('username')
		    
		        context = {
		            'user_ip': user_ip,
		            'todos': todos,
		            'login_form': login_form,
		            'username': username
		            }
		        if login_form.validate_on_submit():
		            username = login_form.username.data
		            session['username'] = username
		            flash('User name registered successfully')
		    
		            return redirect(url_for('index'))
		    
		        return render_template('hello.html',**context)
		    
		    """
		    export FLASK_APP=main.py && export FLASK_ENV=development
		    export FLASK_DEBUG=1
		    """
		    
		    
		```
		
		test_base.py
		``` 
		    from flask_testing import TestCase
		    from flask import current_app
		    
		    from main import app
		    
		    classMainTest(TestCase):
		        defcreate_app(self):
		            app.config['TESTING'] = True
		            app.config['WTF_CSRF_ENABLED'] = False
		    
		            return
		        deftest_app_exists(self):
		            self.assertIsNotNone(current_app) 
		    
		    
		```

* **Claudio Jesus Vázquez Villanueva** (1) [69720](https://platzi.com/comentario/762019/) 
Me sucedio esto Traceback (most recent call last): File "C:\Users\claud\platzi\python\Flask\platzi-flask\tests\test_base.py", lin...

	* **Erik Ochoa** [69720] (1)

		Está fallando el test de redirect porque no regresa un status code valido de 3xx (301, 302, 303 etc.).
		
		Revisa tu código de la ruta **/hello** en el archivo “main” sobretodo el condicional _if_ , yo creo que lo que está pasando es que estás regresando la respuesta del render_template() y no la del redirect()
		``` 
		    @app.route('/hello', methods=['GET', 'POST'])
		    defhello():
		        user_ip = session.get('user_ip')
		        login_form = LoginForm()
		        username = session.get('username')
		    
		        context = {
		            'user_ip': user_ip,
		            'todos': todos,
		            'login_form': login_form,
		            'username': username
		        }
		    
		        if login_form.validate_on_submit():
		            username = login_form.username.data
		            session['username'] = username
		    
		            flash('Nombre de usario registrado con éxito!')
		    
		            return redirect(url_for('index'))
		    
		        return render_template('hello.html', **context)
		    
		```

* **Ivan Camilo Ramirez Rojas** (1) [60075](https://platzi.com/comentario/600340/) 
El self.client que me permite hacer http_requests viene en el TestCase?

* **Jesús Abano Ferrara** (0) [62667](https://platzi.com/comentario/644175/) 
Me aparece este error: ERROR: test_base (unittest.loader._FailedTest) \-------------------------------------------------------------...

	* **Diego Alexander Forero Higuera (Platzi)** [62667] (1)

		Puedes compartir tu archivo de test por favor, para ver por donde puede estar el error.

# Proyecto [3700]

## 0210. Planteamiento del proyecto To Do List [18459](https://platzi.com/clases/1540-flask/18459-planteamiento-del-proyecto-to-do-list/)

### Descripción:


### Comentarios:

* **sebastiancastillo83z** (3) [694228](https://platzi.com/comentario/694228/) 

	Que maravilloso es el mundo Flask !, complejo al principio pero maravillosamente util.

* **Royer Guerrero Pinilla** (1) [1071814](https://platzi.com/comentario/1071814/) 

	Go go go!

* **Adrián Andrés Sosa** (1) [1029009](https://platzi.com/comentario/1029009/) 

	Excelente!

* **Celso Vicente Mercado Hurtado** (1) [685846](https://platzi.com/comentario/685846/) 

	arre con el proyecto !!

* **Anfercode** (1) [666692](https://platzi.com/comentario/666692/) 

	Wow se oye súper interesante este proyecto

## 0220. App Factory [18460](https://platzi.com/clases/1540-flask/18460-app-factory/)

### Descripción:


### Comentarios:

* **Mauricio Chávez Olea** (6) [543207](https://platzi.com/comentario/543207/) 

	Quizás, para hacer más segura la app, la información sensible como la secret key podemos leerla desde el entorno.
	
	Primero, declararla desde la terminal como hemos estado haciendo:
	``` 
	    export SECRET_KEY="Super Secret"
	    
	```
	
	Y luego la podemos leer desde cualquier archivo Python de la siguiente manera
	``` 
	    import os
	    
	    secret_key = os.environ['SECRET_KEY']
	    
	```
	
	Incluso podemos lanzar una excepción cuando la secret key no esté declarada e informarle al usuario que debe establecer una 😄

* **Anfercode** (2) [666719](https://platzi.com/comentario/666719/) 

	Que bien así el proyecto esta as organizado

* **MatiasBZ** (2) [551474](https://platzi.com/comentario/551474/) 

	Que solución brindan los frameworks de python si deseo renderizar con templates que estan alojados en hosts remotos? … o bien, distribuidos en containers docker en diferentes servidores distribuidos ???
	
	El ejemplo de este curso es de arquitectura monolitica. Y como debemos trabajar con Flask y Jinja si deseo distribuir los templates, o bien , tener por separado un template server???

	* **Camilo Cáceres** [551474] (6)

		En mi opinión el curso falla en no presentar el uso real de Flask como backend, que probablemente va a ser una API que sirva datos a algún front-end en React o Vue, pero definitivamente no en Jinja. Flask se hace sumamente escalable como API sirviendo a un Front-end bien construido pero para alguien que quiera montar algo pequeño, Jinja está bien y soluciona el problema inmediato aunque de manera no tan escalable.

	* **Romel Javier Gomez Herrera** [551474] (1)

		“renderizar con templates que están alojados en hosts remotos” he experimentado que añade más latencia, intenta con un micro servicio que sirva un un index.html personalizado en función de la url, luego este archivo index.html descargara los archivos que necesita desde un CDN, lo demás son endpoints, microservicios, apis. Un app angular, la puedes dividir en módulos, optimizar en ese sentido.

	* **mcamelo** [551474] (1)

		Lo que necesitas es un API, en este curso te brindan la informacion nesesaria para crear o exponer las rutas:  
		@app.route(’/index’, method=[‘GET’])
		
		Hay varias formas de tambien crear rutas, no solo esta
		
		Asi como hacer diferentes modulos con los blueprint
		
		Tal vez lo que falta es un ORM pero a ti te brindo uno,  
		<https://docs.sqlalchemy.org/en/13/>

	* **william andres rodriguez borja** [551474] (1)

		lo que quieres hacer es un micro servicio de vistas para una aplicacion monolitica no entendi del todo la pregunta suponiendo que es lo que pienso.  
		Pues si quieres pasarte a micro servicios mejor pasas toda la aplicacion a micro servicios a igual pero en lugar de responder plantillas usas jsonify(dict_rest) para responder json y usaria react de front para no tener que hacer un server de plantillas. como un esquema de micro servicios normal.  
		Y lo puedes hacer progresivo.

* **MatiasBZ** (2) [56347](https://platzi.com/comentario/551474/) 
Que solución brindan los frameworks de python si deseo renderizar con templates que estan alojados en hosts remotos? … o bien, distribuid...

	* **Camilo Cáceres** [56347] (6)

		En mi opinión el curso falla en no presentar el uso real de Flask como backend, que probablemente va a ser una API que sirva datos a algún front-end en React o Vue, pero definitivamente no en Jinja. Flask se hace sumamente escalable como API sirviendo a un Front-end bien construido pero para alguien que quiera montar algo pequeño, Jinja está bien y soluciona el problema inmediato aunque de manera no tan escalable.

* **JORGE ANDRES DIAZ CELIS** (1) [1063808](https://platzi.com/comentario/1063808/) 

	Alguien sabe cuál es el IDE que usa el instructor? me parece súper útil la funcionalidad en la que se despliega las posibles instancias, métodos o variables de un objeto conforme lo va escribiendo. Gracias.

	* **jcavelez** [1063808] (1)

		Parece VSCode con alguna extensión.
		
		En mi PC yo tengo VSCode con las siguientes extensiones y hace lo mismo.
		
		Python  
		Kite Python Autocomple
		
		(Además de ‘Auto Rename Tag’ que es muy últil para HTML)

	* **Sara Galván Ortega** [1063808] (1)

		Utiliza PyCharm pero Visual Code u otro igual te funciona

	* **jcavelez** [1063808] (1)

		[IntelliJ IDEA](https://www.jetbrains.com/es-es/idea/)

	* **Royer Guerrero Pinilla** [1063808] (1)

		Pycharm existe una versión gratuita de comunidad pero no te da muchas herramientas para desarrollo web si estudias en algún instituto, universidad o similar puedes pedir una versión de estudiante con tu correo .edu

* **Angel Santillan Brambila** (1) [646905](https://platzi.com/comentario/646905/) 

	me causa conflicto con el el .config y si lo dejo solo como config no ejecuta el de flask test saben por que??

	* **Diego Alexander Forero Higuera (Platzi)** [646905] (1)

		Puedes compartir el error que te sale para entender un poco el problema y ver que puede estar causándolo.

	* **judamaro** [646905] (1)

		En la consola con el ambiente activado corre `flask --help` y te dará una idea de porque no funciona.  
		Pero revisa que tengas bien escrito todo, porque muchas es un error de escritura.

## 0230. Uso de Blueprints [18461](https://platzi.com/clases/1540-flask/18461-uso-de-blueprints/)

### Descripción:


### Links:

* [blinker · PyPI](https://pypi.org/project/blinker/)

### Comentarios:

* **Mauricio Chávez Olea** (5) [543262](https://platzi.com/comentario/543262/) 

	Está super cool que enseñen Flask con test driven development 😄

	* **Jean Carlos Nuñez Hernandez** [543262] (1)

		Esto es para mi lo mas importante

* **JORGE ANDRES DIAZ CELIS** (4) [1064084](https://platzi.com/comentario/1064084/) 

	Para tener un poco más de claridad, a mi me sirvió entender el árbol del proyecto, depronto a alguien también le sirva:
	``` 
	    ##  arbol del proyecto
	    ##  /venv
	    ##  --main.pylógica de la app
	    ##  --/tests
	    ##  ----test_base.py        pruebas para test
	    ##  --/app
	    ##  ----__init__.py         crea la app, trae configuraciones de config.py, trae el blueprint creado ylo registra enla app
	    ##  ----config.py           fija configuraciones de la app, a ser consumido por /app/__init__.py
	    ##  ----forms.py            crea la clase para los formularios. A ser consumido por main.py
	    ##  ----/auth
	    ##  ------__init__.py       crea el blueprint auth, importa vistas de views.py. Es decir que este va a tener el blueprint yla vista de login.
	    ##  ------views.py          crea una vista de Login. La vista es una ruta a /login/login.html usando el blueprint auth creado en auth/__init__.pyen vez de app.  
	    
	    
	```

* **Rodrigod** (2) [1046460](https://platzi.com/comentario/1046460/) 

	Un blueprint es como el esqueleto de una aplicacion

* **jcavelez** (1) [1065753](https://platzi.com/comentario/1065753/) 

	Buena info para repasar y complementar : [Link](https://www.manejandodatos.es/2015/06/flask-para-aplicaciones-grandes-blueprints/)

* **brandon james grimaldo moscote** (1) [1037936](https://platzi.com/comentario/1037936/) 

	esto de hacer test con flask esta genial.

* **raulfbgomez** (1) [1006633](https://platzi.com/comentario/1006633/) 

	A mi me sale el siguiente error:  
	![error](https://static.platzi.com/media/user_upload/error-84cf8ea4-720b-4709-a771-0a483e489b33.jpg)
	
	Borre las rutas de los anchor en el archivo navbar.html y todo volvió a funcionar correctamente. Alguna idea de porque pasa esto?
	``` 
	    // Cambie url_for por un simple numeral '#'
	    <li><ahref="{{ url_for('index') }}">Inicio</a></li> 
	    
	```

* **hesau2001** (1) [967078](https://platzi.com/comentario/967078/) 

	Qué se supone que es un Blueprint? no logro entenderlo del todo

	* **Israel Yance** [967078] (2)

		Blueprints son módulos con los que se construyen las aplicaciones Flask. Los objetos Blueprints son similares a Flask, pero con la diferencia de que una aplicación sólo tendrá un objeto Flask, mientras que puede tener varios Blueprints. La ventaja de su uso es que para aplicaciones largas puedo distribuir el código en varios ficheros, en lugar de tenerlos todo en un único fichero.  
		Fuente:  
		<https://www.manejandodatos.es/2015/06/flask-para-aplicaciones-grandes-blueprints/>

* **hesau2001** (1) [967056](https://platzi.com/comentario/967056/) 

	A que se refiere cuando dice renderear?

	* **diegomedflo** [967056] (2)
Hay muchos términos técnicos que no me gusta usar, pero son necesarios. El modulo render,_template interpreta el codigo html y lo que tenga dentro de él. Si usas ese módulo, pues estas rendereando algo o estás ejecutando un archivo html.

* **Jorge** (1) [626201](https://platzi.com/comentario/626201/) 

	me manda un problema al momento de hacer el test :  
	def test_auth_blueprint_exists(self):  
	self.assertIn(‘auth’, self.app.blueprints)
	
	me dice que tengo un problema con la linea: app.register_blueprint(auth)

	* **Juan José Lockett** [626201] (1)

		Revisa que estés importando correctamente “from .auth import auth”.  
		Luego en el **init**.py de auth tambien revisa que estes importando correctamente “from flask import Blueprint”.  
		Por ultimo verifica que estes inicializando auth correctamente: "aut = Blueprint(‘auth’, **name** , url_prefix = ‘/auth’).  
		Espero ayude, sino deberás copiar mas información de tu error.

* **Carlos Huarcaya** (1) [617695](https://platzi.com/comentario/617695/) 

	Como podria hacer un test para validar una respuesta en json, e tratado de esa forma pero sin resultados!
	``` 
	    deftest_hello_post(self):
	            fake_user = {
	                "username" : "sonne",
	                "password" : "holiboli"
	            }
	            response = self.client.post(
	                url_for('login'), 
	                data=json.dumps(fake_user),
	                content_type='application/json'
	                )
	            data = json.loads(response.get_data(as_text=True))
	            self.assertEqual(data.get("status"), True)
	    
	```
	
	la url “/login” devuelve lo siguiente
	
	{  
	“password”: “holiboli”,  
	“status”: true,  
	“username”: “sonne”  
	}
	``` 
	    <code>
	    
	```

	* **Diego Casillas Duarte** [617695] (1)

		¿qué tal así?
		``` 
		    from flask import request, jsonify
		    
		    @app.route('/api/auth')
		    defauth():
		        json_data = request.get_json()
		        email = json_data['email']
		        password = json_data['password']
		        return jsonify(token=generate_token(email, password))
		    
		    with app.test_client() as c:
		        rv = c.post('/api/auth', json={
		            'email': 'flask@example.com', 'password': 'secret'
		        })
		        json_data = rv.get_json()
		        assert verify_token(email, json_data['token'])
		    
		```

## 0240. Blueprints II [18462](https://platzi.com/clases/1540-flask/18462-blueprints-ii/)

### Descripción:


### Comentarios:

* **Royer Guerrero Pinilla** (1) [1073035](https://platzi.com/comentario/1073035/) 

	Los blueprints funcionan similar a las apps de django

* **Moshe Cotacallapa** (1) [1069691](https://platzi.com/comentario/1069691/) 

	Tuve este error al ejecutar el test hello_post :
	
	AssertionError: Popped wrong request context. (<RequestContext  
	’<http://localhost/hello>’ [GET] of app> instead of <RequestContext ‘<http://localhost/>’ [GET] of app>)
	
	Al parecer recibe dos diferentes contextos. La solución recomendada [aquí](https://code-examples.net/en/q/19699f8) funcionó para mí también.
	
	Agregar en la funcion create_app de la clase Test.
	``` 
	    app.config['PRESERVE_CONTEXT_ON_EXCEPTION'] = True
	    
	```

* **Nicolás Mayorga Vargas** (1) [1002726](https://platzi.com/comentario/1002726/) 

	Excelente clase. El Blueprint es la viva expresión de Programación Orientada a Objetos

## 0250. Base de datos y App Engine con Flask [18463](https://platzi.com/clases/1540-flask/18463-base-de-datos-y-app-engine-con-flask/)

### Descripción:


* **Bases de Datos SQL:** su composición esta hecha con bases de datos llenas de tablas con filas que contienen campos estructurados. No es muy flexible pero es el más usado. Una de sus desventajas es que mientras más compleja sea la base de datos más procesamiento necesitará.

* **Base de Datos NOSQL:** su composición es no estructurada, es abierta y muy flexible a diferentes tipos de datos, no necesita tantos recursos para ejecutarse, no necesitan una tabla fija como las que se encuentran en bases de datos relacionales y es altamente escalable a un bajo costo de hardware.




### Links:

* [Google Cloud Platform](https://console.cloud.google.com/)

### Comentarios:

* **danielsanz (Platzi)** (4) [535703](https://platzi.com/comentario/535703/) 
	
	![Datastore-Firestore-SQL.png](https://static.platzi.com/media/user_upload/Datastore-Firestore-SQL-5c0624ef-b3a5-4a5b-beeb-e1504216e77a.jpg)

* **Anfercode** (1) [666853](https://platzi.com/comentario/666853/) 

	Esto se puso muy interesante =)

* **Alexander  Silvera** (1) [607804](https://platzi.com/comentario/607804/) 

	Buenas noches una consulta si ya tengo una base de datos en firestore, como hago para relacionarla con mi proyecto de flask??

## 0260. Configuración de Google Cloud SDK [18834](https://platzi.com/clases/1540-flask/18834-configuracion-de-google-cloud-sdk/)

### Descripción:


Ahora vamos a instalar el Google Cloud SDK. Simplemente debemos descargar un ejecutable desde alguno de estos enlaces:

Para Windows dirígete a <https://cloud.google.com/sdk/docs/quickstart-windows>  
Para MacOS dirígete a link <https://cloud.google.com/sdk/docs/quickstart-macos>  
Para Linux dirígete a <https://cloud.google.com/sdk/docs/quickstart-linux>

Una vez que corrimos el instalador, podemos verificar que instalamos correctamente el SDK corriendo en una terminal el siguiente comando:
``` 
    which glcoud
    
```

Ahora inicializamos _gcloud_ y hacemos _login_ con:
``` 
    gcloud init
    
```

> 
```
    gcloud auth login
```

### Comentarios:

* **juan diego ramirez rojas** (5) [903689](https://platzi.com/comentario/903689/) 

	Puede ser obvio, pero no es `which glcoud` es `which gcloud`

	* **Andrés David Ríos Ramirez** [903689] (1)

		Tiene razón Juan

* **Royer Guerrero Pinilla** (1) [1073957](https://platzi.com/comentario/1073957/) 

	No me servio en Windowns así que lo instale en ubuntu WSL

	* **Gabriel De Andrade** [1073957] (1)

		Si quieren aprender a hacer el setup de la WSL en Windows, en el [Curso de Prework](https://platzi.com/clases/prework/) se explica todo este proceso 😄

* **Jean Carlos Nuñez Hernandez** (1) [578456](https://platzi.com/comentario/578456/) 

	no sabia nada de gcloud auth, esta interesante

## 0270. Configuración de proyecto en Google Cloud Platform [18464](https://platzi.com/clases/1540-flask/18464-configuracion-de-proyecto-en-google-cloud-platform/)

### Descripción:


### Links:

* [Google Cloud Platform](https://console.cloud.google.com/projectcreate)

### Comentarios:

* **Angel Santillan Brambila** (2) [647889](https://platzi.com/comentario/647889/) 

	podrias explicar esto para windos ya que nada salio como tu lo hiciste y no se si funciono jeje

	* **Diego Alexander Forero Higuera (Platzi)** [647889] (1)

		Hola. Aquí encuentras la documentación oficial de como instalar gcloud en windows <https://cloud.google.com/sdk/docs/quickstart-windows>

* **Cristian Raul Arce Gallardo** (1) [999396](https://platzi.com/comentario/999396/) 

	Por que no escojio Datastore mode?? solo podemos hacer proyectos gratis en app engine, y app engine no esta disponible para native mode…

* **Reddy Abel Tintaya Conde** (1) [887524](https://platzi.com/comentario/887524/) 

	en la función hello  
	En vez de ponerlo dentro de macros también funciona, aunque no se que tan efectivo sea 😅
	``` 
	    todos = [ todo.to_dict()['description'] for todo inget_todos(username)]
	    context = {
	        'user_ip': user_ip,
	        'todos': todos,
	        'username': username
	    }   	
	    
	```

## 0280. Implementación de Firestore [18465](https://platzi.com/clases/1540-flask/18465-implementacion-de-firestore/)

### Descripción:


### Links:

* [firebase-admin · PyPI](https://pypi.org/project/firebase-admin/)

### Comentarios:

* **Jorge** (3) [628822](https://platzi.com/comentario/628822/) 

	```
	    import firebase_admin
	    from firebase_admin import credentials
	    from firebase_admin import firestore
	    
	    
	    project_id = 'platzi-flask-2....'
	    cred = credentials.ApplicationDefault()
	    firebase_admin.initialize_app(cred, {
	      'projectId': project_id,
	    })
	    
	    
	    db = firestore.client()
	    
	    
	    defget_users():
	        return db.collection('users').get()
	    
	```

* **raulfbgomez** (2) [1006929](https://platzi.com/comentario/1006929/) 

	A mi me decia que no se podía declarar la aplicación mas de una vez y que necesitaba un archivo json, para solucionar eso cambie un poco el código quedando de la siguiente manera:
	``` 
	    if (not len(firebase_admin._apps)):
	      cred = credentials.ApplicationDefault()
	      firebase_admin.initialize_app(cred, {
	        'projectId': 'your-project-id',
	      })
	    
	    db = firestore.client()
	    
	```

* **ThAlan** (2) [546184](https://platzi.com/comentario/546184/) 

	Me sale error al importar de firebase_admin y no se como solucionarlo  
	¿Alguien podría ayudarme?
	
	![vsFlaskError.png](https://static.platzi.com/media/user_upload/vsFlaskError-4f961f12-4fce-43f3-b085-a2f24b4fd874.jpg)

	* **Mauricio Chávez Olea** [546184] (1)

		¿No lo puedes correr o solo es error de VS Code?

	* **Ramon Sanchez** [546184] (2)

		@ThAlan es
		``` 
		    defget_users():
		            return db.collection('users').get()
		    
		```
		
		falto ejecutar el metodo get de db.collection

	* **Royer Guerrero Pinilla** [546184] (1)

		Usas WLS?

* **Royer Guerrero Pinilla** (1) [1074436](https://platzi.com/comentario/1074436/) 

	Si tienen problemas con conectar a firestore aqui les dejo este tutorial  
	[Añadir firebase a tu app](https://firebase.google.com/docs/admin/setup#add_firebase_to_your_app)

* **xmedinavei** (1) [1055295](https://platzi.com/comentario/1055295/) 

	A alguien más le sale este error?
	
	![Screenshot from 2020-03-22 15-04-16.png](https://static.platzi.com/media/user_upload/Screenshot%20from%202020-03-22%2015-04-16-7d9af811-cc52-401b-a37f-1dfbabcc8815.jpg)

* **Giancarlo Zevallos Lecca** (1) [840110](https://platzi.com/comentario/840110/) 

	Tengo un problema al instalar
	``` 
	    pip install firebase-admin
	    
	```
	``` 
	    Building wheels for collected packages: grpcio
	      Building wheel for grpcio (setup.py) ... error
	      ERROR: Command errored out with exit status 1:
	    
	```
	
	Pero creo que el verdadero problema es la libreria **“grpcio”** , porque al instarla me sale el mismo error
	
	Tengo python 3.8 y windows 10

* **Alexander  Silvera** (1) [607985](https://platzi.com/comentario/607985/) 

	estoy teniendo un problema es que cuando quiero pintar los datos en la aplicación de la base de datos firestore, no se muestran los datos en la lista. Si me muestra el usuario y el password conectados pero no logro visualizar los todos.

	* **judamaro** [607985] (1)

		Si te estoy entendiendo, el error esta en donde creas el documento:
		
		users > [El usuario que creaste] > todos > [id del documento]
		
		Es aquí donde creas los documentos y luego se visualizarán en la aplicación.  
		En el primer campo pones: description  
		En el segundo: string  
		En el tercero: La tarea que esta pendiente

## 0290. Autenticación de usuarios Login [18466](https://platzi.com/clases/1540-flask/18466-autenticacion-de-usuarios-login/)

### Descripción:


### Links:

* [Flask-Login — Flask-Login 0.4.1 documentation](https://flask-login.readthedocs.io/en/latest/)

### Comentarios:

* **brandon james grimaldo moscote** (2) [1038596](https://platzi.com/comentario/1038596/) 

	buen día , si les da **error el código** en esta clase , es muy posible y les recomiendo que **instalen la misma versión** que en su momento era la actual al momento en que **lo instalo el profesor** , muy posiblemente les de error , así que instalen la siguiente versión , **pip install flask-login==0.4.1**  
	esa es la versión que esta usando el profe , saludos.

	* **Sara Galván Ortega** [1038596] (1)

		para desinstalar la versión que uno ya instaló se usa el comando
		``` 
		    pip uninstall flask-login
		    
		```

* **Nicolás Mayorga Vargas** (1) [1006648](https://platzi.com/comentario/1006648/) 

	Debo admitir que esta fue la clase más abrumadora y que tuve que regresar al curso de API rest para entender algunos conceptos. Pero está bien. Es necesario

* **hesau2001** (1) [984991](https://platzi.com/comentario/984991/) 

	Hola  
	Solo para comentar que para que funcione su codigo tienen que escribir todo lo que se deci en la clase para establecer el LoginMAnager correctamente

* **Jean Carlos Nuñez Hernandez** (1) [578484](https://platzi.com/comentario/578484/) 

	UserMixin ya tienes implementaciones de metodos listos

## 0300. Autenticación de usuarios Logout [18467](https://platzi.com/clases/1540-flask/18467-autenticacion-de-usuarios-logout/)

### Descripción:


### Comentarios:

* **Ivan Camilo Ramirez Rojas** (2) [600963](https://platzi.com/comentario/600963/) 

	Que tal cambiar
	``` 
	    if user_dic.to_dict() isnotNone:
	    
	```
	
	por
	``` 
	    if user_dic.to_dict():
	    
	```
	
	Sanes si tendría alguna implicación?

	* **Ivan Camilo Ramirez Rojas** [600963] (2)

		Sabes*

	* **karencarolina** [600963] (2)

		user_dic.to_dict() no devuelve un booleano asi que ese if no serviria funciona como lo hizo el profe porque se no existe devuelve None y si no devuelve None se ejecutara el bloque de codigo de ese if

	* **jcavelez** [600963] (1)

		Esto lo termina de aclarar:
		
		Python 3.8.1 (tags/v3.8.1:1b293b6, Dec 18 2019, 22:39:24) [MSC v.1916 32 bit (Intel)] on win32  
		Type “help”, “copyright”, “credits” or “license” for more information.
		
		> > > None == False  
		>  False

* **jcavelez** (1) [85309](https://platzi.com/comentario/1071062/) 
Por qué no extender a UserData directamente de UserMixin para solo tener una clase?

* **Ivan Camilo Ramirez Rojas** (1) [60121](https://platzi.com/comentario/600963/) 
Que tal cambiar if user_dic.to_dict() is not None: por if user_dic.to_dict(): Sanes si tendría alguna implica...

	* **Ivan Camilo Ramirez Rojas** [60121] (2)

		Sabes*

## 0310. Signup [18468](https://platzi.com/clases/1540-flask/18468-signup/)

### Descripción:


### Comentarios:

* **Cristian Raul Arce Gallardo** (5) [1006895](https://platzi.com/comentario/1006895/) 

	Si después de hashear el pwd ya no pueden entrar con su usuario, tienen que usar un check_password_hash en el metodo del login
	``` 
	    @auth.route('/login', methods=['GET', 'POST'])
	    deflogin():
	        login_form = LoginForm()
	        context = {
	            'login_form': LoginForm()
	        }
	    
	        if login_form.validate_on_submit():
	            username = login_form.username.data
	            password = login_form.password.data
	            user_doc = get_user(username)
	    
	            if user_doc.to_dict() isnotNone:
	                
	                if check_password_hash(user_doc.to_dict()['password'], password):
	                    user_data = UserData(username,password)
	                    user = UserModel(user_data)
	    
	                    login_user(user)
	                    flash('Well come again')
	                    redirect(url_for('hello'))
	                else:
	                    flash('wrong password >:(')
	            else:
	                flash('user does not exist =/')
	            return redirect(url_for('index'))
	        
	        return render_template('login.html', **context)
	    
	```

* **David Vargas Domínguez** (3) [641655](https://platzi.com/comentario/641655/) 

	Hola Comunidad!
	
	Averiguando encontré que current_user tbm tiene la propiedad is_anonymous
	
	por lo que hice que el link de signup aparezca en el navbar solo si el usuario no está logeado
	
	navbar.html
	``` 
	    {% if current_user.is_anonymous %}
	            <li><ahref="{{ url_for('auth.signup') }}">Signup</a></li>
	    {% endif %}
	    
	```

* **joseorlandoramirezyeoshen** (1) [590673](https://platzi.com/comentario/590673/) 

	Excelente curso Bernardo.  
	Una pregunta como le haces para recuperar el password y desencriptarlo al hacer logon?  
	Agradecido

	* **joseorlandoramirezyeoshen** [590673] (4)

		Listo.  
		En [views.py](http://views.py) importar **check_password_hash**  
		y en def Login() colocar:  
		if **check_password_hash(password_from_db, password):**  
		user_data = UserData(username, password)  
		user = UserModel(user_data)
		``` 
		                login_user(user)
		                flash('Bienvenido de nuevo')
		                redirect(url_for('hello'))
		            else:
		                flash('La información no coincide')
		```

	* **Bernardo Cassina** [590673] (2)

		Exacto, checamos que el hash del password que el usuario nos envía es igual al hash que tenemos en la base.

	* **juliocefe** [590673] (1)

		Como validan que las urls no puedan ser accedidas(no sé como se escribe) sin la sesión?

* **joseorlandoramirezyeoshen** (1) [59388](https://platzi.com/comentario/590673/) 
Excelente curso Bernardo. Una pregunta como le haces para recuperar el password y desencriptarlo al hacer logon? Agradecido

	* **joseorlandoramirezyeoshen** [59388] (4)

		Listo.  
		En [views.py](http://views.py) importar **check_password_hash**  
		y en def Login() colocar:  
		if **check_password_hash(password_from_db, password):**  
		user_data = UserData(username, password)  
		user = UserModel(user_data)
		``` 
		                login_user(user)
		                flash('Bienvenido de nuevo')
		                redirect(url_for('hello'))
		            else:
		                flash('La información no coincide')
		```

## 0320. Agregar tareas [18469](https://platzi.com/clases/1540-flask/18469-agregar-tareas/)

### Descripción:


### Comentarios:

## 0330. Eliminar tareas [18470](https://platzi.com/clases/1540-flask/18470-eliminar-tareas/)

### Descripción:


### Comentarios:

* **Andrés David Ríos Ramirez** (1) [1060554](https://platzi.com/comentario/1060554/) 

	Si cambian el macros.html por:
	``` 
	    {% import 'bootstrap/wtf.html' as wtf %}
	    
	    {% macro render_todo(todo, delete_form) %}
	        <liclass="list-group-item">
	            <spanclass="badge">
	                {%if todo.to_dict().done %}
	                    Done
	                {% else %}
	                    To do
	                {% endif %}
	            </span>
	            Descripción: {{ todo.to_dict().description }}
	    
	            {{ wtf.quick_form(delete_form, action=url_for('delete', todo_id=todo.id)) }}
	        </li>
	    {% endmacro %}
	    
	```
	
	En vez de False ó True les mostrará To do ó Done  
	![Screen Shot 2020-03-24 at 12.48.38.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-03-24%20at%2012.48.38-45b07531-b888-4e40-817b-59a7c86f452a.jpg)

* **Nicolás Mayorga Vargas** (1) [1011847](https://platzi.com/comentario/1011847/) 

	Me es más cómoda la alternativa para señalar el PATH de esa manera

	* **Andrés David Ríos Ramirez** [1011847] (1)

		Con Python>=3.7 se puede hacer aún mas legible:
		``` 
		    defdelete_todo(user_id, todo_id):
		        todo_ref = db.collection(f"users/{user_id}/todos/{todo_id}")
		        todo_ref.delete()
		    
		```

## 0340. Editar tareas [18471](https://platzi.com/clases/1540-flask/18471-editar-tareas/)

### Descripción:


### Comentarios:

* **Andrés David Ríos Ramirez** (2) [1060922](https://platzi.com/comentario/1060922/) 

	Si en macros.html a cada form del estilo botón le agregan la clase botón se va a ver mejor.
	
	Ejemplo:
	``` 
	    <buttontype="button"class="btn btn-light">
	                {{ wtf.quick_form(delete_form, action=url_for('delete', todo_id=todo.id)) }}
	            </button>
	            <buttontype="button"class="btn btn-light">
	            {{ wtf.quick_form(update_form, action=url_for('update', todo_id=todo.id, done=todo.to_dict().done)) }}
	            </button>
	    
	```
	
	## Así:
	
	![Screen Shot 2020-03-24 at 15.11.20.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-03-24%20at%2015.11.20-44b8d594-2015-4c14-af06-c3417b45fa11.jpg)

## 0350. Deploy a producción con App Engine [18472](https://platzi.com/clases/1540-flask/18472-deploy-a-produccion-con-app-engine/)

### Descripción:


### Links:

* [Google Cloud Platform](https://console.cloud.google.com/appengine)

* [Fundamentos de Google Cloud Platform por Xertica | Materiales](https://platzi.com/clases/fundamentos-google/)

### Comentarios:

* **Reddy Abel Tintaya Conde** (2) [892833](https://platzi.com/comentario/892833/) 

	Que tan grande o usada debe ser mi app para que me comiencen a cobrar?

* **Germán** (2) [615029](https://platzi.com/comentario/615029/) 

	No se puede habilitar si no tenemos cuenta de pago 😦

* **Armando Aguilar L.** (2) [566923](https://platzi.com/comentario/566923/) 

	Cortaron mucho este video

* **brandon james grimaldo moscote** (1) [1039709](https://platzi.com/comentario/1039709/) 

	gracias por el curso , aprendí a punta de mil errores, muy interesante el uso de Flask y la parte de deploy

* **Diego Andres Imbus Guzman** (1) [773736](https://platzi.com/comentario/773736/) 

	Alguien sabe cómo realizar el deployment de flask en amazon?

	* **camiloprietoreyes** [773736] (2)

		Hola, para amazon le recomiendo un vps como lightsail, por otro lado si quiere desplegar el proyecto del curso lo mejor seria cambiar a una base de datos diferente.

* **Cristian Raul Arce Gallardo** (1) [82321](https://platzi.com/comentario/1002785/) 
Hola! como puedo conseguir o configurar mi service accounts? en gcloud Gracias. /Users/panic/.loc...

* **roberto viglino** (1) [82178](https://platzi.com/comentario/999671/) 
Podrían explicar cómo publicar una app de Flask a trabes de IIS en windows server por favor

## 0360. Conclusiones [18473](https://platzi.com/clases/1540-flask/18473-conclusiones/)

### Descripción:


### Comentarios:

* **Jeith S Carrillo A** (7) [604602](https://platzi.com/comentario/604602/) 

	el curso es muy bueno. pero deberia centrarse en lo que se usa flask que es para tener un servicio de backend el cual se conecta con algun frontend .

	* **Eduardo Kiriakos Piazza** [604602] (4)

		Me di cuenta que es mejor Django para muchas cosas ya que trae muchas cosas por defecto que no tiene Flask y es mucho más escalable.
		
		Supongo que Flask al ser tan versátil y de rápido desarrollo funciona mejor para aplicaciones que resuelvan problemas muy específicos, me equivoco?

	* **estebansolorzano** [604602] (1)

		Cada uno es usado para diferentes cosas en especifico, Flask como lo dice es un microframework, podemos hacer cosas grandes (con mayor esfuerzo) pero es bueno para aplicaciones sencillas sin tanta cosa como Django.

* **viktorv** (3) [991211](https://platzi.com/comentario/991211/) 

	Bernardo es muy buen profe! Pero me resultó MUY dificil de seguir el ultimo modulo. Hace muchas cosas y no explica mucho el porque.  
	Sin embargo, obtuve mucho contexto de como es trabajar con Flask y ahora el camino a seguir es mucho mas facil! Excelente

* **artik0** (3) [831846](https://platzi.com/comentario/831846/) 

	muy buen curso, bastante claro y consiso, muchas gracias!

* **jcavelez** (1) [1073302](https://platzi.com/comentario/1073302/) 

	Gran curso. Para mi lo más difícil fue entender url_for y blueprints

* **JORGE ANDRES DIAZ CELIS** (1) [1069978](https://platzi.com/comentario/1069978/) 

	Excelente curso, al ser tan rápida la dinámica hace que te esfuerces más para llevar el ritmo. en mi caso y dado que el entorno de Google al parecer pide Tarjeta de crédito no me pareció tan útil para este ejercicio, por el contrario y dado que he trabajado mucho con MySql, realicé la implementación sobre este motor e hice el deploy en un servidor web, me tomó un poco de tiempo adaptar el código a MySQL pero lo logré y aprendí mucho más. Gracias a Bernardo y a todos los comentarios realizados.

* **brandon james grimaldo moscote** (1) [1039713](https://platzi.com/comentario/1039713/) 

	simplemente asta ahora el curso que mas me gusto de python , gracias por el curso.

* **Diego Casillas Duarte** (1) [1033884](https://platzi.com/comentario/1033884/) 

	Excelente curso 😄 intenté hacer todo casi igual pero me tiraba errores que se resolvieron de quién sabe qué manera, de repente el intérprete sale con pendejaditas.
	
	Me encantó la forma tan práctica de llevar la clase.

* **Adrián Andrés Sosa** (1) [1029390](https://platzi.com/comentario/1029390/) 

	Gracias!

* **Jean Carlos Nuñez Hernandez** (1) [904211](https://platzi.com/comentario/904211/) 

	Este curso esta buenisimo, gracias profe!

