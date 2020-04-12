[Curso de Creación de APIs con Ruby on Rails 1440](https://platzi.com/cursos/ror)

# Introducción [3140]

## 0010. Bienvenida e introducción [15935](https://platzi.com/clases/1440-ror/15935-bienvenida-e-introduccion6969/)

### Descripción:


### Links:

* [Curso de Ruby on Rails: POO | Materiales](https://platzi.com/clases/ruby-on-rails/)

### Comentarios:

* **louismanson** (4) [72934](https://platzi.com/comentario/825625/) 
Ya no está el curso de Rails?

	* **Juan David Castro (Platzi)** [72934] (2)

		Algunos cursos se han deprecado y pronto tendremos sus actualizaciones. Pero aún puedes ver todos los contenidos de Ruby y Rails en Platzi aquí: <https://platzi.com/clases/learning-path/backend-ruby/>. 😉

* **Jtolentino** (4) [71026](https://platzi.com/comentario/788232/) 
El curso al que hace referencia, al parecer ya no esta disponible, entonces ya no se necesita el prerequisito para tomar este curso??

* **esteban-eusse-guerra** (3) [830356](https://platzi.com/comentario/830356/) 

	el curso de rails ya no esta, cual debo ver antes

	* **Ernesto Vizcaíno Alvarado** [830356] (1)

		<https://platzi.com/clases/ruby/>

* **Sebastián Pineda Duque** (2) [452059](https://platzi.com/comentario/452059/) 

	¿Cuál es el curso anterior que menciona el profesor?

	* **ricardocelis (Platzi)** [452059] (3)

		Es este: <https://platzi.com/clases/ruby-on-rails/>

* **SebastianMedinaDonoso** (1) [887512](https://platzi.com/comentario/887512/) 

	<https://platzi.com/clases/ruby-on-rails-2018/> creo que es este

* **Mark Harmsen** (1) [518206](https://platzi.com/comentario/518206/) 

	En _rails_helper.rb_ la línea 47
	``` 
	    config.before(:suite) do
	        DatabaseCleaner.strategy = :transaction
	        DatabaseCleaner.clean_with(:truncation)
	      end
	    
	      config.around(:each) do |example|
	        DatabaseCleaner.cleaning do
	          example.run
	        end
	      end
	    
	```

* **Mark Harmsen** (1) [518178](https://platzi.com/comentario/518178/) 

	Las genmas para agregar:
	
	Development y Test
	``` 
	    group :development, :testdo
	      gem 'rspec-rails', '~> 3.5'
	    end
	    
	```
	
	Solo test
	``` 
	    group :testdo
	      gem 'factory_bot_rails', '~> 4.0'
	      gem 'shoulda-matchers', '~> 3.1'
	      gem 'faker', '~> 1.9'
	      gem 'database_cleaner', '~>1.7'
	    end
	    
	```

* **Mark Harmsen** (1) [518092](https://platzi.com/comentario/518092/) 

	Para instalar un Ruby version manager. Prefiero rbenv (Ruby Enviroment). Acá el link a la documentación [https://github.com/rbenv/rbenv](url)

* **JFretel** (1) [451681](https://platzi.com/comentario/451681/) 

	A aprender! 😄

* **Victor Manuel Franco Cañon** (1) [449023](https://platzi.com/comentario/449023/) 

	Comenzamos con API’s…

* **Sebastián Pineda Duque** (1) [48201](https://platzi.com/comentario/452059/) 
¿Cuál es el curso anterior que menciona el profesor?

	* **ricardocelis (Platzi)** [48201] (3)

		Es este: <https://platzi.com/clases/ruby-on-rails/>

## 0020. Configuración [15937](https://platzi.com/clases/1440-ror/15937-configuracion/)

### Descripción:


### Comentarios:

* **Nico Melgarejo Sabelle** (2) [900507](https://platzi.com/comentario/900507/) 

	Para instalar Rails me gusta mucho esta <http://installrails.com/>

* **Jtolentino** (1) [788266](https://platzi.com/comentario/788266/) 

	Hola Iris, Depende de que OS uses (MacOS, Windows, Linux, etc).

* **Iris Castillo** (1) [769284](https://platzi.com/comentario/769284/) 

	Como instalo sqlite3???

	* **capacitacionin** [769284] (1)

		gem install sqlite3 -v 1.3.11

* **Victor Manuel Franco Cañon** (1) [449028](https://platzi.com/comentario/449028/) 

	Esta guia me fue muy util para instalar Ruby on Rails en ubuntu 18.04 <https://gorails.com/setup/ubuntu/18.04>

	* **Diego Puentes** [449028] (2)

		Saludos.  
		¿Como configurar ruby on rails para trabajar con un servidor remoto? Es decir no trabajar con el <http://localhost:3000> en ves de eso usar ip x.x.x.x:3000

* **Jean Carlos Nuñez Hernandez** (1) [446313](https://platzi.com/comentario/446313/) 

	Instalacion de rails -> gem install rails -v 5.2.1

# Proyecto [3142]

## 0030. Creación del proyecto [15938](https://platzi.com/clases/1440-ror/15938-creacion-del-proyecto0142/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (9) [449050](https://platzi.com/comentario/449050/) 

	 **APP vs API**
	
	Una aplicación de Rails regular usará las vistas de rails (erb o haml) para renderizar las páginas directamente. Es decir, procesará los datos Y los procesará en vistas, respondiendo directamente la solicitud del cliente con una página HTML.
	
	Una API de Rails solo procesará su acción y asumirá que alguien más está haciendo el trabajo de representar la vista para el cliente. Por lo tanto, se espera que una API de Rails devuelva datos en un formato apropiado, como JSON, XML o solo un fragmento de código JS para ejecutar. Es entonces el trabajo de los marcos front-end como AngularJS recibir, analizar y hacer algo con los datos (como actualizar algunos HTML, etc.)
	
	Conceptos extraídos de:
	
	* <https://stackoverflow.com/questions/31101917/what-is-the-difference-between-a-regular-rails-app-and-a-rails-api>
	
	

* **Carlos Arturo Gutierrez Gonzalez** (1) [958748](https://platzi.com/comentario/958748/) 

	tuve un problema al colocar
	``` 
	    rails server
	    
	```
	
	en la linea de codigo 75 del archivo en la ruta de mi computadora
	``` 
	    C:/Ruby24-x64/lib/ruby/gems/2.4.0/gems/bootsnap-1.1.7/lib/bootsnap/load_path_cache/store.rb:75:in `binwrite': "\xDE" `fromASCII-8BITtoUTF-8 (Encoding::UndefinedConversionError)
	    
	    
	```
	
	pero lo solucione simplemente cambiando la linea de codigo en el archivo señalado  
	de:
	``` 
	    File.binwrite(tmp, MessagePack.dump(@data), mode: exclusive_write)
	    
	```
	
	a:
	``` 
	    File.binwrite(tmp, MessagePack.dump(@data), mode: exclusive_write, encoding:Encoding::BINARY)
	    
	```
	
	Si quierene encontrar mas informacion acerca de este error el link de la pagina esta [aquí](https://github.com/Shopify/bootsnap/issues/111)

* **adrianrbp** (1) [781151](https://platzi.com/comentario/781151/) 

	nota sobre **config/application.rb** :
	
	Al iniciar rails se ejecutan 3 archivos:
	
	**1\. config/boot.rb** : Configura Bundler y carga los paths.
	
	**2.config/application.rb** : Carga las gemas de rails, y especificas del Rails.env, además de configurar la app.
	
	**3.app.config/environment.rb** : Ejecuta todos los initializers.
	
	Fuente: [The Rails Way](https://www.amazon.com/Rails-Way-Addison-Wesley-Professional-Ruby/dp/0134657675/ref=dp_ob_title_bk)

* **Diego Puentes** (1) [760509](https://platzi.com/comentario/760509/) 

	Saludos.  
	¿Como configurar ruby on rails para trabajar con un servidor remoto? Es decir no trabajar con el <http://localhost:3000>, un lugar de eso usar: la ip de mi maquina donde esta montado rails **x.x.x.x:3000** por ejemplo.

	* **adrianrbp** [760509] (2)

		para producción puedes configurar Nginx y puma

* **adrianrbp** (1) [748099](https://platzi.com/comentario/748099/) 

	corriendo en un contenedor haciendo binding del puerto 3001:
	``` 
	    rails s -b0.0.0.0 -p3001
	    
	```

* **Johan-Manuel-Buitrago-Segura** (1) [566946](https://platzi.com/comentario/566946/) 

	Instalación de gemas:
	
	group :test do  
	gem ‘factory_bot_rails’, '~> 4.0’  
	gem ‘shoulda-matchers’, '~> 3.1’  
	gem ‘faker’, '~> 1.9’  
	gem ‘database_cleaner’, '~> 1.7’  
	end

* **alejandrovelez948494** (1) [520230](https://platzi.com/comentario/520230/) 

	de donde sale esa variable de instancia llamada json?

* **Diego Ortiz** (1) [510277](https://platzi.com/comentario/510277/) 

	min 1:15 There is a short version to run all the tests:
	``` 
	    rspec
	    
	```
	
	Deben tener un significado diferente que no conozco, pero me funciona igual.

* **nahrivera7** (1) [510261](https://platzi.com/comentario/510261/) 

	En Gemfile, en el grupo de :development, :test agregar:
	``` 
	    gem'rspec-rails', '~> 3.5'
	    
	```
	
	También agregar:
	``` 
	    group :testdo
	      gem 'factory_bot_rails', '~> 4.0'
	      gem 'shoulda-matchers', '~> 3.1'
	      gem 'faker', '~> 1.9'
	      gem 'database_cleaner', '~> 1.7'
	    end
	    
	```

* **Diego Ortiz** (1) [510237](https://platzi.com/comentario/510237/) 

	Such a way to start:
	``` 
	    Puma caught this error: Error loading the 'sqlite3' Active Record adapter. Missing a gem it depends on? can't activate sqlite3 (~> 1.3.6), already activated sqlite3-1.4.0. Make sure all dependencies are added to Gemfile. (LoadError)
	    
	```

	* **nahrivera7** [510237] (3)

		Modifica en el Gemfile tu gema sqlite3:
		``` 
		    gem'sqlite3', '~> 1.3.6'
		    
		```
		
		Luego ve a la consola:
		``` 
		    $ bundle install
		    
		```
		
		Inicia el servidor:
		``` 
		    $ rails s
		    
		```
		
		Y chachan!! Funciona 😉

## 0040. Instalación de gemas necesarias [15939](https://platzi.com/clases/1440-ror/15939-instalacion-de-gemas-necesarias/)

### Descripción:


### Links:

* [RSpec: Behaviour Driven Development for Ruby](http://rspec.info/)

* [GitHub - thoughtbot/factory_bot: A library for setting up Ruby objects as test data.](https://github.com/thoughtbot/factory_bot)

* [GitHub - stympy/faker: A library for generating fake data such as names, addresses, and phone numbers.](https://github.com/stympy/faker)

* [GitHub - DatabaseCleaner/database_cleaner: Strategies for cleaning databases in Ruby.  Can be used to ensure a clean state for testing.](https://github.com/DatabaseCleaner/database_cleaner)

* [
  File: README
  
    — Documentation by YARD 0.9.16
  
](http://rspec.info/documentation/3.8/rspec-core/)

### Comentarios:

* **Victor Manuel Franco Cañon** (19) [458028](https://platzi.com/comentario/458028/) 
	
	![](https://farm8.staticflickr.com/7825/45569375355_f36d4a91a2_h.jpg)

* **Victor Manuel Franco Cañon** (4) [449055](https://platzi.com/comentario/449055/) 

	* rspec - <http://rspec.info/>
	* shoulda-matchers - <https://matchers.shoulda.oi>
	* factory bot - <https://rubygems.org/gems/factory_bot_rails>
	* faker - <https://rubygems.org/gems/faker>
	* database cleaner - <https://rubygems.org/gems/database_cleaner>
	
	

	* **Mario Vizcaino** [449055] (2)

		Te actualizo el link de <https://matchers.shoulda.io/>

	* **Victor Manuel Franco Cañon** [449055] (1)

		Gracias.

* **Lele Lester** (3) [591589](https://platzi.com/comentario/591589/) 

	important! Si estás viendo éste video, asegurate de instalar las versiones que utiliza el profesor, caso contrario (como me ocurrió) vas a tener problemas con FactoryBot!
	``` 
	    group :testdo
	      gem 'factory_bot_rails', '~> 4.0'
	      gem 'shoulda-matchers', '~> 3.1'
	      gem 'faker', '~> 1.9'
	      gem 'database_cleaner', '~> 1.7'
	    end
	    
	```

* **Manuel Ramos La Gambino** (2) [820752](https://platzi.com/comentario/820752/) 

	si llegan a tener algun problema con la gema de “rspec” durante su instalación y les aparece algo asi: “Could not find gem ‘rspec-rails (~> 4.0)’ in any of the gem sources listed in your Gemfile.” en color ROJO, no se asusten 😃 solo debe ir al gemfile y sustituir esto: gem ‘rspec-rails’, ‘~> 4.0’ por solo esto: gem ‘rspec-rails’ 😃 una vez que lo hagan solo corran el bundle install. salu2

* **Johan-Manuel-Buitrago-Segura** (2) [566953](https://platzi.com/comentario/566953/) 

	```
	    
	```
	
	Instalación de gemas:
	
	group :test do  
	gem ‘factory_bot_rails’, '~> 4.0’  
	gem ‘shoulda-matchers’, '~> 3.1’  
	gem ‘faker’, '~> 1.9’  
	gem ‘database_cleaner’, '~> 1.7’  
	end
	```
	```
	

* **Lele Lester** (1) [574038](https://platzi.com/comentario/574038/) 

	instalación de las gemas necesarias

	* **Lele Lester** [574038] (1)

		Gemfile
		``` 
		    group :development, :testdo
		      # Call 'byebug' anywhere in the code to stop execution and get a debugger console
		      gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
		      gem 'factory_bot_rails'
		      gem 'shoulda-matchers'
		      gem 'faker'
		      gem 'database_cleaner'
		    end
		    
		```

	* **Lele Lester** [574038] (1)

		luego ejecutar  
		`bundle install`  
		`rails generate rspec:install`

	* **Lele Lester** [574038] (1)

		Gemfile
		``` 
		    group :development, :testdo
		      # Call 'byebug' anywhere in the code to stop execution and get a debugger console
		      gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
		      gem 'rspec-rails'
		      gem 'factory_bot_rails'
		      gem 'shoulda-matchers'
		      gem 'faker'
		      gem 'database_cleaner'
		    end
		    
		```

	* **Lele Lester** [574038] (1)

		Gemfile
		``` 
		    group :development, :testdo
		      # Call 'byebug' anywhere in the code to stop execution and get a debugger console
		      gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
		      gem 'rspec-rails'
		    end
		    group :testdo
		      gem 'factory_bot_rails'
		      gem 'shoulda-matchers'
		      gem 'faker'
		      gem 'database_cleaner'
		    end
		    
		```

	* **Lele Lester** [574038] (2)

		luego ejecutar `bundle install && rails generate rspec:install`

* **Mark Harmsen** (1) [518187](https://platzi.com/comentario/518187/) 

	Hice un aporte y ya no lo puedo ver. ¿Necesitan aprobación?

## 0050. Configurar rspec + factorybot [15940](https://platzi.com/clases/1440-ror/15940-configurar-rspec-factorybot/)

### Descripción:


### Comentarios:

* **nahrivera7** (5) [510279](https://platzi.com/comentario/510279/) 

	Agrega en rails_helper.rb
	``` 
	    Shoulda::Matchers.configure do |config|
	      config.integrate do |with|
	        # Choose a test framework:
	        with.test_framework :rspec
	    
	        # Choose one or more libraries:
	        with.library :active_record
	        with.library :active_model
	        with.library :action_controller
	        # Or, choose all of the above:
	        with.library :rails
	      end
	    end
	    
	```

	* **Lele Lester** [510279] (1)

		En el mismo archivo, dentro de `RSpec.configure do |config|`, agregar tambien:
		``` 
		      config.before(:suite) do
		        DatabaseCleaner.strategy = :transaction
		        DatabaseCleaner.clean_with(:truncation)
		      end
		    
		      config.around(:each) do |example|
		        DatabaseCleaner.cleaning do
		          example.run
		        end
		      end
		    
		```

	* **Lele Lester** [510279] (1)

		Por último, también dentro de `RSpec.configure do |config|` agregar  
		`config.include FactoryBot::Syntax::Methods`

* **Jesús Alberto Martínez Hernández** (1) [1011845](https://platzi.com/comentario/1011845/) 

	2020
	``` 
	    group :testdo
	      gem 'factory_bot_rails', '~> 4.0'
	      gem 'shoulda', '~> 3.6.0'
	      gem 'shoulda-matchers', '~> 3.1.3'
	      gem 'rails-controller-testing', '~> 1.0.4'
	      gem 'faker', '~> 1.9'
	      gem 'database_cleaner', '~> 1.7'
	      gem 'rspec-rails', '~> 3.5'
	    end
	    
	```

* **yishatlm** (1) [762342](https://platzi.com/comentario/762342/) 

	En mi caso se presentó un error que incluye el argumento:** Invalid argument @ dir_s_mkdir -**. Buscando en internet, ésta fue la línea que me ayudó a solucionarlo:  
	**_ENV[‘TMP’] = 'C:/Windows/Temp’_** .  
	Se debe agregar la siguiente línea al final de la clase de aplicación en el archivo **_application.rb_**  
	Fuente: [https://stackoverflow.com/questions/35517997/rspec-installation-error-invalid-argument](url)

* **sandovalgus** (1) [511455](https://platzi.com/comentario/511455/) 

	Genial la explicación previa al desarrollo

* **Victor Manuel Franco Cañon** (1) [452962](https://platzi.com/comentario/452962/) 

	 **Configuración de factory_bot**
	
	Cuando se habla de la configuración de “FactoryBot” en el minuto 6:25, lo que se esta diciendo es que no hay que configurarla (explícitamente) sino que la gema que instalamos “[factory_bot_rails](https://rubygems.org/gems/factory_bot_rails)” hereda todos los metodos de [factory_bot ](https://rubygems.org/gems/factory_bot) ?

	* **anibalrojas (Platzi)** [452962] (1)

		Esa línea en la configuración es un shortcut para inicializar la biblioteca, no se puede realmente hablar de que una gema herede métodos de otra gema, la herencia está definida entre clases. Lo que debe estar sucediendo es que factory_bot_rails incluye y extiende factory_bot para dar soporte dentro del ambiente de Rails.

* **Victor Manuel Franco Cañon** (1) [48286](https://platzi.com/comentario/452962/) 
Configuración de factory_bot Cuando se habla de la configuración de “FactoryBot” en el minuto 6:25, lo que se esta dicie...

	* **anibalrojas (Platzi)** [48286] (1)

		Esa línea en la configuración es un shortcut para inicializar la biblioteca, no se puede realmente hablar de que una gema herede métodos de otra gema, la herencia está definida entre clases. Lo que debe estar sucediendo es que factory_bot_rails incluye y extiende factory_bot para dar soporte dentro del ambiente de Rails.

## 0060. Hello world (health endpoint) [15941](https://platzi.com/clases/1440-ror/15941-hello-world-health-endpoint/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (10) [453135](https://platzi.com/comentario/453135/) 

	**Buenas practicas en Ruby **
	
	Me preguntaba, si en algunos videos nos instan a implementar buenas practicas o las convenciones utilizadas por la comunidad de Ruby y Ruby on Rails, ademas de algunas gemas como [rubocop](https://rubygems.org/gems/rubocop), en las cuales nos indican que se debería utilizar ‘[single quotes](https://platzi.com/clases/1397-ruby-poo/15074-caracteristicas-del-lenguaje-operadores-conoce-tu-/)’ para situaciones donde no debamos interpolar o Ruby no deba hacer una inspeccion del codigo.
	
	**Mi pregunta es:** porque en el código que estamos escribiendo utilizamos comillas dobles para información que no debemos interpolar o Ruby no debería inspeccionar. Hay alguna convención específica para cuando escribimos tests?
	``` 
	    require "rails_helper"
	    
	    RSpec.describe "Health endpoint", type: :request do
	    
	      describe"GET /health"do
	        before { get'/health' }
	    
	        it "should return OK"do
	          payload = JSON.parse(response.body)
	          expect(payload).not_to be_empty
	          expect(payload['api']).to eq('OK')
	        end
	    
	        it "should return status code 200"do
	          expect(response).to have_http_status(200)
	        end
	      end
	    end```
	    
	```

	* **Diego Ortiz** [453135] (7)

		Tú tienes razón, si no vamos a interpolar o usar comillas sencillas en el texto, no se deben usar las comillas dobles por buenas practicas. Tal vez se sale del scope del curso, pero que bueno que lo apuntes y que la gente sepa que es mejor escribir comillas sencillas.

* **Diego Ortiz** (2) [512118](https://platzi.com/comentario/512118/) 

	Puede que para algunos no sea claro por qué usa el comando:  
	`RAILS_ENV=test rails c`  
	En vez de usar simplemente  
	`rails c`  
	Y la razón está en el gemfile, en esa consola va a usar la gema FactoryBot, que si recordamos, solo fue definida para el ambiente de **test** , al correr el `rails c` solito, abriría una consola del ambente **development**
	``` 
	    group :testdo
	      gem 'factory_bot_rails', '~> 4.0'
	      ...
	    end
	    
	```

* **Victor Manuel Franco Cañon** (2) [48298](https://platzi.com/comentario/453135/) 
**Buenas practicas en Ruby ** Me preguntaba, si en algunos videos nos instan a implementar buenas practicas o las convenciones utilizadas...

	* **Diego Ortiz** [48298] (7)

		Tú tienes razón, si no vamos a interpolar o usar comillas sencillas en el texto, no se deben usar las comillas dobles por buenas practicas. Tal vez se sale del scope del curso, pero que bueno que lo apuntes y que la gente sepa que es mejor escribir comillas sencillas.

* **Nico Melgarejo Sabelle** (1) [901024](https://platzi.com/comentario/901024/) 

	Genial rspect. cumple con ser auto-documentado 👏

* **Diego Ortiz** (1) [512056](https://platzi.com/comentario/512056/) 

	Aqui cabe anotar dos cosas:
	
	  1. Que aunque los modelos se definen en singular, las tablas deben ser creadas en plural (users y posts)
	  2. Un blog podría tener más tablas, como comentarios o etiquetas.
	
	

* **_hackvan** (1) [504388](https://platzi.com/comentario/504388/) 

	leyendo sobre buenas practicas que sugieren al momento de desarrollar APIs que cumplan el concepto de REST.
	
	Mi duda seria si ya tengo un `HealthController` y sugiriendo la convención de REST el metodo que de respuesta no quedaria mejor en un metodo `index`?
	
	health_controller.rb
	``` 
	    classHealthController < ApplicationController
	      defindex
	        render json: { api:'OK' }, status::ok
	      end
	    end
	    
	```
	
	routes.rb
	``` 
	    Rails.application.routes.draw do
	      get '/health', to 'health#index'
	    end
	    
	```
	
	¿Qué opiniones o sugerencias han tenido siguiendo estas convenciones de REST?

	* **nahrivera7** [504388] (2)

		Ojo con los dos puntos despues del “to” >
		``` 
		    Rails.application.routes.draw do
		      get'/health', to: 'health#index'
		    end
		    
		```

	* **Alexei Teófilo Mamani Coaquira** [504388] (2)

		Si quiere trabajar con recurso y siguiendo la recomendaciones de REST, es mejor colocarlo en el metodo show, en tu ruta tendrías algo como  
		resource :health, only: [:show]  
		tu controller tendria que fcambiar de nombre a HealthsController

* **_hackvan** (1) [52370](https://platzi.com/comentario/504388/) 
leyendo sobre buenas practicas que sugieren al momento de desarrollar APIs que cumplan el concepto de REST. Mi duda seria si ya tengo un ...

	* **nahrivera7** [52370] (2)

		Ojo con los dos puntos despues del “to” >
		``` 
		    Rails.application.routes.draw do
		      get'/health', to: 'health#index'
		    end
		    
		```

## 0070. Casos de uso para nuestra aplicación [15943](https://platzi.com/clases/1440-ror/15943-casos-de-uso-para-nuestra-aplicacion/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (5) [453164](https://platzi.com/comentario/453164/) 

	Me agrada mucho esta metodología de explicar que se hará antes de hacer algo!!!

	* **Mario Vizcaino** [453164] (2)

		si, se entiende mucho más fácil.

	* **Victor Manuel Franco Cañon** [453164] (1)

		Si, es como la ruta de lo que hay que hacer… se nota planeado y nada de improvisación. Me agrada mucho.

* **Luis Nabor** (3) [552466](https://platzi.com/comentario/552466/) 

	Hola al implementar el paso a paso que hay en el curso puedes notar que la documentación de git hub ha cambiado un poco pero no afecta mucho a este error:
	``` 
	    bundle exec rspec
	    
	    An error occurred while loading ./spec/requests/health_spec.rb.
	    Failure/Error:
	      Shoulda::Matchers.configure do | config |
	        config.integrate do |with|
	          with.test_framework :rspec
	      
	          with.library :active_record
	          with.library :active_model
	          with.library :action_controller
	      
	          with.library :rails
	        end
	    
	    NameError:
	      uninitialized constant Shoulda
	    # ./spec/rails_helper.rb:12:in `<top (required)>'
	    # ./spec/requests/health_spec.rb:1:in `require'
	    # ./spec/requests/health_spec.rb:1:in `<top (required)>'
	    # ------------------
	    # --- Caused by: ---
	    # NameError:
	    #   uninitialized constant Shoulda
	    #   ./spec/rails_helper.rb:12:in `<top (required)>'
	    No examples found.
	    
	    
	    Finished in0.01366seconds (files took 1.22secondstoload)
	    0 examples, 0 failures, 1 error occurred outside of examples
	    
	    
	```
	
	Lo que realmente afecta es no incluir estas tres librerias:
	``` 
	    # Add additional requires below this line. Rails isnot loaded until this point!
	    require'database_cleaner'
	    require'shoulda-matchers'
	    require'factory_bot_rails'
	    
	    
	```
	
	en el archivos /spec/rails.helper.rb lo cual no se menciona en los paso a paso del video, una vez la incluyas y si tenias el error que te relaciono arriba posiblemente al ejecutar este comando: bundle exec rspec
	
	la felicidad llegue a ti con un mensaje como este:
	``` 
	    Failures:
	    
	      1) Health Endpoint GET health should return OK
	         Failure/Error: before { get 'health'}
	         
	         URI::InvalidURIError:
	           bad URI(isnot URI?): "http://www.example.com:80health"
	         # ./spec/requests/health_spec.rb:7:in `block (3 levels) in <top (required)>'
	         # ./spec/rails_helper.rb:65:in `block (3 levels) in <top (required)>'
	         # ./spec/rails_helper.rb:64:in `block (2 levels) in <top (required)>'
	    
	      2) Health Endpoint GET health should returnstatus code 200
	         Failure/Error: before { get 'health'}
	         
	         URI::InvalidURIError:
	           bad URI(isnot URI?): "http://www.example.com:80health"
	         # ./spec/requests/health_spec.rb:7:in `block (3 levels) in <top (required)>'
	         # ./spec/rails_helper.rb:65:in `block (3 levels) in <top (required)>'
	         # ./spec/rails_helper.rb:64:in `block (2 levels) in <top (required)>'
	    
	    Finished in0.48693 seconds (files took 4.13 seconds to load)
	    2 examples, 2 failures
	    
	    Failed examples:
	    
	    rspec ./spec/requests/health_spec.rb:9 # Health Endpoint GET health should return OK
	    rspec ./spec/requests/health_spec.rb:15 # Health Endpoint GET health should returnstatus code 200
	    
	```

* **sandovalgus** (1) [514885](https://platzi.com/comentario/514885/) 

	Excelente!

## 0080. Planeando nuestro modelo entidad relación [15942](https://platzi.com/clases/1440-ror/15942-planeando-nuestro-modelo-entidad-relacion/)

### Descripción:


### Comentarios:

* **JFretel** (5) [452274](https://platzi.com/comentario/452274/) 

	Excelente manera de enseñar modelo entidad relación!

* **Victor Manuel Franco Cañon** (3) [453178](https://platzi.com/comentario/453178/) 

	Muy buena forma de explicar!!!

* **solivaresr** (1) [76780](https://platzi.com/comentario/892990/) 
Hola, en este caso que pasa con el diagrama de clases?

## 0090. Crear modelos y validaciones + tests [15945](https://platzi.com/clases/1440-ror/15945-crear-modelos-y-validaciones-tests/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (10) [453191](https://platzi.com/comentario/453191/) 

	 **Test-driven development (TDD)** Es decir, diseño orientado por las pruebas.
	
	Es una práctica de programación que consiste en escribir primero las pruebas (generalmente unitarias), después escribir el código fuente que pase la prueba satisfactoriamente y, por último, refactorizar el código escrito.
	
	Con esta práctica se consigue entre otras cosas:
	
	* Codificar de forma “natural” como lo hacemos cuando pensamos en algo, primero pensamos en “qué” queremos hacer y después pasamos al “cómo” como lo haremos
	* un código más robusto, más seguro, y mantenible
	* Mejorar el comportamiento de nuestra app al buscar código duplicado y agruparlo en funciones y utilizar la herencia o el polimorfismo
	* Escribir el código de lo que realmente necesitamos y no lo que creeremos que podríamos utilizar
	
	
	
	_Como todo tiene cosas no tan buenas, cómodas o fáciles depende del punto de vista, puedes verificarlas en el link._
	
	![](https://cdn-images-1.medium.com/max/1600/1*BKWjjdtGyKwhlagGvZ2-_A.gif)
	
	Conceptos extraídos de:
	
	* <https://www.paradigmadigital.com/dev/tdd-como-metodologia-de-diseno-de-software/>
	
	

	* **Mark Harmsen** [453191] (2)

		Gracias Victor por enriquecer este contenido!

	* **Victor Manuel Franco Cañon** [453191] (1)

		Con mucho gusto…

* **Mario Vizcaino** (2) [454339](https://platzi.com/comentario/454339/) 

	a mi me gusta agregar esta gema tambien a mis proyectos [annotate](https://github.com/ctran/annotate_models), ayuda mucho para tener actualizado los modelos.

* **Nico Melgarejo Sabelle** (1) [901441](https://platzi.com/comentario/901441/) 

	Habría puesto el content como text en vez de string

* **Nico Melgarejo Sabelle** (1) [901424](https://platzi.com/comentario/901424/) 

	Gracias por tu opinión!

* **Lele Lester** (1) [589509](https://platzi.com/comentario/589509/) 

	Creación de modelos  
	`rails g model user email:string name:string auth_token:string`  
	`rails g model post title:string content:string published:boolean user:references`
	
	Después de ejecutar los comandos:  
	En el archivo `create_posts.rb` dentro de `db > migrate` tenemos el siguiente código, donde vemos que `post` tiene referencia a `user` con `foreign_key`
	``` 
	    classCreatePosts < ActiveRecord::Migration[5.2]
	      defchange
	        create_table :postsdo |t|
	          t.string :title
	          t.string :content
	          t.boolean :published
	          t.references :user, foreign_key:true
	    
	          t.timestamps
	        end
	      end
	    end
	    
	```

	* **Lele Lester** [589509] (1)

		con `rails db:migrate` nos creará las tablas correspondientes en la DB

* **vicobits** (1) [577433](https://platzi.com/comentario/577433/) 

	Pueden mencionar alguna situación emn particular donde TDD no sea una buena aproximación?

	* **Manuel Cocoba** [577433] (1)

		He tenido problemas, particularmente cuando los casos de uso no esta bien definidos o bien que los clientes estan haciendo cambios de ultimo minuto que afectan la logica de negocio, se vuelve un poco tedioso estar invirtiendo tiempo en actualizar tests y despues lo necesario para que pase. No digo que este mal, al final del dia un test aprobado vale siempre la pena, por que te da la certeza de que todo funciona conforme lo planeado.

* **David Pozo Rojas** (1) [543146](https://platzi.com/comentario/543146/) 

	Al ejecutar el comando para generar mi modelo, en la respuesta de este, no se está generando el user_spec.rb. En mi caso solo genera:  
	invoke active_record  
	create db/migrate/20190324171556_create_users.rb  
	create app/models/user.rb  
	Cuando generé el proyecto le especifiqué --database:postgres que es con la base de datos que yo voy a trabajar no sé si ha podido influir…

## 0100. Implementación de los modelos usando TDD [15944](https://platzi.com/clases/1440-ror/15944-implementacion-de-los-modelos-usando-tdd/)

### Descripción:


### Comentarios:

* **pabloxco** (3) [515883](https://platzi.com/comentario/515883/) 

	En el 10:20 se puede usar para el campo booleano `{ Faker::Boolean.boolean }` para el campo `published`
	``` 
	    FactoryBot.define do
	      factory :post do
	        title { Faker::Lorem.sentence }
	        content { Faker::Lorem.paragraph }
	        published { Faker::Boolean.boolean }
	        user
	      end
	    end
	    
	```

* **Victor Manuel Franco Cañon** (1) [453265](https://platzi.com/comentario/453265/) 

	```
	    Finished in0.27421seconds (files took 0.87276secondstoload)
	    5 examples, 0 failures
	    
	```

	* **Diego Ortiz** [453265] (1)

		Si tarda más tiempo cargando y menos corriendolas comparado a tu resumen  
		¿Qué se podría decir de la máquina que las corre?
		``` 
		    Finished in0.26456seconds (files took 1.07secondstoload)
		    5 examples, 0 failures
		    
		```

## 0110. Listar y mostrar Post pruebas [15946](https://platzi.com/clases/1440-ror/15946-listar-y-mostrar-post-pruebas/)

### Descripción:


### Links:

* [
  File: GETTING_STARTED
  
    — Documentation for factory_bot (4.11.1)
  
](https://www.rubydoc.info/gems/factory_bot/file/GETTING_STARTED.md)

### Comentarios:

* **graphics** (4) [636641](https://platzi.com/comentario/636641/) 

	Yo creo que en el FactoryBot de post podrias haber usado:
	
	`[false, true].sample`
	
	en vez de el if que hiciste, es mas legible y menos redundante.

* **pedrobotero** (3) [799646](https://platzi.com/comentario/799646/) 

	Realmente para mi ha sido difícil seguir el curso porque no siento que haya una explicación clara de porqué se debe hacer cada cosa, si uno está empezando en este mundo hay momentos en los que se siente perdido y/o estancado en el tema.  
	Es mi opinión, tal vez solo me pase a mi.

	* **Nico Melgarejo Sabelle** [799646] (2)

		No solo a ti. Aún cuando tengo una base de Ruby y Rails, me ha costado seguirle la pista las clases porque no sé cuál es la estrategia que está pensando el profesor. En este curso ha sido más clara al usar diagramas con el iPad, pero es fácil perderse entendiendo lo que está pensando el profesor.

* **Diego Ortiz** (3) [513217](https://platzi.com/comentario/513217/) 

	¿Pero ese token que el proveedor le retorna a la SPA, también se lo tiene que hacer saber a la App no es así? De otra forma… ¿el backend cómo se va a enterar que ese token que le están enviando es valido?

	* **simon0191** [513217] (1)

		Cuando se genera un token, el proveedor (Auth0) firma lo firma con una llave privada y una llave pública. La llave privada sólamente la tiene Auth0 y debe garantizar que está bien custodiada para que podamos confiar en él y la llave pública, como su nombre lo dice, es pública y cualquiera puede verla o descargarla. Esas “llaves” son literalmente un par de strings que son generados usando unos principios matemáticos que hacen que estén “conectadas”. De esta manera el que firma puede enviar mensajes firmados y cualquier persona o servicio puede verificar que el mensaje fue firmado por Auth0 usando la llave pública.
		
		Algo así como que tu dedo es la llave privada y la foto de tu huella es la llave pública. Si tu envías una carta, pones tu huella en la carta y publícas una foto de tu huella, cualquiera podría verificar que esa carta es tuya pero nadie podría falsificar tus cartas porque nadie más tiene tu dedo para poner una huella.
		
		En el código del proyecto, en la clase JsonWebToken puedes ver que descargamos la llave pública de [simon0191.auth0.com/.well-known/jwks.json](url) para verificar el token:
		``` 
		    classJsonWebToken
		      defself.verify(token)
		        JWT.decode(token, nil,
		                   true, # Verify the signature of this token
		                   algorithm:'RS256',
		                   iss:'https://simon0191.auth0.com/',
		                   verify_iss:true,
		                   aud:'MH2k1IeuaRhWBbm6kq5wV9g1n7w7Bvfa',
		                   verify_aud:true) do |header|
		          jwks_hash[header['kid']]
		        end
		      end
		    
		      defself.jwks_hash
		        jwks_raw = Net::HTTP.get URI("https://simon0191.auth0.com/.well-known/jwks.json")
		        jwks_keys = Array(JSON.parse(jwks_raw)['keys'])
		        Hash[
		          jwks_keys
		          .map do |k|
		            [
		              k['kid'],
		              OpenSSL::X509::Certificate.new(
		                Base64.decode64(k['x5c'].first)
		              ).public_key
		            ]
		          end
		        ]
		      end
		    end
		    
		```
		
		De esta manera garantizamos que solamente vamos a recibir tokens de Auth0, puesto que si recibimos un token que no haya sido firmado por Auht0, la validación con la llave pública va a fallar.

* **Victor Manuel Franco Cañon** (3) [453388](https://platzi.com/comentario/453388/) 

	Cuando estamos en el ambiente de test, se podría utilizar el comando “reload!” en la consola de Rails, para refrescarla y evitar salir y volver a ejecutarla?

	* **Diego Ortiz** [453388] (2)

		It usually works for me in development enviroment. But it didn’t work for me here.

	* **Victor Manuel Franco Cañon** [453388] (1)

		@diegoalejojo, tks for the info.

* **William Calderón Castillo** (2) [551713](https://platzi.com/comentario/551713/) 

	Para quien instaló las gemas sin el versionamiento (like me), por alguna razón el FactoryBot de última versión al hacer FactoryBot.build(:post) no genera el USER por lo que queda el post con un user_id: nil y se mantiene en valid? FALSE.
	
	Recomiendo instalar las versiones que el profesor recomienda. O ahondar en la documentación con las versiones finales.

	* **Lele Lester** [551713] (1)

		Me acaba de pasar lo mismo. Gracias por tu aporte!

	* **Lele Lester** [551713] (1)

		```
		    gem'factory_bot_rails', '~> 4.0'
		      gem 'shoulda-matchers', '~> 3.1'
		      gem 'faker', '~> 1.9'
		      gem 'database_cleaner', '~> 1.7'
		    
		```

	* **Alexei Teófilo Mamani Coaquira** [551713] (2)

		En realidad si lo genera al ahcer .build lo que hace es hacer una instancia, mas no guardar, si tu hacer FactoryBot.build(:post).user alli esta el usuario sin ID

* **Diego Ortiz** (2) [53071](https://platzi.com/comentario/513217/) 
¿Pero ese token que el proveedor le retorna a la SPA, también se lo tiene que hacer saber a la App no es así? De otra forma… ¿el backend ...

	* **simon0191** [53071] (1)

		Cuando se genera un token, el proveedor (Auth0) firma lo firma con una llave privada y una llave pública. La llave privada sólamente la tiene Auth0 y debe garantizar que está bien custodiada para que podamos confiar en él y la llave pública, como su nombre lo dice, es pública y cualquiera puede verla o descargarla. Esas “llaves” son literalmente un par de strings que son generados usando unos principios matemáticos que hacen que estén “conectadas”. De esta manera el que firma puede enviar mensajes firmados y cualquier persona o servicio puede verificar que el mensaje fue firmado por Auth0 usando la llave pública.
		
		Algo así como que tu dedo es la llave privada y la foto de tu huella es la llave pública. Si tu envías una carta, pones tu huella en la carta y publícas una foto de tu huella, cualquiera podría verificar que esa carta es tuya pero nadie podría falsificar tus cartas porque nadie más tiene tu dedo para poner una huella.
		
		En el código del proyecto, en la clase JsonWebToken puedes ver que descargamos la llave pública de [simon0191.auth0.com/.well-known/jwks.json](url) para verificar el token:
		``` 
		    classJsonWebToken
		      defself.verify(token)
		        JWT.decode(token, nil,
		                   true, # Verify the signature of this token
		                   algorithm:'RS256',
		                   iss:'https://simon0191.auth0.com/',
		                   verify_iss:true,
		                   aud:'MH2k1IeuaRhWBbm6kq5wV9g1n7w7Bvfa',
		                   verify_aud:true) do |header|
		          jwks_hash[header['kid']]
		        end
		      end
		    
		      defself.jwks_hash
		        jwks_raw = Net::HTTP.get URI("https://simon0191.auth0.com/.well-known/jwks.json")
		        jwks_keys = Array(JSON.parse(jwks_raw)['keys'])
		        Hash[
		          jwks_keys
		          .map do |k|
		            [
		              k['kid'],
		              OpenSSL::X509::Certificate.new(
		                Base64.decode64(k['x5c'].first)
		              ).public_key
		            ]
		          end
		        ]
		      end
		    end
		    
		```
		
		De esta manera garantizamos que solamente vamos a recibir tokens de Auth0, puesto que si recibimos un token que no haya sido firmado por Auht0, la validación con la llave pública va a fallar.

* **Lele Lester** (1) [603110](https://platzi.com/comentario/603110/) 

	Cómo hizo para hacer pasar el test de la lista de posts???  
	Probe con factorybot desde la consola crear 10 posts, pero cuando vuelvo a ejecutar rspec obtengo este error
	``` 
	    Failure/Error: expect(payload.size).to eq(posts.size)
	         
	           expected: 10
	                got: 0
	    
	```

* **Jhonnatan Alexander Casas Leon** (1) [471725](https://platzi.com/comentario/471725/) 

	Entonces como haces el test con RSpec de los boolean.

	* **_hackvan** [471725] (4)

		Podemos hacerlo con el matcher `allow_value` asi:
		``` 
		    should allow_value(true, false).for(:published)
		    
		```

* **aycatalan1995** (1) [68489](https://platzi.com/comentario/741348/) 
Buenas tardes, una pregunta: la variable response de ‘response.body’ viene por defecto on rspec o es de otra gema?

	* **adrianrbp** [68489] (1)

		Hola,  
		a diferencia de node.js con express, donde se necesita “body-parser”, en Rails ( y en Django también) viene con el parser y dispatcher incluidos ó para importar desde el mismo framework, Rails utiliza: [Response](https://api.rubyonrails.org/v5.2.2/classes/ActionDispatch/Response.html) de ActionDispatch, el cuál tiene [body](https://api.rubyonrails.org/v5.2.2/classes/ActionDispatch/Response.html#method-i-body).
		
		Esto sucede porque es un “opinionated Frameworks”, que tiene una estructura pre-definida y no deberia cambiarse, seguro que si se pueden reemplazar partes, pero por defecto ya vienen con todo cargado 😃

* **Lele Lester** (1) [60266](https://platzi.com/comentario/603110/) 
Cómo hizo para hacer pasar el test de la lista de posts??? Probe con factorybot desde la consola crear 10 posts, pero cuando vuelvo a eje...

* **Jhonnatan Alexander Casas Leon** (1) [49753](https://platzi.com/comentario/471725/) 
Entonces como haces el test con RSpec de los boolean.

	* **_hackvan** [49753] (4)

		Podemos hacerlo con el matcher `allow_value` asi:
		``` 
		    should allow_value(true, false).for(:published)
		    
		```

* **Victor Manuel Franco Cañon** (1) [48328](https://platzi.com/comentario/453388/) 
Cuando estamos en el ambiente de test, se podría utilizar el comando “reload!” en la consola de Rails, para refrescarla y evitar salir y ...

	* **Victor Manuel Franco Cañon** [48328] (1)

		@diegoalejojo, tks for the info.

* **oscarperezdd58a6572a6b4a4e** (0) [919284](https://platzi.com/comentario/919284/) 

	Para evitar el problema con los posts que tienen user_id en nil en FactoryBot 5, solo se tiene que agregar `FactoryBot.use_parent_strategy = false`  
	al principio del archivo de posts.rb
	
	<https://github.com/thoughtbot/factory_bot/blob/master/GETTING_STARTED.md#associations>

## 0120. Listar y mostrar Post implementación [16038](https://platzi.com/clases/1440-ror/16038-listar-y-mostrar-post-implementacion/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (5) [453468](https://platzi.com/comentario/453468/) 

	Lo mejor de este curso es que cada error que la app esta generando, el profesor lo explica y nos muestra como solucionar cada uno hasta que ya no hay errores. Me gusta mucho la metodología del curso.
	``` 
	    Finished in0.54352seconds (files took 1.33secondstoload)
	    8 examples, 0 failures
	    
	```

	* **Diego Ortiz** [453468] (3)

		Para mi es un reflejo del profesionalisto y calidad del profesor. Me ha parecido muy buen curso. Contrasta mucho con los de la otra profe de la carrera.

	* **Victor Manuel Franco Cañon** [453468] (2)

		Bueno es mejor aprender de los buenos, por otro lado cuando solo nos dan las bases o simplemente no entendemos por falta de información, es un muy buen indicador para buscar mas conocimiento en la web y complementar lo aprendido.

* **Alexei Teófilo Mamani Coaquira** (4) [607315](https://platzi.com/comentario/607315/) 

	Una prueba muy importante tambien seria que si el post no existe pues debe retornar un 404.
	``` 
	    it"should return 404 if post not exists"do
	          get"/posts/0"
	    
	          expect(response).to have_http_status(404)
	        end
	    
	    
	```

	* **Héctor Tello** [607315] (1)

		Muy buen aporte, excelente. Gracias.

* **ernestognw** (4) [461254](https://platzi.com/comentario/461254/) 

	Respecto a la prueba para el detalle de los posts, noté que usó “to_not” en lugar de “not_to” para comprobar que el payload no esté vacío.
	
	Investigué un poco, y por lo que entiendo, ambos son iguales, pero para mantener la consistencia con la documentación de RSpec deberíamos usar “not_to”
	
	[Info extra](https://github.com/everydayrails/rails-4-1-rspec-3-0/issues/3)

## 0130. Crear y editar POST pruebas [15954](https://platzi.com/clases/1440-ror/15954-crear-y-editar-post-pruebas/)

### Descripción:


### Comentarios:

* **Mario Vizcaino** (2) [457133](https://platzi.com/comentario/457133/) 

	Donde puedo encontrar más documentación sobre ese tipo de pruebas?

	* **Victor Manuel Franco Cañon** [457133] (6)

		Espero poder ser de ayuda con lo siguiente, tome algunas preguntas como referente aunque aquí ya han respondido algunas “ej:*”:
		
		* Por dónde iniciar?
		* ¿Qué debo probar, o como utilizar la logica de programacion para saber que se debe probar?
		* ***** ¿Qué gemas o complemento debo usar?
		* Cómo implementarlas las pruebas?
		* Algún libro recomendado sobre este tema ?
		
		
		
		Dado que como tu, tengo el mismo interés en el tema, postee esta pregunta en <https://es.stackoverflow.com/questions/226220/como-hacer-pruebas-test-driven-developmet-en-ruby-on-rails>
		
		Antes que nada, este es el ciclo TDD  
		![](http://mindwaresrl.com/wp-content/uploads/2015/10/diagrama-tdd.png)
		
		Algunos link de interés:
		
		* <https://code.tutsplus.com/es/articles/rspec-testing-for-beginners-part-1--cms-26716>
		* <https://stories.devacademy.la/como-testear-tus-modelos-con-rspec-en-ruby-on-rails-1910bbdecde9>
		* <https://sg.com.mx/revista/31/desarrollando-ruby-rails>
		
		

* **Franco Correa** (1) [585554](https://platzi.com/comentario/585554/) 

	Si los datos que el usuario envía al endpoint el HTTP status code de respuesta no debería ser `unprocessable entity` sino `bad request` (400).
	
	`unprocessable entity` se usa cuando el dato que ya está en el servidor no es valido y por alguna razón no se puede procesar.

	* **Alexei Teófilo Mamani Coaquira** [585554] (1)

		Segun sé, el 400 se ocupa cuando el usuario envia mal los datos, por ejemplo parametros distintos, otros tipos de datos. el 422 se ocupa cuando estos datos que se enviaron, no puedes ser convertidor en data para el servidor se responde con esto.

	* **edesalla17** [585554] (1)

		you can check this article to see why unprocessable_entity works best in this case: <https://www.keycdn.com/support/422-unprocessable-entity>

* **Mario Vizcaino** (1) [48628](https://platzi.com/comentario/457133/) 
Donde puedo encontrar más documentación sobre ese tipo de pruebas?

	* **Victor Manuel Franco Cañon** [48628] (6)

		Espero poder ser de ayuda con lo siguiente, tome algunas preguntas como referente aunque aquí ya han respondido algunas “ej:*”:
		
		* Por dónde iniciar?
		* ¿Qué debo probar, o como utilizar la logica de programacion para saber que se debe probar?
		* ***** ¿Qué gemas o complemento debo usar?
		* Cómo implementarlas las pruebas?
		* Algún libro recomendado sobre este tema ?
		
		
		
		Dado que como tu, tengo el mismo interés en el tema, postee esta pregunta en <https://es.stackoverflow.com/questions/226220/como-hacer-pruebas-test-driven-developmet-en-ruby-on-rails>
		
		Antes que nada, este es el ciclo TDD  
		![](http://mindwaresrl.com/wp-content/uploads/2015/10/diagrama-tdd.png)
		
		Algunos link de interés:
		
		* <https://code.tutsplus.com/es/articles/rspec-testing-for-beginners-part-1--cms-26716>
		* <https://stories.devacademy.la/como-testear-tus-modelos-con-rspec-en-ruby-on-rails-1910bbdecde9>
		* <https://sg.com.mx/revista/31/desarrollando-ruby-rails>
		
		

## 0140. Crear y editar POST implementación [15959](https://platzi.com/clases/1440-ror/15959-crear-y-editar-post-implementacion/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (3) [460298](https://platzi.com/comentario/460298/) 

	Alguien sabe cual es la curva de aprendizaje de TDD en Ruby on Rails?

	* **William Calderón Castillo** [460298] (3)

		Hola, yo llevo trabajando aprox 3 meses en un proyecto para una empresa y sentí un click “eureka” como a los 2 meses y medio para estos TDD en ruby on rails. Se me dificulta aún en el pensar cual es la prueba que debo realizar, cuales se me quedan por fuera, etc etc…pero ya entiendo la finalidad, el objetivo, en lo que ayuda al proyecto.
		
		Lo importante es obligarse como sea a escribir la prueba antes que el código (aún me da piquiña) pero creeeo yo que en 6 meses alguien ya debería estar ducho.

	* **Victor Manuel Franco Cañon** [460298] (1)

		Que tal va tu curva de aprendizaje ?

* **navasg97** (1) [678662](https://platzi.com/comentario/678662/) 

	tengo este error
	
	  1. Posts PuT /posts/{id} should create a post  
	Failure/Error: expect(payload[“id”]).to eq([article.id](http://article.id))
	```     expected: 1
	         got: nil
	    
	    (compared using ==)
	    
	```
	
	
	
	
	antes no lo tenia pero al aplicar por completo la implantación ocurre

	* **Maribel Sainz** [678662] (1)

		Lo solucionaste? me pasó lo mismo

	* **aycatalan1995** [678662] (1)

		agrega tu código de la prueba para revisar mas o menos debería ser algo asi:
		``` 
		    describe'PUT /post/{id}'do 
		        let!(:article) {create(:post)}
		        
		        it 'should update a post'do 
		          req_payload = {
		            post: {
		              title: "titulo",
		              content: "content",
		              published: false,
		            }
		          }
		          # POST HTTP
		          put "/posts/#{article.id}", params: req_payload
		          payload = JSON.parse(response.body)
		          expect(payload).to_not be_empty
		          expect(payload['id']).to eq(article.id)
		          expect(response).to have_http_status(:ok)
		        end
		    
		        it 'should return error menssage on invalid post update'do 
		          req_payload = {
		            article: {
		              title: nil,
		              content: nil,
		              published: false
		            }
		          }
		          # POST HTTP
		          put "/posts/#{article.id}", params: req_payload
		          payload = JSON.parse(response.body)
		          expect(payload).to_not be_empty
		          expect(payload['error']).to_not be_empty
		          expect(response).to have_http_status(:internal_server_error)
		        end
		      end 
		    
		```

* **Luis Nabor** (1) [558337](https://platzi.com/comentario/558337/) 

	para los que estan implementando su codigo al pie de lo codificado en los videos y si tienen este error:
	``` 
	    AbstractController::ActionNotFound:
	           The action 'index' could not be found for PostController
	    
	    
	```
	
	intenten escribir estas lineas asi:
	``` 
	    rescue_from 'ActiveRecord::RecordInvalid' do |e|
	    
	```
	
	y no asi:
	``` 
	    rescue_from ActiveRecord::RecordInvalid do |e|
	    
	```

* **Maribel Sainz** (1) [66042](https://platzi.com/comentario/702118/) 
Posts PUT /posts/{id} should create a post Failure/Error: expect(payload["id"]).to eq(article.id) expected: 13 ...

* **Victor Manuel Franco Cañon** (1) [48907](https://platzi.com/comentario/460298/) 
Alguien sabe cual es la curva de aprendizaje de TDD en Ruby on Rails?

	* **William Calderón Castillo** [48907] (3)

		Hola, yo llevo trabajando aprox 3 meses en un proyecto para una empresa y sentí un click “eureka” como a los 2 meses y medio para estos TDD en ruby on rails. Se me dificulta aún en el pensar cual es la prueba que debo realizar, cuales se me quedan por fuera, etc etc…pero ya entiendo la finalidad, el objetivo, en lo que ayuda al proyecto.
		
		Lo importante es obligarse como sea a escribir la prueba antes que el código (aún me da piquiña) pero creeeo yo que en 6 meses alguien ya debería estar ducho.

## 0150. Usando ActiveModelSerializer [15952](https://platzi.com/clases/1440-ror/15952-usando-activemodelserializer/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (9) [462597](https://platzi.com/comentario/462597/) 

	 **Serializar**
	
	Serializar un objeto es convertirlo en una cadena de bytes con la idea de almacenarlo para su posterior uso o para su uso por otro programa o proceso.
	
	Conceptos extraídos de:
	
	* <https://simonecarletti.com/blog/2010/04/inside-ruby-on-rails-serializing-ruby-objects-with-json/>
	* <http://rubytutorial.wikidot.com/objetos-serializar>
	
	

## 0160. Filtrar posts - pruebas [15956](https://platzi.com/clases/1440-ror/15956-filtrar-posts-pruebas/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (5) [463825](https://platzi.com/comentario/463825/) 

	**Podría utilizarse un operador ternario en esta condicional?**
	
	Nos ahorramos unas lineas de codigo ademas de ser mucho mas legible al implementar la prueba de la siguiente forma?
	``` 
	      factory :post do
	        title { Faker::Lorem.sentence }
	        content { Faker::Lorem.paragraph }
	        published {
	          r = rand(0..1)
	          r == 0 ? false : true
	        }
	        user
	      end
	    
	```
	
	Original
	``` 
	      factory :post do
	        title { Faker::Lorem.sentence }
	        content { Faker::Lorem.paragraph }
	        published {
	          r = rand(0..1)
	          if r == 0
	            false
	          else
	            true
	          end
	        }
	        user
	      end```
	    
	```

	* **Luis Rogelio Reyes Hernández** [463825] (4)

		yo use
		``` 
		    0 == rand(0..1)
		    
		```
		
		y funciona, ya que el resultado sera un booleano

	* **Mark Harmsen** [463825] (2)

		@vifrac y @luis_reyesh98 gracias por sus comentarios mucachos!

	* **Victor Manuel Franco Cañon** [463825] (2)

		@el-mark Estamos para ayudar y aprender gracias al feedback de todos. @luis_reyesh98 Gracias por la info, interesante el ejercicio.

* **Victor Manuel Franco Cañon** (1) [49190](https://platzi.com/comentario/463825/) 
Podría utilizarse un operador ternario en esta condicional? Nos ahorramos unas lineas de codigo ademas de ser mucho mas ...

	* **Mark Harmsen** [49190] (2)

		@vifrac y @luis_reyesh98 gracias por sus comentarios mucachos!

## 0170. Filtrar posts - implementacion [15955](https://platzi.com/clases/1440-ror/15955-filtrar-posts-implementacion/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (7) [464166](https://platzi.com/comentario/464166/) 

	Navegando un poco sobre como emplear correctamente los controladores “buenas practicas” encontré esto:
	
	**Se deberán aplicar los principios de diseño orientado a objetos normales**
	
	* Si el código es realmente un conjunto de utilidades que no necesitan tener acceso a objeto de estado, consideraría ponerlo en un módulo que se llama por separado. Por ejemplo, si el código es todas las utilidades de mapeo, cree un módulo Maps, y acceda a los métodos
	
	* Si el código necesita estado y se usa o podría usarse en cada controlador, coloque el código en ApplicationController.
	
	* Si el código necesita estado y se usa en un subconjunto de todos los controladores lógicamente relacionados, cree una clase base (class MapController < ApplicationController) y coloque allí el código compartido.
	
	* Si el código necesita estado y se usa en un subconjunto de todos los controladores que no están muy relacionados, colóquelo en un módulo e inclúyalo en los controladores necesarios.  
	En el caso, cuando los métodos necesitan estado (params), la elección dependerá de la relación lógica entre los controladores que lo necesitan.
	
	* Use parciales cuando sea posible para el código repetido y, o bien el lugar en un directorio común ‘parciales’ o incluir a través de una ruta específica.  
	Mantenga un enfoque RESTful cuando sea posible (para los métodos) y si cree que está creando una gran cantidad de métodos no RESTful considere la posibilidad de extraerlos a su propio controlador.
	
	
	
	
	Conceptos extraídos de:
	
	* <https://stackoverrun.com/es/q/14775>
	* <https://picandocodigo.net/2012/apuntes-rails-controladores/>
	
	

* **Victor Manuel Franco Cañon** (1) [464154](https://platzi.com/comentario/464154/) 

	```
	    Finished in0.61036seconds (files took 1.04secondstoload)
	    13 examples, 0 failures
	    
	```

* **louismanson** (1) [83315](https://platzi.com/comentario/1024364/) 
Esta forma de buscar solo aplica si mi base de datos esta en sql?

* **adrianrbp** (1) [69512](https://platzi.com/comentario/758297/) 
como puedo hacer debugging si mi controlador no pasa por el servicio? usé byebug haciendo “p @posts” y poniendo byebug en el controller y...

	* **zdaniel_** [69512] (1)

		Cuando trabajas en rails literalmente tus archivos deben nombrarse con underscores. Lo que puede ser que tengas es un error de en el nombre de la clase o del archivo.
		
		No deberias necesitar hacer `require` ya que Rails lo hace por su propia cuenta.
		
		Usualmente este error viene cuando usas spring in desarrollo, mi consejo:
		``` 
		    spring stop
		    
		```
		
		y vuelve a ejecutar tu codigo.
		
		spring es magico en proyectos grandes, pero cuando estas seguro que tu nombre de archivo es correcto, el nombre de la clase es correcto, lo siguiente a probar seria el scope ( clases dentro de modulos) y de ahi spring

## 0180. N+1 query problem explicacion teórica [15961](https://platzi.com/clases/1440-ror/15961-n1-query-problem-explicacion-teorica/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (5) [464177](https://platzi.com/comentario/464177/) 

	 **Cómo: Detectar y resolver N+1 Problems**
	
	Este problema ocurre cuando el código necesita cargar los hijos de una relación padre-hijo (los “muchos” en el “uno a muchos”). En **Rails** , **ActiveRecord** tiene un método llamado **includes** , que garantiza que todos los datos asociados se carguen con el número mínimo de consultas.
	
	Aunque también nos servirá probar las funcionalidades de esta [gema](https://rubygems.org/gems/bullet).
	
	Conceptos extraídos de:
	
	* <https://www.sitepoint.com/silver-bullet-n1-problem/>
	
	

## 0190. N+1 query problem solución [15966](https://platzi.com/clases/1440-ror/15966-n1-query-problem-solucion/)

### Descripción:


### Comentarios:

* **Francisco Ochoa** (7) [446443](https://platzi.com/comentario/446443/) 

	Creo que la solución es agregar includes al final de la primera linea del método index así:
	``` 
	    defindex
	        @posts = Post.where(published:true).includes(:user)
	        if !params[:search].nil? && params[:search].present?
	          @posts = PostsSearchService.search(@posts, params[:search])
	        end
	        render json: @posts, status::ok
	      end```
	    
	```

	* **Victor Manuel Franco Cañon** [446443] (1)

		Porque sugieres hacerlos en la consulta a los post publicados y no donde estan siendo devueltos en formato json?

	* **_hackvan** [446443] (2)

		@vifrac gracias al [Lazy Load](https://rubyinrails.com/2014/01/08/what-is-lazy-loading-in-rails/) en Rails el resultado no se ve afectado si empleamos el `includes` en la primera linea del metodo o antes de llamarlo en el `render`.

	* **adrianrbp** [446443] (1)

		esta solución también funciona para la linea de la busqueda:
		``` 
		    @posts = PostsSearchService.search(@posts, params[:search])
		    
		```
		
		donde los resultados son 2:
		``` 
		    SELECT"users".* FROM"users"WHERE"users"."id"IN (?, ?)  [["id", 1], ["id", 2]]
		    
		```

* **Andrés Felipe Cardona** (2) [763359](https://platzi.com/comentario/763359/) 

	Porque en la prueba con N +1 se tardo solo 11ms en terminar  
	y en teoría solucionando en problema gasto 18ms cuando debió ser menos tiempo no ?

	* **Juan David Zapata Arias** [763359] (1)

		Seguramente a Simón se le pasó aclarar que esta es una solución pensando en la escalabilidad del programa, ahora mismo ni el programa ni la base de datos tienen una alta carga de archivos o datos como para que se note la diferencia en este tipo de pruebas.

* **Francisco Ochoa** (2) [446441](https://platzi.com/comentario/446441/) 

	No se vio cómo lo soluciono. creo que el que edito el video borro la parte importante de este video.

	* **ricardocelis (Platzi)** [446441] (1)

		Hola voy a pasarle el dato al equipo para que quede solucionado, gracias!

* **louismanson** (1) [1024383](https://platzi.com/comentario/1024383/) 

	Aquí otro problema ahora es el tamaño, ahorita manejamos 10 resultados, pero si fueran 35 Mil coincidencias? tendríamos que usar paginación en la búsqueda.

## 0200. Introducción a la autenticación con Tokens [15962](https://platzi.com/clases/1440-ror/15962-introduccion-a-la-autenticacion-con-tokens/)

### Descripción:


### Comentarios:

* **pabloxco** (2) [53555](https://platzi.com/comentario/518801/) 
¿Estaría mal implementado si en lugar de crear el concern secured.rb se agregara como un método privado en el applicat...

	* **simon0191** [53555] (2)

		No estaría mal implementado, tendrías el mismo resultado.
		
		Puse esa lógica en un concern porque prefiero mantener el ApplicationController pequeño, pues he visto que ha medida que una aplicación crece, más lógica compartida entre controladores es necesaria y el ApplicationController termina teniendo decenas de métodos no relacionados entre si lo cual hace que el código sea difícil de leer.
		
		😃

* **louismanson** (1) [1024395](https://platzi.com/comentario/1024395/) 

	El usar un autentificador es bueno pero no limitaría a los usuarios únicamente a usar ese servicio en espesifco? seria bueno que esa fuera una de varias formas de hacer login y usar un manejado de sesiones como [CASino](https://github.com/rbCAS/CASino)

* **pabloxco** (1) [518830](https://platzi.com/comentario/518830/) 

	Para quienes como yo quedaron con la duda sobre `rails dev:cache`. Este comando crea un archivo llamado `tmp/caching-dev.txt`, que luego es verificado sí existe por el archivo de configuración `config/environments/development.rb` de la siguiente manera:
	``` 
	    ...
	      # Enable/disable caching. By default caching is disabled.
	      # Run rails dev:cache to toggle caching.
	      if Rails.root.join('tmp', 'caching-dev.txt').exist?
	        config.action_controller.perform_caching = true
	    
	        config.cache_store = :memory_store
	        config.public_file_server.headers = {
	          'Cache-Control' => "public, max-age=#{2.days.to_i}"
	        }
	      else
	        config.action_controller.perform_caching = false
	    
	        config.cache_store = :null_store
	      end
	    ....
	    
	```
	
	Como se puede apreciar, al no existir el archivo `tmp/caching-dev.txt`, la cache estaba desactivada (`config.cache_store = :null_store`) por default.

* **pabloxco** (1) [518801](https://platzi.com/comentario/518801/) 

	¿Estaría mal implementado si en lugar de crear el concern `secured.rb` se agregara como un método privado en el `application_controller.rb`?:
	``` 
	    classApplicationController < ActionController::API
	    
	      private
	    
	        defauthenticate_user!
	          token_regex = /Bearer (\w+)/
	          headers = request.headers
	          if headers['Authorization'].present? && headers['Authorization'].match(token_regex)
	            token = headers['Authorization'].match(token_regex)[1]
	            if(Current.user = User.find_by_auth_token(token))
	              return
	            end
	          end
	          render json: {error:'Unauthorized'}, status::unauthorized
	        end
	    end
	    
	```
	
	De igual manera se agregaría en el controlador que sea necesario el `before_action :authenticate_user!, ...` logrando lo mismo. 🤔

	* **simon0191** [518801] (2)

		No estaría mal implementado, tendrías el mismo resultado.
		
		Puse esa lógica en un concern porque prefiero mantener el ApplicationController pequeño, pues he visto que ha medida que una aplicación crece, más lógica compartida entre controladores es necesaria y el ApplicationController termina teniendo decenas de métodos no relacionados entre si lo cual hace que el código sea difícil de leer.
		
		😃

* **pabloxco** (1) [518790](https://platzi.com/comentario/518790/) 

	En el minuto 7:00 cuando se usa `byebug` he encontrado que no es necesario realizar el `require 'byebug'` para su uso.

* **Victor Manuel Franco Cañon** (1) [464271](https://platzi.com/comentario/464271/) 

	Excelente explicación.

## 0210. Autenticación pruebas del endpoint de detalle (posts{id}) [15957](https://platzi.com/clases/1440-ror/15957-autenticacion-pruebas-del-endpoint-de-detalle-post/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (4) [464345](https://platzi.com/comentario/464345/) 

	Deberian desde estos cursos motivar las buenas prácticas, convenciones o guías de estilo en ruby…
	
	Segun rubocop
	
	* No deberíamos escribir lineas de codigo de mas de 80 caracteres de largo
	* Los bloques de código no deberían sobrepasar las 25 lineas
	
	
	
	Solo a mi me arrojan estas observaciones?

	* **Diego Ortiz** [464345] (3)

		Tal vez en Uber no usan rubocop como linter de estilo. Sé que algunas empresas tienen sus propios standard de estilos.  
		Pero tal vez sí valdría la pena agregar un documento en el curso hablando de ese tema (Rubocop, Reek y demás).

	* **Victor Manuel Franco Cañon** [464345] (2)

		@diegoalejojo, que interesante tu respuesta, no se me había ocurrido pensar en ello. Por otro lado seria muy bueno que estas detallitos los explicaran en algún lado, una posibilidad puede ser el documento que sugieres. Gracias por la info.

	* **simon0191** [464345] (3)

		Tienes razón @vifrac es algo que valdría mucho la pena incluir en el curso. Te interesaría hacer un PR al repositorio del proyecto para incluir rubocop?
		
		<https://github.com/simon0191/platzi-curso-rails-apis>

* **Mark Harmsen** (2) [53682](https://platzi.com/comentario/520612/) 
¿Alguien sabe por qué no utiliza el método delete?

	* **Mark Harmsen** [53682] (1)

		O sea quiero decir que dentro del CRUD que hace con posts nunca ve la funciòn de delete solo create, read y update…

* **Mark Harmsen** (1) [520612](https://platzi.com/comentario/520612/) 

	¿Alguien sabe por qué no utiliza el método delete?

	* **Mark Harmsen** [520612] (1)

		O sea quiero decir que dentro del CRUD que hace con posts nunca ve la funciòn de delete solo create, read y update…

	* **William Calderón Castillo** [520612] (1)

		No la usa porque no fue planeado usarla desde el inicio. Osea esta app no borra posts. Solo es por eso

	* **Héctor Tello** [520612] (1)

		Me imagino que es para evitar problemas a futuro, por ejemplo, a mí me lo explicaron de la siguiente manera: Tengo un producto y está asociado a proveedores o clientes, si yo después borro ese producto de la BD, causaría un problema de llaves foráneas porque algunas llaves foráneas estarían asociadas a dicho producto, y causaría problemas en la BD. Supongo que por alguna razón parecida no implementó el método delete, y por la misma razón implementó el campo ‘published’ si el post está publicado pues se va a mostrar, de lo contrario es como que no existiera porque no se va a mostrar, pero los desarrolladores sabemos que sí existe dentro de la BD.

	* **Jonatan Camilo Bonilla Malaver** [520612] (3)

		Yo no diría eso **hector-tello680** , ya que si has creado las llaves foráneas adecuadas con sus reglas para inserción, actualización y borrado no deberías tener problemas de consistencia de datos como lo mencionas (principios ACID). Si pasa lo que mencionas entonces algo no está bien construido en tu modelo de datos. En este caso tiene razón **william-ec** simplemente no se agregó, pero como en todo proyecto puedes agregar esa funcionalidad y de paso puedes probar lo de las llaves foráneas, rails te da la mano con eso para mantener la consistencia de tus datos.
		
		Saludos

	* **Héctor Tello** [520612] (1)

		Muchas gracias **jonatancbm** , investigaré al respecto.

* **_hackvan** (1) [516357](https://platzi.com/comentario/516357/) 

	`CurrentAttributes` son como variables globales dentro de la aplicación!

* **Victor Manuel Franco Cañon** (1) [49227](https://platzi.com/comentario/464345/) 
Deberian desde estos cursos motivar las buenas prácticas, convenciones o guías de estilo en ruby… Segun rubocop No deberíamos es...

	* **Victor Manuel Franco Cañon** [49227] (2)

		@diegoalejojo, que interesante tu respuesta, no se me había ocurrido pensar en ello. Por otro lado seria muy bueno que estas detallitos los explicaran en algún lado, una posibilidad puede ser el documento que sugieres. Gracias por la info.

## 0220. Autenticación generacio de auth token para el usuario [15953](https://platzi.com/clases/1440-ror/15953-autenticacion-generacio-de-auth-token-para-el-usua/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (6) [464384](https://platzi.com/comentario/464384/) 
	
	![](https://www.wikitechy.com/tutorials/oauth/img/oauth-images/oauth-tutorial.gif)

* **louismanson** (1) [1024478](https://platzi.com/comentario/1024478/) 

	cual seria la diferencia de usar User.new a User.create?

## 0230. Autenticación agregando autenticacion al controlador de Post [15958](https://platzi.com/clases/1440-ror/15958-autenticacion-agregando-autenticacion-al-controlad/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (2) [464396](https://platzi.com/comentario/464396/) 

	Las abreviaturas **regex** y **regexp** denotan expresiones regulares!

	* **pabloxco** [464396] (2)

		¬¬ Eso de comentar por comentar por ganar 2 puntos sin aportar mucho … pfff

	* **Mark Harmsen** [464396] (3)

		Jajaja @pabloxco y tu comentario hater también te hizo ganar 2 puntos sin aportar mucho jajaja

	* **Manuel Rodríguez Rodriguez Ver Rodriguez Vera** [464396] (3)

		@pabloxco, <https://platzi.com/clases/expresiones-regulares/>, aquí puedes verificar el funcionamiento de **regex, regexp**

* **reneclavijo** (0) [60480](https://platzi.com/comentario/606101/) 
¿Si se desea implementar otro tipo de tokens, por ejemplo JWT, o uno que viene desde OAuth2 Facebook, Google, y demás, se debería actuali...

## 0240. Autenticación lógica de update, delete y create del controlador de blogposts [15960](https://platzi.com/clases/1440-ror/15960-autenticacion-logica-de-update-delete-y-create-del/)

### Descripción:


### Comentarios:

* **armandocgg** (7) [455819](https://platzi.com/comentario/455819/) 

	En PostsController.rb:24 se escribió mal “ **[Current.user.id](http://Current.user.id)** ” en el cursor aparece “[Curen.user.id](http://Curen.user.id)”…

* **Victor Manuel Franco Cañon** (3) [464671](https://platzi.com/comentario/464671/) 

	 **HashWithIndifferentAccess**
	
	[Este ](http://codefol.io/posts/Deep-Rails-Understanding-HashWithIndifferentAccess-Understanding-the-Params-Hash/) es un muy buen articulo sobre “HashWithIndifferentAccess”
	
	Que la magia que hace es convertir cualquier clave en formato “símbolo” en una cadena para luego poder acceder a la informacion que estamos solicitando.
	
	Conceptos extraídos de:
	
	* <http://codefol.io/posts/Deep-Rails-Understanding-HashWithIndifferentAccess-Understanding-the-Params-Hash/>
	
	

* **Mark Harmsen** (3) [53746](https://platzi.com/comentario/521427/) 
¿El método “finb_by_auth_token” de User está definido?

	* **pabloxco** [53746] (4)

		Es parte de la “magia” de Rails. Es un denominado `dynamic finder`, y Rails lo agrega por cada campo del modelo.
		
		<https://guides.rubyonrails.org/active_record_querying.html#dynamic-finders>

* **Mark Harmsen** (2) [521427](https://platzi.com/comentario/521427/) 

	¿El método “finb_by_auth_token” de User está definido?

	* **pabloxco** [521427] (4)

		Es parte de la “magia” de Rails. Es un denominado `dynamic finder`, y Rails lo agrega por cada campo del modelo.
		
		<https://guides.rubyonrails.org/active_record_querying.html#dynamic-finders>

	* **Alexei Teófilo Mamani Coaquira** [521427] (1)

		Exacto por detrás lo que sucede es que cada clase se puede controlar si un metodo no existe, entonces justo en ese momento es donde se hacen estos metodos de acuerdo a cada atributo de cada clase.

* **Jhonnatan Alexander Casas Leon** (1) [475901](https://platzi.com/comentario/475901/) 

	me salen 4 errores y no 3 como en el video
	
	private_posts_spec.rb
	``` 
	    require "rails_helper"
	    
	    RSpec.describe "Posts with Authentication", type: :request do
	      let!(:user) { create(:user) }
	      let!(:other_user) { create(:user) }
	      let!(:user_post) { create(:post, user_id: user.id) }
	      let!(:other_user_post) { create(:post, user_id: other_user.id, published: true) }
	      let!(:other_user_post_draft) { create(:post, user_id: other_user.id, published: false) }
	      let!(:auth_headers) { { 'Authorization' => "Bearer #{user.auth.token}" } }
	      let!(:other_auth_headers) { { 'Authorization' => "Bearer #{other_user.auth.token}" } }
	    
	      describe"GET /posts/{id}"do
	        context'with valid auth'do
	          context'when requisting others author post'do
	            context"when post is public"do
	              before {get"/posts/#{other_user_post.id}", headers: auth_headers }
	    
	                context"payload"do
	                  subject { payload }
	                  it { is_expected.toinclude(:id) }
	                end
	                context"response"do
	                subject { response }
	                it { is_expected.to have_http_status(:ok) }
	                end
	            end
	            context"when post is draft"do
	              before {get"/posts/#{other_user_post_draft.id}", headers: auth_headers }
	    
	                context"payload draft"do
	                  subject { payload }
	                  it { is_expected.toinclude(:error) }
	                end
	                context"response draft"do
	                subject { response }
	                it { is_expected.to have_http_status(:not_found) }
	                end
	              end
	          end
	          context'when requisting users post'do
	            
	          end
	        end 
	      end
	      describe"POST /posts"do
	    
	      end
	      describe"PUT /posts"do
	    
	      end
	          # it "should return OK"do
	          #   get'/posts'
	          #  payload = JSON.parse(response.body)
	          #  expect(payload).to be_empty
	          #  expect(response).to have_http_status(200)
	          # end
	    
	          private
	    
	          def payload
	            JSON.parse(response.body).with_indifferent_access
	          end
	      end
	    
	```
	
	controlller
	``` 
	    classPostsController < ApplicationController
	      before_action :authenticate_user!, only: [:create, :update]
	    #general exception
	      rescue_from Exception do |e|
	        render json:  { error: e.message }, status::internal_error
	      end
	    
	    # exception handler
	    rescue_from ActiveRecord::RecordInvaliddo |e|
	      render json:  { error: e.message }, status::unprocessable_entity
	    end
	    #GET /posts
	    defindex
	      @posts = Post.where(published:true)
	      if !params[:search].nil? && params[:search].present?
	        @posts = PostsSearchService.search(@posts, params[:search])
	      end
	      #includes other module like user that is relationated with posts, this made 1 query to the db 
	      #solution n+1 query problem
	      render json: @posts.includes(:user), status::ok
	    end
	    
	    #GET /posts/{id}
	    defshow
	      @post = Post.find(params[:id])
	      if (@post.published? || (Current.user && @post.user_id == Current.user.id))
	      render json: @post, status::ok
	      else 
	        render json: { error:'Not_Found' }, status::not_found
	      end
	    end
	    
	    #POST /posts
	    defcreate
	      @post = Current.user.posts.create!(create_params)
	      render json: @post, status::created
	    end
	    
	    #PUT /posts/{id}
	    defupdate
	      @post = Current.user.posts.find(params[:id])
	      @post.update!(update_params)
	      render json: @post, status::ok
	    end
	    
	    private
	    
	    defcreate_params
	      params.require(:post).permit(:title,:content,:published) 
	    end
	    
	    defupdate_params
	      params.require(:post).permit(:title,:content,:published) 
	    end
	    
	    defauthenticate_user!
	      #Bearer 'token'
	      token_regex = /Bearer (\W+)/
	      #read HEADER de auth
	      headers = request.headers
	      #verificar que sea valido
	      if ['Authorization'].present? && headers['Authorization'].match(token_regex)
	        token = headers['Authorization'].match(token_regex)[1]
	      #debemos verificar que el user corresponda a un user
	        if (Current.user = User.find_by_auth_token(token))
	            return
	      end
	    end
	    render json: { error:'unauthorized'}, status::unauthorized
	    end
	    
	    end
	    
	```
	
	Pero no me pasan las pruebas

	* **Diego Ortiz** [475901] (1)

		Debiste poner los errores que te salen en las pruebas para encontrar la respuesta más fácil.  
		De lo que se alcanza a ver que en esos dos archivos veo:
		
		  1. Tú `let!(:auth_headers)` estás usando un `user.auth.token` cuando en verdad el auth_token es la columna, así que debe ser `user.auth_token`
		  2. La W de tu `token_regex` es mayúscula y no minúscula como la de Simon
		  3. En el primer `if` del authenticate_user tiene un `['Authorization'].present?` en vez de `headers['Authorization'].present?`
		
		

## 0250. Autenticación Finalizando pruebas de creación y actualización de blogposts [15965](https://platzi.com/clases/1440-ror/15965-autenticacion-finalizando-pruebas-de-creacion-y-ac/)

### Descripción:


### Comentarios:

* **Diego Ortiz** (3) [519982](https://platzi.com/comentario/519982/) 

	Estuve un buen rato tratando de encontrar por qué me estaba fallando una prueba con el error:
	``` 
	    Failure/Error: it { is_expected.to have_http_status(:unauthorized)}
	           expectedtheresponsetohavestatuscode :unauthorized (401) but it was :internal_server_error (500)
	    
	```
	
	Y tenía mal escrita la palabra `unauthorized` en un `status`. Eso me hizo dar cuenta que esas palabras no las elige Simon aleatoriamente sino que corresponde a un _http status code_ así que decidí buscar el listado de simbolos rails para esos status y aquí está el listado:  
	<http://billpatrianakos.me/blog/2013/10/13/list-of-rails-status-code-symbols/>

	* **Mark Harmsen** [519982] (1)

		Gracias Diego!

	* **SrAuto2** [519982] (1)

		Gracias my dude!

* **Victor Manuel Franco Cañon** (2) [466100](https://platzi.com/comentario/466100/) 

	```
	    Finished in0.70052seconds (files took 0.95774secondstoload)
	    22 examples, 0 failures
	    
	```

* **Luis Nabor** (2) [58237](https://platzi.com/comentario/574569/) 
Hola les comparto un par de modificaciones por si a alguien le pasa, el inconveniente era que no le llegaban las cabeceras definidas y en...

	* **anibalrojas (Platzi)** [58237] (1)

		Extrano, no tiene sentido que guardar los headers en una variable de instancia en el controlador corrigiera el error, porque en el código de autenticaded_user! no la puedes referenciar. Lo más seguro es que haya sido alguna otra cosa.

* **Luis Nabor** (1) [574569](https://platzi.com/comentario/574569/) 

	Hola les comparto un par de modificaciones por si a alguien le pasa, el inconveniente era que no le llegaban las cabeceras definidas y enviadas desde las pruebas a mi controlador.
	
	Lo que me toco hacer fue lo siguiente:
	
	En el controlador definir este metodo:
	``` 
	    definitialize(headers = {})
	          @headers = headers
	        end
	    
	```
	
	eso al parecer lo que hizo fue permitir sobre escribir o hacer set al header del request.
	
	Lo otro fue en el archivo secured.rb
	
	dejar la funcion de esta manera:
	``` 
	    moduleSecured
	      defauthenticate_user!
	        #Bearer xxxxxxx
	        token_regex = /Bearer (\w+)/
	        #leer HEADER de Auth
	        headers=request.headers
	        #verificar que sea valido
	        if headers['HTTP_AUTHORIZATION'].present? && headers['HTTP_AUTHORIZATION'].match(token_regex)
	          token=headers['HTTP_AUTHORIZATION'].match(token_regex)[1]
	          #debemos verificar que el token corresponda a un user
	          if (Current.user=User.find_by_user_reset_password_token(token))
	                return
	          end
	        end
	        render json: {error:'Unauthorized'}, status::unauthorized
	      end
	    end
	    
	    
	```
	
	Quien sabe la causa científica de esto y el porque la codificación del curso no me funciono?
	
	Gracias.

	* **anibalrojas (Platzi)** [574569] (1)

		Extrano, no tiene sentido que guardar los headers en una variable de instancia en el controlador corrigiera el error, porque en el código de autenticaded_user! no la puedes referenciar. Lo más seguro es que haya sido alguna otra cosa.

## 0260. Probando el API con Postman [15964](https://platzi.com/clases/1440-ror/15964-probando-el-api-con-postman/)

### Descripción:


### Links:

* [jq](https://stedolan.github.io/jq/)

* [platziblogapi.postman_collection.json - Google Drive](https://drive.google.com/file/d/1fScpYqCLyNhn0Z0FtvXCIuE4kopIk_3v/view)

* [Postman | API Development Environment](https://www.getpostman.com/)

### Comentarios:

* **Mark Harmsen** (2) [521661](https://platzi.com/comentario/521661/) 

	Les dejo el script de FactoryBot para poblar la base de datos, me lo van a agrader para el minuto 3:50 que se tapa la linea de comando con la barra de herramientas del video.
	``` 
	    posts1 = FactoryBot.create_list(:post, 5, user: user_1)
	    
	```

* **omarps** (1) [1041248](https://platzi.com/comentario/1041248/) 

	Usar el `_` para el resultado de la ultima instrucción. TIL

* **Jhonnatan Alexander Casas Leon** (1) [477018](https://platzi.com/comentario/477018/) 

	me sale esto
	``` 
	    bash:jq: command not found
	      % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
	                                     Dload  Upload   Total   Spent    Left  Speed
	    100120120012310 --:--:-- --:--:-- --:--:--1333
	    (23) Failed writing body
	    
	```
	
	al ejecutar jq .

	* **Mark Harmsen** [477018] (2)

		@ casasleonj Es que lo tienes que descargar [https://stedolan.github.io/jq/](url)

* **Victor Manuel Franco Cañon** (1) [466121](https://platzi.com/comentario/466121/) 

	**JQ: ** es un lenguaje funcional de muy alto nivel con soporte para backtracking y gestión de flujos de datos JSON.
	
	* <https://stedolan.github.io/jq/>
	
	

* **mariiglesia** (1) [458111](https://platzi.com/comentario/458111/) 

	Cómo se puede subir imágenes utilizando la API con Rails? Por ejemplo, subir una imagen de cada Post del Blog.

	* **Mario Vizcaino** [458111] (2)

		Desde el js deberias mandarlo como formdata, aqui te dejo un post donde explican un poco eso: [uploading-files-ajax](https://blog.teamtreehouse.com/uploading-files-ajax)

	* **joranboc** [458111] (4)

		Desdel Rails se puede usando gemas como Paperclip como enseñan en este [enlace](https://www.pluralsight.com/guides/handling-file-upload-using-ruby-on-rails-5-api) o utlizando ActiveStorage el cual ya viene integrado con rails como explican [aqui](https://api.rubyonrails.org/files/activestorage/README_md.html)

	* **Raul Palacios** [458111] (3)

		Lo mejor seria almacenarlo en algún servicio de terceros tales como firebase para que tu server no sirva tanto tu app y aparte archivos.

* **mariiglesia** (1) [48715](https://platzi.com/comentario/458111/) 
Cómo se puede subir imágenes utilizando la API con Rails? Por ejemplo, subir una imagen de cada Post del Blog.

	* **Mario Vizcaino** [48715] (2)

		Desde el js deberias mandarlo como formdata, aqui te dejo un post donde explican un poco eso: [uploading-files-ajax](https://blog.teamtreehouse.com/uploading-files-ajax)

## 0270. Explicación de Caching [15963](https://platzi.com/clases/1440-ror/15963-explicacion-de-caching/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (5) [466474](https://platzi.com/comentario/466474/) 

	 **La chache en Ruby on Rails**
	
	En informática, una caché es un componente de hardware o software que almacena datos para que las solicitudes futuras de esos datos se puedan atender con mayor rapidez.
	
	Hay dos argumentos principales para utilizar el almacenamiento en caché:
	
	* La aplicación se vuelve más rápida para el usuario. Una página web más rápida.  
	ayuda a tener usuarios más felices, lo que resulta en una mejor tasa de conversión.
	* Necesita menos hardware para el servidor web porque necesita menos  
	Recursos de CPU y RAM para procesar las consultas.
	
	
	
	Algunos métodos de almacenamiento en caché:
	
	* Almacenamiento en caché de HTTP: Este es el martillo de los métodos de almacenamiento en caché y El arma de máximo rendimiento.
	* Almacenamiento en caché de páginas: este es el destornillador entre los métodos de almacenamiento en caché, puede sacar mucho rendimiento del sistema, pero no es tan bueno como almacenamiento en caché HTTP.
	* Fragmento de caché: esta es la pinza entre los métodos de caché, Pero no lo subestimes!
	
	
	
	Conceptos extraídos de
	
	* <https://medium.com/rubyinside/https-medium-com-wintermeyer-caching-in-ruby-on-rails-5-2-d72e1ddf848c>
	
	

* **yively** (3) [606112](https://platzi.com/comentario/606112/) 

	¿Es más eficiente utilizar $redis como DB en caché o usar los sessions en rails?

## 0280. Usando Cache para acelerar las búsquedas de posts [15949](https://platzi.com/clases/1440-ror/15949-usando-cache-para-acelerar-las-busquedas-de-posts/)

### Descripción:


### Links:

* [Caching with Rails: An Overview â?? Ruby on Rails Guides](https://guides.rubyonrails.org/caching_with_rails.html#activesupport-cache-memorystore)

### Comentarios:

* **Francisco Ochoa** (5) [446784](https://platzi.com/comentario/446784/) 

	Esta muy bueno pero no se por qué no me funciono. es decir nunca quedo en el cache la primera consulta.
	``` 
	    classPostsSearchService
	      defself.search(curr_post, query)
	        # Agregar cache para optimizar
	        posts_ids = Rails.cache.fetch("posts_search/#{query}", expires_in:1.hours) do 
	          curr_post.where("title like '%#{query}%'").map(&:id)
	        end
	    
	        curr_post.where(id: posts_ids)
	      end
	    end```
	    
	```

	* **ricardocelis (Platzi)** [446784] (1)

		Hola Pancho! ya le pase la duda al profe, cualquiercosa te aviso

	* **ricardocelis (Platzi)** [446784] (1)

		digo, cualquier otra duda estamos pendientes!

	* **simon0191** [446784] (6)

		Hola Pancho! Cómo estás haciendo la prueba?  
		Tal vez te falte activar el cache. En ambiente de desarrollo el cache está desactivado por defecto. Se activa y desactiva usando el comando `rails dev:cache`. Prueba y me dices si eso te funciona.

	* **Mark Harmsen** [446784] (1)

		A mi tampoco me funcionó, inlcuso usando “rails dev:cache”
		``` 
		    irb(main):001:0> PostsSearchService.search(Post.all, "lorem")
		      Post Load (1.8ms)  SELECT "posts".* FROM "posts" WHERE (title like '%lorem%')
		      Post Load (0.4ms)  SELECT  "posts".* FROM "posts" WHERE "posts"."id" = ? LIMIT ?  [["id", 4], ["LIMIT", 11]]
		    => #<ActiveRecord::Relation [#<Post id: 4, title: "Doloremque quia amet consequuntur.", content: "Ratione aperiam atque. Sed eaque et. Voluptas reru...", published: false, user_id: 1, created_at: "2019-02-26 18:03:24", updated_at: "2019-02-26 18:03:24">]>
		    irb(main):002:0> PostsSearchService.search(Post.all, "lorem")
		      Post Load (0.3ms)  SELECT "posts".* FROM "posts" WHERE (title like '%lorem%')
		      Post Load (0.1ms)  SELECT  "posts".* FROM "posts" WHERE "posts"."id" = ? LIMIT ?  [["id", 4], ["LIMIT", 11]]
		    => #<ActiveRecord::Relation [#<Post id: 4, title: "Doloremque quia amet consequuntur.", content: "Ratione aperiam atque. Sed eaque et. Voluptas reru...", published: false, user_id: 1, created_at: "2019-02-26 18:03:24", updated_at: "2019-02-26 18:03:24">]>
		    irb(main):003:0> PostsSearchService.search(Post.all, "lorem")
		    
		```

	* **William Calderón Castillo** [446784] (2)

		config.action_controller.perform_caching = true
		
		en el archivo /config/environments/development.rb

	* **jcorvera** [446784] (1)

		Hola,  
		Para que te funcione solo debes reiniciar el servidor de ruby on rails.  
		Es decir parar el comando ****rails s**** y volverlo a ejcutar.

	* **Josue Farfan Lazo** [446784] (1)

		Hola , para que te funcione debes darle permisos, en mi caso ejecute **_sudo rails c_** , porque tampoco me funcionaba solo “rails dev:cache”

* **William Calderón Castillo** (2) [552549](https://platzi.com/comentario/552549/) 

	Para quienes no les funcione solo deben poner TRUE en
	
	config.action_controller.perform_caching = true
	
	en el archivo /config/environments/development.rb

* **Victor Manuel Franco Cañon** (2) [466618](https://platzi.com/comentario/466618/) 

	 **No guarda la cache de la primera consulta?**
	
	Me esta pasando lo mismo que a @panchope8a, dado que no he podido solucionarlo, cree una pregunta en stackoverflow por si a alguien mas le pasa el mismo problema.
	
	* <https://es.stackoverflow.com/questions/227326/como-verificar-si-ruby-on-rails-tiene-activado-el-caching>
	
	

	* **anibalrojas (Platzi)** [466618] (1)

		Se crea el archivo caching-dev.txt en el directorio tmp/?

* **solivaresr** (1) [771672](https://platzi.com/comentario/771672/) 

	si alguien mas tiene algún problema con que Rails no reconoce las clases en carpetas creadas, como services por ejemplo, esto se soluciona agregando config.autoload_paths << “#{Rails.root}/app/services” en config/application.rb

* **Victor Manuel Franco Cañon** (1) [49380](https://platzi.com/comentario/466618/) 
No guarda la cache de la primera consulta? Me esta pasando lo mismo que a @panchope8a, dado que no he podido solucionarl...

	* **anibalrojas (Platzi)** [49380] (1)

		Se crea el archivo caching-dev.txt en el directorio tmp/?

## 0290. Background jobs y ActiveJob  (explicación teórica) [15950](https://platzi.com/clases/1440-ror/15950-background-jobs-y-activejob-explicacion-teorica/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (4) [466646](https://platzi.com/comentario/466646/) 

	Encontre una serie de artículos interesantes sobre Background jobs, por si a alguien le interesa
	
	* [https://gorails.com/episodes/tagged/Background Jobs](https://gorails.com/episodes/tagged/Background%20Jobs)
	
	

## 0300. Generar Reporte para procesar con ActiveJob [15948](https://platzi.com/clases/1440-ror/15948-generar-reporte-para-procesar-con-activejob/)

### Descripción:


### Comentarios:

* **sandovalgus** (4) [515999](https://platzi.com/comentario/515999/) 

	Excelente curso y excelente profesor

	* **henrytabimagiraldo** [515999] (3)

		Completamente de acuerdo

* **Johan-Manuel-Buitrago-Segura** (3) [590781](https://platzi.com/comentario/590781/) 

	Que gran programador es el teacher

## 0310. Enviar Reporte usando ActionMailer [15951](https://platzi.com/clases/1440-ror/15951-enviar-reporte-usando-actionmailer/)

### Descripción:


### Comentarios:

* **Victor Manuel Franco Cañon** (2) [467401](https://platzi.com/comentario/467401/) 

	Muy buena clase…

* **reneclavijo** (1) [60487](https://platzi.com/comentario/606212/) 
¿Si estoy dentro de un Job, enviar un correo con deliver_later sería redundante? ¿es una mala práctica?

## 0320. Autenticacion con auth0 y JWT [16662](https://platzi.com/clases/1440-ror/16662-autenticacion-con-auth0-y-jwt/)

### Descripción:


## JWT

JWT o Json Web Token es un estándar definido por la el IETF (Internet Engineering Task Force) para transmitir digitalmente información relacionada a autenticación y autorización entre dos partes usando un token (que es simplemente un string) resultado de codificar un objeto JSON con la información que se desea transmitir. Según el estándar, este token fue pensado para transmitir “poca” información y adicionalmente para ser compatible con URLs lo que quiere decir que un JWT puede ser incluido en una petición HTTP o en un link. Esto facilita por ejemplo enviar links que dan acceso a un recurso.

Un JWT se ve así:

![Captura de pantalla 2019-01-09 a la\(s\) 12.33.21.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2012.33.21-4a779d1e-a78f-489b-92f5-7d803838f092.jpg)

<https://jwt.io/#debugger-io?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJ1c2VyMSIsIm5hbWUiOiJQZXBlIFBlcmV6IiwiZW1haWwiOiJwZXBlcGVyZXpAbWFpbGluYXRvci5jb20iLCJhZG1pbiI6dHJ1ZX0.4rkTevJa1WW5OE-JXD8RITsia4XC5jn_6V1ZjAfbrYU>

Un JWT está dividido en 3 partes separadas por un punto:

* Header (Encabezado): `eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9`
* Payload (Contenido): `eyJzdWIiOiJ1c2VyMSIsIm5hbWUiOiJQZXBlIFBlcmV6IiwiZW1haWwiOiJwZXBlcGVyZXpAbWFpbGluYXRvci5jb20iLCJhZG1pbiI6dHJ1ZX0`
* Signature (Firma): `4rkTevJa1WW5OE-JXD8RITsia4XC5jn_6V1ZjAfbrYU`



El Header incluye información sobre cómo está construido el token. En el ejemplo anterior, el header dice “`alg`”: “`HS256`” haciendo referencia al algoritmo que se utiliza para generar la firma o signature.

El Payload incluye la información que se quiere transmitir. En el ejemplo se ve que se hace referencia a un usuario, su nombre, su email y su rol como admin.

Finalmente, la firma o signature, es la parte que se utiliza para verificar que la información contenida en el payload y en el header no ha sido modificada.

Los 2 tipos de token JWT más comunes son:

* tokens firmados pero no encriptados.
* tokens firmados y encriptados.



Ambos tipos proveen garantías diferentes. Por un lado, el contenido de los tokens firmados puede ser decodificado por cualquiera, pues no está encriptado. Sin embargo, al contener una firma, esta firma se utiliza por la parte que recibe el token para verificar que el contenido no ha sido modificado. Por otro lado, los token que están encriptados, no pueden ser decodificados a menos de que la parte que reciba el token tenga la llave para poder desencriptarlo.

## Auth0 y [jwt.io](http://jwt.io)

Auth0 es una empresa que provee una plataforma de autenticación y autorización para cualquier tipo de aplicación. Auth0 ha asumido JWT como el método principal para transmitir información de autenticación y autorización y han creado el sitio [jwt.io](http://jwt.io) en donde podemos encontrar documentación sobre librerías en diferentes lenguajes para utilizar este estándar y adicionalmente se puede encontrar una herramienta para hacer debug de tokens. Por ejemplo, podemos hacer debug del token del ejemplo anterior usando la URL <https://jwt.io/#debugger-io?token=>

Por ejemplo:

<https://jwt.io/#debugger-io?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJ1c2VyMSIsIm5hbWUiOiJQZXBlIFBlcmV6IiwiZW1haWwiOiJwZXBlcGVyZXpAbWFpbGluYXRvci5jb20iLCJhZG1pbiI6dHJ1ZX0.4rkTevJa1WW5OE-JXD8RITsia4XC5jn_6V1ZjAfbrYU>

Ahí vamos a poder ver el contenido del token e inclusive crear un token desde cero pues el editor que nos aparece es interactivo y podemos editar su contenido.

![Captura de pantalla 2019-01-09 a la\(s\) 12.39.57.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2012.39.57-245a5e4e-e464-4f92-a184-2f90d7be0fdb.jpg)

En un principio, vas a ver un mensaje diciendo que la firma no es válida. Esto sucede porque el token de ejemplo usa una firma que para ser verificada necesita de un secret. El secret debe ser conocido por la parte que genera el token para así generar la firma y por la parte que recibe el token para verificar la firma. Puedes pensar en la firma como si fuera un sello de una entidad oficial de gobierno. El sello solamente lo tiene la entidad oficial y así garantiza que los documentos que emita son oficiales. La parte que recibe el token, sabe cómo verificar la firma pues conoce cómo se debe ver el sello de esta entidad oficial.

En este caso, el secret es “platzi”. Una vez lo coloques en donde dice “your-256-bit-secret”, el sitio va a verificar que el token fue firmado con ese secret y va a desaparecer el mensaje de firma inválida.

![Captura de pantalla 2019-01-09 a la\(s\) 12.41.27.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2012.41.27-0ce6e707-bae7-4a18-a221-b0fc5134b66d.jpg)

## Configurar Auth0 para autenticación con Github

  1. Abre una cuenta gratuita en [auth0.com](http://auth0.com)

![Captura de pantalla 2019-01-09 a la\(s\) 12.42.27.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2012.42.27-0f346886-9533-498f-8532-9f49a2dbdea3.jpg)

Te sugiero poner que es una cuenta personal, que eres desarrollador y que simplemente estás “playing around”.

  2. Crear una aplicación:



Ve al dashboard en <https://manage.auth0.com/#/applications>, haz click en “New Application” y selecciona la opción “Single Page Web App”. Llama la aplicación PlatziBlog (o como quieras.)

![Captura de pantalla 2019-01-09 a la\(s\) 12.43.28.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2012.43.28-adb039b3-f671-401e-8dbc-f0ed8ac74e33.jpg)

En nuestro caso no estamos implementando el frontend de nuestra aplicación así que puedes omitir el siguiente paso en el que te piden seleccionar un framework de Javascript.

![Captura de pantalla 2019-01-09 a la\(s\) 12.45.15.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2012.45.15-278f5275-d56c-4d04-863c-ec0a173341a2.jpg)

  3. Ve a la pestaña “Settings” y copia el “Client ID” que vamos a utilizar más adelante. Luego, en el campo “Allowed Callback URLs” agrega <http://localhost:3000> y <https://jwt.io> separados por coma. Asegúrate de incluir http y https respectivamente y de guardar los cambios.

  4. Activar integración con Github:




Ve a <https://manage.auth0.com/#/connections/social>. Allí, encuentras las alternativas para integrarte con proveedores de autenticación. Para este proyecto vamos a usar Github así que selecciona la opción Github.

![Captura de pantalla 2019-01-09 a la\(s\) 12.46.37.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2012.46.37-ea91b2f2-17d2-4e4f-9948-3bb5be7f1856.jpg)

Para hacer pruebas no es necesario que crees un client ID y un client secret. Por el momento puedes dejarlos en blanco y Auth0 va a utilizar su propio client ID y client secret de pruebas. Asegúrate de seleccionar “email address” y “read:user” para que podamos usar esta integración para poder obtener el email y el nombre del usuario.

![Captura de pantalla 2019-01-09 a la\(s\) 12.47.19.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2012.47.19-08511b3c-83d6-4079-8856-41f3d9e81933.jpg)

En la misma pantalla ve a la pestaña “Applications” y activa PlatziBlog

![Captura de pantalla 2019-01-09 a la\(s\) 13.15.46.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2013.15.46-678d1ac3-034c-47cc-a15c-feed9716c2d8.jpg)

Hasta este punto tienes configurada una aplicación the Auth0 que te permite hacer login con Github. Ahora debemos hacer la integración en la aplicación para poder obtener un JWT.

## Crear pantalla de login para obtener JWT

<https://github.com/simon0191/platzi-curso-rails-apis/commit/5bcb7c9438ce4784d402f40bc7455a263d67833d>

  1. Crea un controlador llamado AuthController con el siguiente contenido:



**app/controllers/auth_controller.rb**
``` 
    class AuthController < ActionController::Base
     def login
     end
    end
    
```

  2. Crea una vista para el login:



**app/views/auth/login.html.erb**
``` 
    <html>
    <head>
     <title>Platzi Blog - APItitle>
    head>
    <body>
     
     
     <script src="https://cdn.auth0.com/js/auth0/9.5.1/auth0.min.js">script>
     <script>
       // Cuando la ventana carge ejecuta la funcion
       window.addEventListener('load', function() {
        
         // Inicializar integracion con auth0
         var webAuth = new auth0.WebAuth({
           // Apunta a tu dominio de auth0
           domain: 'pepeplatzi.auth0.com',
           // Usa el client id que encuentras en la configuracion de tu aplicacion en Auth0
           clientID: '< TU CLIENT ID DE TU APP DE AUTH0>',
           // Con esto especificamos la clase de token que queremos
           // token para recibir un JWT y id_token para que se incluya informacion del usuario
           responseType: 'token id_token',
           // Con esto especificamos la informacion que deseamos incluir en el token. Para nuestro caso
           // email y profile para poder obtener el nombre
           scope: 'openid profile email',
           // Esta es la URL a la que Auth0 va a redirigir despues de hacer login. Normalmente esto
           // seria una URL al single page application de nuestra aplicacion. En nuestro caso vamos
           // a usar jwt.io para ver el token y asi poder copiar y pegarlo en postman para poder
           // probar el API.
           redirectUri: 'https://jwt.io'
         });
    
         // Con esto se redireciona a la pagina de autenticacion de Auth0.
         // En este caso estamos redirecionando inmediatamente. Normalmente, esto se ejcutaria despues
         // de que el usuario haga click en un boton de login.
         webAuth.authorize();
       });
     script>
    body>
    html>
    
```

  3. Finalmente agrega la ruta a routes.rb

![Captura de pantalla 2019-01-09 a la\(s\) 13.38.59.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2013.38.59-13aeace4-1466-4cf8-9b79-bce647b50062.jpg)

  4. Para probar la integración inicia el servidor de rails con rails s y ve a localhost:3000/login. Esto te va a redirigir a la pantalla de login de Auth0 que se debe ver parecido a esto:

![Captura de pantalla 2019-01-09 a la\(s\) 13.39.43.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2013.39.43-394bb782-ab4a-43c0-bc96-c84cfb3d0101.jpg)

Haz login con tu cuenta de GitHub y Auth0 te debe redirigir a [jwt.io](http://jwt.io) tal como lo configuraste en donde vas a ver tu JWT que debe ser parecido a esto:

![Captura de pantalla 2019-01-09 a la\(s\) 13.41.05.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2013.41.05-c0913196-910c-4ae1-bf4f-dfc7886eaa09.jpg)

## Validar JWT y guardar usuario en caso de no existir

Ahora que podemos generar un JWT con Auth0 debemos validarlo en el backend del API

<https://github.com/simon0191/platzi-curso-rails-apis/commit/f6aa00aecb7c4b5ec423d970531cb5e155909d77>

* Incluye la gema jwt en el Gemfile y ejecuta bundle install
* Crea el archivo lib/json_web_token.rb



**app/lib/json_web_token.rb**
``` 
    require 'net/http'
    require 'uri'
    
    class JsonWebToken
     # Metodo que va a verificar el token que le pasemos y en caso de ser valido va a retornar el
     # contenido del mismo. En caso de ser invalido va a aroojar una excepcion.
     def self.verify(token)
       JWT.decode(token, nil,
                  # Muy importante! Verify the signature of this token
                  true,
                  # El algortimo usado para la firma. RS256 usa una llave privada para generar la firma
                  # Esta llave privada esta custodiada por Auth0 asi que no debemos preocuparnos por esto.
                  # Para validar la firma se utiliza una llave publica que es literalmente publica y se
                  # puede encontrar en el caso de este ejemplo en https://pepeplatzi.auth0.com/.well-known/jwks.json.
                  # Para ver la llave publica de tu dominio Auth0 debes reemplazar "pepeplatzi" con tu
                  # usuario de Auth0. Cualquiera puede ver esta llave asi que es seguro publicarla y compartirla.
                  # El objetivo es permitirle a otras partes verificar firmas generadas por tu aplicacion.
                  algorithm: 'RS256',
                  # Quien emite este token. Usa tu dominio de Auth0
                  iss: "https://pepeplatzi.auth0.com/",
                  # Verificar que el token fue emitido por lo que pusimos en "iss"
                  verify_iss: true,
                  # Para quien fue emitido este token. Aqui debes colocar tu Client ID de Auth0
                  aud: "",
                  # Verificar que el token fue emitido para lo que pusimos en "aud"
                  verify_aud: true) do |header|
         # Dentro de este bloque se especifica como obtener la llave publica para verificar la firma
         # de este token. En este caso, delegamos esa tarea al metodo jwks_hash
         jwks_hash[header['kid']]
       end
     end
    
     def self.jwks_hash
       # Obtenemos la llave publica del dominio de Auth0
       jwks_raw = Net::HTTP.get URI("https://pepeplatzi.auth0.com/.well-known/jwks.json")
       # Decodificamos la llave publica y la retornamos
       jwks_keys = Array(JSON.parse(jwks_raw)['keys'])
       Hash[
         jwks_keys
         .map do |k|
           [
             k['kid'],
             OpenSSL::X509::Certificate.new(
               Base64.decode64(k['x5c'].first)
             ).public_key
           ]
         end
       ]
     end
    end
    
```

  3. Modificar app/controllers/concerns/secured.rb



**app/controllers/concerns/secured.rb **
``` 
    module Secured
     def authenticate_user!
       # Obtener el current user del metodo user_from_token y retornar en caso de que la operacion sea
       # exitosa
       if(Current.user = user_from_token)
         return
       end
       # En caso de que no se obtenga un usuario, retornar 401
       render json: {error: 'Unauthorized'}, status: :unauthorized
     rescue JWT::VerificationError, JWT::DecodeError
       # En caso de que haya un error de validacion del token, retornar 401
       render json: {error: 'Unauthorized'}, status: :unauthorized
     end
    
     def user_from_token
       # Obtener el token del header Authorization
       token = get_token_from_auth_header
       # Utilizar JsonWebToken para verificar y validar el token
       payload = JsonWebToken.verify(token).first.with_indifferent_access
       if payload.present?
         # Si existe un token buscamos un usuario con el email contenido en el token.
         # Si todavia no existe un usuario con este email, se crea usando el metodo `find_or_create_by`
         # de ActiveRecord.
         User.find_or_create_by(email: payload[:email]) do |user|
           user.name = payload[:name]
         end
       end
     end
    
     def get_token_from_auth_header
       # IMPORTANTE! cambiar el regex que teniamos antes. Como JWT incluye puntos, el regex anterior
       # no tenia encuenta puntos.
       token_regex = /Bearer (.+)/
       # leer HEADER de auth
       headers = request.headers
       if headers['Authorization'].present? && headers['Authorization'].match(token_regex)
         headers['Authorization'].match(token_regex)[1]
       end
     end
    end
    
```

  4. Hacer que rails cargue el contenido de la carpeta “app/lib/”



**config/application.rb**
``` 
    require_relative 'boot'
    
    require "rails"
    # requires ...
    module Blogapi
     class Application < Rails::Application
       # otras cosas ...
       config.eager_load_paths << Rails.root.join('app/lib')
       # ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
     end
    end
    
```

  5. Opcionalmente actualizar el modelo User y sus pruebas para remover la autenticación que implementamos previamente



## Probando con Postman

  1. Inicia el servidor con rails s.
  2. Ve a localhost:3000/login, haz login y copia el token que aparece el [jwt.io](http://jwt.io).
  3. Abre postman y usando los mismos requests que creamos previamente modifica el header “Authorization” para que quede con el formato “Bearer ”
  4. Ejecuta el request y debes ver algo parecido a esto.

![Captura de pantalla 2019-01-09 a la\(s\) 13.52.19.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-09%20a%20la%28s%29%2013.52.19-81642edb-a169-4ac2-9471-64773e37822d.jpg)

Felicitaciones! Ya tienes un API que hace autenticación con un JWT creado por Auth0. Ahora solo falta pulir un par de detalles.

## Arreglar los tests

<https://github.com/simon0191/platzi-curso-rails-apis/commit/cfad808cc1b37074370c4eace2bf9a6bf3490bae>

Si removiste la generación de tokens inicial, las pruebas deben estar fallando. Debemos modificarlas para hacer que utilicen la librería JsonWebToken que implementamos.  
En nuestro caso debemos hacer un mock de JsonWebToken y hacer que no se ejecute la lógica de validación del token sino que se retorne siempre los datos del usuario del que estamos interesados en la prueba. Para esto usamos las funcionalidades de mocking de RSpec.

**mocks en RSpec**
``` 
    before { allow(JsonWebToken).to receive(:verify).and_return([{email: user.email}]) }
    
```

Con esta línea estamos instruyendo a RSpec para que intercepte todos los llamados al método “verify” de la clase JsonWebToken y retorne “[{email: user.email}]”.

Una vez hecho esto en las pruebas necesarias ejecuta bundle exec rspec y todas las pruebas deben pasar.

## Usar Secrets de rails 5

Finalmente vamos a utilizar una funcionalidad nueva de rails 5 para incluir secretos o información sensible en el código de nuestra aplicación sin necesidad de exponerlos en el repositorio.

En versiones anteriores de rails, se solía incluir un archivo llamado secrets.rb en donde se incluían cosas como API keys y contraseñas que se necesitaban para integración con otros servicios. Estaba a discreción del equipo de desarrollo omitir este archivo del repositorio de código para que no todos los desarrolladores tuvieran acceso a esta información. Para solucionar esto normalmente se compartian estos secrets usando manejadores de contraseñas como LastPassword o simplemente se compartia en un archivo de google drive. En cualquier caso, no era práctico porque los desarrolladores debían actualizar este archivo manualmente en su entorno de desarrollo.

En rails 5 se introdujo la posibilidad de incluir un archivo encriptado con todos los secrets para que así, esta información sensible pueda ser parte del repositorio de manera segura. Para ello se usa el comando “rails credentials:edit” que abre un editor de texto con un archivo en donde puedes incluir los secrets en formato YAML. Opcionalmente se puede especificar el editor de código que prefieras. Por ejemplo:

* Para usar VScode: `EDITOR="code --wait" rails credentials:edit`
* Para usar Sublime: `EDITOR="subl --wait" rails credentials:edit`
* Para usar vim: `EDITOR="vim" rails credentials:edit`



Este comando va a crear una llave de encripción en el archivo config/master.key y un archivo temporal que vas a poder editar y guardar y que se va a abrir con el editor que especificaste. Una vez guardes el archivo y cierres el editor, rails va a encriptarlo usando master.key en el archivo config/credentials.yml.enc. El archivo master.key debe ser tratado con cautela y no debe ser incluido en el repositorio. Si usas git, rails por defecto genera el archivo gitignore necesario para ignorar este archivo. Sin embargo debes guardar esta llave en un manejador de contraseñas u otro servicio de almacenamiento seguro en donde puedas compartirlo con tu equipo. Si pierdes este archivo no vas a poder desencriptar el contenidod e credentials.yml.enc. Por otro lado, el archivo credentials.yml.enc puede ser incluido en el repositorio pues está encriptado. Para que la aplicación lo pueda desencriptar, debe estar presente la llave en config/master.key o en la variable de entorno RAILS_MASTER_KEY. Por ejemplo:

RAILS_MASTER_KEY=xxxxxxx rails server

De esta manera puedes hacer uso de esta funcionalidad en servicios de despliegue como Heroku sin necesidad de incluir la llave en el repositorio.

Ahora, en nuestro caso la información que podemos incluir en este archivo es la información relacionada a Auth0: client_id y auth0_domain.

Ejecuta _EDITOR=“code --wait” rails credentials:edit_ y agrega esta información:

**credentials.yaml**
``` 
    # Otras cosas ...
    auth0:
     domain: .auth0.com
     client_id: 
    
```

Guarda y cierra el archivo.

Ahora sigue los cambios en <https://github.com/simon0191/platzi-curso-rails-apis/commit/68e421bb7eb6fd0b11836523a22fa11520d96f6d> ignorando los cambios a _config/credentials.yml.enc_

### Comentarios:

* **Jean Carlos Nuñez Hernandez** (2) [582754](https://platzi.com/comentario/582754/) 

	rails credentials:edit -> esto no lo habia visto en un framework como laravel o flask, esta muy interesante

* **reneclavijo** (1) [60488](https://platzi.com/comentario/606231/) 
Gracias por la implementación a través de Auth0, pero tengo unas preguntas: ¿ Lo que se implementó sería un JWT firmado encripta...

# Cierre [3160]

## 0330. Cierre del curso [16037](https://platzi.com/clases/1440-ror/16037-cierre-del-curso1564/)

### Descripción:


### Comentarios:

* **jjjericu** (2) [494168](https://platzi.com/comentario/494168/) 

	muy buen curso!!

* **Victor Manuel Franco Cañon** (2) [467403](https://platzi.com/comentario/467403/) 

	Muy buena metodología, excelente profesor, aunque en algunas ocasiones me hubiera gustado la clase con una especie de texto guía o con información adicional sobre lo que se estaba enseñando.

* **joranboc** (2) [464361](https://platzi.com/comentario/464361/) 

	Excelente profesor, simon explica muy bien y excelente que agregaran cosas como los Mailer y los Jobs

* **camilorc1129** (1) [1000890](https://platzi.com/comentario/1000890/) 

	Hola a todo el curso estuvo muy interesante y completo para empezar en este mundo de Ruby, me gustaria saber ahora para complementar el blog agregando el front end, que framework me sugieren usar que trabaje bien con rails, yo he pensado en React.js, es posible?o cual se acopla mas con Ruby on Rails?

* **Cesar Gonzalez Leyba** (1) [791650](https://platzi.com/comentario/791650/) 

	Increible profesor, explico muy bien los temas ademas que se nota que tiene un conocimiento realmente profundo de la tecnologia, mas cursos con el de ser posible =)

* **Kiel Rodríguez** (1) [525600](https://platzi.com/comentario/525600/) 

	Me gusto mucho, excelente curso!!

* **Iris Castillo** (1) [76947](https://platzi.com/comentario/895723/) 
cree una api … y quiero publicarla en un servidor (hosting contratado que se administra a través de cpanel). pero no he podido acceder a ...

	* **Krystle Salazar** [76947] (1)

		¿Has probado [Heroku](https://heroku.com/)?

