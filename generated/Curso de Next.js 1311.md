# Introducción a Next.JS

## 0010. ¿Qué es Next.JS

### Descripción:


Next.js es un framework para construir aplicaciones web modernas en React. Una de sus principales características es que pensado para tener una excelente experiencia como desarrollador.

### Comentarios:

* **jdgarcia6** (6)

	
	no hace falta aprender react 😄

* **Carlos Rivas** (6)

	
	Saber que el profesor de este curso sera Roberto, asegura la calidad del mismo.

	* **Eduardo Hidalgo Díaz Rugama** (1)

		
		completamente de acuerdo con usted

* **David Daniel Castillo Nava** (4)

	
	Next.js es un framework que usa la Liberia React.js para crear aplicaciones modernas.

* **Miguel Angel Morales Larriega** (3)

	
	Recuerden SSR está presente en:  
	-React como Next.js.  
	-Vue como Nuxt,  
	-Angular como Angular Universal

* **jesusmurf** (3)

	
	Con Nextjs se puede hacer server side rendering con Express, Django… etc? Yo creía que Nextjs era una librería para hacer server side rendering con React.

	* **Oscar Barajas Tavares (Platzi)** (5)

		
		Yo he hecho proyectos con Next.js mezclando express y react, te comparto un proyecto que tengo en github donde mezclo estas tecnologías:
		
		<https://github.com/gndx/100tifi.co>

	* **Sebastian  Segura** (1)

		
		Venia buscando eso @gndx! Tenia en mente la pregunta se puede usar con express? Gracias crack!

* **Andrés Madrigal** (3)

	
	next.js es un framework del framework?

	* **WilliamVelazquez** (2)

		
		Cómo? Te refieres de React? Porque React no es un Framework, es una biblioteca! 😉

	* **Héctor Daniel Vega Quiñones (Platzi)** (7)

		
		 **Next.js** es un framework universal de JavaScript que corre en el navegador y servidor. Usa **React.js** para crear plantillas, lo cual hace que desarolladores con experiencia en React.js puedan tener una experiencia de trabajo rápida y productiva.

	* **Juan David Castro (Platzi)** (9)

		
		Jeje!  
		**Reactjs** es una **librería**. **Nextjs** en cambio si es un **framework** que usa _entre muchas otras herramientas y librerías_ a Reactjs.

	* **Oscar Barajas Tavares (Platzi)** (3)

		
		@juandc nos ha dado la mejor explicación, hay que tener en cuenta la diferencia entre librería y framework.

* **jesus-olivares661** (2)

	
	veo que en el contenido del curso de R eact-Router tienen SSR (Server Side Render).  
	No quiero que me pase como con Vue que usando Nuxt basicamente el conocimientos de Vue-Router no es muy util.  
	Sucede lo mismo con react…?  
	Sera que mejor aprendo primero Next.js

	* **Miguel Angel Morales Larriega** (3)

		
		Next.js hace que ya no necesites de React Router, ya que lo tiene incorporado. Por ende no necesitas tener conocimiento de React Router, ya que al crear componentes nuevos estos por default crean su propia ruta.  
		Ejemplo:  
		Creo un componente llamado index y otro llamado nosotros.  
		enel url: el localhost por defecto es el index pero solo basta con poner “/nosotros” y te lleva automaticamente a la vista de ese componente.  
		Y asi si creas muchos mas archivos en tu carpeta de pages solo pones el “/” seguido del nombre del archivo y listo.  
		No hay mas React Router

