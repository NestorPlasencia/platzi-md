# Introducción

## 0010. Angular 8 Performace

### Descripción:


### Comentarios:

* **darwinyusef** (3)

	
	Soy el primer comentario que cool 😄

* **ehnbytes** (1)

	
	Wow, !!!

* **Harold López Ancar** (1)

	
	Esto se viene bueno!

# Analizando el tamaño del Bundle

## 0020. ¿Qué es un bundle size Tree shaking y su importancia

### Descripción:


### Comentarios:

* **Carlos Eduardo Jaramillo Franco** (4)

	
	Uh creo que están en desorden los vídeos, pues usamos webpack-bundle-analyzer en el video anterior.

* **Jean Alvarez** (1)
Dinamyc Routes Hola me podrías ayudar para implementar dinamyc routes en angular.Quiero por medio del backend , definir los nombres de la...

	* **nicobytes** (1)

		
		Hola!
		
		Quisiera saber el caso en especifico ya que no es común que quieras a partir del backend generar rutas al frontend, al final son dos sistemas aparte que comunican datos a través de un web service.
		
		Así que cada ruta ya tiene el componente que renderiza, parametros que recibe y guards.

## 0030. Implementando Webpack Bundle Analyzer

### Descripción:


### Comentarios:

* **kikekeys** (3)

	
	Si te da un error tipo:` Bundle analyzer Error: listen EADDRINUSE :::8888
	
	Hay de dos:
	
	  * o matas el proceso con kill -9 <PID>
	  * o le pasas por parámetro el puerto, uno distinto al que te marque en uso, ejemplo: `npx webpack-bundle-analyzer -p 1234 dist/YourProjectName/stats-es2015.json`
	
	
	
	Eso funcionó para mi, decía que tenía el puerto 8888 ocupado y primero lo maté el proceso y después intenté con correr en otro puerto, me quedé con la segunda, porque el 8888 lo usa vscode con git.
	
	Fin del comunicado, deje su buen laic.

* **Jean Carlos Nuñez Hernandez** (2)

	
	waaaaao esto es muy bueno para mi Ya!!! lo voy a implementar

* **Alexis Otaño** (2)

	
	Uhhh esto yo lo hice hace un montón de tiempo! Y siempre que queria ver por que pesaba tanto tengo que ir a buscar “Como era que hacia?”, 😂 Ahora voy a tener una guía de como hacerlo paso a paso ! Genial este curso! Muchas gracias!

* **JAVIER ENRIQUE CHARRIS MOLINA** (1)

	
	Genero el ng build --prod --stats-json  
	Pero no me esta generando el archivo stats-es2015.js

* **vladernn** (1)

	
	El webpack bundle analizer nos permite ver visualmente que archivos del proyecto son los que están pesando más.

## 0040. Moment vs date-fns

### Descripción:


### Comentarios:

* **vladernn** (2)

	
	Con [bundlephobia.com](http://bundlephobia.com) podemos comparar librerias y utilizar las más convenientes para el peso de nuestro app con lo consiguiente reduciendo el tiempo de carga de la misma.

	* **Nathaly Stefani Riaño Bejarano** (1)

		
		Súper! Gracias 👍

* **Carlos Eduardo Jaramillo Franco** (1)

	
	Por qué usar date-fns y no dayjs que es mucho más pequeña?

	* **Henderson Said Franco Cruz** (1)

		
		X2

	* **Julio Izquierdo** (1)

		
		Depende la elección que hagas como desarrollador y también depende de las necesidades que tengas de implementación en tu proyecto.

* **Henderson Said Franco Cruz** (0)

	
	Que extensión utilizas para ver el peso de los que estas importando? Saludos.

	* **Nathaly Stefani Riaño Bejarano** (3)

		
		La extensión se llama [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

## 0050. Aplicando un Performance Budget desde el Angular CLI

### Descripción:


### Links:

* [Performance Budget Calculator](https://perf-budget-calculator.firebaseapp.com/)

### Comentarios:

* **Julio Izquierdo** (1)
Entiendo, en algun momento he leido sobre microfrontends. Tienen pensando o han investigado del tema para crear un curso sobre esto? En a...

	* **Massimo Di Berardino** (2)

		
		Hola @jeio1990 la semana pasada en una Plazti Session Oscar Barajas del equipo de Platzi hablo de esto y dijo que estaban en analizando sacar algún curso de esto en un futuro!

* **Julio Izquierdo** (1)
¿Que pasa cuando una aplicación angular crece demasiado a medida que va creciendo tu producto, como solucionar el no seguir agregando com...

	* **nicobytes** (1)

		
		A medida que la app crece es inevitable que se creen más y más componentes y una que otra lib.
		
		Lo recomendable es que dividas tu app en módulos y así fragmentas ese peso en módulos.

# Aumenta la velocidad de navegación

## 0060. Code splitting a nivel de rutas

### Descripción:


### Comentarios:

* **vladernn** (1)

	
	 **Angular budget** nos permite colocar limites de peso a nuestra app para que no pese excesivamente

* **Alexis Otaño** (1)
Waaa menpartio la cabeza lo de mL para pre carga!!! Ya quiero llegar a eso

* **Julio Izquierdo** (1)
La idea es tener diferentes servicios por pequeñas aplicaciones angular donde solo tenga una breve logica a mostrar y no una super aplica...

	* **nicobytes** (1)

		
		En este caso de permisos y seguridad puedes controlar los accesos a cada ruta y módulo.
		
		Las rutas tienen eventos como `CanActive` con el que según el permiso puedes cargar o no esa ruta es la forma en la que se hace normalmente depende al rol se puede mostrar esa ruta.
		
		Cargarlos dinámicamente no es posible de forma fácil en Angular no esta pensado para esto. Ya que deben estar definidas al momento de crear al app.

* **Julio Izquierdo** (1)
¿Los módulos los podría tener en un server distinto a donde está desplegada la aplicación? ej: import ('http://**ip-server**:**port...

	* **nicobytes** (1)

		
		Hola! en teoría si lo puedes hacer ya que lo que genera `ng build` son archivos estáticos (js, html y css) y tu los despliegas donde quieras.
		
		Sin embargo en recomendable que estén en un solo server por seguridad y por menor latencia.
		
		También puedes usar un CDN que lo que hace es distribuir esos archivos estáticos en varios servers en el mundo de forma segura y el server que es más cerca a tus usuarios es el que responde.
		
		Ahora no se cual sea tu caso, cuéntanos en los comentarios.

## 0070. Implementando una propia estrategia de precarga

### Descripción:


### Links:

* [Intersection Observer API - Web API reference | MDN](https://developer.mozilla.org/es/docs/Web/API/Intersection_Observer_API)

* [GitHub - mgechev/ngx-quicklink: Quicklink prefetching strategy for the Angular router](https://github.com/mgechev/ngx-quicklink)

### Comentarios:

* **Alexis Otaño** (4)

	
	Les cuento que esto también funciona con child modules, es decir, la estrategia se debe de declarar en el app.module pero cualquier modulo hijo también es afectado solo que tenga la metadata.

* **Jorge Antonio Castillo Moreno** (2)

	
	Interesante yo en mis proyectos he implementado solamente la primera opcion…  
	Buen curso

* **luisgv94** (1)

	
	Excelente clase, ya todo tiene mucho más sentido. Arriba la cuarentenaaaaa

* **Carlos Nicolas Erices Mendez** (1)

	
	que buen curso.

* **johnsalas** (1)

	
	El ejemplo es muy bueno, lo acabo de implementar en mi sistema donde precargo de acuerdo con el tipo de usuario y está funcionando muy bien, gracias.

* **vladernn** (1)
Entiendo yo que esto se puede sofisticar mucho como por ejemplo precargar los módulos en función de la ruta que nos ha llegado.

	* **nicobytes** (1)

		
		Hola! si solo que ya lo debes hacer tu usando tu propia estrategia de precarga, en el curso vimos tres que son muy prometedoras y sirven en la mayoría de los casos.

## 0080. Implementando QuicklinkStrategy

### Descripción:


### Comentarios:

* **juanbarcinilla** (2)

	
	Muy buena implementacion

* **Andres Gallardo** (1)

	
	Muy bueno !

* **johnsalas** (1)

	
	Si tengo mi menú de hamburguesa en la esquina superior izquierda con todos los links de opciones a diferentes módulos estos también se cargan.

* **tzalejo** (1)
Buenas coders…consulta hay alguna forma de comparar las distintas estrategias?? Saludos

	* **nicobytes** (2)

		
		Hola! no tienen una comparativa clara ya que todas tiene diferentes casos de uso, en resumen lo podría compararla según el caso de uso:
		
		Selective Strategy: Para apps y una cantidad de usuarios no muy grande, en donde tu tienes conocimiento de el navegador y velocidad que van tener tus usuarios.
		
		QuickLink: En caso anterior pero no sabes que navegador y que velocidad van a tener los usuarios.
		
		GuessJS: Cuando quieres mejorar la carga de una forma mucho más avanzada pero debes tener tracking de Google Analytics.

## 0090. Usando Machine Learning para predecir rutas

### Descripción:


### Comentarios:

* **Nathaly Stefani Riaño Bejarano** (2)

	
	Las cadenas de Markov permiten visualizar cada una de las probabilidades que se tienen en la navegación de la aplicación. Evalúa la probabilidad que tiene cada una de las vistas de la aplicación frente a un comportamiento previo de los usuarios, generando un modelo de predicción de precarga de módulos, con el fin de mejorar el rendimiento y la experiencia de usuario mientras navega por la aplicación web desarrollada,

* **vladernn** (1)

	
	Precarga modulos en función de la probabilidad que hay de ir del nodo actual al nodo siguiente siendo los nodos modulos.

## 0100. Google Analytics y Angular

### Descripción:


### Links:

* [Redirecting...](https://analytics.google.com/)

### Comentarios:

* **Giovanny Contreras Muñoz** (1)

	
	Buen Curso 😃

## 0110. Implementando GuessJs

### Descripción:


### Links:

* [GitHub - guess-js/guess: Libraries & tools for enabling Machine Learning driven user-experiences on the web](https://github.com/guess-js/guess)

### Comentarios:

* **Jaiden Meiden** (5)

	
	Al día de hoy, al parecer el error que se presentaba con rutas anidadas, ya fue solucionado y el proyecto pudo ser compilado para producción correctamente.

* **luisgv94** (2)

	
	Lo raro es que google no me da el permiso para acceder a mi cuenta de gmail. A alguien le pasa lo mismo?

	* **Duvan Gonzalez** (1)

		
		Si, igual  
		**Se ha inhabilitado temporalmente el inicio de sesión con Google en esta aplicación**

* **tzalejo** (2)

	
	Es una excelente herramienta, menos mal que ya fue solucionada para rutas anidadas!..  
	Saludos

* **JandroMejia** (2)
El problema de rutas anidadas ya está resuelto, pero ahora Google impide autenticarte en esta aplicación.

* **softpymes** (1)

	
	Esta configuración no afecta ivy?

* **Diego Mantelli** (1)

	
	Muy buena herramienta! Es excelente!!

## 0120. Precarga con Services workers

### Descripción:


### Links:

* [Angular](https://angular.io/guide/service-worker-getting-started)

### Comentarios:

* **tzalejo** (7)

	
	Para aquellos que quieran usar el servidor http: [link](https://www.npmjs.com/package/http-server)
	``` 
	     npm installhttp-server -g
	    
	```
	
	Saludos…

* **veronica oviedo** (3)

	
	Consejo: Al probar a los service workers, es una buena idea usar una ventana de incógnito o privada en su navegador para asegurarse de que el trabajador de servicios no termine leyendo de un estado anterior, lo que puede causar un comportamiento inesperado.

## 0130. ¿Qué es Server Side Render

### Descripción:


### Comentarios:

## 0140. Implementando Angular Universal

### Descripción:


### Links:

* [Angular](https://angular.io/guide/universal)

* [Curso Profesional de Angular](https://platzi.com/clases/angular-profesional/)

* [GitHub - angular/universal: Universal javascript support for Angular](https://github.com/angular/universal)

### Comentarios:

* **Carlos Eduardo Jaramillo Franco** (2)

	
	Hola, si alguno está siguiendo el tutorial con angular 8 le fallará cuando intentan compilarlo porque todavía no hay soporte de express-engine para angular 8.  
	Si quieren de igual manera hacerlo, deben desactivar el “enableIvy” en “angularCompilerOptions” en los archivos tsconfig.app.json y en tsconfig.json! saludos

* **basanchez** (1)

	
	Que dolor de cabeza es pasar una app a SSR. Lo importante es que eso vaya dentro de la planeación del proyecto para prevenir la mayor cantidad de errores posible. Ya después con el tiempo le agarras la onda a lo que debes de cuidar.

* **Manuel Andrade** (1)
Como puedo usar SSR en mi servidor de cpanel??? Falto este tema en este módulo.

	* **nicobytes** (1)

		
		Hola, para esto necesitas NodeJs corriendo en tu servidor.
		
		Un Cpanel es muy limitado, ya que viene con la formula LAMP (Linux, Apache, Mysql y PHP) por defecto y es complejo cambiarlo, debes hablar con tu proveedor.
		
		Te recomiendo mejor un instancia en donde tu tengas total control y puedas instalar node y lo que sea.
		
		Te recomiendo DO (Digital Ocean) para iniciar tiene maquinas desde 5 USD.
		
		Heroku también es un excelente opción si quieres iniciar mucho más rápido.

## 0150. Cuidados con SSR y Angular

### Descripción:


### Comentarios:

* **Manuel Andrade** (1)
Como puedo usar SSR en mi servidor de cpanel??? Falto este tema en este módulo.

	* **nicobytes** (1)

		
		Hola, para esto necesitas NodeJs corriendo en tu servidor.
		
		Un Cpanel es muy limitado, ya que viene con la formula LAMP (Linux, Apache, Mysql y PHP) por defecto y es complejo cambiarlo, debes hablar con tu proveedor.
		
		Te recomiendo mejor un instancia en donde tu tengas total control y puedas instalar node y lo que sea.
		
		Te recomiendo DO (Digital Ocean) para iniciar tiene maquinas desde 5 USD.

* **Rafael Larco Buchelli** (1)
Pese a colocarlo dentro del condicional isPlatform tengo problemas con el localstorage. Me salta el siguiente error: ERROR { Error: Uncau...

	* **nicobytes** (1)

		
		Hola! al parecer tu SSR no esta funcionando muy bien por que toma el localstorage como parte del código del server nos puedes mostrar como estas haciendo el uso de `isPlatform` ?

* **andresgiraldolondono** (0)

	
	Nico, excelente clase pero me quedo una duda, dices que al ejecutar los comandos de SSR serve:ssr, build:ssr se levanta un servidor NODEJS en el puerto 4000, como seria entonces el proceso para llevar una aplicación con SSR a producción? cambiaría algo o seria igual?

	* **basanchez** (1)

		
		Te comparto mi experiencia: tengo un proyecto de SSR en un servidor Ubuntu con un proxy inverso de NGINX. Tu pones la configuración para que cuando se haga una solicitud al puerto 80 tome lo que hay al puerto 4000 (por ejemplo).

	* **basanchez** (1)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-1c4e72df-9278-4c81-9b7d-b9711800627c.jpg)
		
		Algo mas o menos de este estilo.

# Rendimiento en tiempo de ejecución

## 0160. ¿Qué es el Change Detection

### Descripción:


### Comentarios:

* **veronica oviedo** (3)

	```
	    export class GeneratorService {
	    
	      generate(labels: string[], numRange: [number, number], width: number): EmployeeData[] {
	        constresult: EmployeeData[] = [];
	        for (let i = 0; i < width; i += 1) {
	          result.push(this.generateNode(labels, numRange));
	        }
	        returnresult;
	      }
	    
	      generateNumber(numRange: [number, number]) {
	        const diff = numRange[1] - numRange[0];
	        return numRange[0] + Math.floor(Math.random() * diff);
	      }
	    
	      generateLabel(labels: string[]) {
	        return labels[Math.floor(Math.random() * labels.length)];
	      }
	    
	      private generateNode(labels: string[], numRange: [number, number]): EmployeeData {
	        return {
	          label: this.generateLabel(labels),
	          num: this.generateNumber(numRange)
	        };
	      }
	    }```
	    
	```

