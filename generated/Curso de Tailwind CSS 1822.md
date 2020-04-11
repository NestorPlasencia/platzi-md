# Introducción, instalación y ambiente de desarrollo

## 0010. ¿Qué es Tailwind CSS

### Descripción:


### Links:

* [GitHub - victoryoalli/platzifood: Material del curso de Tailwind CSS en @platzi](https://github.com/victoryoalli/platzifood)

* [Curso de Desarrollo Web Online | Platzi](https://platzi.com/clases/html5-css3)

* [Curso de HTML y CSS](https://platzi.com/clases/html-css/)

### Comentarios:

* **Javier Fuentes Mora** (6)

	
	La verdad se ve feo el diseño

* **Abner Batz** (3)

	
	En el curso de Vue.JS básico impartido por @ignacio Anaya, utilizó Tailwind, no pares de aprender.

* **Emmanuel Rodríguez Ramírez** (2)

	
	 **¿[Qué es TailWind CSS](https://tailwindcss.com/)?** 🧐  
	Es un [_framework_](https://en.wikipedia.org/wiki/Software_framework) que permite la contrucción de diseños altamente personalizados y de bajo nivel.
	
	**¿[Por qué usar TailWind CSS](https://tailwindcss.com/#what-is-tailwind)?** 🤨  
	A diferencia de otros frameworks css, como lo es [bootstrap](https://getbootstrap.com/), que otorgan componentes prediseñados, Tailwind provee clases a bajo nivel de css que nos permiten construir diseños completamente personalizados por nostros y sin tener que pelear con el framework en sí.
	
	Nos externa una [responsividad](https://tailwindcss.com/docs/responsive-design/) desde la misma sintaxis.
	
	Trabaja de manera amigable en el crecimiento de nuestro proyecto al proveernos herramientas para [extraer clases](https://tailwindcss.com/docs/extracting-components/).
	
	Pero sobre todo, nos abre su código para [personalizarlo](https://tailwindcss.com/docs/configuration/) ya que esta escrito en [PostCSS](https://postcss.org/) y configurado en JavaScript.
	
	Tailwind is more than a CSS framework, _it’s an engine for creating design systems_.

* **Joel William Mendoza Paucara** (2)

	
	Rayos en diseño no se ve agradable, quiero pensar que es solo el principio.

	* **Cristian Andrés Córdova Valencia** (1)

		
		+1

* **Alberto Alejandro Núñez Garcia** (1)

	
	Lo use para una pequeña web y me encanto, muy rapido.

* **Kevin Brayan Luna Figueroa** (1)

	
	Si me agrada mas que bootstrap, lo empezare a utilizar más!

* **Bernardo Jesús Alfaro Rojas** (1)

	
	Vamos a ver que tal este curso, espero utilizarlo en mis proyectos.

* **Nathaly Stefani Riaño Bejarano** (1)

	
	Tailwind CSS es un framework de CSS para crear rápidamente interfaces de usuario personalizadas con la siguiente ideología:
	
	  * Utility First
	  * Mobile First
	  * Responsive to the Core
	
	
	
	Te permite crear tus propios componentes y utilizarlos cuando necesites.

* **Christian Erik Velázquez Morales** (1)

	
	Vengo de aprender Materialize, y me encantó. Espero, aprender mucho de este curso.

	* **Aaron Gonzalez (Platzi)** (2)

		
		¡Qué genial, Christian!  
		Tailwind es un framework de CSS que ha crecido muchísimo desde su lanzamiento en 2019. En este curso aprenderás a usar las directivas, que son de los mejores features que trae TailwindCSS 😄

	* **Christian Erik Velázquez Morales** (2)

		
		@aaronpaulgz Gracias por el consejo.

* **JheysonEGalvis** (1)

	
	Tailwind Css, vengo con conocimientos muy básicos, espero aprender mucho acerca de este curso 😃

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Lo aprenderás, Jheyson! 😄  
		Tailwind es un framework de CSS que ha crecido muchísimo desde su lanzamiento. En este curso aprenderás a usar las directivas, que son de los mejores features que trae TailwindCSS 😄

* **hectorJosuemacias** (1)

	
	No conocia sobre este framework css.Vamos a aprenderlo entonces

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Bienvenido, **Hector**! 😄  
		Tailwind es un framework de CSS que ha crecido muchísimo desde su lanzamiento 😉

* **José Ponceleón** (1)

	
	Alfin ah llegado el momento 😊

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Qué genial que estes por aquí! 😄  
		Tailwind es un framework de CSS que ha crecido muchísimo desde su lanzamiento 😉

* **Alan Mena** (1)

	
	La espera ha valido la pena. Ya esperaba este curso. 😃

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Qué genial verte por aquí @Kolibri! 😄  
		Estoy seguro este curso te vendrá excelente para aplicarlo a tus proyectos, que por cierto, se ven buenísimos 😉

## 0020. Instalación y ambiente de desarrollo

### Descripción:


### Links:

* [Curso de Gestión de Dependencias y Paquetes con NPM](https://platzi.com/clases/npm/)

* [Tailwind CSS - A Utility-First CSS Framework for Rapidly Building Custom Designs](https://tailwindcss.com)

* [Autoprefixer CSS online](https://autoprefixer.github.io)

* [PostCSS - a tool for transforming CSS with JavaScript](https://postcss.org)

* [Curso de PostCSS](https://platzi.com/clases/postcss/)

* [Tailwind CSS IntelliSense - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

* [Live Server - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

### Comentarios:

* **Victor Yoalli Dominguez** (4)

	
	Otra alternativa a:
	
	`npx tailwindcss init`
	
	es ejecutar
	
	`./node_modules/.bin/tailwind init`
	
	las dos opciones realizan la misma función.

	* **CarlosAlba** (1)

		
		Gracias!
		
		Yo lo estoy corriendo desde Ubuntu y así me funcionó bien.

* **kevinchb1988** (3)

	
	Ya lo resolví siguiendo la documentación de Tailwind…
	
	Editen esta línea de código con sus rutas y listo
	``` 
	    npx tailwindcss build styles.css -o output.css```
	    
	```

	* **Karla Agraz** (2)

		
		Gracias.  
		Me funcionó con : npx tailwindcss build css/tailwind.css -o public/css/style.css

	* **Moisés Cedeño** (2)

		
		Excelente compañeros, es correcto. Si no hacemos esto no se genera el enlace entre el HTML y el CSS entonces no podemos usar las clases de TailwindCSS.
		
		Muchas gracias.

* **david-ponce** (3)

	
	Una manera sencilla de empezar a utilizar Tailwind CSS es utilizando el archivo minificado accediendo a este enlace:
	
	[https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css](https://unpkg.com/tailwindcss@%5E1.0/dist/tailwind.min.css)
	
	Se copia todo y lo guardas como _tailwind.min.css_ en tu proyecto y listo  
	Espero que a alguno le sirva 😃

	* **Aaron Gonzalez (Platzi)** (1)

		
		Usar el CDN suele funcionar y venir bien 😉  
		Solo tener en cuenta que al usarlo hay cosas que perdemos, como:
		
		  * Usar las directivas de `apply` y `variants`
		  * Usar `group-hover`
		  * No puedes agregar otros plug-ins
		
		

	* **david-ponce** (1)

		
		Totalmente de acuerdo aaron, solo di una opción ya que vi que varios tenían duda de usar nodejs, solo es para aprender y comprender esta tecnología no para un proyecto real jeje

* **Hernán Arica** (2)
Me parece demasiado básico el proyecto no me gusta nada el diseño creo que sí quieren insitar a que uno le tome cariño a un nuevo frameworck almenos hay que hacer un buen proyecto

* **Andres Gallardo** (2)

	
	No entendi nada jaja

	* **Jaime David Burbano Montoya** (1)

		
		¿Que no entendiste? Dame detalles, así podriamos ayudarte

* **Daniel Jonguitud** (2)

	
	Otra opción que quiero recomendar para no tener que instalar live server de npm es usar la extensión de VSCode que lleva el mismo nombre. Cualquiera de las dos opciones son exactamente lo mismo.

	* **Aaron Gonzalez (Platzi)** (2)

		
		Es cierto, Daniel. Ambas funcionarán OK 😄  
		Normalmente con este tipo de plugins prefiero instalarlos mediante VSCode ¿tú qué prefieres?

	* **Daniel Jonguitud** (1)

		
		Prefiero tenerla en VSCode 😃

* **Emmanuel Rodríguez Ramírez** (1)

	
	Se me activó VueJS ♥️  
	![Screen Shot 2020-04-05 at 22.48.20.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-04-05%20at%2022.48.20-848b76f5-6e77-41f1-9c0c-21cf55c32222.jpg)

* **Ariel Fernando Mejia** (1)

	
	aaaaah PHPSTORM eso te delatooo profee!!! crack!! 💪🏻

* **kevinchb1988** (1)

	
	Hola, a alguien más le sale este error al momento de realizar el “npm run build”?
	``` 
	    > platzi-tailwind@1.0.0 build C:\Users\KevCB1988\Desktop\platzi-tailwind
	    > postcss css/tailwind.css -o public/css/style.css
	    
	    ReferenceError: requiere is not defined
	        at Object.<anonymous> (C:\Users\KevCB1988\Desktop\platzi-tailwind\postcss.config.js:2:13)
	        at Module._compile (internal/modules/cjs/loader.js:936:30)
	        at Object.Module._extensions..js (internal/modules/cjs/loader.js:947:10)
	        at Module.load (internal/modules/cjs/loader.js:790:32)
	        at Function.Module._load (internal/modules/cjs/loader.js:703:12)
	        at Module.require (internal/modules/cjs/loader.js:830:19)
	        at require (internal/modules/cjs/helpers.js:68:18)
	        at module.exports (C:\Users\KevCB1988\Desktop\platzi-tailwind\node_modules\import-fresh\index.js:28:9)
	        at loadJs (C:\Users\KevCB1988\Desktop\platzi-tailwind\node_modules\cosmiconfig\dist\loaders.js:9:18)
	        at Explorer.loadFileContent (C:\Users\KevCB1988\Desktop\platzi-tailwind\node_modules\cosmiconfig\dist\createExplorer.js:230:12)
	    npm ERR! code ELIFECYCLE
	    npm ERR! errno 1
	    npm ERR! platzi-tailwind@1.0.0 build: `postcss css/tailwind.css -o public/css/style.css`
	    npm ERR! Exit status 1
	    npm ERR!
	    npm ERR! Failed at the platzi-tailwind@1.0.0 build script.
	    npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
	    
	    npm ERR! A complete log of this run can be found in:
	    npm ERR!     C:\Users\KevCB1988\AppData\Roaming\npm-cache\_logs\2020-03-24T00_31_34_387Z-debug.log```
	    
	```

	* **Ivan Fuentes González** (1)

		
		Talvez sea porque en un archivo de configuración tienes requiere en vez de require

	* **kevinchb1988** (1)

		
		@devfuentes Tienes razón, ¡master! gracias

* **elaniin** (1)

	
	Hola, una consulta, cada vez que desee realizar un nuevo proyecto, debo de hacer todo este procedimiento de nuevo? o queda ya todo registrado en nuestra maquina y solo ejecutamos los archivos en uno nuevo?

	* **Gabriel De Andrade (Platzi)** (1)

		
		Si, cada vez que quieras utilizar tailwind tendrás que instalarlo y configurarlo dentro de tu proyecto 😛

* **balachvinic** (1)

	
	No me generaba la construcción del proyecto con **npm run build** , así que buscando encontré que estaba inhabilitado la ejecución de scripts en mi configuración de node. Para habilitarlo solo había que cambiar el valor a **false** con el siguiente comando.
	``` 
	    npm config setignore-scripts false
	    
	```
	
	Si alguien tiene el mismo problema espero le sirva.

	* **José Alfonso Vargas Cruz** (1)

		
		Ya lo probé y no me generó la construcción del proyecto. ¿Hiciste algo más?

* **Francisco López Gutiérrez** (1)

	
	Buenas noches.  
	En la presentación comenta que Taildwind es muy bueno y me llamo la inquietud de conocerlo y cambie de opinión al ver el vídeo Instalación y ambiente de desarrollo donde deja fuera a Windows debido a que yo no cuento con Mac y aún no instalo Linux. Reciba un saludo.

	* **Aaron Gonzalez (Platzi)** (2)

		
		¡Hola, **@frankylg9**! 😄  
		La instalación se realiza con el mismo proceso ya sea en Windows, Mac o Linux. Puedes continuar con normalidad y hacer un proyecto genial.
		
		👉🏾 Acá te dejo también las diversas [formas de instalar TailwindCSS](https://tailwindcss.com/docs/installation/)

	* **CarlosAlba** (2)

		
		Hola!
		
		Bien dice Aaron, no importa el S.O. yo estoy desde un Ubuntu y no todo es como “en la clase” pero un poco de Google y lográs hacer que funcione de maravilla.
		
		Si me permites, ya terminé el curso y regresé por que me parece que tailwind es asombroso, mejor que los otros. Y en el estado de CSS es el que mayor satisfacción genera, no dejes que el S.O. sea una excusa.  
		Animo!

* **JheysonEGalvis** (1)

	
	No entiendo

	* **Nestor Cepeda (Platzi)** (1)

		
		Detalla muy bien la parte que no entiendas, sé más específico por favor. Así la comunidad podría darte feedback.  
		¡Saludos!

## 0030. Directivas de Tailwind

### Descripción:


### Comentarios:

* **Abner Batz** (1)

	
	 **@tailwind base;**  
	ayuda para inicializar elementos de html
	
	**@ tailwind utilities**  
	genera código de utilerias

* **Nathaly Stefani Riaño Bejarano** (1)

	
	Las directivas son instrucciones que permiten que Tailwind agregue los estilos definidos a nuestro archivo de css, lo cual permite utilizar las clases que nos provee éste framework para dar estilo a los elementos del HTML:
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	      <head>
	        <metacharset="UTF-8" />
	        <metaname="viewport"content="width=device-width, initial-scale=1.0" />
	        <title>TailWind CSS Course</title>
	        <linkrel="stylesheet"href="./css/style.css" />
	      </head>
	      <body>
	        <divclass="h-64">
	          <divclass="p-4 m-4 bg-green-600">
	            <h1class="text-2xl font-bold text-white">Tailwind CSS Demo</h1>
	          </div>
	          <divclass="p-4 m-4 bg-green-300 h-full">
	            <h2class="text-green-900">Have much fun using Tailwind CSS</h2>
	          </div>
	        </div>
	      </body>
	    </html>
	    
	```

* **carlosob** (1)
tengo este problema, con el archivo tailwind.css

	* **CarlosAlba** (1)

		
		Hola!
		
		Pues no pasa nada. A mi me marca los mismos errores pero todo funciona. ¿Estas ejecutando el script de package.json?  
		También puedes agregar este:
		``` 
		    "dev": "postcss css/tailwind.css -o public/css/styles.css --watch"
		    
		```

* **Francisco López Gutiérrez** (1)
Buenas noches.

# Conceptos básicos

## 0040. Personalización y configuración

### Descripción:


### Links:

* [Installation - Tailwind CSS](https://tailwindcss.com/docs/installation)

### Comentarios:

* **Abner Batz** (3)

	
	En esta clase aprendí a personalizar y configurar ambiente de **Tailwind CSS**

* **Emmanuel Rodríguez Ramírez** (1)

	
	## Configuración
	
	Ya que Tailwind es un framework para construir UI a la medida, por default, se tiene un archivo _opcional_ llamado `tailwind.config.js` en la raíz de la carpeta, donde está el `package.json`.
	
	## Creando un archivo de configuración
	
	Para generar un archivo de configuración para Tailwind, podemos usar el _Tailwind CLI_ :
	``` 
	    npx tailwind init
	    
	```
	
	**Nota**. Podemos utilizar esta herramienta cuando instalamos la dependencia via `npm`.  
	Donde como resultado tendremos `tailwind.config.js`:
	``` 
	    module.exports = {
	      theme: {},
	      variants: {},
	      plugins: [],
	    }
	    
	```
	
	Cabe mencionar que cada sección, del archivo de configuración, es opcional.
	
	## La sección _Theme_
	
	Esta sección es donde definimos los aspectos relacionados con el diseño visual de nuestro sitio.
	``` 
	    ...
	      theme: {
	        screens: {
	          sm: '640px',
	          md: '768px',
	          lg: '1024px',
	          xl: '1280px',
	        },
	        fontFamily: {
	          display: ['Gilroy', 'sans-serif'],
	          body: ['Graphik', 'sans-serif'],
	        },
	        borderWidth: {
	          default: '1px',
	          '0': '0',
	          '2': '2px',
	          '4': '4px',
	        },
	        extend: {
	          colors: {
	            cyan: '#9cdbff',
	          },
	          spacing: {
	            '96': '24rem',
	            '128': '32rem',
	          }
	        }
	      }
	    ...
	    
	```
	
	## La sección _Variants_
	
	Esta sección nos permite controlar el comportamiento de las utilidades core, como _responsive variants_ y _pseudo-class variants_.
	``` 
	    ...
	      variants: {
	        appearance: ['responsive'],
	        // ...
	        borderColor: ['responsive', 'hover', 'focus'],
	        // ...
	        outline: ['responsive', 'focus'],
	        // ...
	        zIndex: ['responsive'],
	      },
	    ...
	    
	```
	
	## La sección _Plugins_
	
	Esta sección nos permite registrar plugins de terceros con el objetivo de extender utilidades, componentes, estilos, etc.
	``` 
	    ...
	      plugins: [
	        require('tailwindcss-transforms'),
	        require('tailwindcss-transitions'),
	        require('tailwindcss-border-gradients'),
	      ],
	    ...
	    
	```

## 0050. Responsive Design, Mobile First y Utility First

### Descripción:


### Links:

* [Sizzy](https://sizzy.co/)

* [Curso de Responsive Design](https://platzi.com/cursos/responsive-design/)

* [Por qué es importante aprender a diseñar interfaces para móviles](https://platzi.com/blog/diseno-interfaces-moviles-mobile-first/)

* [Utility-First - Tailwind CSS](https://tailwindcss.com/docs/utility-first/)

### Comentarios:

* **Emmanuel Rodríguez Ramírez** (1)

	
	## Responsive Web Design
	
	La web como la conocemos, hoy en día, no es una tecnología pensando en un **UX** o _User Experience_ generando, desafortunadamente, que muchos de los sitio web no estén optimizados para los **dispotivos móviles**.
	
	Definido por [Ethan Marcotte](https://alistapart.com/article/responsive-web-design/), es una filosofía que responde a las necediades de los usuarios y a los dispositivos que estamos usando.
	
	## Mobile First
	
	Como su nombre sugiere, significa que iniciaremos con el diseño de móviles y expandiendo éstas características para crear una verión en tableta o escritorio/web tradicional.
	
	Cabe mencionar que esta filosofía no es sinónimo de limitación, por lo que tenemos que tener el mismo contenido tanto en escritorio como en móvil. Google describe las [_best practices_](https://developers.google.com/search/mobile-sites/mobile-first-indexing) en su sitio.
	
	## Utility first
	
	CSS posee diferentes tipos de paradigmas para abstraer un diseño, como BEM descrito por [Tailwind](https://tailwindcss.com/docs/utility-first/) en ésta sección:
	``` 
	    <divclass="chat-notification">
	      <divclass="chat-notification-logo-wrapper">
	        <imgclass="chat-notification-logo"src="/img/logo.svg"alt="ChitChat Logo">
	      </div>
	      <divclass="chat-notification-content">
	        <h4class="chat-notification-title">ChitChat</h4>
	        <pclass="chat-notification-message">You have a new message!</p>
	      </div>
	    </div>
	    
	```
	
	Sin embargo, llega a ser muy complicado establecer un armonía entre desarrolladores-diseñadores si no hay una concesión de sintaxis o _linter_. Por ello, Tailwind establece su propio orden con el objetivo:
	
	  * No invertir tiempo en inventar nombres para las clases
	  * Detener el crecimiento, sin fin, de CSS
	  * Simplificando y asegurando los cambios al CSS
	
	
	
	## Herramienta para desarrollo 🚀
	
	Como desarrolladores necesitamos herramientas que nos permita exlotar nuestra creatividad al máximo por ellos exiten algunas DevTools:
	
	  * [Safari for Developers](https://developer.apple.com/safari/)
	  * Chrome o [Chrome for Developers](https://www.google.com/chrome/dev/)  
	Y otras más … 🤯
	
	

* **Kevin Brayan Luna Figueroa** (1)

	
	Esta es otra opcion de Sizzy, <https://material.io/resources/resizer/>

	* **Moisés Cedeño** (1)

		
		Gran aporte compañero, muchas gracias.

* **juanchovar** (1)

	
	Sizzy se ve como un muy browser…

	* **Aaron Gonzalez (Platzi)** (3)

		
		Sizzy está genial. Lo he usado hace ya un buen tiempo y te ahorra mucho tiempo al revisar los breakpoints de tu Responsive Design 😄

	* **Ludwring Liccien** (1)

		
		Como lo descargo? es pago?

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Hola, **@Illiccien**! 😄  
		👉🏾 <https://sizzy.co/>
		
		Lo puedes probar free y luego pagar $5.00/mes que pues se ve razonable.

	* **Karla Agraz** (2)

		
		No conocía Sizzy, me parece muy útil para los proyectos 👍

	* **Aaron Gonzalez (Platzi)** (2)

		
		Lo es, **@karla-agraz** 😄  
		Estoy en la prueba free y todo va fenomenal 🙌🏼
		
		Muyyy recomendado 😄

# Utilerías

## 0060. Colores

### Descripción:


### Comentarios:

* **Daniel Jonguitud** (2)

	
	Aquí esta el linea para crear el archivo de configuración
	``` 
	    npx tailwindcss init tailwind.config.full.js --full
	    
	```

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Genial aporte, Daniel! 😄  
		Cuéntanos, ¿cómo vas con el curso?

* **Emmanuel Rodríguez Ramírez** (1)

	
	## Nota
	
	Cuando nostros creamos y agregamos las siguientes lineas al CSS:
	``` 
	    /*tailwind.css*/
	    @tailwind base;
	    @tailwind components;
	    @tailwind utilities;
	    
	```
	
	Procesamos un archivo con las configuraciones por default de Tailwind via el scrip _build_ descrito por:
	``` 
	    ...
	    "build": "postcss css/tailwind.css -o public/css/style.css"
	    ...
	    
	```
	
	El cual, y **nada más observamos** , a través de tailwind.config.full.js. Por lo que, con o sin el archivo generado, estamos viendo el resultado con PostCSS por default.  
	Si deseamos **generar un archivo** de CSS con la configuración establecida en `tailwind.config.js`, debemos agregar los siguientes cambios al archivo de PostCSS:
	``` 
	    // postcss.config.js
	    module.exports = {
	      plugins: [
	        require('tailwindcss')('./tailwindcss.config.js'),
	      ],
	    }
	    
	```

* **Kevin Brayan Luna Figueroa** (1)

	
	Que plugin utiliza el profesor para que el hexadecimal se pinte de color?

	* **Gabriel De Andrade (Platzi)** (3)

		
		[Color HIghlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) 😄

	* **kevinchb1988** (2)

		
		El pluggin es: tailwindcss autocomplete

* **Abner Batz** (1)

	
	 **Tailwind** por default **tiene valores** predefinidos y lo podemos conocer al generar un archivo de configuración con todos los valores completos,con esta línea de comandos  
	**npx tailwindcss init tailwind.config.full.js --full**

* **Jaime David Burbano Montoya** (1)

	
	Aquí pueden ver toda la documentación de los colores  
	<https://tailwindcss.com/docs/customizing-colors>

* **Jaime David Burbano Montoya** (1)

	
	Genial, parece magía y por eso me surge una duda. ¿Donde puedo ver todos los estilos organizados por tipo para saber cual puedo aplicar?

	* **Gabriel De Andrade (Platzi)** (1)

		
		Para eso la documentación de Tailwind está genial: <https://tailwindcss.com/docs/> 😄

* **Mateo Aquino** (1)

	
	A alguien mas no le funciona la extencion de IntelliSense en VSC?

	* **José Ponceleón** (1)

		
		A mi no me funciona :c

	* **Mateo Aquino** (1)

		
		 **SOLUCIÓN**  
		desinstalar y volver a instalar el VSC

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Hola!  
		En ocasiones puede darse esta circunstancia. La solución rápida, post-instalación, es reiniciar VSCode y listo 😄

## 0070. Dimensiones y Espacios

### Descripción:


### Links:

* [Unidades de medida en CSS, la guía definitiva](https://platzi.com/blog/unidades-de-medida-en-css/)

### Comentarios:

* **Jaime David Burbano Montoya** (6)

	
	Aquí pueden ver los anchos  
	<https://tailwindcss.com/docs/width>
	
	Aquí pueden ver los padding  
	<https://tailwindcss.com/docs/padding>
	
	Aquí pueden ver los margin  
	<https://tailwindcss.com/docs/margin>

	* **Kevin Brayan Luna Figueroa** (1)

		
		Gracias por el aporte!

## 0080. Cambiando las propiedades de la tipografía

### Descripción:


### Comentarios:

* **Emmanuel Rodríguez Ramírez** (1)

	
	## @font-faces
	
	Para aprovechar la regla `@font-face`para realizar cualquier personalización fuera de _Tailwindcss_ modificamos el archivo CSS principal de la siguiente manera:
	``` 
	    @tailwind base;
	    
	    @font-face {
	      font-family: Proxima Nova;
	      font-weight: 400;
	      src: url(/fonts/proxima-nova/400-regular.woff) format("woff");
	    }
	    @font-face {
	      font-family: Proxima Nova;
	      font-weight: 500;
	      src: url(/fonts/proxima-nova/500-medium.woff) format("woff");
	    }
	    
	    @tailwind components;
	    
	    @tailwind utilities;
	    
	```
	
	**Nota**. Para definir cualquier personalización hacia los estilos base, agregamos nuestros estilos después de `@tailwind base` y antes de `@tailwind components` para evitar problemas de compilación.

* **Kevin Brayan Luna Figueroa** (1)

	
	Les dejo el link directo para FontSize <https://tailwindcss.com/docs/font-size/#app>

## 0090. Ajustando el espaciado entre letras y líneas

### Descripción:


### Comentarios:

* **Abner Batz** (3)

	
	2 instrucciones que debemos aprender:  
	**Tracking** espaciamiento entre letras  
	**Leading** espaciamiento entre lineas

## 0100. Display

### Descripción:


### Comentarios:

* **Jaime David Burbano Montoya** (1)

	
	¿No hay dispay grid?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Si existe, revisando la documentación oficial aquí la encuentras <https://tailwindcss.com/docs/display#grid>

## 0110. Flexbox

### Descripción:


### Comentarios:

* **Kevin Brayan Luna Figueroa** (1)

	
	Dejo link para ver la documentacion sobre Flexbox <https://tailwindcss.com/docs/display/#flex>

## 0120. Cómo crear grids o columnas en Tailwind CSS

### Descripción:


En esta clase vamos a aprender a crear un grid de columnas utilizando flex en Tailwind.

## Grid Básico

Verás que con lo que hemos aprendido hasta ahora es muy sencillo crear un grid.

  1. Crearemos un elemento que contendrá las columnas de nuestro Grid con la clase de flex.


``` 
    </div>
    
```

  2. Teniendo de base el elemento del punto anterior insertaremos una etiqueta por cada columna que queramos tener de la siguiente manera.



> Una columna
``` 
    	<div
        class=“w-full
        p-4 bg-blue-800"
      ></div>
    </div>
    
```

_Resultado_  
![1.png](https://static.platzi.com/media/user_upload/1-ff78efd3-e529-470f-9105-71cdea0c4593.jpg)

> Dos columnas
``` 
    	<div
        class=“w-full
        p-4 bg-blue-800"
      ></div>
    </div>
    
```

_Resultado_

![2.png](https://static.platzi.com/media/user_upload/2-032d8f91-dea6-4219-8a73-664e47ac4ce5.jpg)

> Tres Columnas
``` 
    	<div
        class="w-1/3
        p-4 bg-blue-800"
      ></div>
      <div
        class="w-1/3 
        p-4 bg-blue-600"
      ></div>
      <div
        class="w-1/3
        p-4 bg-blue-500"
      ></div>
    </div>
    
```

_Resultado_

![3.png](https://static.platzi.com/media/user_upload/3-2622e8e4-05fd-4602-9aab-be142773d75f.jpg)

> Cuatro Columnas
``` 
    	<div
        class="w-1/4
        p-4 bg-blue-700"
      ></div>
      <div
        class="w-1/4 
        p-4 bg-blue-400"
      ></div>
      <div
        class="w-1/4
        p-4 bg-blue-600"
      ></div>
      <div
        class="w-1/4
        p-4 bg-blue-500"
      ></div>
    </div>
    
```

> Cinco columnas
``` 
    	<div
        class="w-1/5
        p-4 bg-blue-700"
      ></div>
      <div
        class="w-1/5 
        p-4 bg-blue-400"
      ></div>
      <div
        class="w-1/5
        p-4 bg-blue-600"
      ></div>
      <div
        class="w-1/5
        p-4 bg-blue-500"
      ></div>
      <div
        class="w-1/5
        p-4 bg-blue-800"
      ></div>
    </div>
    
```

_Resultado_  
![5.png](https://static.platzi.com/media/user_upload/5-02452bb9-7a47-43a0-a29b-7ff312bedfd8.jpg)

> Seis columnas
``` 
    	<div
        class="w-1/6
        p-4 bg-blue-700"
      ></div>
      <div
        class="w-1/6 
        p-4 bg-blue-400"
      ></div>
      <div
        class="w-1/6
        p-4 bg-blue-600"
      ></div>
      <div
        class="w-1/6
        p-4 bg-blue-500"
      ></div>
      <div
        class="w-1/6
        p-4 bg-blue-300"
      ></div>
      <div
        class="w-1/6
        p-4 bg-blue-800"
      ></div>
    </div>
    
```

_Resultado_

![6.png](https://static.platzi.com/media/user_upload/6-a95e1c2b-5694-4ba1-a7f5-e71358b7ac22.jpg)

## Grid Responsivo con Columnas de Anchura Fija

La diferencia para lograr que nuestro grid sea responsivo es que al elemento base donde tenemos la clase de `flex` le agregamos `flex-wrap` con esto logramos que cuando uno de los elemento exceda el tamaño, ese elemento pase al siguiente renglón. Y con el uso de las pseudo-classes responsivas de `sm`, `md`, `lg` y `xl` logramos el numero de columnas deseada por tamaño de pantalla.
``` 
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/6 
        p-4 bg-green-700 mb-1"
      ></div>
    </div>
    
    
```

### Resultados

> **default o xs**

![7.PNG](https://static.platzi.com/media/user_upload/7-6aee0e94-a38b-44ef-be60-d70009555744.jpg)

> **sm**

![8.PNG](https://static.platzi.com/media/user_upload/8-d1e52bc9-e665-41be-85ff-32cc419fb24d.jpg)

> **md**

![9.PNG](https://static.platzi.com/media/user_upload/9-e4472224-501f-4fbd-b43c-e92c6d2c9440.jpg)  
&amp;amp;amp;gt; **lg**

![10.PNG](https://static.platzi.com/media/user_upload/10-ed191c67-c51b-4619-b917-5247e6244176.jpg)

> **xl**

![11.PNG](https://static.platzi.com/media/user_upload/11-1254aea4-326c-405e-be3d-8fe54c1ebb14.jpg)

## Grid Responsivo con Columnas de Anchura Variable

Al igual que con el grid responsivo anterior, agregamos en el elemento base de `flex` la clase de `flex-wrap` y de igual manera hacemos uso de las pseudo-classes responsivas de `sm`, `md`, `lg`y `xl`.
``` 
      <div
        class="w-full sm:w-1/2 md:w-2/5 lg:w-1/6 xl:w-7/12 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/3 md:w-1/5 lg:w-3/6 xl:w-1/12 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/6 md:w-2/5 lg:w-2/6 xl:w-4/12 
        p-4 bg-green-900 mb-1"
      ></div>
    
      <div
        class="w-full sm:w-1/6 md:w-1/5 lg:w-1/6 xl:w-1/12 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/3 md:w-3/5 lg:w-1/6 xl:w-5/12 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-1/5 lg:w-4/6 xl:w-6/12 
        p-4 bg-green-900 mb-1"
      ></div>
    
      <div
        class="w-full sm:w-1/3 md:w-1/5 lg:w-2/6 xl:w-3/12 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/6 md:w-1/5 lg:w-2/6 xl:w-4/12 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/2 md:w-3/5 lg:w-2/6 xl:w-5/12 
        p-4 bg-green-900 mb-1"
      ></div>
    
      <div
        class="w-full sm:w-1/2 md:w-3/5 lg:w-3/6 xl:w-8/12 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/6 md:w-1/5 lg:w-2/6 xl:w-2/12 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/3 md:w-1/5 lg:w-1/6 xl:w-2/12 
        p-4 bg-green-900 mb-1"
      ></div>
    
      <div
        class="w-full sm:w-1/2 md:w-2/5 lg:w-2/6 xl:w-5/12 
        p-4 bg-green-700 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/3 md:w-1/5 lg:w-1/6 xl:w-3/12 
        p-4 bg-green-500 mb-1"
      ></div>
      <div
        class="w-full sm:w-1/6 md:w-2/5 lg:w-3/6 xl:w-4/12 
        p-4 bg-green-900 mb-1"
      ></div>
    </div>
    
    
```

### Resultados

> **default o xs**

![12.PNG](https://static.platzi.com/media/user_upload/12-805b2b1f-7a6d-4150-83e5-510e0161210d.jpg)

> **sm**

![13.PNG](https://static.platzi.com/media/user_upload/13-9cb58230-1020-4f43-aba0-0343c76f6bec.jpg)

> **md**

![14.PNG](https://static.platzi.com/media/user_upload/14-a42d71a2-5d08-4fe6-85a5-f94241d65d85.jpg)

> **lg**

![15.PNG](https://static.platzi.com/media/user_upload/15-0dc64691-aac2-4482-b2ee-2cee9502eae4.jpg)

> **xl**  
>  ![16.PNG](https://static.platzi.com/media/user_upload/16-1d9c2d7d-245e-4064-9fdf-0c7c5bec4e8f.jpg)

## Conclusión

Crear grids en Tailwind usando flex es muy sencillo.  
En `flex` podemos hacer uso de las clases de dimensiones porcentuales, algunos ejemplos son:  
w-1/2, w-2/3, w-3/4, w-5/6, w-7/12,.  
Estas mediciones nos facilita poder crear columnas de 2, 3, 4, 5, 6 y 12 columnas y sus combinaciones.

### Comentarios:

* **Jaime David Burbano Montoya** (3)

	
	Hay un error en el código del paso 2, muestra solo el html de un div, pero se están mostrando 2 que están en w-1/2

* **Abner Batz** (2)

	
	¿Como utilizar **CSS Grid Layout system** en Tailwind?

* **Favio Sauto** (2)

	
	¿Alguien puede ver el código?
	
	A mi no me aparece.

	* **Daniel Jonguitud** (1)

		
		A mi tampoco me aparece, según la fecha de publicación al parecer todavia se sigue actualizando

	* **Juan Felipe Peralta Zapata (Platzi)** (2)

		
		Ya se solucionó ese detalle, ¿podrían confirmarnos si ya pueden ver el código? Por favor. 😃

	* **Favio Sauto** (2)

		
		Ya se ve, ¡Gracias!

* **Guillermo Vara De Gante** (1)

	
	La parte del codigo que no se ve en la primera seccion es un
	``` 
	    <divclass="flex m-4">
	            <divclass="m-2 w-1/2 p-4 bg-blue-800">
	                <p>w-1/2</p>
	            </div>
	            <divclass="m-2 w-1/2 p-4 bg-blue-800">
	                <p>w-1/2</p>
	            </div>
	        </div>
	    
	```

* **Abraham Caso Torres** (1)

	
	Hasta el momento me va gustando mucho este curso.

* **José Alfonso Vargas Cruz** (1)

	
	El paso 1 solo aparece un </div>

* **Hernán Arica** (1)

	
	No sale el código

	* **Juan Felipe Peralta Zapata (Platzi)** (2)

		
		¡Hola! Ya se solucionó ese detalle, de todas formas ¿podrías confirmarnos si ya puedes ver el código? Por favor. 😄

	* **Hernán Arica** (1)

		
		si efectivamente! ya se visualiza el código

## 0130. Crea tus propias utilerías

### Descripción:


### Comentarios:

* **Daniel Jonguitud** (9)

	
	Para que les suceda como en el caso del profesor y solo tengan que guardar el archivo de css para que se actualicen los estilos, podemos añadir un script adicional a nuestro package.json, el cual es el siguiente:
	``` 
	    "scripts": {
	        "build": "postcss css/tailwind.css -o public/css/styles.css",
	        "dev": "postcss css/tailwind.css -o public/css/styles.css --watch"
	      },
	    
	```
	
	Con esto solo tienen que ejecutar “npm run dev” en su terminal para que cada que guarden el archivo se actulize automaticamente.
	
	*Nota: el comando dev continuara su ejecución hasta que le indiquemos lo contrario, para escaparla solo usa control + C en la terminal

	* **Moisés Cedeño** (2)

		
		Estupendo compañero, muchas gracias, me ha funcionado con esto.

	* **LuisViGo** (1)

		
		Amigo sabes como ejecutar este comando y el “live-server public” para que se actualice el archivo y podamos subir el servidor?

	* **Fernando Vallejo** (1)

		
		Bueno yo utilice dos consolas en vscode.

	* **Daniel Jonguitud** (1)

		
		Para LuisViGo: Personalmente utilizo live server desde VSCode pero creo que te sería útil el siguiente enlace para lograr correr tus dos scripts en npm <https://stackoverflow.com/questions/30950032/how-can-i-run-multiple-npm-scripts-in-parallel>

* **LuisViGo** (1)

	
	Como hace el profesor para que se le actualice el “css/style.css” de manera automática y ademas tener activo el servidor con “live-server”?

* **Nathaly Stefani Riaño Bejarano** (1)

	
	Documentación acerca de las variantes en Tailwind CSS: <https://tailwindcss.com/docs/configuring-variants/>

	* **Moisés Cedeño** (1)

		
		Gracias compañera, muy útil.

## 0140. Entendiendo las variantes y las pseudo-clases

### Descripción:


### Links:

* [Pseudo-Class Variants - Tailwind CSS](https://tailwindcss.com/docs/pseudo-class-variants/)

### Comentarios:

* **hanniaflores** (5)

	
	Aquí esta el código que agrega de la documentación
	``` 
	    <button class="disabled:opacity-75 bg-blue-500">
	      Submit
	    </button>
	    
	```
	
	El segundo código que agrega
	``` 
	    variants: {
	        opacity: ['responsive', 'hover', 'focus', 'disabled'],
	      },
	    
	```
	
	link de la documentación:  
	<https://tailwindcss.com/docs/pseudo-class-variants/#app>

## 0150. ¡Es hora de practicar!

### Descripción:


### Colores y Dimensiones

Tip: Una buena práctica al combinar colores, como en botones por ejemplo, es no poner la letra color blanco o negro. En su lugar utiliza las tonalidades del mismo color para hacerla resaltar.

● Crea un botón color azul siguiendo estos consejos, recuerda que las tonalidades predefinidas van del 100 al 900.  
● Crea un botón que se adapte según el tamaño de dispositivo.  
● Cuando sea de tamaño pequeño, este botón debe abarcar el ancho de la pantalla y cuando sea un poco más grande debe tener un tamaño predeterminado.

Si no estás seguro sobre cuáles colores escoger, te recomiendo que uses Paletton, ahí podrás escoger un color y el programa te sugerirá colores que puedan combinar. (<https://paletton.com/>)

### Display y Flexbox

Tip: Una buena práctica es utilizar el margen de cada elemento para posicionarlo con respecto a otros. Esto se logra con margin left (ml-x), margin-top (mt-x). Si usamos margin right y margin bottom lo que hacemos es mover otros elementos respecto del elemento con el que estamos trabajando.

● Crea lo que se conoce como group button de 3 buttons o más. Esto lo logras utilizando lo aprendido en display o flexbox, así como margin y padding.

### Pseudo—Class Variants

Utilizando variantes como hover y active, logra crear efectos cambiando el color de los botones creados anteriormente.

● Cuando pases el cursor encima de uno de los botones deberá cambiar el fondo a un color más oscuro, de tal manera que resalte con el texto. Y al estar en estado normal, el fondo deberá ser claro y el texto, color oscuro.

### Extraer componentes usando @apply

Utilizando la directiva @apply, crea un componente de “alert” con sus variaciones para que se comporte distinto según la clase que le acompañe.

Hay que crear:  
● alert (default) - Utiliza un color neutro  
● alert (danger) - Utiliza un color rojo  
● alert (warning) - Utiliza un color amarillo o naranja  
● alert (info) - Utiliza un color azul

Para desarrollar este reto tendrás que hacer uso de:  
● margin  
● padding  
● border  
● background  
● text color

El código de tu componente de poderse utilizar como sigue:  
El código de tu componente debería verse así:
``` 
    	Este mensaje es una alerta default.
    </div>
    
    <div class=“alert alert-danger”>
    	Este mensaje es una alerta danger.
    </div>
    
    
    <div class=“alert alert-warning”>
    	Este mensaje es una alerta warning.
    </div>
    
    <div class=“alert alert-info”>
    	Este mensaje es una alerta info.
    </div>
    
```

### Comentarios:

* **Ariel Fernando Mejia** (3)

	
	Ojo recordar que las directivas @apply deben ir antes de agregar las utilities en el archivo tailwind.css
	``` 
	    @tailwind base;
	    
	    @tailwind components;
	    
	    .btn-blue {
	        @apply bg-blue-500 text-white font-bold py-2 px-4 rounded;
	    }
	    .btn-blue:hover {
	        @apply bg-blue-700;
	    }
	    
	    .btn-red {
	        @apply bg-red-800 text-white font-bold py-2 px-4 rounded;
	    }
	    .btn-red:hover {
	        @apply bg-red-900;
	    }
	    
	    .alert {
	        @apply bg-blue-100 border-l-4 border-blue-500 text-blue-700 p-4 m-32;
	    }
	    .alert-warning {
	        @apply bg-yellow-100 text-yellow-700 border-yellow-500;
	    }
	    .alert-info {
	        @apply bg-indigo-100 text-indigo-700 border-indigo-500;
	    }
	    .alert-danger {
	        @apply bg-red-100 text-red-700 border-red-500;
	    }
	    .alert-success {
	        @apply bg-green-100 text-green-700 border-green-500;
	    }
	    
	    
	    @tailwind utilities;
	    
	```

* **Daniel Jonguitud** (2)

	
	Colores y Dimesiones:
	``` 
	    <divclass="flex mt-20 justify-center">
	          <buttonclass="btn w-full lg:w-1/2 bg-blue-900">
	            <spanclass="text-blue-100">Botón</span>
	          </button>
	        </div>
	    
	```
	
	Display y Flexbox, Pseudo—Class Variants:
	``` 
	    div class="flex flex-wrap mt-2">
	            <button class="active:bg-black hover:bg-green-900 w-full sm:w-1/3 p-4 bg-green-500 border">
	                <span class="hover:text-green-400 text-green-100">Botón</span>
	            </button>
	            <button class="active:bg-blue-800 hover:bg-yellow-800 w-full sm:w-1/3 p-4 bg-red-800 border">
	                <span class="text-red-100">Botón</span>
	            </button>
	            <button class="active:bg-blue-800 hover:bg-green-800 w-full sm:w-1/3 p-4 bg-yellow-800 border">
	                <span class="text-yellow-100">Botón</span>
	            </button>
	            </div>
	    
	```
	
	Extraer componentes usando @apply:
	``` 
	    .alert {
	        @apply font-bold mx-10 my-10 p-10 border-4;
	    }
	    
	    .alert-default {
	        @apply bg-gray-500 text-gray-100;
	    }
	    
	    .alert-danger {
	        @apply bg-red-500 text-gray-100;
	    }
	    
	    .alert-warning {
	        @apply bg-yellow-500 text-gray-100;
	    }
	    
	    .alert-info {
	        @apply bg-blue-500 text-gray-100;
	    }
	    
	```

* **LeoEsp** (1)

	
	Primer reto
	``` 
	        <divclass="m-10">
	            <button class="bg-blue-600 text-white h-10 borde sm:w-full rounded-lg md:w-1/3 lg:w-1/6">
	                Boton
	            </button>
	        </div>
	    
	```
	
	Segundo reto
	``` 
	        <div class="m-4 flex justify-center">
	            <button class=" bg-green-500 hover:bg-green-900 hover:text-white px-4 py-1">Boton 1</button>
	            <button class=" bg-teal-500 hover:bg-teal-900 hover:text-white px-4 py-1">Boton 2 </button>
	            <button class=" bg-red-500 hover:bg-red-900 hover:text-white px-4 py-1">Boton 3</button>
	        </div>
	    
	```
	
	Tercer reto
	``` 
	    .alert{
	        @apply bg-red-500;
	        @apply text-black;
	        @apply m-4;
	        @apply p-4;
	        @apply rounded-l;
	        @apply w-64;
	    }
	    
	    .alert-danger{
	        @apply bg-red-700 ;
	        @apply text-white;
	    }
	    
	    .alert-warning{
	        @apply bg-yellow-500;
	    }
	    
	    .alert-info{
	        @apply bg-blue-700;
	        @apply  text-white;
	    }
	    
	    
	```

# Proyecto: PlatziFood

## 0160. Creando una card

### Descripción:


### Links:

* [Beautiful Free Images & Pictures | Unsplash](https://unsplash.com/)

### Comentarios:

* **Nathaly Stefani Riaño Bejarano** (5)

	
	Url de la imagen  
	[https://images.unsplash.com/photo-1568901346375-23c9450c58cd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&h=500&q=80](https://images.unsplash.com/photo-1568901346375-23c9450c58cd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&h=500&q=80)

* **Abner Batz** (1)

	
	Así quedó, tan sencillo como no me lo imaginé, increíble.
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	    <head>
	        <metacharset="UTF-8">
	        <metaname="viewport"content="width=device-width, initial-scale=1.0">
	        <title>Card /Producto </title>
	        <linkrel="stylesheet"href="css/style.css">
	    </head>
	    <bodyclass="min-h-screen bg-gray-400 mx-4">
	        <divclass="bg-white mt-4">
	            <imgsrc="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&h=500&q=80"alt="">
	            <h2>titulo</h2>
	            <p>descripcion</p>
	            <div>precio</div>
	            <div>Calificación /reseñas </div>
	        </div>
	        
	    </body>
	    </html>```
	    
	```

## 0170. Aplicando formato a la card

### Descripción:


### Links:

* [Curso de Fundamentos e Introducción al Diseño | Platzi](https://platzi.com/cursos/fundamentos-diseno/)

### Comentarios:

* **Abner Batz** (2)

	
	Una practica que @Victor Yoalli Dominguez ha aprendido como diseñador es que; ****el negro** es muy fuerte** para la vista, cuando se está leyendo. ★★★★★

* **Abraham Caso Torres** (1)

	
	[unsplash.com](http://unsplash.com) lo maximo

* **Nathaly Stefani Riaño Bejarano** (1)

	
	Me gusta que comparta los conocimientos que ha aprendido del diseño! 💚
	``` 
	    <body class="min-h-screen bg-gray-400 m-4">
	      <div>
	        <div>
	          <img
	            class="rounded-lg"
	            src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&h=500&q=80"
	            alt="Hamburger"
	          />
	        </div>
	        <div class="bg-white rounded-lg shadow-lg relative -mt-2 mx-2 p-2">
	          <h2 class="text-xl tracking-tight uppercase font-semibold text-gray-900">
	            Hamburguesa con Queso
	          </h2>
	          <p class="text-gray-700 leading-snug">Hamburguesa con queso y aderezo de chipotle</p>
	          <div class="my-2 text-sm font-semibold text-gray-700">MXN $15</div>
	          <div class="text-yellow-600">&starf;&starf;&starf;&starf;&star; / 36 reseñas</div>
	        </div>
	      </div>
	    </body>
	    
	```

## 0180. Responsive design en la card

### Descripción:


### Links:

* [Cards - Tailwind CSS](https://tailwindcss.com/components/cards/)

### Comentarios:

* **José Alfonso Vargas Cruz** (4)

	
	Para los que quieran probar de forma más sencilla la parte responsive existe una extensión en chrome (y derivados) y firefox para darte una vista de como se ve en cada dispositivo es muy útil, se llama Responsive Viewer.
	
	Chrome: <https://chrome.google.com/webstore/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb>  
	Firefox: <https://addons.mozilla.org/es/firefox/addon/responsiveviewer/>

	* **Fernando Vallejo** (1)

		
		f12

* **Daniel Jonguitud** (1)

	
	Algo que me percate al revisar los diferentes diseños, es que al pasar la vista para iPhone a horizontal, la foto queda pegada a la izquierda en vez extenderse por la pantalla, para solucionar esto, lo único que hice fue quitar la propiedad responsiva de w-full dentro de la imagen para que se aplicará a todos los formatos y me funciono bien. Esto con motivo para que se vea bien o al menos alineado en todos los dispositivos.

	* **Nathaly Stefani Riaño Bejarano** (4)

		
		Gracias!
		
		Adicionalmente, se le puede quitar el box-shadow a la sección de la descripción del producto con:
		``` 
		    md:shadow-none
		    
		```

## 0190. Construye el header

### Descripción:


### Comentarios:

* **Diegoalesco95** (7)

	
	Enlace del logo en el repositorio: [Imagen](https://github.com/victoryoalli/platzifood/blob/master/public/images/logo-w.svg)

	* **CodingLeonardo** (1)

		
		Gran aporte

* **Abner Batz** (2)

	
	¿Por que no actualiza el color primary o secondary, pero si lo reconoce el intellisense?
	
	Corrí el comando **npm run build** , hasta entonces si actualiza.  
	pero esto no lo hizo @victor, **¿que me faltó?**

	* **erikAZ** (1)

		
		me pasaba lo mismo, actualice la version de npm y quedo no se en que tenga q ver

	* **erikAZ** (1)

		
		por cierto el intellisense no lo reconoce VSC, hiciste algo en especial?

* **Abner Batz** (1)
¿Por que no actualiza el color primary o secondary, pero si lo reconoce el intellisense? Corrí el comando npm run build, hasta entonces s...

	* **Karla Agraz** (1)

		
		npx tailwindcss build css/tailwind.css -o public/css/style.css

## 0200. Crea el footer

### Descripción:


### Links:

* [Bootstrap · The most popular HTML, CSS, and JS library in the world.](https://getbootstrap.com/)

* [Beautiful Free Images & Pictures | Unsplash](https://unsplash.com/)

### Comentarios:

* **Jaime David Burbano Montoya** (5)

	
	Para agregarle un transition al hover pueden usar las siguientes etiquetas
	``` 
	    <divclass="hover:text-primary cursor-pointer transition ease-out duration-200" > <i class="fa fa-facebook"></i> Facebook </div>
	    <divclass="hover:text-primary cursor-pointer transition ease-out duration-200" > <i class="fa fa-twitter"></i> Twitter </div>
	    <divclass="hover:text-primary cursor-pointer transition ease-out duration-200" > <i class="fa fa-instagram"></i> Instagram </div>
	    
	```
	
	Con la etiqueta **cursor-pointer** van a hacer que aparezca el dedo del click al hacer hover.  
	Con la etiqueta **transition** van a hacer que el hover tenga una transición en las propiedades que cambian con el hover.  
	Con la etiqueta **ease-out** van a colocar la velocidad de la animación de transición. Pueden ver toda la documentación en [www.tailwindcss.com/docs/transition-timing-function/#/app](www.tailwindcss.com/docs/transition-timing-function/#/app)  
	Con la etiqueta **duration-200** pueden modificar el tiempo que dura la animación. Esta puede ser modificada dede el 200.

	* **Nathaly Stefani Riaño Bejarano** (1)

		
		Genial! Gracias 👏

	* **Kevin Brayan Luna Figueroa** (1)

		
		Muchas gracias por el aporte!

	* **Karla Agraz** (1)

		
		Gracias, muy útil :3

* **Abraham Caso Torres** (1)

	
	<link href=“<https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css>” rel=“stylesheet” integrity=“sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN” crossorigin=“anonymous”>

## 0210. Crea un banner

### Descripción:


### Links:

* [Font Awesome · BootstrapCDN by StackPath](https://www.bootstrapcdn.com/fontawesome/)

### Comentarios:

* **Nathaly Stefani Riaño Bejarano** (2)

	
	Url de la imagen:  
	[https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=667&q=80](https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=667&q=80)

	* **Moisés Cedeño** (1)

		
		Gracias nuevamente 😄

* **Abraham Caso Torres** (1)

	
	npm run watch

* **lmduran12** (1)
Existe alguna manera de tener la imagen en un h-64 y mover un poco hacia arriba o abajo la imagen, en vez de bg-center bg-top o bg-bottom?

	* **pabloverduzcos** (1)

		
		Creo que te refieres a esto: <https://tailwindcss.com/docs/background-position/>

* **piliangie** (1)
Genero el archivo pero no funciona, tengo esta configuracion module.exports = { theme: { fontFamily: { display: [“Gilroy”, “sans-serif”],...

	* **CarlosAlba** (1)

		
		Hola!
		
		En las dependencias del **package.json** deberías tener por lo menos **build** corriendo.
		``` 
		    "devDependencies": {},
		      "scripts": {
		        "build": "postcss css/tailwind.css -o public/css/style.css",
		        "dev": "postcss css/tailwind.css -o public/css/style.css --watch"
		      },
		    
		```
		
		Yo tengo corriendo **dev** me permite ver sin pausas en tiempo real los cambios.  
		Pero debes recordar que para pausarlos usas **ctrl + c**

* **Luis castro** (1)
por que no me corre el npm run watch C:\xampp\htdocs\platzifood (platzifood@1.0.0) λ npm run watch npm ERR! missing script: watch npm ER...

	* **Erik Ochoa (Platzi)** (1)

		
		Revisa tu archivo _package.json_ ya que no tienes un script llamado “watch”.

## 0220. Cómo integrar una card

### Descripción:


### Links:

* [Beautiful Free Images & Pictures | Unsplash](https://unsplash.com/)

### Comentarios:

* **Moisés Cedeño** (1)

	
	En esta clase, en el minuto 8:00 en lugar de darle un margin a alguno de los elementos convendría mejor usar un grid-gap, ya que esto le da espacio a los hijos del container por igual y no a uno con respecto a otro. Lo veo mejor.
	
	Lo aprendí del curso de Responsive Design de Leonidas Esteban.

## 0230. Forms

### Descripción:


### Comentarios:

## 0240. Directivas de Apply

### Descripción:


### Comentarios:

* **LeoEsp** (1)

	
	Siento que esta clase debería ir al principio del curso, hay un reto que pide usar apply  
	(Se que leyendo la documentación se puede resolver solo es una recomendación de mi parte)

* **Kevin Brayan Luna Figueroa** (1)

	
	@apply me ha gustado mucho su funcionalidad!

* **Alejandro Daniel Oroncoy Almeyda** (1)

	
	Muy buen función de taiwind!

	* **Aaron Gonzalez (Platzi)** (1)

		
		Las `@apply` son de los mejores features que tiene TailwindCSS. Actualmente ya cuenta con soporte para Grid-System 😉 más adelante tenemos toda una clase sobre esto.

## 0250. Extraer componentes

### Descripción:


### Comentarios:

## 0260. Navbar

### Descripción:


### Comentarios:

* **Exequiel Exequiel Ramón Dos Santos** (1)

	
	Se que algunos como yo van a querer agregar el icono de la lupa en el input!! si quieren solo tienen que poner:
	``` 
	    <input class="form-control "type="text" placeholder="&#xf002; Search">
	    
	```
	
	y cualquier icono se puede solo tienen que reemplazar el codigo unicode.

## 0270. Alpine JS

### Descripción:


### Links:

* [GitHub - alpinejs/alpine: A rugged, minimal framework for composing JavaScript behavior in your markup.](https://github.com/alpinejs/alpine)

### Comentarios:

* **Jaime David Burbano Montoya** (4)

	
	Con las siguientes etiquetas pueden animar la transición del toggle del navbar.  
	Estas etiquetas van en donde tienen la propiedad **x-show=‘open’** .
	``` 
	    x-transition:enter="transition ease-linear duration-300"
	    x-transition:enter-start="opacity-0 transform -translate-y-4"
	    x-transition:enter-end="opacity-100 transform translate-y-0"
	    x-transition:leave="transition ease-linear duration-300"
	    x-transition:leave-start="opacity-100 transform translate-y-0"
	    x-transition:leave-end="opacity-0 transform -translate-y-4"
	    
	```
	
	En la etiqueta **x-transition:enter** van todas las propiedades de la duración de la animación de entrada  
	En la etiqueta **x-transition:enter-star** van todas las propiedades iniciales de estilos de la etiqueta, algo así como como el “frame 0”% de la entrada  
	En la etiqueta **x-transition:enter-end** van todas las propiedades finales de estilos de la etiqueta, algo así como como el “frame 100%” de la entrada  
	.  
	.  
	En la etiqueta **x-transition:leave** van todas las propiedades de la duración de la animación de salida  
	En la etiqueta **x-transition:leave-start** van todas las propiedades iniciales de estilos de la etiqueta, algo asi como como el “frame 0”% de la salida  
	En la etiqueta **x-transition:leave-end** van todas las propiedades finales de estilos de la etiqueta, algo así como como el “frame 100%” de la salida

	* **Daniel Jonguitud** (2)

		
		Esto esta muy bueno, gracias!!

	* **carlosob** (1)

		
		Buen aporte!! Gracias saludos…

* **Ariel Fernando Mejia** (1)

	
	A los filtros le puedes agregar mas parametros al metodo x-show para que la transicion sea mas suave:
	``` 
	    x-show.transition.duration.600ms="open"
	    
	```
	
	Por detrás show sin mas parametros anade un toggle con display block y display none, mientras que con mas paremetros agregar algunas transiciones. [documentacion de x-show:](https://github.com/alpinejs/alpine#x-show)

* **Abraham Caso Torres** (1)

	
	<https://github.com/alpinejs/alpine>

* **Abraham Caso Torres** (1)

	
	@click=“open = true”

* **Abraham Caso Torres** (1)

	
	<script src=“<https://cdn.jsdelivr.net/gh/alpinejs/alpine@v2.x.x/dist/alpine.min.js>” defer></script>

* **Nathaly Stefani Riaño Bejarano** (1)

	
	Me encantan las herramientas adicionales que se aprenden en los cursos de Platzi! 💚

* **Jaime David Burbano Montoya** (1)

	
	Aquí esta el source del CDN
	
	“<https://cdn.jsdelivr.net/gh/alpinejs/alpine@v2.x.x/dist/alpine.js>” defer

## 0280. Optimiza tu archivo PurgeCSS y NanoCSS

### Descripción:


### Purge CSS & Nano CSS

Este es el contenido del archivo de configuración `postcss.config.js`completo.  
Es Importante agregar la línea de:  
`defaultExtractor: content => content.match(/[\w-/:]+(?<!:)/g) || []`  
Para el correcto funcionamiento de Pseudo-classes.
``` 
    const purgecss = require('@fullhuman/postcss-purgecss')
    module.exports = {
     plugins: [
     require('tailwindcss'),
     require('autoprefixer'),
     purgecss({
     content: [
     './**/*.html',
     //Para agregar soporte para otro tipo de archivos.
     // './**/*.js',
     // './**/*.vue'
     ],
     //IMPORTANTE: Para soportar pseudo-clases
     defaultExtractor: content => content.match(/[\w-/:]+(?<!:)/g) || []
     }),
     require('cssnano')({
     preset: 'default',
     })
     ]
    }
```

### Links:

* [Introduction | PurgeCSS](https://purgecss.com/#table-of-contents)

* [cssnano: A modular minifier based on the PostCSS ecosystem.](https://cssnano.co/)

### Comentarios:

* **Nathaly Stefani Riaño Bejarano** (6)

	
	 **Importante** No olvidar la línea defaultExtractor para que sigan funcionando los breakpoints del responsive design y las pseudoclases que utilizamos en el proyecto!  
	.  
	_post.config.js_
	``` 
	    const purgecss = require("@fullhuman/postcss-purgecss");
	    
	    module.exports = {
	      plugins: [
	        require("tailwindcss"),
	        require("autoprefixer"),
	        purgecss({
	          content: ["./**/*.html"],
	          defaultExtractor: content => content.match(/[\w-/:]+(?<!:)/g) || [],
	        }),
	        require("cssnano")({
	          preset: "default",
	        }),
	      ],
	    };
	    
	```

	* **Ariel Fernando Mejia** (1)

		
		Ojo este comentario es tremendamente util gracias!!!

* **Christian España** (2)

	
	Muchas mas utilidades con tailwind  
	<https://github.com/aniftyco/awesome-tailwindcss>

* **Christian España** (2)

	
	Vue.js UI library using Tailwind CSS.  
	<https://github.com/alfonsobries/vue-tailwind>

* **Christian España** (2)

	
	React UI components using tailwindcss  
	<https://github.com/knipferrc/tails-ui>

* **Christian España** (2)

	
	Formularios en tailwind  
	<https://github.com/tailwindcss/custom-forms>

* **Christian España** (2)

	
	Otro plugin para PostCSS  
	<https://stylelint.io/> StyleLint is a modern CSS linter that proofreads and validates your CSS code.

* **Erick Daniel Pérez Mata** (2)
¿PurgeCSS se puede usar con Bootstrap o Foundation?

	* **CarlosAlba** (1)

		
		Hola!
		
		Según la página de [Purge ](https://purgecss.com/#table-of-contents)CSS sí, funciona para Bootstrap, foundation, materialize y Tailwind.

* **Jaime David Burbano Montoya** (1)

	
	* _Configuración del archivo postcss.config.js_
	``` 
	    const purgecss = require('@fullhuman/postcss-purgecss')
	    
	    module.exports = {
	      plugins: [
	          require('tailwindcss'),
	          require('autoprefixer'),
	          purgecss({
	            content: ['./**/*.html']
	          }),
	          require('cssnano')({
	            preset: 'default',
	        }),
	    
	        ]
	      }
	    
	```

* **Jaime David Burbano Montoya** (1)

	
	**Comando para instalar nanoCss**
	``` 
	    $ npm i cssnano --save-dev
	    
	```

* **Jaime David Burbano Montoya** (1)

	
	Comando para instalar purgecss
	``` 
	    $ npm i -D @fullhuman/postcss-purgecss
	    
	```

* **Christian España** (1)

	
	Bootstrap tables en tailwind  
	<https://github.com/drehimself/tailwindcss-tables>

# Conclusiones

## 0290. Conclusiones y qué sigue

### Descripción:


### Links:

* [GitHub - victoryoalli/platzifood: Material del curso de Tailwind CSS en @platzi](https://github.com/victoryoalli/platzifood)

* [🚀Platzi: ‎Cursos Online Profesionales de Tecnología](https://platzi.com/clases/learning-path/escuela-js)

* [🚀Platzi: ‎Cursos Online Profesionales de Tecnología](https://platzi.com/clases/learning-path/arquitecto/)

* [Obtén un mes gratis en Platzi](https://platzi.com/blog/un-mes-gratis-en-platzi/)

### Comentarios:

* **Nathaly Stefani Riaño Bejarano** (4)

	
	👇 Excelente Cheat Sheet de Tailwind CSS  
	<https://nerdcave.com/tailwind-cheat-sheet>

* **Christian España** (2)

	
	Muchas mas utilidades con tailwind  
	<https://github.com/aniftyco/awesome-tailwindcss>

	* **Nathaly Stefani Riaño Bejarano** (2)

		
		Uff! Gran aporte, muchas gracias 💚

* **Ariel Fernando Mejia** (1)

	
	Realmente increible curso por todos lados asi debieran ser siempre los cursos de platzi, una seccion de intro, una de ensenar ailsado cada funcionalidad y cada explicacion muy concisa y una seccion de proyecto con un scope llamativo pero corto, aparte extras como purgecss, nanocss y alpineJS increible, muchisimas gracias que buen curso

* **Wonder Jhonny Diaz Gonzalez** (1)

	
	Si quieren ver componentes de la comunidad  
	[Tailwind Components  
	](https://tailwindcomponents.com/)

* **Erick Daniel Pérez Mata** (1)
¿Comó sería el deployment en GitHub?

	* **CarlosAlba** (1)

		
		Hola!
		
		Tendrías que hacer deploy del contenido de **public** como lo harías con cualquier optro deploy.

