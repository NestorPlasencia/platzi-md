[Curso de End to End Testing con Cypress 1411](https://platzi.com/cursos/testing-cypress)

# Introducción [2717]

## 0010. ¿Qué es End-to-End Testing [14608](https://platzi.com/clases/1411-testing-cypress/14608-que-es-end-to-end-testing/)

### Descripción:


Para definir **End-to-End Testing** es necesario definir primero otros conceptos:

**Testing** : Es un proceso, un método de trabajo, una herramienta, que se utiliza para identificar fallas en el software o producto con el fin de que este alcance un grado aceptable de madurez y estabilidad antes de ser lanzado.

Según la **Pirámide de testing** , existen varios niveles:

* **Unit Test** o **Pruebas Unitarias** : permiten probar los elementos más fundamentales del software como objetos, funciones, eventos, etc.
* **Component Tests** o **Pruebas de Componentes** : permiten identificar fallas en componentes que incluyen varias funciones o elementos internos.
* **Integration Tests** o **Pruebas de Integración** : permiten probar el comportamiento y posibles fallas en la interacción entre los componentes entre sí, y demás elementos del software.
* **GUI Test** o **End-to-end Tests** : nos permiten identificar fallas en la interfaz de usuario. Es en este nivel de pruebas en el que nos enfocaremos en este curso. Es el _testing_ más elaborado que existe, porque depende de los demás niveles.



Algunas características del **End-to-end Testing** :

* Prueba todo el flujo del software desde el punto de vista del usuario final.
* Prueba el software desde la interfáz de usuario y no desde el código interno.
* Está enfocado en detectar posibles problemas que pudieran encontrar nuestros usuarios en su interacción con el flujo general del programa.



### Comentarios:

* **Sebastián Salinas** (6) [432132](https://platzi.com/comentario/432132/) 

	Excelente que Platzi comience a implementar cursos de Testing.

	* **Juan David Castro (Platzi)** [432132] (1)

		¡Hay muchos otros cursos de testing! Aquí puedes ver algunos: <https://platzi.com/blog/que-es-y-como-funciona-tdd/>. 😉

* **EmpiricalCoder** (4) [419688](https://platzi.com/comentario/419688/) 

	Bien resumido el concepto sobre lo que es el End To End Testing, se ve que vamos a aprender muy bien como usar este nuevo conocimiento y la herramienta (Cypress).
	
	Puedo agregar, que en algunos lugares se le conoce al End To End Testing como BlackBox Testing (o Testing de Caja Negra), ya que se prueba directamente sobre la interfaz gráfica, como un usuario final y sin tener conocimiento de como esta compuesto el código internamente, de modo que solo se prueba la funcionalidad del mismo.

* **cmilianocastiblanco** (2) [560248](https://platzi.com/comentario/560248/) 

	Empecemos este curso, soy usuario de Selenium Java y quiero conocer nuevas herramientas que mejore mi calidad como ingeniero para realizar testing.

* **Joaquin García Santiago** (1) [614636](https://platzi.com/comentario/614636/) 

	¿Que es testing?

	* **alexisromans** [614636] (4)

		Hay un curso de Fundamentos de pruebas, te puede ayudar mucho. 😃

	* **Juan David Castro (Platzi)** [614636] (1)

		Según la descripción de la clase:
		
		> Es un proceso, un método de trabajo, una herramienta, que se utiliza para identificar fallas en el software con el fin de que este alcance un grado aceptable de madurez y estabilidad antes de ser lanzado.

* **orivasm44** (1) [444447](https://platzi.com/comentario/444447/) 

	Con esta curso se puede aplicar TDD?

	* **bewe** [444447] (3)

		Cypress corre mucho, mucho más rápido.  
		Estas mejoras arquitectónicas desbloquean la capacidad de hacer TDD con pruebas completas de principio a fin por primera vez.

* **luisangel2895** (1) [415078](https://platzi.com/comentario/415078/) 

	soy el primer alumno ? :v

	* **Andrés Felipe Largo Rodríguez** [415078] (1)

		Aparentemente :v

## 0020. ¿Qué es Cypress [14609](https://platzi.com/clases/1411-testing-cypress/14609-que-es-cypress/)

### Descripción:


Para llevar a cabo el **End-to-end testing** (e2e) es necesario disponer de una herramienta que simule la interacción de los usuarios con el _browser_. **Cypress** es esa herramienta o framework, que nos permite simular esa interacción. Ha sido producto de una evolución a partir de conceptos y frameworks anteriores como: Selenium, PhantomJS, Nightwatch y Puppeteer.

En el caso de que nuestro aplicativo requiera un backend será necesario utilizar una copia de este que sea lo más exacta posible a lo que estará luego en producción.

**Principales ventajas**

* No usa Selenium, por lo que es muy sencillo de integrar.
* Está hecho con Electron lo que le da acceso y control a una instancia de Chrome u otro navegador.
* Está enfocado exclusivamente en hacer e2e testing, y hacerlo muy bien.
* Funciona con cualquier librería o framework de frontend siempre que corran en un navegador.
* Los tests están escritos en JavaScript.
* Es un todo-en-uno, por lo que no requiere la instalación de paquetes de terceros para hacer su trabajo; sin embargo, se puede extender su funcionalidad con módulos adicionales.
* Es amigable con desarrolladores de QA.
* Es mucho más rápido que cualquier otra alternativa existente a la fecha.



### Links:

* [https://pptr.dev](https://pptr.dev)

* [https://nightwatchjs.org](https://nightwatchjs.org)

* [https://phantomjs.org](https://phantomjs.org)

* [https://seleniumhg.org](https://seleniumhg.org)

### Comentarios:

* **Alexander  Silvera** (7) [412490](https://platzi.com/comentario/412490/) 

	Porque este curso esta en la carrera de php, este tipo de test se puede realizar para cualquier tipo de aplicación?? Ya sea de javascript, php, python??

	* **edsadr** [412490] (4)

		definitivamente esta mal ubicado, ya lo reporto

	* **Osmell Caicedo** [412490] (1)
Así es, ejecutar las pruebas en navegador, permite ser implementado por cualquier front o backend

	* **Jhon Alexander Perez Valencia** [412490] (1)

		desde que tengas tu aplicación corriendo en un navegador, no importa en que lenguaje este hecha con **crypress** pues hacer las pruebas end to end ya que estas pruebas no son de código sino de la interfaz.

* **Alexander  Silvera** (3) [44819](https://platzi.com/comentario/412490/) 
Porque este curso esta en la carrera de php, este tipo de test se puede realizar para cualquier tipo de aplicación?? Ya sea de javascript...

	* **edsadr** [44819] (4)

		definitivamente esta mal ubicado, ya lo reporto

* **sebastian-alvarez-mejia** (2) [812794](https://platzi.com/comentario/812794/) 

	Lo bueno de tener algo de conocimiento en selenium con algún lenguaje de programación. Es que uno se puede adaptar fácilmente a otros procesos de automatización, pero para automatizar app moviles seguire usando por ahora selenium con appium gracias a que son open source.  
	De esta manera uno puede practicar mucho y no estar ligado a un pago mensual.

* **alexisromans** (2) [662648](https://platzi.com/comentario/662648/) 

	Pensaba que usar Selenium era algo moderno y conocido en todo el mercado por su facilidad de uso.

	* **Javier Fuentes Mora** [662648] (1)

		yo pensaba exactamente lo mismo estaba apunto de tomar un curso de selenium por fuera

* **EmpiricalCoder** (2) [419696](https://platzi.com/comentario/419696/) 

	Actualmente se sigue usando muchísimo Selenium Web Driver para Automatizar las Pruebas, sigue siendo muy demandado en el campo laboral, de hecho yo trabajo con Selenium Web Driver, XUnit como librería de Assertions y C# para los scripts, pero definitivamente suena bastante interesante de que una misma herramienta te contemple todos los componentes necesarios, vamos allá!

* **Ale17273has** (1) [525560](https://platzi.com/comentario/525560/) 

	Que interesante espero poder aprender nuevas cosas que me puedan ayudar

* **Alejandro González Reyes** (1) [70022](https://platzi.com/comentario/767819/) 
Que es un desarrollador QA

* **Briam Martínez Escobar** (1) [60700](https://platzi.com/comentario/609469/) 
No se si se tratará el tema más adelante en el curso, pero tengo una duda sobre cómo aborda cypress el tema del shadow dom? Ya que en mi ...

# Primeros pasos [2718]

## 0030. Configurando el proyecto inicial [14610](https://platzi.com/clases/1411-testing-cypress/14610-configurando-el-proyecto-inicial/)

### Descripción:


Para poner en práctica los conocimientos que iremos adquiriendo a lo largo del curso utilizaremos como base una aplicación llamada PlatziPosts, hecha con VueJS y Firebase, que está disponible en la sección de Archivos de esta clase.

Descarga el archivo ZIP, descomprímelo y ejecuta la instalación con `npm i`. También será necesario configurar el proyecto y la base de datos en la consola de Firebase.

Finalmente, crea la base de datos y habilita la autenticación a través de correo y contraseña en la sección correspondiente, luego transcribe los datos de las credenciales del proyecto suministrados por Firebase en el archivo _production.env_ usando la plantilla _example.env_.

Si quieres aprender más acerca de la manera de integrar Firebase en tus proyectos, te invito a ver el [Curso de Firebase para Web](https://platzi.com/cursos/firebase-web/).

### Comentarios:

* **penalba06** (4) [1000805](https://platzi.com/comentario/1000805/) 

	Hare este curso pero testeando otra aplicación, porque a pesar de instalar Node 8, persisten los errores y fallan muchas dependencias y eso que le dedique 2 horas, incluso levante un ambiente con Docker y nada.
	
	Como observación final recomiendo que para los próximos cursos los profesores se aseguren que sus aplicaciones no solo funcionen en sus maquinas, ademas de darle mantenimiento. Es de muy mal gusto comenzar un curso y no poder avanzar porque la instalación resulta ser el capitulo mas complejo del curso.

* **santimontiel** (4) [653077](https://platzi.com/comentario/653077/) 

	Buenas,  
	Si les falla al hacer **npm i**  
	Ejecuten antes este comando: **npm install react-native firebase@4.6.2 --save**  
	Saludos!

	* **Diana Marcela Valencia Garcia** [653077] (2)

		```
		    `<print"Muchas Gracias, fue de gran ayuda tu post">
		    
		```

	* **Diana Marcela Valencia Garcia** [653077] (2)

		```
		    <<print ("Muchas Gracias, fue de gran ayuda tu post")>>
		    
		```

* **eduk2** (4) [555466](https://platzi.com/comentario/555466/) 

	**SOLUCIÓN** para hacer funcionar el proyecto por errores de la versión de node.
	
	Lo normal es que quien instale node para este curso se instale la última versión y con la última versión no funciona el proyecto.  
	**Hay una forma de usar la versión que quieras de node para poder ejecutar este proyecto con node 8**.
	
	Si llevas varios intentos, lo primero que te recomiendo es borrar el directorio node_modules.
	
	Después instalar n (Node version management):
	
	`npm install -g n`
	
	Para indicar que quieres usar la versión 8:
	
	`n 8`
	
	Tras hacer esto puedes hacer un:
	
	`node --version`
	
	Y te debería indicar:
	
	`v8.15.1`
	
	Ahora puedes hacer un:
	
	`npm i npm run dev`
	
	Y te debería funcionar.
	
	Buena suerte!

* **edsadr** (4) [433513](https://platzi.com/comentario/433513/) 

	IMPORTANTE: El curso se hizo con la ultima version de LTS en ese momento que era el 8 por o tanto se reecomienda usar esta versión, Node 10 fue lanzado en LTS a finales del mes pasado, para realizar el update de version hay que asegurarse que todas las dependencias del proyecto ya son compatibles con Node 10, eso es todo un proceso un poco complejo que no esta en el scope del curso y por lo tanto usar una versión diferente de Node puede traerte problemas.

	* **bewe** [433513] (0)

		hola tengo una duda, y agradeceria mucho su ayuda ¿como puedo hacer un desplazamiento de un objeto manteniendo el clic oprimido y soltarlo para dejar el objeto en el lugar que desee ?  
		gracias de antemano

* **asfo** (4) [432845](https://platzi.com/comentario/432845/) 

	Para los que tienen problemas en Node 10/11, es bronca de Firebase, solo actualicen a Firebase 5.5.9 con
	``` 
	    npm install firebase@latest
	    
	```
	
	Y ya después tiran el `npm install` normal y debería funcionar, les dirá que hay un montón de paquetes con vulnerabilidades pero como esto es solo para aprendizaje no hay problema, pueden ignorar eso.

* **sebastian-alvarez-mejia** (3) [812951](https://platzi.com/comentario/812951/) 

	Bueno por lo que veo las personas de platzi, no hacen actualizaciones a estos cursos, la verdad muchas personas esperaban un curso directo a cypress no que tenian que levantar todo un proyecto el cual ya se encuentra desactualizado por el node que de hecho solo corre en node 8 y estamos en node 12… Después de leer los post de los compañeros se logro levantar el proyecto. Por favor usar un github si van a permitir que sea libre. Gracias

	* **Camilo Castro Ballesteros** [812951] (1)

		¿Lograste solucionar los errores? ya solucioné algunas cosas con las dependencias, pero sigo obteniendo errores en la consola.  
		si es así… podrías compartirme un repo donde pueda hacer clone 😃  
		te lo agradecería inmensamente

* **Carlos Jose Solar Zamorano** (3) [755028](https://platzi.com/comentario/755028/) 

	Al correr npm run dev y abrir la app en el browser obtengo el siguiente error:
	
	Uncaught FirebaseError: projectId must be a string in FirebaseApp.options

* **IvanAlexO** (3) [558844](https://platzi.com/comentario/558844/) 

	Para quienes obtuvieron el siguiente mensaje **_Function CollectionReference.doc() requires its first argument to be of type non-empty string, but it was: undefined_**  
	al momento de registrar o hacer login la solución es esta: en al archivo **_Login.vue_** busquen
	``` 
	    login() {
	                    this.performingRequest = true
	    
	                    fb.auth.signInWithEmailAndPassword(this.loginForm.email, this.loginForm.password).then(user => {
	                        this.$store.commit('setCurrentUser', user)
	                        this.$store.dispatch('fetchUserProfile')
	                        this.performingRequest = false
	                        this.$router.push('/dashboard')
	                    }).catch(err => {
	                        console.log(err)
	                        this.performingRequest = false
	                        this.errorMsg = err.message
	                    })
	                }
	    
	```
	
	busquen la línea:
	``` 
	    this.$store.commit(‘setCurrentUser’, user)
	    
	```
	
	y cambienlo por:
	``` 
	    this.$store.commit(‘setCurrentUser’, user.user)
	    
	```
	
	Lo mismo en el método **_singup()_** busquen la línea:
	``` 
	    this.$store.commit('setCurrentUser', user)
	    
	```
	
	y cambenlo por:
	``` 
	    this.$store.commit('setCurrentUser', user.user)
	    
	```
	
	Finalmente busquen:
	``` 
	    fb.usersCollection.doc(user.uid).set({
	                            name: this.signupForm.name,
	                            title: this.signupForm.title
	                        })
	    
	```
	
	y cambien por:
	``` 
	    fb.usersCollection.doc(user.user.uid).set({
	    name: this.signupForm.name,
	    title: this.signupForm.title
	    })
	    
	```
	
	Guarden los cambios y ejecuten, debería perderse el mensaje.  
	Saludos

* **José Luis García Peceros** (2) [1013287](https://platzi.com/comentario/1013287/) 

	para los que le sale error en windows tiene que instalar la version 8. pueden usar nvm, para instalar dejo link  
	<https://github.com/coreybutler/nvm-windows>
	``` 
	    nvm install8
	    
	```
	
	luego
	``` 
	    nvm use8
	    
	```
	
	y listo ya pueden hacer en su protecto npm install

* **Jorge Velasquez** (2) [985662](https://platzi.com/comentario/985662/) 

	SOLUCIÓN para hacer funcionar el proyecto por errores de la versión de node.
	
	Lo normal es que quien instale node para este curso se instale la última versión y con la última versión no funciona el proyecto.  
	Hay una forma de usar la versión que quieras de node para poder ejecutar este proyecto con node 8.
	
	Si llevas varios intentos, lo primero que te recomiendo es borrar el directorio node_modules.
	
	Después instalar n (Node version management):
	
	npm install -g n
	
	Para indicar que quieres usar la versión 8:
	
	n 8
	
	Tras hacer esto puedes hacer un:
	
	node --version
	
	Y te debería indicar:
	
	v8.15.1
	
	Ahora puedes hacer un:
	
	npm i npm run dev
	
	Y te debería funcionar.
	
	Buena suerte!

	* **Facundo Fernandez** [985662] (1)

		Hola, sigue sin funcionarme. Ya no se que hacer!

* **aaronsoto** (2) [930325](https://platzi.com/comentario/930325/) 

	Al ejecutar el comando “npm run dev” obtengo los siguientes datos en la consola y los siguientes errores. Alguien me puede ayudar para poder solucionarlos?
	``` 
	    > platzi-posts@1.0.0 dev C:\xampp\htdocs\Platzi\platzi-posts
	    > webpack-dev-server --inline --progress --config build/webpack.dev.conf.js
	    
	    internal/modules/cjs/loader.js:796
	        throw err;
	        ^
	    
	    Error: Cannot find module 'dotenv-webpack'
	    Require stack:
	    - C:\xampp\htdocs\Platzi\platzi-posts\build\webpack.dev.conf.js
	    - C:\xampp\htdocs\Platzi\platzi-posts\node_modules\webpack\bin\convert-argv.js
	    - C:\xampp\htdocs\Platzi\platzi-posts\node_modules\webpack-dev-server\bin\webpack-dev-server.js
	        at Function.Module._resolveFilename (internal/modules/cjs/loader.js:793:17)
	        at Function.Module._load (internal/modules/cjs/loader.js:686:27)
	        at Module.require (internal/modules/cjs/loader.js:848:19)
	        at require (internal/modules/cjs/helpers.js:74:18)
	        at Object.<anonymous> (C:\xampp\htdocs\Platzi\platzi-posts\build\webpack.dev.conf.js:5:16)
	        at Module._compile (internal/modules/cjs/loader.js:955:30)
	        at Object.Module._extensions..js (internal/modules/cjs/loader.js:991:10)
	        at Module.load (internal/modules/cjs/loader.js:811:32)
	        at Function.Module._load (internal/modules/cjs/loader.js:723:14)
	        at Module.require (internal/modules/cjs/loader.js:848:19) {
	      code: 'MODULE_NOT_FOUND',
	      requireStack: [
	        'C:\\xampp\\htdocs\\Platzi\\platzi-posts\\build\\webpack.dev.conf.js',
	        'C:\\xampp\\htdocs\\Platzi\\platzi-posts\\node_modules\\webpack\\bin\\convert-argv.js',
	        'C:\\xampp\\htdocs\\Platzi\\platzi-posts\\node_modules\\webpack-dev-server\\bin\\webpack-dev-server.js'
	      ]
	    }
	    npm ERR! code ELIFECYCLE
	    npm ERR! errno 1
	    npm ERR! platzi-posts@1.0.0 dev: `webpack-dev-server --inline --progress --config build/webpack.dev.conf.js`
	    npm ERR! Exit status 1
	    npm ERR!
	    npm ERR! Failed at the platzi-posts@1.0.0 dev script.
	    npm ERR! This is probably not a problem with npm. There is likely additional logging output above.```
	    
	```

	* **Brayan Laureano Paucar** [930325] (1)

		amigo tienes que instalar dotenv-webpack , se instala de la siguiente manera  
		npm i -g dotenv-webpack , saludos.

* **luisangel2895** (2) [507847](https://platzi.com/comentario/507847/) 

	Function CollectionReference.doc() requires its first argument to be of type non-empty string, but it was: undefined me sigue saliendo este error cuando quierolo loguearme con un usuario alguien me puede ayudar?

	* **juan diego ramirez rojas** [507847] (1)

		ya lo pudiste solucionar ? a mi me sale igual

	* **Mayra Alejandra Tabares** [507847] (1)

		Hola, a mi también me sucede 😦

	* **motatin** [507847] (1)

		Alguien nos puede ayudar con este error…???

* **Marilians** (2) [415015](https://platzi.com/comentario/415015/) 

	No me funciono… no se por donde empezar a buscar el problema

	* **edsadr** [415015] (1)

		podria ser problemas de versión de node y dependencias, asegurqate de usar Node version 8 e instalar de nuevo con `npm install`

* **Diana Marcela Valencia Garcia** (2) [66161](https://platzi.com/comentario/704020/) 
Buenas Tardes Estoy ejecutando npm run dev, y se genera el siguiente error: 33:24-33 "export ‘XhrIoPool’ was not found in ‘@firebase...

* **nova12** (1) [1011018](https://platzi.com/comentario/1011018/) 

	no pude instalar el proyecto, intente todo lo que han comentado, uso de versiones anteriores de node e intente instalar verciones anteriores de las dependencia de firebase, pero no me funciono

* **UchihaCFC** (1) [975967](https://platzi.com/comentario/975967/) 

	He incluido en el archivo prod.env.js tal cual se dice en el vídeo la configuración de firebase, pero me aparece el siguiente error al iniciar la app en el navegador:
	``` 
	    database.js?b3e7:214 Uncaught FirebaseError: projectId must be a stringin FirebaseApp.options
	    
	```
	
	Me he asegurado de que estén entre comillas para que los coja como string si es el caso pero nada …
	
	¿Cómo debe estar ese archivo ?

* **Angel Hernandez** (1) [879211](https://platzi.com/comentario/879211/) 

	Llevo saltando de curso en curso en la carrera de BackEnd con JS por que todos los cursos siempre tienen uno o mas detalles que los arruinan por completo, en este caso es que resulta que hay que crear un proyecto en FireBase, esto me desmotiva ya que lo que quiero aprender es como probar las funciones de una API con Express, abandonare este curso

* **Alberto Eduardo Tejos Salinas** (1) [771556](https://platzi.com/comentario/771556/) 

	Como recomendación:
	
	Este curso debiera acotarse sólo a cypress, que es lo que nos interesa. Tiene demasiadas cosas que no permiten levantar un proyecto limpio (vue, webpack, etc).
	
	Deberian utilizar Git y no archivos .zip.

* **Carlos Jose Solar Zamorano** (1) [755142](https://platzi.com/comentario/755142/) 

	Al ejecurar npm run dev, obtengo:
	
	Uncaught FirebaseError: Unknown option ‘timestampsInSnapshots’ passed to function settings(). Available options: host, ssl, credentials  
	at new FirestoreError (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/util/error.js:151:28)  
	at eval (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/util/input_validation.js:208:19)  
	at Object.forEach [as c] (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/util/obj.js:59:13)  
	at validateOptionNames (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/util/input_validation.js:206:58)  
	at new FirestoreSettings (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/api/database.js:116:101)  
	at Firestore.settings (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/api/database.js:186:27)  
	at eval (webpack-internal:///./src/firebaseConfig.js:39:4)  
	at Object…/src/firebaseConfig.js (<http://localhost:8081/app.js:4066:1>)  
	at **webpack_require** (<http://localhost:8081/app.js:679:30>)  
	at fn (<http://localhost:8081/app.js:89:20>)

* **Angela Gonzalez** (1) [731790](https://platzi.com/comentario/731790/) 

	Yo estoy tratando de levantar el proyecto y me da el siguiente error
	``` 
	    PS D:\platzi-posts> npm run dev
	    
	    > platzi-posts@1.0.0 dev D:\platzi-posts
	    > webpack-dev-server --inline --progress --config build/webpack.dev.conf.js
	    
	     94% asset optimization
	    
	     ERROR  Failed to compile with 1 errors                                         4:05:53 PM error  in ./src/assets/scss/app.scss
	    
	    Module build failed:Error: `sass-loader` requires `node-sass` >=4. Please install a compatible version.
	        at Object.sassLoader (D:\platzi-posts\node_modules\sass-loader\lib\loader.js:31:19)
	    
	     @ ./src/assets/scss/app.scss 4:14-20713:3-17:514:22-215
	     @ ./src/main.js
	     @ multi (webpack)-dev-server/client?http://localhost:8080 webpack/hot/dev-server ./src/main.js```
	    
	```

	* **jordifort1** [731790] (2)

		Ejecuta “npm install firebase@latest” a continuacion “npm install node-sass@latest”

* **Jaime Quintero Rodríguez** (1) [570461](https://platzi.com/comentario/570461/) 

	Al crear un nuevo Post no me aparecen en los post publicados, en la consola de chrome me sale el siguiente error:
	
	store.js?3bf3:23 Uncaught TypeError: Cannot read property ‘doc’ of undefined  
	at Object.eval [as next] (store.js?3bf3:23)  
	at next (index.cjs.js?5a4f:21218)  
	at eval (index.cjs.js?5a4f:19108)
	
	En concreto esta linea
	``` 
	    if (querySnapshot.docs.length) {
	    // eslint-disable-next-line
	    createdByCurrentUser = store.state.currentUser.uid == querySnapshot.docChanges[0].doc.data().userId
	    }
	    
	```

	* **Jaime Quintero Rodríguez** [570461] (1)

		Lo he solucionado cambiando
		
		querySnapshot.docChanges[0]
		
		por:
		
		(querySnapshot.docChanges())[0]

	* **motatin** [570461] (1)

		Te ha funcionado el cambio??.. Yo lo aplique y sigue sin dejar visualizar los posts.

* **Mariano Banchio** (1) [551893](https://platzi.com/comentario/551893/) 

	Al correr npm run dev y abrir la app en el browser obtengo el siguiente error:
	``` 
	    Uncaught FirebaseError: projectId must be a string in FirebaseApp.options
	    
	```
	
	Ya corrí npm install firebase@latest y nada.  
	Estoy usando la versión de node: 8.11.3  
	Y la versión de npm: 5.6.0  
	Alguna idea?
	
	Gracias desde ya !!

	* **Mariano Banchio** [551893] (1)

		PD: Mi projectId tiene pinta de ser un string realmente:
		``` 
		    projectId:"end-to-end-9d27e",```
		    :p
		```

	* **IvanAlexO** [551893] (1)

		Revisa el archivo **production.env** y asegurate que no existan comillas **( " ")** en ninguno.

	* **juan diego ramirez rojas** [551893] (1)

		ya lo solucionaste, yo tengo el mismo error

	* **juan diego ramirez rojas** [551893] (1)

		estabamos cometiendo el error de poner los valores con comillas a si debe quedar  
		![](url)

	* **juan diego ramirez rojas** [551893] (1)
![](url)

	* **juan diego ramirez rojas** [551893] (1)

		el archivo production.env
		``` 
		    // env template
		    apiKey=AIzaSyCxRLO0GRoaSAAAJIhPTdaw3gplC56MR0I
		    authDomain=AIzaSyCxRLO0GRoaSAAAJIhPTdaw3gplC56MR0I
		    databaseURL=https://platzipost-c35b7.firebaseio.com
		    projectId=platzipost-c35b7
		    storageBucket=''
		    messagingSenderId=194808157431```
		    
		```

	* **Carlos Jose Solar Zamorano** [551893] (1)

		**tengo esta configuración**
		
		// env template  
		apiKey=AIzaSyBZFt8YEWXBmQy0exGDDPuFQiga_QImTDQ  
		[authDomain=platzipost-14307.firebaseapp.com](http://authDomain=platzipost-14307.firebaseapp.com)  
		databaseURL=https://platzipost-14307.firebaseio.com  
		projectId=platzipost-14307  
		[storageBucket=platzipost-14307.appspot.com](http://storageBucket=platzipost-14307.appspot.com)  
		messagingSenderId=692194583472
		
		**Así y todo no me levanta y tengo el sgte error:**
		
		Uncaught FirebaseError: Unknown option ‘timestampsInSnapshots’ passed to function settings(). Available options: host, ssl, credentials  
		at new FirestoreError (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/util/error.js:151:28)  
		at eval (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/util/input_validation.js:208:19)  
		at Object.forEach [as c] (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/util/obj.js:59:13)  
		at validateOptionNames (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/util/input_validation.js:206:58)  
		at new FirestoreSettings (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/api/database.js:116:101)  
		at Firestore.settings (webpack-internal:///./node_modules/@firebase/firestore/dist/esm/src/api/database.js:186:27)  
		at eval (webpack-internal:///./src/firebaseConfig.js:39:4)  
		at Object…/src/firebaseConfig.js (<http://localhost:8081/app.js:4066:1>)  
		at **webpack_require** (<http://localhost:8081/app.js:679:30>)  
		at fn (<http://localhost:8081/app.js:89:20>)

	* **Fabian Gutierrez** [551893] (1)

		la cosa es que el env está llegando undefined; entonces para q corra debes en firebaseConfig reemplaza las variables por el string de production.env

* **Ale17273has** (1) [525615](https://platzi.com/comentario/525615/) 

	Me presenta el siguiente error cuando ejecuto npm run dev
	``` 
	    <0 info it worked if it ends with ok
	    1 verbose cli [ 'C:\\Program Files\\nodejs\\node.exe',
	    1 verbose cli   'C:\\Program Files\\nodejs\\node_modules\\npm\\bin\\npm-cli.js',
	    1 verbose cli   'run',
	    1 verbose cli   'dev' ]
	    2 info using npm@6.4.1
	    3 info using node@v10.15.2
	    4 verbose stack Error: ENOENT: no such file or directory, open 'C:\Users\Sem-6-INGENIERIAINDU\Downloads\proyecto_658add2e-a293-4e19-bfbb-f0e03fcca853\package.json'
	    5 verbose cwd C:\Users\Sem-6-INGENIERIAINDU\Downloads\proyecto_658add2e-a293-4e19-bfbb-f0e03fcca853
	    6 verbose Windows_NT 10.0.17134
	    7 verbose argv "C:\\Program Files\\nodejs\\node.exe" "C:\\Program Files\\nodejs\\node_modules\\npm\\bin\\npm-cli.js" "run" "dev"
	    8 verbose node v10.15.2
	    9 verbose npm  v6.4.1
	    10 error path C:\Users\Sem-6-INGENIERIAINDU\Downloads\proyecto_658add2e-a293-4e19-bfbb-f0e03fcca853\package.json
	    11 error code ENOENT
	    12 error errno -4058
	    13 error syscall open
	    14 error enoent ENOENT: no such file or directory, open 'C:\Users\Sem-6-INGENIERIAINDU\Downloads\proyecto_658add2e-a293-4e19-bfbb-f0e03fcca853\package.json'
	    15 error enoent This is related to npm not being able to find a file.
	    16 verbose exit [ -4058, true ]
	    >
	    
	```

	* **Diego Alexander Forero Higuera (Platzi)** [525615] (1)

		Prueba renombrando la carpeta de proyecto_658add2e-a293-4e19-bfbb-f0e03fcca853 a solo proyecto. El error es que no encuentra el archivo package.json

* **isabellaahc** (1) [473947](https://platzi.com/comentario/473947/) 

	Tengo los siguientes errores al ejecutar los comandos, no he podido finalizar la instalación.  
	¿Alguien que me pueda ayudar?
	
	* npm install:  
	“35047 error code ELIFECYCLE  
	35048 error errno 1  
	35049 error grpc@1.10.1 install: `node-pre-gyp install --fallback-to-build --library=static_library`  
	35049 error Exit status 1  
	35050 error Failed at the grpc@1.10.1 install script.  
	35050 error This is probably not a problem with npm. There is likely additional logging output above.  
	35051 verbose exit [ 1, true ]”
	
	
	
	-npm run dev:  
	"ERROR Failed to compile with 3 errors 11:22:35  
	These dependencies were not found:
	
	* firebase in ./src/firebaseConfig.js, ./src/router/index.js
	* firebase/firestore in ./src/firebaseConfig.js"
	
	

	* **Diego Alexander Forero Higuera (Platzi)** [473947] (1)

		Qué sistema operativo estas usando?, puedes compartir tu archivo package.json?

	* **isabellaahc** [473947] (1)

		Gracias por la la respuesta.  
		Este es mi archivo.
		``` 
		    {
		      "_from": "@firebase/auth@0.9.1",
		      "_id": "@firebase/auth@0.9.1",
		      "_inBundle": false,
		      "_integrity": "sha512-kiJtKXzM7DD1UNTdWcMmmRoU4LBX95JPWgCUN6nzumO1Ed+1izsgE4OwYVbZo+inSlOp6au0JTJrecsHHBemug==",
		      "_location": "/@firebase/auth",
		      "_phantomChildren": {},
		      "_requested": {
		        "type": "version",
		        "registry": true,
		        "raw": "@firebase/auth@0.9.1",
		        "name": "@firebase/auth",
		        "escapedName": "@firebase%2fauth",
		        "scope": "@firebase",
		        "rawSpec": "0.9.1",
		        "saveSpec": null,
		        "fetchSpec": "0.9.1"
		      },
		      "_requiredBy": [
		        "/firebase"
		      ],
		      "_resolved": "https://registry.npmjs.org/@firebase/auth/-/auth-0.9.1.tgz",
		      "_shasum": "406c7dee4688fe2a3a5457d0b75a6e549883bc2e",
		      "_spec": "@firebase/auth@0.9.1",
		      "_where": "C:\\Users\\Tinet\\Desktop\\PLATZI-POSTS\\node_modules\\firebase",
		      "author": {
		        "name": "Firebase",
		        "email": "firebase-support@google.com",
		        "url": "https://firebase.google.com/"
		      },
		      "bundleDependencies": false,
		      "dependencies": {
		        "@firebase/auth-types": "0.5.0"
		      },
		      "deprecated": false,
		      "description": "Javascript library for Firebase Auth SDK",
		      "devDependencies": {
		        "del": "3.0.0",
		        "express": "4.16.3",
		        "firebase-functions": "1.0.1",
		        "firebase-tools": "3.18.2",
		        "google-closure-compiler": "20180402.0.0",
		        "google-closure-library": "20180405.0.0",
		        "gulp": "4.0.0",
		        "gulp-sourcemaps": "2.6.4",
		        "protractor": "5.3.1"
		      },
		      "files": [
		        "dist",
		        "index.d.ts"
		      ],
		      "license": "Apache-2.0",
		      "main": "dist/auth.js",
		      "module": "dist/auth.esm.js",
		      "name": "@firebase/auth",
		      "peerDependencies": {
		        "@firebase/app": "0.x"
		      },
		      "repository": {
		        "type": "git",
		        "url": "https://github.com/firebase/firebase-js-sdk/tree/master/packages/auth"
		      },
		      "scripts": {
		        "build": "gulp",
		        "demo": "./buildtools/run_demo.sh",
		        "generate-test-files": "./buildtools/generate_test_files.sh",
		        "prepare": "npm run build",
		        "serve": "npm run build && npm run generate-test-files && gulp serve",
		        "test": "npm run generate-test-files && ./buildtools/run_tests.sh"
		      },
		      "version": "0.9.1"
		    }```
		    
		```

	* **santimontiel** [473947] (1)

		Hola Isabella, ejecuta primero este comando:  
		**npm install react-native firebase@4.6.2 --save**  
		y después volvé a ejecutar **npm i**  
		Debería funcionarte, saludos! 😃

* **leonardo ortega** (1) [466254](https://platzi.com/comentario/466254/) 

	buenas! ya pude hacer correr el proyecto. pero cuando sigo con la instruccion de generar una cuenta nueva, lleno los datos y cuando quiero guardar me salta ese error, alguien me podria ayudar ?
	
	GRACIAS!!! [4a9fee92-e810-4d09-a1a2-b3def15d7cc8.jpg](https://static.platzi.com/media/user_upload/4a9fee92-e810-4d09-a1a2-b3def15d7cc8-5cac5ac0-d569-4142-9f9c-288a6f2a7577.jpg)

	* **Diego Alexander Forero Higuera (Platzi)** [466254] (1)

		Puedes revisar los logs del servidor y compartirlos para poder ayudarte a solucionar el problema y que puedas seguir con el curso.

	* **Alfonso Rodríguez** [466254] (1)

		Esto se debe a que la version de Firebase que tienes en tu packages.json es superior a la que tiene el instructor, lo cual que en versionas superiores a la 5, Firebase cambio su API aqui un hilo que lo explica:  
		<https://github.com/vuejs/vuefire/issues/183>  
		solo asgurate que tengas la misma version que en el video que es la : “firebase”: “^4.13.1”.  
		y vuelve a correr npm i, con eso debe ser suficiente!

	* **iam-lars** [466254] (1)

		En caso que te siga fallando, lo que hice fue ajustar la función de login() en /src/components/Login.vue, la deje de la siguiente forma:
		``` 
		    fb.auth.signInWithEmailAndPassword(this.loginForm.email, this.loginForm.password)
		    .catch(err => {
		        console.log(err)
		        this.performingRequest = false
		        this.errorMsg = err.message
		    })
		    
		    fb.auth.onAuthStateChanged(user => {
		        this.$store.commit('setCurrentUser', user)
		        this.$store.dispatch('fetchUserProfile')
		        this.performingRequest = false
		        this.$router.push('/dashboard')
		    })
		    
		    
		```
		
		En ese mismo archivo en la función signup(), cambie fb.usersCollection.doc(user.uid) por fb.usersCollection.doc(user.user.uid)

* **leonardo ortega** (1) [462119](https://platzi.com/comentario/462119/) 
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-7281fab5-7f93-4420-9f21-9372fbb983dc.jpg)
	
	tengo este problema cuando le doy npm run dev, alguien me podria ayudar? gracias

	* **Eduardo Hidalgo Díaz Rugama** [462119] (2)

		según el siguiente hilo de github <https://github.com/webpack-contrib/sass-loader/issues/563> el problema puede ser en tu versión de node o tu version de npm. Al final dice que si tienes cierta versión posterior, solo hagas “npm rebuild …” para arreglarlo. Lee todo el hilo.
		
		<https://stackoverflow.com/questions/50210311/sass-loader-requires-node-sass-4-even-if-that-exist> aqui también te ofrecen una posible solución.
		``` 
		    npm rebuild --force
		    
		```

	* **leonardo ortega** [462119] (1)

		gracias Eduardo! con eso pude cargar bien pero cuando me da el enlace <http://localhost:8080/login> no me carga nada… se me queda toda la pantalla en blanco… sabes porque sera? gracias de ante mano!!

	* **Eduardo Hidalgo Díaz Rugama** [462119] (2)

		Si no tienes errores en tu consola cmd, y no te salen errores en tu consola del navegador, es porque posiblemente si esté funcionando todo tu código, pero no estás cargando correctamente los archivos.
		
		tienes que hacer un proceso de debug. verificar que tu html si esté cargado, veificar tu JS, verificar si tus estilos si fueron cargador, y poco a poco ir rastreando el bug.
		
		No puedo darte mas ayuda que esa sin ver el código o ver que te resulta de las consolas xD sorryn

	* **Alfonso Rodríguez** [462119] (3)

		leortega92  
		ignora el archivo production.env y las llaves que colocas ahi, ponlas en el archivo firebaseConfig.js, encontraras esto:  
		`const config = { apiKey: process.env.apiKey, authDomain: process.env.authDomain, databaseURL: process.env.databaseURL, projectId: process.env.projectId, storageBucket: process.env.storageBucket, messagingSenderId: process.env.messagingSenderId }`  
		cada una de esas remplaza su valor equivalente al settings que te da Firebase, no es buena practica pero ya no te mostrara la pantalla en blanco, este problema se debe a que arroja un error en consola diciendo que firebaseapp.options espera una cadena de strings pero por alguna razon que aun no descubro, los setting del file .env no esta llegando al archivo de config. Por el momento es una solucion, espero te sirva!

	* **Jose Carlo Rojas Mora** [462119] (1)

		Si copiaste el archivo de configuración que te da firebase muy posiblemente omitiste la config con la que deben ir en el .env  
		NOMBRE_VARIABLE=Valor_Variable
		``` 
		    apiKey=xxx
		    authDomain=xxx
		    databaseURL=xxx
		    projectId=xxx
		    storageBucket=xxx
		    messagingSenderId=xxx
		    
		```
		
		El archivo conf de firebase viene en formato json no .env

* **EmpiricalCoder** (1) [421915](https://platzi.com/comentario/421915/) 

	No puedo correr la aplicación, me aparece el siguiente error:
	
	![Run Dev Error.JPG](https://static.platzi.com/media/user_upload/Run%20Dev%20Error-f7d797e9-a8f6-408c-a86e-0f3ae0d082a6.jpg)
	
	Por favor que alguien me ayude, necesite continuar con el curso

	* **EmpiricalCoder** [421915] (1)

		```
		    PS C:\Jeremy\Platzi\Testing\E2E_Cypress\platzi-posts>npm run dev
		    
		    > platzi-posts@1.0.0 dev C:\Jeremy\Platzi\Testing\E2E_Cypress\platzi-posts
		    > webpack-dev-server --inline --progress --config build/webpack.dev.conf.js
		    
		    'webpack-dev-server'isnot recognized as an internal or external command,
		    operable program or batch file.
		    npm ERR! code ELIFECYCLE
		    npm ERR! errno 1
		    npm ERR! platzi-posts@1.0.0 dev: `webpack-dev-server --inline --progress --config build/webpack.dev.conf.js`
		    npm ERR! Exit status 1
		    npm ERR!
		    npm ERR! Failed at the platzi-posts@1.0.0 dev script.
		    npm ERR! This is probably not a problem withnpm. There is likely additional logging output above.
		    
		    
		    npm ERR! A complete log ofthis run can be found in:
		    npm ERR!     C:\Users\jbarroso\AppData\Roaming\npm-cache\_logs\2018-11-14T01_36_06_294Z-debug.log
		    PS C:\Jeremy\Platzi\Testing\E2E_Cypress\platzi-posts>
		    
		```

	* **edsadr** [421915] (1)

		podria ser problemas de versión de node y dependencias, asegurqate de usar Node version 8 e instalar de nuevo con `npm install`

	* **EmpiricalCoder** [421915] (1)

		 **Saludos.**
		
		Muchas gracias por la respuesta, sin embargo, la version que instalé en efecto fue la de Node v8 para evitar los problemas de compatibilidad (como pude leer en los comentarios de la clase), pero a pesar de eso me siguió dando el error, me puse a investigar en stackoverslow y no di con una solución completa, es decir, logre que ya no me diera el mismo error pero ahora da otro tipo de error , fue tratando de instalar las dependencias que alli me decía que faltaban instalar (las instale de manera global) y aun asi me persiste el error, no puedo correr la aplicación.
		
		Te dejo imagen del nuevo log que me aparece:
		
		![Error Aplicacion2.JPG](https://static.platzi.com/media/user_upload/Error%20Aplicacion2-b7f5dd6b-5de9-4bb3-a7fb-9f810b8b6287.jpg)
		
		Desde ya muchas gracias, de verdad me interesa y me “urge” poder continuar con el curso.

	* **edsadr** [421915] (1)

		Podrias por favor compartir el resultado de ejecutar `npm install`? al parecer no se te estan instalando las dependencias apropiadamente

* **maria-carolina-cano** (1) [418341](https://platzi.com/comentario/418341/) 

	a mi no me deja registrarme me sale este error {“error”:{“code”:400,“message”:“API key not valid. Please pass a valid API key.”,“errors”:[{“message”:“API key not valid. Please pass a valid API key.”,“domain”:“global”,“reason”:“badRequest”}],“status”:“INVALID_ARGUMENT”}} depronto alguien sabe que es?

	* **maria-carolina-cano** [418341] (1)

		ya logre solucionar el del error 400 Borrando las cookies del navegador y borrando la caché de DNS , pero ahora sale este otro error A network error (such as timeout, interrupted connection or unreachable host) has occurred. gracias

* **dario_a_diaz** (1) [412427](https://platzi.com/comentario/412427/) 

	Genial!, pude configurarlo sin problemas 😃

	* **Juan Manuel Viveros Martinez** [412427] (1)

		En que sistema operativo lo instalaste? tengo mac con la version de node v10.11.0 y npm 6.4.1 y no logre instalar las dependencias.

	* **dario_a_diaz** [412427] (1)

		Yo uso linux, node v8.11.2 y npm 6.1.0. Voy a probar de hacer el upgrade de la version de node a ver si me da problemas o no.

	* **dario_a_diaz** [412427] (1)

		Ahi pude probar con tu misma version @jmanuelviverosm, y sí, da errores al instalar las dependencias. Te sugiero que instales la v8 para poder avanzar con las enseñanzas del curso. Saludos!

	* **edsadr** [412427] (2)

		El curso esta hecho con Node v8, ya v10 esta en LTS esta semana pero los paquetes tardan un rato más en arreglar los problemas de compatibilidad, por lo tanto es prudente quedarse un rato más en v8

	* **johan2732** [412427] (2)

		pequeño detalle, sería bueno que en la descripciòn de la clase se manejara como las versiones mínimas que debemos tener instaladas para poder avanzar más rápido

	* **Juan Manuel Viveros Martinez** [412427] (1)

		Que bien hice todo el proceso en una maquina virtual con ubunto y todo funciono correctamente, el problema lo tengo en mac por las versiones actualizadas creen que si uso NVM para trabajar con node v8 funciona todo ?

	* **dario_a_diaz** [412427] (1)

		@jmanuelviverosm, yo uso nvm, y me funciono (pero uso ubuntu).

	* **suhkha92** [412427] (2)

		@jmanuelviverosm bajaste la maquina base e instalaste todo o encontraste una maquina con los requerimientos ya instalados? Saludos!

	* **Juan Manuel Viveros Martinez** [412427] (2)

		@suhkha92 baje la ultima version de ubuntu que esta en la pagina [](https://www.ubuntu.com/download/desktop) y le instale todo el node, npm y me funciono sin problemas, saludos.

	* **suhkha92** [412427] (1)

		@jmanuelviverosm gracias, ya intenté eso que comentaste pero siempre falla

	* **suhkha92** [412427] (2)

		Bueno, al final pude…en vm no se porque nunca se pudo, pero en mi equipo todo bien. Baje lo necesario con homebrew y efectivamente la version de node: 8.12.0 y npm: 6.4.1, funcionó bien.
		
		Si bien, dió un problema con node-sass, este se arregló corriendo: npm rebuild node-sass
		
		Y listo 😃

* **Alejandro González Reyes** (1) [70023](https://platzi.com/comentario/767821/) 
He tenido muchos problemas instalando proyectos antigúos de mpm a consecuencia de las versionez. Que es recomendable en estos casos.

	* **Juan David Castro (Platzi)** [70023] (1)

		Te recomiendo estudiar cómo se manejan las versiones de las herramientas publicadas en NPM.
		
		Que por defecto instales la última versión de una herramienta no significa que no puedas usar otra versión. Lo mismo al revés. Si tienes una versión vieja que te da problemas o no tiene un parche, puedes actualizarla suprémamente fácil.
		
		👉 <https://docs.npmjs.com/about-semantic-versioning>  
		👉 <https://www.campusmvp.es/recursos/post/truco-actualizar-a-la-ultima-las-versiones-de-dependencias-npm-en-package-json.aspx>

* **Mayra Alejandra Tabares** (1) [69637](https://platzi.com/comentario/760256/) 
Al intentar loguearme se presenta el siguiente error… Function CollectionReference.doc() requires its first argument to be of type ...

* **Mariano Banchio** (1) [56373](https://platzi.com/comentario/551893/) 
Al correr npm run dev y abrir la app en el browser obtengo el siguiente error: Uncaught FirebaseError: projectId must be a string i...

	* **Mariano Banchio** [56373] (1)

		PD: Mi projectId tiene pinta de ser un string realmente:
		``` 
		    projectId:"end-to-end-9d27e",```
		    :p
		```

* **luisangel2895** (1) [52617](https://platzi.com/comentario/507847/) 
Function CollectionReference.doc() requires its first argument to be of type non-empty string, but it was: undefined me sigue saliendo es...

	* **juan diego ramirez rojas** [52617] (1)

		ya lo pudiste solucionar ? a mi me sale igual

* **isabellaahc** (1) [49958](https://platzi.com/comentario/473947/) 
Tengo los siguientes errores al ejecutar los comandos, no he podido finalizar la instalación. ¿Alguien que me pueda ayudar? npm ...

	* **Diego Alexander Forero Higuera (Platzi)** [49958] (1)

		Qué sistema operativo estas usando?, puedes compartir tu archivo package.json?

* **leonardo ortega** (1) [49054](https://platzi.com/comentario/462119/) 
tengo este problema cuando le doy npm run dev, alguien me podria ayudar? gracias

	* **Eduardo Hidalgo Díaz Rugama** [49054] (2)

		según el siguiente hilo de github <https://github.com/webpack-contrib/sass-loader/issues/563> el problema puede ser en tu versión de node o tu version de npm. Al final dice que si tienes cierta versión posterior, solo hagas “npm rebuild …” para arreglarlo. Lee todo el hilo.
		
		<https://stackoverflow.com/questions/50210311/sass-loader-requires-node-sass-4-even-if-that-exist> aqui también te ofrecen una posible solución.
		``` 
		    npm rebuild --force
		    
		```

* **EmpiricalCoder** (1) [45615](https://platzi.com/comentario/421915/) 
No puedo correr la aplicación, me aparece el siguiente error: Por favor que alguien me ayude, necesite continuar con el curso

	* **EmpiricalCoder** [45615] (1)

		```
		    PS C:\Jeremy\Platzi\Testing\E2E_Cypress\platzi-posts>npm run dev
		    
		    > platzi-posts@1.0.0 dev C:\Jeremy\Platzi\Testing\E2E_Cypress\platzi-posts
		    > webpack-dev-server --inline --progress --config build/webpack.dev.conf.js
		    
		    'webpack-dev-server'isnot recognized as an internal or external command,
		    operable program or batch file.
		    npm ERR! code ELIFECYCLE
		    npm ERR! errno 1
		    npm ERR! platzi-posts@1.0.0 dev: `webpack-dev-server --inline --progress --config build/webpack.dev.conf.js`
		    npm ERR! Exit status 1
		    npm ERR!
		    npm ERR! Failed at the platzi-posts@1.0.0 dev script.
		    npm ERR! This is probably not a problem withnpm. There is likely additional logging output above.
		    
		    
		    npm ERR! A complete log ofthis run can be found in:
		    npm ERR!     C:\Users\jbarroso\AppData\Roaming\npm-cache\_logs\2018-11-14T01_36_06_294Z-debug.log
		    PS C:\Jeremy\Platzi\Testing\E2E_Cypress\platzi-posts>
		    
		```

* **maria-carolina-cano** (1) [45319](https://platzi.com/comentario/418341/) 
a mi no me deja registrarme me sale este error {“error”:{“code”:400,“message”:“API key not valid. Please pass a valid API key.”,“errors”:...

	* **maria-carolina-cano** [45319] (1)

		ya logre solucionar el del error 400 Borrando las cookies del navegador y borrando la caché de DNS , pero ahora sale este otro error A network error (such as timeout, interrupted connection or unreachable host) has occurred. gracias

* **Luis Valles** (0) [769257](https://platzi.com/comentario/769257/) 

	Tengo un problema al hacer **npm install**  
	Estoy usando windows 7, y cada vez que intento el paso anterior la consola me indica lo siguiente
	``` 
	    > grpc@1.10.1 install C:\wamp64\www\platzi-posts\node_modules\grpc
	    > node-pre-gyp install --fallback-to-build --library=static_library
	    
	    node-pre-gyp ERR! Tried to download(403): https://storage.googleapis.com/grpc-precompiled-binaries/node/grpc/v1.10.1/node-v64-win32-x64-unknown.tar.gz
	    node-pre-gyp ERR! Pre-built binaries not found for grpc@1.10.1andnode@10.16.0 (node-v64 ABI, unknown) (falling back to source compile with node-gyp)
	    node-pre-gyp ERR! Pre-built binaries not installable for grpc@1.10.1andnode@10.16.0 (node-v64 ABI, unknown) (falling back to source compile with node-gyp)
	    node-pre-gyp ERR! Hit error Connection closed while downloading tarball file```
	    
	```

## 0040. Integrando Cypress al proyecto [14611](https://platzi.com/clases/1411-testing-cypress/14611-integrando-cypress-al-proyecto/)

### Descripción:


Estando en el directorio del proyecto realizamos la instalación de Cypress con el comando `npm i cypress -D`. La instalación puede tomar varios minutos. Recuerda que tu proyecto debe incluir _webpack_ y sus archivos de configuración. Algo que debemos tener muy en cuenta es que para integrar Cypress a nuestro proyecto, necesitaremos configurar un entorno similar al entorno de producción.

Es necesario crear algunos scripts adicionales en las configuraciones de _webpack_ y modificar el archivo _build.js_ para que cargue las credenciales de Firebase apropiadas desde _production.env_ o _test.env_ según el entorno en el que estemos haciendo la ejecución.

Ya que necesitaremos un servidor estático para ejecutar las pruebas de Cypress, procedemos a instalar `npm i pushstate-server -D` y agregamos el _script_ correspondiente para su ejecución en el archivo de configuraciones de _webpack_.

Finalmente creamos el script que ejecutará el _build_ de nuestra aplicación y levantará el _server_ en el que se correrán las pruebas con Cypress. Siempre debemos hacer el _build_ antes de ejecutar el _testing_.

### Links:

* [Installing Cypress | Cypress Documentation](https://docs.cypress.io/guides/getting-started/installing-cypress.html#System-requirements)

### Comentarios:

* **IvanAlexO** (9) [558849](https://platzi.com/comentario/558849/) 

	Para quienes tuvieron el problema de acceder al sitio cuando ejecutan:
	``` 
	    npm runtest:init
	    
	```
	
	Les sale el mensaje: **Listening on port 9000 (<http://0.0.0.0:9000>)** y al dirigirse ahí sale que no encontró la página  
	![errorP.PNG](https://static.platzi.com/media/user_upload/errorP-f942900b-cc63-4195-b5ae-842ade7943df.jpg)  
	En el archivo **_package.json_** cambien la línea siguiente:
	``` 
	    "test:server": "pushstate-server dist"
	    
	```
	
	por la siguiente:
	``` 
	    "test:server": "pushstate-server -d ./dist",
	    
	```
	
	Esto debido a la nueva versión de **_pushstate-server_**
	
	* **-d** hace referecia a un directorio por lo que debemos seleccionar **dist**  
	Ahora nuevamente ejecuten el comando **_npm run test:init_** y MUCHO OJO en lo siguiente: Les seguirá apareciendo la dirección 0.0.0.0:9000 pero en el navegador cambien por **localhost:9000**  
	y la página de test ya está en marcha.  
	Saludos.
	
	

	* **Delsa Mendez** [558849] (1)

		Gracias

* **Alver Ortega** (2) [832308](https://platzi.com/comentario/832308/) 

	al ejecutar el comando `test-server` me salia este error en el navegador  
	Cannot GET /  
	no logre encontrar el error y decidí usar http-server, sirve para crear un servidor virtual y servir assets

* **cristianmaridev** (2) [475930](https://platzi.com/comentario/475930/) 

	Busco ser critico e imparcial a la hora del aprendisaje, 8 años llevo aprendiendo con esta forma, es el primer curso que compro de platzi, ya vi errores que voy comentando por que se notan mucho.
	
	Llevo 2 clases viendo como configurar un proyecto. - error, creación de 0 con lo minimo indispensable y pruebas aisladas son más puntuales rapidas de ver y no querer caminar y hacer algo mientras pasa el video y se pierden cosas.
	
	pushstate no lo conocia me parecio bueno que se pudiera ver con la forma anterior que menciono ya que podría hablarse u organizarse un poco mejor el package.json se tendría tiempo para explayar más acerca de algunas cuestiones que dan para aprender por ahi un poquito más.
	
	No busco ofender sino que todos podamos aportar algun detalle que pueda ser modificable es de por vida el curso, puede mejorar 😄

	* **ernestognw** [475930] (3)

		En mi caso, creo que ver usos robustos de las librerías es lo que aporta mayor valor de Platzi.
		
		A pesar de que es fácil encontrar tutoriales y documentación de las librerías, creo que lo más valioso es ver a los instructores trabajando en ambientes que sean lo más cercanos a la realidad posible.
		
		Los detalles y “mañas” de las implementaciones no te las enseñan los artículos, la documentación, ni los tutoriales en youtube

* **edg_colon** (1) [1045508](https://platzi.com/comentario/1045508/) 

	¿Porque se estan declarando dos veces la constante env?  
	Algun linter ayudaria…

* **Andres Roberto Coello Goyes** (1) [1006326](https://platzi.com/comentario/1006326/) 

	Muchas vueltas…

* **Raúl Martín Anaya Rojo** (1) [812232](https://platzi.com/comentario/812232/) 

	Para los que tengan el siguiente error al ejecutar el comando `pushstate-server dist` y esten trabajando en **windows** :
	``` 
	    events.js:183
	          throw er; // Unhandled 'error' event
	          ^
	    
	    Error: listen EADDRINUSE 0.0.0.0:9000
	        at Server.setupListenHandle [as _listen2] (net.js:1360:14)
	        at listenInCluster (net.js:1401:12)
	        at doListen (net.js:1510:7)
	        at _combinedTickCallback (internal/process/next_tick.js:142:11)
	        at process._tickCallback (internal/process/next_tick.js:181:9)
	        at Function.Module.runMain (module.js:696:11)
	        at startup (bootstrap_node.js:204:16)
	        at bootstrap_node.js:625:3
	    
	```
	
	La solución es eliminar el proceso que esta usando el puerto que utiliza **pushstate-server** u utilizar otro.
	
	Los pasos para eliminar el proceso son los siguientes:
	
	Para encontrar los procesos que están utilizando el puerto
	``` 
	    netstat -ano | find ":9000"
	    
	```
	
	Comando que te dirá que programa esta utilizando el puerto.
	``` 
	    tasklist /fi"pid eq {process-id}"
	    
	```
	
	Comando para eliminar el proceso y liberar el puerto.
	``` 
	    taskkill /pid {process-id} /f
	    
	```
	
	**Nota:**  
	Estos comandos se tienen que utilzar en el **cmd** o en **powerShell** no en bash.
	
	**Mas información:**  
	<https://github.com/nuxt-community/starter-template/issues/87>

* **juand_silva** (1) [804631](https://platzi.com/comentario/804631/) 

	Para los que les aparece este error cuando corren el comando de build
	
	instalen esta dependencia para webpack `npm install --save-dev optimize-css-assets-webpack-plugin@3.2.0`
	
	<https://stackoverflow.com/questions/56850443/unable-to-build-my-vuejs-application-using-npm-run-build>

* **juan diego ramirez rojas** (1) [682429](https://platzi.com/comentario/682429/) 

	alguien sabe porque arroja este error en el login??  
	Function CollectionReference.doc() requires its first argument to be of type non-empty string, but it was: undefined

	* **Mayra Alejandra Tabares** [682429] (2)

		La solución que a mí me sirvió fue esta <https://platzi.com/comentario/558844/>

* **sienddo** (1) [596650](https://platzi.com/comentario/596650/) 

	este curso asume que sos un frontend semi-senior … si no lo sos … se te va a hacer cuesta arriba seguirlo …

	* **Pryffer LLC** [596650] (1)

		para nada amigo, el curso me parece bastante a meno y básico, si tienes problemas para seguirlo te sugiero ver los anteriores cursos y fundamentos de javascript para tener bases solidas.

* **darwistg** (1) [564537](https://platzi.com/comentario/564537/) 

	cypress serviria para probar una app monolítica?, que no contenga javascript.

	* **Diego Alexander Forero Higuera (Platzi)** [564537] (2)

		Sirve para hacer testing en el frontend, no del backend, en front verifica si las cosas que tienen que verse se ven por ejemplo ademas puedes validar otras cosas.

	* **darwistg** [564537] (1)

		umm ya y que herramienta me serviria para probar este tipo de aplicaciones?  
		y porque siempre respondes siempre tu los comentarios? sin ofender

	* **Diego Alexander Forero Higuera (Platzi)** [564537] (1)

		Para test de backend cuando usas JavaScript puedes usar Jasmine, tenemos un curso de test con Jasmine.
		
		En cuanto a porque respondo tanto, es porque me gusta apoyar a los estudiantes.

	* **darwistg** [564537] (1)

		por ejemplo para la laravel que puedo usar? o para php en general, no se porque esta el curso de cypress entonces en la carrera de backend con php si solo es para probar una app hecha con un framework de frontend?, ok pero eres profesor tambien?

	* **Diego Alexander Forero Higuera (Platzi)** [564537] (1)

		Para php la más usada es phpunit para hacer testing unitario, en cuanto a si soy profesor, no, no soy profesor, pero hago parte del team Platzi hace tres años, era estudiante destacado y luego comencé a trabajar con ellos.

	* **darwistg** [564537] (1)

		pero con phpunit no se hacen pruebas de caja negra pruebas finales en la interfaz de usuario. yo quiero ser parte del team, que hay que hacer?

	* **Diego Alexander Forero Higuera (Platzi)** [564537] (1)

		En el Backend nunca se prueba interfaces, se prueba la lógica de la aplicación, si recibe un parámetro una vista que debe pasar. Se prueba que con una consulta especifica retorne un valor esperado, este tipo de cosas son las que siempre se prueban.

	* **Ludwring Liccien** [564537] (1)

		PhPUnit es para Pruebas Unitarias y hasta de integracion.  
		Para Pruebas de End to End o de usuarios puedes usa Cypress en un proyecto PHP o cualquier proyecto web ya que Cypress solo prueba la parte de como se ve y se comporta la app en el navegador

* **IrvingAriel** (1) [502680](https://platzi.com/comentario/502680/) 

	Errores en los archivos .env, no se visualizan dentro del ZIP.

	* **IrvingAriel** [502680] (1)

		No pues te equivocaste, hay que leer mejor el readme y poner más atención en los videos. XD

* **leonardo ortega** (1) [482366](https://platzi.com/comentario/482366/) 

	perdi la paciencia con este curso. en serio… le tenia muchas ganas pero siempre me dan errores y termino pidiendo ayuda a gente que sabe de cosas de programacion, comencé el primero de enero y a 17 dias no he podido avanzar de la clase 4 instalando… los tester que queremos aprender a automatizar precisamente no sabemos de codigo, la idea seria aprender pero hasta los mismos programadores que pido ayuda me dicen que no explican bien aca como hacer las cosas… saludos

	* **devdanielgo** [482366] (4)

		Yo en windows no lo podía correr, lo mismo, errores cuando corría el server, tenía node v10.*, me cambie a una maquina virtual con Ubuntu 18.04, instalé NVM e instalé Node v8.10, y funciona, los parámetros de conexión a firebase los pegué directamente en firebaseConfig.js, ya que parece que webpack no puede procesar los archivos .env por alguna razón; ovbiamente si lo haces de ésta forma no es recomendable porque expones tus paramétros de conexión.
		
		Lo único que me queda es probar con una versión mas reciente de Node para comprobar que ese era el problema, y porque no se lee correctamente el archivo .env

	* **Angela Patricia Girón Duque** [482366] (2)

		Totalmente de acuerdo. Yo estuve tres días hasta que conseguí que todo funcionase.  
		Debería haber un paso a paso de la instalación de las herramientas y el proyecto, incluidos los links a las versiones donde sí funciona, ya que la finalidad del curso es otra y termina resultando muy frustrante no lograr avanzar.

	* **bewe** [482366] (2)

		no lo uses con webpack esto es opcional crea tu crud y implementa cypress este curso tiene mucho que enseñar te lo recomiendo ademas que su documentación es muy completa y facil de interpretar.

	* **amauri-guevara-leon** [482366] (1)

		Hola, yo estoy aprendiendo y mi hermano que ya es programador me está ayudando en las instalaciones. Te concedo la razón porque ne verdad hay muchas cosas que no explican. Yo te quiero dar algunas indicaciones de lo que me ha servido hasta ahora.  
		Contexto: Estoy desde windows 10.
		
		  1. No uses el comando ‘npm’, no funciona, sólo envía errores. Instala mejor ‘yarn’ y podría funcionar.
		  2. Olvídate de la terminal que el usa en el editor de código, o de la de windows. Mejor usa la nueva terminal de Ubuntu que se puede usar en Windows. (Puedes buscar más información en Google).
		  3. Googlea mucho lo que él hace y hazlo de otra manera. Hay diferentes formas de instalar lo que él está usando. Si por ejemplo dice: ‘Corramos build’ y no te funciona, Googlea cómo hacerlo sin necesidad de hacerlo de la manera que él te enseña.
		
		
		
		Creo que eso te podría ayudar. 😄

* **Sebastián Salinas** (1) [432211](https://platzi.com/comentario/432211/) 

	muy sencillas las conexiones y bien explicado, hasta el momento el curso me tiene con muy buenas expectativas

* **catscs** (0) [76201](https://platzi.com/comentario/882839/) 
Hola, que tema esta utilizando par visual code ??

## 0050. La consola de Cypress [14612](https://platzi.com/clases/1411-testing-cypress/14612-la-consola-de-cypress/)

### Descripción:


La consola de Cypress es la interfaz gráfica de configuración y monitoreo en la que están listados todos los _scripts_ de pruebas que hemos definido. Para acceder a ella al momento de ejecutar el testing es necesario incluir en el archivo de _webpack_ un _script_ con el comando `cypress open --project ./test`.

Este comando al ser ejecutado junto con el _build_ y el _server_ , creará una nueva carpeta llamada _test_ con todos los archivos generados durante la ejecución.

La estructura de archivos creados por la consola de Cypress se ve mas o menos así:
``` 
    /test
      /cypress
        /fixtures
        /integration
        /plugins
        /support
        /videos
      cypress.json
    
```

La primera vez que se ejecuta la consola creará algunos archivos de ejemplo. El detalle de cada carpeta y lo que contienen lo veremos más adelante en el curso.

Además de la consola, Cypress cuenta con el _test runner_ , una interfaz gráfica adicional en la que se reailzan las simulaciones y pruebas. Tiene dos secciones principales y un menú.

La sección de la izquierda muestra el progreso, los logs y el detalle de todas las pruebas individualmente, mientras que la sección de la derecha muestra el navegador integrado donde se llevan a cabo las pruebas.

### Links:

* [The Test Runner | Cypress Documentation](https://docs.cypress.io/guides/core-concepts/test-runner.html#Overview)

### Comentarios:

* **Gonzalo Cofré** (1) [714977](https://platzi.com/comentario/714977/) 

	Me aparece el siguiente error al ejecutar en el navegador la url <http://0.0.0.0:9000/>
	
	`Cannot GET /`

	* **Luis Valles** [714977] (1)

		Utiliza la dirección 127.0.0.1:9000, si pushstate está corriendo sin errores, entonces deberías ser capaz de acceder a el desde la dirección de tu host local

	* **Raúl Martín Anaya Rojo** [714977] (1)

		Puedes utilizar el comando:
		``` 
		    pushstate-server -d ./dist
		    
		```
		
		En lugar de
		``` 
		    pushstate-server dist
		    
		```

## 0060. Mi primer test [14613](https://platzi.com/clases/1411-testing-cypress/14613-mi-primer-test/)

### Descripción:


Para correr finalmente nuestros propios _tests_ , necesitaremos ejecutar en paralelo los _scripts_ que hemos creado tanto para levantar el servidor de pruebas como para correr la consola de Cypress. Será necesario instalar una nueva dependencia de desarrollo llamada `npm-run-all`.

Luego de instalada, modificamos el _script_ `test:dev` para que haga uso de ella y ejecute `cypress:open` en paralelo con los scripts `build:test` y `test:server`:
``` 
    ...
    ""test:dev"": ""npm run build:test && run-p --race test:server cypress:open""
    ...
    
```

Usamos el parámetro `--race` para que al terminar la ejecución de Cypress, termine también el servidor de pruebas.

**Tests**

Nuestros _tests_ los crearemos en la carpeta `/integration`, cada set de pruebas en un archivo de JavaScript individual que identificaremos como `.spec.js`.

Cypress trae integradas las funcionalidades de mochaJS y las aserciones de ChaiJS, por lo que si ya has trabajado antes con esto te va a resultar muy familiar.

La definición básica del test es la siguiente:
``` 
    describe('Nombre del test', () => {
      it('Descripción de la prueba', ()  => {
        // --- comandos de cypress
      })
    })
    
```

Mientras que `describe(...)` define y describe todo el conjunto de pruebas, `it(...)` nos permite definir cada test individual.

En el archivo _cypress.json_ , que veremos en detalle más adelante en el curso, se encuentran las configuraciones de Cypress entre las que se pueden definir variables globales que serán accesibles en todos los _scripts_. Esto es muy conveniente para datos como la url base del servidor de pruebas.

### Links:

* [npm-run-all  -  npm](https://www.npmjs.com/npm-run-all)

* [npm-run-all  -  npm](https://www.npmjs.com/package/npm-run-all)

### Comentarios:

* **zecamin** (2) [461894](https://platzi.com/comentario/461894/) 
Excelente tema, actualmente tengo un proyecto con vue y estoy usando vuetify. Ahora se como realizar pruebas e2e

* **orivasm44** (2) [445986](https://platzi.com/comentario/445986/) 

	Me parece interesante creo que es mucho mas fácil la configuración de cypress que ruby, python con selenium y algunos otros que he probado.

	* **Alexei Teófilo Mamani Coaquira** [445986] (1)

		de hecho cypress no solo puede funcionar con node.js, sino tambien con ruby, python.

* **dario_a_diaz** (1) [412884](https://platzi.com/comentario/412884/) 

	Cuando instalo npm-run-all me sale esto en la consola: “found 14 vulnerabilities (6 low, 5 moderate, 3 high)” y me sugiere ejecutar npm audit fix para solucionarlo, el problema es que si ejecuto eso, al parecer me desinstala pushstate-server y las tareas dejan de funcionar. Alguna idea de como solucionarlo?

	* **Juan Diego Lopez Triana** [412884] (1)

		Esas son vulnerabilidades de las dependencias instaladas que encuentra NPM. Con la mayoría de dependencias sucede, pero no es necesario solucionarlas para poder continuar con el proyecto.

* **dario_a_diaz** (1) [44842](https://platzi.com/comentario/412884/) 
Cuando instalo npm-run-all me sale esto en la consola: “found 14 vulnerabilities (6 low, 5 moderate, 3 high)” y me sugiere ejecutar npm a...

	* **Juan Diego Lopez Triana** [44842] (1)

		Esas son vulnerabilidades de las dependencias instaladas que encuentra NPM. Con la mayoría de dependencias sucede, pero no es necesario solucionarlas para poder continuar con el proyecto.

# Implementando tests [2719]

## 0070. Principales comandos [14614](https://platzi.com/clases/1411-testing-cypress/14614-principales-comandos/)

### Descripción:


En esta clase veremos algunos de los comandos principales de Cypress, según su funcionalidad, con los que podemos comenzar a definir nuestras pruebas:

**Comandos para controlar el browser**

* `cy.visit()`: para cargar una URL
* `cy.reload()`: para recargar la URL actual
* `cy.go('back')`: para ir hacia atrás o adelante en la navegación



**Comandos para selección de elementos**

* `cy.get('.selector')`: para seleccionar según un selector html / css
* `cy.contains('text)`: para seleccionar de acuerdo al contenido
* `cy.contains('.selector', 'texto')`: para seleccionar según el selector y el contenido



**Comandos para interactuar con los elementos**

* `cy.get('.selector').click()`: para hacer click sobre un elemento
* `cy.get('.selector').dblclick()`: para hacer dblclick sobre un elemento
* `cy.get('input').type()`: para escribir un texto
* `cy.get('input').clear()`: para limpiar un texto
* `cy.get('checkbox').check()`: para marcar check
* `cy.get('checkbox').uncheck()`: para quitar el check
* `cy.get('select').select('item')`: para seleccionar un item en una lista desplegable



_Cypress permite la encadenación de muchos de estos y otros comandos._

### Links:

* [as | Cypress Documentation](https://docs.cypress.io/api/commands/as.html#Syntax)

* [as | Cypress Documentation](https://docs.cypress.io/api/commands/as.html#Syntax)

### Comentarios:

* **Julianv8** (2) [428854](https://platzi.com/comentario/428854/) 

	Se puede sacar mucho provecho a estos comandos basicos y fortalecer con la documentacion que aparece en el enlace de este curso 😃

* **ingsis_john** (1) [791505](https://platzi.com/comentario/791505/) 

	Encontre esto aunque no me sirvio
	``` 
	    cy.get('iframe').iframeLoaded()
	    .its('document')
	    .getInDocument('input#user_email')
	    .type('123')
	    
	```

* **ingsis_john** (1) [791500](https://platzi.com/comentario/791500/) 

	Como puedo usar la función cy.get() con un iframe para escribir en un input que esta en un iframe?

* **Carlos Azaustre** (1) [483318](https://platzi.com/comentario/483318/) 

	Comandos para interactuar con el browser

* **Carlos Azaustre** (1) [483317](https://platzi.com/comentario/483317/) 

	Comandos para seleccionar elementos

* **Carlos Azaustre** (1) [483315](https://platzi.com/comentario/483315/) 

	Comandos para interactuar elementos

## 0080. Interactuando con elementos [14615](https://platzi.com/clases/1411-testing-cypress/14615-interactuando-con-elementos/)

### Descripción:


El _test runner_ de Cypress tiene una herramienta muy útil en la barra de menús que nos permite inspeccionar los elementos de nuestra aplicación para identificar los selectores que usaremos para definir las interacciones de nuestras pruebas.

Algo que es importante notar es que comandos como _click()_ y _dblclick()_ son asíncronos pero Cypress los ejecuta de manera síncrona o secuencial.

El comando `cy.wait()`, le indica al _browser_ que debe esperar una cantidad determinada de milisegundos antes de continuar con la ejecución del test.

Al modificar y volver a guardar los _scripts_ que definen las pruebas, Cypress vuelve a recargar el _test runner_ automáticamente ya que cuenta con una funcionalidad de _Live Reload_

### Comentarios:

* **francves17** (4) [544122](https://platzi.com/comentario/544122/) 

	Asombroso!

* **luismb** (3) [431775](https://platzi.com/comentario/431775/) 

	Deberían subir el repo pronto para consultarlo. muchas gracias

* **Facundo Fernandez** (1) [1047387](https://platzi.com/comentario/1047387/) 

	Hola, estoy haciendo el curso ya que en mi trabajo tengo que realizar un test a la app de la empresa que es muy grande.  
	La cuestion es que los ID o class de los elementos cambian con cada refresh, cambian constntemente y no puedo mapearlos correctamente ya que muchas veces el test me da error por este tema.  
	Que otra manera de mapear los elementos puedo usar?

* **Gonzalo Cofré** (1) [718789](https://platzi.com/comentario/718789/) 

	Yo tengo este error:
	
	Al ingresar a la URL <http://0.0.0.0:9000/>, el browser dice:
	
	Cannot GET /
	
	¿Alguien sabe cual puede ser el problema?
	
	La linea de comando que uso es:  
	“test:server”: “pushstate-server dist”

	* **motatin** [718789] (1)

		Intenta cambiar en el package.json esa linea de “test:server”:“pushstate-server dist” por la siguiente linea:
		
		“test:server”: “pushstate-server -d ./dist”

* **luismb** (1) [46466](https://platzi.com/comentario/431775/) 
Deberían subir el repo pronto para consultarlo. muchas gracias

## 0090. Aserciones [14616](https://platzi.com/clases/1411-testing-cypress/14616-aserciones/)

### Descripción:


Una **aserción** es lo que nos permite comprobar si el _test_ está bien o no. Mientras no se hayan definido aserciones para nuestros _tests_ , todos van a pasar como válidos.

Cypress utiliza _ChaiJS_ para definir las aserciones. Estas pueden ser principalmente de dos tipos: **BDD** para definir comportamientos esperados y **TDD** para _Test Driving Development_.

Para nuestro proyecto utilizaremos únicamente las aserciones de comportamiento BDD por su facilidad y conveniencia. Las aserciones se pueden encadenar a los selectores.

Para usar las aserciones en la definición de las pruebas se deben encadenar con el método _.should( <aserción>)_, por ejemplo: `cy.get('.selector').should('not.exists')`, para indicar que el elemento definido por .selector no debería estar presente en el DOM; o `cy.get('.selector').should('be.visible')` para indicar que sí debería existir y estar visible.

### Links:

* [Chai](https://www.chaijs.com/)

### Comentarios:

* **Delsa Mendez** (2) [566108](https://platzi.com/comentario/566108/) 

	[chaijs.org](http://chaijs.org) no dirige a ningún lugar.  
	Querrás decir <https://www.chaijs.com/> ?

	* **Jhon Alexander Perez Valencia** [566108] (2)

		sip estas en lo correcto😉 es <https://www.chaijs.com/>

	* **mariandrea (Platzi)** [566108] (1)

		hola, tienen toda la razón! muchas gracias por reportarlo. Ya quedó corregido en la pestaña de recursos 😃

* **bewe** (1) [926360](https://platzi.com/comentario/926360/) 

	<https://docs.cypress.io/guides/references/assertions.html#Chai>

* **Delsa Mendez** (0) [57515](https://platzi.com/comentario/566108/) 
chaijs.org no dirige a ningún lugar. Querrás decir https://www.chaijs.c...

	* **Jhon Alexander Perez Valencia** [57515] (2)

		sip estas en lo correcto😉 es <https://www.chaijs.com/>

## 0100. Hooks [14617](https://platzi.com/clases/1411-testing-cypress/14617-hooks/)

### Descripción:


Cypress incluye los _Hooks_ de acuerdo a las definiciones y casos de uso definidos por el _framework_ de pruebas _Mocha_ , del cual los adopta.

Los _Hooks_ son funciones o métodos que se ejecutan en determinados momentos del flujo de ejecución de los _tests_.

Los que usaremos en nuestro proyecto son:

* **before()** : es una función que se ejecuta una vez antes de la ejecución de todos los _tests_ del mismo grupo.
* **beforeEach()** : es una función que se ejecuta antes de cada _test_ individual.
* **afterEach()** : es una función que se ejecuta después de cada _test_ individual.
* **after()** : es una función que se ejecuta una vez, al finalizar la ejecución de todos los _tests_ del mismo grupo.



Opcionalmente, se puede incluir el método **.skip()** , encadenado a alguna de las definiciones de _test_ de la siguiente manera: `it.skip( ... )`, para indicar a Cypress que este _test_ se omitirá durante la ejecución.

Comparte con tus compañeros en la sección de discusiones de la clase, en qué otras situaciones consideras que serían útiles los _Hooks_ de Cypress.

### Links:

* [Mocha - the fun, simple, flexible JavaScript test framework](https://mochajs.org)

* [Bundled Tools | Cypress Documentation](https://docs.cypress.io/guides/references/bundled-tools.html#Mocha)

### Comentarios:

* **Luis Valles** (2) [775417](https://platzi.com/comentario/775417/) 

	Podrías usar el hook before para hacer fetch a un recurso que compartan todas las pruebas.  
	Por ejemplo, podrías traer datos de la api de jsonplaceholder, para traer nombre, título, email y contraseña de manera predefinida.  
	Claro, puede hacerse con un fixture, pero no he llegado a ese video aún.

* **orivasm44** (2) [446186](https://platzi.com/comentario/446186/) 

	Hay alguna forma de exportar todos los casos de éxito y los casos fallidos a un archivo??

* **Brayan Laureano Paucar** (1) [948939](https://platzi.com/comentario/948939/) 

	excelente, aprendi mucho en este video

* **bewe** (1) [926370](https://platzi.com/comentario/926370/) 

	<https://docs.cypress.io/guides/references/bundled-tools.html#Mocha>

* **lm3232** (1) [755455](https://platzi.com/comentario/755455/) 

	a alguien más no le funcionó el comando after?

* **dario_a_diaz** (1) [413191](https://platzi.com/comentario/413191/) 

	La idea es muy similar a cuando escribes tests con JUnit en java usando los metodos setup and teardown 😃

## 0110. Variables, Fixtures y Alias [14618](https://platzi.com/clases/1411-testing-cypress/14618-variables-fixtures-y-alias/)

### Descripción:


Debido a que Cypress es asíncrono, la forma de definir y usar _variables_ en el código de los _tests_ es diferente a como se hace regularmente en JavaScript.

Los **fixtures** son estructuras u objetos _JSON_ definidos en archivos individuales que se pueden reutilizar en cualquier momento de la secuencia de ejecución de los _tests_. Para poder hacer referencia a ellos posteriormente es necesario asignarles un _alias_.

La forma de incorporar un _fixture_ en cada uno de los _tests_ , sería incorporándolo en el _Hook_ **beforeEach()** de la manera siguiente:
``` 
    cy.fixture(<archivo.json>).as(<alias>)
    
```

y para poder hacer uso de éste, se le debe asignar un _alias_ :
``` 
    cy.get('@alias').then( ( var ) => {
      // ---- en este ámbito ya se puede usar como una variable más
      ...
      cy.get('input').type( var )
      ...
    })
    
```

Al usar el símbolo “”@"" en el selector, se hace referencia a una variable ( _fixture_ ) y no a un elemento de la interfaz.

_NOTA: Ten en cuenta que las funciones de Cypress no regresan un valor en sí mismas, ya que internamente funcionan de manera asíncrona._

### Links:

* [Variables and Aliases | Cypress Documentation](https://docs.cypress.io/guides/core-concepts/variables-and-aliases.html)

* [fixture | Cypress Documentation](https://docs.cypress.io/api/commands/fixture.html#Syntax)

### Comentarios:

* **Carlos Azaustre** (2) [483382](https://platzi.com/comentario/483382/) 

	Usando fixtures

* **Julianv8** (2) [428919](https://platzi.com/comentario/428919/) 

	Cuando ejecutes los test nuevamente debes asegurarte de haber “cerrado la sesion” de ejecuciones anteriores, de lo contrario lo que hara es cargar el “‘a’,‘Dashboard’” sin importar que usuario acutalmente este intentando el logueo, el test aparecera aprobado pero enrealidad esta viendo el Dashboard de una cuenta ya logueada.

* **Juan Diego Lopez Triana** (2) [414784](https://platzi.com/comentario/414784/) 

	Hay alguna forma de usar async/await en vez de anidar codigo con .then() ?

	* **edsadr** [414784] (2)

		el. problema es que los comandos de cypress siguen el paradigma de chainable pero no son promesas estándar por lo tanto el uso de async await es restringido, mira este artículo sobre el tema <https://medium.com/@NicholasBoll/cypress-io-using-async-and-await-4034e9bab207>

	* **Juan Diego Lopez Triana** [414784] (1)

		Gracias

* **Monts27** (1) [82416](https://platzi.com/comentario/1004778/) 
¿Por que no puedo puedo simplemente crear la variable const user = {...}? No veo porque eso no deba funcionar, al final es código Java sc...

# Conceptos avanzados [2720]

## 0120. Ejecución de scripts [14619](https://platzi.com/clases/1411-testing-cypress/14619-ejecucion-de-scripts/)

### Descripción:


En esta clase incorporaremos a nuestro _testing_ un _script_ de NodeJS que eliminará de la base de datos de Firebase los registros de usuario creados en cada ejecución, para evitar que falle el _test_ por error de usuario duplicado. Tendremos que correr este _script_ mediante una instrucción _shell_ antes de la ejecución de cada _testing_ de Cypress.

Para que el _script_ funcione correctamente será necesario instalar **firebase-admin** con `npm i firebase-admin -D` y colocar en el archivo `firebase-admin-keys.json` las credenciales de acceso al proyecto proporcionadas por Firebase en la sección Cuentas de Servicio.

Finalmente creamos un nuevo _script_ en el archivo de configuraciones de _webpack_ llamado `test:clean` con la siguiente línea de comandos: `cd build && node clean-test-db.js` y lo ejecutamos desde el _Hook_ **before()** en el archivo de definiciones de nuestros _tests_ utillizando la función `cy.exec('npm run test:clean')`. También se pueden ejecutar comandos de tipo _shell_ o _scripts_ externos, con la función `cy.task(...)` de Cypress.

### Links:

* [exec | Cypress Documentation](https://docs.cypress.io/api/commands/exec.html#Syntax)

* [task | Cypress Documentation](https://docs.cypress.io/api/commands/task.html#Syntax)

### Comentarios:

* **José Luis García Peceros** (1) [1019945](https://platzi.com/comentario/1019945/) 

	No se por que mi test no se ejecuta por completo:  
	![2020-03-04_00h34_24.png](https://static.platzi.com/media/user_upload/2020-03-04_00h34_24-d695e470-2e16-4731-83ae-505cb7a2cc95.jpg)

* **Diego Fernando Castillo Osorio** (1) [797219](https://platzi.com/comentario/797219/) 

	Cuando agrego la ejecucion del script cy.exec(‘npm run test:clean’) al hook before falla por lo siguiente:
	``` 
	    CypressError: cy.exec('npm run test:clean') failed because the command exited with a non-zero code.
	    
	    Pass {failOnNonZeroExit: false} toignoreexitcodefailures.
	    
	    Information about the failure:
	    Code: 243
	    
	```

* **Gonzalo Cofré** (1) [720427](https://platzi.com/comentario/720427/) 

	Al ejecutar me lanza el siguiente error:
	
	> platzi-posts@1.0.0 test:clean /opt/lampp/htdocs/Platzi/Cypress/platzi-posts  
	>  cd build && node clean-test-db.js
	
	(node:19968) ExperimentalWarning: The http2 module is an experimental API.  
	(node:19968) UnhandledPromiseRejectionWarning: Error: @grpc/grpc-js only works on Node ^8.13.0 || >=10.10.0  
	at Object.<anonymous> (/opt/lampp/htdocs/Platzi/Cypress/platzi-posts/node_modules/@grpc/grpc-js/build/src/index.js:47:11)  
	at Module._compile (module.js:652:30)  
	at Object.Module._extensions…js (module.js:663:10)  
	at Module.load (module.js:565:32)  
	at tryModuleLoad (module.js:505:12)  
	at Function.Module._load (module.js:497:3)  
	at Module.require (module.js:596:17)  
	at require (internal/module.js:11:18)  
	at Object.<anonymous> (/opt/lampp/htdocs/Platzi/Cypress/platzi-posts/node_modules/google-gax/build/src/grpc.js:37:14)  
	at Module._compile (module.js:652:30)  
	(node:19968) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). (rejection id: 1)  
	(node:19968) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.

	* **Luis Valles** [720427] (2)

		Estoy leyendo el output de tu error, tal parece que se trata de un problema de versiones, específicamente del salto entre Node 8.13.0 en adelante.  
		Trata de instalar **nvm** en tu entorno, y cambia la versión actual al node 8.13 o la 8.16

* **jlenciso** (1) [465740](https://platzi.com/comentario/465740/) 

	Al correr el comando me muestra este error:  
	Error listing users: { Error: Error while making request: url.URL is not a constructor. Error code: undefined  
	at FirebaseAppError.Error (native)  
	at FirebaseAppError.FirebaseError [as constructor] (C:\Users\Z055744\Desktop\platzi-posts\node_modules\firebase-admin\lib\utils\error.js:39:28)  
	at FirebaseAppError.PrefixedFirebaseError [as constructor] (C:\Users\Z055744\Desktop\platzi-posts\node_modules\firebase-admin\lib\utils\error.js:85:28)  
	at new FirebaseAppError (C:\Users\Z055744\Desktop\platzi-posts\node_modules\firebase-admin\lib\utils\error.js:119:28) at C:\Users\Z055744\Desktop\platzi-posts\node_modules\firebase-admin\lib\utils\api-request.js:123:19  
	at process._tickDomainCallback (internal/process/next_tick.js:135:7)  
	errorInfo:  
	{ code: ‘app/network-error’,  
	message: ‘Error while making request: url.URL is not a constructor. Error code: undefined’ },  
	codePrefix: ‘app’ }
	
	solo se borran las colecciones pero no se borran los usuarios.
	
	Ayuda con este tema muchas gracias!

## 0130. Comandos personalizados [14620](https://platzi.com/clases/1411-testing-cypress/14620-comandos-personalizados/)

### Descripción:


En esta clase aprenderemos a crear **comandos personalizados** con Cypress. La idea es que cada conjunto o suite de _tests_ sea independiente entre sí; sin embargo, hay ocasiones en que varios _tests_ o _grupos de tests_ requieren ejecutar instrucciones comunes. Los **comandos personalizados** son una manera muy conveniente de agrupar varias instrucciones para reutilizarlas o compartirlas entre diferentes lugares de nuestro flujo de _testing_ en una o varias _suites_.

La definición de los comandos personalizados se hace en el archivo `comands.js` en la carpeta `/support` de la siguiente manera:
``` 
    Cypress.Commands.add( 'miComandoPersonalizado', ( <params> ) => { 
      // --- instrucciones comunes agrupadas como comando personalizado
      ...
    } )
    
```

luego para hacer uso del comando personalizado, se debe invocar como cualquier método propio de Cypress: `cy.miComandoPersonalizado( <params> )`.

### Links:

* [Custom Commands | Cypress Documentation](https://docs.cypress.io/api/cypress-api/custom-commands.html#Syntax)

### Comentarios:

* **elianarubio** (2) [783101](https://platzi.com/comentario/783101/) 

	Es una herramienta muy útil y fácil de usar, luego de varios intentos de correr el proyecto y no lograrlo, estoy probando con una web de en la que tengo control.

* **orivasm44** (2) [447545](https://platzi.com/comentario/447545/) 

	Hasta el momento me parece una muy buena herramienta para crear mis pruebas automatizadas, aunque el código para utilizar firebase da errores hay que hacer ajustes para que corra de manera correcta.

* **Alexis Otaño** (1) [1026971](https://platzi.com/comentario/1026971/) 

	Creacion de comandos personalizados

## 0140. Variables de entorno y configuración [14621](https://platzi.com/clases/1411-testing-cypress/14621-variables-de-entorno-y-configuracion/)

### Descripción:


### Links:

* [Environment Variables | Cypress Documentation](https://docs.cypress.io/guides/guides/environment-variables.html)

### Comentarios:

* **jlenciso** (2) [462390](https://platzi.com/comentario/462390/) 

	Hola Adrián, muchas gracias por el curso.
	
	Muy útiles las variables de entorno. Al respecto de esta prueba de crear un post, identifico un detalle en el test al momento de aplicar el .type(Cypress.env(‘postContent’)) se inserta el texto en el textarea pero después de dar clic en el botón “Crear” el resultado esperado es que se limpie o refresque el textarea sinembargo el resultado actual es que se mantiene el texto insertado en el textarea despues de dar clic en el botón de “Crear”.
	
	Mismo comportamiento si no se utiliza variable de entorno:  
	cy.get(‘textarea’).type(‘Hola esta es una prueba de post’)  
	Se mantiene el texto insertado en el textarea.
	
	Lo mismo ocurre en el video de la prueba que realizas. Y al parecer este comportamiento es momentaneo despues de un minuto se refresca el textarea. Para temas de screenshot tendríamos que esperar a que se refresque el textarea y despues tomar el screenshot ¿Es posible realizar una validación antes de tomar el screenshot?.
	
	Saludos y gracias!

	* **edsadr** [462390] (1)

		Al ser una app reactiva, tendrias que añadir una espera prudencial antes del screenshot depende mucho de la latencia con Firebase

* **Cesar Becerra** (1) [441282](https://platzi.com/comentario/441282/) 

	muy buen curso 😃 ya uso cypress en mi empresa pero esto lo uso para reforzar conocimientos

* **Jhonny Córdova** (1) [414208](https://platzi.com/comentario/414208/) 

	Hola. Tengo un problema con el test de post. Cypress me informa lo siguiente:
	
	**Uncaught FirebaseError: Function DocumentReference.set() called with invalid data. Unsupported field value: undefined (found in field userName)
	
	This error originated from your application code, not from Cypress.
	
	When Cypress detects uncaught errors originating from your application it will automatically fail the current test.
	
	This behavior is configurable, and you can choose to turn this off by listening to the ‘uncaught:exception’ event.**
	
	Así se ve el test. Qué no estoy viendo?
	``` 
	    it('Debe crear un post', () => {
	            cy.get('@userData').then((userData) => {
	                cy.get('textarea').type(Cypress.env('postContent'))
	                
	                cy.contains('button', 'Crear').as('botonCrear')
	                cy.get('@botonCrear').should('be.enabled')
	                cy.get('@botonCrear').click()
	    
	                cy.contains('.col2 h5', userData.name).should('be.visible')
	                cy.contains('p', Cypress.env('postContent')).should('be.visible')
	    
	            })
	        })
	    
	```

	* **edsadr** [414208] (1)

		Podria ser un problema de red, recuerda que esto usa internet para comunicarse con Firebase, verifica

* **dario_a_diaz** (1) [413872](https://platzi.com/comentario/413872/) 

	Se que es un poco básica la pregunta, pero el wait, espera los 3 segundos siempre? o si se carga antes continua con el siguiente step/test?

	* **AngelM** [413872] (0)

		El hook before() ejecutará todas las instrucciiones que pongas dentro de él antes de iniciar con la suit de tests, a diferencia de beforeEach() que se ejecutará una vez por cada test dentro de tu suit de tests.

	* **edsadr** [413872] (1)

		los 3 segundos los agregamos como un tiempo prudencial para esperar la interacción de firebase y el rendering, es un tiempo fijo que firebase va a esperar siempre asi se cargue antes

* **jlenciso** (1) [49074](https://platzi.com/comentario/462390/) 
Hola Adrián, muchas gracias por el curso. Muy útiles las variables de entorno. Al respecto de esta prueba de crear un post, identifico un...

	* **edsadr** [49074] (1)

		Al ser una app reactiva, tendrias que añadir una espera prudencial antes del screenshot depende mucho de la latencia con Firebase

* **Jhonny Córdova** (1) [44972](https://platzi.com/comentario/414208/) 
Hola. Tengo un problema con el test de post. Cypress me informa lo siguiente: **Uncaught FirebaseError: Function DocumentReference.set() ...

	* **edsadr** [44972] (1)

		Podria ser un problema de red, recuerda que esto usa internet para comunicarse con Firebase, verifica

* **dario_a_diaz** (1) [44928](https://platzi.com/comentario/413872/) 
Se que es un poco básica la pregunta, pero el wait, espera los 3 segundos siempre? o si se carga antes continua con el siguiente step/test?

	* **AngelM** [44928] (0)

		El hook before() ejecutará todas las instrucciiones que pongas dentro de él antes de iniciar con la suit de tests, a diferencia de beforeEach() que se ejecutará una vez por cada test dentro de tu suit de tests.

* **Monts27** (0) [82555](https://platzi.com/comentario/1007718/) 
No entiendo que ventaja tiene el usar fixtures, yo podria declarar un objeto plano de JS con la info del usuario al inicio del codigo po...

## 0150. Screenshots [14622](https://platzi.com/clases/1411-testing-cypress/14622-screenshots/)

### Descripción:


Con la función `cy.screenshot( , {  } )` es posible tomar un captura o _screenshot_ de la pantalla o interfaz de nuestra aplicación en cualquier momento durante la ejecución del _testing_.

Esta funcionalidad permite algunas opciones de configuración muy útiles como: **blackout** para ocultar elementos o información que no deba ser expuesta en la captura, **clip** para recortar y capturar sólo una región de la interfaz, **capture: ‘fullPage’** para hacer una captura de toda la página y no solo lo visible en el viewport del navegador, entre otras.

Los archivos de las imágenes capturadas (con formato png) son guardados en subcarpetas identificadas con el nombre de la suite de _tests_ en ejecución, dentro del directorio `/screenshots` creado automáticamente por Cypress.

Es recomendable excluir los _screenshots_ del repositorio github agregando la carpeta correspondiente al archivo `.gitignore.`

### Links:

* [screenshot | Cypress Documentation](https://docs.cypress.io/api/commands/screenshot.html)

### Comentarios:

* **Gonzalo Cofré** (2) [722096](https://platzi.com/comentario/722096/) 

	Cuando vuelvo a ejecutar el test me crea los archivos create-user(1).png, login-failed(1).png y login-user(1).png.
	
	Mi consulta es, ¿No sobreescribe, sino que luego de ejecutar más test, aumentarán los screenshot con valores 2, 3, n?

* **Jhonny Córdova** (2) [414491](https://platzi.com/comentario/414491/) 

	RangeError: Index out of range
	
	Obtengo ese error cuando Cypress intenta hacer los screenshots 😦

	* **edsadr** [414491] (1)

		que version de Node estas usando?

* **Jhonny Córdova** (2) [45011](https://platzi.com/comentario/414491/) 
RangeError: Index out of range Obtengo ese error cuando Cypress intenta hacer los screenshots 😦

	* **edsadr** [45011] (1)

		que version de Node estas usando?

* **Jean Carlos Nuñez Hernandez** (1) [606353](https://platzi.com/comentario/606353/) 

	Buena esta de los screenshut, esta espectacular

* **grupocentrico** (1) [65453](https://platzi.com/comentario/691959/) 
Mi pregunta es: Porqué el fixture(‘user.json’) se ubica en el beforeEach() y no en el before()?

* **grupocentrico** (1) [65452](https://platzi.com/comentario/691958/) 
Mi pregunta es: Porqué el fixture(‘user.json’) se ubica en el beforeEach() y no en el before()? Creería que la data del usuario que está ...

## 0160. Stubs, Spies y Clocks [14623](https://platzi.com/clases/1411-testing-cypress/14623-stubs-spies-y-clocks/)

### Descripción:


En esta clase veremos algunos conceptos y funcionalidades que están relacionados propiamente con End-to-end Testing, pero que están disponibles en Cypress y pudieran sernos de utilidad en alguna ocasión.

* **Stubs** : proporciona una manera programática de simular, sustituir o tomar control del comportamiento esperado de funciones o eventos que suceden en la interfaz de nuestra aplicación.
* **Spies** : permiten intervenir en los llamados a funciones para determinar si fueron llamadas durante la ejecución del _testing_ y qué parámetros recibieron en esa llamda.
* **Clocks** : proporciona una forma de alterar programáticamente la hora y fecha del entorno durante la ejecución del _testing_.



_NOTA; No se recomienda el uso de estas funcionalidades cuando se realiza End-to-end testing, particularmente con Firebase, ya que pudieran generar comportamientos inesperados y no deseados como resultado de las pruebas. Estas funcionalidades son más útiles para pruebas de otro tipo._

### Links:

* [Stubs, Spies, and Clocks | Cypress Documentation](https://docs.cypress.io/guides/guides/stubs-spies-and-clocks.html)

### Comentarios:

* **Brayan Laureano Paucar** (1) [949206](https://platzi.com/comentario/949206/) 

	excelente, estos comandos no los había escuchado, siempre es bueno aprender algo nuevo

* **Luis Valles** (1) [70970](https://platzi.com/comentario/786625/) 
¿Cuál librería puedo aplicar para generar datos de prueba y usarlos en mi end-to-end testing?

	* **omiguelperez** [70970] (1)

		[Faker](https://www.npmjs.com/package/faker)

## 0170. Depuración de los tests [14624](https://platzi.com/clases/1411-testing-cypress/14624-depuracion-de-los-tests/)

### Descripción:


Cyrpress provee dos herramientas para hacer depuración durante la ejecución de los _tests_ :

* **debugger** que detiene la ejecución del código y permite el acceso a la consola de inspección tanto en el código de los _tests_ como de la aplicación que estamos probando.
* **.debug()** que es una función encadenable a cualquier otra función de Cypress, y que al igual que `debugger`, permite la depuración del código durante la ejecución de un flujo de pruebas.



### Links:

* [Debugging | Cypress Documentation](https://docs.cypress.io/guides/guides/debugging.html#Using-debugger)

### Comentarios:

* **Julianv8** (4) [441227](https://platzi.com/comentario/441227/) 

	He seguido los pasos pero, en el test no se detiene para ver el debug

	* **santimontiel** [441227] (4)

		Para que funcione se debe tener el developer tools abierto.
		
		Saludos!

* **Jean Carlos Nuñez Hernandez** (2) [606359](https://platzi.com/comentario/606359/) 

	debbuger en cypress esta muy bueno nos permite ver que pasa en ese momento, todas la ssesiones son secuenciales

* **Julianv8** (1) [47310](https://platzi.com/comentario/441227/) 
He seguido los pasos pero, en el test no se detiene para ver el debug

	* **santimontiel** [47310] (4)

		Para que funcione se debe tener el developer tools abierto.
		
		Saludos!

## 0180. Headless testing [14625](https://platzi.com/clases/1411-testing-cypress/14625-headless-testing/)

### Descripción:


Cuando estamos realizando _End-to-end testing_ en un ambiente real de producción, por lo general no tenemos acceso a la interfaz gráfica del servidor. En estos casos se hace necesario entonces tener la posibilidad de ejecutar todo el flujo de pruebas como lo hemos definido, pero sin la simulación visual de lo que sucede en el navegador durante todo el proceso. Para esto, Cypress dispone de la funcionalidad **Headless testing**.

El cambio necesario para realizar un **Headless testing** es básicamente la sustitución del argumento `open` por `run`, en la ejecución del _script_ de Cypress en las configuraciones del archivo `package.json`, quedando los _scripts_ de la siguiente manera:
``` 
    ""cypress:run"": ""cypress run --project ./test"",
    ...
    ""test"": ""npm run build:test && run-p --race test:server cypress:run"",
    
```

Al ejecutar `npm run test` ya no se ejecutará en el _test runner_ de Cypress sino en un navegador interno sin interfaz gráfica; sin embargo, Cypress registrará toda la ejecución en un video que guardará en la carpeta `/videos` en el sistema de archivos del servidor además de mostrar todas las salidas del proceso en la terminal de línea de comandos.

Al igual que como sucede con los _screenshots_ la recomendación es que la carpeta `/videos` se excluya del repositorio Git a través del `.gitignore` para evitar un uso innecesario de recursos adicionales del servidor.

### Links:

* [Command Line | Cypress Documentation](https://docs.cypress.io/guides/guides/command-line.html#Commands)

### Comentarios:

* **Delsa Mendez** (1) [567043](https://platzi.com/comentario/567043/) 

	Tengo problemas con los vídeos generados. Al reproducir los vídeos, estos corren hasta cierta duración, después se quedan colgados y no muestran el proceso como tal.

	* **Diego Alexander Forero Higuera (Platzi)** [567043] (2)

		Hola, que navegador usas?, puedes probar cambiando el servidor de video en el icono de engrane en el player.

* **bewe** (1) [60999](https://platzi.com/comentario/614511/) 
una pregunta lo que pasa es que inicio mis test en el entorno grafico y corren a la perfección pero en headless corren en electron, com...

# Bonus [2721]

## 0190. Testing condicional [14626](https://platzi.com/clases/1411-testing-cypress/14626-testing-condicional/)

### Descripción:


El **Testing condicional** es aquel en el que las pruebas están sujetas a valores o condiciones de la interfaz que no son inmutables, textos o contenidos de elementos del DOM, fecha y hora, entre otros. Es una práctica que se debe evitar en la mayoría de los casos, ya que puede conducir a resultados inconsistentes tambén conocidos como **flaky tests** en los que, para configuraciones y estados constantes, se obtienen resultados distintos e impredecibles.

Lo recomendable, en el caso de que se requiera obligatoriamente definir diferentes rutas de pruebas basadas en condiciones del entorno, es apoyarse en datos como _cookies_ , _variables de sesión_ , datos almacenados en el _LocalStorage_ , entre otros.

### Links:

* [Conditional Testing | Cypress Documentation](https://docs.cypress.io/guides/core-concepts/conditional-testing.html)

### Comentarios:

* **WilliamVelazquez** (1) [979936](https://platzi.com/comentario/979936/) 

	Me parece que aunque no sea lo más recomendable, deberían hacer algún ejemplo en caso de que alguien requiera ver dicha implementación

## 0200. Plugins [14627](https://platzi.com/clases/1411-testing-cypress/14627-plugins2551/)

### Descripción:


Cypress cuenta con una API propia que facilita la incorporación de **Plugins** , propios o de terceros.

Entre los Plugins oficiales disponibles para extender las funcionalidades de Cypress se encuentran: Browserify, ESLint, Webpack, Cucumber, Docker, TypeScript, entre otros.

En los archivos creados al instalar Cypress está uno que sirve de base para la creación de plugins personalizados, ubicado en la carpeta `/plugins`.

### Links:

* [Plugins | Cypress Documentation](https://docs.cypress.io/plugins)

* [Plugins | Cypress Documentation](https://docs.cypress.io/guides/tooling/plugins-guide.html)

### Comentarios:

* **Sergio Renaud Santiago** (2) [510804](https://platzi.com/comentario/510804/) 

	Estaba probando el plugin browser:launch y si funciona el pugin, el tema es que ya no puede cargar <http://localhost:9000>, alguien podría ayudarme?

* **Sergio Renaud Santiago** (1) [52878](https://platzi.com/comentario/510804/) 
Estaba probando el plugin browser:launch y si funciona el pugin, el tema es que ya no puede cargar http:/...

## 0210. Intellisense [14646](https://platzi.com/clases/1411-testing-cypress/14646-intellisense/)

### Descripción:


### Links:

* [Intelligent Code Completion | Cypress Documentation](https://docs.cypress.io/guides/tooling/intelligent-code-completion.html)

### Comentarios:

## 0220. Seguridad [14628](https://platzi.com/clases/1411-testing-cypress/14628-seguridad/)

### Descripción:


Sólo se puede usar un único dominio para todos los _tests_ que se hayan definido en un conjunto de pruebas en Cypress. No obstante, es posible usar diferentes subdirectorios o subcarpetas para dicho dominio, sin ningún inconveniente.

En el caso en que sea estrictamente necesario realizar un _testing_ hacia otro dominio diferente al propio, existen algunas formas de deshabilitar esta restricción, pero esto es algo que no se recomienda hacer ya que al deshabilitar estas restricciones de seguridad queda expuesto el entorno, y hay un alto riesgo de ser victima de diversos tipos de ataques maliciosos. Se aconseja siempre buscar formas alternativas que incluyan algunas de las funcionalidades que hemos aprendido durante el curso como son los redireccionamientos con JavaScript, **scubs** , **spies** , etc.

### Links:

* [Web Security | Cypress Documentation](https://docs.cypress.io/guides/guides/web-security.html)

### Comentarios:

* **WilliamVelazquez** (2) [979963](https://platzi.com/comentario/979963/) 

	Me parecería bueno incluir aunque sea un ejemplo sencillo en caso de que se llegue a necesitar hacer algo similar

	* **Monts27** [979963] (2)

		Las ultimas clases no ha habido ejemplos

	* **WilliamVelazquez** [979963] (1)

		Justo a eso me refiero

* **Monts27** (1) [1019268](https://platzi.com/comentario/1019268/) 

	No creo que sea correcto que nos digas, “aquí te dejo una guía para que puedas ver como se hace”, de esa manera no hay ninguna diferencia entre un curso/clase/lección a solo ver el temario y buscar nosotros en la documentación
	
	Por favor profundicen más en los conceptos y nos gustaría ver ejemplos de estas implementaciones, no solo darnos links a documentación que de por si ya están pública

* **xergioalex** (1) [1004535](https://platzi.com/comentario/1004535/) 

	Saludos, tengo una aplicación en la que quiero probar el onboarding de usuarios, y para ellos necesito hacer un oauth contra Slack y Google, por lo tanto necesito poder ir a autenticarme en dichos servicios y volver a la aplicación para continuar con el flujo. Esto lo he pensado automatizar como una prueba end to end, pero con base a está restricción si podría hacerlo? Entiendo que podria desactivar la seguridad para lograrlo pero pues con base a este video no es lo ideal.

## 0230. Usando el dashboard de Cypress [14629](https://platzi.com/clases/1411-testing-cypress/14629-usando-el-dashboard-de-cypress/)

### Descripción:


Cypress también cuenta con una plataforma en línea. Esta plataforma incluye un servicio llamado **Dashboard** , que te permite almacenar en la nube los archivos generados por tus _testings_ para cualquier proyecto de tipo _público_. Ofrece también una alternativa de pago para proyectos _privados_ que requiere un registro y algunos pasos adicionales.

Tanto la versión gratuita como la versión de pago disponen de toda la organización y un sistema de reportes similares a la consola que hemos ejecutado hasta ahora de forma local.

### Links:

* [Next-level test management for your teams.
  ](https://www.cypress.io/dashboard)

### Comentarios:

## 0240. Conclusiones [14630](https://platzi.com/clases/1411-testing-cypress/14630-conclusiones5563/)

### Descripción:


¡Felicidades por llegar al final de este curso!

Cypress es una gran herramienta que hace un trabajo muy complejo, como lo es el _End-to-end testing_ , de una forma muy sencilla y con unos resultados muy útiles e interesantes.  
Espero que a partir de ahora te animes a integrarlo en tus proyectos para mejorar la calidad general y su nivel de madurez, y así ofrecen los mejores resultados a tus clientes y usuarios finales.

### Comentarios:

* **orivasm44** (3) [449212](https://platzi.com/comentario/449212/) 

	Gracias @Adrián el curso esta muy bueno ya comencé a integrarlo en el equipo de trabajo, saludos.

* **bewe** (2) [585917](https://platzi.com/comentario/585917/) 

	Gracias @Adrián muchas este curso fue de mucha ayuda recomendado

* **Brayan Laureano Paucar** (1) [949252](https://platzi.com/comentario/949252/) 

	Excelente curso, ahora toca seguir aprendiendo

* **Massimo Di Berardino** (1) [824490](https://platzi.com/comentario/824490/) 

	muy bueno y practico el curso, solo de parte de platzi deberian arreglar el zip del proyecto porque apenas lo bajas tienes que hacer unas cuantas cosas para arreglarlo

* **EduardoSanMartinHernandez** (1) [777678](https://platzi.com/comentario/777678/) 

	Exelente curso @Adrián

* **GerAlfonso** (1) [658103](https://platzi.com/comentario/658103/) 

	Muy buen curso. Gracias @Adrián!!!

