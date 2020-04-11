# Bienvenida e Introducción

## 0010. Bienvenida y Presentación del proyecto PlatziRooms

### Descripción:


¡Bienvenido al Curso Avanzado de Vue.js por Bedu!

En este curso vamos a aprender a construir interfaces de usuario profesionales sin dejar de lado la simplicidad y legibilidad de nuestro código. El proyecto es una aplicación como Airbnb para gestionar viviendas y registrar usuarios con Firebase.

En esta ocasión nos acompaña Javier Diaz Chamorro, él trabaja en [CulturaColectiva](https://culturacolectiva.com/) como ingeniero de frontend y es experto del Bootcamp de Fullstack en Bedu.

### Comentarios:

* **Jorge Eliecer Rangel Jimenez** (2)

	```
	    vue create vuebnb
	    
	```
	
	😃

	* **coderdiaz** (2)

		
		Excelente nombre, no se me había ocurrido 🤔

	* **carllewisc** (1)

		
		Saludos. Hay un eBook donde se también se trata de imitar AriBnb.
		
		El eBook se llama Full-Stack Vue.js 2 and Laravel 5.
		
		El escrito le llamo al proyecto vuebnb. Es un buen libro para ver como conectar Vue con un Back-End en Laravel.
		
		Link del proyecto: <https://vuebnbapp.herokuapp.com/>

* **Juan David Castro (Platzi)** (2)

	
	¿Notaron que el nombre de usuario del profe es **espectacular**?
	
	  * 👉 [**coderdiaz**](https://github.com/coderdiaz) 🎉
	
	

	* **Juan David Castro (Platzi)** (2)

		
		<https://coderdiaz.me> 👏

* **jonathan sanchez** (1)

	
	Un buen inicio para el curso vamos con todo.

* **predator0077** (1)

	
	Vamos a darle con todo

* **Kingsman7** (1)

	
	Bien. gran proyecto

* **Jhon Alexander Perez Valencia** (1)

	
	muy bueno!!!

* **Sebastián Pineda Duque** (1)
¿Y lo que dice el título? ¿Qué se debe saber?

	* **Kevin Javier Morales (Platzi)** (2)

		
		Programación Básica, Javascript, Vue

* **Sebastián Pineda Duque** (0)

	
	¿Y lo que dice el título? ¿Qué se debe saber?

	* **Kevin Javier Morales (Platzi)** (2)

		
		Programación Básica, Javascript, Vue

## 0020. Creación y configuración inicial del proyecto utilizando VUE CLI 3

### Descripción:


[Vue CLI](https://cli.vuejs.org/) es una herramienta oficial de Vue.js que nos ayuda a crear proyectos con una muy buena configuración por defecto que podemos extender y personalizar de acuerdo a nuestros proyectos.

Comando de instalación con [Yarn](https://yarnpkg.com/):
``` 
    bash
    yarn global add @vue/cli
    
```

Si la instalación fue exitosa vamos a tener un nuevo comando en la terminal: `vue`.

La versiones anteriores de Vue CLI usabamos el comando `vue init` para descargar una plantilla con configuración por defecto. Sin embargo, con la nueva versión podemos usar el comando `vue create` que nos permite elegir paso a paso las herramientas y sus diferentes configuraciones para desarrollar nuestro proyecto.

Recuerda que tener todas las configuraciones de tu proyecto en el archivo `package.json` puede ser confuso porque mezclamos las dependencias con sus configuraciones. Más bien, podemos usar archivos dedicados a la configuración de cada herramienta; es más limpio y fácil de detectar el lugar de nuestras configuraciones.

Por último, vamos a correr nuestro proyecto con el comando `vue serve`.

### Links:

* [Vue CLI](http://cli.vuejs.org)

* [](https://yarnpkg.com)

* [](https://yarnpkg.com)

### Comentarios:

* **omarmus** (6)

	
	También pueden crear un proyecto Vue con su interfaz gráfica ejecutando el comando:
	
	vue ui

	* **emanueljtc** (1)

		
		cierto es muy amigable

* **Esteban Ramos Fernández** (6)

	
	Para aquellos que usan Npm  
	npm install -g @vue/cli
	
	Para aquellos que usan Yarn  
	yarn global add @vue/cli

* **Jorge Eliecer Rangel Jimenez** (5)

	```
	    npm install -g @vue/cli
	    vue create platzi-rooms
	    
	```

* **José Francisco Ojeda Vera** (4)

	
	La herramienta que de ayudara en el desarrollo con vue es la vue devtool, la cual es una extension para el navegador, la puedes encontrar para chrome y firefox:  
	<https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=es>
	
	<https://addons.mozilla.org/es/firefox/addon/vue-js-devtools/>

* **Juan David Castro (Platzi)** (4)

	
	Instalación de Vue CLI con NPM (vamos, es muy fácil de “traducir” ¬¬ 😅😛):
	``` 
	    npm install -g @vue/cli
	    
	```

* **jonathan sanchez** (3)

	
	en la version de vue cli 4.1.2 las opciones para la creacion de proyectos sigue siendo igual a las que podemos ver en esta clase.

* **Sebastian Cardoso Castillo** (3)

	
	Existen también templates para empezar proyectos mas avanzados. <https://madewithvuejs.com/templates>

* **Juan David Castro (Platzi)** (3)

	
	🤔 ¿Cuál configuración de ESLint recomiendan para Vue?
	
	El profe recomienda la de Airbnb _(irónico, nuestro proyecto es una aplicación de viviendas 😂)_ pero he visto mucho por Twitter que Prettier está ganando terreno 👀😬.

	* **Edward Steven Ramos Palacios** (2)

		
		Eso finalmente depende de tu gusto. En mi caso siempre uso [standard.js](https://standardjs.com/) porque me gusta el estilo y los rules que se establecen allí.

	* **José Manuel Casani Guerra** (2)

		
		Y eso que importa? , Si podes combinar los EsLint de Vue , Airbnb , Prettier y trabajar tranquilo

* **ricardocelis (Platzi)** (2)

	
	<https://yarnpkg.com>

* **Antonio Luis Gil Rodríguez** (2)
En este caso...

* **jcruzquintero** (1)

	
	Para desinstalar versiones anteriores de vue:
	
	`npm uninstall vue-cli -g`

* **ferroblesh** (1)

	
	el CLI ya está en la versión 4  
	Este curso sigue siendo válido?

	* **sordonezg** (1)

		
		.

* **jesus-olivares661** (1)

	
	Voy a hacer una aplicación pero necesitaré de SEO, será que aplico esta config ó uso NUXT…?

	* **José antonio Cañizales** (2)

		
		Sí, necesitas SSR para el seo usa Nuxt.

* **FabianIgnacio** (1)
Chicos, cambie a windows 10 y ahora me da este error al intentar instalar el vue CLI npm WARN saveError ENOENT: no such file or directory...

	* **Manuel Ojeda** (2)

		
		  * Actualiza NPM e intenta de nuevo.
		  * Sigue los pasos descritos en la documentación de Vue CLI  
		<https://cli.vuejs.org/guide/installation.html>
		
		

* **jonatandana** (1)
Vue cli 3 no usa webpack ?

	* **Edward Steven Ramos Palacios** (2)

		
		No exactamente. Usa una configuración basada en plugins y que es extensible a través del file vue.config.js como lo dice la **[documentacion](https://cli.vuejs.org/guide/webpack.html)**  
		No tienes que preocuparte por ello ya que, si deseas agregar mas opciones al estilo webpack, puedes hacerlo de una manera similar.

* **Juan David Castro (Platzi)** (1)
🤔 ¿Cuál configuración de ESLint recomiendan para Vue? El profe recomienda la de Airbnb (irónico, nuestro proyecto es una aplicación d...

	* **Edward Steven Ramos Palacios** (2)

		
		Eso finalmente depende de tu gusto. En mi caso siempre uso [standard.js](https://standardjs.com/) porque me gusta el estilo y los rules que se establecen allí.

* **Julián Franco Salas** (0)
Que terminal utilizan?

	* **Demian Arenas (Platzi)** (3)

		
		Hola Julian, parece que el profesor tiene instalado ZSH con Oh-My-Zsh. Te recomiendo leer este blog para llevar [tu terminal al siguiente nivel](https://platzi.com/blog/lleva-tu-terminal-al-siguiente-nivel/)

## 0030. Boilerplate y Limpieza del proyecto

### Descripción:


### Comentarios:

* **Juan David Castro (Platzi)** (12)

	
	Notas de la clase:
	
	  * `App.vue` => Aquí está nuestra aplicación, la UI que se repite sin importar la ruta: mensajes bonitos, enlaces a otras vistas, el componente `<router-view />` para renderizar cada vista cuando sea necesario, etc.
	  * `router.js` => Pos el `vue-router`; el archivo de nuestro proyecto con las conexiones y definiciones de todas las partes de la aplicación.
	  * `views/cualquier-cosa.vue` => Las vistas de cada ruta que solo funcionan si las importas desde el router. Ex. Home.vue, About.vue, Careers.vue, etc.
	  * `components/cualquier-cosa.vue` => Cada componente o bloque de lego de la aplicación. Ex. Menu, Footer, Sidebar, Card, etc.
	  * `store.js` => Vuex.
	
	

* **Anthony Will Solsol Soplin** (4)

	
	Explicas cómo dejar un proyecto “limpio” y usar un boilerplate que nos brindas, pero no dejas en claro que son distintas opciones o formas para hacer el proyecto, dejas confundido a uno cuando hace todo eso y luego pides que nos descarguemos el archivo.

* **lalokob** (4)

	
	Si ibas a poner un “boilerplarte” para que hiccimos toooda la configuracion anterior y limpieza de codigo si al final de cuentas eso no se va a usar??!!

	* **Jesús Miguel Quinto Teran** (1)

		
		Me pregunto exactamente lo mismo!, supongo que fue para explicarnos como comenzar de 0

	* **emanueljtc** (1)

		
		no entendi tampoco el porque si se aplicaria un Boilerplate nos indicaron hacer lo anterior.

	* **Sebastian Cardoso Castillo** (1)

		
		Son dos caminos diferentes. Con uno comenzamos desde cero con nuestro preset y en el otro iniciamos un proyecto a partir de un boilerplate

* **jonathan sanchez** (2)

	
	como en comentarios anteriores, esta mal pensado en enseñarnos hacer una configuracion si no la vamos a usar.

* **Jesús Alberto Martínez Hernández** (2)

	
	Hago la misma pregunta que los demàs ¿Porque la configuración y explicaciones si no se iba a ocupar?

* **Jose Luis Colmenares** (2)

	
	Todo el problema es que cambió la versión de Tailwind y ahora no utiliza la que aparece aqui. Es buena idea cuando hagan este curso correr el ocmando `npm run install --save-exact`

* **Alejandro González Reyes** (2)

	
	Cual es la finalidad de importar una librería como tailwind.css desde webpack, si se puede hacer via link.  
	Ventajas, desventajas.?  
	Observo mucha configuración.  
	¿Que alguien me explique?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Al importarla en webpack tienes la ventaja que incluye todo en el bundle final y si tienes configurado por ejemplo para minificar entonces todos los archivos serán minificados para opttimizar su peso. Otra ventaja que tienes es que solo haces un request ya que todos los archivos css salen en un solo archivo en lugar de hacer varias peticiones.

* **Northerchild** (1)

	
	Se me hizo súper rara está clase toda la configuración de la anterior para nada

* **Jose Luis Colmenares** (1)

	
	Tengo problemas para instalar esta librería. me muestra un error con circular-json, no sé donde se encuentra eso y porqué está pasando

* **Bastian Hai Brish** (1)

	
	y el boilerplate?

	* **Anthony Will Solsol Soplin** (1)

		
		En la pestaña de Archivos y Enlaces amigo.

* **FabianIgnacio** (1)

	
	¿Gente alguien sabe por que ocurre este error? Ayuda pls  
	<https://drive.google.com/file/d/1lJuWHKxKuIwmKTMFE4FPfbRnc4rht8Ej/view?usp=sharing>

	* **FabianIgnacio** (1)

		
		Es al momento de ejecutar npm run serve

	* **aragonesteban (Platzi)** (3)

		
		Hola Fabian, debe ser por un error de sintaxis en el código, chequea el código y mira que no tengas nada particular que te esté causando el error.

	* **FabianIgnacio** (2)

		
		Gracias por contestar, lo que sucede es que me da justo después de instalar todo al momento de entrar al directorio y correr el “npm run serve”, me da ese error al final … borrare nodejs e instalaré todo de nuevo a ver que tal, ojala funcione.

	* **FabianIgnacio** (3)

		
		Ok, para la gente que tenga el mismo drama de nuevo… a mi me paso usando Windows 7 ( no se si sea relevante, pero algo me suena) con la versión de nodejs 12.2.0 (Actual) … lo que hice fue usar la LTS recomendada para la mayoria y ahí me funciono! Espero les sirva, saludos

* **antoniofloresonline** (1)

	
	El proyecto se ve genial!!. Saludos al maestro!

	* **coderdiaz** (1)

		
		Saludos Antonio, a desarrollar se ha dicho!

* **FabianIgnacio** (1)
¿Gente alguien sabe por que ocurre este error? Ayuda pls 

	* **FabianIgnacio** (1)

		
		Es al momento de ejecutar npm run serve

* **Alejandro González Reyes** (1)
Cual es la finalidad de importar una librería como tailwind.css desde webpack, si se puede hacer via link. Ventajas, desventajas.? Observ...

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Al importarla en webpack tienes la ventaja que incluye todo en el bundle final y si tienes configurado por ejemplo para minificar entonces todos los archivos serán minificados para opttimizar su peso. Otra ventaja que tienes es que solo haces un request ya que todos los archivos css salen en un solo archivo en lugar de hacer varias peticiones.

# Render Functions y JSX

## 0040. ¿Que son las Render Functions y JSX

### Descripción:


Las _render functions_ son funciones que se encargan de renderizar contenido, interpretar nuestros elementos escritos en JavaScript y transformarlos a código plantilla. Estas funciones proveen mayor control de la lógica de negocio y permiten una transición o curva de aprendizaje más ligera.

Frameworks como React utilizan estas funciones gracias a **JSX** (una _“JavaScript eXtension”_ ) porque nos permite escribir código JavaScript similar a HTML y XML. Nosotros vamos a utilizar un plugin para implementar estas características con Vue.

Desventajas:

  * En ocasiones suele volverse complicado
  * Perdemos algunas características y directivas del framework (`v-bind`, `v-if`, `v-for`)
  * Generalmente, hay muy poca documentación



### Links:

* [](https://yarnpkg.com)

* [JSX 2.0 · Issue #65 · facebook/jsx · GitHub](https://github.com/facebook/jsx/issues/65)

### Comentarios:

* **José Manuel Casani Guerra** (10)

	
	Como profesional de Vuejs , JSX en Vuejs es recomendable mayormente cuando vas a usar:
	
	  * Componentes funcionales (stateless)
	  * HOC (High Order Components)
	
	
	
	Para todo lo demas, facilmente puedes hacerlo con SFC (Single File Components)
	
	Vuejs, es como el premio nobel de la paz entre los programadores, ya que no discrimina ningun conocimiento que tengas, todo te sirve en Vuejs , ya sea que vengas de Angular o React o algun otro framework JS …

* **Juan David Castro (Platzi)** (8)
<h3> **Resumen de la clase:** </h3> ![](https://static.platzi.com/media/user_upload/REACTFORCEVUEWITHJSX-11624aa1-678f-46d3-8c59-5aed916ec472.jpg)

	* **antoniofloresonline** (2)

		
		hahahaha muy bueno!

	* **Jhon Alexander Perez Valencia** (1)

		
		muy bueno jajaj

	* **Juan David Castro (Platzi)** (1)

		
		  * [A Practical Use Case for Vue Render Functions: Building a Design System Typography Grid](https://css-tricks.com/a-practical-use-case-for-vue-render-functions-building-a-design-system-typography-grid/)
		
		

* **David Wagner** (5)

	
	Yo vengo de usar react y estaba mas acostumbrado a usar JSX y me parece muy chevere que tambien se pueda usar en VUE.  
	Asi mi curva de aprendizaje sera menos dolorosa jejeje 😃

	* **Melina Jacqueline onoriaga** (1)

		
		me paso lo mismo!! le venia dando duro al react, y encontrarme con Vue fue pan comido!

* **Esteban Ramos Fernández** (5)

	
	Render functions ha ganado bastante terreno dada la popularidad de react, una de las grandes cosas que tiene vue es que adopta técnicas modernas de desarrollo y las incorpora, esto no solo sirve para poder aprender la variedad de técnicas, también nos ahorra bastante tiempo al momento de querer aprender de otros frameworks como react, en lo personal me interesó bastante estas nuevas disciplinas

* **Brayan Murcia Sanchez** (3)

	
	voy a extrañar demasiado v-if :c

	* **Jhon Alexander Perez Valencia** (1)

		
		😂

	* **leotangram** (1)

		
		Yo no… eso me parece muy “Angular” `ng-if` prefiero JSX, es menos verboso

* **Juan David Castro (Platzi)** (2)

	
	🤔🔥 ¿Llegara a existir [JSX 2.0](https://github.com/facebook/jsx/issues/65)?

	* **Jhon Alexander Perez Valencia** (1)

		
		> tal vez en un futuro lejano

* **Juan David Castro (Platzi)** (1)

	
	🆚 Algunas **características o diferencias** de JSX (JavaScript) con HTML (XML):
	
	  * Siempre usamos _camelCase_ : `charset` es `charSet`, `tabindex` es `tabIndex`, `font-size` es `fontSize`, `first_name` es `firstName`, etc 🐫
	  * `Class` es `className` (no con el plugin de Vue) 🔪
	  * Podemos usar condicionales, variables o -casi- cualquier otra expresión:
	
	
	``` 
	    <h1>Hello, {user && formatName(user)}!</h1>
	    
	```
	
	  * Lo mismo para declarar atributos:
	
	
	``` 
	    <h1className={condition ? "green" : "red"}>Hello, JuanDC!</h1>
	    
	```

	* **Juan David Castro (Platzi)** (1)

		
		  * [Aprende JSX para mejorar tu nivel profesional con Vue (y React) | Platzi Blog](https://platzi.com/blog/vue-react-jsx/)
		  * [Vue.js ❤️ JSX | Medium](https://medium.com/@ianaya89/vue-js-%EF%B8%8F-jsx-abd4eb26ec9b)
		
		

	* **David Wagner** (2)

		
		El link de mediun muy bueno, gracias por el aporte 😃

## 0050. Preparando nuestro entorno para un prototipo

### Descripción:


Antes de crear nuestro primer componente con `createElement` debemos instalar el plugin o dependencia para generar prototipos pequeños y mostrarlos en el navegador. Un prototipo individual por cada componente de Vue.

### Links:

* [Instant Prototyping | Vue CLI](https://cli.vuejs.org/guide/prototyping.html#instant-prototyping)

* [@vue/cli-service-global  -  npm](https://www.npmjs.com/package/@vue/cli-service-global)

### Comentarios:

* **Esteban Ramos Fernández** (3)

	
	Es compatible bajo el uso de sintaxis pug (antiguamente llamado jade) ?

	* **Esteban Ramos Fernández** (2)

		
		Comparto la liga usando jsx con pug en vue
		
		<https://bluewings.github.io/pug-as-jsx-loader/>  
		<https://github.com/pugjs/babel-plugin-transform-react-pug>
		
		Para quienes usan React  
		<https://bluewings.github.io/pug-as-jsx-loader/>

* **Esteban Ramos Fernández** (3)

	
	NPM  
	npm install -g @vue/cli-service-global
	
	YARN  
	yarn global add @vue/cli-service-global

	* **Jhon Alexander Perez Valencia** (1)

		
		gracias

* **jonathan sanchez** (2)

	
	para la nueva version de vue-clic 4.1.2 el comando de instalacion es:
	
	`npm install -g @vue/cli @vue/cli-service-global`

	* **Northerchild** (1)

		
		Gracias

* **Jorge Eliecer Rangel Jimenez** (2)

	```
	    npm install -g @vue/cli-service-global
	    
	```

* **Juan David Castro (Platzi)** (2)

	
	😅 ¿Existe algún plugin así de React/Preact para generar **prototipos individuales** de cada componente?  
	🤔 Me suena [StoryBook](https://storybook.js.org/) 🎨.

* **Emilianoh** (1)

	
	Para el que le da el siguiente error:  
	(node:7897) UnhandledPromiseRejectionWarning: TypeError: Cannot read property ‘version’ of undefined  
	at module.exports (/usr/lib/node_modules/@vue/cli-service-global/node_modules/@vue/cli-plugin-eslint/index.js:18:27)  
	… [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.
	
	Instalar como dependencia del proyecto:  
	\- npm install eslint-plugin-vue  
	\- npm install babel-eslint

* **Xavier Alexandro Basir Jeffrey** (1)

	
	Estaba muy ancioso por hacer este curso pero al ejercutar el vue server me da este error
	
	Command vue serve requires a global addon to be installed.  
	Please run npm install -g @vue/cli-service-global and try again.
	
	Corro el comando que dice el mensaje pero no resuelve el problema. He visto recomendaciones a este error pero ninguna me ha servido.
	
	Me di cuenta que si corro el comando en mi carpeta de NodeJS ahí si funciona, me da a entender que tengo problemas con la instalación global y ya no se que hacer para solventarlo.
	
	Desinstale e Instale nuevamente todo, Node, Vue, Vue-cli y sigo con el mismo problema. Alguna idea? 😦

	* **Juan David Castro (Platzi)** (2)

		
		¡Hola! Puedes seguir los pasos alternativos de la documentación:
		``` 
		    yarn global add @vue/cli-service-global
		    
		```
		
		O también con NPX:
		``` 
		    npx vue-cli-service
		    npx vue-cli-service serve
		    
		```

* **Jesús Miguel Quinto Teran** (1)

	
	Alguno conoce como cambiar e host y port en **Vue serve** , según veo las opciones disponibles son muy pocas:
	``` 
	    Usage: serve [options] [entry]
	    
	    serve a .js or .vue filein development mode withzero config
	    
	    
	    Options:
	    
	      -o, --open  Open browser
	      -c, --copy  Copy local url to clipboard
	      -h, --help  output usage information
	    
	```

	* **Joaquin García Santiago** (2)

		
		Debes crear un archivo `vue.config.js`
		``` 
		    module.exports = {
		      devServer: {
		        port: 3080,
		      },
		    }
		    
		```
		
		para más información puedes consultar este enlace: [VUE devServer](https://cli.vuejs.org/config/#devserver)

* **Cristhian Daza** (1)

	
	App.vue
	``` 
	    <template>
	        <divid="app">
	            <button >Toggle Modal</button>
	        </div>
	    </template>
	    
	    <script>
	    exportdefault {
	        name: 'App'
	    }
	    </script>
	    
	    <style>
	    body {
	        background: #cecece;
	    }
	    
	    .modal {
	        position: absolute;
	        top: 50%;
	        left: 50%;
	        margin-right: -50%;
	        transform: translate(-50%, -50%);
	        width: 250px;
	        background: #fff;
	        padding: 15px;    
	    }
	    
	    .modal > .message {
	        margin: 0;
	        margin-bottom: 10px;
	    }
	    </style>
	    
	```

* **Alejandro González Reyes** (1)

	
	Haber si entiendo, cada archivo .vue es como un proyecto independiente con el comando vue serve

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		No. App.vue es el archivo de entrada, cada componente o contenedor lo creas con extensión .vue y estos son transpilados (pasado a js que entiende el navegador) pero el punto de entrada sigue siendo App.vue. Más adelante se explica esto con más detalle.

* **Gonzalo Cofré** (1)

	
	Al ejecutar `vue serve App.vue` me devuelve este error:
	
	`Command vue serve requires a global addon to be installed. Please run yarn global add @vue/cli-service-global and try again.`
	
	¿alguna idea?

	* **aragonesteban (Platzi)** (4)

		
		Parece que no has instalado globalmente el CLI de **Vue** , para esto corre el comando `npm install -g @vue/cli`.

	* **Xavier Alexandro Basir Jeffrey** (1)

		
		tengo este mismo problema y no lo he podido solucionar, alguna otra idea?

	* **bryanmedina** (1)

		
		tengo el mismo problema

* **Alejandro González Reyes** (1)
Haber si entiendo, cada archivo .vue es como un proyecto independiente con el comando vue serve

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		No. App.vue es el archivo de entrada, cada componente o contenedor lo creas con extensión .vue y estos son transpilados (pasado a js que entiende el navegador) pero el punto de entrada sigue siendo App.vue. Más adelante se explica esto con más detalle.

* **Gonzalo Cofré** (1)
Al ejecutar vue serve App.vue me devuelve este error: Command vue serve requires a global addon to be installed. Pleas...

	* **aragonesteban (Platzi)** (4)

		
		Parece que no has instalado globalmente el CLI de **Vue** , para esto corre el comando `npm install -g @vue/cli`.

* **Esteban Ramos Fernández** (1)
Es compatible bajo el uso de sintaxis pug (antiguamente llamado jade) ?

	* **Esteban Ramos Fernández** (2)

		
		Comparto la liga usando jsx con pug en vue
		
		<https://bluewings.github.io/pug-as-jsx-loader/>  
		<https://github.com/pugjs/babel-plugin-transform-react-pug>
		
		Para quienes usan React  
		<https://bluewings.github.io/pug-as-jsx-loader/>

## 0060. Creación de un componente con createElement

### Descripción:


### Links:

* [GitHub - vuejs/vue-devtools: ?? Browser devtools extension for debugging Vue.js applications.](https://github.com/vuejs/vue-devtools)

* [Vue.js devtools - Chrome Web Store](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)

### Comentarios:

* **Mateo Santiago Zapata Maldonado** (6)

	
	Peinen al profe!

	* **Jesús Miguel Quinto Teran** (1)

		
		jajajajjajajaj!.. .

	* **Kelly Jesus Salazar Sanchez** (1)

		
		😃

* **Juan David Castro (Platzi)** (6)

	
	 **¿Quieren crear su propia función`createElement` con Vainilla JS?**
	
	  * 👉 [Building a Simple Virtual DOM from Scratch - DEV Community](https://dev.to/ycmjason/building-a-simple-virtual-dom-from-scratch-3d05)
	
	

	* **Juan David Castro (Platzi)** (2)

		  * [Case Styles: Camel, Pascal, Snake, and Kebab Case: Which is best? - Medium](https://medium.com/@pddivine/string-case-styles-camel-pascal-snake-and-kebab-case-981407998841)
		
		

	* **Juan Reyes** (1)

		
		Gracias por ese aporte. Está muy bueno el articulo.

	* **Jhon Alexander Perez Valencia** (1)

		
		muy buen aporte

* **Esteban Ramos Fernández** (3)

	
	Es compatible aún la sintaxis de pug al codear con jsx?

	* **Esteban Ramos Fernández** (3)

		
		Comparto la liga usando jsx con pug en vue
		
		<https://bluewings.github.io/pug-as-jsx-loader/>  
		<https://github.com/pugjs/babel-plugin-transform-react-pug>
		
		Para quienes usan React  
		<https://bluewings.github.io/pug-as-jsx-loader/>

* **Esteban Ramos Fernández** (3)
Es compatible aún la sintaxis de pug al codear con jsx?

	* **Esteban Ramos Fernández** (3)

		
		Comparto la liga usando jsx con pug en vue
		
		<https://bluewings.github.io/pug-as-jsx-loader/>  
		<https://github.com/pugjs/babel-plugin-transform-react-pug>
		
		Para quienes usan React  
		<https://bluewings.github.io/pug-as-jsx-loader/>

* **rodrigo-carmona** (2)

	
	a alguien mas le pasa que le aparece un error al utilizar console.log
	
	dejo extracto del error :
	
	Unexpected console statement no-console

	* **chepix10** (2)

		
		Sí, a mí también me pasó. Puedes crear un archivo .eslintrc.js en el directorio de render-functions y colocarle lo siguiente:
		``` 
		    module.exports = {
		      rules: {
		        'no-console': process.env.NODE_ENV === 'production' ? 'error' : 'off',
		        'no-debugger': process.env.NODE_ENV === 'production' ? 'error' : 'off',
		      },
		    }
		    
		```
		
		y vuelves a ejecutar en la terminar el comando:
		``` 
		    vue serve App.vue
		    
		```

* **dgaribayr** (2)

	
	La clase está cada vez mas interesante. Mi consulta es:  
	¿Porqué es necesario usar @click.prevent en vez de @click?  
	Tengo entendido que eso se aplica para un button del tipo submit dentro de un formulario para evitar que se envíe el formulario en vez de realizar algun method. Pero en este caso no esta dentro de un formulario ni es del tipo submit, entonces ¿por qué usar @click.prevent ?

	* **aragonesteban (Platzi)** (5)

		
		Hola, esto es para evitar cualquier ejecución default que tengan lo botones en html, como por ejemplo recargar la página, entonces se agrega el prevent para prevenir eso y se ejecute como tú quieras.

	* **Manuel Ojeda** (2)

		
		Se utiliza @click.prevent cuando el botón se encuentra dentro de un tag <form> para evitar que haga alguna función como recargar la página, tal como lo menciona @aragonesteban

	* **Edward Steven Ramos Palacios** (2)

		
		Es el equivalente a lo que seria en JavaScript el
		``` 
		    functiondoSomething(event){
		      event.preventDefault()
		      ...
		    }
		    
		```
		
		y evita el comportamiento por defecto del browser.

* **jonathan sanchez** (1)

	
	una sintaxis valida para render es:
	``` 
	    render: function (createElement) {
	        return createElement(
	          'h1', 'hola mundo'
	        )
	      }```
	    
	```

* **dgaribayr** (1)
La clase está cada vez mas interesante. Mi consulta es: ¿Porqué es necesario usar @click.prevent en vez de @click? Tengo entendido que es...

	* **aragonesteban (Platzi)** (5)

		
		Hola, esto es para evitar cualquier ejecución default que tengan lo botones en html, como por ejemplo recargar la página, entonces se agrega el prevent para prevenir eso y se ejecute como tú quieras.

## 0070. Utilizando JSX para la creación de un componente

### Descripción:


JSX nos permite definir la estructura de nuestros componentes con una sintaxis similar a HTML con todos los beneficios de JavaScript. Recuerda que JSX es una _syntax sugar_ para escribir componentes con `createElement` y resulta muy útil o familiar si estamos familiarizados con React.

### Comentarios:

* **diegoCode** (7)

	
	en mi opinión, no me convence usar JSX en vue… 🤔

	* **lalokob** (3)

		
		creo que la unica funcionalidad es que te permite armar tus propios componentes con metodos y propiedades de forma mas “sencilla” tampoco me convence a mi… ni me gusto

* **Juan Pablo Calao Pérez** (5)

	
	Como aporte, en JSX se puede omitir el operador ternario utilizando el &&:
	``` 
	    render () {
	        return (
	          this.show && 
	          <divclass="modal">
	            <p>{this.message}</p>
	            <buttononClick={this.handleCancelClick}>Cancel</button>
	            <buttononClick={this.handleOkClick}>Ok</button>
	          </div>
	        )
	      },
	    
	```

	* **Juan Reyes** (1)

		
		Trucazo :v

* **Mateo Santiago Zapata Maldonado** (4)

	
	Todo Document Model de los Nodos del Arbol HTML tienen propiedades (redundante), a que voy CreateElement es una Forma “moderna” (tonta) de crear Nodos del DOM de forma muy VIU, a ver si me explico:
	
	Version Vanilla:
	``` 
	    const img = document.createElement('img');
	    img.src = 'https://media.giphy.com/media/cuPm4p4pClZVC/giphy.gif'
	    img.onClick = () => alert('Hola')
	    
	```
	
	Version super moderna, goku, kamekameha, zen o sama VIU:
	``` 
	    createElement('img', {
	        attrs: {
	            src: 'https://media.giphy.com/media/cuPm4p4pClZVC/giphy.gif',
	        },
	        on: {
	            click: function() {
	                alert('Hola');
	            }
	        }
	    
	```
	
	Ahora, se han dado cuenta algo en JSX? Cuando escribimos un onClick directamente escribimos es onClick en vez de onclick en minuscula como lo hacemos naturalmente?
	
	Explico porque, JSX crea nodos de forma dinamica en vanilla pero sin necesidad de instanciar las cosas, por ejemplo:
	
	Version JSX:
	``` 
	    return (
	    <CampoUsuario>
	    	<inputplaceHolder="Escribe aqui algo" />
	    <CampoUsuario/>
	    )
	    
	```
	
	JSX Traduce a Vanilla o a createElement de React o Vue Algo asi:
	``` 
	    const CampoUsuario = document.createElement('div');
	    CampoUsuario.id = '_CampoUsuario_';
	    const input = document.createElement('input');
	    input.placeHolder = 'Escribe aqui algo';
	    input.appendChild(input);
	    
	```

* **Alejandro González Reyes** (3)

	
	Me gusta mas JSX.  
	Pero me encantaría puedan dar más contexto dónde es necesario usar render functions en VueJS.  
	Algunos comentan en componentes statesless, pero que es eso?

	* **Edward Steven Ramos Palacios** (3)

		
		Los componentes stateless son aquellos que no tienen un estado en si, y por el contrario reciben los datos por propiedades.  
		por ejemplo:
		
		Este archivo MyImage.js (por darle un nombre. Puede ser cualquiera)
		``` 
		    exportdefault {
		      props: {
		        src: {
		          required: true,
		          type: String
		        }
		      },
		      render(createElement){
		        return createElement(
		          'img',
		          {
		            'attrs': {
		              'src': this.src
		            }
		          }
		        )
		      }
		    }
		    
		```
		
		y lo usarias igual:
		``` 
		    <MyImage
		          src="el/path/a/la/imagen.jpg">
		    </MyImage>
		    
		```

* **lenielluzardo** (2)

	
	A mi me gustaria saber es, qué utilidad le puedo dar a cada una de las formas de crear los componentes??? o es cuestion de gustos???.  
	Es decir, por un lado tenemos las SFC, por otro tenemos la creacion de componentes por medio de renderFunction(), y otra forma a traves de la sintaxis de JSX. La verdad todas me parecen espectaculares, pero, en que momento usar cual???

* **JoosCode** (2)
bueno entonces noto la complejidad porque yo no vengo de react seria entonces mejor aprender react ? y luego esta version extensa de vue ?

	* **Kevin Javier Morales (Platzi)** (2)

		
		No hace falta aprender necesariamente React, puede ir al curso de Vue <https://platzi.com/clases/vuejs/>

* **alan-saldivar** (1)

	
	La primera vez que tomé el curso no me quedaban los conceptos muy claros, pero ahora que React es mi pan diario desde hace unos meses es muy pero muy parecido.

* **ervic_alexis** (1)

	
	Se puede usar Bootstrap-Vue con JSx?

	* **Jhon Alexander Perez Valencia** (1)

		
		es posible

* **JoosCode** (1)

	
	bueno entonces noto la complejidad porque yo no vengo de react seria entonces mejor aprender react ? y luego esta version extensa de vue ?

	* **Kevin Javier Morales (Platzi)** (2)

		
		No hace falta aprender necesariamente React, puede ir al curso de Vue <https://platzi.com/clases/vuejs/>

	* **ricardocelis (Platzi)** (1)

		
		así es puedes comenzar con los otros cursos de Vue que te dejarán más que listo para este, saludos!

	* **coderdiaz** (1)

		
		No es necesario aprender React, puedes comenzar con los otros cursos básico y profesional de la carrera de Vue.js y posteriormente pasarte a este curso 😃

* **Esteban Ramos Fernández** (1)

	
	createElement es una nueva feature de vue para el desarrollo de componentes al estilo react y que facilita o más bien hace posible el entendimiento de dicha práctica para una posible migración o facilidad de uso entre react y vue escrita en sintaxis similar a html llamada jsx

	* **José Manuel Casani Guerra** (3)

		
		No es tan nueva que digamos , esta desde la version 2 de Vue

	* **coderdiaz** (1)

		
		Como nota: `createElement` no es un nuevo feature ya que tiene incorporado como menciona el compañero desde la versión 2, principalmente `createElement` es el eslabón principal ya que funge como un motor de interpretación de elementos en el DOM. Si tienen curiosidad, todo el código de templating que ustedes realicen ya sea en `template` o `jsx`, es interpretado a través del paquete `vue-template-compiler` y transpilado a elementos con `createElement`. Si tienen la curiosidad, compilen el proyecto como si lo lanzarán a producción y verifiquen el bundle de JavaScript.
		``` 
		    npm run build
		    
		```
		
		o
		``` 
		    yarnbuild
		    
		```

* **Juan David Castro (Platzi)** (1)

	
	Haber si entendí 🤔:
	
	Si `createElement` es una función super chevere para crear elementos de HTML. Y, JSX es una sintaxis super chevere de escribir `createElement` porque se parece a HTML… Entonces, JSX es una sintaxis muy parecida a HTML que “compila” a elementos de HTML con `createElement` que, por supuesto, compila a HTML ahora si de verdad 😅.

	* **Juan David Castro (Platzi)** (1)

		
		  * [JSX In Depth | React Docs](https://reactjs.org/docs/jsx-in-depth.html)
		
		

	* **José Manuel Casani Guerra** (1)

		
		JSX nacio de XHP , que es una forma de hacer template mediante XML e interpretadores javascript…
		
		JSX no es HTML , alli te equivocas , se parece al HTML para darle una confianza y usabilidad al codigo …

* **Alejandro González Reyes** (1)
Me gusta mas JSX. Pero me encantaría puedan dar más contexto dónde es necesario usar render functions en VueJS. Algunos comentan en compo...

	* **Edward Steven Ramos Palacios** (3)

		
		Los componentes stateless son aquellos que no tienen un estado en si, y por el contrario reciben los datos por propiedades.  
		por ejemplo:
		
		Este archivo MyImage.js (por darle un nombre. Puede ser cualquiera)
		``` 
		    exportdefault {
		      props: {
		        src: {
		          required: true,
		          type: String
		        }
		      },
		      render(createElement){
		        return createElement(
		          'img',
		          {
		            'attrs': {
		              'src': this.src
		            }
		          }
		        )
		      }
		    }
		    
		```
		
		y lo usarias igual:
		``` 
		    <MyImage
		          src="el/path/a/la/imagen.jpg">
		    </MyImage>
		    
		```

## 0080. Utilizando Slots con Render Functions y JSX

### Descripción:


Los _Slots_ nos ayudan a crear componentes reutilizables y personalizables al mismo tiempo, nos permiten definir el contenido de nuestros componentes para evitar el trabajo de crear un nuevo archivo por cada cambio en los componentes. Son muy útiles e importantes en el mundo de Vue.js.

### Links:

* [Slots — Vue.js](https://vuejs.org/v2/guide/components-slots.html)

### Comentarios:

* **José Manuel Casani Guerra** (8)

	
	Recuerden , que $slots.default es muy diferente a children …
	
	<https://vuejs.org/v2/guide/render-function.html#slots-vs-children>

	* **Facundo Petre** (1)

		
		Gracias por el aporte, estaba pensando que eran muy similares

	* **Freddy Córdova Arana** (1)

		
		Gracias por el tip 👍

* **Melvin Hernández** (4)

	
	 **Solucion**  
	En el componente ModalJsx
	``` 
	    render() {
	    	return (this.show) ? <div class="modal">
	    		<div class="content">{this.$slots.default}</div>
	    	</div> : null
	    }
	    
	```
	
	En el componente App
	``` 
	    <modal-jsx:show="show">
	    	<p>hello World</p>
	    </modal-jsx>
	    
	```

* **Matias Jesus Ruiz Ruiz** (3)

	
	Utilizando Slots en JSX!
	``` 
	    render() {
	        return (this.show) ? <divid="modal">
	          <divclass="content">{this.$slots.default}</div>
	          <buttononClick={this.clickCancelHandler}>Cancelar</button>
	          <buttononClick={this.clickOkHandler}>Ok</button>
	        </div> : null
	      },
	    
	    
	```

* **CioGDeveloper** (3)

	
	Hola! Tengo dudas sobre la necesidad real de incorporar funcionalidades de React a Vue, la verdad…creo que vue tiene por si mismo posibilidades de sobra para hacer cualquier cosa, estamos en 2019, pregunta: ¿Alguien sabe si JSX se utiliza en proyectos reales y qué perspectivas de crecimiento tiene actualmente en el ecosistema Vue? no he oido demasiado sobre esto últimamente…

	* **Edward Steven Ramos Palacios** (3)

		
		Desde mi experiencia no conozco proyectos que usen JSX con Vue. Vue tiene todas las capacidades para crear productos de alto rendimiento y listas para producción. Por ejemplo el sitio de [MTA](https://new.mta.info/) de NY usa Vue.js en su stack.  
		Para finalizar, según esta [encuesta](https://research.hackerrank.com/developer-skills/2019) que muestra, entre otras cosas, lo que los developers quieren aprender, el deseo de aprender Vue.js crecio un 2X comparado con el año 2018. Asi que adelante con Vue!

* **jgorocica** (3)

	
	Mi solución para agregar el slot al ModalJSX, fue agregar un div en el render del componente ModalJsx.vue, me quedó de la siguiente manera:
	``` 
	    return (this.show) ? <divclass="modal">
	          <divclass="content">
	            {this.$slots.default}
	          </div>
	          <buttononClick={this.clickCancelHandle} >Cancel</button>
	          <buttononClick={this.clickOkHandle}>Ok</button>
	        </div> : null
	    
	```
	
	Y por último, pasarle el contenido del slot desde App.vue
	``` 
	    <modal-jsx:show="show">
	         <h1>Titulo modalJsx</h1>
	         <hr>
	         <p> Hello world from AppVue </p>
	       </modal-jsx>
	    
	```

* **Nelson Manuel Ordaz Yglesias** (2)

	
	Los **slots** son secciones dentro de un componente, donde podemos cargar o reemplazar con elementos desde un elemento padre.
	
	Definiendo slot en uncomponente:
	``` 
	    render (createElement) {
	        return (this.show) ? createElement('div', {
	          class: 'modal',
	        }, [
	    		createElement('div', {
	            		class: 'content',
	       	 	 }, this.$slots.default)
	    
	```
	
	Cargando o reemplazando desde un elemento padre :
	``` 
	    <modal-create-element:show="show">
	    	<h1>Modal title</h1>
	    	<p>Hello World</p>
	    </modal-create-element>
	    
	```

* **Ludwing Juan Homero Pérez Tzaquitzal** (2)

	
	Mi código en ModalJsx.vue
	``` 
	    return (this.show) ? <divclass="modal">
	                    <divclass="content">{this.$slots.default}</div>
	                    <buttononClick={this.clickCancelHandler}>Cancel</button>
	                    <buttononClick={this.clickOkHandler}>Ok</button>
	                </div> : null
	    
	```
	
	Y mi código en App.vue
	``` 
	    <modal-jsx:show="show">
	                <h1>Slots JSX</h1>
	                <p>Hello world! con slots y jsx</p>
	            </modal-jsx>
	    
	```

* **Jesús Miguel Quinto Teran** (2)

	
	Solución JSX:
	``` 
	      render() {
	        return (this.show) ? <divclass="modal">
	          <div> {this.$slots.default} </div>
	          <buttononClick={this.clickCancelHandler}>Cancel</button>
	          <buttononClick={this.clickOkHandler}>Ok</button>
	        </div> : null
	      },
	    
	```
	
	Como dato interesante, con {{}} no funciona, tarde algo de tiempo en comprender que el equivalente en JSX es {}.

* **Alejandro González Reyes** (2)

	
	Mi aporte como colocar comentarios en JSX
	``` 
	    render () {
	            return (this.show) ? <divclass="modal">
	                {/* <p>{this.message}</p> */}
	                {this.$slots.default}
	                <buttononClick={this.clickCancelHandler}>Cancel</button>
	                <buttononClick={this.clickOkHandler}>Ok</button>
	            </div> : null
	        },
	    
	```
	
	``  
	<modal-jsx :show=“show” message=“Hola desde Jsx”>  
	<h1>Modal JSX</h1>  
	<p>Hola desde mi componente slot</p>  
	</modal-jsx>
	```
	```
	

* **Juan David Castro (Platzi)** (2)

	
	  * [Vue.js Slots - Flabio Copes](https://flaviocopes.com/vue-slots/)
	  * [Understanding Component Slots with Vue.js - Alligator.io](https://alligator.io/vuejs/component-slots/)
	  * [The Power of Scoped Slots in Vue](https://pineco.de/power-scoped-slots-vue/)
	  * [Practical Use of Vue.js Scoped Slots](https://itnext.io/new-unnamed-post-8da9cdbf5df3)
	
	

	* **Juan David Castro (Platzi)** (1)

		  * [Vue - how to pass down slots inside wrapper component?](https://stackoverflow.com/questions/50891858/vue-how-to-pass-down-slots-inside-wrapper-component)
		
		

* **César Ernesto Rivas Martínez** (1)

	
	**App.vue**
	``` 
	    <modal-jsx:show="showModal">
	    	<h1>Test Slot with JSX</h1>
	    </modal-jsx>
	    
	```
	``` 
	    <divclass="modal">
	            <divclass="content">{this.$slots.default}</div>
	            <buttononClick={this.cancelHandler}>Cancelar</button>
	            <buttononClick={this.okHandler}>Ok</button>
	    </div>
	    
	```

* **Anthony Will Solsol Soplin** (1)

	
	Buena explicación, sencilla y entendible

* **Juan Pablo Calao Pérez** (1)

	
	En **App.vue** :
	``` 
	    <modal-jsxmessage="Hello Jsx":show="show">
	        <p>Slot JSX</p>
	    </modal-jsx>
	    
	```
	
	En **ModalJsx.vue** :
	``` 
	    <divclass="modal">
	        <divclass="content">{this.$slots.default}</div>
	        <buttononClick={this.handleCancelClick}>Cancel</button>
	        <buttononClick={this.handleOkClick}>Ok</button>
	    </div>
	    
	```

* **Michael Rodriguez** (1)

	
	¿Que son los Slots?

	* **Jesús Miguel Quinto Teran** (2)

		
		Un Slot es una funcionalidad de Vuejs que te permite pasar un bloque de Html desde un componente padre a un componente hijo para este ultimo lo muestre como suyo. De esta forma podemos personalizar el html del componente hijo desde el padre.
		
		Con los **props** envías **datos** a los hijos  
		Con los **slots** envias **html** a los hijos

* **wilmaracaicedos** (1)

	
	Componente ModalJsx.vue
	``` 
	      render () {
	        return (this.show) ? <divclass="modal">
	          <divclass="content">
	            {this.$slots.default}
	          </div>
	          <buttononClick={this.clickCancelHandler}>Cancel</button>
	          <buttononClick={this.clickOkHandler}>Ok</button>
	        </div> : null
	      },
	    
	```
	
	Componente App.vue
	``` 
	    <modal-jsxv-bind:show="show">
	          <h1>Modal title</h1>
	          <p>Hello World</p>
	        </modal-jsx>
	    
	```

	* **Mateo Santiago Zapata Maldonado** (2)

		
		Me parece mucho mas Facil la forma natural de trabajo de Vue, ¿porque utilizar esto?

	* **Jorge Palacios** (2)

		
		Se usa para contenido hecho con programación en el sitio. Para aplicaciones más complejas.

* **Jorge Eliecer Rangel Jimenez** (1)

	
	ModalJsx.vue
	``` 
	    		render() {
	    		return (this.show) ? <divclass="modal">
	    			<divclass="content">{this.$slots.default}
	    				<buttononClick={this.clickCancelHandler}>Cancel</button>
	    				<buttononClick={this.clickOkHandler}>Ok</button>
	    			</div>
	    		</div> : null
	    	},
	    
	```

* **CioGDeveloper** (1)
Hola! Tengo dudas sobre la necesidad real de incorporar funcionalidades de React a Vue, la verdad…creo que vue tiene por si mismo posibil...

	* **Edward Steven Ramos Palacios** (3)

		
		Desde mi experiencia no conozco proyectos que usen JSX con Vue. Vue tiene todas las capacidades para crear productos de alto rendimiento y listas para producción. Por ejemplo el sitio de [MTA](https://new.mta.info/) de NY usa Vue.js en su stack.  
		Para finalizar, según esta [encuesta](https://research.hackerrank.com/developer-skills/2019) que muestra, entre otras cosas, lo que los developers quieren aprender, el deseo de aprender Vue.js crecio un 2X comparado con el año 2018. Asi que adelante con Vue!

## 0090. Creando un Modal de Login para PlatziRooms

### Descripción:


 **Vuex** es una librería para manejar el estado de nuestras aplicaciones con Vue.js. sin aumentar su complejidad. Esta herramienta facilita la comunicación entre componentes sin importar en qué parte de nuestra aplicación o del árbol de componentes nos encontremos.

Vuex utiliza un **_store_ centralizado**, un único lugar donde guardamos el estado compartido de nuestros componentes. Cada componente se comunica con el _store_ y este se encarga de comunicarse con toda la aplicación. Así, podemos comunicar más fácilmente todas las partes de nuestra aplicación sin importar su posición, ni siquiera si se trata de comunicar componentes hijos con sus padres.

En este caso, vamos a usar Vuex para controlar nuestro componente Modal.

### Links:

* [What is Vuex? | Vuex](https://vuex.vuejs.org)

### Comentarios:

* **Cristhian Daza** (6)

	
	Los estilos del Modal.vue
	``` 
	    <style scoped>
	    .modal {
	      min-width: 350px;
	      top: 50%;
	      left: 50%;
	      margin-right: -50%;
	      transform: translate(-50%, -50%);
	      z-index: 2000;
	       @apply absolute bg-white p-4 shadow-lg rounded;
	    }
	     .modal > .modal-head {
	      @apply relative;
	    }
	     .modal-wrapper::after {
	      content: "";
	      position: fixed;
	      top: 0;
	      left: 0;
	      width: 100vw;
	      height: 100vh;
	      background: rgba(37, 37, 37, 0.8);
	    }
	    </style>
	    
	```

	* **FabianIgnacio** (1)

		
		Gracias c:

* **Jesús Miguel Quinto Teran** (2)

	
	Guao! Hace unos meses cuando aprendía Vuex trabajé exactamente igual para progagar los estados de la modales desde distintos componentes!!.. 😋😋😋
	
	Que bonito se siente cuando la pensaste igual que el profe!!

* **Alejandro González Reyes** (2)

	
	¿Tenía entendido que tanto la mutacion como el action recibe el payload.?  
	pero en este caso ese payload lo declara dividido (name, value). A que se debe ello

	* **Miguel Herreros Cejas** (2)

		
		No es que lo envíe dividido. Es que envía dos valores, el nombre y el valor.

	* **Jesús Miguel Quinto Teran** (2)

		
		Éso se llama desestructuración de objecto. En el curso de fundamentos de Javascript lo explica muy bien.
		
		<https://platzi.com/clases/1339-fundamentos-javascript/12893-desestructurar-objetos/>

* **lenielluzardo** (1)

	
	hay inconsistencia entre los archivos del repositorio y los de la clase…

* **Nicolás Arias** (1)

	
	Cuál es el motivo de usar la acción para llamar la mutación en lugar de hacer el commit directamente en los componentes? Es por buenas prácticas?

* **Alejandro González Reyes** (1)
¿Tenía entendido que tanto la mutacion como el action recibe el payload.? pero en este caso ese payload lo declara dividido (name, value)...

	* **Miguel Herreros Cejas** (2)

		
		No es que lo envíe dividido. Es que envía dos valores, el nombre y el valor.

## 0100. Creando la lógica general de nuestros modales con Vuex

### Descripción:


Gracias a Vuex podemos comunicar componentes de diferentes partes de nuestra aplicación. Ahora, vamos a aprovechar esta funcionalidad para abrir nuestro modal cuando pulsamos el botón de _Login_ en el Header.

Para este debemos configurar nuestro componente de modal para solo activarse cuando la variable del _store_ es _true_. Así, podemos disparar un cambio a estas variables del _store_ desde cualquier parte de la aplicación (por ejemplo, con el boton de _login_ en el _header_ ) y abrir o cerrar el modal. Vamos a realizar este mismo proceso para cerrar el modal desde el icono de la X.

### Comentarios:

* **Juan David Castro (Platzi)** (7)

	
	  * [Comunicación entre componentes con Vue - Javier Diaz en Medium](https://medium.com/@coderdiaz/comunicaci%C3%B3n-entre-componentes-con-vue-js-94b9bf3003e) (artículo del porfe 😎)
	  * [Data Flow in VueJs — VueX Application](https://medium.com/@cyphertree_dev/data-flow-in-vuejs-vuex-application-112383d1a3ed)
	  * [Data Flow in Vue and Vuex: Share state across components](https://benjaminlistwon.com/blog/data-flow-in-vue-and-vuex/)
	  * [Should I Store This Data in Vuex? Why use Vuex in the first place? - Reasons for storing data in Vuex](https://markus.oberlehner.net/blog/should-i-store-this-data-in-vuex/)
	
	

	* **Freddy Córdova Arana** (1)

		
		Gracias por los artículos 😁👍

	* **Jhon Alexander Perez Valencia** (1)

		
		> (y)

* **jgorocica** (5)

	
	Les dejo aquí la regla de ESLint para copiar y pegar
	``` 
	    'no-param-reassign': ['error', {
	          props: true,
	          ignorePropertyModificationFor: [
	            'state', // for vuex state
	          ]
	        }]
	    
	```
	
	En mi caso tuve que cerrar y volver a abrir mi editor

	* **Jesús Alberto Martínez Hernández** (1)

		
		gracias!

	* **arnold025** (1)

		
		me dio un error al copiar el código que pusiste, pues la propiedad se llama **ignorePropertyModificationsFor**
		``` 
		        'no-param-reassign': ['error', {
		          props: true,
		          ignorePropertyModificationsFor: [
		            'state', // for vuex state
		          ]
		        }]
		    
		```

* **David Wagner** (3)

	
	En mi caso no me valio por que tenia que definir los los valores como json, con todo les dejo aqui lo que me funciono a mi
	``` 
	    "no-param-reassign": [
	          "error",
	          {
	            "props": true,
	            "ignorePropertyModificationsFor": [
	              "state",
	            ]
	          }
	        ],
	    
	```

* **Alejandro González Reyes** (2)

	
	Me pueden explicar que signficado tiene esta parte del código con respecto a la que yo declaré.  
	El profe
	``` 
	    mutations: {
	        SET_MODAL_STATE: (state, { name, value }) => {
	          state.modals[name] = value;
	        },
	      },
	      actions: {
	        TOGGLE_MODAL_STATE: ({ commit }, { name, value }) => {
	          commit('SET_MODAL_STATE', { name, value });
	        },
	      },
	    
	```
	
	Yo
	``` 
	    mutations: {
	        SET_MODAL_STATE(state, payload) {
	          // Se puede acceder a los atributos de un objeto mediante sintaxis de array
	          // apuntamos al modal (path) y cambiamos su valor (value)
	          state.modals[payload.name] = payload.value;
	        },
	      },
	      actions: {
	        TOGGLE_MODAL_STATE(context, payload) {
	          context.commit('SET_MODAL_STATE', payload);
	        },
	      },
	    
	```

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Lo que veo del código simplemente tu pasas los valores como objetos en el caso de payload en lugar de pasar los valores explícitos los pasas como un objeto y no pasas el commit si no el contexto que contiene el commit, son formas diferente de acceder a las variables, probablemente para mi es mas legible la que usa el profesor, pero hay que ver todo el código.

	* **Nelson Manuel Ordaz Yglesias** (2)

		
		La única diferencia es como envías la información de name y value. En ambos casos son objetos, sin embargo, en el primero caso se mandan los datos de forma explícita, y en el segundo de forma implícita.  
		Es como que enviaras un paquete (caja, bolsa, etc.) con dos productos (name y value) sin envolver, al descubierto, y en el otro caso envías el paquete pero, los productos van envueltos sin saber que son hasta que los abres. No se si me di a entender. Saludos.

* **wavilap** (1)
Hola y como podria detectar el cambio del estado si sale sin apretar los botones?

	* **Manuel Ojeda** (2)

		
		Dentro de Vue.js hay una propiedad que se le puede asignar a los **v-model** que son asigandos a un elemento HTML, digo atributo es **v-on:change** o **@change** , en esa propiedad puedes ejecutar un metodo que hará el cambio en el estado.
		``` 
		    <input v-model="tuModelo"type="text"@change="tuMetodo()" />
		    
		```

* **Alejandro González Reyes** (1)
Me pueden explicar que signficado tiene esta parte del código con respecto a la que yo declaré. El profe mutations: { SET_MODAL...

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Lo que veo del código simplemente tu pasas los valores como objetos en el caso de payload en lugar de pasar los valores explícitos los pasas como un objeto y no pasas el commit si no el contexto que contiene el commit, son formas diferente de acceder a las variables, probablemente para mi es mas legible la que usa el profesor, pero hay que ver todo el código.

## 0110. Creando el contenido de nuestro modal

### Descripción:


### Links:

* [Tailwind CSS - A Utility-First CSS Framework for Rapid UI Development](https://tailwindcss.com/docs/what-is-tailwind/)

### Comentarios:

* **Edward Steven Ramos Palacios** (9)

	
	Por si alguien se pregunta de donde saca las clases CSS => [TailWind](https://tailwindcss.com/docs/what-is-tailwind/)

	* **Jhon Alexander Perez Valencia** (1)

		
		Gracias 😃

	* **Nelson Manuel Ordaz Yglesias** (1)

		
		Muchas gracias.

* **Alejandro González Reyes** (3)

	
	Ok, finalmente comprendo la importancia de los slot

* **Edward Steven Ramos Palacios** (2)

	
	Login Form

	* **Jhon Alexander Perez Valencia** (1)

		
		(y)

* **Edward Steven Ramos Palacios** (2)

	
	El formulario de Login y Registro también pueden ser componentes y luego importarlos y usarlos dentro del modal.

	* **John Daison Agudelo S.** (1)

		
		Yo prefiero crear componentes (pensando en el principio de atomicidad) y usar slots solo para cosas que cambien poco como un componente de alertas donde pasamos el texto, color, icono. pero no para pasar todo un formulario completo, creo que esto seria una mala practica

# Componentes controlados y uso de librerías externas

## 0120. Componentes Controlados y Variables Personalizadas

### Descripción:


Los componentes controlados nos ayudan a tener el control sobre diferentes partes de un componente a través de parámetros.

Podemos usar la propiedad `v-model` para conectar variables con componentes y personalizar el contenido de la aplicación. Sin embargo, toda la lógica de nuestros componentes quedan en un mismo lugar, lo que los hace más difícil reutilizar. Por lo tanto, vamos a crear un nuevo componente para cada parte o funcionalidad reutilizable de nuestra aplicación pero configurados de tal forma que la lógica es controlada por los componentes padres, no por el mismo componente.

### Comentarios:

* **Juan David Castro (Platzi)** (6)

	
	Los componentes controlados son componentes super **reutilizables** que necesitan ser llamados por otros componentes para tener su lógica completa y funcionar correctamente.
	
	Es como si dejaran algunos últimos detalles de implementación para después pero, en realidad, le dejan la tarea al componente papá para poder funcionar de formas diferentes de acuerdo a las necesidades de cada parte de la aplicación.
	
	  * [Checklist for Writing Highly Reusable Components in React and Vue](https://hackernoon.com/checklist-for-writing-highly-reusable-components-in-react-and-vue-531f963864bd)
	
	

	* **Jesús Miguel Quinto Teran** (1)

		
		Muchas gracias!  
		Muy útil tu comentario.

* **Anthony Will Solsol Soplin** (3)
Y cuándo un componente no es controlado?

* **alanlapierre** (3)

	
	Se trata simplemente de hacer que el componente sea mas flexible y reutilizable. El termino “componente controlado” no se si es el adecuado, o si se usa de forma amplia. Los camponentes tienen entradas y salidas de datos (por medio de eventos) y mientras mas genéricos sean, mas fácil es usarlos dentro del mismo proyecto…o inclusive, en otros proyectos…

* **jesus-olivares661** (2)

	
	como haría en el caso que desee enviarle varios parametros desde el padre al hijo…? es decir como haria para recibir varios props.  
	En ese caso no puedo usar v-model así

	* **Nicolás Arias** (1)

		
		Si puedes, pero en el v-model tendrías que enviar un objeto, en este artículo lo hacen <https://zaengle.com/blog/using-v-model-on-nested-vue-components>

* **David Vargas Domínguez** (2)

	```
	    <toggle-input
	    	v-model="form.newsletter"
	    ></toggle-input>
	    
	    // hace lo mismo que...
	    
	    <toggle-input
	    	:value="form.newsletter"
	    	@input="(value) => { this.form.newsletter = value }"
	    ></toggle-input>
	    
	    
	```
	
	Dejo el link donde se explica más detalladamente  
	<https://vuejs.org/v2/guide/components.html#Emitting-a-Value-With-an-Event>

* **Northerchild** (1)

	
	Me toco ver dos veces el video, pero ya entendí como funciona bien los eventos del hijo que se envían al podre y como estos se escuchan

* **jhonsoverosovero** (1)

	
	El profe no hace entender mucho, alguién tiene otros recursos para seguir aprendiendo, como videos o blogs que hablen de este tema?

* **Nicolás Arias** (1)

	
	Custom model prop names

* **Nicolás Arias** (1)

	
	Custom model

* **Jesús Miguel Quinto Teran** (1)

	
	Excelente clase! Creería que es una de las mas útiles para entender el **two way data binding vue**. Gracias

* **David Wagner** (1)

	
	parte en que empieza a hacer el v-model

* **Carlos Fuentes** (1)

	
	Los estilos CSS del ToggleInput
	``` 
	    `<style>
	    .toggle {
	      position: relative;
	      display: inline-block;
	      -ms-flex-negative: 0;
	      flex-shrink: 0;
	      border-radius: 9999px;
	      cursor: pointer;
	      height: 1.5rem;
	      width: 3rem;
	    }
	    .toggle:focus {
	      outline: 0;
	      -webkit-box-shadow: 0004pxrgba(52, 144, 220, 0.5);
	      box-shadow: 0004pxrgba(52, 144, 220, 0.5);
	    }
	    .toggle:before {
	      display: inline-block;
	      border-radius: 9999px;
	      height: 100%;
	      width: 100%;
	      background-color: #dae1e7;
	      content: "";
	      -webkit-box-shadow: inset 02px4pxrgba(0, 0, 0, 0.1);
	      box-shadow: inset 02px4pxrgba(0, 0, 0, 0.1);
	      -webkit-transition: background-color 0.2s ease;
	      transition: background-color 0.2s ease;
	    }
	    .toggle[aria-checked="true"]:before {
	      background-color: #3490dc;
	    }
	    .toggle:after {
	      position: absolute;
	      top: 0;
	      left: 0;
	      border-radius: 9999px;
	      height: 1.5rem;
	      width: 1.5rem;
	      background-color: #fff;
	      border-width: 1px;
	      border-color: #dae1e7;
	      -webkit-box-shadow: 02px4px0rgba(0, 0, 0, 0.1);
	      box-shadow: 02px4px0rgba(0, 0, 0, 0.1);
	      content: "";
	      -webkit-transition: -webkit-transform 0.2s ease;
	      transition: -webkit-transform 0.2s ease;
	      transition: transform 0.2s ease;
	      transition: transform 0.2s ease, -webkit-transform 0.2s ease;
	      -webkit-transform: translateX(0);
	      transform: translateX(0);
	    }
	    .toggle[aria-checked="true"]:after {
	      -webkit-transform: translateX(1.5rem);
	      transform: translateX(1.5rem);
	    }
	    </style>````
	    
	```

* **Alejandro González Reyes** (1)

	
	Alguien tiene recursos sobre este tema, el profe lo complicó demasiado y el tema se ve interesante

	* **Edward Steven Ramos Palacios** (2)

		
		Ya probaste viendo la documentación oficial de vue?

* **Alejandro González Reyes** (1)

	
	Esta clase no le entendí nada.  
	Bastaba con que dijiera que el v-model se comporta de forma distinta en los componentes hijos.

* **Alejandro González Reyes** (1)
Alguien tiene recursos sobre este tema, el profe lo complicó demasiado y el tema se ve interesante

	* **Edward Steven Ramos Palacios** (2)

		
		Ya probaste viendo la documentación oficial de vue?

## 0130. Construcción del componente de Recordar Contraseña

### Descripción:


### Comentarios:

* **Jesús Miguel Quinto Teran** (4)

	
	Estilos para **ToggleInput**
	``` 
	    <style>
	    .toggle {
	      position: relative;
	      display: inline-block;
	      -ms-flex-negative: 0;
	      flex-shrink: 0;
	      border-radius: 9999px;
	      cursor: pointer;
	      height: 1.5rem;
	      width: 3rem;
	    }
	    .toggle:focus {
	      outline: 0;
	      -webkit-box-shadow: 0004pxrgba(52, 144, 220, 0.5);
	      box-shadow: 0004pxrgba(52, 144, 220, 0.5);
	    }
	    .toggle:before {
	      display: inline-block;
	      border-radius: 9999px;
	      height: 100%;
	      width: 100%;
	      background-color: #dae1e7;
	      content: "";
	      -webkit-box-shadow: inset 02px4pxrgba(0, 0, 0, 0.1);
	      box-shadow: inset 02px4pxrgba(0, 0, 0, 0.1);
	      -webkit-transition: background-color 0.2s ease;
	      transition: background-color 0.2s ease;
	    }
	    .toggle[aria-checked="true"]:before {
	      background-color: #3490dc;
	    }
	    .toggle:after {
	      position: absolute;
	      top: 0;
	      left: 0;
	      border-radius: 9999px;
	      height: 1.5rem;
	      width: 1.5rem;
	      background-color: #fff;
	      border-width: 1px;
	      border-color: #dae1e7;
	      -webkit-box-shadow: 02px4px0rgba(0, 0, 0, 0.1);
	      box-shadow: 02px4px0rgba(0, 0, 0, 0.1);
	      content: "";
	      -webkit-transition: -webkit-transform 0.2s ease;
	      transition: -webkit-transform 0.2s ease;
	      transition: transform 0.2s ease;
	      transition: transform 0.2s ease, -webkit-transform 0.2s ease;
	      -webkit-transform: translateX(0);
	      transform: translateX(0);
	    }
	    .toggle[aria-checked="true"]:after {
	      -webkit-transform: translateX(1.5rem);
	      transform: translateX(1.5rem);
	    }
	    </style>
	    
	```

* **Juan David Castro (Platzi)** (1)

	
	  * 👀 [NPM/vue-password](https://www.npmjs.com/package/vue-password)
	
	

* **Alejandro González Reyes** (1)

	
	No cabe duda que necesito una mejor explicación acerca de los componentes controlados

	* **Jhon Alexander Perez Valencia** (1)

		
		x2

	* **Jesús Miguel Quinto Teran** (1)

		
		<https://bangjelkoski.com/blog/building-a-controlled-vue-input-component>

	* **Jhon Alexander Perez Valencia** (1)

		
		gracias @Jesuskinto

	* **Juan David Castro (Platzi)** (1)

		
		Los componentes controlados son componentes super reutilizables que necesitan ser llamados por otros componentes para tener su lógica completa y funcionar correctamente.
		
		Es como si dejaran algunos últimos detalles de implementación para después pero, en realidad, le dejan la tarea al componente papá para poder funcionar de formas diferentes de acuerdo a las necesidades de cada parte de la aplicación.
		
		Checklist for Writing Highly Reusable Components in React and Vue

* **Alejandro González Reyes** (1)
No cabe duda que necesito una mejor explicación acerca de los componentes controlados

	* **Jhon Alexander Perez Valencia** (1)

		
		x2

## 0140. Creación de un componente Slider utilizando la librería tiny-slider

### Descripción:


### Links:

* [GitHub - ganlanyuan/tiny-slider: Vanilla javascript slider for all purposes.](https://github.com/ganlanyuan/tiny-slider)

### Comentarios:

* **David Daza** (6)

	
	De esta clase resalto:
	
	  * `this.$el` hace referencia al elemento padre del componente.
	  * Anteponer el símbolo `$` al nombre de una propiedad dentro del método `data` de la instancia anula toda la reactividad de esa propiedad.
	
	

* **Alejandro González Reyes** (2)

	
	En este enlace hay una explicación detallada de los componentes controlados.  
	[link](https://zaengle.com/blog/using-v-model-on-nested-vue-components)

* **Alejandro González Reyes** (2)

	
	¿Que diferencia hay entre usar la librería de forma tradicional (más rápido) a convertirla en un componente (mucho código)?,

	* **aragonesteban (Platzi)** (2)

		
		Creo que tu mismo te estas respondiendo la pregunta, la libreria te soluciona de forma rápida lo que necesitas, de otra forma, hacer la libreria desde cero para que haga lo mismo te va tomar tiempo, gastos y mucho mantenimiento para que haga lo mismo que una libreria, la cual toda una comunidad ya le da soporte.

* **Jorge Eliecer Rangel Jimenez** (2)

	
	tiny-slider 2.0 for Vue
	
	(<https://www.npmjs.com/package/vue-tiny-slider>)

* **Edward Steven Ramos Palacios** (2)

	
	Aqui el ejemplo con VueTinySlider:
	``` 
	    <template>
	      <tiny-slider
	        :mouse-drag="options.mouseDrag"
	        :auto-init="options.autoInit"
	        :loop="options.loop"
	      >
	        <slot></slot>
	      </tiny-slider>
	    </template>
	    <script\>
	    import VueTinySlider from'vue-tiny-slider'
	    
	    exportdefault {
	      name: 'Slider',
	      components: {
	        'tiny-slider': VueTinySlider
	      },
	      props: {
	        options: {
	          type: Object,
	          default: {
	            mouseDrag: false,
	            loop: true,
	            autoInit: true,
	            controls: true
	          }
	        }
	      }
	    }
	    <script\>
	    <stylelang="scss">
	    @import'./node_modules/tiny-slider/src/tiny-slider.scss';
	    </style>```
	    
	```

* **Juan David Castro (Platzi)** (2)

	
	También podemos usar el componente/librería [tiny-slider 2.0 for Vue](https://github.com/viktorlarsson/vue-tiny-slider) con toda la implementación de la librería base ya lista para usar en nuestra aplicación con Vue.

* **Northerchild** (1)

	
	Me encanto está clase

* **Kelly Jesus Salazar Sanchez** (1)

	
	Profe que extension usa para el autocompletado de los archivos veo que es muy eficiente vscode en esa parte o solo son ideas mia?

	* **Germán** (3)

		
		yo uso vue 2 snnipets y funciona super en vscode

* **Alejandro González Reyes** (1)

	
	Pregunta, el metodo beforeDestroy se invoca a través del hook beforeDestroy() del componente vue?

	* **Edward Steven Ramos Palacios** (1)

		
		Lo que se ve en la clase es el hook **beforeDestroy()** Está por fuera del objeto methods y siempre se ejecutara antes de destruir el componente. Muy útil para hacer labores de limpieza de recursos y demás.

* **Jorge Eliecer Rangel Jimenez** (1)

	
	tiny-slider 2.0 for Vue
	
	[](https://www.npmjs.com/package/vue-tiny-slider)

* **Alejandro González Reyes** (1)
Pregunta, el metodo beforeDestroy se invoca a través del hook beforeDestroy() del componente vue?

	* **Edward Steven Ramos Palacios** (1)

		
		Lo que se ve en la clase es el hook **beforeDestroy()** Está por fuera del objeto methods y siempre se ejecutara antes de destruir el componente. Muy útil para hacer labores de limpieza de recursos y demás.

* **Alejandro González Reyes** (1)
¿Que diferencia hay entre usar la librería de forma tradicional (más rápido) a convertirla en un componente (mucho código)?,

	* **aragonesteban (Platzi)** (2)

		
		Creo que tu mismo te estas respondiendo la pregunta, la libreria te soluciona de forma rápida lo que necesitas, de otra forma, hacer la libreria desde cero para que haga lo mismo te va tomar tiempo, gastos y mucho mantenimiento para que haga lo mismo que una libreria, la cual toda una comunidad ya le da soporte.

# High Order Functions

## 0150. ¿Qué son las High Order Functions - Crea tu primera HOF

### Descripción:


Las _High Order Functions_ o _HOFs_ son funciones que reciben funciones como argumentos y también retornan una función como resultado; nos ayudan a simplificar nuestro código. Entre menos código necesitamos para implementar una funcionalidad, más fácil de mantener es nuestra aplicación.

### Links:

* [Curso de Programación Funcional en JS por Bedu | Materiales](https://platzi.com/clases/funcional-js/)

### Comentarios:

* **Juan David Castro (Platzi)** (5)

	
	Las funciones puras también son muy importantes en la programación funcional: son funciones que siempre devuelven un mismo resultado cuando entregamos los mismos argumentos.
	
	Por ejemplo, la función `const suma = (x, y) => x +y;` siempre devuelve `10` cuando recibe los argumentos `5, 5`.
	
	En este caso, el profe hizo un ejemplo de HOF consumiendo un recurso de internet pero, los _fetchers_ nunca pueden ser funciones puras, la web puede caerse o puede cambiar el formato de la respuesta de la API. Por lo tanto, no es una función pura.
	
	No todas las funciones tienen que ser puras pero si debemos diferenciar entre una función pura o no pura para saber si debemos prepararnos para recibir cualquier tipo de resultados inesperados.

	* **Juan David Castro (Platzi)** (2)

		
		  * [Funciones Puras: Una breve introducción a la Programación Funcional - @jjyepez en el Curso de Redux](https://platzi.com/tutoriales/1200-redux/1797-funciones-puras-una-breve-introduccion-a-la-programacion-funcional/)
		  * [What Is a Pure Function in JavaScript?](https://medium.freecodecamp.org/what-is-a-pure-function-in-javascript-acb887375dfe)
		
		

* **Jhon Alexander Perez Valencia** (4)

	
	si se preguntan cual es el editor.  
	el editor es **_Playcode_**

* **Juan David Castro (Platzi)** (3)

	
	  * [Introducción a las Higher Order Functions - Curso de Programación Funcional por Bedu en Platzi](https://platzi.com/clases/1497-funcional-js/16807-introduccion-a-las-higher-order-functions/)
	
	

* **Freddy Córdova Arana** (2)

	
	<https://pokeapi.co/>

* **David Daza** (2)

	
	¿Cuál es ese editor? Está genial!

	* **coderdiaz** (4)

		
		Playcode 😃

* **Northerchild** (2)
Se podría decir qué es un Closures?

	* **Gabriel De Andrade (Platzi)** (2)

		
		No tanto, acá hablamos de como pasamos las funciones como argumentos y al mismo tiempo devolvemos funciones, un closure habla más de cómo una función recuerda el scope en el que fué declarada. [Curso de Closures y Scope en JavaScript](https://platzi.com/clases/scope/)

* **César Ernesto Rivas Martínez** (1)

	
	Nota: No siempre ecmascript es legible y facil de interpretar pero si fácil de escribir, según mi opinión

* **Alejandro González Reyes** (1)

	
	Pues yo no le veo la simplicidad de código, bastaba con la primera version

	* **Jorge Palacios** (5)

		
		Hace mucho más simple tu código. Aquí sólo ves unas lineas. Pero imagina el manejar decenas de llamados y parámetros, y que tu archivo termine de 200 líneas.
		
		Es más fácil de entender fetchPokemonsTipo(“hierba”)
		
		que fetchRecursos(“tipo”, “hierba”)
		
		pero la verdadera funcionalidad está en que, si abstraes esto otro nivel, podrías hacer que fetcher acepte la ruta base, y que esta función te sirva para construir funciones fetch de cualquier tipo con una o dos lineas de código.

## 0160. Vuex

### Descripción:
![](https://vuex.vuejs.org/flow.png)

### Links:

* [What is Vuex? | Vuex](https://vuex.vuejs.org)

### Comentarios:

* **Juan David Castro (Platzi)** (5)
![](https://vuex.vuejs.org/vuex.png)

	* **Jhon Alexander Perez Valencia** (1)

		
		(y)

* **Maximo Martinez Soria** (1)

	
	Saben que tipografía y theme es el de vscode?

## 0170. Obtener datos usando Vuex

### Descripción:


Vamos a convertir nuestros elementos estáticos de lista de apartamentos repetidos manualmente en componentes dinámicos que muestran los datos del estado con Vuex.

Para esto debemos crear un _getter_ en el archivo `store.js` que se encargue de obtener la información de los apartamentos que vamos a consumir desde nuestros componentes con la función `mapGetters` de Vuex. Más adelante vamos a consumir los datos desde la base de datos de Firebase.

### Links:

* [Getters | Vuex](https://vuex.vuejs.org/guide/getters.html#the-mapgetters-helper)

### Comentarios:

* **Jesús Miguel Quinto Teran** (4)

	
	Interesante uso del for para repetir contenido:
	``` 
	    v-for="i in 12"
	    
	```

* **Alejandro González Reyes** (4)

	
	El usar propiedades computadas evita mutar el estado de un componente padre desde el hijo.

* **Edward Steven Ramos Palacios** (4)

	
	Para realizar una iteración y que en la data no tengan algún dato único como el id pueden usar el index que da la directiva v-for:
	``` 
	    v-for="(room, index) in rooms":key="index"
	    
	```

* **Miguel Herreros Cejas** (2)

	
	Una pregunta. La manera de traer los datos a los componentes
	``` 
	    import { mapGetters } from 'vuex';
	    ...
	    
	    ...mapGetters({
	          user: 'authUser'
	        })
	    
	```
	
	¿Se puede utilizar en la versión 2 del CLI de Vue?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Creo que si es posible, pero es fácil de probar, cambia la versión de vue-cli en el package.json e instala las dependencias y cuéntanos como te va, una de las mejores formas de aprender es experimentar si se rompe, nos muestras el error y vemos si podemos solucionarlo entre todos, si funciona entonces queda resuelta tu pregunta. 😉

	* **César Ernesto Rivas Martínez** (2)

		
		Segun mis conocimientos, deberia de, porque VUE es una cosa y VUE CLI es otra, la utilizacion de
		``` 
		    ...mapGetters({
		          user: 'authUser'
		        })
		    
		```
		
		No depende de VUE CLI, porque es sintaxis de EMACSCRIPT.

* **ferroblesh** (1)

	
	En mi caso particular las imagenes no se desplegaban.  
	Agregué 2 puntos al inicio de src y con eso funcionó.  
	Ejemplo de la imagen de profile:
	``` 
	    <img class="profile__image w-full" :src="profile.avatar">
	    
	```

* **Omar Jesus Hernández Bastos** (1)

	
	Importante entender que cuando usamos
	``` 
	    computed:{
	    	...mapGetters([
	    	'Arreglo',]),	
	    }
	    
	    
	```
	
	Nos traemos un arreglo completo, mientras que para traernos una sola variable puntual del state
	``` 
	    //variable pura
	    variablepuntual:
	      computed: {
	        ...mapGetters({
	          user: 'authUser',
	        }),
	      },
	    
	    
	```

* **Jesús Miguel Quinto Teran** (1)

	
	Muy buena clase!..  
	Unas de las cosas mas interesantes que logre notar es la gran cantidad de datos que ahora descansan sobre Vuex…
	
	Simplifica mucho el trabajo.

## 0180. Crea un getter dinámico en Vuex utilizando HOF

### Descripción:


Por defecto, los _getters_ no aceptan argumentos. Esto es un problema porque muchas veces necesitamos enviar argumentos para conseguir diferentes resultados y responder contenido dinámico en nuestras aplicaciones.

Afortunadamente existen los _getters_ dinámicos: funciones _getters_ que devuelven otras funciones (si, así como las _High Orden Functions_ ). Gracias a está técnica podemos enviar argumentos a las funciones que devuelven los _gettters_ y obtener resultados dinámicos con todas las ventajas de pasar argumentos a una función en JavaScript.

### Links:

* [Getters | Vuex](https://vuex.vuejs.org/guide/getters.html#method-style-access)

### Comentarios:

* **David Daza** (4)

	
	Para este caso particular, **¿cúal es la ventaja del getter dinámico?**. Siento que no es necesario puesto que el `id` del usuario autenticado se va a mantener durante el tiempo que esté logueado, por tanto, bastaría con crear un getter que devuelva el número de habitaciones del usuario autenticado:
	``` 
	    getters: {
	    	userRoomsCount: (state, getters) => Object.keys(getters.authUser.rooms).length,
	    }
	    
	```
	
	¿Qué opinan?

	* **Edward Steven Ramos Palacios** (3)

		
		Desde mi punto de vista, el tuyo también me parece válido. Pienso que tal vez solo querían enseñar como se puede hacer uso de las HOF’s en Vuex.

	* **Omar Enrique Crespo Merchan** (3)

		
		Hacer uso de la HOF mantiene esa función mas abstracta de lo que el componente requiere lo que permitirá que sea mas fácil reutilizarlo… Cuando usas HOF normalmente si solo tienes 1 aplicación para ellas es inútil… hasta que escalas y necesitas reutilizar lógica. Y se vuelve mucho mas útil cuando te toca refactorizar lógica… Por ejemplo una HOF usada en 12 lugares diferentes y descubres forma de optimizar… Editas la HOF y listo optimización replicada en todos los “hijos” de la HOF, sin HOF tendrías que ir a cada caso de uso a refactorizar
		
		Las buenas practicas cobran sentido cuando el proyecto crece y necesita escalar. Por ello es importante que nos acostumbremos a ellas porque se echan en falta cuando tienes un proyecto que no hace uso de ellas

* **Juan David Castro (Platzi)** (2)

	
	  * [Dynamic Vuex Getters - Vuex for Everyone in Vue School](https://vueschool.io/lessons/dynamic-vuex-getters)
	
	

* **David Daza** (2)
Para este caso particular, ¿cúal es la ventaja del getter dinámico?. Siento que no es necesario puesto que el id</...

	* **Edward Steven Ramos Palacios** (3)

		
		Desde mi punto de vista, el tuyo también me parece válido. Pienso que tal vez solo querían enseñar como se puede hacer uso de las HOF’s en Vuex.

* **Alejandro González Reyes** (1)

	
	Me hice bolas en la hof de es6, como quedaría con es5

	* **Edward Steven Ramos Palacios** (1)

		```
		    getters: {
		      userRoomsCount: function (state) {
		        return function (id) {
		          return objectCountProperties(state.user[id].rooms)
		        }
		      }
		    }
		    
		```
		
		Y lo usas de la misma forma.  
		Saludos.

* **alan-saldivar** (1)

	
	El hecho de haber explicado de una forma sencilla cómo sacar un lenght de un objeto lo vuelve en un shortcut poderoso para JS en general. Super like.

	* **alan-saldivar** (1)

		
		Algo que sí podemos hacer más sencillo es exportar la constante directamente en lugar de expor default

* **Alejandro González Reyes** (1)
Me hice bolas en la hof de es6, como quedaría con es5

	* **Edward Steven Ramos Palacios** (1)

		```
		    getters: {
		      userRoomsCount: function (state) {
		        return function (id) {
		          return objectCountProperties(state.user[id].rooms)
		        }
		      }
		    }
		    
		```
		
		Y lo usas de la misma forma.  
		Saludos.

## 0190. Creación de la vista para creación de publicaciones

### Descripción:


### Links:

* [Beautiful Free Images & Pictures | Unsplash](https://unsplash.com)

### Comentarios:

* **Jesús Miguel Quinto Teran** (2)

	
	Excelente clase!
	
	Es impresionante el aprovechamiento de los **Slots** en éste proyecto!!

* **Jhon Alexander Perez Valencia** (2)

	
	## …
	
	<https://unsplash.com/>

* **Alejandro González Reyes** (2)

	
	Añadir clase mx-auto al container para que se centren horizontalmente

## 0200. Agregando datos con Vuex

### Descripción:


### Comentarios:

* **Alejandro González Reyes** (2)

	
	¿ Que existe de diferencia entre crear una firma de action de esta forma?
	``` 
	    CREATE_ROOM({state, commit}, payload)
	    
	```
	
	y esta otra. Ya que en el curso anterior de VUE, se dijo que el action recibe como parametro el contexto y la carga util
	``` 
	    CREATE_ROOM(context, payload)
	    
	```

	* **Omar Enrique Crespo Merchan** (2)

		
		La primera forma usa una nueva forma de js llamada destructuring… La segunda es la forma tradicional. Es una decisión tuya cual usar pero a efectos técnicos es exactamente lo mismo solo azucar para la sintaxis

	* **Omar Enrique Crespo Merchan** (3)

		
		a efectos tecnicos es exactamente lo mismo… Es solo una forma mas directa de acceder a las variables de un parametro, objeto o array. La tecnica se llama destructuring puedes buscar acerca de ella

* **walter** (1)

	
	hola en la clase anterior me redireciona pero se ve en blanco.  
	![](https://res.cloudinary.com/dewgxbhbm/image/upload/v1558275906/error_xgz3ql.png)

	* **Jesús Miguel Quinto Teran** (2)

		
		Tu problema parece estar en el Store, Verifica que **userRoomsCount** este creado correctamente.
		``` 
		    userRoomsCount: state => id => countObjectProperties(state.users[id].rooms),
		    
		```

* **Alejandro González Reyes** (1)

	
	Hay un error.  
	Se supone que se agregó al store todas las salas creadas desde el form.  
	¿porque cuando accedo al home, el store vuelve a su estado normal?

	* **Omar Enrique Crespo Merchan** (1)

		
		El store se reinicia si recargas la página. Este es solo el estado de tu apliación si recargas la página el estado se reinicia… No deberías de tener problema si agregas un enlace al home y a través de links <router-link> te vas al home… Si lo haces manualmente cambiando la ruta recargas la página reinicias el estado y el sitio que agregaste ya no estará

* **walter** (1)
hola en la clase anterior me redireciona pero se ve en blanco.

	* **Jesús Miguel Quinto Teran** (2)

		
		Tu problema parece estar en el Store, Verifica que **userRoomsCount** este creado correctamente.
		``` 
		    userRoomsCount: state => id => countObjectProperties(state.users[id].rooms),
		    
		```

* **Alejandro González Reyes** (1)
¿ Que existe de diferencia entre crear una firma de action de esta forma? CREATE_ROOM({state, commit}, payload) y esta otra...

	* **Omar Enrique Crespo Merchan** (2)

		
		La primera forma usa una nueva forma de js llamada destructuring… La segunda es la forma tradicional. Es una decisión tuya cual usar pero a efectos técnicos es exactamente lo mismo solo azucar para la sintaxis

* **Alejandro González Reyes** (1)
Hay un error. Se supone que se agregó al store todas las salas creadas desde el form. ¿porque cuando accedo al home, el store vuelve a su...

	* **Omar Enrique Crespo Merchan** (1)

		
		El store se reinicia si recargas la página. Este es solo el estado de tu apliación si recargas la página el estado se reinicia… No deberías de tener problema si agregas un enlace al home y a través de links <router-link> te vas al home… Si lo haces manualmente cambiando la ruta recargas la página reinicias el estado y el sitio que agregaste ya no estará

# Base de datos en tiempo real con Firebase

## 0210. Instalación y Configuracion de Firebase Realtime Database

### Descripción:


Firebase es un _Backend as a Servicice_ , una herramienta que nos facilita la creación de tareas de backend y despliegue de forma mucho más simple, mantenible y escalable.

Firebase nos proporciona muchas ayudas y APIs para realizar tareas como crear y autenticar usuarios, guardar nuestra información en bases de datos, almacenar archivos estáticos, administrar la infraestructura (con Google Cloud), analizar métricas, entre muchas otras.

Podemos conectar cualquiera de nuestras aplicaciones con Firebase, solo debemos añadir una nueva dependencia a nuestro proyecto:
``` 
    yarn add firebase
    
```

### Links:

* [Sign in - Google Accounts](https://console.firebase.google.com)

* [Firebase](https://firebase.google.com)

* [Curso de Firebase para Web](https://platzi.com/cursos/firebase-web)

### Comentarios:

* **Juan David Castro (Platzi)** (7)

	
	**¿Qué es Firebase?**
	
	  * Todas _(bueno, casi todas :sweat_smiles)_ las aplicaciones necesitan programar código backend para sus diferentes funcionalidades: guardar info en bases de datos, almacenar archivos, autenticar usuarios, etc 😮.
	  * Firebase en un _BAAS (Backend as a Service)_ : Google se encargara él solito de crear y administrar las funciones, bases de datos e infraestructura de nuestra aplicación; nuestra tarea solo será trabajar algunas configuraciones en su plataforma _([firebase.google.com](http://firebase.google.com))_ y construir nuestra aplicación 😱🎉.
	  * Toda esta infraestructura funciona con Google Cloud. Tenemos muchas posibilidades para escalar nuestras aplicaciones en el futuro 👌.
	
	
	
	**Servicios de Firebase:**
	
	  * Firestore es una base de datos NoSQL que nos permite almacenar y sincronizar en tiempo real los datos e nuestra aplicación ✌️📝.
	  * La autenticación (en mi opinión, la herramienta más útil de Firebase 😍🎉) nos permite crear, autenticar y administrar los usuarios de nuestras aplicaciones con email y password, login y signup con redes sociales, correos electrónicos de recuperación de contraseña, entre muchas otras cosas geniales 🚫🏁 ✖️ ✔️ .
	  * Cloud Storage para almacenar archivos estáticos 😮.
	  * Cloud Messaging para enviar notificaciones 📩.
	  * Firebase Hosting para desplegar nuestras aplicaciones _(hasta dónde tengo entendido son despliegues común y corrientes)_ y Cloud Functions para despliegues sin programar el código backend de la aplicación 🙃🆙.
	
	

	* **Juan David Castro (Platzi)** (1)

		
		Estos tutoriales del Blog de Platzi _(uno con vídeo animado 😮)_ son muy útiles para entender cómo funcionan las reglas de seguridad en Firebase 👌:
		
		  * [Reglas de seguridad en Firebase - @anncode](https://platzi.com/blog/reglas-de-seguridad-en-firebase/)
		  * [Reglas de Seguridad de Firebase: ejemplo práctico - @jjyepez](https://platzi.com/blog/reglas-de-seguridad-de-firebase-ejemplo-practico/)
		
		

	* **Freddy Córdova Arana** (1)

		
		No sabia casi nada de Firebase, pero ahora me interesa mucho. Gracias 😄

	* **Jhon Alexander Perez Valencia** (1)

		
		gracias

	* **Ludwing Juan Homero Pérez Tzaquitzal** (1)

		
		Gran aporte!!  
		Gracias!

* **Sebastian Cardoso Castillo** (3)

	
	Para los que estan usando Nuxt tienen que crear un archivo _firebase.js_ en la carpeta plugins. Ahí llaman al modulo, le dan la configuración, lo inicializan y lo exportan. Luego en el archivo _nuxt.config.js_ llaman al plugin dentro de la prop plugins.

* **Andres Rivera** (2)

	
	¿por qué toca cambiar la doble comilla por la sencilla?

	* **Sebastian Cardoso Castillo** (3)

		
		Son convenciones, vienen con la configuración de eslint.

* **Juan Pablo Calao Pérez** (1)

	
	por qué utilizamos “Realtime database” si está “Cloud Firestore”??

	* **Sebastian Cardoso Castillo** (1)

		
		![](https://i.ibb.co/jRgS4cg/11.png)  
		Si Cloud Firestore es la nueva generación de Realtime Database entonces significa que que RD queda obsoleto o depreado?

## 0220. Obteniendo los datos desde Firebase Realtime Database

### Descripción:


### Comentarios:

* **Juan Pablo Calao Pérez** (3)

	
	Este es un muy buen proyecto para importar y exportar en JSON una base de datos en Cloud Firestore: <https://github.com/dalenguyen/firestore-import-export>

* **Jorge Palacios** (3)

	
	Si tienen 3 horas como yo, buscando el por qué no muestra las habitaciones. Que parece no realizarse la conexión en la base de datos y no sale ningún error en consola. Puedes intentar lo siguiente:
	
	Entra en la pestaña de Reglas en tu base de datos en Firebase, y verifica que las reglas de read y write estén en true.

* **Juan David Castro (Platzi)** (3)

	
	 **Firestore** 🆚 **Realtime Database** :
	
	  * [Firebase Realtime DB vs Firestore 🔥 - Chris Esplin](https://www.youtube.com/watch?v=TmXct7seeBY)
	  * [What’s the Difference Between Cloud Firestore & Firebase Realtime Database? #AskFirebase](https://www.youtube.com/watch?v=KeIx-mArUck)
	  * [Choosing a Firebase Database For Your App: Realtime Database vs. Cloud Firestore](https://savvyapps.com/blog/firebase-realtime-database-vs-cloud-firestore-for-your-app)
	
	

	* **Juan David Castro (Platzi)** (1)

		
		Podemos importar y exportar la data de nuestros usuarios en archivos JSON y CVS _(información separada por comas)_ 👍 🕹

	* **Jhon Alexander Perez Valencia** (1)

		
		(y) muy buen aporte

## 0230. Agregando la consulta de usuarios

### Descripción:


### Comentarios:

* **victormanuelmurillocamayo** (1)

	
	Copié el codigo del profe pero me dice lo isguiente
	``` 
	    index.cjs.js?3523:1618Uncaught (in promise) Error: Reference.child failed: First argument was an invalid path = "null". Paths must be non-empty strings and can't contain ".", "#", "$", "[", or"]"
	    
	    mi codigo es en store.js
	    FETCH_USER: ({ state, commit }, { id }) => new Promise((resolve) => {
	          firebase.database().ref('users').child(id).once('value', (snapshot) => {
	            commit('SET_ITEM', { resource: 'users', id: snapshot.key, item: snapshot.val() });
	            resolve(state.users[id]);
	          });
	        }),
	    
	    
	    
	```
	``` 
	    `<code>
	    
	```

	* **Jenny Katherine Aguilera Morales** (1)

		
		Hola tengo ese mismo error, obtuviste alguna solución?

	* **Angel Santillan Brambila** (1)

		
		revisa el data.json que importaste probablemente al momemento que borramos los .key ocasionara algun problema. En mi caso funciono sin problemas. la pregunta lleva meses y tambien tengo curiosidad si pudiste resolver el problema  
		saludos

	* **neontigermx** (1)

		
		¿De casualidad no deshabilitaste el authId en store.js?, eso hice yo y me salio ese mismo error.

## 0240. Almacenando nuevas publicaciones en Firebase Realtime Database

### Descripción:


### Comentarios:

* **Jesús Miguel Quinto Teran** (3)

	
	Reto:
	
	App.vue
	``` 
	    <template>
	      <divid="app">
	        <router-view/>
	      </div>
	    </template>
	    
	    <script>
	    import { mapActions } from'vuex';
	    exportdefault {
	      created() {
	        this.fethServices();
	      },
	    
	      methods: {
	        ...mapActions({ fethServices: 'FETCH_SERVICES'}),
	      },
	    }
	    </script>
	    
	    
	    <stylelang="postcss"src="./assets/tailwind.postcss"></style>
	    <stylelang="css"src="./assets/main.css"></style>
	    
	```
	
	Store.js
	``` 
	    ...
	    actions: {
	    ... 
	    FETCH_SERVICES: ({ state, commit }) => new Promise((resolve) => {
	          const instance = firebase.database().ref('services');
	    
	          instance.once('value', (snapshot) => {
	            const services = snapshot.val();
	            Object.keys(services).forEach((serviceId) => {
	              const service = services[serviceId];
	              const data = {
	                item: service,
	                id: serviceId,
	                resource: 'services',
	              };
	              commit('SET_ITEM', data);
	            });
	    
	            resolve(Object.values(state.rooms));
	          });
	        }),
	    ...
	    }
	    ...
	    
	    getters: {
	    ...
	    services: state => state.services,
	    ...
	    }
	    
	```
	
	filters/Id2service.js
	``` 
	    import store from '../store';
	    
	    const id2Serive = {};
	    const { services } = store.state;
	    
	    id2Serive.install = functionid2s(Vue) {
	      Vue.filter('id-to-service', (val) => {
	        if (services[val]) {
	          return services[val].name;
	        }
	        return val;
	      });
	    };
	    
	    exportdefault id2Serive;
	    
	```
	
	CreateHousePage.vue
	``` 
	    <template>
	      <page-layout>
	        <sectionclass="py-4 bg-teal-dark">
	          <divclass="container">
	            <formclass="form">
	              <divclass="form__field relative">
	                <iclass="input-icon material-icons absolute text-grey-darker">search</i>
	                <input
	                  class="input__search"
	                  id="where"
	                  type="text"
	                  placeholder="Mexico City, Mexico">
	              </div>
	            </form>
	          </div>
	        </section>
	        <sectionclass="section__create py-6">
	          <divclass="container">
	            <h1class="text-3x1"> Publish a new rooms</h1>
	            <form>
	              <divclass="mb-4">
	                <labelclass="input__label">Title</label>
	                <input
	                  v-model="publication.title"
	                  class="input__field"type="text"placeholder="Bruce Wayne">
	              </div>
	              <divclass="mb-4">
	                <labelclass="input__label">Description</label>
	                <textarea
	                  v-model="publication.description"
	                  class="input__field"rows="10"placeholder="Bruce Wayne"></textarea>
	              </div>
	              <divclass="mb-4">
	                <labelclass="input__label">Feacture Image</label>
	                <input
	                  v-model="publication.feacturedImage"
	                  class="input__field"
	                  type="text"placeholder="https://images.unsplash.com/photo-1560681610-68f081d2e7dd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80">
	              </div>
	              <divclass="mb-4">
	                <labelclass="input__label">Servicios</label>
	                <buttonv-for="(service, id) in services":key="id"
	                  @click.prevent="addService(id)"
	                  class="font-semibold py-3 px-6 mr-4 rounded"
	                  :class="isActive(id) ? 'bg-blue-dark':'bg-blue-light'">
	                  {{ service.name }}
	                </button>
	              </div>
	              <divclass="mb-4 text-right">
	                <button
	                  @click.prevent="save"
	                  class="w-full bg-yellow-dark text-yellow-darker font-semibold py-3 px-6 rounded">
	                  Publish
	                </button>
	              </div>
	            </form>
	          </div>
	        </section>
	      </page-layout>
	    </template>
	    
	    <script>
	    import { mapGetters } from'vuex';
	    import PageLayout from'@/layouts/PageLayout.vue';
	    
	    exportdefault {
	      name: 'CreateHousePage',
	    
	      data() {
	        return {
	          publication: {
	            title: '',
	            description: '',
	            feacturedImage: '',
	            services: {},
	          },
	        };
	      },
	    
	      components: {
	        PageLayout,
	      },
	    
	      computed: {
	        ...mapGetters(['services']),
	      },
	    
	      methods: {
	        save() {
	          const {
	            title,
	            description,
	            services,
	            feacturedImage,
	          } = this.publication;
	    
	          const room = {
	            title,
	            description,
	            services,
	            featured_image: feacturedImage,
	            publishedAt: Date.now(),
	          };
	    
	          this.$store.dispatch('CREATE_ROOM', room);
	        },
	    
	        addService(serviceId) {
	          if (this.publication.services[serviceId]) {
	            this.$delete(this.publication.services, serviceId);
	          } else {
	            const id = JSON.parse(JSON.stringify(serviceId));
	            this.$set(this.publication.services, id, id);
	          }
	        },
	    
	        isActive(serviceId) {
	          if (this.publication.services[serviceId]) {
	            returntrue;
	          }
	          returnfalse;
	        },
	      },
	    };
	    </script>
	    
	```
	
	  * Formulario:  
	![formulario](https://i.ibb.co/dbZ6p7p/form.png)
	
	  * HouseCard:  
	![card-house](https://i.ibb.co/8gVPwQq/house.png)
	
	
	

* **Juan David Castro (Platzi)** (2)

	
	En este vídeo también vemos cómo crear un proyecto de React para utilizar Firebase en el nuevo sitio de Podcasts de la gente de [Aprendiendo Frontend](https://www.youtube.com/channel/UC6nEW2GNewHJn9KXT_Mvwuw):
	
	  * [Raw live coding - Creamos un proyecto con ReactJS desde cero.](https://www.youtube.com/watch?v=0Q1p1cXI_64)
	
	

* **neontigermx** (1)

	
	Me tomó bastante tiempo pero lo logré xD  
	Dejo mi commit del ejercicio :3  
	<https://github.com/andres87mx/vuejs-avanzado-firebase/commit/d506d29da34bf7e196ee80eea544060e321d0538>

* **Jesús Miguel Quinto Teran** (1)

	
	Aquí doc [Leer y escribir datos en firebase](https://firebase.google.com/docs/database/web/read-and-write)

* **Alejandro González Reyes** (1)

	
	¿Cual es la finalidad de resolver las promesas en los actions del store  
	CREATE_ROOM, FETCH_ROOM y FETCH_USER?  
	ya que el no colocarlas sigue funcionando…
	``` 
	    FETCH_USER({ state, commit }, id) {
	          returnnew Promise((resolve) => {
	            firebase.database().ref('users').child(id).once('value', (snapshot) => {
	              commit('SET_ITEM', {
	                resource: 'users',
	                id: snapshot.key,
	                item: snapshot.val(),
	              });
	            });
	            resolve(state.users[id]);
	          });
	        }
	    
	```
	
	Si se supone que el método once( ) retorna una promesa.

	* **Edward Steven Ramos Palacios** (2)

		
		En el ejemplo que pones, es sencillo. Notificar a quien llama la promesa de que se resolvió y retornó un valor. De esta manera puedes ejecutar una nueva acción como por ejemplo, notificar al usuario de algo.
		``` 
		    this.$store.dispatch('FETCH_USER ', 1).then(response => {
		      /* en este punto sabes que la promesa se resolvió y puedes ejecutar una acción, como mostrar un toast, modal o lo que quieras, por ejemplo. Y usar el valor de retorno */
		    
		    })
		    
		```
		
		Por otro lado una promesa siempre debe resolverse. Bien sea con resolve o reject para el caso de que algo no salga como se esperaba.

* **Alejandro González Reyes** (1)
¿Cual es la finalidad de resolver las promesas en los actions del store CREATE_ROOM, FETCH_ROOM y FETCH_USER? ya que el no colocarlas sig...

	* **Edward Steven Ramos Palacios** (2)

		
		En el ejemplo que pones, es sencillo. Notificar a quien llama la promesa de que se resolvió y retornó un valor. De esta manera puedes ejecutar una nueva acción como por ejemplo, notificar al usuario de algo.
		``` 
		    this.$store.dispatch('FETCH_USER ', 1).then(response => {
		      /* en este punto sabes que la promesa se resolvió y puedes ejecutar una acción, como mostrar un toast, modal o lo que quieras, por ejemplo. Y usar el valor de retorno */
		    
		    })
		    
		```
		
		Por otro lado una promesa siempre debe resolverse. Bien sea con resolve o reject para el caso de que algo no salga como se esperaba.

## 0250. Perfeccionando el flujo de navegación de nuestra App

### Descripción:


Vamos a corregir los enlaces y botones a las diferentes partes de nuestra aplicación para poder navegarla correctamente.

Para esto vamos a editar el archivo `HeaderPartial.vue` y cambiar la etiqueta de los enlaces a partes internas de nuestra aplicación: en vez de usar etiquetas `a` vamos a usar `router-link` y en vez de usar la propiedad `href` vamos a usar la propiedad `:to={name:'RutaDeLaAplicación'}`.

### Comentarios:

* **David Daza** (12)

	
	Es más fácil utilizar el atributo `tag` del elemento `router-link` para indicar el elemento HTML que queremos que se renderice:
	``` 
	    <router-link
	    	:to="{ name: 'CreateHousePage' }"
	    	tag="button"
	    	class="mr-2 flex items-center"
	    >
	    	<iclass="material-icons">add</i>
	    </router-link>	
	    
	```

# Autenticación con Firebase

## 0260. Configuracion Inicial para trabajar con Firebase Authentication

### Descripción:


Firebase nos proporciona una configuración muy sencilla para manejar la creación de usuarios, inicio de sesión y logout de la aplicación con email y password o con redes sociales _(Google Accounts, Facebook, Twitter, Github o incluso nuestros proveedores personalizados)_.

También tenemos acceso y control muy personalizado de toda esta información gracias a la sección de autenticación de usuarios en la [Consola de Firebase](https://console.firebase.google.com); nos permite controlar todas nuestras cuentas de forma muy sencilla, podemos inhabilitar y eliminar usuarios, enviar correos electrónicos para cambiar contraseñas y crear plantillas para configurar el envío de emails de nuestra aplicación.

El equipo de Google ha creado algunos **SDKs** _(Software Development Kits)_ para facilitar la programación y configuración de estas funcionalidades en los lenguajes y plataformas más comunes. En caso de no encontrar estas librerías oficiales, podemos buscar diferentes herramientas creadas por la comunidad.

### Comentarios:

* **pg** (3)

	
	Otra forma de resolver el cierre de la Modal seria pasando el nombre de la modal como parametro al metodo closeModal
	
	template
	``` 
	    <modal:show="modals.login" @close-modal="closeModal('login')">login form</modal>
	    <modal:show="modals.register" @close-modal="closeModal('register')">register form</modal>
	    
	```
	
	methods
	``` 
	      methods: {
	        closeModal(name) {
	          this.$store.dispatch('TOGGLE_MODAL_STATE', {
	            name,
	            value: false,
	          });
	        },
	        registerHandlerSubmit() {
	          this.$store.dispatch('CREATE_USER', this.formRegister)
	            .then(() => {
	              this.closeModal('register');
	            });
	        },
	      },
	    
	```

* **Heyner Javier Marmol Verbel** (1)

	
	otra forma de cerrar el modal es en el componente modal pasar como props en nombre y devolverlo en el emit:
	``` 
	    name: 'Modal',
	      props: {
	        show: {
	          type: Boolean,
	          default: false,
	        },
	        name: {
	          type: String,
	          require: true,
	        },
	      },
	      methods: {
	        onClose() {
	          this.$emit('close-modal', this.name);
	        },
	      },
	    
	```
	
	y en el Default layout llamarlo de esta manera:
	``` 
	    <modal:show="modals.login"name="login" @close-modal="(name) => closeModal(name)">
	    	slot
	    </modal>
	    
	```
	
	y en el metodo de layout así:
	``` 
	      methods: {
	        closeModal(name) {
	          this.$store.dispatch('TOGGLE_MODAL_STATE', {
	            name,
	            value: false,
	          });
	        },
	      },
	    
	```

## 0270. Agregando nuevos usuarios en firebase autentication

### Descripción:


Vamos a añadir los usuarios que creamos con nuestro formulario a Firebase. Debemos conectarnos a la base de datos y enviar los datos necesarios para crear las cuentas en el método `beforeCreate` del botón de registrar.

Para esto vamos a crear una nueva acción de Vuex en el archivo `store.js`. Debemos usar los métodos `firebase.auth.createUserWithEmailAndPassword` para registrar los usuarios en Firebase Authentication y `firebase.database().ref('').child().set()` para guardarlos en Firebase Database.

También debemos guardar la información de los usuarios en el estado local de la aplicación. Así, podremos mostrar (o no) cierto contenido si los usuarios están autenticados.

### Comentarios:

* **Juan David Castro (Platzi)** (6)

	
	Con Firebase podemos tener **ilimitadas cantidades de usuarios** registrados sin que Google nos cobre un centavo 😱🎉.  
	**AWESOME!** 😍

* **Sebastian Cardoso Castillo** (1)

	
	Tengo otra base de datos SQL en el Cloud de Google y dentro tiene una tabla usuarios.¿Es una buena práctica guardar el usuario en tantos lados?

	* **Anthony Will Solsol Soplin** (2)

		
		De por sí, si no administras bien una base de datos NoSQL como lo es Firestore o Realtime Database puede ser inconsistente. No me imagino si le sumas a eso tener repartida la misma información en distintas fuentes 😕 ¿Le diste alguna solución a eso?

* **Juan David Castro (Platzi)** (1)

	
	Cuando añadimos autenticación con Google Accounts _(o cualquier otra red social soportada por Firebase)_ el proceso de registro/inicio de sesión es un poco diferente. En vez de llenar un formulario y esperar un correo electrónico, vamos a abrir una nueva ventana del navegador para llenar los datos que nos piden estas cuentas (pop-up).

## 0280. Inicio de sesión de usuario

### Descripción:


### Comentarios:

* **Juan David Castro (Platzi)** (3)

	
	¿Qué pasa cuando intentamos crear un usuario con email y contraseña pero el usuario ya esta creado? ¿Firebase devuelve un error o autenticamos automáticamente a los usuarios? 🤔

	* **coderdiaz** (4)

		
		En este caso, Firebase te resuelve con un error de que el usuario ya esta creado si se está haciendo uso del mismo correo 😃

	* **Jesús Miguel Quinto Teran** (2)

		
		Creates a new user account associated with the specified email address and password.
		
		On successful creation of the user account, this user will also be signed in to your application.
		
		**_User account creation can fail if the account already exists or the password is invalid._**
		
		Note: The email address acts as a unique identifier for the user and enables an email-based password reset. This function will create a new user account and set the initial user password.

* **Sebastian Cardoso Castillo** (1)

	
	Donde escribo el **firebase.auth()onAuthStateChaged() si estoy en Nuxt?**

	* **Juan David Castro (Platzi)** (2)

		
		En esta guía se explica super bien: <https://www.davidroyer.me/blog/nuxtjs-firebase-auth/>. 😉

* **Juan David Castro (Platzi)** (1)
¿Qué pasa cuando intentamos crear un usuario con email y contraseña pero el usuario ya esta creado? ¿Firebase devuelve un error o autenti...

	* **coderdiaz** (4)

		
		En este caso, Firebase te resuelve con un error de que el usuario ya esta creado si se está haciendo uso del mismo correo 😃

## 0290. Cierre de sesión de usuario

### Descripción:


### Comentarios:

* **Heyner Javier Marmol Verbel** (2)
al momento de consultar el usuario con este código me devuelve null: firebase.database().ref('users').child(id).once('value', (snap...

	* **Manuel Ojeda** (2)

		
		¿Declaraste la action como Promise?  
		Al ser una acción http requiere que la action sea una new Promise, yo cuento con este código y funciona bien
		``` 
		    FETCH_USER: ({ state, commit }, { id }) => new Promise((resolve) => {
		          firebase.database().ref('users').child(id).once('value', (snapshot) => {
		            commit('SET_ITEM', { resource: 'users', id: snapshot.key, item: snapshot.val() });
		            resolve(state.users[id]);
		          });
		        })
		    
		```
		
		Saludos.

* **Heyner Javier Marmol Verbel** (1)

	
	al momento de consultar el usuario con este código me devuelve null:
	``` 
	    firebase.database().ref('users').child(id).once('value', (snapshot) => {
	            commit('SET_ITEM', { resource: 'users', id: snapshot.key, item: snapshot.val() });
	            resolve(state.users[id]);
	          });
	    
	```
	
	Alguien sabe porque, o si le paso pudo solucionarlo?

	* **Manuel Ojeda** (2)

		
		¿Declaraste la action como Promise?  
		Al ser una acción http requiere que la action sea una new Promise, yo cuento con este código y funciona bien
		``` 
		    FETCH_USER: ({ state, commit }, { id }) => new Promise((resolve) => {
		          firebase.database().ref('users').child(id).once('value', (snapshot) => {
		            commit('SET_ITEM', { resource: 'users', id: snapshot.key, item: snapshot.val() });
		            resolve(state.users[id]);
		          });
		        })
		    
		```
		
		Saludos.

## 0300. Protegiendo páginas utilizando Navigation Guards

### Descripción:


Las _Navigation Guards_ de Vue Router nos ayudan a proteger ciertas rutas de nuestra aplicación con redirecciones o cancelaciones. Podemos conectarnos al conjunto de funciones que se ejecutan antes (con `router.beforeEach`), durante y después (con `router.afterEach`) del proceso de navegación de diferentes maneras: de forma global global, por rutas o por componentes.

Para indicarle a Vue Router que nuestras rutas deben ser protegidas debemos añadir la siguiente información:
``` 
    {
            path: '...',
            name: '...',
            component: '...',
            meta: {
                    requiresAuth: true,
            }
    }
    
```

### Links:

* [Navigation Guards | Vue Router](https://router.vuejs.org/guide/advanced/navigation-guards.html)

### Comentarios:

* **Juan David Castro (Platzi)** (4)

	
	  * [In Component Navigation Guards - Vue School in The Vue.js Master Class](https://vueschool.io/lessons/in-component-navigation-guards)
	  * [Learn Vue Router Navigation Guards Quickly - Medium](https://medium.com/vue-by-example/learn-vue-router-navigation-guards-quickly-1eb974097b85)
	  * [Vue Router Navigation Guards Explained - CodePen](https://codepen.io/patrickodacre/pen/owjVNK)
	
	

* **Jesús Miguel Quinto Teran** (3)

	
	Interesante uso del metodo **some** , es algo nuevo para mi!!,
	
	**Notas:**
	
	  * to: Es el objecto de tipo Router que representa la ruta de llegada.
	
	  * to.matched: Es una propiedad de tipo arreglo que esta compuesta por la ruta actual y todas sus rutas hijas.
	
	  * some: Es un método de los arreglos que los recorre y retorna true si alguna condición se cumple.
	
	  * to.matched.some(route => route.meta.requiresAuth) : Finalmente evaluamos si la ruta en **to** o alguna de sus rutas hijas requieren auth para entrar.
	
	
	

* **Alejandro González Reyes** (2)

	
	Hay un error en la app.  
	Si bien las rutas están protegidas, cuando se encuentra logeado el usuario si puede acceder a crear una nueva room desde el boton de add en el header, pero si quiere ir a su perfil, es necesario colocar la ruta en la barra de navegación del browser y al dar enter, lo redirecciona a home, y después de unas centesimas de segundo lo vuelve a reconocer como autenticado.

	* **Juan David Castro (Platzi)** (1)

		
		¿Cómo lo solucionarias?

	* **Omar Enrique Crespo Merchan** (2)

		
		yo he colocado un router-link en el header en el nombre del usuario
		``` 
		    <router-link to="/user"class="text-black no-underline leading-none">
		      {{ user.name }}
		    </router-link>
		    
		```
		
		Pero este no seria la mejor solución ya que el usuario si esta logeado no deberia de poder interactuar con una app donde aparece como no logeado… Si mal adelante en el curso no solucionan esto lo hare yo con un loading screen que no deje hacer nada hasta que se sepa si el usuario esta autenticado… O guardare en cache las credenciales del usuario para que aparezcan directamente y después el servidor compruebe si el usuario debe de ser deslogeado

	* **Juan Pablo Calao Pérez** (1)

		
		Jústamente iba a preguntar por eso. La razón es porque fetch auth user es una acción asíncrona, y el before each se ejecuta antes de que pueda cargarse el usuario en el store. Por lo tanto, en el primer render no hay usuario autenticado, y por eso redirecciona. Si alguien tiene una solución, compártala. Yo también buscaré solucionarlo

* **Sebastian Cardoso Castillo** (1)

	
	En Nuxt habría que hacer un middleware?

	* **Juan David Castro (Platzi)** (1)

		
		😉👉 [Using Firebase Auth With Nuxt.js](https://www.davidroyer.me/blog/nuxtjs-firebase-auth/)

* **iLuisCastillo** (1)

	
	en el condicional de store.state.authId me da null, pero cuando lo imprimo en consola si aparece, alguna ayuda?

	* **iLuisCastillo** (1)

		
		aca el codigo
		``` 
		    router.beforeEach((to, from, next) => {
		      if (to.matched.some(route => route.meta.requiresAuth)) {
		        store.state.authId ? next() : next({ name: 'HomePage' });
		      } else {
		        next();
		      }
		    });```
		    
		```

	* **aragonesteban (Platzi)** (2)

		
		Hola Luis, creo que tienes el condicional ternario alreves, supongo que debería ir de la siguiente manera.
		``` 
		    store.state.authId ? next({ name: 'HomePage' }) : next();
		    
		```
		
		Para que si el id existe lo redireccione al HomePage.

* **Alejandro González Reyes** (1)
Hay un error en la app. Si bien las rutas están protegidas, cuando se encuentra logeado el usuario si puede acceder a crear una nueva roo...

	* **Juan David Castro (Platzi)** (1)

		
		¿Cómo lo solucionarias?

# Scoped Slots

## 0310. ¿Qué son los Scoped Slots Dónde utilizarlos y por qué

### Descripción:


Los _Scoped Slots_ son un tipo de _slots_ especiales que nos ayudan a crear _templates_ reutilizables que exponen la información del componente para que los componentes padres puedan acceder a las _props_ de sus componentes hijos.

### Comentarios:

* **Jesús Miguel Quinto Teran** (2)

	
	Guao!! Tuve que ver el vídeo 2 veces!, esta genial ésto de los **Scoped Slots** , de hecho me sucedió un problema parecido en dos proyectos en Vue, mi solución fue modificar los componentes hijos.!!

* **Alejandro González Reyes** (2)

	
	En este enlace lo explican de forma detallada.  
	[Link](https://alligator.io/vuejs/scoped-component-slots/)

	* **Jhon Alexander Perez Valencia** (1)

		
		gracias

* **carlos-bolivar** (1)

	
	Es Genial la capacidad de personalizar nuestros componentes los _Scoped Slots_ Realmente hacen que nuestros componente sean muchos mas reutilizables.

* **Juan David Castro (Platzi)** (1)

	
	 **Ventajas y características de los Scoped Slots:**
	
	  * 🛃 Contenido más personalizado
	  * ♻️ Componentes más reutilizables
	  * 🔁 Acceso desde los componentes padres a los datos de los componentes hijos, algo así como pasar _props_ pero a la inversa 🙈👏
	  * 🤔 Son algo así como _renderless components_ o componentes que no renderizan contenido sino que los usamos para acceder a datos especiales de alguna parte, me atrevería a decir que son algo muy parecido a las [Render Functions](https://platzi.com/tutoriales/1199-react/2159-usa-functions-as-children-render-props-en-reactjs/) o componentes _Providers_ de React 👀
	
	

	* **Juan David Castro (Platzi)** (1)

		  * [Understanding scoped slots in Vue.js - Medium](https://medium.com/binarcode/understanding-scoped-slots-in-vue-js-db5315a42391)
		  * [Scoped Component Slots in Vue.js - Alligator.io](https://alligator.io/vuejs/scoped-component-slots/)
		  * [Using Scoped Slots in Vue.js to Abstract Functionality - CSS Tricks](https://css-tricks.com/using-scoped-slots-in-vue-js-to-abstract-functionality/)
		  * [Vue.js Scoped Slots & Renderless Components - YouTube](https://www.youtube.com/watch?v=6cn3xyK4Alk)
		
		

	* **Jhon Alexander Perez Valencia** (1)

		
		(y)

## 0320. Integración de Scoped Slots en Platzi Rooms

### Descripción:


### Comentarios:

* **Jhon Alexander Perez Valencia** (3)

	
	único comentario 😃

* **jhonsoverosovero** (1)

	
	que paso, no se puede ver el video!

* **luisangel2895** (1)

	
	nel x2 :v

* **Alexander Henry Obispo Buendia** (1)

	
	nel :v

# Deploy

## 0330. Creando y desplegando nuestra app en Heroku

### Descripción:


En esta clase el profesor Javier Diaz Chamorro nos explica cómo subir nuestras aplicaciones de Vue.js a la plataforma de Heroku.

Heroku es una plataforma de Salesforce que nos ayuda a desplegar nuestras aplicaciones con soporte para distintos lenguajes de programación. Heroku solo necesita saber el lenguaje de backend (en este caso es Node.js) y la base de datos que usamos para desarrollar nuestra aplicación. Solo debemos elegir un método de deploy, que puede ser conectando nuestros repositorios de Github para que los commits de una rama generen automáticamente un nuevo despliegue. O, si preferimos, descargando la herramienta de Heroku y haciendo los deploys manualmente.

### Links:

* [Cloud Application Platform | Heroku](https://www.heroku.com)

* [¿Qué es Heroku y para qué me sirve?](https://platzi.com/blog/que-es-heroku-y-para-que-me-sirve/)

### Comentarios:

* **Juan David Castro (Platzi)** (3)

	
	Uff. No se si vieron el detalle pero… !El profe hizo el commit para configurar el deploy de la aplicación directamente desde Visual Studio Code!

* **Sebastian Cardoso Castillo** (2)

	
	Yo no instale heroku pero lo tengo asociado a mi github y cada vez que hago push se modifica mi sitio web que tengo alojado.

* **Jesús Miguel Quinto Teran** (2)

	
	En en curso Profesional de Vuejs utilizamos **now** para hacer el Deploy y honestamente fue mucho mas fácil, **entonces** : cual es la ventaja de utilizar Heroku ?

	* **Anthony Will Solsol Soplin** (1)

		
		[Now.sh](http://Now.sh) solo provee alojamiento de páginas estáticas. Heroku es más bien comparable a App Engine de GCP. Para este ejemplo sería más que suficiente usar [Now.sh](http://Now.sh), pero Heroku provee lo necesario para realizar el backend, además se puede implementar bases datos y obtener el codigo fuente del servidor desde git. De todos modos es una opción más que es bueno conocer.

	* **Juan David Castro (Platzi)** (1)

		
		Incorrecto. Now también nos permite trabajar con backend, servidores, docker y todos los juguetes. 🤔

* **Anthony Will Solsol Soplin** (1)

	
	Hubiese sido interesante continuar con el ecosistema de Firebase y usar su servicio de Hosting. Igual muy agradecido con este video, porque estas configuraciones son de mucha ayuda para saber hacer del mismo modo deploy a un hosting más “tradicional”.

	* **Juan David Castro (Platzi)** (2)

		
		Puedes estudiarlo a profundidad en el Curso de Firebase para Web. 😉
		
		👉 <https://platzi.com/clases/1435-firebase-web/15618-que-nos-brinda-el-hosting-de-firebase/>

## 0340. Conclusiones y Despedida

### Descripción:


¡Felicitaciones por terminar el Curso Avanzado de Vue.js por Bedu!

Recuerda resolver los ejercicios, completar el examen, dejar 5 estrellitas y mostrarnos tus dudas o comentarios en la sección de discusiones.

### Comentarios:

* **Edward Steven Ramos Palacios** (3)

	
	Gracias Pro! por este curso 😃

* **citux** (2)

	
	vi muchas cosas de vue que no conocia muy bueno 😃

* **Northerchild** (1)

	
	Muchas gracias por todo profe

* **darwistg** (1)

	
	las peticiones al servidor se recomienda hacerse en el created() ??  
	la pregunta del examen tiene mala esa respuesta.

* **Ludwing Juan Homero Pérez Tzaquitzal** (1)

	
	Muy buen curso!

* **carlos-bolivar** (1)

	
	De los cursos mas completos de Vue que realizado, conforme y mucho mas con lo que nos brindo el profe Javier, todo un crack!!

* **Sebastian Cardoso Castillo** (1)

	
	A mi este curso me gusto muchisimo!

* **Jesús Miguel Quinto Teran** (1)

	
	 **Excelente curso!** , una de las cosas mas interesantes es el gran uso de los los slots, cada día me encanta mas Vuejs… Gracias!!!.

* **Jhon Alexander Perez Valencia** (1)

	
	## Excelente curso!

* **Wonder Jhonny Diaz Gonzalez** (1)

	
	Excelente, gracias!