* **David Ruiz** (2)

	
	Tengo una pregunta, he leido mucho en la comunidad de JavaScript y React, devs que hablan de Gatsby y Next, quisera saber si esos dos se relacionan. Por que estoy algo confundido ya que relaciono más Gatsby como WordPress pero para React.

	* **Juan David Castro (Platzi)** (5)

		
		👋 ¡Hey David! ¿Cómo vas? Ambos son muy parecidos.
		
		**Gatsby** está sobretodo orientado a construir blogs y se ha vuelto muy popular porque nos da muy buena experiencia de desarrollo y es relativamente “fácil” extender sus superpoderes usando plugins que instalamos por NPM y configuramos en archivos tipo JSON.
		
		Además, Gatsby tiene muy buenos resultados en performance porque hace _preloading_ , eso significa que cuando entramos a una página podemos ver la estructura y los estilos funcionando casi inmediatamente, como si fuera SSR.
		
		Muchas personas “importantes” en el mundo de React usan Gatsby para sus blogs, como [Dan Abramov](https://overreacted.io/) y [Kent Dodds](http://kentcdodds.com). 😮
		
		**Next** es muy parecido pero no está orientado a blogs sino a cualquier cosa. También ofrece la opción de [_preloading_](https://nextjs.org/features/static-exporting) pero, a mi parecer, su mejor funcionalidad es que el SSR es excelente y no hay que hacer nada, funciona bien desde el principio. 👌
		
		Muchísimas personas y empresas usan Next para sus sitios web y aplicaciones.
		
		__
		
		Si quieres elegir uno de los dos te recomiendo que tomes ambos cursos (yes, ¡pronto tendremos curso de Gatsby aquí en Platzi!). 🎉🙌

* **Jesus Garcia** (2)

	
	iniciando curso 😄

* **renny10037** (1)

	
	Tengo que saber typescript para usar next.js?

* **AUREA PAOLA RODRIGUEZ BARRON Rodriguez** (1)

	
	Hola a todos!, hay alguna manera de crear Middlewares personalizados para Next?, además… el “react-helmet” funciona de la misma manera?

* **Rigo Antonio Galicia Barrera** (1)

	
	Alguien sabe como integrar next con redux?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Hola en la documentación oficial de next hay un ejemplo de como integrar redux <https://github.com/zeit/next.js/tree/canary/examples/with-redux>

* **Anthony Gonzalez** (1)

	
	Empecemos! 😬

* **Georgie Duarte** (1)

	
	Soy de los que le gusta tener los estilos en archivo aparte, se puede guardar en un archivo aparte styled JSX e importarlos desde el componente? para aprovechar la caracteristica de que lso estilos solo afecten ese componente?

	* **Eduardo Hidalgo Díaz Rugama** (1)

		
		Si. asi como importas módulos en archivos separados, puedes hacer los mismo con styled JSX.
		
		También puedes añadir plugins a tu webpack para ser capaz de leer archivos css y exportarlos a tus componentes. Yo así trabajo. Es cómodo porque cuando compilar el bundle productivo puedes juntar todos tus archivos css en uno solo, y al cargar tu webpage solo cargas 1 archivo css

* **Omar Alvarez** (1)

	
	Next.Js es el equivalente a Webpack?? o son dos cosas muy distintas

	* **Andres Rodriguez Escudero** (2)

		
		Tengo entendido que Nextjs tiene webpack por dentro para generar los bundle.  
		`Automatic transpilation and bundling (with webpack and babel)`
		
		<https://nextjs.org/docs/>

* **Diego Fernando Berrio Meza** (1)

	
	Esta es mi app de podcasts puedes verla <https://podcasts-kpehsmweph.now.sh/>

* **Gonzalo Gras cantou** (1)

	
	VAMO ROBERTTT !!! 😄

* **Lauramduquesa** (1)
Hola a todos, tengo un problema de CORS, llamando cualquier API desde componentes, por ejemplo utilizando el useEffect(), debo sobre esc...

	* **Luis Arturo Lira Cerda** (2)

		
		Hay un paquete de npm llamada cors. Sólo lo instalas con npm i cors y luego en el server lo usas
		``` 
		    const cors = require('cors')
		    app.use(cors())
		    
		```
		
		Aunque esa lo he necesitado hacer en API que yo he creado. Para el tema de este curso de Next.js no recuerdo que fuera necesario.  
		También, sería de gran ayudad que nos compartas tu código y una captura del error que te lanza.

* **Georgie Duarte** (1)
Soy de los que le gusta tener los estilos en archivo aparte, se puede guardar en un archivo aparte styled JSX e importarlos desde el comp...

	* **Eduardo Hidalgo Díaz Rugama** (1)

		
		Si. asi como importas módulos en archivos separados, puedes hacer los mismo con styled JSX.
		
		También puedes añadir plugins a tu webpack para ser capaz de leer archivos css y exportarlos a tus componentes. Yo así trabajo. Es cómodo porque cuando compilar el bundle productivo puedes juntar todos tus archivos css en uno solo, y al cargar tu webpage solo cargas 1 archivo css

* **jesusmurf** (1)
Con Nextjs se puede hacer server side rendering con Express, Django… etc? Yo creía que Nextjs era una librería para hacer server side ren...

	* **Oscar Barajas Tavares (Platzi)** (5)

		
		Yo he hecho proyectos con Next.js mezclando express y react, te comparto un proyecto que tengo en github donde mezclo estas tecnologías:
		
		<https://github.com/gndx/100tifi.co>

* **Andrés Madrigal** (0)
next.js es un framework del framework?

	* **WilliamVelazquez** (2)

		
		Cómo? Te refieres de React? Porque React no es un Framework, es una biblioteca! 😉

## 0020. Creando nuestra primera página

### Descripción:


Vamos a crear nuestra primera página en Next.js, más que nada para tener una muy buena idea de cómo funciona el router de Next, cómo crear un pequeño componente en React, y sobre todo cómo hacer para crear un buen entorno de desarrollo en un proyecto de Node.  
Esto no es solamente para Next, puede aplicar para cualquier proyecto que hagamos en Javascript.

### Comentarios:

* **eddyarellanes** (15)

	
	Curso de Unit Testing de Platzi spoiler alert?

	* **ferontv_** (3)

		
		Ojala !

	* **jesusmurf** (4)

		
		Si! un curso de Unit Testing para React con Jest por favor!!

	* **victorAguilera** (1)

		
		La documentacion oficial es bastante buena

	* **mariandrea (Platzi)** (2)

		
		Ya tenemos un curso de Unit Testing con Jasmine: <https://platzi.com/clases/pruebas-unitarias/>

	* **mariandrea (Platzi)** (2)

		
		Y también un Curso de JavaScript Testing con Jest  
		<https://platzi.com/clases/js-jest/>

* **Luis Daniel Becerra Avellaneda** (8)

	```
	    mkdir podcast
	    cd podcast
	    npm init -y
	    npm addnext react react-dom
	    
	```
	
	O si prefieres utilizar yarn
	``` 
	    yarn init -y
	    yarn addnext react react-dom
	    
	```

* **edwintrumpet** (5)

	
	Usando un componente funcional y Fragment en lugar de div para no enviar cosas de más al navegador se vería así:
	``` 
	    import { Fragment } from'react'
	    
	    exportdefault () => (
	        <Fragment>
	            <h1>¡Hola mundo!</h1>
	            <p>Bienvenidos al curso de Next.js</p>
	        </Fragment>
	    )
	    
	```
	
	Por lo que veo no es necesario importar React y ReactDOM, pero si es necesario hacerlo con Fragment.

	* **Luis Miguel Rodriguez** (7)

		
		sintaxis corta de fragment <> </>

	* **Alejandro Robleto** (1)

		
		muy buena gracias por recordalo edwin

* **roganoalien** (5)

	
	qué diferencia hay entre `npm add` y `npm install`?

	* **Danvasem** (3)

		
		npm add es un ‘alias’ de nom install.

	* **Danvasem** (3)

		
		npm add es un alias de npm install

* **Sergio Minei** (5)

	
	## Iniciar un proyecto con Next
	
	Instalar las dependencias:
	``` 
	    $ npm add next react react-dom 
	    
	```
	
	**Scripts indispensables**
	
	**dev** : entorno de desarrollo.  
	**build** y **start** : entorno de producción
	
	Dentro del package.json, se debe agregar:
	``` 
	    "scripts": {
	      "dev": "next",
	      "build": "next build",
	      "start": "next start"
	    }
	    
	```
	
	**Ruteo**
	
	Next busca automáticamente todas las páginas en la carpeta **pages**.
	
	El **router** lo que busca es el mismo nombre del la ruta (path) que tenemos en la carpeta **/pages**.
	
	**Ejemplo** :  
	`GET/`  
	Muestra el archivo en: `/pages/index.js`  
	`GET/platzi`  
	Muestra el archivo en: `/pages/platzi.js`
	
	En React, cada componente debe de retornar un solo objeto de HTML.
	
	**Ejemplo de un componente** :
	``` 
	    exportdefaultclassextendsReact.Component{
	      render() {
	        return (
	          <div>
	            <h1>Hola Mundo!</h1>
	            <p>Bienvenido al curso de Nect.js</p>
	          </div>
	        )
	      }
	    }
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

	* **Ivan Robles** (2)

		
		Excelente trabajo MineiToshio!! 😃

	* **Sergio Minei** (3)

		
		Muchas gracias @elSharmaz

* **Miguel Angel Morales Larriega** (4)

	
	//Con un sfc podría haber hecho menos código:
	
	const Index = () => (  
	<h1>¡Hola Platzi!</h1>  
	);  
	export default Index;

	* **Juan González** (1)

		
		export default Index = () => <h1>¡Hola Platzi!</h1>

* **Miguel Angel Morales Larriega** (3)

	
	Al ejecutar solo “npm-init” te trae cada valor del objeto del paquete y te hace una serie de preguntas para poder definir cada uno de ellos.
	
	En cambio al agregarle “-y” te trae por default los valores.

* **Eduardo P. Rivero** (3)

	
	Si como yo les gusta usar una carpeta **src** y mantener todo su código ahi pueden pasarle el root directory a next:
	``` 
	    "scripts": {
	        "dev": "next ./src"
	    }
	    
	```
	
	De esta manera pueden tener su carpeta **pages** dentro de src. Obviamente funciona con cualquier ruta no solo con **src**.

* **Carlos Sánchez** (2)

	
	si usamos nextjs, no necesitamos webpack?

	* **Sebastian Cardoso Castillo** (1)

		
		No necesitamos instalar webpack porque next lo usa por abajo. En el archivo next.config.js podemos configurar las opciones de webpack

* **JoosCode** (2)

	
	tengo una pregunta y disculpen mi novatada… porque funciona index.js si no estoy importando react ??

	* **sampol.90 (Platzi)** (5)

		
		Todo archivo `.js` se convertiste en una ruta, es procesado y renderizado. Next se encarga de hacer el import necesario 😃

	* **santiagomarcano** (1)

		
		Es importante resaltar que el archivo debe estar ubicado en la carpeta pages para que Next lo lea como una ruta

* **Daniela Gonzales** (2)

	
	cual es la diferencia de crear un web con next y sin next?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Next ofrece features adicionales como server side render directamente, si no usas next tienes que hacer todo el server side render tu, eso es que tu pagina cargue de inmediato una versión estática mientras carga todos los datos y tu app de react, con esto el usuario siente que el sitio es más fluido y rápido.

	* **Miguel Angel Morales Larriega** (2)

		
		La diferencia es SSR  
		Hacerlo sin next js implica que tu aplicación es un CSR (Client Side Render) osea una aplicacion que corre del lado del cliente.  
		Ahora si tu aplicación es abierta en otro tipo de comoputador o celular que no tiene la misma capacidad que una actual, genera que tu aplicacion se demore en el tiempo de carga y sea solo óptimo en computadores actuales.  
		Pero al utilizar SSR (Server Side Render) tu aplicación correrá del lado del servidor y no tendras problema en el tiempo de carga y obviamente se podra ver en cualquier tipo de dispositivo, pero ojo quizas me diras que el servidor será mas lento, pero no es así, ya que un sevidor es mucho más rapido y más optimo que una computadora.
		
		Espero haberte aclarado las dudas.

* **Carlos Rivas** (2)

	
	¿No es mejor usar un “fragment” en vez de un “div”?

	* **LeandroVidela** (2)

		
		Claro! Sería algo así:
		``` 
		    classHolaextendsReact.Component{
		      render() {
		        return (
		          <React.Fragment>
		            <h1>HolaPlatzi</h1>
		            <p>Bienvenidos al curso de next js</p>
		          </React.Fragment>
		        );
		      }
		    }
		    
		    export defaultHola;
		    
		```

	* **Martin L.** (1)

		
		pensaba lo mismo

	* **edg_colon** (1)

		```
		    functionHola () {
		    
		        return (
		          <>
		            <h1>Hola Platzi</h1>
		            <p>Bienvenidos al curso de next js</p>
		          </>
		        );
		    }
		    
		    export default Hola;
		    
		```

* **Sergio Minei** (2)

	
	La mascota de Github del fondo del video está tomando PlatziCola! 😮

* **Juan  Reyes** (2)

	
	30 a 40 Millones de años xD

* **Carlos Rivas** (2)
¿No es mejor usar un “fragment” en vez de un “div”?

	* **LeandroVidela** (2)

		
		Claro! Sería algo así:
		``` 
		    classHolaextendsReact.Component{
		      render() {
		        return (
		          <React.Fragment>
		            <h1>HolaPlatzi</h1>
		            <p>Bienvenidos al curso de next js</p>
		          </React.Fragment>
		        );
		      }
		    }
		    
		    export defaultHola;
		    
		```

* **alejandrocabreratavara** (2)
Al momento de crear nuestro componente de react como clase , es decir class extends React.Component { … No es necesario importar react? …...

	* **davidtoca (Platzi)** (1)

		
		Es mejor si al momento de importar React haces esto:
		``` 
		    importReact, { Component } from 'react'
		    
		    classTuComponenteextendsComponent{
		    }
		    
		```

* **José Antonio aparicio gallego** (1)

	
	Usas la clase de React.Component sin importarla, me puedes explicar como puede funcionar eso que tu haces por que normalmente no funciona así,
	
	tendrías que poner al principio, pero yo no veo por ningún sitio eso  
	una respuesta seria apropiada. Gracias
	
	import React, { PureComponent } from “react”

* **Didier Zúñiga** (1)

	
	Es decir que con Next también se hacen cosas que se hacen con con webpack?

* **WSJedp** (1)

	
	Que gran clase, no conocia Next y por lo que veo es un gran framework, para realizar aplicaciones de todo tipo de tamaños!

* **Alejandro Robleto** (1)

	
	buenicima esta clase me gusto mucho y se que se vanza muy rapido

* **Juancarlos Salcedo Terán** (1)

	
	Como soluciono esto!!![![error yarn run dev.png](https://static.platzi.com/media/user_upload/error%20yarn%20run%20dev-e9291a0c-f4b6-4d9c-a1f9-641faa73d26f.jpg)

	* **onlinejaime** (2)

		
		Tal y como te pone el error, verifica que no hayas hecho ningún error en la escritura del query.
		
		Si este era el fallo, dame una estrellita!!!

	* **Juancarlos Salcedo Terán** (1)

		
		NO eh podido solucionar esto aun…

	* **Daniel Esteves** (1)

		
		¡Hola Juan! El error se debe a una configuración del `package.json` debes tener el `"browserlist"` de esta manera:
		``` 
		    "browserslist": {
		      "production": [
		        ">0.2%", "not dead", "not op_mini all"
		      ],
		      "development": []
		    }
		    
		```

	* **jhon manuel angulo moncada** (1)

		
		Puede ser que tu problema sea por que estas pasando return y el <div> en lineas diferentes prueba así:
		``` 
		    export defaultclassextendsReact.Component{
		        render() {
		            return <div>
		                <h1>HolaMundo!</h1>
		                <p>Bienvenidos al curso de Next.js</p>
		            </div>
		        }
		    }
		    
		```

* **JF2C** (1)

	
	Quizás usar más const que let

* **Julio Gutierrez** (1)

	
	Scripts indispensables  
	**dev:** Entorno de Desarrollo (livereload, otros)  
	**build y start:** Entorno de Producción.

* **Julio Gutierrez** (1)

	
	nvm init -y  
	Comando para crear el archivo de configuración de un proyecto en Node

* **alejandrocabreratavara** (1)

	
	Al momento de crear nuestro componente de react como clase , es decir  
	class extends React.Component { …
	
	No es necesario importar react? … ni darle nombre al componente?

	* **davidtoca (Platzi)** (1)

		
		Es mejor si al momento de importar React haces esto:
		``` 
		    importReact, { Component } from 'react'
		    
		    classTuComponenteextendsComponent{
		    }
		    
		```

* **salinash2000** (1)

	
	en este caso no se requiere hacer el import de react?

* **Byhako** (1)

	
	¿Como puedo configurar el puerto en el que corre si no tengo webpack?

	* **sergiodxa** (3)

		
		Usando `next -p 3001` o `next start -p 3001` para cambiarlo al puerto 3001.

	* **Sebastian Cardoso Castillo** (1)

		
		También puedes usar **npm run dev – -p** 3001 para cambiarlo al puerto 3001

* **Byhako** (1)

	
	¿Cual es la diferencia entre los scrips build y start?

	* **sergiodxa** (3)

		
		  * `next` inicia la aplicación en modo desarrollo
		  * `next build` construye los archivos para producción
		  * `next start` uso los archivos del build para iniciar la aplicación en modo producción
		
		
		
		Usando `next build` podrías hacer el build en tu computadora por ejemplo o en un sistema de CI/CD y luego subir los archivos a un servidor y ahí ejecutar `next start`
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Byhako** (1)

		
		Muchas gracias. Ahora si todo claro. 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **jescobarospina** (1)

		
		Sergio como vas? de casualidad sabes como montar una app de Next en IIS?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Daniee** (1)

	
	seria recomendable utilizar webpack ? o el build que hace next ya esta suficientemente optimizado ?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Next ya tiene webpack optimizado para trabajar, puedes configurar webpack si necesitas cosas especificas <https://nextjs.org/docs#customizing-webpack-config>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Oscar Barajas Tavares (Platzi)** (1)

	
	No debemos olvidar utilizar  
	`npm init -y`
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Oscar Fernando Segovia Julia** (1)

	
	No se puede usar Template en lugar de Div?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		No, los navegadores renderizan el contenido de la etiqueta template como texto plano por lo tanto con react puede fallar, la práctica más común es crear un contenedor usando div.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Martín Leyva** (1)

	
	Una de las restricciones que tenemos al desarrollar en React, es que cada componente debe devolver un solo componente de HTML.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Martín Leyva** (1)

	
	El siguiente paso es **_agregar las dependencias_** :  
	npm add next react react-dom
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Kevin Humberto León Santamaria** (1)
No me corre el entorno de desarrollo, ya intente borrando la carpeta node_modules y el archivo package-lock.json, luego borre el cache y ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Gabriel De Andrade (Platzi)** (2)

		
		Hola! Parece que en la pages del proyecto no está declarado un index.js, asegurate de que si exista un archivo index.js dentro de pages y asegurate de estar en la carpeta correcta 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Byron Miguel Piedrahita Hernandez** (1)
Que mas se necesita tener instalado aparte de node.js antes de comenzar este proyecto?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **edwintrumpet** (1)
¿Se pueden usar componentes funcionales?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **AlexGarrixen** (1)

		
		Hola edwin claro que si, si requieres crear un estado puedes hacerlo con hooks
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **JoosCode** (1)
tengo una pregunta y disculpen mi novatada… porque funciona index.js si no estoy importando react ??
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **sampol.90 (Platzi)** (5)

		
		Todo archivo `.js` se convertiste en una ruta, es procesado y renderizado. Next se encarga de hacer el import necesario 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Byhako** (1)
¿Como puedo configurar el puerto en el que corre si no tengo webpack?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **sergiodxa** (3)

		
		Usando `next -p 3001` o `next start -p 3001` para cambiarlo al puerto 3001.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Byhako** (1)
¿Cual es la diferencia entre los scrips build y start?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **sergiodxa** (3)

		
		  * `next` inicia la aplicación en modo desarrollo
		  * `next build` construye los archivos para producción
		  * `next start` uso los archivos del build para iniciar la aplicación en modo producción
		
		
		
		Usando `next build` podrías hacer el build en tu computadora por ejemplo o en un sistema de CI/CD y luego subir los archivos a un servidor y ahí ejecutar `next start`
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Oscar Fernando Segovia Julia** (1)
No se puede usar Template en lugar de Div?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		No, los navegadores renderizan el contenido de la etiqueta template como texto plano por lo tanto con react puede fallar, la práctica más común es crear un contenedor usando div.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Martín Leyva** (0)

	
	 **next** automaticamente busca todas las páginas en la carpeta pages
	
	El **router** lo que busca es el mismo nombre del la ruta ( **path** ) que tenemos
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Martín Leyva** (0)

	
	El primer paso para todo proyecto de JavaScript es crear un archivo **_package.json_** que tiene información basica para el proyecto.
	
	La foma mas fácil de hacerlo es con:
	
	npm init -y
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

## 0030. Styled JSX

### Descripción:


Vamos a hablar en esta clase de Styled JSX que es el sistema de estilos que maneja Next.js y viene a resolver algunos problemas que son muy típicos del mundo de React, e incluso algunos que son más propios de CSS.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Sergio Minei** (7)

	
	## Style JSX
	
	**Styled JSX** que es el sistema de estilos que maneja Next.js.
	
	¿Por qué usar Style JSX?
	
	  * Es más acorde a React.
	  * Evitamos problemas al escalar.
	
	
	
	**¿Cómo funciona?**  
	Escribimos CSS3 como siempre pero solo aplica al componente.
	``` 
	    <style jsx>{`
	      .clase {color: red}
	    `}<style>
	    
	```
	
	**Style JSX** solo se aplica por componente. Tampoco se aplica a componente internos o externos.
	
	¿Cómo se pueden romper estas reglas?
	
	**Atributos Globales**
	
	`<style jsx global>`
	
	Estos atributos se van a aplicar a toda la aplicación. No se recomienda usar atributos globales.
	``` 
	    <style jsx global>{`
	      body {background: red}
	    `}<style>
	    
	```
	
	**Operador Global**
	
	`:global()`
	
	Este nos permite aplicar un atributo de css de manera global.
	``` 
	    <style jsx>{`
	      :global(p) {color: green}
	    `}<style>
	    
	```
	
	En el caso anterior, todas las etiquetas `p` van a tener el estilo `color:green`.
	
	Si se quiere aplicar un estilo a todos los hijos de la aplicación, se puede hacer de la siguiente manera:
	``` 
	    <style jsx>{`
	      div :global(p) {color: green}
	    `}<style>
	    
	```
	
	En este caso, se aplica el `p{ color: green }` a todos los `p` que están dentro del componente.
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jhon manuel angulo moncada** (6)

	
	para next “9.1.3”
	
	ya no se usa “static”, en su reemplazo se usa “public”
	
	y la imagen se cargaría así:
	``` 
	    <img 
	                src="/platzi-logo-small.png"
	                alt="Platzi logo"
	                />
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **ferontv_** (6)

	
	Listo !
	
	![](https://firebasestorage.googleapis.com/v0/b/pruebas-cfb21.appspot.com/o/Captura%20de%20pantalla%202018-07-10%20a%20la\(s\)%2022.54.57-aa7cbfa9-6039-4092-9ee6-820b6a7e2ee1.jpg?alt=media&token=7718de87-ff2b-453a-9f2f-5b4934d7a7de)
	``` 
	    exportdefaultclassextendsReact.Component {
	      render() {
	        return (
	          <div>
	            <div className="container">
	              <h1>Acerca del curso</h1>
	              <img src="/static/about-img.jpg" alt="Platzi"/>
	              <p>Next.js promete ser uno de los frameworks más utilizados por devs frontend</p>
	            </div>
	            <style jsx>
	              {`
	                .container {
	                  font-family: 'Avenir', Helvetica, Arial, sans-serif;
	                  display: flex;
	                  flex-direction: column;
	                  height: 100%;
	                  align-items: center;
	                  justify-content: space-around;
	                }
	                h1 {
	                  color: #14BDEB;
	                  font-size: 5.5em;
	                }
	                :global(div p) {
	                  color: #EEF4ED;
	                  font-size: 3.5em;
	                  text-align: center;
	                }
	                img {
	                  max-width: 70%;
	                }
	              `}
	            </style>
	    
	            <style jsx global>
	              {`
	                body {
	                  background: #2C302E;
	                }
	              `}
	            </style>
	          </div>
	        );
	      }
	    }
	    
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Henry Villavicencio** (3)
Next ha cambiado un poco. Ahora debes colocar la carpeta static dentro de una llamada public. A mí no me cargaban las imágenes y así pude soluciona
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Cesar Augusto Garzón Puentes** (1)

		
		Exactamente.  
		<https://nextjs.org/docs/basic-features/static-file-serving>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Luis Daniel Becerra Avellaneda** (3)

	
	Reto Completo: <https://podcast-bynuniycwt.now.sh/FJS>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **johnaagudelo** (2)

	
	En la nueva versión los assets se ponen dentro de una carpeta “public” y se accede desde el componente solo ingresando el nombre del asset.
	
	`<img src="/platzi-logo.png" alt="logo platzi" />`
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Alan Mena** (2)

	
	Reto cumplido:
	``` 
	    import { Fragment } from'react';
	    
	    exportdefaultfunctionBird() {
	    
	        return (
	            <Fragment>
	                <stylejsx>{`
	    
	                    img {
	                        max-width: 100%;
	                        text-align: center;
	                        display: block;
	                        margin: auto;
	                    }
	            
	                `}</style>
	    
	                <stylejsxglobal>{`
	                    body {
	                        background: #273837;
	                    }
	                `}</style>
	    
	                <img 
	                    src="/static/Bird.jpg" 
	                    alt="Kolibri"
	                />
	    
	            </Fragment>
	        );
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Jorge Mendez Ortega** (1)

		
		good
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Luis Salazar** (2)

	
	Les recomiendo a todos los chicos para mejor manejo de componentes con React, si vienen con poco conocimiento, crear un componente funcional hace todo mucho mas entendible.
	``` 
	    import React from"react";
	    
	    const Home  = () => {
	        return (
	            <divclassName="main">
	                <h1>Hola Mundo <span>!!!</span></h1>
	                <div>
	                    <imgsrc="/static/platzi-logo.png"alt="Platzi" />
	                </div>
	    
	                <stylejsx>{`
	    
	                    .main {
	                        display: flex;
	                        flex-direction: column;
	                        align-items: center;
	                    }
	    
	                    h1 {
	                        color: red;
	                    }
	    
	                    img {
	                        width: 100px;
	                        height: auto;
	                    }
	                `}</style>
	    
	                <stylejsxglobal>{`
	                    body {
	                        background-color: #fff;
	                    }
	                `}</style>
	            </div>
	        )
	    }
	    
	    export default Home
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **josdanind** (1)

		
		Cuando creo un componente y lo importo a mi index.js, se genera un error ocacionado por la etiqueta <style jsx>. ¿Importas algún módulo para porder renderizar el componente?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **David Daniel Castillo Nava** (2)

	
	 **Mi reto!!**
	
	![](https://s3.amazonaws.com/davecast/reto.png)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jsechirinos** (2)

	
	**Importante esta clase**
	
	`examen spoiler alert`
	
	Styled JSX:
	
	`Como funciona?`  
	Escribimos CSS3 como siempre,  
	sólo aplica al componente.
	
	**Estilos al componente**
	``` 
	    <scriptjsx>{`
	    	... tus estilos como en css
	    `}</script>
	    
	```
	
	**Estilos de forma global**
	``` 
	    <scriptjsxglobal>{`
	    	... tus estilos como en css
	    `}</script>
	    
	```
	
	* * *
	
	**Operador :global()**
	
	**Ejemplo:**
	``` 
	    <divclassName="main">
	    	<Navegacion/>
	    </div>
	    
	    //Navegacion Component
	    <div>
	    	<a>Home</a>
	    </div>
	    
	    
	```
	
	Cambiar el estilo de Navegacion
	``` 
	    <scriptjsx>{`
	    	.main:global(a){
	    		color:red;
	    	}
	    `}</script>
	    
	```
	
	**Casos Especiales**
	
	`:global(p){ ...estilos }` = afecta a todos los **< p>** de la app
	
	`div:global(p){ ...estilos }` = hace referencia al **< div>** del componente y afecta a todas sus **< p>**
	
	`:global(div p){ ...estilos }` = todos los **< p>** que estén dentro de un **< div>** en la app, serán afectadas
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jhurtadojerves** (2)
![](https://i.imgur.com/E188nEe.png)
	
	El código del componente en github: <https://github.com/jhurtadojerves/platzi-podcasts/blob/master/pages/about.js>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **edwintrumpet** (2)
¿Se puede usar Sass? ¿Se pueden crear los estilos en una hoja aparte?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **santiagomarcano** (2)

		
		Hola Edwin. Si es posible! Puedes usar tanto hojas de estilo como módulos CSS.
		
		<https://github.com/zeit/next-plugins/tree/master/packages/next-sass>
		
		En ese repositorio encontrarás la integración completa de Sass a un proyecto existente de Next.js
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Luis Fernando Valderrama Gastiaburu** (1)

	
	Completed  
	![page about.png](https://static.platzi.com/media/user_upload/page%20about-2ae70dc7-5d43-43d6-9146-c0a7b3839e4f.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Sánchez** (1)

	
	Aqui esta la mia.  
	![Screenshot NextJS](https://i.imgur.com/0s2UfXE.png)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Roberto S. Sampayo** (1)

	
	Mi Pagina about:
	
	![](https://i.imgur.com/h3zWuqB.png)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WSJedp** (1)

	
	Los styled jsx nos permiten crear los estilos css dentro del mismo componente, permitiéndonos crear componentes y aplicaciones muchas mas reactivas y poderosas para nuestros proyectos!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Le_MaliX** (1)

	
	Aqui mi "about"  
	Código:
	``` 
	    import React from 'react';
	    
	    export default () => (
	      <>
	        <div className="flex">
	          <img src="/wd-logo.png" alt="Logo" />
	          <h2>Created by &#65533;&#65533;&#65533;</h2>
	          <p>Proyecto de aprendizaje de NextJS</p>
	        </div>
	    
	        <style jsx>
	          {`
	            .flex {
	              display: flex;
	              flex-direction: column;
	              justify-content: center;
	              align-items: center;
	              min-height: 100vh;
	            }
	            img, p, h2 {
	              max-width: 50%;
	              max-height: 50vh;
	            }
	            p, h2 {
	              color: white;
	              text-align: center;
	            }
	          `}
	        </style>
	    
	        <style jsx global>
	          {`
	            body {
	              margin: 0;
	              background: #222;
	            }
	          `}
	        </style>
	      </>
	    );
	    
	    
	```
	
	Screenshot  
	![screen.png](https://static.platzi.com/media/user_upload/screen-8af66ef7-fe6e-4f94-b6b5-a635ca2e59c6.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Oscar Lozano** (1)
![reto next.JPG](https://static.platzi.com/media/user_upload/reto%20next-344016c9-af92-42cc-acf6-af55dbb79256.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jaime David Burbano Montoya** (1)

	
	Les comparto mi resultado
	
	**Código**
	``` 
	    export default class extends React.Component{
	        render(){
	            return(
	                <>
	                    <article>
	                        <img src="/static/platzi-logo.png" alt="Logo Platzi"/>
	                        
	                        <h1>CREADO POR JAIME BURBANO</h1>
	                        <p>FRONTEND REACT DEVELOPER</p>
	                    </article>
	    
	                    {/* CSS */}
	                    <style jsx global>{`
	                        body{
	                            margin: 0;
	                            background: linear-gradient(90deg,#1c3643,#273b47 25%,#1e5372);
	                            bakground-repeat: no-repeat;
	                            
	                        }
	                    `}</style>
	    
	                    <style jsx>{`
	                        article {
	                            width: 100vw;
	                            height: 100vh;
	                            user-select: none;
	    
	                            display: flex;
	                            flex-direction: column;
	                            flex-wrap: nowrap;
	                            justify-content: center;
	                            align-content: center;
	                            align-items: center;
	                        }
	    
	                        img {
	                            max-width250px;
	                            margin-bottom: 50px;
	                            pointer-events: none;
	                        }
	    
	                        h1 {
	                            font-weight: bolder;
	                            font-family: Arial, Helvetica, sans-serif;
	                            opacity: .7;
	                            margin-bottom: 0px;
	                            color: white;
	                            transition: all .4s;
	                            cursor: pointer;
	                        }
	    
	                        h1:hover{
	                            opacity: 1;
	                        }
	    
	                        p {
	                            font-weight: bolder;
	                            font-family: Arial, Helvetica, sans-serif;
	                            opacity: .5;
	                            letter-spacing: 2px;
	                            font-size:14px;
	                            color: white;
	                            transition: all .4s;
	                            cursor: pointer;
	                        }
	    
	                        p:hover{
	                            opacity: .8;
	                        }
	    
	                    `}</style>
	                    
	                </>
	            )
	        }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Jaime David Burbano Montoya** (1)
![](https://ibb.co/rxjgJJB)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Ernesto Vizcaíno Alvarado** (1)

	
	Reto cumplido  
	![Captura de Pantalla 2019-12-20 a la\(s\) 9.55.43 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-12-20%20a%20la%28s%29%209.55.43%20p.%C2%A0m.-180646ff-0904-4e10-90fe-8d2bf55f33e6.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Betty Rossana Jimenez Cedeño** (1)

	```
	    <code>
	    import React, { Component } from'react'
	    
	     classAboutextendsComponent{
	      render() {
	        return (
	          <div>
	            <h2>Soy desarrolladora frontend</h2>
	            <p>Aprendiendo next por primera vez</p>
	            <a>bettyjimenez.com</a>
	    
	            <imgsrc="../static/credit-card.png"/>
	          <stylejsx>
	            {`
	            img{
	              width: 32px;
	              height:32px;
	            }
	              h2{
	                color: purple;
	              }
	              p{
	                color: gray;
	              }
	              a{
	                color:white;
	              }
	            `}
	          </style>
	          <stylejsxglobal>{`
	            body {
	              background: red;
	              
	            }
	          `}</style>
	          </div>
	    </code>
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (1)

	
	Reto completado:
	``` 
	    import { Fragment } from "react";
	    
	    const About = () => (
	        <Fragment>
	            <img src="/vikingo.png" alt="Vikingo" />
	            <h1>Creado Por JMZ</h1>
	            <h2>Jugando con NextJS</h2>
	            <style jsx>{`
	                :global(body){
	                  background-color: #272822;
	                }
	                img {
	                  display: block;
	                  margin:50px auto;
	                }
	                h1, h2 {
	                  color:#FFFFFF;
	                  text-align: center;
	                }
	            `}</style>
	        </Fragment>
	    );
	    
	    export default About;
	    
	    
	```
	
	Resultado
	
	![Captura de Pantalla 2019-12-18 a la\(s\) 2.26.52.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-12-18%20a%20la%28s%29%202.26.52-36b66284-4a03-496a-9184-6e6d029a1caa.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (1)

	
	Esta implementación que utiliza `NextJS` es similar a lo que se genera con los `WebComponents` nativos de `JS` ya que me suena familiar lo de que solo los estilos afecten al componente me suena como el  
	`Shadow Dom` de los `WebComponents`.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jhon manuel angulo moncada** (1)

	
	reto cumplido
	``` 
	    export default class extends React.Component {
	        render() {
	            return <div>
	                <img
	                    src="/platzi-logo-small.png"
	                    alt="Platzi logo"
	                />
	                
	                <h1>Creado por Jhon Angulo</h1>
	                <p href="#">Curso de Next.js de Platzi</p>
	                
	                <style jsx>{`
	                    h1 {
	                        color: white;
	                        text-align: center;
	                    }
	                    p {
	                        color: white;
	                        text-align: center;
	                    }
	                    img {
	                        max-width: 20%;
	                        display: block;
	                        margin: 0 auto;
	                    }
	                `}</style>
	                <style jsx global>{`
	                    body {
	                        background: #263238;
	                    }
	                `}</style>
	            </div>
	        }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Manuel Ojeda** (1)

	
	Reto completado!  
	![chrome_1hFsFGS1S1.png](https://static.platzi.com/media/user_upload/chrome_1hFsFGS1S1-39d751de-0aef-440f-8f1c-f05d825e0120.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Alejandro Robleto** (1)

	
	les comparto este link de los codigos de colores html para que les pongan los que gusten  
	<https://html-color-codes.info/codigos-de-colores-hexadecimales/>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Alejandro Robleto** (1)

	
	solo puedo decir wow esta parte del uso de los estilos si que fue genial… me gusto mucho.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **onlinejaime** (1)

	
	¿¿Por qué nadie de todos los que han hecho el reto, ha hecho lo que tocaba??  
	Se supone que hay que hacer una página que, desde el index vaya al about… ¿?  
	En fin…
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **luis_felipe** (1)

	```
	    export default class extends React.Component{
	        render(){
	            return <React.Fragment>
	                <div>
	                    <img src="/static/platzi-logo.png" alt="platzi"/>            
	                    <h3>Created for Felipe Carrasco</h3>
	                    <p>Curso de Next.JS de Platzi!</p>
	                </div>
	                {/** componente en la pagina */}
	                <style jsx>{`
	                h3 {
	                    color: red;
	                    text-align: center;
	                }
	                :global(p) {
	                    color: white;
	                    text-align: center;
	                }
	                img {
	                    max-width: 20%;
	                    display: block;
	                    margin: 0 auto;
	                    padding-top: 10%;
	                }
	                `}</style>
	                {/** componente global */}
	                <style jsx global>{`
	                    body {
	                        background: #145C9E;
	                    }            
	                `}</style>
	            </React.Fragment>
	        }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Alejandro Trejo Cuxim** (1)

	
	Que sencillo parece ser Next.js por ahora.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Houses** (1)

	
	Así me quedo a mi…
	``` 
	    exportdefaultclassextendsReact.Component {
	    	render() {
	    		return (
	    			<div>
	    				<div>
	    					<img src="/static/platzi-logo.png" alt="Plazi" />
	    					<h1>Hola Mundo!</h1>
	    					<p>Bienvenidos al curso papus</p>
	    				</div>
	    				<style jsx>{`
	    					h1 {
	    						color: green;
	    					}
	    
	    					p {
	    						color: green;
	    					}
	    
	    					img {
	    						height: 100px;
	    					}
	    
	    					div {
	    						display: flex;
	    						flex-direction: column;
	    						justify-content: center;
	    						align-items: center;
	    						background: #f3f3f3;
	    						border-radius: 20px;
	    						margin-top: 15%;
	    						padding: 10%;
	    					}
	    				`}</style>
	    
	    				<style jsx global>{`
	    					body {
	    						background: gray;
	    					}
	    				`}</style>
	    			</div>
	    		)
	    	}
	    }```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Manuel Garcia** (1)

	
	Pues, no es mucho pero es trabajo honesto haha…
	``` 
	    export default class extends React.Component{
	        render(){
	            return(
	                <div>
	                    <h2>Listo para ver el server side Rendering!</h2>
	                    <figure className='app_img'>
	                        <img
	                            src='/static/img.jpg'
	                            alt='simple_image'
	                        />
	                    </figure>
	                    <p>Página web creada por ManuelDEV</p>
	                    <style jsx>{`
	                        img {
	                            width: 100%;
	                            height: 100%;
	                            display: block;
	                            margin0 auto;
	                        }
	                        figure{
	                            border-radius: 12px;
	                            overflow: hidden;
	                            width: 120px;
	                            box-shadow: 0px2px5px#0000002;
	                            margin: 0 auto;
	                        }
	                        p,h2{
	                            text-align: center;
	                            font-family: sans-serif;
	                            margin-bottom: 12px;
	                            padding: 5px;
	                            color: white;
	                        }
	                        :global(*){
	                            margin: 0px;
	                            padding: 0px;
	                            box-sizing: border-box;
	                        }
	                        :global(body){
	                            background-color: #2c3e50;
	                        }
	    
	                    `}</style>
	                </div>
	            )
	        }
	    }```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Cesar Octavio de Jesús Meza Carrillo** (1)

	
	Asi es como me quedo a mi:
	``` 
	    export default class extends React.Component{
	        render(){
	            return <div className="contenido">
	                <div className="logo">
	                    <img src="/static/platzi-logo.png" alt="Platzi-Logo"/>
	                </div>
	                <h1>Creado por Cesar Meza!!!  </h1>
	                <p>Estoy emocionado por seguir con este curso!!</p>
	    
	                <style jsx>{`
	    
	                .contenido{
	                    display: flex;
	                    flex-direction: column;
	                    align-items: center;
	                }
	                .logo {
	                    max-width: 50%;
	                    margin: 0 auto;
	                }
	                `}</style>
	                <style jsx global>{`
	                body {
	                    background: gray;
	                    color: white;
	                  
	                }
	                h1 {
	                   font-family: 'Quicksand', sans-serif;
	                }
	                p {
	                    font-family: 'Indie Flower', cursive;
	                }
	                `
	                }</style>
	            </div>
	            
	        }
	    }```
	    
	    Esta muy modesto jejeje.
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Miguel Angel Morales Larriega** (1)

	
	Si utilizas un framework de css en deves de css propio. La manera de importarlo sería en una Master Page.
	
	  1. Creo el archivo Master.js y dentro importo head, que vendría a ser parte de next.
	  2. A travez de link escribo la ruta  
	Ejemplo:
	
	
	
	import Head from ‘next/head’;
	
	export default class extends React.Component{  
	render(props){  
	return(  
	<div>  
	<Head>  
	<title>Proyecto con SSR</title>  
	<link rel=“stylesheet” href=“<https://aquivalaruta>”/>  
	</Head>  
	{props.children}  
	</div>  
	)  
	}
	
	//los props.children es el contenido que va a heredar de cada una de las paginas  
	//y claro importo el MasterPage en mi archivo index, y en todas las demas paginas
	
	**Ahora todo ese código se arriba es muy engorroso, con un sfc me ahorraria mucho mas:
	
	const MasterPage = (props) => (  
	<div>  
	<Head>  
	<title>Proyecto con SSR</title>  
	<link rel=“stylesheet” href=“<https://aquivalaruta>”/>  
	</Head>  
	{props.children}  
	</div>  
	);  
	export default MasterPage
	
	//Al no poner los corchetes y el return, doy por implicito estos
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Arturo Lira Cerda** (1)

	
	Así quedó 😄  
	![](https://postimg.cc/c6J8xVzL)
	``` 
	    export default class extends React.Component {
	        render(){
	            return(
	                <div className="Content">
	                    <div className="logo">
	                        <img src="/static/platzi-logo.png" alt="Platzi Logo" />
	                    </div>
	                    <h1>¡Hola a todos!</h1>
	                    <p>Me emociona comenzar el curso de Next.js</p>
	                    <p>React.js me está gustando muchísimo y me emociona aprender más sobre lo relacionado a este Framework</p>
	                    <div className="techs">
	                        <img src="/static/technologies.png" alt="techs"/>
	                        <img src="/static/nextjs.png" alt="nextjs"/>
	                    </div>
	    
	                    <style jsx>{`
	                        .Content {
	                            height: 100vh;
	                            display: flex;
	                            flex-direction: column;
	                            justify-content: center;
	                            max-width: 300px;
	                            margin: 0 auto;
	                        }
	                        h1 {
	                            color: white;
	                        }
	                        p {
	                            color: white;
	                        }
	                        .logoimg {
	                            width: 150px; 
	                            display: block;
	                            margin: 50px auto;
	                        }
	                        .techsimg {
	                            width: 100%;
	                            margin-top: 15px;
	                        }
	                    `}</style>
	    
	                    <style jsx global>
	                        {`
	                        body {
	                            background: #1A2A35;
	                            text-align: center;
	                            font-family: Arial;
	                        }
	                        `}
	                    </style>
	                </div>
	            )
	        }
	    }```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Arturo Lira Cerda** (1)

		
		![Y así se ve](https://postimg.cc/c6J8xVzL)  
		[](https://postimg.cc/c6J8xVzL)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Luis Arturo Lira Cerda** (1)

		
		Ay, no salió bien, dejo el link:  
		<https://postimg.cc/c6J8xVzL>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Jhon Alexander Perez Valencia** (1)

	
	se puede usar sass, stylus, etc?  
	en el caso de que si, deberían ser globales?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jorge Velasquez** (1)

	
	My solution  
	![reto1.png](https://static.platzi.com/media/user_upload/reto1-631afd2b-9307-43b3-8270-f9946c44ee90.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Cristihan Albarran** (1)

		
		nice!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **RBN1993** (1)

	
	Hola, a alguien más le aparece este error en la consola del navegador: [](index.js:1 Warning: the ‘url’ property is deprecated. <https://err.sh/zeit/next.js/url-deprecated>)  
	Si alguno lo ha resuelto, ¿me puede decir cómo? gracias.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **jobcoronadoduran** (2)

		
		este error aparece porque podrías estar utilizando un ancla sin envolverlo con un Link esto puedes verlo mejor con esta clase.  
		<https://platzi.com/clases/1311-next-js/12078-utilizando-ampltlinkampgt/>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **jobcoronadoduran** (2)

		
		También sucede cuando cuando tienes React Dev Tools activado
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **RBN1993** (1)

		
		Gracias, pero me parece que actualizando el package.json se solucionó. Ya acabe el curso y no lo he podido comprobar.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **alexjcm** (1)

	
	Tarea cumplida!  
	![](https://i.postimg.cc/XvGZpLBQ/nextjs.png)
	``` 
	    exportdefaultclassextendsReact.Component{
	      render() {
	        return (
	          <div>
	            <center>
	              <h1>HOME</h1>
	              <imgsrc="/static/logo-nextjs.webp"alt="NextJs" />
	            </center>
	            <stylejsx>   {`
	                h1 {
	                  color: #ec47cb;
	                }
	                img {
	                  max-width: 45%;
	                  display: block;
	                  margin: 0 auto;
	                }  `}
	            </style>
	            <stylejsxglobal>  {`
	                body {
	                  background-image: url("/static/fondo.jpg");
	                } `}
	            </style>
	          </div>
	        );
	      }
	    }
	    
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jessica Tatiana Camacho** (1)

	
	mi página
	``` 
	    exportdefaultclassextendsReact.Component{
	      render() {
	        return (
	          <div>
	            <imgsrc="/static/logo-misal.png"alt="logo" />
	            <divclassName="wrapper">
	    
	              <h1>Esta página fue hecha por Tatiana</h1>
	              <p>Bienvenidos a Misal.co</p>
	            </div>
	    
	            <stylejsx>{`
	            p{
	              font-size:16px;
	              color:black;
	             
	            }
	            img{
	              max-width:50%;
	              margin:0 auto;
	              display:block
	            }
	    
	            .wrapper{
	              display:flex;
	              flex-direction:column;
	              align-items:center
	            }
	            `}</style>
	            <stylejsxglobal>{`
	            body{
	              background-color:white;
	              
	            }
	            `}</style>
	          </div>
	        )
	      }
	    }```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Adrian Avila** (1)

	```
	           <style jsx>{`
	              img {
	                max-width: 220px;
	              }
	              .brandNamep {
	                font-size: 45px;
	                font-style: normal;
	                font-variant: normal;
	                line-height: 49.5px;
	                font-family: 'Helvetica Neue';
	                display: inline;
	              }
	              .keller {
	                color: #ccc;
	                font-weight: 400;
	                margin: -3.5px;
	              }
	              .williams {
	                color: #666;
	                font-weight: 150;
	                margin: 3.5px;
	              }
	              .principal {
	                width: 345px;
	                margin: 0 auto;
	              }
	            `}</style>
	    
	            {/* <style jsx global>
	              {`
	                body {
	                  background: #2a2e31;
	                }
	              `}
	            </style> */}
	    
	```
	
	![reto](https://i.imgur.com/lxHKk7S.png)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Gerardo Manuel Reyes Fernández** (1)

	
	Tiene alguna desventaja o consideración usar server side rendering a parte de lo de las apis?  
	Se me ocurre que en caso de tener millones de usuarios tendríamos que tener más servidores que con client side rendering(ejemplo).  
	Me gustaría saber cuando si y cuando no o si siempre es preferible usar Server Side Rendering
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eduardo Hidalgo Díaz Rugama** (3)

		
		Siempre es preferible usar Server Side Rendering.
		
		El problema de “CSR” (Client side rendering) es que nunca vas a poder optimizar tu página al 100%. Debido a que cargas tu html vacio, y luego cargas el js con el que viene React (o lo que sea), tu SEO no viene incluido. Tu contenido no viene incluido. Viene un html vacio.
		
		En consecuencia, los indexadores como google no pueden hacer scraping de tu página y decirle al mundo el bonito contenido que tienes porque reciben una página vacía.
		
		Otro problema es que eso trae mala experiencia de usuario. Tus usuarios siempre van a ver una página sin cargar en el TTFB. Verán que cargó el contenido, pero no lo pinta.
		
		Hoy en día no te tienes que preocupar por tener 100 servidores. Eso no es un problema. Estuve en una empresa donde recibian 10 millones de views en tráfico y lo soportaban con 4 servers internos. Luego se migraron a azure y con 2 servers les bastaba.
		
		Concentrate en seguir aprendiendo y en probar todo. No te cases con CSR o SSR, aprende ambos y analízalos. Olvida riesgos de escalabilidad. Eso lo aprenderás a su tiempo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **MichaelSornoza** (1)
![](https://lh4.googleusercontent.com/3VMctI-Wesxk2d3TdOEoKubMX4oA-im916BtvUUuHWMLMIoIUKkbg3g_Diua0wC_ZEn3IuM9_WzORA=w1366-h667)
	``` 
	    exportdefaultclassextendsReact.Component {
	      render () {
	        return (
	          <div>
	            <picture>
	              <img src="/static/platzi-logo.png" />
	            </picture>
	            <div className="TextContent">
	              <h2>Realizado por <a>@MichaelSornoza</a></h2>
	              <p>Práctica del curso Next.js de Platzi.com</p>
	            </div>
	    
	            <style jsx>{`
	              .TextContent {
	                align-items: center;
	                display: flex;
	                flex-direction: column;
	                color: white;
	              }
	              img {
	                max-width: 10%;
	                display: block;
	                margin: 50px auto;
	              }
	    
	            `}</style>
	            <style jsx global>{`
	              body {
	                background-color: #224A62;
	              }
	            `}</style>
	          </div>
	        )
	      }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **s99sergio** (1)

	
	Hola, soy nuevo por aqui XD, me esta encantando este curso, solo tengo una duda algo tonta XD, ¿Como se saca el simbolo ` en el teclado? D:
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **happiestack** (1)

		
		Ahi depende totalmente de tu teclado fisico y el idioma en que este configurado. Intenta usando ascii con alt+96 o alt+60
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Efrén Sánchez** (1)

	
	Yo hice un Time line: 👇🏼👇🏼
	``` 
	    <div>
	    
	          <div class="container">
	            <div class="jumbotron">
	              <h1>Dr. Norman Borlaug</h1>
	              <h2><em>The man who saved a billion lives</em></h2>
	              <div class="thumbnail"><img src="https://c2.staticflickr.com/4/3689/10613180113_fdf7bcd316_b.jpg"/>
	                <p class="caption">Dr. Norman Borlaug, third from left, trains biologists in Mexico on how to increase wheat yields - part of his life-long war on hunger.</p>
	              </div>
	              <div class="hero">
	                <h3>Time line of Dr. Borlaug's life:</h3>
	                <ul>
	                  <li><strong>1914</strong> - Born in Cresco, Iowa</li>
	                  <li><strong>1933</strong> - Leaves his family's farm to attend the University of Minnesota, thanks to a Depression era program known as the "National Youth Administration"</li>
	                  <li><strong>1935</strong> - Has to stop school and save up more money. Works in the Civilian Conservation Corps, helping starving Americans. "I saw how food changed them", he said. "All of this left scars on me."</li>
	                  <li><strong>1937</strong> - Finishes university and takes a job in the US Forestry Service</li>
	                  <li><strong>1938</strong> - Marries wife of 69 years Margret Gibson. Gets laid off due to budget cuts. Inspired by Elvin Charles Stakman, he returns to school study under Stakman, who teaches him about breeding pest-resistent plants.</li>
	                  <li><strong>1941</strong> - Tries to enroll in the military after the Pearl Harbor attack, but is rejected. Instead, the military asked his lab to work on waterproof glue, DDT to control malaria, disenfectants, and other applied science.</li>
	                  <li><strong>1942</strong> - Receives a Ph.D. in Genetics and Plant Pathology</li>
	                  <li><strong>1944</strong> - Rejects a 100% salary increase from Dupont, leaves behind his pregnant wife, and flies to Mexico to head a new plant pathology program. Over the next 16 years, his team breeds 6,000 different strains of disease resistent wheat - including different varieties for each major climate on Earth.</li>
	                  <li><strong>1945</strong> - Discovers a way to grown wheat twice each season, doubling wheat yields</li>
	                  <li><strong>1953</strong> - crosses a short, sturdy dwarf breed of wheat with a high-yeidling American breed, creating a strain that responds well to fertalizer. It goes onto provide 95% of Mexico's wheat.</li>
	                  <li><strong>1962</strong> - Visits Delhi and brings his high-yielding strains of wheat to the Indian subcontinent in time to help mitigate mass starvation due to a rapidly expanding population</li>
	                  <li><strong>1970</strong> - receives the Nobel Peace Prize</li>
	                  <li><strong>1983</strong> - helps seven African countries dramatically increase their maize and sorghum yields</li>
	                  <li><strong>1984</strong> - becomes a distinguished professor at Texas A&M University</li>
	                  <li><strong>2005</strong> - states "we will have to double the world food supply by 2050." Argues that genetically modified crops are the only way we can meet the demand, as we run out of arable land. Says that GM crops  are not inherently dangerous because "we've been genetically modifying plants and animals for a long time. Long before we called it science, people were selecting the best breeds."</li>
	                  <li><strong>2009</strong> - dies at the age of 95.</li>
	                </ul>
	                <blockquote>
	                  <p>"Borlaug's life and achievement are testimony to the far-reaching contribution that one man's towering intellect, persistence and scientific vision can make to human peace and progress."</p>
	                  <footer><cite>-Indian Prime Minister Manmohan Singh</cite></footer>
	                </blockquote>
	                <h3>If you have time, you should read more about this incredible human being on his <a href="https://en.wikipedia.org/wiki/Norman_Borlaug" target="_blank">Wikipedia entry</a>.</h3>
	              </div>
	            </div>
	              <footer class="footer">
	                <p>Written by:</p>
	              </footer>
	          </div>
	    
	          <style jsx>{`
	            h1{ text-align: center; }
	            h2{ text-align: center; }
	            h3{ text-align: center; }
	            p{ text-align: center; }
	            li{ margin-bottom: .5rem; }
	            img{ display: block; margin: 0 auto; width: 50%; }
	            ul{ padding: 5%; }
	            `}
	          </style>
	    
	          <style jsx global>{`
	            body{ margin-top: 60px; font-size: 1.5em; }
	          `}</style>
	    
	        </div>
	    
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Andres Rodriguez Escudero** (1)

		
		Y como se ve?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Julio Gutierrez** (1)

	```
	    exportdefaultclassextendsReact.Component{
	        render(){
	            return<div>
	                <h1>Hola Mundo</h1>
	                <p>Bienenidos al Curso de Next.js</p>
	                <p>Enviar</p>
	                <stylejsx>{`
	                h1 {
	                    color: red;
	                }
	                :global(div p) {
	                    color: green;
	                }
	                `}</style>
	    
	                <stylejsxglobal>{`
	                body {
	                    background: yellow;
	                }
	                `}</style>
	    
	            </div>
	        }
	    }```
	    
	    
	    De esta forma :global(div p)
	    Configura a que todos los p dentro de divs de toda nuestra aplicación deben de tener este estilo.
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Julio Gutierrez** (1)

	```
	    exportdefaultclassextendsReact.Component{
	        render(){
	            return<div>
	                <h1>Hola Mundo</h1>
	                <p>Bienenidos al Curso de Next.js</p>
	                <p>Enviar</p>
	                <stylejsx>{`
	                h1 {
	                    color: red;
	                }
	                div :global(p) {
	                    color: green;
	                }
	                `}</style>
	    
	                <stylejsxglobal>{`
	                body {
	                    background: yellow;
	                }
	                `}</style>
	    
	            </div>
	        }
	    }```
	    
	    Todas las <p> que se encuentren dentro de <div> tendrán este estilo
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Julio Gutierrez** (1)

	
	**< style jsx>** Solo se puede crear estilo por el componente activo.
	
	**<style jsx global> ** Con este se puede crear estilo a toda la pagina.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **ma_angelica_romero** (1)

	
	Que carrusel puedo usar en nextjs?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **nandoalvarado092** (1)

		
		¡Hola! estuve revisando y encontre este muy bueno.  
		<https://www.npmjs.com/package/react-responsive-carousel>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **nandoalvarado092** (1)

		
		En realidad me lo recomendó un amigo, antes solía utilizar el owl-carousel, pero como me comento el, tiene la dependencia de jQuery.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **eltenis** (1)

	
	Como se puede añadir un libreria como bootstrapp??? ya que no se donde poner el link he instalado en npm bootrstapp pero no hace nada
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Minei** (1)

	
	Si tengo estilos globales, ¿en qué parte me recomiendan ponerlo? ¿En un archivo css aparte? ¿como un Style JSX en el primer componente?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (1)

	
	¿Cómo prueban el código para que se vea así en la imagen del celular? 😮
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **ricardocelis (Platzi)** (2)

		
		Hola william en google chrome simplemente haciendo la ventana de ese tamaño, pero si quieres tener tamaños más expecíficos presiona F12, y haz click en el siguiente ícono:
		
		![iconodeformasDePantalla.PNG](https://static.platzi.com/media/user_upload/iconodeformasDePantalla-38b52674-514a-4ffa-b621-eee4f2eac94f.jpg)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **WilliamVelazquez** (0)

		
		Gracias Celis! ¿Y si me gustaría que apareciera de fondo el móbil (en este caso el iPhone)?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Imderf** (2)

		
		Sencillo:  
		1.- Lo primero que haces, será abrir Chrome, y pruebas con una URL cualquiera
		
		2.- Ahora haces click derecho sobre cualquier parte del sitio, y seleccionas la opción “Inspeccionar elemento”. O Simplemente F12
		
		3- Aparecerá una ventana a la derecha o en la parte inferior de tu pantalla. En la parte superior a la izquierda de esta ventana verás dos iconos pequeños.
		
		4- Da click en el segundo icono que tiene forma de un smartphone o tablet.
		
		Allí tendrás para emular diferentes dispositivos. Puedes elegir el tamaño de la pantalla en la barra horizontal de la parte superior. Esta barra te permitirá de probar en diversas resoluciones, como el Nexus 5X, iPhone 6 o iPad Pro ect…
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (4)

		
		La mejor forma de hacer esto es usando el emulador de [Android Studio](https://developer.android.com/studio/), que viene con imágenes que emulan perfectamente un Pixel 2/Nexus 5X/etc.  
		También las podés conectar con tu Chrome para poder debuggear en un device real, lo que es genial para resolver problemas específicos de Android o iOS.
		
		Si tenés Mac, [XCode](https://developer.apple.com/xcode/) tiene una herramienta idéntica que emula cualquier iPhone, y es la que usé para armar las capturas el curso.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **WilliamVelazquez** (0)

		
		Muchas gracias @robertomgonzalez 😃  
		Gracias por el excelente curso!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **edwintrumpet** (1)

		
		Puede abrir la aplicación conectando el celular a la misma red wifi que está conectado el computador en el que lo está desarrollando.  
		Pero ahí no servirá poner localhost sino tiene que poner la dirección de ip local que le pertenece a su computador en esa red.  
		En windows se consigue por consola con el comando ipconfig y en linux con ifconfig.  
		Es un número que empieza con 192.168.0…  
		Y no olvidar poner el puerto 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Wladimir Hernández** (1)

	
	Reto Cumplido
	``` 
	    exportdefaultclassextendsReact.Component {
	      render() {
	        return (
	          <div>
	            <div className="container">
	              <img src="/static/platzi-logo.png" alt="Platzi"/>
	              <h1>Creado por Wladimir Hernández</h1>
	              <p>Para el Curso de Next.js de Platzi</p>
	            </div>
	            <style jsx>
	              {`
	                .container {
	                  font-family: 'Avenir', Helvetica, Arial, sans-serif;
	                  display: flex;
	                  flex-direction: column;
	                  height: 100%;
	                  align-items: center;
	                  justify-content: space-around;
	                }
	                h1 {
	                  color: #fff;
	                  font-size: 60px;
	                }
	                 p {
	                  color: #fff;
	                  font-size: 40px;
	                  text-align: center;
	                }
	                img {
	                  max-width: 20%;
	                  display: block;
	                  margin: 0 auto;
	                }
	              `}
	            </style>
	    
	            <style jsx global>
	              {`
	                body {
	                  background: #1c3643;
	                }
	              `}
	            </style>
	          </div>
	        );
	      }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **José Antonio aparicio gallego** (1)
A mí me gustaría saber donde está ubicado tsconfig
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Erik Ochoa (Platzi)** (1)

		
		Esa es una buena pregunta, imagino que en algún directorio dentro de node_modules y de nextjs 🤔pero… ¿para qué quieres saber? creo que si quieres modificar la configuración default lo que debes hacer es crear tu propio tsconfig en el directorio raíz de tu proyecto.
		
		Aquí la [documentación](https://nextjs.org/docs/basic-features/typescript) al respecto.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Jaime David Burbano Montoya** (1)
Si los estilos se manejan de esta manera, ¿Significa que puedo ponerle la misma clase a diferentes etiquetas en diferentes componentes y ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Juan David Castro (Platzi)** (1)

		
		¡Hola, Jaime!
		
		Significa que tus estilos solo se van a aplicar a los elementos de tu componente y no en el resto de la aplicación. Aunque también existe una opción para darle estilos a elementos de cualquier parte del documento. Pásate un rato por estas lecturas:
		
		  * <https://github.com/zeit/styled-jsx#getting-started>
		  * <https://github.com/zeit/styled-jsx#global-styles>
		
		
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Ramiro Nicolas D'Accorso Rosati** (1)
Estoy teniendo problemas: al aplicar estilos globales, dejan de funcionar los estilos comunes. Porque sera? Dejo mi codigo. export ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Ramiro Nicolas D'Accorso Rosati** (1)

		
		Solved! no me den bola!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Miguel Rivera** (1)
Como puedo intrducir una hoja de estilos global antes del cierre de html, o como se puede evitar el render blocking de google page insights
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jhon Alexander Perez Valencia** (1)
se puede usar sass, stylus, etc? en el caso de que si, deberían ser globales?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **RBN1993** (1)
Hola, a alguien más le aparece este error en la consola del navegador: [](index.js:1 Warning: the ‘url’ property is deprecated. 
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **jobcoronadoduran** (2)

		
		este error aparece porque podrías estar utilizando un ancla sin envolverlo con un Link esto puedes verlo mejor con esta clase.  
		<https://platzi.com/clases/1311-next-js/12078-utilizando-ampltlinkampgt/>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Gerardo Manuel Reyes Fernández** (1)
Tiene alguna desventaja o consideración usar server side rendering a parte de lo de las apis? Se me ocurre que en caso de tener millones ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eduardo Hidalgo Díaz Rugama** (3)

		
		Siempre es preferible usar Server Side Rendering.
		
		El problema de “CSR” (Client side rendering) es que nunca vas a poder optimizar tu página al 100%. Debido a que cargas tu html vacio, y luego cargas el js con el que viene React (o lo que sea), tu SEO no viene incluido. Tu contenido no viene incluido. Viene un html vacio.
		
		En consecuencia, los indexadores como google no pueden hacer scraping de tu página y decirle al mundo el bonito contenido que tienes porque reciben una página vacía.
		
		Otro problema es que eso trae mala experiencia de usuario. Tus usuarios siempre van a ver una página sin cargar en el TTFB. Verán que cargó el contenido, pero no lo pinta.
		
		Hoy en día no te tienes que preocupar por tener 100 servidores. Eso no es un problema. Estuve en una empresa donde recibian 10 millones de views en tráfico y lo soportaban con 4 servers internos. Luego se migraron a azure y con 2 servers les bastaba.
		
		Concentrate en seguir aprendiendo y en probar todo. No te cases con CSR o SSR, aprende ambos y analízalos. Olvida riesgos de escalabilidad. Eso lo aprenderás a su tiempo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **s99sergio** (1)
Hola, soy nuevo por aqui XD, me esta encantando este curso, solo tengo una duda algo tonta XD, ¿Como se saca el simbolo ` en el teclado? D:
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **happiestack** (1)

		
		Ahi depende totalmente de tu teclado fisico y el idioma en que este configurado. Intenta usando ascii con alt+96 o alt+60
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Sebastian Cardoso Castillo** (0)

	
	Que temas de colores esta usando para Visual Studio? A mi me muestra el CSS todo del mismo color.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Danvasem** (1)

		
		Para que te aparezca con los colores pintados tienes que instalar en VSCode la siguiente extensión: [](https://marketplace.visualstudio.com/items?itemName=blanu.vscode-styled-jsx)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Danvasem** (1)

		
		<https://marketplace.visualstudio.com/items?itemName=blanu.vscode-styled-jsx>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Danvasem** (1)

		
		Si quieres habilitar también el auto-completado en styled jsx entonces debes instalar este otro plugin:  
		<https://marketplace.visualstudio.com/items?itemName=AndrewRazumovsky.vscode-styled-jsx-languageserver>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **hakutravel** (0)
Buenos dias, estoy enlasando la imagen de la carpeta static pero no me lo muestra
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Rafa Jiménez** (2)

		
		Hola,
		
		Como se hace en el curso esta obsoleto, tienes que crear una carpeta public y dentro poner la de static, pero no hace falta que cambies el src, te dejo el enlace donde lo explica
		
		<https://github.com/zeit/next.js/blob/master/errors/static-dir-deprecated.md>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

# Server Side Rendering

## 0040. ¿Qué es Server Side Rendering

### Descripción:


En esta clase vamos a ver el concepto de Server Side Rendering que es una de las features más importantes que tiene Next y nos ayuda a mejorar la performance de nuestro sitio, la experiencia de usuario y algo muy importante; el tema de SEO y sharing.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Sergio Minei** (14)

	
	## Server Side Rendering
	
	![Client Side Rendering](https://raw.githubusercontent.com/MineiToshio/CursosPlatzi/master/Curso%20de%20Next.js/img/client-side-rendering.png)
	
	Con el **Client Side Rendering** , el usuario debe de esperar un tiempo significativo para poder ver la aplicación. Esto se debe a que primero debe de descargar todo el JS y luego esperar a que cargue para poder visualizar algo.
	
	![Server Side Rendering](https://raw.githubusercontent.com/MineiToshio/CursosPlatzi/master/Curso%20de%20Next.js/img/server-side-rendering.png)
	
	Con el **Server Side Rendering** , el servidor ya envía una HTML con CSS y, por ende, el usuario tiene que esperar mucho menos para tener una primera vista de la aplicación.
	
	**¿Qué ventajas tiene?**
	
	  * Mejor Performance.
	  * Indexa en todos los servicios.
	
	
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **onlinejaime** (2)

		
		Sergio Minei… ¿Quieres ser mi amigo? 😉
		
		Brutal la currada que te has pegado. Pasas a ser mi nº 1 en Platzi.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Manuel Garcia** (3)

	
	Client Side Rendering < Server Side Rendering
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **brapastor** (3)

	
	puedo usar next js con otro framework como django o laravel?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Si, es posible, la forma más sencilla de implementarlo es usando django o laravel como api.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **brapastor** (1)

		
		Pero en produccion tendria que correr next, enves de django o laravel verdad 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Debes correr los dos, next para que sirva el front de tu aplicación y django o laravel para que sirva el api.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **David Antonio Ordóñez Cornejo** (3)

	
	No queda clara la diferencia.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (20)

		
		La principal diferencia entre Server Side Rendering y Client Side Rendering es que **con SSR el server envía el HTML con todo el contenido listo para renderizar**. Esto es mucho más performante (ya que para nuestro browser es como si fuese un sitio estático) e indexa mejor en buscadores, ya que podemos acceder a todo el contenido fácilmente con curl/wget.
		
		En comparación, con CSR tradicional el server manda un HTML vacío, y tenemos que descargar toda la aplicación y esperar que haga lo suyo para poder empezar a ver el contenido. Esto es mucho más lento y requiere un browser que ejecute JS para funcionar correctamente.
		
		Next.JS usa una mezcla de los dos: SSR para la carga inicial (por ser más rápido), y CSR cada vez que clickeamos en un link con la app inicializada, ya que ahí puede aplicar varias optimizaciones y mecanismos de precarga que hacen que todo funcione lo más rápido posible.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **David Antonio Ordóñez Cornejo** (1)

		
		Ok, gracias por el complemento.
		
		Creo que experimenté una espiral generacional, en mis tiempos la novedad era AJAX vs los sitios que se cargaban por completo del lado del server, pero ahora veo que la historia se ha invertido. Lo interesante es que next hace como lo mencionas, un híbrido de las dos maneras y explota sus ventajas en performance y SEO.
		
		Saludos!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Julio J Yépez** (5)

		
		Hola @davidherzlos,  
		Creo que tienes un poco mezclados los conceptos acá … AJAX tiene que ver con asincronicidad … listo. Es el génesis de todo lo asíncrono … ergo … fetch.
		
		SSR tiene más que ver con el First Load Rendering y Time To Interactive … no todo se renderiza del lado del servidor como se hacía antes con PHP o ASP …
		
		Acá la clave está en esos primeros 2 o 3 segundos en cargar algo que el usuario pueda ver y tocar…
		
		Yo lo comparo más con el ob_flush() de PHP … el manejo del buffering de salida de php para mí tiempo un poco más de relación que ajax.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Brian Bentancourt** (2)

	
	hola, tengo una aplicacion react sin next, estoy teniendo problemas para compartir mi url en facebook. puedo generar un html con next solo con los meta tags y luego desde el cliente sigo usando react como siempre?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		¡Hola! NextJS se encarga de procesar este tipo de peticiones, las meta tags son del SEO y cuando Next hace el build compila en archivos estáticos para que el SEO pueda ser mucho mejor
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **WSJedp** (1)

	
	¿Next puede ser utilizado con Express? Es decir, ¿Se podría crear en Next una API dentro del mismo sitio?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Enrique Devars (Platzi)** (1)

	
	server side rendering
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Adriann Felipe Sanchez Sierra** (1)

	
	Gran explicación! 😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (1)

	
	Gran feature de Next! Es lo principal por lo que quería que el curso estuviera disponible! 😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Brian Bentancourt** (1)
hola, tengo una aplicacion react sin next, estoy teniendo problemas para compartir mi url en facebook. puedo generar un html con next sol...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		¡Hola! NextJS se encarga de procesar este tipo de peticiones, las meta tags son del SEO y cuando Next hace el build compila en archivos estáticos para que el SEO pueda ser mucho mejor
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0050. Intro a getInitialProps

### Descripción:


En esta clase vamos a ver la función getInitialProps de Next, que nos permite cargar el contenido principal de la página cuando tenemos que recurrir a una API.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Links:

* [platzi-nextjs/index.js at 3.getInitialProps · Aerolab/platzi-nextjs · GitHub](https://github.com/Aerolab/platzi-nextjs/blob/3.getInitialProps/pages/index.js)

### Comentarios:

* **Sergio Minei** (10)

	
	## getInitialProps
	
	La función getInitialProps nos permite cargar el contenido principal de la página cuando tenemos que recurrir a una API.
	``` 
	    staticasync getInicialProps() {
	      //aquí traemos los datos
	      let request = await fetch('url')
	      let datos = await request.json()
	      return { datos }
	    }
	    
	```
	
	Luego de cargar los datos, los va a agregar a los props de React.
	
	`getInitialProps()` solamente funciona en pages y es parte de next.js. No va a funcionar con otras librerías o frameworks.
	
	Cuando se trabaja con **Server Side Rendering** , algunos métodos dejan de funcionar. Esto se debe a que la función ya no está corriendo por el navegador sino desde el servidor.
	
	En este caso, vamos a instalar **isomorphic-fetch** que nos va a permitir usar fetch desde node.js.
	``` 
	    $ npm add isomorphic-fetch
	    
	```
	
	Para usarlo, solo debe de importarse.
	``` 
	    import'isomorphic-fetch';
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Fernando Berrio Meza** (2)

		
		muchas gracias
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Minei** (2)

		
		gracias a ti @Digbemez
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Carlos Rivas** (2)

		
		Tus resumenes siempre me ayudan a no parar el video para copiar los tips, sos grande @MineiToshio
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Minei** (1)

		
		Gracias @carlsrivs! Me alegra mucho saber que los resúmenes son de ayuda 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Georgie Duarte** (2)

		
		si @MineiToshio de verdad gracias me han servido muchos tus apuntes en diversos cursos.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Minei** (1)

		
		Qué bueno que te estén ayudando los resúmenes @GeoD! 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Neira Steven** (2)

		
		es getInitialProps, gracias por tus aportes
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **elvis-retiz** (4)

	
	¿Alguien que me pueda decir porque me ocurre eso? Anexo codigo mas abajo
	
	![error.jpg](https://static.platzi.com/media/user_upload/error-244ac4a6-21f2-44a1-bfc3-b21cdabe4c54.jpg)
	``` 
	    import"isomorphic-fetch";
	    
	    exportdefaultclassextendsReact.Component{
	      staticasync getInitialProps() {
	        let req = await fetch("https://api.audioboom.com/channels/recommended");
	        let { body: channels } = await req.json();
	        console.log({ channels });
	        return { channels };
	      }
	    
	      render() {
	        const { channels } = this.props;
	        return (
	          <React.Fragment>
	            <header>Podcast</header>
	    
	            {channels.map(channel => {
	              <div>{channel.title}</div>;
	            })}
	    
	            <stylejsx>{`
	              header {
	                color: #fff;
	                background: #8756ca;
	                padding: 15px;
	                text-align: center;
	              }
	            `}</style>
	    
	            <stylejsxglobal>{`
	              body {
	                margin: 0;
	                font-family: system-ui;
	                background-color: white;
	              }
	            `}</style>
	          </React.Fragment>
	        );
	      }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **RBN1993** (3)

		
		Parece ser que es por que se usa un <a></a> sin un <Link> miralo aquí. <https://platzi.com/clases/1311-next-js/12078-utilizando-ampltlinkampgt/> , pregunté lo mismo en esta clase <https://platzi.com/clases/1311-next-js/12075-styled-jsx/> y me respondieron muy tarde, no se con certeza si es verdad por que ya acabe el curso.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **RBN1993** (3)

		
		Recuerdo que actualice mi package.json y se me quitó, si encuentras la respuesta dimelo, gracias.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Miguel Angel Morales Larriega** (1)

		
		Veo que estas escribiendo codigo junto, esa debe de ser la razon
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Gregorio Garcia** (4)

	
	Si quisieramos utilizar las variables de css ¿sería de éste modo o hay una mejor manera?
	
	![global.png](https://static.platzi.com/media/user_upload/global-8e7c15c1-cd9f-4f8a-a6ba-2f1a39297cf0.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Juan David Castro (Platzi)** (10)

		
		Ya que estas usando template literals ( **`** ) puedes usar variables nativas de JavaScript 😛 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Georgie Duarte** (2)

		
		tamb puedes agregar sass o style a next y usar variables en el css
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **edwintrumpet** (3)

	
	Si están usando componentes funcionales y el getInitialProps les está dando dificultades pueden hacerlo de esta manera…
	``` 
	    import { Fragment } from'react'
	    import'isomorphic-fetch'
	    
	    functionHome({ channels }) {
	        return (
	            <Fragment>
	                <header>Podcast</header>
	    
	                {
	                    channels.map(channel => <div>{channel.title}</div>)
	                }
	    
	                <stylejsx>{`
	                    header {
	                        color: #FFF;
	                        background: #8756CA;
	                        padding: 15px;
	                        text-align: center;
	                    }
	                `}</style>
	    
	                <stylejsxglobal>{`
	                    body {
	                        margin: 0;
	                        font-family: system-ui;
	                        background: white;
	                    }
	                `}</style>
	            </Fragment>
	        )
	    }
	    
	    Home.getInitialProps = async () => {
	        const req = await fetch('https://api.audioboom.com/channels/recommended')
	        const { body: channels } = await req.json()
	        return { channels }
	    }
	    
	    exportdefault Home;
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Miguel Rodriguez** (1)

		
		Agregando Doc por si alguien tiene dudas  
		[Fetching data and component lifecycle](https://nextjs.org/docs#fetching-data-and-component-lifecycle)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Antonio Nicasio** (3)

	
	excelente curso muy bien explicado
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Sánchez** (2)

	
	Si están usando Next.js 9.3 o que sea más nuevo. En su [documentación de getInitialProps()](https://nextjs.org/docs/api-reference/data-fetching/getInitialProps) recomiendan usar [getServerSideProps()](https://nextjs.org/docs/basic-features/data-fetching#getserversideprops-server-side-rendering) o [getStaticProps()](https://nextjs.org/docs/basic-features/data-fetching#getstaticprops-static-generation).
	
	La principal diferencia entre ambas funciones es que `getServerSideProps()` se llama en cada carga de página, mientras que `getStaticProps()` solo es llamada al momento de hacer build. Con esto anterior ya claro, sabemos que debemos usar `getServerSideProps()` para hacer lo que el profesor hizo esta clase.
	
	Mi codigo usando `getServerSideProps()` quedo de esta forma:
	``` 
	    import 'isomorphic-fetch';
	    
	    function App({ channels }) {
	      return (
	        <>
	          <header>Podcasts</header>
	    
	          <div className="channels">
	            {channels.map(channel => (
	              <div className="channel">
	                <img src={channel.urls.logo_image.original} alt="" />
	                <h2>{channel.title}</h2>
	              </div>
	            ))}
	          </div>
	    
	          <style jsx>{`
	            header {
	              color: #fff;
	              background: #8756ca;
	              padding: 15px;
	              text-align: center;
	            }
	    
	            .channels {
	              display: grid;
	              grid-gap: 15px;
	              padding: 15px;
	              grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
	            }
	    
	            .channel {
	              display: block;
	              border-radius: 3px;
	              box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.15);
	              margin-bottom: 0.5em;
	            }
	    
	            .channel img {
	              width: 100%;
	            }
	    
	            .channel h2 {
	              padding: 5px;
	              font-size: 0.9em;
	              font-weight: 600;
	              margin: 0;
	              text-align: center;
	            }
	          `}</style>
	    
	          <style jsx global>{`
	            body {
	              margin: 0;
	              background: white;
	              font-family: system-ui;
	            }
	          `}</style>
	        </>
	      );
	    }
	    
	    export async function getServerSideProps() {
	      let req = await fetch('https://api.audioboom.com/channels/recommended');
	      let { body: channels } = await req.json();
	    
	      return { props: { channels: channels } };
	    }
	    
	    export default App;
	    
	```
	
	Si tienen alguna duda sobre el codigo me pueden preguntar o ir a la documentación de Next.js.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (2)

	
	Separe el código un poco para poder apreciar mejor lo que esta pasando.
	
	Separe los estilos en un script llamado** component-style.js** lo curioso es que los estilos los toma correctamente pero no toma el **:global(body)** pero si lo coma cuando utilizo esto **< style jsx global>** y al usar un **literal string** use una variable para para el color .
	``` 
	    const COLOR = "#1d76db";
	    exportdefault (
	        <stylejsx>
	            {`
	                :global(body){
	                  padding: 0;
	                  margin: 0;
	                }
	                header {
	                  background-color: ${COLOR};
	                  color: white;
	                  padding: 15px;
	                  text-align: center;
	                }
	                .channels {
	                  display: grid;
	                  grid-gap: 15px;
	                  padding: 15px;
	                  grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
	                }
	                a.channel {
	                  display: block;
	                  margin-bottom: 0.5em;
	                  color: #333;
	                  text-decoration: none;
	                }
	                .channel img {
	                  border-radius: 3px;
	                  box-shadow: 0px 2px 6px rgba(0,0,0,0.15);
	                  width: 100%;
	                }
	                h2 {
	                  padding: 5px;
	                  font-size: 0.9em;
	                  font-weight: 600;
	                  margin: 0;
	                  text-align: center;
	                }
	            `}
	        </style>
	    );
	    
	```
	
	Este es el código del componente que estamos probando durante la clase, coloque algunos comentarios espero les funcionen de guia 😸.
	``` 
	    import React, { Fragment } from"react";
	    import"isomorphic-fetch";
	    
	    import StyleJSX from"./component-style";
	    
	    const API = "https://api.audioboom.com/channels/recommended?api_version=2";
	    
	    /**
	     * Muestra el listado de PodCast.
	     *
	     * @param {object} props Listado de propiedades del componente.
	     *
	     * @return PodCastList.
	     */
	    const PodCastList = (props) => {
	        // Destructuración y definiendo un valor por defecto en el caos de que no exista el nodo
	        const { channels = [] } = props;
	        return (
	            <Fragment>
	                <header>Podcast List</header>
	                <divclassName="channels">
	                    {
	                        channels.map((channel) => {
	                            const { id, title, urls: { logo_image: { original } } } = channel;
	                            return (
	                                <aclassName="channel"key={`potcast-${id}`}>
	                                    <imgsrc={original}alt={title} />
	                                    <h2>{title}</h2>
	                                </a>
	                            );
	                        })
	                    }
	                </div>
	                {StyleJSX}
	            </Fragment>
	        );
	    };
	    
	    /**
	     * Llamado a la api de audioboom.
	     *
	     * @return {Promise}.
	     */
	    PodCastList.getInitialProps = async () => {
	        const SEND = await fetch(API);
	        // Destructuración y renombramiento del nodo body
	        const { body: channels } = await SEND.json();
	        return { channels };
	    };
	    
	    export default PodCastList;
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **AndresCervera15** (2)

	
	Código funcionando al día de hoy 05/OCT/19
	``` 
	    import 'isomorphic-fetch';
	    
	    export default class extends React.Component {
	      static async getInitialProps() {
	        let req = await fetch(
	          'https://api.audioboom.com/channels/recommended?api_version=2'
	        );
	    
	        let { body: channels } = await req.json();
	    
	        return { channels };
	      }
	    
	      render() {
	        const { channels } = this.props;
	        return (
	          <div>
	            <header>Podcasts</header>
	    
	            <div className="channels">
	              {channels.map(channel => (
	                <div className="channel" key={channel.id}>
	                  <img src={channel.urls.logo_image.original} alt="" />
	                  <h2>{channel.title}</h2>
	                </div>
	              ))}
	            </div>
	    
	            <style jsx>{`
	              header {
	                color: #fff;
	                background: #8756ca;
	                padding: 15px;
	                text-align: center;
	              }
	    
	              .channels {
	                display: grid;
	                grid-gap: 30px;
	                padding: 20px;
	                grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
	              }
	    
	              .channel {
	                display: block;
	                border-radius: 3px;
	                box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.15);
	                margin-bottom: 0.5;
	              }
	    
	              .channel img {
	                width: 100%;
	              }
	    
	              h2 {
	                padding: 5px;
	                font-size: 0.9em;
	                font-weight: 600;
	                margin: 0;
	                text-align: center;
	              }
	            `}</style>
	    
	            <style jsx global>{`
	              body {
	                margin: 0;
	                font-family: system-ui;
	              }
	            `}</style>
	          </div>
	        );
	      }
	    }
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Miguel Angel Morales Larriega** (2)

	
	Esta es otra forma de hacerlo con stales functional component y con unfetch
	
	![Captura2.PNG](https://static.platzi.com/media/user_upload/Captura2-ccccda29-5a80-42ca-b345-bb66e0ca2464.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **José antonio Cañizales** (2)

	
	Si alguien esta usando React Hooks se puede usar la function getInitialProps con esta syntaxis:
	``` 
	    functionPage({ stars }) {
	      return<div>Next stars: {stars}</div>
	    }
	    Page.getInitialProps = async ({ req }) => {
	      const res = await fetch('https://api.github.com/repos/zeit/next.js')
	      const json = await res.json()
	      return { stars: json.stargazers_count }
	    }
	    exportdefault Page
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Miguel Angel Morales Larriega** (1)

		
		No veo nada de React Hhooks en ese código, solo veo un functional component y si, esa es la forma correcta de usar getInitialProps en componentes funcionales.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Eduardo Hidalgo Díaz Rugama** (2)

	
	mis respetos al profesor y a esta clase. Es asombroso como con las tecnologías adecuadas y la experiencia adecuada en 14 minutos crea un catálogo de podcasts. Sin palabras.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Daniee** (2)

	
	Hola Roberto ! Una pregunta: Tenemos en next los estados de los componentes de React ?
	
	Quisiera añadir un feature a mi proyecto que sería crear una especie de loader, que desaparezca cuando la primera carga se haya realizado para que se muestre todo el contenido a la vez.
	
	En react existe el ComponentDidMount, cómo podría conseguir eso en next ?
	
	Saludos desde Suiza ! Me encanta la manera en la que explicas
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (4)

		
		Hola! Las páginas en Next son componentes estándar de React, por lo que dispones de todos los métodos de React.
		
		Puntualmente componentDidMount sólo se ejecuta en el cliente en Next (y no durante SSR), por lo que se pueden hacer loaders y comportamientos más complejos que van por fuera del mecanismo de server side rendering.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Brian Dennis Vega Hidalgo** (2)

	
	Algun plugin para para intellisense dentro de la etiqueta <style jsx>. todo se ve como texto
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **joseVargas94** (1)

		
		en este post encontré como hacerlo  
		<https://github.com/zeit/styled-jsx/issues/186>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Georgie Duarte** (2)

		
		si usas VSCODE puedes buscar este vscode-styled-jsx como extension me funciona muy bien.
		
		te dejo la web  
		<https://marketplace.visualstudio.com/items?itemName=blanu.vscode-styled-jsx>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Fadith Enrique Escorcia Mujica** (1)

	
	Isomorphic-fecth sirve para dar soporte a al servidor para utilizar fetch
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **assistcardaciit** (1)

	
	Buenas, aca no me esta funcionando los Css.  
	Alguna idea???
	``` 
	    const renderChannel = channel => (
	      <a className="channel" key={channel.id}>
	        <img src={channel.urls.logo_image.original} alt="" />
	        <h2>{channel.title}</h2>
	      </a>
	    );
	    
	    const renderChannels = ({ channels }) => (
	      <div className="channels">
	        {channels.map(channel => renderChannel(channel))}
	      </div>
	    );
	    
	    const Page = props => (
	      <div>
	        <header>Podcasts</header>
	        {renderChannels(props)}
	        <style jsx>{`
	          header {
	            color: #fff;
	            background: #8756ca;
	            padding: 15px;
	            text-align: center;
	          }
	          .channels {
	            display: grid;
	            grid-gap: 15px;
	            padding: 15px;
	            grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
	          }
	          a.channel {
	            display: block;
	            margin-bottom: 0.5em;
	            color: #333;
	            text-decoration: none;
	          }
	          .channel img {
	            border-radius: 3px;
	            box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.15);
	            width: 100%;
	          }
	          h2 {
	            padding: 5px;
	            font-size: 0.9em;
	            font-weight: 600;
	            margin: 0;
	            text-align: center;
	          }
	        `}</style>
	    
	        <style jsx global>
	          {`
	            body {
	              background: white;
	              font-family: system-ui;
	              margin: 0;
	            }
	          `}
	        </style>
	      </div>
	    );
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		No te toma ninguna propiedad del css o solo alguna?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **_jrgarciadev** (1)

		
		El css de channels debe estar dentro de la función renderChannels y así con todas, a no se que le coloques la etiqueta “global” al styled, ej. <styles jsx global>{``}</styles>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **WSJedp** (1)

	
	Next tiene un gran parecido a React Native, la forma en que recibe los props, en como se consume las API y la forma de agregar estilos es de una manera muy intuitiva y agil! Genial!!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Andres Roberto Coello Goyes** (1)

	
	Alguien sabe si se puede cambiar o modificar la pagina de error 404 de next js…?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Serrati** (2)

		```
		    // pages/404.js
		    exportdefaultfunctionCustom404() {
		      return<h1>404 - Page Not Found</h1>
		    }
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Andres Roberto Coello Goyes** (1)

		
		eso es todo? como lo integro ?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **gosunkugi** (1)

	
	vengan pero tengo una pregunta, los datos del api se descargan del lado del servidor y se “fusionan” y terminan dentro del bundly?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **raulfbgomez** (1)

		
		En este caso si, todo el código que esta dentro de `getInitialProps` se ejecuta del lado del servidor y solo se ejecuta del lado del cliente cuando se navega por un componente de `next/link` o `next/router`. [Documentación.](https://nextjs.org/docs/api-reference/data-fetching/getInitialProps)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Anthony Farias** (1)

	
	Me voló la cabeza eso de grid css! ___
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Jorge Mendez Ortega** (1)

		
		Te recomiendo que revises este material
		
		Grid  
		<https://cssgridgarden.com/>
		
		y  
		Flex  
		<https://flexboxfroggy.com/>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Carlos Andrés Cobo Sinisterra** (1)

	
	Hola mi gente, pregunta en el getInitialProps hace el get a la API para obtener los datos pero como puedo hacer un post, put o delete? tambien existe alguna funcion en la que se recomiende?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **nahrivera7** (1)

		
		Según entiendo en el video, lo que queremos hacer es un GET de la información esencial de la página, osea si tu Home tiene info que viene de un API, necesitas tener esa info para poder renderizarla. Caso contrario en un POST o un PUT, en dónde tu vista inicial sería un formulario por ejemplo. O en el caso de un DELETE, tu vista inicial sería los datos que vienen del GET.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Marco Antonio Macedo Preciado** (1)

		
		Para usar otros metodos de HTTP en la peticion tienes que indicarle a fetch (que es la funcion que se encarga de las peticiones) el metodo. Algo así:
		``` 
		    static async getInitialProps(){
		    	const data = await fetch('/el-endpoint-de-la-api/', {
		    		method: 'POST'
		    		});
		    	constresult = data.json();
		    	returnresult;
		    }
		    
		    
		```
		
		Puedes leer más sobre fetch [acá](https://developer.mozilla.org/es/docs/Web/API/Fetch_API/Utilizando_Fetch)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Wilson Marino Pablo Mendez** (1)

	
	Brutal _CSS Grid Layout_
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Miguel Angel Morales Larriega** (1)

	
	te faltó ponerle un key  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-c8d7bf40-e50b-4f9d-b05a-1a2e1ebe3bec.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Miguel Angel Morales Larriega** (1)

	
	Creo que una mejor práctica sería instalar fetch como una dependecnia del desarrollo, osea npm install --save-dev isomorphic-unfetch
	
	Esto generara un objeto llamado devDependencies  
	"devDependencies": {  
	“isomorphic-unfetch”: “^3.0.0”  
	}
	
	Lo adecuado es usar unfetch cuando se trata de next js
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **uninorteplatziparatodos** (1)

		
		Por que debería ser una dependencia de desarrollo? En producción si utilizas `npm i --only-production` para no instalar lo que no se necesita, no la instalaría y haría que el código falle.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **webins** (1)

	
	Acabo de buildear la aplicacion y arrancarla usando el prefetch en los links pero igual no me precarga mi archivo de channel.js en network como aparece en el video, ¿Por que?
	``` 
	    import "isomorphic-fetch";
	    import Link from "next/link";
	    
	    export default class extends React.Component {
	      static async getInitialProps() {
	        let request = await fetch("https://api.audioboom.com/channels/recommended");
	        let { body: channels } = await request.json();
	    
	        return { channels };
	      }
	    
	      render() {
	        const { channels } = this.props;
	        return (
	          <React.Fragment>
	            <headerclassName="Head">Podcast</header>
	            <divclassName="grid-container">
	              {channels.map(channel => (
	                <sectionclassName="container">
	                  <header>
	                    <Linkhref={`/channel?id=${channel.id}`}prefetch>
	                      <aclassName="link">
	                        <h1className="title"key={channel.id}>
	                          {channel.title}{" "}
	                        </h1>
	                      </a>
	                    </Link>
	                  </header>
	                  <Linkhref={`/channel?id=${channel.id}`}prefetch>
	                    <aclassName="link">
	                      <nav>
	                        <img
	                          className="logoImg"
	                          src={channel.urls.logo_image.original}
	                        />
	                      </nav>
	                    </a>
	                  </Link>
	                  <main>
	                    <h2className="description">{channel.description}</h2>
	                  </main>
	                </section>
	              ))}
	            </div>```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Diaz Venero** (1)

	
	Si en algún momento aparece el warning de incluir el api version, la forma de llamarla es: <https://api.audioboom.com/channels/recommended?api_version=2>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Diaz Venero** (1)

	
	Les comparto otra api libre para jugar: <https://randomuser.me>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Diaz Venero** (1)

	
	[NextJS] Traer los datos desde un API
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Joaquin Mayer Breitkreitz** (1)

	
	Alguien sabe que theme de vscode esta usando?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		El tema que utiliza es el por defecto, los colores del editor es Monokai.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **brapastor** (1)

	
	`<style jsx>{`  
	header{  
	color: #fff;  
	background: #8756ca;  
	padding: 15px  
	}  
	`} </style> <style jsx global>{`  
	body{  
	margin: 0;  
	font-family: system-ui;  
	background:white  
	}  
	`} </style>`
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Georgie Duarte** (1)

	
	si agrego la dependencia para porder importar css que venga de otro archivo, pierdo la versatilidad de que los estilos sean por componente y pasaran a ser globales?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **ebar0n (Platzi)** (1)

		
		Hola, no necesariamente pierdes versatilidad, al contrario, puedes reusarlos porque seran globales, de igual forma siempre puedes seguir teniendo estilos especificos para un componente.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Armando de jesus santiz lopez** (1)
Los getInitialProps también funciona en el frontend o toca hacer otra función para pedir datos al api ?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **esdraspavon** (1)

	
	Los estilos usados en clase:
	``` 
	    <style jsx>{`
	               header {
	                   color:#fff;
	                   background:#8756ca;
	                   padding:15px;
	                   text-align:center;
	               }
	               .channels {
	                   display: grid;
	                   grid-gap: 15px;
	                   padding: 15px;
	                   grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
	               }
	               .channel {
	                   display: block;
	                   border-radius: 3px;
	                   box-shadow: 02px 6px rgba(0,0,0,0.15);
	                   margin-bottom: 0.5em;
	               }
	               .channel img {
	                   width:100%;
	               }
	               h2{
	                padding: 5px;
	                font-size: 0.9em;
	                font-weight: 600;
	                margin: 0;
	                text-align:center;
	               }
	    
	            `}
	            </style>
	            <style jsx global>{`
	            body{
	                margin:0;
	                font-family:system-ui;
	                background:white;
	            }
	            `}
	            </style>
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Julio Gutierrez** (1)

	
	**Utilizar grid con Next.js**
	``` 
	    import fetch from 'isomorphic-fetch'
	    
	    export default class extends React.Component {
	    
	        // getInitialProps() es una función que solo se puede ejecutar en Next.js 
	        
	        static async getInitialProps(){
	            
	            // Llamo al API de audioboom y obtengo la los caneles recomendados 
	            let req = await fetch
	            ('https://api.audioboom.com/channels/recommended')
	    
	            //  obtengo todo lo que contiene "body": [] y lo asigno a una variable llamada channels
	            let { body: channels } = await req.json()
	    
	            // Regreso los todos los channels
	            console.log(channels)
	            return { channels }
	        }
	    
	        render(){
	            const { channels } = this.props
	    
	            return <div>
	                <header>Podcasts</header>
	    
	                <div className="channels">
	                {
	                    channels.map((channel) => (
	                        <a className="channel">
	                        <img src={ channel.urls.logo_image.original } alt="" />
	                        <h2>{ channel.title }</h2>
	                        </a>
	                    ))
	                }
	                </div>
	                
	                <style jsx>{`
	                header {
	                    color: #fff;
	                    background: #8756ca;
	                    padding: 15px;
	                    text-align: center;
	                }
	                .channels {
	                    display: grid;
	                    grid-gap: 15px;
	                    padding: 15px;
	                    grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
	                }
	                .channel {
	                    display: block;
	                    border-radius: 3px;
	                    margin-bottom: 0.5em;
	                    color: #333;
	                    text-decoration: none;
	                }
	                .channel img {
	                    width: 100%;
	                    border-radius: 3px;
	                    box-shadow: 0px 2px 6px rgba(0,0,0,0,.15);
	                    width: 100px;
	                }
	                h2 {
	                    padding: 5px;
	                    font-size: 0.9em;
	                    font-weight: 600;
	                    maring: 0;
	                    text-align: center;
	                }
	               
	                `}</style>
	    
	                <style jsx global>{`
	                body {
	                    margin: 0;
	                    font-family: system-ui
	                    background: white;
	                }
	                `}</style>
	    
	            </div>
	        }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Julio Gutierrez** (1)

	
	**Ejemplo de uso de fetch utilizando librería isomorphic-fetch**
	``` 
	    import fetch from'isomorphic-fetch'
	    
	    exportdefaultclassextendsReact.Component{
	    
	        // getInitialProps() es una función que solo se puede ejecutar en Next.js 
	        
	        staticasync getInitialProps(){
	            
	            // Llamo al API de audioboom y obtengo la los caneles recomendados 
	            let req = await fetch
	            ('https://api.audioboom.com/channels/recommended')
	    
	            //  obtengo todo lo que contiene "body": [] y lo asigno a una variable llamada channels
	            let { body: channels } = await req.json()
	    
	            // Regreso los todos los channels
	            console.log(channels)
	            return { channels }
	        }
	    
	        render(){
	            const { channels } = this.props
	            return<div>
	                <header>Podcasts</header>
	    
	                {
	                    channels.map((channel) => (
	                        <div>{ channel.title } </div>
	    
	                    ))
	                }
	                
	                <stylejsx>{`
	                header {
	                    color: #fff;
	                    background: #8756ca;
	                    padding: 15px;
	                    text-align: center;
	                }
	               
	                `}</style>
	    
	                <stylejsxglobal>{`
	                body {
	                    margin: 0;
	                    font-family: system-ui
	                    background: white;
	                }
	                `}</style>
	    
	            </div>
	        }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Julio Gutierrez** (1)

	
	getInitialProps - solo funciona en Next.js - NO funciona en otro framework
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **oobie92** (1)

	
	Para quienes no les pinte bien las respuests esta fue mi solucion ya que map no me lo estaba retornando:
	``` 
	          <div>
	            { channels.map((channel) => {
	              return (<div className="channels">
	                <img src={ channel.urls.logo_image.original } alt="" />
	                <h2>{ channel.title }</h2>
	              </div>)
	            }) }
	          </div>
	    
	```
	
	Saludos
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Jose Adan Ardila Sanchez** (1)

		
		Realmente la razón de que no te hubiera pintado tiene que ver con la forma en la que escribes la arrow function, si se pone de esta forma:
		``` 
		    channels.map(channel => {
		                        < div className="channel" >
		                            <img src={channel.urls.logo_image.original} alt="podcast_image" />
		                        </div>
		                    })
		    
		```
		
		la función necesita un return literal como el que pusiste debido a que el cuerpo de la arrow function está delimitado por {}
		
		si en lugar de poner {} delimitas el cuerpo de la arrow function con () no necesitas indicar explícitamente el return ya que “lo que se produzca adentro será retornado” así:
		``` 
		    channels.map(channel => (
		                        < div className="channel" >
		                            <img src={channel.urls.logo_image.original} alt="podcast_image" />
		                        </div>
		                    ))
		    
		```
		
		espero te sirva de algo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Gerardo Nava Pereda** (1)

	
	¿Axios vs isomorphic-fetch? ¿Hay alguna ventaja o desventaja una sobre otra?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (1)

		
		Hola, usar uno o no es más cuestión de gustos ya que ambas hacen lo mismo, hacer una petición, pero en mi experiencia me gusta más `Axios` ya que te permite crear una configuración global de peticiones, cada una de las peticiones son muy sencillas y permite reutilizar código.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Khriztian Moreno Zuluaga** (1)

	
	Como habilitan el `Emmet` para jsx ?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eddy Nelson Pérez Decena** (1)

		
		Si alguien tiene una respuesta soy todo oidos
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (3)

		
		En el curso usamos Visual Studio Code, que tiene Emmet automático si elegís el lenguaje **Javascript React** (abajo a la derecha en el editor).
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **mirandajignacio** (1)

	
	Utilizan algún plugin para tener intellisense dentro de la etiqueta <style jsx>. Se me ve todo como si fuera un string.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (4)

		
		Hay un plugin de Styled JSX para VS Code. Tiene varios bugs pero funciona aceptablemente bien.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Byhako** (1)

	
	¿Cual es la diferencia entre npm install y npm add?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (5)

		
		npm add es un alias para npm install
		
		![Screenshot_20180717_223608.png](https://static.platzi.com/media/user_upload/Screenshot_20180717_223608-fe482667-54b4-4b34-a99a-151b2060b38a.jpg)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Minei** (2)

		
		Que interesante que unos de los aliases sea **isntall.**
		
		Hacer que un typo se vuelva un comando oficial es épico!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **marcelo.lavizzari** (1)

	
	Cuales serian las ventajas , entre usar el <style jsx> dentro de un archivo js y usar un archivo css por cada componente, (no en forma global), como lo hemos estado aprendiendo en los cursos de react. ? Ademas de que me parece que el utilizar un archivo, css, es mass facil de manipular, para alguien que realice solo el maquetado y nos las funcionalidades de la app.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (3)

		
		Styled JSX es similar a CSS Modules en funcionamiento, ya que las clases se renombran por componente para evitar problemas de scoping. También podés utilizar JS inline, que dependiendo de cómo tengas configurado tu entorno puede ser más cómodo. Esto es cuestión de gustos, y para la mayoría de proyectos son lo mismo.
		
		Si preferís tener los estilos en un archivo aparte podés utilizar [next-css](https://github.com/zeit/next-plugins/tree/master/packages/next-css) que te deja hacer exactamente eso, y también tenés ejemplos con PostCSS y demás en los docs si preferís usar preprocessors.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Baltazar Ortega** (1)
¿Porqué en getInitialProps() está return { channels } y luego otra ves en render() const { channels } = this.props ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		getInitialProps es un método que se ejecuta para llamar la información de fuentes de datos remotas como un api, lo que retorna esta función lo guarda en this.props, por esto luego en el método render se vuelve a asignar this.props a { channels }
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **SKILLON** (1)
dentro de la función render, siempre que quiera ejecutar un map debo utilizar paréntesis en lugar de llaves para que se haga render?, por...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Ivan Padilla Bernal** (2)

		
		Es sencillo, cuando usas llaves tu tienes que usar un ‘ **return** ’ si es que quieres retornar algo porque a veces quieres hacer operaciones antes de retornar algo, pero cuando sabes que todo lo que está en la función va a retornar se usa paréntesis.  
		Por ejemplo esto sería similar
		``` 
		    objeto.map((param) => {
		    	return <div>{param.param}</div>
		    })
		    
		```
		``` 
		    objeto.map((param) => (
		    	<div>{param.param}</div>
		    ))
		    
		```
		
		pero también como es una simple linea se puede simplificar más o sea ya no hace falta poner llaves ni parentesis (solo aplica cuando se tiene una linea de código)
		``` 
		    objeto.map((param) => <div>{param.param}</div>)
		    
		```
		
		Y este sería un ejemplo donde se tiene que usar llaves a fuerza porque el “ **console.log** ” no se puede retornar
		``` 
		    objeto.map((param) => {
		    	console.log(param)
		    	return <div>{param.param}</div>
		    })
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **elvis-retiz** (1)
¿Alguien que me pueda decir porque me ocurre eso? Anexo codigo mas abajo import "isomorphic-fetch"; export default class extends ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **RBN1993** (3)

		
		Parece ser que es por que se usa un <a></a> sin un <Link> miralo aquí. <https://platzi.com/clases/1311-next-js/12078-utilizando-ampltlinkampgt/> , pregunté lo mismo en esta clase <https://platzi.com/clases/1311-next-js/12075-styled-jsx/> y me respondieron muy tarde, no se con certeza si es verdad por que ya acabe el curso.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Georgie Duarte** (1)
si agrego la dependencia para porder importar css que venga de otro archivo, pierdo la versatilidad de que los estilos sean por component...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **ebar0n (Platzi)** (1)

		
		Hola, no necesariamente pierdes versatilidad, al contrario, puedes reusarlos porque seran globales, de igual forma siempre puedes seguir teniendo estilos especificos para un componente.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Gerardo Nava Pereda** (1)
¿Axios vs isomorphic-fetch? ¿Hay alguna ventaja o desventaja una sobre otra?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (1)

		
		Hola, usar uno o no es más cuestión de gustos ya que ambas hacen lo mismo, hacer una petición, pero en mi experiencia me gusta más `Axios` ya que te permite crear una configuración global de peticiones, cada una de las peticiones son muy sencillas y permite reutilizar código.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Khriztian Moreno Zuluaga** (1)
Como habilitan el Emmet para jsx ?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eddy Nelson Pérez Decena** (1)

		
		Si alguien tiene una respuesta soy todo oidos
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Byhako** (1)
¿Cual es la diferencia entre npm install y npm add?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (5)

		
		npm add es un alias para npm install
		
		![Screenshot_20180717_223608.png](https://static.platzi.com/media/user_upload/Screenshot_20180717_223608-fe482667-54b4-4b34-a99a-151b2060b38a.jpg)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **HandCloud** (0)
porque cuando intento consumir una api de mi pc me lanza un error de certificacion?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

## 0060. Utilizando el componente Link

### Descripción:


En esta clase vamos a ver como linkear páginas nuevas, y sobre todo cómo funciona el router de Next.js en mayor detalle.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Juan David Castro (Platzi)** (17)

	
	Que grande! Es el primer profesor que avisa cuando va a explicar una pregunta del examen 😂 😂 😂!!
	
	GENIAAAAL!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **ferontv_** (4)

		
		El curso está increíble ! Vamos paso a paso de manera concreta y simple. Bastante buena la forma de enseñar de Roberto, además bien por esos avisos para el examen 👏🏻
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **WilliamVelazquez** (2)

		
		Exacto, todo lo explica con gran claridad! 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Oscar Barajas Tavares (Platzi)** (3)

		
		Es muy bueno el profesor siempre explica a detalle.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **David Daniel Castillo Nava** (3)

		
		Primera vez que veo clase con el pero explica muy bien.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Diego Fernando Berrio Meza** (8)

	
	Hasta ahora no tuve ningún error **Roberto Gonzalez** es por mucho uno de los mejores profesores de Platzi.
	
	ojala el pudiera dar el curso de React su explicación es muy limpia y no tiene rodeos eso ayuda a que los estudiantes se concentren y no den vueltas mientras aprenden.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Diaz Venero** (1)

		
		estaria bueno para React y todos los de Js tambien 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **LeandroVidela** (4)

	
	Para evitar el Warning que tira en la consola ( ** _Each child in a list should have a unique “key” prop._** ), tenemos que agregar el atributo KEY al <Link>.
	``` 
	    <Linkhref="/channel"key={channel.id}prefetch>
	          <aclassName="channel">
	               .....
	          </a>
	    </Link>
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Minei** (4)

	
	## Enlazando Páginas
	
	Next usa un componente llamado `<Link/>` que debe de contener un `<a>`.
	``` 
	    import Link from'next/link';
	    
	    <Linkhref='/channel'>
	      <aclassName="channel">
	        click me
	      </a>
	    </Link>
	    
	```
	
	**Nota** : El href va en el `<Link>`. No en el `<a>`.
	
	**Si clickeamos en un Link** :
	
	  * Client Side Rendering.
	  * Carga sólo lo que falta de esa página.
	  * Cambia la ruta en el browser.
	
	
	
	**Si abrimos un nuebo tab** :
	
	  * Server Side Rendering.
	  * Carga todo el HTML, CSS y JS.
	  * Crea una nueva sesión.
	
	
	
	## Prefetch
	
	Prefetch le indica a next que el Link es importante y que vaya precargando el contenido por adelantado y así se ahorra un poco de tiempo de carga.
	
	Prefetch solo funciona en producción (npm run build && npm start).
	``` 
	    <Link href='/channel' prefetch>
	      <a>...</a>
	    </Link>
	    
	```
	
	Prefetch no precarga getInitialProps. Solo precarga HTML, CSS y JS.
	
	¿Qué pasa si repito prefetch? Por ejemplo, si está dentro de un `map()`.  
	Cada página solo se precarga una vez.
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Fernando Azuaje** (3)

	
	ya no es necesario agregar prefetch a Link, Next lo hace por si solo cuando lo corren en modo produccion
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jhurtadojerves** (3)

	
	Una consulta más bien off topic.
	
	¿que complemente tienes instalado para que funcione emmet en JSX con vcode?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (5)

		
		Viene con VSCode! Lo que tenés que hacer es setear el tipo de archivo a **Javascript React** abajo a la derecha (idealmente para todos los archivos .js, así no tenés que configurarlo a cada rato).
		
		Después sólo sumé la extensión de Styled JSX que te da syntax highlighting en el CSS.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Kevin Javier Morales (Platzi)** (6)

		
		Esto lo pude lograr el poco tiempo que tuve VSCode instalado. Es cuestion de agregarle un par de lineas al archivo settings. [Esta respuesta](https://stackoverflow.com/questions/39320393/jsx-or-html-autocompletion-in-visual-studio-code) puede servirte ademas de lo que dice Roberto.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **jhurtadojerves** (1)

		
		Muchas gracias a los dos, ya está solucionado. Vengo de webStorm y me estoy acostumbrando 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Daniee** (1)

		
		Wau ayuda un montón a agilizar el trabajo gracias chicos !
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **jhon manuel angulo moncada** (2)

	
	Como argumentan los compañeros desde Next 9, ya no es necesario utilizar “prefetch”, este viene en true por defecto.
	
	lo que podemos hacer es desactivarlo cuando no lo sea requerido:
	
	prefetch={false}
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Diego Ortiz** (2)

	
	Al parecer ya no es necesario usar prefetch según este mensaje que me salió en la terminal:  
	Next.js auto-prefetches automatically based on viewport. The prefetch attribute is no longer needed. More: <https://err.sh/zeit/next.js/prefetch-true-deprecated>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Camilo Rivera Quintero** (2)

	
	Buen Profe!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **eltenis** (2)
Que bueno... y para utilizar Rutas privadas.... es decir con login.... y luego entras a la App??? Muchas gracias
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Diaz Venero** (1)

		
		Hola, como lo resolviste?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		¡Hola! Este tipo de comportamiento lo puedes manejar con un estado y ese estado se lo pasas a tus rutas que quieres mantener privadas, si el usuario está autorizado o no
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Diego Ortiz** (2)
Cuando lo corro en producción, revisando mi network… se queda haciendo infinitas peticiones a webpack-hmr?page=/ y a: ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Sánchez** (1)

	
	[Desde Next.js 9](https://nextjs.org/blog/next-9#prefetching-in-viewport-links) el componente `Link` hace el `prefetch` de forma automática a medida que los componentes aparezcan en el viewport por lo que no es necesario hacer lo que dice en la clase.
	
	Si se desea eliminar el `prefetch` para páginas que no se visitan mucho, se puede hacer `prefetch={false}`.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **José Antonio aparicio gallego** (1)

	
	prefetch pregunta de examen Prehistórico
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WSJedp** (1)

	
	Para poder utilizar el componente Link deberemos importar la librería next/link, y así poder desplazarnos por nuestras vistas de forma dinámica y rápida sin necesidad de recargar nuestro navegador, ademas, nos ofrece el Prefetch, que nos sirve para pre-cargar un archivo Js antes de entrar en él.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Alejandro Trejo Cuxim** (1)
<h1>Importante</h1>
	
	Recordar que si la página se llama: “/channel” el componente debe llamarse en pages de igual manera osea: channel.js
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **carlos-samuel-hernandez** (1)

	
	Cuando intento navegar a un channel, me aparece lo siguiente:  
	**An unexpected error has occurred.**
	
	Alguien me puede ayudar? Por favor
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Ortiz** (1)

		
		Debes colocar más información en este tipo de preguntas. Como tu archivo index.js, tu archivo channel.js, tu estructura de archivos, etc…
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Gianfranco Correa** (1)

	
	que interesante se está poniendo esto!! después de ver react y redux, este curso le da el toque para terminar de fascinarte ❤️
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Julio Gutierrez** (1)

	
	<Link href="/channel" prefetch></Link>
	
	  * prefetch No carga getInitialProps, sólo el payload
	
	  * prefetch Solo funciona en producción, no funciona en modo dev. ( npm run build && npm start)
	
	  * prefetch Es una forma de acelerar el precargado del render
	
	
	
	``` 
	    import fetch from'isomorphic-fetch'
	    import Link from'next/link'
	    
	    exportdefaultclassextendsReact.Component{
	    
	        // getInitialProps() es una función que solo se puede ejecutar en Next.js 
	        
	        staticasync getInitialProps(){
	            
	            // Llamo al API de audioboom y obtengo la los caneles recomendados 
	            let req = await fetch
	            ('https://api.audioboom.com/channels/recommended')
	    
	            //  obtengo todo lo que contiene "body": [] y lo asigno a una variable llamada channels
	            let { body: channels } = await req.json()
	    
	            // Regreso los todos los channels
	            console.log(channels)
	            return { channels }
	        }
	    
	        render(){
	            const { channels } = this.props
	    
	            return<div>
	                <header>Podcasts</header>
	    
	                <divclassName="channels">
	                {
	                    channels.map((channel) => (
	                        <Linkhref="/channel">
	                        <aclassName="channel"prefetch>
	                        <imgsrc={channel.urls.logo_image.original } alt="" />
	                        <h2>{ channel.title }</h2>
	                        </a>
	                        </Link>
	                    ))
	                }
	                </div>
	                
	                <stylejsx>{`
	                header {
	                    color: #fff;
	                    background: #8756ca;
	                    padding: 15px;
	                    text-align: center;
	                }
	                .channels {
	                    display: grid;
	                    grid-gap: 15px;
	                    padding: 15px;
	                    grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
	                }
	                .channel {
	                    display: block;
	                    border-radius: 3px;
	                    margin-bottom: 0.5em;
	                    color: #333;
	                    text-decoration: none;
	                    text-align: center;
	                }
	                .channel img {
	                    width: 100%;
	                    border-radius: 3px;
	                    box-shadow: 0px 2px 6px rgba(0,0,0,0,.15);
	                    width: 100px;
	                }
	                h2 {
	                    padding: 5px;
	                    font-size: 0.9em;
	                    font-weight: 600;
	                    maring: 0;
	                    text-align: center;
	                }
	               
	                `}</style>
	    
	                <stylejsxglobal>{`
	                body {
	                    margin: 0;
	                    font-family: system-ui
	                    background: white;
	                }
	                `}</style>
	    
	            </div>
	        }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Daniee** (1)

	
	Habría que tener agregar una vez más el Header a la página donde vamos ?
	
	No se podría hacer cómo en otros frameworks, donde la navegación del lado del cliente se carga en un componente para no tener que llamar una vez más al Header y al Footer por ejemplo ? Gracias !
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Antonio Ordóñez Cornejo** (1)

	
	Se usa el atributo className y no class. Eso tiene alguna importancia en next.js?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **davidtoca (Platzi)** (2)

		
		es porque next usa react, y react requiere el uso de classname, el uso de class esta restringido a webcomponents
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Ivan Robles** (5)

		
		En las proximas versiones de React se va a utilizar **class** , dejando de lado a **className** , pero mientras tanto hay que utilizar **className**.
		
		<https://github.com/facebook/react/issues/13525#issuecomment-417778489>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **jobcoronadoduran** (1)

		
		actualmente no se puede.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **David Daniel Castillo Nava** (1)

	
	Excelente como explica, todo detallado. De momento me esta gustando el Next.Js.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Joaquin Araujo** (1)

	
	He notado que al regresar al index desde channel tarda un poco en renderizarlo ¿le pasa a alguien más?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **jobcoronadoduran** (1)

		
		si
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Jesus Garcia** (1)

	
	excelente explicacion del prefetch
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **EnmanuelCastillo** (1)
General algún inconveniente el que los archivos sean de extensión .jsx en vez de .js???
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Gabriel De Andrade (Platzi)** (3)

		
		Hoy en día no, los archivos .jsx y .js se comportan igual en la mayoría de compiladores, no deberías tener problemas por usar uno o el otro, la decisión va a depender de lo que acuerdes con tu equipo y tus reglas de trabajo 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **EnmanuelCastillo** (1)
General algún inconveniente el que los archivos sean de extensión .jsx en vez de .js???
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Antonio Ordóñez Cornejo** (1)
Se usa el atributo className y no class. Eso tiene alguna importancia en next.js?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **davidtoca (Platzi)** (2)

		
		es porque next usa react, y react requiere el uso de classname, el uso de class esta restringido a webcomponents
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **jhurtadojerves** (0)
Una consulta más bien off topic. ¿que complemente tienes instalado para que funcione emmet en JSX con vcode?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (5)

		
		Viene con VSCode! Lo que tenés que hacer es setear el tipo de archivo a **Javascript React** abajo a la derecha (idealmente para todos los archivos .js, así no tenés que configurarlo a cada rato).
		
		Después sólo sumé la extensión de Styled JSX que te da syntax highlighting en el CSS.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0070. Recibiendo Parámetros

### Descripción:


En esta clase vamos a ver cómo hacer una de las cosas más cruciales que tenemos en cualquier aplicación, que es recibir parámetros sobre una página.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Sergio Minei** (8)

	
	## Recibiendo Parámetros
	``` 
	    // /pagina?id=54412
	    staticasync getInitialProps({query}) {
	      let id = query.id;
	    }
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jhurtadojerves** (4)

	
	Me gusta la forma tan sencilla para enviar parámetros, ojalá en seguientes clases se vea alguna forma de hacerlo más bonito, quitar ese ?id= de la url.
	
	Gran clase
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (8)

		
		En la clase de Next Routes vemos cómo hacer URLs agradables 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **jhurtadojerves** (0)

		
		Justo vi el temario y supuse que Next Routes lo arreglará, gracias por la respuesta 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Juan David Castro (Platzi)** (4)

	
	Si, estoy gritando…
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Ricardo José Galarza Palacios** (2)

	
	Yo escribí channel.jsx de esta forma me gusta mas:
	``` 
	    exportdefaultclassextendsReact.Component{
	      staticasync getInitialProps({ query }) {
	        let reqChannel = awaitthis.getChannel(query.id);
	        let reqAudioClips = awaitthis.getAudioClipsChannel(query.id);
	        let reqSeries = awaitthis.getSeries(query.id);
	        return {
	          channel: reqChannel.channel,
	          audio_clips: reqAudioClips,
	          series: reqSeries
	        };
	      }
	    
	      staticasync getChannel(idChannel) {
	        let req = await fetch(`https://api.audioboom.com/channels/${idChannel}`);
	        let {
	          body: { channel }
	        } = await req.json();
	        return { channel };
	      }
	    
	      staticasync getAudioClipsChannel(idChannel) {
	        let req = await fetch(
	          `https://api.audioboom.com/channels/${idChannel}/audio_clips`
	        );
	        let dataAudios = await req.json();
	        return dataAudios.body.audio_clips;
	      }
	    
	      staticasync getSeries(idChannel) {
	        let req = await fetch(
	          `https://api.audioboom.com/channels/${idChannel}/child_channels`
	        );
	        let dataSeries = await req.json();
	        return dataSeries.body.channels;
	      }
	    
	      render() {
	        const { channel, audio_clips, series } = this.props;
	        console.log(this.props);
	    
	        return (
	          <div>
	            <header>Podcasts</header>
	            <h1>{channel.title}</h1>
	    
	            <h2>Series</h2>
	            {series.map(serie => (
	              <div>{serie.title}</div>
	            ))}
	    
	            <h2>Podcast</h2>
	            {audio_clips.map(clip => (
	              <div>{clip.title}</div>
	            ))}
	            <stylejsx>
	              {`
	                header {
	                  color: #fff;
	                  background: #8756ca;
	                  padding: 15px;
	                  text-align: center;
	                }
	                .channels {
	                  display: grid;
	                  grid-gap: 15px;
	                  padding: 15px;
	                  grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
	                }
	                a.channel {
	                  display: block;
	                  margin-bottom: 0.5em;
	                  color: #333;
	                  text-decoration: none;
	                }
	                .channel img {
	                  border-radius: 3px;
	                  box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.15);
	                  width: 100%;
	                }
	                h1 {
	                  font-weight: 600;
	                  padding: 15px;
	                }
	                h2 {
	                  padding: 5px;
	                  font-size: 0.9em;
	                  font-weight: 600;
	                  margin: 0;
	                  text-align: center;
	                }
	              `}
	            </style>
	            <stylejsxglobal>
	              {`
	                body {
	                  margin: 0;
	                  font-family: system-ui;
	                  background: white;
	                }
	              `}
	            </style>
	          </div>
	        );
	      }
	    }
	    
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Gaston Morales** (2)

	
	Increible como esta llendo el curso !!!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **LeandroVidela** (2)

	
	Por qué desde **channel.js** no hace falta importar **“isomorphic-fetch”**? Noto que también estamos usando fetch() en este archivo.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (4)

		
		Hola, el archivo `index.js` es el comienzo de la aplicación, desde ahí es la única parte donde se importa `isomorphic-fetch`, en los demás pages funcionará **fetch()** porque se está importando desde el comienzo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **JoosCode** (1)

		
		si noto eso pero tampoco se importa react en el index ? y no entiendo como trabaja nuxt para hacer esas importaciones ??
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **JoosCode** (1)

		
		si noto eso pero tampoco se importa react en el index ? y no entiendo como trabaja next para hacer esas importaciones ??
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (2)

		
		Hola @JoosCode, Next.js usa un import dinámico, es decir, cuando se llama `React` lo esta importando automáticamente sin tener un import explícito.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Georgie Duarte** (2)

	
	como hago para ver el api de esa manera. que plugging usa? yo abro esa url y veo la data pero no me aparece de manera comestible.??
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **David Vargas Domínguez** (1)

		
		Hola, en mi caso uso una extensión de chrome. Se llama JSON Formatter  
		<https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa>
		
		Si usas otro navegador, debe tener sus variantes
		
		Saludos!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **assistcardaciit** (1)

	
	Hola, tengo otra consulta relacionada con nextJS. En este ejemplo channel y audio_clips
	``` 
	      let channel = fetch(`https://api.audioboom.com/channels/${query.id}`)
	        .then(response => response.json())
	        .then(response => renameBodytoChannel(response.body));
	      let audio_clips = fetch(
	        `https://api.audioboom.com/channels/${query.id}/audio_clips`
	      )
	        .then(response => response.json())
	        .then(response => renameBodytoAudio_clips(response.body));
	      return { channel, audio_clips };
	    };```
	    
	    me llegan undefined las props. Porq seran?
	    
	    antes me funcionaba porque devolvia todo de la siguiente forma
	    ```Channel.getInitialProps = ({ query }) =>
	      fetch(`https://api.audioboom.com/channels/${query.id}`)
	        .then(response => response.json())
	        .then(response => renameBodytoChannel(response.body));
	    
	```
	
	en este caso channel devolvia valores, pero al agregar audio_clips no me funciona nada 😞
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Anthony Farias** (1)

	
	Implementacion de channel como componente funcional:
	``` 
	    const Channel = ({ channel, audioClips, series }) => {
	        return (
	            <div>
	                <header>Podcast</header>
	    
	                <h1>{channel.title}</h1>
	    
	                <h2>Ultimos Podcasts</h2>
	                {
	                    audioClips.map((clip, key) => (
	                        <divkey={key}>{clip.title}</div>
	                    ))
	                }
	                <h2>Series</h2>
	                {
	                    series.map((serie, key) => (
	                        <divkey={key}>{serie.title}</div>
	                    ))
	                }
	                <stylejsx>
	                    {
	                        `
	                        header{
	                            color: #fff;
	                            background: #8756ca;
	                            padding: 15px;
	                            text-align: center;
	                        }
	    
	                        h1{
	                            padding: 3px;
	                            text-align:center;
	                            font-size: 16px
	                        }
	                        `
	                    }
	                </style>
	    
	                <stylejsxglobal>
	                    {
	                        `
	                    body{
	                        background: white;
	                        margin:0;
	                        font-family: system-ui
	                    }
	                    `
	                    }
	    
	                </style>
	            </div>
	        )
	    }
	    
	    Channel.getInitialProps = async ({ query }) => {
	        let idChannel = query.id;
	    
	        let reqChannel = await fetch(`https://api.audioboom.com/channels/${idChannel}`);
	        let dataChannel = await reqChannel.json();
	        let channel = dataChannel.body.channel;
	    
	        let reqAudio = await fetch(`https://api.audioboom.com/channels/${idChannel}/audio_clips`);
	        let dataAudio = await reqAudio.json();
	        let audioClips = dataAudio.body.audio_clips;
	    
	        let reqSeries = await fetch(`https://api.audioboom.com/channels/${idChannel}/child_channels`);
	        let dataSeries = await reqSeries.json();
	        let series = dataSeries.body.channels;
	        return { channel, audioClips, series };
	    }
	    
	    exportdefault Channel```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Anthony Farias** (1)

	
	Si se reinicia el servidor y entramos directo a la pagina de channel/:id entonces bota el error de que fetch no está definido. Habrá que definirlo siempre en nuestras paginas.  
	![error.png](https://static.platzi.com/media/user_upload/error-92f5407e-7e80-4f87-8c7b-a39881577fa6.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Diego Ortiz** (1)

	
	Además de Next, me gusta aprender las diferentes sintaxis:  
	`async getMethod(parametro) { let query = parametro.query }`  
	Es exactamente igual que tener:  
	`async getMethod([ query }) { }`
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Julio Andrés Ramirez De Freitas** (1)

	
	Este es mi JSX Style para tener la misma vista ue mostro al principio.
	``` 
	    header {
	                            color: #fff;
	                            background: #8756ca;
	                            padding: 15px;
	                            text-align: center;
	                        }
	    
	                        .channels {
	                            display: grid;
	                            grid-gap: 15px;
	                            padding: 15px;
	                            grid-template-columns: repeat(
	                                auto-fill,
	                                minmax(160px, 1fr)
	                            );
	                            color: black;
	                        }
	    
	                        .channel {
	                            display: flex;
	                            border-radius: 4px;
	                            box-shadow: 0px3px4pxrgba(0, 0, 0, 0.15);
	                            text-decoration: none;
	                            overflow: hidden;
	                            transition: all ease 0.2s;
	                        }
	    
	                        .channelimg {
	                            margin: auto;
	                            width: 100%;
	                        }
	    
	                        .channel:hover {
	                            transform: translateY(-0.5em);
	                        }
	    
	                        h2 {
	                            padding: 5px;
	                            font-size: 12px;
	                            font-weight: 600;
	                            margin: 0.5em000;
	                            text-align: center;
	                        }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **oteka21** (1)

	
	Por que no crear un los componentes reutilizables como el Header
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Sergio Alejandro Trejo Cuxim** (1)

		
		Lo puedes hacer sin ningún problema, hasta puede ser un componente funcional, no necesita ser un componente de clase
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **alexjcm** (1)

	
	Si a la fecha a alguien se le presenta este **warning** en consola:
	
	![](https://i.postimg.cc/Y9RkJ2HT/error-key-react.jpg)
	
	Simplemente deben agregar un **key** a cada _< div/>_ que nos devuelve la lista:
	``` 
	       <h2>Series</h2>
	        {series.map(seri => (
	          <div key={seri.id}>{seri.title}</div>
	        ))}
	    
	       <h2>Ultimos podcasts</h2>
	        {audioClips.map(clip => (
	          <div>{clip.title}</div>
	        ))}
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Georgie Duarte** (1)

	
	como puedo ver los datos del api en el navegador de forma digerible para ver la estructura? si abro la url me trae los datos pero sin un formato ordenado??
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Georgie Duarte** (1)

		
		buscaba era ver la info de la api asi como se ve en el video con el formato para entender su estructura y saber como acceder a la info que necesito.
		
		Use potsman que me permite hacer el request y me muestra la respues con unos estilos simpaticos. Me acorde de esta herramienta del curso de node.js
		
		pero gracias por la respuesta
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Puedes usar insomina rest (<https://insomnia.rest/>) es un cliente para hacer consultas a API o postman, también puedes instalar en chrome una extensión para parsear respuestas json y verlas mejor estructuradas la extensión se llama Json Formatter <https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Eduardo Hidalgo Díaz Rugama** (1)

		
		también está postman! es igual que insomnia.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Julio J Yépez** (3)

		
		Hay plugins para chrome que te permiten ver archivos JSON en un formato mejorado: <https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc?hl=en>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **alexjcm** (1)

		
		Excelentes recomendaciones.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **alejandrocabreratavara** (1)
![Captura de pantalla 2018-09-24 a la\(s\) 21.49.08.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-09-24%20a%20la%28s%29%2021.49.08-42c49fab-1d68-47c3-b65d-3fa3ec9931d2.jpg)
	
	Alguien sabe que puede estarme pasando ?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **alejandrocabreratavara** (1)
![Captura de pantalla 2018-09-24 a la\(s\) 21.53.01.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-09-24%20a%20la%28s%29%2021.53.01-3872b4d7-1a69-4862-8bc1-1f4c6f239364.jpg)
		
		Esto es mi codigo
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **alejandrocabreratavara** (1)
![Captura de pantalla 2018-09-24 a la\(s\) 21.53.21.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-09-24%20a%20la%28s%29%2021.53.21-0e15ad11-bb28-4a86-8930-382ded137791.jpg)
		
		Este el error …
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **alejandrocabreratavara** (2)

		
		Sorry me di cuenta del error, desde el index , estaba pasando mal el id del channel…
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Eduardo Rasgado Ruiz** (1)

	
	Madre mia Willy!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Daniel Castillo Nava** (1)

	
	Yo grito pero es por que en verdad esto me esta gustando!!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **assistcardaciit** (1)
Respuesta a: Recibiendo Parámetros Hola, tengo otra consulta relacionada con nextJS. En este ejemplo channel y audio_clips let channel = ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Georgie Duarte** (1)
como puedo ver los datos del api en el navegador de forma digerible para ver la estructura? si abro la url me trae los datos pero sin un ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Georgie Duarte** (1)

		
		buscaba era ver la info de la api asi como se ve en el video con el formato para entender su estructura y saber como acceder a la info que necesito.
		
		Use potsman que me permite hacer el request y me muestra la respues con unos estilos simpaticos. Me acorde de esta herramienta del curso de node.js
		
		pero gracias por la respuesta
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **alejandrocabreratavara** (1)
Alguien sabe que puede estarme pasando ?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **alejandrocabreratavara** (1)
![Captura de pantalla 2018-09-24 a la\(s\) 21.53.01.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-09-24%20a%20la%28s%29%2021.53.01-3872b4d7-1a69-4862-8bc1-1f4c6f239364.jpg)
		
		Esto es mi codigo
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0080. Performance de Get Initial Props

### Descripción:


Al utilizar await en cada fetch al traer los datos desde la API nos evitamos el callback hell, pero estamos haciendo que el usuario tenga que esperar cerca de un segundo y medio hasta que se completen secuencialmente las tres request.  
En esta clase veremos cómo con Promise.all() solucionamos este problema de performance al paralelizar nuestras request.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **jsechirinos** (9)

	
	Se puede optimizar los `requests` de forma paralela con:  
	`Promise.all()`
	
	**Sintaxis:**
	``` 
	    let[req1, req2] = awaitPromise.all([
	    	fetch(url_1),
	    	fetch(url_2)
	    ])
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (8)

	
	Opte por optimizar un poco más la otra parte asíncrona después de que se obtuvo lo necesario de la API quedándome de la siguiente forma:
	``` 
	    		let [dataChannel, dataSeries, dataAudios] = await Promise.all([
	          reqChannel.json(),
	          reqSeries.json(),
	          reqAudios.json()
	        ])
	        
	        let channel = dataChannel.body.channel
	        let series = dataSeries.body.channels
	        let audioClips = dataAudios.body.audio_clips
	    
	```
	
	😃
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eduardo Hidalgo Díaz Rugama** (3)

		
		te falta meterle manejo de errores, y que muestres un mensaje de error amigable en caso que te falle algun llamado. Igual, algo interesante, ¿como le harías para pintar en pantalla aquellos llamados que si se cumplieron y solo mostrar el error en la sección donde truene?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Alejandro Trejo Cuxim** (1)

		
		Existen varias formas de lo que plantea Eduardo, para el caso de los ‘child_channels’, podemos con un IF si la request tiene o no datos, si tiene entonces regresar la data, de lo contrario, regresar la data con un mensaje de error.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Alejandro Trejo Cuxim** (1)

		
		Pero tener cuidado, esto que comenté fue para validar que tenían data, pero recuerda la naturaleza del Promise.all según MDN:  
		**_Si alguna de las promesas pasadas en el argumento iterable falla, la promesa all es rechazada inmediatamente con el valor de la promesa que fué rechazada, descartando todas las demás promesas hayan sido o no cumplidas. Si se pasa un array vacío a all , la promesa se cumple inmediatamente_**
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **WSJedp** (4)

	
	Cada vez que tengamos la necesidad de realizar varias peticiones a una API, la mejor practica es usar Promise.all(), es una función que nos permite realizar varias peticiones en paralelo, nos resulta bastante útil para mejor la rapidez de carga.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **MauricioHernanCabrera** (4)

	
	Bueeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee e esto esta genial!
	``` 
	    static async getInitialProps ({ query: { id }}) {
	        const [reqChannel, reqAudio, reqSeries] = await Promise.all([
	          fetch(`https://api.audioboom.com/channels/${id}`),
	          fetch(`https://api.audioboom.com/channels/${id}/audio_clips`),
	          fetch(`https://api.audioboom.com/channels/${id}/child_channels`)
	        ])
	    
	        const [
	          { body: { channel }},
	          { body: { audio_clips: audioClips }},
	          { body: { channels: series }}
	        ] = await Promise.all([
	          reqChannel.json(),
	          reqAudio.json(),
	          reqSeries.json()
	        ])
	        
	        return {
	          channel,
	          audioClips,
	          series
	        }
	      }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Arturo Lira Cerda** (3)

	
	Si quieren hacer tanto la request como la parte de pasar a JSON en la misma parte donde se hacen todas juntas, pueden usar .then()
	
	Personalmente a mí me gusta más así para no declarar tantas variables ^^
	``` 
	    static async getInitialProps({query}){
	            let idChannel = query.id
	    
	            let [reqChannel, reqSeries, reqAudios] = await Promise.all([
	                fetch(`https://api.audioboom.com/channels/${idChannel}`).then((response) => response.json()),
	                fetch(`https://api.audioboom.com/channels/${idChannel}/child_channels`).then((response) => response.json()),
	                fetch(`https://api.audioboom.com/channels/${idChannel}/audio_clips`).then((response) => response.json())
	            ])
	    
	            let channel = reqChannel.body.channel;
	            let series = reqSeries.body.channels;
	            let audioClips = reqAudios.body.audio_clips;
	    
	            return { channel, audioClips, series }
	        }```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Ivan Padilla Bernal** (2)

		
		Lo que hace el profesor no está del todo mal porque lo ideal es escribir código de forma vertical y no horizontal para hacerlo más legible pero pues fuera de eso ya depende de gustos
		
		Por cierto en tu caso ya no sería la request sino la data así que esto ya es de buenas practicas, y las buenas practicas dicen que debes nombrar las variables conforme lo que tienen que sería:
		
		[dataChannel, dataSeries, dataAudios]
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **tony_campos** (1)

		
		Siempre se debería buscar que el código sea fácil de leer, regularmente se pasa mucho más tiempo leyendo código existente que escribiendo código nuevo y tiene muchos beneficios como mayor limpieza, fácil comprensión y por tanto fácil mantenimiento del mismo (entre muchos otros beneficios).
		
		Por ejemplo:  
		Tener únicamente “.json()” como en el código original es mucho más fácil de leer que esta versión:  
		.then( ( response ) => response.json() )
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Sergio Minei** (3)

	
	## Performance de Get
	
	Si hay varias requests, se pueden paralelizar con `Promise.all()`.
	``` 
	    let [req1, req2] = awaitPromise.all([
	      fetch('url1'),
	      fetch('url2')
	    ])
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **DiegoKardona** (2)

	
	Porqué usamos `let [req1, re2]` en vez de `const [req1, req2]`?
	
	Probé con `const` y me funciona muy bien. Por favor alguien digame que diferencia puede haber entre uno y otro.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Erik Ochoa (Platzi)** (4)

		
		Si usas **const** tanto **req1** como **req2** no podrán ser reasignadas en ningún momento en el código:
		``` 
		    req1 = 'Otro valor'// Esto te muestra un error
		    
		```
		
		**const** se usa para cuando quieres que una variable sea **inmutable** , si este es el caso, adelante.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Diego Ivan Padilla Bernal** (2)

		
		Yo creo que usar **let** lo hizo más por costumbre porque en este caso lo ideal si seria **const** porque no se modifica
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **antony999k** (2)

	
	No me gusto esta clase, se salta muchas cosas que en un principio son difíciles de entender
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		Hola Antony, ¿podrías contarnos que cosas te dieron dificultad?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Nacho Ávila** (2)

	
	Me pregunto si no es más óptimo cargar el contenido de la pagina mínimo con un loader y una vez cargada la página hacer estas request. El tiempo de carga sería el mismo pero tanto para arañas de búsqueda como para el usuario, la página se carga antes aunque sin contenido útil. Creo que es el standard actual. ¿Que opináis?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		No te lo recomiendo, siempre debemos mostrarle a nuestros usuarios contenido para darle cierto feedback de lo que está pasando, y los loaders suelen ser molestos
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **elvis-retiz** (2)
¿Saben que es lo que tengo que hacer para integrar mi aplicación con firebase para usar firestore?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Le_MaliX** (1)

	
	Usando aún mas la desestructuración y cachando errores
	``` 
	    static async getInitialProps({ query: { id } }) {
	        try {
	          const [reqChannel, reqAudios, reqChilds] = await Promise.all([
	            fetch(`https://api.audioboom.com/channels/${id}`),
	            fetch(`https://api.audioboom.com/channels/${id}/audio_clips`),
	            fetch(`https://api.audioboom.com/channels/${id}/child_channels`),
	          ]);
	          const { body: { channel } } = await reqChannel.json();
	          const { body: { audio_clips } } = await reqAudios.json();
	          const { body: { channels } } = await reqChilds.json();
	          return { channel, audio_clips, channels };
	        } catch ({ message }) {
	          return (message);
	        }
	      }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Ricardo José Galarza Palacios** (1)

	
	Un poco mas corto
	``` 
	    staticasync getInitialProps({ query }) {
	        let [reqChannel, reqAudioClips, reqSeries] = awaitPromise.all([
	            fetch(`https://api.audioboom.com/channels/${query.id}`),
	            fetch(`https://api.audioboom.com/channels/${query.id}/audio_clips`),
	            fetch(`https://api.audioboom.com/channels/${query.id}/child_channels`)
	        ]);
	        let channel = (await reqChannel.json()).body.channel;
	        let audioClips = (await reqAudioClips.json()).body.audio_clips;
	        let series = (await reqSeries.json()).body.channels;
	        return {channel, audioClips, series}
	      }```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Alejandro Trejo Cuxim** (1)

	
	## **Promise.all**
	
	Tener en cuenta que puede romperse:  
	_Si alguna de las promesas pasadas en el argumento iterable falla, la promesa all es rechazada inmediatamente con el valor de la promesa que fué rechazada, descartando todas las demás promesas hayan sido o no cumplidas._ \- **MDN**
	
	<h3>Para evitar que se termine el ciclo por “falla” implemente lo siguiente, no es lo mejor pero funciona, espero comentarios.</h3>
	
	Gracias a esto si alguno falla continua la ejecución de las demás.
	``` 
	    const [ requestChannel, requestClips, requestChilds ] = await Promise.all([
	       request.get(`/channels/${idChannel}`, '').catch(error => error),
	       request.get(`/channels/${idChannel}/audio_clips`, '').catch(error => error),
	       request.get(`/channels/${idChannel}/child_channels`, '').catch(error => error)
	    ]);
	    
	```
	
	Utilicé otro cliente HTTP para utilizar las llamadas al API, pero utilicen la Fetch del curso.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Diaz Venero** (1)

	
	Request paralelas a un api, mejora de performance
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Wilson Fabian Pérez Sucuzhañay** (1)

	
	Consulta como se deberia hacer el await si para el siguiente fecht necesita del anterior ya no servivio el all? ¿Qué metodo deberiamos utilizar?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **DiegoKardona** (1)
Porqué usamos let [req1, re2] en vez de const [req1, req2]? Probé con const y me funciona muy bien...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Erik Ochoa (Platzi)** (4)

		
		Si usas **const** tanto **req1** como **req2** no podrán ser reasignadas en ningún momento en el código:
		``` 
		    req1 = 'Otro valor'// Esto te muestra un error
		    
		```
		
		**const** se usa para cuando quieres que una variable sea **inmutable** , si este es el caso, adelante.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **hernandezalejandro** (0)

	
	Asi puede implementarse axios en el getInitialProps
	``` 
	    channel.getInitialProps = async ({ query }) => {
	        let idChannel = query.id;
	    
	        let URL1 = `https://api.audioboom.com/channels/${idChannel}`
	        let URL2 = `https://api.audioboom.com/channels/${idChannel}/audio_clips`
	        let URL3 = `https://api.audioboom.com/channels/${idChannel}/child_channels`
	    
	        let [ reqChannel, reqAudios, reqSeries ] = awaitPromise.all([ axios.get(URL1), axios.get(URL2), axios.get(URL3) ]);
	        
	        const dataChannel = await reqChannel.data;
	        let channel = dataChannel.body.channel;
	    
	        const dataAudios = await reqAudios.data;
	        let audioClips = dataAudios.body.audio_clips;
	    
	        const dataSeries = await reqSeries.data;
	        let series = dataSeries.body.channels;
	    
	        let response = { channel, audioClips, series }
	        return {...response}
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jose Adrian Valentin Rodriguez** (0)
en todo los componentes que maneje muchas consultas tengo que ocupar el promise.all eso no afecta? si consultara muchos componentes en el...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

## 0090. Vista de Podcasts

### Descripción:


Este reto pone a prueba todo lo que venimos aprendiendo hasta el momento en el curso y va a requerir testear todo; desde crear páginas nuevas, hasta tomar atributos y hacer request a una API.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Joaquin Araujo** (8)

	
	Sí a alguien le da el siguiente error en la consola:
	
	![Screenshot from 2018-07-23 16-13-28.png](https://static.platzi.com/media/user_upload/Screenshot%20from%202018-07-23%2016-13-28-ab2179ae-2103-4fdc-a7ef-989a64634f73.jpg)
	
	Es porque “Las keys (que se solicitan en la consola) ayudan que React identifique sí los elementos han cambiado, se han agregado o se han eliminado”, por lo tanto si no las agregas en cada elemento (que retorna el `map`), React tendrá un problema para identificar los elemento (retornados del método `map`).
	
	Lee más [aquí](https://reactjs.org/docs/lists-and-keys.html#keys)
	
	Y solucionalo así:  
	![platzi from 2018-07-23 16-28-08.png](https://static.platzi.com/media/user_upload/platzi%20from%202018-07-23%2016-28-08-7f6d7979-c955-417d-9080-a5e27f0751c7.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Julio Andrés Ramirez De Freitas** (7)

	
	**Reto Cumplido y un poco mas **
	
	![podcast.png](https://static.platzi.com/media/user_upload/podcast-eb617111-dac2-411a-8db0-a14e2e57f703.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Ortiz** (4)

		
		Yo ni pude encontrar cómo se sube una imagen en un comentario de Platzi (sin tener que subirla a un servicio externo)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Alejandro Trejo Cuxim** (2)

		
		Sencillo Diego Ortiz, solamente arrastas la imagen.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **jhon manuel angulo moncada** (3)

	
	Hice un pequeño cambio solo para traer los podcast en español jeje:
	``` 
	    'https://api.audioboom.com/channels/recommended?category_ids[]=179'
	    
	```
	
	![Sin título.png](https://static.platzi.com/media/user_upload/Sin%20t%C3%ADtulo-552c5d6e-4d33-4148-be5c-6655c1c29795.jpg)
	
	dato adicional uso este color en el header y en background de la clase clip #4a148c
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Arturo Lira Cerda** (3)

	
	Listo 😄 Lo bueno de haber tomado cursos anteriores como React, Redux, Fundamentos de JavaScript, etc. es que entiendo perfectamente qué hace el código, no siento que solo copio y pego.
	
	![Podcasts.PNG](https://static.platzi.com/media/user_upload/Podcasts-699f18b5-3266-45fb-8d00-9d91e4bac4f4.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **camiladi** (3)

	
	para los que les suceda como a mi que cuando accedían a la api de audioboom se les veía lineas ilegibles de JSON, el profesor utiliza la extensión de chrome JSONView, aquí les dejo en link para agregarla:
	
	<https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc/related>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Daniel Castillo Nava** (3)

	
	**Reto cumplico!!**
	
	![](https://s3.amazonaws.com/davecast/reto2.png)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Alejandro Trejo Cuxim** (2)
<h3>Utilizando un componente funcional:</h3>
	
	Ya que, las clases son más pesadas, más lentas y todas esas chuchas, funciona bien en función para solo mostrar la información
	``` 
	    const Podcast = (props) => {
	        const { audioClip } = props;
	        return(
	            <divclassName="flex column">
	                <Head>
	                    <title>Heart Radio - Podcast</title>
	                </Head>
	                <Header />
	                <divclassName="podcast justify-center">
	                    {
	                        <h2>
	                            { audioClip.title }
	                        </h2>
	                    }
	                </div>
	            </div>
	        );
	    }
	    Podcast.getInitialProps = async ({ query }) => {
	        const idAudio = query.id;
	        const response = await request.get(`/audio_clips/${idAudio}.mp3`, '');    
	    	return { audioClip: response.body.audio_clip };
	    }
	    
	```
	
	PD: Utilizen el fetch, aquí utilizo otro cliente HTTP
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jsechirinos** (2)

	
	 **Reto Cumplido**
	
	![reto vista podcast](https://image.ibb.co/cwOPST/reto1.png)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Sánchez** (1)

	
	Asi quedo mi página de Podcast! Trate de basarme un poco en PocketCasts 😄
	
	![Screenshot](https://i.imgur.com/uhpalnb.png)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Roberto S. Sampayo** (1)

	
	Así quedo mi podcast page:
	
	![](https://i.imgur.com/MdRHec4.png)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **johnaagudelo** (1)
![Captura de Pantalla 2020-03-18 a la\(s\) 8.57.23 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202020-03-18%20a%20la%28s%29%208.57.23%20p.%C2%A0m.-016ab8d8-c38e-4026-af86-cc298672d499.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jdpo2008** (1)

	
	Reto Logrado
	
	![Reto_Platzi_curso_Nextjs.png](https://static.platzi.com/media/user_upload/Reto_Platzi_curso_Nextjs-7c638868-a68c-45eb-8a6c-1ef2f3eb04db.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **CodingLeonardo** (1)

	
	💚😎**Reto Completado!**💚😎  
	![screencapture-localhost-3000-podcast-2020-01-18-17_51_43.png](https://static.platzi.com/media/user_upload/screencapture-localhost-3000-podcast-2020-01-18-17_51_43-a3793494-d786-41f0-9565-c0722dea3624.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (1)

	
	Todo el reto lo monte en CodeSanBox, les comparto la URL correspondiente a la practica
	
	**Codigo**  
	<https://codesandbox.io/s/taller-de-next-cf1dj>
	
	**Montado en un server**  
	<https://cf1dj.sse.codesandbox.io/>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Manuel Ojeda** (1)

	
	Reto completado 🤘
	
	![msedge_NNuif4lddh.png](https://static.platzi.com/media/user_upload/msedge_NNuif4lddh-5330a320-ba1d-414c-86e0-e8fd59550466.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Wilson Marino Pablo Mendez** (1)

	
	Genail!!  
	Usando variables dinamicos en css _(background-image:url($image-portada))_
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **josdanind** (1)

	
	Roberto usó una API muy enredada para este proyecto, me a llevado tiempo entender el JSON. Para la próxima una más sencilla, como una de pokemón, jajaja.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Danner Adib Uribe** (1)

	
	Hola, alguien sabe porque este error:  
	![Captura de pantalla 2019-06-07 a la\(s\) 2.34.10 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-06-07%20a%20la%28s%29%202.34.10%20p.%20m.-4d5bbb78-166f-493c-b2c4-4a7aae8271f5.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Simón Rotjes** (1)

		
		audioClips es undefinded o null, probably un typo, checkea la linea de codigo donde creaste esa variable e hiciste el call
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **EnmanuelCastillo** (1)
Verifica a ver si la llamada a la api la nombraste con la constante Clips o si la guardaste en otra variable
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Gaston Morales** (1)

	
	 **Hola, tengo un problema, en algunos podcast todo funciona correctamente, mientras que en otros, me da este error, alguno tienen un solución a esto ?**
	
	**![error 1.jpg](https://static.platzi.com/media/user_upload/error%201-4946c913-92d8-4ad0-99c2-be424b9cffae.jpg)![error 2.jpg](https://static.platzi.com/media/user_upload/error%202-7eaf5bd4-70ec-471c-bd3e-cd8c67ce09d4.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **LeandroVidela** (1)

	
	Reto cumplido! No se veía la imagen y tuve modificar **picture**.
	``` 
	    picture 
	      background: inherit
	      height:250px
	      padding:10px
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **alexjcm** (1)

	
	Hasta ahora todo se me ha hecho algo fácil, menos lo de css, creo que tendré que seguir el curso de CSS. 😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **esdraspavon** (1)

	
	Vamooos!!
	
	![podcast.png](https://static.platzi.com/media/user_upload/podcast-f73a2f2d-6f7d-4a99-8640-7179f1033ef6.jpg)
	
	💪 💪
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

# Componentes Reutilizables

## 0100. Creando componentes en React

### Descripción:


La idea de un componente es identificar código duplicado o cosas que realmente no queremos copiar y pegar y separarlas en archivos independientes y reutilizables.

En esta clase vamos a empezar a crear componentes de React, no sólo páginas, sino los módulos que componen estas páginas.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **David Daniel Castillo Nava** (8)

	
	Cuando te pones a escuchar podcast en el mismo app que acabas de montar!! 😄 Cada vez se pone mas interesante el curso
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Diego Ivan Padilla Bernal** (3)

	
	Para ChannelGrid y Layout no se debieron usar componentes stateful sino más bien stateless así esos componentes quedarían más legibles.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Ortiz** (1)

		
		Tome la idea y efectivamente, lo transformé en un stateless, así:
		``` 
		    import css from'./channelGrid.scss'
		    import Link from'next/link'
		    
		    const ChannelGrid = (props) => {
		        const channels = props.channels
		    
		        const channelsList = channels.map(channel => (
		            <Linkhref={`/channel?id=${channel.id}`}key={channel.id}>
		                <aclassName={css.channelContainer}>
		                    <imgclassName={css.channelImg}src={channel.urls.logo_image.original} />
		                    <h2className={css.channelTitle}> {channel.title} </h2>
		                </a>
		            </Link>
		        ))
		    
		        return <divclassName={css.channels}>
		            {channelsList}
		        </div>
		    }
		    
		    export default ChannelGrid
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Sergio Minei** (3)

	
	## Creando Componentes
	
	La idea de un componente es identificar código duplicado o cosas que realmente no queremos copiar y pegar y separarlas en archivos independientes y reutilizables.
	
	Se recomienda crear los componentes dentro de una carpeta **components**.
	
	El nombre de los componentes y su respectivo archivo .js deben se escribirse en **PascalCase**.
	
	Si se desea que un componente renderee los elementos hijos, se hace con la propiedad `props.children`.
	``` 
	    import Link from'next/link';
	    import Head from'next/head';
	    
	    exportdefaultclassLayoutextendsReact.Component{
	      render () {
	        const { children, title } = this.props;
	        return (
	          <div>
	            { children }
	          </div>
	        )
	      }
	    }
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jsechirinos** (3)

	
	 **Recapitulación**  
	Siempre empezar por papel diseñando la api que queremos usar:
	
	  * Crear Componentes: evitar la duplicidad de código
	  * Separar en Componentes: Simples(solo render con props), Smart Components (con Lógica)
	
	
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **mariomenjr** (3)

		
		Del curso de Leonidas 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Betty Rossana Jimenez Cedeño** (2)

	
	Es mi idea, o el link que se esta usando para la API, es intendible
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **kevinspider** (2)

	
	Hola, haciendo la creación de los componentes al pasarle el prop al ChannelGrid me tira un error diciendo que .map no esta definido alguien sabe por que sucede
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Simón Rotjes** (1)

		
		Verifica que el objeto que estas pasando como una prop no sea null.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Luis Manuel Brito Romero** (1)

		
		Compañero. en el componente ChannelGrid, cuando asignas props a channels hay que hacerlo de esta manera
		``` 
		    const ChannelGrid = (props) => {
		        const channels = props.channels;
		        return ( 
		            <div className="channels">
		                {
		                    channels.map((channel) => ( 
		                        <Link href={`/channel?id=${channel.id}`} key={channel.id}>
		                            <a className='channel'>
		                                <img src={channel.urls.logo_image.original} alt=""/>
		                                <h2>{channel.title}</h2>
		                            </a>
		                        </Link>
		                    ))
		                }
		    
		                <style jsx> {`
		                .channels {
		                    display: grid;
		                    grid-gap: 15px;
		                    padding: 15px;
		                    grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
		                }
		                a.channel {
		                    display: block;
		                    margin-bottom: 0.5em;
		                    color: #333;
		                    text-decoration: none;
		                }
		                .channel img {
		                    border-radius: 3px;
		                    box-shadow: 0px 2px 6px rgba(0,0,0,0.15);
		                    width: 100%;
		                }
		                h2 {
		                    padding: 5px;
		                    font-size: 0.9em;
		                    font-weight: 600;
		                    margin: 0;
		                    text-align: center;
		                }
		                `}
		                </style>
		            </div>
		    
		            
		         );
		    }
		     
		    export default ChannelGrid;
		    <code>
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Eduardo Hidalgo Díaz Rugama** (2)

	
	o woao. que grande! que magistral. en 15 minutos explicó perfectamente como integrar next.js con react, enseño patrón de componentes con react, y enseñó props, children y map.
	
	Estoy yendo a twitter a hacerle follow al profesor, y a seguirle la pista de cualquier curso que de.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Joaquin Araujo** (2)

	
	Tal como dijo Robert, el `<Head />` se puede colocar en cualquier lugar del código pero **algo que siempre debes de tener en cuenta es: “Usar buenas prácticas”** , tu código seguramente lo mirará otro dev (o tu yo del futuro) y es necesario que lo entienda.
	
	La traducción de `<Head />` es Cabeza; por sentido común debería estar al principio del código 😃
	
	“Los individuos marcan goles, pero los equipos ganan partidos”, Zig Ziglar.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (2)

	
	¿Hace falta importar isomorphic-fetch en cada uno de los js de pages? Actualmente lo estoy importando unicamente dentro del index pero no estoy seguro si al ponerse en producción me afecte el no importarlo en los demás.
	
	De antemano gracias,  
	Saludos! 😃
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (8)

		
		Es muy recomendable importar las librerías que utilices en cada archivo para evitar problemas o bugs a futuro (ya sean isomorphic-fetch, componentes u otras funciones). Olvidarse de importar libs a veces crea bugs donde una página anda navegando desde el browser (desde la home a una page en particular), pero que crashea si entrás directamente y Next tiene que hacer server side rendering.
		
		Otro caso es que en Next no suele hacer falta importar React en páginas o componentes, pero en cuanto empezás a agregar con algunos plugins de webpack el compilador falla con un error críptico si no importás React explícitamente. Cuando te pasa podés estar un rato largo googleando hasta descubrir que es por eso.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **.** (1)

		
		En mi caso yo siempre he visto que solamente lo tienes que importar donde estés haciendo el fetch ya que ahí es donde vas a usar la funcionalidad de lo que estás importando.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **WilliamVelazquez** (2)

		
		Muchas gracias! @robertomgonzalez y @carlossz como mencionas más vale agregarlo para evitar cualquier bug! 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **RBN1993** (1)

		
		Lo que puedes hacer es crear un servicio api.js donde llamarías una sola vez a esa librería y exportas las llamadas a las apis que vayas a usar. Así de esa manera tienes toda esa lógica en un solo sitio y la importas donde te sea necesario sin repetir código.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Ivan Magdaleno** (1)

	
	¿Es adecuado usar un <a> dentro de un componente <Link>?
	
	¿No se supone que el componente <Link> al momento de renderizarse, genera un <a>?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Matias Alejandro Lopez Heredia** (1)

		
		Respondió a tu duda en un video anterior en donde explicó el componente Link de Next. Este a diferencia de otros, no genera un tag a, lo que hace es inyectarle la propiedad href definida en Link a un tag a definido por el programador. En resumen, tenés que crear un tag a adentro de Link, o no te va a funcionar.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **onlinejaime** (1)

	
	No me funciona cuando hago lo de <Head>, no recibe los props y no cambia el título en la pestaña… ¿Será porque uso Windows? No entiendo el porqué. Todo lo demás funciona.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **onlinejaime** (1)

		
		Solución:
		
		[](url)<https://github.com/zeit/next.js/issues/5774>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Kelly Jesus Salazar Sanchez** (1)

	
	Mi codigo
	``` 
	    import React from 'react'
	    import 'isomorphic-fetch'
	    import Layout from '../components/Layout'
	    import ChannelGrid from '../components/ChannelGrid'
	    
	    
	    const Home = ({ channels }) => (
	      <Layouttitle="Podcasts">
	          <ChannelGridchannels={channels } />
	        </Layout>
	    )
	    
	    Home.getInitialProps = async () => {
	      let req = await fetch('https://api.audioboom.com/channels/recommended')
	      let { body: channels } = await req.json()
	      return { channels }
	    }
	    exportdefault Home```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Salazar** (1)

	
	No era mas facil iniciar el proyecto ya armando los componentes y dejando una estructura mas legible del todo el proyecto?, y a su vez hubiese sido un gran plus para entender de forma mas legible Next.js. A veces me hace sentir que el que dicta este curso carece de conocimientos sobre como explicar sin tantas vueltas.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Cristian Camilo Cucunubá** (6)

		
		Si hubiera sido mas facil para una persona que sabe react, pero como este curso tambien sirve para personas que nunca han programado con react, es mas facil explicarlo escribiendo todo el codigo de una.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **jenapi** (1)

		
		sinceramente este me parece que es uno de los mejores cursos de react que he tomado en platzi, el profesor me hace querer seguir viendo las clases y la forma de explicar está muy bien. Ningún concepto ha sido redundante y cada vez que introduce algún conocimiento nuevo viene acompañado de su lamina para explicar
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **javier alejandro segovia** (1)

	
	La api de series no se cargando. haci descargue el archivos de pestaña , y tampoco funciona.  
	No puedo ver la serie.  
	Necesito ayuda
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Revisa que no tengas errores en la consola.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Andres.F.Delgado** (1)

	
	Porqué await está encerrado entre paréntesis ?
	``` 
	    let clip = (await fetchClip.json()).body.audio_clip
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (2)

		
		Es para tomar el .body.audio_clip del resultado del await en una sola línea. Sería equivalente a hacer:
		``` 
		    letclipData = await fetchClip.json()
		    letclip = clipData.body.audio_clip
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Carlos Rivas** (1)

		
		Muy brutal tu forma de optimizar el código, @robertomgonzalez, ¿sigues alguna guía en particular o lo aprendiste de algún lado?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Juan  Reyes** (1)

	
	Nunca ames a nadie de Posta jajaja
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (1)
Por que siempre ponen dentro de div vacios y no utilizan fragmernt?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Alejandro Robleto** (1)
a mi me marca un error en el index al guardar los cambio de channelgrid me dice que no esta 😕
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Juan David Castro (Platzi)** (1)

		
		¡Hola!
		
		¿Podrías mostrarnos una captura del error? Y también tu código. Así sin esa info es muy difícil adivinar cuál es la solución. 😅🐛🙏
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **nik020** (1)
Mmm yo hubiera hecho un componente que sea el item del podcast, dentro de ChannelGrid o reemplazarlo por channelGrid y el loop en el home...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Rubén Jiménez Uribe** (1)
Al guardar ChannelGrid.js a mi me marco error de que no tenía importado Link, pero en el video veo que no esta importado. What!? Bueno en...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **RafaelTorresE** (1)
Por qué tengo el siguiente error cuando quiero renderizar? React.Children.only expected to receive a single React element child.<...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Debes estar haciendo return de dos elementos html, intenta solo devolver uno conteniendo los dos dentro de un div por ejemplo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **javier alejandro segovia** (1)
La api de series no se cargando. haci descargue el archivos de pestaña , y tampoco funciona. No puedo ver la serie. Necesito ayuda
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Revisa que no tengas errores en la consola.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Andres.F.Delgado** (1)
Porqué await está encerrado entre paréntesis ? let clip = (await fetchClip.json()).body.audio_clip 
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (2)

		
		Es para tomar el .body.audio_clip del resultado del await en una sola línea. Sería equivalente a hacer:
		``` 
		    letclipData = await fetchClip.json()
		    letclip = clipData.body.audio_clip
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (1)
¿Hace falta importar isomorphic-fetch en cada uno de los js de pages? Actualmente lo estoy importando unicamente dentro del index pero no...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **robertomgonzalez** (8)

		
		Es muy recomendable importar las librerías que utilices en cada archivo para evitar problemas o bugs a futuro (ya sean isomorphic-fetch, componentes u otras funciones). Olvidarse de importar libs a veces crea bugs donde una página anda navegando desde el browser (desde la home a una page en particular), pero que crashea si entrás directamente y Next tiene que hacer server side rendering.
		
		Otro caso es que en Next no suele hacer falta importar React en páginas o componentes, pero en cuanto empezás a agregar con algunos plugins de webpack el compilador falla con un error críptico si no importás React explícitamente. Cuando te pasa podés estar un rato largo googleando hasta descubrir que es por eso.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0110. Reorganizar la vista de podcasts

### Descripción:


En este reto tendremos que aplicar lo que aprendimos en la clase anterior sobre refactoring, al resto de la aplicación.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Links:

* [Using the viewport meta tag to control layout on mobile browsers - Mozilla | MDN](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag)

### Comentarios:

* **David Daniel Castillo Nava** (15)

	
	 _ **Reto cumplido**_
	
	_Home_  
	![](https://s3.amazonaws.com/davecast/reto31.png)
	
	_Channel_  
	![](https://s3.amazonaws.com/davecast/reto32.png)  
	_  
	Clip_  
	![](https://s3.amazonaws.com/davecast/reto33.png)
	
	Cada vez me gusta mas el curso y usar **React** con **Next.js**
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Ramiro Calo** (1)

		
		Hola, podrías compartir tus styles de channel? me gustó como te quedó.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Joaquin Araujo** (4)

	
	Les cuento que así quedó mi `<PodcastList />`
	
	![Screenshot from 2018-07-25 18-09-26 \(1\).png](https://static.platzi.com/media/user_upload/Screenshot%20from%202018-07-25%2018-09-26%20%281%29-6d10a15e-ab41-498b-9c83-e53948286d3f.jpg)
	
	¿Te gustaría saber como lo hice? Aquí te comparto el [enlace](https://github.com/JoaquinAraujo/podcasts-app/tree/a5b63e3b52e619d6b6030e6a1c01ee8a5ec6d4f1) a el repositorio donde almacenaré el proyecto del curso.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **david vicent** (3)

	
	No se ve la vista del iphone X
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		¡Hola David! ¿Te sale algún error con la vista del iPhone? Recuerda que el profesor está usando Mac y Xcode
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **alexabellerman** (2)
![Screen Shot 2020-01-03 at 03.36.16.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-01-03%20at%2003.36.16-14829499-51b3-450e-97b2-99c9cbae6460.jpg) ![Screen Shot 2020-01-03 at 03.36.31.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-01-03%20at%2003.36.31-10ae3f65-1565-4787-8044-bd5284a873ba.jpg) ![Screen Shot 2020-01-03 at 03.36.38.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-01-03%20at%2003.36.38-644f878d-5b4e-47ac-9ee2-a025e94ccb45.jpg) ![Screen Shot 2020-01-03 at 03.36.50.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-01-03%20at%2003.36.50-3591fea6-bfc7-43de-933a-a521a7c7b5d8.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jhurgen Maraza** (2)

	
	Soy el único al que no le funciona el link de <https://api.audioboom.com/channels/recommended> ?  
	me lo devuelve vacío…
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Salazar** (1)

		
		A mi me paso lo mismo con series, con un conditional rendering filtrando si viene vacio o no, queda mas prolijo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		¡Hola Jhurgen! He probado esa URL y pues si tiene datos en JSON, ¿qué clase de error te da a ti?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **David Esteban Higuita Velasquez** (2)

	
	¿cómo se puede observar la data que retorna un api en next?  
	Me refiero a ver la respuesta directa del api similar a cómo se ve en el network de chrome cuando se crea una app con create-reacat-app, es decir, allá puedo ver el api consumido y la data que llega, y supongo que como en next ya está el server-side-rendering la forma es distinta, pero no se cómo hacerlo
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		Puedes hacer un `console.log()` después de obtener los datos e imprimirlo en la consola
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **jhon manuel angulo moncada** (1)

	
	Reto cumplido…
	``` 
	    import Layout from '../components/Layout'
	    import ChannelGrid from '../components/ChannelGrid'
	    import PodcastList from '../components/PodcastList'
	    
	    export default class extends React.Component {
	    
	      static async getInitialProps({ query }) {
	        let idChannel = query.id
	    
	        let [reqChannel, reqSeries, reqAudios] = await Promise.all([
	          fetch(`https://api.audioboom.com/channels/${idChannel}`),
	          fetch(`https://api.audioboom.com/channels/${idChannel}/child_channels`),
	          fetch(`https://api.audioboom.com/channels/${idChannel}/audio_clips`)
	        ])
	    
	        let dataChannel = await reqChannel.json()
	        let channel = dataChannel.body.channel
	    
	        let dataAudios = await reqAudios.json()
	        let audioClips = dataAudios.body.audio_clips
	    
	        let dataSeries = await reqSeries.json()
	        let series = dataSeries.body.channels
	    
	        return { channel, audioClips, series }
	      }
	    
	      render() {
	        const { channel, audioClips, series } = this.props
	    
	        return <Layout title={channel.title}>
	    
	          <div className="banner" style={{ backgroundImage: `url(${channel.urls.banner_image.original})` }} />
	    
	          {series.length > 0 &&
	            <React.Fragment>
	              <h1>{channel.title}</h1>
	              <ChannelGrid channels={series} />
	            </React.Fragment>
	          }
	    
	          <PodcastList audioClips={audioClips} />
	    
	          <style jsx>{`
	            .banner {
	              width: 100%;
	              padding-bottom: 25%;
	              background-position: 50%50%;
	              background-size: cover;
	              background-color: #aaa;
	            }
	    
	            h1 {
	              font-weight: 600;
	              padding: 15px;
	            }
	          `}</style>
	        </Layout>
	      }
	    }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **SOFTDYNAMIC** (1)
![](https://scontent.flim9-1.fna.fbcdn.net/v/t1.0-9/71567023_2596349897115579_5998322450528468992_n.jpg?_nc_cat=104&_nc_oc=AQkwGh4PeIxAQVvkoZ5Tg9qb1416Yz0UMNVNPkw3VGsf3IT3MXdk0FMoT2IJWiNbvV8&_nc_ht=scontent.flim9-1.fna&oh=f1e5b8739503c220b41323454c958906&oe=5E302199)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **esdraspavon** (1)

	
	**_Reto cumplido!! _** 💪
	
	![channel.png](https://static.platzi.com/media/user_upload/channel-e8310763-52da-493c-8d0f-b561978e692f.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jhurgen Maraza** (1)
Soy el único al que no le funciona el link de https://api.audioboom.com/channels...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Salazar** (1)

		
		A mi me paso lo mismo con series, con un conditional rendering filtrando si viene vacio o no, queda mas prolijo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

# Navegación Avanzada

## 0120. Gestionando Errores

### Descripción:


En esta clase vamos a empezar a ver uno de los temas más importantes que tenemos que tener en cuenta cuando hacemos una aplicación un poquito más compleja, y es: ¿Qué pasa en nuestra aplicación si se rompe algo?
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Links:

* [GitHub - zeit/next.js: Next.js is a lightweight framework for static and server?rendered applications.](https://github.com/zeit/next.js/#custom-error-handling)

### Comentarios:

* **jsechirinos** (9)

	
	Si todo correcto: 200,  
	Si no existe el contenido: 404,  
	Si se prendió fuego el data center y no funciona el server: 503,  
	jejej excelente clase…
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Minei** (5)

	
	## Manejo de Errores
	
	Cuando hacemos Server Side Rendering, nuestros servidor responde con un status.
	
	  * **Status 200** : Todo está bien.
	  * **Error 404** : Página no existe
	  * **Error 503** : Hay un probblema de red o la API no está funcionando.
	
	
	
	Se debe de hacer un manejo de control de errores en un bloque de `try/catch`. Además se debe de agregar un `if` para manejar el status que retorna el fetch. Por último, se tiene que cambiar el `res.statusCode` para que el servidor maneje internamente el error que ocurrió.
	``` 
	    staticasync getInitialProps({ query }) {
	      let idChannel = query.id;
	    
	      try {
	    
	        let req = await fetch('https://api.audioboom.com/channels/recommended');
	    
	        if(req.status >= 400) {
	          res.statusCode = req.status;
	          return { tatusCode: req.status }
	        }
	    
	        //más código
	    
	        return { statusCode: 200 }
	    
	      } catch(e) {
	        return { statusCode: 503}
	      }
	    }
	    
	```
	
	Para el manejo de errores Next.js nos da un componente llamado `<Error/>`.
	``` 
	    importErrorfrom'next/error';
	    
	```
	
	Luego, dentro del componente:
	``` 
	    const { statusCode } = this.props;
	    
	    if(statusCode !== 200) {
	      return<ErrorstatusCode={statusCode}/>
	    }
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Daniel Alberto Esquinazi** (3)

		
		recuerda que tienes q obtener el objeto res de los parametros
		``` 
		    staticasyncgetInitialProps({ res }) {
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Minei** (2)

		
		muchas gracias por el dato @esquinazi 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Matias Alejandro Lopez Heredia** (2)

	
	Se puede “catchear” errores de promesas de dos formas nativas en JavaScript.
	
	  1. Seria usar try/catch como lo hicieron en esta lección.
	  2. Otra seria usar .then().catch(), el then es una función que como parametro tiene el resultado correcto de la promesa, y el catch es lo mismo pero cuando la promesa tuvo un error.
	
	
	
	Ahora, fuera de lo nativo de JS, hay otras formas, una que particularmente me gusta es una biblioteca llamada “await-to-js”, la pueden encontrar en el siguiente enlace: [await-to-js](https://www.npmjs.com/package/await-to-js)  
	Con esta library, envolvemos la promesa en una función llamada “to”, y esta nos retorna un arreglo de dos objectos, en la posición 0 un objeto de error, si la promise salió mal, y en la posición 1, el objeto resultado de la respuesta correcta de la promise.
	``` 
	    import to from'await-to-js'// Importan la library
	    const [error, response] = await to(fetch("http://...")) // Envuelven la promesa
	    
	```
	
	Luego podrían manejar el error de la siguiente forma:
	``` 
	    if (error) {
	      // Manejar el error
	      return { statusCode: error.status }
	    }
	    // Usar el response para lo que sea nesecario, ya que no existe ningún error.
	    // Por ej:
	    return { data: response.data, statusCode: response.status }
	    
	```
	
	Espero les sirva 😃
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **LeandroVidela** (2)

	
	No entiendo porque seteamos a 200 el statusCode en caso de éxito. No sería correcto asignarle el valor del status del request ( req.status )?
	
	Si dejamos el código como lo vimos en la clase y tenemos un error de tipeo en la URL del Fetch nos tira un error horrible, mientras que si cambiamos el valor de statusCode a req.status no devuelve un error 404, que entiendo sería lo más correcto, ya que lo URL a la que le hacemos la petición no existe.
	
	Dejo acá mi código:
	``` 
	    static async getInitialProps({ res }) {
	        try {
	          let req = await fetch("https://api.audioboom.com/channels/recommended");
	          let { body: channels } = await req.json();
	    
	          return { channels, statusCode: req.status };
	        } catch (error) {
	          res.statusCode = 503;
	          return { channels: null, statusCode: 503 };
	        }
	      }
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Agustín Castro** (2)

	
	Hola!
	
	Como se gestionan los errores que capturamos en componentDidCatch por un componente?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jose Galbis Soler** (1)

	
	No has vuelto a conectar el wifi! En el minuto 11.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Roberto S. Sampayo** (1)

	
	Chicos, me aparece este error:
	``` 
	    index.js:1 Warning: Can't perform a React state updateon an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions andasynchronous tasks in a useEffect cleanupfunction.
	    
	```
	
	¿a que se debe y como lo soluciono?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WSJedp** (1)

	
	El manejo de errores es uno de los componentes mas importantes de todo desarrollo web, un buen manejo de errores le servirá tanto a los usuarios para guiarse mejor dentro del sitio web como para nosotros para ubicar el desarrollo web en una mejor posición en la web gracias al SEO.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Alejandro Robleto** (1)

	
	wow este manejo de errores fue magico, con sinceridad hasta ahora me quedo mas claro como udarlos y manejarlo ademas de la buena teoria. fue magistral … gracias!!!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **santiagomarcano** (1)

	
	Primero que nada agradecer por el curso!
	
	En el manejo de errores del Promise.all() si falla el fetch a los audio clips o a las series y no el channel la app tira error de undefined corriendo en entorno de desarrollo.
	
	Luego de un par de pruebas me di cuenta que, en produccion, por suerte, Next nos cubre la espalda y por defecto tira un error 500 si hay falla en alguna request. No es lo mas ideal en UX pero por lo menos no vemos un error chungo de código.
	
	Alguien propone alguna solución a eso? He estado intentado un par de cosas pero no he llegado a la solución de momento.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Sergio Alejandro Trejo Cuxim** (2)

		
		Tengo una solución para ti.  
		Añade un catch a cada petición, de modo que si uno falla regresará el “reject” y no se disparará en error global.  
		Utilizo yo otro cliente HTTP, tu utiliza el fetch.
		``` 
		    const [ requestChannel, requestClips, requestChilds ] = await Promise.all([
		       request.get(`/channels/${idChannel}`, '').catch(error => error),
		       request.get(`/channels/${idChannel}/audio_clips`, '').catch(error => error),
		       request.get(`/channels/${idChannel}/child_channels`, '').catch(error => error)
		    ]);
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Le_MaliX** (1)

		
		Yo lo solucione de la siguiente manera:
		``` 
		    // En el if evaluamos si alguno de los tres requests
		    // es mayor a 400
		    if (
		            reqChannel.status >= 400
		            || reqAudios.status >= 400
		            || reqChilds.status >= 400
		          ) {
		            // El res.statusCode lo igualamos al valor mas
		            // grande de los 3
		            res.statusCode = Math.max(reqChannel.status, reqAudios.status, reqChilds.status);
		            // Finalmente en el return devolvemos el res.statusCode
		            // como statusCode
		            return {
		              channel: null, audioClips: null, series: null, statusCode: res.statusCode,
		            };
		          }```
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **AlexRodriguez1218** (1)

	
	iba a preguntar algo, pero sinceramente el profesor explica de forma tan sencilla que en la redaccion de la pregunta la respondi… sos grande…!!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **RBN1993** (1)

	
	@robertomgonzalez al quitar la red y desplazarme en el navegador hacia atrás y volver a channel me dice que res no está definido. La solución hardcodeada que he puesto es if (res) res.statusCode = 503 pero, ¿me puedes dar una solución mejor y explicarme a qué se debe ese error?  
	Gracias.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (1)

		
		Hola, la variable `res` debe llegarte como parámetro desde la función `getInitialProps({ res })`, por si llega `undifined` podrías poner un valor **default** cuando llega como parámetro desde la función de la siguiente forma: `getInitialProps({ res = {} })` y te ahorras en hacer esa validación con un `if`.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Carlos Andrés Cobo Sinisterra** (1)

	
	Hola mi gente, pregunta, podemos cambiar a diferentes idiomas los mensajes de error? o personalizar el texto usando el tag Error de next?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eduardo Hidalgo Díaz Rugama** (2)

		
		No hay ningún tag de error en next, y no, no puedes poner varios idiomas para los mensajes de error. Al menos no como supongo que tu crees que se podría hacer.
		
		Para personalizar tu página de error en Next te recomiendo ir al curso de Next y ver esa sección. esta muy bien explicado. adicional: <https://nextjs.org/docs/#custom-error-handling>
		
		Para el idioma, debes usar alguna librería de internacionalización (i18n). Eso es un poco más complejo, pero se puede. Otra manera es que hagas tu propia librería de internacionalización.
		
		Para hacer tu propia librería necesitas 2 cosas:
		
		  1. detectar el idioma en el navegador
		  2. tener archivos (como json por ejemplo) donde almacenes las traducciones.
		
		
		
		entonces según el idioma que detectaste, haces que toda la aplicación consuma los textos del mismo idioma.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Tobías Schwarz** (1)

	
	La página de channels me queda en en blanco con el texto “An unexpected error has occurred” pero no tengo ningún error en la consola de next ni en la del navegador ni en la pestaña network del navegador
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Diego Fernando Berrio Meza** (1)

	
	 **Alerta de spoiler**  
	Presten atención
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Adriann Felipe Sanchez Sierra** (1)

	
	No hay una forma de tener un componente que englobe todo y que éste tenga control sobre algún error generado sobre los componentes que estén dentro? Algo así como se realiza en el curso de React Native.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Matias Martínez** (2)

		
		Si mal no recuerdo hay un apartado en el curso de React que te enseña el manejo de errores. La verdad no tengo muy claro como funciona porque en la practica no lo eh usado.
		
		Saludos,  
		Tito
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Daniel Alberto Esquinazi** (1)

	
	No entendí por que solamente asignamos el status code a la respuesta en los casos de error, deberíamos asignarlos también en el caso de éxito? es decir
	
	`res.StatusCode = 200`
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		En este momento de la clase <https://platzi.com/clases/next-js/concepto/navegacion-avanzada/gestionando-errores/material/?time=533> retorna el status code 200 si todo funciona y 503 si hay error de conexión por ejemplo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Daniel Alberto Esquinazi** (1)

		
		Gracias por la respuesta pero viendo la clase nuevamente pude escuchar que explica esto.En el caso de éxito el valor por defecto de `res.statusCode` es `200` y por eso es que no lo asigna.
		
		tiempo 8:15 aproximadamente
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **RBN1993** (1)
@robertomgonzalez al quitar la red y desplazarme en el navegador hacia atrás y volver a channel me dice que res no está definido. La solu...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (1)

		
		Hola, la variable `res` debe llegarte como parámetro desde la función `getInitialProps({ res })`, por si llega `undifined` podrías poner un valor **default** cuando llega como parámetro desde la función de la siguiente forma: `getInitialProps({ res = {} })` y te ahorras en hacer esa validación con un `if`.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Carlos Andrés Cobo Sinisterra** (1)
Hola mi gente, pregunta, podemos cambiar a diferentes idiomas los mensajes de error? o personalizar el texto usando el tag Error de next?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eduardo Hidalgo Díaz Rugama** (2)

		
		No hay ningún tag de error en next, y no, no puedes poner varios idiomas para los mensajes de error. Al menos no como supongo que tu crees que se podría hacer.
		
		Para personalizar tu página de error en Next te recomiendo ir al curso de Next y ver esa sección. esta muy bien explicado. adicional: <https://nextjs.org/docs/#custom-error-handling>
		
		Para el idioma, debes usar alguna librería de internacionalización (i18n). Eso es un poco más complejo, pero se puede. Otra manera es que hagas tu propia librería de internacionalización.
		
		Para hacer tu propia librería necesitas 2 cosas:
		
		  1. detectar el idioma en el navegador
		  2. tener archivos (como json por ejemplo) donde almacenes las traducciones.
		
		
		
		entonces según el idioma que detectaste, haces que toda la aplicación consuma los textos del mismo idioma.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Tobías Schwarz** (1)
La página de channels me queda en en blanco con el texto “An unexpected error has occurred” pero no tengo ningún error en la consola de n...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Adriann Felipe Sanchez Sierra** (1)
No hay una forma de tener un componente que englobe todo y que éste tenga control sobre algún error generado sobre los componentes que es...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Matias Martínez** (2)

		
		Si mal no recuerdo hay un apartado en el curso de React que te enseña el manejo de errores. La verdad no tengo muy claro como funciona porque en la practica no lo eh usado.
		
		Saludos,  
		Tito
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0130. Personalizando errores

### Descripción:


En esta clase el profesor Roberto González nos explica como podremos personalizar errores cuando estamos usando Next.js en nuestra aplicación para generar un buen Server Side Rendering y personalizar nuestras páginas de errores para hacer nuestros propios diseños.

Next.js es un framework para construir aplicaciones web modernas en React. Una de sus principales características es que es pensado para tener una excelente experiencia como desarrollador; pero una característica más poderosa es generar un buen SSR para el cliente y manejar el SEO mucho más optimizado, los buscadores nos podrán encontrar más rápido y Google nos indexará muchísimo mejor gracias al SSR agregado.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **jsechirinos** (7)

	
	Código base de `_error.js`
	
	<https://github.com/zeit/next.js/#custom-error-handling>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Eduardo Rasgado Ruiz** (5)

	
	Que pasa si el error está en el getInirialPros({ res })??. Pasa que entré en un 404 y mi enlace con Link dirige a “/” pues si me desconecto de internet y cliqueo “Volver a home” (desde el 404 o 503 después de desconectarme del internet), sorpresa: Me tira un error del tipo red is undefined! Como lo manejamos?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **jobcoronadoduran** (1)

		
		igual me pasa lo mismo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Sergio Minei** (4)

	
	## Personalizando Errores
	
	El componente error se puede modificar creando una página **_error.js**.
	``` 
	    //Ejemplo de _error.js
	    import React from'react'
	    
	    exportdefaultclassErrorextendsReact.Component{
	      static getInitialProps({ res, err }) {
	        const statusCode = res ? res.statusCode : err ? err.statusCode : null;
	        return { statusCode }
	      }
	    
	      render() {
	        return (
	          <p>
	            {this.props.statusCode
	              ? `An error ${this.props.statusCode} occurred on server`
	              : 'An error occurred on client'}
	          </p>
	        )
	      }
	    }
	    
	```
	
	## Personalizar Document
	
	Las páginas en Next saltan la definición de markup de un documento. Por ejemplo, nunca se usa `<html>` o `<body>`. Para modificar este comportamiento, se crea se crea una página **_document.js**.
	
	Document maneja los componentes básicos que devuelve Next cuando hace Server Side Rendering. Esto solo debe de hacerse cuando es necesario.
	
	Document solo se usa para renderizar Server Side y no debería tener nada funcional.
	
	**¿Cuándo modificarlo?**
	
	  * Google AMP
	  * Facebook Instant Pagees
	  * Plugins como Styles Components
	
	
	``` 
	    // ./pages/_document.js
	    import Document, { Head, Main, NextScript } from'next/document'
	    
	    exportdefaultclassMyDocumentextendsDocument{
	      staticasync getInitialProps(ctx) {
	        const initialProps = await Document.getInitialProps(ctx)
	        return { ...initialProps }
	      }
	    
	      render() {
	        return (
	          <html>
	            <Head>
	              <style>{`body { margin: 0 } /* custom! */`}</style>
	            </Head>
	            <body className="custom_class">
	              <Main />
	              <NextScript />
	            </body>
	          </html>
	        )
	      }
	    }
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **raulfbgomez** (2)

	
	Actualmente, Enero de 2020 ha cambiado un poco la manera de manejar la pagina de error. Pueden ver la documentación [aquí.](https://nextjs.org/docs/advanced-features/custom-error-page)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Jose Galbis Soler** (1)

		
		Si cierto, estaba dandome un error distinto al 404, y he entrado a observar la api de next.js. Entonces tambien me he dado cuenta que no gastan class sino function para definir las pages y los componentes. Aunque esto sigue funcionando no me queda claro si es una forma de hacerlo de versiones anteriores y en futuras versiones se recomienda el uso de functions o si no tiene nada que ver, y simplemente es por costumbre. O si en realidad es por eficiencia o seguridad.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Roberto S. Sampayo** (1)

		
		Muchas Gracias por la Docu Raul!, esta bueno ver de que ya tienen todo para que se haga por funtions en vez de clases
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Luis Daniel Becerra Avellaneda** (2)

	
	A partir del minuto 9:21 se empieza a repetir
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **WilliamVelazquez** (1)

		
		Sí, aunque creo que cambia ligeramente
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Gracias, vamos a revisar.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **WilliamVelazquez** (1)

		
		De nada! 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Carlos Rivas** (1)

		
		Aun sigue ese error.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Enrique Devars (Platzi)** (1)

		
		Sigue el error en el video
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **mariandrea (Platzi)** (1)

		
		hola, una disculpa por el tiempo que nos tomó corregir este error. Ya se solucionó. Muchas gracias por reportarlo 😃
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Roberto S. Sampayo** (1)

	
	A los nuevos, consulto, les esta andando bien la Api, creo que se cayo
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Fadith Enrique Escorcia Mujica** (1)

		
		Todo [perfecto.Si](http://perfecto.Si) tienes problemas deja tu duda
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Alejandro Robleto** (1)

	```
	    alguin sabe como podria resovle este problema, quiero arrastrar la captura al comentario pero no me deja.
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Matias Alejandro Lopez Heredia** (1)

		
		No se puede arrastar una imagen simplemente, tenes que usar el boton que dice “Imagen”, y subir la imagen a algun servidor gratis, y ponerla url en donde te lo indica el comentario.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Alejandro Robleto** (1)
alguin sabe como podria resovle este problema, quiero arrastrar la captura al comentario pero no me deja.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Jose Padron (Platzi)** (1)

		
		Toca que le des al botón de “Imagen” y arrastras la imagen para que se cambia por donde dice “url”
		
		y listo, prueba:
		
		![crying.jpg](https://static.platzi.com/media/user_upload/crying-cd06ec62-67ee-4260-ab4f-f8e65fe2f043.jpg)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0140. ¿Cómo diseñar URLs

### Descripción:


En esta clase vamos a ver algo mucho más relacionado a experiencia de usuario de lo que venimos viendo, y tiene que ver con repensar cómo están armadas las URLs de nuestra aplicación, que es lo que mucha gente no le presta atención, pero que es muy importante, tanto para nuestros usuarios como para motores de búsqueda, incluso para posicionamiento en buscadores como Google.

En este sentido, hay un par de principios que debemos considerar: Legibilidad y Consistencia.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Sergio Minei** (9)

	
	## Diseñando Urls
	
	Principios para crear Urls user friendly:
	
	**1\. Legibilidad** : Deben ser entendibles por nuestros usuarios.
	
	> //Esto no es legible  
	>  /channel?id=156486
	> 
	> //Esto si  
	>  /Posta
	
	**2\. Consistencia** : Deberíamos poder borrar cualquier fragmento.
	
	> /podcast/un-buen-dia  
	>  /channel/posta  
	>  /channel  
	>  /
	
	En el caso anterior, no se cumple con la consistencia en las urls. Por ejemplo, `/podcast` no tendría sentido puesto que siempre se necesita de un posdcast para reproducirlo. Por otro lado, `/channel` tampoco tendría sentido ya que `/` muestra lo mismo.
	
	Una mejor propuesta sería:  
	`/nombre-serie/nombre-podcast`
	
	> /posta/un-buen-dia  
	>  /posta  
	>  /
	
	Con esta estructura, si se usa solo el primer fragmento de urls, `/posta`, se mostraría todos los podcast de la serie posta. Del mismo modo, si se ingresa a `/posta/un-buen-dia`, se estaría mostrando el podcast _un buen día_ de la seria _posta_.
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jsechirinos** (2)

	
	`Urls User Friendly`
	
	  * **Legibles:** Deben ser fácilmente entendibles para los usuarios.
	
	  * **Consistencia:** Deberíamos poder borrar cualquier formato y tener una respuesta  
	Ejemplo:
	
	
	
	
	— Incorrecto  
	`/podcast/un-buen-dia` = ( reproduce el podcast buen día )  
	`/podcast = (no tendría` sentido el reproductor sin un podcast )
	
	— Correcto  
	`/posta/un-buen-dia` = (reproduce el podcast buen día)  
	`/posta` = (listado de podcasts de Posta)  
	`/` = ( el home con canales)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

## 0150. Configurando Next Routes

### Descripción:

  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Sergio Minei** (8)

	
	## Next Routes
	
	Next Routes permite asignar un nombre a una url con Next.
	
	Con Next Routes, el router de Next por defecto no sirve.
	``` 
	    $ npm install next-routes --save
	    
	```
	
	Para usar Next Routes, se debe de configurar server.js.
	``` 
	    const next = require('next')
	    const routes = require('./routes')
	    const app = next({ dev: process.env.NODE_ENV !== 'production' })
	    const handler = routes.getRequestHandler(app)
	    const port = process.env.PORT || 3000;
	    
	    const { createServer } = require('http')
	    app.prepare().then(() => {
	      createServer(handler).listen(port)
	    })
	    
	```
	
	Para definir las rutas, se hace con un archivo routes.js.
	``` 
	    const routes = require('next-routes')
	    
	    // .add(nombre, url, archivo.js)      
	    module.exports = routes()        
	      .add('index')
	      .add('channel', '/:slug.:id', 'channel')
	      .add('podcast', '/:slugChannel.:id/:slung.:id', 'podcast')                  
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **wilson_romero** (2)

		
		Gracias por el resumen
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **ClaudioHerreraC** (2)

		
		GENIAL GRACIAS!!!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Luis Daniel Becerra Avellaneda** (5)

	
	[Next-Routes](https://github.com/fridays/next-routes)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Alejandro Trejo Cuxim** (4)

	
	Ya es más sencillo implementar rutas dinámicas de manera oficial por parte de Next.js, esto a partir de la versión 9
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jhurgen Maraza** (3)

	
	Alguien me puede dar una mano?  
	Corro el comando npm run dev y se queda colgado en ‘node server.js’ y no pasa de eso  
	hice todo lo de la clase, me fije archivo por archivo y lo tengo igual, es mas hasta me descargue los js de la parte de recursos e igual no me funcionan, me fije en el package.json y lo tengo igual. Alguien tendria una idea cual seria el error? si tengo que instalar algo de node?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (1)

		
		Hola, comúnmente estos errores se deben a Node.js, puedes desinstalar Node.js e instalarlo otra vez, puedes instalar la versión LTS que es la más estable…
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Jhurgen Maraza** (2)

		
		Volví a instalar Node y sigue igual. Se queda en
		
		> Node Server.js
		
		Ayuda! volvi a hacer todos los pasos, a instalar cada una de las dependecias
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Esteban Ciudad** (1)

		
		me pasa lo mismo, regrese unas semanas depues a correr el proyecto del curso y me quedo pegado en “node server.js”. He probado reinstalando varias versiones de node desde la estable LTS hasta las mas nuevas. Cuando intento entrar al localhost se tarda mucho y a veces carga despues de un rato pero otras veces simplemente no, es muy raro, esto sucede solamente con el server personalizado porque si ejecuto “next” me corre sin problemas
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Esteban Ciudad** (1)

		
		<https://github.com/zeit/next.js/issues/7259>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Diego Ivan Padilla Bernal** (1)

		
		Pues que esperas que salga?  
		Se supone que el último mensaje que debe salir es eso, yo como quiera puse un mensaje para no perder la costumbre
		``` 
		    ...
		    
		    const { createServer } = require("http");
		    app.prepare().then(() => {
		      createServer(handler).listen(port, () => {
		        console.log(`Server listening on port ${port}`);
		      });
		    });
		    
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **iLuisCastillo** (1)

		
		Lo he leido en un issue de github:
		
		"Confirm, also using custom server via const { createServer } = require(‘http’)  
		stuck at
		
		[ wait ] compiling …  
		but navigating to the server in works"
		
		cuando se queda estancado, igual entro a las rutas y funciona, y ya no se estanca mas.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **nachoogoomez** (2)

	
	A dia de hoy Next permite hacer el enrutado de manera mucho mas sencilla y nativa
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Fernando Azuaje** (2)

	
	Con la propiedad ‘as’ de Link tambien se pueden hacer mas sencillas de leer las rutas. un ejemplo con los canales:
	``` 
	    <Link href={`/channel?id=${ channel.id }`} as={`/${channel.title}.${channel.id}`}>
	              <aclassName='channel'>
	                <imgsrc={channel.urls.logo_image.original } alt="" />
	                <h2>{ channel.title }</h2>
	              </a>
	            </Link>```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Kemt** (2)

	
	Hola! tengo una duda, como estoy acostumbrado a trabajar de esta manera, al principio de curso configure para tener mis carpetas de “pages” y “component” dentro de otra llamada “src”, ahora parece que next-router no trabaja con esto, que podría hacer?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jose ortiz** (2)

	
	next routes remplaza a react router?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **eduardoluisgr** (1)

		
		No exactamente, las funciones internas de next, con su capeta /pages remplaza a react-router
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Eduardo Rasgado Ruiz** (2)

	
	Si no comprendes como funciona la sintaxis para las rutas con :slug.id, etc. No desesperes, sigue la clase hasta el final y comprenderás 😃
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (2)
Al utilizar next-router tendríamos el mismo poder que facilita express?, algo como Generar middleware Url ...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **cesar88** (1)

	
	Me pase a aprender next desde su web ya que este curso quedo muy desactualizado y varias cosas cambiaron… como el manejo de las rutas x ej… ojala saquen un curso actualizado de NEXT!!  
	<https://nextjs.org/learn/basics/create-dynamic-pages/use-router>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Jorge Mendez Ortega** (1)

		
		pero clara mente dicen que el router de next queda corto ya que incialmente next esta pensado para sitios estáticos, lo que en mi caso me a funcionado para manejar rutas de manera dinámica es `express` o el paquete de `http` de node lo e probado en un desarrollo y me esta dando buenos resultados ya que las peticiones a `API's` me funciona muy bien generarlas de manera asincrona desde el router ya que tengo entendido que como buena practica no es muy recomendable hacerlo en `getInitialProps`
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Daniel Elver Valderrama Mejia** (1)

	
	Buenas Team !  
	TENGO UN ERROR  
	This is probably not a problem with npm. There is likely additional logging output above.  
	Me hace referencia en serve.js
	
	Si me pueden ayudar Gracias
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Kevin Kleber Rivamontan Alvarado** (1)

	```
	    "scripts": {
	        "dev": "node server.js",
	        "build": "next build",
	        "start": "NODE_ENV=production node server.js"
	      }```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Kevin Kleber Rivamontan Alvarado** (1)

	```
	    const routes = require('next-routes')
	    
	                                    
	    module.exports = routes()                           
	    .add('about')                                      
	    .add('blog', '/blog/:slug')                         
	    .add('user', '/user/:id', 'profile')                
	    .add('/:noname/:lang(en|es)/:wow+', 'complex')      
	    .add({name: 'beta', pattern: '/v3', page: 'v3'})    ```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Kevin Kleber Rivamontan Alvarado** (1)

	```
	    // server.js
	    const next = require('next')
	    const routes = require('./routes')
	    const app = next({dev: process.env.NODE_ENV !== 'production'})
	    const handler = routes.getRequestHandler(app)
	    
	    // With express
	    const express = require('express')
	    app.prepare().then(() => {
	      express().use(handler).listen(3000)
	    })
	    
	    // Without express
	    const {createServer} = require('http')
	    app.prepare().then(() => {
	      createServer(handler).listen(3000)
	    })```
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jhurgen Maraza** (1)
Alguien me puede dar una mano? Corro el comando npm run dev y se queda colgado en ‘node server.js’ y no pasa de eso hice todo lo de la cl...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (1)

		
		Hola, comúnmente estos errores se deben a Node.js, puedes desinstalar Node.js e instalarlo otra vez, puedes instalar la versión LTS que es la más estable…
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Kemt** (1)
Hola! tengo una duda, como estoy acostumbrado a trabajar de esta manera, al principio de curso configure para tener mis carpetas de “page...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Geordano Polanco Rodríguez** (0)

	
	Pero esto sólo es necesario si quieres utilizar Server side rendering?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Daniel Elver Valderrama Mejia** (0)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-5b12fa94-a725-4e4f-b991-94d831dca60f.jpg)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

## 0160. Implementando Next Routes

### Descripción:


Siguiendo con la clase pasada, vamos a empezar a implementar Next Routes dentro del resto de nuestra aplicación. Así todos los links internos siguen esta nueva estructura de URLs que estuvimos diseñando.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Joaquin Araujo** (9)

	
	Aqui tienes el regex `replace(/[^\w\-]+/g, '')` 😉
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **CodingLeonardo** (1)

		
		Gracias me ahorraste tiempo
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **jhurtadojerves** (6)

	
	Para la lista de podcast en channel, esto sirve:
	``` 
	    params={{
	                    slugChannel: slug(clip.channel.title), 
	                    idChannel: clip.channel.id,
	                    slug: slug(clip.title), 
	                    id: clip.id,
	                  }}
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Efrén Sánchez** (1)

		
		Y el `routes.js` :
		``` 
		    .add('index')
		      .add('channel', '/:slug.:id', 'channel')
		      .add('podcast', '/:slugChannel.:idChannel/:slug.:id', 'podcast')
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Luis Arturo Lira Cerda** (3)

	
	Así lo pueden agregan PodcastList
	``` 
	    <Link route="podcast"
	        params={{
	                slugChannel: slug(podcast.channel.title),
	                idChannel: podcast.channel.id,
	                slug: slug(podcast.title),
	                id: podcast.id
	        }}
	        prefetch key={podcast.id}>
	        <aclassName="podcast">
	            <h3>{podcast.title}</h3>
	        </a>
	    </Link>               	
	    
	```
	
	Y no olviden que en el botón de “volver” de la página podcast también debemos agregarlo 😃
	``` 
	    <Link route="channel"
	        params={{
	            slug: slug(clip.channel.title),
	            id: clip.channel.id
	        }}
	    >
	        <aclassName='close'>&lt; Volver</a>
	    </Link>
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Minei** (2)

	
	## Enlazando páginas con Next Routes
	
	**Next Routes** usa otro tipo de componente `<Link>` para enlazar página.
	``` 
	    import {Link} from'../routes';
	    
	    <Linkroute='channel'params={{ 
	      slug:slug(channel.title), 
	      id:channel.id }}>
	      <a>Enlace</a>
	    </Link>
	    
	```
	
	  * **route** : es el nombre del enlace definido en routes.js
	  * **params** : son los parámetros definidos en routes.js. Nótese las doble `{{}}`.
	
	
	
	## Encode de textos para urls
	
	Para transformar un texto en un formato que sea compatible con las urls, por ejemplo, para transformar un título, se va a usar una librería llamada **slugify**.
	``` 
	    $ npm install slugify
	    
	```
	
	Luego, para usarlo, se puede realizar de la siguiente manera:
	``` 
	    import slugify from'slugify';
	    
	    exportdefaultfunctionslug(name) {
	      return slugify(name, { lower: true }).replace(/[^\w\-]+/g, '')
	    }
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Edgar de Jesus Mendoza Ortegon** (2)

		
		Gracias por el aporte
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **oteka21** (2)

		
		Wooow me quito el sombrero con tu resumen del curso!! Saludos Crack 🙌🏽
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (1)

	
	Por qué no utilizar código nativo en ves de una librería, ya que el código puede quedar de la siguiente manera.
	``` 
	    const slug = (name = "") => name.toLocaleLowerCase().replace(/\s/g, "-");
	    
	```
	
	Siempre e considerado que si se puede resolver de manera muy sencilla alguna tarea por que utilizar una libreria.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Geordano Polanco Rodríguez** (1)

		
		Me parece que lo ha realizado con una librería externa, para resolver un posible problema con la internacionalización.
		
		Tu código puede que te funcione, pero si pretende internacionalizar la aplicación, puede que te encuentres con problemas.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Alejandro Robleto** (1)

	
	completamente practico y magnifico
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Andres Rodriguez Escudero** (1)

	
	Consulta, Si Next Routes no es de mi agrado, que otra alternativa podría tomar? o simplemente podría quedarme con las rutas que me entrega por default Next con Link?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **aragonesteban (Platzi)** (2)

		
		Hola, no creo que sea posible, con ese router trabaja el framework para poder hacer el **Server Side Rendering** , es como el `@angular/router` de Angular, con esto trabaja el framework para que todo esté unificado y legible.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **yaftemx** (1)

	
	Esto esta muy bueno.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Eduardo Hidalgo Díaz Rugama** (1)

	
	Precioso video. Increible. Que buen curso 😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **soymichelt** (1)

	
	Tengo una duda. ¿Cómo podría hacer que los buscadores indexen mis URL’s dinámicas generadas desde la API en Next Routes?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **manuel-corrales** (2)

		
		Al igual que indexan URL dinámicas de PHP u otros servicios, si tienes enlaces desde el index que apunten a ellos y autoridad se indexaran. Recuerda que deben tener contenido único y de calidad para acelerar este proceso.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **soymichelt** (1)

		
		@manuel-corrales **gracias por responder amigo.**
		
		¿Qué pasa cuando tienes miles de URL dinámicas generadas y no todas pueden estar en el Index?
		
		**Por ejemplo:** _“El Blog de Platzi no contiene todas sus URL’s dinámicas en el Index, pero aún así las publicaciones aparecen en los buscadores”_
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **soymichelt** (1)
Tengo una duda. ¿Cómo podría hacer que los buscadores indexen mis URL’s dinámicas generadas desde la API en Next Routes?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **manuel-corrales** (2)

		
		Al igual que indexan URL dinámicas de PHP u otros servicios, si tienes enlaces desde el index que apunten a ellos y autoridad se indexaran. Recuerda que deben tener contenido único y de calidad para acelerar este proceso.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0170. Vistas Híbridas

### Descripción:


En esta clase vamos a ver algo muy particular, y tiene que ver con cómo implementar vistas híbridas. Conoceremos una de las funcionalidaes de React que es: setState(), que nos permite cambiar el estado de los componentes.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Cristian Camilo Cucunubá** (7)

	
	 **Codigo Con React Hooks :**
	``` 
	    const [openPodcast, setPodcast] = useState(null);
	        const setOpenPodcast = (event, podcast) => {
	            event.preventDefault()
	            setPodcast(podcast)
	        }
	    
	```
	
	Y no cree el otro componente para tener el elemento onClick, simplemte agregue el evento en la etiqueta hija <a> del Link.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Miguel Rodriguez** (1)

		
		Aqui pueden leer un poco sobre el evento click en nextjs no puede ir directo en en el componente <Link> pero si puede ir en su children.
		
		[onClick event doesn’t exist in next/link ?](https://github.com/zeit/next.js/issues/7304)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Sergio Minei** (6)

	
	## State
	
	Estate se usa para definir el estado interno de un componente. A diferencia de los props, estate puede ser modificado.
	
	Para usar state, primero debe de inicializarse en un constructor:
	``` 
	    constructor(props) {
	      super(props);
	      this.state = { openPodcast: null }
	    }
	    
	```
	
	`this.setState()` cambia el estado interno de un componente.
	``` 
	    this.setState({
	      openPodcast: podcast
	    })
	    
	```
	
	Para obtener un estado, se puede hacer de la siguiente manera:
	``` 
	    const { openPodcast } = this.state;
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (4)

	
	Hola Roberto! 😃  
	¿hay alguna diferencia si para inicializar el estado en lugar de usar el constructor explícitamente lo realizo de la siguiente forma?:
	``` 
	    export defaultclassextendsReact.Component{
	    
	      state = {
	        openPodcast: null
	      }
	    
	    ...
	    
	```
	
	De antemano muchas gracias y un saludo! 🤚
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Lo mejor es usar el constructor, por estándar y por facilidad de lectura del código.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **WilliamVelazquez** (1)

		
		Muchas gracias! ¿El usarlo así tiene algún problema en rendimiento o en algún otro aspecto?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Creo que es más en pensar en tu yo del futuro para cuando tengas que mantener la aplicación, porque luego no te acuerdas el porque lo hiciste así.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **WilliamVelazquez** (1)

		
		Gracias Gollum! 😉
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Simón Rotjes** (1)

		
		 **YO NO USO constructor()**
		
		Asi como frameworks como Next.js facilitan y/o mejoran tu calidad de desarrollo, declarar (si aplica) el estado de un componente usando…
		
		**state = {}**
		
		Hara que tu codigo sea mas limpio, corto y facil de mantener, ademas es posible que con el tiempo nuevos _releases_ vuelvan ciertas cosas obsoletas.
		
		**SI ENCUENTRAS MEJORES MANERAS DE HACERLO, _THEN DO IT!_**
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Javier Ignacio** (3)

	
	a día de hoy, ¿los chicos de next.js fixearon el tema del link?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **JoosCode** (1)

		
		misma pregunta me hago … supongo que tendra una solucion porque que feo incrustar un componente solo para hacer onClick …
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Esteban Ciudad** (4)

		
		a mi me funciona de la siguiente manera, añado el onclick al elemento a y dejo el componente Link igual con sus params:
		``` 
		    {audioClips.map(clip => (
		              <Link
		                route="podcast"
		                params={{
		                  slugChannel: slug(clip.channel.title),
		                  idChannel: clip.channel.id,
		                  slug: slug(clip.title),
		                  id: clip.id
		                }}
		              >
		                <a
		                  className="podcast"
		                  onClick={event => onClickPodcast(event, clip)}
		                >
		                  <h3>{clip.title}</h3>
		                  <div className="meta">
		                    {Math.ceil(clip.duration / 60)} minutes
		                  </div>
		                </a>
		              </Link>
		            ))}
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **AlexRodriguez1218** (1)

		
		Segun la documentacion de Next,js a hoy no se ha solucionado, el onClick se debe agregar a un elemento a para que funcione
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Ramiro Nicolas D'Accorso Rosati** (2)

	
	Ya se actualizo el componente link? Porque next va por la versión 9+ y en el curso esta la 6.1
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Le_MaliX** (1)

		
		Actualmente puedes poner el componente onclick en uno de los childrens del Link, te dejo el link al [Pull request](https://github.com/zeit/next.js/pull/4474) donde se solucionó
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Miguel Angel Morales Larriega** (2)

	
	No es necesario escribir el constructor para un state:
	
	state= {  
	openPodcast: null  
	}
	
	openPodcast = (e, podcast) => {  
	e.preventDefault();  
	this.setState({  
	openPodcast: podcast  
	})  
	}
	
	//Otra forma de mostrar codigo a partir de una validación es la siguiente:  
	{(openPodcast)?<div>Hay un podcast abierto</div>: null}
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Ivan Padilla Bernal** (1)

		
		Lo del inicializar el state estas en lo correcto, más que nada para simplificar código, pero lo de la otra forma de validar funciona pero sería escribir un poco de código extra así que en ese casi se es mejor como lo hizo el profesor
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Javier Ignacio** (2)
a día de hoy, ¿los chicos de next.js fixearon el tema del link?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **JoosCode** (1)

		
		misma pregunta me hago … supongo que tendra una solucion porque que feo incrustar un componente solo para hacer onClick …
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **carlosaepn** (1)

	
	Las clases sirven como guía, sin embargo Next ya fue actualizado en muchos ámbitos, por lo cual es recomendable revisar constantemente la documentación. 🙃  
	[Link con onClick](https://nextjs.org/docs/api-reference/next/link)  
	[Router con hooks](https://nextjs.org/docs/api-reference/next/router)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Ivan Magdaleno** (1)

	
	Por qué menciona el Link de Next? No se supone que desde la clase pasada estamos usando el Link de next-routes en lugar del Link de Next?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Andres Rodriguez Escudero** (1)

	
	Me queda la duda, si no es necesario hacer `bind`del metodo `openPodcast`como se suele hacer en React. algo como:
	``` 
	    this.openPodcast = this.openPodcast.bind(this);
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Ivan Padilla Bernal** (1)

		
		cuando se usa una **arrow function** no es necesario hacer eso.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **santiagomarcano** (1)

	
	He aprendido mucho con este curso aunque este video sin duda ha sido el mas confuso. Es raro picar código y no saber para que si no hasta el final del video. Creo que seria mejor explicar a detalle la funcionalidad que se quiere implementar antes de picar todo el código y mas aun si se está haciendo un “hack” para que funcione en Next.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Andres Rodriguez Escudero** (1)

		
		Lo hizo, al principio del video, la idea es que puedas cargar en un modal el podcast que es seleccionado con un “click” para que no tenga que abrir otra página, sino que lo abra en la misma, pero en un modal. Esto resulta mas eficiente porque no tienes que hacerle un tiro a la API para traer el podcast, que puede ser mas costoso en tiempo y recursos cuando en el listado ya te trae todo el detalle del podcast, solo es usarlo. Saludos
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **walter** (1)

	
	hola me sale lo siguiente  
	Error in ./pages/channel.js  
	Module not found: Error: Can’t resolve ‘…/components/PodcastListWidthClink’ in 'D:\podcasts\pages’  
	ModuleNotFoundError: Module not found: Error: Can’t resolve ‘…/components/PodcastListWidthClink’ in 'D:\podcasts\pages’  
	at factoryCallback (D:\podcasts\node_modules\webpack\lib\Compilation.js:276:40)  
	at factory (D:\podcasts\node_modules\webpack\lib\NormalModuleFactory.js:235:20)  
	at resolver (D:\podcasts\node_modules\webpack\lib\NormalModuleFactory.js:60:20)  
	at asyncLib.parallel (D:\podcasts\node_modules\webpack\lib\NormalModuleFactory.js:127:20)  
	at D:\podcasts\node_modules\async\dist\async.js:3888:9  
	at D:\podcasts\node_modules\async\dist\async.js:473:16  
	at iteratorCallback (D:\podcasts\node_modules\async\dist\async.js:1062:13)  
	at D:\podcasts\node_modules\async\dist\async.js:969:16  
	at D:\podcasts\node_modules\async\dist\async.js:3885:13  
	at resolvers.normal.resolve (D:\podcasts\node_modules\webpack\lib\NormalModuleFactory.js:119:22)  
	at onError (D:\podcasts\node_modules\enhanced-resolve\lib\Resolver.js:65:10)  
	at loggingCallbackWrapper (D:\podcasts\node_modules\enhanced-resolve\lib\createInnerCallback.js:31:19)  
	at runAfter (D:\podcasts\node_modules\enhanced-resolve\lib\Resolver.js:158:4)  
	at innerCallback (D:\podcasts\node_modules\enhanced-resolve\lib\Resolver.js:146:3)  
	at loggingCallbackWrapper (D:\podcasts\node_modules\enhanced-resolve\lib\createInnerCallback.js:31:19)  
	at next (D:\podcasts\node_modules\tapable\lib\Tapable.js:252:11)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Revisa que no tengas un error de digitación, por lo que veo esta buscando el archivo PodcastListWidthClink creo que sobra la n en el Clink y por eso no encuentra el archivo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **walter** (1)

		
		ok me voy a fijar quisas no me dicuenta.  
		gracias
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **esdraspavon** (1)

		
		Si, tambien parece que se te escapo una **d** en **Width**
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **walter** (1)
hola me sale lo siguiente Error in ./pages/channel.js Module not found: Error: Can’t resolve ‘…/components/PodcastListWidthClink’ in 'D:\\...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Revisa que no tengas un error de digitación, por lo que veo esta buscando el archivo PodcastListWidthClink creo que sobra la n en el Clink y por eso no encuentra el archivo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Leo Islas** (0)
duda estoy apenas tomando el curso y me gusto bastante ya que me ayuda bastante en la parte de SEO de paginas dinamicas pero estaticas al...
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Gabriel De Andrade (Platzi)** (1)

		
		Hola! Si puedes usar Hooks, lo que pasa es que este curso se grabó antes de que esta feature saliera en React, pero en Platzi siempre se actualizan los cursos así que no te preocupes por que se quede viejo tampoco 😄
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0180. Implementar el Modal

### Descripción:

  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Jose Adan Ardila Sanchez** (2)

	
	No se si sea mi impresión pero luego de finalizar esta clase observo 2 cosas interasantes:
	
	  1. Realmente el href no se necesita debido a que el evento clic está recibiendo el podcast completo, luego  
	cualquier ruta que pongamos en el href igual funcionará devido incluso el prevetDefault.
	
	  2. la página podcas.js ya no se necesitaría debido a que realmente quien muestra el podcas cuando de  
	selecciona es el chanel.js
	
	
	
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **esdraspavon** (5)

		
		Desde mi punto de vista es necesario ambos, ya que:
		
		  1. Es necesario el href, si por ejemplo, quieres abrir el podcast en una nueva pestaña, solo click derecho y abrir en una nueva pestaña
		  2. Tener la vista de podcast, también sería necesario para el para el punto anterior, y ademas si quisieras compartir un link directo al podcast.  
		:smile
		
		
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Henry Villavicencio** (1)

		
		Yo coincido con el dilema cualquier href funcionaria. Lo ideal seria que se mostrara en la barra la url pero no cambia entonces compartir la url podcast no se vuelve tan sencillo. Si alguna persona encontró la solución a esto compártala estaré muy agradecido.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Jesus Garcia** (2)

	
	seria interezante realizar todo el trabajo con material-ui
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Oscar Barajas Tavares (Platzi)** (5)

		
		Puede ser un buen reto tratar de implementarlo uno mismo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sebastian Martin** (3)

		
		<https://github.com/mui-org/material-ui/tree/master/examples/nextjs>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0190. Agregando un loader

### Descripción:

  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Sergio Alejandro Trejo Cuxim** (7)

	
	Esta es la versión actualizada para Next.js V9
	``` 
	    Router.events.on('routeChangeStart', () => NProgress.start() );
	    Router.events.on('routeChangeComplete', () => NProgress.done() );
	    Router.events.on('routeChangeError', () => NProgress.done() ); 
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Sergio Minei** (7)

	
	## Loaders
	
	Se va a usar **nprogress** para mostrar un loader al cargar las páginas.
	``` 
	    $ npm add nprogress
	    
	```
	
	Para usarlo, se debe agregar las siguientes líneas de código al inicio del componente princioan o Layout:
	``` 
	    import NProgress from'nprogress';
	    import Router from'next/router';
	    
	    Router.onRouteChangeStart = (url) => {
	      NProgress.start()
	    }
	    Router.onRouteChangeComplete = () => NProgress.done()
	    Router.onRouteChangeError = () => NProgress.done()
	    
	```
	
	Además se debe de agregar la [hoja de estilos de nprogress](https://raw.githubusercontent.com/zeit/next.js/canary/examples/with-loading/static/nprogress.css) a los estilos globales del proyecto.
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (5)

	
	Hoja de estilos de nprogress 😃  
	[nprogress.css](https://raw.githubusercontent.com/zeit/next.js/canary/examples/with-loading/static/nprogress.css)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (5)

	
	Ejemplo with-loading the next.js  
	<https://github.com/zeit/next.js/tree/canary/examples/with-loading>  
	😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **raulfbgomez** (3)

	
	[Aquí encontraran el CSS del ejemplo](https://github.com/zeit/next.js/blob/canary/examples/with-loading/public/nprogress.css)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Pablo Tabares Hernandez** (2)

	
	Router.onRouteChangeStart = (url) => {  
	NProgress.start()  
	}  
	Router.onRouteChangeComplete = () => NProgress.done()  
	Router.onRouteChangeError = () => NProgress.done()
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (2)

	
	Enlace a NProgress.js  
	<http://ricostacruz.com/nprogress/>  
	😃
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **carlosaepn** (1)

	
	Por si quieren crear su propio Loading component…
	``` 
	    import { useRouter } from 'next/router';
	    
	    const Loading = () => {
	    	const router = useRouter();
	    	const [ loading, setLoading ] = React.useState('');
	    
	    	React.useEffect(() => {
	    		const handleStart = (url) => url !== router.pathname && setLoading(true);
	    		const handleComplete = (url) => url !== router.pathname && setLoading(false);
	    
	    		router.events.on('routeChangeStart', handleStart);
	    		router.events.on('routeChangeComplete', handleComplete);
	    		router.events.on('routeChangeError', handleComplete);
	    
	    		return () => {
	    			router.events.off('routeChangeStart', handleStart);
	    			router.events.off('routeChangeComplete', handleComplete);
	    			router.events.off('routeChangeError', handleComplete);
	    		};
	    	});
	    
	    	return loading && <div>Loading...</div>;
	    };
	    
	    export default Loading;
	    
	    
	```
	
	Despues solo importenlo en Layout 🙃
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **diegoguevaraco** (1)

	
	Hola, como se debe importar en Nextjs una CSS desde un archivo externo?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Puedes usar este plugin <https://github.com/zeit/next-plugins/tree/master/packages/next-css>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **diegoguevaraco** (1)

		
		Gracias!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **diegoguevaraco** (1)
Hola, como se debe importar en Nextjs una CSS desde un archivo externo?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Puedes usar este plugin <https://github.com/zeit/next-plugins/tree/master/packages/next-css>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

# Publicando nuestra app

## 0200. Mejores prácticas en Github

### Descripción:


En esta clase vamos a ver algo que no tiene tanto que ver con Next, pero tiene que ver más con nuestra vida como desarrolladores. Es algo que es muy relevante cuando queremos crear un portafolio o cuando queremos aplicar a algún trabajo, y tiene que ver con publicar los proyectos en Github, y más específicamente con la creación de un [README.md](http://README.md) básico.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Eduardo Rasgado Ruiz** (4)

	```
	    document.write("Hagan un curso corto de implementacion de README.md")
	    
	```
	
	😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Esteban  Saravia** (4)

		
		Dale una mirada a docsie [Docsie markdown editor](https://www.docsie.io/markdown_editor/)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Carlos Rivas** (3)

		
		De hecho, no estaría mal que hicieran una serie de cursos cortos (o un solo curso completo) de varios temas relevantes como el markdonw del readme y otras configuraciones del entorno de trabajo. Sé que en algunos cursos los explican, pero no a profundidad y cuando los mencionan lo hacen de manera relativa al proyecto y no desde una vista general que ayude a implementarlos en otras circunstancias.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Juan David Castro (Platzi)** (1)

		
		Este tutorial explica muy bien cómo funciona Markdown para diferentes plataformas, incluido Platzi: <https://platzi.com/tutoriales/1099-fundamentos-javascript-2017/1615-markdown-el-lenguaje-de-estilos-para-los-readmemd-de-tus-paquetes-npm-y-de-los-tutoriales-de-platzi/>. 😉
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Juan David Castro (Platzi)** (1)

		
		Este artículo también puede ser de mucha ayuda: <http://anabelisa.co/readme/>. 😉
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Baltazar Ortega** (3)

	
	Este es un truco para subir imagenes al readme usando los issues de Github: [link](https://www.youtube.com/watch?v=hHbWF1Bvgf4)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **valentina-rua-carrillo** (2)

	
	Este site nos ayuda a agilizar el proceso del [Readme.md](http://Readme.md)  
	<https://pandao.github.io/editor.md/en.html>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **gosunkugi** (1)

	
	alguien ha puesto a andar el router en GitHub pages?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Gabriel De Andrade (Platzi)** (1)

		
		Hola! Que problema tienes exactamente?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Jorge Mendez Ortega** (1)

		
		no croe que lo puedas hacer correr ya que `githubPages` ya que no tiene la capacidad de correr `next` si quieres hacer la integracion completa te recomiendo usar heroku
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (1)

	
	Practicamente el Readme es markdown no veo cual es la complejidad sobre el tema VisualCode y Atom cuentan con plugins que nos permite previsualizar lo que estamos escribiendo. ademas de que le mismo git hub te da una vista previa de lo que estamos haciendo.
	
	le comparto una guia de markdown  
	<https://www.markdownguide.org/basic-syntax/>
	
	Y otras recomendaciones para buenas practicas en github
	
	  * [Recomendaciones para generar un buen commit](https://medium.com/@jmz12/buenas-pr%C3%A1cticas-para-commits-5eb4c86b9a47)
	  * [Recomendaciones para el manejo de ramas](https://medium.com/@jmz12/recomendaciones-para-el-manejo-de-ramas-5dd4b5a23c91l)
	
	
	
	Todos tendríamos que aprenden markdown ya que es muy potente
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

## 0210. Publicar la app con now

### Descripción:

  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **robertomgonzalez** (16)

	
	Un dato importante de las primeras clases: Para que funcione bien nuestra app en **now** tenemos que tener **dos scripts registrados en package.json** : **build** y **start**.  
	Build se encarga de procesar nuestros archivos para que queden listos para producción, y Start se encarga de correr el server en modo producción de la forma más rápida posible.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **mariomenjr** (3)

		
		Uno de los mejores cursos en Platzi. Junto con los fundamentos de bases de datos y los dos cursos de Leonidas sobre React y Redux.
		
		¡Gracias por esa forma de instruir, @robertomgonzalez!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Sergio Minei** (6)

	
	## Despliegue con Now
	
	Para desplegar la aplicación en [Now.sh](https://zeit.co/now) se va a instalar now de manera global.
	``` 
	    $ npm install -g now
	    
	```
	
	Se puede hacer un deploy en el plan gratuito. El plan gratuito hace que el código fuente de tu aplicación sea libre.
	``` 
	    $ now --public
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Next.js)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **José Gabriel Guzmán Lopéz** (5)

	
	 **Este es el mio**  
	<https://podcasts-kpehsmweph.now.sh>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Leo Islas** (1)

		
		duda , hiciste alguna modificación en la parte de rutas ya que cuando yo recargo  
		me marca que no encuentra la aplicación pero solo me pasa en producción no en modo dev
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (5)

	
	Aquí se encuentra mi repositorio al final del curso! 😄  
	[Repositorio](https://github.com/WilliamVelazquez/podcasts)  
	[App Pública](https://podcasts-tzfafutwzr.now.sh/)
	
	Gracias por todo Roberto! 😃
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Ricardo Medina** (4)

	
	Aqui este mi proyecto ya publicado ; )
	
	[App podcasts](https://app-podcasts-huthdkasle.now.sh)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jhonatan Miranda** (4)

	
	[Código completo en github](https://github.com/johnserrano15/podcasts)
	
	[App demo](https://podcasts-bkwaiavyko.now.sh/)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Betty Rossana Jimenez Cedeño** (2)

	
	Para los que no saben, now es de Zeit,  
	Los pasos son:
	
	  * Instalar now, como lo hace el profe.
	
	  * Se tienen que registrar en zeit.
	
	  * Luego desde la consola pueden acceder con:
	
	
	
	``` 
	    now login correo@corre.com
	    
	```
	
	  * Verifican su correo
	
	  * Corren el:
	
	
	
	``` 
	    now --public
	    
	```
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Carlos Enrique Gonzalez Peña** (2)

	
	Una pregunta, Now tiene la posibilidad de publicar un server, entiendo esa parte pero con el puro comando de now es suficiente para que se aproveche el SSR?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (2)

		
		¡Hola! Si, literalmente Now creó NextJS con solo el comando `now` el se encargará de saber que es una aplicación en Next y hacer el deploy
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **alexjcm** (2)

	
	Para los amigos que tienen problemas con publicar la _app_ , tienen que crear y configurar los archivos: **now.json** y **next.config.js** en el root del proyecto.
	
	**next.config.js**
	``` 
	    module.exports = {
	      target: "serverless" 
	    };
	    
	```
	
	**now.json**
	``` 
	    {
	      "version": 2,
	      "name": "nombre-de-la-app",
	      "builds": [{ "src": "package.json", "use": "@now/next" }]
	    }
	    
	    
	```
	
	Para más información: [Ver documentación](https://zeit.co/guides/deploying-nextjs-with-now/)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Danvasem** (1)

		
		Seguí los pasos de la documentación pero no puedo publicar con now, escribo “now --public” en la línea de comandos y no sucede nada, no presenta ni error ni nada. ¿Alguién que haya tenido y solventado este problema?
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Danvasem** (1)

		
		Bueno, logré realizar la publicación. Basicamente tuve que copiar y pegar los archivos “now.cmd” y “now” que se encontraban en la ruta de los paquetes globales de npm y los pegué en la carpeta del proyecto, posterior le di doble clic a now.cmd y se realizó la publicación.
		
		No creo que lo anterior sea correcto, pero me funcionó así.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **gusgonzalez060** (2)

	
	Para los que hacen deploy en Now y en lugar de la App de podcast funcionando, les muestra las carpetas, la solución está en el siguiente enlace de la documentación oficial de Next:
	
	<https://zeit.co/guides/deploying-nextjs-with-now/>
	
	Espero les sirva!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Arturo Lira Cerda** (1)

		
		Gracias! 😄 Esta fue la solución que me sirvió
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Eduardo Rasgado Ruiz** (2)

	
	Excelente curso. Gracias @robertomgonzalez eres un pro en lo que haces. Un gran abrazo desde México.  
	Ahora mis resultados:  
	[Mi app](https://podcasts-nsgvextlwc.now.sh)  
	[El repo](https://github.com/eduardorasgado/podcastiny)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Daniel Castillo Nava** (2)

	
	Como puedo crear un dist folder para colocarlo en git pages??
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Erik Ochoa (Platzi)** (3)

		
		No todas las aplicaciones web pueden ser hosteadas en github pages. Por ejemplo aplicaciones como la de este curso no estoy seguro pueda generar los archivos totalmente estáticos para subirlos a github pages ya que usa Server Side Rendering y para eso necesitamos node en el servidor.
		
		Ciertamente Next permite hacer la exportación de los archivos estáticos pero aclara que no es aplicable en todos los proyectos. [Export Into a Static HTML App](https://nextjs.org/learn/excel/static-html-export)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Sergio Minei** (2)

		
		No vas a poder subir una aplicación hecha con Next a Github Pages puesto que no es una página estática.
		
		Lo ideal es que lo hagas con Now como se enseña al final del curso y agregues el enlace a tu repositorio de Github.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **David Daniel Castillo Nava** (1)

		
		Bueno seguiré investigando para hacerlo con el next export aunque creo que me da problemas con el next routes. Tratare de seguir investigando. Gracias por las respuestas.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Jorge Mendez Ortega** (1)

	
	Si recuerdo bien `now` paso a ser `Zeit`  
	<https://zeit.co/>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Roy Hodson** (1)

	
	<https://podcast.royhg1496.now.sh>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Francisco Bustos** (1)

	
	Hola tengo un problema al hacer ddeploy de mi aplicacion con next-routes resulta que las rutas no las reconoce en produccion si recargas una url sale error 404 osea como si no la encontrara como puedo solucionar esto. Localmente si funcionan bien pero en produccion en now no.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Leo Islas** (0)

		
		checa tu codigo puede ser que en la parte de routes.js la conexión con el slug sean puntos y no guiones ya que hay como un un error al tomar el separador cuando pasa por la expresión regular y tomara como el slug el primer - guion dejandote como id todo lo demas  
		del nombre espero me puedas entender pero estoy casi seguro que puede ser eso ya que me paso a mi XD saludos
		``` 
		    primera vez 
		    slug: nombre-del-podcast
		    id: 8129319283
		    
		    segunda vez que recargas 
		    slug: nombre
		    id: del-podcast-8129319283   
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Manuel Ojeda** (1)

	
	<https://podcasts.manuelojeda.now.sh>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Alejandro Robleto** (1)

	
	no me funciono pero bueno se que con mas practica lo podre lograr
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **SOFTDYNAMIC** (1)

	
	<https://nextjscmbpodcasts.fyupanquia.now.sh>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Vargas Domínguez** (1)

	
	Increíble curso! Repositorio y demo completados. 😃
	
	Repositorio: <https://github.com/thedavos/podcast-app>  
	App Demo: <https://podcast-app.davos.now.sh/>
	
	Ahora queda contenerizarlo con Docker, nunca paren de aprender!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **mexdelgado** (1)

	
	Excelente curso!!!
	
	[Repo](https://github.com/rudemex/curso-platzi-nextjs)  
	[Demo](https://curso-platzi-nextjs.mexdelgado.now.sh/)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **camiladi** (1)

	
	No puedes ser, un bonus de Docker, este curso no pudo estar mejor 😄 diez mil puntos.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Juan David Castro (Platzi)** (1)

	
	  * [A simple React(Next.js) app development on Docker](https://medium.com/@khwsc1/a-simple-react-next-js-app-development-on-docker-6f0bd3f78c2c)
	
	
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Efrén Sánchez** (1)
![Capture.png](https://static.platzi.com/media/user_upload/Capture-39fdaad7-ede5-4f78-8442-b925e976feab.jpg)
	
	Tengo que ser super torpe, porque yo no consigo hacer deploy del repositorio  
	LLevo todo el dia investigando y nada. Ni con now.json, ni desde github…
	
	Agradecería alguna sugerencia
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Efrén Sánchez** (1)

		
		Siempre que hago `now --public` voy a la dirección que me pasa Now y aparece lo de la imagen
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **RAMIRO JHONATAN TORREJON CASTRO** (1)

		
		Hola @EfrenSango, crea un file _now.json_ en la raiz de tu proyecto  
		con esta información
		``` 
		    {
		    	"version": 2,
		    	"builds": [
		    		{ "src": "package.json", "use": "@now/next" }
		    	]
		    }
		    
		```
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **ma_angelica_romero** (1)
Cómo se publica en servidores de digitalocean
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Andres Rodriguez Escudero** (1)

		
		Creería que sí, pero tendrías que hacer toda la configuración de tu server a mano, o bueno casí a mano en caso que DigitalOcean no tenga algún helper que te facilite el trabajo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Cesar Herrera** (1)

	
	Una app como esta se puede publicar en un hosting como los que renta goodady ?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Andres Rodriguez Escudero** (1)

		
		No conozco los hosting que renta GooDady, pero si eso soporta Nodejs no le vería problema. Eso sí, tendrías que hacer muchas cosas a mano. Si lo logras comparte tu experiencia, seguro no eres el único con la misma duda.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		Te recomiendo que lo publiques en [Now.sh](http://Now.sh) ya que no debes pagar nada, es totalmente seguro y puedes utilizar tu dominio con ellos
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Ricardo Medina** (1)

	
	Aqui esta mi proyecto ya publicado con [Now.sh](http://Now.sh)
	
	[Url](https://app-podcasts-huthdkasle.now.sh)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **David Daniel Castillo Nava** (1)

	
	Que significan todas las carpetas que genera el comando build?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eduardo Rasgado Ruiz** (3)

		
		Es el bundle y sus amigos, son el resultado de transpilar, compactar y hacer legible nuestro código en todas las plataformas de navegación posibles. Usualmente puede hacerse a mano cuando trabajas solo con ReactJS o VanillaJS con ES6, etc. pero gracias al framework Next o a create-react-app este proceso se hace de forma automática. Al final todos los components y pages que creamos se optimizan y tu aplicativo final termina usando lo que hay dentro de esas carpetas que mencionas.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **alainccc** (1)
Hola y si quiero publicarlo en mi propio server que necesito?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Luis Daniel Becerra Avellaneda** (2)

		
		Creo que a travez de now tambien puedes hacerlo, busca en la documentacion o toma el curso de now <https://platzi.com/clases/deploy-now/>
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **alainccc** (0)
Gracias
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Oscar Barajas Tavares (Platzi)** (1)

		
		También puedes ponerte el reto de hacer deploy en heroku o amazon web services, te servira mucho entender como hacerlo.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **David Daniel Castillo Nava** (1)
Que significan todas las carpetas que genera el comando build?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Eduardo Rasgado Ruiz** (3)

		
		Es el bundle y sus amigos, son el resultado de transpilar, compactar y hacer legible nuestro código en todas las plataformas de navegación posibles. Usualmente puede hacerse a mano cuando trabajas solo con ReactJS o VanillaJS con ES6, etc. pero gracias al framework Next o a create-react-app este proceso se hace de forma automática. Al final todos los components y pages que creamos se optimizan y tu aplicativo final termina usando lo que hay dentro de esas carpetas que mencionas.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **David Daniel Castillo Nava** (1)
Como puedo crear un dist folder para colocarlo en git pages??
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Erik Ochoa (Platzi)** (3)

		
		No todas las aplicaciones web pueden ser hosteadas en github pages. Por ejemplo aplicaciones como la de este curso no estoy seguro pueda generar los archivos totalmente estáticos para subirlos a github pages ya que usa Server Side Rendering y para eso necesitamos node en el servidor.
		
		Ciertamente Next permite hacer la exportación de los archivos estáticos pero aclara que no es aplicable en todos los proyectos. [Export Into a Static HTML App](https://nextjs.org/learn/excel/static-html-export)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

## 0220. Conclusiones del curso

### Descripción:


¡Felicitaciones, Terminamos el curso de Next.JS!  
Recuerda compartir tu proyecto con la comunidad en el sistema de discusiones.
  *[CI]: Integración Contínua
  *[CD]: Despliegue Contínuo

### Comentarios:

* **Cesar Becerra** (11)

	
	Mas cursos con este profesor!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **José Gabriel Guzmán Lopéz** (1)

		
		 **Total este tipo es un PRO**
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **mariomenjr** (1)

		
		¡POR FAVOR!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Gregorio Garcia** (10)

	
	Este profesor me dejó sorprendido, demás de excelente. ¡Muchísimas gracias! 😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **miguelcostero** (4)

	
	<https://podcasts-zauwrglmeu.now.sh>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **miguelcostero** (1)

		
		Excelente curso, muy buen profesor.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **LeandroVidela** (3)

	
	Excelente profe!
	
	Apliqué los conocimientos del curso para crear un template de mi portfolio y quedó súper!!!
	
	[Demo del portfolio publicado con Now](https://portfolio.leandrovidela.now.sh/)
	
	[Repo del portfolio en GitHub](https://github.com/leandrovidela/portfolio)
	
	Gracias! 😄 😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Manuel Ojeda** (2)

		
		Está super genial tu portafolio 🤘
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **LeandroVidela** (1)

		
		Mucha gracias, pásame el tuyo!
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Carlos Rivas** (3)

	
	A riesgo de que me caigan a piedras los Leonidas-lovers, pienso que de ahora en adelante @robertomgonzalez es el profesor que debería impartir los cursos de React.js, definitivamente una forma muy limpia de explicar y sin dejar cabos sueltos.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Juan Luis Rojas León** (3)

	
	[Repositorio en Github](https://github.com/rojasleon/next-podcasts)  
	[Aplicación web](https://next-podcasts.now.sh/)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jsechirinos** (3)

	
	`Next.js` is Ready…!!
	
	[Code](https://github.com/JoseChirinos/podcasts)  
	[Live Podcast](https://podcasts-nyqtzxpzdh.now.sh/)
	
	**Bien Explicado, Excelente curso…!!!**
	
	Siguiente parada PWA con React…!!!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jesus Garcia** (3)

	
	eran altas las expectativas sobre todo el profesor que no había visto, y todo fue excelente 10pts para el y el curso. son los mejores platzi.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **Oscar Barajas Tavares (Platzi)** (1)

		
		Como te fue en el curso, muestranos tu proyecto final.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Ruben Padilla** (2)

	
	Comparto el link del repositorio y deploy:
	
	⚡️ [Repositorio](https://github.com/rubbenpad/podcaster)  
	🚀 [Deploy](https://podcaster-next.now.sh/)
	
	💅🏻 Implemente el proyecto con styled-components.
	
	💪🏻 Agradezco feedback
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jhonatan Miranda** (2)

	
	Muy buen curso 😃 uno de los mejores.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **WilliamVelazquez** (2)

	
	Magnífico curso! Todo gracias al excelente profesor que estuvo a cargo, espero que tengamos la oportunidad de tener más cursos impartidos por Roberto! 😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **jhurtadojerves** (2)

	
	Muy bueno el curso, me encantó. Excelente contenido, excelente profesor.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **fredy bustos** (2)

	
	Estuvo excelente. Quedaron muchas cosas mucho mas claras.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **.** (2)

	
	Estuvo increíble el curso, muchos conceptos que no conocía o no tenía tan claros ahora los tengo listos para aplicar. Gracias Robert!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **johnaagudelo** (1)

	
	[Repository](https://github.com/johnaagudelo0820/podcasts-nextjs)  
	[Deploy](https://podcasts-gamma.now.sh/)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Le_MaliX** (1)

	
	👨‍💻 [Código fuente](https://github.com/LeMalix/nextjs-podcast-player)  
	🌐 [Deployment](https://nextjs-podcast-player.now.sh/)  
	Muy buen curso!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **cristian soria** (1)

	
	Muy bueno el dictado del curso Roberto. Felicitaciones!  
	Consulta, El manejo del statement cuando una app es más grande como lo manejas? Esta bien combinar con Redux? De ser asi las llamas las hacemos en el getInitialProps?
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **alexabellerman** (1)

	
	<https://github.com/Hiteple/platzi-podcast> 😃
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Lauramduquesa** (1)

	
	<https://podcast-roan-phi.now.sh/>
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Fernando Azuaje** (1)

	
	excelente curso, quisiera mas cursos con el profesor Roberto aqui en platzi
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Erick Sánchez Noguerón** (1)

	
	Buen Curso :3
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **orivasm44** (1)

	
	El curso esta muy bien no es necesario saber react pero es posible que si no lo conoces te queden algunas dudas, muy buena explicación @robertomgonzalez
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Luis Diaz Venero** (1)

	
	excelente servicio 😄 el mejor profe de Platzi!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **JoosCode** (1)

	
	Grande profe salu2 SUPER AGRADECIDO CON USTED!!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Gaston Morales** (1)

	
	Realmente este fue un curso increíble 😄
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Paola Camcho Alapizco** (1)

	
	Increíble curso y profesor, espero encontrarlo en otros cursos.  
	Dejo link del resultado proyecto podcast-app
	
	[Repo](https://gitlab.com/pahoalapizco/podcast-app)  
	[Podcast-App](https://podcast-app.paolacalapizco.now.sh/)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **antony999k** (1)

	
	Muy buen profesor, se me hizo un poco rápido el curso al principio, pero esta exelente
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Tobías Schwarz** (1)

	
	El mejor profesor (a mi gusto) que he visto en Platzi (después de Freddy)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **carlos.guilarte.5** (1)

	
	Alguien me puede dar una referencia para porder subir mi proyecto en producción en un servidor con ubuntu.? tengo una aplicación completa y no se como correrlo en un server con ubuntu. Saludos.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **wilson_romero** (1)
Te recomiendo digitalocean hay un curso muy bueno en platzi
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

	* **Daniel Esteves** (1)

		
		Lo que puedes hacer es tener una cuenta en Digital Ocean y clonar tu repositorio en ese servidor, luego activarlo y que siempre esté en linea con el paquete `pm2` y redirigir tu dominio a DO. Pero claro esa es la manera difícil y complicada, si lo quieres hacer de una manera mucho más rápida y sencilla puedes hacer deploy en [now.sh](http://now.sh)
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

* **Matias Gabriel De Marines** (1)

	
	Realmente muy buen profesor!
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **José Gabriel Guzmán Lopéz** (1)

	
	 **MI PROYECTO**  
	[](https://podcasts-kpehsmweph.now.sh)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **José Gabriel Guzmán Lopéz** (1)

	
	**Gracias Roberto**  
	Este es uno de los mejores profesores que tiene Platzi  
	no se puso con rodeos aprendí bastante.  
	**SOS GRANDE**  
	Saludo desde colombia.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Ricardo Medina** (1)

	
	Excelente curso para empezar con este maravilloso Framework Web y muy bien explicado por el profesor. Saludos.
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Eduardo Rasgado Ruiz** (1)

	
	Mi app:  
	[Podcastiny](https://podcasts-nsgvextlwc.now.sh)
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

* **Jose Galbis Soler** (1)
Me surge la duda de si es mejor emplear el uso de class o por contra utilizar functions. A la hora de definir las pages y los components....
	  *[CI]: Integración Contínua
	  *[CD]: Despliegue Contínuo

	* **assistcardaciit** (2)

		
		Mi recomendacion es que te acostumbres a funciones en lugar de clases. Si vas a incursionar en el mundo React la tendencia es ir para el lado de Hooks o sea programacion funcional.
		  *[CI]: Integración Contínua
		  *[CD]: Despliegue Contínuo

