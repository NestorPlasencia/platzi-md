# Getting Started

## 0010. Bienvenida

### Descripción:


### Comentarios:

* **Jose Daniel Barría Reyes** (3)

	
	Estoy emocionado de empezar este curso y mucho mas con Oscar Barajas!

* **JheysonEGalvis** (1)

	
	¿Que conocimiento previos se necesitan para tomar este curso?

## 0020. Continuous Integration (CI) y Continuous Delivery (CD)

### Descripción:


### Comentarios:

* **Miguel Ángel Muñoz Pozos** (4)
![](https://miro.medium.com/max/1400/0*TH1nBsXNDB5Njynk.PNG)

## 0030. Crear cuenta en Travis-ci.org

### Descripción:


### Links:

* [Travis CI - Test and Deploy Your Code with Confidence](https://travis-ci.org/)

* [Travis CI User Documentation](https://docs.travis-ci.com/)

### Comentarios:

* **louismanson** (2)

	
	Desde el **2018**[travis-ci.com](http://travis-ci.com) permite proyectos **open source y privados** y solo deberíamos usar el **.com** , aparte ya no usa solamente GitHub, también funcionan con [Bitbucket](https://bitbucket.org) tanto para el login como repositorio.
	
	<https://blog.travis-ci.com/2018-05-02-open-source-projects-on-travis-ci-com-with-github-apps>

* **louismanson** (2)

	
	El curso es de Travis, pero considero importante que menciones otros sistemas como [Github Actions](https://github.com/features/actions),[Google Cloud Build](https://cloud.google.com/cloud-build), [jenkins](https://jenkins.io) etc

	* **Miguel Ángel Muñoz Pozos** (2)

		
		Me gusta tu ida considero que seria un curso por cada una de las tecnologías que mencionas. ¿Tu has usado todas estas herramientas?

	* **louismanson** (2)

		
		Solo de Jenkins si hay un curso creo. Pero si es un problema que noto en cada curso que no se menciona herramientas que hacen lo mismo. Estaría bien que se mencionaran aunque sea un minuto para saber si es buena idea probar otra tecnología, ver luego cuál es mejor y tener un sope mas amplio.
		
		De las que mencione si he usado todas aparte Travis, tengo proyectos en cada uno, aunque Jenkins es el que menos entiendo por ahora.

	* **Mario E Fernandez  Serrano** (1)

		
		Wow, que Pro! genial saber de otras herramientas para la cultura DevOps, estaría genial que escribieras y nos compartieras un tutorial de algunas de las que has probado. 😃

	* **Kevin Javier Morales (Platzi)** (1)

		
		Gracias por el feedback! Lo tendremos en cuentas para los próximos cursos 😃

# Configuración

## 0040. Archivo de configuración travis.yml

### Descripción:


### Links:

* [vscode-icons - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

### Comentarios:

* **Jose Daniel Barría Reyes** (1)

	
	Codigos de la clase
	``` 
	    //inicializar el proyecto
	    mkdir travis 
	    cd travis
	    git init
	    npm init -y
	    // (opcional) touch .travis.yml
	    code .
	    
	```
	
	archivo .travis.yml
	``` 
	    # trabajamos con javascript
	    language: node_js
	    # os: osx
	    # hay mas configuraciones
	    git:
	      # 3 niveles de git
	      depth:3
	    
	    branches:
	      # branches que no queremos implementar
	      except:
	      - legacy
	      - experimental
	    
	    branches:
	      # solo las ramas que queremos
	      only:
	      - master
	      - stable
	    
	    before_install:#antes de hacerlo
	      - python
	    
	    install:
	      - yarn install
	    # - apt install curl
	    
	    script:
	      - yarn deploy
	      - yarn test
	    
	    before_script:
	      - clean
	    
	    after_script:
	      - yarn clean
	    
	    cache:
	      directories:
	        - node_modules # mantener en cache node_modules
	    
	    
	```

## 0050. Archivo de configuración travis.yml jobs y deploy

### Descripción:


### Links:

* [GitHub - gndx/platzi-store: Curso de Pruebas unitarias con Jest](https://github.com/gndx/platzi-store)

* [Travis CI User Documentation](https://docs.travis-ci.com/)

### Comentarios:

* **Jose Daniel Barría Reyes** (1)

	
	codigos de la clase. Archivo .travis.yml
	``` 
	    // ...
	    jobs:
	      include:
	        - stage: test
	          script: yarn test
	          script: yarn eslint
	        - stage: deploy
	          script: yarn deploy
	    
	    # deploy github page y heroku
	    
	    deploy:
	      provider: heroku
	      on
	        repo: danibarria/platzistore
	    
	```

# Deploy Github Pages

## 0060. Configuración de travis.yml

### Descripción:


### Links:

* [GitHub - gndx/platzi-store: Curso de Pruebas unitarias con Jest](https://github.com/gndx/platzi-store)

* [Travis CI User Documentation](https://docs.travis-ci.com/)

### Comentarios:

* **Diegoalesco95** (2)

	
	Revisando la documentación de Travis, me di cuenta que hay un error en la escritura de las configuraciones de la sección deploy debido a que se está utilizando el caracter “-” en vez de “_”, siendo la forma correcta la siguiente:
	``` 
	    deploy:
	      provider: pages
	      skip_cleanup:true
	      keep_history:true
	      github_token: $GITHUB_TOKEN  # Set in the settings page of your repository, as a secure variable
	      local_dir: dist/
	      target_branch: gh-pages
	      commit_message:"Deploy de proyecto"
	      on:
	        branch: master
	    
	```
	
	Al final Travis pasa por alto ese detalle al momento de hacer el deploy ya que hace las validacion y al parecer corrige automáticamente, sin embargo ahi les dejo el dato.
	
	Fuente: [GitHub Pages Deployment](https://docs.travis-ci.com/user/deployment/pages/)

* **Jose Daniel Barría Reyes** (1)

	
	Configuracion travis para platzi-store
	``` 
	    language: node_js
	    
	    cache:
	      directories:
	        - node_modules
	        - ~/.npm
	    
	    node_js:
	      -'12'
	    
	    git:
	      depth:3
	    
	    script:
	      # la configuracion de travis tiene yarn
	      - yarn build
	    
	    deploy:
	      provider: pages # github pages
	      skip-clean:true
	      keep-history:true
	      github-token: $GITHUB_TOKEN
	      local-dir: dist/
	      target-branch: gh-pages
	      commit_message:"deploy on project"
	      on:
	        branch: master
	    
	    # por defecto yarn hace yarn install
	    
	```

## 0070. Test & Deploy de Platzi Store

### Descripción:


### Links:

* [Configurar Git - Ayuda de GitHub](https://help.github.com/es/github/getting-started-with-github/set-up-git)

### Comentarios:

* **louismanson** (2)

	
	Mis pruebas duran ~1:30 hrs, por 2312 Test. Hay forma de designar más recursos a Travis para que haga más rápido las pruebas?

* **Emmanuel Rodríguez Ramírez** (1)

	
	Visto desde GitHub, settings (repo) > WebHooks  
	![Screen Shot 2020-03-20 at 13.13.56.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-03-20%20at%2013.13.56-e9238ea4-11a4-4a71-9f4a-ff0360f98b41.jpg)

# Integración y Notificaciones

## 0080. Integración con notificaciones de correo electrónico

### Descripción:


### Comentarios:

* **Jose Daniel Barría Reyes** (1)

	
	codigo de la clase
	``` 
	    notifications:
	      email:
	        reciepients:
	        - oscar@platzi.com
	        - oscar@arepa.dev
	        on_success: always
	        on_failure: always
	    # manda emails a esos mails cuando es exitoso y cuando falla
	    
	```

## 0090. Integración con notificaciones de Slack

### Descripción:


### Comentarios:

* **Jose Daniel Barría Reyes** (2)

	
	codigo de la clase
	``` 
	    notifications:
	      slack: workspace:token
	      # ...
	    
	```

# Deploy Heroku

## 0100. Configuración de Integración

### Descripción:


### Comentarios:

* **Miguel Ángel Muñoz Pozos** (3)

	
	[Repo platzi-store-backend ](https://github.com/gndx/platzi-store-backend)

* **Eduardo P. Rivero** (1)

	
	Hice un post explicando como hacer la integración entre netlify y travis.
	
	<https://platzi.com/tutoriales/1843-travis/5302-deployments-unicos-por-git-branch-con-netlify-y-travis/>

* **Emmanuel Rodríguez Ramírez** (1)

	
	[Heroku](https://www.heroku.com/platform)
	
	Nube PaaS (Platform As A Service), que permite el despliegue, ejecución y administración de aplicaciones escritos en múltiples lenguajes y frameworks. Entendidos como un sistema administrador de contenedor, enfocados en la experiencia “software delivery and DX”.
	
	![Screen Shot 2020-03-20 at 13.25.47.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-03-20%20at%2013.25.47-e4dd6bee-d614-4ce0-bc56-e7d8e30ddeeb.jpg)

## 0110. Configuración de travis.yml con Heroku

### Descripción:


### Comentarios:

* **Emmanuel Rodríguez Ramírez** (3)

	
	Me gustaría hacer un comentario muy reflexivo.  
	“En este punto, dejamos de ser un sólo eslabone en un proceso tan simple de desarrollo, y empezamos a formar parte de todo un proceso complicado de _software lifecycle & devops_”

* **Jose Daniel Barría Reyes** (1)

	
	codigo de la clase
	``` 
	    language: node_js
	    
	    cache:
	      directories:
	        - node_modules
	        - ~/.npm
	    
	    node_js:
	      - '12'
	    
	    git:
	      depth: 3
	    
	    script:
	      - yarn test
	    
	    notifications:
	      slack: workspace:token
	      email:
	        reciepients:
	          - oscar@platzi.com
	          - oscar@arepa.dev
	        on_success: always
	        on_failure: always
	    
	    deploy:
	      provide: heroku
	      skip-cleanup: true
	      keep-history: true
	      api_key: apiKey # desde heroku
	      app: platzi-store-backend
	      on:
	        repo: danibarria/platzi-store-backend
	    
	    
	```

## 0120. Deploy de Platzi Store Backend

### Descripción:


### Comentarios:

# Seguridad

## 0130. Instalar Travis CLI (Command Line Client)

### Descripción:


Para poder utilizar Travis CI CLI es necesario contar con Ruby en tu sistema operativo. Te dejo una serie de recursos para su instalación en los diferentes sistemas operativos:

  1. [Instalar Ruby en Wiwndows](https://www.ruby-lang.org/es/documentation/installation/#rubyinstaller)
  2. [Instalar Ruby en Ubuntu](https://www.ruby-lang.org/es/documentation/installation/#apt)
  3. [Instalar Ruby en OS X](https://www.ruby-lang.org/es/documentation/installation/#homebrew)
  4. [Otros sistemas operativos](https://www.ruby-lang.org/es/documentation/installation/)



Ahora que ya tienes instalado Ruby en tu sistema operativo vamos a proceder a instalar el cliente de línea de comandos de Travis, con el cual podemos realizar tareas específicas que nos ayuden a ser más efectivos con el uso de esta herramienta.

Para garantizar que tenemos instalado Ruby, debemos ejecutar el comando y comprobar que tenemos una versión superior a 1.9.3
``` 
    ruby -v
    
```

Ahora lo que debemos instalar es el cliente que está disponible como una gema de Ruby y debemos de ejecutar el siguiente comando:
``` 
    gem install travis
    
```

Una vez que la instalación se ha realizado debemos controlar que tenemos Travis instalado con el siguiente comando:
``` 
    travis version
    
```

Si quieres aprender más acerca del “Command Line Client” que implementa Travis CI te invito a revisar el repositorio del proyecto. [The Travis Client](https://github.com/travis-ci/travis.rb)

### Comentarios:

* **Jose Daniel Barría Reyes** (2)

	
	Muchas gracias! Lo instalare.

* **Joel Andy Rojas Valencia** (1)

	
	brew install travis

## 0140. Buenas practicas de seguridad

### Descripción:


### Links:

* [Encryption keys - Travis CI](https://docs.travis-ci.com/user/encryption-keys/)

### Comentarios:

* **Jose Daniel Barría Reyes** (2)

	
	Buenas practicas de seguridad: En este curso utilizamos información sensible que deberíamos ocultar. Para eso travis-cli nos ofrece el siguiente comando:
	``` 
	    travis encrypt tu_clave
	    
	```
	
	para encriptar tu información sensible y que solo travis pueda entender.  
	Luego de ejecutar este comando, travis genera lo siguiente
	``` 
	    secure:"..."
	    
	```
	
	luego eso lo integrarias de la siguiente manera
	``` 
	    # ejemplo con api key
	    api_key:
	    	secure:"..."
	    
	```
	
	y de esa manera aseguramos nuestras claves y/o información sensible.

* **Joel Andy Rojas Valencia** (1)

	
	Si el comando: _travis encrypt localmeetups…_ les da el siguiente error: **repository not known to<https://api.travis-ci.org/:>**
	
	Intentar con el siguiente comentario:
	``` 
	    travis encrypt localmeetups --com
	    
	```

# Travis CI Enterprise

## 0150. Travis CI Enterprise y cierre del curso

### Descripción:


### Links:

* [🚀Platzi: ‎Cursos Online Profesionales de Tecnología](https://platzi.com/clases/learning-path/escuela-js/)

* [Obtén un mes gratis en Platzi](https://platzi.com/blog/un-mes-gratis-en-platzi/)

### Comentarios:

* **Joel Andy Rojas Valencia** (1)

	
	Muy interesante el curso y el profesor va directo al grano, me encanto.  
	Lo recomendare.!!

* **louismanson** (1)

	
	Desde el **2018** **Travis-CI** busca unificar todo bajo su domino **.com** , por lo que los proyectos open source y privados se deben manejar ya en **[Travis-ci.com](https://www.travis-ci.com)** y ya no el **[travis-ci.org](https://www.travis-ci.org)** , en este ultimo se da mantenimiento y se esta migrando al **.com**
	
	_Over the next several months, we’ll be migrating all[travis-ci.org](http://travis-ci.org) repositories and customers to [travis-ci.com](http://travis-ci.com). Though this will not happen right away, you can go ahead and read more about what to expect in the [docs](https://docs.travis-ci.com/user/migrate/open-source-on-travis-ci-com/)._
	
	[Anuncio Oficial](https://blog.travis-ci.com/2018-05-02-open-source-projects-on-travis-ci-com-with-github-apps)

* **Jose Daniel Barría Reyes** (1)

	
	Genial este curso! Super recomendado

* **Alejandro Daniel Oroncoy Almeyda** (1)

	
	> :C Recién me doy cuenta:(

	* **Kevin Javier Morales (Platzi)** (1)

		
		El examen ya está publicado 😄

* **louismanson** (1)

	
	No hay examen para este curso D:<

	* **Kevin Javier Morales (Platzi)** (1)

		
		El examen ya está publicado 😃

