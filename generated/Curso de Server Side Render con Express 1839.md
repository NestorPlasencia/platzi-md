[Curso de Server Side Render con Express 1839](https://platzi.com/cursos/ssr)

# Conocimientos necesarios para aplicar SSR [5380]

## 0010. Introducción al curso [26460](https://platzi.com/clases/1839-ssr/26460-introduccion-al-curso/)

### Descripción:


### Links:

* [React – A JavaScript library for building user interfaces](https://reactjs.org/)

* [Babel · The compiler for next generation JavaScript](https://babeljs.io/)

* [Express - Node.js web application framework](https://expressjs.com/)

### Comentarios:

* **Gerardo Nava Pereda** (4) [1011457](https://platzi.com/comentario/1011457/) 

	Excelente! Qué bien que lo remasterizaron este curso!
	
	## Isomorphic | Universal | SSR
	
	[React Redux Universal Hot Example](https://github.com/erikras/react-redux-universal-hot-example)

	* **sampol.90 (Platzi)** [1011457] (2)

		Cualquier duda estaré para ayudarte 🤘🏼

* **rafaelsalass (Platzi)** (2) [1018520](https://platzi.com/comentario/1018520/) 

	Hola 😄

* **Ignacio_Damanes** (2) [1014726](https://platzi.com/comentario/1014726/) 

	POR QUE SIEMPRE QUE SACAN UN CURSO LO PONEN AL PRINCIPIO DE LA ESCUELA DE JS?
	
	Al contrario el otro dia sacaron uno de js basico y lo pusieron al principio.  
	Solo genera dudas.
	
	Buen curso y profesor, saludos

* **ValentinGutierrez** (1) [1022911](https://platzi.com/comentario/1022911/) 

	Jajaja estaba por terminar la carrera y me sacan un curso nuevo >:V

* **Ignacio_Damanes** (1) [82891](https://platzi.com/comentario/1014727/) 
POR QUE SIEMPRE QUE SACAN UN CURSO LO PONEN AL PRINCIPIO DE LA ESCUELA DE JS? Al contrario el otro dia sacaron uno de js basico y lo pusi...

	* **hdmjesus** [82891] (1)

		X2

## 0020. Presentación del proyecto del curso y sus herramientas [26461](https://platzi.com/clases/1839-ssr/26461-presentacion-del-proyecto-del-curso-y-sus-herramie/)

### Descripción:


### Comentarios:

* **jw_caceres** (1) [1016675](https://platzi.com/comentario/1016675/) 

	Hasta el momento vamos bien, está interesante lo que se plantéa como contenido… un punto de mejora: está un poco complicado descargar los archivos requeridos para el curso, sería genial que lo suban como un ZIP

	* **sampol.90 (Platzi)** [1016675] (2)

		Puedes hacer pull del repo o un fork 🤔

	* **Gabriel De Andrade (Platzi)** [1016675] (1)

		Si vas a la sección de enlaces también puedes darle a descargar todo y te lo descarga como un .zip 😄

* **devops** (1) [1015260](https://platzi.com/comentario/1015260/) 

	MUY BUENO EL CURSO

## 0030. ¿Qué es Server Side Rendering [26462](https://platzi.com/clases/1839-ssr/26462-que-es-server-side-rendering/)

### Descripción:


### Comentarios:

* **Gerardo Nava Pereda** (3) [1014238](https://platzi.com/comentario/1014238/) 

	## Ventajas del SSR
	
	* Primera carga más rápida
	* Mejor SEO
	* Look & Feel
	* Mejor UX
	
	

* **pabloverduzcos** (3) [1012746](https://platzi.com/comentario/1012746/) 

	Entonces a grandes rasgos, hacer **SSR** nos permite hacer tareas en paralelo, que en este caso es hidratar el cliente con HTML en lo que se descarga el **bundle** de nuestra aplicación ¿cierto?

	* **sampol.90 (Platzi)** [1012746] (2)

		Así es

* **Jean Carlos Nuñez Hernandez** (2) [1011685](https://platzi.com/comentario/1011685/) 

	Client Side Rendering CSR

# Preparando entorno para aplicar SSR [5381]

## 0040. Actualizando dependencias en NPM [26463](https://platzi.com/clases/1839-ssr/26463-actualizando-dependencias-en-npm/)

### Descripción:


### Comentarios:

* **Jean Carlos Nuñez Hernandez** (4) [1011719](https://platzi.com/comentario/1011719/) 

	npm outdated para ver las librerias que debe ser actualizadas

* **nca1478** (1) [1117029](https://platzi.com/comentario/1117029/) 

	Resumen de la clase:
	
	  1. Buscamos un proyecto que contenga react, react-router y redux.
	
	  2. Creamos una nueva rama del proyecto con:  
	git checkout -b nombre_rama
	
	  3. Verificar las ramas que hay que actualizar: npm outdated
	
	  4. Para actualizar la aplicación ingresamos: npm update
	
	  5. Para verificar si hubo actualización de paquetes, lo hacemos con: git status
	
	  6. Para verificar las dependencias actualizadas, ingresamos: git diff
	
	  7. Volvemos a verificar las dependencias que tenemos que actualizar con: git outdated
	
	  8. Hay dependencias que no se pueden actualizar directamente con el comando git update, porque estas dependencias tienen otras dependencias que pueden estar siendo utilizadas por otras dependencias.
	
	  9. Corremos la aplicación (npm run start) para verificar que todavia funciona la aplicación y que el proceso de actualización de dependencias se realizó exitosamente.
	
	
	

* **devops** (1) [1015293](https://platzi.com/comentario/1015293/) 

	favor de especificar? estas utilizando linux? y que version y que estan instalando???

	* **sampol.90 (Platzi)** [1015293] (1)

		Se esta usando MacOSX, pero no deberia cambiar mucho en Linux la instalación y actualización de dependencias.

* **Gerardo Nava Pereda** (1) [1014284](https://platzi.com/comentario/1014284/) 

	```
	    npm outdated
	    npm update
	    
	```

* **José Manuel Puicón Rodas** (1) [1014014](https://platzi.com/comentario/1014014/) 

	npm update --> Para actualizar las librerías 😃

## 0050. Creación del servidor en Express [26464](https://platzi.com/clases/1839-ssr/26464-creacion-del-servidor-en-express/)

### Descripción:


### Comentarios:

* **Daniel Hernández** (2) [1036807](https://platzi.com/comentario/1036807/) 

	```
	    npm i @babel/register -D 
	    
	```
	
	o
	``` 
	    npm install @babel/register--save-dev
	    
	```
	
	las 2 formas son lo mismo

* **nca1478** (1) [1117156](https://platzi.com/comentario/1117156/) 

	Resumen de la Clase
	
	  1. Creamos 2 carpetas dentro de la carpeta src, src/server: fuentes con toda la lógica relacionada con el servidor src/frontend: fuentes con toda la lógica relacionada con la app.
	
	  2. Movemos todos los archivos de nuestra app en react ubicada actualmente en la carpeta src, hacia src/frontend.
	
	  3. Creamos en la carpeta src/server 2 archivos, index.js y server.js.
	
	  4. Instalamos la siguiente dependencia: npm install @babel/register
	
	  5. En el archivo src/server/index.js, agregamos la siguiente configuración:  
	require(’@babel/register’)({  
	presets: [’@babel/preset-env’, ‘@babel/preset-react’],  
	})  
	require(’./server’)
	
	  6. Instalamos más dependencias: npm install express dotenv.
	
	  7. Express sirve para poder instalar nuestro servidor local y dotenv se utiliza para manejar nuestras variables de entorno.
	
	  8. Agregamos todo el código necesario para correr el servidor de express en el archivo src/server/server.js.
	
	  9. Creamos un nuevo script en el archivo package.json, para poder ejecutar nuestro servidor:  
	“scripts”: { “start:dev” : “node src/server/index” }
	
	  10. Ejecutamos nuestro servidor desde la consola con:  
	npm run start:dev.
	
	  11. Desde el navegador de Google Chrome, ingremos a la dirección 127.0.0.1:3000 o localhost:3000 para verificar que esta funcionando nuestro servidor de express.
	
	
	

* **Eden Gomez Gress** (1) [1057726](https://platzi.com/comentario/1057726/) 

	Buen dia companeros, cuando trato de ejecutar el comando " npm run start:dev" me sale este error
	``` 
	    Error: Cannot find module'@babel/preset-presets-env'from'/Users/eden/Desktop/platzi/server-side-express/PlatziVideo2/PlatziVideo2'
	    
	```
	
	Alguien sabe a que se debe?

	* **sampol.90 (Platzi)** [1057726] (2)

		Es por que estas llamando al paquete mal.
		
		Tienes: @babel/preset-presets-env  
		Es: @babel/preset-env
		
		Saludos!

	* **Eden Gomez Gress** [1057726] (1)

		En donde tengo que modificar el llamado de ese modulo?

	* **sampol.90 (Platzi)** [1057726] (2)

		Se usa en dos lados:
		
		  1. En tu .babelrc en el root del proyecto
		  2. En el index.js que esta dentro de la carpeta server
		
		

	* **Eden Gomez Gress** [1057726] (2)

		Gracias profesor ya arregle el problema. fue un typo dentro del archivo index.js dentro de la carpeta “server”

* **Daniel Hernández** (1) [1036827](https://platzi.com/comentario/1036827/) 

	otra manera de escribirlo…
	``` 
	    app.listen(3000, (error) => {
	      error ? console.log(error) : console.log('Server running on 3000 port');
	    });
	    
	```

## 0060. Usando Nodemon y Dotenv [26465](https://platzi.com/clases/1839-ssr/26465-usando-nodemon-y-dotenv/)

### Descripción:


### Links:

* [Page not found · GitHub · GitHub](https://github.com/PlatziDev/Frontend/blob/master/bundles/development-bundles.js)

### Comentarios:

* **Alver Ortega** (4) [1030589](https://platzi.com/comentario/1030589/) 

	Mi aporte:
	
	Crear un archivo index.js en una carpeta nueva llamada config dentro de server
	``` 
	    import dotenv from 'dotenv';
	    
	    dotenv.config();
	    
	    const { ENV, PORT } = process.env;
	    
	    exportdefault {
	        env: ENV,
	        port: PORT,
	    }
	    
	```
	
	y en server.js solo llamo esa configuración
	``` 
	    import express from 'express';
	    
	    import config from './config';
	    
	    const { env, port } = config;
	    
	    const app = express();
	    if (env === 'development') {
	        console.log(env);
	    }
	    
	    app.get('*', (req, res) => {
	        console.log('hola man')
	        res.send({ hello: 'express'}).end();
	    });
	    
	    
	    app.listen(port, (err) => {
	        if (err) console.log(err);
	        else console.log(`Server running on port ${port}`);
	    });
	    
	```

	* **sampol.90 (Platzi)** [1030589] (1)

		Excelente aporte, de hecho usarlo asi es la manera mas limpia porque solo lo defines una vez.

	* **Alver Ortega** [1030589] (1)

		si es una buena manera de modularizar las cosas

* **José Manuel Puicón Rodas** (2) [1014097](https://platzi.com/comentario/1014097/) 

	console.log(`server running in mode ${ENV} on port ${PORT}`);

## 0070. Integración de Webpack con Express [26466](https://platzi.com/clases/1839-ssr/26466-integracion-de-webpack-con-express/)

### Descripción:


### Links:

* [GitHub - webpack/webpack-dev-middleware: A development middleware for webpack](https://github.com/webpack/webpack-dev-middleware)

* [GitHub - webpack-contrib/webpack-hot-middleware: Webpack hot reloading you can attach to your own server](https://github.com/webpack-contrib/webpack-hot-middleware)

* [GitHub - gaearon/react-hot-loader: Tweak React components in real time.](https://github.com/gaearon/react-hot-loader)

* [Curso de Webpack | Platzi](https://platzi.com/clases/webpack/)

### Comentarios:

* **JUAN SILVA** (2) [1018593](https://platzi.com/comentario/1018593/) 

	npm install webpack-dev-middleware webpack-hot-middleware --dev

* **José Manuel Puicón Rodas** (2) [1014147](https://platzi.com/comentario/1014147/) 

	Si tienen un error parecido a este:
	``` 
	    Cannot find module 'react-hot-loader/babel
	    
	```
	
	Instalen de la siguiente manera:
	``` 
	    npm install react-hot-loader --save-dev
	    
	```

* **Enrique Devars (Platzi)** (2) [1012535](https://platzi.com/comentario/1012535/) 

	Si su caso es como el mio que están haciendo este curso con otro proyecto de React, y sus archivos de react termina en **.js** , y no les funciona el Hot Reloading es porque Nodemon reinicia el servidor de Webpack que implementamos con Express cada vez que se modifica un archivo de Javascript.
	
	Para solucionar esto solo debemos modificar nuestro script de desarrollo ignorando nuestra carpeta de Frontend.en nuestro package.json
	``` 
	    "start:dev": "nodemon --ignore './src/Frontend/' src/server/index.js"
	    
	```
	
	Muchísimas gracias profesor por esta clase, en verdad me ayudo enormemente a solucionar un problema del trabajo.

* **Enrique Devars (Platzi)** (2) [1011578](https://platzi.com/comentario/1011578/) 

	Excelente clase, me encanto que explicara para que sirve cada dependencia. Además de mostrar para que sirve cada configuración que hicimos.

* **Jose Gustavo Pacheco Sanchez** (1) [1030501](https://platzi.com/comentario/1030501/) 

	Un proyecto creado con create-react-app puede tener este tipo de configuración? para poder tener Server Side Render

	* **Gabriel De Andrade (Platzi)** [1030501] (1)

		En este caso es mejor que hagas uso de tecnologías como Next.js que vemos al final del curso 😄

	* **Jose Gustavo Pacheco Sanchez** [1030501] (1)

		Gracias por la respuesta, checare muy bien esa clase 😄

* **diego-serrano** (1) [1021721](https://platzi.com/comentario/1021721/) 

	A ustedes no les ocurre que la bandera --save esta deprecada ? Por ende me instala las dependencias que tienen que ser de devDependencies en el objeto de dependencies.

	* **gustavoa6791** [1021721] (2)

		utiliza -D, por ejemplo npm install nodemon -D

	* **Diego Alexander Forero Higuera (Platzi)** [1021721] (2)

		–save o -P es para guardar en las dependencias de producción  
		–save-dev o -D es para guardar como versión de desarrollo  
		Si escribes --save en una dependencia de desarrollo te la va a poner como dependencia de producción

# Integración de Express con React [5382]

## 0080. Servir React con Express [26467](https://platzi.com/clases/1839-ssr/26467-servir-react-con-express/)

### Descripción:


### Links:

* [redux-devtools - npm](https://www.npmjs.com/package/redux-devtools)

* [GitHub - reduxjs/redux-devtools: DevTools for Redux with hot reloading, action replay, and customizable UI](https://github.com/reduxjs/redux-devtools)

### Comentarios:

* **Camilo Andrés Santana Lizcano** (3) [1019930](https://platzi.com/comentario/1019930/) 

	Wow genial  
	Esto se pone bueno 😄

## 0090. Abstrayendo React Router, creando history y haciendo initialState más accesible [26468](https://platzi.com/clases/1839-ssr/26468-abstrayendo-react-router-creando-history-y-haciend/)

### Descripción:


### Comentarios:

* **David Lara Chirinos** (1) [1074768](https://platzi.com/comentario/1074768/) 

	Wao, ya adoro este curso

* **Miguel Ángel Muñoz Pozos** (1) [1023784](https://platzi.com/comentario/1023784/) 

	```
	    npm install history react-router-config
	    
	```

* **Heber Yarod Chanca Melgar** (1) [83411](https://platzi.com/comentario/1026230/) 
¿Es necesario instalar react-router para importar la clase Router? ¿No se puede trabajar con el Router de react-router-dom?

	* **Gabriel De Andrade (Platzi)** [83411] (1)

		Hola! Sí, deberías poder usar el de react-router-dom sin problemas

# Aplicar Server Side Rendering [5383]

## 0100. Definición de la función principal para realizar el renderizado desde el servidor [26469](https://platzi.com/clases/1839-ssr/26469-definicion-de-la-funcion-principal-para-realizar-e/)

### Descripción:


### Links:

* [Curso de Backend con Node.js](https://platzi.com/clases/backend-nodejs/)

### Comentarios:

* **jakson-duvan-zambrano** (1) [1042085](https://platzi.com/comentario/1042085/) 

	Ayuda tengo este error
	``` 
	    Error: Element type is invalid: expected a string (for built-in components) or a class/function (forcompositecomponents) butgot: undefined. Youlikelyforgottoexportyourcomponentfromthefileit'sdefinedin, oryoumighthavemixedupdefaultandnamedimports.
	        at ReactDOMServerRenderer.render (/mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/react-dom/cjs/react-dom-server.node.development.js:3743:17)
	        at ReactDOMServerRenderer.read (/mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/react-dom/cjs/react-dom-server.node.development.js:3373:29)
	        at renderToString (/mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/react-dom/cjs/react-dom-server.node.development.js:3988:27)
	        at renderApp (/mnt/c/users/57305/documents/escuela_js/platzivideo/src/server/server.js:122:16)
	        at Layer.handle [as handle_request] (/mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/express/lib/router/layer.js:95:5)
	        at next (/mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/express/lib/router/route.js:137:13)
	        at Route.dispatch (/mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/express/lib/router/route.js:112:3)
	        at Layer.handle [as handle_request] (/mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/express/lib/router/layer.js:95:5)
	        at /mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/express/lib/router/index.js:281:22
	        at param (/mnt/c/users/57305/documents/escuela_js/platzivideo/node_modules/express/lib/router/index.js:354:14)
	    
	```

	* **Luis Arturo Lira Cerda** [1042085] (1)

		No puedes pasar captura de tu código?
		
		También revisa esto, tal vez pueda servirte <https://stackoverflow.com/questions/34130539/uncaught-error-invariant-violation-element-type-is-invalid-expected-a-string>

	* **esdraspavon** [1042085] (1)

		a mi me ocurría lo mismo, cambié la forma de importar los componentes en serverRoutes.js y funcionó!

	* **David Lara Chirinos** [1042085] (1)

		Te recomiendo, rectificar el patch e los import
		``` 
		    const routes = [
		      {
		        exact: true,
		        path: '/',
		        component: Home,
		      },
		      {
		        exact: true,
		        path: '/login',
		        component: Login,
		      },
		      {
		        exact: true,
		        path: '/register',
		        component: Register,
		      },
		      {
		        exact: true,
		        path: '/player/:id',
		        component: Player,
		      },
		      {
		        name: 'NotFound',
		        component: NotFound,
		      },
		    ];
		    
		```

## 0110. Assets require hook [26470](https://platzi.com/clases/1839-ssr/26470-assets-require-hook/)

### Descripción:


### Links:

* [Server Rendering](https://redux.js.org/recipes/server-rendering)

* [ReactDOM – React](https://reactjs.org/docs/react-dom.html#hydrate)

### Comentarios:

* **Daniel Hernández** (3) [1038568](https://platzi.com/comentario/1038568/) 

	En mi caso tuve que agregar mi componente Layout para que se viera el header de la app.
	``` 
	    const html = renderToString(
	        <Provider store={store}>
	          <StaticRouter location={req.url} context={{}}>
	            <Layout>
	              {renderRoutes(serverRoutes)}
	            </Layout>
	          </StaticRouter>
	        </Provider>,
	      );
	    
	```

	* **carlosdummy14** [1038568] (1)

		Agradezco la solución, sin embargo me gustaría que el Prof. nos ampliara el porque sucede esto…
		
		Gracias

* **Guillermo Andres Valenzuela Palencia** (1) [1113849](https://platzi.com/comentario/1113849/) 

	Al deshabilitar Javascript, no me cargan las imagenes…

* **Guido Cavallo** (1) [1013612](https://platzi.com/comentario/1013612/) 
En mi caso yo configuro dentro de express en el apartado de las configuraciones para solo el entorno de desarrollo un servidor de estáticos con express. No es necesario instalar una dependencia extra que agrega peso a nuestro proyecto, cuando express viene incluído con un servidor de estáticos. Para el entorno de producción, los estaticos no se sirven desde express (por eso solo debemos configurarlo para el development) y en su lugar servimos los estáticos con Nginx, lo cual lo hace más eficientemente.

	* **Ezequiel Guerra** [1013612] (2)

		Claro si se puede hacer de la forma que tu dices y si funcionaria, pero si te fijas en el proyecto se están manejado algunas imágenes desde webpack, como el logo entre otras, es por eso se esta utilizando dentro de _webpack.config.js_ * el loader **file-loader**.
		
		Lo que he visto que se recomienda es usar imágenes livianas para que las maneje webpack como iconos etc, y las otras si en estáticos.
		
		En este caso para utilizar la imagen como el logo se esta usando
		``` 
		    import logo from'path'
		    
		    <img src={logo} />
		    
		```
		
		En el caso de tenerla como un directorio estático ya cambiaría un poco y debería usarse de la siguiente forma .
		``` 
		    <img src="host/imagen.png" />
		    
		```

## 0120. Hydrate y estado de Redux desde Express [26471](https://platzi.com/clases/1839-ssr/26471-hydrate-y-estado-de-redux-desde-express/)

### Descripción:


### Links:

* [Helmet](https://helmetjs.github.io/)

* [ReactDOM – React](https://es.reactjs.org/docs/react-dom.html#reference)

* [Server Rendering](https://redux.js.org/recipes/server-rendering/)

### Comentarios:

* **pabloverduzcos** (3) [1013033](https://platzi.com/comentario/1013033/) 

	Gran manera de resumir **renderToString** e **hydrate** , definitivamente todo queda más claro 😄

* **Daniel Hernández** (1) [83961](https://platzi.com/comentario/1039170/) 
al hacer delete window.PRELOADED_STATE; ya no lo hace visible desde la consola, pero si yo inspecciono el DOM desde el b...

	* **sampol.90 (Platzi)** [83961] (1)

		Si quieres eliminar el script puedes asignarle un id y en lo que se monte el cliente eliminas del DOM el script.

# Trabaja con entornos de desarrollo y producción [5384]

## 0130. Configurando nuestro servidor para producción [26472](https://platzi.com/clases/1839-ssr/26472-configurando-nuestro-servidor-para-produccion/)

### Descripción:


### Links:

* [GitHub - webpack-contrib/terser-webpack-plugin: Terser Plugin](https://github.com/webpack-contrib/terser-webpack-plugin)

### Comentarios:

## 0140. Configurando webpack para producción [26473](https://platzi.com/clases/1839-ssr/26473-configurando-webpack-para-produccion/)

### Descripción:


### Links:

* [Curso de Expresiones Regulares](https://platzi.com/clases/expresiones-regulares/)

* [GitHub - webpack-contrib/compression-webpack-plugin: Prepare compressed versions of assets to serve them with Content-Encoding](https://github.com/webpack-contrib/compression-webpack-plugin)

* [GitHub - webpack-contrib/terser-webpack-plugin: Terser Plugin](https://github.com/webpack-contrib/terser-webpack-plugin)

### Comentarios:

* **Camilo Andrés Santana Lizcano** (2) [1028564](https://platzi.com/comentario/1028564/) 

	Para no tener que estar cambiando el archivo .env podemos ponermos en modo **production** desde el script
	``` 
	    "build": "ENV=production webpack-cli --config webpack.config.js",
	    
	```

	* **Luis Arturo Lira Cerda** [1028564] (1)

		En algunos casos habrá a personas que nos les funcionará el script de esta manera, pero pueden hacerlo usando esta librería de npm <https://www.npmjs.com/package/cross-env>

* **Miguel Ángel Muñoz Pozos** (1) [1024028](https://platzi.com/comentario/1024028/) 

	Excelente clase el uso de variable de entorno ayuda mucho.♥

## 0150. Optimización del Build [26474](https://platzi.com/clases/1839-ssr/26474-optimizacion-del-build/)

### Descripción:


### Links:

* [GitHub - danethurber/webpack-manifest-plugin: webpack plugin for generating asset manifests](https://github.com/danethurber/webpack-manifest-plugin)

* [Curso de Expresiones Regulares](https://platzi.com/clases/expresiones-regulares/)

### Comentarios:

* **José Manuel Puicón Rodas** (1) [1022263](https://platzi.com/comentario/1022263/) 

	Esta optimización me emocionó !

* **Daniel Hernández** (1) [83969](https://platzi.com/comentario/1039368/) 
no entiendo por que ya no se usa html-loader

	* **sampol.90 (Platzi)** [83969] (1)

		Por que se está sirviendo todo desde Express. Ya no haría falta servir tu aplicación de react con el html loader

## 0160. Aplicar hashes al nombre de nuestros builds [26475](https://platzi.com/clases/1839-ssr/26475-aplicar-hashes-al-nombre-de-nuestros-builds/)

### Descripción:


### Comentarios:

* **Didier Zúñiga** (1) [1056085](https://platzi.com/comentario/1056085/) 

	A mi me pasa lo mismo que a @inquietus en su comentario sobre el prefijo 1 en los assets, pero me pasa solo cuando aplico la configuración de splitChunks para generar el vendor, y solo me sucede con el CSS, he revisado y todo esta igual al que se hace en la clase.

* **Jair Balcazar Cobeña** (1) [1052038](https://platzi.com/comentario/1052038/) 

	Cual es el beneficio de utilizar hashes en los nombres de los archivos, considero que se debió mencionar en la clase.

	* **sampol.90 (Platzi)** [1052038] (3)

		El principal beneficio de aplicar hashes es que el nombre cambia cada vez que desplegamos con cambios hechos, entonces nuestros usuarios siempre van a tener la ultima versión que lancemos por qué el navegador va a considerarlos archivos distintos y no van a tener caché.

* **Rafa Jiménez** (1) [1018526](https://platzi.com/comentario/1018526/) 

	Hola, tengo una duda a ver si me pueden ayudar
	
	Cuando hago el bundle, en mi carpeta de public se generan el app.js y app.css pero también se están generando 1.app.js y 1.app.css
	
	Alguien sabe a que se debe? estoy haciendo algo mal?
	
	![Captura de pantalla 2020-03-04 a las 16.13.01.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202020-03-04%20a%20las%2016.13.01-704b4e3e-cf15-4e12-b6a1-2e2ad04b3c4a.jpg)

	* **sampol.90 (Platzi)** [1018526] (1)

		Me compartes tu configuración de webpack por favor?
		
		Esto normamente esta relacionado a lo que tengas en tu output

	* **Rafa Jiménez** [1018526] (1)

		Lo he comparado con el del curso pero no encuentro diferencias
		
		<https://gist.github.com/inquietuss/684887f0a0d598140b4e67982b40f314>

	* **sampol.90 (Platzi)** [1018526] (1)

		Mmmm weird. Prueba importando solo el bundles que no tienen el 1 a ver. Tu configuración luce bien 🤔

	* **Rafa Jiménez** [1018526] (1)

		He terminado el proyecto y funciona todo correctamente excepto este detalle, si consigo solucionarlo lo compartiré
		
		Gracias por todo sampol, gran curso!

	* **sampol.90 (Platzi)** [1018526] (1)

		Brutal! Recuerda hacer el exámen de certificación y calificar el curso 👍

	* **ApolloAu** [1018526] (1)

		pot lo que vi en githubque posteaste, en los plugins te falta el plugin para crear el manifest.
		
		`!isDev ? new ManifestPlugin() : () => {},`
		
		Asi lo tengo yo.
		``` 
		    plugins: [
		        isDev ? new webpack.HotModuleReplacementPlugin() : () => {},
		        !isDev
		          ? new CompressionWebpackPlugin({
		              test: /\.js$|\.css$/,
		              filename: '[path].gz',
		            })
		          : () => {},
		        new MiniCssExtractPlugin({
		          filename: isDev ? 'assets/app.css' : 'assets/app-[hash].css',
		        }),
		        !isDev ? new ManifestPlugin() : () => {},
		      ],```
		    
		```

	* **ApolloAu** [1018526] (1)

		Nop error, esta ahi.

# Buenas prácticas de Server Side Render [5385]

## 0170. Vendorfiles en Webpack definiendo cacheGroups [26476](https://platzi.com/clases/1839-ssr/26476-vendorfiles-en-webpack-definiendo-cachegroups/)

### Descripción:


### Comentarios:

## 0180. Vendorfiles en Webpack generando el vendorfile [26477](https://platzi.com/clases/1839-ssr/26477-vendorfiles-en-webpack-generando-el-vendorfile/)

### Descripción:


### Links:

* [ESLint - Pluggable JavaScript linter](https://eslint.org/)

### Comentarios:

* **Luis Arturo Lira Cerda** (3) [1071863](https://platzi.com/comentario/1071863/) 

	Si quieren que su carpeta public se limpie cada vez que hagan un build, instalen `npm i -D clean-webpack-plugin` y agreguen la siguiente configuración a su webpack.config.js porque cada que hagan cambios y hagan un build, los archivos se generarán con un hash diferente, y con esto no tendrán archivos basura.
	``` 
	    const { CleanWebpackPlugin } = require('clean-webpack-plugin')
	    
	    // en la parte de los plugins
	    isDev
	      ? () => {}
	      : new CleanWebpackPlugin({
	        cleanOnceBeforeBuildPatterns: path.resolve(__dirname, 'src/server/public')
	      })
	    
	```

## 0190. Configuración de ESLint [26478](https://platzi.com/clases/1839-ssr/26478-configuracion-de-eslint/)

### Descripción:


### Links:

* [Next.js - The React Framework](https://nextjs.org/)

### Comentarios:

* **Miguel Ángel Muñoz Pozos** (2) [1024624](https://platzi.com/comentario/1024624/) 

	Un **Lint **es una herramienta de programación; originalmente lint era el nombre de una herramienta de programación utilizada para detectar código sospechoso, confuso o incompatible entre distintas arquitecturas en programas escritos en C; es decir, errores de programación que escapan al habitual análisis sintáctico que hace el compilador. En la actualidad, se utiliza este término para designar a herramientas que realizan estas tareas de comprobación en cualquier lenguaje de programación. Las herramientas de tipo lint generalmente funcionan realizando un análisis estático del código fuente.
	
	Las construcciones sospechosas que se suelen buscar son usos de variables antes de ser inicializadas o creadas, condiciones que no varían bajo ninguna circunstancia (Son siempre verdaderas o siempre falsas) y cálculos cuyos resultados probablemente caigan fuera del rango permitido por las variables utilizadas.

* **Didier Zúñiga** (1) [1062777](https://platzi.com/comentario/1062777/) 

	Chicos.
	
	Estoy usando **localStorage** para almacenar unos datos, funciona bien pero cuando la pagina se recarga (F5) aparece el error **ReferenceError: localStorage is not defined**
	
	Me imagino que ya no funciona por el hecho de renderearse en el server.
	
	Alguna manera optima para solucionar esto?

	* **esdraspavon** [1062777] (1)

		Hola Didier! Yo lo solucioné guardando la información en cookie, asi puedo acceder tanto desde el sv como desde el cliente.
		
		Cualquier otra idea, es bienvenida!

# Alternativas al SSR con Express [5386]

## 0200. Cómo implementar Next.js [26479](https://platzi.com/clases/1839-ssr/26479-como-implementar-nextjs/)

### Descripción:


### Links:

* [GatsbyJS](https://www.gatsbyjs.org/)

* [Gatsby Server Rendering APIs | GatsbyJS](https://www.gatsbyjs.org/docs/ssr-apis/)

* [Webpack and SSR | GatsbyJS](https://www.gatsbyjs.org/docs/webpack-and-ssr/)

* [Curso de Desarrollo de Aplicaciones Web con Gatsby JS](https://platzi.com/clases/gatsby/)

### Comentarios:

## 0210. Cómo usar Gatsby.js [26480](https://platzi.com/clases/1839-ssr/26480-como-usar-gatsbyjs/)

### Descripción:


### Comentarios:

## 0220. Cuando usar cada una de las herramientas presentadas [26481](https://platzi.com/clases/1839-ssr/26481-cuando-usar-cada-una-de-las-herramientas-presentad/)

### Descripción:


### Comentarios:

