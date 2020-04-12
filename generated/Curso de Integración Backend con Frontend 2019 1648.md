[Curso de Integración Backend con Frontend 2019 1648](https://platzi.com/cursos/bff-2019)

# Introducción a Backend for Frontend [4452]

## 0010. Bienvenido al Curso [22220](https://platzi.com/clases/1648-bff-2019/22220-bienvenido-al-curso/)

### Descripción:


¡Hola! Tu profesor para este curso será Carlos Sampol, Frontend Developer de Platzi. Vamos a integrar el Backend y el Frontend tomando la autenticación y API que ya habíamos creado anteriormente en la Escuela de JavaScript.

A lo largo de toda la escuela de JS hemos aprendido a configurar nuestro entorno, cómo manejar conceptos básicos de Git, configurar VS Code y luego creamos una aplicación de HTML y CSS estática. A continuación añadimos interactividad con React. Luego manejamos un estado centralizado y manejamos rutas.

Después tomamos el proyecto creado y elaboramos el servidor de Server Side Rendering. Paralelamente estábamos creando una API para listar nuestras películas. Además autenticamos el inicio de sesión y autorización del usuario para que tenga el flujo normal de una aplicación.

Al unir el Backend y Frontend vamos a integrar nuestra API creando pruebas con Jest. Finalmente vamos a hacer un despliegue en DigitalOcean para poder acceder a nuestra aplicación desde cualquier sitio.

¡Empezamos!

### Links:

* [GitHub - platzi/PlatziVideo at feature/integration](https://github.com/platzi/PlatziVideo/tree/feature/integration)

### Comentarios:

* **Massimo Di Berardino** (4) [954635](https://platzi.com/comentario/954635/) 

	Ahora si se viene lo chido 😄

* **Favio Sauto** (4) [719072](https://platzi.com/comentario/719072/) 

	Las clases 5, 10 y 13 siguen apareciendo en proceso y también me gustaría saber que código utiliza y/o modifica de los anteriores cursos de la escuela de Javascript, solo me queda este curso para completar la escuela js y sería bueno que muestren los archivos que se modifican y que partes se modifican porque ando confundido en esa parte, además de que se liberen las 3 clases que faltan. Espero su respuesta team Platzi 😁

	* **sampol.90 (Platzi)** [719072] (3)

		Hola Favio, el código del curso lo puedes encontrar [aqui](https://github.com/platzi/PlatziVideo/tree/feature/integration) o en la sección de enlaces. Respecto a los materiales faltantes que corresponden a la solución de retos estarán disponibles muy pronto.

	* **Favio Sauto** [719072] (1)

		Gracias!

* **TOGSAC** (3) [707673](https://platzi.com/comentario/707673/) 

	Cuando estará completo el curso ya que no carga las clases 5 ,10 y 13

	* **Daniel Esteves** [707673] (1)

		¡Hola! Pronto estará disponible el material número cinco, el diez y trece ya están listos en la plataforma 💪

* **manuel-mendoza142** (2) [785756](https://platzi.com/comentario/785756/) 

	Antes de Ver este curso cual deberia ver antes

	* **Daniel Esteves** [785756] (5)

		¡Hola Manuel! Este curso hace parte de [Escuela JS](https://platzi.com/clases/escuela-de-javascript/), entra y podrás ver los cursos en orden uno por uno 💪

	* **Luis Rodriguez** [785756] (3)

		Definitivamente deberías de ver los cursos anteriores dentro de la Ruta de Aprendizaje de “[Carrera de Javascript](https://platzi.com/learning-path/escuelajs/)”, ya que lo que vas a ver de código es lo que se construyo en las clases previas.

* **Brando Rodríguez** (2) [703101](https://platzi.com/comentario/703101/) 
Seguimos 💛 javascript !!

* **Camilo Andrés Santana Lizcano** (1) [1030432](https://platzi.com/comentario/1030432/) 

	Ha sido un largo camino para llegar hasta aquí, muy emocionado de empezar 😄

* **daag13** (1) [935597](https://platzi.com/comentario/935597/) 
Hola, alguien me puede contar que cursos serían prerequisito pars este curso?

	* **Ruben Padilla** [935597] (2)

		Lo recomendable es que sigas la carrera de Javascript desde el inicio. Haras el frontend y el backend del proyecto. En este curso haces la integración de las 2 partes.

* **Andres Roberto Coello Goyes** (1) [922130](https://platzi.com/comentario/922130/) 

	¿se puede hacer lo mismo si tengo el fronted con NEXT ?

* **wilantury** (1) [821707](https://platzi.com/comentario/821707/) 

	Como siempre, con muchas ganas de iniciar el curso.

## 0020. Cómo instalar NVM [24687](https://platzi.com/clases/1648-bff-2019/24687-como-instalar-nvm/)

### Descripción:


Si tienes más de un mes programando con Node.js te habrás dado cuenta que se actualiza a cada rato. [Acá podrás ver](https://github.com/nodejs/Release/blob/master/schedule.svg) la planeación a futuro de Node.js conforme a su versión LTS.

Cada nueva actualización puede producir problemas o bugs dentro de tus proyectos, aquí es donde entra a escena [NVM](https://github.com/nvm-sh/nvm): Node Version Manager. Su principal funcionalidad es que te permite instalar distintas versiones de Node.js y elegir cuándo y cuál usar con solamente un comando:
``` 
    nvm use –lts // actual versión LTS. 
    nvm use 6.2.1 // versión 6.2.1 
    
```

## Instalar NVM en Linux y Mac

Su instalación es muy sencilla, simplemente debemos correr el siguiente comando:
``` 
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.1/install.sh | bash 
    
```

Para verificar que la instalación se realizó sin problemas prueba corriendo el comando:
``` 
    nvm --version 
    
```

Si te llega a marcar un error como el siguiente: `nvm: command not found`, simplemente debes añadir las siguientes líneas de código dentro de tu archivo `.bash_profile` o `~/.zshrc`. Supongamos que viste el increíble Curso de Prework y tienes instalado zsh, debes correr el siguiente comando:
``` 
    // Vamos a editar el archivo zshrc con Visual Studio Code, puedes usar el editor que prefieras. 
    code ~/.zshrc 
    
```

Hasta el final del archivo vas a añadir:
``` 
    export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")" [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" 
    
```

![código del archivo zshrc](https://static.platzi.com/media/user_upload/Screenshot%20from%202019-11-12%2016-44-35-0fe5ce3e-e13a-4537-9b35-ab6933b960f6.jpg)

## Instalar NVM en Windows

nvm no tiene soporte para Windows, pero para ello existe [nvm-windows](https://github.com/coreybutler/nvm-windows). Su instalación es muy sencilla, simplemente debes entrar a su [sección de descargas](https://github.com/coreybutler/nvm-windows/releases) y descargar el archivo [nvm-setup.zip](https://github.com/coreybutler/nvm-windows/releases/download/1.1.7/nvm-setup.zip).

Ya que tenemos el archivo zip procedemos a descomprimirlo y ejecutamos el archivo _nvm-setup.exe_.

### Comentarios:

* **Iván Darío Sánchez Jiménez** (3) [825224](https://platzi.com/comentario/825224/) 

	Para los usuarios de Linux luego de correr el script puede retornar command not found al tratar de consultar la versión, antes de modificar el archivo (~/.bash_profile, ~/.zshrc, ~/.profile, or ~/.bashrc) abrir una nueva terminal y volver a intentar
	``` 
	    nvm --version
	    
	```
	
	[Consultado en: Node Version Manager](https://github.com/nvm-sh/nvm)

* **Juan Carlos García Esquivel** (1) [834760](https://platzi.com/comentario/834760/) 

	No me funciono el código de arriba, tengo nvm con hyper sobre ubuntu en W10 y esto fue lo que si me funciono:
	
	  1. **`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.1/install.sh | bash`**
	  2. Abrir archivo .zshrc para edición: **`code ~/.zshrc`** o si no tienes vscode **`nano ~/.zshrc`**
	  3. Al final del archivo añadir este código: **`export NVM_DIR="$HOME/.nvm" [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm [ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"`**  
	4.Guardar cambios y reiniciar la terminal y listo ejecutas **nvm --version**
	
	

* **Carlos Gerardo Pérez Horta** (1) [822996](https://platzi.com/comentario/822996/) 

	Yo he estado usando [n](https://github.com/tj/n), que es un gestor de versiones de nodejs como nvm ¿Tendré algún inconveniente si no uso nvm?

## 0030. Múltiples versiones de Node con NVMRC [22221](https://platzi.com/clases/1648-bff-2019/22221-multiples-versiones-de-node-con-nvmrc/)

### Descripción:


Vamos a aprender el uso de la librería **nvm** que nos permite manejar múltiples versiones de Node solamente ejecutando un comando.

### Links:

* [GitHub - glrodasz/platzi-auth-passport](https://github.com/glrodasz/platzi-auth-passport)

* [GitHub - nvm-sh/nvm: Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions](https://github.com/nvm-sh/nvm)

### Comentarios:

* **Javier Fuentes Mora** (6) [823850](https://platzi.com/comentario/823850/) 

	Por eso no me gustan sus cursos … osea que archivos en especifico se van a copiar en el de SSR Teníamos algo en el server.js diferente a lo que muestra lo que muestra se parece al index.js del curso de autenticación , se sobrescribe y se cambia el nombre o se agrega algo ?? no explica nada

* **JUAN SILVA** (3) [872722](https://platzi.com/comentario/872722/) 

	para los que estan igual de perdidos hay que usar el siguiente repositorio (clonarlo) <https://github.com/platzi/PlatziVideo/tree/feature/integration> y actualizar los archivos .env

* **Fernando Azuaje** (3) [816158](https://platzi.com/comentario/816158/) 

	alguien me puede explicar cuales son los archivos que se van a integrar ahora al ssr? de parte del curso de passport

* **oqodigital** (3) [71640](https://platzi.com/comentario/801359/) 
Hola. Faltó en un archivo .env.example, para guiarnos, porque como que se juntó todo en el nuevo archivo de integración pero hay cosas qu...

	* **zefe** [71640] (2)

		```
		    PORT =3001
		    NODE_ENV=development
		    API_URL=
		    API_KEY_TOKEN=
		    
		```

* **rusbel bermúdez rivera** (2) [1024439](https://platzi.com/comentario/1024439/) 

	No hubo integración continua con los dos cursos que dio el profesor 😕 mal plan…

* **Manuel Ojeda** (2) [736569](https://platzi.com/comentario/736569/) 

	Para quienes estén utilizando WSL con Ubuntu en Windows 10 e hicieron la instalación con Curl, utilicen este comando al final de su archivo .zshrc
	``` 
	    . "$HOME/.nvm/nvm.sh"
	    
	```

	* **Tonalli López** [736569] (2)

		Que pasos seguiste para que te funcionara?, porque por más que lo instalo y lo desinstalo y vuelvo a seguir lo pasos de la documentación no me funciona nvm

	* **th3_bu6** [736569] (3)

		creo que la linea completa que debes insertar es:  
		[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh  
		despues de insertarla en tu archivo .zshrc deberas reiniciar la consola y deberia funcionar

* **Jair Balcazar Cobeña** (1) [1107547](https://platzi.com/comentario/1107547/) 

	Estoy demasiado perdido, la idea no era llegar y bajar el repositorio para poder seguir este curso sino venir trabajando con los proyectos ya realizados en los cursos anteriores.

* **Leonel Adrian Oliveros Munoz** (1) [844829](https://platzi.com/comentario/844829/) 

	Para los que se preguntan por el server.js
	``` 
	    import express from 'express';
	    import dotenv from 'dotenv';
	    import webpack from 'webpack';
	    import helmet from 'helmet';
	    import axios from 'axios';
	    import passport from 'passport';
	    import boom from '@hapi/boom';
	    import cookieParser from 'cookie-parser';
	    import main from './routes/main';
	    
	    dotenv.config();
	    
	    const ENV = process.env.NODE_ENV;
	    const app = express();
	    const PORT = process.env.PORT || 3000;
	    
	    app.use(express.json());
	    app.use(cookieParser());
	    app.use(passport.initialize());
	    app.use(passport.session());
	    app.use(express.static(`${__dirname}/public`));
	    
	    // Basic strategy
	    require('./utils/auth/strategies/basic');
	    
	    if (ENV === 'development') {
	      console.log('Loading dev config');
	      const webpackConfig = require('../../webpack.config');
	      const webpackDevMiddleware = require('webpack-dev-middleware');
	      const webpackHotMiddleware = require('webpack-hot-middleware');
	      const compiler = webpack(webpackConfig);
	      const serverConfig = {
	        contentBase: `http://localhost${PORT}`,
	        port: PORT,
	        publicPath: webpackConfig.output.publicPath,
	        hot: true,
	        historyApiFallback: true,
	        stats: { colors: true },
	      };
	      app.use(webpackDevMiddleware(compiler, serverConfig));
	      app.use(webpackHotMiddleware(compiler));
	    } else {
	      console.log(`Loading ${ENV} config`);
	      app.use(helmet());
	      app.use(helmet.permittedCrossDomainPolicies());
	      app.disable('x-powered-by');
	    }
	    
	    app.post('/auth/sign-in', async (req, res, next) => {
	      passport.authenticate('basic', async (error, data) => {
	        try {
	          if (error || !data) {
	            return next(boom.unauthorized());
	          }
	    
	          req.login(data, { session: false }, async (error) => {
	            if (error) {
	              next(error);
	            }
	    
	            const { token, ...user } = data;
	    
	            res.cookie('token', token, {
	              httpOnly: !(ENV === 'development'),
	              secure: !(ENV === 'development'),
	            });
	            res.status(200).json(user.user);
	          });
	        } catch (error) {
	          next(error);
	        }
	      })(req, res, next);
	    });
	    
	    app.post('/auth/sign-up', async (req, res, next) => {
	      const { body: user } = req;
	      try {
	        const userData = await axios({
	          url: `${process.env.API_URL}/api/auth/sign-up`,
	          method: 'post',
	          data: user,
	        });
	        res.status(201).json({
	          name: req.body.name,
	          email: req.body.email,
	          id: userData.data.data,
	        });
	      } catch (error) {
	        next(error);
	      }
	    });
	    
	    app.get('*', main);
	    
	    app.listen(PORT, (err) => {
	      if (err) console.log(err);
	      console.log(`Server runding on ${PORT}`);
	    });
	    
	```

	* **gustavoa6791** [844829] (1)

		alguien me puede decir en que clase de que curso se hizo este server

	* **Dante Calderón** [844829] (1)

		Es todo un curso, el curso de [autenticacion con passport](https://platzi.com/clases/passport/)

	* **jandrey** [844829] (1)

		No exactamente yo lo que veo es que el profesor copio y pego del curso de passport pero no explico esa parte simplemente muestra el código ya copiado del otro curso.

* **Jorgelisapa** (1) [825754](https://platzi.com/comentario/825754/) 

	NVM una libreria para manejar diferentes versiones de Node js.

* **Jorge Giraldo Guerrero R.** (1) [732263](https://platzi.com/comentario/732263/) 

	Dime cuales son los cursos que debo tener para hacer este, gracias.

	* **Daniel Esteves** [732263] (3)

		¡Hola Jorge! Para poder seguir con este curso debes haber visto primero estos dos:
		
		* [Curso de Frontend Developer](https://platzi.com/clases/frontend-developer/)
		* [Curso de Backend con Node.js](https://platzi.com/clases/backend-nodejs/)
		
		
		
		Estos cursos corresponden a la Escuela de JavaScript 💪

	* **David Behar** [732263] (1)

		Uff, realmente son muchos, acá te paso la liga de todos:  
		<https://platzi.com/escuela-js/>
		
		[![escuela.png](https://static.platzi.com/media/user_upload/escuela-7617d35b-8d58-4aa8-af5b-c58c1eab6de6.jpg)](https://platzi.com/escuela-js/)

* **AryRosvall** (1) [73136](https://platzi.com/comentario/829172/) 
Qué token es el que se coloca, el del public o el admin para generar los usuarios?

	* **Luis Arturo Lira Cerda** [73136] (2)

		Según lo que mencionó Guillermo en el curso de Passport, en el server de SSR debe ir el public. El admin debería ir en un admin cliente. Aunque no sé si los construiremos también en este curso.

## 0040. ¿Qué es Backend for Frontend [22647](https://platzi.com/clases/1648-bff-2019/22647-que-es-backend-for-frontend/)

### Descripción:


### Comentarios:

* **wilantury** (5) [821726](https://platzi.com/comentario/821726/) 

	Patrón de software construido con microservicios,crea backend específico para frontend con necesidades propias y específicas.

## 0050. El patrón de software Backend for Frontend [22656](https://platzi.com/clases/1648-bff-2019/22656-el-patron-de-software-backend-for-frontend/)

### Descripción:
![Infografia-Backend-frontend-3.jpg](https://static.platzi.com/media/user_upload/Infografia-Backend-frontend-3-ff888934-82aa-4e9c-978e-78529238a34e.jpg)

### Comentarios:

* **nicobytes** (3) [1004897](https://platzi.com/comentario/1004897/) 

	¿GraphQL no sería una buena solución para esto? Ya que como en un lenguaje de consulta para APIS cada cliente (mobile, web, tablet) pide los datos que necesita.

* **Román Alexis Suárez** (3) [728120](https://platzi.com/comentario/728120/) 

	Por favor revisar la siguiente clase, ya que no sirve o aún no la han subido al igual que otras clases del siguiente módulo:(

	* **Daniel Esteves** [728120] (3)

		¡Hola Román! Pronto estará disponible la siguiente clase y te estaremos avisando cuando esté lista 💪

	* **lcmartinez_ (Platzi)** [728120] (2)

		Ya está disponible:  
		<https://platzi.com/clases/1648-bff/22224-que-es-redux-thunk/>

* **eddyarellanes** (2) [841819](https://platzi.com/comentario/841819/) 

	Aquí también da pie para ver conceptos como Serverless con Microservices.

* **FizIrvin** (2) [831248](https://platzi.com/comentario/831248/) 

	muy buena infografía, ¿la hizo el profe?

	* **Gabriel De Andrade (Platzi)** [831248] (3)

		Hola! El contenido de las infografías la realizan los profesores, junto con el equipo de educación y el equipo de diseño es el encargado de toda la parte visual 😄

# Integra PlatziVideo con la API [4453]

## 0060. ¿Qué es Redux Thunk [22224](https://platzi.com/clases/1648-bff-2019/22224-que-es-redux-thunk/)

### Descripción:


 **thunk** es una función que está dentro de una función; lo que la hace especial es que está siendo retornada a esa función.

**redux-thunk** hace un attach o bind de la función dispatch (para poder despachar acciones) y la función getState. Esto nos garantiza que al trabajar con funciones asíncronas (por ejemplo, hacer la petición de inicio de sesión o registro de usuario) tengamos que seguir determinados pasos; ejemplo, si hacemos la petición de inicio de sesión y está bien, podremos usar una acción para configurar el estado de nuestro Store.

### Links:

* [GitHub - reduxjs/redux-thunk: Thunk middleware for Redux](https://github.com/reduxjs/redux-thunk)

### Comentarios:

* **wilantury** (5) [821757](https://platzi.com/comentario/821757/) 

	Hola, aquí dejo una lectora para complementar esta clase. <https://platzi.com/blog/como-funciona-redux-thunk/>

* **oqodigital** (2) [71647](https://platzi.com/comentario/801499/) 
El proyecto no me funciona. Hice la instalación completa y no funciona. Será mejor que pesque el de ssr y agregue los cambios mejor? ya q...

	* **zefe** [71647] (2)

		Lo que hizo Guillermo en ssr es un poco diferente, incluso aquí Sampol los métodos de inicio de sesión y registro lo hace en src/server/server.js [revisa esos 2 metodos aquí es este commit](https://github.com/platzi/PlatziVideo/commit/5bbf0aa39f67f1d964ee58e2f9d2de36611d7461)

* **RichBarusta** (1) [981615](https://platzi.com/comentario/981615/) 

	que templare usas para que los === y => te aparezcan estilizados ??

* **jandrey** (1) [965883](https://platzi.com/comentario/965883/) 

	Las variables del archivo .env cuales son ?¿

	* **Alejandro Moraga** [965883] (1)

		De que proyecto especificamente?, si es para el proyecto de front se ocuparon estas variables en el archivo .env
		``` 
		    // CONFIG
		    PORT=
		    NODE_ENV=
		    
		    
		    // API URL
		    API_URL=
		    
		    
		```

* **Rene Ismael Barrios Rojas** (1) [822353](https://platzi.com/comentario/822353/) 

	Que es mejor redux thunk o redux saga?

	* **Nestor Cepeda (Platzi)** [822353] (3)

		¡Hola! 😃  
		_" Thunks can never act in response to an action. Redux-Saga, on the other hand, subscribes to the store and can trigger a saga to run or continue when a certain action is dispatched."_  
		[Referencia](https://decembersoft.com/posts/redux-thunk-vs-redux-saga/)

	* **Nestor Cepeda (Platzi)** [822353] (3)

		Contestando puntualmente a tu pregunta, diría que depende del proyecto. 🤓

* **johnyauyo** (1) [70678](https://platzi.com/comentario/780103/) 
el video/texto 5, Optimización de rutas para el inicio de sesión, no esta cargado.

	* **Daniel Esteves** [70678] (2)

		¡Hola John! La lectura aún no está lista pero cuando ya esté subida a la plataforma te informaremos 🙌

## 0070. Registro de usuario [22225](https://platzi.com/clases/1648-bff-2019/22225-registro-de-usuario/)

### Descripción:


### Comentarios:

* **Javier Fuentes Mora** (5) [825049](https://platzi.com/comentario/825049/) 

	muy mal que no sepamos ni que garegar del curso pasado

* **Luis Arturo Lira Cerda** (4) [869493](https://platzi.com/comentario/869493/) 

	Hay algo muy importante que no mencionan para que lo de esta clase pueda funcionar y es que cambiaron la respuesta que tiene el Server Side Render en la ruta de /auth/sign-up. En el curso con Guillermo solo habíamos puesto que esa ruta regresara un mensaje, pero en el vídeo aparece de esta manera:
	``` 
	    app.post('/auth/sign-up', asyncfunction (req, res, next) {
	        const { body: user } = req
	        try {
	            const userData = await axios({
	                url: `${config.apiUrl}/api/auth/sign-up`,
	                method: 'post',
	                data: user
	            })
	    
	            res.status(201).json({
	                name: req.body.name,
	                email: req.body.email,
	                id: userData.data.data
	            })
	        } catch (err) {
	            next(err)
	        }
	    })
	    
	```
	
	La escuela de JavaScript me ha parecido muy buena en general, excepto por estos dos cursos con Sampol. En este y en del SSR han habido varias cosas que no explicaron, algunas las noté viendo los vídeos y otras viendo los comentarios.

* **Alejandro Moraga** (3) [996128](https://platzi.com/comentario/996128/) 

	Los cursos de sampol deben ser los unicos que te hacen revisar el codigo una y otra y otra vez, un 10. ❤️

	* **rusbel bermúdez rivera** [996128] (1)

		no me se hace muy proactivo, cuando tu tiempo es limitado en el dia para poder estudiar 3 horas reconfigurando no es buena practica

* **Gerardo Nava Pereda** (1) [982863](https://platzi.com/comentario/982863/) 

	En la función “registerUser” el parámetro “redirectUrl” puede ser sustituido por “history” y hacer un
	``` 
	    history.push("/url")
	    
	```
	
	así mantenemos la SPA de react router redux y no recargar la aplicación.
	
	Esto va a recargar toda la Aplicación:
	``` 
	    window.location.href = redirecUrl
	    
	```

	* **rusbel bermúdez rivera** [982863] (1)

		a no solo me funciona utilizando history.push, no me redirecciona como lo hace sampol

* **Gerardo Nava Pereda** (1) [982856](https://platzi.com/comentario/982856/) 

	¿Por que a todo le pone payload como naming, es eso buena o mala práctica? ¿No debería ser más declarativo con el nombre de sus parámetros (más descriptivo)? Entre tanto payload ya no sabes que significa payload xD

* **Luis Arturo Lira Cerda** (1) [869512](https://platzi.com/comentario/869512/) 

	Algo que me pasa es que necesito poner en modo production para que me funcione esto, si lo uso en mo de desarrollo el formulario sólo recarga la página y pone el texto de los inputs en la URL.
	
	Esta es mi configuración que usa en el modo de desarrollo, no sé si tengo algo mal configurado
	``` 
	    if (process.env.NODE_ENV == 'development') {
	        console.log('Loading dev config')
	        const webpackConfig = require('../../webpack.config.js')
	        const webpackDevMiddleware = require('webpack-dev-middleware')
	        const webpackHotMiddleware = require('webpack-hot-middleware')
	        const compiler = webpack(webpackConfig)
	        const serverConfig = {
	            contentBase: `http://localhost:${PORT}`,
	            port: PORT,
	            publicPath: webpackConfig.output.publicPath,
	            hot: true,
	            historyApiFallback: true,
	            stats: { colors: true }
	        }
	        app.use(webpackDevMiddleware(compiler, serverConfig))
	        app.use(webpackHotMiddleware(compiler))
	    }
	    
	```

	* **Luis Arturo Lira Cerda** [869512] (2)

		Después de estar un rato revisando el código y mi consola, tenía tiempo con este error en mi consola de Chrome, decía que era en Vendor.
		``` 
		    Uncaught Error: Expected the enhancer to be afunction.
		    
		```
		
		Lo que hice fue borrar toda la carpeta de assets y volver a compilar todo, npm run build para crear todo lo de producción y run dev para trabajar en desarrollo.
		
		También con esto mi extensión de React Dev Tools ha vuelto a diferenciar si estoy en producción o en desarrollo.

	* **Luis Arturo Lira Cerda** [869512] (2)

		También con eso que hice de borrar la carpeta de assets se arregló el problema de que el formulario no me funcionaba en desarrollo. Se los pongo aquí por si a alguien le pasa lo mismo.

	* **Victor Martin Ortiz Palacio** [869512] (1)

		Tenia el mismo problema, pero con un error diferente: **EvalError: call to eval() blocked by CSP** , y era porque tenia la siguiente configuracion de helmet:
		``` 
		    app.use(
		        helmet.contentSecurityPolicy({
		          directives: {
		            defaultSrc: ["'self'"],
		            styleSrc: ["'self'", 'maxcdn.bootstrapcdn.com']
		          }
		        })
		      );
		    
		```
		
		lo solucione moviendola para que sea utilizada solo en modo produccion.

	* **Alejandro Moraga** [869512] (2)

		a mi no me funcionaba en modo desarrollo, lo solucione eliminando del .env la variable de node_env y agregando en el package los siguientes codigos en cada entorno correspondiente, por alguna razon que aun no puedo comprender no puedo ejecutar el codigo de npm run build en modo desarrollo como lo tenia en el .ENV y lo solucione como lo mencione.
		``` 
		    "scripts": {
		        "build": "NODE_ENV=production webpack-cli --config webpack.config.js --colors",
		        "start:prod": "NODE_ENV=production node src/server/index.js",
		        "start:dev": "NODE_ENV=development nodemon src/server/index.js --exact babel-node"
		      },
		    
		```

* **edwintrumpet** (1) [847034](https://platzi.com/comentario/847034/) 

	Hay varias cosas que hacen que no funcione.  
	Como explica un compañero más abajo toca instalar e importar _@babel/polyfill_ , pero aún así va a fallar porque nuestro reducer espera un usuario de vuelta para autenticar y le estamos pasando la data con la que responde la API y esta no trae información del usuario.  
	Se podría arreglar pasándole al _registerRequest_ el payload eliminando antes el valor password.  
	Pero aún así no tendría una autenticación válida ya que no tendría el token, por lo que lo mejor es modificar el reducer para que solamente devuelva el mismo estado y no agregue nada a la llave user.

* **Leonel Adrian Oliveros Munoz** (1) [844872](https://platzi.com/comentario/844872/) 

	para el error de regeneratorRuntime debe installa el paquete @babel/polyfill y requerirlo en server/index.js
	``` 
	    require('ignore-styles');
	    require('@babel/polyfill');
	    
	    require('@babel/register')({
	      ignore: [/(node_modules)/],
	      presets: ['@babel/preset-env', '@babel/preset-react'],
	    });
	    
	    require('asset-require-hook')({
	      extensions: ['jpg', 'png', 'gif'],
	      name: '/assets/[hash].[ext]',
	    });
	    
	    require('./server.js');
	    
	    
	```

* **johanse7** (1) [823351](https://platzi.com/comentario/823351/) 

	Porque no utilizar Fetch en vez de axios?

	* **Javier Fuentes Mora** [823351] (3)

		axios lo unico que te ahora es el parse a .json()

	* **ziker** [823351] (3)

		Puedes implementar cualquier librería que te permita hacer peticiones creo que queda al gusto del programador, de igual forma te recomiendo no casarte con ninguna. Te dejo un enlace a ésta por si gustas <https://www.npmjs.com/package/trae>

## 0080. Validación de rutas [22226](https://platzi.com/clases/1648-bff-2019/22226-validacion-de-rutas/)

### Descripción:


### Comentarios:

* **Juan Carlos García Esquivel** (6) [823881](https://platzi.com/comentario/823881/) 

	Esto esta muy bueno, de la misma forma que se validan las rutas de home y de player, se debería validar la ruta de login de tal forma que si estamos logueados nos redireccione a home y no nos permita entrar a login ya que sería muy raro que eso pasara, la validación quedaria asi:
	``` 
	    {
	    path: '/login',
	    component: isLogged ? Home : Login,
	    exact: true
	    }
	    
	```

	* **David Behar** [823881] (1)

		Debería de mostrarse un Profile, eso creo, ¿no?

	* **Juan Carlos García Esquivel** [823881] (3)

		Hola David, la validación que propongo funciona de la siguiente forma: si ya estás logueado y accedes a esa ruta /login manualmente no deberías de poder entrar **porque ya estás logueado** , en ese caso lo mejor seria redireccionar al usuario al **home** , si tu quieres mostrar el perfil no veo problema **el objetivo es que no deberías entrar a esa ruta otra vez** , no tiene sentido que si ya estás logueado puedas entrar a esa ruta sería como poder loguearse múltiples veces.

* **Enrique Devars (Platzi)** (1) [917665](https://platzi.com/comentario/917665/) 

	Otra forma de validar las rutas es usando el componente Redirect que tiene react-router-dom
	``` 
	      <Route
	              exact
	              path="/login"
	              component={() => {
	                if (isLogged) {
	                  return <Redirect to="/dashboard" />;
	                } else {
	                  return <Login />;
	                }
	              }}
	            />```
	    
	```

## 0090. Integración del Inicio de sesión [22227](https://platzi.com/clases/1648-bff-2019/22227-integracion-del-inicio-de-sesion/)

### Descripción:


### Comentarios:

* **AlexGarrixen** (3) [69846](https://platzi.com/comentario/764656/) 
¿ Aun no se puede ver la clase de integracion con redes sociales?

	* **Erik Ochoa (Platzi)** [69846] (3)

		Hola, esa clase esta en formato de lectura que puedes consultar acá <https://platzi.com/clases/1648-bff/22228-integracion-del-inicio-de-sesion-con-redes-sociale/>

* **Juan J. López Lira** (2) [73824](https://platzi.com/comentario/841988/) 
Si corres el repo de esta clase no cargan los estilos de hecho en un proyecto que estoy haciendo alterno siguiendo esta metodología marca...

	* **Manuel Ojeda** [73824] (3)

		Parte del proyecto vienen desde el primer curso de esta carrera de JavaScript, es importante seguir todas las clases y el curso para al punto en el que estamos todo eso este cubierto.
		
		Pregunta, ¿haz llevado la carrera desde cero?
		
		¿qué problemas presentas?

* **Gschwind** (1) [773699](https://platzi.com/comentario/773699/) 

	![Selección_142.png](https://static.platzi.com/media/user_upload/Selecci%C3%B3n_142-3ae8f760-f51e-433a-991b-55d2686ca900.jpg)  
	![Selección_143.png](https://static.platzi.com/media/user_upload/Selecci%C3%B3n_143-387d4720-6e46-4a06-849d-987f1c857df3.jpg)
	
	Alguien más tiene este problema ? Me guarda las cookies pero nunca entra al try, se va por el catch y no me sale ningun error por consola

	* **Enrique Devars (Platzi)** [773699] (1)

		Me pasaba igual, lo que hice fue declarar el inical State fuera del main

* **Iván Bautista Guerrero** (0) [990449](https://platzi.com/comentario/990449/) 

	Bueno, después de muchos errores me di cuenta que hay que instalar el middleware **npm install cookie-parser.** Para poder usar req.cookies.

## 0100. Integración del Cierre de Sesión [22229](https://platzi.com/clases/1648-bff-2019/22229-integracion-del-cierre-de-sesion/)

### Descripción:


### Comentarios:

* **Leonel Adrian Oliveros Munoz** (1) [844878](https://platzi.com/comentario/844878/) 

	falta cambiar el initialstate por
	``` 
	    initialState = {
	    	user
	    }
	    
	```

## 0110. Fetch de estado inicial [22230](https://platzi.com/clases/1648-bff-2019/22230-fetch-de-estado-inicial/)

### Descripción:


### Reto

Implementa un método con la ayuda de redux y redux-thunk para que al momento de hacer clic en el símbolo de más (+) se haga el proceso de pegar el API, hacer request, enviar el post y que se asocie con el usuario que tiene la sesión iniciada.

### Comentarios:

* **Luis Arturo Lira Cerda** (4) [870184](https://platzi.com/comentario/870184/) 

	Esta fue mi solución al reto. Primero que nada, el endpoint de los userMovies recuerdo que lo hicimos diferentes a como se proponer en el vídeo. Nuestra ruta para crear una userMovie era enviar tanto el _id de la película y el id del usuario, sólo eso se guarda en esa colección.
	
	Así que primero lo que hice fue agregar un action que reciba el todas las props de la película, al componente de Carousel Item, también llega el _id, así que lo extraje de las props y también lo envío ya que es necesario.
	``` 
	    const { cover, title, year, contentRating, duration, id, customList, _id } = props;
	    
	        const handleSetFavorite = () => {
	            props.setFavoriteUserMovie({
	                cover, title, year, contentRating, duration, id, _id
	            });
	        };
	    
	```
	
	El action al recibir el payload, extrae el _id en otra variable y luego hace un post hacia nuestra /user-movies del SSR. Y cuando recibe la respuesta hacer el dispatch a setFavorite para que sea renderizado inmediatamente en la lista del usuario del frontend.
	``` 
	    exportconst setFavoriteUserMovie = (payload) => {
	        const { _id: movieId } = payload
	        return (dispatch) => {
	            axios({
	                url: '/user-movies',
	                method: 'post',
	                data: { movieId }
	            }).then(() => {
	                dispatch(setFavorite(payload))
	            }).catch(error => dispatch(setError(error)))
	        }
	    }
	    
	```
	
	En el SSR en la parte del post lo que hago es tomar también la cookie del id del usuario de la request y crear el objeto que espera nuestra API, el cual debe contener el userId y el movieId.
	``` 
	    app.post('/user-movies', asyncfunction (req, res, next) {
	        try {
	            const { body } = req
	            const { token, id } = req.cookies
	    
	            const userMovie = {
	                userId: id,
	                movieId: body.movieId
	            }
	            const { data, status } = await axios({
	                url: `${config.apiUrl}/api/user-movies`,
	                headers: { Authorization: `Bearer ${token}` },
	                method: 'post',
	                data: userMovie
	            })
	    
	            if (status !== 201) {
	                return next(boom.badImplementation())
	            }
	    
	            res.status(201).json(data)
	    
	        } catch (err) {
	            next(err)
	        }
	    })
	    
	```
	
	Luego, en la parte del main.js hago el get hacia la ruta /api/user-movies, pasó el id del usuario que está siendo tomado desde la cookie, así sólo traigo las películas de ese usuario. Al recibir la respuesta de las películas del usuario, como esta lista no tiene las props como el cover, tiitle, etc, lo que debo hacer es filtrar de la lista de películas y sólo dejar las que tenga la lista del usuario. Como no tengo mucha experiencia comparando elementos de array distintos, user dos for anidados, para determinar si la película dentro de la lista general estaba también en la lista de películas del usuario, si sí, la agrega a un nuevo array llamado myList y ese array es el que paso al estado.
	``` 
	    let userList = await axios({
	        url: `${config.apiUrl}/api/user-movies?userId=${id}`,
	        headers: { Authorization: `Bearer ${token}` },
	        method: 'get'
	    })
	    
	    moviesList = moviesList.data.data
	    userList = userList.data.data
	    
	    var myList = []
	    for (let i = 0; i < userList.length; i++) {
	        for (let j = i; j < moviesList.length; j++) {
	            if (moviesList[j]._id == userList[i].movieId) {
	                myList.push(moviesList[j])
	            }
	        }
	    }
	    
	```
	
	Si alguien sabe cómo comprar arrays de una manera más eficiente o más limpia me gustaría saberlo 😄

	* **jandrey** [870184] (2)

		```
		    const userMovies = []
		        movies.filter(movie => {
		          data.data.filter(id => {
		            if (id.movieId === movie._id) {
		              userMovies.push(movie)
		            }
		          })
		        })
		    
		```

* **Alejandro Moraga** (3) [1007139](https://platzi.com/comentario/1007139/) 

	Las clases con este profesor son un desafio constante xD!

* **José Abdiel Ortega Vázquez** (1) [1089594](https://platzi.com/comentario/1089594/) 

	De hecho la petición debería hacerse a /api/user-movies existe una para las peliculas del usuario solo le pasamos el id por req.query

* **Daniel Hurtado** (1) [969182](https://platzi.com/comentario/969182/) 

	Dependiendo del tipo de desarrollo (en este no tanto, por lo simple y liviano del desarrollo), sería más interesante que el fetch de la info de las películas lo hiciera el mismo componente al ser montado (ComponentDidMount()), esto tendría las siguientes ventajas:
	
	* La carga inicial del sitio sería más rápida (el navegador mostraría que está lista antes, mientras carga en segundo plano la información, que usualmente no es mostrada en la vista inicial o above the fold si no me equivoco).
	* Mejor manejo de errores: Si la petición se realiza dentro del SSR al momento de enviar la página renderizada, en caso de algún error en esta petición, si no se maneja bien y se aisla podría romper el renderizado completo y el usuario no vería nada
	* El código que creemos para hacer el fetch podríamos reutilizarlo en autorefresh, en cargar más, etc.
	
	

# Implementación de testing en el proyecto [4454]

## 0120. Configuración de fileMocks y styleMocks [22232](https://platzi.com/clases/1648-bff-2019/22232-configuracion-de-filemocks-y-stylemocks/)

### Descripción:


Vamos a agregar pruebas con la ayuda de jest y enzyme.

Instalaremos las dependencias con `yarn addd jest enzyme babel-jest enzyme-adapter -16 react-test-renderer --dev`

### Comentarios:

* **Daniel Hurtado** (1) [969228](https://platzi.com/comentario/969228/) 

	Estas dependencias solo serán usadas para desarollo, por lo que debemos instalarlas con npm i -D … o yarn add --dev … Recuerden que TODO lo hayamos instalado en nuestro proyecto sin señalar que es de desarrollo, será cargado en los .js que le enviamos al usuario.

* **Ruben Padilla** (1) [945974](https://platzi.com/comentario/945974/) 

	Plugin de Jest para vscode. Nos puede ayudar con nuestros test!  
	[jest-vscode](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)

## 0130. Implementando pruebas en el footer [22233](https://platzi.com/clases/1648-bff-2019/22233-implementando-pruebas-en-el-footer/)

### Descripción:


### Comentarios:

* **Diego Ivan Padilla Bernal** (6) [782320](https://platzi.com/comentario/782320/) 

	Si llegan a tener problemas con los test como por ejemplo que les aparesca “TypeError: Cannot read property ‘current’ of undefined” y les señale el error en “create(<Componente/>)”. Tienen que asegurarse de que las versiones de react y react-test-renderer sean las mismas  
	por ejemplo en mi caso sería:
	``` 
	    "react": "16.8.6",
	        "react-dom": "16.8.6",
	        "react-test-renderer": "16.8.6",
	    
	```

* **Omar Flores Grimontt** (4) [760107](https://platzi.com/comentario/760107/) 

	Si utilizas css modules, para probar el matching de las clases solo debes instalar un paquete más:
	``` 
	    yarn add--dev identity-obj-proxy
	    
	```
	
	Y cambiar el jest.moduleMapper de estilos en tu package.json
	``` 
	    "jest": {
	        "moduleNameMapper": {
	          "\\.(jpg|jpeg|png|gif)$": "<rootDir>/src/frontend/__mocks__/fileMock.js",
	          "\\.(scss|css)$": "identity-obj-proxy" // <== Acá
	        }
	      }
	    
	```
	
	Esto va a hacer que cuando se creen los snapshots jest interprete, el llamado de estilos de la siguiente manera:
	``` 
	    styles.footer === 'footer'
	    
	```
	
	Y por ende cuando cree el snapshot va a tener
	``` 
	    classname='footer'
	    
	```
	
	Luego de eso, corres el test tal cual como lo hizo el profesor y va a correr perfectamente.

	* **Omar Flores Grimontt** [760107] (2)

		Más información [acá](https://jestjs.io/docs/en/webpack.html#mocking-css-modules)

* **Daniel Hurtado** (2) [972279](https://platzi.com/comentario/972279/) 

	En un estudio de desarrollo profesional, las personas realmente realizan pruebas de componentes stateless?
	
	Personalmente las pruebas me parecen lo más aburrido en un desarrollo, pero son útiles para APIs y tal vez componentes que manejen estado, pero un componente como footer lo único que estamos verificando es si existe y tiene su clase, cuando este componente rara vez lo vamos a modificar, por lo que me parecería una perdida total del tiempo

* **José Abdiel Ortega Vázquez** (1) [1093965](https://platzi.com/comentario/1093965/) 

	Si alguien tiene un error con los watcher corra esto.
	``` 
	    echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
	    
	```

## 0140. Creando Mocks del store [22234](https://platzi.com/clases/1648-bff-2019/22234-creando-mocks-del-store/)

### Descripción:


Al usar React Router y Redux es necesario hacer un wrapper porque hay funciones o componentes que están siendo conectados con redux, esto se hace para que todo funcione de manera adecuada y nuestros tests no se rompan.

### Comentarios:

## 0150. Implementando pruebas en el header [22235](https://platzi.com/clases/1648-bff-2019/22235-implementando-pruebas-en-el-header/)

### Descripción:


### Comentarios:

* **Tonalli López** (6) [767097](https://platzi.com/comentario/767097/) 

	Si llegan a tener problemas con los test como por ejemplo que les aparesca “TypeError: Cannot read property ‘current’ of undefined” y les señale el error en “create(<Componente/>)”. Tienen que asegurarse de que las versiones de react y react-test-renderer sean las mismas

## 0160. Probando el envio del formulario [22236](https://platzi.com/clases/1648-bff-2019/22236-probando-el-envio-del-formulario/)

### Descripción:


Probaremos nuestro componente de registro para verificar que no haya cambios – usando Snapshot – y luego vamos a probar el formulario de registro para que cuando hagamos “ **submit** ” lleguemos a la función de envío de formulario.

### Comentarios:

* **Iván Darío Sánchez Jiménez** (2) [832424](https://platzi.com/comentario/832424/) 

	Si luego de crear un snapshot utilizando `yarn jest`, debemos realizar cambios en un script, necesitamos actualizar el snapshot para que el script actualizado y el nuevo snapshot puedan hacer match.
	
	Para esto iniciamos
	
	`yarn test:watch`
	
	En donde vamos a utilizar una función para regenerar snapshots.
	
	* Presionamos **u** (To update failling snapshots)
	
	
	
	y se actualizan todos los snapshots.

## 0170. Probando acciones [22237](https://platzi.com/clases/1648-bff-2019/22237-probando-acciones/)

### Descripción:


### Comentarios:

## 0180. Probando Gravatar function [22238](https://platzi.com/clases/1648-bff-2019/22238-probando-gravatar-function/)

### Descripción:


### Comentarios:

## 0190. Jest Coverage [22239](https://platzi.com/clases/1648-bff-2019/22239-jest-coverage/)

### Descripción:


### Links:

* [Curso de JavaScript Testing con Jest](https://platzi.com/cursos/js-jest/)

* [Writing Tests · Redux](https://redux.js.org/recipes/writing-tests)

### Comentarios:

# Despliegue del Frontend [4455]

## 0200. Creación del Droplet en Digital Ocean [22240](https://platzi.com/clases/1648-bff-2019/22240-creacion-del-droplet-en-digital-ocean/)

### Descripción:


### Links:

* [Droplets on DigitalOcean - More than just virtual machines](https://www.digitalocean.com/products/droplets/)

* [Curso de Digital Ocean](https://platzi.com/cursos/digital-ocean/)

### Comentarios:

* **dariusv** (2) [712355](https://platzi.com/comentario/712355/) 

	En Archivos y enlaces el botón de Descargar todo está descargando el html de esta pagina, no los archivos del curso.

	* **Daniel Esteves** [712355] (2)

		¡Hola! Ya acomodamos el error y puedes consultar sin problema los enlaces en la sección de archivos 💪

* **gustavoa6791** (1) [81803](https://platzi.com/comentario/990124/) 
se puede hacer deploy del frontend con now ?

	* **Juan David Castro (Platzi)** [81803] (1)

		Por supuesto. Tanto frontend como backend. 😉

## 0210. Instalación de paquetes requeridos para el despliegue en el servidor [22241](https://platzi.com/clases/1648-bff-2019/22241-instalacion-de-paquetes-requeridos-para-el-desplie/)

### Descripción:


### Links:

* [GitHub - nodesource/distributions: NodeSource Node.js Binary Distributions](https://github.com/nodesource/distributions)

### Comentarios:

* **Enrique Alexis Lopez Araujo** (2) [810177](https://platzi.com/comentario/810177/) 

	instalar nginx: apt-get install nginx

* **Enrique Alexis Lopez Araujo** (2) [810174](https://platzi.com/comentario/810174/) 

	Siempre que iniciemos un droplet en digital ocean escribir el siguiente comando apt-get update && apt-get upgrade

* **Adrian Camilo Caminos** (2) [770238](https://platzi.com/comentario/770238/) 

	si quisiera desplegar la aplicacion en firebase como seria la configuracion

	* **Daniel Esteves** [770238] (1)

		¡Hola! Firebase solo soporta el despliegue de archivos estáticos, así que si deseas subir y usar Firebase Hosting esa es la única condición

* **abdielalvarez** (1) [819611](https://platzi.com/comentario/819611/) 

	apt-get no está disponible para mac segùn yo entiendo, como debería escribir en terminal?  
	npm ERR! notsup Unsupported platform for apt-get@0.1.0: wanted {“os”:“linux”,“arch”:“any”} (current: {“os”:“darwin”,“arch”:“x64”})

	* **zefe** [819611] (2)

		por medio de la consola tienes que conectarte al servidor que creaste en DigitalOcean una vez conectado al servidor estas usando ubuntu linux. y es por eso que puedes ejecutar esos comandos desde la terminal de tu mac.

* **Enrique Alexis Lopez Araujo** (1) [810173](https://platzi.com/comentario/810173/) 

	Instalar nodejs curl -sL https://deb.nodesource.com/setup_10.x

* **Enrique Alexis Lopez Araujo** (1) [810172](https://platzi.com/comentario/810172/) 

	Instalar las siguientes dependencias apt-get install nodejs build-essential npm

## 0220. Configuración de nginx [22242](https://platzi.com/clases/1648-bff-2019/22242-configuracion-de-nginx/)

### Descripción:


### Comentarios:

* **Enrique Alexis Lopez Araujo** (4) [810186](https://platzi.com/comentario/810186/) 

	Verificar la configuracion de nginx con nginx -t

## 0230. Conexión SSH y clonación del proyecto [22243](https://platzi.com/clases/1648-bff-2019/22243-conexion-ssh-y-clonacion-del-proyecto/)

### Descripción:


Vamos a configurar una llave SSH para asociarla a GitHub y luego tener permisos para clonar el repositorio del proyecto, instalar dependencias y ejecutarlo.

### Links:

* [Generating a new SSH key and adding it to the ssh-agent - GitHub Help](https://help.github.com/en/enterprise/2.16/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

### Comentarios:

* **Iván Darío Sánchez Jiménez** (3) [834946](https://platzi.com/comentario/834946/) 

	SSH en linux
	``` 
	    ssh-keygen -t rsa -b4096 -C "name@mail.com"
	    
	```
	
	Activar el servidor ssh
	``` 
	    eval $(ssh-agent -s)
	    
	```
	
	Ruta de la llave ssh
	``` 
	    cd ~/.ssh/
	    
	```
	
	Agregar la llave privada al servidor
	``` 
	    ssh-add ~/.ssh/id_rsa
	    
	```
	
	Iniciar servidor de llaves SSH
	``` 
	    eval $(ssh-agent -s)
	    
	```
	
	Añadir la llave primaria al servidor SSH
	``` 
	    ssh-add ruta_llave_privada
	    
	```

* **Enrique Alexis Lopez Araujo** (2) [810215](https://platzi.com/comentario/810215/) 

	Correr el comando pm2 start src/server/index.js

* **Enrique Alexis Lopez Araujo** (2) [810214](https://platzi.com/comentario/810214/) 

	Instalar npm install pm2 -g para correr aplicaciones en background

* **José Abdiel Ortega Vázquez** (1) [1095163](https://platzi.com/comentario/1095163/) 

	Para pegar en la terminal con el teclado usas CTRL+Mayus o Shift+ V

* **diego-serrano** (1) [1031004](https://platzi.com/comentario/1031004/) 

	alguien mas tuvo estos problemas al momento de hacer build en la consola de Digital ocean?  
	![](![Screen Shot 2020-03-11 at 2.47.36 AM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-03-11%20at%202.47.36%20AM-e982ef10-be49-48f1-8a46-6b2f2746fa57.jpg)

## 0240. Instalación del Certificado SSL [22244](https://platzi.com/clases/1648-bff-2019/22244-instalacion-del-certificado-ssl/)

### Descripción:


### Comentarios:

* **carlosdummy14** (2) [1011246](https://platzi.com/comentario/1011246/) 

	Se que quizás no es el lugar, pero tengo una duda desde que empece con esta serie de cursos.
	
	Donde estamos almacenando los videos???  
	En el servidor de Digital o en donde???
	
	Gracias de antemano por la respuesta.

	* **José Abdiel Ortega Vázquez** [1011246] (1)

		Los videos los tienen en un servidor a parte lo más probable. Cuando subes contenido multimedia normalmente lo haces a un Content Delivery Network (CDN). Yo en lo personal una vez usé Cloudinary.

* **Jorge Humberto Nemogá Pinzón** (2) [832565](https://platzi.com/comentario/832565/) 

	[Cerbot - Nginx on Ubuntu 18.04 LTS (bionic)](https://certbot.eff.org/lets-encrypt/ubuntubionic-nginx)

* **José Abdiel Ortega Vázquez** (1) [1095348](https://platzi.com/comentario/1095348/) 

	Alguién me pude explicar este error y cómo solucionarlo por favor?
	
	se bloqueó debido a la falta de coincidencia del tipo MIME (“text/html”) (X-Content-Type-Options: nosniff)
	
	Esto hace que no carguen mis CSS y mi JS

## 0250. Cierre del curso [22245](https://platzi.com/clases/1648-bff-2019/22245-cierre-del-curso/)

### Descripción:


¡Felicitaciones has llegado al final del curso!

Junto a JavaScript has aprendido: maquetación, CSS, React, creaste y autentificaste una API, creaste un server side rendering y por último integramos todo y aplicaste pruebas unitarias, para después continuar con producción.

Ahora el camino que seguirá depende de ti, ¿Frontend?, ¿Backend? o ¿ambos? Y no lo olvides, ¡Nunca pares de Aprender!

### Links:

* [Bases de Datos](https://platzi.com/base-de-datos/)

### Comentarios:

# Bonus [4742]

## 0260. Integración del inicio de sesión con redes sociales Login con FIrebase y Google Web [22228](https://platzi.com/clases/1648-bff-2019/22228-integracion-del-inicio-de-sesion-con-redes-sociale/)

### Descripción:


En esta clase veremos cómo implementar el sistema de autenticación que nos brinda firebase para nuestra aplicación, específicamente permitir que tus usuarios se autentiquen en Firebase mediante su cuenta de Google.

## Setup

Antes de comenzar con la implementación:

  1. Asegúrate de que tengas agregado Firebase a tu proyecto.

  2. Debes habilitar el acceso con Google en la consola de Firebase

    1. Ya que tengas tu proyecto creado en Firebase, ve a la sección de Auth ![Screen Shot 2019-10-03 at 12.00.35 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-10-03%20at%2012.00.35%20PM-7f66d220-6524-4665-90ee-b6a66c456024.jpg)

    2. Una vez en Auth, ve a “Configurar el método de acceso”


![Screen Shot 2019-10-03 at 12.23.58 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-10-03%20at%2012.23.58%20PM-9caebb1d-aa25-40b9-b24c-d18e5144e950.jpg)
``` 
    1. En está sección irás a la opción de Google para poder habilitarla
    
```

![Screen Shot 2019-10-03 at 12.25.08 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-10-03%20at%2012.25.08%20PM-ca2e90b5-2152-4b69-bcaa-b333327a9e60.jpg)
``` 
    1. Habilita la opción de Google, guardas el cambio y listo!
    
```

![Screen Shot 2019-10-03 at 12.25.42 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-10-03%20at%2012.25.42%20PM-c3904734-6698-4d4e-9e75-6ed9074b07cf.jpg)

Como último paso en la consola de firebase, debemos de obtener los datos de configuración de nuestro proyecto los cuales puedes encontrar o generar en:

**Nuestro proyecto > Configuración > Tus aplicaciones:**

![Screen Shot 2019-10-03 at 12.26.20 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-10-03%20at%2012.26.20%20PM-80ce65b5-d45b-4947-8e0b-d908d0a75c56.jpg)

## Implementación

Para la parte de implementación, comenzamos instalando la dependencia necesaria para disponer de Firebase en nuestro proyecto de react:

`npm install firebase --save`

Una vez instalado vamos a proceder a crear un archivo ‘firebase.js’ en la carpeta de utils con la siguiente información:
``` 
    import firebase from 'firebase/app';
    import 'firebase/auth';
     
    const config = {
      apiKey: process.env.API_KEY,
      authDomain: process.env.AUTH_DOMAIN,
      databaseURL: process.env.DATABASE_URL,
      projectId: process.env.PROJECT_ID,
      storageBucket: process.env.STORAGE_BUCKET,
      messagingSenderId: process.env.MESSAGING_SENDER_ID,
      appId: process.env.APP_ID,
    };
     
    firebase.initializeApp(config);
    export const { auth } = firebase;
    export const provider = new firebase.auth.GoogleAuthProvider();
    
```

Y en nuestro archivo de `.env` añadimos las variables de entorno que necesitamos para nuestro proyecto:

`API_KEY= AUTH_DOMAIN= DATABASE_URL= PROJECT_ID= STORAGE_BUCKET= MESSAGING_SENDER_ID= APP_ID=`  
Esta configuración es proveída por Firebase en tu dashboard y en la configuración de tu proyecto.

## CONFIGURACION CON PLATZI VIDEO.

### Enlazar boton de Inicio de Sesión con Firebase, en archivo de nuestro proyecto ‘Login.jsx’ que encuentras en la carpeta ‘src/containers’ vamos a trabajar la siguiente lógica:

Importamos los métodos que creamos en el archivo de firebase.js que son nuestro auth y el provider.

`import { auth, provider } from '../utils/firebase';`

Una vez que importamos, vamos a crear la lógica que se encarga de iniciar sesión:

`const loginWithGoogleAccount = () => { auth().signInWithPopup(provider) .then(({ user }) => { props.history.push('/); // si el login es exitoso lo enviamos al Home de nuestra aplicación. }); }`  
Ahora que tenemos la función que se encarga de manejar el login con Google, vamos a implementarla en la sección de “Inicia sesión con Google”.

Tu código debe de quedar de la siguiente manera:
``` 
            `
              ![googleicon]({googleIcon})
              Inicia sesión con Google
            `
    
```

Con esto hemos agregado el login con Google a tu aplicación, cabe mencionar que esta lógica funciona para registrar nuevos usuarios, por lo que podrás añadir la misma lógica a tu contenedor de register.jsx. Ahora tendrás integrado el inicio de sesión con Google, al darle click, se mostrará un modal donde elegirás tu cuenta de Google, le darás permisos y podrás entrar con Google.

Ahora que tienes los datos que te provee google puedes utilizar la información para pasarla al estado de Redux y presentar la imagen y el nombre de tu usuario dentro de la aplicación.

Te invito a seguir estos mismos pasos para añadir la integración con Twitter y que tu proyecto sea mas robusto.

### Comentarios:

* **johanse7** (6) [836807](https://platzi.com/comentario/836807/) 

	Porque no se siguió la linea con la estrategia que creo Guillermo en el curso de passport implemento passport-facebook’ por ejemplo?

	* **José Abdiel Ortega Vázquez** [836807] (1)

		Es una sugerencia de hecho implementarla con la de guillermo es sencillo solo debes hacer un fetch o un post con axios desde el action que se manda llamar y colocar en tú componente para que se ejecute al hacer click en el boton de log con google.

* **ValentinGutierrez** (1) [1022300](https://platzi.com/comentario/1022300/) 

	Sinceramente me mareo un poco esto!

