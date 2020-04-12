[Curso de Node.js con Hapi 1376](https://platzi.com/cursos/hapi-js)

# Introducción [2592]

## 0010. Bienvenida al curso y prerrequisitos [13995](https://platzi.com/clases/1376-hapi-js/13995-bienvenida-al-curso-y-prerrequisitos/)

### Descripción:


 **¿Qué es Hapi?**  
**Hapi** es uno de los frameworks más usados en el ecosistema de **NodeJS**. Está diseñado pensando en aplicativos modularizados de grandes dimensiones. Contempla la separación de la configuración de la lógica del negocio y utiliza su propia forma de hacer las cosas.  
Es usado para crear: Aplicativos Web, APIs REST, APIs en GraphQL, Proxies HTTP e Integrador de múltiples Backends, entre otros.

**Prerrequisitos del curso**

* Conocimientos básicos de NodeJS
* Conocimientos generales de arquitectura MVC
* Y opcionalmente, conocimientos básicos de: Express, Asincronía en Node con async / await y Firebase



### Comentarios:

* **Emerson Cedeño Salazar** (4) [397243](https://platzi.com/comentario/397243/) 

	"Opinionado" en este contexto quiere decir: "estrictamente estructurado"?

	* **Julio J Yépez** [397243] (3)

		Opinionado yo creo que se refiere más a que “tiene su propia manera de hacer las cosas”, que se aleja un poco de los convencionalismos o estándares más ampliamente adoptados.

	* **edsadr** [397243] (4)

		Me refiero a que tiene una forma definida de como hacer las cosas, muchos frameworks simplemente proveen una estructura básica y ya tu decides como usarla, Hapi te da ya de entrada una estructura que cumple con buenas prácticas

* **Juan David Castro (Platzi)** (2) [395252](https://platzi.com/comentario/395252/) 

	Recorderis 😼

	* **Julio J Yépez** [395252] (2)

		… es como cuando dices “a priori” o “grosso modo” … sería sinónimo de “recordatorio”.

* **Agustin Clemente** (2) [394827](https://platzi.com/comentario/394827/) 

	Donde esta el curso básico de node?

	* **Kevin Javier Morales (Platzi)** [394827] (1)

		Todavía no ha salido

	* **Juan José Vega Quintero** [394827] (1)

		Ya salió

* **Chrystian Fabian Lozano Ramirez** (1) [871645](https://platzi.com/comentario/871645/) 

	Este curso es mejor que el de Sails?

	* **Eduardo P. Rivero** [871645] (2)

		Yo he usado ambos y depende de cómo te guste trabajar los proyectos:
		
		Sails es un framework más grande con muchas más convenciones que hapi, por ejemplo Sails te fuerza por defecto a cierta estructura de carpetas/archivos y a usar tu capa de datos con Waterline su ORM. Mientras que Hapi está centrado más en el servidor web no te fuerza a una estructura de carpetas/archivos y puedes complementarlo con cualquier otro _library_ para base de datos.
		
		Yo prefiero HapiJs basicamente por los server methods.

* **Alejandro González Reyes** (1) [747039](https://platzi.com/comentario/747039/) 

	Wallmart nuevamente. Quién pensaría que Black Friday en USA y el Buen Fín en México pondrían en aprietos a muchos equipos de desarrollo de estas grandes empresas.
	
	Si no mal recuerdo NodeJS nace al ingenio de uno de los desarrolladores que trabajaba en Wallmart

* **TeoOL** (1) [65677](https://platzi.com/comentario/695944/) 
Existen mas usos a ademas de los que has mencionado?

	* **Juan David Castro (Platzi)** [65677] (1)

		Hapi desarrolla muchas herramientas. Obviamente, el punto central es la creación de aplicaciones web o APIs REST y GraphQL. Pero también existen paquetes como **`@hapi/joi`** que nos ayuda a validar información y funciona para aplicaciones de cualquier fin.
		
		* <https://www.npmjs.com/package/@hapi/joi>
		* <https://github.com/hapijs>
		
		

## 0020. Breve historia y estado actual [13996](https://platzi.com/clases/1376-hapi-js/13996-breve-historia-y-estado-actual/)

### Descripción:


_Hapi_ fue creado por Eran Hammer, el mismo desarrollador y creador de la especificación _OAuth_ , quien siendo líder del equipo de Mobile en _Walmart_ , se vió en la necesidad de buscar una solución a los problemas relacionados con el tráfico del sitio web durante los días cercanos al BlackFriday.

Junto a su equipo crea _Hapi_ , como un middleware de _Express_ , ya que éste no les ofrecía solución a los problemas que estaban enfrentando. Luego de probar diferentes combinaciones de soluciones, decidieron crear todo el framework desde cero sobre la base del principio: _““mejor configuración que código””_ , e inspirados en Express y Director. Así que crearon un concepto nuevo con el que lograron soluciones más eficientes para su problema.

Recientemente _Hapi_ (en su versión más reciente 17.x) fue rediseñado para aprovechar toda la funcionalidad y potencialidad que ofrece el trabajo asincrónico con **Async / Wait** de **NodeJS**.

### Comentarios:

* **jesusmurf** (5) [396273](https://platzi.com/comentario/396273/) 

	Me gustaría saber si es posible trabajar con Typescript en Hapi

	* **jesusmurf** [396273] (2)

		Aprovecho para preguntar si también es posible trabajar con GraphQL 😃

	* **Juan David Castro (Platzi)** [396273] (4)

		Claro! Hay muchos recursos en Github y en Medium.
		
		<https://hapibook.jjude.com/>

	* **Juan David Castro (Platzi)** [396273] (6)

		Para GraphQL: [Setting up GraphQL with Hapi.js](https://blog.callstack.io/super-simple-graphql-server-with-hapi-js-mongodb-and-a-new-apollo-server-41418ded2faf).

	* **jesusmurf** [396273] (2)

		Muchas gracias amigo!

	* **edsadr** [396273] (5)

		Para TS: <https://github.com/dwyl/hapi-typescript-example>  
		en la clase sobre el ecosistema de Hapi dejo un enlace sobre GraphQL también

	* **Luis Paredes** [396273] (1)

		Primera vez que veo un profesor comentar aqui para ayudar, excelente!

	* **Juan David Castro (Platzi)** [396273] (1)

		@luisparedes cada vez pasa más seguido… 💪

* **jesusmurf** (2) [43347](https://platzi.com/comentario/396273/) 
Me gustaría saber si es posible trabajar con Typescript en Hapi

	* **jesusmurf** [43347] (2)

		Aprovecho para preguntar si también es posible trabajar con GraphQL 😃

* **Brandon Iván Quiroa Loarca** (1) [1058756](https://platzi.com/comentario/1058756/) 

	Que genial que haya explicado el trasfondo de Hapi!

* **Alejandro González Reyes** (1) [747056](https://platzi.com/comentario/747056/) 

	Desde hace años vengo usando linux y cuando comencé a trabajar con nodeJS, ví el mismo sistema de reutilización de librerías.  
	En un principio puede ser factible mantener delgado el software, pero pasado el tiempo es un sufrimiento, pues muchas librerías se van quedando obsoletas, por lógica hay que actualizarlas o cambiarlas. Pero el problema surge cuando no hay compatibilidad.
	
	Lo mejor es tener todo el control.

## 0030. Conceptos principales de hapi y creación de nuestro primer servidor [13997](https://platzi.com/clases/1376-hapi-js/13997-conceptos-principales-de-hapi-y-creacion-de-nuestr/)

### Descripción:


El _servidor_ es la unidad básica y principal de los aplicativos web.

Para crear un servidor con **Hapi** , sólo basta con requerir el módulo y luego ejecutar la función _server_ :
``` 
    const Hapi = require(""hapi"")
    
    const server = Hapi.server({
      port: 3000,
      host: 'localhost'
    })
    
```

Luego es necesario definir los puntos de interacción mediante una _ruta_ :
``` 
    server.route({
      method: 'GET',
      path: '/hola',
      handler: (request, h) => {
        return 'Hola Mundo'
      }
    })
    
```

La propiedad _method_ indica si el request esperado es de tipo _GET_ o _POST_ , y el _path_ es la url relativa asociada a esta ruta definida. El _handler_ es la función que manejará la respuesta que se enviará al navegador.

### Comentarios:

* **Eduardo Hidalgo Díaz Rugama** (5) [405906](https://platzi.com/comentario/405906/) 

	es la introducción mas completa, simple, y efectiva que he tenido sobre API’s (:

* **Jose Alberto Arango Sánchez** (3) [642456](https://platzi.com/comentario/642456/) 

	Esto si es un profesor, debería dar los cursos de Node.js.

* **Jhon Alexander Perez Valencia** (3) [626465](https://platzi.com/comentario/626465/) 

	```
	    "use strict"
	    
	    const hapi = require("hapi");
	    
	    const server = hapi.server({
	      port: process.env.PORT || 3000,
	      host: "localhost"
	    })
	    
	    const init = async () => {
	      server.route({
	        method: "GET",
	        path: "/",
	        handler: (req, h)=>{
	          return {hello:"world"}
	        }
	      })
	    
	      try {
	        await server.start()
	      } catch (error) {
	        console.error(error)
	        process.exit(1)
	      }
	    
	      console.log("The server is on")
	    }
	    
	    init()
	    
	```

* **Carlos Andrés Charris S** (3) [394878](https://platzi.com/comentario/394878/) 

	```
	    "scripts": {
	        "dev": "nodemon, ",
	        "lint": "standard",
	        "lint-fix": "standard --fix",
	        "test": "echo \"Error: notest specified\" && exit 1"
	      }```
	    
	```

* **Carlos Andrés Charris S** (3) [394829](https://platzi.com/comentario/394829/) 

	```
	    const hapi = require('hapy');
	    
	    // Configuramos el servidor
	    const sever = hapi.server({
	    	port: 3000,
	    	host: 'localhost'
	    });
	    
	    // Configuramos las rutas de accedo a nuestro API
	    server.route({
	    	method: 'GET',
	    	path: '/hola',
	    	handler: (request, h)=>{
	    		return'Hola Mundo';
	    	}
	    })
	    
	    
	```
	
	`method: // método con el cual se va a hacer la petición`  
	`path: // ruta de acceso`  
	`handler: // Lógica de la petición`

	* **Jecsham Castillo** [394829] (2)

		`const Hapi = require('hapi')`

* **Alejandro González Reyes** (2) [747072](https://platzi.com/comentario/747072/) 

	Hapi se ha actualizado y para poder instalarlo es necesario
	``` 
	    npm i @hapi/hapi
	    
	```

* **Luis Paredes** (2) [597209](https://platzi.com/comentario/597209/) 

	Con esta clase aprendi mas que en los otros 2 cursos de nodejs que hice anteriormente, que buen profesor!

	* **Jose Alberto Arango Sánchez** [597209] (1)

		Es que este man si sabe como enseñar, se ensucia las manos tirando código, no como los otros que andan explicando código

* **darwin1111** (2) [43496](https://platzi.com/comentario/397829/) 
¿Que tipo de extensiones utilizas en Visual Estudio Code?

	* **edsadr** [43496] (5)

		aqui te dejo mi lista de extensiones:
		
		code --install-extension Rubymaniac.vscode-paste-and-indent  
		code --install-extension Zignd.html-css-class-completion  
		code --install-extension abusaidm.html-snippets  
		code --install-extension alefragnani.project-manager  
		code --install-extension andrejunges.Handlebars  
		code --install-extension chenxsan.vscode-standardjs  
		code --install-extension christian-kohler.npm-intellisense  
		code --install-extension codezombiech.gitignore  
		code --install-extension dbaeumer.vscode-eslint  
		code --install-extension deerawan.vscode-hapijs-snippets  
		code --install-extension donjayamanne.githistory  
		code --install-extension dsznajder.es7-react-js-snippets  
		code --install-extension dzannotti.vscode-babel-coloring  
		code --install-extension eamodio.gitlens  
		code --install-extension eg2.vscode-npm-script  
		code --install-extension Equinusocio.vsc-material-theme  
		code --install-extension esbenp.prettier-vscode  
		code --install-extension formulahendry.auto-close-tag  
		code --install-extension GitHub.vscode-pull-request-github  
		code --install-extension HookyQR.beautify  
		code --install-extension joelday.docthis  
		code --install-extension kisstkondoros.vscode-codemetrics  
		code --install-extension kumar-harsh.graphql-for-vscode  
		code --install-extension leizongmin.node-module-intellisense  
		code --install-extension mechatroner.rainbow-csv  
		code --install-extension miramac.vscode-exec-node  
		code --install-extension ms-azuretools.vscode-azurefunctions  
		code --install-extension ms-vscode.azure-account  
		code --install-extension ms-vscode.sublime-keybindings  
		code --install-extension ms-vsliveshare.vsliveshare  
		code --install-extension ms-vsliveshare.vsliveshare-audio  
		code --install-extension msjsdiag.debugger-for-chrome  
		code --install-extension octref.vetur  
		code --install-extension PeterJausovec.vscode-docker  
		code --install-extension PKief.material-icon-theme  
		code --install-extension Shan.code-settings-sync  
		code --install-extension streetsidesoftware.code-spell-checker  
		code --install-extension streetsidesoftware.code-spell-checker-spanish  
		code --install-extension techer.open-in-browser  
		code --install-extension vincaslt.highlight-matching-tag  
		code --install-extension wesbos.theme-cobalt2  
		code --install-extension wix.vscode-import-cost  
		code --install-extension xabikos.JavaScriptSnippets  
		code --install-extension xabikos.ReactSnippets

* **albertodsosa** (1) [1033335](https://platzi.com/comentario/1033335/) 

	Tips para crear nuevos proyectos <https://philna.sh/blog/2019/01/10/how-to-start-a-node-js-project/>

* **Eduardo P. Rivero** (1) [961810](https://platzi.com/comentario/961810/) 

	Hapi y sus módulos oficiales cambiaron ahora se instalan y referencian de manera distinta, escribí un tutorial sobre eso:
	
	<https://platzi.com/tutoriales/1376-hapi-js/4883-actualiza-hapijs-a-su-nueva-dependencia-en-npm/>

	* **Juan José Vega Quintero** [961810] (1)

		Gracias!!!  
		Me ayudo mucho

* **Alejandro González Reyes** (1) [747108](https://platzi.com/comentario/747108/) 

	Favor de corregirme:  
	el ultimo console.log está mal ubicado, ya que al estar fuera del try se ejecuta antes que el server se haya iniciado…

	* **gorydev** [747108] (1)

		Estás equivocado, el código entra al try y ejecuta la parte del await lo cuál no avanzará hasta obtener una respuesta si esta no trae error entonces se sale del try/catch y ejecuta el console.log pero si trae un error entonces entra al catch y ejecuta el console.error

* **Edgar de Jesus Mendoza Ortegon** (1) [702544](https://platzi.com/comentario/702544/) 

	El mejor curso de nodejs en platzi muy buena clase.

* **Gaston Morales** (1) [683540](https://platzi.com/comentario/683540/) 

	Magnifica Explicación

* **Bjota** (1) [569850](https://platzi.com/comentario/569850/) 

	Dependencias  
	npm i standard nodemon -D  
	npm i hapi -S

* **darwin1111** (1) [397829](https://platzi.com/comentario/397829/) 

	¿Que tipo de extensiones utilizas en Visual Estudio Code?

	* **edsadr** [397829] (5)

		aqui te dejo mi lista de extensiones:
		
		code --install-extension Rubymaniac.vscode-paste-and-indent  
		code --install-extension Zignd.html-css-class-completion  
		code --install-extension abusaidm.html-snippets  
		code --install-extension alefragnani.project-manager  
		code --install-extension andrejunges.Handlebars  
		code --install-extension chenxsan.vscode-standardjs  
		code --install-extension christian-kohler.npm-intellisense  
		code --install-extension codezombiech.gitignore  
		code --install-extension dbaeumer.vscode-eslint  
		code --install-extension deerawan.vscode-hapijs-snippets  
		code --install-extension donjayamanne.githistory  
		code --install-extension dsznajder.es7-react-js-snippets  
		code --install-extension dzannotti.vscode-babel-coloring  
		code --install-extension eamodio.gitlens  
		code --install-extension eg2.vscode-npm-script  
		code --install-extension Equinusocio.vsc-material-theme  
		code --install-extension esbenp.prettier-vscode  
		code --install-extension formulahendry.auto-close-tag  
		code --install-extension GitHub.vscode-pull-request-github  
		code --install-extension HookyQR.beautify  
		code --install-extension joelday.docthis  
		code --install-extension kisstkondoros.vscode-codemetrics  
		code --install-extension kumar-harsh.graphql-for-vscode  
		code --install-extension leizongmin.node-module-intellisense  
		code --install-extension mechatroner.rainbow-csv  
		code --install-extension miramac.vscode-exec-node  
		code --install-extension ms-azuretools.vscode-azurefunctions  
		code --install-extension ms-vscode.azure-account  
		code --install-extension ms-vscode.sublime-keybindings  
		code --install-extension ms-vsliveshare.vsliveshare  
		code --install-extension ms-vsliveshare.vsliveshare-audio  
		code --install-extension msjsdiag.debugger-for-chrome  
		code --install-extension octref.vetur  
		code --install-extension PeterJausovec.vscode-docker  
		code --install-extension PKief.material-icon-theme  
		code --install-extension Shan.code-settings-sync  
		code --install-extension streetsidesoftware.code-spell-checker  
		code --install-extension streetsidesoftware.code-spell-checker-spanish  
		code --install-extension techer.open-in-browser  
		code --install-extension vincaslt.highlight-matching-tag  
		code --install-extension wesbos.theme-cobalt2  
		code --install-extension wix.vscode-import-cost  
		code --install-extension xabikos.JavaScriptSnippets  
		code --install-extension xabikos.ReactSnippets

* **Wladimir Hernández** (1) [395392](https://platzi.com/comentario/395392/) 

	Me gusta lo ordenado que se escribe el código en Hapi, el problema que he tenido con express es que me parece que no es muy intuitivo.

# Creando un sitio básico con Hapi [2593]

## 0040. El objeto h, response y sus herramientas [13998](https://platzi.com/clases/1376-hapi-js/13998-el-objeto-h-response-y-sus-herramientas/)

### Descripción:


El objeto **h** , es el segundo argumento que recibe la función _handler_ de una ruta definida.

Contiene una colección de utilidades y propiedades relativas a la información de respuesta que se va a enviar al cliente, al navegador.

Métodos básicos del objeto h:

* h. **response** (): Crea un objeto de respuesta.
* h. **redirect** (): Redirecciona una petición.



El objeto **Response** (creado con el método _h.response_ ), permite definir las propiedades de la respuesta. A través de este objeto se pueden especificar las cabeceras, tipo de documento y código de respuesta devuelto al cliente, mediante los métodos: .header(), .type() y .code()

Código: Ejemplo de respuesta simple y redirect.

### Links:

* [17.6.0 API Reference](https://hapijs.com/api#response-toolkit)

* [17.6.0 API Reference](https://hapijs.com/api#response-object)

* [17.6.0 API Reference](https://hapijs.com/api#response-toolkit)

### Comentarios:

* **Alejandro González Reyes** (4) [747129](https://platzi.com/comentario/747129/) 

	Dejo mi apunte de esta clase en el código
	``` 
	    'use strict'
	    
	    // Requerir el modulo de hapi (Framework)
	    const Hapi = require('@hapi/hapi')
	    
	    // Configurar el servidor de nuestra aplicación. En un contenedor (Docker) si marca error colocar 0.0.0.0 (todos)
	    const server = Hapi.server({
	      port: process.env.PORT || 3000,
	      host: 'localhost'
	    })
	    
	    // Definicion de función para inicializar el proyecto. Intenamnete hay tareas asincronas
	    asyncfunctioninit() {
	      // Definición de rutas (indicar el método HTTP, URL y controlador de ruta)
	      server.route({
	        method: 'GET',
	        path: '/',
	        handler: (req, h) => {
	          // El objeto h es un conjunto de utilidades para la respuesta.
	          return h.response('Hola desde HapiJS').code(200)
	        }
	      })
	    
	      server.route({
	        method: 'GET',
	        path: '/redirect',
	        handler: (req, h) => {
	          return h.redirect('https://platzi.com')
	        }
	      })
	    
	      // Arrancar el servidor de HapiJS, se considera una tarea asincrona.
	      try {
	        await server.start()
	        console.log(`Servidor lanzado en: ${server.info.uri}`)
	      } catch (error) {
	        console.error(error)
	        // Salir de nodeJS con un código de error (1), 0 es un código de exito
	        process.exit(1)
	      }
	    }
	    
	    // Inicializar el proyecto
	    init();
	    
	```

* **Alejandro González Reyes** (3) [747128](https://platzi.com/comentario/747128/) 

	Hasta el momento ExpressJS me gusta mucho como organiza las cosas, pero es importante tener conocimiento de otros Frameworks.

* **Andres Mora Vanegas** (2) [395933](https://platzi.com/comentario/395933/) 
Falto un video, llego a explicar un tema sobre algo que ya había explicado y no hay un inicio del proyecto ni nada

	* **jesusmurf** [395933] (1)

		Creo que solo es en la versión mobile y para tablets que no aparece esa clase

	* **i_ChrisRojas** [395933] (2)

		En escritorio se ve perfecto la clase que mencionas. Cabe destacar que es un video de Youtube. Por ende quizás tuvo algún problema de compatibilidad con el dispositivo que estas viendo tu.
		
		Saludos.

	* **Kerohuixco** [395933] (1)

		Si esta una clase antes que esta.

* **oqodigital** (2) [73782](https://platzi.com/comentario/841236/) 
@hapi/hapi o solo hapi? Cuál es la diferencia?

	* **Juan David Castro (Platzi)** [73782] (3)

		De ahora en adelante debemos usar **`@hapi/hapi`** , pero no hay nada de qué preocuparse, sigue funcionando como ante. Al principio de esta lectura se explica por qué: <https://www.npmjs.com/package/hapi>. 😉

* **José Daniel Hernández Estrada** (1) [685519](https://platzi.com/comentario/685519/) 

	He probado varios framework y Hapi me ha parecido el mejor hasta el momento 😃

## 0050. Uso de plugins - Contenido estático [13999](https://platzi.com/clases/1376-hapi-js/13999-uso-de-plugins-contenido-estatico/)

### Descripción:


Los **plugins** son módulos o archivos de Javascript creados generalmente por terceros, que le adicionan funcionalidades al framework base de **Hapi**.

Para implementar un _plugin_ nuevo a nuestro proyecto, lo primero es importarlo en el index.js con la función **requier()** de NodeJS. Luego es necesario registrarlo con `await server.register(plugin)`.

Por el momento, incluiremos en nuestro proyecto los plugins de **Inert** y **Path**
``` 
    const inert = require('inert')
    const path = require('path')
    
```

El plugin **Inert** extiende los métodos disponibles en el _objeto h_ , y **Path** nos permite definir una ubicación relativa para todos los **routes** de nuestro proyecto, entre otras cosas.

Código: usando Inert para servir un directorio de archivos y  
un index.html en el path ‘/’

### Links:

* [inert  -  npm](https://www.npmjs.com/package/inert)

* [17.6.0 API Reference](https://hapijs.com/api#server.options.routes)

* [17.6.0 API Reference](https://hapijs.com/api#-routeoptionsfiles)

### Comentarios:

* **Juan  Reyes** (8) [394774](https://platzi.com/comentario/394774/) 

	Este video tiene un audio algo bajo…

	* **davidtoca (Platzi)** [394774] (1)

		gracias por el reporte, lo vamos a revisar

	* **Mateo Santiago Zapata Maldonado** [394774] (1)

		Normal.

* **Gerardo Cetzal Balam** (5) [809649](https://platzi.com/comentario/809649/) 

	This package has been deprecated  
	npm i inert
	
	[ahora](https://www.npmjs.com/package/@hapi/inert) es con npm i @hapi/inert

* **Alejandro González Reyes** (2) [747174](https://platzi.com/comentario/747174/) 

	Mi aporte en el código
	``` 
	    'use strict'
	    
	    // Requerir el modulo de hapi (Framework)
	    const Hapi = require('@hapi/hapi')
	    // Requerir el plugin de hapi para servir archivos estaticos
	    const inert = require('inert')
	    const path = require('path')
	    
	    // Configurar el servidor de nuestra aplicación. En un contenedor (Docker) si marca error colocar 0.0.0.0 (todos)
	    const server = Hapi.server({
	      port: process.env.PORT || 3000,
	      host: 'localhost',
	      // Definir propiedades generales para todas las rutas. (En este caso indico que las rutas que requieran archivos estáticos, se servirán desde la carpeta public)
	      routes: {
	        files: {
	          relativeTo: path.join(__dirname, 'public')
	        }
	      }
	    
	    })
	    
	    // Definicion de función para inicializar el proyecto. Intenamnete hay tareas asincronas
	    asyncfunctioninit() {
	    
	      try {
	        // Registrar los plugins que hapi va a necesitar (en este caso servir archivos estaticos)
	        await server.register(inert)
	    
	        // Definición de rutas (indicar el método HTTP, URL y controlador de ruta)
	        // Se declaran después del plugin ya que las rutas hacen uso del misom para devolver archivos estáticos
	        server.route({
	          method: 'GET',
	          path: '/home',
	          handler: (req, h) => {
	            // El plugin de inert inyecta el metodo file en el objeto h para servir un archivo estático
	            return h.file('index.html').code(200)
	          }
	        })
	    
	        // Ruta para servir archivos estáticos asociados (img/css/js)
	        server.route({
	          method: 'GET',
	          path: '/{param*}',
	          handler: {
	            directory: {
	              path: '.',
	              redirectToSlash: true
	            }
	          }
	        })
	    
	        // Arrancar el servidor de Hapi
	        await server.start()
	        console.log(`Servidor lanzado en: ${server.info.uri}`)
	      } catch (error) {
	        console.error(error)
	        // Salir de nodeJS con un código de error (1), 0 es un código de exito
	        process.exit(1)
	      }
	    }
	    
	    // Inicializar el proyecto
	    init();
	    
	```

* **Alejandro González Reyes** (2) [747134](https://platzi.com/comentario/747134/) 

	Es importante mencionar que path es un módulo nativo de NodeJS, no es un plugin.

* **Bjota** (2) [57900](https://platzi.com/comentario/570453/) 
Cúal es la extensión de VSC para visualizar el tamaño de los archivos importados?

	* **sampol.90 (Platzi)** [57900] (3)

		Puedes usar ImportCost para esto 😃

* **Juan José Vega Quintero** (1) [1100366](https://platzi.com/comentario/1100366/) 

	A cambiado bastante todo, el código que a día de hoy me funciona
	``` 
	    "use strict";
	    
	    const Hapi = require("@hapi/hapi");
	    const inert = require("@hapi/inert");
	    const path = require("path");
	    
	    const server = new Hapi.server({
	      port: 3000,
	      host: "localhost",
	      routes: {
	        files: {
	          relativeTo: path.join(__dirname, "public"),
	        },
	      },
	    });
	    
	    const provision = async () => {
	      try {
	        await server.register(inert);
	    
	        server.route({
	          method: "GET",
	          path: "/home",
	          handler: (request, h) => {
	            return h.file("index.html");
	          },
	        });
	    
	        server.route({
	          method: "GET",
	          path: "/{param*}",
	          handler: {
	            directory: {
	              path: ".",
	              redirectToSlash: true,
	              index: true,
	            },
	          },
	        });
	    
	        await server.register(inert);
	        await server.start();
	      } catch (error) {
	        process.on("unhandledRejection", (err) => {
	          console.log(err);
	          process.exit(1);
	        });
	      }
	      console.log("Server running on %s", server.info.uri);
	    };
	    
	    provision();
	    
	    
	```

* **Luis Fernando Farji** (1) [677318](https://platzi.com/comentario/677318/) 

	En archivos y enlaces falta registrar inert

* **Bjota** (1) [570453](https://platzi.com/comentario/570453/) 

	Cúal es la extensión de VSC para visualizar el tamaño de los archivos importados?

	* **sampol.90 (Platzi)** [570453] (3)

		Puedes usar ImportCost para esto 😃

* **ing.stephanysc** (1) [82217](https://platzi.com/comentario/1000411/) 
No se ningun paquete de hapi/hapi, ni hapi/inert funciona, no seguire más este curso, realmente frustrante.

* **Alejandro González Reyes** (1) [68847](https://platzi.com/comentario/747173/) 
Mi aporte en el código 'use strict' // Requerir el modulo de hapi (Framework) const Hapi = require('@hapi/hapi') // Requerir el pl...

* **Alejandro González Reyes** (1) [68846](https://platzi.com/comentario/747170/) 
Porque se organizó la ubicación de las rutas después del registro del plugin?

## 0060. Plantillas con Handlebars [14000](https://platzi.com/clases/1376-hapi-js/14000-plantillas-con-handlebars/)

### Descripción:


Las _plantillas_ son generalmente archivos _html_ con marcadores particulares que permiten la inserción de variables y la ejecución de algunas instrucciones de programación, antes de ser renderizados. Esta interpretación previa la realiza un plugin conocido como **motor de plantillas** , como es el caso de **Handlebars**.

Para incluir variables o instrucciones de código con **Handlebars** es necesario el uso de dobles llaves (o _curly braces_ ). Un bloque de _html_ con **Handlebars** sería algo como lo siguiente:
``` 
    <div class=""post"">
      <h1>Author: {{fullName author}}</h1>
      <div class=""body"">{{body}}</div>
    
      <h1>Comments</h1>
    
      {{#each comments}}
      <h2>By {{fullName author}}</h2>
      <div class=""body"">{{body}}</div>
      {{/each}}
    </div>
    
```

Los _bloques de instrucción_ en **Handlebars** comienzan con **#** y se cierran con **/**.

Para más información, recuerda consultar la documentación oficial en <http://handlebarsjs.com/> y así conocer mucho más de las opciones que te brinda este potente motor de plantillas.

### Links:

* [Try Handlebars.js in your web browser](http://tryhandlebarsjs.com/)

* [Handlebars.js: Minimal Templating on Steroids](http://handlebarsjs.com/)

* [handlebars  -  npm](https://www.npmjs.com/package/handlebars)

### Comentarios:

* **marcelobaez** (5) [402926](https://platzi.com/comentario/402926/) 

	El profe utiliza una extensión en VSCode llamada Import Cost, la cual permite saber cual es el tamaño de modulos importados, y ademas “colorea” si considera que es pesado/costoso.
	
	En lo personal me resultó un poco molesto porque me gusta tener el IDE lo mas limpio posible, pero recomiendo le den una prueba al mismo:
	
	[<https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost>]

* **Alejandro González Reyes** (1) [747181](https://platzi.com/comentario/747181/) 

	Me siento cómodo al ver nuevamente las dobles llaves al estilo Blade de Laravel.  
	Pug en limpio pero en ocasiones se vuelve molesto cuando tienes anidación de tags o br

* **Edgar de Jesus Mendoza Ortegon** (1) [702584](https://platzi.com/comentario/702584/) 

	esto se puede configurar con reactjs?

* **waldoaraque** (1) [674281](https://platzi.com/comentario/674281/) 

	Esto me recuerda un poco a la forma de manejar los templates con AngularJS…

* **Jairo Junior Casalins Blanco** (1) [593553](https://platzi.com/comentario/593553/) 

	¿cual es mejor nunjucks o handlebars.js?

	* **Diego Alexander Forero Higuera (Platzi)** [593553] (2)

		Creo que todo va en gustos. Hay motores de templates que tienen algunas funcionalidades interesantes pero al final del día es con el motor de templates con el que te sientas mas cómodo trabajando.

* **eddyarellanes** (1) [463993](https://platzi.com/comentario/463993/) 

	Hace años use Handlebars con MeteorJs, pero en ese entonces no sabía xD

* **Wladimir Hernández** (1) [395425](https://platzi.com/comentario/395425/) 

	Creo que a los que venimos utilizando frameworks modernos de JavaScript, Handlebars nos cae de anillo al dedo.

* **Jorman Ortega** (1) [62211](https://platzi.com/comentario/635936/) 
A la hora de usar un motor de plantillas cual es mas recomendable handlerbars o EJS ?

	* **Diego Alexander Forero Higuera (Platzi)** [62211] (3)

		Creo que todo va en gustos. Hay motores de templates que tienen algunas funcionalidades interesantes pero al final del día es con el motor de templates con el que te sientas mas cómodo trabajando. No hay uno mejor que el otro, solo uno con el que te sientes mejor trabajando.

* **Jose Alberto Arango Sánchez** (0) [642526](https://platzi.com/comentario/642526/) 

	Buen curso 😃

## 0070. Renderizado de vistas - Layout y template del home [14001](https://platzi.com/clases/1376-hapi-js/14001-renderizado-de-vistas-layout-y-template-del-home/)

### Descripción:


En **Hapi** podemos usar la arquitectura _MVC (Modelo-Vista-Controlador)_ para organizar la lógica de nuestras aplicaciones. Para implementar el uso de _vistas_ es necesario instalar el plugin **Vision** y configurarlo de la siguiente manera:
``` 
    server.views({
      engines: { // --- hapi puede usar diferentes engines
        hbs: handlebars // --- asociamos el plugin al tipo de archivos  
      },
      relativeTo: __dirname, // --- para que las vistas las busque fuera de /public
      path: 'views', // --- directorio donde colocaremos las vistas dentro de nuestro proyecto
      layout: true, // --- indica que usaremos layouts 
      layoutPath: 'views' // --- ubicación de los layouts
    })
    
```

Al crear el archivo **layout.hbs** evitaremos repetir las mismas secciones de html en cada una de las vistas, remplazando sólo lo relativo al contenido que cambiará según las rutas definidas en nuestra aplicación.

En la definición de las rutas, tendremos que cambiar la respuesta devuelta en _handler_ para que invoque a **h.view()** en lugar de **h.file()** , con los parámetros esperados por el layout.

Para poder incorporar el html de las vistas dentro del _layout.hbs_ , es necesario usar **triples llaves** en lugar de **dobles** , ya que por defecto Handlebars escapa el código _html_ convirtiéndolo en su equivalente texto plano.

### Links:

* [vision  -  npm](https://www.npmjs.com/package/vision)

### Comentarios:

* **Alejandro González Reyes** (3) [747204](https://platzi.com/comentario/747204/) 

	Mi aporte en código
	``` 
	    'use strict'
	    
	    // Requerir el modulo de hapi (Framework)
	    const Hapi = require('@hapi/hapi')
	    // Requerir el plugin de hapi para servir archivos estaticos
	    const inert = require('@hapi/inert')
	    // Requerir el plugin de hapi para gestionar el motor de plantillas
	    const vision = require('@hapi/vision')
	    const path = require('path')
	    
	    // Configurar el servidor de nuestra aplicación. En un contenedor (Docker) si marca error colocar 0.0.0.0 (todos)
	    const server = Hapi.server({
	      port: process.env.PORT || 3000,
	      host: 'localhost',
	      // Definir propiedades generales para todas las rutas. (En este caso indico que las rutas que requieran archivos estáticos, se servirán desde la carpeta public)
	      routes: {
	        files: {
	          relativeTo: path.join(__dirname, 'public')
	        }
	      }
	    
	    })
	    
	    // Definicion de función para inicializar el proyecto. Intenamnete hay tareas asincronas
	    asyncfunctioninit() {
	    
	      try {
	        // Registrar los plugins que hapi va a necesitar (en este caso servir archivos estaticos)
	        await server.register(inert)
	        // Registrar plugin para gestionar el motor de plantillas
	        await server.register(vision)
	    
	        // Configurar nuestro motor de plantillas. Usará handlebars y cuando invoquemos una vista automáticamente buscará una con extensión hbs (no hace falta especificarlo). Debe buscar a partir del directorio actual, las vistas se encuentran en views y se activa compatibilidad con layouts, los cuales se encuentran en layouts
	        server.views({
	          engines: {
	            hbs: require('handlebars')
	          },
	          relativeTo: __dirname,
	          path: 'views',
	          layout: true,
	          layoutPath: 'layouts'
	        })
	    
	        // Definición de rutas (indicar el método HTTP, URL y controlador de ruta)
	        // Se declaran después del plugin ya que las rutas hacen uso del misom para devolver archivos estáticos
	        server.route({
	          method: 'GET',
	          path: '/',
	          handler: (req, h) => {
	            // El plugin de vision inyecta el metodo view al objeto h para renderizar una vista con el motor de plantillas configurado en la aplicación
	            return h.view('index', {
	              title: 'Home'
	            })
	          }
	        })
	    
	        // Ruta para servir archivos estáticos asociados (img/css/js)
	        server.route({
	          method: 'GET',
	          path: '/{param*}',
	          handler: {
	            directory: {
	              path: '.',
	              redirectToSlash: true
	            }
	          }
	        })
	    
	        // Arrancar el servidor de Hapi
	        await server.start()
	        console.log(`Servidor lanzado en: ${server.info.uri}`)
	      } catch (error) {
	        console.error(error)
	        // Salir de nodeJS con un código de error (1), 0 es un código de exito
	        process.exit(1)
	      }
	    }
	    
	    // Inicializar el proyecto
	    init();
	    
	```

* **Julio J Yépez** (2) [398253](https://platzi.com/comentario/398253/) 

	En la configuración de **Handlebars** , la propiedad _layoutPath_ estaba escrita como ‘view’ … ya luego fue corregida como ‘views’, puesto que se refieren al mismo directorio indicado en _path_.

* **Armando_Alamilla** (2) [395421](https://platzi.com/comentario/395421/) 

	No entendí muy bien la función que tiene layoutPath.  
	El profesor menciona que esta propiedad nos va a permitir poner los layouts junto con las vistas.  
	Pero no entiendo muy bien a qué se refiere. ¿alguien podría ayudarme?

	* **edsadr** [395421] (3)

		Básicamente es una propiedad que permite definir donde vision va a buscar los archivos de layouts, para no tener una estructura más compleja lo definimos al mismo directorio donde están las visitas, pero digamos que es posible tener los layouts separados de las vistas en otro directorio y definir el path a ese directorio usando la propiedad layoutPath… si tienes más dudas me cuentas

	* **yoshua_diaz** [395421] (5)

		Hay un archivo que creo llamado **layout.hbs** (qué contiene todo el contenido común entodas las vistas) y otro llamado **index.hbs** (qué contiene información solo para el home), si vez el archivo index.hbs no hay nada que le diga que template usar como layout, entonces con las propiedades **layout:true** le dice que vamos a soportar layouts y con **layoutPath** le decimos donde esta el archivo que usaremos como layout, ya que sin eso verías el contenido del index.hbs sin la cabecera y las llamadas a los estilos y scripts, espero haberte podido ayudar 😃

	* **Sabrina Valerio Hidalgo** [395421] (1)

		Esto es un poco más sencillo de entender si estudias un framework de JS.

* **Juan José Vega Quintero** (1) [1100449](https://platzi.com/comentario/1100449/) 

	Ahora es:
	``` 
	    npm i @hapi/vision
	    
	```

* **Fernando Cordero** (1) [917675](https://platzi.com/comentario/917675/) 

	<https://www.npmjs.com/package/@hapi/vision>  
	nuevo enlace en npm

* **DiegoTinitana** (1) [479299](https://platzi.com/comentario/479299/) 

	La variable ‘content’ en donde la define para que se renderize

* **Kevin Josué Calderón Peraza** (0) [426718](https://platzi.com/comentario/426718/) 

	En layout.hbs, como es que es {{{content}}} “conecta” por asi decirlo con index.hbs?

	* **Jecsham Castillo** [426718] (3)

		Eso es porque se definió como layout en la configuración. Cada vez que se renderice una view, tomará el layout como plantilla, y reemplazará {{{content}}} con la vista que toque.

## 0080. Recibiendo parámetros en una ruta POST - Creación del registro [14002](https://platzi.com/clases/1376-hapi-js/14002-recibiendo-parametros-en-una-ruta-post-creacion-de/)

### Descripción:


El objeto **request** nos permite obtener datos de la petición recibida desde el cliente. El método pasado como parámetro para la creación de este objeto define si trabajaremos con GET o POST.

Proipiedades del **request** :

* request.path
* request.method
* request.get
* request.payload: es en esta propiedad donde recibimos los datos enviados con el método POST.



Ciclo de vida del objeto **request** , se refiere a los eventos que suceden durante la carga, existencia y descarga del objeto:

* OnRequest
* OnPreAuth
* OnCredentials
* OnPostAuth
* OnPreHandler
* OnPostHandler
* OnPreResponse



Más información sobre el ciclo de vida del objeto **request** en el repositorio oficial del proyecto: [Link](https://github.com/hapijs/hapi/blob/master/API.md#request-lifecycle)

Código: Definimos rutas GET y POST para registrar usuarios y recibir  
parámetros en el request.

### Comentarios:

* **Alejandro González Reyes** (3) [747719](https://platzi.com/comentario/747719/) 

	Mi aporte en el código
	``` 
	    'use strict'
	    
	    // Requerir el modulo de hapi (Framework)
	    const Hapi = require('@hapi/hapi')
	    // Requerir el plugin de hapi para servir archivos estaticos
	    const inert = require('@hapi/inert')
	    // Requerir el plugin de hapi para gestionar el motor de plantillas
	    const vision = require('@hapi/vision')
	    const path = require('path')
	    
	    // Configurar el servidor de nuestra aplicación. En un contenedor (Docker) si marca error colocar 0.0.0.0 (todos)
	    const server = Hapi.server({
	      port: process.env.PORT || 3000,
	      host: 'localhost',
	      // Definir propiedades generales para todas las rutas. (En este caso indico que las rutas que requieran archivos estáticos, se servirán desde la carpeta public)
	      routes: {
	        files: {
	          relativeTo: path.join(__dirname, 'public')
	        }
	      }
	    
	    })
	    
	    // Definicion de función para inicializar el proyecto. Intenamnete hay tareas asincronas
	    asyncfunctioninit() {
	    
	      try {
	        // Registrar los plugins que hapi va a necesitar (en este caso servir archivos estaticos)
	        await server.register(inert)
	        // Registrar plugin para gestionar el motor de plantillas
	        await server.register(vision)
	    
	        // Configurar nuestro motor de plantillas. Usará handlebars y cuando invoquemos una vista automáticamente buscará una con extensión hbs (no hace falta especificarlo). Debe buscar a partir del directorio actual, las vistas se encuentran en views y se activa compatibilidad con layouts, los cuales se encuentran en layouts
	        server.views({
	          engines: {
	            hbs: require('handlebars')
	          },
	          relativeTo: __dirname,
	          path: 'views',
	          layout: true,
	          layoutPath: 'layouts'
	        })
	    
	        // Definición de rutas (indicar el método HTTP, URL y controlador de ruta)
	        // Se declaran después del plugin ya que las rutas hacen uso del misom para devolver archivos estáticos
	        server.route({
	          method: 'GET',
	          path: '/',
	          handler: (req, h) => {
	            // El plugin de vision inyecta el metodo view al objeto h para renderizar una vista con el motor de plantillas configurado en la aplicación
	            return h.view('index', {
	              title: 'Home'
	            })
	          }
	        })
	    
	        /**
	       * Rutas para el registro de usuarios
	       * 
	       * el objeto request permite recuperar los datos de la petición. 
	       * sus propiedades son path, method, 
	       * params, query, get, payload (PUT/POST)
	       * 
	       * El objeto request tiene un ciclo de vida en HapiJS
	       * https://github.com/hapijs/hapi/blob/master/API.md#request-lifecycle
	         */
	        server.route({
	          method: 'GET',
	          path: '/register',
	          handler: (req, h) => {
	            return h.view('register')
	          }
	        })
	    
	        server.route({
	          method: 'POST',
	          path: '/create-user',
	          handler: (req, h) => {
	            // Mostrar en consola el cuerpo de la petición
	            console.log(req.payload)
	            return'Usuario creado satisfactoriamente'
	          }
	        })
	    
	        // Ruta para servir archivos estáticos asociados (img/css/js)
	        server.route({
	          method: 'GET',
	          path: '/{param*}',
	          handler: {
	            directory: {
	              path: '.',
	              redirectToSlash: true
	            }
	          }
	        })
	    
	        // Arrancar el servidor de Hapi
	        await server.start()
	        console.log(`Servidor lanzado en: ${server.info.uri}`)
	      } catch (error) {
	        console.error(error)
	        // Salir de nodeJS con un código de error (1), 0 es un código de exito
	        process.exit(1)
	      }
	    }
	    
	    // Inicializar el proyecto
	    init();
	    
	```

* **csgarciavel** (2) [525112](https://platzi.com/comentario/525112/) 

	porque el campo de correo exige que los datos ingresados contengan arroba , ¿en que parte del codigo se encuentra esto ?

	* **Angel Hernandez** [525112] (1)

		Hola 😄 estas validaciones son realizadas debido al tipo de input que estas usando, como el correo tiene el tipo “email” y el atributo “required”, en navegador realiza la validación y a través de css tu puedes agregar estilos personalizados para que tu formulario destaque un campo inválido .

	* **Diego Alexander Forero Higuera (Platzi)** [525112] (3)

		como lo menciona @angel998 son las validaciones propias del navegador por usar un input con el type email, pero como buena práctica debes validar siempre también en el servidor.

	* **Juan David Castro (Platzi)** [525112] (1)

		Shi. El navegador hace una validación “automática”. Pero también puedes hacerlo a mano 😮 : <https://www.w3schools.com/js/js_validation.asp>.

* **silvermiguel96** (1) [413035](https://platzi.com/comentario/413035/) 

	Que interesante la simplicidad en su desarrollo.

* **Alejandro González Reyes** (1) [68881](https://platzi.com/comentario/747707/) 
Alguno de ustedes sabe como indicar a nodemon que inspeccione cambios en otros archivos, por ejemplo plantillas, ya que solamente inspecc...

	* **Juan David Castro (Platzi)** [68881] (1)

		Mira esta sección de la documentación: <https://github.com/remy/nodemon/blob/master/README.md#running-non-node-scripts>.
		``` 
		    nodemon --exec "python -v" ./app.py
		    
		```

* **csgarciavel** (1) [54043](https://platzi.com/comentario/525112/) 
porque el campo de correo exige que los datos ingresados contengan arroba , ¿en que parte del codigo se encuentra esto ?

	* **Angel Hernandez** [54043] (1)

		Hola 😄 estas validaciones son realizadas debido al tipo de input que estas usando, como el correo tiene el tipo “email” y el atributo “required”, en navegador realiza la validación y a través de css tu puedes agregar estilos personalizados para que tu formulario destaque un campo inválido .

## 0090. Definir una mejor estructura con buenas prácticas en Hapi [14003](https://platzi.com/clases/1376-hapi-js/14003-definir-una-mejor-estructura-con-buenas-practicas-/)

### Descripción:


Con el fin de tener una mejor organización de los archivos de nuestro proyecto, y considerando que estamos trabajando con la arquitectura _MVC_ , haremos una primera refactorización del código.

Creamos el directorio `/controllers` para colocar los _controladores site y user_ de nuestro proyecto. Pasamos la definición de las rutas a su propio módulo `routes.js` como un arreglo que exportaremos más adelante. Distribuímos los _handlers_ asociados a cada _vista_ en la definición de las _rutas_ hacia el archivo del _controlador_ para cada contexto, ya sea _site_ o _user_. Requerimos los controladores desde el módulo de rutas, y fnalmente importamos la definición de rutas desde el `index.js` y las asociamos al _server_ con `server.route(routes)`.

La raíz de la estructura general quedaría de momento:  
-/public  
-/controllers  
-/views  
-routers.js  
-index.js

### Comentarios:

* **Alexander  Silvera** (6) [395257](https://platzi.com/comentario/395257/) 

	Una consulta el module.exports no va al final del archivo??

	* **Juan David Castro (Platzi)** [395257] (4)

		No necesariamente, depende de tus gustos 😄…
		
		En mi caso me gusta tenerlos tan arriba como pueda 😎

	* **edsadr** [395257] (3)

		Gracias al hoisting de JavaScript puedes ponerlo donde quieras

	* **Felipe Acosta** [395257] (1)

		Jejeje en mi caso me gusta mas tenerlo abajo, al igual que exportar las clases

	* **Jecsham Castillo** [395257] (1)

		Realmente depende del modo en que quieras exportar el módulo.

* **Alexander  Silvera** (3) [43252](https://platzi.com/comentario/395257/) 
Una consulta el module.exports no va al final del archivo??

	* **Juan David Castro (Platzi)** [43252] (4)

		No necesariamente, depende de tus gustos 😄…
		
		En mi caso me gusta tenerlos tan arriba como pueda 😎

* **Alejandro González Reyes** (2) [747840](https://platzi.com/comentario/747840/) 

	Mi aporte en el código  
	Archivo index.js
	``` 
	    'use strict'
	    
	    // Requerir el modulo de hapi (Framework)
	    const Hapi = require('@hapi/hapi')
	    // Requerir el plugin de hapi para servir archivos estaticos
	    const inert = require('@hapi/inert')
	    // Requerir el plugin de hapi para gestionar el motor de plantillas
	    const vision = require('@hapi/vision')
	    const path = require('path')
	    
	    // Requerir archivo de rutas
	    const routes = require('./router')
	    
	    // Configurar el servidor de nuestra aplicación. En un contenedor (Docker) si marca error colocar 0.0.0.0 (todos)
	    const server = Hapi.server({
	      port: process.env.PORT || 3000,
	      host: 'localhost',
	      // Definir propiedades generales para todas las rutas. (En este caso indico que las rutas que requieran archivos estáticos, se servirán desde la carpeta public)
	      routes: {
	        files: {
	          relativeTo: path.join(__dirname, 'public')
	        }
	      }
	    
	    })
	    
	    // Definicion de función para inicializar el proyecto. Intenamnete hay tareas asincronas
	    asyncfunctioninit() {
	    
	      try {
	        // Registrar plugins de hapi para servir archivos estaticos
	        await server.register(inert)
	        // Registrar plugin para gestionar el motor de plantillas
	        await server.register(vision)
	    
	        // Configurar nuestro motor de plantillas.
	        server.views({
	          engines: {
	            hbs: require('handlebars')
	          },
	          relativeTo: __dirname,
	          path: 'views',
	          layout: true,
	          layoutPath: 'layouts'
	        })
	    
	        // Registrar archivo de rutas en la aplicación
	        server.route(routes)
	        // Arrancar el servidor de Hapi
	        await server.start()
	        console.log(`Servidor lanzado en: ${server.info.uri}`)
	      } catch (error) {
	        console.error(error)
	        // Salir de nodeJS con un código de error (1), 0 es un código de exito
	        process.exit(1)
	      }
	    }
	    
	    // Inicializar el proyecto
	    init();
	    
	```
	
	Archivo router.js
	``` 
	    // Requerir modulos de controlador de ruta
	    const siteController = require('./controllers/site')
	    const userController = require('./controllers/user')
	    
	    // Declarar conjunto de rutas y asociar su respectivo controlador de ruta
	    const routes = [
	      {
	        method: 'GET',
	        path: '/',
	        handler: siteController.index
	      },
	      {
	        method: 'GET',
	        path: '/register',
	        handler: userController.register
	      },
	      {
	        method: 'POST',
	        path: '/create-user',
	        handler: userController.createUser
	      },
	      {
	        // Ruta para servir archivos estáticos asociados (img/css/js)
	        method: 'GET',
	        path: '/{param*}',
	        handler: {
	          directory: {
	            path: '.',
	            redirectToSlash: true
	          }
	        }
	      }
	    ];
	    
	    module.exports = routes
	    
	```
	
	Archivo userController.js
	``` 
	    // Definición de controladores de ruta
	    
	    functionregister(req, h) {
	      return h.view('register')
	    }
	    
	    functioncreateUser(req, h) {
	      console.log(req.payload)
	      return'Usuario creado satisfactoriamente'
	    }
	    
	    module.exports = {
	      register,
	      createUser
	    }
	    
	```
	
	Archivo siteController.js
	``` 
	    // Definición de controlaadores de ruta
	    
	    functionindex(req, h) {
	      return h.view('index', {
	        title: 'Home'
	      })
	    }
	    
	    module.exports = {
	      index
	    }
	    
	```

	* **Juan José Vega Quintero** [747840] (1)

		Puedes compartir el github del proyecto  
		Está muy bien documentado para estudiarlo

* **Fernando Cordero** (1) [919494](https://platzi.com/comentario/919494/) 

	```
	    'use strict'
	    
	    // Requerir el modulo de hapi (Framework)
	    const Hapi = require('@hapi/hapi')
	    const handlerbars = require('handlebars') // para implementacion de plantillas
	    const inert = require('inert') // extiende los metodos disponible en el objeto h
	    const vision = require('@hapi/vision') //para implementar el uso de vistas. Hay que configurarlo por ser un plugin
	    const path = require('path') // nos permite definir una ubicación relativa para todos los routes de nuestro proyecto
	    const routes = require('./routes')
	    
	    // Configurar el servidor de nuestra aplicación. En un contenedor (Docker) si marca error colocar 0.0.0.0 (todos)
	    const server = Hapi.server({
	        port: process.env.PORT || 3000,
	        host: 'localhost',
	        //definir desde donde va acceder a las rutas. relaviteTo (routes.files)
	        routes: {
	            files: {
	                relativeTo: path.join(__dirname, 'public')
	            }
	        } 
	    })
	    
	    // Definicion de función para inicializar el proyecto. Internamente hay tareas asincronas
	    asyncfunctioninit() {
	    
	      // Arrancar el servidor de HapiJS, se considera una tarea asincrona.
	        try {
	            // registrando inert
	            await server.register(inert)
	            //registrando vision
	            await server.register(vision)
	            //configuracion de vision
	            server.views({
	                engines: {  //hapi puede usar diferentes engines
	                    hbs: handlerbars //asociamos el plugin al tipo de archivo
	                },
	                relativeTo: __dirname, //para que las vistas las busque fuera de /public
	                path: 'views', //directorio done colocaremos las vistas dento de nuestro proyecto
	                layout: true, //indica que usaremos layouts
	                layoutPath: 'views'//ubicacion de layouts
	            })
	            server.route(routes)
	            await server.start()
	        } catch (error) {
	            console.error(error)
	        // Salir de nodeJS con un código de error (1), 0 es un código de exito
	            process.exit(1)
	        }
	    
	        console.log(`Servidor lanzado en: ${server.info.uri}`)
	    }
	    
	    // Inicializar el proyecto
	    init();
	    
	```

## 0100. Validando la información - Implementando Joi [14004](https://platzi.com/clases/1376-hapi-js/14004-validando-la-informacion-implementando-joi/)

### Descripción:


La validación de los datos suministrados por el usuario puede hacerse tanto en el _frontend_ como en el _backend_ , incluso puede hacerse en ambos lados, lo cual se recomienda.

Para hacer la validación de información en el _backend_ , Hapi cuenta con un módulo llamado **Joi** que ofrece múltiples condiciones de validación, como: tipo de dato, mínimos y máximos, condiciones personalizadas, etc.

**Joi** nos permite generar validación de un esquema específico en Hapi en el mismo momento en que se definen las _rutas_.

Luego de instalar y requerir el módulo en el arhivo _routes.js_ será necesario agregar la propiedad _options_ que contiene a su vez _validate_ y luego _payload_ , en esta caso porque los datos serán recibidos por POST, allí definimos entonces las condiciones de validación para cada dato esperado.

### Links:

* [joi  -  npm](https://www.npmjs.com/package/joi)

### Comentarios:

* **Alejandro González Reyes** (5) [747895](https://platzi.com/comentario/747895/) 

	Mi aporte en el código  
	Al día de hoy es importante instalar hapi, sus módulos y plugins desde
	``` 
	    npm i @hapi/hapi @hapi/inert @hapi/joi @hapi/vision
	    
	```
	
	Por otra parte, es posible que en la versión de hapi 18.4 y joi 16.1.4 no funcione la validación tal como lo explica el profesor. Dejo un ejemplo completo actualizado hasta Septiembre 2019
	``` 
	    // Requerir módulo para validación de datos en el backend
	    const Joi = require('@hapi/joi')
	    
	    // Requerir modulos de controlador de ruta
	    const siteController = require('./controllers/site')
	    const userController = require('./controllers/user')
	    
	    // Declarar conjunto de rutas y asociar su respectivo controlador de ruta
	    const routes = [
	      {
	        method: 'GET',
	        path: '/',
	        handler: siteController.index
	      },
	      {
	        method: 'GET',
	        path: '/register',
	        handler: userController.register
	      },
	      {
	        // Los datos enviados a esta ruta deben cumplir con cierto esquema de validación. Ṕara ello se agrega dentro de sus opciones la validación del payload (body request)
	        // Cada esquema define los criterios que debe cumplir un campo para pasar la validación 
	        method: 'POST',
	        path: '/create-user',
	        handler: userController.createUser,
	        options: {
	          validate: {
	            payload: Joi.object({
	              email: Joi.string().email().required(),
	              name: Joi.string().required().min(3),
	              password: Joi.string().required().min(6)
	            })
	          }
	        }
	      },
	      {
	        // Ruta para servir archivos estáticos asociados (img/css/js)
	        method: 'GET',
	        path: '/{param*}',
	        handler: {
	          directory: {
	            path: '.',
	            redirectToSlash: true
	          }
	        }
	      }
	    ];
	    
	    module.exports = routes
	    
	```

	* **GerAlfonso** [747895] (1)

		Al instalar @hapi/joi@^16.xx se debe envolver el esquema con Joi.object():
		``` 
		    options: {
		          validate: {
		            payload: Joi.object({
		              name: Joi.string().required().min(3),
		              email: Joi.string().email().required(),
		              password: Joi.string().required().min(6)
		            })
		          }
		        }
		    
		```

* **rubenchanamesanchez** (2) [1082139](https://platzi.com/comentario/1082139/) 

	Si les aparece un error como el siguiente:
	``` 
	    Error: Cannot set uncompiled validationruleswithout configuring a validator
	    
	```
	
	Deben de definir el payload como un Joi.Object
	``` 
	    options: {
	          validate: {
	            payload: Joi.object({
	              name: Joi.string()
	                .required()
	                .min(3),
	              email: Joi.string()
	                .email()
	                .required(),
	              password: Joi.string()
	                .required()
	                .min(6)
	            })
	          }
	        },
	    
	```

* **hnino** (2) [595212](https://platzi.com/comentario/595212/) 

	<https://www.npmjs.com/package/joi> ya fue deprecado, para el curso si funciona, pero para hacer una aplicación ya deberían de usar el actualizado. Ahora esta en <https://github.com/hapijs/joi>

* **Alejandro Jaramillo Merino** (2) [410828](https://platzi.com/comentario/410828/) 

	Buenas tardes, que plugin utilizan en el browser para que la respuesta se muestre en una forma grafica amigable??
	
	En mi browser se presenta asi… ** _{“statusCode”:400,“error”:“Bad Request”,“message”:“Invalid request payload input”}_

	* **Javier Molinas** [410828] (2)

		Hola, la que yo utilizo se llama JSON Formatter, es una extension de chrome <https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en>

	* **edsadr** [410828] (2)

		Hola, sigue avanzando en el curso, luego resolvemos eso para verlo de una forma amigable

* **Fernando Azuaje** (1) [661759](https://platzi.com/comentario/661759/) 

	instalen
	``` 
	    npm i @hapi/joi
	    
	```
	
	ya que el paquete que usan en el surso ya fue deprecado

* **Bjota** (1) [570458](https://platzi.com/comentario/570458/) 

	npm i joi -S

* **Alejandro Jaramillo Merino** (1) [44693](https://platzi.com/comentario/410828/) 
Buenas tardes, que plugin utilizan en el browser para que la respuesta se muestre en una forma grafica amigable?? En mi browser se presen...

	* **Javier Molinas** [44693] (2)

		Hola, la que yo utilizo se llama JSON Formatter, es una extension de chrome <https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en>

## 0110. Introducción a Firebase [14005](https://platzi.com/clases/1376-hapi-js/14005-introduccion-a-firebase/)

### Descripción:


Ya teniendo validada la información que recibimos del usuario, el siguiente paso es almacenarla para su posterior recuperación. Para esto haremos uso del servicio de base de datos de **Firebase / Storage** con una configuración básica.

El proceso de creación y configuración de la base de datos se hace a través del sitio web <https://firebase.google.com> mediante la consola de administración, accediendo con una cuenta Google y creando un proyecto nuevo. En la sección de Configuración / Cuentas de Servicio, generamos las credenciales de acceso para NodeJS en formato json, que usaremos en nuestro proyecto, en la siguiente clase.

### Links:

* [Firebase](http://firebase.google.com/)

### Comentarios:

## 0120. Creando un modelo y guardando en firebase [14015](https://platzi.com/clases/1376-hapi-js/14015-creando-un-modelo-y-guardando-en-firebase/)

### Descripción:


Para implementar el uso de la base de datos de Firebase en nuestro proyecto, crearemos el directorio `/config` para guardar el archivo _json_ con las credenciales de acceso al servicio, y el directorio `/models` con los modelos asociados a las diferentes entidades que requiere nuestra aplicación. Instalamos desde la terminal el módulo `firebase-admin` con npm. Requerimos el módulo en el index.js del directorio `/models` e invocamos el método `firebase.initializeApp()`

### Links:

* [firebase-admin  -  npm](https://www.npmjs.com/package/firebase-admin)

### Comentarios:

* **Alejandro González Reyes** (6) [748048](https://platzi.com/comentario/748048/) 

	Mi aporte en el código Septiembre 2019
	
	Archivo de conexión a la base de datos
	``` 
	    'use strict'
	    
	    // Información de configuración proporcionada en 
	    // NombreProyectoFirebase -> configuración del proyecto -> cuentas del servicio
	    
	    const firebase = require('firebase-admin')
	    const serviceAccount = require('../config/firebase.json')
	    
	    firebase.initializeApp({
	      credential: firebase.credential.cert(serviceAccount),
	      databaseURL: "https://mxplatzi-overflow.firebaseio.com"
	    })
	    
	    // Crear una instancia (referencia) de la base de datos
	    const db = firebase.database()
	    
	    // Importar modulos (CLASES) correspondientes a los modelos de la base de datos
	    const User = require('./users')
	    
	    // Recordar que los modelos esperan como parámetro una referencia hacia la base de datos.
	    // Exportamos las instancias de los modelos listas para ser invocadas en los controladores correspondientes
	    module.exports = {
	      user: new User(db)
	    }
	    
	```
	
	Archivo de modelo User
	``` 
	    'use strict'
	    
	    const bcrypt = require('bcrypt')
	    
	    /**
	   * Clase compatible con Firebase Data Base
	     */
	    
	    classUser{
	      // La clase recibe una referencia hacia la base de datos de firebase donde se guardará la información
	      constructor(db) {
	        this.db = db
	        this.ref = this.db.ref('/')
	        this.collection = this.ref.child('users')
	      }
	    
	      // Método de clase para guardar un usuario en la base de datos de firebase
	      async create(data) {
	        console.log(data)
	        // Destructuro el objeto con el payload enviado. Ya que Hapi lo decora con un prototipo null que no es compatible con Firebase
	        const user = {
	          ...data
	        }
	        // Se genera una contraseña encriptada a partir de la proporcionada. this.constructor llama a la clase, ya que el método encrypt es estático
	        user.password = awaitthis.constructor.encrypt(user.password)
	        const newUser = this.collection.push(user)
	        // Retornamos el id del usuario
	        return newUser.key
	      }
	    
	      // Método estático asincrono para la encriptacion de contraseñas
	      staticasync encrypt(password) {
	        const saltRounds = 10
	        const hashedPassword = await bcrypt.hash(password, saltRounds)
	        return hashedPassword
	      }
	    }
	    
	    module.exports = User
	    
	```
	
	Archivo de controlador User
	``` 
	    'use strict'
	    
	    // Definición de controladores de ruta
	    
	    // Importar el archivo de conexión a la base de datos
	    const { user } = require('../models/index')
	    
	    functionregister(req, h) {
	      return h.view('register')
	    }
	    
	    /**
	   * Controlador encargado de registrar un usuario en la base de datos.
	   * La base de datos se encuentra en un servicio desentralizado (Firebase) que retonra una promesa.
	     */
	    asyncfunctioncreateUser(req, h) {
	      try {
	        const createUserId = await user.create(req.payload)
	        return h.response(`Usuario registrado satisfactoriamente con el ID ${createUserId}`).code(201)
	      } catch (error) {
	        console.error(error)
	        return h.response('Problemas al registrar el usuario').code(500)
	      }
	    }
	    
	    module.exports = {
	      register,
	      createUser
	    }
	    
	```
	
	El problema de obj.hasOwnProperty se debe a que el objeto de payload tiene una decoración de prototipo null.
	``` 
	    [Object: null prototype] {
	      name: 'Fernanda Villar Becerril',
	      email: 'fer.nanda@outlook.com',
	      password: 'secreto' }
	    
	```
	
	Esto se soluciona de muchas formas, la mas sencilla es destructurando el objeto.

* **Juan David Castro (Platzi)** (5) [395348](https://platzi.com/comentario/395348/) 

	La clase esta genial! Qué emocionante ya tener forma de registrar usuarios de verdad de verdad 😄 🎉

* **jorgeisaacvasquezsanchez** (2) [613403](https://platzi.com/comentario/613403/) 

	PARA PODER INSTALAR BCRYPT EN WINDOWS 10 TUVE QUE EJECUTAR LOS SIGUIENTES PASOS
	
	  1. Instalar las dependencias de node-gyp, así:  
	Abrimis una consola de comandos normal o de PowerShell con privilegios de Administrador.
	
	
	``` 
	    npm install --global --production windows-build-tools
	    
	```
	
	Esto Instalará todas las herramientas y configuraciones requeridas
	
	  1. Instalar el paquete de node-gyp, de forma global, con el siguiente comando:
	
	
	``` 
	    $ npm install -g node-gyp
	    
	```
	
	  1. Instalar el paquete de bcrypt, como dependencia del proyecto, con el siguiente comando:
	
	
	``` 
	    npm install bcrypt -S
	    
	```

* **jorgeisaacvasquezsanchez** (2) [613330](https://platzi.com/comentario/613330/) 

	¿Cómo hizo el profesor para detener la instalación de firebase-admin, cuando se le olvidó poner -S el final del comando de instalación de npm? ¿Lo hizo con el equivalente a Ctrl + C en Windows?

	* **Juan David Castro (Platzi)** [613330] (1)

		Sip. **`Ctrl + C`**. Si quieres recontraprofundizar puedes tomar el [Curso de Introducción a Terminal y Línea de Comandos](https://platzi.com/terminal). 😬

* **DESTRUN** (2) [467106](https://platzi.com/comentario/467106/) 

	Solucion para instalar bcrypt en Windows
	
	<https://stackoverflow.com/a/40046466/9053821>

* **Navarrock33** (2) [398295](https://platzi.com/comentario/398295/) 

	Tengo problemas al instalar bcrypt, estoy en win 10 x64 y me dice que la plataforma no está soportada

	* **Navarrock33** [398295] (3)

		Solucionado, me faltaba una dependencia llamada node-gyp en [node-gyp](https://github.com/nodejs/node-gyp) explican que hay que correr
		``` 
		    npm install --global --production windows-build-tools
		    
		```
		
		en consola como admin para poder instalarla

	* **Navarrock33** [398295] (1)

		También tuve que copiar manualmente un archivo bcrypt_lib.node al path que me pedia, un circo de 40 min. 😕

* **Alexander  Silvera** (2) [395283](https://platzi.com/comentario/395283/) 

	Hay un problema en los videos de este curso, cada vez que comienza un video nuevo el sonido esta en distintas frecuencias; es decir algunos estan más alto que otros.

	* **Felipe Acosta** [395283] (1)

		Es verdad algunos, suenan mas duro que otros

	* **gorydev** [395283] (1)

		es cierto algunos videos el audio se escucha más bajo y en general el curso tiene un audio bajo =(

* **Fernando Cordero** (1) [926317](https://platzi.com/comentario/926317/) 

	Para los usuarios de Windows deben instalar primero python [https://www.python.org/downloads/](url)  
	Luego correr el siguiente comando en PowerShell como administrador:
	``` 
	    npm install --global --production windows-build-tools
	    
	```
	
	Reinicien Win, y luego ejecuten en la terminal:  
	`npm i bcrypt -S`

* **landony04** (1) [677953](https://platzi.com/comentario/677953/) 

	con la version 8.6 de Firebase da problema “obj.hasOwnProperty is not a function”, tal vez podrian explicar el por que para poder utilizar las librerias en su ultima version, me toco utilizar la que tienen declarada en el packege.json del curso.

	* **grupolah** [677953] (5)

		El mismo problema tenia, hice este arreglo y lo pude solucionar, con la ultma version de firebase-admin, como que cuando usas **bcrypt** agregar un dato no valido por firebase, por eso decidi mejor hacerlo manual.
		``` 
		    async create(data) {
		        ....
		        let newUser = this.collection.push();
		        newUser.set({
		          email: data.email,
		          name : data.name,
		          password: data.password
		        });
		        ....
		      }
		    
		```
		
		**Pdt:Se que puede haber otra forma, pero por motivos practicos lo deje asi.**

* **Fernando Azuaje** (1) [662278](https://platzi.com/comentario/662278/) 

	para el momento en el que realizo el curso hay un problema con la ultima version de firebase-admin (8.2) y no funcionan los metodos que se ven en la creacion de la clase, o al menos a mi no me sirvio y tuve que usar la version que usan en el curso

* **DESTRUN** (1) [467207](https://platzi.com/comentario/467207/) 

	me da este error al tratar de ejecutar npm run dev finalizando el video
	
	@firebase/database: FIREBASE WARNING: {“code”:“app/invalid-credential”,“message”:“Credential implementation provided to initializeApp() via the “credential” property failed to fetch a valid Google OAuth2 access token with the following error: “Failed to parse access token response: Error: Server responded with status 400.”.”}

	* **Diego Alexander Forero Higuera (Platzi)** [467207] (2)

		Es un error al intentar conectar con el servicio de autenticación, puedes compartir el stack trace completo del error.

	* **DESTRUN** [467207] (1)

		Solamente suelta ese log cada 2 segundos

	* **Diego Alexander Forero Higuera (Platzi)** [467207] (1)

		Revisa que no tengas algún error de digitación, si puedes compartir tu código de preferencia via github probablemente te podamos ayudar mejor.

	* **Luis Paredes** [467207] (1)

		tengo el mismo error

	* **Luis Paredes** [467207] (1)

		Tenia el mismo error y simple y facil es la solucion, acomoda la hora de tu pc. ahi esta el error!

* **eddyarellanes** (1) [464301](https://platzi.com/comentario/464301/) 

	Si alguien más usa Windows y tuvo problemas usando bcrypt por x o y razón, en el repo recomiendan utilizar mejor bcryptjs.  
	“Optimized bcrypt in JavaScript with zero dependencies. Compatible to the C++ bcrypt binding on node.js and also working in the browser.”
	
	Las líneas utilzadas en el curso se pueden cambiar por estas:
	``` 
	    staticasyncencrypt(password){
	        const salt = 10    
	        const hashedPassword = await bcrypt.hash( password, salt)
	        return hashedPassword
	      
	        return hashedPassword
	      }
	    
	```
	
	Bye x)

	* **eddyarellanes** [464301] (1)

		<https://www.npmjs.com/package/bcryptjs>

	* **JUAN SILVA** [464301] (1)

		Sinceramente la mejor solución es no programar en Windows, la mayoria de herramientas estan diseñadas para funcionar sin problemas en Ubuntu o MacOs. Deja de matarte la cabeza y pasate a Ubuntu.

* **Enzo Aliatis** (1) [395372](https://platzi.com/comentario/395372/) 

	Finísimo el curso hasta aquí!🎉

* **JUAN SILVA** (1) [65480](https://platzi.com/comentario/692330/) 
Por que cuando usamos la ultima versión de firebase admin y la actualización de modulos joi, innert, hapi, y vision a @hapi/ innert @hapi...

	* **gorydev** [65480] (1)

		porque si te pones a ver tiene sentido, en el payload lo que estás recibiendo es un objeto con los datos del usuario por eso Joi lo que validará será un objeto:
		``` 
		    payload: Joi.object({
		         name: Joi.string().required().min(2),
		         email: Joi.string().required().min(5),
		         password: Joi.string().required().min(6),
		    })
		    
		```

* **DESTRUN** (1) [49425](https://platzi.com/comentario/467207/) 
me da este error al tratar de ejecutar npm run dev finalizando el video @firebase/database: FIREBASE WARNING: {“code”:“app/invalid-creden...

	* **Diego Alexander Forero Higuera (Platzi)** [49425] (2)

		Es un error al intentar conectar con el servicio de autenticación, puedes compartir el stack trace completo del error.

* **Alexander  Silvera** (1) [43255](https://platzi.com/comentario/395283/) 
Hay un problema en los videos de este curso, cada vez que comienza un video nuevo el sonido esta en distintas frecuencias; es decir algun...

	* **Felipe Acosta** [43255] (1)

		Es verdad algunos, suenan mas duro que otros

## 0130. Implementando el login y validación del usuario [14016](https://platzi.com/clases/1376-hapi-js/14016-implementando-el-login-y-validacion-del-usuario/)

### Descripción:


Teniendo el modelo de Usuario ya definido, podemos pasar a la implementación del Login, para lo cual creamos una nueva vista y agregaremos un método en el controlador, además de las rutas correspondientes para el login y la validación de usuarios.

Al hacer un _query_ sobre los registros almacenados en Firebase, el resultado devuelto es un objeto JSON con los resultados, en los que las keys de cada elemento corresponden con los IDs de cada usuario. Aún cuando el resultado devuelto es sólo un registro, la estructura es la misma.

Es importante tener en cuenta que al recuperar los datos desde Firebase, la contraseña viene cifrada, por lo que la validación debe hacerse comparando ambos datos con _bcrypt_.

### Comentarios:

* **Alejandro González Reyes** (4) [748625](https://platzi.com/comentario/748625/) 

	Mi aporte en el código
	
	modelo User
	``` 
	    // Metodo de clase para recuperar a un usuario si las credenciales de acceso son correctas
	      asyncvalidateUser(data) {
	        // Ordenar la colección por email, consultar el usuario por su email (no me interesa escuchar cambios en la data, por ello once)
	        const queryUser = awaitthis.collection.orderByChild("email").equalTo(data.email).once("value")
	        // Obtengo el objeto con los resultados de mi consulta {objId: {}, objId: {}, objId: {}}
	        const userFound = queryUser.val()
	        if (userFound) {
	          // Obtengo un arreglo con los ids de los documentos que forman parte de los resultados de mi busqueda. Me interesa quedarme con el elemento (ObjectId) del primer documento, mas no con el arreglo
	          const userId = Object.keys(userFound)[0]
	          // comparar si las contraseñas son correctas {documentoResultado.objectId.password}
	          const passwordRight = await bcrypt.compare(data.password, userFound[userId].password)
	    
	          return (passwordRight) ? userFound[userId] : false;
	        }
	        returnfalse
	      }
	    
	```
	
	Controladores para el login y validación de usuarios
	``` 
	    /**
	   * Controladores encargados de mostrar la vista de login (formulario)
	   * Procesar la data del usuario para verificar que sus credenciales de acceso sean las correctas
	   * Leer en la base de datos (Firebase)
	     */
	    functionlogin(req, h) {
	      return h.view('login', { title: 'Login' })
	    }
	    
	    asyncfunctionvalidateUser(req, h) {
	      try {
	        const userLogin = await user.validateUser(req.payload)
	        return userLogin
	      } catch (error) {
	        console.error(error)
	        return h.response('Problemas al logear el usuario').code(500)
	      }
	    }
	    
	```
	
	Rutas
	``` 
	    /**
	   * Controladores encargados de mostrar la vista de login (formulario)
	   * Procesar la data del usuario para verificar que sus credenciales de acceso sean las correctas
	   * Leer en la base de datos (Firebase)
	     */
	    functionlogin(req, h) {
	      return h.view('login', { title: 'Login' })
	    }
	    
	    asyncfunctionvalidateUser(req, h) {
	      try {
	        const userLogin = await user.validateUser(req.payload)
	        return userLogin
	      } catch (error) {
	        console.error(error)
	        return h.response('Problemas al logear el usuario').code(500)
	      }
	    }```
	    
	```

* **Fernando Cordero** (2) [926644](https://platzi.com/comentario/926644/) 

	@firebase/database: FIREBASE WARNING: Using an unspecified index. Your data will be downloaded and filtered  
	on the client. Consider adding “.indexOn”: “email” at /users to your security rules for better performance.
	
	Seria bueno revisar esto

	* **jbarriospd** [926644] (1)

		Apoyo al compañero!

	* **albertodsosa** [926644] (2)

		Solución:  
		Vete a tu dashboard de firebase al apartado database y la pestaña rules y escriban esto…
		``` 
		    {
		      /* Visit https://firebase.google.com/docs/database/security to learn more about security rules. */
		      "rules": {
		        "users": {
		            ".indexOn": "email"      
		        },
		        ".read": false,
		        ".write": false
		      }
		    }
		    
		```
		
		fuente: [Indexa tus datos](https://firebase.google.com/docs/database/security/indexing-data?authuser=0#defining_data_indexes)

* **Mateo Santiago Zapata Maldonado** (1) [548305](https://platzi.com/comentario/548305/) 

	Hubiese sido increible, si todo fuera solo un api Rest con Postman o algo parecido…

* **DESTRUN** (1) [470597](https://platzi.com/comentario/470597/) 

	todo funcionando hasta ahora

* **Alejandro González Reyes** (1) [68934](https://platzi.com/comentario/748623/) 
Mi duda Porque se hace uso del ordenamiento de datos. orderByChild durante la consulta de recuperación de información. Así como el método...

	* **gorydev** [68934] (1)

		se ordena los resultados que sea más rápido al buscar el ‘email’ del usuario luego el método ‘once’ quiere decir que una vez se obtenga algún valor lo va a devolver

## 0140. Autenticación de usuarios - Cookies y estado [14017](https://platzi.com/clases/1376-hapi-js/14017-autenticacion-de-usuarios-cookies-y-estado/)

### Descripción:


"Hay diferentes maneras de mantener el estado de autenticación de un usuario en un sistema. Para este proyecto usaremos la forma más sencilla que es a través de una _cookie_ y usando el _state_ de Hapi.

Con la función `server.state( '<nombre de la cookie>', { <opciones> } )` definimos las características de la _ cookie_ que usaremos en la ruta definida para hacer la validación. Luego asignaremos los datos propios de la autenticación a esta _cookie_ en el controlador, en la misma instrucción en la que hacemos el _redirect_ al Home, luego de validado el usuario.

Habiendo guardado el estado de la autenticación, podemos definir entonces diferentes opciones en el _Layout_ que nos permitan por ejemplo, hacer _Logout_ y mostrar la información del usuario, entre otras cosas.

### Links:

* [17.6.0 API Reference](https://hapijs.com/api#-serveroptionsstate)

### Comentarios:

* **jesus gutierrez gonzalez** (4) [494211](https://platzi.com/comentario/494211/) 

	si no se guarda la cookie es porque falta el path
	
	server.state(‘user’, {  
	ttl: 1000 * 60 * 60 * 24 * 7,  
	isSecure: process.env.NODE_ENV === ‘prod’,  
	encoding: ‘base64json’,  
	path: ‘/’  
	})

* **Alejandro González Reyes** (2) [748703](https://platzi.com/comentario/748703/) 

	Mi aporte en el código
	``` 
	    // Configurar el servidor para el envio de cookies (nombreCookie, opciones)
	        // https://hapi.dev/tutorials/cookies/?lang=en_US
	        // tiempo de vida de la cookie (en milisegundos)
	        // localhost no es seguro
	        // codificación de la cookie
	        server.state('user', {
	          ttl: 1000 * 60 * 60 * 24 * 7,
	          isSecure: process.env.NODE_ENV === 'prod',
	          encoding: 'base64json',
	        })
	    
	```
	
	En el controlador
	``` 
	    asyncfunctionvalidateUser(req, h) {
	      try {
	        const userLogin = await user.validateUser(req.payload)
	        if (!userLogin) {
	          return h.response('Email y/o Contraseña incorrectas').code(401)
	        }
	        // En aplicaciones Web, las cookies se usan a menudo para mentener el estado de un usuario entre solicitudes http
	    
	        // Se redirecciona al usuario y se le envía la cookie llamada user configurara previamente en la aplicacion (nombreCookie, data)
	        return h.redirect('/').state('user', {
	          name: userLogin
	    
	    
	```
	
	function index(req, h) {  
	return h.view(‘index’, {  
	title: ‘Home’,  
	user: req.state.user // El valor de esta variable de ruta se obteniene del estado actual de la aplicación (accede a la cookie user) para mostrar o no ciertos controles en la vista  
	})  
	}```  
	.name,  
	email: userLogin.email,  
	})  
	} catch (error) {  
	console.error(error)  
	return h.response(‘Problemas al logear el usuario’).code(500)  
	}  
	}
	``` 
	    Enviar variables a la vistas
	    
	    
	    
	    
	```
	
	function index(req, h) {  
	return h.view(‘index’, {  
	title: ‘Home’,  
	user: req.state.user // El valor de esta variable de ruta se obteniene del estado actual de la aplicación (accede a la cookie user) para mostrar o no ciertos controles en la vista  
	})  
	}
	``` 
	    y enla vista
	    
	    
	    
	    
	```
	
	{{! Si hay usuario, es porque hay estado, es decir, hay cookie activa (logeado) }}  
	{{#if user}}  
	<div class=“col m-2 text-right”>  
	<h6><span class=“badge badge-info”>{{[user.name](http://user.name)}}</span></h6>  
	<a href="/" class=“btn btn-primary btn-lg border border-white” role=“button” aria-pressed=“true”>Preguntar</a>  
	<a href="/logout" class=“btn btn-primary btn-lg border border-white ml-2” role=“button” aria-pressed=“true”>Salir</a>  
	</div>  
	{{else}}  
	<div class=“col m-2 text-right”>  
	<a href="/login" class=“btn btn-primary btn-lg border border-white” role=“button” aria-pressed=“true”>Login</a>  
	<a href="/register" class=“btn btn-primary btn-lg border border-white ml-2” role=“button” aria-pressed=“true”>Registrarse</a>  
	</div>  
	{{/if}}
	```
	```
	

* **Juan Carlos García Esquivel** (1) [1100498](https://platzi.com/comentario/1100498/) 

	Según recuerdo las cookies sirven para poder compartir información entre peticiones (request) por esta razón cuando se guarda una cookie esta se envía en todas las peticiones, por eso la pasamos a la vista desde el request 😎

* **Fernando Cordero** (1) [926982](https://platzi.com/comentario/926982/) 

	[https://hapi.dev/api/?v=19.0.4#server.state()](url)

## 0150. Manejando errores [14018](https://platzi.com/clases/1376-hapi-js/14018-manejando-errores/)

### Descripción:


Para el manejo general de errores con Hapi usamos la instrucción `process.on( '<tipo de error>', ( <error> ) => { <callback> } )` en el script principal. En el _callback_ de la función, **error** devuelve un objeto con los detalles del error capturado. Los tipos de errores que vamos a manejar en el proyecto son: `unhandledRejection` y `unhandledException`. Estos dos tipos de errores son los más comunes y los que se aconseja manejar como mínimo en cualquier aplicación.

Luego definimos el método `failActions` en las rutas en las que haremos las validaciones. Este método hará referencia a su vez al método del controlador en el cual se procesará el manejo de los errores.

Para mostrar los mensajes de error en la aplicación de una manera más amigable y controlada, usaremos el módulo _boom_ , que está integrado en el core de Hapi.

### Links:

* [boom  -  npm](https://www.npmjs.com/package/boom)

### Comentarios:

* **Fernando Azuaje** (3) [662638](https://platzi.com/comentario/662638/) 

	el modulo de boom esta deprecado, pueden usar @hapi/boom

* **Danniel Sequera** (3) [592241](https://platzi.com/comentario/592241/) 

	Me gustaría saber si como estoy escribiendo mis controladores son 100% equivalentes a la manera en que lo esta explicando el profesor.
	
	site.js
	``` 
	    'use strict'
	    
	    module.exports = {
	    	home: (request, h) => {
	    		return h.view('index', {
	    			title: 'Home',
	    			user: request.state.user
	    		});
	    	},
	    	register: function(request, h) {
	    		return h.view('register', {
	    			title: 'Register',
	    			user: request.state.user
	    		});
	    	},
	    	login: function(request, h) {
	    		return h.view('login', {
	    			title: 'Login',
	    			user: request.state.user
	    		});
	    	},
	    	logout: function(request, h) {
	    		return h.redirect('/login').unstate('user');
	    	}
	    };
	    
	```
	
	user.js
	``` 
	    'use strict'
	    
	    constBoom = require('boom');
	    const { users } = require('../models/index');
	    
	    module.exports = {
	    	createUser: async function(request, h) {
	    		letresult = null;
	    
	    		try {
	    			result = await users.create(request.payload);
	    		} catch (error) {
	    			console.error(error);
	    			return h.response('Problemas creando el usuario!').code(500);
	    		}
	    
	    		return h.response(`Usuario creado, ID: ${result}`);
	    	},
	    	validateUser: async function(request, h) {
	    		letresult = null;
	    
	    		try {
	    			result = await users.validate(request.payload);
	    
	    			if(!result) {
	    				return h.response('Email y/o contraseña incorrecta').code(401);
	    			}
	    		} catch (error) {
	    			console.error(error);
	    			return h.response('Problemas validando el usuario!').code(500);
	    		}
	    
	    		return h.redirect('/').state('user', {
	    			name: result.name,
	    			email: result.email
	    		});
	    	},
	    	failValidation: function(request, h, error) {
	    		Boom.badRequest('Falló la validación', request.payload);
	    	}
	    };
	    
	```

	* **Alejandro González Reyes** [592241] (1)

		es exactamente lo mismo. En lo personal me gustan las cosas limpias. Por ello el crea las funciones con nombre antes y después al exportar hace referencia a ellas.

* **Alejandro González Reyes** (2) [748736](https://platzi.com/comentario/748736/) 

	Interesante este artículo acerca de manejar los errores no controlados  
	<https://medium.com/dailyjs/how-to-prevent-your-node-js-process-from-crashing-5d40247b8ab2>

* **jorgeisaacvasquezsanchez** (2) [629231](https://platzi.com/comentario/629231/) 

	¿Que beneficios trae usar los bloques {{#with variable}} en vez del tradicional {{#if variable}}?

	* **Juan David Castro (Platzi)** [629231] (1)

		Usando **`#with`** entras directamente a las propiedades:
		``` 
		    // {
		    //  title: "My first post!",
		    //  author: {
		    //    firstName: "Charles",
		    //    lastName: "Jolley"
		    //  }
		    // }
		    
		    <divclass="entry">
		      <h1>{{title}}</h1>
		    
		      {{#with author}}
		      <h2>By {{firstName}} {{lastName}}</h2>
		      {{/with}}
		    </div>
		    
		```
		
		Referencia: <https://handlebarsjs.com/builtin_helpers.html>.

* **Danniel Sequera** (1) [59512](https://platzi.com/comentario/592241/) 
Me gustaría saber si como estoy escribiendo mis controladores son 100% equivalentes a la manera en que lo esta explicando el profesor. si...

	* **Alejandro González Reyes** [59512] (1)

		es exactamente lo mismo. En lo personal me gustan las cosas limpias. Por ello el crea las funciones con nombre antes y después al exportar hace referencia a ellas.

## 0160. Visualización de errores [14019](https://platzi.com/clases/1376-hapi-js/14019-visualizacion-de-errores/)

### Descripción:


Hasta ahora hemos estado mostrando un texto básico con los detalles de cada error capturado, pero en lo que se refiere a la apariencia, esta no es la forma más amigable de hacerlo ya que no le estamos dando mayor feedback al usuario sobre lo que ha pasado con su operación y lo estamos dejando en una calle sin salida.

Lo que haremos en esta clase será utilizar una vista a la que pasaremos la información del error y la mostraremos de una manera que sea visualmente más amigable para los usuarios. Para esto, sustituiremos los llamados a `h.response( '<mensaje>' ).code( <código-error> )` por `h.view( '<ruta>', { <variables> } )`

Para la visualización del `error 404`, incorporamos un nuevo layout, con su respectiva vista `404.hbs` y definimos una nueva ruta para los llamados a urls que no estén definidas en nuestra aplicación con `/{any*}`. Esta ruta se coloca al final de las definiciones para que solo se tome en cuenta si ninguna de las rutas anteriores se corresponde con el _request_. Al hacer el llamado a la vista en el controlador del sitio, debemos recordar indicar en el tercer argumento de la función view, el objeto con la propiedad _layout_ para indicar el nuevo _layou_ que mostrará el error.

### Comentarios:

* **DESTRUN** (3) [470678](https://platzi.com/comentario/470678/) 

	404.hbs
	``` 
	    <divclass="container">
	      <divclass="row justify-content-center mt-5">
	        <divclass="col-md-12 text-center">
	          <span class="display-1 d-block">404</span>
	          <divclass="mb-4 lead">La página que buscas no existe.</div>
	          <a href="/"class="btn btn-link">Vuelve al Home</a>
	        </div>
	      </div>
	    </div>
	    
	```

* **Alejandro González Reyes** (2) [749196](https://platzi.com/comentario/749196/) 

	Es importante agregar el prefijo assets/ a los scripts declarados en el layout de error
	``` 
	      <!-- Optional JavaScript -->
	      <!-- jQuery first, then Popper.js, then Bootstrap JS -->
	      <scriptsrc="./assets/error_files/jquery-3.2.1.slim.min.js"
	        integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
	        crossorigin="anonymous"></script>
	      <scriptsrc="./assets/error_files/popper.min.js"
	        integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
	        crossorigin="anonymous"></script>
	      <scriptsrc="./assets/error_files/bootstrap.min.js"
	        integrity="sha384-a5N7Y/aK3qNeh15eJKGWxsqtnX/wWdSZSKp+81YjTmS15nvnvxKHuzaWwXHDli+4"
	        crossorigin="anonymous"></script>
	    
	```

* **jorgeisaacvasquezsanchez** (1) [629238](https://platzi.com/comentario/629238/) 

	¿Que beneficios trae usar los bloques `{{#with variable}}` en vez del tradicional `{{#if variable}}` ?

	* **Juan David Castro (Platzi)** [629238] (1)

		Te respondí en la pregunta de la clase anterior 😉: <https://platzi.com/comentario/629231/>.

* **Alberto González** (1) [78896](https://platzi.com/comentario/929436/) 
¡Hola! ¿Porqué es necesario agregar: ‘/assets’ en el archivo routes.js, en el método ‘GET’?

	* **Erik Ochoa (Platzi)** [78896] (1)

		Porque al dejarlo como `/` se mezcla con las llamadas a páginas invalidas que deben regresar un 404. Por eso agrupamos los **assets** o recursos (imágenes, fuentes, estilos, etc.) que necesita el sitio en ese directorio, bajo ese path.

* **nikosantis** (1) [74036](https://platzi.com/comentario/845399/) 
Me ha estado apareciendo este mensaje: [2019-12-01T20:49:30.454Z] @firebase/database: FIREBASE WARNING: Using an unspecified index. Your...

## 0170. Controlar el error 404 en inert y el error de validación [14020](https://platzi.com/clases/1376-hapi-js/14020-controlar-el-error-404-en-inert-y-el-error-de-vali/)

### Descripción:


El error 404 que ya estamos controlando es el que está relacionado con las rutas de nuestra aplicación, sin embargo, falta controlar la visualización de este mismo tipo de error para los archivos estáticos que usamos en nuestra interfaz y que estamos cargando con _inert_. Para esto haremos una nueva función en el controlador del sitio para el manejo de _not found_ de los archivos estáticos.

Básicamente lo que haremos será interceptar el error de _boom_ devuelto por _inert_ con `response.isBoom` y analizar si su código es 404 para redireccionar entonces a la vista apropiada. Para poder hacer la intercepción del error y alterar el _life cycle_ del request, es necesario indicar la siguiente instrucción `server.ext( 'onPreResponse', handler )` antes de la definición de las rutas en el _script_ principal.

Cuando interceptamos el _life cycle_ de un _request_ , debemos hacer un `.takeover()` para forzar la finalización del ciclo, y esto lo hacemos luego del `code(n)` en el llamado a la vista.

### Comentarios:

* **Alejandro González Reyes** (3) [752490](https://platzi.com/comentario/752490/) 

	Responder con el verdadero mensaje del error
	``` 
	    // Controlador de errores de validación para los usuarios (amigable)
	    functionfailValidation(req, h, error) {
	      console.error(error)
	      // Un objeto de las rutas y sus respectivas vistas
	      const templates = {
	        '/create-user': 'register',
	        '/validate-user': 'login'
	      }
	      // retorno la vista con base a la ruta donde se originó el error de validación
	      // es importante detener la propagación del error en este punto y responder (takeover)
	      return h.view(templates[req.path], {
	        title: 'Error de validación',
	        error: error.output.payload.message
	      }).code(400).takeover()
	      // return Boom.badRequest('Falló la validación', req.payload)
	    }
	    
	```

* **henrytabimagiraldo** (3) [398003](https://platzi.com/comentario/398003/) 

	creo que me hizo falta un gráfico o algo así cuando explicó el ciclo de vida del request (es más creo que debería haber un video que se dedique a explicar exclusivamente el ciclo)

	* **edsadr** [398003] (7)

		la verdad habia un slide que no pusieron pero la explicación esta más atras en esta clase <https://platzi.com/clases/hapi-js/concepto/creando-un-sitio-basico-con-hapi/recibiendo-parametros-en-una-ruta-post-creacion-de/material/>![imagen](https://cldup.com/8NguAux2YH-2000x2000.png)

* **Alejandro González Reyes** (1) [69175](https://platzi.com/comentario/752543/) 
Como puedo cambiar el idioma de los mensajes de error con Hapi/Joi

	* **Juan David Castro (Platzi)** [69175] (2)

		👉 <https://github.com/hapijs/joi/issues/598>

* **Alejandro González Reyes** (1) [68978](https://platzi.com/comentario/749317/) 
¿Como se haría para mostrar el nombre del campo que origina el error, así como su descripción?

	* **Juan David Castro (Platzi)** [68978] (1)

		¡Hola! Qué bueno que lo resolviste de la manera que explicas en este comentario: <http://platzi.com/comentario/752490/>.
		
		Había que usar el parámetro de error en la función **`failValidation`** para obtener el mensaje del campo que originaba el error ( **`error.output.payload.message`** ).
		
		Más referencias:
		
		👉 <https://medium.com/@csakis/hapi-joi-error-handling-with-custom-messages-1f544e2b1489>

## 0180. Repaso - Creación del modelo y controlador para preguntas [14021](https://platzi.com/clases/1376-hapi-js/14021-repaso-creacion-del-modelo-y-controlador-para-preg/)

### Descripción:


En esta clase tomaremos la sección de preguntas de nuestro proyecto para hacer un repaso de lo aprendido hasta ahora.

* A partir del _html_ , tomamos el contenido del tag


``` 
      <main>
        ...
      </main>
    
```

y lo extraemos a un archivo de _handlebars_ en la carpeta `/vistas`

* Creamos el modelo de preguntas  
`questions.js` en la carpeta `/models`


``` 
    class MiModelo {
      constructor ( db ) {
        this.db = db
        this.ref = this.db.ref('/')
        this.collection = this.ref.child('entidad')
      }
      async miMetodo( args ) {
        // --- instrucciones
      return key
      }
    }
    module.exports = MiModelo
    
```

* En el `index.js` de la carpeta `/models`, importamos cada archivo de modelo luego de la declaración de la base de datos de Firebase, y los exportamos con _new_ para que no haya duplicados.

* Creamos el archivo de controlador en la carpeta `/controllers` con la función que va a retornar la vista, e importamos el modelo creado a través del index. Al finalizar, exportamos la función.




### Comentarios:

* **henrytabimagiraldo** (4) [398015](https://platzi.com/comentario/398015/) 

	normalmente dentro de las convenciones del mvc no es al revés? (modelos en singular y controladores en plural)

	* **Felipe Acosta** [398015] (4)

		Es verdad yo tambien note esto, por eso en mi ejercicio estoy creando los modelos en singular

	* **jesusmurf** [398015] (5)

		Si, es algo en lo que también me fije. Creo que el profesor lo hizo así por despiste. Esos detalles tampoco son lo importante del curso 😃

* **Fernando Cordero** (2) [952922](https://platzi.com/comentario/952922/) 

	Mientras tanto en vez de responder con `return h.response(`Pregunta creada con el ID ${result}`)` , pueden redireccionar al home
	``` 
	    return h.redirect('/')```
	    
	    
	```

## 0190. Repaso - Creación de las rutas para crear preguntas [14022](https://platzi.com/clases/1376-hapi-js/14022-repaso-creacion-de-las-rutas-para-crear-preguntas/)

### Descripción:


Hasta ahora hemos repasado cómo definir el modelo y crear la función en el controlador para el manejo de preguntas de nuestro proyecto. En esta clase vamos a difinir las rutas y enlazarlas con las vista para que todo trabaje en conjunto.

* En el _action_ del formulario que definimos en la vista con _handlebars_ indicamos la ruta a la cual se va a dirigir el navegador al hacer clic en el botón en _Crear pregunta_.

* Incorporamos el condicional para el manejo de errores en el archivo de _handlebars_ de la vista.

* Agregamos la _url_ en el archivo _layout_ que enlazará a la ruta que definiremos a continuación para hacer las preguntas.

* Creamos la función necesaria en el controlador para hacer el llamado a la vista.

* Definimos las nuevas rutas: la de creación de la pregunta y la que recibirá los datos de formulario para crear nuevas preguntas, es acá donde definimos las validaciones que se aplicarán a los datos con Joi.

* Agregamos la ruta en la función de validación de _urls_.




### Comentarios:

* **Fernando Azuaje** (2) [663268](https://platzi.com/comentario/663268/) 

	Exelente curso hasta ahora

* **albertodsosa** (1) [1039573](https://platzi.com/comentario/1039573/) 

	Acordarse de deconstruir la data antes de setearla si no da error:
	``` 
	    async create(data, user) {
	            const ask = {
	                ...data
	            }
	    
	            ask.owner = user
	            const question = this.collection.push()
	            question.set(ask)
	    
	            return question.key
	        }
	    
	```

* **jbarriospd** (1) [1007672](https://platzi.com/comentario/1007672/) 

	Hola a todos, Me aparce un error 415, “message”: "Unsupported Media Type"  
	Alguna idea de que me puede estar pasando?, de antemano gracias

	* **albertodsosa** [1007672] (2)

		Quita la propiedad esta del formulario `enctype="multipart/form-data"`, es para envio de archivos esto.

## 0200. Listar las últimas preguntas en el home [14024](https://platzi.com/clases/1376-hapi-js/14024-listar-las-ultimas-preguntas-en-el-home0196/)

### Descripción:


Para listar las últimas preguntas creadas en la base de datos de Firebase, agregamos un nuevo método en el modelo de las preguntas y usamos la función
``` 
    this.collection.limitToLast( n ).once('value')
    
```

para obtener los **n** últimos registros al final de los datos.

Luego debemos incluir el llamado al método anterior desde el controlador que maneja las rutas en la aplicación. Y finalmente sustituimos el bloque que renderiza las preguntas en la plantilla del _home_ , `index.hbs`, por una nueva estructura de _handlebars_ llamada `{#each ... } ... {/each}`

### Comentarios:

# Aplicacion de conceptos avanzados [2594]

## 0210. Enrutamiento avanzado - visualizando una pregunta [14025](https://platzi.com/clases/1376-hapi-js/14025-enrutamiento-avanzado-visualizando-una-pregunta/)

### Descripción:


A través del enrutamiento avanzado de Hapi, recibiendo parámetros en el _request_ , podemos tener una vista específica para mostrar los detalles de cada pregunta. Partimos de un archivo _html_ y creamos un método en el modelo de preguntas que ya teníamos antes. Este método nos permitirá obtener el objeto con los detalles de la pregunta individual según su ID.

Al igual que en oportunidades anteriores, creamos una función en el controlador del sitio que maneje la ruta para la nueva vista. Creamos la plantilla con _handlebars_ trasladando el contenido del _tag_ main, desde la vista html original e incluimos las variables que recibimos desde el modelo.

Definimos una nueva ruta en el archivo `routes.js`, indicando en la propiedad **path** los parámetros que esperamos recibir desde el controlador, es aquí donde estamos utilizando el enrutamiento avanzado. Finalmente actualizamos los enlaces en el layout principal colocando en _href_ la nueva ruta creada con la variable _key_ que dispones en cada iteración del ciclo `each` para las preguntas recientes.

### Comentarios:

* **Felipe Acosta** (8) [399570](https://platzi.com/comentario/399570/) 

	Al exportar las funciones del controlador tambien se podria hacer asi:
	``` 
	    module.exports = {
	      home,
	      register,
	      login,
	      notFound,
	      fileNotFound,
	      ask,
	      viewQuestion
	    }
	    
	```

	* **Juan David Castro (Platzi)** [399570] (1)

		Así me gusta más 😛

	* **marcelobaez** [399570] (2)

		No recuerdo si es o no Syntax sugar, pero si es parte de ES6 / ES2015. Y creo que a todos nos gusta mas asi jaja

	* **Jecsham Castillo** [399570] (1)

		Sí se puede hacer así, aunque para las clases no está mal que se haga de la otra manera para no confundir a algunos que no sepan

	* **gorydev** [399570] (1)

		hay que destacar que se puede exportar así porque es el mismo nombre tanto en la llave como en el valor porque si son diferentes se debe colocar ambos

## 0220. Enrutamiento avanzado - respondiendo una pregunta [14026](https://platzi.com/clases/1376-hapi-js/14026-enrutamiento-avanzado-respondiendo-una-pregunta/)

### Descripción:


Para crear la funcionalidad de respuesta, creamos un método nuevo en el modelo de preguntas llamado `answer`. Este método nos permitirá insertar con _push_ el objeto con la respuesta individual para una pregunta que será almacenada en un arreglo _child_ llamado _answers_.

Luego definimos el método respectivo en el controlador de las preguntas y creamos la ruta que manejará el envío de las respuestas desde el formulario.

Es importante tener en cuenta que el ID de la pregunta que estamos respondiendo, corresponde a un _input_ de tipo _hidden_ en la vista, por lo que debemos asignar apropiadamente su valor a partir del _key_ recibido en la ruta.

Finalmente, actualizamos la vista de detalles de pregunta, recordando que las respuestas son un arreglo en la base de datos de Firebase, por lo que deberemos recorrerlo igualmente con la instrucción `{#each ... } ... {/each}` de _handlebars_.

Para el conteo de las respuestas crearemos un _helper_ personalizado de _handlebars_ y lo registraremos en el `index.js` con el método **.registerHelper( ‘ <nombre helper>’, <función helper> )**. Los _helpers_ son funciones de JavaScript que están disponibles globalmente en la aplicación para ser incluídas en cualquiera de las vistas.

### Comentarios:

* **Julio J Yépez** (4) [414576](https://platzi.com/comentario/414576/) 

	En el _helper_ del conteo, pudiéramos validar si el arreglo de respuestas viene en _null_ para devolver 0, y así no tendríamos que incluir el _tag_ #if en la plantilla.

	* **Julio J Yépez** [414576] (5)

		Por cierto en el _helper_ usamos Object.keys( answers ).length y no answers.length porque answers no es realmente un arreglo simple sino más bien una lista o colección, y ésta no dispone directamente de la propiedad length, por lo que hay que usar este artificio de crear un arreglo de llaves a partir de la colección y luego sí, acceder a la propiedad length de dicho arreglo.

	* **Jecsham Castillo** [414576] (2)

		Tienes razón

* **henrytabimagiraldo** (3) [398136](https://platzi.com/comentario/398136/) 

	no sería mejor crear un modelo para “answer” ?

	* **edsadr** [398136] (3)

		Tienes razón, pero por tiempo en el curso no es conveniente, seria otra clase adicional de solo repaso

* **Juan Carlos García Esquivel** (1) [1104687](https://platzi.com/comentario/1104687/) 

	Modifique un poco el código y quedo así:  
	index.js
	``` 
	    handlebars.registerHelper('answerNumber', (answers) => {
	      if (answers === undefined) {
	        return0;
	      }
	      const keys = Object.keys(answers);
	      return keys.length;
	    });
	    
	```
	
	index.hbs
	``` 
	    <h3>
	      {{answerNumber question.answers}}
	    </h3>
	    
	```

## 0230. Generando la lógica de la plantilla según si es creador o contribuidor [14027](https://platzi.com/clases/1376-hapi-js/14027-generando-la-logica-de-la-plantilla-segun-si-es-cr/)

### Descripción:


En esta clase agregaremos la funcionalidad de marcado de las respuestas como correctas, para esto nos apoyaremos en otro _helper_ de _handlebars_ por lo que haremos primero una refactorización creando un archivo que contenga todos los _helpers_ en una función que retornará el objeto _handlebars_ personalizado.

El tag `{#if}{/if}` de _handlebars_ no soporte comparar múltiples condiciones, por lo que tendremos que crear un helper de tipo _método de bloque_ , que tiene una estructura parecida a la siguiente:
``` 
    handlebars.registerHelper('nombreHelper', ( params..., options ) => {
    	if( <condición> ) {
    		// --- renderiza el contenido
    		return options.fn( this )
    	}
    	// --- no renderiza el contenido
    	return options.inverse( this )
    })
    
```

Un método de bloque es en esencia un _tag_ personalizado en _handlebars_ , de tipo bloque `{#miHelper} ... {/miHelper}`, similar a `{#if}{/if}`, `{#with}{/with}`, `{#each}{/each}`, etc.

### Comentarios:

* **henrytabimagiraldo** (2) [398167](https://platzi.com/comentario/398167/) 

	que interesante forma de usar el module.exports 😮

* **jesusmurf** (1) [408742](https://platzi.com/comentario/408742/) 

	Esas subidas de contexto me han resultado algo confusas, se sube de contexto respecto a que?

	* **edsadr** [408742] (5)

		se sube de contexto con respecto al bloque de Handlebars donde estes, si esta en un bloque anidado tienes que subir el contexto al que referencias el número de niveles que necesites para obtener el contexto del padre u otro ancestro

	* **jesusmurf** [408742] (1)

		Muchas gracias ahora lo entiendo 😃

	* **waldoaraque** [408742] (1)

		¿esto tendría que ver con el método del helper? Digo, como se definió el contexto **this** para definir las condiciones del **if** … No sé, si me explico.

* **jesusmurf** (1) [44517](https://platzi.com/comentario/408742/) 
Esas subidas de contexto me han resultado algo confusas, se sube de contexto respecto a que?

	* **edsadr** [44517] (5)

		se sube de contexto con respecto al bloque de Handlebars donde estes, si esta en un bloque anidado tienes que subir el contexto al que referencias el número de niveles que necesites para obtener el contexto del padre u otro ancestro

## 0240. Métodos de servidor - respuesta correcta [14028](https://platzi.com/clases/1376-hapi-js/14028-metodos-de-servidor-respuesta-correcta/)

### Descripción:


Los **métodos del servidor** en Hapi, son _métodos o funciones_ que pueden ser accedidos desde cualquier ruta de la aplicación de manera global.

Lo primero que haremos será crear el método estándar en el modelo. En nuestro caso, el modelo de las preguntas.

Luego creamos un archivo que contendrá los métodos del servidor y lo guardamos como `/lib/methods.js`. En este archivo requerimos el modelo donde hemos creado el método estándar y lo asociamos a un método propio, transladando todos los argumentos del método original.

Finalmente requerimos en el script principal de la aplicación el archivo con los métodos del servidor y registramos cada m[etodo en el _server_ con la instrucción `server.method( '<nombre del método>', methods.<metodo creado> )`, ya luego en el código podremos acceder a estos métodos a través del objeto _request_ de Hapi.

### Comentarios:

* **Julio J Yépez** (3) [414632](https://platzi.com/comentario/414632/) 

	¿Los métodos de servidor de HapiJS serían equivalentes a los Helpers de handlebars de tipo funciones?

	* **Jecsham Castillo** [414632] (1)

		Se podría decir 😀

	* **WilliamVelazquez** [414632] (1)

		Son similares pero lo que entendí es que los métodos de servidor se pueden acceder por medio del request 😃

## 0250. Usando métodos de servidor [14029](https://platzi.com/clases/1376-hapi-js/14029-usando-metodos-de-servidor/)

### Descripción:


Usar los métodos de servidor que creamos en la clase pasada es tan simple como acceder a `req.server.methods`:
``` 
    req.server.methods.<nombre método>( args )
    
```

Esto lo hacemos en el controlador y de allí continuamos el ciclo normal de las rutas como hemos visto hasta ahora.

### Comentarios:

* **henrytabimagiraldo** (4) [398257](https://platzi.com/comentario/398257/) 

	para evitar duplicar código validando si el usuario esta autentica use middlewares de la siguiente forma:
	
	  1. cree un archivo middleware.js en el directorio lib
	
	
	``` 
	    // lib/middlewares.js
	    'use strict'
	    
	    functionisAuth (req, h) {
	      if (!req.state.user) {
	        return h.redirect('/login').takeover()
	      }
	    
	      return h.continue
	    }
	    
	    module.exports = {
	      isAuth
	    }
	    
	```
	
	  1. Añadí el middleware a las rutas que solo se pueden acceder autenticado
	
	
	``` 
	    // routes.js
	    const middlewares = require('./lib/middlewares')
	    ...
	    module.exports = [
	      ...
	      {
	        method: '...',
	        path: '...',
	        handler: ... ,
	        options: {
	          pre: [
	            {method: middlewares.isAuth}
	          ]
	        }
	      },
	      ...
	    ]
	    
	```

	* **edsadr** [398257] (3)

		Más adelante en el curso veras otra forma de autenticar que sería mejor

* **Julio J Yépez** (2) [414664](https://platzi.com/comentario/414664/) 

	Algo que no me gusta mucho, y que estoy seguro hay maneras un poco más elegantes de resolver, es el uso constante del bloque `try / catch`.

	* **Juan Carrillo** [414664] (1)

		Es recomendable manejar los errores lo mas cerca posible de la línea de código o método que los produzca. Sin embargo podríamos dejar que se propaguen hasta un nivel superior y dejar que los reciba un handler de errores, creo que es la forma en que se hace con express seguro con hapi se puede manejar igual.

* **Fernando Cordero** (1) [953341](https://platzi.com/comentario/953341/) 

	[https://dev.to/gafi/7-reasons-to-always-use-async-await-over-plain-promises-tutorial-4ej9](url)

* **Alvaro   Gonzalez** (1) [399259](https://platzi.com/comentario/399259/) 

	Por que usas async y await ? eso no degrada la funcion …?  
	Que tan recomendado es usarlos…?

	* **edsadr** [399259] (4)

		hay muchas razones para usar aync/await en vez de promesas, te recomiendo este artículo para que lo entiendas mejor: <https://hackernoon.com/6-reasons-why-javascripts-async-await-blows-promises-away-tutorial-c7ec10518dd9>

	* **Fernando Cordero** [399259] (1)

		En programación no hay una cosa mejor que otra, sino más conveniente. En un entorno en el que tienes que hacer muchas tareas asíncronas, async/await no te permite hacerlas en paralelo, y las promesas si.
		
		Del mismo modo, hay casos donde ganan los callback, y hasta los eventos  
		Esto lo dijo @codingcarlos

## 0260. Manejo del caché -  Agregando el home al caché [14030](https://platzi.com/clases/1376-hapi-js/14030-manejo-del-cache-agregando-el-home-al-cache/)

### Descripción:


Internamente Hapi maneja el caché de las aplicaciones usando un módulo llamado **CatBox** que ya viene integrado en el _core_ del _framework_. Este módulo utiliza varios modos de _caching_ ; por defecto, Hapi implementa el _caché_ de memoria.

También es posible ampliar las funcionalidades del uso de _caché_ en nuestras aplicaciones instalando y configurando otros módulos disponibles como: Redis, MemCache, etc.

Para habilitar el uso de _caching_ **del lado del cliente** con Hapi basta con agregar la propiedad **options** en la definición de cada ruta y definir el tiempo de expiración con **expiresIn** y el tipo de privacidad con **privacy**.
``` 
    ...
    'options': {
      'expiresIn': <duracion>, // en milisegundos
      'privacy'  : <tipo privacidad>
    }
    ...
    
```

Nos apoyaremos en los métodos de servidor que aprendimos en clases anteriores para definir el uso de _caché_ en el _backend_ de nuestra aplicación, ya que Hapi permite hacer _caching_ del resultados de este tipo de métodos al momento de registrarlos en el script principal:
``` 
    server.method( '<nombre método>', methods.<metodo>, {
    'cache': {
      'expiresIn': <duracion>,
      'generateTimeout': <timeout>
    }
    
```

### Links:

* [catbox  -  npm](https://www.npmjs.com/package/catbox)

* [17.6.0 API Reference](https://hapijs.com/api#route.options.cache)

### Comentarios:

* **DESTRUN** (2) [471917](https://platzi.com/comentario/471917/) 

	Y esos ojitos?

* **Alejandro González Reyes** (1) [69244](https://platzi.com/comentario/753800/) 
No me queda claro la diferencia entre cache en el navegador y servidor.

	* **Juan David Castro (Platzi)** [69244] (1)

		👉 [Site Cache vs. Browser Cache vs. Server Cache: What’s the Difference?](https://wp-rocket.me/blog/different-types-of-caching/)  
		👉 [Show Me the Cache! Server Cache vs. Browser Cache](https://www.commonplaces.com/blog/show-me-the-cache-server-cache-vs-browser-cache)

## 0270. Procesamiento de archivos - Aceptando imágenes [14031](https://platzi.com/clases/1376-hapi-js/14031-procesamiento-de-archivos-aceptando-imagenes/)

### Descripción:


En esta clase aprenderemos el manejo de archivos con Hapi. Agregaremos la posibilidad de anexar imágenes a las preguntas. Para esto será necesario modificar el método _create_ del modelo _questions.js_ para que guarde en la base de datos de Firebase el nombre de archivo.

Será necesario también requerir algunos módulos adicionales, o algunas funciones desde esos módulos:
``` 
    const { writeFile } = require('fs')
    const { promisify } = require('util')
    const { join } = require('path')
    
```

Instalaremos y usaremos el módulo `uuid` en su versión `v1` para manejar nuestros propios nombres de archivo internamente y evitar la duplicidad.

En el controlador de las preguntas incorporamos la lógica del manejo de archivos cuando se ha identificado la presencia del dato _image_ en el _buffer_ del con
``` 
    Buffer.isBuffer( request.payload.image )
    
```

Este campo _image_ debemos incluirlo en el formulario, en la vista con el formulario de respuesta. Finalmente, al recibir el archivo a través del _buffer_ tendremos que escribirlo en el _filesystem_ del servidor, para lo cual usaremos la función _writeFile_ que hemos convertido en promesa y llamado `write( args )` con los argumentos correspondientes. Ya para mostrar la imagen en la vista cuando se haya recuperado, sólo bastará con incorporar la etiqueta `<img />` con la referencia al archivo almacenado.

### Comentarios:

* **henrytabimagiraldo** (2) [398434](https://platzi.com/comentario/398434/) 

	El modulo fs de node, en la versiones más recientes, soporta por defecto las promesas (es un feature en etapa experimental a la fecha 10/10/18). [ver documentación](https://nodejs.org/dist/latest-v10.x/docs/api/fs.html#fs_fs_promises_api)

	* **edsadr** [398434] (8)

		el curso esta hecho en Node 8, y definitivamente recomiendo no usar features experimentales y solo trabajar con la versión LTS más reciente

* **Juan Carlos García Esquivel** (1) [1105756](https://platzi.com/comentario/1105756/) 

	Mi ruta quedo de la siguiente manera:
	``` 
	    {
	        path: '/create-question',
	        method: 'POST',
	        options: {
	          payload: {
	            multipart: true,
	          },
	          validate: {
	            payload: Joi.object({
	              title: Joi.string().required(),
	              description: Joi.string().required(),
	              image: Joi.any().optional(),
	            }),
	            failAction: user.failValidation,
	          },
	        },
	        handler: question.createQuestion,
	      },
	    
	```

## 0280. Logging con Good - Monitoreando el servidor [14032](https://platzi.com/clases/1376-hapi-js/14032-logging-con-good-monitoreando-el-servidor/)

### Descripción:


El proceso de registrar los eventos que suceden internamente en nuestra aplicación, también conocido como _logging_ , es un aspecto técnico bastante habitual en entornos de producción de la vida real.

Hapi incluye un método `.log( args )` tanto en el objeto `server`, como en `request` y en `response` que nos permiten un registro muy básico de eventos; sin embargo, la práctica recomendada es hacer _logging_ con un módulo adicional llamado **Good** y una dependencia para el manejo de transporters llamada **good-console**.

Al igual que hemos hecho antes, una vez instalado el paquete de Good, será necesario requerirlo y registrarlo debidamente en el _script_ principal, pero en este caso lo haremos de una manera ligeramente diferente:
``` 
    ...
    await server.register({
      'plugin': good,
      'options': {
        'reporters': {
          'console': [
            {
              'module': 'good-console'
            },
            'stdout' // --- salida estándard
          ]
        }
      }
    })
    ...
    
```

Luego de configurado el paquete, la implementación es tan simple como ejecutar la misma instrucción `server.log( '<etiqueta o tag>', <mensaje> )`, donde `<mensaje>` puede ser una cadena de texto o un objeto. Recuerda que el método log también está disponible en los objetos `request` y `response`.

### Links:

* [good  -  npm](https://www.npmjs.com/package/good)

* [good-console  -  npm](https://www.npmjs.com/package/good-console)

### Comentarios:

* **gorydev** (3) [809182](https://platzi.com/comentario/809182/) 

	Dado que los modulos ‘good’ y ‘good-console’ están deprecados se debe utilizar los modulos `@hapi/good` y `@hapi/good-console` y para utilizarlos se haría de la siguiente manera:
	``` 
	    await server.register({
	          plugin: require('@hapi/good'),
	          options: {
	            ops: {
	              interval: 2000,
	            },
	            reporters: {
	              myConsoleReporters: [
	                {
	                  module: require('@hapi/good-console'),
	                },
	                'stdout',
	              ],
	            },
	          },
	        });
	    
	```
	
	lo demás se utiliza igual `server.log('TAG', 'Mensaje')`

* **jesusmurf** (2) [409252](https://platzi.com/comentario/409252/) 

	Por que no es tan recomendable hapi-pino?

* **jesusmurf** (1) [44558](https://platzi.com/comentario/409252/) 
Por que no es tan recomendable hapi-pino?

## 0290. Creación de plugins - Teoría [14033](https://platzi.com/clases/1376-hapi-js/14033-creacion-de-plugins-teoria/)

### Descripción:


Habiendo completado toda la funcionalidad básica de nuestra aplicación, podemos pensar en extender algunas de estas funcionalidades para que otros desarrolladores puedan tener acceso desde sitios externos e integrarse con nuestro proyecto. Por lo general la solución más conveniente es ofrecer una _API REST_ a través de un **plugin** personalizado.

En Hapi, un **plugin** es un Objeto que tiene básicamente la siguiente estructura:
``` 
    const plugin = {
      'name'    : 'miPlugin', // --- requerido
      'version' : '1.0.0', // --- opcional
      'register': function (server, options) {
        ...
      }
    }
    
```

* En `server` se indica la referencia de cuál servidor se la añadirán las responsabilidades asociadas a este _plugin_.

* En `opciones` se pueden colocar parámetros externos como credenciales, condiciones especiales, entre otras.




### Comentarios:

* **DESTRUN** (3) [471940](https://platzi.com/comentario/471940/) 

	Me gusta si has hecho todo bien hasta acá

## 0300. Creación de plugins - Implementando un API REST [14034](https://platzi.com/clases/1376-hapi-js/14034-creacion-de-plugins-implementando-un-api-rest/)

### Descripción:


Partiremos de la estructura que vimos en la clase anterior para desarrollar nuestra API REST.

En el método `register` del _plugin_ definiremos tanto las rutas necesarias para acceder a nuestra API, como el _handler_ que hace las veces de método del controlador para cada ruta. Además, en lugar de preparar y devolver una vista, devolveremos simplemente la salida por defecto de Hapi que es de formato _JSON_.

Luego de tener definidas todas las rutas, los _handlers_ con los parámetros esperados, las validaciones con Joi y las salidas de posibles errores con Boom, estamos listos para requerir y registrar nuestro _plugin_ en el _script_ principal de nuestra aplicación.

Adicionalmente, modificaremos la función `fileNotFound(...)` en el controlador de sitio para evitar que los errores `404` de nuestra API, se visualicen a través de la vista y en cambio lo hagan con _JSON_ que es la salida por defecto.

### Comentarios:

* **gorydev** (3) [809251](https://platzi.com/comentario/809251/) 

	para quienes les de error en la validación con joi deben agruparlo en un objeto de la siguiente manera:
	``` 
	    options: {
	        validate: {
	            params: joi.object({
	                amount: joi.number().integer().min(1).max(20)
	                  .required(),
	            }),
	            failAction: failValidation,
	        },
	    },
	    
	```
	
	de igual forma para la otra ruta del api

## 0310. Estrategías de autenticación -  Asegurando el API REST [14035](https://platzi.com/clases/1376-hapi-js/14035-estrategias-de-autenticacion-asegurando-el-api-res/)

### Descripción:


Con el objeto de restringir el acceso a nuestra API para que solo los usuarios registrados en nuestra base de datos puedan hacer usa de ella, implementaremos una estrategia de autenticación básica de Hapi, para lo cual será necesario instalar un módulo adicional llamado `hapi-auth-basic`.

Una vez instalado, requerido y registrado el módulo `hapi-auth-basic` en el _script_ de nuestro _plugin_ de API REST, debemos implementarlo de la siguiente manera:
``` 
    server.auth.strategy('simple', 'basic', { 'validate': validateAuth })
    
```

Donde `simple` es el nombre de la estrategia de autenticación, `basic` es el tipo (asociado al módulo que instalamos) y `validateAuth` es el método en el que definiremos la lógica de validación de los usuarios. Este último de forma muy similar a como lo hicimos antes en el método _validate_ del modelo `users` en nuestra aplicación.

De esta manera, cuando se intente acceder a cualquiera de las rutas definidas para nuestra API REST, el navegador solicitará los datos de autenticación `usuario` y `password` y solo devolverá resultados útiles cuando las credenciales obtenidas de la autenticación sean válidas.

### Links:

* [hapi-auth-basic  -  npm](https://www.npmjs.com/package/hapi-auth-basic)

* [17.6.0 API Reference](https://hapijs.com/api#server.auth.strategy())

### Comentarios:

* **nikosantis** (3) [849130](https://platzi.com/comentario/849130/) 

	No funciona así de “simple” con el @hapi/basic, ya que no valida bien, puedes poner cualquier cosa y valida, porque se equivocó en usar la función de validar de users, que no era validate sino validateUser. Así lo hice:
	
	No es necesario require el basic.
	
	Registrar basic  
	`await server.register(require('@hapi/basic'))`
	
	Usamos la estrategia:
	
	`server.auth.strategy('simple', 'basic', { validate }) server.auth.default('simple')`
	
	Llamamos arriba los modelos de users.  
	`const users = require('../models/index').users`
	
	y finalmente la función validate.
	
	`async function validate (req, username, password, h) {  
	let user
	``` 
	      try {
	        user = await users.validateUser({
	          email: username,
	          password: password
	        })
	      } catch (error) {
	        server.log('error', error)
	      }
	    
	      return {
	        credentials: user || {},
	        isValid: (user !== false)
	      }
	    }`
	    
	```

* **Fernando Cordero** (1) [962623](https://platzi.com/comentario/962623/) 

	exactamente como dijo @nikosantis

* **gorydev** (1) [809282](https://platzi.com/comentario/809282/) 

	el módulo de autenticación `hapi-auth-basic` está deprecado se debe usar `@hapi/basic` y se implementa de la siguiente forma:
	``` 
	    await server.register(require('@hapi/basic'));
	    server.auth.strategy('simple', 'basic', { validate: validateAuth });
	    
	```
	
	la función `validateAuth` queda igual que en la clase

* **Diego Ivan Padilla Bernal** (1) [608014](https://platzi.com/comentario/608014/) 

	al final en el modelo users se implementó el método **validateUser** y no **validate** así que aunque ingresará datos erróneos ingresaría sin problema.

## 0320. Seguridad básica - Asegurando el servidor contra CSRF [14036](https://platzi.com/clases/1376-hapi-js/14036-seguridad-basica-asegurando-el-servidor-contra-csr/)

### Descripción:


Una de las vulnerabilidades más comunes en cualquier servidor o sitio web, es la Falsificación de Petición en Sitios Cruzados o **CSRF** por sus sigles del inglés Cross-site request forgery, que es un tipo de ataque en el que son transmitidos comandos no autorizados por un usuario del sitio web en el que deberíamos confiar.

Para atender y corregir esta vulnerabilidad incorporaremos a nuestro proyecto un módulo adicional de Hapi llamado **crumb** que utiliza un _token_ de validación para cada una de las rutas accedidas por los usuarios.

**Implementación**

Una vez instalado con `npm i crumb -S` procedemos a registrarlo en el scrip principal, de la misma manera que hemos hecho antes con _good_.
``` 
    const crumb = require('crumb')
    ...
    
    await server.register({
      'plugin': crumb, 
      'options': {
        'cookieOptions': {
          'isSecure': process.env.NODE_ENV === 'prod'
        }
      }
    })
    ...
    
```

**Crumb** utiliza una cookie para realizar la validación del _token_ en cada una de las rutas de nuestra aplicación y la contrasta con el valor de un _input_ de tipo _hidden_ y de nombre **crumb** , que debe estar presente en cada una de las vistas.

La propiedad `isSecure` estaría entonces activa (en _true_ ) cuando estemos en el entorno de producción e inactiva (en _false_ ) mientras estemos en el entorno de desarrollo. Cuando no está presente el _input_ de validación o su valor no es el correcto, el servidor devuelve un código de error `403` al browser, indicando que el acceso está prohibido o no está autorizado.

### Links:

* [crumb  -  npm](https://www.npmjs.com/package/crumb)

* [blankie  -  npm](https://www.npmjs.com/package/blankie)

* [Curso de Análisis de Vulnerabilidades Web con OWASP](https://platzi.com/cursos/seguridad/)

### Comentarios:

* **vsotoanon** (2) [43926](https://platzi.com/comentario/402480/) 
Buenas tardes, me gustaría saber si me pueden recomendar algún PlugIn para integrar la Autenticacion con ActiveDirectory, estuve viendo n...

	* **edsadr** [43926] (1)

		la verdad no encuentro un módulo decente que te ayude en eso, aunque Auth0 tienen una solución, mira este post: <https://auth0.com/authenticate/hapi/active-directory/> … por otro lado el módulo que dices tiene 3 años de publicado, habria que ver en que estado esta, igual si no encuentras otra opción puedes integrar ese módulo a hapi con una función de autenticación como se hace en la clase de API REST

* **vsotoanon** (1) [402480](https://platzi.com/comentario/402480/) 

	Buenas tardes, me gustaría saber si me pueden recomendar algún PlugIn para integrar la Autenticacion con ActiveDirectory, estuve viendo node-activedirectory, pero me gustaria ver algo mas apegadao a hapi para seguir el orden de este proyecto.
	
	<https://github.com/gheeres/node-activedirectory>

	* **edsadr** [402480] (1)

		la verdad no encuentro un módulo decente que te ayude en eso, aunque Auth0 tienen una solución, mira este post: <https://auth0.com/authenticate/hapi/active-directory/> … por otro lado el módulo que dices tiene 3 años de publicado, habria que ver en que estado esta, igual si no encuentras otra opción puedes integrar ese módulo a hapi con una función de autenticación como se hace en la clase de API REST

	* **Mauricio Serna Flórez** [402480] (1)

		La librería de ADAL de Microsoft te puede ayudar, <https://github.com/AzureAD/azure-activedirectory-library-for-nodejs> está bien documentada y decentemente mantenida.

## 0330. Seguridad básica - Asegurando el servidor contra XSS [14037](https://platzi.com/clases/1376-hapi-js/14037-seguridad-basica-asegurando-el-servidor-contra-xss/)

### Descripción:


Otra de las vulnerabilidades que es muy común es **XSS** o Cross-site scripting, que es un tipo de ataque de seguridad por inyección en el que un atacante inyecta datos o algún _script_ o códio malicioso desde otro sitio web diferente.

Para manejar y corregir esta vulnerabilidad en la seguridad de nuestra aplicación implementaremos la estrategia de **CSP** o Content Security Policy para definir específicamente los orígenes desde los cuales vamos a permitir la ejecución de _scripts_ o el acceso a recursos desde y hacia nuestra aplicación. Para esto usaremos un par de _plugins_ adicionales: **Blankie** y **scooter** (scooter por ser dependencia de blankie).

Instalamos ambos desde la terminal: `npm i blankie scooter -S` y requerimos ambos en nuestro _script principal_.

Al igual que los _plugins_ anteriores, registramos **blankie** con las siguientes opciones:
``` 
    await server.register ([ scooter, {
      'plugin': blankie,
      'options': {
        'defaultSrc': `'self' 'unself-inline' <urls adicionales>`,
        'styleSrc': `'self' 'unself-inline' <urls adicionales>`,
        'fontSrc': `'self' 'unself-inline' <urls adicionales>`,
        'scriptSrc': `'self' 'unself-inline' <urls adicionales>`,
        'generateNonces': false
      }
    }])
    
```

Finalmente, al acceder a nuestra aplicación, notaremos que sólo serán permitidos los _scripts_ y _recursos_ que provengan desde las fuentes explícitamente definidas en las opciones indicadas al registrar el plugin, de lo contrario simplemente no se cargarán.

_Si quieres aprender más sobre temas de Seguridad en la web, te invito a ver luego el[Curso de Análisis de Vulnerabilidades Web con OWASP](https://platzi.com/cursos/seguridad/)._

### Links:

* [blankie  -  npm](https://www.npmjs.com/package/blankie)

* [scooter  -  npm](https://www.npmjs.com/package/scooter)

### Comentarios:

* **Diego Ivan Padilla Bernal** (3) [608298](https://platzi.com/comentario/608298/) 

	al parecer blankie ya no usa **scooter** sino **@hapi/scooter** porque no me encontraba el plugin hasta que instalé el otro

# Herramientas de desarrollo [2595]

## 0340. Depuración del proyecto [14038](https://platzi.com/clases/1376-hapi-js/14038-depuracion-depurando-el-proyecto/)

### Descripción:


Para depurar el código del proyecto solo hace falta iniciar el servidor de `node` con la siguiente instrucción:
``` 
    node --inspect index.js
    
```

Se lanzará el servidor como de costumbre, pero adicionalmente se creará un servidor para la interfaz de depuración que podemos acceder desde el navegador _Google Chrome_.

Específicamente se podrá ver un icono de NodeJS al inicio de la barra de menú del _Inspector de elementos_ , y al hacer clic sobre este, se abrirá una consola de _DevTools_ dedicada para la depuración de Node. Agregamos luego el proyecto al _workspace_ y estamos listos para iniciar la depuración.

Una alternativa a las DevTools de _Google Chrome_ es la funcuionalidad de depuración que viene integrada con el editor de _Microsoft_ VisualStudio Code. Esta funcionalidad está representada por un ícono particular en la barra de herramientas que asemeja un _bug_ con un círculo tachado. Al hacer clic sobre este icono, se habilita el panel con las opciones de configuración y ejecución de la depuración. Luego en la terminal integrada del editor se puede ver la consola de depuración.

En ambas herramientas es posible establecer _breakpoints_ , _run_ paso a paso, inspección de variables y otras funciones de depuración.

Una tercera alternativa es mediante la implementación del módulo **hapi-dev-errors** dentro del propio código de la aplicación. Este módulo se instala, requiere y registra de la misma manera que Good y los otros módulos que hemos visto, pero en las opciones de registro indicaremos la propiedad: `showErrors`, a la que asignaremos un valor buleano de acuerdo con la variable de entorno `process.env.NODE_ENV` para asegurarnos de que los mensajes de depuración solo sean visibles en el entorno de desarrollo, no en producción. Con este módulo, los errores serán capturados y mostrados directamente en el navegador de una forma amigable y con algunos detalles para su depuración.

### Links:

* [hapi-dev-errors  -  npm](https://www.npmjs.com/package/hapi-dev-errors)

### Comentarios:

* **Jecsham Castillo** (4) [443872](https://platzi.com/comentario/443872/) 

	Esto es lo que necesitaba.

## 0350. Ecosistema de Hapi [14006](https://platzi.com/clases/1376-hapi-js/14006-ecosistema-de-hapi/)

### Descripción:


En el sitio web de Hapi, hay una sección llamada Plugins en la que están organizados una gran cantidad de complementos según su funcionalidad de los cuales te menciono algunos que conozco y que pudieran serte de utilidad:

* **Hapi pal** : permite hacer un _scafolding_ (o estructura de archivos base) de la cual partir en el desarrollo de tus proyectos.
* **Apollo server** : permite crear una API de _GraphQL_
* **Bell** : para el manejo simplificado de autenticación con redes sociales, Slack, Github, Dropbox, DigitalOcean, y muchos más.
* **Lab** : permite hacer _tests_ del proyecto.
* **Lout** : es un generador de documentación para Hapi.
* **Hapi Swagger** : permite generar documentación de APIs compatible con _OpenAPI_.



Te invito a completar tu proyecto y compertirlo con tus compañeros para intercambiar experiencias.  
Recuerda que puedes dejarme tus comentarios, dudas y sugerencias en la sección de deiscusiones, o contactarme a través de mis redes sociales para cualquier consulta sobre cualquiera de los temas aprendidos en este curso.

¡Felicidades!  
De esta manera hemos llegado al final del curso de Hapi, ya puedes seguir adelante y tomar el examen.

### Links:

* [https://hapipal.com/](https://hapipal.com/)

* [apollo-server-hapi  -  npm](https://www.npmjs.com/package/apollo-server-hapi)

* [bell  -  npm](https://npmjs.com/package/bell)

* [lab  -  npm](https://www.npmjs.com/package/lab)

* [hapi-swagger  -  npm](https://www.npmjs.com/package/hapi-swagger)

* [lout  -  npm](https://www.npmjs.com/package/lout)

* [hapi Plugins](https://hapijs.com/plugins)

### Comentarios:

* **henrytabimagiraldo** (8) [398834](https://platzi.com/comentario/398834/) 

	Hey! Muchas gracias por todo el conocimiento compartido! ;D

	* **Navarrock33** [398834] (3)

		Gracias a ti también por tus comentarios, habían conceptos de los que me vengo a enterar gracias a tus comentarios a lo largo del curso =)

* **Jecsham Castillo** (3) [443890](https://platzi.com/comentario/443890/) 

	Realmente un buen curso y un excelente profesor, noté que siempre estuvo respondiendo dudas a los estudiantes en los comentarios!

* **Eduardo P. Rivero** (2) [961809](https://platzi.com/comentario/961809/) 

	Con el nuevo diseño de la web de Hapi, ahora en la sección de plugin van a ver los proyectos realizados por la comunidad y en la sección de módulos los mantenidos por el core team de Hapi.
	
	[Modulos oficiales de Hapi](https://hapi.dev/family/?sort=name)
	
	[Plugins](https://hapi.dev/plugins/)
	
	También hapi ahora es distribuido en npm bajo la organización **hapi** por lo que la forma de instalarlo y referenciarlo ha cambiado, escribí sobre eso en este tutorial:
	
	<https://platzi.com/tutoriales/1376-hapi-js/4883-actualiza-hapijs-a-su-nueva-dependencia-en-npm/>

* **gorydev** (2) [809401](https://platzi.com/comentario/809401/) 

	les comparto mi repo [Hapi-REST-repo](https://github.com/gorydev/Hapi-REST)

* **Andrés Mauricio Montoya Sánchez** (2) [590851](https://platzi.com/comentario/590851/) 

	Genial! Yo he hecho algunas pequeñas modificaciones orientadas a las ultimas versiones de node: <https://github.com/MontoyaAndres/platzi/tree/master/hapi-hello> y también cómo subir este proyecto a now. Aquí la URL: <https://platzioverflow.andresmontoyain.now.sh/>

* **Luis Alexander Chip** (1) [913961](https://platzi.com/comentario/913961/) 

	Excelente curso, muy buena explicacion por parte del profesor.

* **Sabrina Valerio Hidalgo** (1) [735113](https://platzi.com/comentario/735113/) 

	Uno de los mejores cursos que he tomando en Platzi!

* **Fernando Azuaje** (1) [667782](https://platzi.com/comentario/667782/) 

	Exelente curso

* **Luis Paredes** (1) [600938](https://platzi.com/comentario/600938/) 

	Lo dije al principio y al final lo mantengo excelente Profesor!

* **mario-salinas** (1) [460181](https://platzi.com/comentario/460181/) 

	Que genial curso, siento que es de los mejores de Platzi.  
	Gracias

