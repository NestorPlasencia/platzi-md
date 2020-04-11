# Conceptos básicos de Webpack

## 0010. Bienvenida al curso

### Descripción:


¡Te damos la bienvenida al Curso de Webpack 4!

Leonidas Esteban es **Frontend Chapter Lead** en @GrowMobility además de **Google Developer Expert** y **Best Platzi Teacher**. Él es tu profesor en este curso donde aprenderás cómo usar Webpack para empaquetar tus dependencias tanto en ambientes de producción como desarrollo.

No es requisito para tomar el curso pero te recomendamos revisar la Carrera de [Arquitectura Frontend](https://platzi.com/arquitecto/) y tomar cursos como los de **Angular** , **React** y **Vue**.

Recuerda que cualquier duda puedes usar nuestro sistema de discusiones. ¡Nunca pares de aprender!

### Links:

* [  LeonidasEsteban
 - YouTube](https://youtube.com/leonidasesteban)

* [Curso de Webpack | Platzi | Materiales](https://platzi.com/clases/webpack-3/)

### Comentarios:

* **Johan Manuel Perez Soto** (19)

	
	:v :v  
	![](https://dok7xy59qfw9h.cloudfront.net/568/589/467/-299996997-1tmpk57-10h9m9cf59in5p0/original/file.jpg)

	* **Johan Nieto** (7)

		
		el profe leonidas es el “undertale” de los profesores de platzi, lo amas y lo odias las 2 al mismo tiempo XD

	* **juanyut** (2)

		
		F

	* **Cristhian Hernandez** (4)

		
		Leonidas, da todos los cursos al parecer jajaja

* **Rocio Calderon Hernandez** (11)

	
	Cada vez que empiezo un curso y veo que el profe es Leonidas…suspiro aliviada…menos mal, me voy a enterar de todo!!

* **Hebert de León** (10)

	
	No puede ser, pensé que por fin me habría librado de Leonidas :l

* **Manuel Ojeda** (6)

	
	Es un honor tenerte de vuelta sensei!

* **Martin Viera** (5)

	
	Cámbienle el nombre, no se debería llamar más Platzi, se debería llamar Leotzi, Platznidas, Leonidas Platzteban o algo parecido. Uno de los mejores profes sin dudas.

* **juanvalero252** (5)

	
	El mejor profesor de Platzi (por mucho) Su metodología para enseñar es rica en metodologías de estudio, enseña desde cero sin asumir que los estudiantes deben saber algún termino o definición. si Leonidas diera todos los cursos de platzi serian millonarios

* **Xavier Alexandro Basir Jeffrey** (5)

	
	Es un honor ver otro curso con Leonidas 😄

* **georgehossa** (5)

	
	Welcome back @Leonidas ya era hora de tener un nuevo curso con vos!! espero actualizar y consolidar varios conocimientos adquiridos en el curso anterior.

* **Mariana Valencia** (4)

	
	Momento de aprender webpack!

* **Byron Miguel Piedrahita Hernandez** (4)

	
	Autodidacta super emocionado como todo un ingeniero 10x… 😛

* **Luis Miguel Rodriguez** (4)

	
	Aquí inicia mi carrera con React.JS 😃

* **Rodrigo Salazar Osnaya** (3)

	
	No sé qué sucederá pero estoy muy nervioso :v  
	A aprender cosas nuevas!

* **edwintrumpet** (3)

	
	Qué bien ese reconocimiento de Platzi al profe, muy buen profe definitivamente.  
	Hace rato estaba esperando el curso.

* **christian-magro-perez** (2)

	
	Sigue así, felicidades Leonidas

* **Yennifer Hurtado Arce** (2)

	
	jaja me encanta tu energía!! ❤️

* **carlos_sanchez** (2)

	
	Esto no me lo esperaba! Un nuevo curso de Leo en Platzi!!

* **ajosue98** (2)

	
	Genial, Leonidas Esteban  
	Super motivado por aprender esta nueva tecnología 😄

* **GuillermoLoza** (2)

	
	Siiii, webpack 4

* **platzerito080420202** (1)

	
	fome qlao xd

	* **Daniel Esteban Santos Mendez** (1)

		
		Jajaja

* **jdiegochg10** (1)

	
	empezemos!

* **José Antonio aparicio gallego** (1)

	
	Yo lo único que quisiera saber es como se puede utilizar TypesScript con Webpack pero en este curso tan básico no lo explican,
	
	¿alguien que lo pueda corregir para que se pueda compilar ?
	``` 
	    {
	      "name": "midiezmilprueba",
	      "version": "1.0.0",
	      "description": "",
	      "main": "index.js",
	      "scripts": {
	        "start": "node dist/index.js",
	        "dev": "tsc-watch --onSuccess \"node dist/index.js\" ",
	        "build": "tsc",
	        "webpack": "webpack-dev-server"
	      },
	      "keywords": [],
	      "author": "",
	      "license": "ISC",
	      "dependencies": {
	        "bcrypt": "^4.0.1",
	        "cors": "^2.8.5",
	        "express": "^4.17.1",
	        "fork-ts-checker-notifier-webpack-plugin": "^2.0.0",
	        "fork-ts-checker-webpack-plugin": "^4.1.0",
	        "jsonwebtoken": "^8.5.1",
	        "jsx-loader": "^0.13.2",
	        "mongoose": "^5.9.5",
	        "morgan": "^1.10.0",
	        "passport": "^0.4.1",
	        "passport-jwt": "^4.0.0",
	        "tsconfig-paths-webpack-plugin": "^3.2.0"
	      },
	      "devDependencies": {
	        "@babel/core": "^7.2.2",
	        "@babel/preset-env": "^7.3.1",
	        "@types/bcrypt": "^3.0.0",
	        "@types/cors": "^2.8.6",
	        "@types/express": "^4.17.3",
	        "@types/jsonwebtoken": "^8.3.8",
	        "@types/mongoose": "^5.7.7",
	        "@types/morgan": "^1.9.0",
	        "@types/node": "^13.9.3",
	        "@types/passport": "^1.0.3",
	        "@types/passport-jwt": "^3.0.3",
	        "@types/webpack": "^4.41.8",
	        "@types/webpack-dev-server": "^3.10.1",
	        "babel-loader": "^8.0.5",
	        "css-loader": "^3.4.2",
	        "install": "^0.13.0",
	        "npm": "^6.14.3",
	        "ts-loader": "^6.2.2",
	        "ts-node": "^8.8.1",
	        "tsc-watch": "^4.2.3",
	        "tsconfig-paths": "^3.9.0",
	        "typescript": "^3.8.3",
	        "webpack": "^4.29.0",
	        "webpack-cli": "^3.2.1",
	        "webpack-dev-server": "^3.1.14"
	      }
	    }
	    
	    
	```

	* **Gabriel De Andrade (Platzi)** (2)

		
		[Esta guía de Webpack](https://webpack.js.org/guides/typescript/) te aclara super bien cómo hacerlo 😄

* **José Antonio aparicio gallego** (1)

	```
	    {
	      "compilerOptions": {
	        "target": "esnext",
	        "module": "commonjs",
	        "jsx": "preserve",
	        "lib": ["dom", "es2019"],
	        "baseUrl": ".",
	        "moduleResolution": "node",
	        "strict": true,
	        "allowJs": true,
	        "noEmit": true,
	        "allowSyntheticDefaultImports": true,
	        "esModuleInterop": true,
	        "skipLibCheck": true,
	        "noUnusedLocals": true,
	        "noUnusedParameters": true,
	        "isolatedModules": true,
	        "removeComments": false,
	        "preserveConstEnums": true,
	        "inlineSourceMap": true,
	        "forceConsistentCasingInFileNames": true,
	        "resolveJsonModule": true,
	        "paths": {"Root/*":["src/*"]},
	      },
	      "exclude": ["dist", ".next", "out", "next.config.js"],
	      "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx","serve"]
	    }
	    
	    
	```

* **José Antonio aparicio gallego** (1)

	```
	    const TsconfigPathsPlugin = require("tsconfig-paths-webpack-plugin");
	    const ForkTsCheckerWebpackPlugin = require("fork-ts-checker-webpack-plugin");
	    const ForkTsCheckerNotifierWebpackPlugin = require("fork-ts-checker-notifier-webpack-plugin");
	    
	    const path = require("path");
	    module.exports = {
	      context: process.cwd(),
	      mode: "development",
	      devtool: "inline-source-map",
	      entry: path.join(__dirname, "src", "index"),
	      watch: true,
	      output: {
	        path: path.join(__dirname, "dist"),
	        publicPath: "/dist/",
	        filename: "bundle.js",
	        chunkFilename: "[name].js"
	      },
	      module: {
	        rules: [
	          {
	            test: /.jsx?$/,
	            include: [path.resolve(__dirname, "src")],
	            exclude: [path.resolve(__dirname, "node_modules")],
	            loader: "babel-loader",
	            query: {
	              presets: [
	                [
	                  "@babel/env",
	                  {
	                    targets: {
	                      browsers: "last 2 chrome versions"
	                    }
	                  }
	                ]
	              ]
	            }
	          },
	          {
	            test: /\.ts$/,
	            loader: "ts-loader",
	            options: {
	              reportFiles: ["src/**/*.{ts,tsx}", "!src/skip.ts"],
	              transpileOnly: true
	            },
	            exclude: /node_modules/
	          }
	        ]
	      },
	      resolve: {
	        extensions: [".json", ".js", ".jsx", ".ts"],
	        plugins: [new TsconfigPathsPlugin({ configFile: "./tsconfig.json" })]
	      },
	      plugins: [
	        new ForkTsCheckerNotifierWebpackPlugin({
	          title: "Webpack build",
	          excludeWarnings: true
	        }),
	        new ForkTsCheckerWebpackPlugin()
	      ],
	    
	      devServer: {
	        contentBase: path.join(__dirname, "/dist/"),
	        inline: true,
	        host: "localhost",
	        port: 8080
	      },
	      stats: {
	        warningsFilter: /export .* was not found in/
	      }
	    };
	    
	    
	```

* **José Antonio aparicio gallego** (1)

	
	Pero si ya tenemos webpack 5

	* **Gabriel De Andrade (Platzi)** (1)

		
		Webpack 5 todavía está en beta 😛

* **Frank Carmona** (1)

	
	aca vamos

* **webrevolution** (1)

	
	Otra vez x aqui

* **Igor 'Bae** (1)

	
	Motiva mucho todo el plan de la carrera

	* **justoneye** (0)

		
		Cuál estás siguiendo?

* **ehnbytes** (1)

	
	Interesante curso!!

* **Sebastian Cardoso Castillo** (1)

	
	Me gusta como ha mejorado como profesor Leonidas.

* **Emmanuel Hernandez Ramirez** (1)

	
	Esto es nuevo pero veamos que tal se pone

* **Hugo Arrazola Dotor** (1)

	
	emocianado por aprender algo nuevo!!!

* **Manuel Rivera** (1)

	
	Vengo del curso de React Router, que primero me envió a realizar el curso de redux y ahora a este. Miremos que ta!!

* **Hernán Arica** (1)

	
	ajajaj buenísimo que sigas manteniendo la misma energía de siempre!!

* **Hugo Martínez** (1)

	
	Se prendioooooo 🔥🔥

* **Luis Enrique Sanchez Piñerua** (1)
Extrañaba tus cursos!

* **Alirio Alejandro Angel Arenas** (1)

	
	Excelente volver a ver un curso de Leonidas! emocionadisimo de comenzar

* **Brayan Murcia Sanchez** (1)
Muy ansioso por aprender del mejor, gracias profe Leonidas, vamos mis 300!

* **jesus-olivares661** (1)

	
	Me ví el de webpack anterior. Será que me veo este…? ó continúo con flutter…?  
	Hay muchas novedades…?

	* **Favio Sauto** (2)

		
		Te recomiendo ver este, yo igual me vi el anterior pero con la versión 4 de Webpack han cambiado muchas cosas y este curso es una gran manera de actualizarnos

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Hola hay muchos cambios de la versión 3 a la 4, muchas cosas se rompen y se manejan de forma diferente si quieres actualizar una aplicación que tienes con webpack 3 te recomiendo mucho ver este curso.

* **José Antonio aparicio gallego** (1)
Yo lo único que quisiera saber es como cambio mi código para que puede utilizar typeScript mit Webpack const TsconfigPathsPlugin =...

* **adrianrbp** (1)
Qué diferencias hay entre Parcel y Webpack?, cuándo debería usar Parcel y cuándo Webpack?

	* **Juan David Castro (Platzi)** (3)

		
		Parcel es increíble. Por ahora, yo creo que es mejor usar Webpack para los proyectos importantes en producción. Pero para probar herramientas, programar por diversión o estudiar sin necesidad de preocuparnos por la configuración, Parcel es fascinante. 😉
		
		Te recomiendo estas comparaciones:
		
		👉 <https://blog.jakoblind.no/parcel-webpack/>  
		👉 <https://medium.com/js-imaginea/comparing-bundlers-webpack-rollup-parcel-f8f5dc609cfd>  
		👉 <https://medium.com/@ibrahimbutt/if-youve-ever-configured-webpack-parcel-will-blow-your-mind-b615468cee78>

* **Byron Miguel Piedrahita Hernandez** (1)
Como me vuelvo un <>Google Developer Expert y que hace un Frontend Chapter Lead?

	* **Manuel Ojeda** (8)

		
		Hola Byron, para ser un Google Developer necesitas inscribirte al programa de Google y cumplir una serie de requisitos tales como:
		
		  * Ser un experto en el tema que quieres demostrar
		  * Demostrar continuamente que estás desarrollando
		  * Ser influencia y reconocido dentro de conferencias, ya sean grandes o pequeñas.
		  * Crear contenido de gran calidad, tutoriales, códigos de ejemplo, blogs post, videos, etc.
		  * Ser mentor
		
		
		
		Referencia:  
		<https://developers.google.com/community/experts/>
		
		Un **Frontend Chapter Lead** en resumen es quien será el lider de un equipo de desarrolladores Frontend.

* **manumac86** (0)

	
	Volvio!!! Vamooooo!!!

## 0020. Introducción a Webpack

### Descripción:


 **Webpack** es un empaquetador para Javascript y sus amigos. Convierte módulos con dependencias en archivos estáticos que los navegadores entienden.

Nos permite empaquetar, optimizar los diferentes módulos Javascript y sus dependencia en nuestro proyecto. Es usado en proyectos basados en Javascript como: React, Vue, Angular entre otros.

### User Experience

Se logra con una aplicación que:

  * Funcione
  * Sea rápida
  * Cumpla sus necesidades
  * Se actualice
  * Responda a sus interacciones
  * Producto de calidad



### Developer Experience

  * Escribir aplicaciones de manera eficiente.
  * Tener un código limpio.
  * Aplicar tecnología para resolver sus problemas.
  * Tener un conjunto de reglas y convenciones.
  * Entorno de desarrollo optimizado en productividad.



### Links:

* [webpack](https://webpack.js.org)

* [webpack - Google Slides](https://docs.google.com/presentation/d/13R2BNhh-92EOSgivW3CbN9GXbat2sfrAzdWNGeIaWCs/edit?usp=sharing)

### Comentarios:

* **alexjcm** (18)

	
	Webpack es más genial si es Leonidas quien lo enseña

	* **Fp_1000** (1)

		
		True Story

* **Alan Santiago** (8)

	
	¿Cómo mejorar la **_Developer Experience_**? 🤔  
	.  
	Con el curso de [Buenas prácticas](https://platzi.com/clases/mejor-codigo/). Se los recomiendo.

* **juand_silva** (7)

	
	La típica de Colombianos **“Se le tiene pero se le demora”** xD

* **Jose Luis Colmenares** (6)

	
	Webpack es un conjunto de reglas que vamos a configurar para saber como funciona nuestro stack (de archivos), que está incluido en nuestro stack, y cómo manipulamos nuestro stack para que nuestra tecnología pase de la Developer Experience (Modules with Dependencies) a la User Experience (Static Assets).

* **Pedro Samuel Fagundez** (6)

	
	Después de 3 cursos sin ver a Leonidas, volver a verlo es darse cuenta el porqué es el mejor profesor de Platzi !

* **Ricardo Lugo Recillas** (5)

	
	  * Introducción a Webpack 
	    * Es un empaquetador de javascript, empaquedaro de módulos de JS  
	-User expirence:  
	Se busca que la aplicación funcione, que sea rapida , que cumpla todas la necesidades, se actualice (escalable), responda a la interacción y al final sea un gran producto de calidad.
	    * Developer Experience  
	Escribir una aplicación de manera Eficiente, generar un código totalmente limpio, Ampliar la tecnología para la resolución del problema, seguir un conjunto de reglas y convenciones, al salir a producción la optimizacion del desarrollo.
	
	

* **webrevolution** (4)

	
	tanto tiempo sin saber de webpack

* **citux** (4)

	
	intento fallido del examen a retomar :p

* **Felipe Acosta** (4)

	
	Jajajajaja estuvo buena esa de “Se le tiene pero se le demora”, clasica del colombiano

* **luis-fernando-yupanqui-taco** (3)

	
	Eso funciona con fe!!!

* **heysoypaez** (3)

	
	 **Curso de Webpack 4**
	
	Webpack es un empaquetador para javascript y sus amigos
	
	Empaquetador de modulos para aplicaciones modernas en JS
	
	Developer Experience  
	Desarrollo
	
	  * Escribir aplicaciones de manera eficiente
	  * Tener un código limpio
	  * Aplicar tecnologia para resolver sus problemas
	  * Tener un conjunto de reglas y convenciones
	  * Entorno de desarrollo optimizado en productiviad
	
	
	
	User Experience  
	Produccion
	
	  * Funcione
	  * Cubra su necesidad
	  * Sea rapida
	  * Se actualice
	  * De feedback
	
	

* **Yennifer Paola Herrera Ariza** (3)

	
	Definitivamente este es el curso que necesitaba :gre

* **aldoea** (2)

	
	¿ Webpack solo es útil para frontend o tiene alguna aplicación en el desarrollo de backend ?

	* **luis-mendoza877** (1)

		
		pues como es para js, me imagino que puede servir para backend con Node.js

	* **Emmanuel Rodríguez Ramírez** (1)

		
		[](https://stackoverflow.com/questions/37788142/webpack-for-back-end)

	* **Emmanuel Rodríguez Ramírez** (3)

		
		[Intetna con este link](https://stackoverflow.com/questions/37788142/webpack-for-back-end)

	* **Juan José Vega Quintero** (1)

		
		Que buena pregunta e interesante respuesta en stack overflow

* **Alan Santiago** (2)

	
	Una buena manera de dar _feedback_ a los usuarios es usando **animaciones**. 🤩  
	.  
	<https://platzi.com/clases/animaciones-web/> 👀

* **Estefymine** (2)
Bienvenidos 💚

* **Daniel .** (2)

	
	a repasar el curso, vamo a actualizarnos

* **Fabián andres Pedraza Borhorquez** (1)

	
	es muy importante hacer la diferencia del user experience al developer experience ya que en algunos proyectos solo se tiene encuenta el UX dejando de lado las buenas practicas que se pueden llevar en un proyecto para entender y actualizar los proyectos

* **Diego Alejandro Bayona Cardozo** (1)

	
	el Developer Experience me parece vital, muchos compañeros que he tenido no lo aplicaban y es mucho mas difícil poder realizar proyectos cuando no se tienen esas practicas

* **jdiegochg10** (1)

	
	webpack

* **webrevolution** (1)

	
	le picas a algo???

* **Ronnie Moncayo** (1)

	
	Maestro!!

* **Miguel Angel Morales Larriega** (1)

	
	Diferencia con Babel?

	* **Felipe Acosta** (2)

		
		Babel es una librería para usar Javascript del futuro ahora mismo.

	* **emileond** (3)

		
		Webpack es un todo en uno para tu app, babel únicamente sirve para compilar JS moderno y que tenga compatibilidad con todos los navegadores.

* **Adrian Garcia Saaib** (1)

	
	Una clase para repasar

* **David Acevedo** (1)

	
	Que es webpack?  
	Es un empaquetador para aplicaciones modernas, por ejemplo con webpack podemos hacer que todo el código js de nuestra aplicación sea exportado en un código transpilado y minificado con todas las dependencias que usemos o bien un archivo con el CSS tras haber pasado los preprocesadores necesarios.
	
	muchos devs consideran a webpack como la evolucion de herramientas como grunt y gulp ya que permite de alguna manera automatizar los procesos principales que son transpilar y preprocesar código de .scss a .css, de ES7 a ES5/6, etc…

* **danielfernando** (1)
Las paginas mas visitadas en la actualidad utilizan Webpack?

	* **Jose Padron (Platzi)** (5)

		
		No todas, puedes ver con qué tecnologías están hecha la página con una extensión de google chrome se llama: wappalyzer 😉 te la recomiendo

## 0030. Configurando un nuevo proyecto de Javascript

### Descripción:


Aprende más en el Curso de Webpack en Platzi disponible con tu suscripción en: <https://platzi.com/clases/webpack/>  
Adquiere hoy la suscripción de Platzi en: <http://platzi.com/precios>

En esta clase el profesor Leonidas Esteban nos guía paso a paso para crear nuestro primer proyecto usando Webpack.

En nuestro proyecto existen dependencias del tipo desarrollo y del tipo core con sus respectivas versiones, por eso usaremos NPM para administrarlas e instalar Webpack que viene a ser una dependencia (de desarrollo) más en nuestro proyecto de Javascript.

### Links:

* [
    
        
          npm-init  | 
    
    npm Documentation
  ](https://docs.npmjs.com/cli/init)

* [Node.js](https://nodejs.org/en/)

* [clase 3 Configurando un nuevo proyecto de Javascript · LeonidasEsteban/webpack-4@632e183 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/632e1834219687778c5013d9afb959940be65918)

### Comentarios:

* **beMendoza_** (22)

	
	Este es el **shorthand** para realizar el comando del profesor `npm i -D -E webpack@4.32.2`
	
	En donde:  
	`i significa install`  
	`-D significa --save-dev`  
	`-E significa --save-exact`
	```
	``` 
	<https://docs.npmjs.com/misc/config#shorthands-and-other-cli-niceties>  
	En este link pueden encontrar muchos más shorthands

	* **Thony07** (1)

		
		Toma tu like soldado !  
		Y gracias

* **edwintrumpet** (11)

	
	Se puede reemplazar install por su shortcut i así:
	``` 
	    npm install webpack
	    
	```
	``` 
	    npm i webpack
	    
	```
	
	Las banderas con doble guión como --save se pueden reemplazar con su shortcut usando mayúsculas y sólo un guión así:
	``` 
	    npm install webpack --save
	    
	```
	``` 
	    npm i webpack -S
	    
	```
	
	El shortcut de --save-dev es -D
	``` 
	    npm install webpack --save-dev
	    
	```
	``` 
	    npm i webpack -D
	    
	```
	
	Para instalar una versión precisa del paquete se puede agregar a su nombre el número de la versión después del signo @ así:
	``` 
	    npm i webpack@4.32.2 -D
	    
	```
	
	Este método agregará webpack a las dependencias de desarrollo con el número de versión 4.32.2 pero cuando se descarguen los paquetes se instalará la última versión del paquete debido al prefijo ^
	``` 
	    "devDependencies": {
	    	"webpack": "^4.32.2"
	    }
	    
	```
	
	Para guardar la versión exacta en el package.json se debe agregar la bandera --save-exact y su shortcut sería -E
	``` 
	    npm install webpack --save-dev --save-exact
	    
	```
	``` 
	    npm i webpack -D -E
	    
	```
	
	Esto agregará la dependencia sin el prefijo, lo que instalaría la versión exacta indicada en cada instalación.
	
	Pueden ver más opciones en la [documentación](https://docs.npmjs.com/cli/install)

* **roberbox** (9)

	
	Para instalar la versión de Leonidas, basta con escribir  
	npm install -D -E webpack@4.32.2  
	-D (–save–dev)  
	-E (–save–exact)

* **Manuel Rivera** (7)

	
	Para instalar la versión de Leonidas, basta con escribir
	
	npm install -D -E webpack@4.32.2
	
	-D (–save–dev)  
	-E (–save–exact)

* **Omar del Real** (7)

	
	A partir de la versión 5 de NPM, ya no hace falta incluir el parámetro “-–save” ya que lo hace automáticamente, en cambio si debemos usar “-–save-dev” o “-D” para instalarla como dependencia de desarrollo, un saludo 😉

	* **swapuruguay** (3)
Eso mismo iba a comentar

* **Karl Heitmann** (6)

	
	Amigos, para instalar la versión 4.32.2 utilicen:
	``` 
	    npm install webpack@4.32.2 --save-dev --save-exact
	    
	```
	
	Noten el arroba después del nombre del paquete y antes del flag --save-dev

* **Simón Arenas** (5)

	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-1d720897-4179-4435-bb8d-d42cc785e108.jpg)  
	Pueden ver todos mis apuntes de este curso [aquí](https://www.notion.so/simon98/Webpack-88d2c9bfe228471481af99236964a149)😃

	* **Nigtdreams** (1)

		
		Super clean tus notas

	* **Nigtdreams** (1)

		
		Muchas gracias por tus apunte, yo tambien tengo algunos. Si necesitas alguno avisame

	* **jdiegochg10** (1)

		
		tienes algun curso de notion.?

* **Luis Miguel Rodriguez** (5)

	
	`npm install webpack --save-dev --save-exact`  
	se puede resumir de esta manera  
	`npm i webpack -D -E`

* **German Sayago** (5)

	
	en la consola, si colocan “code .” (code espacio punto) les abre el proyecto directamente en visual studio code en el directorio correspondiente

	* **GuillermoLoza** (2)

		
		Muy interesante tu aporte  
		😄

* **Sebastian Cardoso Castillo** (4)

	
	Ya no hace falta poner el --save. Solo con poner **npm i webpack** queda implicito. Para dependencia de desarrollo **npm i -D webpack**.

* **Daniel Hurtado** (4)

	
	en las versiones actuales ya no es necesario poner el --save, se coloca automáticamente

* **Cesar Zavala Varon** (4)

	
	Demasiada carreta para lo que realmente se debe hacer…

* **lsolares** (4)

	
	Con npm init -y se puede saltar la parte tediosa del enter, enter y enter…
	``` 
	    npm init -y
	    
	```

* **Cristian Andrés Córdova Valencia** (3)

	
	Cuando ejecute npm init en nombre establecí:  
	**“name”: “webpack”,**
	
	Esto hizo que me diese un error al intentar instalar webpack. Ya que al parecer no podemos llamar igual al proyecto que al paquete ya que da un conflicto de nombres. Lo resolví simplemente cambiando de nombre el directorio y renombrando el apartado de “name” en el fichero package.json así:  
	**“name”: “Curse_Webpack”,**
	
	Saludos.

* **Felix E. Orduz G.** (3)

	
	Resumen de la clase en una sola linea (crea un directorio llamado demo)
	``` 
	    mkdir demo && cd demo && yarn init -y && yarn add -DE webpack
	    
	```

* **Alexis Otaño** (3)
<h4>Actualemente al instalar usando npm</h4>
	``` 
	    npm install <nombre del paquete>
	    // o 
	    npm i <nombre del paquete>
	    // [mas corto]
	    
	```
	
	el --save no es necesario pues ya se asume.  
	Personalmente soy un poco paranoico y lo sigo escribiendo =), pero de apoco se acostumbra  
	`--save-dev` para guardar como dependencia  
	`-g` para instalar de forma global

* **Sergio Atanacio** (3)

	
	Tal vez fué demaciado saltarme del video de selectores css, del curso de desarrollo web online al curso de Webpack. 😃

	* **Yennifer Paola Herrera Ariza** (3)

		
		Sigue la ruta que mostró Leo en el video de bienvenida. Podrías saltarte los cursos de PostCss, Css Grid, Animaciones para la web y tomarlos después de este curso. Asegúrate de tomar el curso de Fundamentos de Js y ya estarías listo para volver 😉

* **Kelly Jesus Salazar Sanchez** (3)

	
	Para instalar la version del profe Leonidas
	``` 
	    npm install webpack@4.32.2 --save-dev --save-exact
	    
	```

* **Fabián andres Pedraza Borhorquez** (2)

	
	![cursoplatzi-webpack.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-d2f7caab-df66-4db0-8619-f2cd5b01516e.jpg)  
	estoy empezando el curso de webpack y he logrado configurarlo continuare a ver que me depara el destino

* **Cristian Andrés Córdova Valencia** (2)

	
	Con las teclas:  
	Ctrl + L
	
	Limpian su terminal de una manera rápida. Sin necesidad de escribir clear. 😉

	* **Gabriel De Andrade (Platzi)** (1)

		
		Para mas datos interesantes como este: [Curso de Terminal y Línea de Comandos](https://platzi.com/clases/terminal) 😄

* **Henry Puentes Gonzalez** (2)

	
	desde la carpeta que creaste:
	
	webpack-4  
	puedes iniciar el proyecto .js con npm init, posterior darle los siguientes comando:
	``` 
	    touch index.js
	    
	    code .
	    
	```

* **Simón Arenas** (2)

	
	**OJO** : no llamen a su proyecto exactamente ‘webpack’ o les dará error.

	* **Fernando Vallejo** (1)
Ojito ojito

* **Daniel Hurtado** (2)

	
	Que le pasó a la l del sticker de platzi xD

	* **Jaime David Burbano Montoya** (1)

		
		Lo mismo pense

* **Luis Fernando Farji** (2)

	
	Es muy importante que la carpeta que vamos a crear para trabajar no se llame Webpack, sino va a dar error.

	* **sordonezg** (1)

		
		Excelente, me sirvio.

* **José Tuzinkievicz** (2)

	
	Para [desinstalar](https://flaviocopes.com/npm-uninstall-packages/) dependencias

* **roxydev** (2)
-D es - - save-dev y - E es - - save-exact

* **fnevarez00** (2)

	
	i -> install  
	-D -> \--save-dev
	``` 
	    npm i -D webpack
	    
	```

* **fidekof** (2)
Leónidas muy buenas clases ... Tengo una duda... En webpack tu configuraste un config.js para cada tipo de herramienta 1 para babel, 1 pa...

	* **Erik Ochoa (Platzi)** (2)

		
		Es posible importar cualquier archivo JS que exporte algo dentro de otro, como en este caso lo hace _webpack.config.js_ con la instrucción `module.exports`. Solo que lo único que lograrías sería tener un objeto con todas las configuraciones de tu otra configuración y tocaría a ti por medio de código mezclarlo con lo que ya tienes, todo un lío.
		
		Esta configuración se hizo así por cuestiones didácticas para separar cada tema y hacer más fácil su aprendizaje. En un entorno real, se tiene un sólo archivo de configuración de webpack o uno para ambiente **dev** y otro para **prod**.
		
		Saludos 👋

* **ehnbytes** (1)

	
	wow!!

* **Pablo Victor Vargas** (1)

	
	habia creado el archivo como “webpack” y no me dejaba instalar webpack porque tenia el mismo nombre que la dependencia!! cosas que pasan!!! jeje

* **jdiegochg10** (1)

	
	interesante!

* **WSJedp** (1)

	
	Cuando estamos creando un proyecto JavaScript debemos entender la diferencia entre las dependencias de desarrollador y las dependencias del sistema, las del desarrollador son todas aquellas dependencias que necesita nuestro proyecto para funcionar en el modo de desarrollo, mientras que las dependencias del sistema son todas aquellas que necesita siempre nuestro proyecto, tanto en un entorno de producción como en un entorno de desarrollo.

* **Jose Alejandro Sorza Ubaque** (1)

	
	Algo que me di cuenta en el proceso de este curso es que, si estan trabajando con un equipo mac (en mi caso con macOS Mojave) primero tienen que instalar un gestor de paquetes que se llama Homebrew, ya despues si pueden hacer las demas instalaciones

	* **Gabriel De Andrade (Platzi)** (2)

		
		Si, lo primero es instalar Homebrew, es bastante sencillo, acá las instrucciones, [Homebrew](https://brew.sh/) 😄

* **webrevolution** (1)

	
	de regreso!!!

* **Simón Arenas** (1)

	
	Este es el shorthand para realizar el comando del profesor npm i -D -E webpack@4.32.2
	
	En donde:  
	i significa install  
	-D significa --save-dev  
	-E significa --save-exact

	* **Gabriel De Andrade (Platzi)** (1)

		
		Esto lo aprendemos más a fondo en el [Curso de Gestión de Dependencias y Paquetes con NPM](https://platzi.com/clases/npm/) 😄

* **ldiegomr** (1)

	
	 **Para instalar nodejs en CentOS**
	
	  1. Descagar el archivo Binarios Linux:  
	`wget https://nodejs.org/dist/v12.15.0/node-v12.15.0-linux-x64.tar.xz`
	
	  2. Descomprimir e instalar nodejs en nuestro sistema:  
	`sudo tar --strip-components 1 -xf node-v* -C /usr/local`
	
	  3. Verificar que nodejs fue instalado en nuestro equipo:  
	`node --version`
	
	
	
	
	**Recurso original**  
	<https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-a-centos-7-server#install-a-package-from-the-node-site>

* **isncsanchez** (1)

	
	No pude corrernode en mi computadora, alguien conoce la solucion al siguiente error ??
	
	Esto al correr npm init
	``` 
	      var doExit = npm.config.loaded ? npm.config.get('_exit') : true
	                              ^
	    
	    TypeError: Cannot read property 'loaded'of undefined
	        at exit (/usr/local/lib/node_modules/npm/lib/utils/error-handler.js:97:27)
	        at process.errorHandler (/usr/local/lib/node_modules/npm/lib/utils/error-handler.js:216:3)
	        at process.emit (events.js:223:5)
	        at process._fatalException (internal/process/execution.js:150:25)
	    
	    
	```
	
	node 12,14,1  
	npm 6.13,7
	
	Al final obte por hacer una configuracion de uns ervicio con Docker y Docker Compose en donde estoy trabajando sin problemas, pero me gustaria correrlo en mi local.

* **sordonezg** (1)

	
	instale la version 4.41.5
	
	entendi a leonidas que es importante usar la misma version de webpack que usa el o me equivoco?

	* **FerPM** (1)

		
		Yo entendí lo mismo. Es muy importante tener la misma versión que usa Leonidas en el curso (min 9:20 del video) . Lo que no queda claro, me parece, es como hacerlo. Es decir, él lo explica con -exact, pero no se como hace npm para saber la exacta version que Leonidas usó en el curso. 😦

	* **miguelangelsoler** (1)

		
		Para instalar la versión exacta que usa el teacher:
		
		`npm i webpack@4.32.2 --save-dev --save-exact`

* **Enrique Sardon Manrique** (1)
Yarn hace el trabajo de npm más rápido y con menos modificadores

* **Camilo Andrés Santana Lizcano** (1)

	
	Entendamos de una vez y por todas de qué se trata webpack

* **webrevolution** (1)

	
	4.41.0 sera que no me corre todo el curso?

* **Luis Alberto Bernal** (1)

	
	que onda con el ojito ojito… jajajaja

	* **Martinez Palacios** (1)

		
		Jajaja yo tampoco entiendo lo del ojito ojito, y ya he visto que otro profesor de platzi dice eso. Pero contento de estudiar otro curso con Leonidas.

	* **Camilo Rivera Quintero** (1)

		
		muletillas de Leonidas jajaj

	* **José Tuzinkievicz** (1)

		
		Simplemente se refiere a que se tenga cuidado y se preste atención a lo que se esté haciendo.

	* **Karl Heitmann** (1)

		
		Es notable, le da personalidad a la clase. Este ha sido mi profesor favorito!!!

* **José A. Cárdenas** (1)

	
	Aiura  
	![Captura.JPG](https://static.platzi.com/media/user_upload/Captura-c29c5c74-8369-4754-9dfa-03aeffd15521.jpg)

	* **raimercm** (1)

		
		se soluciona cambiando el nombre de la carpeta “webpack”

	* **luis zevallos** (1)

		
		tenia este mismo error era que el parckage.json tenia en mismo nombre de webpack

* **cesarcubillos** (1)

	
	Excelente explicación, acá tomando nota para almacenar mejor la info

* **Miguel Angel Morales Larriega** (1)

	
	No es necesario escribir --save o -S, ya que igual instala webpack como dependencia de producción:  
	npm i webpack  
	y en e package.json me crea el objeto dependencia con webpack incluido y su versión

	* **Johan Manuel Perez Soto** (1)

		
		Es cierto lo que dice este desconocido!

	* **Eduardo P. Rivero** (1)

		
		Correcto. A partir de la version 5 este es el comportamiento por defecto.

* **David Acevedo** (1)

	
	Dependencias y herramientas necesarias para el curso hasta ahora:  
	-Node  
	-npm  
	-webpack version: 4.32.2 ( es recomendable seguir la version del curso para evitar frustraciones)
	
	iniciar proyecto con npm  
	-npm init  
	instalacion de webpack como dependencia de desarrollo  
	npm install webpack --save-dev

* **jose ortiz** (1)

	
	si tienen algun problema con las instalacion, solo escriban en el package.json :
	``` 
	    "devDependencies": {
	        "webpack": "4.32.2"
	      }
	    
	```
	
	y luego
	``` 
	    npm install
	    
	```

* **GuillermoLoza** (1)

	
	Para instalar una versión en

* **capacita.ti** (1)

	
	Si quieren trabajar con una versión específica de Node y probar sus características, recomiendo [NVM](https://github.com/nvm-sh/nvm)  
	Aquí un tutorial --> [https://medium.com/devschile/múltiples-versiones-de-node-con-nvm-63b2ac715c38](https://medium.com/devschile/m%C3%BAltiples-versiones-de-node-con-nvm-63b2ac715c38)  
	Grande Leo!

	* **Raul Contreras** (1)

		
		En windows va fatal nvm XD

* **luisglopez7777** (1)
Buenas, vengo del curso de React js y quiero hacer un proyecto con la configuración parecida a la de create-react-app y usar este curso c...

	* **Gabriel De Andrade (Platzi)** (2)

		
		Si, deberías instalar las últimas versiones para tu proyecto. No deberían tener demasiadas diferencia con las de este curso 😛

* **christian-magro-perez** (1)
¿Desde que versión de Node soporta Webpack?

	* **Gabriel De Andrade (Platzi)** (2)

		
		De la 8 para arriba 😄

* **Armando Marin Metlich** (1)
Leonidas, tengo una duda. Hice primero el curso de reactJS, y las apps se creaban con “create react app” que ya incluye webpack, y las de...

	* **Erik Ochoa (Platzi)** (4)

		
		El `--save` lo usas para cuando quieres guardar una dependencia de producción en el package.json y que otras personas pueden instalar las dependencias de tu proyecto sin problemas.
		
		Webpack se integra sin problemas con React, en el curso vas a ver un proyecto al final con hecho con React. En cuanto a react-native no sé que tan útil sea usar webpack en sí.

* **Hebert de León** (1)
¿Algún lugar donde pueda aprender más del tema de Licencias?

	* **Juan David Castro (Platzi)** (2)

		
		👉 [¿Qué licencia uso para mi código libre? - Geeky Theory](https://geekytheory.com/que-licencia-uso-para-mi-codigo-libre)  
		👉 [El Control de Versiones con Git: Licencia](https://swcarpentry.github.io/git-novice-es/11-licensing/)  
		👉 [¿Sabes bien qué licencia elegir para tu software? MuyLinux](https://www.muylinux.com/2013/07/18/eleccion-licencia-software/)

* **a0ba** (1)
No pasa nada si tengo la versión 4.39.1 de webpack verdad?

	* **Carlos Martinez** (2)

		
		yo tengo la 4.36.1 y no he tenido problemas hasta ahora, si te da errores revisa si estás escribiendo bien el código , y si por casualidad le das vueltas y vueltas al error y nada que lo solucionas baja la versión del profesor.
		
		si se solucionó es porque era la versión, si no, es porque escribiste algo mal.
		
		saludos 😃

* **josdanind** (1)
Tengo inconvenientes con la instalación de webpack con npm: npm ERR! path /home/... npm ERR! code ENOENT npm ERR! errno -2 npm ERR!...

	* **Jhon Alexander Perez Valencia** (2)

		
		## Posible soluccion 😃
		
		  1. verifica que la carpeta donde lo estes instalando no se llame “webpack” pon otro nombre como “webpack4” o algun otro.
		  2. verifica que si exista el archivo package.json (que se crea cuando pones el comando ´npm init´)
		
		
		
		si aun te sale el error verifica que en el archivo package.json en el campo “name” no diga “webpack”

* **Carlos Remesal** (0)

	
	Intento escribir los comandos que escribe Leonidas en mi ordenador en Node.js y no me funciona, me dan error, es que el esta trabajando el linux? no entiendo no me funciona ni el comando clear

	* **Gabriel De Andrade (Platzi)** (1)

		
		Hola! Leonidas está trabajando en MacOS que funciona muy parecido a Linux, si quieres tener la mejor experiencia de desarrollo te aconsejo que primero pases por el [Curso de Prework](https://platzi.com/clases/prework/), por los básicos de JS y por los básicos de tu Framework favorito, este curso de Webpack es un Curso bastante Avanzado. También recuerda que puedes pedir tu ruta de aprendizaje personalizada a [team@platzi.com](mailto:team@platzi.com) 😄

	* **Hernán Arica** (1)

		
		es por que tenés que usar la consola GitBash

## 0040. Creando nuestro primer bundle con Webpack

### Descripción:


Vamos a instalar otra dependencia llamada **webpack-cli** , la API que expone webpack en forma de **CLI (Command Line Interface)** que nos va a permitir interactuar y configurar Webpack desde la terminal.

El comando `webpack` tiene una bandera llamada `--mode` que nos permite cambiar entre los modos producción y desarrollo. Recuerda que por defecto nos pone en modo producción si no la especificamos.

### Links:

* [clase 4 creando nuestro primer bundle · LeonidasEsteban/webpack-4@0c6b99d · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/0c6b99df700098e3e9b7e4f4f03be05747017d0b)

### Comentarios:

* **Simón Arenas** (9)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-5b134874-4a1f-4c57-8292-a4831f6e1719.jpg)
	
	Pueden ver todos mis apuntes de este curso [aquí](https://www.notion.so/simon98/Crear-un-bundle-83fd8f17143a4c6eb266681df6d862d9)😃

	* **Javier Armando Vargas Vega** (1)

		
		Excelente resumen

	* **Juan Jose Mayorga Garcia** (1)

		
		wow! muchas gracias, son geniales!

* **jhon manuel angulo moncada** (7)

	
	es mas fácil usar:
	``` 
	    npm i webpack-cli@3.3.2 -D -E
	    
	```
	
	i = install  
	-D = --save-dev  
	-E = --save-exact

	* **FerPM** (1)

		
		Lo conseguí gracias a vos!!!

* **David Acevedo** (5)

	
	 **Creacion de bundle con webpack**
	
	Desde la version 4 de webpack requiere el uso de webpack cli el cual se instala como dependencia de desarrollo en nuestro proyecto
	
	**npm install webpack-cli --save-dev**
	
	haciendo uso de npx podemos usar webpack como comando en en nuestra consola  
	-npx webpack -v (nos arrojara la version instalada)  
	**Creacion de archivo e entrada y salida en nuestro webpack  
	**  
	**npx webpack --entry ./index.js --output ./bundle.js --mode development**
	
	Con este comando le estamos indicando a webpack el archivo en el que trabajaremos nuestro código para que webpack lo procese y luego le indicamos el archivo de salida del bundle el cual se utilizara en el producto final.  
	con el flag de “–mode” indicamos si queremos una version de production la cual traera todo el codigo minificado o modo development.

* **Néstor López** (4)

	
	Npx nos permite llamar un módulo instalado en el proyecto, sin tenerlo global

* **Karl Heitmann** (4)

	
	Amigos, para instalar la versión 3.3.2 utilicen:
	``` 
	    npm install webpack-cli@3.3.2 --save-dev --save-exact
	    
	```
	
	Noten el arroba después del nombre del paquete y antes del flag --save-dev

	* **Fernando Vallejo** (1)
Ojito ojito

* **Jhon Alexander Perez Valencia** (3)

	
	CLI: Command Line Interface

* **Johan Stivens Suarez Galindo** (2)

	
	Leonidas es un duro, explica muy bien!

* **webrevolution** (2)

	
	cli - command line interface  
	siempre pense que era de cliente jajaja

* **Isaias Chávez** (2)

	
	con el flag de “–mode” indicamos si queremos una version de production la cual traera todo el codigo minificado (Para entrega)  
	o modo development para cuando nos encontremos desarrollando.  
	Creo que esto será super importante en el futuro.

* **carlos-bolivar** (2)

	
	El orden de los primeros 4 videos esta mal, este video seria el 4to video, este va antes de “Iniciando un webpack.config” recomiendo lo arreglen para no confundir a los demas estudiantes, hasta ahora buen inicio de curso 😄!!

	* **diego-serrano** (2)

		
		Si. No es el primer curso con ese problema.

	* **Juan Luis Rojas León** (1)

		
		Pronto lo arreglarán.

	* **Isaias Chávez** (1)

		
		Creo que no es necesario, la clases no están en desorden. De hecho, cualquier clase que veas primero te ayudará a entender la otra. Yo te hice caso y ví primero la otra.

* **Carlos Gómez Mont** (2)

	
	Alguien más también instala CLI y tiene 42 vulnerabilidades o soy el único 😦 ? Saludos.

	* **Wilson Marino Pablo Mendez** (1)

		
		A mí **“0 vulnerabilities”**

	* **Emiliano Durán** (1)

		```
		    + webpack-cli@3.3.5
		    added 63 packages from 29 contributors and audited 5291 packages in12.924s
		    found 0 vulnerabilities
		    
		```

* **Fabián andres Pedraza Borhorquez** (1)

	
	![cursoplatzi-webpack-bundle.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-bundle-adb8f374-2588-44d6-8e5a-224da061e66e.jpg) esto esta emocionante 😃

* **jdiegochg10** (1)

	
	Interesante, la técnología Webpack

* **Cristian Andrés Córdova Valencia** (1)

	
	npm install webpack-cli -D -E webpack-cli@3.3.2

* **Juan David Marin** (1)

	
	Resumiendo clase:  
	En esta clase vemos como instalar el webpack-cli por linea de comandos y su configuración.  
	Se crea un archivo.js (No digo el nombre para que entren a ver todo el video).  
	También vimos el npx que también de npm y su sintaxis ó la forma de ejecutar de manera correcta.

* **Iván Darío Sánchez Jiménez** (1)

	
	Para quienes no tenga habilitada la opción para abrir archivos en la aplicación por defecto pueden instalar la extensión para vscode llamada **open**
	
	Si instalan una llamada **open in browser** no la recomiendo ya que no soporta todos los navagadores según el sistema operativo.

* **sordonezg** (1)

	
	no me queda clara la diferencia entre dependencies y devDependencies

	* **Gabriel De Andrade (Platzi)** (9)

		
		Las **devDependencies** son aquellas que sólo utilizarás tu como desarrollador y que el público no necesitará para correr la página, estas dependencias no serán tomadas en cuenta a la hora de hacer el empaquetado final de tu página, es decir, no se incluirán en la versión de producción. Por ejemplo: ESLint  
		  
		Por otra parte, las **dependencies** forman parte esencial de tu página y siempre serán incluídas en la versión de producción, pues estas serán necesarias para correr la página. Por ejemplo: React.  
		  
		Puedes aprender más de esto en el [Curso de Gestión de Dependencias y Paquetes con NPM](https://platzi.com/clases/npm/) 😄

	* **sordonezg** (1)

		
		Gracias por responderme Gabriel, me aclaraste la duda!

	* **Elias Ojeda Medina** (2)

		
		@GabrielElpidio gracias, no sabia del curso, apredí varias cosas, justo pause el de webpack por ver el otro

* **Yaisel Hurtado González** (1)

	
	¿Leonidas cuáles son las extensiones de VS Code que usas durante el curso?

	* **Juan José Vega Quintero** (1)

		
		Tiene un video en Youtube donde muestra toda su configuración, con una simple búsqueda lo encuentras

* **anadecanha** (1)

	
	yo ni siquiera he podido instalar el CLI 😦

	* **Thony07** (3)

		
		Puede que sea por la versión que instalaste previamente de webpack  
		Yo instale la misma que Leonidas, y no me permitía instalar el CLI  
		Luego instale una versión más actualizada de webpack y webpack-cli y si me permitió !
		
		Primero instalé:
		``` 
		    <npm i -D -E webpack@4.39.3>
		    
		```
		
		Luego instalé:
		``` 
		    <npm i -D -E webpack-cli@3.3.2>
		    
		```
		
		Y mis devDependencies quedaron así:
		``` 
		    "devDependencies": {
		        "webpack": "4.39.3",
		        "webpack-cli": "3.3.8"
		      }
		    
		```
		
		Saludos, espero que te sirva 😃

* **Jessen Mercado** (1)

	
	Para instalar cli versión 3.3.2:
	
	npm install webpack-cli@3.3.2 --save-dev --save-exact

* **José Tuzinkievicz** (1)

	
	Cómo [instalar](https://www.alvarolara.com/2015/06/08/como-instalar-versiones-de-un-paquete-con-npm/) una versión específica de un paquete.

	* **Karl Heitmann** (2)

		
		Utiliza:
		``` 
		    npm install webpack-cli@3.3.2 --save-dev --save-exact
		    
		```
		
		**Pista: ** al ver el video, el output del comando npm install que hizo Leo dice “webpack@4.32.2”, ese @ me dió la pista de que tenía que suplir el arroba para instalar una versión específica del paquete

* **SOFTDYNAMIC** (1)

	
	Calmaos !

* **Luis Alberto Bernal** (1)

	```
	    C:\Users\Luis Bernal\webpack-4>npx webpack --entry index.js --output bundle
	    
	    Insufficient number of arguments or no entry found.
	    Alternatively, run 'webpack(-cli) --help'for usage info.
	    
	    Hash: cf4b155b56e06edcc0f5
	    Version: webpack 4.39.3
	    Time: 180ms
	    Built at: 2019-09-039:43:30 PM
	    
	    WARNING in configuration
	    The 'mode' option hasnot been set, webpack will fallback to'production'for this value. Set'mode' option to'development'or'production'to enable defaults foreach environment.
	    You can also set it to'none'to disable any default behavior. Learn more: https://webpack.js.org/configuration/mode/
	    
	    ERROR in Entry modulenot found: Error: Can't resolve 'index.js' in 'C:\Users\Luis Bernal\webpack-4'
	    
	    C:\Users\Luis Bernal\webpack-4>npx webpack --entry ./index.js --output ./bundle
	    Error: EISDIR: illegal operation on a directory, open 'C:\Users\Luis Bernal\webpack-4\bundle'
	    
	    C:\Users\Luis Bernal\webpack-4>```
	    
	    
	    NO SE PORQUE ME DA ESE ERROR
	    
	```

	* **Jean León** (1)

		
		Hola, es probable que te falte instalar el CLI de webpack.  
		verifica en **package.json** que en **devDependencies** lo tengas así
		``` 
		    "devDependencies": {
		        "webpack": "4.39.3",
		        "webpack-cli": "3.3.8"
		      }
		    
		```
		
		Si te falta **webpack-cli** debes instalarlo ejecutando **npm install -D webpack-cli**

	* **Simón Arenas** (1)

		
		No es _index.js_ , la forma forrecta es _./index.js_

* **wert89** (1)

	
	cual es el primer video del curso?

	* **jonChica** (3)

		
		Creo que este es el cuarto video, va antes de “Iniciando un webpack.config”

* **Adrian Garcia Saaib** (1)

	
	la línea en la que creamos el entry point ya no la guardamos en el package.json como script? por qué?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Hola. No entiendo muy bien tu pregunta, puedes aclarar un poco más para poder ayudarte a despejar tu duda.

	* **Adrian Garcia Saaib** (1)

		
		Ya se solucionó en la siguiente clase.  
		Preguntaba por los comandos declarados en package.json. al parecer hay dos maneras de correr la tarea, llamandola en la terminal como lo hace leonidas en esta clase y creando el script de la tarea en el package.json como se muestra en la siguiente clase.

* **Rigo Antonio Galicia Barrera** (1)

	
	Estoy utilizando el comando npx webpack --entry ./index.js --output ./bundle.js y me da este error:
	
	Cannot find module ‘./ModuleError’

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Revisa que tengas correctamente instalado webpack, al parecer es un problema de instalación

* **Juan David Marin** (1)
Tengo una pequeña inquietud. Es buena practica sobre escribir en este caso el archivo bundle.js ? por lo que noto sí pero es una inquietud.

	* **Alejandro Zapata Molina** (1)

		
		Supongo que si, ya que ese archivo almacena el código para que el navegador lo entienda con todas las configuraciones que vamos añadiendo a medida que pasa el tiempo, entonces si no se sobre escribe el archivo estaríamos guardando muchos archivos con cinfiguraciones que ya probamos y creando uno nuevo por cada una, lo que sería inútil en mi punto de vista.

## 0050. Iniciando un webpack.config

### Descripción:


Al ir creciendo nuestra configuración de Webpack iremos agregando cada vez más banderas a nuestros comandos y terminará como una línea gigante en la terminal. ¿Cómo hacemos que esa línea sea muy pequeñita, personalizable y escalable? Por medio de un archivo llamado por defecto **webpack.config.js**.

Este archivo permite importar módulos usando el formato commonJS y recibe por lo menos dos configuraciones básicas, un **entry** y un **output**.

  * **Entry Point** : Es la ruta del archivo principal de nuestra aplicación JS a ser procesado por Webpack. Se pueden tener varios Entry Points.
  * **Output** : Es la ruta de salida donde va a generar nuestro bundle con todos nuestros archivos especificados como Entry Points empaquetados en uno sólo.



### Links:

* [clase 5 iniciando un webpack.config · LeonidasEsteban/webpack-4@227ae7b · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/227ae7b81808cedc92d4c6c74a779b3a91a68324)

### Comentarios:

* **Simón Arenas** (7)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-7b1cc62f-adc2-454f-b27b-9011b1a1ebea.jpg)
	
	Pueden ver todos mis apuntes de este curso [aquí](https://www.notion.so/simon98/Iniciando-un-webpack-config-7fa38d447edc450fa49a0f2d9ab386d5)😃

* **David Acevedo** (5)

	
	Resumen de clase:
	
	Otra forma de configurar nuestro webpack es usando el archivo **webpack.config.js**  
	Luego de crear el archivo hay que tener encuenta que por el momento webpack usa** common js**, para importa y exportar modulos.
	
	**Configuracion Basica**
	``` 
	    const path = require('path')
	    
	    module.exports = {
	      entry: './index.js',
	      mode: 'development',
	      output: {
	        path: path.resolve(__dirname ),
	        filename: 'bundle.js'
	      }
	    }
	    
	```
	
	luego de tener la configuracion, podemos probar su funcionamiento con el comando **npx webpack**  
	tambien es buena preactica usar npm scripts desde nuestro package json para configurar este comando usando
	``` 
	    "scripts": {
	        "build": "webpack"
	      },
	    
	```
	
	entonces podemos correr webpack desde la consola usando **npm run build**

	* **Facundo Nicolás García Martoni (Platzi)** (1)

		
		Excelente resumen!

* **Ricardo Lugo Recillas** (4)

	
	se genera un archivo webpack.config.js  
	donde se pone el siguiente codigo
	``` 
	    const path = require('path');  /*se instancoia el modulo de path de node*/
	    
	    /* El siguiente codigo en realidad es igual a lo siguiente */
	    /* npx webpack  --entry ./index.js  --output ./bundle.js --mode development */
	    module.exports = {
	      entry: './index.js',
	      mode: 'development',
	      output: {
	        path: path.resolve(__dirname), /*direccion relativca de posicion actual*/
	        filename: 'bundle.js'/*nombre de bundel */
	      }
	    }
	    
	```
	
	se ejecuta con npx webpack  
	o se genera un script dentro de package.jsom
	``` 
	    "scripts": {
	        "test": "echo \"Error: notest specified\" && exit 1",
	        "build" :"webpack"
	      },
	    
	    
	```

* **Marco Antonio Macedo Preciado** (4)

	
	Explico el código:
	
	Se requiere un modulo nativo de Node.js y se guarda en una constante llamada “path”.
	
	Despues vamos a exportar nuestra configuración haciendo un
	``` 
	    module.exports={
	    /*Así es como funcionan los módulos nativos en Node.js, es una forma de indicarle a otros archivos (en este caso webpack) que es lo que tiene que tomar de este archivo, todo lo que no este dentro del **module.exports** se ignorará.*/
	    
	    }
	    
	```
	
	Dentro de entry especificamos cual va a ser el archivo a transpilar con webpack en output creamos un json con path que indica la ruta de nuestro output (que funciona mediante la función resolve del modulo path para hacer que la ruta sea compatible con diferentes entornos, usando ademas la variable global de Node.js “__dirname” que se encarga de brindar la ruta actual en la que nos encontremos), ademas el campo filename que especifica el nombre archivo final.
	
	En mode especificamos el tipo de transpilación que queremos.
	``` 
	    entry  : "./index.js",
	      output : {
	        path     : path.resolve(__dirname),
	        filename : "bundle.js"
	      },
	      mode   : "development"```
	    
	    
	```

* **carlos ruales** (4)

	
	Para ejecutar comandos de webpack hay diferentes caminos 🛤. Anteriormente ejecutamos un comando con NPX para transpilar un archivos .JS y generarlo especificando un OUTPUT, pero esto puede ser en la práctica algo que quite más tiempo y engorroso.
	
	Para ello se puede crear un archivo de configuración de webpack. El nombre de este archivo en teoría puede ser cualquiera pero se recomienda llamarlo webpack.config.js.
	
	Dentro de este archivo se especificarán las acciones que queramos que webpack haga por nosotros. El archivo de ejemplo es este:
	``` 
	    const path = require(‘path’) /*este es un modulo de node y se encarga de la gestion de rutas*/
	    
	    /*Para exportar un modulo, se debe hacer de la forma de commonJS*/
	    module.exports = {
	        entry: ‘./index.js’, /*El archivo que queremos transpilar */
	        mode: ‘development’, /* modo de ejecución */
	        output:{ /*Configuraciones para el archivo final que generará webpack */
	            path: path.resolve(__dirname), /* La ruta en donde quedará el archivo final */
	            filename: ‘bundle.js’ /*El nombre con el que se creará el archivo final */
	        } 
	    }
	    
	    
	```
	
	Una vez se tenga esta configuración ⚙️ se puede llamar de dos maneras ✌🏽:
	
	  * con npx: Se puede llamar con este comando para que webpack tome el archivo de configuración y haga su proceso con base en este. El comando es
	
	
	``` 
	    npx webpack
	    
	```
	
	  * con npm: Dentro del archivo .JSON, dentro del objeto scripts se puede configurar un comando para ser llamado directamente por npm. El comando que se añadirá es: build, que a su vez llamará a webpack
	
	
	``` 
	    “scripts”:{
	        “build”: “webpack” //build sera el nombre que usaremos en consola
	    }
	    
	    
	```
	
	Para ejecutarlo basta con escribir en la consola 🤩:
	``` 
	    npm run webpack 
	    
	```

	* **Isaias Chávez** (2)

		
		Muchas gracias! Ahora entiendo un poco mejor.

* **Mariana Valencia** (3)

	
	Una de mis grandes frustraciones es no saber por qué algo se utiliza, comencé a ver React sin saber Webpack y ahora veo que todo es bastante más fácil de lo que pensaba

* **ingsis_john** (3)

	
	Los comandos npx se pueden simplificar mediante la configuración del archivo llamado webpack.config.js
	
	Se debe crear el archivo y añadir la libreria path, se crea un objeto y dentro se pasa la propiedad entry: ‘./index.js’, y la propiedad output: {path: ‘’, filename: ‘’} se le indica el mode y asimismo se puede indicar en el archivo package.json el comando para luego correrlo de la siguiente forma: `npm run build`en lugar de `npx ...` que esta a partir de la version 5.2 de npm

* **miguel angel goda molina** (3)

	
	en el script del packge se pueden llegar a tener varios nombres para correr codigo por ejemplo en webpack puede ser uno para hacer development y otro para hacer el build

* **Fabián andres Pedraza Borhorquez** (2)

	
	![cursoplatzi-webpack-webpack.config.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-webpack.config-8e065efe-d67d-4eb7-8757-7db14d1db03b.jpg) creo que en la practica estas configuraciones ya seran mucho mas sencillas

* **WSJedp** (2)

	
	Increíble como un solo vídeo puede cambiar la perspectiva de todo 😮

* **webrevolution** (2)

	
	recordando!!!

* **Deymer Hernandez** (2)

	
	Y las cosas empiezan a tener sentido.

* **Yaisel Hurtado González** (2)

	
	Sugiero cambiar el nombre del curso a **Curso de Magia Negra con Webpack **

* **Luis Rangel Castro** (2)

	
	bundle.js  
	ejecutando comando en modo production  
	![Screen Shot 2019-10-21 at 22.37.55.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-10-21%20at%2022.37.55-314d4f3d-f391-468e-9c0d-2810a3d52a51.jpg)

* **Isaias Chávez** (2)

	
	¿Eso significa que podriamos escribir dentro del los scripts del package.json ese comando grandísimo que se supone que nos ahorramos con el webpack.config.js? ¿Y sería igual?

	* **Andres Roberto Coello Goyes** (3)

		
		asi es es los escript de **package** son como variables con nombres cortos que pueden ejecutar instrucciones largas. en este caso.  
		_npm run build_ significa: **npx webpack --entry ./index.js --output ./creado.js --mode development** …

* **Jhon Alexander Perez Valencia** (2)

	
	NPX esta disponible desde la version 5.2 de NPM

* **jdiegochg10** (1)

	```
	    {
	      "name": "webpack-04",
	      "version": "1.0.0",
	      "description": "eso sera divertido",
	      "main": "index.js",
	      "scripts": {
	        "test": "echo \"Error: no test specified\" && exit 1",
	        "build": "webpack"
	      },
	      "keywords": [
	        "webpack"
	      ],
	      "author": "Julio Diego <diego_jd_28@hotmail.com>",
	      "license": "MIT",
	      "dependencies": {},
	      "devDependencies": {
	        "webpack": "4.42.1",
	        "webpack-cli": "3.3.11"
	      }
	    }```
	    
	```

* **emanuel-alejandro-mamani** (1)

	
	Geniaaal, aprendi unas par de cosas que no sabia de package.json

* **ehnbytes** (1)

	
	Hola comencé con Angular, node y react, ahora sigo con webpack

* **Uzi Rodriguez** (1)

	
	No me funciona el modo development, me muestra este error:
	
	Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.

	* **Jean León** (1)

		
		revisa que todo esté bién en tu archivo webpack.config.js

* **christian-magro-perez** (1)

	
	Gracias por la clase, yo soy de las personas que empecé con React y también Angular sin saber éste tipo de conceptos previos. Muy agradecido. Saludos

* **Aaron Yamil Luna Parrado** (1)

	
	Ya se porque dicen que Leonidas es un gran profesor. Se raja!

* **Hugo Arrazola Dotor** (1)

	
	ahora lo entiendo todo 😛

* **Manuel Rivera** (1)

	
	Excelente ir aprendiendo el por que de las cosas y de los cimientos de webpack 😄

* **Osvaldo Trejo** (1)

	
	Wooow que buena clase!

* **Luis Rangel Castro** (1)

	
	bundle.js  
	ejecutando comando en modo development  
	![Screen Shot 2019-10-21 at 22.36.34.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-10-21%20at%2022.36.34-9c49d8f6-9e0a-4dd5-97dc-3a177e31aacc.jpg)

* **webrevolution** (1)

	
	muy bueno el primer bundle

* **cesarcubillos** (1)

	
	Es muy chévere ver toda la configuración que tiene webpack, mucho tiempo viviendo sin esto jajaja

* **Smarin-jpg** (1)

	
	Alguien sabe por que me sale:  
	required is not defined

	* **Enrique Devars (Platzi)** (1)

		
		Creo que tienes un typo, la función se llama ‘require’

	* **Smarin-jpg** (1)

		
		Si asi es lo descubri hace un par de dias, facepalm.

* **Francisco Jherson Huacho Inga** (1)
Disculpen, en la clase anterior solo iniciaron el proyecto e instalaron webpack. Pero no realizaron el ejemplo del Entry y Output, además...

	* **Edward Steven Ramos Palacios** (1)

		
		Esta es la clase donde Leonidas escribe el entry y el output.:  
		[Clase](https://platzi.com/clases/1620-webpack/21116-iniciando-un-webpackconf-4/)

* **Adrian Garcia Saaib** (1)
Me dio mas dudas de como se trabaja en un equipo de desarrolladores, entonces en un Script yo guardo mis actualizaciones del App?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		El ideal es que los scripts sean de uso para todo el equipo de desarrollo.

* **newtongrav** (1)
Me sale este error al ejecutar npx webpack: Invalid configuration object. Webpack has been initialised using a configurati...

	* **AlexGarrixen** (3)

		
		Hola newtongrav al parecer tu error es de sintaxis.  
		Checa que este bien escrito la propiedad **path** porque lo escribiste como patch

* **Néstor López** (0)

	
	`npx` está disponible desde la version 5.2 de **npm**

## 0060. Cargando configuraciones por defecto y personalizadas

### Descripción:


Por medio del uso de la bandera `--config` podemos especificar un archivo de configuración externo con el nombre que queramos en lugar del nombre por defecto **webpack.config.js**.

### Links:

* [clase 6 Cargando configuración por defecto y personalizada · LeonidasEsteban/webpack-4@e8ead38 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/e8ead380a85225298e17d24db6dfc65d5d85aef9)

### Comentarios:

* **Mariana Valencia** (9)

	
	¡Más cursos con Leonidas!

* **David Acevedo** (8)

	
	Resumen de clase:
	
	En esta clase se agrego una configuracion de webpack diferentes para un build externo. para eso se agrego.  
	dentro de la carpeta **externals** un **webpack.config.js**  
	con la siguiente configuracion
	``` 
	    const path = require('path')
	    
	    module.exports = {
	      entry: path.resolve(__dirname, 'index.js'),
	      mode: 'development',
	      output: {
	        path: path.resolve(__dirname, 'dist' ),
	        filename: 'bundle.js'
	      }
	    }
	    
	```
	
	donde le indicamos que nuestro bundle se guarde dentro de la carpeta dist.
	
	Tambien se agregaron 3 cmandos en npm scripts para probar las diferentes ejecuciones.
	``` 
	    "scripts": {
	        "build": "webpack --entry ./index.js --output ./bundle.js --mode development",
	        "build:local": "webpack --mode production",
	        "build:external": "webpack --config ./external/webpack.config.js"
	      },
	    
	```

* **heysoypaez** (4)

	
	**Apuntes**
	
	  * Dentro de dist van los compilados de webpack (es una convencion de desarrolladores)
	
	  * Con --config le digo a webpack-cli donde esta el archivo de configuracion
	
	  * Es posible crear diferentes archivos config para webpack:
	
	
	
	``` 
	    "scripts": {
	        "build:local": "webpack --entry ./index.js --output ./bundle.js --mode development",
	        "build:production": "webpack --mode production",
	        "build:external": "webpack --config ./external/webpack.config.js"
	      },
	    
	```

* **Marvin Rafael Ancheta Cuéllar** (2)

	
	Excelente herramienta este webpack  
	Genial!!!

* **Andrés Felipe Cano Sierra** (2)

	
	De aquí salen los famosos :
	``` 
	    npm run dev
	    
	    npm run prod
	    
	    
	```
	
	**feels great man**

	* **webrevolution** (1)

		
		eh vuelto a nacer!!!

* **Enrique Devars (Platzi)** (2)

	
	¿Qué significa “dist”?

	* **Oscar Estuardo de la Mora** (12)

		
		 **dist** ribution como para referirse que es producto de distribución o producto final

* **Fabián andres Pedraza Borhorquez** (1)

	
	![cursoplatzi-webpackxdefectoypersonaliz.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpackxdefectoypersonaliz-36fa13a2-66ad-4221-9d3f-de837e23fbe2.jpg)  
	bastante real y funcional me enganche con webpack

* **Bernardino Villagra Baez** (1)

	
	Entre en un mundo de la cual no quiero salir!!!

* **Frank Carmona** (1)

	
	genial webpack!

* **ehnbytes** (1)

	
	Buen curso!!

* **Manuel Rivera** (1)

	
	Genial ! 😄

* **ingsis_john** (1)

	
	Las multiples configuraciones se manejan mediante los scripts en el packages.json
	
	Para el ejemplo se tiene que se crea una nueva carpeta llamada external y luego dentro se crea el archivo webpack.config.js  
	y se deja la misma configuración del archivo que se uso para la anterior clase, tambien se copiaron los archivos: index.js y index.html para que se genere el archivo bundle.js

* **webrevolution** (1)

	
	excelente!!!

* **muxproo** (1)

	
	Tienen algun tipo de nombre en expecifico la forma de como se escriben estas propiedades en este jS file para Webpack.config.js donde puedo encontrar mas informacion sobre como se tiene que ordenar cada plugin o y cada loaders oh no hay una forma expicifica de como se organiza la estructura este archivo .config.js y todo depende del desarrolador de plugin.

* **Julian Querol Polo** (1)

	
	Los archivos compilados no se suelen guardar en una carpeta public, que es la que lee el navegador?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		No necesariamente, todo depende de como configuras las rutas del servidor, puede ser assets, o static o dist, o el nombre que quieras.

* **Johan Stivens Suarez Galindo** (1)
Cuál es la diferencia cuando hablas entre desarrollo y producción en webpack?

	* **Didier Zúñiga** (2)

		
		Son modos diferentes de ejecutar tu proyecto, usas **development** para probar el funcionamiento de tu proyecto localmente, paquetes de desarrollo que estés usando, etc. Usas **production** cuando vas a subir tu proyecto a la nube para que sea accedido por tus clientes o usuarios, en production vas a omitir el uso de paquetes de desarrollo para que subas únicamente lo necesario y asi tu app sea segura y lo mas ligera posible en la nube.

* **Jose Alejandro Sorza Ubaque** (1)
Tengo un problema, en la terminal me esta dando un error en el que consiste que no puede encontrar el modulo. y no me deja dejando contin...

	* **Alejandro Zapata Molina** (2)

		
		Verifica que el archivo webpack.config.js está dentro de la carpeta external, parece que no lo puede encontrar.

* **lenielluzardo** (1)
Siempre se deben duplicar los archivos?

	* **pruebadate** (0)

		
		Podrias especificar tu duda?

## 0070. Múltiples puntos de entrada

### Descripción:


### Links:

* [clase 7 Múltiples puntos de entrada · LeonidasEsteban/webpack-4@b277299 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/b277299210b27c1f1db70697eb0c97ba69c3d052)

### Comentarios:

* **Sebastián Barre** (15)

	
	Ya que se está usando path para las rutas lo recomendable sería separar las carpetas por comas
	``` 
	    const path = require('path');
	    
	    module.exports = {
	      mode: 'development',
	    
	      entry: {
	        home: path.resolve(__dirname, 'src', 'javascripts', 'index.js'),
	        precios: path.resolve(__dirname, 'src', 'javascripts', 'precios'),
	        contacto: path.resolve(__dirname, 'src', 'javascripts', 'contacto')
	      },
	    
	      output: {
	        path: path.resolve(__dirname, 'dist', 'js'),
	        filename: 'bundle-[name].js'
	      }
	    };
	    
	```

	* **EmmanuelMr** (3)

		
		por qué esto es más recomendable? elimina la posibilidad de tener algunos errores o es por buenas practicas? así lo llegue a hacer en un principio pero después vi que también funciona así
		``` 
		    (__dirname, 'src/javascript/index.js')
		    
		```

	* **Facundo Nicolás García Martoni (Platzi)** (7)

		
		@EmmanuelMr porque justamente es el módulo “path” de npm el que transpila la dirección que le pasamos por parámetro al método “resolve” a los diferentes sistemas operativos, ya que algunos utilizan “/”, otros “”, otros “//” y así. Ese es el sentido de separar las carpetas por comas 😉

	* **pabloverduzcos** (1)

		
		Gracias por el dato 😄.

* **fullsquatdev** (5)

	
	Encontre un repositorio que me gusto para automatizar los entry points se llama glob  
	<https://github.com/isaacs/node-glob>  
	el ejemplo que me sirvio es este:
	``` 
	    const glob = require("glob");
	    
	    const entry = glob.sync('./path/to/entries/**/*.js')
	        .reduce((entries, entry) => Object.assign(entries, {[entry.split('/').pop().replace('.js', '')]: entry}), {});
	    
	    
	    ...entry
	    
	```

* **Johan Manuel Perez Soto** (4)

	
	Yo lo que utilizo actualmente para borra la distribución anterior es el siguiente script
	``` 
	    "rm -rf ./build & webpack --config ./multi-entry-points/webpack.config.js"
	    
	```
	
	Aun no se si es la mejor forma, pero es conocimiento que traigo del curso de terminal y linea de comandos… :v

	* **Juan José Vega Quintero** (1)

		
		rm -rf se tiene que usar con mucha precaución

* **Simón Arenas** (3)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-e2eb5c1a-fdc3-496f-b7a7-efea79eb359e.jpg)
	
	⚡Pueden ver todos mis apuntes de este curso [aquí](https://www.notion.so/simon98/Iniciando-un-webpack-config-7fa38d447edc450fa49a0f2d9ab386d5)😃

* **Cesar Zavala Varon** (3)

	
	Sinceramente… y quisiera que alguien me lo refute o debata. No seria mejor simplemente importar un archivo json que defina los path y el nombre del archivo?
	
	**Ejemplo:** un archivo llamado **entrypoints.json**
	``` 
	    {
	    	"Home": "./views/index.js"
	    }
	    
	    
	```
	
	Luego, Importar el archivo dentro del webpack.config.js y pasarle el valor al entry…
	``` 
	    const entries = require(‘entrypoints.json’)
	    module.exports = [
	     { 
	    		entry: entrypoints,
	    		...
	    
	```
	
	para que complicarnos tanto…

	* **Cris464** (1)

		
		lo que creo es que como path como ya esta definido y solo toca importar el modulo de node.  
		como definirias path en .json?  
		si no estoy mal el module de path esta escrito en .ts

* **Marco Antonio Macedo Preciado** (3)

	
	Para generar nombres de archivos usamos el template [name] 😉😉

* **David Acevedo** (2)

	
	Resumen de clase:
	
	En esta clase se ve como configurar multiples puntos de entradas y salida en nuestro webpack.
	``` 
	    const path = require('path');
	    
	    module.exports = {
	      entry: {
	        home:     path.resolve(__dirname, 'src/js/home.js'),
	        contacto: path.resolve(__dirname, 'src/js/contacto.js'),
	        precios:  path.resolve(__dirname, 'src/js/precios.js')
	      },
	      mode: 'development',
	      output: {
	        path:path.resolve(__dirname, 'dist'),
	        filename: 'js/[name].js'
	      }
	    }
	    
	```
	
	usando el template [name].js de webpack sabra en que archivos configurar la salidas.

* **Fabián andres Pedraza Borhorquez** (1)

	
	![cursoplatzi-webpack-multiplesPuntosdeEntrada.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-multiplesPuntosdeEntrada-12a3fbef-5c4d-44a6-aeda-1797e013ca05.jpg) casi no lo logro por culpa de una coma jeje

* **Jose Alejandro Sorza Ubaque** (1)

	
	Increible Clase 😃

* **Oscar Lozano** (1)

	
	Hola! al ejecutar npm run build:multi no se crearon los 3 archivos en dist/js/ que son contacto, index y precios los cree manualmente para poder avanzar.

	* **Jonattan_Infante** (1)

		
		¿Se generaba alguna en error en la terminal?

* **Manuel Rivera** (1)

	
	Por el momento todo corre de maravilla  
	![webpack.PNG](https://static.platzi.com/media/user_upload/webpack-b6d7d0b7-a3c0-4ba3-ae3e-9b6017e14e0c.jpg)

* **cesarcubillos** (1)

	
	Muy útil las múltiples entradas :v

* **Adrian Garcia Saaib** (1)

	
	También para efectos prácticos puedes agregar los 3 archivos de salida en el mismo html, agregando los 3 scripts.
	``` 
	    <scriptsrc="dist/js/contact.js"></script>
	        <scriptsrc="dist/js/home.js"></script>
	        <scriptsrc="dist/js/prices.js"></script>
	    
	```

	* **José antonio Cañizales** (2)

		
		En estos momentos funcionaria, pero no es recomendable por la escalabilidad, ya que un proyecto medio tendría al menos 100 archivos de js.

* **christian-magro-perez** (1)
Hola, cuando ejecuté npm run build:multi me arrojó el siguiente error: Invalid configuration object. Webpack has been initialised using a...

	* **Juan H** (1)

		
		Hola cristian! Dejaste sueltos a home, precios y contacto. No encuentra la configuracion **entry** por eso te dice que el archivo de configuracion es invalido. Deben estar dentro de **entry** ya que es una propiedad que si conoce
		``` 
		    const path = require('path')
		    
		    
		    module.exports = {
		        entry: {
		            home: path.resolve(__dirname,'src/js/index.js'),
		            precios: path.resolve(__dirname,'src/js/precios.js'),
		            contact: path.resolve(__dirname,'src/js/contact.js'),
		        },
		        
		        output: {
		            path: path.resolve(__dirname, 'dist'),
		            filename: 'js/[name].js'
		        }
		    }
		    
		    
		```
		
		Cualquier otra cosa no dudes en preguntar 😄

## 0080. Manejo de assets con Loaders

### Descripción:


 **Los Loaders** son la funcionalidad que nos da Webpack para interpretar tipos de archivos no soportados de forma nativa por Javascript.

**style-loader** sirve para inyectar un tag style (el CSS) al DOM de nuestro HTML, mientras que **css-loader** sólo sirve para interpretar archivos CSS.

### Links:

* [GitHub - webpack-contrib/css-loader: CSS Loader](https://github.com/webpack-contrib/css-loader)

* [GitHub - webpack-contrib/style-loader: Style Loader](https://github.com/webpack-contrib/style-loader)

* [Curso de Expresiones Regulares | Materiales](https://platzi.com/clases/expresiones-regulares/)

* [Curso de HTML y CSS | Materiales](https://platzi.com/clases/html-css/)

* [Curso de Responsive Design | Materiales](https://platzi.com/clases/responsive-design/)

* [clase 8 Manejo de assets con Loaders · LeonidasEsteban/webpack-4@15a625f · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/15a625f0057af482dc1b246b9b792d21123c6fc0)

### Comentarios:

* **Luis Arturo Lira Cerda** (13)

	
	Y no olviden que el orden de ejecución de los loaders es del último hacia el primero en el array. En este caso, primero se ejecuta css-loader y después se ejecuta style-loader.
	
	Si tuviéramos 5 loaders en el array, webpack los ejecutará en el orden de 5, 4, 3, 2 y 1 😃

	* **heysoypaez** (1)

		
		gracias por el apunte luis, me di cuenta a los trancazos, tomare el apunte para mis notas

* **Jorge Daniel Pat Navarro** (8)

	
	Puse primero el ccs-loader y luego el style-loader, me marco error
	``` 
	     use:['css-loader', 'style-loader']
	    
	```
	
	pero los puse como en el video y todo corrio bien, podria ser un buen punto a considerar. Si alguien sabe el porque, me encantaria saberlo 😄

	* **Tobías Schwarz** (11)

		
		Hola Jorge, esto es porque los loader siempre corren desde el último al primero, en ese orden. Por lo tanto en este caso debe ir último el css-loader ya que es el primero en correr y es el que permite que podamos usar el css en js, y primero (es decir para que corra segundo) el style-loader que lo que hará será colocar el css en el head del html.
		
		Si por ejemplo estuviésemos usando sass, debería ir:
		
		[‘style-loader’, ‘css-loader’, ‘sass-loader’]
		
		Para que primero se compile sass, luego se interprete el css, y por último los estilos se coloquen en el head con el style-loader.
		
		¿No sé si me expliqué mas o menos?

	* **Jeanmi94** (2)

		
		Buenísimo Tobías. La verdad es que estaba haciendo un proyecto con React y no me cargaba ni sass ni css. Como dijo nuestro señor: Los últimos serán los primeros.  
		Gracias me salváis la vida. haha

	* **Jorge Daniel Pat Navarro** (1)

		
		Gracias Tobías, ya entendi perfectamente, perdon por contestar un mes despues, no habia visto tu comentario.
		
		Me sacaste de una gran duda 😃

	* **lenielluzardo** (1)

		
		MUCHAS GRACIAS, la cabeza me iba a explotar jajaja!😂😂😂

	* **Juan H** (1)

		
		Ayyy, Gracias a tobias por la explicacion y a daniel por la solucion, Me estaba explotando por eso. Muchas gracias!

* **heysoypaez** (8)

	
	"no te preocupes si no sabes expresiones regulares yo tampoco copialo y pegalo, eso funciona" JAJAJAJJAJA

	* **Leonidas Esteban Gonzalez** (4)

		
		😅

	* **David Behar** (1)

		
		LOL

	* **heysoypaez** (2)

		
		Sea como sea, recomiendo aprenderlo, yo hice el curso de expresiones regulares de Beco aquí en Platzi y sin mentirle, lo uso todos los días, es oro!

* **lenielluzardo** (7)

	
	Los loaders deben declararse de la siguiente manera para que no de error:
	``` 
	     use: ['style-loader', 'css-loader']
	    
	```
	
	Estaba teniendo este problema y no encontre solucion en la web. **La solucion la encontre en uno de los comentarios de esta seccion. Muchas gracias! LEAN LOS COMENTARIOS😂😂😂**

* **Marco Flores** (6)

	
	css-loader => Sirve para **interpretar **el código css.  
	style-loader => Sirve para **inyectar **el css a mi html

* **heysoypaez** (6)

	
	 _Webpack pretende usar javascript como la base de operaciones de tu App_
	
	  * Los loaders nos permiten transpilar css a js.
	  * Css loader es quien transpila mi css al js.
	  * style loader es quien lo carga a mi HTML.
	
	
	
	**Comandos usados:**
	``` 
	    $ npm install --save-dev --save-exact style-loader
	    
	    $ npm install --save-dev --save-exact css-loader
	    
	    
	```

* **Karl Heitmann** (5)

	
	No te preocupes, si no sabes expresiones regulares… yo tampoco. Copiar y pegar.
	
	Este es mi profe favorito 😄 😄 😄

* **David Acevedo** (5)

	
	Resumen de clase:
	
	En esta clase vemos como webpack nos permite cargar otros achivos dentro de js en este caso importar archivos css dentro de un js.
	
	para esto tenemos que instalar 2 dependencias.  
	-css-loader -> carga de css  
	-style-loader -> css inyection  
	**Importante** -> El orden de ejecucion es desde el ultimo index del array al primero  
	el archivo de configuracion seria.
	``` 
	    const path = require('path');
	    
	    module.exports = {
	      entry: path.resolve(__dirname,'src/js/index.js'),
	      mode: 'development',
	      output: {
	        path: path.resolve(__dirname, 'dist'),
	        filename: 'js/bundle.js'
	      },
	      module: {
	        rules: [
	          {
	            test: /\.css$/,
	            use: [
	              'style-loader',
	              'css-loader'
	            ]
	          }
	        ]
	      }
	    }
	    
	```
	
	Con la expresión regular .css$/, le indicamos que permita esta carga en todos los archivos que terminan en .css

	* **Ivan Perea Fuentes** (1)

		
		Buen apunte, me estaba volviendo loco porque me daba un error muy extraño.
		
		Gracias!

* **Oscar Hernando Cabrera Plazas** (4)

	
	Me da la impresión que el comando que debía correr en el minuto 7:50 era el de npm run build:css , pero volvió a correr el de instalar el css-loader?

	* **diego-serrano** (1)

		
		Tengo la misma impresion.

	* **Johan Manuel Perez Soto** (1)
![](https://previews.123rf.com/images/leremy/leremy1502/leremy150200054/36629322-great-minds-think-alike.jpg)

	* **Oscar Velásquez** (1)

		
		Seep… Vine a los comentarios para ver si alguien se había dado cuenta… Creo que lo hizo intencionalmente para ver si estamos atentos jaja

* **Fernando Vallejo** (2)
Deberías utilizar git para versionar tu proyecto en cada clase.

	* **juanfar** (1)

		
		Ya, el problema es cuanto tiempo tomaría el curso, para eso está el curso de git.

	* **Henry Puentes Gonzalez** (1)

		
		La mayoría lo estamos haciendo! pero buen comentario para los que no…

	* **Gabriel De Andrade (Platzi)** (3)

		
		El profe lo está haciendo, acá te dejo el link, puedes ver que cada clase tiene un commit [GitHub](https://github.com/LeonidasEsteban/webpack-4) 😄

* **Diego Mierez** (2)

	
	Ayuda!  
	Cuando corro el buil:css me sale un asset de home.js pero cuando abro el index.html en el navegador me da error en la sentencia del import. Un error de sintaxis. Me dice que no puede importar fuera de un módulo.  
	¿Alguien puede ayudarme?

	* **DavidArmandoVelazquez** (1)

		
		Hola, puedes mostrar tu codio o el error que te aparece?

* **Diego Mierez** (2)

	
	Hola amigos 😃  
	Tengo un problema … el build me corre bien en la terminal pero cuando lo corro en el navegador no me corre el css.  
	Me dice que tengo un error en al importar css. Como que la secuencia impor '…/ ’ no puede ejecutarse fuera de un modulo.  
	Alguien tuvo este error?? me podrán ayudar??

	* **DavidArmandoVelazquez** (2)

		
		Si pusiste “…/” al momento de hacer el import, estas escribiendo un punto de mas

	* **Diego Mierez** (1)

		
		Hola @DavidArmandoVelazquez gracias por tu ayuda. No solo tenía un punto de más en el código sino que además, el error era que no estaba llamando al archivo correcto de js en el html 🤦‍♂️

* **Manuel Rivera** (2)

	
	Min: 6:08  
	El error que le muestra al profe es por que esta importando un archivo que no existe, pues el esta queriendo importar el archivo index.css pero no lo ha creado, el verdadero error que nos da la consola por que no puede interpretar css dentro de un archivo js es el siguiente.
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-a230d8b7-2533-4cd4-ac87-04868359d71f.jpg)
	
	Lo adjunto por si no lo topamos en otra ocasión y conocer cuál es el error que nos muestra en consola y saber que hacer.

* **FizIrvin** (2)

	
	Muy buena explicación Leo. En varios proyectos, he visto que cargan el Loader de CSS a la configuración de webpack, y ahora estoy asimilando por qué se utiliza tanto al hacer una app en js. Uno lo ve natural principio, como si fuera parte de javascript inyectar css o por defecto lo hiciera, pero no es así, sino hay que configurarlo.

	* **Aram Ceballos Gonzalez** (1)

		
		Exacto, al principio uno puede pensar que js lo hace por defecto pero no es asi, quien lo hace es webpack

* **Johan Manuel Perez Soto** (2)

	
	Luego de repetir un par de veces se entiende 😂😂

* **Adrian Garcia Saaib** (2)

	
	Ahora quiero hacer el curso de expresiones regulares D:

* **Daniel .** (2)

	
	Deberian unir los loader css y style

* **luis-carlos-zabala** (2)
Saludos a todos, Siguiendo la practica del curso, traté de importar el archivo css en el JS corriendo el webpack (npm run build_css y com...

	* **Fernando Alejandro Yerena Ramos** (1)

		
		¿Puedes mostrarnos el package.json y el webpack.config.js?  
		Es probable que el _script_ esté buscando el archivo de configuración en otra carpeta a la de esta clase.

* **Fabián andres Pedraza Borhorquez** (1)

	
	![cursoplatzi-webpack-assets-loader.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-assets-loader-12b52037-5af8-4b2f-890e-8648d831092e.jpg) muy buen aprendizaje

	* **Alejandro Jimenez** (1)

		
		Perfeeecto

* **Daniel Lopez** (1)

	
	¿En que ocasiones seria util llamar un css en un js?

	* **Alejandro Jimenez** (1)

		
		Yo también me hice esa pregunta pero creo que es de ese tipo de cosas que probablemente nunca usemos pero es bueno saber que se pueden hacer por si acaso.

* **NestorBeltran** (1)

	
	Hola, a mi me tiraba error el innerHTML, mi solución fue poner el inner dentro de window.onload

* **Nycgia** (1)

	
	Para los que tengan un error similar a este:
	``` 
	    ERROR in ./src/assets/styles/index.css
	    Module build failed (from ./node_modules/css-loader/dist/cjs.js):  
	    CssSyntaxError
	    
	    (1:1) Unknown word
	    
	```
	
	Se debe al orden de los loaders, el correcto es:
	``` 
	    module: {
	            rules: [
	                {
	                    test: /\.css$/,
	                    use: [
	                        'css-loader',
	                        'style-loader',
	                    ]
	                }
	            ],
	        }
	    
	```

	* **frontendwenance** (0)

		
		probe hacer eso pero sigo con el mismo error

	* **jorge-hernandez** (2)

		
		El orden correcto es:
		``` 
		    rules: [
		          {
		            test: /\.css$/i,
		            use: ['style-loader', 'css-loader'],
		          },
		        ]
		    
		```

* **Alfredo Gonzalez** (1)

	
	Si tienen algún problema, tal vez estén pasando el valor de test en el webpack.config.js como un string, el valor se pasa como tal

* **FerPM** (1)

	
	por ahora anda y la verdad es increíble como aparece el css sin ser llamado. no puedo entender donde esta la magia. Me siento como dentro de Photoshop haciendo retoque digital!

* **FerPM** (1)

	
	Como hicieron para instalar la misma version que el profe?  
	yo probé con:  
	npm install -D -E css-loader@2.1.1  
	y me dió error  
	tuve que seguir al profe y me quedó la version  
	"css-loader": “3.4.2”,  
	SUPERNADAQUEVER!!!

	* **FerPM** (1)

		
		ya pude como explica Leonidas en la siguiente clase. Lo logré con el comando:  
		npm install --save-dev css-loader@2.1.1

* **Jessie Buckland Pérez** (1)

	
	¿!¿! Que no panda el cúnico ?!?! 😄 😄

* **Mariana Valencia** (1)

	
	Me encantó esta clase ❤️

* **Manuel Rivera** (1)

	
	Excelente 😄

* **Juan Pena Verdú** (1)

	
	Ayyyy... que no pande el púnico! xD

* **Andres Roberto Coello Goyes** (1)

	
	Me sigue marcando el error …css/index.css al momento de importar el css dentro del js. apesar de tener las 2 dependencias instaladas…  
	??

	* **Jessen Mercado** (1)

		
		Hola, sube tu código para poder ayudarte 😄

	* **Andres Roberto Coello Goyes** (1)

		
		Ya aprobé el curso ayer.  
		Gracias por tus intenciones 😊😉

* **alexjcm** (1)

	
	Luego de este curso toca seguir el curso de expresiones regulares 😂

* **Wilson Marino Pablo Mendez** (1)

	
	L O L 😃

* **Angel Jose Hinostroza Calderon** (1)

	
	Donde se pueden encontrar todos los loaders que existen?

	* **Favio Sauto** (3)

		
		De aquí: [loaders de webpack](https://webpack.js.org/loaders/) y aquí: [loaders de terceros](https://github.com/webpack-contrib/awesome-webpack#loaders)
		
		El primero es del equipo de Webpack

* **Luis Miguel Rodriguez** (1)

	
	3:35 excelente jajaja

	* **onlinejaime** (1)

		
		3:47 mejor, quizá???

* **Juan David Marin** (1)
No entiendo por que me da el error, importo style-loader que esta en 1.1.3

	* **Erik Ochoa (Platzi)** (1)

		
		¿Qué error te da **@Juanmany29**? compártelo para poder ayudarte.

* **heysoypaez** (1)
Veo que el CSS termina inyectando los estilos en una etiqueta style en el HTML ¿Esto es lo ideal ? ¿Habra una forma que cree...

	* **Fernando Alejandro Yerena Ramos** (2)

		
		Para desarrollo viene bien. Acelera el proceso que hace Webpack por detrás.
		
		Con el uso de _plugins_ se puede hacer lo que mencionas. En la siguiente clase, Leonidas toca el tema. 😄

* **Byron Miguel Piedrahita Hernandez** (0)
El Syle-loader solo sirve para interpretar el codigo css y Syle-loader sirve para inyectar css a mi html. Esto esta bien esplicado? paso ...

	* **Manuel Ojeda** (2)

		
		 **css-loader** carga y lee los estilos en algún archivo css que este haciendo include a tu archivo js.  
		**styles-loader** hace la inyección de esos estilos al html sin generar un archivo css al momento realizar la compilación del proyecto.

## 0090. Introducción al uso de plugins

### Descripción:


 **Los Plugins** sirven para extender las capacidades de webpack y dar más poder a los loaders.

### Links:

* [GitHub - jantimon/html-webpack-plugin: Simplifies creation of HTML files to serve your webpack bundles](https://github.com/jantimon/html-webpack-plugin)

* [GitHub - webpack-contrib/mini-css-extract-plugin: Lightweight CSS extraction plugin](https://github.com/webpack-contrib/mini-css-extract-plugin)

* [Commits · LeonidasEsteban/webpack-4 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commits/master)

### Comentarios:

* **David Acevedo** (6)

	
	 **Resumen de clase:**
	
	En esta clase se vio una introduccion a el uso de plugin en webpack con dos muy utiles.
	
	**MiniCssExtractPlugin**  
	npm install mini-css-extract-plugin --save-dev
	
	Este plugin nos generara nuestro archivo de estilos de forma separada.  
	**HtmlWebpackPlugin**  
	npm install html-webpack-plugin --save-dev
	
	Este archivo nos generara un estructura html con los archivos js y css de dist ya importados
	
	webpack.config.js:
	``` 
	    const path = require('path');
	    const MiniCssExtractPlugin = require('mini-css-extract-plugin');
	    const HtmlWepackPlugin = require('html-webpack-plugin');
	    
	    module.exports = {
	      entry: path.resolve(__dirname, 'src/js/index.js'),
	      mode: 'development',
	      output: {
	        path: path.resolve(__dirname, 'dist'),
	        filename: 'js/index.js'
	      },
	      module: {
	        rules: [
	          {
	            test: /\.css$/,
	            use: [
	              {
	                loader: MiniCssExtractPlugin.loader
	              },
	              'css-loader'
	            ]
	    
	          }
	        ]
	      },
	      plugins: [
	        new MiniCssExtractPlugin({
	          filename: 'css/[name].css'
	        }),
	        new HtmlWepackPlugin({
	          title : 'Nuevo titulo con el plugin htmlwebpackplugin'
	        })
	      ]
	    }
	    
	```

* **edwintrumpet** (6)

	
	Noté que al crear el nuevo archivo html como no se basa en el archivo original que ya teníamos perdí por ejemplo el viewport y la configuración de idioma.  
	En la [documentación](https://www.npmjs.com/package/html-webpack-plugin) dice como construir nuestros templates personalizados.  
	Lo que hice fue hacer que tomara el archivo que ya tenía construido como base para que inyecte el css y javaScript sobre ese así:
	``` 
	    newHtmlWebpackPlugin({
	    	title: 'My first bundle',
	    	template: path.resolve(__dirname, 'src/index.html');
	    })
	    
	```
	
	Ahí ya toma como template el archivo que teníamos, y para agregar de forma dinámica el title debemos editar esa parte en el archivo html original así:
	``` 
	    <title><%= htmlWebpackPlugin.options.title %></title>
	    
	```

* **JarlLuis** (5)

	
	Auto-magica-mente

* **FerPM** (4)

	
	es este punto me surge una duda. si tengo un CSS, ¿para que lo inyecto el JS? si después lo voy a linkear a my html? Ademas no entiendo ¿para que quiero exportar un css que ya tengo?

	* **romerodiesan** (6)

		
		A veces usas preprocesadores como sass, stylus, o incluso librerías como React y frameworks como Angular, dónde vas a necesitar configuraciones como esas. El objetivo es que uses herramientas como las que te mencioné anteriormente y luego que Webpack se encargue de convertir tooodo eso, en HTML, CSS, JavaScript. Una magia donde todo quede optimizado de la mejor manera posible, y que corra en todos los navegadores, y sin importar versión.

	* **FerPM** (2)

		
		Gracias Romero. Me sirvió de mucho tu respuesta

	* **romerodiesan** (1)

		
		De nada @FerPM

* **Andres Roberto Coello Goyes** (4)

	
	las versiones de las dependencias son importantes, tuve un gran problema con webpack…

	* **Juan José Vega Quintero** (2)

		
		Yo no e instale las más recientes

* **Claudio Jesus Vázquez Villanueva** (4)

	
	Me encanta que te das cuenta de tus Errores y no los ocultas Grande Leonidas!

* **Wilson Marino Pablo Mendez** (4)

	
	Me estoy arriesgando a usar las últimas versiones, espero no tener problemas en el transcurso del curso.

	* **luis-carlos-zabala** (2)

		
		Igual yo, estoy usando las últimas versiones, hasta el momento todo bien!

	* **Alan Santiago** (2)

		
		La versión actual de _webpack_ es la **4.39.1** , mientras no cambie el primer número _(4)_ no van a haber cambios tan drásticos entre la versión del curso y la versión que uses 🤠

* **SOFTDYNAMIC** (3)

	
	All commands still working until now with new versions

* **Adrian Garcia Saaib** (2)

	
	como puedo hacer para que mi css de salida salga minificado?

* **edwintrumpet** (2)

	
	Encontré que el html-webpack-plugin incluye una opción en configuración para minimizar el archivo html de salida así:
	``` 
	    newHtmlWebpackPlugin({
	    	minify: {
	    		collapseWhitespace: true
	    	}
	    })
	    
	```
	
	¿El otro plugin mini-css-extract-plugin trae algo parecido o toca instalar otros paquetes para minimizar?

* **edwintrumpet** (2)

	
	Veo que lo que hicimos aquí fue crear un archivo html completamente diferente, no estamos inyectando el css y el javaScript al archivo html que ya teníamos porque ya no tiene las mismas etiquetas y si ponemos contenido al archivo anterior nos damos cuenta que no aparece en el nuevo archivo.

* **FerPM** (2)
en el punto 7:40 de esta clase me surge una duda: Si tengo un CSS, ¿para que lo inyecto el JS? si después lo voy a linkear a my html? Ade...

	* **Juan H** (3)

		
		Hola fer. Ese css puedes minificarlo, hacer que pese menos. Ademas ayuda en la organizacion del proyecto. podrias tener muchos css dsitintos para distintos js (Como en ReactJS) y despues inyectarlos todo en uno solo y hacerlo mas pequenos. O trabajar con SASS o LESS y compilar a css

* **luis-carlos-zabala** (2)
Si se tiene contenido en el index.html que está fuera de dist, ¿este nuevo .html que se está generando debe igual traer el contenido del ...

	* **Fernando Alejandro Yerena Ramos** (4)

		
		Por defecto [`HTML Webpack Plugin`](https://github.com/jantimon/html-webpack-plugin#options) genera un nuevo `.html`.  
		Si cuentas con un archivo index.html, puedes configurar `HTML Webpack Plugin` para que use ese archivo como plantilla.
		``` 
		    	newHtmlWebpackPlugin({
		    		title: "Plugins"
		    		template: "./src/templates/index.html",
		        }),
		    ``
		```

* **Fabián andres Pedraza Borhorquez** (1)

	
	![cursoplatzi-webpack-plugins.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-plugins-28d91764-6fa9-425b-bcf9-9d94e2632bb3.jpg) super gracias leonidas

* **BRYAN ALEXANDER CONDOR DE LA CRUZ** (1)

	
	plugins webpack.config.js

* **Jemd** (1)

	
	Adoro el carisma de Leonidas no deja que te aburras en sus cursos, cada curso dictado por él es una joya

* **Juan H** (1)

	
	Como funciona un loader junto a un Plugin

* **Manuel Rivera** (1)

	
	Entonces se puede decir que path es un plugin ya instalado por defecto en webpack ?

	* **nick** (1)

		
		Hola, amigo, path es un módulo nativo de Node.js que toma strings como parámetros y retorna un string nuevo, por eso es que hacemos el require(‘path’) sin instalar nada, porque Node.js lo busca en su core, ahora al momento de instalar un plugin lo que sucede es que al buscarlo con require(‘x’) node también busca en la carpeta de node_modules de tu proyecto lo que permite usarlo sin especificar un path adicional como ‘./plugins/x’;

	* **Yank Carlos Reyes Espinal** (1)

		
		Ey, para más información, siempre puedes leer la doc del paquecte 😃
		
		<https://nodejs.org/api/path.html>

* **Marco Flores** (1)

	
	HtmlWebpackPlugin => Plugin que **inserta** los **bundles** al html.

* **Marco Flores** (1)

	
	loaders => **interpretan **los tipos de archivo.  
	plugins => **Extienden** los poderes de los loadres.

* **lenielluzardo** (1)

	
	En esta clase creo que comprendi al 100% el concepto de los** entry points**, yo lo entendi asi:  
	-al usar el template de webpack para el nombre del archivo .css, éste toma el nombre del **entry point** de home, ya que desde el archivo **_home.js_** es que se ‘‘llama’’ al .css.
	
	  * Entonces quiere decir que el plugin lo que hace es ir al home.js, verifica que exista un archivo .css importado, accede a él (.css) y entonces lo minifica, definiendo el nombre del archivo con el nombre del ‘punto de entrada’ que uso para llegar a él.
	
	
	
	Alguien me entendio?😂😂😂

* **Karl Heitmann** (1)

	
	Además, este profe coloca bien los enlaces y archivos. Muy bien!!!

* **Karl Heitmann** (1)

	
	“Adivina como se llama…” siii!! yo lo adiviné!!! Jajaja, estas son las mejores clases!!!

* **José Tuzinkievicz** (1)

	
	Cómo “sabe” el plugin que que tiene que exportar el HTML en la carpeta dist?

	* **SantiagoPrietoA** (2)

		
		output: {  
		path: path.resolve(__dirname, ‘dist’), <== Esta linea es la respuesta  
		filename: ‘js/[name].js’  
		},

	* **José Tuzinkievicz** (1)

		
		Gracias Santiago!

	* **idmevander** (1)

		
		Acotacion, me pregunte lo mismo, segun la documentacion del plugin si quieres añadir una otra ruta que no sea el dist que configuramos en el output, se puede hacer con 'filename: ‘otracarperta/[name].html’

* **Alan Santiago** (1)

	
	¿Para producción es necesario siempre producir un _.css_ y después importarlo desde el _index.html_?

	* **Marco Antonio Macedo Preciado** (2)

		
		Sí, facilita el mantener los archivos en servidores externos.

* **eyesidmorenov** (1)

	
	new HtmlWebpackPlugin({  
	template: “./src/templates/home.html”,  
	filename: “index.html”,  
	chunks: [‘home’]  
	}),  
	new HtmlWebpackPlugin({  
	template: “./src/templates/contact.html”,  
	filename: “aboutus.html”,  
	chunks: [‘contact’]  
	}),`
	
	Para que no genere error la forma correcta es HtmlWebPackPlugin  
	es decir la P de pack va en mayúscula.
	
	Saludos y Éxitos…

* **eyesidmorenov** (1)

	
	<body>  
	<div id=“root” class=“row”>  
	INDEX …  
	</div>  
	<script src=“javascripts/libs/sweetalert2.min.js”></script>  
	<script src=“javascripts/libs/jquery-2.2.2.min.js”></script>  
	<script src=“stylesheets/js/materialize.min.js”></script>  
	</html>
	
	<script type=“text/javascript” src="…/js/P.js"></script>
	
	Alguien sabe como hago para que no genere el bundle por fuera de la plantilla…
	
	Gracias…

* **Victor Ruiz** (1)

	
	Que es mejor o más utilizado, hacer uso del css desde el import en javascript ó manejarlo como documentos separados con el plugin de html?

	* **Diego Alexander Forero Higuera (Platzi)** (6)

		
		En mi opinion las dos son igual de validas, todo depende si escribes css puro o usas preprocesadores, en el segundo caso es mejor usar el import en JavaScript para que este pueda hacer la transformación a css y minificarlo, etc.

	* **Victor Ruiz** (1)

		
		Me parece muy buena recomendación lo que comentas, muchas gracias.

* **sergiocastilla** (1)

	
	Me da un error y no e porque
	``` 
	    <code>
	    
	    $ npm run buid:plugins
	    npm ERR! missing script: buid:plugins
	    
	    npm ERR! A complete log of this run can be found in:
	    npm ERR!     C:\Users\SERGIO\AppData\Roaming\npm-cache\_logs\2019-07-20T10_40_15_807Z-debug.log
	    
	    </code>
	    
	```

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Estas escribiendo buid debe ser build

* **Angel Jose Hinostroza Calderon** (1)

	
	Si tuviera 2 archivos html y 1 archivo css como puedo yo especificar que ese archivo css se referenciara en uno de los 2 archivos html?

	* **Abner Paul Ccari Lindo** (1)

		
		Cada archivo html deberia tener su propio entry, es decir un archivo js (como en la clase de multi-entries), y es ahi donde podrias importar el css al entry que deseas.

	* **Abner Paul Ccari Lindo** (1)

		
		Y para finalmente generar el html con su entry.js en especifico, tendrias que usar un atributo de htmlwebpackplugin llamado ‘chunks’, que tambien podria ser uno o varios.
		``` 
		    entry: {
		            home: path.resolve(__dirname,'src/js/index.js'),
		            contact: path.resolve(__dirname,'src/js/contact.js'),
		        },```
		    
		    
		    
		    
		```
		
		Y en tus plugins:
		``` 
		    new HtmlWebpackPlugin({
		          template: "./src/templates/home.html",
		          filename: "index.html",
		          chunks: ['home'] 
		        }),
		        new HtmlWebpackPlugin({
		          template: "./src/templates/contact.html",
		          filename: "aboutus.html",
		          chunks: ['contact']
		        }),```
		    
		```

	* **eyesidmorenov** (1)

		
		No hay forma que usando algo a si
		
		new HtmlWebpackPlugin({  
		template: “./src/templates/XXXXXXX.html”,  
		filename: “html/XXXXXXX.html”,  
		chunks: [‘XXXXXXX’]  
		}),
		
		Es decir XXXXXXX por name funcione… Asi evitar que declarar uno por uno… Hay forma de hacerlo genérico ???
		
		Gracias!!!

* **Juan Carlos García Esquivel** (1)
¿Porque los plugins se importan al archivo webpack.config.js y los loaders solo se instalan?

	* **Luis Arturo Lira Cerda** (3)

		
		Nunca me había preguntado eso, pero supongo que es porque un plugin necesita ser instanciado para poder acceder a sus métodos o pasarle una configuración y que este le indique al compilador de webpack el comportamiento que deberá tener.
		
		Y un loader es sólo una serie de instrucciones de cómo el compilador de webpack tratará los archivos que le especifiquemos o para los que esté creado dicho loader.
		
		Lo entiendo como que los loaders son sólo para extender la capacidades de webpack y los plugins son los modifican el comportamiento de webpack.

* **Yaisel Hurtado González** (1)
¿Existe algún repo en Github con los códigos de este curso?

	* **Ruben Padilla** (2)

		
		Hola!
		
		[Repositorio del curso de Webpack v4](https://github.com/LeonidasEsteban/webpack-course-v4) 👈

* **eduardoluisgr** (1)
¿Cómo hago para que webpack cambie los nombres de mis clases por un hash? yo uso CRA y realicé el eject

	* **Juan David Castro (Platzi)** (1)

		
		👉 [Customize Webpack configuration of React Apps created with create-react-app](https://medium.com/@ryoldash/customize-webpack-config-of-react-app-created-with-create-react-app-7a78c7849edc)

* **cesarcubillos** (1)
¿El archivo home quedó minificado? En mi caso no quedó.

	* **Manuel Ojeda** (2)

		
		¿Utilizaste los comando tal como Leonidas nos muestra?  
		Es importante seguir la clase al pie de la letra.
		
		¿Qué comandos utilizaste?  
		¿Cómo tienes tu package.json y webpack.config?

## 0100. Servidor de desarrollo

### Descripción:


### Links:

* [GitHub - webpack/webpack-dev-server: Serves a webpack app. Updates the browser on changes. Documentation https://webpack.js.org/configuration/dev-server/.](https://github.com/webpack/webpack-dev-server)

* [clase 10 - Servidor de desarrollo · LeonidasEsteban/webpack-4@fe46266 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/fe46266ebd4d5567102e21cda48f185af60dc953)

### Comentarios:

* **jorge-gianareas** (13)

	
	Les dejo un link para complementar la excelente clase del profesor: <https://youtu.be/vF2emKbaP4M>
	
	Webpack 4 es un empaquetador de módulos, muy utilizado en archivos del Frontend y necesario en todos los frameworks de Javascript como React, Angular, y Vue.js y otros desarrollos de Javascript en el Frontend.
	
	CURSO DE NODEJS  
	<https://youtu.be/BhvLIzVL8_o>
	
	APLICACION DEL CLIMA CON JAVASCRIPT Y WEBPACK  
	<https://youtu.be/yxT6ylPM7uM>
	
	CLON DE GITHUB CON WEBPACK  
	<https://youtu.be/I4kJKnu6_jc>
	
	VARIABLES DE ENTORNO EN NODEJS  
	<https://youtu.be/U6st9-lNUyY>
	
	RED SOCIAL NODEJS Y MONGODB  
	<https://youtu.be/TqC3e8nBycg>
	
	JAVASCRIPT ORIENTADO A OBJETOS CON WEBPACK  
	<https://youtu.be/nqre9kKFRpc>
	
	CURSO DE GIT:  
	<https://youtu.be/HiXLkL42tMU>
	
	VIDEO DE VSCODE:  
	<https://youtu.be/zbycB-Yetb0>
	
	VISITA MI SITIO WEB PARA MÁS CURSOS Y TUTORIALES  
	<http://www.faztweb.com>  
	<http://blog.faztweb.com>
	
	FAZT CODE - YOUTUBE:  
	<https://www.youtube.com/channel/UCMn2>…
	
	TWITTER  
	<http://twitter.com/fazttech>
	
	INSTAGRAM  
	<https://www.instagram.com/fazttech/>
	
	FACEBOOK  
	<http://facebook.com/fazttech>
	
	COMUNIDAD EN DISCORD  
	<https://discord.gg/37PHuNw>
	
	#webpack #javascript #frontend

	* **Manuel Rivera** (1)

		
		ya me suscribí bro, mire por encima 3 videos y esta muy cool tu contenido y la forma de explicar, muchas gracias, los miraré completos para aprender aún mas.

* **Manuel Rivera** (10)

	
	Ahora ya vamos descubriendo al mago que esta detrás de Create-react-app jajajjaaj 😄

* **isncsanchez** (6)

	
	En caso de que necesitan cambiar donde se corre el weback-dev-server, pueden aniadir la siguiente configuracion en el exports del config. ( Yo por ejemplo tube que hacerlo para exponerlo del contenedor de docke ).
	
	![Configuracion de dev server.png](https://static.platzi.com/media/user_upload/Configuracion%20de%20dev%20server-bf713125-115f-472c-a087-912e5cf31d89.jpg)

	* **Juan Carlos García Esquivel** (1)

		
		Buen aporte, muchas gracias

* **FerPM** (4)

	
	queda como el hot reload de Flutter!!! Grabas y ves cambios!!!  
	Me viene bien para no extrañar tanto ya que por motivos laborales me tuve que pasar a React.

* **David Behar** (4)

	
	## Webpack Dev Server o Servidor de desarrollo
	
	[webpack-dev-server](https://github.com/webpack/webpack-dev-server) es un [CLI (command line interface)](https://www.w3schools.com/whatis/whatis_cli.asp) que se puede usar para hacer un entorno de desarrollo de manera sencilla, ya que de manera nativa recargará los archivos que se modifiquen en tiempo real.  
	.  
	`webpack-dev-server` usará [webpack](https://webpack.js.org/) con un servidor de desarrollo cuya funcionalidad principal es la recarga en vivo. Esto debe usarse para **desarrollo solamente** porque estará escuchando los cambios que se realicen en tiempo real, lo que es una carga innecesaria en memoria, porque los archivos en servidores de producción no deberían cambiar seguido, haciendo insostenible el uso intensivo de la aplicación.  
	.  
	`webpack-dev-server` utiliza [webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) por debajo, mismo que proporciona un acceso rápido en memoria a los assets de webpack.

* **gosunkugi** (3)

	
	chicos… no entiendo muy bien la diferencia entre --watch y – --watch

	* **Carlos Martinez** (5)

		
		hola, verás la diferencia es que cuando queremos escribir un script en el package.json lo hacemos agregandole `--watch` al final.
		
		ahora, si lo quieres “probar” o hacer directamente desde la terminal debes correr tu comando con ciertos cambios , es decir, le agregas el `--`  
		por ejemplo:  
		en el package.json tendrías un script  
		`"build:dev: "webpack --mode development --watch"`
		
		pero directamente desde la terminal seria:  
		`"build:dev: "webpack --mode development -- --watch"`
		
		aunque mejor sale instalarse el webpack-dev-server

	* **Carlos Martinez** (3)

		
		un pequeño error jeje  
		en la terminal sería  
		`npm run build:dev -- --watch`

	* **Alan Santiago** (3)

		
		Es básicamente se usa “–” para agregar las siguientes _flags_ que quieras al comando original de _npm_ que creaste.  
		.  
		Por ejemplo, si escribes `npm run build:dev -w` habrá un problema, puesto que se entiende que esa _-w_ es una opción del comando _npm run_. Lo que en verdad quieres hacer es llamar al comando `webpack --config ./ejemplo/webpack.config.js` y agregarle a **ese comando interno** la flag _-w_ , así que lo que haces es esto:
		``` 
		    $ npm run build:dev -- -w
		    
		```
		
		Cuando escribes eso, se agrega lo que haya después del _–_ al comando interno, así que sería lo mismo a que escribieras `webpack ./ejemplo/webpack.config.js -w`  
		Espero te sea de ayuda 🤠

* **iamyoujared** (3)

	
	Si por alguna razón te sale error de **constructor is not a function**  
	Lo resuelves instalando esto 👇  
	npm install fsevents -f

* **David Acevedo** (3)

	
	En esta clase aprendimos como hacer que nuestro navegador haga reload cuando escuche los cambios en los archivos de desarrollo  
	Instalando la librería: npm install webpack-dev-server --save-dev  
	y usando nuestro comando de npm scripts:
	
	`json "build:dev": "webpack-dev-server --config ./webpack-server/webpack.config.js"`

* **javier-andres-bonilla-leiva** (2)

	
	sería muy practico ser NEO y con un disco y una conexión a la cabeza… dieran el comando upload reactjs + webpack +… y al despertar uno dijera…
	
	  * ya se hacer paginas modernas!
	
	
	
	jajajaja 😃

	* **Jessie Buckland Pérez** (2)

		
		Apúntate al programa Neuralink!!! 😉

* **Adrian Garcia Saaib** (2)

	
	Hay plugins que entre ellos causan conflictos al mostrar la salida?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Puede llegar a existir problema si se espera un flujo y se cambia el orden de los plugins, por ejemplo si quieres minificar el css y trabajas con stylus, entonces primero debes pasar de stylus a css y luego si minificar, pero si colocas primero el plugin de minifcación no va a realizar ninguna acción porque no hay css aun y va a terminar saliendo el css sin minificar.

* **brayaninchea** (2)

	
	¿Se puede ver en el celular también al mismo tiempo cuando usas el webpack-dev-server?

	* **Abner Paul Ccari Lindo** (6)

		
		Claro que si!  
		Webpack-dev-server por default agarra el localhost, pero para que pueda ser accesible exteriormente (obviamente en la misma red) debes incluir esto en tu webpack.config.js en modules.exports :
		``` 
		    devServer: {
		            host: '0.0.0.0', 
		            port: 8080, // Si deseas cambiar el puerto que tambien viene por default 8080
		        },
		    
		```
		
		No te olvides que para abrirlo en otro dispositivo debes poner tu IP y agregar el puerto (como 192.168.1.10:8080).
		
		Tambien puede incluirlo por el CLI
		``` 
		    webpack-dev-server--host 0.0.0.0
		    
		```

	* **edwintrumpet** (3)

		
		Usualmente cuando uno levanta un servidor en localhost puede accederse desde otros dispositivos que estén conectados a la misma red de internet usando una ip.  
		la ip de localhost usualmente es 127.0.0.1 pero esta sólo sirve para el mismo computador.  
		Yo averiguo cuál es la ip desde la que se puede acceder a mi computador usando el comando `ifconfig` en Linux o `ipconfig` en Windows y me da una ip algo así 192.168.0.**  
		La cosa es que lo intenté hacer con este servidor que levanta webpack-dev-server y rechaza la conexión desde mi celular 😦

	* **Luis Rangel Castro** (1)

		```
		    const path = require('path');
		    const MiniCSSExtractPlugin = require('mini-css-extract-plugin');
		    const HtmlWebpackPlugin = require('html-webpack-plugin');
		    
		    module.exports = {
		        entry: {
		            home: path.resolve(__dirname, 'src/js/index.js')
		        },
		        mode: 'development',
		        output: {
		            path: path.resolve(__dirname, 'dist'),
		            filename: 'js/[name].js'
		        },
		        module: {
		            rules: [
		                {
		                    test: /\.css$/,
		                    use: [
		                        {
		                            loader: MiniCSSExtractPlugin.loader
		                        },
		                        'css-loader'
		                    ]
		                }
		            ]
		        },
		        plugins: [
		            new HtmlWebpackPlugin({
		                title: 'Nuevo Titulo desde el Plugin',
		                minify: {
		                    collapseWhitespace: true
		                }
		            }),
		            new MiniCSSExtractPlugin({
		                filename: 'css/[name].css'
		            })
		        ],
		        devServer: {
		            host: '0.0.0.0', 
		            port: 8080, // Si deseas cambiar el puerto que tambien viene por default 8080
		        }
		    }
		    
		```

* **cristhianrs** (1)

	
	no me corre en localhost tuve que probar otras opciones y encontre una donde tendria que cambiar el host en el webpack.config.js para que levante en el navegador  
	pero actualmente nose porque no levanta en localhost
	``` 
	    devServer:{
	            host: "127.0.0.1"
	        }
	    
	```

* **idmevander** (1)

	
	donde le doy like???

* **Fabián andres Pedraza Borhorquez** (1)

	
	![cursoplatzi-webpack-servidor de desarrollo.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-servidor%20de%20desarrollo-75216ae1-b388-4b92-95c8-36c5691a712c.jpg) esto cada vez se pone mejor siguiendo los pasos me ha funcionado tal cual

* **carlos ruales** (1)

	
	¿Por qué en mi caso no me toma el index.html de la carpeta webpack-dev-server que se creó para esta clase y en vez de eso me toma el index.html que se creó desde la primera clase?
	
	Otro tema es que intente acceder por medio de la url: _**<http://localhost:8080/webpack-dev-server>**_
	
	pero lo unico que me lista son los archivos .js y .css

	* **Armando Duarte Quiñones** (2)

		
		Especificaste la ruta de la carpeta en el JSON?

	* **Andres Roberto Coello Goyes** (1)

		
		creo que tiene que ver con tu ruta en el json.

	* **Cristian Bravo** (1)

		
		el mismo problema, como lo solucionaste ?

	* **carlos ruales** (2)

		
		Gracias a todos pero ya lo pude resolver, fue un problema de rutas.

	* **dcastrocoder** (2)

		
		Para el que le no le “recargue”, lamentablemente no han mencionado el “error” y aquí lo doy a conocer.  
		Si se han realizado las cosas como en el video todo debe ir muy bien. Sin embargo, lo que puede suceder es que estamos modificando el archivo **css ** que no corresponde.  
		Se debe modificar el que se encuentra en la ruta:  
		src --> css --> index.css  
		![Screenshot_1.png](https://static.platzi.com/media/user_upload/Screenshot_1-5c867379-7b45-425e-b9ab-b4c546104f20.jpg)

* **onlinejaime** (1)

	
	Hola. He intentado dos veces que, al cambiar **“build:dev”: “webpack --config ./webpack-dev-server/webpack.config.js” ** por **“build:dev”: “webpack-dev-server --config ./webpack-dev-server/webpack.config.js”** me construya la carpeta ‘dist’ y no lo hace más que en virtual para lanzar el visionado de la web en el servidor 8081 (o el que sea).
	
	¿Es normal? ¿No debería salir la carpeta ‘dist’ en el árbol de archivos cuando lanzo el servidor? ¿Por qué no la crea? Repito, con el CLI de webpack sí funciona.

	* **Victor Escareno** (2)

		
		Hola, hasta donde entiendo esa es la idea, se crea un servidor virtual en memoria para que sea más rápido y fácil trabajar, en lugar de hacer un build y escribir los archivos en memoria cada vez que se hace algún cambio, webpack dev server lo carga en memoria. Esto se hace en modo de desarrollo. Se crean los archivos y la carpeta dist cuando ya no hay cambios y se “compila” el proyecto (modo de producción).

* **Victor Escareno** (1)

	
	Me surge la duda, para llevar un control de versiones (git), ¿Se recomienda hacer commit a todos archivos de la instalación o sólo a las carpetas del código?

	* **Diego Alexander Forero Higuera (Platzi)** (7)

		
		Es una buena practica excluir los directorios de node_modules y el dist ya que en desarrollo los archivos por lo general no están optimizados.

* **czabala847** (1)
No me queda claro que es un CLI?

	* **Juan David Castro (Platzi)** (1)

		
		> **Command-line interface** (CLI) o la interfaz de línea de comandos es un método que permite a los usuarios dar instrucciones a algún programa informático por medio de una línea de texto simple.  
		>  – [https://es.wikipedia.org/wiki/Interfaz_de_línea_de_comandos](https://es.wikipedia.org/wiki/Interfaz_de_l%C3%ADnea_de_comandos)
		
		Dicho de otra forma, es la forma en que podemos usar una aplicación, programa o herramienta usando comandos de la terminal. Por eso necesitamos el paquete **`webpack`** junto con **`webpack-cli`**. Porque con solo el primero no tenemos forma de ejecutar los comandos de webpack para que compile nuestros archivos.

* **edwintrumpet** (1)
Yo siempre que levanto un servidor en localhost puedo acceder desde otros dispositivos conectados a la red usando la ip 192.168.0.**. Per...

	* **Abner Paul Ccari Lindo** (2)

		
		Esa caracteristica la puedes configurar en tu webpack.config, para que pueda ser accesible desde otros devices.
		``` 
		    devServer: {
		        host: '0.0.0.0',
		        port: 8080,
		      }
		    
		    
		```
		
		Tambien lo puedes hacer por medio del webpack-cli agregando un flag de --host
		``` 
		    webpack-dev-server--host 0.0.0.0
		    
		```

## 0110. Hot Module Replacement

### Descripción:


### Links:

* [clase 11 - hot module replacement · LeonidasEsteban/webpack-4@66a8244 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/66a82441a67d35aa8468a0acd2d783f786d5c58b)

### Comentarios:

* **David Behar** (11)

	
	## Configuración del devServer en webpack.config
	
	Para configurar el `webpack-dev-server` puedes agregar un objeto llamado [devServer](https://webpack.js.org/configuration/dev-server/) dentro de tu webpack.
	``` 
	    module.exports = {
	      //...
	      devServer: {
	        // webpack-dev-server configuration
	      }
	    };
	    
	```
	
	En el devServer podemos configurar cosas como:
	
	  * `hot`: Activa el HotModuleReplacementPlugin que muestra los cambios sin actualizar la página
	  * `port`: Al crear un servidor de prueba con webpack-dev-server éste tomará por defecto el puerto 8080, acá podrás cambiar el puerto.
	  * `open`: Abrirá el navegador al iniciar el servidor
	  * `allowedHosts`: Dominios que permitirá el servidor utilizar
	  * [Etc…](https://webpack.js.org/configuration/dev-server/)
	
	
	
	Configuraciones del devServer
	
	## HotModuleReplacementPlugin
	
	Hot Module Replacement (HMR) es un plugin de Webpack que permite intercambiar, agregar o eliminar [módulos](https://webpack.js.org/concepts/modules/) en tiempo de ejecución, sin una recarga completa de la página.  
	.  
	Para activarlo lo tienes que importar desde webpack, agregarlo como plugin y en el devServer agregar la propiedad hot
	``` 
	    const webpack = require('webpack');
	    module.exports = {
	      //...
	      devServer: {
	        hot: true
	      }
	      plugins: [
	        new webpack.HotModuleReplacementPlugin()
	      ]
	    };
	    
	```
	
	HMR puede acelerar significativamente el desarrollo de las siguientes formas:
	
	  * Conservando el estado de la aplicación que se pierde durante una recarga.
	  * Ahorre un valioso tiempo de desarrollo actualizando solo lo que ha cambiado.
	  * Actualice al instante el navegador cuando se realicen modificaciones a CSS / JS en el código fuente, que es casi comparable a cambiar los estilos directamente en las herramientas de desarrollo del navegador.
	
	

* **Luis Arturo Lira Cerda** (8)

	
	No sé si se dieron cuenta algunos, pero si sólo usamos MiniCssExtractPlugin, simplemente va crear los archivos css en al carpeta dist/css pero no los minifica.  
	.  
	Para minificarlos hay que instalar dos dependencias más para desarrollo:
	``` 
	    npm i -D terser-webpack-plugin optimize-css-assets-webpack-plugin
	    
	```
	
	y configurar nuestro archivo de configuración de webpack para producción con lo siguiente:
	``` 
	    // Imports
	    const TerserJSPlugin = require('terser-webpack-plugin')
	    const OptimizeCSSAssetsPlugin = require('optimize-css-assets-webpack-plugin')
	    
	    // En module.exports agregamos esto a lo que ya tenemos
	    optimization: {
	        minimizer: [
	          new TerserJSPlugin({}), 
	          new OptimizeCSSAssetsPlugin({})
	        ],
	      },
	      module: {
	        rules: [
	          {
	            test: /\.css$/,
	            use: [
	              { loader: MiniCssExtractPlugin.loader },
	              'css-loader'
	            ]
	          }
	        ]
	      },
	      plugins: [
	        new HtmlWebpackPlugin(),
	        new MiniCssExtractPlugin({
	          filename: 'css/[name].css'
	        })
	      ]
	    
	```
	
	Con esto minificará los estilos CSS y en dado caso que también quieran minificar los archivos HTML, debemos agregar esto al HtmlWebpackPlugin.
	``` 
	    new HtmlWebpackPlugin({
	          minify: {
	            collapseWhitespace: true,
	            removeComments: true,
	            removeRedundantAttributes: true,
	            removeScriptTypeAttributes: true,
	            removeStyleLinkTypeAttributes: true,
	            useShortDoctype: true
	          }
	        })
	    
	```
	
	Espero les sirva 😃

	* **alexis** (3)

		
		No hace falta, cuando se hace el build a producción, automáticamente se minifica.

	* **Adrian Garcia Saaib** (1)

		
		a mi no me funciono el ejemplo, y lo puse exacto D: sabes si funciona con webpack-dev-server?

	* **Javier Sain Osorno Aguirre** (0)

		
		Que versiones se instalaron en terser-webpack-plugin y optimize-css-assets-webpack-plugin ??

	* **cesarcubillos** (1)

		
		Ah, con razón, muchas gracias Luis, pensé que era error mío jejeje.

* **Camilo Andrés Santana Lizcano** (7)

	
	Para los que usan react router, esto les permite navegar dentro de su SPA sin problemas
	``` 
	    devServer: {
	        historyApiFallback: true
	      }
	    
	```

	* **Georgie Duarte** (1)

		
		si sufri en su momento con eso en el cambio de vistas

* **onlinejaime** (5)

	
	Si añadimos esto:
	
	meta: {  
	viewport: ‘width=device-width, initial-scale=1’  
	// Will generate: <meta name=“viewport” content=“width=device-width, initial-scale=1, shrink-to-fit=no”>  
	},
	
	nos incluirá etiquetas <meta name> en el html resultante, en este caso ‘viewport’.

* **Iair Poloniecki** (4)

	
	De verdad que parece mágico Webpack, pero me hace ruido tener que hacer taaaaantas configuraciones solo para empezar un proyecto. No se puede acelerar el proceso???

	* **David Behar** (4)

		
		En React (seguro existirá un equivalente en Vue y Angular) puedes hacer un boilerplate listo para empezar desde la linea de comandos teniendo instalado node sólo con [create-react-app](https://reactjs.org/docs/create-a-new-react-app.html):
		``` 
		    npx create-react-app my-app <app-name>
		    
		```
		
		Lo puedes hacer de manera sencilla y normalmente no modificas mucho tu webpack, pero es muy importante entender cómo funciona para poder mejorar la experiencia cuando deseas hacer cosas más interesantes.

	* **David Behar** (1)

		
		En React (seguro existirá un equivalente en Vue y Angular) puedes hacer un boilerplate listo para empezar desde la linea de comandos teniendo instalado node sólo con create-react-app:
		``` 
		    npx create-react-app <app-name>
		    
		```
		
		Lo puedes hacer de manera sencilla y normalmente no modificas mucho tu webpack, pero es muy importante entender cómo funciona para poder mejorar la experiencia cuando deseas hacer cosas más interesantes.

	* **Aram Ceballos Gonzalez** (3)

		
		O tambien puedes descargar la extension “webpack” si usas vscode y te crea todo el archivo de configuracion de webpack automaticamente

	* **juand_silva** (1)

		
		O puedes utilizar **parcel** necesita **cero** configuración  
		<https://parceljs.org/>

* **Jorge Velasquez** (4)

	
	**Conceptos**  
	En su núcleo, webpack es un paquete de módulos estáticos para aplicaciones JavaScript modernas. Cuando el paquete web procesa su aplicación, genera internamente un gráfico de dependencia que mapea cada módulo que su proyecto necesita y genera uno o más paquetes .
	
	Obtenga más información sobre los módulos de JavaScript y los módulos de paquetes web aquí .
	
	Desde la versión 4.0.0, webpack no requiere un archivo de configuración para agrupar su proyecto. Sin embargo, es increíblemente configurable para adaptarse mejor a sus necesidades.
	
	Para empezar solo necesitas entender sus conceptos básicos :
	
	Entrada  
	Salida  
	Cargadoras  
	Complementos  
	Modo  
	Compatibilidad del navegador[]([url]  
	[https://webpack.js.org/concepts/](url)

	* **Pablitvs** (3)

		
		alto copy paste jajajaj

* **David Acevedo** (4)

	
	Resumen de clase:
	
	En esta clase se vio como hacer una escucha de cambios en los archivos sin que haga reload el navegador con el uso de **hot module replacement**
	
	webpack.config.js
	``` 
	    const path = require('path');
	    const MiniCssExtractPlugin = require('mini-css-extract-plugin');
	    const HtmlWepackPlugin = require('html-webpack-plugin');
	    const webpack = require('webpack');
	    module.exports = {
	      entry: path.resolve(__dirname, 'src/js/index.js'),
	      mode: 'development',
	      output: {
	        path: path.resolve(__dirname, 'dist'),
	        filename: 'js/index.js'
	      },
	      devServer:{
	        hot: true,
	        open:true,
	        port: 9090,
	      },
	      module: {
	        rules: [
	          {
	            test: /\.css$/,
	            use: [
	              'style-loader',
	              'css-loader'
	            ]
	          }
	        ]
	      },
	      plugins: [
	        new webpack.HotModuleReplacementPlugin(),
	        new HtmlWepackPlugin({
	          title : 'Hot Reload'
	        })
	      ]
	    }```
	    
	    notar que se saco el plugin  **MiniCssExtractPlugin**, ya que a la hora de trabajar en modo development es mucho mas rapido hacer una inyeccion directa de nuestro codigo css al navegador
	    
	    Tambien es necesario indicar en nuestros js que queremos que escuche para que solo haga el cambio en una funcion especifica, esto se hace con el codigo.
	    
	    
	    ```js
	    import'../css/styles.css'
	    import drawText from'./drawText';
	    
	    drawText()
	    
	    if(module.hot) {
	      module.hot.accept('./drawText', function(){
	        console.log('Haciendo el hot reload')
	        drawText()
	      })
	    }
	    
	```
	
	donde drawText es una funcion que retorna una tag “p” con el texto.
	
	ademas se vieron otras configuraciones para nuestro key devServer en el webpack.config.js.
	``` 
	    devServer:{
	        hot: true, // Recarga en caliente
	        open:true, // Abre una pestaña en el navegador
	        port: 9090, // cambia el puerto de desarrollo
	      },
	    
	```

* **Manuel Rivera** (3)

	
	Por que al ejecutar el comando del script ya no se esta creando la salida de los archivos, osea ya no se genera la carpeta dist con los archivos .js, .html y el .css lo quito Leonidas. pero los otros dos y la carpetas dist ?

	* **Ismael Teixeira** (6)

		
		Hola! Esta me ha parecido una buena pregunta. No estoy seguro pero creo que se debe a que estamos utilizando el plugin de webpack-dev-server. Como Leonidas dijo, en entornos de desarrollo es mas rapido tener los archivos inyectados al navegador desde JS que exportandolos y creando los archivos (como en el caso de MiniCSSExtractPlugin), por lo que creo que debido a esa razon no se crea la carpeta dist.
		
		Como te dije, esto no lo se a ciencia cierta pero si ya lograste saberlo dejalo aqui en la caja de comentarios!

	* **Ismael Teixeira** (4)

		
		Como decia en mi anterior comentario webpack-dev-server no crea los archivos build! Aqui la info: <https://github.com/webpack/webpack-dev-server/issues/24>

	* **javier-andres-bonilla-leiva** (3)

		
		hola
		
		ismael tiene razon
		
		para que los archivos cambien debes cambiar el comando webpack
		
		de
		``` 
		    "build:dev": "webpack-dev-server --config ./01-07-webpack-dev-server/webpack.config.js",
		       
		    a
		    
		    "build:dev": "webpack --config ./01-07-webpack-dev-server/webpack.config.js",
		    
		```
		
		de esta forma ya actualizará los archivos de salida

* **Marco Flores** (3)

	
	ENTORNO
	
	  * desarrollo => style-loader
	  * producción => MiniCSSExtractPlugin
	
	

	* **maria-del-carmen-rodriguez** (1)

		
		Proporciona la capacidad de ejecutar middleware personalizado después de todos los demás middleware internamente dentro del servidor.
		``` 
		    devServer: {
		        after: function(app, server, compiler) {
		          // do fancy stuff
		        }
		    
		```

* **dcastrocoder** (2)

	
	La “recarga en caliente” es sumamente importante pues evita recargar todos los componentes de la aplicación, sino que solamente recarga el que ha sido modificado.  
	Asumo que habrá alguna manera de hacerlo de forma más mecánica y sistemática, entendiendo que una aplicación puede tener muchos componentes.

* **danielfernando** (2)

	
	la documentacion de los plugins la encuentran en:  
	<https://webpack.js.org/plugins/>

* **Carlos Martinez** (2)

	
	para ver como sería adaptarle varios loaders a webpack.  
	<https://webpack.js.org/concepts/loaders/>
	
	Básicamente es dentro del array **rules** ir poniendo objetos con la propiedad **test** para identificar el tipo de archivo .css .hbs .ts ect, y **use** que son los loaders que se utilizaran con la extensión correspondiente identificada por **test**

* **Emiliano Durán** (2)

	
	Algo obvio pero no está mal resaltarlo: En la documentación del plugin aparece esta leyenda como advertencia.  
	**HMR should never be used in production.**

	* **heysoypaez** (1)

		
		gracias por recordar una obviedad que suele ser obviada Emiliano 😃

* **Fabián andres Pedraza Borhorquez** (1)

	
	super importante esta clase yaque nos evitamos estar recargando el navegador c ada vez que hagamos un ajuste

* **BRYAN ALEXANDER CONDOR DE LA CRUZ** (1)

	
	Código de propiedades de objeto de HotModuleReplacement, que permite indicar que parte recargar en caliente.

* **Johan Stivens Suarez Galindo** (1)

	
	No sabía que webpack también podía compilar las imágenes y cualquier otro archivo que haga parte de tu aplicación, por ejemplo, en este caso, con file-loader para las imágenes:
	``` 
	    {
	    	test: /.(jpg|png)$/,
	    		use: {
	    			loader: “file-loader”,
	    		options: {
	    			name: “./images/image.png”,
	    			},
	    },
	    },
	    
	    
	```

* **Juan David Marin** (1)

	
	Enseñas muchas cosas en una sola clase!  
	Gracias

* **Luis Gustavo Mejia** (1)

	
	DevTools failed to parse SourceMap: webpack:///node_modules/sockjs-client/dist/sockjs.js.map
	
	tengo el siguiente error en encuanto realizo lo de automatizar el refresco de la pagina no se si alguien pueda ayudarme

	* **Líncol Saenz** (1)

		
		Puedes poner todas líneas de error que te saltan, o esa es la única línea?

	* **Luis Gustavo Mejia** (1)

		
		esa es la única que sale

	* **Líncol Saenz** (1)

		
		Comprueba que tienes todos los módulos instalados correctamente. Si el problema persiste, prueba cambiando de navegador. (He leído sobre algunos problemas con chrome).  
		O elimina “node_modules” y reinstala todos los paquetes necesarios, de seguro le hiciste algún “npm audit”(fix) a alguno de los paquetes y se rompió.

* **Fadith Enrique Escorcia Mujica** (1)

	
	En caso de que mini-css-extract-plugin no funcione con HRM se puede forzar a que funcione con la siguiente configuración.
	``` 
	    module: {
	        rules: [
	          {
	            test: /\.(sa|sc|c)ss$/,
	            use: [
	              {
	                loader: MiniCssExtractPlugin.loader,
	                options: {
	                  hmr: process.env.NODE_ENV === 'development',
	                },
	              },
	              'css-loader',
	              'postcss-loader',
	              'sass-loader',
	            ],
	          },
	        ],
	      },
	    
	```

* **Marvin Rafael Ancheta Cuéllar** (1)

	
	Revisando la documentación, veo que también se puede agregar el compilador SASS  
	y se puede agregar al loader así:
	``` 
	     { loader: 'sass-loader' }
	    
	```
	
	que debe ir dentro de
	``` 
	    rulers: [  
	       {
	          use: [ 
	                  // aquí va el sass-loader
	           ]
	    }
	    
	```
	
	Pero si se va a usar primero hay que instalarlo así:
	``` 
	    npm install sass-loader node-sass webpack --save-dev
	    
	```

* **DavidArmandoVelazquez** (1)

	
	Si escribes el flag --open directamente en el comando tambien abre la ventana del navegador
	``` 
	    "webpack-dev-server --config ./webpack-dev-server/external.config.js --open"`
	    
	```

* **lenielluzardo** (1)

	
	Para configurar el server a los archivos ‘‘bundle’’ les dejo el [link](https://webpack.js.org/configuration/dev-server/)

* **Iair Poloniecki** (1)

	
	Me anduvo el hot reload sin ese if en el index

* **JarlLuis** (1)

	
	Webpack es genial

* **Cristian Bravo** (1)

	
	que flashero que es mientras te enseña te hace reir a las carcajadas !! groso

* **Jose Luis Colmenares** (1)

	
	Super chevere esta clase

* **Armando Duarte Quiñones** (1)

	
	una de las configuraciones que me pareció mas interesantes fue la de index, con ella indicamos cual es el documento indice
	``` 
	    index: 'index.html'
	    
	    
	```

* **Emiliano Durán** (1)

	
	Tengo una duda… no se si alguien tuvo el mismo problema… pero cuando hago cambios en la estructura index.html el Host Module no actualiza los cambios en el navegador y tampoco tengo mensajes de error por consola.  
	Agradecería saber si esto es un problema de configuración o simplemente es el correcto funcionamiento.  
	Saludos!!!

	* **Santiago Papa da Motta** (2)

		
		Estás abriendo con localhost:9000 o directamente el archivo index.html?

	* **Emiliano Durán** (1)

		
		Gracias Santiago por responder… lo abro con localhost:9000.

	* **danielfernando** (1)

		
		Debe haber un error en la configuración

	* **Angel Santillan Brambila** (1)

		
		Creo que eso se debe a la configuración de webpack pusimos que resolviera nuestros archivos desde el index.js y no desde nuestro index.html recuerda que webpack a traves de es index.js esta creando el archivo index.html pero en la carpeta dist y no esta tomando en cuenta para nada el index.html de la carpeta src  
		Saludos espero esto resuelva tu duda

* **heysoypaez** (1)

	
	esta fue la config con la que quede
	``` 
	    devServer: {
	    		hot: true,
	    		port: 9000,
	    		clientLogLevel: 'silent',
	    		lazy: false,
	    		https: true,
	    		
	    	},
	    
	```

	* **danielfernando** (1)

		
		¿Que hacen clientLogLevel y lazy?

* **Adrian Garcia Saaib** (1)

	
	Si deseas que se lean todos los archivos independientemente que tipo sean puedes cambiar esto
	``` 
	    // test: /\.css$/,
	    test: /\.(sa|sc|c)ss$/, //test all frameworks
	    
	```

* **capacita.ti** (1)

	
	Me acabo de dar cuenta que al modificar un component en React, me sale [HMR] Cannot apply update. Need to do a full reload! y se recarga toda la página.  
	Con css no se recarga todo. Es normal Leonidas?

	* **Raul Contreras** (4)

		
		Un requisito para que no se recargue completamente es que no estés aplicando ningún plugin de extracción de css

* **Manuel Rivera** (1)
Por que al ejecutar el comando del script ya no se esta creando la salida de los archivos, osea ya no se genera la carpeta dist con los a...

* **lenielluzardo** (1)
No me queda claro si los archivos que webpack-dev-server esta sirviendo son los bundles o los archivos fuentes?...

	* **Erik Ochoa (Platzi)** (2)

		
		Según tengo entendido **webpack-dev-server** crea un bundle en memoria, así que no hay forma de modificarlo directamente. La forma normal de trabajar es editar los archivos fuentes y que se vuelva a hacer el bundle automáticamente.

* **Pablitvs** (1)
no terminé de entender si es necesario configurar hot module replacement, si estamos usando react o vue. también leí en comentarios dicie...

	* **Juan David Castro (Platzi)** (1)

		
		> Hot Module Replacement (HMR) builds on top of the WDS. It enables an interface that makes it possible to swap modules live. For example, **style-loader can update your CSS without forcing a refresh**. **Implementing HMR for styles is ideal** because CSS is stateless by design.  
		>  – <https://survivejs.com/webpack/appendices/hmr/>
		
		👉 [Hot Module Replacement with Stylesheets | Webpack Docs](https://webpack.js.org/guides/hot-module-replacement/#hmr-with-stylesheets).

* **Fernando Alejandro Yerena Ramos** (1)
¿Por qué en este caso exportamos con la sintaxis ECS6? ¿Tiene que ver con que no es procesado por Node? ¿O es indistinto la forma en que ...

	* **Edward Steven Ramos Palacios** (2)

		
		Se usa la sintaxis ES6 para agregar soporte a ciertas caracteristicas de javascript que aun no son soportadas nativamente por los navegadores. Por ejemplo para usar los imports de los archivos de JS es necesario.

# Trabajando con loaders y plugins

## 0120. Soporte de Javascript moderno

### Descripción:


Javascript es un lenguaje moderno en evolución, siempre agregando nuevas funciones. El problema es que al ser interpretado en el navegador, no tenemos control sobre que versión de Javascript soportan y por lo tanto que funciones.

Para poder usar Javascript moderno y tener una buena **Developer Experience** sin afectar la **User Experience** , existe **Babel**. Babel transpila nuestro código moderno de Javascript a una una versión que todos los navegadores pueden entender.

### Links:

* [babel/packages/babel-core at master · babel/babel · GitHub](https://github.com/babel/babel/tree/master/packages/babel-core)

* [GitHub - babel/babel-loader: 📦 Babel loader for webpack](https://github.com/babel/babel-loader)

* [babel/packages/babel-preset-env at master · babel/babel · GitHub](https://github.com/babel/babel/tree/master/packages/babel-preset-env)

* [@babel/plugin-transform-runtime · Babel](https://babeljs.io/docs/en/babel-plugin-transform-runtime)

* [clase 12 - Soporte de javascript moderno · LeonidasEsteban/webpack-4@634ea39 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/634ea397b400e2d6c7a76b1d0cd604aff5042670)

### Comentarios:

* **David Behar** (13)

	
	## Soporte de Javascript moderno con babel
	
	Javascript es un lenguaje en constante evolución, cada año se encuentra agragando nuevas funcionalidades.  
	.  
	Una de las mayores ventajas y desventajas que tenemos es que javascript se corre en el navegador, lo que significa uso menor de recursos de parte de nuestros servidores, pero también que los navegadores se actualizan más lento que los nuevos releases de las versiones, además de que existen diferentes navegadores que soportan [diferentes funcionalidades](https://www.w3schools.com/js/js_versions.asp).  
	.  
	Para poder tener un mejor **developer experience** (que los desarrolladores programen más rápido) con las funcionalidades modernas de JavaScript es necesario utilizar un [transpilador de código](https://ingenieriadesoftware.es/diferencia-transpilacion-compilacion/), siendo el más popular [babel](https://github.com/babel/babel).  
	.  
	El papel de **babel** será el de **transpilar** (convertir y adaptar código) escrito en estándares modernos (normalmente superior a ecmaScript 2015) a estándares que [soporten la mayoría de los navegadores](https://www.w3schools.com/js/js_versions.asp), de esta manera el desarrollador se preocupa por porgramar de manera cómoda y webpack con babel lo convierten en lo que sea mejor para los navegadores.  
	.  
	Para hacer uso de **Babel** en webpack, como éste tiene un loader (babel-loader), tenemos que instalar `@babel/core` (que tiene la funcionalidad básica de babel) y `babel-loader` e instanciar el loader dentro de nuestras `rules` de la siguiente manera:
	``` 
	    module.exports = {
	    //
	      module: {
	        rules: [
	          {
	            test: /\.js$/,
	            use: 'babel-loader', // Intercepta los archivos de js y transpila en versiones más antiguas que entiendan la mayoría de los navegadores
	            exclude: /node_modules/,
	          },
	      },
	    };
	    
	    
	```
	
	Babel requerirá de configuración, ésta puede ser declarada dentro del webpack, pero se recomienda hacerlo dentro de un archivo llamado [.babelrc](https://babeljs.io/docs/en/config-files) que leerá babel a la hora de ser configurado por webpack.

* **Marlene Serrano García** (11)

	
	Me lanzaba el error :  
	Error: "Cannot find module ‘babel-preset-env’ from (ruta de mi proyecto)"  
	Por sí a alguien le causa el mismo conflicto, basta que en su .babelrc, sustituyan el valor de presets, algo así:
	``` 
	    {
	        "presets" : [
	            "@babel/preset-env"
	        ]
	    }```
	    
	```

	* **Northerchild** (1)

		
		Muchas gracias

	* **Nycgia** (1)

		
		Justo iba a comentar esto, gracias Marlene por el comentario.

	* **rubencolina** (1)

		
		justo venía a escribir esto

* **Manuel Rivera** (7)

	
	ojito ojito 😄

* **Adrian Garcia Saaib** (5)

	
	repaso de las dependencias de babel:  
	**babel-loader** va a entender todos los archivos .js y se los va a pasar a **babel/core** , que va a cambiar el formato de js moderno a js que yo le diga, y el js que queremos es la tercer dependencia  
	**babel/preset-env**

* **Iair Poloniecki** (4)

	```
	    npm i -D -E @babel/core@7.4.5 babel-loader@8.0.6 @babel/preset-env@7.4.5
	    
	```

* **José antonio Cañizales** (3)

	
	el --save-exact es para que no agregue el “^” en el package.json, quiere decir que usa la versión exacta del paquete que le indiques o la mas actual del momento, y es útil cuando se instala el proyecto en otro entorno de desarrollo, te da la seguridad de que cuando instales el proyecto, se instalara la version con la que desarrollaste originalmente.

* **dcastrocoder** (2)

	
	Soy de los que les gusta trabajar con las últimas versiones estables de las tecnologías de desarrollo.  
	Si instalas dichas versiones, en esta ocasión probablemente te salga este error:  
	![](![Screenshot_2.png](https://static.platzi.com/media/user_upload/Screenshot_2-b85d43fc-6718-4cb7-8439-6c5f0af4c7d1.jpg)  
	El error está en la manera como se llama a las configuraciones que se hacen en el **.babelrc**  
	La solución sería llamarla así:  
	![](![Screenshot_3.png](https://static.platzi.com/media/user_upload/Screenshot_3-87aff1da-767e-4635-9e07-be3d8d762d3d.jpg)

* **JarlLuis** (2)

	
	Nuevo modulo, nueva camisa jajaja semamoooo

* **Luis Rangel Castro** (2)

	```
	    npm install -D @babel/core babel-loader @babel/preset-env
	    
	```

	* **JarlLuis** (1)

		
		y el exaaaact viejooo?

	* **emanueljtc** (1)

		
		falto el -E para el --save-exact

* **Johan Manuel Perez Soto** (2)

	
	Cual finder we, yo uso windows :v

* **Wicho_Doble_Vi** (2)

	
	parcel o webpack?

* **Fabián andres Pedraza Borhorquez** (1)

	
	no me compilaba y le cambie el port:9000 a port:8080 y me funciono

* **beaps** (1)
Si estoy haciendo un proyecto sencillo con vanilla js pero quiero utilizar babel… ¿Podría utilizarlo sin webpack? y si es así, ¿cómo serí...

	* **beaps** (3)

		
		Seguí los pasos de este [enlace](https://babeljs.io/setup#installation) de la página de babel y me funciona.
		
		package.json
		``` 
		    {
		      "name": "tu proyecto",
		      "version": "1.0.0",
		      "description": "",
		      "main": "index.js",
		      "scripts": {
		        "build": "babel src -d lib"
		      },
		      "author": "",
		      "license": "ISC",
		      "devDependencies": {
		        "@babel/cli": "^7.6.4",
		        "@babel/core": "^7.6.4",
		        "@babel/preset-env": "^7.6.3"
		      }
		    }
		    
		```
		
		.babelrc
		``` 
		    {
		      "presets": [
		        "@babel/preset-env"
		      ],
		      "plugins": []
		    }
		    
		```
		
		En esta [página](https://babeljs.io/docs/en/plugins/) se encuentran los plugins… Alguno interesante que debería añadir?

## 0130. Trabajando con Javascript moderno

### Descripción:


### Links:

* [babel/packages/babel-core at master · babel/babel · GitHub](https://github.com/babel/babel/tree/master/packages/babel-core)

* [GitHub - babel/babel-loader: 📦 Babel loader for webpack](https://github.com/babel/babel-loader)

* [babel/packages/babel-preset-env at master · babel/babel · GitHub](https://github.com/babel/babel/tree/master/packages/babel-preset-env)

* [@babel/plugin-transform-runtime · Babel](https://babeljs.io/docs/en/babel-plugin-transform-runtime)

* [Fundamentos de JavaScript | Materiales](https://platzi.com/clases/fundamentos-javascript/)

* [clase 14 - Trabajando con javascript moderno · LeonidasEsteban/webpack-4@4bbd237 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/4bbd237069a0467bc5faa031cfe359b98f31dbd2)

### Comentarios:

* **Alan Santiago** (11)

	
	Leonidas hablando mientras programa es más rápido que los subastadores en EEUU 🤣😂  
	.  
	![subastador.jpg](https://static.platzi.com/media/user_upload/subastador-992106ba-4425-46cf-b3f8-faea67c68dcd.jpg)

* **Iair Poloniecki** (10)

	```
	    npm i -D -E @babel/plugin-transform-runtime@7.4.4
	    npm i -E @babel/runtime@7.4.5
	    
	```

* **Mariano Villarreal** (9)

	
	Buenas. No me funcionó la solucion para las funciones asincronas.  
	Encontré una que si.
	
	En mi .babelrc
	``` 
	    "plugins": [
	        // plugin for async functions
	        ["@babel/plugin-transform-runtime",
	          {
	            "regenerator": true
	          }
	        ]
	      ],
	    
	```
	
	En mi package.json
	``` 
	    "@babel/plugin-transform-runtime": "^7.5.0",
	        "@babel/runtime": "^7.5.4",
	    
	```
	
	Excelente curso. Saludos

	* **Jenny Katherine Aguilera Morales** (1)

		
		Muchas gracias por tu aporte tampoco me funcionaba 😃

	* **CodingLeonardo** (1)

		
		Muchas gracias por tu aporte 😆💚

	* **necrobahamut** (1)

		
		Esta raro que no te funcionara, porque la opción de “regenerator” es por defecto true: ![doc](https://imgur.com/a/4TXkKoY) o también lo puedes ver en la [documentacion oficial](https://babeljs.io/docs/en/babel-plugin-transform-runtime)

* **Luis Arturo Lira Cerda** (7)

	
	El archivo js de producción sin el plugin que ejecuta las llamadas asíncronas:  
	![SinRuntime.png](https://static.platzi.com/media/user_upload/SinRuntime-f906935c-8ff8-440a-b4ce-3f5d47c0a73d.jpg)
	
	El archivo de js con el plugin que lo hace:  
	![ConRuntime.png](https://static.platzi.com/media/user_upload/ConRuntime-a976085e-9c69-48cb-a14c-af1344b17f6c.jpg)

* **skorpion** (5)

	
	Lo mejor fue conocer la api de pokemon ajajja

* **Yank Carlos Reyes Espinal** (4)

	
	“No funcionó esta habilidad” - Leonidas (300 - 400 A.C)

* **Facundo Nicolás García Martoni (Platzi)** (4)

	
	En mi caso no fue necesario instalar el plugin de Babel para que soporte funciones asíncronas, a ustedes les pasó?

	* **Emiliano Durán** (1)

		
		Me dio el mismo error… tiene sentido la clase

	* **SOFTDYNAMIC** (1)

		
		Bueno yo lo instalé antes de ejecutarlo

	* **Iair Poloniecki** (2)

		
		Para ver la diferencia habría que usar un navegador que no soporte ECMAScript 6

	* **Gerardo Nava Pereda** (2)

		
		En tu ambiente de producción muchos de tus usuarios van a tener navegadores viejos y tu App no va a servir del todo … es por ello que tienes que compilar con babel a ES5 o usar pollyfills 😉

	* **necrobahamut** (3)

		
		No es necesario, si revisan la carpeta de ./node_modules/@babel verán varios plugins-transform muy específicos cada uno, no se si se deba que nuestras instalaciones ya tienen por defecto esos plugins, de hecho lo que Leonidas menciona en esta clase es un poco erróneo, porque las 2 cosas que menciona en esta clase se usan para evitar código repetido en nuestro bundle final, pueden verlo desde la [documentación oficial](https://babeljs.io/docs/en/babel-runtime) de babel.

* **Luis Miguel Rodriguez** (4)

	
	Facilmente este puede ser un curso de wepack + babel (mini)

* **Camilo Andrés Santana Lizcano** (3)

	
	Me he divertido mucho hasta ahora aprendiendo webpack con Leonidas 😄

	* **Iván Darío Sánchez Jiménez** (4)

		
		Deberiamos haber visto este curso antes de entrar a la escuela de JavaScript. Cierto Andres? yo también ando entendiendo varias de las configuraciones que hicimos.

	* **Camilo Andrés Santana Lizcano** (2)

		
		Sí claro, nada como unas buenas bases

* **David Behar** (3)

	
	Si queremos que nos vuelva a preguntar hasta que pongamos un pokemont válido, podríamos poner el siguiente código que nos validaráque esté en los primeros 151 pokemons, que seamos reales, son los únicos que existen, jijiji
	``` 
	    let characterId = Number(prompt('¿Qué personaje deseas?'));
	    while (characterId === 0 || characterId >= 151) {
	      characterId = Number(prompt('El personaje deberá ser un número menor a 151')) ;
	    }
	    
	```

	* **Juan José Vega Quintero** (2)

		
		Jajajaja  
		Más de 151 fake

	* **David Behar** (1)

		
		😅

* **Hernan Maza** (2)

	
	Se puede aplicar source mapping para analizar el codigo fuente original?

* **Manuel Rivera** (2)

	
	la proxima clase es sobre el azucar sintético (jsx) según el profesor Richard del curso de react jajaja

	* **Alejandro Jimenez** (1)

		
		Es azúcar sintáctico

* **Juan Carlos Pinzón** (2)

	
	Entonces ese @babel/runtime como se instaló como dependencia core, va a estar presente en el bundle

* **Fabián andres Pedraza Borhorquez** (1)

	
	![cursoplatzi-webpack-javascript-moderno.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-javascript-moderno-4014be06-fc4c-4ab5-af78-1bbf51adab1c.jpg) esto esta muyy chevere pero tengo un problema y esque no me compila cuando lo mando con el port:9000 pero si lo dejo en el port:8080 si funciona bien alguine sabe porque pasa esto ? este es el error que me genera![cursoplatzi-webpack-error-port9000.jpg](https://static.platzi.com/media/user_upload/cursoplatzi-webpack-error-port9000-7f348164-b664-41b0-b59a-dba4699712cf.jpg)

* **HumbertoMLL** (1)

	
	Las versiones que instala son:  
	"@babel/plugin-transform-runtime": “7.4.4”
	
	“@babel/runtime”: “7.4.5”

* **Yaisel Hurtado González** (1)

	
	Upss tuve problemas con el CORS …  
	![](https://www.dropbox.com/s/l3tzqp9vqwq0h7y/Screenshot_20200201_211551.png?dl=0)

	* **Leonardo Casallas Beltran** (1)

		
		Para esto puedes instalar una extension de google chrome como:
		
		  * [Moesif Orign & CORS Changer](https://chrome.google.com/webstore/detail/moesif-orign-cors-changer/digfbfaphojjndkpccljibejjbppifbc)
		
		  * [CORS Unblock](https://chrome.google.com/webstore/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino)
		
		
		

* **Yank Carlos Reyes Espinal** (1)

	
	Pero al menos toma un suspiro al dar la clase. 😅

* **maria-del-carmen-rodriguez** (1)

	
	Esta es la documentación oficial del plugin  
	<https://babeljs.io/docs/en/babel-plugin-transform-runtime>

* **Juan Carlos Pinzón** (1)

	
	Excelente Clase

* **Clonathan** (1)

	
	This is fun!

* **Luis Rangel Castro** (1)

	```
	    npm install --save @babel/runtime
	    
	```

* **Luis Rangel Castro** (1)

	```
	    npm install -D @babel/plugin-transform-runtime
	    
	```

* **Miguel Angel Martelo Quiroz** (1)

	
	Excelente clase!!!

* **Byron Vargas** (1)
tengo este error en la consola del html final async function search(id){ const response = await fetch("https://pokeapi.co/api/v...

	* **Byron Vargas** (2)

		
		ya encontré el problema, es el url con comillas dobles, las puse comillas simples y funciono todo correctamente

* **sergi.g.gonzalez.7** (1)
en modo desarrollo me sigue minificando el código 😦 con el babel, que config afecta a esto?

	* **Juan David Castro (Platzi)** (1)

		
		👋 ¡Hola!
		
		Lo estudiamos en estas dos clases:
		
		👉 <https://platzi.com/clases/1620-webpack/21154-configuracion-de-desarrollo-para-platzi-badges-r-8/>  
		👉 <https://platzi.com/clases/1620-webpack/21155-configuracion-basica-de-produccion-para-platzi-b-4/>
		
		También te puede interesar:
		
		👉 <https://stackoverflow.com/questions/46524999/how-do-i-disable-babel-minification-when-not-in-production>

* **eduardoluisgr** (1)
¿cual es la diferencia entre instalar un module como dependencia de desarrollo, o como dependencia del proyecto?, ¿cambia algo al momento...

	* **Steven Anaya** (3)

		
		Efectivamente, las dependencias de desarrollo no se instalan cuando la variable de entorno de NODE_ENV esta en production.

## 0140. Soporte de JSX (React)

### Descripción:


 **JSX** es un lenguaje de templates para React que permite definir componentes con un código muy similar al HTML.

No existe navegador que entienda JSX porque no es un estándar, es algo especifico de React. Afortunadamente Babel puede transpilar el código JSX de nuestros archivos JS a código que el navegador.

### Links:

* [@babel/preset-react · Babel](https://babeljs.io/docs/en/babel-preset-react)

* [Curso de React.js | Materiales](https://platzi.com/clases/react/)

* [clase 15 - Soporte de JSX (React) · LeonidasEsteban/webpack-4@18861c7 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/18861c7335be8f890c8cc56773a32f67e225038d)

### Comentarios:

* **Miguel Angel Martelo Quiroz** (6)

	
	Uuuffff, super, nunca había entendido tan bien como trabajar con React sin create-react-app GENIAL!!!

	* **Juan José Vega Quintero** (2)

		
		Esta clase explota la cabeza de cualquiera

* **alexjcm** (6)

	
	Si van a utilizar archivos **.js** y **.jsx** deberán configurar el archivo _webpack.config.js_ de la siguiente manera:
	``` 
	    //
	     module: {
	        rules: [
	          {
	            test: /\.(js|jsx)$/,
	            use:"babel-loader",
	            exclude: /node_modules/
	          }   
	        ]
	      },
	      resolve: {
	        extensions: [".js", ".jsx"]
	      },
	      //
	    
	```

* **heysoypaez** (4)

	
	**¿Cómo instalar React.js con Webpack**
	
	Genial, tu y yo ya tenemos la base de Webpack y ahora instalaremos React, esto es lo que haremos
	
	  1. Instalar las siguientes dependencias:
	
	
	``` 
	    npm install --save-dev --save-exact @babel/preset-react
	    
	    npm install --save --save-exact react
	    
	    npm install react-dom --save --save-exact 
	    
	    //Nota: El orden de los flags no importa
	    
	    
	```
	
	  1. Actualizar el archivo de .babelrc (el archivo que tiene tu configuración de babel):
	
	
	``` 
	    "presets": [
	    		"@babel/preset-env",
	    		"@babel/preset-react"
	    	]
	    
	    
	    
	```
	
	React necesita un elemento container en el HTML, para ello modificaremos nuestro HTML hecho automaticamente con webpack
	
	  1. Actualizar en webpack.config.js el plugin de HTML
	
	
	``` 
	    plugins: [
	    
	    		new webpack.HotModuleReplacementPlugin(),
	    
	    		new HtmlWebpackPlugin({
	    			title: "plugins",
	    			minify: {
	    				collapseWhitespace: true
	    			},
	    			template:  path.resolve( __dirname, "index.html" )	
	    		})
	    	]
	    
	```
	
	  1. Y añadiremos el elemento container que llamaremos en el index.js de React.
	
	
	``` 
	    <!DOCTYPE html>
	    <html>
	    <head>
	    	<title></title>
	    	<metacharset="utf-8">
	    </head>
	    <body>
	    	<divid="root"></div>
	    </body>
	    </html>
	    
	    
	```
	
	  1. ¡Y voilá! _Haz que algo que marque la diferencia suceda con tu App en React.js_
	
	
	
	Index.js
	``` 
	    //Gracias a Webpack es que es posible hacer esto
	    import React from "react";
	    import {render} from "react-dom";
	    import App from "./components/App.js";
	    import"../css/index.css";
	    
	    render(<App />, document.getElementById("root"))
	    
	    
	```
	
	App.js
	``` 
	    import React from"react";
	    
	    functionApp(props) {
	    	
	    	return(
	    		<sectionclassName="App">
	    			<h1>App Testing</h1>
	    		</section>
	    	)
	    }
	    
	    exportdefault App;
	    
	    
	```

	* **Luis Rangel Castro** (2)

		```
		    npm install -D @babel/preset-react
		    
		    npm install --save react react-dom
		    
		```

* **heysoypaez** (4)

	
	Me parece mágico haber llegado a construir desde cero con Webpack la magia detrás de React (no tan desde cero pero mucha más cerca)
	
	Genial!!!

	* **Luis Jeanpier Monserrate** (1)

		
		concuerdo contigo, ahora entiendo la funcion que cumplia babel en el proyecto del curso de react

* **maria-del-carmen-rodriguez** (3)

	
	— npm install --save-dev --save-exact webpack webpack-cli webpack-dev-server css-loader style-loader html-webpack-plugin babel-loader @babel/core @babel/preset-env @babel/preset-react @babel/plugin-transform-runtime
	
	— npm install --save --save-exact react react-dom @babel/runtime  
	instalaciones necesarias para la configuración de un proyecto de react

* **Hector Cardona** (3)

	
	Una pregunta, cuando utilizo los options del loader de babel-loader desde .babelrc, no me funciona el codigo, pero si los pongo directo en el webpack.config funciona correctamente, que debo hacer?
	
	Asi tengo que hacerlo para que funcione
	``` 
	    {
	            test: /\.js$/, //En este cato interpretara los tipo .js
	            exclude: /node_modules/,
	            use: {
	              loader:"babel-loader",
	              options: {
	                presets: ["@babel/preset-env", "@babel/preset-react"]
	              }
	            } //transpilara nuestro codigo al ultimo ecmascript soportado por los navegadores
	          }
	    
	```

	* **Marvin Rafael Ancheta Cuéllar** (1)

		
		A mi me pasa exactamente lo mismo.  
		Ya me diste una idea.  
		Voy a revisar a ver si me lee el archivo babel.babelrc

* **Ivan Joseph** (2)

	
	Una buena alternativa a Babel para JSX es usar sucrase, disponible aquí:  
	<https://sucrase.io/>  
	y en NPM <https://www.npmjs.com/package/sucrase>  
	Sucrase es más rápido y no necesita plugins  
	sin embargo, no transpila el código a versions anteriores, es decir, no se asegura que el código sea compatible en todos lo navegadores. Los creadores de sucrase recomienda sucrase en desarrollo (porque es más rápido) y babel en producción.

* **Carlos Martinez** (2)

	
	si le ponen .jsx a sus extensiones de javascript recuerden que deben modificar la expresion regular en el loader así `test: /\.jsx?$/` para que encuentre tanto archivos js como jsx
	
	si no lo hacen webpack no reconocerá sus .jsx y dirá que hace falta un loader, cuando en realidad no es asi.
	``` 
	    {
	                    test: /\.jsx?$/,
	                    use:'babel-loader',
	                    exclude: /node_modules/
	                } ```
	    
	```

* **Adrian Garcia Saaib** (2)

	
	no me recarga el componente y me sale esto  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-b55fb679-f419-4193-bf70-ffb632f03b4b.jpg)

	* **Adrian Garcia Saaib** (1)

		
		recordar que la etiqueta con el id=“container” no debe ser una etiqueta script

* **Marvin Rafael Ancheta Cuéllar** (1)

	
	He seguido los pasos del video pero no entiendo porqué me da el siguiente error:
	``` 
	    SyntaxError: C:\Users\marvin.ancheta\Documents\PRUEBAS\WEBPACK\webpack-4\react\src\js\index.js: Unexpected token (7:7)
	    
	      5 | import App from './components/app'
	      6 |
	    > 7 | render(<App />,document.getElementById('container'))
	        |        ^
	    
	```
	
	Com que si no reconociera el código de React.  
	Pero ya instalé todo lo necesario y mi package.json y webpack.config.js está tal y como dijo el profesor  
	Alguien que me pueda ayudar

	* **Gabriel De Andrade (Platzi)** (1)

		
		Puedes mostrar tu archivo index.js? 😄

	* **santiagobarrios** (1)

		
		tengo el mismo error, lo pudiste solucionar ?

	* **Fabián andres Pedraza Borhorquez** (1)

		
		yo igual como puedo solucionarlo

* **Julian Labrador** (1)

	
	alguien me podria explicar… entonces create-react-app de fondo tine todo esto de babel preconfigurado???

	* **Gabriel De Andrade (Platzi)** (3)

		
		Sip, `create-react-app` hace todo este proceso de fondo 😄

* **Manuel Rivera** (1)

	
	Super! Conociendo el poder de webpack y mirando cada vez mas lo que esta detrás de create-react-app, genial !!

* **Deyvi Edwin Jara García** (1)

	
	Estimados que plugin se podría usar para minificar el código de css, o ese se minificaria con el plugin: MiniCSSExtractPlugin al correr webpack en modo produccion.

	* **Daniel Esteves** (2)

		
		El código se minifica automáticamente gracias a ese plugin de CSS 💪

* **Adrian Garcia Saaib** (1)

	
	Como esta eso que solo utilizar funciones y hooks?

	* **Facundo Nicolás García Martoni (Platzi)** (2)

		
		En las últimas versiones de React se están dejando de lado las clásicas **clases** , que permitían poner estado, personalizar el ciclo de vida del componente y otras características que los componentes funcionales no tenían. Con la llegada de los **Hooks** se pueden editar estos aspectos de una manera más sencilla ahora en los componentes que usan funciones en lugar de clases, por lo que el desarrollo se vuelve más eficiente 😉

	* **Carlos Martinez** (2)

		
		puedes usar tanto hooks como componentes con clases, la verdad es que ambos son buenos dependiendo de lo que necesites
		
		por ahora no es que hooks vaya a reemplazar a las clases , pero quien sabe, tal vez dentro de 3 años si.

	* **danielfernando** (1)

		
		Si tienes una class que solo tiene codigo en return (),
		``` 
		    classejemploextendsReact.Component{
		      render() {
		        return (
		          <div>
		    				todo el codigo
		    			</div>
		        );
		      }
		    }
		    
		```
		
		es mejor que crees una function como en la clase

* **lenielluzardo** (1)
Hola yo estoy teniendo el siguiente error ERROR in ./src/js/index.js 8:7 Module parse failed: Unexpected token (8:7) You may need a...

	* **Manuel Ojeda** (2)

		
		Es posible que te esté haciendo falta:  
		<https://babeljs.io/docs/en/babel-preset-react>

## 0150. Trabajando con React

### Descripción:


### Links:

* [clase 15 - trabajando con react.js · LeonidasEsteban/webpack-4@a5d3e1c · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/a5d3e1cbbf5d28ac8b90004ed70a9c05c3593457)

### Comentarios:

* **Facundo Nicolás García Martoni (Platzi)** (16)

	
	De nada 😃
	``` 
	    {
	      "loaders": [
	        {
	          "name": "css-loader",
	          "id": "1"
	        },
	        {
	          "name": "style-loader",
	          "id": "2"
	        },
	        {
	          "name": "babel-loader",
	          "id": "3"
	        }
	      ]
	    }
	    
	```

	* **Ernesto Vizcaíno Alvarado** (1)

		
		Genial, gracias

	* **CodingLeonardo** (1)

		
		Gracias 😆💚

	* **Thony07** (2)

		
		A realizar la copiación y pegación 😄 jjj

* **Marvin Rafael Ancheta Cuéllar** (4)

	
	Excelente clase!!!  
	Recomiendo para practicar usar el contenido de esta API para darle más actualidad a esta clase.
	``` 
	    https://thevirustracker.com/free-api?countryTimeline=ES
	    
	```
	
	Es la API de los datos del Coronavirus el parámetro es el código alfanumérico del país, como por ejemplo: SV, US, ES, CO, etc.

* **emanueljtc** (4)

	
	La cara de alegria de Leonidas cuando va a enseñar algo en React no tiene precio jajaja

* **Luis Rangel Castro** (3)

	
	Destructuring
	``` 
	    functionLoader(props) {
	        return (<li>{props.data.name}</li>);
	    }
	    
	    functionLoader({data}) {
	        return (<li>{data.name}</li>);
	    }
	    
	    functionLoader({data:{name}}) {
	        return (<li>{name}</li>);
	    }
	    
	```

* **Camilo Andrés Santana Lizcano** (2)

	
	Wow!  
	Esa no me la sabia
	
	Mapeamos nuestros datos
	``` 
	    state.map((item)=>{
	    	<User {...item} />
	    })
	    
	```
	
	Recuperamos los props, desde el componente listado
	``` 
	    const User = ({name}) => {
	      return (
	        <li>{name}</li>
	      )
	    }
	    
	```

* **Mariana Valencia** (2)

	
	In love with this class.

* **Northerchild** (2)

	
	Los Hooks son la LEYYYYYY!!!

* **edg_colon** (2)

	
	Genial hooks!  
	useState, useEffect, useContext, useReducer son lo máximo, no hay necesidad de usar Redux.

	* **Cristian Florez** (1)

		
		He tenido problemas usando Redux. Que me recomiendas, lo dejo de lado y estudio use Context y useReducer ??

	* **edg_colon** (1)

		
		¿Que probelmas tuviste?
		
		A mi punto de vista se me hace mas facil y se ve mas limpio en codigo manejar customHooks, y para compartir el estado de manera global utilizo el hook useContext.
		
		busca sobre : react hooks flux pattern
		
		Este video en su momento me sirvió de mucho:
		
		<https://www.youtube.com/watch?v=corZt4Sb-fQ>
		
		Si tienes alguna duda la podemos resolver ya en código.

* **Edgar de Jesus Mendoza Ortegon** (2)

	
	Excelennttee!!!

* **Daniel Lopez** (1)

	
	pasa algo si no se le asigna un key al componente?

	* **Julio Cesar Jaramillo Palacios** (2)

		
		No pasa nada en este momento pero si en un futuro quieres obtener un elemento de la lista de componentes y cambiar por ejemplo su valor tendrás que poner la key para poder indicarle a tu función a cual elemento va a ser afectado.

	* **Daniel Lopez** (1)

		
		ok muchas gracias por tu explicacion.

* **Juan David Marin** (1)

	
	Wow! me explicaste tres temas que estoy aprendiendo y me cuesta de una manera clara y concisa.
	
	ME AYUDASTE EN EL TRABAJO GRACIAS !

* **Manuel Rivera** (1)

	
	Gracias por el truquito del spread operator 😄

* **ingsis_john** (1)

	
	Una forma que no conocia para pasar las propiedades de react usando el operador spread <Component {…elemento} />

* **heysoypaez** (1)

	
	Gracias como siempre por compartir ese valor práctico mezclado de tu entusiasmo Leonidas, eres grande mister!

## 0160. Soporte imágenes, fuentes y videos

### Descripción:


Para soportar la importación de archivos binarios en nuestro código Javascript cómo lo son: fuentes, imágenes y videos, podemos usar **url-loader**.

`url-loader` transforma archivos a un cadena de texto base64 para que carguen dentro de nuestros archivos Javascript y así ahorrarnos un request al servidor por cada archivo transformado.

Debemos tomar en cuenta que sólo nos conviene convertir archivos pequeños, ya que archivos muy grandes podrían hacer nuestro archivo bundle muy pesado. Es por esto que la opción **limit** del `url-loader` sirve para asignar el peso máximo que un archivo puede tener para ser transformado en base64.

No olvides instalar **file-loader** junto con **url-loader** ya que cuando se sobrepasa el limite establecido en la opción `limit` y el archivo no pueda ser transformado a base64, **url-loader** hará uso del **file-loader** para insertar un nombre y ruta de archivo en el lugar correspondiente.

### Links:

* [GitHub - webpack-contrib/url-loader: A loader for webpack which transforms files into base64 URIs](https://github.com/webpack-contrib/url-loader)

* [clase 16 - Soporte images, fuentes y videos · LeonidasEsteban/webpack-4@8b9e89f · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/8b9e89f6ed2937b84cf6826f96126d32f5d8fec8)

### Comentarios:

* **Facundo Nicolás García Martoni (Platzi)** (29)

	
	Les dejo un link con las fuentes, imágenes y videos 😉 <https://www.mediafire.com/file/xmwem40q5qc0igr/src.zip/file>

	* **Luis Jeanpier Monserrate** (2)

		
		con cuidado es un heroe xd.svg

	* **CodingLeonardo** (1)

		
		Gracias por tu aporte 💚😆.

	* **PabloMM** (1)

		
		Gracias por tu aporte buen hombre! 👌🐱‍🚀

	* **joselockerzt** (1)

		
		Muchas gracias me has ahorrado bajar uno por uno.

	* **jhon manuel angulo moncada** (1)

		
		gracias.

	* **emanueljtc** (1)

		
		gracias buen hombre

	* **Kevin Humberto León Santamaria** (1)

		
		Gracias compañero…

	* **RafaelEchart** (1)

		
		crack!

* **Favio Sauto** (22)

	
	Les dejo el código del font-face
	``` 
	    @font-face {
	      font-family: "open_sansregular";
	      src: url("../fonts/OpenSans-Regular-webfont.eot");
	      src: url("../fonts/OpenSans-Regular-webfont.eot?#iefix") format("embedded"),
	        url("../fonts/OpenSans-Regular-webfont.woff") format("woff"),
	        url("../fonts/OpenSans-Regular-webfont.ttf") format("truetype"),
	        url("../fonts/OpenSans-Regular-webfont.svg#open_sansregular") format("svg");
	      font-weight: normal;
	      font-style: normal;
	    }
	    
	```

	* **heysoypaez** (2)

		
		siempre hay un buen hombre que da apoyo moral

* **Luis Rangel Castro** (9)

	```
	    @font-face {
	      font-family: 'open_sansregular';
	      src: url('../fonts/OpenSans-Regular-webfont.eot');
	      src: url('../fonts/OpenSans-Regular-webfont.eot?#iefix') format('embedded-opentype'),
	          url('../fonts/OpenSans-Regular-webfont.woff') format('woff'),
	          url('../fonts/OpenSans-Regular-webfont.ttf') format('truetype'),
	          url('../fonts/OpenSans-Regular-webfont.svg#open_sansregular') format('svg');
	      font-weight: normal;
	      font-style: normal;
	    }
	    
	```

* **Manuel Rivera** (6)

	
	Link de los archivos en repo <https://github.com/LeonidasEsteban/webpack-4/tree/master/url-loader/src>

* **cesarcubillos** (2)
Mis preguntas son: ¿Hasta qué tamaño es recomendable pasar a base64 las imágenes? ¿Los videos también pueden quedar en ...

	* **Erik Ochoa (Platzi)** (3)

		
		Hola, 👋 mira:
		
		  1. Se recomiendan usar base64 solo para imágenes muy pequeñas como iconos y logos. en mi opinión personal un rango **entre 8 y 15 KiloBytes** sería el adecuado. Los navegadores han avanzado mucho y pueden manejar mejor las peticiones, también recuerda que los archivos de imagen son “cacheados” en el navegador y no se tiene que hacer la petición HTTP todo el tiempo.
		
		  2. No te recomiendo que lo uses para vídeo, **estarías aumentando muchísimo el consumo de ancho** de banda en cada petición. Toma en cuenta que al convertir cualquier archivo en base64 aumenta su tamaño de un 20% a 37%.
		
		
		
		
		Espero esto te sirva. 🙂

* **Luis Gustavo Mejia** (1)

	
	Buenas noches aun no me queda muy claro que pasa si el archivo sobre pasa el limit-url no si alguien pueda ayudarme

	* **Gabriel De Andrade (Platzi)** (1)

		
		Cuando un archivo sobrepasa el limit-url en vez de ser transformado a base64 se coloca la imagen en una carpeta a parte para ser consumida 😛

* **Jaime David Burbano Montoya** (1)

	
	Hola, alguien podría explicarme con un poco mas de detalle lo de imagenes base 64, y como saber cuanto ponerle de limit al url loader?

	* **juand_silva** (5)

		
		Hola, base64 es sistema que codifica archivos utilizando la mayor potencia de los bits (2) que es 64, se usa en imagenes pequeñas de 100kb aprox. Con esto ayudamos al performance de un aplicación; ya que, no vamos a hacer peticiones adicionales al servirdor. Más claramente, esta imagen esta encodeada en el bundle de la App y con esto evitamos hacer peticiones HTTPRequest al server.
		
		El limit es para que los archivos no excedan el limite de su peso en bytes para transformalos en Base64.
		
		Aquí hay un link para convertir imagenes en Base64 y deseas utilizar imagenes más grandes los mejor es utilizar la imagen normalmente.  
		<https://www.base64-image.de/>

* **David Behar** (1)

	
	Les recuerdo que, como el archivo index.css está importado desde javascript, al fallar la importación de las fuentes fallará, de hecho no encontrará las fuentes si no tenemos el loader, ésto porque nuestra aplicación se compilará en la carpeta de build, por lo tanto las rutas relativas a index.css son sobre build y necesitamos de webpack para que nos pase los archivos a la carpeta correspondiente.

* **JUAN SILVA** (1)

	```
	    npm install --save-dev --save-exact url-loader@1.1.2
	    
	```

* **JUAN SILVA** (1)

	```
	    npm install --save-dev --save-exact file-loader@3.0.1
	    
	```

* **Luis Rangel Castro** (1)

	
	[repo](https://github.com/LeonidasEsteban/webpack-4/tree/master/url-loader/src)

* **Luis Rangel Castro** (1)

	```
	    npm install -D url-loader
	    
	```

* **jose ortiz** (1)

	
	cual seria el limite adecuado para los archivos base 64?

	* **Marco Antonio Macedo Preciado** (1)

		
		9kb suena bien.

* **Julio Alejandro Villanueva Flores** (1)

	
	Hola! Qué configuración tienes en VS Code para trabajar con React?

	* **Chuy_17** (1)

		
		Aquí hay una pequeña explicación, creo que a eso te refieres  
		[VScode Extensions](https://medium.com/@eshwaren/enable-emmet-support-for-jsx-in-visual-studio-code-react-f1f5dfe8809c), saludos.

* **fnevarez00** (1)

	
	gracias Favio!

* **MoisesGuevara** (1)
¿Como podria tener acceso a la imagen en el css, o si lo hago con Vanilla Javascript?

	* **Juan David Castro (Platzi)** (1)

		
		👋 ¡Hola!
		
		Te recomiendo darle una leída a esta sección de la documentación de Webpack:
		
		👉 <https://webpack.js.org/guides/asset-management/#loading-images>
		
		😉👌

* **gosunkugi** (1)
Gente ~ dos preguntas: Si mal no entendí, ¿lo que hace esto es pasar recursos vinculados a la carpeta de producción? Y, ¿por qué puso el ...

	* **Manuel Ojeda** (1)

		
		Webpack te da el resultado de los tamaños de los archivos tras ejecutar la compilación, esto es para tener una idea del resultado y considerar optimizar.
		
		En este caso es meramente demostrativo y conocer el tamaño de los recursos (imágenes).

## 0170. Estilos con preprocesadores

### Descripción:


Es una práctica común usar preprocesadores de CSS como: Sass, Less, Stylus y hasta PostCSS. Webpack permite integrar estos preprocesadores en su configuración a través de loaders, sólo ten cuidado con las **peerDependencies** que son dependencias que el loader espera estén instaladas previamente, como el caso de **stylus** para **stylus-loader**.

### Links:

* [GitHub - webpack-contrib/sass-loader: Compiles Sass to CSS](https://github.com/webpack-contrib/sass-loader)

* [GitHub - webpack-contrib/less-loader: Compiles Less to CSS](https://github.com/webpack-contrib/less-loader)

* [GitHub - shama/stylus-loader: A stylus loader for webpack.](https://github.com/shama/stylus-loader)

* [GitHub - postcss/postcss-loader: PostCSS loader for webpack](https://github.com/postcss/postcss-loader)

* [Curso de PostCSS | Materiales](https://platzi.com/clases/postcss/)

* [Curso de Sass | Materiales](https://platzi.com/clases/sass/)

* [Curso de Less | Materiales](https://platzi.com/clases/less/)

* [Curso de Stylus | Materiales](https://platzi.com/clases/stylus/)

* [clase 17 - Estilos con preprocesadores · LeonidasEsteban/webpack-4@1107aef · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/1107aef95f2c571fcdf9747bd3a43f3b2b79868e)

### Comentarios:

* **heysoypaez** (5)

	
	#Mi resumen
	
	Tutorial: Cómo trabajar con preprocesadores de CSS en Webpack
	
	  1. **Necesitas instalar los loaders de los preprocesadores:**
	
	
	``` 
	    	npm install sass-loader
	    	npm install stylus-loader
	    	npm installless-loader
	    	npm install postcss-loader
	    
	    --save-dev --save-exact
	    
	    //Versión Corta
	    
	    	npm install sass-loader stylus-loader less-loader postcss-loader --save-dev --save-exact
	    	
	    
	```
	
	  1. Antes de configurar los preprocesadores en webpack necesitas tenerlos previamente instalado en tu computador, tenerlos en tus `Peer dependencies`.
	
	
	
	Instalando preprocesadores de CSS
	``` 
	    	npm install sass
	    	npm install node-sass
	    	npm install stylus
	    	npm installless
	    
	    --save-dev --save-exact
	    
	    //Shortversion
	    
	    	npm install sass stylus less--save-dev --save-exact
	    	
	    
	```
	
	  1. Necesitas añadir los loaders en tus archivo de webpack.config.js.
	
	
	``` 
	    			{
	    				test: /\.scss$/,
	    				use: [ 
	    
	    					"style-loader",
	    					"css-loader",
	    					"sass-loader"
	    					]
	    			},
	    			{
	    				test: /\.less$/,
	    				use: [ 
	    
	    					"style-loader",
	    					"css-loader",
	    					"less-loader"
	    					]
	    			},
	    			{
	    				test: /\.styl$/,
	    				use: [ 
	    
	    					"style-loader",
	    					"css-loader",
	    					"stylus-loader"
	    					]
	    			}
	    
	```
	
	  1. ¡Y voilá! Pon a correr tu webpack config y crea unos diseños inspiradores para tu aplicación web.
	
	
	
	En mi caso:
	``` 
	    npm run build:precss
	    
	    
	```

	* **Luis Rangel Castro** (2)

		```
		    npm install -D sass-loader stylus-loader less-loader postcss-loader
		    
		```

	* **Luis Rangel Castro** (1)

		```
		    npm install -D sass stylus less
		    
		```

* **Fadith Enrique Escorcia Mujica** (3)

	
	wow y pensar que yo queria comprar prepros :v esta clase me ahorro 29 dolares

* **heysoypaez** (3)

	
	En caso de PostCSS …  
	#Mi resumen
	
	**Tutorial: Cómo trabajar con POST CSS en Webpack**
	
	  1. Necesitas instalar el loader de PostCSS:
	
	
	``` 
	    	npm install postcss-loader --save-dev --save-exact
	    
	    
	```
	
	  1. Configura el loader de POST CSS en webpack.config.js
	
	
	
	_Nota:_
	
	  * Los archivos de post css son .css
	  * Primero aplica css loader y despues postcss loader
	
	
	``` 
	    				test: /\.css$/,
	    				use: [ 
	    
	    					"style-loader",
	    					{
	    						loader:"css-loader",
	    						options: {
	    							importLoaders:1
	    						}
	    					},
	    					"postcss-loader"
	    
	```
	
	  1. PostCSS trabaja con plugins, instala lo que usarás.
	
	
	``` 
	    
	    npm install --save-dev --save-exact postcss-nested
	    
	    
	```
	
	  1. Añade los plugins usados en postcss.config.js
	
	
	``` 
	    	module.exports = {
	    		plugins: {
	    			"postcss-nested": {
	    				
	    			}
	    		}
	    	}
	    
	```
	
	  1. ¡Y voilá! Pon a correr tu webpack config y crea unos diseños inspiradores para tu aplicación web.
	
	
	
	En mi caso:
	``` 
	    npm run build:precss
	    
	    
	```

	* **Luis Rangel Castro** (1)

		```
		    npm install -D postcss-nested
		    
		```

* **NestorBeltran** (2)

	
	<https://platzi.com/tutoriales/1548-react/4258-usa-los-snippets-de-emmet-para-escribir-mas-rapido-en-react/>

* **David Behar** (1)

	
	¿Cómo le haces para usar emmet en React? No encuentro el plugin de vscode

	* **Gabriel De Andrade (Platzi)** (4)

		
		Dentro de VSCode debes seleccionar el lenguaje del archivo para que sea JavaScript React. Puedes hacer esto agregando esta línea en tu settings.json de VSCode (Ctrl + Shift + P y buscas “Preferences: Open Settings(JSON)”) o agregandolo al settings.json dentro de tu carpeta .vscode de tu proyecto  
		[Enable Emmet Support for JSX](https://medium.com/@eshwaren/enable-emmet-support-for-jsx-in-visual-studio-code-react-f1f5dfe8809c)
		``` 
		    "files.associations": {
		        "*.js": "javascriptreact",
		      },
		    
		```

	* **David Behar** (1)

		
		Wow, eso fue súper rápido, ya vi que se le metieron super poderes al autocompletado, muchas gracias, por mi parte quedó así:
		``` 
		    "files.associations": {
		        "*.js": "javascriptreact",
		        "*.jsx": "javascriptreact",
		      },
		    
		```

	* **David Behar** (1)

		
		Sobre todo fue genial que no tuve que instalar un plugin adicional, siento que instalar plugins para cada cosa no está tan cool

	* **Gabriel De Andrade (Platzi)** (2)

		
		Si, React está bastante bien complementado con VSCode, y su usas TypeScript empezarás a tener aún más superpoderes 😛

* **GibsonR** (1)

	
	Excelente curso de verdad que un aprende

* **Thony07** (1)

	
	ADVERTENCIA !!!
	
	La versión de la dependencia _SI_ importa mucho !  
	Si no saben cual versión instaló Leonidas, fíjense en la opción “Archivos y Enlaces”, diríjanse al repo del curso y entren al package.json !
	
	Tal vez a mucho les parezca obvio pero a muchos tambien les ayudará.
	
	Saludos y suerte 😄

	* **Juan José Vega Quintero** (1)

		
		Igual todo esta funcionando correctamente con las ultimas versiones

	* **Thony07** (1)

		
		@juanjosevega Mejor!  
		El caso es que pueden haber conflicto entre versiones.  
		Ojo, dije que “puede haber” no dije que si o si habría

* **Luis Rangel Castro** (1)

	
	[repo](https://github.com/LeonidasEsteban/webpack-4/tree/master/prepro/src)

* **SOFTDYNAMIC** (1)

	
	postcss es el que malogra la fiesta u.u

* **Fernando Alejandro Yerena Ramos** (1)

	
	`importLoader` es una opción de `css-loader` que nos permite configurar cuantos _loaders_ serán aplicados antes de `css-loader`
	
	Pueden consultar la documentación de `css-loader`[aquí](https://webpack.js.org/loaders/css-loader/#importloaders).

* **Adrian Garcia Saaib** (1)

	
	Pues el que más me llamó la atención fue post 😄 también porque he visto que lo usan algunos profesores de platzi

	* **Manuel Ojeda** (1)

		
		Quizás también tome ese curso, ya conozco LESS y SASS 🤔

	* **Espasa** (1)

		
		Te lo recomiendo, sobretodo si trabajas o quieres trabajar con CSS moderno.  
		PostCSS te permitirá hacer entendible el código de CSS3 en todos los navegadores y utilizar código de CSS4 gracias a sus plugins.

* **onlinejaime** (1)

	
	Hasta ahora he usado bootstrap y funcionaba con los tres anteriores preprocesadores. Al seguir la clase con lo de postcss ya no funciona el proyecto si no comento la línea de bootstrap. **¿Sabéis por qué puede ser?**

	* **Manuel Ojeda** (2)

		
		Hola Jaime, si he leído que existe conflicto entre Bootstrap 4 que está construido con SASS y PostCSS, quizás este plugin de NPM te ayude:  
		<https://www.npmjs.com/package/bootstrap-postcss>

* **Johan Stivens Suarez Galindo** (1)
No entendí exactamente qué es una peerDependencies, alguien me puede explicar, por favor?

	* **boni** (1)

		
		Alli van dependencias que tu “npm package” requiere que instales para funcionar correctamente.

* **czabala847** (1)
Para archivos TypeScript se necesita también un loader?

	* **Gabriel De Andrade (Platzi)** (2)

		
		Así es, pero en la documentación oficial de webpack puedes aprender a configurarlo [TypeScript - WebPack](https://webpack.js.org/guides/typescript/) 😄

* **onlinejaime** (1)
Estilos con preprocesadores Hasta ahora he usado bootstrap y funcionaba con los tres anteriores preprocesadores. Al seguir la clase con l...

	* **Edward Steven Ramos Palacios** (1)

		
		Puede que haga falta algun loader para post css.

# Conceptos Avanzados de Webpack

## 0180. Evitar código duplicado

### Descripción:


### Links:

* [SplitChunksPlugin | webpack](https://webpack.js.org/plugins/split-chunks-plugin/)

* [clasee 18 - Evitar código duplicado · LeonidasEsteban/webpack-4@b897f99 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/b897f995c7ae2ec97f1fc02e60306862ba194db0)

### Comentarios:

* **Pablitvs** (7)

	
	pero en este modulo no cambiaste de camisa!

* **David Behar** (3)

	
	## Code splitting:
	
	.  
	Es útil dividir nuestro código en diversos archivos y a veces enteros proyectos, pero no queremos cargar nuestra aplicación de más multiplicando el peso de alguna dependencia al utilizarla en diferentes partes de la aplicación, para eso utilizamos el módulo de optimización con splitChunks en webpack.  
	.
	``` 
	    module.exports = {
	      entry:{
	        home: path.resolve(__dirname, './src/js/index.js'),
	        contact: path.resolve(__dirname, './src/js/contact.js'),
	      },
	      devServer:{...},
	      output:{...},
	      module:{...},
	      plugins: [...],
	      optimization:{
	        splitChunks:{ // permite dividir el peso en diferentes archivos para evitar duplicación
	          chunks:'all',
	          minSize:0,
	          name:'commons',
	        }
	      },
	    }
	    
	```

* **Facundo Nicolás García Martoni (Platzi)** (3)

	
	Resumen de la clase
	
	1)) Agregar lo siguiente al archivo **webpack.config.js** :
	``` 
	    mode: 'production',
	    optimization: {
	        splitChunks: {
	          chunks: "all",
	          minSize: 0,
	          name: "commons"
	        }
	      }
	    
	```
	
	2)) Llamar al script **commons.js** generado en los archivos html:
	``` 
	    <scriptsrc="dist/js/commons.js"></script>
	    <scriptsrc="dist/js/index.js"></script>
	    
	```

	* **heysoypaez** (1)

		
		gracias por el aporte! me lo tomo para mis notas personales 😃

* **pabloverduzcos** (2)

	
	A esto tambien se le conoce como **vendor files** 📦, ¿cierto?

	* **Demian Arenas (Platzi)** (4)

		
		Así es Juan Pablo, ese archivo con todo el código en común es el vendor file que guardamos en cache para optimizar los sitios web.

	* **pabloverduzcos** (1)

		
		¡Genia!

* **Fernando Alejandro Yerena Ramos** (2)

	
	La propiedad `chunk` de `splitChunks` puede recibir cualquiera de estos tres parámetros:
	
	  * ‘initial’: indica a webpack que optimice solo los módulos que son importados de forma no dinámica.
	  * `async`: webpack optimizará solo aquellos que son cargados de forma no-dinámica.
	  * `all`: indica a webpack que optimice, lo mejor que pueda, los módulos sin importar si son cargados de forma dinámica o no-dinámica.
	
	
	
	Comparto esta lectura que lo explica más a detalle y con un ejemplo practico.
	
	  * [Webpack 4 — Mysterious SplitChunks Plugin](https://medium.com/dailyjs/webpack-4-splitchunks-plugin-d9fbbe091fd0)
	
	

* **Carlos Eduardo Jaramillo Franco** (1)

	
	¿Cómo puedo hacer que el propio webpack me genere los multiples index?

* **Raul Gracia Maiques** (1)

	
	[2:04] De eso se trata está clase… De… Prevenir código duplicado.
	
	Bueno, luego de esta introducción, ya saben como funciona esto.
	
	Vamos a duplicar la carpetita. [2:14]
	
	xD
	
	Saludos desde España,

* **Andrés Valencia** (1)

	
	al quitar _web server_ del **package.json** se rompen los links a las imágenes, video y fuentes, pero que no _“panda el cúnico”_ dos clases más adelante se corrige

* **Alexis Anderson Montenegro Reyes** (1)

	
	Yo solo habia escuchado Chunks en Minecraft 😉

* **David Behar** (1)

	
	A mi me gustó mucho más especificar en la tarea del **package.json** si va a ser **desarrollo** o **producción** , ya que a veces utilizamos el mismo archivo de webpack para desarrollo y para producción sólo cambiando **webpack** por **webpack-dev-server**

* **SOFTDYNAMIC** (1)

	
	¿Por qué no me genera ningún commons.js?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Asegurate de cambiar en el package.json wepack-dev-server por solo webpack en la parte de los scripts  
		`"build:prevent-duplication": "webpack --config ./prevent-duplication/webpackl.config.js"`

* **Carlos Stiwar Asprilla Mosquera** (1)

	
	Me pueden indicar porque no se me crea la carpeta dist automaticamente como en el video?

	* **Juan Pablo Castillo Rioja** (4)

		
		puede ser que en el script que llamas estas usando webpack-dev-server en lugar de webpack

* **Josias Cubillos Gutierrez** (1)

	
	Alguien podría explicarme por qué al eliminar la carpeta dist como lo hace Leonidas en el video y correr la tarea no me genera nuevamente la carpeta dist.

	* **Andres Roberto Coello Goyes** (1)

		
		A mi me paso lo mismo, puede ser un problema de cache, en mi caso yo volvi a crear esa carpeta vacia DIST y volvi a ejecutar y todo funciono correctamente…

	* **miguelangelsoler** (2)

		
		Debes ejecutar la tarea como **webpack** , no como webpack-dev-server.

* **Adrian Garcia Saaib** (1)

	
	Me aparecio esto, dice que es por el tamaño del video y del bundle pero no entiendo que pasa.  
	![as.PNG](https://static.platzi.com/media/user_upload/as-599af5f2-7590-4042-8f51-f783376b020a.jpg)  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-c5ffb70c-de58-4639-b1f8-010c969531ce.jpg)

	* **onlinejaime** (1)

		
		En modo ‘production’ estás, entiendo. En el modo ‘development’, ¿también te ha sucedido lo mismo?. Porque a mí no, me sale todo ok. Pero no he probado modo producción.

	* **Adrian Garcia Saaib** (2)

		
		Si, al parecer era eso, gracias.  
		Tambien no fucnionaba al mostrar en el browser pero error de sintaxis. 👀

## 0190. Añadiendo un Dynamic Link Library

### Descripción:


Mientras más librerías agregamos más lento se empiezan a volver nuestros builds, arruinando así la **Developer Experience**. Por suerte podemos crear una (o varias) Dynamic Link Library para acortar estos tiempos.

Una **Dynamic Link Library (DLL)** es un conjunto de librerías comunes que no cambian frecuentemente por lo que se hace un build por adelantado de las mismas para no re-empaquetar cada vez que hacemos build de nuestra aplicación.

Beneficiando tanto la **Developer Experience** como la **User Experience** ya que el caché del navegador va a mantener una copia que solo va a cambiar cuando nosotros agreguemos o quitemos alguna dependencia, ahorrando así valiosos requests al servidor.

### Links:

* [DllPlugin | webpack](https://webpack.js.org/plugins/dll-plugin/)

* [clase 20 - Añadiendo un Dymanic Link Library · LeonidasEsteban/webpack-4@263e9db · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/263e9db3e0a0c07a65b3b5e9ec4ebad46e3ee94d)

### Comentarios:

* **heysoypaez** (14)

	
	Principio subyacente de la clase.
	
	  1. Mientras más dependencias más lento será tu build de production.
	
	
	
	¿Qué acciones clave extraigo de esta clase ?
	
	_Para hacer el build más rápido vamos a aplicar la técnica de **dynamic link library**._
	
	_“Una Dynamic Link Library (DLL) es un conjunto de librerías comunes que no cambian frecuentemente por lo que se hace un build por adelantado de las mismas para no re-empaquetar cada vez que hacemos build de nuestra aplicación.”_.
	
	* * *
	
	#Tutorial:  
	Cómo crear un Dynamic Link Library para acortar el tiempo de carga de librerias. (Estamos creando un webpack config super optimizado para produccion).
	
	  1. Creamos los siguientes archivos:
	
	
	  * `webpack.config.js` (el webpack de toda la vida).
	  * `webpack.dll.config.js` (el webpack para las librerias).
	
	
	  1. Colocamos las dependencias core que se repite su uso en nuestra app en el entry de nuestro `webpack.dll.config.js`. para guardarla en cache del navegador y precargarlas.
	
	
	
	`webpack.dll.config.js`
	``` 
	    entry: {
	    		modules: [
	    		"react",
	    		"react-dom"
	    		]
	    	},
	    
	    
	```
	
	  1. Añadimos plugin de DLL en nuestro `webpack.dll.config.js`.
	
	
	
	`webpack.dll.config.js`
	``` 
	    plugins: [
	    		new webpack.DLLPlugin({
	    			name: "[name]",
	    			path: path.join(__dirname, "[name]-manifest.json")
	    		})
	    	]
	    
	```
	
	  1. Eliminamos lineas de código de developmente en nuestro `webpack.dll.config.js`.
	
	  2. Corres el dll wepack config y despues corres el otro webpack config con el script que creaste para `npm run` en tu package.json.
	
	
	
	
	`package.json`
	``` 
	       
	        "build:dll": "webpack --config ./dll/webpack.dll.config.js",
	        "build:prevent-duplication-fast": "webpack --config ./dll/webpack.config.js"
	    
	    
	```
	
	`cli`
	``` 
	    	$ npm run build:dll
	    	$ npm run build:prevent-duplication-fast
	    
	    
	```
	
	  1. Añades el siguiente plugin en tu archivo `webpack.config.js`. El plugin optimizará tu CSS para producción, no está directamente relacionado con el DLL.
	
	
	``` 
	    		newMiniCssExtractPlugin({
	    			filename: "css/[name].css",
	    			chunkFilename: "css/[id].css"
	    		})	,
	    
	    
	```
	
	Notas:
	
	  * library es quien enlaza los modulos que creamos al codigo que escribimos de la app
	  * Esta clase es dificil, practica, genera nuevas configuraciones.
	
	

* **Facundo Nicolás García Martoni (Platzi)** (3)

	
	Resumen de la clase
	
	Se deben tener dos archivos:
	
	  * **webpack.config.js**
	  * **webpack.dll.config.js**
	
	
	
	El primero debe estar optimizado para producción, de esta manera:
	``` 
	    module.exports = {
	      entry: {
	        modules: ["react", "react-dom"]
	      },
	      mode: "production",
	      output: {
	        path: path.resolve(__dirname, "dist"),
	        filename: "js/[name].js",
	        library: "[name]"
	      },
	      plugins: [
	        new webpack.DllPlugin({
	          name: "[name]",
	          path: path.join(__dirname, "[name]-manifest.json")
	        })
	      ]
	    };
	    
	```
	
	En el segundo, tenemos que requerir el archivo **modules-manifest.json** creado al final el primer archivo de configuración, en la sección de plugins:
	``` 
	    newwebpack.DllReferencePlugin({
	          manifest: require("./modules-manifest.json")
	        })
	    
	```
	
	En la clase, además se reemplazó el **style-loader** por el **mini-css-extract-plugin** , agregando en la sección de plugins lo siguiente:
	``` 
	    newMiniCssExtractPlugin({
	          filename: "css/[name].css",
	          chunkFilename: "css/[id].css"
	        }),
	    
	```

* **Northerchild** (2)

	
	Es genial eso

* **CodingLeonardo** (2)

	
	Excelente Clase Leonidas💚😆

* **Jose Luis Colmenares** (2)

	
	Esta clase me dio algunos problemas.

	* **Daniel Esteves** (1)

		
		¡Hola @jlrcolm! ¿Nos podrías contar que problemas te dio? Y de ser posible captura de pantalla de tu error 😃

* **Luis Arturo Lira Cerda** (2)

	
	Tengo una duda, ¿por qué cuándo me genera el archivo html me inyecta tanto el js de home y de contacto?
	``` 
	    <scriptsrc="js/home.js"></script>
	    <scriptsrc="js/contacto.js">
	    
	```
	
	Así tengo configurada la parte de HtmlWebpackPlugin
	``` 
	    new HtmlWebpackPlugin({
	      template: path.resolve(__dirname, ‘index.html’),
	      minify: {
	        collapseWhitespace: true,
	        removeComments: true,
	        removeRedundantAttributes: true,
	        removeScriptTypeAttributes: true,
	        removeStyleLinkTypeAttributes: true,
	        useShortDoctype: true
	      }
	    })
	    
	```

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Puedes compartir tu archivo webpack.config.js para revisar si falta algo en otra parte que pueda hacer que este causando este comportamiento.

	* **Luis Arturo Lira Cerda** (1)

		
		@gollum23 Así es como tengo el webpack.config. Si agrego otro HtmlWebpackPlugin y que tome el template de contacto.html, también le inyecta ambos archivos de JS (home.js y contacto.js)
		``` 
		    const path = require('path')
		    const MiniCssExtractPlugin = require('mini-css-extract-plugin')
		    const HtmlWebpackPlugin = require('html-webpack-plugin')
		    const TerserJSPlugin = require('terser-webpack-plugin')
		    const OptimizeCSSAssetsPlugin = require('optimize-css-assets-webpack-plugin')
		    const webpack = require('webpack')
		    
		    module.exports = {
		      entry: {
		        home: path.resolve(__dirname, 'src/js/index.js'),
		        contacto: path.resolve(__dirname, 'src/js/contacto.js')
		      },
		      mode: 'production',
		      output: {
		        path: path.resolve(__dirname, 'dist'),
		        filename: 'js/[name].js',
		        chunkFilename: 'js/[id].[chunkhash].js'
		      },
		      optimization: {
		        minimizer: [
		          new TerserJSPlugin({}),
		          new OptimizeCSSAssetsPlugin({})
		        ]
		      },
		      module: {
		        rules: [
		          {
		            test: /\.js$/,
		            use: 'babel-loader',
		            exclude: '/node_modules/'
		          },
		          {
		            test: /\.css$/,
		            use: [
		              { loader: MiniCssExtractPlugin.loader },
		              {
		                loader: 'css-loader',
		                options: {
		                  importLoaders: 1
		                }
		              },
		              'postcss-loader'
		            ]
		          },
		          {
		            test: /\.less$/,
		            use: [
		              { loader: MiniCssExtractPlugin.loader },
		              'css-loader',
		              'less-loader'
		            ]
		          },
		          {
		            test: /\.scss$/,
		            use: [
		              { loader: MiniCssExtractPlugin.loader },
		              'css-loader',
		              'sass-loader'
		            ]
		          },
		          {
		            test: /\.styl$/,
		            use: [
		              { loader: MiniCssExtractPlugin.loader },
		              'css-loader',
		              'stylus-loader'
		            ]
		          },
		          {
		            test: /\.jpg|png|gif|woff|eot|ttf|svg|mp4|webm$/,
		            use: {
		              loader: 'url-loader',
		              options: {
		                limit: 90000
		              }
		            }
		          }
		        ]
		      },
		      plugins: [
		        new HtmlWebpackPlugin({
		          template: path.resolve(__dirname, 'index.html'),
		          minify: {
		            collapseWhitespace: true,
		            removeComments: true,
		            removeRedundantAttributes: true,
		            removeScriptTypeAttributes: true,
		            removeStyleLinkTypeAttributes: true,
		            useShortDoctype: true
		          }
		        }),
		        new MiniCssExtractPlugin({
		          filename: 'css/[name].css',
		          chunkFilename: 'css/[id].css'
		        }),
		        new webpack.DllReferencePlugin({
		          manifest: require('./modules-manifest.json')
		        })
		      ]
		    }
		    
		```

	* **Fernando Alejandro Yerena Ramos** (6)

		
		@Luis_LiraC, en la documentación de [`HTML Wepack Plugin`](https://github.com/jantimon/html-webpack-plugin#usage) específica que si tenemos _multiple entry points_ , todos serán agregados en una etiqueta `<script>` dentro del HTML generado (lo dice al final de _Usage_ ) .
		
		Para solucionarlo, en la configuración del _plugin_ debemos especificar los _chunks_ (nuestros entry points), incluyendo el creado por `splitChunk`; que queremos inyectar en cada archivo HTML.
		``` 
		    	plugins: [
		            new HtmlWebpackPlugin({
		                title: 'Home',
		                template: path.resolve(__dirname, 'src' ,'index.html')
		                chunks: ['commons','home'],
		                filename: 'index.html',
		            }),
		            new HtmlWebpackPlugin({
		                title: 'Contact Page',
		                myPageHeader: 'Contact',
		                template: path.resolve(__dirname, 'src' ,'index.html')
		                chunks: ['commons','contact'],
		                filename: 'contact.html',
		            })
		       ]
		    
		```
		
		Referencias:
		
		  * [_Usage_ HTML Webpack Plugin](https://github.com/jantimon/html-webpack-plugin#usage)
		  * [_Multi-page applications_](https://medium.com/a-beginners-guide-for-webpack-2/multi-page-applications-4ae2ebfabc37)
		  * Me pasó lo mismo 🤣
		
		

* **Javier Armando Vargas Vega** (1)

	
	Muy interesante el tema explicado en el video.
	
	Sin embargo veo que al final del video abre el archivo index.html que está ubicado en la raíz, pero no abre el archivo index.html que se genera luego de correr webpack.
	
	En mi caso intenté correr el archivo index.html que se generó en la carpeta de distribución, pero me arrojó un error: que no encontraba el archivo modules.js
	
	Sin embargo lo corregí modificando el archivo index.html que se generó.

* **FizIrvin** (1)

	
	estas clases de optimización y preparar para producción son buenas.

* **Carlos Martinez** (1)

	
	tengo una duda, porqué Leonidas modifica el index.html y el contact.html para enlazarles el css y javascript???
	
	no se supone que eso ya está todo enlazado en la carpeta dist? no entiendo porque debe enlazarlos a mano, o acaso lo hace para demostrar?
	
	en la carpeta dist solo tenemos el index.html pero con el js tanto de commons(modules ahora) , de home y de contacto, es decir 3 archivos enlazados de js cuando debería haber solo 2.
	
	estuve investigando y si queremos tener 2 .html en la carpeta dist, debemos hacer 2 instancias del htmlWebpackPlugin, y si queremos 3, 3 instancias y asi
	
	asi que para resumir mi pregunta, Leonidas solo hace las modificaciones para enlazar el css y js a mano para demostrar? ya que creo yo que esa no es la manera correcta de modificarlos no?

	* **Diego Ivan Padilla Bernal** (4)

		
		Exactamente eso que hace Leonidas no es lo correcto, lo mejor es que webpack te genere los dos archivos html y te agrege los assets indispensables

	* **Alan Santiago** (2)

		
		Y cómo se puede hacer que _webpack_ genere esos dos archivos?

	* **Carlos Martinez** (2)

		
		estuve investigando, y si vas a crear un html a mano sería para tener un template de referencia, por ej en react se necesita tener un elemento HTML contenedor, donde irá toda la app hecha en react, por ello se hace un HTML de template y todos sus scripts y css son puestos por webpack, ahora si no tienes necesidad de “preconfigurar” un HTML pues solo indicas el nombre del archivo en el HtmlWebpackPuglin
		
		he aqui de lo que hablo:
		``` 
		    new HtmlWebpackPlugin({
		                
		                // que tome este archivo ya creado anteriormete como template
		                template: path.resolve(__dirname, 'publicTemplates','index.html'),
		                filename: "index.html",
		                //inject: true,
		                chunks: ['home']
		            }),
		            new HtmlWebpackPlugin({
		                 
		                // que tome este archivo ya creado anteriormete como template
		                template: path.resolve(__dirname, 'publicTemplates','contact.html'),
		                filename: "contact.html",
		                //inject: true,
		                chunks: ['contact'],
		                
		                
		            })```
		    
		```

	* **oqodigital** (1)

		
		Hay que entender que igual son solo ejercicios, para mostrar los potenciales uso de webpack independiente de lo que se esté haciendo.  
		Por ejemplo, el PNG de platzi, el logo, se perdió, pero no importa, lo importante era la configuración de webpack específicamente de Dll

* **onlinejaime** (1)

	
	A mí me pasa lo mismo que @Luis_LiraC…

* **Schenier Aldair López Uriarte** (1)
Entonces en vez de utilizar Chunk, de la clase anterior lo suyo sería mejor utilizar DLL? O Cuando usamos una y cuando la otra? O según g...

## 0200. Dynamic imports

### Descripción:


### Links:

* [@babel/plugin-syntax-dynamic-import · Babel](https://babeljs.io/docs/en/babel-plugin-syntax-dynamic-import)

* [clase 20 - Dynamic imports · LeonidasEsteban/webpack-4@b3339ed · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/b3339ed4317e6cff6f09206be8d55c1917dc9cba)

### Comentarios:

* **David Behar** (4)

	
	En esta clase se me figuró a Leo diciendo OMG como Jonathan Joestar de JoJo’s  
	![](https://media1.tenor.com/images/5cac16c4813db3157438d2e3683cfd75/tenor.gif?itemid=15404720)

	* **Juan José Vega Quintero** (1)

		
		La serie es buena?

	* **David Behar** (2)

		
		A mi me gusta bastante

* **Facundo Nicolás García Martoni (Platzi)** (4)

	
	Resumen de la clase
	
	1)) Instalar **@babel/plugin-syntax-dynamic-import**
	``` 
	    npm install --save-dev --save-exact @babel/plugin-syntax-dynamic-import
	    
	```
	
	2)) En **.babelrc** agregar el plugin:
	``` 
	    "plugins": [
	    	"@babel/plugin-syntax-dynamic-import"
	    ]
	    
	```
	
	3)) En el atributo output de **webpack.config.js** agregar lo siguiente:
	``` 
	    publicPath:'dist/',
	    chunkFilename:'js/[id].[chunkhash].js'
	    
	```
	
	Pd: Si el error “ _Module not found: Error: Can’t resolve '@babel/runtime/helpers/asyncToGenerator_ ’” ocurre, instalar **@babel/runtime** , así:
	``` 
	    npm install --save-dev --save-exact @babel/runtime
	    
	```

	* **Luis Rangel Castro** (1)

		```
		    npm install -D @babel/plugin-syntax-dynamic-import
		    
		```

* **cesarcubillos** (3)
¿Cuando hago imports a partir de un evento siempre debo tratar el handle como una función asíncrona cierto?

	* **Juan David Castro (Platzi)** (2)

		
		Sip. Los imports dinámicos son como hacer peticiones a un servidor con **`fetch`**. Podemos usar _async await_ o promesas. O también algunas herramientas como Next.js que nos ayudan a usar _imports_ dinámicos sin preocuparnos por la parte asíncrona, solo la ruta al componente, que si con SSR o que sin SSR, un loader y listos.
		
		<https://github.com/zeit/next.js/blob/canary/examples/with-dynamic-import/pages/index.js>

* **pablo_l** (2)

	
	No funciona, llegue al punto de copiar y pegar la misma config. y no hay caso. es como si luego de definir al publicPath anida las peticiones de los recursos: `http://127.0.0.1:5500/dynamic-imports/dist/dist/css/home.css`  
	cuando en realidad, los transpilados, esta en:  
	`http://127.0.0.1:5500/dynamic-imports/dist/css/home.css http://127.0.0.1:5500/dynamic-imports/dist/...`  
	Despues, edito manualmente las rutas, y hay otro error más:  
	`Uncaught (in promise) RangeError: Maximum call stack size exceeded`  
	cuando ejecuto el botón.

	* **Johan Stivens Suarez Galindo** (1)

		
		Puedes poner el código de tu webpack y de tu app para examinar lo que pasa?

	* **Javier Armando Vargas Vega** (1)

		
		Me ocurría lo mismo. Al ver en el error me decía que el archivo js que se generaba dinámicamente lo buscaba en el directorio dist/dist/archivodinamico.js.
		
		Para solucionarlo le quité el `publicPath` de la configuración del webpack.config.js y funcionó ahora sí bien.

* **Juan Carlos Pinzón** (2)
También puedo utilizar Dynamic imports para cargar algún paquete o librería que previamente haya instalado con npm? Por ejemplo utilizar ...

	* **Matthew Dominick Rosell Felix** (1)

		
		Creo que en esta clase de React Avanzado se realiza lo que estas preguntando: <https://platzi.com/clases/1601-react-avanzado/21269-uso-de-polyfill-de-intersection-observer-e-impor-2/?time=2>  
		Espero te sirva.

* **Mariana Valencia** (1)

	
	Qué locura esta clase ❤️

* **heysoypaez** (1)

	
	¿Alguien me puede explicar por qué fue necesario configurar esto para que funcionará?
	``` 
	    	output: {
	    		path: path.resolve( __dirname , "dist/" ),
	    		filename: "js/[name].js",
	    		publicPath: "dist/",
	    		chunkFilename: "js/[id].[chunkhash].js "
	    	},
	    
	```
	
	¿Por qué antes webpack no consiguió el archivo y ahora si?

	* **Luis Jeanpier Monserrate** (2)

		
		tambien estoy algo confundido en esta parte, en algun momento webpack empezo a solicitar la dirección de donde buscara los assets. en la clase pasada no cargaba ni la imagen ni el video; despues de indicarle el publicpath si lo hizo

	* **Emmanuel Tepepa Carrasco** (1)

		
		Hasta donde yo entiendo como ocupa los .html del template y no de dist/ por eso le da ese error, entonces tiene que especificar donde se van a buscar los archivos .js adicionales. Creo que si usara los .html de dist/ no tendría problema, pero no estoy seguro.

	* **Manuel Rivera** (1)

		
		Por esa misma configuración ahora si cargan los demas archivos ? como la imagen y el video ? entonces es como decirle a webpack que aparte de la dirección en la que busca los archivos le configruamos el publicPath para que busque en la carpeta que se le especifique ademas de en la que esta buscando ?

	* **Andrés Valencia** (1)

		
		Porque ya no estamos utilizando webpack-dev-server en el package.json sino sólo webpack

* **Diego Ivan Padilla Bernal** (1)

	
	Si tienes bien configurado el webpack para que el mismo te genere los archivos index y contact no hará falta lo último de configurar el **publicPath**

	* **Alan Santiago** (2)

		
		¿Cómo se configura?  
		Ya agregué las dos instancias de **HtmlWebpackPlugin** :
		``` 
		    newHtmlWebpackPlugin({
		          title: 'Home',
		          template: path.resolve(__dirname, 'src/index.html'),
		          chunks: ['modules', 'home'],
		          filename: 'index.html'
		        }),
		        newHtmlWebpackPlugin({
		          title: 'Contact',
		          template: path.resolve(__dirname, 'src/index.html'),
		          chunks: ['modules', 'contact'],
		          filename: 'contact.html'
		        }),
		    
		```
		
		Pero los archivos _.html_ que salen sólo tienen **un archivo js** , no tienen incluido a _modules.js_ , configuré la _publicPath_ a _dist_ y ahora llama a _dist/css/style.css/_ en vez de _css/style.css/. No sé cómo configurarlo 😫

	* **Carlos Eduardo Jaramillo Franco** (1)

		
		@alanzzat me pasa exactamente lo mismo, encontraste alguna solucion?

* **Manuel Rivera** (1)
¿Por qué en la clase anterior no cargaba la imágeni y tampoco el video, y ahora si se cargan los dos en el navegador ?

# Practicando

## 0210. Setup de Platzi Badges

### Descripción:


### Links:

* [Curso de Git y GitHub Profesional | Platzi | Materiales](https://platzi.com/clases/git-github/)

* [GitHub - Sparragus/platzi-badges: Código del proyecto del Curso de React.js de Platzi](https://github.com/sparragus/platzi-badges)

* [Curso de React.js | Materiales](https://platzi.com/clases/react/)

* [Curso Vue.js | Platzi | Materiales](https://platzi.com/clases/vuejs/)

* [clase 21 - setup de platzi badges · LeonidasEsteban/webpack-4@9bbf306 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/9bbf306ded9d158b083b4b4370d3bef631d2f5da)

### Comentarios:

* **JoosCode** (4)

	
	En esta clase si comienza lo bueno :v

* **heysoypaez** (4)

	
	Esta clase fue basicamente de limpieza para dejar nuestra React App de Platzi badges lista para trabajar por nosotros.
	
	Recuerda que create-react-app te preconfigura Webpack, la misión de este curso es que lo hagamos nosotros.
	
	**¿Qué hicimos?**
	
	_Eliminar las dependencias que no vamos a usar en package.json para dejarlo de la siguiente manera:_
	``` 
	    {
	      "name": "platzi-badges",
	      "version": "0.1.0",
	      "private": true,
	      "scripts": {
	        "server": "json-server --port 3001 --watch server/db.json",
	        "seed": "node server/seed.js"
	      },
	      "dependencies": {
	    
	        "boostrap": "^2.0.0",
	        "md5": "^2.2.1",
	        "react": "16.8.3",
	        "react-dom": "16.8.3",
	        "react-router-dom": "^5.0.1"
	      },
	      "devDependencies": {
	        "faker": "^4.1.0",
	        "json-server": "^0.14.2"
	      },
	      "eslintConfig": {
	        "extends": "react-app"
	      },
	      "browserslist": [
	        ">0.2%",
	        "not dead",
	        "not ie <= 11",
	        "not op_mini all"
	      ]
	    }
	    
	```

* **Jessie Buckland Pérez** (3)

	
	Dale a tu cuerpo Webpack Macarena!!!

* **Manuel Rivera** (2)

	
	Nos fuimoooos !!!

* **aarango09** (1)

	
	Que poder,

* **Andrés Felipe Cano Sierra** (1)

	
	Momento épico

* **Carlos Gómez Mont** (1)

	
	A mi me sigue arrojando 2 vulnerabilidades pero con audit fix quedó 😃

	* **Andrés Felipe Cano Sierra** (3)

		
		¡Ten cuidado!  
		Ese comando te puede actualizar algunas dependencias, ya que las vulnerabilidades son parchadas entre actualizaciones de versiones.

* **lenielluzardo** (1)

	
	Genial!, super emocionado de retomar el curso y empezar a practicar con un proyecto real💪🏼

* **josegts** (1)

	
	El curso del profe Richard, fue el primero que tome, nostalgia :3

* **Julio Ignacio Oyarzun Cayuman** (1)

	
	Acabo de bajar el proyecto, mas el archivo de configuración package.json ya no tiene todas las tareas mostradas en el video.

* **Jose Luis Colmenares** (1)

	
	Como se supone que funciona `npm run start` si había eliminado todo los node_modules y package.json?

	* **Alejandro González Reyes** (2)

		
		Lo mismo me he preguntado yo.  
		La verdad es que el equipo de postproducción de platzi es pésimo groso y vergonzoso.

	* **jhon manuel angulo moncada** (2)

		
		hola
		
		  1. debes borrar el archivo “package-lock.json” no el “package.json”
		
		  2. borrar el directorio node_modules  
		estas 2 cosas dentro de la carpeta Webpack-4
		
		  3. debes ir a tu consola a tu ruta…\Webpack-4\platzi-badges y correr el comando “npm i”, esto te crea el directorio node_modules pero dentro de la carpeta platzi-badges
		
		  4. ejecuta el comando “npm start” dentro de la ruta de platzi-badges y listo.
		
		
		

	* **Jesús Duarte García** (1)

		
		Funciona porque tenemos node_modules dentro de la carpeta de react y su propio package.json 😃 se borraron los de la carpeta padre para que no chocaran entre si pero siguen existiendo dentro de la carpeta React

	* **Sergio Agámez Negrete** (1)

		
		Hola, es debido a que estamos dentro de la carpeta /platzi-badges y allí si hay un package.json, ese es el que se está tomando

* **Luis Jeanpier Monserrate** (1)

	
	En esta clase tomamos el proyecto del curso de react(platzi-badges), y le removeremos sus configuraciones predefinidas de webpack, para que nosotros con lo aprendido del curso, configuremos manualmente como debería comportarse webpack en el proyecto.

## 0220. Configuración de desarrollo para Platzi Badges (React.js)

### Descripción:


 **Dependencias instaladas en clase:**

  * @babel/runtime
  * webpack
  * webpack-cli
  * webpack-dev-server
  * css-loader
  * style-loader
  * file-loader
  * babel-loader
  * @babel/core
  * @babel/preset-env
  * @babel/preset-react
  * @babel/plugin-syntax-dynamic-import
  * @babel/plugin-transform-runtime
  * @babel/plugin-proposal-class-properties
  * html–webpack-plugin



### Links:

* [GitHub - Sparragus/platzi-badges: Código del proyecto del Curso de React.js de Platzi](https://github.com/Sparragus/platzi-badges)

* [@babel/plugin-proposal-class-properties · Babel](https://babeljs.io/docs/en/babel-plugin-proposal-class-properties)

* [Curso de React.js](https://platzi.com/cursos/react/)

* [clase 22 - Configuración de desarrollo para Platzi Badges (React.js) · LeonidasEsteban/webpack-4@ab2cef5 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/ab2cef5d075c6587956239222c125435660ff866)

### Comentarios:

* **Facundo Nicolás García Martoni (Platzi)** (9)

	
	Sentencia para instalar todas las dependencias de la clase. Solo copiar y pegar en consola lo siguiente:
	``` 
	    npm i -D -E @babel/runtime webpack webpack-cli webpack-dev-server css-loader style-loader file-loader babel-loader @babel/core @babel/preset-env @babel/preset-react @babel/plugin-syntax-dynamic-import @babel/plugin-transform-runtime @babel/plugin-proposal-class-propertieshtml-webpack-plugin
	    
	```

	* **Carlos Martinez** (2)

		
		gracias, solo un pequeño detalle, @babel/runtime es una dependencia core del proyecto, por ello se instala con npm i de siempre
		
		de resto gracias, me ahorraste el trabajo jeje

	* **CodingLeonardo** (1)

		
		** ** _Gracias me ahorraste el trabajo_** **💚😆

	* **Luis Rangel Castro** (2)

		```
		    npm install --save -S @babel/runtime
		    
		```

	* **Luis Rangel Castro** (2)

		```
		    npm i -D -E webpack webpack-cli webpack-dev-server css-loader style-loader file-loader babel-loader @babel/core @babel/preset-env @babel/preset-react @babel/plugin-syntax-dynamic-import @babel/plugin-transform-runtime @babel/plugin-proposal-class-propertieshtml-webpack-plugin
		    
		```

	* **Luis Rangel Castro** (1)

		```
		    npm install -D -S @babel/plugin-proposal-class-properties
		    
		```

	* **Sergio Agámez Negrete** (1)

		
		Gracias!!! 😄

	* **Diego Camino** (1)

		
		Gracias buen hombre!

* **Luis Jeanpier Monserrate** (3)

	
	les ha pasado que no les carga las imagenes ?

	* **Brian Dennis Vega Hidalgo** (7)

		
		es por que es importante el slash del final del public path
		``` 
		    output: {
		        path: path.resolve(__dirname, "dist"),
		        filename: "js/[name].js",
		        publicPath: "http://localhost:9000/",
		        chunkFilename: "js/[id].[chunkhash].js"
		      },
		    
		```

* **Manuel Rivera** (2)

	
	Dependencias de desarrollo
	
	npm i webpack webpack-cli webpack-dev-serv  
	er css-loader style-loader file-loader babel-loader @babel/core @babel/preset-env @babel/preset-react @babel/plugin-syntax-dynamic-import @babel/plugin-transform-runtime html-webpack-plugin -D -E

	* **dcastrocoder** (1)

		
		Que buen samaritano!

* **Adrian Garcia Saaib** (2)

	
	hubo un pequeñisimo problema, para los que hacemos el ejercicio sobre el proyecto del curso de react, el servidor de la api no se puede conectar.
	
	Todas las peticiones a la api regresan error.

	* **Adrian Garcia Saaib** (9)

		
		Ya pude de una manera hacerlo funcionar de nuevo. Al parecer npm-run-all te permite correr varias tareas entonces lo volví a instalar. En package.json puse en devDependecies
		``` 
		    "npm-run-all": "4.1.5"
		    
		```
		
		despues corrí npm install
		
		Ya instalada, agregé una tarea que corriera varios comandos:  
		escribiendo npm run dev estoy corriendo tanto build:dev como server
		``` 
		    "dev": "npm-run-all -p build:dev server",
		    
		```
		
		Corrí npm run dev en terminal y funcionó bien
		
		—Ahora la única duda que tengo es si dejando el proyecto así lo podré mostrar en github igual con todo y el servidor json

* **Javier Armando Vargas Vega** (1)

	
	Muy buena clase. Sin embargo me pareció bastante confuso el tema.

* **Andrés Gutierrez** (1)

	
	una pregunta con el dll webpack plugin, nosotros en este proyecto estamos usando una single page application, pero he intentado hacer una con varias y mi segundo html renderiza lo mismo que el index, entonces si quiero hacer una multi page application no me sirve, he buscado en internet y revisado documentación, pero no entiendo, ayuda 😦

* **Ivan Bazaldua** (1)

	
	¿Por que dentro de la configuración webpack.dev.config.js en devServer se usa un contentBase apuntando a la carpeta dist? Tenia entendido que esta carpeta se genera en producción.
	``` 
	    const path = require("path");
	    const HtmlWebpackPlugins = require("html-webpack-plugin");
	    const webpack = require("webpack");
	    module.exports = {
	      entry: {
	        app: path.resolve(__dirname, "src/index.js")
	      },
	      mode: "development",
	      output: {
	        path: path.resolve(__dirname, "dist"),
	        filename: "js/[name]-bundle.js",
	        publicPath: "http://localhost:9000/",
	        chunkFilename: "js/[id].[chunckhash].js"
	      },
	      devServer: {
	        contentBase: path.resolve(__dirname, "dist"),
	        open: true,
	        port: 9000,
	        hot: true
	      },
	      module: {
	        rules: [
	          {
	            test: /\.js$/,
	            use: "babel-loader",
	            exclude: /node_modules/
	          },
	          {
	            test: /\.css$/,
	            use: ["style-loader", "css-loader"]
	          },
	          {
	            test: /\.jpg|jpeg|png|svg|gif|woff|ttf|eot|mp4$/,
	            use: {
	              loader: "file-loader",
	              options: {
	                outputPath: "assets/"
	              }
	            }
	          }
	        ]
	      },
	      plugins: [
	        new webpack.HotModuleReplacementPlugin(),
	        new HtmlWebpackPlugins({
	          template: path.resolve(__dirname, "public/index.html")
	        })
	      ]
	    };
	    
	    
	```

* **jgersain** (1)

	
	para que se usa la bandera -S cuando hace el npm install --save -S @babel/runtime

	* **GuillermoLoza** (2)

		
		Hola  
		–save y -S  
		**es lo mismo** así que no es necesario

* **Johan Stivens Suarez Galindo** (1)
Hola, una consulta, alguno sabe si con webpack es posible configurar una dirección para que se pueda acceder públicamente desde otros sit...

	* **Gabriel De Andrade (Platzi)** (2)

		
		Mmmm, creo que no estoy entendiendo bien la pregunta, esto parece un problema más de redirección de dominios, de todas maneras si la puedes explicar de nuevo sería genial! Suena a una pregunta muy interesante 😄

* **borisbelmarm** (1)
Por qué en el publicPath del output estamos hardcodeando la url del localhost para que funcione? No debería ser una ruta dinámica? Siento...

	* **Erik Ochoa (Platzi)** (1)

		
		Para desarrollo no hay problema, pero un ambiente de producción si debería ser algo dinámico fácil de cambiar.

* **Hernan Llull** (1)
Hola, una consulta, no entendi muy bien para que funciona el plugin “proposal-class-properties” de babel.

	* **Erik Ochoa (Platzi)** (1)

		
		Sirve para usar características del lenguaje de Javascript que todavía están sólo como propuestas.
		
		En su descripción dice que:
		
		`This plugin transforms static class properties as well as properties declared with the property initializer syntax`

* **eduardoluisgr** (1)
Yo también uso next js, en el usan plugins como next-images para importar imágenes, etc… ¿estas configuraciones que hemos aprendido hasta...

	* **Erik Ochoa (Platzi)** (2)

		
		Next.js [usa webpack ](https://nextjs.org/blog/next-7#webpack-4)en el fondo y puede ser configurado usando un archivo llamado _[next.config.js](https://nextjs.org/docs#customizing-webpack-config)_ .
		
		Mi recomendación es seguir siempre la forma recomendada en la documentación del framework, en este caso sería redundante usar webpack como un proceso aparte ya que Next.js lo tiene de cierta forma “integrado”.
		
		Espero haya resulto tu duda. 🙂

* **Claudio Jesus Vázquez Villanueva** (1)
Que significa -S Y -E?

	* **Alan Santiago** (4)

		
		 **-S** es una abreviación de **–save** que sirve para guardarlo en _dependencias_ del proyecto.  
		.  
		**-E** es una abreviación de **–save-extact** que sirve para guardar exactamente la versión que quieres, y que cuando alguien más descargue tu proyecto, tenga la misma versión que tú.

## 0230. Configuración básica de producción para Platzi Badges (React.js)

### Descripción:


### Links:

* [GitHub - Sparragus/platzi-badges: Código del proyecto del Curso de React.js de Platzi](https://github.com/Sparragus/platzi-badges)

* [Curso de React.js](https://platzi.com/cursos/react/)

* [clase 23 - Configuración básica de producción para Platzi Badges (Rea… · LeonidasEsteban/webpack-4@03e32af · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/03e32af39eee5e3b9456cfdb65eb3f70c4a2951a)

### Comentarios:

* **Facundo Nicolás García Martoni (Platzi)** (6)

	
	Resumen de la clase
	
	1)) Instalar las siguientes dependencias:
	``` 
	    npm i -D -E mini-css-extract-plugin url-loader
	    
	```
	
	2)) Cambiar “style-loader” por el loader instalado en el paso anterior. Quitar _hotmodules_ para mejorar el rendimiento
	
	3)) Agregar `--static ./dist` al atributo _server_ de los _scripts_ de **package.json**
	
	4)) En el _publicPath_ del _output_ de **webpack.config.js** poner `http://localhost:3001/` (Solo para el entorno local, para hacer deploy se debe cambiar esta configuración)

* **Leonardo Casallas Beltran** (1)

	
	bootstrap tambien lo puedo incluir en el webpack.dll.config.js ?

* **Raúl Martín Anaya Rojo** (1)

	
	¿Por qué `@babel/runtime` no está en las dependencias de desarrollo?

	* **Gabriel De Andrade (Platzi)** (1)

		
		Porque es una dependencia que se va a necesitar para construir la aplicación en producción. Recuerda que las dependencias de desarrollo se dejan por fuera a la hora de construir una app en producción [Curso de Gestión de Dependencias y Paquetes con NPM](https://platzi.com/clases/npm/) 😄

	* **Iván Darío Sánchez Jiménez** (1)

		
		Reemplaza a babel-polyfill y requiere estar compilado en el bundle para interpretar cosas como promesas, metodos estáticos, entre otros.

* **jorgejeal** (1)

	
	No entendi eso del script de server… Alguien me podría explicar a detalle que significa? estoy tratando de crear la base de un proyecto en webpack pero esa parte del server no la entendí y no me funciona… en el caso de github pages, que ruta tendría que colocar en el webpack.config.js (en public path). Agradecería mucho una respuesta lo antes posible…

* **Adrian Garcia Saaib** (1)

	
	por qué en produccion no usamos el hotmodules?

	* **Facundo Nicolás García Martoni (Platzi)** (2)

		
		Me imagino que es porque no tiene utilidad, en producción ya actúa react haciendo render de los componentes que cambian (prácticamente lo mismo que hace hotmodules pero en producción).

	* **Xavier Alexandro Basir Jeffrey** (3)

		
		Cuando ya tienes un sitio en producción no tiendes a estar haciéndole cambios constantemente, de por si el código puede estar tan minificado que sea complicado hacer cambios en el. En fin para además mantener un buen performance no se usa el hotmodules en producción.

* **David Isaac Flores Medrano** (1)
Para hacer deploy a now… cual debe ser la configuración del publicPath ?

## 0240. Configuración óptima de producción para Platzi Badges (React.js)

### Descripción:


 **Dependencias instaladas en clase:**

  * terser-webpack-plugin
  * optimize-css-assets-webpack-plugin
  * clean-webpack-plugin
  * add-asset-html-webpack-plugin



### Links:

* [Curso de React.js](https://platzi.com/cursos/react/)

* [add-asset-html-webpack-plugin  -  npm](https://www.npmjs.com/package/add-asset-html-webpack-plugin)

* [GitHub - webpack-contrib/terser-webpack-plugin: Terser Plugin](https://github.com/webpack-contrib/terser-webpack-plugin)

* [GitHub - NMFR/optimize-css-assets-webpack-plugin: A Webpack plugin to optimize \ minimize CSS assets.](https://github.com/NMFR/optimize-css-assets-webpack-plugin)

* [GitHub - johnagan/clean-webpack-plugin: A webpack plugin to remove your build folder(s) before building](https://github.com/johnagan/clean-webpack-plugin)

* [clase 24 - Configuración óptima de producción para Platzi Badges (Rea… · LeonidasEsteban/webpack-4@b77dc0e · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/b77dc0e137ed11d7681088decc8413804854bc5d)

### Comentarios:

* **heysoypaez** (13)

	
	Para los que no lo sepan:  
	En terminal podemos escribir los comando separados por punto y coma y asi se ejecutará uno después del otro cuando el anterior habrá terminado.
	``` 
	    npm run build:dll ; npm run build ; npm run server
	    
	```
	
	Lo veo más eficiente que estar esperando que terminen los procesos…

	* **Néstor López** (3)

		
		Yo acostumbro usar &&, ejemplo:
		``` 
		    rm -rf node_modules && npm i && npm run build
		    
		```

	* **heysoypaez** (1)

		
		Entiendo que ese operador es mejor porque solo se ejecuta si no hay errores! Pero depende del caso concreto.

* **Iair Poloniecki** (4)

	
	Llego a este punto del curso y recién averiguo que se puede lograr la misma funcionalidad casi sin configuración con Parcel y parece que también con Meteor xD

	* **Manuel Rivera** (2)

		
		jajajaja bro, no conocía sobre Parcel, pero mire algunos videos de como funciona y la verdad hace todo automáticamente a medida que vas necesitando algo, pero la pregunta que tengo es, vale la pena aprender Parcel ? osea me refiero a que React o demas framworks de js no funcionan es con webpack ? Por que si es por evitarnos complicaciones, ese Parcel en lo poco que mire hace todo por ti, instala, transfomar, ejecuta, etc . Es demasiado generoso jaja

* **Facundo Nicolás García Martoni (Platzi)** (4)

	
	Resumen de la clase  
	1)) Instalar la siguiente dependencia. Solo copiar y pegar en la consola:
	``` 
	    npm i -D add-asset-html-webpack-plugin 
	    
	```
	
	2)) En **webpack.config.js** llamar al plugin instalado e instanciarlo con su respectiva configuración:
	``` 
	    constAddAssetHtmlPlugin = require("add-asset-html-webpack-plugin");
	    
	```
	``` 
	    newAddAssetHtmlPlugin({
	          filepath: path.resolve(__dirname, "dist", "js", "*.dll.js"),
	          outputPath: "js",
	          publicPath: "http://localhost:3001/js"
	        })
	    
	```
	
	3)) En el _output_ de **webpack.dll.config.js** colocar lo siguiente:
	``` 
	    output: {
	        path: path.resolve(__dirname, "dist"),
	        filename: "js/[name].[hash].dll.js",
	        library: "[name]"
	      },
	    
	```

* **jgersain** (2)

	
	para que sirve el flag -S cuando instala algo con npm?

	* **jorgejeal** (1)

		
		También tengo la misma duda pero debería significar algo como “–save”

	* **abraham7703 Pimentel** (2)

		
		<https://www.npmjs.com/package/flag?activeTab=readme>
		
		A veces es bueno utilizar Google de vez en cuando.

* **Manuel Rivera** (1)

	
	A partir de webpack 4, si importa el orden de add-assets-webpack-plugin, siempre debe ir después de html-webacp-plugin.

* **Sylvester Josué Rojas Cañón** (1)

	
	Pregunta muchachos,
	
	Es necesario que utilice _resolve_ en esta super configuración, o solo se le debe colocar a un proyecto que maneja extensiones .jsx

* **JuanMonje** (1)

	
	Grande Leonidas

* **David Behar** (1)

	
	Basado en estas sesiones y el create-react-app creé las configuraciones de un boilerplate en React, se los dejo a continuación:  
	<https://github.com/behagoras/react-basic-app>

	* **Iván Darío Sánchez Jiménez** (1)

		
		Se rompió el enlace David

	* **David Behar** (1)

		
		Caray, que raro, a mi si me funciona el link

* **Adrian Garcia Saaib** (1)

	
	Esta configuración es la perfecta?

* **josdanind** (1)
A mi no me cargan las imágenes

	* **Jose Padron (Platzi)** (2)

		
		¿Podrías compartirnos tu código? para ver donde pudo fallar

* **heysoypaez** (1)
¿En qué momento usamos terser-webpack-plugin y para qué lo usamos? Según veo en ningún momento del video se usa. 😦

	* **Erik Ochoa (Platzi)** (1)

		
		Se usa en la siguiente clase para minificar el código Javascript usando [Terser](https://www.npmjs.com/package/terser), un parser/compresor de Javascript alternativo a UglifyJS.

* **edwintrumpet** (1)
A mí no me cargan las imágenes 😦

	* **Manuel Ojeda** (2)

		
		Puedes ayudarnos pasando tu código, así sabremos cual es el problema.
		
		Otra información que nos puede ayudar son los errores que arroja la consola del navegador.

## 0250. Versionando, limpiando y comprimiendo archivos

### Descripción:


### Links:

* [clase 25 - Versionando, limpiando y comprimiendo archivos · LeonidasEsteban/webpack-4@4e65fdb · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/4e65fdb30b414c4a62f93ec0f5e7b9a82bd3d8a2)

### Comentarios:

* **Favio Sauto** (13)

	
	Alrededor del minuto 4:49 hay un corte que salta el video a unos minutos más allá y se pierden algunos pasos, si el error sigue cuando estes viendo este video lo que hace Leonidas es:
	
	  1. Instala el “clean-webpack-plugin” (npm i -D -S clean-webpack-plugin)
	  2. Lo instancia en el archivo webpack.config.js (const { CleanWebpackPlugin } = require(‘clean-webpack-plugin’))
	  3. Instala otros dos plugins que son TerserJSPlugin y Optimize Css Assets Plugin (npm i -D -S terser-webpack-plugin optimize-css-assets-plugin)
	  4. También los instancia en el archivo webpack.config.js (const TerserJSPlugin = require(‘terser-webpack-plugin’) y const OptimizeCSSAssetsPlugin = require(‘optimize-css-assets-plugin’))
	  5. Entre la parte de “output” y “module” dentro de “module.exports” pone esto:
	
	
	``` 
	    optimization: {
	        minimizer: [new TerserJSPlugin(), new OptimizeCSSAssetsPlugin()]
	      },
	    
	```
	
	  1. Y en plugins, esto:
	
	
	``` 
	    newCleanWebpackPlugin({
	          cleanOnceBeforeBuildPatterns: ["**/app.*"]
	        })
	    
	```
	
	Si has seguido el código al pie de la letra en todo el curso, te debería quedar así:
	``` 
	    const path = require("path");
	    const HtmlWebpackPlugin = require("html-webpack-plugin");
	    const MiniCssExtractPlugin = require("mini-css-extract-plugin");
	    const webpack = require("webpack");
	    const AddAssetHtmlPlugin = require("add-asset-html-webpack-plugin");
	    const { CleanWebpackPlugin } = require("clean-webpack-plugin");
	    const TerserJSPlugin = require("terser-webpack-plugin");
	    const OptimizeCSSAssetsPlugin = require("optimize-css-assets-webpack-plugin");
	    
	    module.exports = {
	      entry: {
	        app: path.resolve(__dirname, "src/index.js")
	      },
	      mode: "production",
	      output: {
	        path: path.resolve(__dirname, "dist"),
	        filename: "js/[name].[hash].js",
	        publicPath: "http://localhost:3001/",
	        chunkFilename: "js/[id].[chunkhash].js"
	      },
	      optimization: {
	        minimizer: [new TerserJSPlugin(), new OptimizeCSSAssetsPlugin()]
	      },
	      module: {
	        rules: [
	          {
	            test: /\.js$/,
	            use: "babel-loader",
	            exclude: /node_modules/
	          },
	          {
	            test: /\.css$/,
	            use: [
	              {
	                loader: MiniCssExtractPlugin.loader
	              },
	              "css-loader"
	            ]
	          },
	          {
	            test: /\.jpg|png|gif|woff|eot|ttf|svg|mp4|webm$/,
	            use: {
	              loader: "url-loader",
	              options: {
	                limit: 1000,
	                name: "[hash].[ext]",
	                outputPath: "assets"
	              }
	            }
	          }
	        ]
	      },
	      plugins: [
	        new MiniCssExtractPlugin({
	          filename: "css/[name].[hash].css",
	          chunkFilename: "css/[id].[hash].css"
	        }),
	        new webpack.HotModuleReplacementPlugin(),
	        new HtmlWebpackPlugin({
	          template: path.resolve(__dirname, "public/index.html")
	        }),
	        new webpack.DllReferencePlugin({
	          manifest: require("./modules-manifest.json")
	        }),
	        new AddAssetHtmlPlugin({
	          filepath: path.resolve(__dirname, "dist/js/*.dll.js"),
	          outputPath: "js",
	          publicPath: "http://localhost:3001/js/"
	        }),
	        new CleanWebpackPlugin({
	          cleanOnceBeforeBuildPatterns: ["**/app.*"]
	        })
	      ]
	    };
	    
	    
	```

	* **Favio Sauto** (4)

		
		El terser optimiza y minifca el js mientras que el optimize-css-assets optimiza y minimiza el css

	* **Carlos Martinez** (3)

		
		gracias, solo una cosa, el `HotModuleReplacementPlugin()` se quita ya que react se ocupa de ello, claro, si se está trabajando con react.
		
		Me ayudó mucho tu comentario , saludos

* **Facundo Nicolás García Martoni (Platzi)** (8)

	
	Resumen de la clase
	
	1)) Instalar las siguientes dependencias con la siguiente instrucción:
	``` 
	    npm i -D -E clean-webpack-plugin terser-webpack-plugin optimize-css-assets-webpack-plugin
	    
	```
	
	2)) Agregar lo siguiente al _output_ de **webpack.config.js** :
	``` 
	    name:'[hash].[ext]',
	    outputPath:'assets'
	    
	```
	
	También agregar el template _[hash]_ al objeto MiniCssExtractPlugin:
	``` 
	    newMiniCssExtractPlugin({
	          filename: "css/[name].[hash].css",
	          chunkFilename: "css/[id].[hash].css"
	        }),
	    
	```
	
	3)) Instanciar TerserJSPlugin y OptimizeCSSAssetsPlugin. Agregar después el atributo _optimization_ a **webpack.config.js** con la siguiente configuración:
	``` 
	    const TerserJSPlugin = require("terser-webpack-plugin");
	    const OptimizeCSSAssetsPlugin = require("optimize-css-assets-webpack-plugin");
	    
	```
	``` 
	    optimization: {
	        minimizer: [new TerserJSPlugin(), new OptimizeCSSAssetsPlugin()]
	      },
	    
	```
	
	4)) Instanciar CleanWebpackPlugin, y configurarlo:
	``` 
	    const { CleanWebpackPlugin } = require("clean-webpack-plugin");
	    
	```
	``` 
	    newCleanWebpackPlugin({
	          cleanOnceBeforeBuildPatterns: ["**/app.**"]
	        })
	    
	```

	* **heysoypaez** (3)

		
		Aprecio mucho tus resumenes, el mejor tutorial escrito de la clase, amigo !

* **maria-del-carmen-rodriguez** (7)

	
	DEPENDENCIAS NECESARIAS PARA HACER JALAR PLATZI BADGES  
	webpack  
	webpack-cli  
	webpack-dev-server  
	css-loader PARA PERMITIR IMPORTAR CSS  
	style-loader PARA INYECTAR EL CSS IMPORTADO DENTRO DE JS  
	file-loader PARA PODER IMPORTAR ARCHIVOS MULTIMEDIA E INYECTARLAS, TIENE CONFIGURACIONES COMO DE DONDE SER SERVIRÁN LOS ARCHIVOS ETC  
	babel-loader PARA CONECTAR CON BABEL  
	@babel/core MOTOR DE BABEL  
	@babel/preset-env PRESET POR DEFAULT DE BABEL PARA JAVASCRIPT MODERNO  
	@babel/preset-react PRESET PARA CONFIGURACIÓN POR DEFECTO DE REACT  
	html-webpack-plugin PARA AUTO GENERAR EL HTML CON LAS IMPORTACIONES PERTINENTES  
	DEPENDENCIAS ADICIONALES PARA AÑADIRLE MAS POSIBILIDADES AL DESARROLLO  
	@babel/runtime MODULO DONDE BABEL GUARDA LOS COMMONS  
	@babel/plugin-syntac-dynamic-import PARA PODER HACER IMPORTS DENTRO DE FUNCIONES  
	@babel/plugin-transform-runtime PARA INYECTAR Y EXPORTAR LAS COSAS DE @BABEL/RUNTIME  
	DEPENDENCIAS DE PRODUCCION  
	url-loader PARA INJECTAR LOS ARCHIVOS MULTIMEDIA CONVERTIDOS EN BASE64 EN LOS SRC, TIENE CONFIGURACIONES LA MAS COMÚN ES EL TAMAÑO MINIMO REQUERIDO DEL ARCHIVO  
	mini-css-extract-plugin PARA EXPORTAR EL CSS Y PONERLO EN UN ARCHIVO APARTE DESDE WEBPACK  
	add-asset-html-webpack-plugin PARA AÑADIR POR EJEMPLO REFERENCIAS A SCRPTS EN HTMLWEBPACKPLUGIN  
	clean-webpack-plugin PARA BORRAR LOS ARCHIVOS GENERADOS ANTERIORMENTE  
	optimize-css-assets-webpack-plugin PARA OPTIMIZAR EL CSS YA QUE MINICSSEXTRACTPLUGIN NO LO HACE  
	terser-webpack-plugin PARA OPTIMIZAR MAS EL JS YA QUE EL --MODE PRODUCTION LE HACE FALTA MAS OPTIMIZACION

* **Johan Stivens Suarez Galindo** (3)

	
	Cuando genero el modules.(hash).js con el comando “npm run build:dll” no solo genera el archivo, sino que tambien un txt del mismo nombre con este contenido:
	``` 
	    /*
	    object-assign
	    (c) Sindre Sorhus
	    @license MIT
	    */
	    
	    /**@license React v0.13.3
	     * scheduler.production.min.js
	     *
	     * Copyright (c) Facebook, Inc. and its affiliates.
	     *
	     * This source code is licensed under the MIT license found in the
	     * LICENSE file in the root directory of this source tree.
	     */
	    
	    /**@license React v16.8.3
	     * react-dom.production.min.js
	     *
	     * Copyright (c) Facebook, Inc. and its affiliates.
	     *
	     * This source code is licensed under the MIT license found in the
	     * LICENSE file in the root directory of this source tree.
	     */
	    
	    /**@license React v16.8.3
	     * react.production.min.js
	     *
	     * Copyright (c) Facebook, Inc. and its affiliates.
	     *
	     * This source code is licensed under the MIT license found in the
	     * LICENSE file in the root directory of this source tree.
	     */
	    
	```
	
	Por qué pasa? Hay alguna forma de impedir que se genere?

	* **Pablo Mariano Gonzalez Ocon** (1)

		
		me pasa igual

* **oteka21** (2)

	
	Creo que mejor que usar solo [hash] es mejor utilizar [contenthash] ya que cambia el hash del build solo si el contenido de los archivos cambia

	* **Manuel Rivera** (1)

		
		Exacto, lo recomiendan en la documentación oficial.

* **Alan Santiago** (2)

	
	La clase se corta por el minuto **5:16** 😫

	* **heysoypaez** (1)

		
		al parecer !!!

* **Alfredo Gonzalez** (1)

	
	Solo se genera un bundle de todos mis archivos css?. Es decir que el bundle inicial carga con todos los estilos?, y si tuviese clases con nombres iguales en mis archivos css me generaría un error al renderizar un componente o pagina?

* **Carlos Eduardo Jaramillo Franco** (1)

	
	¿Por qué ya no estamos usando el splitChunks de optimization que aprendimos?

	* **Manuel Rivera** (1)

		
		Por que estamos utilizando dll, hay varias maneras de code plitting.

* **Brayan Murcia Sanchez** (1)

	
	profe Leonidas o compañeros, estoy ingresándole mas estilos al badges, y decidi usar scss para adjuntar diferentes archivos, pero no encuentro un loader que me funcione, y siempre me indica este error
	``` 
	    ./src/styles/scss/index.scss 1:0
	    Module parse failed: Unexpected character'@' (1:0)
	    You may need an appropriate loader to handle this file type, currently no loaders are configured toprocess this file. See https://webpack.js.org/concepts#loaders
	    
	    
	```
	
	y mi webpack.config.js
	``` 
	    const path = require('path')
	    const HtmlWebpackPlugin = require('html-webpack-plugin')
	    const MiniCssExtractPlugin = require('mini-css-extract-plugin')
	    const webpack = require('webpack')
	    const AddAssetHtmlPlugin = require('add-asset-html-webpack-plugin')
	    var ExtractTextPlugin = require('extract-text-webpack-plugin')
	    const extractCSS = new ExtractTextPlugin('css/styles.css')
	    
	    module.exports = {
	      entry: {
	        app: path.resolve(__dirname, 'src/index.js')
	      },
	      output: {
	        path: path.resolve(__dirname, 'dist'),
	        filename: 'js/[name].js',
	        publicPath: 'dist/',
	        chunkFilename: 'js/[id].[chunkhash].js'
	      },
	      module: {
	        rules: [
	          {
	            test: /\.js$/,
	            exclude: /node_modules/,
	            use: {
	              loader: 'babel-loader',
	              options: {
	                presets: ['@babel/preset-env', '@babel/preset-react']
	              }
	            }
	          },
	          {
	            test: /\.css$/,
	            use: [
	              {
	                loader: MiniCssExtractPlugin.loader
	              },
	              'css-loader'
	            ]
	          },
	          {
	            test: /\.scss$/,
	            use: extractCSS.extract({ use: ['css-loader', 'sass-loader'] })
	          },
	          {
	            test: /\.styl$/,
	            use: extractCSS.extract({ use: ['css-loader', 'stylus-loader'] })
	          },
	          {
	            test: /\.jpg|png|gif|woff|eot|ttf|svg|mp4|webm$/,
	            use: {
	              loader: 'url-loader',
	              options: {
	                limit: 1000
	              }
	            }
	          }
	        ]
	      },
	      plugins: [
	        new MiniCssExtractPlugin({
	          filename: 'css/[name].css',
	          chunkFilename: 'css/[id].css'
	        }),
	        new HtmlWebpackPlugin({
	          template: path.resolve(__dirname, 'public/index.html')
	        }),
	        new webpack.DllReferencePlugin({
	          manifest: require('./modules-manifest.json')
	        }),
	        new AddAssetHtmlPlugin({
	          filepath: path.resolve(__dirname, 'dist/js/*.dll.js'),
	          outputPath: 'js',
	          publicPath: 'http://localhost:3001/js'
	        })
	      ]
	    }
	    
	```

	* **David Vargas Domínguez** (2)

		
		Podría ser que te olvidaste instalar sass-loader y node-sass para que funcione con los archivos scss/sass. Revisa tus dependencias ^^’

* **Matias Niz** (1)

	
	La clase esta incompleta? o me parece?..

* **Armando de jesus santiz lopez** (1)
Genial Leónidas

* **Casitron12** (1)

	
	En el minuto 5:02
	
	Leonidas habia puesto new TersetJSPlugin()  
	Se supone que es Terser

* **Adrian Garcia Saaib** (1)

	
	Ya teniendo esto, asi lo puedo subir a github? solo cambiando las publicPath por la url de mi githubpage?  
	tendre que subir solo el dist

	* **Facundo Nicolás García Martoni (Platzi)** (1)

		
		Tengo la misma duda, te funcionó así? 🤔

	* **Daniel H. Guissepe** (1)

		
		Hay un procedimiento especial para hacer deployment de apps de react en gh-pages. Aquí hay un listado <https://facebook.github.io/create-react-app/docs/deployment>. Pero es la documentación de create-react-app. Si buscas en dicho enlace “GitHub Pages” te explican como hacerlo habiendo hecho la app con create-react-app, pero debe ser similar para un caso a pie como es webpack. Por lo menos te sirve de referencia y puedes indagar un poco más en internet 😃 yo también seguiré ese camino cuando complete este curso, pero por ahora tengo entendido que hay que usar una dependencia.

	* **Alan Santiago** (1)

		
		Efectivamente, en la documentación de react y el deploy lo puedes ver 🤠

	* **santiagobarrios** (1)

		
		<https://platzi.com/tutoriales/1548-react/4065-guia-para-usar-github-pages-en-tus-proyectos-de-reactjs/>

* **Luis Carlos Carrillo Tovar** (1)

	
	Para instalar Optimize Css Assets plugin se hace con el comando npm install -D -S optimize-css-assets-webpack-plugin

* **bewe** (1)
¿Porqué al darle F5 en badges y badges/new da error, como si dejara de funcionar react-router-dom ? error /GET /badges/new 404

* **danielfernando** (1)
como podria hacer para que tambien elimine los archivos que empiezen con modules con el plugin CleanWebpackPlugin

	* **Jessie Buckland Pérez** (1)

		
		En teoria con añadir en webpack.config.js el siguiente código:
		``` 
		    newCleanWebpackPlugin({
		    	cleanOnceBeforeBuildPatterns:['**/app.*', '**/modules.*']
		    })
		    
		```
		
		De esta manera consigues que ademas de los app en las carpetas con el hash y su extensión también se borren los modules.
		
		¿Porqué quieres eliminar estos archivos?, pruébalo y cualquier otra duda me comentas, ¿ok? Saludos.

* **brayaninchea** (1)
cuando lo compilo con sass en desarrollo, no me genera un archivo .css en la carpeta dist/

	* **AlexGarrixen** (3)

		
		Hola brayaninchea,recuerda que no se genera porque solo esto sucede cuando hagamos el build para producción, en desarrollo solo se inyectan los estilos

## 0260. Setup de Platzi Rooms

### Descripción:


### Links:

* [GitHub - platzi/VUEJSAvanzado: Repo del curso de VUEJSAvanzado](https://github.com/platzi/VUEJSAvanzado)

* [clase 26 - setup de platzi rooms · LeonidasEsteban/webpack-4@26e233b · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/26e233b13893dd79c4479d30da80d429820260e9)

### Comentarios:

* **Raúl Martín Anaya Rojo** (2)

	
	Eso que hizo Leonidas para agregar cursor de acuerdo a la selección se logra con **Ctrl + D**
	
	Más trucos de visual studio code, aquí  
	<https://code.visualstudio.com/docs/getstarted/tips-and-tricks>

* **Jorge Palacios** (2)

	
	–save-exact nunca lo había escuchado, yo usaba el @

	* **JerezA** (4)

		
		lo hizo absolutamente todas las clases hehe, mas bien yo no conocia el metodo con @

* **Raúl Martín Anaya Rojo** (1)

	
	El proyecto no me funcionaba, hasta que la dependencia de **vue** y la de **vue/template-compiler** las deje con la misma versión. Es decir **vue@2.5.22** y **vue-template-compiler@2.5.22**

* **FizIrvin** (1)

	
	para evitar que no me salga aquí mismo “en vivo”

* **Andrés Felipe Cano Sierra** (1)
No he podido pasar del npm install Tengo el siguiente código de error: grpc@1.20.0 install: `node-pre-gyp install --fa...

	* **Jessie Buckland Pérez** (1)

		
		Buenas Andrés, por experiencia creo que tiene relación con firebase, no conozco en detalle el curso de vuejs ya que no lo he realizado, pero seguramente si actualizas tu version de firebase a la 7.7.0 podrás hacer el install correctamente. Cuéntame si te ha servido el tip, Un saludo!!

## 0270. Configuración de desarrollo para Platzi Rooms (Vue.js)

### Descripción:


### Links:

* [GitHub - platzi/VUEJSAvanzado: Repo del curso de VUEJSAvanzado](https://github.com/platzi/VUEJSAvanzado)

* [clase 27 - configuración de desarrollo para platzi rooms · LeonidasEsteban/webpack-4@9c77a2b · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/9c77a2b52d091bce9647145eee11bdabd9ac84bb)

### Comentarios:

* **memowii** (14)

	
	Aporto un código que ya tiene las versiones de la dependencia:
	``` 
	    npm i -D -E @babel/core@7.4.5 @vue/cli-plugin-eslint@3.4.0 @babel/plugin-proposal-class-properties@7.4.4 @vue/cli-service@3.4.0 @babel/plugin-syntax-dynamic-import@7.2.0 @vue/eslint-config-airbnb@4.0.0 @babel/preset-env@7.4.5 babel-eslint@10.0.1 @vue/babel-preset-app@3.8.0 eslint@5.8.0 add-asset-html-webpack-plugin@3.1.3 eslint-plugin-vue@5.0.0 autoprefixer@9.6.0 babel-loader@8.0.6 clean-webpack-plugin@3.0.0 css-loader@2.1.1file-loader@4.0.0 html-webpack-plugin@3.2.0 optimize-css-assets-webpack-plugin@5.0.1 postcss-import@12.0.1 postcss-import@12.0.1 postcss-loader@3.0.0 style-loader@0.23.1 tailwindcss@0.7.4 tailwindcss@0.7.4 vue-template-compiler@2.5.22 terser-webpack-plugin@1.3.0 url-loader@2.0.0 vue-loader@15.7.0 vue-template-compiler@2.6.10 webpack@4.33.0 webpack-cli@3.3.2 webpack-dev-server@3.6.0
	    
	```

	* **Ludwing Juan Homero Pérez Tzaquitzal** (1)

		
		Gracias amigo! Eres grande!

	* **Juan José Vega Quintero** (1)

		
		Gente que le pone el alma

* **Facundo Nicolás García Martoni (Platzi)** (13)

	
	Sentencia para instalar las dependencias usadas. Copiar y pegar en consola:
	``` 
	    npm i -D -E @babel/core @babel/plugin-proposal-class-properties @babel/plugin-syntax-dynamic-import @babel/preset-env add-asset-html-webpack-plugin babel-loader clean-webpack-plugin css-loader file-loader html-webpack-plugin optimize-css-assets-webpack-plugin style-loader terser-webpack-plugin url-loader webpack webpack-cli webpack-dev-server tailwindcss vue-template-compiler postcss-loader autoprefixer postcss-import @vue/babel-preset-app vue-loader
	    
	```

* **neontigermx** (6)

	
	No tengo idea que pasó, pero no me arrancaba el proyecto, tuve que instalar lo siguiente:  
	npm i -D -E core-js regenerator-runtime

* **Ludwing Juan Homero Pérez Tzaquitzal** (2)

	
	La forma de configuración de webpack en vue ahora se hace por medio de un archivo que se llama vue.config.js A mi personalmente no me gusta porque siento que complica un poco la configuración de webpack que uno ya conoce, pero bueno, fue decisión del equipo de vue y ni modo. Pero igual es bueno saber configurar webpack para vue como lo enseñó Leonidas.

* **Andrés Felipe Cano Sierra** (2)
npm install --save --save-exact @babel/core @babel/plugin-proposal-class-properties @babel/plugin-syntax-dynamic-import @babel/pres...

* **Fides Gerardo Escalona Molina** (1)

	
	Si terminaste la clase y no te funciona la app, prueba copiando el código que encuentras aquí abajo, reemplazas todo el package.json que se encuentra dentro de la carpeta platzi-rooms y ejecutas “npm install” en el terminal, y después “npm run build:dev”, a mi me funcionó
	``` 
	    {
	      "name": "platzi-rooms",
	      "version": "0.1.0",
	      "private": true,
	      "scripts": {
	        "serve": "vue-cli-service serve",
	        "build": "vue-cli-service build",
	        "lint": "vue-cli-service lint",
	        "build:dev": "webpack-dev-server --config ./webpack.dev.config.js"
	      },
	      "dependencies": {
	        "firebase": "5.8.3",
	        "tiny-slider": "2.9.1",
	        "vue": "2.6.10",
	        "vue-router": "3.0.1",
	        "vuex": "3.0.1"
	      },
	      "devDependencies": {
	        "@babel/core": "7.4.5",
	        "@babel/plugin-proposal-class-properties": "7.4.4",
	        "@babel/plugin-syntax-dynamic-import": "7.2.0",
	        "@babel/preset-env": "7.4.5",
	        "@vue/babel-preset-app": "3.8.0",
	        "add-asset-html-webpack-plugin": "3.1.3",
	        "autoprefixer": "9.6.0",
	        "babel-loader": "8.0.6",
	        "clean-webpack-plugin": "3.0.0",
	        "css-loader": "2.1.1",
	        "file-loader": "4.0.0",
	        "html-webpack-plugin": "3.2.0",
	        "optimize-css-assets-webpack-plugin": "5.0.1",
	        "postcss-import": "12.0.1",
	        "postcss-loader": "3.0.0",
	        "style-loader": "0.23.1",
	        "tailwindcss": "0.7.4",
	        "terser-webpack-plugin": "1.3.0",
	        "url-loader": "2.0.0",
	        "vue-loader": "15.7.0",
	        "vue-template-compiler": "2.6.10",
	        "webpack": "4.33.0",
	        "webpack-cli": "3.3.2",
	        "webpack-dev-server": "3.6.0"
	      }
	    }
	    
	```

* **Juan José Vega Quintero** (1)

	
	Tengo problemas con firebase
	``` 
	    ERRORin ./src/main.js
	    Modulenot found: Error: Can't resolve 'firebase' in '/mnt/c/Users/juanj/Desktop/Platzi/2020/Webpack/code/platzi-rooms/src'
	    
	```
	
	Alguien tiene una solución?

* **jhon manuel angulo moncada** (1)

	
	usen las versiones de las dependencias del curso, no funciona con las nuevas =(

* **SOFTDYNAMIC** (1)
A qué se debe estos errores ?

	* **davidtoca (Platzi)** (2)

		
		Es por tu editor, hay un caracter invisible que se usa para separa las lineas que deberia ser CRLF pero tu editor esta poniendo LF <https://es.wikipedia.org/wiki/CRLF>, que editor estas usando? usa un editor como atom o visual studio para no tener estos problemas

## 0280. Configuración de producción para Platzi Rooms (Vue.js)

### Descripción:


### Links:

* [GitHub - platzi/VUEJSAvanzado: Repo del curso de VUEJSAvanzado](https://github.com/platzi/VUEJSAvanzado)

* [clase 28 - configuración de produción para platzi-rooms · LeonidasEsteban/webpack-4@df718b6 · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/df718b61c7943fdbabb056e07bc1d072de1c1fb2)

### Comentarios:

* **Alexander Henry Obispo Buendia** (7)

	
	Si desean pueden generar un servidor con express.
	``` 
	    npm i -S express
	    
	```
	
	crea un archivo server.js (al mismo nivel que package.json y webpack.config,js) e introduce la siguiente configuración.
	``` 
	    const express = require(‘express’)
	    const port = process.env.PORT || 8080
	    constapp = express()
	    
	    app.use(express.static(__dirname + “/dist/”))
	    
	    app.get(/.*/, (req, res) => {
	    res.sendFile(__dirname, + “/dist/index.html”)
	    });
	    
	    app.listen(port, () => {
	    console.log(Platzi rooms listening on port ${port}!)
	    })
	    
	```
	
	y en tu package.json
	``` 
	    “start”: “nodeserver.js”,
	    
	```
	
	y listo en tu consola
	``` 
	    npm start
	    
	```
	
	espera el mensaje y abre <http://localhost:8080> 😃

	* **SOFTDYNAMIC** (1)

		
		Excelente

	* **JarlLuis** (1)

		
		Gracias por el aporte!!!

* **Facundo Nicolás García Martoni (Platzi)** (3)

	
	Para los que no les funcione el **http-server** , hagan lo siguiente:
	
	1)) En su **package.json** , dentro de las _devDependencies_ , pongan lo siguiente:
	``` 
	    "@vue/cli-service": "^3.4.0",
	    
	```
	
	2)) En el comando _start_ , lo siguiente:
	``` 
	    "start": "vue-cli-service serve",
	    
	```
	
	3)) Corran _npm install_ para instalar esta dependencia:
	``` 
	    npm install
	    
	```
	
	4)) Los _publicPath_ del **webpack.config.js** deben quedar así:
	``` 
	    output: {
	        path: path.resolve(__dirname, "dist"),
	        filename: "js/[name].[hash].js",
	        publicPath: "dist",
	        chunkFilename: "js/[id].[chunkhash].js"
	      },
	    
	```
	``` 
	    newAddAssetHtmlPlugin({
	          filepath: path.resolve(__dirname, "dist", "js", "*.dll.js"),
	          outputPath: "js",
	          publicPath: "js"
	        }),
	    
	```
	
	5)) Hagan _build_ y corran el servidor, y problema solucionado 😉
	``` 
	    npm run build
	    npm start
	    
	```

* **maria-del-carmen-rodriguez** (2)

	
	con poner ./ en el publicPath me funciono

* **jcknight77** (2)

	
	Para los que no les funcione correctamente el comando npm run start, se debe modificar el archivo **package.json** en la sección _devDependencies_ y modificar la línea del **http-server** así:
	``` 
	    "http-server": "0.9.0",
	    
	```
	
	Ejecutar:
	``` 
	    npm install
	    
	```
	
	Finalmente:
	``` 
	    npm run start
	    
	```

* **Luis Jeanpier Monserrate** (1)

	
	si no les funciona el comando npm start; prueben instalando http-server globalmente con : “npm i -g http-server”. A mi me funcionó; esto es en caso de que npm no les reconozca el comando http-server dist

* **brayaninchea** (1)

	
	Luego de instalar “http-server”, no me carga la pagina, ejecutando npm run start

* **Adrian Garcia Saaib** (1)

	
	Odio los syntax errors D:

## 0290. Despedida del curso

### Descripción:


¡Felicitaciones! has llegado al final, ya sabes como configurar Webpack para cualquier proyecto basado en Javascript y así ahorrarte un montón de tiempo a ti y a tú equipo. Te invitamos a tomar los demás cursos que tenemos para ti, como el [Curso de React.js](https://platzi.com/clases/jquery-js/) o el [Curso Avanzado de Vue.js](https://platzi.com/clases/vuejs-avanzado/) y Firebase por Bedu.

Recuerda que hay una infinidad de **loaders** y **plugins** que expanden las funciones de Webpack, sigue investigando por tu cuenta para que puedes aprovechar aún más está increíble herramienta.

No olvides aprobar el examen y **¡Nunca pares de aprender!**

### Links:

* [clase 29 - despedida · LeonidasEsteban/webpack-4@677f53a · GitHub](https://github.com/LeonidasEsteban/webpack-4/commit/677f53a1c24bc2ca1b9cd7ac0719485c95e04703)

### Comentarios:

* **Ludwing Juan Homero Pérez Tzaquitzal** (5)

	
	Gran curso! Es muy aclarativo el curso, siempre usé webpack pero nunca entendí qué hacía, ahora ya no me da miedo tocar el webpack.config.
	
	Gracias Leonidas! Eres un gran profesor!!

* **Enrique Devars (Platzi)** (5)

	
	jajajajaja el Barto
	
	![elBarto](https://vignette.wikia.nocookie.net/simpsons/images/0/06/IMG_1653.PNG/revision/latest?cb=20170101022958)

	* **Ernesto Vizcaíno Alvarado** (1)

		
		jajajaja

* **jackelinejaimesortiz1** (4)

	
	Team React!!!

* **Alvaro Garracini** (4)

	
	React!

* **Miguel Angel Martelo Quiroz** (4)

	
	React!!!

* **jose ortiz** (4)

	
	Team React 😃

* **jhon manuel angulo moncada** (3)

	
	React…!

* **ojblanco** (3)

	
	React

* **Camilo Rivera Quintero** (3)

	
	React

* **Xavier Alexandro Basir Jeffrey** (3)

	
	Team Vue.js💚

* **Northerchild** (2)

	
	Ay yo amo los dos, aguante VUE Y REACT!

* **Manuel Rivera** (2)

	
	Team azucar sintética (jsx segun el profesor Richard del curso de React ) Team React ajajja

* **Ivan Joseph** (2)

	
	React y Vue son muy buenos, React te deja manejar el ciclo de vida del componente y hacer las cosas de forma más estructurada. Prefiero cualquiera a Angular. (opinión personal).

* **josegts** (2)

	
	team React!

* **Ludwing Juan Homero Pérez Tzaquitzal** (2)

	
	Vue 100% hasta la muerte!!

* **SOFTDYNAMIC** (2)

	
	Both

* **robertosalgado** (2)

	
	Team Vue

* **memowii** (2)

	
	React!!!

* **Sabrina Valerio Hidalgo** (2)

	
	Team React 💙✊🏻

* **Alexander Henry Obispo Buendia** (2)

	
	Team React y Vue :v me gustan los 2 xd

* **Ernesto Vizcaíno Alvarado** (2)

	
	Team React

* **Javier Armando Vargas Vega** (1)

	
	Hasta ahora he visto algo de React. Estoy aprendiendo.
	
	Nada de Vue.
	
	Veremos a ver cuál me gusta más.  
	Por lo demás muy buen Curso. Algo complicado me parecieron las configuraciones de los proyectos de react y vue. Pero creo que será practicando mucho para entender bien el tema.

* **Johan Stivens Suarez Galindo** (1)

	
	Team React papu! Gracias Leonidas! Aprendí mucho con este curso!

* **Iván Darío Sánchez Jiménez** (1)

	```
	    while(true){
	    	console.log('Team React')
	    }
	    
	```

* **Jemd** (1)

	
	Team React ⚛

* **Elias Ojeda Medina** (1)

	
	Muy buen curso, @Leonidas, has mejorado bastante la forma en que enseñas y das los cursos

* **Jessie Buckland Pérez** (1)

	
	Team show me the vanguard tech 😄

* **Anthony Farias** (1)

	
	Team react. Odio escribir código HTML. Larga vida al JSX xD

* **Ricardo Medina** (1)

	
	Muy buen curso, a la altura del sensei Leonidad! con respecto a vue a react, me gustan ambos :p

* **JerezA** (1)

	
	Team React 4eva!

* **Erick Sánchez Noguerón** (1)

	
	Excelente curso, como todos los impartidos por Leonidas.

* **Diego Ivan Padilla Bernal** (1)

	
	Team React

* **Xavier Alexandro Basir Jeffrey** (1)

	
	Soy el único que ha usado Vue más no React? tendré que echarle un ojo a los cursos de react a ver que tal

	* **Ludwing Juan Homero Pérez Tzaquitzal** (1)

		
		Ya somos dos!

* **Facundo Nicolás García Martoni (Platzi)** (1)

	
	Espectacular curso Leonidas!

* **Adrian Garcia Saaib** (1)

	
	A mi me gusta React porque no he usado Vue! ✔🤷‍♂️🛥🏊‍♂️🚣‍♂️😁😥😂📝😥

	* **Alan Santiago** (2)

		
		 **Vue** también es muy fancy 🤓

	* **David Behar** (1)

		
		Es lo mismo que yo pensé

* **raulaallendep** (1)
Hola, tengo un archivo de configuracion que contiene el HOST, PORT y otras variables de entorno de mi aplicacion. Este archivo lo requier...

	* **Guido Cavallo** (1)

		
		porque no usas la librería [dotenv ](https://www.npmjs.com/package/dotenv)para manejar las variables de entorno.
		
		Te creas un archivo .env y ahí configuras todas variables, ese archivo es portable y no tienes que configurar variables en el sistema operativo.

