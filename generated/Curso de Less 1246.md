# Cómo funciona Less

## 0010. Introducción a los cursos de preprocesadores

### Descripción:


### Comentarios:

* **Henry Gabriel Rodríguez Tovar** (5)

	
	El curso es de Less, pero la introducción dice que es de Stylus.

	* **rsanchez0** (2)

		
		El de Stylus dice Sass

	* **Jorge Wenner Arévalo Alvis** (1)

		
		jajajajaj cierto >.<

	* **Jose Armando Acevedo Angarita** (2)

		
		Es que la logica, es la misma que en el codigo… REUTILIZAR CODIGO!!! jajaajajajaajaj

	* **Roner Ortega Cueto** (1)

		
		Falta un boton de “me divierte”

* **hotarray** (3)

	
	Listo para comenzar 😄

* **diego rodriguez** (1)

	
	creo que me gusta mas sass

* **Camilo Alexander Velandia Velandia** (1)

	
	hasta el momento me quedo con sass

* **Nicolas Jiménez** (1)

	
	Veo que casi no hay comentarios recientes lo cual me hace pensar que quizá a la gente ya no le interesa aprender sobre pre procesardores 😦 ¿Por qué será?

* **Omar Enrique Crespo Merchan** (1)

	
	Empecemos ^^

* **LuisDark123** (1)

	
	Con todo el animo para empezar!!!

	* **Hdas** (1)

		
		Buen apunte

* **Juan David Rodriguez Dominguez** (1)

	
	a comenzar

## 0020. Introducción al curso

### Descripción:


### Comentarios:

* **Juan David Rodriguez Dominguez** (1)

	
	😃

	* **Jose Daniel Barría Reyes** (0)

		
		😄

	* **Jorge Wenner Arévalo Alvis** (1)

		
		😃

	* **SEBASTIAN PADUANO** (1)

		
		😄

	* **jdgarcia6** (1)

		
		😃

	* **Smarin-jpg** (1)

		
		😄

	* **Hdas** (1)

		
		:V

	* **Anfercode** (1)

		
		😄

	* **Pablo Sozko** (1)

		
		✌

	* **Jose Armando Acevedo Angarita** (1)

		
		😃

	* **David Alejandro Mosquera Moreno** (1)

		
		😃

	* **Freddy Córdova Arana** (1)

		
		😎

	* **Bikatti** (1)

		
		😎

	* **Roner Ortega Cueto** (1)

		
		😂

	* **jose-morales-varon** (1)

		
		😎

	* **diego rodriguez** (1)

		
		😀

	* **Emmanuel López** (1)

		
		😃

## 0030. Instalación de Less

### Descripción:


Para crear nuestro código debemos hacer algunos archivos fuera de CSS. Tenemos que saber que vamos a trabajar archivos .less. Hay muchas formas de compilar, entonces siempre esto depende de nuestro flujo de trabajo. Personalmente, soy fan de las UI los programas que hacen todo. Podemos usar Codekit en Mac y Prepross en Windows.

### Comentarios:

* **hotarray** (6)

	
	¡Profe!, no ignore a Linux XD

	* **Leonidas Esteban Gonzalez** (20)

		
		usa less desde la terminal, instala node y luego less
		``` 
		    npm install -g less
		    
		```
		
		ya luego puedes usar este comando
		``` 
		    lessc nombreDeTuArchivoLess.less nombreDeTuCSS.css 
		    
		```

	* **hotarray** (0)

		
		¡Gracias Leonidas!

	* **Omar Enrique Crespo Merchan** (1)

		
		grande leo… tremendo genio! XD

	* **Jorge Wenner Arévalo Alvis** (1)

		
		buena leo! xd

* **Gerardo Manuel Reyes Fernández** (2)

	
	No se que tan común sea pero al menos con angular da opción para que preconfigure automaticamente con webpack, creo que también funciona al usar vue y react, ambos usando webpack.  
	![Captura de pantalla de 2019-01-04 12-57-57.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20de%202019-01-04%2012-57-57-1b792f06-4f86-4e0e-b204-bfdda9b6c1f4.jpg)