* **veronica oviedo** (2)

	
	Se les olvido poner el link al github para traer el generator-service.ts

* **Jessie Buckland Pérez** (1)

	
	La detección de cambios es un concepto que puede que desconozcas, te recomiendo ir rápidamente al vídeo de "Optimización de componentes con OnPush" en donde se explica inicialmente las dos listas de datos con funciones y carga de datos aleatorios utilizados para explicar esto.

## 0170. Preparando módulo para Change Detection

### Descripción:


### Comentarios:

## 0180. Analizando el Change Detection

### Descripción:


### Comentarios:

## 0190. Optimización de componentes con OnPush

### Descripción:


### Links:

* [fibonacci.ts · GitHub](https://gist.github.com/nicobytes/e86c416f927182829f55bc0a02e29c3a)

### Comentarios:

* **Ricardo Exequiel De Angelis** (1)

	```
	    ERROR in src/app/website/contact/components/list/list.component.ts:17:20 - error NG1010: changeDetection must be a member of ChangeDetectionStrategy enum from @angular/core
	    
	    17   changeDetection: ChangeDetectionStrategy.OnPush
	                          ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	    src/app/website/contact/contact.module.ts:12:9 - error NG6001: The class 'ListComponent' is listed inthe declarations ofthe NgModule 'ContactModule', butisnot a directive, a component, or a pipe. Either remove itfromthe NgModule's declarations, or add an appropriate Angular decorator.
	    
	    12         ListComponent
	               ~~~~~~~~~~~~~```
	    
	    Para los que tengan este error solo corrijan el import de changeDetectionStrategy debe ser de angularCore
	    
	```

## 0200. Usando pipes puros

### Descripción:


### Comentarios:

* **Andres Gallardo** (1)

	
	Excelente ! Siempre pense que nunca iba a usar pipes jaja

## 0210. subscribe

### Descripción:


### Comentarios:

* **veloz21** (10)

	
	Una mejor práctica para desuscribirte de tus suscripciones, es usar el operator de rxjs takeUntil, que mantiene activa las suscripciones de la aplicación hasta que otro observable emita.  
	Eso sirve cuando tienes muchas suscripciones en tu componente, para evitar tener un unsuscribe por cada suscripción, además de prevenir que se te olvide agregar el unsuscribe de alguna.
	
	Un ejemplo es el siguiente:
	``` 
	    export class UnsubscribeComponent implements OnInit, OnDestroy {
	    
	      value1: number;
	      value2: number;
	      value3: number;
	    
	      subscribe1: Subscription;
	      subscribe2: Subscription;
	      subscribe3: Subscription;
	      private ngUnsubscribe = new Subject();
	      constructor() { }
	    
	      ngOnInit() {
	        this.subscribe1 = interval(1000).pipe(
	          takeUntil(this.ngUnsubscribe)
	        ).subscribe(value => {
	          this.value1 = value;
	        });
	    
	        this.subscribe1 = interval(1000).pipe(
	          takeUntil(this.ngUnsubscribe)
	        ).subscribe(value => {
	          this.value2 = value;
	        });
	    
	        this.subscribe1 = interval(1000).pipe(
	          takeUntil(this.ngUnsubscribe)
	        ).subscribe(value => {
	          this.value3 = value;
	        });
	      }
	    
	      ngOnDestroy() {
	        this.ngUnsubscribe.next();
	        this.ngUnsubscribe.complete();
	      }
	    
	    }
	    
	    
	```

	* **Cristian Mota Núñez** (1)

		
		Puedes eliminar estas lineas de codigo ya que no se utilizan y pueden generar confusion. Muy buen aporte por cierto 😃
		``` 
		    subscribe1: Subscription;
		    subscribe2: Subscription;
		    subscribe3: Subscription;
		    this.subscribe1 
		    
		```

* **Johan Sebastia Medina Camacho** (1)
Una pregunta si yo creo una variable de tipo observable para almacenar una petición http (que en teoría se auto de-suscribe) si yo poster...

	* **nicobytes** (1)

		
		Estas en lo correcto si guardas esto como como un observable que viene de httpClient ella completa la suscripción, así que en esa variable no tienes por preocuparte por esto.

## 0220. Async

### Descripción:


### Comentarios:

* **NINO DAVID SIMEON HUACCHO** (2)
¿Hay forma alguna de que el código lo suban a un repositorio público? intento bajarlo desde la sección Archivos/Enlaces y es tedioso hace...

	* **Juan David Castro (Platzi)** (2)

		
		Psssss…
		
		😮 <https://github.com/nicobytes/platzi-store-pro>

# Conclusiones

## 0230. Conclusiones

### Descripción:


### Comentarios:

