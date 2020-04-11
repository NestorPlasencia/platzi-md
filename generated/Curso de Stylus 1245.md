# Introducción al curso

## 0010. Introducción a los cursos de preprocesadores

### Descripción:


### Comentarios:

* **Rene Ismael Barrios Rojas** (6)

	
	En el intro dice curso de Sass y es de stylus jej

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Gracias por el reporte.

	* **Yahir  Castro** (1)

		
		aun dice sass 😦

	* **Jhonny luna** (1)

		
		aun lo dice

* **Rafael Guillermo Rodriguez Garcia** (3)

	
	Hice un aporte para quienes deseen que se compile automáticamente el Jade o Stylus, cuando se salva en Sublime Text 2/3  
	[Automatizar Jade y Stylus con Sublime Text](https://platzi.com/javascript-jquery-febrero-2015/tutoriales/automatizar-jade-y-stylus-con-sublime-text-23/)

	* **jjuanleyva** (1)

		
		Alguna idea de como hacerlo en VScode?

	* **Hdas** (1)

		
		buen apunte

* **Jonatan David Padilla** (2)

	
	Excelente, vamos con toda!!  
	[Aqui](https://abalozz.es/que-es-un-preprocesador-de-css/) Un enlace para que se informen sobre la lista de preprocesadores y su importancia.

	* **Hdas** (1)

		
		Muchas gracias por la información

* **Gerardo Ruiz** (1)

	
	Es muy bueno este profe. Me ayudó mucho con sass 😄

* **Leonidas Esteban Gonzalez** (1)
Test de comentario

* **Juan Carlos Felizzola Vega** (1)

	
	¡Comencemos con el primer preprocesador!

* **esdraspavon** (0)

	
	Manos a la obra! 💪

## 0020. Introducción a Stylus

### Descripción:


Hola soy Daniel Martínez @Wakkos y seré tu profesor en este curso de Stylus.  
Veremos su sintaxis y lo robusto que es comparado con otros preprocesadores.

Recuerda que tenemos los cursos de Sass y Less aquí en Platzi.

### Comentarios:

* **Juan Carlos Felizzola Vega** (6)

	
	¿Platzi usa Stylus?

	* **Diego Alexander Forero Higuera (Platzi)** (9)

		
		Si, en Platzi usamos stylus como preprocesador css

	* **ivan_acg** (4)

		
		¿Porqué? @GOLLUM23

	* **Jordy Kevin Tirado Torres** (1)

		
		cual es la mayor diferencia entre stylus y sass??  
		y cuando utilizar uno o el otro.?

	* **Juan Carlos Felizzola Vega** (1)

		
		Jordy, es de gustos. En este caso es la forma en la cual Stylus o Sass se acomode a la forma en que programas

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		stylus tiene una sintaxis muy parecida a python, no requiere `;`, o `{}` para delimitar los bloques de código, los bloques se delimitan con identación, es muy parecido a escribir python.

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		@JordyKevin sass por ejemplo si tienes que usar los `:` para separar la propiedad del valor, en stylus no, sass puedes compilarlo usando ruby sin necesidad de tener node, para stylus si o si necesitas node. Al final del día es cuestión de gustos.

## 0030. Compilación e instalación

### Descripción:


Como saben el uso de un preprocesador es una herramienta que nos sirve para compilar el código que creamos.  
En esta clase te enseño a instalar Stylus.

**Recuerden:** Stylus no usa Ruby como backend sino NodeJS.

### Links:

* [CodeKit - THE Mac App for Web Developers](https://codekitapp.com/)

### Comentarios:

* **Stuard Gerardo Carrillo Gonzalez** (13)

	
	## Stylus
	
	## Introducción al curso
	
	Stylus es un pre-procesador de css. Lo que quire decir que este código se copila para luego guardarlo en un archivo CSS. Por lo tanto se traduce del lenguaje de Stylus al lenguaje de CSS.
	
	Stylus trabaja con NodeJS
	
	## UI/Copiladores
	
	**[Codekit](https://codekitapp.com/) \- Trial|$34**
	
	> macOS
	
	Build websites faster and better
	
	Sass, Less, Stylus, CSS, CoffeeScript, Pug, Slim, Haml, TypeScript, JavaScript, ES6, Markdown, JSON, SVG, PNG, GIF and JPEG
	
	**Características**
	
	  * Refrescar automáticamente los navegadores
	  * Cualquier dispositivo
	  * No requiere mucha/ninguna configuración
	  * Optimizacion y Minificacion
	  * Instalación de Frameworks
	  * Debuger
	
	
	
	**[Prepos](https://prepros.io/) \- Trial|$29**
	
	> Mac, Windows & Linux
	
	Compile Sass, Less, Stylus, Jade, CoffeeScript on Mac, Windows & Linux with Live Browser Reload
	
	Sass, Less, Stylus, Cssnext, Jade/Pug, Markdown, Slim, Coffeescript etc.
	
	**Características**
	
	  * Debuger
	  * Refrescar automáticamente los navegadores
	  * Optimizacion y Minificacion
	  * Prevista desde la red para distintos dispositivos
	  * Inspector remoto
	  * Temas claros y oscuros
	
	
	
	**[Webpack](https://platzi.com/clases/webpack/)**
	
	> Mac, Windows & Linux
	
	Puedes copilarlo utilizando webpack. Lo único que requiere es que lo configures. En Platzi tiene un curso de webpack el cual enseñan a configurar webpack y también como utilizarlo con Stylus y demas pre/post-procesadores de estilos.
	
	## Projecto _[PlatziMusic]-Stylus_
	
	Se recomienda **no** guardar los estilos en la raíz. En mi caso creare una carpeta `./src` para todos los archivos “Fuentes” que utilize mi proyecto y una carpeta interna `./src/styles` para guardar los estilos no procesados. Tambien voy a requerir una carpeta `dist/css` para los output(los archivos finales).
	
	Ahora crearemos el primer archivo en `./src/styles`
	
	> Deberías configurar el output de tu archivo. Eso dependera de tu UI. En mi caso sera `./dist/css`
	
	_styles.styl_
	``` 
	    body
	      color: red
	    
	```
	
	_[output]/styles.css_
	``` 
	    body{color:#f00}
	    
	```

	* **Kevin Chipana Chucare** (1)

		
		Genial, gracias

	* **Hdas** (1)

		
		Muchas gracias

* **Ana Lima (Platzi)** (8)

	
	Aquí el link para Prepros
	
	<https://prepros.io/>
	
	Prepros puede compilar casi todos los preprocesadores como Sass, Less, Stylus, Cssnext, Jade/Pug, Markdown, Slim, Coffeescript etc

	* **Oscar Barajas Tavares (Platzi)** (1)
Me gusta más codekit

	* **Hdas** (1)

		
		Muchas gracias

* **Jonatan David Padilla** (3)

	
	Umm… al parecer con sintaxis mas facil nos vuelve la vida mas facil.
	
	…me comienzan a gustar mucho los preprocesadores.
	
	Si eres usuario Windows descarga prepros [aqui](https://prepros.io/)

	* **Hdas** (1)

		
		Muchas gracias

* **Abdías Estrada** (2)

	
	En este [enlace](https://webdesign.tutsplus.com/articles/why-i-choose-stylus-and-you-should-too--webdesign-18412) hay un guía corta para usar Stylus con Grunt y Bower. Deberan descargar el archivo adjunto StylusCompiler.zip

* **Efrén Martínez Rodríguez** (1)

	
	Siempre uso la Codepen para las practicas de este curso.

* **Juan  Reyes** (1)

	
	❤️ love stylus nodejs

* **hotarray** (1)

	
	Cheeee, me tardé más de media hora queriendo instalar prepos en gnu/linux/fedora… tuve un error de dependencias.

	* **hotarray** (0)

		
		pero ahora todo bien

* **jimmy-alexander-castiblanco-bu** (1)
Tengo una duda cuando creo mi archivo styles.styl Automáticamente me lo crea como Stylez.styl.txt Como un archivo de texto alguien me pu...

	* **Camilo Alexander Velandia Velandia** (1)

		
		no es normal, debes configurarlo en codekit o prepros

* **Wilder Lizama** (0)

	
	Si alguno trabaja sobre Linux y usa **Gulp** para compilar instalar [gulp-stylus](https://www.npmjs.com/package/gulp-stylus)`npm install --save-dev gulp-stylus`

* **Juan Carlos Felizzola Vega** (0)

	
	CodeKit, Prepros y otros… además de agregarnos un --watch, también nos da la posibilidad de probar de forma local nuestro proyectos en otros dispositivos.

# Cómo funciona Stylus

## 0040. Sintaxis

### Descripción:


 **Datos importantes:**

  * Stylus es un preprocesador que difiere un poco del resto por su sintaxis.
  * Su sintaxis es anidada.
  * En Stylus no es necesario usar los brackets y ; pero debemos recordar que para tener mejores prácticas deberíamos usarlas.



### Comentarios:

* **Stuard Gerardo Carrillo Gonzalez** (4)

	
	## Cómo funciona Stylus
	
	En stylus no requeriremos el uso de
	
	**{ … }**
	
	_css_
	``` 
	    body {
	      background: #lightyellow;
	    }
	    
	```
	
	_stylus_
	``` 
	    body
	      background: lightyellow
	    
	```
	
	**punto y coma**  
	_css_
	``` 
	    body {
	      background: #ffffe0;
	      color: #2c2c2c;
	    }
	    
	```
	
	_stylus_
	``` 
	    body
	      background: lightyellow
	      color: #2c2c2c
	    
	```
	
	**la coma**  
	_css_
	``` 
	    body,
	    .light-theme {
	      background: #ffffe0;
	      color: #2c2c2c;
	    }
	    body.header,
	    .light-theme.header {
	      font-family: monospace;
	    }
	    
	```
	
	_stylus_
	``` 
	    body
	    .light-theme
	      background: lightyellow
	      color: #2c2c2c
	      .header
	        font-family: monospace
	    
	```

	* **Víctor Julián González Estrada** (1)

		
		yo incluso si lo uso sin :, para mi es mucho mas comodo y no me confunde.
		``` 
		    body
		    	.light-theme
		    		background lightyellow
		                    color#2c2c2c
		                    .header
		    			font-family monoscape```
		    
		```

	* **Víctor Julián González Estrada** (0)

		
		me quedo ahi mal la identación, pero si me explicque?

	* **Hdas** (1)

		
		Que buena información

* **Ana Lima (Platzi)** (4)

	
	Recuerda que utilizar las {} y ; es buena práctica. Sin embargo, este preprocesador los colocará automáticamente, entonces no será necesario escribirlos en este curso.

	* **Leonidas Esteban Gonzalez** (10)

		
		En preprocesadores está regla no se cumple, una de las bondades principales de stylus es la no necesidad de usar : ; {} pero es tan cool que si usas alguno de estos elementos o todos juntos stylus seguirá haciendo bien su trabajo

	* **Yomar Esteban Miranda Sarmiento** (0)

		
		Es muy cierto lo que dice Leonidas, una de las grandes ventajas de Stylus.

	* **Juan Carlos Felizzola Vega** (0)

		
		Me parece muy bien no usarlos.  
		Me estoy acostumbrando a Python

	* **Hdas** (1)

		
		Bastante útil esta herramienta

* **deveeup** (3)

	
	los " : " también se pueden omitir…

	* **Hdas** (1)

		
		Gracias

* **jose-morales-varon** (2)

	
	De las sintaxis más sencilla que puede existir

* **Camilo Alexander Velandia Velandia** (1)

	
	es genial el uso de stylus

## 0050. Anidaciones

### Descripción:


Gracias a las anidaciones podemos añadir propiedades a través de la sintaxis de Stylus. Además, esto nos permite referenciar al padre.

### Comentarios:

* **Stuard Gerardo Carrillo Gonzalez** (11)

	
	## Anidaciones
	
	Con stylus tenemos acceso a hacer anidaciones interesantes.
	
	_sub_
	
	> Hacemos referencia a todos los elementos que estén dentro de las etiquetas padres
	``` 
	    body, .light-theme
	      background lightyellow
	      color#2c2c2c
	    
	      .primer-hijo
	        margin-bottom24px
	    
	```
	
	_child_
	
	> Con el uso de “>” hacemos referencia a los hijos directos del elemento padre
	``` 
	    body, .light-theme
	      background lightyellow
	      color#2c2c2c
	    
	      > .primer-hijo
	        margin-bottom24px
	    
	```
	
	_reference_
	
	> Con el uso de “&” hacemos referencia al nombre del elemento padre
	``` 
	    .psudoe-element
	      width300px
	    
	      &:before
	        content'hola'
	      
	      .ie-8 &
	        &:before
	          content'ciao'
	    
	```
	
	> **NOTA:** No anidar mas de 3 veces
	
	_ejemplo de modulación_
	``` 
	    .btn
	      background white
	      color black
	      border-radius3px
	    
	      &-alert
	        background red
	        color white
	    
	      &-warn
	        background orange
	        color white
	    
	```

	* **Hdas** (1)

		
		Muchas gracias pro tu aporte que buena información

	* **Nathaly Stefani Riaño Bejarano** (1)

		
		Gran resumen! 👌

* **Jhon Alexander Perez Valencia** (3)

	
	> hasta el momento la sintaxis de **Stylus** es igual a la de **SASS**

	* **Freddy Córdova Arana** (1)

		
		es verdad

	* **ricardo-cuan** (1)

		
		en Stylus puedes no usar llaves, dos puntos y los punto y coma
		
		Haciéndolos muy similar a Python

* **LuisDark123** (3)

	
	Las anidaciones son una herramienta super útil.  
	Un ejemplo en el que yo vi el uso de las anidaciones es la creacion del menu de navegacion.
	``` 
	    header
	    	width100%
	    	& nav
	    		float right;
	    		& ul
	    			padding10px
	    
	```

	* **Hdas** (1)

		
		Buen dato

* **Yomar Esteban Miranda Sarmiento** (3)

	
	Cabe destacar que no es necesario usar : ; {}
	``` 
	    .pseudoelement
	    	width 300px
	    	&:before
	    		content"Hola Mundo!"
	    	.ie-8 &
	    		&:before
	    			content 'Good Bye'
	    
	    body
	    	background teal
	    	font-size .9em	
	    	.primerhijo
	    		margin-bottom 24px
	    	> .primerhijo
	    		font-size 18px
	    		
	    .btn
	    	border-radius 5px
	    	&--alert
	    		background red
	    
	```

	* **Hdas** (1)

		
		Gracias

* **Davermx** (2)

	
	Hola compañeros, pues al parecer yo me confundi un poco con todo el procedimiento, quiero pensar que solo fui yo. la verdad me confundio un poco el saber que usar, es decir usar visual studio code. o prepros. tambien me confundio si se podia utilizar visual code. para procesar los archivos stylus. no critico pero concidero que no fue muy claro wakkos en ese sentido. “ojo” , no estoy criticando solo pienso que me confundio un poco. si no estoy mal, el procedimiento es el siguiente, por favor corrijanme si estoy mal.
	
	1.- se usa ide, visual code, atom, sublime, etc. para crear archivos estandar, html, carpetas etc. para el proyecto.
	
	2.- se usa prepros solo para generar el archivo styl, el cual crear el archivo css normal que usa el index.
	
	cabe comentar que al crear el ejercicio de wakkos, en visual studio, tuve que descargar un pluggin para poder crear archivos styl. tambien que al momento de guardar el ejercicio me marco un error por no poner {}. tenia que ponerlas si no , no me dejaba guardar, una vez guardado se crea el archivo stylus. ya minificado. la verdad no me aparecio como se muestra con wakkos.
	
	agradeceria la retroalimentacion compañeros, saludos y espero que sirva el comentario para algun compañero que le paso lo mismo.

	* **carlosmora_biz** (1)

		
		Hola. Puede ser un tema de gustos. Como lo indicas es viable, pero personalmente no soy amigo de tener que abrir varias herramientas para hacer algo que saldria listo por comandos.
		
		La opcion que yo uso es usar vscode para editar y tener un proceso en linea de comandos monitoreando el archivo .styl por medio de stylus (paquete de nodejs) para compilarlo cada vez que guarde y enviar el resultado al .css.
		
		saludos

* **Andrés Campuzano Garzón** (1)

	
	Esta interesante para proyectos pequeños/medianos.

	* **Mackial Houng** (1)

		
		Que recomiendas para los proyectos grandes?

* **Sebastian Gutierrez** (1)

	
	Buenos dias
	
	tengo una pregunta alguien sabe en vscode como puedo arreglar este pequeño problemilla  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-8c38cefd-93e4-4104-a676-4433312d2618.jpg)

	* **Eric Rodríguez Gallegos** (1)

		
		Tengo el mismo problema, ojala alguien pueda ayudar. Saludos.

	* **Norma Constanza Giraldo Reyes** (5)

		
		A mi me pasó lo mismo y estaba usando Prepross para compilar, con lo cual lo único que hay que hacer es quitarle el check a la opción Minify css. Ya que lo que está haciendo es simplificar el css.

* **youcan** (1)

	
	Anidaciones (Nesting) son un recurso muy útil, sin embargo puede causarnos problemas si anidamos muchos elementos ya que puede comprometer la reusabilidad.

	* **Hdas** (1)

		
		Buen dato

* **Jonatan David Padilla** (1)

	
	Las identaciones nos ayudan a tener el mismo resultado pero con menos lineas codigo.

	* **Hdas** (1)

		
		Bastante útil

* **Emmanuel García** (1)
¿Cuándo puedo saber que es una buena idea anidar y cuándo no?.

	* **Erik Ochoa (Platzi)** (1)

		
		Eso te lo da la práctica, como consejo: yo no me pasaría de tres niveles de anidación.

* **Juan Carlos Felizzola Vega** (0)

	
	Para referenciar al padre usamos `&`

## 0060. Reto Instalación con Grunt

### Descripción:


### Comentarios:

* **hnavarrete** (9)

	
	 **Instalar con npm:**
	``` 
	    npm install -g stylus
	    
	```
	
	Verificar si se instalo correctamente revisando la versión:
	``` 
	    stylus -V
	    
	```
	
	Desde la terminal nos colocamos sobre la carpeta en donde tenemos nuestro archivo de Stylus, en este caso llamado **styles.styl **y ejecutamos el siguiente comando:
	``` 
	    stylus -w styles.styl -o ../css/
	    
	```
	
	  * Con la **-w** le agregamos un watcher para que detecte al hacer cambios en el archivo especificado.
	
	  * Con la **-o** le indicamos la ruta de salida (output) para nuestro archivo .css
	
	
	

	* **Hdas** (1)

		
		Buen aporte

	* **Jhon Alexander Perez Valencia** (1)

		
		muy buen aporte

	* **EdwFabMar** (1)

		
		Buen aporte

	* **Andrés Campuzano Garzón** (1)

		
		Esto tambien sirve para Sass?

	* **Emmanuel García** (1)

		
		Excelente aporte. Por si alguien tiene un error sobre los permisos de escritura al momento de instalar “npm install -g stylus” (sirve para otros módulos) simplemente tienen que ejecutar
		``` 
		    sudo chown -R $USER /usr/local/lib/node_modules
		    
		```
		
		Pd: Uso Mac

* **Stuard Gerardo Carrillo Gonzalez** (6)

	
	## Stylus Webpack
	
	_package.json_
	``` 
	    "scripts": {
	      "build": "webpack --mode development",
	      "build:dev": "webpack --watch --mode development",
	      "build:prod": "webpack --mode production"
	    },
	    ...
	    "devDependencies": {
	      "css-loader": "^0.28.10",
	      "extract-text-webpack-plugin": "^4.0.0-beta.0",
	      "style-loader": "^0.20.2",
	      "stylus": "^0.54.5",
	      "stylus-loader": "^3.0.2",
	      "webpack": "^4.1.1",
	      "webpack-cli": "^2.0.10"
	    }
	    
	```
	
	_index.js_
	``` 
	    import '../styles/styles.styl'
	    
	    console.log("styles loaded")
	    
	```
	
	_styles.styl_
	``` 
	    .btn
	      background white
	      color black
	      border-radius3px
	    
	      &-alert
	        background red
	        color white
	    
	      &-warn
	        background orange
	        color white
	    
	      &-info
	        background lightblue
	        color white
	        
	    
	```
	
	_webpack.config.js_
	``` 
	    const path = require('path')
	    const ExtractTextPlugin = require('extract-text-webpack-plugin')
	    
	    module.exports = {
	      entry: path.resolve(__dirname, 'src/js/index.js'),
	      output: {
	        path: path.resolve(__dirname, 'dist/js'),
	        filename: "index.js"
	      },
	      module: {
	        rules: [
	          {
	            test: /\.styl$/,
	            use: ExtractTextPlugin.extract({
	              fallback: "style-loader",
	              use: [
	                'css-loader',
	                'stylus-loader'
	              ]
	            })
	          }
	        ]
	      },
	      plugins: [
	        new ExtractTextPlugin("stylesWP/styles.css")
	      ]
	    }
	    
	```

	* **eddyarellanes** (0)

		
		Buen aporte! 😃

	* **Hdas** (1)

		
		Buen aporte

	* **Jhon Alexander Perez Valencia** (1)

		
		muy buen aporte, 😃

* **CarlosAlba** (2)

	
	Hola a todos!  
	Realmente fue complicado para mi hacer esto por que jamás habia tocado node ni nada de eso, pero a la vez fue muy emocionante.  
	Les invito a leer y practicar este [tutorial](https://webdesign.tutsplus.com/series/the-command-line-for-web-design--cms-777), esta en ingles y en otros idiomas, no basta con leer es necesario probar y practicar hasta dominarlo.

* **Rafael Guillermo Rodriguez Garcia** (1)

	
	por la consola:
	``` 
	    stylus -w -o ../public/css app.styl
	    
	```
	
	-w es el watched  
	-o es el directorio donde quiero el css

	* **Hdas** (1)

		
		Buen aporte

# Herramientas de Stylus

## 0070. Variables

### Descripción:


Una de las mayores ventajas que tienen los preprocesadores son las variables, estas nos permiten controlar un entorno porque podemos manipular un entorno. Esto quiere decir que podemos cambiar muchas cosas a través de muchas variables.

### Comentarios:

* **Stuard Gerardo Carrillo Gonzalez** (5)

	
	_styles.styl_
	``` 
	    // Variables
	    font-size-normal = 18px
	    font-size-small = font-size-normal - 2px
	    font-size-paragraph = font-size-normal
	    
	    // Texts
	    p
	      font-sizefont-size-paragraph
	    
	    span
	      font-sizefont-size-normal
	    
	      &.small
	        font-sizefont-size-small
	    
	```

* **Gaston Morales** (4)

	
	Muy útiles las variables, ahorran mucho código y es mas ordenada para trabajar

* **Juan Carlos Felizzola Vega** (3)

	
	Para declarar una variable
	``` 
	    nombre_variable = valor_variable
	    
	```

	* **Hdas** (1)

		
		Muchas gracias

* **jose-morales-varon** (2)

	
	Dios bendiga a las Variables

* **cascharly** (2)

	
	Como se escapa un variable?

	* **davidtoca (Platzi)** (4)

		
		Con la funcion unquote, por ejemplo imagina que quieres usar sans-serif como un string solamente, entonces harias:
		``` 
		    unquote("sans-serif")
		    
		```

	* **Hdas** (1)

		
		Gracias

* **Rafael Alvarez Cardona** (1)

	
	Stylus es amor puro ❤️

* **JasoSalgado** (1)

	
	Muy útiles las variables.

	* **Hdas** (1)

		
		Versátiles y ahorran mucho código

* **LuisDark123** (0)

	
	En mi codigo declaro la variable color_theme para aplicar un color a todos los contenidos que quiero pero no se visualiza el color en mi pagina a pesar que el css si cambio. ¿Debo de configurar algo?  
	¿O esta mal el codigo?
	
	Stylus
	``` 
	    color_theme = background black
	    
	    body
	      background color_theme
	      
	    .box
	        background color_theme
	        &--light
	            background color_theme
	    
	```
	
	Css
	``` 
	    body{background:background #000}.box{background:background #000}.box--light{background:background #000}
	    
	```

	* **davidtoca (Platzi)** (3)

		
		define color_theme solo como black, asi:
		``` 
		    color_theme = black
		    
		```
		
		porque como lo tienes actualmente se reemplazaria así:
		``` 
		    background: background black
		    
		```

	* **LuisDark123** (0)

		
		Gracias davidtoca

	* **Hdas** (1)

		
		no es necesario agregar la propiedad esta se define cuando sea necesario, la variable corresponde al valor correspondiente que tomara esta al determinar a que propiedad afectara.

## 0080. Estructura de CSS y propuesta de reto

### Descripción:


Una de las ventajas de los preprocesadores es que podemos crear diferentes parciales para organizar nuestro código. Cuando creamos un parcial debemos tener un _, lo que quiere decir que debe ser importado en un archivo principal.

### Comentarios:

* **Juan Carlos Felizzola Vega** (7)

	
	Los archivos que tiene un `_` no se compila.  
	Para importar archivos usamos `@import "_nombre_archivo"`

* **Hdas** (4)

	
	Estructura de CSS
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-ad00cd33-b603-4cbe-8191-8a266f025273.jpg)

* **Jonatan David Padilla** (4)

	
	Las variables son geniales, se evita mucho tener que leer el codigo nuevamente para buscar el color o anotarlo en algun lado.
	
	me gusta mucho el hecho de que puedo poner el nombre que me plasca y utilizarolo durante todo el codigo.
	
	variables que serian muy comunes:
	``` 
	    font-big =  20px
	        font-little = 10px
	        font-title = 30px
	    
	        principal-color = #244355
	        second-color = #8BC73A
	    
	        circulos = 50%
	        
	    
	```
	
	Que otras ideas se les pasa al momento de poder crear varables?

	* **Hdas** (1)

		
		Que buen aporte muchas gracias

* **LuisDark123** (3)

	
	¿En la carga del sitio afectaria tener muchos archivos de variables?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Al compilar stylus puedes tener solo un archivo de salida por lo tanto no va a dar problema, si tienes muchos archivos css, si afecta ya que es necesario hacer más peticiones para traer todos los archivos.

	* **Giorgio Ventura** (2)

		
		Sumando el aporte de GOLLUM23, es por ese motivo que parcializamos _archivo.styl, para evitar compilaciones de más!

* **Gabriel Alejandro Delgado Álvarez** (2)

	
	![](![RETO2.png](https://static.platzi.com/media/user_upload/RETO2-c05c3aac-14e8-42c4-b6a3-5d2b82f37f20.jpg)

* **Emmanuel García** (1)

	
	Este es un ejemplo un poco más completo de como estructurar tu proyecto, espero que les sirva.  
	styles/  
	|  
	|– abstracts/ (or utilities/)  
	| |– _variables.scss // Sass Variables  
	| |– _functions.scss // Sass Functions  
	| |– _mixins.scss // Sass Mixins  
	|  
	|– base/  
	| |– _reset.scss // Reset/normalize  
	| |– _typography.scss // Typography rules  
	|  
	|– components/ (or modules/)  
	| |– _buttons.scss // Buttons  
	| |– _carousel.scss // Carousel  
	| |– _slider.scss // Slider  
	|  
	|– layout/  
	| |– _navigation.scss // Navigation  
	| |– _grid.scss // Grid system  
	| |– _header.scss // Header  
	| |– _footer.scss // Footer  
	| |– _sidebar.scss // Sidebar  
	| |– _forms.scss // Forms  
	|  
	|– pages/  
	| |– _home.scss // Home specific styles  
	| |– _about.scss // About specific styles  
	| |– _contact.scss // Contact specific styles  
	|  
	|– themes/  
	| |– _theme.scss // Default theme  
	| |– _admin.scss // Admin theme  
	|  
	|– vendors/  
	| |– _bootstrap.scss // Bootstrap  
	| |– _jquery-ui.scss // jQuery UI  
	|  
	`– main.scss // Main Sass file

* **J Michael Hernández González** (1)
![](https://scontent.feoh6-1.fna.fbcdn.net/v/t1.15752-0/p280x280/78303946_533475467508396_8320893373812572160_n.png?_nc_cat=110&_nc_ohc=UMHHO-eOdTQAQmZq_cTuqlVKuYVEKTJFdOdngLJypaC5hR7mUXRdvXzAQ&_nc_ht=scontent.feoh6-1.fna&oh=69041bc3050384f8b7bf56e83083c230&oe=5E83B288)

* **Felipoch** (1)
¿Es posible organizar los parciales de la misma forma como se organiza en Sass? sass/ | |– utilities/ | |– _variables.sass // Variab...

* **LuisDark123** (1)
¿En la carga del sitio afectaria tener muchos archivos de variables?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Al compilar stylus puedes tener solo un archivo de salida por lo tanto no va a dar problema, si tienes muchos archivos css, si afecta ya que es necesario hacer más peticiones para traer todos los archivos.

* **ivan_acg** (0)

	
	Buen tip

## 0090. Solución del reto y añadir HTML

### Descripción:


Resolución del reto: En esta clase te muestro cómo solucionar el reto que te propuse en la clase anterior. Además, te mostraré cómo usar HTML en nuestro archivo.

### Comentarios:

* **Juan Carlos Felizzola Vega** (18)

	
	Archivos vistos en clase:
	
	style.styl
	``` 
	    @import"lib/_variables.styl"
	    @import"lib/_mixins.styl"
	    @import"lib/_functions.styl"
	    
	    @import"layout/_site.styl"
	    @import"layout/_blocks.styl"
	    
	    @import"base/_links.styl"
	    @import"base/_buttons.styl"
	    @import"base/_typography.styl"
	    @import"base/_tables.styl"
	    
	    @import"components/_grid.styl"
	    @import"components/_utilities.styl"
	    
	```
	
	_site.styl
	``` 
	    html
	      background: color-backgroud
	      font-size: 87.5%
	      -webkit-overflow-scrolling: touch
	      -webkit-tap-highlight-color: transparent
	      -webkit-text-size-adjust: 100%
	      -ms-text-size-adjust: 100%
	    
	    
	    body
	      margin: 0
	      padding: 0
	      width: 100%
	      background-color: transparent
	      font-family basefont
	      line-height: lineheight
	      color: textcolor
	    
	```
	
	_blocks.styl
	``` 
	    .block
	      max-width: 60%
	      margin-right auto
	      margin-left auto
	      margin-bottom: padding
	      background-color: color-white
	      position: relative
	      &__body
	        padding: padding 
	        background-color: color-white
	        position: relative
	      
	      &_title
	        background-color: color-white
	        padding: padding
	        font-size: 28px
	        font-weight: bold
	        color: color-secondary
	        border-bottom 1px solid color-lightgrey
	    
	```
	
	_buttons.styl
	``` 
	    .btn
	      display inline-block
	      width auto
	      line-height2.5
	      color buttoncolor
	      text-align center
	      vertical-align middle
	      white-space nowrap
	      background-color buttonbackground
	      cursor pointer
	      margin-left 0
	      margin-top 0
	      margin-right 0
	      margin-bottom 0
	      padding-top 0
	      padding-bottom 0
	      padding-right 2.2em
	      padding-left 2.2em
	      text-transform uppercase
	      text-decoration none
	      font-size basefontsize 
	      font-weight bold
	      letter-spacing .05em
	      border-radius0
	      transition all .2s ease-in
	      border none
	      &:hover
	        text-decoration none
	        color white
	        background-colorcolor-brand
	        cursor pointer
	    
	      &:active,
	      &:focus
	        outline: none
	    
	      /*
	      ** Secondary buttons
	      */
	    
	      &.btn--secondary
	        background-color white
	        colorcolor-brand
	        &:hover
	          background-colorcolor-brand
	          color: white
	    
	      /*
	      ** Disable buttons
	      */
	      
	      &.btn--disable
	        cursor not-allowed
	        background-color grey
	        color white
	        border-color gray
	        &.:visited
	          background-color grey
	          color: grey
	    
	        &:hover
	          cursor not-allowed
	          color white
	          background-color grey
	          border-color darken(grey, 10)
	    
	      /*
	      ** Error buttons
	      */
	      
	      &.btn--error, .btn--error:visited
	        colorcolor-error
	        border-color lightgray
	        &:hover
	          background-colorcolor-error
	          color white
	    
	      /*
	      ** Warning buttons
	      */
	    
	      &.btn--info, btn--info:visited
	        colorcolor-brand
	        border-colorcolor-brand
	        &:hover
	          background-colorcolor-brand
	          color white
	    
	```
	
	_variables.styl
	``` 
	    /*
	      Colors
	    **
	      Branding colors
	    */
	    
	    color-brand = #ea83ee
	    color-secondary = rgb(219, 216, 121)
	    
	    color-black = rgb(0,0,0)
	    color-darkgrey = #4D4D4D
	    color-grey = #737373
	    color-lightgrey = #BFBFBF
	    color-white = rgb(255, 255, 255)
	    
	    color-border = color-darkgrey
	    
	    //Texturas
	    color-alert = rgb(252, 228, 207)
	    color-error = rgb(218, 79, 73)
	    color-invert = invert(color-error)
	    color-info = rgb(66, 184, 221)
	    color-success = rgb(91, 183, 91)
	    
	    // Tipografia
	    basefont = 'Quicksand', sans-serif
	    basefontsize = 16px
	    baseheadingfont = basefont
	    baseheadingfontweight = bold
	    altfont = Georgia, Times, 'Times New Roman'
	    codefont = 'Courier New', monospace 
	    lineheight = 1.5
	    textcolor = color-blank
	    
	    button-color = color-white
	    button-background = color-brand
	    color-brackground = color-white
	    
	    // Constantes
	    border-radius = 3px
	    padding = 24px
	    page-max-width = 800px
	    
	    img-dir = '/img'
	    
	```

	* **EYALICO** (1)

		
		gracias por el aporte

	* **Hdas** (1)

		
		Que buen aporte muchas gracias

	* **EdwFabMar** (1)

		
		Muy buen aporte

	* **gydoar** (1)

		
		Falto fue el index.html para visualizar bien

	* **Alexander Ramirez Tobon** (1)

		
		gracias

* **Ana Lima (Platzi)** (5)

	
	Estaría muy genial que subieran esos archivos a la plataforma para poder visualizarlos bien.

	* **Yomar Esteban Miranda Sarmiento** (0)

		
		Al igual que tu estoy esperando a que suban los archivos a algún repositorio o al sistema.

	* **Yomar Esteban Miranda Sarmiento** (2)

		
		Acabo de avanzar a la siguiente clase y me dí cuenta que allí se encuentran los archivos, cuando quieras puedes entrar a revisar.

	* **Ana Lima (Platzi)** (1)

		
		Muchas gracias Yomar, no lo había notado!

	* **Hdas** (1)

		
		Muchas gracias

* **Karina Betzabe Romero Ulloa** (2)

	
	Comparto la solución a la que llegué. Saludos.
	
	\-------------------------VARIABLES ----------------------------------
	
	font-family-base: “Ubuntu”, sans-serif  
	font-family-header: “Roboto”, Arial
	
	font-size-small = 16px  
	font-size-normal = 25px  
	font-size-big = 60px
	
	color-brand: #ffffff  
	color-primary: #000000  
	color-secondary: #BFBFBF
	
	color-alert: yellow  
	color-warning: red
	
	margin: 1em  
	padding: 1em  
	border-radius: 5px
	
	\-------------------------ARCHIVOS ----------------------------------
	
	@import “lib/_variables.styl”  
	@import “lib/_mixins.styl”  
	@import “lib/_functions.styl”
	
	@import “elements/_buttons.styl”  
	@import “elements/_fonts.styl”  
	@import “elements/_inputs.styl”
	
	@import “layout/_cards.styl”  
	@import “layout/_layout.styl”

	* **Hdas** (2)

		
		buen aporte gracias

* **Gabriel Alejandro Delgado Álvarez** (1)

	
	Vine al curso de Stylus justo despues de terminar el curso de Sass, y si bien no es algo super importante que nos muestre el codigo HTML que escribio y los avances que escribio en el Preprocesador y se compilaron, siempre se agradece, porque al pasar de una clase a otra y ver todo eso, y que la clase se base en algo que simplemente apareció, te deja algo perdido. Y pues ya es la segunda vez ;v

* **czabala847** (1)

	
	Los media queries tambien deberian estar en un parcial aparte?

	* **Edward Steven Ramos Palacios** (2)

		
		Desde mi experiencia te aconsejo que no. Siempre es bueno mantenerlas en el mismo file de las clases que quieres modificar.

* **gydoar** (1)
Donde podemos encontrar el repositorio con los archivos completos.

	* **wilson_romero** (2)

		
		<https://github.com/Wakkos/StyleGuide-PlatziMusic.git>

* **czabala847** (1)
Los media queries tambien deberian estar en un parcial aparte?

	* **Edward Steven Ramos Palacios** (2)

		
		Desde mi experiencia te aconsejo que no. Siempre es bueno mantenerlas en el mismo file de las clases que quieres modificar.

## 0100. Mixins

### Descripción:


Vamos a ver Mixins para mostrarte cómo podemos este preprocesador nos permite crecer las clases. Los mixins son declarados a través de nombres. Es importante que siempre añadamos el prefijo Mixin maxwidth.

### Comentarios:

* **Juan Carlos Felizzola Vega** (6)

	
	Un mixin nos permite reutilizar valores dentro del mismo CSS  
	Se declara facilmente con su nombre, y como buena práctica usamos `minix-` antes del nombre que queremos darle
	``` 
	    mixin-max-width():
	    	max-widthwidth
	    	margin-left auto
	    	margin-right auto
	    
	```
	
	Y se aplica de la siguiente forma:
	``` 
	    .container
	      mixin-max-width()
	    
	```

	* **CarlosAlba** (2)

		
		Yo intente cambiar el:
		``` 
		    margin-left: auto
		    margin-right: auto
		    
		```
		
		por un:
		``` 
		    margin: 0auto 
		    
		```
		
		y funciona perfecto

	* **Hdas** (1)

		
		Muchas gracias que buen aporte

* **Jonatan David Padilla** (4)

	
	Es importante nombrar a los **mixins** diferente a los nombres de la propiedades de CSS

	* **CarlosAlba** (1)

		
		Excelente recomendacion eso evitaria complicaciones y/o confisiones

	* **Hdas** (1)

		
		que buen dato para tener en cuenta siempre

* **Jonatan David Padilla** (2)

	
	Otro ejemplo diferente al compañero anterior con el uso de **mixins**
	
	De la siguiente manera declaro el mixin con su nombre y parametros
	``` 
	    anchura() 
	        display flex
	        justify-content: center
	        align-items: center
	        width300px
	        height300px
	        text-align center
	    
	```
	
	Y asi lo aplico a cualquier elemento
	``` 
	    .container
	        anchura()
	    
	    
	```

	* **Hdas** (1)

		
		Muchas gracias que buen aporte

* **Raul Contreras** (1)

	
	Creo que es mejor, antes que esto:
	``` 
	    mixin-max-width()
	        max-width: 800px
	        margin-left: auto
	        margin-right: auto
	    
	    .container
	        mixin-max-width()
	    .section
	        margin-bottom: 24px
	        mixin-max-width()
	        max-width: 600px
	    
	```
	
	Hacer esto…
	``` 
	    .container, .section
	        max-width: 800px
	        margin-left: auto
	        margin-right: auto
	    .section
	        max-width: 600px
	    
	```
	
	EL MAL USO DE LOS MIXINS PUEDE AUMENTAR, CONSIDERABLE E INNECESARIAMENTE EL TAMAÑO DEL ARCHIVO

## 0110. Mixins Paramétricos

### Descripción:


¿Cómo solucionamos que un diseñador quiera meter más información dentro de un solo mixin?  
No debemos hacer otro mixin, sino que podemos usar los mixin paramétricos. Aquí lo que debemos incluir son parámetros para que podamos guardar cierta información que es nueva dentro del mixin.

### Comentarios:

* **Juan Carlos Felizzola Vega** (6)

	
	Para dar parámetros a un mixin lo usamos dentro del paréntesis:
	``` 
	    mixin-max-width(width)
	      max-widthwidth
	      margin-left auto
	      margin-right auto
	    
	    .container
	      mixin-max-width(800px)
	    
	```
	
	Para usar valores por defecto igualamos el parametro al valor que queremos:
	``` 
	    page-max-width = 1024px
	    mixin-max-width(width = page-max-width)
	      mixin-max-width()
	      margin-left auto
	      margin-right auto
	    
	    .container
	      mixin-max-width(800px)
	    
	```

	* **Hdas** (1)

		
		Muchas gracias buen aporte

* **Ricardo Medina** (4)

	
	Excelente que en stylus podamos usar valores por defecto en nuestros mixins!
	
	Overview
	``` 
	    /*Declaramos una variable en nuestra sección de variables de proyecto*/
	    
	    page-max-width= 1024px
	    
	    /*Luego agregamos esa variable como valor por defecto del mixins*/
	    /*El mixin debe estar declarado en nuestro archivo de mixins*/
	    
	    mixin-max-width(width=page-max-width)
	      max-width:width
	      margin-left:auto
	      margin-right:auto
	    
	    /*Aplicando el mixin con valor por defecto*/
	    .container
	      mixin-max-width()
	    
	    /*Aplicando el mixin con valor custom*/
	    .section
	      mixin-max-width(90%)
	    
	```

	* **Hdas** (1)

		
		Muchas gracias buen aporte

* **Imderf** (3)

	
	 **También podemos igualar la variable con otra variable:**
	``` 
	    /*Declaramos una variable*/
	    
	    page-max-width= 1024px
	    
	    /*Luego agregamos esa variable como valor por defecto */
	    
	    mixin-max-width(width=page-max-width)
	      max-width:width
	      margin-left:auto
	      margin-right:auto
	    
	    /*Aplicando el mixin con valor por defecto*/
	    .container
	      mixin-max-width()
	    
	    /*Aplicando el mixin con el valor modificado*/
	    .section
	      mixin-max-width(90%)
	    
	```

	* **Hdas** (1)

		
		Muchas gracias buen aporte

## 0120. Funciones internas

### Descripción:


Vamos conocer cómo operan las funciones internas en Stylus.

### Links:

* [Functions — Stylus](http://stylus-lang.com/docs/functions.html)

### Comentarios:

* **ivan_acg** (6)

	
	_**Funciones internas**_
	
	En stylus podemos asignar variables dinamicas y asignarles funciones matematicas que ejecutaras cada que sean llamadas .
	
	Por ejemplo podremos utilizar la declaracion
	``` 
	    **padding : mixin-padding-small(2px)**
	    
	```
	
	Ubicada en la carpeta **site.styl**
	
	y pasarle la la función
	``` 
	    mixin-padding-small(a)
	    
	    	**a + padding**
	    
	```
	
	Ubicada en la carpeta **mixin.styl**
	
	Donde padding proviene de la carpeta ** _variables.styl**
	
	y equivale a :
	``` 
	    	**minipadding = padding / 2**
	```

	* **Kevin Chipana Chucare** (2)

		
		Graciass

	* **Hdas** (1)

		
		Muchas gracias buen resumen

	* **Juan Vicente Cordero** (1)

		
		Algo que no me queda claro de este aporte, los asteriscos ( ** ) que pintan en las declaraciones.

* **Juan Carlos Felizzola Vega** (4)

	
	Las definiciones de funciones aparecen idénticas a mixins; sin embargo, las funciones pueden devolver un valor.

	* **Hdas** (1)

		
		Gracias

* **Lenin Vladimir Felix Torres** (0)

	
	WoW, Primer Comentario!! Es muy Recomendable usar las funciones ya que nos ayudan muchisimo cuando queremos evitar el exceso de lineas dentro de la hoja de estilos!

	* **Hdas** (1)

		
		también hacen mas versátil el código y nos ahorra tiempo en al depuración

## 0130. Condicionales

### Descripción:


Stylus cuenta con condicionales if que vienen muy útiles a la hora de asegurarnos que algo tiene un valor y que se ejecute algo si eso se cumple.

### Comentarios:

* **LuisDark123** (5)

	
	Use una variable para sustituir el true y false para agilizar el cambio de tema modificando una sola vez todo. ¿Qué opinan?
	``` 
	    toggleTheme = true
	    
	    theme(themeSelected = toggleTheme)
	        if themeSelected
	        	background-color black
	        	color white
	        else
	        	background-color white
	        	color black
	    
	    .area
	    	theme()
	    
	```

* **Juan Carlos Felizzola Vega** (4)

	
	Los condicionales proporcionan flujo de control a un lenguaje que de otra manera es estático, proporcionando importaciones condicionales, mixins, funciones y más.

	* **Hdas** (1)

		
		Buen dato muchas gracias

* **Gustavo J. Arias** (4)

	
	Hola! una consulta, así como se puede usar IF/ELSE, también puedo usar el ELSE IF ?, además de eso, las variables siempre deben ser booleanas o también pueden ser de otro tipo ?
	
	Gracias 😃

	* **Yomar Esteban Miranda Sarmiento** (5)

		
		Si se puede usar ELSE IF, este ejemplo lo saqué de la documentación oficial de **stylus** :
		``` 
		    compare(a, b)
		      ifa > b
		        higher
		      elseifa < b
		        lower
		      else
		        equal
		    
		```
		
		Al parecer también puedes usar **Strings** para evaluar las condiciones, este ejemplo también está en la documentación oficial:
		``` 
		    stringish(val)
		       if val is a'string' or val is a'ident'
		         yes
		       else
		         no
		    
		```
		
		Te dejo el [Link](http://stylus-lang.com/docs/functions.html) de donde tome los ejemplos.

	* **Yomar Esteban Miranda Sarmiento** (1)

		
		Puedes ir directamente a la parte de **condicionales**[aquí](http://stylus-lang.com/docs/functions.html#conditionals)

	* **Hdas** (1)

		
		Muchas gracias que buen aporte

* **jangove** (1)

	
	else en background :white ;  
	el punto y coma va siempre o es error?

	* **Hdas** (1)

		
		no es necesario

## 0140. Directiva for

### Descripción:


### Comentarios:

* **Filiberto Santillán** (12)

	
	Escribí un tutorial aquí en la comunidad que espero les sea de gran ayuda.
	
	Conoce más sobre Stylus: datos útiles y otras características:
	
	<https://platzi.com/stylus/tutoriales/conoce-mas-datos-sobre-stylus-datos-utiles-y-otras-caracteristicas/>

	* **Hdas** (1)

		
		gracias

* **Yomar Esteban Miranda Sarmiento** (11)

	
	Aquí tengo un resumen que he venido realizando a lo largo del curso:  
	[Resumen Curso Stylus](https://github.com/yomar-dev/notas-stylus)

	* **LuisDark123** (2)

		
		Esta excelente. Me ayudo a linealizar los conocimientos adquiridos.

	* **Yomar Esteban Miranda Sarmiento** (1)

		
		Estamos para ayudarnos.

	* **Hdas** (1)

		
		que buen aporte muchas gracias

* **Imderf** (4)

	
	Esta directiva nos permite realizar ciclos para realizar un determinado número de veces.
	``` 
	    grid-size = (1..12)
	    
	    .grid
	    	display: flex
	    	flex-wrap: wrap
	    	position: relative
	    	flex-direction: row
	    	
	    [class^="grid--item"]
	    	flex-shrink: 0
	    	margin-right: 0
	    	flex-grow: 1
	    	
	    foriin grid-size
	    	.grid--item-{i}
	    		width: (100 / i) * 1%
	    
	```
	
	Resultado:
	``` 
	    .grid {
	      display: -webkit-box;
	      display: -ms-flexbox;
	      display: flex;
	      -ms-flex-wrap: wrap;
	      flex-wrap: wrap;
	      position: relative;
	      -webkit-box-orient: horizontal;
	      -webkit-box-direction: normal;
	      -ms-flex-direction: row;
	      flex-direction: row;
	    }
	    
	    [class^="grid--item"] {
	      -ms-flex-negative: 0;
	      flex-shrink: 0;
	      margin-right: 0;
	      -webkit-box-flex: 1;
	      -ms-flex-positive: 1;
	      flex-grow: 1;
	    }
	    
	    .grid--item-1 {
	      width: 100%;
	    }
	    
	    .grid--item-2 {
	      width: 50%;
	    }
	    
	    .grid--item-3 {
	      width: 33.333333333333336%;
	    }
	    
	    .grid--item-4 {
	      width: 25%;
	    }
	    
	    .grid--item-5 {
	      width: 20%;
	    }
	    
	    .grid--item-6 {
	      width: 16.666666666666668%;
	    }
	    
	    .grid--item-7 {
	      width: 14.285714285714286%;
	    }
	    
	    .grid--item-8 {
	      width: 12.5%;
	    }
	    
	    .grid--item-9 {
	      width: 11.11111111111111%;
	    }
	    
	    .grid--item-10 {
	      width: 10%;
	    }
	    
	    .grid--item-11 {
	      width: 9.090909090909092%;
	    }
	    
	    .grid--item-12 {
	      width: 8.333333333333334%;
	    }
	    
	```

	* **Hdas** (1)

		
		buen resumen

* **Daniel Diaz Orozco** (4)

	
	Muy buen curso, Muchas gracias Profe.

	* **Hdas** (1)

		
		buen curso

* **ivan_acg** (3)

	
	Muy buen curso profesor , pero me gustaria un poco mas de ejercitacion , hicimos el curso pero no desarrollamos en si un proyecto , hubiese estado muy bueno -

	* **Daniel Martínez** (3)

		
		Te propongo lo siguiente: Crea tu framework de CSS, que puedas usar en todos los proyectos. Si quieres ver un ejemplo, mira lo que yo he creado:  
		<https://github.com/Wakkos/Wakkos-CSS-Framework>
		
		Está en desarrollo, pero… A partir de ese repo, yo empiezo todos mis proyectos (Incluso en empresas grandes).
		
		Es un ejercicio que SIEMPRE ayuda a sacar nuestra “creatividad” con preprocesadores, y es algo que nos será siempre útil.

	* **Hdas** (1)

		
		que buen aporte buena información

* **CarlosAlba** (2)

	
	en el minuto 7:30 explica como escapar las variables

* **Teofilo Rosales Gama** (2)

	
	por si tiene problemas con el simbolo de sombrero aqui se los dejo:
	``` 
	    alt + 094 = ^ 
	    
	```
	
	o simplemente copien y pegen

	* **Hdas** (1)

		
		muchas gracias

* **Cristian Camilo Cucunubá** (2)

	
	 **Reto Sprite de Banderas**
	
	**HTML**
	``` 
	    <divclass="container">
	      <divclass="flag flag-usa">
	        
	      </div>
	      <divclass="flag flag-uk">
	      
	      </div>
	    </div>
	    
	```
	
	**CSS**
	``` 
	    flag-url = "https://image.flaticon.com/sprites/new_packs/551843-square-country-simple-flags.png"
	    
	    flags = { uk: -36px, usa: -236px, japan: -436px }
	    
	    .container
	    	border: 1px solid red;
	    .flag
	      	width: 130px
	     	height: 128px
	      	background-position-y: -30px
	      	background-image: url(flag-url)
	    
	    for flag in flags
	      	.flag.flag-{flag}
	        		background-position-x: flags[flag]
	    
	```
	
	[Demo](https://codepen.io/3c/pen/YvQMNr)

	* **Hdas** (1)

		
		Muchas gracias por tu aporte

* **Rafael Guillermo Rodriguez Garcia** (2)

	
	Para los interesados en generar el código css al salvar el archivo . _styl_ , les dejo este aporte.  
	<https://platzi.com/stylus/tutoriales/automatizar-jade-y-stylus-con-sublime-text-3/>

	* **Hdas** (1)

		
		gracias

* **Juan Carlos Felizzola Vega** (2)

	
	Hizo falta un ejercicio práctico!
	
	Buen contenido… seguimos con los demás cursos de preprocesadores.  
	Seguimos esperando el **examen de certificación**.

* **Angélica María Rocha García** (1)

	
	Muchas gracias Daniel por este curso.

* **Rafael Alvarez Cardona** (1)

	
	Para escapar es => {$i}

* **ricardo-cuan** (1)

	
	Me pareció un poco corto el curso

* **Karina Betzabe Romero Ulloa** (1)

	
	Range … …  
	Both the inclusive (…) and exclusive (…) range operators are provided, expanding to expressions:
	
	1…5  
	// => 1 2 3 4 5
	
	1…5  
	// => 1 2 3 4
	
	5…1  
	// => 5 4 3 2 1
	
	[fuente](http://stylus-lang.com/docs/operators.html)

* **CarlosAlba** (1)

	
	Aquí explica como escapar una variable, según lo que comenta es colocandola entre {}

* **CarlosAlba** (1)

	
	es mi idea o @wakkos dijo que display: flex nos va a hacer falta?
	
	osea podemos usar display grid pero qué significa que nos hará falta?

	* **Hdas** (1)

		
		depende de la organización que dispongas para tu proyecto

* **LuisDark123** (1)

	
	NOTAS
	
	Directiva for - Ejemplo basico
	``` 
	    .div
	        for x in (0..15)
	            content x
	    
	```
	
	Directiva for - Ejemplo avanzado
	``` 
	    containerElements = (1..12)
	    
	    .container{
	    	width100%;
	    	height auto;
	    }
	    
	    [class^="container-item"]
	    	width300px
	    	height300px
	    	background-color red
	    	
	    foriin containerElements
	    	.container-item-{i}
	    		margin (100px / i)
	    
	```

* **CarlosAlba** (1)
es mi idea o @wakkos dijo que display: flex nos va a hacer falta? osea podemos usar display grid pero qué significa que nos hará falta?

	* **Hdas** (1)

		
		depende de la organización que dispongas para tu proyecto