* **Teofilo Rosales Gama** (0)

	
	Uen Koala para less es free para los pobres :  
	<http://koala-app.com>

	* **Brugarolas** (3)

		
		Koala está muy bien, pero Prepros se puede usar también de forma gratuita sin ninguna limitación (salvo un aviso para que lo compres cada vez que lo inicias).

* **eddyarellanes** (0)

	
	Configuración del buen Less para el buen webpack x)  
	<https://webpack.js.org/loaders/less-loader/>

* **Yomar Esteban Miranda Sarmiento** (0)

	
	Aún le falta edición a este video, a partir del minuto **10:00** se empieza a hablar de **SASS** siendo este un curso de **LESS.**

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Gracias por el reporte, lo vamos a editar y subir corregido lo más pronto posible. 😃

	* **Emerson Cedeño Salazar** (1)
Muy interesante, bloopers! 😅

* **hotarray** (0)

	
	Re flashero el final jajaja…

	* **AyKaren** (1)

		
		Lo arreglamos 🙊

	* **hotarray** (0)

		
		De ¡10! 😄

	* **Hdas** (1)

		
		gracias

* **hotarray** (0)

	
	¿Alguna opción open-source?

	* **hotarray** (0)

		
		Hasta el momento utilizo Prepros en Fedora.

## 0040. Tutorial y Reto

### Descripción:


Vamos a comenzar con los imports de Less.  
En esta clase te voy a enseñar a hacer que un solo archivo se compile, pero que este importe todos los otros archivos.  
Te muestro además cómo podemos compilar unos archivos específicos debemos usuar el _ (underscore) para que el compilador sepa cuáles son los archivos que se compilan como parte de otros archivos.

### Comentarios:

* **Kevin Nick Pascual Tuesta** (20)

	
	Estuve buscando y está es la forma mas rápida que encontré espero que les ayude [less-watch-compìler](https://github.com/jonycheung/deadsimple-less-watch-compiler)
	
	Instalamos mediante nuestra favorita consola de comandos (CMDER 😄 para los de windows):
	``` 
	    npm install -g less-watch-compiler
	    
	```
	
	Ahora solo nos queda ejecutar el comando del observador:
	``` 
	    less-watch-compiler <ruta_origen><ruta_destino>"nombre_del_archivo.less"
	    
	    //example
	    less-watch-compiler reto/src reto/render/css styles.less
	    
	```

* **arathjz** (5)

	
	Un tip que les puedo pasar es que hagan una carpeta con todos sus archivos fuente, dentro de **src** , y dentro de esa carpeta crear una subcarpeta llamada **less** para sus archivos. A su vez para los archivos compilados pueden ir dentro de una carpeta llamada **dist**. Esta practica les ayudara para cuando aprendan webpack. 😃

* **Jhon Michael Garcia Cuellar** (3)
Con sass no se usa barra baja para llamar el archivo, en less si es necesario

	* **Rayymonn** (0)

		
		ne corrijo en ambos casos se pueden llamar con el _nombre , pues es para indicar que el archivo no se va a compilar, en ambos casos es igual,lo acabo de probar 😃

* **crloshro** (2)

	
	Para el caso de gulp aqui estaria la forma de compilarlo:
	
	[](https://webkul.com/blog/compiling-less-file-gulp/)
	
	Me sirvió al 100%

	* **crloshro** (1)

		
		<https://webkul.com/blog/compiling-less-file-gulp/>

	* **Jorge Wenner Arévalo Alvis** (1)

		
		bueno!

* **Teofilo Rosales Gama** (2)

	
	yo uso la UI Koala para windows, is free

	* **Hdas** (1)

		
		Muchas Gracias

* **Sebastián Córdoba Omen** (1)

	
	Para importar recuerden finalizar con (😉  
	@import “base/_tipografia.less”;

* **Jorge Giraldo Guerrero R.** (1)

	
	Daniel cual es el arbol de archivos, gracias…

## 0050. Variables Definición y ejemplos

### Descripción:


Para el reto debes hacer una estructura de carpetas para todos los archivos que vamos a usar en el proyecto. En esta clase vamos a hablar sobre variables. Las variables son contenedores a los que les podemos asignar un valor específico.

### Comentarios:

* **Ruben Dario** (7)

	
	Esta interesante el curso, aunque para mi humilde criterio lo ideal es poder ver los cambios como tal en una pagina previamente definida.

	* **checho-leal** (1)

		
		de acuerdo

* **Jose Daniel Barría Reyes** (3)

	
	para declarar la variable
	``` 
	    @atr-sing : valor;
	    
	```
	
	en el ejemplo se uso la notacion atributo-significado  
	por ejemplo para el color principal y secundario
	``` 
	    @color-brand:#ea93ee;
	    @color-secondary: rgb(213,216,121);
	    
	```

	* **Jose Daniel Barría Reyes** (0)

		
		para llamar a esa variable
		``` 
		    @variable
		    
		```
		
		😄

	* **Jorge Wenner Arévalo Alvis** (1)

		
		😃

	* **Hdas** (1)

		
		Muchas gracias

* **J Michael Hernández González** (2)

	
	Carpetas  
	*Variables  
	*Mixins  
	*Globales  
	*Componentes

* **Mildred Guerra Rodríguez** (2)

	
	Carpetas
	
	  * base
	
	  * components
	
	  * layout
	
	  * utils
	
	
	

* **mariaguadalupelopezflores79** (2)

	
	El profesor asigna en el ejemplo el valor de la variable a una propiedad de css que no existe text-color, debería ser color: @color-brand;

	* **Erika Luna (Platzi)** (2)

		
		Estas en lo correcto. la propiedad correcta es color

	* **Hdas** (1)

		
		Gracias

* **jimmy-alexander-castiblanco-bu** (1)

	
	Carpetas  
	-base  
	-components  
	-layouts  
	-lib

* **Mildred Guerra Rodríguez** (1)

	
	Estructura de carpetas  
	base  
	components  
	layout  
	lib  
	utils

* **Jose Daniel Barría Reyes** (1)

	
	Para mejor organizacion:
	
	  * base : para nuestros elementos html
	  * lib : para nuestras variables
	
	

	* **Hdas** (1)

		
		Gracias

* **Jose Daniel Barría Reyes** (0)

	
	hacer una plantilla que nos sirva para el futuro :p

## 0060. Anidaciones

### Descripción:


Para esta clase vamos a usar unas variables que vamos a usar para los botones.

### Comentarios:

* **Jose Daniel Barría Reyes** (5)

	
	**nesting** : podemos agregar pseudoselectores (tales como :hover) dentro de la clase general, con el caracter & referenciamos al padre.(anidacion en spanish)
	``` 
	    //less
	    .btn{
	    	//properties
	    	&:hover{
	    		//properties
	    	}
	    }
	    
	```

	* **Hdas** (1)

		
		Gracias

* **Jose Daniel Barría Reyes** (3)

	
	Siempre incluir los parciales!

	* **Jose Daniel Barría Reyes** (1)

		
		agregar las variables primero, luego los elementos de base

	* **Hdas** (1)

		
		Buen apunte

* **gydoar** (2)

	
	La respuesta exacta es que al tener mas anidaciones, más reusabilidad perdemos.

* **julianaabad** (2)

	
	Por que es necesario manejar la escala de grises?

* **LuisDark123** (2)
En stylus el profesor Daniel Martinez recomienda no usar mas de 3 anidaciones pero, ¿Cuantas anidaciones se recomiendan para Less?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		El problema no es tanto por el preprocesador es mas por el rendimiento del navegador ya que muchas animaciones pueden hacer que la pagina se vea lenta.

* **Angélica María Rocha García** (1)

	
	Es mejor más clases que selectores 😄

* **Pau Pregoni Juan** (1)

	
	Estaría bueno poder ver el output de lo que se está haciendo.

* **Jair Cañon** (1)


* **Karina Betzabe Romero Ulloa** (1)

	
	Me parece interesante [esto](https://go.gliffy.com/go/publish/4784259)

* **Gerardo Manuel Reyes Fernández** (1)

	
	-Es preferible una clase demás a un selector demás.
	
	No se si entendí muy bien la clase. Lo que entendí es que existe lamanera de anidar pero no hay que abusar de este recurso.  
	Esta clase me recuerda un poco al principio de Single Responsability que se usa en programación.

	* **Hdas** (1)

		
		exacto puedes usar este recurso pero es mejor no abusar de el dado que puede traer problemas

* **Jorge Wenner Arévalo Alvis** (1)

	
	😃

* **LuisDark123** (1)

	
	En stylus el profesor Daniel Martinez recomienda no usar mas de 3 anidaciones pero, ¿Cuantas anidaciones se recomiendan para Less?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		El problema no es tanto por el preprocesador es mas por el rendimiento del navegador ya que muchas animaciones pueden hacer que la pagina se vea lenta.

	* **Néstor José Silva Castillo** (2)

		
		En realidad no hay un máximo o mínimo, el problema radica en que con muchas anidaciones somos más propensos al error.

* **Angélica María Rocha García** (1)
¿Cuántas anidaciones me recomendarían tener ?

	* **Juan David Castro (Platzi)** (1)

		
		No sabría decirte un número. Inevitablemente, entre más grande sea tu proyecto, más código CSS vamos a necesitar. Aquí la recomendación es que usemos una clase larga y descriptiva en lugar de muchas clases cortas para cada detalle.
		
		> Es mejor tratar de evitar la anidación siempre que se pueda, en lugar de anidar es mucho mejor crear clases con prefijos, por ejemplo .btn y .btn-success es mejor que tener .btn y .btn .success.  
		>  Solamente considero que vale la pena anidar cuando querés dar estilos a una etiqueta directamente sin usar clases (cosa que es mejor tratar de evitar de todas formas).  
		>  – <https://medium.com/@sergiodxa/escribiendo-css-de-la-forma-correcta-b420a498219c>

## 0070. Mixins

### Descripción:


Less es uno de los primeros preprocesadores que son la posibilidad de mezclar selectores. Lo más importante es que con estos podemos ahorrar mucísimo código.

### Comentarios:

* **luismjaquez** (4)

	
	Hay una gran diferencia al crear un mixin en LESS que en SASS!

	* **Emerson Cedeño Salazar** (3)

		
		vía **SASS** _(bien explícito)_ :
		
		  * declaración explícita,
		  * no es necesario que el nombre del mismo inicie con un punto,
		
		
		``` 
		    @mixin my_mixin { ... }
		    
		```
		
		vía **LESS** _(no tan explícito)_ :
		``` 
		    .my_mixin() { … }
		    
		```
		
		… y al igual que ambos, no compila sino hasta que es implementado en algún selector.

	* **Emerson Cedeño Salazar** (2)

		
		… de igual forma, en cuanto a la implementación:
		
		vía **SASS** _(explícita)_ :
		``` 
		    .element { @include my_mixin; }
		    
		```
		
		vía **LESS** :
		``` 
		    .element { .my_mixin; }
		    
		```

	* **Hdas** (1)

		
		Muchas gracias que buena información

* **Gerardo Manuel Reyes Fernández** (2)

	
	Don’t repeat yourself !!  
	Realmente esto de los mixins pueden reducir lineas y lineas de código y hacerlo mas mantenible  
	Esta padre también que si no se usa un mixin no lo compila.

	* **Hdas** (1)

		
		Don’t repeat yourself !! Tu lo has dicho

* **LuisDark123** (2)

	
	Notas:
	
	Crear un mixin
	
	Libreria Less
	``` 
	    .mixin-nombre(){
	        width: 100%;
	        background-color: red;
	    }
	    
	```
	
	Archivo Less
	``` 
	    body{
	    	.mixin-nombre
	    }
	    
	```
	
	Css
	``` 
	    body {
	      width: 100%;
	      background-color: red;
	    }
	    
	```

	* **Jorge Wenner Arévalo Alvis** (2)

		
		gracias

	* **Hdas** (1)

		
		Gracias

* **Jose Daniel Barría Reyes** (1)

	
	 _Mixins_ : mezclar selectores o reutilizar selectores en base a otros. Esto nos ayuda a reutilizar codigo.
	``` 
	    .max-width(){
	    	//properties
	    	max-width: 1024px;
	    }
	    .section{
	    	//lo aplicamos a una clase
	    	.max-width;
	    }
	    .footer{
	    	.max-width;
	    }
	    
	```
	
	Esos solo se compilan si los incluimos

	* **Hdas** (1)

		
		Gracias

## 0080. Mixins Paramétricos

### Descripción:


### Comentarios:

* **LuisDark123** (3)

	
	Notas:
	
	Mixin Parametrico
	
	Archivo _variables.styl
	``` 
	    @maxWidthDefault:1024px;
	    
	    .mixinMaxWidth(@maxWidth: @maxWidthDefault){
	    	max-width: @maxWidth;
	    }
	    
	```
	
	Archivo style.less
	``` 
	    section{
	    	.mixinMaxWidth(80%)
	    }
	    
	    .section{
	    	.mixinMaxWidth()
	    }
	    
	```
	
	Archivo style.css
	``` 
	    section {
	      max-width: 80%;
	    }
	    .section {
	      max-width: 1024px;
	    }
	    
	```

	* **Jorge Wenner Arévalo Alvis** (1)

		
		gracias

	* **Hdas** (1)

		
		Muchas gracias

* **Teofilo Rosales Gama** (2)

	
	falsa alarma logre solucionarlo con un plugin Easy LESS  
	para que compile en la carpeta css tube que hacer una configuracion de trabajo en un settings.json aqui les mando la conf:
	``` 
	    {
	        "less.compile": {
	            "out": "../\\css\\",
	            "sourceMap": true
	        }
	    
	    }
	    
	```

* **Angélica María Rocha García** (1)

	
	genial el poder de los Mixins 😄

* **Jose Daniel Barría Reyes** (0)

	
	Para mejor organizacion, se crea un parcial de **mixins**

	* **Jose Daniel Barría Reyes** (0)

		
		ejemplo de mixin que me gusto  
		_mixin.less:
		``` 
		    .max-width(@maxwidth:@page-max-width){
		    //declaramos el parametro maxwidth con page-max-width por defecto
		    	max-width: @max-width;
		    }
		    
		```
		
		_layout.less:
		``` 
		    .container--landing{
		        .max-width(80%);
		    }
		    
		```
		
		_variables.less :
		``` 
		    @page-max-width: 1024;
		    
		```

	* **Hdas** (1)

		
		Muchas gracias

* **Teofilo Rosales Gama** (0)

	
	cuando intento compilar el padding me sale :
	``` 
	    .container {
	      padding: 12px * 2;
	    }
	    
	```
	
	estos son mis archivos:
	
	variables.less
	``` 
	    @color-brand:#ea83ee;
	    @color-secondary: rgb(219,216,121);
	    
	    @color-border:@color-brand;
	    
	    @color-grey:#737373;
	    @buttonbg:@color-brand;
	    @buttontxt:#ffffff;
	    
	    @color-alert: rgb(210,0,0);
	    //constantes
	    @page-max-width: 2014px;
	    @padding:12px;
	    @superpadding:@padding * 2;
	    
	```
	
	layout.less
	``` 
	    .container {
	      padding: @superpadding;
	    }
	    
	```
	
	styles.less
	``` 
	    @import"lib/_variables.less";
	    @import"lib/_mixins.less";
	    
	    @import"base/_tipografia.less";
	    @import"base/_botones.less";
	    
	    @import"layout/_layout.less";
	    
	```
	
	uso el progrma koala

## 0090. Solución del reto

### Descripción:


### Comentarios:

* **Jorge Wenner Arévalo Alvis** (2)

	
	graciiiiias!

* **LuisDark123** (2)

	
	Esta clase me sirvió muchísimo, ya que yo dividía directamente mi código de css con “comentarios”. Gracias profesor, es usted increible.

	* **Hdas** (1)

		
		Buena clase

* **Jose Daniel Barría Reyes** (2)

	
	aqui el profe nos deja una plantilla de los parciales que considera que DEBEN estar en cada proyecto

	* **Hdas** (1)

		
		una base, siempre se puede usar la estructura de archivos que se crea conveniente

* **EmilyViri** (1)

	
	¿Existe algún esquema o estructura de archivos, para trabajar con Less?
	
	Me baso en todo lo que ha mencionando el profesor durante el curso, o es la perspectiva que él tiene, y por eso nos da tantos tips, respecto al “acomodo” de las  
	carpetas.
	
	Saludos. 😄

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		No hay un esquema, debes pensar más en que te sientas cómoda trabajando, si trabajas en equipo entonces definir las reglas para la estructura para que todos la entiendan y puedan trabajar sin problema.

	* **EmilyViri** (1)

		
		Oh ya capto 😮, muchas gracias @GOLLUM23

	* **Hdas** (1)

		
		siempre se puede usar la estructura de archivos que se crea conveniente

	* **Felipoch** (2)

		
		Una guía:
		
		<https://itnext.io/structuring-your-sass-projects-c8d41fa55ed4>

	* **Emmanuel García** (1)

		
		@Felipoch, justo que estaba buscando, gracias

* **EmilyViri** (0)
¿Existe algún esquema o estructura de archivos, para trabajar con Less? Me baso en todo lo que ha mencionando el profesor durante el curs...

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		No hay un esquema, debes pensar más en que te sientas cómoda trabajando, si trabajas en equipo entonces definir las reglas para la estructura para que todos la entiendan y puedan trabajar sin problema.

## 0100. Funciones de Less

### Descripción:


### Comentarios:

* **LuisDark123** (7)

	
	Sugiero que al ponerle nombre a una variable para determinar un color no se le debe colocar el nombre del color directamente ya que cuando se modifique el valor hexadecimal (color) podríamos confundir la variable.
	
	Por ejemplo:
	
	Al principio declaramos la variable asignándole un color azul.
	``` 
	    @colorBlue: blue;
	    
	```
	
	Y si en un futuro queremos cambiar la variable asignándole un color rojo, nos confundirá el nombre de la variable.
	``` 
	    @colorBlue: red;
	    
	```

	* **Hdas** (1)

		
		Se puede usar el nombre para la variable que mas se ajusto a tus preferencias o las de tu equipo de trabajo

* **LuisDark123** (3)

	
	Notas:
	
	Funciones
	``` 
	    @colorDefault: gray;
	    @colorModify: darken(@colorDefault, 60%);
	    
	```

* **Rayymonn** (2)

	
	jajaja varias veces se confunde de pre procesador jaja y dice sass 😃

* **jose-morales-varon** (2)

	
	Tenía entendido que esas funciones para oscurecer y aclarar eran de SASS

* **Jorge Wenner Arévalo Alvis** (2)

	
	genial 😃

	* **Hdas** (1)

		
		Buena clase

* **Imderf** (1)

	
	Función para oscurecer un color.
	``` 
	    @color-grey:#737373;
	    @color-drakgrey: darken(@color-grey, 45%);
	    
	```
	
	Para aclarar un color con Función.
	``` 
	    @color-grey:#737373;
	    @color-lighten: lighten(@color-grey, 25%);
	    
	```

	* **Hdas** (1)

		```
		    <@color-lighten: lighten(@color-grey, 25%);>
		    
		```

## 0110. Ejemplo de funciones con Less

### Descripción:


### Links:

* [
  Functions | Less.js
](http://lesscss.org/functions/)

### Comentarios:

* **LuisDark123** (9)

	
	Funciones vistas en el curso
	
	Aclarar un color
	``` 
	    @colorDefault: gray;
	    @color = lighten(@colorDefault, 80%);
	    
	```
	
	Opacar un color
	``` 
	    @colorDefault: gray;
	    @color = darken(@colorDefault, 80%);
	    
	```
	
	Saturar un color
	``` 
	    @colorDefault: gray;
	    @color = saturate(@colorDefault, 80%);
	    
	```
	
	Desaturar un color
	``` 
	    @colorDefault: gray;
	    @color = desaturate(@colorDefault, 80%);
	    
	```
	
	(Ruleta) Girar un color
	``` 
	    @colorDefault: gray;
	    @color = spin(@colorDefault, 80%);
	    
	```

	* **Jorge Wenner Arévalo Alvis** (2)

		
		bueno!

	* **Hdas** (1)

		
		Muchas gracias que buen resumen

* **Jesus Sandrea** (2)

	
	Pueden poner el link? 😄

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Ya esta disponible en la pestaña de enlaces.

* **Imderf** (1)

	
	Función para restar colores:
	``` 
	    @color: red - blue;
	    
	```
	
	Función para desaturar:
	``` 
	    @color-2: desaturate(grey, 80%);
	    
	```
	
	[Link de todas las funciones de Less](http://lesscss.org/functions/)

	* **Hdas** (1)

		
		Muchas gracias buen aporte

## 0120. Controles de Flujo

### Descripción:


### Comentarios:

* **LuisDark123** (5)

	
	Notas:
	
	Control de flujo con una condicion
	``` 
	    .condicional (@size) when (@size =< 1024px){
	    	width: 100%;
	    }
	    
	    .article{
	    	.condicional(800px);
	    }
	    
	```
	
	Control de flujo con dos condicionales
	``` 
	    .condicional (@size) when (@size =< 1024px){
	    	width: 100%;
	    }
	    
	    .condicional (@size) when (@size > 1024px){
	    	width: auto%;
	    }
	    
	    .article{
	    	.condicional(2200px);
	    }
	    
	```
	
	Escapar una expresión en less
	``` 
	    width: calc(~"50% - 12px");
	    
	```

	* **Jorge Wenner Arévalo Alvis** (2)

		
		😃

	* **Hdas** (1)

		
		Muchas gracias

* **elputoboss** (4)

	
	El símbolo para escapar en less no es “virguriña” como dice el profesor sino virgulilla

	* **Hdas** (1)

		
		gracias

* **LuisDark123** (4)

	
	Personalmente prefiero el if/else de stylus, es mas comprensible.

* **Cristian1398** (2)

	
	Me gustó este curso. Muchas gracias por traer este curso

	* **Hdas** (1)

		
		Muy buen curso

* **Ruben Dario** (1)

	
	Me ha gustado en general el curso, una opinion muy personal y es que cuando se crean variables, funciones y demas deberian ser con nombres en español para evitar confusiones con respecto a lo que si deberia ir en ingles en lo que propiamente hablando de la programacion como tal

	* **Diego Alexander Forero Higuera (Platzi)** (7)

		
		En el mundo de la programación el 99% de código profesional lo encuentras escrito en ingles esto es por varias razones, una porque es un idioma por decirlo de alguna manera universal, la segunda y tal vez la más importante en mi opinión es que evitas el uso de acentos y caracteres como la ñ que puedes sin darte cuenta usarlos y tener un error que te toma un par de horas encontrar solo porque tienes la palabra en español correctamente escrita y tu cerebro puede pasar por encima de ella varias veces sin notar que es un error.

* **Teofilo Rosales Gama** (1)

	
	para uso online  
	<http://lesscss.org/less-preview/>

* **luismjaquez** (1)

	
	Siempre habia escuchado de LESS y nunca me habia animado a aprenderlo hasta que vi este curso.

* **LucasFer** (0)

	
	Excelente, habia leido de estos preprocesadores. y con este curso me ha cerrado del todo! Gracias Platzi por traernos tan buenos profesores.

